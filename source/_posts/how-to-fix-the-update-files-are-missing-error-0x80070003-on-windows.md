---
title: How to Fix the Update Files Are Missing Error 0X80070003 on Windows
date: 2024-08-16T01:43:42.552Z
updated: 2024-08-17T01:43:42.552Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the Update Files Are Missing Error 0X80070003 on Windows
excerpt: This Article Describes How to Fix the Update Files Are Missing Error 0X80070003 on Windows
keywords: Windows Update Issue Resolution,Troubleshoot Update Error 0X80070003,Fixing Missing Files in Windows Updates,Error 0X80070003 Solutions for Windows,Overcoming Update File Loss on PC,Resolving Windows 10 Update Failure,Stop Windows Updater Error 0X80070003
thumbnail: https://thmb.techidaily.com/eb6c43743edfe7719c43f746c3a62c94afe56182a98c24ab59e2903c5366daaa.jpg
---

## How to Fix the Update Files Are Missing Error 0X80070003 on Windows

 It's not unusual for Windows users to run into issues when installing updates or upgrading to the latest version of Windows. The problem with these error codes is that most of the time, they do not specify the cause of the error or what users can do to avoid it.

 A common error that users run into when trying to update their system is 0x80070003\. This error is accompanied by a message stating "Some update files are missing." Let's explore the reasons behind this issue and the solutions you can try to resolve it.

## Why Are Update Files Missing From Your PC?

 One or more of the following reasons might explain why you are experiencing the problem on your computer:

1. The Windows log file might have corrupt data files that are interfering with the update installation process in Windows. The best way to deal with corrupt files is by repairing them using the built-in Windows utilities. If that does not work, you can delete them to resolve the problem.
2. The essential system files have become corrupt. This scenario can be resolved by running the troubleshooting utilities described below. They can identify corrupt files and replace them with healthy ones.
3. The Windows update components required for the pending updates to install are not functioning properly, which is causing the system to throw the error Fortunately, repairing the corrupt components is easy and can be done within a few minutes using the Command Prompt.
4. The Windows Update service and other relevant services required by the system to install the pending updates are disabled or have become corrupt. In this case, you can simply restart the services to resolve the issue.

 Now that you know what might be causing the problem let’s see how to resolve this case of missing update files in Windows.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
## 1\. Delete the Contents of the DataStore Folder

 The DataStore folder in Windows is a log file that stores information about all the updates installed in the system. This folder is located in the SoftwareDistribution folder, which is a directory of update-related information in Windows.

 In several cases, the underlying issue was caused due to the corrupt components of the DataStore folder, which were interfering with the system’s update process. An easy way to resolve this issue is by deleting the contents of this folder or removing the Data Store folder as a whole. Both methods are safe to execute.

 We have described the steps for doing this below. However, if you do not want to delete the DataStore folder or its contents, you can also repair them. For that, follow the next method below.

1. Launch File Explorer and navigate to the following location below:  
`C:\Windows\SoftwareDistribution`  
![Software distribution](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-software-distribution.jpg)
2. Locate the**DataStore** folder in the SoftwareDistribution folder and right-click on it.
3. Choose**Delete** from the context menu.  
![Delete the DataStore folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/software-distribution-datastore-delete-1.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->
4. Click**Yes** in the confirmation prompt to proceed.

 Once the folder is deleted, open the Settings app and try installing the updates again.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
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
4. Wait for the command to execute, and then execute the following command:  
`Dism /Online /Cleanup-Image /ScanHealth`  
![DISM scanhealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/scanhealth.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
5. Next, proceed with the following command:  
`Dism /Online /Cleanup-Image /RestoreHealth`  
![DISM restorehealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/restorehealth.jpg)
6. Once this command is executed, close the Command Prompt window and check if you can now download the targeted updates.

 While you are at it, you can also [run the Windows Update troubleshooter](https://www.makeuseof.com/tag/windows-update-troubleshooter/) . This tool also works like the utilities we just described above. It will scan the system for errors and suggest you relevant fixes that can be applied using the troubleshooter as well.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
7. After the commands are executed, restart your computer. Hopefully, you will be able to install the pending updates on reboot.

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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-a-step-by-step-approach-to-rl-streaming/"><u>[New] 2024 Approved  A Step-by-Step Approach to RL Streaming</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-the-insiders-guide-to-mastering-igtv/"><u>[New] 2024 Approved  The Insider's Guide to Mastering IGTV</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-a-step-by-step-approach-to-downloading-memorable-moments-from-social-media-for-2024/"><u>[New] A Step-By-Step Approach to Downloading Memorable Moments From Social Media for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-in-depth-look-at-razers-hd-webcam-experience/"><u>[Updated] 2024 Approved  In-Depth Look at Razer's HD Webcam Experience</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-the-essential-guide-for-live-facebook-streams-pcmaclaptop/"><u>[Updated] 2024 Approved  The Essential Guide for Live Facebook Streams (PC/Mac/Laptop)</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-2024-approved-top-5-macos-safari-video-conversion-apps/"><u>[Updated] 2024 Approved  Top 5 macOS Safari Video Conversion Apps</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-in-depth-motion-assessment-2023/"><u>[Updated] In-Depth Motion Assessment 2023</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-leveraging-insta-archive-features-a-step-by-step-approach/"><u>[Updated] Leveraging Insta Archive Features  A Step-by-Step Approach</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-mastery-of-video-sharing-a-guide-to-utilizing-zoom-on-the-youtube-platform/"><u>2024 Approved  Mastery of Video Sharing  A Guide to Utilizing Zoom on the YouTube Platform</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-strategies-for-sustainable-brand-collaboration-with-youtubers/"><u>2024 Approved  Strategies for Sustainable Brand Collaboration with YouTubers</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/approved-tracking-trends-the-systematic-method-for-assessing-youtube-income-flows/"><u>2024 Approved  Tracking Trends  The Systematic Method for Assessing YouTube Income Flows</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-tecno-pop-8-system-crash-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Tecno Pop 8 System Crash Issue | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/access-denied-secure-your-windows-environment-with-these-4-tactics/"><u>Access Denied: Secure Your Windows Environment with These 4 Tactics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-a-three-dimensional-soundscape-in-windows-11/"><u>Achieving a Three-Dimensional Soundscape in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/audio-visual-assurance-verify-windows-equipment-before-calling/"><u>Audio Visual Assurance: Verify Windows Equipment Before Calling</u></a></li>
<li><a href="https://win-able.techidaily.com/boost-performance-fast-a-guide-to-effortless-shader-customization-in-swbfii/"><u>Boost Performance Fast! A Guide to Effortless Shader Customization in SWBFII</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-storage-demands-on-windows-os/"><u>Decoding the Storage Demands on Windows OS</u></a></li>
<li><a href="https://facebook.techidaily.com/digital-cupids-at-work-facebooks-novel-approach-to-matchmaking/"><u>Digital Cupids at Work: Facebook’s Novel Approach to Matchmaking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discreet-deletion-of-email-after-signing-in-windows/"><u>Discreet Deletion of Email After Signing In Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easily-overcome-response-incorrect-message/"><u>Easily Overcome Response Incorrect Message</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-search-on-windows-11-the-top-5-must-knows/"><u>Elevating Search on Windows 11: The Top 5 Must-Knows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-0x800f0845-from-windows-updates/"><u>Eradicating 0X800f0845 From Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-resolving-outlook-errors-on-windows/"><u>Expert Tips: Resolving Outlook Errors on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-and-restore-your-microsoft-store-registrations-win-11/"><u>Fix and Restore Your Microsoft Store Registrations (Win 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-bypass-disruptions-caused-by-new-windows-updates/"><u>How to Bypass Disruptions Caused by New Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-outlook-rules-not-working-on-windows/"><u>How to Fix Outlook Rules Not Working on Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-intercept-text-messages-on-motorola-razr-40-drfone-by-drfone-virtual-android/"><u>How to Intercept Text Messages on Motorola Razr 40 | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-honor-70-lite-5g-phone-without-password-by-drfone-android/"><u>How To Unlock Honor 70 Lite 5G Phone Without Password?</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/hugging-face-significance-and-utility/"><u>Hugging Face: Significance & Utility</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-effortless-screen-captures-for-pc-users-free-guide/"><u>In 2024, Effortless Screen Captures for PC Users (Free Guide)</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-final-cut-pro-x-achieving-perfect-vertical-video-for-instagram/"><u>In 2024, Final Cut Pro X  Achieving Perfect Vertical Video for Instagram</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-investing-in-the-right-keyboard-for-low-cost-maximum-output/"><u>In 2024, Investing in the Right Keyboard for Low Cost, Maximum Output</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-overcoming-deformed-video-playback-online/"><u>In 2024, Overcoming Deformed Video Playback Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-advanced-shortcuts-into-windows-explorer-menus/"><u>Integrating Advanced Shortcuts Into Windows Explorer Menus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-clis-for-efficient-task-management-windows-11/"><u>Integrating CLIs for Efficient Task Management (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-persistent-microsoft-edge-shortcuts/"><u>Preventing Persistent Microsoft Edge Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-functionality-of-windows-photo-viewer-in-win11/"><u>Restoring Functionality of Windows Photo Viewer in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-missing-data-from-windows-1011s-search-feature/"><u>Restoring Missing Data From Windows 10/11'S Search Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-directdraw-crashes-in-win11-a-step-by-step-guide/"><u>Solving DirectDraw Crashes in Win11: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-the-endless-cycle-of-windows-ui-issues/"><u>Stop the Endless Cycle of Windows UI Issues</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/syncing-songs-with-your-facebook-chronicles/"><u>Syncing Songs with Your Facebook Chronicles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-5-best-pc-optimization-tools-on-a-windows-pc/"><u>The 5 Best PC Optimization Tools on a Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-hidden-perils-behind-budget-windows-activation-codes/"><u>The Hidden Perils Behind Budget Windows Activation Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-surface-computer-firmware-update-manual/"><u>The Ultimate Surface Computer Firmware Update Manual</u></a></li>
<li><a href="https://win-howtos.techidaily.com/tips-and-solutions-for-restoring-microsoft-print-to-pdf-functionality-on-windows-11/"><u>Tips and Solutions for Restoring Microsoft Print to PDF Functionality on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-altering-window-icons-distance-on-11plus-windows/"><u>Title: Altering Window Icons' Distance on 11+ Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbo-charging-windows-printer-performance/"><u>Turbo-Charging WIndows Printer Performance</u></a></li>
<li><a href="https://apple-account.techidaily.com/turning-off-two-factor-authentication-from-apple-iphone-13-mini-5-tips-you-must-know-by-drfone-ios/"><u>Turning Off Two Factor Authentication From Apple iPhone 13 mini? 5 Tips You Must Know</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/ultimate-battlescape-chronicles-total-wars-sweepstakes/"><u>Ultimate Battlescape Chronicles  Total Wars Sweepstakes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-tackling-steam-disk-errors/"><u>Understanding and Tackling Steam Disk Errors</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/unlocking-asmr-potential-professional-filming-practices-revealed-for-2024/"><u>Unlocking ASMR Potential  Professional Filming Practices Revealed for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrading-graphic-memory-in-windows-11-systems/"><u>Upgrading Graphic Memory in Windows 11 Systems</u></a></li>
<li><a href="https://howto.techidaily.com/why-your-tecno-camon-20-pro-5g-screen-might-be-unresponsive-and-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Your Tecno Camon 20 Pro 5G Screen Might be Unresponsive and How to Fix It | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-wrinkle-free-up-operator-installation/"><u>Windows Wrinkle? Free Up Operator Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/workflow-enhancer-integrating-sticky-notes-into-your-windows-morning-ritual/"><u>Workflow Enhancer: Integrating Sticky Notes Into Your Windows Morning Ritual</u></a></li>
</ul></div>
