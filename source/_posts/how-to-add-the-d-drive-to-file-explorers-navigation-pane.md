---
title: "How to Add the D: Drive to File Explorer's Navigation Pane"
date: 2025-01-22T00:29:49.296Z
updated: 2025-01-24T21:36:22.653Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Before You Proceed…

 We are going to [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/) to add the D: drive to the Navigation Pane. This file will make changes to the Windows registry, and you need to be careful [not to mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/). A slip-up could make Windows unusable.

 Furthermore, we highly recommend that you learn how to [back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). That way, you have a way of returning it to the state it was in before you made any changes that broke it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SDUPd69Qfls?si=uIGZG-riskwmVZYg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Do I Add the D: Drive to the Navigation Pane in File Explorer?

 Start by pressing **Win + S** to bring up Windows Search. Then, type **notepad** in the Search box, and when Notepad shows up in the search results, click on it to launch it.

![The Notepad search result](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/notepad-search-result.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oySc0DiqmKc?si=8pynRzuhlq2RUPZ6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LdVT_-3gESA?si=_HfjpbUEHSRKTXjt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Next, double-click the Registry file you just created and click **Yes** on the UAC prompt. You’ll then be asked if you want to continue with the merge, so click **Yes**. Afterward, press **Win + E** to open File Explorer.

![the D drive showing in the bottom section of the Navigation pane on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/d-drive-nav-pane.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15TKQ-BOENI?si=Ri4B2AuxAdi0Bglz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-videos.techidaily.com/updated-converting-youtube-journeys-into-animated-expressions-a-comprehensive-guide-for-mobiledesktop-users/"><u>[Updated] Converting YouTube Journeys Into Animated Expressions A Comprehensive Guide for Mobile/Desktop Users</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-streamlining-production-processes-a-magix-video-pro-x-perspective/"><u>[Updated] In 2024, Streamlining Production Processes A Magix Video Pro X Perspective</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-laughter-layouts-design-meme-magic-on-kapwing/"><u>[Updated] Laughter Layouts Design Meme Magic on Kapwing</u></a></li>
<li><a href="https://solve-popular.techidaily.com/cookiebot-enhanced-experience-optimize-your-website-with-cutting-edge-analytics/"><u>Cookiebot-Enhanced Experience: Optimize Your Website with Cutting-Edge Analytics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-disk-space-management-using-windows-autodelete-functionality/"><u>Effective Disk Space Management Using Windows' AutoDelete Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-chromes-incorrect-system-time-windows-wide/"><u>Fixing Chrome's Incorrect System Time Windows-Wide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-live-sound-input-for-obs-on-windows-11/"><u>How to Enable Live Sound Input for OBS on Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-use-face-id-to-pay-for-apple-tvplus-on-iphone-14-pro-max-by-drfone-ios-unlock-ios-unlock/"><u>How to Use Face ID to Pay for Apple TV+ on iPhone 14 Pro Max</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-remove-forgotten-pin-of-your-vivo-y200-by-drfone-android/"><u>In 2024, How to Remove Forgotten PIN Of Your Vivo Y200</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-which-is-the-best-fake-gps-joystick-app-on-vivo-y100-drfone-by-drfone-virtual-android/"><u>In 2024, Which is the Best Fake GPS Joystick App On Vivo Y100? | Dr.fone</u></a></li>
<li><a href="https://discover-great.techidaily.com/mastering-torrent-sharing-how-to-install-and-utilize-elementum-burst-alongside-gaia/"><u>Mastering Torrent Sharing: How To Install & Utilize Elementum Burst Alongside Gaia</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-missing-startup-icons-in-task-manager/"><u>Overcoming Missing Startup Icons in Task Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-obscured-wireless-connections-windows/"><u>Overcoming Obscured Wireless Connections Windows</u></a></li>
<li><a href="https://tech-hub.techidaily.com/sham-tech-outsmarted-keep-your-data-secure-from-fakes/"><u>Sham Tech Outsmarted: Keep Your Data Secure From Fakes!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-windows-11-snipping-tool-edits/"><u>The Ultimate Guide to Windows 11 Snipping Tool Edits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-outlook-preview-setup-steps/"><u>Unveiling Windows' Outlook Preview Setup Steps</u></a></li>
</ul></div>

