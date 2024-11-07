---
title: "Fix Guide: Enhance Windows Bluetooth Device with Full Sound Features"
date: 2024-11-01T20:46:55.853Z
updated: 2024-11-07T05:01:21.012Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Fix Guide: Enhance Windows Bluetooth Device with Full Sound Features"
excerpt: "This Article Describes Fix Guide: Enhance Windows Bluetooth Device with Full Sound Features"
keywords: Bluetooth Audio Fix,Full Sound on Windows,Windows Bluetooth Tips,Improve Bluetooth Sound,Windows Hearing Boost,Bluetooth Device Enhancement,Optimize Windows Audio
thumbnail: https://thmb.techidaily.com/fa290563760e589f24a85fc95189dcd8b9293ad6203d8af2e7f7aed06726e6d2.jpg
---

## Fix Guide: Enhance Windows Bluetooth Device with Full Sound Features

 When you connect your Bluetooth headphone or speaker to your Windows computer, it may show the status as connected as "voice only" or "music only." This is nothing a quick "disconnect and reconnect" troubleshooting method can’t usually solve.

 However, if a quick reconnect doesn’t help, the problem may be due to a buggy audio driver, incorrect audio device configuration, and stopped audio services. Here we show you a few troubleshooting tips to help you resolve this problem on Windows and get your Bluetooth headset working again.

## 1\. Run the Windows Bluetooth Troubleshooter

![Run Bluetooth troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/bluetooth-troubleshooter-1.jpg)

 Windows 10 and 11 feature a built-in troubleshooter to find and fix common Bluetooth issues. It is an automated tool but works differently on Windows 10 and 11\.

 To run the Bluetooth troubleshooter:

1. Press **Win + I** to open **Settings**.
2. In the **System** tab, scroll down and click on **Troubleshooter**.
3. Select the **Other troubleshooters** option.  
![bluetooth troubleshooter get help automatic diagnostic](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/bluetooth-troubleshooter-get-help-automatic-diagnostic.jpg)
4. Click **Run** for the **Bluetooth** option.
5. The troubleshooter will scan the system for issues and recommend applicable fixes automatically. Follow the on-screen instructions to apply the fixes.
6. On the newer iteration of Windows 11, this will open the **Get Help** app seeking your consent to run the troubleshooter. Click **Yes** and then follow the on-screen instructions. You can skip some steps, like checking for Windows updates, by selecting the **No** option.

 Let the Get Help app try all available fixes until the issue is fixed.

## 2\. Enable Bluetooth Services in Device Properties

 Your headset or speaker offers distinct services which are enabled by default. However, if disabled, one or more Bluetooth functions can stop working for your audio device. To fix the issue, open the Bluetooth device properties using the Control Panel and review the services.

 Here’s how to do that:

1. Press **Win + R** to open **Run**.  
![control printers run box windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/control-printers-run-box-windows.jpg)
2. Type **control Printer** and click **OK** to open the **Bluetooth & devices** tab in the **Settings** app.

3. Next, click on **Devices**.  
![bluetooth and devices devices windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/bluetooth-and-devices-devices-windows-11-settings.jpg)
4. Scroll down and click **More devices** **and printer settings**. This should open **Devices and Printers** in the Control Panel.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094482/7443" target="_top" id="2094482">
  <img src="//a.impactradius-go.com/display-ad/7443-2094482" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Alternatively, copy and paste the following in the **Run** dialog to open **Device and Printers**.  
`shell:::{A8A91A66-3A7D-4424-8D24-04E180695C7A}`
6. Next, right-click on your **Bluetooth headset** or **speaker** and select **Properties**.
7. Open the **Services** tab in the **Properties** dialog.
8. Under **Bluetooth services**, select all the options. You’ll usually have the following options. Enable them all:  
`Audio Sink  
Handsfree Telephony  
Remote Control  
Remotely Controllable Device`
9. Click **Apply** and **OK** to save the changes.

 Close the Control Panel, and your Bluetooth audio device should start to work now. If not, perform a restart and check for any improvements.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132160/7443" target="_top" id="2132160">
  <img src="//a.impactradius-go.com/display-ad/7443-2132160" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132160/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Check and Enable the Windows Bluetooth Services

 Windows OS uses multiple Bluetooth-related services that help it connect to other Bluetooth devices and transmit audio. This is in addition to the services enabled above.

 If any of these services are stopped or incorrectly configured, your Bluetooth headphone or speaker can start malfunctioning. To fix the problem, check the status of all the essential Bluetooth-associated services and restart them if necessary.

 You can check the status of services and restart them from the Services snap-in. To check and restart Bluetooth services:

1. Press **Win + R** to open **Run**.
2. Type **services.msc** and click **OK** to open the Services snap-in.  
![Services Shortcode In Run Dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/opening-sevices-from-run_dialog.jpg)
3. In the Services snap-in, locate the following services and check if the status shows **Running**.  

`Bluetooth Audio Gateway Service  
Bluetooth Support Service  
Bluetooth User Support Service`
4. If not, right-click on **Bluetooth Audio Gateway Service** and select **Restart**.  
![restart bluetooth services services snap in windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/restart-bluetooth-services-services-snap-in-windows.jpg)
5. Once done, check the other two services. If not running, restart the services one by one.
6. Close the Services snap-in and check for any improvements.

 If the issue persists, [disable any audio enhancements on Windows](https://www.makeuseof.com/disable-audio-enhancements-windows/). While intended to improve your listening experience, these enhancements can also cause audio issues. Turning off these enhancements can help you resolve the problem with your audio devices.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123739/7443" target="_top" id="2123739">
  <img src="//a.impactradius-go.com/display-ad/7443-2123739" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123739/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Check Your Bluetooth Device Driver for Issues

 An outdated or buggy Bluetooth driver is a common cause of a malfunctioning Bluetooth device on Windows computers. Try to update the driver, perform a roll back or uninstall the driver to see if it resolves the issue.

* **Update the driver**: You can [find and replace outdated drivers on Windows using Device Manager](https://www.makeuseof.com/tag/find-replace-outdated-windows-drivers/). In Device Manager, expand the **Bluetooth** section and locate your Bluetooth adapter. On most computers, you may find an **Intel Bluetooth Wireless Bluetooth** device. Find the device and check if a new driver update is available.
* **Roll back a recent driver update**: New but buggy driver update can also cause the Bluetooth adapter to act up. To fix the issue, you can [perform a driver rollback for the Bluetooth adapter](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) to install the previous driver version. While a handy option, its availability can differ depending on when the driver was installed.
* **Reinstall the Bluetooth adapter driver:** A reinstall may be necessary if a corrupt or partially installed driver causes Bluetooth-related problems. To [uninstall Bluetooth drivers in Windows](https://www.makeuseof.com/windows-11-uninstall-drivers/), you can use the Device Manager or the Command Prompt. Restart your PC and Windows should reinstall the driver.

## 5\. Update the Bluetooth Driver Manually From the Manufacturer’s Website

 While some driver updates may be available via Windows updates, you will likely receive the latest update from the device manufacturer's website. In this instance, check your Bluetooth device manufacturer's website to see if a new update is available.

 To manually download and install the latest Bluetooth device driver update:

1. Press **Win + R** to open **Run**.
2. Type **devmgmt.msc** and click **OK** to open Device Manager.
3. In Device Manager, expand the **Bluetooth** section. Here locate your Bluetooth device's make. In this instance, we have an **Intel (R) Wireless Bluetooth (R)** device.  
![device manager driver version detials](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/device-manager-driver-version-detials.jpg)
4. Double-click on the Bluetooth device entry to open its properties.
5. Next, open the **Driver** tab. Note down the Driver version. You’ll need this to see if a newer driver version is available.
6. Since we have an Intel Bluetooth Wireless device, we’ll open the [Intel Wireless Bluetooth for Windows page](https://www.intel.com/content/www/us/en/download/18649/intel-wireless-bluetooth-for-windows-10-and-windows-11.html). The page lists the latest version of the driver available for download. In case of a different Bluetooth device manufacturer, visit the manufacturer's website and locate downloads for the device.  
![download bluetooth driver manually](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/download-bluetooth-driver-manually.jpg)
7. Compare the version with the one available on your computer. Download the newer version if available. Run the installer and complete the installation.

8. During installation, your Bluetooth devices, including the headphone, keyboard, and mouse, may stop working temporarily. Wait for a few minutes for the changes to apply. Sometimes, a restart may be necessary to finish installing the update.

 Similarly, the download page may also offer older versions of the driver. If you have the latest version installed, try to download an older version to perform a downgrade. Useful if the rollback driver option isn’t available in Device Manager.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100537/7443" target="_top" id="2100537">
  <img src="//a.impactradius-go.com/display-ad/7443-2100537" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100537/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Fixing the Bluetooth Headset or Speaker Showing a "Voice Only" Error

 Incorrect Bluetooth service configuration is a common reason your Bluetooth device shows as connected as voice only. You can configure the device’s properties to enable these services. If the issue persists, check for driver issues by installing a new driver update or performing a driver rollback.

 However, if a quick reconnect doesn’t help, the problem may be due to a buggy audio driver, incorrect audio device configuration, and stopped audio services. Here we show you a few troubleshooting tips to help you resolve this problem on Windows and get your Bluetooth headset working again.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-optimal-action-capture-software-insights/"><u>[New] 2024 Approved Optimal Action Capture Software Insights</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-low-fee-android-communication-options-10-best/"><u>[Updated] In 2024, Low-Fee Android Communication Options, 10 Best</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-premier-choices-for-accessible-screen-recorders/"><u>2024 Approved Premier Choices for Accessible Screen Recorders</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unlocking-skypes-full-capacity-with-effective-zoom-methods/"><u>2024 Approved Unlocking Skype's Full Capacity with Effective Zoom Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/compelling-case-for-continuing-with-your-current-os-windows-10/"><u>Compelling Case for Continuing with Your Current OS - Windows 10</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/convert-your-ipod-songs-a-step-by-step-guide-to-changing-drm-m4p-files-to-freely-listenable-m4a-without-costs/"><u>Convert Your iPod Songs: A Step-by-Step Guide to Changing DRM M4P Files to Freely Listenable M4A without Costs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/custom-pdf-viewer-preferences-on-windows/"><u>Custom PDF Viewer Preferences on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-advanced-file-backup-features/"><u>Enabling Advanced File Backup Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-windows-11-services-disabling-risk/"><u>Essential Windows 11 Services: Disabling Risk</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-complete-setup-blueprint-for-wm6/"><u>In 2024, Complete Setup Blueprint for WM6</u></a></li>
<li><a href="https://fox-links.techidaily.com/in-2024-cutting-down-the-wait-quick-time-lapse-on-iphone/"><u>In 2024, Cutting Down the Wait Quick Time-Lapse on iPhone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-change-google-pixel-8-lock-screen-clock-in-seconds-by-drfone-android/"><u>In 2024, How To Change Google Pixel 8 Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-security-of-user-authentication-on-w11/"><u>Mastering the Security of User Authentication on W11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/modern-methods-rapidly-turning-srt-into-txt-format-for-2024/"><u>Modern Methods Rapidly Turning SRT Into TXT Format for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/premier-visual-quality-leaks-for-2024/"><u>Premier Visual Quality Leaks for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-access-to-windows-network-configuration-setup/"><u>Quick Access to Window's Network Configuration Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-remedies-to-tackle-windows-operations-promotion-errors/"><u>Quick Remedies to Tackle Windows Operations Promotion Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-11s-0x8004def5-onedrive-fiasco/"><u>Resolving Windows 11'S 0X8004DEF5 Onedrive Fiasco</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalize-your-text-editor-experience-7-troubleshooting-tips-for-windows/"><u>Revitalize Your Text Editor Experience: 7 Troubleshooting Tips for Windows</u></a></li>
</ul></div>

