---
title: Reviving a Dysfunctional Resource Monitor on Windows 11
date: 2025-03-01T01:24:47.363Z
updated: 2025-03-05T03:40:37.547Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reviving a Dysfunctional Resource Monitor on Windows 11
excerpt: This Article Describes Reviving a Dysfunctional Resource Monitor on Windows 11
keywords: Revive Resource Monitor W11,Reinstate W11 ResMon,Resurrection W11 Monitor,Reboot Resource Monitor Win11,Restore Windows 11 ResMon,Reset Dysfunctional ResMon Win11,Revive W11 Performance Monitor
thumbnail: https://thmb.techidaily.com/52b4eaebcfcbc6c7fedd891af89526f0d5ee168fe7bb540778411c3fb0605514.jpg
---

## Reviving a Dysfunctional Resource Monitor on Windows 11

 Resource Monitor is a Windows utility that monitors the use and performance of your computer's hardware resources. Unfortunately, it sometimes stops working or encounters issues, making it difficult to track system performance and manage resource usage.

 So, if you're having trouble getting the Resource Monitor tool working on your computer, check out the steps below to troubleshoot any issues and get it up and running again.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Causes the Resource Monitor App to Stop Working?

 Before we dive into solving the problem, let's first check what causes the Resource Monitor app to stop working correctly. There are a few potential causes you should consider.

 The most common cause of Resource Monitor not working is corrupted or outdated drivers. Outdated or incorrect drivers can prevent the software from running properly and cause functionality errors. Additionally, if there are hardware issues with your computer, such as a faulty power supply or RAM, problems with Resource Monitor could also arise.

 Finally, if you have recently installed new antivirus software on your computer, it could block access to the Resource Monitor program.

So, let's move on to the solution and fix this problem.

## 1\. Restart the Computer

![windows restart](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-restart.jpg)

 When troubleshooting software-related issues, a computer restart can often resolve them without resorting to complex solutions. Doing so refreshes all running programs and services while also clearing out any temporary files that might be causing problems.

 In most cases, this can get things back up and running without requiring extra effort. Plus, this solution is usually quick and easy since you only need to shut down your PC and wait for it to boot back up again. If you're having trouble restarting your PC, you can check out our guide on the[different ways you can restart Windows](https://www.makeuseof.com/windows-restart-methods/) .

## 2\. Change the DPI Settings

 Another possible fix for Resource Monitor not working on Windows is to change your DPI settings. Changing the scaling from 100% to 125% or higher on some computers can cause issues with Resource Monitor. Therefore, try adjusting it back to its original setting and check if the tool works again.

To change the DPI scale to its default settings, follow these steps:

1. Press**Win + I** on your keyboard to[open the Settings menu](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. From the left pane, select**System** .
3. Then click**Display** on the right.
4. Under the**Scale & layout** section, click the drop-down menu next to the**Scale** option.  
![Change DPI Scale in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/change-dpi-scale-in-settings.jpg)
5. Choose the recommended value.

 Once you have made the changes, close the Settings window and run the Resource Monitor app to see if the problem is resolved.

## 3\. Run the System File Checker

 If restarting your computer and changing the DPI settings didn't work, running an SFC scan can often detect and repair any corrupted system files that might be causing problems.

To do this, follow these steps:

1. Right-click on Start and select**Run** from the menu list.
2. Type**cmd** in the text box and press**Ctrl + Shift + Enter** on your keyboard.
3. When the UAC popup appears on the screen, click**Yes** to open Command Prompt with admin access. If you want in-depth information, read our guide on[running the command prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) .  
![Run SFC Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-sfc-command.jpg)
4. Now in the elevated Command Prompt window, type in the command below and press Enter:  

sfc /scannow
5. Wait for the process to complete, then restart your PC.

## 4\. Check for Windows Updates

 It is also possible for an outdated version of Windows to cause this issue, so[manually check for any pending Windows updates](https://www.makeuseof.com/update-windows-manually/) and install them.

 Microsoft regularly releases new versions of Windows that fix bugs and improve performance, which makes updating worthwhile. Here's how to do it:

1. Press**Win + I** on your keyboard to launch the System Settings.
2. From the left side of the Settings menu, click**Windows Update** .
3. When Windows Update opens, click the**Check for updates** button.  
![Check for Updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/check-for-updates.jpg)

 If there are any updates available, it will download and install them automatically. After the download completes, install the updates and restart your computer. After that, check to see if Resource Monitor is working.

## 5\. Uninstall the Latest Windows Updates

 If you recently updated your OS and there are no newer updates for it, the last update might have caused the issue. So, try uninstalling any recent update you may have installed, which could help resolve conflicts between the updates and existing system files that are causing problems with Resource Monitor.

1. Press**Win + I** on your keyboard to open the Settings menu
2. Select**Windows Update** from the left pane
3. Now go to the right and click on**Update history** .  
![Update history in Windows Update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/update-history-in-windows-update.jpg)
4. Scroll down to Related settings and click**Uninstall updates** .  

![Uninstall the latest Windows Update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-the-latest-windows-update.jpg)

 Then select any recent updates that you want to uninstall. After that, restart your computer and check if Resource Monitor is now working properly.

## 6\. Create a New User Account

 If you're still having issues, try[creating a new local user account](https://www.makeuseof.com/windows-11-create-local-user-account/) and see if that fixes the issue. This can be helpful if corrupted user profile data or settings cause the problem. To do so, follow the steps below:

1. Open the Settings app on your computer.
2. From the left, select**Accounts** .
3. Click**Other users** under Account settings.
4. Next to Add other users, click**Add account** .  
![Create a New User Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/create-a-new-user-account.jpg)
5. On the Microsoft account page, click **I don't have this person's sign-in information** .

 Then follow the instructions to add a new user account and then sign in with that account. Now open Resource Monitor and see if it's working properly.

## 7\. Troubleshoot in Clean Boot State

 When all else fails, try starting your computer in safe mode and see if the problem persists. If it does not, then background services and applications are possibly conflicting with startup items and causing this error to occur.

In such a case, you need to perform a clean boot as instructed below:

1. Open the**Run** dialog box.
2. Type**MSConfig** in the text box and hit Enter.
3. Check the**Selective startup** box on the General tab.  
![Perform-a-Clean-Boot-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Perform-a-Clean-Boot-1.jpg)
4. Uncheck the**Load startup items** box.

5. Switch to the**Services** tab and check the**Hide all Microsoft services** box.  
![Hide all Microsoft services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Hide-all-Microsoft-services.jpg)
6. Then click**Disable All** .

7. Go to the Startup tab and click the**Open Task Manager** link
8. Disable any services or programs that are active in Startup apps.

 Once you have done this, close Task Manager, then click**OK** on the MSConfig window to save these changes. Now restart your computer for them to take effect, then try using Resource Monitor to see if they work now.

## Resolve Resource Monitor Issues in Windows 11

 Resource Monitor helps you monitor the performance and usage of your system's resources, including memory, disk, and network activity. If you're having trouble accessing this tool, this guide may help.

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
<li><a href="https://extra-approaches.techidaily.com/new-perfecting-your-podcast-entry-in-apples-catalog/"><u>[New] Perfecting Your Podcast Entry in Apple's Catalog</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-earning-potential-for-creators-in-youtube-ads-for-2024/"><u>[Updated] Earning Potential for Creators in YouTube Ads for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-spark-conversation-crafting-questions-for-ig-story-boost/"><u>[Updated] In 2024, Spark Conversation Crafting Questions for IG Story Boost</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-the-essentials-of-crafting-crystal-clear-vhs-graphics-online/"><u>2024 Approved The Essentials of Crafting Crystal-Clear VHS Graphics Online</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/138583970-9781449714352-compass-points-for-daily-living/"><u>Compass Points for Daily Living | Free Book</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-blue-screen-analysis-techniques-with-microsoft-on-w11/"><u>Effective Blue Screen Analysis Techniques with Microsoft on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-pc-with-windows-11s-divine-functionality/"><u>Elevate Your PC with Windows 11'S Divine Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-browser-efficiency-youtube-stream-optimization/"><u>Enhancing Browser Efficiency: YouTube Stream Optimization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/faux-friends-how-innocent-looking-apps-tax-your-windows-11/"><u>Faux Friends: How Innocent-Looking Apps Tax Your Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-missing-program-linkage-issue-on-windows-os/"><u>Fixing Missing Program Linkage Issue on Windows OS</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210355695-9781999254827-instant-kundalini/"><u>Instant Kundalini | Free Book</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-resourceerror-display-of-text-in-windows-11/"><u>Overcoming ResourceError: Display of Text in Windows 11</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-stuck-on-downloading-of-honor-x50i-7-ways-to-resolve-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Stuck on Downloading Of Honor X50i? 7 Ways to Resolve | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-expires-shortly-alert-in-windows-11/"><u>Resolving Windows Expires Shortly Alert in Windows 11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/reveal-every-detail-the-leading-clear-image-apps/"><u>Reveal Every Detail The Leading Clear Image Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/walkthrough-restoring-win-os-backups-to-sys-defaults/"><u>Walkthrough: Restoring Win OS Backups to Sys Defaults</u></a></li>
<li><a href="https://win-cheats.techidaily.com/yl-software-unveils-strategies-for-detecting-crypto-scams-safely-online/"><u>YL Software Unveils Strategies for Detecting Crypto Scams Safely Online</u></a></li>
</ul></div>

