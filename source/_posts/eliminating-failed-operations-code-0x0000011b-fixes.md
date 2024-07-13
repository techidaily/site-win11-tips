---
title: "Eliminating 'Failed' Operations: Code 0X0000011B Fixes"
date: 2024-07-12T17:05:33.193Z
updated: 2024-07-13T17:05:33.193Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Eliminating 'Failed' Operations: Code 0X0000011B Fixes"
excerpt: "This Article Describes Eliminating 'Failed' Operations: Code 0X0000011B Fixes"
keywords: Error Code X0000011B Solution,ZeroXError Correction,Fixed Operation Issue,Resolve XError,Bug Elimination Technique,Correcting Operational Failure,Addressing 0xError Fixes
thumbnail: https://thmb.techidaily.com/f039a729b962f9ef9ca84af335ac6a5c033da72e1971abe6cb320e3e4a83ec5c.jpg
---

## Eliminating 'Failed' Operations: Code 0X0000011B Fixes

 A new security patch released by Microsoft may have caused printers shared over the network to malfunction, resulting in the operation failed 0x0000011B error. The error has primarily affected Windows 10 21H1 build running computers. However, you may also experience it on Windows 11 systems.

 You can fix the error by installing the latest patch for the bug in the Windows update section. If not, here are other troubleshooting steps to fix the error and get your printer working again.

 Note that all the fixes must be applied to the host system that has the printer connected to it.

## 1\. Restart the Print Spooler Service

 A common troubleshooting step to fix issues with your printer is to restart the print spooler service. It is an essential service that handles the print job between your computer and printer. If the [print spooler service is not running](https://www.makeuseof.com/print-spooler-service-not-running-windows/) , you can manually start it from the Services snap-in. Here’s how to do it.

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

## 2\. Install All the Pending Windows Updates
![check windows 10 updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-windows-10-updates.jpg)

 If it’s a widespread issue, you’ll likely receive a bug fix via Windows update. So, begin with checking if a new Windows update is available. These are often small hotfixes released to fix widespread issues.

To check and install Windows updates:

1. Press**Win + I** to open the**Settings** app.
2. In the left pane, open the**Windows Update** tab. Open**Update & Security** on Windows 10.
3. Click on**Check for updates** . Windows will look for pending updates and list them here.
4. Click on**Download & install** to install the updates.
5. Once installed, restart your PC and check for any improvements.

## 3\. Install the Printer Manually via the Local Port

 A little complicated, yet a working solution to fix the operation failed error 0x0000011B is to [add your printer manually to Windows](https://www.makeuseof.com/windows-11-add-wired-wireless-printer/) for the local port. Here’s how to do it.

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

 Note that modifying your Windows Registry involves risk. We recommend you [back up your Windows registry](http://www.makeuseof.com/tag/backup-restore-windows-registry/) and [create a system restore](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps below.

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
![control panel uninstall programs view installed updatges](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/control-panel-uninstall-programs-view-installed-updatges.jpg)
4. Click on**View installed updates** under**Programs and Features** . This will open the**Uninstall updates** section in the**Settings** app. Alternatively, go to **Settings > Windows Update > Update history > Uninstall updates** to access the same.  
![uninstall windows updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/uninstall-windows-updates.jpg)
5. Locate the problematic update (**KB5005565**) and click on**Uninstall** .
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
<li><a href="https://win11.techidaily.com/swiftly-remedy-windows-onedrive-server-issues/"><u>Swiftly Remedy Windows OneDrive Server Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easing-up-stuck-exe-files-on-windows-platform/"><u>Easing Up Stuck EXE Files on Windows Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-to-resolve-windows-error-0xc00000f-efficiently/"><u>Expert Tips to Resolve Windows Error 0Xc00000f Efficiently</u></a></li>
<li><a href="https://iphone-location.techidaily.com/4-effective-methods-fake-gps-location-on-apple-iphone-6s-plusipad-drfone-by-drfone-virtual-ios/"><u>4 Effective Methods Fake GPS Location on Apple iPhone 6s Plus/iPad | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/your-guide-to-premium-metaverse-goggles-and-headsets/"><u>Your Guide to Premium Metaverse Goggles & Headsets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/drive-down-compilation-times-with-android-studio-tweaks-on-windows/"><u>Drive Down Compilation Times with Android Studio Tweaks on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-stuck-windows-enter-mechanism/"><u>Addressing Stuck Windows 'Enter' Mechanism</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-component-services-access-in-windows-11/"><u>Demystifying Component Services Access in Windows 11</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-viral-laughter-lab-for-2024/"><u>[Updated] Viral Laughter Lab for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-essential-steps-for-a-gorgeous-discord-profile-photo/"><u>[Updated] 2024 Approved  Essential Steps for a Gorgeous Discord Profile Photo</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insightful-strategies-for-hardware-serial-numbers-on-windows/"><u>Insightful Strategies for Hardware Serial Numbers on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hide-windows-11-language-line-from-status-bar/"><u>Hide Windows 11 Language Line From Status Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/file-management-follies-steering-clear-of-windows-11-errors/"><u>File Management Follies: Steering Clear of Windows 11 Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-manage-widget-notifications-on-windows-11/"><u>How to Manage Widget Notifications on Windows 11</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-fix-apple-id-verification-code-not-working-on-iphone-15-pro-max-by-drfone-ios/"><u>In 2024, How To Fix Apple ID Verification Code Not Working On iPhone 15 Pro Max</u></a></li>
<li><a href="https://android-location.techidaily.com/3-effective-methods-to-fake-gps-location-on-android-for-your-asus-rog-phone-8-drfone-by-drfone-virtual/"><u>3 Effective Methods to Fake GPS location on Android For your Asus ROG Phone 8 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decorate-with-style-customizing-themes-for-an-improved-win11-experience/"><u>Decorate with Style: Customizing Themes for an Improved Win11 Experience</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-spring-into-savings-wondershare-filmora-coupon-code-march-2024/"><u>Updated Spring Into Savings Wondershare Filmora Coupon Code - March 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-who-rules-the-realm-of-youtube/"><u>[New] Who Rules the Realm of YouTube?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/error-code-0x80242016-stopping-windows-updates/"><u>Error Code 0X80242016 Stopping Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automating-iphones-calendar-into-windows-os/"><u>Automating iPhone's Calendar Into Windows OS</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/4-methods-to-merge-mp4-and-mp3/"><u>4 Methods to Merge MP4 and MP3</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-embedding-audio-in-instant-storytelling-platforms-for-2024/"><u>[New] Embedding Audio in Instant Storytelling Platforms for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-line-proficiency-decoding-errors-in-windows-through-advanced-troubleshooting-techniques/"><u>Command Line Proficiency: Decoding Errors in Windows Through Advanced Troubleshooting Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correct-disabled-volume-adjustment-on-windows/"><u>Correct Disabled Volume Adjustment on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stop-0x0000011b-failures-in-windows-os/"><u>How to Stop 0X0000011B Failures in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-red-crossed-symbol-in-windows-explorer/"><u>Deciphering Red Crossed Symbol in Windows Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-play-your-favorite-oldschool-pc-games-with-dosbox-x/"><u>How to Play Your Favorite Oldschool PC Games With DOSBox-X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hacking-the-login-loop-in-windows-1011/"><u>Hacking the Login Loop in Windows 10/11</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-time-trackers-in-action-using-obs-for-timed-events/"><u>2024 Approved  Time Trackers in Action  Using OBS for Timed Events</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-process-of-screen-sharing-samsung-galaxy-s23-ultra-to-pc-detailed-steps-drfone-by-drfone-android/"><u>In 2024, Process of Screen Sharing Samsung Galaxy S23 Ultra to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-pathway-to-create-high-quality-audio-cds-from-mp3-files-using-imgburn-windows/"><u>Easy Pathway to Create High Quality Audio Cds From MP3 Files Using ImgBurn (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dial-up-decibels-the-top-4-programs-to-increase-volume-on-windows/"><u>Dial Up Decibels: The Top 4 Programs to Increase Volume on Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/dose-life360-notify-me-when-someone-checks-my-location-on-honor-x50iplus-drfone-by-drfone-virtual-android/"><u>Dose Life360 Notify Me When Someone Checks My Location On Honor X50i+? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-lost-connection-problem-on-windows-vpn-client/"><u>Fixing Lost Connection Problem on Windows VPN Client</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-lowering-sounds-on-mac-and-pc-gradually-and-invisibly/"><u>[Updated] In 2024, Lowering Sounds On Mac & PC Gradually and Invisibly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-offline-lsa-message-in-windows-os/"><u>Fixing the Offline LSA Message in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/excellent-windows-apps-transforming-videos/"><u>Excellent Windows Apps Transforming Videos</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/keeping-the-flow-alive-2023-guide-to-live-video-repairs-on-fb/"><u>Keeping the Flow Alive  2023 Guide to Live Video Repairs on FB</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-the-ultimate-guide-to-zero-cost-win-media-tools/"><u>Explore the Ultimate Guide to Zero-Cost Win Media Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-oculus-quest-to-function-in-windows-vr/"><u>Customizing Oculus Quest to Function in Windows VR</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-more-value-black-friday-offers-at-612-win10/"><u>Get More Value: Black Friday Offers at $6.12 Win10</u></a></li>
</ul></div>
