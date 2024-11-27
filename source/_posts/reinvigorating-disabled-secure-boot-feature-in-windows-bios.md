---
title: Reinvigorating Disabled Secure Boot Feature in Windows BIOS
date: 2024-11-21T16:21:29.002Z
updated: 2024-11-27T16:18:52.780Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reinvigorating Disabled Secure Boot Feature in Windows BIOS
excerpt: This Article Describes Reinvigorating Disabled Secure Boot Feature in Windows BIOS
keywords: Secure Boot for Disabled,Reinvigorate BIOS Boot,Disability Support Windows,Enhanced BIOS Security,Improve Secure Boot Feature,Revamping BIOS Accessibility,Boosting Windows Secure Boot
thumbnail: https://thmb.techidaily.com/0aeedb6f0e08290ddfa4945f77d0426cb986cac7f0c8ef179d1c62c13237705d.jpg
---

## Reinvigorating Disabled Secure Boot Feature in Windows BIOS

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kTHQrw8e1gk?si=gTPIa7KjhSZ0Vz97&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aYH0B2HqcIM?si=3fkoG85L6hAeB4ok&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Boot into BIOS again and check if the greyed-out secure boot problem is resolved.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X4q6gyaEojM?si=ImdFm6Zsr0azykqV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Update BIOS

![system information bios version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/system-information-bios.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VlwHTQQMs?si=BXYwD1pKiaTuev4y&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the issue persists, your problem may be due to outdated BIOS firmware. While you don't need to update your system BIOS as frequently, the newer version tends to bring bug fixes, performance improvements, and newer hardware support.

 A BIOS update is recommended if your motherboard or laptop manufacturer recommends it. Any updates will be available via the laptop or motherboard manufacturer's websites.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Prepare Your Computer for a BIOS Update

 Before you update your BIOS, you'll need to[suspend BitLocker protection](https://www.makeuseof.com/windows-10-disable-or-suspend-bitlocker/) . You may also need to[temporarily turn off Windows Security protection](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) and third-party antivirus.

 Next, check your current BIOS version. You don't want to install an older version of BIOS on your computer. So, press the**Win** key, type**system information** , and open the System Information app from the search results. In the System Information dialog, locate and check the**BIOS Version/Date** entry. Note down the BIOS version, for example,**AMI F.27, 3/17/2022** .

 Unlike other driver and software feature updates, updating your BIOS can be tricky. You can update BIOS from within BIOS, where the BIOS Setup Utility can check your laptop manufacturer's website for BIOS updates. This option, however, is not available for all computers.

![HP download bios firmware update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hp-download-bios-firmware-update.jpg)

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
<li><a href="https://facebook-video-content.techidaily.com/new-becoming-a-seo-guru-top-ten-facebook-optimization-tactics-for-2024/"><u>[New] Becoming a SEO Guru Top Ten Facebook Optimization Tactics for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-boosting-webcam-quality-with-ease-and-precision/"><u>[New] Boosting WebCam Quality with Ease and Precision</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/mmediate-hit-list-top-10-videos-watched-first-hour/"><u>[New] Immediate Hit List Top 10 Videos Watched First Hour</u></a></li>
<li><a href="https://youtube-web.techidaily.com/n-2024-from-clicks-to-cash-the-journey-of-youtubes-ajay-nagar/"><u>[New] In 2024, From Clicks to Cash The Journey of YouTube's Ajay Nagar</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-unveiling-the-most-honest-youtube-growth-services-for-2024/"><u>[Updated] Unveiling the Most Honest Youtube Growth Services for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicate-error-a00f425d-on-windows-camera-application/"><u>Eradicate Error A00F425D on Windows Camera Application</u></a></li>
<li><a href="https://howto.techidaily.com/fix-app-not-available-in-your-country-play-store-problem-on-honor-magic-6-lite-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix App Not Available in Your Country Play Store Problem on Honor Magic 6 Lite | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harnessing-the-power-of-winstall-for-swift-grouped-app-deployments-on-windows-11/"><u>Harnessing the Power of Winstall for Swift Grouped App Deployments on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-restore-functionality-of-cortana-on-latest-version-windows-11/"><u>How to Restore Functionality of Cortana on Latest Version Windows 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-tecno-pova-5-to-pc-drfone-by-drfone-android/"><u>How to Screen Mirroring Tecno Pova 5 to PC? | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-quickrestore-reviewers-thoughts/"><u>In 2024, QuickRestore Reviewers Thoughts</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-ultimate-uav-upgrade-path-key-parts-and-add-ons/"><u>In 2024, The Ultimate UAV Upgrade Path Key Parts and Add-Ons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-one-side-windows-earbud-sound-issue/"><u>Mending One-Side Windows Earbud Sound Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-white-screen-on-microsoft-appstore/"><u>Overcoming White Screen on Microsoft Appstore</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/pc-peace-stop-the-fallout-4-crash-cases/"><u>PC Peace: Stop the Fallout 4 Crash Cases</u></a></li>
<li><a href="https://win11-tips.techidaily.com/repairing-voice-commands-xbox-and-windows-harmony/"><u>Repairing Voice Commands: Xbox & Windows Harmony</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-the-functionality-of-windows-11-calendar/"><u>Understanding the Functionality of Windows 11 Calendar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-complexity-of-html-in-windows-11s-default-mail-settings/"><u>Unraveling the Complexity of HTML in Windows 11'S Default Mail Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrading-pin-length-in-modern-windows/"><u>Upgrading PIN Length in Modern Windows</u></a></li>
</ul></div>

