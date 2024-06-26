---
title: "Windows Utility Tips: Efficiently Handling Archived Files"
date: 2024-06-25T16:33:32.650Z
updated: 2024-06-26T16:33:32.650Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Utility Tips: Efficiently Handling Archived Files"
excerpt: "This Article Describes Windows Utility Tips: Efficiently Handling Archived Files"
keywords: Windows Archive Tips,File Management Windows,Archiving in Windows,Window's File Optimization,Quick Access Windows,Efficient File Handling,Windows Storage Solutions
thumbnail: https://thmb.techidaily.com/d03c6bda0db9e446c0d9464753859ee1c2f12f38d94da77b1f5b8b2204a1d875.jpg
---

## Windows Utility Tips: Efficiently Handling Archived Files

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
<li><a href="https://win11-tips.techidaily.com/8-hacks-for-instantaneous-iis-server-management-entry/"><u>8 Hacks for Instantaneous IIS Server Management Entry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-windows-system-secrets-generating-and-evaluating-reports/"><u>Unlock Windows System Secrets: Generating & Evaluating Reports</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-printing-at-your-fingertips-slow-printer-remedies-in-windows/"><u>Fast Printing at Your Fingertips: Slow Printer Remedies in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/take-full-advantage-of-windows-11-features/"><u>Take Full Advantage of Windows 11 Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-updater-setback-error-0x800f080a-on-windows-systems/"><u>Bypassing Updater Setback Error 0X800F080A on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-windows-11-visuality-with-app-sizing/"><u>Boosting Windows 11 Visuality with App Sizing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-no-cost-win-for-podcast-enthusiasts/"><u>The Ultimate No-Cost Win for Podcast Enthusiasts</u></a></li>
<li><a href="https://unlock-android.techidaily.com/best-ways-on-how-to-unlockbypassswiperemove-xiaomi-redmi-note-12-pro-5g-fingerprint-lock-by-drfone-android/"><u>Best Ways on How to Unlock/Bypass/Swipe/Remove Xiaomi Redmi Note 12 Pro 5G Fingerprint Lock</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-craft-instagram-visuals-mac-techniques-for-video-scaling/"><u>[Updated] Craft Instagram Visuals  Mac Techniques for Video Scaling</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-15-cinematic-royalty-free-piano-music-for-film-and-videos/"><u>Updated In 2024, 15 Cinematic Royalty Free Piano Music for Film and Videos</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-top-picks-superior-iphone-tone-creators/"><u>[Updated] Top Picks  Superior iPhone Tone Creators</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-8-valuable-image-ratio-changer-online-for-2024/"><u>New 8 Valuable Image Ratio Changer Online for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-find-your-match-top-rated-flac-converters-compared-for-2024/"><u>New Find Your Match Top-Rated FLAC Converters Compared for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-co-singers-capturing-hearts-online/"><u>[New] 2024 Approved  Co-Singers Capturing Hearts Online</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-how-to-effortlessly-eradicate-unwanted-youtube-post-comments/"><u>[Updated] In 2024, How to Effortlessly Eradicate Unwanted Youtube Post-Comments</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-unleash-creative-potential-with-top-tips-for-gopro-timelapses/"><u>[New] 2024 Approved  Unleash Creative Potential with Top Tips for GoPro Timelapses</u></a></li>
</ul></div>
