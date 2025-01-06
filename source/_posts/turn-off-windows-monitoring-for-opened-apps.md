---
title: Turn Off Windows Monitoring for Opened Apps
date: 2024-12-30T06:34:04.092Z
updated: 2025-01-05T17:51:47.306Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Turn Off Windows Monitoring for Opened Apps
excerpt: This Article Describes Turn Off Windows Monitoring for Opened Apps
keywords: Turn Off Windows Tracking,Disable WinAppMonitor,Stop Windows App Monitoring,End App Watchfulness in Windows,Block Windows App Activity,Halt Windows Program Surveillance,Cease Windows Opened Apps Watch
thumbnail: https://thmb.techidaily.com/96ca9c739207d23d042e7f8016b381f18f2564ff73ddf98034c5d696bcc3f7e9.jpg
---

## Turn Off Windows Monitoring for Opened Apps

 Windows records and monitors how often you use particular applications. While this may enhance productivity, it does also raise privacy concerns.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2NU63YqpVqw?si=uoJs0-nZYAkILqXx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Disable App Launch Tracking Through Windows Settings

 To disable app launch tracking, open the Start menu and type **Settings** in the search bar. Select the **Settings** option in the search results. In the left-side menu, click the **Privacy & security** tab. Then click **General** under the Windows permissions section.

 On the next page, locate **Let Windows improve Start and search results by tracking app launches** and toggle it off.

![Disable App Launch Tracking through Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-windows-settings.jpg)

 After making the changes, Windows will stop tracking and recording your app launches.

 If you ever need to re-enable the feature, repeat the same steps and toggle the switch back on. This will enable Windows to start tracking and recording your app launches.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OFDHJnZLwTA?si=WThcb2h76AnZDzcQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fZTlPdOFNmo?si=Ym8p7ayV1gtNzzXj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Click **Apply** \> **OK** to save your changes.

 This way, you can disable app launch tracking using the group policy editor.

 To enable the feature again, follow the same steps and navigate to _User Configuration > Administrative Templates > Windows Components > Edge UI_. Then double-click on **Turn off tracking of app usage** and check the **Not Configured** or **Disabled** option.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-0Ww1YIIUe4?si=cQ-Gkh9UCJABuPZU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you're done, close the Registry Editor and restart your computer. Now, Windows won't track or record app launches.

 If you ever want to turn back on app launch tracking, double-click on the **Start\_TrackProgs** DWORD in Registry Editor and set its value to **1**. After that, restart your system for the changes to take effect.

## Windows Won’t Track or Monitor the Apps You Use

 If you don't want to mess with the Registry Editor or Group Policy Editor, use the Settings option to disable app launch tracking. Choose the method you prefer and enjoy a tracking-free experience.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-lab.techidaily.com/ed-10-best-youtube-music-reaction-videos-2023/"><u>[Updated] 10 Best YouTube Music Reaction Videos 2023</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-art-of-haul-video-production-and-editing-techniques/"><u>2024 Approved The Art of Haul Video Production and Editing Techniques</u></a></li>
<li><a href="https://tech-revival.techidaily.com/beware-the-google-bard-app-is-a-hidden-threat-avoid-downloading-now/"><u>Beware: The Google Bard App Is a Hidden Threat - Avoid Downloading Now!</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/complete-examination-of-eero-pro-wifi-routers-for-extensive-home-wireless-reach-and-quality-connection/"><u>Complete Examination of Eero Pro WiFi Routers for Extensive Home Wireless Reach and Quality Connection</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-stop-google-chrome-from-tracking-your-location-on-nokia-g22-drfone-by-drfone-virtual-android/"><u>In 2024, How to Stop Google Chrome from Tracking Your Location On Nokia G22? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-steam-connection-mainteninas-a-rust-windows-solution-guide/"><u>Mastering Steam Connection Mainteninas: A Rust-Windows Solution Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-microsoft-store-glitch-error-x80072f30-fix-guide/"><u>Overcoming Microsoft Store Glitch: Error X80072F30 Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reigniting-skyrim-with-script-enhancement-fixes/"><u>Reigniting Skyrim with Script Enhancement Fixes</u></a></li>
<li><a href="https://extra-hints.techidaily.com/shaking-it-off-analyzing-the-efficacy-of-photostability/"><u>Shaking It Off Analyzing the Efficacy of PhotoStability</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-tutorial-eliminating-isdonedll-issues-on-windows/"><u>Step-by-Step Tutorial: Eliminating ISDone.dll Issues on Windows</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-authors-toolkit-enhanced-by-ai-9-uses-of-chatgpt-to-write-and-polish-your-next-bestseller/"><u>The Author's Toolkit Enhanced by AI: 9 Uses of ChatGPT to Write and Polish Your Next Bestseller</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/tweeting-trouble-laughter-league/"><u>Tweeting Trouble Laughter League</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-server-stumbled-error-for-a-smooth-microsoft-store-experience-on-windows-11-and-11/"><u>Unblocking Server Stumbled Error for a Smooth Microsoft Store Experience on Windows 11 & 11</u></a></li>
<li><a href="https://win-amazing.techidaily.com/upgrade-to-the-latest-intel-hd-iris-graphics-drivers-on-windows-10-and-11-easy-download-and-update-process/"><u>Upgrade to the Latest Intel HD / Iris Graphic's Drivers on Windows 10 & 11 – Easy Download and Update Process</u></a></li>
</ul></div>

