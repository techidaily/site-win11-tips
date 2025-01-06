---
title: Troubleshooting Tips for Windows Subsystem After Upgrade
date: 2025-01-05T11:50:58.042Z
updated: 2025-01-05T16:13:30.484Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Tips for Windows Subsystem After Upgrade
excerpt: This Article Describes Troubleshooting Tips for Windows Subsystem After Upgrade
keywords: WinSys Upgrade Fixes,Windows Sys Troubleshoot,System Update Solutions,Resolve WinSub Upgrade,PC Boot Subsystem Fix,Restart WinSub Errors,Upgrading Windows Sys Tips
thumbnail: https://thmb.techidaily.com/9cc1ab34a2708ce6599562965ce7d038d6461c86c7f5043e45b0cca41d824dbd.jpg
---

## Troubleshooting Tips for Windows Subsystem After Upgrade

 There are several potential reasons why Windows Subsystem for Linux (WSL) stopped working after your PC was upgraded to Windows 11\. Thankfully, the breakdown is unlikely to be terminal, although you might have to try a few different fixes to get it working once again.

 **MUO VIDEO OF THE DAY**

 **SCROLL TO CONTINUE WITH CONTENT**

 Here are several ways to get the Windows Subsystem for Linux working again after upgrading to Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Check That WSL Is Enabled

 It isn't unusual that upgrading to a newer version of the OS will break some apps and features. So although it might sound obvious, checking WSL hasn't simply been disabled during the upgrade process should be your first step. Here's how to check:

![checking if WSL is enabled in Windows Features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-enabled.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaGNHfAT92w?si=bvHo1iYK2JBIPtRo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. In Windows Search, type**Turn Windows features on or off** and click the search result that should appear at the top.
2. In the Windows System dialog, scroll down until you see**Windows Subsystem for Linux** .
3. If the checkbox for the feature is not selected, do so now. Then click**Ok** .
4. You might also need to restart your computer before checking to see if that fixed the problem.

 Hopefully, WSL is now working, and you can begin using the tool. If not, read on for some other possible solutions.

 Learn more about the[things you can do with WSL and Linux](https://www.makeuseof.com/pros-cons-windows-subsystem-for-linux/) on your Windows computer.

## 2\. Enable Hyper-V and Virtual Machine Platform

 If you want to use a subsystem such as WSL in Windows, you'll also need to enable the virtualization tools. These include Hyper-V and the Virtual Machine Platform.

![Error message in the command line interface](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-feature-missing.jpg)

 If a command line interface opens, telling you a required feature is not installed, when you try to run your Linux distribution, this is likely what it refers to.

1. Search for**Turn Windows features on or off** and click the search result.
2. In Windows Features, scroll down to find**Virtual Machine Platform** and**Windows Hypervisor Platform** .
3. Check the boxes next to each of these features and then click**Ok** .
4. You will need to restart your computer to complete the installation of these tools.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SgRVYjqB70s?si=My_2cDvJVdincQRu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Repair the Linux Distribution App

 Your Linux distribution app, such as Ubuntu, Kali, or Debian, could be corrupted or require updating. This can cause WSL to appear to be broken. Repairing Windows apps is very easy.

1. Open**Settings > Apps > App & Features** .
2. Scroll down to the list of your apps to find your Linux distro app.
3. Click the**three dots** to the right of the app name, and select**Advanced options** .  
![Advanced app options in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl.jpg)
4. Click the**Repair** button and follow the on-screen instructions if repairs are necessary.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/T-ssCD10v2M?si=WVWGNayUiCAkMZzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![repairing an app in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl-app.jpg)

 Check if WSL is working. If not, try uninstalling and reinstalling the Linux distribution app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/grbt-5VvbuI?si=qnoirlmljslpqcQj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Force WSL to Open Using the Microsoft Store

 If WSL is enabled but still refuses to open, you can try forcing launch through the Microsoft Store app. This can sometimes fix temporary glitches when opening WSL directly doesn't work.

1. Open the Microsoft Store app and search for**WSL** .
2. On the store page for WSL, you should see an**Open** button. If the button says**Update** , click it to update the app.  
![opening the WSL app in the Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/force-open-store.jpg)
3. Click the**Open** button, and the default Linux distro app should launch.

4. If a command line interface window opens instead, it will probably tell you a required feature is missing. See**Enable Hyper-V and Virtual Machine Platform** above.

 If forcing WSL to open doesn't work, try the same with the Linux distro app you are using. Open the Store, search for your distro, and click the**Open** button.

## 5\. Uninstall Recent Updates to Fix WSL

 If WSL stopped working after installing an update, the update could be the cause. You can uninstall the most recent update to see if that fixes the problem.

[Uninstalling Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) isn't a complicated process, even if you have never done it before.

 If, after uninstalling the update, WSL still does not work, it is a good idea to reinstall it. Updates can often include security and performance tweaks, so it is generally recommended to keep Windows updated.

## 6\. Check That Malware Isn't Blocking WSL

 The final thing to try to get WSL working is scanning for malware. The potential for malware to prevent Windows Subsystem for Linux from working is low but not unheard of.

 Run a[full scan in Microsoft Defender](https://www.makeuseof.com/easy-ways-boost-security-microsoft-defender-and-windows-10/) or whichever third-party antivirus software you use. Quarantine or remove any malware your antivirus scan finds. Then restart your computer and try using WSL to see if that was the issue.

## Fixing WSL After Upgrading to Windows 11

 Upgrading to Windows 11 usually goes smoothly, but apps and features can occasionally break. If you find that WSL is no longer working after upgrading to the newest Windows OS, don't worry, there is usually an easy fix. You might only need to re-enable the feature in the Windows system settings, but if not, running through the other fixes here will usually solve the problem.

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
<li><a href="https://fox-links.techidaily.com/new-2024-approved-tackling-massed-up-tiktoks-expert-edits-for-less-chaos/"><u>[New] 2024 Approved Tackling Massed-Up TikToks Expert Edits for Less Chaos</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/egular-payouts-for-youtube-content-makers-in-2024/"><u>[New] Regular Payouts for YouTube Content Makers, In 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-simplified-techniques-for-blurring-faces-in-pictures/"><u>2024 Approved Simplified Techniques for Blurring Faces in Pictures</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-starters-kit-establishing-yourself-on-youtube-profitably/"><u>2024 Approved Starter's Kit Establishing Yourself on YouTube Profitably</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-step-by-step-guide-for-elevating-your-youtube-feedback-with-emojis/"><u>2024 Approved Step-by-Step Guide for Elevating Your Youtube Feedback with Emojis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-windows-1011-app-starter-issue-code-0xc000003e/"><u>Eliminating Windows 10/11 App Starter Issue: Code 0XC000003E</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/innovative-approaches-to-documenting-facetime-talks-for-2024/"><u>Innovative Approaches to Documenting FaceTime Talks for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-powershell-scripts-to-unblock-files/"><u>Navigating Through PowerShell Scripts to Unblock Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-the-silenced-voice-recognition-your-win11-guide/"><u>Reviving the Silenced Voice Recognition: Your Win11 Guide</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-flip-side-using-ai-to-combat-malware/"><u>The Flip Side: Using AI to Combat Malware</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-non-syncing-in-ms-to-do-app/"><u>Troubleshooting Non-Syncing in MS To-Do App</u></a></li>
<li><a href="https://win-fantastic.techidaily.com/troubleshooting-your-itunes-backups-when-they-turn-grey-in-windows-11-what-to-do/"><u>Troubleshooting Your iTunes Backups When They Turn Grey in Windows 11 – What to Do?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfreeze-your-toolbar-6-solutions-for-stuck-context-menus/"><u>Unfreeze Your Toolbar: 6 Solutions for Stuck Context Menus</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/king-your-online-potential-mastering-seo-for-youtube-success-for-2024/"><u>Unlocking Your Online Potential Mastering SEO for YouTube Success for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mystery-of-update-error-code-0x80246007/"><u>Unraveling the Mystery of Update Error Code: 0X80246007</u></a></li>
<li><a href="https://win11-tips.techidaily.com/window-adjustment-guide-dealing-with-windows-overscan/"><u>Window Adjustment Guide: Dealing with Windows Overscan</u></a></li>
</ul></div>

