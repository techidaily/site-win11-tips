---
title: Integrating USB Drives Into File System Navigation
date: 2024-10-13T23:38:19.805Z
updated: 2024-10-15T07:45:04.540Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Integrating USB Drives Into File System Navigation
excerpt: This Article Describes Integrating USB Drives Into File System Navigation
keywords: USB Drive Integration,File Navigate USB,File System USB Add,USB Data Filesystem,File Explorer USB,USB System Navigation,Incorporating USB Drives
thumbnail: https://thmb.techidaily.com/81c104f653fc6628652d6140a521e94570f22aa2499ea9263be6a00f18fb658c.jpg
---

## Integrating USB Drives Into File System Navigation

 To access the D: drive, you normally have to open File Explorer, click on **This PC** in the Navigation pane, and expand the **Devices and drives** section. With a simple hack, you can add it to the Navigation pane so you can easily access it straight from there. It will require you to tweak the Windows Registry, but don’t worry; we'll show you an extremely easy way of going about it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Before You Proceed…

 We are going to [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/) to add the D: drive to the Navigation Pane. This file will make changes to the Windows registry, and you need to be careful [not to mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/). A slip-up could make Windows unusable.

 Furthermore, we highly recommend that you learn how to [back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). That way, you have a way of returning it to the state it was in before you made any changes that broke it.

<!-- affiliate ads begin -->
<span id="1912746">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1912746.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20231-1912746">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1912746.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fmindmanager.sjv.io%2Fc%2F5597632%2F1912746%2F20231'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1912746/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How Do I Add the D: Drive to the Navigation Pane in File Explorer?

 Start by pressing **Win + S** to bring up Windows Search. Then, type **notepad** in the Search box, and when Notepad shows up in the search results, click on it to launch it.

![The Notepad search result](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/notepad-search-result.png)

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938750/19272" target="_top" id="1938750">
  <img src="//a.impactradius-go.com/display-ad/19272-1938750" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938750/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Next, double-click the Registry file you just created and click **Yes** on the UAC prompt. You’ll then be asked if you want to continue with the merge, so click **Yes**. Afterward, press **Win + E** to open File Explorer.

![the D drive showing in the bottom section of the Navigation pane on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/d-drive-nav-pane.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975821/19272" target="_top" id="1975821">
  <img src="//a.impactradius-go.com/display-ad/19272-1975821" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975821/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The D: drive should now be visible in the bottom part of the Navigation pane.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135375/19272" target="_top" id="2135375">
  <img src="//a.impactradius-go.com/display-ad/19272-2135375" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135375/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How Do I Remove the D: Drive From the Navigation Pane in File Explorer?

 To remove the D: drive from the navigation pane, open Notepad and then copy and paste the below text:

`Windows Registry Editor Version 5.00  
  
[-HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}][HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\HideDesktopIcons\NewStartPanel]  
"{0525388b-89d9-4112-bf4d-2aaccb716a7f}"=-  
  
[-HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]`

 Save the file as **remove-d-drive-file-explorer.reg**. Afterward, double-click the registry file and click **Yes** on the UAC prompt. When asked if you want to continue with the merge, click **Yes** again.

 Now the D: drive should be gone from the navigation pane in File Explorer.

## Create an Easier Way to Access the D: Drive on Your Windows Computer

 With this guide, you will remove an extra step when accessing the D: drive on your Windows computer. Once you have created the registry files, adding and removing the D: drive from the Navigation pane will be easy. While the registry files are safe, don’t forget to create a backup of your Registry or a system restore point for good measure.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-chromebook-real-time-screenshot-app-for-2024/"><u>[Updated] Chromebook Real-Time Screenshot App for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-solutions-to-hard-reset-vivo-y27-5g-phone-using-pc-drfone-by-drfone-reset-android-reset-android/"><u>3 Solutions to Hard Reset Vivo Y27 5G Phone Using PC | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-fix-the-cannot-find-gpeditmsc-error-in-windows/"><u>4 Ways to Fix the “Cannot Find Gpedit.msc” Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-key-steps-to-resolve-epic-launcher-security-code-errors-on-windows/"><u>7 Key Steps to Resolve Epic Launcher Security Code Errors on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-understanding-and-using-components-settings/"><u>A Guide to Understanding and Using Components Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-crashing-keep-your-file-explorer-fixed-in-windows-11/"><u>Avoid Crashing: Keep Your File Explorer Fixed in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-the-past-erasing-defenders-track-of-security-efforts/"><u>Banish the Past: Erasing Defender’s Track of Security Efforts</u></a></li>
<li><a href="https://technical-tips.techidaily.com/decoding-bsod-exploring-the-causes-and-consequences-of-blue-screens-in-computers/"><u>Decoding BSOD: Exploring the Causes and Consequences of Blue Screens in Computers</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-the-newest-drivers-for-nvidias-rtx-2080-compatible-with-windows-1011-systems/"><u>Download the Newest Drivers for NVIDIA's RTX 2080 - Compatible with Windows 10/11 Systems</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/how-intova-x-changes-action-camera-game-for-2024/"><u>How Intova X Changes Action Camera Game for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-art-of-digital-makeup-on-video-platforms/"><u>In 2024, The Art of Digital Makeup on Video Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719371223006-master-the-digital-age-essential-keys-fan-deal-at-lowest-price-on-windows-11-612lifetime/"><u>Master the Digital Age - Essential Keys Fan Deal at Lowest Price on Windows 11, $6.12/Lifetime!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/steam-servers-now-online-previous-connection-issues-solved/"><u>Steam Servers Now Online - Previous Connection Issues Solved</u></a></li>
<li><a href="https://extra-resources.techidaily.com/step-by-step-incorporating-audio-into-ppts/"><u>Step-by-Step Incorporating Audio Into PPTs</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-list-of-5-social-networking-apps-to-enhance-your-friends-collection/"><u>The Ultimate List of 5 Social Networking Apps to Enhance Your Friends Collection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719355984111-troubleshooting-made-simple-your-guide-to-windows-help/"><u>Troubleshooting Made Simple: Your Guide to Windows Help</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    