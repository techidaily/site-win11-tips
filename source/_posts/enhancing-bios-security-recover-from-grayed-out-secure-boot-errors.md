---
title: "Enhancing BIOS Security: Recover From Grayed Out Secure Boot Errors"
date: 2024-10-29T16:45:51.709Z
updated: 2024-11-01T18:59:02.620Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Enhancing BIOS Security: Recover From Grayed Out Secure Boot Errors"
excerpt: "This Article Describes Enhancing BIOS Security: Recover From Grayed Out Secure Boot Errors"
keywords: SecureBootErrorRecovery,BIOSSecurityEnhancement,SecureBootFixingTips,BootingSystemSecured,ErrorGrayOutSolutions,SecurityBoostBIOS,FixedBootStatusUpdate
thumbnail: https://thmb.techidaily.com/270179364474a44da1eaeda7613c10f10260fff7aad4cae0d60acb9733eadc20.jpg
---

## Enhancing BIOS Security: Recover From Grayed Out Secure Boot Errors

 You need a secure boot-compatible computer to install Windows 11\. But there are other reasons to enable secure boot when available. It is a safety standard that prevents malicious codes from running on your PC during boot.

 But what if secure boot option is grayed out in BIOS? This can happen due to incorrect changes to your BIOS settings. You can load the default boot configuration to restore secure boot on Windows. Here is how to troubleshoot and fix the secure boot grayed-out problem in the BIOS.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

 Note that the fast boot feature is different from Fast Startup. Fast Boot is a BIOS feature, whereas[Fast Startup is a Windows feature to speed up the boot process](https://www.makeuseof.com/what-is-windows-fast-startup-why-disable-it/) .

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
4. Read the description in the**Security Feature Reset Request** dialog. Here you'll need to enter a pass code to complete the reset request.
5. So, enter the shown**pass code** and press**Enter** .  
![restore bios factory settings default pass code](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/restore-bios-factory-settings-default-pass-code.jpg)
6. Press**F10** to save the changes and exit**BIOS** .

7. Boot into BIOS again and check if the greyed-out secure boot problem is resolved.

## 4\. Update BIOS

![system information bios version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/system-information-bios.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043638/7443" target="_top" id="2043638">
  <img src="//a.impactradius-go.com/display-ad/7443-2043638" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043638/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the issue persists, your problem may be due to outdated BIOS firmware. While you don't need to update your system BIOS as frequently, the newer version tends to bring bug fixes, performance improvements, and newer hardware support.

 A BIOS update is recommended if your motherboard or laptop manufacturer recommends it. Any updates will be available via the laptop or motherboard manufacturer's websites.

<!-- affiliate ads begin -->
<span id="1983588">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983588.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983588">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983588.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983588%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983588/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Prepare Your Computer for a BIOS Update

 Before you update your BIOS, you'll need to[suspend BitLocker protection](https://www.makeuseof.com/windows-10-disable-or-suspend-bitlocker/) . You may also need to[temporarily turn off Windows Security protection](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) and third-party antivirus.

 Next, check your current BIOS version. You don't want to install an older version of BIOS on your computer. So, press the**Win** key, type**system information** , and open the System Information app from the search results. In the System Information dialog, locate and check the**BIOS Version/Date** entry. Note down the BIOS version, for example,**AMI F.27, 3/17/2022** .

 Unlike other driver and software feature updates, updating your BIOS can be tricky. You can update BIOS from within BIOS, where the BIOS Setup Utility can check your laptop manufacturer's website for BIOS updates. This option, however, is not available for all computers.

![HP download bios firmware update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hp-download-bios-firmware-update.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135404/19272" target="_top" id="2135404">
  <img src="//a.impactradius-go.com/display-ad/19272-2135404" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135404/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Alternatively, you can also manually install BIOS from within Windows. For example, on an HP computer, go to the[HP Drivers page](https://support.hp.com/drivers) . Select your device manually or let the website detect the device for you.

 Next, check for the pending drivers and BIOS updates. If detected, download the HP Notebook System BIOS Update (Intel / AMD Processors). Make sure to compare the version with the version installed on your PC. If same or older, you don't need to update your BIOS.

 To update BIOS, run the firmware file and follow the on-screen instructions. Your computer will restart into the BIOS Update utility. Select**Apply Update Now** and wait for the update to finish installing. Once done, boot into BIOS and check if the Secure Boot option is available. Make sure to enable your antivirus and BitLocker protection again.

## 5\. Load the BIOS Defaults Settings

![load BIOS default settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/load-bios-default-settings.jpg)

 You can restore your BIOS to its factory default settings to fix issues occurring due to corrupt BIOS configuration. While loading the default settings will not affect your data, we recommend you back up any and all the important data on your computer before proceeding with a BIOS reset.

To load BIOS defaults settings:

1. Boot into**BIOS** and open the**Exit** tab.
2. Next, select the**Load Setup Defaults** option and press**Enter** .
3. Select**Yes** and press**Enter** . This will load setup default values for all SETUP items.
4. Select**Save Changes** and**Exit** .
5. Boot into**BIOS** again and check if the secure boot option is restored.

<!-- affiliate ads begin -->
<span id="1484963">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1484963.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1484963">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1484963.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1484963%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1484963/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-how-to-set-up-and-use-the-grid-layout-for-zoom/"><u>[New] 2024 Approved How to Set Up and Use the Grid Layout for Zoom</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-2024-approved-free-passport-photography-made-simple-our-top-10-picks-list/"><u>[Updated] 2024 Approved Free Passport Photography Made Simple Our Top 10 Picks List</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-2024-approved-the-beginners-blueprint-for-winning-animation-in-windows/"><u>[Updated] 2024 Approved The Beginner’s Blueprint for Winning Animation in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combining-gmail-and-outlook-on-pc-easy-steps-included/"><u>Combining Gmail & Outlook on PC: Easy Steps Included</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/delete-gmail-account-withwithout-password-on-nokia-c12-pro-by-drfone-android/"><u>Delete Gmail Account With/Without Password On Nokia C12 Pro</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-honor-play-7t-drfone-by-drfone-virtual-android/"><u>Fixing Foneazy MockGo Not Working On Honor Play 7T | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-elevate-your-workflow-upgrade-virtualbox-to-version-70-for-w11-users/"><u>How To Elevate Your Workflow: Upgrade VirtualBox to Version 7.0 for W11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-file-or-directory-is-corrupted-error-0x80070570-on-windows-10-and-11/"><u>How to Fix the “File or Directory Is Corrupted” Error 0X80070570 on Windows 10 & 11</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-avoid-common-pitfalls-in-ppt-recording/"><u>In 2024, Avoid Common Pitfalls in PPT Recording</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-best-4k-monitors-for-mac-the-ultimate-list/"><u>In 2024, Best 4K Monitors for Mac - The Ultimate List</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-htc-u23-pro-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track HTC U23 Pro Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-sea-of-saving-and-restoring-sticky-notes/"><u>Navigating the Sea of Saving and Restoring Sticky Notes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-failed-application-setup-on-microsoft-store/"><u>Navigating Through Failed Application Setup on Microsoft Store</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/preserving-audio-integrity-techniques-for-altering-pitch-in-audacity/"><u>Preserving Audio Integrity Techniques for Altering Pitch in Audacity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-the-irritating-steam-error-code-e84/"><u>Quick Fixes for the Irritating Steam Error Code E84</u></a></li>
<li><a href="https://network-issues.techidaily.com/taming-the-turbulent-windows-11-screen/"><u>Taming the Turbulent Windows 11 Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-case-for-pc-top-9-arguments-against-macs/"><u>The Case for PC: Top 9 Arguments Against Macs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-quick-and-simple-guide-to-sticky-notes-in-win11/"><u>The Quick and Simple Guide to Sticky Notes in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-tech-mysteries-hardware-ids-in-windows-os/"><u>Unraveling Tech Mysteries: Hardware IDs in Windows OS</u></a></li>
</ul></div>

