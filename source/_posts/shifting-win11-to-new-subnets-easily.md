---
title: Shifting Win11 to New Subnets Easily
date: 2024-07-12T17:17:40.060Z
updated: 2024-07-13T17:17:40.060Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Shifting Win11 to New Subnets Easily
excerpt: This Article Describes Shifting Win11 to New Subnets Easily
keywords: Win11 Network Change,Shift Win11 Settings,Subnet Update Windows,Simple Win11 Adjustment,Easy OS Subnet Alter,New IP Setup for Win11,Optimized Windows Reassignment
thumbnail: https://thmb.techidaily.com/185bd2e3ee5add750b89a3f134c1fcf3132bd93146cc3a0d22887acdb0a82b64.jpg
---

## Shifting Win11 to New Subnets Easily

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
<li><a href="https://win11-tips.techidaily.com/expert-guide-to-utilizing-diskusage-on-windows-systems/"><u>Expert Guide to Utilizing DiskUsage on Windows Systems</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-getting-the-pokemon-go-gps-signal-not-found-11-error-in-vivo-s17e-drfone-by-drfone-virtual/"><u>In 2024, Getting the Pokemon Go GPS Signal Not Found 11 Error in Vivo S17e | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-screen-unresponsive-error-on-windows-11/"><u>Overcoming 'Screen Unresponsive' Error on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/curtailing-premature-windows-edge-tabs/"><u>Curtailing Premature Windows Edge Tabs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-and-solving-win-os-device-errors/"><u>Navigating and Solving Win OS Device Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-admin-managed-feature-issues-in-windows-11/"><u>Troubleshooting Admin-Managed Feature Issues in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-hogwarts-legacys-memory-shortage-mistake/"><u>Resolving Hogwarts Legacy's Memory Shortage Mistake</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-resolving-winerror-0x80071a90-in-windows/"><u>Understanding & Resolving WinError: 0X80071a90 in Windows</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/-reduction-for-better-video-experiences-on-youtube-for-2024/"><u>Noise Reduction for Better Video Experiences on YouTube for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719328086208-calibrate-display-colors-go-to-settings-)-system-)-display-and-use-the-built-in-calibration-tool-for-accurate-color-representation/"><u>Calibrate Display Colors: Go to 'Settings' > 'System' > 'Display' And Use the Built-In Calibration Tool for Accurate Color Representation.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/purging-faulty-windows-11-recycle-bin-messages/"><u>Purging Faulty Windows 11 Recycle Bin Messages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switching-to-preferred-pdf-viewer-on-windows/"><u>Switching to Preferred PDF Viewer on Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-vivo-y36-drfone-by-drfone-virtual-android/"><u>9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Vivo Y36 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reconfiguring-account-lockout-limit-post-failed-sign-in-in-windows-1011/"><u>Reconfiguring Account Lockout Limit Post-Failed Sign-In in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-task-manager-with-finesse/"><u>Elevating Task Manager with Finesse</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proven-strategies-for-unlocking-store-apps-directory/"><u>Proven Strategies for Unlocking Store Apps Directory</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-geforce-experiences-retrieval-failure-on-windows-11-systems/"><u>Fixing GeForce Experience's Retrieval Failure on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-rockalldlldll-disappearance-issue-windows/"><u>Rectifying Rockalldll.dll Disappearance Issue (Windows)</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-from-cut-to-clip-chaos-achieving-smoothness-with-inshot/"><u>2024 Approved  From Cut-to-Clip Chaos  Achieving Smoothness with Inshot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-disable-the-win11-firewall/"><u>Strategies to Disable the Win11 Firewall</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-fix-windows-11-graphics-drivers-reset/"><u>Efficient Fix: Windows 11 Graphics Drivers Reset</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-ram-cache-and-how-to-purge-it/"><u>Decoding Windows RAM Cache and How to Purge It</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-google-frp-lock-on-poco-x6-pro-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock on Poco X6 Pro Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-art-of-epic-save-preservation/"><u>Navigating the Art of Epic Save Preservation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/alternate-routes-to-open-the-latest-windows-apps/"><u>Alternate Routes to Open the Latest Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-video-from-mkv-to-mp4-on-windows-pcs/"><u>Optimizing Video: From MKV to MP4 on Windows PCs</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-beginning-to-connect-a-comprehensive-facebook-setup-walkthrough/"><u>[New] In 2024, Beginning to Connect  A Comprehensive Facebook Setup Walkthrough</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unified-tech-experience-windows-pc-and-galaxy-device-flow/"><u>Unified Tech Experience – Windows PC & Galaxy Device Flow</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/seamless-access-watching-fb-videos-on-apple-tv-explained/"><u>Seamless Access  Watching FB Videos on Apple TV Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-windows-screen-saver-wait-time/"><u>Optimize Windows Screen Saver Wait Time</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-network-hurdles-restoring-file-transfer-on-win11/"><u>Navigating Network Hurdles: Restoring File Transfer on WIN11</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-innovative-tricks-for-captivating-boomerangs/"><u>[New] 2024 Approved  Innovative Tricks for Captivating Boomerangs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/brightness-boost-for-windows-11-control-your-pcs-glow/"><u>Brightness Boost for Windows 11: Control Your PC's Glow</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-wintoys-unlocking-a-versatile-tool-in-windows-os/"><u>Understanding WinToys: Unlocking a Versatile Tool in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-a-windows-11-recycle-bin-malfunction/"><u>Fixing a Windows 11 Recycle Bin Malfunction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-like-a-pro/"><u>Navigating Windows Like a Pro</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-do-you-like-clouds-or-sky-and-want-to-use-them-as-a-video-background-explore-this-article-to-learn-about-the-sky-change-video-in-filmora.m/"><u>New 2024 Approved Do You Like Clouds or Sky and Want to Use Them as a Video Background? Explore This Article to Learn About the Sky Change Video in Filmora</u></a></li>
<li><a href="https://fox-helps.techidaily.com/premium-audio-modification-solutions-magically-effective/"><u>Premium Audio Modification Solutions  Magically Effective</u></a></li>
<li><a href="https://fake-location.techidaily.com/ispoofer-is-not-working-on-vivo-v29-fixed-drfone-by-drfone-virtual-android/"><u>iSpoofer is not working On Vivo V29? Fixed | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-windows-11-defender-aguard-on-edge/"><u>Step-by-Step Guide to Windows 11 Defender Aguard on Edge</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-remove-and-reset-face-id-on-apple-iphone-8-by-drfone-ios/"><u>In 2024, How to Remove and Reset Face ID on Apple iPhone 8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-code-0x80070570-file-corruption-in-windows-11/"><u>Troubleshooting Code 0X80070570 File Corruption in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-for-fixing-fall-guys-link-failures-windows-wise/"><u>Essential Steps for Fixing Fall Guys Link Failures Windows-Wise</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-teach-you-to-transfer-files-from-itel-s23-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways To Teach You To Transfer Files from Itel S23 to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-uninstall-failure-windows-1011-access-issue/"><u>Resolving Uninstall Failure: Windows 10/11 Access Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-preference-portal-your-operating-systems-lair/"><u>The Preference Portal: Your Operating System’s Lair</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-top-facebook-video-mp4-downloaders/"><u>[New] In 2024, Top Facebook Video MP4 Downloaders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-installation-fix-for-ms-pc-manager-on-xp/"><u>Unlock Installation: Fix for MS PC Manager on XP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-window-restoration-after-dark-screens/"><u>Effortless Window Restoration After Dark Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/zenith-of-clarity-top-strategies-for-combating-blurry-windows-views/"><u>Zenith of Clarity: Top Strategies for Combating Blurry Windows Views</u></a></li>
</ul></div>
