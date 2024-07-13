---
title: How to Stop Windows Users From Changing the Date and Time
date: 2024-07-12T17:15:03.852Z
updated: 2024-07-13T17:15:03.852Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Stop Windows Users From Changing the Date and Time
excerpt: This Article Describes How to Stop Windows Users From Changing the Date and Time
keywords: Stopping DST Change on PCs,Prevent Windows Time Modification,Anti-TimeShift in Windows,Block Clock Adjustment WIN,Secure Windows Date Settings,Disable System Time Editing,Protect Windows Timestamps
thumbnail: https://thmb.techidaily.com/46bc9e67353768ac792e1534a64f3c2875130c736cfcb08614e4c3a629de687e.jpg
---

## How to Stop Windows Users From Changing the Date and Time

 You’re using your Windows device and notice something strange in the date and time settings. Someone has changed the settings without your knowledge or permission. This makes it difficult to stay on schedule with tasks and activities. In this guide, we’ll show how to stop anonymous users from changing date and time settings on Windows computers.

## How To Prevent Users From Changing the Date and Time on Windows

 There are two ways to prevent users from changing Windows date and time. The first is to use Group Policy Editor, a system administration tool designed to control computer behavior in an organization. While the second way is to use Registry Editor, which allows you to modify Windows registry settings.

 For both methods, you need administrative access to the computer to change it. Once you’ve made the changes, nobody can alter the date and time settings. Let’s look at each method in more detail.

## 1\. Use the Group Policy Editor

 If your computer is part of an organization and users often change the date and time, use Group Policy Editor to stop it. This will prevent those with limited access to the computer from altering the date and time. However, this method only works for Windows Pro, Enterprise, or Education Editions.

 So, if you have Windows Home Edition, this won’t work. In that case, you must first [activate the Group Policy Editor for Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). If it seems complicated, skip it and try the next solution instead.

 Follow these steps to prevent users from changing the date and time:

1. Press **Win + R** on your keyboard to open the Run window.
2. Type **gpedit.msc** in the text box and press Enter. This will open the Group Policy Editor window.
3. On the left side of the window, navigate to the following path:  
Computer Configuration > Administrative Templates > System > Locale Services
4. In the right-side pane, double-click on **Disallow user override of locale settings**.  
![Disallow user override of locale settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/disallow-user-override-of-locale-settings.jpg)
5. In the pop-up window, check the **Enabled** radio button.
6. Then click **Apply** \> **OK** to save the changes.

 This will block anyone from changing the date and time settings on your computer. However, if you have administrative access to the computer, you can still alter the settings.

 If you want to revert to the default settings later, open Group Policy Editor again and change the value of Disallow user override of locale settings back to Not Configured or Disabled. This way, users can change the time and date again.

## 2\. Tweak the Registry Editor

 If you’re using Windows Home Edition or have disabled the Group Policy Editor, use the Registry Editor to protect date and time settings. This method is more advanced and has a higher risk of system damage.

 In that case, [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it. Doing so will restore settings if something goes wrong.

 Follow these steps to stop users from changing the time and date via the registry:

1. [Open the Run command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** in the field and press Enter. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. In the Registry Editor window, navigate to the following path:  
HKEY_CURRENT_USER\Software\Policies\Microsoft\Control Panel\International\
4. If the International folder doesn’t exist, create one. To do that, right-click on Control Panel and select **New** \> **Key**. Name it **International**.
5. Then right-click on **International** and select New > DWORD (32-bit) Value.
6. Name the newly created value **PreventUserOverrides**.
7. Double-click on the **PreventUserOverrides** DWORD value.  
![Use Registry Editor to Prevent Users From Chaning date and time settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/use-registry-editor-to-prevent-users-from-chaning-date-and-time-settings.jpg)
8. In the pop-up window, change the Value data to **1** and click **OK**.

 Once you’ve made the changes, close the Registry Editor window and restart your computer.

 To undo this restriction, delete the **PreventUserOverrides** DWORD value from the registry or change the value to **0**. Doing so will enable users to change the time and date again.

## Stop Windows Time and Date Changes

 Now stop unauthorized users from changing the date and time settings on your Windows computer. This keeps your tasks and activities on track. If necessary, you can always undo this restriction.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-videos.techidaily.com/in-2024-digital-fortune-makers-top-earning-youtubers/"><u>In 2024, Digital Fortune Makers  Top Earning YouTubers</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-in-2024-youtube-sound-library/"><u>Updated In 2024, YouTube Sound Library</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-decades-most-ingenious-frames-and-organizers-24/"><u>2024 Approved  The Decade's Most Ingenious Frames & Organizers '24</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/ideal-video-maker-apps-for-novice-iphone-and-android-users/"><u>Ideal Video Maker Apps for Novice iPhone and Android Users</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-vivo-t2-5g-by-drfone-android/"><u>In 2024, AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Vivo T2 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-the-edge-why-a-pc-outmatches-a-mac-in-9-key-aspects/"><u>Analyzing the Edge: Why a PC Outmatches a Mac in 9 Key Aspects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-control-over-group-policy-in-windows-11/"><u>Enhance Control over Group Policy in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/error-resolution-at-your-fingertips-top-10-tools/"><u>Error Resolution at Your Fingertips: Top 10 Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/designing-a-lasting-deletion-feature-for-windows-desktop-trash/"><u>Designing a Lasting Deletion Feature for Windows Desktop Trash</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-network-errors-a-guide-for-windows-11-users/"><u>Eliminating Network Errors: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafted-canvas-in-windows-desk-decor-tutorials/"><u>Crafted Canvas in Windows: Desk Decor Tutorials</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/tasty-trends-unveiled-a-taste-of-tiktok-culture-for-2024/"><u>Tasty Trends Unveiled  A Taste of TikTok Culture for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-samsung-galaxy-z-flip-5-drfone-by-drfone-virtual-android/"><u>In 2024, Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Samsung Galaxy Z Flip 5 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-utorrent-stalled-peer-connections-on-win/"><u>Addressing uTorrent Stalled Peer Connections on Win</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/in-2024-deejay-discovery-compile-dj-beats-for-your-playlist/"><u>In 2024, Deejay Discovery Compile DJ Beats for Your Playlist</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-cutting-edge-techniques-for-google-meet-aesthetic-enhancement-for-2024/"><u>[Updated] Cutting-Edge Techniques for Google Meet Aesthetic Enhancement for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-and-solving-the-enigmatic-windows-c0000022-hurdle/"><u>Decoding and Solving the Enigmatic Window's C0000022 Hurdle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-not-found-rockalldll-on-windows-pc/"><u>How to Fix 'Not Found' Rockalldll on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-cannot-open-files-in-windows-system/"><u>How to Resolve 'Cannot Open' Files in Windows System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-correcting-xbox-game-pass-fatal-error-in-windows-11/"><u>Guide to Correcting Xbox Game Pass Fatal Error in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-seamless-workflows-ifttt-for-task-management/"><u>Crafting Seamless Workflows: IFTTT for Task Management</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/in-2024-unleash-your-creativity-best-mac-video-maker-apps/"><u>In 2024, Unleash Your Creativity Best Mac Video Maker Apps</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-prime-video-strategies-selecting-perfect-format-for-youtube/"><u>In 2024, Prime Video Strategies – Selecting Perfect Format for YouTube</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-essential-screen-recording-steps-for-perfection/"><u>[New] In 2024, Essential Screen Recording Steps for Perfection</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/3-easy-ways-to-factory-reset-a-locked-iphone-12-mini-without-itunes-drfone-by-drfone-ios/"><u>3 Easy Ways to Factory Reset a Locked iPhone 12 mini Without iTunes | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-steps-for-perfect-directx-setup-and-updates/"><u>Easy Steps for Perfect DirectX Setup & Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-prime-screenshot-substitutes-beyond-the-windows-ecosystem/"><u>5 Prime Screenshot Substitutes Beyond the Windows Ecosystem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-zoom-crash-code-1132-on-windows-devices/"><u>Eliminating Zoom Crash Code 1132 on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-windows-vlc-input-compatibility-faults/"><u>Correcting Windows VLC Input Compatibility Faults</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719342757489-commanding-your-digital-files-linking-dropbox-googledrive-to-c/"><u>Commanding Your Digital Files: Linking Dropbox, GoogleDrive to C:</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-prime-6-tools-to-remove-signature-backgrounds-effortlessly/"><u>[New] Prime 6 Tools to Remove Signature Backgrounds Effortlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easing-up-microsoft-store-restrictions-on-windows-11/"><u>Easing Up Microsoft Store Restrictions on Windows 11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-auditory-logging-system-tones-and-voice-samples/"><u>[New] In 2024, Auditory Logging  System Tones & Voice Samples</u></a></li>
<li><a href="https://win11-tips.techidaily.com/brightening-dull-cursors-in-uefi/"><u>Brightening Dull Cursors in UEFI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-win1011-context-menu-integrate-disk-space-viewer/"><u>Customizing Win10/11 Context Menu: Integrate Disk Space Viewer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-the-challenge-the-ultimate-fix-for-xbox-game-passs-error-code-0x800700e9/"><u>Conquering the Challenge: The Ultimate Fix for Xbox Game Pass’s Error Code 0X800700E9</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-set-of-folders-cannot-be-opened-error-in-outlook-on-windows/"><u>How to Fix “The Set of Folders Cannot Be Opened” Error in Outlook on Windows</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-innovating-interaction-beyond-vidcon-conclaves/"><u>[Updated] Innovating Interaction  Beyond VidCon Conclaves</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-pokemon-go-joystick-on-infinix-note-30-vip-racing-edition-drfone-by-drfone-virtual-android/"><u>How to use Pokemon Go Joystick on Infinix Note 30 VIP Racing Edition? | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-ace-bgm-selection-perfect-backdrops-for-video-calling/"><u>[Updated] In 2024, Ace BGM Selection  Perfect Backdrops for Video Calling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-over-windows-updater-failure-x712/"><u>Winning Over Windows Updater Failure X712</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-win-based-steam-internet-connectivity-issues/"><u>Fixing Win-Based Steam Internet Connectivity Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-tweaking-win11-connectivity-options/"><u>Guide to Tweaking Win11 Connectivity Options</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-converting-conversations-speech-to-text-made-easy/"><u>New 2024 Approved Converting Conversations Speech to Text Made Easy</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-innovative-5-tech-solutions-for-capturing-video-calls/"><u>[Updated] In 2024, Innovative 5 Tech Solutions for Capturing Video Calls</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-a-vloggers-dream-exploring-the-best-12-video-capture-devices-for-2024/"><u>[Updated] A Vlogger's Dream  Exploring the Best 12 Video Capture Devices for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/interpreting-the-purpose-behind-a-facebooks-blue-video-icon/"><u>Interpreting the Purpose Behind a Facebook's Blue Video Icon</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-tricks-to-stream-pre-filmed-footage-during-facebook-livestreams/"><u>[New] In 2024, Tricks to Stream Pre-Filmed Footage During Facebook Livestreams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-photo-editing-experience-with-photoshop/"><u>Enhancing Photo Editing Experience with Photoshop</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-no-money-down-best-web-converters-from-tiktok-to-mp3-ranked/"><u>2024 Approved  No Money Down  Best Web Converters From TikTok To MP3 Ranked</u></a></li>
</ul></div>
