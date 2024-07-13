---
title: Fixing Inactive Icons on the Desktop Bar
date: 2024-07-12T17:01:27.585Z
updated: 2024-07-13T17:01:27.585Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Inactive Icons on the Desktop Bar
excerpt: This Article Describes Fixing Inactive Icons on the Desktop Bar
keywords: Icon Activation Guide,Desktop Icons Fix,Revive PC Desktop,Reactivate Icons,Desktop Bar Troubleshoot,Reset Toolbar Icons,Fixed Icons Tips
thumbnail: https://thmb.techidaily.com/0e0ddc9d3f1e3fb1a939d99c12ca5daee2fa294d073b52247b8e64f5288cf09f.jpg
---

## Fixing Inactive Icons on the Desktop Bar

 Taskbar thumbnail previews usually enable you to see an app window’s content without maximizing it. However, some Windows 11/10 users have posted on help forums about thumbnail previews not working. When taskbar thumbnail previews aren’t working, they don’t appear when users hover their cursors over minimized windows.

 This issue often arises when users have multiple windows open for apps. Consequently, users only see text labels for minimized window titles. Does a similar thing happen when you try to view taskbar previews? If so, this is how you can fix taskbar thumbnail previews not working on Windows 11/10 PCs.

## 1\. Restart File Explorer’s Process

 The File Explorer process handles the taskbar and many other Windows UI elements. So, restarting that process is a good place to start with troubleshooting this taskbar thumbnail preview issue. Doing so can address File Explorer glitches that could be causing the issue.

 You can restart File Explorer on the **Processes** tab inside Task Manager. Right-click the Windows Explorer process there and select **Restart**. Check out this guide to [restarting File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) for further instructions if needed.

![The Restart button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/restart-button.jpg)

## 2\. Repair System Files

 It’s usually recommended to try repairing system files whenever a Windows function isn’t working right. In this case, taskbar window previews aren’t working correctly. Running a System File Checker scan might repair corrupted system files causing this issue. Our [how to run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide provides guidelines for utilizing the SFC command-line tool.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/sfc-scannow.jpg)

## 3\. Edit the Taskband and Advanced Registry Keys

 Editing the Taskbar registry key is a widely confirmed solution for fixing taskbar thumbnail previews not working. This potential resolution will fix the **NumThumbnails** DWORD in that key, which might be deleted or incorrectly set. That DWORD sets the maximum number of taskbar thumbnail previews for a single minimized window. This is how you should edit the **Taskband** registry key:

1. Click the magnifying glass or file finder text box on the Windows 11/10 taskbar and input a **regedit** search term.
2. Select the **Registry Editor** search result to access that utility.
3. Go to the **Taskbar** key by inputting this location in the registry address bar:  
`Computer\HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Taskband`
4. If you can’t see a **NumThumbnails** DWORD, right-click the **Taskbar** key in Registry Editor’s sidebar and select **New** \> **DWORD**.  
![The New > DWORD option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-dword-options.jpg)
5. Enter **NumThumbnails** inside the DWORD name text box.
6. Double-click the **NumThumbnails** DWORD.  
![The NumThumbnails DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/numthumbnails-dword.jpg)
7. If that **DWORD** is set at **0**, erase that number and input **10** in the **Value** box.  
![The Edit DWORD (32-bit) Value window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/edit-dword-window3.jpg)
8. Click **OK** to set the new **NumThumbnails** value.
9. Restart Windows 11/10 (or restart File Explorer) for this registry tweak to take effect.

 You might also need to delete a **DisablePreviewWindow** or **DisablePreviewDesktop** DWORD in the **Advanced** registry key to fix taskbar thumbnail previews not working. To do so, right-click the **DisablePreviewWindow** or **DisablePreviewDesktop** DWORD in the **Advanced** key and select **Delete** \> **Yes**. The registry location of the **Advanced** key is:

`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`

## 4\. Disable the Turn Off Taskbar Thumbnails Policy Setting

 Group Policy Editor includes a policy setting for disabling taskbar thumbnail policies. If you’re a Windows 11/10 Pro or Enterprise user, check that policy to make sure it’s not set to disable taskbar thumbnail previews. You can disable the **Turn off taskbar thumbnails** policy as follows:

1. [Open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) window by pressing the **Windows key + R** keyboard shortcut, inputting **gpedit.msc**, and selecting Run’s **OK** option.
2. Double-click **User Configuration** \> **Administrative Templates** \> **Start menu and taskbar** in the navigation sidebar.  
![The Local Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/local-group-policy-editor.jpg)
3. Next, double-click **Turn off taskbar thumbnails** to access configuration options for that policy.
4. Click the **Disabled** or **Not Configured** option.  
![The Turn off taskbar thumbnail window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/turn-off-windows-taskbar-window.jpg)
5. Select **Apply** \> **OK** to disable the **Turn off taskbar thumbnails** policy as configured.

## 5\. Roll Windows Back With a System Restoration Point

 If you have System Restore enabled, that could be a useful troubleshooting tool for fixing taskbar thumbnail previews not working. Restoring Windows to a date when your taskbar window previews worked might undo background changes that caused the issue. However, this will only work if you can select a suitable restore point that predates the issue.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/system-restore-tool.jpg)

 You can roll back Windows by following the instructions in this guide to [utilizing System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/). Applying this potential solution will remove software packages installed after the date of the selected restore point. This will mean some reinstallation of software will probably be necessary after rolling back Windows.

## Get Your Taskbar Thumbnail Previews Fixed

 Taskbar thumbnail previews may not be the most essential feature, but many users will undoubtedly miss them when they’re not working. Applying the troubleshooting methods in this guide will usually get the Windows 11/10 taskbar thumbnails working again in most cases. So, give them a try if you can’t view taskbar thumbnail previews for minimized windows.

 This issue often arises when users have multiple windows open for apps. Consequently, users only see text labels for minimized window titles. Does a similar thing happen when you try to view taskbar previews? If so, this is how you can fix taskbar thumbnail previews not working on Windows 11/10 PCs.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-11-installation-on-unsupported-hardware/"><u>Tackling Windows 11 Installation on Unsupported Hardware</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-storage-4-methods-to-tap-into-windows-11s-disk-manager/"><u>Streamline Storage: 4 Methods to Tap Into Windows 11'S Disk Manager</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-navigating-the-nuances-zooming-in-on-roblox/"><u>2024 Approved  Navigating the Nuances  Zooming In on Roblox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-recover-from-failed-discord-games-detection-on-windows/"><u>Steps to Recover From Failed Discord Games Detection on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/smooth-sailing-with-these-fixes-for-windows-update/"><u>Smooth Sailing with These Fixes for Windows Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-file-tracking-the-ultimate-guide-to-copying-windows-11-filesystem-trails-6-methods/"><u>Winning at File Tracking: The Ultimate Guide to Copying Windows 11 Filesystem Trails (6 Methods)</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-leading-discord-automated-friends/"><u>2024 Approved  Leading Discord Automated Friends</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eject-incompatible-setup-warnings-in-win11/"><u>Eject Incompatible Setup Warnings in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-system-performance-by-adding-disk-space-analyzer-tool/"><u>Streamline System Performance by Adding Disk Space Analyzer Tool</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/pro-tips-for-captivating-vr-videos-top-9-strategies-for-2024/"><u>Pro Tips for Captivating VR Videos  Top 9 Strategies for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tracking-and-tallying-windows-app-sizes/"><u>Tracking and Tallying Windows App Sizes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-slow-windows-10-closure-while-tasks-remain-open/"><u>Strategies for Slow Windows 10 Closure While Tasks Remain Open</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-pioneering-vlogging-tech-our-ranking-of-top-12-video-cameras/"><u>In 2024, Pioneering Vlogging Tech  Our Ranking of Top 12 Video Cameras</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-enhance-your-streaming-experience-amazon-prime-video-aspect-ratio-guide/"><u>Updated In 2024, Enhance Your Streaming Experience Amazon Prime Video Aspect Ratio Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-blue-screen-0xc0000001-on-pc/"><u>Tackling Blue Screen 0xC0000001 on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-the-secrets-of-windows-iscsi-initiator-accessibility/"><u>Uncovering the Secrets of Windows iSCSI Initiator Accessibility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disable-default-settings-keep-your-usb-running-on-windows-11/"><u>Disable Default Settings - Keep Your USB Running on Windows 11</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/viral-beats-cutting-edge-music-for-youtube-short-videos/"><u>Viral Beats  Cutting-Edge Music for YouTube Short Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-temporary-file-hassles-resolved-instantly/"><u>Windows' Temporary File Hassles Resolved Instantly</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-secrets-of-editing-numerical-data-in-tiktoks/"><u>The Secrets of Editing Numerical Data in TikToks</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-amplify-views-on-tiktok-with-these-standout-username-concepts/"><u>2024 Approved  Amplify Views on TikTok with These Standout Username Concepts</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/from-inconsistent-exports-securing-smooth-srt-outputs-for-2024/"><u>From Inconsistent Exports  Securing Smooth SRT Outputs for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-skip-out-of-s-mode-with-ease-for-your-pc/"><u>Swiftly Skip Out of S Mode with Ease for Your PC</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-solutions-to-find-your-samsung-galaxy-m34-5g-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Solutions to Find Your Samsung Galaxy M34 5G Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-9-methods-to-control-volume-levels-in-windows-11/"><u>Unlock 9 Methods to Control Volume Levels in Windows 11</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-best-flv-editor-for-windows-8-effortless-video-editing-software/"><u>Updated Best FLV Editor for Windows 8 Effortless Video Editing Software</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-optimize-sound-clarity-top-audio-interface-recommendations/"><u>In 2024, Optimize Sound Clarity  Top Audio Interface Recommendations</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-expanding-possibilities-with-virtual-reality/"><u>[Updated] Expanding Possibilities with Virtual Reality</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-ways-to-track-oneplus-nord-n30-se-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Track OnePlus Nord N30 SE without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-the-ultimate-list-of-free-mkv-cutting-software-for-2024/"><u>New The Ultimate List of Free MKV Cutting Software for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-accessing-global-events-facebook-live-on-roku-devices/"><u>2024 Approved  Accessing Global Events  Facebook Live on Roku Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-broken-disk-organization-in-os/"><u>Addressing Broken Disk Organization in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-webp-visualization-with-these-excellent-tools/"><u>Enhance WebP Visualization with These Excellent Tools</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-benq-bl2711u-the-artisans-choice-for-high-end-4k-display-enthusiasts/"><u>[Updated] 2024 Approved  BenQ BL2711U - The Artisan's Choice for High-End 4K Display Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-solve-systemsettings-issue-on-win11/"><u>Strategies to Solve SystemSettings Issue on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-woes-8-strategies-for-neutralizing-pink-displays/"><u>Windows Woes: 8 Strategies for Neutralizing Pink Displays</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-the-heart-of-your-system-pc-manager-for-w11/"><u>Configuring the Heart of Your System: PC Manager for W11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-sony-game-systems-redefine-your-gaming-soundscape/"><u>In 2024, Sony Game Systems  Redefine Your Gaming Soundscape</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-more-than-one-antivirus-isnt-ideal-for-windows-users/"><u>Why More Than One Antivirus Isn't Ideal for Windows Users</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-maximize-impact-best-practices-for-fb-video-posts/"><u>[Updated] In 2024, Maximize Impact  Best Practices for FB Video Posts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-efficiency-with-these-5-must-have-apps-on-windows-11/"><u>Enhance Efficiency with These 5 Must-Have Apps on Windows 11</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-dual-performance-the-tiktok-duet-trend-for-2024/"><u>[New] Dual Performance  The TikTok Duet Trend for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-unlock-easy-audio-modification-with-these-7-free-online-apps-for-2024/"><u>Updated Unlock Easy Audio Modification with These 7 Free Online Apps for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-methods-for-windows-easy-access-center-entry/"><u>5 Methods for Windows Easy Access Center Entry</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-15-pro-max-to-other-iphone-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 15 Pro Max To Other iPhone devices? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-to-stop-unpredictable-printer-changes/"><u>Tactics to Stop Unpredictable Printer Changes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-connecting-win-product-code-and-microsoft-accounts/"><u>Tips for Connecting WIN PRODUCT CODE & MICROSOFT ACCOUNTS</u></a></li>
<li><a href="https://youtube-help.techidaily.com/examining-the-economic-impact-of-mr-beast-for-2024/"><u>Examining the Economic Impact of Mr. Beast for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-rapid-switching-on-win-11-desktop/"><u>Tips for Rapid Switching on Win 11 Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-spontaneous-file-explorer-opens/"><u>Disabling Spontaneous File Explorer Opens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/selective-vmm-recommendations-for-windows-11-success/"><u>Selective VMM Recommendations for Windows 11 Success</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-next-gen-editing-with-movavi-pro-video-2024/"><u>[New] Next-Gen Editing with Movavi Pro Video 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-in-2024-perfecti-top-photo-and-video-display-programming/"><u>[New] In 2024, Perfecti  Top Photo & Video Display Programming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-playnite-with-emulated-game-support/"><u>Upgrade Playnite with Emulated Game Support</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-planning-to-use-a-pokemon-go-joystick-on-xiaomi-redmi-a2-drfone-by-drfone-virtual-android/"><u>In 2024, Planning to Use a Pokemon Go Joystick on Xiaomi Redmi A2? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-secure-your-browsing-with-microsofts-defender-in-win-11/"><u>Step-by-Step: Secure Your Browsing with Microsoft's Defender in Win 11</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-expertly-navigate-the-cloud-of-content-with-best-screen-recording-tools-for-2024/"><u>[Updated] Expertly Navigate the Cloud of Content with Best Screen Recording Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switchtonightvisioninnotepadwin/"><u>SwitchToNightVisionInNotepadWin</u></a></li>
</ul></div>
