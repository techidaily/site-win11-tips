---
title: Inhibit Application Start-Tracking Feature on Windows
date: 2024-10-05T21:07:22.313Z
updated: 2024-10-09T00:51:14.469Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Inhibit Application Start-Tracking Feature on Windows
excerpt: This Article Describes Inhibit Application Start-Tracking Feature on Windows
keywords: Stop Windows App Tracking,Inhibit Tracking Feature,Disable Windows Start Tracker,Turn Off App Monitoring,Prevent Windows Start-Tracking,Block Application Tracking Win,Halt Start-Track on PC
thumbnail: https://thmb.techidaily.com/a3293f7209aa15a71e0e22b0ceceeb5d43595d799fa4a5a92be66390c4a5c2d5.jpg
---

## Inhibit Application Start-Tracking Feature on Windows

 Windows records and monitors how often you use particular applications. While this may enhance productivity, it does also raise privacy concerns.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925489/19272" target="_top" id="1925489">
  <img src="//a.impactradius-go.com/display-ad/19272-1925489" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925489/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Click **Apply** \> **OK** to save your changes.

 This way, you can disable app launch tracking using the group policy editor.

 To enable the feature again, follow the same steps and navigate to _User Configuration > Administrative Templates > Windows Components > Edge UI_. Then double-click on **Turn off tracking of app usage** and check the **Not Configured** or **Disabled** option.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137225/26400" target="_top" id="2137225">
  <img src="//a.impactradius-go.com/display-ad/26400-2137225" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137225/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2027162/19272" target="_top" id="2027162">
  <img src="//a.impactradius-go.com/display-ad/19272-2027162" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027162/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you're done, close the Registry Editor and restart your computer. Now, Windows won't track or record app launches.

 If you ever want to turn back on app launch tracking, double-click on the **Start\_TrackProgs** DWORD in Registry Editor and set its value to **1**. After that, restart your system for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134501/19576" target="_top" id="2134501">
  <img src="//a.impactradius-go.com/display-ad/19576-2134501" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134501/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Windows Won’t Track or Monitor the Apps You Use

 If you don't want to mess with the Registry Editor or Group Policy Editor, use the Settings option to disable app launch tracking. Choose the method you prefer and enjoy a tracking-free experience.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-videos.techidaily.com/new-tailoring-igtv-titles-and-summaries-for-impact/"><u>[New] Tailoring IGTV Titles & Summaries for Impact</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-unveiling-the-superior-video-compression-in-av1/"><u>[New] Unveiling the Superior Video Compression in AV1</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-mastering-the-art-of-preserving-playstation-4-gaming-history/"><u>[Updated] 2024 Approved Mastering the Art of Preserving PlayStation 4 Gaming History</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-accelerating-your-creative-process-high-quality-3d-models-tools/"><u>2024 Approved Accelerating Your Creative Process High-Quality 3D Models Tools</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-expert-tips-for-mastering-iphones-sound-capture/"><u>2024 Approved Expert Tips for Mastering iPhone's Sound Capture</u></a></li>
<li><a href="https://discord-videos.techidaily.com/anddvdmp4/"><u>安心&高品質でDVDからMP4への変換 - 無料、コピーロックを解除可能</u></a></li>
<li><a href="https://driver-download.techidaily.com/ensure-compatibility-downloading-logitech-hd-c270-camera-drivers-for-windows-11-users/"><u>Ensure Compatibility: Downloading Logitech HD C270 Camera Drivers for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/getting-to-grips-with-windows-11s-audio-settings-quickly/"><u>Getting to Grips with Windows 11'S Audio Settings Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-wsl-registration-failure-error-code-0x80370102/"><u>How To Rectify WSL Registration Failure (Error Code 0X80370102)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-printer-connectivity-hurdles-in-windows-11/"><u>Overcoming Printer Connectivity Hurdles in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinvent-your-techs-future-away-from-windows/"><u>Reinvent Your Tech's Future, Away From Windows</u></a></li>
<li><a href="https://fox-that.techidaily.com/shutterbugs-solution-fixing-fuzzy-iphone-snapshots-with-ease/"><u>Shutterbug's Solution: Fixing Fuzzy iPhone Snapshots with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-solve-w11w10-bluetooth-pin-verification-failures/"><u>Strategies to Solve W11/W10 Bluetooth PIN Verification Failures</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/sudden-shadow-immediate-copyright-issue/"><u>Sudden Shadow Immediate Copyright Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/surge-power-the-top-5-pc-performance-tools-for-win/"><u>Surge Power: The Top 5 PC Performance Tools for Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-your-onedrive-placement-in-win-11/"><u>Tailor Your OneDrive Placement in Win 11</u></a></li>
<li><a href="https://fox-helps.techidaily.com/techniques-for-straightening-aerial-video-stability-for-2024/"><u>Techniques for Straightening Aerial Video Stability for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-dormant-pane-panes-ultimate-guide-to-win11/"><u>Unlocking Dormant Pane Panes: Ultimate Guide to Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-secrets-to-comic-reading-in-win11/"><u>Unveiling the Secrets to Comic Reading in Win11</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    