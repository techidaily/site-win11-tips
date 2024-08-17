---
title: A Step-By-Step Manual for WS11's Software Reset
date: 2024-08-16T01:17:17.308Z
updated: 2024-08-17T01:17:17.308Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Step-By-Step Manual for WS11's Software Reset
excerpt: This Article Describes A Step-By-Step Manual for WS11's Software Reset
keywords: WS11 Reset Guide,SoftReset WS11 Manual,WS11 Software Troubleshoot,Step-by-Step WS11 Fix,Resetting WS11 System,WS11 Reboot Instructions,Software Restore WS11
thumbnail: https://thmb.techidaily.com/b9c87935bcb636b8006c11267defd1b13d4f0a5467f4617c51e1bd762f7f5db4.png
---

## A Step-By-Step Manual for WS11's Software Reset

 Users widely report Windows 11 update errors on support forums. Updates fail to install because of such errors. You can often fix update errors by resetting the catroot 2 and Windows SoftwareDistribution folders as covered below.

## What Are the SoftwareDistribution and Catroot2 Folders?

 The SoftwareDistribution folder is a directory that stores files required for installing Windows updates on PCs. It is a temporary repository of the update files. Thus, the SoftwareDistribution folder is an important component for updating Windows.

 Catroot 2 is a folder that stores the signature data for Windows 11 updates. Those are the files the Cryptographic service needs for update verification.

 Both folders contain files needed for the installation of Windows updates. Windows update installation issues can occur because of corrupted data in those folders. Those errors typically appear in Settings with variable codes like 0x800f0922 when users manually select to check for and install updates.

 Therefore, resetting those folders is a troubleshooting method for fixing Windows 11 update installation issues. Resetting the SoftwareDistribution and Catroot2 folders removes corrupted data they might contain, which rebuilds them. You can reset those folders by deleting their contents or renaming them.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
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
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Enter and execute this rename command for the catroot2 folder:  
`ren %systemroot%\system32\catroot2 catroot2.bak`  
![The ren catroot2 command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/ren-catroot2-folder.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->
5. Repeat step 11 of the preceding method by executing the four commands for restarting the disabled services.  
![The net start command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/net-start-commands.jpg)
<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Exit Command Prompt and select to restart your PC.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
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
7. Click **Additional Fixes** on the left of the FixWin window.
8. Select the **Quick Fixes** tab.
9. Press the **Reset Software Distribution folder** button.  
![The Quick Fixes tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/quick-fixes-tab.jpg)
10. Click the **Reset catroo2 Folder** option.
11. Exit FixWin and reboot your PC after selecting those options.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-glue.techidaily.com/new-unraveling-chroma-key-mystery-for-everyone-starting-off-with-green-screen-for-2024/"><u>[New] Unraveling Chroma Key Mystery  For Everyone Starting Off with Green Screen for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-9-powerful-youtube-video-downloader-for-android-for-2024/"><u>[Updated] 9 Powerful YouTube Video Downloader for Android for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-efficient-obs-fb-streaming-techniques-for-2024/"><u>[Updated] Efficient OBS-FB Streaming Techniques for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-invisible-pathways-advanced-techniques-for-chat-file-extraction-for-2024/"><u>[Updated] Invisible Pathways  Advanced Techniques for Chat File Extraction for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-key-steps-for-efficient-access-to-windows-connections-tool/"><u>10 Key Steps for Efficient Access to Window's Connections Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-key-tips-for-restoring-fbm-functionality-on-desktop/"><u>10 Key Tips for Restoring FBM Functionality on Desktop</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-from-free-posts-to-fiscal-success-fb-pages-profit-playbook/"><u>2024 Approved  From Free Posts to Fiscal Success  FB Pages Profit Playbook</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-ultimate-buyers-blueprint-for-youtubers/"><u>2024 Approved  The Ultimate Buyer's Blueprint for Youtubers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-android-innovations-to-transform-your-windows-11-setup/"><u>6 Android Innovations to Transform Your Windows 11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-crucial-strategies-to-salvage-a-frozen-windows-service-panel/"><u>7 Crucial Strategies to Salvage a Frozen Windows Service Panel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-guide-to-windows-narrators-legacy-keyboard-shortcuts/"><u>A Complete Guide to Windows Narrator's Legacy Keyboard Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-walkthrough-cortana-data-retrieval-for-windows-users/"><u>A Complete Walkthrough: Cortana Data Retrieval for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-fix-13-solutions-for-windows-system-repair/"><u>A Quick Fix: 13 Solutions for Windows System Repair</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-quick-guide-to-oneplus-11r-frp-bypass-instantly-by-drfone-android/"><u>A Quick Guide to OnePlus 11R FRP Bypass Instantly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-through-to-windows-11-security-control-screen/"><u>A Step-by-Step Through to Windows 11 Security Control Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-file-browsing-activate-filters-with-checkbox-on-win11/"><u>Accelerate File Browsing: Activate Filters with Checkbox on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-system-load-in-win11/"><u>Accelerate System Load in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/access-display-settings-right-click-on-the-desktop-and-select-display-settings/"><u>Access Display Settings: Right-Click on the Desktop and Select Display Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-unviewable-documents-error-in-microsoft-office-mail/"><u>Addressing 'Unviewable' Documents Error in Microsoft Office Mail</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-network-disconnect-in-windows-11-a-step-by-step-guide/"><u>Addressing Network Disconnect in Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-loading-device-drivers-in-windows-11/"><u>Addressing Non-Loading Device Drivers in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-slowness-in-windows-discord-interface/"><u>Addressing Slowness in Windows Discord Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-timeout-issue-windows-1110-semaphore-error-0x80070079/"><u>Addressing Timeout Issue - Windows 11/10 Semaphore Error 0X80070079</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-your-windows-dynamic-background-anytime/"><u>Adjusting Your Windows Dynamic Background Anytime</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-tips-for-managing-users-via-command-prompt/"><u>Advanced Tips for Managing Users via Command Prompt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-graphics-memory-a-comprehensive-guide-to-supercharging-win1011/"><u>Amplify Graphics Memory - A Comprehensive Guide to Supercharging Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-in-depth-look-at-winservicesexe-and-its-errors/"><u>An In-Depth Look at Winservices.exe and Its Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/approach-to-reveal-hidden-drives-on-windows/"><u>Approach to Reveal Hidden Drives on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assessing-your-windows-11-activation-status/"><u>Assessing Your Windows 11 Activation Status</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augmenting-desktop-interactivity-the-widget-approach-in-win-11/"><u>Augmenting Desktop Interactivity: The Widget Approach in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-editing-setup-office-products-word-for-text-only-opened-attachments/"><u>Avoid Editing: Setup Office Products (Word) for Text Only Opened Attachments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-visual-clutter-inside-windows-search/"><u>Avoiding Visual Clutter Inside Windows Search</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-directional-audio-with-windows-earbuds/"><u>Balancing Directional Audio with Windows Earbuds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beat-the-100-quagmire-with-these-simple-solutions/"><u>Beat the 100%% Quagmire with These Simple Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginners-trick-swiftly-access-sticky-notes-post-boot-windows/"><u>Beginner's Trick: Swiftly Access Sticky Notes Post-Boot Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-windows-11-videoscripting-software-round-up/"><u>Best Windows 11 Videoscripting Software Round-Up</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-windows-single-board-gadgets/"><u>Best Windows Single-Board Gadgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-utilizing-box-for-file-selections-in-win11/"><u>Boost Efficiency: Utilizing Box for File Selections in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-power-visibility-customizing-full-charge-alerts-for-win11/"><u>Boost Power Visibility: Customizing Full Charge Alerts for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-system-health-through-interactive-device-tracking/"><u>Boost System Health Through Interactive Device Tracking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-workflow-the-ultimate-guide-to-wpm-in-windows-11/"><u>Boost Your Workflow: The Ultimate Guide to WPM in Windows 11</u></a></li>
<li><a href="https://fox-info.techidaily.com/crafting-success-steps-to-thriving-as-a-designer-for-2024/"><u>Crafting Success  Steps to Thriving as a Designer for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/obal-with-music-transform-your-spotify-lists-into-youtube-videos/"><u>Go Global with Music  Transform Your Spotify Lists Into YouTube Videos</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-xiaomi-redmi-a2-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Xiaomi Redmi A2 without Losing Data | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-realme-12-proplus-5g-phone-with-broken-screen-by-drfone-android/"><u>How to Unlock Realme 12 Pro+ 5G Phone with Broken Screen</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-atandt-apple-iphone-11-pro-with-3-methods-by-drfone-ios/"><u>In 2024, How to Unlock AT&T Apple iPhone 11 Pro with 3 Methods</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-revamp-your-chat-audio-experience-with-a-personalized-whatsapp-ringtone/"><u>In 2024, Revamp Your Chat Audio Experience with a Personalized WhatsApp Ringtone</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/mastering-car-ai-troubleshooting-and-fixing-6-common-mishaps/"><u>Mastering Car AI: Troubleshooting & Fixing 6 Common Mishaps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719255690388-pro-tips-to-improve-your-snip-and-sketch-screenshot-experience/"><u>Pro Tips to Improve Your Snip & Sketch Screenshot Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719381156661-reactive-keys-reclaiming-shift-on-win/"><u>Reactive Keys: Reclaiming Shift on Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719258042287-reclaiming-chrome-in-w11-easy-to-follow-remediation-tips/"><u>Reclaiming Chrome in W11 - Easy-to-Follow Remediation Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719292309532-revolutionize-incompatibility-on-windows-without-tools/"><u>Revolutionize Incompatibility on Windows without Tools!</u></a></li>
<li><a href="https://facebook.techidaily.com/sustainability-shines-facebooks-full-renewable-dependency/"><u>Sustainability Shines: Facebook's Full Renewable Dependency</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/the-updated-method-to-bypass-xiaomi-redmi-note-12-5g-frp-by-drfone-android/"><u>The Updated Method to Bypass Xiaomi Redmi Note 12 5G FRP</u></a></li>
</ul></div>
