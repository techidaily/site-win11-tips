---
title: Overcoming the 'Cannot Continue' Error in AMD Installation
date: 2024-07-03T12:38:48.657Z
updated: 2024-07-04T12:38:48.657Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming the 'Cannot Continue' Error in AMD Installation
excerpt: This Article Describes Overcoming the 'Cannot Continue' Error in AMD Installation
keywords: AMD Install Troubleshoot,Overcome AMD Error,Stop AMD Cancel Error,Fixing AMD Setup Issue,Resolve AMD Failure,Correct AMD Not Continue,Eliminate AMD Freeze Error
thumbnail: https://thmb.techidaily.com/3f0dd2ba23afb65e6bd0d3f90edabc5ca5d9604be85f232f57f9da3d1c3125e2.jpg
---

## Overcoming the 'Cannot Continue' Error in AMD Installation

 AMD Radeon Software can auto-detect your graphics card and install its compatible drivers. However, sometimes the installer stops working with the AMD error 195\. The full error reads: "AMD Software cannot continue because it is unable to access the required web resources."

 This error can occur if the Windows firewall or third-party antivirus program blocks the AMD installer. To fix the issue, temporarily disable your firewall or run a compatible version of the installer. Here are a few ways to fix the AMD error 195 on Windows.

## 1\. Update Your Antivirus or Disable It Temporarily
![quit malwarebytes windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/quit-malwarebytes-windows.jpg)

 Antivirus conflict is the most common reason for the AMD 195 error. An outdated antivirus definition may block the installer from running on your computer due to a false positive.

 Most antivirus programs are by default set to auto-update, but you can make sure it is the case by checking if your antivirus is up-to-date in Settings. If you use Malwarebytes antivirus, right-click the antivirus program icon in the system tray and select**Check for updates** .

 Alternatively, open the antivirus application, go to**Settings** , and open the**About** tab. Click on**Check for updates** to download and install the latest version available.

 If the antivirus program is up-to-date, consider disabling your antivirus temporarily and running the installer. Depending on your antivirus program, you may have to quit or temporarily disable the antivirus completely.

 To disable Malwarebytes, right-click the app icon in the system tray and select**Quit Malwarebytes** . Run the installer and check if the error is resolved. Relaunch Malwarebytes again to enable protection. Other antivirus programs, including AVG and Avast, allow you to disable the antivirus for a few hours without closing the app completely.

## 2\. Turn Off or Reconfigure Your Firewall

 Similar to your antivirus, a firewall can also block inbound and outbound connections and prevent the installer from downloading necessary files. You can disable your firewall temporarily to determine if your firewall setting is triggering the error.

 You can [turn off Windows Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) from the Settings app. Third-party antivirus programs may have their own firewall programs built-in to the application. Sweep your antivirus settings to find and disable the firewall protection.

 If the error is resolved with the firewall disabled, you’ll need to add the AMD installer to allow the list to allow traffic from the AMD server. You can add [the AMD servers to the allow list on Windows Defender](https://www.makeuseof.com/how-to-whitelist-files-windows-defender/) to run the installer without conflict.

 Third-party antivirus programs use their own allow list. If you use Malwarebytes, go to**Settings** and open the**Allow List** tab. Click**Add** and select**Allow a file or folder** . Select the AMD software installer to add it to the allowed list. Now run the installer to see if the error is resolved. You can remove the allowed list entry after the program is installed.

 If the issue persists, run the installer after disabling both Windows Defender and Windows Firewall. Make sure to re-enable the services after installing AMD Radeon software.

## 3\. Install the AMD Software Driver Manually
![download amd radeon software driver manually](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/download-amd-radeon-software-driver-manually.jpg)

 If the auto detector tool is not working, you can manually install AMD Radeon Adrenalin Edition drivers from the website. Follow these steps to download AMD drivers manually:

1. Go to the [AMD Drivers and Support page](https://www.amd.com/en/support) .
2. Click the**Search all products** drop-down, select your graphics driver from the list, and click**Submit** .
3. Select your Windows edition.
4. Under the**AMD Software Adrenalin Edition** section, verify the version and the file size. The offline installer is often between 500 MB-600 MB in size.
5. Click**Download** to save the installer to your local drive.
6. Run the**MBSetup.exe** file and follow the on-screen instructions to complete the installation. If the offline installer doesn’t work, check for compatibility issues and, if necessary, install an older version of the driver to fix the error.

## 4\. Install an Older Version of AMD Software
![radeon software update graphics driver version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/radeon-software-update-graphics-driver.jpg)

 Sometimes, the AMD error 195 may be triggered due to a buggy installer or incompatibility issues. To fix the problem, try to install the older version of the software.

 Downloading an older version of AMD Radeon Software is a little tricky. Since AMD doesn’t have a list of all drivers released, you’ll need to manually locate and download the drivers. Fortunately, AMD lets you download older drivers from its release notes page.

 To download the older version of AMD Software, first, check the current version of AMD software installed on your computer. To do this:

1. Right-click on the desktop and select**AMD Radeon Software** .
2. In Radeon Software, click the**Gear** icon and open the**System** tab.
3. Note down the current AMD driver version installed on your computer.

 Next, find a list of AMD Software Adrenalin Edition releases. A quick web search will bring up the list of all the releases. Locate an older release than the one installed on your computer. Perform a web search again to find an official AMD release note associated with the version you want to download. Download the driver and run the installer to see if the error is resolved.

## 5\. Other Troubleshooting Steps to Try

* Use an Ethernet connection to download the installer and other files. Issues with your wireless connection may cause the installer to fail and show an error. Plugin an Ethernet cable into your laptop and run the installer to download the necessary files from the ADM server.
* [Run the installer in the clean boot state](https://www.makeuseof.com/clean-boot-windows-11/) . You can run the AMD software in a clean boot state to check for third-party program and startup app conflicts. In a clean boot state, Windows starts with only Microsoft services and startup apps disabled. If the installation goes through, you can safely assume a third-party app conflict triggering the error.
* Perform a clean install – If the error occurs when performing an update, try to [clean install your GPU drivers](https://www.makeuseof.com/how-to-cleanly-install-and-reinstall-gpu-drivers-on-windows/) . You can uninstall the AMD graphics driver using Device Manager, the AMD Radeon Software, and Display Driver Uninstaller (DDU).

## Fixing the ADM Error 195 on Windows

 AMD Error 195 is often triggered due to conflict with your security program. To fix the problem, run the installer with the Windows Defender and Defender Firewall disabled. If the issue persists, run the installer in a clean boot state. Additionally, perform a clean install without the auto detector, or install an older version to fix compatibility issues.


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
<li><a href="https://win11-tips.techidaily.com/virtualbox-v70-upgrade-guide-win11-edition-walkthrough/"><u>VirtualBox v7.0 Upgrade Guide – Win11 Edition Walkthrough</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-dxgierrordeviceremoved-error-in-windows-10-and-11/"><u>How to Fix the DXGI_ERROR_DEVICE_REMOVED Error in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-simple-steps-for-overcoming-windows-onedrive-glitches/"><u>5 Simple Steps for Overcoming Windows OneDrive Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-storage-disks-in-windows-os/"><u>Deciphering Storage Disks in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-disconnections-windows-and-printers/"><u>Overcoming Disconnections: Windows & Printers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-index-performance-on-your-pc/"><u>Enhancing Index Performance on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-how-to-access-mspaint-in-windows-11/"><u>Discovering How to Access MSPaint in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-workspace-tackling-screen-lag-in-windows/"><u>Streamline Your Workspace: Tackling Screen Lag in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-open-and-use-the-windows-terminal-in-quake-mode/"><u>How to Open and Use the Windows Terminal in Quake Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secrets-to-turn-off-lurking-apps-in-window-11/"><u>Secrets to Turn Off Lurking Apps in Window 11</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-restore-a-bricked-xiaomi-redmi-note-12-pro-5g-back-to-operation-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Restore a Bricked Xiaomi Redmi Note 12 Pro 5G Back to Operation | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-explore-haunting-aural-landscapes/"><u>Updated In 2024, Explore Haunting Aural Landscapes</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-pioneers-leading-the-charge-in-virtual-experiences/"><u>2024 Approved  Pioneers Leading the Charge in Virtual Experiences</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-oppo-a78-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Oppo A78</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-the-ultimate-guide-to-changing-video-dimensions/"><u>New 2024 Approved The Ultimate Guide to Changing Video Dimensions</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-scalable-techniques-for-vimeo-broadcasting/"><u>In 2024, Scalable Techniques for Vimeo Broadcasting</u></a></li>
<li><a href="https://techidaily.com/remove-the-lock-of-itel-by-drfone-android-unlock-android-unlock/"><u>Remove the lock of Itel</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-crafting-timeless-videos-with-retro-filmmaking-skills/"><u>[New] 2024 Approved  Crafting Timeless Videos with Retro Filmmaking Skills</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-windows-video-editing-apps-the-best-imovie-substitutes/"><u>2024 Approved Windows Video Editing Apps The Best iMovie Substitutes</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-fast-track-the-worlds-top-8-burgeoning-video-hubs-on-youtube/"><u>[New] In 2024, Fast-Track  The World's Top 8 Burgeoning Video Hubs on YouTube</u></a></li>
</ul></div>
