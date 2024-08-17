---
title: 4 Easy Ways to Check Your RAM Type on Windows
date: 2024-08-16T01:11:37.558Z
updated: 2024-08-17T01:11:37.558Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 4 Easy Ways to Check Your RAM Type on Windows
excerpt: This Article Describes 4 Easy Ways to Check Your RAM Type on Windows
keywords: RAM Check Guide Windows,Windows RAM Type Test,Learn RAM Identification,Windows RAM Verification,Find Windows RAM Type,Identify Windows RAM Model,Check RAM Type Windows
thumbnail: https://thmb.techidaily.com/4820926913a4a1263a46714c8a07c6721c528103224c7dceab692252cbf067a0.jpg
---

## 4 Easy Ways to Check Your RAM Type on Windows

 Knowing the type of RAM installed on your Windows PC can help you make more informed decisions when upgrading or diagnosing performance issues. Thankfully, it’s possible to check the RAM type on your Windows PC without opening the computer case and getting your hands dirty.

 This guide will walk you through some easy methods for identifying the type of RAM housed within your computer.

## 1\. How to Check the RAM Type With Command Prompt

 The most straightforward to check the RAM type on your Windows PC is via Command Prompt. You can use this method even [if you're a beginner with the Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/), as it only requires you to run a single command.

 Here's how you can check the RAM type on Windows using the Command Prompt:

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the menu that appears.
2. Select **Yes** when the User Account Control (UAC) prompt appears.
3. In the console, type the command mentioned below and press **Enter**.  
`wmic memorychip get devicelocator, memorytype`
4. Note down the code number under the **MemoryType** column.  
![Check Memory Type Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-command-prompt.jpg)

 Compare the numerical value from the **MemoryType** column with the following table to identify the RAM type. For instance, if the code number is **24**, it means your computer has **DDR3** RAM.

![A Table Showing RAM Type and Numeric Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/a-table-showing-ram-type-and-numeric-value.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
## 2\. How to Check the RAM Type With PowerShell

 Like Command Prompt, you can use PowerShell to find out the type of RAM installed on your Windows computer. Here are the steps for the same.

1. Press **Win + S** to open the search menu.
2. Type **powershell** in the box.
3. Select **Run as administrator**.
4. When the User Account Control (UAC) prompt appears, select **Yes** to continue.
5. Type the following command in the PowerShell window and hit **Enter**.  
`Get-CimInstance -ClassName Win32_PhysicalMemory | Format-Table SMBIOSMemoryType`  
![Check RAM Type Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-ram-type-using-powershell.jpg)

 Under the **SMBIOSMemoryType** column, note down the code number and compare it with the following table to determine the RAM type.

![A Table Showing RAM Type and Numeric Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/a-table-showing-ram-type-and-numeric-value.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. How to Check the RAM Type Using the Task Manager App

 Windows Task Manager can provide you with all the necessary hardware information you need about your PC, including the type of RAM installed. However, it's important to note that Task Manager does not show the memory type if your PC has [DDR4 or DDR5 RAM](https://www.makeuseof.com/ddr4-vs-ddr5-should-you-upgrade/). So, this method will only work for PCs with DDR3 or lower-generation RAM.

 To check the RAM type using Windows Task Manager, follow these steps:

1. Press **Ctrl + Shift + Esc** to open the Task Manager.
2. Switch to the **Performance** tab.
3. Select **Memory** from the left pane. You should see the amount and type of RAM your PC has in the top right corner of the screen.  
![Check Memory Type Using Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-windows-task-manager.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->

 The Windows Task Manager does more than show hardware information. You also use it to manage running programs, end tasks, and view resource usage. To learn more, read our guide on the best [Windows Task Manager tips that you may not know](https://www.makeuseof.com/tag/10-windows-task-manager-tricks-didnt-know/).

<!-- affiliate ads begin -->

<!-- affiliate ads end -->
## 4\. How to Check the RAM Type Using CPU-Z

 If you're seeking a relatively uncomplicated method to check the RAM type along with other hardware details, you can use a third-party app like CPU-Z. It is available for free and allows you to access various sets of information about your computer, including details about both the CPU and the RAM.

 Download and open the [CPU-Z](https://www.cpuid.com/softwares/cpu-z.html) app on your PC. Click on the **Memory** tab to get a detailed breakdown of the installed RAM. Under the **General** section, look for the value in the **Type** field to know the type of RAM installed on your PC.

![Check Memory Type Using CPU-Z App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-cpu-z-app.jpg)
<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Know the Type of RAM Installed on Your Windows PC

 The performance of your computer is affected not only by the amount of RAM installed but also by the type of RAM. Fortunately, identifying the RAM type on your Windows PC is a quick and painless process with the methods mentioned above.

 This guide will walk you through some easy methods for identifying the type of RAM housed within your computer.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-skills.techidaily.com/new-prime-panel-participant-prompter/"><u>[New] Prime Panel Participant Prompter</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-facebooks-blue-icon-decoding-its-meaning-in-chats/"><u>[Updated] Facebook's Blue Icon  Decoding Its Meaning in Chats</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-change-youtube-playback-speed-to-speed-up-or-slow-down-video-for-2024/"><u>[Updated] How to Change YouTube Playback Speed to Speed Up or Slow Down Video for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-celestial-craftsmanship-perfecting-night-portraits-step-by-step/"><u>[Updated] In 2024, Celestial Craftsmanship  Perfecting Night Portraits Step-by-Step</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-no-fuss-guide-to-recording-virtual-classes-on-windowsmacos-for-2024/"><u>[Updated] No-Fuss Guide to Recording Virtual Classes on Windows/macOS for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-guide-to-troubleshooting-the-windows-camera-app/"><u>A Complete Guide to Troubleshooting the Windows Camera App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-your-assault-fixing-lags-for-pc-warriors/"><u>Ace Your Assault: Fixing Lags for PC Warriors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-desktop-icon-chaos-in-windows/"><u>Avoid Desktop Icon Chaos in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-windows-experience-our-criteria-for-best-free-drivers/"><u>Boost Your Windows Experience: Our Criteria for Best Free Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/brilliant-obsidian-structure-for-clear-notes/"><u>Brilliant Obsidian Structure for Clear Notes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-microsoft-office-error-0x80041015-a-fix-guide/"><u>Conquering Microsoft Office Error 0X80041015: A Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/creating-your-perfect-reading-experience-notepad-customization-in-windows-11/"><u>Creating Your Perfect Reading Experience: Notepad Customization in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-breakdown-windows-saver-dynamics/"><u>Expert Breakdown: Windows Saver Dynamics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-java-vm-not-found-issue-on-windows-devices/"><u>Fixing Java VM Not Found Issue on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-deal-with-imminent-license-expiry-on-your-pc/"><u>How to Deal with Imminent License Expiry on Your PC</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/innovative-no-cost-solutions-for-modern-photography-enhancements-for-2024/"><u>Innovative No-Cost Solutions for Modern Photography Enhancements for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-your-machine-prepared-to-run-newest-windows-os/"><u>Is Your Machine Prepared to Run Newest Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterpiece-ahead-initiating-mspaint-windows-11-style/"><u>Masterpiece Ahead: Initiating MSPaint, Windows 11 Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-cursor-visibility-on-win-11-a-guide/"><u>Maximizing Cursor Visibility on Win 11: A Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-visibility-unveiling-windows-11s-system-tray-and-hidden-items/"><u>Maximizing Visibility: Unveiling Windows 11'S System Tray & Hidden Items</u></a></li>
<li><a href="https://win11-tips.techidaily.com/momentum-builds-with-windows-11s-upcoming-feature-unveil/"><u>Momentum Builds with Windows 11’S Upcoming Feature Unveil</u></a></li>
<li><a href="https://ai-video.techidaily.com/new-in-2024-maximize-yandex-translate-in-video-translation-and-beyond/"><u>New In 2024, Maximize Yandex Translate in Video Translation and Beyond</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-tips-ignoring-license-expires-messages-in-win11/"><u>Quick Tips: Ignoring ‘License Expires’ Messages in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restarting-the-windows-indexer-a-quick-guide/"><u>Restarting the Windows Indexer: A Quick Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revealing-the-hidden-search-bar-in-win11s-task-manager/"><u>Revealing the Hidden Search Bar in Win11's Task Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionize-your-workflow-why-the-latest-windows-outlook-matters/"><u>Revolutionize Your Workflow: Why the Latest Windows' Outlook Matters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-turning-onoff-secure-boot-in-virtualbox/"><u>Step-by-Step Guide: Turning On/Off Secure Boot in VirtualBox</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-instructions-creating-and-sharing-imessage-voicemails/"><u>Step-by-Step Instructions: Creating and Sharing iMessage Voicemails</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-windows-from-starting-spotify-by-default/"><u>Stop Windows From Starting Spotify by Default</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/streamline-software-maintenance-a-selection-of-top-11-gratis-program-update-tools/"><u>Streamline Software Maintenance: A Selection of Top 11 Gratis Program Update Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-performance-replacing-aged-technology/"><u>Streamlining Windows Performance: Replacing Aged Technology</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swivel-your-snaps-with-these-6-steps-for-windows-11-users/"><u>Swivel Your Snaps with These 6 Steps for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-checklist-for-dolby-atmos-installation-in-windows/"><u>The Essential Checklist for Dolby Atmos Installation in Windows</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/transforming-photos-to-videos-the-leading-snapchat-edit-tools-for-2024/"><u>Transforming Photos to Videos  The Leading Snapchat Edit Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-steam-library-accessibility-on-win-11-pcs/"><u>Troubleshooting Steam Library Accessibility on Win 11 PCs</u></a></li>
</ul></div>
