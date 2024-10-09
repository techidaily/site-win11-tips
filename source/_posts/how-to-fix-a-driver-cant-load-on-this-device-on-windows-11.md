---
title: How to Fix “A Driver Can’t Load on This Device” On Windows 11
date: 2024-10-04T01:29:07.120Z
updated: 2024-10-08T17:15:01.584Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix “A Driver Can’t Load on This Device” On Windows 11
excerpt: This Article Describes How to Fix “A Driver Can’t Load on This Device” On Windows 11
keywords: Windows 11 Install Troubleshooting,Loading Drivers in W11 OS,Resolving Boot Failure Errors,Fixing Driver Load Issues,Windows 11 Update Procedures,Diagnosing Device Driver Problems,Steps to Correct Driver Not Loading
thumbnail: https://thmb.techidaily.com/84ba87eddab3e368851899b58852311f605514d50db5d45ec6de18d3ab0b6cd6.jpg
---

## How to Fix “A Driver Can’t Load on This Device” On Windows 11

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

 You can also visit the device manufacturer’s website to download the latest updated drivers, which will be digitally signed. These should pose no issues during installation.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135394/19272" target="_top" id="2135394">
  <img src="//a.impactradius-go.com/display-ad/19272-2135394" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135394/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://aligracehair.sjv.io/c/5597632/1972698/19272" target="_top" id="1972698">
  <img src="//a.impactradius-go.com/display-ad/19272-1972698" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972698/19272" style="position:absolute;visibility:hidden;" border="0" />
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
6. Paste the following path into the address bar and press the **Enter** key:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Class\`
7. Press **Ctrl + F** to open the **Find** window. **Paste** the copied GUID and click on the **Find Next** option.
8. Go to the right-hand side pane of the found GUID key. Find the **UpperFilters** value.
9. Right-click on it and select the **Delete** option.  
![Modify the System Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/modify-the-system-registry.jpg)
10. Similarly, find the **LowerFilters** value and then delete it as well. Some devices may not have this value.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148642/16836" target="_top" id="2148642">
  <img src="//a.impactradius-go.com/display-ad/16836-2148642" border="0" alt="https://techidaily.com" width="300" height="50"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148642/16836" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2141676/17091" target="_top" id="2141676">
  <img src="//a.impactradius-go.com/display-ad/17091-2141676" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettieu.pxf.io/i/5597632/2141676/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Your Driver Issues on Windows 11, Fixed

 These are the best methods you can use to fix the "A driver can't load on this device" error on your Windows 11 PC. Update all the device drivers, install optional updates, and disable memory integrity. After that, modify the system registry and remove the meddlesome RGB application to get rid of this problem.

 In this guide, we will discuss some methods to resolve this issue and restore your PC drivers to a normal working state.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-skills.techidaily.com/new-mastering-your-digital-talk-leading-web-based-text-to-speech-apps-for-chrome/"><u>[New] Mastering Your Digital Talk Leading Web-Based Text-to-Speech Apps for Chrome</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-how-to-convert-youtube-to-mp4-safely/"><u>[Updated] How to Convert YouTube to MP4 Safely?</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/5-ways-to-send-ringtones-from-apple-iphone-x-to-iphone-including-iphone-15-drfone-by-drfone-transfer-from-ios/"><u>5 Ways to Send Ringtones from Apple iPhone X to iPhone Including iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/motion-vs-youtube-who-earns-more-from-video-content-for-2024/"><u>Dailymotion vs YouTube Who Earns More From Video Content for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-tips-to-control-the-fn-key-functionality/"><u>Effective Tips to Control the Fn Key Functionality</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-3-ways-to-change-location-on-facebook-marketplace-for-tecno-phantom-v-fold-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Change Location on Facebook Marketplace for Tecno Phantom V Fold | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-a-dual-device-expedition-in-virtual-frontiers/"><u>In 2024, A Dual-Device Expedition in Virtual Frontiers</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-downloading-samfw-frp-tool-30-for-oneplus-nord-3-5g-by-drfone-android/"><u>In 2024, Downloading SamFw FRP Tool 3.0 for OnePlus Nord 3 5G</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-fix-life360-shows-wrong-location-on-infinix-hot-40-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Life360 Shows Wrong Location On Infinix Hot 40? | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-depth-analysis-of-the-kasa-ks240-a-user-friendly-guide-to-integrating-with-apples-homekit/"><u>In-Depth Analysis of the Kasa KS240: A User-Friendly Guide to Integrating with Apple's HomeKit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-smoothly-sync-with-onedrive-even-when-failed-windows-11/"><u>Quick Guide to Smoothly Sync with OneDrive, Even When Failed (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-tips-to-unfreeze-your-torrents-in-windows/"><u>Quick Tips to Unfreeze Your Torrents in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-disappearing-iconage-for-windows-apps/"><u>Restore Disappearing Iconage for Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speed-up-your-workflow-solving-windows-excel-lag/"><u>Speed Up Your Workflow: Solving Windows-Excel Lag</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-windows-tools-accessibility-hotkey-configurations-for-fixes/"><u>Tailoring Windows Tools Accessibility: Hotkey Configurations for Fixes</u></a></li>
<li><a href="https://android-transfer.techidaily.com/top-5-from-vivo-s17e-to-iphone-contacts-transfer-apps-and-software-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Top 5 from Vivo S17e to iPhone Contacts Transfer Apps and Software | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-your-devices-full-internet-potential-in-windows-11/"><u>Unlock Your Device’s Full Internet Potential in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-hidden-power-of-your-computers-windows-key/"><u>Unveiling the Hidden Power of Your Computer's Windows Key</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-wonderland-how-to-identify-your-computers-brand-and-model/"><u>Windows Wonderland: How To Identify Your Computer's Brand & Model</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    