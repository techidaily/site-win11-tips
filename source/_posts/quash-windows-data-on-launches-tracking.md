---
title: Quash Windows Data on Launches Tracking
date: 2024-06-25T16:13:19.652Z
updated: 2024-06-26T16:13:19.652Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quash Windows Data on Launches Tracking
excerpt: This Article Describes Quash Windows Data on Launches Tracking
keywords: Quiet Tracking Data,Stop Windows Surveillance,End Windows Privacy Intrusion,Disable Windows Tracking,Halt Windows Monitoring,Eliminate Window's Data Collection,Prevent Launches on Windows Tracking
thumbnail: https://thmb.techidaily.com/8b607e0e604394629b363ae69329923c5b752c9a4c4af741aef58011df0d7554.jpg
---

## Quash Windows Data on Launches Tracking

 Windows records and monitors how often you use particular applications. While this may enhance productivity, it does also raise privacy concerns.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

## 1\. How to Disable App Launch Tracking Through Windows Settings

 To disable app launch tracking, open the Start menu and type **Settings** in the search bar. Select the **Settings** option in the search results. In the left-side menu, click the **Privacy & security** tab. Then click **General** under the Windows permissions section.

 On the next page, locate **Let Windows improve Start and search results by tracking app launches** and toggle it off.

![Disable App Launch Tracking through Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-windows-settings.jpg)

 After making the changes, Windows will stop tracking and recording your app launches.

 If you ever need to re-enable the feature, repeat the same steps and toggle the switch back on. This will enable Windows to start tracking and recording your app launches.

## 2\. How to Disable App Launch Tracking Using the Group Policy Editor

 You can also disable app launch tracking using the Group Policy Editor. But this method is only available in the Pro and Enterprise versions.

 If you don't have these Windows versions, [turn on the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) and follow these instructions.

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **gpedit.msc** in the text box and click **OK**.
3. In the Group Policy Editor window, navigate to the following path:  
`User Configuration > Administrative Templates > Windows Components > Edge UI​`
4. Go to the right side of the window and double-click on **Turn off tracking of app usage**.  
![Disable App Launch Tracking using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-using-group-policy-editor.jpg)
5. On the next page, check the **Enabled** box.
6. Click **Apply** \> **OK** to save your changes.

 This way, you can disable app launch tracking using the group policy editor.

 To enable the feature again, follow the same steps and navigate to _User Configuration > Administrative Templates > Windows Components > Edge UI_. Then double-click on **Turn off tracking of app usage** and check the **Not Configured** or **Disabled** option.

## 3\. How to Disable App Launch Tracking Through the Registry Editor

 Registry Editor is another method to disable app launch tracking. The process is tricky as you need to manually modify the registry keys and one wrong move can cause serious problems. So, we suggest you [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 To disable app launch tracking through Registry Editor, do the following:

1. Right-click on Start and select **Run** from the menu list.
2. Type **regedit** in the text field and click **OK**. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. When the UAC window appears, click **Yes** to grant privileges.
4. In the left pane, navigate to the following path:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. If you don't find the Advanced folder, right-click on **Explorer** and select **New** \> **Key**.
6. Name it **Advanced** and press the Enter key.
7. Now, right-click on the **Advanced** folder and choose **New** \> **DWORD (32-bit) Value**.
8. Name it **Start\_TrackProgs** and hit Enter.  
![Disable App Launch Tracking through the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-the-registry-editor.jpg)
9. Double-click on the **Start\_TrackProgs** DWORD and set its value to **0**.

 Once you're done, close the Registry Editor and restart your computer. Now, Windows won't track or record app launches.

 If you ever want to turn back on app launch tracking, double-click on the **Start\_TrackProgs** DWORD in Registry Editor and set its value to **1**. After that, restart your system for the changes to take effect.

## Windows Won’t Track or Monitor the Apps You Use

 If you don't want to mess with the Registry Editor or Group Policy Editor, use the Settings option to disable app launch tracking. Choose the method you prefer and enjoy a tracking-free experience.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/keep-windows-11-clean-enable-the-autodelete-functionality/"><u>Keep Windows 11 Clean: Enable the Autodelete Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-data-safety-embedding-secure-passwords-into-files/"><u>Elevate Data Safety: Embedding Secure Passwords Into Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-unlocking-windows-11/"><u>Quick Guide: Unlocking Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-restore-deleted-run-logs/"><u>Methods to Restore Deleted Run Logs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/purple-pandemonium-restore-your-pcs-color-calibration/"><u>Purple Pandemonium? Restore Your PC's Color Calibration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/charting-your-course-in-windows-preload-land/"><u>Charting Your Course in Windows Preload Land</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-cortana-assistance-feature/"><u>Eliminate Cortana Assistance Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-windowed-games-a-list-of-best-fps-trackers-on-pc/"><u>Winning at Windowed Games: A List of Best FPS Trackers on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-dynamic-system-health-enhancement/"><u>Windows' Dynamic System Health Enhancement</u></a></li>
<li><a href="https://extra-information.techidaily.com/discover-the-premier-10-mixers-for-professional-podcasters/"><u>Discover the Premier 10 Mixers for Professional Podcasters</u></a></li>
<li><a href="https://discord-videos.techidaily.com/mastering-device-specific-discord-deletion-techniques-for-2024/"><u>Mastering Device-Specific Discord Deletion Techniques for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-activation-lock-on-the-iphone-12-mini-without-previous-owner-by-drfone-ios/"><u>How to Remove Activation Lock On the iPhone 12 mini Without Previous Owner?</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-best-webm-to-mp3-converters-expert-recommendations-for-2024/"><u>New Best WebM to MP3 Converters Expert Recommendations for 2024</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-premium-10-tools-for-crafting-tiktok-videos-online-w-for-2024/"><u>[New] Premium 10 Tools for Crafting TikTok Videos Online (W) for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-professional-workshop-embedding-countdown-features-in-obs/"><u>[Updated] In 2024, Professional Workshop  Embedding Countdown Features in OBS</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-cinematic-clarity-expert-4k-screens-for-editing-artistry/"><u>In 2024, Cinematic Clarity  Expert 4K Screens for Editing Artistry</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-logo-design-101-tips-to-make-your-podcast-stand-out/"><u>2024 Approved  Logo Design 101  Tips to Make Your Podcast Stand Out</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-the-comprehensive-guide-to-lexis-audio-editor-reviews-innovations-and-how-tos/"><u>In 2024, The Comprehensive Guide to Lexis Audio Editor Reviews, Innovations, and How-Tos</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-the-shorter-path-cutting-video-duration-on-youtube/"><u>[New] In 2024, The Shorter Path  Cutting Video Duration on YouTube</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>