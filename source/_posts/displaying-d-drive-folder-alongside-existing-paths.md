---
title: "Displaying D: Drive Folder Alongside Existing Paths"
date: 2025-01-13T17:28:18.169Z
updated: 2025-01-18T16:23:05.643Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/SgRVYjqB70s?si=My_2cDvJVdincQRu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Before You Proceed…

 We are going to [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/) to add the D: drive to the Navigation Pane. This file will make changes to the Windows registry, and you need to be careful [not to mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/). A slip-up could make Windows unusable.

 Furthermore, we highly recommend that you learn how to [back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). That way, you have a way of returning it to the state it was in before you made any changes that broke it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vfq0vw0Spz8?si=2EAk6hW-Gb-o33_L" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Do I Add the D: Drive to the Navigation Pane in File Explorer?

 Start by pressing **Win + S** to bring up Windows Search. Then, type **notepad** in the Search box, and when Notepad shows up in the search results, click on it to launch it.

![The Notepad search result](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/notepad-search-result.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l-SCWTWpegY?si=oxTsHQkIu1v4-I6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 The D: drive should now be visible in the bottom part of the Navigation pane.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mMYEK2gtY5c?si=ytxNz_JHZkTrwb4b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/8U3ooyFiAB4?si=yXPQrDhMBEJwN2EZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-footage.techidaily.com/new-beat-boulevard-optimal-dj-video-downloads-for-2024/"><u>[New] Beat Boulevard Optimal DJ Video Downloads for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-crafting-visuals-theory-to-practice-with-colors/"><u>[New] Crafting Visuals Theory to Practice with Colors</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-mastering-text-warping-techniques-in-photos-and-videos-for-2024/"><u>[New] Mastering Text Warping Techniques in Photos & Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-the-premier-streaming-apps-of-2023-a-comprehensive-review-by-movavi/"><u>Discover the Premier Streaming Apps of 2023: A Comprehensive Review by Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/en-ligne-gratuite-pour-transformer-votre-video-wmv-en-mkv-utilisant-movavi-conversion-simple-et-rapide/"><u>En Ligne Gratuite Pour Transformer Votre Vidéo WMV en MKV Utilisant Movavi - Conversion Simple Et Rapide</u></a></li>
<li><a href="https://tech-revival.techidaily.com/exploring-the-latest-editing-additions-to-dall-e-3-room-for-improvement-still-present/"><u>Exploring the Latest Editing Additions to DALL-E 3 - Room for Improvement Still Present</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/fx360-pro-cooler-by-id-cooling-exceptional-performance-at-just-60/"><u>FX360 Pro Cooler by ID-Cooling - Exceptional Performance at Just $60</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723015815223-immediate-solutions-to-restart-fortnite-voice-chatting-no-hassle/"><u>Immediate Solutions to Restart Fortnite Voice Chatting - No Hassle!</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-ultimate-10-royale-duelists-arena/"><u>In 2024, Ultimate 10 Royale Duelists' Arena</u></a></li>
<li><a href="https://games-able.techidaily.com/superior-ssd-selection-for-ps5/"><u>Superior SSD Selection for PS5</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-selection-of-screen-recorder-tools-ranking-the-top-15-for-your-laptop/"><u>The Ultimate Selection of Screen Recorder Tools - Ranking the Top 15 for Your Laptop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-14-best-stock-video-scenes-of-2022-free-and-premium-selections/"><u>Top 14 Best Stock Video Scenes of 2022 - Free & Premium Selections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformation-gratuite-de-fichiers-jpg-en-gif-sur-internet-avec-movavi-comprendre-la-conversion-facile/"><u>Transformation Gratuite De Fichiers JPG en GIF Sur Internet Avec Movavi - Comprendre La Conversion Facile</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformez-facilement-un-mp4-en-video-flash-flv-sans-frais-movavi/"><u>Transformez Facilement Un MP4 en Vidéo Flash (FLV) Sans Frais - Movavi</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unlocking-tech-secrets-with-toms-hardware-diagnostics/"><u>Unlocking Tech Secrets with Tom's Hardware Diagnostics</u></a></li>
</ul></div>

