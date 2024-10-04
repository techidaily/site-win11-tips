---
title: How to Correctly Handle Missing Updates on Windows 10/8
date: 2024-09-29T01:10:29.665Z
updated: 2024-10-03T16:55:54.592Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Correctly Handle Missing Updates on Windows 10/8
excerpt: This Article Describes How to Correctly Handle Missing Updates on Windows 10/8
keywords: Update Issues Windows 10,Windows 10 Update Fix,Handling Windows Updates,Missing Windows 10 Updates,Resolve Windows 10 Update Error,Windows 8 Updates Correction,Fixing Updates in Windows OS
thumbnail: https://thmb.techidaily.com/f755ebc6fd74e541b86783b8f288eb9ebe73ceda235653be011e1c74d43e6c3e.jpg
---

## How to Correctly Handle Missing Updates on Windows 10/8

 It's not unusual for Windows users to run into issues when installing updates or upgrading to the latest version of Windows. The problem with these error codes is that most of the time, they do not specify the cause of the error or what users can do to avoid it.

 A common error that users run into when trying to update their system is 0x80070003\. This error is accompanied by a message stating "Some update files are missing." Let's explore the reasons behind this issue and the solutions you can try to resolve it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Are Update Files Missing From Your PC?

 One or more of the following reasons might explain why you are experiencing the problem on your computer:

1. The Windows log file might have corrupt data files that are interfering with the update installation process in Windows. The best way to deal with corrupt files is by repairing them using the built-in Windows utilities. If that does not work, you can delete them to resolve the problem.
2. The essential system files have become corrupt. This scenario can be resolved by running the troubleshooting utilities described below. They can identify corrupt files and replace them with healthy ones.
3. The Windows update components required for the pending updates to install are not functioning properly, which is causing the system to throw the error Fortunately, repairing the corrupt components is easy and can be done within a few minutes using the Command Prompt.
4. The Windows Update service and other relevant services required by the system to install the pending updates are disabled or have become corrupt. In this case, you can simply restart the services to resolve the issue.

 Now that you know what might be causing the problem let’s see how to resolve this case of missing update files in Windows.

## 1\. Delete the Contents of the DataStore Folder

 The DataStore folder in Windows is a log file that stores information about all the updates installed in the system. This folder is located in the SoftwareDistribution folder, which is a directory of update-related information in Windows.

 In several cases, the underlying issue was caused due to the corrupt components of the DataStore folder, which were interfering with the system’s update process. An easy way to resolve this issue is by deleting the contents of this folder or removing the Data Store folder as a whole. Both methods are safe to execute.

 We have described the steps for doing this below. However, if you do not want to delete the DataStore folder or its contents, you can also repair them. For that, follow the next method below.

1. Launch File Explorer and navigate to the following location below:  
`C:\Windows\SoftwareDistribution`  
![Software distribution](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-software-distribution.jpg)
2. Locate the**DataStore** folder in the SoftwareDistribution folder and right-click on it.
3. Choose**Delete** from the context menu.  
![Delete the DataStore folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/software-distribution-datastore-delete-1.jpg)
4. Click**Yes** in the confirmation prompt to proceed.

 Once the folder is deleted, open the Settings app and try installing the updates again.

## 2\. Run System Scans

 The next thing you can do is scan the system for potential issues. The best way to do this is by using built-in system utilities like the System File Checker and DISM.

 The System File Checker (SFC) will scan the protected system files for inconsistencies. If it finds a file that is corrupt, SFC will replace it with its healthier cached counterpart. DISM, on the other hand, will repair the system image.

 We will be using the Command Prompt to run these tools. Make sure you are logged into Windows as an administrator before proceeding:

Here is all that you need to do:

1. Open Command Prompt as an administrator (see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for instructions).
2. Click**Yes** in the User Account Control prompt.
3. In the Command Prompt window, type the command mentioned below and hit**Enter** .  
`sfc /scannow`  
![SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/sfc-scannow.jpg)
4. Wait for the command to execute, and then execute the following command:  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049379/7443" target="_top" id="2049379">
  <img src="//a.impactradius-go.com/display-ad/7443-2049379" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049379/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`Dism /Online /Cleanup-Image /ScanHealth`  
![DISM scanhealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/scanhealth.jpg)
5. Next, proceed with the following command:  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105859/7443" target="_top" id="2105859">
  <img src="//a.impactradius-go.com/display-ad/7443-2105859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105859/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`Dism /Online /Cleanup-Image /RestoreHealth`  
![DISM restorehealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/restorehealth.jpg)
6. Once this command is executed, close the Command Prompt window and check if you can now download the targeted updates.

 While you are at it, you can also[run the Windows Update troubleshooter](https://www.makeuseof.com/tag/windows-update-troubleshooter/) . This tool also works like the utilities we just described above. It will scan the system for errors and suggest you relevant fixes that can be applied using the troubleshooter as well.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012420/19272" target="_top" id="2012420">
  <img src="//a.impactradius-go.com/display-ad/19272-2012420" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012420/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Repair the Update Components

 As we mentioned earlier, the update components can also deal with some kind of corruption, leading to the problem under discussion.

 The good news is that repairing these components is quite simple, and we will also use the Command Prompt in this method. We recommend[creating a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed. This will help you revert to the current system state in case something goes wrong during the execution of the method.

Once the restore point is created, follow these steps:

1. Open a Run dialog box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) to learn how).
2. Type cmd in the text field of Run and press Ctrl + Shift + Enter to open Command Prompt as an administrator.
3. Click**Yes** in the User Account Control prompt.
4. Once you are inside the Command Prompt, execute the commands below one by one:  
`<code>net stop wuauserv  
net stop cryptSvc  
net stop bits  
net stop msiserver`  
``` `` ```
5. Once all the services are stopped, execute the following commands. These will clear the update cache in the system:  
`<code>ren %systemroot%\softwaredistribution softwaredistribution.bak  
ren %systemroot%\system32\catroot2 catroot2.bak`  
``` `` ```
6. Now, proceed with the following commands one by one to start the Windows update services again:  
`<code>net start wuauserv  
net start bits  
net start cryptsvc  
net start trustedinstaller  
net start appidsvc`  
![Restart the update services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/restart-the-services.jpg)
7. After the commands are executed, restart your computer. Hopefully, you will be able to install the pending updates on reboot.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144280/7443" target="_top" id="2144280">
  <img src="//a.impactradius-go.com/display-ad/7443-2144280" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144280/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get the Missing Update Files Back on Windows

 Hopefully, by now, you should have successfully resolved the annoying update error. In case you are still facing the issue, you can use the Microsoft update catalog to install the updates manually. It may also be a good idea to report this issue to the Microsoft support team so they can launch an official fix for the problem.

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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-masterful-use-of-digital-boards-in-web-meetings-across-appleandroid-and-laptops/"><u>[New] 2024 Approved Masterful Use of Digital Boards in Web Meetings Across Apple/Android & Laptops</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-from-beginner-to-expert-the-ultimate-guide-to-hp-screen-recording/"><u>[New] From Beginner to Expert The Ultimate Guide to HP Screen Recording</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-into-the-world-of-fraps-screenshots/"><u>[Updated] Into the World of Fraps Screenshots</u></a></li>
<li><a href="https://win11-tips.techidaily.com/12-best-free-video-compression-programs-top-picks-for-seamless-media-management/"><u>12 Best Free Video Compression Programs: Top Picks for Seamless Media Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavi-m4b-aac/"><u>最新の無料方法で：オンラインMovavi M4B AAC ビデオコンバートガイド</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/confirming-youtube-pro-rated-earnings-for-2024/"><u>Confirming YouTube Pro-Rated Earnings for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/expert-fixes-for-bypassing-csgo-login-problems-get-playing-now/"><u>Expert Fixes for Bypassing CSGO Login Problems - Get Playing Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-crop-tool-edit-your-videos-with-ease/"><u>Free Online Crop Tool: Edit Your Videos with Ease</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/hacks-to-do-pokemon-go-trainer-battles-for-itel-p55plus-drfone-by-drfone-virtual-android/"><u>Hacks to do pokemon go trainer battles For Itel P55+ | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-infinix-zero-5g-2023-turbo-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Infinix Zero 5G 2023 Turbo Without Password | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/motorcycle-video-magic-best-cam-hats-of-2023-selection-for-2024/"><u>Motorcycle Video Magic Best Cam Hats of 2023 Selection for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/online-vrijetijdige-mp4-in-m4a-vervanger-movavi-expertise-voor-duurzaamheid/"><u>Online Vrijetijdige MP4 in M4A Vervanger Movavi: Expertise Voor Duurzaamheid</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swf-webm/"><u>SWF WebM 전환기 - 웹에서 자원공유 용이: 실시간 코어 리소스를 모바일에 가장 적합한 형식으로 쉽게 전환</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-11-convertisseurs-mov-gratuits-pour-mac-windows-et-en-ligne-comparatif-complet/"><u>Top 11 Convertisseurs MOV Gratuits Pour Mac, Windows Et en Ligne : Comparatif Complet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trasforma-i-tuoi-video-wma-in-formato-3gp-senza-costi-utilizzando-il-servizio-di-movavi-online/"><u>Trasforma I Tuoi Video WMA in Formato #3GP Senza Costi Utilizzando Il Servizio Di Movavi Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ultimate-guide-to-standard-image-dimensions-expert-tips-from-movavi/"><u>Ultimate Guide to Standard Image Dimensions - Expert Tips From Movavi</u></a></li>
<li><a href="https://extra-hints.techidaily.com/unveiling-top-7-crypto-creators-for-nft-conversion/"><u>Unveiling Top 7 Crypto-Creators for NFT Conversion</u></a></li>
</ul></div>

