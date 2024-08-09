---
title: Tackling Insufficient Rights Error During Windows Installation
date: 2024-08-08T11:00:30.788Z
updated: 2024-08-09T11:00:30.788Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling Insufficient Rights Error During Windows Installation
excerpt: This Article Describes Tackling Insufficient Rights Error During Windows Installation
keywords: WinErrorInstallRights,InstallerRightsIssue,WindowsSetupAccessError,AccessRightFailWindows,InstallationRightFailure,WindowsInstallInsufficient,RightsErrorDuringInstall
thumbnail: https://thmb.techidaily.com/d72c9b0ad235ae2e33438a2833486adc17771826c6a96da1aa4105529dabc652.jpg
---

## Tackling Insufficient Rights Error During Windows Installation

 Users report Windows software installation errors of various kinds on support forums. Some of those reports have been about an error message that says, “The installer has insufficient privileges to access this directory.” That error message pops up on some users’ Windows 11/10 PCs when they try to install desktop programs with setup files.

 The result of this installation error is the same as most others. Users can’t install the software packages they need to when it happens. This is how you can fix the “installer has insufficient privileges” error on a Windows 11/10 PC.

## 1\. Run the Affected Software’s Setup File With Admin Rights

 Running the setup file for an affected program with administrator rights is perhaps the simplest of potential fixes for the “installer has insufficient privileges” error.

 A few users say that’s all they needed to do to fix the “installer has insufficient privileges” error. So, try right-clicking the software’s installer file and selecting **Run as administrator**.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/run-as-administrator-option.jpg)

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Unblock the Setup File

 In addition, check if the installer file is blocked before running it. To do that, right-click the program’s setup file and select **Properties**.

 If you can see an **Unblock** option on the **General** tab, deselect the checkbox and select **Apply**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
## 3\. Take Ownership of the Software’s Installation Directory

 One of the more widely confirmed solutions for fixing the “installer has insufficient privileges” error is to take ownership of the installation directory for the affected software.

 The “installer has sufficient privileges” error message specifies the path of the directory selected to install the software. Take ownership of the second to last folder of that path. The last folder is the one created during the installation that won’t currently exist on your PC.

 Alternatively, you can also apply this potential solution by manually creating the folder specified within the error message that doesn’t currently exist. Keep the error message open and create the last folder in the path. Then take ownership of the last folder in the installation path specified and click **Retry** within the error message.

 You can take ownership of a folder manually or by adding a new context menu option that does the job. This guide about [taking ownership of folders in Windows 11](https://www.makeuseof.com/windows-10-11-own-folder/) includes full instructions for both methods. It’s more straightforward to apply this potential solution by adding a **Take Ownership** option to the context menu with Winaero Tweaker.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
![The Take Ownership option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/take-ownership-option.jpg)

## 4\. Try Installing it in a Different Folder

 You might be able to bypass the “installer has insufficient privileges” error by selecting to install the software in a different directory. Many users install software packages in the Program Files folder. So, try selecting to install a program at a completely different folder path from the one specified in the error message.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Start or Restart Windows Installer

 Installation issues can arise because of Windows Installer service issues. Or that service might not even be running. So, check that service and either start or restart it depending on whether it’s running or not. You can start or restart Windows Installer like this:

1. [Open Services](https://www.makeuseof.com/windows-11-open-services-app/), an app you can access by pressing the **Windows** logo + **R** hotkey and inputting a **service.msc** command.
2. Right-click Windows Installer and select **Start** if that service isn’t on and running.  
![windows installer option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-installer-option.jpg)
3. If Windows Installer is running, select its **Restart** context menu option.

 Alternatively, you can double-click the **Windows Installer** service to view its properties window and restart it from there. Click **Start** if the service is already stopped, or, select **Stop > Start** to restart.

## 6\. Disable UAC Before Installing

 User Account Control is one of the security features that can generate installation issues when set to its higher levels. Turn off UAC before attempting to install affected software to see if that resolves the “installer has insufficient privileges” error. Check out this guide about [disabling User Account Control](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) for details about how to turn off UAC.

![The Never notify option in UAC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/never-notify-option.jpg)

## 7\. Disable All User Account Control Policy Settings

 If you’re a Windows Pro or Enterprise user, you can disable all UAC security settings that might be causing this error by restricting software installation.

 The Group Policy Editor tool in Windows Pro and Enterprise editions enables users to disable more User Account Control settings. You can turn off all UAC policy settings with Group Policy Editor like this:

1. [Open the Group Policy Editor tool](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and double-click **Computer Configuration** in its sidebar.
2. Then double-click **Windows Settings** \> **Security Settings** \> **Local Policies** \> **Security Options** to access UAC policy settings.
3. Double-click **User Account Control: Admin Approval Mode** to bring up that policy setting window.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
![The UAP security policy settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/security-options.jpg)
4. Select **Disabled** to turn off that policy setting.
5. Click **Apply** \> **OK** to save the policy setting you’ve selected.  
<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Enabled radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-enabled-radio-button.jpg)

 Once done, repeat steps three to five above for all the User Account Control policy settings. Exit Group Policy Editor and restart your PC after disabling all UAC policy settings.

## 8\. Turn Off Third-Party Security Apps

 If you’ve installed a third-party security app, such as antivirus or firewall software, that could be a possible cause for the “installer has insufficient privileges” error on your PC.

 Third-party antivirus tools have settings that can restrict or block the installation of suspicious programs when enabled. That’s more likely to happen when you’re trying to install unsigned software, which antivirus apps sometimes flag.

 You can prevent potential security app blocks when installing programs by temporarily disabling their antivirus shields.

 To find an option for disabling your antivirus app’s shield, right-click its system tray icon; select a setting to turn off your antivirus for a while on the right-click context menu that opens. Then have a go at installing affected software packages again with the antivirus shield disabled.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
## 9\. Try Installing Software After Clean Booting

 Clean booting means disabling all third-party apps and services that start with Windows. This troubleshooting method can prevent software conflicts by eliminating unneeded apps and services running in the background. In this case, a clean boot might disable an app or service that’s hindering the software installation process.

 We have a detailed guide on [performing a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/) explaining how you can disable the startup items with System Configuration and Task Manager. Select to restart your PC after you’ve set a clean boot configuration. Install the software you need after restarting to see if the clean booting has made any difference.

![The Services tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-services-tab.jpg)

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 10\. Uninstall Older Software Versions

 The “installer has insufficient privileges” has been reported to occur by users trying to install new versions of software already on their PCs.

 If there’s an older version of the software you can’t install already on your PC, then try uninstalling the preceding version first. This guide on [uninstalling software in Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) includes various methods for removing programs.

![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-uninstall-option.jpg)

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
## Get Your Windows 11/10 Software Installed

 The possible fixes covered here will probably resolve the “installer has insufficient privileges” Windows error in most cases but aren’t necessarily guaranteed.

 Resolution three, taking ownership of the installation directory, is the most widely confirmed solution. So, this error is usually a privilege (permission) issue for installing software, which the potential resolutions above will likely address.

 The result of this installation error is the same as most others. Users can’t install the software packages they need to when it happens. This is how you can fix the “installer has insufficient privileges” error on a Windows 11/10 PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-in-depth-analysis-of-vidmas-recording-capabilities/"><u>[New] 2024 Approved  In-Depth Analysis of Vidma's Recording Capabilities</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-xchange-your-thoughts-on-better-alternatives/"><u>[New] 2024 Approved  XChange Your Thoughts on Better Alternatives</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-youtubes-secret-to-flawless-video-spin-guide-and-tips/"><u>[New] 2024 Approved  YouTube's Secret to Flawless Video Spin (Guide & Tips)</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-dive-into-asmr-its-positive-effects-explored/"><u>[New] Dive Into ASMR  Its Positive Effects Explored</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-26-metaverse-milestones-a-journey-into-virtual-realms/"><u>[Updated] 26 Metaverse Milestones  A Journey Into Virtual Realms</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-carryminati-unmasked-the-monetary-milestones/"><u>2024 Approved  CarryMinati Unmasked  The Monetary Milestones</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-fb-video-extraction-for-desktops-and-phones/"><u>2024 Approved  FB Video Extraction for Desktops & Phones</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-windows-and-mac-recording-tactics-finding-your-perfect-match-freepaid/"><u>2024 Approved  Windows & Mac Recording Tactics - Finding Your Perfect Match (Free/Paid)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-get-the-most-out-of-the-windows-11-taskbar/"><u>7 Ways to Get the Most Out Of the Windows 11 Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-lsassexe-component-not-found-error-in-windows/"><u>Addressing lsass.exe Component Not Found Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/becoming-a-storage-strategy-expert-with-windows-diskusage-commands-mastery/"><u>Becoming a Storage Strategy Expert with Windows' DiskUsage Commands Mastery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-barriers-the-role-of-copilot-key-in-windows-11/"><u>Breaking Down Barriers: The Role of Copilot Key in Windows 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/bypassing-google-account-with-vnrom-bypass-for-vivo-y77t-by-drfone-android/"><u>Bypassing Google Account With vnROM Bypass For Vivo Y77t</u></a></li>
<li><a href="https://win11-tips.techidaily.com/curing-windows-11-unrecognized-devices/"><u>Curing Windows 11 Unrecognized Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-mechanics-behind-failed-usb-attachment-in-virtualbox/"><u>Decoding the Mechanics Behind Failed USB Attachment in VirtualBox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delving-into-upcoming-changes-with-windows-11-version-22h2/"><u>Delving Into Upcoming Changes with Windows 11 Version 22H2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/designing-the-ui-for-windows-11s-self-update-checker/"><u>Designing the UI for Windows 11'S Self-Update Checker</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-computer-experience-running-task-manager-as-admin-on-win11/"><u>Elevate Your Computer Experience: Running Task Manager as Admin on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-compliance-with-insider-editions/"><u>Ensuring Compliance with Insider Editions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-routes-to-access-windows-11-display-settings-in-10-steps/"><u>Essential Routes to Access Windows 11 Display Settings in 10 Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-to-resynchronize-google-drive-on-desktop-os/"><u>Essential Steps to Resynchronize Google Drive on Desktop OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-find-and-change-the-subnet-mask-in-windows-11/"><u>How to Find and Change the Subnet Mask in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-a-persistent-enter-network-credentials-message-on-windows/"><u>How to Fix a Persistent Enter Network Credentials Message on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-suppress-gaming-suggestions-in-windows-11-ui/"><u>How to Suppress Gaming Suggestions in Windows 11 UI</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-3-effective-ways-to-bypass-activation-lock-from-iphone-xr-by-drfone-ios/"><u>In 2024, 3 Effective Ways to Bypass Activation Lock from iPhone XR</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-delete-gmail-account-withwithout-password-on-xiaomi-mix-fold-3-by-drfone-android/"><u>In 2024, Delete Gmail Account With/Without Password On Xiaomi Mix Fold 3</u></a></li>
<li><a href="https://extra-skills.techidaily.com/journey-beyond-boundaries-secure-this-top-7-metavue-tech-for-2024/"><u>Journey Beyond Boundaries - Secure This Top 7 Metavue Tech for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-windows-11-os-the-installation-of-outlook-preview-app/"><u>Leveraging Windows 11 OS: The Installation of Outlook Preview App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-swift-typing-techniques-with-powertoys/"><u>Master Swift Typing Techniques with PowerToys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-cc-errors-on-windows-10-a-step-by-step-guide/"><u>Mastering CC Errors on Windows 10: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-multi-screen-setup-on-windows-11/"><u>Mastering Multi-Screen Setup on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-print-control-in-windows-11-9-ways-short-version-max-48-chars/"><u>Navigating Print Control in Windows 11 (9 Ways) - Short Version (Max 48 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-0x80070570-error-in-windows-restoring-damaged-data/"><u>Overcoming 0X80070570 Error in Windows: Restoring Damaged Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-printer-connection-failsafes-in-windows/"><u>Overcoming Printer Connection Failsafes in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-control-of-your-windows-headset-mic/"><u>Regain Control of Your Windows Headset Mic</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-default-energy-management-in-windows-11/"><u>Regaining Default Energy Management in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-valorants-speech-issues-on-pc/"><u>Resolving Valorant's Speech Issues on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-11s-image-import-error-with-apple-devices-step-by-step/"><u>Resolving Windows 11'S Image Import Error with Apple Devices Step-by-Step</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-decades-old-windows-authentication-error/"><u>Reversing Decades-Old Windows Authentication Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/routine-to-reach-wordpad-functionality-in-windows/"><u>Routine to Reach WordPad Functionality in Windows</u></a></li>
<li><a href="https://fix-guide.techidaily.com/simple-solutions-to-fix-android-systemui-has-stopped-error-for-itel-p55-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Simple Solutions to Fix Android SystemUI Has Stopped Error For Itel P55 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-tackle-windows-security-faults-effectively/"><u>Steps to Tackle Windows Security Faults Effectively</u></a></li>
<li><a href="https://unlock-android.techidaily.com/still-using-pattern-locks-with-itel-a70-tips-tricks-and-helpful-advice-by-drfone-android/"><u>Still Using Pattern Locks with Itel A70? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-connectivity-issues-with-geforce-experience-software/"><u>Tackling Connectivity Issues with GeForce Experience Software</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-9-imitation-ai-threats-how-fraudulent-chatgpt-apps-endanger-your-privacy/"><u>Top 9 Imitation AI Threats: How Fraudulent ChatGPT Apps Endanger Your Privacy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-not-signed-update-problem-in-win11win10/"><u>Troubleshooting 'Not Signed' Update Problem in Win11/Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-disabled-roblox-game-due-to-user-settings-in-windows/"><u>Troubleshooting Disabled Roblox Game Due to User Settings in WINDOWS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unexpectedly-installed-rav-trace-back-and-efface-it/"><u>Unexpectedly Installed Rav? Trace Back & Efface It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unpacking-and-solving-the-mystery-of-error-0x8007251d/"><u>Unpacking and Solving the Mystery of Error 0X8007251d</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-and-resolving-windows-store-issue-code-0x00000000/"><u>Unraveling and Resolving Windows Store Issue Code 0X00000000</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-application-space-consumption-guide/"><u>Windows Application Space Consumption Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-key-control-a-step-by-step-approach/"><u>Windows Key Control - A Step-by-Step Approach</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>