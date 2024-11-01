---
title: Decoding App Execution Aliases in Programming
date: 2024-10-25T17:04:57.002Z
updated: 2024-11-01T18:53:36.099Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Decoding App Execution Aliases in Programming
excerpt: This Article Describes Decoding App Execution Aliases in Programming
keywords: Code Execution Basics,Programming Aliases Explained,Deciphering Execute Functions,Understanding Alias Identities,Programming Execution Insights,Coding Execution Patterns,Unraveling Code Actions
thumbnail: https://thmb.techidaily.com/6ea42b82e55f6c668ff7a393a7539803912a1c23ef44a3dc870ec2d24d91150f.jpg
---

## Decoding App Execution Aliases in Programming

 If you're trying to open an app like Microsoft Paint in the Run Dialog and see an error message, it could be caused by your app aliases. But what exactly are App Execution Aliases, where do you find them, and how do you use them?

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Are App Execution Aliases?

 An alias is an alternative name given to something. The most obvious example is the codename given to a spy or undercover agent. On Windows, aliases have nothing to do with spying. Instead, they are used for streamlining tasks, such as entering commands.

 Windows 10 and 11 both allow aliases to be declared for some apps by default. The available apps vary but are often those commonly associated with command line tools. Giving an app an alias allows it to be executed using a shorter title rather than the full name or path.

 App aliases can be used in several[Windows Command Line Interfaces](https://www.makeuseof.com/what-is-cli-what-does-it-stand-for/) (CLI), including the Run Dialog, Command Prompt, and[PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) . If you use these tools with any regularity, app aliases can help to streamline entering commands.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043597/7443" target="_top" id="2043597">
  <img src="//a.impactradius-go.com/display-ad/7443-2043597" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043597/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Enable App Execution Aliases in Settings

 You can enable and disable aliases for compatible apps in the main settings in both Windows 10 and 11\. If more than one app uses the same alias name, you can choose which has the alias applied to it.

In Windows 11:

1. Open**Settings > Apps** , and look for**Advanced app settings** .
2. In the advanced app settings, click**App execution aliases** to see the list of compatible apps.
3. Use the slider switches to enable or disable the alias for each app. You can see the alias name below each app.

![app aliases in windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win11.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918679/19272" target="_top" id="1918679">
  <img src="//a.impactradius-go.com/display-ad/19272-1918679" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918679/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868590/19272" target="_top" id="1868590">
  <img src="//a.impactradius-go.com/display-ad/19272-1868590" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868590/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Right-click in the right pane and select**New > String value** . Name the string**path** . The change the Value data to the same path as above, but without the app filename.

 You can now close the Registry Editor. The new App Execution Alias will now be available to use in the Windows CLIs.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925544/19272" target="_top" id="1925544">
  <img src="//a.impactradius-go.com/display-ad/19272-1925544" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925544/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-screen-savers-in-action-expert-tips-on-recording-your-minecraft-experience-for-2024/"><u>[Updated] Screen Savers in Action Expert Tips on Recording Your Minecraft Experience for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-from-idea-to-screenshot-a-mac-guide-to-ootd-tiktoks/"><u>2024 Approved From Idea to Screenshot A Mac Guide to OOTD TikToks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-unlocking-windows-11s-credential-vault/"><u>A Comprehensive Guide to Unlocking Windows 11’S Credential Vault</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activate-data-safety-with-controlled-folder-access-feature/"><u>Activate Data Safety with Controlled Folder Access Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-requires-ancient-login-details/"><u>Addressing Windows Requires Ancient Login Details</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-academic-achievement-winning-study-methods-on-a-windows-pc/"><u>Boost Academic Achievement: Winning Study Methods on a Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-windows-11-desktop-appeal-live-and-animated-backgrounds/"><u>Boost Your Windows 11 Desktop Appeal: Live and Animated Backgrounds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-efficiency-upgrades-to-windows-11s-clipboard-history/"><u>Boosting Efficiency: Upgrades to Windows 11'S Clipboard History</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/easy-guide-how-to-bypass-vivo-v27e-frp-android-10111213-by-drfone-android/"><u>Easy Guide How To Bypass Vivo V27e FRP Android 10/11/12/13</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-the-updated-epson-wf-2750-printer-driver-here/"><u>Get the Updated Epson WF-2750 Printer Driver Here!</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-to-rip-a-dvd-using-vlc-media-player-on-mac-and-windows-systems/"><u>How to Rip a DVD Using VLC Media Player on Mac and Windows Systems</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-13-pro-max-to-other-iphone-14-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 13 Pro Max To Other iPhone 14 devices? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719255310971-jump-over-compatibility-obstacles-with-these-simple-fixes/"><u>Jump Over Compatibility Obstacles with These Simple Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/protecting-the-default-windows-clock-configuration/"><u>Protecting the Default Windows Clock Configuration</u></a></li>
<li><a href="https://win-web.techidaily.com/solving-issues-with-acers-erecovery-management-functionality-comprehensive-tips/"><u>Solving Issues With Acer's eRecovery Management Functionality - Comprehensive Tips</u></a></li>
<li><a href="https://youtube-data.techidaily.com/shing-potential-views-best-keyword-resources-ranked/"><u>Unleashing Potential Views Best Keyword Resources Ranked</u></a></li>
</ul></div>

