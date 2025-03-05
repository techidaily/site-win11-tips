---
title: "Pro Tools: Proficiently Using PowerShell for Archive Operations"
date: 2025-02-28T02:31:30.970Z
updated: 2025-03-04T22:34:19.425Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Pro Tools: Proficiently Using PowerShell for Archive Operations"
excerpt: "This Article Describes Pro Tools: Proficiently Using PowerShell for Archive Operations"
keywords: Pro Tools PShell,PowerShell Archives,Archive Management PS,Efficient Archive PS,Archive PowerScripting,Proficient PSArchive,Advanced Shell Archiving
thumbnail: https://thmb.techidaily.com/e660cb7c486fc8d0b8cac52fbec26fad8dcc27b5b29050cd2236573beb2ecb06.jpg
---

## Pro Tools: Proficiently Using PowerShell for Archive Operations

 Are you running out of space on your Windows PC? The best thing you can do to free up some space is to compress big files through zipping. There are plenty of third-party tools that can come in handy in this situation.

 However, if you prefer to use Command Prompt or Windows PowerShell over anything else, there are commands you can use in these utilities to zip or unzip files. So, let's check out how to zip or unzip files using Command Prompt and Windows PowerShell.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

 There are several viable ways to[create zip files on Windows](https://www.makeuseof.com/easy-ways-create-zip-file-windows-10/) . One of these is through Windows PowerShell. However, the**tar** command doesn't work in Windows PowerShell; we'll use another command to get the work done.

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

 There may be situations where you want to[unzip files on your Windows computer](https://www.makeuseof.com/unzip-files-windows-10/) . Fortunately, you can do that as well using Command Prompt. Here's how:

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
<li><a href="https://vp-tips.techidaily.com/new-in-2024-how-to-download-vlc-player-for-free-and-safe-on-mac/"><u>[New] In 2024, How to Download VLC Player for Free and Safe on Mac?</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-in-2024-free-logo-blueprint-tailor-and-share-your-brand-identity/"><u>[Updated] In 2024, Free Logo Blueprint Tailor and Share Your Brand Identity</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-end-to-end-camera-rotation-explained/"><u>2024 Approved End-to-End Camera Rotation Explained</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-tailor-topical-laughs/"><u>2024 Approved Tailor Topical Laughs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypassing-update-interruption-a-comprehensive-guide-to-solving-error-0xc1900208-in-windows-10/"><u>Bypassing Update Interruption: A Comprehensive Guide to Solving Error 0Xc1900208 in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-compatibility-essential-wsl-2-advice-for-pcs/"><u>Conquer Compatibility: Essential WSL 2 Advice for PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-tackling-excessive-c-drive-data-usage/"><u>Efficiently Tackling Excessive C: Drive Data Usage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reinstate-accurate-battery-life-meter-on-pcs-running-win-11/"><u>How to Reinstate Accurate Battery Life Meter on PCs Running Win 11</u></a></li>
<li><a href="https://vp-tips.techidaily.com/listenlogic-evaluating-alternatives-to-dacast/"><u>ListenLogic Evaluating Alternatives to DaCast</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-photography-in-windows-11-building-impressive-slide-shows-and-fixes/"><u>Mastering the Art of Photography in Windows 11: Building Impressive Slide Shows & Fixes</u></a></li>
<li><a href="https://buynow-info.techidaily.com/monoprices-affordable-graphics-tablet-tested-top-features-low-cost/"><u>Monoprice's Affordable Graphics Tablet Tested: Top Features, Low Cost</u></a></li>
<li><a href="https://activate-lock.techidaily.com/new-guide-how-to-check-icloud-activation-lock-status-from-your-apple-iphone-13-pro-max-by-drfone-ios/"><u>New Guide How To Check iCloud Activation Lock Status From Your Apple iPhone 13 Pro Max</u></a></li>
<li><a href="https://games-able.techidaily.com/post-gtx-world-do-you-need-an-rtx-right-away/"><u>Post-GTX World: Do You Need an RTX Right Away?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proactive-device-management-in-system-sleep/"><u>Proactive Device Management in System Sleep</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-vanished-5ghz-connection-link-in-windows-11-swiftly/"><u>Restore Vanished 5GHz Connection Link in Windows 11 Swiftly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slash-clutter-a-fast-way-to-remove-bloatware-in-win11/"><u>Slash Clutter: A Fast Way to Remove Bloatware in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-stop-keyboard-use-for-computer-running-windows/"><u>Steps to Stop Keyboard Use for Computer Running Windows</u></a></li>
</ul></div>

