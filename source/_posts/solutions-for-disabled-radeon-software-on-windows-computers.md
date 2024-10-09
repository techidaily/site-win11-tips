---
title: Solutions for Disabled Radeon Software on Windows Computers
date: 2024-10-01T21:18:05.178Z
updated: 2024-10-09T06:42:32.725Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solutions for Disabled Radeon Software on Windows Computers
excerpt: This Article Describes Solutions for Disabled Radeon Software on Windows Computers
keywords: Disabled Radeon,Windows Radeon Fixes,Enhanced Graphics PCs,Solve Radeon Glitches,Optimized AMD Graphics,Radeon Performance Tips,Disabled GPU Settings Windows
thumbnail: https://thmb.techidaily.com/72ad6224a96d1332d870ccac31eeed89a25da9895e91d61d746d246092f66e50.png
---

## Solutions for Disabled Radeon Software on Windows Computers

 Users who need to fix AMD Radeon Software not working can’t open that app and access its settings. Are you among those users? If so, you can fix AMD Radeon Software not opening on a Windows PC with the resolutions below.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915830/19272" target="_top" id="1915830">
  <img src="//a.impactradius-go.com/display-ad/19272-1915830" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915830/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Alternatively, you can try erasing a specific file within the CN folder, which users have also confirmed works. To do that, open the CN folder to view its contents. Right-click the **gmdb.blb** file in that directory and select Delete.

## 4\. Disable and Re-enable the AMD Radeon Graphics Adapter

 Disabling and re-enabling the AMD graphics adapter is another potential resolution users confirm can kick-start AMD Radeon Software. You can disable and re-enable the AMD graphics adapter on your PC as follows:

1. First, [open Device Manager](https://www.makeuseof.com/windows-open-device-manager/) (press the **Windows key** \+ **X** hotkey and select the shortcut for that tool).
2. Double-click the **Display adapters** category to extend it.
3. Right-click the AMD Radeon graphics card to select **Disable device**.  
![The Disable device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/disable-device-option.jpg)
4. Click on **Yes** when asked to confirm the selected option.
5. Wait a minute and right-click the AMD Radeon graphics card again to select **Enable device**.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139118/17108" target="_top" id="2139118">
  <img src="//a.impactradius-go.com/display-ad/17108-2139118" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139118/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Update AMD Graphics Driver

 A faulty or old AMD driver on your PC could be a possible cause for the Radeon software not working. You can fix that by installing the latest AMD driver for your PC’s graphics card.

 Check out our guide to [updating graphics drivers on Windows](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/) for further details about how to apply this potential fix.

![A Download option for an AMD graphics driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/amd-driver-download-page.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948895/19272" target="_top" id="1948895">
  <img src="//a.impactradius-go.com/display-ad/19272-1948895" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948895/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Restore the Previous AMD Driver Installed on Your PC

 Sometimes buggy new graphics drivers can cause issues, which is why NVIDIA and AMD release hotfixes. If your PC already has the latest AMD driver, restoring the previous one installed could be a viable solution for some users.

 You can do that by selecting a **Roll Back Driver** option, as covered in our guide on [rolling back graphics drivers on Windows](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/).

![The Roll Back Driver option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/roll-back-driver-option.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1006793/11832" target="_top" id="1006793">
  <img src="//a.impactradius-go.com/display-ad/11832-1006793" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1006793/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Set Windows 11/10 to Clean Boot

 A conflicting background program could be another factor for AMD Radeon not opening. The best way to remedy this possible cause is to configure your PC to clean boot and restart it. This will disable third-party apps and services automatically starting with Windows.

 To apply a clean boot, you’ll need to remove apps and services from the startup with Task Manager and MSConfig. Our article about [performing a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/) includes specific instructions for how you can disable the required startup items. Restart your PC after disabling the startup items and select to open AMD Radeon.

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/services-tab-in-msconfig.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1001446/11832" target="_top" id="1001446">
  <img src="//a.impactradius-go.com/display-ad/11832-1001446" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1001446/11832" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1912746">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1912746.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20231-1912746">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1912746.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fmindmanager.sjv.io%2Fc%2F5597632%2F1912746%2F20231'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1912746/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, [open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-open-registry-editor/) before continuing.

1. Clear the registry address bar to input the following key location there:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\AMD\CN`
2. Double-click the **DriverVersion** string in the **CN** registry key.  
![The Value data box for the DriverVersion string](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/value-data-box.jpg)
3. Clear the **Value data** box.
4. Press the **Ctrl** \+ **V** hotkey to paste the copied driver version number into the **Value data** box.  
![The Value data box for the DriverVersion string](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/value-data-box.jpg)
5. Select **OK** in the Edit String window.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043594/7443" target="_top" id="2043594">
  <img src="//a.impactradius-go.com/display-ad/7443-2043594" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043594/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 9\. Reinstall the AMD Radeon Software

 Reinstalling AMD Radeon Software can also fix variable issues that prevent that app from starting. You can remove AMD Radeon with the Control Panel or Settings methods in our guide to[uninstalling Windows software](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/). Or you can utilize a third-party uninstaller app to remove that software and thoroughly erase its leftovers.

 To reinstall that app, open this [AMD Radeon Software Microsoft Store page](https://apps.microsoft.com/detail/amd-radeon-software/9NZ1BJQN6BHL?hl=en-US&gl=US). Click the **Install** and **Open in Microsoft Store** buttons; select **Get** to install the AMD Radeon Software.

![The AMD Radeon Software page on Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/amd-radeon-software.jpg)

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
<li><a href="https://fox-cloud.techidaily.com/new-in-2024-budget-friendly-cloud-pricing-showdown/"><u>[New] In 2024, Budget-Friendly Cloud Pricing Showdown</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-masterpiece-in-motion-capture-sonys-x1000-action-gear/"><u>2024 Approved Masterpiece in Motion Capture Sony's X1000 Action Gear</u></a></li>
<li><a href="https://win11-tips.techidaily.com/devhome-explained-mastering-windows-11-upgrades/"><u>DevHome Explained: Mastering Windows 11 Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-deep-the-ultimate-win11-mouse-properties-guide/"><u>Dive Deep: The Ultimate Win11 Mouse Properties Guide</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/expert-analysis-why-the-samsung-galaxy-s20-fe-5g-reigns-supreme-in-the-world-of-next-gen-mobile-phones/"><u>Expert Analysis: Why the Samsung Galaxy S20 FE 5G Reigns Supreme in the World of Next-Gen Mobile Phones</u></a></li>
<li><a href="https://technical-tips.techidaily.com/grabacion-de-voz-a-formato-mp3-sin-costo-alguno-convertidor-en-linea-gratuito-con-movavi/"><u>Grabación De Voz a Formato MP3 Sin Costo Alguno - Convertidor en Línea Gratuito Con Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-set-up-custom-hotkeys-for-pasting-pre-defined-text-snippets-in-windows-10-and-11/"><u>How to Set Up Custom Hotkeys for Pasting Pre-Defined Text Snippets in Windows 10 & 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-music-from-motorola-edge-40-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Music from Motorola Edge 40 to iPod | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-new-multiple-ways-how-to-remove-icloud-activation-lock-on-your-apple-iphone-12-mini-by-drfone-ios/"><u>In 2024, New Multiple Ways How To Remove iCloud Activation Lock On your Apple iPhone 12 mini</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-msvcr120dll-missing-message-on-desktops/"><u>Navigating 'Msvcr120_dll' Missing Message on Desktops</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/professional-approaches-for-logging-youtube-streams/"><u>Professional Approaches for Logging YouTube Streams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-in-game-audio-output-solving-windows-issues-in-valorant/"><u>Realigning In-Game Audio Output: Solving Windows Issues in Valorant</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-dormant-devices-with-synapse-on-windows-11/"><u>Reviving Dormant Devices with Synapse on Windows 11</u></a></li>
<li><a href="https://article-posts.techidaily.com/streamlining-your-subtitle-workflow-with-leading-online-tools-for-2024/"><u>Streamlining Your Subtitle Workflow with Leading Online Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-erroneous-code-fixing-0x800713f-mail-glitch-in-windows-11/"><u>Tackling Erroneous Code: Fixing 0X800713F Mail Glitch in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-7-tricks-for-resolving-obs-studios-disconnect-issue-on-windows-pcs/"><u>Top 7 Tricks for Resolving OBS Studio's Disconnect Issue on Windows PCs</u></a></li>
<li><a href="https://tech-revival.techidaily.com/understanding-gptzero-the-ultimate-guide-to-identifying-synthetic-content/"><u>Understanding GPTZero: The Ultimate Guide to Identifying Synthetic Content</u></a></li>
</ul></div>

