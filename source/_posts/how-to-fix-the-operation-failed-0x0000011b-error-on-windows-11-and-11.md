---
title: How to Fix the Operation Failed 0X0000011B Error on Windows 11 & 11
date: 2024-11-24T17:05:13.373Z
updated: 2024-11-27T16:16:49.456Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the Operation Failed 0X0000011B Error on Windows 11 & 11
excerpt: This Article Describes How to Fix the Operation Failed 0X0000011B Error on Windows 11 & 11
keywords: WinError0x011BFix,XP11FailureSolution,Windows11OperationRepair,OSX0000011BFixWin,Error0x011BWindowsTroubleshoot,WinErrorResolution011B,0X0000011BEasyFixWin11
thumbnail: https://thmb.techidaily.com/b89bc76dab2d2da8b94cbca20640b5005a7d287429d61f6d3112ce6c1768b0a9.jpg
---

## How to Fix the Operation Failed 0X0000011B Error on Windows 11 & 11

 A new security patch released by Microsoft may have caused printers shared over the network to malfunction, resulting in the operation failed 0x0000011B error. The error has primarily affected Windows 10 21H1 build running computers. However, you may also experience it on Windows 11 systems.

 You can fix the error by installing the latest patch for the bug in the Windows update section. If not, here are other troubleshooting steps to fix the error and get your printer working again.

 Note that all the fixes must be applied to the host system that has the printer connected to it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Restart the Print Spooler Service

 A common troubleshooting step to fix issues with your printer is to restart the print spooler service. It is an essential service that handles the print job between your computer and printer. If the[print spooler service is not running](https://www.makeuseof.com/print-spooler-service-not-running-windows/) , you can manually start it from the Services snap-in. Here’s how to do it.

1. Press**Win + R** to open**Run** .
2. Type**services.msc** and click**OK** .
3. In the**Service** snap-in, locate the**Print Spooler** service.  
![print spooler service properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/print-spooler-service-properties.jpg)
4. Next, right-click on the service and select**Properties** .  
![print spooler service startup type automatic](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/print-spooler-service-startup-type-automatic.jpg)
5. In the**Properties** dialog, open the**General** tab.  
![restart print spooler service 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/restart-print-spooler-service-1.jpg)
6. Click the**Startup type** drop-down and set it to**Automatic** .
7. Click**Apply** and**OK** to save the changes.
8. Right-click on**Print** **Spooler** again and click**Restart** .
9. Once the Print Spooler service is up and running, create a new print job and check for any improvements.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aYH0B2HqcIM?si=3fkoG85L6hAeB4ok&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Install All the Pending Windows Updates

![check windows 10 updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-windows-10-updates.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-G7cU8dYvuI?si=JaKqRcW6qq9CDvty&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If it’s a widespread issue, you’ll likely receive a bug fix via Windows update. So, begin with checking if a new Windows update is available. These are often small hotfixes released to fix widespread issues.

To check and install Windows updates:

1. Press**Win + I** to open the**Settings** app.
2. In the left pane, open the**Windows Update** tab. Open**Update & Security** on Windows 10.
3. Click on**Check for updates** . Windows will look for pending updates and list them here.
4. Click on**Download & install** to install the updates.
5. Once installed, restart your PC and check for any improvements.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xIP8ktrmOdg?si=zRnjbGzM6PDx2jCq&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Install the Printer Manually via the Local Port

 A little complicated, yet a working solution to fix the operation failed error 0x0000011B is to[add your printer manually to Windows](https://www.makeuseof.com/windows-11-add-wired-wireless-printer/) for the local port. Here’s how to do it.

1. Press**Win + I** to open**Settings** .
2. Next, click on**Devices** and then open the**Printers & scanners** tab.
3. Next, click on**Add a printer or scanner** . Windows will scan for available printers.  
![the printer that i want isnt listed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-printer-that-i-want-isnt-listed.jpg)
4. Click on the**The printer that I want isn’t listed** option. If you don't see the option immediately, wait for a few seconds after clicking on the**Add a printer or scanner** option.
5. In the**Add Printer** dialog, select **Add a local printer or network printer with manual settings.**  
![add local printer network printer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/add-local-printer-network-printer.jpg)

1. Under**Choose a printer por** t, select**Create a new port.**  
![create new port local port add printer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/create-new-port-local-port-add-printer.jpg)
2. Click the drop-down for**Type of port** and select**Local Port.**
3. Click**Next** .  
![enter port name printer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/enter-port-name-printer.jpg)
4. Type your network printer file path and the network printer name in the**Enter a port name** field. You can use the username or the IP address for the computer name and then the printer name you want to share.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qfCSLAhd4FY?si=CUBztmilaeAwl1lw&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Click**OK** to save the printer.

1. Next, select your printer manufacturer from the list to install the printer driver.
2. Next, select the correct printer driver under the**Printers** column.
3. Click**Next** .
4. Choose a name for your printer driver and click**Install** .
5. Click**Next** and wait for the installation to complete.

 Your newly added printer will now appear under**Device and Printer** in**Control Panel** and the**Settings** app. Give a new print job to see if the error is resolved.

## 4\. Disable the CVE-2021-1678 Registry Fix

 The problematic security update included a security fix to patch the Printer Spooler Spoofing vulnerability dubbed CVE-2021-1678\. However, the new changes seem to have triggered the 0x0000011B operation failed error.

 To fix the error without uninstalling the security update, you’ll need to create a new registry entry to disable the feature. Here’s how to do it.

 Note that modifying your Windows Registry involves risk. We recommend you[back up your Windows registry](http://www.makeuseof.com/tag/backup-restore-windows-registry/) and[create a system restore](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps below.

Next, follow these steps to disable CVE-2021-1678 mitigation:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open Registry Editor.
3. In Registry Editor, navigate to the following location. Copy and paste the registry path for quick navigation:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Print`
4. Next, right-click on**Print > New > DWORD (32-bit) Value.**  
![create new dword 32 bit value registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/create-new-dword-32-bit-value-registry-editor.jpg)
5. Rename the**DWORD value** as**RpcAuthnLevelPrivacyEnabled.**  
![registry editor modify rpcauthlevelprivacyenabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor-modify-rpcauthlevelprivacyenabled.jpg)
6. Right-click on the**RpcAuthnLevelPrivacyEnabled** value and select**Modify** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gyGoQi7hsZk?si=8OcKcPUj2wSBmVZ1&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Type**0** in the**Value data** field and click**OK** to save the changes.  
![registry editor modify rpcauthlevelprivacyenabled 0 disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor-modify-rpcauthlevelprivacyenabled-0-disabled.jpg)
8. Close**Registry Editor** and restart your PC to apply the changes.
9. After the restart, try to use your shared printer and check if the error is resolved.

## 5\. Uninstall Recently Installed Updates

 Assuming the issue is triggered after you installed a Windows security update, uninstalling the update should undo the changes and fix the error. You can uninstall some individual updates from the Windows updates section. This feature is specifically available to undo issues that may have occurred after installing an update.

 Note that the concerned update (KB5005565) was released to fix a print spooler vulnerability on Windows OS. Uninstalling the update can leave your computer vulnerable again. Use this as a last resort if none of the above methods helped resolve the error.

To uninstall Windows updates:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel.**  
![control panel uninstall programs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/control-panel-uninstall-programs.jpg)
3. Next, click on**Programs** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xtylXDY9YfA?si=VonzSiDFGCpJm2uC&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![control panel uninstall programs view installed updatges](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/control-panel-uninstall-programs-view-installed-updatges.jpg)
4. Click on**View installed updates** under**Programs and Features** . This will open the**Uninstall updates** section in the**Settings** app. Alternatively, go to **Settings > Windows Update > Update history > Uninstall updates** to access the same.  
![uninstall windows updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/uninstall-windows-updates.jpg)
5. Locate the problematic update (**KB5005565**) and click on**Uninstall** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gkdZ3A1mock?si=2zeR5GtTU2VujM_w&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Click**Uninstall** again to confirm the action. Wait for the update to uninstall and restart your PC to apply the changes.

## Fixing the 0x0000011b Printing Error on Windows

 This error has largely affected Windows 10 computers. To fix the issue, try to install all the pending Windows updates that may include a hotfix. You can also add the printer manually to a local port or edit the registry entry to disable the problematic setting. If nothing works, uninstalling the security update may be the last resort. However, doing so can put your computer at risk of print spooler spoofing vulnerability.

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
<li><a href="https://article-helps.techidaily.com/updated-cutting-edge-8-lens-modifications-for-webcams/"><u>[Updated] Cutting-Edge 8 Lens Modifications for Webcams</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-tunefab-screen-recorder-review/"><u>[Updated] Tunefab Screen Recorder Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-drive-errors-a-windows-guide/"><u>Clearing Drive Errors: A Windows Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-to-rectify-non-starting-search-service/"><u>Expert Tips to Rectify Non-Starting Search Service</u></a></li>
<li><a href="https://buynow-info.techidaily.com/google-nest-hub-gen-2-reviewed-how-not-including-a-camera-affects-user-experience-and-functionality/"><u>Google Nest Hub Gen 2 Reviewed – How Not Including a Camera Affects User Experience and Functionality</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-nubia-z50s-pro-frp-in-3-different-ways-by-drfone-android/"><u>How To Bypass Nubia Z50S Pro FRP In 3 Different Ways</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-3-ways-to-unlock-your-apple-iphone-7-plus-for-free-by-drfone-ios/"><u>In 2024, 3 Ways to Unlock Your Apple iPhone 7 Plus for Free</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-do-you-get-sun-stone-evolutions-in-pokemon-for-apple-iphone-6-drfone-by-drfone-virtual-ios/"><u>In 2024, How Do You Get Sun Stone Evolutions in Pokémon For Apple iPhone 6? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-reset-gmail-password-on-infinix-hot-40-devices-by-drfone-android/"><u>In 2024, How to Reset Gmail Password on Infinix Hot 40 Devices</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-a-lost-vivo-s18e-for-free-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track a Lost Vivo S18e for Free? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mute-issues-resolving-keyboard-volume-problems-in-windows/"><u>Mute Issues: Resolving Keyboard Volume Problems in Windows</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/perfecting-online-visuals-beauty-focused-color-correction/"><u>Perfecting Online Visuals Beauty-Focused Color Correction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-resource-grab-taming-windows-ums-consumption-by-vanguard/"><u>Reducing Resource Grab: Taming Windows' UMS Consumption by Vanguard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-windows-keys-triggering-without-intent/"><u>Remedying Windows Keys Triggering without Intent</u></a></li>
<li><a href="https://win11-tips.techidaily.com/renewal-of-pre-installed-software-with-microsoft-store/"><u>Renewal of Pre-Installed Software with Microsoft Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-operation-failure-0x0000011b-in-windows-11/"><u>Solving Operation Failure 0X0000011B in Windows 11</u></a></li>
<li><a href="https://win-blog.techidaily.com/step-by-step-tutorial-eliminating-performance-bugs-in-watch-dogs-legion-for-a-smooth-pc-gaming-experience/"><u>Step-by-Step Tutorial: Eliminating Performance Bugs in 'Watch Dogs Legion' For a Smooth PC Gaming Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-run-history-loss-on-windows/"><u>Troubleshooting Run History Loss on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-corrected-display-sharing-after-connection-issues/"><u>Unlocking Corrected Display Sharing After Connection Issues</u></a></li>
</ul></div>

