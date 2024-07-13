---
title: 5 Ways to Fix a Windows Device That's Stuck in Dark Mode
date: 2024-07-12T17:58:09.269Z
updated: 2024-07-13T17:58:09.269Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 5 Ways to Fix a Windows Device That's Stuck in Dark Mode
excerpt: This Article Describes 5 Ways to Fix a Windows Device That's Stuck in Dark Mode
keywords: Dark Modes Troubleshoot,Windows Dark Mode Fixes,Resolve Dark Mode Error,Restart Dark Mode Issue,Turn Off Windows Dark Mode,Revert to Light Theme,Fix Stuck Dark Mode Device
thumbnail: https://thmb.techidaily.com/b92970fb02a09749baa6f2838ddd89dd174bd2bb3f33370dc3c96100a7eda776.jpg
---

## 5 Ways to Fix a Windows Device That's Stuck in Dark Mode

 You might often enable dark mode on Windows to reduce eye strain, but it’s quite frustrating when you suddenly can’t switch from dark to normal mode again

 If you’re experiencing this issue, then we’ve got solutions for you. In this article, we’ll explore the five ways to fix your Windows PC when it’s stuck in dark mode.

## 1\. Configure Settings in the Local Group Policy Editor

 The Local Group Policy Editor (LGPE) is a tool that allows you to configure various settings on your device. Interestingly, you can also use the LGPE to troubleshoot various system issues.

 Now, let’s check out how this tool can help you when your device is stuck in dark mode:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **User Configuration > Administrative Templates > Control Panel > Personalization**.
4. Double-click on the **Prevent changing theme** option on the right-hand side pane.

![Using the Local Group Policy Editor to Prevent Others From Changing the Desktop Theme](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-the-Local-Group-Policy-Editor-to-Prevent-Others-From-Changing-the-Desktop-Theme.jpg)

 Next, select the **Not Configured** or **Disabled** option on the pop-up screen. From there, click **Apply** and then click **OK** to disable the **Prevent changing theme** option.

 If the issue persists, navigate to the **Personalization** folder as per the previous steps and then disable the following options:

* Prevent changing color and appearance
* Prevent changing desktop background
* Prevent changing screen saver
* Prevent changing color scheme
* Load a specific theme
* Force specific screen saver
* Force a specific visual style file or force Windows Classic

 Finally, restart your device to save these changes.

## 2\. Tweak the Contrast Theme Settings

 You might be stuck in dark mode simply because you’ve enabled the "High contrast" option on Windows. So, let’s check out how you can resolve this problem:

1. Press **Win + I** to open the system settings.
2. Select **Ease of Access** from the options.
3. Click **High contrast** on the left.
4. **Turn off** the button below the **Turn on high contrast** option and check if this resolves the issue.

![Turning off the button below the Turn on high contrast option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/turning-off-the-button-below-the-turn-on-high-contrast-option.jpg)

## 3\. Edit the Relevant Registry Files

 Editing some Registry files could also help you tackle the issue at hand. But to be on the safe side, [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first before you proceed. This tool is sensitive and could wreak havoc on your PC if you tweak the wrong keys.

 Now, here’s how to fix the “dark mode” problem using the Registry Editor:

1. Press **Win + R** to open the Run command dialog box.
2. Type **regedit** and press **Enter** to open the Registry Editor. Alternatively, check out [the various ways to access the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. Type the following command into the address bar:

HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Themes\Personalize

 Next, double-click on the **AppsUseLightTheme** value on the right-hand side pane.

![Clicking the AppsUseLightTheme value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/clicking-the-appsuselighttheme-value.jpg)

 Type **0** in the **Value data** box and then click **OK**.

 From there, set the **Value data** as **0** for the **ColorPrevalence**, **EnableTransparency**, and **SystemUsesLightTheme** values. When you finish, restart your device and check if this resolves the problem.

## 4\. Disable Third-Party Apps Like the Auto Dark Mode Tool

 Apps like the [Microsoft Auto Dark Mode](https://apps.microsoft.com/store/detail/auto-dark-mode/XP8JK4HZBVF435) tool switch between dark and light modes at scheduled times. If you’ve configured its settings unknowingly, then it might end up enabling the dark mode feature unexpectedly.

 To resolve the issue, the best solution would be to disable this tool (and any other similar third-party app). Alternatively, you can configure the tool’s settings to your liking. That way, your device will only go into dark mode when you want it to.

## 5\. Perform Some Generic Windows-Based Fixes

 Still struggling to resolve the issue? Perhaps the error is caused by corrupted system files. In this case, the best solution is to [repair corrupted Windows files using its built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

 And if all else fails, [update your Windows device](https://www.makeuseof.com/update-windows-manually/) and see if that helps.

## No More Getting Stuck in Dark Mode

 There’s no denying that the Windows dark mode option is quite convenient. However, being unable to switch from dark to normal mode is quite unpleasant. If your device is stuck in dark mode, try any of the solutions we’ve covered.


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
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-the-ultimate-guide-to-affordable-stock-photography-insights-from-pexelscom/"><u>Updated 2024 Approved The Ultimate Guide to Affordable Stock Photography Insights From Pexels.com</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-fast-track-to-facebooks-latest-viewing-history-2e23/"><u>[New] Fast Track to Facebook’s Latest Viewing History (2E23)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cross-platform-android-entertainment-in-windows-11-via-play-services/"><u>Cross-Platform Android Entertainment in Windows 11 via Play Services</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/the-swift-video-voyage-navigating-through-the-youtubes-and-tiktok-landscapes-for-2024/"><u>The Swift Video Voyage  Navigating Through the YouTubes and TikTok Landscapes for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-setting-up-a-taskbar-on-windows-11-tablets/"><u>Guide to Setting Up a Taskbar on Windows 11 Tablets</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-rhythm-and-reels-instagrams-music-playbook-for-2024/"><u>[Updated] Rhythm & Reels  Instagram’s Music Playbook for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/s-best-android-video-editors-free-paid-and-everything-in-between/"><u>S Best Android Video Editors Free, Paid, and Everything in Between</u></a></li>
<li><a href="https://win11-tips.techidaily.com/astra-pilot-disappearance-steps-for-windows-11-users/"><u>Astra Pilot Disappearance? Steps for Windows 11 Users</u></a></li>
<li><a href="https://howto.techidaily.com/fix-unfortunately-settings-has-stopped-on-realme-11-5g-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Unfortunately Settings Has Stopped on Realme 11 5G Quickly | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-ultimate-screenshot-and-record-solutions-for-discord/"><u>[New] In 2024, Ultimate Screenshot & Record Solutions for Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-0x0000011b-operation-failure-on-windows-11/"><u>Correcting 0X0000011B Operation Failure on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-setup-windows-11-arm-from-an-iso-file-stepwise-approach/"><u>Efficiently Setup Windows 11 ARM From an ISO File Stepwise Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-7-prime-free-password-generators-for-pcs/"><u>Explore 7 Prime Free Password Generators for PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-uninstallreinstall-issues-for-windows-store/"><u>Fix Uninstall/Reinstall Issues for Windows Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-data-protection-top-7-win-apps-148-chars/"><u>Enhancing Data Protection: Top 7 Win Apps (148 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fixes-for-browser-copy-paste-woes-in-windows/"><u>Essential Fixes for Browser Copy-Paste Woes in Windows</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/top-5-vivo-y02t-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Vivo Y02T Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dismantling-lan-access-barriers-on-winsminecraft/"><u>Dismantling LAN Access Barriers on WinsMinecraft</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/audio-wizards-unveiled-top-5-techniques-for-win10-for-2024/"><u>Audio Wizards Unveiled  Top 5 Techniques for Win10 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-through-windows-update-obstacles-with-error-code-0x800736cc/"><u>Breaking Through Windows Update Obstacles with Error Code 0X800736CC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-through-the-haze-9-tips-for-crystal-clear-pc-monitors/"><u>Cutting Through the Haze: 9 Tips for Crystal-Clear PC Monitors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-the-nvidia-geforce-connection-hurdle-in-win-11/"><u>Bypassing the Nvidia GeForce Connection Hurdle in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-note-clarity-obsidian-canvas-methods/"><u>Enhancing Note Clarity: Obsidian Canvas Methods</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-the-true-story-of-youtube-earnings-and-viewer-volume-requirements/"><u>[Updated] In 2024, The True Story of YouTube Earnings and Viewer Volume Requirements</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-bending-words-altering-text-images/"><u>In 2024, Bending Words  Altering Text Images</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-2024-approved-whats-music-video-gif-and-how-to-add-music-to-gif-files/"><u>Updated 2024 Approved Whats Music Video GIF & How to Add Music to GIF Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-obsolete-to-optimal-atlasos-makeover/"><u>From Obsolete to Optimal: AtlasOS Makeover</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-windows-11-editions-a-compre-point-by-point-analysis/"><u>Deciphering Windows 11 Editions: A Compre Point-by-Point Analysis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/counteracting-mandatory-elements-alert-on-windows-10and11-os/"><u>Counteracting Mandatory Elements Alert on Windows 10&11 OS</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-expert-techniques-for-acquiring-pristine-images/"><u>2024 Approved  Expert Techniques for Acquiring Pristine Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hacking-into-windows-11s-silent-camera-alert-system/"><u>Hacking Into Windows 11'S Silent Camera Alert System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-how-clockdate-shows-in-window-11/"><u>Customizing How Clock/Date Shows in Window 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-valorants-audio-sync-on-microsoft-devices/"><u>Correcting Valorant's Audio Sync on Microsoft Devices</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/2024-approved-discovering-the-most-captivating-anime-character-reinterpretations/"><u>2024 Approved Discovering the Most Captivating Anime Character Reinterpretations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/game-explorer-3-ways-to-access-directories-on-windows-pcs/"><u>Game Explorer: 3 Ways to Access Directories on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dodging-the-dead-zone-fix-for-stranded-xbox-on-windows-11/"><u>Dodging the Dead Zone: Fix for Stranded Xbox on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-you-to-wipe-login-page-contacts/"><u>Guiding You to Wipe Login Page Contacts</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-viral-victory-restoring-your-facebook-space/"><u>[New] 2024 Approved  Viral Victory  Restoring Your Facebook Space</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-cutting-edge-photo-editing-the-top-10-apps-with-sweet-stickers/"><u>In 2024, Cutting-Edge Photo Editing  The Top 10 Apps with Sweet Stickers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-failed-file-creation-on-11-camera-app/"><u>Bypassing Failed File Creation on 11 Camera App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disguised-delayers-innocuous-apps-hindering-pc-speed/"><u>Disguised Delayers: Innocuous Apps Hindering PC Speed</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-efficiently-isolate-key-moments-in-youtube-footage/"><u>[New] In 2024, Efficiently Isolate Key Moments in YouTube Footage</u></a></li>
</ul></div>
