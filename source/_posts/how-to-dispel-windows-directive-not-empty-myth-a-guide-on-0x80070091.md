---
title: "How to Dispel Windows' Directive Not Empty Myth: A Guide on 0X80070091"
date: 2024-10-13T21:35:54.618Z
updated: 2024-10-20T18:33:32.444Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes How to Dispel Windows' Directive Not Empty Myth: A Guide on 0X80070091"
excerpt: "This Article Describes How to Dispel Windows' Directive Not Empty Myth: A Guide on 0X80070091"
keywords: Dispel 0X80070091,Overcoming 0X80070091 Error,Directive Not Empty Help,Fixing Windows Myth,0X80070091 Resolution Guide,Empty Disk Misconception,Clearing 0X80070091
thumbnail: https://thmb.techidaily.com/b865d1fe2bcace495751c454db93866647380420be6c31ae58cdceea73012a33.jpg
---

## How to Dispel Windows' Directive Not Empty Myth: A Guide on 0X80070091

 Error 0x80070091 is a File Explorer issue that occurs for some users when they try to delete folders in Windows 11/10\. The error message says, “The directory is not empty," and you can't delete the folder that throws the error.

 The 0x80070091 message suggests that the error occurs because a folder isn’t empty. Yet, you should be able to erase directories that contain files without any issues. Furthermore, that error can also arise for empty folders. If you’re seeing the same folder error 0x80070091 in Windows, try applying these potential fixes.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Try Erasing the Folder With the Command Prompt

 The Command Prompt gives users another way to delete folders in Windows 11/10\. So, you might be able to erase an affected folder without issues by using the Command Prompt. Using the Command Prompt might be more of a workaround, but at least you’ll get the folder deleted if works.

 Run Command Prompt with elevated (administrative) rights. Our guide about[running Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) includes numerous methods for launching that app. Then input this command and press**Enter** to delete an affected folder:

`rmdir /s "folder path"`

 You’ll need to replace**folder path** in that command with the location of whatever directory you need to delete. The location should include a drive letter and a full path for the directory like in this example:

`rmdir /s "C:\Users\New folder"`

![The delete folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-folder-command.jpg)

## 2\. Restart Windows File Explorer

 Restarting File Explorer can resolve issues that occur with that file manager. However, closing and reopening the Explorer window doesn’t restart the file manager. You’ll need to restart the Explorer process via Task Manager like this:

1. To view Task Manager, press**Ctrl** +**Shift** +**Esc** simultaneously.
2. Select File Explorer on the**Processes** tab.  
![The Restart option for File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-options-for-file-explorer.jpg)
3. Press the**Restart** button for the selected Explorer process.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1883998/19272" target="_top" id="1883998">
  <img src="//a.impactradius-go.com/display-ad/19272-1883998" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1883998/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Scan System Files With an SFC Scan

 Error 0x80070091 can be caused by some corrupted system files that need repairing. Running an SFC scan might both detect and repair corrupted system files and fix error 0x80070091 in the process. You can scan with SFC as instructed in our post for[running the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) .

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/sfc-scannow-command.jpg)

## 4\. Check for Errors With a Disk Scan

 The 0x80070091 error is often due to corrupted or bad hard drive sectors. A lot of users have said they’ve resolved that issue by using the Check Disk (CHKDSK) utility for repairing bad drive sectors. This is how you can check for and repair bad sectors with Check Disk:

1. Open up the Command Prompt window with administrative rights.
2. Type in this Check Disk command and press**Enter:**  
`chkdsk /f /r C:`
3. Press**Y** to schedule the scan for a restart.  
![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/chkdsk-scan-command.jpg)
4. Click**Start** and select**Power** \>**Restart** to reboot.

 If the folder the 0x80070091 error occurs for isn’t on the C: drive, you’ll need to modify the above command. Replace**C:** with the letter of the storage drive that includes the affected folder.

## 5\. Modify the Affected Folder’s Permissions

 Error 0x80070091 can arise because of insufficient folder permission. You might need to set an affected folder to full permission to resolve error 0x80070091\. To do that, change the folder’s permission settings as follows:

1. Open Explorer and right-click the affected folder to select**Properties** .  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/properties-option.jpg)
2. Click the window’s**Security** tab.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416">
  <img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Next, press the**Advanced** button.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/security-tab.jpg)
4. Click**Change** beside the owner’s name.  
![The Advanced Security Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced-security-settings-window.jpg)
5. Enter your Windows user account name inside the object name text box.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047351/19272" target="_top" id="2047351">
  <img src="//a.impactradius-go.com/display-ad/19272-2047351" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047351/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Select a User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/select-a-user-or-group.jpg)
6. Then select the**Check Names** option and**OK** .
7. Click**Replace owner on subcontainers and objects** to select that setting.
8. Press the Advanced Security Settings window’s**Apply** and**OK** buttons.

## 6\. Run an Antivirus Scan

 Malware could also feasibly be causing error 0x80070091 on your PC. If you’re still trying to fix that issue after going through all the potential fixes above, run an antivirus scan with Windows Security or alternative third-party software. This is how to run a scan with the Windows Security app.

1. Double-click a**Windows Security** (shield) icon in the system tray part of the taskbar.
2. Click**Virus & threat protection** \>**Scan options** to view all options for scanning.  
![The Scan options navigation link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-scan-options-link.jpg)
3. Select the most thorough**Full Scan** option, which could take more than an hour to finish.  

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134247/18498" target="_top" id="2134247">
  <img src="//a.impactradius-go.com/display-ad/18498-2134247" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134247/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Full scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/full-scan-option.jpg)
4. Press**Scan now** to start the antivirus scanning.
5. Then wait to see if the scan detects anything, and select**Remove** if it does.
6. Click**Start actions** to apply.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139119/17108" target="_top" id="2139119">
  <img src="//a.impactradius-go.com/display-ad/17108-2139119" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139119/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Delete Your Folders in File Explorer Again With These Fixes

 You’ll probably be able to delete the folders for which error 0x80070091 occurred after applying those potential solutions. If that error persists, the Windows registry on your PC could be corrupted. To resolve such registry issues, you might need to perform a system restore or even reset Windows 11/10.

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
<li><a href="https://youtube-web.techidaily.com/allying-up-mr-beasts-earnings-for-2024/"><u>[New] Tallying Up Mr. Beast's Earnings for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-2024-approved-expertly-curated-windows-video-editors-guide/"><u>[Updated] 2024 Approved Expertly Curated Windows Video Editors Guide</u></a></li>
<li><a href="https://location-fake.techidaily.com/11-best-location-changers-for-apple-iphone-12-pro-drfone-by-drfone-virtual-ios/"><u>11 Best Location Changers for Apple iPhone 12 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convertitori-online-gratuito-per-filetti-mpeg-a-mp3-ottienilo-facilmente-con-movavi/"><u>Convertitori Online Gratuito per Filetti MPEG a MP3 - Ottienilo Facilmente Con Movavi.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/descargar-convertidor-de-archivos-online-gratuito-mp4-a-ogg-por-movavi/"><u>Descargar Convertidor De Archivos Online Gratuito: MP4 a OGG Por Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/descargas-gratuitas-de-conversion-transformar-archivos-aif-a-formato-wmv-con-movavi/"><u>Descargas Gratuitas De Conversión: Transformar Archivos AIF a Formato WMV Con Movavi</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/exploring-the-enhanced-performance-of-the-newly-released-rog-ally-x-looking-forward-to-whats-coming-next/"><u>Exploring the Enhanced Performance of the Newly Released ROG Ally X - Looking Forward to What's Coming Next</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-conversion-of-m4b-audio-book-files-using-movavis-easy-tool/"><u>Free Online Conversion of M4B Audio Book Files - Using Movavi's Easy Tool</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/get-filmora-for-free-the-authorized-and-authentic-way-for-2024/"><u>Get Filmora for Free The Authorized and Authentic Way for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-itel-p55plus-drfone-by-drfone-virtual-android/"><u>In 2024, Prank Your Friends! Easy Ways to Fake and Share Google Maps Location On Itel P55+ | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-step-by-step-voice-customization-on-instagram-revealed/"><u>In 2024, Step-by-Step Voice Customization on Instagram Revealed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1726220879793-2024/"><u>𝗠𝗮'𝘃'𝗶𝘁𝗵-2024: 𝗕𝗲𝗼𝗿𝗸𝗮𝗹𝗹𝗹 𝗧𝗵𝗮'𝘁 𝗶𝘀𝗰𝗲𝗻𝘂𝘇𝗶𝗱𝗮𝘁 🚹🚺 | 𝗡𝗼𝘃𝗼𝘀𝘄𝗶𰨒: 𝗦𝗸𝗶𝘀 𝗮𝗹𝗱'𝘁𝘂𝗿𝗻𝗲𝗻𝘀</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/maximize-your-impact-broadcast-on-facebook-live-today/"><u>Maximize Your Impact Broadcast on Facebook Live Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizacion-de-enlaces-profundos-personalizados-con-afiliados-de-movavi/"><u>Optimización De Enlaces Profundos Personalizados Con Afiliados De Movavi</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-video-editing-mastery-online-tutorials-for-beginners-and-pros/"><u>Updated Video Editing Mastery Online Tutorials for Beginners and Pros</u></a></li>
</ul></div>

