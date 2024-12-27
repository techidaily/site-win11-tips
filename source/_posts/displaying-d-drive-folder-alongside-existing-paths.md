---
title: "Displaying D: Drive Folder Alongside Existing Paths"
date: 2024-12-20T22:07:03.227Z
updated: 2024-12-27T20:14:28.100Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/jvwX82j3ci0?si=gAWoovjXgs3m1d7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Before You Proceed…

 We are going to [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/) to add the D: drive to the Navigation Pane. This file will make changes to the Windows registry, and you need to be careful [not to mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/). A slip-up could make Windows unusable.

 Furthermore, we highly recommend that you learn how to [back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). That way, you have a way of returning it to the state it was in before you made any changes that broke it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Do I Add the D: Drive to the Navigation Pane in File Explorer?

 Start by pressing **Win + S** to bring up Windows Search. Then, type **notepad** in the Search box, and when Notepad shows up in the search results, click on it to launch it.

![The Notepad search result](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/notepad-search-result.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aG3NRuHrIJg?si=HwzwD0RXmrzIXX1V" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/aRMCbJxLuwE?si=E5sfJvoqkv1qCMWz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Next, double-click the Registry file you just created and click **Yes** on the UAC prompt. You’ll then be asked if you want to continue with the merge, so click **Yes**. Afterward, press **Win + E** to open File Explorer.

![the D drive showing in the bottom section of the Navigation pane on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/d-drive-nav-pane.jpg)

 The D: drive should now be visible in the bottom part of the Navigation pane.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pRR3Oq03EuE?si=ZTy8-WH0AesA9zRh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-files.techidaily.com/new-2024-approved-exploring-new-horizons-top-5-samsung-gear-vr-games/"><u>[New] 2024 Approved Exploring New Horizons - Top 5 Samsung Gear VR Games</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-illustrate-like-a-pro-selecting-superior-vector-image-creators/"><u>[New] Illustrate Like a Pro Selecting Superior Vector Image Creators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combatting-unstable-pointer-in-windows-environments/"><u>Combatting Unstable Pointer in Windows Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-wallet-power-with-premium-w11-pro-deals/"><u>Elevate Wallet Power with Premium W11 Pro Deals</u></a></li>
<li><a href="https://buynow-help.techidaily.com/expert-look-at-the-high-performance-huion-inspiroy-g10t-drawing-board-stellar-construct-and-efficacy-unveiled/"><u>Expert Look at the High-Performance Huion Inspiroy G10T Drawing Board - Stellar Construct and Efficacy Unveiled</u></a></li>
<li><a href="https://technical-tips.techidaily.com/exploring-apples-latest-ai-innovations-from-wwdc-underwhelming-advancements-and-my-relief-tech-insights/"><u>Exploring Apple's Latest AI Innovations From WWDC: Underwhelming Advancements and My Relief | Tech Insights</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-google-frp-lock-on-vivo-v27e-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock on Vivo V27e Devices</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-pc-screen-to-tecno-pova-6-pro-5g-phones-drfone-by-drfone-android/"><u>How to Mirror PC Screen to Tecno Pova 6 Pro 5G Phones? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-swiftly-launch-your-computers-diagnostic-mode/"><u>How to Swiftly Launch Your Computer's Diagnostic Mode</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1722178437843-live-traffic-updates/"><u>Live Traffic Updates:</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-disk-utility-windows-1011-edition-techniques/"><u>Navigating Disk Utility: Windows 10/11 Edition Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-access-essential-windows-keyboard-tricks-for-efficiency/"><u>Quick Access: Essential Windows Keyboard Tricks for Efficiency</u></a></li>
<li><a href="https://win-amazing.techidaily.com/reliable-techniques-for-updating-and-installing-amd-ryzen-gpu-drivers-safely/"><u>Reliable Techniques for Updating & Installing AMD Ryzen GPU Drivers Safely</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-minimum-spec-requirements-conflicts-with-intel-graphics-errors/"><u>Resolving Minimum Spec Requirements Conflicts with Intel Graphics Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/savvy-shoppers-secret-buy-now-for-612-life-win10/"><u>Savvy Shoppers' Secret: Buy Now for $6.12 Life Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-significance-and-risks-of-deleting-pagefilesys/"><u>The Significance and Risks of Deleting Pagefile.sys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unallocated-drive-letters-in-windows-explained-and-how-to-fix-it/"><u>Unallocated Drive Letters in Windows Explained & How to Fix It</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/unlocking-security-potential-video-tutorial-on-deploying-bitrasers-erasure-solutions-for-large-scale-environments/"><u>Unlocking Security Potential: Video Tutorial on Deploying BitRaser's Erasure Solutions for Large-Scale Environments</u></a></li>
<li><a href="https://discover-cheats.techidaily.com/upgrading-from-windows-10-to-windows-11-transfer-your-profile-with-ease-using-these-three-techniques/"><u>Upgrading From Windows 10 to Windows 11? Transfer Your Profile with Ease Using These Three Techniques</u></a></li>
</ul></div>

