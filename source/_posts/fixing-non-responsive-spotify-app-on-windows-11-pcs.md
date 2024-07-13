---
title: Fixing Non-Responsive Spotify App on Windows 11 PCs
date: 2024-07-12T17:17:11.604Z
updated: 2024-07-13T17:17:11.604Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Non-Responsive Spotify App on Windows 11 PCs
excerpt: This Article Describes Fixing Non-Responsive Spotify App on Windows 11 PCs
keywords: Responsive Spotify Fix,Win11 Spotify Responsive,Spotify App Responsiveness,Windows 11 Spotify Glitches,Spotify PC Fix Guide,Spotify Update for Win11,Non-Responsive App
thumbnail: https://thmb.techidaily.com/e35b3a5c1a462189bf0e7eb85d4007a41df15f6c2fae50b407ca5b13b61d24c2.jpg
---

## Fixing Non-Responsive Spotify App on Windows 11 PCs

 Spotify is among the foremost music-streaming apps for Windows. However, some users can’t utilize that software because of a “Spotify application is not responding” error. That error message pops up for some users when they try opening the Spotify app on Windows 10 and 11\.

 Spotify doesn’t open when the “application is not responding” error occurs. Although users can’t still utilize Spotify within a browser, that’s not quite the same as the Windows app. This is how you can fix the “Spotify application is not responding” error message on a Windows PC.

## 1\. Terminate Background Spotify Processes in Task Manager

 Ending Spotify background processes is one of the most straightforward and widely confirmed resolutions for the “application is not responding” error. This error often occurs because a Spotify process is still running in the background. So, the first thing you should do is to terminate all Spotify processes you can find in Task Manager like this:

1. Click anywhere on an empty taskbar space with your mouse’s right button to select **Task Manager**.
2. Select **Processes** if Task Manager opens with a different tab.
3. If you can see Spotify in the Apps section, right-click that process and select **End task**.  
![The End task option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/end-task-option.jpg)
4. Go through the background section and disable any Spotify processes you see there by selecting **End task**.
5. Exit the Task Manager tool.
6. Then right-click a Spotify desktop or Start menu shortcut and select **Run as administrator**.

## 2\. Run the Taskkill Command

 Some Spotify users have said they were able to resolve the “application is not responding” error by running a taskkill command. This is a variation of the above resolution for terminating Spotify processes via the Command Prompt. You can run the taskkill command for Spotify as follows:

1. Open the Command Prompt as an administrator (see [how to open the Command Prompt app with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) for help).  
![The Run as administrator Command Prompt option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-as-administrator-option-for-command-prompt.jpg)
2. Input this taskkill command:  
`TASKKILL /F /IM spotify.exe`  
![The taskkill command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/taskkill-command.jpg)
3. Press **Enter** to execute the taskill command.

## 3\. Delete the Spotify User Data Folder

 Deleting a -user subfolder within the Spotify data folder is another user-confirmed method for fixing the “Spotify application is not responding” error. Erasing that subfolder will delete the Spotify desktop app’s cached data for songs and login details. This is how you can delete the -user data folder in Windows:

1. Open Run by pressing that app’s **Win + R** key combo.
2. Type **%appdata%** in Run’s **Open** box and press **Enter** to view a Roaming folder.
3. Click the Spotify folder.
4. Open the users subfolder within the Spotify directory.  
![The -user folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/user-folder.jpg)
5. Right-click on the -user folder with random characters within its directory title and select **Delete**.
6. Try opening Spotify again.

 A variation of this potential resolution is to erase a specific Spotify cache file. To do so, you’ll need to open the -user folder. Then right-click the **local-files.bnk** file and select **Delete**.

 If you’re utilizing the UWP app, select the **Reset** option to clear Spotify’s cached data. You can click that **Reset** option within the Apps & Features section of the Windows Settings app. Our guide tells you [how to reset Windows apps](https://www.makeuseof.com/windows-reset-app/).

## 4\. Repair the Spotify App

 Users with the UWP Spotify app can also try selecting a **Repair** option. The **Repair** option is available for fixing Microsoft Store apps that aren’t working right. You can select that troubleshooting option for Spotify just below that app’s **Reset** button from its advanced options within the Apps & Features tool.

![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/apps-and-features.jpg)

## 5\. Check That Spotify Is Allowed Through the Windows Firewall

 A firewall block is another potential cause for the “Spotify application is not responding” error. To address this possible cause, open Windows Defender Firewall’s allowed app settings and select the **Public** and **Private** checkboxes for the Spotify app. Our guide for [allowing apps through Windows Defender Firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) includes full instructions for applying this resolution.

![The Windows Defender Firewall applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-defender-firewall.jpg)

 Many third-party security apps also have firewall components that can feasibly cause the “Spotify application is not responding” error much the same as WDF. If your PC has third-party security software installed, try allowing Spotify through that app’s firewall. Look for firewall exception options in the software’s settings tabs and select to permit Spotify through it.

## 6\. Disable Third-Party Security Software Installed

 Third-party security software packages also have antivirus shields that can cause app startup issues. So, try disabling the antivirus component of any third-party security app installed before running Spotify. This can usually be done by right-clicking the system tray icon of an antivirus tool and selecting a disable or turn-off setting for temporarily deactivating the shield.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 If that works, don’t leave the antivirus shield disabled. Instead, add Spotify to the antivirus software’s scanning exclusion list. Go through the app’s setting tabs to find its antivirus exclusion options.

## 7\. Reinstall the Spotify App

 Finally, reinstall your Spotify software if the “application is not responding” error persists after applying all the alternative resolutions above. That’s probably the best way to fix other Spotify bugs or corrupted files causing the error. You can uninstall Spotify with the Apps & Features Settings tool, which is one of the methods in our guide to [removing Windows software](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/).

![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/apps-and-features.jpg)

 We also recommend that you eradicate leftover Spotify data before reinstalling. To do so, delete the Spotify data folder at this directory path:

`C:\Users\<user name>\AppData\Roaming\Spotify`

 Or you could utilize a third-party uninstaller to remove Spotify. Software packages like IObit Uninstaller and Advanced Uninstaller Pro are freely available and will eradicate Spotify’s leftover data and registry entries. Check out our article about the [best Windows third-party uninstaller software](https://www.makeuseof.com/windows-11-uninstallers-stubborn-apps/) for further details.

![The IObit Uninstaller software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/iobit-uninstaller-1.jpg)

 Then you can reinstall either the UWP or the desktop Spotify app. Click **Download** on the [Spotify Windows download page](https://www.spotify.com/us/download/windows/) to get the setup wizard for the desktop software. Then you’ll need to double-click the **SpotifySet.exe** file to install the desktop software.

 If you prefer the UWP Spotify app version, open this [Microsoft Store page](https://apps.microsoft.com/store/detail/spotify-music-and-podcasts/9NCBCSZSJRSB). Press the **Get in Store** app button on the Spotify page. Next, select **Open Microsoft Store** on the dialog box that prompts you to install the app from there. Click on Spotify’s **Get** button to both download and install that app.

![The Get option for the Spotify UWP app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/get-option-for-spotify.jpg)

## Get Back in the Groove With Your Spotify Windows App

 Those potential solutions will probably kick-start Spotify when the “Spotify application is not responding” stops it from starting. They’re worth a try since they’ve worked for many other Spotify users. Then you can listen to all your favorite albums with the Spotify Windows app again.

 Spotify doesn’t open when the “application is not responding” error occurs. Although users can’t still utilize Spotify within a browser, that’s not quite the same as the Windows app. This is how you can fix the “Spotify application is not responding” error message on a Windows PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/whats-the-difference-between-the-c-drive-and-the-d-drive/"><u>What's the Difference Between the C: Drive and the D: Drive?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-dynamic-system-health-enhancement/"><u>Windows' Dynamic System Health Enhancement</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-expert-advice-on-free-youtube-events-without-extra-cost/"><u>In 2024, Expert Advice on Free Youtube Events without Extra Cost</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/what-does-jailbreaking-iphone-12-pro-max-i-do-get-answers-here-drfone-by-drfone-ios/"><u>What Does Jailbreaking iPhone 12 Pro Max i Do? Get Answers here | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-movecopy-tasks-to-windows-explorers-context-menu/"><u>Adding Move/Copy Tasks to Windows Explorer's Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/momentum-builds-with-windows-11s-upcoming-feature-unveil/"><u>Momentum Builds with Windows 11’S Upcoming Feature Unveil</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensure-non-crashy-windows-user-experience/"><u>Ensure Non-Crashy Windows User Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-windows-11-camera-app-f429f-hiccup/"><u>How to Rectify Windows 11 Camera App F429F Hiccup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-sound-control-with-windows-11-volume-tools/"><u>Mastering Sound Control with Windows 11 Volume Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-additional-views-in-win-11s-context-menu/"><u>Eliminating Additional Views in Win 11'S Context Menu</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-accelerating-your-watch-experience-on-instagram-videos/"><u>In 2024, Accelerating Your Watch Experience on Instagram Videos</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-the-quick-fix-guide-to-instagram-popularity-accelerate-your-visibility-with-15-tricks-of-the-trade-for-2024/"><u>[Updated] The Quick-Fix Guide to Instagram Popularity  Accelerate Your Visibility with 15 Tricks of the Trade for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-a-modern-interface-in-retro-machines-guide-to-windows-11-to-go-and-rufus/"><u>Crafting a Modern Interface in Retro Machines - Guide to Windows 11, To Go & Rufus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-window-11-search-expertise-with-these-tricks/"><u>Elevate Your Window 11 Search Expertise With These Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/folders-and-files-in-the-spotlight-6-access-techniques/"><u>Folders and Files in the Spotlight: 6 Access Techniques</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-get-the-most-out-of-your-gopro-mac-video-editing-essentials-for-2024/"><u>Updated Get the Most Out of Your GoPro Mac Video Editing Essentials for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/charting-your-course-through-cortana-history-windows/"><u>Charting Your Course Through Cortana History (Windows)</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-in-2024-mastering-audio-removing-vocals-from-video-like-a-pro/"><u>New In 2024, Mastering Audio Removing Vocals From Video Like A Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-4-strategies-for-mac-address-extraction-in-windows-11/"><u>Exploring 4 Strategies for MAC Address Extraction in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-8-ways-to-iis-explorer/"><u>A Step-by-Step Approach: 8 Ways to IIS Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-conjoin-windows-serial-numbers-and-microsoft-accounting/"><u>How to Conjoin Windows Serial Numbers & MICROSOFT ACCOUNTING</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-seamless-integration-of-snaps-in-zoom-virtual-meetings/"><u>2024 Approved  Seamless Integration of Snaps in Zoom Virtual Meetings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-side-by-side-error-corrective-techniques-for-win10/"><u>Addressing Side-by-Side Error: Corrective Techniques for Win10</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-the-ultimate-selection-of-6-pioneering-instagram-reel-apps/"><u>[New] In 2024, The Ultimate Selection of 6 Pioneering Instagram Reel Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-user-access-regulation-for-everyday-windows-pcs/"><u>Mastering User Access Regulation for Everyday Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/velocity-validation-precise-windows-steps-to-assess-internet-router-performance/"><u>Velocity Validation: Precise Windows Steps to Assess Internet Router Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/empower-your-windows-network-with-python-driven-transfers/"><u>Empower Your Windows Network with Python-Driven Transfers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-youtube-playback-speed-delays-in-chrome/"><u>Fixing YouTube Playback Speed Delays in Chrome</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-voice-transformation-on-the-move-best-audio-modification-tools-for-smartphones/"><u>[Updated] In 2024, Voice Transformation on the Move  Best Audio Modification Tools for Smartphones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixes-for-unopenable-windows-folders-click-doubled-down/"><u>Fixes for Unopenable Windows Folders, Click-Doubled Down</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-building-brands-on-the-buzzing-platform-of-instagram-marketing/"><u>[New] Building Brands on the Buzzing Platform of Instagram Marketing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-blank-monitor-during-windows-launch/"><u>Fixing Blank Monitor During Windows Launch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-guide-to-troubleshooting-the-windows-camera-app/"><u>A Complete Guide to Troubleshooting the Windows Camera App</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-best-camera-apps-to-record-stunning-slow-movement-photos-iphoneandroid/"><u>[Updated] Best Camera Apps to Record Stunning Slow Movement Photos iPhone/Android</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-deciphering-the-advantages-of-modern-multicam-technology/"><u>In 2024, Deciphering the Advantages of Modern Multicam Technology</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-microsoft-office-error-0x80041015-a-fix-guide/"><u>Conquering Microsoft Office Error 0X80041015: A Fix Guide</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-industrys-choice-our-miniature-dvd-players-guide/"><u>[Updated] In 2024, Industry's Choice  Our Miniature DVD Players Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/wsls-impact-on-linux-desktop-usage/"><u>WSL's Impact on Linux Desktop Usage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-password-safety-tools-for-windows-11-users/"><u>Winning Password Safety Tools for Windows 11 Users</u></a></li>
<li><a href="https://extra-tips.techidaily.com/delve-into-the-art-of-text-animation-14-stunning-examples/"><u>Delve Into the Art of Text Animation  14 Stunning Examples</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-4-sim-location-trackers-to-easily-find-your-lost-samsung-galaxy-m14-5g-device-by-drfone-android/"><u>In 2024, Top 4 SIM Location Trackers To Easily Find Your Lost Samsung Galaxy M14 5G Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-breakdown-windows-saver-dynamics/"><u>Expert Breakdown: Windows Saver Dynamics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-unrealcefsubprocess-high-cpu-and-ram-usage-on-windows/"><u>How to Fix the UnrealCEFSubprocess High CPU and RAM Usage on Windows</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-leapfrog-content-management-from-youtube-to-dailymotion-effortlessly/"><u>In 2024, Leapfrog Content Management  From YouTube to Dailymotion Effortlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-the-power-of-hyper-v-in-windows-11-homes-with-this-guide/"><u>Unleash the Power of Hyper-V in Windows 11 Homes with This Guide</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/reverse-rewind-repeat-mastering-video-reversal-in-final-cut-pro-for-2024/"><u>Reverse, Rewind, Repeat Mastering Video Reversal in Final Cut Pro for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/curing-obscured-network-visibility-in-windows/"><u>Curing Obscured Network Visibility in Windows</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-next-gen-streaming-prosperity-for-gamers/"><u>2024 Approved  Next-Gen Streaming Prosperity for Gamers</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-maximizing-your-income-potential-on-instagram/"><u>[New] 2024 Approved  Maximizing Your Income Potential on Instagram</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-youtubes-glamour-guild-comprehensive-style-compendium/"><u>[New] 2024 Approved  Youtube's Glamour Guild  Comprehensive Style Compendium</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-registry-editor-access-control-in-win11/"><u>Mastering Registry Editor Access Control in Win11</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/crafting-prime-tiktok-openings-using-macos/"><u>Crafting Prime TikTok Openings Using MacOS</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-what-this-post-can-teach-you-about-clay-animation/"><u>Updated What This Post Can Teach You About Clay Animation</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-navigate-browser-black-screens-with-ease/"><u>[Updated] Navigate Browser Black Screens with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-you-through-lost-ethernet-connection-fixes/"><u>Guiding You Through Lost Ethernet Connection Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-your-assault-fixing-lags-for-pc-warriors/"><u>Ace Your Assault: Fixing Lags for PC Warriors</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-populate-play-button-visuals-incorporating-electrodes/"><u>2024 Approved  Populate Play Button Visuals  Incorporating Electrodes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-choose-and-set-your-favorite-command-prompt/"><u>How to Choose and Set Your Favorite Command Prompt</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-videos-from-your-lava-blaze-2-5g-by-fonelab-android-recover-video/"><u>How to recover old videos from your Lava Blaze 2 5G</u></a></li>
<li><a href="https://howto.techidaily.com/7-fixes-for-unfortunately-phone-has-stopped-on-lava-yuva-3-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Fixes for Unfortunately, Phone Has Stopped on Lava Yuva 3 | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-remove-the-lock-screen-fingerprint-of-your-vivo-y77t-by-drfone-android/"><u>In 2024, Remove the Lock Screen Fingerprint Of Your Vivo Y77t</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-guide-to-adding-creative-closure-in-vimeo-videos/"><u>In 2024, Guide to Adding Creative Closure in Vimeo Videos</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-how-to-locate-horrific-noise-profiles-for-filmmaking/"><u>New How to Locate Horrific Noise Profiles for Filmmaking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/copilot-disappearance-in-ws11-quick-fixes-guide/"><u>Copilot Disappearance in WS11: Quick Fixes Guide</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-critical-asmr-video-elements-to-note/"><u>[Updated] In 2024, Critical ASMR Video Elements to Note</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-sculpting-success-in-visual-communications/"><u>[New] 2024 Approved  Sculpting Success in Visual Communications</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-in-2024-s-top-rated-mp4-to-mp3-converter-apps-for-smartphone-users/"><u>Updated In 2024, S Top-Rated MP4 to MP3 Converter Apps for Smartphone Users</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/unmatched-tools-apart-from-obs-for-broadcasting-for-2024/"><u>Unmatched Tools Apart From OBS for Broadcasting for 2024</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-ultimate-guide-to-catch-the-regional-located-pokemon-for-apple-iphone-se-2020-drfone-by-drfone-virtual-ios/"><u>In 2024, Ultimate Guide to Catch the Regional-Located Pokemon For Apple iPhone SE (2020) | Dr.fone</u></a></li>
</ul></div>
