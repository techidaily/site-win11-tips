---
title: Addressing Game Bar Errors on Underpowered Systems
date: 2024-08-16T02:02:47.890Z
updated: 2024-08-17T02:02:47.890Z
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## Update Your Graphics Adapter’s Driver

 An outdated or faulty graphics driver might be causing this recording issue on your PC. Try installing the latest graphics driver for your GPU if you haven’t updated it in a while (or ever). This guide tells you [how to update a PC’s graphics driver in Windows](http://www.makeuseof.com/update-graphics-drivers-in-windows-10/).

![The NVIDIA graphics driver download page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/nvidia-driver-download.jpg)
<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Enable the Windows Game Recording and Broadcasting Policy

 Group Policy Editor includes a Game Recording and Broadcasting policy that prevents recording when disabled. So, Windows Pro and Enterprise users must make sure that the Game Recording and Broadcasting policy is set to enabled. Do note that Windows Home doesn’t include the Group Policy Editor.

 Here is how you can enable that policy:

1. [Open Local Group Policy Editor](https://www.makeuseof.com/tag/open-local-group-policy-editor-windows/) and double-click **Computer Configuration** when it appears.
2. Double-click **Administrative Templates** \> **Windows Components**.
3. Select **Windows Game Recording and Broadcasting** in Group Policy’s sidebar.
4. Then double-click on the **Enables or disables Windows Game Recording and Broadcasting** policy.  
![The Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
5. Click **Enabled** if that policy is disabled.
6. Select **Apply** to enable the recording policy and **OK** to close the window.  
![The Enables or disables Windows Game Recording and Broadcasting policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-game-and-recording-policy-window.jpg)
7. Close Group Policy Editor, bring up your Start menu and select **Power** \> **Restart**.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://fox-http.techidaily.com/new-2024-approved-comprehensive-overview-dji-inspire-2/"><u>[New] 2024 Approved  Comprehensive Overview - DJI Inspire 2</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-a-comprehensible-guide-to-adding-images-on-instagram-for-2024/"><u>[New] A Comprehensible Guide to Adding Images on Instagram for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-agrarian-aesthetics-stardew-clones-and-cousins/"><u>[New] Agrarian Aesthetics  Stardew Clones and Cousins</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-attract-more-viewers-crafting-impressive-youtube-description-with-custom-templates/"><u>[New] Attract More Viewers  Crafting Impressive Youtube Description with Custom Templates</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-complete-guide-to-cleaning-up-figma-canvases/"><u>[New] Complete Guide to Cleaning Up Figma Canvases</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-discovering-the-secret-to-instagram-voice-change/"><u>[New] In 2024, Discovering the Secret to Instagram Voice Change</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-quick-glimpse-youtube-shorts-insights/"><u>[New] Quick Glimpse  YouTube Shorts Insights</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-ultimate-video-playback-device-pcmobile-focus/"><u>[New] Ultimate Video Playback Device - PC/Mobile Focus</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-comprehensive-srt-education-and-resources/"><u>[Updated] 2024 Approved  Comprehensive SRT Education and Resources</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-digital-detox-ignoring-negativity-on-youtube-for-2024/"><u>[Updated] Digital Detox  Ignoring Negativity on YouTube for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-in-2024-visionary-vector-top-10-mac-drawing-suites-zero-price/"><u>[Updated] In 2024, Visionary Vector  Top 10 Mac Drawing Suites (Zero Price!)</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-live-stream-audience-analysis-solutions/"><u>[Updated] Live Stream Audience Analysis Solutions</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-platform-power-play-which-one-dominates-vimeo-youtubeplusdailymotion/"><u>[Updated] Platform Power Play  Which One Dominates - Vimeo, YouTube+DailyMotion?</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-update-short-form-video-coverage/"><u>[Updated] Update Short-Form Video Coverage</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-premium-gaming-systems-high-performance-meets-style/"><u>2024 Approved  Premium Gaming Systems  High Performance Meets Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-ways-to-fix-a-reappearing-deleted-file-or-folder-on-windows/"><u>8 Ways to Fix a Reappearing Deleted File or Folder on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-detailed-walkthrough-of-using-system-restore-in-windows-os/"><u>A Detailed Walkthrough of Using System Restore in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-harmony-with-googles-cross-platform-tool/"><u>Achieving Harmony with Google's Cross-Platform Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-clickable-items-in-the-latest-os-update/"><u>Addressing Non-Clickable Items in the Latest OS Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advice-for-avoiding-hidden-displays-during-windows-games/"><u>Advice for Avoiding Hidden Displays During Windows Games</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/or-affluence-enroll-now-in-youtubes-partner-programme-for-2024/"><u>Aim for Affluence  Enroll Now in YouTube's Partner Programme for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-fun-integrating-games-into-windows-11-through-google-play/"><u>Android Fun: Integrating Games Into Windows 11 Through Google Play</u></a></li>
<li><a href="https://win11-tips.techidaily.com/audio-troubleshooting-in-obs-studio-on-windows-11-devices/"><u>Audio Troubleshooting in OBS Studio on Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-clutter-boost-clarity-keeping-your-notifications-centered-in-windows-11/"><u>Avoid Clutter, Boost Clarity: Keeping Your Notifications Centered in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-unwanted-bios-access-during-windows-initialization/"><u>Avoiding Unwanted BIOS Access During Windows Initialization</u></a></li>
<li><a href="https://howto.techidaily.com/best-methods-for-tecno-pova-5-pro-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Best Methods for Tecno Pova 5 Pro Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-windows-11s-missing-wi-fi-functionality/"><u>Boosting Windows 11'S Missing Wi-Fi Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-your-pc-health-top-13-tactics-to-restore-windows/"><u>Boosting Your PC Health: Top 13 Tactics to Restore Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/break-free-from-verifying-glass-cases-in-windows-installation/"><u>Break Free From Verifying Glass Cases in Windows Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-windows-11s-spotify-link-barriers/"><u>Breaking Down Windows 11'S Spotify Link Barriers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-into-high-privilege-windows-command-center/"><u>Breaking Into High-Privilege Windows Command Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-code-how-to-reactivate-memory-feature-in-win11/"><u>Breaking the Code: How to Reactivate Memory Feature in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridge-firewall-gap-enable-chrome-networking-in-windows-os/"><u>Bridge Firewall Gap: Enable Chrome Networking in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-gaps-in-windows-11-sticky-notebook-coordination/"><u>Bridging Gaps in Window's 11 Sticky Notebook Coordination</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-the-gap-between-windows-and-photoshop-open-up-delays/"><u>Bridging the Gap Between Windows and PhotoShop Open-Up Delays</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-more-to-the-table-reimagining-windows-11s-widget-framework/"><u>Bringing More to the Table: Reimagining Windows 11'S Widget Framework</u></a></li>
<li><a href="https://win11-tips.techidaily.com/browser-blackout-blues-efficient-strategies-to-unlock-windows-sites/"><u>Browser Blackout Blues: Efficient Strategies to Unlock Windows Sites</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-windows-download-block-with-opera-tricks/"><u>Bypass Windows Download Block with Opera Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-windows-default-alter-clock-region-on-the-fly/"><u>Bypass Windows' Default: Alter Clock Region On-the-Fly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-access-denied-saving-problems-on-windows/"><u>Bypassing Access Denied Saving Problems on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-audacity-sound-error-in-windows-10-and-11/"><u>Bypassing Audacity Sound Error in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-microsoft-store-lockdown-on-windows-11/"><u>Bypassing Microsoft Store Lockdown on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-the-gloom-bringing-back-daylight-in-windows/"><u>Bypassing The Gloom: Bringing Back Daylight in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-the-not-found-window-error/"><u>Bypassing the Not Found Window Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-user-account-prompts-in-windows/"><u>Bypassing User Account Prompts in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-permission-issues-easily/"><u>Bypassing Windows Permission Issues Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cant-select-or-highlight-text-in-a-pdf-on-windows-heres-how-to-fix-it/"><u>Can't Select or Highlight Text in a PDF on Windows? Here's How to Fix It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/capture-windows-like-a-pro-snip-tool-vs-prtsc-advantages/"><u>Capture Windows Like a Pro: Snip Tool Vs. PrtSc Advantages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/capturing-sound-in-win-11-step-by-step/"><u>Capturing Sound in Win 11 Step-by-Step</u></a></li>
<li><a href="https://extra-information.techidaily.com/carving-out-your-place-in-the-design-world-for-2024/"><u>Carving Out Your Place in the Design World for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/character-map-navigation-in-new-windows-11/"><u>Character Map Navigation in New Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/character-map-unlocked-in-windows-11-edition/"><u>Character Map Unlocked in Windows 11 Edition</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-samsung-galaxy-a05s-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Samsung Galaxy A05s Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/1719579212463-dive-into-hindi-mastery-with-8-compelling-mondly-advantages/"><u>Dive Into Hindi Mastery with 8 Compelling Mondly Advantages!</u></a></li>
<li><a href="https://program-issues.techidaily.com/fixing-launch-errors-for-armored-core-vi-fires-of-rubicon-players-experience/"><u>Fixing Launch Errors for Armored Core VI: Fires of Rubicon Players Experience</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-preserve-precision-4-advanced-screen-recording-for-gamers/"><u>In 2024, Preserve Precision  4 Advanced Screen Recording for Gamers</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-top-platforms-for-amplifying-youtube-content/"><u>In 2024, Top Platforms for Amplifying YouTube Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719360477145-reigniting-your-computers-print-functionality-with-effective-wwin-solutions/"><u>Reigniting Your Computer's Print Functionality with Effective WWin Solutions</u></a></li>
<li><a href="https://games-able.techidaily.com/1719167883005-rekindle-the-joy-classics-reimagined-for-your-device/"><u>Rekindle the Joy: Classics Reimagined for Your Device</u></a></li>
<li><a href="https://extra-information.techidaily.com/selective-blurring-the-modern-editors-guide-for-pcmobile/"><u>Selective Blurring  The Modern Editor's Guide for PC/Mobile</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/tutorial-to-change-oppo-find-n3-flip-imei-without-root-a-comprehensive-guide-by-drfone-android/"><u>Tutorial to Change Oppo Find N3 Flip IMEI without Root A Comprehensive Guide</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/ultimate-audio-guide-to-the-top-5-4k-recording-microphones/"><u>Ultimate Audio Guide to the Top 5 4K Recording Microphones</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-the-ipogo-get-you-banned-and-how-to-solve-it-on-oppo-k11-5g-drfone-by-drfone-virtual-android/"><u>Will the iPogo Get You Banned and How to Solve It On Oppo K11 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719376942389-windows-gptmimicry-a-costless-local-edition-via-gpt4all/"><u>Windows GPTMimicry: A Costless Local Edition via GPT4All.</u></a></li>
</ul></div>
