---
title: Steps to Resolve Windows Error Code 0X80070570 for Corrupted Items
date: 2024-08-16T02:25:57.432Z
updated: 2024-08-17T02:25:57.432Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Resolve Windows Error Code 0X80070570 for Corrupted Items
excerpt: This Article Describes Steps to Resolve Windows Error Code 0X80070570 for Corrupted Items
keywords: Fixing Error Code 0X80070570,Resolving Windows Error 0X80070570,Error 0X80070570 Correction Steps,Troubleshoot 0X80070570 Windows,Cure 0X80070570 File Issue,Fixing Windows 0X70 Error,Overcoming 0X80070570 Files Problem
thumbnail: https://thmb.techidaily.com/095ce3d3eacef166f46f59459d5ef71a92a706285f3160a9b70eb170ae6406f1.jpg
---

## Steps to Resolve Windows Error Code 0X80070570 for Corrupted Items

 Error 0x80070570 is a Windows issue that sometimes pops up when you try to delete files on external hard drives. This error also occurs when users try to transfer files between PCs and external drives. The error 0x80070570 message says, “The file or directory is corrupted and unreadable.”

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

## 1\. Repair System Files With an SFC Scan

 Some users have confirmed repairing system files resolved error 0x80070570 on their PCs. System File Checker is a command-line tool with which you can check for and repair corrupted system files that might be causing file operation issues. Check out our guide to [utilizing System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) for details about how to run an SFC scan within the Command Prompt.

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command2.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## 2\. Utilize the Check Disk Tool

 Drive file system issues often cause error 0x80070570\. The most widely confirmed solution for that error is to run a CHKDSK scan of the drive you can’t delete files on or transfer files to. The CHKDSK tool can repair file system errors on the drive it’s scanning.

![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)

 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Perform a Startup Repair

 This resolution is recommended if error 0x80070570 occurs when trying to delete files on the C: hard drive or transfer them there. Startup Repair is primarily a utility for fixing Windows startup issues. However, that tool can remedy corrupted system files and C: drive issues. This is how you can utilize Startup Repair:

1. First, [bring up the Advanced Startup Options menu](https://www.makeuseof.com/windows-11-access-advanced-startup-options/) via the Settings app.
2. Select **Startup Repair** within the Advanced options menu.  
![The Start-up Repair option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-up-repair.jpg)
3. Next, select your Windows user account.
4. Input your user account password.
5. Select **Continue** to initiate the repair.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Format an External Drive

 Formatting an affected external drive to which you can’t transfer files or delete data because of error 0x80070570 is suggested only as a last resort. Applying this potential fix will wipe all data on the drive, so do not format your PC’s C: drive. However, some users have confirmed formatting affected external drives fixes error 0x80070570\.

![The format drive utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-format-tool.jpg)

 You can format an external drive with the Windows Disk Management utility or in File Explorer. Connect the drive to your PC, and then follow the steps in this guide on [how to format a USB drive](https://www.makeuseof.com/tag/format-usb-drive/) to do this within File Explorer.

## Perform the Required File Operations Again on Windows

 The potential error 0x80070570 solutions covered here have worked for many Windows 11/10 users. Repairing drive errors with the CHKDSK tool usually does the trick. You could also utilize a third-party utility like Hard Disk Sentinel and HDDScan to check for and repair drive issues. With error 0x80070570 fixed, you can copy or delete files as required again.

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-becoming-an-expert-at-yt-studio-navigation/"><u>[New] 2024 Approved  Becoming an Expert at YT Studio Navigation</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-decoding-the-secret-of-highest-quality-youtube-mp3s/"><u>[New] 2024 Approved  Decoding the Secret of Highest Quality YouTube MP3s</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-achieving-virality-on-youtube-essential-steps-demystified/"><u>[New] Achieving Virality on YouTube  Essential Steps Demystified</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-visual-victory-apple-and-android-highlight-covers/"><u>[New] In 2024, Visual Victory  Apple & Android Highlight Covers</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-capture-clarity-enjoy-convenience-with-our-top-5-recorder-recommendations-for-2024/"><u>[Updated] Capture Clarity, Enjoy Convenience with Our Top 5 Recorder Recommendations for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-optimal-stabilization-for-mirrorless-with-gimbals/"><u>2024 Approved  Optimal Stabilization for Mirrorless with Gimbals</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-the-role-of-b-roll-in-professional-editing/"><u>2024 Approved  The Role of B Roll in Professional Editing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-steps-to-disable-automatic-updates-in-windows/"><u>5 Steps To Disable Automatic Updates in Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-vivo-y27-4g-drfone-by-drfone-virtual-android/"><u>9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Vivo Y27 4G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-blackout-in-widows-remote-desktop-connection/"><u>Addressing Blackout in Widows Remote Desktop Connection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-missing-history-on-windows-runs/"><u>Addressing Missing History on Windows Runs</u></a></li>
<li><a href="https://extra-hints.techidaily.com/beacon-of-ringtone-richness-online-for-2024/"><u>Beacon of Ringtone Richness Online for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/best-practices-for-configuring-and-measuring-fb-instream-ads-for-2024/"><u>Best Practices for Configuring and Measuring FB Instream Ads for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/boosting-your-youtube-views-a-strategy-guide-for-2024/"><u>Boosting Your YouTube Views  A Strategy Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridge-the-gap-quick-fixes-for-slow-windows-app-connections/"><u>Bridge the Gap: Quick Fixes for Slow Windows App Connections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/complete-guide-to-disabling-the-windows-subsystem/"><u>Complete Guide to Disabling the Windows Subsystem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cure-for-non-booting-windows-hiberflattening/"><u>Cure for Non-Booting Windows HiberFlattening</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dims-masterclass-restoring-and-repairing-win11-images/"><u>DIMS Masterclass: Restoring and Repairing Win11 Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-strategies-to-control-external-hard-drive-usage/"><u>Effective Strategies to Control External Hard Drive Usage</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/expert-insights-on-the-cost-effective-samsung-galaxy-s10e-quality-meets-portability/"><u>Expert Insights on the Cost-Effective Samsung Galaxy S10e: Quality Meets Portability</u></a></li>
<li><a href="https://win11-tips.techidaily.com/focusing-gpo-application-one-user-approach-for-windows-1111/"><u>Focusing GPO Application: One-User Approach for Windows 11/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harnessing-the-potential-of-diskusage-for-in-depth-drive-space-examination/"><u>Harnessing the Potential of DiskUsage for In-Depth Drive Space Examination</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-google-frp-on-zte-by-drfone-android-unlock-remove-google-frp/"><u>How To Bypass Google FRP on ZTE</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-detect-and-remove-spyware-on-tecno-spark-10c-drfone-by-drfone-virtual-android/"><u>How to Detect and Remove Spyware on Tecno Spark 10C? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-download-and-install-msixbundle-and-appxappxbundle-files-from-the-microsoft-store/"><u>How to Download and Install Msixbundle and Appx/Appxbundle Files From the Microsoft Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-directx-setup-couldnt-download-the-file-error-on-windows/"><u>How to Fix the “DirectX Setup Couldn’t Download the File” Error on Windows</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-harnessing-social-potential-a-compreenasculated-blueprint-for-smm-mastery/"><u>In 2024, Harnessing Social Potential  A Compreenasculated Blueprint for SMM Mastery</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-ultimate-guide-to-catch-the-regional-located-pokemon-for-vivo-s18-drfone-by-drfone-virtual-android/"><u>In 2024, Ultimate Guide to Catch the Regional-Located Pokemon For Vivo S18 | Dr.fone</u></a></li>
<li><a href="https://ai-video.techidaily.com/in-2024-ultimate-guide-to-translating-youtube-videos-without-cc/"><u>In 2024, Ultimate Guide to Translating YouTube Videos Without CC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-folder-access-inserting-into-windows-11-context-menu/"><u>Mastering Folder Access: Inserting Into Window's 11 Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-installation-of-google-play-in-w11/"><u>Mastering the Installation of Google Play in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-security-running-as-administrator/"><u>Navigating Windows Security: Running As Administrator</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-fcp-audio-editing-essentials-a-step-by-step-guide/"><u>New 2024 Approved FCP Audio Editing Essentials A Step-by-Step Guide</u></a></li>
<li><a href="https://extra-information.techidaily.com/pop-culture-with-a-click-using-kinemaster/"><u>Pop Culture with a Click  Using KineMaster</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-reviving-non-functioning-reading-aloud-in-word-2016plus/"><u>Quick Guide to Reviving Non-Functioning Reading Aloud in Word 2016+</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-reset-windows-paperwork-service/"><u>Quick Reset Windows' Paperwork Service</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/recommended-best-applications-for-mirroring-your-tecno-phantom-v-fold-screen-drfone-by-drfone-android/"><u>Recommended Best Applications for Mirroring Your Tecno Phantom V Fold Screen | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-non-active-vss-service-states/"><u>Restoring Non-Active VSS Service States</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simple-steps-to-record-clear-sound-in-windows-11/"><u>Simple Steps to Record Clear Sound in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-typing-solutions-for-windows-pcs-7-must-dos/"><u>Speedy Typing Solutions for Windows PCs (#7 Must-Dos)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-keep-lol-playtime-uninterrupted-in-windows/"><u>Strategies to Keep LoL Playtime Uninterrupted in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-troubled-tracker-fixes-for-frozen-torrents/"><u>Tackling the Troubled Tracker: Fixes for Frozen Torrents</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactical-tutorials-for-new-folder-navigation-in-win11/"><u>Tactical Tutorials for New Folder Navigation in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-blackwhite-windows-store-errors/"><u>Troubleshooting Black/White Windows Store Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-copy-pasting-issues-across-chrome-edge-and-firefox-on-win/"><u>Troubleshooting Copy-Pasting Issues Across Chrome, Edge, & Firefox on Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-powershell-errors-with-script-enablement-fixes/"><u>Troubleshooting PowerShell Errors with Script Enablement Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-wows-fatal-issue-in-windows-1111/"><u>Troubleshooting WoW's Fatal Issue in Windows 11/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncharted-errors-the-8-most-crucial-mistakes-for-new-windows-11-users/"><u>Uncharted Errors: The 8 Most Crucial Mistakes for New Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11-bypassing-tpm-with-rufus/"><u>Unlocking Windows 11: Bypassing TPM with Rufus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-the-windows-print-management-tool-and-how-do-you-access-it/"><u>What Is the Windows Print Management Tool, and How Do You Access It?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-10s-guide-to-effortlessly-merge-data/"><u>Win 10'S Guide to Effortlessly Merge Data</u></a></li>
</ul></div>
