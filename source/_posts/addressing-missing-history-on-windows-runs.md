---
title: Addressing Missing History on Windows Runs
date: 2024-07-12T17:18:59.715Z
updated: 2024-07-13T17:18:59.715Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Missing History on Windows Runs
excerpt: This Article Describes Addressing Missing History on Windows Runs
keywords: History Gaps in WinOS,Fix Historical Omissions,Windows History Lacks,Remedy Unrecorded Windows Events,Bridge Windows Past Missing,Resolve OS History Voids,Correct Windows Timeline Gaps
thumbnail: https://thmb.techidaily.com/354d3de8b2ab7d7a38cbcbf902765f2fb1bfbf3c885557e06e23ea74d7f6110b.jpg
---

## Addressing Missing History on Windows Runs

 The Run command dialog box in Windows makes it easy to launch apps, access system tools, and perform various other tasks. It also has an auto-complete feature that makes it easy to re-use your commands later. However, the auto-complete feature in the Run tool may not work if it fails to save your command history in the first place.

 If you're encountering a similar problem, don’t fret. Below, we share some quick and useful tips that should get the Run tool to save your history once again.

## 1\. Check Your Privacy Settings

 A common reason why Windows may not save the Run command history is if you have previously blocked it from tracking your app launches. Here’s how you can change that.

1. Press **Win + I** to open the Settings app.
2. Select **Privacy & security** from the left sidebar.
3. Under Windows permissions, click on **General**.
4. Enable the toggle next to **Let Windows improve Start and search results by tracking app launches**.  
![Allow Windows to Track App Launches on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-windows-to-track-app-launches-on-windows.jpg)

 After completing the above steps, try running a few commands via the Run dialog box. Then, check if it is saving your command history and providing auto-complete suggestions.

## 2\. Edit Registry Files

 Is the **Let Windows improve Start and search results by tracking app launches** option grayed out on your PC? If so, you can take help from the Registry Editor to get Windows to save your Run command history.

 As you may already be aware, registry files on your PC store essential settings for Windows and its services. Making incorrect modifications to these files can render your system inoperable. Hence, it’s a good idea to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Click the search icon on the taskbar or press the **Win + S** keyboard shortcut to open the search menu.
2. Type **registry editor** in the search box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer > Advanced**.
5. Locate the **Start\_TrackProgs** entry in the right pane. If you can’t find it, right-click on the **Advanced** key and select **New > DWORD (32-bit) Value**. Rename it to **Start\_TrackProgs**.
6. Double-click the newly created DWORD and enter **1** in the **Value data** field.
7. Click **OK**.  
![Edit Registry DWORD on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-registry-dword-on-windows.jpg)

 Restart your PC after this for the changes to take effect. Following this, the Run command should start saving your history on Windows.

## 3\. Apply Generic Fixes

 If the problem persists even after implementing the above tips, you can try applying some basic fixes to resolve the underlying issue.

* **Restart Your PC:** This may appear rudimentary, but temporary OS-related glitches can sometimes cause such anomalies. If it’s nothing major, [restarting your PC](https://www.makeuseof.com/windows-restart-methods/) should fix any issues with the Run command.
* **Run an SFC Scan:** Such issues can also arise if some of the critical system files on your PC are corrupt. [Running a System File Checker (SFC) scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) can help detect and repair any damaged system files on your PC.
* **Scan for Malware:** It’s possible that your system is infected by malware, which is why the Run command is having trouble saving your history. To rule out this possibility, you can [scan Windows for malware using PowerShell](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/) or Windows Defender.

## Get the Run Tool to Save Your History on Windows

 It can be inconvenient if the Run command dialog box stops saving your history on Windows. Hopefully, one of the solutions provided above has successfully resolved the issue for you.

 If you feel that the Run utility in Windows lacks advanced features, you can always switch to alternative tools like Run-Command or PowerToys Run.

 If you're encountering a similar problem, don’t fret. Below, we share some quick and useful tips that should get the Run tool to save your history once again.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/overcoming-netflix-freeze-in-windows-software/"><u>Overcoming Netflix Freeze in Windows Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-into-powertoys-for-faster-copy-pasting/"><u>Dive Into PowerToys for Faster Copy-Pasting</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-cutting-ties-with-instagram-users-for-2024/"><u>[Updated] Cutting Ties with Instagram Users for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/innovative-approaches-to-network-broadcast-with-vlc/"><u>Innovative Approaches to Network Broadcast with VLC</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-becoming-a-skin-deep-sage-setting-up-your-beauty-channel-for-2024/"><u>[New] Becoming a Skin-Deep Sage  Setting Up Your Beauty Channel for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/ignite-a-sizzling-online-presence-with-these-instagram-9-strategies/"><u>Ignite a Sizzling Online Presence with These Instagram #9 Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/historic-footprints-in-tech-rediscovering-7-old-world-windows-aspects/"><u>Historic Footprints in Tech: Rediscovering 7 Old-World Windows Aspects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-manual-for-registry-editing-with-command-prompt/"><u>Comprehensive Manual for Registry Editing with Command Prompt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-turn-off-the-mobile-interface-win-11/"><u>Quick Fix: Turn Off the Mobile Interface (Win 11)</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-the-ultimate-guide-to-comical-vocal-customization-for-enjoyable-calls/"><u>In 2024, The Ultimate Guide to Comical Vocal Customization for Enjoyable Calls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-communication-making-calls-on-windows-11-with-unison-app/"><u>Elevate Communication: Making Calls on Windows 11 with Unison App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719204825676-fix-the-unresponsive-shift-on-your-pc-now/"><u>Fix the Unresponsive Shift on Your PC Now!</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-6-video-styles-for-maximum-viewer-engagement/"><u>[New] 6 Video Styles for Maximum Viewer Engagement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gain-early-access-the-way-into-windows-11-beta/"><u>Gain Early Access: The Way Into Windows 11 Beta</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-amplify-your-facebook-presence-with-mobile-music-files/"><u>2024 Approved  Amplify Your Facebook Presence with Mobile Music Files</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/unbeatable-ways-to-archive-lol-battles/"><u>Unbeatable Ways to Archive LOL Battles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lightning-bloatware-eradication-for-your-win11-system/"><u>Lightning Bloatware Eradication for Your Win11 System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/next-gen-teams-meeting-demands-efficiently/"><u>Next-Gen Teams Meeting Demands Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-cloud-storage-onedrive-login-on-windows/"><u>Master Your Cloud Storage: OneDrive Login on Windows</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-elite-channel-explorer-discover-prime-video-status/"><u>In 2024, Elite Channel Explorer  Discover Prime Video Status</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-stop-nvidia-graphic-boost-features/"><u>Guide to Stop NVIDIA Graphic Boost Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-launching-apps-on-windows-11/"><u>Efficiently Launching Apps on Windows 11</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-bold-and-creative-pfp-options-for-a-unique-tiktok-look/"><u>[Updated] In 2024, Bold & Creative PFP Options for a Unique TikTok Look</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-xiaomi-redmi-13c-5g-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Xiaomi Redmi 13C 5G Phones with/without a PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-winsplit-display-issues-now/"><u>Fixing WinSplit Display Issues Now!</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-in-2024-premier-pick-top-10-apps-to-catch-football-and-tennis-in-the-moment/"><u>[New] In 2024, Premier Pick  Top 10 Apps to Catch Football and Tennis in the Moment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-the-corrupted-file-issue-in-windows-11-os-error-0x80070570/"><u>Mending the Corrupted File Issue in Windows 11 OS (Error 0X80070570)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-fatal-glitches-steps-to-fix-error-0x00000001-in-xbox-game-pass-for-windows-11/"><u>Overcoming Fatal Glitches: Steps to Fix Error 0X00000001 in Xbox Game Pass for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-onedrive-connection-problems-in-os-versions/"><u>Fixing OneDrive Connection Problems in OS Versions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-11s-fatal-0xf0831-malfunction/"><u>Bypassing Windows 11'S Fatal 0XF0831 Malfunction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/propelty-keystrokes-on-windows-1011-decrease-lag-quickly/"><u>Propelty Keystrokes on Windows 10/11: Decrease Lag Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-customization-user-dir-names-in-w11/"><u>Mastering Customization: User Dir Names in W11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-samsung-galaxy-a34-5g-phone-password-without-factory-reset-by-drfone-android/"><u>How to Unlock Samsung Galaxy A34 5G Phone Password Without Factory Reset?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-effortless-edits-crafting-new-folders-on-windows-11/"><u>Explore Effortless Edits: Crafting New Folders on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-setup-service-via-command-line-utilities/"><u>Adjusting Setup Service via Command-Line Utilities</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-how-to-schedule-effective-reliable-virtual-team-meetings-with-google/"><u>[Updated] 2024 Approved  How to Schedule Effective, Reliable Virtual Team Meetings with Google</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-the-ultimate-list-best-movie-trailer-makers-for-windows-and-mac/"><u>New 2024 Approved The Ultimate List Best Movie Trailer Makers for Windows and Mac</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-selected-best-5-youtube-script-writing-ai-customized-for-you/"><u>Updated Selected Best 5 YouTube Script Writing AI Customized for You</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-direct-from-youtube-select-sites-for-effortless-tone-downloads/"><u>2024 Approved  Direct-From-YouTube  Select Sites for Effortless Tone Downloads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-the-vintage-password-problem-on-w10w11/"><u>Navigating Through the Vintage Password Problem on W10/W11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-comprehensible-rundown-on-djis-latest-creation-inspire-2/"><u>In 2024, The Comprehensible Rundown on DJI's Latest Creation - Inspire 2</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-sharefake-gps-on-uber-for-itel-p55plus-drfone-by-drfone-virtual-android/"><u>How to share/fake gps on Uber for Itel P55+ | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-soundtracks-for-snaps-a-guide-to-video-audio-selection/"><u>In 2024, Soundtracks for Snaps  A Guide to Video Audio Selection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-spotify-connections-on-windows-11-devices/"><u>Overcoming Spotify Connections on Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-elite-windows-apps-for-data-security-149-chars/"><u>7 Elite Windows Apps for Data Security (149 Chars)</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/reimagine-personal-storytelling-on-snapchat-access-a-library-of-over-120-ideas-to-stand-out/"><u>Reimagine Personal Storytelling on Snapchat  Access a Library of Over 120 Ideas to Stand Out</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-free-screenshot-and-recording-made-simple-for-android-users/"><u>[New] 2024 Approved  Free Screenshot & Recording Made Simple for Android Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/excel-on-windows-1011-our-selection-of-the-top-5plus-productivity-boosters/"><u>Excel on Windows 10/11: Our Selection of the Top 5+ Productivity Boosters</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-essential-8-backdrops-to-transform-your-mbp-screen/"><u>In 2024, Essential 8 Backdrops to Transform Your MBP Screen</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-how-to-obtain-and-create-animated-gif-icons-like-a-pro-for-2024/"><u>Updated How to Obtain and Create Animated GIF Icons Like a Pro for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delight-in-top-tier-windows-features-via-ms-store-apps/"><u>Delight in Top-Tier Windows Features via MS Store Apps</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-efficient-ways-to-archive-facetime-chats/"><u>[New] Efficient Ways to Archive FaceTime Chats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improve-real-time-display-updates-for-win-11-task-tracker/"><u>Improve Real-Time Display Updates for Win 11 Task Tracker</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-simplified-guide-to-accurate-profile-ages-on-tiktok/"><u>[New] Simplified Guide to Accurate Profile Ages on TikTok</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-window-updates-blocked-by-error-2e/"><u>Fix Window Updates Blocked by Error 2E</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-cannot-access-source-file-in-win1110/"><u>Dealing with Cannot Access Source File in Win11/10</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-on-oppo-reno-11-5g-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos on Oppo Reno 11 5G</u></a></li>
</ul></div>
