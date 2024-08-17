---
title: Unearthing Windows BSOD Indicators & Their Origins
date: 2024-08-16T02:41:53.309Z
updated: 2024-08-17T02:41:53.309Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unearthing Windows BSOD Indicators & Their Origins
excerpt: This Article Describes Unearthing Windows BSOD Indicators & Their Origins
keywords: BSOD Causes Analysis,System Crash Diagnosis,Blue Screen Errors Triggers,BIOS Boot Failures,Hardware Malfunction Signals,Windows Fault Indicators,Operating System Exceptions
thumbnail: https://thmb.techidaily.com/a6de986a3fdb94c7142abb7e1738397c8994a30f493de897d20f957481bc1b83.jpg
---

## Unearthing Windows BSOD Indicators & Their Origins

 When your computer crashes and you face a Blue Screen of Death (BSOD), your system saves the details of the crash as a BSOD log, in a pre-defined location in Windows. This information gives you details about when the crash happened, what caused it, and sometimes even what to do to fix the problem.

 In this guide, we will first discuss where are the BSOD files located in Windows and then how to identify them. Once you have located a BSOD file, we will show you how to read it properly to understand the potential causes of the error and resolve the problem.

## Where Are the BSOD Log Files Located in Windows?

 You can find the BSOD log files in the Event Viewer, Control Panel, and Registry Editor in Windows. Below, we have listed the detailed steps for finding these files in all three of these utilities.

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Find and Read the BSOD Log Files in the Event Viewer

 The Event Viewer is a tool developed by Microsoft for users to view system and program-related events in Windows. These events can include system errors, warnings, informational messages, and more. In other words, every issue you encounter (whether a minor glitch or a major crash) will be logged in the Event Viewer for later investigation and sharing with Microsoft.

 You can check out our detailed guide on [what the Event Viewer is and how it can be useful](https://www.makeuseof.com/windows-event-viewer-guide/) if you are unfamiliar with it.

 Here is how you can find the BSOD log files in the Event Viewer:

1. Right-click on the Windows icon in the taskbar and choose **Event Viewer** from the context menu.  
![Choose Event Viewer in the context menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/event-viewer.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
2. Head over to the **Action** menu located at the top, and choose **Create Custom View** from the context menu.  
![Create a custom view in the Event viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/create-custom-view.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
3. In the following dialog, expand the dropdown for **Logged** and choose the time when you encountered the issue.  
![Check the logged section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/custom-time.jpg)
4. Now, move to the Event Level section and choose **Error**.  
![Event level of the error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/error-event-level.jpg)
5. Expand the dropdown for **Event Logs** and checkmark the box for **Windows Logs**.  
![Choose Windows logs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-logs.jpg)

1. Click **OK** to proceed.
2. You will now be prompted to enter a name and description for the custom view you just created. Enter these details and click **OK**.  
![Create a filter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/name-event-viewer.jpg)
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Once the view is created, you will be presented with a list of errors that occurred during the time frame you selected earlier. You can sort this information further in the Date and time section.  
![Check the Event Viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/event-viewer-11.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Next, locate the BSOD using details like the date and time again.
5. Once you find the targeted log, click on it.
6. Check both the General and Details tabs to get information about this error.

 Once you find the error code associated with the crash and the cause, you can look for solutions online, or head over to our guide that discusses [how to fix blue screen errors in Windows](https://www.makeuseof.com/tag/4-tips-fix-blue-screen-error/) if it's a bsod.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
7. Name this value as **DisplayParameters** and double-click on it.
8. Under Value data, type 1 and click **OK**.  
![Change the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/value-data-1.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
9. Once done, restart your PC.

 Upon reboot, you should be able to view the log files without any problems.

### 3\. Find and Read the BSOD Log Files in the Control Panel

 The third way of finding and reading the BSOD log files is via the Control Panel. This approach offers a graphical representation of the log files using the Windows Reliability Monitor, unlike the methods we have explored previously.

 The Reliability Monitor, which is different than the Performance Monitor (see [Reliability Monitor vs. Performance Monitor](https://www.makeuseof.com/reliability-monitor-vs-performance-monitor/)) will show you a timeline of important system events that occurred on your computer including BSOD occurrences, software installations, application crashes, and other relevant events.

 Here is how you can use it to identify and fix problems that may affect your system:

1. Type Control Panel in the search area of the taskbar and click **Open**.
2. In the following window, choose **System and Security** \> **Security and Maintenance**.  
![Security and maintenance settings in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/security-maintenance.jpg)
3. Click on **Maintenance** and then select **View reliability history**.  
![Check the reliability history of the system](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/view-realability-history.jpg)
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
4. You should now see a graph showing the reliability data. Look for red cross icons and blue (i) icons in the graph, as they show problematic events.  
![Reliability graph](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/realability-graph.jpg)
5. Click on each of the icons to view its details. Keep repeating the process to locate the event you are looking for.

 You will be presented with information like the faulting application path, its name, fault module timestamp, exception code, etc. If this app caused a BSOD crash, then you can try ending its process via the Task Manager or uninstalling the app if it is not necessary.

 It is also a good idea to copy this information and send it to Microsoft for review if you cannot find a solution online.

## Learn How to Read Your BSOD Log Files and Resolve Your Crashes

 ​​​​​​Windows blue screen errors are nothing new, but since they only display messages like "Your PC encountered a problem" without describing the cause, it can be difficult to find a fix. Understanding how to read BSOD log files can not only help you identify the exact cause of the problem but also help you find the right solution.

 Whenever a component causes your system to crash, you can disable it and switch to a better alternative to avoid the problem.

 In this guide, we will first discuss where are the BSOD files located in Windows and then how to identify them. Once you have located a BSOD file, we will show you how to read it properly to understand the potential causes of the error and resolve the problem.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-posts.techidaily.com/new-become-a-periscope-wizard-with-our-full-guidebook/"><u>[New] Become a Periscope Wizard with Our Full Guidebook</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-optimizing-techniques-broadcasting-via-obs-to-facebook/"><u>[Updated] 2024 Approved  Optimizing Techniques  Broadcasting via OBS to Facebook</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-correcting-unsteady-flight-footage-artifacts/"><u>[Updated] Correcting Unsteady Flight Footage Artifacts</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-farm-frenzy-the-ultimate-group-game-guide-for-farms/"><u>[Updated] Farm Frenzy  The Ultimate Group Game Guide for Farms</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-audience-appeal-the-ultimate-guide-to-youtube-video-formats/"><u>[Updated] In 2024, Audience Appeal  The Ultimate Guide to YouTube Video Formats</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-the-fundamentals-of-creating-breathtaking-canon-time-lapses/"><u>[Updated] The Fundamentals of Creating Breathtaking Canon Time-Lapses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-full-screen-windows-alignment-in-windows/"><u>Achieving Full-Screen Windows Alignment in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-barriers-editing-your-win11-fax-pages-with-ease/"><u>Breaking Down Barriers: Editing Your Win11 Fax Pages with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-restrictions-for-microsoft-store-on-win11/"><u>Clearing Restrictions for Microsoft Store on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/craft-your-win11-boot-experience-steps-to-optimize-service-setups/"><u>Craft Your Win11 Boot Experience: Steps to Optimize Service Setups</u></a></li>
<li><a href="https://extra-hints.techidaily.com/deciphering-the-value-of-photoshop-sway-control/"><u>Deciphering the Value of Photoshop Sway Control</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/detailed-guide-of-ispoofer-for-pogo-installation-on-honor-x7b-drfone-by-drfone-virtual-android/"><u>Detailed guide of ispoofer for pogo installation On Honor X7b | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detailed-process-for-moving-qbittorrent-software-across-pcs/"><u>Detailed Process for Moving qBittorrent Software Across PCs</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/diving-into-digital-delights-facebook-video-repository/"><u>Diving Into Digital Delights  Facebook Video Repository</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-shortcuts-for-power-users-on-windows/"><u>Essential Shortcuts for Power Users on Windows</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/expert-evaluation-navigating-through-apple-books-digital-library/"><u>Expert Evaluation: Navigating Through Apple Books Digital Library</u></a></li>
<li><a href="https://win11-tips.techidaily.com/foster-robust-windows-application-connections-with-simple-fixes/"><u>Foster Robust Windows Application Connections with Simple Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-classic-to-continuous-understanding-windows-10-and-11s-evolution/"><u>From Classic to Continuous: Understanding Windows 10 & 11'S Evolution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-graphic-design-to-daily-use-ai-in-windows/"><u>From Graphic Design to Daily Use: AI in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-reopen-battlenet-desktop-client-on-windows-os/"><u>Guide to Reopen Battle.net Desktop Client on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-securely-manage-editing-accessibility/"><u>Guide to Securely Manage Editing Accessibility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-and-disable-the-windows-key/"><u>How to Enable and Disable the Windows Key</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fake-gps-on-apple-iphone-xs-max-for-mobile-legends-drfone-by-drfone-virtual-ios/"><u>How To Fake GPS On Apple iPhone XS Max For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-use-ispoofer-on-honor-magic-5-pro-drfone-by-drfone-virtual-android/"><u>How to use iSpoofer on Honor Magic 5 Pro? | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-can-i-catch-the-regional-pokemon-without-traveling-on-apple-iphone-6-drfone-by-drfone-virtual-ios/"><u>In 2024, How Can I Catch the Regional Pokémon without Traveling On Apple iPhone 6 | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-come-up-with-the-best-pokemon-team-on-nokia-c12-drfone-by-drfone-virtual-android/"><u>In 2024, How to Come up With the Best Pokemon Team On Nokia C12? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-ways-to-augment-folder-context-menus/"><u>Innovative Ways to Augment Folder Context Menus</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/inside-look-a-detailed-comparison-between-nintendo-switch-lite-and-oled-variant/"><u>Inside Look: A Detailed Comparison Between Nintendo Switch Lite & OLED Variant</u></a></li>
<li><a href="https://fake-location.techidaily.com/methods-to-change-gps-location-on-apple-iphone-se-2020-drfone-by-drfone-virtual-ios/"><u>Methods to Change GPS Location On Apple iPhone SE (2020) | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-open-secrets-of-windows-11-sticky-notes/"><u>Navigating the Open Secrets of Windows 11 Sticky Notes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-w11-way-to-alter-your-fax-cover-page/"><u>Navigating the W11 Way to Alter Your Fax Cover Page</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-update-obstacles-with-these-fixes/"><u>Overcome Update Obstacles with These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11-camera-issue-fixing-error-f429f/"><u>Overcoming Windows 11 Camera Issue: Fixing Error F429F</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redirecting-home-page-in-win11-settings/"><u>Redirecting Home Page in Win11 Settings</u></a></li>
<li><a href="https://driver-install.techidaily.com/revive-usb-support-on-classic-windows-operating-systems/"><u>Revive USB Support on Classic Windows Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-downloads-for-windows-top-10-choices-revealed/"><u>Secure Downloads for Windows: Top 10 Choices Revealed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-failed-windows-speech-recognition-initialization/"><u>Solving Failed Windows Speech Recognition Initialization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-reigniting-wifi-detection-in-windows-11-systems/"><u>Steps for Reigniting Wifi Detection in Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-roblox-unrecoverable-errors/"><u>Strategies to Overcome Roblox Unrecoverable Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tap-into-divine-interface-capabilities-in-windows-11/"><u>Tap Into Divine Interface Capabilities in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-end-of-windows-xp-7-and-81-era-from-microsoft/"><u>The End of Windows XP, 7 & 8.1 Era From Microsoft</u></a></li>
<li><a href="https://some-skills.techidaily.com/top-3-tactics-converting-pins-to-audio-clips-for-2024/"><u>Top 3 Tactics  Converting Pins to Audio Clips for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/unlocking-apple-iphone-12-mini-passcode-without-a-computer-by-drfone-ios/"><u>Unlocking Apple iPhone 12 mini Passcode without a Computer</u></a></li>
<li><a href="https://driver-error.techidaily.com/unwanted-bluetooth-stayin-fix-for-windows-11/"><u>Unwanted Bluetooth Stayin': Fix for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-display-experience-shift-to-adaptive-layouts/"><u>Upgrade Display Experience: Shift to Adaptive Layouts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-settings-returning-to-initial-touch-keyboard-configuration/"><u>Win 11 Settings: Returning to Initial Touch Keyboard Configuration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-guide-to-opening-quick-capture-utility/"><u>Windows 11 Guide to Opening Quick Capture Utility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/zeroing-out-0x800f0831-windows-troubleshoot-guide/"><u>Zeroing Out 0X800F0831: Windows Troubleshoot Guide</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>