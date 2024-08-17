---
title: Fixing Unsuccessful Execution of High Privileges Tasks
date: 2024-08-16T02:46:27.738Z
updated: 2024-08-17T02:46:27.738Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Unsuccessful Execution of High Privileges Tasks
excerpt: This Article Describes Fixing Unsuccessful Execution of High Privileges Tasks
keywords: High-Privilege Task Failure,Unsuccessful Exec Execution,Insecure Task Handling,Privilege Escalation Fix,Secure Task Management,Mitigating Exc Execution,Strong Privilege Controls
thumbnail: https://thmb.techidaily.com/4703b9d657812b3886216df90e44b1d9ef5fb3878b6869f4909ce7c65740d3ae.jpg
---

## Fixing Unsuccessful Execution of High Privileges Tasks

 Windows offers a Run as administrator option that allows users to run applications and programs with administrator privileges. You can also use it to troubleshoot computer issues. But what if this feature malfunctions, depriving you of administrator rights?

 That’s where this guide comes into play. So, let’s look at what you can do to fix Run as administrator not working on Windows.

## What Causes Run as Administrator Not Working?

 Before you start fixing things, you must understand what causes this issue. In general, you may experience Run as administrator not working due to the following reasons:

* Group Policy or User Account Control (UAC) blocks the application or program you’re trying to run.
* The user account associated with your device isn’t an administrator account and therefore doesn’t have the necessary privileges.
* Corrupt system files or registry entries could prevent you from running administrator programs.
* Malware infection on your computer could disrupt the feature.

 Now that you know the potential causes of this issue, let’s look at ways to fix it. ​​​

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
## 1\. Restart Your Computer

 If you’re having trouble running applications with administrative privileges, [restarting your computer](https://www.makeuseof.com/windows-restart-methods/) will likely solve the issue. This simple solution flushes out any temporary issues and puts the system in its default state.

## 2\. Check Your Account Type

 Not all user accounts are equal. To run programs with administrative privileges, you must have an administrator account. So, [head to the Control Panel](https://www.makeuseof.com/windows-open-control-panel/) and [check your account type](https://www.makeuseof.com/check-windows-account-admin-rights/). If it’s not labeled as an administrator account, switch to a different one or create a new account.

## 3\. Check User Account Control Settings

 The Windows User Account Control (UAC) prevents malicious programs from installing on your computer. This security feature can stop you from using elevated privileges.

 To ensure the issue isn’t related to UAC, head to the Control Panel and check your User Account Settings. If it is set to the highest level, bring it down to the default. Here's how to do it:

1. Press **Win + S** simultaneously to open the search box.
2. Type **Control Panel** in the search box and press Enter. This will open the Control Panel window.
3. View items by **Large icons** in the Control Panel and click on **User Accounts**.
4. In the right pane, click on **Change User Account Control settings**. Doing this will open the User Account Control Settings window.
5. Here you’ll see a slider with four options: **Always notify**, **Default**, **Notify me only when applications try to make changes to my computer**, and **Never notify**.  
![User Account Control Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/user-account-control-settings.jpg)
6. Drag the slider to **Default**, then click **OK**. It will set your UAC to the default level and enable you to run applications with elevated privileges.

 Now, close the window and restart your PC. After that, try running the application with the Run as administrator feature and see if it works.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Change Group Policy Settings

 Is the Run as administrator function not working despite trying the suggestions above? It's likely that group policy settings block the feature. To fix this, head to the Local Group Policy Editor and check the settings.

 Here’s what you need to do:

1. Press **Win + R** simultaneously to open the Run dialogue box.
2. Type **gpedit.msc** in the text field and press **Enter**. This will open the Local Group Policy Editor window on your computer screen.
3. From the left navigation panel, go to the following path:  
Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options
4. In the right pane, you'll see a list of different security options. Scroll to the bottom and double-click on the **User Account Control: Run all administrators in Admin Approval Mode** policy.  
![Run all administrators in admin approved](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/run-all-administrators-in-admin-approved.jpg)
5. Doing this will open another window. Here, select the **Disabled** option and click **Apply** \> **OK**.  
![Disable User Account Control in Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-user-account-control-in-group-policy.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
6. Close the Local Group Policy Editor and restart your computer.

 After restarting, try running a program with elevated privileges. It should work now. Don't forget to re-enable the Admin Approval Mode setting once you're finished troubleshooting.

## 5\. Clean up the Context Menu

 When you right-click on a program or file, you often see the Run as administrator option in the context menu. If it's missing, you should look at your context menu entries for clutter.

 This solution involves editing the Windows registry. A single mistake can cause serious problems. So proceed cautiously and [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before applying any changes.

 Follow these steps to clean up the context menu:

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the text field and press Enter. Doing this will open the Windows Registry Editor.
3. If the UAC window pops up, click **Yes** to grant administrative privileges.
4. In the Registry Editor window, navigate to the following path:  
Computer\HKEY_CLASSES_ROOT\*\shellex\ContextMenuHandlers
5. Next, expand the **ContextMenuHandlers** folder and look for any suspicious entries. If you find any, delete them.  
![Clean the Context Menu Items](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/clean-the-context-menu-items.jpg)
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Now exit the Registry Editor and restart your computer.

 Once your computer reboots, you will see the Run as administrator option in the context menu. Try running a program with elevated privileges and see if it works.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Try Some Generic Fixes

 Besides the fixes mentioned above, some generic solutions work in any situation. Try these out if you’re still having issues running applications with elevated privileges:

* [Repair Corrupted System Files](https://www.makeuseof.com/windows-built-in-repair-tools/): It restores your computer’s corrupted and missing system files. Use them to repair the root cause of the issue.
* [Perform a Clean Boot](https://www.makeuseof.com/clean-boot-windows-11/): When you start Windows in a clean boot state, the operating system will only run essential services and programs. It identifies any third-party software causing the issue.
* [Create a New Administrator User Account](https://www.makeuseof.com/tag/windows-administrator-account-everything-need-know/): If all else fails, try creating a new administrator user account and logging in. This ascertains if your existing account is corrupted or not.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Troubleshooting Run as Administrator on Windows

 We hope this guide helped you solve the Run as administrator not working on Windows issue. Despite the prevalence of this problem, it’s relatively easy to fix if you know what to do.

 If none of the troubleshooting steps worked, try running a system scan using an advanced antivirus program. Some malicious programs prevent you from running as an administrator. A complete system scan should find and remove any malicious software on your computer, so you can start using it again.

 That’s where this guide comes into play. So, let’s look at what you can do to fix Run as administrator not working on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-elevate-persuasion-through-30-powerful-video-themes/"><u>[New] In 2024, Elevate Persuasion Through 30 Powerful Video Themes</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-the-ultimate-guide-to-scheduling-zoom-events/"><u>[New] In 2024, The Ultimate Guide to Scheduling Zoom Events</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-producing-dynamic-content-for-discord-channels/"><u>[New] Producing Dynamic Content for Discord Channels</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-az-screen-recorder-review-series/"><u>[Updated] AZ Screen Recorder Review Series</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-techniques-to-transfer-data-from-infinix-smart-8-pro-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Techniques to Transfer Data from Infinix Smart 8 Pro to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/8-premier-no-lag-screen-capture-tools/"><u>8 Premier No-Lag Screen Capture Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-missing-d3dx939-dll-in-win11/"><u>Addressing Missing D3DX9_39 DLL in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-productivity-integrating-flow-launcher-into-daily-routine/"><u>Amplify Productivity: Integrating Flow Launcher Into Daily Routine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/audio-recording-basics-for-newcomers-on-win-11/"><u>Audio Recording Basics for Newcomers on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphered-defense-dont-shift-too-suddenly/"><u>Deciphered Defense? Don't Shift Too Suddenly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-how-to-access-mspaint-in-windows-11/"><u>Discovering How to Access MSPaint in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-time-intensive-gpsvc-hangs/"><u>Eliminating Time-Intensive GPSVC Hangs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/file-system-exploration-in-win11-6-keyways-to-duplicating-file-and-folder-paths/"><u>File System Exploration in Win11: 6 Keyways to Duplicating File and Folder Paths</u></a></li>
<li><a href="https://win11-tips.techidaily.com/finding-files-in-flux-top-6-methods-to-extract-and-duplicate-windows-11-folder-trails/"><u>Finding Files in Flux: Top 6 Methods to Extract and Duplicate Windows 11 Folder Trails</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-users-through-compatibility-challenges-with-intel-gpu/"><u>Guiding Users Through Compatibility Challenges with Intel GPU</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-turn-off-find-my-apple-iphone-15-pro-when-phone-is-broken-by-drfone-ios/"><u>How to Turn Off Find My Apple iPhone 15 Pro when Phone is Broken?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-5-ways-to-track-tecno-phantom-v-flip-without-app-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Ways to Track Tecno Phantom V Flip without App | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-building-your-brands-buzz-on-youtube-with-fresh-insights/"><u>In 2024, Building Your Brand's Buzz on Youtube with Fresh Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-windows-startup-the-comprehensive-guidebook/"><u>Master Your Windows Startup: The Comprehensive Guidebook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-automation-for-batch-files/"><u>Mastering Windows Automation for Batch Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-teams-speed-and-efficiency-upgrade/"><u>Microsoft Teams' Speed & Efficiency Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimizing-browser-heft-comparing-best-options-for-low-ram-usage/"><u>Minimizing Browser Heft: Comparing Best Options for Low RAM Usage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11-read-only-folder-issues/"><u>Overcoming Windows 11 Read-Only Folder Issues</u></a></li>
<li><a href="https://facebook.techidaily.com/pivot-to-profit-5-effective-techniques-for-earning-on-fb-and-insta/"><u>Pivot to Profit: 5 Effective Techniques for Earning on FB and Insta</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rethinking-default-browsing-in-newest-windows-os/"><u>Rethinking Default Browsing in Newest Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-your-systems-graphics-with-windows-11-tips/"><u>Revive Your System's Graphics with Windows 11 Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-digital-management-with-windows-automatic-file-disposal/"><u>Simplify Digital Management with Windows' Automatic File Disposal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steering-with-apple-maps-from-a-pc/"><u>Steering with Apple Maps From a PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/supercharge-your-pc-top-5-windows-speed-solutions/"><u>Supercharge Your PC: Top 5 Windows Speed Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-frozen-volume-shadows-in-operating-systems/"><u>Tackling Frozen Volume Shadows in Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-resource-allocation-within-wsl-android-environment/"><u>Tailoring Resource Allocation Within WSL-Android Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-why-files-carry-an-x-marking/"><u>Understanding Why Files Carry an X Marking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-do-numbers-on-windows-updates-stand-for/"><u>What Do Numbers on Windows Updates Stand For?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-ram-a-quick-guide-for-efficient-identification/"><u>Windows RAM: A Quick Guide for Efficient Identification</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>