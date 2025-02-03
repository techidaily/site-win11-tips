---
title: Tips for Delaying Windows 10 Restart While Ongonant Applications Are Opened
date: 2025-01-25T01:33:16.802Z
updated: 2025-01-31T18:10:32.634Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/-yZKNLxj3po?si=-RbF6nCJEVlHWP-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Does Windows Show an Error Message While Logging Off?

 It may be that you have quite a few tasks running simultaneously, each possibly with unsaved data. If this is the case, each task or application attempts to save data before Windows logs off. This could be one reason for the error message. As a remedy, you may want to extend the time allotted for signing off to allow all tasks to finish what they are doing.

 Alternatively, it could just be a problem task. This may be true if it is a recurring issue. In this case, and if you’re sure none of the applications you are using will lose data, you could make Windows force a sign-off more quickly.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Should You Try First?

 The method described here basically forces Windows to wait longer while shutting down or logging off. However, if you have a misbehaving program interfering with Windows log-off, it could be something to look into. There are fixes you should try first if there is an[app preventing Windows from shutting down or logging off](https://www.makeuseof.com/this-app-preventing-windows-shutting-down-restarting-signing-out-error/) .

 If none of those options works, you can adjust how long Windows waits before logging off, which gives any running or buggy apps more time to sort themselves out.

## Make Windows Wait Longer When Logging Off

 There are two processes that you can turn to. With the first, WaitToKillAppTimeout, Windows grants apps 20 seconds to save data and close. If apps don’t respond, Windows considers them “hung.” HungAppTimeout, the second, tells Windows how many seconds to wait before considering apps to be hung and offering a force-close solution.

 Changing both these values involves[editing the registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) , so be wary, and[make a backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) copy before you tinker with it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GBWcw6rXIdg?si=Tlue44bW-bPA4tH9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

### 1B. How to Change WaitToKillAppTimeout for All Users

This will apply altered log-off rules to all users on the PC.

1. Open the Registry editor.
2. Navigate to the following folder in the registry:  
`HKEY_USERS\.DEFAULT\Control Panel\Desktop`
3. Follow steps three to six from method 1A to change how long Windows waits for apps to finish closing properly when logging off for all users.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XS1nQCe95LU?si=A2dhdFkSAI61_nKA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

### 2B. How to Change HungAppTimeout for All Users

This will allow you to change the default value for all users.

1. Open the Registry Editor.
2. Navigate to the following folder in the registry:  
`HKEY_USERS\.DEFAULT\Control Panel\Desktop`
3. Follow steps 3 to 6 from method 2A to change how long Windows waits when logging off for all users.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uV3vm805eX0?si=YSPcsFxBcJmoxLsU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://twitter-videos.techidaily.com/new-ultimate-guide-enjoy-tweets-in-stunning-hd-quality/"><u>[New] Ultimate Guide Enjoy Tweets in Stunning HD Quality</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-verifying-your-youtube-sign-in-details/"><u>[New] Verifying Your YouTube Sign-In Details</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-giggle-guild-the-ultimate-list-of-twitter-joke-threads/"><u>[Updated] Giggle Guild The Ultimate List of Twitter Joke Threads</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-proven-techniques-securely-archive-your-instagram-story/"><u>[Updated] In 2024, Proven Techniques Securely Archive Your Instagram Story</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-sharpening-scenes-the-power-of-film-zoom/"><u>[Updated] Sharpening Scenes The Power of Film Zoom</u></a></li>
<li><a href="https://win-amazing.techidaily.com/direct-access-to-your-epson-ds-30-all-in-one-windows-compatible-drivers-for-wise-users/"><u>Direct Access to Your Epson DS 30 All-in-One: Windows Compatible Drivers for Wise Users</u></a></li>
<li><a href="https://techtrends.techidaily.com/easy-techniques-to-preserve-and-share-moments-playing-ps4-with-screenshots/"><u>Easy Techniques to Preserve and Share Moments Playing PS4 with Screenshots</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-workflow-with-effective-wsl-2-methods/"><u>Elevate Your Workflow with Effective WSL 2 Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-bypassing-error-0x80242016-in-wu/"><u>Guide to Bypassing Error 0X80242016 in WU</u></a></li>
<li><a href="https://some-techniques.techidaily.com/ignite-creative-spark-choosing-from-the-best-6-nft-services-for-2024/"><u>Ignite Creative Spark Choosing From the Best 6 NFT Services for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methodical-approach-to-mic-evaluation-on-win-os/"><u>Methodical Approach to Mic Evaluation on Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-command-execution-pick-terminal-first/"><u>Streamline Your Command Execution: Pick Terminal First</u></a></li>
<li><a href="https://some-guidance.techidaily.com/syncing-youtube-audio-to-film-compositions-for-2024/"><u>Syncing YouTube Audio to Film Compositions for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-stop-auto-opens-of-windows-11s-searchbar/"><u>Tips to Stop Auto-Opens of Windows 11'S Searchbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfreezing-microsoft-teams-a-guide-for-w11-and-w10/"><u>Unfreezing Microsoft Teams: A Guide for W11 & W10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-enigma-of-windows-11s-disguised-theme-settings/"><u>Unlocking the Enigma of Windows 11'S Disguised Theme Settings</u></a></li>
</ul></div>

