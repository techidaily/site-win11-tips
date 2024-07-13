---
title: Addressing Game Bar Errors on Underpowered Systems
date: 2024-07-12T17:03:19.848Z
updated: 2024-07-13T17:03:19.848Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Game Bar Errors on Underpowered Systems
excerpt: This Article Describes Addressing Game Bar Errors on Underpowered Systems
keywords: Game Bar Fix Guide,Low-Power Gaming Tips,Overcome System Lag,Optimize Windows Games,Resolve Graphics Freeze,Performance in Underpowered PCs,Efficient Error Handling
thumbnail: https://thmb.techidaily.com/60a050976608e9140d90809a0ac2529ef41e9995b243e26e295a790742b88b8b.jpg
---

## Addressing Game Bar Errors on Underpowered Systems

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
<li><a href="https://tiktok-video-files.techidaily.com/new-dynamic-diversity-30plus-fresh-biographical-strategies-to-triple-your-views-following-on-tiktok-filmora-platform/"><u>[New] Dynamic Diversity  30+ Fresh Biographical Strategies to Triple Your Views, Following on TikTok-Filmora Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-file-denial-in-steam-for-windows-11-users/"><u>Tackling File Denial in Steam for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-line-magic-automating-archive-creation-in-windows/"><u>Command Line Magic: Automating Archive Creation in Windows</u></a></li>
<li><a href="https://youtube-data.techidaily.com/spiring-youtube-guides-for-aspiring-singers-and-instrumentalists/"><u>15 Inspiring YouTube Guides for Aspiring Singers and Instrumentalists</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-enhance-visual-clarity-premier-video-marker-eraser/"><u>[New] Enhance Visual Clarity  Premier Video Marker Eraser</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/ultimate-guide-from-zte-blade-a73-5g-frp-bypass-by-drfone-android/"><u>Ultimate Guide from ZTE Blade A73 5G FRP Bypass</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-hidden-pathways-open-directory-games-in-windows/"><u>The Hidden Pathways: Open Directory Games in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sharpen-windows-safety-edge-context-menu-firewall-customization-guide/"><u>Sharpen Windows Safety Edge: Context Menu Firewall Customization Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-windows-problems-effective-assistance-guide/"><u>Conquer Windows Problems: Effective Assistance Guide</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-a-step-by-step-approach-to-saving-your-screen-while-streaming/"><u>[Updated] In 2024, A Step-by-Step Approach to Saving Your Screen While Streaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-11-reactivating-deactivated-voice-command/"><u>Addressing Windows 11: Reactivating Deactivated Voice Command</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-window-into-evolution-noteworthy-windows-11-file-enhancements/"><u>A Window Into Evolution: Noteworthy Windows 11 File Enhancements</u></a></li>
<li><a href="https://extra-information.techidaily.com/ultimate-choice-top-mp4-players-unveiled/"><u>Ultimate Choice  Top MP4 Players Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-windows-11-visuality-with-app-sizing/"><u>Boosting Windows 11 Visuality with App Sizing</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-virtualdub-vs-the-competition-a-comprehensive-review-and-alternative-guide/"><u>In 2024, Virtualdub Vs. The Competition A Comprehensive Review and Alternative Guide</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/2024-approved-mastering-audio-recording-and-integrating-narration-into-video-projects/"><u>2024 Approved Mastering Audio Recording and Integrating Narration Into Video Projects</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-guide-to-retaining-your-tiktok-content-post-reload-glitch-for-2024/"><u>[New] Guide to Retaining Your TikTok Content Post-Reload Glitch for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-routes-to-windows-control-panel-entry/"><u>Unveiling the Routes to Windows Control Panel Entry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-the-new-os-build-a-focused-and-effective-windows-11-boot-drive-in-three-ways/"><u>Conquer the New OS – Build a Focused and Effective Windows 11 Boot Drive in Three Ways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-fatal-javascript-issue-with-ease-on-win-11-discord/"><u>Conquering Fatal Javascript Issue with Ease on Win 11 Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-and-fixing-the-msvcr110dll-gap/"><u>Uncovering & Fixing the Msvcr110.dll Gap</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-initiate-sfc-process-in-windows-1087/"><u>Steps to Initiate SFC Process in Windows 10/8/7</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-hidefake-snapchat-location-on-your-samsung-galaxy-s24plus-drfone-by-drfone-virtual-android/"><u>How to Hide/Fake Snapchat Location on Your Samsung Galaxy S24+ | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-effortlessly-pinning-friends-on-snapchat-with-confidence/"><u>[Updated] In 2024, Effortlessly Pinning Friends on Snapchat with Confidence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speed-spectrum-mastering-windows-network-adapter-assessment-methods/"><u>Speed Spectrum: Mastering Windows' Network Adapter Assessment Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-fixes-for-the-v22h2-update-dilemma-on-win11-os/"><u>Efficient Fixes for the V22H2 Update Dilemma on Win11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/surreptitious-shutdown-strategy-for-windows-11/"><u>Surreptitious Shutdown Strategy for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoidance-of-error-0x80070570-saving-your-damaged-files-in-windows-11/"><u>Avoidance of Error 0X80070570: Saving Your Damaged Files in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unpacking-the-delay-in-windows-11-adoption/"><u>Unpacking the Delay in Windows 11 Adoption</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-door-on-stuck-wow-61-patches/"><u>Unlocking the Door on Stuck WoW 6.1 Patches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-mute-microphone-issue-during-video-recordings/"><u>Tackling Mute Microphone Issue During Video Recordings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrading-widely-used-directx-classics-through-dxvk/"><u>Upgrading Widely-Used DirectX Classics Through DXVK</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-complex-archives-efficiently-handling-multiple-zips-in-one-go/"><u>Decoding Complex Archives: Efficiently Handling Multiple ZIPS in One Go</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-your-lost-dxgidll-with-these-win11-hacks/"><u>Restore Your Lost Dxgi.dll with These Win11 Hacks</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-converting-youtube-broadcasts-into-listenable-formats-for-2024/"><u>[Updated] Converting YouTube Broadcasts Into Listenable Formats for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-window-11-screens-a-comprehensive-wallpaper-plan/"><u>Tailoring Window 11 Screens: A Comprehensive Wallpaper Plan</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-the-variance-in-procedures-for-local-and-remote-windows-reinstallations/"><u>Analyzing the Variance in Procedures for Local and Remote Windows Reinstallations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-resetting-windows-settings-on-reboot/"><u>Steps for Resetting Windows Settings on Reboot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correct-camera-omission-from-windows-dm-display/"><u>Correct Camera Omission From Windows' DM Display</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-the-hurdles-of-xbox-game-pass-error-code-0-essential-tips-for-windows-11-users/"><u>Avoiding the Hurdles of Xbox Game Pass Error Code 0: Essential Tips for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-and-taming-high-cpu-use-in-modern-windows-host/"><u>Deciphering and Taming High CPU Use in Modern Windows Host</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-csgo-launch-failures-on-w11/"><u>Troubleshooting CS:GO Launch Failures on W11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-epic-playlist-over-a-hundred-top-tier-titles/"><u>2024 Approved  Epic Playlist  Over a Hundred Top-Tier Titles</u></a></li>
</ul></div>
