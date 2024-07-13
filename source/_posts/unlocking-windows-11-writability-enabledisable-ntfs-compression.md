---
title: "Unlocking Windows 11' Writability: Enable/Disable NTFS Compression"
date: 2024-07-12T16:30:02.193Z
updated: 2024-07-13T16:30:02.193Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlocking Windows 11' Writability: Enable/Disable NTFS Compression"
excerpt: "This Article Describes Unlocking Windows 11' Writability: Enable/Disable NTFS Compression"
keywords: Win11 WriteAbility,Disable NTFS Comp,Enable NTFS Off,Windows NTFS Control,Manage Windows Text,Compress NTFS Locked,Change NTFS Settings
thumbnail: https://thmb.techidaily.com/4cdd8afbaa8b657928993c65ff49e85d13ed5759387c65adfd46afd484910746.jpg
---

## Unlocking Windows 11' Writability: Enable/Disable NTFS Compression

 Is your Windows computer running out of storage? There are plenty of ways to remove redundant data and free up some extra space. Among all, the most preferred method is using NTFS file compression.

 NTFS file compression is a Windows feature that compresses files and folders by removing reductant data from them. The best part about this feature is that it does its job without damaging the file and losing the data.

 Nevertheless, let's check out some ways to enable NTFS file compression in Windows 11.

## 1\. Enable NTFS File Compression Through the File Explorer

 The quickest way to enable NTFS [file compression](https://www.makeuseof.com/windows-11-file-compression-guide/) is through File Explorer. Below are the steps to compress a folder:

1. Open the File Explorer and head toward the folder you want to compress.
2. Right-click on the target folder and choose**Properties** from the context menu.
3. In the**General** tab, select the**Advanced** option.
4. Under the**Compress or Encrypt attributes** section, check the**Compress contents to save disk space** box and click**OK** .  
![Compress content to save disk option in Folder properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/compress-content-to-save-disk-option.jpg)
5. Click**Apply** \>**OK** to save the changes.
6. In the confirmation dialog box that crops up, choose the **Apply changes to this folder, subfolders, and files option** .  
![Apply changes option in folder properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/apply-changes-option.jpg)
7. Click**OK.**

 That's it, the folder has now been compressed. You can confirm this by comparing the current folder size with its previous size.

 From now on, every file or folder that you will move inside the compressed folder will be compressed automatically. To disable compression, uncheck the**Compress contents to save disk space** box and save the changes.

Similarly, you can compress an entire drive. Here's how:

1. Open the File Explorer, and right-click on the drive you want to compress.
2. In the**General** tab, check the**Compress this drive to save disk space** box.  
![Driver properties in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/driver-properties.jpg)
3. Click**Apply** and then click**OK** on the confirmation box that crops up.

## 2\. Enable NTFS File Compression Using the Command Prompt

 If you are a power user, you can use the Command Prompt to enable file compression on Windows 11\. Here are the steps to do it:

1. Press the**Win + S** hotkeys to open the**Windows Search.**
2. In the search bar, type**Command Prompt** and choose**Run as administrator** from the right pane. If this method is not working, you can use any other way to [open Command Prompt with admin rights](https://www.makeuseof.com/how-to-always-open-command-prompt-as-administrator-windows/) .
3. Type the following command and press**Enter** to enable file compression.  
`fsutil behavior set disablecompression 0`

![File compression command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/file-compression-command.jpg)

 You'll see the "**A reboot is required for this change to take effect** " message on the console. So, restart your computer to apply the changes.

 If you want to disable File Compression, execute the following command in the elevated Command Prompt window, followed by a system restart.

`fsutil behavior set disablecompression 1`

## 3\. Enable NTFS File Compression Using the Registry Editor

 Another quick way to enable compression is through the Registry Editor. Follow the below steps to do it:

1. Open the**Run dialog box** by pressing the**Win + R** hotkeys.
2. Type**regedit** in the text field and click**OK.**
3. In the Registry Editor, navigate to the below location:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Policies`
4. Right-click on the**Policies** folder in the left sidebar, hover the cursor to**New,** and choose**DWORD** **(32-bit) Value** from the context menu.  
![Choosing DWORD in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/choosing-dword.jpg)
5. Right-click on the newly created value and choose**Rename** .
6. Type**Ntfsenablecompression** in the text field.
7. Select and right-click on**Ntfsenablecompression** again, and choose**Modify** .
8. Type**1** in the**Value data** .  
![Editing Ntfsenablecompression in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/editing-ntfsenablecompression.jpg)
9. Click**OK** to save the changes.

 File compression is now enabled on your computer. If you want to disable it, type 0 in Value data and save the changes.

## 4\. Enable NTFS File Compression Using the Local Group Policy Editor

 The Local Group Policy Editor is the go-to place to configure important Windows policies. To use it to enable file compression, follow the below instructions:

1. In the Run dialog box, type**gpedit.msc** and click**OK.**
2. Head towards the following location in the Local Group Policy Editor:  
`Computer Configuration\Administrative Templates\System\Filesystem\NTFS`
3. Double-click on the**Do not allow compression on all NTFS volumes policy** to open its properties window.
4. Choose the**Disabled** option.  
![Disabling policy in LGPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disabling-policy.jpg)
5. Click**Apply** \>**OK** to enable file compression.

 You can disable the file compression by choosing the**Enabled** option in the**Do not allow compression on all NTFS volumes policy** properties window.

## Free Up Space on Windows 11 With File Compression

 Enabling file compression is a great way to free up some space on Windows 11\. Using this feature can come in handy when you are running out of space but also don't want to compress your files using third-party compression tools.

 Meanwhile, you might be interested in learning more about the NTFS file system.


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
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-registry-tweaks-in-windows-terminal/"><u>The Ultimate Guide to Registry Tweaks in Windows Terminal</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/where-is-the-best-place-to-catch-dratini-on-apple-iphone-7-drfone-by-drfone-virtual-ios/"><u>Where Is the Best Place to Catch Dratini On Apple iPhone 7 | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-the-magnificent-art-of-pokemon-go-streaming-on-oppo-a58-4g-drfone-by-drfone-virtual-android/"><u>In 2024, The Magnificent Art of Pokemon Go Streaming On Oppo A58 4G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-solve-windows-error-exception-breakpoint-encountered/"><u>Steps to Solve Windows Error: Exception Breakpoint Encountered</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/detailed-review-of-doctorsim-unlock-service-for-apple-iphone-12-pro-max-drfone-by-drfone-ios/"><u>Detailed Review of doctorSIM Unlock Service For Apple iPhone 12 Pro Max | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/three-ways-to-sim-unlock-motorola-edge-40-neo-by-drfone-android/"><u>Three Ways to Sim Unlock Motorola Edge 40 Neo</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-no-cost-no-problem-top-free-video-editing-software-for-chromebook/"><u>Updated In 2024, No Cost, No Problem Top Free Video Editing Software for Chromebook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-desktop-portable-tools-in-win11-menu/"><u>Streamline Your Desktop: Portable Tools in Win11 Menu</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-achieving-authenticity-altering-voices-on-instagram-profiles/"><u>[Updated] 2024 Approved  Achieving Authenticity  Altering Voices on Instagram Profiles</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-androidprocessmedia-has-stopped-on-poco-c51-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android.Process.Media Has Stopped on Poco C51 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-ignoring-restricted-feature-on-windows-software/"><u>Tips for Ignoring Restricted Feature on Windows Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-hidden-disk-space-with-windows-1011s-deletion-automation/"><u>Unlock Hidden Disk Space with Windows 10/11'S Deletion Automation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-resource-building-shortcuts-for-microsofts-uwp-apps-in-windows-11/"><u>The Ultimate Resource: Building Shortcuts for Microsoft's UWP Apps in Windows 11</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-reverse-engineering-a-step-by-step-guide-to-reversing-tiktok-videos/"><u>Updated In 2024, Reverse Engineering A Step-by-Step Guide to Reversing TikTok Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-temporary-file-error-1152-on-windows/"><u>Remedying Temporary File Error 1152 on Windows</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-macbook-air-vs-pro-evaluating-the-m1-advantage/"><u>In 2024, MacBook Air Vs. Pro  Evaluating the M1 Advantage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-pcs-touch-interface-a-user-friendly-tutorial/"><u>Tailoring Your PC’s Touch Interface: A User-Friendly Tutorial</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-navigating-the-path-to-youtube-stardom-with-these-tactics/"><u>[New] Navigating the Path to YouTube Stardom with These Tactics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/onedrives-blob-tag-issue-a-windows-based-solution-guide/"><u>OneDrive's Blob Tag Issue: A Windows-Based Solution Guide</u></a></li>
<li><a href="https://extra-resources.techidaily.com/gigglygraphics-mememakers-haven/"><u>GigglyGraphics  MemeMaker's Haven</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-stuck-scrollbar-and-freezing-pages-in-microsoft-excel-on-windows/"><u>Stop Stuck Scrollbar & Freezing Pages in Microsoft Excel on Windows</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-split-trim-and-edit-mastering-video-segmentation-in-windows-live-movie-maker-for-2024/"><u>Updated Split, Trim, and Edit Mastering Video Segmentation in Windows Live Movie Maker for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-windows-1011s-camera-error-0xa00f425d/"><u>Quick-Fix for Windows 10/11'S Camera Error: 0XA00F425D</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-reset-a-motorola-edge-40-neo-phone-that-is-locked-by-drfone-android/"><u>In 2024, How to Reset a Motorola Edge 40 Neo Phone that is Locked?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secrets-of-superior-gaming-with-amd-radeon-tweaks/"><u>Secrets of Superior Gaming with AMD Radeon Tweaks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/self-guided-inspector-writes-secure-your-computer-from-spyware/"><u>Self-Guided Inspector' Writes: Secure Your Computer From Spyware</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-tune-tracker-latest-audio-tech-for-2024/"><u>[New] Tune Tracker  Latest Audio Tech for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-reactivating-windows-11s-diagnostic-features/"><u>Quick Fixes: Reactivating Windows 11'S Diagnostic Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-user-profile-correction-for-w11-oses/"><u>Mastering User Profile Correction for W11 OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-apex-of-atmospheric-analysis-windows-11s-top-weather-apps/"><u>The Apex of Atmospheric Analysis: Windows 11'S Top Weather Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-virtualboxs-0x80004005-failure-message/"><u>Resolving Virtualbox's 0X80004005 Failure Message</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-a-filmmakers-companion-the-journey-from-capturing-to-post-production-of-360-videos/"><u>2024 Approved  A Filmmaker's Companion  The Journey From Capturing to Post-Production of 360 Videos</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-comparative-review-top-cloud-services-prices/"><u>2024 Approved  Comparative Review  Top Cloud Services' Prices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-ram-essential-tweaks-for-enhanced-windows-performance/"><u>Maximizing RAM: Essential Tweaks for Enhanced Windows Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-utorrent-installer-errors-in-windows-environment/"><u>Overcoming uTorrent Installer Errors in Windows Environment</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-free-banner-templates-and-makers-for-youtube/"><u>In 2024, Free Banner Templates & Makers for YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-pc-reset-virtual-memory/"><u>Optimize Your PC: Reset Virtual Memory</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-mac-movie-magic-how-to-bring-your-vision-to-life/"><u>New 2024 Approved Mac Movie Magic How to Bring Your Vision to Life</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-typical-directory-display-order-in-win11/"><u>Reviving Typical Directory Display Order in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-convert-cr2-images-to-windows-friendly-jpg-format/"><u>Swiftly Convert CR2 Images to Windows-Friendly JPG Format</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-black-screen-phenomenon-in-webcams/"><u>Overcoming Black Screen Phenomenon in Webcams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaim-lost-control-panel-features-on-windows-11/"><u>Reclaim Lost Control Panel Features on Windows 11</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-expanding-reach-fb-live-on-broadcast-networks/"><u>[New] Expanding Reach  FB Live on Broadcast Networks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-normal-display-on-microsoft-store/"><u>Restoring Normal Display on Microsoft Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/single-point-protection-the-benefits-of-a-solo-antivirus-on-windows/"><u>Single-Point Protection: The Benefits of a Solo Antivirus on Windows</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/professional-edge-in-instagram-videos-with-green-screen-tech-for-2024/"><u>Professional Edge in Instagram Videos with Green Screen Tech for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-clearing-steams-dns-cache/"><u>Mastering the Art of Clearing Steam's DNS Cache</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-remove-a-previously-synced-google-account-from-your-samsung-by-drfone-android/"><u>In 2024, How to Remove a Previously Synced Google Account from Your Samsung</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-chuckle-fest-the-ultimate-list-of-hilarious-youtube-personalities/"><u>[Updated] In 2024, Chuckle Fest  The Ultimate List of Hilarious YouTube Personalities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-upgrades-safely-with-tpm-and-secure-boot-enablement/"><u>Navigating Upgrades Safely with TPM and Secure Boot Enablement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-disabled-troubleshooters-in-modern-windows/"><u>Resolving Disabled Troubleshooters in Modern Windows</u></a></li>
</ul></div>
