---
title: Workaround for Non-Compatible Programs on Windows XP/Vista/7
date: 2024-09-01T05:18:02.765Z
updated: 2024-09-02T05:18:02.765Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Workaround for Non-Compatible Programs on Windows XP/Vista/7
excerpt: This Article Describes Workaround for Non-Compatible Programs on Windows XP/Vista/7
keywords: WinXP Vista Compatibility Fix,XP/Vista Software Solutions,Vista/Windows Compatability Tools,Programs for Old Windows OS,Windows XP/7 Third-Party Fixes,Cross-Version Software Support,Windows XP/Vista Upgrades
thumbnail: https://thmb.techidaily.com/48491c0a3b929750d09e0d3e1dede43e654117023e73246a1998baa96a66f8fd.jpg
---

## Workaround for Non-Compatible Programs on Windows XP/Vista/7

 The Program Compatibility Troubleshooter is a tool from Microsoft that checks for and resolves compatibility issues when running older applications on newer versions of Windows. However, sometimes the troubleshooter fails to work as expected.

 If you're facing this issue, there are several possible causes and ways to fix it. Let's look into them below.

## 1\. Check For Corrupted System Files

 Corrupted system files can cause the Program Compatibility Troubleshooter not to work correctly. To ensure all your system files are functioning properly, run the built-in System File Checker utility on Windows. Here's how to do it:

1. Right-click on**Start** and select**Run** from the menu list.
2. Type**cmd** in the text box and press**Ctrl + Shift + Enter** on your keyboard.
3. If UAC appears on the screen, click**Yes** to grant privileges.  
![Run SFC Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-sfc-command.jpg)
4. In Command Prompt type the below command and hit Enter:  
`sfc /scannow`

 Wait for the scan to finish. This may take several minutes and your PC may restart once or twice during the process. Once the scan is completed, check if the Program Compatibility Troubleshooter works now.

## 2\. Repair Corrupted System Image

 If the System File Checker was unable to repair corrupt system files, you can use the DISM tool from Command Prompt to fix them. Here's how to do it:

1. Use one of the many[ways to run Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) to get an elevated prompt running.  
![Run DISM Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-dism-command.jpg)
2. In Command Prompt, type the below command and hit**Enter** :  
`DISM /Online /Cleanup-Image /RestoreHealth`

 The DISM tool will start scanning the system for corruption. It can take up to 20 minutes, but it is worth waiting because it can repair a lot of system issues. Once the scan is completed, restart your computer and check if the issue is fixed.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Uninstall Third-Party Security Software

 Sometimes, certain third-party security software can interfere with the Program Compatibility Troubleshooter and cause it to not work. Uninstalling these programs should help.

1. Right-click on Start and select**Installed apps** .
2. Search for your security software in the list of installed programs.
3. Then click the three dots and select**Uninstall** .

 Follow the on-screen instructions to remove the program from your PC. Once done, restart your PC and try running the Program Compatibility Troubleshooter again.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Restart the Diagnostic Policy Service

 The Diagnostic Policy Service is responsible for allowing the Program Compatibility Troubleshooter to work properly. If it's not running, restarting it should help the troubleshooter function normally.

1. Press**Win + R** on your keyboard to open the Run dialog box.
2. Type**services.msc** in the text box and click**OK** .
3. Look for the**Diagnostic Policy Service** and double-click it.  
![Restart Diagnostic Policy Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-diagnostic-policy-service.jpg)
4. In the Diagnostic Policy Service Properties window, set the Startup type to**Automatic** and click**Start** .
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
5. Next, click**Apply** and**OK** to save the changes.

 Now restart your PC and try running the Program Compatibility Troubleshooter again to see if it works.

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Run the Troubleshooter in Safe Mode

 If you are still experiencing this issue, try running the Program Compatibility Troubleshooter in safe mode. This will help you troubleshoot any compatibility issues more effectively.

To do this, follow the below steps:

1. Start your PC in safe mode (see[how to start Windows in safe mode](https://www.makeuseof.com/windows-11-boot-safe-mode/) for instructions).
2. Once in safe mode,[run the Program Compatibility Troubleshooter](https://www.makeuseof.com/run-program-compatibility-troubleshooter-windows/) and check if it works. If so, it means that one of your installed programs is causing the issue. Try uninstalling them and see if the issue is fixed.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 6\. Reset Windows

 If all else fails, you can try[resetting Windows to its default settings](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) . This will reinstall Windows and get rid of any potential issues that may be causing the troubleshooter to not work.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
## Fixing Program Compatibility Troubleshooter Problems on Windows

 If the Program Compatibility Troubleshooter is not working on your computer, read this guide. The steps here will help you fix this issue and have the tool working and running again.


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
<li><a href="https://extra-hints.techidaily.com/new-audible-annotations-choosing-the-top-speech-to-text-apps/"><u>[New] Audible Annotations  Choosing the Top Speech-to-Text Apps</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-how-to-safely-capture-your-favorite-youtube-audio-for-free-for-2024/"><u>[New] How to Safely Capture Your Favorite YouTube Audio for Free for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-insights-into-instagram-follower-exits/"><u>[New] In 2024, Insights Into Instagram Follower Exits</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-seamless-access-watching-fb-videos-on-apple-tv-explained/"><u>[New] In 2024, Seamless Access  Watching FB Videos on Apple TV Explained</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/nline-havens-for-sponsorship-initiatives-on-youtube-for-2024/"><u>[New] Online Havens for Sponsorship Initiatives on YouTube for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-echoes-in-the-room-mac-sound-studio/"><u>[Updated] In 2024, Echoes in the Room  Mac Sound Studio</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-comprehensive-app-exploration-az-capture-essentials/"><u>2024 Approved  Comprehensive App Exploration  AZ Capture Essentials</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/8-best-apps-for-screen-mirroring-samsung-galaxy-s23-ultra-pc-drfone-by-drfone-android/"><u>8 Best Apps for Screen Mirroring Samsung Galaxy S23 Ultra PC | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convenient-options-boot-into-safe-mode-with-6-steps-in-windows-11/"><u>Convenient Options: Boot Into Safe Mode with 6 Steps in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-11s-intricate-data-collection/"><u>Decoding Windows 11'S Intricate Data Collection</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/dissecting-revenue-allocation-for-shortform-content-makers/"><u>Dissecting Revenue Allocation for Shortform Content Makers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-into-techniques-preventing-apex-crashes-on-windows-11/"><u>Dive Into Techniques: Preventing Apex Crashes on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-fixes-to-overcome-common-windows-app-errors/"><u>Efficient Fixes to Overcome Common Windows App Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-multitask-management-cascade-windows-with-alt-tab/"><u>Efficient Multitask Management: Cascade Windows with Alt-Tab</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/eliminating-sounds-issues-comprehensive-solutions-for-the-realtek-alc887-hd-audio-driver-in-windows/"><u>Eliminating Sounds Issues: Comprehensive Solutions for the Realtek ALC887 HD Audio Driver in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-window-monitors-brilliance-with-top-software-for-6-users/"><u>Enhancing Window Monitors' Brilliance with Top Software for 6 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-pc-setup-sticking-gmail-on-the-windows-taskbar/"><u>Essential PC Setup: Sticking Gmail on the Windows Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-system-tools-sfc-chkdsk-and-dissect-wintools-decoded/"><u>Exploring System Tools: SFC, CHKDSK, and Dissect - WinTools Decoded</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-silent-speech-problems-for-gamers-playing-on-pc/"><u>Fixing Silent Speech Problems for Gamers Playing on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-unheard-sound-from-devices-on-microsoft-windows/"><u>Fixing Unheard Sound From Devices on Microsoft Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-adjust-admin-managed-chromium-and-microsoft-edge-in-windows/"><u>Guidelines to Adjust Admin-Managed Chromium & Microsoft Edge in Windows</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-do-vivo-y02t-screen-sharing-drfone-by-drfone-android/"><u>How To Do Vivo Y02T Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-geforce-now-error-xc0f1103f-in-11/"><u>How to Rectify GeForce Now Error Xc0f1103f in 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-tackle-device-latency-zerodxgierror-in-win11-pcs/"><u>How to Tackle Device Latency ZeroDXGIError in Win11 PCs</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-expedite-content-indexing-with-these-7-free-youtube-tag-extractors/"><u>In 2024, Expedite Content Indexing with These 7 FREE YouTube Tag Extractors</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/innovative-approaches-to-capturing-skype-calls-on-obs/"><u>Innovative Approaches to Capturing Skype Calls on OBS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-with-finesse-your-windows-11-laptops-touch-settings/"><u>Navigate with Finesse: Your Windows 11 Laptop's Touch Settings</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/novice-necessities-your-first-steps-in-gopro-world/"><u>Novice Necessities - Your First Steps in GoPro World</u></a></li>
<li><a href="https://win11-tips.techidaily.com/novices-companion-to-windows-accessibility-features/"><u>Novice's Companion to Windows Accessibility Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-high-definition-screen-scale-glitches/"><u>Overcoming High-Definition Screen Scale Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reign-in-windows-stop-unwanted-screen-movement/"><u>Reign In Windows: Stop Unwanted Screen Movement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-old-cursor-color-schemes-tips/"><u>Reviving Old Cursor Color Schemes: Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-lower-ntoskrnlexe-usage/"><u>Strategies to Lower Ntoskrnl.exe Usage</u></a></li>
<li><a href="https://howto.techidaily.com/stuck-at-android-system-recovery-of-oneplus-nord-ce-3-lite-5g-fix-it-easily-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Stuck at Android System Recovery Of OnePlus Nord CE 3 Lite 5G ? Fix It Easily | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-6-best-video-converters-for-windows/"><u>The 6 Best Video Converters for Windows</u></a></li>
<li><a href="https://android-frp.techidaily.com/the-complete-guide-to-samsung-galaxy-a54-5g-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>The Complete Guide to Samsung Galaxy A54 5G FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-enhance-slow-execution-of-excel-workbooks-on-windows/"><u>Tips to Enhance Slow Execution of Excel Workbooks on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-app-setup-utilizing-winstall-in-the-windows-11-landscape/"><u>Transforming App Setup: Utilizing Winstall in the Windows 11 Landscape</u></a></li>
</ul></div>
