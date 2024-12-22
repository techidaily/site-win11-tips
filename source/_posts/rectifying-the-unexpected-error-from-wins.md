---
title: Rectifying the Unexpected Error From WINS
date: 2024-12-19T03:19:26.904Z
updated: 2024-12-21T20:18:33.570Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Rectifying the Unexpected Error From WINS
excerpt: This Article Describes Rectifying the Unexpected Error From WINS
keywords: WINS Fix Guide,Error Resolution WinS,WINS Troubleshooting Tips,WinS Error Correction,Quick WINS Fix Steps,WinS Issue Rectification,Unforeseen Errors WinS
thumbnail: https://thmb.techidaily.com/1c9229fb0800113350dfae57f612d2aef9036646b6591dcd5ed2f832a16cf380.jpg
---

## Rectifying the Unexpected Error From WINS

 Windows Security incorporates the Microsoft Defender antivirus utility. However, some users can’t select to run Microsoft Defender scans because of an error message that says: “Unexpected error. Sorry, we ran into a problem.” That “Unexpected error” message pops up for some users when they select the**Virus & threat protection** tab in Windows Security.

 Consequently, the**Virus and threat protection tab** is inaccessible. That error means there’s an issue with the Windows antivirus tool. This is how you can resolve the “Unexpected error” issue.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Check for New Windows Updates

 First, check for and install available Windows patch updates. Microsoft releases many patches to update Microsoft Defender. So, a patch update could feasibly resolve a Windows Security bug. Our[guide to manually updating Windows](https://www.makeuseof.com/update-windows-manually/#:~:text=Press%20the%20Win%20%2B%20I%20hotkeys,the%20Check%20for%20updates%20button.) tells you how to check for and install new updates in Settings.

![The Reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-option.jpg)

## 2\. Run System File and Image Scans

 System file issues might be causing the “Unexpected error” on your PC. To check if that’s the case, run a System File Checker scan within the Command Prompt. Such a scan will repair the corrupted system files detected. Our guide on[utilizing the SFC tool on Windows](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to scan system files with that utility.

![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-sfc-scannow-command.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SDUPd69Qfls?si=uIGZG-riskwmVZYg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 It’s also recommended to run a Deployment Image Servicing and Management scan, which can resolve Windows system image issues. The System File Checker tool doesn’t work when there are issues with the system image. So, try executing this command before the SFC scan as well:

`Dism /Online /Cleanup-Image /RestoreHealth`

## 3\. Remove Third-Party Antivirus Software

 Do you have an alternative third-party antivirus tool installed on your PC? If so, then there’s a possibility that antivirus software is causing the issue by conflicting with Microsoft Defender. At least try turning off the third-party AV utility by right-clicking the system tray icon for the app and selecting a disable context menu setting.

 If disabling the third-party antivirus software works, you have two options. You can re-enable that antivirus software and utilize the alternative antivirus scanner it provides. Or you can completely uninstall the third-party antivirus software if you prefer Microsoft Defender. Our guide to removing Windows software includes numerous methods for uninstalling programs.

## 4\. Modify the Windows Defender Registry Key

 This registry tweak for modifying a**DisableAntiSpyware** DWORD is one of the most widely confirmed fixes for the “Unexpected error” issue. So, maybe this could the “Unexpected error” solution you’re looking for as well. To apply this potential fix, edit the registry as follows:

1. Open Run, input**regedit** , and click**OK** .
2. Erase the current registry path and input this registry key location inside the address box:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender`
3. You can skip through to step five if the Windows Defender key includes a**DisableAntiSpyware** DWORD. However, users who can’t see that DWORD will need to right-click the**Windows Defender** key and select**New** \>**DWORD** .  
![The New and Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-new-key-options.jpg)
4. Type**DisableAntiSpyware** in the DWORD’s text box.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/e4Nt2xXXtmE?si=CtKwFry4b0AJXnaN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Double-click the**DisableAntiSpyware** DWORD to access its**Value** box.
6. Input**0** in the data box if that’s not the current value set.  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-edit-dword-window.jpg)
7. Select**OK** to confirm the value for the DWORD.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Reset the Windows Security App

 Resetting Windows Security is worth trying whenever that app isn’t working right. In this case, something is up with the antivirus component of that app. You can reset that app within Settings or by executing a PowerShell command. Our article about[resetting Windows Security](https://www.makeuseof.com/windows-11-reset-windows-security/) tells you how to apply this potential resolution in three different ways.

![The Reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AcAYRX0cwwA?si=DxqWU39vqksZbe1s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Run a Malwarebytes Scan

 The “Unexpected error” can sometimes be caused by malware targeting Windows Security. Yet, users can’t purge malware with Windows Security because of the error. So, try running a scan with the freeware Malwarebytes version. Some users have said utilizing that software helped them resolve the “Unexpected error” issue. This is how you can run a Malwarebytes scan:

1. Open the[Malwarebytes](https://www.anrdoezrs.net/links/7251228/type/dlg/sid/UUmuoUeUpU2024249/https://www.malwarebytes.com/) website.
2. Click the**Free Download** button.
3. Activate Explorer by holding the**Windows** logo key and pressing**E** .
4. Go to the folder location containing the Malwarebytes setup file.
5. Double-click the**MBSetup.exe** file.
6. Click**Install** to add Malwarebytes to a default directory path.  
![The Install button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-button-for-malwarebytes.jpg)
7. Select**Me or my family** (for personal use) at the production selection step and click**Next** .
8. Click**Skip this for now** if you prefer not to install the additional Malwarebytes Browser Guard software.  
![The Skip this for now option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/skip-this-for-now-option.jpg)
9. Select**Done** to finish.

10. Malwarebytes will then open automatically. Select**Get started** \>**Maybe later** within the Malwarebytes window.
11. Click**Get started** again.
12. Select Malwarebytes’**Scan** option.  
![The Scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/scan-option.jpg)
13. Press the**Quarantine** button after the scan.

 If this potential resolution works, you can keep Malwarebytes installed for manual scanning. It’s a 14-day trial of the Premium version, and the real-time protection will only last a couple of weeks. However, you can disable the Malwarebytes protection to ensure it doesn’t conflict with Microsoft Defender by right-clicking the utility’s system tray icon and deselecting the**Malware** ,**Ransomware** ,**Exploit** , and**Web Protection** options.

 The Microsoft Safety Scanner is an alternative to Malwarebytes you can run a malware scan with as well. However, that’s only a temporary scanning utility that expires after 10 days. You can download that utility from this[Microsoft page](https://learn.microsoft.com/en-us/microsoft-365/security/intelligence/safety-scanner-download?view=o365-worldwide) . Check out[our Microsoft Safety Scanner guide](https://www.makeuseof.com/microsoft-safety-scanner-guide/) for details about to purge malware with that tool.

## 7\. Check the "Turn Off Microsoft Defender Antivirus" Group Policy Setting

 If you’re a Windows Pro or Enterprise user, check that the the**Turn Off Microsoft Defender Antivirus** policy isn’t enabled in Group Policy. You can check that policy in the following steps:

1. [Open Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) by pressing the**Windows** logo +**S** hotkey, entering**gpedit.msc** in the search box, and selecting the**gpedit.msc** result.
2. Then navigate to this policy location in Group Policy’s sidebar:  
`Computer Configuration\Administrative Templates\Windows Components\Microsoft Defender Antivirus`
3. Next, double-click**Turn Off Microsoft Defender Antivirus** to check that policy.  
![The Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/microsoft-defender-antivirus-policy-settings.jpg)
4. Click**Not Configured** if that policy is set to**Enabled** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/td3ojuzhloY?si=N_maQNiJWrJp7XZl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![The Turn Off Microsoft Defender Antivirus policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-microsoft-defender-antivirus.jpg)
5. Select the policy’s**Apply** and**OK** options.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ASUEYpqSP5E?si=0KOZxrTVexTuUkRn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 8\. Reset Windows or Perform an In-Place Upgrade

 Resetting Windows is a troubleshooting method that restores the platform to a default (factory) configuration. The Reset this PC tool gives you a simple way to reinstall the platform and preserve user files, but you’ll need to reinstall apps.

[Applying a Windows reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) might resolve some deeper system issues causing the “Unexpected error” issue. However, it’s only advised to do so if none of the other potential solutions suggested here work.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-this-pc-tool.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1KKovVi9epE?si=EF7KA7b4KsEpWA-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 An in-place upgrade is an alternative troubleshooting method to resetting Windows. Performing an in-place upgrade will reinstall Windows by installing the latest build version. So, it’s like a reset, but the advantage is that an in-place upgrade preserves the apps you’ve installed. This guide to[performing an in-place upgrade on Windows](https://www.makeuseof.com/in-place-upgrade-windows-11/) provides full instructions for upgrading Windows 11 in such a way.

 However, you could feasibly upgrade to a new Windows version via Settings. Open**Windows Update** in the Settings app to see if there’s a version upgrade available. If so, select to upgrade to the latest Windows build from there.

## Run a Scan With Windows Security Again

 You’ll probably be able to access the antivirus-scanning options in Windows Security again after applying the potential solutions covered here. So, try applying all those potential “Unexpected error” resolutions in the order specified to find one that works on your Windows PC. You can also contact the[Microsoft Windows support service](https://support.microsoft.com/en-us/home/contact?SourceApp=smc2&ContactUsExperienceEntryPointAssetId=Google) for further assistance but give the potential fixes outlined here a try first.

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
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-primepickings-top-twitters-and-top-viewers-favorites/"><u>[New] 2024 Approved PrimePickings Top Twitters & Top Viewers’ Favorites</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/n-2024-best-recording-equipment-for-creating-youtube-masterpieces/"><u>[New] In 2024, Best Recording Equipment For Creating YouTube Masterpieces</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-in-2024-affordable-wonders-in-virtual-reality-headsets-from-china/"><u>[Updated] In 2024, Affordable Wonders in Virtual Reality Headsets From China</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-superior-sonic-collectors-for-seminars-for-2024/"><u>[Updated] Superior Sonic Collectors for Seminars for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/accelerate-yt-growth-strategies-for-1kplus-subscribers-for-2024/"><u>Accelerate YT Growth Strategies for 1K+ Subscribers for 2024</u></a></li>
<li><a href="https://android-location.techidaily.com/easy-ways-to-manage-your-xiaomi-13t-location-settings-drfone-by-drfone-virtual/"><u>Easy Ways to Manage Your Xiaomi 13T Location Settings | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-pc-not-valid-warning-in-windows-os/"><u>Eliminating 'PC Not Valid' Warning in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-cure-the-missing-msvcr110dll-problem/"><u>How to Cure the Missing msvcr110.dll Problem</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-free-location-spoofers-to-fake-gps-location-on-your-vivo-y100-5g-drfone-by-drfone-virtual/"><u>In 2024, 10 Free Location Spoofers to Fake GPS Location on your Vivo Y100 5G | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-mastering-sierras-cloud-storage-for-effortless-documentdrive-access/"><u>In 2024, Mastering Sierra's Cloud Storage for Effortless Document/Drive Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-microsoft-store-fault-code-0x80073cf3-on-win11/"><u>Mending Microsoft Store Fault Code 0X80073cf3 on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simple-steps-to-standardize-users-on-win11/"><u>Simple Steps to Standardize Users on Win11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/strategies-and-techniques-in-documentary-scriptwriting/"><u>Strategies and Techniques in Documentary Scriptwriting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-customizing-windows-11-notepad/"><u>The Ultimate Guide to Customizing Windows 11 Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-troubleshooting-systemsettingsexe-in-win11/"><u>Tips for Troubleshooting SystemSettings.exe in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-update-fiasco-defeat-0x800736cc/"><u>Troubleshooting Windows Update Fiasco: Defeat 0X800736CC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-filesystems-top-6-techniques-to-extract-file-and-folder-paths-from-windows-11/"><u>Unlocking Filesystems: Top 6 Techniques to Extract File & Folder Paths From Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-terminal-reboot-return-to-standard/"><u>Win11 Terminal Reboot: Return To Standard</u></a></li>
<li><a href="https://extra-resources.techidaily.com/winning-at-love-one-swipe-at-a-time-top-tips-for-bold-biographies/"><u>Winning at Love, One Swipe at a Time Top Tips for Bold Biographies</u></a></li>
</ul></div>

