## ZClassic Windows Wallet 1.2 for Windows x64
#### (1-click installer, alpha, untested, don't use to store funds)

About
--------------

Based on https://github.com/z-classic/zclassic/releases/tag/1.1 - I'm trying to fix some issues with the Windows installer, v1.1 is almost 1Gb as it includes the large proving key, this installer is less than 100mb as it downloads the proving key if it's not found on the system.

I've also added a 1 click launcher based on zcash4win meaning that batch files no longer need to be used to start and stop the daemon, the aim is to make this as user friendly as possible. A minimal Java runtime is included also, so there should be no need for any extras to install.

This is untested, unfinished and probably won't download the blockchain as it uses old peer information from github. The peer info is hardcoded at the moment. The intention is to change this in future so it download peer info on launch.

Only use for testing, don't store ZCL on this wallet, it's untested right now.

I recommend VirtualBox to test install:

https://www.virtualbox.org/wiki/Downloads

Use the Microsoft provided Windows 10 x64 image from here:

https://developer.microsoft.com/en-us/microsoft-edge/tools/vms/

You can the use snapshots feature to put the VM in a previous state.

Install
-----------------

### Windows
Download zclassic.zip, unzip, and run zclassic.msi, VM recommended for testing, if you want to check the contents of the zip is valid:

```
  File: zclassic.msi
  Size: 77,905,920    
  MD5:  2e61e837c494389402d3d22d8ad98283
```

To-Do
--------------

Add functionality to automatically refresh peer info on startup, shouldn't be too difficult but I want to get the basics working first.

Feedback
--------------

If you find any issues please add to the 'issues' feature on GitHub
