---
title: Eradicating the OneDrive Symbol From Windows 11 Filesystem
date: 2024-06-25T16:45:20.854Z
updated: 2024-06-26T16:45:20.854Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eradicating the OneDrive Symbol From Windows 11 Filesystem
excerpt: This Article Describes Eradicating the OneDrive Symbol From Windows 11 Filesystem
keywords: Removing OneDrive in Win11,Eliminate OneDrive on PC,Remove OneDrive From File System,Delete OneDrive Windows 11,Ditch OneDrive Filesystem,Exclude OneDrive FS,Eradicate Windows 11 OneDrive
thumbnail: https://thmb.techidaily.com/e66e28dff9a78d29ac6c41d0e2dd487a7c339d734ca57b3143f21e9c629c5f8e.jpg
---

## Eradicating the OneDrive Symbol From Windows 11 Filesystem

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

## How to Show the OneDrive Icon Again in File Explorer ![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)

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
<li><a href="https://win11-tips.techidaily.com/quick-languages-change-navigating-hotkeys-in-windows-11-and-11-pro/"><u>Quick Languages Change: Navigating Hotkeys in Windows 11 & 11 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-the-wild-high-on-your-windows-desktop/"><u>Taming the Wild High on Your Windows Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convenient-ways-downloading-setting-up-and-running-msix-extensions-on-windows/"><u>Convenient Ways: Downloading, Setting Up & Running MSIX Extensions on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-windows-camera-recording-retention/"><u>Expert Tips for Windows Camera Recording Retention</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-zoom-crash-code-1132-on-windows-devices/"><u>Eliminating Zoom Crash Code 1132 on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stealth-mode-for-windows-11-apps/"><u>Stealth Mode for Windows 11 Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-greyed-out-waste-bin-icon-in-win11/"><u>Restoring Greyed Out Waste Bin Icon in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-automatic-restarts-on-windows-11-devices/"><u>Conquering Automatic Restarts on WIndows 11 Devices</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-mastering-the-art-of-creating-an-original-tiktok-hashtag/"><u>In 2024, Mastering the Art of Creating an Original TikTok Hashtag</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/top-rated-digital-audio-level-equalizer-for-2024/"><u>Top-Rated Digital Audio Level Equalizer for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/2024-approved-winning-strategies-for-youtube-seo-titles-and-descriptions/"><u>2024 Approved  Winning Strategies for YouTube SEO  Titles & Descriptions</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-hottest-twitters-the-viral-video-countdown/"><u>2024 Approved  Hottest Twitters  The Viral Video Countdown</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-instagram-stories-unseen-aspects-revealed/"><u>[Updated] Instagram Stories  Unseen Aspects Revealed</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unveiling-the-complete-image-enhancement-capabilities-with-polarr/"><u>In 2024, Unveiling the Complete Image Enhancement Capabilities with Polarr</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-profitability-in-production-starting-a-successful-vlog/"><u>2024 Approved  Profitability in Production  Starting a Successful Vlog</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-securing-your-shots-top-15-mounting-options-for-gopro/"><u>[New] Securing Your Shots  Top 15 Mounting Options for GoPro</u></a></li>
<li><a href="https://extra-resources.techidaily.com/exclusive-insight-into-selecting-the-top-5-digital-title-makers/"><u>Exclusive Insight Into Selecting the Top 5 Digital Title Makers</u></a></li>
</ul></div>
