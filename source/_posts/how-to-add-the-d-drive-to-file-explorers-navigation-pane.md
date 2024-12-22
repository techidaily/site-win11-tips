---
title: "How to Add the D: Drive to File Explorer's Navigation Pane"
date: 2024-12-19T16:06:40.423Z
updated: 2024-12-22T03:26:59.935Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/r_wWybMqZEM?si=0nPjCQDLS2MCaQbG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Do I Add the D: Drive to the Navigation Pane in File Explorer?

 Start by pressing **Win + S** to bring up Windows Search. Then, type **notepad** in the Search box, and when Notepad shows up in the search results, click on it to launch it.

![The Notepad search result](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/notepad-search-result.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/620kcQ7Dw7w?si=a5ussGs5HV7sG3hF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/q4-YQ9Wjtfg?si=6afn1fydg_Wb9B8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Next, double-click the Registry file you just created and click **Yes** on the UAC prompt. You’ll then be asked if you want to continue with the merge, so click **Yes**. Afterward, press **Win + E** to open File Explorer.

![the D drive showing in the bottom section of the Navigation pane on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/d-drive-nav-pane.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aknYnDfODro?si=zONIVzA9FFq0rLOD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/HtM7d4dpN1I?si=2vN_xgVGD4eYGORu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Create an Easier Way to Access the D: Drive on Your Windows Computer

 With this guide, you will remove an extra step when accessing the D: drive on your Windows computer. Once you have created the registry files, adding and removing the D: drive from the Navigation pane will be easy. While the registry files are safe, don’t forget to create a backup of your Registry or a system restore point for good measure.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://eaxpv-info.techidaily.com/new-how-to-transform-your-youtube-vids-a-guide-to-softened-screens-for-2024/"><u>[New] How to Transform Your Youtube Vids A Guide to Softened Screens for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-critical-review-of-samsungs-digital-photography-advancements-for-2024/"><u>[Updated] Critical Review of Samsung's Digital Photography Advancements for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-faces-of-technology-analyzing-face-detection-in-phones-for-2024/"><u>[Updated] Faces of Technology Analyzing Face Detection in Phones for 2024</u></a></li>
<li><a href="https://win-answers.techidaily.com/accessing-your-print-job-logs-steps-to-review-printed-document-records-on-windows-11/"><u>Accessing Your Print Job Logs: Steps to Review Printed Document Records on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dodging-delayed-wow-windows-installation/"><u>Dodging Delayed WoW Windows Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortlessly-navigate-office-environment-with-windows-11s-outlook-preview/"><u>Effortlessly Navigate Office Environment with Windows 11'S Outlook Preview</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-remedying-writing-failures-in-windows-11/"><u>Guide to Remedying Writing Failures in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-address-format-required-discrepancy-in-windows/"><u>How to Address 'Format Required' Discrepancy in Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-find-ispoofer-pro-activation-key-on-xiaomi-redmi-12-5g-drfone-by-drfone-virtual-android/"><u>How to Find iSpoofer Pro Activation Key On Xiaomi Redmi 12 5G? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-full-guide-to-catch-100-iv-pokemon-using-a-map-on-nokia-c110-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Catch 100 IV Pokémon Using a Map On Nokia C110 | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/intel-driven-two-14-inch-displays-experience-the-acemagic-x1-laptop-for-under-900/"><u>Intel Driven, Two 14-Inch Displays: Experience the Acemagic X1 Laptop for Under $900</u></a></li>
<li><a href="https://techtrends.techidaily.com/macos-15-sequoia-unleashed-a-deep-dive-into-release-information-and-groundbreaking-features/"><u>MacOS 15 (Sequoia) Unleashed: A Deep Dive Into Release Information & Groundbreaking Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-windows-connection-change-nat-type-efficiently-in-win1110/"><u>Optimize Your Windows Connection: Change NAT Type Efficiently in Win11/10</u></a></li>
<li><a href="https://fox-pages.techidaily.com/resolving-the-issue-when-an-excel-spreadsheet-vanishes-post-save/"><u>Resolving the Issue When an Excel Spreadsheet Vanishes Post-Save</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-and-fixing-the-root-of-virtualbox-usb-device-disconnection/"><u>Uncovering and Fixing the Root of VirtualBox USB Device Disconnection</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    