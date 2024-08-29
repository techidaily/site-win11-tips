---
title: Reclaiming Previously Erased Sleep Mode Profiles
date: 2024-08-28T01:13:12.045Z
updated: 2024-08-29T01:13:12.045Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reclaiming Previously Erased Sleep Mode Profiles
excerpt: This Article Describes Reclaiming Previously Erased Sleep Mode Profiles
keywords: Restore Sleep Modes,Reset Sleep Profile,Reinstate Sleep Settings,Override Firmware Sleep,Erase and Reclaim Sleep Profiles,Regain Sleep Mode,Undelete Sleep Schedule
thumbnail: https://thmb.techidaily.com/9827a92b9acfe7ff5ad59fca7934fb301cf15e62dfa6be6fe2bedc9f0e414ea5.jpg
---

## Reclaiming Previously Erased Sleep Mode Profiles

 Windows 11 and 10 come with preset power plans: High Performance, Power Saver, Balanced, and sometimes Ultimate Performance. You can switch between these plans to get the best performance, more battery life or a bit of both worlds. Some laptop manufacturers, like HP, have their own power plan, like HP Recommended.

 However, often after installing a Windows update, default power plans can go missing, or you may see only one power plan. This can also happen if you have made changes to your power plans recently. In any case, here are a few troubleshooting steps to help restore the missing default power plans on Windows 11 and 10 running systems.

## How to Check Which Power Plan Is Missing

![check missing power plans control panel windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-missing-power-plans-control-panel-windows-11.jpg)

 Depending on your system hardware specification, you may see three or four power plans in the Power Options panel. Balanced, Power Saver and High Performance are the most common in all Windows computers.

 However, higher-end hardware running Windows 11\\10 Pro can have the Ultimate Performance Power plan as well. It is a preset power plan to help boost your system performance in a professional setup. Even if available, enabling the[Ultimate Performance power plan may not be necessary for most users](https://www.makeuseof.com/should-you-enable-ultimate-performance-power-plan-windows-10/) .

 You can check the available and missing power plans on Windows from Control Panel:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK**
3. In the**Control Panel** , open**Hardware and Sound.**
4. Next, click on**Power Options** .
5. Expand the**Show additional plans** section.

## 1\. Change Power Mode From the Settings Panel

![change power mode windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/change-power-mode-windows-11.jpg)

[On Windows 11, you can change the power mode from the Settings app](https://www.makeuseof.com/windows-11-change-power-plan/) . You can choose between the Best power efficiency, Balanced, and Best performance power modes in the Power & battery settings.

To change power mode on Windows 11:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, scroll down and click on**Power & battery** .
3. Click the drop-down for**Power mode** and select your preferred power plan.

 If the Power Mode doesn’t show any or some power schemes, you’ll need to restore it using the powercfg command-line utility.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
## 2\. Reset the Default Power Plan Settings Using Power PowerShell

![](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reset-default-power-plans-windows-11-powershell.jpg)

 Before you try to restore the power plans, reset all the power plan settings to factory default. A reset will only fix issues that occurred due to incorrect configuration.

To reset Windows default power plans:

1. [Open PowerShell with administrator rights.](https://www.makeuseof.com/windows-11-powershell-administrator/)
2. In the PowerShell window, type the following command and press**Enter** :  
`powercfg -restoredefaultschemes`
3. The above command will reset default power schemes. Close PowerShell and check for any improvements.

## 3\. Restore the Missing Power Plan Using the Command Prompt

![restore default power plan windows 11 command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/restore-default-power-plan-windows-1-command-prompt.jpg)

 You can restore the missing default power plans on Windows using the Command Prompt. We’ll use the**powercfg** command-line feature to duplicate the existing but missing power plans.

 Follow these steps to restore the missing control power schemes. Make sure to only execute the commands for the power control schemes that are missing. Otherwise, it will create duplicate entries for the same power plan in Power Options.

1. Press the**Win** key and type**cmd** .
2. Right-click on**Command Prompt** and select**Run as administrator** .
3. In the Command Prompt window, type the following command and press Enter:  
`[High Performance]  
powercfg -duplicatescheme 8c5e7fda-e8bf-4a96-9a85-a6e23a8c635c  
[Balanced]  
powercfg -duplicatescheme 381b4222-f694-41f0-9685-ff5bb260df2e  
[Power Saver]  
powercfg -duplicatescheme a1841308-3541-4fab-bc81-f71556f20b4a  
[Ultimate Performance]  
powercfg -duplicatescheme e9a42b02-d5df-448d-aa00-03f14749eb61`
4. If successfully executed, type**exit** and press**Enter** to close Command Prompt.

 Next, open**Control Panel** and go to**Power Options** to check if the missing power plans are restored on your Windows computer.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Enable the High Performance Power Plan Using Command Prompt

![enable high performance plan windows command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-high-performance-plan-windows-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
 You can use a different**powercfg** command to enable the High Performance power plan on Windows. This is useful if your system is missing only the High Performance power scheme. Here’s how to do it.

1. [Open Command Prompt with administrator rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
2. In the Command Prompt window, type the following command and press**Enter** :  
`powercfg /s SCHEME_MIN`
3. After the command is executed, close the Command Prompt window.
4. Next, go to **Control Panel > Hardware and Sound > Power Options** . Here, you can use the**High Performance** power plan.

 If the power plans are still missing, check if Modern Standby (S0) is enabled. If yes, you’ll need to disable Modern Standby to restore the missing power plans.

## 5\. Disable Modern Standby (S0) to Restore Default Power Plans

 If you have a Modern Standby (S0) compatible system, check if this sleep state is enabled. When enabled, the default power plans may be disabled to prevent any conflict when the system is in a low-power idle state.

 As you may have guessed already, in this situation, you’ll need to[disable Modern Standby (S0) on Windows](https://www.makeuseof.com/windows-disable-modern-standby/) to restore the default power plans on Windows. After you disable Modern Standby (S0), open Power Options to use the default power plans.

 Conversely, you may encounter BSOD and other critical errors after disabling Modern Standby (S0). If yes, enable Modern Standby again to fix the issues.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Manually Create the Power Plans

 If you don’t want to use the preset power plans, you can create your own power plans on Windows. This should work irrespective of the Modern Standby state of your computer.

To create a custom Power Plan on Windows:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel.**
3. Go to**Hardware and Sound.**
4. Next, click on**Power Options** .  
![control panel create power plan windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/control-panel-create-power-plan-windows-11.jpg)
5. In the left pane, click on**Create a Power Plan.**  
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
![control panel create power plan power saver windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/control-panel-create-power-plan-power-saver-windows-11.jpg)
6. Next, select the power plan you want to restore and enter a name for the plan under the**Plan name field.**  
![control panel create power plan configure](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/control-panel-create-power-plan-configure.jpg)
7. Next, configure the settings for the new power plan.
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Click**Create** .\`

 Your new custom power plan will appear in Power Options. To remove the power plan, unselect the plan and click on**Change plan** settings. Next, click on**Delete this plan** and click**OK** .

## Restore the Missing Default Power Plans on Windows

 Power plans on your Windows laptops help you manage how your device uses power. If you don’t see the power schemes on Windows, try to reset the default power plans using PowerShell. Similarly, you can also use PowerShell to duplicate and restore the existing power plans.

 That said, not seeing the Ultimate Performance power plan in Power Options is not unusual. By default, it is only available on high-end Windows hardware and disabled to prevent battery draining. But you can still enable it using a PowerShell cmdlet. For most users, however, the balanced power plan offers a great balance between performance and battery life.


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
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-download-and-organize-facebook-urls-top-8-tools-of-the-year/"><u>[New] In 2024, Download & Organize Facebook URLs  Top 8 Tools of the Year</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-tune-and-trends-a-guide-to-sound-in-social-media-snapshots/"><u>[New] In 2024, Tune & Trends  A Guide to Sound in Social Media Snapshots</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-perfecting-iphone-photography-for-vr-spheres/"><u>[New] Perfecting iPhone Photography for VR Spheres</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-visionsonic-vsdc-review-ideal-substitutes/"><u>[New] VisionSonic VSDC Review - Ideal Substitutes</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-capture-your-discord-sessions-a-guide/"><u>[Updated] 2024 Approved  Capture Your Discord Sessions  A Guide</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-navigating-youtubes-economy-a-guide-to-video-revenue-generation/"><u>[Updated] 2024 Approved  Navigating YouTube's Economy  A Guide to Video Revenue Generation</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-best-16-youtube-intro-makers-to-bring-you-more-views/"><u>2024 Approved  Best 16 YouTube Intro Makers to Bring You More Views</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-clear-vision-through-stillness-control/"><u>2024 Approved  Clear Vision Through Stillness Control</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/advanced-gaming-rigs-equipped-for-hidden-connector-boards-supporting-6500dx-2500dc-and-asus-zenbtr-with-corsairs-latest-case-models/"><u>Advanced Gaming Rigs Equipped for Hidden Connector Boards: Supporting 6500D/X, 2500D/C and Asus ZenBTR with Corsair's Latest Case Models</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721104437171-cant-run-rtx-gaming-fix-the-issue-now-done/"><u>Can't Run RTX Gaming? Fix the Issue Now, Done</u></a></li>
<li><a href="https://location-social.techidaily.com/change-location-on-yik-yak-for-your-realme-v30t-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>Change Location on Yik Yak For your Realme V30T to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/choose-the-best-mac-livestream-software-today/"><u>Choose the Best Mac Livestream Software Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combining-macos-and-windows-apps-for-maximum-efficiency/"><u>Combining macOS and Windows Apps for Maximum Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convenient-customization-windows-11-and-11-portable-menu-addition/"><u>Convenient Customization: Windows 11 & 11 Portable Menu Addition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/creating-context-menus-to-signal-software-patches/"><u>Creating Context Menus to Signal Software Patches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diagnosing-and-resolving-non-functional-gesture-inputs/"><u>Diagnosing and Resolving Non-Functional Gesture Inputs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiency-unleashed-powertoys-batch-rename-feature/"><u>Efficiency Unleashed: PowerToys' Batch Rename Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-windows-discover-2023s-community-favorites/"><u>Elevate Windows: Discover 2023'S Community Favorites</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-stranded-message-error-on-windows-1011-xbox-app/"><u>Fixing the ‘Stranded’ Message Error on Windows 10/11 Xbox App</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-updated-software-installing-the-newest-epson-xp-310-drivers/"><u>Get Updated Software: Installing the Newest Epson XP-310 Drivers</u></a></li>
<li><a href="https://change-location.techidaily.com/guide-how-to-unbrick-a-bricked-nokia-c110-phone-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Guide How To Unbrick a Bricked Nokia C110 Phone | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-completely-uninstall-wsl-on-windows-10-and-11/"><u>How to Completely Uninstall WSL on Windows 10 & 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fake-the-location-to-get-around-the-mlb-blackouts-on-lava-blaze-curve-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Fake the Location to Get Around the MLB Blackouts on Lava Blaze Curve 5G | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-top-screen-recording-software-showdown-obs-or-fraps-battle/"><u>In 2024, Top Screen Recording Software Showdown  OBS or Fraps Battle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-your-work-and-play-with-exclusive-ms-picks/"><u>Maximize Your Work & Play with Exclusive MS Picks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-inconsistent-gestures-on-your-windows-device/"><u>Mending Inconsistent Gestures on Your Windows Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-missing-windows-logins-with-ease/"><u>Navigating Through Missing Windows Logins with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/no-commercials-just-content-a-new-era-for-win-11/"><u>No Commercials, Just Content - A New Era for Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-playnite-for-a-comprehensive-gaming-library/"><u>Optimizing Playnite for a Comprehensive Gaming Library</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-media-tool-errors-0x8007043c-and-0x90017-fixes/"><u>Overcoming Media Tool Errors: 0X8007043C and 0X90017 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reopening-hidden-nvidia-control-panel-on-w11/"><u>Reopening Hidden Nvidia Control Panel on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-password-inclusion-for-your-windows-file-system/"><u>Seamless Password Inclusion for Your Windows File System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-correct-error-code-0x80d03801-ms-store/"><u>Steps to Correct Error Code 0X80D03801 MS Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-email-management-pin-gmail-to-windows-taskbar/"><u>Streamline Email Management: Pin Gmail to Windows Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-windows-thumbnails-size-easily/"><u>Tailoring Windows Thumbnails Size Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-from-pin-based-login-on-windows-11-to-traditional-passwords/"><u>Transitioning From PIN-Based Login on Windows 11 to Traditional Passwords</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uninterrupted-powertoys-experience-with-system-switch-up/"><u>Uninterrupted PowerToys Experience with System Switch-Up</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-secrets-how-to-fix-null-input-sounds/"><u>Unlocking the Secrets: How to Fix Null Input Sounds</u></a></li>
<li><a href="https://some-skills.techidaily.com/vanguard-devices-frontline-computing-titans-for-2024/"><u>Vanguard Devices  Frontline Computing Titans for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-woes-how-to-re-enable-the-hidden-enhancement-panel/"><u>Windows 11 Woes: How to Re-Enable the Hidden Enhancement Panel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-strategies-6-fast-tips-for-overcoming-ppt-save-failures/"><u>Winning Strategies: 6 Fast Tips for Overcoming PPT Save Failures</u></a></li>
</ul></div>
