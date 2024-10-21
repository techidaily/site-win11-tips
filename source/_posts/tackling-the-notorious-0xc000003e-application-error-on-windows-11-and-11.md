---
title: Tackling the Notorious 0xC000003E Application Error on Windows 11 & 11
date: 2024-10-19T02:51:11.783Z
updated: 2024-10-21T00:42:51.677Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling the Notorious 0xC000003E Application Error on Windows 11 & 11
excerpt: This Article Describes Tackling the Notorious 0xC000003E Application Error on Windows 11 & 11
keywords: Windows 11 Error Fix,C000003E Windows Bug,Win11 App Crash Repair,ZeroErrorWin11 Solution,0XC000003E Fix Guide,Windows XPe11 Application Errors,C000003E Win11 Troubleshooting
thumbnail: https://thmb.techidaily.com/80e5cdef4afad3cdaa6f71026bfd555865de3d18de62989f967049cc703431b5.jpg
---

## Tackling the Notorious 0xC000003E Application Error on Windows 11 & 11

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
<a href="https://appsumo.8odi.net/c/5597632/2111964/7443" target="_top" id="2111964">
  <img src="//a.impactradius-go.com/display-ad/7443-2111964" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111964/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Run the Compatibility Troubleshooter

 Error 0xc000003e can sometimes occur because of software compatibility issues. Windows has a Compatibility Troubleshooter that applies recommended compatibility settings for programs, which might help some users fix the 0xc000003e error. This is how you run that compatibility troubleshooter in Windows:

1. First, open the**Compatibility** tab for an affected program as instructed in steps one to three of this guide’s first potential resolution.
2. Click the**Run compatibility troubleshooter** button.
3. Select the**Try recommended settings** option.  
![The Try recommended settings option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/try-recommended-settings-option.jpg)
4. Press the**Test the program** button to see if the software works with recommended settings.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151864/7443" target="_top" id="2151864">
  <img src="//a.impactradius-go.com/display-ad/7443-2151864" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151864/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Test the program button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/test-the-program-button.jpg)
5. Select**Next** on the Program Compatibility Troubleshooter window.
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
<a href="https://appsumo.8odi.net/c/5597632/2130874/7443" target="_top" id="2130874">
  <img src="//a.impactradius-go.com/display-ad/7443-2130874" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130874/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Run an Antivirus Scan

 Malware is another possible cause for the error 0xc000003e. So, it’s recommended users manually run an antivirus scan in Windows. This is how you can run an antivirus scan with the built-in Windows Security utility:

1. Open Windows Security by double-clicking the system tray (shield) icon for that app.
2. Select the**Virus & threat protection** tab.  
![The Home tab in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-virus-threat-protection-tab.jpg)
3. Click**Scan options** to view all settings for scanning.  
![The Scan options navigation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-scan-options-link.jpg)
4. Select the radio button for the**Full scan** option.  
![The Full scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/full-scan-option.jpg)
5. Click**Scan now** to start the antivirus scanning.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105866/7443" target="_top" id="2105866">
  <img src="//a.impactradius-go.com/display-ad/7443-2105866" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105866/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Temporarily Turn Off Antivirus Protection

 It’s not uncommon for some third-party antivirus software to sound false positive alarms for legitimate software processes. Such incorrect detection can generate all kinds of startup errors for flagged programs. If you have installed a third-party antivirus utility, turn its shield off and then try launching any software for which error 0xc000003e occurs.

 How exactly you disable third-party antivirus utilities varies between apps. However, you can usually select to turn off antivirus tools from their context menus. Right-click a system tray icon for your antivirus package to see if its context menu includes an option for disabling its shield. If it does, select to turn off the shield for an hour or so.

## 7\. Reinstall the Program Affected With Error 0xc000003e

 The 0xc000003e error can also arise because of corrupted software installations. You can fix a corrupted software installation by reinstalling the app. Reinstalling will also ensure you have the latest app version, which can address compatibility issues.

 Uninstall the affected app with one of the methods in our guide on[how to uninstall software in Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) . The Control Panel’s**Program and Features** applet or**Apps & Features** within Settings will be sufficient for uninstalling most software.

 When you’ve uninstalled the software, download its latest version from the publisher’s website. Then you can reinstall the program by opening the downloaded setup wizard.

![The Programs and Features Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/programs-and-features-applet.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118320/7443" target="_top" id="2118320">
  <img src="//a.impactradius-go.com/display-ad/7443-2118320" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118320/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123740/7443" target="_top" id="2123740">
  <img src="//a.impactradius-go.com/display-ad/7443-2123740" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123740/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-crafting-the-ultimate-mc-community-dwellings/"><u>[New] 2024 Approved Crafting the Ultimate MC Community Dwellings</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-all-encompassing-clarification-the-basics-of-googles-podcast-platform/"><u>2024 Approved All-Encompassing Clarification The Basics of Google's Podcast Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/2024teki-zengin-uygulamalar-farkli-cesitli-video-vize-yayincilik-prodikti/"><u>2024'Teki Zengin Uygulamalar: Farklı Çeşitli Video Vize Yayıncılık Prodikti</u></a></li>
<li><a href="https://howto.techidaily.com/8-ultimate-fixes-for-google-play-your-realme-narzo-n55-isnt-compatible-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Ultimate Fixes for Google Play Your Realme Narzo N55 Isnt Compatible | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/business-video-editing-software-movavi-suite-and-screen-recording-solutions/"><u>Business Video Editing Software: Movavi Suite & Screen Recording Solutions</u></a></li>
<li><a href="https://unlock-android.techidaily.com/complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-infinix-note-30i-by-drfone-android/"><u>Complete Review & Guide to Techeligible FRP Bypass and More For Infinix Note 30i</u></a></li>
<li><a href="https://win11-tips.techidaily.com/converting-tiff-images-to-jpeg-format-free-easy-guide-with-movavi/"><u>Converting TIFF Images to JPEG Format Free - Easy Guide with Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-offline-vob-to-m4a-transformation-try-the-no-cost-movavi-solution/"><u>Easy Offline VOB to M4A Transformation - Try the No Cost Movavi Solution</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/exploring-ussd-what-you-need-to-know-about-unstructured-supplementary-service-data/"><u>Exploring USSD: What You Need to Know About Unstructured Supplementary Service Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guia-de-descarga-gratuita-para-convertir-archivos-avi-a-formato-m4a-con-convertidor-on-line-de-movavi/"><u>Guía De Descarga Gratuita Para Convertir Archivos AVI a Formato M4A Con Convertidor On-Line De Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/imovie-windows-pc-imovie/"><u>IMovie ใน Windows: เซ็ก컬 ไส้กระแท่ก ข้อสง่�ใน PC iMovie - ทักษะลึกซาก</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavi-convertidor-de-video-f4v-a-formatos-sin-costo-usar-online-gratis/"><u>Movavi: Convertidor De Vídeo F4V a Formatos Sin Costo - Usar Online Gratis</u></a></li>
<li><a href="https://review-topics.techidaily.com/play-mkv-movies-on-xiaomi-redmi-note-12-pro-4g-is-it-possible-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Play MKV movies on Xiaomi Redmi Note 12 Pro 4G, is it possible?</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/spread-the-rhythm-sharing-playlists-in-minutes/"><u>Spread the Rhythm Sharing Playlists in Minutes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-ranked-photography-slide-show-apps-windows-mac-and-web-options/"><u>Top-Ranked Photography Slide Show Apps : Windows, Mac & Web Options</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-unleash-your-creativity-easy-video-editing-with-gopro-quik-for-macbook/"><u>Updated Unleash Your Creativity Easy Video Editing with GoPro Quik for MacBook</u></a></li>
<li><a href="https://win-updates.techidaily.com/1728503771412-windows/"><u>コンピュータがWindows更新後に開始しないときの解決法</u></a></li>
</ul></div>

