---
title: Adjusting to the Latest Windows 11, Maintain Linux Subsystem Efficiency
date: 2024-07-12T18:08:17.691Z
updated: 2024-07-13T18:08:17.691Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting to the Latest Windows 11, Maintain Linux Subsystem Efficiency
excerpt: This Article Describes Adjusting to the Latest Windows 11, Maintain Linux Subsystem Efficiency
keywords: Win11 Setup Guide,Linux Subsys Optimize,New Windows Features,Enhancing WSL Performance,Windows 11 Migration Tips,Efficient WSL Usage,Maximizing OS Harmony
thumbnail: https://thmb.techidaily.com/2058f819a1d231ffe8fa3c91a4af4cfd3ee338d92aed76fb6bf5194cca7db102.jpg
---

## Adjusting to the Latest Windows 11, Maintain Linux Subsystem Efficiency

 There are several potential reasons why Windows Subsystem for Linux (WSL) stopped working after your PC was upgraded to Windows 11\. Thankfully, the breakdown is unlikely to be terminal, although you might have to try a few different fixes to get it working once again.

 **MUO VIDEO OF THE DAY**

 **SCROLL TO CONTINUE WITH CONTENT**

 Here are several ways to get the Windows Subsystem for Linux working again after upgrading to Windows 11.

## 1\. Check That WSL Is Enabled

 It isn't unusual that upgrading to a newer version of the OS will break some apps and features. So although it might sound obvious, checking WSL hasn't simply been disabled during the upgrade process should be your first step. Here's how to check:

![checking if WSL is enabled in Windows Features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-enabled.jpg)

1. In Windows Search, type**Turn Windows features on or off** and click the search result that should appear at the top.
2. In the Windows System dialog, scroll down until you see**Windows Subsystem for Linux** .
3. If the checkbox for the feature is not selected, do so now. Then click**Ok** .
4. You might also need to restart your computer before checking to see if that fixed the problem.

 Hopefully, WSL is now working, and you can begin using the tool. If not, read on for some other possible solutions.

 Learn more about the [things you can do with WSL and Linux](https://www.makeuseof.com/pros-cons-windows-subsystem-for-linux/) on your Windows computer.

## 2\. Enable Hyper-V and Virtual Machine Platform

 If you want to use a subsystem such as WSL in Windows, you'll also need to enable the virtualization tools. These include Hyper-V and the Virtual Machine Platform.

![Error message in the command line interface](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-feature-missing.jpg)

 If a command line interface opens, telling you a required feature is not installed, when you try to run your Linux distribution, this is likely what it refers to.

1. Search for**Turn Windows features on or off** and click the search result.
2. In Windows Features, scroll down to find**Virtual Machine Platform** and**Windows Hypervisor Platform** .
3. Check the boxes next to each of these features and then click**Ok** .
4. You will need to restart your computer to complete the installation of these tools.

## 3\. Repair the Linux Distribution App

 Your Linux distribution app, such as Ubuntu, Kali, or Debian, could be corrupted or require updating. This can cause WSL to appear to be broken. Repairing Windows apps is very easy.

1. Open**Settings > Apps > App & Features** .
2. Scroll down to the list of your apps to find your Linux distro app.
3. Click the**three dots** to the right of the app name, and select**Advanced options** .  
![Advanced app options in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl.jpg)
4. Click the**Repair** button and follow the on-screen instructions if repairs are necessary.  
![repairing an app in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl-app.jpg)

 Check if WSL is working. If not, try uninstalling and reinstalling the Linux distribution app.

## 4\. Force WSL to Open Using the Microsoft Store

 If WSL is enabled but still refuses to open, you can try forcing launch through the Microsoft Store app. This can sometimes fix temporary glitches when opening WSL directly doesn't work.

1. Open the Microsoft Store app and search for**WSL** .
2. On the store page for WSL, you should see an**Open** button. If the button says**Update** , click it to update the app.  
![opening the WSL app in the Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/force-open-store.jpg)
3. Click the**Open** button, and the default Linux distro app should launch.
4. If a command line interface window opens instead, it will probably tell you a required feature is missing. See**Enable Hyper-V and Virtual Machine Platform** above.

 If forcing WSL to open doesn't work, try the same with the Linux distro app you are using. Open the Store, search for your distro, and click the**Open** button.

## 5\. Uninstall Recent Updates to Fix WSL

 If WSL stopped working after installing an update, the update could be the cause. You can uninstall the most recent update to see if that fixes the problem.

[Uninstalling Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) isn't a complicated process, even if you have never done it before.

 If, after uninstalling the update, WSL still does not work, it is a good idea to reinstall it. Updates can often include security and performance tweaks, so it is generally recommended to keep Windows updated.

## 6\. Check That Malware Isn't Blocking WSL

 The final thing to try to get WSL working is scanning for malware. The potential for malware to prevent Windows Subsystem for Linux from working is low but not unheard of.

 Run a [full scan in Microsoft Defender](https://www.makeuseof.com/easy-ways-boost-security-microsoft-defender-and-windows-10/) or whichever third-party antivirus software you use. Quarantine or remove any malware your antivirus scan finds. Then restart your computer and try using WSL to see if that was the issue.

## Fixing WSL After Upgrading to Windows 11

 Upgrading to Windows 11 usually goes smoothly, but apps and features can occasionally break. If you find that WSL is no longer working after upgrading to the newest Windows OS, don't worry, there is usually an easy fix. You might only need to re-enable the feature in the Windows system settings, but if not, running through the other fixes here will usually solve the problem.


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
<li><a href="https://win11-tips.techidaily.com/adjusting-your-windows-search-and-highlight-settings/"><u>Adjusting Your Window's Search and Highlight Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-privilege-levels-for-non-administrators-on-windows-os/"><u>Altering Privilege Levels for Non-Administrators on Windows OS</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-to-come-up-with-the-best-pokemon-team-on-apple-iphone-xs-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Come up With the Best Pokemon Team On Apple iPhone XS? | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/essential-strategies-for-acquiring-photo-and-video-backdrops/"><u>Essential Strategies for Acquiring Photo & Video Backdrops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/alter-the-default-display-on-task-manager-windows-11/"><u>Alter the Default Display on Task Manager (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/battle-bugs-tackling-skyrims-extension-failure/"><u>Battle Bugs: Tackling Skyrim's Extension Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-with-automated-folder-pairings-in-new-windows-os/"><u>Boost Efficiency with Automated Folder Pairings in New Windows OS</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-exploring-the-essence-of-vimeo-a-leader-in-video-platforms-for-2024/"><u>[Updated] Exploring the Essence of Vimeo  A Leader in Video Platforms for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-aspect-ratio-preferences-on-facebook-vids/"><u>[New] In 2024, Aspect Ratio Preferences on Facebook Vids</u></a></li>
<li><a href="https://extra-information.techidaily.com/amplify-engagement-essential-tips-for-tiktok-unbox-videos/"><u>Amplify Engagement  Essential Tips for TikTok Unbox Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-winerror-740-easy-to-follow-tips-for-windows-users/"><u>Avoiding WinError 740: Easy-to-Follow Tips for Windows Users</u></a></li>
<li><a href="https://fake-location.techidaily.com/wondering-the-best-alternative-to-hola-on-nokia-xr21-here-is-the-answer-drfone-by-drfone-virtual-android/"><u>Wondering the Best Alternative to Hola On Nokia XR21? Here Is the Answer | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-the-past-erasing-defenders-track-of-security-efforts/"><u>Banish the Past: Erasing Defender’s Track of Security Efforts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-windows-fn-key-behavior-for-efficiency/"><u>Altering Windows Fn Key Behavior for Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beyond-code-ai-reshaping-windows-tech-landscape/"><u>Beyond Code: AI Reshaping Windows Tech Landscape</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-default-screen-saver-in-windows-11/"><u>Adjusting Default Screen Saver in Windows 11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-instagram-filter-techniques-for-a-stunning-feed/"><u>[Updated] 2024 Approved  Instagram Filter Techniques for a Stunning Feed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/artificinas-intelligence-microsofts-innovative-ai-addition-to-windows-11-taskbar/"><u>Artificinas Intelligence: Microsoft’s Innovative AI Addition to Windows 11 Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-efficiency-in-win11-with-custom-cmd-commands/"><u>Boosting Efficiency in Win11 with Custom Cmd Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-system-insight-with-elevated-task-manager-access-on-win11/"><u>Boosting System Insight with Elevated Task Manager Access on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/artistry-made-easy-top-7-windows-11-drawing-apps-reviewed/"><u>Artistry Made Easy: Top 7 Windows 11 Drawing Apps Reviewed</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-the-ultimate-playlist-best-sandbox-game-choices/"><u>In 2024, The Ultimate Playlist  Best Sandbox Game Choices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-startup-efficiency-altering-boot-menu-delay/"><u>Boosting Startup Efficiency: Altering Boot Menu Delay</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-want-to-learn-how-to-create-the-random-letter-reveal-intro-read-through-the-stages-of-preparing-this-effect-via-filmora-in-this-guide-for-2024/"><u>Updated Want to Learn How to Create the Random Letter Reveal Intro? Read Through the Stages of Preparing This Effect via Filmora in This Guide for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-beat-fiends-exploring-the-most-popular-rap-songs-on-tiktok/"><u>In 2024, Beat Fiends  Exploring the Most Popular Rap Songs on TikTok</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-performance-by-rebooting-windows-11-ram/"><u>Boost Performance by Rebooting Windows 11 RAM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-guide-to-extend-windows-10-shutdown-duration/"><u>Advanced Guide to Extend Windows 10 Shutdown Duration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-network-settings-a-guide-for-win11/"><u>Adjust Network Settings: A Guide for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-unauthorized-profiles-on-pcs-win1011-guide/"><u>Addressing Unauthorized Profiles on PCs: Win10/11 Guide</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-no-watermark-video-cutting-top-7-free-tools-for-2024/"><u>New No-Watermark Video Cutting Top 7 Free Tools for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/the-complete-guide-to-honor-magic-v2-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>The Complete Guide to Honor Magic V2 FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-file-management-using-checkbox-for-selections-in-win11/"><u>Boost File Management: Using Checkbox for Selections in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-yellow-shade-from-laptop-panels/"><u>Banishing Yellow Shade From Laptop Panels</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/unlock-your-creative-flow-sharing-hundreds-of-photos-and-vids-on-ig-for-2024/"><u>Unlock Your Creative Flow  Sharing Hundreds of Photos and Vids on IG for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-performance-with-these-12-unneeded-windows-programs/"><u>Boost Performance with These 12 Unneeded Windows Programs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/asus-s15-oled-experience-merging-chic-and-versatile-features/"><u>Asus S15 OLED Experience: Merging Chic & Versatile Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/app-aesthetics-the-hidden-culprits-in-windows-11-performance-drop/"><u>App Aesthetics: The Hidden Culprits in Windows 11 Performance Drop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-buffer-rates-to-minimize-lag-with-vlc/"><u>Adjusting Buffer Rates to Minimize Lag with VLC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beat-the-blues-swift-remedies-to-hypervisor-bsos-in-winxose/"><u>Beat the Blues: Swift Remedies to Hypervisor BSOS in WINXOSE</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-how-to-convert-youtube-tracks-to-mp3-safely-the-3-best-ways/"><u>2024 Approved  How To Convert YouTube Tracks to MP3 Safely - The 3 Best Ways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-steam-authentication-setbacks-in-rust-for-windows-users/"><u>Avoiding Steam Authentication Setbacks in Rust for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automate-file-disposal-in-windows-for-efficiency-gains/"><u>Automate File Disposal in Windows for Efficiency Gains</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-cpu-temp-in-windows-11-systems/"><u>Balancing CPU Temp in Windows 11 Systems</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-text-animation-made-easy-top-phone-apps-for-video-editing-for-2024/"><u>New Text Animation Made Easy Top Phone Apps for Video Editing for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-stepping-into-the-spotlight-joining-tiktok-sessions/"><u>[New] Stepping Into the Spotlight  Joining TikTok Sessions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-crashing-keep-your-file-explorer-fixed-in-windows-11/"><u>Avoid Crashing: Keep Your File Explorer Fixed in Windows 11</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-convert-text-to-mp3-on-windows-mac-android-and-iphone/"><u>Updated In 2024, Convert Text to MP3 on Windows, Mac, Android and iPhone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-techniques-for-picture-adjustment-on-windows-11-unveiled/"><u>Advanced Techniques for Picture Adjustment on Windows 11 Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-file-management-in-windows-11/"><u>Boosting File Management in Windows 11</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-master-the-motion-personalized-animation-techniques/"><u>In 2024, Master the Motion  Personalized Animation Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beyond-cortana-microsofts-four-future-plans/"><u>Beyond Cortana: Microsoft's Four Future Plans</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-your-digital-experience-adding-directories-to-taskbar-menu/"><u>Amplify Your Digital Experience: Adding Directories to Taskbar Menu</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-techniques-to-transfer-data-from-honor-80-pro-straight-screen-edition-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Techniques to Transfer Data from Honor 80 Pro Straight Screen Edition to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginning-your-quake-experience-via-terminal/"><u>Beginning Your Quake Experience via Terminal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-frustration-fixing-11s-windows-pin-hiccups/"><u>Avoid Frustration: Fixing 11'S Windows PIN Hiccups</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-quick-assembly-of-stunning-google-collages/"><u>[Updated] Quick Assembly of Stunning Google Collages</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-image-all-screen-website-view/"><u>[Updated] In 2024, Image All-Screen Website View</u></a></li>
</ul></div>
