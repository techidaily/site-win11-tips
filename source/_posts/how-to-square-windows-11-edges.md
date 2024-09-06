---
title: How to Square Windows 11 Edges
date: 2024-09-05T19:32:03.421Z
updated: 2024-09-06T19:32:03.421Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Square Windows 11 Edges
excerpt: This Article Describes How to Square Windows 11 Edges
keywords: Square W11 Panels,Edge Smoothing Tips,Win11 Edge Fixes,Window Squaring Guide,Win11 Borders Adjust,Edges Alignment Windows,Perfected Windows 11 Edges
thumbnail: https://thmb.techidaily.com/f52859b8cd9dd422cf0c712696f19c9a8d2ea9a54ae99a71f15e709bfd0f373c.jpg
---

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2126493/26400" target="_top" id="2126493">
  <img src="//a.impactradius-go.com/display-ad/26400-2126493" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2126493/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Square Windows 11 Edges

 With Windows 11, Microsoft brought several visual changes to its desktop operating system, including the notable addition of rounded corners for windows, menus, and dialog boxes. While the new design update has been widely embraced by many users, there are those who prefer a more traditional look with sharp corners.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

## 1\. How to Disable Rounded Corners in Windows 11 Using a Third-Party Tool

**Win11DisableOrRestoreRoundedCorners** is an open-source tool available on GitHub that can help you disable rounded corners on your Windows 11 PC. Since this tool modifies your PC's system files to remove the rounded corners, it's a good idea to [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before using it.

1. Head over to GitHub’s website to [download the Win11DisableOrRestoreRoundedCorners tool](https://github.com/valinet/Win11DisableRoundedCorners/releases).
2. Double-click the downloaded executable file to run it.
3. If you see the Microsoft Defender SmartScreen window, click on **More info** and then select **Run anyway**.
4. Select **Yes** when the User Account Control (UAC) prompt appears.  
![Microsoft Defender SmartScreen Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/microsoft-defender-smartscreen-window.jpg)

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2135315/14409" target="_top" id="2135315">
  <img src="//a.impactradius-go.com/display-ad/14409-2135315" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2135315/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Once you complete the above steps, a PowerShell window should appear and disable rounded corners on your PC. Here’s a glimpse of how your windows will look once the rounded corners are disabled.

![Square Corners in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/square-corners-in-windows-11.jpg)

 Note that this tool will not disable rounded corners in the Start menu or some modern apps. If you want to revert the changes later, simply run the downloaded EXE file again.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115918/19272" target="_top" id="2115918">
  <img src="//a.impactradius-go.com/display-ad/19272-2115918" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115918/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. How to Disable Rounded Corners in Windows 11 Using the Registry Editor

 Don't want to use a third-party tool? No problem. You can also disable rounded corners in Windows 11 by making changes to the Windows Registry. However, it's crucial to exercise caution, as modifying registry files without proper knowledge can be risky.

 Before you proceed, consider [backing up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/), just in case. After that, use these steps to disable rounded corners via the Registry Editor:

1. Press **Win + S** to open the search menu.
2. Type in **registry editor** and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Navigate to **Computer > HKEY\_CURRENT\_USER > Software > Microsoft > Windows > DWM**.
5. Right-click on the **DWM** key and select **New > DWORD (32-bit) Value**. Rename it to **UseWindowFrameStagingBuffer**.
6. Double-click the newly created DWORD and enter **0** in the **Value data** field. Then, click **OK**.
7. [Restart your PC](https://www.makeuseof.com/windows-restart-methods/) to apply the changes.  
![Disable Rounded Corners in Windows 11 via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-rounded-corners-in-windows-11-via-registry-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123474/16836" target="_top" id="2123474">
  <img src="//a.impactradius-go.com/display-ad/16836-2123474" border="0" alt="https://techidaily.com" width="300" height="50"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123474/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you want to reverse the above change later, repeat the same steps mentioned earlier and change the value data for the **UseWindowFrameStagingBuffer** to **1**.

## 3\. How to Disable Rounded Corners in Windows 11 via Device Manager

 Another way to remove rounded corners in Windows 11 is by disabling the graphics driver on your PC. However, it is important to consider a few caveats. Firstly, disabling the graphics driver will result in reduced display performance, lower screen resolutions, and the deactivation of any visual effects. Secondly, this will also prevent you from running any graphics-intensive applications or games on your PC.

 If you are fine with these trade-offs, use these steps to disable rounded corners via Device Manager.

1. Press **Win + X** to open the Power User menu.
2. Select **Device Manager** from the list.
3. Double-click on **Display adapters** to expand it.
4. Right-click on your display driver and select **Disable device**.  
![Disable Graphics Driver on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-graphics-driver-on-windows-11.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118325/7443" target="_top" id="2118325">
  <img src="//a.impactradius-go.com/display-ad/7443-2118325" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118325/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Once the graphics driver is disabled, you should see square corners on all windows and menus in Windows 11\. If you want to undo this change later, simply enable the graphics driver via Device Manager.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130528/26400" target="_top" id="2130528">
  <img src="//a.impactradius-go.com/display-ad/26400-2130528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130528/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Disabling Rounded Corners in Windows 11 Is Easy

 Using a third-party tool is arguably the most convenient way to remove rounded corners in Windows 11\. However, if you prefer to rely on the native methods, you can use the Registry Editor or Device Manager instead.

 Disabling rounded corners isn’t the only way to get the classic look of previous Windows versions. You can also use a third-party tool like the ExplorerPatcher to make Windows 11 look like Windows 10\.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-screen-grab.techidaily.com/new-visual-data-harvester-for-2024/"><u>[New] Visual Data Harvester for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-capturing-the-web-in-motion-a-compact-list-of-leading-recorders/"><u>[Updated] 2024 Approved  Capturing the Web in Motion  A Compact List of Leading Recorders</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-in-2024-ultimate-viewing-vistas-backdrop-recommendations/"><u>[Updated] In 2024, Ultimate Viewing Vistas  Backdrop Recommendations</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-perfect-thumbnail-size-for-click-through-rates/"><u>[Updated] Perfect Thumbnail Size for Click-Through Rates</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-transforming-xbox-experiences-through-effective-capture-techniques/"><u>2024 Approved  Transforming Xbox Experiences Through Effective Capture Techniques</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/blend-tech-geniuses-setting-up-chromecast-compatibility-with-fire-stick/"><u>Blend Tech Geniuses: Setting Up Chromecast Compatibility with Fire Stick</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/chromatic-choices-discover-the-best-5-screens-today-for-2024/"><u>Chromatic Choices  Discover the Best 5 Screens Today for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-forbidden-save-messages-on-windows-pcs/"><u>Clearing Up 'Forbidden Save' Messages on Windows PCs</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/comprehensive-analysis-of-linksys-velop-the-ultimate-guide-to-a-superior-wireless-mesh-system/"><u>Comprehensive Analysis of Linksys Velop: The Ultimate Guide to a Superior Wireless Mesh System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-world-of-warcrafts-fatal-problem-132-on-windows/"><u>Conquering World of Warcraft's Fatal Problem #132 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-failed-task-sequences-fixing-error-0x8007000f/"><u>Dealing with Failed Task Sequences: Fixing Error 0X8007000f</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-steps-to-access-and-manage-printers-efficiently/"><u>Decoding Windows: Steps to Access and Manage Printers Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/download-and-save-your-cortana-activity-log/"><u>Download and Save Your Cortana Activity Log</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/elevate-your-skycraft-copilot-pro-explained/"><u>Elevate Your Skycraft - Copilot Pro Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-windows-update-requests/"><u>Eliminating Windows Update Requests</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/excel-file-recovery-recover-corrupt-excel-2003-files-easily-stellar-by-stellar-guide/"><u>Excel File Recovery – Recover Corrupt Excel 2003 Files Easily | Stellar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/finding-ideal-nvidia-drivers-for-gamers-or-studios/"><u>Finding Ideal Nvidia Drivers for Gamers or Studios</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-update-error-a-step-by-step-guide/"><u>Fixing Windows Update Error: A Step-By-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-zero-to-hero-hyper-v-setup-for-w11-home-users/"><u>From Zero to Hero: Hyper-V Setup for W11 Home Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/getting-past-the-roadblock-solutions-for-unpreviewable-files-in-email-apps/"><u>Getting Past the Roadblock: Solutions for Unpreviewable Files in Email Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-safeguard-your-pc-by-altering-password-on-win-11/"><u>How to Safeguard Your PC by Altering Password on Win 11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/ignite-your-online-discovery-journey-experience-why-perplexity-ai-is-the-top-secret-to-winning-at-google-searches/"><u>Ignite Your Online Discovery Journey: Experience Why Perplexity AI Is the Top Secret to Winning at Google Searches</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-image-fusion-merging-photos-into-one-masterpiece/"><u>In 2024, Image Fusion  Merging Photos Into One Masterpiece</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-approaches-to-maximize-windows-11s-beginning/"><u>Innovative Approaches to Maximize Windows 11'S Beginning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-savings-techniques-for-thrifty-windows-10-enthusiasts/"><u>Key Savings Techniques for Thrifty Windows 10 Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lowering-wasteful-resource-usage-by-ntoskrnlexe/"><u>Lowering Wasteful Resource Usage by Ntoskrnl.exe</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-system-fixes-reviving-troubleshooters-in-windows-11/"><u>Mastering System Fixes: Reviving Troubleshooters in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-mysterious-obs-error-a-step-by-step-approach/"><u>Overcoming Mysterious OBS Error: A Step-by-Step Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-wi-fi-setup-obstacles-bridging-actions-on-windows-os/"><u>Overcoming Wi-Fi Setup Obstacles: Bridging Actions on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-clock-anomalies-in-google-chrome/"><u>Overcoming Windows Clock Anomalies in Google Chrome</u></a></li>
<li><a href="https://fake-location.techidaily.com/prevent-cross-site-tracking-on-apple-iphone-14-plus-and-browser-drfone-by-drfone-virtual-ios/"><u>Prevent Cross-Site Tracking on Apple iPhone 14 Plus and Browser | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-disconnecting-onedrive-from-your-windows-explorer-view/"><u>Quick Fix: Disconnecting OneDrive From Your Windows Explorer View</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-text-display-issue-on-win11-msresouce/"><u>Rectifying Text Display Issue on Win11: MsResouce</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-accessible-wastecan-icon-on-windows-11/"><u>Reinstating Accessible Wastecan Icon on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reliable-re-boot-methods-your-explore-experience-win-11/"><u>Reliable Re-Boot Methods: Your Explore Experience, Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-legacy-systems-for-grandparent-users/"><u>Simplifying Legacy Systems for Grandparent Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simultaneous-file-release-techniques-for-windows-enthusiasts/"><u>Simultaneous File Release Techniques for Windows Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-fill-void-of-msvcr120dll-in-windows-os/"><u>Solutions to Fill Void of MSVCR120.DLL in Windows OS</u></a></li>
<li><a href="https://techtrends.techidaily.com/star-trek-series-marathon-watching-from-the-original-through-to-beyond/"><u>Star Trek Series Marathon: Watching From The Original Through to Beyond</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-locating-and-using-the-component-services-tool/"><u>Step-by-Step: Locating and Using the Component Services Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-into-snap-mastery-configuring-windows-with-powertoys/"><u>Step-Into Snap Mastery: Configuring Windows with PowerToys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-no-detected-fingerprint-on-windows-systems/"><u>Tackling No Detected Fingerprint on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-1011-error-0x0000004e-quick-guide/"><u>Tackling Windows 10/11 Error 0X0000004E Quick Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-tricks-bridging-airpods-and-windows-devices/"><u>Tech Tricks: Bridging AirPods & Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-win11-mouse-settings-and-controls/"><u>The Ultimate Guide to Win11 Mouse Settings & Controls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-system-speed-with-enhanced-window-run-utility/"><u>Transforming System Speed with Enhanced Window Run Utility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-guide-stop-vmfreeze-and-freezes-in-windows-11/"><u>Troubleshooting Guide: Stop VMfreeze & Freezes in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-printing-woes-a-guide-to-windows-11/"><u>Troubleshooting Printing Woes: A Guide to Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-notepad-freeze-issues/"><u>Troubleshooting Windows Notepad Freeze Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-the-calculator-a-windows-11-primer/"><u>Uncovering the Calculator: A Windows 11 Primer</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/unlock-creative-potential-with-no-cost-green-screen-knowledge-from-top-4-educational-channels-for-2024/"><u>Unlock Creative Potential with No-Cost Green Screen Knowledge From Top 4 Educational Channels for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>