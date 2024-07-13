---
title: "Altering Taskbar Size: Step-by-Step Guide"
date: 2024-07-12T18:04:10.532Z
updated: 2024-07-13T18:04:10.532Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Altering Taskbar Size: Step-by-Step Guide"
excerpt: "This Article Describes Altering Taskbar Size: Step-by-Step Guide"
keywords: Taskbar Resize Tutorial,Windows Adjust Bar,Set Taskbar Width,Modify Taskbar,TaskSize Change Steps,Customizing Bar Size,Alter Taskbar Sizes Guide
thumbnail: https://thmb.techidaily.com/25b0e40b25535b4355b8cca4194992e02cab9c78ac10458526a89f4c7d70d265.jpg
---

## Altering Taskbar Size: Step-by-Step Guide

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
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-augmenting-film-quality-integrating-letterboxing-in-digital-spaces/"><u>[Updated] In 2024, Augmenting Film Quality  Integrating Letterboxing in Digital Spaces</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-integration-in-windows-11-for-effective-multitasking/"><u>Android Integration in Windows 11 for Effective Multitasking</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/unveiling-booktiks-must-read-masterpieces-a-reading-delight-for-2024/"><u>Unveiling #Booktik's Must-Read Masterpieces  A Reading Delight for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beating-the-bug-the-comprehensible-guide-for-resolving-error-0x800700e9-in-xbox-game-pass-and-windows-11/"><u>Beating the Bug: The Comprehensible Guide for Resolving Error 0X800700E9 in Xbox Game Pass & Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-task-handling-a-guide-to-windows-11-mastery/"><u>Boosting Task Handling - A Guide to Windows 11 Mastery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-not-recognized-issues-in-windows-with-these-fixes/"><u>Banish 'Not Recognized' Issues in Windows with These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-development-with-these-wsl-2-secrets/"><u>Boost Your Development with These WSL 2 Secrets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-windowed-app-movement-windows-task-managing-tips/"><u>Avoiding Windowed App Movement: Windows Task Managing Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-operations-efficient-data-alignment-in-win11/"><u>Boost Operations: Efficient Data Alignment in Win11</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-integrated-camera-use-photos-and-videos-on-one-phone-for-2024/"><u>[New] Integrated Camera Use  Photos and Videos on One Phone for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-nvidia-writes-of-error-3-in-win1011/"><u>Avoiding NVIDIA' Writes of Error 3 in Win10/11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-card-on-nokia-c22-online-without-jailbreak-by-drfone-android/"><u>In 2024, How to Unlock SIM Card on Nokia C22 online without jailbreak</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-tips-for-managing-users-via-command-prompt/"><u>Advanced Tips for Managing Users via Command Prompt</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-vanguard-of-radio-theatre-composition/"><u>In 2024, The Vanguard of Radio-Theatre Composition</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-find-my-friends-work-on-realme-narzo-60-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Does find my friends work on Realme Narzo 60 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altwindirstat-strategies-for-effective-disk-space-management/"><u>AltWinDirStat Strategies for Effective Disk Space Management</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-voice-over-fundamentals-from-syncing-dialogue-to-final-cut-for-2024/"><u>[New] Voice Over Fundamentals  From Syncing Dialogue to Final Cut for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-aspire-with-angles-crafting-compelling-visuals-through-instagram-rotation/"><u>[New] Aspire with Angles  Crafting Compelling Visuals Through Instagram Rotation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-system-performance-by-enabling-automatic-file-deletion-in-winos/"><u>Boost System Performance by Enabling Automatic File Deletion in WINOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-windows-apps-with-efficient-internet-fixes/"><u>Boost Your Windows Apps with Efficient Internet Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/arrow-anomalies-unveiled-and-resolved-for-windows-users/"><u>Arrow Anomalies Unveiled and Resolved for Windows Users</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-boost-your-insta-reels-with-tiktok-inspired-hits-and-stats/"><u>In 2024, Boost Your Insta Reels with TikTok-Inspired Hits and Stats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-pc-display-orientation-via-windows/"><u>Adjust PC Display Orientation via Windows</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-fast-track-controlling-netflix-playback-speeds/"><u>2024 Approved  Fast Track - Controlling Netflix Playback Speeds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-integration-microsofts-new-taskbar-helper-in-windows-11-streamlines-tasks/"><u>AI Integration: Microsoft's New Taskbar Helper in Windows 11 Streamlines Tasks</u></a></li>
<li><a href="https://vp-tips.techidaily.com/adobe-audition-tutorial-managing-sound-curves/"><u>Adobe Audition Tutorial  Managing Sound Curves</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assessing-windows-app-size-efficiency/"><u>Assessing Windows App Size Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-hotkeys-for-instantaneous-windows-redos/"><u>Boost Efficiency: Hotkeys for Instantaneous Windows Redos</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-how-to-make-fortnite-thumbnail-in-30-seconds/"><u>2024 Approved  How to Make Fortnite Thumbnail in 30 Seconds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-to-windows-webcam-conversion-guide-for-windows-11-users/"><u>Android to Windows Webcam Conversion Guide for Windows 11 Users</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-the-ultimate-youtube-editors-handbook-a-step-by-step-journey/"><u>[New] The Ultimate YouTube Editor's Handbook  A Step-by-Step Journey</u></a></li>
<li><a href="https://win11-tips.techidaily.com/audio-troubleshooting-in-obs-studio-on-windows-11-devices/"><u>Audio Troubleshooting in OBS Studio on Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginner-friendly-guide-setting-up-the-jdk-on-windows-11/"><u>Beginner-Friendly Guide: Setting Up the JDK on Windows 11</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-120plus-original-title-concepts-for-unique-and-memorable-snapchat-stories/"><u>[Updated] In 2024, 120+ Original Title Concepts for Unique and Memorable Snapchat Stories</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-the-best-free-mpeg-video-stitching-software/"><u>Updated 2024 Approved The Best Free MPEG Video Stitching Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automate-peaceful-slumber-for-your-w11-gadgets-at-rest/"><u>Automate Peaceful Slumber for Your W11 Gadgets at Rest</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/mastering-instagram-video-streaming-quickness-for-2024/"><u>Mastering Instagram Video Streaming Quickness for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-browser-safety-on-windows-11-with-the-implementation-of-defender-aguard/"><u>Boost Browser Safety on Windows 11 with the Implementation of Defender Aguard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blackview-space-for-storage-sluggishness-sets-in/"><u>Blackview: Space for Storage, Sluggishness Sets In</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-superior-strategies-for-unrestricted-space-allocation/"><u>2024 Approved  Superior Strategies for Unrestricted Space Allocation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-the-deadly-js-error-in-discord-a-quick-guide-for-win-11-users/"><u>Banish the Deadly JS Error in Discord: A Quick Guide for Win 11 Users</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-inside-their-secrets-top-10-youtube-beauty-gurus-you-need-to-see/"><u>[Updated] Inside Their Secrets  Top 10 YouTube Beauty Gurus You Need to See</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/all-you-need-to-know-about-mega-greninja-for-apple-iphone-se-drfone-by-drfone-virtual-ios/"><u>All You Need To Know About Mega Greninja For Apple iPhone SE | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/awaken-your-device-finding-and-fixing-muted-speaker-issues/"><u>Awaken Your Device – Finding & Fixing Muted Speaker Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augment-win11-notepad-with-genius-mentor/"><u>Augment Win11 Notepad with Genius Mentor</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/unlock-social-growth-youtube-links-to-fb-for-2024/"><u>Unlock Social Growth  YouTube Links to FB for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-life360-on-windows-pc-for-infinix-smart-8-hd-drfone-by-drfone-virtual-android/"><u>How to Use Life360 on Windows PC For Infinix Smart 8 HD? | Dr.fone</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-avs-mac-video-editor-create-stunning-videos/"><u>New 2024 Approved AVS Mac Video Editor Create Stunning Videos</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-from-front-to-back-a-step-by-step-guide-to-creating-engaging-angles-in-photography-for-instagram-triumphs/"><u>[New] From Front to Back  A Step-by-Step Guide to Creating Engaging Angles in Photography for Instagram Triumphs</u></a></li>
</ul></div>
