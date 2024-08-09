---
title: "Windows Memory Mapping: Uncovering RAM Types Easily"
date: 2024-08-08T10:59:17.223Z
updated: 2024-08-09T10:59:17.223Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Memory Mapping: Uncovering RAM Types Easily"
excerpt: "This Article Describes Windows Memory Mapping: Uncovering RAM Types Easily"
keywords: RAM Basics,Windows Mapped RAM,RAM Types Guide,Learn RAM Mapping,Uncovering RAM,Easy RAM Types,Memory Mapping Windows
thumbnail: https://thmb.techidaily.com/32e2647cfec7540fd7d33c1c66a7dde730efec2830801400ac767081505a0953.jpg
---

## Windows Memory Mapping: Uncovering RAM Types Easily

 Knowing the type of RAM installed on your Windows PC can help you make more informed decisions when upgrading or diagnosing performance issues. Thankfully, it’s possible to check the RAM type on your Windows PC without opening the computer case and getting your hands dirty.

 This guide will walk you through some easy methods for identifying the type of RAM housed within your computer.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
## 2\. How to Check the RAM Type With PowerShell

 Like Command Prompt, you can use PowerShell to find out the type of RAM installed on your Windows computer. Here are the steps for the same.

1. Press **Win + S** to open the search menu.
2. Type **powershell** in the box.
3. Select **Run as administrator**.
4. When the User Account Control (UAC) prompt appears, select **Yes** to continue.
5. Type the following command in the PowerShell window and hit **Enter**.  
`Get-CimInstance -ClassName Win32_PhysicalMemory | Format-Table SMBIOSMemoryType`  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Check RAM Type Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-ram-type-using-powershell.jpg)

 Under the **SMBIOSMemoryType** column, note down the code number and compare it with the following table to determine the RAM type.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
![A Table Showing RAM Type and Numeric Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/a-table-showing-ram-type-and-numeric-value.jpg)

## 3\. How to Check the RAM Type Using the Task Manager App

 Windows Task Manager can provide you with all the necessary hardware information you need about your PC, including the type of RAM installed. However, it's important to note that Task Manager does not show the memory type if your PC has [DDR4 or DDR5 RAM](https://www.makeuseof.com/ddr4-vs-ddr5-should-you-upgrade/). So, this method will only work for PCs with DDR3 or lower-generation RAM.

 To check the RAM type using Windows Task Manager, follow these steps:

1. Press **Ctrl + Shift + Esc** to open the Task Manager.
2. Switch to the **Performance** tab.
3. Select **Memory** from the left pane. You should see the amount and type of RAM your PC has in the top right corner of the screen.  
![Check Memory Type Using Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-windows-task-manager.jpg)

 The Windows Task Manager does more than show hardware information. You also use it to manage running programs, end tasks, and view resource usage. To learn more, read our guide on the best [Windows Task Manager tips that you may not know](https://www.makeuseof.com/tag/10-windows-task-manager-tricks-didnt-know/).

## 4\. How to Check the RAM Type Using CPU-Z

 If you're seeking a relatively uncomplicated method to check the RAM type along with other hardware details, you can use a third-party app like CPU-Z. It is available for free and allows you to access various sets of information about your computer, including details about both the CPU and the RAM.

 Download and open the [CPU-Z](https://www.cpuid.com/softwares/cpu-z.html) app on your PC. Click on the **Memory** tab to get a detailed breakdown of the installed RAM. Under the **General** section, look for the value in the **Type** field to know the type of RAM installed on your PC.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
![Check Memory Type Using CPU-Z App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-cpu-z-app.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
## Know the Type of RAM Installed on Your Windows PC

 The performance of your computer is affected not only by the amount of RAM installed but also by the type of RAM. Fortunately, identifying the RAM type on your Windows PC is a quick and painless process with the methods mentioned above.

 This guide will walk you through some easy methods for identifying the type of RAM housed within your computer.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-webster.techidaily.com/024-approved-transform-your-streaming-experience-through-youtubes-av1-technology/"><u>[New] 2024 Approved  Transform Your Streaming Experience Through YouTube's AV1 Technology</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-adaptive-speaking-methods-in-free-fire/"><u>[New] Adaptive Speaking Methods in Free Fire</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-directing-content-flow-uploading-imovie-films-to-youtube-for-2024/"><u>[New] Directing Content Flow  Uploading IMovie Films to YouTube for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-ensuring-accessibility-and-seo-with-responsive-design/"><u>[New] Ensuring Accessibility and SEO with Responsive Design</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-framework-for-utilizing-movies-as-learning-tools/"><u>[New] Framework for Utilizing Movies as Learning Tools</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-maximize-video-impact-with-full-screen-settings/"><u>[New] In 2024, Maximize Video Impact with Full-Screen Settings</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-simplified-video-posts-on-twitter-and-tumblr/"><u>[New] In 2024, Simplified Video Posts on Twitter and Tumblr</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-insiders-pathway-to-effective-auditory-notes/"><u>[New] The Insider’s Pathway to Effective Auditory Notes</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-audiovisual-power-evaluating-mirrorless-vs-dslr-cameras/"><u>[Updated] 2024 Approved  Audiovisual Power  Evaluating Mirrorless vs DSLR Cameras</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-elevate-your-youtube-channel-perfecting-video-scriptwriting-skills-for-2024/"><u>[Updated] Elevate Your YouTube Channel  Perfecting Video Scriptwriting Skills for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-comprehending-instagrams-max-video-length/"><u>[Updated] In 2024, Comprehending Instagram's Max Video Length</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-primary-movie-document-review-and-backup-titles/"><u>[Updated] In 2024, Primary Movie Document Review and Backup Titles</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-in-2024-streaming-screenshots-share-without-twitting/"><u>[Updated] In 2024, Streaming Screenshots  Share Without Twitting</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-making-your-videos-farewell-count-outro-essentials/"><u>[Updated] Making Your Video's Farewell Count  Outro Essentials</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-overcoming-iphones-difficulty-in-auto-focusing-issues-for-2024/"><u>[Updated] Overcoming iPhone's Difficulty in Auto-Focusing Issues for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/2-ways-to-transfer-text-messages-from-xiaomi-redmi-k70-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>2 Ways to Transfer Text Messages from Xiaomi Redmi K70 to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-optimize-your-audio-content-expert-tips-for-editing-in-garageband/"><u>2024 Approved  Optimize Your Audio Content  Expert Tips for Editing in GarageBand</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-quiet-quick-clean-auditory-connections/"><u>2024 Approved  Quiet, Quick, Clean Auditory Connections</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-art-of-optimizing-your-yt-channel-description/"><u>2024 Approved  The Art of Optimizing Your YT Channel Description</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-methods-for-removing-a-disks-partition-in-windows/"><u>3 Methods for Removing a Disk's Partition in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ingenious-ways-to-delete-a-drives-segmentation-in-windows/"><u>4 Ingenious Ways to Delete a Drive's Segmentation in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-fix-the-no-such-interface-supported-error-in-windows/"><u>5 Ways to Fix the No Such Interface Supported Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-fix-the-secure-boot-state-unsupported-error-in-windows/"><u>5 Ways to Fix the Secure Boot State Unsupported Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-strategies-to-fix-failed-security-codes-from-epic-games-on-windows/"><u>7 Strategies to Fix Failed Security Codes From Epic Games on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-superior-features-added-to-windows-11-feb-update/"><u>9 Superior Features Added to Windows 11, Feb Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-ways-to-fix-the-no-servers-found-error-in-apex-legends-for-windows/"><u>9 Ways to Fix the No Servers Found Error in Apex Legends for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-correcting-entry-not-found-message/"><u>A Guide to Correcting 'Entry Not Found' Message</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-efficient-language-switching-in-windows-11/"><u>A Guide to Efficient Language Switching in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-approach-to-probing-program-hideouts-in-windows/"><u>A Practical Approach to Probing Program Hideouts in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-to-new-windows-pin/"><u>A Step-by-Step Approach to New Windows PIN</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerated-assistance-top-tips-for-fixed-gameplay-on-pcs/"><u>Accelerated Assistance: Top Tips for Fixed Gameplay on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-d-drive-folder-in-windows-explorer/"><u>Accessing D: Drive Folder in Windows Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-folder-and-file-unity-a-windows-exploration/"><u>Achieving Folder & File Unity: A Windows Exploration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-fingerprint-authentication-in-windows-11/"><u>Activating Fingerprint Authentication in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-blank-screens-on-system-ignition/"><u>Addressing Blank Screens on System Ignition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-errors-caused-by-organization-managed-features-on-windows-11/"><u>Addressing Errors Caused by Organization-Managed Features on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-faulty-volume-adjustment-sliders/"><u>Addressing Faulty Volume Adjustment Sliders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-frozen-windows-guard-in-windows-11/"><u>Addressing Frozen Windows Guard in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-absentee-tab-button-on-your-pc/"><u>Addressing the Absentee Tab Button on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/aging-gracefully-upgrading-your-familys-old-computer/"><u>Aging Gracefully: Upgrading Your Family’s Old Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplifying-windows-protection-integrating-additional-firewall-settings-into-context-menu/"><u>Amplifying Windows Protection: Integrating Additional Firewall Settings Into Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-insider-look-at-microsofts-revolutionary-copilot-tool/"><u>An Insider Look at Microsoft's Revolutionary Copilot Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/anecdotal-insights-into-seamless-windows-11-setup/"><u>Anecdotal Insights Into Seamless Windows 11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/approaches-to-address-roblox-glitches/"><u>Approaches to Address Roblox Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/audio-visual-capture-mastery-snipping-tools-latest-recording-features-explained-max-156/"><u>Audio-Visual Capture Mastery: Snipping Tool's Latest Recording Features Explained (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automate-the-journey-always-command-prompt-admin-style/"><u>Automate the Journey: Always Command Prompt, Admin Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-downtime-disaster-essential-steps-for-checking-windows-11-device-availability/"><u>Avoid Downtime Disaster: Essential Steps for Checking Windows 11 Device Availability</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-frustration-easily-setup-icloud-on-windows-pc/"><u>Avoid Frustration: Easily Setup iCloud on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beating-the-bug-the-comprehensible-guide-for-resolving-error-0x800700e9-in-xbox-game-pass-and-windows-11/"><u>Beating the Bug: The Comprehensible Guide for Resolving Error 0X800700E9 in Xbox Game Pass & Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/black-friday-bonanza-get-your-deal-612-for-eternal-windows-10/"><u>Black Friday Bonanza: Get Your Deal - $6.12 for Eternal Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-disk-space-how-to-use-windows-autodeleting-feature/"><u>Boost Disk Space: How to Use Windows' AutoDeleting Feature</u></a></li>
<li><a href="https://games-able.techidaily.com/boosting-gearsports-frame-rate-tactics/"><u>Boosting Gearsports Frame Rate Tactics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-steam-downloads-combatting-speedy-slowdowns/"><u>Boosting Steam Downloads: Combatting Speedy Slowdowns</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-task-manager-admin-mode-on-windows-11/"><u>Boosting Task Manager: Admin Mode on Windows 11</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/effortless-image-and-video-integration-microsoft-teams-snap-camera-for-2024/"><u>Effortless Image and Video Integration  Microsoft Teams Snap Camera for 2024</u></a></li>
<li><a href="https://data-wizards.techidaily.com/expertise-in-videography-praises-from-patrons/"><u>Expertise in Videography, Praises From Patrons</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-erase-an-iphone-11-pro-without-apple-id-by-drfone-ios/"><u>How to Erase an iPhone 11 Pro without Apple ID?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719274715388-how-to-organize-your-notes-visually-with-obsidian-canvas/"><u>How to Organize Your Notes Visually with Obsidian Canvas</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719355808573-how-to-reactivate-and-rescue-non-responsive-printer-feature-via-win-plus-p-in-windows/"><u>How to Reactivate and Rescue Non-Responsive Printer Feature via Win + P in Windows.</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-view-mov-files-on-edge-2023-by-aiseesoft-video-converter-play-mov-on-android/"><u>How to view MOV files on Edge 2023 ?</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-creating-stunning-instagram-profile-screenshots/"><u>In 2024, Creating Stunning Instagram Profile Screenshots</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-do-i-stop-someone-from-tracking-my-realme-gt-neo-5-se-drfone-by-drfone-virtual-android/"><u>In 2024, How Do I Stop Someone From Tracking My Realme GT Neo 5 SE? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-detect-and-stop-mspy-from-spying-on-your-samsung-galaxy-f54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Detect and Stop mSpy from Spying on Your Samsung Galaxy F54 5G | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-samsung-galaxy-xcover-6-pro-tactical-edition-pin-codepattern-lockpassword-by-drfone-android/"><u>In 2024, How to Unlock Samsung Galaxy XCover 6 Pro Tactical Edition PIN Code/Pattern Lock/Password</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-motorola-razr-40-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Motorola Razr 40 Ultra | Dr.fone</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-the-ultimate-checklist-for-fpv-drone-propeller-selection/"><u>In 2024, The Ultimate Checklist for FPV Drone Propeller Selection</u></a></li>
<li><a href="https://youtube-help.techidaily.com/instant-aspect-ratio-tuning-for-youtube-on-mac-for-2024/"><u>Instant Aspect Ratio Tuning for Youtube on Mac for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/revitalize-your-device-the-importance-of-the-intel-82579lm-driver-update/"><u>Revitalize Your Device: The Importance of the Intel 82579LM Driver Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719205412582-shed-light-on-dark-windows-11-desktops-tips-inside/"><u>Shed Light on Dark Windows 11 Desktops - Tips Inside</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/the-art-of-vocal-performance-for-video-projects-for-2024/"><u>The Art of Vocal Performance for Video Projects for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719328507288-uncomplicated-start-menus-say-no-to-ads/"><u>Uncomplicated Start Menus - Say No to Ads!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719334255604-win11-chrome-issues-jumpstart-solution-suggestions/"><u>Win11 Chrome Issues? Jumpstart Solution Suggestions</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>