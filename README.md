## SwiFTP is dead, long live SwiFTP

An FTP Server for your android device.

----------

I (Dave) don't have time to maintain SwiFTP, and since it's a few years since the last update, I'm declaring it dead. However, Pieter Pareit has forked a new version at http://ppareit.github.com/swiftp/ with some badly needed interface improvements.

### Description

This program allows you to run an ftp server on your android device. This means that any program can access the files on your device while the ftp server is running. For example, entering 'ftp://...' in the firefox url bar will allow you to browse the files on your device from a desktop pc or a laptop.
By default, the user name and password are both 'ftp', you should change them. You use this username and password when accessing the server.

There is a configuration option ("keep phone awake") that fixes a problem where file transfers go slow or stop completely when the phone sleeps. If you have this problem, check this box and restart SwiFTP. Your phone will stay awake as long as the server is running.

For power and security reasons, it is recommended that the server be stopped after use.

### Screenshots

![](https://github.com/shenhuanet/swiftp/raw/master/screenshots/mainscreen_1.22.png)

![](https://github.com/shenhuanet/swiftp/raw/master/screenshots/config_1.22.png)
