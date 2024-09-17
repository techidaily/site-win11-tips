---
title: What Are App Execution Aliases, and How Do You Use Them?
date: 2024-09-13T04:50:49.738Z
updated: 2024-09-17T05:31:20.725Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes What Are App Execution Aliases, and How Do You Use Them?
excerpt: This Article Describes What Are App Execution Aliases, and How Do You Use Them?
keywords: App Exec ALIAS,SEO Exec ALIAS,Execute Alias Usage,Alias for App SEO,App Performance Optimization,Enhancing App Visibility,Boosting App Engagement
thumbnail: https://thmb.techidaily.com/1ed4f091728645649c840ae907d2be87aba494a53f4cf1942b1dcf1c240fc190.jpg
---

## What Are App Execution Aliases, and How Do You Use Them?

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
<a href="https://wigfever.sjv.io/c/5597632/1995803/22899" target="_top" id="1995803">
  <img src="//a.impactradius-go.com/display-ad/22899-1995803" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/1995803/22899" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://eaxpv-info.techidaily.com/new-flawless-offline-viewing-your-guide-to-mobile-video-downloads-for-idevices-for-2024/"><u>[New] Flawless Offline Viewing Your Guide to Mobile Video Downloads for iDevices for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-best-free-non-intrusive-android-screen-recorders/"><u>[New] In 2024, Best Free Non-Intrusive Android Screen Recorders</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-mastering-gif-a-step-by-step-guide/"><u>[New] Mastering GIF A Step-by-Step Guide</u></a></li>
<li><a href="https://win-amazing.techidaily.com/asus-pce-ac68-wireless-network-card-freshly-released-driver-download-option/"><u>ASUS PCE-AC68 Wireless Network Card - Freshly Released Driver Download Option</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-the-top-7-windows-photo-org-systems/"><u>Discover the Top 7 Windows Photo Org Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-hidden-gems-windows-11-themes/"><u>Discovering Hidden Gems: Windows 11 Themes</u></a></li>
<li><a href="https://android-unlock.techidaily.com/downloading-samfw-frp-tool-30-for-htc-by-drfone-android/"><u>Downloading SamFw FRP Tool 3.0 for HTC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/empowering-cross-device-communication-via-nearby/"><u>Empowering Cross-Device Communication via Nearby</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enjoy-your-favorite-games-android-to-windows-powered-by-google-play/"><u>Enjoy Your Favorite Games: Android to Windows, Powered by Google Play</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-activate-stellar-data-recovery-for-iphone-13-pro-max-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Activate Stellar Data Recovery for iPhone 13 Pro Max | Stellar</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-samsung-galaxy-f34-5g-location-by-number-drfone-by-drfone-virtual-android/"><u>How to Track Samsung Galaxy F34 5G Location by Number | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-photo-import-glitches-with-ios-devices-on-windows/"><u>Overcoming Photo Import Glitches with iOS Devices on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-rectify-windows-11-search-woes/"><u>Quick Guide to Rectify Windows 11 Search Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-unanticipated-security-alerts-in-win10win11/"><u>Troubleshooting Unanticipated Security Alerts in Win10/Win11</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/unveiling-nest-audios-superiority-in-smart-speaker-market-a-must-have-for-connoisseurs-of-sound/"><u>Unveiling Nest Audio's Superiority in Smart Speaker Market - A Must-Have for Connoisseurs of Sound</u></a></li>
</ul></div>

