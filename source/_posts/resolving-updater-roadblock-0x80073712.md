---
title: "Resolving Updater Roadblock: 0X80073712"
date: 2024-07-12T17:14:25.609Z
updated: 2024-07-13T17:14:25.609Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Resolving Updater Roadblock: 0X80073712"
excerpt: "This Article Describes Resolving Updater Roadblock: 0X80073712"
keywords: Updater Error Fixing,0X80073712 Troubleshooting,BSOD Error Code 0X80073712,Windows Update Failure Resolution,System Freeze,Updater Roadblock Solutions,Zeroing Out Software Issues
thumbnail: https://thmb.techidaily.com/e6c7c0aea059b2b9594111c92d9d243c60708ba7355f3daa30e8aeaa265b4225.jpg
---

## Resolving Updater Roadblock: 0X80073712

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
<li><a href="https://win11-tips.techidaily.com/remedying-writing-rights-denied-on-windows-devices/"><u>Remedying Writing Rights Denied on Windows Devices</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-speech-recognition-and-use-it-free/"><u>In 2024, Speech Recognition and Use It Free</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/cut-the-clutter-best-iphone-android-apps-for-watermark-removal/"><u>Cut the Clutter  Best iPhone, Android Apps for Watermark Removal</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-free-mobile-downloader-the-ultimate-apps-for-video-buffs/"><u>[Updated] Free Mobile Downloader  The Ultimate Apps for Video Buffs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modifying-password-policy-update-lockout-value-post-incorrect-attempts/"><u>Modifying Password Policy: Update Lockout Value Post Incorrect Attempts</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-meme-mastery-the-top-10-apps-for-android-and-ios-users-for-2024/"><u>New Meme Mastery The Top 10 Apps for Android and iOS Users for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-windows-net-runtime-requirement-hurdle/"><u>Avoiding Windows' .NET Runtime Requirement Hurdle</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-tiktok-watermark-remover-software-online-options-compared/"><u>Updated TikTok Watermark Remover Software Online Options Compared</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/in-2024-rotate-your-3gp-videos-for-free-top-5-tools-of-the-year/"><u>In 2024, Rotate Your 3GP Videos for Free Top 5 Tools of the Year</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-security-faults-and-fixes/"><u>Navigating Through Windows Security Faults & Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-files-write-access-no-more-restrictions/"><u>Adjusting Windows Files: Write Access No More Restrictions</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-2024-approved-brilliance-bunch-leading-gk-video-channels/"><u>[Updated] 2024 Approved  Brilliance Bunch  Leading GK Video Channels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrading-to-optimal-windows-audios-through-driver-revision/"><u>Upgrading to Optimal Windows Audios Through Driver Revision</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-address-offline-lsa-warning/"><u>Steps to Address Offline LSA Warning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/system-patch-up-reviving-synapse-in-latest-windows/"><u>System Patch-Up: Reviving Synapse in Latest Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-discontinue-repeated-edge-icons/"><u>Solutions to Discontinue Repeated Edge Icons</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-best-side-by-side-video-editors-for-ios-and-android-phones/"><u>New 2024 Approved Best Side-by-Side Video Editors for iOS and Android Phones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tweak-viewer-direction-on-windows-monitor/"><u>Tweak Viewer Direction on Windows Monitor</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-elevate-your-profile-with-vimeo-on-instagram/"><u>In 2024, Elevate Your Profile with Vimeo on Instagram</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/maximize-views-sharing-your-twitch-stream-on-fb-for-2024/"><u>Maximize Views  Sharing Your Twitch Stream on FB for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-where-is-the-best-place-to-catch-dratini-on-vivo-y100-drfone-by-drfone-virtual-android/"><u>In 2024, Where Is the Best Place to Catch Dratini On Vivo Y100 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shifting-paradigms-of-administrative-control-in-windows-environments/"><u>Shifting Paradigms of Administrative Control in Windows Environments</u></a></li>
<li><a href="https://video-capture.techidaily.com/the-ultimate-guide-to-sync-obs-with-facebook/"><u>The Ultimate Guide to Sync OBS with Facebook</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-regular-payment-structures-in-youtuber-economics/"><u>In 2024, Regular Payment Structures in YouTuber Economics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-windows-11-password-strategy/"><u>Transforming Windows 11 Password Strategy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-the-impact-reducing-unrealcefsubprocess-load-in-windows/"><u>Mitigating the Impact: Reducing UnrealCEFSubprocess Load in Windows</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-the-insiders-look-at-facebook-video-proportions-and-settings-for-2024/"><u>[Updated] The Insider's Look at Facebook Video Proportions and Settings for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-resolve-dual-user-microsoft-errors/"><u>Strategies to Resolve Dual User Microsoft Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/circumventing-non-changeable-sleepwake-modes-in-windows-11/"><u>Circumventing Non-Changeable Sleep/Wake Modes in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-pcs-dns-cache-efficiently/"><u>Revamp Your PC's DNS Cache Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-overcome-windows-file-not-found-error/"><u>Methods to Overcome Windows 'File Not Found' Error</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-ios-system-issues-of-iphone-12-pro-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair iOS System Issues of iPhone 12 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-case-for-how-win11-wins-over-macos/"><u>The Case For: How Win11 Wins over macOS</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-dj-audio-editor-software-review/"><u>Updated In 2024, DJ Audio Editor Software Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-overcoming-d3d11-gpu-hurdles-in-w11w10/"><u>Quick Guide to Overcoming D3D11 GPU Hurdles in W11/W10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modifying-windows-11-shutdown-time-for-tasks-in-progress/"><u>Modifying Windows 11 Shutdown Time for Tasks in Progress</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-unlock-professional-video-capturing-key-insights/"><u>[New] In 2024, Unlock Professional Video Capturing  Key Insights</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-a-closer-look-at-the-m1-pro-versus-m1-max-in-apple-devices/"><u>In 2024, A Closer Look at the M1 Pro Versus M1 Max in Apple Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-the-empty-folder-error-message-on-win-11/"><u>Removing the 'Empty Folder' Error Message on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-ed-themed-windows-experience/"><u>Tailoring Ed-Themed Windows Experience</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-enthusiastic-appreciation-audio-creator-for-2024/"><u>Updated Enthusiastic Appreciation Audio Creator for 2024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/in-2024-unleash-your-creativity-gopro-video-editing-on-mac-for-beginners/"><u>In 2024, Unleash Your Creativity GoPro Video Editing on Mac for Beginners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-chkdsk-sfc-vs-dism-in-os-maintenance/"><u>Understanding CHKDSK, SFC Vs. DISM in OS Maintenance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedily-seek-synonyms-with-win11-dictionary/"><u>Speedily Seek Synonyms with Win11 Dictionary</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-optimize-memory-retention-using-mematics-solution/"><u>[New] Optimize Memory Retention Using Mematic's Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reestablishing-access-rectifying-unreachable-ea-services/"><u>Reestablishing Access: Rectifying Unreachable EA Services</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-unlock-free-music-anytime-facebook-app-for-2024/"><u>[New] Unlock Free Music, Anytime - Facebook App for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-guide-to-buy-and-install-adobe-reader-via-ms-store/"><u>Simplified Guide to Buy and Install Adobe Reader via MS Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-workflow-integrating-wordpad-shortcuts-into-context-menus-on-windows-11/"><u>Streamlining Workflow: Integrating WordPad Shortcuts Into Context Menus on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augment-windows-management-with-a-disk-space-analysis-tool/"><u>Augment Windows Management with a Disk Space Analysis Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-functionality-of-microsofts-phone-link-an-introduction/"><u>The Functionality of Microsoft's 'Phone Link': An Introduction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pro-wls-techniques-unlocking-the-full-power-of-wsl-2-in-win-oses/"><u>Pro WLS Techniques: Unlocking the Full Power of WSL 2 in Win OSes</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/approved-unveiling-the-power-of-youtube-backlinks-for-creators/"><u>2024 Approved  Unveiling the Power of YouTube Backlinks for Creators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-digital-containers-file-prop-techniques/"><u>Navigating Digital Containers: File Prop Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-new-windows-11-experience-must-try-settings/"><u>Tailoring Your New Windows 11 Experience: Must-Try Settings</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-screen-guards-protect-your-device-capture-better/"><u>[Updated] Screen Guards  Protect Your Device, Capture Better</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-from-live-demos-to-online-sharing-mastering-idevice-screenshots-for-video-content/"><u>[Updated] 2024 Approved  From Live Demos to Online Sharing  Mastering iDevice Screenshots for Video Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-glitches-with-ps/"><u>Resolving Windows Glitches with PS</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-from-live-action-to-animated-video-to-cartoon-conversion-made-easy-for-2024/"><u>New From Live-Action to Animated Video to Cartoon Conversion Made Easy for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/unveiling-the-ultimate-frequency-tuner-configurations/"><u>Unveiling the Ultimate Frequency Tuner Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essentials-of-installing-works-in-the-latest-os/"><u>The Essentials of Installing Works in the Latest OS</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-finest-15-zero-cost-methods-to-record-windows-screens-for-2024/"><u>[Updated] Finest 15 Zero-Cost Methods to Record Windows Screens for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-how-to-animate-your-designs-with-canva-gif-for-2024/"><u>New How to Animate Your Designs With Canva GIF for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-legends-of-arcade-combat-nintendos-top-ten-on-switch/"><u>[Updated] Legends of Arcade Combat  Nintendo's Top Ten on Switch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-ways-to-check-for-open-tcpip-ports-on-windows/"><u>3 Ways to Check for Open TCP/IP Ports on Windows</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-enhance-your-photos-with-top-insta-editors-for-2024/"><u>[New] Enhance Your Photos with Top Insta Editors for 2024</u></a></li>
</ul></div>
