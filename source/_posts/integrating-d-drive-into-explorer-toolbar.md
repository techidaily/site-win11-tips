---
title: "Integrating D: Drive Into Explorer Toolbar"
date: 2024-10-10T16:21:36.604Z
updated: 2024-10-15T05:06:24.611Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Integrating D: Drive Into Explorer Toolbar"
excerpt: "This Article Describes Integrating D: Drive Into Explorer Toolbar"
keywords: Explore D Browser,Explorer Toolbar Integrate,DriveIntoExplorerUpdate,ExploreToolBarDriveAdd,DBrowserIntegrationEase,ExplorerEnhancementTool,QuickToolbarSetupDrive
thumbnail: https://thmb.techidaily.com/cd918524a7d7688c6ef6414ad8dfa9dc1bddfeb0b565f942655d5f5347ebbc9b.jpg
---

## Integrating D: Drive Into Explorer Toolbar

 To access the D: drive, you normally have to open File Explorer, click on **This PC** in the Navigation pane, and expand the **Devices and drives** section. With a simple hack, you can add it to the Navigation pane so you can easily access it straight from there. It will require you to tweak the Windows Registry, but don’t worry; we'll show you an extremely easy way of going about it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Before You Proceed…

 We are going to [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/) to add the D: drive to the Navigation Pane. This file will make changes to the Windows registry, and you need to be careful [not to mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/). A slip-up could make Windows unusable.

 Furthermore, we highly recommend that you learn how to [back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). That way, you have a way of returning it to the state it was in before you made any changes that broke it.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136619/26400" target="_top" id="2136619">
  <img src="//a.impactradius-go.com/display-ad/26400-2136619" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136619/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How Do I Add the D: Drive to the Navigation Pane in File Explorer?

 Start by pressing **Win + S** to bring up Windows Search. Then, type **notepad** in the Search box, and when Notepad shows up in the search results, click on it to launch it.

![The Notepad search result](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/notepad-search-result.png)

<!-- affiliate ads begin -->
<span id="1630055">
					<video width="192" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1630055.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18460-1630055">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1630055.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:120px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fcaperobbin.sjv.io%2Fc%2F5597632%2F1630055%2F18460'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1630055/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then copy and paste the below text into Notepad:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]  
@="D: Drive"  
"System.IsPinnedToNamespaceTree"=dword:00000001  
"SortOrderIndex"=dword:00000050  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\DefaultIcon]  
@=hex(2):69,00,6d,00,61,00,67,00,65,00,72,00,65,00,73,00,2e,00,64,00,6c,00,6c,\  
  00,2c,00,2d,00,33,00,32,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\InProcServer32]  
@=hex(2):43,00,3a,00,5c,00,57,00,49,00,4e,00,44,00,4f,00,57,00,53,00,5c,00,73,\  
  00,79,00,73,00,74,00,65,00,6d,00,33,00,32,00,5c,00,73,00,68,00,65,00,6c,00,\  
  6c,00,33,00,32,00,2e,00,64,00,6c,00,6c,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\Instance]  
"CLSID"="{0E5AAE11-A475-4c5b-AB00-C66DE400274E}"  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\Instance\InitPropertyBag]  
"Attributes"=dword:00000011  
"TargetFolderPath"=hex(2):44,00,3a,00,5c,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\ShellFolder]  
"FolderValueFlags"=dword:00000028  
"Attributes"=dword:f080004d  
  
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\HideDesktopIcons\NewStartPanel]  
"{0525388b-89d9-4112-bf4d-2aaccb716a7f}"=dword:00000001  
  
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]  
@="D: Drive"`

 Press **Ctrl + S**, name the file **add-d-drive-file-explorer.reg**, and then click **Save**. Don’t forget to add the REG file extension to let Windows know it’s working with a Registry file.

![saving a registry file in Notepad on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/save-reg-file-add-drive-nav-pane.jpg)

 Next, double-click the Registry file you just created and click **Yes** on the UAC prompt. You’ll then be asked if you want to continue with the merge, so click **Yes**. Afterward, press **Win + E** to open File Explorer.

![the D drive showing in the bottom section of the Navigation pane on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/d-drive-nav-pane.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037351/7443" target="_top" id="2037351">
  <img src="//a.impactradius-go.com/display-ad/7443-2037351" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037351/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The D: drive should now be visible in the bottom part of the Navigation pane.

## How Do I Remove the D: Drive From the Navigation Pane in File Explorer?

 To remove the D: drive from the navigation pane, open Notepad and then copy and paste the below text:

`Windows Registry Editor Version 5.00  
  
[-HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}][HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\HideDesktopIcons\NewStartPanel]  
"{0525388b-89d9-4112-bf4d-2aaccb716a7f}"=-  
  
[-HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]`

 Save the file as **remove-d-drive-file-explorer.reg**. Afterward, double-click the registry file and click **Yes** on the UAC prompt. When asked if you want to continue with the merge, click **Yes** again.

 Now the D: drive should be gone from the navigation pane in File Explorer.

<!-- affiliate ads begin -->
<span id="1983475">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983475.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983475">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983475.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983475%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983475/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Create an Easier Way to Access the D: Drive on Your Windows Computer

 With this guide, you will remove an extra step when accessing the D: drive on your Windows computer. Once you have created the registry files, adding and removing the D: drive from the Navigation pane will be easy. While the registry files are safe, don’t forget to create a backup of your Registry or a system restore point for good measure.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-from-ordinary-to-outstanding-a-guide-to-snapchat-edits/"><u>[New] In 2024, From Ordinary to Outstanding A Guide to Snapchat Edits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-global-ip-using-command-prompt-on-win/"><u>Deciphering Global IP Using Command Prompt on WIN</u></a></li>
<li><a href="https://win-superb.techidaily.com/descargar-y-convertir-de-formato-mp3-a-wav-sin-coste-guia-completa-con-movavi/"><u>Descargar Y Convertir De Formato MP3 a WAV Sin Coste: Guía Completa Con Movavi</u></a></li>
<li><a href="https://program-issues.techidaily.com/eliminating-the-hurdle-expert-tips-to-fix-dev-error-6034-on-pc-and-xbox-console-call-of-duty-fans-guide/"><u>Eliminating the Hurdle: Expert Tips to Fix Dev Error 6034 on PC and Xbox Console – Call of Duty Fans Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-safety-masterful-firewall-configuration/"><u>Enhancing Safety: Masterful Firewall Configuration</u></a></li>
<li><a href="https://program-issues.techidaily.com/fix-lag-issues-and-improve-frame-rate-in-call-of-duty-warzone-expert-tips-inside/"><u>Fix Lag Issues & Improve Frame Rate in Call of Duty Warzone - Expert Tips Inside!</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-xiaomi-redmi-k70e-by-phone-number-drfone-by-drfone-virtual-android/"><u>How to Track Xiaomi Redmi K70E by Phone Number | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lockdown-keep-windows-clock-unaltered/"><u>Lockdown: Keep Windows' Clock Unaltered</u></a></li>
<li><a href="https://article-posts.techidaily.com/master-the-art-of-zooming-in-snapchat-photos-and-videos/"><u>Master the Art of Zooming in Snapchat Photos & Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-high-cpu-impact-of-windows-extender/"><u>Mitigating High CPU Impact of Windows Extender</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/pattern-locks-are-unsafe-secure-your-oppo-reno-10-5g-phone-now-with-these-tips-by-drfone-android/"><u>Pattern Locks Are Unsafe Secure Your Oppo Reno 10 5G Phone Now with These Tips</u></a></li>
<li><a href="https://tech-revival.techidaily.com/rapid-and-easy-mp3-video-converter-online-tool-gyors-hatosag/"><u>Rapid & Easy MP3 Video Converter - Online Tool | Gyors Hatóság</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-unidentified-lsassexe-problem-in-windows-10/"><u>Steps to Fix Unidentified lsass.exe Problem in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-black-screen-dilemma-on-win10-and-11-swiftly/"><u>Tackling the Black Screen Dilemma on Win10 & 11 Swiftly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-simplified-image-editing-in-windows-photos/"><u>The Art of Simplified Image Editing in Windows Photos</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/ultimate-laptops-your-go-to-machine-for-expert-video-editing-for-2024/"><u>Ultimate Laptops Your Go-To Machine for Expert Video Editing for 2024</u></a></li>
</ul></div>

