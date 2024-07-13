---
title: Correcting Taskbar Icons that Don't Pop Up
date: 2024-07-12T17:31:32.938Z
updated: 2024-07-13T17:31:32.938Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Taskbar Icons that Don't Pop Up
excerpt: This Article Describes Correcting Taskbar Icons that Don't Pop Up
keywords: Fix Taskbar Icons,Taskbar Icon Fix,Popping Taskbar Icons,Taskbar Pop-Up Issue,Adjusting Taskbar Items,Rectify Taskbar Display,Taskbar Icon Visibility
thumbnail: https://thmb.techidaily.com/fa51da89f91ea3306806b0c92d6d119cfa0eae393a63e41c230a883a3e7c64cd.jpg
---

## Correcting Taskbar Icons that Don't Pop Up

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
<li><a href="https://win11-tips.techidaily.com/sharpening-up-discord-response-time-on-windows-devices/"><u>Sharpening Up Discord Response Time on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-this-device-is-being-used-by-someone-else-in-sound/"><u>Resolving 'This Device Is Being Used By Someone Else' In Sound</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/how-to-become-a-youtube-partner/"><u>How to Become A YouTube Partner</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-your-pubg-saved-data-in-windows-1110/"><u>Reviving Your PUBG Saved Data in Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/propel-productivity-the-top-6-win-tracking-software-choices/"><u>Propel Productivity: The Top 6 Win Tracking Software Choices</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-your-ultimate-companion-for-mastering-mov-recordings-on-windows-10/"><u>[Updated] In 2024, Your Ultimate Companion for Mastering MOV Recordings on Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-stalled-amd-driver-in-windows-environment/"><u>Remedying Stalled AMD Driver in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secrets-to-always-seeing-your-sticky-notes-in-windows/"><u>Secrets to Always Seeing Your Sticky Notes in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-new-horizons-upgrading-old-pcs-to-22h2/"><u>Navigating New Horizons: Upgrading Old PCs to 22H2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-xbox-game-pass-fatal-error-code-0-on-windows-11/"><u>Resolving Xbox Game Pass Fatal Error Code 0 on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-printer-connectivity-in-windows-os/"><u>Restoring Printer Connectivity in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/install-update-and-remove-with-precision-using-windows-package-manager/"><u>Install, Update & Remove with Precision Using Windows Package Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-resolving-error-0xc00000f-in-windows-pcs/"><u>Understanding and Resolving Error 0Xc00000f in Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-error-code-0x800713f-windows-11s-mail-woes/"><u>Unraveling Error Code 0X800713F: Windows 11'S Mail Woes</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-snapchat-profitability-techniques/"><u>[Updated] 2024 Approved  Snapchat Profitability Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-file-download-problems-in-windows/"><u>Strategies to Overcome File Download Problems in WIndows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-activate-hyper-v-in-windows-11/"><u>Quick Guide to Activate Hyper-V in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-with-ease-your-guide-to-windows-11-audio-control/"><u>Navigating with Ease: Your Guide to Windows 11 Audio Control</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-premium-collection-expert-tiktok-downloader-tools/"><u>In 2024, Premium Collection  Expert TikTok Downloader Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-power-of-in-hand-typing-enable-steps-on-windows/"><u>Unlock the Power of In-Hand Typing: Enable Steps on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sync-success-reestablishing-obs-studio-server-connection-in-win/"><u>Sync Success: Reestablishing OBS Studio Server Connection in Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trim-down-warmup-latency-top-tips-for-a-quicker-boot-up/"><u>Trim Down Warmup Latency – Top Tips for a Quicker Boot-Up</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-addressing-windows-update-errors/"><u>Step-by-Step: Addressing Windows Update Errors</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-quick-youtube-revenue-assessments-available/"><u>2024 Approved  Quick YouTube Revenue Assessments Available</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-zero-cost-youtube-meetings-easy-to-host/"><u>[Updated] 2024 Approved  Zero Cost Youtube Meetings  Easy to Host</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reconnecting-lost-window-pans-in-windows-11/"><u>Reconnecting Lost Window Pans in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rearrange-screen-alignment-for-windows-users/"><u>Rearrange Screen Alignment for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlink-others-login-on-win-11/"><u>Unlink Others' Login on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reimagining-the-clipboard-in-windows-11-with-user-centric-features/"><u>Reimagining the Clipboard in Windows 11 with User-Centric Features</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-harnessing-the-power-of-imagery-for-engaging-fb-slideshows/"><u>[Updated] 2024 Approved  Harnessing the Power of Imagery for Engaging FB Slideshows</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-twitvid-mastery-your-go-to-resource-for-video-downloads/"><u>2024 Approved  TwitVid Mastery  Your Go-To Resource for Video Downloads</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/how-to-make-a-slideshow-with-icecream-slideshow-maker-for-2024/"><u>How to Make a Slideshow with Icecream Slideshow Maker for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-crafting-a-viral-phenomenon-on-igtv-with-savvy-hash-tags/"><u>2024 Approved  Crafting a Viral Phenomenon on IGTV with Savvy Hash Tags</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-taskbar-in-windows-11/"><u>Tailoring Your Taskbar in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-swiftly-show-and-hide-directories-on-windows-11-pcs/"><u>Tips for Swiftly Show & Hide Directories on Windows 11 PCs</u></a></li>
<li><a href="https://extra-skills.techidaily.com/prime-microphones-for-high-resolution-4k-video-shooting-for-2024/"><u>Prime Microphones for High-Resolution 4K Video Shooting for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/post-update-failure-navigating-disconnect-in-windows-discord/"><u>Post-Update Failure: Navigating Disconnect in Windows Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-6-windows-to-dos-optimal-apps-compared/"><u>Top 6 Windows To-Dos: Optimal Apps Compared</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reestablishing-usb-connection-in-windows-11/"><u>Reestablishing USB Connection in Windows 11</u></a></li>
</ul></div>
