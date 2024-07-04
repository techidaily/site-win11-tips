---
title: Fixing Inactive Icons on the Desktop Bar
date: 2024-06-25T16:33:47.815Z
updated: 2024-06-26T16:33:47.815Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/minimizing-overheat-during-intense-play/"><u>Minimizing Overheat During Intense Play</u></a></li>
<li><a href="https://win11-tips.techidaily.com/practical-guide-to-disregarding-false-security-alarms-in-chrome/"><u>Practical Guide to Disregarding False Security Alarms in Chrome</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-troubleshooting-for-elusive-temp-files/"><u>Windows Troubleshooting for Elusive Temp Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-flush-the-steam-dns-cache-on-windows/"><u>How to Flush the Steam DNS Cache on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solutions-for-windows-11s-0x8004def5-glitches/"><u>Swift Solutions for Windows 11'S 0X8004DEF5 Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lightning-bloatware-eradication-for-your-win11-system/"><u>Lightning Bloatware Eradication for Your Win11 System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-pc-gaming-with-yuzu-on-windows/"><u>Skyrocket PC Gaming with Yuzu on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easing-up-microsoft-store-restrictions-on-windows-11/"><u>Easing Up Microsoft Store Restrictions on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-search-on-windows-11-the-top-5-must-knows/"><u>Elevating Search on Windows 11: The Top 5 Must-Knows</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-capturing-attention-on-tiktok-must-use-tagging-techniques/"><u>[New] 2024 Approved  Capturing Attention on TikTok  Must-Use Tagging Techniques</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-joining-the-digital-dialogue-facebook-basics/"><u>[New] Joining the Digital Dialogue (Facebook Basics)</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-why-is-ipogo-not-working-on-xiaomi-redmi-a2plus-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, Why is iPogo not working On Xiaomi Redmi A2+? Fixed | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/most-reliable-platforms-to-gather-video-intro-templates-for-2024/"><u>Most Reliable Platforms to Gather Video Intro Templates for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-best-tools-to-hard-reset-infinix-hot-30-5g-drfone-by-drfone-reset-android-reset-android/"><u>3 Best Tools to Hard Reset Infinix Hot 30 5G | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-the-ultimate-list-of-trending-instagram-hashtags-for-success/"><u>[Updated] In 2024, The Ultimate List of Trending Instagram Hashtags for Success</u></a></li>
<li><a href="https://extra-tips.techidaily.com/spotify-advertisement-made-easy-tips-and-tricks/"><u>Spotify Advertisement Made Easy  Tips and Tricks</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-elevate-your-tiktok-presence-with-powerful-slow-motion-techniques/"><u>2024 Approved  Elevate Your TikTok Presence with Powerful Slow Motion Techniques</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-from-capture-to-share-expert-insights-into-screen-recording-software/"><u>[New] In 2024, From Capture to Share  Expert Insights Into Screen Recording Software</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-beam-your-best-selecting-the-stirring-photos-on-instagram/"><u>2024 Approved  Beam Your Best  Selecting the Stirring Photos on Instagram</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>