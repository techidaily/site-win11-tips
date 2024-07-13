---
title: "Windows 11 & 11 Pro Mastery: A Guide to Successfully Uninstall and Reinstall Extras"
date: 2024-07-12T17:43:54.105Z
updated: 2024-07-13T17:43:54.105Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11 & 11 Pro Mastery: A Guide to Successfully Uninstall and Reinstall Extras"
excerpt: "This Article Describes Windows 11 & 11 Pro Mastery: A Guide to Successfully Uninstall and Reinstall Extras"
keywords: Win11 Installation Tips,Win11 Extras Removal,Win11+Pro Uninstall Steps,ProWin11 Reinstall Guide,Win11 Extras Setup,Win11 Upgrade Support,Win11 Customization Techniques
thumbnail: https://thmb.techidaily.com/bd1f3164b21938808543fb77a181f9a976b01572cf9b49cfe1852edc61f82d53.jpg
---

## Windows 11 & 11 Pro Mastery: A Guide to Successfully Uninstall and Reinstall Extras

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
Get-WindowsOptionalFeature -Online ![Get Optional Feature Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/get-optional-feature-command.jpg)  
 This command will show you the**FeatureName** and**State** of every optional Windows feature that you can use. Make sure to copy the "**FeatureName** " of the feature that you want to enable on Windows.
4. To turn on a certain feature, use the following command and replace "**FEATURENAME** " with the feature's name that you copied earlier:  
Enable-WindowsOptionalFeature -Online -FeatureName FEATURENAME ![Enable Optional Feature Command In PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/optional-feature-in-powershell.jpg)
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
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-must-watch-10-unique-igtv-content-formats-for-brands/"><u>[New] In 2024, Must-Watch  10 Unique IGTV Content Formats for Brands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-pc-boost-unearthing-windows-best-eight-restart-strategies/"><u>Quick PC Boost: Unearthing Windows' Best Eight Restart Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-microsofts-apppack-and-msibundle-files-to-enhance-productivity/"><u>Integrating Microsoft's Apppack and MsiBundle Files to Enhance Productivity</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-blending-photos-and-tunes-for-free-a-guide-to-enhancing-imagery-with-music-on-computers-and-smartphones/"><u>2024 Approved Blending Photos and Tunes for Free A Guide to Enhancing Imagery with Music on Computers & Smartphones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-mouse-double-click-3-essential-tips/"><u>Mastering Mouse Double-Click: 3 Essential Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/image-editing-strategies-remove-unwanted-areas/"><u>Image Editing Strategies: Remove Unwanted Areas</u></a></li>
<li><a href="https://extra-hints.techidaily.com/quicklooker-windows-11s-speedy-photo-viewer/"><u>QuickLooker  Windows 11'S Speedy Photo Viewer</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-top-trends-in-instagram-hashtags-for-enhanced-reach-for-2024/"><u>[New] Top Trends in #Instagram Hashtags for Enhanced Reach for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-adjustments-for-enhanced-windows-bar/"><u>Step-by-Step Adjustments for Enhanced Windows Bar</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-cards-of-xiaomi-redmi-note-12-pro-5g-without-puk-codes-by-drfone-android/"><u>In 2024, How To Unlock SIM Cards Of Xiaomi Redmi Note 12 Pro 5G Without PUK Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/notepads-dark-shift-windows-11-guide/"><u>Notepad's Dark Shift: Windows 11 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/introducing-automatic-system-updates-notice-to-windows-11-ui/"><u>Introducing Automatic System Updates Notice to Windows 11 UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-failed-updates-error-0x800f0845/"><u>Steps to Fix Failed Updates - Error 0X800f0845</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-7-steps-to-mend-obs-server-link-error-in-windows/"><u>Navigating 7 Steps to Mend OBS Server Link Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-aural-anomaly-fixing-audacity-writes-on-wos/"><u>Tackling the Aural Anomaly: Fixing Audacity' Writes on WOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-your-pc-restarting-windows-11-apps/"><u>Reviving Your PC: Restarting Windows 11 Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reconnecting-to-spotify-fixing-windows-11-errors/"><u>Reconnecting to Spotify: Fixing Windows 11 Errors</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-edit-like-a-pro-best-gopro-video-editing-software-besides-gopro-studio-for-2024/"><u>Updated Edit Like a Pro Best GoPro Video Editing Software (Besides GoPro Studio) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-inactive-windows-file-alignment-service/"><u>Solutions for Inactive Windows File Alignment Service</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/no-fuss-vocal-elimination-procedures-for-audacity-professionals-for-2024/"><u>No-Fuss Vocal Elimination Procedures for Audacity Professionals for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-windows-terminal-the-unshackled-experience/"><u>Restoring Windows Terminal: The Unshackled Experience</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/premier-tiktok-editing-apps-for-windows-users/"><u>Premier TikTok Editing Apps for Windows Users</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-encapsulate-powerpoint-visuals-in-media/"><u>[New] 2024 Approved  Encapsulate PowerPoint Visuals in Media</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategic-service-management-for-optimized-windows-11/"><u>Strategic Service Management for Optimized Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-exception-handling-breaking-point-solution/"><u>Mastering Windows Exception Handling: Breaking Point Solution</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-youtube-thumbnail-secrets-boost-views-with-the-right-size-design-and-strategy/"><u>2024 Approved YouTube Thumbnail Secrets Boost Views with the Right Size, Design, and Strategy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-disrupted-windows-thx-spatial-sound/"><u>Mending Disrupted Windows THX Spatial Sound</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-steam-for-seamless-gameplay-on-windows-11-devices/"><u>Realigning Steam for Seamless Gameplay on Windows 11 Devices</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/guide-to-mirror-your-samsung-galaxy-a34-5g-to-other-android-devices-drfone-by-drfone-android/"><u>Guide to Mirror Your Samsung Galaxy A34 5G to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-auto-lock-and-screensaver-configurations/"><u>Mastering Auto-Lock & Screensaver Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-unregistered-package-error-in-win11-images/"><u>Steps to Resolve Unregistered Package Error in Win11 Images</u></a></li>
<li><a href="https://extra-tips.techidaily.com/natures-canvas-a-variety-of-downloads-to-enhance-cinematic-work/"><u>Nature’s Canvas  A Variety of Downloads to Enhance Cinematic Work</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-roots-user-permissions-back-to-basics-in-win11/"><u>Restoring Roots: User Permissions Back to Basics in Win11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/harnessing-the-full-potential-of-windows-11s-auto-hdr-feature-for-2024/"><u>Harnessing the Full Potential of Windows 11'S Auto HDR Feature for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/the-best-of-the-best-top-video-editors-for-windows-mac-ios-android-and-linux-users/"><u>The Best of the Best Top Video Editors for Windows, Mac, iOS, Android, and Linux Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-tasks-updating-window-11s-context-menu/"><u>Streamlining Tasks: Updating Window 11'S Context Menu</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-3-ways-to-fake-gps-without-root-on-apple-iphone-15-drfone-by-drfone-virtual-ios/"><u>In 2024, 3 Ways to Fake GPS Without Root On Apple iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-setup-virtualboxs-security-features-secure-boot-and-tpm/"><u>How to Setup VirtualBox's Security Features: Secure Boot & TPM</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/top-8-speech-to-text-tools-compatible-with-windows-and-macos-systems/"><u>Top 8 Speech-to-Text Tools Compatible with Windows & macOS Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snipgear-gone-wrong-nine-effective-tips-to-get-it-running-again/"><u>SnipGear Gone Wrong? Nine Effective Tips to Get It Running Again</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switching-on-or-off-windows-digital-protection-filter/"><u>Switching on or Off Windows' Digital Protection Filter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/old-hardware-new-horizinas-guiding-windows-11-22h2-installation/"><u>Old Hardware, New Horizinas: Guiding Windows 11 22H2 Installation</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-amplify-your-snapchat-experience-with-easy-voice-customization/"><u>[Updated] Amplify Your Snapchat Experience with Easy Voice Customization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-thrive-in-free-championship-football-simulator/"><u>How to Thrive in Free Championship Football Simulator</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-master-the-art-of-file-acquisition-expert-guide-for-downloading-igtv/"><u>2024 Approved  Master the Art of File Acquisition  Expert Guide for Downloading IGTV</u></a></li>
</ul></div>
