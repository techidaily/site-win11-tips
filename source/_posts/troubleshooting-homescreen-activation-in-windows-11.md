---
title: Troubleshooting Homescreen Activation in Windows 11
date: 2024-06-25T16:26:14.328Z
updated: 2024-06-26T16:26:14.328Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Homescreen Activation in Windows 11
excerpt: This Article Describes Troubleshooting Homescreen Activation in Windows 11
keywords: Windows 11 Home Screen Fix,Enable Windows 11 Lockscreen,Windows 11 Startup Display,Windows 11 Homescreen Trouble,Activate Windows 11 Homescreen,Windows 11 Screen On/Off,Windows 11 Homescreen Fix Guide
thumbnail: https://thmb.techidaily.com/1a08c8dedd48664d90b507bda304483e40c9a1d2dac0696255a8394fc453f16e.jpg
---

## Troubleshooting Homescreen Activation in Windows 11

 Microsoft introduced the Settings app in Windows 8 and has since worked to improve the overall usability of the app. Its design has undergone several changes and the new one in Windows 11 looks much better due to the better UI and feature organization.

 However, it isn't just a cosmetic change because many utilities and Control Panel items are migrated to the Settings app. Microsoft also released a different version of the Settings app which incorporates a new Home section and a layout that will help you access the most commonly used settings. Let’s learn how to enable it on your PC.

## What's Wrong With the Old Settings App?

 The old Settings app directly opens the System section when you launch it. This section contains the most common settings like Display, Sound, Storage, Troubleshooting, and more. But you will still have to use the left side menu to access common settings such as Network, Personalization, Bluetooth, One Drive, and more.

![Current Settings app-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/current-settings-app-1.jpg)

 Microsoft noticed this issue and created a new Home section in the revamped Settings app. At the time of writing, you can only find this new Settings app in the Windows Insider program.

 The new Home section brings all the common settings under one roof, so the users don't have to dive deep into the Settings app to change a network or personalization setting.

## How to Enable the Home Section in the Settings App

 Repeat the following steps to enable and use the Home section in the Settings App:

### 1\. Download the Latest Insider Build and ViveTool

 The new Settings app with a Home section is available in the Windows Insider Dev build 23493\. So, you must update your PC enrolled in the Dev channel to the build version 23493 or above. If you don't want to enroll your PC into the Windows Insider program or want to try out the build in a virtual machine, there’s an easy way.

 You can [use UPP DUMP to download Windows Insider builds without enrolling in the Windows Insider program](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/). After the download completes, you will have to perform an in-place upgrade or create a bootable USB drive to install the Dev build on your PC.

 The enhanced Settings app with the included Home section isn't directly available in build 243943\. So, you must use Vivetool to enable the experimental feature. All you need to do is [download ViveTool from GitHub](https://github.com/thebookisclosed/ViVe/releases).

 After the download completes, navigate to the download location using File Explorer and extract the contents of the archive to a folder named "**Vive**". Move the folder containing the Vivetool to the **C** drive.

### 2\. Enable the Home Section in the Settings App

 After updating your Windows PC and installing Vivetool, repeat the following steps:

1. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **cmd** in the text box and press the **Ctrl + Shift + Enter** keys simultaneously.
2. The User Account Control window will pop up. Click on the **Yes** button.
3. First, you need to switch to the drive where you extracted the Vivetool. Type **cd c:\\** in the Command Prompt window and press the **Enter** key to execute the command.
4. Now, you need to switch to the folder where Vivetool is present. Since we extracted the tool to a folder named “**Vive**” our command becomes: **cd vive**.
5. Type **vivetool** and press the **Enter** key to check if the tool runs perfectly or not.  
![Enable the New Home Section in the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-the-new-home-section-in-the-settings-app.jpg)
6. Now, type the following commands and press the **Enter** key to execute them one by one:  
`vivetool /enable /id:42058345  
vivetool /enable /id:42058313`
7. **Close** the Command Prompt window.  
![Enable the New Home Section in the Settings App 2-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-the-new-home-section-in-the-settings-app-2-1.jpg)
8. **Restart** your PC to apply the changes made by the Vivetool in the Settings app.

## What Does the Enhanced Settings App Look Like?

 We compared the experimental and the old Settings app, and there are a few noticeable changes. For example, you automatically land on the Home section every time you open the enhanced Settings app.

 As a result, it is easier to access commonly uses settings. For instance, the top section shows your current internet connection, alongside a Windows Update check button.

![New and old settings app side by side-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-and-old-settings-app-side-by-side-1.jpg)

 Below that, there is a card that displays the recommended settings. You also get a bird’s eye view of the total available storage space in your Outlook account. There’s also a much-needed personalization card that you can use to change the themes and color mode of your Windows PC.

 If you haven’t completed a crucial security setup for your Microsoft account, you will see a reminder on the Home Page. Apart from that, Microsoft brazenly promotes its Microsoft service as a separate card. You cannot rearrange or remove tiles, so you are stuck with the layout and the promotional stuff from Microsoft.

![New home section in the settings app-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-home-section-in-the-settings-app-1.jpg)

 Still, it is a much-needed overhaul from the existing Settings app, which will improve the overall user experience. Microsoft is also trying out a Home section in the File Explorer app.

## A Revamped Settings App on Windows

 Microsoft’s take on the new Home section in the Settings app is a change we would definitely want to see in the stable builds in the upcoming months. But there are major changes arriving to the File Explorer and other Windows apps like the Photos app which recently got an update to support the dark mode and some zoom and usability improvements.

 However, it isn't just a cosmetic change because many utilities and Control Panel items are migrated to the Settings app. Microsoft also released a different version of the Settings app which incorporates a new Home section and a layout that will help you access the most commonly used settings. Let’s learn how to enable it on your PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/mending-disrupted-windows-thx-spatial-sound/"><u>Mending Disrupted Windows THX Spatial Sound</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-windows-from-repeatedly-accessing-cmos-settings/"><u>Stop Windows From Repeatedly Accessing CMOS Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-comparison-dissecting-key-differences-between-local-and-microsoft-logins-in-os/"><u>In-Depth Comparison: Dissecting Key Differences Between Local & Microsoft Logins in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-dism-error-0x800f082f-on-windows/"><u>Tackling DISM Error 0X800F082F on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-the-secrets-of-windows-iscsi-initiator-accessibility/"><u>Uncovering the Secrets of Windows iSCSI Initiator Accessibility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-the-prime-8-video-cutter-tools-on-windows/"><u>Discover the Prime 8 Video Cutter Tools on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-invisible-hardware-on-microsoft-oses/"><u>Addressing Invisible Hardware on Microsoft OSes</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-essential-no-cost-game-recording-software-guide/"><u>In 2024, Essential No-Cost Game Recording Software Guide</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-9-best-phone-monitoring-apps-for-nokia-c12-plus-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Best Phone Monitoring Apps for Nokia C12 Plus | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-quick-tips-for-smooth-ipad-screen-capture-for-2024/"><u>[New] Quick Tips for Smooth iPad Screen Capture for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-key-fb-video-plays-for-optimal-engagement-for-2024/"><u>[New] Key FB Video Plays for Optimal Engagement for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-elevating-your-work-with-impeccable-thumbnails/"><u>[Updated] 2024 Approved  Elevating Your Work with Impeccable Thumbnails</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-nokia-105-classic-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from Nokia 105 Classic to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-downgrade-iphone-se-2022-without-losing-any-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade iPhone SE (2022) without Losing Any Data? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/3-things-you-must-know-about-fake-snapchat-location-on-vivo-y100-drfone-by-drfone-virtual-android/"><u>3 Things You Must Know about Fake Snapchat Location On Vivo Y100 | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-expert-tips-capturing-high-quality-whatsapp-voice-transcripts/"><u>[Updated] Expert Tips  Capturing High-Quality WhatsApp Voice Transcripts</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>