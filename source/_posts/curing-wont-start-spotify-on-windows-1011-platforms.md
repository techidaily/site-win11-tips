---
title: Curing Won't Start Spotify on Windows 10/11 Platforms
date: 2024-07-12T16:49:05.352Z
updated: 2024-07-13T16:49:05.352Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Curing Won't Start Spotify on Windows 10/11 Platforms
excerpt: This Article Describes Curing Won't Start Spotify on Windows 10/11 Platforms
keywords: Fix Spotify Windows Issue,Restart Spotify On PC,Troubleshoot Spotify Playback,Resolve Spotify Not Starting,Enable Spotify Sound on Win,Start Spotify Sound Challenges,Activate Spotify Windows 10/11
thumbnail: https://thmb.techidaily.com/f060aa48894ea1b017bf8a4af8da622e4076e35a663f40c627d05eef8a39852a.png
---

## Curing Won't Start Spotify on Windows 10/11 Platforms

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
<li><a href="https://win11-tips.techidaily.com/restoring-functioning-office-outlook-alerts/"><u>Restoring Functioning Office Outlook Alerts</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-android-app-not-installed-error-on-oppo-a58-4g-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android App Not Installed Error on Oppo A58 4G Quickly? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/selective-vmm-recommendations-for-windows-11-success/"><u>Selective VMM Recommendations for Windows 11 Success</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-avoid-boredom-learn-to-shuffle-youtube-lists/"><u>2024 Approved  Avoid Boredom  Learn to Shuffle YouTube Lists</u></a></li>
<li><a href="https://discord-videos.techidaily.com/top-tools-to-screen-capture-discord-online-interactions-for-2024/"><u>Top Tools to Screen-Capture Discord Online Interactions for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/raising-the-bar-for-user-interface-in-w11-larger-icons/"><u>Raising the Bar for User Interface in W11: Larger Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/probing-windows-bsod-files-and-their-residues/"><u>Probing Windows BSOD Files & Their Residues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-solve-systemsettings-issue-on-win11/"><u>Strategies to Solve SystemSettings Issue on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guides-to-restore-lock-screen-timeout-mechanism/"><u>Guides to Restore Lock Screen Timeout Mechanism</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/2024-approved-wmm-not-your-thing-try-these-13-video-editing-solutions/"><u>2024 Approved WMM Not Your Thing? Try These 13 Video Editing Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-save-settings-restoration-in-windows-1011s-pubg/"><u>Mastering Save Settings Restoration in Windows 10/11'S PUBG</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reworking-records-6-windows-applications-for-date-revision/"><u>Reworking Records: 6 Windows Applications for Date Revision</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-premium-3ds-pc-mimicry-software-choices/"><u>2024 Approved  Premium 3Ds PC Mimicry Software Choices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-blue-screen-0xc0000001-on-pc/"><u>Tackling Blue Screen 0xC0000001 on PC</u></a></li>
<li><a href="https://facebook.techidaily.com/social-synergy-in-the-virtual-realm-8-methods-to-connect/"><u>Social Synergy in the Virtual Realm: 8 Methods to Connect</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-premiering-popularity-amazon-prime-tweets-of-23/"><u>2024 Approved  Premiering Popularity  Amazon Prime Tweets of '23</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-system-performance-by-adding-disk-space-analyzer-tool/"><u>Streamline System Performance by Adding Disk Space Analyzer Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/increase-output-decrease-time-harness-power-of-flow-launcher/"><u>Increase Output, Decrease Time: Harness Power of Flow Launcher</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/peak-creation-suite-insightful-2023-analysis/"><u>Peak Creation Suite  Insightful 2023 Analysis</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-avidemux-for-beginners-cropping-cutting-and-polishing-your-video-footage/"><u>New In 2024, Avidemux for Beginners Cropping, Cutting, and Polishing Your Video Footage</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-sjcam-sj6-legend-action-camera-complete-review/"><u>[Updated] In 2024, SJCam SJ6 Legend Action Camera Complete Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-repair-image-id-0x80780119-on-windows-os/"><u>How To Repair Image ID: 0X80780119 on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-unsuccessful-nvidia-connect-attempts-in-windows-11/"><u>Resolving Unsuccessful Nvidia Connect Attempts in Windows 11</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-crafting-winning-tiktok-ad-campaigns-techniques-and-examples/"><u>[New] Crafting Winning TikTok Ad Campaigns  Techniques & Examples</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-secure-your-browsing-with-microsofts-defender-in-win-11/"><u>Step-by-Step: Secure Your Browsing with Microsoft's Defender in Win 11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-smartphone-photographers-must-have-app-list/"><u>2024 Approved  Smartphone Photographers' Must-Have App List</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-exclusive-list-10-budget-friendly-passport-photographers-online/"><u>In 2024, Exclusive List  10 Budget-Friendly Passport Photographers Online</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-2024-approved-brief-blueprints-iphone-content-for-desktop/"><u>[New] 2024 Approved  Brief Blueprints  IPhone Content for Desktop</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-boosting-story-reach-through-linked-profile-ties/"><u>[New] 2024 Approved  Boosting Story Reach Through Linked Profile Ties</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-enhancing-viewer-attention-igtv-cover-tips/"><u>[Updated] In 2024, Enhancing Viewer Attention  IGTV Cover Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-pc-printer-link-fixes/"><u>Mastering PC Printer Link Fixes</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-5-simple-yet-powerful-strategies-to-skyrocket-your-youtube-views/"><u>[Updated] 2024 Approved  5 Simple Yet Powerful Strategies to Skyrocket Your YouTube Views</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-error-0x80072efd-in-windows-devicesstore-apps/"><u>Overcoming Error 0X80072EFD in Windows Devices/Store Apps</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-a-step-by-step-approach-to-crafting-your-video-market-standouts/"><u>[Updated] In 2024, A Step-by-Step Approach to Crafting Your Video' Market Standouts</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/approved-thumbnail-design-for-engagement-a-youtube-resizing-guide/"><u>2024 Approved  Thumbnail Design for Engagement  A YouTube Resizing Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-skip-out-of-s-mode-with-ease-for-your-pc/"><u>Swiftly Skip Out of S Mode with Ease for Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-application-was-unable-to-start-0xc000003e-error-in-windows-11-and-11/"><u>How to Fix “The Application Was Unable to Start” 0Xc000003e Error in Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-erase-personal-info-from-sign-in-window/"><u>Guide to Erase Personal Info From Sign-In Window</u></a></li>
<li><a href="https://howto.techidaily.com/full-guide-how-to-fix-connection-is-not-private-on-realme-c55-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Guide How To Fix Connection Is Not Private on Realme C55 | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/comprehensive-scrutiny-gear-360s-virtual-reality-capability-for-2024/"><u>Comprehensive Scrutiny  Gear 360'S Virtual Reality Capability for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-oneplus-nord-n30-se-location-on-skout-drfone-by-drfone-virtual-android/"><u>How to Change OnePlus Nord N30 SE Location on Skout | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switchtonightvisioninnotepadwin/"><u>SwitchToNightVisionInNotepadWin</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-ways-to-tackle-windows-rpc-errors-effectively/"><u>Easy Ways to Tackle Windows RPC Errors Effectively</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-saving-scenes-seamlessly-the-power-of-vimeo-record/"><u>[New] In 2024, Saving Scenes Seamlessly  The Power of Vimeo Record</u></a></li>
<li><a href="https://win11-tips.techidaily.com/smooth-sailing-with-these-fixes-for-windows-update/"><u>Smooth Sailing with These Fixes for Windows Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-specific-error-403-in-roblox-space/"><u>Resolving Windows-Specific Error 403 in Roblox Space</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-restoring-a-dysfunctional-downloads-hub-in-windows/"><u>Guidelines for Restoring a Dysfunctional Downloads Hub in Windows</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-best-voice-changers-for-whatsapp-free-included/"><u>Updated 2024 Approved Best Voice Changers for WhatsApp Free Included</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-recover-from-failed-discord-games-detection-on-windows/"><u>Steps to Recover From Failed Discord Games Detection on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recovering-d3dx939dll-error-on-win11/"><u>Recovering D3DX9_39.dll Error on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-impacts-of-ditching-windows-11s-taskbar-chatting-feature/"><u>Exploring Impacts of Ditching Windows 11'S Taskbar Chatting Feature</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-unraveling-image-mysteries-the-triple-tactic-fb-backward-search/"><u>[Updated] Unraveling Image Mysteries  The Triple-Tactic FB Backward Search</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-from-in-the-moment-to-lasting-images-how-to-save-from-snapchat/"><u>[New] 2024 Approved  From In-the-Moment to Lasting Images  How to Save From Snapchat</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-low-latency-techniques-for-discord-on-windows/"><u>Mastering Low-Latency Techniques for Discord on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-storage-4-methods-to-tap-into-windows-11s-disk-manager/"><u>Streamline Storage: 4 Methods to Tap Into Windows 11'S Disk Manager</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-2024-approved-heartstrings-harmony-best-music-to-accompany-your-engagement/"><u>[Updated] 2024 Approved  Heartstrings Harmony  Best Music to Accompany Your Engagement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapid-rendition-accelerating-prints-on-windows-system/"><u>Rapid Rendition: Accelerating Prints on Windows System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/obscure-yet-outstanding-windows-11-themes/"><u>Obscure yet Outstanding Windows 11 Themes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-ad-ds-printer-fails-in-win-1011/"><u>Resolving AD DS Printer Fails in Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-no-device-drivers-detected-on-windows-setup/"><u>Resolving 'No Device Drivers Detected' On Windows Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-persistent-failures-of-cp-configurations-on-win11/"><u>Mending Persistent Failures of CP Configurations on Win11</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-size-your-videos-youtubes-best-practices-unveiled/"><u>[Updated] How to Size Your Videos  YouTube's Best Practices Unveiled</u></a></li>
<li><a href="https://animation-videos.techidaily.com/cartoon-fundamentals-how-to-learn-cartoon-characters-sketch-quickly/"><u>Cartoon Fundamentals How to Learn Cartoon Characters Sketch Quickly</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-optimize-gmail-for-video-calls-with-effective-zoom-use/"><u>In 2024, Optimize Gmail for Video Calls with Effective Zoom Use</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-ways-to-track-nokia-c12-without-them-knowing-drfone-by-drfone-virtual-android/"><u>3 Ways to Track Nokia C12 without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefine-task-manager-welcome-panel-in-windows-11/"><u>Redefine Task Manager Welcome Panel in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-video-lag-in-vlc-media-player-on-windows/"><u>How to Fix Video Lag in VLC Media Player on Windows</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-retrieve-lost-photos-from-pixel-fold-by-fonelab-android-recover-photos/"><u>Best Android Data Recovery - Retrieve Lost Photos from Pixel Fold.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-and-folder-combination-in-windows-11/"><u>Mastering File & Folder Combination in Windows 11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/the-art-of-video-thumbnail-making-for-popular-content-for-2024/"><u>The Art of Video Thumbnail Making for Popular Content for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-efficient-content-management-rank-of-the-top-10-youtube-trimmers/"><u>In 2024, Efficient Content Management  Rank of the Top 10 YouTube Trimmers</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-srt-and-mp4-synergy-a-comprehensive-guide-edition-for-2024/"><u>[New] SRT & MP4 Synergy  A Comprehensive Guide Edition for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-slow-windows-10-closure-while-tasks-remain-open/"><u>Strategies for Slow Windows 10 Closure While Tasks Remain Open</u></a></li>
</ul></div>
