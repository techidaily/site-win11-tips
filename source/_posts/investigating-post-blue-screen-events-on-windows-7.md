---
title: Investigating Post-Blue Screen Events on Windows 7
date: 2024-08-16T02:31:47.462Z
updated: 2024-08-17T02:31:47.462Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Investigating Post-Blue Screen Events on Windows 7
excerpt: This Article Describes Investigating Post-Blue Screen Events on Windows 7
keywords: Blue Screen Analysis,Win7 BSOD Diagnosis,System Crash Investigation,Windows Error Debugging,OS Recovery Strategies,Boot Failure Fixing,Memory Issue Identification
thumbnail: https://thmb.techidaily.com/c07b7ea823a20fff0d48f1accc60826d6016566f3469f152eba0254ae0b7e1bc.jpg
---

## Investigating Post-Blue Screen Events on Windows 7

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
![Choose Event Viewer in the context menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/event-viewer.jpg)
<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. Head over to the **Action** menu located at the top, and choose **Create Custom View** from the context menu.  
![Create a custom view in the Event viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/create-custom-view.jpg)
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
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Once the view is created, you will be presented with a list of errors that occurred during the time frame you selected earlier. You can sort this information further in the Date and time section.  
![Check the Event Viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/event-viewer-11.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
4. Next, locate the BSOD using details like the date and time again.
5. Once you find the targeted log, click on it.
6. Check both the General and Details tabs to get information about this error.

 Once you find the error code associated with the crash and the cause, you can look for solutions online, or head over to our guide that discusses [how to fix blue screen errors in Windows](https://www.makeuseof.com/tag/4-tips-fix-blue-screen-error/) if it's a bsod.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
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
<!-- affiliate ads begin -->
<span id="1793213">
					<video width="1080" height="1620" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:1080px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Name this value as **DisplayParameters** and double-click on it.
8. Under Value data, type 1 and click **OK**.  
![Change the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/value-data-1.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
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
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-docs.techidaily.com/024-approved-how-much-wealth-can-you-generate-on-youtube-using-cpm/"><u>[New] 2024 Approved  How Much Wealth Can You Generate on YouTube Using CPM?</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-navigating-the-spotlight-how-to-optimize-content-visibility-on-youtube/"><u>[New] 2024 Approved  Navigating the Spotlight  How to Optimize Content Visibility on Youtube</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-audiovisual-synergy-infusing-music-into-vimeo-creations/"><u>[New] Audiovisual Synergy  Infusing Music Into Vimeo Creations</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-enhancing-outreach-with-strategic-partner-selection-on-youtube/"><u>[New] Enhancing Outreach with Strategic Partner Selection on YouTube</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-iphone-night-pics-101-enhancing-dark-images/"><u>[Updated] 2024 Approved  IPhone Night Pics 101  Enhancing Dark Images</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-locate-the-best-bargains-on-gopro-cameras/"><u>2024 Approved  Locate the Best Bargains on GoPro Cameras</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-music-infused-videos-perfecting-sound-with-inshot/"><u>2024 Approved  Music-Infused Videos  Perfecting Sound with InShot</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-unpacking-manycams-revolutionary-recording-features/"><u>2024 Approved  Unpacking ManyCam's Revolutionary Recording Features</u></a></li>
<li><a href="https://extra-information.techidaily.com/25-top-rated-gratis-online-photography-tools-for-2024/"><u>25 Top-Rated, Gratis Online Photography Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-window-light-in-windows-11-top-solutions-explored/"><u>Boosting Window Light in Windows 11: Top Solutions Explored</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-windows-gpu-performance-the-best-six-tools-guide/"><u>Boosting Windows GPU Performance: The Best Six Tools Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaching-windows-11-theme-shields-with-registry-insights/"><u>Breaching Windows 11 Theme Shields with Registry Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-and-solving-windows-steams-error-e84/"><u>Breaking Down and Solving Windows Steam's Error E84</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-windows-headset-mic-not-working/"><u>Breaking Down Window's Headset Mic Not Working</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-free-from-defenders-history-windows-strategies-unveiled/"><u>Breaking Free From Defender's History: Windows Strategies Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-silence-windows-11s-veiled-bar-investigator/"><u>Breaking Silence: Windows 11’S Veiled Bar Investigator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-through-windows-11-tpm-release-methods/"><u>Breaking Through Windows 11: TPM Release Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathing-life-into-frozen-windows-hibernate/"><u>Breathing Life Into Frozen Windows Hibernate</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridge-apple-and-microsoft-ecosystems-windows-11-via-parallels/"><u>Bridge Apple and Microsoft Ecosystems: Windows 11 via Parallels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-systems-android-to-windows-shared-files/"><u>Bridging Systems: Android to Windows Shared Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-your-gadgets-win11s-stickies-explained/"><u>Bridging Your Gadgets: WIN11'S Stickies, Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-the-forgotten-how-to-locate-the-hidden-enhancement-in-windows-11/"><u>Bring Back the Forgotten: How to Locate the Hidden Enhancement in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/bring-back-the-life-solutions-for-non-responsive-bluetooth-mice-windows/"><u>Bring Back the Life: Solutions for Non-Responsive Bluetooth Mice (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-windows-update-service-quickly/"><u>Bring Back Windows Update Service Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-forth-the-forgotten-off-screen-window-revival-steps-for-win1011/"><u>Bringing Forth the Forgotten: Off-Screen Window Revival Steps for Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-pin-for-smooth-projections-on-windows-11/"><u>Bypass PIN for Smooth Projections on WIndows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-restrictions-to-gain-admin-control/"><u>Bypass Restrictions to Gain Admin Control</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-clogged-right-click-menus-in-windows-os/"><u>Bypassing Clogged Right-Click Menus in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-clutter-unwanted-application-removal-on-windows-11/"><u>Bypassing Clutter: Unwanted Application Removal on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-decades-old-keyboard-entry-error/"><u>Bypassing Decades-Old Keyboard Entry Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-hurdles-a-guide-to-overcoming-roblox-error-262/"><u>Bypassing Hurdles: A Guide to Overcoming Roblox Error 262</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-ssi-on-windows-easy-installation-of-unchecked-drivers/"><u>Bypassing SSI on Windows: Easy Installation of Unchecked Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-w11s-onedrive-def5-hurdle-with-easy-fixes/"><u>Bypassing W11's Onedrive Def5 Hurdle with Easy Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/c-vs-d-key-differences-in-windows-disk-drives/"><u>C vs D: Key Differences in Windows Disk Drives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/capturing-your-desktop-prtsc-vs-snipping-tool-in-windows-10/"><u>Capturing Your Desktop: PrtSc Vs. Snipping Tool in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/checking-for-updates-on-spotify-software-and-system/"><u>Checking for Updates on Spotify Software & System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/child-protection-mastering-windows-11-safety-settings/"><u>Child Protection: Mastering Windows 11 Safety Settings</u></a></li>
<li><a href="https://tech-haven.techidaily.com/elevate-your-home-cooking-game-7-innovative-uses-for-chatgpt-in-the-kitchen/"><u>Elevate Your Home Cooking Game - 7 Innovative Uses for ChatGPT in the Kitchen</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-detect-and-remove-spyware-on-nokia-c12-pro-drfone-by-drfone-virtual-android/"><u>How to Detect and Remove Spyware on Nokia C12 Pro? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-your-computer-when-it-gets-stuck-during-windows-setup/"><u>How to Fix Your Computer When It Gets Stuck During Windows Setup</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-for-people-wanting-to-mock-gps-on-realme-c67-5g-devices-drfone-by-drfone-virtual/"><u>In 2024, For People Wanting to Mock GPS on Realme C67 5G Devices | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-reset-your-infinix-hot-40-lock-screen-password-by-drfone-android/"><u>In 2024, How to Reset your Infinix Hot 40 Lock Screen Password</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-realme-gt-neo-5-phone-without-any-data-loss-by-drfone-android/"><u>In 2024, How to Unlock Realme GT Neo 5 Phone without Any Data Loss</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-ken-burns-effect-techniques-for-camtasia-users/"><u>In 2024, Ken Burns Effect Techniques for Camtasia Users</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-savvy-screenshot-tactics-for-netflix-on-mac-a-complete-guide-of-six-ways/"><u>In 2024, Savvy Screenshot Tactics for Netflix on Mac - A Complete Guide of Six Ways</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-hidden-world-exploring-vlc-player-extras/"><u>In 2024, The Hidden World  Exploring VLC Player Extras</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/in-depth-analysis-and-user-experience-tips-for-google-maps-on-iphone/"><u>In-Depth Analysis and User Experience Tips for Google Maps on iPhone</u></a></li>
<li><a href="https://some-skills.techidaily.com/tackling-latency-issues-for-smooth-video-conferencing-on-xbox-one-for-2024/"><u>Tackling Latency Issues for Smooth Video Conferencing on Xbox One for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-next-wave-of-social-media-top-apps-as-periscope-alternates/"><u>The Next Wave of Social Media  Top Apps as Periscope Alternates</u></a></li>
</ul></div>
