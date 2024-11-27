---
title: Troubleshooting System Failures Due to Inadequate Intel Graphic Specs
date: 2024-11-21T17:00:02.843Z
updated: 2024-11-27T16:35:04.970Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting System Failures Due to Inadequate Intel Graphic Specs
excerpt: This Article Describes Troubleshooting System Failures Due to Inadequate Intel Graphic Specs
keywords: Intel Graphics Troubleshooting,GPU Performance Issues,Graphic Specs Problems,System Failure Fixes,Inadequate Graphics Resolution,Optimizing PC Graphics,Hardware Debugging Guide
thumbnail: https://thmb.techidaily.com/289e1b59f873ec0dc8305b0281292ab73fb1d9fdd29063def94d2427e3383ad3.jpg
---

## Troubleshooting System Failures Due to Inadequate Intel Graphic Specs

 When installing an Intel graphics driver, your computer may show an error indicating the system doesn’t meet the minimum requirements. This error is often triggered due to incompatibility issues. In some instances, it can be a conflict between your integrated and dedicated graphics processing units.

 In this guide, we show you how to fix the "this computer doesn’t meet minimum requirements" error to help you install the latest Intel HD graphics driver on your computer.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Install Drivers Using Intel Driver and Support Assistant

![intel driver support assistant](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/intel-driver-support-assistant.jpg)

 Intel Driver and Support Assistant is a propitiatory system assistant that can automatically detect and help you install the latest Intel graphics drivers. It is a handy utility to install compatible Intel drivers when you encounter an error.

 To install drivers using Intel Driver and Support Assistant:

1. Go to the [Intel download page](https://www.intel.in/content/www/in/en/support/intel-driver-support-assistant.html) and download the **Intel Driver & Support Assistant** installer.
2. Run the installer and wait for the process to complete.
3. Next, run the installer to complete the installation and restart your computer.
4. Launch the installer and allow it to scan your computer. It will detect newer drivers and other necessary updates available for your system. Check if the driver you want to install is available and complete the installation.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/M5pwd2mwaQQ?si=qyZHgdTlbQbc32Mp&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Install the Intel HD Graphics Driver as Legacy Hardware

 If you want to install an older driver version that doesn’t support Plug And Play, you can manually install the Intel driver as legacy hardware. This should fix any compatibility issues triggering this error.

 We recommend you [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps below. A restore point can help you recover and restore your system if something goes awry.

 To install the Intel driver as legacy hardware:

1. Press **Win + R** to open **Run**.
2. Type **devmgmt.msc** and click **OK** to open **Device Manager**.
3. In Device Manager, select your computer name.
4. Next, click on **Action** and select **Add legacy hardware**.  
![device manager add legacy hardware](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/device-manager-add-legacy-hardware.jpg)
5. Click **Next** in the Welcome wizard.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Select the **Install the hardware that I manually select from a list (Advanced)** option.  
![install the hardware that I manually select from a list advanced](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/install-the-hardware-that-i-manually-select-from-a-list-advanced.jpg)
2. Click **Next**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Next, select **Display adapters** from the **Common hardware types** list and click **Next**.  
![common hardware types display adapter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/common-hardware-types-display-adapter.jpg)
4. Since you already have the Intel setup file, click **Have Disk**.  
![select the device driver you want to install for this hardware have disk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/select-the-device-driver-you-want-to-install-for-this-hardware-have-disk.jpg)
5. Next, click **Browse**.

1. Navigate to the location where the Intel setup file is stored. Open the folder and select the file **autorun.inf** and click **Open**.
2. If the autorun.inf file is missing, open the **Graphics** subfolder and select the **igdlh64.inf** file.  
![select igdlh64 inf from graphics folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/select-igdlh64-inf-from-graphics-folder.jpg)
3. Click **OK** to proceed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NTQGoOOiJzs?si=zbZwflEfXgBY3qbs&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. In the next screen, you can select your Intel graphics model. If you don’t know the model number, select **Intel HD Graphics** and click **Next**. Follow the on-screen instructions to complete the installation.
5. Once installed, restart your PC.

 In most instances, manually selecting the installation file will install the Intel graphics driver without error. However, if the error persists, you can [roll back or update the driver from the Device Manager](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) to fix the problem. In Device Manager, expand the **Display Adapters** section and select **Intel HD graphics** to perform a rollback.

 If a rollback is not available, check your computer for new Windows updates. On Windows 11, press **Win + I** to open **Setting**s and then the **Windows Update** tab. Then click on **Check for updates**. Install any updates available for the display adapter. Once installed, restart your computer to apply the changes and check for any improvements.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xa2_mFu-obA?si=_xDGF1pv-dnuaDOr&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fixing the Intel HD Graphics Does Not Meet Minimum Requirement Error

 Installing older Intel drivers on newer editions of Windows can be tedious and result in errors. To resolve the issue, install the driver manually using the legacy hardware option in Device Manager. If not, use Intel’s Support Assistant to automatically install the best driver for your display adapter.

 In this guide, we show you how to fix the "this computer doesn’t meet minimum requirements" error to help you install the latest Intel HD graphics driver on your computer.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-blue.techidaily.com/new-examining-the-perks-and-pitfalls-of-vr/"><u>[New] Examining the Perks and Pitfalls of VR</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-facebook-live-video-downloaders-how-to-download-live-videos-for-2024/"><u>[New] Facebook Live Video Downloaders | How to Download Live Videos for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-a-comprehensive-tour-youtube-creator-suite-for-2024/"><u>[Updated] A Comprehensive Tour YouTube Creator Suite for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/beyond-predecessors-how-gpt-4-surpasses-gpt-35/"><u>Beyond Predecessors: How GPT-4 Surpasses GPT-3.5</u></a></li>
<li><a href="https://sound-issues.techidaily.com/comprehensive-guide-to-diagnosing-and-repairing-windows-11-mic-failures/"><u>Comprehensive Guide to Diagnosing & Repairing Windows 11 Mic Failures</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/conquer-the-curse-of-crimson-pixels-a-comprehensive-guide-to-repairing-the-orange-display-fault/"><u>Conquer the Curse of Crimson Pixels: A Comprehensive Guide to Repairing the Orange Display Fault</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diagnosing-and-fixing-one-side-windows-earphone-sound/"><u>Diagnosing and Fixing One-Side Windows Earphone Sound</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-adjustment-of-text-emphasis-and-search-effects/"><u>Easy Adjustment of Text Emphasis and Search Effects</u></a></li>
<li><a href="https://extra-hints.techidaily.com/examination-the-top-tier-ar-parrot-drone-20/"><u>Examination The Top-Tier AR Parrot Drone 2.0</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/how-to-master-the-art-moviemaker-movie-uploads-on-vimeo-for-2024/"><u>How To Master the Art Moviemaker Movie Uploads on Vimeo for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-9-best-phone-monitoring-apps-for-vivo-v29e-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Best Phone Monitoring Apps for Vivo V29e | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-d-drive-into-explorer-toolbar/"><u>Integrating D: Drive Into Explorer Toolbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-around-the-windows-settings-app-failures/"><u>Navigate Around the Windows Settings App Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-second-screen-anomaly-in-windows-11/"><u>Solving Second Screen Anomaly in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-your-taskbar-in-windows-11/"><u>Streamlining Your Taskbar in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-devices-boot-process-with-expert-service-configurations-in-win11/"><u>Tailoring Your Device's Boot Process with Expert Service Configurations in Win11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/the-10-best-tools-to-bypass-icloud-activation-lock-from-iphone-x-you-should-try-out-by-drfone-ios/"><u>The 10 Best Tools to Bypass iCloud Activation Lock From iPhone X You Should Try Out</u></a></li>
<li><a href="https://win11-tips.techidaily.com/triple-pathway-approach-to-understanding-windows-group-policies/"><u>Triple-Pathway Approach to Understanding Windows Group Policies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-correcting-system-errors-in-dwarf-fortress/"><u>Understanding and Correcting System Errors in Dwarf Fortress</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    