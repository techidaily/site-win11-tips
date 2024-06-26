---
title: Put a Halt on Application Start-Tracking in Windows
date: 2024-06-25T16:08:07.165Z
updated: 2024-06-26T16:08:07.165Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Put a Halt on Application Start-Tracking in Windows
excerpt: This Article Describes Put a Halt on Application Start-Tracking in Windows
keywords: Stop App Tracking Windows,End App Start Monitoring,Cease Window Tracker Use,Disable Windows Tracking,Halt Application Logging,Block Windows Start-Tracking,Prevent App Start Monitoring
thumbnail: https://thmb.techidaily.com/97bc8f701c5a50640871957d35ec4f8e16308c84bcc3926e5048675a7dfb62d5.png
---

## Put a Halt on Application Start-Tracking in Windows

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
<li><a href="https://win11-tips.techidaily.com/steering-clear-of-stuck-warcraft-patches/"><u>Steering Clear of Stuck Warcraft Patches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719261998240-unfreeze-windows-update-easy-to-follow-tips/"><u>Unfreeze Windows Update: Easy-to-Follow Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-voice-typing-problems-error-code-0x80049dd3-in-windows-11/"><u>Remedying Voice Typing Problems (Error Code: 0X80049DD3) in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-change-the-windows-spotlight-picture-whenever-you-want/"><u>How to Change the Windows Spotlight Picture Whenever You Want</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-track-fixes-dealing-with-directdraw-glitches-in-win1011/"><u>Fast-Track Fixes: Dealing with DirectDraw Glitches in Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-greyed-out-waste-bin-icon-in-win11/"><u>Restoring Greyed Out Waste Bin Icon in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/can-malware-scanners-hang-up-compute-resources/"><u>Can Malware Scanners Hang Up Compute Resources?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-winerror-0xc0000005/"><u>Mastering the Art of Fixing WinError 0Xc0000005</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-dolby-atmos-installation-in-windows-1111/"><u>Seamless Dolby Atmos Installation in Windows 11/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-gpresult-the-ultimate-gpo-report-tool/"><u>Exploring GPResult: The Ultimate GPO Report Tool</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-from-flat-to-fantastic-3d-text-creation-tips/"><u>2024 Approved  From Flat to Fantastic  3D Text Creation Tips</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-step-by-step-guide-removing-photo-backdrops/"><u>[New] Step-by-Step Guide  Removing Photo Backdrops</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-detect-and-stop-mspy-from-spying-on-your-tecno-camon-30-pro-5g-drfone-by-drfone-virtual-android/"><u>How to Detect and Stop mSpy from Spying on Your Tecno Camon 30 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/peer-reviewed-evaluation-of-action-screening-tech-for-2024/"><u>Peer-Reviewed Evaluation of Action Screening Tech for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-affordable-android-chat-top-free-app-alternatives/"><u>[Updated] In 2024, Affordable Android Chat  Top Free App Alternatives</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-2024-approved-advanced-audacity-editing-adjusting-pitch-without-audio-degradation/"><u>New 2024 Approved Advanced Audacity Editing Adjusting Pitch Without Audio Degradation</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/from-script-to-screen-cutting-edge-video-editing-for-youtubers/"><u>From Script to Screen  Cutting-Edge Video Editing for YouTubers</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-mastering-your-console-innovative-approaches-to-xbox-captures-for-2024/"><u>[Updated] Mastering Your Console  Innovative Approaches to Xbox Captures for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-maximize-creativity-with-these-10-androidpc-video-tools/"><u>[Updated] In 2024, Maximize Creativity with These 10 Android/PC Video Tools</u></a></li>
<li><a href="https://extra-resources.techidaily.com/elevate-edits-complimentary-image-enhancer-app/"><u>Elevate Edits - Complimentary Image Enhancer App</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>