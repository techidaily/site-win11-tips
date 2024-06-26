---
title: Troubleshoot Manual Timezone Setting in Microsoft OS
date: 2024-06-25T16:43:21.300Z
updated: 2024-06-26T16:43:21.300Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshoot Manual Timezone Setting in Microsoft OS
excerpt: This Article Describes Troubleshoot Manual Timezone Setting in Microsoft OS
keywords: Windows Timezone Fix Guide,Set Timezone MSOS,Resolve Time Zone Errors,Adjust Timezone in Windows,Correct Timezone in OS,Timezone Correction Steps,Microsoft Timezone Calibration
thumbnail: https://thmb.techidaily.com/b7ac3fecaf39cbf4ad53ade68b5607328fb5fc5fabf85fb01691cb6e94c786a0.jpg
---

## Troubleshoot Manual Timezone Setting in Microsoft OS

 Did you ever experience being in a different time zone while working on your Windows computer? You've checked Windows time settings and noticed that it's not set to your current location. Suddenly, you realize that the time zone is greyed out, and you can’t configure it automatically. What do you do next? There are several scenarios where Windows cannot automatically set the time zone, and here's how to fix them.

## 1\. Restart Your PC

 The first step when troubleshooting any Windows-related issue is to restart the computer. It seems obvious, but it often solves the problem. Rebooting flushes out cached data that could cause time zone problems. It also resets various temporary services that may prevent Windows from automatically setting the time zone.

 To restart your computer, save all your work and close any running applications. After that, open the Start menu and click **Restart**. Once your computer restarts, check if that fixes the issue.

## 2\. Turn on Location Services in the Settings

 If restarting your computer didn't fix the issue, check if location services are enabled. Location services allow Windows to automatically detect the time zone and set it accordingly.

 To verify location services, follow these steps:

1. Press **Win + I** to open the Settings window.
2. From the left navigation panel, click **Privacy & security**.
3. Under the **App permissions** section, select **Location**.
4. Make sure the **Location services** option is enabled. If it's not, switch the toggle to turn it on.  
![Enable Location Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-location-services.jpg)

 Now restart your computer and check if Windows can set the time zone automatically.

## 3\. Set the Windows Time Service to Automatic

 If the location services are already enabled, but Windows still can't detect the time zone, the problem may be related to the Windows Time Service. This background service keeps your system clock synchronized with time servers.

 Windows won't detect the time zone if the service is not running. To fix this issue, set Windows Time Service to Automatic.

 Here's how to do that:

1. Press **Win + R** on your keyboard to open the Run window.
2. Type **services.msc** in the text box and press **Enter**.
3. Scroll down in the Services window and locate the **Windows Time** service.
4. Right-click the service and select **Properties**.
5. In the Properties window, set the **Startup type** to **Automatic**.  
![Windows Time Service Status](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-time-service-status.jpg)
6. Now check the **Service status**. If it reads **Stopped**, click the **Start** button to start the service.
7. Click **Apply** and **OK** to save the changes.

 Once you've done this, restart your PC and check the time zone settings.

## 4\. Tweak the Registry Editor

 If Windows still fails to detect the time zone or the "Set time zone automatically" option is still grayed out, you may need to tweak your registry. This is a more technical solution and requires registry knowledge. If you're not good at registry editing, skip this step or ask a professional for help.

 Follow these steps to make the changes:

 Modifying the registry incorrectly may cause serious problems. Before making any changes, [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/).

1. Press **Win + S** on your keyboard to open the Windows Search.
2. Type **regedit** in the search bar and press **Enter**.
3. If the UAC window pops up, click **Yes** to grant administrative privileges.
4. In the Registry Editor window, navigate to the following directory.  
`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\tzautoupdate`
5. In the right pane, double-click the **Start** (DWORD) value.  
![Modify Registry to change the Set time zone automatically setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modify-registry-to-change-the-set-time-zone-automatically-setting.jpg)
6. When the Edit DWORD Value window pops up, set the Value data to **3** and click **OK**.
7. After doing this, you must change the location setting. To do this, navigate to the following key:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\location`  
 You can also copy and paste the path into the Registry Editor address bar. Now press Enter and this directs you to the Location key.
8. Move to the right pane and double-click the **Value** (REG\_SZ) value.  
![Edit Registry to change the location setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/edit-registry-to-change-the-location-setting.jpg)
9. In the Edit String window, type **Allow** in the **Value data** field and click OK.

 After that, close the Registry Editor and restart your PC. Windows should detect the time zone automatically and set it correctly.

## 5\. Use the Group Policy Editor

 If you're comfortable with registry editing, use the Group Policy Editor instead. However, the tool is only compatible with Windows Pro and Enterprise editions. If you're not a Pro user, [activate the Group Policy for Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/), then follow these steps:

1. Right-click on Start and select **Run**.
2. Type **gpedit.msc** in the text field and click **OK**. The Local Group Policy Editor window will open.
3. On the left navigation panel, browse to the following path:  
`Computer Configuration > Administrative Templates > Windows Components > Location and Sensors > Windows Location Provider`
4. Go to the right pane and double-click on **Turn off Windows Location Provider**.  
![Turn off Windows Location Provider](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/turn-off-windows-location-provider.jpg)
5. In the pop-up window, check the **Not Configured** option.
6. Click **Apply** and **OK** to save the changes.

 Now close the Group Policy Editor and restart your PC. After restarts check if your Windows detects the time zone automatically.

## 6\. Reset the Windows Time Service

 This problem may also occur if the Windows Time Service or time synchronization settings become corrupted. In that case, reset the service to its default settings and see if that helps. Here's how to do it:

1. Click on Start and type **cmd** in the search box.
2. Press **Ctrl + Shift + Enter** on your keyboard simultaneously. This opens the Command Prompt in administrator mode.
3. If the pop-up window appears, click **Yes** to grant permission.
4. In the Command Prompt window, type net **stop w32time** and press **Enter**. Running this command will stop the Windows Time Service.
5. Now, type **w32tm /unregister** in the Command Prompt window and hit **Enter**. This unregisters the service.
6. Next, type **w32tm /register** and press **Enter**. This will re-register the Windows Time Service.
7. After that, type net **start w32time** to restart the Windows Time Service.

 Once done, close the Command Prompt and restart your computer to check if it solves the problem.

## 7\. Try Some Generic Windows Fixes

 There are also generic fixes you can try:

1. **Run the System File Checker tool:**[running System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) scans for corrupted system files and replaces them if necessary.
2. **Perform a Clean Boot:** If that didn't work, [try a Windows clean boot](https://www.makeuseof.com/clean-boot-windows-11/). This determines if third-party applications interfere with Windows Time Service.
3. **Update Windows:** Finally, [update Windows to the latest version](https://www.makeuseof.com/update-windows-manually/) to ensure you have all the latest fixes and security patches.

## Windows Can Now Automatically Set the Time Zone

 We hope the article helped you resolve timing issues on your Windows computer. It may occur due to missing or corrupted system files or incorrect time zone settings. Make sure to try these solutions and perform a System Restore if the problem persists.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-challenge-xfffffddd-print-error-in-xp/"><u>Overcoming the Challenge: XFFFFFDDD Print Error in XP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-curb-energy-drain-while-playing-games-on-pc/"><u>Strategies to Curb Energy Drain While Playing Games on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/icon-position-correction-made-simple/"><u>Icon Position Correction Made Simple</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-easy-steps-to-wipe-your-drives-partitions-in-windows/"><u>4 Easy Steps to Wipe Your Drive's Partitions in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-system-performance-with-effective-use-of-windows-law-filters/"><u>Elevating System Performance with Effective Use of Window's LAW Filters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-using-the-netstat-command-in-win11/"><u>A Step-by-Step Approach: Using the Netstat Command in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-surface-computer-firmware-update-manual/"><u>The Ultimate Surface Computer Firmware Update Manual</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-easily-remove-tiktok-watermarks-best-online-solutions/"><u>Updated In 2024, Easily Remove TikTok Watermarks Best Online Solutions</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-unlock-the-6th-richest-strategies-for-successful-ig/"><u>[Updated] In 2024, Unlock the 6Th Richest Strategies for Successful IG</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-your-honor-play-8t-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>How to Mirror Your Honor Play 8T Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/unveiling-the-power-of-video-enhancer-22-for-professionals-for-2024/"><u>Unveiling the Power of Video Enhancer 2.2 for Professionals for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-the-viral-trend-you-need-to-try-here-it-is/"><u>[New] 2024 Approved  The Viral Trend You Need to Try - Here It Is</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/from-filters-to-fun-factors-maximizing-iphones-gif-capabilities/"><u>From Filters to Fun Factors  Maximizing iPhone's GIF Capabilities</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/what-legendaries-are-in-pokemon-platinum-on-honor-x9b-drfone-by-drfone-virtual-android/"><u>What Legendaries Are In Pokemon Platinum On Honor X9b? | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-ultimate-top-5-cost-free-pinterest-videos-download/"><u>In 2024, Ultimate Top 5  Cost-Free Pinterest Videos Download</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>