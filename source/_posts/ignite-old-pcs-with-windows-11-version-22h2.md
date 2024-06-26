---
title: Ignite Old PCs with Windows 11 Version 22H2
date: 2024-06-25T17:01:50.245Z
updated: 2024-06-26T17:01:50.245Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Ignite Old PCs with Windows 11 Version 22H2
excerpt: This Article Describes Ignite Old PCs with Windows 11 Version 22H2
keywords: Ignite Old PCs,Windows 11 Upgrade,22H2 Release,Old PC Revival,Free OS Update,Legacy Systems Focus,Microsoft Windows X
thumbnail: https://thmb.techidaily.com/b940b6b0f5ea7e32cad1821c53c7dd63eece1d15c1851d2a65f8ffeb1e28c4c2.jpg
---

## Ignite Old PCs with Windows 11 Version 22H2

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
<li><a href="https://win11-tips.techidaily.com/mastering-voice-commands-xbox-and-pc-synergy/"><u>Mastering Voice Commands: Xbox & PC Synergy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-windows-store-faults-rectify-error-0x80072f17/"><u>Mending Windows Store Faults: Rectify Error 0X80072f17</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-3-windows-group-policy-approaches/"><u>Navigating 3 Windows Group Policy Approaches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-file-denial-in-steam-for-windows-11-users/"><u>Tackling File Denial in Steam for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-the-new-windows-taskbar-design/"><u>Maximizing the New Windows Taskbar Design</u></a></li>
<li><a href="https://win11-tips.techidaily.com/chilly-cheer-christmas-presents-with-microsofts-marketplace/"><u>Chilly Cheer: Christmas Presents with Microsoft's Marketplace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-gmaps-integration-process-in-windows/"><u>Navigating the GMaps Integration Process in Windows</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-ultimate-compilation-of-top-sky-hd-sites-for-2024/"><u>The Ultimate Compilation of Top Sky HD Sites for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/the-art-of-auditory-transformation-replacing-audio-in-videos-step-by-step/"><u>The Art of Auditory Transformation Replacing Audio in Videos Step by Step</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-mobile-split-screen-video-editors-the-best-for-ios-and-android/"><u>2024 Approved Mobile Split Screen Video Editors The Best for iOS and Android</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-quick-and-easy-steps-to-efficient-free-clock-use/"><u>[Updated] Quick and Easy Steps to Efficient Free Clock Use</u></a></li>
<li><a href="https://android-location.techidaily.com/10-fake-gps-location-apps-on-android-of-your-vivo-t2-5g-drfone-by-drfone-virtual/"><u>10 Fake GPS Location Apps on Android Of your Vivo T2 5G | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-5-most-effective-methods-to-unlock-iphone-11-pro-in-lost-mode-by-drfone-ios/"><u>In 2024, 5 Most Effective Methods to Unlock iPhone 11 Pro in Lost Mode</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-framelight-free-elevate-mobile-photography-today/"><u>In 2024, Framelight Free  Elevate Mobile Photography Today</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-the-ultimate-method-to-locate-fb-watched-content/"><u>[Updated] In 2024, The Ultimate Method to Locate FB Watched Content</u></a></li>
</ul></div>
