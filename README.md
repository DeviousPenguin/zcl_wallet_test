## ZClassic Windows Wallet 1.2 for Windows x64
#### (1-click installer, alpha, untested, don't use to store funds)

About
--------------

Based on https://github.com/z-classic/zclassic/releases/tag/1.1 - I'm trying to fix some issues with the Windows installer, as it's 900mb right now. This installer is less than 100mb right now.

This is untested, unfinished and probably won't download the blockchain as it uses old peer information from github. The peer info is hardcoded at the moment. The intention is to change this in future so it download peer info on launch.

The main changes from the current wallet it that it downloads the 900mb proving key if it's not already on the system, meaning the installer can now be below 100mb.

I've also added a 1 click launcher similar zcash4win meaning that batch files no longer need to be used to start and stop the daemon, the aim is to make this as user friendly as possible. A minimal Java runtime is included also, so there should be no need for any extras to install.

Only use for testing, don't store ZCL funds on this wallet. 

I recommend VirtualBox to test install:

https://www.virtualbox.org/wiki/Downloads

Use the Microsoft provided Windows 10 x64 image from here:

https://developer.microsoft.com/en-us/microsoft-edge/tools/vms/

You can the use snapshots feature to put the VM in a previous state.

Install
-----------------

### Windows
Download zclassic.msi and run, VM recommended for testing

```
  File: ‘./zclassic.msi’
  Size: 77905920    
  MD5: 2e61e837c494389402d3d22d8ad98283
```

To-Do
--------------

Add functionality to automatically refresh peer info on startup, shouldn't be too difficult but I want to get the basics working first.

Feedback
--------------

If you find any issues please add to the 'issues' feature on GitHub
