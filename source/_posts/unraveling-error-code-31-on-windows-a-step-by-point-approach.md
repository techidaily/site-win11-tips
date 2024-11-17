---
title: "Unraveling Error Code 31 on Windows: A Step-By Point Approach"
date: 2024-11-12T17:38:48.765Z
updated: 2024-11-17T20:06:54.748Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unraveling Error Code 31 on Windows: A Step-By Point Approach"
excerpt: "This Article Describes Unraveling Error Code 31 on Windows: A Step-By Point Approach"
keywords: Fix Error Code 31,Win31 Solution Guide,Debugging Error 31,Windows Error Diagnosis,Code 31 Troubleshoot,Resolve Windows Error,Step-by-Step Error 31
thumbnail: https://thmb.techidaily.com/cc0866b80e38550ff25e3009719b526ea4484f9d37497b921eea5c41a1afe3dd.jpg
---

## Unraveling Error Code 31 on Windows: A Step-By Point Approach

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1972679/19272" target="_top" id="1972679">
  <img src="//a.impactradius-go.com/display-ad/19272-1972679" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972679/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2112008/7443" target="_top" id="2112008">
  <img src="//a.impactradius-go.com/display-ad/7443-2112008" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2112008/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Delete the Corrupted Network Config File on Older Machines

![delete config value registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/delete-config-value-registry-editor.jpg)

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
<a href="https://aligracehair.sjv.io/c/5597632/1975807/19272" target="_top" id="1975807">
  <img src="//a.impactradius-go.com/display-ad/19272-1975807" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975807/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Reinstall Your Network Adapter Driver

 You can manually uninstall your network adapter device and driver to perform a network reset on older Windows versions. You can use the reliable Device Manager to uninstall your network devices.

1. Open Device Manager (see[how to open Device Manager](https://www.makeuseof.com/windows-open-device-manager/) for detailed steps).
2. Next, expand the**Network Adapters** section.
3. Right-click on the network adapter and select**Uninstall Device.**  
![uninstall network device device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-network-device-device-manager.jpg)
4. In the confirmation dialog, check the**Attempt to remove the driver for this device** option.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135373/19272" target="_top" id="2135373">
  <img src="//a.impactradius-go.com/display-ad/19272-2135373" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135373/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484">
  <img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Select the most recent restore point and click**Next** .  
![system properties system restore](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-properties-system-restore.jpg)
6. Confirm your restore point and read the description to understand what apps and data on your PC are affected.
7. Click**Finish** to initialize the system restore process. Your PC will restart and may take some time to finish. Your PC will restart and show a system restore success or failure message.

 If the restore process fails, try it again. At times, it may take more than one attempt to get it right. If the computer is restored, it should hopefully restore the old network driver configuration and fix the error.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144281/7443" target="_top" id="2144281">
  <img src="//a.impactradius-go.com/display-ad/7443-2144281" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144281/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-transformative-youtube-decks-via-tailored-templates/"><u>[Updated] In 2024, Transformative Youtube Decks via Tailored Templates</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-transform-viewership-seo-for-the-newbie-on-youtube/"><u>[Updated] Transform Viewership SEO for the Newbie on YouTube</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-2023-update-sony-bdp-s3700-in-depth-analysis/"><u>2024 Approved 2023 Update Sony BDP-S3700 in Depth Analysis</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-efficient-look-up-table-techniques-for-movies/"><u>2024 Approved Efficient Look-Up Table Techniques for Movies</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-ideal-vr-solutions-for-drone-flying/"><u>2024 Approved Ideal VR Solutions for Drone Flying</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/3d-lut-mobile-app-review-a-composite-application-for-editing-media-for-2024/"><u>3D LUT Mobile App Review - A Composite Application for Editing Media for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/access-real-time-forex-data-with-ease-incorporating-current-exchange-rates-into-your-excel-worksheets/"><u>Access Real-Time Forex Data with Ease: Incorporating Current Exchange Rates Into Your Excel Worksheets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-tips-for-multi-page-excel-prints-repeating-data-with-ease/"><u>Advanced Tips for Multi-Page Excel Prints: Repeating Data with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ditch-manual-data-entry-seamlessly-move-information-from-printed-forms-using-this-smartphone-technique/"><u>Ditch Manual Data Entry: Seamlessly Move Information From Printed Forms Using This Smartphone Technique</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-techniques-for-consolidating-and-dividing-cells-within-microsoft-excel-spreadsheets/"><u>Easy Techniques for Consolidating and Dividing Cells Within Microsoft Excel Spreadsheets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-strategies-for-concealing-errors-and-signals-in-your-excel-spreadsheets/"><u>Effective Strategies for Concealing Errors and Signals in Your Excel Spreadsheets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-generating-rng-values-using-microsoft-excel-tools-and-features/"><u>Guide: Generating RNG Values Using Microsoft Excel Tools and Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-core-12-imperative-excel-techniques-you-need-to-familiarize-yourself-with/"><u>Mastering the Core: 12 Imperative Excel Techniques You Need to Familiarize Yourself With</u></a></li>
<li><a href="https://win11-tips.techidaily.com/must-have-android-apps-for-enhanced-chromebook-functionality/"><u>Must-Have Android Apps for Enhanced Chromebook Functionality</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-unsupported-device-errors-in-your-it-driver-setup/"><u>Resolving Unsupported Device Errors in Your IT Driver Setup</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/revamp-your-tech-collection-latest-m3-macbook-pro-and-imac-upgrades-to-macos-high-sierra-detailed-guide-zdnet/"><u>Revamp Your Tech Collection: Latest M3 MacBook Pro & iMac Upgrades to macOS High Sierra - Detailed Guide | ZDNET</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-how-to-create-dynamic-summaries-by-groupingcollapsing-excel-rows/"><u>Step-by-Step Guide: How to Create Dynamic Summaries by Grouping/Collapsing Excel Rows</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/the-legal-limits-of-capturing-youtube-video-footage-for-2024/"><u>The Legal Limits of Capturing YouTube Video Footage for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-storytellers-ai-companion-chatgpt-for-engaging-narratives/"><u>The Storyteller’s AI Companion: ChatGPT for Engaging Narratives</u></a></li>
</ul></div>

