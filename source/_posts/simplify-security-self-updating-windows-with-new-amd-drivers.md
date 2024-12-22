---
title: "Simplify Security: Self-Updating Windows with New AMD Drivers"
date: 2024-12-20T16:22:12.756Z
updated: 2024-12-21T22:14:02.346Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Simplify Security: Self-Updating Windows with New AMD Drivers"
excerpt: "This Article Describes Simplify Security: Self-Updating Windows with New AMD Drivers"
keywords: Simplified Windows Security,AMD Driver Updates,Self-Updating Windows,Enhanced Windows Safety,Secure Windows OS,New AMD Drivers,Automated Windows Update
thumbnail: https://thmb.techidaily.com/36f771b0e455ffd27a9b597a4a43e9338a94fa4efcb33fd8811a101c2c676422.png
---

## Simplify Security: Self-Updating Windows with New AMD Drivers

 AMD Software Adrenaline Edition on Windows lets you manage your AMD graphics card, game stats, perform driver updates, and more. Sometimes, after an update, it may fail to launch with the error Windows update has replaced your AMD graphics driver.

 The full error reads Windows update may have automatically replaced your AMD graphics driver. This error is due to a conflict between the AMD Software Adrenaline Edition driver and the UWP AMD graphics driver installed by Windows.

 To fix the problem, you’ll need to stop Windows from installing AMD Radeon drivers automatically and perform a manual reinstall. Here’s how to do it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2ipTu54inBo?si=gRegjvtVq5gm_PHo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Does Windows Automatically Replace Your AMD Graphics Drivers?

 By default, the Windows operating system installs the[Microsoft Basic Display Adapter](https://www.makeuseof.com/microsoft-basic-display-adapter-guide/) during the initial setup. It provides display graphics capabilities so that you can set up your new computer and install the necessary drivers.

 This basic display driver lets you configure your discrete graphics with the latest drivers using AMD Software. It also acts as a backup when your discrete GPU driver faults causing[black screen issues on Windows](https://www.makeuseof.com/fix-black-screen-on-windows-10-11/) .

 However, this error occurs when Windows updates install the UWP (Universal Windows Platform) driver for your AMD Radeon GPU. Since two versions of the same driver are installed, when you try to open the AMD Software Adrenaline Edition app it will trigger an error.

 AMD has addressed this issue and provided a quick fix. To fix the error, you'll need to stop Windows from automatically installing the AMD graphics drivers. Then, reinstall the AMD graphics driver using AMD software.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Roll Back the AMD Graphics Driver

![amd radeon display adapter driver roll back](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/amd-radeon-display-adapter-driver-roll-back.jpg)

 An easy way to fix Windows replacing your AMD graphics error is to roll back the AMD graphics driver. A driver rollback removes the current driver and reinstalls the previous version saved on your computer. Fortunately, you can[roll back device drivers using the Windows Device Manager](http://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) .

 In Device Manager, look for and expand the**Display Adapters** section. Here, select the**AMD Radeon (TM) graphics** device and perform a driver rollback. Once done, restart your computer and check for any improvements. If the**Roll Back Driver** option is greyed out, you can't perform a rollback for the selected device.

 Once the error is resolved, you'll need to stop Windows from automatically downloading AMD drivers. If not, you’ll likely encounter the same error after each Windows update.

 You can[stop automatic driver updates on Windows](https://www.makeuseof.com/windows-stop-automatic-driver-updates/) using device installation settings,**Group Policy Editor** , and the**Windows Registry** . With the device installation settings for automatic driver download set to off, Windows won't download and install AMD graphics drivers automatically.

## 2\. Repair and Reinstall the AMD Software Driver

![amd radeon software installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/amd-radeon-software-installer.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/d-COuhPT5mk?si=wLZU6jkkAdJuAn6h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can reinstall the AMD Software driver using the existing driver. This may fix temporary issues with the driver causing the conflict. Follow these steps to repair and reinstall the AMD graphics driver:

1. Press**Win + E** to open File Explorer and navigate to the following location:  
`C:\AMD\RadeonInstaller\RadeonInstaller\Radeon_Folder_with_verison_name`
2. Next, double-click to run the**Setup.exe** file.  
![run amd setup exe repair graphics driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/run-amd-setup-exe-repair-graphics-driver.jpg)
3. In the**AMD Radeon Software Installer** dialog, select the driver version to install.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xa2_mFu-obA?si=_xDGF1pv-dnuaDOr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Click**Install** and wait for the driver to install.

 If you encounter an AMD error 195, temporarily[disable Windows Defender Firewall](https://www.makeuseof.com/how-to-turn-off-windows-defender/) and**Real-Time Threat Protection** and try again.

## 3\. Reinstall the AMDSoftware Graphics Driver

![amd software adrenaline edition uninstall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/amd-software-adrenaline-edition-uninstall.jpg)

 If the issue persists, try to remove and reinstall the AMD Software graphics driver. Once uninstalled, you can download the latest driver using the AMD Software.

To uninstall the AMD graphics driver:

1. Press**Win + I** to open**Settings** .
2. Open the**Apps** tab and click**Installed Apps** .
3. Next, search for**AMD Software** .  
![unisntall amd graphics driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/unisntall-adm-graphics-driver.jpg)
4. Click**Uninstall** and then**Uninstall** again to confirm the action.
5. Select**AMD Radeon Graphics** and click**Uninstall** .

 The AMD Software will start removing the driver from your computer. This process may take some time, and your monitor or display may flicker during the process. If it does, don't fret; it's just Windows getting used to the changes to your display drivers.

 Once done, click on**Finish** and restart your PC.

 When you uninstall a display driver, your secondary monitor can stop working. This will happen if your monitor's HDMI cable is directly connected to the port on your dedicated graphics unit. Your secondary display should work again as you reinstall the graphics driver.

 After the restart, you can[update your AMD Radeon graphics driver](https://www.makeuseof.com/update-amd-radeon-graphics-driver-windows-11/) using AMD Software. Install the driver and restart your PC to see if the error is resolved.

## 4\. Use a System Restore Point

 A restore point helps you recover your computer when a bad Windows update or driver installation causes the system to malfunction. You can use a restore point to undo the changes without affecting your data and files.

 Unfortunately, using a System Restore point requires you made one in the past. If you haven't made any, now's a good time to get into the habit of making them. Check out[how to make a System Restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) for more information.

To undo the recent changes using a restore point:

1. Press**Win + R** to open**Run** .
2. Type**rstrui.exe** and click**OK** .  
![select restore point](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/select-restore-point.jpg)
3. In the**System Restore** dialog, select the**Recommended** **restore** option. If not, select the**Choose a different restore point** option**.**
4. Select a**restore point** and click**Next** .  
![select restore point windows 11 finish](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/select-restore-point-windows-11-finish.jpg)
5. Read the description and click**Finish** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JlX-G8rBs1w?si=iIhUoWAq5x3YK9rA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. System Restore will restart and restore your PC to the state it was in before the date of the selected restore point.

## Fixing the Windows Update May Have Automatically Replaced Your AMD Driver

 This error occurs if multiple versions of the same AMD Radeon graphics driver are installed on your computer. To fix the issue, perform a driver rollback for your AMD Radeon graphics in Device Manager. Once done, change the device installation setting to prevent Windows from automatically installing the OEM driver for your GPU.

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
<li><a href="https://instagram-video-recordings.techidaily.com/new-20plus-secrets-to-insta-wonderful-videos-for-2024/"><u>[New] 20+ Secrets to Insta-Wonderful Videos for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-elevate-video-consumption-constructing-an-ideal-watch-later-list-on-youtube/"><u>[New] 2024 Approved Elevate Video Consumption Constructing an Ideal 'Watch Later' List on YouTube</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-steps-to-ensure-peaceful-gmeet-sessions-silence-techniques/"><u>[New] In 2024, Steps to Ensure Peaceful GMeet Sessions Silence Techniques</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-simple-approach-to-getting-clownfish-voice-changer-on-windows/"><u>2024 Approved Simple Approach to Getting Clownfish Voice Changer on Windows</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-the-top-8-sites-for-sharing-and-downloading-free-3d-text-psds/"><u>2024 Approved The Top 8 Sites for Sharing and Downloading Free 3D Text PSDs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combat-snip-and-sketch-failures-a-guide-to-capturing-entire-display/"><u>Combat Snip & Sketch Failures: A Guide to Capturing Entire Display</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-the-noisy-disruptor-win1011s-error-0xc00d36b4/"><u>Correcting the Noisy Disruptor: Win10/11's Error 0Xc00d36b4</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/expertly-curated-the-best-7-alarm-clock-applications-for-you/"><u>Expertly Curated: The Best 7 Alarm Clock Applications for You</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-microsoft-ai-transforms-online-marketplaces/"><u>How Microsoft AI Transforms Online Marketplaces</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ideal-android-software-syncing-with-windows-devices/"><u>Ideal Android Software Syncing With Windows Devices</u></a></li>
<li><a href="https://some-techniques.techidaily.com/immerse-in-fun-the-top-samsung-gear-vr-games-for-2024/"><u>Immerse in Fun The Top Samsung Gear VR Games for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/intel-command-center-stream-your-gameplays-seamlessly/"><u>Intel Command Center: Stream Your Gameplays Seamlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-loading-unsigned-drivers-despite-sie/"><u>Mastering Windows: Loading Unsigned Drivers Despite SIE</u></a></li>
<li><a href="https://blog-min.techidaily.com/reduction-de-taille-optimale-pour-les-videos-hd-4k-et-8k-diminution-jusqua-90-comment-le-faire/"><u>Réduction De Taille Optimale Pour Les Vidéos HD, 4K Et 8K : Diminution Jusqu'à 90% - Comment Le Faire?</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-to-overcome-update-error-0xc1900208-in-windows-11/"><u>Step-by-Step Solutions to Overcome Update Error 0xC1900208 in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/successfully-integrating-office-works-into-win11/"><u>Successfully Integrating Office Works Into Win11</u></a></li>
<li><a href="https://common-error.techidaily.com/the-definitive-guide-resolving-the-d3derrnotavailable-error-on-your-pc/"><u>The Definitive Guide: Resolving the D3DERR_NOTAVAILABLE Error on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-windows-11-operation-with-superior-run-capabilities/"><u>Transforming Windows 11 Operation with Superior Run Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncomplicated-office-integration-in-windows-10-and-11/"><u>Uncomplicated Office Integration in WIndows 10 & 11</u></a></li>
</ul></div>

