---
title: Reclaiming Default Energy Profiles in Windows 11
date: 2024-11-22T17:44:36.415Z
updated: 2024-11-27T17:48:33.616Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reclaiming Default Energy Profiles in Windows 11
excerpt: This Article Describes Reclaiming Default Energy Profiles in Windows 11
keywords: Win11 Energy Save,Profile Reformation,Optimize Power Plan,Efficient Startup,Safe Defaults Fix,Windows Performance Boost,Profiles Adjustment
thumbnail: https://thmb.techidaily.com/4729098ff75053594bc9af7963d84132dd5d779fe074b891a4ea943b993770f6.jpg
---

## Reclaiming Default Energy Profiles in Windows 11

 Windows 11 and 10 come with preset power plans: High Performance, Power Saver, Balanced, and sometimes Ultimate Performance. You can switch between these plans to get the best performance, more battery life or a bit of both worlds. Some laptop manufacturers, like HP, have their own power plan, like HP Recommended.

 However, often after installing a Windows update, default power plans can go missing, or you may see only one power plan. This can also happen if you have made changes to your power plans recently. In any case, here are a few troubleshooting steps to help restore the missing default power plans on Windows 11 and 10 running systems.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KKFdFHaVIJg?si=x2vLw7ty3FtHX-9T&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Check Which Power Plan Is Missing

![check missing power plans control panel windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-missing-power-plans-control-panel-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eu4vwlZcMvM?si=4vEczfVU4BUUFP-t&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/PUDdKOsEN74?si=tkZf-KVinjuwmgx9&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Enable the High Performance Power Plan Using Command Prompt

![enable high performance plan windows command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-high-performance-plan-windows-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LBCobAYzzcc?si=J3eSTQ3AdyxWAjGo&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/iOVkXoUxLf4?si=QfC18T2cb5OkiaXo&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
![control panel create power plan power saver windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/control-panel-create-power-plan-power-saver-windows-11.jpg)
6. Next, select the power plan you want to restore and enter a name for the plan under the**Plan name field.**  
![control panel create power plan configure](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/control-panel-create-power-plan-configure.jpg)
7. Next, configure the settings for the new power plan.
8. Click**Create** .\`

 Your new custom power plan will appear in Power Options. To remove the power plan, unselect the plan and click on**Change plan** settings. Next, click on**Delete this plan** and click**OK** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/W5aJC8okA8s?si=L2rnYAp-gmGlLQSf&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-constructing-attention-grabbing-trailers-for-youtube/"><u>[New] 2024 Approved Constructing Attention-Grabbing Trailers for YouTube</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-revamp-your-video-exposure-on-youtube-with-these-simple-steps/"><u>[New] 2024 Approved Revamp Your Video Exposure on YouTube with These Simple Steps</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-in-2024-meme-magic-sprinkle-hilarity-with-simple-steps/"><u>[Updated] In 2024, Meme Magic Sprinkle Hilarity with Simple Steps</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-twitterscape-archive-the-ultimate-compiler-and-preserver-of-tweets-in-frames-for-2024/"><u>[Updated] Twitterscape Archive The Ultimate Compiler & Preserver of Tweets in Frames for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-hdr-lighting-insight-does-it-merit-creation/"><u>2024 Approved HDR Lighting Insight Does It Merit Creation?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decode-the-steady-freeze-top-9-fixes-for-windows-update-stall/"><u>Decode the Steady Freeze: Top 9 Fixes for Windows Update Stall</u></a></li>
<li><a href="https://some-approaches.techidaily.com/digiarty-expert-in-converting-and-managing-your-digital-media-with-dvd-and-video-tools/"><u>Digiarty - Expert in Converting and Managing Your Digital Media with DVD & Video Tools</u></a></li>
<li><a href="https://fox-helps.techidaily.com/enhance-dji-flight-aesthetics-start-with-free-trial-lutts-for-2024/"><u>Enhance DJI Flight Aesthetics – Start With Free Trial LUTTs for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-to-troubleshoot-cant-get-mail-on-windows-11-mail/"><u>Essential Tips to Troubleshoot Can't Get Mail on Windows 11 Mail</u></a></li>
<li><a href="https://driver-download.techidaily.com/how-to-easily-download-and-update-sata-controller-drivers-on-windows-systems/"><u>How to Easily DownLoad and Update SATA Controller Drivers on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-a-driver-cant-load-on-this-device-on-windows-11/"><u>How to Fix “A Driver Can’t Load on This Device” On Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterclass-in-mitigating-chrome-profiles-malfunctions/"><u>Masterclass in Mitigating Chrome Profiles Malfunctions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shifting-initial-home-page-away-from-settings-app/"><u>Shifting Initial Home Page Away From Settings App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essence-of-ai-pcs-and-their-distinct-features/"><u>The Essence of AI PCs and Their Distinct Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-realignment-of-window-widgets-separation-in-winos/"><u>Title: Realignment of Window Widgets' Separation in WinOS</u></a></li>
<li><a href="https://win-community.techidaily.com/trois-facons-simples-de-supprimer-les-fichiers-dactualisation-dans-windows-11-guide-complet/"><u>Trois Façons Simples De Supprimer Les Fichiers D'Actualisation Dans Windows 11 : Guide Complet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unclickers-manual-for-win11-users-facing-issues/"><u>Unclicker's Manual for Win11 Users Facing Issues</u></a></li>
</ul></div>

