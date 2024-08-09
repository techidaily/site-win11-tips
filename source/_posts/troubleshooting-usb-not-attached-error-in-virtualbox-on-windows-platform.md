---
title: Troubleshooting 'USB Not Attached' Error in VirtualBox on Windows Platform
date: 2024-08-08T11:02:22.807Z
updated: 2024-08-09T11:02:22.807Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting 'USB Not Attached' Error in VirtualBox on Windows Platform
excerpt: This Article Describes Troubleshooting 'USB Not Attached' Error in VirtualBox on Windows Platform
keywords: USB Error VirtualBox Win,Fixing USB Non-Attached VM,VirtualBox USB Recognition,Resolve USB Not Attached Win,Windows VirtualBox USB Troubleshoot,Unattached USB in Virtual Box,USB Error Handling on VBox Windows
thumbnail: https://thmb.techidaily.com/566315d56d553ccbd049a4fe3b4211dbde8cabf2cb29973d2f7eb7ff1fc0e46d.jpg
---

## Troubleshooting 'USB Not Attached' Error in VirtualBox on Windows Platform

 VirtualBox lets you run many operating systems in a virtual environment without affecting your host system files. It is a great hypervisor platform perfect for trying out any operating system without installing it alongside your host operating system. But many users face an issue while connecting a USB device to their VirtualBox Virtual machine.

 VirtualBox does support USB devices out of the box but requires an extension pack to enable USB 2.0 and USB 3.0 devices. If you see the ‘Failed to Attach the USB Device’ error every time you try to connect a USB device, don’t fret. We will list out the possible reasons why you see the error code along with multiple fixes to resolve the issue.

## Reasons for the "Failed to Attach the USB Device" Error

Here are some possible reasons for the VirtualBox USB devices error.

1. The USB drive is corrupt or the USB port is not working.
2. You haven’t installed the correct VirtualBox extension pack on your system.
3. You are running an outdated version of VirtualBox.
4. You haven’t added the USB device to the virtual machine using USB settings.

 Now, you know the possible reasons why VirtualBox throws an error code when you connect a USB device. Here are the following methods you can try to fix the error code and successfully connect the USB device to the virtual machine.

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Fix the "Failed to Attach the USB Device" Error in Windows

 Now that we know what's potentially causing the issue, let's explore the fixes.

### 1\. Restart VirtualBox

 Before you move on to other advanced fixes, restart the VirtualBox application. If restarting the app doesn’t work, restart Windows. It will restart all the processes and services including the ones VirtualBox needs to function properly. Now, connect a USB device and try to attach it to a virtual machine in VirtualBox. If it still doesn’t show up, move to the next fix.

### 2\. Check the USB Device on the Host System

 Before trying to attach the USB device to the VirtualBox virtual machine, first check if it shows up on your host system. Launch the File Explorer and go to This PC and check if the USB drive appears there. If you don’t see the USB drive, do as follows:

1. First, open Device Manager. There are many[different ways to open the Device Manager](https://www.makeuseof.com/windows-open-device-manager/) , but a quick way is to press**Win + R** to launch the Run command box. Type**devmgmt.msc** and press the**Enter** key to launch the Device Manager.  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
![Check the USB Device on the Host System](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Check-the-USB-Device-on-the-Host-System.jpg)
2. Navigate to the**Disk Drives** option and click the**arrow** icon to expand the section.
3. Find the USB drive you connected to the host system. If it is not present in the list, pull it out and reconnect it to another USB port on your system.

 If the USB port on your system malfunctions, the USB drive won’t show up in Device Manager or File Explorer. But if the USB drive doesn’t appear in the device manager even after changing the port, it could have a hardware malfunction. In that case, try connecting another USB drive to VirtualBox virtual machine.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
### 3\. Install the VirtualBox Extension Pack

 VirtualBox can only attach USB 1.0 devices to a virtual machine. You need to install the extension pack to add USB 2.0 or 3.0 devices. Here’s how to do it.

1. Open VirtualBox on your system and navigate to**Help > About VirtualBox** . Note the version currently installed on your system.
2. Launch any web browser on your system and go to the[official VirtualBox download page](https://www.virtualbox.org/wiki/Downloads) .
3. Click on the build number which is present on your system. Scroll down and download its corresponding extension pack.
4. Now, open VirtualBox. Navigate to**File > Tools > Extension Pack Manager** .  
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
![_Install the VirtualBox Extension Pack](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/_Install-the-VirtualBox-Extension-Pack.jpg)
5. Click on the**Install** icon and select the extension pack file you downloaded in step 3.
6. Click on the**Install** button, accept the**EULA** and click on the**I Agree** button.
7. Wait for the extension pack to install.
8. Run the virtual machine and try to connect the USB device to it.

### 4\. Update VirtualBox

 An outdated version of VirtualBox can encounter errors. So, you need to update VirtualBox to fix the underlying bugs and get access to new features offered by the developers. Here’s how to update VirtualBox on Windows.

1. Launch VirtualBox on your system. It will automatically notify you if a newer version is available. You can go to**Help > About VirtualBox** and check the current version info there.
2. Then, navigate to**Help > VirtualBox Web Site** . It will redirect you to the official website.
3. Click on the**Downloads** section and download the latest version. Also, download the corresponding extension pack.
4. Close the VirtualBox app and end all associated processes using Task Manager.
5. Run the downloaded executable file and follow the on-screen instructions to install it on your system. Also, install the extension pack as illustrated in Method 3 above.
6. Now, try to connect the USB device to the virtual machine using the settings menu.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
### 5\. Configure the USB Controller in Virtual Machine Settings

 A mismatch in the USB controller settings can also produce the VirtualBox error. If you want to add a USB device to the VirtualBox virtual machine, you must select the correct USB controller option in the USB settings.

1. Open VirtualBox and click on the virtual machine to which you want to add the USB drive.
2. Click on the**Settings** icon on the top. Then click on the**USB** option in the list.
3. Firstly, click the**Enable USB controller** checkbox to enable the USB device attaching feature to the virtual machine.
4. Then, select the USB 2.0 or 3.0 controller option located below the**Enable USB controller** option.  
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
![Configure the USB Controller](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Configure-the-USB-Controller.jpg)
5. Now, click on the**Add new USB filter** and pick the USB device you want to connect to the virtual machine.
6. Click on the**OK** button and close the settings window. Start the virtual machine and check if the error pops up now.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
### 6\. Reinstall the VBox USB drivers

 Corrupt or missing VBox USB drivers on your system could cause the Virtual Box error code. Reinstalling the USB drivers can fix the driver issue and allow USB devices to connect with the virtual machine.

1. Launch File Explorer on your Windows system. Visit the following path:**C:\\Program Files\\Oracle\\VirtualBox\\drivers\\USB**
2. Navigate to the**Device** subfolder and find the**VBoxUSB.inf** file.
3. Right-click on the file and select the**Install** option.
4. Now, navigate to the**Filters** subfolder and locate the**VBoxUSBMon.inf** file.
5. Right-click on the file and select the**Install** option.
6. Close Virtual Box and restart your system. Connect the USB device to the virtual machine and check whether the error code pops up.

### 7\. Reinstall VirtualBox

 If all the above methods don’t solve the ‘Failed to Attach the USB Device’ Error code, consider reinstalling the VirtualBox app on your system. Here’s how to do it.

1. Press the**Win + R** key to launch the Run command box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**appwiz.cpl** and press the enter key. The Programs and Features window will launch.
2. Locate VirtualBox from the list of installed programs and double-click on it.  
![Reinstall VirtualBox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Reinstall-VirtualBox.jpg)
3. **UAC** will pop up. Click on**Yes** to continue.
4. Follow the on-screen prompts to uninstall VirtualBox from your system.
5. Now visit the[official VirtualBox website](https://www.virtualbox.org/wiki/Downloads) and download the app and the corresponding extension pack.
6. Open the download location and run the setup file. Follow the on-screen prompts to install and then install the extension pack as described in method 3.
7. Now, attach a USB device and start the virtual machine to check if the error code occurs or not.

## Easily Connect USB Devices to Your Virtual Machine Once More

 VirtualBox needs the extension pack to enable connectivity for USB 2.0 and 3.0 devices. Check your USB devices for errors and verify that they mount properly on the host system. Reinstall USB drivers if you face the error again. Lastly, remove VirtualBox from the system and do a fresh installation.


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
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-click-worthy-chronicles-shaping-successful-meme-videos-for-instafb/"><u>[New] 2024 Approved  Click-Worthy Chronicles  Shaping Successful Meme Videos for Insta/FB</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-heritage-on-display-post-copyright-masterpieces/"><u>[New] Heritage on Display  Post-Copyright Masterpieces</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-colorful-cinematography-the-evolving-world-of-4k-chroma-blades/"><u>[Updated] Colorful Cinematography  The Evolving World of 4K Chroma Blades</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-how-to-view-facebook-stories-anonymously2/"><u>[Updated] In 2024, How to View Facebook Stories Anonymously2</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-optimize-sound-speed-with-these-essential-apps/"><u>2024 Approved  Optimize Sound Speed with These Essential Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-turn-filter-keys-on-or-off-on-windows/"><u>4 Ways to Turn Filter Keys On or Off on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-strategies-for-enabling-uninstalled-features-in-win10win11/"><u>7 Strategies for Enabling Uninstalled Features in Win10/Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-the-most-ignored-yet-crucial-windows-11-features/"><u>A Guide to the Most Ignored Yet Crucial Windows 11 Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-guide-to-resolving-steam-setup-problems-win11-edition/"><u>A Practical Guide to Resolving Steam Setup Problems, Win11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/access-strongest-passwords-effortlessly-with-these-7-free-generators/"><u>Access Strongest Passwords Effortlessly With These 7 Free Generators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-network-unity-wi-fi-plus-ethernet-integration-in-windows/"><u>Achieving Network Unity: Wi-Fi + Ethernet Integration in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-affected-windows-shield-functions-on-win-11/"><u>Addressing Affected Windows Shield Functions on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-functional-automation-rules-on-desktop/"><u>Addressing Non-Functional Automation Rules on Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-unified-sticky-note-syncing-on-win11/"><u>Addressing Non-Unified Sticky Note Syncing on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-sudden-screen-blackouts-in-winsteam/"><u>Addressing Sudden Screen Blackouts in WinSteam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-window-frame-blackout-restore-taskbar/"><u>Addressing Window Frame Blackout: Restore Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719367958537-adjust-brightness-slider-look-for-the-brightness-slider-under-system-or-personalization-tabs-in-settings/"><u>Adjust Brightness Slider: Look for the Brightness Slider Under 'System' Or 'Personalization' Tabs in Settings.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-buffer-rates-to-minimize-lag-with-vlc/"><u>Adjusting Buffer Rates to Minimize Lag with VLC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-reset-counter-after-failed-logins-on-windows-1011/"><u>Adjusting Reset Counter After Failed Logins on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-software-sizes-with-keyboard-shortcuts-in-win11/"><u>Adjusting Software Sizes with Keyboard Shortcuts in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-stealth-tactics-eliminate-11s-search-icon/"><u>Advanced Stealth Tactics: Eliminate 11'S Search Icon</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-tips-for-efficient-voice-access-on-windows/"><u>Advanced Tips for Efficient Voice Access on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-copilot-arrives-on-windows-11-transforming-user-interaction/"><u>AI Copilot Arrives on Windows 11, Transforming User Interaction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/alleviating-resource-drain-by-ntoskrnlexe/"><u>Alleviating Resource Drain by Ntoskrnl.exe</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automate-peaceful-slumber-for-your-w11-gadgets-at-rest/"><u>Automate Peaceful Slumber for Your W11 Gadgets at Rest</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-interruptions-resolving-steams-error-code-e84/"><u>Avoid Interruptions: Resolving Steam’s Error Code E84</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-display-drivers-that-dont-launch-in-windows-10/"><u>Avoiding Display Drivers That Don’t Launch in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-do-not-have-access-issue-for-app-removals/"><u>Avoiding Do Not Have Access Issue for App Removals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-inquiries-stealthy-strategies-for-secure-credentials-in-win-11/"><u>Avoiding Inquiries: Stealthy Strategies for Secure Credentials in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-soon-will-expire-warning-on-microsoft-os/"><u>Avoiding Soon Will Expire Warning on Microsoft OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/become-a-full-screen-screenshot-expert-4-essential-tricks-for-windows/"><u>Become a Full-Screen Screenshot Expert: 4 Essential Tricks for Windows.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-fit-selecting-vms-that-thrive-on-windows-11-platforms/"><u>Best Fit: Selecting VMs That Thrive On Windows 11 Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-performance-by-rebooting-windows-11-ram/"><u>Boost Performance by Rebooting Windows 11 RAM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-harness-windows-smart-launcher-techniques/"><u>Boost Productivity: Harness Windows' Smart Launcher Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-windows-apps-with-efficient-internet-fixes/"><u>Boost Your Windows Apps with Efficient Internet Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-edges-app-guard-with-enhanced-graphics/"><u>Boosting Edge's App Guard with Enhanced Graphics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-storage-efficiency-in-windows-11/"><u>Boosting Storage Efficiency in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719202889022-efficient-tips-for-resolving-common-windows-problems/"><u>Efficient Tips for Resolving Common Windows Problems</u></a></li>
<li><a href="https://fox-that.techidaily.com/how-to-retrieve-your-iphone-when-it-seems-missing-from-find-my-app/"><u>How To Retrieve Your iPhone When It Seems Missing From Find My App</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-hands-on-with-hp-envy-27-pushing-screen-tech-to-limits/"><u>In 2024, Hands-On with HP Envy 27  Pushing Screen Tech to Limits</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/master-live-broadcast-setup-using-obs-studio-pc-mac-laptop-for-2024/"><u>Master Live Broadcast Setup Using OBS Studio (PC, Mac, Laptop) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719350537828-navigating-troubled-waters-help-for-your-windows-woes/"><u>Navigating Troubled Waters: Help for Your Windows Woes!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719327147890-secrets-to-perfect-full-screen-snipping-with-windows-toolkit/"><u>Secrets to Perfect Full-Screen Snipping with Windows' Toolkit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719380953369-swift-file-stewardship-streamlining-googledrive-and-dropbox-via-windows-c/"><u>Swift File Stewardship: Streamlining GoogleDrive & Dropbox via Windows C:</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/unlock-youtube-placement-secrets-what-matters-most-in-2024/"><u>Unlock YouTube Placement Secrets  What Matters Most, In 2024</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/updated-in-2024-top-6-animated-emoji-video-effects/"><u>Updated In 2024, Top 6 Animated Emoji Video Effects</u></a></li>
</ul></div>
