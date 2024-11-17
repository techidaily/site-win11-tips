---
title: "Efficient File Handling: Zipping with CLI Tools on Windows OS"
date: 2024-11-15T20:20:37.890Z
updated: 2024-11-17T16:22:36.293Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Efficient File Handling: Zipping with CLI Tools on Windows OS"
excerpt: "This Article Describes Efficient File Handling: Zipping with CLI Tools on Windows OS"
keywords: ZipWindowsCLI,EfficientFileZip,CLIZippingWin,OptimizeFileSave,CommandLineArchive,FileCompressionTool,WindowsZIPCLI
thumbnail: https://thmb.techidaily.com/07e687f8419c4806cb630c22e1fb9dad31142326727645ceb99c557de0c60728.jpg
---

## Efficient File Handling: Zipping with CLI Tools on Windows OS

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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136614/26400" target="_top" id="2136614">
  <img src="//a.impactradius-go.com/display-ad/26400-2136614" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136614/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Zip Files Using Windows PowerShell

 There are several viable ways to[create zip files on Windows](https://www.makeuseof.com/easy-ways-create-zip-file-windows-10/) . One of these is through Windows PowerShell. However, the**tar** command doesn't work in Windows PowerShell; we'll use another command to get the work done.

Here's how to zip files using Windows PowerShell:

1. Open the Start Menu, type**Windows PowerShell,** and choose Run as administrator from the right pane.
2. In the console, type the following command and press**Enter** . Ensure to replace**file destination** and**target location** with the location of the file and the place where you want the file to be zipped, respectively. Also, replace**file name** with the name of the file you want to zip and**destination name** with the destination folder name.  
`Compress-Archive -LiteralPath 'file destination\file name' -DestinationPath 'target location\destination name'`  
![Zipping command in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/zipping.jpg)

<!-- affiliate ads begin -->
<span id="1982462">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982462.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982462">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982462.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982462%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982462/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to zip multiple files, execute the following command. Replace**file destination** and**file destination 1** with the location of the first and second files, respectively. And replace**file name** and**file name 2** with the first and second file names.

`Compress-Archive -LiteralPath 'file destination\file name', 'file destination 1\file name 2 -DestinationPath 'target location\destination name'  
`

![Zipping 2 files at once](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/zipping-2.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657396/16446" target="_top" id="1657396">
  <img src="//a.impactradius-go.com/display-ad/16446-1657396" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657396/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Unzip Files Using Command Prompt

 There may be situations where you want to[unzip files on your Windows computer](https://www.makeuseof.com/unzip-files-windows-10/) . Fortunately, you can do that as well using Command Prompt. Here's how:

1. Launch Command Prompt with admin privileges.
2. Use the**cd** command to head toward the zip file's location.
3. Type the following command and press**Enter** . Replace '**Name** ' with the name of the zip file.  
`tar -xf Name.zip`  
![Unzipping file in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping-file.jpg)

You've successfully unzipped the file.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123748/7443" target="_top" id="2123748">
  <img src="//a.impactradius-go.com/display-ad/7443-2123748" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123748/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://youtube-docs.techidaily.com/ed-mastering-chapter-division-in-youtube-videos/"><u>[Updated] Mastering Chapter Division in YouTube Videos</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-nostalgia-revue-old-school-review-of-the-goofys/"><u>[Updated] Nostalgia Revue Old-School Review of The Goofys</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-the-definitive-guide-to-10-premium-vector-stockplaces/"><u>2024 Approved The Definitive Guide to 10 Premium Vector Stockplaces</u></a></li>
<li><a href="https://screen-capture.techidaily.com/budget-friendly-video-recording-tools-for-pcs-for-2024/"><u>Budget-Friendly Video Recording Tools for PCs for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/enhancing-imagery-add-filters-to-videos-on-devices/"><u>Enhancing Imagery Add Filters to Videos on Devices</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/free-high-quality-srt-translation-services-1-8-for-2024/"><u>Free, High-Quality SRT Translation Services – #1-#8 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-do-cloud-and-disk-based-windows-reinstallation-vary/"><u>How Do Cloud and Disk-Based Windows Reinstallation Vary?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-windows-11s-zero-error-hurdle/"><u>Mastery over Windows 11'S Zero-Error Hurdle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shifting-screen-placement-in-windows-1011/"><u>Shifting Screen Placement in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stabilize-your-windows-pointer-instantly-quick-solution/"><u>Stabilize Your Windows Pointer Instantly! Quick Solution</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/the-secrets-to-unforgettable-borders-in-your-instagram-shots/"><u>The Secrets to Unforgettable Borders in Your Instagram Shots</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tidying-up-faulty-recycle-bins-with-windows-11/"><u>Tidying Up Faulty Recycle Bins with WIndows 11</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/toms-tech-specs-a-comprehensive-guide-to-hardware-mastery/"><u>Tom's Tech Specs: A Comprehensive Guide to Hardware Mastery</u></a></li>
<li><a href="https://location-social.techidaily.com/top-7-skype-hacker-to-hack-any-skype-account-on-your-vivo-g2-drfone-by-drfone-virtual-android/"><u>Top 7 Skype Hacker to Hack Any Skype Account On your Vivo G2 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-windows-emailcalendar-by-adding-fav-photos/"><u>Transform Windows' Email/Calendar by Adding Fav Photos</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshoot-fast-effective-remedies-for-oculus-rift-s-microphone-issues/"><u>Troubleshoot Fast: Effective Remedies for Oculus Rift S Microphone Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-overcoming-windows-0x80070003-file-updater-error/"><u>Troubleshooting: Overcoming Windows' 0X80070003 File Updater Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unzipping-files-proficiently-using-powershell-commands/"><u>Unzipping Files Proficiently Using PowerShell Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrading-your-devices-defense-extend-pin-code-on-win11/"><u>Upgrading Your Device's Defense: Extend Pin Code on Win11</u></a></li>
</ul></div>

