---
title: "Navigating Windows Security: Running As Administrator"
date: 2024-07-12T17:19:26.930Z
updated: 2024-07-13T17:19:26.930Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Navigating Windows Security: Running As Administrator"
excerpt: "This Article Describes Navigating Windows Security: Running As Administrator"
keywords: Admin Privilege Execution,Secure Windows Login,Windows OS Protection,Run As Admin Guide,System Access Management,User Account Control,Security Settings Roleplay
thumbnail: https://thmb.techidaily.com/d20fb0a2bb9049e2210bb23aa9225c390244059cedf35b9a34d45f9a041c8543.jpg
---

## Navigating Windows Security: Running As Administrator

 Windows offers a Run as administrator option that allows users to run applications and programs with administrator privileges. You can also use it to troubleshoot computer issues. But what if this feature malfunctions, depriving you of administrator rights?

 That’s where this guide comes into play. So, let’s look at what you can do to fix Run as administrator not working on Windows.

## What Causes Run as Administrator Not Working?

 Before you start fixing things, you must understand what causes this issue. In general, you may experience Run as administrator not working due to the following reasons:

* Group Policy or User Account Control (UAC) blocks the application or program you’re trying to run.
* The user account associated with your device isn’t an administrator account and therefore doesn’t have the necessary privileges.
* Corrupt system files or registry entries could prevent you from running administrator programs.
* Malware infection on your computer could disrupt the feature.

 Now that you know the potential causes of this issue, let’s look at ways to fix it. ​​​

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
6. Now exit the Registry Editor and restart your computer.

 Once your computer reboots, you will see the Run as administrator option in the context menu. Try running a program with elevated privileges and see if it works.

## 6\. Try Some Generic Fixes

 Besides the fixes mentioned above, some generic solutions work in any situation. Try these out if you’re still having issues running applications with elevated privileges:

* [Repair Corrupted System Files](https://www.makeuseof.com/windows-built-in-repair-tools/): It restores your computer’s corrupted and missing system files. Use them to repair the root cause of the issue.
* [Perform a Clean Boot](https://www.makeuseof.com/clean-boot-windows-11/): When you start Windows in a clean boot state, the operating system will only run essential services and programs. It identifies any third-party software causing the issue.
* [Create a New Administrator User Account](https://www.makeuseof.com/tag/windows-administrator-account-everything-need-know/): If all else fails, try creating a new administrator user account and logging in. This ascertains if your existing account is corrupted or not.

## Troubleshooting Run as Administrator on Windows

 We hope this guide helped you solve the Run as administrator not working on Windows issue. Despite the prevalence of this problem, it’s relatively easy to fix if you know what to do.

 If none of the troubleshooting steps worked, try running a system scan using an advanced antivirus program. Some malicious programs prevent you from running as an administrator. A complete system scan should find and remove any malicious software on your computer, so you can start using it again.

 That’s where this guide comes into play. So, let’s look at what you can do to fix Run as administrator not working on Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-startup-paths-essential-steps/"><u>Unlocking Windows' Startup Paths: Essential Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-normalcy-windows-11s-basic-user-reset-guide/"><u>Unleashing Normalcy: Windows 11'S Basic User Reset Guide</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-a-new-era-of-streaming-leading-voices-of-female-creators/"><u>[Updated] A New Era of Streaming  Leading Voices of Female Creators</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-the-ultimate-screen-capture-showdown-free-vs-paid-cam-recorders/"><u>[Updated] The Ultimate Screen Capture Showdown  Free vs Paid Cam Recorders</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-understanding-macos-big-sur-minimum-requirements/"><u>[Updated] 2024 Approved  Understanding MacOS Big Sur  Minimum Requirements</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-fix-fixed-no-more-obs-camera-issues/"><u>In 2024, Fix Fixed  No More OBS Camera Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensively-correcting-stuck-batch-files-on-windows/"><u>Comprehensively Correcting Stuck Batch Files on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/web-accessibility-in-the-absence-of-built-in-browser/"><u>Web Accessibility in the Absence of Built-In Browser</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-change-desktop-icon-spacing-in-windows-11-and-10/"><u>How to Change Desktop Icon Spacing in Windows 11 and 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-printer-access-for-windows-users/"><u>Unblocking Printer Access for Windows Users</u></a></li>
<li><a href="https://screen-recording.techidaily.com/cinematic-clips-reviewed-best-in-the-business/"><u>Cinematic Clips Reviewed  Best in the Business</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-old-school-games-a-guide-to-adding-achievements-via-retroarch/"><u>Boosting Old-School Games: A Guide to Adding Achievements via Retroarch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-recurring-anydesk-windows-anomalies/"><u>Unraveling Recurring AnyDesk Windows Anomalies</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-2024-10-must-know-iphone-x-tricks-to-enhance-usage/"><u>[New] In 2024, 10 Must-Know iPhone X Tricks to Enhance Usage</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-20plus-digital-hubs-unlimited-image-access-for-all/"><u>[Updated] 20+ Digital Hubs  Unlimited Image Access for All</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-web-speed-contrast-in-your-tech-world/"><u>Addressing the Web Speed Contrast in Your Tech World</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-hottest-online-spots-customized-packaging-at-your-fingertips/"><u>2024 Approved  Hottest Online Spots  Customized Packaging at Your Fingertips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-windows-shop-failure-x800704cf/"><u>Deciphering Windows Shop Failure X800704CF</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-online-retrobing-navigating-youtubes-deleted-content/"><u>[New] Online Retrobing  Navigating YouTube’s Deleted Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-the-distinctions-between-windows-terminal-and-powershell/"><u>Analyzing The Distinctions Between Windows Terminal and PowerShell</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/insta-vid-techniques-scaling-videos-to-perfect-size-in-fcpx-for-2024/"><u>Insta-Vid Techniques  Scaling Videos to Perfect Size in FCPX for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-comedy-crusade-youtubes-hottest-laughter-leaders-for-2024/"><u>[Updated] Comedy Crusade  YouTube's Hottest Laughter Leaders for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-gateway-how-to-enter-os-settings/"><u>The Gateway: How to Enter OS Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-definitive-window-by-window-walkthrough-of-hdr-in-windows-11/"><u>The Definitive Window-by-Window Walkthrough of HDR in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/visualize-storage-quickly-integrate-diskanalyzer-into-windows-menu/"><u>Visualize Storage Quickly: Integrate DiskAnalyzer Into Windows Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-distinctions-a-comparative-analysis-of-standard-login-vs-microsoft-account-on-pcs/"><u>Dissecting Distinctions: A Comparative Analysis of Standard Login vs Microsoft Account on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/wired-for-security-swiftly-repairing-windows-features/"><u>Wired for Security: Swiftly Repairing Windows Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-unable-to-open-geforce-experience-error/"><u>Troubleshooting Unable to Open GeForce Experience Error</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/decoding-instagram-selfies-the-validation-handbook/"><u>Decoding Instagram Selfies  The Validation Handbook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-ways-to-open-the-local-group-policy-editor-in-windows-11/"><u>10 Ways to Open the Local Group Policy Editor in Windows 11</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-the-battle-of-screen-capture-supremacy-obs-vs-fraps-for-2024/"><u>[Updated] The Battle of Screen Capture Supremacy  OBS vs Fraps for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-customization-top-20-settings-for-enhanced-performance/"><u>Windows 11 Customization: Top 20 Settings for Enhanced Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-a-personalized-look-with-these-easy-to-follow-theme-steps-for-win11/"><u>Achieve a Personalized Look with These Easy-to-Follow Theme Steps for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-store-error-with-xbox-games/"><u>Troubleshooting Windows Store Error with Xbox Games</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/in-2024-out-of-obscurity-reversing-tiktoks-stealth-ban/"><u>In 2024, Out of Obscurity  Reversing TikTok's Stealth Ban</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-mysteries-of-microsofts-copilot-key-in-windows-11/"><u>Unveiling the Mysteries of Microsoft's Copilot Key in Windows 11</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-enhancing-the-speed-of-vimeo-videos/"><u>[Updated] In 2024, Enhancing the Speed of Vimeo Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-correcting-windows-error-code-0x80071a90/"><u>Understanding and Correcting Windows Error Code: 0X80071A90</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-free-and-fast-guide-to-detecting-fraudulent-accounts-among-instragrammers/"><u>2024 Approved  Free & Fast Guide to Detecting Fraudulent Accounts Among Instragrammers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reacquire-lost-copilot-in-ws11-journeys/"><u>How To Reacquire Lost Copilot In WS11 Journeys</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-tweeting-trouble-laughter-league/"><u>2024 Approved  Tweeting Trouble  Laughter League</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-xpatch-puzzle-error-0x80073712/"><u>Decoding Windows XPatch Puzzle: Error 0X80073712</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-top-10-places-for-accessing-gratis-graphics/"><u>[New] Top 10 Places for Accessing Gratis Graphics</u></a></li>
<li><a href="https://extra-support.techidaily.com/pictorial-humor-ranking-10-memes-by-creativity-for-2024/"><u>Pictorial Humor  Ranking #10 Memes by Creativity for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unplugging-problems-addressing-frequent-ps4-disconnection-in-pc/"><u>Unplugging Problems: Addressing Frequent PS4 Disconnection in PC</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-harnessing-the-power-of-asynchronous-programming-in-javascript/"><u>[Updated] Harnessing the Power of Asynchronous Programming in JavaScript</u></a></li>
<li><a href="https://howto.techidaily.com/fix-cant-take-screenshot-due-to-security-policy-on-vivo-x-flip-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Cant Take Screenshot Due to Security Policy on Vivo X Flip | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/imovie-for-newbies-a-comprehensive-tutorial-on-adding-audio-for-2024/"><u>IMovie for Newbies A Comprehensive Tutorial on Adding Audio for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-windows-drive-space-without-spending-a-dime/"><u>Elevate Windows Drive Space Without Spending a Dime</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-correcting-wmp-failures/"><u>Understanding & Correcting WMP Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-and-11-gaming-experience-boosted-by-solving-directdraw-errors/"><u>Windows 11 & 11 Gaming Experience Boosted by Solving DirectDraw Errors</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-join-the-social-gaming-movement-xbox-and-fb-livestreams/"><u>[New] 2024 Approved  Join the Social Gaming Movement  Xbox & FB Livestreams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-a-recycle-bin-corrupted-error-on-windows-11-and-11/"><u>How to Fix a Recycle Bin Corrupted Error on Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/experience-the-pinnacle-of-windows-interactivity/"><u>Experience the Pinnacle of Windows Interactivity</u></a></li>
</ul></div>
