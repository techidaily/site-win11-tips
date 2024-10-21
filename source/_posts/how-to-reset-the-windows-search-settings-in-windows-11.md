---
title: How to Reset the Windows Search Settings in Windows 11
date: 2024-10-20T02:51:34.898Z
updated: 2024-10-20T18:47:05.673Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Reset the Windows Search Settings in Windows 11
excerpt: This Article Describes How to Reset the Windows Search Settings in Windows 11
keywords: Windows 11 Search Reset Guide,WinSearch Options Revert,Windows Search Control Panel,Restore Windows 11 Indexing Service,Keyboard Shortcuts for Search Settings,Disable Windows Search Feature,Indexing Service Fix in Win11
thumbnail: https://thmb.techidaily.com/503d593f9428317b9217e37989fa613e5c3305adb6e8017e4b8755b0efa649e5.png
---

## How to Reset the Windows Search Settings in Windows 11

 Like any other computer program, Windows Search can sometimes develop issues that require you to reset its settings to work properly. This article explains two simple ways to reset Windows Search settings back to default. Let's look at each one in detail.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Should You Reset Windows Search Settings?

 Windows Search tracks files and folders on your hard drive, so you can find them more quickly. However, over time search settings and preferences can become corrupted, leading to incorrect search results or slow performance. To get the most effective results from Windows Search, you should periodically reset your search settings.

 Resetting search settings on Windows can improve search speed and accuracy. It gets rid of useless data and resolves errors or conflicts due to stored information. This can ultimately enhance your computer’s performance and provide a more efficient search experience.

 Let's now explore how to reset Windows Search settings.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915825/19272" target="_top" id="1915825">
  <img src="//a.impactradius-go.com/display-ad/19272-1915825" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915825/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Tweak the Registry Editor

 If you want to reset Windows Search settings back to default, you can modify the registry editor. It involves directly changing certain keys in the Windows Registry, which can sometimes become risky if done incorrectly.

 To avoid this issue, be sure to [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before proceeding. Once done, follow these steps.

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the dialog box and hit the Enter key.
3. When the UAC prompt appears on the screen, click **Yes** to continue.
4. In the Registry Editor window, navigate to the following path:  
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows Search  
 You can also copy and paste the path into the address bar at the top of the window and hit the Enter key. This will take you to the Windows Search section.
5. Now move to the right pane and search for the key named **SetupCompletedSuccessfully**.  
![Reset Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-search.jpg)
6. Select this key, right-click on it, and choose **Modify**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049382/7443" target="_top" id="2049382">
  <img src="//a.impactradius-go.com/display-ad/7443-2049382" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049382/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Set the value to **0** and click **OK** to save the changes.

 If the SetupCompletedSuccessfully key is missing, you will have to manually create it. To do this, right-click on the Windows Search key and select **New > DWORD (32-bit) Value**. Name this newly created key as **SetupCompletedSuccessfully** and set its value to **0**.

 After performing the steps above, close the Registry Editor and restart your computer for the changes to take effect.

## 2\. Use Windows PowerShell

 If you prefer command-line solutions, you can use PowerShell to reset Windows Search settings. It involves running a few simple commands to restore search settings. Here's how to do it.

[Open the Microsoft Download Page](https://www.microsoft.com/en-us/download/100295) and download the ResetWindowsSearchBox.ps1 PowerShell script. Once downloaded, right-click on the file and select **Run with PowerShell**.

 If you see an error message _"Cannot be loaded because the running script is disabled on this system"_ you need to enable script execution first. To do that, [open PowerShell as a system administrator](http://www.makeuseof.com/windows-11-powershell-administrator/). Then type **Get-ExecutionPolicy** and press Enter.

![Restrict or Unrestrict the Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restrict-or-unrestrict-the-command.png)

 If the output is **Restricted**, execute the following command to allow PowerShell scripts:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted

 After setting the execution policy, try running the ResetWindowsSearchBox.ps1 file again. Once the script is executed successfully, it resets Windows search settings.

![Reset Windows Search Via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-search-via-powershell.png)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134491/18498" target="_top" id="2134491">
  <img src="//a.impactradius-go.com/display-ad/18498-2134491" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134491/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After resetting the Windows Search settings, you can restore the execution policy to its original settings. To do that, open PowerShell as an administrator again and execute the following command:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Restricted

 Once the execution policy is set back to its original value, restart your computer. The Windows Search settings should now be restored to their default state.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118306/7443" target="_top" id="2118306">
  <img src="//a.impactradius-go.com/display-ad/7443-2118306" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118306/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Easy Ways to Reset Windows Search

 Resetting Windows search settings can fix any issues you may have with your search experience. This guide will teach you how to reset Windows Search settings to their original values.

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
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-prime-time-video-capture-for-windows-users-10-best/"><u>[New] In 2024, Prime Time Video Capture for Windows Users - 10 Best</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-2024-approved-step-by-step-guide-to-android-movie-upturning/"><u>[Updated] 2024 Approved Step-by-Step Guide to Android Movie Upturning</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-expert-roundup-of-platforms-for-video-intro-acquisition/"><u>[Updated] Expert Roundup of Platforms for Video Intro Acquisition</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-unlocking-video-editing-on-windows-11-for-professionals/"><u>2024 Approved Unlocking Video Editing on Windows 11 for Professionals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1726225807073-8/"><u>8가지 획기적인 증명사진 스타일을 제공하는 최선의 촬영 도구 소피</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conversao-de-video-gratuita-on-line-de-m4v-para-mp4/"><u>Conversão De Vídeo Gratuita On-Line - De M4V Para MP4</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conversione-gratuita-online-da-flv-a-swf-con-movavi-trasforma-il-tuo-video-senza-costi/"><u>Conversione Gratuita Online Da FLV a SWF Con Movavi - Trasforma Il Tuo Video Senza Costi</u></a></li>
<li><a href="https://technical-tips.techidaily.com/discover-the-best-free-online-calendar-options-today/"><u>Discover the Best Free Online Calendar Options Today</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-tecno-camon-20-premier-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some Pro Tips for Pokemon Go PvP Battles On Tecno Camon 20 Premier 5G | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-web-conferences-archival/"><u>In 2024, Web Conferences Archival</u></a></li>
<li><a href="https://solve-outstanding.techidaily.com/kostenlose-software-fur-hochwertiges-dvd-audio-extrahieren-perfektes-endgerat-fur-sammler-und-enthusiasten/"><u>Kostenlose Software Für Hochwertiges DVD-Audio Extrahieren – Perfektes Endgerät Für Sammler Und Enthusiasten</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavis-no-cost-online-service-change-your-audio-tracks-from-mp3-to-video-on-demand-vob/"><u>Movavi's No-Cost Online Service: Change Your Audio Tracks From MP3 to Video on Demand (VOB)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformacion-gratuita-de-archivos-raf-en-imagenes-jpg-por-movavi/"><u>Transformación Gratuita De Archivos RAF en Imágenes JPG Por Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformez-vos-videos-familiales-amateures-en-productions-professionnelles-astuces-et-conseils/"><u>Transformez Vos Vidéos Familiales Amateures en Productions Professionnelles : Astuces Et Conseils</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trasforma-i-tuoi-file-mov-in-wmv-online-gratuito-con-ease-movavi/"><u>Trasforma I Tuoi File MOV in WMV Online Gratuito Con Ease - Movavi</u></a></li>
<li><a href="https://tech-revival.techidaily.com/uniting-tech-and-talk-setup-winchatgpt/"><u>Uniting Tech and Talk: Setup WinChatGPT</u></a></li>
</ul></div>

