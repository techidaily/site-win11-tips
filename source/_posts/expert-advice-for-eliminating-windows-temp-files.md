---
title: Expert Advice for Eliminating Windows' Temp Files
date: 2024-08-16T02:28:28.684Z
updated: 2024-08-17T02:28:28.684Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Expert Advice for Eliminating Windows' Temp Files
excerpt: This Article Describes Expert Advice for Eliminating Windows' Temp Files
keywords: Clear Win Temp Files,Optimize PC Performance,Remove System Junk,Cleanup Windows Cache,Delete Temp Data Pro,Speed Up Windows,Free Up Disk Space
thumbnail: https://thmb.techidaily.com/e8d273b848143c340000d0079f7c83e7faa1151d78bf679fca424eb3bb1ead67.jpg
---

## Expert Advice for Eliminating Windows' Temp Files

 Temporary files, as the name implies, aren’t meant to stick around on your Windows computer forever. Although Windows makes it simple to delete temporary files, there can be times when these files refuse to leave.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

## 1\. Use the Disk Cleanup Tool

[Windows offers several options for clearing temporary files](http://www.makeuseof.com/windows-11-delete-temporary-files/) on your PC. If you are unable to delete temporary files via the Settings app or File Explorer, try using the Disk Cleanup tool instead.

 Here are the steps you can follow:

1. Press **Win + S** to access the search menu.
2. Type **disk cleanup** in the box and press **Enter**.
3. Use the drop-down menu to select the drive from which you want to clear temporary files.
4. Click **OK**.
5. Under **Files to delete**, use the checkboxes to select the files you want to remove.
6. Click **OK** to proceed.
7. Click the **Delete Files** to confirm.  
![Delete Temp Files Using Disk Cleanup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-disk-cleanup.jpg)

 Wait for a few moments until the Disk Cleanup tool clears all the temporary files.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Use Command Prompt

 If the Disk Cleanup utility fails to delete some or all of the temporary files on Windows, you can try using the Command Prompt instead. Don’t worry, the process isn’t as complex as it might sound.

 Follow these steps to continue:

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt appears.
3. Copy and paste the following command into the console and hit **Enter**.  
del /q /f /s %temp%\* && del /s /q C:\Windows\temp\*  
![Delete Temp Files Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->

 Wait for the above command to run and delete the temporary files.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Empty the SoftwareDistribution Folder

 Windows saves all the downloaded update files in the SoftwareDistribution folder before installing them. If a [Windows system update gets stuck](https://www.makeuseof.com/tag/windows-update-stuck/), the OS will not delete the temporary files associated with it.

 To fix this, you can try emptying the SoftwareDistribution folder manually using these steps:

1. Press **Win + S** to open the search menu.
2. Type **services** in the box and press **Enter**.
3. In the Services window, locate the **Windows Update** service. Right-click on it and select **Stop**.
4. Press **Win + R** to open the Run dialog box.
5. Type the following path in the text field and hit **Enter**.  
C:\Windows\SoftwareDistribution\Download
6. In the File Explorer window, press **Ctrl + A** to select all the files and click the **trash icon** at the top to delete them.
7. Return to the Services window, right-click on the **Windows Update** service, and select **Start**.  
![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/clear-softwaredistribution-folder.jpg)

 If you run into issues while emptying the SoftwareDistribution folder, you can [force delete files in Windows](https://www.makeuseof.com/windows-11-delete-stubborn-files/) using Command Prompt or a third-party tool.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
## 4\. Edit Registry Files

 By default, the Disk Cleanup utility does not delete temporary files that are less than seven days old. This is because Windows marks these files as active. However, if you want to delete all the temporary files, regardless of their age, you can make changes to the Windows Registry.

 Since editing registry files is slightly risky, make sure to [back up all registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) as a precaution. Once done, follow these steps to edit registry files:

1. Press **Win + R** to open the Run dialog box.
2. Type **regedit** in the box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer > VolumeCaches > Temporary Files**.
5. In the right pane, double-click the **LastAccess** key.
6. Enter **0** in the Value data field.
7. Click **OK**.  
![Edit DWORD in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-dword-in-registry.jpg)

 Restart your PC after this and try to delete temporary files once again.

<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## 5\. Boot Into Safe Mode

 It's possible that a third-party program or background service is preventing Windows from erasing temporary files on your system. Booting your PC in safe mode can help you avoid any interference, as Windows will only run with essential drivers and services.

 Use one of the many ways to [boot into safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) and try to delete temporary files one more time.

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
## Get Rid of Temporary Files on Windows

 Clearing temporary files is a great way to free up storage space without deleting any of your apps or important data.

 We hope that one of the above tips was helpful and you were able to delete the temporary files without any problems.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-information.techidaily.com/new-360-camera-rigsmounts-for-vr-video-production/"><u>[New] 360 Camera Rigs/Mounts for VR Video Production</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-master-the-art-of-illuminating-dark-images-on-iphone/"><u>[New] Master the Art of Illuminating Dark Images on Iphone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-the-key-to-captivating-audiences-crafting-fb-slideshows/"><u>[New] The Key to Captivating Audiences  Crafting FB Slideshows</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-add-flair-with-gifs-on-snapchat-a-comprehensive-walkthrough/"><u>[Updated] 2024 Approved  Add Flair with GIFs on Snapchat – A Comprehensive Walkthrough</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-beginners-guide-to-interpreting-facebook-metrics/"><u>[Updated] 2024 Approved  Beginner's Guide to Interpreting Facebook Metrics</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-channel-alchemy-turning-viewers-into-believers/"><u>[Updated] Channel Alchemy  Turning Viewers Into Believers</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-in-2024-navigating-through-windows-11s-new-frontier/"><u>[Updated] In 2024, Navigating Through Windows 11'S New Frontier</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-strategic-first-impressions-the-unpacking-edge/"><u>[Updated] Strategic First Impressions  The Unpacking Edge</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-comprehensive-visuals-what-sets-360-apart/"><u>2024 Approved  Comprehensive Visuals  What Sets 360° Apart?</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-photo-magic-weaving-text-into-your-imagery-journey/"><u>2024 Approved  Photo Magic  Weaving Text Into Your Imagery Journey</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-premier-free-android-recording-apps-no-ads/"><u>2024 Approved  Premier Free Android Recording Apps (No Ads)</u></a></li>
<li><a href="https://howto.techidaily.com/9-quick-fixes-to-unfortunately-touchwiz-has-stopped-of-samsung-galaxy-a05s-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Quick Fixes to Unfortunately TouchWiz has stopped Of Samsung Galaxy A05s | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-window-into-evolution-noteworthy-windows-11-file-enhancements/"><u>A Window Into Evolution: Noteworthy Windows 11 File Enhancements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-11-reactivating-deactivated-voice-command/"><u>Addressing Windows 11: Reactivating Deactivated Voice Command</u></a></li>
<li><a href="https://games-able.techidaily.com/amds-fsr-3-launch-challenger-to-nvidias-dynamic-super-sampling/"><u>AMD's FSR 3 Launch: Challenger to NVIDIA's Dynamic Super Sampling?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-the-variance-in-procedures-for-local-and-remote-windows-reinstallations/"><u>Analyzing the Variance in Procedures for Local and Remote Windows Reinstallations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-the-hurdles-of-xbox-game-pass-error-code-0-essential-tips-for-windows-11-users/"><u>Avoiding the Hurdles of Xbox Game Pass Error Code 0: Essential Tips for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-windows-11-visuality-with-app-sizing/"><u>Boosting Windows 11 Visuality with App Sizing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-line-magic-automating-archive-creation-in-windows/"><u>Command Line Magic: Automating Archive Creation in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-the-new-os-build-a-focused-and-effective-windows-11-boot-drive-in-three-ways/"><u>Conquer the New OS – Build a Focused and Effective Windows 11 Boot Drive in Three Ways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-fatal-javascript-issue-with-ease-on-win-11-discord/"><u>Conquering Fatal Javascript Issue with Ease on Win 11 Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correct-camera-omission-from-windows-dm-display/"><u>Correct Camera Omission From Windows' DM Display</u></a></li>
<li><a href="https://buynow-info.techidaily.com/cost-analysis-and-performance-review-nikon-sb-700/"><u>Cost Analysis and Performance Review: Nikon SB-700</u></a></li>
<li><a href="https://extra-information.techidaily.com/creative-cuts-unlocking-tiktoks-potential/"><u>Creative Cuts  Unlocking TikTok's Potential</u></a></li>
<li><a href="https://facebook.techidaily.com/digital-silence-strikes-whatsapp-and-instagram-downed/"><u>Digital Silence Strikes: WhatsApp & Instagram Downed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-fixes-for-the-v22h2-update-dilemma-on-win11-os/"><u>Efficient Fixes for the V22H2 Update Dilemma on Win11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-setup-ensure-your-pcs-microphone-and-webcam/"><u>Efficient Setup: Ensure Your PC's Microphone & Webcam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-webbrowsers-for-lighter-system-resource-use-on-os-x-windows-chromeos/"><u>Efficient Webbrowsers for Lighter System Resource Use on OS X, Windows, ChromeOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tools-for-shaping-windows-esd-files-into-iso/"><u>Essential Tools for Shaping Windows' ESD Files Into ISO</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-fixing-windows-error-code-0xc00000f-instantly/"><u>Guidelines to Fixing Windows Error Code 0Xc00000f Instantly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guides-to-resolve-windows-11-search-tool-errors/"><u>Guides to Resolve Windows 11 Search Tool Errors</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-fix-mfc42ddll-missing-or-not-found-errors/"><u>How to Fix Mfc42d.dll Missing or Not Found Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-this-file-cannot-be-previewed-error-in-outlook-for-windows/"><u>How to Fix the This File Cannot Be Previewed Error in Outlook for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-highlight-the-mouse-cursor-in-windows-11-and-11/"><u>How to Highlight the Mouse Cursor in Windows 11 & 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-6-to-others-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 6 To Others devices? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-use-an-additional-monitor-without-gui-chipset/"><u>How to Use an Additional Monitor Without GUI Chipset</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ifttt-and-microsoft-to-dot-synergy-explained/"><u>IFTTT & Microsoft To-Dot Synergy Explained</u></a></li>
<li><a href="https://tech-hub.techidaily.com/immediate-use-dive-into-8-tailored-gpt-experiences/"><u>Immediate Use: Dive Into 8 Tailored GPT Experiences</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-for-people-wanting-to-mock-gps-on-honor-magic-5-pro-devices-drfone-by-drfone-virtual/"><u>In 2024, For People Wanting to Mock GPS on Honor Magic 5 Pro Devices | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-getting-the-pokemon-go-gps-signal-not-found-11-error-in-motorola-defy-2-drfone-by-drfone-virtual/"><u>In 2024, Getting the Pokemon Go GPS Signal Not Found 11 Error in Motorola Defy 2 | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-get-and-use-pokemon-go-promo-codes-on-honor-magic-vs-2-drfone-by-drfone-virtual-android/"><u>In 2024, How to Get and Use Pokemon Go Promo Codes On Honor Magic Vs 2 | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-unlink-apple-id-from-apple-iphone-se-2022-by-drfone-ios/"><u>In 2024, How To Unlink Apple ID From Apple iPhone SE (2022)</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-insta-prowess-guide-the-9-secrets-behind-top-posters-success/"><u>In 2024, Insta Prowess Guide  The 9 Secrets Behind Top Posters' Success</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-muting-unwanted-noise-obs-audio-solution/"><u>In 2024, Muting Unwanted Noise  OBS Audio Solution</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-phone-speaker-transcriber-voice-logging-iphone-24/"><u>In 2024, Phone Speaker Transcriber  Voice Logging (iPhone '24)</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-reasons-why-pokemon-gps-does-not-work-on-nokia-c210-drfone-by-drfone-virtual-android/"><u>In 2024, Reasons why Pokémon GPS does not Work On Nokia C210? | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-depth-analysis-of-lg-k51-stunning-design-compromised-by-sluggish-performance/"><u>In-Depth Analysis of LG K51: Stunning Design Compromised by Sluggish Performance</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/iphone-vs-samsung-a-battle-of-tech-giants-to-find-your-perfect-phone-match/"><u>IPhone vs Samsung: A Battle of Tech Giants to Find Your Perfect Phone Match</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-restoring-functionality-fix-media-on-win11/"><u>Mastering the Art of Restoring Functionality: Fix Media on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-for-troubleshooting-failed-capture-on-win11/"><u>Methods for Troubleshooting Failed Capture on Win11</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-top-online-video-editing-tools-for-vertical-content/"><u>New In 2024, Top Online Video Editing Tools for Vertical Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-isarcextract-error-in-windows-11-updates/"><u>Overcoming ISArcExtract Error in Windows 11 Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-virtualbox-usb-connection-issue-on-windows-devices/"><u>Overcoming VirtualBox USB Connection Issue on Windows Devices</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcoming-windows-10-screen-blankness/"><u>Overcoming Windows 10 Screen Blankness</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-xbox-mic-malfunctions-in-windows-os/"><u>Overcoming Xbox Mic Malfunctions in Windows OS</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/professional-stabilization-tech-for-youtube-content-creators-for-2024/"><u>Professional Stabilization Tech for YouTube Content Creators for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/rank-the-best-comparative-study-of-6-hdmi-21-monitors-for-2024/"><u>Rank the Best  Comparative Study of 6 HDMI 2.1 Monitors for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-your-photos-after-infinix-note-30-has-been-deleted-by-fonelab-android-recover-photos/"><u>Recover your photos after Infinix Note 30 has been deleted.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-command-gain-admin-status/"><u>Regain Command - Gain Admin Status</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rejoining-fall-guys-fixing-connectivity-issues-on-pc/"><u>Rejoining Fall Guys: Fixing Connectivity Issues on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-driver-initialization-failure-in-windows-11/"><u>Solutions for Driver Initialization Failure in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-the-non-verified-error-during-windows-file-installation/"><u>Solving the Non-Verified Error During Windows File Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/storeroom-in-mp60-speed-still-scarce/"><u>Storeroom in MP60, Speed Still Scarce</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-guide-to-managing-win11-applications-via-winget/"><u>The Complete Guide to Managing Win11 Applications via Winget</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-checklist-longer-pins-in-windows-11-and-11/"><u>The Ultimate Checklist: Longer PINs in Windows 11 and 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-intel-unison-for-windows-11-calling/"><u>The Ultimate Guide to Intel Unison for Windows 11 Calling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-the-mechanics-of-windows-11s-compatibility-tool/"><u>Uncovering the Mechanics of Windows 11’S Compatibility Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-microsofts-ai-assistive-functions/"><u>Understanding Microsoft's AI Assistive Functions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11-display-options-with-these-10-tips/"><u>Unlocking Windows 11 Display Options with These 10 Tips</u></a></li>
<li><a href="https://article-helps.techidaily.com/unveiling-lightroom-for-android-a-complete-guide/"><u>Unveiling Lightroom for Android  A Complete Guide</u></a></li>
</ul></div>
