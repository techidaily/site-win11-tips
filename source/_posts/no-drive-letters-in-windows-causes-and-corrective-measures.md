---
title: "No Drive Letters in Windows: Causes and Corrective Measures"
date: 2024-09-11T01:22:25.349Z
updated: 2024-09-12T01:22:25.349Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes No Drive Letters in Windows: Causes and Corrective Measures"
excerpt: "This Article Describes No Drive Letters in Windows: Causes and Corrective Measures"
keywords: No-Drive Windows Fix,Diskless PC Remedies,Drive-Less OS Solutions,Boot Without Disks Guide,Driveless Win Troubleshooting,Fix Windows No-Drive Issue,ZeroDrive System Repair
thumbnail: https://thmb.techidaily.com/a7b1079661cd8a131ebfc4e02675a90ed3f73ee624780bb20b2d8532eb393d21.jpg
---

## No Drive Letters in Windows: Causes and Corrective Measures

 Seeing the error message "drive letter not available" when accessing or creating a new storage drive can be very frustrating. The reason for the error isn't always immediately obvious, but it is rarely unsolvable.

 Here are the most common causes for an unavailable drive letter on Windows, and ways you can fix the problem.


>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>







<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139121/17108" target="_top" id="2139121">
  <img src="//a.impactradius-go.com/display-ad/17108-2139121" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139121/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## What Are Drive Letters in Windows?

 Any new storage drive, volume, or partition you add to your computer (especially if you[add a partition to your hard drive for optimum performance](https://www.makeuseof.com/how-to-partition-hard-drive/) ) needs to have a letter assigned before it will work. It is basically a label, a way for the system and the user to recognize different storage spaces.

 If a drive or partition does not have a letter assigned, it will be inaccessible to you and the software and services that may need to see the files in that space.

 Drive letters, occasionally called device letters, run alphabetically from A to Z. These days, A and B are rarely used, and we've covered before[why local drives on Windows start from "C"](https://www.makeuseof.com/why-local-drives-windows-start-from-c/) .

 New storage devices will be automatically assigned the first unused letter when connected. This automatic process occasionally fails or gets blocked by a conflict in the system settings.

 Upgrading from an older version of Windows to a new version can sometimes cause drive letters to be reassigned. Let's say that your applications all point to a particular drive, but that drive is now assigned a different letter. Things will get frustrating quickly if you can't select the letter you need.





<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130869/7443" target="_top" id="2130869">
  <img src="//a.impactradius-go.com/display-ad/7443-2130869" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130869/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Reasons Why Drive Letters Are Unavailable

 As mentioned, there are several possible reasons why you might see the "Drive letter not available" error. The most common reasons include:

### The Letter Is In Use by a Hidden Removable Drive

 When you connect a removable drive, such as a USB thumb drive, a drive letter will be assigned to it. Sometimes even after the removable drive is disconnected, the drive letter remains associated with it. In this case, it will be unavailable, and you'll see the error message.





<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134246/18498" target="_top" id="2134246">
  <img src="//a.impactradius-go.com/display-ad/18498-2134246" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134246/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




### The Letter Is Permanently Assigned to Another Storage Volume

 It is possible to permanently assign a drive letter to a particular partition or drive. This also includes optical devices like the CD/DVD drive. If you have previously done this, the drive letter will no longer be available to choose from when setting up a new partition or drive.





<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014853/22899" target="_top" id="2014853">
  <img src="//a.impactradius-go.com/display-ad/22899-2014853" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014853/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## How to Make Drive Letters Available for Use

 Both of the causes for the error detailed above are fixable. You can download free software to help with reassigning the letters. But you can also use the Windows Registry Editor to solve the problem yourself. Here's how.

1. Open the**Run dialog** by pressing**Win + R** .
2. Type**Regedit** and click**Ok** to open the Registry Editor.
3. Using either the panel on the left or the address field at the top, navigate to:**HKEY\_LOCAL\_MACHINE\\SYSTEM\\MountedDevices** .  
![Mounted devices in the Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/drive-letter-registry.jpg)
4. In the list of assigned devices, right-click on the one you want to change and select**Rename** .




<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137227/26400" target="_top" id="2137227">
  <img src="//a.impactradius-go.com/display-ad/26400-2137227" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137227/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




5. Change the drive letter to any other unused letter to free up the one being used.
6. Close the Registry Editor and restart your computer. You should then be able to assign the unused letter as you wish.

 If you prefer not to mess around with the Registry directly, you can use something like[AOMEI Partition Assistant Standard](https://www.diskpart.com/download-home.html) . The free version has limited tools but will let you reassign drive letters.

1. Open the Partition Assistant app and find the drive you want to reassign in the main window.
2. Right-click on the drive and select**Advanced > Change Drive Letter** from the menu.
3. In the new panel, use the dropdown menu to select a new and unused drive letter.  
![Changing a drive letter in third-party software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/partition-assistant-driveletter.jpg)
4. Click**Ok** and confirm the operation on the next screen. It may take a few seconds to process the change.
5. You can then return to the main screen, find the drive to which you want to assign that released letter, and repeat the process.





<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2120866/26400?prodsku=mars" target="_top" id="2120866">
  <img src="//a.impactradius-go.com/display-ad/26400-2120866" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2120866/26400?prodsku=mars" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Getting a Drive Letter Back on Windows

 Although frustrating, seeing the "Drive Letter Not Available" error is rarely due to an unsolvable issue. In most cases, you just need to force the change using the Registry Editor or a bit of third-party software. Either solution is fast and easy and should see your desired drive letter free to use quickly.


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
<li><a href="https://extra-approaches.techidaily.com/new-master-your-vision-with-these-6-premier-nft-tools/"><u>[New] Master Your Vision with These 6 Premier NFT Tools</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-content-creator-acclaim-through-subscriber-recognition/"><u>[Updated] Content Creator Acclaim Through Subscriber Recognition</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-best-practices-for-video-thumbnail-creation-in-the-digital-age/"><u>[Updated] In 2024, Best Practices for Video Thumbnail Creation in the Digital Age</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-transforming-android-devices-into-broadcast-powerhouses-with-obs/"><u>[Updated] In 2024, Transforming Android Devices Into Broadcast Powerhouses with OBS</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-vogue-videos-compiling-free-youtube-channel-frames/"><u>[Updated] In 2024, Vogue Videos Compiling FREE YouTube Channel Frames</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-streamsurf-skimming-above-dacast/"><u>[Updated] StreamSurf Skimming Above DaCast</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/captura-total-de-pantalla-optimizada-el-record-perfecto-para-pcs-con-windows/"><u>Captura Total De Pantalla Optimizada: El Récord Perfecto Para PCs Con Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combat-strategy-for-windows-error-code-0x8007045d/"><u>Combat Strategy for Windows' Error Code: 0X8007045D</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-dual-displays-in-windows-11-easy-guide/"><u>Configuring Dual Displays in Windows 11 Easy Guide</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/degrees-matter-rotating-videos-for-social-glory-for-2024/"><u>Degrees Matter Rotating Videos for Social Glory for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/designing-mythic-universes-via-chatgpt/"><u>Designing Mythic Universes via ChatGPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-your-multi-monitor-experience-with-top-window-brightness-controls/"><u>Elevating Your Multi-Monitor Experience with Top Window Brightness Controls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-intrusive-windows-tracking-systems/"><u>Eliminate Intrusive Windows Tracking Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/extend-windows-capacity-safely-and-intelligently/"><u>Extend Windows Capacity Safely & Intelligently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fathom-cpu-peaks-understanding-and-adjusting-with-windows-monitor/"><u>Fathom CPU Peaks: Understanding and Adjusting with Windows Monitor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-errors-with-copypaste-feature-on-windows-11/"><u>Fixing Errors with Copy/Paste Feature on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-black-screen-issue-on-cyberpunk-2077-a-comprehensive-guide/"><u>Fixing the Black Screen Issue on Cyberpunk 2077: A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-reboot-loop-into-bios-setup/"><u>Fixing Windows Reboot Loop Into BIOS Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hacks-to-modify-fixed-sleepwake-modes-in-win11/"><u>Hacks to Modify Fixed Sleep/Wake Modes in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harmonize-your-hours-regain-windows-rhythm/"><u>Harmonize Your Hours, Regain Windows Rhythm</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-lava-blaze-2-pro-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>How to Cast Lava Blaze 2 Pro Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reactivate-a-non-operational-win11-code/"><u>How to Reactivate a Non-Operational Win11 Code</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-the-activation-lock-on-your-ipad-and-apple-iphone-7-plus-without-apple-account-by-drfone-ios/"><u>How to Remove the Activation Lock On your iPad and Apple iPhone 7 Plus without Apple Account</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-resolve-razer-synapse-app-doesnt-start-up/"><u>How to Resolve 'Razer Synapse App Doesn't Start Up'</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-apps-from-xiaomi-civi-3-to-another-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Apps from Xiaomi Civi 3 to Another | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/howto-use-biometrics-with-windows-11-for-security/"><u>Howto: Use Biometrics with Windows 11 for Security</u></a></li>
<li><a href="https://review-topics.techidaily.com/identify-malfunctioning-your-hardware-drivers-with-windows-device-manager-on-windows-11-by-drivereasy-guide/"><u>Identify malfunctioning your hardware drivers with Windows Device Manager on Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/immediate-remedies-correcting-itbm-error-code-driver-unavailable/"><u>Immediate Remedies: Correcting ITBm Error Code 'Driver Unavailable'</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-gratuitous-green-backdrops-available/"><u>In 2024, Gratuitous Green Backdrops Available</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-the-ultimate-guide-to-vivo-s17t-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Ultimate Guide to Vivo S17t Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-top-10-budget-friendly-digital-photography-workspaces-online/"><u>In 2024, Top 10 Budget-Friendly Digital Photography Workspaces Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ipad-pro-vs-macbook-pro-showdown-discover-what-sets-them-apart/"><u>IPad Pro vs MacBook Pro Showdown: Discover What Sets Them Apart</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-of-fixing-winget-issues-w11-style/"><u>Master the Art of Fixing Winget Issues W11 Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-of-vocal-to-text-conversion-with-windows-whisper/"><u>Master the Art of Vocal to Text Conversion with Windows Whisper</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-steam-file-sync-in-windows-environment/"><u>Mastering Steam File Sync in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-issues-with-windows-character-map-functionality/"><u>Overcoming Issues with Windows Character Map Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-terminal-background-image/"><u>Personalizing Terminal Background Image</u></a></li>
<li><a href="https://extra-information.techidaily.com/pinterest-video-extraction-top-5-free-tools-ranked/"><u>Pinterest Video Extraction Top 5 Free Tools Ranked</u></a></li>
<li><a href="https://win11-tips.techidaily.com/propel-productivity-top-7-ways-to-use-windows-11-smartly/"><u>Propel Productivity: Top 7 Ways to Use Windows 11 Smartly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-the-windows-net-framework-obstacle-error/"><u>Remedying the Windows .NET Framework Obstacle Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-razers-controller-fixed-in-w10-and-w11/"><u>Resetting Razer's Controller: Fixed in W10 & W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-lack-of-hypervisor-in-windows-sandbox-environment/"><u>Resolving Lack of Hypervisor in Windows Sandbox Environment</u></a></li>
<li><a href="https://extra-tips.techidaily.com/reverse-video-order-on-your-ios-gadget/"><u>Reverse Video Order on Your iOS Gadget</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-file-selection-harnessing-checkboxes-in-windows-11/"><u>Simplifying File Selection: Harnessing Checkboxes in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-remove-hyber-v-from-windows-11-pro/"><u>Steps to Remove Hyber-V From Windows 11 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-windows-11-experience-enabling-end-task-on-taskbar/"><u>Tailoring Your Windows 11 Experience: Enabling End Task on Taskbar</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-google-pixel-8-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset Google Pixel 8 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-end-of-cortana-dawn-of-four-alternatives-in-windows/"><u>The End of Cortana, Dawn of Four Alternatives in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-guide-to-labeling-files-in-windows-11/"><u>The Essential Guide to Labeling Files in Windows 11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-9-chatgpt-add-ons-enhance-your-chatbot-experience-today/"><u>Top 9 ChatGPT Add-Ons: Enhance Your Chatbot Experience Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-c0000022-crash-in-windows-os/"><u>Troubleshooting C0000022 Crash in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-office-glitch-resetting-errors/"><u>Troubleshooting Windows Office Glitch: Resetting Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-fbm-potential-top-fixes-for-pc-users/"><u>Unlocking FBM Potential: Top Fixes for PC Users</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unveiling-fraudgpt-what-it-is-its-potential-harm-and-how-to-shield-yourself/"><u>Unveiling FraudGPT: What It Is, Its Potential Harm, and How to Shield Yourself</u></a></li>
<li><a href="https://win11-tips.techidaily.com/websites-halted-by-hardware-7-windows-fixes-for-browsing-blockades/"><u>Websites Halted by Hardware: 7 Windows Fixes for Browsing Blockades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-ram-cache-essentials-and-clearance-guide/"><u>Windows RAM Cache Essentials & Clearance Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-system-lifespan-indicator/"><u>Windows System Lifespan Indicator</u></a></li>
</ul></div>




