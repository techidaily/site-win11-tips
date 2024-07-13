---
title: How To Efficiently Extract OneDrive From Windows Explorer
date: 2024-07-12T17:13:01.437Z
updated: 2024-07-13T17:13:01.437Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How To Efficiently Extract OneDrive From Windows Explorer
excerpt: This Article Describes How To Efficiently Extract OneDrive From Windows Explorer
keywords: WinExplorerOneDriveSync,OneDriveAccessTips,ExploreOneDriveEfficiency,StreamlineOneDriveWindows,OptimizeDriveExtraction,WindowsOneDriveTools,SyncOneDriveFastlyte
thumbnail: https://thmb.techidaily.com/5f042bcf8e18adcc53cbb8d889707c4f827028b312f2b21172b0735c2d2d47e0.jpeg
---

## How To Efficiently Extract OneDrive From Windows Explorer

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

## How to Remove OneDrive Shortcut From File Explorer via the Registry Editor

 You can remove the OneDrive icon from File Explorer using a registry hack. This way, you can get rid of the icon in File Explorer without uninstalling the OneDrive client. If you would rather remove the app entirely, follow our guide on [removing OneDrive on Windows 11](https://www.makeuseof.com/windows-11-disable-remove-onedrive/) .

 Note that modifying the Windows registry involves risk. We recommend you [create a system restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed with the steps below. A restore point will help you restore your computer in case something goes wrong.

 Once done, follow these steps to remove the OneDrive shortcut from File Explorer:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open Registry Editor. Click**Yes** if prompted by**User Account Control (UAC).**
3. Next, in the Registry Editor, navigate to the following location. Copy and paste the registry path in the editor for quicker navigation:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
4. In the right pane, right-click on**System.IsPinnedToNameSpaceTree** DWORD value and select**Modify** .  
![remove onedrive icon windows 11 registry editor modify system is pinned to name space free](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-modify-system-is-pinnedtonamespace-free.jpg)
5. In the**Value data** field, type**0** and click**OK** .  
![remove onedrive icon windows 11 registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor.jpg)
6. Next, navigate to the following location in Registry Editor:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace`
7. In the left pane, right-click on**{018D5C66-4533-4307-9B53-224DE2ED1FE6}** and select**Delete** to remove the entry.  
![remove onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
8. Once done, close the Registry Editor.
9. When you open File Explorer, the OneDrive icon will not be visible anymore.

## How to Show the OneDrive Icon Again in File Explorer
![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

## Remove OneDrive Icon Without Uninstalling OneDrive

 This registry hack is a handy way to make the OneDrive icon disappear without deleting the app entirely from your PC. Alternatively, if you don’t use the service, you can completely remove OneDrive on Windows 11 or disable the service using Group Policy Editor.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>



<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-help.techidaily.com/new-how-do-i-use-adobe-premiere-to-upload-youtube-videos/"><u>[New] How Do I Use Adobe Premiere To Upload YouTube Videos?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/apps-calm-demeanor-hides-computational-challenges-for-windows-users/"><u>Apps' Calm Demeanor Hides Computational Challenges for Windows Users</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-music-from-ace-2-by-fonelab-android-recover-music/"><u>Easy steps to recover deleted music from Ace 2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-downloading-errors-in-microsoft-store/"><u>Addressing Downloading Errors in Microsoft Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/asus-zenbook-14-oled-review-pcmac-comparison/"><u>ASUS Zenbook 14 OLED Review: PC/Mac Comparison?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-the-gaming-experience-winning-strategies-for-ps1-and-windows-duckstations-guide/"><u>Elevating the Gaming Experience: Winning Strategies for PS1 and Windows - Duckstation's Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-incorrect-parameters-for-winloadlib/"><u>Dealing with Incorrect Parameters for WinLoadLib</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-ways-for-swift-epic-game-loading/"><u>Unveiling Windows Ways for Swift Epic Game Loading</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-error-code-0x80300024-on-windows-xp/"><u>Eliminating Error Code: 0X80300024 on Windows XP</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/2024-approved-maximize-your-reach-learn-how-to-make-viral-reaction-videos-with-filmora/"><u>2024 Approved Maximize Your Reach Learn How to Make Viral Reaction Videos with Filmora</u></a></li>
<li><a href="https://win11-tips.techidaily.com/break-free-from-operators-downloading-deadlock-in-windows/"><u>Break Free From Operator's Downloading Deadlock in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-inactivity-lock-timer/"><u>Adjusting Windows Inactivity Lock Timer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/desktops-uncluttered-remove-win11s-spotlight-symbol/"><u>Desktops Uncluttered: Remove Win11's Spotlight Symbol</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-keyways-to-activate-telnet-on-windows-11-pcs/"><u>3 Keyways to Activate Telnet on Windows 11 PCs</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-the-wealth-of-mr-beast/"><u>[New] The Wealth of Mr. Beast</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-virtualboxs-0x80004005-failure-on-win/"><u>Dealing with VirtualBox's 0X80004005 Failure on Win</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-action-filmmaking-camera-picks-for-newbies/"><u>[Updated] Action Filmmaking  Camera Picks for Newbies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-windows-lav-filters-usage-and-functionality/"><u>Demystifying Windows LAV Filters Usage and Functionality</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-expert-tips-for-smooth-cross-sounding-with-audacity/"><u>[Updated] Expert Tips for Smooth Cross-Sounding with Audacity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combatting-windows-steam-broadcaster-errors/"><u>Combatting Windows Steam Broadcaster Errors</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/sustainable-strategies-for-securing-over-a-million-viewers-for-2024/"><u>Sustainable Strategies for Securing Over a Million Viewers for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-best-websites-to-find-3d-gold-text-effects/"><u>2024 Approved  Best Websites to Find 3D Gold Text Effects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-file-sync-solutions-for-windows-users/"><u>Best File Sync Solutions for Windows Users</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-a-guide-asus-rog-phone-8-pro-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>In 2024, A Guide Asus ROG Phone 8 Pro Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augmenting-file-explorer-menus-with-auto-update-features/"><u>Augmenting File Explorer Menus with Auto-Update Features</u></a></li>
<li><a href="https://fix-guide.techidaily.com/in-2024-how-to-fake-snapchat-location-without-jailbreak-on-vivo-v30-lite-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fake Snapchat Location without Jailbreak On Vivo V30 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1011-volume-control-fix-guide/"><u>Windows 10/11 Volume Control Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-failures-qt-platform-support-error-at-launch/"><u>Correcting Failures: 'Qt Platform Support' Error at Launch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-xc0f1103f-issues-with-geforce-now-on-win11/"><u>Correcting Xc0f1103f Issues with GeForce Now on Win11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-gigabytes-needed-for-a-full-days-movie-watching/"><u>In 2024, Gigabytes Needed for a Full Day's Movie Watching</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-windows-11-potential-via-powertoys-install/"><u>Unleashing Windows 11 Potential via PowerToys Install</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-elevating-engagement-on-tiktok-through-hashtag-expertise/"><u>[Updated] 2024 Approved  Elevating Engagement on TikTok Through Hashtag Expertise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-w11-desktop-customization-essentials/"><u>Effortless W11 Desktop Customization Essentials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-windows-11-systray-with-scroll-lock-and-num-indicators/"><u>Amplify Windows 11 SysTray with Scroll Lock and Num Indicators</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/mac-users-guide-styling-top-tier-ootd-tiktoks-for-2024/"><u>Mac Users' Guide  Styling Top-Tier OOTD TikToks for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-process-system-isnt-responding-error-on-google-pixel-8-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Process System Isnt Responding Error on Google Pixel 8 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-history-hiccup-quick-fixes-in-3-steps/"><u>Windows History Hiccup - Quick Fixes in 3 Steps</u></a></li>
</ul></div>
