---
title: "DIMS Masterclass: Restoring and Repairing Win11 Images"
date: 2024-07-12T17:20:11.835Z
updated: 2024-07-13T17:20:11.835Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes DIMS Masterclass: Restoring and Repairing Win11 Images"
excerpt: "This Article Describes DIMS Masterclass: Restoring and Repairing Win11 Images"
keywords: Win11 Image Recovery,Win11 Image Repair,Win11 Diagnostic Tools,Win11 Image Masterclass,Win11 Restore Tutorial,Win11 Images Fixed Guide,Win11 Image Correction
thumbnail: https://thmb.techidaily.com/9f799a63c5ced001089eec847a965c77100b85a292d3d2c56946946b1d875c1f.jpg
---

## DIMS Masterclass: Restoring and Repairing Win11 Images

 Windows 11, like its predecessor, features the built-in Deployment Image Servicing and Management (DISM), a command-line utility to troubleshoot critical system errors. The DISM commands can help you fix Blue Screen of Death (BSOD) errors, a slow computer due to broken system files, and even repair the Windows Recovery Environment.

 In this article, we’ll show you how you can use the DISM and System File Checker utility to repair your damaged Windows 11 image and installation.

## How to Use the DISM Command in Windows 11

 The DISM command-line utility is a multi-purpose tool. It allows the system administrator to prepare and service Windows images. In addition, you can use the DISM tool in combination with the System File Checker utility to recover your Windows computer from critical failure.

 While DISM supports multiple specified commands, to repair your Windows computer, you only need to know the DISM CheckHealth, DISM ScanHealth, and DISM RestoreHealth commands.

 If you can boot into Windows 11, you can run the DISM command from an elevated PowerShell console or Command Prompt. If not, you’ll need to [boot into the Windows Recovery Environment](boot%20into%20the%20Windows%20Recovery%20Environment) and launch Command Prompt from **Advanced Options** to run DISM.

## Check Your System Health Using the DISM CheckHealth Command

 You can check for any file corruption using the DISM CheckHealth command. It is a diagnostic tool used to detect system image corruption and report the same. However, it doesn’t perform any repair.

 To run the CheckHealth command:

1. Press the **Win** key and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator**.  
![DISM scan health powershell command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-clean-health-powershell-command.jpg)
3. In the Command Prompt window, type the following command and press **Enter**:  
`DISM /Online /Cleanup-Image /CheckHealth`
4. In the above command, the **/Online** parameter specifies the scan must be performed on the currently running operating system. The **/Cleanup-Image** parameter specifies the operation is related to Windows image repair.
5. When executed, the command will show the report as “**The component stored has been corrupted**” or “**No component store corrupted detected.**” depending on whether a component store corruption is found.  
![DISM powershell CheckHealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-powershell-checkhealth-command.jpg)
6. If you use PowerShell, use the following command instead:  
`Repair-WindowsImage -Online -CheckHealth`
7. The PowerShell command will report your image status to indicate whether it is **Healthy**, **Repairable** or **Non-repairable**. A healthy image doesn’t need any further action, and you can proceed to run the SFC tool.

 If the image is repairable, you can use the RestoreHealth command to use Windows Update to fix any corruption. However, for a non-repairable image, you may need to perform a clean install to fix your computer.

## Perform an Advanced System Image Scan with the ScanHealth Command
![DISM scan health command PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-scan-health-command-powershell.jpg)

 You can use the DISM ScanHealth command to perform an advanced scan of your Windows 11 system image. This will check your system for component store corruption and save the report to a log file.

 To run the DISM ScanHealth command:

1. Open **PowerShell** as administrator.
2. Type the following command and press Enter:  
`DISM /Online /Cleanup-Image /ScanHealth`
3. This process may take some time to complete. Once done, it will report any issues with the component store.
4. If an issue is detected, run the DISM RestoreHealth command to repair your Windows image.

## Run the DISM RestoreHealth Command to Repair the Windows System Image
![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dism-scan-health-restore-health-command-prompt.jpg)

 The DISM RestoreHealth command uses Windows Update to provide the necessary files to fix file corruption and repair the Windows 11 system image. However, you must be connected to the internet so that the DISM tool can download and restore the files needed to perform a repair.

 To run the DISM RestoreHealth command:

1. Open **Windows PowerShell** as administrator.
2. Next, type the following command and press **Enter**:  
`DISM.exe /Online /Cleanup-image /RestoreHealth`
3. The DISM utility will perform a scan and start repairing the Windows system image. This process may take some time to complete. So, wait till the progress bar reaches 100%.

## Repair System Image Using an Alternate Repair Source

 The DISM RestoreHealth command may not work if your computer is not connected to the internet or if the Windows Update component is corrupt. In this situation, you can use a Windows installation media or a mounted Windows ISO as a local source to repair the system image.

 First, [create a bootable Windows 11 USB drive](https://www.makeuseof.com/windows-11-create-bootable-usb-drive/). Once you have the installation media ready, connect it to your computer and proceed with the below steps.

 To repair your Windows 11 system image using DISM and a local repair source:

1. Press **Win + E** to open **File Explorer**.
2. Open your installation media drive, open the **Sources** folder and make sure the **install.wim** file exists. Also, note the driver letter assigned to your installation media. In this instance, our installation media is assigned the drive letter **(I:)**.  
![install wim file in Windows 11 installation media](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/install-wim-file-in-windows-11-installation-media.jpg)
3. Next, type the following command to run the **DISM RestoreHealth** command with the installation media as a repair source:  
`DISM /Online /Cleanup-Image /RestoreHealth /Source:I\Sources\install.wim /LimitAccess`
4. In the above command, replace the placeholder **:I** with your installation media drive letter. Also, the **LimitAccess** command is an optional parameter that restricts DISM access to the specified source and prevents it from using **Windows Update** as a repair source.
5. Once the process is complete, you can close Command Prompt and run the **System File Checker** utility to complete the repair process.

## Repair Your Windows Installation Using the System File Checker (SFC) Utility
![run system file checker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/run-system-file-checker.png)

 Once you have successfully repaired your Windows 11 system image using the DISM RestoreHealth command, run the System File Checker (SFC) utility. It will scan your Windows installation for system file corruption and fix them automatically.

 In almost all instances, you must run the System File Checker utility after using the DISM image repair command to complete the repair process. Here’s how to do it:

1. Press **Win + X** to open the **WindowsX** menu.
2. Click **Terminal (Admin)** to launch the **Windows** Terminal app as administrator.
3. In the **Terminal** window, type the following command to run the **System File Checker** utility:  
`sfc /scannow`
4. When you run the above command, the System File Checker utility will start verifying the integrity of system files to detect corruption. If detected, it’ll automatically try to repair by replacing the files with a cached copy located at **%WinDir%\\System32\\dllcache.**

 The SFC process may take some time to complete and often may feel stuck at some stage. If you see no progress for a long time, press the **Enter** key a few times on your keyboard to refresh the Command Prompt window to view real-time progress.

 After the process is complete, restart your computer and check for any improvements. If the issue persists, run the **sfc /scannow** command again to see if that helps fix the problem.

## Repair and Recover Your Windows System Image Using DISM and SFC

 DISM makes it easy to repair a corrupt Windows image. It works both online using Windows Update and offline with a WIM file. The steps to use DISM may look complicated at first glance; however, it only takes two commands and an elevated Command Prompt to repair your Windows 11 image and installation.

 In this article, we’ll show you how you can use the DISM and System File Checker utility to repair your damaged Windows 11 image and installation.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/steps-to-enable-digital-supervision-in-windows-11-pcs/"><u>Steps to Enable Digital Supervision in Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-windows-exploration-without-the-use-of-ls/"><u>Streamlined Windows Exploration Without the Use of LS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-the-onedrive-symbol-from-windows-11-filesystem/"><u>Eradicating the OneDrive Symbol From Windows 11 Filesystem</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/eliminate-unwanted-audio-with-top-microphone-suppression-software/"><u>Eliminate Unwanted Audio with Top Microphone Suppression Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-operation-issues-on-modern-windows-pcs/"><u>Resolving Operation Issues on Modern Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-code-0x0000004e-on-windows-os/"><u>Eliminating Code 0X0000004E on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/successfully-overcome-windows-error-0x80070003-a-step-by-step-guide/"><u>Successfully Overcome Windows Error 0X80070003 - A Step-by-Step Guide</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-oppo-reno-10-proplus-5g-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Oppo Reno 10 Pro+ 5G to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-advanced-hue-adjustment-strategies-for-professionals/"><u>[Updated] Advanced Hue Adjustment Strategies for Professionals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steering-clear-of-stuck-warcraft-patches/"><u>Steering Clear of Stuck Warcraft Patches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-setting-up-window-sandbox/"><u>The Ultimate Guide to Setting up Window Sandbox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/past-keys-to-future-launches-utilizing-windows-7-for-windows-11-bootup/"><u>Past Keys to Future Launches: Utilizing Windows 7 for Windows 11 Bootup</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-how-to-use-whiteboard-in-zoom-meeting/"><u>[New] In 2024, How to Use Whiteboard in Zoom Meeting</u></a></li>
<li><a href="https://screen-recording.techidaily.com/1715860767791-updated-capture-every-detail-on-mac-free/"><u>[Updated] Capture Every Detail on Mac - Free!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-and-o365-sync-issues-a-quick-guide-to-fixing-errors/"><u>Win 11 and O365 Sync Issues: A Quick Guide to Fixing Errors</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-android-gaming-delight-with-kinemaster-app-explored/"><u>2024 Approved  Android Gaming Delight with KineMaster App Explored</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-mspm-setup-obstacles-in-windows-vista/"><u>Overcoming MSPM Setup Obstacles in Windows Vista</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-achieve-more-views-tailoring-and-scaling-youtube-images/"><u>[Updated] Achieve More Views  Tailoring and Scaling YouTube Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-smooth-asana-operations-on-pcs/"><u>Restoring Smooth Asana Operations on PCs</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-oppo-reno-10-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Oppo Reno 10 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-celebrating-the-hottest-instagram-after-effects-plugins/"><u>[New] In 2024, Celebrating the Hottest Instagram After Effects Plugins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719334227097-windows-transcends-platforms-iphoneipadmacpc-compatibility-announced/"><u>Windows Transcends Platforms: IPhone/iPad/Mac/PC Compatibility Announced!</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-inverted-intrigue-mastering-the-art-of-turning-photos-for-instagram-glory/"><u>[Updated] Inverted Intrigue  Mastering the Art of Turning Photos for Instagram Glory</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-edit-and-send-fake-location-on-telegram-for-your-vivo-y78-5g-in-3-ways-drfone-by-drfone-virtual-android/"><u>In 2024, Edit and Send Fake Location on Telegram For your Vivo Y78 5G in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-windows-crashes-due-to-video-drivers/"><u>Remedying Windows Crashes Due to Video Drivers</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-astral-expressions-top-30-bios-to-boost-your-signs-charm/"><u>[Updated] Astral Expressions  Top 30 Bios to Boost Your Sign's Charm</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-updater-roadblock-0x80073712/"><u>Resolving Updater Roadblock: 0X80073712</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-immersive-experience-creating-rich-skype-recordings-using-obs/"><u>In 2024, Immersive Experience  Creating Rich Skype Recordings Using OBS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-evolves-spotlight-on-new-updates-capabilities/"><u>Windows 11 Evolves: Spotlight on New Updates' Capabilities</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-maximizing-your-library-a-detailed-walkthrough-of-downloading-music-from-spotify/"><u>New 2024 Approved Maximizing Your Library A Detailed Walkthrough of Downloading Music From Spotify</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-various-methods-to-transfer-pictures-from-apple-iphone-15-pro-to-pc-drfone-by-drfone-transfer-from-ios/"><u>In 2024, Various Methods to Transfer Pictures from Apple iPhone 15 Pro to PC | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-cure-all-solutions-for-windows-camera-glitches/"><u>Quick Cure-All Solutions for Windows Camera Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-non-definable-error-in-windows-environment/"><u>Tackling 'Non-Definable' Error in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-recollection-of-previous-windows-password/"><u>Mending “Recollection of Previous Window's Password”</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-make-an-impact-top-10-free-and-paid-intro-maker-websites-reviewed/"><u>Updated 2024 Approved Make an Impact Top 10 Free and Paid Intro Maker Websites Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-write-file-access-issue-on-windows-1011/"><u>Troubleshooting Write File Access Issue on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winrars-hash-harmony-six-ways-to-ensure-correct-sums/"><u>WinRAR's Hash Harmony: Six Ways to Ensure Correct Sums</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/iphone-and-android-the-five-best-non-youtube-apps-for-2024/"><u>IPhone & Android  The Five Best Non-Youtube Apps for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-remedy-fixing-file-not-found-issues-in-windows-1110/"><u>Quick Remedy: Fixing 'File Not Found' Issues in Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/where-windows-hides-shot-files/"><u>Where Windows Hides Shot Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-microsoft-store-fault-code-0x80072efd/"><u>Eradicating Microsoft Store Fault Code 0X80072EFD</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-is-greyed-out-on-iphone-se-how-to-bypass-by-drfone-ios/"><u>Apple ID is Greyed Out On iPhone SE How to Bypass?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-insiders-guide-to-customizing-the-desktop-menu/"><u>The Insider's Guide to Customizing the Desktop Menu</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-discover-the-art-of-curating-music-on-youtube-with-our-steps-for-2024/"><u>[New] Discover the Art of Curating Music on YouTube with Our Steps for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-2024-approved-seamless-transitions-shooting-smooth-time-lapse-with-hero5/"><u>[New] 2024 Approved  Seamless Transitions  Shooting Smooth Time-Lapse with Hero5</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11-potential-steps-for-successful-optional-components-integration/"><u>Unlocking Windows 11 Potential: Steps for Successful Optional Components Integration</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-innovative-ideas-to-make-your-youtube-shorts-exceptional/"><u>[New] Innovative Ideas to Make Your YouTube Shorts Exceptional</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-change-lock-screen-wallpaper-on-motorola-edge-40-neo-by-drfone-android/"><u>How to Change Lock Screen Wallpaper on Motorola Edge 40 Neo</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-windows-strategy-for-sound-graph-segregation/"><u>Understanding Windows' Strategy for Sound Graph Segregation</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-prime-tools-elevating-digital-collaboration/"><u>[New] 2024 Approved  Prime Tools Elevating Digital Collaboration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/supercharge-windows-11s-notepad-with-copilot/"><u>Supercharge Windows 11’S Notepad With Copilot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-failure-code-0x0001-on-nvidia-software/"><u>Addressing Failure Code 0X0001 on Nvidia Software</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/reasons-why-pokemon-gps-does-not-work-on-realme-c33-2023-drfone-by-drfone-virtual-android/"><u>Reasons why Pokémon GPS does not Work On Realme C33 2023? | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-content-creation-and-currency-maximizing-youtube-wealth/"><u>2024 Approved  Content Creation & Currency  Maximizing YouTube Wealth</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-disabled-lock-screen-timeout-windows/"><u>Addressing Disabled Lock Screen Timeout Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-prevent-date-changes-on-windows-pcs/"><u>Steps to Prevent Date Changes on Windows PCs</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-best-5-tiktok-voice-generators-you-should-try/"><u>Updated Best 5 TikTok Voice Generators You Should Try</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/best-picks-the-most-acclaimed-10-online-vimeo-video-harvesters-for-2024/"><u>Best Picks  The Most Acclaimed 10 Online Vimeo Video Harvesters for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-where-to-find-the-best-budgeted-gopro-purchases-for-2024/"><u>[New] Where to Find the Best Budgeted GoPro Purchases for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/crafting-characters-the-art-of-3d-text-design/"><u>Crafting Characters  The Art of 3D Text Design</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-essentials-for-becoming-a-top-notch-interviewer/"><u>[New] The Essentials for Becoming a Top-Notch Interviewer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-installation-of-windows-chatgpt/"><u>Step-by-Step Installation of Windows ChatGPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crucial-cross-platform-tools-windows-meets-android/"><u>Crucial Cross-Platform Tools: Windows Meets Android</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-does-the-stardust-trade-cost-in-pokemon-go-on-lava-blaze-curve-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How does the stardust trade cost In pokemon go On Lava Blaze Curve 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-restoring-accessibility-of-displays-in-nvidia-software/"><u>Tips for Restoring Accessibility of Displays in Nvidia Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-windows-crash-focus-on-0x800f0831/"><u>Eliminate Windows Crash: Focus on 0X800f0831</u></a></li>
</ul></div>
