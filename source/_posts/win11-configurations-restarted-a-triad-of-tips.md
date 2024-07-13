---
title: "Win11 Configurations Restarted: A Triad of Tips"
date: 2024-07-12T17:16:48.497Z
updated: 2024-07-13T17:16:48.497Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Win11 Configurations Restarted: A Triad of Tips"
excerpt: "This Article Describes Win11 Configurations Restarted: A Triad of Tips"
keywords: Win11 Setup Guide,Windows 11 Reboot Advice,Resetting Win11 Settings,Win11 Config Tips,Safe Win11 Restart,Win11 Optimization Steps,Reconfigure Win11 Faster
thumbnail: https://thmb.techidaily.com/a691a544cb7cde4aeceab56e4cf68f393a99f1feb2da71ac3ca94b7300f4d4b3.jpg
---

## Win11 Configurations Restarted: A Triad of Tips

 The Settings app in Windows 11 makes it simple for you to manage various settings and preferences on your computer. Whether you want to customize your computer's theme, manage network connections or check for system updates, the Windows Settings app is a central location for all your computer management needs.

 If the Windows 11 Settings app stops working, or if you want to restore it to its default settings, you can always reset it. You can reset the Windows Settings app using the search menu, Command Prompt or PowerShell. Let's go over all three methods in detail.

## 1\. How to Reset the Windows 11 Settings App Using the Search Menu

 The quickest way to reset the Windows 11 Settings app is through the search menu. So, let's start with that.

To reset the Windows 11 Settings app with the search menu:

1. Click the magnifying icon on the taskbar or use the**Win + S** keyboard shortcut to access the search menu.
2. Type**Settings** in the search box.
3. Select the**App settings** option from the right pane.
4. Scroll down to the Reset section and click the**Reset** button.
5. Select**Reset** again to confirm.  
![Reset Settings App in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reset-settings-app-in-windows-11.jpg)

 After completing the above steps, you can use one of the [many ways to access the Windows Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) and configure it again.

## 2\. How to Reset the Windows 11 Settings App via PowerShell

 If you prefer to interact with your computer through a command-line interface, you can also use PowerShell to reset the Windows Settings app. Don’t worry, the process isn’t as intimidating as it might sound.

 Use these steps to reset the Windows 11 Settings app using PowerShell.

1. Click the**search icon** on the taskbar to open the search menu.
2. Type**Windows PowerShell** in the search box.
3. Select**Run as administrator** from the right side.
4. When the User Account Control (UAC) prompt appears, select**Yes** to continue.
5. In the console, type the following command and press**Enter** to reset the Settings app.  
`Get-AppxPackage *Windows.ImmersiveControlPanel* | Reset-AppxPackage`  
![Reset Settings App Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reset-settings-app-using-powershell.jpg)

 If you're a PowerShell enthusiast, why not take the time to learn these [useful Windows PowerShell commands](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) to improve efficiency?

## 3\. How to Reset the Windows 11 Settings App Using Command Prompt

 Another way to reset the Windows 11 Settings app is via Command Prompt. Similar to the method above, resetting the Settings app using Command Prompt only requires you to run a single command.

 To reset the Windows 11 Settings app using Command Prompt, use these steps:

1. Press**Win + X** or right-click the**start icon** to open the Power User menu and select**Run** from the list.
2. Type**cmd** in the text box and then press**Ctrl + Shift + Enter** on your keyboard to [open Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/#how-to-run-command-prompt-as-an-administrator-through-the-windows-search-tool) .
3. Select**Yes** when the User Account Control (UAC) prompt shows up.
4. In the console, paste the following command and hit**Enter** :  
`PowerShell -ExecutionPolicy Unrestricted -Command "& {$manifest = (Get-AppxPackage *immersivecontrolpanel*).InstallLocation + '\AppxManifest.xml' ; Add-AppxPackage -DisableDevelopmentMode -Register $manifest}"`

![Reset Settings App Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reset-settings-app-using-command-prompt.jpg)

 Once you run the above command, Windows will reset the Settings app on your computer.

 Do you find Command Prompt to be too complicated or boring to use? Here are some of [the best Command Prompt alternatives for Windows](https://www.makeuseof.com/best-command-prompt-alternatives-for-windows/) worth trying.

## Resetting the Windows 11 Settings App

 Regardless of the method you use, resetting Windows 11 Settings app shouldn’t take more than a couple of minutes of your time. After that, you can start configuring your computer settings from scratch.

 If, however, resetting the Settings app does not solve your problem, you can try creating a new user account. Alternatively, you can consider factory resetting your Windows 11 computer and starting over.


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
<li><a href="https://video-creation-software.techidaily.com/updated-unbiased-review-top-aiff-converters-for-seamless-audio-conversion-for-2024/"><u>Updated Unbiased Review Top AIFF Converters for Seamless Audio Conversion for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-network-locked-sim-card-inserted-on-your-oneplus-phone-unlock-it-now-by-drfone-android/"><u>In 2024, Network Locked SIM Card Inserted On Your OnePlus Phone? Unlock It Now</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-anonymous-no-more-bringing-back-fb-sessions/"><u>2024 Approved  Anonymous No More  Bringing Back Fb Sessions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-soon-expiring-license-messages-from-your-pc/"><u>Eliminating “Soon Expiring License” Messages From Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-shifting-your-powertoys-profile-to-another-pc/"><u>Efficiently Shifting Your PowerToys Profile to Another PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-pc-tune-ups-wins-prime-performance-hacks/"><u>Essential PC Tune-Ups: Win's Prime Performance Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assess-power-demands-in-windows-based-personal-computers/"><u>Assess Power Demands in Windows-Based Personal Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-10-woes-cure-non-responsive-f-keys-now/"><u>Windows 10 Woes? Cure Non-Responsive F-Keys Now</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-mastering-360-fb-live-broadcasts/"><u>[New] 2024 Approved  Mastering 360 FB Live Broadcasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-resolving-rdp-errors-in-windows-11/"><u>Essential Tips for Resolving RDP Errors in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-windows-system-secrets-generating-and-evaluating-reports/"><u>Unlock Windows System Secrets: Generating & Evaluating Reports</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-windows-schedule-breakdown-quickly/"><u>Troubleshoot Windows Schedule Breakdown Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-remedies-to-immediate-addition-problems-for-your-onedrive-drive/"><u>Efficient Remedies to Immediate Addition Problems for Your OneDrive Drive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/artificial-insight-windows-software-reinvented/"><u>Artificial Insight: Windows Software Reinvented</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dism-strategies-reviving-windows-11-images/"><u>DISM Strategies: Reviving Windows 11 Images</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-realme-11x-5g-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Realme 11X 5G Bricked Devices | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-unwelcome-closure-messages-from-your-roblox-games/"><u>Avoiding Unwelcome Closure Messages From Your Roblox Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-error-0x80070522-unlocking-client-privileges-in-windows-1110/"><u>Troubleshooting Error 0X80070522: Unlocking Client Privileges in Windows 11/10</u></a></li>
<li><a href="https://howto.techidaily.com/6-fixes-to-unfortunately-whatsapp-has-stopped-error-popups-on-xiaomi-redmi-k70-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Fixes to Unfortunately WhatsApp has stopped Error Popups On Xiaomi Redmi K70 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-windows-environment-top-6-innovative-android-apps/"><u>Transform Your Windows Environment: Top 6 Innovative Android Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-the-classics-with-clear-cut-winning-strategies-for-high-definition-hd/"><u>Ace the Classics with Clear-Cut Winning Strategies for High-Definition HD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fixes-to-stop-windows-10-blue-screens/"><u>Essential Fixes to Stop Windows 10 Blue Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-windows-security-account-manager-glitches/"><u>Correcting Windows Security Account Manager Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-6-excellent-tools-for-controlling-windows-screen-luminosity/"><u>Unveiling the 6 Excellent Tools for Controlling Windows Screen Luminosity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-the-antiquity-embellishing-old-games-with-retroarch-awards/"><u>Upgrade the Antiquity - Embellishing Old Games With Retroarch Awards</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-gits-full-potential-with-github-desktop-on-windows/"><u>Unlocking Git's Full Potential with GitHub Desktop on Windows</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-poco-c55-phone-without-pin-by-drfone-android/"><u>How to Unlock Poco C55 Phone without PIN</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-unauthorized-save-errors-in-microsoft-os/"><u>Troubleshooting Unauthorized Save Errors in Microsoft OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/directing-local-groups-policy-a-focused-approach-for-users-in-windows-11-and-11/"><u>Directing Local Groups Policy: A Focused Approach for Users in Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-potential-four-ways-to-open-disk-management-in-win11/"><u>Unleashing Potential: Four Ways to Open Disk Management in Win11</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-the-two-factor-authentication-on-apple-iphone-15-pro-max-by-drfone-ios/"><u>In 2024, How To Remove the Two Factor Authentication On Apple iPhone 15 Pro Max</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-optimal-metaverse-displays-the-ultimate-8-picks/"><u>2024 Approved  Optimal Metaverse Displays  The Ultimate 8 Picks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-seamless-multilingual-input-adjusting-keyboard-layout-in-windows-11/"><u>Achieve Seamless Multilingual Input: Adjusting Keyboard Layout in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-are-windows-cab-files-and-how-do-you-install-them/"><u>What Are Windows CAB Files and How Do You Install Them?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-visibility-of-results-with-windows-11-search-fixes/"><u>Enhancing Visibility of Results with Windows 11 Search Fixes</u></a></li>
<li><a href="https://extra-information.techidaily.com/conquering-the-complexities-of-360-video-post-production-in-premiere-for-2024/"><u>Conquering the Complexities of 360° Video Post-Production in Premiere for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unseen-sd-card-on-pc-restore-its-visibility-in-explorer/"><u>Unseen SD Card on PC? Restore Its Visibility in Explorer</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-how-to-make-a-ken-burns-effect-in-camtasia-9/"><u>[Updated] 2024 Approved  How to Make a Ken Burns Effect in Camtasia 9?</u></a></li>
<li><a href="https://extra-skills.techidaily.com/professional-drone-use-in-visual-storytelling-for-2024/"><u>Professional Drone Use in Visual Storytelling for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-error-30005-struggles-with-new-file-creation/"><u>Fixing Windows Error 30005 - Struggles with New File Creation</u></a></li>
<li><a href="https://android-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-motorola-moto-g13-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Motorola Moto G13</u></a></li>
</ul></div>
