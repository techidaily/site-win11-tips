---
title: Fixing Unloading Drivers on Windows 11 System
date: 2025-02-12T17:29:26.259Z
updated: 2025-02-16T02:46:28.432Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DCARjc5g5VI?si=9OfovbKBrpoJeXTY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/l-SCWTWpegY?si=oxTsHQkIu1v4-I6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/XoC2TGp1PLY?si=iH9xs76NhWn4pP-E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Paste the following path into the address bar and press the **Enter** key:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Class\`
7. Press **Ctrl + F** to open the **Find** window. **Paste** the copied GUID and click on the **Find Next** option.
8. Go to the right-hand side pane of the found GUID key. Find the **UpperFilters** value.
9. Right-click on it and select the **Delete** option.  
![Modify the System Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/modify-the-system-registry.jpg)
10. Similarly, find the **LowerFilters** value and then delete it as well. Some devices may not have this value.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KKFdFHaVIJg?si=x2vLw7ty3FtHX-9T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

11. **Restart** your PC for the changes to take effect.

## 5\. Reinstall or Remove the Concerned Application

 Some users face an eny.sys driver issue which controls RGB lighting on PCs. This is a problem for many MSI and ASUS PC users. It is not a system utility and if it encounters an error every time, you must reinstall the concerned RGB-lighting-controlled application.

 Reinstalling the latest version will ensure that the application comes with signed drivers and fixes the driver issues with Windows 11 PCs. Here’s how to do it:

1. Right-click on the **Start** button to open the **Power User menu**.
2. Click on the **Installed apps** option.
3. Find the concerned RGB-controlling application and click on the **ellipsis** icon. Select the **Uninstall** option.
4. Click on the **Uninstall** button.  
![Remove a meddlesome application](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/remove-a-meddlesome-application.jpg)

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
<li><a href="https://fox-helps.techidaily.com/updated-game-of-thrones-ringtones-15-best-websites-reviewed-and-ranked-for-2024/"><u>[Updated] Game of Thrones Ringtones 15 Best Websites Reviewed and Ranked for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-streamlining-screen-captures-on-mi-11-lite/"><u>[Updated] Streamlining Screen Captures on Mi 11 Lite</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-premium-pick-of-budget-friendly-vectors-and-graphic-sites/"><u>2024 Approved Premium Pick of Budget-Friendly Vectors & Graphic Sites</u></a></li>
<li><a href="https://location-social.techidaily.com/change-location-on-yik-yak-for-your-xiaomi-redmi-note-12r-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>Change Location on Yik Yak For your Xiaomi Redmi Note 12R to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-to-lava-blaze-2-pro-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Lava Blaze 2 Pro FRP Bypass With Best Methods</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/easy-steps-to-resolve-d3dx934dll-missing-on-your-pc/"><u>Easy Steps to Resolve d3dx9_34.dll Missing on Your PC</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-troubleshooting-update-your-synaptics-touchpad-driver-without-hassle/"><u>Easy Troubleshooting: Update Your Synaptics Touchpad Driver Without Hassle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-overcoming-microsoft-store-crashes-0x80073d26-fix/"><u>Guide to Overcoming Microsoft Store Crashes: 0X80073D26 Fix</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-peak-workshop-masterpiece-insight/"><u>In 2024, Peak Workshop Masterpiece Insight</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-basics-starting-microsoft-paint-in-windows-11/"><u>Mastering the Basics: Starting Microsoft Paint in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-brighten-up-dark-windows-display/"><u>Methods to Brighten Up Dark Windows Display</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamping-the-reset-account-lockout-after-incorrect-passwords-on-windows-11/"><u>Revamping the Reset Account Lockout After Incorrect Passwords on Windows 11</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-solutions-to-restart-and-refresh-your-iphone-15-device/"><u>Ultimate Solutions to Restart and Refresh Your iPhone 15 Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfreezing-frozen-windows-run-logs/"><u>Unfreezing Frozen Windows Run Logs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-and-resolving-entry-not-found-error/"><u>Unveiling and Resolving 'Entry Not Found' Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-truth-how-to-detect-your-hard-drivessd-status-in-windows/"><u>Unveiling the Truth: How to Detect Your Hard Drive/SSD Status in Windows</u></a></li>
</ul></div>

