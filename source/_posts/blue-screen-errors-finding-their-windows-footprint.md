---
title: "Blue Screen Errors: Finding Their Windows Footprint"
date: 2024-08-08T10:53:53.506Z
updated: 2024-08-09T10:53:53.506Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Blue Screen Errors: Finding Their Windows Footprint"
excerpt: "This Article Describes Blue Screen Errors: Finding Their Windows Footprint"
keywords: Blue Screens Woes,Win Error Fixing,Debugging Blues,System Crash Guide,PC Blue Outage,Fixing Screen Fail,Windows Troubleshoot
thumbnail: https://thmb.techidaily.com/14af88c4727edfc68754682f8d9e5a16b4632ead51b56f451896cf5d83dd52e4.jpg
---

## Blue Screen Errors: Finding Their Windows Footprint

 When your computer crashes and you face a Blue Screen of Death (BSOD), your system saves the details of the crash as a BSOD log, in a pre-defined location in Windows. This information gives you details about when the crash happened, what caused it, and sometimes even what to do to fix the problem.

 In this guide, we will first discuss where are the BSOD files located in Windows and then how to identify them. Once you have located a BSOD file, we will show you how to read it properly to understand the potential causes of the error and resolve the problem.

## Where Are the BSOD Log Files Located in Windows?

 You can find the BSOD log files in the Event Viewer, Control Panel, and Registry Editor in Windows. Below, we have listed the detailed steps for finding these files in all three of these utilities.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Find and Read the BSOD Log Files in the Event Viewer

 The Event Viewer is a tool developed by Microsoft for users to view system and program-related events in Windows. These events can include system errors, warnings, informational messages, and more. In other words, every issue you encounter (whether a minor glitch or a major crash) will be logged in the Event Viewer for later investigation and sharing with Microsoft.

 You can check out our detailed guide on [what the Event Viewer is and how it can be useful](https://www.makeuseof.com/windows-event-viewer-guide/) if you are unfamiliar with it.

 Here is how you can find the BSOD log files in the Event Viewer:

1. Right-click on the Windows icon in the taskbar and choose **Event Viewer** from the context menu.  
<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Choose Event Viewer in the context menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/event-viewer.jpg)
2. Head over to the **Action** menu located at the top, and choose **Create Custom View** from the context menu.  
![Create a custom view in the Event viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/create-custom-view.jpg)
3. In the following dialog, expand the dropdown for **Logged** and choose the time when you encountered the issue.  
![Check the logged section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/custom-time.jpg)
4. Now, move to the Event Level section and choose **Error**.  
![Event level of the error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/error-event-level.jpg)
5. Expand the dropdown for **Event Logs** and checkmark the box for **Windows Logs**.  
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
![Choose Windows logs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-logs.jpg)

1. Click **OK** to proceed.
2. You will now be prompted to enter a name and description for the custom view you just created. Enter these details and click **OK**.  
![Create a filter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/name-event-viewer.jpg)
3. Once the view is created, you will be presented with a list of errors that occurred during the time frame you selected earlier. You can sort this information further in the Date and time section.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
7. Name this value as **DisplayParameters** and double-click on it.
8. Under Value data, type 1 and click **OK**.  
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Change the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/value-data-1.jpg)
9. Once done, restart your PC.

 Upon reboot, you should be able to view the log files without any problems.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
### 3\. Find and Read the BSOD Log Files in the Control Panel

 The third way of finding and reading the BSOD log files is via the Control Panel. This approach offers a graphical representation of the log files using the Windows Reliability Monitor, unlike the methods we have explored previously.

 The Reliability Monitor, which is different than the Performance Monitor (see [Reliability Monitor vs. Performance Monitor](https://www.makeuseof.com/reliability-monitor-vs-performance-monitor/)) will show you a timeline of important system events that occurred on your computer including BSOD occurrences, software installations, application crashes, and other relevant events.

 Here is how you can use it to identify and fix problems that may affect your system:

1. Type Control Panel in the search area of the taskbar and click **Open**.
2. In the following window, choose **System and Security** \> **Security and Maintenance**.  
![Security and maintenance settings in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/security-maintenance.jpg)
3. Click on **Maintenance** and then select **View reliability history**.  
![Check the reliability history of the system](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/view-realability-history.jpg)
4. You should now see a graph showing the reliability data. Look for red cross icons and blue (i) icons in the graph, as they show problematic events.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
![Reliability graph](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/realability-graph.jpg)
5. Click on each of the icons to view its details. Keep repeating the process to locate the event you are looking for.

 You will be presented with information like the faulting application path, its name, fault module timestamp, exception code, etc. If this app caused a BSOD crash, then you can try ending its process via the Task Manager or uninstalling the app if it is not necessary.

 It is also a good idea to copy this information and send it to Microsoft for review if you cannot find a solution online.

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-enhancing-youtube-presence-creating-professional-thumbnails-from-smartphones/"><u>[New] 2024 Approved  Enhancing YouTube Presence  Creating Professional Thumbnails From Smartphones</u></a></li>
<li><a href="https://article-files.techidaily.com/new-2024-approved-unveiling-the-10-leading-christian-church-streamers/"><u>[New] 2024 Approved  Unveiling The 10 Leading Christian Church Streamers</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-streamlined-conversion-experience-superior-video-to-text-software/"><u>[New] Streamlined Conversion Experience  Superior Video-to-Text Software</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-converting-twitter-video-lyrics-to-custom-gif-animations/"><u>[Updated] 2024 Approved  Converting Twitter Video Lyrics to Custom GIF Animations</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-best-5-web-based-titling-aces-identified/"><u>[Updated] Best 5 Web-Based Titling Aces Identified</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-crafting-success-while-catching-up-on-all-the-latest-talks/"><u>[Updated] Crafting Success While Catching Up on All the Latest Talks</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-practical-techniques-for-downloading-youtube-srt/"><u>[Updated] Practical Techniques for Downloading YouTube SRT</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-the-essentials-of-screen-capture-with-fraps/"><u>[Updated] The Essentials of Screen Capture with Fraps</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-dial-down-dynamic-range-with-ease/"><u>2024 Approved  Dial Down Dynamic Range with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-your-non-operational-windows-11-hotspot/"><u>Activating Your Non-Operational Windows 11 Hotspot</u></a></li>
<li><a href="https://extra-tips.techidaily.com/best-choices-essential-support-gear-for-your-gopro-camera-for-2024/"><u>Best Choices  Essential Support Gear for Your GoPro Camera for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-security-implementing-controlled-access-in-windows/"><u>Command Security: Implementing Controlled Access in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-error-0x8000ffff-in-windows-based-printers/"><u>Conquering Error 0X8000FFFF in Windows-Based Printers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/craft-the-perfect-christmas-look-in-windows-11/"><u>Craft the Perfect Christmas Look in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-the-prime-8-video-cutter-tools-on-windows/"><u>Discover the Prime 8 Video Cutter Tools on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-wintoys-a-brief-dive-into-a-formidable-windows-feature/"><u>Discovering WinToys: A Brief Dive Into a Formidable Windows Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-way-to-unlink-wi-fi-on-windows-11/"><u>Efficient Way to Unlink Wi-Fi on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-savings-with-w11-pro-key-access-prime-deals/"><u>Elevate Savings with W11 Pro Key: Access Prime Deals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-work-with-multiple-displays-in-win11/"><u>Elevate Your Work with Multiple Displays in Win11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/everything-you-need-to-know-about-lock-screen-settings-on-your-vivo-y100i-power-5g-by-drfone-android/"><u>Everything You Need to Know about Lock Screen Settings on your Vivo Y100i Power 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-chrome-freeze-and-blank-screens/"><u>Fixing the Chrome Freeze and Blank Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-engage-window-management-feature-in-windows-11-end-task/"><u>How to Engage Window Management Feature in Windows 11 (End Task)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-audacitys-internal-portaudio-error-in-windows-10-and-11/"><u>How to Fix Audacity’s Internal PortAudio Error in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-lock-windows-safescreen-state-against-user-change/"><u>How to Lock Windows SafeScreen State Against User Change</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-an-airtag-from-your-apple-id-account-on-apple-iphone-15-plus-by-drfone-ios/"><u>How to Remove an AirTag from Your Apple ID Account On Apple iPhone 15 Plus?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-suppression-of-windows-11-notifications/"><u>Immediate Suppression of Windows 11 Notifications</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-film-talents-unleashed-downloadable-content-pass/"><u>In 2024, Film Talents Unleashed  Downloadable Content Pass</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-track-imei-number-of-realme-12-5g-through-google-earth-by-drfone-android/"><u>In 2024, How To Track IMEI Number Of Realme 12 5G Through Google Earth?</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-perfecting-virtual-presentations-key-practices-for-using-skypes-screen-share-feature/"><u>In 2024, Perfecting Virtual Presentations  Key Practices for Using Skype’s Screen Share Feature</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-prodigious-8-cameras-enhancing-video-quality-in-broadcast/"><u>In 2024, Prodigious 8 Cameras Enhancing Video Quality in Broadcast</u></a></li>
<li><a href="https://extra-information.techidaily.com/instantaneous-change-from-srt-to-txt-with-our-proven-methods/"><u>Instantaneous Change From SRT to TXT with Our Proven Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jolt-from-hibernation-freeze-on-your-pc/"><u>Jolt From Hibernation Freeze on Your PC</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-fcpx-on-a-budget-10-essential-free-plugins/"><u>New 2024 Approved FCPX on a Budget 10 Essential Free Plugins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/no-more-frustrations-installation-fixes-for-missing-windows-upgrades/"><u>No More Frustrations! Installation Fixes for Missing Windows Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-greyed-out-unlock-pin-function-in-windows-11/"><u>Overcoming Greyed Out Unlock Pin Function in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/preventing-disruptive-print-spooler-failures-on-pcs/"><u>Preventing Disruptive Print Spooler Failures on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quelling-irregular-beats-soundcard-irq-solutions/"><u>Quelling Irregular Beats: Soundcard IRQ Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-control-of-lock-screen-delay-on-pcs/"><u>Regaining Control of Lock Screen Delay on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/reinstate-your-favorite-microsoft-store-for-windows-devices/"><u>Reinstate Your Favorite Microsoft Store for Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719365826035-resolve-camera-woes-in-windows-heres-how/"><u>Resolve Camera Woes in Windows, Here’s How!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-wobbling-keyboard-arrows-in-windows-environments/"><u>Revive Wobbling Keyboard Arrows in Windows Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-dolby-atmos-installation-in-windows-1111/"><u>Seamless Dolby Atmos Installation in Windows 11/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-administrator-privileges-denial-in-cmd-prompt/"><u>Solving Administrator Privileges Denial in Cmd Prompt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-overcome-insufficient-access-during-uninstall/"><u>Steps to Overcome Insufficient Access During Uninstall</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-amend-out-of-memory-issues-in-hogwarts-adventures/"><u>Strategies to Amend Out of Memory Issues in Hogwarts Adventures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-connections-how-to-clear-dns-in-steam-settings/"><u>Streamline Connections: How to Clear DNS in Steam Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-unusual-wsl-error-4294967295-on-pcs/"><u>Tackling Unusual WSL Error 4294967295 on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-from-s-mode-essential-tips-for-windows-1011/"><u>Transitioning From S Mode: Essential Tips for Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-11s-operation-elevation-issue-740/"><u>Troubleshooting Windows 11'S Operation Elevation Issue #740</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-11-screen-recording-techniques-combining-audio-and-visual-features-in-snipping-tool-max-156/"><u>Unveiling Windows 11 Screen Recording Techniques: Combining Audio & Visual Features in Snipping Tool (Max 156)</u></a></li>
<li><a href="https://change-location.techidaily.com/where-is-the-best-place-to-catch-dratini-on-vivo-y77t-drfone-by-drfone-virtual-android/"><u>Where Is the Best Place to Catch Dratini On Vivo Y77t | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-simplification-recapturing-default-rights/"><u>Windows 11 Simplification: Recapturing Default Rights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-the-promise-of-next-generation-in-the-upcoming-moment/"><u>Windows 11: The Promise of Next Generation in the Upcoming Moment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-insight-determining-your-intel-cpus-generation/"><u>Windows Insight: Determining Your Intel CPU's Generation</u></a></li>
</ul></div>
