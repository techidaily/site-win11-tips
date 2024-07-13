---
title: Optimizing File Operations in PowerShell & Command Prompt
date: 2024-07-12T17:40:24.273Z
updated: 2024-07-13T17:40:24.273Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Optimizing File Operations in PowerShell & Command Prompt
excerpt: This Article Describes Optimizing File Operations in PowerShell & Command Prompt
keywords: PowerShell File Optimization,PS Command Speed,Efficient PS Scripts,Command Prompt Performance,Enhance File Access,Streamlined Data Transfers,PowerShell File Operations
thumbnail: https://thmb.techidaily.com/9be334cdafc76019f9e5ad788ad6c3507c69da5b07f01ac5528173fed7156fb9.jpg
---

## Optimizing File Operations in PowerShell & Command Prompt

 Are you running out of space on your Windows PC? The best thing you can do to free up some space is to compress big files through zipping. There are plenty of third-party tools that can come in handy in this situation.

 However, if you prefer to use Command Prompt or Windows PowerShell over anything else, there are commands you can use in these utilities to zip or unzip files. So, let's check out how to zip or unzip files using Command Prompt and Windows PowerShell.

## How to Zip Files Using Command Prompt

 You can zip files through Command Prompt using the tar command. It's a command line tool that helps you to extract files and create archives. However, this command only works in Windows 10 or later.

Here's how to zip files using Command Prompt:

1. Open the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Command Prompt** and**Run as administrator** from the right pane.
3. In the console, type the following command and press**Enter** . Replace**'Place'** with the location of the file.  
`cd Place`  
![Place of the file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/place.jpg)
4. Type**dir** and press**Enter** . It'll show the files inside the selected folder.  
![Dir command in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dir.jpg)
5. To zip all the files inside the selected folder, type the following command and press**Enter** . Replace '**Compressed** ' with the name you want to give your folder where the zip file will be stored. Also, replace '**FileExt** ' with the extension of the file you're zipping.  
`tar -a -c -f Compressed.zip *.FileExt`  
![Tar command in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tar.jpg)
6. To zip a single file, execute the following command. Again, replace '**Compressed** ' with the name you want to give your folder where the zip file will be stored, '**FileExt** ' with your file's extension, and '**FileName** ' with the name of the file you want to zip.  
`tar -a -c -f Compressed.zip FileName.FileExt`  
![Compressing one file in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/compressing-one-file.jpg)

## How to Zip Files Using Windows PowerShell

 There are several viable ways to [create zip files on Windows](https://www.makeuseof.com/easy-ways-create-zip-file-windows-10/) . One of these is through Windows PowerShell. However, the**tar** command doesn't work in Windows PowerShell; we'll use another command to get the work done.

Here's how to zip files using Windows PowerShell:

1. Open the Start Menu, type**Windows PowerShell,** and choose Run as administrator from the right pane.
2. In the console, type the following command and press**Enter** . Ensure to replace**file destination** and**target location** with the location of the file and the place where you want the file to be zipped, respectively. Also, replace**file name** with the name of the file you want to zip and**destination name** with the destination folder name.  
`Compress-Archive -LiteralPath 'file destination\file name' -DestinationPath 'target location\destination name'`  
![Zipping command in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/zipping.jpg)

 If you want to zip multiple files, execute the following command. Replace**file destination** and**file destination 1** with the location of the first and second files, respectively. And replace**file name** and**file name 2** with the first and second file names.

`Compress-Archive -LiteralPath 'file destination\file name', 'file destination 1\file name 2 -DestinationPath 'target location\destination name'  
`

![Zipping 2 files at once](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/zipping-2.jpg)

## How to Unzip Files Using Command Prompt

 There may be situations where you want to [unzip files on your Windows computer](https://www.makeuseof.com/unzip-files-windows-10/) . Fortunately, you can do that as well using Command Prompt. Here's how:

1. Launch Command Prompt with admin privileges.
2. Use the**cd** command to head toward the zip file's location.
3. Type the following command and press**Enter** . Replace '**Name** ' with the name of the zip file.  
`tar -xf Name.zip`  
![Unzipping file in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping-file.jpg)

You've successfully unzipped the file.

## How to Unzip Files Using Windows PowerShell

 Windows PowerShell lets you quickly unzip files on your computer. Here's how to do that:

1. Open Windows PowerShell with admin rights.
2. Type the following command and press**Enter** . Make sure to replace <**file** **destination** \> and <**target** **location** \> with the location of the zip file and the place where you want the file to be unzipped, respectively.  
`Expand-Archive -LiteralPath <file destination> -DestinationPath <target location>`  
![Unzipping file in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping.jpg)

## Save Up Space on Windows 11 by Zipping Your Files

 As a Windows user, you will always come across situations where you want to zip or unzip files. However, if you don't want to use a third-party tool, you can use Command Prompt and Windows PowerShell to quickly zip and unzip files on Windows using the above methods.

 Meanwhile, you might be interested in learning a few important Command Prompt commands.


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
<li><a href="https://some-approaches.techidaily.com/new-the-ultimate-guide-to-audio-selection-in-video-unboxing/"><u>[New] The Ultimate Guide to Audio Selection in Video Unboxing</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-complete-transformation-handbook-using-morphvox-tech/"><u>[New] Complete Transformation Handbook Using MorphVOX Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-detailed-how-to-for-hypertuned-windows-11-homes/"><u>A Detailed How-To for Hypertuned Windows 11 Homes</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-thrifty-approaches-to-youtube-video-card-production/"><u>[Updated] Thrifty Approaches to YouTube Video Card Production</u></a></li>
<li><a href="https://howto.techidaily.com/super-easy-ways-to-deal-with-realme-v30-unresponsive-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Super Easy Ways To Deal with Realme V30 Unresponsive Screen | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719296093582-restore-your-shift-keys-functionality/"><u>Restore Your Shift Key's Functionality.</u></a></li>
<li><a href="https://article-tips.techidaily.com/unveiling-the-best-voice-alteration-programs-for-vtubers/"><u>Unveiling the Best Voice Alteration Programs for VTubers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-easy-ways-to-check-your-ram-type-on-windows/"><u>4 Easy Ways to Check Your RAM Type on Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/planning-to-use-a-pokemon-go-joystick-on-lava-agni-2-5g-drfone-by-drfone-virtual-android/"><u>Planning to Use a Pokemon Go Joystick on Lava Agni 2 5G? | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/gain-traction-the-definitive-guide-to-top-trending-tiktok-hashes-for-2024/"><u>Gain Traction  The Definitive Guide to Top Trending TikTok Hashes for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-ways-to-fix-a-reappearing-deleted-file-or-folder-on-windows/"><u>8 Ways to Fix a Reappearing Deleted File or Folder on Windows</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-calculating-image-dimensions-a-simple-and-accurate-method-for-2024/"><u>New Calculating Image Dimensions A Simple and Accurate Method for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-to-customize-your-laptops-touchpads/"><u>A Step-by-Step to Customize Your Laptop's Touchpads</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-htc-u23-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use GPS Joystick to Fake GPS Location On HTC U23 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/address-unsigned-files-issue-for-updated-pcs/"><u>Address 'Unsigned' Files Issue for Updated PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-strategies-to-fix-failed-security-codes-from-epic-games-on-windows/"><u>7 Strategies to Fix Failed Security Codes From Epic Games on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719353940627-resolve-icloud-install-issues-on-windows-quickly/"><u>Resolve iCloud Install Issues on Windows Quickly!</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-expert-tips-for-high-quality-minecraft-saves/"><u>[New] In 2024, Expert Tips for High-Quality Minecraft Saves</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-unlocking-windows-11s-credential-vault/"><u>A Comprehensive Guide to Unlocking Windows 11’S Credential Vault</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-microsoft-edge-fix-for-w10w11/"><u>Accelerate Your Microsoft Edge: Fix for W10/W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-visual-journey-customizing-your-windows-11-monitor-walls/"><u>A Visual Journey: Customizing Your Windows 11 Monitor Walls</u></a></li>
<li><a href="https://windows11.techidaily.com/disregard-met-not-fulfilled-emblem-on-win11/"><u>Disregard Met Not Fulfilled Emblem on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-key-steps-to-resolve-epic-launcher-security-code-errors-on-windows/"><u>7 Key Steps to Resolve Epic Launcher Security Code Errors on Windows</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-cyberspace-cinema-collector/"><u>2024 Approved  Cyberspace Cinema Collector</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-walkthrough-windows-11-sandbox-setup/"><u>A Comprehensive Walkthrough: Windows 11 Sandbox Setup</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-edit-mp4-on-mac-mavericks-a-comprehensive-video-editing-guide/"><u>New 2024 Approved Edit MP4 on Mac Mavericks A Comprehensive Video Editing Guide</u></a></li>
<li><a href="https://some-tips.techidaily.com/the-science-behind-whatsapp-voice-talks-for-2024/"><u>The Science Behind WhatsApp Voice Talks for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessibility-enhanced-with-shortcuts-for-microsoft-store-uwp/"><u>Accessibility Enhanced with Shortcuts for Microsoft Store UWP</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/a-comprehensive-guide-downloading-from-instagram-to-iphone-for-2024/"><u>A Comprehensive Guide  Downloading From Instagram to iPhone for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/actions-to-take-when-facing-invalid-name-on-pc/"><u>Actions to Take When Facing Invalid Name on PC</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/top-10-best-spy-watches-for-your-apple-iphone-se-2020-drfone-by-drfone-virtual-ios/"><u>Top 10 Best Spy Watches For your Apple iPhone SE (2020) | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-premier-video-logger-focused-on-windows-11/"><u>In 2024, Premier Video Logger, Focused on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-thoroughly-detailed-guide-to-windows-boot-options/"><u>A Thoroughly Detailed Guide to Windows Boot Options</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-audfreetech-a-deep-dive-into-audio-file-liberation-techniques/"><u>In 2024, AudFreeTech  A Deep Dive Into Audio File Liberation Techniques</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-master-content-creation-video-and-photo-synergy/"><u>In 2024, Master Content Creation  Video & Photo Synergy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-strategy-to-reactivate-winget-on-w11/"><u>A Step-by-Step Strategy to Reactivate Winget on W11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-innovating-your-gaming-experience-capturing-ps3-playthroughs/"><u>[Updated] Innovating Your Gaming Experience  Capturing PS3 Playthroughs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-incorrect-parameter-loaderror-87/"><u>Addressing Incorrect Parameter LoadError 87</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-num-caps-lock-signifiers-in-win11-systemtray/"><u>Adding Num, Caps Lock Signifiers in Win11 SystemTray</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-pixel-perfect-video-modifier/"><u>2024 Approved  Pixel-Perfect Video Modifier</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-msvcrt120dll-omission-on-pcs/"><u>Addressing Msvcrt120dll Omission on PCs</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-top-picks-for-zero-price-mp3-fusion-technology/"><u>New Top Picks for Zero-Price MP3 Fusion Technology</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-key-components-not-found-error-in-win11-environment/"><u>Addressing Key Components Not Found Error in Win11 Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-crucial-modifications-to-revolutionize-the-windows-11-taskbar/"><u>6 Crucial Modifications to Revolutionize the Windows 11 Taskbar</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-discover-the-top-educational-animation-platforms/"><u>2024 Approved Discover the Top Educational Animation Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-windows-11s-network-settings/"><u>Accessing Windows 11'S Network Settings</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-how-to-mass-download-tiktok-videos/"><u>[New] How To Mass Download TikTok Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-secure-windows-strategies-when-bitlocker-fails/"><u>5 Secure Windows Strategies When Bitlocker Fails</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-ui-skills-with-windows-11-widgets/"><u>Accelerate Your UI Skills with Windows 11 Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-methods-for-removing-a-disks-partition-in-windows/"><u>3 Methods for Removing a Disk's Partition in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-taskbar-icon-glitches-in-win-108/"><u>Addressing Taskbar Icon Glitches in Win 10/8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-compre-cookie-cutter-guide-to-revamping-your-pc-with-a-fresh-os/"><u>A Compre Cookie-Cutter Guide to Revamping Your PC with a Fresh OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-ways-to-fix-video-stuttering-issues-on-windows/"><u>9 Ways to Fix Video Stuttering Issues on Windows</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-complete-guidebook-to-evaluating-your-videos-impact-and-earning-power/"><u>[New] 2024 Approved  Complete Guidebook to Evaluating Your Video's Impact and Earning Power</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-full-guide-to-unlock-your-realme-c33-2023-by-drfone-android/"><u>In 2024, Full Guide to Unlock Your Realme C33 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-simple-guide-to-windows-11-home-interface-activation/"><u>A Simple Guide to Windows 11 Home Interface Activation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719289062860-rescue-your-browser-fix-google-chrome-in-w11-today/"><u>Rescue Your Browser: Fix Google Chrome in W11 Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-battery-performance-add-custom-alerts-to-windows-11/"><u>Accelerating Battery Performance: Add Custom Alerts to Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comparative-look-at-windows-most-utilized-software-tools/"><u>A Comparative Look at Windows' Most Utilized Software Tools</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-masterclass-in-visualization-perfectly-cropped-instagram-videos-for-2024/"><u>[Updated] Masterclass in Visualization  Perfectly Cropped Instagram Videos for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/perfect-guide-for-linking-instagram-to-tiktok/"><u>Perfect Guide for Linking Instagram to TikTok</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-locked-windows-11-themes-through-registry-expertise/"><u>Accessing Locked Windows 11 Themes Through Registry Expertise</u></a></li>
</ul></div>
