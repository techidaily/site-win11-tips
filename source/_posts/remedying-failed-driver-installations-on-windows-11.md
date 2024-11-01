---
title: Remedying Failed Driver Installations on Windows 11
date: 2024-10-30T16:31:42.014Z
updated: 2024-11-01T16:52:49.226Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Remedying Failed Driver Installations on Windows 11
excerpt: This Article Describes Remedying Failed Driver Installations on Windows 11
keywords: Fixing Drivers in Windows 11,Windows 11 Driver Issues,Resolving Installed Driver Errors,Correcting Failed Driver Installation,Restoring Driver Functionality on Win11,Troubleshooting Device Drivers,Fixing Windows 11 Driver Failure
thumbnail: https://thmb.techidaily.com/0e72ae7670739d2aa724a5c1676e3ea5eb7af36bcb7980843f57c620d01dbd2b.jpg
---

## Remedying Failed Driver Installations on Windows 11

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880976/19272" target="_top" id="1880976">
  <img src="//a.impactradius-go.com/display-ad/19272-1880976" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880976/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1886073/19272" target="_top" id="1886073">
  <img src="//a.impactradius-go.com/display-ad/19272-1886073" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886073/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Reinstall or Remove the Concerned Application

 Some users face an eny.sys driver issue which controls RGB lighting on PCs. This is a problem for many MSI and ASUS PC users. It is not a system utility and if it encounters an error every time, you must reinstall the concerned RGB-lighting-controlled application.

 Reinstalling the latest version will ensure that the application comes with signed drivers and fixes the driver issues with Windows 11 PCs. Here’s how to do it:

1. Right-click on the **Start** button to open the **Power User menu**.
2. Click on the **Installed apps** option.
3. Find the concerned RGB-controlling application and click on the **ellipsis** icon. Select the **Uninstall** option.
4. Click on the **Uninstall** button.  
![Remove a meddlesome application](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/remove-a-meddlesome-application.jpg)

 After removing the app, restart your PC and check if the error pops up now. Now, visit the app manufacturer's website and download the recent version of the RGB-control app. Install it and check if it causes the driver error. If that is the case, then you must remove the application.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049388/7443" target="_top" id="2049388">
  <img src="//a.impactradius-go.com/display-ad/7443-2049388" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049388/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Use System Restore

 System Restore is an excellent utility baked into Windows that helps you fix issues in one go. It will roll back your PC to an earlier state when there were no abrupt issues with your PC.

 Check our guide on [how to use System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) and revert to an earlier PC state without losing your personal files. However, all the installed apps and updates after the restore point will be removed, if you adopt this route.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135365/19272" target="_top" id="2135365">
  <img src="//a.impactradius-go.com/display-ad/19272-2135365" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135365/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://extra-skills.techidaily.com/new-mastering-mobile-media-3-key-steps-to-stabilize-iphone-videos/"><u>[New] Mastering Mobile Media 3 Key Steps to Stabilize iPhone Videos</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-free-video-wizardry-top-8-editing-programs-for-youtube-enthusiasts-for-2024/"><u>[Updated] Free Video Wizardry Top 8 Editing Programs for YouTube Enthusiasts for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-most-acclaimed-3ip-voice-recorders-on-tablets/"><u>[Updated] In 2024, Most Acclaimed 3iP Voice Recorders on Tablets</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-navigating-the-world-of-digital-filters-for-optimal-video-quality-for-2024/"><u>[Updated] Navigating the World of Digital Filters for Optimal Video Quality for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/accelerated-learning-path-with-final-cut-pro-for-2024/"><u>Accelerated Learning Path with Final Cut Pro for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-the-noise-wake-on-idle-restarts-in-w10w11/"><u>Cutting the Noise: Wake on Idle Restarts in W10/W11</u></a></li>
<li><a href="https://video-capture.techidaily.com/from-beginner-to-pro-the-essential-guide-to-capturing-your-mac-display-for-2024/"><u>From Beginner to Pro The Essential Guide to Capturing Your Mac Display for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-elevate-your-ig-videos-tips-and-templates/"><u>In 2024, Elevate Your IG Videos Tips & Templates</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/registration-and-login-virbo-ai-live-stream/"><u>Registration and Login | Virbo AI Live Stream</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedies-for-black-screen-crisis-in-win-based-playing/"><u>Remedies for Black Screen Crisis in Win-Based Playing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stealthy-apps-in-disguise-hurt-your-windows-11-performance/"><u>Stealthy Apps in Disguise Hurt Your Windows 11 Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-action-for-spotify-error-4-windows-11-fixes/"><u>Swift Action for Spotify Error 4: Windows 11 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solution-for-handling-windows-update-failures-and-errors-0x80070003/"><u>Swift Solution for Handling Windows Update Failures & Errors: 0X80070003</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-quintessential-setup-navigating-facebook-twitter-instagram-and-youtube/"><u>The Quintessential Setup: Navigating Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-cdrive-and-ddrive-distinctions/"><u>Understanding C:Drive & D:Drive Distinctions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-the-importance-of-winservicesexe/"><u>Understanding the Importance of WinServices.exe</u></a></li>
</ul></div>

