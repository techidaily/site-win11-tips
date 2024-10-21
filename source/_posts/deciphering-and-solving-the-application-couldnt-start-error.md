---
title: Deciphering and Solving The Application Couldn't Start Error
date: 2024-10-15T04:43:56.710Z
updated: 2024-10-20T16:28:06.463Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Deciphering and Solving The Application Couldn't Start Error
excerpt: This Article Describes Deciphering and Solving The Application Couldn't Start Error
keywords: Fixing Start App Error,Resolve App Launch Error,Stop App Not Starting Issue,Troubleshoot Start Error,Eliminate Application Failure,Tackle Init Error in Apps,Correct Start-Up Error
thumbnail: https://thmb.techidaily.com/78f06b81f7c57e1e88ac6a7fa4601f5ae07cf7d31be3889aa12b125cc68b1e89.jpg
---

## Deciphering and Solving The Application Couldn't Start Error

 Error 0xc000003e is among the more widely reported startup issues for Windows software packages. That error displays this message when users select to run recently installed software, “The application was unable to start correctly (0xc000003e).” As a result, users can’t open and utilize programs for which that error message pops up.

 The 0xc000003e error has been mostly reported for the Zoom and Discord apps, but it can arise for other software. It’s an issue that can occur on Windows 11, 10, and 8 platforms. Here are some probable resolutions for fixing the 0xc000003e error.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Set the Affected Software to Run With Admin Rights

 Firstly, try opening affected software with administrative rights. Some apps the 0xc000003e error occurs for might need more elevated permissions to operate. You can set the software to run as an administrator like this:

1. Open Windows Explorer and open the installation directly that includes the affected software.
2. Right-click the EXE (application) file for the software error 0xc000003e occurs and select**Properties** .
3. Then click**Compatibility** to access the settings below.  
![The Compatibility tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/compatibility-tab.jpg)
4. Select**Run this program as administrator** to set the program to run with elevated permissions.
5. Click**Apply** to save the selected options.
6. Press the**OK** button to exit the window.

<!-- affiliate ads begin -->
<span id="1938141">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938141.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938141">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938141.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938141%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938141/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Run the Compatibility Troubleshooter

 Error 0xc000003e can sometimes occur because of software compatibility issues. Windows has a Compatibility Troubleshooter that applies recommended compatibility settings for programs, which might help some users fix the 0xc000003e error. This is how you run that compatibility troubleshooter in Windows:

1. First, open the**Compatibility** tab for an affected program as instructed in steps one to three of this guide’s first potential resolution.
2. Click the**Run compatibility troubleshooter** button.
3. Select the**Try recommended settings** option.  
![The Try recommended settings option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/try-recommended-settings-option.jpg)
4. Press the**Test the program** button to see if the software works with recommended settings.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100530/7443" target="_top" id="2100530">
  <img src="//a.impactradius-go.com/display-ad/7443-2100530" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100530/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Test the program button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/test-the-program-button.jpg)
5. Select**Next** on the Program Compatibility Troubleshooter window.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118311/7443" target="_top" id="2118311">
  <img src="//a.impactradius-go.com/display-ad/7443-2118311" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118311/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Click**Yes, save these settings** if the**Test Program** option opened the software.  
![The Yes, save these settings option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/yes-option.jpg)
7. Close out of the troubleshooter, and restart your PC.

## 3\. Repair System Files

 System file corruption is one of the more regular causes of software startup errors in Windows. It’s recommended to run both Deployment Image Servicing and Management and System File Checker scans for repairing system files. A DISM scan can repair image component store corruption. These are the steps for running those scans in the Command Prompt:

1. Click the Windows taskbar’s search box or button (magnifying glass icon).
2. Type the search phrase**cmd** inside the text box.
3. Click**Command Prompt** with your mouse’s right button to select a**Run as administrator** option (see[how to run the Command Prompt as administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for more methods).
4. Then input this Prompt command and press**Return** :  
`DISM.exe /Online /Cleanup-image /Restorehealth`
5. Enter and execute the following SFC command:  
`sfc /scannow`  
![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-sfc-command.jpg)
6. Wait for the scan to reach a 100 percent mark and show a Windows Resource Protection outcome message.

## 4\. Run a Check Disk Scan

 You might need to fix error 0xc000003e because of a drive issue. There could be bad disk sectors on your PC’s hard drive that store data for affected software packages. Running a Check Disk (Chkdsk) scan could resolve such an issue. You can run such as scan with Windows’ Chkdsk utility as follows:

1. Bring up Command Prompt with administrative rights, as covered in resolution three.
2. Type in and execute this Chkdsk command:  
`chkdsk c: /f /r`
3. Press**Y** and**Enter** when prompted to schedule the scan for a restart.  
![A Chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/chkdsk-scan.jpg)
4. Next, select to restart Windows 11 or 10\. The Chkdsk utility will start its scanning after the restart.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105869/7443" target="_top" id="2105869">
  <img src="//a.impactradius-go.com/display-ad/7443-2105869" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105869/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137213/26400" target="_top" id="2137213">
  <img src="//a.impactradius-go.com/display-ad/26400-2137213" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137213/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Run an Antivirus Scan

 Malware is another possible cause for the error 0xc000003e. So, it’s recommended users manually run an antivirus scan in Windows. This is how you can run an antivirus scan with the built-in Windows Security utility:

1. Open Windows Security by double-clicking the system tray (shield) icon for that app.
2. Select the**Virus & threat protection** tab.  
![The Home tab in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-virus-threat-protection-tab.jpg)
3. Click**Scan options** to view all settings for scanning.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918684/19272" target="_top" id="1918684">
  <img src="//a.impactradius-go.com/display-ad/19272-1918684" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918684/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Scan options navigation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-scan-options-link.jpg)
4. Select the radio button for the**Full scan** option.  
![The Full scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/full-scan-option.jpg)
5. Click**Scan now** to start the antivirus scanning.

## 6\. Temporarily Turn Off Antivirus Protection

 It’s not uncommon for some third-party antivirus software to sound false positive alarms for legitimate software processes. Such incorrect detection can generate all kinds of startup errors for flagged programs. If you have installed a third-party antivirus utility, turn its shield off and then try launching any software for which error 0xc000003e occurs.

 How exactly you disable third-party antivirus utilities varies between apps. However, you can usually select to turn off antivirus tools from their context menus. Right-click a system tray icon for your antivirus package to see if its context menu includes an option for disabling its shield. If it does, select to turn off the shield for an hour or so.

## 7\. Reinstall the Program Affected With Error 0xc000003e

 The 0xc000003e error can also arise because of corrupted software installations. You can fix a corrupted software installation by reinstalling the app. Reinstalling will also ensure you have the latest app version, which can address compatibility issues.

 Uninstall the affected app with one of the methods in our guide on[how to uninstall software in Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) . The Control Panel’s**Program and Features** applet or**Apps & Features** within Settings will be sufficient for uninstalling most software.

 When you’ve uninstalled the software, download its latest version from the publisher’s website. Then you can reinstall the program by opening the downloaded setup wizard.

![The Programs and Features Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/programs-and-features-applet.jpg)

## 8\. Roll Back Windows With the System Restore Tool

 If you have System Restore enabled on your PC, that utility may provide a potential fix for 0xc000003e. System Restore enables you to roll Windows back to saved restoration points, which can fix corrupted system files. Selecting a restore point that predates the 0xc000003e error on your PC could fix the issue.

 Our guide on[how to create restore points on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) includes full instructions about how to roll back Windows with System Restore. Note that any software you installed after a selected restore point will not be available after rolling back Windows. You’ll need to reinstall the software packages removed for a chosen restoration point.

![The System Restore point tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-system-restore-point.jpg)

## Get Error 0xc000003e Sorted on Your PC

 So, that’s how you can get the 0xc000003e error sorted out in Windows 11 and 10\. We don’t promise those possible solutions will work for everybody. However, they’re some of the most likely ways to fix error 0xc000003e. Beyond those resolutions, clean booting and updating Windows might also help some users resolve error 0xc000003e.

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
<li><a href="https://extra-lessons.techidaily.com/new-choose-wisely-top-10-expert-picked-gopro-housing/"><u>[New] Choose Wisely Top 10 Expert-Picked GoPro Housing</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-harmonyhub-pro-downloads-and-reviews-for-2024/"><u>[New] HarmonyHub Pro Downloads & Reviews for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-convenient-chromebook-shot-techniques-method-4/"><u>[New] In 2024, Convenient Chromebook Shot Techniques (Method #4)</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-time-your-shots-perfectly-tips-for-instagrams-slow-motion/"><u>[New] In 2024, Time Your Shots Perfectly Tips for Instagram’s Slow Motion</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-earn-while-playing-games-online/"><u>[Updated] 2024 Approved Earn While Playing Games Online</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-create-a-youtube-music-playlist-on-web-and-mobile-a-detailed-guidance/"><u>[Updated] Create a YouTube Music Playlist on Web and Mobile - A Detailed Guidance</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-from-mobile-to-hard-drive-best-online-and-os-x-exporters-for-instagram-videos/"><u>[Updated] In 2024, From Mobile to Hard Drive Best Online and OS X Exporters for Instagram Videos</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-secrets-to-saving-and-sharing-your-roblox-experience-on-a-mac-for-2024/"><u>[Updated] Secrets to Saving & Sharing Your Roblox Experience on a Mac for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-realme-10t-5g-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Realme 10T 5G Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mp2avi-movavi/"><u>無限制使用的在線MP2與AVI媒體文件型式改變工具 – Movavi轉換器</u></a></li>
<li><a href="https://win11-tips.techidaily.com/aumentar-el-volumen-de-tu-video-guia-paso-a-paso-con-movavi/"><u>Aumentar El Volumen De Tu Video: Guía Paso a Paso Con Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-conversion-convert-webm-to-mov-using-movavis-web-service/"><u>Free Online Conversion: Convert WEBM to MOV Using Movavi's Web Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gratis-online-mov-to-3gp-converter-vrije-gratis-software-door-movavi/"><u>Gratis Online MOV-to-3GP Converter - Vrije Gratis Software Door Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gratuito-converter-de-filmes-wmv-para-formato-aiff-ferramentas-online-com-recomendacoes-da-movavi/"><u>Gratuito Converter De Filmes WMV Para Formato AIFF: Ferramentas Online Com Recomendações Da Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gratuito-online-conversor-de-video-wmv-para-desktop-moveit/"><u>Gratuito Online Conversor De Vídeo WMV Para Desktop - MoveIt!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavis-ultimate-guide-to-optimizing-your-obs-setup-for-professional-quality-streaming/"><u>Movavi's Ultimate Guide to Optimizing Your OBS Setup for Professional Quality Streaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/online-avi-to-ogv-kansbare-omzetting-gratis-door-movavi/"><u>Online AVI-to-OGV Kansbare Omzetting Gratis Door Movavi</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/score-a-steal-apple-m2-macbook-air-now-just-800-before-october-deals-kick-off-shoppers-alert/"><u>Score a Steal: Apple M2 MacBook Air Now Just $800 Before October Deals Kick Off - Shoppers Alert!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mp4trp-movavi/"><u>オンラインで簡単に変換！MP4ファイルを無料のTRPコードに - Movavi</u></a></li>
</ul></div>

