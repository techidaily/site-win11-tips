---
title: Silencing Windows Update Alerts
date: 2024-10-13T05:43:51.408Z
updated: 2024-10-14T18:21:24.729Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Silencing Windows Update Alerts
excerpt: This Article Describes Silencing Windows Update Alerts
keywords: Stop Windows Update Notifications,Mute Update Alerts WinXP/Win10,Quiet System Updates Windows,Bypass Update Interruptions,Halt Windows Update Alarms,Disable Update Prompts Windows,Prevent Windows Update Alerts
thumbnail: https://thmb.techidaily.com/606be4e6c5a29affde6b0062eb01d7884930a95dd58e84baf4df0ccd1b6b1a9d.jpg
---

## Silencing Windows Update Alerts

 When an update is ready for installation, Windows notifies you and prompts you to restart your computer. As helpful as these reminders are, they can also be distracting at times. Fortunately, it’s possible to disable update notifications on Windows.

 You can disable Windows update notifications using the Settings app, Group Policy Editor, or Registry Editor. Let's go over each of these methods one by one.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Disable Windows Update Notifications via the Settings App

 The quickest way to disable update notifications on Windows is through the Settings app. Here are the steps for the same.

1. Press**Win + I** to open Windows Settings. You can also use any method we cover in[how to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Update & Security > Windows Update** .
3. Select**Advanced options** .
4. Disable the toggle for**Notify me when a restart is required to finish updating** .
5. Disable the toggle for**Get me up to date** so that Windows does not display a restart warning when an update is ready for installation.  
![Disable Windows Update Notifications Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-settings-app.jpg)

 Once you complete the above steps, Windows should not bother you with update notifications.

<!-- affiliate ads begin -->
<a href="https://smilemakers.pxf.io/c/5597632/2123901/26106" target="_top" id="2123901">
  <img src="//a.impactradius-go.com/display-ad/26106-2123901" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://smilemakers.pxf.io/i/5597632/2123901/26106" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Disable Windows Update Notifications Using Group Policy Editor

 Group Policy Editor is a powerful tool for configuring various settings on your Windows computer. If you have the Enterprise or Professional edition of Windows, you can disable update notifications using the Group Policy Editor. If you don't have either of those versions, read our guide on[how to access Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

To disable Windows update notifications using Group Policy Editor:

1. Press**Win + R** to open the Run dialog box.
2. Type**gpedit.msc** in the box and press**Enter** .
3. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Update > Manage end use experience.**
4. Double-click the**Display options for update notifications** policy on your right.
5. Select the**Disabled** option.
6. Click**Apply** followed by**OK** .  
![Disable Windows Update Notifications Using the Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-group-policy-editor-1.jpg)

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2129041/19576" target="_top" id="2129041">
  <img src="//a.impactradius-go.com/display-ad/19576-2129041" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2129041/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to re-enable the Windows update notifications later, follow the same steps above and set the**Display options for update notifications** policy to**Not configured** .

## 3\. Disable Windows Update Notifications With Registry Editor

 If you can’t seem to access the Group Policy Editor for some reason, you can use the Registry Editor to disable update notifications.

 Since Registry Editor is a powerful tool that needs to be handled with care, we recommend that you back up all the registry files or create a restore point before proceeding with the changes below. If you need help, check our guides on[how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and[how to create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

To disable Windows update notifications using Registry Editor:

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the Registry Editor window, use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows** .
5. Locate the**WindowsUpdate** key. If you can’t find it, right-click on the**Windows** key and select**New > Key** . Rename the key as**WindowsUpdate** .
6. Right-click the**WindowsUpdate** key and select**New > DWORD (32-bit) Value** .
7. Rename the DWORD as**SetUpdateNotificationLevel** .
8. Double-click the newly created DWORD and change its**Value data** to**0** .
9. Click**OK** .  
![Disable Windows Update Notifications Using the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-registry-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134241/18498" target="_top" id="2134241">
  <img src="//a.impactradius-go.com/display-ad/18498-2134241" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134241/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Exit the Registry Editor window and restart your PC to apply the changes. Following that, Windows will not display update notifications on your computer.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100533/7443" target="_top" id="2100533">
  <img src="//a.impactradius-go.com/display-ad/7443-2100533" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100533/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## No More Update Notifications on Windows

 Windows updates are critical for the overall stability of your computer. That said, turning off Windows update notifications makes sense if you're not in a rush to install updates as soon as they are ready for installation.

 If you find Windows notifications to be distracting in general, you can use Focus Assist to silence all alerts and stay productive.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-data.techidaily.com/024-approved-mastering-yoga-top-10-youtube-resources-for-enlightened-living/"><u>[New] 2024 Approved Mastering Yoga Top 10 YouTube Resources for Enlightened Living</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/024-approved-prime-tools-turning-youtube-videos-into-text/"><u>[New] 2024 Approved Prime Tools Turning YouTube Videos Into Text</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-a-critical-evaluation-of-ustream-with-equivalents/"><u>[New] A Critical Evaluation of Ustream with Equivalents</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-quick-guide-securing-your-favorite-audio-narratives-on-iphoneipad/"><u>[New] Quick Guide Securing Your Favorite Audio Narratives on iPhone/iPad</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-securely-accessing-social-memories-fb-status-videos-guide/"><u>[Updated] In 2024, Securely Accessing Social Memories FB Status Videos Guide</u></a></li>
<li><a href="https://fox-helps.techidaily.com/a-canvas-of-colors-advanced-theory-and-use/"><u>A Canvas of Colors Advanced Theory & Use</u></a></li>
<li><a href="https://extra-resources.techidaily.com/conquer-the-canvas-of-nature-mastering-iphone-sky-photography/"><u>Conquer the Canvas of Nature Mastering iPhone Sky Photography</u></a></li>
<li><a href="https://win11-tips.techidaily.com/directing-changes-to-user-profiles-in-w11-os/"><u>Directing Changes to User Profiles in W11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-enabling-windows-notepad-with-excel-views/"><u>Guide: Enabling Windows Notepad with Excel Views</u></a></li>
<li><a href="https://win11-tips.techidaily.com/run-a-local-and-free-chatgpt-clone-on-your-windows-pc-with-gpt4all/"><u>Run a Local and Free ChatGPT Clone on Your Windows PC With GPT4All</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-amplify-vram-in-windows-os/"><u>Strategies to Amplify VRAM in Windows OS</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-7-phone-number-locators-to-track-oppo-a1x-5g-location-drfone-by-drfone-virtual-android/"><u>Top 7 Phone Number Locators To Track Oppo A1x 5G Location | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unleash-your-online-potential-with-perplexity-ai-the-ultimate-yet-untapped-google-search-enhancer/"><u>Unleash Your Online Potential with Perplexity AI - The Ultimate, Yet Untapped Google Search Enhancer</u></a></li>
</ul></div>

