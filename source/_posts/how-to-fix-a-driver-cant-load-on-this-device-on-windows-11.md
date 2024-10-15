---
title: How to Fix “A Driver Can’t Load on This Device” On Windows 11
date: 2024-10-12T21:21:31.382Z
updated: 2024-10-15T11:44:39.322Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997635/19272" target="_top" id="1997635">
  <img src="//a.impactradius-go.com/display-ad/19272-1997635" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997635/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://aligracehair.sjv.io/c/5597632/2135415/19272" target="_top" id="2135415">
  <img src="//a.impactradius-go.com/display-ad/19272-2135415" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135415/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135352/19272" target="_top" id="2135352">
  <img src="//a.impactradius-go.com/display-ad/19272-2135352" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135352/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Use System Restore

 System Restore is an excellent utility baked into Windows that helps you fix issues in one go. It will roll back your PC to an earlier state when there were no abrupt issues with your PC.

 Check our guide on [how to use System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) and revert to an earlier PC state without losing your personal files. However, all the installed apps and updates after the restore point will be removed, if you adopt this route.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1972698/19272" target="_top" id="1972698">
  <img src="//a.impactradius-go.com/display-ad/19272-1972698" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972698/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-mastering-live-broadcasts-obs-tips-for-youtube-and-twitch/"><u>[New] 2024 Approved Mastering Live Broadcasts OBS Tips for YouTube & Twitch</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-a-beginners-guide-to-quantum-hdr-systems/"><u>[New] A Beginner’s Guide to Quantum HDR Systems</u></a></li>
<li><a href="https://youtube-data.techidaily.com/he-definitive-guide-to-professional-level-youtube-video-edits-for-2024/"><u>[New] The Definitive Guide to Professional-Level YouTube Video Edits for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-10-speed-up-apps-for-mobile-music-and-podcasts/"><u>[Updated] 2024 Approved 10 Speed-Up Apps for Mobile Music and Podcasts</u></a></li>
<li><a href="https://win-community.techidaily.com/effective-strategies-how-to-securely-transfer-data-from-windows-server-2019-to-a-network-attached-storage/"><u>Effective Strategies: How to Securely Transfer Data From Windows Server 2019 to a Network-Attached Storage</u></a></li>
<li><a href="https://facebook.techidaily.com/freedom-of-expression-say-no-to-facebook-tagged-photos/"><u>Freedom of Expression: Say No to Facebook Tagged Photos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-effortlessly-overcome-steam-content-blocks/"><u>How to Effortlessly Overcome Steam Content Blocks</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/navigating-tiktok-image-and-description-upgrades/"><u>Navigating TikTok Image & Description Upgrades</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-level-up-your-video-editing-skills-6-must-know-adobe-premiere-secrets/"><u>New In 2024, Level Up Your Video Editing Skills 6 Must-Know Adobe Premiere Secrets</u></a></li>
<li><a href="https://win-solutions.techidaily.com/1722995560280-nier-replica-master-update-solved-launch-trouble-no-more/"><u>NieR Replica Master Update Solved: Launch Trouble No More</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-cannot-connect-problems-for-win-users/"><u>Overcoming Cannot Connect Problems for Win Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-sound-access-failure-with-audacity-windows-1011/"><u>Resolving Sound Access Failure with Audacity (Windows 10/11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-edthemes-on-your-windows-11/"><u>Streamline EdThemes on Your Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trim-down-gaming-pc-power-use-optimize-winwm-graphical-engine/"><u>Trim Down Gaming PC Power Use: Optimize WinWM Graphical Engine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-discord-fatal-javascript-glitch-in-windows-os/"><u>Troubleshooting Discord Fatal JavaScript Glitch in Windows OS</u></a></li>
</ul></div>

