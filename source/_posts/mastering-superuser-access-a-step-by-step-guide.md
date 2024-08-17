---
title: "Mastering Superuser Access: A Step-by-Step Guide"
date: 2024-08-16T02:19:30.870Z
updated: 2024-08-17T02:19:30.870Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Superuser Access: A Step-by-Step Guide"
excerpt: "This Article Describes Mastering Superuser Access: A Step-by-Step Guide"
keywords: Superuser Mastery,User Privileges Guide,Gain Admin Control,Secure System Entry,Enhance Root Access,Elevate Permissions,Command Line Expertise
thumbnail: https://thmb.techidaily.com/a84f233e2df716933c1def7036ee5f60e5a298fe75b79753bbc6bfd2f6d9a6e5.jpg
---

## Mastering Superuser Access: A Step-by-Step Guide

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
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Drag the slider to **Default**, then click **OK**. It will set your UAC to the default level and enable you to run applications with elevated privileges.

 Now, close the window and restart your PC. After that, try running the application with the Run as administrator feature and see if it works.

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
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
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
5. Doing this will open another window. Here, select the **Disabled** option and click **Apply** \> **OK**.  
![Disable User Account Control in Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-user-account-control-in-group-policy.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
6. Close the Local Group Policy Editor and restart your computer.

 After restarting, try running a program with elevated privileges. It should work now. Don't forget to re-enable the Admin Approval Mode setting once you're finished troubleshooting.

<!-- affiliate ads begin -->

<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
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
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-ballot-box-bonanza-topping-politic-simulations/"><u>[New] 2024 Approved  Ballot Box Bonanza  Topping Politic Simulations</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-easeus-screen-recorder-featuresreview/"><u>[New] 2024 Approved  EaseUS Screen Recorder Features|Review</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-how-to-rotate-youtube-videos-by-any-angle/"><u>[New] 2024 Approved  How to Rotate YouTube Videos by Any Angle</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/-creators-guide-to-understanding-youtube-policies-for-2024/"><u>[New] A Creator’s Guide to Understanding YouTube Policies for 2024</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-pulse-pounding-perfection-create-compelling-tiktok-videos-with-templates/"><u>[New] Pulse-Pounding Perfection  Create Compelling TikTok Videos with Templates</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-securing-the-title-top-5-hmds-for-drone-pilots-for-2024/"><u>[New] Securing the Title  Top 5 HMDs for Drone Pilots for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-become-a-facetime-pro-skype-call-basics-for-mobile-users/"><u>[Updated] Become a Facetime Pro  Skype Call Basics for Mobile Users</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-creating-momentum-in-life-coaching-video-series/"><u>[Updated] In 2024, Creating Momentum in Life Coaching Video Series</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-instagram-video-timing-what-you-need-to-know/"><u>[Updated] Instagram Video Timing  What You Need To Know</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-ios-snapshot-spectrum-your-quick-reference-for-2024/"><u>[Updated] IO's Snapshot Spectrum  Your Quick Reference for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-teachers-handbook-building-a-successful-youtube-channel-10-must-dos/"><u>[Updated] Teachers' Handbook  Building a Successful YouTube Channel – 10 Must-Dos</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-unveiling-the-ideal-youtube-subset-of-viewers-for-2024/"><u>[Updated] Unveiling the Ideal YouTube Subset of Viewers for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-utilizing-picture-in-picture-feature-across-all-chrome-devices-for-2024/"><u>[Updated] Utilizing Picture In Picture Feature Across All Chrome Devices for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-tips-to-design-an-eye-catching-logo-for-podcasts/"><u>2024 Approved  Tips to Design an Eye-Catching Logo for Podcasts</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-easy-ways-to-copy-contacts-from-itel-p55t-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Easy Ways to Copy Contacts from Itel P55T to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/amplify-pictorial-points-using-rings-of-radial-focus/"><u>Amplify Pictorial Points Using Rings of Radial Focus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-the-corrupted-windows-11-trash-issue/"><u>Correcting the Corrupted Windows 11 Trash Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-edge-methods-for-faster-epic-game-installs/"><u>Cutting-Edge Methods for Faster Epic Game Installs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-meaning-and-solution-of-winerror-0x80071a90/"><u>Decoding the Meaning & Solution of WinError 0X80071a90</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delving-into-automated-software-fixes-windows-way/"><u>Delving Into Automated Software Fixes: Windows Way</u></a></li>
<li><a href="https://win11-tips.techidaily.com/desk-dilemmas-taming-the-pink-and-purple-on-your-screen/"><u>Desk Dilemmas: Taming the Pink & Purple on Your Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-superuser-in-terminal-a-step-by-step-guide/"><u>Enabling Superuser in Terminal: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-windows-information-discovery-everywhereapp-style/"><u>Enhance Windows Information Discovery, EverywhereApp Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/epic-color-crisis-8-ways-to-retool-your-pink-desktop/"><u>Epic Color Crisis: 8 Ways to Retool Your Pink Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-using-outlook-preview-in-windows-11/"><u>Essential Tips for Using Outlook Preview in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-making-windows-menus-less-obvious/"><u>Expert Tips: Making Windows Menus Less Obvious</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-absence-of-files-notification-on-win-11/"><u>Fixing Absence of Files Notification on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-responsive-volume-control-on-win-1011-pc/"><u>Fixing Responsive Volume Control on Win 10/11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/getting-to-know-wintoys-your-intuitive-guide-to-an-underutilized-tool-in-windows/"><u>Getting to Know WinToys: Your Intuitive Guide to an Underutilized Tool in Windows</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/harvesting-hours-top-10-friendly-farm-gaming-experiences-for-2024/"><u>Harvesting Hours  Top 10 Friendly Farm Gaming Experiences for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-ccleaner-not-working-on-windows-10-and-11/"><u>How to Fix CCleaner Not Working on Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-generate-a-group-policy-report-with-the-gpresult-command/"><u>How to Generate a Group Policy Report With the GPResult Command</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-view-and-clear-the-windows-11-activity-history/"><u>How to View and Clear the Windows 11 Activity History</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-vivo-x90s-by-drfone-android/"><u>In 2024, 10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Vivo X90S</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-2-ways-to-monitor-xiaomi-redmi-note-12-pro-5g-activity-drfone-by-drfone-virtual-android/"><u>In 2024, 2 Ways to Monitor Xiaomi Redmi Note 12 Pro 5G Activity | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-2023s-top-8-video-sensations-a-facebook-deep-dive/"><u>In 2024, 2023'S Top 8 Video Sensations  A Facebook Deep Dive</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-on-infinix-gt-10-pro-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock on Infinix GT 10 Pro Devices</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-selecting-the-perfect-day-for-podcast-drops/"><u>In 2024, Selecting the Perfect Day for Podcast Drops</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-the-ultimate-method-for-recorded-instagram-stories/"><u>In 2024, The Ultimate Method for Recorded Instagram Stories</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/mastering-video-capturing-made-simple-a-complete-guide-using-zd-software/"><u>Mastering Video Capturing Made Simple  A Complete Guide Using ZD Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/msstore-dilemma-resolving-windows-error-code-0x0-in-3-steps/"><u>MsStore Dilemma - Resolving Windows Error Code 0X0 in 3 Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mute-functionality-disabling-windows-11-tasks/"><u>Mute Functionality: Disabling Windows 11 Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-past-error-x80072f30-in-windows-store/"><u>Navigate Past Error X80072F30 in Windows Store</u></a></li>
<li><a href="https://driver-download.techidaily.com/official-hp-deskjet-2600-drivers-easy-installation-guide-for-win-7810-users/"><u>Official HP DeskJet 2600 Drivers: Easy Installation Guide for Win 7/8/10 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-teams-screen-failures/"><u>Overcoming Teams Screen Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/power-saving-perplexities-the-tale-of-windows-standby/"><u>Power Saving Perplexities: The Tale of Windows' Standby</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-the-0x80072746-email-failure-on-windows-pc/"><u>Resolving the 0X80072746 Email Failure on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-disconnected-remote-resources-on-your-pc/"><u>Reviving Disconnected Remote Resources on Your PC</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/screensphere-comprehensively-global-plus-locally-connected-for-2024/"><u>ScreenSphere  Comprehensively Global + Locally Connected for 2024</u></a></li>
<li><a href="https://driver-download.techidaily.com/secure-and-fast-download-csr-bluetooth-chip-drivers-for-immediate-use/"><u>Secure & Fast: Download CSR Bluetooth Chip Drivers for Immediate Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/selecting-and-styling-terminal-image/"><u>Selecting and Styling Terminal Image</u></a></li>
<li><a href="https://extra-skills.techidaily.com/sonys-vision-for-immersive-video-exploring-xperia-xz-premium-for-2024/"><u>Sony's Vision for Immersive Video  Exploring Xperia XZ Premium for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-and-fix-crashed-epic-games-launcher-window/"><u>Stop & Fix Crashed Epic Games Launcher Window</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-smarter-android-resource-use-in-wsl/"><u>Strategies for Smarter Android Resource Use in WSL</u></a></li>
<li><a href="https://win11-tips.techidaily.com/synergizing-macos-and-windows-software/"><u>Synergizing macOS and Windows Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-aesthetic-enhancement-implementing-themes-from-the-microsoft-store/"><u>The Art of Aesthetic Enhancement: Implementing Themes From the Microsoft Store</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-complete-guide-to-iphone-silhouette-mastery/"><u>The Complete Guide to iPhone Silhouette Mastery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/time-saving-windows-keyboard-tricks-for-swift-tasks/"><u>Time-Saving Windows: Keyboard Tricks for Swift Tasks</u></a></li>
<li><a href="https://app-tips.techidaily.com/top-alternative-podcast-apps-to-replace-player-fm-on-your-android-device/"><u>Top Alternative Podcast Apps to Replace Player FM on Your Android Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-seven-pocket-friendly-tools-to-increase-windows-volume/"><u>Top Seven Pocket-Friendly Tools to Increase Windows Volume</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshoot-airpods-charge-issues-with-these-9-effective-tips/"><u>Troubleshoot AirPods Charge Issues with These 9 Effective Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-0xc00000f-windows-problems/"><u>Troubleshooting 0xC00000F Windows Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-sniptools-unresponsive-commands/"><u>Troubleshooting SnipTool's Unresponsive Commands</u></a></li>
</ul></div>
