---
title: Taming the Non-Empty Directories Warning with #0X80070091 on Windows 11
date: 2024-10-19T16:37:27.385Z
updated: 2024-10-21T04:02:39.254Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Taming the Non-Empty Directories Warning with #0X80070091 on Windows 11
excerpt: This Article Describes Taming the Non-Empty Directories Warning with #0X80070091 on Windows 11
keywords: Win11 Directory Error,OS X0X Warning,Empty Folder Fix,Directories Warning,0X70091 Fix,Windows NonEmptyError,0X80070091 Troubleshoot
thumbnail: https://thmb.techidaily.com/76cb87841297f436650576e356aab992c1ddd1148ccda3c73b6601c2eaf3c2ce.jpg
---

## Taming the Non-Empty Directories Warning with #0X80070091 on Windows 11

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

<!-- affiliate ads begin -->
<span id="1424533">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424533.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424533">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424533.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424533%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424533/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Restart Windows File Explorer

 Restarting File Explorer can resolve issues that occur with that file manager. However, closing and reopening the Explorer window doesn’t restart the file manager. You’ll need to restart the Explorer process via Task Manager like this:

1. To view Task Manager, press**Ctrl** +**Shift** +**Esc** simultaneously.
2. Select File Explorer on the**Processes** tab.  
![The Restart option for File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-options-for-file-explorer.jpg)
3. Press the**Restart** button for the selected Explorer process.

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
<span id="1982461">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982461.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982461">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982461.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982461%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982461/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Next, press the**Advanced** button.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/security-tab.jpg)
4. Click**Change** beside the owner’s name.  

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014854/22899" target="_top" id="2014854">
  <img src="//a.impactradius-go.com/display-ad/22899-2014854" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014854/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Advanced Security Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced-security-settings-window.jpg)
5. Enter your Windows user account name inside the object name text box.  
![The Select a User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/select-a-user-or-group.jpg)
6. Then select the**Check Names** option and**OK** .
7. Click**Replace owner on subcontainers and objects** to select that setting.
8. Press the Advanced Security Settings window’s**Apply** and**OK** buttons.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151893/7443" target="_top" id="2151893">
  <img src="//a.impactradius-go.com/display-ad/7443-2151893" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151893/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Run an Antivirus Scan

 Malware could also feasibly be causing error 0x80070091 on your PC. If you’re still trying to fix that issue after going through all the potential fixes above, run an antivirus scan with Windows Security or alternative third-party software. This is how to run a scan with the Windows Security app.

1. Double-click a**Windows Security** (shield) icon in the system tray part of the taskbar.
2. Click**Virus & threat protection** \>**Scan options** to view all options for scanning.  
![The Scan options navigation link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-scan-options-link.jpg)
3. Select the most thorough**Full Scan** option, which could take more than an hour to finish.  
![The Full scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/full-scan-option.jpg)
4. Press**Scan now** to start the antivirus scanning.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130869/7443" target="_top" id="2130869">
  <img src="//a.impactradius-go.com/display-ad/7443-2130869" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130869/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Then wait to see if the scan detects anything, and select**Remove** if it does.
6. Click**Start actions** to apply.

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
<li><a href="https://screen-recording.techidaily.com/new-time-lapse-tips-for-iphoneipad-users/"><u>[New] Time-Lapse Tips for iPhone/iPad Users</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-ultimate-windows-recordings-made-simple-for-2024/"><u>[New] Ultimate Windows Recordings Made Simple for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-from-live-to-recorded-a-skilled-approach-to-skype-chat-documentation/"><u>[Updated] 2024 Approved From Live to Recorded A Skilled Approach to Skype Chat Documentation</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-laughburst-app-for-all-humor-needs/"><u>[Updated] LaughBurst App for All Humor Needs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-simple-methods-for-optimizing-your-videos-preparing-content-for-instagram-with-movavi/"><u>3 Simple Methods for Optimizing Your Videos: Preparing Content for Instagram with Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1726225206241-flvwmv-movavi/"><u>瀏覽器上無成本FLV變WMV改變 - 實現這一過程的Movavi方法</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/dvd20245/"><u>最新無料DVDコピーソフト選別：2024年のオススメ機能が詰まったリッパー5本勝負 - 完全版</u></a></li>
<li><a href="https://win11-tips.techidaily.com/aktif-sanayi-sistemlerine-katkida-bulunan-keygen-kullanabilir-icin-bir-yapitir/"><u>Aktif Sanayi Sistemlerine Katkıda Bulunan Keygen Kullanabilir İçin Bir Yapıtır</u></a></li>
<li><a href="https://blog-min.techidaily.com/best-3-software-to-transfer-files-tofrom-your-infinix-smart-7-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Best 3 Software to Transfer Files to/from Your Infinix Smart 7 via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/como-transformar-m1v-en-archivo-mp4-sin-coste-mediante-herramientas-web-libres/"><u>Cómo Transformar M1V en Archivo MP4 Sin Coste Mediante Herramientas Web Libres</u></a></li>
<li><a href="https://win11-tips.techidaily.com/descargar-e-impresione-m4r-archivos-a-formato-mp3-gratuito-sin-costo-con-converter-movavi/"><u>Descargar E Impresione M4R Archivos a Formato MP3 Gratuito Sin Costo Con Converter - Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dicas-facilmente-executaveis-desenvolva-seu-olhar-selvagem-com-fotos-expressivas/"><u>Dicas Facilmente Executáveis: Desenvolva Seu Olhar Selvagem Com Fotos Expressivas</u></a></li>
<li><a href="https://techtrends.techidaily.com/enhance-your-rooms-acoustics-masterful-integration-of-subwoofers-with-samsung-soundbars/"><u>Enhance Your Room's Acoustics: Masterful Integration of Subwoofers with Samsung Soundbars</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gratis-moegenoefening-livestreamen-met-jeldende-videoprogramma-movavi/"><u>Gratis Moegenoefening Livestreamen Met Jeldende Videoprogramma - Movavi</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-vivo-s18e-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Vivo S18e | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/komt-een-kostenlose-conversie-aan-ogg-adres-met-movavi-voor-online-activiteiten-afvallend-au-inlevering-gratis/"><u>Komt Een Kostenlose Conversie Aan: OGG-Adres Met Movavi Voor Online Activiteiten, Afvallend .au - Inlevering Gratis</u></a></li>
<li><a href="https://video-capture.techidaily.com/mac-tips-capturing-class-notes-efficiently-for-2024/"><u>Mac Tips Capturing Class Notes Efficiently for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movogv-movavi/"><u>MOV到OGV無料線上轉換 - 利用Movavi轉換工具</u></a></li>
<li><a href="https://win-special.techidaily.com/quick-and-free-effortless-conversion-of-pdfs-into-docxpptxswfimage-formats/"><u>Quick and Free: Effortless Conversion of PDFs Into DOCX/PPTX/SWF/Image Formats</u></a></li>
</ul></div>

