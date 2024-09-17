---
title: Understanding Execution Identifiers in App Management
date: 2024-09-13T09:12:00.117Z
updated: 2024-09-17T02:25:11.089Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Understanding Execution Identifiers in App Management
excerpt: This Article Describes Understanding Execution Identifiers in App Management
keywords: ID in Apps,App Identifier,Execution IDs,Manage App ID,App Management Keywords,Identifier Understanding,Executable Identifiers
thumbnail: https://thmb.techidaily.com/836b19a99b81c291189dfbcf8add59f634c1fb8aacdfd70319b10cdaec65e638.jpg
---

## Understanding Execution Identifiers in App Management

 If you're trying to open an app like Microsoft Paint in the Run Dialog and see an error message, it could be caused by your app aliases. But what exactly are App Execution Aliases, where do you find them, and how do you use them?

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Are App Execution Aliases?

 An alias is an alternative name given to something. The most obvious example is the codename given to a spy or undercover agent. On Windows, aliases have nothing to do with spying. Instead, they are used for streamlining tasks, such as entering commands.

 Windows 10 and 11 both allow aliases to be declared for some apps by default. The available apps vary but are often those commonly associated with command line tools. Giving an app an alias allows it to be executed using a shorter title rather than the full name or path.

 App aliases can be used in several[Windows Command Line Interfaces](https://www.makeuseof.com/what-is-cli-what-does-it-stand-for/) (CLI), including the Run Dialog, Command Prompt, and[PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) . If you use these tools with any regularity, app aliases can help to streamline entering commands.

## How to Enable App Execution Aliases in Settings

 You can enable and disable aliases for compatible apps in the main settings in both Windows 10 and 11\. If more than one app uses the same alias name, you can choose which has the alias applied to it.

In Windows 11:

1. Open**Settings > Apps** , and look for**Advanced app settings** .
2. In the advanced app settings, click**App execution aliases** to see the list of compatible apps.
3. Use the slider switches to enable or disable the alias for each app. You can see the alias name below each app.

![app aliases in windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win11.jpg)

In Windows 10:

1. If you're using Windows 10, you'll find the aliases in**Settings > Apps & features** .
2. Click the**App execution aliases** link near the top of the Apps & features page.
3. You can then enable and disable aliases using the switches.

![app aliases in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win10.jpg)

 By default, in both Windows 10 and 11, you can only enable or disable existing app aliases. But if you don't mind editing the Registry, you can create new aliases for many other apps.

## Create App Execution Aliases in Registry Editor

 Before editing or creating registry keys, it is advisable to[create a full backup of the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . Of course, you should also ensure you understand how to restore the Registry from that backup.

 The process below for creating app execution aliases in the Registry Editor should be the same in both Windows 10 and 11.

1. Open**Windows Search** , type**Registry Editor** , and click on the search result to open it.
2. In the editor, navigate to **HKEY\_CURRENT\_USER\\Software\\Microsoft\\Windows\\CurrentVersion\\App Paths** .
3. Next, right-click on the**App Paths** key in the left-hand pane, and select**New > Key** .
4. Give the new key an alias name that relates to the app and ends with .exe. For example, if the alias is for Calendar, call it something like cal.exe.
5. With the alias selected, double-click the**Default** value in the right-hand pane.  
![editing app aliases in registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-regedit.jpg)
6. In the Value data field, you will need to enter the full path to the app executable file. For example**C:\\Program Files (x86)\\Calendar.exe** .
7. Right-click in the right pane and select**New > String value** . Name the string**path** . The change the Value data to the same path as above, but without the app filename.

 You can now close the Registry Editor. The new App Execution Alias will now be available to use in the Windows CLIs.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123472/16836" target="_top" id="2123472">
  <img src="//a.impactradius-go.com/display-ad/16836-2123472" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123472/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Using and Creating App Execution Aliases

 Entering commands into tools such as Command Prompt and PowerShell can be laborious. You can streamline that process by enabling or creating aliases for apps that commonly feature in those commands. Why type out a full path to an executable file when you can point to it with a few keystrokes?

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
<li><a href="https://fox-blue.techidaily.com/new-the-ultimate-guide-to-top-online-tools-for-perfecting-your-video-subtitles/"><u>[New] The Ultimate Guide to Top Online Tools for Perfecting Your Video Subtitles</u></a></li>
<li><a href="https://android-unlock.techidaily.com/best-oppo-find-x7-ultra-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>Best Oppo Find X7 Ultra Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delivering-significant-gains-in-windows-11/"><u>Delivering Significant Gains in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-launcher-not-found-on-pc/"><u>Eliminating Launcher Not Found on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-the-ultimate-artistic-tools-on-windows-11-platform/"><u>Explore the Ultimate Artistic Tools on Windows 11 Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gear-up-performance-the-ultimate-vram-upgrade-plan-for-windows/"><u>Gear Up Performance - The Ultimate VRAM Upgrade Plan for Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-realme-narzo-60x-5g-find-my-friends-no-location-found-drfone-by-drfone-virtual-android/"><u>How to Fix Realme Narzo 60x 5G Find My Friends No Location Found? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-turn-your-terminal-back-to-standard-win11/"><u>How to Turn Your Terminal Back To Standard (Win11)</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-smaller-brands-bigger-impacts-infographics/"><u>In 2024, Smaller Brands, Bigger Impacts (Infographics)</u></a></li>
<li><a href="https://review-topics.techidaily.com/issues-playing-h-265-hevc-video-on-motorola-g24-power-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Issues playing H.265 HEVC video on Motorola G24 Power</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/1716465298533-personalize-your-channel-with-free-pics/"><u>Personalize Your Channel With Free Pics!</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/quick-fixes-for-annoying-ipad-recording-problems-for-2024/"><u>Quick Fixes for Annoying iPad Recording Problems for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-error-code-0x800704b3/"><u>Resolving Windows Error Code: 0X800704B3</u></a></li>
<li><a href="https://android-location-track.techidaily.com/solutions-to-spy-on-lava-blaze-curve-5g-with-and-without-jailbreak-drfone-by-drfone-virtual-android/"><u>Solutions to Spy on Lava Blaze Curve 5G with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://article-helps.techidaily.com/venturing-virtuality-a-review-of-lgs-360-headset/"><u>Venturing Virtuality A Review of LG's 360 Headset</u></a></li>
</ul></div>

