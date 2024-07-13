---
title: Winning Over Windows Updater Failure X712
date: 2024-07-12T17:43:56.303Z
updated: 2024-07-13T17:43:56.303Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Winning Over Windows Updater Failure X712
excerpt: This Article Describes Winning Over Windows Updater Failure X712
keywords: Win Update Fix,Windows XP712 Failsafe,XP712 Updater Resolve,Updater X712 Success,Overcoming XP Updater Error,XP712 Update Solutions,XP712 Update Failure Fix
thumbnail: https://thmb.techidaily.com/a4fdcd80183f244d65d1a43dcdc553851a248e6cf760faf0d85aa4162c1de5de.jpg
---

## Winning Over Windows Updater Failure X712

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

## 4\. Run the Disk Cleanup Tool

 Disk Cleanup can wipe the delivery optimization files, old Windows update files as well as the Temp folder. If files in these locations are corrupted, they can interfere with the normal update process. Here’s how to run disk cleanup on Windows:

1. Press**Win + S** to open the search utility in Windows.
2. Type**cleanmgr.exe** and press the enter key to open the Disk Cleanup tool.
3. It will select the system drive (C) by default. Click on the**OK** button to continue.
4. Select the checkboxes of files that you want the tool to clean up. Then, click on the**Clean up system files** button.  
![Disk Cleanup App in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disk-cleanup-app-in-windows-11.jpg)
5. Disk Cleanup will close and redirect you to pick the appropriate drive. Click on the**OK** button.
6. Lastly, click on the**Delete files** button.

## 5\. Rename the SoftwareDistribution Folder

 Windows update stores its content in the SoftwareDistribution folder. Since it is located inside the Windows folder in the C drive, you mustn’t delete it. Instead, you can rename the folder to force the update service to recreate the folder again.

Repeat the following steps:

1. Open the Start menu and search CMD. Press Ctrl + Shift + Enter to open the command prompt with admin privileges.
2. Type the following commands to stop all the Windows update-related services:  
 net stop wuauserv net stop cryptSvc net stop bits net stop msiserver ![Rename the SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/rename-the-softwaredistribution-folder.jpg)
3. Once these services stop running, type**cls** in the command prompt windows. Then enter the following commands:  
 ren C:\\Windows\\SoftwareDistribution SoftwareDistribution.old ren C:\\Windows\\System32\\catroot2 Catroot2.old ![Rename the SoftwareDistribution Folder 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/rename-the-softwaredistribution-folder-2.jpg)
4. Both the above commands rename the**SoftwareDistribution** folder and**Catroot2** folder.
5. Now, you need to restart all the Windows services you stopped in step 3\. Enter the following commands:  
net start wuauserv net start cryptSvc net start bits net start msiserver ![Rename the SoftwareDistribution Folder 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/rename-the-softwaredistribution-folder-3.jpg)
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

## 7\. Manually Download Windows Updates

 If you are unable to download a specific Windows update using the Settings page, consider a direct download and install approach. Visit the Microsoft Update Catalog website and search for the KB update you want to download. However, you first have to check the corresponding update number which is failing to download and install on your system.

![Manually Download Windows Updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/manually-download-windows-updates.jpg)

## 8\. Reset Windows

 Resetting Windows is the last resort you have if none of the above methods work in your favor. However, before learning [how to perform a Windows system reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) , try out general fixes such as [SFC, CHKDSK, and DISM](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) scans on your system. Also,[disable Windows Defender](https://www.makeuseof.com/how-to-turn-off-windows-defender/) and try updating your system before hitting the reset button.

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
<li><a href="https://discord-videos.techidaily.com/in-2024-unraveling-the-pioneers-behind-famed-discord-expressions/"><u>In 2024, Unraveling the Pioneers Behind Famed Discord Expressions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-a-halted-warcraft-update-sequence/"><u>Navigating a Halted Warcraft Update Sequence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-incorrect-windows-duo-software-setup/"><u>Steps to Rectify Incorrect Windows Duo Software Setup</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-the-7-best-total-war-games/"><u>[Updated] In 2024, The 7 Best Total War Games</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-music-from-oppo-reno-9a-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Music from Oppo Reno 9A to iPod | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-internal-audio-error-in-audacity-win-11-and-11/"><u>Tackling Internal Audio Error in Audacity, Win 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speeding-up-a-halted-download-the-windows-method/"><u>Speeding up a Halted Download: The Windows Method</u></a></li>
<li><a href="https://article-helps.techidaily.com/acclaimed-vehicle-monitoring-systems-explained-for-2024/"><u>Acclaimed Vehicle Monitoring Systems Explained for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-d3d11-gpu-error-landscape-for-windows-1110/"><u>Navigating the D3D11 GPU Error Landscape for Windows 11/10</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-saving-the-best-from-fb-in-high-definition/"><u>[New] Saving the Best From FB in High Definition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalizing-steam-data-flow-escaping-slowdown-traps/"><u>Revitalizing Steam Data Flow: Escaping Slowdown Traps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/open-sound-settings-efficiently-using-these-9-strategies-in-windows-11/"><u>Open Sound Settings Efficiently Using These 9 Strategies in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-turn-your-voice-to-text-in-real-time-with-whisper-desktop/"><u>How to Turn Your Voice to Text in Real Time With Whisper Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-data-theft-controlling-removable-storage-on-pcs/"><u>Preventing Data Theft: Controlling Removable Storage on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quash-windows-data-on-launches-tracking/"><u>Quash Windows Data on Launches Tracking</u></a></li>
<li><a href="https://ai-topics.techidaily.com/2024-approved-easy-steps-to-make-a-talking-avatar-with-ai-from-any-photos/"><u>2024 Approved Easy Steps to Make a Talking Avatar with AI From Any Photos</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-unleash-your-creativity-top-free-3d-animation-apps-for-mobile/"><u>New 2024 Approved Unleash Your Creativity Top Free 3D Animation Apps for Mobile</u></a></li>
<li><a href="https://win11-tips.techidaily.com/intel-unison-explained-easy-mobile-dialing-on-the-latest-windows-11/"><u>Intel Unison Explained: Easy Mobile Dialing on the Latest Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reset-and-reactivate-a-windows-users-guide-for-ms-store/"><u>Reset and Reactivate: A Windows User's Guide for MS Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solve-stuck-sheets-and-frozen-viewport-in-excel/"><u>Solve Stuck Sheets and Frozen Viewport in Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-non-uniform-colour-realms-in-windows/"><u>Navigating Non-Uniform Colour Realms in Windows</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fake-the-location-to-get-around-the-mlb-blackouts-on-itel-p55plus-drfone-by-drfone-virtual-android/"><u>In 2024, Fake the Location to Get Around the MLB Blackouts on Itel P55+ | Dr.fone</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-how-to-be-a-successful-youtuber/"><u>Updated How To Be A Successful YouTuber</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-no-server-issues-fixes-and-tips-for-apex-on-windows-(156-chars/"><u>Overcoming 'No Server' Issues: Fixes and Tips for Apex on Windows (<156 Chars)</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-the-most-effective-ways-to-bypass-iphone-7-activation-lock-by-drfone-ios/"><u>In 2024, The Most Effective Ways to Bypass iPhone 7 Activation Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-and-fixing-device-disconnection-on-win-1011/"><u>Navigating and Fixing Device Disconnection on Win 10/11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-honor-play-8t-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Honor Play 8T to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-getting-acquainted-with-discord-stickers-for-2024/"><u>[Updated] Getting Acquainted with Discord Stickers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-display-embrace-tiled-workspace/"><u>Streamline Your Display: Embrace Tiled Workspace</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-how-to-choose-a-live-streaming-platform-with-10-tips/"><u>[New] How to Choose a Live Streaming Platform with 10 Tips?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-exception-breakpoint-obstacle/"><u>Overcoming Windows Exception Breakpoint Obstacle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivation-guide-for-your-frozen-windows-11-search-box/"><u>Reactivation Guide for Your Frozen Windows 11 Search Box</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-tackle-windows-package-unopenable-issue-effectively/"><u>Steps to Tackle Windows Package Unopenable Issue Effectively</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/tips-for-perfect-control-how-to-use-your-switch-pro-on-steam/"><u>Tips for Perfect Control  How to Use Your Switch Pro on Steam</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-use-phone-clone-to-migrate-your-poco-x6-data-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Use Phone Clone to Migrate Your Poco X6 Data? | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-non-microsoft-methods-for-game-session-recording/"><u>[New] 2024 Approved  Non-Microsoft Methods for Game Session Recording</u></a></li>
<li><a href="https://extra-hints.techidaily.com/adobes-path-to-perspective-creating-life-like-text/"><u>Adobe's Path to Perspective  Creating Life-Like Text</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-design-stunning-whatsapp-status-updates-with-these-apps-for-2024/"><u>New Design Stunning WhatsApp Status Updates with These Apps for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-integration-of-ping-in-routine-windows-tasks/"><u>Seamless Integration of Ping in Routine Windows Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-problems-with-saving-windows-volume-configurations/"><u>Overcoming Problems with Saving Window's Volume Configurations</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-unleash-your-creativity-best-hand-drawing-whiteboard-animation-tools-2023/"><u>New Unleash Your Creativity Best Hand Drawing Whiteboard Animation Tools 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/latency-free-leap-essential-tips-for-clean-video-windows-streams/"><u>Latency-Free Leap: Essential Tips for Clean Video Windows Streams</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-lights-camera-action-a-kids-guide-to-making-movies/"><u>New 2024 Approved Lights, Camera, Action! A Kids Guide to Making Movies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-telnet-activation-on-latest-windows-systems/"><u>Secure Telnet Activation on Latest Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-a-new-surname-username-alteration-in-windows-11/"><u>Securing a New Surname: UserName Alteration in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/investigating-windows-process-hostaggregate-use-and-security-implications/"><u>Investigating Windows' Process HostAggregate: Use & Security Implications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-file-management-with-windows-autodelete-feature/"><u>Simplifying File Management with Windows' AutoDelete Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-hidden-time-display-on-windows-bar/"><u>Setting Up Hidden Time Display on Window's Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-approaches-to-instantaneously-generating-multiple-subfolders-in-windows/"><u>Innovative Approaches to Instantaneously Generating Multiple Subfolders in Windows</u></a></li>
</ul></div>
