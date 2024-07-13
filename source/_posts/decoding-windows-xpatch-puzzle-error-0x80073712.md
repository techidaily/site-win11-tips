---
title: "Decoding Windows XPatch Puzzle: Error 0X80073712"
date: 2024-07-12T16:54:06.967Z
updated: 2024-07-13T16:54:06.967Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Decoding Windows XPatch Puzzle: Error 0X80073712"
excerpt: "This Article Describes Decoding Windows XPatch Puzzle: Error 0X80073712"
keywords: Win XP Security Issue,XP Error 0X80073712 Fix,Solving Windows Patch Error,XP Error Code Repair,XpError Fix Guide,Resolve XP Update Failure,Overcoming XP Patch Glitch
thumbnail: https://thmb.techidaily.com/e0fa0d67e26442f6514904daf3cc23134382c2cc52f88c01d78e6b3f6c28c68c.jpg
---

## Decoding Windows XPatch Puzzle: Error 0X80073712

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
<li><a href="https://win11-tips.techidaily.com/discover-the-file-path-of-your-current-wallpaper/"><u>Discover the File Path of Your Current Wallpaper</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-ultimate-guide-to-funny-image-memes/"><u>[New] The Ultimate Guide to Funny Image Memes</u></a></li>
<li><a href="https://article-posts.techidaily.com/perfecting-the-art-of-podcast-title-creation-essential-tips-and-inspirations/"><u>Perfecting the Art of Podcast Title Creation  Essential Tips & Inspirations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-macos-usability-through-windows-apps/"><u>Boosting macOS Usability Through Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-censored-windows-11-theme-options-with-registry/"><u>Unveiling Censored Windows 11 Theme Options with Registry</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-hdmi-radeon-revival/"><u>[New] In 2024, HDMI Radeon Revival</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-edge-top-windows-platforms-for-ndsswitch-players/"><u>Cutting Edge: Top Windows Platforms for NDS/Switch Players</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-must-have-upgrades-top-11-phantom-4-addons/"><u>In 2024, Must-Have Upgrades  Top 11 Phantom 4 Addons</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-guide-to-mirror-your-tecno-pova-6-pro-5g-to-other-android-devices-drfone-by-drfone-android/"><u>In 2024, Guide to Mirror Your Tecno Pova 6 Pro 5G to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-in-2024-quick-fix-resizing-your-video-to-perfect-proportions/"><u>Updated In 2024, Quick Fix Resizing Your Video to Perfect Proportions</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-novel-talk-points-for-daily-videos/"><u>[New] Novel Talk Points for Daily Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-speech-detection-with-windows/"><u>Streamlining Speech Detection with Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-activatingdeactivating-touch-typing-on-windows/"><u>Tips for Activating/Deactivating Touch Typing on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-terminal-and-powershell-identifying-what-sets-them-aside/"><u>Windows Terminal and PowerShell: Identifying What Sets Them Aside</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-strategies-eradicate-wow-error-132-in-1011/"><u>Winning Strategies: Eradicate WoW Error 132 in 10/11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-youtube-video-trapping-best-practices-explored/"><u>In 2024, YouTube Video Trapping  Best Practices Explored</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-2024-approved-unlock-15-simple-vlog-inspirations-today/"><u>[New] 2024 Approved  Unlock 15 Simple Vlog Inspirations Today</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-final-cut-pro-x-the-ultimate-guide-for-vertical-video-posts/"><u>2024 Approved  Final Cut Pro X  The Ultimate Guide for Vertical Video Posts</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-essential-free-tools-convert-youtube-audio-to-mp3-on-iphone/"><u>[Updated] 2024 Approved  Essential Free Tools  Convert YouTube Audio to MP3 on iPhone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719371847315-fixing-faulty-windows-keys-in-a-minute/"><u>Fixing Faulty Windows Keys in a Minute</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/get-rid-of-corrupt-excel-2010-file-stellar-by-stellar-guide/"><u>Get Rid of corrupt Excel 2010 File | Stellar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-steam-goals-a-complete-walkthrough/"><u>Clearing Steam Goals: A Complete Walkthrough</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-revealed-the-foremost-10-gadgets-elevating-your-podcast-sound/"><u>[Updated] Revealed  The Foremost 10 Gadgets Elevating Your Podcast Sound</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-repairing-razer-synapse-fixes-for-modern-oses/"><u>Swift Repairing: Razer Synapse Fixes for Modern OSes</u></a></li>
<li><a href="https://extra-resources.techidaily.com/excellence-in-starting-points-for-panzoids/"><u>Excellence in Starting Points for Panzoids</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-framed-perfection-websites-and-apps-to-elevate-your-images/"><u>2024 Approved  Framed Perfection  Websites and Apps to Elevate Your Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbo-charging-steam-downloads-for-windows-users/"><u>Turbo-Charging Steam Downloads for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-address-winscomrssvdll-issues-during-system-boot/"><u>Steps to Address WinscomrssvDll Issues During System Boot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-the-windows-11-ui-to-prompt-users-for-system-updates/"><u>Tailoring the Windows 11 UI to Prompt Users for System Updates</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/full-guide-to-catch-100-iv-pokemon-using-a-map-on-realme-gt-neo-5-se-drfone-by-drfone-virtual-android/"><u>Full Guide to Catch 100 IV Pokémon Using a Map On Realme GT Neo 5 SE | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-made-storage-repositioning-in-onedrive-for-win-11/"><u>Tailor-Made Storage Repositioning in OneDrive for Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-list-of-brightness-managers-for-windows-multiscreen-professionals/"><u>The Ultimate List of Brightness Managers For Windows Multiscreen Professionals</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-does-active-presenter-8-outperform-its-rivals-for-2024/"><u>[New] Does Active Presenter 8 Outperform Its Rivals for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/battery-friendly-tips-minimize-windows-11-apps-impact/"><u>Battery-Friendly Tips: Minimize Windows 11 Apps' Impact</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-flashframe-crafter/"><u>In 2024, FlashFrame Crafter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-steam-library-no-sync-error-solution/"><u>Tackling Steam Library: No Sync Error Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-your-desktop-experience-with-winbubbles-best-practices/"><u>Tailor Your Desktop Experience with WinBubble's Best Practices</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-architect-of-audiovisual-brilliance/"><u>2024 Approved  Architect of Audiovisual Brilliance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/workarounds-for-static-energy-controls-on-windows-11/"><u>Workarounds for Static Energy Controls on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-pro-efficient-docx-to-pdf-conversion-made-simple/"><u>Win 11 Pro: Efficient DOCX to PDF Conversion Made Simple</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-art-of-crafting-impressive-hdr-images-using-lightroom/"><u>[Updated] The Art of Crafting Impressive HDR Images Using Lightroom</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-approach-automated-password-addition-into-windows-texts/"><u>Streamlined Approach: Automated Password Addition Into Windows Texts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-bypass-chatbot-assistance-in-win-11-key-gen/"><u>Why Bypass Chatbot Assistance in Win 11 Key Gen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-salvage-dormant-wsreset-service-on-windows/"><u>Steps to Salvage Dormant WSReset Service on Windows</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-worlds-finest-screen-recording-software-no-deadline-for-2024/"><u>[New] World's Finest Screen Recording Software (No Deadline) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/creating-an-educational-ambiance-for-windows/"><u>Creating an Educational Ambiance for Windows</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-optimize-twitter-vids-the-full-hd-method/"><u>[Updated] 2024 Approved  Optimize Twitter Vids  The Full HD Method</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-disk-potential-masterful-techniques-in-w10w11/"><u>Unlocking Disk Potential: Masterful Techniques in W10/W11</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-feasible-ways-to-fake-location-on-facebook-for-your-realme-11-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Feasible Ways to Fake Location on Facebook For your Realme 11 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-win11-written-in-devhomes-script/"><u>Deciphering Win11' Written in DevHome's Script</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/streamline-video-production-with-free-music-for-2024/"><u>Streamline Video Production with Free Music for 2024</u></a></li>
</ul></div>
