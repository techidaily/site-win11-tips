---
title: "Tailoring Windows 11 to Your Needs: Active Hours & Updates"
date: 2024-06-25T16:31:34.288Z
updated: 2024-06-26T16:31:34.288Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tailoring Windows 11 to Your Needs: Active Hours & Updates"
excerpt: "This Article Describes Tailoring Windows 11 to Your Needs: Active Hours & Updates"
keywords: Win11 Customization,Update Schedule,Active Windows Hour,Personalized Settings,OS Regular Updates,Tailored Windows Features,Windows 11 Enhancements
thumbnail: https://thmb.techidaily.com/527ec40dbef906cadfd5828e1a10f887ec75fd463af4e51940397e62459c5f66.jpg
---

## Tailoring Windows 11 to Your Needs: Active Hours & Updates

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
<li><a href="https://win11-tips.techidaily.com/corrective-measures-for-disabled-lock-screen-timer/"><u>Corrective Measures for Disabled Lock Screen Timer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/four-steps-for-pausing-windows-update/"><u>Four Steps for Pausing Windows Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restarting-the-windows-indexer-a-quick-guide/"><u>Restarting the Windows Indexer: A Quick Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-pagefilesys-understanding-its-windows-purpose/"><u>What Is Pagefile.sys? Understanding Its Windows Purpose</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enable-tone-playback-on-windows-post-hardware-failure/"><u>Enable Tone Playback on Windows Post Hardware Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-missing-display-configurations-on-nvidia/"><u>Overcoming Missing Display Configurations on Nvidia</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-conquering-win-errors/"><u>The Ultimate Guide to Conquering Win Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-desktop-with-these-8-innovative-personalization-steps-from-bubbleui/"><u>Elevate Your Desktop with These 8 Innovative Personalization Steps From BubbleUI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-overcoming-org-managed-configurations-in-windows-11/"><u>Guidelines for Overcoming Org-Managed Configurations in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/determine-disk-technology-in-windows-1011/"><u>Determine Disk Technology in Windows 10/11</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-cure-missing-fb-stories-on-devices/"><u>[Updated] 2024 Approved  Cure Missing FB Stories on Devices</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-oppo-reno-11f-5g-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Oppo Reno 11F 5G to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-your-pictures-after-g24-power-has-been-deleted-by-fonelab-android-recover-pictures/"><u>Recover your pictures after G24 Power has been deleted.</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-professional-guide-ensuring-imovie-content-shines-on-vimeo/"><u>2024 Approved  Professional Guide  Ensuring iMovie Content Shines on Vimeo</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-eco-friendly-recorder-ads-absolved/"><u>[Updated] In 2024, Eco-Friendly Recorder - Ads Absolved</u></a></li>
<li><a href="https://extra-tips.techidaily.com/beijings-frost-touched-games-highlights-from-2022-for-2024/"><u>Beijing's Frost-Touched Games, Highlights From 2022 for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/best-game-screen-recorders/"><u>Best Game Screen Recorders</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-you-can-try-final-cut-pro-for-90-days-absolutely-free-final-cut-pros-latest-version-is-available-for-a-free-trial-learn-everything-abo/"><u>Updated 2024 Approved You Can Try Final Cut Pro for 90 Days Absolutely Free. Final Cut Pros Latest Version Is Available for a Free Trial. Learn Everything About It Right Here</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-a-comprehensive-guide-to-azure-speech-to-text-implementation/"><u>2024 Approved  A Comprehensive Guide to Azure Speech-to-Text Implementation</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-instagram-harmony-a-comprehensive-song-selection-methodology/"><u>2024 Approved  Instagram Harmony  A Comprehensive Song Selection Methodology</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>