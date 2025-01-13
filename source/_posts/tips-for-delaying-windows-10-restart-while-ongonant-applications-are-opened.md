---
title: Tips for Delaying Windows 10 Restart While Ongonant Applications Are Opened
date: 2025-01-11T01:06:36.494Z
updated: 2025-01-12T19:28:39.103Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tips for Delaying Windows 10 Restart While Ongonant Applications Are Opened
excerpt: This Article Describes Tips for Delaying Windows 10 Restart While Ongonant Applications Are Opened
keywords: Win10 Restart Tip,Stop Windows 10 Reboot,Prevent OS Shutdown,Delay Windows 10 Close,Ongoing App Stay On,Bypass PC Sleep Mode,Keep Apps Active W10
thumbnail: https://thmb.techidaily.com/c7f5000e41b71ee026b5d1dc2b4d2e4d8155a2a1a3717610151f0f8cc3caeaae.jpg
---

## Tips for Delaying Windows 10 Restart While Ongonant Applications Are Opened

 Sometimes, when shutting down, restarting, or logging off from your Windows 10 machine, you may get an error message that interrupts or even cancels the operation. To prevent this from happening, you can make Windows wait longer when logging off.

 Making the system give it a little while longer could actually save you time. Here’s what you should do, should you be faced with this situation.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/h5uImbOWmTg?si=z4kP-R0QbXbBAJTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Does Windows Show an Error Message While Logging Off?

 It may be that you have quite a few tasks running simultaneously, each possibly with unsaved data. If this is the case, each task or application attempts to save data before Windows logs off. This could be one reason for the error message. As a remedy, you may want to extend the time allotted for signing off to allow all tasks to finish what they are doing.

 Alternatively, it could just be a problem task. This may be true if it is a recurring issue. In this case, and if you’re sure none of the applications you are using will lose data, you could make Windows force a sign-off more quickly.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lp78eFEGwVU?si=-4orJBLvJJrggCJ2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Should You Try First?

 The method described here basically forces Windows to wait longer while shutting down or logging off. However, if you have a misbehaving program interfering with Windows log-off, it could be something to look into. There are fixes you should try first if there is an[app preventing Windows from shutting down or logging off](https://www.makeuseof.com/this-app-preventing-windows-shutting-down-restarting-signing-out-error/) .

 If none of those options works, you can adjust how long Windows waits before logging off, which gives any running or buggy apps more time to sort themselves out.

## Make Windows Wait Longer When Logging Off

 There are two processes that you can turn to. With the first, WaitToKillAppTimeout, Windows grants apps 20 seconds to save data and close. If apps don’t respond, Windows considers them “hung.” HungAppTimeout, the second, tells Windows how many seconds to wait before considering apps to be hung and offering a force-close solution.

 Changing both these values involves[editing the registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) , so be wary, and[make a backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) copy before you tinker with it.

### 1A. How to Set WaitToKillAppTimeout for Just Your User Account

 Do this to change how long Windows waits for apps when logging off just from your user account.

1. Open the Registry editor. See[how to open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-open-registry-editor/) for more information.
2. Navigate to the following folder in the registry:  
`HKEY_CURRENT_USER\Control Panel\Desktop`
3. In the pane on the right, look for the string named**WaitToKillAppTimeout** .
4. If you don’t see it, you’ll need to create it by right-clicking in any empty space in the pane and selecting**New > String Value** . Rename it**WaitToKillAppTimeout** .
5. Double-click this string to edit its value, which is in milliseconds. (1000 milliseconds equals one second.) By default, the value data is set to 20,000 (or 20 seconds).
6. Increase this value to make Windows wait on running apps longer before shutting down or logging off. (Decreasing its value will log you off more quickly.)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nlwr9LjJ-ng?si=I6UNAtfBkY2FTceu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 1B. How to Change WaitToKillAppTimeout for All Users

This will apply altered log-off rules to all users on the PC.

1. Open the Registry editor.
2. Navigate to the following folder in the registry:  
`HKEY_USERS\.DEFAULT\Control Panel\Desktop`
3. Follow steps three to six from method 1A to change how long Windows waits for apps to finish closing properly when logging off for all users.

### 2A. How to Set HungAppTimeout for Just Your User Account

 Doing this will change how long Windows waits for apps that it considers hung. This is just for your user account.

1. Open the Registry Editor.
2. Navigate to the following folder in the Registry:  
`HKEY_CURRENT_USER\Control Panel\Desktop`
3. In the pane on the right, look for the string named**HungAppTimeout** .
4. If the string doesn’t exist, create it by right-clicking in any empty space in the pane and choosing**New > String Value** . Rename it**HungAppTimeout** .
5. Double-click this string to edit its value – again, in milliseconds. (1000 milliseconds equals 1 second.) By default, the value data is set to 5000.
6. Increase this value to make Windows afford more time to hung apps and wait longer when shutting down or logging off. (Reduce this value to log off more quickly.)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VlwHTQQMs?si=BXYwD1pKiaTuev4y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2B. How to Change HungAppTimeout for All Users

This will allow you to change the default value for all users.

1. Open the Registry Editor.
2. Navigate to the following folder in the registry:  
`HKEY_USERS\.DEFAULT\Control Panel\Desktop`
3. Follow steps 3 to 6 from method 2A to change how long Windows waits when logging off for all users.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OZQJUTr44rA?si=ADA0nD1VnXjR_sH0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Give Apps More Time to Close When Logging Off

 If apps keep interrupting Windows when you shut down or log off, it would be wise to give them a little more time to finish up and close properly. That way, they won’t interrupt the log-off process and have you intervene manually.

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
<li><a href="https://youtube-data.techidaily.com/024-approved-ad-based-revenue-tracking-for-youtubers-success/"><u>[New] 2024 Approved Ad-Based Revenue Tracking for YouTubers' Success</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-gear-vr-compatibility-the-definitive-mobile-device-list-2023-edition/"><u>[Updated] Gear VR Compatibility The Definitive Mobile Device List - 2023 Edition</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ving-financial-gain-with-youtube-shorts-essentials-opportunities-and-earning-prospects-for-2024/"><u>Achieving Financial Gain with Youtube Shorts Essentials, Opportunities & Earning Prospects for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/advanced-dynamic-typographic-options-for-2024/"><u>Advanced Dynamic Typographic Options for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathing-life-into-non-operational-win11-licenses/"><u>Breathing Life Into Non-Operational Win11 Licenses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-capture-failed-on-your-pcs-camera-app/"><u>Bypass Capture Failed on Your PC's Camera App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-connectivity-hiccups-for-windows-users-and-spotify/"><u>Bypassing Connectivity Hiccups for Windows Users and Spotify</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-update-failure-windows-error-code-0x80242016/"><u>Bypassing Update Failure: Windows Error Code 0X80242016</u></a></li>
<li><a href="https://win11-tips.techidaily.com/choosing-a-drives-for-your-games-on-xbox-app-made-simple/"><u>Choosing a Drives for Your Games on Xbox App, Made Simple</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-vivo-s18-location-on-twitter-drfone-by-drfone-virtual-android/"><u>How to Change your Vivo S18 Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-with-location-spoofer-on-vivo-s18e-drfone-by-drfone-virtual-android/"><u>How To Simulate GPS Movement With Location Spoofer On Vivo S18e? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-the-reel-effect-creating-compelling-loops-on-ig/"><u>In 2024, The Reel Effect Creating Compelling Loops on IG</u></a></li>
<li><a href="https://fox-metric.techidaily.com/step-by-step-guide-changing-your-user-profile-on-windows-10-tips-from-yl-computing/"><u>Step-by-Step Guide: Changing Your User Profile on Windows 10 - Tips From YL Computing</u></a></li>
<li><a href="https://win-amazing.techidaily.com/the-ultimate-guide-to-downloading-and-refreshing-your-asus-bluetooth-drivers/"><u>The Ultimate Guide to Downloading and Refreshing Your ASUS Bluetooth Drivers</u></a></li>
</ul></div>

