---
title: Resolving 'No Device Drivers Detected' On Windows Setup
date: 2024-06-25T16:39:28.015Z
updated: 2024-06-26T16:39:28.015Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving 'No Device Drivers Detected' On Windows Setup
excerpt: This Article Describes Resolving 'No Device Drivers Detected' On Windows Setup
keywords: No Driver Errors,Fix Driver Issue,Windows Driver Setup,Device Not Recognized,Boot Without Drivers,Install Windows Properly,Detecting Windows Devices
thumbnail: https://thmb.techidaily.com/cd3d2360a2d4ccd17e303566ba964ef54de4b2742b9a5d3bf951667fe61ff2f5.jpg
---

## Resolving 'No Device Drivers Detected' On Windows Setup

 Did you get hit by an error in the middle of a Windows installation process? Often encountered in the form of a "No device drivers were found" dialog box, this bug usually occurs when the setup cannot find your disk drive.

 Luckily, there are a host of tricks that can rescue you from this harrowing error. We have rounded up some of them, so let's jump right into the solutions.

## 1\. Check the USB Port ![usb stick plugged into a port](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/usb-stick-plugged-into-a-port.jpg)

 If you are installing your Windows from a USB stick, it's possible to encounter this error if something has gone wrong with the USB port.

 Hardware components go bust all the time, which may be why the "No device drivers were found" error occurred in your PC in this case. So, try a different port for the installation and see if that fixes the issue for you.

 If that's not possible, plug in the USB in a different PC and see if the installation goes smoothly there.

## 2\. Check Your Installation Media

 Similar to the above method, you should see if there's a problem with the installation media itself.

 Whether something is wrong with the USB or it's the installation setup that's gone off, you can check this by trying the installation media on another PC. If the setup works fine there, then the trouble is most likely with your PC; jump down to the methods below for fixing it.

## 3\. Use the Command Prompt

 If you have ever used Windows even semi-regularly, you must already be aware of the force that is the [Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/). It's a tool known for its short, cryptic commands that let you manage your computer in the best possible way.

 You can use it to fix the "No Device Drivers Were Found" error on your Windows as well. Here's how:

1. Plug in the USB stick and start the installation process.
2. On the boot-up setup screen, press the **Shift + F10** shortcut to open the cmd.
3. From there, type in the following commands one by one and hit **Enter**:  
DiskpartList Disk

 Now, select the disk you'd like to install your Windows on. Then type in the following command and hit **Enter**:

select disk 1

 Here, "select disk" is the command to select the disk, and "1" denotes the disk that you have chosen.

 Note that this method will remove all your previous data (we are clearing the hard disk here), and you will have to start from ground zero. Finally, type _Clean_ and hit **Enter**. You will be face the error from there on.

## 4\. Insert USB Into an Alternate Port

 At MUO, we are big fans of clever hacks or tweaks that can get your stuff working in one way or the other. This method is a picture-perfect example of that.

 When you encounter the driver error, click the **Cancel** button. When you get to the welcome screen, take out the USB stick and plug it into a different port. Finally, click on **Install**.

 You should be able to get past the "No Device Drivers Were Found" error through this short trick. If the error persists, don't worry; move to the next method below.

## 5\. Try a Different Hard Drive

 If you have tried all the above methods, but the error still won't budge, it might now be time to get your hard drive checked. Hard drives can stop working for all sorts of reasons: wear and tear caused over time, damage from overheating (though this is becoming less and less common), and so on.

 If that turns out to be the case for you, then trying out a different hard drive will be worth the effort. You can [install a new hard drive](https://www.makeuseof.com/tag/install-hard-drive-replace/) or try getting one from your friend. If the culprit was indeed your hard disk, then the error will be fixed for good.

## Fixing the "No Device Drivers Were Found" Error While Installing Windows

 As long as you work on Windows, you will continue encountering all sorts of errors. While there's no panacea to fix all the bugs of this sort once and for all, you can always try out hacks like the above. In most cases, one or other method will always do the trick for you. However, if you still can't get anything to work, you can always try out a complete PC reset as your last resort.

 Luckily, there are a host of tricks that can rescue you from this harrowing error. We have rounded up some of them, so let's jump right into the solutions.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>