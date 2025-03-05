---
title: "How to Add the D: Drive to File Explorer's Navigation Pane"
date: 2025-02-27T01:40:09.163Z
updated: 2025-03-04T21:52:41.922Z
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
<li><a href="https://article-posts.techidaily.com/updated-2024-approved-essential-insights-for-aspiring-editors-into-final-cut-pro/"><u>[Updated] 2024 Approved Essential Insights for Aspiring Editors Into Final Cut Pro</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-channel-name-magic-ideas-for-impactful-titles-for-2024/"><u>[Updated] Channel Name Magic Ideas for Impactful Titles for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-designing-eye-catching-instagram-post-previews/"><u>[Updated] In 2024, Designing Eye-Catching Instagram Post Previews</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/agriculture-amalgamations-best-friendly-farmers-game-roster-for-2024/"><u>Agriculture Amalgamations Best Friendly Farmer's Game Roster for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/easy-methods-to-convert-fbx-format-to-obj-perfect-for-3d-printer-readiness/"><u>Easy Methods to Convert .fbx Format to .obj - Perfect for 3D Printer Readiness</u></a></li>
<li><a href="https://fox-direct.techidaily.com/expert-online-workshop-title-author-for-2024/"><u>Expert Online Workshop Title Author for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/fixes-for-preventing-slime-rancher-2-from-crashing-on-your-pc-a-step-by-step-guide/"><u>Fixes for Preventing Slime Rancher 2 From Crashing on Your PC: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-re-register-microsoft-store-apps-on-windows-11-and-11/"><u>How to Re-Register Microsoft Store Apps on Windows 11 & 11</u></a></li>
<li><a href="https://fox-links.techidaily.com/in-2024-leading-5-underwater-filters-for-gopro-videos/"><u>In 2024, Leading 5 Underwater Filters for Gopro Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-list-highest-calibre-ds-emulation-on-pc/"><u>Master List: Highest Calibre DS Emulation on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/old-computers-reimagined-windows-11-with-to-go-and-rufus-masterclass/"><u>Old Computers Reimagined: Windows 11 with To Go and Rufus Masterclass</u></a></li>
<li><a href="https://win11-tips.techidaily.com/opening-windows-secrets-with-precision/"><u>Opening Windows Secrets with Precision</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secrets-to-optimizing-battery-usage-in-windows-systems/"><u>Secrets to Optimizing Battery Usage in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-setup-for-new-win-11-users-via-double-clicked-apks/"><u>Simplified Setup for New Win 11 Users via Double-Clicked APKs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skip-wsl-save-time/"><u>Skip WSL, Save Time!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-walkthrough-reading-comics-on-win11/"><u>Step-by-Step Walkthrough: Reading Comics on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategic-disk-management-visualize-and-maximize-with-altwindirstat/"><u>Strategic Disk Management: Visualize & Maximize with AltWinDirStat</u></a></li>
<li><a href="https://fox-helps.techidaily.com/unlock-the-power-of-animation-infusing-life-into-your-ig-story-texts-for-2024/"><u>Unlock the Power of Animation Infusing Life Into Your IG Story Texts for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-the-ai-music-forerunners-crafting-harmonies-for-a-new-era/"><u>Updated 2024 Approved The AI Music Forerunners Crafting Harmonies for a New Era</u></a></li>
</ul></div>

