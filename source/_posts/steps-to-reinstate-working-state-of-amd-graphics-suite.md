---
title: Steps to Reinstate Working State of AMD Graphics Suite
date: 2024-08-16T02:19:47.119Z
updated: 2024-08-17T02:19:47.119Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Reinstate Working State of AMD Graphics Suite
excerpt: This Article Describes Steps to Reinstate Working State of AMD Graphics Suite
keywords: Reinstating AMD Graphics,AMD Graphics Suite Work,Restore AMD Graphics Status,Resetting AMD Graphics,AMD Graphics Recovery Steps,Reactivate AMD Graphics,Reviving AMD Graphic Suite
thumbnail: https://thmb.techidaily.com/0b4741c5a95a2eb27426575b3e77bfe93d41de0ce8390e58e556e7c4a810a2f7.jpg
---

## Steps to Reinstate Working State of AMD Graphics Suite

 Users who need to fix AMD Radeon Software not working can’t open that app and access its settings. Are you among those users? If so, you can fix AMD Radeon Software not opening on a Windows PC with the resolutions below.

## 1\. Run AMD Radeon Software as an Administrator

 Users typically select to run AMD Radeon Software without admin rights from the context menu. Instead, try running AMD Radeon Software as an administrator to see if that helps. You can do that by pressing the **Windows** logo button + **S**, inputting **AMD** in the search box, and selecting **Run as administrator** for the AMD app found.

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/run-as-administrator-option.jpg)

 If that works, permanently set AMD Radeon Software to run with elevated privileges. To do so, follow the steps in this article about [always running apps as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/). However, note that you can’t permanently set the AMD Radeon Software MS Store app to run as administrator.

## 2\. End the RadeonSoftware Process Tree

 First, check if Task Manager shows a process for AMD Radeon Software. If it does, that effectively means the app is already running in the background. Terminating the process tree for AMD Radeon Software might then fix the issue. You can close the RadeonSoftware process tree like this:

1. Press the **Ctrl** \+ **Shift** \+ **Esc** keyboard key combination to activate Task Manager.
2. Select Task Manager’s **Details** tab.
3. Look for and right-click **RadeonSoftware.exe** to select the **End process tree** option.  
![The End process tree option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/end-process-tree-option.jpg)
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Click on the **End process tree** button to confirm.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Delete the CN Folder

 Corrupted profile data often causes the AMD Radeon Software to stop working. You can fix that by deleting the CN folder, which contains Radeon profile data. Erasing that folder rebuilds the profile. This is how you can delete the CN folder:

1. Utilize the **Windows key + R** keyboard shortcut to access the Run dialog.
2. Type **%appdata%** into Run and click **OK** to access a Roaming directory.
3. Click AppData in Explorer’s folder location bar.
4. Open the Local subfolder inside the AppData folder.
5. Click the AMD folder to go inside it.  
![the-CN-folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/the-cn-folder.jpg)
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Right-click the CN folder and select **Delete**.

 Alternatively, you can try erasing a specific file within the CN folder, which users have also confirmed works. To do that, open the CN folder to view its contents. Right-click the **gmdb.blb** file in that directory and select Delete.

## 4\. Disable and Re-enable the AMD Radeon Graphics Adapter

 Disabling and re-enabling the AMD graphics adapter is another potential resolution users confirm can kick-start AMD Radeon Software. You can disable and re-enable the AMD graphics adapter on your PC as follows:

1. First, [open Device Manager](https://www.makeuseof.com/windows-open-device-manager/) (press the **Windows key** \+ **X** hotkey and select the shortcut for that tool).
2. Double-click the **Display adapters** category to extend it.
3. Right-click the AMD Radeon graphics card to select **Disable device**.  
![The Disable device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/disable-device-option.jpg)
4. Click on **Yes** when asked to confirm the selected option.
5. Wait a minute and right-click the AMD Radeon graphics card again to select **Enable device**.

## 5\. Update AMD Graphics Driver

 A faulty or old AMD driver on your PC could be a possible cause for the Radeon software not working. You can fix that by installing the latest AMD driver for your PC’s graphics card.

 Check out our guide to [updating graphics drivers on Windows](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/) for further details about how to apply this potential fix.

![A Download option for an AMD graphics driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/amd-driver-download-page.jpg)

## 6\. Restore the Previous AMD Driver Installed on Your PC

 Sometimes buggy new graphics drivers can cause issues, which is why NVIDIA and AMD release hotfixes. If your PC already has the latest AMD driver, restoring the previous one installed could be a viable solution for some users.

 You can do that by selecting a **Roll Back Driver** option, as covered in our guide on [rolling back graphics drivers on Windows](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/).

![The Roll Back Driver option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/roll-back-driver-option.jpg)
<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Set Windows 11/10 to Clean Boot

 A conflicting background program could be another factor for AMD Radeon not opening. The best way to remedy this possible cause is to configure your PC to clean boot and restart it. This will disable third-party apps and services automatically starting with Windows.

 To apply a clean boot, you’ll need to remove apps and services from the startup with Task Manager and MSConfig. Our article about [performing a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/) includes specific instructions for how you can disable the required startup items. Restart your PC after disabling the startup items and select to open AMD Radeon.

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/services-tab-in-msconfig.jpg)
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 8\. Edit the CN Registry Key

 Editing the **CN** registry key is resolution confirmed to fix the “Radeon Settings and Driver versions do not match” error message some users see when they try to start AMD Radeon. This registry fix involves entering a new value for the **DriverVersion** string in the **CN** key. These are the steps for applying this registry fix:

1. First, open the **Display adapters** category within Device Manager, as instructed for steps one and two of this guide’s fourth resolution.
2. Click the AMD graphics card with the right mouse button and select **Properties**.
3. Select **Driver** on the tab bar.
4. Drag the cursor over the driver number on that tab and press **Ctrl** \+ **C** to copy.  
![A driver version number](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/driver-version-detail.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
5. Close the properties window and Device Manager tool.

 Now, [open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-open-registry-editor/) before continuing.

1. Clear the registry address bar to input the following key location there:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\AMD\CN`
2. Double-click the **DriverVersion** string in the **CN** registry key.  
![The Value data box for the DriverVersion string](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/value-data-box.jpg)
<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Clear the **Value data** box.
4. Press the **Ctrl** \+ **V** hotkey to paste the copied driver version number into the **Value data** box.  
![The Value data box for the DriverVersion string](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/value-data-box.jpg)
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Select **OK** in the Edit String window.

## 9\. Reinstall the AMD Radeon Software

 Reinstalling AMD Radeon Software can also fix variable issues that prevent that app from starting. You can remove AMD Radeon with the Control Panel or Settings methods in our guide to [uninstalling Windows software](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/). Or you can utilize a third-party uninstaller app to remove that software and thoroughly erase its leftovers.

 To reinstall that app, open this [AMD Radeon Software Microsoft Store page](https://apps.microsoft.com/detail/amd-radeon-software/9NZ1BJQN6BHL?hl=en-US&gl=US). Click the **Install** and **Open in Microsoft Store** buttons; select **Get** to install the AMD Radeon Software.

![The AMD Radeon Software page on Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/amd-radeon-software.jpg)

<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Utilize Your AMD Radeon Software Again

 AMD Radeon Software is undoubtedly important to access for configuring graphical settings. The potential resolutions in this guide have enabled many users to fix AMD Radeon not working and access its settings again. So, applying those Windows 11/10 fixes will probably kick-start AMD Radeon on your PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-recording.techidaily.com/new-2023-facebook-live-video-downloaders-for-2024/"><u>[New] 2023 Facebook Live Video Downloaders for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-blueprint-for-creating-viral-trailers-in-the-world-of-youtube/"><u>[New] 2024 Approved  Blueprint for Creating Viral Trailers in the World of YouTube</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-enhancing-text-realism-with-illustrators-tools/"><u>[New] Enhancing Text Realism with Illustrator's Tools</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-advanced-tips-for-blending-modes-in-vfx/"><u>[New] In 2024, Advanced Tips for Blending Modes in VFX</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-boomerang-brilliance-keeping-users-hooked-on-ig/"><u>[New] In 2024, Boomerang Brilliance  Keeping Users Hooked on IG</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-streamers-dilemma-is-vlc-superior-to-mpc/"><u>[New] In 2024, Streamer's Dilemma  Is VLC Superior to MPC?</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-ultimate-capture-assistant-az-audits-and-alternatives-for-2024/"><u>[New] Ultimate Capture Assistant - AZ Audits & Alternatives for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-elevating-your-gopro-footage-through-color-grading/"><u>[Updated] Elevating Your GoPro Footage Through Color Grading</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-gamers-sound-selection-top-5-noise-canceling-earbuds/"><u>[Updated] Gamers’ Sound Selection  Top 5 Noise-Canceling Earbuds</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-fifa-video-highlights-top-youtube-data-infographics/"><u>[Updated] In 2024, FIFA Video Highlights  Top YouTube Data Infographics</u></a></li>
<li><a href="https://blog-min.techidaily.com/2-ways-to-transfer-text-messages-from-vivo-y100-5g-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>2 Ways to Transfer Text Messages from Vivo Y100 5G to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-step-by-step-windows-10-audio-capture/"><u>2024 Approved  Step-by-Step  Windows 10 Audio Capture</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-guide-overcoming-launch-failures-in-obs-studio/"><u>Comprehensive Guide: Overcoming Launch Failures in OBS Studio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/controlling-metrics-on-your-windows-11-wifi-networks/"><u>Controlling Metrics on Your Windows 11 Wifi Networks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-missing-essentials-issue-on-windows-11-system/"><u>Correcting 'Missing Essentials' Issue on Windows 11 System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/countering-sudden-invisibility-in-win-based-gaming/"><u>Countering Sudden Invisibility in Win-Based Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphraning-the-message-of-crossed-out-icons-on-files/"><u>Deciphraning: The Message of Crossed-Out Icons on Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-unauthorized-users-4-routines-for-restraining-windows-access/"><u>Eliminating Unauthorized Users: 4 Routines for Restraining Windows Access</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-error-code-xc0f1103f-with-nvidias-geforce-now/"><u>Eradicating Error Code Xc0f1103f with NVIDIA's GeForce Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-track-command-management-in-windows-1011/"><u>Fast-Track Command Management in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-access-the-protected-windowsapps-folder-on-windows/"><u>How to Access the Protected WindowsApps Folder on Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-life360-on-windows-pc-for-vivo-g2-drfone-by-drfone-virtual-android/"><u>How to Use Life360 on Windows PC For Vivo G2? | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-3-effective-methods-to-fake-gps-location-on-android-for-your-vivo-s18e-drfone-by-drfone-virtual/"><u>In 2024, 3 Effective Methods to Fake GPS location on Android For your Vivo S18e | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-techniques-to-transfer-data-from-nokia-g310-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Techniques to Transfer Data from Nokia G310 to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-life360-notify-when-you-log-out-on-realme-note-50-drfone-by-drfone-virtual-android/"><u>In 2024, Does Life360 Notify When You Log Out On Realme Note 50? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-approaches-to-adding-items-to-win-11-contextual-menu/"><u>Innovative Approaches to Adding Items to Win 11 Contextual Menu</u></a></li>
<li><a href="https://win-amazing.techidaily.com/instant-installation-targus-universal-docking-station-driver-downloads/"><u>Instant Installation: Targus Universal Docking Station Driver Downloads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-mouse-settings-in-windows-11-with-minimal-hassle/"><u>Mastering Mouse Settings in Windows 11 with Minimal Hassle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/outsmarting-windows-logon-requirements/"><u>Outsmarting Windows Logon Requirements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-to-spur-up-your-printers-speed/"><u>Quick Fixes to Spur Up Your Printer's Speed</u></a></li>
<li><a href="https://extra-hints.techidaily.com/redefining-collaboration-the-power-of-immersive-vr/"><u>Redefining Collaboration  The Power of Immersive VR</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refreshing-graphics-drivers-on-windows-11-systems/"><u>Refreshing Graphics Drivers on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-original-windows-backup-configurations/"><u>Regaining Original Windows Backup Configurations</u></a></li>
<li><a href="https://program-issues.techidaily.com/resolved-chronicles-of-arise-overcoming-ue4s-critical-bugs/"><u>Resolved: Chronicles of Arise - Overcoming UE4's Critical Bugs</u></a></li>
<li><a href="https://location-social.techidaily.com/set-your-preferred-job-location-on-linkedin-app-of-your-realme-10t-5g-drfone-by-drfone-virtual-android/"><u>Set Your Preferred Job Location on LinkedIn App of your Realme 10T 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shed-heavy-weights-pure-power-windows-11-tiny/"><u>Shed Heavy Weights: Pure Power, Windows 11 Tiny</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-sound-issue-in-audacity-on-windows-1111/"><u>Steps to Resolve Sound Issue in Audacity on Windows 11/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-reinstallation-when-applications-dont-start-on-ms-marketplace/"><u>Strategies for Reinstallation When Applications Don't Start on MS Marketplace</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/the-essentials-of-crafting-youtube-videos-from-start-to-finish/"><u>The Essentials of Crafting YouTube Videos From Start to Finish</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-leading-windows-brightness-management-apps-and-utilities/"><u>The Leading Windows Brightness Management Apps & Utilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-computere-clock-display-top-5-windows-screensaver-apps-for-dynamic-visuals/"><u>Transform Your Computer’e Clock Display: Top 5 Windows Screensaver Apps for Dynamic Visuals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfreezing-and-restoring-itunes-on-windows-devices/"><u>Unfreezing and Restoring iTunes on Windows Devices</u></a></li>
<li><a href="https://activate-lock.techidaily.com/unlocking-an-icloud-locked-ipad-and-iphone-6-by-drfone-ios/"><u>Unlocking an iCloud Locked iPad and iPhone 6</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unpacking-error-0x80070522-in-windows-restore-client-access-rights/"><u>Unpacking Error 0X80070522 in Windows: Restore Client Access Rights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-your-pcs-onedrive-mysteries-solutions-here/"><u>Unraveling Your PC's OneDrive Mysteries: Solutions Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-secrets-of-monitoring-network-traffic-on-windows-11/"><u>Unveiling the Secrets of Monitoring Network Traffic on Windows 11</u></a></li>
</ul></div>
