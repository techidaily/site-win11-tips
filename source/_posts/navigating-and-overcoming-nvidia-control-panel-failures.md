---
title: Navigating and Overcoming Nvidia Control Panel Failures
date: 2024-12-07T22:27:49.865Z
updated: 2024-12-12T19:59:36.734Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating and Overcoming Nvidia Control Panel Failures
excerpt: This Article Describes Navigating and Overcoming Nvidia Control Panel Failures
keywords: Nvidia CP Fix Guide,Nvidia CP Troubleshooting,Nvidia CP Recovery Tips,CP Nvidia Repair Steps,Resolving Nvidia Control Panel,Stop Nvidia Control Errors,Restoring Failed Nvidia CP
thumbnail: https://thmb.techidaily.com/095ce3d3eacef166f46f59459d5ef71a92a706285f3160a9b70eb170ae6406f1.jpg
---

## Navigating and Overcoming Nvidia Control Panel Failures

 The NVIDIA Control Panel is an app included on PCs with NVIDIA GPUs with which users can change graphical settings. However, some users can’t change NVIDIA Control Panel options because of an “Access denied” error. The message of that error says, “Failed to apply selected settings to your system.”

 The “Access denied” error is mostly reported to arise for 3D settings. As a result, NVIDIA Control Panel doesn’t apply (save) the settings users select. This is how you can resolve NVIDIA Control Panel’s “Access denied” error within Windows 11/10.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Run the NVIDIA Control Panel as an Administrator

 Firstly, try running the NVIDIA Control Panel with elevated admin permissions, which has worked for some users. To do that, press the**Windows** logo +**S** keyboard buttons and input NVIDIA Control Panel. Right-click NVIDIA Control Panel and select**Run as administrator** .

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-as-administrator-option2.jpg)

 Should this potential fix work, then it would be better to set the NVIDIA Control Panel to always run with administrative rights. However, that UWP app is located within a protected folder. You’ll need to[take ownership of the WindowsApps folder](https://www.makeuseof.com/windows-10-11-own-folder/) to set permanent admin rights for the NVIDIA Control Panel.

 If you take ownership of the WindowsApps folder, open the NVIDIACorp subfolder to reach the NVIDIA Control Panel file. Then you’ll need to set the nvcplui.exe file to run with admin rights. Follow the steps in this how to[set an app to always run as an administrator guide](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) to set elevated permissions for the nvcplui.exe file. The path for the NVIDIA Control Panel folder is:

`C:\Program Files\WindowsApps\NVIDIACorp.NVIDIAControlPanel_8.1.964.0_x64__56jybvy8sckqj`

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qn1XkPJde9Y?si=i6ZJARXO8sJhy2FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Select the Repair and Reset Options for the NVIDIA Control Panel

 The NVIDIA Control Panel app has**Repair** and**Reset** troubleshooting options you can select in Settings. Both options can be useful for fixing apps when they’re not working right. So, try selecting the**Repair** option first and then**Reset** to clear the app’s data if repairing isn’t enough. Check out this[article about resetting apps in Windows](https://www.makeuseof.com/windows-reset-app/) for details about how to apply this potential fix.

![The Repair and Reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-reset-options.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-yZKNLxj3po?si=-RbF6nCJEVlHWP-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Start or Restart the NVIDIA Display Container Service

 The NVIDIA Display Container is an important GPU service that runs numerous other NVIDIA background tasks. Make sure that service is running or restart it if it is. You can start or restart NVIDIA Display Container like this:

1. Click the**Type here to search** button or the Search box on the taskbar to access the Windows file finder tool.
2. Input**services** inside the file search utility.
3. Select**Services** to launch that app.
4. Then double-click**NVIDIA Display Container** to view the settings for that service.  
![The Services app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-services-app.jpg)  
 Screenshot captured by Jack Slater - No attribution required
5. Click on the**Startup type** menu and select**Automatic** from there.
6. Next, select**Start** if the NVIDIA Display Container service is stopped. Or select**Stop** \>**Start** to restart that service.  
![The NVIDIA Display Container service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/nvidia-display-container-service.jpg)
7. Click**Apply** to set the NVIDIA Display Container service’s settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0OxkndZbIA4?si=TWJlkTbYKsVag8-q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

8. Close the NVIDIA Display Container Properties window by clicking**OK** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Update Your NVIDIA Graphics Card Driver

 The most widely confirmed fix for the “Access denied” error is to manually update the NVIDIA graphics driver. Thus, this is often an issue caused by outdated or faulty NVIDIA drivers. This[guide to updating NVIDIA drivers](https://www.makeuseof.com/how-update-nvidia-graphics-card-drivers-windows/) provides further details about how to apply this potential solution by manually downloading the latest GPU driver available from the NVIDIA site.

 When you’ve downloaded the latest NVIDIA driver package for your GPU, bring up the directory that includes its setup file. Double-click the NVIDIA driver package file to view its setup wizard and select the**Custom** option. Then select the**Perform a clean installation** checkbox and click**Next** to install.

![The Perform a clean installation checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/perform-a-clean-installation.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jf0JvOqiAXc?si=kHEHQGC_PhBv4xij" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Roll Back the NVIDIA Driver

 If the “Access denied” error arises after installing a new NVIDIA driver, rolling back that driver to a previous one could be a viable potential solution. You’ll only be able to do that if the previous NVIDIA GPU driver file is still available. Our[article about rolling back drivers](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) includes guidelines for how to apply this potential fix.

 If the**Roll Back** option is grayed out, you might still be able to roll back to a previous NVIDIA graphics driver with the System Restore utility. Rolling Windows back to a restoration point restores drivers installed before the selected date. However, that will only work if your PC has a restore point that predates the driver update.

![The Roll Back Driver button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/roll-back-driver-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c17xsnbinCQ?si=xHKslFgC3QbxY4qW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This[post about creating and utilizing restore points](https://www.makeuseof.com/windows-11-create-restore-point/) tells you how to roll back Windows. Select a restore point that will restore the previous NVIDIA graphics driver. You can click**Scan for affected** programs in System Restore to check if a chosen restoration point will restore an NVIDIA graphics driver.

## 6\. Restore a Previous Version of the DRS Folder

 Some NVIDIA Control Panel users have said they fixed the “Access denied” error by restoring a DRS folder version backup. Note that you’ll only be able to apply this potential fix if you’ve got File History enabled or restore points saved on your PC. This is how you can restore a previous DRS folder version in Windows 11/10:

1. First, bring up File Explorer by clicking the taskbar button with the folder library icon.
2. Then click the**View** button to select a**Show** option.
3. Select the**Hidden Items** option.  
![The Hidden items checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hidden-items-option.jpg)
4. Clear Explorer’s address bar to input the following path:  
`C:\ProgramData\NVIDIA Corporation`
5. Then right-click the DRS folder and select**Properties** .
6. Click the**Previous Versions** tab.  
![The Previous Versions tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/previous-version-tab.jpg)
7. Select the most recent folder version shown in that tab.
8. Click the**Restore** button.

 To select the same**Hidden Items** option in Windows 10, you’ll need to open the**View** tab in Explorer. Then select the checkbox labeled**Hidden Items** on that tab.

## 7\. Turn Off the Game Bar

 It’s also recommended to turn off the Game Bar in case that’s causing any issues with the NVIDIA Control Panel. This potential resolution applies more to Windows 10 since Windows 11’s Settings app doesn’t include a specific option for disabling the Game Bar. You can turn off the Game Bar in Windows 10 like this:

1. Open Settings by clicking the cog icon on the Start menu.
2. Click the**Gaming** category.
3. Then turn off the**Enable Xbox Game Bar** option.  
![The Xbox Game Bar setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-xbox-game-bar-option.jpg)

## Change Your Settings in the NVIDIA Control Panel Again

 Many users have resolved NVIDIA Control Panel’s “Access denied” error with the potential fixes covered above. So, the probability one of them will also fix that issue on your PC is good. With that issue sorted, you can change all settings in the NVIDIA Control Panel as required.

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
<li><a href="https://instagram-video-files.techidaily.com/new-7-critical-practices-for-controlling-instagram-tv-videosize-for-2024/"><u>[New] 7 Critical Practices for Controlling Instagram TV Videosize for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-instagram-video-orientation-whats-the-flip/"><u>[Updated] In 2024, Instagram Video Orientation - What's the Flip?</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-pinpointing-the-leading-10-secret-story-supporters-for-2024/"><u>[Updated] Pinpointing the Leading 10 Secret Story Supporters for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-unlock-the-power-to-create-personalized-whatsapp-alerts/"><u>[Updated] Unlock the Power to Create Personalized WhatsApp Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delving-into-disabling-gpgpu-task-prioritization-windows-wise/"><u>Delving Into Disabling GPGPU Task Prioritization Windows-Wise</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/direct3d-launcher-fixes-in-effect/"><u>Direct3D Launcher Fixes in Effect</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-computer-experience-top-10-must-know-powertoy-features/"><u>Elevate Your Computer Experience: Top 10 Must-Know PowerToy Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixes-for-endless-stuck-in-bios-during-windows-boot-up/"><u>Fixes for Endless Stuck in BIOS During Windows Boot-Up</u></a></li>
<li><a href="https://change-location.techidaily.com/full-guide-to-catch-100-iv-pokemon-using-a-map-on-samsung-galaxy-s23-ultra-drfone-by-drfone-virtual-android/"><u>Full Guide to Catch 100 IV Pokémon Using a Map On Samsung Galaxy S23 Ultra | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-frp-on-nokia-c02-by-drfone-android/"><u>How to Bypass FRP on Nokia C02?</u></a></li>
<li><a href="https://fox-direct.techidaily.com/how-to-transfer-photos-and-videos-from-iphone-to-iphone-for-2024/"><u>How to Transfer Photos and Videos From iPhone to iPhone for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-your-android-for-windows-11-webcam-functionality/"><u>Leveraging Your Android for Windows 11 Webcam Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/method-for-altering-reset-counter-after-failed-logins/"><u>Method for Altering Reset Counter After Failed Logins</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-final-cut-pro-x-captioning-a-step-by-step-guide-for-2024/"><u>New Final Cut Pro X Captioning A Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-user-experience-adding-shortcut-keys-for-wordpad-to-windows-ui/"><u>Personalizing User Experience: Adding Shortcut Keys for Wordpad to Windows UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sudos-arrival-streamlining-windows-tasks/"><u>Sudo's Arrival: Streamlining Windows Tasks</u></a></li>
</ul></div>

