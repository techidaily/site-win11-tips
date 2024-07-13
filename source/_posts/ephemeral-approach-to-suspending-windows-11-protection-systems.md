---
title: Ephemeral Approach to Suspending Windows 11 Protection Systems
date: 2024-07-12T16:51:05.044Z
updated: 2024-07-13T16:51:05.044Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Ephemeral Approach to Suspending Windows 11 Protection Systems
excerpt: This Article Describes Ephemeral Approach to Suspending Windows 11 Protection Systems
keywords: Windows 11 Safeguard Pause,Short-Lived OS Secure Shutdown,Temporary Security Windows Stoppage,Quick Suspend Windows Defenses,Ephemeral Protection System Halt,Briefly Halting Windows Guard,Transient Safeguard Pause Win11
thumbnail: https://thmb.techidaily.com/ff0e2bc796f68a77c989442115175dff38598efbd629d2e9e9c88ebc255585bb.jpg
---

## Ephemeral Approach to Suspending Windows 11 Protection Systems

 Windows Security is the built-in security app for Windows 11\. You should always keep it enabled as it protects your computer from online and offline threats. However, you may come across situations where you might need to disable it.

 Whether you want to disable it for personal preference or install an app that's facing interference by it, here's how to temporarily disable Windows Security in Windows 11.

## 1\. Temporarily Disable Windows Security Using the Settings App

 The Settings app is the central hub of Windows OS, from where you can manage important system settings. You can use it to personalize your computer, change privacy settings, update Windows, and do much more. It's also one of the places to disable Windows Security on your computer. Here's how:

1. Press the**Win + I** hotkeys to open the**Settings** app.
2. Choose**Privacy & security** from the left sidebar.
3. Click the**Open Windows** **Security** button on the right pane.  
![Open Windows Security option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/open-windows-security.jpg)
4. In the Windows Security app, choose the**Virus & threats protection** option from the left sidebar.
5. Click**Manage settings** under the Virus & threats protection section.
6. Disable the toggle under the**Real-time protection** option.  
![Disabling Real-time protection in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/real-time-protection.jpg)

## 2\. How to Temporarily Disable Windows Security Using the Registry Editor

 Windows Registry is a massive database of important settings and software installed on your computer. You can access and edit that database using a built-in tool called the Registry Editor.

 The Registry Editor can also come in handy in temporarily disabling Windows Security. Here's how to do that:

1. Open the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Windows Security** and press Enter.
3. Select**Virus & threat protection** from the left sidebar.
4. Turn off the toggle under the**Tamper protection** option.  
![Disabling Tamper Protection in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tamper-protection.jpg)
5. Click**Yes** to the UAC that crops up.

 Now it's time to open the Registry Editor. Check out [how to open the Registry Editor on Windows 11](https://www.makeuseof.com/windows-11-open-registry-editor/) for steps on how to do this.

1. When the Registry Editor opens, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows Defender`
2. Right-click on**Windows Defender** in the left sidebar and choose**Permissions.**  
![Permissions option in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/permissions.jpg)
3. Click the**Advanced** options.  
![Advanced option in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced.jpg)
4. Click**Change** next to the**Owner** option.
5. In the**Select User or Group window** , click the**Advanced** button.  
![Advanced option in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced-option.jpg)

1. Click the**Find Now** button and then select the admin account.  
![Find Now option in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/find-now.jpg)
2. Click**OK** \>**OK** to save the changes.
3. Check the **Replace all child object permission entries with inheritable permission entries from this object** box.  
![Replace all child object permission entries with inheritable permission entries from this object box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/replace-all-child-object-permission-entries-with-inheritable-permission-entries-from-this-object.jpg)
4. Click**Apply** \>**OK.**
5. Next, head towards the**Permission for Windows Defender** window, and check the box next to**Full control.**  
![Full control box in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/full-control-box.jpg)
6. Click**Apply** \>**OK.**
7. Right-click on the blank space in the right pane, and create three**DWORD (32-bit) Value** with the following names:  
`DisableAntiVirus  

DisableAntiSpyware  

ServiceStartStates`
8. Double-click on each value, type**1** in**Value data,** and click**OK.**

Restart your computer for the changes to take effect.

## 3\. Temporarily Disable Windows Security Using the Local Group Policy Editor

 Another quick way to temporarily turn off Windows Security is through the Local Group Policy Editor. Here's what you need to do:

1. Open the Run dialog box, type**gpedit.msc** , and click**OK.**
2. In the Local Group Policy Editor, navigate to**Computer Configuration** \>**Administrative Templates** \>**Windows Components** \>**Microsoft Defender Antivirus** .
3. Double-click on the**Turn off Microsoft Defender Antivirus** policy.  
![Microsoft Defender Antivirus policy in LGPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/microsoft-defender-antivirus.jpg)
4. Click**Enabled** .  
![Enabled option in LGPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enabled-option.jpg)
5. Click**Apply** \>**OK.**

 Once your work is done, you can enable Windows Security by choosing**Disabled** for the Turn off Microsoft Defender Antivirus policy.

## 4\. Temporarily Disable Windows Security Using Autoruns

 Autoruns is a Windows utility using which you can turn off the service responsible for starting Windows Security at startup. Before you use Autoruns, disable Tamper Protection by following the steps in method 2.

 Follow the below instructions to disable Windows Security using Autoruns:

1. To begin with,[download Autoruns](https://download.sysinternals.com/files/Autoruns.zip) on your computer.
2. Extract the downloaded file on your computer.
3. Next, boot your computer in safe mode (see [how to boot in safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) ) and then open the extracted Autoruns folder.
4. Double-click on the**Autoruns64** file and then choose**Run** from the prompt that crops up.  
![Run option for Autoruns](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/run-option.jpg)
5. Click**Agree** in the**Autoruns Licence Agreement window** .
6. In the Autoruns window, click**Options** and uncheck**Hide Windows Entries.**  
![Hide Microsoft Entries option in Autoruns](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/hide-microsoft-enteries.jpg)
7. Click**Services.**
8. Uncheck the**WinDefend** box and then close the Autoruns window.  
![Disabling WinDefend in Autoruns](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windefend.jpg)

 Now, to boot in normal mode, open the**System Configuration** window, select**Normal startup,** and then**OK.**

## Stop Windows Security for a Little While on Windows 11

 The new Window Security app ensures you don't have to install a dedicated antivirus program to safeguard your computer. However, the strict policy of Windows Security can sometimes block the installation of third-party apps on your computer. Fortunately, you can disable Windows Security by following the above methods.


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
<li><a href="https://ai-video-tools.techidaily.com/2024-approved-uncovered-top-mac-speech-to-text-apps-you-never-knew-existed-free-and-no-installation/"><u>2024 Approved Uncovered Top Mac Speech-to-Text Apps You Never Knew Existed Free & No Installation</u></a></li>
<li><a href="https://win11.techidaily.com/8-handy-windows-11-and-11-command-shortcuts-you-can-set-up-with-nircmd/"><u>8 Handy Windows 11 & 11 Command Shortcuts You Can Set Up With NirCmd</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-7-steps-to-mend-obs-server-link-error-in-windows/"><u>Navigating 7 Steps to Mend OBS Server Link Error in Windows</u></a></li>
<li><a href="https://extra-resources.techidaily.com/live-yt-sessions-on-phone-for-newbies-without-a-million-viewers/"><u>Live YT Sessions on Phone for Newbies without a Million Viewers</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-rekindling-relics-of-facebook-tales-step-by-device-step-for-2024/"><u>[Updated] Rekindling Relics of Facebook Tales  Step by Device Step for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-microsofts-apppack-and-msibundle-files-to-enhance-productivity/"><u>Integrating Microsoft's Apppack and MsiBundle Files to Enhance Productivity</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-creating-an-audio-visual-harmony-integrating-music-into-videos/"><u>2024 Approved Creating an Audio-Visual Harmony Integrating Music Into Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-windows-terminal-the-unshackled-experience/"><u>Restoring Windows Terminal: The Unshackled Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-exception-handling-breaking-point-solution/"><u>Mastering Windows Exception Handling: Breaking Point Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-into-cmd-mastery-the-20-most-important-commands/"><u>Dive Into CMD Mastery: The 20 Most Important Commands</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-innovative-8-image-collections-for-macbook-screens/"><u>2024 Approved  Innovative 8 Image Collections for MacBook Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/notepads-dark-shift-windows-11-guide/"><u>Notepad's Dark Shift: Windows 11 Guide</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-the-ultimate-guide-to-blurring-faces-in-photos-and-videos-free-resources-for-2024/"><u>Updated The Ultimate Guide to Blurring Faces in Photos and Videos (Free Resources) for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/tips-and-tricks-for-setting-up-your-realme-12plus-5g-phone-pattern-lock-by-drfone-android/"><u>Tips and Tricks for Setting Up your Realme 12+ 5G Phone Pattern Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/finding-windows-11-account-settings-center/"><u>Finding Windows 11 Account Settings Center</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/top-tech-to-freeze-gaming-moments-in-pcmac-screenshots-for-2024/"><u>Top Tech to Freeze Gaming Moments in PC/Mac Screenshots for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-in-2024-15-best-action-cameras/"><u>[Updated] In 2024, 15 Best Action Cameras</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-vidgrabmaster-mobilepc-app-downloads/"><u>[Updated] 2024 Approved  VidGrabMaster  Mobile/PC App Downloads</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-a-step-by-step-guide-for-creating-channel-trailers-that-convert-viewers-into-customers-for-2024/"><u>[Updated] A Step-by-Step Guide for Creating Channel Trailers that Convert Viewers Into Customers for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-ways-to-track-honor-magic-6-lite-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Track Honor Magic 6 Lite without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-thrive-in-free-championship-football-simulator/"><u>How to Thrive in Free Championship Football Simulator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-setup-virtualboxs-security-features-secure-boot-and-tpm/"><u>How to Setup VirtualBox's Security Features: Secure Boot & TPM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerated-unzipping-of-multiple-files-using-windows-tools/"><u>Accelerated Unzipping of Multiple Files Using Windows Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-arp-cache-how-to-empty-it/"><u>Decoding Windows ARP Cache: How to Empty It?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-disrupted-windows-thx-spatial-sound/"><u>Mending Disrupted Windows THX Spatial Sound</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-audiovisual-collection-computer-and-voice-archives/"><u>[New] Audiovisual Collection  Computer & Voice Archives</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-harmonyhook-screen-recordings-a-review/"><u>[Updated] In 2024, HarmonyHook Screen Recordings  A Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/old-hardware-new-horizinas-guiding-windows-11-22h2-installation/"><u>Old Hardware, New Horizinas: Guiding Windows 11 22H2 Installation</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-mp4-video-download-companion-booklet/"><u>[New] In 2024, MP4 Video Download Companion Booklet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-roots-user-permissions-back-to-basics-in-win11/"><u>Restoring Roots: User Permissions Back to Basics in Win11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/pioneering-vr-cycling-choose-wisely-for-2024/"><u>Pioneering VR Cycling  Choose Wisely for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-windows-0x8007007e-error-code/"><u>How to Fix the Windows 0X8007007E Error Code</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-realme-gt-5-pro-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Realme GT 5 Pro to New Android? | Dr.fone</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/master-languages-with-these-brain-toning-techniques/"><u>Master Languages with These Brain-Toning Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-steam-for-seamless-gameplay-on-windows-11-devices/"><u>Realigning Steam for Seamless Gameplay on Windows 11 Devices</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-the-best-free-online-video-flipper-software-and-apps/"><u>2024 Approved The Best Free Online Video Flipper Software and Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-pc-boost-unearthing-windows-best-eight-restart-strategies/"><u>Quick PC Boost: Unearthing Windows' Best Eight Restart Strategies</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-the-ultimate-guide-enabling-autoplay-on-youtube-in-facebook/"><u>2024 Approved  The Ultimate Guide  Enabling Autoplay on Youtube in Facebook</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-advanced-audio-management-for-enhanced-visual-media-consumption-desktop-and-internet-platforms/"><u>2024 Approved Advanced Audio Management for Enhanced Visual Media Consumption (Desktop & Internet Platforms)</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-best-voice-conversion-tools-for-vlogging-professionals/"><u>[Updated] 2024 Approved  Best Voice Conversion Tools for Vlogging Professionals</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-launchpad-essentials-your-first-steps-in-streaming/"><u>[Updated] Launchpad Essentials  Your First Steps in Streaming</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-crafting-perfect-youtube-channel-names-a-comprehensive-guide-for-video-content-creators-maximum-length-156-characters/"><u>[New] 2024 Approved  Crafting Perfect Youtube Channel Names  A Comprehensive Guide for Video Content Creators (Maximum Length  156 Characters)</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-from-disarray-to-artwork-your-collage-journey/"><u>2024 Approved  From Disarray to Artwork  Your Collage Journey</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-the-secrets-of-windows-odbc-settings-panel/"><u>Deciphering the Secrets of Windows' ODBC Settings Panel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-efficient-coding-solutions-with-microsofts-companion/"><u>Crafting Efficient Coding Solutions with Microsoft's Companion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dxgidll-missing-heres-how-win11-can-help/"><u>Dxgi.dll Missing? Here's How Win11 Can Help</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reconnecting-to-spotify-fixing-windows-11-errors/"><u>Reconnecting to Spotify: Fixing Windows 11 Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-control-windows-11-shutdown-with-open-filestasks/"><u>How to Control Windows 11 Shutdown with Open Files/Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-your-pc-restarting-windows-11-apps/"><u>Reviving Your PC: Restarting Windows 11 Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-windows-upgrade-failures-and-errors/"><u>How to Resolve Windows Upgrade Failures and Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-the-integration-of-apple-maps-on-pcs/"><u>Deciphering the Integration of Apple Maps on PCs</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-unlocking-your-sub4sub-potential-the-critical-pre-entry-guide/"><u>[Updated] Unlocking Your Sub4sub Potential  The Critical Pre-Entry Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-domain-services-printer-failures-on-newest-microsoft-os/"><u>Fixing Domain Services Printer Failures on Newest Microsoft OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-blocked-paths-in-windows-update/"><u>Clearing Up Blocked Paths in Windows Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-automate-microsoft-to-do-with-ifttt/"><u>How to Automate Microsoft To Do With IFTTT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-auto-lock-and-screensaver-configurations/"><u>Mastering Auto-Lock & Screensaver Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/image-editing-strategies-remove-unwanted-areas/"><u>Image Editing Strategies: Remove Unwanted Areas</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-art-of-subtle-sonic-softening-using-lumafusion/"><u>The Art of Subtle Sonic Softening Using Lumafusion</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/swiftly-start-sharing-joy-installing-the-ifunny-meme-app/"><u>Swiftly Start Sharing Joy  Installing the iFunny Meme App</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-motorola-moto-g-stylus-5g-2023-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Live Location is Not Updating and How to Fix on your Motorola Moto G Stylus 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-masterclass-identifying-the-best-vocal-effacement-tools-and-programs-for-2024/"><u>New Masterclass Identifying the Best Vocal Effacement Tools and Programs for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-mouse-double-click-3-essential-tips/"><u>Mastering Mouse Double-Click: 3 Essential Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cortana-ends-new-windows-aid-emerges/"><u>Cortana Ends, New Windows Aid Emerges</u></a></li>
<li><a href="https://win11-tips.techidaily.com/introducing-automatic-system-updates-notice-to-windows-11-ui/"><u>Introducing Automatic System Updates Notice to Windows 11 UI</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/rapid-retrieval-for-missed-snaps/"><u>Rapid Retrieval for Missed Snaps</u></a></li>
<li><a href="https://extra-tips.techidaily.com/advancing-your-yi-action-recordings-with-top-accessories/"><u>Advancing Your YI Action Recordings with Top Accessories</u></a></li>
</ul></div>
