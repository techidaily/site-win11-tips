---
title: Optimizing File Operations in PowerShell & Command Prompt
date: 2024-06-25T17:07:22.635Z
updated: 2024-06-26T17:07:22.635Z
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
<li><a href="https://win11-tips.techidaily.com/redefine-your-digital-space-with-win-11-sketching-techniques/"><u>Redefine Your Digital Space with Win 11 Sketching Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-bypass-oculus-setup-failures-in-windows-1110/"><u>Quick Guide to Bypass Oculus Setup Failures in Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reestablishing-credible-power-consumption-forecasts-in-win-11-setup/"><u>Reestablishing Credible Power Consumption Forecasts in Win 11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-nvidia-control-panel-access-denied-error-in-windows-1110/"><u>How to Fix the NVIDIA Control Panel “Access Denied” Error in Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-the-uninitialized-drive-message-on-pc/"><u>Dealing with the 'Uninitialized Drive' Message on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assisting-users-with-erratic-gesture-inputs-in-windows/"><u>Assisting Users with Erratic Gesture Inputs in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-system-fatal-c0000022-error/"><u>Resolving Windows System Fatal C0000022 Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-the-no-image-preview-error-in-your-windows-11-environment/"><u>Fix the No Image Preview Error in Your Windows 11 Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-windows-11-boot-tracks-step-by-step-guide/"><u>Clearing Windows 11 Boot Tracks: Step-by-Step Guide</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-top-strategies-for-finding-and-using-a-lost-iphone-x/"><u>2024 Approved  Top Strategies for Finding & Using a Lost iPhone X</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-unlimited-editing-discover-these-9-free-cloud-tools/"><u>In 2024, Unlimited Editing  Discover These 9 Free Cloud Tools</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-the-truth-behind-instas-video-selfie-authenticity-check/"><u>[New] The Truth Behind Insta's Video Selfie Authenticity Check</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-style-sleuths-influential-beauty-creators/"><u>2024 Approved  Style Sleuths  Influential Beauty Creators</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-plot-craft-guild-bestowed-batch/"><u>2024 Approved  Plot Craft Guild - Bestowed Batch</u></a></li>
<li><a href="https://android-location.techidaily.com/easy-ways-to-manage-your-vivo-s17t-location-settings-drfone-by-drfone-virtual/"><u>Easy Ways to Manage Your Vivo S17t Location Settings | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/savor-the-spectacle-best-practices-for-cooking-channel-titling-for-2024/"><u>Savor the Spectacle  Best Practices for Cooking Channel Titling for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/maximize-views-the-ultimate-youtube-thumbnail-template-and-tips/"><u>Maximize Views The Ultimate YouTube Thumbnail Template and Tips</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/amplification-of-combined-enthusiasm-trend/"><u>Amplification of Combined Enthusiasm Trend</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-easy-guide-how-to-bypass-samsung-galaxy-m14-4g-frp-android-10111213-by-drfone-android/"><u>In 2024, Easy Guide How To Bypass Samsung Galaxy M14 4G FRP Android 10/11/12/13</u></a></li>
</ul></div>
