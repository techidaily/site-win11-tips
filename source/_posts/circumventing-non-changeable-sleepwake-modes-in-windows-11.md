---
title: Circumventing Non-Changeable Sleep/Wake Modes in Windows 11
date: 2024-08-16T01:41:21.748Z
updated: 2024-08-17T01:41:21.748Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Circumventing Non-Changeable Sleep/Wake Modes in Windows 11
excerpt: This Article Describes Circumventing Non-Changeable Sleep/Wake Modes in Windows 11
keywords: Windows Wake Control,Bypass Power Modes,Win11 Sleep Disabling,Modify Wake Settings,Circumvent Deep Sleep,Enable On-Demand Boot,Dynamic Windows Wake
thumbnail: https://thmb.techidaily.com/a84f233e2df716933c1def7036ee5f60e5a298fe75b79753bbc6bfd2f6d9a6e5.jpg
---

## Circumventing Non-Changeable Sleep/Wake Modes in Windows 11

 Power modes on Windows are a mix of hardware and system settings that determine how and where your device will spend its power. Windows has three power modes by default; Balanced, Best performance, and Best power efficiency.

 Changing these modes is quite simple, but in some cases, users can face difficulty jumping from one mode to another. So, we examine what might be causing the problem and how to troubleshoot it.

## Why Can't You Change the Power Mode in Windows 11?

 Several factors can prevent you from changing the power mode in Windows. Here are the most common reasons behind this problem:

* You are using a custom power plan. When on a customized power plan, Windows does not allow you to switch to a different power mode in Settings. This problem can be fixed by choosing the Balanced power plan, which is recommended for Windows.
* The current power plan is faulty. In some cases, the users found out that the issue was caused due to some restriction related to their current power plan. This problem can be resolved by simply switching to a different plan, as we will discuss below.
* A corruption issue within the system is causing the problem. The best way to rule out such problems is by running the Power troubleshooter built into Windows.

 Now that we know what can cause the problem, let's look at what you can do to solve it.

## 1\. Change the Power Plan

 The first thing we recommend you do is switch to a different power plan, especially if you are using a custom power plan. We suggest shifting to the Balanced plan and checking if that fixes the issue. This plan optimizes the performance automatically. This means it will activate the full performance mode when you are actively using the computer and switch to the power-saving mode when you are not.

Here is how you can proceed:

1. Open a Run dialog box by pressing the Win + R keys together.
2. Type control in the text field of Run and click**Enter** .
3. In the following window, expand the**View by** category at the top and choose**Large icons** .  
![Click on Large icons option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/large-icons-control-panel.jpg)
4. Now, look for**Power options** and click on it.  
![Click on Power Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/win11-power-options.jpg)
5. You should now be able to see your current power plan. Click on**Create a power plan** in the left pane.  
![Create a power plan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/create-power-plan-1.jpg)
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Choose the**Balanced power plan** and click**Next** \>**Create** .  
![Click on the Create button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/create-power-plan-next-create.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->

Once done, check if you can now change the power mode successfully.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
## 2\. Run the Power Troubleshooter

 Your system can also be dealing with some kind of corruption issue that is causing the power modes and plans to act up. In this scenario, the best way to proceed is by running the Power troubleshooter.

 This utility is located in the Troubleshoot section of Windows Settings and works by scanning the system for potential issues. If a problem within the system is identified, it will notify you and then suggest relevant fixes.

Here is how you can run the troubleshooter:

1. Press the Win + I keys together to open the Settings app.
2. Choose**System** \>**Troubleshoot** in the following window.
3. Click on**Other troubleshooters** .  
![Click on Other troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/other-troubleshooters-win11.jpg)
4. Now, look for the Power troubleshooter and click on the**Run** button for it.  
![Run the Power troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/power-troubleshooter-win11.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Wait for the troubleshooter to complete its process, and then check the results. If the troubleshooter has found any issues, click on**Apply this fix** to proceed with the relevant solutions. Otherwise, click on**Close the troubleshooter** and move to the next method below.

## 3\. Reset the Power Settings

 If changing the power plan did not do the trick for you, you can try resetting the power settings to their default state. They will revert to how they were when you began using Windows, thus fixing the error at hand.

Follow these steps to proceed:

1. Press the Win + R keys together to open a Run dialog.
2. Type cmd in the text field of Run and press Ctrl + Shift + Enter to open Command Prompt with administrative privileges.
3. Click**Yes** in the User Account Control prompt.
4. Once you are inside the Command Prompt window, type the command mentioned below and hit Enter to execute it:  
powercfg –restoredefaultscheme ![Restore the default power theme](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/powercfg-restoredefaultschemes.jpg)
<!-- affiliate ads begin -->
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
<!-- affiliate ads end -->
5. Once the command is executed, check if you can change the power mode successfully.

 In case the power plan changes again after a short while of executing this method, you will need to make changes as an administrator in the Group Policy Editor.

Here is how you can do that:

1. [Open the Group Policy Editor as an administrator](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .
2. Now, head over to the following location:  
Computer Configuration -> Administrative Templates -> System -> Power Management
3. Locate the**Select an active power plan** option in the right pane and double-click on it.  
![Choose the Select an active power plan policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/select-an-active-power-plan.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Choose**Enabled** and then choose the targeted power plan from the dropdown.
5. Click**Apply** \>**OK** to save the changes, and then restart your computer.

Hopefully, this will resolve the issue.

## 4\. Revert the System to an Older Working State

 Another way to fix the problem is by reverting the system back to a state where you can change the power modes without any issues. This can be achieved using the System Restore feature,[one of the most important PC-Saving Windows Tools available](https://www.makeuseof.com/tag/8-pc-saving-windows-tools-must-not-overlook/) , which periodically creates restore points on the system.

 The restore points represent a point in time when the system was in a certain state, and by choosing one, you can return the system to that point in time.

 In this case, you can choose a state where the current issue is not present.

## Switch Power Modes Easily

 By now, you should be able to switch the power modes successfully. However, if you are still experiencing the problem and cannot find a way around it, then you can contact the official Microsoft team and report the issue to them. They will likely be able to find the root cause of the issue and suggest a fix.

 If nothing really works, you can always clean install Windows to give it a fresh, error-free start.


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
<li><a href="https://on-screen-recording.techidaily.com/new-windows-10-ultimate-screen-capture-tool-for-2024/"><u>[New] Windows 10  Ultimate Screen Capture Tool for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-effortless-video-upload-from-apple-devices-to-youtube-channel/"><u>[Updated] Effortless Video Upload From Apple Devices to YouTube Channel</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-elevate-your-reddit-presence-with-proactive-tips/"><u>[Updated] Elevate Your Reddit Presence with Proactive Tips</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-ergonomic-hold-techniques-for-clarity/"><u>[Updated] In 2024, Ergonomic Hold Techniques for Clarity</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-step-into-the-spotlight-learning-youtube-vlogger-etiquette/"><u>[Updated] Step Into the Spotlight  Learning YouTube Vlogger Etiquette</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-top-8-social-tools-to-skyrocket-your-likes-on-facebook-for-2024/"><u>[Updated] Top 8 Social Tools to Skyrocket Your Likes on Facebook for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-a-complete-rundown-reels-vs-stories-on-instagram/"><u>2024 Approved  A Complete Rundown  Reels vs Stories on Instagram</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-techniques-for-text-in-the-windows-snip-tool/"><u>Advanced Techniques for Text in the Windows Snip Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoidance-tactics-skirting-windows-account-sign-ins/"><u>Avoidance Tactics: Skirting Windows Account Sign-Ins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-ms-defenders-restrictions-for-additional-virus-protection/"><u>Bypassing MS Defender's Restrictions for Additional Virus Protection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-windows-11-boot-tracks-step-by-step-guide/"><u>Clearing Windows 11 Boot Tracks: Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-mcuicntexe-non-existent-window-complaint/"><u>Dealing with McUICnt.exe Non-Existent Window Complaint</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-missing-pages-in-microsoft-store-windows/"><u>Dealing with Missing Pages in Microsoft Store Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/declutter-drive-space-recognizing-the-leviathans-in-windows-pcs/"><u>Declutter Drive Space: Recognizing the Leviathans in Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/getting-the-best-bargains-on-essential-windows-11-codes/"><u>Getting the Best Bargains on Essential Windows 11 Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-windows-to-run-this-application-you-must-install-net-core-error/"><u>How to Fix the Windows “To Run This Application, You Must Install .NET Core” Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-remove-the-background-of-an-image-using-paint-or-paint-3d/"><u>How to Remove the Background of an Image Using Paint or Paint 3D</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-nokia-g42-5g-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Nokia G42 5G</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-airplane-mode-turn-off-gps-location-on-oppo-a59-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Does Airplane Mode Turn off GPS Location On Oppo A59 5G? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-i-transferred-messages-from-tecno-camon-20-premier-5g-to-iphone-12xs-max-in-seconds-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How I Transferred Messages from Tecno Camon 20 Premier 5G to iPhone 12/XS (Max) in Seconds | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-come-up-with-the-best-pokemon-team-on-vivo-s18-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Come up With the Best Pokemon Team On Vivo S18 Pro? | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-introduction-to-moving-visual-content/"><u>In 2024, Introduction to Moving Visual Content</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-primeworldplus-local-complete-tv-content-at-fingertips/"><u>In 2024, PrimeWorld+ Local  Complete TV Content at Fingertips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insight-into-cab-files-their-purpose-within-the-windows-domain/"><u>Insight Into CAB Files: Their Purpose Within the Windows Domain</u></a></li>
<li><a href="https://win11-tips.techidaily.com/invisible-culprits-affecting-windows-11s-efficiency/"><u>Invisible Culprits Affecting Windows 11'S Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keyboard-keyscalyping-restore-your-arrows-now/"><u>Keyboard Keyscalyping? Restore Your Arrows Now</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/optimal-tactics-for-saving-android-interactions/"><u>Optimal Tactics for Saving Android Interactions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-challenges-with-steams-downloading-functionality-during-updates/"><u>Overcoming Challenges with Steam's Downloading Functionality During Updates</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/pokemon-go-error-12-failed-to-detect-location-on-apple-iphone-14-pro-max-drfone-by-drfone-virtual-ios/"><u>Pokemon Go Error 12 Failed to Detect Location On Apple iPhone 14 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/process-of-screen-sharing-oppo-a59-5g-to-pc-detailed-steps-drfone-by-drfone-android/"><u>Process of Screen Sharing Oppo A59 5G to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-blue-screens-resulting-from-wins-intruder-exception/"><u>Quick Fixes for Blue Screens Resulting From Win's Intruder Exception</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-modifying-login-credentials-on-win-11/"><u>Quick Guide to Modifying Login Credentials on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaiming-missing-power-configurations-in-win-11-os/"><u>Reclaiming Missing Power Configurations in Win 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-deactivated-office-alerts-in-windows/"><u>Resolving Deactivated Office Alerts in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seize-the-deal-unmissable-black-friday-612-win10/"><u>Seize the Deal: Unmissable Black Friday - $6.12 Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-malfunctioning-office-notification-system/"><u>Solving Malfunctioning Office Notification System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-to-windows-11-character-map/"><u>Step-by-Step to Windows 11 Character Map</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-eliminating-nvidia-experience-disconnect-issues/"><u>Strategies for Eliminating Nvidia Experience Disconnect Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-access-and-manage-gpo-settings-in-win11/"><u>Swiftly Access and Manage GPO Settings in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-minimizing-disruptions-in-windows-updates/"><u>The Art of Minimizing Disruptions in Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essentials-for-successful-intel-lan-setup-on-vista/"><u>The Essentials for Successful Intel LAN Setup on Vista</u></a></li>
<li><a href="https://android-frp.techidaily.com/the-updated-method-to-bypass-oppo-a78-frp-by-drfone-android/"><u>The Updated Method to Bypass Oppo A78 FRP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-resolving-battlenet-not-available-errors-on-win-1011/"><u>Tips for Resolving Battle.net Not Available Errors on Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-2023-laptop-reveals-ifa-edition/"><u>Top 2023 Laptop Reveals - IFA Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-reasons-to-choose-win11-over-apples-macos/"><u>Top Reasons to Choose Win11 Over Apple's macOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-secure-boot-status-a-windows-bios-solution-manual/"><u>Unlocking Secure Boot Status: A Windows BIOS Solution Manual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-10-step-roadmap-to-winrm/"><u>Unraveling the 10-Step Roadmap to WinRM</u></a></li>
<li><a href="https://howto.techidaily.com/want-to-uninstall-google-play-service-from-samsung-galaxy-s24-ultra-here-is-how-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Want to Uninstall Google Play Service from Samsung Galaxy S24 Ultra? Here is How | Dr.fone</u></a></li>
</ul></div>
