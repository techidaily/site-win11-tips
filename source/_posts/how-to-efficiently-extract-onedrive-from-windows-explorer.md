---
title: How To Efficiently Extract OneDrive From Windows Explorer
date: 2024-06-25T16:43:42.616Z
updated: 2024-06-26T16:43:42.616Z
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
<li><a href="https://win11-tips.techidaily.com/windows-audio-device-isolation-explained/"><u>Windows Audio Device Isolation Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-spot-and-dismantle-unused-windows-folders-easily/"><u>How to Spot & Dismantle Unused Windows Folders Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-vocal-expressions-to-written-words-with-windows-whisper/"><u>From Vocal Expressions to Written Words with Windows Whisper</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-navigation-tips-on-using-narrator-commands/"><u>Streamlining Windows Navigation: Tips on Using Narrator Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-grades-with-these-top-8-windows-study-hacks/"><u>Skyrocket Grades with These Top 8 Windows Study Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-window-management-active-periods-not-permanent-disruptions/"><u>Efficient Window Management: Active Periods, Not Permanent Disruptions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-fixing-unexpected-system-call-failures-on-win1011/"><u>Guide: Fixing Unexpected System Call Failures on Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-new-waves-in-windows-unlocking-vivetools-secrets/"><u>Navigating New Waves in Windows: Unlocking ViVeTool's Secrets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/propel-windows-app-speed-revitalize-their-web-connection/"><u>Propel Window's App Speed: Revitalize Their Web Connection</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-the-easy-guide-to-youtube-to-avi-conversion-technology/"><u>[Updated] The Easy Guide to YouTube-to-AVI Conversion Technology</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/instagram-pro-tip-speedy-like-video-strategies-for-2024/"><u>Instagram Pro Tip  Speedy Like-Video Strategies for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-picture-perfect-instagram-carousel/"><u>[New] In 2024, Picture-Perfect Instagram Carousel</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-how-to-install-videoleap-video-editor-on-your-macbook/"><u>Updated How to Install Videoleap Video Editor on Your MacBook</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-boosting-obs-streams-direct-to-facebook-feed/"><u>[Updated] In 2024, Boosting OBS Streams Direct to Facebook Feed</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-social-media-roadmap-for-business-growth-for-2024/"><u>The Social Media Roadmap for Business Growth for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-crafting-seamless-visuals-with-instagrams-chroma-key/"><u>[Updated] Crafting Seamless Visuals with Instagram's Chroma Key</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-initiating-live-channels-your-comprehensive-guide/"><u>[Updated] 2024 Approved  Initiating Live Channels  Your Comprehensive Guide</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-android-and-iphone-select-top-tier-mobile-multimedia-tools/"><u>[New] Android & iPhone  Select Top-Tier Mobile Multimedia Tools</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-timeless-tones-a-compendium-of-quality-sound-sites/"><u>In 2024, Timeless Tones  A Compendium of Quality Sound Sites</u></a></li>
</ul></div>
