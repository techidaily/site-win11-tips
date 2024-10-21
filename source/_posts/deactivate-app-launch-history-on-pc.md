---
title: Deactivate App Launch History on PC
date: 2024-10-18T18:17:32.351Z
updated: 2024-10-20T19:26:25.398Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Deactivate App Launch History on PC
excerpt: This Article Describes Deactivate App Launch History on PC
keywords: Clear App Launch History,Delete Launch Records,Remove Launch Trail,Wipe Launch Data,Erase Launch Logs,Reset Application Timeline,Cleanse PC Launch History
thumbnail: https://thmb.techidaily.com/c01f488742f525379e15c90538d56863d279883606cc35ff29b3863a4d78b16e.jpg
---

## Deactivate App Launch History on PC

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137207/26400" target="_top" id="2137207">
  <img src="//a.impactradius-go.com/display-ad/26400-2137207" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137207/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Click **Apply** \> **OK** to save your changes.

 This way, you can disable app launch tracking using the group policy editor.

 To enable the feature again, follow the same steps and navigate to _User Configuration > Administrative Templates > Windows Components > Edge UI_. Then double-click on **Turn off tracking of app usage** and check the **Not Configured** or **Disabled** option.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135408/19272" target="_top" id="2135408">
  <img src="//a.impactradius-go.com/display-ad/19272-2135408" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135408/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://laganoo.pxf.io/c/5597632/1528685/16446" target="_top" id="1528685">
  <img src="//a.impactradius-go.com/display-ad/16446-1528685" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528685/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you're done, close the Registry Editor and restart your computer. Now, Windows won't track or record app launches.

 If you ever want to turn back on app launch tracking, double-click on the **Start\_TrackProgs** DWORD in Registry Editor and set its value to **1**. After that, restart your system for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902278/19272" target="_top" id="1902278">
  <img src="//a.impactradius-go.com/display-ad/19272-1902278" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902278/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Windows Won’t Track or Monitor the Apps You Use

 If you don't want to mess with the Registry Editor or Group Policy Editor, use the Settings option to disable app launch tracking. Choose the method you prefer and enjoy a tracking-free experience.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-essential-tips-for-making-youtube-introductory-trailers/"><u>[New] In 2024, Essential Tips for Making YouTube Introductory Trailers</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1-tackling-the-irritating-quirks-urgent-solutions-apple-must-implement-for-iphone-users-insights/"><u>1. Tackling the Irritating Quirks: Urgent Solutions Apple Must Implement for iPhone Users - Insights</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-best-tools-to-hard-reset-honor-magic-6-drfone-by-drfone-reset-android-reset-android/"><u>3 Best Tools to Hard Reset Honor Magic 6 | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-find-my-iphone-without-apple-id-on-your-iphone-xs-by-drfone-ios/"><u>How to Remove Find My iPhone without Apple ID On your iPhone XS?</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-hands-free-guide-to-storing-google-voice-chats/"><u>In 2024, Hands-Free Guide to Storing Google Voice Chats</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/mastering-the-art-of-continuous-snapstreak-success-for-2024/"><u>Mastering the Art of Continuous Snapstreak Success for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/optimize-zoom-performance-top-three-tactical-approaches/"><u>Optimize Zoom Performance Top Three Tactical Approaches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-windows-11-proactive-disk-management/"><u>Optimizing Windows 11: Proactive Disk Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-error-in-portaudio-for-audacity-windows-11-and-11/"><u>Overcoming Error in PortAudio for Audacity, Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proven-methods-to-reactivate-the-dormant-wsreset-service/"><u>Proven Methods to Reactivate the Dormant WSReset Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-lowering-cpu-consumption/"><u>Strategies for Lowering CPU Consumption</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/streaming-snapshots-for-facebook-2023-for-2024/"><u>Streaming Snapshots for Facebook, 2023 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-interrupted-exception-on-w10w11-systems/"><u>Troubleshooting Interrupted Exception on W10/W11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/visual-deception-hiding-data-in-windows-images-without-trace/"><u>Visual Deception: Hiding Data in Windows Images Without Trace</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    