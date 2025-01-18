---
title: Troubleshooting PC Doesn't Meet Game Bar Issue
date: 2025-01-11T16:04:11.927Z
updated: 2025-01-18T18:00:25.353Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting PC Doesn't Meet Game Bar Issue
excerpt: This Article Describes Troubleshooting PC Doesn't Meet Game Bar Issue
keywords: Fixing Gaming Issues,Resolve Game Bar Errors,Troubleshoot PC Games,Overcoming PC Playbar,Addressing Game Performance,Solving Game Bar Problems,Enhancing Gameplay Experience
thumbnail: https://thmb.techidaily.com/d3c3a020a8c3e31354179c514456d8a6b689ea566aeb576eef913d65398f2493.jpg
---

## Troubleshooting PC Doesn't Meet Game Bar Issue

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3UyJuZYzjt0?si=W87GeyzVKVORAk7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Delete the **0** number and input **1** within the **Value data** box.  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-dword-window.jpg)
7. Set the value by clicking **OK** inside the Edit DWORD window.
8. Then close out of the Registry Editor app and restart Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xIP8ktrmOdg?si=zRnjbGzM6PDx2jCq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Wy0uYNNdMDM?si=5ir7EHlr0CkpcYOT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/qfCSLAhd4FY?si=CUBztmilaeAwl1lw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-clips.techidaily.com/new-projecting-yourself-to-the-world-with-insta-captions/"><u>[New] Projecting Yourself to the World with Insta Captions</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-tips-for-supercharging-tiktok-videos-with-professional-voiceovers/"><u>[Updated] 2024 Approved Tips for Supercharging TikTok Videos with Professional Voiceovers</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-from-silent-movies-to-sound-films-a-modern-tutorial/"><u>[Updated] From Silent Movies to Sound Films A Modern Tutorial</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-in-2024-visual-storytelling-101-mastering-the-art-of-posting-images-on-youtube/"><u>[Updated] In 2024, Visual Storytelling 101 Mastering the Art of Posting Images on YouTube</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/compatible-with-any-windows-os-secure-your-oculus-driver-downloads-now-windows-11-10-8-and-7/"><u>Compatible with Any Windows OS: Secure Your Oculus Driver Downloads Now! (Windows 11, 10, 8 & 7)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-rdp-error-codes-in-modern-windows-systems/"><u>Decoding RDP Error Codes in Modern Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-admin-command-execution-without-hurdles/"><u>Ensuring Admin Command Execution Without Hurdles</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-secure-is-duckduckgo-compared-to-other-search-engines-exploring-the-facts/"><u>How Secure Is DuckDuckGo Compared to Other Search Engines? Exploring the Facts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-game-bars-pc-doesnt-meet-hardware-requirements-for-captures-error-in-windows/"><u>How to Fix Game Bar’s “PC Doesn't Meet Hardware Requirements for Captures” Error in Windows</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-gopro-hero4-session-vs-hero5-session/"><u>In 2024, GoPro Hero4 Session Vs Hero5 Session</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-search-for-integrity-how-to-filter-out-fake-windows-apps/"><u>In Search for Integrity: How to Filter Out Fake Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-workflow-integrate-onedrive-and-microsoft-id/"><u>Streamline Your Workflow: Integrate OneDrive & Microsoft ID</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-fundamentals-of-creating-alluring-podcast-descriptions/"><u>The Fundamentals of Creating Alluring Podcast Descriptions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-non-functional-deletion-keys-in-windows/"><u>Troubleshooting Non-Functional Deletion Keys in Windows</u></a></li>
</ul></div>

