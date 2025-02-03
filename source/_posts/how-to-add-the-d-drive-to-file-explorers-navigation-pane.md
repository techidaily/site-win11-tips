---
title: "How to Add the D: Drive to File Explorer's Navigation Pane"
date: 2025-01-26T11:33:16.445Z
updated: 2025-02-01T01:55:29.032Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes How to Add the D: Drive to File Explorer's Navigation Pane"
excerpt: "This Article Describes How to Add the D: Drive to File Explorer's Navigation Pane"
keywords: Adding Drive in Nav Pane,D Drive File Explorer,Nav Pane Add Drive,Explore Files Access D,Drive Visibility File Explorer,Accessing D,Include D
thumbnail: https://thmb.techidaily.com/753ea2eddd8b518b4665a97d288cc75a73bb10ccbb0e89329d2b14f4c70fc588.jpg
---

## How to Add the D: Drive to File Explorer's Navigation Pane

 To access the D: drive, you normally have to open File Explorer, click on **This PC** in the Navigation pane, and expand the **Devices and drives** section. With a simple hack, you can add it to the Navigation pane so you can easily access it straight from there. It will require you to tweak the Windows Registry, but don’t worry; we'll show you an extremely easy way of going about it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qfCSLAhd4FY?si=CUBztmilaeAwl1lw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Before You Proceed…

 We are going to [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/) to add the D: drive to the Navigation Pane. This file will make changes to the Windows registry, and you need to be careful [not to mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/). A slip-up could make Windows unusable.

 Furthermore, we highly recommend that you learn how to [back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). That way, you have a way of returning it to the state it was in before you made any changes that broke it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oeSN3u4fO9M?si=Ua3Hzcil6u6akDgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/GPk8_xpN_rA?si=YbAdgsjAKsCn_UsB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Next, double-click the Registry file you just created and click **Yes** on the UAC prompt. You’ll then be asked if you want to continue with the merge, so click **Yes**. Afterward, press **Win + E** to open File Explorer.

![the D drive showing in the bottom section of the Navigation pane on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/d-drive-nav-pane.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/May-pLCUkEA?si=PGlcFZAlsp3S3beI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLlUft1ZxI0?si=pBd5QdHEE27qsNlN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://some-skills.techidaily.com/new-ultimate-guide-to-top-8-gold-text-in-3d-realms/"><u>[New] Ultimate Guide to Top 8 Gold Text in 3D Realms</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-unveiling-top-10-trending-tweets-of-2023/"><u>[New] Unveiling Top 10 Trending Tweets of 2023</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-top-5-alternatives-to-tiktok-you-should-know-updated/"><u>[Updated] In 2024, Top 5 Alternatives to TikTok You Should Know [Updated ]</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-expertise-in-action-gopro-for-dynamic-time-lapses/"><u>2024 Approved Expertise in Action GoPro for Dynamic Time-Lapses</u></a></li>
<li><a href="https://location-fake.techidaily.com/4-methods-to-turn-off-life-360-on-xiaomi-13-ultra-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>4 Methods to Turn off Life 360 On Xiaomi 13 Ultra without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clarifying-system-repair-tools-chkdsk-vs-sfc-and-dissect-processes/"><u>Clarifying System Repair Tools: Chkdsk Vs. Sfc & Dissect Processes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/converting-gmail-to-outlook-mail-on-windows/"><u>Converting Gmail to Outlook Mail on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-windows-11-camera-glitch-code-a00f4289/"><u>Correcting Windows 11 Camera Glitch Code A00F4289</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-a-smooth-wsl-2-experience-with-docker-tools/"><u>Expert Tips for a Smooth WSL 2 Experience with Docker Tools</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-card-on-google-pixel-8-pro-online-without-jailbreak-by-drfone-android/"><u>How to Unlock SIM Card on Google Pixel 8 Pro online without jailbreak</u></a></li>
<li><a href="https://ai-video.techidaily.com/new-an-exhaustive-list-of-lip-sync-apps-for-vibrant-video-creation/"><u>New An Exhaustive List of Lip Sync Apps for Vibrant Video Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-mail-app-failure-decode-windows-11s-0x800713f/"><u>Overcoming Mail App Failure: Decode Windows 11’S 0X800713F</u></a></li>
<li><a href="https://data-wizards.techidaily.com/reclaim-space-fix-error-36-in-macos-trash/"><u>Reclaim Space: Fix Error 36 in macOS Trash</u></a></li>
<li><a href="https://win11-tips.techidaily.com/script-snafus-say-goodbye-with-these-windows-fixes/"><u>Script Snafus? Say Goodbye with These Windows Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-your-productivity-in-windows-with-these-top-apps/"><u>Skyrocket Your Productivity in Windows with These Top Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-unsyncing-google-drive-on-your-pc-instantly/"><u>Troubleshoot Unsyncing Google Drive on Your PC Instantly</u></a></li>
<li><a href="https://some-tips.techidaily.com/unveiling-metas-hidden-virtual-reality-masterpiece-a-potential-game-changer-for-the-tech-world-eclipsing-apples-vision-pro/"><u>Unveiling Meta's Hidden Virtual Reality Masterpiece: A Potential Game-Changer for the Tech World, Eclipsing Apple's Vision Pro</u></a></li>
</ul></div>

