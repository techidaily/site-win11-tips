---
title: Mastering the Art of Fixing Error Code 31 in Windows OS
date: 2024-06-25T16:51:07.341Z
updated: 2024-06-26T16:51:07.341Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the Art of Fixing Error Code 31 in Windows OS
excerpt: This Article Describes Mastering the Art of Fixing Error Code 31 in Windows OS
keywords: Windows Error Code 31 Solution,Debugging Error Code 31,Resolving WinError 31,Troubleshoot Code 31 Windows,Fixing WinOS Error 31,Overcome OS Error 31 Fix,Decode Error 31 in Windows
thumbnail: https://thmb.techidaily.com/25bf753c78130a921149c781a28200c1963f284bc6d075e275272bdd4200ee96.jpg
---

## Mastering the Art of Fixing Error Code 31 in Windows OS

 Are you encountering an error message on Windows that reads "network adapter error code 31: this device is not working properly"? This error often occurs due to a corrupted or incorrect version of the network adapter driver installed on your PC.

 As such, let's explore all the ways to fix the network adapter error code 31 on Windows.

## 1\. Check for Any Pending Network Driver Updates

 First off, check to see if your network driver has any pending updates. While you can update the drivers for the device connected to your computer using Device Manager, we don't recommend it, as Device Manager often fails to find the most recent updates for the driver.

 You will most likely find the latest network driver on your computer manufacturer's website, so check who made your PC and visit their website for details. If you use an external network adapter, visit the adapter manufacturer's website instead.

 Additionally, you can also find new drivers using your manufacturer's proprietary system management tool. For example, with Lenovo and HP computers, you can use the Lenovo Vantage and HP Support Assistant utility to find and install new drivers for your network adapter and other devices.

## 2\. Perform a Driver Roll Back

 If you believe a recent driver update is causing the error, you can use the**Roll Back Driver** option to perform a rollback and reinstall the previous version of the network adapter driver.

To perform a network driver rollback:

1. Press**Win + R** to open Run.
2. Type**devmgmt** .**msc** and click**OK** to open Device Manager.
3. In Device Manager, expand the**Network Adapters** section.  
![device manager network adapter properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/device-manager-network-adapter-properties.jpg)
4. Right-click on your network device and select**Properties** .
5. In the**Properties** dialog, open the**Driver** tab.  
![device manager network driver roll back driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/device-manager-network-driver-roll-back-driver-1.jpg)
6. Click the**Roll Back Driver** button. If the option is**greyed out** , your computer doesn't have an older driver to perform a rollback. Check your manufacturer's website to see if they have older drivers in an archive.
7. Next, in the confirmation dialog, give a reason and click**Yes** .
8. Once the driver rollback is complete, check if the problem is resolved. If not, check if you can perform another rollback for the network device driver to see if that helps.

## 3\. Perform a Network Reset

 Windows 10 and 11 feature a "network reset" option. This will remove and reinstall the network drivers and other networking components to their factory defaults to help you fix network adapter issues on your computer.

To perform a network reset:

1. Press**Win + I** to open**Settings** .
2. Open the**Network & internet** tab in the left pane.
3. Click on**Advanced network settings** .
4. ![advanced network settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/advanced-network-settings-windows-11.jpg)  
 Next, click on**Network reset** .
5. ![advanced network settings windows 11 network reset](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/advanced-network-settings-windows-11-network-reset.jpg)  
 Click on**Reset now** and click**Yes** to rest your network settings.  
![advanced network settings windows 11 network reset reset now](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/advanced-network-settings-windows-11-network-reset-reset-now.jpg)
6. Your PC will restart during the process.

## 3\. Delete the Corrupted Network Config File on Older Machines ![delete config value registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/delete-config-value-registry-editor.jpg)

 On an older Windows Vista or XP computer, you can resolve the issue by tweaking a registry entry. You need to delete a corrupt config key in Registry Editor and then uninstall the device from Device Manager to fix the error.

 The following steps only apply to a Windows computer running Vista or XP.

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open**Registry Editor** .
3. In Registry Editor, navigate to the following path:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Network\`
4. In the right pane, locate the**Config** value.
5. Next, right-click on the**Config** value and select**Delete** .
6. Click**Yes** to confirm the action.

 Once the key is deleted, you'll need to remove and reinstall the network driver. You can do it using Device Manager, as shown in the step below.

 Note that modifications to some registry entries may fail due to insufficient permission issues. If you get an error when deleting the Config value, take full ownership of the registry key and then try again. Our guide on [how to take full ownership of registry keys on Windows 10](https://www.makeuseof.com/windows-10-full-ownership-registry/) will work on older systems too.

## 4\. Reinstall Your Network Adapter Driver

 You can manually uninstall your network adapter device and driver to perform a network reset on older Windows versions. You can use the reliable Device Manager to uninstall your network devices.

1. Open Device Manager (see [how to open Device Manager](https://www.makeuseof.com/windows-open-device-manager/) for detailed steps).
2. Next, expand the**Network Adapters** section.
3. Right-click on the network adapter and select**Uninstall Device.**  
![uninstall network device device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-network-device-device-manager.jpg)
4. In the confirmation dialog, check the**Attempt to remove the driver for this device** option.  
![uninstall network driver device device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-network-driver-device-device-manager.jpg)
5. Click**Uninstall** to confirm the action.

 Once uninstalled, restart your PC. After the restart, Windows will automatically detect connected but unrecognized devices and install the necessary drivers.

 If Windows fails to install the driver, open**Device Manager** , right-click on your network adapter and select**Update driver** . You can also download the latest drivers from your computer manufacturer's website, as shown in step one.

## 6\. Perform a System Restore

 This error can occur if Windows modifies your network adapter settings during an update. You can use a restore point to undo the changes and restore the computer to its earlier state. Since Windows automatically creates a new restore point before installing an update, you should be able to find a recent restore point to undo the changes.

To perform a restore point:

1. Press the**Win** key and type**restore point.**
2. Click on**Create a restore point** from the search result.
3. In the**System Protection** dialog, click the**System Restore** button.  
![system properties system restore](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-properties-system-restore.jpg)
4. In the**System Restore** dialog, click**Next** to view all the available restore points. Additionally, check the**Show more restore points** option to view older restore points.
5. Select the most recent restore point and click**Next** .  
![system properties system restore](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-properties-system-restore.jpg)
6. Confirm your restore point and read the description to understand what apps and data on your PC are affected.
7. Click**Finish** to initialize the system restore process. Your PC will restart and may take some time to finish. Your PC will restart and show a system restore success or failure message.

 If the restore process fails, try it again. At times, it may take more than one attempt to get it right. If the computer is restored, it should hopefully restore the old network driver configuration and fix the error.

## Fix the Network Adapter Code 31 Error on Windows

 Network adapter code 31 is one of the many errors that can cause your network adapter to malfunction. To fix the error, check if you have the latest network adapter driver installed. If necessary, perform a driver rollback, clean up corrupt registry value or perform a system restore.

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
<li><a href="https://win11-tips.techidaily.com/how-to-effortlessly-switch-nat-settings-in-windows-oses/"><u>How to Effortlessly Switch NAT Settings in Windows OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-display-experience-shift-to-adaptive-layouts/"><u>Upgrade Display Experience: Shift to Adaptive Layouts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-and-tricks-to-fix-error-0x800700e1-in-windows-11/"><u>Tips & Tricks to Fix Error 0X800700E1 in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-error-0x0000004e-in-windows-devices/"><u>Navigating Error 0X0000004E in Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improve-live-feed-rates-on-task-monitor-win-11/"><u>Improve Live Feed Rates on Task Monitor Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-xbox-live-service-disruptions-on-pcs/"><u>Troubleshooting Xbox Live Service Disruptions on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/game-gateway-3-steps-to-direct-folder-entry-on-pc/"><u>Game Gateway: 3 Steps to Direct Folder Entry on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-strategies-against-locked-out-windows-pin/"><u>Immediate Strategies Against Locked-Out Windows PIN</u></a></li>
<li><a href="https://win11-tips.techidaily.com/examining-the-prospects-why-choose-win11-over-macos/"><u>Examining the Prospects: Why Choose Win11 Over MacOS</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-online-audio-enhancement-a-step-by-step-guide-to-adjusting-speed-and-pitch-for-2024/"><u>Updated Online Audio Enhancement A Step-by-Step Guide to Adjusting Speed & Pitch for 2024</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713963576144-new-if-you-are-a-marketer-who-want-to-create-facebook-ads-to-boost-your-business-you-are-coming-to-the-right-place-well-share-you-some-useful-tips-to-start-/"><u>New If You Are a Marketer Who Want to Create Facebook Ads to Boost Your Business, You Are Coming to the Right Place. Well Share You some Useful Tips to Start Your First FB Ads Campaign for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-viral-visionaries-twitters-10-hotest-content-threads-today/"><u>2024 Approved  Viral Visionaries  Twitter's 10 Hotest Content Threads Today</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fake-gps-on-apple-iphone-15-plus-for-mobile-legends-drfone-by-drfone-virtual-ios/"><u>How To Fake GPS On Apple iPhone 15 Plus For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-remove-tiktok-watermarks-in-seconds-top-online-solutions/"><u>New In 2024, Remove TikTok Watermarks in Seconds Top Online Solutions</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-reaching-new-crowds-simultaneous-youtube-and-twitch-coverage/"><u>In 2024, Reaching New Crowds  Simultaneous Youtube & Twitch Coverage</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/2024-approved-women-in-warfare-youtubes-elite-ten/"><u>2024 Approved  Women in Warfare  YouTube’s Elite Ten</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-motorola-moto-g23-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Live Location is Not Updating and How to Fix on your Motorola Moto G23 | Dr.fone</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-the-ultimate-guide-to-video-editors-for-windows-11-free-paid-and-in-between/"><u>New 2024 Approved The Ultimate Guide to Video Editors for Windows 11 Free, Paid, and In-Between</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-in-2024-top-7-best-free-gif-apps-for-android/"><u>Updated In 2024, Top 7 Best Free GIF Apps for Android</u></a></li>
</ul></div>
