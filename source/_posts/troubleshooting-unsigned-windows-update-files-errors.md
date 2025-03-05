---
title: Troubleshooting Unsigned Windows Update Files Errors
date: 2025-03-01T19:00:53.751Z
updated: 2025-03-05T02:43:41.614Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Unsigned Windows Update Files Errors
excerpt: This Article Describes Troubleshooting Unsigned Windows Update Files Errors
keywords: Windows Update Fix Guide,Update Error Resolution,Windows Security Patches,Signed Update Troubleshoot,Update File Validation,Unsigned Error Remedy,Windows Updates Support
thumbnail: https://thmb.techidaily.com/0171a03fcfaa97ca9a37fd62265ffdf540832c9ac080e870fc5542fba83032d5.jpg
---

## Troubleshooting Unsigned Windows Update Files Errors

 Users frequently report Windows 11/10 update errors on software support forums. One such update issue reported is an error message that says, “Some update files aren’t signed.” Some users see that error message appear within Settings’ Windows Update tab when trying to update Windows.

 Windows updates fail to install when this issue occurs. This error usually includes either a 0x800b0109 or 0x800b0100 code after its message. This is how you can resolve the “Some update files aren’t signed” error 0x800b0109 on a Windows 11/10 PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Utilize the Windows Update Troubleshooter

 The Windows Update troubleshooting tool is there to help you fix any issues encountered when trying to update Windows 11/10\. That troubleshooter doesn’t necessarily fix every update error, but it can at least resolve some issues.

 So, utilizing that troubleshooter is always worth a try, which you can access in Settings as covered within this guide to [running any troubleshooter on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/).

![The Windows Update troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-update-troubleshooter.jpg)

## 2\. Run Deployment Imaging and System File Scans

 System file corruption is among the [most common reasons for Windows update errors](https://www.makeuseof.com/reasons-why-windows-updates-fail/). For that reason, running a System File Checker scan to address system file corruption is a recommended troubleshooting method for error 0x800b0109\.

 It’s also advisable to utilize the Deployment Imaging and Servicing Management to repair possible Windows image corruption.

 Both Deployment Imaging and System File Checker are Command Prompt tools. You can run them by inputting and executing two commands within the Command Prompt. Our article on [repairing corrupted Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) includes instructions on how to utilize the SFC and DISM command-line tools.

![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-sfc-scannow.jpg)

## 3\. Check the Windows Update and BITS Services Are Enabled

 Windows Updates and Background Intelligent Transfer Service (BITS) are two services that need to be enabled for updates. So, check those services are correctly set like this:

1. Simultaneously press the **Windows** logo + **S** keys on your keyboard.
2. Enter the search phrase "services" to find the app with a matching title.
3. Click on **Services** inside the search results.
4. Double-click **Windows Update** to access settings for that service.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/services-window.jpg)
5. Set the **Startup type** setting to the **Automatic** option.  

![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/startup-type-drop-down-menu.jpg)
6. Click **Start** (inside the properties windows) to run the Windows Update service.

7. Save the settings by pressing the **Apply** and **OK** buttons.
8. Double-click the **Background Intelligent Transfer Service** to view its settings.
9. Select a **Manual** startup option.
10. Click the **Start** option for the BITS service if it’s stopped.
11. Then click on the **Apply** and **OK** options to set that service’s options.

 If you find both services to be already enabled and running, try restarting them. You can do so by right-clicking the BITS and Windows Update service names and selecting a **Restart** option on their context menus.

## 4\. Reset Components for Windows Updates

 Resetting components for Windows updates will completely refresh the catroot2 and SoftwareDistribution folders, which store update data. This troubleshooting method also reregisters all DLL files for important update services. Applying such a potential resolution can fix corrupted components causing error 0x800b0109\.

 To apply this possible error 0x800b0109 resolution, check out our article on [resetting Windows update components](https://www.makeuseof.com/reset-windows-update-components/). That guide includes a command-line and batch file method. Creating and running a batch file is the quicker and more straightforward way to reset Windows update components.

## 5\. Deactivate Third-Party Security Software

 A third-party security (antivirus) app can potentially conflict with Windows update processes. This can happen when the antivirus protection of a security app locks files needed by Windows Update. It’s not something that happens often, but temporarily disable any third-party antivirus protection on your PC just in case.

 Security apps typically include options for disabling antivirus protection on their system tray context menus. Right-click your security app’s icon in Windows 11’s system tray area to find and select its option for temporarily disabling the antivirus shield. Then, return to the Settings app to see if error 0x800b0109 still happens with the antivirus shield disabled.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

## 6\. Erase the Windows Update Key

 Deleting the Windows Update registry key is a potential resolution some users confirm to fix error 0x800b0109\. However, we always recommend [backing up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or saving a system restoration point before deleting registry keys.

 When you’ve done that, try deleting the Windows Update key like this:

1. Open Run, accessible by pressing **Windows** logo key + **R**, and type a **regedit** command into that accessory.
2. Select Run’s **OK** option to open the Registry Editor.
3. Next, clear the registry address bar and input this key path there:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\WindowsUpdate`
4. Right-click the WindowsUpdate registry key to select **Delete**.  
![The Delete context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-delete-option-1.jpg)
5. Click **Yes** when prompted for confirmation to delete the key.  

![The Confirm Key Delete prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-key-confirmation-1.jpg)

 Thereafter, it’s also recommended to restart the Windows Update and BITS services. To do so, open Services as covered in the first three steps of resolution three. Then, select the **Restart** context menu options for Windows Update and BITS.

## 7\. Try Downloading the Failed Update From Microsoft Update Catalog

 If error 0x800b0109 still isn’t fixed after applying the potential resolutions above, try going around it by manually downloading the affected update from [Microsoft Update Catalog](https://www.catalog.update.microsoft.com/Home.aspx). Then, you can install the update with an MSU file downloaded from there.

 You will first need to identify what update is failing as follows:

1. Simultaneously press your keyboard’s **Windows** logo + **I** keys to access Settings.
2. Click **Windows Update** (or **Update & Security**) in Settings.
3. Select **Update history** to view installed and failed updates.  
![The update history in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-history4.jpg)
4. Note down the KB code for your recently failed Windows update.

 Then, you can find and download that failed update on the Microsoft Update Catalog website. This article about [updating Windows manually](https://www.makeuseof.com/update-windows-manually/) includes instructions for utilizing the Microsoft Update Catalog.

## 8\. Apply an In-Place Windows Upgrade

 An in-place Windows upgrade is the last resort for fixing error 0x800b0109\. Applying this potential resolution will reinstall Windows on your PC with its latest ISO file. The installation of a fresh Windows copy will likely resolve other issues causing the 0x800b0109 update error that other potential solutions couldn’t fix.

 The good thing about an in-place upgrade is that it won’t eradicate your installed software or user files. This [how-to perform an in-place upgrade](https://www.makeuseof.com/in-place-upgrade-windows-11/) guide tells you how to apply this potential solution for Windows 11\. The steps are quite similar for Windows 10, but you’ll need to download its ISO with the Media Creation Tool available on this [Microsoft page](https://www.microsoft.com/en-gb/software-download/windows10).

![The Windows 10 Media Creation tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-10-setup-window.jpg)

## Get Windows Updated Again

 There isn’t a surefire way to fix error 0x800b0109 since there are varied possible reasons for that Windows 11/10 issue occurring. However, it’s likely at least one of the eight potential resolutions in this guide will fix that update issue on your PC.

 Some of the best third-party Windows repair tools might also be helpful for resolving the “Some update files aren’t signed” error.

 Windows updates fail to install when this issue occurs. This error usually includes either a 0x800b0109 or 0x800b0100 code after its message. This is how you can resolve the “Some update files aren’t signed” error 0x800b0109 on a Windows 11/10 PC.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-techniques.techidaily.com/new-gopro-karma-demystified-a-comprehensive-look/"><u>[New] GoPro Karma Demystified A Comprehensive Look</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-the-art-of-video-blending-using-modes-mastery/"><u>[New] In 2024, The Art of Video Blending Using Modes Mastery</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-speed-shots-and-stills-quicktime-techniques-for-samsung-users/"><u>[Updated] 2024 Approved Speed Shots & Stills Quicktime Techniques for Samsung Users</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-secrets-of-snapping-finding-missing-private-images/"><u>[Updated] Secrets of Snapping Finding Missing Private Images</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unearthing-the-skies-hubsan-h501x4-quad-drone-analysis/"><u>[Updated] Unearthing the Skies Hubsan H501X4 Quad Drone Analysis</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/amd-radeon-3450-driver-updates-made-simple-for-optimal-graphics-card-functioning/"><u>AMD Radeon 3450 Driver Updates Made Simple for Optimal Graphics Card Functioning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gateway-to-apps-in-windows-11-navigating-effortlessly/"><u>Gateway to Apps in Windows 11: Navigating Effortlessly</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-various-methods-to-transfer-pictures-from-apple-iphone-6-plus-to-pc-drfone-by-drfone-transfer-from-ios/"><u>In 2024, Various Methods to Transfer Pictures from Apple iPhone 6 Plus to PC | Dr.fone</u></a></li>
<li><a href="https://article-helps.techidaily.com/navigate-to-8-elite-free-3d-vids-software-companies-for-2024/"><u>Navigate to 8 Elite Free 3D Vids Software Companies for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-failure-mfc71udll-missing/"><u>Resolving Windows Failure: Mfc71u.dll Missing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-frozen-photoapp-win11-edition-photoshop-not-opening/"><u>Reviving Frozen PhotoApp, Win11 Edition (Photoshop) Not Opening</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-username-changes-in-the-latest-windows/"><u>Step-by-Step UserName Changes in the Latest Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-read-locked-windows-files-a-guide/"><u>Taming Read-Locked Windows Files: A Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-windows-odbc-management-toolkit/"><u>The Essential Windows ODBC Management Toolkit</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-car-locator-apps-for-motorola-razr-40-drfone-by-drfone-virtual-android/"><u>Top 5 Car Locator Apps for Motorola Razr 40 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-disk-control-explore-4-opening-steps-in-windows-disk-editor/"><u>Unlock Disk Control: Explore 4 Opening Steps in Windows Disk Editor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-stunning-graphics-with-driver-refresh-in-win1011/"><u>Unlock Stunning Graphics with Driver Refresh in WIN10/11</u></a></li>
</ul></div>

