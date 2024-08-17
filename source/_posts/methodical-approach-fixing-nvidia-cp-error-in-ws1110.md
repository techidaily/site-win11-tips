---
title: "Methodical Approach: Fixing Nvidia CP Error in WS11/10"
date: 2024-08-16T01:26:29.288Z
updated: 2024-08-17T01:26:29.288Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Methodical Approach: Fixing Nvidia CP Error in WS11/10"
excerpt: "This Article Describes Methodical Approach: Fixing Nvidia CP Error in WS11/10"
keywords: Nvidia Fix Guide,WS11 CP Troubleshoot,Fixed NVLink Error,GPU CP Issue Resolve,Nvidia Cleanup Procedures,TechNvidia Repair Steps,CP Error Solutions WS10/11
thumbnail: https://thmb.techidaily.com/a471b0d2c144e4e5b46108f146c187bc2176565f5eff5e3e04c1be7552d848bf.jpg
---

## Methodical Approach: Fixing Nvidia CP Error in WS11/10

 The NVIDIA Control Panel is an app included on PCs with NVIDIA GPUs with which users can change graphical settings. However, some users can’t change NVIDIA Control Panel options because of an “Access denied” error. The message of that error says, “Failed to apply selected settings to your system.”

 The “Access denied” error is mostly reported to arise for 3D settings. As a result, NVIDIA Control Panel doesn’t apply (save) the settings users select. This is how you can resolve NVIDIA Control Panel’s “Access denied” error within Windows 11/10.

## 1\. Run the NVIDIA Control Panel as an Administrator

 Firstly, try running the NVIDIA Control Panel with elevated admin permissions, which has worked for some users. To do that, press the**Windows** logo +**S** keyboard buttons and input NVIDIA Control Panel. Right-click NVIDIA Control Panel and select**Run as administrator** .

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-as-administrator-option2.jpg)

 Should this potential fix work, then it would be better to set the NVIDIA Control Panel to always run with administrative rights. However, that UWP app is located within a protected folder. You’ll need to [take ownership of the WindowsApps folder](https://www.makeuseof.com/windows-10-11-own-folder/) to set permanent admin rights for the NVIDIA Control Panel.

 If you take ownership of the WindowsApps folder, open the NVIDIACorp subfolder to reach the NVIDIA Control Panel file. Then you’ll need to set the nvcplui.exe file to run with admin rights. Follow the steps in this how to [set an app to always run as an administrator guide](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) to set elevated permissions for the nvcplui.exe file. The path for the NVIDIA Control Panel folder is:

`C:\Program Files\WindowsApps\NVIDIACorp.NVIDIAControlPanel_8.1.964.0_x64__56jybvy8sckqj`

## 2\. Select the Repair and Reset Options for the NVIDIA Control Panel

 The NVIDIA Control Panel app has**Repair** and**Reset** troubleshooting options you can select in Settings. Both options can be useful for fixing apps when they’re not working right. So, try selecting the**Repair** option first and then**Reset** to clear the app’s data if repairing isn’t enough. Check out this [article about resetting apps in Windows](https://www.makeuseof.com/windows-reset-app/) for details about how to apply this potential fix.

![The Repair and Reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-reset-options.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->

## 3\. Start or Restart the NVIDIA Display Container Service

 The NVIDIA Display Container is an important GPU service that runs numerous other NVIDIA background tasks. Make sure that service is running or restart it if it is. You can start or restart NVIDIA Display Container like this:

1. Click the**Type here to search** button or the Search box on the taskbar to access the Windows file finder tool.
2. Input**services** inside the file search utility.
3. Select**Services** to launch that app.
4. Then double-click**NVIDIA Display Container** to view the settings for that service.  
![The Services app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-services-app.jpg)  
<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
 Screenshot captured by Jack Slater - No attribution required
5. Click on the**Startup type** menu and select**Automatic** from there.
6. Next, select**Start** if the NVIDIA Display Container service is stopped. Or select**Stop** \>**Start** to restart that service.  
![The NVIDIA Display Container service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/nvidia-display-container-service.jpg)
7. Click**Apply** to set the NVIDIA Display Container service’s settings.
8. Close the NVIDIA Display Container Properties window by clicking**OK** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 4\. Update Your NVIDIA Graphics Card Driver

 The most widely confirmed fix for the “Access denied” error is to manually update the NVIDIA graphics driver. Thus, this is often an issue caused by outdated or faulty NVIDIA drivers. This [guide to updating NVIDIA drivers](https://www.makeuseof.com/how-update-nvidia-graphics-card-drivers-windows/) provides further details about how to apply this potential solution by manually downloading the latest GPU driver available from the NVIDIA site.

 When you’ve downloaded the latest NVIDIA driver package for your GPU, bring up the directory that includes its setup file. Double-click the NVIDIA driver package file to view its setup wizard and select the**Custom** option. Then select the**Perform a clean installation** checkbox and click**Next** to install.

![The Perform a clean installation checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/perform-a-clean-installation.jpg)

## 5\. Roll Back the NVIDIA Driver

 If the “Access denied” error arises after installing a new NVIDIA driver, rolling back that driver to a previous one could be a viable potential solution. You’ll only be able to do that if the previous NVIDIA GPU driver file is still available. Our [article about rolling back drivers](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) includes guidelines for how to apply this potential fix.

 If the**Roll Back** option is grayed out, you might still be able to roll back to a previous NVIDIA graphics driver with the System Restore utility. Rolling Windows back to a restoration point restores drivers installed before the selected date. However, that will only work if your PC has a restore point that predates the driver update.

![The Roll Back Driver button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/roll-back-driver-option.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This [post about creating and utilizing restore points](https://www.makeuseof.com/windows-11-create-restore-point/) tells you how to roll back Windows. Select a restore point that will restore the previous NVIDIA graphics driver. You can click**Scan for affected** programs in System Restore to check if a chosen restoration point will restore an NVIDIA graphics driver.

## 6\. Restore a Previous Version of the DRS Folder

 Some NVIDIA Control Panel users have said they fixed the “Access denied” error by restoring a DRS folder version backup. Note that you’ll only be able to apply this potential fix if you’ve got File History enabled or restore points saved on your PC. This is how you can restore a previous DRS folder version in Windows 11/10:

1. First, bring up File Explorer by clicking the taskbar button with the folder library icon.
2. Then click the**View** button to select a**Show** option.
3. Select the**Hidden Items** option.  
![The Hidden items checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hidden-items-option.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
4. Clear Explorer’s address bar to input the following path:  
`C:\ProgramData\NVIDIA Corporation`
5. Then right-click the DRS folder and select**Properties** .
6. Click the**Previous Versions** tab.  
![The Previous Versions tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/previous-version-tab.jpg)
7. Select the most recent folder version shown in that tab.
8. Click the**Restore** button.

 To select the same**Hidden Items** option in Windows 10, you’ll need to open the**View** tab in Explorer. Then select the checkbox labeled**Hidden Items** on that tab.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
## 7\. Turn Off the Game Bar

 It’s also recommended to turn off the Game Bar in case that’s causing any issues with the NVIDIA Control Panel. This potential resolution applies more to Windows 10 since Windows 11’s Settings app doesn’t include a specific option for disabling the Game Bar. You can turn off the Game Bar in Windows 10 like this:

1. Open Settings by clicking the cog icon on the Start menu.
2. Click the**Gaming** category.
3. Then turn off the**Enable Xbox Game Bar** option.  
![The Xbox Game Bar setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-xbox-game-bar-option.jpg)
<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Change Your Settings in the NVIDIA Control Panel Again

 Many users have resolved NVIDIA Control Panel’s “Access denied” error with the potential fixes covered above. So, the probability one of them will also fix that issue on your PC is good. With that issue sorted, you can change all settings in the NVIDIA Control Panel as required.

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
<li><a href="https://screen-video-capture.techidaily.com/new-mellow-playtime-10-top-rated-stress-erasers/"><u>[New] Mellow Playtime  10 Top-Rated Stress Erasers</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-exiting-the-invisible-web-of-tiktok-shadowbaning/"><u>[Updated] 2024 Approved  Exiting the Invisible Web of TikTok Shadowbaning</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-how-to-use-your-recordings-for-a-seamless-live-experience-on-fb/"><u>[Updated] 2024 Approved  How to Use Your Recordings for a Seamless Live Experience on FB</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-radiant-spectrum-enhancer/"><u>[Updated] 2024 Approved  Radiant Spectrum Enhancer</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-effortless-hue-adjustments-with-adobes-software-for-2024/"><u>[Updated] Effortless Hue Adjustments with Adobe's Software for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-soundscapes-of-apple-in-the-realm-of-vids/"><u>2024 Approved  Soundscapes of Apple in the Realm of Vids</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-essential-components-of-podcast-scripting-guide-plus-free-examples/"><u>2024 Approved  The Essential Components of Podcast Scripting (Guide + Free Examples)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/5-easy-ways-to-fix-canon-printer-wont-print-in-windows-11/"><u>5 Easy Ways to Fix Canon Printer Won't Print in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-error-0xca00a009-from-windows-update-logs/"><u>Clearing Error 0xCA00A009 From Windows Update Logs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-0x8007045d-failure-on-microsoft-oses/"><u>Correcting 0X8007045D Failure on Microsoft OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/costly-mistakes-when-opting-for-discounted-activation-keys/"><u>Costly Mistakes When Opting for Discounted Activation Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/craft-secure-quick-access-button-in-windows-11-for-hardware-unhook/"><u>Craft Secure, Quick Access Button in Windows 11 for Hardware Unhook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-your-way-through-windows-file-organization/"><u>Customizing Your Way Through Windows File Organization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-your-pcs-intel-processor-gen-through-windows/"><u>Deciphering Your PC's Intel Processor Gen Through Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-system-fixes-via-hotkey-configurations-in-w1011/"><u>Efficient System Fixes via Hotkey Configurations in W10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-collaboration-with-these-5-innovative-windows-folder-techniques/"><u>Enhance Collaboration with These 5 Innovative Windows Folder Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explaining-and-solving-the-problem-of-missing-windows-drive-letters/"><u>Explaining and Solving The Problem Of Missing Windows Drive Letters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidance-to-overcome-same-user-account-error-on-pc/"><u>Guidance to Overcome Same-User Account Error on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-avoid-discord-starting-with-system-boots-up/"><u>How to Avoid Discord Starting with System Boots Up</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-apple-iphone-15-pro-apples-new-iphone-by-drfone-ios/"><u>How to Unlock Apple iPhone 15 Pro, Apples New iPhone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-can-i-bypass-a-forgotten-phone-password-of-vivo-v30-pro-by-drfone-android/"><u>In 2024, Can I Bypass a Forgotten Phone Password Of Vivo V30 Pro?</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-cutting-edge-obs-use-in-android-broadcasting/"><u>In 2024, Cutting-Edge OBS Use in Android Broadcasting</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-the-complete-guide-to-zte-axon-40-lite-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Complete Guide to ZTE Axon 40 Lite FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://fox-direct.techidaily.com/injecting-spark-into-your-unique-podcast-format/"><u>Injecting Spark Into Your Unique Podcast Format</u></a></li>
<li><a href="https://win11-tips.techidaily.com/inside-windows-power-to-guide-apps-browsers/"><u>Inside Windows' Power to Guide Apps, Browsers</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/instagrams-best-tools-ranked-editors-to-elevate-reels/"><u>Instagram's Best Tools Ranked  Editors to Elevate Reels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/managing-high-gpu-activity-in-windows-desktop-window/"><u>Managing High GPU Activity in Windows Desktop Window</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-formatting-essential-disk-error-on-pc/"><u>Navigating the 'Formatting Essential' Disk Error on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-0x80242016-error-in-windows-updates/"><u>Overcoming 0X80242016 Error in Windows Updates</u></a></li>
<li><a href="https://common-error.techidaily.com/power-overload-solution-for-interface-gateway/"><u>Power Overload Solution for Interface Gateway</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventive-tips-the-top-7-windows-activities-that-could-be-risky/"><u>Preventive Tips: The Top 7 Windows Activities That Could Be Risky</u></a></li>
<li><a href="https://win11-tips.techidaily.com/probing-the-digital-core-acquiring-sids-on-win11-systems/"><u>Probing the Digital Core: Acquiring SIDs on Win11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-dropbox-cpu-load-on-windows-systems/"><u>Reducing Dropbox CPU Load on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refreshing-your-pc-resetting-windows-11-applications/"><u>Refreshing Your PC: Resetting Windows 11 Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sketchmasters-roundup-top-7-drawing-tools-for-windows/"><u>SketchMasters Roundup: Top 7 Drawing Tools for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/smooth-launch-into-lotr-world-lol/"><u>Smooth Launch Into LOTR World (LOL)</u></a></li>
<li><a href="https://video-capture.techidaily.com/state-of-the-art-gaming-capture-systems-not-just-fbx-files-for-2024/"><u>State-of-the-Art Gaming Capture Systems, Not Just FBX Files for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-razer-blade-pro-17-unveiled-high-end-performance-tailored-for-travel/"><u>The Razer Blade Pro 17 Unveiled: High-End Performance, Tailored for Travel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/time-traveling-computers-into-the-windows-11-era-with-old-tools/"><u>Time Traveling Computers Into the Windows 11 Era with Old Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-preventing-unwanted-command-window-activation/"><u>Tips for Preventing Unwanted Command Window Activation</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/top-10-airplay-apps-in-samsung-galaxy-a34-5g-for-streaming-drfone-by-drfone-android/"><u>Top 10 AirPlay Apps in Samsung Galaxy A34 5G for Streaming | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/tweet-trends-unveiled-top-videos-of-the-twittersphere-for-2024/"><u>Tweet Trends Unveiled  Top Videos of the Twittersphere for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-picture-files-on-windows-11-pc/"><u>Unlocking Picture Files on Windows 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unwanted-warning-fixes-for-chrome-on-windows-systems/"><u>Unwanted Warning Fixes for Chrome on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-how-to-invisibly-remove-the-language-feature/"><u>Windows 11: How to Invisibly Remove the Language Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-excellence-via-vivetool-getting-ahead-of-the-curve/"><u>Windows Excellence via ViVeTool: Getting Ahead of the Curve</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-yourphoneexe-necessary-or-not-for-security/"><u>Windows' YourPhone.exe - Necessary or Not for Security?</u></a></li>
</ul></div>
