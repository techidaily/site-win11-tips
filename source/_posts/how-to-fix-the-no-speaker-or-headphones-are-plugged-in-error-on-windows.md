---
title: How to Fix the No Speaker or Headphones Are Plugged In Error on Windows
date: 2024-12-09T23:02:21.779Z
updated: 2024-12-13T00:52:07.577Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the No Speaker or Headphones Are Plugged In Error on Windows
excerpt: This Article Describes How to Fix the No Speaker or Headphones Are Plugged In Error on Windows
keywords: Windows Audio Issue Resolution,Troubleshoot No Sound Windows,Headphones Error Windows Fix,Speaker Not Plugged PC Error,Windows No Input Device,Clearing Audio Glitches Win,Stop Headphone Connection Failures
thumbnail: https://thmb.techidaily.com/b59734d21ac4befa6d882d663a57d13f768195f331fa0eea08a7ad594a08d5e2.jpg
---

## How to Fix the No Speaker or Headphones Are Plugged In Error on Windows

 Sometimes, you may notice a red X on the sound icon on the Windows taskbar. If you hover the cursor over it, it shows a no speaker, or headphones are plugged in error. This error can occur due to issues with the audio driver or Windows audio services.

 To fix the error, run the built-in audio troubleshooter that can find and fix common audio issues with the sound device. If not, you can perform an audio driver rollback or manually reinstall the audio driver to restore your system's audio.

 Here are a few troubleshooting steps to help you fix the no speaker or headphones are plugged in error on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Run the Windows Audio Troubleshooter

 You can troubleshoot sound problems on Windows using the built-in audio troubleshooter. It scans your Windows system for common audio issues and tries to fix them automatically.

To run the troubleshooter:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, scroll down and click on**Troubleshoot** .
3. Next, click on**Other** **troubleshooters** .  
![Windows 11 troubleshoot other troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-troubleshoot-other-troubleshooter.jpg)
4. Click the**Run** button for**Playing Audio** . It will check your audio service status and prompt you to select your audio device.  
![Windows 11 settings troubleshoot other troubleshooters playing audio run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-settings-troubleshoot-other-troubleshooters-playing-audio-run.jpg)
5. Select your device speaker and click**Next** .

6. Click**NO** ,**Do not open Audio Enhancements** in the**Turn off Sound Effects and Enhancements** dialog.
7. Apply any recommended fixes and check for any improvements.

 If the troubleshooter left a good impression on you, check out our[guide to every troubleshooter on Windows 11](https://www.makeuseof.com/windows-11-troubleshooters/) for more of them.

## 2\. Perform an Audio Device Driver Rollback

 If a Windows or driver update has messed up your audio device, you can perform a driver rollback to reinstall the last known good driver. You can use the Device Manager to[roll back a driver in Windows](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) .

 To roll back an audio device driver, follow our guide on[how to roll back a driver in Windows](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) . You'll likely find your audio drivers in the**Sound, video, and game controllers** section of Device Manager.

## 3\. Add Network Service and Local Services to the Local Administrator Group

 Another way to fix this error is to add**Network service** and**Local Services** to the Local Administrator Group. Network Service and Local Service are predefined accounts part of the service control manager. Adding these accounts to the Local Administrator Group should help you fix the sound problem on your Windows PC.

 Note that Local Users and Groups is not available on the Windows Home edition. Home users, however, can add Network Service and Local Services to the local administrator group using Command Prompt.

 To add Network Service and Local Services to the Local Administrator Group using Local Users and Groups:

1. Press**Win + X** to open the**WinX** **Menu** .
2. Click on**Computer Management.**
3. In**Computer Management** , click on**Local User and Groups.**  
![computer management windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/computer-management-windows-11.jpg)
4. In the right pane, double-click on**Groups** to view all the local accounts.  
![local users and groups administrator properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/local-users-and-groups-administrator-properties.jpg)
5. Select and right-click on the**Administrators** account and select**Properties** .  
![administrator properties local users and groups](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/administrator-properties-local-users-and-groups.jpg)

1. Click the**Add** button in the**Administrator Properties** dialog.
2. ![administrator properties local users and groups](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/administrator-properties-local-users-and-groups.jpg)
3. Next, type**network service** and click**Check Names** . It should change the object name to**NETWORK SERVICE.**  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jvwX82j3ci0?si=gAWoovjXgs3m1d7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![add network service local administrator group](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/add-network-service-local-administrator-group.jpg)
4. Click**OK** to add network service to the local user group.

5. In the**Administrator Properties** dialog, you'll see**NT Authority\\Network Service added as the member.**
6. Click the**Add** button again and repeat the steps to add**Local Services** to the group as well.
7. Once done, click**Apply** and**OK** to save the changes.

 If you use the Windows Home edition, you can use Command Prompt to add Local Network and Local Services to the local administrator group. Here's how to do it.

![add network service local administrator group command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/add-network-service-local-administrator-group-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0OxkndZbIA4?si=TWJlkTbYKsVag8-q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Press the**Win** key and type**cmd** .
2. Right-click on**Command Prompt** and select**Run as administrator.**
3. In the Command Prompt window, type the following to add "local service" to the Local Group Administrator:  
`net localgroup Administrators /add localservice`
4. Next, type the following command to add "network service" to the Local Group Administrator account:  
`net localgroup Administrators /add networkservice`
5. If both the commands are executed successfully, type**exit** and press**Enter** to close Command Prompt.
6. Restart your PC and check if the error is resolved.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kTHQrw8e1gk?si=gTPIa7KjhSZ0Vz97" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Uninstall the Audio Device and Driver

 Temporary glitches with the audio device driver can cause this error on Windows. To fix the issue, uninstall the audio device and the associated driver from Device Manager. After the restart, Windows will automatically reinstall the driver to resolve the issue.

To uninstall an audio device:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Device Manager** from the context menu.
3. In Device Manager, expand the**Sound, video, and game controllers** section.
4. Right-click on your audio device, like**Realtek** **Audio** .  
![uninstall audio device device manager 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-audio-device-device-manager-1.jpg)
5. Select**Attempt to remove the driver for this device** option in the**Uninstall Device** dialog.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XoC2TGp1PLY?si=iH9xs76NhWn4pP-E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![uninstall audio device device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-audio-device-device-manager.jpg)
6. Click**Uninstall** to remove the device.

7. Once uninstalled, restart your PC. Windows will automatically install the necessary drivers for your audio device.

 If the issue persists, manually reinstall the audio device driver from the manufacturer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zWYVKFk3yPQ?si=Yu7xsjIYgRiq8zHk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Manually Reinstall the Audio Device Driver

 If the automatic reinstall doesn't work, check if your computer manufacturer or the audio device OEM has a stable driver version available. On a laptop, visit your computer manufacturer's website and download the latest audio drivers. On a desktop, you can download the latest drivers for your sound card from the manufacturer's website.

 Alternatively, you can also manually reinstall the existing drivers for your audio device. Check out[how to update Windows, Apps, and drivers](https://www.makeuseof.com/tag/update-windows-software-guide/) for more information.

 If the issue persists, change the device installation settings and then reinstall the driver. To change device installation settings:

![device installation settings windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/device-installation-settings-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15Ju8Cb4UZ8?si=5wdiQXdz1BOxIkDH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Press the**Win** key, and type**device installation settings.**
2. Next, click on**Change device installation settings** from the search result.
3. Select the**No (your device might not work as expected)** option in the**Device installation settings** dialog.
4. Click**Save Changes** . Click**Yes** if prompted by**User Account Control.**

 With the automatic driver download disabled, reinstall the existing driver to fix the no audio issue.

## Fixing the "No Speaker or Headphones Are Plugged In" Error

 The error often occurs due to a bad driver update. To fix it, you can perform a rollback or manually reinstall the audio device driver. In addition, try to update the audio device driver from the manufacturer's website.

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
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-unraveling-virtual-realitys-interactive-gear/"><u>[Updated] 2024 Approved Unraveling Virtual Reality's Interactive Gear</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-effortless-link-upload-on-instagrams-social-sphere/"><u>[Updated] Effortless Link Upload on Instagram's Social Sphere</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-in-2024-air-vs-pro-with-m1-optimal-laptop-for-your-needs/"><u>[Updated] In 2024, Air Vs. Pro with M1 Optimal Laptop for Your Needs?</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-champions-5-wearable-devices-for-top-fpv-racing/"><u>2024 Approved Champion's 5 Wearable Devices for Top FPV Racing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-edge-methods-for-heic-to-jpeg-switch-on-windows-11/"><u>Cutting-Edge Methods for Heic to JPEG Switch on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-video-output-fixing-black-webcam-display/"><u>Enhancing Video Output: Fixing Black Webcam Display</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-uses-for-microsofts-vcplusplus-distribute/"><u>Exploring Uses for Microsoft's VC++ Distribute</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-go-incognito-with-admin-credentials-on-windows-11/"><u>How to Go Incognito with Admin Credentials on Windows 11</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-install-the-epson-xp-400-printer-drivers-a-complete-guide/"><u>How to Install the Epson XP-400 Printer Drivers: A Complete Guide</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-a-vivo-t2-5g-easily-by-drfone-android/"><u>How To Unlock a Vivo T2 5G Easily?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-your-windows-experience-with-unseen-functionalities-from-vivetool/"><u>Maximize Your Windows Experience with Unseen Functionalities From ViVeTool</u></a></li>
<li><a href="https://hardware-help.techidaily.com/prepare-to-be-amazed-by-the-power-of-intels-newest-ai-chip-in-upcoming-laptop-models-discover-all-the-spectacular-perks-techreviewzen/"><u>Prepare to Be Amazed by the Power of Intel's Newest AI Chip in Upcoming Laptop Models - Discover All the Spectacular Perks! | TechReviewZen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-chrome-repair-for-windows-sudden-closure-errors/"><u>Quick Chrome Repair for Windows' Sudden Closure Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/route-to-administrator-rights-on-window-control-hub/"><u>Route to Administrator Rights on Window Control Hub</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-rectifying-cannot-link-with-nvidia-error-in-windows/"><u>Steps for Rectifying Cannot Link with NVIDIA Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-command-prompt-with-elevated-authority-in-windows-11/"><u>The Ultimate Guide to Command Prompt with Elevated Authority in Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-telegram-spy-tools-on-tecno-phantom-v-fold-for-parents-drfone-by-drfone-virtual-android/"><u>Top 10 Telegram Spy Tools On Tecno Phantom V Fold for Parents | Dr.fone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/troubleshooting-and-fixing-samsung-printer-drivers-on-windows-a-comprehensive-guide/"><u>Troubleshooting and Fixing Samsung Printer Drivers on Windows: A Comprehensive Guide</u></a></li>
<li><a href="https://facebook.techidaily.com/why-leaving-no-footprint-on-facebook-is-smart/"><u>Why Leaving No Footprint on Facebook Is Smart</u></a></li>
</ul></div>

