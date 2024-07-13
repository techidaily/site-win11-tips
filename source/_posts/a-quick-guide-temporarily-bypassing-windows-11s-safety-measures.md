---
title: "A Quick Guide: Temporarily Bypassing Windows 11'S Safety Measures"
date: 2024-07-12T17:48:51.126Z
updated: 2024-07-13T17:48:51.126Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes A Quick Guide: Temporarily Bypassing Windows 11'S Safety Measures"
excerpt: "This Article Describes A Quick Guide: Temporarily Bypassing Windows 11'S Safety Measures"
keywords: Bypass Windows 11 SafeGuard,Easily Skip Security Features,Shortcut Windows 11 Protection,Temporarily Disable WS11 Safeguards,Bypassing Win11 Safety Norms,Quick Windows 11 Security Bypass,Circumvent Win11 Defenses
thumbnail: https://thmb.techidaily.com/4c1a39277ea3313859b9362ca2031ca0eab790234cc40f347849f915f7ea8138.jpg
---

## A Quick Guide: Temporarily Bypassing Windows 11'S Safety Measures

 Windows Security is the built-in security app for Windows 11\. You should always keep it enabled as it protects your computer from online and offline threats. However, you may come across situations where you might need to disable it.

 Whether you want to disable it for personal preference or install an app that's facing interference by it, here's how to temporarily disable Windows Security in Windows 11.

## 1\. Temporarily Disable Windows Security Using the Settings App

 The Settings app is the central hub of Windows OS, from where you can manage important system settings. You can use it to personalize your computer, change privacy settings, update Windows, and do much more. It's also one of the places to disable Windows Security on your computer. Here's how:

1. Press the**Win + I** hotkeys to open the**Settings** app.
2. Choose**Privacy & security** from the left sidebar.
3. Click the**Open Windows** **Security** button on the right pane.  
![Open Windows Security option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/open-windows-security.jpg)
4. In the Windows Security app, choose the**Virus & threats protection** option from the left sidebar.
5. Click**Manage settings** under the Virus & threats protection section.
6. Disable the toggle under the**Real-time protection** option.  
![Disabling Real-time protection in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/real-time-protection.jpg)

## 2\. How to Temporarily Disable Windows Security Using the Registry Editor

 Windows Registry is a massive database of important settings and software installed on your computer. You can access and edit that database using a built-in tool called the Registry Editor.

 The Registry Editor can also come in handy in temporarily disabling Windows Security. Here's how to do that:

1. Open the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Windows Security** and press Enter.
3. Select**Virus & threat protection** from the left sidebar.
4. Turn off the toggle under the**Tamper protection** option.  
![Disabling Tamper Protection in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tamper-protection.jpg)
5. Click**Yes** to the UAC that crops up.

 Now it's time to open the Registry Editor. Check out [how to open the Registry Editor on Windows 11](https://www.makeuseof.com/windows-11-open-registry-editor/) for steps on how to do this.

1. When the Registry Editor opens, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows Defender`
2. Right-click on**Windows Defender** in the left sidebar and choose**Permissions.**  
![Permissions option in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/permissions.jpg)
3. Click the**Advanced** options.  
![Advanced option in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced.jpg)
4. Click**Change** next to the**Owner** option.
5. In the**Select User or Group window** , click the**Advanced** button.  
![Advanced option in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced-option.jpg)

1. Click the**Find Now** button and then select the admin account.  
![Find Now option in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/find-now.jpg)
2. Click**OK** \>**OK** to save the changes.
3. Check the **Replace all child object permission entries with inheritable permission entries from this object** box.  
![Replace all child object permission entries with inheritable permission entries from this object box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/replace-all-child-object-permission-entries-with-inheritable-permission-entries-from-this-object.jpg)
4. Click**Apply** \>**OK.**
5. Next, head towards the**Permission for Windows Defender** window, and check the box next to**Full control.**  
![Full control box in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/full-control-box.jpg)
6. Click**Apply** \>**OK.**
7. Right-click on the blank space in the right pane, and create three**DWORD (32-bit) Value** with the following names:  
`DisableAntiVirus  

DisableAntiSpyware  

ServiceStartStates`
8. Double-click on each value, type**1** in**Value data,** and click**OK.**

Restart your computer for the changes to take effect.

## 3\. Temporarily Disable Windows Security Using the Local Group Policy Editor

 Another quick way to temporarily turn off Windows Security is through the Local Group Policy Editor. Here's what you need to do:

1. Open the Run dialog box, type**gpedit.msc** , and click**OK.**
2. In the Local Group Policy Editor, navigate to**Computer Configuration** \>**Administrative Templates** \>**Windows Components** \>**Microsoft Defender Antivirus** .
3. Double-click on the**Turn off Microsoft Defender Antivirus** policy.  
![Microsoft Defender Antivirus policy in LGPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/microsoft-defender-antivirus.jpg)
4. Click**Enabled** .  
![Enabled option in LGPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enabled-option.jpg)
5. Click**Apply** \>**OK.**

 Once your work is done, you can enable Windows Security by choosing**Disabled** for the Turn off Microsoft Defender Antivirus policy.

## 4\. Temporarily Disable Windows Security Using Autoruns

 Autoruns is a Windows utility using which you can turn off the service responsible for starting Windows Security at startup. Before you use Autoruns, disable Tamper Protection by following the steps in method 2.

 Follow the below instructions to disable Windows Security using Autoruns:

1. To begin with,[download Autoruns](https://download.sysinternals.com/files/Autoruns.zip) on your computer.
2. Extract the downloaded file on your computer.
3. Next, boot your computer in safe mode (see [how to boot in safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) ) and then open the extracted Autoruns folder.
4. Double-click on the**Autoruns64** file and then choose**Run** from the prompt that crops up.  
![Run option for Autoruns](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/run-option.jpg)
5. Click**Agree** in the**Autoruns Licence Agreement window** .
6. In the Autoruns window, click**Options** and uncheck**Hide Windows Entries.**  
![Hide Microsoft Entries option in Autoruns](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/hide-microsoft-enteries.jpg)
7. Click**Services.**
8. Uncheck the**WinDefend** box and then close the Autoruns window.  
![Disabling WinDefend in Autoruns](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windefend.jpg)

 Now, to boot in normal mode, open the**System Configuration** window, select**Normal startup,** and then**OK.**

## Stop Windows Security for a Little While on Windows 11

 The new Window Security app ensures you don't have to install a dedicated antivirus program to safeguard your computer. However, the strict policy of Windows Security can sometimes block the installation of third-party apps on your computer. Fortunately, you can disable Windows Security by following the above methods.


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
<li><a href="https://win11-tips.techidaily.com/how-to-reboot-dns-cache-in-windows-11/"><u>How to Reboot DNS Cache in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-preference-portal-your-operating-systems-lair/"><u>The Preference Portal: Your Operating System’s Lair</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/eep-up-to-date-with-youtube-community-guidelines/"><u>[New] Keep Up-to-Date With YouTube Community Guidelines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-gaming-service-failures-on-pcs-and-laptops/"><u>How To Resolve Gaming Service Failures on PCs and Laptops</u></a></li>
<li><a href="https://screen-capture.techidaily.com/comprehensive-capture-solutions-azs-reviews-and-backups-for-2024/"><u>Comprehensive Capture Solutions - AZ's Reviews & Backups for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-save-windows-spotlight-pictures-to-use-as-wallpapers-when-you-want/"><u>How to Save Windows Spotlight Pictures to Use as Wallpapers When You Want</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insight-into-the-functionality-of-windows-component-services/"><u>Insight Into the Functionality of Windows Component Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-efficiency-into-daily-use-with-win11-icon-additions/"><u>Integrating Efficiency Into Daily Use with Win11 Icon Additions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-task-manager-with-finesse/"><u>Elevating Task Manager with Finesse</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-a-windows-11-recycle-bin-malfunction/"><u>Fixing a Windows 11 Recycle Bin Malfunction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harnessing-the-power-of-google-maps-in-your-windows-system/"><u>Harnessing the Power of Google Maps in Your Windows System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-microsoft-outlooks-something-went-wrong-error-on-windows/"><u>How to Fix Microsoft Outlook's “Something Went Wrong” Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jump-from-smartphone-to-desktop-android-gameplay-in-windows-11-with-google/"><u>Jump From Smartphone to Desktop: Android Gameplay in Windows 11 with Google</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-fix-windows-11-graphics-drivers-reset/"><u>Efficient Fix: Windows 11 Graphics Drivers Reset</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/switch-cards-between-apple-iphone-6s-and-other-iphones-will-move-all-phone-services-drfone-by-drfone-transfer-from-ios/"><u>Switch Cards Between Apple iPhone 6s and other iPhones Will Move All Phone Services? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-admin-managed-feature-issues-in-windows-11/"><u>Troubleshooting Admin-Managed Feature Issues in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-to-utilizing-diskusage-on-windows-systems/"><u>Expert Guide to Utilizing DiskUsage on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-open-programs-with-preset-window-sizes-in-windows-11/"><u>How to Open Programs With Preset Window Sizes in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-installation-fix-for-ms-pc-manager-on-xp/"><u>Unlock Installation: Fix for MS PC Manager on XP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-11-command-not-working-issue/"><u>Fixing Windows 11 Command Not Working Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unified-tech-experience-windows-pc-and-galaxy-device-flow/"><u>Unified Tech Experience – Windows PC & Galaxy Device Flow</u></a></li>
<li><a href="https://network-issues.techidaily.com/navigating-through-youtubes-unwanted-green-mistakes/"><u>Navigating Through YouTube's Unwanted Green Mistakes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/brightness-boost-for-windows-11-control-your-pcs-glow/"><u>Brightness Boost for Windows 11: Control Your PC's Glow</u></a></li>
<li><a href="https://win11-tips.techidaily.com/zenith-of-clarity-top-strategies-for-combating-blurry-windows-views/"><u>Zenith of Clarity: Top Strategies for Combating Blurry Windows Views</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/tips-for-preventing-invisible-thumbnails-on-shorts-videos-for-2024/"><u>Tips for Preventing Invisible Thumbnails on Shorts Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-wintoys-unlocking-a-versatile-tool-in-windows-os/"><u>Understanding WinToys: Unlocking a Versatile Tool in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/curtailing-premature-windows-edge-tabs/"><u>Curtailing Premature Windows Edge Tabs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/alternate-routes-to-open-the-latest-windows-apps/"><u>Alternate Routes to Open the Latest Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-for-fixing-fall-guys-link-failures-windows-wise/"><u>Essential Steps for Fixing Fall Guys Link Failures Windows-Wise</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-add-emoji-to-linkedin-post-5-tips-you-need-to-know-for-2024/"><u>New Add Emoji to Linkedin Post – 5 Tips You Need to Know for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-ram-cache-and-how-to-purge-it/"><u>Decoding Windows RAM Cache and How to Purge It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-code-0x80070570-file-corruption-in-windows-11/"><u>Troubleshooting Code 0X80070570 File Corruption in Windows 11</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-best-practices-for-converting-webp-to-jpg-format/"><u>2024 Approved  Best Practices for Converting WebP to JPG Format</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-window-restoration-after-dark-screens/"><u>Effortless Window Restoration After Dark Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-resolving-winerror-0x80071a90-in-windows/"><u>Understanding & Resolving WinError: 0X80071a90 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719328086208-calibrate-display-colors-go-to-settings-)-system-)-display-and-use-the-built-in-calibration-tool-for-accurate-color-representation/"><u>Calibrate Display Colors: Go to 'Settings' > 'System' > 'Display' And Use the Built-In Calibration Tool for Accurate Color Representation.</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-perfect-your-instagram-video-upload/"><u>2024 Approved  Perfect Your Instagram Video Upload</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-geforce-experiences-retrieval-failure-on-windows-11-systems/"><u>Fixing GeForce Experience's Retrieval Failure on Windows 11 Systems</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-mastering-airtunes-on-your-apple-devices-quick-guide-to-repairs/"><u>[New] Mastering Airtunes on Your Apple Devices - Quick Guide to Repairs</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/go-full-screen-with-ease-masterful-mac-scaling-methods-for-insta-posts/"><u>Go Full Screen with Ease  Masterful Mac Scaling Methods for Insta Posts</u></a></li>
</ul></div>
