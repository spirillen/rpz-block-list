# rpz-block-list

<img src="https://github.com/spirillen/rpz-block-list/blob/master/.assets/badd-boyz-hosts.jpg" alt="Badd Boyz Hosts File to Protect Your Computer and Devices Against Bad Web Sites"/><img src="https://github.com/spirillen/rpz-block-list/blob/master/.assets/spacer.jpg"/>[![Build Status](https://travis-ci.org/spirillen/rpz-block-list.svg?branch=master)](https://travis-ci.org/spirillen/rpz-block-list)<img src="https://github.com/spirillen/rpz-block-list/blob/master/.assets/spacer.jpg"/>[![GitHub Stats](https://img.shields.io/badge/github-stats-ff5500.svg)](http://githubstats.com/spirillen/rpz-block-list)<img src="https://github.com/spirillen/rpz-block-list/blob/master/.assets/spacer.jpg"/>

A hosts file for use on any operating system to block bad domains out of your servers or devices.

* Here's the [RAW hosts file](https://raw.githubusercontent.com/spirillen/rpz-block-list/master/hosts)

- Copyright: https://github.com/mitchellkrogza

_______________
[![VERSION](https://img.shields.io/badge/VERSION%20-%20V1.2018.12.7425-blue.svg)](https://github.com/spirillen/rpz-block-list/commits/master)
#### Bad Host Count: 3642
```
# File generated by https://github.com/funilrys/PyFunceble
# Date of generation: Mon 03 Dec 07:12:13 SAST 2018 

Status      Percentage   Numbers     
----------- ------------ ------------
ACTIVE      99%          3642        
INACTIVE    0%           8           
INVALID     0%           0           
```
____________________

- You are free to copy and distribute this file for non-commercial uses, as long the original URL and attribution is included.

************************************************
# DOMAIN ADDITIONS FALSE POSITIVES / DOMAIN REMOVALS / OTHER ISSUES: 

Please forward any additions, corrections or false positives by:

[![Log an Issue](https://img.shields.io/badge/LOGGING%20-%20an%20issue%20%F0%9F%9A%A6-blue.svg)](https://github.com/spirillen/rpz-block-list/issues) 

or send a PULL REQUEST on the [domains.txt](PULL_REQUESTS/domains.txt) file in the PULL_REQUESTS folder. 

************************************************
## COMPILED FROM:

This list of hosts is compiled from real server logs on my own servers where I run a number of very busy web sites. 

This list originated from the list of bad referrers domain lists for:

[![NGINX ULTIMATE BAD BOT BLOCKER](https://img.shields.io/badge/NGINX%20-%20ULTIMATE%20BAD%20BOT%20BLOCKER%20%E2%9B%94-blue.svg)](https://github.com/mitchellkrogza/nginx-ultimate-bad-bot-blocker)
or [![Get the APACHE ULTIMATE BAD BOT BLOCKER](https://img.shields.io/badge/APACHE%20-%20ULTIMATE%20BAD%20BOT%20BLOCKER%20%E2%9B%94-blue.svg)](https://github.com/mitchellkrogza/apache-ultimate-bad-bot-blocker)

The list has now been separated from those projects as it contains certain domains which do not actually belong in a hosts file.

************************************************
## WHAT IS A HOSTS FILE?

A hosts file, named `hosts` (with no file extension), is a plain-text file
used by all operating systems to map hostnames to IP addresses.

In most operating systems, the `hosts` file is preferential to `DNS`.
Therefore if a domain name is resolved by the `hosts` file, the request never
leaves your computer.

Having a smart `hosts` file goes a long way towards blocking malware, adware, ransomware, porn and other nuisance web sites.

A hosts file like this causes any lookups to any of the listed domains to resolve back to your localhost so it prevents any outgoing connections to the listed domains.

************************************************
## WHERE DO I PUT THIS ON MY COMPUTER?
To modify your current `hosts` file, look for it in the following places and modify it with a text
editor.

**Linux, Mac OS X, iOS, Android**: `/etc/hosts` folder.

**Windows Systems**: `%SystemRoot%\system32\drivers\etc\hosts` folder.

************************************************
## UNDERSTANDS PUNYCODE / IDN DOMAIN NAMES
A lot of lists out there put funny domains into their hosts file. Your hosts file and DNS will not understand this. This list uses converted domains which are in the correct DNS format to be understood by any operating system.

For instance
The domain:

`lifehacĸer.com` (note the K)

actually translates to:

`xn--lifehacer-1rb.com`

You can do an nslookup on any operating system and it will resolve correctly.

`nslookup xn--lifehacer-1rb.com`

```xn--lifehacer-1rb.com
	origin = dns1.yandex.net
	mail addr = iskalko.yandex.ru
	serial = 2016120703
	refresh = 14400
	retry = 900
	expire = 1209600
	minimum = 14400
xn--lifehacer-1rb.com	mail exchanger = 10 mx.yandex.net.
Name:	xn--lifehacer-1rb.com
Address: 78.110.60.230
xn--lifehacer-1rb.com	nameserver = dns2.yandex.net.
xn--lifehacer-1rb.com	text = "v=spf1 redirect=_spf.yandex.net"
xn--lifehacer-1rb.com	nameserver = dns1.yandex.net.
```

- Look at: https://www.charset.org/punycode for more info on this.

************************************************
## Contributors

- Nissar Chababy - https://github.com/funilrys/PyFunceble (Excellent script for checking ACTIVE, INACTIVE and EXPIRED Domain Names)

************************************************
## Support this Project

[![Help me out with a mug of beer](https://img.shields.io/badge/Help%20-%20me%20out%20with%20a%20mug%20of%20%F0%9F%8D%BA-blue.svg)](https://paypal.me/mitchellkrog/)


************************************************

