---
title: Customizing How Clock/Date Shows in Window 11
date: 2024-07-12T17:29:35.778Z
updated: 2024-07-13T17:29:35.778Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Customizing How Clock/Date Shows in Window 11
excerpt: This Article Describes Customizing How Clock/Date Shows in Window 11
keywords: Windows Clock Personalization,Set Date Display Mode,Customize Time Format,Adjust Window 11 Time,Clock Appearance Control,Windows 11 Date Settings,Time Display Preferences
thumbnail: https://thmb.techidaily.com/96ca9c739207d23d042e7f8016b381f18f2564ff73ddf98034c5d696bcc3f7e9.jpg
---

## Customizing How Clock/Date Shows in Window 11

 The system tray clock on the right side of the Windows taskbar shows the date and time. While most users find this information useful, others might consider it a source of distraction.

 As such, if you want to hide the clock and date from the taskbar, then this is the place where you need to be. We'll share three different ways by which you can configure the taskbar to hide or show the clock and date.

## 1\. Hide or Show the Clock and Date from the Taskbar by Using Windows System Settings

 The System Settings is the central hub of a Windows PC. You can use it to update Windows, manage privacy settings,[customize the taskbar](https://www.makeuseof.com/windows-11-customize-taskbar/) , and more.

 It's also one of the places from where you can configure the taskbar to hide or show the clock and date. You can do this by following the below instructions:

 This method only works for Windows 10\. If you are using Windows 11, you can try any other method in this article.

1. Open the**Settings** menu by pressing the**Win + I** hotkeys.
2. Choose the**Personalization** option.
3. Select**Taskbar** from the left panel.
4. Scroll down and click the**Turn system icon on or off** option under the**Notification** area.  
![Turn system icons on or off option in Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-system-icons-on-or-off.png)
5. In the new window that crops up, disable the toggle next to**Clock.**  
![Disable the Clock in System Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-clock.png)

 That's it. You've disabled the clock and date from the taskbar.

 To enable them again, head towards the above settings again and enable the toggle.

## 2\. Hide or Show the Clock and Date from the Taskbar by Using the Local Group Policy Editor

 The next utility that will help you hide or show the clock and date from the taskbar is the Local Group Policy Editor. You can use this utility to manage Windows features, sign-in and shutdown processes, and more.

 The Local Group Policy Editor is disabled by default in the Windows Home edition. To enable it, check out our guide on how to [access the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 Nevertheless, here's how to use Local Group Policy Editor to configure the taskbar to hide the clock and date.

1. Open the Run dialog box, type**gpedit.msc,** and press Enter.
2. In the Local Group Policy Editor, select the**Administrative Templates** folder under**User configuration.**
3. Click the**Start Menu and Taskbar** folder.
4. Click the**Setting** option in the right pane.
5. Search for and right-click on the**Remove Clock from the system notification area** policy. Then, choose**Edit** from the context menu.
6. In the policy edit window, choose the**Enabled** option.  
![Disabling Clock and Date using the local group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disabling-clock-and-date.jpg)
7. Click**Apply** \>**OK** to save the changes.

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

## 3\. Hide or Show the Clock and Date from the Taskbar Using the Registry Editor

 The [Registry Editor](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is an extensive database of your Windows operating system configuration settings. You can use it to navigate the registry and edit its keys.

 Here's how to use the Registry Editor to hide the clock and date from the taskbar:

1. In the Run dialog box, type**regedit** and click**OK.** It'll [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Navigate to the following location:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies`
3. Right-click on the**Policies** key in the left panel, choose**New,** and then select**Key.**
4. Name the key**Explorer** and press Enter.  
![Creating new key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/creating-new-key.jpg)
5. In the Explorer key, right-click on the blank space, and choose**New** \>**DWORD (32-bit Value)** .
6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

## Remove Any Distraction from the Taskbar

 The system tray clock helps you to keep track of the date and time. But if it has become a distraction or you want to keep the taskbar clean, you can use either of the above methods to configure the taskbar to hide the clock and date.


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
<li><a href="https://audio-shaping.techidaily.com/updated-the-ultimate-list-of-mobile-audio-augmentation-tools-iosandroid-2023-edition/"><u>Updated The Ultimate List of Mobile Audio Augmentation Tools (iOS/Android, 2023 Edition)</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-card-on-itel-s23-online-without-jailbreak-by-drfone-android/"><u>How to Unlock SIM Card on Itel S23 online without jailbreak</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-effortless-access-top-5-chrome-addons-for-quickly-download-facebook-vids/"><u>[New] 2024 Approved  Effortless Access  Top 5 Chrome Addons for Quickly Download Facebook Vids</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/through-eyes-unseen-an-essential-vr-chronology/"><u>Through Eyes Unseen  An Essential VR Chronology</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/dive-into-instagram-live-without-hesitation-for-2024/"><u>Dive Into Instagram Live Without Hesitation for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-cutting-the-fat-in-windows-11/"><u>The Ultimate Guide to Cutting the Fat in Windows 11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-unlocking-seamless-linktree-addition-in-your-tiktok-profile/"><u>In 2024, Unlocking Seamless Linktree Addition in Your TikTok Profile</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-windows-multiscreen-woes/"><u>Understanding Windows Multiscreen Woes</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-playlist-passport-traveling-tunes-throughout-platforms/"><u>In 2024, Playlist Passport  Traveling Tunes Throughout Platforms</u></a></li>
<li><a href="https://extra-information.techidaily.com/fast-forwarding-or-reverse-mastering-netflix-frame-control/"><u>Fast-Forwarding or Reverse  Mastering Netflix Frame Control</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-winterminals-bg-pic/"><u>Setting WinTerminal's Bg Pic</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-ultimate-no-fuss-techniques-for-valorant-sessions/"><u>In 2024, Ultimate No-Fuss Techniques for Valorant Sessions</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-unlock-icloud-lock-from-your-iphone-xs-and-ipad-by-drfone-ios/"><u>How to Unlock iCloud lock from your iPhone XS and iPad?</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-are-there-legal-constraints-in-capturing-online-video-screenshots/"><u>[New] 2024 Approved  Are There Legal Constraints in Capturing Online Video Screenshots?</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-in-depth-look-10-must-have-terraria-mods/"><u>[Updated] 2024 Approved  In-Depth Look  10 Must-Have Terraria Mods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-0x800704cf-error-in-win11-marketplace/"><u>Overcoming 0X800704CF Error in Win11 Marketplace</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-from-novice-to-pro-a-comprehensive-guide-to-using-audacity-on-a-mac/"><u>[Updated] 2024 Approved  From Novice to Pro  A Comprehensive Guide to Using Audacity on a Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-running-sfc-on-windows/"><u>Understanding and Running SFC on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-user-access-regulation-for-everyday-windows-pcs/"><u>Mastering User Access Regulation for Everyday Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-tip-how-to-turn-off-nvidia-ui/"><u>Tech Tip: How to Turn Off NVIDIA UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swivel-your-snaps-with-these-6-steps-for-windows-11-users/"><u>Swivel Your Snaps with These 6 Steps for Windows 11 Users</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-strategies-for-identifying-lowest-cloud-data-rates/"><u>2024 Approved  Strategies for Identifying Lowest Cloud Data Rates</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-in-2024-vhs-on-the-go-best-mobile-apps-for-vintage-video-lovers/"><u>New In 2024, VHS on the Go Best Mobile Apps for Vintage Video Lovers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-winget-in-windows-11-environments/"><u>Reactivating Winget in Windows 11 Environments</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-unveiling-modernity-discover-these-top-10-digital-realms-for-artistic-font-styles/"><u>[Updated] 2024 Approved  Unveiling Modernity  Discover These Top 10 Digital Realms for Artistic Font Styles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-sound-control-with-windows-11-volume-tools/"><u>Mastering Sound Control with Windows 11 Volume Tools</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-change-your-iphone-se-2022-apple-id-on-macbook-by-drfone-ios/"><u>How To Change Your iPhone SE (2022) Apple ID on MacBook</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/chaptered-videos-on-vimeo-a-comprehensible-guide-for-2024/"><u>Chaptered Videos on Vimeo  A Comprehensible Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-onedrive-errors-on-windows-effective-fixes/"><u>Tackling OneDrive Errors on Windows: Effective Fixes</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-iphones-and-light-creating-impactful-silhouettes/"><u>[New] IPhones and Light  Creating Impactful Silhouettes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revealing-the-hidden-search-bar-in-win11s-task-manager/"><u>Revealing the Hidden Search Bar in Win11's Task Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-windows-11-camera-app-f429f-hiccup/"><u>How to Rectify Windows 11 Camera App F429F Hiccup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-engineering-the-taskbar-key-steps-to-better-windows-11-ux/"><u>Re-Engineering the Taskbar: Key Steps to Better Windows 11 UX</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-mobile-mastery-best-video-editing-apps-for-ios-and-android/"><u>Updated 2024 Approved Mobile Mastery Best Video Editing Apps for iOS and Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-banishing-the-persistent-pink-error-on-windows/"><u>The Ultimate Guide to Banishing the Persistent Pink Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-the-role-of-windows-print-management-interface/"><u>Understanding the Role of Windows Print Management Interface</u></a></li>
<li><a href="https://extra-hints.techidaily.com/mastering-instagram-reels-incorporating-tracks-seamlessly/"><u>Mastering Instagram Reels  Incorporating Tracks Seamlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-roblox-error-262-instantly/"><u>Overcoming Roblox Error 262 Instantly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/momentum-builds-with-windows-11s-upcoming-feature-unveil/"><u>Momentum Builds with Windows 11’S Upcoming Feature Unveil</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-hasty-guide-from-raw-images-to-high-quality-youtube-thumbnail-art/"><u>[New] Hasty Guide  From Raw Images to High-Quality YouTube Thumbnail Art</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-create-stunning-videos-from-images-10-top-online-makers-for-2024/"><u>New Create Stunning Videos From Images 10 Top Online Makers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinvigorating-faulty-troubleshooters-in-windows-os/"><u>Reinvigorating Faulty Troubleshooters in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-registry-editor-access-control-in-win11/"><u>Mastering Registry Editor Access Control in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-your-windows-11-defense-enhanced-filter-options-via-context-menu/"><u>Upgrade Your Windows 11 Defense: Enhanced Filter Options via Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-hyper-v-setup-process-for-windows-11-home-edition/"><u>Navigating the Hyper-V Setup Process for Windows 11 Home Edition</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-ultimate-guide-to-premium-hd-screen-capture-gear/"><u>[New] In 2024, Ultimate Guide to Premium HD Screen Capture Gear</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-premium-dj-visuals-library-seamless-download-experience/"><u>[New] In 2024, Premium DJ Visuals Library - Seamless Download Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-steam-library-accessibility-on-win-11-pcs/"><u>Troubleshooting Steam Library Accessibility on Win 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-blocking-self-starting-windows-store/"><u>Strategies for Blocking Self-Starting Windows Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-mouse-response-time-on-windows-devices/"><u>Optimizing Mouse Response Time on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-windows-headset-microphone-blockage/"><u>Unblocking Windows Headset Microphone Blockage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrecting-your-muted-windows-start-button-icon/"><u>Resurrecting Your Muted Windows Start Button Icon</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-fcpx-error-fixing-mastery-top-tips-and-tricks-for-smooth-editing/"><u>Updated 2024 Approved FCPX Error-Fixing Mastery Top Tips and Tricks for Smooth Editing</u></a></li>
</ul></div>
