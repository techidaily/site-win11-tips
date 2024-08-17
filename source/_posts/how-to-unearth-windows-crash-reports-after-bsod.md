---
title: How to Unearth Windows' Crash Reports After BSOD
date: 2024-08-16T02:06:16.391Z
updated: 2024-08-17T02:06:16.391Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Unearth Windows' Crash Reports After BSOD
excerpt: This Article Describes How to Unearth Windows' Crash Reports After BSOD
keywords: Windows BSOD Logs,Find Windows Crash Reports,Access Post-BSOD Data,Post-Crash Diagnostics in Windows,Uncovering Windows Errors,BSOD Incident Investigation,Retrieving Windows Error Files
thumbnail: https://thmb.techidaily.com/4509b58b3a9a19b95f97977ea395ec0191792aea55bdaf18f72a70f3772092da.jpg
---

## How to Unearth Windows' Crash Reports After BSOD

 When your computer crashes and you face a Blue Screen of Death (BSOD), your system saves the details of the crash as a BSOD log, in a pre-defined location in Windows. This information gives you details about when the crash happened, what caused it, and sometimes even what to do to fix the problem.

 In this guide, we will first discuss where are the BSOD files located in Windows and then how to identify them. Once you have located a BSOD file, we will show you how to read it properly to understand the potential causes of the error and resolve the problem.

## Where Are the BSOD Log Files Located in Windows?

 You can find the BSOD log files in the Event Viewer, Control Panel, and Registry Editor in Windows. Below, we have listed the detailed steps for finding these files in all three of these utilities.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
### 1\. Find and Read the BSOD Log Files in the Event Viewer

 The Event Viewer is a tool developed by Microsoft for users to view system and program-related events in Windows. These events can include system errors, warnings, informational messages, and more. In other words, every issue you encounter (whether a minor glitch or a major crash) will be logged in the Event Viewer for later investigation and sharing with Microsoft.

 You can check out our detailed guide on [what the Event Viewer is and how it can be useful](https://www.makeuseof.com/windows-event-viewer-guide/) if you are unfamiliar with it.

 Here is how you can find the BSOD log files in the Event Viewer:

1. Right-click on the Windows icon in the taskbar and choose **Event Viewer** from the context menu.  
![Choose Event Viewer in the context menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/event-viewer.jpg)
2. Head over to the **Action** menu located at the top, and choose **Create Custom View** from the context menu.  
![Create a custom view in the Event viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/create-custom-view.jpg)
3. In the following dialog, expand the dropdown for **Logged** and choose the time when you encountered the issue.  
![Check the logged section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/custom-time.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
4. Now, move to the Event Level section and choose **Error**.  
![Event level of the error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/error-event-level.jpg)
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Expand the dropdown for **Event Logs** and checkmark the box for **Windows Logs**.  
![Choose Windows logs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-logs.jpg)

1. Click **OK** to proceed.
2. You will now be prompted to enter a name and description for the custom view you just created. Enter these details and click **OK**.  
![Create a filter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/name-event-viewer.jpg)
<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->
3. Once the view is created, you will be presented with a list of errors that occurred during the time frame you selected earlier. You can sort this information further in the Date and time section.  
![Check the Event Viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/event-viewer-11.jpg)
4. Next, locate the BSOD using details like the date and time again.
5. Once you find the targeted log, click on it.
6. Check both the General and Details tabs to get information about this error.

 Once you find the error code associated with the crash and the cause, you can look for solutions online, or head over to our guide that discusses [how to fix blue screen errors in Windows](https://www.makeuseof.com/tag/4-tips-fix-blue-screen-error/) if it's a bsod.

### 2\. Find and Read the BSOD Log Files in the Registry Editor

 In case using the Event Viewer does not work for you for some reason, you can use another Windows utility to locate and study the BSOD log files—the Registry Editor.

 Windows Registry Editor is an administrative-level utility that lets you control how Windows operates and interacts with hardware and software. The Registry stores information related to the hardware and software components of your system. This information in the Registry is stored in the form of keys and values, and by modifying these with the dedicated Registry Editor, you can customize the operations of your system.

 Listed below are the steps for finding the BSOD log files in the Registry Editor. Make sure you are logged into your system as an administrator before you proceed.

1. Press the **Win + R** keys to open Run.
2. Type "regedit" in Run and press **Ctrl + Shift + Enter** to launch the Registry Editor as an administrator.
3. Now, select **Yes** in the User Account Prompt.
4. Once you are inside the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\CrashControl`
5. Next, move to the right pane and right-click on an empty space anywhere.
6. Choose **New** \> **DWORD (32-bit) Value**.  
![Create a new DWORD value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/dword-policies.jpg)
<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Name this value as **DisplayParameters** and double-click on it.
8. Under Value data, type 1 and click **OK**.  
![Change the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/value-data-1.jpg)
9. Once done, restart your PC.

 Upon reboot, you should be able to view the log files without any problems.

### 3\. Find and Read the BSOD Log Files in the Control Panel

 The third way of finding and reading the BSOD log files is via the Control Panel. This approach offers a graphical representation of the log files using the Windows Reliability Monitor, unlike the methods we have explored previously.

 The Reliability Monitor, which is different than the Performance Monitor (see [Reliability Monitor vs. Performance Monitor](https://www.makeuseof.com/reliability-monitor-vs-performance-monitor/)) will show you a timeline of important system events that occurred on your computer including BSOD occurrences, software installations, application crashes, and other relevant events.

 Here is how you can use it to identify and fix problems that may affect your system:

1. Type Control Panel in the search area of the taskbar and click **Open**.
2. In the following window, choose **System and Security** \> **Security and Maintenance**.  
![Security and maintenance settings in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/security-maintenance.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
3. Click on **Maintenance** and then select **View reliability history**.  
![Check the reliability history of the system](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/view-realability-history.jpg)
4. You should now see a graph showing the reliability data. Look for red cross icons and blue (i) icons in the graph, as they show problematic events.  
![Reliability graph](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/realability-graph.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
5. Click on each of the icons to view its details. Keep repeating the process to locate the event you are looking for.

 You will be presented with information like the faulting application path, its name, fault module timestamp, exception code, etc. If this app caused a BSOD crash, then you can try ending its process via the Task Manager or uninstalling the app if it is not necessary.

 It is also a good idea to copy this information and send it to Microsoft for review if you cannot find a solution online.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## Learn How to Read Your BSOD Log Files and Resolve Your Crashes

 ​​​​​​Windows blue screen errors are nothing new, but since they only display messages like "Your PC encountered a problem" without describing the cause, it can be difficult to find a fix. Understanding how to read BSOD log files can not only help you identify the exact cause of the problem but also help you find the right solution.

 Whenever a component causes your system to crash, you can disable it and switch to a better alternative to avoid the problem.

 In this guide, we will first discuss where are the BSOD files located in Windows and then how to identify them. Once you have located a BSOD file, we will show you how to read it properly to understand the potential causes of the error and resolve the problem.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-web.techidaily.com/024-approved-the-numbers-game-how-much-does-adsense-pay-on-a-thousand-video-glimpses/"><u>[New] 2024 Approved  The Numbers Game  How Much Does AdSense Pay on a Thousand Video Glimpses?</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-essentials-for-picking-the-perfect-tiktok-backgrounds/"><u>[Updated] Essentials for Picking the Perfect TikTok Backgrounds</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-how-to-view-facebook-videos-with-apple-remote/"><u>[Updated] How to View Facebook Videos with Apple Remote</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-flickerframe-repository-review/"><u>[Updated] In 2024, FlickerFrame Repository Review</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-the-power-of-video-endorsements-in-advertising/"><u>[Updated] In 2024, The Power of Video Endorsements in Advertising</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-unlock-insights-into-video-popularity-via-rank-trackers/"><u>[Updated] Unlock Insights Into Video Popularity via Rank Trackers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-essential-tactics-for-control-panel-entry/"><u>10 Essential Tactics for Control Panel Entry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/13-tips-to-fix-windows-system-restore/"><u>13 Tips to Fix Windows System Restore</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-the-filmmakers-formula-for-unbeatable-tiktok-reaction-content-using-filmora/"><u>2024 Approved  The Filmmaker’s Formula for Unbeatable TikTok Reaction Content Using Filmora</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unlocking-hidden-gems-open-source-art-lists/"><u>2024 Approved  Unlocking Hidden Gems  Open-Source Art Lists</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-quick-ways-to-disable-usb-selective-suspend-in-windows-11/"><u>3 Quick Ways to Disable USB Selective Suspend in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-clear-the-microsoft-defender-protection-history-on-windows-10-and-11/"><u>4 Ways to Clear the Microsoft Defender Protection History on Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-alternative-protection-strategies-for-missing-bitlocker-in-winoss/"><u>5 Alternative Protection Strategies for Missing Bitlocker in WinOSs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-fix-the-checksum-error-in-winrar/"><u>6 Ways to Fix the Checksum Error in WinRAR</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-slick-techniques-to-launch-iis-manager/"><u>8 Slick Techniques to Launch IIS Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-compre-cookie-cutter-guide-to-revamping-your-pc-with-a-fresh-os/"><u>A Compre Cookie-Cutter Guide to Revamping Your PC with a Fresh OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-secrets-the-fastest-ways-to-uncover-windows-11s-credential-manager/"><u>Accessing Secrets: The Fastest Ways to Uncover Windows 11'S Credential Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-digital-dreamland-with-windows-pcs/"><u>Achieving Digital Dreamland with Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-system-called-fails-on-windows-1011/"><u>Addressing System Called Fails on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-10-and-11s-phishing-protection-settings/"><u>Adjusting Windows 10 & 11'S Phishing Protection Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjustment-assistants-best-windows-utilities-for-date-tweaking/"><u>Adjustment Assistants: Best Windows Utilities for Date Tweaking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-assistants-impact-on-windows-11-experience/"><u>AI Assistant's Impact on Windows 11 Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplified-audio-top-4-applications-to-surpass-windows-100-threshold/"><u>Amplified Audio: Top 4 Applications to Surpass Windows’ 100%% Threshold</u></a></li>
<li><a href="https://win11-tips.techidaily.com/artificial-intelligence-windows-future-trailblazer/"><u>Artificial Intelligence: Windows' Future Trailblazer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-act-keeping-high-vitality-in-check-on-windows/"><u>Balancing Act: Keeping High Vitality in Check on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beating-the-bug-fixing-frequent-apex-legends-crashes-on-windows-11/"><u>Beating the Bug: Fixing Frequent Apex Legends Crashes on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginners-guide-efficient-w11-microphone-use/"><u>Beginner's Guide: Efficient W11 Microphone Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-practices-unveiled-supercharge-wsl-2-with-windows-dev-tools/"><u>Best Practices Unveiled: Supercharge WSL 2 with Windows Dev Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beyond-boundaries-artificinas-intelligence-in-windows-11/"><u>Beyond Boundaries: Artificinas Intelligence in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blueprint-to-rule-winos-apps-browsers/"><u>Blueprint to Rule WinOS Apps, Browsers</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/budget-friendly-powerhouse-comparing-the-apple-ipad-air-4-with-ipad-pro/"><u>Budget-Friendly Powerhouse: Comparing the Apple iPad Air 4 with iPad Pro</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/essential-tools-for-perfect-linux-screenshots-for-2024/"><u>Essential Tools for Perfect Linux Screenshots for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-tecno-camon-30-pro-5g-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on Tecno Camon 30 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://os-tips.techidaily.com/fixing-an-unsuccessful-icloud-backup-for-android-and-ios-devices-a-comprehensive-guide/"><u>Fixing an Unsuccessful iCloud Backup for Android and iOS Devices – A Comprehensive Guide</u></a></li>
<li><a href="https://android-location.techidaily.com/getting-the-pokemon-go-gps-signal-not-found-11-error-in-infinix-smart-8-plus-drfone-by-drfone-virtual/"><u>Getting the Pokemon Go GPS Signal Not Found 11 Error in Infinix Smart 8 Plus | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-samsung-galaxy-m34-5gwithwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Samsung Galaxy M34 5Gwith/without a PC</u></a></li>
<li><a href="https://techidaily.com/how-to-get-out-of-dfu-mode-on-apple-iphone-11-pro-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Get Out of DFU Mode on Apple iPhone 11 Pro? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-complete-guide-for-apple-iphone-13-pro-lock-screen-drfone-by-drfone-ios/"><u>In 2024, Complete Guide For Apple iPhone 13 Pro Lock Screen | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-connecting-to-google-meet-laptop-plus-mobile/"><u>In 2024, Connecting to Google Meet  Laptop + Mobile</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-fast-tracking-fb-content-efficiency-strategies-explored/"><u>In 2024, Fast-Tracking FB Content  Efficiency Strategies Explored</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fixing-foneazy-mockgo-not-working-on-samsung-galaxy-a05-drfone-by-drfone-virtual-android/"><u>In 2024, Fixing Foneazy MockGo Not Working On Samsung Galaxy A05 | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-obs-versus-shadowplay-streaming-software-showdown/"><u>In 2024, OBS versus ShadowPlay - Streaming Software Showdown</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/showmore-screen-recorder-review-all-you-need-to-know-for-2024/"><u>ShowMore Screen Recorder Review  All You Need To Know for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-insiders-guide-to-top-ranking-titles/"><u>The Insider's Guide to Top-Ranking Titles</u></a></li>
<li><a href="https://android-unlock.techidaily.com/the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-samsung-galaxy-s23plus-by-drfone-android/"><u>The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On Samsung Galaxy S23+</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719266023156-zero-cost-local-gpt-clones-gpt4alls-window-solution/"><u>Zero-Cost Local GPT Clones: GPT4All's Window Solution.</u></a></li>
</ul></div>
