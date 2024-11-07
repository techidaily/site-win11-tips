---
title: Unzipping Files Proficiently Using PowerShell Commands
date: 2024-11-03T18:30:17.234Z
updated: 2024-11-07T02:27:14.157Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unzipping Files Proficiently Using PowerShell Commands
excerpt: This Article Describes Unzipping Files Proficiently Using PowerShell Commands
keywords: PowerShell File Unzip,Efficient Unzipper PS,Zip Extraction Scripts,PowerShell Decompression,PS File Handling,Automated File Untar,Streamlined Zipping Tools
thumbnail: https://thmb.techidaily.com/ad227a8d5363831d078e6323942af2a72809395f7bf85c351306cae77a65bd05.jpg
---

## Unzipping Files Proficiently Using PowerShell Commands

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1972684/19272" target="_top" id="1972684">
  <img src="//a.impactradius-go.com/display-ad/19272-1972684" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972684/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123735/7443" target="_top" id="2123735">
  <img src="//a.impactradius-go.com/display-ad/7443-2123735" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123735/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Unzip Files Using Command Prompt

 There may be situations where you want to[unzip files on your Windows computer](https://www.makeuseof.com/unzip-files-windows-10/) . Fortunately, you can do that as well using Command Prompt. Here's how:

1. Launch Command Prompt with admin privileges.
2. Use the**cd** command to head toward the zip file's location.
3. Type the following command and press**Enter** . Replace '**Name** ' with the name of the zip file.  
`tar -xf Name.zip`  
![Unzipping file in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping-file.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087234/19272" target="_top" id="2087234">
  <img src="//a.impactradius-go.com/display-ad/19272-2087234" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087234/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

You've successfully unzipped the file.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137393/7443" target="_top" id="2137393">
  <img src="//a.impactradius-go.com/display-ad/7443-2137393" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137393/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-explore-top-rated-windows-10-video-capture-software/"><u>[New] 2024 Approved Explore Top-Rated Windows 10 Video Capture Software</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-the-ultimate-guide-to-vlc-features-in-mac-os/"><u>[New] The Ultimate Guide to VLC Features in Mac OS</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-stepwise-approach-to-mastering-vimeo-recording/"><u>2024 Approved Stepwise Approach to Mastering Vimeo Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-straightforward-approach-to-discovering-ram-in-windows/"><u>A Straightforward Approach to Discovering RAM in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-boot-efficiency-with-windows-11-programs/"><u>Boosting Boot Efficiency with Windows 11 Programs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719373707174-check-physical-connections-make-sure-cables-are-firmly-connected-if-you-have-external-monitors-or-projectors-with-separate-brightness-controls/"><u>Check Physical Connections: Make Sure Cables Are Firmly Connected if You Have External Monitors or Projectors with Separate Brightness Controls.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/compute-discerning-window-systems-origins/"><u>Compute: Discerning Window Systems' Origins</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-to-oppo-a59-5g-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Oppo A59 5G FRP Bypass With Best Methods</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-samsung-galaxy-a23-5g-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Samsung Galaxy A23 5G to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-activate-and-use-life360-ghost-mode-on-samsung-galaxy-s24-drfone-by-drfone-virtual-android/"><u>In 2024, How To Activate and Use Life360 Ghost Mode On Samsung Galaxy S24 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-restrictions-and-unlocking-full-ram-potential/"><u>Overcoming Restrictions and Unlocking Full RAM Potential</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/perfecting-videos-a-premier-editor-for-vimeo-professionals-for-2024/"><u>Perfecting Videos A Premier Editor for Vimeo Professionals for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-resolving-unreachable-device-error-on-pc/"><u>Quick Guide: Resolving Unreachable Device Error on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-pc-gaming-with-yuzu-on-windows/"><u>Skyrocket PC Gaming with Yuzu on Windows</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/top-orbi-mesh-router-analysis-ultimate-guide-to-the-finest-wireless-range-extender/"><u>Top Orbi Mesh Router Analysis: Ultimate Guide to the Finest Wireless Range Extender</u></a></li>
<li><a href="https://extra-hints.techidaily.com/transform-your-content-simple-steps-to-change-numbers-on-tiktok/"><u>Transform Your Content Simple Steps to Change Numbers on TikTok</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-microphone-issues-live-recording-fixes-in-obs-w11/"><u>Troubleshooting Microphone Issues: Live Recording Fixes in OBS, W11</u></a></li>
</ul></div>

