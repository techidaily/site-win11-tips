---
title: "Streamlining File Sharing: Using Dropbox/Google Drive From Windows Paths"
date: 2024-07-12T16:58:47.739Z
updated: 2024-07-13T16:58:47.739Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Streamlining File Sharing: Using Dropbox/Google Drive From Windows Paths"
excerpt: "This Article Describes Streamlining File Sharing: Using Dropbox/Google Drive From Windows Paths"
keywords: File Sharing Streamline,Cloud Storage Access,Path Integration Dropbox,Google Drive System Link,Windows File Transfer,Syncing Files Efficiently,Remote File Connectivity
thumbnail: https://thmb.techidaily.com/bf80edb76b200416e748e081aeadfa243850d855fed3e04f595dd2c29ba995d4.jpg
---

## Streamlining File Sharing: Using Dropbox/Google Drive From Windows Paths

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
<li><a href="https://audio-shaping.techidaily.com/harmonizing-without-spending-the-ultimate-selection-of-no-fee-audio-mixing-programs-for-2024/"><u>Harmonizing Without Spending - The Ultimate Selection of No-Fee Audio Mixing Programs for 2024</u></a></li>
<li><a href="https://apple-account.techidaily.com/troubleshooting-error-connecting-to-the-apple-id-server-from-iphone-13-pro-max-by-drfone-ios/"><u>Troubleshooting Error Connecting to the Apple ID Server From iPhone 13 Pro Max</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfecting-selectivity-enable-checkbox-file-option-in-win11/"><u>Perfecting Selectivity: Enable Checkbox File Option in Win11</u></a></li>
<li><a href="https://howto.techidaily.com/fix-app-not-available-in-your-country-play-store-problem-on-htc-u23-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix App Not Available in Your Country Play Store Problem on HTC U23 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-conquering-win-errors/"><u>The Ultimate Guide to Conquering Win Errors</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-2024-approved-a-beginners-guide-to-tell-you-what-3d-animation-is/"><u>Updated 2024 Approved A Beginners Guide to Tell You What 3D Animation Is</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-revive-network-router-page-on-windows/"><u>Methods to Revive Network Router Page on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-minecraft-glitches-with-these-fixes/"><u>Stop Minecraft Glitches with These Fixes</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-boosting-video-management-creating-an-effective-youtube-watch-later-list/"><u>[New] Boosting Video Management  Creating an Effective YouTube Watch Later List</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-unseen-resurrect-off-screen-windows-in-win1011/"><u>Unlock the Unseen: Resurrect Off-Screen Windows in Win10/11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-mastering-instagrams-newest-feature-reels-explained/"><u>[Updated] Mastering Instagram's Newest Feature  Reels Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-phone-call-basics-with-intel-unison/"><u>Mastering Windows 11: Phone Call Basics with Intel Unison</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-win11-space-to-perfection/"><u>Tailoring Your Win11 Space to Perfection</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-top-7-apps-altering-vocal-soundtracks/"><u>2024 Approved  Top 7 Apps Altering Vocal Soundtracks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-grades-with-these-top-8-windows-study-hacks/"><u>Skyrocket Grades with These Top 8 Windows Study Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/telnet-integration-in-modern-windows-11/"><u>Telnet Integration in Modern Windows 11</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-apples-finest-video-editing-software-for-creative-pros/"><u>2024 Approved Apples Finest Video Editing Software for Creative Pros</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-delight-in-facebooks-forgotten-meme-kingdoms-for-2024/"><u>[Updated] Delight in Facebook's Forgotten Meme Kingdoms for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-which-screen-recorder-excels-obs-or-fraps-in-2024/"><u>[Updated] Which Screen Recorder Excels  OBS or Fraps, In 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-vivo-y100t-location-on-twitter-drfone-by-drfone-virtual-android/"><u>How to Change your Vivo Y100t Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/achieving-peak-video-clarity-with-youtubes-tools-for-2024/"><u>Achieving Peak Video Clarity with YouTube's Tools for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unveiling-burst-function-in-gopro-cameras/"><u>In 2024, Unveiling Burst Function in GoPro Cameras</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-steps-to-correct-cannot-find-gpeditmsc-issue/"><u>Unveiling Steps to Correct Cannot Find Gpedit.msc Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapid-rectifications-quick-tricks-to-prevent-windows-crashes-in-games/"><u>Rapid Rectifications: Quick Tricks to Prevent Windows Crashes in Games</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-circle-everything-you-need-to-know-on-samsung-galaxy-s24plus-drfone-by-drfone-virtual-android/"><u>Life360 Circle Everything You Need to Know On Samsung Galaxy S24+ | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-premium-mobile-apps-for-slow-motion-video-iosandroid/"><u>In 2024, Premium Mobile Apps for Slow Motion Video iOS/Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-windows-11-keyboard-shortcuts-next-to-power-icon/"><u>Tailoring Windows 11: Keyboard Shortcuts Next to Power Icon</u></a></li>
<li><a href="https://extra-tips.techidaily.com/expert-endorsed-8-tripods-for-flawless-4k-footage/"><u>Expert-Endorsed 8 Tripods for Flawless 4K Footage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalize-your-windows-11-interface-with-these-tips/"><u>Revitalize Your Windows 11 Interface with These Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-secrets-efficient-qr-codes-on-windows-systems/"><u>Unlocking Secrets: Efficient QR Codes on Windows Systems</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-everything-you-need-to-know-about-lock-screen-settings-on-your-vivo-x90s-by-drfone-android/"><u>In 2024, Everything You Need to Know about Lock Screen Settings on your Vivo X90S</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-geforce-experience-setup-failure-windows-11-edition/"><u>Resolving GeForce Experience Setup Failure, Windows 11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-monitoring-integrating-system-resource-data-in-systray/"><u>Streamline Monitoring: Integrating System Resource Data in SysTray</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/top-rated-video-speed-adjustment-software-for-pc-and-mac/"><u>Top-Rated Video Speed Adjustment Software for PC and Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-hidden-pin-removal-switch-in-windows-11/"><u>Unlocking Hidden Pin Removal Switch in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-comics-an-intuitive-approach-for-win11-users/"><u>Navigating Comics: An Intuitive Approach for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tricks-for-rapid-download-experience-at-ms-store/"><u>Tricks for Rapid Download Experience at MS Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-new-waves-in-windows-unlocking-vivetools-secrets/"><u>Navigating New Waves in Windows: Unlocking ViVeTool's Secrets</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-unlock-6-figure-visibility-on-youtube-via-optimal-hashtags/"><u>In 2024, Unlock 6-Figure Visibility on YouTube via Optimal Hashtags</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-gamelog-analysts-guide-for-2024/"><u>[New] GameLog Analyst's Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-methodology-for-windows-update-reset/"><u>Stepwise Methodology for Windows Update Reset</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-correcting-severe-browser-js-problem-in-discord/"><u>Strategies for Correcting Severe Browser JS Problem in Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-0x8024800c-in-windows-update/"><u>Steps to Resolve 0X8024800C in Windows Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reboot-the-process-solving-hidden-logins-on-windows-11/"><u>Reboot the Process: Solving Hidden Logins on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essentials-of-epic-data-preservation-techniques/"><u>The Essentials of Epic Data Preservation Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-valorant-microphone-failures-on-windows-10/"><u>Overcoming Valorant Microphone Failures on Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-microsoft-store-blockage-issue-on-win11/"><u>Resolving Microsoft Store Blockage Issue on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-unidentified-window-second-screen/"><u>Resolving Unidentified Window Second Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/start-your-chatgpt-experience-windows-guide/"><u>Start Your ChatGPT Experience: Windows Guide</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-streamline-video-creation-incorporating-apples-siri-into-tiktok/"><u>[New] 2024 Approved  Streamline Video Creation  Incorporating Apple's Siri Into TikTok</u></a></li>
</ul></div>
