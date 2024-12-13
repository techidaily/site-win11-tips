---
title: How to Fix Game Bar’s “PC Doesn't Meet Hardware Requirements for Captures” Error in Windows
date: 2024-12-10T19:44:44.535Z
updated: 2024-12-12T22:58:05.010Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix Game Bar’s “PC Doesn't Meet Hardware Requirements for Captures” Error in Windows
excerpt: This Article Describes How to Fix Game Bar’s “PC Doesn't Meet Hardware Requirements for Captures” Error in Windows
keywords: Fix Game Bar Error,Resolve PC Capture Issue,Overcome Game Bar Warning,Stop Hardware Requirement Error,Eliminate Capture Fail Error,Windows Game Capture Fix,Correcting Game Bar Errors
thumbnail: https://thmb.techidaily.com/6aaf83c5a09999402e25379b87750585dedbdeb12f25c6a6196a672ab852e088.jpg
---

## How to Fix Game Bar’s “PC Doesn't Meet Hardware Requirements for Captures” Error in Windows

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DBMTAJBx-X4?si=sje5pFJXiHzJJGbP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vfq0vw0Spz8?si=2EAk6hW-Gb-o33_L" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oP8grXxuy2o?si=uIRNhTYbecTcaC7J" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LW6wNx3XAj8?si=VaIuFIIx8MM_RhUR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-zero.techidaily.com/024-approved-engaging-listeners-respectfully-for-increased-sign-ups/"><u>[New] 2024 Approved Engaging Listeners Respectfully for Increased Sign-Ups</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-from-hidden-channels-to-the-throne-of-1k-subscribers/"><u>[New] 2024 Approved From Hidden Channels to the Throne of 1K Subscribers</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-essential-guide-top-10-steps-for-instructors-on-youtube-channels/"><u>[Updated] In 2024, Essential Guide Top 10 Steps for Instructors on YouTube Channels</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-iphone-video-editing-showdown-cameo-against-filmorago/"><u>[Updated] IPhone Video Editing Showdown Cameo Against FilmoraGo</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-save-youtube-playback-a-comprehensive-screencast-guide-at-no-cost/"><u>[Updated] Save YouTube Playback A Comprehensive Screencast Guide at No Cost</u></a></li>
<li><a href="https://screen-recording.techidaily.com/critical-analysis-of-vsdc-highlighting-best-software-for-2024/"><u>Critical Analysis of VSDC, Highlighting Best Software for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fully-delete-wsl-on-modern-windows/"><u>How to Fully Delete WSL on Modern Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-xiaomi-13t-pro-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Xiaomi 13T Pro Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-11-parental-controls-setup/"><u>Navigating Windows 11 Parental Controls Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stay-ahead-of-tech-effective-firmware-update-practices-for-surfaces/"><u>Stay Ahead of Tech: Effective Firmware Update Practices for Surfaces</u></a></li>
<li><a href="https://discover-awesome.techidaily.com/step-by-step-guide-converting-multi-track-hd-video-files-into-avi-mp4-for-smartphones-and-tablets/"><u>Step-by-Step Guide: Converting Multi-Track HD Video Files Into AVI MP4 for Smartphones and Tablets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-work-around-microsoft-defender-exclusivity-issue/"><u>Strategies to Work Around Microsoft Defender Exclusivity Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-secrets-credential-manager-troubleshooting/"><u>Unlock Secrets: Credential Manager Troubleshooting</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/unveiling-the-secrets-to-verified-instagram-images/"><u>Unveiling the Secrets to Verified Instagram Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-the-war-against-software-strife-with-pct/"><u>Winning the War Against Software Strife with PCT</u></a></li>
</ul></div>

