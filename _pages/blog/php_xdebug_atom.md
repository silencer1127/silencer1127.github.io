---
title: "Blog"
category: "main"
permalink: /blog/php_xdebug_atom
layout: single
author_profile: true
date: 2018-09-21
---

## How to debug PHP code using xdebug in Atom

First of all, we assume an apache server with php > 7.0 is installed. If not, [LAMP](https://bitnami.com/stack/lamp){:target="lamp"}. is highly recommended from [Bitnami](https://bitnami.com/){:target="bitnami"}.

1. Install [xdebug](https://xdebug.org){:target="xdebug"}.

    xdebug comes with LAMP as an extension, no installation required. If not, for most Linux system, xdebug can be installed using the package management, e.g. apt-get install php-xdebug in Ubuntu

2. Configure php.ini

    * Append the following text to php.ini
    ```
    ;[XDebug]
    zend_extension="where_is_your_xdebug.so"
    xdebug.remote_enable=true
    xdebug.remote_host=127.0.0.1
    xdebug.remote_port=9000
    xdebug.remote_handler=dbgp
    xdebug.profiler_enable=1
    xdebug.profiler_output_dir=/tmp
    xdebug.remote_mode=req
    xdebug.remote_autostart=true
    xdebug.idekey=xdebug-atom
    ```

    * In LAMP, just uncomment those lines in php.ini and add extra lines as needed.
    * Test whether xdebug is working or not
        * Don't forget to restart apache server
        * Create a new file under apache htdocs
        * Write `<?php phpinfo(); ?>` and save it
        * Load webpage in browser and you should see Xdebug enabled in zend engine section

3. Install [Atom](https://atom.io/){:target="atom"} and additional packages

    * Install Atom editor and click install under settings
    * Search and install [php-debug](https://atom.io/packages/php-debug){:target="php-debug"}, atom-debug-ui, ide-php
    * **NEVER** install atom-ide-ui when prompt (conflicting with php-debug, took me hours to figure this out)
    * Set a breakpoint in Atom and reload the page in browser, you should see the page loading paused and the line where the code stopped is highlighted



