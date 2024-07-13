---
title: Tackling Windows 11 Installation on Unsupported Hardware
date: 2024-07-12T17:08:20.996Z
updated: 2024-07-13T17:08:20.996Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling Windows 11 Installation on Unsupported Hardware
excerpt: This Article Describes Tackling Windows 11 Installation on Unsupported Hardware
keywords: Win11 Support Issues,Unsupported Hardware Compatibility,Hardware Limitations in Win11,Troubleshooting Win11 Installation,Bypassing Windows Hardware Requirements,Overcoming Win11 Installation Barriers,Fixing Unsupported Devices for Win11
thumbnail: https://thmb.techidaily.com/7f46fac9a85eca734c1f07440ac82d4e70260de3231ef2557f357bda5f1ea303.jpg
---

## Tackling Windows 11 Installation on Unsupported Hardware

 If you have installed Windows 11 on unsupported hardware, the upgrade process will be a tough task. When you try to look for an update, Windows 11 shows everything as up to date and has no option to install the 22H2 version.

 While you can use the ISO-based clean install method, the upgrade process lets you install the latest version without deleting your apps and other data. Here’s how to upgrade to Windows 11 22H2 on unsupported hardware using the Windows 11 setup file.

## How to Upgrade to Windows 11 22H2 on Unsupported Hardware

[Windows 11 runs a hardware compatibility check](https://www.makeuseof.com/check-computer-compatible-windows-11-22h2/) during the upgrade process. To perform a successful upgrade, you’ll need to work around this hardware compatibility assessment. To achieve this, we’ll replace the appraiserress.dll file in Windows 11 ISO with the appraiserress.dll from Windows 10 ISO.

 If you have Windows 11 22H2 and Windows 10 ISO available, skip to the third step below. If not, follow all the steps to download the necessary ISOs and then perform an upgrade.

 While these steps shouldn’t cause any issues, it is better to [create a backup of any important Windows 11 data](https://www.makeuseof.com/windows-11-create-complete-backup/) on your system drive just in case something goes wrong and you need to perform a clean install.

## 1\. Download the Windows 11 22H2 ISO
![iso file download windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/iso-file-download-windows-11.jpg)

 You can [legally download the Windows 11 ISO](https://www.makeuseof.com/windows-11-download-iso/) from the Microsoft server directly or using Media Creation Tool. For this guide, we’ll use Media Creation Tool to download the ISO image file.

1. Go to the [Microsoft Software Download page](https://www.microsoft.com/software-download/windows11) .
2. Click on**Download Now** under**Create Windows 11 Installation Media.**
3. Run the**mediacreationtool.exe** file and accept the license terms.
4. Review the selected language and edition. To change the language, uncheck**Use the recommended options for this PC** and select your preferred language.
5. Click**Next** .
6. Select the**ISO file** option in the**Choose which media to use** dialog.
7. Select the download location and click**Save** . Make sure the selected partition has enough space available.
8. Media Creation Tool will start downloading the ISO to your local drive. This process may take some time, depending on your Internet connection. So wait for the download to complete.
9. Once the download is complete, click**Finish** and follow the next step to download Windows 10 ISO.

## 2\. Download a Windows 10 ISO
![windows 10 download ISO preference](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-10-download-iso-preference.jpg)

 You’ll need to modify the Windows 11 ISO by replacing the appraiserress.dll with a version available in Windows 10 ISO. This DLL file is responsible for performing a hardware check during an upgrade.

To download Windows 10 ISO:

1. Go to [Windows 10 download page](https://www.microsoft.com/en-us/software-download/windows10) .
2. Click the**Download Now** button under**Create Windows 10 installation media** .
3. Run the**mediacreationtool.exe** file to open Windows 10 Setup dialog.
4. Click on**Accept** .
5. In the**What do you want to do** screen, select**Create installation media** and click**Next** .
6. Check if the language, edition, and architecture preferences are set correctly. If not, click on**Use the recommended options for this** **device** and set your preferences.
7. Next, select the**ISO file** option and click**Next** .
8. Select the download location and click**Save** .
9. The downloading process may take several minutes to complete. So wait for the process to complete and click**Finish** once done.

 Once you have both the ISO files saved, follow the next step to extract and modify the Windows 11 ISO.

## 3\. Modify the Windows 11 ISO to Bypass Hardware Check During the Upgrade

 The following steps involve extracting the Windows 10 ISO and copying the appraiserress.dll file. Next, move the copied DLL file to the Windows 11 ISO’s sources folder. Here’s how to do it.

1. Right-click on the**Windows 10 ISO** file and select**Mount** . This will create a new virtual DVD Drive and open the ISO folder.  
![mount windows 10 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/mount-windows-10-iso.jpg)
2. Open the**Sources** folder and locate the**appraiserres.dll** file. Copy the**DLL** file and move it to a different folder.  
![copy appraiserres dll windows 10 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-appraiserres-dll-windows-10-iso.jpg)
3. Next, extract the Windows 11 ISO to a different folder. You can [use WinRAR to extract](https://www.win-rar.com/start.html?&L=0) the Windows 11 ISO file.  
![extract windows 11 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/extract-windows-11-iso.jpg)
4. Open the Windows 11 ISO's extracted folder and then the**Source** folder.
5. Next, copy and paste the**appraiserres.dll** file copied from Windows 10 ISO into Windows 11 ISO's**Sources** folder.

1. Select**Replace the file in the destination** to confirm the action.  
![replace the file in the destination appraiserrs ll windows 11 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/replace-the-file-in-the-destination-appraiserrs-ll-windows-11-iso.jpg)
2. Next, disconnect your PC from the Internet. This prevents the setup from downloading updated files during installation and overwriting the modified dll file.
3. Once the Internet is disabled, open the extracted Windows 11 ISO folder and double-click on the**Setup file** . Click**Yes** if prompted by UAC.
4. In the**Windows 11 Setup** dialog, click on**Change how Setup downloads updates.**  
![windows 11 setup not right now updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-11-setup-not-right-now-updates.jpg)
5. Next, select**Note right now.** This will prevent the Windows setup from finding and installing newer updates causing the upgrade process to fail on unsupported hardware.  
![windows 11 setup choose what to install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-11-setup-choose-what-to-install.jpg)
6. In the**Choose what to keep** screen, select**Keep personal files and apps.**
7. Click**Next** and then click on**Accept** .  
![windows 11 setup ready to install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-11-setup-ready-to-install.jpg)
8. Next, click on**Install** to install Windows 11 version 22H2 while keeping your personal files and apps.
9. Leave your computer idle until the installation process is complete. After the restart, you’ll have the latest Windows 11 22H2 running on your computer.

To check your Windows specification:

![check windows specification windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/check-windows-specification-windows-11.jpg)

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, scroll down and click on**About** .
3. Under Windows specifications, you’ll see**Version 22H2** if the upgrade was successful.

## 4\. Go Back to the Previous Version
![go back windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/go-back-windows-11.jpg)

 If you run into an issue after the upgrade, you can use the**Go back** option to undo the update and restore the earlier version of Windows 11\. However, the "Go back" option is only available for seven days since the upgrade. After that, the option will be greyed out.

To go back to the previous version:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, scroll down and click on**Recovery** .
3. Click on**Go back** under**Recovery options** . Then, follow the on-screen instructions to uninstall the Windows 22H2 update.

## Installing Windows 11 22H2 on Unsupported Hardware

 It is easy to bypass the Windows 11 system hardware requirements when you want to perform a clean install. However, to perform an upgrade, you’ll need to modify the appraiserress.dll file and then run the setup.

 While the upgrade is possible for now, the lack of future automatic Windows updates makes maintaining the PC a complicated task. If upgrading to Windows 11 is not a must, you can stick to Windows 10 on older hardware, which will continue to receive support until late 2025.


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
<li><a href="https://win11-tips.techidaily.com/resolving-windows-update-issue-error-code-0x80073712/"><u>Resolving Windows Update Issue: Error Code 0X80073712</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-power-of-csgo-in-w11/"><u>Unlocking the Power of CS:GO in W11</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-streamline-your-workflow-with-the-top-5-pc-screen-grabbers/"><u>[New] Streamline Your Workflow with the Top 5 Pc Screen Grabbers</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-ultimate-playbook-iphone-downloading-for-podcast-enthusiasts/"><u>[New] The Ultimate Playbook  IPhone Downloading for Podcast Enthusiasts</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-14-plus-to-android-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 14 Plus To Android devices? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-efficiency-mastering-ms-projectenaside-from-what-ive-provided-please-give-me-5-new-book-titles-related-to-ai-in-healthcare/"><u>Unlock Efficiency: Mastering MS Project'enaside From What I've Provided, Please Give Me 5 New Book Titles Related to AI in Healthcare</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-game-launch-freezes-steps-to-mend-windows-11-steam/"><u>Troubleshooting Game Launch Freezes: Steps to Mend Windows 11 Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quickly-manipulate-text-illumination-in-windows-11/"><u>Quickly Manipulate Text Illumination in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-and-tricks-for-resolving-active-directory-printer-issues-on-win11/"><u>Tips & Tricks for Resolving Active Directory Printer Issues on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-power-peaks-controlling-wlanext-usage/"><u>Taming Power Peaks: Controlling WLANEXT Usage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-editing-tasks-with-powertoys-text-tools/"><u>Simplify Editing Tasks with PowerToys' Text Tools</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/e-conversation-starters-for-streaming/"><u>Unique Conversation Starters for Streaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategizing-user-focused-gpo-settings-for-windows-1111-oses/"><u>Strategizing User-Focused GPO Settings for Windows 11/11 OSes</u></a></li>
<li><a href="https://some-guidance.techidaily.com/tales-for-twilight-film-analysis-for-2024/"><u>Tales for Twilight  Film Analysis for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-sizing-down-software-on-windows-11/"><u>Mastering the Art of Sizing Down Software on Windows 11</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-best-5-multitasking-visual-and-audio-producers/"><u>2024 Approved  Best 5 Multitasking Visual & Audio Producers</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-drive-tiktok-engagement-a-collection-of-viral-username-concepts/"><u>[New] 2024 Approved  Drive TikTok Engagement  A Collection of Viral Username Concepts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-the-amd-installer-crash-in-windows/"><u>Quick Fixes for the AMD Installer Crash in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-rectifying-error-0x80300024-in-winxp/"><u>Steps for Rectifying Error 0X80300024 in WinXP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-11s-error-0x0000011b-on-operations/"><u>Tackling Windows 11'S Error 0X0000011B on Operations</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-quick-fix-for-clearer-focus-in-google-meet-for-2024/"><u>[Updated] Quick Fix for Clearer Focus in Google Meet for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/spotlight-on-7-irksome-windows-11-aesthetics/"><u>Spotlight on 7 Irksome Windows 11 Aesthetics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/supercharge-with-leading-winning-apps-for-windows/"><u>Supercharge with Leading Winning Apps for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/standardizing-your-windows-system-backups/"><u>Standardizing Your Windows System Backups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-identify-non-recognized-usb-devices-on-win-11/"><u>Steps to Identify Non-Recognized USB Devices on Win 11</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-the-premier-screenshot-applications-for-linux-users-for-2024/"><u>[New] The Premier Screenshot Applications for Linux Users for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-whatsapp-chat-history-from-iphone-11-pro-max-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How To Recover Whatsapp Chat History From iPhone 11 Pro Max | Stellar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-device-tracking-with-windows-live-tiles/"><u>Mastering Device Tracking with Windows Live Tiles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimalist-workstations-with-windows-os/"><u>Minimalist Workstations with Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-another-program-uses-device-auditory-fault/"><u>Tackling 'Another Program Uses Device' Auditory Fault</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-missing-msvcrt120dll-on-your-computer/"><u>Overcoming Missing Msvcrt120dll on Your Computer</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-benq-bl2711u-the-artisans-choice-for-high-end-4k-display-enthusiasts/"><u>In 2024, BenQ BL2711U - The Artisan's Choice for High-End 4K Display Enthusiasts</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-how-to-make-text-reveal-effect-easily-for-2024/"><u>Updated How to Make Text Reveal Effect Easily for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/t-insights-on-forging-youtube-sponsorship-bonds-using-famebit/"><u>Expert Insights on Forging YouTube Sponsorship Bonds Using FameBit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resuscitating-silent-windows-headset-mic/"><u>Resuscitating Silent Windows Headset Mic</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-sudo-tool-is-coming-to-windows-how-and-why-to-use-it/"><u>The Sudo Tool Is Coming to Windows: How and Why to Use It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/superior-vm-choices-to-upgrade-windows-11-performance/"><u>Superior VM Choices To Upgrade Windows 11 Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-successful-java-setup-in-windows/"><u>Strategies for Successful Java Setup in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silence-windows-aggressive-contrast-mode/"><u>Silence Windows' Aggressive Contrast Mode</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-display-apple-iphone-13-mini-screen-on-pc-easily-drfone-by-drfone-ios/"><u>In 2024, How to Display Apple iPhone 13 mini Screen on PC Easily? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-gaming-e84-fix-for-steam-windows/"><u>Streamline Your Gaming: E84 Fix for Steam Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-new-age-of-computing-from-w10s-familiarity-to-w11s-novelty/"><u>The New Age of Computing: From W10's Familiarity to W11's Novelty</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-missing-optional-windows-extras-in-7-steps/"><u>Troubleshooting Missing Optional Windows Extras in 7 Steps</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-from-playtime-to-profits-ryan-kajis-youtube-cash-crusade/"><u>[Updated] 2024 Approved  From Playtime to Profits  Ryan Kaji's YouTube Cash Crusade</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/easy-guide-to-vivo-y78plus-t1-edition-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Vivo Y78+ (T1) Edition FRP Bypass With Best Methods</u></a></li>
</ul></div>
