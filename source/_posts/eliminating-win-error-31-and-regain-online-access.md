---
title: Eliminating WIN Error 31 and Regain Online Access
date: 2024-11-02T21:26:22.405Z
updated: 2024-11-07T10:44:42.439Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminating WIN Error 31 and Regain Online Access
excerpt: This Article Describes Eliminating WIN Error 31 and Regain Online Access
keywords: WIN Error Fix,Restore Internet Access,Resolve Error 31,Online Connectivity Solution,Unblocking Windows,Recover Web Service,Error 31 Remedy
thumbnail: https://thmb.techidaily.com/2fabafc66fe8d6c738eceaf2d94bef9969abb79ce6dfc7f79cdd9561a56a5238.jpg
---

## Eliminating WIN Error 31 and Regain Online Access

 Are you encountering an error message on Windows that reads "network adapter error code 31: this device is not working properly"? This error often occurs due to a corrupted or incorrect version of the network adapter driver installed on your PC.

 As such, let's explore all the ways to fix the network adapter error code 31 on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139121/17108" target="_top" id="2139121">
  <img src="//a.impactradius-go.com/display-ad/17108-2139121" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139121/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. ![advanced network settings windows 11 network reset](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/advanced-network-settings-windows-11-network-reset.jpg)  
 Click on**Reset now** and click**Yes** to rest your network settings.  
![advanced network settings windows 11 network reset reset now](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/advanced-network-settings-windows-11-network-reset-reset-now.jpg)
6. Your PC will restart during the process.

## 3\. Delete the Corrupted Network Config File on Older Machines

![delete config value registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/delete-config-value-registry-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098705/14409" target="_top" id="2098705">
  <img src="//a.impactradius-go.com/display-ad/14409-2098705" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098705/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

 Note that modifications to some registry entries may fail due to insufficient permission issues. If you get an error when deleting the Config value, take full ownership of the registry key and then try again. Our guide on[how to take full ownership of registry keys on Windows 10](https://www.makeuseof.com/windows-10-full-ownership-registry/) will work on older systems too.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938693/19272" target="_top" id="1938693">
  <img src="//a.impactradius-go.com/display-ad/19272-1938693" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938693/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Reinstall Your Network Adapter Driver

 You can manually uninstall your network adapter device and driver to perform a network reset on older Windows versions. You can use the reliable Device Manager to uninstall your network devices.

1. Open Device Manager (see[how to open Device Manager](https://www.makeuseof.com/windows-open-device-manager/) for detailed steps).
2. Next, expand the**Network Adapters** section.
3. Right-click on the network adapter and select**Uninstall Device.**  
![uninstall network device device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-network-device-device-manager.jpg)
4. In the confirmation dialog, check the**Attempt to remove the driver for this device** option.  

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134236/18498" target="_top" id="2134236">
  <img src="//a.impactradius-go.com/display-ad/18498-2134236" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134236/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![uninstall network driver device device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-network-driver-device-device-manager.jpg)
5. Click**Uninstall** to confirm the action.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037345/7443" target="_top" id="2037345">
  <img src="//a.impactradius-go.com/display-ad/7443-2037345" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037345/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once uninstalled, restart your PC. After the restart, Windows will automatically detect connected but unrecognized devices and install the necessary drivers.

 If Windows fails to install the driver, open**Device Manager** , right-click on your network adapter and select**Update driver** . You can also download the latest drivers from your computer manufacturer's website, as shown in step one.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123512/26400" target="_top" id="2123512">
  <img src="//a.impactradius-go.com/display-ad/26400-2123512" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123512/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-how-to-embed-youtube-in-your-gslides-presentation/"><u>[Updated] 2024 Approved How to Embed YouTube in Your GSlides Presentation</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-quick-start-guide-to-recording-remote-meetings-with-ease-windows-mac/"><u>[Updated] 2024 Approved Quick-Start Guide to Recording Remote Meetings with Ease (Windows, Mac)</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-cutting-edge-tricks-in-streamlabs-obs-broadcasts-for-2024/"><u>[Updated] Cutting-Edge Tricks in Streamlabs OBS Broadcasts for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-essential-screenshot-and-recorder-software-guide-for-macs/"><u>[Updated] Essential Screenshot & Recorder Software Guide for Macs</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-pictures-from-nubia-red-magic-8s-proplus-by-fonelab-android-recover-pictures/"><u>Easy steps to recover deleted pictures from Nubia Red Magic 8S Pro+.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-navigate-past-an-infinite-windows-update-countdown/"><u>How to Navigate Past an Infinite Windows Update Countdown</u></a></li>
<li><a href="https://win11-tips.techidaily.com/joining-forces-connecting-wp-plus-android-via-samsung-flow/"><u>Joining Forces: Connecting WP + Android via Samsung Flow</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keyboard-command-proficiency-a-guide-to-windows-narrator/"><u>Keyboard Command Proficiency: A Guide to Windows Narrator</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/montblanc-launches-high-end-1300-smartwatch-with-wear-os-does-it-meet-expectations-yet/"><u>Montblanc Launches High-End $1,300 Smartwatch with Wear OS: Does It Meet Expectations Yet?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-video-rendering-increasing-vram-in-windows/"><u>Optimize Video Rendering: Increasing VRAM in Windows</u></a></li>
<li><a href="https://data-recovery.techidaily.com/photo-and-file-retrieval-for-mobile-devices/"><u>Photo and File Retrieval for Mobile Devices</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-videos-back-from-oneplus-11r-by-fonelab-android-recover-video/"><u>Simple ways to get lost videos back from OnePlus 11R</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-generic-audio-device-unsupported-in-windows/"><u>Solutions for Generic Audio Device Unsupported in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-the-package-registration-hurdle-for-windows-users/"><u>Solving the Package Registration Hurdle for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-approach-to-windows-11-amd-graphics-driver-upgrades/"><u>Stepwise Approach to Windows 11 AMD Graphics Driver Upgrades</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/tech-scoop-intels-panther-lake-lineup-expands-to-three-aiming-for-market-impact-post-lunar-success/"><u>Tech Scoop: Intel's Panther Lake Lineup Expands to Three, Aiming for Market Impact Post Lunar Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-invalid-profiles-clearing-windows-1111-errors/"><u>Troubleshooting Invalid Profiles: Clearing Windows 11/11 Errors</u></a></li>
<li><a href="https://tech-hub.techidaily.com/which-ai-helper-should-you-choose-diving-into-snapchats-my-ai-and-chatgpt/"><u>Which AI Helper Should You Choose? Diving Into Snapchat’s My AI and ChatGPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/window-11-taskbar-height-adjustment-tips/"><u>Window 11 Taskbar Height Adjustment Tips</u></a></li>
</ul></div>

