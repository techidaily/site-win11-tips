---
title: Incorporating External Disk Into Explorer Nav Pane
date: 2024-07-12T16:31:38.175Z
updated: 2024-07-13T16:31:38.175Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Incorporating External Disk Into Explorer Nav Pane
excerpt: This Article Describes Incorporating External Disk Into Explorer Nav Pane
keywords: Explore External Disk,Add External Drive,Internal-External Linkage,External Drive Inexplorer,Disk Integration in Explorer,Explorer Disk Settings,Extending Explorer Nav Pane
thumbnail: https://thmb.techidaily.com/0a337b8d498c7856f1553f3aec6dd0a0ba10469da4dedfe1c7e2e3409bef7181.jpg
---

## Incorporating External Disk Into Explorer Nav Pane

 To access the D: drive, you normally have to open File Explorer, click on **This PC** in the Navigation pane, and expand the **Devices and drives** section. With a simple hack, you can add it to the Navigation pane so you can easily access it straight from there. It will require you to tweak the Windows Registry, but don’t worry; we'll show you an extremely easy way of going about it.

## Before You Proceed…

 We are going to [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/) to add the D: drive to the Navigation Pane. This file will make changes to the Windows registry, and you need to be careful [not to mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/). A slip-up could make Windows unusable.

 Furthermore, we highly recommend that you learn how to [back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). That way, you have a way of returning it to the state it was in before you made any changes that broke it.

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

 Next, double-click the Registry file you just created and click **Yes** on the UAC prompt. You’ll then be asked if you want to continue with the merge, so click **Yes**. Afterward, press **Win + E** to open File Explorer.

![the D drive showing in the bottom section of the Navigation pane on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/d-drive-nav-pane.jpg)

 The D: drive should now be visible in the bottom part of the Navigation pane.

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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/innovative-use-of-android-phones-as-webcams-on-windows-11-pcs/"><u>Innovative Use of Android Phones as Webcams on Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-initial-load-hurdles-in-lol/"><u>Overcoming Initial Load Hurdles in LOL</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-dormant-devices-with-synapse-on-windows-11/"><u>Reviving Dormant Devices with Synapse on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insight-into-cab-files-their-purpose-within-the-windows-domain/"><u>Insight Into CAB Files: Their Purpose Within the Windows Domain</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-deactivated-office-alerts-in-windows/"><u>Resolving Deactivated Office Alerts in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-blue-screens-resulting-from-wins-intruder-exception/"><u>Quick Fixes for Blue Screens Resulting From Win's Intruder Exception</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-modifying-login-credentials-on-win-11/"><u>Quick Guide to Modifying Login Credentials on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-malfunctioning-office-notification-system/"><u>Solving Malfunctioning Office Notification System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-msvcr120dll-missing-message-on-desktops/"><u>Navigating 'Msvcr120_dll' Missing Message on Desktops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-windows-to-run-this-application-you-must-install-net-core-error/"><u>How to Fix the Windows “To Run This Application, You Must Install .NET Core” Error</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-amp-up-your-sessions-with-essential-tips-from-zooms-changer-suite/"><u>In 2024, Amp Up Your Sessions with Essential Tips From Zoom's Changer Suite</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-step-by-step-guide-to-find-youtube-hidden-videos/"><u>[New] Step-By-Step Guide to Find YouTube Hidden Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaiming-missing-power-configurations-in-win-11-os/"><u>Reclaiming Missing Power Configurations in Win 11 OS</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-strategic-approaches-to-youtube-short-glitches/"><u>[New] Strategic Approaches to YouTube Short Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lightening-up-your-browser-load-top-7-windows-apps-less-ram-intensive/"><u>Lightening Up Your Browser Load: Top 7 Windows Apps Less RAM-Intensive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keyboard-keyscalyping-restore-your-arrows-now/"><u>Keyboard Keyscalyping? Restore Your Arrows Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-set-up-custom-hotkeys-for-pasting-pre-defined-text-snippets-in-windows-10-and-11/"><u>How to Set Up Custom Hotkeys for Pasting Pre-Defined Text Snippets in Windows 10 & 11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/setting-up-your-youtube-studio-essential-equipment-list-for-2024/"><u>Setting Up Your YouTube Studio  Essential Equipment List for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/invisible-culprits-affecting-windows-11s-efficiency/"><u>Invisible Culprits Affecting Windows 11'S Efficiency</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-motorola-edge-40-drfone-by-drfone-virtual-android/"><u>In 2024, Can I use iTools gpx file to catch the rare Pokemon On Motorola Edge 40 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-in-game-audio-output-solving-windows-issues-in-valorant/"><u>Realigning In-Game Audio Output: Solving Windows Issues in Valorant</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-oppo-reno-11f-5g-drfone-by-drfone-virtual-android/"><u>The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Oppo Reno 11F 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-voice-commands-xbox-and-pc-synergy/"><u>Mastering Voice Commands: Xbox & PC Synergy</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-from-ordinary-to-spectacular-making-wow-worthy-tiktok-videos-with-templates/"><u>[New] In 2024, From Ordinary to Spectacular  Making Wow-Worthy TikTok Videos with Templates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-to-windows-11-character-map/"><u>Step-by-Step to Windows 11 Character Map</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seize-the-deal-unmissable-black-friday-612-win10/"><u>Seize the Deal: Unmissable Black Friday - $6.12 Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-remove-the-background-of-an-image-using-paint-or-paint-3d/"><u>How to Remove the Background of an Image Using Paint or Paint 3D</u></a></li>
<li><a href="https://win11-tips.techidaily.com/peak-potential-identifying-the-top-pc-boosters-for-windows/"><u>Peak Potential: Identifying the Top PC Boosters for Windows</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-can-we-bypass-itel-a60s-frp-by-drfone-android/"><u>In 2024, How Can We Bypass Itel A60s FRP?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-c0000005-error-on-your-pcs-operating-system/"><u>Remedy for C0000005 Error on Your PC's Operating System</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-unleash-creativity-with-free-excellent-facebook-picture-makers/"><u>[Updated] In 2024, Unleash Creativity with Free, Excellent Facebook Picture Makers</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-itel-p55-5g-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock Itel P55 5G Phone Pattern Lock without Factory Reset</u></a></li>
</ul></div>
