---
title: Switch Off Windows Record of Launches
date: 2024-11-15T19:56:42.439Z
updated: 2024-11-17T17:23:12.541Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123727/7443" target="_top" id="2123727">
  <img src="//a.impactradius-go.com/display-ad/7443-2123727" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123727/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1918666/19272" target="_top" id="1918666">
  <img src="//a.impactradius-go.com/display-ad/19272-1918666" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918666/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Click **Apply** \> **OK** to save your changes.

 This way, you can disable app launch tracking using the group policy editor.

 To enable the feature again, follow the same steps and navigate to _User Configuration > Administrative Templates > Windows Components > Edge UI_. Then double-click on **Turn off tracking of app usage** and check the **Not Configured** or **Disabled** option.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880960/19272" target="_top" id="1880960">
  <img src="//a.impactradius-go.com/display-ad/19272-1880960" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880960/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2082536/7443" target="_top" id="2082536">
  <img src="//a.impactradius-go.com/display-ad/7443-2082536" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082536/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://eaxpv-info.techidaily.com/new-from-zero-to-hero-learning-the-art-of-youtube-content-for-2024/"><u>[New] From Zero to Hero Learning the Art of YouTube Content for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-step-by-step-audio-addition-for-impactful-instagram-visuals/"><u>[New] Step-by-Step Audio Addition for Impactful Instagram Visuals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-new-file-metadata-dates-and-more-in-windows/"><u>Crafting New File Metadata: Dates & More in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-techniques-for-windows-calculator-access/"><u>Essential Techniques for Windows Calculator Access</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-overcome-launcher-crash-on-windows-error-0x803f8001/"><u>How to Overcome Launcher Crash on Windows: Error 0X803F8001</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-4-ways-to-sync-contacts-from-apple-iphone-15-to-ipad-easily-drfone-by-drfone-transfer-from-ios/"><u>In 2024, 4 Ways to Sync Contacts from Apple iPhone 15 to iPad Easily | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-honor-80-pro-straight-screen-edition-location-on-twitter-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change your Honor 80 Pro Straight Screen Edition Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/maximizing-generative-ai-in-the-workplace-essential-tips-to-boost-confidence-and-efficiency-amongst-staff-expert-advice-by-zdnet/"><u>Maximizing Generative AI in the Workplace: Essential Tips to Boost Confidence and Efficiency Amongst Staff | Expert Advice by ZDNET</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-for-addressing-and-correcting-discoloration/"><u>Methods for Addressing and Correcting Discoloration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-w11w10-with-effective-synapse-fixes/"><u>Streamlining W11/W10 with Effective Synapse Fixes</u></a></li>
</ul></div>

