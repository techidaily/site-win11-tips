---
title: Fixing Windows Game Capture Denial Due to Low Specs
date: 2024-07-12T17:23:28.752Z
updated: 2024-07-13T17:23:28.752Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Windows Game Capture Denial Due to Low Specs
excerpt: This Article Describes Fixing Windows Game Capture Denial Due to Low Specs
keywords: Game Performance Optimization,Resolve High FPS Issues,Enhance Gaming Speed,Tackle Latency Problems,Overcome Low Spec Limitations,Improve Windows Capture,Address Specs Restrictions
thumbnail: https://thmb.techidaily.com/ba4d76a3836c79aa2d1ffbc408b14921a58fa2b19ac7a8b8eb3ad2286e02cfeb.jpg
---

## Fixing Windows Game Capture Denial Due to Low Specs

 Many users utilize the Xbox Game Bar app pre-installed with Windows for recording game clips. However, some users can’t record anything with the Game Bar because of an error that says, “sorry, your PC doesn't meet the hardware requirements for captures.” That error message can appear within Settings or when users select to record.

 The error message highlights a PC doesn’t meet system requirements for Game Bar recording. Yet, this error often arises for users who’ve utilized Game Bar’s recording on their PCs before. This is how you can fix the “PC doesn't meet the hardware requirements for captures” error in Windows 10 and 11\.

## Enable Game DVR With Game DVR Config

 Game DVR Config is third-party software with which some users have resolved the “PC doesn't meet the hardware requirements for captures” error. That software includes settings users can select to enable Game DVR along with audio and microphone capture.

 Here is how you can enable Game DVR with that software:

1. Open the [Game DVR Config](https://github.com/FunkyFr3sh/GameDVR%5FConfig/releases) page.
2. Click the **GameDVR\_Config.exe** download link.
3. Bring up Windows Explorer and the Downloads folder or other directory containing the Game DVR file.
4. Double-click the **GameDVR\_Config** file.
5. Select the **Enable Game DVR (Win+G)** checkbox.  
![The Game DVR Config software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/game-dvr-config.jpg)
6. Click the **Force software MFT** checkbox to select that setting.
7. Exit Game DVR Config and [open Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/).
8. Look for the Broadcast DVR server on the **Processes** tab. Right-click Broadcast DVR Server and select **End task** if you can find that process.

## Edit the Control Registry Key

 Editing the Control registry key is a fix that’s worked for some users. Try editing that key like this:

1. To activate Run, simultaneously press **Win** \+ **R**.
2. Type **regedit** within the Run command box and press the **Enter** key.
3. Clear the text in the address bar and input this registry key location there:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control`
4. If there isn’t a **PortableOperatingSystem** DWORD already, right-click on the **Control** key and select **New** and **DWORD**. Input **PortableOperatingSystem** within the new key’s text box.  
![The New and Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/new-key-options.jpg)
5. Double-click on the **PortableOperatingSystem** DWORD in the Control key.
6. Delete the **0** number and input **1** within the **Value data** box.  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-dword-window.jpg)
7. Set the value by clicking **OK** inside the Edit DWORD window.
8. Then close out of the Registry Editor app and restart Windows.

## Update Your Graphics Adapter’s Driver

 An outdated or faulty graphics driver might be causing this recording issue on your PC. Try installing the latest graphics driver for your GPU if you haven’t updated it in a while (or ever). This guide tells you [how to update a PC’s graphics driver in Windows](http://www.makeuseof.com/update-graphics-drivers-in-windows-10/).

![The NVIDIA graphics driver download page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/nvidia-driver-download.jpg)

## Enable the Windows Game Recording and Broadcasting Policy

 Group Policy Editor includes a Game Recording and Broadcasting policy that prevents recording when disabled. So, Windows Pro and Enterprise users must make sure that the Game Recording and Broadcasting policy is set to enabled. Do note that Windows Home doesn’t include the Group Policy Editor.

 Here is how you can enable that policy:

1. [Open Local Group Policy Editor](https://www.makeuseof.com/tag/open-local-group-policy-editor-windows/) and double-click **Computer Configuration** when it appears.
2. Double-click **Administrative Templates** \> **Windows Components**.
3. Select **Windows Game Recording and Broadcasting** in Group Policy’s sidebar.
4. Then double-click on the **Enables or disables Windows Game Recording and Broadcasting** policy.  
![The Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/group-policy-editor.jpg)
5. Click **Enabled** if that policy is disabled.
6. Select **Apply** to enable the recording policy and **OK** to close the window.  
![The Enables or disables Windows Game Recording and Broadcasting policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-game-and-recording-policy-window.jpg)
7. Close Group Policy Editor, bring up your Start menu and select **Power** \> **Restart**.

## Erase Data in the GameDVR Registry Key

 Corrupted GameDVR entries within the registry can cause the “PC doesn't meet the hardware requirements for captures” error. You can fix that by deleting DWORDs and strings in the GameDVR registry key, which will automatically regenerate. However, we still recommend users back up the registry before applying this potential solution.

 You can erase data from the GameDVR registry key as follows:

1. Open Registry Editor with Run, as covered in the first couple of steps of resolution two.
2. Go to this GameDVR registry key location:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\GameDVR`
3. Select all DWORDs and strings within the GameDVR key by holding the **Ctrl** key and clicking on them.
4. Then right-click and select **Delete** \> **Yes**.  
![the-delete-option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-delete-option.jpg)
5. Click the Start menu’s Power button and select **Restart**.

## Get Recording Again With the Xbox Game Bar

 The potential solutions covered here are widely confirmed to resolve the “PC doesn't meet the hardware requirements for captures” by users who’ve needed to fix that issue. So, it’s most likely applying the potential fixes above will resolve that Game Bar recording issue on your Windows laptop or desktop. Then you can record video while gaming with the Game Bar’s recording feature again.

 The error message highlights a PC doesn’t meet system requirements for Game Bar recording. Yet, this error often arises for users who’ve utilized Game Bar’s recording on their PCs before. This is how you can fix the “PC doesn't meet the hardware requirements for captures” error in Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://android-unlock.techidaily.com/in-2024-a-perfect-guide-to-remove-or-disable-google-smart-lock-on-vivo-y27-4g-by-drfone-android/"><u>In 2024, A Perfect Guide To Remove or Disable Google Smart Lock On Vivo Y27 4G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactical-tutorials-for-new-folder-navigation-in-win11/"><u>Tactical Tutorials for New Folder Navigation in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/too-much-glitches-handle-deps-before-virtualbox-on-win/"><u>Too Much Glitches? Handle Deps Before VirtualBox on Win</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-microphone-matchmaking-adapting-to-your-youtube-channels-needs/"><u>[New] Microphone Matchmaking  Adapting to Your YouTube Channel's Needs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-invalid-steam-response-issue/"><u>Steps to Resolve Invalid Steam Response Issue</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-ultimate-selection-the-top-7-daws-excelling-in-guitar-track-production-updated-for-2024/"><u>New Ultimate Selection The Top 7 DAWs Excelling in Guitar Track Production (Updated ) for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-discovering-the-top-tools-for-engaging-video-beginnings-for-2024/"><u>[New] Discovering the Top Tools for Engaging Video Beginnings for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-remove-screen-lock-pin-on-vivo-v27e-like-a-pro-5-easy-ways-by-drfone-android/"><u>How To Remove Screen Lock PIN On Vivo V27e Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-stabilizing-dwarf-fortress-on-win/"><u>Solutions for Stabilizing Dwarf Fortress on Win</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/the-ultimate-guide-to-the-best-7-tiktok-apps-for-success/"><u>The Ultimate Guide to the Best 7 TikTok Apps for Success</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-in-depth-analysis-best-desktop-video-recorders/"><u>[New] 2024 Approved  In-Depth Analysis  Best Desktop Video Recorders</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-photos-from-21-by-fonelab-android-recover-photos/"><u>How to Rescue Lost Photos from 21?</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-the-ultimate-guide-to-vignette-apps-free-and-paid-options-for-ios-and-android-for-2024/"><u>Updated The Ultimate Guide to Vignette Apps Free and Paid Options for iOS and Android for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-evolution-and-function-of-modern-vr-helmets/"><u>[Updated] The Evolution and Function of Modern VR Helmets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719307808288-tackling-windows-glitches-find-solutions-now/"><u>Tackling Windows Glitches: Find Solutions Now!</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-7-phone-number-locators-to-track-xiaomi-redmi-12-location-drfone-by-drfone-virtual-android/"><u>Top 7 Phone Number Locators To Track Xiaomi Redmi 12 Location | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-unlock-a-locked-out-windows-11-with-error-22/"><u>Strategies to Unlock a Locked Out Windows 11 with Error 22</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-15-apps-to-hack-wifi-password-on-samsung-galaxy-a14-4g-by-drfone-android/"><u>In 2024, Top 15 Apps To Hack WiFi Password On Samsung Galaxy A14 4G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-windows-11-bluetooth-try-connecting-error/"><u>Steps to Resolve Windows 11 Bluetooth 'Try Connecting' Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-ensure-seamless-windows-notepad-functioning/"><u>Steps to Ensure Seamless Windows Notepad Functioning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-steps-to-disable-automatic-updates-in-windows/"><u>5 Steps To Disable Automatic Updates in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbo-enabledisable-bing-ai-on-windows-11-search-bar/"><u>Turbo Enable/Disable: Bing AI on Windows 11 Search Bar</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-gain-traction-in-yt-mastering-green-screen-ctas/"><u>2024 Approved  Gain Traction in YT  Mastering Green Screen CTAs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-routines-to-pause-windows-and-office-software-updates/"><u>4 Routines to Pause Windows & Office Software Updates</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-premier-mp4-broadcast-suite/"><u>[New] In 2024, Premier MP4 Broadcast Suite</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win10-isolating-and-fixing-unilateral-audio-malfunction/"><u>Win10: Isolating and Fixing Unilateral Audio Malfunction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sticky-notes-strategies-for-sustained-top-level-visibility-on-win-os/"><u>Sticky Notes Strategies for Sustained Top-Level Visibility on Win OS</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-frp-on-honor-magic-v2-by-drfone-android/"><u>In 2024, How to Bypass FRP on Honor Magic V2?</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/instagram-feed-adding-videos/"><u>Instagram Feed  Adding Videos</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/elevating-content-strategy-through-youtube-metrics-for-2024/"><u>Elevating Content Strategy Through YouTube Metrics for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-2024-approved-ranked-your-must-have-5-iphones-for-excellent-podcasting/"><u>[New] 2024 Approved  Ranked  Your Must-Have 5 iPhones for Excellent Podcasting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/whats-behind-windows-11s-disappearing-thumbnail-issue-fixes-here/"><u>What's Behind Windows 11'S Disappearing Thumbnail Issue? Fixes Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-windows-workshop-generating-and-deciphering-system-insights/"><u>The Windows Workshop: Generating & Deciphering System Insights</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-accelerated-cinematography-best-5-diy-hacks-for-quick-learning/"><u>In 2024, Accelerated Cinematography  Best 5 DIY Hacks for Quick Learning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-powershell-errors-with-script-enablement-fixes/"><u>Troubleshooting PowerShell Errors with Script Enablement Fixes</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-learn-how-everything-works-on-tecno-camon-20-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Learn How Everything Works On Tecno Camon 20 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-10s-guide-to-effortlessly-merge-data/"><u>Win 10'S Guide to Effortlessly Merge Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/use-external-tools-explore-third-party-software-like-flux-redshift-or-display-temp-to-customize-display-behavior-according-to-time-of-day-and-ambient-light-26/"><u>Use External Tools: Explore Third-Party Software Like f.lux, Redshift, or Display Temp to Customize Display Behavior According to Time of Day and Ambient Light Conditions</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/n-2024-clear-youtube-watch-later-playlist-step-by-step/"><u>[New] In 2024, Clear YouTube Watch Later Playlist - [Step-by-Step]</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-troubled-tracker-fixes-for-frozen-torrents/"><u>Tackling the Troubled Tracker: Fixes for Frozen Torrents</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-recover-non-operational-windows-apps/"><u>Steps to Recover Non-Operational Windows Apps</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-13-pro-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone 13 Pro without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/portable-computing-orientation-set-right/"><u>Portable Computing - Orientation Set Right</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-evolutionary-leap-with-ai-copilot-in-windows-11-life/"><u>The Evolutionary Leap with AI Copilot in Windows 11 Life</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-windows-11-calculator-activation/"><u>Steps for Windows 11 Calculator Activation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncharted-errors-the-8-most-crucial-mistakes-for-new-windows-11-users/"><u>Uncharted Errors: The 8 Most Crucial Mistakes for New Windows 11 Users</u></a></li>
<li><a href="https://techidaily.com/xiaomi-won-t-play-mov-videos-how-to-fix-by-aiseesoft-video-converter-play-mov-on-android/"><u>Xiaomi  won't play MOV videos, how to fix ?</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-brief-bliss-in-photo-collage-crafting-the-google-way/"><u>2024 Approved  Brief Bliss in Photo Collage Crafting - The Google Way</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-the-windows-print-management-tool-and-how-do-you-access-it/"><u>What Is the Windows Print Management Tool, and How Do You Access It?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-windows-from-repeatedly-accessing-cmos-settings/"><u>Stop Windows From Repeatedly Accessing CMOS Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-keep-lol-playtime-uninterrupted-in-windows/"><u>Strategies to Keep LoL Playtime Uninterrupted in Windows</u></a></li>
</ul></div>
