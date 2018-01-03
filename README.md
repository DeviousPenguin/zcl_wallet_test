Zclassic v1.2 test 1 click installer for Windows (alpha)


Install
-----------------

### Windows
Download zclassic.msi and run

About
--------------

This is untested, unfinished and probably won't download the blockchain as it uses old peer information from github. 

The main changes from the current wallet it that it downloads the 900mb proving key if it's not already on the system, meaning the installer can now be below 100mb.

I've also added a 1 click laincher based on zcash4win meaning that batch files no longer need to be used to start and stop the daemon, the aim is to make this as user friendly as possible. A minimal Java runtime is included also, no need for extra things to install.

Only use for testing, don't store ZCL funds on this wallet. 

I recommend VirtualBox to test install, use the Microsoft provided Windows 10 x64 image from here:

https://developer.microsoft.com/en-us/microsoft-edge/tools/vms/

You can use snapshots to put the VM in a previous state.

To-Do
--------------

Add functionality to automatically refresh peer info on startup, shouldn't be too difficult but I want to get the basics working first.

Feedback
--------------

If you find any issues please add to the 'issues' feature on GitHub
