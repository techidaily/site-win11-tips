---
title: How to Disable App Launch Tracking in Windows
date: 2024-11-02T09:36:15.166Z
updated: 2024-11-07T03:37:31.237Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Disable App Launch Tracking in Windows
excerpt: This Article Describes How to Disable App Launch Tracking in Windows
keywords: Disabling Windows Tracking,Stop App Launch History,Eliminate Tracking Features,Halt Launcher Logging,Preventing Usage Data,Turn Off Windows Tracking,Cease Application Traces
thumbnail: https://thmb.techidaily.com/d568502deceace8c4ecf36ae07d16a3133e76d13956dfbeb425d156edf1af5a5.png
---

## How to Disable App Launch Tracking in Windows

 Windows records and monitors how often you use particular applications. While this may enhance productivity, it does also raise privacy concerns.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

## 1\. How to Disable App Launch Tracking Through Windows Settings

 To disable app launch tracking, open the Start menu and type **Settings** in the search bar. Select the **Settings** option in the search results. In the left-side menu, click the **Privacy & security** tab. Then click **General** under the Windows permissions section.

 On the next page, locate **Let Windows improve Start and search results by tracking app launches** and toggle it off.

![Disable App Launch Tracking through Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-windows-settings.jpg)

 After making the changes, Windows will stop tracking and recording your app launches.

 If you ever need to re-enable the feature, repeat the same steps and toggle the switch back on. This will enable Windows to start tracking and recording your app launches.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132160/7443" target="_top" id="2132160">
  <img src="//a.impactradius-go.com/display-ad/7443-2132160" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132160/7443" style="position:absolute;visibility:hidden;" border="0" />
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
6. Click **Apply** \> **OK** to save your changes.

 This way, you can disable app launch tracking using the group policy editor.

 To enable the feature again, follow the same steps and navigate to _User Configuration > Administrative Templates > Windows Components > Edge UI_. Then double-click on **Turn off tracking of app usage** and check the **Not Configured** or **Disabled** option.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100533/7443" target="_top" id="2100533">
  <img src="//a.impactradius-go.com/display-ad/7443-2100533" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100533/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2068426/7443" target="_top" id="2068426">
  <img src="//a.impactradius-go.com/display-ad/7443-2068426" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068426/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you're done, close the Registry Editor and restart your computer. Now, Windows won't track or record app launches.

 If you ever want to turn back on app launch tracking, double-click on the **Start\_TrackProgs** DWORD in Registry Editor and set its value to **1**. After that, restart your system for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2148775/18498" target="_top" id="2148775">
  <img src="//a.impactradius-go.com/display-ad/18498-2148775" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148775/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-sundae-screening-comprehensive-tutorial-on-frozen-camera-app/"><u>[Updated] 2024 Approved Sundae Screening Comprehensive Tutorial on Frozen Camera App</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-avoiding-the-crowd-stand-out-with-unique-youtube-persona-for-2024/"><u>[Updated] Avoiding the Crowd Stand Out with Unique YouTube Persona for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-best-5-headsets-a-youtube-gamers-guide/"><u>[Updated] Best 5 Headsets A YouTube Gamer's Guide</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-flash-video-insights-guide-for-2024/"><u>[Updated] Flash Video Insights Guide for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/chuckle-chest-premium-selection-of-gratuitous-gags-for-2024/"><u>Chuckle Chest Premium Selection of Gratuitous Gags for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-internal-failure-in-win11win10-connections/"><u>Correcting Internal Failure in Win11/Win10 Connections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-taskbar-functionality-with-new-contextual-folders/"><u>Enhancing Taskbar Functionality with New Contextual Folders</u></a></li>
<li><a href="https://techtrends.techidaily.com/fai-tornare-in-vita-i-tuoi-video-su-computer-una-guida-completa-al-recupero-e-alla-riproduzione-multimediale/"><u>Fai Tornare in Vita I Tuoi Video Su Computer: Una Guida Completa Al Recupero E Alla Riproduzione Multimediale</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/fun-and-flight-5-best-drone-options-for-children/"><u>Fun and Flight 5 Best Drone Options for Children</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-spatial-sound-in-windows-11/"><u>How to Enable Spatial Sound in Windows 11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-audio-perfection-achieved-expert-tips-without-a-microphone/"><u>In 2024, Audio Perfection Achieved Expert Tips Without a Microphone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-crafting-a-blended-media-experience-with-tunes/"><u>In 2024, Crafting a Blended Media Experience with Tunes</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-pc-screen-to-xiaomi-redmi-note-12r-phones-drfone-by-drfone-android/"><u>In 2024, How to Mirror PC Screen to Xiaomi Redmi Note 12R Phones? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-full-load-in-windows-chatgpt/"><u>Mitigating Full Load in Windows ChatGPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-the-100-obstacle-in-windows-update-processes/"><u>Overcome the 100% Obstacle in Windows Update Processes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-address-phantom-devices-in-pcs/"><u>Strategies to Address Phantom Devices in PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-strategies-for-tackling-windows-camera-errors/"><u>Swift Strategies for Tackling Windows Camera Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-reigniting-winget-in-windows-11/"><u>Troubleshooting: Reigniting Winget in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unsticking-windows-update-quick-repair-tips/"><u>Unsticking Windows Update: Quick Repair Tips</u></a></li>
</ul></div>

