---
title: Tips for Delaying Windows 10 Restart While Ongonant Applications Are Opened
date: 2025-02-25T22:19:07.140Z
updated: 2025-03-04T22:52:40.439Z
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
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-the-pathway-to-perfect-zoom-communication-unlocking-effective-online-interactions/"><u>[New] 2024 Approved The Pathway to Perfect ZOOM Communication Unlocking Effective Online Interactions</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-2023s-ultimate-selection-of-ios-devices-for-classic-psp-games/"><u>[New] In 2024, 2023'S Ultimate Selection of iOS Devices for Classic PSP Games</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/eep-up-to-date-with-youtube-community-guidelines/"><u>[New] Keep Up-to-Date With YouTube Community Guidelines</u></a></li>
<li><a href="https://location-social.techidaily.com/change-location-on-yik-yak-for-your-apple-iphone-6s-plus-to-enjoy-more-fun-drfone-by-drfone-virtual-ios/"><u>Change Location on Yik Yak For your Apple iPhone 6s Plus to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-persistent-edge-in-windows-11/"><u>Dealing with Persistent Edge in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/escaping-the-trap-of-unresponsive-windows-updates/"><u>Escaping the Trap of Unresponsive Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/extend-windows-security-integrating-firewalls-into-context-menus/"><u>Extend Window's Security: Integrating Firewalls Into Context Menus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-gift-windows-apps-on-christmas-via-the-microsoft-store/"><u>How to Gift Windows Apps on Christmas via the Microsoft Store</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/latest-guide-how-to-bypass-honor-70-lite-5g-frp-without-computer-by-drfone-android/"><u>Latest Guide How To Bypass Honor 70 Lite 5G FRP Without Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-mayhem-the-art-of-fixing-faulty-registry-items/"><u>Mastery Over Mayhem: The Art of Fixing Faulty Registry Items</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-the-complexities-of-multimonitor-setup-in-win11/"><u>Navigating Through the Complexities of Multimonitor Setup in Win11</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-merge-videos-without-logos-7-best-software-options/"><u>New 2024 Approved Merge Videos Without Logos 7 Best Software Options</u></a></li>
<li><a href="https://article-tips.techidaily.com/zenith-pinnacle-design-review/"><u>Zenith Pinnacle Design Review</u></a></li>
</ul></div>

