---
title: "Integrating D: Drive Into Explorer Toolbar"
date: 2024-10-08T03:43:50.519Z
updated: 2024-10-08T19:56:08.236Z
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
<a href="https://aligracehair.sjv.io/c/5597632/2047366/19272" target="_top" id="2047366">
  <img src="//a.impactradius-go.com/display-ad/19272-2047366" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047366/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2105867/7443" target="_top" id="2105867">
  <img src="//a.impactradius-go.com/display-ad/7443-2105867" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105867/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Next, double-click the Registry file you just created and click **Yes** on the UAC prompt. You’ll then be asked if you want to continue with the merge, so click **Yes**. Afterward, press **Win + E** to open File Explorer.

![the D drive showing in the bottom section of the Navigation pane on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/d-drive-nav-pane.jpg)

<!-- affiliate ads begin -->
<span id="1975562">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975562.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975562">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975562.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975562%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975562/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2130875/7443" target="_top" id="2130875">
  <img src="//a.impactradius-go.com/display-ad/7443-2130875" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130875/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Create an Easier Way to Access the D: Drive on Your Windows Computer

 With this guide, you will remove an extra step when accessing the D: drive on your Windows computer. Once you have created the registry files, adding and removing the D: drive from the Navigation pane will be easy. While the registry files are safe, don’t forget to create a backup of your Registry or a system restore point for good measure.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-hints.techidaily.com/new-assessing-djis-flight-vision-tx-headset-performance/"><u>[New] Assessing DJI's Flight Vision TX Headset Performance</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-best-practices-in-digital-media-capturing-for-2024/"><u>[New] Best Practices in Digital Media Capturing for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-error-code-963-on-google-play-of-tecno-spark-10-4g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Error Code 963 on Google Play Of Tecno Spark 10 4G | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/discovering-the-significance-of-blue-icons-on-fb-messaging-app-for-2024/"><u>Discovering the Significance of Blue Icons on FB Messaging App for 2024</u></a></li>
<li><a href="https://buynow-info.techidaily.com/dive-into-the-depths-with-gopro-hero7-black-review/"><u>Dive Into the Depths with GoPro HERO7 Black Review!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reveal-hidden-elements-in-windows-11-ui/"><u>How to Reveal Hidden Elements in Windows 11 UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-turn-off-virtualization-on-windows-11/"><u>How to Turn Off Virtualization on Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-6-ways-to-change-spotify-location-on-your-xiaomi-redmi-13c-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 6 Ways to Change Spotify Location On Your Xiaomi Redmi 13C 5G | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/looking-for-a-location-changer-on-nokia-g42-5g-look-no-further-drfone-by-drfone-virtual-android/"><u>Looking For A Location Changer On Nokia G42 5G? Look No Further | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/mastering-background-removal-in-images-using-canva-for-2024/"><u>Mastering Background Removal in Images Using Canva for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-videos-from-vivo-by-fonelab-android-recover-video/"><u>Possible solutions to restore deleted videos from Vivo</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-keyboard-issues-in-the-windows-snipper/"><u>Resolving Keyboard Issues in the Windows Snipper</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-steam-storage-write-failure/"><u>Resolving Windows' Steam Storage Write Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamping-mouse-interaction-with-windows-clicklock-feature/"><u>Revamping Mouse Interaction with Windows ClickLock Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-altering-windows-index-settings/"><u>Step-by-Step: Altering Windows Index Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-potential-integrating-previous-pc-software-with-newer-os/"><u>Unlocking Potential: Integrating Previous PC Software with Newer OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-secrets-the-component-services-of-windows-11/"><u>Unlocking Secrets: The Component Services of Windows 11</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    