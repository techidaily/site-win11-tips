---
title: Restoring Grayed-Out Secure Boot on Windows BIOS Settings
date: 2024-09-05T19:32:03.571Z
updated: 2024-09-06T19:32:03.571Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Grayed-Out Secure Boot on Windows BIOS Settings
excerpt: This Article Describes Restoring Grayed-Out Secure Boot on Windows BIOS Settings
keywords: Secure Boot Restoration,BIOS Recovery,Windows Boot Security,Secure Boot Fix Win,Grayed-Out BIOS Setting,Boot System Repair,Boot Integrity Check
thumbnail: https://thmb.techidaily.com/222a89a5c83410b00a22c43d882a6db1215cf7d876d04dbe1c258634355223be.jpg
---

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115946/19272" target="_top" id="2115946">
  <img src="//a.impactradius-go.com/display-ad/19272-2115946" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115946/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Restoring Grayed-Out Secure Boot on Windows BIOS Settings

 You need a secure boot-compatible computer to install Windows 11\. But there are other reasons to enable secure boot when available. It is a safety standard that prevents malicious codes from running on your PC during boot.

 But what if secure boot option is grayed out in BIOS? This can happen due to incorrect changes to your BIOS settings. You can load the default boot configuration to restore secure boot on Windows. Here is how to troubleshoot and fix the secure boot grayed-out problem in the BIOS.

## 1\. Set Admin Password in BIOS

 You can set an administrator password in BIOS security to prevent unauthorized access to the setup utility. On some computers, you may need to enable an administrator password to enable secure boot.

 To set an administrator password, you need to access the BIOS Security tab. The following steps are for an HP Pavilion laptop. Refer to your manufacturer's manual for other OEM devices.

To set an administrator password in BIOS:

1. Shut down your PC.
2. Press the**Power** to restart and then start pressing the**F10** key to enter BIOS Setup Utility. Other manufacturers like Dell, Asus, and Lenovo use F2 to access the BIOS utility.
3. In the BIOS Setup Utility, use the right and left arrow keys to open the**Security** tab.  
![bios set administrator password 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/bios-set-administrator-password-1.jpg)
4. Next, select**Administrator Password** and press**Enter** . On other computers, you may see the**Set Supervisor Password** option instead.
5. Here, type your new administrator password and then repeat the password in the**Confirm New Password** field.
6. Press**Enter** to save the password.  
![bios set administrator password](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/bios-set-administrator-password.jpg)
7. Next, press**F10** to save the changes and exit**BIOS** .
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137380/7443" target="_top" id="2137380">
  <img src="//a.impactradius-go.com/display-ad/7443-2137380" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137380/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Boot into**BIOS** again, and**Secure Boot** should be available for use.

 You can remove the administrator password after enabling Secure Boot. To do this, open the**Security** tab in BIOS and select**Administrator Password** . Next, enter your administrator password, but leave the**Enter New Password** and**Confirm New Password** fields blank. Press**Enter** again to save the changes.

## 2\. Disable Fast Boot in BIOS

 Fast Boot is a UEFI/BIOS feature. When enabled, it skips the check for a USB device, such as a bootable drive to speed up the boot process. However, the same can also prevent you from enabling secure boot in BIOS.

 To fix the issue, boot into the BIOS Setup Utility and disable Fast Boot. This feature may not be available on all computers. If not available, skip to the next solution.

 Note that the fast boot feature is different from Fast Startup. Fast Boot is a BIOS feature, whereas[Fast Startup is a Windows feature to speed up the boot process](https://www.makeuseof.com/what-is-windows-fast-startup-why-disable-it/) .

To disable fast boot in BIOS:

1. Boot into**BIOS**
2. Use the right and left arrow keys to open the**Advanced** tab.
3. Next, select**Boot Options** and press**Enter** .
4. Select**Fast Boot** and set it to**Disabled** .
5. Press**Enter** to save the changes.
6. Press**F10** to save the changes and exit.
7. After the computer restarts, boot into BIOS to see if you can access Secure Boot.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135359/19272" target="_top" id="2135359">
  <img src="//a.impactradius-go.com/display-ad/19272-2135359" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135359/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Restore the BIOS Security Settings to Factory Defaults

 You can restore BIOS security settings to factory defaults to enable secure boot. If you have made major changes to the BIOS security settings, a reset will remove the custom configuration and restore the factory default security settings. Most BIOS utilities allow you to perform a restore in the BIOS Security tab.

To restore BIOS Security settings to factory defaults:

1. Boot into BIOS.
2. Open the**Security** tab using the arrow keys.
3. Use the down arrow keys and select**Restore Security settings to factory defaults** .  
![restore bios factory settings default](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/restore-bios-factory-settings-default.jpg)
4. Read the description in the**Security Feature Reset Request** dialog. Here you'll need to enter a pass code to complete the reset request.
5. So, enter the shown**pass code** and press**Enter** .  
![restore bios factory settings default pass code](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/restore-bios-factory-settings-default-pass-code.jpg)
6. Press**F10** to save the changes and exit**BIOS** .
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135415/19272" target="_top" id="2135415">
  <img src="//a.impactradius-go.com/display-ad/19272-2135415" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135415/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Boot into BIOS again and check if the greyed-out secure boot problem is resolved.

## 4\. Update BIOS

![system information bios version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/system-information-bios.jpg)

 If the issue persists, your problem may be due to outdated BIOS firmware. While you don't need to update your system BIOS as frequently, the newer version tends to bring bug fixes, performance improvements, and newer hardware support.

 A BIOS update is recommended if your motherboard or laptop manufacturer recommends it. Any updates will be available via the laptop or motherboard manufacturer's websites.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135396/19272" target="_top" id="2135396">
  <img src="//a.impactradius-go.com/display-ad/19272-2135396" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135396/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Prepare Your Computer for a BIOS Update

 Before you update your BIOS, you'll need to[suspend BitLocker protection](https://www.makeuseof.com/windows-10-disable-or-suspend-bitlocker/) . You may also need to[temporarily turn off Windows Security protection](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) and third-party antivirus.

 Next, check your current BIOS version. You don't want to install an older version of BIOS on your computer. So, press the**Win** key, type**system information** , and open the System Information app from the search results. In the System Information dialog, locate and check the**BIOS Version/Date** entry. Note down the BIOS version, for example,**AMI F.27, 3/17/2022** .

 Unlike other driver and software feature updates, updating your BIOS can be tricky. You can update BIOS from within BIOS, where the BIOS Setup Utility can check your laptop manufacturer's website for BIOS updates. This option, however, is not available for all computers.

![HP download bios firmware update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hp-download-bios-firmware-update.jpg)

 Alternatively, you can also manually install BIOS from within Windows. For example, on an HP computer, go to the[HP Drivers page](https://support.hp.com/drivers) . Select your device manually or let the website detect the device for you.

 Next, check for the pending drivers and BIOS updates. If detected, download the HP Notebook System BIOS Update (Intel / AMD Processors). Make sure to compare the version with the version installed on your PC. If same or older, you don't need to update your BIOS.

 To update BIOS, run the firmware file and follow the on-screen instructions. Your computer will restart into the BIOS Update utility. Select**Apply Update Now** and wait for the update to finish installing. Once done, boot into BIOS and check if the Secure Boot option is available. Make sure to enable your antivirus and BitLocker protection again.

<!-- affiliate ads begin -->
<span id="1993651">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993651.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993651">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993651.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993651%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993651/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Load the BIOS Defaults Settings

![load BIOS default settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/load-bios-default-settings.jpg)

<!-- affiliate ads begin -->
<span id="1630055">
					<video width="192" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1630055.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18460-1630055">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1630055.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:120px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fcaperobbin.sjv.io%2Fc%2F5597632%2F1630055%2F18460'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1630055/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You can restore your BIOS to its factory default settings to fix issues occurring due to corrupt BIOS configuration. While loading the default settings will not affect your data, we recommend you back up any and all the important data on your computer before proceeding with a BIOS reset.

To load BIOS defaults settings:

1. Boot into**BIOS** and open the**Exit** tab.
2. Next, select the**Load Setup Defaults** option and press**Enter** .
3. Select**Yes** and press**Enter** . This will load setup default values for all SETUP items.
4. Select**Save Changes** and**Exit** .
5. Boot into**BIOS** again and check if the secure boot option is restored.

## Fixing the Grayed Out Secure Boot Option in BIOS

 Secure Boot in BIOS is greyed out if the administrator password is not set. In other instances, incorrect BIOS security settings and outdated BIOS can cause the issue. As a last resort, try to restore BIOS settings to factory defaults to restore Secure Boot in BIOS.


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
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-the-professionals-playbook-mastering-live-video-sharing-on-fb/"><u>[New] In 2024, The Professional's Playbook  Mastering Live Video Sharing on FB</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-crafting-the-perfect-ringtone-for-your-ios-device/"><u>[Updated] Crafting the Perfect Ringtone for Your iOS Device</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-eliminating-frame-drops-in-obs-broadcasts-for-2024/"><u>[Updated] Eliminating Frame Drops in OBS Broadcasts for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-flawlessrecorder-suite-w10-edition/"><u>[Updated] In 2024, FlawlessRecorder Suite W10 Edition</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-spotlight-on-8-trusted-youtube-growth-services/"><u>[Updated] Spotlight on 8 Trusted Youtube Growth Services</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-seamless-process-of-instagram-video-content/"><u>2024 Approved  Seamless Process of Instagram Video Content</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-visionarys-manual-selecting-the-most-compelling-4k-displays-today/"><u>2024 Approved  The Visionary's Manual  Selecting the Most Compelling 4K Displays Today</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-upgrade-your-content-creation-process-via-youtube-studio/"><u>2024 Approved  Upgrade Your Content Creation Process via YouTube Studio</u></a></li>
<li><a href="https://network-issues.techidaily.com/aligning-backups-fix-desktop-upside-down/"><u>Aligning Backups: Fix Desktop Upside Down</u></a></li>
<li><a href="https://vp-tips.techidaily.com/become-a-selfie-pro-10-premium-free-ios-camera-apps-for-2024/"><u>Become a Selfie Pro  10 Premium, Free iOS Camera Apps for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-up-unmet-windows-11-requirements-alert/"><u>Clear Up Unmet Windows 11 Requirements Alert</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-time-before-next-login-after-failure-in-win-1011/"><u>Customizing Time Before Next Login After Failure in Win 10/11</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/discover-cutting-edge-tech-through-toms-hardware-lens/"><u>Discover Cutting-Edge Tech Through Tom's Hardware Lens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-task-managers-live-feed-rates-for-windows-11/"><u>Elevate Task Manager's Live Feed Rates for Windows 11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/failed-to-play-mov-movies-on-motorola-razr-40-ultra-by-aiseesoft-video-converter-play-mov-on-android/"><u>Failed to play MOV movies on Motorola Razr 40 Ultra</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hiding-the-language-indicator-in-a-smokescreen-on-win11/"><u>Hiding the Language Indicator in a Smokescreen on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-address-the-requires-privilege-error-error-0x80070522-on-pcs/"><u>How To Address the “Requires Privilege” Error (Error 0X80070522) on PCs</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-poco-x6-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on Poco X6? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-easily-unlock-your-motorola-moto-e13-device-sim-by-drfone-android/"><u>In 2024, Easily Unlock Your Motorola Moto E13 Device SIM</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-infinix-hot-30-5g-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Infinix Hot 30 5G to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-new-multiple-ways-how-to-remove-icloud-activation-lock-on-your-iphone-14-pro-max-by-drfone-ios/"><u>In 2024, New Multiple Ways How To Remove iCloud Activation Lock On your iPhone 14 Pro Max</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-structuring-inspirational-lifestyle-content-for-audiences/"><u>In 2024, Structuring Inspirational Lifestyle Content for Audiences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jumpstart-creativity-opening-ms-paint-on-win11/"><u>Jumpstart Creativity: Opening MS Paint on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/map-out-windows-location-for-snaps/"><u>Map Out Windows Location for Snaps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-printer-network-setup-a-windows-guide/"><u>Mastering Printer Network Setup: A Windows Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-password-required-avoidance-on-windows-11/"><u>Mastering the Art of 'Password Required' Avoidance on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-challenges-uninstalling-and-reinstalling-store-games/"><u>Overcoming Challenges: Uninstalling and Reinstalling Store Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-bsod-interrupt-exception-troubleshoot/"><u>Preventing BSOD: Interrupt Exception Troubleshoot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaim-your-pc-7-tricks-to-revitalize-windows-update/"><u>Reclaim Your PC: 7 Tricks to Revitalize Windows Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaiming-control-command-efficiency-on-windows-11/"><u>Reclaiming Control Command Efficiency on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reconfigure-win11s-subnet-settings/"><u>Reconfigure Win11's Subnet Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefining-reset-count-for-lockouts-after-logon-errors-in-windows-11-pro/"><u>Redefining Reset Count for Lockouts After Logon Errors in Windows 11 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refreshing-windows-paperwork-handler/"><u>Refreshing Windows Paperwork Handler</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-create-file-failed-with-code-32-in-windows-error-30005/"><u>Resolving Create File Failed With Code 32 in Windows Error 30005</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-error-invalid-network-path/"><u>Resolving Windows Error: Invalid Network Path</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secrets-to-affordable-access-buying-windows-11-codes/"><u>Secrets to Affordable Access: Buying Windows 11 Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-handling-missing-powershell-on-windows/"><u>Strategies for Handling 'Missing PowerShell' On Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-fix-proc-invocation-failures-in-malwarebytes-software/"><u>Strategies to Fix Proc Invocation Failures in Malwarebytes Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-remedies-for-stalling-spotify-connectivity/"><u>Swift Remedies for Stalling Spotify Connectivity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-subtitle-issues-in-prime-video-for-smooth-windows-11-watching/"><u>Tackling Subtitle Issues in Prime Video for Smooth Windows 11 Watching</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-disabling-acceleration-with-your-mouse-in-windows/"><u>Tips for Disabling Acceleration with Your Mouse in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-post-monitor-connection-windows-lag-fixes/"><u>Troubleshooting Post-Monitor Connection: Windows Lag Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turning-your-spoken-language-into-written-communication-using-whisper-on-windows/"><u>Turning Your Spoken Language Into Written Communication Using Whisper on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncover-the-hidden-issues-causing-login-blackouts/"><u>Uncover the Hidden Issues Causing Login Blackouts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfreezing-steam-directory-access-fixes-for-windows-11/"><u>Unfreezing Steam Directory Access: Fixes for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-new-dimensions-of-windows-11-usefulness/"><u>Unlock New Dimensions of Windows 11 Usefulness</u></a></li>
</ul></div>
