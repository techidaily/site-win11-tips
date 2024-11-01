---
title: "The Role of Aliases in Coding: A Practical Guide"
date: 2024-10-30T16:44:34.896Z
updated: 2024-11-01T17:25:42.509Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes The Role of Aliases in Coding: A Practical Guide"
excerpt: "This Article Describes The Role of Aliases in Coding: A Practical Guide"
keywords: Code Alias Basics,Aliasing Techniques,Coding with Alias,Programming Identity,Effective Code Alias,Efficient Coding Practices,Secure Software Development
thumbnail: https://thmb.techidaily.com/56c09995c4310ae28019d3390616d9116d70341b815aee65c7667ed39de0e4c8.jpg
---

## The Role of Aliases in Coding: A Practical Guide

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135369/19272" target="_top" id="2135369">
  <img src="//a.impactradius-go.com/display-ad/19272-2135369" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135369/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

In Windows 10:

1. If you're using Windows 10, you'll find the aliases in**Settings > Apps & features** .
2. Click the**App execution aliases** link near the top of the Apps & features page.
3. You can then enable and disable aliases using the switches.

![app aliases in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win10.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144281/7443" target="_top" id="2144281">
  <img src="//a.impactradius-go.com/display-ad/7443-2144281" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144281/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134494/18498" target="_top" id="2134494">
  <img src="//a.impactradius-go.com/display-ad/18498-2134494" border="0" alt="https://techidaily.com" width="721" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134494/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Right-click in the right pane and select**New > String value** . Name the string**path** . The change the Value data to the same path as above, but without the app filename.

 You can now close the Registry Editor. The new App Execution Alias will now be available to use in the Windows CLIs.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151882/7443" target="_top" id="2151882">
  <img src="//a.impactradius-go.com/display-ad/7443-2151882" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151882/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-support.techidaily.com/new-photographic-albums-with-background-music/"><u>[New] Photographic Albums with Background Music</u></a></li>
<li><a href="https://win11-tips.techidaily.com/corrective-measures-for-virtual-disks-not-starting/"><u>Corrective Measures for Virtual Disks Not Starting</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-canon-mp280-printer-drivers-windows-10-8-and-7-guide/"><u>Download Canon MP280 Printer Drivers: Windows 10, 8, and 7 Guide</u></a></li>
<li><a href="https://some-techniques.techidaily.com/guide-how-to-share-apples-live-images-with-android-contacts-successfully/"><u>Guide: How to Share Apple's Live Images with Android Contacts Successfully</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-revive-blackened-webcam-on-windows-os/"><u>How to Revive Blackened Webcam on Windows OS</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-11-best-location-changers-for-xiaomi-redmi-note-13-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 11 Best Location Changers for Xiaomi Redmi Note 13 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-ultimate-guide-to-crafting-exquisite-hdr-portraits/"><u>In 2024, The Ultimate Guide to Crafting Exquisite HDR Portraits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-your-efficiency-with-essential-win11-navigation-shortcuts/"><u>Maximize Your Efficiency with Essential Win11 Navigation Shortcuts</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-essential-podcast-production-a-ranked-selection-of-the-best-free-and-paid-editing-tools/"><u>New Essential Podcast Production A Ranked Selection of the Best Free & Paid Editing Tools</u></a></li>
<li><a href="https://win-luxury.techidaily.com/step-by-step-tutorial-on-transferring-your-icloud-images-to-an-outside-hard-disk/"><u>Step-by-Step Tutorial on Transferring Your iCloud Images to an Outside Hard Disk</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-clear-printer-usage-messages/"><u>Steps to Clear Printer Usage Messages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-prevent-windows-11-from-listening-in/"><u>Steps to Prevent Windows 11 From Listening In</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-on-overcoming-installation-hurdles-in-windows-os/"><u>Tips on Overcoming Installation Hurdles in Windows OS</u></a></li>
<li><a href="https://win-able.techidaily.com/troubleshoot-roblox-glitches-instantly-top-6-fixes-for-pc-players-updated-guide-2024/"><u>Troubleshoot Roblox Glitches Instantly: Top 6 Fixes for PC Players - Updated Guide 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbo-drives-efficient-data-alignment-for-win11-users/"><u>Turbo Drives: Efficient Data Alignment for Win11 Users</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-2024-approved-the-sonic-landscape-a-study-on-sound-forgeutility/"><u>Updated 2024 Approved The Sonic Landscape A Study on Sound Forgeutility</u></a></li>
</ul></div>

