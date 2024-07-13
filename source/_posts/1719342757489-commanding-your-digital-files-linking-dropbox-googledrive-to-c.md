---
title: "Commanding Your Digital Files: Linking Dropbox, GoogleDrive to C:"
date: 2024-07-12T17:43:57.373Z
updated: 2024-07-13T17:43:57.373Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Commanding Your Digital Files: Linking Dropbox, GoogleDrive to C:"
excerpt: "This Article Describes Commanding Your Digital Files: Linking Dropbox, GoogleDrive to C:"
keywords: Cloud Storage Management,Dropbox & GoogleDrive Integration,Linking Drive Systems,File Organization Strategy,Digital Files Sync,C,Secure Data Backup
thumbnail: https://thmb.techidaily.com/78d24648f206f65b94f12ac351c4b3ce727b02ece4c292665e0f6b95fb5f60be.jpg
---

## Commanding Your Digital Files: Linking Dropbox, GoogleDrive to C

 Today, cloud storage solutions are an essential part of our daily life, to the point that all major OSes come with support for such cloud services "baked in".

 Cloud storage services are easier than ever to access, they offer free storage, and as a bonus, they can make your life miserable if you want to access anything stored there using a quirky app instead of your web browser.

 That's why you can find extra third-party tools that assist in using cloud storage "as a normal drive". For this article, though, we'll do the same by exploiting Windows' built-in shared folders functionality!

## Common Cloud Storage Issues You May Encounter on Windows

 Dropbox, Google Drive, and similar cloud storage/sync services are easy to access from a web browser or the OS's default file manager. When you demand more than merely accessing your files, though, you may run into issues.

* Dropbox is accessible from a link in the file manager that brings you to its actual local folder, inside which your files are synced. Alternatively, you can visit that folder yourself. Dropbox cannot be "accessible through a letter" by default.
* Google Drive offers the option to map every account to a drive letter. However, try to access the contents of the virtual drive "behind" its "official" drive letter. Instead of your Google Drive files, you'll find a link to its local folder.
* Other alternatives may be even worse, with some only accessible locally through their custom clients.

 So, is it impossible to have your cloud storage account's "root folder" accessible directly from a drive letter?

 Thankfully, you can use a third-party solution for that. They're usually straightforward and can make your cloud storage "behave" like a normal drive on your computer. Still, you might want to avoid such apps for various reasons.

* Most cost money or are ad-supported.
* You'll be giving access to your data to another third party (on top of the cloud storage provider).
* The more apps and services that have access to your files, the higher the chances they'll fall into the wrong hands after a security breach.
* Extra software and services translate to increased complexity and potential for failure: some files may not sync when you expect them, metadata might get lost, etc.

 The major case against them is that there's no reason to use more software than you need.

## Why Not Just Use Google Drive's Folders?

 Let's see how Google Drive fails to offer proper access to its local folder through a letter.

1. Right-click on **Google Drive's icon** on the tray, click on the **cog icon** on the top right to access its menu and choose **Preferences**. Click on the **cog icon** in Google Drive Preferences window to access your account's settings. Ensure there's a drive letter assigned to your Google Drive.  
![Google Drive Settings Drive Letter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/google-drive-settings-drive-letter.jpg)
2. Visit the actual **drive letter** through any file manager and wonder how there's a "My Drive" folder instead of your files.  
![Google Drive Actual Drive Letter Contents](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/google-drive-actual-drive-letter-contents.jpg)
3. Try "entering" that folder and marvel at how the **path** changes to the true one where Google Drive's folder is stored, potentially breaking some apps.  
![Google Drive True Folder Path](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/google-drive-true-folder-path.jpg)

 Now, let's fix, or rather "sidestep" this little issue by exploiting how network folders work on Windows.

## How to Set Up Windows Shared Folders

 The first part of the process will be "sharing" the actual folder used by the cloud storage service that we want to access directly from a drive. Don't worry; you won't be sharing anything with anyone (apart from the cloud service provider where you already keep your files).

 For this example, we'll swap cloud services and "do Dropbox", but you can use the same process with any cloud storage service's local folder.

1. Run your favorite file manager and visit the path "directly above" your cloud storage folder (so that you can see it in your file manager).  
![Dropbox Folder In Windows Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dropbox-folder-in-windows-explorer.jpg)
2. Right-click on the folder and choose **Properties**.  
![Dropbox Folder Windows Explorer Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dropbox-folder-windows-explorer-properties.jpg)
3. Move to the **Sharing** tab and enable sharing for your folder. If you need help, check our guide on [how to access shared folders on Windows](https://www.makeuseof.com/unable-to-access-shared-folder-windows/).  
![Dropbox Folder Windows Explorer Properties Sharing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dropbox-folder-windows-explorer-properties-sharing.jpg)

## How to Assign Letters to “Networked” Cloud Storage Folders

 Your folder should be accessible "as a share" by now, but it still isn't mapped to a letter. For that, we'll use Windows' ability to assign letters to "network drives" for easy access.

 Thankfully, Windows also recognizes the shared folder as "a network drive", even if it's stored locally.

1. Type "**\\\\localhost**" in your file manager's location bar to see all the shared folders on your local PC. Among them should be your newly shared cloud storage folder.  
![Windows Explorer Localhost Shared Folders](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-explorer-localhost-shared-folders.jpg)
2. Right-click on it and choose **Map network drive**.  
![Windows Explorer Localhost Shared Folders Menu Map Network Drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-explorer-localhost-shared-folders-menu-map-network-drive.jpg)
3. Choose the **letter** you want to assign to your cloud storage folder from the drop-down menu next to **Drive**. Click **Finish** to apply the change.  
![Windows Explorer Map Network Drive Letter Selection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-explorer-map-network-drive-letter-selection.jpg)
4. Visit your "new drive" using the letter you assigned, and you should have direct access to your cloud storage's contents.  
![Windows Explorer Direct Access To Dropbox Folder From Letter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-explorer-direct-access-to-dropbox-folder-from-letter.jpg)

 The above implies that you'll set up your cloud storage client to fully sync all files and folders/keep them stored locally.

## What About Using Subst?

 You may wonder why we didn't go with subst for this guide. Indeed, subst is so useful that we've made sure to include it on our list of [the essential Windows CMD commands you should know](https://www.makeuseof.com/tag/essential-windows-cmd-commands/). But what is it, how can it help, and how do you use it?

 Open Windows Search with **Win + S**, search for "**Terminal**" or "**PowerShell**", and choose **Run as Administrator**. There, use subst like:

subst DRIVE_LETTER: FULL:\PATH\TO\FOLDER

 For example, to map the folder "c:\\Cloud Drives\\Dropbox" to the letter "Z", the command would be:

subst Z: "C:\Cloud Drives\Dropbox"

 After that, your folder should be accessible from the drive you assigned to it. If the change isn't apparent immediately, log off and back on or restart your PC.

## A Local Folder for Your Cloud Storage on Windows

 Thanks to Microsoft's somewhat square logic of "if it's a shared folder, you can map it, no matter where it is", it's easy to access your cloud storage folders directly from a drive letter. All it takes is to share them with yourself!

 Of course, power users would probably prefer to "subst them" to submission. Strangely, many forget that "subst" can also be used with cloud storage folders. Despite your chosen path, we can probably mark this little annoyance when using cloud storage folders with a "problem solved."

 Cloud storage services are easier than ever to access, they offer free storage, and as a bonus, they can make your life miserable if you want to access anything stored there using a quirky app instead of your web browser.

 That's why you can find extra third-party tools that assist in using cloud storage "as a normal drive". For this article, though, we'll do the same by exploiting Windows' built-in shared folders functionality!



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://tiktok-videos.techidaily.com/the-ultimate-list-of-global-tiktok-titans/"><u>The Ultimate List of Global TikTok Titans</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-tour-to-windows-booting-point/"><u>A Quick Tour to Windows' Booting Point</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-security-settings-through-gpo/"><u>Unveiling Windows Security Settings Through GPO</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-performance-skyrocketing-vram-in-win1011-systems/"><u>Enhance Performance: Skyrocketing VRAM in Win10/11 Systems</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-show-wi-fi-password-on-vivo-y77t-by-drfone-android/"><u>How to Show Wi-Fi Password on Vivo Y77t</u></a></li>
<li><a href="https://extra-resources.techidaily.com/comprehensive-overview-merging-srt-with-mp4-files-and-videos/"><u>Comprehensive Overview  Merging SRT with MP4 Files and Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-hdd-invisibility-glitches/"><u>Correcting HDD Invisibility Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-share-failures-on-geforce-experience-for-w10w11/"><u>Tackling Share Failures on GeForce Experience for W10/W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-wizardry-learn-hotkeys-to-manage-your-pc/"><u>Windows Wizardry: Learn Hotkeys to Manage Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-adopting-sudo-can-transform-your-windows-experience/"><u>Why Adopting Sudo Can Transform Your Windows Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convergence-of-ios-and-windows-using-apple-maps-effectively/"><u>Convergence of iOS and Windows: Using Apple Maps Effectively</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-recording-sims-4-games-a-complete-beginners-guide-for-2024/"><u>[Updated] Recording Sims 4 Games  A Complete Beginner's Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-a-personalized-windows-11-interface-with-enlarged-icons/"><u>Crafting a Personalized Windows 11 Interface with Enlarged Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-app-start-issue-qt-plugin-not-available/"><u>Troubleshooting App Start Issue: Qt Plugin Not Available</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-unlink-your-apple-iphone-8-plus-from-your-apple-id-by-drfone-ios/"><u>How To Unlink Your Apple iPhone 8 Plus From Your Apple ID</u></a></li>
<li><a href="https://extra-information.techidaily.com/expert-tips-building-meme-foundations/"><u>Expert Tips  Building Meme Foundations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-mouseclicklock-usability-on-windows-systems/"><u>Boosting MouseClickLock Usability on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-detailed-manual-for-individualized-keybindings-in-win11/"><u>A Detailed Manual for Individualized Keybindings in Win11</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-vivid-palette-review-best-5-high-definition-displays/"><u>[Updated] 2024 Approved  Vivid Palette Review  Best 5 High-Definition Displays</u></a></li>
<li><a href="https://techidaily.com/useful-ways-that-can-help-to-effectively-recover-deleted-files-from-nokia-c12-pro-by-fonelab-android-recover-data/"><u>Useful ways that can help to effectively recover deleted files from Nokia C12 Pro</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/1719581584502-efficient-bokmaal-learning-quick-10-minute-fixes/"><u>Efficient Bokmaal Learning, Quick 10-Minute Fixes!</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-mastering-the-art-of-adding-youtube-playlists-to-your-website-seamlessly/"><u>2024 Approved  Mastering the Art of Adding YouTube Playlists to Your Website Seamlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-device-diversity-into-a-single-note-world/"><u>Transforming Device Diversity Into a Single Note World</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-masterpiece-maker-unleash-the-hidden-potential-in-your-videos/"><u>New Masterpiece Maker Unleash the Hidden Potential in Your Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-erratic-read-only-file-behavior-on-win11/"><u>Fixing Erratic Read-Only File Behavior on Win11</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-the-ultimate-list-best-video-speed-editor-software-for-windows-mac-and-linux/"><u>Updated 2024 Approved The Ultimate List Best Video Speed Editor Software for Windows, Mac, and Linux</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-advanced-array-manipulations-and-sorting-algorithms-for-2024/"><u>[Updated] Advanced Array Manipulations and Sorting Algorithms for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-clean-boot-a-beginners-approach/"><u>Windows 11 Clean Boot: A Beginner's Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-capturing-uac-alerts-on-your-pc/"><u>Expert Guide: Capturing UAC Alerts on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/can-malware-scanners-hang-up-compute-resources/"><u>Can Malware Scanners Hang Up Compute Resources?</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-top-strategies-to-tackle-vlc-challenges-on-macos/"><u>[New] Top Strategies to Tackle VLC Challenges on macOS</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-seamless-transition-of-idevice-content-to-youtube/"><u>In 2024, Seamless Transition of iDevice Content to YouTube</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-essential-11-guides-on-color-adjustment-excellence/"><u>2024 Approved  Essential 11 Guides on Color Adjustment Excellence</u></a></li>
<li><a href="https://activate-lock.techidaily.com/easy-tutorial-for-activating-icloud-from-iphone-x-safe-and-legal-by-drfone-ios/"><u>Easy Tutorial for Activating iCloud from iPhone X Safe and Legal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/executing-customized-policies-to-a-singular-account-in-win-1011/"><u>Executing Customized Policies to a Singular Account in Win 10/11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/extended-exploration-gopro-slr4-silver-edition/"><u>Extended Exploration  GoPro SLR4 Silver Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-smooth-operation-fixing-windows-notepad-crashes/"><u>Ensuring Smooth Operation: Fixing Windows Notepad Crashes</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-gear-up-with-our-12-tycoon-titles-your-gaming-passport-to-success/"><u>[Updated] 2024 Approved  Gear Up with Our #12 Tycoon Titles - Your Gaming Passport to Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-updater-setback-error-0x800f080a-on-windows-systems/"><u>Bypassing Updater Setback Error 0X800F080A on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-full-capability-of-windows-11-with-multi-display-setup/"><u>Unlock the Full Capability of Windows 11 With Multi-Display Setup</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-i-transferred-messages-from-samsung-galaxy-s23plus-to-iphone-12xs-max-in-seconds-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How I Transferred Messages from Samsung Galaxy S23+ to iPhone 12/XS (Max) in Seconds | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-5-tactics-reactivating-windows-defender-protection-mechanism/"><u>Top 5 Tactics: Reactivating Windows Defender Protection Mechanism</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-and-tricks-to-fix-error-0x800700e1-in-windows-11/"><u>Tips & Tricks to Fix Error 0X800700E1 in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-value-not-available-issue-in-windows/"><u>Eradicating Value Not Available Issue in Windows</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-complete-tutorial-on-after-effects-countdown-timer-adding/"><u>Updated 2024 Approved Complete Tutorial on After Effects Countdown Timer Adding</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-insta-video-size-strategy-for-maximum-engagement/"><u>[New] In 2024, Insta Video Size Strategy for Maximum Engagement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cant-scroll-in-microsoft-excel-for-windows-try-these-fixes/"><u>Can't Scroll in Microsoft Excel for Windows? Try These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-steam-online-connectivity-failures-w11/"><u>Addressing Steam Online Connectivity Failures W11</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-mastering-the-deck-to-deck-experience-with-durecorder/"><u>[New] 2024 Approved  Mastering the Deck-to-Deck Experience with DuRecorder</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-windows-phone-media-saving-problems/"><u>Eliminating Windows Phone Media Saving Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-desktop-experience-with-windows-11-widgets/"><u>Elevate Your Desktop Experience with Windows 11 Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-dims-handbook-for-windows-11-repair/"><u>The Complete DIMS Handbook for Windows 11 Repair</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-wasd-isolation-necessity-or-concern/"><u>Understanding WASD Isolation: Necessity or Concern?</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-crafting-the-ultimate-mc-community-dwellings-for-2024/"><u>[New] Crafting the Ultimate MC Community Dwellings for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/expert-tips-to-dominate-kinemaster-and-identify-top-online-video-services/"><u>Expert Tips to Dominate KineMaster & Identify Top Online Video Services</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/pro-mac-and-pc-screen-capture-experts-for-2024/"><u>Pro Mac & PC Screen Capture Experts for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-overcoming-unnatural-motion-blur-in-uav-videos/"><u>2024 Approved  Overcoming Unnatural Motion Blur in UAV Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-seamless-web-access-via-win-os/"><u>Ensuring Seamless Web Access via Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-center-personalizing-folders-through-comments-in-11/"><u>Command Center: Personalizing Folders Through Comments in 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/confusion-in-xbox-app-gaming-placement/"><u>Confusion in Xbox App Gaming Placement</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-mocroscreen-recording-ads/"><u>In 2024, MocroScreen Recording Ads</u></a></li>
</ul></div>
