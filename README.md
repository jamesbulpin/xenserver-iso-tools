xenserver-iso-tools
===================

Tools for creating XenServer ISOs

Live CD creator
---------------

A kickstart file to create a CentOS 6.4 based XenServer live CD. 

This requires a suitable version of livecd-tools, see
http://arrfab.net/blog/?p=324

To build: sudo livecd-creator --verbose --config=centos6-liveCD-xenserver.cfg --fslabel=XenServerLive --cache=/var/cache/live


