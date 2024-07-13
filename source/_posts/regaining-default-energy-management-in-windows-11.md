---
title: Regaining Default Energy Management in Windows 11
date: 2024-07-12T16:55:35.298Z
updated: 2024-07-13T16:55:35.298Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Regaining Default Energy Management in Windows 11
excerpt: This Article Describes Regaining Default Energy Management in Windows 11
keywords: Win11 Energy Save,Default Power Mode,Windows Efficient Use,Energy Saver Settings,W11 Low Power,Optimized Battery Life,Power Management Tech
thumbnail: https://thmb.techidaily.com/f1e60caa3e6b666a54baaa6c3e17dd97a81f74bfc14a37bcb509db67f36be2c1.jpg
---

## Regaining Default Energy Management in Windows 11

 Windows 11 and 10 come with preset power plans: High Performance, Power Saver, Balanced, and sometimes Ultimate Performance. You can switch between these plans to get the best performance, more battery life or a bit of both worlds. Some laptop manufacturers, like HP, have their own power plan, like HP Recommended.

 However, often after installing a Windows update, default power plans can go missing, or you may see only one power plan. This can also happen if you have made changes to your power plans recently. In any case, here are a few troubleshooting steps to help restore the missing default power plans on Windows 11 and 10 running systems.

## How to Check Which Power Plan Is Missing
![check missing power plans control panel windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-missing-power-plans-control-panel-windows-11.jpg)

 Depending on your system hardware specification, you may see three or four power plans in the Power Options panel. Balanced, Power Saver and High Performance are the most common in all Windows computers.

 However, higher-end hardware running Windows 11\\10 Pro can have the Ultimate Performance Power plan as well. It is a preset power plan to help boost your system performance in a professional setup. Even if available, enabling the [Ultimate Performance power plan may not be necessary for most users](https://www.makeuseof.com/should-you-enable-ultimate-performance-power-plan-windows-10/) .

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

## 4\. Enable the High Performance Power Plan Using Command Prompt
![enable high performance plan windows command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-high-performance-plan-windows-command-prompt.jpg)

 You can use a different**powercfg** command to enable the High Performance power plan on Windows. This is useful if your system is missing only the High Performance power scheme. Here’s how to do it.

1. [Open Command Prompt with administrator rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
2. In the Command Prompt window, type the following command and press**Enter** :  
`powercfg /s SCHEME_MIN`
3. After the command is executed, close the Command Prompt window.
4. Next, go to **Control Panel > Hardware and Sound > Power Options** . Here, you can use the**High Performance** power plan.

 If the power plans are still missing, check if Modern Standby (S0) is enabled. If yes, you’ll need to disable Modern Standby to restore the missing power plans.

## 5\. Disable Modern Standby (S0) to Restore Default Power Plans

 If you have a Modern Standby (S0) compatible system, check if this sleep state is enabled. When enabled, the default power plans may be disabled to prevent any conflict when the system is in a low-power idle state.

 As you may have guessed already, in this situation, you’ll need to [disable Modern Standby (S0) on Windows](https://www.makeuseof.com/windows-disable-modern-standby/) to restore the default power plans on Windows. After you disable Modern Standby (S0), open Power Options to use the default power plans.

 Conversely, you may encounter BSOD and other critical errors after disabling Modern Standby (S0). If yes, enable Modern Standby again to fix the issues.

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
<li><a href="https://win11-tips.techidaily.com/how-to-improve-windows-taskmanager-through-cli-integration/"><u>How to Improve Windows TaskManager Through CLI Integration</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-ways-to-find-unlocking-codes-for-oneplus-nord-n30-se-phones-by-drfone-android/"><u>In 2024, Ways To Find Unlocking Codes For OnePlus Nord N30 SE Phones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-linkage-airpods-and-windows-harmony/"><u>Master the Linkage: AirPods & Windows Harmony</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-difficulty-of-error-0x000-in-xbox-game-pass-windows-edition/"><u>Overcoming the Difficulty of Error 0X000_ in Xbox Game Pass Windows Edition</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-in-2024-how-to-rotate-avi-in-verticalportrait-orientation-windows-macandro/"><u>New In 2024, How to Rotate AVI in Vertical/Portrait Orientation Windows, Mac,Andro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/group-free-enhance-windows-11-taskbar-ease/"><u>Group-Free: Enhance Windows 11 Taskbar Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-windows-remedy-guide-eight-tactics/"><u>Essential Windows Remedy Guide - Eight Tactics</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/cropping-video-in-vlc-step-by-step/"><u>Cropping Video in VLC Step by Step</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-free-mpeg-video-concatenation-top-5-options/"><u>2024 Approved Free MPEG Video Concatenation Top 5 Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-windows-search-with-image-cleanse/"><u>Simplifying Windows Search with Image Cleanse</u></a></li>
<li><a href="https://extra-information.techidaily.com/complete-guide-to-cleaning-up-figma-canvases/"><u>Complete Guide to Cleaning Up Figma Canvases</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-your-ps4-remote-link-eliminating-random-drops-in-connection/"><u>Secure Your PS4 Remote Link: Eliminating Random Drops in Connection</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-framecraft-videocutter/"><u>[Updated] 2024 Approved  FrameCraft VideoCutter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-an-exception-breakpoint-has-been-reached-error-on-windows/"><u>How to Fix the “An Exception Breakpoint Has Been Reached” Error on Windows</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-to-balance-youtube-with-a-full-time-job/"><u>[Updated] In 2024, How to Balance YouTube with a Full-Time Job</u></a></li>
<li><a href="https://video-capture.techidaily.com/comprehensive-breakdown-obs-video-capture-capabilities/"><u>Comprehensive Breakdown  OBS Video Capture Capabilities</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-essential-skills-for-podcast-description-writers/"><u>[Updated] In 2024, Essential Skills for Podcast Description Writers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-vac-rejection-in-steam-windows-gameplay/"><u>Overcoming VAC Rejection in Steam Windows Gameplay</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-streamlined-steps-to-share-videos-on-twitter-and-tumblr/"><u>2024 Approved  Streamlined Steps to Share Videos on Twitter & Tumblr</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-silencing-the-defender-firewall-in-win11/"><u>Guide to Silencing the Defender Firewall in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-store-mishaps-cure-0x80072f30-glitches/"><u>Tackling Windows Store Mishaps: Cure 0X80072F30 Glitches</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-eyewear-challenge-google-vs-samsung-virtual-reality/"><u>The Eyewear Challenge  Google Vs. Samsung Virtual Reality</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-techniques-to-achieve-consistent-frame-rates-in-obs-studio/"><u>[Updated] Techniques to Achieve Consistent Frame Rates in OBS Studio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-removal-of-win11s-official-store/"><u>Exclusive Removal of Win11's Official Store</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-capture-mac-scenery-screen-and-microphone-feature/"><u>[New] In 2024, Capture Mac Scenery  Screen and Microphone Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/manipulating-login-retry-wait-timepost-failed-attempts/"><u>Manipulating Login Retry Wait Timepost-Failed Attempts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-rectify-bluetooth-check-pin-error-in-windows-oses/"><u>Strategies to Rectify Bluetooth Check Pin Error in Windows OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sync-success-starting-windows-and-accessing-notepad-quickly/"><u>Sync Success: Starting Windows and Accessing Notepad Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keep-older-systems-healthy-with-win10-improvements/"><u>Keep Older Systems Healthy with Win10 Improvements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailored-keybinds-for-snippet-copy-and-paste/"><u>Tailored Keybinds for Snippet Copy & Paste</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-your-performance-essential-strategies-with-windows-11/"><u>Skyrocket Your Performance: Essential Strategies with Windows 11</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/itunes-recording-proven-techniques-for-success-for-2024/"><u>ITunes Recording Proven Techniques for Success for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-iphone-image-import-something-went-wrong-error-in-windows-10-and-11/"><u>How to Fix the iPhone Image Import “Something Went Wrong” Error in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-stalled-outlook-alerts-for-new-messages/"><u>Reviving Stalled Outlook Alerts for New Messages</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-key-screenshot-utilities-1-8/"><u>2024 Approved  Key Screenshot Utilities #1-8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-to-remedy-access-denied-on-windows/"><u>Tactics to Remedy 'Access Denied' On Windows</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-ad-innovations-what-to-expect-from-facebook/"><u>2024 Approved  Ad Innovations  What to Expect From Facebook</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/from-mundane-to-memorable-transform-your-social-media-identity-with-these-tips-for-2024/"><u>From Mundane to Memorable  Transform Your Social Media Identity with These Tips for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/non-edge-processes-lurking-in-task-manager/"><u>Non-Edge Processes Lurking in Task Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-steam-disk-write-error-on-windows/"><u>How to Fix the Steam Disk Write Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-network-issues-on-windows-11-a-comprehensible-approach/"><u>Overcoming Network Issues on Windows 11 - A Comprehensible Approach</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-this-article-will-show-you-how-to-clone-yourslef-in-videos-with-filmora/"><u>New This Article Will Show You How to Clone Yourslef in Videos with Filmora</u></a></li>
<li><a href="https://some-guidance.techidaily.com/transform-into-a-hdr-photography-wizard-via-photoshop-for-2024/"><u>Transform Into a HDR Photography Wizard via Photoshop for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-what-legendaries-are-in-pokemon-platinum-on-oppo-a78-drfone-by-drfone-virtual-android/"><u>In 2024, What Legendaries Are In Pokemon Platinum On Oppo A78? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-common-powerpoint-print-errors-with-9-effective-methods/"><u>Overcoming Common PowerPoint Print Errors with 9 Effective Methods</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-fast-forwarding-fundamentals-a-novices-guide-to-snapchat/"><u>[New] Fast Forwarding Fundamentals  A Novice's Guide to Snapchat</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-fix-successful-non-operational-obs-camera/"><u>[Updated] In 2024, Fix Successful  Non-Operational OBS Camera</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-jump-to-notes-starting-windows-with-immediate-access/"><u>Quick Jump to Notes: Starting Windows with Immediate Access</u></a></li>
<li><a href="https://apple-account.techidaily.com/protecting-your-privacy-how-to-remove-apple-id-from-apple-iphone-xs-by-drfone-ios/"><u>Protecting Your Privacy How To Remove Apple ID From Apple iPhone XS</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/premier-8-voice-recognition-tools-windows-macos-and-cloud-solutions-roundup/"><u>Premier 8 Voice Recognition Tools Windows, macOS & Cloud Solutions Roundup</u></a></li>
<li><a href="https://windows11.techidaily.com/expedite-photo-corrections-ps-and-windows-strategy/"><u>Expedite Photo Corrections: PS & Windows Strategy</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/top-voice-changer-app-magic-call-and-its-alternatives/"><u>Top Voice Changer App  Magic Call and Its Alternatives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-secure-your-childrens-online-world-windows-11/"><u>Guidelines to Secure Your Children’s Online World: Windows 11</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-discord-plus-spotify-sync-tips-and-tricks/"><u>[New] In 2024, Discord + Spotify Sync  Tips and Tricks</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-speed-racers-remarkable-22-run/"><u>In 2024, Speed Racers' Remarkable '22 Run</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-collectors-delight-exclusive-black-friday-price-drop-on-essential-windows-11/"><u>Key Collectors' Delight – Exclusive Black Friday Price Drop on Essential Windows 11</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-harmonizing-visuals-and-sounds-displaying-audio-waves-and-adding-expressive-animation-in-magix-movie-edit-pro/"><u>2024 Approved Harmonizing Visuals & Sounds Displaying Audio Waves & Adding Expressive Animation in Magix Movie Edit Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-microsoft-office-activation-error/"><u>Resolving Microsoft Office Activation Error</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-navigate-through-group-sharing-options-on-messenger/"><u>2024 Approved  Navigate Through Group Sharing Options on Messenger</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slash-gpu-load-for-smarter-windows-11-wm-efficiency/"><u>Slash GPU Load for Smarter Windows 11 WM Efficiency</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-fake-gps-location-spoofer-a-good-choice-on-itel-p55-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Is Fake GPS Location Spoofer a Good Choice On Itel P55 5G? | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-ios-video-posting-made-easy-step-by-step-guide/"><u>2024 Approved  IOS Video Posting Made Easy  Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-activatedeactivate-safeguard-in-windows-10/"><u>Steps to Activate/Deactivate SafeGuard in Windows 10</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/unraveling-youtubes-monetization-policy-overhaul-for-2024/"><u>Unraveling YouTube’s Monetization Policy Overhaul for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-fingerprint-recognition-in-windows-11/"><u>Integrating Fingerprint Recognition in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-dealing-with-do-not-have-access-errors/"><u>Strategies for Dealing with 'Do Not Have Access' Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-your-windows-notes-prominent/"><u>Keeping Your Windows Notes Prominent</u></a></li>
</ul></div>
