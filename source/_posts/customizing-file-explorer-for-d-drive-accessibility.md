---
title: "Customizing File Explorer for D: Drive Accessibility"
date: 2024-11-04T10:07:51.703Z
updated: 2024-11-06T18:41:00.482Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Customizing File Explorer for D: Drive Accessibility"
excerpt: "This Article Describes Customizing File Explorer for D: Drive Accessibility"
keywords: Custom File Explorer,Drive Accessibility,Explore File Drives,Personalize D,Enhanced Drive Viewing,Drive Navigate Tool,File Explorer Optimization
thumbnail: https://thmb.techidaily.com/c38adae2e42bb33172470753ec027ccdb4d1aafb812ed418ac2e91f37424af9f.jpg
---

## Customizing File Explorer for D: Drive Accessibility

 To access the D: drive, you normally have to open File Explorer, click on **This PC** in the Navigation pane, and expand the **Devices and drives** section. With a simple hack, you can add it to the Navigation pane so you can easily access it straight from there. It will require you to tweak the Windows Registry, but don’t worry; we'll show you an extremely easy way of going about it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Before You Proceed…

 We are going to [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/) to add the D: drive to the Navigation Pane. This file will make changes to the Windows registry, and you need to be careful [not to mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/). A slip-up could make Windows unusable.

 Furthermore, we highly recommend that you learn how to [back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). That way, you have a way of returning it to the state it was in before you made any changes that broke it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1972684/19272" target="_top" id="1972684">
  <img src="//a.impactradius-go.com/display-ad/19272-1972684" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972684/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How Do I Add the D: Drive to the Navigation Pane in File Explorer?

 Start by pressing **Win + S** to bring up Windows Search. Then, type **notepad** in the Search box, and when Notepad shows up in the search results, click on it to launch it.

![The Notepad search result](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/notepad-search-result.png)

<!-- affiliate ads begin -->
<span id="1993647">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993647.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993647">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993647.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993647%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993647/22993" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925565/19272" target="_top" id="1925565">
  <img src="//a.impactradius-go.com/display-ad/19272-1925565" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925565/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2112007/7443" target="_top" id="2112007">
  <img src="//a.impactradius-go.com/display-ad/7443-2112007" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2112007/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Create an Easier Way to Access the D: Drive on Your Windows Computer

 With this guide, you will remove an extra step when accessing the D: drive on your Windows computer. Once you have created the registry files, adding and removing the D: drive from the Navigation pane will be easy. While the registry files are safe, don’t forget to create a backup of your Registry or a system restore point for good measure.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-blue.techidaily.com/new-high-fidelity-on-the-big-screen-the-4k-monitor-tale-of-lgs-31mu97-b/"><u>[New] High Fidelity on the Big Screen The 4K Monitor Tale of LG's 31MU97-B</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-in-2024-a-leaders-list-of-8-online-havens-for-golden-3d-and-text/"><u>[New] In 2024, A Leader's List of 8 Online Havens for Golden 3D & Text</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-revolutionizing-storytelling-free-onlineoffline-animations/"><u>[Updated] Revolutionizing Storytelling Free Online/Offline Animations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-new-interfaces-in-windows-11-post-update-edition/"><u>Discovering New Interfaces in Windows 11 Post-Update Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-deep-into-server-management-using-iis-manager/"><u>Dive Deep Into Server Management Using IIS Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/illuminate-your-living-space-embrace-the-season/"><u>Illuminate Your Living Space, Embrace the Season</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fixing-foneazy-mockgo-not-working-on-vivo-y17s-drfone-by-drfone-virtual-android/"><u>In 2024, Fixing Foneazy MockGo Not Working On Vivo Y17s | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-full-apps-deep-dive-with-az-video-logger-pro/"><u>In 2024, Full-Apps Deep Dive with AZ Video Logger Pro</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-real-time-engagement-proven-strategies-for-facebook-video-screen-sharing/"><u>In 2024, Real-Time Engagement Proven Strategies for Facebook Video Screen Sharing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-walkthrough-for-theme-implementation-via-microsoft-store/"><u>In-Depth Walkthrough for Theme Implementation via Microsoft Store</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/latest-logitech-g-pro-driver-version-available-compatible-with-windows-os/"><u>Latest Logitech G PRO Driver Version Available: Compatible with Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-syncing-wsl-with-windows-11/"><u>Mastering the Art of Syncing WSL With Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-windows-11-soundscape-with-custom-control-commands/"><u>Optimize Windows 11 Soundscape with Custom Control Commands</u></a></li>
<li><a href="https://win-amazing.techidaily.com/seamless-guide-to-updating-and-downloading-sata-driver-software-for-windows-machines/"><u>Seamless Guide to Updating and Downloading SATA Driver Software for Windows Machines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-win-password-update/"><u>Step-by-Step Guide to Win Password Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-eliminate-invalid-tags-from-onedrives-reparse-buffer/"><u>Tips to Eliminate Invalid Tags From OneDrive's Reparse Buffer</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-steps-for-unfreezing-path-of-exile-on-your-pcmac/"><u>Troubleshooting Steps for Unfreezing Path of Exile on Your PC/Mac</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    