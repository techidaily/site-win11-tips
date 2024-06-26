---
title: "Navigating New Horizons: Upgrading Old PCs to 22H2"
date: 2024-06-25T16:16:51.407Z
updated: 2024-06-26T16:16:51.407Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Navigating New Horizons: Upgrading Old PCs to 22H2"
excerpt: "This Article Describes Navigating New Horizons: Upgrading Old PCs to 22H2"
keywords: Horizon PC Upgrade,Old PC Revamp,New Era Computers,H2022 PC Update,Tech Transition Guide,Modern PCs Boost,Horizon System Overhaul
thumbnail: https://thmb.techidaily.com/132555d330df6c205c8e32dca26d7905a91b5054d60d992a4b9ddb9496678dda.png
---

## Navigating New Horizons: Upgrading Old PCs to 22H2

 If you have installed Windows 11 on unsupported hardware, the upgrade process will be a tough task. When you try to look for an update, Windows 11 shows everything as up to date and has no option to install the 22H2 version.

 While you can use the ISO-based clean install method, the upgrade process lets you install the latest version without deleting your apps and other data. Here’s how to upgrade to Windows 11 22H2 on unsupported hardware using the Windows 11 setup file.

## How to Upgrade to Windows 11 22H2 on Unsupported Hardware

[Windows 11 runs a hardware compatibility check](https://www.makeuseof.com/check-computer-compatible-windows-11-22h2/) during the upgrade process. To perform a successful upgrade, you’ll need to work around this hardware compatibility assessment. To achieve this, we’ll replace the appraiserress.dll file in Windows 11 ISO with the appraiserress.dll from Windows 10 ISO.

 If you have Windows 11 22H2 and Windows 10 ISO available, skip to the third step below. If not, follow all the steps to download the necessary ISOs and then perform an upgrade.

 While these steps shouldn’t cause any issues, it is better to [create a backup of any important Windows 11 data](https://www.makeuseof.com/windows-11-create-complete-backup/) on your system drive just in case something goes wrong and you need to perform a clean install.

## 1\. Download the Windows 11 22H2 ISO ![iso file download windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/iso-file-download-windows-11.jpg)

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

## 2\. Download a Windows 10 ISO ![windows 10 download ISO preference](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-10-download-iso-preference.jpg)

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

## 4\. Go Back to the Previous Version ![go back windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/go-back-windows-11.jpg)

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
<li><a href="https://win11-tips.techidaily.com/file-system-exploration-in-win11-6-keyways-to-duplicating-file-and-folder-paths/"><u>File System Exploration in Win11: 6 Keyways to Duplicating File and Folder Paths</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-discrepancies-in-computers-processor-utilization/"><u>Resolving Discrepancies in Computers' Processor Utilization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-launch-and-configure-win-11-sandbox/"><u>How to Launch and Configure Win 11 Sandbox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-msresourceappnametext-glitch-win11-style/"><u>Fixing 'MsResource:AppName/Text Glitch', Win11 Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stop-roblox-needs-quitting-on-windows-without-hesitation/"><u>How to Stop Roblox Needs Quitting on Windows Without Hesitation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidance-on-resolving-windows-software-initiation-flaw-error/"><u>Guidance on Resolving Windows Software Initiation Flaw (Error)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-windows-store-error-code-0x80073cf3/"><u>Steps to Resolve Windows Store Error Code 0X80073CF3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-pc-sound-with-new-windows-audio-drivers/"><u>Streamline Your PC Sound with New Windows Audio Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-path-to-seamless-update-in-win11/"><u>Clearing Path to Seamless Update in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-eliminate-directdraw-faults-on-windows-oses/"><u>Steps to Eliminate DirectDraw Faults on Windows OSes</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-excellence-unleashed-the-pinnacle-fps-selections-for-2024/"><u>[Updated] Excellence Unleashed  The Pinnacle FPS Selections for 2024</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/in-2024-3-actionable-ways-to-create-countdown-animation-for-videos/"><u>In 2024, 3 Actionable Ways to Create Countdown Animation for Videos</u></a></li>
<li><a href="https://extra-information.techidaily.com/essential-podcast-mics-ranked-in-the-top-10/"><u>Essential Podcast Mics  Ranked in the Top 10</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-mp3-kitty-acoustic-trick/"><u>2024 Approved MP3 Kitty Acoustic Trick</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-unveiling-the-mysteries-of-metaverse-persona-designs-for-2024/"><u>[New] Unveiling the Mysteries of Metaverse Persona Designs for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-guides-on-creating-cost-free-youtube-beginnings-and-conclusions/"><u>In 2024, Guides on Creating Cost-Free YouTube Beginnings & Conclusions</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-top-10-high-quality-android-voice-capture-software/"><u>In 2024, Top 10 High-Quality Android Voice Capture Software</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-complete-guide-to-record-desktop-screen-on-windows-for-free-3-ways/"><u>In 2024, Complete Guide to Record Desktop Screen on Windows for Free [3 Ways]</u></a></li>
<li><a href="https://animation-videos.techidaily.com/how-to-make-an-animated-travel-map-video-in-2024/"><u>How to Make an Animated Travel Map Video, In 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/innovative-techniques-for-captivating-fb-video-content/"><u>Innovative Techniques for Captivating FB Video Content</u></a></li>
</ul></div>
