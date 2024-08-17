---
title: Navigating Through Windows Security Faults & Fixes
date: 2024-08-16T01:42:51.865Z
updated: 2024-08-17T01:42:51.865Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Through Windows Security Faults & Fixes
excerpt: This Article Describes Navigating Through Windows Security Faults & Fixes
keywords: Windows Security Checkup,Fixing Windows Errors,Secure Windows Repair,Windows Guard Update,Error Resolution Windows,Windows Safety Patch,Stable Windows Solution
thumbnail: https://thmb.techidaily.com/8f8ccde6a37994fbb46b3e6f7b726055988d6d039d40b57440a0147cb4ded38c.jpg
---

## Navigating Through Windows Security Faults & Fixes

 Windows Security incorporates the Microsoft Defender antivirus utility. However, some users can’t select to run Microsoft Defender scans because of an error message that says: “Unexpected error. Sorry, we ran into a problem.” That “Unexpected error” message pops up for some users when they select the**Virus & threat protection** tab in Windows Security.

 Consequently, the**Virus and threat protection tab** is inaccessible. That error means there’s an issue with the Windows antivirus tool. This is how you can resolve the “Unexpected error” issue.

## 1\. Check for New Windows Updates

 First, check for and install available Windows patch updates. Microsoft releases many patches to update Microsoft Defender. So, a patch update could feasibly resolve a Windows Security bug. Our [guide to manually updating Windows](https://www.makeuseof.com/update-windows-manually/#:~:text=Press%20the%20Win%20%2B%20I%20hotkeys,the%20Check%20for%20updates%20button.) tells you how to check for and install new updates in Settings.

![The Reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-option.jpg)

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Run System File and Image Scans

 System file issues might be causing the “Unexpected error” on your PC. To check if that’s the case, run a System File Checker scan within the Command Prompt. Such a scan will repair the corrupted system files detected. Our guide on [utilizing the SFC tool on Windows](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to scan system files with that utility.

![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-sfc-scannow-command.jpg)
<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 It’s also recommended to run a Deployment Image Servicing and Management scan, which can resolve Windows system image issues. The System File Checker tool doesn’t work when there are issues with the system image. So, try executing this command before the SFC scan as well:

`Dism /Online /Cleanup-Image /RestoreHealth`

## 3\. Remove Third-Party Antivirus Software

 Do you have an alternative third-party antivirus tool installed on your PC? If so, then there’s a possibility that antivirus software is causing the issue by conflicting with Microsoft Defender. At least try turning off the third-party AV utility by right-clicking the system tray icon for the app and selecting a disable context menu setting.

 If disabling the third-party antivirus software works, you have two options. You can re-enable that antivirus software and utilize the alternative antivirus scanner it provides. Or you can completely uninstall the third-party antivirus software if you prefer Microsoft Defender. Our guide to removing Windows software includes numerous methods for uninstalling programs.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## 4\. Modify the Windows Defender Registry Key

 This registry tweak for modifying a**DisableAntiSpyware** DWORD is one of the most widely confirmed fixes for the “Unexpected error” issue. So, maybe this could the “Unexpected error” solution you’re looking for as well. To apply this potential fix, edit the registry as follows:

1. Open Run, input**regedit** , and click**OK** .
2. Erase the current registry path and input this registry key location inside the address box:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender`
3. You can skip through to step five if the Windows Defender key includes a**DisableAntiSpyware** DWORD. However, users who can’t see that DWORD will need to right-click the**Windows Defender** key and select**New** \>**DWORD** .  
![The New and Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-new-key-options.jpg)
4. Type**DisableAntiSpyware** in the DWORD’s text box.
5. Double-click the**DisableAntiSpyware** DWORD to access its**Value** box.
6. Input**0** in the data box if that’s not the current value set.  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-edit-dword-window.jpg)
7. Select**OK** to confirm the value for the DWORD.

## 5\. Reset the Windows Security App

 Resetting Windows Security is worth trying whenever that app isn’t working right. In this case, something is up with the antivirus component of that app. You can reset that app within Settings or by executing a PowerShell command. Our article about [resetting Windows Security](https://www.makeuseof.com/windows-11-reset-windows-security/) tells you how to apply this potential resolution in three different ways.

![The Reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-option.jpg)

## 6\. Run a Malwarebytes Scan

 The “Unexpected error” can sometimes be caused by malware targeting Windows Security. Yet, users can’t purge malware with Windows Security because of the error. So, try running a scan with the freeware Malwarebytes version. Some users have said utilizing that software helped them resolve the “Unexpected error” issue. This is how you can run a Malwarebytes scan:

1. Open the [Malwarebytes](https://www.anrdoezrs.net/links/7251228/type/dlg/sid/UUmuoUeUpU2024249/https://www.malwarebytes.com/) website.
2. Click the**Free Download** button.
3. Activate Explorer by holding the**Windows** logo key and pressing**E** .
4. Go to the folder location containing the Malwarebytes setup file.
5. Double-click the**MBSetup.exe** file.
6. Click**Install** to add Malwarebytes to a default directory path.  
![The Install button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-button-for-malwarebytes.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
7. Select**Me or my family** (for personal use) at the production selection step and click**Next** .
8. Click**Skip this for now** if you prefer not to install the additional Malwarebytes Browser Guard software.  
![The Skip this for now option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/skip-this-for-now-option.jpg)
<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
9. Select**Done** to finish.
10. Malwarebytes will then open automatically. Select**Get started** \>**Maybe later** within the Malwarebytes window.
11. Click**Get started** again.
12. Select Malwarebytes’**Scan** option.  
![The Scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/scan-option.jpg)
13. Press the**Quarantine** button after the scan.

 If this potential resolution works, you can keep Malwarebytes installed for manual scanning. It’s a 14-day trial of the Premium version, and the real-time protection will only last a couple of weeks. However, you can disable the Malwarebytes protection to ensure it doesn’t conflict with Microsoft Defender by right-clicking the utility’s system tray icon and deselecting the**Malware** ,**Ransomware** ,**Exploit** , and**Web Protection** options.

 The Microsoft Safety Scanner is an alternative to Malwarebytes you can run a malware scan with as well. However, that’s only a temporary scanning utility that expires after 10 days. You can download that utility from this [Microsoft page](https://learn.microsoft.com/en-us/microsoft-365/security/intelligence/safety-scanner-download?view=o365-worldwide) . Check out [our Microsoft Safety Scanner guide](https://www.makeuseof.com/microsoft-safety-scanner-guide/) for details about to purge malware with that tool.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
## 7\. Check the "Turn Off Microsoft Defender Antivirus" Group Policy Setting

 If you’re a Windows Pro or Enterprise user, check that the the**Turn Off Microsoft Defender Antivirus** policy isn’t enabled in Group Policy. You can check that policy in the following steps:

1. [Open Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) by pressing the**Windows** logo +**S** hotkey, entering**gpedit.msc** in the search box, and selecting the**gpedit.msc** result.
2. Then navigate to this policy location in Group Policy’s sidebar:  
`Computer Configuration\Administrative Templates\Windows Components\Microsoft Defender Antivirus`
3. Next, double-click**Turn Off Microsoft Defender Antivirus** to check that policy.  
![The Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/microsoft-defender-antivirus-policy-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
4. Click**Not Configured** if that policy is set to**Enabled** .  
![The Turn Off Microsoft Defender Antivirus policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-microsoft-defender-antivirus.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
5. Select the policy’s**Apply** and**OK** options.

## 8\. Reset Windows or Perform an In-Place Upgrade

 Resetting Windows is a troubleshooting method that restores the platform to a default (factory) configuration. The Reset this PC tool gives you a simple way to reinstall the platform and preserve user files, but you’ll need to reinstall apps.

[Applying a Windows reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) might resolve some deeper system issues causing the “Unexpected error” issue. However, it’s only advised to do so if none of the other potential solutions suggested here work.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-this-pc-tool.jpg)

 An in-place upgrade is an alternative troubleshooting method to resetting Windows. Performing an in-place upgrade will reinstall Windows by installing the latest build version. So, it’s like a reset, but the advantage is that an in-place upgrade preserves the apps you’ve installed. This guide to [performing an in-place upgrade on Windows](https://www.makeuseof.com/in-place-upgrade-windows-11/) provides full instructions for upgrading Windows 11 in such a way.

 However, you could feasibly upgrade to a new Windows version via Settings. Open**Windows Update** in the Settings app to see if there’s a version upgrade available. If so, select to upgrade to the latest Windows build from there.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
## Run a Scan With Windows Security Again

 You’ll probably be able to access the antivirus-scanning options in Windows Security again after applying the potential solutions covered here. So, try applying all those potential “Unexpected error” resolutions in the order specified to find one that works on your Windows PC. You can also contact the [Microsoft Windows support service](https://support.microsoft.com/en-us/home/contact?SourceApp=smc2&ContactUsExperienceEntryPointAssetId=Google) for further assistance but give the potential fixes outlined here a try first.

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
<li><a href="https://youtube-zero.techidaily.com/024-approved-mapping-out-the-next-wave-of-social-media-graphs/"><u>[New] 2024 Approved  Mapping Out the Next Wave of Social Media Graphs</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-apowersofts-place-in-the-screen-capture-market/"><u>[New] Apowersoft's Place in the Screen Capture Market</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-enhance-social-media-presence-by-saving-webcam-videos-via-vlc-for-2024/"><u>[New] Enhance Social Media Presence by Saving Webcam Videos via VLC for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-must-have-add-ons-for-your-gopro-adventure/"><u>[New] Must-Have Add-Ons for Your GoPro Adventure</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-step-by-step-gopro-4k-editing-basics/"><u>[New] Step-by-Step GoPro 4K Editing Basics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-audacity-audio-inconsistency-in-windows-1111/"><u>Correcting Audacity Audio Inconsistency in Windows 11/11</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/detailed-review-of-doctorsim-unlock-service-for-iphone-15-plus-by-drfone-ios/"><u>Detailed Review of doctorSIM Unlock Service For iPhone 15 Plus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-peasy-double-click-android-files-in-win-11/"><u>Easy-Peasy: Double-Click Android Files in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-windows-experience-with-these-2023-microsoft-store-community-choice-winning-apps/"><u>Elevate Your Windows Experience With These 2023 Microsoft Store Community Choice Winning Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-windows-security-bypassing-faulty-pins-easily/"><u>Enhance Windows Security: Bypassing Faulty PINs Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-sticky-notes-dont-get-lost/"><u>Ensuring Sticky Notes Don't Get Lost</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-virtualbox-v70-installation-for-windows-11-users/"><u>Essential Guide: VirtualBox v7.0 Installation for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-routes-to-windows-recovery-toolkit/"><u>Essential Routes to Windows Recovery Toolkit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-dodge-repeated-network-logon-error-messages-on-windows/"><u>How to Dodge Repeated Network Logon Error Messages on Windows</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-full-guide-to-fix-itoolab-anygo-not-working-on-oppo-reno-11-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Fix iToolab AnyGO Not Working On Oppo Reno 11 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-mastering-lock-screen-settings-how-to-enable-and-disable-on-samsung-galaxy-a05-by-drfone-android/"><u>In 2024, Mastering Lock Screen Settings How to Enable and Disable on Samsung Galaxy A05</u></a></li>
<li><a href="https://win-amazing.techidaily.com/incorerpt-quotes-from-siegels-research-as-titles-for-different-sections-of-the-assembly-instructions-eg-the-key-here-was/"><u>Incorerpt Quotes From Siegel's Research as Titles for Different Sections of the Assembly Instructions (E.g., The Key Here Was...).</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jumpstart-stalled-excel-workflow-on-windows-devices/"><u>Jumpstart Stalled Excel Workflow on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-saved-gamer-tactics-with-launcher-backups/"><u>Mastering Saved Gamer Tactics with Launcher Backups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-rebooting-indexed-databases/"><u>Mastering the Art of Rebooting Indexed Databases</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-overloaded-system-by-controlling-processes/"><u>Resolving Overloaded System by Controlling Processes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-enhance-visibility-of-webcam-usage-on-win11/"><u>Steps to Enhance Visibility of Webcam Usage on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-fixing-token-misrepresentation-issues/"><u>Strategies for Fixing “Token Misrepresentation” Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-retro-arc-of-gaming-shading-techniques-for-ancient-artifacts/"><u>The Retro Arc of Gaming: Shading Techniques for Ancient Artifacts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-windows-guide-to-fast-clickers/"><u>The Ultimate Windows Guide to Fast Clickers</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-8-chromium-enhancers-powered-by-artificial-intelligence/"><u>Top 8 Chromium Enhancers Powered by Artificial Intelligence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-imminent-windows-licensing-warning/"><u>Troubleshooting Imminent Windows Licensing Warning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-exe-files-on-your-pc-no-more-issues/"><u>Unlock EXE Files on Your PC, No More Issues!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-key-beware-the-subtle-dangers-of-discounts/"><u>Windows Key Beware: The Subtle Dangers of Discounts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-renewal-methods-for-driver-replacement-and-update/"><u>Windows Renewal: Methods for Driver Replacement and Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-pairings-4-innovative-windows-webp-viewer-apps/"><u>Winning Pairings: 4 Innovative Windows WebP Viewer Apps</u></a></li>
</ul></div>
