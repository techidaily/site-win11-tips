---
title: Comprehensive Fix for MMC Snap In Creation Failure
date: 2024-10-21T18:48:51.194Z
updated: 2024-10-26T17:46:35.501Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Comprehensive Fix for MMC Snap In Creation Failure
excerpt: This Article Describes Comprehensive Fix for MMC Snap In Creation Failure
keywords: MMC Fix Creation Fail,Snapping Issue Resolved,MMC Repair Success,Creative Snap Fixed,MMC Connectivity Cure,Fix MMC Errors,Snapping Restored Properly
thumbnail: https://thmb.techidaily.com/f14d93751e019bfea4a977ac2ac9bc564b77ea9b7c9b8b27159acb247e2b395b.jpg
---

## Comprehensive Fix for MMC Snap In Creation Failure

 The "MMC could not create the snap-in" error has been around for some time and still seem to bug some users now and then. The error occurs when you try to open an administrative tool such as an Event Viewer, Task Scheduler, and so forth.

 Sometimes, the error may also pop up after a Blue Screen of Death (BSOD), causing one or more apps to crash. This error often occurs if the registry configuration of the snap-in is malfunctioning. Here we show a few ways to fix to help you resolve the "MMC could not create the snap-in" error and restore administrative tools access in Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Fix the Broken Registry Configuration for the Snap-In

![delete-registry-key-mmc-snap-in-windows-registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/delete-registry-key-mmc-snap-in-windows-registry.jpg)

 If the registry configuration for the affected snap-in is broken, it may trigger the "MMC could not create the snap-in" error. To fix the issue, you’ll need to delete the corrupt registry entry associated with the snap-in. Here’s how to do it.

 Making incorrect modifications to the Windows Registry involves risk and may cause your system to malfunction. We recommend you [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [make a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) to be on the safe side.

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK**.
3. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\MMC\SnapIns`
4. The **SnapIns** key consists of multiple sub-keys. You need to locate the sub-key identical to the **CLSID** shown in the error message.
5. For example, if the error occurs when opening Event Viewer, you’ll likely see **CLSID: c7b8fb06-bfe1-4c2e-9217-7a69a95bbac4**, and so on. So, note down the **CLSID** shown in the error screen.

1. In the **Registry Editor**, select the sub-key folder with the same name as the error **CLSID**.
2. Next, right-click on the same sub-key folder and select **Delete**.
3. Click **Yes** to confirm the action.
4. Close the **Registry Editor** and restart your computer.
5. After the restart, open the administrative tool snap-in to see if the error is resolved.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047351/19272" target="_top" id="2047351">
  <img src="//a.impactradius-go.com/display-ad/19272-2047351" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047351/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Enable .NET Framework

![enable net framework 3 5 windows features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-net-framework-3-5-windows-features.jpg)

 You can also fix this error by enabling .NET Framework 3.5\. The idea is that one of the snap-ins on your PC may need .NET Framework 3.5 to work. So, if the feature is disabled, you may encounter an error.

 Fortunately, you can easily enable the .NET Framework feature using the Turn Windows features on or off dialog. Here’s how to do it.

 To enable .NET Framework 3.5:

1. Press the **Win** key and type **Windows features** and click on **Turn Windows features on or off** from the search results.
2. In the **Windows Features** dialog, select the **.NET Framework 3.5 (include .NET 2.0 and 3.0)**.
3. Next, click the **Plus** icon to expand the section and select the options ‘**Windows Communications Foundation HTTP Activation**’ and **‘Windows Communications Foundation Non-HTTP Activation**’.
4. Next, click to **Apply** the changes and install the feature.
5. Once installed, you’ll be prompted to restart the computer. Restart your system, and the MMC snap-in should work now.

## 3\. Check for and Repair Corrupt System Files

![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dism-scan-health-restore-health-command-prompt.jpg)

 If you have one or more corrupt system files, it may cause issues with the system apps. You can run the System File Checker tool to determine if the problem is due to system file issues. It will scan and check the integrity of systems files and automatically repair them to fix the problem.

 Microsoft recommends running its built-in Windows image check and repair utility, Deployment Image Servicing and Management (DISM), before running the System File Checker utility.

 If you're not sure how to run either of these tools, we cover both in our guide on [how to repair corrupt Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016143/19272" target="_top" id="2016143">
  <img src="//a.impactradius-go.com/display-ad/19272-2016143" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016143/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Remove and Reinstall the Microsoft Visual C++ Redistributable

![repair microsoft visual c plus plus distributable package](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/repair-microsoft-visual-c-plus-plus-distributable-package.jpg)

 If the issue persists, try to fix and repair issues with the Visual C++ Redistributable package. If there are any issues with the package, it can cause the MMC snap-ins to stop working.

 To repair the Visual C++ Redistributable package:

1. Press **Win + R** to open Run.
2. Type "control" and click **OK** to open Control Panel.
3. In Control Panel, click on **Uninstall a program** under **Programs**.
4. Locate and select the **Microsoft Visual C++ Redistributable** entry and click **Uninstall**.
5. In the **Modify Setup** dialog, click **Repair**. The repair process may take a few minutes to complete.
6. Once done, restart your computer and check for any improvements.

 If the issue persists, reinstalling the Visual C++ Redistributable package may be required. To reinstall the package:

![uninstall microsoft visual c plus plus distributable package](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/uninstall-microsoft-visual-c-plus-plus-distributable-package.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137207/26400" target="_top" id="2137207">
  <img src="//a.impactradius-go.com/display-ad/26400-2137207" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137207/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Select the **Microsoft Visual C++ package** in Control Panel and click on **Uninstall**.
2. Click **Uninstall** in the **Modify Setup** dialog.
3. Click **Finish** to complete uninstallation. Repeat the process for all the Visual C++ Redistributable packages.
4. Once done, head over to the [Microsoft Visual C++ Redistributable package page](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170).
5. Download the latest version of the package available on your computer. Depending on your system compatibility, you can select from ARM64, X86, and X64 architecture versions.
6. Run the executable file to install the package and follow the on-screen instructions.
7. Once installed, restart your computer and check if MMC snap-ins are now working.

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098702/14409" target="_top" id="2098702">
  <img src="//a.impactradius-go.com/display-ad/14409-2098702" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098702/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Fix the MMC Snap-In and Restore Your Administrative Tools on Windows

 This error is triggered when a snap-in malfunctions, which is often a case of broken registry configuration. To fix the issue, you can delete the broken registry sub-key for the affected snap-in. Additionally, enable/re-enable the .NET Framework 3.5\. If not, scan the system for file integrity issues with the DISM and System File Checker utility.

 Alternatively, you can use the Remote Server Administration Tools (RSAT), which has additional features. RSAT is only available on the Pro and Enterprise edition of the Windows OS. However, you can run a PowerShell script to install it on the Windows Home version easily.

 Sometimes, the error may also pop up after a Blue Screen of Death (BSOD), causing one or more apps to crash. This error often occurs if the registry configuration of the snap-in is malfunctioning. Here we show a few ways to fix to help you resolve the "MMC could not create the snap-in" error and restore administrative tools access in Windows.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-direct.techidaily.com/new-voice-to-text-an-all-inclusive-guide-to-googles-document-feature-for-2024/"><u>[New] Voice to Text An All-Inclusive Guide to Google's Document Feature for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-a-jargon-primer-for-virtual-experiences/"><u>[Updated] A Jargon Primer for Virtual Experiences</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-elevate-your-channels-popularity-with-12-key-growth-techniques-for-2024/"><u>[Updated] Elevate Your Channel's Popularity with 12 Key Growth Techniques for 2024</u></a></li>
<li><a href="https://fox-that.techidaily.com/banish-that-twinkle-seventh-seal-secrets-for-tackling-smartphone-screen-fluctuations/"><u>Banish that Twinkle: Seventh-Seal Secrets for Tackling Smartphone Screen Fluctuations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/custom-desktop-organization-stick-gmail-on-windows-edge/"><u>Custom Desktop Organization: Stick Gmail on Windows Edge</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-graphics-performance-with-more-vram/"><u>Elevating Graphics Performance with More VRAM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/everything-you-need-to-know-about-windows-screen-savers/"><u>Everything You Need to Know About Windows Screen Savers</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-error-495-while-downloadupdating-android-apps-on-poco-f5-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Error 495 While Download/Updating Android Apps On Poco F5 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/mastering-iphoneandroid-the-best-slo-mo-camera-app-compilation-for-2024/"><u>Mastering iPhone/Android The Best Slo-Mo Camera App Compilation for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-window-management-utilizing-end-task-option-windows-11/"><u>Mastering the Art of Window Management: Utilizing End Task Option (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefine-your-users-profile-path-with-simple-steps/"><u>Redefine Your User’s Profile Path with Simple Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-resource-consumption-tips-for-edge-view2-process/"><u>Reducing Resource Consumption: Tips for Edge View2 Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-the-windows-configuration-dashboard/"><u>Reviving the Windows Configuration Dashboard</u></a></li>
<li><a href="https://fox-links.techidaily.com/transforming-footage-into-high-quality-content-for-2024/"><u>Transforming Footage Into High-Quality Content for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-disk-varieties-via-windows-tools/"><u>Unveiling Disk Varieties via Windows Tools</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-how-to-safeguard-your-work-saving-fcp-projects-like-a-pro/"><u>Updated 2024 Approved How to Safeguard Your Work Saving FCP Projects Like a Pro</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-similar-software-or-alternatives-to-virtualdub/"><u>Updated In 2024, Similar Software or Alternatives to VirtualDub</u></a></li>
</ul></div>

