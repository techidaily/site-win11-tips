---
title: Including Third-Party Storage on File Explorer
date: 2024-08-16T02:30:38.833Z
updated: 2024-08-17T02:30:38.833Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Including Third-Party Storage on File Explorer
excerpt: This Article Describes Including Third-Party Storage on File Explorer
keywords: CloudFileStorage,FileExplorerIntegration,ExtraBackupOptions,StorageToolsAccess,SecureSyncPlatforms,ThirdPartySaving,ExplorerCloudUploading
thumbnail: https://thmb.techidaily.com/0275b65ec50c26c096fbd58891ad5416742f7595ba3ecd2f30cf7442df5bd214.png
---

## Including Third-Party Storage on File Explorer

 To access the D: drive, you normally have to open File Explorer, click on **This PC** in the Navigation pane, and expand the **Devices and drives** section. With a simple hack, you can add it to the Navigation pane so you can easily access it straight from there. It will require you to tweak the Windows Registry, but don’t worry; we'll show you an extremely easy way of going about it.

## Before You Proceed…

 We are going to [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/) to add the D: drive to the Navigation Pane. This file will make changes to the Windows registry, and you need to be careful [not to mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/). A slip-up could make Windows unusable.

 Furthermore, we highly recommend that you learn how to [back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). That way, you have a way of returning it to the state it was in before you made any changes that broke it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
## How Do I Add the D: Drive to the Navigation Pane in File Explorer?

 Start by pressing **Win + S** to bring up Windows Search. Then, type **notepad** in the Search box, and when Notepad shows up in the search results, click on it to launch it.

![The Notepad search result](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/notepad-search-result.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
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
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Next, double-click the Registry file you just created and click **Yes** on the UAC prompt. You’ll then be asked if you want to continue with the merge, so click **Yes**. Afterward, press **Win + E** to open File Explorer.

![the D drive showing in the bottom section of the Navigation pane on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/d-drive-nav-pane.jpg)
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The D: drive should now be visible in the bottom part of the Navigation pane.

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
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
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-from-zero-to-hero-amplifying-youtube-influence-via-famebit-partnerships/"><u>[New] In 2024, From Zero to Hero  Amplifying YouTube Influence via FameBit Partnerships</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-access-high-res-fb-media-files/"><u>[Updated] In 2024, Access High Res FB Media Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-reasons-to-use-the-new-outlook-app-on-windows/"><u>9 Reasons to Use the New Outlook App on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-fresh-windows-11-approach-to-system-cleanliness/"><u>A Fresh Windows 11 Approach to System Cleanliness</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/accent-across-the-seas-from-british-to-american-cockney-isms/"><u>Accent Across the Seas: From British to American Cockney-Isms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automating-iphones-calendar-into-windows-os/"><u>Automating iPhone's Calendar Into Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaching-windows-login-restrictions-a-quick-guide/"><u>Breaching Windows Login Restrictions: A Quick Guide</u></a></li>
<li><a href="https://techtrends.techidaily.com/bypassing-equipment-limits-to-watch-the-roku-channel-online/"><u>Bypassing Equipment Limits to Watch the Roku Channel Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-oculus-quest-to-function-in-windows-vr/"><u>Customizing Oculus Quest to Function in Windows VR</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dial-up-decibels-the-top-4-programs-to-increase-volume-on-windows/"><u>Dial Up Decibels: The Top 4 Programs to Increase Volume on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/error-code-0x80242016-stopping-windows-updates/"><u>Error Code 0X80242016 Stopping Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/excellent-windows-apps-transforming-videos/"><u>Excellent Windows Apps Transforming Videos</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-hardware-analysis-by-toms-team-your-trusted-source/"><u>Expert Hardware Analysis by Tom's Team - Your Trusted Source</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-self-scrolled-windows-with-ease-and-precision/"><u>Fix Self-Scrolled Windows with Ease and Precision</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/-topics-to-cover-in-your-vlogs-for-2024/"><u>Fresh Topics to Cover in Your Vlogs for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-improving-win11-point-accuracy-and-size/"><u>Guide to Improving Win11' Point Accuracy & Size</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-tecno-pova-5-pro-location-on-twitter-drfone-by-drfone-virtual-android/"><u>How to Change your Tecno Pova 5 Pro Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-mend-flickering-screens-in-windows-11/"><u>How to Mend Flickering Screens in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rescue-your-vscode-session-w11/"><u>How to Rescue Your VSCode Session W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stop-0x0000011b-failures-in-windows-os/"><u>How to Stop 0X0000011B Failures in Windows OS</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-oneplus-ace-2withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on OnePlus Ace 2with/without a PC</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-a-oppo-reno-9a-easily-by-drfone-android/"><u>In 2024, How To Unlock a Oppo Reno 9A Easily?</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-motorola-defy-2-phone-frp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Motorola Defy 2 Phone FRP Lock</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-troubleshooting-tips-fixing-srt-from-premiere-freeze/"><u>In 2024, Troubleshooting Tips  Fixing SRT From Premiere Freeze</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/mastering-screenflow-a-guide-to-enhanced-creativity-on-macos-for-2024/"><u>Mastering ScreenFlow  A Guide to Enhanced Creativity on macOS for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-adding-wordpad-shortcut-accessibility/"><u>Mastering Windows 11: Adding WordPad Shortcut Accessibility</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ating-through-the-world-of-cosmetics-youtubes-top-artists-for-2024/"><u>Navigating Through the World of Cosmetics  YouTube's Top Artists for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcome-bluescreen-error-wdf-incompatibility-fix/"><u>Overcome BlueScreen Error: WDF Incompatibility Fix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-0x00000001-barrier-in-game-access/"><u>Overcoming the 0X00000001 Barrier in Game Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-effortless-transition-in-windows-terminals-attention-mode/"><u>Quick Fix: Effortless Transition in Windows Terminal’s Attention Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamping-gpos-a-step-by-step-guide-for-windows-users/"><u>Revamping GPOs: A Step-by-Step Guide for Windows Users</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-tips-to-boosting-internet-performance/"><u>Step-by-Step Tips to Boosting Internet Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-file-backup-with-windows-11/"><u>Streamlining File Backup with Windows 11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/structuring-panels-for-productive-interviews/"><u>Structuring Panels for Productive Interviews</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-prevent-unintentional-erasure-of-panel-settings-by-cp/"><u>Techniques to Prevent Unintentional Erasure of Panel Settings by CP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-workspace-win-11s-finest-productivity-tools/"><u>Transform Your Workspace: Win 11'S Finest Productivity Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tweak-windows-11-shutdown-procedure-for-active-operations/"><u>Tweak Windows 11 Shutdown Procedure for Active Operations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/workaround-cease-discord-startup-and-update-checks-in-windows/"><u>Workaround: Cease Discord Startup and Update Checks in Windows</u></a></li>
</ul></div>
