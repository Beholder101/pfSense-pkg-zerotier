# pfSense-pkg-zerotier
pfSense package to support zerotier, forked from ChanceM. 

## Changes
Added MTU Size and Route info to controller page.
Corrected display of Controller IP Pools start and end info

## ToDo
Correct display of Active Members, Authorized Members and Total Members

## Install
1. Build [zerotier](https://github.com/zerotier/ZeroTierOne) dev branch, or better yet, get it from /usr/ports/zerotier.
2. Copy these files and build on FreeBSD.
3. SCP to pfSense
4. Run `pkg add pfsense-pkg-zerotier-1.0.txz`
5. Run `Service zerotier start`
