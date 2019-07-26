---
title: "Blog"
category: "main"
permalink: /blog/matlab_17_before_libGL_issue
layout: single
author_profile: true
date: 2019-07-26
---

# How to fix a libGL issue for MATLAB version 2017 or earlier in Linux

## What's the problem?

I was trying to install a R2015a verson of MATLAB in Linux Mint 19 as there is a third-party package I'd like to use but it relies on the exact version (R2015a) of MALTAB. The installation and activation procedure was fine just as normal as other newer versions. However, when the first time I started MATLAB, it crashed immediately and quited. The error message returned was something like:
```
    libGL error: failed to load driver: swrast
    X Error of failed request:  BadValue (integer parameter out of range for operation)
    Major opcode of failed request:  154 (GLX)
    Minor opcode of failed request:  3 (X_GLXCreateContext)
    Value in failed request:  0x0
    Serial number of failed request:  36
    Current serial number in output stream:  39
    MATLAB is selecting SOFTWARE OPENGL rendering.
```

## Does this problem exist in any other version of MATLAB and/or Linux?

People also reported this issue in MATLAB version R2014a - R2017b, under Ubuntu and Debian.

## How to fix it

This issue is due to a conflict of c++ library between MATLAB built-in version and the os version.

1. Go to MATLAB directory:
```
    cd {MATLAB installation folder}/{MATLAB version}/sys/os/glnxa64
```

2. Move MATLAB c++ libraries to as backup
```
    mv libgcc_s.so.1 libgcc_s.so.1.bak
    mv libstdc++.so.6.0.17 libstdc++.so.6.0.17.bak
    rm libstdc++.so.6 (this is a link and will be overwritten anyway)
```
3. Find your OS c++ library: `ls /usr/lib/x86_64-linux-gnu/ | grep libstdc`
4. Create a link of OS c++ library in the MATLAB directory
```
    ln -sf /usr/lib/x86_64-linux-gnu/libstdc++.so.6.0.25 libstdc++.so.6
```

## Credits

Credits should be given to those smart people who posted their solutions in [https://www.mathworks.com/matlabcentral/answers/241374-libgl-error-persists-and-i-ve-tried-everything](https://www.mathworks.com/matlabcentral/answers/241374-libgl-error-persists-and-i-ve-tried-everything){:target="matlab-answer"}