---
title: How to Find and Change the Subnet Mask in Windows 11
date: 2024-07-12T16:55:13.047Z
updated: 2024-07-13T16:55:13.047Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Find and Change the Subnet Mask in Windows 11
excerpt: This Article Describes How to Find and Change the Subnet Mask in Windows 11
keywords: Win11 Subnet Changing Guide,Subnet Mask Alteration in Win11,Setting Win11 Network Settings,Find Win11 Subnet Address,Windows 11 NetMask Update,Modify Win11 IP Configuration,Subnet Mask Change Procedure in Windows 11
thumbnail: https://thmb.techidaily.com/3119c4d644ca38982b7a0f68d251b6e048a299751591496c468d996da741d28a.jpg
---

## How to Find and Change the Subnet Mask in Windows 11

 Devices in a subnetwork have IP addresses that begin with the same prefix. The length of this prefix is different for different devices—it depends on the network size, whose length is identified using the subnet mask.

 While troubleshooting network issues, you must ensure that the subnet mask is correct. So, we'll share how to find and change the subnet in Windows 11.

## How to Find the Subnet Mask in Windows 11

 The easiest way to find the subnet mask in Windows 11 is through the [Windows Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) or Windows PowerShell. To find it using the Command Prompt, follow the steps below:

1. Press the**Win** key to launch the Start Menu.
2. In the search bar, type**Command Prompt** and choose the**Run as administrator** option from the right pane.
3. In the elevated Command Prompt window, type**ipconfig /all** and press Enter. This command will display all the important details about the network your computer is connected to, including the subnet mask.
4. Scroll and look for**Subnet Mask.** It'll be under the**Wireless LAN adapter Wi-Fi** section.  
![Finding the Subnet mask in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/finding-the-subnet-mask.jpg)

 The steps to do it using Windows PowerShell are similar to the Command Prompt. To do it,[open Windows PowerShell with admin rights](https://www.makeuseof.com/windows-11-powershell-administrator/) , type the ipconfig /all command, and press Enter.

 In the result that appears, you can see the subnet mask under the Wireless LAN adapter Wi-Fi section.

## How to Change the Subnet Mask in Windows 11

 Now that you know how to find the subnet mask on your computer, let's check out how to change it.

### 1\. Change the Subnet Mask Using the Windows Settings

 The settings menu is the central hub of a Windows operating system. It's a place to configure different settings of your computer and manage the network. You can also use it to change the subnet mask.

Here's how to do it:

1. [Open the Windows Systems Settings menu](https://www.makeuseof.com/windows-ways-to-open-system-settings/) , and choose**Network & internet** from the left panel.
2. Select**Wi-Fi,** and then choose your network in the following window.
3. Click the**Edit** button next to the**IP assignment** option.  
![Edit button in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/edit-button.jpg)
4. In the prompt that crops up, click on the drop-down icon and choose**Manual.**
5. Enable the toggle next to the IP version you're using.
6. Enter the details, including the subnet mask, and click**Save.**  
![Entering the new Subnet Mask in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/entering-the-new-subnet-mask.jpg)

### 2\. Change the Subnet Mask Using the Control Panel

 The Control Panel is the go-to place to configure window settings and make changes to your device. To use it to change the subnet mask, follow the below instructions:

1. Press the Win key, type**Control Panel** in the search bar, and press Enter.
2. Click the drop-down icon next to**View by** and choose**Large icons.**
3. Choose**Network and Internet** , and then select**Network and Sharing Center** in the following window.
4. Click on your network next to**Connections.**  
![Network name in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-name.jpg)
5. Choose**Properties** from the window that appears.
6. Select the IP version you're using. For instance, if you're using IPv4, select**Internet Protocol Version 4 (TCP/IPv4)** and click the**Properties** button.  
![IPv4 properties option in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/ipv4-properties.jpg)
7. Select the**Use the following address** option and enter the details.  
![Changing the Subnet Mask in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/changing-the-subnet-mask.jpg)
8. Click**OK** to save the changes.

### 3\. Change the Subnet Mask Using Windows PowerShell

 Windows PowerShell is also one of the places from where you can change the subnet mask in Windows 11\. Here's how to do it:

1. Open Windows PowerShell with admin rights, type the following command, and press Enter. This command will display all the network adapters installed on your device.  
`Get-NetAdapter -physical`
2. To change the subnet mask, type the following command and press Enter. Make sure to replace the "**ifIndex Number** " with the number associated with the network adapter whose subnet mask you want to change. And replace "**subnet prefix length** " with the new subnet prefix length you want.  
`Set-NetIPAddress -InterfaceIndex (ifIndex Number) -PrefixLength (subnet prefix length)`

 For instance, if the ifIndex Number is 3 and the new subnet prefix length you want is 24, then the command will be:

`Set-NetIPAddress -InterfaceIndex 3 -PrefixLength 24`

![Command to change the subnet mask in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/command-to-change-the-subnet-mask.jpg)

## Changing the Subnet Mask in Windows 11

 The subnet mask helps to identify the network and the host bit of the IP address. If you want to find and change the subnet mask on your computer, you can do it using either of the above methods.

 Meanwhile, you might be interested to know more about subnets and how to calculate them.


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
<li><a href="https://win11-tips.techidaily.com/easy-ways-to-tackle-windows-rpc-errors-effectively/"><u>Easy Ways to Tackle Windows RPC Errors Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guides-to-restore-lock-screen-timeout-mechanism/"><u>Guides to Restore Lock Screen Timeout Mechanism</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-full-potential-of-the-windows-key/"><u>Unlocking Full Potential of the Windows Key</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-checklist-for-fine-tuning-windows-11-installation/"><u>The Ultimate Checklist for Fine-Tuning Windows 11 Installation</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-evasion-techniques-for-youtube-bans/"><u>[Updated] In 2024, Evasion Techniques for YouTube Bans</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-act-reducing-excessive-background-load/"><u>Balancing Act: Reducing Excessive Background Load</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-troubleshooting-for-elusive-temp-files/"><u>Windows Troubleshooting for Elusive Temp Files</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-top-rated-font-creation-tools-for-discord-on-devices/"><u>[Updated] Top-Rated Font Creation Tools for Discord on Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-your-connection-top-9-fixes-for-missing-bluetooth-in-windows-11/"><u>Bring Back Your Connection: Top 9 Fixes for Missing Bluetooth in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-5-best-torrent-clients-for-windows/"><u>The 5 Best Torrent Clients for Windows</u></a></li>
<li><a href="https://ai-voice.techidaily.com/new-top-10-robotic-voice-generators/"><u>New Top 10 Robotic Voice Generators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-activate-educational-themes/"><u>Win 11: Activate Educational Themes</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-nintendo-switch-capturing-your-playtime/"><u>[Updated] 2024 Approved  Nintendo Switch  Capturing Your Playtime</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-restoring-a-dysfunctional-downloads-hub-in-windows/"><u>Guidelines for Restoring a Dysfunctional Downloads Hub in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719341208077-pause-on-snipwise-discover-fixes-today-here/"><u>Pause on SnipWise? Discover Fixes Today, Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-youtube-watch-on-chrome-windows/"><u>Accelerate Your YouTube Watch on Chrome Windows</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-ultimate-guide-to-best-internet-recording-tools-2023/"><u>[New] 2024 Approved  Ultimate Guide to Best Internet Recording Tools 2023</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-virtual-frontier-top-pc-vr-headset-innovations-of-the-year/"><u>In 2024, Virtual Frontier  Top PC VR Headset Innovations of the Year</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-approach-to-setting-powershell-policies/"><u>A Practical Approach to Setting PowerShell Policies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-dark-displays-during-win-games/"><u>Troubleshooting Dark Displays During Win Games</u></a></li>
<li><a href="https://location-social.techidaily.com/proven-ways-in-how-to-hide-location-on-life360-for-poco-x6-pro-drfone-by-drfone-virtual-android/"><u>Proven Ways in How To Hide Location on Life360 For Poco X6 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-free-gaming-setup-dualshock-for-windows-users/"><u>Tech-Free Gaming Setup: DualShock for Windows Users</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-pro-level-webcams-the-ultimate-choice-for-your-podcasts/"><u>2024 Approved  Pro Level Webcams  The Ultimate Choice for Your Podcasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-win11-ui-with-enlarged-icons/"><u>Transform Your Win11 UI with Enlarged Icons</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-trend-analysis-through-infographics/"><u>[Updated] In 2024, Trend Analysis Through Infographics</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-spice-up-viewers-innovative-cooking-channel-naming-tips/"><u>[New] Spice Up Viewers  Innovative Cooking Channel Naming Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turning-spoken-words-into-written-phrases-a-guide-for-windows-users/"><u>Turning Spoken Words Into Written Phrases: A Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transition-trio-top-apps-making-pc-switch-easier/"><u>Transition Trio: Top Apps Making PC Switch Easier</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/in-2024-vsdc-free-video-editor-review-2023/"><u>In 2024, VSDC Free Video Editor Review 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-error-1152-temporary-file-extract-failure/"><u>Tackling 'Error 1152: Temporary File Extract Failure'</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-tecno-pova-5-location-is-wrong-drfone-by-drfone-virtual-android/"><u>How to Fix My Tecno Pova 5 Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-elevate-your-snapchat-creativity-with-these-6-editors/"><u>In 2024, Elevate Your Snapchat Creativity with These 6 Editors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-customization-increasing-icon-dimensions-in-w11/"><u>Winning at Customization: Increasing Icon Dimensions in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719298672852-leveraging-local-links-to-global-drives-dropbox-and-googledrive-via-c/"><u>Leveraging Local Links to Global Drives: Dropbox & GoogleDrive via C:</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-erase-personal-info-from-sign-in-window/"><u>Guide to Erase Personal Info From Sign-In Window</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-the-operation-of-microsofts-phone-link-app/"><u>Demystifying the Operation of Microsoft's 'Phone Link' App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-impacts-of-ditching-windows-11s-taskbar-chatting-feature/"><u>Exploring Impacts of Ditching Windows 11'S Taskbar Chatting Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/thriving-without-11-upgrade-boost-your-pc-health/"><u>Thriving Without 11 Upgrade: Boost Your PC Health</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-camera-combat-gopro-hero5-vs-garmin-virb-ultra-face-off/"><u>In 2024, Camera Combat  GoPro Hero5 Vs. Garmin VIRB Ultra Face-Off</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-application-was-unable-to-start-0xc000003e-error-in-windows-11-and-11/"><u>How to Fix “The Application Was Unable to Start” 0Xc000003e Error in Windows 11 & 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-become-a-pro-editor-in-seconds-canvas-essential-secrets/"><u>2024 Approved  Become a Pro Editor in Seconds  Canva's Essential Secrets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/chilly-cheer-christmas-presents-with-microsofts-marketplace/"><u>Chilly Cheer: Christmas Presents with Microsoft's Marketplace</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-choreographed-combat-selecting-superior-fighting-titles/"><u>[New] In 2024, Choreographed Combat  Selecting Superior Fighting Titles</u></a></li>
</ul></div>
