---
title: Overcoming Device Driver Load Failure in Win11
date: 2024-06-25T17:06:19.939Z
updated: 2024-06-26T17:06:19.939Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Device Driver Load Failure in Win11
excerpt: This Article Describes Overcoming Device Driver Load Failure in Win11
keywords: Win11 Driver Loading,Fixing Windows 11,Device Driver Error,Overcome Drive Fail,Win11 Boot Issue,Load Failure Win10,Resolving Driver Crashes
thumbnail: https://thmb.techidaily.com/1ddec9a0b5a6c3e1804c33a43db9c91ffd9d92f92510209406429341a2fb6bc6.jpg
---

## Overcoming Device Driver Load Failure in Win11

 Windows loads drivers every time you power on your PC. However, some users face the "A driver can't load on this device" error after they boot to the desktop. This error can arise while installing an unsigned driver or due to a meddlesome application.

 In this guide, we will discuss some methods to resolve this issue and restore your PC drivers to a normal working state.

## 1\. Check for Optional Windows Updates

 Optional updates can contain driver updates for your device components. So, you must check for available driver updates in the Windows Update Settings. Repeat the following steps:

1. Press **Win + I** to launch the Settings app.
2. Click on the **Windows Update** icon.
3. Now click on the **Advanced options**.
4. Scroll down to the **Additional Options** section. Click on the **Optional Updates** option.
5. Check if any optional updates related to the device you are facing issues with are available. Download and install it.  
![Install optional updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/install-optional-updates.jpg)
6. **Close** the Settings app.

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
6. Paste the following path into the address bar and press the **Enter** key:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Class\`
7. Press **Ctrl + F** to open the **Find** window. **Paste** the copied GUID and click on the **Find Next** option.
8. Go to the right-hand side pane of the found GUID key. Find the **UpperFilters** value.
9. Right-click on it and select the **Delete** option.  
![Modify the System Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/modify-the-system-registry.jpg)
10. Similarly, find the **LowerFilters** value and then delete it as well. Some devices may not have this value.
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/in-pursuit-of-purposeful-downloads-from-windows-store/"><u>In Pursuit of Purposeful Downloads From Windows Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-mystery-of-windows-1011-failed-app-start/"><u>Unveiling the Mystery of Windows 10/11 Failed App Start</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-password-entry-for-instantaneous-win-11-connections/"><u>Bypassing Password Entry for Instantaneous Win 11 Connections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-altering-window-icons-distance-on-11plus-windows/"><u>Title: Altering Window Icons' Distance on 11+ Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-steam-cloud-syncs-in-win-10/"><u>Fixing Steam Cloud Syncs in Win 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719373707174-check-physical-connections-make-sure-cables-are-firmly-connected-if-you-have-external-monitors-or-projectors-with-separate-brightness-controls/"><u>Check Physical Connections: Make Sure Cables Are Firmly Connected if You Have External Monitors or Projectors with Separate Brightness Controls.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-chrome-freeze-and-blank-screens/"><u>Fixing the Chrome Freeze and Blank Screens</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-locked-out-of-apple-iphone-12-pro-max-5-ways-to-get-into-a-locked-apple-iphone-12-pro-max-drfone-by-drfone-ios/"><u>In 2024, Locked Out of Apple iPhone 12 Pro Max? 5 Ways to get into a Locked Apple iPhone 12 Pro Max | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-top-10-best-free-facetime-for-android-alternatives/"><u>[New] 2024 Approved  Top 10 Best Free FaceTime for Android Alternatives</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-unlocking-the-potential-complete-review-of-sony-x1000v/"><u>2024 Approved  Unlocking the Potential  Complete Review of Sony X1000V</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-5-best-auto-music-mixer-for-mac/"><u>Updated 5 Best Auto Music Mixer for Mac</u></a></li>
<li><a href="https://video-capture.techidaily.com/excellent-video-capture-tools-android-edition-five-picks-for-2024/"><u>Excellent Video Capture Tools  Android Edition - Five Picks for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/mastering-android-device-manager-the-ultimate-guide-to-unlocking-your-realme-gt-neo-5-device-by-drfone-android/"><u>Mastering Android Device Manager The Ultimate Guide to Unlocking Your Realme GT Neo 5 Device</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-summit-creation-pro-x-evaluation-for-2024/"><u>[New] Summit Creation Pro X Evaluation for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-top-10-horizontal-and-vertical-igtv-editing-apps-reviewed-for-2024/"><u>[New] Top 10 Horizontal & Vertical IGTV Editing Apps Reviewed for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-best-choices-8-edits-suites-for-linux-users/"><u>[New] 2024 Approved  Best Choices  8 Edits Suites for Linux Users</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>