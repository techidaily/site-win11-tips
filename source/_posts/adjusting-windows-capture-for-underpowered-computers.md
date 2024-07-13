---
title: Adjusting Windows Capture for Underpowered Computers
date: 2024-07-12T18:00:34.635Z
updated: 2024-07-13T18:00:34.635Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Windows Capture for Underpowered Computers
excerpt: This Article Describes Adjusting Windows Capture for Underpowered Computers
keywords: Power-Efficient Capture Settings,Low-Spec Computer Recording,Optimized Video Capture,Efficient Windows Capture,Customizing Underpowered PCs,Enhancing WinCapture Performance,Adjusting for Weak Systems
thumbnail: https://thmb.techidaily.com/8d4f635de6f8288e79a21d2dcf9027cad8747323c88b4f310acedbe966d2fadc.jpg
---

## Adjusting Windows Capture for Underpowered Computers

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-information.techidaily.com/new-conduct-your-clicks-harmonize-images-and-sounds/"><u>[New] Conduct Your Clicks  Harmonize Images & Sounds</u></a></li>
<li><a href="https://youtube-data.techidaily.com/-social-media-perspective-dissecting-igtv-versus-youtubes-features-for-2024/"><u>[New] A Social Media Perspective  Dissecting IGTV versus YouTube's Features for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginners-guide-efficient-w11-microphone-use/"><u>Beginner's Guide: Efficient W11 Microphone Use</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/thriving-as-an-online-gaming-content-creator-for-2024/"><u>Thriving as an Online Gaming Content Creator for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-maximizing-clarity-improve-iphoneandroid-video-quality-for-2024/"><u>[New] Maximizing Clarity  Improve iPhone/Android Video Quality for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-aural-journey-illustrating-sound-patterns-with-waveform-graphics-and-dynamic-animations-in-nle-essential/"><u>In 2024, Aural Journey Illustrating Sound Patterns with Waveform Graphics and Dynamic Animations in NLE Essential</u></a></li>
<li><a href="https://win11-tips.techidaily.com/batch-rename-made-easy-the-powerof-tools-guide/"><u>Batch-Rename Made Easy: The PowerOf Tools Guide</u></a></li>
<li><a href="https://extra-information.techidaily.com/from-novice-to-pro-your-journey-with-hdr-in-ps/"><u>From Novice to Pro  Your Journey with HDR in PS</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-navigating-adobe-clouds-storage-explained-simply-with-comparisons/"><u>[New] Navigating Adobe Cloud's Storage, Explained Simply with Comparisons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-auto-lock-on-windows-tips-and-tricks/"><u>Avoiding Auto-Lock on Windows: Tips & Tricks</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-maximizing-instagram-video-lengths-a-step-by-step-guide-for-2024/"><u>[New] Maximizing Instagram Video Lengths  A Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-pitfalls-with-microsoft-teams-how-to-conquer-error-80080300/"><u>Avoiding Pitfalls with Microsoft Teams: How to Conquer Error 80080300</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-social-media-savvy-top-101-bio-tips-and-techniques-for-facebookers/"><u>[New] Social Media Savvy  Top 101 Bio Tips & Techniques for Facebookers</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-expert-color-techniques-for-professional-visual-narratives/"><u>2024 Approved  Expert Color Techniques for Professional Visual Narratives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/approach-to-reveal-hidden-drives-on-windows/"><u>Approach to Reveal Hidden Drives on Windows</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-6-ways-to-transfer-contacts-from-oppo-f25-pro-5g-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 6 Ways To Transfer Contacts From Oppo F25 Pro 5G to iPhone | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-sfx-strategies-for-windows-11-users/"><u>Advanced SFX Strategies for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-workflow-the-ultimate-guide-to-wpm-in-windows-11/"><u>Boost Your Workflow: The Ultimate Guide to WPM in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/backup-plan-for-windows-users-when-bitlocker-isnt-an-option/"><u>Backup Plan for Windows Users When BitLocker Isn't an Option</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-windows-11-outputs-with-savvy-techniques/"><u>Amplify Windows 11 Outputs with Savvy Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-call-productivity-on-windows-11-with-the-intel-unison-app/"><u>Boosting Call Productivity on Windows 11 with the Intel Unison App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assessing-lighter-browsing-options-best-in-class-for-ram-consumption/"><u>Assessing Lighter Browsing Options: Best in Class for RAM Consumption</u></a></li>
<li><a href="https://win11-tips.techidaily.com/black-friday-bonanza-get-your-deal-612-for-eternal-windows-10/"><u>Black Friday Bonanza: Get Your Deal - $6.12 for Eternal Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-windows-11-highlighted-icons-for-tidy-desktop/"><u>Banish Windows 11 Highlighted Icons for Tidy Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-terminals-user-privilege-settings/"><u>Adjusting Windows Terminal's User Privilege Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplifying-graphical-performance-in-windows-11s-safeguard-feature/"><u>Amplifying Graphical Performance in Windows 11'S Safeguard Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-integration-windows-11s-next-chapter/"><u>AI Integration: Windows 11'S Next Chapter</u></a></li>
<li><a href="https://video-capture.techidaily.com/mastering-online-meetings-with-these-budget-friendly-video-conferencing-services/"><u>Mastering Online Meetings with These Budget-Friendly Video Conferencing Services</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-top-8-best-video-quality-enhancers-free-and-paid/"><u>New 2024 Approved Top 8 BEST Video Quality Enhancers Free & Paid</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-window-placement-for-windows-users/"><u>Adjust Window Placement for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-wows-endless-loop-fix-error-132-in-win-editions/"><u>Avoid WoW's Endless Loop: Fix Error 132 in Win Editions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-assistants-impact-on-windows-11-experience/"><u>AI Assistant's Impact on Windows 11 Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-functionality-and-visual-impact-of-win11-taskbar-icons/"><u>Boosting Functionality & Visual Impact of Win11 Taskbar Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-windows-11-protection-with-new-firewall-add-ons-in-the-context-menu/"><u>Boost Windows 11 Protection with New Firewall Add-Ons in the Context Menu</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-avoiding-the-hashtag-void-strategies-for-tiktok-success-for-2024/"><u>[Updated] Avoiding the Hashtag Void  Strategies for TikTok Success for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-boosted-audio-visual-experience-choose-av1-on-youtube-for-2024/"><u>[Updated] Boosted Audio-Visual Experience  Choose AV1 on YouTube for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-setting-up-shortcuts-for-windows-troubleshooters/"><u>Boost Efficiency: Setting Up Shortcuts for Windows Troubleshooters</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-redefining-schooling-with-virtual-reality/"><u>[Updated] Redefining Schooling with Virtual Reality</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>