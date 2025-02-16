---
title: Tips for Delaying Windows 10 Restart While Ongonant Applications Are Opened
date: 2025-02-11T23:15:21.345Z
updated: 2025-02-15T18:55:13.983Z
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

## Why Does Windows Show an Error Message While Logging Off?

 It may be that you have quite a few tasks running simultaneously, each possibly with unsaved data. If this is the case, each task or application attempts to save data before Windows logs off. This could be one reason for the error message. As a remedy, you may want to extend the time allotted for signing off to allow all tasks to finish what they are doing.

 Alternatively, it could just be a problem task. This may be true if it is a recurring issue. In this case, and if you’re sure none of the applications you are using will lose data, you could make Windows force a sign-off more quickly.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2En1CHbiYwA?si=jZKzTr9EIT2ShjGK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Should You Try First?

 The method described here basically forces Windows to wait longer while shutting down or logging off. However, if you have a misbehaving program interfering with Windows log-off, it could be something to look into. There are fixes you should try first if there is an[app preventing Windows from shutting down or logging off](https://www.makeuseof.com/this-app-preventing-windows-shutting-down-restarting-signing-out-error/) .

 If none of those options works, you can adjust how long Windows waits before logging off, which gives any running or buggy apps more time to sort themselves out.

## Make Windows Wait Longer When Logging Off

 There are two processes that you can turn to. With the first, WaitToKillAppTimeout, Windows grants apps 20 seconds to save data and close. If apps don’t respond, Windows considers them “hung.” HungAppTimeout, the second, tells Windows how many seconds to wait before considering apps to be hung and offering a force-close solution.

 Changing both these values involves[editing the registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) , so be wary, and[make a backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) copy before you tinker with it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/97ydpSmzTJw?si=tFcelmtQX4u-b3u5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/_1g4U13PBk0?si=xJLJtlc4hKBTBH8M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 1B. How to Change WaitToKillAppTimeout for All Users

This will apply altered log-off rules to all users on the PC.

1. Open the Registry editor.
2. Navigate to the following folder in the registry:  
`HKEY_USERS\.DEFAULT\Control Panel\Desktop`
3. Follow steps three to six from method 1A to change how long Windows waits for apps to finish closing properly when logging off for all users.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/On0Jw2oMZf0?si=Pm-FJoEt8XWmtMbr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=lhdUUVYMVQjzHXBh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2B. How to Change HungAppTimeout for All Users

This will allow you to change the default value for all users.

1. Open the Registry Editor.
2. Navigate to the following folder in the registry:  
`HKEY_USERS\.DEFAULT\Control Panel\Desktop`
3. Follow steps 3 to 6 from method 2A to change how long Windows waits when logging off for all users.

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
<li><a href="https://fox-helps.techidaily.com/new-animators-choice-full-review-2024-edition/"><u>[New] Animator's Choice Full Review - 2024 Edition</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-androids-creme-de-la-creme-for-fast-vid-fixing/"><u>2024 Approved Android's Crème De La Crème for Fast Vid Fixing</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/approved-the-key-to-success-perfecting-your-online-yt-presence/"><u>2024 Approved The Key to Success Perfecting Your Online YT Presence</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-top-10-screenshot-enhancers-ios-and-android-sticker-edition/"><u>2024 Approved Top 10 Screenshot Enhancers IOS & Android Sticker Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-admin-restrictions-from-windows-security-error/"><u>Clearing Admin Restrictions From Windows Security Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-new-heights-increasing-window-11-icon-size/"><u>Explore New Heights: Increasing Window 11 Icon Size</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-a-beginners-primer-to-ps4-gameplay-screenshots-and-streaming/"><u>In 2024, A Beginner's Primer to PS4 Gameplay Screenshots and Streaming</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/next-gen-framework-overhaul-for-advanced-13-systems-dive-into-enhanced-display-technologies-and-elite-processors/"><u>Next-Gen Framework Overhaul for Advanced 13 Systems - Dive Into Enhanced Display Technologies and Elite Processors</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/no-cost-digital-revenue-prognosticator-for-2024/"><u>No-Cost Digital Revenue Prognosticator for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-missing-dll-rockalldlldll-glitches/"><u>Overcoming 'Missing DLL: Rockalldll.dll' Glitches</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/painting-a-new-world-ai-illustration-through-chatgpt/"><u>Painting a New World: AI Illustration Through ChatGPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefining-windows-11s-default-touch-interface-positioning/"><u>Redefining Windows 11'S Default Touch Interface Positioning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-windows-error-code-0xc0000001-instances/"><u>Remedy for Windows Error Code 0XC0000001 Instances</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/top-10-airplay-apps-in-realme-narzo-60-5g-for-streaming-drfone-by-drfone-android/"><u>Top 10 AirPlay Apps in Realme Narzo 60 5G for Streaming | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tracking-desktop-image-save-path-in-windows-11/"><u>Tracking Desktop Image Save-Path in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-for-iphone-photo-import-error-on-windows-pc/"><u>Troubleshooting for iPhone Photo Import Error on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-the-pros-and-cons-of-different-win-video-codes/"><u>Understanding the Pros & Cons of Different Win Video Codes</u></a></li>
</ul></div>

