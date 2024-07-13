---
title: Reactivating Frozen Wastebin Symbol on Win11
date: 2024-07-12T17:34:14.666Z
updated: 2024-07-13T17:34:14.666Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reactivating Frozen Wastebin Symbol on Win11
excerpt: This Article Describes Reactivating Frozen Wastebin Symbol on Win11
keywords: Reactive Wastebin Fix -,Win11 Freeze Issue -,Symbol Reactivate Win11 -,Frozen Bin Icon Win10/Win11 -,Reformat Wastebin Image -,Revive Windows Wastebin -,Clearing Freeze Symbol Win11 -,Fix Frozen Bin Icon,Win11 Wastebin Issue,Reactivate Symbol Win11,Freeze Fix for Windows Bin,Restore Wastebin Image Win11,Revive Windows Bin Icon,Clear Symbol Issue Win11,Fix Frozen Bin -,Wastebin Win11 Fix -,Reactivate Icon Win -,Freeze Bin Issue Win -,Restore Symbol Win11 -,Revive Win Bins -,Clear Symb W11 -
thumbnail: https://thmb.techidaily.com/6658e9df1d38e14ee675787c7264985ccf523b4b4cb415efb9479f5287d0efcf.jpg
---

## Reactivating Frozen Wastebin Symbol on Win11

 The Recycle Bin has been a staple on Windows for a long time, but not everyone wants it on the desktop. You can disable it via the Desktop Icon Settings, but there is a bug where if you try to re-enable it, the "Recycle Bin" option is grayed out and cannot be toggled.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

## 1\. How to Bring Back the Recycle Bin Using the Group Policy Editor

 The Group Policy Editor lets you show or hide the Recycle Bin icon from the desktop. Check if you have modified and accidentally disabled the Recycle Bin group policy recently. If so you can set the Remove Recycle Bin icon from the desktop policy to "Not Configured" which will restore it.

 You may not find the Local Group Policy Editor in Windows Home Edition. However, you can run a batch script to [enable Group Policy Editor on the Windows Home edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) or skip to the Registry Editor-based fix in the next step.

 To restore the Recycle Bin icon using the Group Policy Editor:

1. Press **Win + R** to open **Run**.
2. Type **gpedit.msc** and click **OK** to open the **Group Policy Editor**.  
![gpedit msc windows 11 run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/gpedit-msc-windows-11-run.jpg)
3. Next, navigate to the following location:  
`User Configuration > Administrative Templates > Desktop`
4. In the right pane, locate and double-click on the **Remove Recycle Bin icon from the desktop** option to open its properties.  
![edit remove recycle bin icon from settings gpedit policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-remove-recycle-bin-icon-from-settings-gpedit-policy.jpg)
5. In the **Properties** dialog, select **Not Configured**.  
![edit remove recycle bin icon from settings gpedit policy not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-remove-recycle-bin-icon-from-settings-gpedit-policy-not-configured.jpg)
6. Click **Apply** and **OK** to save the changes.

 Close the Group Policy Editor and check your desktop to see if you can access the Recycle Bin. If not, make sure the Recycle Bin is set to show in Desktop Icon Settings.

 To enable Recycle Bin in Desktop Icon Settings:

1. Press **Win + I** to open **Settings**.
2. Next, open the **Personalization** tab in the left panel.
3. Click on **Themes**.  
![desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/desktop-icon-settings-windows-11.jpg)
4. Click on **Desktop icon settings** under the **Related settings** section.
5. In the **Desktop Icon Settings** dialog, select **Recycle Bin**.  
![enable recycle bin desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/enable-recycle-bin-desktop-icon-settings-windows-11.jpg)
6. Click **Apply** and **OK** to save the changes.

 If you can’t access Group Policy Editor or if the issue persists, you can use the Registry Editor to fix this problem.

## 2\. Modify the Recycle Bin Registry Settings

 Another way to resolve and restore the grayed-out Recycle Bin icon in the Desktop settings is via the Windows Registry. You can modify the registry entry value responsible for the settings and configurations of Recycle Bin working to restore the functionality.

 Making modifications to the Windows registry involves tweaking settings that may harm your device if performed incorrectly. We recommend you [create a Windows restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [take a Windows registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before attempting to modify the Windows registry.

 To modify the Recycle Bin registry value:

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK**. Click **Yes** if prompted by **User Account Control**.
3. In the Registry Editor, navigate to the following location. You can copy and paste the path in the editor for quicker navigation:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\NonEnum`
4. In the right pane, locate the **{645FF040-5081-101B-9F08-00AA002F954E}** DWORD (32-bit) value.  
![registry editor nonnum new dword value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value.jpg)
5. If it does not exist, you’ll need to create a new value. To do this, right-click on the **NonEnum** subkey folder in the left pane and select **New > DWORD (32-bit) Value**.
6. Rename the value as **{645FF040-5081-101B-9F08-00AA002F954E}**.
7. Next, double-click on the new DWORD value to open its properties.  
![registry editor nonnum new dword value edit 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value-edit-0.jpg)
8. Type **0** in the Value data field and click **OK** to save the changes.
9. Close Registry Editor and restart your computer. Sometimes, you’ll need to restart your computer for the new registry modifications to work.

 If the issue persists, try to [create a new user account with administrative rights](https://www.makeuseof.com/windows-11-create-local-user-account/), [perform a system restore](https://www.makeuseof.com/use-system-restore-windows/), or [repair corrupted Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

## Get Access to the Recycle Bin Desktop Icon Setting Again

 An incorrectly modified group policy can gray out the Recycle Bin icon in the Desktop Icon Settings dialog. Fortunately, it's an easy fix, and you should now have your Recycle Bin back to how you like it.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-info.techidaily.com/2023s-best-updated-lg-bp550-overview/"><u>2023'S Best  Updated LG BP550 Overview</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-ultimate-compilation-4-websites-for-ringtone-hunt/"><u>The Ultimate Compilation  4 Websites for Ringtone Hunt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719365401948-addressing-windows-printer-issues-a-guide-for-unresponsive-print-commands/"><u>Addressing Windows Printer Issues: A Guide for Unresponsive Print Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719361339925-solving-ms-to-do-discrepancies-no-sync-heres-how/"><u>Solving MS To-Do Discrepancies: No Sync? Here's How</u></a></li>
<li><a href="https://win11-tips.techidaily.com/directing-changes-to-user-profiles-in-w11-os/"><u>Directing Changes to User Profiles in W11 OS</u></a></li>
<li><a href="https://extra-information.techidaily.com/pixels-of-peaceful-bedtime-narratives/"><u>Pixels of Peaceful Bedtime Narratives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-efficient-language-switching-in-windows-11/"><u>A Guide to Efficient Language Switching in Windows 11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-optimize-game-console-audio-settings-on-sony-platforms/"><u>[New] Optimize Game Console Audio Settings on Sony Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-add-ons-for-disk-image-duality-on-pc/"><u>Avoiding Add-Ons for Disk Image Duality on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-methods-for-natively-creating-photo-carousel-on-windows-11/"><u>7 Methods for Natively Creating Photo Carousel on Windows 11</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-find-your-ideal-wedding-timer-on-android-and-ios-platforms-here/"><u>[Updated] Find Your Ideal Wedding Timer on Android & iOS Platforms Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-system-performance-with-effective-use-of-windows-law-filters/"><u>Elevating System Performance with Effective Use of Window's LAW Filters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719309134944-10-command-prompt-wonders-you-didnt-know/"><u>10 Command Prompt Wonders You Didn’t Know</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/reverse-the-ordinary-turning-images-upside-down/"><u>Reverse the Ordinary  Turning Images Upside Down</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-path-to-seamless-update-in-win11/"><u>Clearing Path to Seamless Update in Win11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/cant-play-mp4-files-on-motorola-moto-g-stylus-2023-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Can't play MP4 files on Motorola Moto G Stylus (2023)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-overcoming-permission-denied-messages-winos/"><u>A Guide to Overcoming 'Permission Denied' Messages, WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-the-frustration-of-inaccessible-windows-commands/"><u>Avoiding the Frustration of Inaccessible Windows Commands</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-audio-converter-face-off-top-6-contenders/"><u>2024 Approved Audio Converter Face-Off Top 6 Contenders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-excel-essential-productivity-software-for-professionals-on-windows/"><u>Efficiently Excel: Essential Productivity Software for Professionals on Windows</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-breaking-into-the-tiktok-livestream-realm-for-2024/"><u>[New] Breaking Into the TikTok Livestream Realm for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-instagram-edit-10-best-tools-unveiled/"><u>[New] 2024 Approved  Instagram Edit  10 Best Tools Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-window-shifts-gone-but-not-forgotten/"><u>6 Window Shifts: Gone But Not Forgotten</u></a></li>
<li><a href="https://win11-tips.techidaily.com/edge-off-your-windows-11-desktop/"><u>Edge Off Your Windows 11 Desktop</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-expert-tips-for-effective-pip-use-on-edge-browser/"><u>2024 Approved  Expert Tips for Effective PIP Use on Edge Browser</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719359080464-windows-11-note-saving-strategies-no-software/"><u>Windows 11 Note-Saving Strategies, No Software!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-the-superiority-of-pcs-to-macs-in-9-areas/"><u>Dissecting the Superiority of PCs to Macs in 9 Areas</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-finding-the-right-angle-for-your-fb-videos-for-2024/"><u>[New] Finding the Right Angle for Your FB Videos for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/how-to-use-cartoon-face-lens-in-snapchat/"><u>How to Use Cartoon Face Lens in Snapchat?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-reliable-clicks-and-movement-on-your-desktop/"><u>Ensuring Reliable Clicks & Movement on Your Desktop</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-learn-the-step-by-step-process-of-slowing-down-time-lapse-videos-on-your-iphone-for-2024/"><u>Updated Learn the Step-by-Step Process of Slowing Down Time-Lapse Videos on Your iPhone for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-swift-steps-for-word-definition-finder/"><u>7 Swift Steps for Word Definition Finder</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-writing-problems-on-windows-platforms/"><u>Eliminating Writing Problems on Windows Platforms</u></a></li>
<li><a href="https://video-capture.techidaily.com/streamline-your-screen-captures-with-4-methods-for-2024/"><u>Streamline Your Screen Captures with 4 Methods for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-the-leading-sources-for-easy-access-to-whoosh-soundscapes-and-their-uses/"><u>2024 Approved The Leading Sources for Easy Access to Whoosh Soundscapes and Their Uses</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/in-2024-the-top-10-online-resources-for-gaming-intro-design/"><u>In 2024, The Top 10 Online Resources for Gaming Intro Design</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/eco-effective-marketing-green-screens-and-cta-boosting-for-2024/"><u>Eco-Effective Marketing  Green Screens & CTA Boosting for 2024</u></a></li>
</ul></div>
