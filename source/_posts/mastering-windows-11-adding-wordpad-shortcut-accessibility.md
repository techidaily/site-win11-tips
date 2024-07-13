---
title: "Mastering Windows 11: Adding WordPad Shortcut Accessibility"
date: 2024-07-12T17:37:11.470Z
updated: 2024-07-13T17:37:11.470Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Windows 11: Adding WordPad Shortcut Accessibility"
excerpt: "This Article Describes Mastering Windows 11: Adding WordPad Shortcut Accessibility"
keywords: Win11WordpadShortcut,WordPadWinAccess,Win11AddWordpad,WordPadWindows11,Win11TextEditing,AccessibilityWordPad,ShortcutsWin11
thumbnail: https://thmb.techidaily.com/2fabafc66fe8d6c738eceaf2d94bef9969abb79ce6dfc7f79cdd9561a56a5238.jpg
---

## Mastering Windows 11: Adding WordPad Shortcut Accessibility

 Windows' WordPad app is either a limited word processor or an advanced text editor depending on how you look at it. Unlike Notepad, WordPad is a rich text editor that incorporates formatting and styling options for content. Therefore, it is a preferable alternative to Notepad for opening and editing TXT and RTF files.

 As such, you might want to add WordPad shortcuts to Windows 11’s context menu, so you can quickly access WordPad and open TXT/RTF documents with it. This is how you can set up context menu shortcuts for launching WordPad and opening files in it.

## How to Add a WordPad Shortcut to Windows 11’s Context Menu

 To create WordPad shortcuts on the right-click menu, you’ll need to do a bit of manual registry tweaking. The editing required is relatively straightforward, but you can back up the Windows registry beforehand if preferred. See [how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) if you need help.

You can add a basic WordPad shortcut to the context menu like this:

1. Click inside the**Type here to search** box at the top of Windows 11’s Start menu.
2. Type the keyword**regedit** in the search box to open the Registry Editor (see [how to open the Registry Editor for more methods](https://www.makeuseof.com/windows-11-open-registry-editor/) ).
3. Erase the current location from the Registry Editor’s address bar.
4. Enter this shell key location inside the registry address bar and hit**Return** :  
`Computer\HKEY_CLASSES_ROOT\Directory\Background\shell\`
5. Right-click**shell** in the Registry Editor’s sidebar to select a**New** option.

1. Select**Key** to add a new registry key.  
![The New and Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-new-key-options.jpg)
2. Enter**WordPad** in the text box for the new key.
3. Then right-click the new**WordPad** key and select the**New** \>**Key** options again.
4. Input**command** for the subkey’s title.  
![The WordPad key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-command-subkey.jpg)
5. Select the command key in the sidebar, and then double-click its**(Default)** string.
6. Input this path in the**Value** box:  
`"C:\Program Files\Windows NT\Accessories\wordpad.exe"`
7. Click**OK** to save the value, and exit the Registry Editor.  
![An Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/an-edit-string-window2.jpg)

 Now you can open WordPad from the desktop context menu in Windows 11\. Right-click anywhere on the desktop background and select**Show more options** to access the classic menu. Selecting the new**WordPad** option on that menu will open the app’s window.

![The WordPad context menu shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-wordpad-shortcut.jpg)

## How to Add an Open with WordPad Shortcut to Windows 11’s Context Menu

 The basic WordPad shortcut launches the app, but you’ll need to open documents from its**File** tab manually. Instead, you can add a second context menu option for opening files with WordPad. That right-click option will provide a shortcut for opening documents in WordPad directly from File Explorer. This is how to add an**Open with WordPad** option to the context menu:

1. Open Registry Editor as outlined in the first three steps for adding a WordPad shortcut to the context menu.
2. Then clear out the address bar, and input this location path there:  
`HKEY_CLASSES_ROOT\*\shell`
3. Next, click the**shell** key with the right mouse button and select**New** .
4. Click the**Key** option for adding new registry entries.
5. Input**Open with WordPad** for the new key’s title.
6. Right-click**Open with Wordpad** and select**New** \>**Key** to add a subkey.
7. Type**command** in the text box for the subkey.  
![The Open with WordPad key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-with-wordpad-key.jpg)
8. Double-click the**(Default)** string for the new command subkey you just added.
9. Enter**wordpad.exe %1** in the**Value** box, and click**OK** to apply.  
![The wordpad.exe value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-wordpad-exe-value-data.jpg)

 Now you can close the Registry Editor and try out the**Open with WordPad** context menu shortcut. Launch File Explorer (see [how to launch File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) ), and navigate to a folder containing some TXT or RTF files. Right-click an RTF or TXT document and select**Show more options** . Click**Open with WordPad** to bring up the right-clicked document in that app.

## How to Erase the WordPad Context Menu Shortcuts

 If you ever change your mind about having WordPad context menu options, you can remove them by deleting their keys. To do so, you’ll need to open the following key locations in the Registry Editor:

`Computer\HKEY_CLASSES_ROOT\*\shell\Open with WordPad\command  
Computer\HKEY_CLASSES_ROOT\Directory\Background\shell\WordPad\command`

 Then right-click the**Open with WordPad** or**WordPad** key to select a**Delete** option. A dialogue box will open requesting confirmation to erase. Select**Yes** if you’re sure about deleting the key.

![The Delete option for registry keys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-delete-option2.jpg)

## Make the Most of Your WordPad Context Menu Shortcuts

 So, why add Notepad to Windows 11’s context menu when you set up WordPad shortcuts on it instead? Such shortcuts will give you direct access to a somewhat overlooked and underrated advanced text editor that can handle documents with images in them. You can utilize WordPad as a lightweight document viewer for looking at and even editing ODT, DOCX, TXT, and RTF files.

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
<li><a href="https://win11-tips.techidaily.com/accelerate-startup-manipulating-boot-timeout-on-windows-11/"><u>Accelerate Startup: Manipulating Boot Timeout on Windows 11</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/ar-or-augmented-reality-is-one-of-the-most-significant-technological-inventions-this-technology-is-used-in-many-applications-that-we-use-daily-like-maps-mus/"><u>AR, or Augmented Reality, Is One of the Most Significant Technological Inventions. This Technology Is Used in Many Applications that We Use Daily, Like, Maps, Music, Video Games, Tourism, Sightseeing, Etc</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-change-windows-11-administrator-name/"><u>A Comprehensive Guide to Change Windows 11 Administrator Name</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-avoiding-pitfalls-in-sub4sub-key-lessons-from-a-seasoned-guide/"><u>[Updated] Avoiding Pitfalls in Sub4sub  Key Lessons From a Seasoned Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-onedrives-faulty-blob-tag-errors-in-windows/"><u>Addressing OneDrive's Faulty Blob Tag Errors in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-insufficient-installation-privilege-issue-on-win-1011/"><u>Addressing Insufficient Installation Privilege Issue on Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-window-updates-that-left-old-traits-behind/"><u>6 Window Updates That Left Old Traits Behind</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-streamlined-guide-to-resolving-roblox-error-code-262/"><u>A Streamlined Guide to Resolving Roblox Error Code 262</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-absence-of-hypervisor-on-windows-sandbox/"><u>Addressing Absence of Hypervisor on Windows Sandbox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719335028418-stop-early-window-11-edge-tabs-now/"><u>Stop Early Window 11 Edge Tabs Now</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/leveraging-screencastifys-advanced-features-for-2024/"><u>Leveraging Screencastify's Advanced Features for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719343275245-tackle-windows-geforce-failures-head-on-today/"><u>Tackle Windows GeForce Failures Head-On Today!</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-2-ways-to-monitor-apple-iphone-8-plus-activity-drfone-by-drfone-virtual-ios/"><u>In 2024, 2 Ways to Monitor Apple iPhone 8 Plus Activity | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-navigating-the-melody-to-words-top-three-online-tools-for-mp3-conversion-current-trends-for-2024/"><u>Updated Navigating the Melody to Words Top Three Online Tools for MP3 Conversion Current Trends for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719276038972-troubleshoot-silent-pc-audio-solutions-ready/"><u>Troubleshoot Silent PC Audio – Solutions Ready</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-pgsharp-legal-when-you-are-playing-pokemon-on-lava-storm-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Is pgsharp legal when you are playing pokemon On Lava Storm 5G? | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-unlocking-creative-potential-a-deep-dive-into-screenflow-for-mac/"><u>[Updated] 2024 Approved  Unlocking Creative Potential  A Deep Dive Into ScreenFlow for Mac</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-cricket-iphone-se-2022-for-free-by-drfone-ios/"><u>How To Unlock Cricket iPhone SE (2022) for Free</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-in-2024-premium-audiophile-gear-elevating-your-video-streaming-experience/"><u>New In 2024, Premium Audiophile Gear Elevating Your Video Streaming Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719269092202-fixed-windows-shift-key-unreachable/"><u>Fixed: Windows Shift Key Unreachable</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-nvidia-panel-errors-win1110-fixes/"><u>Addressing Nvidia Panel Errors: Win11/10 Fixes</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-2024-approved-crafting-visuals-in-ae-selecting-excellent-plugin-choices/"><u>[New] 2024 Approved  Crafting Visuals in AE  Selecting Excellent Plugin Choices</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-the-ultimate-guide-to-slow-motion-in-windows-live-movie-maker-for-2024/"><u>New The Ultimate Guide to Slow Motion in Windows Live Movie Maker for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-open-the-ease-of-access-center-on-windows/"><u>5 Ways to Open the Ease of Access Center on Windows</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-seamlessly-connect-with-friends-and-family-via-skype-call/"><u>In 2024, Seamlessly Connect with Friends & Family via Skype Call</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-adding-emulators-to-playnite-on-pc/"><u>A Step-by-Step Guide: Adding Emulators to Playnite on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/access-strongest-passwords-effortlessly-with-these-7-free-generators/"><u>Access Strongest Passwords Effortlessly With These 7 Free Generators</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-web-based-video-teaser-creators/"><u>Updated Web-Based Video Teaser Creators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-compelling-arguments-why-windows-11-eclipses-macos/"><u>6 Compelling Arguments Why Windows 11 Eclipses macOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-alternatives-when-bitlocker-isnt-available-on-windows/"><u>5 Alternatives When Bitlocker Isn't Available on Windows</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-unleash-your-creative-potential-top-8-digital-audio-workstations-for-studio-quality-sound-design/"><u>Updated In 2024, Unleash Your Creative Potential Top 8 Digital Audio Workstations for Studio-Quality Sound Design</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-the-ultimate-guide-to-top-reads-popularized-by-booktok-enthusiasts/"><u>2024 Approved  The Ultimate Guide to Top Reads Popularized by BookTok Enthusiasts</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-best-free-webm-players-how-to-play-webm-video-files/"><u>[Updated] Best Free WebM Players  How to Play WebM Video Files?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-storage-with-windows-iscsi-initiator/"><u>Accessing Storage with Windows iSCSI Initiator</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-motorola-moto-e13-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Motorola Moto E13 | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-teach-you-to-transfer-files-from-oppo-find-n3-flip-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways To Teach You To Transfer Files from Oppo Find N3 Flip to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-absence-of-rockalldlldll-windows/"><u>Addressing Absence of Rockalldll.dll (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-walkthrough-to-setting-up-dns-on-windows-11/"><u>A Complete Walkthrough to Setting Up DNS on Windows 11</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/the-ultimate-list-best-royalty-free-laughter-soundtracks-for-your-videos/"><u>The Ultimate List Best Royalty-Free Laughter Soundtracks for Your Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapting-notepad-display-from-light-to-dark-in-win-11-version/"><u>Adapting Notepad Display: From Light to Dark in Win 11 Version</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-gpu-thermal-spikes-during-play/"><u>Addressing GPU Thermal Spikes During Play</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-how-do-beginners-make-a-cool-video-for-youtube-on-mac/"><u>[Updated] 2024 Approved  How Do Beginners Make a Cool Video for YouTube on Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719320045015-clean-and-tailor-your-w11-desktop-now/"><u>Clean & Tailor Your W11 Desktop, Now</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/master-your-media-on-vimeo-with-top-ranked-editors-for-2024/"><u>Master Your Media on Vimeo with Top-Ranked Editors for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-look-at-addressing-error-code-262-on-roblox/"><u>A Comprehensive Look at Addressing Error Code 262 on Roblox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-fix-the-no-such-interface-supported-error-in-windows/"><u>5 Ways to Fix the No Such Interface Supported Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-yuzu-emulation-windows-tips/"><u>Accelerating Yuzu Emulation: Windows Tips</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-from-hd-to-breathtaking-eizos-newest-4k-display/"><u>[Updated] From HD to Breathtaking  EIZO's Newest 4K Display</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/easy-guide-how-to-bypass-vivo-s17-frp-android-10111213-by-drfone-android/"><u>Easy Guide How To Bypass Vivo S17 FRP Android 10/11/12/13</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-playstation-services-hiccup-on-windows/"><u>Addressing PlayStation Services Hiccup on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensible-guide-to-managing-windows-key/"><u>A Comprehensible Guide to Managing Windows Key</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-photos-from-honor-magic-v2-by-fonelab-android-recover-photos/"><u>Possible solutions to restore deleted photos from Honor Magic V2.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-alternative-protection-strategies-for-missing-bitlocker-in-winoss/"><u>5 Alternative Protection Strategies for Missing Bitlocker in WinOSs</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-game-on-video-recording-revolution/"><u>[Updated] Game On  Video Recording Revolution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-windows-subsystem-for-linux-wsl-steps/"><u>Activating Windows Subsystem for Linux (WSL) Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/2024s-best-windows-computers-for-enhanced-productivity/"><u>2024'S Best Windows Computers for Enhanced Productivity</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-perfecting-time-sync-in-video-postings-on-youtube-for-2024/"><u>[New] Perfecting Time Sync in Video Postings on YouTube for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/quick-fixes-for-why-is-my-tecno-spark-20-pro-black-and-white-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Quick Fixes for Why Is My Tecno Spark 20 Pro Black and White | Dr.fone</u></a></li>
</ul></div>
