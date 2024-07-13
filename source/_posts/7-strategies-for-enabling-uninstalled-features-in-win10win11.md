---
title: 7 Strategies for Enabling Uninstalled Features in Win10/Win11
date: 2024-07-12T17:58:32.438Z
updated: 2024-07-13T17:58:32.438Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 7 Strategies for Enabling Uninstalled Features in Win10/Win11
excerpt: This Article Describes 7 Strategies for Enabling Uninstalled Features in Win10/Win11
keywords: Win10 Feature Reinstall,Windows XPX11 Update Guide,Latest OS Compatibility Tips,Uninstalled WinFeatures Strategy,Enable Disabled WinOptions,Windows Support Uninstalls,Backup & Restore OS Functions
thumbnail: https://thmb.techidaily.com/237f968e1f2378d2ca8f58711b34f30634497fa9b29838c074677a1e86056393.jpg
---

## 7 Strategies for Enabling Uninstalled Features in Win10/Win11

 Optional features are those that you can add to get more functionality or support for certain file formats. For example, you can install different font packs or old Windows utilities like Paint and WordPad.

 If you're having trouble installing optional features, you're not alone. Sometimes optional features may fail to install due to corrupt system files, an outdated Windows version, or incorrect configuration settings.

 Fortunately, there are several ways to fix this problem and get the optional features running again. So, how can you fix the optional features not installing issue?

## 1\. Use the DISM Tool

 One of the first things you can try is using the Deployment Image Servicing and Management (DISM) tool. This tool is part of Windows, and you can use it to fix corrupt system files, including ones that could be causing problems when installing optional features.

To use the DISM tool, follow these steps:

1. Press**Win + Q** to bring up the Windows search dialogue box.
2. Type**cmd** and click**Run as administrator** to open the Command Prompt.
3. Type**dism /online /cleanup-image /restorehealth** and press**Enter** .  
![DISM Windows Utility Overview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/dism-windows-utility.jpg)

 This will start the DISM tool and begin scanning your system for any corrupt or missing files. If it finds any issues with your computer, it will automatically repair them.

 Once the process is complete, you can restart your computer and try installing the optional feature again. If DISM does not work or throws an error code, make sure to go through the [DISM not working fixes](https://www.makeuseof.com/windows-11-dism-error-2-fix/) .

## 2\. Run the System File Checker or SFC Utility

 Another tool you can use to fix issues with optional feature installation is the System File Checker (SFC) utility.

 SFC is a command-line utility on Windows, which means you can use it from the Command Prompt itself. It is a useful tool for troubleshooting and repairing problems with the system files on your computer, similar to the DISM tool.

To check your system using SFC, follow these steps:

1. Open the Command Prompt with administrative rights using any of the [ways to open CMD as an admin on Windows](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
2. Type**sfc /scannow** and press**Enter** .  
![SFC Utility In Windows Overview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-utility-in-windows.jpg)
3. Once SFC scans for errors, make sure to restart your computer.

Want to know the best part?

 The best part is that the System File Checker not only helps you fix the optional features problem but also any other Windows issues. In fact, it's one of the best [ways to repair corrupted Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) .

## 3\. Reset the Windows Update Components

 Windows Update Components include all the services, tasks, and programs that work together to make sure your Windows system is up-to-date and secure.

 Resetting the Windows Update components might help solve the issue with optional feature installation. Here's how you can reset the Windows Update components easily:

1. Open the Command Prompt utility as an administrator.
2. Type the following commands one after the other, pressing**Enter** after each one:

`net stop wuauserv  
net stop cryptSvc  
net stop bits  
net stop msiserver  
ren C:\Windows\SoftwareDistribution SoftwareDistribution.old  
ren C:\Windows\System32\catroot2 catroot2.old  
net start wuauserv  
net start cryptSvc  
net start bits  
net start msiserver`

 This command will stop the Windows Update services, rename the**SoftwareDistribution** and**catroot2** folders, and then restart the services. This can help reset the update process and fix any issues that might be causing problems with optional feature installation.

![Update Components Reset In CMD Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/update-components-reset-in-cmd.jpg)

 While the commands may look intimidating, you don't need to worry, as all the commands mentioned above will not cause any harm to your system.​​​​

## 4\. Run the Windows Update Troubleshooter

 If the Command Prompt method did not work for you, you can use the Windows Update Troubleshooter to reset update components. This tool can help identify and fix problems with the update process, including issues that might be preventing optional features from installing.

Follow these steps to run the update troubleshooter on Windows:

1. Press**Win + I** to launch the Settings app.
2. Scroll down and click**Troubleshoot > Other troubleshooters.**  
![Troubleshooter Settings In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/troubleshooter-settings-in-windows.jpg)
3. Click**Run** next to**Windows Update** to run the troubleshooter.  
![Other Troubleshooters In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/other-troubleshooters-in-windows.jpg)
4. Follow the prompts to complete the troubleshooting process.

 If you're using Windows 10, the Windows Update Troubleshooter is in**Settings > Update & Security >** **Troubleshoot > Windows Update** .

 The troubleshooter will begin scanning your system for any issues with the update process and will offer suggestions for how to fix them. So, you just need to follow the prompts, and then try [installing the optional features](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) again.

## 5\. Update Windows to the Latest Version

 If the issue with optional feature installation is related to outdated system files, you may be able to fix it by updating Windows to the latest version.

 Updating Windows can help ensure that you have the latest security patches, bug fixes, and system files, which can help resolve any issues you may be experiencing.

Here's how you can update Windows to the latest version:

1. Press**Win + I** to open the Settings app.
2. Click on**Windows** **Update > Check for updates** on Windows 11\. For Windows 10, click on **Update & Security > Windows Update > Check for Updates** .  
![Windows Update In Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-update-in-windows-11.jpg)

 That's it. Now, you can install any update that is available for your computer.

 By default, Windows automatically downloads and installs updates, but you can also check for updates manually by following the steps above.

## 6\. Restart the Windows Module Installer Service

 The Windows Module Installer service allows you to install, change, and remove Windows features and optional components. If it is not working properly, it can make it difficult to install optional features.

 Follow the below-given steps to restart the Windows Module Installer service:

1. Open Windows search and type**services** .
2. Select the best match to open the**Services** app.
3. Scroll down and find the**Windows Module Installer** service.
4. Right-click on the service and select**Restart** .  
![Windows Modules Installer Service In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-modules-installer-service.jpg)

 When you reset the module installer service, Windows tries to stop it and then start it again, which can help reset the installation process of optional features and fix any issues that might be causing problems.

 Once the service restarts, try installing the optional feature again, and it should work now.

## 7\. Restore Windows Features Using PowerShell

 If all the above methods fail to work, restoring Windows features is your last resort. So, if you are unable to use or install an optional Windows feature, you might be able to fix the problem by using PowerShell to restore a particular feature.

 Here are the steps for restoring Windows features using the PowerShell:

1. Press**Win + X** to open the Power User menu.
2. Click on**Windows PowerShell (Admin)** or**Terminal (Admin)** .
3. Type the following command and press**Enter** :  
Get-WindowsOptionalFeature -Online  
![Get Optional Feature Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/get-optional-feature-command.jpg)  
 This command will show you the**FeatureName** and**State** of every optional Windows feature that you can use. Make sure to copy the "**FeatureName** " of the feature that you want to enable on Windows.
4. To turn on a certain feature, use the following command and replace "**FEATURENAME** " with the feature's name that you copied earlier:  
Enable-WindowsOptionalFeature -Online -FeatureName FEATURENAME  
![Enable Optional Feature Command In PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/optional-feature-in-powershell.jpg)
5. Restart your computer for the changes to take effect.

 This will add the feature back to your system and should make it available for you to enable or disable in the features window.

 This method only allows you to restore a specific feature and, not all the features at once. So, you need to copy and paste the same command and edit the**FEATURENAME** every time.

 If these steps don't fix the problem, you may need to ask Microsoft or a technical support professional for more help.

## Get Back the Windows Optional Features

 Hopefully, the issue with optional features not installing on your system should be fixed now. In any case, it is important to keep your system up-to-date and to follow best practices for maintaining your computer properly to help prevent issues like this from occurring.


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
<li><a href="https://win11-tips.techidaily.com/combat-exception-interrupted-glitches-in-windows-systems/"><u>Combat 'Exception Interrupted' Glitches in Windows Systems</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-unbranded-and-unbeatable-10-free-android-video-editing-apps/"><u>2024 Approved Unbranded and Unbeatable 10 Free Android Video Editing Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-11-icon-display-ease/"><u>Enhancing Windows 11 Icon Display Ease</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/graphicgrind-studio-for-2024/"><u>GraphicGrind Studio for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-enhance-youtube-views-leveraging-outro-content-partnerships-for-2024/"><u>[New] Enhance YouTube Views  Leveraging Outro Content Partnerships for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719283991472-update-windows-11-ensure-your-system-is-up-to-date-for-any-built-in-improvements-and-fixes-regarding-display-settings/"><u>Update Windows 11: Ensure Your System Is up to Date for Any Built-In Improvements and Fixes Regarding Display Settings.</u></a></li>
<li><a href="https://howto.techidaily.com/fix-samsung-galaxy-xcover-6-pro-tactical-edition-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Samsung Galaxy XCover 6 Pro Tactical Edition Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-silent-camera-activation-in-windows-11/"><u>Bypassing Silent Camera Activation in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-the-ideal-placement-for-onedrive-on-windows-11/"><u>Crafting the Ideal Placement for OneDrive on Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-sony-xperia-10-v-drfone-by-drfone-virtual-android/"><u>Fixing Foneazy MockGo Not Working On Sony Xperia 10 V | Dr.fone</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/in-2024-tips-for-exporting-audacity-tracks-as-mp3-audio/"><u>In 2024, Tips for Exporting Audacity Tracks as MP3 Audio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-full-screen-freezes-in-sonic-on-w11/"><u>Eliminating Full-Screen Freezes in Sonic on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-a-toolbar-update-check-feature-into-windows-11plus11-interface/"><u>Integrating a Toolbar Update Check Feature Into Windows 11+11 Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-your-way-to-system32-win11/"><u>Discovering Your Way to System32 (Win11)</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/sparking-social-media-stories-facebook-fame-techniques-for-2024/"><u>Sparking Social Media Stories  Facebook Fame Techniques for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/best-nokia-c12-pro-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>Best Nokia C12 Pro Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-practices-for-cleaning-up-the-icon-cache/"><u>Best Practices for Cleaning Up the Icon Cache</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-change-your-apple-id-on-apple-iphone-xs-max-with-or-without-password-drfone-by-drfone-ios/"><u>In 2024, How To Change Your Apple ID on Apple iPhone XS Max With or Without Password | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-of-snapping-in-depth-guide-to-powertoy-window-layouts/"><u>Master the Art of Snapping: In-Depth Guide to PowerToy Window Layouts</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-explore-and-learn-about-discord-stickers/"><u>[New] Explore & Learn About Discord Stickers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/implementing-custom-window-bg-in-winterm/"><u>Implementing Custom Window Bg in WinTerm</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-cultivate-creativity-best-video-concepts-for-viewers/"><u>[Updated] Cultivate Creativity  Best Video Concepts for Viewers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-edge-always-active-on-windows-11-guide/"><u>Is Edge Always Active on Windows 11? Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-fixing-memory-detection-problems/"><u>Understanding and Fixing Memory Detection Problems</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-bridging-the-gap-with-magix-music-maker-for-beginners/"><u>[New] Bridging the Gap with Magix Music Maker for Beginners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conducting-an-intuitive-in-place-windows-11-transition/"><u>Conducting an Intuitive, In-Place Windows 11 Transition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-out-the-webp-savings-in-google-chrome-for-windows/"><u>Cutting Out the WebP Savings in Google Chrome for Windows</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-detailed-tutorial-to-merge-videos-in-vlc-media-player/"><u>New 2024 Approved Detailed Tutorial to Merge Videos in VLC Media Player</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-oneplus-ace-2-pro-mirror-screen-to-pc-drfone-by-drfone-android/"><u>In 2024, How OnePlus Ace 2 Pro Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-windows-friendly-forecast-tools/"><u>Essential Windows-Friendly Forecast Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-empty-directory-error-code-0x80070091-in-win11/"><u>Eliminating Empty Directory Error Code 0X80070091 in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fixes-for-windows-defender-shield-unresponsiveness/"><u>Essential Fixes for Windows Defender Shield Unresponsiveness</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-back-access-clearing-windowss-prior-passcode/"><u>Winning Back Access: Clearing “Windows's Prior Passcode”</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-windows-sandbox-no-hypervisor-was-found-0xc0351000-error/"><u>How to Fix the Windows Sandbox No Hypervisor Was Found 0XC0351000 Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-your-system-advanced-techniques-to-revise-the-windows-registry-in-command-prompt/"><u>Unlock Your System: Advanced Techniques to Revise the Windows Registry in Command Prompt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-should-you-care-about-runtime-brokers-on-your-system/"><u>Why Should You Care About Runtime Brokers on Your System?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719233145490-win-plus-print-problem-heres-your-quick-windows-fix-guide/"><u>Win + Print Problem? Here's Your Quick Windows Fix Guide.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-guide-5-steps-to-reset-windows-defender-status/"><u>Troubleshooting Guide: 5 Steps to Reset Windows Defender Status</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-gadget-grapple-comparing-gopros-hero5-and-garmin-virb/"><u>[New] Gadget Grapple  Comparing GoPro's Hero5 & Garmin VIRB</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/setting-up-for-success-an-instagram-business-account-blueprint/"><u>Setting Up for Success  An Instagram Business Account Blueprint</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-functional-copy-paste-in-chromeedgefirefox-windows/"><u>Fixing Non-Functional Copy-Paste in Chrome/Edge/Firefox Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-batch-script-execution-power/"><u>Elevate Your Batch Script Execution Power</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-inactive-push-notifications-for-outlook/"><u>Enabling Inactive Push Notifications for Outlook</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-amplifying-visuals-expert-guide-to-snapchat-zoom/"><u>2024 Approved  Amplifying Visuals  Expert Guide to Snapchat Zoom</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/2024-approved-live-shopping-in-china-major-changes-in-the-industry/"><u>2024 Approved Live Shopping in China Major Changes in the Industry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-stable-internet-windows-edition-guide/"><u>Troubleshooting Stable Internet: Windows Edition Guide</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-the-final-verdict-on-screen-capture-obs-vs-twitch-studio/"><u>[Updated] The Final Verdict on Screen Capture  OBS vs Twitch Studio</u></a></li>
<li><a href="https://some-techniques.techidaily.com/how-much-do-podcasters-earn-on-average-in-2024/"><u>How Much Do Podcasters Earn on Average, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instructingdarkmodeonwindowsnotepad/"><u>InstructingDarkModeOnWindowsNotepad</u></a></li>
</ul></div>
