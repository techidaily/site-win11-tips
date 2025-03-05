---
title: Eliminate Windows Updates Prompts
date: 2025-02-27T20:43:07.580Z
updated: 2025-03-05T02:09:20.043Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminate Windows Updates Prompts
excerpt: This Article Describes Eliminate Windows Updates Prompts
keywords: Stop Update Alerts,Avoid Windows Prompt,Block Update Notifications,Remove Update Reminders,Disable WinUpdates,Quiet Update Warnings,Halt Updater Messages
thumbnail: https://thmb.techidaily.com/ebbfde368b81e7f396fe512ace44b149bef6fef394a1d6fd8cfa20e2c4a0b6c3.jpg
---

## Eliminate Windows Updates Prompts

 When an update is ready for installation, Windows notifies you and prompts you to restart your computer. As helpful as these reminders are, they can also be distracting at times. Fortunately, it’s possible to disable update notifications on Windows.

 You can disable Windows update notifications using the Settings app, Group Policy Editor, or Registry Editor. Let's go over each of these methods one by one.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Disable Windows Update Notifications via the Settings App

 The quickest way to disable update notifications on Windows is through the Settings app. Here are the steps for the same.

1. Press**Win + I** to open Windows Settings. You can also use any method we cover in[how to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Update & Security > Windows Update** .
3. Select**Advanced options** .
4. Disable the toggle for**Notify me when a restart is required to finish updating** .
5. Disable the toggle for**Get me up to date** so that Windows does not display a restart warning when an update is ready for installation.  
![Disable Windows Update Notifications Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-settings-app.jpg)

 Once you complete the above steps, Windows should not bother you with update notifications.

## 2\. Disable Windows Update Notifications Using Group Policy Editor

 Group Policy Editor is a powerful tool for configuring various settings on your Windows computer. If you have the Enterprise or Professional edition of Windows, you can disable update notifications using the Group Policy Editor. If you don't have either of those versions, read our guide on[how to access Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

To disable Windows update notifications using Group Policy Editor:

1. Press**Win + R** to open the Run dialog box.
2. Type**gpedit.msc** in the box and press**Enter** .
3. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Update > Manage end use experience.**
4. Double-click the**Display options for update notifications** policy on your right.
5. Select the**Disabled** option.
6. Click**Apply** followed by**OK** .  
![Disable Windows Update Notifications Using the Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-group-policy-editor-1.jpg)

 If you want to re-enable the Windows update notifications later, follow the same steps above and set the**Display options for update notifications** policy to**Not configured** .

## 3\. Disable Windows Update Notifications With Registry Editor

 If you can’t seem to access the Group Policy Editor for some reason, you can use the Registry Editor to disable update notifications.

 Since Registry Editor is a powerful tool that needs to be handled with care, we recommend that you back up all the registry files or create a restore point before proceeding with the changes below. If you need help, check our guides on[how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and[how to create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

To disable Windows update notifications using Registry Editor:

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the Registry Editor window, use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows** .
5. Locate the**WindowsUpdate** key. If you can’t find it, right-click on the**Windows** key and select**New > Key** . Rename the key as**WindowsUpdate** .
6. Right-click the**WindowsUpdate** key and select**New > DWORD (32-bit) Value** .
7. Rename the DWORD as**SetUpdateNotificationLevel** .
8. Double-click the newly created DWORD and change its**Value data** to**0** .
9. Click**OK** .  
![Disable Windows Update Notifications Using the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-registry-editor.jpg)

 Exit the Registry Editor window and restart your PC to apply the changes. Following that, Windows will not display update notifications on your computer.

## No More Update Notifications on Windows

 Windows updates are critical for the overall stability of your computer. That said, turning off Windows update notifications makes sense if you're not in a rush to install updates as soon as they are ready for installation.

 If you find Windows notifications to be distracting in general, you can use Focus Assist to silence all alerts and stay productive.

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
<li><a href="https://article-helps.techidaily.com/new-2024-approved-a-comprehensive-guide-accumulating-massive-amounts-of-tiktok-videos/"><u>[New] 2024 Approved A Comprehensive Guide Accumulating Massive Amounts of TikTok Videos</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-how-to-join-someones-live-on-tiktok-as-a-guest/"><u>[New] How To Join Someone’s Live on TikTok as a Guest</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/n-2024-highest-ranking-youtube-tracker-for-popular-video-insight/"><u>[New] In 2024, Highest-Ranking YouTube Tracker for Popular Video Insight</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-top-music-choices-for-captivating-video-experiences/"><u>[New] Top Music Choices for Captivating Video Experiences</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-bright-ideas-effective-lighting-in-vlogging/"><u>[Updated] Bright Ideas Effective Lighting in Vlogging</u></a></li>
<li><a href="https://discover-guides.techidaily.com/1728474442558-windows-11/"><u>详细解答：如何重新设定 Windows 11 的任务条布局</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-mac-with-windows-11-the-parallels-technique/"><u>Conquering Mac with Windows 11: The Parallels Technique</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-setup-positioning-quick-access-tools-in-win11-interface/"><u>Effortless Setup: Positioning Quick Access Tools in Win11 Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/end-the-extra-speed-deactivating-mouse-accel-on-windows-11/"><u>End the Extra Speed: Deactivating Mouse Accel on Windows 11</u></a></li>
<li><a href="https://driver-download.techidaily.com/get-the-latest-amd-radeon-rx-ebx-590-graphics-card-software-for-windows-pcs/"><u>Get the Latest AMD Radeon RX Ebx 590 Graphics Card Software for Windows PCs</u></a></li>
<li><a href="https://fox-links.techidaily.com/in-depth-insight-into-final-cut-pro-editing/"><u>In-Depth Insight Into Final Cut Pro Editing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-linux-side-of-windows-uninterrupted-by-win-11/"><u>Keeping Linux Side of Windows Uninterrupted by Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-rearranging-onedrive-storage-in-win10/"><u>Mastering the Art of Rearranging OneDrive Storage in Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-operational-failure-in-win11-code-0x0000011b/"><u>Overcoming Operational Failure in Win11 (Code 0X0000011B)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rerouting-to-reinstalled-microsoft-store-programs-on-pc/"><u>Rerouting to Reinstalled Microsoft Store Programs on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-your-favorite-feature-how-to-bring-back-photo-viewer-on-win11/"><u>Restore Your Favorite Feature: How to Bring Back Photo Viewer on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stuck-in-the-stream-7-ways-to-reopen-reluctant-websites-on-win-os/"><u>Stuck in the Stream? 7 Ways to Reopen Reluctant Websites on Win OS</u></a></li>
<li><a href="https://tech-revival.techidaily.com/what-is-claude-pro-and-how-does-it-compare-to-chatgpt-plus/"><u>What Is Claude Pro and How Does It Compare to ChatGPT Plus?</u></a></li>
<li><a href="https://fox-that.techidaily.com/whatsapp-zoom-bug-fixes-capturing-clearer-photos-and-videos/"><u>WhatsApp Zoom Bug Fixes: Capturing Clearer Photos and Videos</u></a></li>
</ul></div>

