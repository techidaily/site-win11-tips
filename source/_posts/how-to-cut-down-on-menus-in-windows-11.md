---
title: How to Cut Down on Menus in Windows 11
date: 2024-07-12T16:31:32.858Z
updated: 2024-07-13T16:31:32.858Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Cut Down on Menus in Windows 11
excerpt: This Article Describes How to Cut Down on Menus in Windows 11
keywords: Menu Reduction Tips,Save Space Windows 11,Menu Size Control W11,Minimize Menus Win11,Cut Down W11 Interface,Reduce Window Menus,Windows 11 Menu Optimization
thumbnail: https://thmb.techidaily.com/e35da50e74d4ad42a2d4ca6cbb01ed721572402298c4b208ceac1efbbaaf58d4.png
---

## How to Cut Down on Menus in Windows 11

 Windows 11 comes with a fresh new look and has mainly got a positive response for its new interface. However, there are a couple of features that are not being welcomed by the users. For instance, the addition of the "show more options" entry to the right-click context menu.

 Although it was introduced to simplify things, many users still prefer the old context menu from Windows 10\. Fortunately, you can remove Show more options from the context menu on Windows 11 by following the below methods.

## 1\. How to Remove "Show More Options" From the Context Menu With Folder Options

 The [Windows Folder Options](https://www.makeuseof.com/windows-folder-options-guide/) in File Explorer is the go-to place to view and manage File Explorer settings. You can use it to [enable compact view in File Explorer on Windows 11](https://www.makeuseof.com/how-to-enable-compact-view-windows-11-file-explorer/) , manage file thumbnails, remove the "show more options" entry, and much more.

 Here's how to use the folder option to remove the "show more options" entry from the context menu:

1. Press the**Win + E** hotkey to open the**File Explorer.**
2. Click the three horizontal dots at the top bar and choose**Options.**
3. In the**Folder Options,** switch to the**View** tab.
4. Check the**Launch folder** **windows in a separate process** box.  
![Launch folder windows in a separate process box in the Folder option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/launch-folder-windows-in-a-separate-process-box.jpg)
5. Click**Apply** \>**OK** to save the changes.

Next, restart your computer for the changes to take effect.

## 2\. Remove Show More Options From the Context Menu Using the Command Prompt

 If you're a power user, you can use Command Prompt to remove the "show more options" entry from the context menu. Here's how:

1. Open the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Command Prompt** and choose**Run as administrator** from the right pane.
3. Click**Yes** to the UAC that crops up.
4. In the elevated Command Prompt window, type the following command and press**Enter** :  
`reg add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve`

![Command to Remove Context menu in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/command-to-remove-context-menu.jpg)

 After executing the command, you'll see the "The operation completed successfully" message to confirm that it went through.

 Now, you will have to restart Windows Explorer to see the changes. To do that, open the**Task Manager** (see how to [launch the Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) ), right-click on**Windows Explorer,** and choose**Restart.**

 Check if you can see the changes. If not, then you will have to restart your computer for the changes to take effect.

 In the future, if you want to add the "show more options" entry to the context menu, then open Command Prompt with admin rights and run the following command:

`reg delete "HKEY_CURRENT_USER\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}" /f​`

## 3\. Remove Show More Options From the Context Menu Using the Registry Editor

 Another quick way to remove the "show more options" entry is through the Registry Editor. Here's what you need to do:

 Before making any changes to the registry, ensure you've [created a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) or [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . This will ensure your system settings and files are secure, and you can quickly access them if something goes wrong.

1. Open the Start Menu, type**Registry Editor** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID`
3. Right-click on the empty space on the right pane, click**New,** and then select**DWORD** **(32-bit) Value** from the context menu.
4. Name the value as**"UndockingDisabled"** and press**Enter** .  
![UndockingDisabled entry in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/undockingdisabled-entry.jpg)
5. Double-click on the UndockingDisabled key, type**1** in the**Value data,** and click**OK** to save the changes.  
![Editing UndockingDisabled in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/editing-undockingdisabled.jpg)

## 4\. Remove the "Show More Options" Entry From the Context Menu Using Winaero Tweaker

 There are plenty of third-party tools using which you can customize the look of your Windows 11 computer. For this guide, we will use Winaero Tweaker.

 Here's how to download Winaero Tweaker and use it to remove the "show more options" entry from the context menu:

1. Download the [Winaero Tweaker zip file](https://winaero.com/downloads/winaerotweaker.zip) on your computer.
2. Unzip the file, open the executable, and then follow the on-screen instructions to install it on your computer.
3. Launch Winaero Tweaker and choose the**Classic Full Context Menus** option from the left sidebar.  
![Classic Full Context Menus option of Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/classic-full-context-menus-option.jpg)
4. Check the**Enable classic full context menus** box.  
![Enable classic full context menus option in Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-classic-full-context-menus.jpg)
5. Click the**Restart Explorer** button that appears.

## Enjoy an Old School Context Menu on Windows 11

 The desktop context menu lets you quickly access areas like the personalization menu, display settings, and much more. In Windows 11, you get the new "Show more options" entry in the context menu. But if you prefer the old design, you can quickly disable the "Show more options" entry from the context using either of the above methods.


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
<li><a href="https://win11-tips.techidaily.com/troubleshoot-missing-5ghz-network-on-windows-11-top-7-solutions/"><u>Troubleshoot Missing 5GHz Network on Windows 11: Top 7 Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-deals-bf-black-friday-612-win10-for-life/"><u>Best Deals: BF Black Friday - $6.12 Win10 for Life</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-spotlight-strategies-for-solo-talent-vs-tiktok-titans/"><u>[Updated] Spotlight Strategies for Solo Talent Vs. TikTok Titans</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-variability-in-windows-protocols-for-cloud-and-local-reinstallation/"><u>Understanding Variability in Windows Protocols for Cloud and Local Reinstallation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-get-the-most-out-of-the-windows-11-start-menu/"><u>7 Ways to Get the Most Out of the Windows 11 Start Menu</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/honor-x9a-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>Honor X9a ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713963965076-updated-kdenlive-is-a-free-open-source-video-editing-software-application-kdenlive-is-a-powerful-video-editor-that-can-be-used-to-create-professional-qualit/"><u>Updated Kdenlive Is a Free, Open-Source Video Editing Software Application. Kdenlive Is a Powerful Video Editor that Can Be Used to Create Professional-Quality Videos for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-analytics-unlocked-your-step-by-step-youtube-guide/"><u>[New] In 2024, Analytics Unlocked  Your Step-by-Step YouTube Guide</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-music-from-honor-x8b-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Music from Honor X8b to iPod | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-role-of-windows-11-in-software-installation-harmony/"><u>The Role of Windows 11 in Software Installation Harmony</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-pinnacle-clarity-to-your-w11-desktop-wallpaper/"><u>Bringing Pinnacle Clarity to Your W11 Desktop Wallpaper</u></a></li>
<li><a href="https://win11-tips.techidaily.com/browsing-lightly-identifying-minimal-resource-using-software-across-windowsmacoschromeos/"><u>Browsing Lightly: Identifying Minimal Resource-Using Software Across Windows/macOS/ChromeOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/chrome-opening-woes-resolved-fast-fixed-for-windows-11-users/"><u>Chrome Opening Woes Resolved: Fast Fixed for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-folder-customization-adding-movecopy-context-functionality/"><u>Windows 11 Folder Customization - Adding Move/Copy Context Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-your-windows-11-integrating-cutting-edge-run-commands/"><u>Upgrade Your Windows 11: Integrating Cutting-Edge Run Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-frozen-opera-downloads-in-windows-sphere/"><u>Unlock Frozen Opera Downloads in Windows Sphere</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-the-def5-barrier-tips-for-win11s-onedrive-errors/"><u>Breaking Down the DEF5 Barrier: Tips for Win11's OneDrive Errors</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-the-art-of-condensation-editing-youtube-video-durations/"><u>[New] The Art of Condensation  Editing YouTube Video Durations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-high-definition-adventures-winning-with-windows-and-scummvm/"><u>The Ultimate Guide to High Definition Adventures: Winning with Windows & ScummVM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-windows-workspaces-into-a-unified-digital-ecosystem-via-aoemi/"><u>Transforming Windows Workspaces Into a Unified Digital Ecosystem via AOEMi</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-unlock-4k-video-editing-without-breaking-the-bank-free-options-for-2024/"><u>Updated Unlock 4K Video Editing without Breaking the Bank Free Options for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-best-video-editing-software-for-adding-music-and-soundtracks/"><u>2024 Approved Best Video Editing Software for Adding Music and Soundtracks</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/the-next-generation-of-mac-video-capture-software-not-bandicam/"><u>The Next Generation of Mac Video Capture Software (Not Bandicam)</u></a></li>
<li><a href="https://location-fake.techidaily.com/6-ways-to-change-spotify-location-on-your-apple-iphone-15-drfone-by-drfone-virtual-ios/"><u>6 Ways to Change Spotify Location On Your Apple iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-virtual-adrenaline-rushes-top-10-without-gta/"><u>In 2024, Virtual Adrenaline Rushes - Top 10 Without GTA</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-the-ultimate-filmora-coupon-code-resource-7-ways-to-save/"><u>Updated The Ultimate Filmora Coupon Code Resource 7 Ways to Save</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-from-widescreen-to-vertical-the-essential-guide-to-resizing-social-media-videos/"><u>Updated In 2024, From Widescreen to Vertical The Essential Guide to Resizing Social Media Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-task-scheduler-guide-to-efficient-batch-processing/"><u>The Task Scheduler Guide to Efficient Batch Processing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transition-to-new-life-for-your-outdated-computer/"><u>Transition to New Life for Your Outdated Computer</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-3-effective-methods-to-fake-gps-location-on-android-for-your-tecno-spark-10-pro-drfone-by-drfone-virtual/"><u>In 2024, 3 Effective Methods to Fake GPS location on Android For your Tecno Spark 10 Pro | Dr.fone</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/top-ranked-sources-for-embedding-text-visual-effects/"><u>Top Ranked Sources for Embedding Text Visual Effects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-path-to-reinstating-default-windows-backups/"><u>The Path to Reinstating Default Windows Backups</u></a></li>
<li><a href="https://youtube-help.techidaily.com/how-to-optimize-your-channels-with-youtubes-featured-spotlight-for-2024/"><u>How to Optimize Your Channels with YouTube’s Featured Spotlight for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-best-free-voice-changer-for-valorant-you-should-have-a-try/"><u>In 2024, Best Free Voice Changer for Valorant You Should Have a Try</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-device-synergy-samsung-dex-for-galaxy-users/"><u>Streamlining Device Synergy: Samsung DeX for Galaxy Users</u></a></li>
<li><a href="https://some-techniques.techidaily.com/ideal-steadicams-for-uav-aerial-cinematography-for-2024/"><u>Ideal Steadicams for UAV Aerial Cinematography for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-alter-desktop-icons-separation-in-win-oss/"><u>Title: Alter Desktop Icons' Separation in WIN OSs</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-building-a-robust-360-video-broadcast-framework-for-fb/"><u>[New] Building a Robust 360 Video Broadcast Framework for FB</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trouble-locating-astra-pilot-help-for-windows-11-pcs/"><u>Trouble Locating Astra Pilot? Help For Windows 11 PCs</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-capturing-your-laptop-simple-lenovo-steps/"><u>[Updated] Capturing Your Laptop  Simple Lenovo Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/your-ultimate-toolkit-to-counteract-bsod-on-win10/"><u>Your Ultimate Toolkit to Counteract BSOD on Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailored-tools-focused-uninstall-strategies-for-windows-1011/"><u>Tailored Tools: Focused Uninstall Strategies for Windows 10/11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/connecting-consciously-with-content-craftsmen-of-your-realm-for-2024/"><u>Connecting Consciously with Content Craftsmen of Your Realm for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-future-windows-laptops-top-picks/"><u>The Ultimate Guide to Future Windows Laptops: Top Picks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-the-power-extracting-device-ids-in-windows/"><u>Unleashing the Power: Extracting Device IDs in Windows</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-xiaomi-redmi-k70-drfone-by-drfone-android/"><u>How To Use Allshare Cast To Turn On Screen Mirroring On Xiaomi Redmi K70 | Dr.fone</u></a></li>
</ul></div>
