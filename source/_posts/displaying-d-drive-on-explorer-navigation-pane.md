---
title: "Displaying D: Drive on Explorer Navigation Pane"
date: 2024-12-03T21:16:44.109Z
updated: 2024-12-06T21:23:53.803Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Displaying D: Drive on Explorer Navigation Pane"
excerpt: "This Article Describes Displaying D: Drive on Explorer Navigation Pane"
keywords: Drive Display,Explorer Panes,Explore Navigation,Drive Views,File Browser,Navigational Panes,Storage Shows
thumbnail: https://thmb.techidaily.com/7f8f4d19272d4759318cbc88d919ca0c7c48f620077177c71b194a7d51d8ecab.jpg
---

## Displaying D: Drive on Explorer Navigation Pane

 To access the D: drive, you normally have to open File Explorer, click on **This PC** in the Navigation pane, and expand the **Devices and drives** section. With a simple hack, you can add it to the Navigation pane so you can easily access it straight from there. It will require you to tweak the Windows Registry, but don’t worry; we'll show you an extremely easy way of going about it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YwOwUI47FuU?si=NK7IEELjx7_SJSl2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Before You Proceed…

 We are going to [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/) to add the D: drive to the Navigation Pane. This file will make changes to the Windows registry, and you need to be careful [not to mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/). A slip-up could make Windows unusable.

 Furthermore, we highly recommend that you learn how to [back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). That way, you have a way of returning it to the state it was in before you made any changes that broke it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lCpzYpVPIZA?si=hNte-mPRIzjvqpRy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 Next, double-click the Registry file you just created and click **Yes** on the UAC prompt. You’ll then be asked if you want to continue with the merge, so click **Yes**. Afterward, press **Win + E** to open File Explorer.

![the D drive showing in the bottom section of the Navigation pane on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/d-drive-nav-pane.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1CdWd06fCwc?si=wzg-68q0jAksPRXp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The D: drive should now be visible in the bottom part of the Navigation pane.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FATJWpNYmio?si=72ugPTb3vJXz6cAM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Do I Remove the D: Drive From the Navigation Pane in File Explorer?

 To remove the D: drive from the navigation pane, open Notepad and then copy and paste the below text:

`Windows Registry Editor Version 5.00  
  
[-HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}][HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\HideDesktopIcons\NewStartPanel]  
"{0525388b-89d9-4112-bf4d-2aaccb716a7f}"=-  
  
[-HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]`

 Save the file as **remove-d-drive-file-explorer.reg**. Afterward, double-click the registry file and click **Yes** on the UAC prompt. When asked if you want to continue with the merge, click **Yes** again.

 Now the D: drive should be gone from the navigation pane in File Explorer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/it8VkxDUdAc?si=ef6VZWR7kW4P9ikh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-links.techidaily.com/new-2024-approved-notable-industry-players-driving-vr-growth/"><u>[New] 2024 Approved Notable Industry Players Driving VR Growth</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-apple-macbook-air-vs-pro-which-m1-laptop-is-better-in-2024/"><u>[Updated] Apple MacBook Air Vs. Pro Which M1 Laptop Is Better, In 2024</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/discover-the-best-of-tech-in-the-oneplus-e-6t-top-notch-performance-meets-budget-friendliness/"><u>Discover the Best of Tech in the OnePlus E 6T: Top-Notch Performance Meets Budget Friendliness</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensure-your-computer-passes-windows-11-standards/"><u>Ensure Your Computer Passes Windows 11 Standards</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-lava-blaze-2-to-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Lava Blaze 2 To Phone | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/in-depth-solutions-correcting-risk-of-rain-2-game-crash-errors/"><u>In-Depth Solutions: Correcting Risk of Rain 2 Game Crash Errors</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/learn-british-phrases-sayings-and-slang-a-guide-to-speaking-like-a-brit/"><u>Learn British Phrases, Sayings, And Slang: A Guide To Speaking Like A Brit</u></a></li>
<li><a href="https://hardware-help.techidaily.com/mastering-the-world-of-electronics-with-toms-computer-components-guide/"><u>Mastering the World of Electronics with Tom's Computer Components Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-windows-11-service-utilization-for-enhanced-functionality/"><u>Optimizing Windows 11 Service Utilization for Enhanced Functionality</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/premium-top-11-list-audio-recording-essentials-for-2024/"><u>Premium Top 11 List - Audio Recording Essentials for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/privacy-panic-after-windows-hellos-fingerprint-vulnerability/"><u>Privacy Panic: After Windows Hello's Fingerprint Vulnerability</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-your-path-to-victory-steams-approach/"><u>Resetting Your Path to Victory: Steam's Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-internal-audio-issues-with-audacity-windows-11-os/"><u>Resolving Internal Audio Issues with Audacity, Windows 11 OS</u></a></li>
<li><a href="https://buynow-info.techidaily.com/top-prime-day-bargains-unbeatable-acer-offers/"><u>Top Prime Day Bargains: Unbeatable Acer Offers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-razer-synapse-device-recognition-in-windows-11/"><u>Troubleshooting: Razer Synapse Device Recognition in Windows 11</u></a></li>
</ul></div>

