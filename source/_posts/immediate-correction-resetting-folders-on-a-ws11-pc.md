---
title: "Immediate Correction: Resetting Folders on a WS11 PC"
date: 2024-08-16T01:45:45.234Z
updated: 2024-08-17T01:45:45.234Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Immediate Correction: Resetting Folders on a WS11 PC"
excerpt: "This Article Describes Immediate Correction: Resetting Folders on a WS11 PC"
keywords: WS11 Folder Reset Guide,WS11 Restore Directories,Windows WS11 Folder Fix,Quick Directory Reset WS11,WS11 PC Folders Update,Immediate WS11 Folder Recovery,Resetting Folders on WS11
thumbnail: https://thmb.techidaily.com/d5d5810dfb5162fe3838fd5a512ce840bf5c9c8c52397ab8a1f2ef651a47611e.jpg
---

## Immediate Correction: Resetting Folders on a WS11 PC

 Users widely report Windows 11 update errors on support forums. Updates fail to install because of such errors. You can often fix update errors by resetting the catroot 2 and Windows SoftwareDistribution folders as covered below.

## What Are the SoftwareDistribution and Catroot2 Folders?

 The SoftwareDistribution folder is a directory that stores files required for installing Windows updates on PCs. It is a temporary repository of the update files. Thus, the SoftwareDistribution folder is an important component for updating Windows.

 Catroot 2 is a folder that stores the signature data for Windows 11 updates. Those are the files the Cryptographic service needs for update verification.

 Both folders contain files needed for the installation of Windows updates. Windows update installation issues can occur because of corrupted data in those folders. Those errors typically appear in Settings with variable codes like 0x800f0922 when users manually select to check for and install updates.

 Therefore, resetting those folders is a troubleshooting method for fixing Windows 11 update installation issues. Resetting the SoftwareDistribution and Catroot2 folders removes corrupted data they might contain, which rebuilds them. You can reset those folders by deleting their contents or renaming them.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
11. Return to the Command Prompt and execute these separate commands for restarting the disabled services.  
`net start bits  

net start wuauserv  

net start cryptSvc  

net start msiserver`
12. Restart the PC and check for updates after clearing those folders.

## How to Reset the SoftwareDistribution and Catroot2 Folders by Renaming Them

 Renaming the SoftwareDistribution and Catroot2 directories is an alternative method for resetting those folders. Windows will recreate those folders after you’ve renamed them. You can rename the SoftwareDistribution and catroot2 folders with the Command Prompt like this:

1. Run the Command Prompt with elevated admin rights.
2. Repeat step four of the preceding method to execute the commands for disabling services.  
![The net stop commands](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/net-stop-commands.jpg)
3. Input this command to rename the SoftwareDistribution folder and press **Return**:  
`ren %systemroot%\softwaredistribution softwaredistribution.bak`  
![The rename SoftwareDistribution folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/ren-softwaredistribution-command.jpg)
<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
4. Enter and execute this rename command for the catroot2 folder:  
`ren %systemroot%\system32\catroot2 catroot2.bak`  
![The ren catroot2 command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/ren-catroot2-folder.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Repeat step 11 of the preceding method by executing the four commands for restarting the disabled services.  
![The net start command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/net-start-commands.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
6. Exit Command Prompt and select to restart your PC.

## How to Reset the SoftwareDistribution and Catroot2 Folders With FixWin 11

 FixWin 11 is one of the [best freely available Windows repair tools](https://www.makeuseof.com/tag/5-free-tools-fix-problem-windows-10/) that includes troubleshooting options. Among them are two options for resetting the catroot2 and SoftwareDistribution folders. This is how you can select those quick fix options in FixWin 11:

1. Open this [FixWin 11 page](https://www.softpedia.com/get/Tweak/System-Tweak/FixWin-11.shtml) on the Softpedia website.
2. Click on the **Free Download** button for FixWin.
3. Select **Secure Download (US)** to obtain FixWin’s ZIP archive.
4. Activate a File Explorer window and go to your browser’s downloads folder.
5. Extract the FixWin archive by going through the steps in this article about [unzipping ZIP files on Windows](https://www.makeuseof.com/how-to-extract-zip-files-windows-11/).  
![The Extract Compressed ZIP archive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/extract-compressed-window.jpg)
6. Double-click the **FixWin 11.1.exe** file in the extracted folder for FixWin.
7. Click **Additional Fixes** on the left of the FixWin window.
8. Select the **Quick Fixes** tab.
9. Press the **Reset Software Distribution folder** button.  
![The Quick Fixes tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/quick-fixes-tab.jpg)
10. Click the **Reset catroo2 Folder** option.
11. Exit FixWin and reboot your PC after selecting those options.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## Fix Windows Update Issues by Resetting the SoftwareDistribution and Catroot2 Folders

 It’s important to resolve update issues when they arise for the sake of keeping Windows updated. Resetting the catroo2 and SoftwareDistribution folders is one of the most effective troubleshooting methods for fixing Windows update errors.

 So, try doing that whenever you need to fix an error code shown within the Windows Update tab of Settings.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-harness-freedom-with-top-rated-android-editing-apps/"><u>[New] 2024 Approved  Harness Freedom with Top-Rated Android Editing Apps</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-unplugged-bliss-selecting-smartphone-slowdowns/"><u>[New] In 2024, Unplugged Bliss  Selecting Smartphone Slowdowns</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-fine-tuning-color-balance-in-obs/"><u>[Updated] In 2024, Fine-Tuning Color Balance in OBS</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-ios-snapshot-spectrum-your-quick-reference/"><u>[Updated] IO's Snapshot Spectrum  Your Quick Reference</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-optimizing-team-calls-prepost-meeting-screen-customization-for-2024/"><u>[Updated] Optimizing Team Calls  Pre/Post-Meeting Screen Customization for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/12-superfluous-windows-tools-you-can-live-without/"><u>12 Superfluous Windows Tools You Can Live Without</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-ultimate-storage-solution-for-sony-a7s-ii/"><u>2024 Approved  Ultimate Storage Solution for Sony A7S II</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-century-of-change-the-windows-taskbar/"><u>A Century of Change: The Windows Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-walkthrough-upgrading-surface-hardware/"><u>A Comprehensive Walkthrough: Upgrading Surface Hardware</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-guide-to-restoring-essential-features-of-photo-viewer-on-win11/"><u>A Quick Guide to Restoring Essential Features of Photo Viewer on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/access-and-annotate-comics-easily-on-win11/"><u>Access and Annotate Comics Easily on Win11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/1721926130457-access-openais-newest-innovation-the-exclusive-gpt-custom-store-start-using-today/"><u>Access OpenAI's Newest Innovation: The Exclusive GPT Custom Store - Start Using Today!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-an-innovative-auto-refresh-check-option-to-the-windows-ui/"><u>Adding an Innovative Auto-Refresh Check Option to the Windows UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-efficiency-program-troubleshooting-tool-inclusion/"><u>Adding Efficiency: Program Troubleshooting Tool Inclusion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-no-camera-found-error-on-windows-11-os/"><u>Addressing No Camera Found Error on Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-missing-rockalldlldll-problem/"><u>Addressing the 'Missing Rockalldll.dll' Problem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-empty-display-of-system-startups/"><u>Addressing the Empty Display of System Startups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-black-remote-desktop-display/"><u>Addressing Window's Black Remote Desktop Display</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-windows-customization-adding-directories-to-context-menu/"><u>Advanced Windows Customization - Adding Directories to Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-integration-windows-11s-next-chapter/"><u>AI Integration: Windows 11'S Next Chapter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-windows-fn-key-behavior-for-efficiency/"><u>Altering Windows Fn Key Behavior for Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-windows-efficiency-embrace-adaptive-tiling/"><u>Amplify Windows Efficiency: Embrace Adaptive Tiling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-and-ranking-video-codecs-for-windows-pcs/"><u>Analyzing and Ranking Video Codecs for Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-teamsters-crashes-on-windows-11-10/"><u>Avoiding Teamsters Crashes on Windows 11, 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bar-of-time-the-windows-taskbars-journey/"><u>Bar of Time: The Windows Taskbar's Journey</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719328256303-bargain-alert-key-enthusiasts-snag-612lifetime-windows-11-deal-today-only/"><u>Bargain Alert: Key Enthusiasts Snag $6.12/Lifetime Windows 11 Deal Today Only!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beating-the-default-shrinking-in-winos/"><u>Beating the Default Shrinking in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-tools-for-win-soft-installation-chocolatey-or-wm/"><u>Best Tools for Win Soft Installation: Chocolatey or WM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-functionality-with-windows-11s-taskbar/"><u>Boosting Functionality with Windows 11'S Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-the-effectiveness-of-your-pointer-on-win11s-system/"><u>Boosting the Effectiveness of Your Pointer on Win11's System</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/budget-friendly-edits-made-easy-with-vimeos-free-tools/"><u>Budget-Friendly Edits Made Easy with Vimeo's Free Tools</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-google-frp-lock-from-realme-c53-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock from Realme C53 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-solution-fixing-windows-auto-detect-proxy-errors/"><u>Immediate Solution: Fixing Windows' Auto Detect Proxy Errors</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-oneplus-ace-2-pro-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>In 2024, How to Unlock OnePlus Ace 2 Pro Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-apple-iphone-12-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, Why Your WhatsApp Location is Not Updating and How to Fix On Apple iPhone 12 Pro Max | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-depth-insights-into-camstudio-recording/"><u>In-Depth Insights Into CamStudio Recording</u></a></li>
<li><a href="https://extra-skills.techidaily.com/perfecting-your-images-lightrooms-favorite-luts-for-2024/"><u>Perfecting Your Images  LightRoom's Favorite LUTs for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/solving-r9-driver-issues-on-windows-10-platform/"><u>Solving R9 Driver Issues on Windows 10 Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719239834039-start-menu-no-more-unwanted-advertisements/"><u>Start Menu, No More Unwanted Advertisements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719319856563-turbocharge-windows-11-boot-speed-heres-how/"><u>Turbocharge Windows 11 Boot Speed – Here’s How!</u></a></li>
<li><a href="https://unlock-android.techidaily.com/universal-unlock-pattern-for-vivo-y100i-power-5g-by-drfone-android/"><u>Universal Unlock Pattern for Vivo Y100i Power 5G</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/visionary-vistas-the-ultimate-list-of-motivating-ig-images-for-2024/"><u>Visionary Vistas  The Ultimate List of Motivating IG Images for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/where-is-the-best-place-to-catch-dratini-on-oneplus-12r-drfone-by-drfone-virtual-android/"><u>Where Is the Best Place to Catch Dratini On OnePlus 12R | Dr.fone</u></a></li>
</ul></div>
