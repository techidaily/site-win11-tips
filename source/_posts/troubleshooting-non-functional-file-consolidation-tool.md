---
title: Troubleshooting Non-Functional File Consolidation Tool
date: 2024-09-01T05:16:04.368Z
updated: 2024-09-02T05:16:04.368Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Non-Functional File Consolidation Tool
excerpt: This Article Describes Troubleshooting Non-Functional File Consolidation Tool
keywords: Fix Consolidate Files Error,Unblock File Merge Issue,Resolve File Aggregator Failure,Stop Duplicate File Problems,Correct File Combination Mishaps,End File Sync Glitches,Clear Concat File Issues
thumbnail: https://thmb.techidaily.com/934c09a684ad314c00e00ed21a2e7539ae4858551b2266da80c837988bee503d.jpg
---

## Troubleshooting Non-Functional File Consolidation Tool

 The Disk Defragmenter tool is a Windows user's best friend. This tool fixes fragmentation issues so that your hard drive runs smoother, but it itself sometimes comes across problems of its own. If you're having trouble with your disk defragmenter, there are a few things you can do to resolve the problem.

 In this article, you will learn how to fix the Disk Defragmenter so it works properly again.

## What Is the Disk Defragmenter? Why Does It Stop Working?

 The Disk Defragmenter tool rearranges files on your hard drive so that they are stored in a contiguous manner. This helps to improve file access speed and overall system performance. Disk fragmentation can occur over time as you add, remove, and modify files on your hard drive.

 Although a disk defragmenter is an important tool for keeping your computer running smoothly, sometimes it does not work as it should. Here are a few things that can cause the disk defragmenter to stop working:

1. The tool won't work if you have a solid-state drive (SSD). SSDs don't need to be defragmented because they don't have the same type of moving parts that traditional hard drives do.
2. Another possibility is that you have a virus or malware on your computer that's interfering with the disk defragmenter. You can try running a virus scan to see if that fixes the problem.
3. Corrupt system files can also cause the service to malfunction. In such a case, it may be worthwhile running an SFC (System File Checker) scan as a way to diagnose the problem.

 Now we know what causes the Disk Defragmenter to stop working, it's time to look at some solutions that may help you fix the problem.

## 1\. Check Disk Defragmenter's Status

 If your computer is running slowly, one potential reason could be that the Disk Defragmenter service is not running properly. This service helps to optimize your hard drive by rearranging files so that they can be read more quickly and efficiently.

 To check if the Disk Defragmenter service is running properly, follow the steps:

1. Open the Services app (see[ways to open the Services app on Windows](https://www.makeuseof.com/windows-11-open-services-app/) ).
2. Scroll down to the "Optimise drives" service and double-click on it.
3. Click on the drop-down menu and set the Start type to "Manual."
4. Make sure the Service status is "Running." If it is not, then click on**Start** to run it.  
![Set Optimise drives Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Set-Optimise-drives-Properties.jpg)
5. Click**Apply > OK** to save it.

 After making the above changes, check if it solves the problem. If not, move on to the next solution.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Run the System File Checker tool

 Another way to fix your disk defragmenter is to run the System File Checker tool. This tool will scan all of your system files and replace any that are corrupt or missing.

To run the System File Checker, follow these steps:

1. Press**Win + X** on your keyboard to open the Power User menu.
2. Select the**Run** option from the menu list.
3. In the Run command dialog box, type "cmd" and press**Ctrl + Shift + Enter** at the same time.
4. When UAC appears on the screen, select**Yes** to approve administrator access.
5. Once you're in the Command Prompt window, type "sfc /scannow", and press**Enter** .

 It may take a while for the scan to complete, so be patient. Once the scan is complete, restart your computer and try running Disk Defragmenter again. It should now work properly.

![SFC and DISM Scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/SFC-and-DISM-Scan.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
 If you're still having trouble with your Disk Defragmenter tool after running an SFC scan, you may need to use the DISM utility. To do this, open the Command Prompt as an administrator and run the below command line:

`DISM /Online /Cleanup-Image /ScanHealth\nDism.exe /online /cleanup-image /restorehealth`

 Once the scan is complete, restart your computer and try defragmenting again.

## 3\. Run the CHKDSK Utility

 If your computer's Disk Defragmenter is still not working, you can try[running the CHKDSK utility](http://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) . This is a computer program designed to check the integrity of your hard drive, identify errors, and fix them.

To run the CHKDSK utility, follow the below steps:

1. Press the Windows key and search for "Command Prompt".
2. Right-click on the search result and select**Run as administrator** .
3. Click**Yes** if UAC prompts on your computer screen. This will open a Command Prompt with admin access.  
![Run chkdsk command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Run-chkdsk-command.jpg)
4. When you're in Command Prompt, type the following command and press Enter:  
<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
`chkdsk C: /f`

 In the command above,**"C:"** represents your drive, so you should replace it with the letter that refers to your drive.

 Once the scanning process is completed, and you have been informed that your drive has been scanned, try to defragment it again.

 As it turns out, it may take several minutes for the scan to complete, depending on the size of your partition and sometimes it seems to get stuck. However, you should let it complete its task uninterrupted.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Close All Third-Party Applications

 Some third-party applications may interfere with Disk Defragmenter if they are running. In such a case, close all third-party programs and see if that helps the defragmenter to run properly.

 If you close all active windows and find that the defragmenter is still having issues, there might be a background process interfering with it. As such, you can try ending some third-party processes and see if that fixes it.

1. Press**Ctrl + Shift + Esc** on your keyboard to open the Task Manager.
2. On the Processes tab, find a non-essential third-party service and right-click on it.
3. Then select**End task** from the context menu.  
![Close Programs Via Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Close-Programs-Via-Task-Manager.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 After closing one, check if the disk defragmenter works again. If it does, the service you just closed is the culprit. Now you can either update, re-install, or even uninstall the problematic app so it stops interfering with Disk Defragmenter.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fixing Windows Disk Defragmenter's Opening Issues

 Disk defragmentation can improve the situation by rearranging files so that they can be evenly distributed throughout the drive. However, sometimes the Disk Defragmenter tool doesn't work as expected. If you encounter this problem, the methods described above should help you resolve it.


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
<li><a href="https://facebook-clips.techidaily.com/new-browsing-bygone-tales-in-the-facebook-universe-with-devices-for-2024/"><u>[New] Browsing Bygone Tales in the Facebook Universe with Devices for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-top-10-mobile-relaxation-renders-idle-games/"><u>[Updated] In 2024, Top 10 Mobile Relaxation Renders (Idle Games)</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-masterful-webcam-hacks-for-creative-sessions/"><u>[Updated] Masterful Webcam Hacks for Creative Sessions</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-sharpen-your-scopes-a-comprehensive-guide-to-close-up-roblox/"><u>2024 Approved  Sharpen Your Scopes  A Comprehensive Guide to Close-Up Roblox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detect-signs-is-it-time-for-windows-clean-slate/"><u>Detect Signs: Is It Time for Windows Clean Slate?</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/discover-why-the-lg-oled-c9-is-top-choice-for-picture-quality-lovers-a-comprehvew-in-our-latest-tv-showdown/"><u>Discover Why the LG OLED C9 Is Top Choice for Picture Quality Lovers - A Comprehvew in Our Latest TV Showdown!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-diagnosing-and-fixing-cc-issues-on-windows-10/"><u>Efficiently Diagnosing and Fixing CC Issues on Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-leading-zeros-display-in-microsoft-excel-a-comprehensive-guide/"><u>Ensuring Leading Zeros Display in Microsoft Excel: A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-scribbling-in-windows-11-effortlessly/"><u>Get Scribbling in Windows 11 Effortlessly</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fake-gps-on-asus-rog-phone-7-for-mobile-legends-drfone-by-drfone-virtual-android/"><u>How To Fake GPS On Asus ROG Phone 7 For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-manage-your-laptops-energy-efficient-features/"><u>How to Manage Your Laptop's Energy Efficient Features</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-record-and-save-every-sound-on-pc-exclusive-x-recorder/"><u>In 2024, Record & Save Every Sound on PC - Exclusive X-Recorder</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-excel-spreadsheets-into-your-slides-a-step-by-step-guide/"><u>Integrating Excel Spreadsheets Into Your Slides: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-excel-reporting-build-professional-dashboards-for-insightful-analytics/"><u>Master Excel Reporting: Build Professional Dashboards for Insightful Analytics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-microsoft-store-repairs-fixing-code-0x80072f30-quickly/"><u>Master Microsoft Store Repairs: Fixing Code 0X80072F30 Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-excel-a-step-by-step-guide-to-using-index-and-match/"><u>Mastering Excel: A Step-by-Step Guide to Using INDEX and MATCH</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-ms-excel-a-comprehensive-tutorial-on-square-root-calculation-techniques/"><u>Mastering MS Excel: A Comprehensive Tutorial on Square Root Calculation Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-disabling-windows-updates/"><u>Mastering the Art of Disabling Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-command-prompt-a-guide-to-user-management/"><u>Navigating Command Prompt: A Guide to User Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-startup-hurdles-for-photoshop-on-windows-1011/"><u>Overcoming Startup Hurdles for Photoshop on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proactive-approach-locating-your-devices-mac-address-in-windows-11/"><u>Proactive Approach: Locating Your Device's MAC Address in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redesigning-workplace-efficiency-with-microsofts-latest-office-template-overhaul/"><u>Redesigning Workplace Efficiency with Microsoft's Latest Office Template Overhaul</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-your-pcs-bluetooth-link-with-these-9-essential-tips-for-win-11/"><u>Restore Your PC's Bluetooth Link with These 9 Essential Tips for Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/selecting-the-ideal-excel-chart-type-a-guide-for-presenting-your-data-effectively/"><u>Selecting the Ideal Excel Chart Type: A Guide for Presenting Your Data Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-switching-between-foreign-languages-on-windows-devices/"><u>Speedy Switching Between Foreign Languages on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-adjusting-gaps-between-cells-text-and-borders-in-excel-spreadsheets/"><u>Step-by-Step Guide: Adjusting Gaps Between Cells, Text, and Borders in Excel Spreadsheets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-creating-a-pie-chart-using-microsoft-excel/"><u>Step-by-Step Guide: Creating a Pie Chart Using Microsoft Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-implementing-strikethrough-text-feature-in-microsoft-excel/"><u>Step-by-Step Guide: Implementing Strikethrough Text Feature in Microsoft Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-tackle-audacitys-sound-fault-windows-11-os/"><u>Strategies to Tackle Audacity's Sound Fault, Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-installation-craft-a-focused-fast-bootable-win-11-drive/"><u>Streamline Your Installation: Craft a Focused, Fast Bootable Win 11 Drive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-file-management-overcoming-o365-errors-on-win-11/"><u>Streamlined File Management: Overcoming O365 Errors on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-the-process-of-adjusting-pointer-settings-in-windows-11/"><u>Streamlining the Process of Adjusting Pointer Settings in Windows 11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-ultimate-list-reddits-most-adored-and-upvoted-stories-for-2024/"><u>The Ultimate List  Reddit's Most Adored and Upvoted Stories for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-reverting-windows-folders-to-full-editability/"><u>Tips for Reverting Windows Folders to Full Editability</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-11-amazing-tricks-and-tasks-achievable-using-siri-on-your-mac/"><u>Top 11 Amazing Tricks and Tasks Achievable Using Siri on Your Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-9-essential-excel-text-manipulation-techniques-using-microsoft-office/"><u>Top 9 Essential Excel Text Manipulation Techniques Using Microsoft Office</u></a></li>
<li><a href="https://solve-news.techidaily.com/transform-your-iphone-photos-into-editable-documents-using-ocr-discover-the-power-of-finereader-for-pdf-conversion/"><u>Transform Your iPhone Photos Into Editable Documents Using OCR - Discover the Power of FineReader for PDF Conversion!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unifying-ms-office-suite-with-your-zoho-online-platform-a-step-by-step-guide/"><u>Unifying MS Office Suite with Your Zoho Online Platform: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-efficiency-with-google-sheets-top-14-capabilities-missed-in-microsoft-excel/"><u>Unlocking Efficiency with Google Sheets: Top 14 Capabilities Missed in Microsoft Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-secrets-of-successful-gmaps-integration-in-windows/"><u>Unveiling the Secrets of Successful GMaps Integration in Windows</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-2024-approved-fcp-x-visual-effects-how-to-create-seamless-green-screen-composites/"><u>Updated 2024 Approved FCP X Visual Effects How to Create Seamless Green Screen Composites</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-context-menu-incorporating-copy-and-move-commands-into-folder-options-win-11/"><u>Upgrade Context Menu: Incorporating Copy & Move Commands Into Folder Options (Win 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/work-on-excel-powerpoint-and-word-online-doc-editing-anywhere/"><u>Work on Excel, PowerPoint & Word Online Doc Editing Anywhere</u></a></li>
</ul></div>
