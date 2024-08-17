---
title: "Avoidance Tactics: Removing OneDrive in File Explorer Window"
date: 2024-08-16T01:59:43.176Z
updated: 2024-08-17T01:59:43.176Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Show the OneDrive Icon Again in File Explorer
![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
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
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-boosting-stability-and-speed-more-ram-for-minecraft/"><u>[New] 2024 Approved  Boosting Stability & Speed  More RAM for Minecraft</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-audiovisual-power-evaluating-mirrorless-vs-dslr-cameras/"><u>[New] Audiovisual Power  Evaluating Mirrorless vs DSLR Cameras</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-from-obscurity-to-popularity-facebooks-best-follower-growth-methods-for-2024/"><u>[New] From Obscurity to Popularity  Facebook's Best Follower Growth Methods for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-what-every-user-should-know-about-facebooks-latest-shift-for-2024/"><u>[New] What Every User Should Know About Facebook's Latest Shift for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-expert-review-best-15-cameras-in-4k-resolution-for-2024/"><u>[Updated] Expert Review  Best 15 Cameras in 4K Resolution for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-quicksilver-chords-shorts-actor-melodies/"><u>[Updated] Quicksilver Chords  Shorts' Actor Melodies</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-top-hits-on-reddit-a-compilation-of-the-best-ten/"><u>[Updated] Top Hits on Reddit - A Compilation of the Best Ten</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-is-picku-the-ultimate-answer-to-enhancing-your-android-photos/"><u>2024 Approved  Is PickU the Ultimate Answer to Enhancing Your Android Photos?</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-softening-the-end-effective-methods-for-reducing-volume-in-premiere-pro/"><u>2024 Approved  Softening the End  Effective Methods for Reducing Volume in Premiere Pro</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-ultimate-guide-for-crafting-engaging-shareable-youtube-shorts/"><u>2024 Approved  The Ultimate Guide for Crafting Engaging, Shareable YouTube Shorts</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-total-byte-requirement-for-24-hours-of-movie-viewing/"><u>2024 Approved  Total Byte Requirement for 24 Hours of Movie Viewing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-walkthrough-on-windows-11-sound-settings-navigation/"><u>A Quick Walkthrough on Windows 11 Sound Settings Navigation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-blocked-paths-in-windows-update/"><u>Clearing Up Blocked Paths in Windows Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensible-methodology-for-adding-intel-ethernet-support/"><u>Comprehensible Methodology for Adding Intel Ethernet Support</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cortana-ends-new-windows-aid-emerges/"><u>Cortana Ends, New Windows Aid Emerges</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/efficient-and-trustworthy-in-depth-analysis-of-the-audew-mini-compressor-unit/"><u>Efficient and Trustworthy: In-Depth Analysis of the Audew Mini Compressor Unit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortlessly-connect-airpods-to-windows-machines/"><u>Effortlessly Connect AirPods to Windows Machines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-data-protection-turning-on-controlled-folder-access/"><u>Ensuring Data Protection: Turning on Controlled Folder Access</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-your-z270-high-end-gaming-motherboard-with-ultimate-overclocking-features/"><u>Get Your [Z270] High-End Gaming Motherboard with Ultimate Overclocking Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gpt4all-for-pcs-local-free-chatgpt-version/"><u>GPT4All for PCs: Local, Free ChatGPT Version.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-changing-windows-11-search-icons-backwards/"><u>Guidelines for Changing Windows 11 Search Icons Backwards</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-empower-your-taskbar-with-new-features/"><u>How to Empower Your Taskbar with New Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-unreadable-source-issue-on-your-windows-pc/"><u>How to Fix ‘Unreadable Source’ Issue on Your Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-turn-your-voice-to-text-in-real-time-with-whisper-desktop/"><u>How to Turn Your Voice to Text in Real Time With Whisper Desktop</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-5-solutions-for-poco-x5-pro-unlock-without-password-by-drfone-android/"><u>In 2024, 5 Solutions For Poco X5 Pro Unlock Without Password</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-how-to-trim-video-in-windows-11-photos-easily/"><u>In 2024, How to Trim Video in Windows 11 Photos Easily</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-instagram-filter-mastery-essential-skills/"><u>In 2024, Instagram Filter Mastery - Essential Skills</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-motorola-moto-g84-5g-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>In 2024, Motorola Moto G84 5G ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-the-ultimate-ppt-recording-process-explained/"><u>In 2024, The Ultimate PPT Recording Process Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-microsofts-apppack-and-msibundle-files-to-enhance-productivity/"><u>Integrating Microsoft's Apppack and MsiBundle Files to Enhance Productivity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/investigating-windows-process-hostaggregate-use-and-security-implications/"><u>Investigating Windows' Process HostAggregate: Use & Security Implications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/latency-free-leap-essential-tips-for-clean-video-windows-streams/"><u>Latency-Free Leap: Essential Tips for Clean Video Windows Streams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-exception-handling-breaking-point-solution/"><u>Mastering Windows Exception Handling: Breaking Point Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-a-halted-warcraft-update-sequence/"><u>Navigating a Halted Warcraft Update Sequence</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-16-top-rated-free-avi-rotators-for-windows-mac-android-and-iphone-for-2024/"><u>New 16 Top-Rated Free AVI Rotators for Windows, MAC, Android, and iPhone for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/old-hardware-new-horizinas-guiding-windows-11-22h2-installation/"><u>Old Hardware, New Horizinas: Guiding Windows 11 22H2 Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-no-server-issues-fixes-and-tips-for-apex-on-windows-(156-chars/"><u>Overcoming 'No Server' Issues: Fixes and Tips for Apex on Windows (<156 Chars)</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/planning-to-use-a-pokemon-go-joystick-on-honor-x50i-drfone-by-drfone-virtual-android/"><u>Planning to Use a Pokemon Go Joystick on Honor X50i? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reset-and-reactivate-a-windows-users-guide-for-ms-store/"><u>Reset and Reactivate: A Windows User's Guide for MS Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-hidden-time-display-on-windows-bar/"><u>Setting Up Hidden Time Display on Window's Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-incorrect-windows-duo-software-setup/"><u>Steps to Rectify Incorrect Windows Duo Software Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-display-embrace-tiled-workspace/"><u>Streamline Your Display: Embrace Tiled Workspace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-internal-audio-error-in-audacity-win-11-and-11/"><u>Tackling Internal Audio Error in Audacity, Win 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-dims-handbook-for-windows-11-repair/"><u>The Complete DIMS Handbook for Windows 11 Repair</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-intricacies-of-crafting-a-virtual-experience-for-2024/"><u>The Intricacies of Crafting a Virtual Experience for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-5-tactics-reactivating-windows-defender-protection-mechanism/"><u>Top 5 Tactics: Reactivating Windows Defender Protection Mechanism</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-app-start-issue-qt-plugin-not-available/"><u>Troubleshooting App Start Issue: Qt Plugin Not Available</u></a></li>
<li><a href="https://printer-issues.techidaily.com/update-mf4770n-drivers-in-win1087-environment/"><u>Update MF4770n Drivers in Win10/8/7 Environment</u></a></li>
</ul></div>
