---
title: Simple Strategies to Reboot Distribution & Catroot in Windows 11
date: 2024-09-01T05:15:01.904Z
updated: 2024-09-02T05:15:01.904Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Simple Strategies to Reboot Distribution & Catroot in Windows 11
excerpt: This Article Describes Simple Strategies to Reboot Distribution & Catroot in Windows 11
keywords: Win11 Distrib Relaunch,Catroot Fix Windows 11,Rebooting Windows 11 OS,Strategies for Win11 Update,Catroot Optimization Wins11,Distribution Reboot in Win11,Simple Win11 System Fixes
thumbnail: https://thmb.techidaily.com/4d3965d206c3e8f9b4a9da6d71e7e79363ab237dd992d3524ab2a99d8d4908ed.jpg
---

## Simple Strategies to Reboot Distribution & Catroot in Windows 11

 Users widely report Windows 11 update errors on support forums. Updates fail to install because of such errors. You can often fix update errors by resetting the catroot 2 and Windows SoftwareDistribution folders as covered below.

## What Are the SoftwareDistribution and Catroot2 Folders?

 The SoftwareDistribution folder is a directory that stores files required for installing Windows updates on PCs. It is a temporary repository of the update files. Thus, the SoftwareDistribution folder is an important component for updating Windows.

 Catroot 2 is a folder that stores the signature data for Windows 11 updates. Those are the files the Cryptographic service needs for update verification.

 Both folders contain files needed for the installation of Windows updates. Windows update installation issues can occur because of corrupted data in those folders. Those errors typically appear in Settings with variable codes like 0x800f0922 when users manually select to check for and install updates.

 Therefore, resetting those folders is a troubleshooting method for fixing Windows 11 update installation issues. Resetting the SoftwareDistribution and Catroot2 folders removes corrupted data they might contain, which rebuilds them. You can reset those folders by deleting their contents or renaming them.

## How to Reset the SoftwareDistribution and Catroot2 Folders by Erasing Their Contents

 This method for resetting the SoftwareDistribution and Catroot2 folders involves manually eradicating the data in them via File Explorer. It’s also necessary to disable and re-enable certain services via the Command Prompt to ensure they’re not utilizing files in them. Delete the files in the SoftwareDistribution and Catroot2 folders as follows:

1. Open the file finder utility accessible with a **Windows** logo + **S** hotkey.
2. Locate the Command Prompt by entering the keyword **cmd** into the search text box.
3. Select to [open the Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) by clicking its **Run as administrator** option on the right of the search tool.
4. Input and execute the following separate commands to disable services required for updating Windows 11:  
`net stop bits  

net stop wuauserv  

net stop cryptsvc  

net stop msiserver`
5. Press the **Windows key + E** on your keyboard to go to File Explorer.
6. Open the SoftwareDistribution folder at this path:  
`C:\Windows\SoftwareDistribution`
7. Press **Ctrl** \+ **A** to select all the files in the SoftwareDistribution folder.
8. Right-click and select **Delete** (the trash can button) to eradicate selected content.  
![The SoftwareDistribution folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/softwaredistribution-folder.jpg)
9. Bring up the catroot2 folder by entering this path in Explorer’s address bar:  
`C:\Windows\System32\catroot2`
10. Repeat steps seven and eight above to erase everything in that folder.  
![The catroot2 folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/catroot2folder.jpg)
11. Return to the Command Prompt and execute these separate commands for restarting the disabled services.  
`net start bits  

net start wuauserv  

net start cryptSvc  

net start msiserver`
12. Restart the PC and check for updates after clearing those folders.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Reset the SoftwareDistribution and Catroot2 Folders by Renaming Them

 Renaming the SoftwareDistribution and Catroot2 directories is an alternative method for resetting those folders. Windows will recreate those folders after you’ve renamed them. You can rename the SoftwareDistribution and catroot2 folders with the Command Prompt like this:

1. Run the Command Prompt with elevated admin rights.
2. Repeat step four of the preceding method to execute the commands for disabling services.  
![The net stop commands](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/net-stop-commands.jpg)
3. Input this command to rename the SoftwareDistribution folder and press **Return**:  
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
`ren %systemroot%\softwaredistribution softwaredistribution.bak`  
![The rename SoftwareDistribution folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/ren-softwaredistribution-command.jpg)
4. Enter and execute this rename command for the catroot2 folder:  
<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
`ren %systemroot%\system32\catroot2 catroot2.bak`  
![The ren catroot2 command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/ren-catroot2-folder.jpg)
5. Repeat step 11 of the preceding method by executing the four commands for restarting the disabled services.  
![The net start command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/net-start-commands.jpg)
6. Exit Command Prompt and select to restart your PC.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->

## How to Reset the SoftwareDistribution and Catroot2 Folders With FixWin 11

 FixWin 11 is one of the [best freely available Windows repair tools](https://www.makeuseof.com/tag/5-free-tools-fix-problem-windows-10/) that includes troubleshooting options. Among them are two options for resetting the catroot2 and SoftwareDistribution folders. This is how you can select those quick fix options in FixWin 11:

1. Open this [FixWin 11 page](https://www.softpedia.com/get/Tweak/System-Tweak/FixWin-11.shtml) on the Softpedia website.
2. Click on the **Free Download** button for FixWin.
3. Select **Secure Download (US)** to obtain FixWin’s ZIP archive.
4. Activate a File Explorer window and go to your browser’s downloads folder.
5. Extract the FixWin archive by going through the steps in this article about [unzipping ZIP files on Windows](https://www.makeuseof.com/how-to-extract-zip-files-windows-11/).  
![The Extract Compressed ZIP archive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/extract-compressed-window.jpg)
6. Double-click the **FixWin 11.1.exe** file in the extracted folder for FixWin.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
7. Click **Additional Fixes** on the left of the FixWin window.
8. Select the **Quick Fixes** tab.
9. Press the **Reset Software Distribution folder** button.  
![The Quick Fixes tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/quick-fixes-tab.jpg)
10. Click the **Reset catroo2 Folder** option.
11. Exit FixWin and reboot your PC after selecting those options.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fix Windows Update Issues by Resetting the SoftwareDistribution and Catroot2 Folders

 It’s important to resolve update issues when they arise for the sake of keeping Windows updated. Resetting the catroo2 and SoftwareDistribution folders is one of the most effective troubleshooting methods for fixing Windows update errors.

 So, try doing that whenever you need to fix an error code shown within the Windows Update tab of Settings.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-beyond-basiccams-prospects-of-elevated-performance/"><u>[New] 2024 Approved  Beyond BasicCams  Prospects of Elevated Performance</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-pioneering-techniques-in-screen-snatching/"><u>[New] 2024 Approved  Pioneering Techniques in Screen Snatching</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-redefine-viewing-premium-platforms-for-videos/"><u>[New] 2024 Approved  Redefine Viewing  Premium Platforms for Videos</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-the-essential-blueprint-for-scheduling-success-with-slack-plus-filmora/"><u>[Updated] 2024 Approved  The Essential Blueprint for Scheduling Success with Slack + Filmora</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-essential-game-editor-tools-for-novices/"><u>[Updated] Essential Game Editor Tools for Novices</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-error-code-963-on-google-play-of-motorola-razr-40-ultra-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Error Code 963 on Google Play Of Motorola Razr 40 Ultra | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-default-file-formats-in-ms-office-suite-powerpoint-2016-word-and-excel/"><u>Adjusting Default File Formats in MS Office Suite (PowerPoint 2016, Word & Excel)</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/affordable-tech-on-the-go-amazon-fire-hd-8-8th-gen-features-and-value-insights/"><u>Affordable Tech on the Go: Amazon Fire HD 8 (8Th Gen) Features and Value Insights.</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/-digital-domination-top-10-youtube-viewership-ranking/"><u>Daily Digital Domination  Top 10 YouTube Viewership Ranking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detect-signs-is-it-time-for-windows-clean-slate/"><u>Detect Signs: Is It Time for Windows Clean Slate?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-techniques-for-assigning-row-numbers-in-ms-excel-a-step-by-step-guide/"><u>Effective Techniques for Assigning Row Numbers in MS Excel: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-diagnosing-and-fixing-cc-issues-on-windows-10/"><u>Efficiently Diagnosing and Fixing CC Issues on Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-leading-zeros-display-in-microsoft-excel-a-comprehensive-guide/"><u>Ensuring Leading Zeros Display in Microsoft Excel: A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-scribbling-in-windows-11-effortlessly/"><u>Get Scribbling in Windows 11 Effortlessly</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-delete-gmail-account-withwithout-password-on-nubia-red-magic-9-pro-by-drfone-android/"><u>In 2024, Delete Gmail Account With/Without Password On Nubia Red Magic 9 Pro</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-send-and-fake-live-location-on-facebook-messenger-of-your-asus-rog-phone-7-drfone-by-drfone-virtual-android/"><u>In 2024, How to Send and Fake Live Location on Facebook Messenger Of your Asus ROG Phone 7 | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-music-from-nokia-xr21-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Music from Nokia XR21 to iPod | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-step-by-step-guide-for-easy-macbook-air-recordings/"><u>In 2024, Step-by-Step Guide for Easy Macbook Air Recordings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-excel-spreadsheets-into-your-slides-a-step-by-step-guide/"><u>Integrating Excel Spreadsheets Into Your Slides: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-excel-reporting-build-professional-dashboards-for-insightful-analytics/"><u>Master Excel Reporting: Build Professional Dashboards for Insightful Analytics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-microsoft-store-repairs-fixing-code-0x80072f30-quickly/"><u>Master Microsoft Store Repairs: Fixing Code 0X80072F30 Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-excel-a-step-by-step-guide-to-using-index-and-match/"><u>Mastering Excel: A Step-by-Step Guide to Using INDEX and MATCH</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-ms-excel-a-comprehensive-tutorial-on-square-root-calculation-techniques/"><u>Mastering MS Excel: A Comprehensive Tutorial on Square Root Calculation Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-disabling-windows-updates/"><u>Mastering the Art of Disabling Windows Updates</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/mastery-guide-securely-archiving-snapchat-media-on-devices-for-2024/"><u>Mastery Guide  Securely Archiving Snapchat Media on Devices for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-command-prompt-a-guide-to-user-management/"><u>Navigating Command Prompt: A Guide to User Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-startup-hurdles-for-photoshop-on-windows-1011/"><u>Overcoming Startup Hurdles for Photoshop on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proactive-approach-locating-your-devices-mac-address-in-windows-11/"><u>Proactive Approach: Locating Your Device's MAC Address in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redesigning-workplace-efficiency-with-microsofts-latest-office-template-overhaul/"><u>Redesigning Workplace Efficiency with Microsoft's Latest Office Template Overhaul</u></a></li>
<li><a href="https://win11-tips.techidaily.com/selecting-the-ideal-excel-chart-type-a-guide-for-presenting-your-data-effectively/"><u>Selecting the Ideal Excel Chart Type: A Guide for Presenting Your Data Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-switching-between-foreign-languages-on-windows-devices/"><u>Speedy Switching Between Foreign Languages on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-adjusting-gaps-between-cells-text-and-borders-in-excel-spreadsheets/"><u>Step-by-Step Guide: Adjusting Gaps Between Cells, Text, and Borders in Excel Spreadsheets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-creating-a-pie-chart-using-microsoft-excel/"><u>Step-by-Step Guide: Creating a Pie Chart Using Microsoft Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-implementing-strikethrough-text-feature-in-microsoft-excel/"><u>Step-by-Step Guide: Implementing Strikethrough Text Feature in Microsoft Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-tackle-audacitys-sound-fault-windows-11-os/"><u>Strategies to Tackle Audacity's Sound Fault, Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-file-management-overcoming-o365-errors-on-win-11/"><u>Streamlined File Management: Overcoming O365 Errors on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-the-process-of-adjusting-pointer-settings-in-windows-11/"><u>Streamlining the Process of Adjusting Pointer Settings in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-reverting-windows-folders-to-full-editability/"><u>Tips for Reverting Windows Folders to Full Editability</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-11-amazing-tricks-and-tasks-achievable-using-siri-on-your-mac/"><u>Top 11 Amazing Tricks and Tasks Achievable Using Siri on Your Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-9-essential-excel-text-manipulation-techniques-using-microsoft-office/"><u>Top 9 Essential Excel Text Manipulation Techniques Using Microsoft Office</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unifying-ms-office-suite-with-your-zoho-online-platform-a-step-by-step-guide/"><u>Unifying MS Office Suite with Your Zoho Online Platform: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-efficiency-with-google-sheets-top-14-capabilities-missed-in-microsoft-excel/"><u>Unlocking Efficiency with Google Sheets: Top 14 Capabilities Missed in Microsoft Excel</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-the-best-in-computer-hardware-by-toms-review-corner/"><u>Unveiling the Best in Computer Hardware by Tom’s Review Corner</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/unveiling-the-best-ways-to-watch-360-videos-on-android/"><u>Unveiling the Best Ways to Watch 360 Videos on Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-secrets-of-successful-gmaps-integration-in-windows/"><u>Unveiling the Secrets of Successful GMaps Integration in Windows</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-leading-video-chat-services-a-ranked-guide-to-alternative-omegle-options/"><u>Updated Leading Video Chat Services A Ranked Guide to Alternative Omegle Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-context-menu-incorporating-copy-and-move-commands-into-folder-options-win-11/"><u>Upgrade Context Menu: Incorporating Copy & Move Commands Into Folder Options (Win 11)</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/wie-man-epub-ruckwartssicherung-entfernt-eine-einfache-anleitung/"><u>Wie Man EPUB-Rückwärtssicherung Entfernt: Eine Einfache Anleitung</u></a></li>
<li><a href="https://win11-tips.techidaily.com/work-on-excel-powerpoint-and-word-online-doc-editing-anywhere/"><u>Work on Excel, PowerPoint & Word Online Doc Editing Anywhere</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>