---
title: Mastering the Art of Restarting Windows Updates
date: 2024-08-16T01:55:04.849Z
updated: 2024-08-17T01:55:04.849Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the Art of Restarting Windows Updates
excerpt: This Article Describes Mastering the Art of Restarting Windows Updates
keywords: Update Restarts Mastery,Windows Update Control,Tech Update Reinitiation,Renew Windows Update,Pause & Resume Updates,Fixing Update Issues,Update Rollback Guide,Master Update Restarts,Tech Updates Renewal,Pause & Resume Windows Updates,Fix Update Errors,Update Rollback Steps,Guide to Windows Updates Restart
thumbnail: https://thmb.techidaily.com/5a836c04a4d923a2e47e122afc97ffb5e93afa98d18b4563b5a8924a658295ed.jpg
---

## Mastering the Art of Restarting Windows Updates

 When addressing errors and issues associated with a system update, you may need to reset the Windows Update components. You can achieve this by running a few commands in the Command Prompt or by creating and executing a batch file.

 This guide will provide a detailed walkthrough for both methods, allowing you to effectively reset the Windows Update components.

## 1\. How to Reset the Windows Update Components Manually

 The most common method for resetting Windows Update components is through the Command Prompt. Here are the steps you can follow.

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt shows up.
3. Copy and paste the following commands one by one and press **Enter** after each command to stop each service related to Windows Update.  
`net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc`  
![Reset Windows Update Components Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-windows-update-components-using-command-prompt.jpg)
4. Run the following command to delete the **qmgr\*.dat** files.  
`Del "%ALLUSERSPROFILE%\Application Data\Microsoft\Network\Downloader\*.*"`
5. Enter **Y** to confirm.

1. Type the following commands and press **Enter** after each to delete all the Windows Update files.  
`rmdir %systemroot%\SoftwareDistribution /S /Q  
rmdir %systemroot%\system32\catroot2 /S /Q`
2. Type the following commands and press **Enter** after each to reset the BITS and Windows Update services to their default security descriptors.  
`sc.exe sdset bits D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
sc.exe sdset wuauserv D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)`
3. Now, run the following command to navigate to the **System32** folder.  
`cd /d %windir%\system32`
4. Copy and paste the following commands individually and press **Enter** after each to re-register all the BITS and Windows Update files.  
`regsvr32.exe /s atl.dll  
regsvr32.exe /s urlmon.dll  
regsvr32.exe /s mshtml.dll  
regsvr32.exe /s shdocvw.dll  
regsvr32.exe /s browseui.dll  
regsvr32.exe /s jscript.dll  
regsvr32.exe /s vbscript.dll  
regsvr32.exe /s scrrun.dll  
regsvr32.exe /s msxml.dll  
regsvr32.exe /s msxml3.dll  
regsvr32.exe /s msxml6.dll  
regsvr32.exe /s actxprxy.dll  
regsvr32.exe /s softpub.dll  
regsvr32.exe /s wintrust.dll  
regsvr32.exe /s dssenh.dll  
regsvr32.exe /s rsaenh.dll  
regsvr32.exe /s gpkcsp.dll  
regsvr32.exe /s sccbase.dll  
regsvr32.exe /s slbcsp.dll  
regsvr32.exe /s cryptdlg.dll  
regsvr32.exe /s oleaut32.dll  
regsvr32.exe /s ole32.dll  
regsvr32.exe /s shell32.dll  
regsvr32.exe /s initpki.dll  
regsvr32.exe /s wuapi.dll  
regsvr32.exe /s wuaueng.dll  
regsvr32.exe /s wuaueng1.dll  
regsvr32.exe /s wucltui.dll  
regsvr32.exe /s wups.dll  
regsvr32.exe /s wups2.dll  
regsvr32.exe /s wuweb.dll  
regsvr32.exe /s qmgr.dll  
regsvr32.exe /s qmgrprxy.dll  
regsvr32.exe /s wucltux.dll  
regsvr32.exe /s muweb.dll  
regsvr32.exe /s wuwebv.dll`
5. Type the following and press **Enter** to reset Winsock (Windows Sockets).  
`netsh winsock reset`
6. Copy and paste the following commands one by one and press **Enter** after each to restart the services related to Windows Update.  
`net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`

 Close the Command Prompt window and restart your PC to apply the changes. If you're interested in discovering more useful commands, check our guide on the [best Command Prompt commands](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/) for Windows.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. How to Reset the Windows Update Components Using a Batch File

 Another way to reset Windows Update components is to [create and run a batch file in Windows](https://www.makeuseof.com/tag/write-simple-batch-bat-file/). Here are the steps to make one:

1. Press **Win + S** to open the search menu.
2. Type **Notepad** in the search box and press **Enter**.
3. Copy and paste the following command in the Notepad window.  
`net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc  
Del "%ALLUSERSPROFILE%\Application Data\Microsoft\Network\Downloader\*.*"  
rmdir %systemroot%\SoftwareDistribution /S /Q  
rmdir %systemroot%  
system32\catroot2 /S /Q  
sc.exe sdset bits D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
sc.exe sdset wuauserv D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
cd /d %windir% system32  
regsvr32.exe /s atl.dll  
regsvr32.exe /s urlmon.dll  
regsvr32.exe /s mshtml.dll  
regsvr32.exe /s shdocvw.dll  
regsvr32.exe /s browseui.dll  
regsvr32.exe /s jscript.dll  
regsvr32.exe /s vbscript.dll  
regsvr32.exe /s scrrun.dll  
regsvr32.exe /s msxml.dll  
regsvr32.exe /s msxml3.dll  
regsvr32.exe /s msxml6.dll  
regsvr32.exe /s actxprxy.dll  
regsvr32.exe /s softpub.dll  
regsvr32.exe /s wintrust.dll  
regsvr32.exe /s dssenh.dll  
regsvr32.exe /s rsaenh.dll  
regsvr32.exe /s gpkcsp.dll  
regsvr32.exe /s sccbase.dll  
regsvr32.exe /s slbcsp.dll  
regsvr32.exe /s cryptdlg.dll  
regsvr32.exe /s oleaut32.dll  
regsvr32.exe /s ole32.dll  
regsvr32.exe /s shell32.dll  
regsvr32.exe /s initpki.dll  
regsvr32.exe /s wuapi.dll  
regsvr32.exe /s wuaueng.dll  
regsvr32.exe /s wuaueng1.dll  
regsvr32.exe /s wucltui.dll  
regsvr32.exe /s wups.dll  
regsvr32.exe /s wups2.dll  
regsvr32.exe /s wuweb.dll  
regsvr32.exe /s qmgr.dll  
regsvr32.exe /s qmgrprxy.dll  
regsvr32.exe /s wucltux.dll  
regsvr32.exe /s muweb.dll  
regsvr32.exe /s wuwebv.dll  
netsh winsock reset  
netsh winsock reset proxy  
net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`
4. Click the **File** menu at the top, then **Save as**.  
![Save a Notepad File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/save-a-notepad-file.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Enter **Reset Windows Components.bat** in the name field and specify your preferred location for saving the file.
6. Click the **Save as type** drop-down menu to select **All files**, then click on **Save**.
7. Locate the saved batch file on your PC. Right-click on it and select **Run as administrator** from the context menu.
8. Select **Yes** when the User Account Control (UAC) prompt appears.  
![Reset Windows Update Components Using a Batch File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-windows-update-components-using-a-batch-file.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->

 Once you've executed the batch file, feel free to keep it around. That way, the next time you encounter problems with Windows Update, you can run the file again without having to repeat the above steps.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
## Reset the Windows Update Components to Fix Problems

 Downloading and installing Windows updates may not always be smooth. In such cases, resetting the Windows Update components can prove effective. However, if that doesn't work, you may have to try your luck with other Windows Update fixes.

 This guide will provide a detailed walkthrough for both methods, allowing you to effectively reset the Windows Update components.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-beginners-path-to-screen-casting-with-apple-devices/"><u>[New] 2024 Approved  Beginner’s Path to Screen Casting with Apple Devices</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-secrets-of-thriving-in-the-top-10-business-channel-space/"><u>[New] 2024 Approved  Secrets of Thriving in the Top 10 Business Channel Space</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-harmony-hub-capture-store-and-review-sounds-for-2024/"><u>[New] Harmony Hub  Capture, Store & Review Sounds for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-from-play-to-view-a-guide-to-recording-overwatch-games/"><u>[New] In 2024, From Play to View  A Guide to Recording Overwatch Games</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-how-to-schedule-and-dive-into-virtual-gatherings-with-zoom-on-an-android-platform/"><u>[New] In 2024, How to Schedule and Dive Into Virtual Gatherings with Zoom on an Android Platform</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-master-windows-11-a-treasure-trove-of-undisclosed-features/"><u>[New] Master Windows 11  A Treasure Trove of Undisclosed Features</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-digital-deviation-expert-strategies-to-rotate-videos-on-youtube/"><u>[Updated] Digital Deviation  Expert Strategies to Rotate Videos on YouTube</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-effortless-conversions-selecting-the-10-prime-flv-to-youtubes-options/"><u>[Updated] Effortless Conversions  Selecting the 10 Prime Flv to YouTubes Options</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-figure-skating-highlights-2022-winter-olympics/"><u>[Updated] Figure Skating Highlights 2022 Winter Olympics</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-stepwise-simplification-broadcasting-personal-yt-videos-using-gmail/"><u>[Updated] Stepwise Simplification  Broadcasting Personal YT Videos Using Gmail</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-unraveling-the-secrets-to-smooth-vimeo-video-downloads/"><u>[Updated] Unraveling the Secrets to Smooth Vimeo Video Downloads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cool-running-tech-maintaining-moderate-temperatures-while-gaming/"><u>Cool Running Tech: Maintaining Moderate Temperatures While Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/counteracting-no-display-available-on-windows-11/"><u>Counteracting 'No Display Available' On Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-one-way-outlook-on-secure-windows-operating-system/"><u>Dealing with One-Way Outlook on Secure Windows Operating System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-into-unparalleled-windows-software-selection/"><u>Dive Into Unparalleled Windows Software Selection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-boot-speed-manipulating-boot-sequence-timer/"><u>Enhancing Boot Speed: Manipulating Boot Sequence Timer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enriching-context-menus-adding-a-diskspace-analyzer-feature/"><u>Enriching Context Menus: Adding a DiskSpace Analyzer Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-the-depths-of-0x0000003b-bsod-error-in-windows-pcs/"><u>Exploring the Depths of 0X0000003B BSOD Error in Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-no-connection-to-ea-servers-on-your-pc/"><u>Fixing No Connection to EA Servers on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harnessing-the-potential-of-wingetui-for-w11-package-management/"><u>Harnessing the Potential of WingetUI for W11 Package Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-activate-w11s-accelerated-support-mode/"><u>How to Activate W11’s Accelerated Support Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-expand-your-playnite-digital-library-on-windows-pcs/"><u>How to Expand Your Playnite Digital Library on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-manage-spotlight-images-on-your-pcs-lock-screen/"><u>How to Manage Spotlight Images on Your PC's Lock Screen</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-tecno-spark-go-2024-by-phone-number-drfone-by-drfone-virtual-android/"><u>How to Track Tecno Spark Go (2024) by Phone Number | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-a-vivo-x100-easily-by-drfone-android/"><u>How To Unlock a Vivo X100 Easily?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lack-of-drive-letters-on-your-windows-pc-heres-why-and-how-to-fix-it/"><u>Lack of Drive Letters on Your Windows PC? Here's Why & How to Fix It</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/leading-edge-in-game-capture-moving-past-fbx-methods/"><u>Leading Edge in Game Capture  Moving Past FBX Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leading-non-windows-programs-as-substitutes-for-the-windows-snip-tool/"><u>Leading Non-Windows Programs as Substitutes for the Window’s Snip Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-mkv-to-mp4-transformation-on-windows/"><u>Navigating Through MKV-to-MP4 Transformation on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-shift-key-stickiness-in-windows-os/"><u>Overcome Shift Key Stickiness in Windows OS</u></a></li>
<li><a href="https://buynow-info.techidaily.com/precision-and-durability-in-every-detail-reviewing-the-stable-masterpiece-that-is-the-twelve-south-compass-pro/"><u>Precision and Durability in Every Detail: Reviewing the Stable Masterpiece That Is the Twelve South Compass Pro</u></a></li>
<li><a href="https://screen-capture.techidaily.com/pro-tips-for-video-conference-recordings-desktop-edition/"><u>Pro Tips for Video Conference Recordings  Desktop Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-network-unavailable-error-on-windows-devices/"><u>Remedying 'Network Unavailable' Error on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-spotify-freeze-issue-in-windows-11-os/"><u>Resolving Spotify Freeze Issue in Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revenue-sources-for-windows-11-microsofts-strategy/"><u>Revenue Sources for Windows 11: Microsoft's Strategy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-a-chrome-friendly-environment-in-windows-11/"><u>Setting Up a Chrome-Friendly Environment in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-fixing-windows-service-non-responder-error/"><u>Strategies for Fixing Windows Service Non-Responder Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-system-efficiency-incorporating-law-filters-into-your-workflow/"><u>Streamlining System Efficiency: Incorporating LAW Filters Into Your Workflow</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-best-weather-apps-for-windows-11-and-11/"><u>The Best Weather Apps for Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-launching-windows-ea-quickly/"><u>The Ultimate Guide to Launching Windows EA Quickly</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-tutorial-on-engaging-in-dialogue-through-mozilla-thunderbirds-chat-functionality/"><u>The Ultimate Tutorial on Engaging in Dialogue Through Mozilla Thunderbird's Chat Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-win11-guide-to-crafting-extractable-sfxs/"><u>The Win11 Guide to Crafting Extractable SFXs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-4-innovations-microsoft-paint-revamped/"><u>Top 4 Innovations: Microsoft Paint Revamped</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uniting-computers-and-phones-with-samsung-flow/"><u>Uniting Computers & Phones with Samsung Flow</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-profile-management-new-folder-titles/"><u>Win 11 Profile Management: New Folder Titles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-timeline-6-ways-to-get-your-systems-timer-running/"><u>Windows Timeline: 6 Ways to Get Your System's Timer Running</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-strategies-for-loaded-screen-woes-lol/"><u>Winning Strategies for Loaded-Screen Woes (LOL)</u></a></li>
</ul></div>
