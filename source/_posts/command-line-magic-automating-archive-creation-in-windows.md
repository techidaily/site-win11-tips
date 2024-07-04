---
title: "Command Line Magic: Automating Archive Creation in Windows"
date: 2024-06-25T16:08:28.718Z
updated: 2024-06-26T16:08:28.718Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Command Line Magic: Automating Archive Creation in Windows"
excerpt: "This Article Describes Command Line Magic: Automating Archive Creation in Windows"
keywords: Command Line Tricks,Archive Automation Win,Archiving Scripts CMD,File Management CLI,Windows Archive Tool,Magic Command Utility,Efficient Data Extract
thumbnail: https://thmb.techidaily.com/b88c99aa3c51aa4517857e5b79893f53f6ca04daaffc99f79faac8fc9b5eb352.jpg
---

## Command Line Magic: Automating Archive Creation in Windows

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
<li><a href="https://win11-tips.techidaily.com/reclaiming-control-over-typing-with-these-9-fixes-for-broken-keyboard-commands-on-windows-pc/"><u>Reclaiming Control over Typing with These 9 Fixes for Broken Keyboard Commands on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-quick-ways-to-check-your-graphics-card-model-on-windows-11/"><u>3 Quick Ways to Check Your Graphics Card Model on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-no-more-files-errors-in-win-11/"><u>Eliminating 'No More Files' Errors in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-windows-11-login-issues-without-screen-display/"><u>Clear Windows 11 Login Issues Without Screen Display</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securely-building-win11-self-extractables/"><u>Securely Building Win11 Self-Extractables</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-pin-removal-functionality-in-windows-11-os/"><u>Restoring PIN Removal Functionality in Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-the-windows-application-net-error-message/"><u>Correcting the Windows Application .NET Error Message</u></a></li>
<li><a href="https://win11-tips.techidaily.com/captivating-christmas-vistas-with-window-artistry/"><u>Captivating Christmas Vistas with Window Artistry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-the-power-extracting-device-ids-in-windows/"><u>Unleashing the Power: Extracting Device IDs in Windows</u></a></li>
<li><a href="https://review-topics.techidaily.com/play-mkv-movies-on-motorola-moto-g-5g-2023-is-it-possible-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Play MKV movies on Motorola Moto G 5G (2023), is it possible?</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-mastering-wide-angle-postings-integrating-360-photos-on-mobile-apps/"><u>[New] In 2024, Mastering Wide Angle Postings  Integrating 360 Photos on Mobile Apps</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-noble-recorders-crafted-for-games/"><u>[New] In 2024, Noble Recorders Crafted for Games</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-achieve-professionally-styled-images-top-10-luts-in-lightroom/"><u>[New] Achieve Professionally Styled Images  Top 10 LUTs in LightRoom</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-navigating-the-aspect-ratio-maze-for-twitter-media/"><u>2024 Approved  Navigating the Aspect Ratio Maze for Twitter Media</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-shrink-mpeg2-files-get-virtualdub-for-video-compression/"><u>In 2024, Shrink MPEG2 Files Get VirtualDub for Video Compression</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-samsung-galaxy-s23plus-phone-without-any-data-loss-by-drfone-android/"><u>How to Unlock Samsung Galaxy S23+ Phone without Any Data Loss</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-do-i-stop-someone-from-tracking-my-vivo-y100t-drfone-by-drfone-virtual-android/"><u>In 2024, How Do I Stop Someone From Tracking My Vivo Y100t? | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-leading-directory-of-cost-free-online-resources-for-superior-vector-graphics/"><u>In 2024, Leading Directory of Cost-Free Online Resources for Superior Vector Graphics</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-practical-demonstrations-creating-and-configuring-timer-modules-in-obs-for-2024/"><u>[New] Practical Demonstrations  Creating and Configuring Timer Modules in OBS for 2024</u></a></li>
</ul></div>
