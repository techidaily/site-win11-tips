---
title: Stop Windows From Monitoring Opened Software
date: 2024-09-11T20:35:04.084Z
updated: 2024-09-17T04:04:03.830Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stop Windows From Monitoring Opened Software
excerpt: This Article Describes Stop Windows From Monitoring Opened Software
keywords: Stop Software Tracking,Avoid Windows Surveillance,End PC Monitoring,Disable Software Watch,Block Window Tracker,Prevent OS Tracking,Eliminate Windows Spying
thumbnail: https://thmb.techidaily.com/dce6bc9a112b3f049356452f785b8eb72027385ba75d849bd9c5cf60929a80d0.png
---

## Stop Windows From Monitoring Opened Software

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115929/19272" target="_top" id="2115929">
  <img src="//a.impactradius-go.com/display-ad/19272-2115929" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115929/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://buynow-info.techidaily.com/clearstream-2v-indooroutdoor-hdtv-antenna-review/"><u>ClearStream 2V Indoor/Outdoor HDTV Antenna Review</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/expert-tips-to-address-lg-display-driver-concerns-across-windows-11-8-and-7-systems/"><u>Expert Tips to Address LG Display Driver Concerns Across Windows 11, 8, and 7 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-frozen-windows-command-prompt-window/"><u>Fixing Frozen Windows Command Prompt Window</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-motorola-edge-40-drfone-by-drfone-virtual-android/"><u>How Do I Stop Someone From Tracking My Motorola Edge 40? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-feasible-ways-to-fake-location-on-facebook-for-your-samsung-galaxy-a14-4g-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Feasible Ways to Fake Location on Facebook For your Samsung Galaxy A14 4G | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-fix-apple-id-verification-code-not-working-from-apple-iphone-14-pro-by-drfone-ios/"><u>In 2024, How To Fix Apple ID Verification Code Not Working From Apple iPhone 14 Pro</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-vivo-y100t-drfone-by-drfone-virtual-android/"><u>In 2024, Prank Your Friends! Easy Ways to Fake and Share Google Maps Location On Vivo Y100t | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/insight-into-the-discontinued-service-what-was-google-hangouts/"><u>Insight Into the Discontinued Service: What Was Google Hangouts?</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/iteration/"><u>Iteration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfecting-your-files-security-with-powertoys-locksmith/"><u>Perfecting Your Files' Security with PowerToys Locksmith</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-forgotten-windows-data-devices/"><u>Restoring Forgotten Windows Data Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-guide-to-launch-and-setup-win-11s-sandbox/"><u>Stepwise Guide to Launch and Setup Win 11'S Sandbox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-silent-screencast-feedback-in-powerpoint/"><u>Troubleshooting Silent Screencast Feedback in PowerPoint</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turning-onoff-touch-typing-on-your-windows-device/"><u>Turning On/Off Touch Typing on Your Windows Device</u></a></li>
</ul></div>

