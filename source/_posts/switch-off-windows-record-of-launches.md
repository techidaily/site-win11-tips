---
title: Switch Off Windows Record of Launches
date: 2024-09-01T05:19:58.254Z
updated: 2024-09-02T05:19:58.254Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Switch Off Windows Record of Launches
excerpt: This Article Describes Switch Off Windows Record of Launches
keywords: Stop Windows Launch Recorder,Disable Launch History,Turn Off Startup Logs,End Windows Recordings,Prevent Launch Tracking,Eliminate Launch Data,Halt System Startups
thumbnail: https://thmb.techidaily.com/ced9cab3bb4f4b670e0a461fa0277071d0fe6cc512c46ece52a065d147ecc37a.jpg
---

## Switch Off Windows Record of Launches

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
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
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->

 Once you're done, close the Registry Editor and restart your computer. Now, Windows won't track or record app launches.

 If you ever want to turn back on app launch tracking, double-click on the **Start\_TrackProgs** DWORD in Registry Editor and set its value to **1**. After that, restart your system for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
## Windows Won’t Track or Monitor the Apps You Use

 If you don't want to mess with the Registry Editor or Group Policy Editor, use the Settings option to disable app launch tracking. Choose the method you prefer and enjoy a tracking-free experience.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-discovering-why-filmora-captivates-your-heart/"><u>[New] 2024 Approved  Discovering Why Filmora Captivates Your Heart</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-2024-approved-steps-to-activate-windows-11-auto-hdr-option/"><u>[New] 2024 Approved  Steps to Activate Windows 11 Auto-HDR Option</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-crafting-and-gauging-the-success-of-fb-instream-ads-for-2024/"><u>[New] Crafting and Gauging the Success of FB Instream Ads for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-strategies-to-solve-obs-fullscreen-breakdowns/"><u>[Updated] 2024 Approved  Strategies to Solve OBS Fullscreen Breakdowns</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-experiences-with-the-syma-x8c-drone/"><u>[Updated] Experiences with the Syma X8C Drone</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-fasttrack-retrosnap-replay-for-2024/"><u>[Updated] FastTrack RetroSnap Replay for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-fixing-audio-absence-in-online-shared-videos/"><u>[Updated] Fixing Audio Absence in Online Shared Videos</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-decoding-popularity-a-truthful-look-at-reels-on-instagram/"><u>[Updated] In 2024, Decoding Popularity  A Truthful Look at Reels on Instagram</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-unlocking-crossfade-magic-using-audacity-effectively-for-2024/"><u>[Updated] Unlocking Crossfade Magic  Using Audacity Effectively for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-best-photo-boosts-for-perfecting-your-feed/"><u>2024 Approved  Best Photo Boosts for Perfecting Your Feed</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-excellent-10-drone-set-professional-filming-and-photography/"><u>2024 Approved  Excellent 10-Drone Set  Professional Filming & Photography</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/a-step-by-step-pathway-to-messaging-media-download/"><u>A Step-by-Step Pathway to Messaging Media Download</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-you-when-your-vivo-v30-is-off-drfone-by-drfone-virtual-android/"><u>Can Life360 Track You When Your Vivo V30 is off? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-breakdown-understanding-windows-odbc-system/"><u>Comprehensive Breakdown: Understanding Windows' ODBC System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/direct-download-methods-for-newcomers-to-windows/"><u>Direct Download Methods for Newcomers to Windows</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-bypass-android-lock-screen-using-emergency-call-on-samsung-by-drfone-android/"><u>How to Bypass Android Lock Screen Using Emergency Call On Samsung?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-change-itel-p55plus-lock-screen-password-by-drfone-android/"><u>How To Change Itel P55+ Lock Screen Password?</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-change-your-sim-pin-code-on-your-motorola-edge-40-pro-phone-by-drfone-android/"><u>How To Change Your SIM PIN Code on Your Motorola Edge 40 Pro Phone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-it-lava-yuva-3-pro-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix It Lava Yuva 3 Pro Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-news-and-interests-high-memory-and-cpu-usage-on-windows-10-and-11/"><u>How to Fix News and Interests' High Memory and CPU Usage on Windows 10 and 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-spyware-signs-without-tools/"><u>Identifying Spyware Signs without Tools</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-flashcapture-quick-image-hold-manual/"><u>In 2024, FlashCapture  Quick Image Hold Manual</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-rewards-and-risks-virtual-reality-unveiled/"><u>In 2024, Rewards & Risks  Virtual Reality Unveiled</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-trends-that-make-your-meme-epidemic/"><u>In 2024, Trends That Make Your Meme Epidemic</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-iomap64sys-fault-management-in-windows-pcs/"><u>Mastering IOMap64.sys Fault Management in Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-your-pcs-potential-onedrive-fails-remedied/"><u>Mastering Your PC's Potential: OneDrive Fails Remedied</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-11s-elevation-conflict-overcoming-error-740/"><u>Navigating Windows 11'S Elevation Conflict: Overcoming Error #740</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-visuals-on-win1011-by-driver-rebooting/"><u>Optimizing Visuals on Win10/11 by Driver Rebooting</u></a></li>
<li><a href="https://review-topics.techidaily.com/play-hevc-h-265-on-xperia-5-v-is-it-possible-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Play HEVC H.265 on Xperia 5 V, is it possible?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prevent-snipping-tool-start-with-print-key-in-windows-11-os/"><u>Prevent Snipping Tool Start with Print Key in Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-vanished-recorded-run-events/"><u>Preventing Vanished Recorded Run Events</u></a></li>
<li><a href="https://win11-tips.techidaily.com/propel-your-productivity-key-strategies-with-windows-11/"><u>Propel Your Productivity: Key Strategies with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-refreshing-desktop-icons-in-windows/"><u>Quick Fix: Refreshing Desktop Icons in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-sleep-windows-1011-turns-off-by-itsself/"><u>Quick Sleep: Windows 10/11 Turns Off By Itsself</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivate-steam-graphics-in-windows-environment/"><u>Reactivate Steam Graphics in Windows Environment</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/resolving-windows-pcs-critical-system-error-0x00000028-a-step-by-step-guide/"><u>Resolving Windows PC's Critical System Error 0X00000028: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-automatic-voice-feature-in-ms-word/"><u>Restoring Automatic Voice Feature in MS Word</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrecting-off-screen-windows-6-steps-for-win11/"><u>Resurrecting Off-Screen Windows: 6 Steps for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-windows-files-with-top-tricks-max-156/"><u>Simplify Windows Files with Top Tricks (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stabilizing-the-sweep-of-your-cursor-deactivating-mouse-accel-in-win-11/"><u>Stabilizing the Sweep of Your Cursor: Deactivating Mouse Accel in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-to-resolve-failing-windows-discord-updates/"><u>Step by Step to Resolve Failing Windows Discord Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-address-critical-javascript-failure-in-discord-on-windows/"><u>Steps to Address Critical JavaScript Failure in Discord on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-preserve-windows-system-time-settings/"><u>Strategies to Preserve Windows System Time Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-value-proposition-of-windows-11s-interactive-elements/"><u>The Value Proposition of Windows 11'S Interactive Elements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/three-methods-to-use-telnet-in-windows-11/"><u>Three Methods to Use Telnet in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-unresponsive-speakers-in-modern-os/"><u>Troubleshoot Unresponsive Speakers in Modern OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1011-hack-abruptly-delete-non-responsive-printers/"><u>Windows 10/11 Hack: Abruptly Delete Non-Responsive Printers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-sound-system-enhancement-through-drivers-update-tutorial/"><u>Windows Sound System Enhancement Through Drivers Update Tutorial</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>