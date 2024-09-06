---
title: Streamlining Access to Non-Local Files
date: 2024-09-05T19:35:23.434Z
updated: 2024-09-06T19:35:23.434Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Streamlining Access to Non-Local Files
excerpt: This Article Describes Streamlining Access to Non-Local Files
keywords: File Access Streamline,Local File Retrieval,Remote Data Ease,External Content Open,Non-Local Share,Cross-File Access,Global File Availability
thumbnail: https://thmb.techidaily.com/efe03172267db8e41dde950b174798601940a22588399da557fc77a3f3ce0d36.jpeg
---

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137225/26400" target="_top" id="2137225">
  <img src="//a.impactradius-go.com/display-ad/26400-2137225" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137225/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Streamlining Access to Non-Local Files

 To access the D: drive, you normally have to open File Explorer, click on **This PC** in the Navigation pane, and expand the **Devices and drives** section. With a simple hack, you can add it to the Navigation pane so you can easily access it straight from there. It will require you to tweak the Windows Registry, but don’t worry; we'll show you an extremely easy way of going about it.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123508/26400" target="_top" id="2123508">
  <img src="//a.impactradius-go.com/display-ad/26400-2123508" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123508/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Before You Proceed…

 We are going to [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/) to add the D: drive to the Navigation Pane. This file will make changes to the Windows registry, and you need to be careful [not to mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/). A slip-up could make Windows unusable.

 Furthermore, we highly recommend that you learn how to [back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). That way, you have a way of returning it to the state it was in before you made any changes that broke it.

## How Do I Add the D: Drive to the Navigation Pane in File Explorer?

 Start by pressing **Win + S** to bring up Windows Search. Then, type **notepad** in the Search box, and when Notepad shows up in the search results, click on it to launch it.

![The Notepad search result](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/notepad-search-result.png)

<!-- affiliate ads begin -->
<span id="1977028">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977028.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977028">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977028.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977028%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977028/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://25home.pxf.io/c/5597632/2123471/16836" target="_top" id="2123471">
  <img src="//a.impactradius-go.com/display-ad/16836-2123471" border="0" alt="https://techidaily.com" width="234" height="60"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123471/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Next, double-click the Registry file you just created and click **Yes** on the UAC prompt. You’ll then be asked if you want to continue with the merge, so click **Yes**. Afterward, press **Win + E** to open File Explorer.

![the D drive showing in the bottom section of the Navigation pane on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/d-drive-nav-pane.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137220/26400" target="_top" id="2137220">
  <img src="//a.impactradius-go.com/display-ad/26400-2137220" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137220/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2120867/26400?prodsku=mars" target="_top" id="2120867">
  <img src="//a.impactradius-go.com/display-ad/26400-2120867" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2120867/26400?prodsku=mars" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Create an Easier Way to Access the D: Drive on Your Windows Computer

 With this guide, you will remove an extra step when accessing the D: drive on your Windows computer. Once you have created the registry files, adding and removing the D: drive from the Navigation pane will be easy. While the registry files are safe, don’t forget to create a backup of your Registry or a system restore point for good measure.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-webster.techidaily.com/024-approved-elevate-your-video-game-top-tips-for-perfect-live-thumbnails/"><u>[New] 2024 Approved Elevate Your Video Game Top Tips for Perfect Live Thumbnails</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-unveiling-hidden-gems-facebooks-video-treasures/"><u>[New] Unveiling Hidden Gems Facebook's Video Treasures</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-journey-to-visual-impact-with-simple-lenses/"><u>2024 Approved Journey to Visual Impact with Simple Lenses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-words-behavior-opens-email-attachments-as-text-only/"><u>Customizing Word's Behavior: Opens Email Attachments as Text Only</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-windows-11-dir-is-not-empty-error-0x80070091/"><u>Dealing with Windows 11 Dir Is Not Empty Error (0X80070091)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-the-enigma-unraveling-wacatacbmls-mechanism-on-windows/"><u>Deciphering the Enigma: Unraveling Wacatac.B!ml's Mechanism on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-windows-update-numbering-systems/"><u>Demystifying Windows Update Numbering Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-windows-experience-mastering-w11-bar-use/"><u>Elevate Windows Experience: Mastering W11 Bar Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-performance-of-faulty-windows-cleaners/"><u>Enhancing Performance of Faulty Windows Cleaners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-user-experience-3-ways-to-boost-mouse-speed/"><u>Enhancing User Experience: 3 Ways to Boost Mouse Speed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-picks-best-torrent-software-for-windows-devices/"><u>Expert Picks: Best Torrent Software for Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-diagnosing-and-rectifying-incorrect-pc-cpu-readings/"><u>Guide to Diagnosing and Rectifying Incorrect PC CPU Readings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-disable-or-remove-hyper-v-in-windows-11/"><u>How to Disable or Remove Hyper-V in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-see-recently-opened-files-on-windows/"><u>How to See Recently Opened Files on Windows</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-motorola-moto-g73-5g-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>In 2024, How to Cast Motorola Moto G73 5G Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-the-best-8-vpn-hardware-devices-reviewed-on-poco-c55-drfone-by-drfone-virtual-android/"><u>In 2024, The Best 8 VPN Hardware Devices Reviewed On Poco C55 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovating-windows-subsystem-for-android-resource-utilization/"><u>Innovating Windows Subsystem for Android Resource Utilization</u></a></li>
<li><a href="https://win-amazing.techidaily.com/lenovo-ideapad-t430-drivers-seamless-download-and-installation-guide-for-windows-1087-users/"><u>Lenovo IdeaPad T430 Drivers: Seamless Download & Installation Guide for Windows 10/8/7 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-of-windows-faults-0x0000004e-demystified/"><u>Mastery of Windows Faults: 0X0000004E Demystified</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-d3d11-gpu-compatibility-issues-on-win11win10/"><u>Mitigating D3D11 GPU Compatibility Issues on Win11/Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfecting-wins-alert-settings-on-windows-11/"><u>Perfecting Wins Alert Settings on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalized-group-policy-application-on-windows-users-versions-1111/"><u>Personalized Group Policy Application on Windows Users, Versions 11/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/power-lockdown-effortless-methods-for-terminating-user-in-win11/"><u>Power Lockdown: Effortless Methods for Terminating User in Win11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/privacy-paranoia-the-risks-of-sharing-with-chatgpt/"><u>Privacy Paranoia: The Risks of Sharing with ChatGPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-guide-stop-vmware-virtual-machine-error-in-win11/"><u>Quick Fix Guide: Stop VMware Virtual Machine Error in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-common-windows-onedrive-problems/"><u>Quick Fixes for Common Windows OneDrive Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rebooting-astra-pilot-link-on-latest-os-ws11/"><u>Rebooting Astra Pilot Link on Latest OS, WS11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefining-digital-canvas-4-key-upgrades-to-microsoft-paint/"><u>Redefining Digital Canvas: 4 Key Upgrades to Microsoft Paint</u></a></li>
<li><a href="https://techidaily.com/remove-the-lock-of-poco-f5-5g-by-drfone-android-unlock-android-unlock/"><u>Remove the lock of Poco F5 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-failed-ms-pc-manager-setup-in-windows-os/"><u>Resolve Failed MS PC Manager Setup in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reworking-the-windows-experience-a-triad-of-tips/"><u>Reworking the Windows Experience: A Triad of Tips</u></a></li>
<li><a href="https://win-amazing.techidaily.com/seamless-setup-essential-linksys-ae2500-drivers-available-for-immediate-download/"><u>Seamless Setup: Essential Linksys AE2500 Drivers Available for Immediate Download</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-error-30005-creating-files-unsuccessful-in-windows/"><u>Solving Error 30005: Creating Files Unsuccessful in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-turn-offon-smartfiltration-on-windows-11/"><u>Steps to Turn Off/On SmartFiltration on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-handling-windows-11s-read-only-files/"><u>Strategies for Handling Windows 11'S Read-Only Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-approach-from-mkv-to-mp4-on-windows-pcs/"><u>Streamlined Approach: From MKV to MP4 on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/supercharge-outlook-performance-on-your-windows-machine/"><u>Supercharge Outlook Performance on Your Windows Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swivel-pictures-perfectly-in-windows-11/"><u>Swivel Pictures Perfectly in Windows 11</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-steps-to-resolve-bloodhunts-performance-issues-on-your-computer/"><u>Troubleshooting Steps to Resolve Bloodhunt's Performance Issues on Your Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ultimate-weather-tech-selection-for-win-devices/"><u>Ultimate Weather Tech Selection for Win Devices</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/unboxing-connectivity-an-experts-opinion-on-the-features-of-mobvoi-ticwatch-pro-4g/"><u>Unboxing Connectivity: An Expert's Opinion on the Features of Mobvoi Ticwatch Pro 4G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-access-restrictions-on-windows-pc/"><u>Unlock Access Restrictions on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-windows-app-interactivity-via-streamlined-connection-solutions/"><u>Upgrade Window's App Interactivity via Streamlined Connection Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-developing-a-security-focused-removal-applet/"><u>Windows 11: Developing a Security-Focused Removal Applet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-file-treasure-hunting-mastering-the-sixest-strategies-for-copying-paths/"><u>Windows File Treasure Hunting: Mastering the Sixest Strategies for Copying Paths</u></a></li>
<li><a href="https://win11-tips.techidaily.com/xbox-wont-start-try-these-fixes-for-windows-users/"><u>Xbox Won't Start? Try These Fixes for Windows Users</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>