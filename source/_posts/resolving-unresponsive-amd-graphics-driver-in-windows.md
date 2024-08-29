---
title: Resolving Unresponsive AMD Graphics Driver in Windows
date: 2024-08-28T01:15:45.017Z
updated: 2024-08-29T01:15:45.017Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Unresponsive AMD Graphics Driver in Windows
excerpt: This Article Describes Resolving Unresponsive AMD Graphics Driver in Windows
keywords: Fix AMD GPU Error,Resolve Graphics Failure,Update AMD Drivers,Windows Graphic Glitches,Fix AMD Driver Issue,AMD Graphics Troubleshooting,Reinstall Graphics Software
thumbnail: https://thmb.techidaily.com/54da0f4f94eef8925e725ad6e5d476f72d3b4dfe3f3f6a2e608d839212aa9eeb.jpg
---

## Resolving Unresponsive AMD Graphics Driver in Windows

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
4. Click on the **End process tree** button to confirm.

## 3\. Delete the CN Folder

 Corrupted profile data often causes the AMD Radeon Software to stop working. You can fix that by deleting the CN folder, which contains Radeon profile data. Erasing that folder rebuilds the profile. This is how you can delete the CN folder:

1. Utilize the **Windows key + R** keyboard shortcut to access the Run dialog.
2. Type **%appdata%** into Run and click **OK** to access a Roaming directory.
3. Click AppData in Explorer’s folder location bar.
4. Open the Local subfolder inside the AppData folder.
5. Click the AMD folder to go inside it.  
![the-CN-folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/the-cn-folder.jpg)
6. Right-click the CN folder and select **Delete**.

 Alternatively, you can try erasing a specific file within the CN folder, which users have also confirmed works. To do that, open the CN folder to view its contents. Right-click the **gmdb.blb** file in that directory and select Delete.

## 4\. Disable and Re-enable the AMD Radeon Graphics Adapter

 Disabling and re-enabling the AMD graphics adapter is another potential resolution users confirm can kick-start AMD Radeon Software. You can disable and re-enable the AMD graphics adapter on your PC as follows:

1. First, [open Device Manager](https://www.makeuseof.com/windows-open-device-manager/) (press the **Windows key** \+ **X** hotkey and select the shortcut for that tool).
2. Double-click the **Display adapters** category to extend it.
3. Right-click the AMD Radeon graphics card to select **Disable device**.  
![The Disable device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/disable-device-option.jpg)
4. Click on **Yes** when asked to confirm the selected option.
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
5. Wait a minute and right-click the AMD Radeon graphics card again to select **Enable device**.

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Update AMD Graphics Driver

 A faulty or old AMD driver on your PC could be a possible cause for the Radeon software not working. You can fix that by installing the latest AMD driver for your PC’s graphics card.

 Check out our guide to [updating graphics drivers on Windows](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/) for further details about how to apply this potential fix.

![A Download option for an AMD graphics driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/amd-driver-download-page.jpg)

## 6\. Restore the Previous AMD Driver Installed on Your PC

 Sometimes buggy new graphics drivers can cause issues, which is why NVIDIA and AMD release hotfixes. If your PC already has the latest AMD driver, restoring the previous one installed could be a viable solution for some users.

 You can do that by selecting a **Roll Back Driver** option, as covered in our guide on [rolling back graphics drivers on Windows](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/).

![The Roll Back Driver option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/roll-back-driver-option.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Set Windows 11/10 to Clean Boot

 A conflicting background program could be another factor for AMD Radeon not opening. The best way to remedy this possible cause is to configure your PC to clean boot and restart it. This will disable third-party apps and services automatically starting with Windows.

 To apply a clean boot, you’ll need to remove apps and services from the startup with Task Manager and MSConfig. Our article about [performing a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/) includes specific instructions for how you can disable the required startup items. Restart your PC after disabling the startup items and select to open AMD Radeon.

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/services-tab-in-msconfig.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## 8\. Edit the CN Registry Key

 Editing the **CN** registry key is resolution confirmed to fix the “Radeon Settings and Driver versions do not match” error message some users see when they try to start AMD Radeon. This registry fix involves entering a new value for the **DriverVersion** string in the **CN** key. These are the steps for applying this registry fix:

1. First, open the **Display adapters** category within Device Manager, as instructed for steps one and two of this guide’s fourth resolution.
2. Click the AMD graphics card with the right mouse button and select **Properties**.
3. Select **Driver** on the tab bar.
4. Drag the cursor over the driver number on that tab and press **Ctrl** \+ **C** to copy.  
![A driver version number](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/driver-version-detail.jpg)
5. Close the properties window and Device Manager tool.
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->

 Now, [open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-open-registry-editor/) before continuing.

1. Clear the registry address bar to input the following key location there:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\AMD\CN`
2. Double-click the **DriverVersion** string in the **CN** registry key.  
![The Value data box for the DriverVersion string](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/value-data-box.jpg)
3. Clear the **Value data** box.
<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Press the **Ctrl** \+ **V** hotkey to paste the copied driver version number into the **Value data** box.  
![The Value data box for the DriverVersion string](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/value-data-box.jpg)
5. Select **OK** in the Edit String window.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 9\. Reinstall the AMD Radeon Software

 Reinstalling AMD Radeon Software can also fix variable issues that prevent that app from starting. You can remove AMD Radeon with the Control Panel or Settings methods in our guide to[uninstalling Windows software](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/). Or you can utilize a third-party uninstaller app to remove that software and thoroughly erase its leftovers.

 To reinstall that app, open this [AMD Radeon Software Microsoft Store page](https://apps.microsoft.com/detail/amd-radeon-software/9NZ1BJQN6BHL?hl=en-US&gl=US). Click the **Install** and **Open in Microsoft Store** buttons; select **Get** to install the AMD Radeon Software.

![The AMD Radeon Software page on Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/amd-radeon-software.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
## Utilize Your AMD Radeon Software Again

 AMD Radeon Software is undoubtedly important to access for configuring graphical settings. The potential resolutions in this guide have enabled many users to fix AMD Radeon not working and access its settings again. So, applying those Windows 11/10 fixes will probably kick-start AMD Radeon on your PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-sites-where-virtual-worlds-come-alive/"><u>[New] 2024 Approved  Sites Where Virtual Worlds Come Alive</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-free-youtube-outro-kings-6-top-suggestions/"><u>[New] In 2024, Free YouTube Outro Kings  6 TOP Suggestions</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-core-components-for-transformative-facebook-advertisements-for-2024/"><u>[Updated] Core Components for Transformative Facebook Advertisements for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/best-performers-top-10-innovative-4k-mirrorless-models-for-2024/"><u>Best Performers  Top 10 Innovative 4K Mirrorless Models for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-coding-repair-x-script-in-ragnarok/"><u>Conquer Coding: Repair X-Script in Ragnarok</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-key-differences-between-exe-software-packages-and-msi/"><u>Deciphering Key Differences Between Exe Software Packages & Msi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-ssd-optimize-with-ssd-fresh-for-windows-users/"><u>Enhance Your SSD: Optimize with SSD Fresh for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-no-supported-device-for-windows-hello-login/"><u>Fixing 'No Supported Device' For Windows Hello Login</u></a></li>
<li><a href="https://change-location.techidaily.com/full-guide-to-catch-100-iv-pokemon-using-a-map-on-vivo-s17-pro-drfone-by-drfone-virtual-android/"><u>Full Guide to Catch 100 IV Pokémon Using a Map On Vivo S17 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gaming-mastery-on-windows-11-top-strategies-for-peak-performance-and-fun/"><u>Gaming Mastery on Windows 11: Top Strategies for Peak Performance and Fun</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-turn-onoff-windows-11-highlight-effect/"><u>Guide to Turn On/Off Windows 11 Highlight Effect</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-activate-w11s-rapid-assistance-feature/"><u>How to Activate W11's Rapid Assistance Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-correct-failed-system-call-error-in-windows-devices/"><u>How to Correct Failed System Call Error in Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-load-drivers-without-sie-compliance-on-pcs/"><u>How to Load Drivers Without SIE Compliance on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-prevent-chromium-from-spontaneously-launching-tabs/"><u>How to Prevent Chromium From Spontaneously Launching Tabs</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-stream-your-xbox-gameplay-to-discord/"><u>How to Stream Your Xbox Gameplay to Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-unstick-scrollbar-fix-for-excel-on-pc/"><u>How to Unstick Scrollbar: Fix for Excel on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/linguistic-harmony-installing-fonts-for-all-windows-users/"><u>Linguistic Harmony: Installing Fonts for All Windows Users</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/managing-a-flip-screen-with-raspberry-pi-tips-and-techniques-for-successful-setup/"><u>Managing a Flip Screen with Raspberry Pi: Tips and Techniques for Successful Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-focus-with-our-select-8-windows-pomodoro-tools/"><u>Maximize Focus with Our Select 8 Windows Pomodoro Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-win11-like-a-pro-with-powerful-command-shortcuts/"><u>Navigate Win11 Like a Pro with Powerful Command Shortcuts</u></a></li>
<li><a href="https://fix-guide.techidaily.com/oneplus-nord-n30-5g-camera-not-working-unexpected-error-fix-it-now-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>OnePlus Nord N30 5G Camera Not Working Unexpected Error? Fix It Now | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-error-0x00000001-in-xbox-game-pass-with-windows-11/"><u>Overcoming Error 0X00000001 in Xbox Game Pass with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-obstructed-operations-by-windows-security/"><u>Overcoming Obstructed Operations by Windows Security</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-upgrade-rejected-error-messages/"><u>Overcoming Windows Upgrade Rejected Error Messages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstate-missing-sound-configuration-in-windows-10/"><u>Reinstate Missing Sound Configuration in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-0x8007045d-fatal-exception-error-on-win-1011/"><u>Resolving 0X8007045D Fatal Exception Error on Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-low-performance-pcs-overcoming-intel-hd-graphics-issues/"><u>Resolving Low-Performance PCs: Overcoming Intel HD Graphics Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securely-hiding-personal-info-on-windows-login/"><u>Securely Hiding Personal Info on Windows Login</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solve-keyboardmouse-not-activating-on-windows-11-after-sleep/"><u>Solve Keyboard/Mouse Not Activating on Windows 11 After Sleep</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-windows-11-unpacking-error-code-0xc1900101/"><u>Solving Windows 11: Unpacking Error Code 0xC1900101</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-portaudio-fault-in-audacity-windows-11/"><u>Steps to Rectify PortAudio Fault in Audacity, Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-prevent-darkened-screens-while-gaming-on-win/"><u>Strategies to Prevent Darkened Screens While Gaming on WIN</u></a></li>
<li><a href="https://driver-install.techidaily.com/surface-pro-4-driver-setup-for-windows-pcs/"><u>Surface Pro 4 Driver Setup for Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/system-debugging-made-easy-locating-and-resolving-error-codes-via-the-power-of-command-prompt/"><u>System Debugging Made Easy: Locating and Resolving Error Codes via the Power of Command Prompt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-o365-cloud-synchronization-hiccups-windows/"><u>Tackling O365 Cloud Synchronization Hiccups (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-diagnostic-failures-on-your-system/"><u>Tackling the Diagnostic Failures on Your System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essentials-to-successfully-install-oracles-jdk-on-your-windows-11-system/"><u>The Essentials to Successfully Install Oracle's JDK on Your Windows 11 System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-window-whisperer-decoding-and-fixing-windows-11-screen-issues/"><u>The Window Whisperer: Decoding and Fixing Windows 11 Screen Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-8-solutions-for-not-found-in-windows-os/"><u>Top 8 Solutions for 'Not Found' In Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-file-disappearance-top-8-methods/"><u>Troubleshooting File Disappearance: Top 8 Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-frozen-lol-startup/"><u>Troubleshooting Frozen LOL Startup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-removing-windows-bt-directories-effectively/"><u>Understanding and Removing Windows ~BT Directories Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-device-functions-in-windows-11s-edge-guards/"><u>Unlocking Device Functions in Windows 11'S Edge Guards</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-hidden-steps-to-fullscreen-integrity/"><u>Unveiling Hidden Steps to Fullscreen Integrity</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-in-2024-melody-and-motion-best-sync-videography-applications-of-the-decades-first-half/"><u>Updated In 2024, Melody and Motion Best-Sync Videography Applications of the Decades First Half</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-reset-reclaim-default-user-access-rights/"><u>Windows 11 Reset: Reclaim Default User Access Rights</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>