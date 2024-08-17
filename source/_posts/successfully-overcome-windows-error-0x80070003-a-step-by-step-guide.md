---
title: Successfully Overcome Windows Error 0X80070003 - A Step-by-Step Guide
date: 2024-08-16T01:53:18.422Z
updated: 2024-08-17T01:53:18.422Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Successfully Overcome Windows Error 0X80070003 - A Step-by-Step Guide
excerpt: This Article Describes Successfully Overcome Windows Error 0X80070003 - A Step-by-Step Guide
keywords: Fixing Error 0X80070003,Windows Error Resolution,WinError Code Repair,Overcoming Blue Screen,Step-by-Step System Fix,Troubleshoot WinError,ZeroX Error Guide
thumbnail: https://thmb.techidaily.com/5f066f9d9f5dd144763c4bbeccea3e56ce5ff6713b3a3e310bb03e72d6daf58f.jpg
---

## Successfully Overcome Windows Error 0X80070003 - A Step-by-Step Guide

 It's not unusual for Windows users to run into issues when installing updates or upgrading to the latest version of Windows. The problem with these error codes is that most of the time, they do not specify the cause of the error or what users can do to avoid it.

 A common error that users run into when trying to update their system is 0x80070003\. This error is accompanied by a message stating "Some update files are missing." Let's explore the reasons behind this issue and the solutions you can try to resolve it.

## Why Are Update Files Missing From Your PC?

 One or more of the following reasons might explain why you are experiencing the problem on your computer:

1. The Windows log file might have corrupt data files that are interfering with the update installation process in Windows. The best way to deal with corrupt files is by repairing them using the built-in Windows utilities. If that does not work, you can delete them to resolve the problem.
2. The essential system files have become corrupt. This scenario can be resolved by running the troubleshooting utilities described below. They can identify corrupt files and replace them with healthy ones.
3. The Windows update components required for the pending updates to install are not functioning properly, which is causing the system to throw the error Fortunately, repairing the corrupt components is easy and can be done within a few minutes using the Command Prompt.
4. The Windows Update service and other relevant services required by the system to install the pending updates are disabled or have become corrupt. In this case, you can simply restart the services to resolve the issue.

 Now that you know what might be causing the problem let’s see how to resolve this case of missing update files in Windows.

## 1\. Delete the Contents of the DataStore Folder

 The DataStore folder in Windows is a log file that stores information about all the updates installed in the system. This folder is located in the SoftwareDistribution folder, which is a directory of update-related information in Windows.

 In several cases, the underlying issue was caused due to the corrupt components of the DataStore folder, which were interfering with the system’s update process. An easy way to resolve this issue is by deleting the contents of this folder or removing the Data Store folder as a whole. Both methods are safe to execute.

 We have described the steps for doing this below. However, if you do not want to delete the DataStore folder or its contents, you can also repair them. For that, follow the next method below.

1. Launch File Explorer and navigate to the following location below:  
`C:\Windows\SoftwareDistribution`  
![Software distribution](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-software-distribution.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
2. Locate the**DataStore** folder in the SoftwareDistribution folder and right-click on it.
3. Choose**Delete** from the context menu.  
![Delete the DataStore folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/software-distribution-datastore-delete-1.jpg)
4. Click**Yes** in the confirmation prompt to proceed.

 Once the folder is deleted, open the Settings app and try installing the updates again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Run System Scans

 The next thing you can do is scan the system for potential issues. The best way to do this is by using built-in system utilities like the System File Checker and DISM.

 The System File Checker (SFC) will scan the protected system files for inconsistencies. If it finds a file that is corrupt, SFC will replace it with its healthier cached counterpart. DISM, on the other hand, will repair the system image.

 We will be using the Command Prompt to run these tools. Make sure you are logged into Windows as an administrator before proceeding:

Here is all that you need to do:

1. Open Command Prompt as an administrator (see [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for instructions).
2. Click**Yes** in the User Account Control prompt.
3. In the Command Prompt window, type the command mentioned below and hit**Enter** .  
`sfc /scannow`  
![SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/sfc-scannow.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
4. Wait for the command to execute, and then execute the following command:  
`Dism /Online /Cleanup-Image /ScanHealth`  
![DISM scanhealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/scanhealth.jpg)
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Next, proceed with the following command:  
`Dism /Online /Cleanup-Image /RestoreHealth`  
![DISM restorehealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/restorehealth.jpg)
6. Once this command is executed, close the Command Prompt window and check if you can now download the targeted updates.

 While you are at it, you can also [run the Windows Update troubleshooter](https://www.makeuseof.com/tag/windows-update-troubleshooter/) . This tool also works like the utilities we just described above. It will scan the system for errors and suggest you relevant fixes that can be applied using the troubleshooter as well.

## 3\. Repair the Update Components

 As we mentioned earlier, the update components can also deal with some kind of corruption, leading to the problem under discussion.

 The good news is that repairing these components is quite simple, and we will also use the Command Prompt in this method. We recommend [creating a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed. This will help you revert to the current system state in case something goes wrong during the execution of the method.

Once the restore point is created, follow these steps:

1. Open a Run dialog box (see [how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) to learn how).
2. Type cmd in the text field of Run and press Ctrl + Shift + Enter to open Command Prompt as an administrator.
3. Click**Yes** in the User Account Control prompt.
4. Once you are inside the Command Prompt, execute the commands below one by one:  
`<code>net stop wuauserv  
net stop cryptSvc  
net stop bits  
net stop msiserver`  
``` `` ```
5. Once all the services are stopped, execute the following commands. These will clear the update cache in the system:  
`<code>ren %systemroot%\softwaredistribution softwaredistribution.bak  
ren %systemroot%\system32\catroot2 catroot2.bak`  
``` `` ```
6. Now, proceed with the following commands one by one to start the Windows update services again:  
`<code>net start wuauserv  
net start bits  
net start cryptsvc  
net start trustedinstaller  
net start appidsvc`  
![Restart the update services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/restart-the-services.jpg)
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
7. After the commands are executed, restart your computer. Hopefully, you will be able to install the pending updates on reboot.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## Get the Missing Update Files Back on Windows

 Hopefully, by now, you should have successfully resolved the annoying update error. In case you are still facing the issue, you can use the Microsoft update catalog to install the updates manually. It may also be a good idea to report this issue to the Microsoft support team so they can launch an official fix for the problem.


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
<li><a href="https://facebook-video-share.techidaily.com/new-tech-savvy-simplified-your-guide-to-making-10-easy-youtube-videos/"><u>[New] Tech Savvy Simplified  Your Guide to Making 10 Easy YouTube Videos</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-pro-streamers-choice-the-top-5-gaming-webcams-to-own/"><u>[Updated] 2024 Approved  Pro Streamer's Choice  The Top 5 Gaming Webcams to Own</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-add-dynamic-blur-to-images-a-photoshop-journey/"><u>2024 Approved  Add Dynamic Blur to Images – A Photoshop Journey</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/4-ways-to-mirror-apple-iphone-se-to-laptop-via-usb-or-wi-fi-drfone-by-drfone-ios/"><u>4 Ways to Mirror Apple iPhone SE to Laptop via USB or Wi-Fi | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-guide-to-enhancing-performance-in-your-new-windows-11-setup/"><u>A Quick Guide to Enhancing Performance in Your New Windows 11 Setup</u></a></li>
<li><a href="https://extra-resources.techidaily.com/a-list-of-android-podcast-picks-for-2024/"><u>A-List of Android Podcast Picks for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-windows-component-services-interface-quickly/"><u>Accessing Windows' Component Services Interface Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-items-to-windows-11-desktop-menu-hierarchy/"><u>Adding Items to Windows 11 Desktop Menu Hierarchy</u></a></li>
<li><a href="https://activate-lock.techidaily.com/bypass-icloud-activation-lock-with-imei-code-from-iphone-8-plus-by-drfone-ios/"><u>Bypass iCloud Activation Lock with IMEI Code From iPhone 8 Plus</u></a></li>
<li><a href="https://fox-helps.techidaily.com/deliberate-pixels-top-cameras-to-freeze-time-in-video/"><u>Deliberate Pixels  Top Cameras to Freeze Time in Video</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-writing-game-wins-finest-tools/"><u>Elevate Your Writing Game – Win's Finest Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-group-policies-in-windows-via-tripartite-lens/"><u>Exploring Group Policies in Windows via Tripartite Lens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/finding-lightweight-browsers-for-chromeoswindowsmacos-ram-and-cpu-wise/"><u>Finding Lightweight Browsers for ChromeOS/Windows/macOS: RAM & CPU-Wise</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/full-tutorial-to-bypass-your-nubia-z50-ultra-face-lock-by-drfone-android/"><u>Full Tutorial to Bypass Your Nubia Z50 Ultra Face Lock?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-your-system-ready-for-windows-11-with-our-top-3-usb-tips/"><u>Get Your System Ready for Windows 11 with Our Top 3 USB Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-start-wordpad-in-a-windows-desktop/"><u>How to Start WordPad in a Windows Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-streamline-note-taking-with-win-11-display-rules/"><u>How to Streamline Note-Taking with Win 11 Display Rules</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-ispoofer-on-samsung-galaxy-s23plus-drfone-by-drfone-virtual-android/"><u>How to use iSpoofer on Samsung Galaxy S23+? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-solutions-to-find-your-samsung-galaxy-a14-5g-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Solutions to Find Your Samsung Galaxy A14 5G Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-ace-memes-top-template-compendium/"><u>In 2024, Ace Memes  Top Template Compendium</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-action-camera-selection-under-200-high-quality-low-cost/"><u>In 2024, Action Camera Selection Under $200  High Quality, Low Cost</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-stolen-apple-iphone-14-plus-in-different-conditionsin-drfone-by-drfone-ios/"><u>In 2024, How To Unlock Stolen Apple iPhone 14 Plus In Different Conditionsin | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-pokemon-go-cooldown-chart-on-asus-rog-phone-7-ultimate-drfone-by-drfone-virtual-android/"><u>In 2024, Pokémon Go Cooldown Chart On Asus ROG Phone 7 Ultimate | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-resolving-skewed-online-video-quality/"><u>In 2024, Resolving Skewed Online Video Quality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-comparison-dissecting-key-differences-between-local-and-microsoft-logins-in-os/"><u>In-Depth Comparison: Dissecting Key Differences Between Local & Microsoft Logins in OS</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/is-your-apple-iphone-12-mini-in-security-lockout-proper-ways-to-unlock-drfone-by-drfone-ios/"><u>Is Your Apple iPhone 12 mini in Security Lockout? Proper Ways To Unlock | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-accurate-typing-remedying-the-issue-of-miskeyed-letters/"><u>Mastering Accurate Typing: Remedying the Issue of Miskeyed Letters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-immediate-folder-upload-tackling-onedrive-errors/"><u>Mastering Immediate Folder Upload: Tackling OneDrive Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-nullified-network-visibility-in-windows/"><u>Navigating Through Nullified Network Visibility in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-device-disconnection-dxgi-error-guide/"><u>Overcoming Device Disconnection: DXGI Error Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-vmware-crashes-a-guide-for-win11-users/"><u>Overcoming VMware Crashes: A Guide for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinventing-win11s-configuration-interface/"><u>Reinventing Win11's Configuration Interface</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-your-windows-11-copy-and-paste-malfunction-easily/"><u>Resolving Your Windows 11 'Copy & Paste' Malfunction Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revising-the-start-page-to-a-new-preference-in-win11/"><u>Revising the Start Page to a New Preference in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-strategies-windows-voice-logging/"><u>Step-by-Step Strategies: Windows Voice Logging</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-multitasking-enhancing-windows-11-widget-capabilities/"><u>Streamlining Multitasking: Enhancing Windows 11 Widget Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-app-experience-win11-color-automation/"><u>Tailoring Your App Experience: Win11 Color Automation</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-role-of-look-up-tables-in-cinematic-coloring-for-2024/"><u>The Role of Look-Up Tables in Cinematic Coloring for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-prolong-pin-length-for-enhanced-safety/"><u>Tips to Prolong PIN Length for Enhanced Safety</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-telegram-spy-tools-on-oppo-find-n3-for-parents-drfone-by-drfone-virtual-android/"><u>Top 10 Telegram Spy Tools On Oppo Find N3 for Parents | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/transforming-courtship-through-technology-leveraging-chatgpt-for-better-connections/"><u>Transforming Courtship Through Technology: Leveraging ChatGPT for Better Connections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tricking-eyes-vanish-taskbar-search-in-windows-11/"><u>Tricking Eyes: Vanish Taskbar Search in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-the-power-of-sandbox-with-win-11/"><u>Unleashing the Power of Sandbox with Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-ip-and-mac-info-with-windows-powershell/"><u>Unraveling IP and MAC Info with Windows Powershell</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-stronger-side-why-you-should-opt-for-win11/"><u>Unveiling the Stronger Side: Why You Should Opt for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/w11-addressing-undetected-additional-monitor/"><u>W11: Addressing Undetected Additional Monitor</u></a></li>
<li><a href="https://win-blog.techidaily.com/warzone-wont-start-troubleshooting-common-issues/"><u>Warzone Won't Start: Troubleshooting Common Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-compatibility-tips-synapse-reinstatement-guide/"><u>Win Compatibility Tips: Synapse Reinstatement Guide</u></a></li>
</ul></div>
