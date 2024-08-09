---
title: "Fixing System Failures: A Guide to Repairing FS in Win11"
date: 2024-08-08T11:01:44.655Z
updated: 2024-08-09T11:01:44.655Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Fixing System Failures: A Guide to Repairing FS in Win11"
excerpt: "This Article Describes Fixing System Failures: A Guide to Repairing FS in Win11"
keywords: Fix System Win11,Win11 Stability,FS Issue Resolution,Troubleshooting FS,Win11 Repair Guide,Error Correction Win11,Software Failure Fixes
thumbnail: https://thmb.techidaily.com/6060180ff020afbbd02ae1895cf9d82d0058a11f9344fe92d8db0b4a31855d9f.JPG
---

## Fixing System Failures: A Guide to Repairing FS in Win11

 A file system error can occur in Windows 10 and 11 when you try to open files or Microsoft Store apps. When such an error occurs, a message pops up that says, “File system error (code).” File system errors have variable error codes like -2147219195, -2147219196, -2147163893, and -1073741521.

 The causes of such errors vary, but the result is much the same. Users can’t open the files or apps for which file system errors arise. These general resolutions can fix a wide variety of file system errors in Windows 10 and 11.

## 1\. Run the SFC and DISM Command Line Tools

 File system errors can often be related to system file corruption. Windows 11 and 10 have the same SFC and DISM command-line tools for repairing system files and Windows system image. Running those utilities in the Command Prompt could feasibly resolve numerous file system errors.

 Our guide on[how to run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to initiate an SFC scan. You can also run a Deployment Image Servicing Management scan in the Command Prompt before or after running the SFC tool. To do so, you’ll need to execute the following command:

`DISM.exe /Online /Cleanup-image /Restorehealth`

## 2\. Scan Your Hard Drive

 Hard drive integrity issues such as bad sectors also cause file system errors to occur in Windows 11/10\. For that reason, scanning your hard drive with the Check Disk tool is a recommended troubleshooting method for file system errors. The Check Disk utility (otherwise CHKDSK) scans for and repairs bad drive sectors detected. This is how you can run CHKDSK in the Command Prompt:

1. Open the file and app search box by pressing the**Win + S** key combination.
2. Select Command Prompt’s**Run as administrator** option within the search results to launch the app with elevated privileges.
3. Then type this command in the Prompt’s window and press**Enter** :  
`chkdsk c: /f /r`
4. You’ll need to press**Y** to schedule the scan for a restart.  
<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The chkdsk command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/chkdsk.jpg)
5. Exit the Command Prompt window.
6. Click**Start > Power** to select**Restart** . The CHKDSK scan will start after the restart.

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Run the Windows Store App Troubleshooter

 If a file system error occurs when you try launching MS Store apps or opening files with them, the Windows Store App troubleshooter might be useful for fixing it. That troubleshooter is there to resolve issues that stop UWP apps from working as they should. These are the steps for opening the Windows Store App troubleshooter:

1. To access Settings, press the**Windows** logo key +**E** keyboard shortcut that opens that app.
2. Scroll down the tab and click a**Troubleshoot navigation** option.
3. Select**Other trouble-shooters** to bring up a list of tools for troubleshooting Windows.
4. Then press the**Run** button for launching the Windows Store App troubleshooter.  
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
![The troubleshooter list in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-store-apps-troubleshooter1.jpg)
5. Apply any suggestions the troubleshooter provides.  
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-store-app-window.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Check That the Windows License Manager Service Is Running

 Some file system errors can arise for opening files with UWP apps when the Windows License Manager service is disabled. That’s a service required for MS Store infrastructure support, and apps downloaded from the store don’t always work right when it’s disabled. This is how you can check that service is enabled and start it if necessary:

1. Bring up the Windows search tool and input**Services** inside its text box.
2. Select**Services** within the search results.
3. Double-click**Windows License Manager Service** to access its properties window.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-services-window2.jpg)
4. Click on the**Startup type** menu to open it and select**Automatic** .  
![The Windows License Manager server window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-license-service-manager.jpg)
5. If the service isn’t running, press**Start** within the properties window.
6. Select**Apply** to save settings for the Windows License Manager Service.
7. Click**OK** to close the Windows License Manager Service Properties window.

## 5\. Reinstall Any Affected App

 This potential solution is more applicable to fixing file system errors that occur for opening specific UWP apps. Reinstalling the app for which the error arises might resolve it in such a scenario. For example, users confirmed reinstalling Microsoft Photos can resolve file system error -2147219196.

 You can remove UWP apps with some of the methods in our guide for uninstalling software in Windows 11\. You can uninstall most apps with the Apps & Features tool in Settings. However, you might need to use the PowerShell method in our guide to remove some pre-installed Windows 11 apps.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Apps & features in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/apps-features-window.jpg)

 When you’ve uninstalled the app, reinstall it from the MS Store. Bring up the Microsoft Store, and input the app’s title in its search box. Then select the app to reinstall in the search results, and click the**Get** button for it.

## 6\. Set Up a New Local User Account on Windows

 File system errors can arise because of user account issues. Such errors might not arise if you set up and utilize a new local user account in Windows 11\. That might not be the most ideal resolution, but you can migrate user files to a newly established account.

 Our guide on[how to fix Windows issues by creating new accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) includes full instructions for how to apply this solution.

<!-- affiliate ads begin -->
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Add account button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-account-button.jpg)

## 7\. Restore Windows to an Earlier Date

 System Restore is a troubleshooting tool that can potentially address various causes for file system errors, be it system file corruption, app conflicts, or recent Windows updates. It fixes many things by restoring Windows to an earlier date (system snapshot). However, restoring Windows to an earlier time will only likely work if you can select a restore point that predates the file system error on your PC.

 To apply this potential solution, read through our guide to[utilizing System Restore and creating restore points](https://www.makeuseof.com/windows-11-create-restore-point/) . Select a restoration date that will take your PC back to a time when there wasn’t a system file error on it. The oldest restore point available is the most likely one to do that.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
![The System Restore tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/system-restore-window.jpg)

 However, restoring Windows to a previous time removes software not installed on the restoration point’s date. So, it’s likely you’ll have to reinstall some apps after rolling back Windows. Clicking**Scan for affected programs** in System Restore provides an overview of software that will be removed for a restore point.

## 8\. Reset Windows

 This final system file error solution is the most drastic of all since it amounts to reinstalling Windows 10 or 11\. Factory resetting restores Windows to a default system state, which can fix many errors caused by registry, third-party software, and system file issues. If you can’t fix a system file error with any other potential fix in this guide, then resetting is the last thing to try.

 Windows 11 and 10 have a Reset this PC tool that makes it easy to factory reset the platform. That tool also includes an option that enables you to keep user files in the process. Our guide on[how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) includes instructions for applying this potential resolution with this tool.

## Get File System Errors Sorted in Windows

 Users often report file system errors on support forums much the same as BSOD (Blue Screen of Death) and missing DLL file issues. You can't ignore them when they stop you from opening important user files or apps. Whatever file system error you need to fix in Windows 10 and 11, you’ll probably be able to resolve it with at least one of the potential resolutions above.

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
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-youtubes-buzzing-titles-roundup-1-8/"><u>[Updated] 2024 Approved  YouTube's Buzzing Titles Roundup  #1-#8</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-conquer-the-crowd-reach-your-goal-of-1k-insta-admirers-monthly-for-2024/"><u>[Updated] Conquer the Crowd  Reach Your Goal of 1K Insta Admirers Monthly for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-vlc-video-recording-performance-study/"><u>[Updated] VLC Video Recording Performance Study</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-motorola-moto-g24-drfone-by-drfone-virtual-android/"><u>15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Motorola Moto G24 | Dr.fone</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-cutting-out-the-clutter-efficient-borders-removal-on-canva/"><u>2024 Approved  Cutting Out the Clutter  Efficient Borders Removal on Canva</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosted-methods-for-graphic-detail-recognition-windows-11/"><u>Boosted Methods for Graphic Detail Recognition, Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-barriers-uniting-pc-and-android-devices/"><u>Breaking Barriers: Uniting PC & Android Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-non-operational-inbox-messages-on-windows/"><u>Breaking Down Non-Operational Inbox Messages on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/circumventing-verify-errors-for-third-party-windows-apps/"><u>Circumventing Verify Errors for Third-Party Windows Apps</u></a></li>
<li><a href="https://buynow-info.techidaily.com/comprehensive-anker-super-bright-flashlight-examination-rugged-illumination-for-adventure-enthusiasts/"><u>Comprehensive Anker Super Bright Flashlight Examination - Rugged Illumination for Adventure Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-symbolic-x-in-windows-file-explorer/"><u>Decoding: The Symbolic X in Windows File Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-new-depths-noteworthy-alterations-in-windows-11s-interface/"><u>Exploring New Depths: Noteworthy Alterations in Windows 11'S Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-apply-local-group-policies-to-a-specific-user-account-in-windows-10-and-11/"><u>How to Apply Local Group Policies to a Specific User Account in Windows 10 and 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-spotify-application-is-not-responding-error-in-windows-11-and-11/"><u>How to Fix the “Spotify Application Is Not Responding” Error in Windows 11 & 11</u></a></li>
<li><a href="https://iphone-location.techidaily.com/how-to-fix-the-apple-iphone-6-plus-gps-not-working-issue-drfone-by-drfone-virtual-ios/"><u>How to Fix the Apple iPhone 6 Plus GPS not Working Issue | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-open-and-use-the-windows-terminal-in-quake-mode/"><u>How to Open and Use the Windows Terminal in Quake Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-quickly-remove-bloatware-from-windows-11/"><u>How to Quickly Remove Bloatware From Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-lost-data-of-iphone-x-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Lost Data of iPhone X? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stop-discord-from-launching-at-startup-and-searching-for-updates-on-windows/"><u>How to Stop Discord From Launching at Startup and Searching for Updates on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-setup-for-bings-ai-assistance-in-windows-11-search-shortcuts/"><u>Instant Setup for Bing's AI Assistance in Windows 11 Search Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-device-connectivity-troubleshooting-on-win-os/"><u>Mastering Device Connectivity Troubleshooting on Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-starting-csgo-in-w11/"><u>Mastering the Art of Starting CS:GO in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-unique-devices-names-erase-in-use-issues-on-pcs/"><u>Mastering Unique Devices Names: Erase 'In Use' Issues on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-efficiency-in-windows-photos-via-shortcuts/"><u>Maximize Efficiency in Windows Photos via Shortcuts</u></a></li>
<li><a href="https://review-topics.techidaily.com/motorola-edgeplus-2023-support-turn-off-screen-lock-by-drfone-android-unlock-android-unlock/"><u>Motorola Edge+ (2023) support - Turn Off Screen Lock.</u></a></li>
<li><a href="https://review-topics.techidaily.com/motorola-moto-g34-5g-won-t-play-mkv-movies-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Motorola Moto G34 5G won’t play MKV movies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-disconnection-issues-with-ea-services-in-win/"><u>Overcoming Disconnection Issues with EA Services in Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-how-to-resolve-windows-11s-nvidia-cp-issue/"><u>Quick Guide: How to Resolve Windows 11'S Nvidia CP Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-jot-down-techniques-in-windows-11-no-apps/"><u>Quick Jot-Down Techniques in Windows 11, No Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restarting-affected-windows-netflix-functions/"><u>Restarting Affected Windows Netflix Functions</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/ride-the-waves-with-top-tier-surf-cameras-for-2024/"><u>Ride the Waves with Top-Tier Surf Cameras for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/routine-steps-to-engage-windows-11s-calculator/"><u>Routine Steps to Engage Windows 11'S Calculator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slaying-windows-beast-error-code-0xc00ce556/"><u>Slaying Window's Beast Error: Code 0xC00CE556</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snowflake-surprises-gifting-windows-games-via-mstore/"><u>Snowflake Surprises: Gifting Windows Games via MSTORE</u></a></li>
<li><a href="https://win11-tips.techidaily.com/surface-laptop-studio-2-explored-creators-dream-device/"><u>Surface Laptop Studio 2 Explored: Creator's Dream Device?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-resolve-win11s-blue-screen-through-these-tips/"><u>Swiftly Resolve Win11's Blue Screen Through These Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-controlling-edges-cpu-usage/"><u>Techniques for Controlling Edge's CPU Usage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-installer-lacks-permissions-in-windows-1110/"><u>Troubleshooting Installer Lacks Permissions in Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-wins-update-failure-on-win11-v22h2/"><u>Troubleshooting Wins Update Failure on Win11 V22H2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-solving-token-access-failure-errors/"><u>Understanding and Solving Token Access Failure Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-meaning-behind-windows-patch-ids/"><u>Unveiling the Meaning Behind Window's Patch IDs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-watchlist-spot-the-red-flags-in-these-7-tasks/"><u>Windows Watchlist: Spot the Red Flags in These 7 Tasks</u></a></li>
</ul></div>
