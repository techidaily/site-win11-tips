---
title: "Addressing Nvidia Panel Errors: Win11/10 Fixes"
date: 2024-07-03T12:47:23.623Z
updated: 2024-07-04T12:47:23.623Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Addressing Nvidia Panel Errors: Win11/10 Fixes"
excerpt: "This Article Describes Addressing Nvidia Panel Errors: Win11/10 Fixes"
keywords: Nvidia Panel Troubleshoot,Win11 Panel Fix,Win10 GPU Issues,Nvidia Freeze Errors,Repair Panel Glitches,Resolve PCIe Graphics,Update Windows Graphics
thumbnail: https://thmb.techidaily.com/5961427253350c1b74e1650e9c2f8a99858d6dfe3a81786842ed520231401b1b.jpg
---

## Addressing Nvidia Panel Errors: Win11/10 Fixes

 The NVIDIA Control Panel is an app included on PCs with NVIDIA GPUs with which users can change graphical settings. However, some users can’t change NVIDIA Control Panel options because of an “Access denied” error. The message of that error says, “Failed to apply selected settings to your system.”

 The “Access denied” error is mostly reported to arise for 3D settings. As a result, NVIDIA Control Panel doesn’t apply (save) the settings users select. This is how you can resolve NVIDIA Control Panel’s “Access denied” error within Windows 11/10.

## 1\. Run the NVIDIA Control Panel as an Administrator

 Firstly, try running the NVIDIA Control Panel with elevated admin permissions, which has worked for some users. To do that, press the**Windows** logo +**S** keyboard buttons and input NVIDIA Control Panel. Right-click NVIDIA Control Panel and select**Run as administrator** .

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-as-administrator-option2.jpg)

 Should this potential fix work, then it would be better to set the NVIDIA Control Panel to always run with administrative rights. However, that UWP app is located within a protected folder. You’ll need to [take ownership of the WindowsApps folder](https://www.makeuseof.com/windows-10-11-own-folder/) to set permanent admin rights for the NVIDIA Control Panel.

 If you take ownership of the WindowsApps folder, open the NVIDIACorp subfolder to reach the NVIDIA Control Panel file. Then you’ll need to set the nvcplui.exe file to run with admin rights. Follow the steps in this how to [set an app to always run as an administrator guide](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) to set elevated permissions for the nvcplui.exe file. The path for the NVIDIA Control Panel folder is:

`C:\Program Files\WindowsApps\NVIDIACorp.NVIDIAControlPanel_8.1.964.0_x64__56jybvy8sckqj`

## 2\. Select the Repair and Reset Options for the NVIDIA Control Panel

 The NVIDIA Control Panel app has**Repair** and**Reset** troubleshooting options you can select in Settings. Both options can be useful for fixing apps when they’re not working right. So, try selecting the**Repair** option first and then**Reset** to clear the app’s data if repairing isn’t enough. Check out this [article about resetting apps in Windows](https://www.makeuseof.com/windows-reset-app/) for details about how to apply this potential fix.

![The Repair and Reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-reset-options.jpg)

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
8. Close the NVIDIA Display Container Properties window by clicking**OK** .

## 4\. Update Your NVIDIA Graphics Card Driver

 The most widely confirmed fix for the “Access denied” error is to manually update the NVIDIA graphics driver. Thus, this is often an issue caused by outdated or faulty NVIDIA drivers. This [guide to updating NVIDIA drivers](https://www.makeuseof.com/how-update-nvidia-graphics-card-drivers-windows/) provides further details about how to apply this potential solution by manually downloading the latest GPU driver available from the NVIDIA site.

 When you’ve downloaded the latest NVIDIA driver package for your GPU, bring up the directory that includes its setup file. Double-click the NVIDIA driver package file to view its setup wizard and select the**Custom** option. Then select the**Perform a clean installation** checkbox and click**Next** to install.

![The Perform a clean installation checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/perform-a-clean-installation.jpg)

## 5\. Roll Back the NVIDIA Driver

 If the “Access denied” error arises after installing a new NVIDIA driver, rolling back that driver to a previous one could be a viable potential solution. You’ll only be able to do that if the previous NVIDIA GPU driver file is still available. Our [article about rolling back drivers](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) includes guidelines for how to apply this potential fix.

 If the**Roll Back** option is grayed out, you might still be able to roll back to a previous NVIDIA graphics driver with the System Restore utility. Rolling Windows back to a restoration point restores drivers installed before the selected date. However, that will only work if your PC has a restore point that predates the driver update.

![The Roll Back Driver button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/roll-back-driver-option.jpg)

 This [post about creating and utilizing restore points](https://www.makeuseof.com/windows-11-create-restore-point/) tells you how to roll back Windows. Select a restore point that will restore the previous NVIDIA graphics driver. You can click**Scan for affected** programs in System Restore to check if a chosen restoration point will restore an NVIDIA graphics driver.

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
<li><a href="https://win11-tips.techidaily.com/securing-smooth-file-transfers-tips-and-tricks-for-windows-users/"><u>Securing Smooth File Transfers: Tips & Tricks for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-curtail-pc-sound-enhancement-effects/"><u>How To Curtail PC Sound Enhancement Effects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-your-windows-notes-prominent/"><u>Keeping Your Windows Notes Prominent</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719258280599-jump-over-the-endless-update-hurdle-quick-fixes-now/"><u>Jump Over The Endless Update Hurdle: Quick Fixes Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-boosting-virtualbox-version-70-on-windows-11/"><u>Step-by-Step Guide: Boosting VirtualBox Version 7.0 on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-enabling-task-managers-quick-find-feature-on-win11/"><u>Step-by-Step Guide: Enabling Task Manager's Quick Find Feature on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-path-to-reinstating-default-windows-backups/"><u>The Path to Reinstating Default Windows Backups</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-setting-up-success-crafting-your-first-youtube-channel/"><u>[Updated] Setting Up Success  Crafting Your First YouTube Channel</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-efficient-practices-logging-google-voice-dialogues/"><u>[Updated] In 2024, Efficient Practices  Logging Google Voice Dialogues</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-instantize-dynamic-images-in-photoshop/"><u>[New] Instantize Dynamic Images in Photoshop</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-navigating-the-hottest-templates-in-igs-vfx-community/"><u>2024 Approved  Navigating the Hottest Templates in IG's VFX Community</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-watch-hulu-outside-us-on-vivo-g2-drfone-by-drfone-virtual-android/"><u>How to Watch Hulu Outside US On Vivo G2 | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-samsung-galaxy-a14-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some Pro Tips for Pokemon Go PvP Battles On Samsung Galaxy A14 5G | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/unleashing-the-power-of-structured-chapters-in-online-video-creation/"><u>Unleashing the Power of Structured Chapters in Online Video Creation</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-infinix-note-30-phone-password-without-factory-reset-by-drfone-android/"><u>How to Unlock Infinix Note 30 Phone Password Without Factory Reset?</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-clash-for-dominance-leading-royale-games/"><u>2024 Approved  Clash for Dominance  Leading Royale Games</u></a></li>
</ul></div>
