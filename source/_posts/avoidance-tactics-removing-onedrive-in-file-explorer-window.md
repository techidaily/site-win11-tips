---
title: "Avoidance Tactics: Removing OneDrive in File Explorer Window"
date: 2024-07-12T17:06:30.386Z
updated: 2024-07-13T17:06:30.386Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Avoidance Tactics: Removing OneDrive in File Explorer Window"
excerpt: "This Article Describes Avoidance Tactics: Removing OneDrive in File Explorer Window"
keywords: Remove Drives,Exclude OneDrive,Bypass Windows Storage,Eliminate SharePoint Folder,Disable Office Cloud Access,Hide File Explorer Extras,Opt Out of Sync Feature
thumbnail: https://thmb.techidaily.com/485fa639637af95e40bb39955015be2d5660936e6475a435b4a4c85695223b88.jpg
---

## Avoidance Tactics: Removing OneDrive in File Explorer Window

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
<li><a href="https://win11-tips.techidaily.com/restoring-unavailable-windows-updates-in-windows/"><u>Restoring Unavailable Windows Updates in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-portable-executable-an-overview/"><u>Windows' Portable Executable: An Overview</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-create-the-night-to-day-effect-videos-for-2024/"><u>Updated Create the Night-to-Day Effect Videos for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-change-xiaomi-redmi-13c-lock-screen-clock-in-seconds-by-drfone-android/"><u>How To Change Xiaomi Redmi 13C Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-windows-11s-full-potential-through-taskbar-utilization/"><u>Unleash Windows 11'S Full Potential Through Taskbar Utilization</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-the-magnificent-art-of-pokemon-go-streaming-on-samsung-galaxy-m54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, The Magnificent Art of Pokemon Go Streaming On Samsung Galaxy M54 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-strategies-to-combat-windows-1011-error-740/"><u>Swift Strategies to Combat Windows 10/11 Error 740</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-unseen-networks-a-win11-guide/"><u>Reviving Unseen Networks: A Win11 Guide</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-get-noticed-5-best-movie-intro-maker-apps-and-tools-for-2024/"><u>New Get Noticed 5 Best Movie Intro Maker Apps and Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-non-responsive-ctrl-issue-in-windows-11/"><u>Overcoming the Non-Responsive Ctrl Issue in Windows 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-21-vegas-pro-insights-an-expert-breakdown/"><u>[Updated] '21 Vegas Pro Insights – An Expert Breakdown</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-the-ultimate-alternatives-to-native-software/"><u>Win 11: The Ultimate Alternatives to Native Software</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/spotting-instagram-followers-lost-for-2024/"><u>Spotting Instagram Followers Lost for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-change-vivo-t2-5g-lock-screen-password-by-drfone-android/"><u>How To Change Vivo T2 5G Lock Screen Password?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinforced-graphics-elevating-edges-protected-mode/"><u>Reinforced Graphics: Elevating Edge's Protected Mode</u></a></li>
<li><a href="https://techidaily.com/repair-video-tool-repair-all-your-damaged-video-files-of-play-8t-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>Repair Video Tool - Repair all your damaged video files of Play 8T on Windows</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-gaming-hits-with-powerful-hashtag-strategies/"><u>In 2024, Gaming Hits with Powerful Hashtag Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-secrets-to-configuring-pc-manager/"><u>Unveiling the Secrets to Configuring PC Manager</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-a-found-iphone-13-by-drfone-ios/"><u>In 2024, How To Unlock A Found iPhone 13?</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-snapchat-on-mac-quick-setup-tips/"><u>[Updated] In 2024, Snapchat on Mac - Quick Setup Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfecting-file-formats-transforming-docx-into-plain-pdf-text-via-windows-11/"><u>Perfecting File Formats: Transforming DOCX Into Plain PDF Text via Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reimagine-your-pc-swap-out-windows-11s-essentials/"><u>Reimagine Your PC: Swap Out Windows 11'S Essentials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/retrieving-lost-actions-from-winrunhist/"><u>Retrieving Lost Actions From WinRunHist</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-upgrade-hurdle-top-7-deterrents-to-windows-11-switching/"><u>The Upgrade Hurdle: Top 7 Deterrents to Windows 11 Switching</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-your-shopping-microsoft-store-error-0x80072f30-cure/"><u>Simplify Your Shopping: Microsoft Store Error 0X80072F30 Cure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-tutorial-for-turning-on-windows-11s-quick-start/"><u>Step-by-Step Tutorial for Turning On Windows 11'S Quick Start</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-5-best-gba-emulators-for-ios-you-can-find/"><u>[Updated] In 2024, 5 Best GBA Emulators for iOS You Can Find</u></a></li>
<li><a href="https://win11-tips.techidaily.com/15-secrets-to-discovering-window-settings/"><u>15 Secrets to Discovering Window Settings</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-the-ultimate-guide-to-face-swapping-2024s-best-apps-for-mobile-devices/"><u>Updated The Ultimate Guide to Face Swapping 2024S Best Apps for Mobile Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-device-disconnect-errors-on-win-11-os/"><u>Remedying Device Disconnect Errors on Win 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taking-control-of-windows-read-only-constraints/"><u>Taking Control of Windows Read-Only Constraints</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-sid-exploration-a-comprehensible-guidebook/"><u>Windows 11 SID Exploration: A Comprehensible Guidebook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/purging-html-from-windows-11s-mail-for-improved-clarity/"><u>Purging HTML From Windows 11’S Mail for Improved Clarity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-chrome-stuck-in-w11-quick-fixes/"><u>Troubleshooting: Chrome Stuck in W11? Quick Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tricks-for-unsignatured-drivers-on-modern-windows/"><u>Tricks for Unsignatured Drivers on Modern Windows</u></a></li>
</ul></div>
