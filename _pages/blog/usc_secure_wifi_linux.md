---
title: "Blog"
category: "main"
permalink: /blog/usc_secure_wifi_linux
layout: single
author_profile: true
date: 2018-09-21
---

## How to connect to the "USC Secure Wireless" under Linux

The followings are the simplied configurations (in Ubuntu or Linux Mint) stolen from here:

[http://flukylogs.blogspot.com/2014/12/connecting-to-usc-secure-wireless-on.html](http://flukylogs.blogspot.com/2014/12/connecting-to-usc-secure-wireless-on.html){:target="flukylogs"}

Connection Name: USC Secure Wireless

General:
* Auto-connect and user privilege are chosen as needed

WiFi:

* SSID: USC Secure Wireless
* Mode: Infrastructure
* BSSID: /\*left blank\*/
* Device MAC address: /\*left blank\*/
* Cloned MAC address: /\*left blank\*/
* MTU: automatic

WiFi Security:

* Security: WPA & WPA2 Enterprise
* Authentication: Protected EAP (PEAP)
* Anonymous identity: /\*left blank\*/
* CA certificate: (None)
* Inner authentication: GTC
* Username: "Your USC ID" (do **NOT** add @usc.edu here)
* Password:  "Your password" 

IPv4 Settings:

* Method: Automatic (DHCP)
* /\*left blank anywhere else\*/ 

IPv6 Settings:

* /\*left blank\*/
