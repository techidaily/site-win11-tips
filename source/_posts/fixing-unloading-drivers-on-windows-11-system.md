---
title: Fixing Unloading Drivers on Windows 11 System
date: 2025-02-28T21:44:23.564Z
updated: 2025-03-04T19:09:03.488Z
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

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-information.techidaily.com/new-amplify-your-voice-expert-insights-on-podcast-editing-in-garageband/"><u>[New] Amplify Your Voice Expert Insights on Podcast Editing in GarageBand</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-unmatched-ai-tools-for-visual-storytelling-for-2024/"><u>[Updated] Unmatched AI Tools for Visual Storytelling for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-pc-screen-to-motorola-razr-40-phones-drfone-by-drfone-android/"><u>How to Mirror PC Screen to Motorola Razr 40 Phones? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-prevent-and-cure-system-settings-failures-in-win11/"><u>How to Prevent and Cure System Settings Failures in Win11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-the-apple-iphone-14-plus-sim-lock-4-easy-methods-by-drfone-ios/"><u>In 2024, How To Unlock The Apple iPhone 14 Plus SIM Lock 4 Easy Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-unreachable-error-from-geforce-experience-on-pc/"><u>Overcoming Unreachable Error From GeForce Experience on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prioritizing-safety-in-windows-11-service-management/"><u>Prioritizing Safety in Windows 11 Service Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-tips-for-win11s-5ghz-wi-fi-disconnection-fixes/"><u>Quick Tips for Win11's 5GHz Wi-Fi Disconnection Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-internal-system-configurations-on-windows-11/"><u>Steps to Rectify Internal System Configurations on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-steps-for-removing-microsoft-points-out/"><u>Streamlined Steps for Removing Microsoft' Points Out</u></a></li>
<li><a href="https://win-top.techidaily.com/understanding-redirects-comprehensive-guide-with-essential-seo-strategies-boost-your-sites-ranking/"><u>Understanding Redirects: Comprehensive Guide with Essential SEO Strategies | Boost Your Site's Ranking</u></a></li>
</ul></div>

