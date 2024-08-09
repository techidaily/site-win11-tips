---
title: "Addressing Windows Update Disruption: X712 Fiasco"
date: 2024-08-08T10:55:27.952Z
updated: 2024-08-09T10:55:27.952Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Addressing Windows Update Disruption: X712 Fiasco"
excerpt: "This Article Describes Addressing Windows Update Disruption: X712 Fiasco"
keywords: WinUpdateFiasco Fixes,XP712 Security Concerns,Uptime Restoration Guide,Safe Windows Update,X712 Troubleshooting Steps,Updater Stability Issues,Secure Windows Patching
thumbnail: https://thmb.techidaily.com/98061f90f0702266772c41039bf7505ea26afb88709675b4845f86d9c07123c1.jpg
---

## Addressing Windows Update Disruption: X712 Fiasco

 Microsoft frequently releases updates to fix security issues, and introduce new features and stability to the Windows OS. But not all updates install smoothly on your system and trigger an error code while doing so. Many users share their woes with the 0x80073712 update error code with the error message that some files are missing from the system.

 If you experience the same update error code and are unable to install the latest Windows update, don’t worry. We will list out all the possible fixes that you can try to resolve the 0x80073712 error code.

## 1\. Use the Windows Troubleshooter

 Before jumping onto major fixes, leverage the in-built troubleshooter on Windows 10 and 11\. It tries to find out existing problems with Windows Update and try to fix them. Repeat the following steps:

1. Press**Win + I** to launch the settings app.
2. Navigate to the**System > Troubleshoot** section.
3. Click on the**Other Troubleshooter** option.
4. Locate the**Windows Update troubleshooter** option from the list.
5. Then, click on the**Run** button to start the troubleshooter.  
![Windows Update Troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-update-troubleshooter.jpg)
6. Wait for the Windows Update troubleshooter to identify problems. Click on the**Next** button.
7. Close the troubleshooter window and reattempt the Windows update installation.

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->
## 2\. Perform a Complete system shutdown

 Windows OS enables the fast startup option by default. Even if you restart your system, or shut it down, it preserves the system state using hibernate. So, you need to perform a complete system shutdown and then power it back on to close and restart all background services.

Here’s how to perform a complete system shutdown:

1. Press**Win + X** to launch the Power user menu. Scroll down and select the**Terminal (Admin)** option from the list.
2. The Terminal app will open with an instance of a command prompt with admin privileges.
3. Type the**shutdown /s /f /t 0** command and press the**enter** key.
4. Your system will power off. It will take a tad bit longer that a normal shutdown procedure.
5. Now, restart your Windows PC and try to install the Windows update.

## 3\. Restart Windows Update services

 Windows Update uses a bunch of background services to fetch and download updates. If these services aren’t running automatically, you will encounter an error. These include**Windows Update Service** ,**Windows Installer Service** ,**Cryptographic Services** , and**Background Intelligent Transfer Service** .

Repeat the following steps to start the necessary services:

1. Press**Win + R** to [launch the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**services.msc** and press the**enter** key
2. Services utility will launch on your system. Now locate the**Background Intelligent Transfer** service in the list.
3. Double-click on the BITS service to open the**properties** window. Set the**Startup Type** as**Automatic** and click on the**Apply** button.  
![Disabling Windows Update Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disabling-windows-update-services.jpg)
4. Click on the**OK** button and close the Properties windows. Now, right-click on the service and select the**Start** option from the context menu.
5. Similarly, set all the services as automatic and manually start them.
6. **Close** the Services window and reattempt the Windows update.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
## 4\. Run the Disk Cleanup Tool

 Disk Cleanup can wipe the delivery optimization files, old Windows update files as well as the Temp folder. If files in these locations are corrupted, they can interfere with the normal update process. Here’s how to run disk cleanup on Windows:

1. Press**Win + S** to open the search utility in Windows.
2. Type**cleanmgr.exe** and press the enter key to open the Disk Cleanup tool.
3. It will select the system drive (C) by default. Click on the**OK** button to continue.
4. Select the checkboxes of files that you want the tool to clean up. Then, click on the**Clean up system files** button.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
![Disk Cleanup App in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disk-cleanup-app-in-windows-11.jpg)
5. Disk Cleanup will close and redirect you to pick the appropriate drive. Click on the**OK** button.
6. Lastly, click on the**Delete files** button.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Rename the SoftwareDistribution Folder

 Windows update stores its content in the SoftwareDistribution folder. Since it is located inside the Windows folder in the C drive, you mustn’t delete it. Instead, you can rename the folder to force the update service to recreate the folder again.

Repeat the following steps:

1. Open the Start menu and search CMD. Press Ctrl + Shift + Enter to open the command prompt with admin privileges.
2. Type the following commands to stop all the Windows update-related services:  
 net stop wuauserv net stop cryptSvc net stop bits net stop msiserver  
<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Rename the SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/rename-the-softwaredistribution-folder.jpg)
3. Once these services stop running, type**cls** in the command prompt windows. Then enter the following commands:  
 ren C:\\Windows\\SoftwareDistribution SoftwareDistribution.old ren C:\\Windows\\System32\\catroot2 Catroot2.old  
![Rename the SoftwareDistribution Folder 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/rename-the-softwaredistribution-folder-2.jpg)
4. Both the above commands rename the**SoftwareDistribution** folder and**Catroot2** folder.
5. Now, you need to restart all the Windows services you stopped in step 3\. Enter the following commands:  
net start wuauserv net start cryptSvc net start bits net start msiserver  
![Rename the SoftwareDistribution Folder 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/rename-the-softwaredistribution-folder-3.jpg)
6. Lastly,**restart** your system and visit the following folder location:**C:\\Windows** . You will notice that there is a new SoftwareDistribution folder in that location.
7. Open the Windows update in Settings and try to download and install updates.

## 6\. Delete the Pending.xml file

 The pending.xml file contains all the pending Windows update tasks. Oftentimes, it can interfere with installing new updates because there are already multiple incomplete old update tasks. So, you must delete this file and proceed with the Windows update.

Retrace the following steps to delete the pending.xml file:

1. Log in with an administrator account. Then, press**Win + E** to launch the file explorer.
2. Navigate to the**C:\\Windows\\WinSxS** folder.
3. Locate the**pending.xml** in the**WinSxS** folder and right-click on it.
4. Press the**Shift** key and click on the**Delete** option.
5. Restart your computer.

<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
## 7\. Manually Download Windows Updates

 If you are unable to download a specific Windows update using the Settings page, consider a direct download and install approach. Visit the Microsoft Update Catalog website and search for the KB update you want to download. However, you first have to check the corresponding update number which is failing to download and install on your system.

<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->
![Manually Download Windows Updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/manually-download-windows-updates.jpg)

## 8\. Reset Windows

 Resetting Windows is the last resort you have if none of the above methods work in your favor. However, before learning [how to perform a Windows system reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) , try out general fixes such as [SFC, CHKDSK, and DISM](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) scans on your system. Also,[disable Windows Defender](https://www.makeuseof.com/how-to-turn-off-windows-defender/) and try updating your system before hitting the reset button.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
## Update Windows Without Hiccups

 Windows updates can be tricky to install sometimes. Use the inbuilt troubleshooter to identify and fix problems. After that restart, all the crucial Windows update services and run the Disk Cleanup tool. If everything else fails, try doing a manual update or performing a Windows Reset.


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
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-effortless-broadcast-blending-a-guide-to-obspluszoom/"><u>[New] 2024 Approved  Effortless Broadcast Blending  A Guide to OBS+Zoom</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-enhancing-video-discoverability-with-smart-thumbnails/"><u>[New] 2024 Approved  Enhancing Video Discoverability with Smart Thumbnails</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-instagram-vids-to-mp3s-a-noobs-guide-revealed/"><u>[New] In 2024, Instagram Vids to MP3s - A Noob's Guide Revealed</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-social-media-tip-post-youtube-content-dont-twit-for-2024/"><u>[New] Social Media Tip  Post YouTube Content, Don't Twit for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-breaking-barriers-masterful-techniques-for-photosvideos-in-win11/"><u>[Updated] Breaking Barriers  Masterful Techniques for Photos/Videos in Win11</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-instagram-enterprise-account-the-complete-guidebook-for-2024/"><u>[Updated] Instagram Enterprise Account  The Complete Guidebook for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-mastering-the-art-of-selecting-free-music-for-videos/"><u>[Updated] Mastering the Art of Selecting Free Music for Videos</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-no-splurge-audio-devices-for-yt-beginners-for-2024/"><u>[Updated] No-Splurge Audio Devices for YT Beginners for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-best-budget-friendly-high-quality-ae-templates/"><u>2024 Approved  Best Budget-Friendly, High-Quality AE Templates</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-concurrent-display-archiving/"><u>2024 Approved  Concurrent Display Archiving</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoidance-tactics-skirting-windows-account-sign-ins/"><u>Avoidance Tactics: Skirting Windows Account Sign-Ins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-integrated-video-on-windows-1011/"><u>Bypassing Integrated Video on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-windows-11-boot-tracks-step-by-step-guide/"><u>Clearing Windows 11 Boot Tracks: Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combat-unwanted-scrolling-windows-edition/"><u>Combat Unwanted Scrolling: Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-win11s-sticky-notes-with-ease/"><u>Conquer Win11's Sticky Notes with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-deep-the-ultimate-win11-mouse-properties-guide/"><u>Dive Deep: The Ultimate Win11 Mouse Properties Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/drive-clearance-ways-keeping-files-on-win11-safe-max-156-chars/"><u>Drive Clearance Ways: Keeping Files on Win11 Safe (Max 156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-windows-11s-rounded-edges/"><u>Eliminate Windows 11'S Rounded Edges</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/enhancing-smooth-playback-stop-frame-gaps-in-obs/"><u>Enhancing Smooth Playback  Stop Frame Gaps in OBS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/everyday-annoyances-windows-11-review-highlights/"><u>Everyday Annoyances: Windows 11 Review Highlights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-windows-1011-climate-choices/"><u>Exclusive Windows 10/11 Climate Choices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/getting-the-best-bargains-on-essential-windows-11-codes/"><u>Getting the Best Bargains on Essential Windows 11 Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-faster-your-windows-edge-fix-win10-w11/"><u>How to Faster Your Windows Edge: Fix (Win10, W11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-windows-to-run-this-application-you-must-install-net-core-error/"><u>How to Fix the Windows “To Run This Application, You Must Install .NET Core” Error</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-3utools-virtual-location-not-working-on-oppo-find-n3-fix-now-drfone-by-drfone-virtual-android/"><u>In 2024, 3uTools Virtual Location Not Working On Oppo Find N3? Fix Now | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-track-imei-number-of-xiaomi-13-ultra-through-google-earth-by-drfone-android/"><u>In 2024, How To Track IMEI Number Of Xiaomi 13 Ultra Through Google Earth?</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-ispoofer-is-not-working-on-lenovo-thinkphone-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, iSpoofer is not working On Lenovo ThinkPhone? Fixed | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlock-itel-p55-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>In 2024, Unlock Itel P55 Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keyboard-keyscalyping-restore-your-arrows-now/"><u>Keyboard Keyscalyping? Restore Your Arrows Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-voice-commands-xbox-and-pc-synergy/"><u>Mastering Voice Commands: Xbox & PC Synergy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-msvcr120dll-missing-message-on-desktops/"><u>Navigating 'Msvcr120_dll' Missing Message on Desktops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/peak-potential-identifying-the-top-pc-boosters-for-windows/"><u>Peak Potential: Identifying the Top PC Boosters for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-in-game-audio-output-solving-windows-issues-in-valorant/"><u>Realigning In-Game Audio Output: Solving Windows Issues in Valorant</u></a></li>
<li><a href="https://network-issues.techidaily.com/rectifying-windows-10-hologram-error/"><u>Rectifying Windows 10 Hologram Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-c0000005-error-on-your-pcs-operating-system/"><u>Remedy for C0000005 Error on Your PC's Operating System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-dormant-devices-with-synapse-on-windows-11/"><u>Reviving Dormant Devices with Synapse on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailored-windows-trick-sticky-notes-open-up-with-system-boot/"><u>Tailored Windows Trick: Sticky Notes Open-Up With System Boot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-minimizing-disruptions-in-windows-updates/"><u>The Art of Minimizing Disruptions in Windows Updates</u></a></li>
<li><a href="https://screen-recording.techidaily.com/top-6-strategies-for-mc-village-housebuilding-for-2024/"><u>Top 6 Strategies for MC Village Housebuilding for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-reasons-to-choose-win11-over-apples-macos/"><u>Top Reasons to Choose Win11 Over Apple's macOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbocharge-windows-11-boot-speed-heres-how/"><u>Turbocharge Windows 11 Boot Speed – Here’s How</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/tutorial-to-change-samsung-galaxy-a14-4g-imei-without-root-a-comprehensive-guide-by-drfone-android/"><u>Tutorial to Change Samsung Galaxy A14 4G IMEI without Root A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-your-windows-devices-microsoft-store-error-code-x800704cf/"><u>Unlocking Your Windows Devices: Microsoft Store Error Code X800704CF</u></a></li>
<li><a href="https://hardware-help.techidaily.com/update-brother-mfc-j480dw-printer-drivers-on-your-windows-pc/"><u>Update Brother MFC J480DW Printer Drivers on Your Windows PC</u></a></li>
</ul></div>
