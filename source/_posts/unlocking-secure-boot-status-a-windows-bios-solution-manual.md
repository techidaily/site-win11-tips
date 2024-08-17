---
title: "Unlocking Secure Boot Status: A Windows BIOS Solution Manual"
date: 2024-08-16T01:25:55.072Z
updated: 2024-08-17T01:25:55.072Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlocking Secure Boot Status: A Windows BIOS Solution Manual"
excerpt: "This Article Describes Unlocking Secure Boot Status: A Windows BIOS Solution Manual"
keywords: Secure Boot Guide,BIOS Security Tips,Unlocking UEFI,Windows Boot Modes,BIOS Update Steps,System Booting Fixes,Safe Startup Methods
thumbnail: https://thmb.techidaily.com/212e21d96bc4724d21a24c1110e599b63bc2c397e891bb1e1f9fc06be1f08b00.jpg
---

## Unlocking Secure Boot Status: A Windows BIOS Solution Manual

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
8. Boot into**BIOS** again, and**Secure Boot** should be available for use.

 You can remove the administrator password after enabling Secure Boot. To do this, open the**Security** tab in BIOS and select**Administrator Password** . Next, enter your administrator password, but leave the**Enter New Password** and**Confirm New Password** fields blank. Press**Enter** again to save the changes.

## 2\. Disable Fast Boot in BIOS

 Fast Boot is a UEFI/BIOS feature. When enabled, it skips the check for a USB device, such as a bootable drive to speed up the boot process. However, the same can also prevent you from enabling secure boot in BIOS.

 To fix the issue, boot into the BIOS Setup Utility and disable Fast Boot. This feature may not be available on all computers. If not available, skip to the next solution.

 Note that the fast boot feature is different from Fast Startup. Fast Boot is a BIOS feature, whereas [Fast Startup is a Windows feature to speed up the boot process](https://www.makeuseof.com/what-is-windows-fast-startup-why-disable-it/) .

To disable fast boot in BIOS:

1. Boot into**BIOS**
2. Use the right and left arrow keys to open the**Advanced** tab.
3. Next, select**Boot Options** and press**Enter** .
4. Select**Fast Boot** and set it to**Disabled** .
5. Press**Enter** to save the changes.
6. Press**F10** to save the changes and exit.
7. After the computer restarts, boot into BIOS to see if you can access Secure Boot.

## 3\. Restore the BIOS Security Settings to Factory Defaults

 You can restore BIOS security settings to factory defaults to enable secure boot. If you have made major changes to the BIOS security settings, a reset will remove the custom configuration and restore the factory default security settings. Most BIOS utilities allow you to perform a restore in the BIOS Security tab.

To restore BIOS Security settings to factory defaults:

1. Boot into BIOS.
2. Open the**Security** tab using the arrow keys.
3. Use the down arrow keys and select**Restore Security settings to factory defaults** .  
![restore bios factory settings default](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/restore-bios-factory-settings-default.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
4. Read the description in the**Security Feature Reset Request** dialog. Here you'll need to enter a pass code to complete the reset request.
5. So, enter the shown**pass code** and press**Enter** .  
![restore bios factory settings default pass code](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/restore-bios-factory-settings-default-pass-code.jpg)
6. Press**F10** to save the changes and exit**BIOS** .
7. Boot into BIOS again and check if the greyed-out secure boot problem is resolved.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
## 4\. Update BIOS
![system information bios version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/system-information-bios.jpg)

 If the issue persists, your problem may be due to outdated BIOS firmware. While you don't need to update your system BIOS as frequently, the newer version tends to bring bug fixes, performance improvements, and newer hardware support.

 A BIOS update is recommended if your motherboard or laptop manufacturer recommends it. Any updates will be available via the laptop or motherboard manufacturer's websites.

<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Prepare Your Computer for a BIOS Update

 Before you update your BIOS, you'll need to [suspend BitLocker protection](https://www.makeuseof.com/windows-10-disable-or-suspend-bitlocker/) . You may also need to [temporarily turn off Windows Security protection](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) and third-party antivirus.

 Next, check your current BIOS version. You don't want to install an older version of BIOS on your computer. So, press the**Win** key, type**system information** , and open the System Information app from the search results. In the System Information dialog, locate and check the**BIOS Version/Date** entry. Note down the BIOS version, for example,**AMI F.27, 3/17/2022** .

 Unlike other driver and software feature updates, updating your BIOS can be tricky. You can update BIOS from within BIOS, where the BIOS Setup Utility can check your laptop manufacturer's website for BIOS updates. This option, however, is not available for all computers.

![HP download bios firmware update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hp-download-bios-firmware-update.jpg)
<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Alternatively, you can also manually install BIOS from within Windows. For example, on an HP computer, go to the [HP Drivers page](https://support.hp.com/drivers) . Select your device manually or let the website detect the device for you.

 Next, check for the pending drivers and BIOS updates. If detected, download the HP Notebook System BIOS Update (Intel / AMD Processors). Make sure to compare the version with the version installed on your PC. If same or older, you don't need to update your BIOS.

 To update BIOS, run the firmware file and follow the on-screen instructions. Your computer will restart into the BIOS Update utility. Select**Apply Update Now** and wait for the update to finish installing. Once done, boot into BIOS and check if the Secure Boot option is available. Make sure to enable your antivirus and BitLocker protection again.

## 5\. Load the BIOS Defaults Settings
![load BIOS default settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/load-bios-default-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->

 You can restore your BIOS to its factory default settings to fix issues occurring due to corrupt BIOS configuration. While loading the default settings will not affect your data, we recommend you back up any and all the important data on your computer before proceeding with a BIOS reset.

To load BIOS defaults settings:

1. Boot into**BIOS** and open the**Exit** tab.
2. Next, select the**Load Setup Defaults** option and press**Enter** .
3. Select**Yes** and press**Enter** . This will load setup default values for all SETUP items.
4. Select**Save Changes** and**Exit** .
5. Boot into**BIOS** again and check if the secure boot option is restored.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
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
<li><a href="https://fox-links.techidaily.com/new-melodic-moments-to-augment-your-status/"><u>[New] Melodic Moments to Augment Your Status</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-navigating-soundtrack-selection-in-unboxing-filmmaking/"><u>[New] Navigating Soundtrack Selection in Unboxing Filmmaking</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-chuckling-chronicles-your-essential-meme-tools-list/"><u>[Updated] Chuckling Chronicles  Your Essential Meme Tools List</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-masterful-color-transformations-with-free-and-paid-luts-for-cameras-for-2024/"><u>[Updated] Masterful Color Transformations with Free & Paid LUTs for Cameras for 2024</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/10-culturally-rich-foreign-movies/"><u>10 Culturally Rich Foreign Movies</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-innovative-tools-for-cutting-edge-xbox-gaming-recordings/"><u>2024 Approved  Innovative Tools for Cutting-Edge Xbox Gaming Recordings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-windows-11-search-performance-with-these-key-methods/"><u>Boosting Windows 11 Search Performance with These Key Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/break-free-from-issues-restoring-windows-family-security/"><u>Break Free From Issues: Restoring Windows Family Security</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breakdown-of-windows-11s-latest-enhancements-after-update/"><u>Breakdown of Windows 11'S Latest Enhancements After Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-barriers-for-skyrims-script-enhancement/"><u>Breaking Barriers for Skyrim's Script Enhancement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-what-makes-ai-systems-different/"><u>Breaking Down: What Makes AI Systems Different?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-barrier-enabling-sluggish-batch-files-on-pcs/"><u>Breaking the Barrier: Enabling Sluggish Batch Files on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-gaps-in-computing-ai-for-windows-solutions/"><u>Bridging Gaps in Computing: AI for Windows Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-void-spaces-in-windows-navigator/"><u>Bridging Void Spaces in Windows Navigator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-the-store-reactivation-steps-for-ms-in-windows-11/"><u>Bring Back the Store: Reactivation Steps for MS in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-outdated-computers-into-the-win11-era/"><u>Bringing Outdated Computers Into the Win11 Era</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-unknown-device-error-step-by-step-guide-for-windows-users/"><u>Bypassing 'Unknown Device Error': Step-by-Step Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-disabled-accounts-fixing-windows-login-fails/"><u>Bypassing Disabled Accounts: Fixing Windows Login Fails</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-hardware-errors-windows-1110-guide/"><u>Bypassing Hardware Errors: Windows 11/10 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-the-obstacle-dealing-with-device-error-22-on-windows-11/"><u>Bypassing the Obstacle: Dealing with Device Error 22 on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-usb-suspend-windows-11-guide/"><u>Bypassing USB Suspend: Windows 11 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-11-admin-lockdown/"><u>Bypassing Windows 11 Admin Lockdown</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-workspace-failures-fixing-office-errors-in-winos/"><u>Bypassing Workspace Failures: Fixing Office Errors in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-your-geforce-experience-scanning-problem-in-win/"><u>Bypassing Your GeForce Experience Scanning Problem in Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cableless-game-controls-connecting-ps3-to-pc/"><u>Cableless Game Controls: Connecting PS3 to PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cant-delete-temporary-files-in-windows-try-these-fixes/"><u>Can’t Delete Temporary Files in Windows? Try These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/captivating-windows-slideshow-execute-with-seven-simple-steps/"><u>Captivating Windows Slideshow - Execute with Seven Simple Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/change-your-windows-terminal-color-scheme/"><u>Change Your Windows Terminal Color Scheme</u></a></li>
<li><a href="https://win11-tips.techidaily.com/charting-course-past-the-lost-at-sea-xbox-error-in-win11/"><u>Charting Course Past the Lost at Sea Xbox Error in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/choosing-effective-real-time-file-transfer-software-google-and-windows-options/"><u>Choosing Effective Real-Time File Transfer Software: Google & Windows Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/choosing-the-best-bittorrent-clients-for-windows-users/"><u>Choosing the Best BitTorrent Clients for Windows Users</u></a></li>
<li><a href="https://fox-that.techidaily.com/diy-solutions-for-restoring-your-airplay-functionality/"><u>DIY Solutions for Restoring Your AirPlay Functionality</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/expanding-viewership-tweeting-to-fb-effectively-for-2024/"><u>Expanding Viewership  Tweeting to FB Effectively for 2024</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-nokia-c300-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Nokia C300 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-free-up-apple-iphone-15-pro-space-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>How To Free Up Apple iPhone 15 Pro Space | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-bypass-icloud-activation-lock-with-imei-code-on-your-iphone-6-plus-by-drfone-ios/"><u>In 2024, Bypass iCloud Activation Lock with IMEI Code On your iPhone 6 Plus</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-life360-notify-when-you-log-out-on-honor-magic-6-lite-drfone-by-drfone-virtual-android/"><u>In 2024, Does Life360 Notify When You Log Out On Honor Magic 6 Lite? | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-for-people-wanting-to-mock-gps-on-oppo-a2-devices-drfone-by-drfone-virtual/"><u>In 2024, For People Wanting to Mock GPS on Oppo A2 Devices | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-can-i-use-a-fake-gps-without-mock-location-on-motorola-edge-40-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Use a Fake GPS Without Mock Location On Motorola Edge 40? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-use-google-assistant-on-your-lock-screen-of-infinix-hot-30i-phone-by-drfone-android/"><u>In 2024, How to Use Google Assistant on Your Lock Screen Of Infinix Hot 30i Phone</u></a></li>
<li><a href="https://buynow-info.techidaily.com/in-depth-analysis-of-the-midland-gxt1000vp4-radio-transceiver-exceptional-clarity-in-communications/"><u>In-Depth Analysis of the Midland GXT1000VP4 Radio Transceiver - Exceptional Clarity in Communications</u></a></li>
<li><a href="https://some-tips.techidaily.com/is-photoshops-image-smoothing-worth-the-hype-in-2024/"><u>Is Photoshop's Image Smoothing Worth the Hype, In 2024</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/latest-logitech-brio-webcam-drivers-available-for-windows-1187-users/"><u>Latest Logitech Brio Webcam Drivers Available for Windows 11/8/7 Users</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/leveraging-visuals-for-profile-dominance-for-2024/"><u>Leveraging Visuals for Profile Dominance for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/prime-catchy-headline-creator-for-2024/"><u>Prime Catchy Headline Creator for 2024</u></a></li>
<li><a href="https://win-able.techidaily.com/quick-fixes-for-sluggish-downloads-in-utorrent-get-back-to-torrenting-fast/"><u>Quick Fixes for Sluggish Downloads in uTorrent – Get Back to Torrenting Fast!</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-4-sim-location-trackers-to-easily-find-your-lost-xiaomi-13t-pro-device-by-drfone-android/"><u>Top 4 SIM Location Trackers To Easily Find Your Lost Xiaomi 13T Pro Device</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/ultimate-voice-transformation-tools-for-social-media-stars-for-2024/"><u>Ultimate Voice Transformation Tools for Social Media Stars for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-the-ipogo-get-you-banned-and-how-to-solve-it-on-lava-agni-2-5g-drfone-by-drfone-virtual-android/"><u>Will the iPogo Get You Banned and How to Solve It On Lava Agni 2 5G | Dr.fone</u></a></li>
</ul></div>
