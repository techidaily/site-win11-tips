---
title: Adjusting Windows 11 Taskbar Scaling
date: 2024-07-12T18:04:21.742Z
updated: 2024-07-13T18:04:21.742Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Windows 11 Taskbar Scaling
excerpt: This Article Describes Adjusting Windows 11 Taskbar Scaling
keywords: Win11TaskbarScale,Windows11BarResize,TaskbarWidthControl,TaskbarScalingWin,WindowBarAdjustment,BarSizeChangeWin,ScalingTaskbarWindows
thumbnail: https://thmb.techidaily.com/6152b7c969d91f2eaae0be3b9bf8b8ec86f6a4683a1dd9c2aefb366c737706ad.jpg
---

## Adjusting Windows 11 Taskbar Scaling

 Ever looked at the Windows 11 Taskbar and thought it looks too small for your liking? Or maybe you feel it could be a little smaller? If that’s the case, you can change its size to suit your needs by making it bigger or smaller.

 Unlike Windows 10, you can’t just unlock the Taskbar and adjust its size freely in Windows 11\. While Microsoft has removed this way of going about it in Windows 11, there is a workaround that you can use, although it’s not as elegant.

## How Do I Make the Windows 11 Taskbar Bigger or Smaller?

 The only way to change the size of the Taskbar is to use the Registry Editor. However, we advise caution when dealing with the Windows Registry because if something goes wrong, you might experience performance issues on your Windows 11 PC. If you’re unfamiliar with it, we recommend reading our guides on [what the Windows Registry is](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) and [how to not mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/) .

 Once you’re all caught up or are already familiar with the Windows Registry, and you know what you’re doing, you can make the Taskbar bigger or smaller. To do that:

1. Start by pressing**Win + R** to open Windows Run.
2. Type**regedit** in the text box and hit the**Enter** key.
3. Then, click**Yes** on the UAC prompt to launch the Registry Editor.
4. Copy and paste the below text in the address bar of the Registry Editor and hit the**Enter** key:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. In the**Advanced** key, look for a value called**TaskbarSi** . If it’s not there, right-click**Advanced** , select**New > DWORD (32-bit) Value** , and name that value**TaskbarSi.**  
![creating a new dword in the advanced key in the Registry Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/new-dword-advanced-regedit.jpg)
6. Double-click**TaskbarSi** to edit it, and then enter**2** in the**Value data** text box and click**OK** to make the Taskbar bigger.  
![changing the taskbarsi value to 2 in the Registry Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/taskbarsi-value-2.jpg)

 Once you restart your computer, you will see the result: an enlarged Taskbar.

![an enlarged Taskbar on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-enlarged-taskbar.jpg)

 To make the Taskbar smaller, enter**0** in the**Value data** text box, click**OK** , and then restart your computer. You will then see that the Taskbar has shrunk.

![a smaller taskbar in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-small-taskbar.jpg)

 If you decide to go back to the Taskbar’s default size, you can easily set**Value data** to**1** or simply delete the**TaskbarSi** value.

## Adjust the Taskbar’s Size to Suit Your Needs on Windows 11

 Even though you can’t make the Taskbar bigger or smaller on Windows 11 as easily as you can on Windows 10, a little know-how can help. And as long as you followed the instructions mentioned above correctly, you shouldn’t worry about messing up the Windows Registry. However, we still recommend that you use this method only if you know what you’re doing.


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
<li><a href="https://win11-tips.techidaily.com/boost-operations-efficient-data-alignment-in-win11/"><u>Boost Operations: Efficient Data Alignment in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blackview-space-for-storage-sluggishness-sets-in/"><u>Blackview: Space for Storage, Sluggishness Sets In</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-taskbar-size-step-by-step-guide/"><u>Altering Taskbar Size: Step-by-Step Guide</u></a></li>
<li><a href="https://change-location.techidaily.com/pokemon-go-no-gps-signal-heres-every-possible-solution-on-xiaomi-redmi-note-12-5g-drfone-by-drfone-virtual-android/"><u>Pokemon Go No GPS Signal? Heres Every Possible Solution On Xiaomi Redmi Note 12 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-efficiency-activating-search-bar-on-windows-11-tm/"><u>Boost Your Efficiency: Activating Search Bar on Windows 11 TM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-typing-copy-pasting-expertise/"><u>Boost Your Typing, Copy-Pasting Expertise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-alternatives-to-windows-snipping-tool-for-swift-image-grabs/"><u>Best Alternatives to Windows Snipping Tool for Swift Image Grabs</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-tecno-spark-10-4g-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset Tecno Spark 10 4G | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-breaking-news-afbs-secret-to-trending-content/"><u>2024 Approved  Breaking News  AFB's Secret to Trending Content</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/how-to-set-up-and-use-xbox-screen-recording-tools-for-2024/"><u>How to Set Up and Use Xbox Screen Recording Tools for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-gaming-harmonies-archive-legal-free-to-access/"><u>[Updated] Gaming Harmonies Archive  Legal, Free to Access</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-silent-soundscape-revolution-a-deep-dive-into-eliminating-sound-interference-with-the-right-tools-online-and-offline-for-2024/"><u>New Silent Soundscape Revolution A Deep Dive Into Eliminating Sound Interference with the Right Tools (Online & Offline) for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-turbo-speed-photo-browser-for-windows-10/"><u>2024 Approved  Turbo Speed Photo Browser for Windows 10</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-infallible-steps-to-tiktok-bio-link-integration-without-error/"><u>2024 Approved  Infallible Steps to TikTok Bio-Link Integration Without Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginner-friendly-guide-setting-up-the-jdk-on-windows-11/"><u>Beginner-Friendly Guide: Setting Up the JDK on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-user-frustrations-in-windows-11-transition/"><u>Analyzing User Frustrations in Windows 11 Transition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-the-deadly-js-error-in-discord-a-quick-guide-for-win-11-users/"><u>Banish the Deadly JS Error in Discord: A Quick Guide for Win 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplifying-windows-protection-integrating-additional-firewall-settings-into-context-menu/"><u>Amplifying Windows Protection: Integrating Additional Firewall Settings Into Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-nvidia-writes-of-error-3-in-win1011/"><u>Avoiding NVIDIA' Writes of Error 3 in Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-windows-apps-with-efficient-internet-fixes/"><u>Boost Your Windows Apps with Efficient Internet Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/aid-in-correcting-windows-media-tool-issue-x8007043c/"><u>Aid in Correcting Windows' Media Tool Issue X.8007043C</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-pc-speed-with-win11-startup-tweaks/"><u>Boosting PC Speed with Win11 Startup Tweaks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-android-studio-speed-on-windows-pcs/"><u>Boosting Android Studio Speed on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-integration-in-windows-11-for-effective-multitasking/"><u>Android Integration in Windows 11 for Effective Multitasking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augment-win11-notepad-with-genius-mentor/"><u>Augment Win11 Notepad with Genius Mentor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-the-trouble-fixing-corrupted-recycle-bin-on-win1011/"><u>Avoid the Trouble: Fixing Corrupted Recycle Bin on Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/behind-closed-curtains-of-windows-how-to-open-hidden-self-assessment-tool/"><u>Behind Closed Curtains of Windows: How to Open Hidden Self-Assessment Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-your-windows-dynamic-background-anytime/"><u>Adjusting Your Windows Dynamic Background Anytime</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-not-recognized-issues-in-windows-with-these-fixes/"><u>Banish 'Not Recognized' Issues in Windows with These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-tips-for-managing-users-via-command-prompt/"><u>Advanced Tips for Managing Users via Command Prompt</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-efficient-lecture-capture-with-macos/"><u>[Updated] 2024 Approved  Efficient Lecture Capture with MacOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-user-interface-customization-for-win-11/"><u>Advanced User Interface Customization for Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-pc-display-orientation-via-windows/"><u>Adjust PC Display Orientation via Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-organization-in-windows-discover-5-key-folder-insights/"><u>Boost Organization in Windows - Discover 5 Key Folder Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-integration-microsofts-new-taskbar-helper-in-windows-11-streamlines-tasks/"><u>AI Integration: Microsoft's New Taskbar Helper in Windows 11 Streamlines Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-development-with-these-wsl-2-secrets/"><u>Boost Your Development with These WSL 2 Secrets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-to-windows-webcam-conversion-guide-for-windows-11-users/"><u>Android to Windows Webcam Conversion Guide for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-windows-11s-autosaverestore-techniques-and-options/"><u>Analyzing Windows 11'S AutoSave/Restore Techniques and Options</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-ultimate-guide-to-zero-cost-remote-desktop-software/"><u>[New] 2024 Approved  Ultimate Guide to Zero-Cost Remote Desktop Software</u></a></li>
<li><a href="https://audio-editing.techidaily.com/hush-hours-in-editing-step-by-step-noise-suppression-methods-with-premiere-pro/"><u>Hush Hours in Editing Step-by-Step Noise Suppression Methods with Premiere Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-terminal-backdrop/"><u>Adjusting Windows Terminal Backdrop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/arrow-anomalies-unveiled-and-resolved-for-windows-users/"><u>Arrow Anomalies Unveiled and Resolved for Windows Users</u></a></li>
<li><a href="https://extra-tips.techidaily.com/5-must-try-websites-for-cost-free-effects-for-2024/"><u>5 Must-Try Websites for Cost-Free Effects for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-system-performance-by-enabling-automatic-file-deletion-in-winos/"><u>Boost System Performance by Enabling Automatic File Deletion in WINOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-hotkeys-for-instantaneous-windows-redos/"><u>Boost Efficiency: Hotkeys for Instantaneous Windows Redos</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-11-pro-passcode-screen-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 11 Pro Passcode Screen?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beating-the-bug-the-comprehensible-guide-for-resolving-error-0x800700e9-in-xbox-game-pass-and-windows-11/"><u>Beating the Bug: The Comprehensible Guide for Resolving Error 0X800700E9 in Xbox Game Pass & Windows 11</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-video-enhancement-software-boost-clarity-and-detail-instantly/"><u>Updated 2024 Approved Video Enhancement Software Boost Clarity and Detail Instantly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-windowed-app-movement-windows-task-managing-tips/"><u>Avoiding Windowed App Movement: Windows Task Managing Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assessing-windows-app-size-efficiency/"><u>Assessing Windows App Size Efficiency</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/travel-blogging-essentials-step-by-step-path-to-success-for-2024/"><u>Travel Blogging Essentials  Step-by-Step Path to Success for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-hot-takes-highlight-twitters-trending-topics-for-2024/"><u>[Updated] Hot Takes Highlight  Twitter's Trending Topics for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-audio-clarity-10-pro-tips-for-high-quality-recordings/"><u>2024 Approved  Audio Clarity  10 Pro Tips for High-Quality Recordings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-machines-explained-how-they-stand-out/"><u>AI Machines Explained: How They Stand Out</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advancing-microsofts-phone-functionality-on-windows-11/"><u>Advancing Microsoft’s Phone Functionality on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-browser-safety-on-windows-11-with-the-implementation-of-defender-aguard/"><u>Boost Browser Safety on Windows 11 with the Implementation of Defender Aguard</u></a></li>
</ul></div>
