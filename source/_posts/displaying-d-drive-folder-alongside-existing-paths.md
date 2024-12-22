---
title: "Displaying D: Drive Folder Alongside Existing Paths"
date: 2024-12-20T06:11:38.775Z
updated: 2024-12-21T18:18:09.818Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Displaying D: Drive Folder Alongside Existing Paths"
excerpt: "This Article Describes Displaying D: Drive Folder Alongside Existing Paths"
keywords: Show Drive in Folder,Drive Folder Display,Drive Path Integration,Existing Folders with Drive,D,Folder Drive Alignment,Drive Folder Syncing
thumbnail: https://thmb.techidaily.com/2ceae87a9b9364e8de7f8199f6943542799e9e444d1e94cece6744b91d0b78e1.jpg
---

## Displaying D: Drive Folder Alongside Existing Paths

 To access the D: drive, you normally have to open File Explorer, click on **This PC** in the Navigation pane, and expand the **Devices and drives** section. With a simple hack, you can add it to the Navigation pane so you can easily access it straight from there. It will require you to tweak the Windows Registry, but don’t worry; we'll show you an extremely easy way of going about it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PKZUYice-ws?si=L8iMa9T3h7TMSWdQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Before You Proceed…

 We are going to [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/) to add the D: drive to the Navigation Pane. This file will make changes to the Windows registry, and you need to be careful [not to mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/). A slip-up could make Windows unusable.

 Furthermore, we highly recommend that you learn how to [back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). That way, you have a way of returning it to the state it was in before you made any changes that broke it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X18Dq7rV-xI?si=twFfXIPD0TFmC5EM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Do I Add the D: Drive to the Navigation Pane in File Explorer?

 Start by pressing **Win + S** to bring up Windows Search. Then, type **notepad** in the Search box, and when Notepad shows up in the search results, click on it to launch it.

![The Notepad search result](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/notepad-search-result.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/umvX4ZdWbxk?si=tPXL0-Kzf9SQaY8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Create an Easier Way to Access the D: Drive on Your Windows Computer

 With this guide, you will remove an extra step when accessing the D: drive on your Windows computer. Once you have created the registry files, adding and removing the D: drive from the Navigation pane will be easy. While the registry files are safe, don’t forget to create a backup of your Registry or a system restore point for good measure.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-navigating-the-world-of-mac-screenshot-with-confidence/"><u>[New] Navigating the World of Mac Screenshot with Confidence</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-simplified-guide-to-recording-pc-screens-for-hp-users/"><u>[New] Simplified Guide to Recording PC Screens for HP Users</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-from-ordinary-to-stunning-photo-tile-magic/"><u>[Updated] From Ordinary to Stunning Photo Tile Magic</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-from-views-to-valuables-the-ultimate-video-income-play/"><u>[Updated] In 2024, From Views to Valuables The Ultimate Video Income Play</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-streaming-mastery-with-obs-game-mode-for-2024/"><u>[Updated] Streaming Mastery with OBS Game Mode for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-quick-guide-to-xiaomi-redmi-note-12-pro-4g-frp-bypass-instantly-by-drfone-android/"><u>A Quick Guide to Xiaomi Redmi Note 12 Pro 4G FRP Bypass Instantly</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/audiovisual-alchemy-transforming-powerpoint-into-engagement-for-2024/"><u>Audiovisual Alchemy Transforming PowerPoint Into Engagement for 2024</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/best-anti-tracker-software-for-apple-iphone-xs-max-drfone-by-drfone-virtual-ios/"><u>Best Anti Tracker Software For Apple iPhone XS Max | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-internal-failure-in-win11win10-connections/"><u>Correcting Internal Failure in Win11/Win10 Connections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-taskbar-functionality-with-new-contextual-folders/"><u>Enhancing Taskbar Functionality with New Contextual Folders</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-11-pro-max-to-the-previous-ios-system-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone 11 Pro Max to the Previous iOS System Version? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-spatial-sound-in-windows-11/"><u>How to Enable Spatial Sound in Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-xr-to-others-android-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone XR To Others Android Devices? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-the-100-obstacle-in-windows-update-processes/"><u>Overcome the 100% Obstacle in Windows Update Processes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pinpointing-and-purging-error-0xa00f4289-in-win11s-webcam/"><u>Pinpointing & Purging Error 0xA00F4289 in Win11's Webcam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-address-phantom-devices-in-pcs/"><u>Strategies to Address Phantom Devices in PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-strategies-for-tackling-windows-camera-errors/"><u>Swift Strategies for Tackling Windows Camera Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unsticking-windows-update-quick-repair-tips/"><u>Unsticking Windows Update: Quick Repair Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-how-to-lock-your-screens-look/"><u>Windows 11: How to Lock Your Screen's Look</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    