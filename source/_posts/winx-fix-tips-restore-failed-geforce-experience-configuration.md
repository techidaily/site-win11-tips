---
title: "WinX Fix Tips: Restore Failed GeForce Experience Configuration"
date: 2024-10-16T16:44:37.304Z
updated: 2024-10-20T18:42:05.108Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes WinX Fix Tips: Restore Failed GeForce Experience Configuration"
excerpt: "This Article Describes WinX Fix Tips: Restore Failed GeForce Experience Configuration"
keywords: Fix GeForce Config,XP Repair Guide,Xfix Tips,Successful GFX Setup,Reconfigure Video Fix,Restore GPU Settings,WinX Graphics Troubleshoot
thumbnail: https://thmb.techidaily.com/2f5a7138163b464da142425b5cd4fc9ef8759bb9361cd872c71016b4ccd5a432.jpg
---

## WinX Fix Tips: Restore Failed GeForce Experience Configuration

 GeForce Experience is software with which users can usually optimize their games. However, some GeForce Experience users can’t optimize games with that software because of an “unable to retrieve settings” error. Some users see that error message when they click games’ thumbnails in GeForce Experience.

 Consequently, users can’t select the Optimize option for games that show the “unable to retrieve settings” error. That’s a bit annoying for players seeking optimal gaming performance. This is how you can fix GeForce Experience’s “unable to retrieve settings” error within Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Run GeForce Experience With Administrative Rights

 A few players have said running GeForce Experience with admin rights resolved the “Unable to retrieve settings” error for them. So, that’s a simple resolution worth trying. To see if that works for you, bring up the Windows search tool and input GeForce Experience. Then right-click the GeForce Experience search result to select **Run as administrator**.

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-as-administrator-option4.jpg)

 If that works, set GeForce Experience to always run with elevated user rights. Then you won’t need to select the **Run as administrator** option all the time. Our guide for [always running apps as an administrator on Windows](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) tells you how to set software packages to start with elevated permissions.

## 2\. Remove Scan Locations

 Some GeForce Experience users confirm that removing scan locations and rescanning fixes the “Unable to retrieve settings” error. This is how you can remove scan locations in GeForce Experience:

1. Open the GeForce Experience window.
2. Click the **Settings** button by your user account name.  
![The Settings menu button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/settings-button.jpg)
3. Select the **Games & Apps** tab.
4. Then select a scan location and click **Remove**. Repeat this step to remove all scan locations shown.  
![The Remove button for scan locations](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-button.jpg)
5. Press the **Scan Now** button to rescan.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151859/7443" target="_top" id="2151859">
  <img src="//a.impactradius-go.com/display-ad/7443-2151859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151859/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Delete the CefCache Folder

 CefCache is a GeForce Experience folder that stores cached data. GeForce Experience optimization issues can arise when that cache includes corrupted configuration files. You might be able to resolve the “Unable to retrieve settings” error by deleting the CafCache folder like this:

1. Ensure GeForce Experience isn’t already running by closing it on the taskbar and the system tray. Right-click the NVIDIA system tray and select **Exit** to close GeForce Experience there.
2. Open File Explorer (press **Win + E**) and input this path in the folder address bar:  
`C:\Users\<user folder>\AppData\Local\NVIDIA Corporation\NVIDIA GeForce Experience`  
![The CefCache folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/cefcache-folder.jpg)
3. Right-click the **CefCache** folder to select **Delete**.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151858/7443" target="_top" id="2151858">
  <img src="//a.impactradius-go.com/display-ad/7443-2151858" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151858/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/delete-button.jpg)
4. Then launch the GeForce Experience software.
5. Input your GeForce Experience account details again and click **Log In**.

## 4\. Restore Default NVIDIA 3D Settings

 Restoring the NVIDIA 3D Settings to default is another potential fix for the “Unable to retrieve settings” error that has worked for some users. Applying this resolution will reset all 3D settings you’ve changed in the NVIDIA Control panel to a default configuration. You can apply this potential resolution as follows:

1. Right-click on the NVIDIA logo inside the system tray area to select **Control Panel**.
2. Next, select **Manage 3D** settings in the NVIDIA Control Panel.
3. Click **Restore** on the **Global Settings** tab.  
![The Restore button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/restore-button.jpg)
4. Select **Yes** to reset the settings.

## 5\. Delete the Steam User Data

 The “Unable to retrieve settings” error can arise for Steam games because of a data conflict with Steam. Players have confirmed erasing data in a Steam userdata subfolder works for fixing this issue. So, that’s a possible resolution recommended for all players who’ve got Steam installed. Clear Steam’s userdata folder like this:

1. Simultaneously press **Win + X** and select the File Explorer shortcut.
2. Input this userdata folder path in Explorer’s address bar:  
`C:\Program Files\Steam\userdata`  
![Steam's userdata folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/userdata-folder.jpg)
3. Right-click a subfolder that doesn’t have any numbers in its name within the userdata folder and select **Delete**.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2148774/18498" target="_top" id="2148774">
  <img src="//a.impactradius-go.com/display-ad/18498-2148774" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148774/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Repeat the previous step to delete all subfolders in userdata with non-numeric titles like anonymous, etc.

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2135316/14409" target="_top" id="2135316">
  <img src="//a.impactradius-go.com/display-ad/14409-2135316" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2135316/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Perform Some Generic Windows Fixes

 There are a few Windows-based fixes you can try to get rid of this error.

### Erase Temporary Windows Data

 The Temp folder stores temporary files. GeForce Experience users confirm deleting data in that Temp folder can fix the “Unable to retrieve settings” issue. So, try eradicating data in that folder with one of the methods in our guide to [deleting temporary files](https://www.makeuseof.com/windows-11-delete-temporary-files/)[in Windows 11](http://www.makeuseof.com/windows-11-delete-temporary-files/).

![disk-cleanup-tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disk-cleanup-tool.jpg)

### Install the Latest NVIDIA Driver for Your GPU

 Although less likely, corrupted NVIDIA GPU driver files can feasibly cause the “Unable to retrieve settings” error to arise. In this case, installing the latest NVIDIA graphics drivers could be a solution for some users. Uninstall your PC’s current NVIDIA graphics driver and install the latest one by downloading it from the NVIDIA website.

 Follow the instructions in our guide to [installing and cleanly reinstalling GPU drivers](https://www.makeuseof.com/how-to-cleanly-install-and-reinstall-gpu-drivers-on-windows/) to apply this potential fix with the DDU software.

![The NVIDIA driver downloads page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/nvidia-driver-downloads.jpg)

### Disable Third-Party Antivirus Tools

 If you’ve got third-party antivirus software installed on your Windows PC, that might be blocking GeForce Experience from accessing certain folders and optimizing settings. BitDefender Total Security is one antivirus utility widely confirmed to cause this issue. Those users who've confirmed that needed to disable BitDefender to resolve the issue.

 So, try disabling BitDefender or any other third-party antivirus software to see if that makes a difference. You can disable real-time scanning by right-clicking an antivirus tool in the Windows system tray and selecting to disable or turn it off from the context menu. Select to temporarily disable the antivirus scanning for about an hour or so and then open GeForce Experience.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886069/19272" target="_top" id="1886069">
  <img src="//a.impactradius-go.com/display-ad/19272-1886069" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886069/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Reinstall GeForce Experience

 Reinstalling GeForce Experience might be a necessary potential fix for the “Unable to retrieve files” error if others fail. That will replace any corrupted GeForce Experience files that could be causing glitches. Remove GeForce Experience with a method in this guide to [uninstalling software in Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/).

![The Programs and Features applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/uninstall-option3.jpg)

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2135315/14409" target="_top" id="2135315">
  <img src="//a.impactradius-go.com/display-ad/14409-2135315" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2135315/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Restart the PC before reinstalling GeForce Experience. Then head over to this [GeForce Experience](https://www.nvidia.com/en-gb/geforce/geforce-experience/download/) webpage and click **Download Now**. Open the folder your browser usually downloads files to and double-click the GeForce Experience setup wizard. Go through the installer’s steps to reinstall the software.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123750/7443" target="_top" id="2123750">
  <img src="//a.impactradius-go.com/display-ad/7443-2123750" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123750/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Optimize Your Games With GeForce Experience

 Many GeForce Experience users have fixed the “unable to retrieve settings” error in Windows with the resolutions above. You may have to try applying a few of them to get the issue sorted since there are quite a few potential causes for this error. Then you can quickly and fully optimize all your favorite games with GeForce Experience again.

 However, remember that there are numerous ways to optimize Windows games without GeForce Experience. You can optimize gaming by enabling or even disabling certain Windows features and closing background apps. Plus, you can manually adjust the graphical settings in the NVIDIA Control Panel or games to optimize Windows gaming.

 Consequently, users can’t select the Optimize option for games that show the “unable to retrieve settings” error. That’s a bit annoying for players seeking optimal gaming performance. This is how you can fix GeForce Experience’s “unable to retrieve settings” error within Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-sure.techidaily.com/024-approved-your-next-great-story-selecting-free-android-editing-tools/"><u>[New] 2024 Approved Your Next Great Story Selecting Free Android Editing Tools</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-nine-superior-choices-for-live-streaming-now/"><u>[New] Nine Superior Choices for Live Streaming Now</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-effortless-harmony-creating-engaging-and-organized-youtube-playlists/"><u>[Updated] In 2024, Effortless Harmony Creating Engaging and Organized YouTube Playlists</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-top-10-online-stores-for-personalized-box-designs/"><u>2024 Approved Top 10 Online Stores for Personalized Box Designs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mp4-aacmovavi/"><u>在线MP4-AAC无障碍转换服务：如何用Movavi实现高效转码</u></a></li>
<li><a href="https://discover-extraordinary.techidaily.com/download-le-kit-de-developpeur-windows-adk-pour-utiliser-avec-aomei-backupper/"><u>Download Le Kit De Développeur Windows ADK Pour Utiliser Avec AOMEI Backupper</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-conversion-of-mov-files-to-vob-format-move-itcom/"><u>Free Online Conversion of MOV Files to VOB Format - Move-it.com</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-6-superior-apps-for-effortless-mac-video-grabbing/"><u>In 2024, 6 Superior Apps for Effortless Mac Video Grabbing</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-top-15-augmented-reality-games-like-pokemon-go-to-play-on-poco-c51-drfone-by-drfone-virtual-android/"><u>In 2024, Top 15 Augmented Reality Games Like Pokémon GO To Play On Poco C51 | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-unlock-apple-iphone-se-without-passcode-easily-by-drfone-ios/"><u>In 2024, Unlock Apple iPhone SE Without Passcode Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/les-12-maitres-du-montage-video-en-haute-volee-en-2024-decouvrez-avec-movavi/"><u>Les 12 Maîtres Du Montage Vidéo en Haute Volée en 2024 - Découvrez Avec Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/no-cost-web-based-aiffaac-audio-format-changeover-movavi-converter/"><u>No-Cost Web-Based Aiff/Aac Audio Format Changeover - Movavi Converter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/online-m4a-to-swf-file-transformation-without-charge-with-movavi-software-solutions/"><u>Online M4A to SWF File Transformation without Charge with Movavi Software Solutions</u></a></li>
<li><a href="https://win-answers.techidaily.com/solving-the-frame-rate-dip-in-age-of-empires-iv-troubleshooting-guide/"><u>Solving the Frame Rate Dip in Age of Empires IV: Troubleshooting Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforma-su-contenido-flash-al-formato-mp4-por-internet-sin-gastos-guia-paso-a-paso-solucion-gratuita-de-movavi/"><u>Transforma Su Contenido Flash Al Formato MP4 Por Internet Sin Gastos, Guía Paso a Paso - Solución Gratuita De Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformation-gratuit-du-format-audio-fichier-opus-a-mp3-sur-movavi/"><u>Transformation Gratuit Du Format Audio : Fichier OPUS À MP3 Sur Movavi</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/why-does-the-pokemon-go-battle-league-not-available-on-sony-xperia-10-v-drfone-by-drfone-virtual-android/"><u>Why does the pokemon go battle league not available On Sony Xperia 10 V | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1726221843560-3g2-mp4-movavi/"><u>구독 없이 3G2 파일을 무료 MP4 형식으로 전환하는 - Movavi 소프트웨어</u></a></li>
<li><a href="https://win11-tips.techidaily.com/iuycroynhcdtjrjsp5eg7zse66gc7is47iqkoidrsjjsnzhtmjug67cw6rk97j2eioycroyaqe2vncdsojxqtzdtlzwg66as66plus47yq4iouwqeuylsi/"><u>사진 편집 프로세스: 반응형 배경을 사용한 정교한 리미트 방법</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    