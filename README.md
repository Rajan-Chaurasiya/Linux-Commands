# Linux-Commands
How to Install Linux on Windows 10
Linux is a family of open-source operating systems. They are based on the Linux kernel and are free to download. They can be installed on either a Mac or Windows computer. Here’s how to install Linux on a Windows 10 PC. 

If you want to dual boot Linux and Windows, you will need to create a space for your Linux OS to live. In order to do this, you will have to partition your main hard drive. Here’s how to do that:

### Service-Computer-Need-Professional-Help-with-Your-Computer_
1. How to Partition a Hard Drive in Windows 10
2. Open the Windows Search Bar. This is the magnifying glass-shaped icon in the bottom-left corner of your screen.
3. Then type “DISKMGMT.MSC” in the search bar and hit enter.
search disk management
4. Right-click on your main hard drive and select Shrink Volume. If you have more than one drive, make sure to choose the one that says Primary Partition. This will usually be labeled as the C: drive.  
shrink volume
5.Then choose how much you want to shrink your drive. It is recommended that you set aside at least 20GB (20,000MB) for Linux.
shrink drive by
Finally, click Shrink.
Once you have a designated space to install Linux, you’ll need to write a Linux Distro onto a USB thumb drive or external drive 4GB or larger. Here’s how to do that:

How to Make a Linux Bootable USB
***Download a Linux distro in ISO format. An ISO file is a disk image. Some of the top options are Ubuntu, Mint, or Fedora. They are free to download from each distribution’s main website. For this article, we are using Ubuntu.
Insert the USB drive into your computer. You might be asked to format your drive. This will erase all the data stored on your drive, so make sure to back up your files before you begin.
Download Rufus. You can find the latest version of the application here.
Open Rufus and select your USB drive from the Device list. If you don’t know which drive to use, eject all other drives until you only have one to choose from.
Under Boot Selection, click the Select button and choose the ISO file you downloaded earlier. Don’t change the other default settings.
Rufus
Finally, click Start. If you get a pop-up message asking you to select a mode that you want to use to write the image, choose ISO.
choose iso
Then wait for Rufus to mount your ISO file onto your drive. This might take some time, so be patient if the progress bar gets stuck.***

Warning: This will erase all the data on your drive, so make sure to back up any important files.

Service-Computer-Computer-Virus
How to Install Linux from USB
Now that you have your Linux distro on a USB, here’s how to

Insert a bootable Linux USB drive.
Click the start menu. This is the button in the lower-left corner of your screen that looks like the Windows logo.
Then hold down the SHIFT key while clicking Restart. This will take you into the Windows Recovery Environment.
windows 10 shift restart
Then select Use a Device.
windows recovery use a device
Find your device in the list. If you don’t see your drive, choose EFI USB Device, then pick your drive from the next screen.
use a device linux
Your computer will now boot Linux. If your computer reboots Windows, there was either an issue with your drive, or you might have to change settings in your BIOS.
Warning: Changing BIOS settings can damage your computer if you don’t know what you’re doing.

Select Install Linux. Some distros also let you try out the OS before installing it here.
tru or install ubuntu
Go through the installation process. This will differ depending on which distro you are trying to install. These details might include your WiFi network, language, time zone, keyboard layout, etc. You might also be required to create an account with a username and password. Make sure to write down any details, as you will likely need them in the future.
Most distros will allow you to partition your drive or erase it and do a clean install during the installation.
Warning: Erasing your disk will mean you will lose your settings, files, and Windows operating system. Only select Erase if you have saved copies of all your files before starting the install process.

Reboot your computer when prompted. If you have more than one OS in your system, you will be taken to a GNU GRUB screen after rebooting. This screen allows you to select which OS you want to boot. 
ubuntu grub
If you do not see a GRUB screen when you boot up your computer, you can try moving your Linux distro higher on your boot list in BIOS.

When you’re done, you can do a hardware check. In some cases, you may need to download additional drivers to make some hardware work. The option to download drivers can be found in the Systems Settings of your new Linux OS. After verifying that your hardware is working properly, you can start exploring and using your Linux distro. 

If you’re a Mac user, check out our blog on how to install Linux on your Mac.

Service-Computer-Slow-Computer_
