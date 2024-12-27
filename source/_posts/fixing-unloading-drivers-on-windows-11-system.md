---
title: Fixing Unloading Drivers on Windows 11 System
date: 2024-12-20T19:47:06.546Z
updated: 2024-12-27T21:05:41.657Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Unloading Drivers on Windows 11 System
excerpt: This Article Describes Fixing Unloading Drivers on Windows 11 System
keywords: Windows 11 Unloader Fix,Driver Loading Issue Solve,Resolve Windows Loaders,Boot Device Troubleshoot,Fix Windows OS Errors,Update PC Boot Drivers,Diagnose System Start Error
thumbnail: https://thmb.techidaily.com/b513a033c1a351aae3735f8454f39fad640e3916330df7f776c432bd4bea35f1.jpg
---

## Fixing Unloading Drivers on Windows 11 System

 Windows loads drivers every time you power on your PC. However, some users face the "A driver can't load on this device" error after they boot to the desktop. This error can arise while installing an unsigned driver or due to a meddlesome application.

 In this guide, we will discuss some methods to resolve this issue and restore your PC drivers to a normal working state.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Check for Optional Windows Updates

 Optional updates can contain driver updates for your device components. So, you must check for available driver updates in the Windows Update Settings. Repeat the following steps:

1. Press **Win + I** to launch the Settings app.
2. Click on the **Windows Update** icon.
3. Now click on the **Advanced options**.
4. Scroll down to the **Additional Options** section. Click on the **Optional Updates** option.
5. Check if any optional updates related to the device you are facing issues with are available. Download and install it.  
![Install optional updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/install-optional-updates.jpg)
6. **Close** the Settings app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2Iv3DjT2Fyw?si=pR_z8ZDDVGF2MvKJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can also visit the device manufacturer’s website to download the latest updated drivers, which will be digitally signed. These should pose no issues during installation.

## 2\. Disable the Memory Integrity Feature

 Memory Integrity is a security feature that leverages virtualization to protect unauthorized programs from making changes to important security processes. But this security setting can prevent a driver from loading old or unsigned drivers from running on your PC.

 So, you must disable Memory Integrity. Repeat the following steps:

1. Press **Win + I** to open the Settings app.
2. Click on the **Privacy & security** option in the left-hand side menu.
3. Now, click on the **Windows Security** option.
4. Scroll down and click on the **Device Security** option.
5. Navigate to the Core Isolation section. Click on the **Core isolation details** option.
6. Disable the **toggle** present below the **Memory Integrity** option.  
![Disable Memory Integrity](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/disable-memory-integrity.jpg)
7. **Restart** your PC to apply the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0nGlyEL5K6Y?si=3KZhTTBvKcPmyS68" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now, check if the “a driver cannot load on this device” still pops up.

## 3\. Uninstall Any Recent System Updates

 If you are encountering an issue with a driver after installing a recent Windows update, you should consider removing that from your PC. Rolling back the update won’t remove any of your personal files.

 Check our guide on [ways to manually uninstall Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) for more information. But remember that it is not possible to remove all installed updates.

## 4\. Modify the System Registry

 Corrupt registry entries for the device can also be a reason for the hardware device encountering the driver issue. So, you must modify the system registry and remove those corrupt entries for the device.

 Make sure to manually export a [backup of your PC registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) onto a removable drive, so you always have the option to revert to the last working configuration.

 Repeat the following steps:

1. Right-click on the **Start** button to open the **Power User menu**. Click on the **Device Manager** option.
2. Locate the device facing driver issues and double-click on it to open its **Properties**.
3. Switch to the **Details** tab.
4. Click on the drop-down tab and click on the **Class GUID** option. It will display the GUID. **Copy** it to the clipboard.  
![Checking GUID in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/checking-guid-in-device-manager.jpg)
5. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **Regedit** and press the **Ctrl + Shift + Enter** keys to open the Registry editor.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/d-COuhPT5mk?si=wLZU6jkkAdJuAn6h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Paste the following path into the address bar and press the **Enter** key:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Class\`
7. Press **Ctrl + F** to open the **Find** window. **Paste** the copied GUID and click on the **Find Next** option.
8. Go to the right-hand side pane of the found GUID key. Find the **UpperFilters** value.
9. Right-click on it and select the **Delete** option.  
![Modify the System Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/modify-the-system-registry.jpg)
10. Similarly, find the **LowerFilters** value and then delete it as well. Some devices may not have this value.
11. **Restart** your PC for the changes to take effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SyMZxS9479s?si=0T6zZpyN2LBftFTM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Reinstall or Remove the Concerned Application

 Some users face an eny.sys driver issue which controls RGB lighting on PCs. This is a problem for many MSI and ASUS PC users. It is not a system utility and if it encounters an error every time, you must reinstall the concerned RGB-lighting-controlled application.

 Reinstalling the latest version will ensure that the application comes with signed drivers and fixes the driver issues with Windows 11 PCs. Here’s how to do it:

1. Right-click on the **Start** button to open the **Power User menu**.
2. Click on the **Installed apps** option.
3. Find the concerned RGB-controlling application and click on the **ellipsis** icon. Select the **Uninstall** option.
4. Click on the **Uninstall** button.  
![Remove a meddlesome application](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/remove-a-meddlesome-application.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LI9nKlbhnw8?si=uUXFVbuEqXtFHHv0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After removing the app, restart your PC and check if the error pops up now. Now, visit the app manufacturer's website and download the recent version of the RGB-control app. Install it and check if it causes the driver error. If that is the case, then you must remove the application.

## 6\. Use System Restore

 System Restore is an excellent utility baked into Windows that helps you fix issues in one go. It will roll back your PC to an earlier state when there were no abrupt issues with your PC.

 Check our guide on [how to use System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) and revert to an earlier PC state without losing your personal files. However, all the installed apps and updates after the restore point will be removed, if you adopt this route.

## Your Driver Issues on Windows 11, Fixed

 These are the best methods you can use to fix the "A driver can't load on this device" error on your Windows 11 PC. Update all the device drivers, install optional updates, and disable memory integrity. After that, modify the system registry and remove the meddlesome RGB application to get rid of this problem.

 In this guide, we will discuss some methods to resolve this issue and restore your PC drivers to a normal working state.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-zero.techidaily.com/n-2024-crafting-your-music-collection-youtube-playlists-guide/"><u>[New] In 2024, Crafting Your Music Collection YouTube Playlists Guide</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-silent-streaming-rankings-of-the-top-8-secret-downloaders-2023/"><u>[New] In 2024, Silent Streaming Rankings of the Top 8 Secret Downloaders, 2023</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-unlock-seamless-video-conversion-youtube-to-dailymotion/"><u>[Updated] In 2024, Unlock Seamless Video Conversion YouTube to Dailymotion</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-social-media-success-strategies-for-effective-facebook-reel-creation/"><u>[Updated] Social Media Success Strategies for Effective Facebook Reel Creation</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-timeless-stop-motion-gems-in-the-top-15/"><u>2024 Approved Timeless Stop-Motion Gems in the Top 15</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-the-process-of-clearing-restrictions-in-pcs/"><u>Demystifying the Process of Clearing Restrictions in PCs</u></a></li>
<li><a href="https://driver-download.techidaily.com/download-and-setup-for-epson-xp-400-printer-drivers-user-friendly-guide/"><u>Download & Setup for Epson XP 400 Printer Drivers: User Friendly Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-alternative-av-solutions-despite-microsoft-defender-blockade/"><u>Enabling Alternative AV Solutions Despite Microsoft Defender Blockade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-file-transfer-capabilities-chrome-downloads-in-windows/"><u>Enhancing File Transfer Capabilities: Chrome Downloads in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/getting-lele-playable-again-fix-windows-wol-issues/"><u>Getting LeLë Playable Again: Fix Windows WoL Issues</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-can-i-remove-the-apple-watch-activation-lock-by-iphone-11-pro-max-without-the-previous-owner-by-drfone-ios/"><u>In 2024, Can I Remove the Apple Watch Activation Lock By iPhone 11 Pro Max without the Previous Owner?</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-sharefake-location-on-whatsapp-for-huawei-p60-drfone-by-drfone-virtual-android/"><u>In 2024, How to Share/Fake Location on WhatsApp for Huawei P60 | Dr.fone</u></a></li>
<li><a href="https://discover-cheats.techidaily.com/mastering-the-art-of-flipbook-watermarking-a-step-by-step-guide-with-flipbuilder/"><u>Mastering the Art of FlipBook Watermarking: A Step-by-Step Guide with FlipBuilder</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-wsl-android-resource-allocation/"><u>Optimizing WSL Android Resource Allocation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-fix-non-transferring-data-from-windows-usb-devices/"><u>Strategies to Fix Non-Transferring Data From Windows USB Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1011-the-essential-password-addition-technique/"><u>Windows 10/11: The Essential Password Addition Technique</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-pin-woes-heres-what-to-do/"><u>Windows PIN Woes? Here's What to Do</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-strategies-for-completing-windows-endless-countdowns/"><u>Winning Strategies for Completing Windows' Endless Countdowns</u></a></li>
<li><a href="https://win-comparisons.techidaily.com/zdnets-top-picks-superior-standing-desk-attachment-units-reviewed/"><u>ZDNET's Top Picks: Superior Standing Desk Attachment Units Reviewed</u></a></li>
</ul></div>

