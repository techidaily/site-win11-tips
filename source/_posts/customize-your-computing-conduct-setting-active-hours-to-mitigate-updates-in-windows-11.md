---
title: "Customize Your Computing Conduct: Setting Active Hours to Mitigate Updates in Windows 11"
date: 2024-06-25T16:54:23.491Z
updated: 2024-06-26T16:54:23.491Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Customize Your Computing Conduct: Setting Active Hours to Mitigate Updates in Windows 11"
excerpt: "This Article Describes Customize Your Computing Conduct: Setting Active Hours to Mitigate Updates in Windows 11"
keywords: Windows 11 Update Control,SetactiveWindowsHours,Customize Windows Updates,Personalized PC Schedule,Hourly Windows Configuration,ActiveUpdateWindowsManagement,ConfigureWindowsUpdates
thumbnail: https://thmb.techidaily.com/fe074f06665304f02bb44d59a2cf2f7a7e742cf6a430b43148a19a35d32e38f9.jpg
---

## Customize Your Computing Conduct: Setting Active Hours to Mitigate Updates in Windows 11

 Typically, the installation of Windows updates necessitates a system restart, which can cause disruptions during critical work sessions. However, by configuring active hours, you can define the specific times during which you generally use your computer for work. Once you do, Windows will schedule update installations to occur outside of these active hours, ensuring that your work sessions remain uninterrupted.

 You can set active hours in Windows via the Settings app, the Group Policy Editor, or the Registry Editor. Let’s go through each of these methods in detail.

## 1\. How to Set Active Hours Manually via the Settings App

 The Settings app in Windows gives you several options for managing the installation of Windows updates. Here's how you can use it to set active hours on Windows 11\.

1. Press **Win + I** to open the Settings app.
2. Navigate to the **Windows Update** tab using the left sidebar.
3. Select **Advanced options**.
4. Click on **Active hours** to expand it.
5. Use the drop-down menu next to **Adjust active hours** to select **Manually**.
6. In the **Start time** and **End time** fields, specify the hours during which you typically use your device.  
![Set Active Hours Manually via the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-the-settings-app.jpg)

## 2\. How to Set Active Hours Manually Using the Group Policy Editor

 Although the Group Policy Editor on Windows is commonly used to manage advanced system-level settings, you can also use it to set active hours on your computer.

 Note that Group Policy Editor is only available on Professional, Education, and Enterprise editions of Windows. If you use Windows Home, check our guide on [how to access Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

 Follow these steps to set active hours on Windows using the Group Policy Editor.

1. Press **Win + R** to open the Run dialog box.
2. Type **gpedit.msc** in the box and press **Enter**.
3. Use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Update > Manage end user experience**.
4. Double-click the **Turn off auto-restart for updates during active hours** policy on your right.
5. Select the **Enabled** option.
6. Under **Options**, use the drop-down menus next to **Start** and **End** to specify your active hours.
7. Hit **Apply** followed by **OK**.  
![Set Active Hours Manually via Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-group-policy-editor.jpg)

## 3\. How to Set Active Hours Manually With the Registry Editor

 Another method for setting active hours involves tweaking the Windows Registry.

 Although setting active hours via the Registry Editor is a straightforward process, it’s important to be cautious, as incorrect changes made to registry files can render your PC inoperable. If you opt for this method, make sure you either [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Press **Win + S** to access the search menu.
2. Type **registry editor** in the text box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > WindowsUpdate > UX > Settings**.
5. Double-click the **ActiveHoursStart** entry.
6. In the **Value data** field, enter the desired value for the start time of your active hours in a 24-hour format. If you were to set the start time to **9:00 AM**, for instance, you would enter **9** in the text box.
7. Click **OK** to save the value.  
![Set Active Hours Manually via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-registry-editor.jpg)
8. Double-click the **ActiveHoursEnd** entry to set the end time of your active hours in the 24-hour format. For instance, if you want to set the end time to **5:00 PM**, type **17** in the Value data field and click **OK**.
9. Exit the Registry Editor window.  
![Set Active Hours Manually via the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-the-registry-editor.jpg)

## 4\. How to Configure Windows to Set Active Hours Automatically

 You can also configure Windows to set active hours automatically. Doing so will allow Windows to analyze your usage patterns and automatically adjust the active hours accordingly.

 To configure Windows to set active hours automatically:

1. Use one of [the many ways to open the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. Navigate to **Windows Update > Advanced options > Active hours**.
3. Click the drop-down menu next to **Adjust active hours** and select **Automatically**.  
![Set Active Hours Automatically on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-automatically-on-windows.jpg)

## Setting Active Hours on Windows Is Easy

 Once you set the active hours using one of the above methods, Windows will avoid initiating automatic restarts for updates during the specified period. As a result, you won’t be interrupted by sudden reboots during your work hours.

 You can set active hours in Windows via the Settings app, the Group Policy Editor, or the Registry Editor. Let’s go through each of these methods in detail.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/skyrocket-your-tech-game-with-these-top-7-windows-tips/"><u>Skyrocket Your Tech Game with These Top 7 Windows Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-unveiled-major-updates-on-windows-11-vs-10/"><u>Windows Unveiled: Major Updates on Windows 11 Vs. 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-and-resolving-issues-with-registry-editor-missing/"><u>Uncovering and Resolving Issues with 'Registry Editor' Missing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-tricks-to-overcome-pin-failures-in-win10win11/"><u>Quick Tricks to Overcome PIN Failures in Win10/Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-power-peaks-controlling-wlanext-usage/"><u>Taming Power Peaks: Controlling WLANEXT Usage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bitfort-fractured-stay-the-course-before-change/"><u>BitFort Fractured: Stay the Course Before Change</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stealth-mode-for-windows-11-apps/"><u>Stealth Mode for Windows 11 Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-file-operations-in-powershell-and-command-prompt/"><u>Optimizing File Operations in PowerShell & Command Prompt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-address-failed-lunar-client-startup-errors/"><u>Solutions to Address Failed Lunar Client Startup Errors</u></a></li>
<li><a href="https://howto.techidaily.com/6-solutions-to-fix-error-505-in-google-play-store-on-asus-rog-phone-7-ultimate-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Solutions to Fix Error 505 in Google Play Store on Asus ROG Phone 7 Ultimate | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-swift-tips-for-easy-ipad-screen-recordings/"><u>In 2024, Swift Tips for Easy iPad Screen Recordings</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-unparalleled-snapchat-experience-top-editing-tools-on-smartphones/"><u>[New] 2024 Approved  Unparalleled Snapchat Experience  Top Editing Tools on Smartphones</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-best-of-the-best-top-10-video-players-for-slow-motion-video/"><u>New 2024 Approved Best of the Best Top 10 Video Players for Slow Motion Video</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-capture-your-inspiration-top-5-pinterest-videos-without-cost/"><u>[New] Capture Your Inspiration! Top 5 Pinterest Videos Without Cost</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-navigating-the-social-sea-identifying-unfollowers-on-instagram/"><u>[New] 2024 Approved  Navigating the Social Sea  Identifying Unfollowers on Instagram</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-delving-into-immersive-vr-storytelling/"><u>[Updated] 2024 Approved  Delving Into Immersive VR Storytelling</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-achieving-high-view-count-a-youtube-video-guide/"><u>2024 Approved  Achieving High View Count  A YouTube Video Guide</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-beyond-the-box-the-finest-alternatives-to-obs-for-live-broadcasting/"><u>2024 Approved  Beyond the Box  The Finest Alternatives to OBS for Live Broadcasting</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-conquering-the-flaws-of-windows-11-photo-app/"><u>2024 Approved  Conquering the Flaws of Windows 11 Photo App</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>