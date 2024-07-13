---
title: Efficient Ways to Delete Email From Windows Sign-In Screen
date: 2024-07-12T16:32:22.330Z
updated: 2024-07-13T16:32:22.330Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Efficient Ways to Delete Email From Windows Sign-In Screen
excerpt: This Article Describes Efficient Ways to Delete Email From Windows Sign-In Screen
keywords: Sign-In Screen Cleanup,Email Removal Tips,Deleting Windows Emails,Quick Email Disabling,Contact Panel Purge,Simplify Inbox Clutter,Remove Emails Fast
thumbnail: https://thmb.techidaily.com/8d42a5be41c7b4a2ee5933ca8170ed38361404ba710cadb2872cd630ac7e122c.jpg
---

## Efficient Ways to Delete Email From Windows Sign-In Screen

 If you frequently use your computer in public places, it's a good idea to remove your email address from the Windows login screen. This means people can't get your email address if they see your screen over your shoulder.

 You can accomplish this using the Settings app, Group Policy Editor, or Registry Editor. In this post, we've covered all these methods in detail.

## 1\. How to Hide Email Address From Windows Login Screen Using the Settings App

 The Windows Settings app provides a quick way to hide account information from the login screen. So, if you are in a rush, use the following steps to remove user email addresses from the Windows login screen.

1. Press**Win + I** or use one of the [many ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Accounts > Sign-in options** .
3. Under**Additional settings** , toggle off the switch next to **Show account details such as my email address on the sign-in screen** .  
![Hide Email From Windows Login Screen Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-settings-app.jpg)

## 2\. How to Hide Email Address From Windows Login Screen Using the Group Policy Editor

 The Group Policy Editor (or gpedit.msc) is a handy Windows tool for configuring advanced system settings. You can also this tool to hide your email address from the Windows login screen.

 Note that the Group Policy Editor is only available on Windows Professional, Education, and Enterprise editions. If your PC is running Windows Home, check out [how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

1. Press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the search box and select the first result that appears.
3. Use the left pane to navigate to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options** .
4. Double-click the **Interactive Logon: Display user information when the session is locked** policy on your right.
5. In the properties window, click the drop-down menu to select the**Do not display user information** option.
6. Click**Apply** followed by**OK** .  
![Hide Email From Windows Login Screen Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-group-policy-editor.jpg)
7. Next, double-click on the**Interactive logon: Do not display last user name** policy from the same section.
8. Select**Enabled** in the properties window.
9. Click**Apply** followed by**OK** to save changes.

## 3\. How to Hide Email Address From Windows Login Screen Using the Registry Editor

 If the above two methods don’t work for some reason, you can make changes to the Windows registry files to hide your email address from the login screen. For that, you’ll need to use the Registry Editor on Windows.

 When it comes to editing Registry files, it's important to be cautious as making incorrect changes can cause irreversible damage to your PC. We recommend you either back up all the registry files or create a restore point before you make any changes. If you need help with that, check our guides on [how to back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [how to create a restore point in Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

 Once you’re done with that, use the following steps to hide your email address from the Windows login screen via Registry Editor.

1. Press**Win + X** to open the Power User menu and select**Run** from the list.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows > System** .
5. Right-click on the**System** key and select**New > DWORD (32-bit) Value** .
6. Rename the DWORD to**BlockUserFromShowingAccountDetailsOnSignin** .
7. Double-click on the newly created DWORD and enter**1** in the**Value data** field. Then, click**OK** .  
![Hide Email From Windows Login Screen Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-registry-editor.jpg)

 Exit the Registry Editor and restart your PC for the changes to take effect.

## Hiding Your Email Address From the Windows Login Screen Is Easy

 As we just saw, hiding your personal information from the Windows login screen barely takes a couple of minutes, regardless of the method you employ.


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
<li><a href="https://extra-lessons.techidaily.com/skills-for-photo-manipulation-mastery/"><u>Skills for Photo Manipulation Mastery</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/enhancing-photos-with-chronological-details/"><u>Enhancing Photos with Chronological Details</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrecting-the-lost-top-tips-to-regain-missing-windows-in-11/"><u>Resurrecting the Lost: Top Tips to Regain Missing Windows in 11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-fix-confirmed-shorts-are-showing-up/"><u>[Updated] Fix Confirmed  Shorts Are Showing Up</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-data-transfer-mishaps-with-windows-usb-devices/"><u>Reversing Data Transfer Mishaps with Windows USB Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-the-windows-11-ui-to-prompt-users-for-system-updates/"><u>Tailoring the Windows 11 UI to Prompt Users for System Updates</u></a></li>
<li><a href="https://extra-resources.techidaily.com/a-comprehensive-overview-of-google-photos-use/"><u>A Comprehensive Overview of Google Photos Use</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-simplified-guide-to-transform-vimeo-video-into-mp3/"><u>[Updated] 2024 Approved  Simplified Guide to Transform Vimeo Video Into MP3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstate-preview-screens-for-files-troubleshoot-on-win-11/"><u>Reinstate Preview Screens for Files – Troubleshoot on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/peak-performance-selective-software-secrets-for-speedy-wins/"><u>Peak Performance: Selective Software Secrets for Speedy Wins</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/elevate-your-biz-game-youtube-channels-that-succeeded/"><u>Elevate Your Biz Game  YouTube Channels That Succeeded</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-speech-detection-with-windows/"><u>Streamlining Speech Detection with Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/workarounds-for-static-energy-controls-on-windows-11/"><u>Workarounds for Static Energy Controls on Windows 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-expert-guide-choosing-best-bdr-players-on-windowsmacos/"><u>[Updated] Expert Guide  Choosing Best BDR Players on Windows/macOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-list-of-brightness-managers-for-windows-multiscreen-professionals/"><u>The Ultimate List of Brightness Managers For Windows Multiscreen Professionals</u></a></li>
<li><a href="https://extra-information.techidaily.com/mastery-over-music-flow-the-art-of-audio-blending/"><u>Mastery Over Music Flow  The Art of Audio Blending</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-files-on-windows-using-python-for-network-transfer/"><u>Seamless Files on Windows: Using Python for Network Transfer</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-integrating-gopro-adventures-with-popular-social-media-channels/"><u>[New] 2024 Approved  Integrating GoPro Adventures with Popular Social Media Channels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-setup-for-gpt/"><u>Navigating Through Windows Setup for GPT</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-ideal-chat-and-meetup-tools-for-large-groups/"><u>2024 Approved  Ideal Chat & Meetup Tools for Large Groups</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-unlocking-your-potential-in-youtube-video-production-scripts/"><u>2024 Approved  Unlocking Your Potential in YouTube Video Production Scripts</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-swiftly-rotate-videos-in-vlc-for-smooth-viewing/"><u>In 2024, Swiftly Rotate Videos in VLC for Smooth Viewing</u></a></li>
<li><a href="https://ai-voice.techidaily.com/updated-top-4-hatsune-miku-voice-ai-generators-for-all-times/"><u>Updated Top 4 Hatsune Miku Voice AI Generators for All Times</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-experience-seamless-recording-cost-free-tools-for-pcsmacos/"><u>2024 Approved  Experience Seamless Recording  Cost-Free Tools for PCs/macOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-address-winscomrssvdll-issues-during-system-boot/"><u>Steps to Address WinscomrssvDll Issues During System Boot</u></a></li>
<li><a href="https://some-techniques.techidaily.com/how-to-solve-youtube-video-distorted-issue-for-2024/"><u>How to Solve YouTube Video Distorted Issue for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-to-windows-11-home-settings/"><u>Navigating to Windows 11 Home Settings</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-simple-steps-to-record-your-youtube-streams/"><u>[New] In 2024, Simple Steps to Record Your YouTube Streams</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-life360-on-windows-pc-for-htc-u23-drfone-by-drfone-virtual-android/"><u>How to Use Life360 on Windows PC For HTC U23? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-made-storage-repositioning-in-onedrive-for-win-11/"><u>Tailor-Made Storage Repositioning in OneDrive for Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/battery-friendly-tips-minimize-windows-11-apps-impact/"><u>Battery-Friendly Tips: Minimize Windows 11 Apps' Impact</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalize-your-chatting-experience-with-10-fixes/"><u>Revitalize Your Chatting Experience with 10 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-censored-windows-11-theme-options-with-registry/"><u>Unveiling Censored Windows 11 Theme Options with Registry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-terminal-and-powershell-identifying-what-sets-them-aside/"><u>Windows Terminal and PowerShell: Identifying What Sets Them Aside</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbo-charging-steam-downloads-for-windows-users/"><u>Turbo-Charging Steam Downloads for Windows Users</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-android-screen-recording-tutorial-essentials/"><u>[Updated] Android Screen Recording Tutorial Essentials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719371847315-fixing-faulty-windows-keys-in-a-minute/"><u>Fixing Faulty Windows Keys in a Minute</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-7-free-video-editing-programs-that-work-flawlessly-for-2024/"><u>[Updated] 7 Free Video Editing Programs That Work Flawlessly for 2024</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-reviewing-the-live-streaming-shopping-industry-in-china/"><u>Updated Reviewing the Live Streaming Shopping Industry in China</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-triggering-instant-play-for-youtube-videos-on-social-media/"><u>[New] In 2024, Triggering Instant Play for YouTube Videos on Social Media</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-double-click-with-these-simple-windows-adjustments/"><u>Optimize Your Double-Click with These Simple Windows Adjustments</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-from-zero-to-hero-on-ig-how-to-garner-a-million-fans-fast-track/"><u>[New] In 2024, From Zero to Hero on IG  How to Garner a Million Fans Fast-Track</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-xiaomi-redmi-note-12-4g-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Xiaomi Redmi Note 12 4G to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-steam-login-lock-ups-with-rust-and-windows/"><u>Navigating Through Steam Login Lock-Ups with Rust & Windows</u></a></li>
<li><a href="https://youtube-help.techidaily.com/how-you-can-get-paid-for-videos-for-2024/"><u>How You Can Get Paid for Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-in-use-resource-error-in-windows-oses-149-chars/"><u>Overcoming In-Use Resource Error in Windows OSes (149 Chars)</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-strategic-screen-customization-timely-adjustments-in-teams/"><u>[Updated] In 2024, Strategic Screen Customization  Timely Adjustments in Teams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stealth-mode-off-how-to-turn-down-windows-11/"><u>Stealth Mode Off: How to Turn Down Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-activatingdeactivating-touch-typing-on-windows/"><u>Tips for Activating/Deactivating Touch Typing on Windows</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/n-2024-fanbase-titans-the-10-most-subscribed-youtube-creators/"><u>[New] In 2024, Fanbase Titans  The 10 Most Subscribed YouTube Creators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-strategies-eradicate-wow-error-132-in-1011/"><u>Winning Strategies: Eradicate WoW Error 132 in 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-your-desktop-experience-with-winbubbles-best-practices/"><u>Tailor Your Desktop Experience with WinBubble's Best Practices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-repairing-razer-synapse-fixes-for-modern-oses/"><u>Swift Repairing: Razer Synapse Fixes for Modern OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-pro-efficient-docx-to-pdf-conversion-made-simple/"><u>Win 11 Pro: Efficient DOCX to PDF Conversion Made Simple</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-disk-potential-masterful-techniques-in-w10w11/"><u>Unlocking Disk Potential: Masterful Techniques in W10/W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-steam-library-no-sync-error-solution/"><u>Tackling Steam Library: No Sync Error Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-salvage-dormant-wsreset-service-on-windows/"><u>Steps to Salvage Dormant WSReset Service on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-bypass-chatbot-assistance-in-win-11-key-gen/"><u>Why Bypass Chatbot Assistance in Win 11 Key Gen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-approach-automated-password-addition-into-windows-texts/"><u>Streamlined Approach: Automated Password Addition Into Windows Texts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-steps-for-a-functional-windows-11-search-interface/"><u>Quick Steps for a Functional Windows 11 Search Interface</u></a></li>
</ul></div>
