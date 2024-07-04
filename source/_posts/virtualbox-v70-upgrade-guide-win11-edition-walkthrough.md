---
title: VirtualBox v7.0 Upgrade Guide – Win11 Edition Walkthrough
date: 2024-06-25T16:20:01.602Z
updated: 2024-06-26T16:20:01.602Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes VirtualBox v7.0 Upgrade Guide – Win11 Edition Walkthrough
excerpt: This Article Describes VirtualBox v7.0 Upgrade Guide – Win11 Edition Walkthrough
keywords: VirtualBox V7 Update,Windows 11 Box Guide,VirtualBox Win11 Walkthrough,VirtualSuite V7 Guide,Upgrading VirtualBox,VirtualWin V7 Tutorial,V7 VirtualOS Update
thumbnail: https://thmb.techidaily.com/1ed4f091728645649c840ae907d2be87aba494a53f4cf1942b1dcf1c240fc190.jpg
---

## VirtualBox v7.0 Upgrade Guide – Win11 Edition Walkthrough

 Earlier, installing Windows 11 in VirtualBox was no easy feat. But with VirtualBox 7.0 you can install Windows 11 much faster without performing any registry hacks.

 If you use VirtualBox 6.1 on your system, it is better to upgrade to the newest version. Unlike most apps that auto-update, VirtualBox needs manual efforts to update to the new version. We will elaborate on the methods to update to VirtualBox 7.0 on Windows 11 and install the necessary add-ons.

## What’s New in VirtualBox 7.0?

 VirtualBox comes with support for Secure Boot in UEFI mode. It can now emulate TPM chips which are a mandatory requirement for Windows 11\. Along with that, there are some subtle but useful design changes that make it feel like a latest-gen app. Some menu options appear in new places, but it isn’t something to worry about. Plus, you can enjoy the dark mode on VirtualBox now and protect your eyes!

## How to Upgrade to VirtualBox 7.0 on Windows 11

 VirtualBox does remind you that an update is available. But unlike most apps, you need to visit the official site and download all the necessary components and the new installer file to upgrade VirtualBox. Then, you need to install the new version on your system which will replace all the files of the current build present on your system.

 But that’s not all! If you connect USB devices to VirtualBox virtual machines, you will have to remove the old extension pack and install the latest one released for the new build. Lastly, you will have to install the new guest additions pack for VirtualBox 7.0\. So, let’s begin.

### 1\. Download the VirtualBox 7.0 Installer File and the Extension Pack

 Repeat the following steps to download all the necessary files for VirtualBox 7.0.

1. Launch the VirtualBox app on your system. Navigate to**Help > VirtualBox Web Site** .
2. The app will redirect you to the official VirtualBox website.
3. Navigate to the left-hand side menu and click on the**Downloads** option.  
![Download VirtualBox 7.0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/download-virtualbox-7-0.jpg)
4. Locate the**VirtualBox 7.0.4 platform packages** section. Click on the**Windows Hosts** option to download the installer file on your system.
5. Scroll down and find the**VirtualBox 7.0.4 Oracle VM VirtualBox Extension Pack** section. Click on the**All supported platforms** option to download the extension pack file for version 7.0.4.
6. Wait for both downloads to finish and close the browser.

Now, you have all the necessary files to upgrade to VirtualBox 7.0.

### 2\. Install VirtualBox 7.0

To install VirtualBox 7.0, repeat the following steps:

1. Close the VirtualBox app if it is already running on your system. You can even restart your system for reducing issues while installing the latest version of VirtualBox.
2. Press the**Win + E** key to launch the File Explorer app on your system (see [how to launch File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) for more info). Click on the**Downloads** folder and locate the VirtualBox 7.0 installer file.
3. Right-click on the installer file and select the**Run as administrator** option from the context menu.
4. UAC will pop up. Click on the**Yes** button to continue.
5. VirtualBox 7.0 installer will launch. Pick the installation destination and click on the**Yes** button.  
![Install VirtualBox 7.0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/install-virtualbox-7-0.jpg)
6. VirtualBox will warn you about temporarily shutting the network interfaces. It means you will lose internet connectivity for some time.
7. Click on the**Yes** button. The installer will notify you about the missing dependencies. Click on the**Yes** button to install them as well.
8. Wait for the installation to complete. Click on the**Finish** button to close the installer window.

 VirtualBox 7.0 will launch on your system. But wait! Don’t close the app yet.

### 3\. Install the New Extension Pack

 Even after you upgrade the VirtualBox app to the newest version, the extension pack doesn’t upgrade along with it. So, it will have the older version of the extension pack which worked with the older VirtualBox version. You need to remove it and install the new extension pack that you download in the second method.

To install the VirtualBox 7.0 extension pack, do as follows:

1. Open the VirtualBox app. Navigate to**File > Tools > Extension Pack Manager** .
2. Under the list of active extension packs, you will see the older version with a red sign. It indicates that the extension pack is incompatible with VirtualBox 7.0.
3. Right-click on the old extension pack and select the**Uninstall** option.  
![Remove the Old Extension Pack](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-the-old-extension-pack.jpg)
4. Click on the**Remove** button to begin the uninstallation.
5. UAC will pop up. Click on the**Yes** button to begin the uninstallation.

1. Now, click on the**Install Extension Pack** button located at the top. Locate the extension pack file you downloaded previously and select it. Click on the**Open** button.
2. VirtualBox extension pack installer will pop up. Click on the**Install** button.  
![Install the New Extension Pack](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/install-the-new-extension-pack.jpg)
3. Accept the**EULA** by scrolling down. Click on the**I Agree** button.
4. UAC will pop up. Click on the**Yes** button to begin the extension pack installation.
5. Once the extension pack installs, it will appear in the list of installed extension packs.

 Now, you can easily connect the USB devices to one or many virtual machines that you created using VirtualBox. Check out our guide on [how to add a USB device to VirtualBox on Windows](https://www.makeuseof.com/windows-virtualbox-add-usb/) for more information.

### 4\. Install the Guest Additions

 VirtualBox Guest Additions offers all the necessary drivers for a virtual machine. Since VirtualBox supports DirectX 11, it is advisable to install Guest Additions as it will offer drivers for all the components.

 Here’s how to install the VirtualBox Guest Additions on a virtual machine:

1. Open the VirtualBox app. Click on any Windows virtual machine and then select the**Start** option.
2. Wait for the Windows virtual machine to boot up. After that, navigate to the top of the VirtualBox windows and click on**Devices** .
3. Then, select the**Insert Guest Additions CD Image** option.
4. Open the**File Explorer** app on your Windows virtual machine. You will see the guest additions CD image mounted there.
5. Double-click to open the CD image directory. Scroll down and right-click on the**VBoxWindowsAdditions–amd64.exe** file. Select**Run as administrator** from the context menu.  
![Install the Guest Additions 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/install-the-guest-additions-1.jpg)
6. UAC will pop up. Click on**Yes** to continue.  
![Install the Guest Additions 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/install-the-guest-additions-2.jpg)
7. Follows the on-screen prompts to install the Guest Additions on your system.
8. Click on the**Reboot now** option to apply changes to the Windows virtual machine.

 It may take a while to install the guest additions. Once done, you can change the resolution of the virtual machine to match the display resolution.

## Will the Old Virtual Machines Work With VirtualBox 7.0?

 Yes. VirtualBox 7.0 will run the old virtual machines that you created without any issues. But you have to install the extension pack and the guest additions otherwise it could crash or not run at all. We tried running old Windows 10 and 11 virtual machines that we created in version 6.1.32, and they worked fine.

## Upgrade to VirtualBox 7.0 With Ease

 VirtualBox 7.0 is the first third-party hypervisor to introduce emulation of TPM 2.0 chips. Microsoft still impedes Windows 11 installation as a virtual machine if the hypervisor cannot emulate the chip. But VirtualBox 7.0 can now install Windows 11 after enabling the passthrough of the TPM 2.0 chip for a virtual machine.


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
<li><a href="https://win11-tips.techidaily.com/seamless-system-controls-learn-how-to-use-4-techniques-for-disk-editor-on-win11/"><u>Seamless System Controls: Learn How to Use 4 Techniques for Disk Editor on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augment-windows-management-with-a-disk-space-analysis-tool/"><u>Augment Windows Management with a Disk Space Analysis Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-outlooks-error-0x80040610-in-windows-systems/"><u>Overcoming Outlook's Error 0X80040610 in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snipcam-issues-quick-solutions-for-troubleshooting/"><u>SnipCam Issues: Quick Solutions for Troubleshooting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-analysis-of-user-profile-control-with-cmd/"><u>In-Depth Analysis of User Profile Control with CMD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-unsuited-file-vlc-problem/"><u>Overcoming Windows' 'Unsuited File' VLC Problem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-manual-timezone-setting-in-microsoft-os/"><u>Troubleshoot Manual Timezone Setting in Microsoft OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-resolve-microsoft-store-fault-error-0x0-in-windows/"><u>Strategies to Resolve Microsoft Store Fault: Error 0X0 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-11-screen-recording-techniques-combining-audio-and-visual-features-in-snipping-tool-max-156/"><u>Unveiling Windows 11 Screen Recording Techniques: Combining Audio & Visual Features in Snipping Tool (Max 156)</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-activate-and-use-life360-ghost-mode-on-oppo-f25-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How To Activate and Use Life360 Ghost Mode On Oppo F25 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/a-perfect-guide-to-remove-or-disable-google-smart-lock-on-vivo-t2-pro-5g-by-drfone-android/"><u>A Perfect Guide To Remove or Disable Google Smart Lock On Vivo T2 Pro 5G</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/best-mac-screen-capture-tools-for-2024/"><u>Best Mac Screen Capture Tools for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/in-2024-unlock-your-music-expert-advice-on-converting-soundcloud-to-mp3/"><u>In 2024, Unlock Your Music Expert Advice on Converting Soundcloud to MP3</u></a></li>
<li><a href="https://android-location-track.techidaily.com/2-ways-to-monitor-xiaomi-mix-fold-3-activity-drfone-by-drfone-virtual-android/"><u>2 Ways to Monitor Xiaomi Mix Fold 3 Activity | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-20-best-video-editors-compatible-with-dji-videos/"><u>In 2024, 20 Best Video Editors Compatible with DJi Videos</u></a></li>
<li><a href="https://youtube-web.techidaily.com/izing-your-channels-earnings-a-guide-to-creating-impactful-trailers-for-2024/"><u>Maximizing Your Channel's Earnings  A Guide to Creating Impactful Trailers for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-elite-sound-recording-tools-11-selection/"><u>[New] In 2024, Elite Sound Recording Tools - #11 Selection</u></a></li>
<li><a href="https://howto.techidaily.com/bricked-your-motorola-moto-e13-heres-a-full-solution-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Bricked Your Motorola Moto E13? Heres A Full Solution | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-samsung-galaxy-m34-drfone-by-drfone-android/"><u>How To Use Allshare Cast To Turn On Screen Mirroring On Samsung Galaxy M34 | Dr.fone</u></a></li>
</ul></div>
