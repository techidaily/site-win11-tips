---
title: Stops Repeated Edge Icons on Workspace
date: 2024-07-12T16:58:46.697Z
updated: 2024-07-13T16:58:46.697Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stops Repeated Edge Icons on Workspace
excerpt: This Article Describes Stops Repeated Edge Icons on Workspace
keywords: Stop Edge Icon Repetition,Avoiding Icon Cloning,Preventing Icons Overlap,Unique Workspace Imagery,No Repeat Edges Displayed,Cleaner Workspace Design,Remove Repeated Visuals
thumbnail: https://thmb.techidaily.com/3c44f0be88269dfe58e87652a332c52a578262780df7f0b33d89646c55a92321.jpg
---

## Stops Repeated Edge Icons on Workspace

 Does Windows keep showing the Microsoft Edge shortcut on your desktop even after you delete it? Don’t worry, your computer hasn't been compromised. Several users have shared their experiences of Windows automatically generating the Edge shortcut after a system restart or update.

 Fortunately, there's no requirement to manually delete the Edge desktop shortcut repeatedly. Here are some helpful tips that should help resolve the issue in no time.

## 1\. Prevent Microsoft Edge From Opening at Startup

 By default, Microsoft Edge runs every time you start your Windows computer. Several users on the Microsoft forums reported fixing this particular issue by preventing Microsoft Edge from opening at startup. Hence, it’s the first thing you should try.

 You can use Task Manager to review all the apps that are configured to run at boot and disable Edge from there. Here are the steps you can follow:

1. Press **Win + X** to open the Power User menu.
2. Select **Task Manager** from the resulting menu.
3. Select **Startup apps** from the left pane.
4. Locate and select **Microsoft Edge** on the list. Right-click on it and select **Disabled** from the context menu.  
![Startup Apps in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Startup-Apps-in-Task-Manager.jpg)

 Additionally, you should also [access the startup folder on your Windows PC](https://www.makeuseof.com/access-startup-folder-windows/) and delete any shortcuts labeled Microsoft Edge.

## 2\. Edit Registry Files

 Another way to prevent the Microsoft Edge shortcut from reappearing on your desktop involves editing registry files.

 Making incorrect changes to the registry files can cause serious damage to your system. Hence, it’s a good idea to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

 Even if you are familiar with the registry editor, make sure you follow the steps carefully to [avoid accidentally messing up the Windows registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/).

 Use the following instructions:

1. Press **Win + R** to open the Run dialog box.
2. Type **regedit** in the text box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft**.
5. Right-click on the **Microsoft** key and select **New > Key**. Name it **EdgeUpdate**.
6. Right-click on the **EdgeUpdate** key and select **New > DWORD (32-bit) Value**. Rename it **CreateDesktopShortcutDefault**.
7. Double-click the newly created DWORD and enter **0** in the Value data field. Then, click **OK**.
8. Within the **EdgeUpdate** key, create another DWORD and name it **RemoveDesktopShortcutDefault**.
9. Double-click the **RemoveDesktopShortcutDefault** DWORD and enter **0** in the Value data field.
10. Click **OK**.  
![EdgeUpdate Key in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edgeupdate-key-in-registry.jpg)

 Close the Registry Editor window and restart your PC. After that, check if the issue is resolved.

## 3\. Modify Group Policy Settings

 If the issue remains even after you edit registry files, you can try modifying the group policy settings.

 The Group Policy Editor is only available in the Professional, Education, or Enterprise editions of Windows. That said, you can [access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) with a simple workaround.

 Follow these steps to modify Group Policy settings:

1. Press **Win + S** to open the search menu.
2. Type **gpedit.msc** in the search box and press **Enter**.
3. Select **Yes** if the User Account Control (UAC) prompt appears.
4. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Components > Microsoft Edge**.
5. Double-click the **Allow Microsoft Edge to pre-launch at Windows startup, when the system is idle, and each time Microsoft Edge is closed** policy in the right pane.
6. Select the **Disabled** option.  
![Microsoft Edge pre-launch policy selected in the Local Group Policy Editor Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Local-Group-Policy-Editor-Window.jpg)
7. Hit Apply followed by **OK**.
8. Similarly, disable the **Allow Microsoft Edge to start and load the Start and New Tab page at Windows startup, and each time Microsoft Edge is closed** policy as well.

 Restart your PC one more time and check if the issue is resolved.

## 4\. Remove Microsoft Edge as the Default Browser

 Another reason why the Microsoft Edge shortcut may keep showing up on your Windows desktop is if you have set it as the default browser.

 Try [changing the default browser on your Windows PC](https://www.makeuseof.com/windows-11-change-default-browser/) to something other than Microsoft Edge and see if that fixes the issue.

 If you need help picking a reliable browser, you can check out [the best browsers for Windows](https://www.makeuseof.com/windows-11-best-browsers/).

## 5\. Restrict Other Users From Creating Desktop Shortcuts

 If you share your computer with others, someone else may be creating shortcuts for Edge without your permission. If you don't want this to happen, you can use the Group Policy Editor to prevent other users from creating desktop shortcuts.

 Here are the steps for the same:

1. Click the search icon on the taskbar to access the search menu.
2. Type **edit group policy** or **gpedit** in the search box and select the first result that appears.
3. Use the left pane to navigate to **User Configuration > Administrative Templates > Control Panel > Personalization**.
4. Double-click on the **Prevent changing desktop icons** policy in the right pane.
5. Select the **Enabled** option.
6. Click **Apply** and then **OK**.  
![Using the Local Group Policy to Prevent Others From Changing Desktop Icons](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-the-Local-Group-Policy-to-Prevent-Others-From-Changing-Desktop-Icons.jpg)

 And that's about it. Once you make the above changes, the other users won't be able to create, modify, or delete your desktop icons.

## 6\. Review Scheduled Tasks

 It is possible that a scheduled task is causing Windows to create a desktop shortcut for Edge repeatedly. To check for this possibility, you need to review tasks in the Task Scheduler app.

 Use these steps to check automated tasks in Task Scheduler:

1. Right-click on the **Start icon** and select **Run** from the menu that appears.
2. Type **taskschd.msc** in the box and press **Enter** to open the Task Scheduler app.
3. Select **Task Scheduler Library** in the left pane to view a list of tasks in the middle pane.
4. Locate and select any Edge-related tasks.
5. Click the **Disable** option in the right pane.  
![An Automated task selected in the Task Scheduler window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Task-Scheduler-Window.jpg)

 Further, you can [restrict others from creating and running tasks in the Task Scheduler app](https://www.makeuseof.com/windows-block-task-manager/) by modifying the group policy settings or the registry files.

## 7\. Uninstall Microsoft Edge From Your PC

 If none of the above tips help, you can consider uninstalling Microsoft Edge to fix the problem. This can be useful if Microsoft Edge isn’t your preferred browser anyway.

 Use Command Prompt or PowerShell to [uninstall Microsoft Edge from your Windows computer](https://www.makeuseof.com/windows-11-uninstall-microsoft-edge/). Once you remove the browser, the issue should be resolved.

## Prevent Microsoft Edge From Appearing on Your Desktop

 It can be confusing if Microsoft Edge’s shortcut keeps appearing on your desktop for no apparent reason. Hopefully, one of the above-mentioned fixes has helped fix the issue for good, and you are at peace.

 Does your Windows desktop look like a jumbled mess? If so, you can easily organize it by grouping desktop shortcut icons with a third-party program.

 Fortunately, there's no requirement to manually delete the Edge desktop shortcut repeatedly. Here are some helpful tips that should help resolve the issue in no time.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://android-unlock.techidaily.com/how-to-change-lava-yuva-2-pro-lock-screen-password-by-drfone-android/"><u>How To Change Lava Yuva 2 Pro Lock Screen Password?</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-windows-videophone-apps-the-ultimate-7-1/"><u>[Updated] 2024 Approved  Windows Videophone Apps  The Ultimate #7-#1</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explaining-and-mending-error-code-0x8007251d-a-guide/"><u>Explaining and Mending Error Code 0X8007251d: A Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-method-for-deleting-steam-dns-from-windows-os/"><u>Efficient Method for Deleting Steam DNS From Windows OS</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/audiovisual-excellence-unlocked-a-review-of-avs-editors-innovative-features-and-related-comparisons/"><u>Audiovisual Excellence Unlocked – A Review of AVS Editors Innovative Features & Related Comparisons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-your-battlenet-downloads-win-pc-style/"><u>Boosting Your Battle.net Downloads, Win-PC Style</u></a></li>
<li><a href="https://android-location-track.techidaily.com/5-ways-to-track-tecno-phantom-v-fold-without-app-drfone-by-drfone-virtual-android/"><u>5 Ways to Track Tecno Phantom V Fold without App | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-8-engaging-exercise-routines-for-active-viewership/"><u>In 2024, 8 Engaging Exercise Routines for Active Viewership</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-top-10-instagram-grid-makers-to-create-visually-appealing-grids/"><u>[New] 2024 Approved  Top 10 Instagram Grid Makers to Create Visually Appealing Grids</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-minimize-malware-scanners-cpuram-demands/"><u>How to Minimize Malware Scanner's CPU/RAM Demands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-cortana-assistance-feature/"><u>Eliminate Cortana Assistance Feature</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/learn-the-art-of-crafting-short-youtube-videos/"><u>Learn the Art of Crafting Short YouTube Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-solve-media-creator-tool-errors-winerror-0x8007043c/"><u>How to Solve Media Creator Tool Errors: WinError 0X8007043C</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-analysis-process-sorting-and-theme-customization-in-windows-11/"><u>In-Depth Analysis: Process Sorting and Theme Customization in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-hyper-v-in-windows-11/"><u>How to Enable Hyper-V in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-default-cmd-settings-with-ease/"><u>Altering Default CMD Settings with Ease</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/tactics-for-textural-image-modification/"><u>Tactics for Textural Image Modification</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-crash-of-windows-update-error-x712/"><u>Fixing the Crash of Windows Update Error X712</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-ace-trackers-our-top-five-games/"><u>In 2024, Ace Trackers  Our Top Five Games</u></a></li>
<li><a href="https://extra-hints.techidaily.com/elite-srs-conversions-maximum-benefits-for-tech-enthusiasts/"><u>Elite SRS Conversions  Maximum Benefits for Tech Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-correction-resetting-folders-on-a-ws11-pc/"><u>Immediate Correction: Resetting Folders on a WS11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-error-code-31-in-windows-os/"><u>Mastering the Art of Fixing Error Code 31 in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/implementing-windows-11-parental-control-measures/"><u>Implementing Windows 11 Parental Control Measures</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-stolen-iphone-6s-in-different-conditionsin-by-drfone-ios/"><u>In 2024, How To Unlock Stolen iPhone 6s In Different Conditionsin</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-ultimate-actions-replay-analysis/"><u>[Updated] Ultimate Actions Replay Analysis</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-stay-ahead-of-the-curve-top-task-filled-ideas-for-maximizing-your-podcast-experience/"><u>In 2024, Stay Ahead of the Curve  Top Task-Filled Ideas for Maximizing Your Podcast Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-recognized-hdd-problems-in-a-step-by-step-windows-11-process/"><u>Fixing Non-Recognized HDD Problems in a Step-by-Step Windows 11 Process</u></a></li>
<li><a href="https://extra-information.techidaily.com/communication-mastery-for-impactful-interviews/"><u>Communication Mastery  For Impactful Interviews</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevated-operations-consistent-admin-mode-for-terminal/"><u>Elevated Operations: Consistent Admin Mode for Terminal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-there-are-no-more-files-error-on-windows-10-and-11/"><u>How to Fix the “There Are No More Files” Error on Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-flushed-to-functional-8-steps-for-desktop-color-correction/"><u>From Flushed to Functional: 8 Steps for Desktop Color Correction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-recordings-best-no-fee-windows-editors/"><u>Master Your Recordings: Best No-Fee Windows Editors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-install-unsupported-windows-packages/"><u>Guidelines to Install Unsupported Windows Packages</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-rapid-releases-review-best-quick-gaming-selections/"><u>[New] Rapid Releases Review  Best Quick Gaming Selections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-key-steps-to-restore-mail-alert-functionality-in-windows/"><u>9 Key Steps to Restore Mail Alert Functionality in Windows</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-muting-background-noise-in-skype-sessions/"><u>[Updated] 2024 Approved  Muting Background Noise in Skype Sessions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/handling-utorrent-installation-hiccups-in-windows-78/"><u>Handling uTorrent Installation Hiccups in Windows 7/8</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-life360-on-windows-pc-for-apple-iphone-6-drfone-by-drfone-virtual-ios/"><u>How to Use Life360 on Windows PC For Apple iPhone 6? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-experience-locate-the-lost-feature-in-windows-11/"><u>Enhance Your Experience: Locate the Lost Feature in Windows 11</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-unmatched-performance-1-4k-gaming-laptops/"><u>In 2024, Unmatched Performance  #1 4K Gaming Laptops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/examining-utility-windows-reliability-and-performance-monitors/"><u>Examining Utility: Windows' Reliability & Performance Monitors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-intelligence-microsofts-new-ai-helper-for-windows-11-taskbar/"><u>Integrating Intelligence: Microsoft's New AI Helper for Windows 11 Taskbar</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-guide-to-acquiring-free-picture-frame-videos/"><u>2024 Approved  Guide to Acquiring Free Picture Frame Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-directory-size-a-powershell-approach/"><u>Dissecting Directory Size: A PowerShell Approach</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-3-easy-methods-to-unlock-icloud-locked-apple-iphone-14-plusipadipod-by-drfone-ios/"><u>In 2024, 3 Easy Methods to Unlock iCloud Locked Apple iPhone 14 Plus/iPad/iPod</u></a></li>
<li><a href="https://howto.techidaily.com/fixes-for-apps-keep-crashing-on-oneplus-ace-2-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixes for Apps Keep Crashing on OnePlus Ace 2 Pro | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-unleash-your-creativity-top-rated-4k-video-editing-software/"><u>In 2024, Unleash Your Creativity Top-Rated 4K Video Editing Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-stop-windows-from-launching-spotify/"><u>Guide to Stop Windows From Launching Spotify</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-steps-to-restore-your-youtube-shorts-thumbnails/"><u>2024 Approved  Steps to Restore Your YouTube Shorts' Thumbnails</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-configure-multiple-display-devices-in-windows-11/"><u>How to Configure Multiple Display Devices in Windows 11</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-smartphones-and-tablets-leading-gb-gameplayers-for-2024/"><u>[Updated] Smartphones & Tablets  Leading GB Gameplayers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-handling-widget-notifications-win-11-style/"><u>Efficiently Handling Widget Notifications Win 11 Style</u></a></li>
</ul></div>
