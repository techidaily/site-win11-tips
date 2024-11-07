---
title: "Step-by-Step: Rectifying Windows 11/10 Nvidia Errors"
date: 2024-11-01T23:15:24.701Z
updated: 2024-11-07T11:51:43.208Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Step-by-Step: Rectifying Windows 11/10 Nvidia Errors"
excerpt: "This Article Describes Step-by-Step: Rectifying Windows 11/10 Nvidia Errors"
keywords: Fixing Nvidia in Win11/10,Solving Win Nvidia Glitches,Nvidia Correction for Windows Users,Overcoming Win11/10 Nvidia Errors,Remedying Nvidia Problems WIndows,Steps to Fix NVidia in WinOS,Correcting Nvidia Issues in Windows
thumbnail: https://thmb.techidaily.com/54fd3e003b786647a6f1d7a89a0a9ff3e56e44f972b8ef6e36ebd7fc54a18cb3.jpg
---

## Step-by-Step: Rectifying Windows 11/10 Nvidia Errors

 The NVIDIA Control Panel is an app included on PCs with NVIDIA GPUs with which users can change graphical settings. However, some users can’t change NVIDIA Control Panel options because of an “Access denied” error. The message of that error says, “Failed to apply selected settings to your system.”

 The “Access denied” error is mostly reported to arise for 3D settings. As a result, NVIDIA Control Panel doesn’t apply (save) the settings users select. This is how you can resolve NVIDIA Control Panel’s “Access denied” error within Windows 11/10.

## 1\. Run the NVIDIA Control Panel as an Administrator

 Firstly, try running the NVIDIA Control Panel with elevated admin permissions, which has worked for some users. To do that, press the**Windows** logo +**S** keyboard buttons and input NVIDIA Control Panel. Right-click NVIDIA Control Panel and select**Run as administrator** .

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-as-administrator-option2.jpg)

 Should this potential fix work, then it would be better to set the NVIDIA Control Panel to always run with administrative rights. However, that UWP app is located within a protected folder. You’ll need to[take ownership of the WindowsApps folder](https://www.makeuseof.com/windows-10-11-own-folder/) to set permanent admin rights for the NVIDIA Control Panel.

 If you take ownership of the WindowsApps folder, open the NVIDIACorp subfolder to reach the NVIDIA Control Panel file. Then you’ll need to set the nvcplui.exe file to run with admin rights. Follow the steps in this how to[set an app to always run as an administrator guide](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) to set elevated permissions for the nvcplui.exe file. The path for the NVIDIA Control Panel folder is:

`C:\Program Files\WindowsApps\NVIDIACorp.NVIDIAControlPanel_8.1.964.0_x64__56jybvy8sckqj`

## 2\. Select the Repair and Reset Options for the NVIDIA Control Panel

 The NVIDIA Control Panel app has**Repair** and**Reset** troubleshooting options you can select in Settings. Both options can be useful for fixing apps when they’re not working right. So, try selecting the**Repair** option first and then**Reset** to clear the app’s data if repairing isn’t enough. Check out this[article about resetting apps in Windows](https://www.makeuseof.com/windows-reset-app/) for details about how to apply this potential fix.

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997675/19272" target="_top" id="1997675">
  <img src="//a.impactradius-go.com/display-ad/19272-1997675" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997675/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Update Your NVIDIA Graphics Card Driver

 The most widely confirmed fix for the “Access denied” error is to manually update the NVIDIA graphics driver. Thus, this is often an issue caused by outdated or faulty NVIDIA drivers. This[guide to updating NVIDIA drivers](https://www.makeuseof.com/how-update-nvidia-graphics-card-drivers-windows/) provides further details about how to apply this potential solution by manually downloading the latest GPU driver available from the NVIDIA site.

 When you’ve downloaded the latest NVIDIA driver package for your GPU, bring up the directory that includes its setup file. Double-click the NVIDIA driver package file to view its setup wizard and select the**Custom** option. Then select the**Perform a clean installation** checkbox and click**Next** to install.

![The Perform a clean installation checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/perform-a-clean-installation.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068426/7443" target="_top" id="2068426">
  <img src="//a.impactradius-go.com/display-ad/7443-2068426" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068426/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Roll Back the NVIDIA Driver

 If the “Access denied” error arises after installing a new NVIDIA driver, rolling back that driver to a previous one could be a viable potential solution. You’ll only be able to do that if the previous NVIDIA GPU driver file is still available. Our[article about rolling back drivers](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) includes guidelines for how to apply this potential fix.

 If the**Roll Back** option is grayed out, you might still be able to roll back to a previous NVIDIA graphics driver with the System Restore utility. Rolling Windows back to a restoration point restores drivers installed before the selected date. However, that will only work if your PC has a restore point that predates the driver update.

![The Roll Back Driver button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/roll-back-driver-option.jpg)

 This[post about creating and utilizing restore points](https://www.makeuseof.com/windows-11-create-restore-point/) tells you how to roll back Windows. Select a restore point that will restore the previous NVIDIA graphics driver. You can click**Scan for affected** programs in System Restore to check if a chosen restoration point will restore an NVIDIA graphics driver.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075462/7443" target="_top" id="2075462">
  <img src="//a.impactradius-go.com/display-ad/7443-2075462" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075462/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Restore a Previous Version of the DRS Folder

 Some NVIDIA Control Panel users have said they fixed the “Access denied” error by restoring a DRS folder version backup. Note that you’ll only be able to apply this potential fix if you’ve got File History enabled or restore points saved on your PC. This is how you can restore a previous DRS folder version in Windows 11/10:

1. First, bring up File Explorer by clicking the taskbar button with the folder library icon.
2. Then click the**View** button to select a**Show** option.
3. Select the**Hidden Items** option.  
![The Hidden items checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hidden-items-option.jpg)
4. Clear Explorer’s address bar to input the following path:  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975821/19272" target="_top" id="1975821">
  <img src="//a.impactradius-go.com/display-ad/19272-1975821" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975821/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1815678/21290" target="_top" id="1815678">
  <img src="//a.impactradius-go.com/display-ad/21290-1815678" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://versadesk.pxf.io/i/5597632/1815678/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://youtube-docs.techidaily.com/est-of-the-best-cutting-edge-hiring-videos-1-10-for-2024/"><u>[New] Best of the Best Cutting-Edge Hiring Videos #1-10 for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-in-2024-writers-who-defined-genres-through-exceptional-works/"><u>[New] In 2024, Writers Who Defined Genres Through Exceptional Works</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-facial-lockout-a-deep-dive-into-iphones-face-id-vs-galaxys-recognition/"><u>2024 Approved Facial Lockout A Deep Dive Into iPhone's Face ID Vs. Galaxy’s Recognition</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-ultimate-iphone-hdr-insights-for-stunning-images/"><u>2024 Approved Ultimate iPhone HDR Insights for Stunning Images</u></a></li>
<li><a href="https://driver-download.techidaily.com/expert-tips-on-acquiring-and-updating-dell-latitude-e643n-drivers-for-a-seamless-windows-experience/"><u>Expert Tips on Acquiring & Updating Dell Latitude E643n Drivers for a Seamless Windows Experience</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-download-and-update-your-creative-sound-blasters-drivers-on-windows-11/"><u>How to Download & Update Your Creative Sound Blaster's Drivers on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-flickering-mouse-pointer-on-windows/"><u>How to Fix the Flickering Mouse Pointer on Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-card-on-apple-iphone-12-online-without-jailbreak-by-drfone-ios/"><u>In 2024, How to Unlock SIM Card on Apple iPhone 12 online without jailbreak</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-strategizing-the-open-door-to-market-success/"><u>In 2024, Strategizing the Open Door to Market Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-productivity-leveraging-windows-11s-developer-tools/"><u>Maximizing Productivity: Leveraging Windows 11'S Developer Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapid-route-to-uncover-graphics-card-details-window-11/"><u>Rapid Route to Uncover Graphics Card Details, Window 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-windows-original-sleepwake-patterns/"><u>Regaining Windows' Original Sleep/Wake Patterns</u></a></li>
<li><a href="https://win-web3.techidaily.com/1728472022483-sd/"><u>SD 卡救援手法介绍 - 利用命令行解决方案恢复丢失数据</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-boot-stability-top-strategies-to-sidestep-system-setbacks/"><u>Secure Boot Stability: Top Strategies to Sidestep System Setbacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-google-on-your-w11-device/"><u>Setting Up Google on Your W11 Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-1011-enabled-three-routes-to-telnet-success/"><u>Win 10/11 Enabled: Three Routes to Telnet Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-revolution-redesign-and-upgrades-in-explorer/"><u>Windows 11 Revolution: Redesign and Upgrades in Explorer</u></a></li>
</ul></div>

