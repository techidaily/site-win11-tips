---
title: Expanding Accessibility to External Devices in Explorer
date: 2024-11-25T16:50:54.881Z
updated: 2024-11-27T17:00:01.561Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Expanding Accessibility to External Devices in Explorer
excerpt: This Article Describes Expanding Accessibility to External Devices in Explorer
keywords: Device Access Expansion,Explorer Accessibility,Global Device Connectivity,Explore Device Integration,Cross-Platform Interface,Broadening External Device Use,Universal Device Linkage
thumbnail: https://thmb.techidaily.com/1b3acf6f92837e9104aa399e6aa268354b94b6b827af6bb095b68b19082ca48f.png
---

## Expanding Accessibility to External Devices in Explorer

 To access the D: drive, you normally have to open File Explorer, click on **This PC** in the Navigation pane, and expand the **Devices and drives** section. With a simple hack, you can add it to the Navigation pane so you can easily access it straight from there. It will require you to tweak the Windows Registry, but don’t worry; we'll show you an extremely easy way of going about it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lp78eFEGwVU?si=-4orJBLvJJrggCJ2&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Before You Proceed…

 We are going to [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/) to add the D: drive to the Navigation Pane. This file will make changes to the Windows registry, and you need to be careful [not to mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/). A slip-up could make Windows unusable.

 Furthermore, we highly recommend that you learn how to [back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). That way, you have a way of returning it to the state it was in before you made any changes that broke it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xtylXDY9YfA?si=VonzSiDFGCpJm2uC&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/6KXVWj6Ar1M?si=Cd_jktmoN3e9OzH3&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Next, double-click the Registry file you just created and click **Yes** on the UAC prompt. You’ll then be asked if you want to continue with the merge, so click **Yes**. Afterward, press **Win + E** to open File Explorer.

![the D drive showing in the bottom section of the Navigation pane on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/d-drive-nav-pane.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SyMZxS9479s?si=0T6zZpyN2LBftFTM&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Create an Easier Way to Access the D: Drive on Your Windows Computer

 With this guide, you will remove an extra step when accessing the D: drive on your Windows computer. Once you have created the registry files, adding and removing the D: drive from the Navigation pane will be easy. While the registry files are safe, don’t forget to create a backup of your Registry or a system restore point for good measure.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-discerning-true-value-from-recordcasts-promises/"><u>[New] In 2024, Discerning True Value From RecordCast’s Promises</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-adjust-your-timeline-facebook-look-back-guide/"><u>[Updated] Adjust Your Timeline Facebook Look Back Guide</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-demystifying-the-language-of-virtuality-for-2024/"><u>[Updated] Demystifying the Language of Virtuality for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-eliminate-blackout-issues-with-game-capture-apps-for-2024/"><u>[Updated] Eliminate Blackout Issues with Game Capture Apps for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-pivot-points-revolutionize-your-youtube-angles-with-ease/"><u>[Updated] In 2024, Pivot Points Revolutionize Your YouTube Angles with Ease</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/avchd-mts-converter-for-redmi-note-13-pro-5g-by-aiseesoft-video-converter-play-mts-on-android/"><u>AVCHD MTS Converter for Redmi Note 13 Pro 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-incompatible-input-on-windows-for-vlc-player/"><u>Fixing Incompatible Input on Windows for VLC Player</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-address-error-code-0xc0000001-in-windows/"><u>How To Address Error Code 0XC0000001 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-elevate-your-login-security-ditching-the-pin-method-in-windows-11/"><u>How to Elevate Your Login Security: Ditching the PIN Method in Windows 11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-prime-choices-the-premier-portable-devices-for-editors/"><u>In 2024, Prime Choices The Premier Portable Devices for Editors</u></a></li>
<li><a href="https://buynow-info.techidaily.com/maxing-out-your-wallet-for-max-headphones/"><u>Maxing Out Your Wallet for Max Headphones?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/nearby-sharing-evaluation-google-versus-windows-protocol/"><u>Nearby Sharing Evaluation: Google Versus Windows Protocol</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-fixing-windows-11s-microsoft-store-error/"><u>Tips for Fixing Windows 11'S Microsoft Store Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/triumphant-tech-reclamation-the-three-step-windows-fixes/"><u>Triumphant Tech Reclamation: The Three-Step Windows Fixes</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-the-potency-of-akasa-geckos-ssd-cooler-an-elite-blower-heatsink-for-optimal-drive-performance/"><u>Unveiling the Potency of Akasa Gecko's SSD Cooler: An Elite Blower Heatsink for Optimal Drive Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-boot-struggles-here-are-5-secure-boot-remedies/"><u>Windows Boot Struggles? Here Are 5 Secure Boot Remedies</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    