---
title: Clearing Up VMware Freeze-Ups on Windows 11
date: 2024-06-25T16:21:04.086Z
updated: 2024-06-26T16:21:04.086Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Clearing Up VMware Freeze-Ups on Windows 11
excerpt: This Article Describes Clearing Up VMware Freeze-Ups on Windows 11
keywords: Fix Windows VM Freeze-Up,Resolve VMFreezes in Win11,Stop VM Crashes Windows,Eliminate Win11 VM Stops,Preventing VM Lags on W11,Avoid Freezing in WinVMware,End Win11 VM Lag Issues
thumbnail: https://thmb.techidaily.com/80c8f2832769bf50662b01ca1e988a4c71933b23ed7117cea801b49e429b370c.jpg
---

## Clearing Up VMware Freeze-Ups on Windows 11

 VMware Workstation Player is among the best virtualization software available today. You can create virtual machines and install operating systems on them. Virtual machines save you the trouble of wiping your hard disk to try out an operating system. However, it is not the only use case of third-party hypervisors like VMware.

 And although virtual machines typically run smoothly, you might occasionally experience a BSOD error while launching or using a virtual machine in a VMware workstation player. So, we'll list the potential reasons for BSODs in VMware along with multiple methods to resolve the issue.

## Reasons for VMware BSOD Error on Windows 11

Here are a few possible reasons for the VMware BSOD error on Windows:

1. Native virtualization services like WHP are running alongside VMware.
2. You are using an outdated version of Windows.
3. VMware is conflicting with another application or background service.
4. The virtual machine is eating up more resources than the system can spare.

## How to Fix VMware BSOD Error on Windows 11

 Now, you know the possible reasons for the BSOD error while using VMware. Try out the following methods to fix the issue.

### 1\. Restart VMware

 Before moving on to more complex fixes, restart the VMware program on your Windows 11 computer. Close the program and terminate all its processes from the Task Manager. Now, relaunch VMware and power on a virtual machine. Keep the machine running for some time, and keep an eye out for BSOD errors.

### 2\. Update VMware

 An outdated version of VMware can act finicky with the new system updates. So, you must update it to apply fixes released by developers for newfound bugs. Here's how to do it:

1. Launch VMware on your system.
2. Navigate to the top left section and click on the Player button.
3. Then, go to**Help > Software Updates** .
4. Click on the**Check for Updates** button. Wait for the utility to search for the latest available update, if any.
5. If an update is available, click on the**Download and install** button. Wait for the update to install.  
![Update VMware](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/update-vmware.jpg)
6. [UAC](https://www.makeuseof.com/tag/user-account-control-windows-10/) will pop up. Click on the**Yes** button to begin the update installation.
7. Close the VMware program. Follow the on-screen prompts to install the update on your system.
8. Click on the**Finish** button after the installation completes successfully.
9. Restart your system. Launch VMware and start a virtual machine. Check if the program produces a BSOD error.

### 3\. Disable Hyper-V and Other Windows Features

 Third-party hypervisors fail to launch or work properly when Hyper-V or other virtualization features such as Windows Hypervisor Platform, Virtual Machine Platform, and more. You must turn off all these features before using VMware on your Windows 11 system.

Repeat the following steps to disable Windows features:

1. Press**Win + R** to launch the Run command box. Type**appwiz.cpl** and press the enter key.
2. Programs and Features utility will launch. Click on the**Turn Windows features on or off** option.
3. Scroll down and uncheck the**Hyper-V** feature in the list. Similarly, uncheck the**Windows Hypervisor Platform** ,**Virtual Machine Platform** , and**Windows Subsystem for Linux** .  
![Disable Windows Features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-windows-features.jpg)
4. Windows will uninstall all these features from your system and auto-restart it to apply changes. It will take a while to remove all these features.
5. Sign in and launch VMware again. Now, power on a virtual machine and check if a BSOD error pops up.

### 4\. Reconfigure Virtual Machine Resources

 If your virtual machine crashes and throws a BSOD error, it is likely consuming more resources than your system can spare. Ideally, you should not devote more than 50 percent of any hardware (CPU, RAM, or disk space) to a virtual machine. Always leave enough for the host system to run smoothly and then devote the rest to the virtual machine.

Here's how to reconfigure virtual machine resources in VMware.

1. Launch VMware on your system. Click on any virtual machine in the list and select the**edit virtual machine settings** option.
2. Under the hardware tab, click on the**Memory** option. Adjust the slider to the recommended memory size.
3. Move to the Processors option and expand the**number of processor cores** dropdown list. Select**four** and click on the**OK** button.  
![Reconfigure virtual machine resources](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reconfigure-virtual-machine-resources.jpg)
4. These hardware settings are different for every operating system. Make sure to allocate only the bare minimum resources specified by the operating system developers.
5. Now, power on the virtual machine and use it for some time. If you still encounter a BSOD error, move to the next method.

### 5\. Update Windows

 An outdated version of Windows can contain bugs and may not sit well with new apps and software. So, update your Windows system using the settings app. Repeat the following steps to update Windows:

1. Press**Win + I** to [launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to the top right section and click on the Windows Update icon.
3. Click on the**Check for updates** button. Wait for the utility to search for new updates for your device.  
![Update Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/update-windows.jpg)
4. Download and install the update.**Restart** your system to apply the update.
5. Launch VMware on your system and start a virtual machine.

### 6\. Perform a Clean Boot

 A background program could be interfering with the nominal working of VMware. You must perform and clean boot to isolate and identify the root cause of trouble. Clean boot will start Windows with basic drivers and programs.

To clean boot your Windows PC, repeat the following steps:

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**msconfig** and press the enter key. The system configuration utility will launch.
3. Switch to the**Services** tab and click on the**Hide all Microsoft services** option.
4. Click on the**Disable all** button and then switch to the startup tab. Click on the Open Task Manager option.
5. Task Manager will launch. Right-click on a startup program and select the**Disable** option. Repeat this action for all programs.  
![Perform a Clean Boot-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/perform-a-clean-boot-1.jpg)
6. Close Task Manager and click on the**OK** button.
7. Restart your system and launch VMware. If it runs fine, open System Configuration, enable some services, and try again.
8. Identify and uninstall the troublemaker program or keep its services disabled on startup.

### 7\. Use a Different ISO File

 A corrupt ISO file can also cause a BSOD error while installing the operating system on a virtual machine. If you are using an old ISO file that is possibly corrupt, download its most recent version and add it to the virtual machine.

 Start the virtual machine and boot from that ISO file using the boot menu options. Begin the installation process and check if the process completes without an issue.

### 8\. Use a Different Hypervisor

 The last resort is to use a different hypervisor program for the time being. Try a level-1 hypervisor like Hyper-V or use level-2 hypervisors like VirtualBox or QEMU. Report the issue to the VMware developers and wait for them to release a bug fix for the BSOD issue.

 VirtualBox had a similar issue when it wasn't compatible with Windows 11\. It took Oracle some time to release a compatible version, forcing users to find a temporary alternative while waiting for the fix.

## VMware BSOD Error Won't Bother You Anymore

 VMware can easily run all the popular operating systems inside a virtual machine. But the BSOD error renders the program unusable. Try out the basic troubleshooting methods and update VMware and Windows. After that, disable Windows Hyper-V and other virtualization features and reconfigure the virtual machine resources.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-failures-from-windows-memory-tool/"><u>How To Rectify Failures From Windows Memory Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-edge-access-control-constructing-your-windows-personal-pins/"><u>Cutting-Edge Access Control: Constructing Your Windows Personal Pins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skip-steps-just-admin-command-prompt-anytime-now/"><u>Skip Steps, Just Admin Command Prompt Anytime Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-the-operation-of-microsofts-phone-link-app/"><u>Demystifying the Operation of Microsoft's 'Phone Link' App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/multilingual-mastery-harnessing-the-power-of-hotkey-translations-in-windows-11/"><u>Multilingual Mastery: Harnessing the Power of Hotkey Translations in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-roblox-availability-tackling-windows-settings-issue/"><u>Unblocking Roblox Availability: Tackling Windows Settings Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinforced-graphics-elevating-edges-protected-mode/"><u>Reinforced Graphics: Elevating Edge's Protected Mode</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-quick-tips-apply-smooth-motion-blur-on-your-pics/"><u>In 2024, Quick Tips  Apply Smooth Motion Blur on Your Pics</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/most-popular-iphone-podcast-soundshare-for-2024/"><u>Most Popular iPhone Podcast Soundshare for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-the-ultimate-checklist-for-transforming-your-tiktok-handle/"><u>In 2024, The Ultimate Checklist for Transforming Your TikTok Handle</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/in-2024-issues-with-tiktok-videos-finding-the-fixes/"><u>In 2024, Issues with TikTok Videos? Finding the Fixes</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-brighten-up-best-video-editing-apps-for-mobile-devices-for-2024/"><u>New Brighten Up Best Video Editing Apps for Mobile Devices for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-120plus-original-title-concepts-for-unique-and-memorable-snapchat-stories/"><u>[Updated] 2024 Approved  120+ Original Title Concepts for Unique and Memorable Snapchat Stories</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-latest-guide-how-to-bypass-oneplus-nord-3-5g-frp-without-computer-by-drfone-android/"><u>In 2024, Latest Guide How To Bypass OnePlus Nord 3 5G FRP Without Computer</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-enhancing-projects-methodically-adding-audio-files-in-final-cut-pro/"><u>Updated 2024 Approved Enhancing Projects Methodically Adding Audio Files in Final Cut Pro</u></a></li>
</ul></div>
