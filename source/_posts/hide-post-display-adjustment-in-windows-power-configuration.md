---
title: Hide Post-Display Adjustment in Windows Power Configuration
date: 2024-07-12T17:27:36.402Z
updated: 2024-07-13T17:27:36.402Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Hide Post-Display Adjustment in Windows Power Configuration
excerpt: This Article Describes Hide Post-Display Adjustment in Windows Power Configuration
keywords: Windows Power Save,Hide Display Ads,Power Config Tweaks,Adjust Windows Settings,Power Management Tips,Reduce Screen Ads,Optimize PC Performance
thumbnail: https://thmb.techidaily.com/a88de5655376206e2ee17661cb9dd03b46b68bf81e7fb9a2b0bcd4cf8d7ba0d8.jpg
---

## Hide Post-Display Adjustment in Windows Power Configuration

 There are times when you need to step away from your PC, and if you’re gone long enough, the screen will automatically dim. Windows does this to preserve your battery, and you can adjust when your display should darken in the Power Options menu by editing the **Dim display after** option.

 If for some reason you can’t see the **Dim display after** option in the Power Options menu, or it’s there and you want to remove it, you can use PowerShell or the Registry Editor to show or hide it. Here’s how.

## How to Show or Hide the “Dim Display After” Option Using PowerShell

 First, launch Windows PowerShell. There are many [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/), but the easiest method is to press **Win + S** to open Windows Search. Then, enter **powershell** in the search box and click on **Windows PowerShell** when it appears in the search results.

![windows powershell in the windows search results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/windows-powershell-search.jpg)

 In PowerShell, enter the following command to show the **Dim Display after** option in the Power Options menu:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee -ATTRIB_HIDE

 To hide it, enter the following command:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee +ATTRIB_HIDE

 After entering the command you want, hit the **Enter** key on your keyboard for PowerShell to execute it. Afterward, the **Dim display after** option should appear or disappear accordingly in the Power Options menu.

## How to Show or Hide the “Dim display after” Option Using the Registry Editor

 Considering how vital the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is for the smooth operation of Windows, you might want to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you edit it. Afterward, open the Registry Editor by pressing **Win + R**, typing **regedit** in the text box, and clicking **OK**.

![regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/regedit.jpg)

 Click **Yes** to bypass the UAC prompt.

 In the address bar of the Registry Editor, copy and paste the following text into it:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\7516b95f-f776-4464-8c53-06167f40cc99\17aaa29b-8b43-4b94-aafe-35f64daaf1ee

 On the right panel, double-click the **Attributes** entry to open it up for editing.

![the attributes entry in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-dim-display-after-attributes-entry.jpg)

 Then, in the **Value data** text box, enter **1** to hide **Dim display after** in the Power Options menu or **2** to show it.

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

 Now you can open the Power Options menu (see [how to open the power options on Windows 10](https://www.makeuseof.com/windows-10-open-power-options/)) and check under **Display** to see if the **Dim display after** option is there or not.

## Controlling the “Dim Display After” Option in the Power Options Menu

 Now that you know how to show or hide **Dim display after**, you know what to do when you can’t find it in the Power Options menu or need to remove it. We recommend keeping it hidden and then bringing it up whenever you need it. This will make sure that no one messes with this important display setting when you’ve set it up perfectly.

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
<li><a href="https://win11-tips.techidaily.com/1719377868664-is-prtscr-a-gateway-to-windows-11s-snipping-tool-no/"><u>Is PrtScr a Gateway to Windows 11'S Snipping Tool? No!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-power-management-hiding-dim-display/"><u>Accessing Power Management: Hiding 'Dim Display'</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-oppo-reno-8t-5g-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Oppo Reno 8T 5G Bricked Devices | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-to-new-windows-pin/"><u>A Step-by-Step Approach to New Windows PIN</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719292218138-quicker-downloads-for-battlenet-games-win-pcs-now/"><u>Quicker Downloads for Battle.net Games, Win PCs Now!</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-best-recorders-for-lecture-recording/"><u>[Updated] 2024 Approved  Best Recorders for Lecture Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-one-way-outlook-issue-in-secure-environments/"><u>Addressing the One-Way Outlook Issue in Secure Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-portaudio-fault-in-audacity-windows-11-os/"><u>Addressing PortAudio Fault in Audacity, Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719363317332-troubleshoot-non-functional-shift-in-windows/"><u>Troubleshoot Non-Functional Shift in Windows.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-global-scripts-windows-font-acquisition-guide/"><u>Accessing Global Scripts: Windows Font Acquisition Guide</u></a></li>
<li><a href="https://fix-guide.techidaily.com/lenovo-thinkphone-stuck-on-screen-finding-solutions-for-stuck-on-boot-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Lenovo ThinkPhone Stuck on Screen – Finding Solutions For Stuck on Boot | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activation-essentials-making-most-of-win11s-widget-bar/"><u>Activation Essentials: Making Most of Win11's Widget Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-things-you-should-avoid-doing-on-windows-11/"><u>8 Things You Should Avoid Doing on Windows 11</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-a-comprehensive-look-at-editing-and-uploading-virtual-reality-videos-to-youtube/"><u>[Updated] A Comprehensive Look at Editing and Uploading Virtual Reality Videos to YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-android-powered-webcams-in-windows-11-environments/"><u>A Guide to Android-Powered Webcams in Windows 11 Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-permanently-disable-microsoft-defender-in-windows-11/"><u>5 Ways to Permanently Disable Microsoft Defender in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-clickable-items-in-the-latest-os-update/"><u>Addressing Non-Clickable Items in the Latest OS Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activate-quick-fix-support-windows-11-procedure/"><u>Activate Quick Fix Support: Windows 11 Procedure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-your-way-through-windows-with-mouseclicklock-techniques/"><u>Ace Your Way Through Windows with MouseClickLock Techniques</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-elevate-presentations-10-must-have-slide-show-designs-at-no-cost/"><u>2024 Approved  Elevate Presentations  10 Must-Have Slide Show Designs at No Cost</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-in-use-files-errors-in-windows-152-chars/"><u>Addressing 'In-Use' Files Errors in Windows (152 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-onedrive-errors-in-windows-1011-system/"><u>Addressing OneDrive Errors in Windows 10/11 System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-routes-to-reviving-the-elusive-windows-terminal/"><u>5 Routes to Reviving the Elusive Windows Terminal</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-exploring-instagrams-hidden-gems-accessing-no-cost-filters/"><u>[Updated] Exploring Instagram's Hidden Gems  Accessing No-Cost Filters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-improve-your-gaming-experience-on-a-windows-11-pc/"><u>7 Ways to Improve Your Gaming Experience on a Windows 11 PC</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-streamlining-communication-utilizing-masks-and-filters/"><u>[New] In 2024, Streamlining Communication  Utilizing Masks and Filters</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-efficiency-boost-discover-the-top-5-youtube-shorteners/"><u>[New] In 2024, Efficiency Boost  Discover the Top 5 YouTube Shorteners</u></a></li>
<li><a href="https://extra-resources.techidaily.com/clearsnap-guide-how-to-exclude-distracting-picture-borders/"><u>ClearSnap Guide  How to Exclude Distracting Picture Borders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-file-browsing-activate-filters-with-checkbox-on-win11/"><u>Accelerate File Browsing: Activate Filters with Checkbox on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/access-anywhere-unveiling-gaming-data-in-windows/"><u>Access Anywhere: Unveiling Gaming Data in Windows</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-enhancing-your-game-time-with-youtube-live-broadcasts/"><u>[Updated] 2024 Approved  Enhancing Your Game Time with YouTube Live Broadcasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719348868755-is-your-pc-compatible-with-windows-11-see-here/"><u>Is Your PC Compatible with Windows 11? See Here</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-avoiding-the-samsung-gear-360-hurdle-top-camera-alternatives-of-2023/"><u>[New] Avoiding the Samsung Gear 360 Hurdle - Top Camera Alternatives of 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719382715644-unlock-potential-of-windows-without-using-the-compatibility-tool/"><u>Unlock Potential of Windows without Using the Compatibility Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719294305886-ignite-performance-gains-in-winoutlook-today/"><u>Ignite Performance Gains in WinOutlook, Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-and-resolving-msvcr110dll-lack/"><u>Addressing and Resolving MSVCR110.dll Lack</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-essential-steps-to-clear-overflowing-c-drive-data/"><u>3 Essential Steps to Clear Overflowing C: Drive Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-ways-to-fix-there-are-no-startup-items-to-display-in-the-task-manager-error-on-windows/"><u>8 Ways to Fix There Are No Startup Items to Display in the Task Manager Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-ways-to-fix-the-no-servers-found-error-in-apex-legends-for-windows/"><u>9 Ways to Fix the No Servers Found Error in Apex Legends for Windows</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-from-kitchen-to-feeds-the-10-hottest-tiktok-treats/"><u>2024 Approved  From Kitchen to Feeds  The 10 Hottest TikTok Treats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-breakdown-of-mouse-customization-features-on-win11/"><u>A Complete Breakdown of Mouse Customization Features on Win11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-discover-the-future-of-screens-with-camstudios-2023-review/"><u>[Updated] In 2024, Discover the Future of Screens with CamStudio's 2023 Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/access-denied-reconnecting-to-windows-shared-items/"><u>Access Denied: Reconnecting to Windows Shared Items</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-free-animated-logo-makers-top-picks-and-expert-design-tips/"><u>2024 Approved Free Animated Logo Makers Top Picks and Expert Design Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719314760975-home-run-your-gptclone-on-windows-free-and-easy-with-gpt4all/"><u>Home-Run Your GPTClone on Windows – Free & Easy with GPT4All</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-fix-the-windows-update-error-0x800f080a/"><u>6 Ways to Fix the Windows Update Error 0X800f080a</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-functional-utorrent-installers-on-pc-with-os-x/"><u>Addressing Non-Functional uTorrent Installers on PC with OS X</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-dont-get-lost-in-conversion-mp3-to-mp4-best-practices/"><u>New Dont Get Lost in Conversion MP3 to MP4 Best Practices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-access-the-startup-folder-in-windows/"><u>5 Ways to Access the Startup Folder in Windows</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-endgame-permanently-blocking-access-to-youtube-shorts/"><u>2024 Approved  The Endgame  Permanently Blocking Access to YouTube Shorts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-customizing-terminal-color-schemes/"><u>A Guide to Customizing Terminal Color Schemes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-compreenasolutiontowindowss-lsass-problem-step-by-step-guide/"><u>A CompreenasolutiontoWindows's Lsass Problem: Step by Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-windows-11s-archiving-feature/"><u>Activating Windows 11'S Archiving Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719359918304-error-handling-strategies/"><u>Error Handling Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719338441167-navigating-through-the-hurdles-winplusprint-mishaps-in-windows/"><u>Navigating Through the Hurdles: Win+Print Mishaps in Windows.</u></a></li>
</ul></div>
