---
title: "Addressing Windows Update Disruption: X712 Fiasco"
date: 2024-07-12T18:06:30.051Z
updated: 2024-07-13T18:06:30.051Z
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
 net stop wuauserv net stop cryptSvc net stop bits net stop msiserver  
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
<li><a href="https://win11-tips.techidaily.com/avoiding-do-not-have-access-issue-for-app-removals/"><u>Avoiding Do Not Have Access Issue for App Removals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-requires-ancient-login-details/"><u>Addressing Windows Requires Ancient Login Details</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-screen-separation-issues/"><u>Addressing Windows Screen Separation Issues</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-encompassed-understanding-google-podcast-app-elucidated/"><u>[New] Encompassed Understanding  Google Podcast App Elucidated</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augmenting-task-manager-functionality-in-windows-11-with-cli/"><u>Augmenting Task Manager Functionality in Windows 11 with CLI</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-quickstart-to-flawless-nft-artistry-for-beginners/"><u>In 2024, Quickstart to Flawless NFT Artistry for Beginners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-utilizing-box-for-file-selections-in-win11/"><u>Boost Efficiency: Utilizing Box for File Selections in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-interruptions-resolving-steams-error-code-e84/"><u>Avoid Interruptions: Resolving Steam’s Error Code E84</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-convert-and-save-webcam-images-in-vlc/"><u>In 2024, Convert and Save Webcam Images in VLC</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-initiating-efficient-conversations-on-snapchat-with-three-steps/"><u>[Updated] 2024 Approved  Initiating Efficient Conversations on Snapchat with Three Steps</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-webcam-safety-essentials-the-best-covers-ranked/"><u>[Updated] Webcam Safety Essentials  The Best Covers Ranked</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unraveling-the-lifecycle-of-windows-movie-maker-releases/"><u>In 2024, Unraveling the Lifecycle of Windows Movie Maker Releases</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-zooming-anomalies-fix-7-way-for-mouse-wheels/"><u>Banish Zooming Anomalies: Fix 7 Way for Mouse Wheels</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-how-to-add-music-to-instagram-reels/"><u>[Updated] 2024 Approved  How to Add Music to Instagram Reels?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bluetooth-harmony-linking-airpods-with-windows/"><u>Bluetooth Harmony: Linking AirPods with Windows</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-unleash-your-creativity-the-best-free-music-recording-software/"><u>In 2024, Unleash Your Creativity The Best Free Music Recording Software</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-gaming-and-economics-collide-24s-best-business-simulations/"><u>[Updated] 2024 Approved  Gaming and Economics Collide  '24'S Best Business Simulations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-computers-space-on-windows-using-these-free-tools/"><u>Boost Your Computer's Space on Windows Using These Free Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-windows-customization-adding-directories-to-context-menu/"><u>Advanced Windows Customization - Adding Directories to Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/aesthetic-arcade-adventures-old-classics-in-dosbox-x/"><u>Aesthetic Arcade Adventures: Old Classics in DOSBox-X</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-full-guide-to-unlock-apple-iphone-se-2020-with-itunes-drfone-by-drfone-ios/"><u>In 2024, Full Guide to Unlock Apple iPhone SE (2020) with iTunes | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-initiating-your-adventure-in-av1/"><u>2024 Approved  Initiating Your Adventure in AV1</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-exit-dfu-mode-on-iphone-6s-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Exit DFU Mode on iPhone 6s? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-settings-for-continuous-save-support-in-nvidia-control-center/"><u>Adjusting Settings for Continuous Save Support in NVidia Control Center</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-the-definitive-guide-to-instagram-to-mp4-transformation-2-ways-for-2024/"><u>[Updated] The Definitive Guide to Instagram-to-MP4 Transformation 2 Ways for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/secrets-to-proficient-ipad-screening-for-2024/"><u>Secrets to Proficient iPad Screening for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/batch-to-executable-guide-for-windows-users/"><u>Batch-to-Executable Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-wireless-and-cable-networks-on-windows-systems/"><u>Balancing Wireless & Cable Networks on Windows Systems</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-or-see-text-messages-what-can-you-do-with-life360-on-apple-iphone-11-drfone-by-drfone-virtual-ios/"><u>Can Life360 Track Or See Text Messages? What Can You Do with Life360 On Apple iPhone 11? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-captivating-viewers-top-10-creative-yt-reaction-tactics/"><u>[New] 2024 Approved  Captivating Viewers  Top 10 Creative YT Reaction Tactics</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-enhancing-business-communication-with-professional-skype-recordings/"><u>[New] Enhancing Business Communication with Professional Skype Recordings</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/elevate-video-performance-top-notch-youtube-seo-strategies-for-2024/"><u>Elevate Video Performance  Top-Notch YouTube SEO Strategies for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-optimal-cameras-for-puppet-film-projects/"><u>[New] Optimal Cameras for Puppet Film Projects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-alternatives-to-windows-snipping-quick-reliable-capture-techniques/"><u>Best Alternatives to Windows Snipping: Quick, Reliable Capture Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-act-keeping-high-vitality-in-check-on-windows/"><u>Balancing Act: Keeping High Vitality in Check on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-dpi-settings-for-optimal-display-performance/"><u>Adjust DPI Settings for Optimal Display Performance</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-a-step-by-step-journey-clearing-images-with-picsart-for-2024/"><u>[New] A Step-By-Step Journey  Clearing Images with Picsart for 2024</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-call-history-from-motorola-edgeplus-2023-by-fonelab-android-recover-call-logs/"><u>The way to get back lost call history from Motorola Edge+ (2023)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/aid-for-absconded-hardware-recognition-in-winos/"><u>Aid for Absconded Hardware Recognition in WinOS</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-free-vimeo-tutorial-to-craft-engaging-videos-for-2024/"><u>[New] Free Vimeo Tutorial to Craft Engaging Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-tips-for-efficient-voice-access-on-windows/"><u>Advanced Tips for Efficient Voice Access on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blending-folders-and-files-win-10s-technique/"><u>Blending Folders and Files: Win 10'S Technique</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bestowing-wondrous-widgets-onto-context-menu/"><u>Bestowing Wondrous Widgets Onto Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-pc-speed-with-improved-win11-startups/"><u>Boost PC Speed with Improved Win11 Startups</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-360-degree-cameras-vs-3d-cameras-what-are-the-differences/"><u>In 2024, 360 Degree Cameras Vs 3D Cameras  What Are the Differences</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-in-app-image-alterations-resizing-photos-made-simple-ios/"><u>In 2024, In-App Image Alterations  Resizing Photos Made Simple (iOS)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-methods-for-bypassing-windows-error-0x80040610-in-office/"><u>Advanced Methods for Bypassing Windows Error 0X80040610 in Office</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-videos-from-honor-magic-6-lite-by-fonelab-android-recover-video/"><u>Easy steps to recover deleted videos from Honor Magic 6 Lite</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-motorola-defy-2-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on Motorola Defy 2 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-11-shutdown-interval-for-executing-jobstasks/"><u>Adjusting Windows 11 Shutdown Interval for Executing Jobs/Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-unsolicited-file-explorer-activity/"><u>Addressing Unsolicited File Explorer Activity</u></a></li>
<li><a href="https://network-issues.techidaily.com/win11-dark-screen-post-update-solution/"><u>Win11 Dark Screen Post-Update Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-counter-strike-performance-a-frame-rate-guide/"><u>Boosting Counter-Strike Performance: A Frame Rate Guide</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/vintage-racing-spectacles-top-five/"><u>Vintage Racing Spectacles  Top Five</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-mastery-in-conflict-the-leading-7-total-war-tactics-for-2024/"><u>[Updated] Mastery in Conflict  The Leading 7 Total War Tactics for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-windows-tactics-for-hardware-id-retrieval/"><u>Advanced Windows Tactics for Hardware ID Retrieval</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginning-on-time-adjusting-startup-services-for-windows-11/"><u>Beginning on Time: Adjusting Startup Services for Windows 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-ultimate-speech-refinement-kit-free-tools-for-flawless-audio-effects/"><u>The Ultimate Speech Refinement Kit  Free Tools for Flawless Audio Effects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-10-and-11s-phishing-protection-settings/"><u>Adjusting Windows 10 & 11'S Phishing Protection Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-tools-for-win-soft-installation-chocolatey-or-wm/"><u>Best Tools for Win Soft Installation: Chocolatey or WM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beat-up-hypervisor-bsos-on-windows-step-by-step/"><u>Beat Up Hypervisor BSOS on Windows, Step by Step</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginners-trick-swiftly-access-sticky-notes-post-boot-windows/"><u>Beginner's Trick: Swiftly Access Sticky Notes Post-Boot Windows</u></a></li>
</ul></div>
