---
title: "Solving 0X0000011B Errors: Operation Issue Resolved"
date: 2024-10-14T13:03:29.611Z
updated: 2024-10-14T20:56:07.825Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Solving 0X0000011B Errors: Operation Issue Resolved"
excerpt: "This Article Describes Solving 0X0000011B Errors: Operation Issue Resolved"
keywords: Fix ZeroError X1B,Solve X011B Error,Resolve Operation X0B,Overcome X1B Failure,Ending X1B Issue,Correct X1B Errors,Mend Operation X0B
thumbnail: https://thmb.techidaily.com/443fa3d21137649dff0319f1c3c3070702e32a7b2f673e094959a8fdb4cdbd5b.jpg
---

## Solving 0X0000011B Errors: Operation Issue Resolved

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
<a href="https://aligracehair.sjv.io/c/5597632/1997630/19272" target="_top" id="1997630">
  <img src="//a.impactradius-go.com/display-ad/19272-1997630" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997630/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
5. Click**OK** to save the printer.

1. Next, select your printer manufacturer from the list to install the printer driver.
2. Next, select the correct printer driver under the**Printers** column.
3. Click**Next** .
4. Choose a name for your printer driver and click**Install** .
5. Click**Next** and wait for the installation to complete.

 Your newly added printer will now appear under**Device and Printer** in**Control Panel** and the**Settings** app. Give a new print job to see if the error is resolved.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137204/26400" target="_top" id="2137204">
  <img src="//a.impactradius-go.com/display-ad/26400-2137204" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137204/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
7. Type**0** in the**Value data** field and click**OK** to save the changes.  
![registry editor modify rpcauthlevelprivacyenabled 0 disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor-modify-rpcauthlevelprivacyenabled-0-disabled.jpg)
8. Close**Registry Editor** and restart your PC to apply the changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118314/7443" target="_top" id="2118314">
  <img src="//a.impactradius-go.com/display-ad/7443-2118314" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118314/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. After the restart, try to use your shared printer and check if the error is resolved.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/857869/11832" target="_top" id="857869">
  <img src="//a.impactradius-go.com/display-ad/11832-857869" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/857869/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Uninstall Recently Installed Updates

 Assuming the issue is triggered after you installed a Windows security update, uninstalling the update should undo the changes and fix the error. You can uninstall some individual updates from the Windows updates section. This feature is specifically available to undo issues that may have occurred after installing an update.

 Note that the concerned update (KB5005565) was released to fix a print spooler vulnerability on Windows OS. Uninstalling the update can leave your computer vulnerable again. Use this as a last resort if none of the above methods helped resolve the error.

To uninstall Windows updates:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel.**  
![control panel uninstall programs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/control-panel-uninstall-programs.jpg)
3. Next, click on**Programs** .  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111964/7443" target="_top" id="2111964">
  <img src="//a.impactradius-go.com/display-ad/7443-2111964" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111964/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![control panel uninstall programs view installed updatges](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/control-panel-uninstall-programs-view-installed-updatges.jpg)
4. Click on**View installed updates** under**Programs and Features** . This will open the**Uninstall updates** section in the**Settings** app. Alternatively, go to **Settings > Windows Update > Update history > Uninstall updates** to access the same.  
![uninstall windows updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/uninstall-windows-updates.jpg)
5. Locate the problematic update (**KB5005565**) and click on**Uninstall** .
6. Click**Uninstall** again to confirm the action. Wait for the update to uninstall and restart your PC to apply the changes.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137220/26400" target="_top" id="2137220">
  <img src="//a.impactradius-go.com/display-ad/26400-2137220" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137220/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://common-error.techidaily.com/banish-windows-store-issue-0x80072ee7-with-these-proven-fixes/"><u>Banish Windows Store Issue 0X80072EE7 with These Proven Fixes</u></a></li>
<li><a href="https://extra-tips.techidaily.com/boosting-engagement-the-key-to-successful-tiktok-unpack-videos/"><u>Boosting Engagement The Key to Successful TikTok Unpack Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combatting-winrars-summation-missteps-with-6-fixes/"><u>Combatting WinRAR's Summation Missteps with 6 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cut-down-installation-time-with-proper-deps-setup/"><u>Cut Down Installation Time with Proper Deps Setup</u></a></li>
<li><a href="https://extra-hints.techidaily.com/decoding-the-freeze-in-photo-booth-videos/"><u>Decoding the Freeze in Photo Booth Videos</u></a></li>
<li><a href="https://driver-install.techidaily.com/direct-to-digital-jetprot-8710-drivers-for-enhanced-windows-printing/"><u>Direct to Digital: JetProt 8710 Drivers for Enhanced Windows Printing</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/do-you-want-to-know-how-to-freeze-video-check-this-article-and-find-the-easiest-way-to-freeze-frame-of-your-video-for-2024/"><u>Do You Want to Know How to Freeze Video? Check This Article and Find the Easiest Way to Freeze Frame of Your Video for 2024</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723341658979-experience-the-powerful-symphony-with-blueants-soundblade-vibrant-sounds-and-style-combined/"><u>Experience the Powerful Symphony with BlueAnt's Soundblade - Vibrant Sounds & Style Combined!</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-3-effective-methods-to-fake-gps-location-on-android-for-your-oneplus-12-drfone-by-drfone-virtual/"><u>In 2024, 3 Effective Methods to Fake GPS location on Android For your OnePlus 12 | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-asus-rog-phone-8-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Asus ROG Phone 8 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-windows-11-calendar-space/"><u>Navigating the Windows 11 Calendar Space</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-disabled-memory-feature-on-new-windows-11/"><u>Overcoming Disabled Memory Feature on New Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-call-logs-from-infinix-note-30-5g-by-fonelab-android-recover-call-logs/"><u>Possible solutions to restore deleted call logs from Infinix Note 30 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-exquisite-photography-building-inspiring-slideshows-and-fixing-spots-in-win11/"><u>Step-by-Step Guide to Exquisite Photography: Building Inspiring Slideshows & Fixing Spots in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-overcome-ownership-challenges-with-org-managed-configurations-in-windows-11/"><u>Tips to Overcome Ownership Challenges with Org-Managed Configurations in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-and-11-pro-mastery-a-guide-to-successfully-uninstall-and-reinstall-extras/"><u>Windows 11 & 11 Pro Mastery: A Guide to Successfully Uninstall and Reinstall Extras</u></a></li>
</ul></div>

