---
title: A Step-by-Step Plan for Installing WIN11 Version 22H2 Updater
date: 2024-08-16T01:17:44.512Z
updated: 2024-08-17T01:17:44.512Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Step-by-Step Plan for Installing WIN11 Version 22H2 Updater
excerpt: This Article Describes A Step-by-Step Plan for Installing WIN11 Version 22H2 Updater
keywords: Win11 Update Guide,Windows 11 H2 Installer,Win11 V22H2 Installation,WIN11v22Updater Steps,Upgrade to Win11H2,Win11 22H2 Update Plan,Execute Windows 11 H2 Patch
thumbnail: https://thmb.techidaily.com/d222a947a358a9a5da5a72c775e634907e671d005e0a2808f2ac3a2ab7305bec.jpg
---

## A Step-by-Step Plan for Installing WIN11 Version 22H2 Updater

 Microsoft released its first Windows 11 build version update in September 2022\. The 22H2 update has added a slew of new Windows 11 features and options. Many users are now installing that update via Settings.

 However, some users have reported in forums that they can’t upgrade Windows 11 to the 22H2 version. Those users have said that updates get stuck at percentage marks when they try to download and install them from Settings. Some users see error codes like 0x800f0806 for that update. This is how you can fix the Windows 11 22H2 update not installing.

## 1\. Run Windows 11’s Troubleshooter for Updates

 The Windows Update troubleshooter is there to check for and resolve issues with the update process. That troubleshooter isn’t guaranteed to fix all update errors, but it might fix Windows 11’s 22H2 update not installing for some users at least. You can run the Windows Update troubleshooter in the following steps:

1. Press**Win** +**I** to open**Settings** .
2. Select the**System** tab’s**Troubleshoot** option.
3. Click**Other trouble-shooters** to reach the troubleshooting utilities.
4. Select**Run** for the Windows Update troubleshooter.  
![The Run button for Windows Update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/the-run-button-for-windows-update-1.jpg)
5. Wait for the troubleshooter to detect issues and display an outcome. It will usually automatically apply fixes for detected issues.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Disconnect Non-Essential External Hardware and Peripherals From PC

 It's recommended that users unplug non-essential hardware from PCs before attempting to upgrade to a new Windows 11 version. Doing so will ensure that there aren't any non-essential hardware devices that can potentially interrupt or conflict with the upgrade process. You'll still need your mouse and keyboard of course, but disconnect all the following non-essential peripherals:

* Headphones
* External storage drives
* Printers
* Scanners
* Speakers (they're not essential)
* Gamepads
* USB Hubs
* Webcams
* Microphones
* Secondary monitors (you only need one)

## 3\. Run a System File and Deployment Image Scan

 System file corruption can cause Windows update errors to arise. You can check for and remedy corrupted files by running a System File Checker scan in the Command Prompt. It’s also recommended to run a Deployment Image Servicing and Management scan to check the system image before that. This is how to run both scanning tools in Windows 11.

1. Open the file search tool with the**Windows** +**S** hotkey.
2. Search for Command Prompt by inputting**cmd** in the text box.
3. Right-click Command Prompt inside the search tool’s results to select a**Run as administrator** option.
4. Start by inputting this command and pressing**Enter** :  
`DISM.exe /Online /Cleanup-image /Restorehealth`
5. Then run the SFC tool by typing in the following command and pressing**Return** :  
`sfc /scannow`
6. Wait for the SFC scan to show an outcome message in the Command Prompt.

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->
## 4\. Free Up Some Drive Storage Space

 You’ll need at least 64 gigabytes of drive storage space available for the Windows 11 22H2 update. So, check your hard drive has enough space for the 22H2 update before installing it.

 If it doesn’t, free up the required drive storage space for the update by erasing superfluous files and uninstalling Windows software. Check out our [Cleanup recommendations guide](https://www.makeuseof.com/free-storage-space-with-cleanup-recommendations/) for further details about how to create storage space via Settings.

![Cleanup recommendations in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/cleanup-recommendations-1.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<span id="1793213">
					<video width="1080" height="1620" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:1080px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Check If the Dependency Services for Windows Update are Enabled

 The Windows Update service has some service dependencies that need to be enabled and running. Windows 11 22H2 update issues will likely arise if necessary prerequisite services are disabled. You can make sure the Windows Module Installer, BITS, and CryptSvc services are enabled like this:

1. Open Windows 11’s Services utility. You can check out our [how-to-open Services guide](https://www.makeuseof.com/windows-11-open-services-app/) for further instructions.
2. Double-click**Windows Module Installer** to view a properties window for that service.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/windows-modules-installer-1.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
3. Select the**Automatic** start option for the service on its**Startup type** drop-down menu.
4. Click**Start** on the properties window if the service isn’t running.  
![The Windows Modules Installer service properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/a-service-properties-window-1.jpg)
5. Select**Apply** \>**OK** to set the service’s settings.
6. Repeat the previous four steps for the Background Intelligent Transfer Service, Cryptographic Service, and Windows Update services.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Make Sure .NET Framework 3.5 is Enabled

 The .NET Framework 3.5 feature also needs to be enabled for the Windows Update service to work. That should be enabled by default in Windows 11, but some users may still need to turn on .NET Framework 3.5\. This is how you can make sure .NET Framework 3.5 is enabled in Windows 11:

1. Open the file and app search utility by pressing the**Windows** +**S** key combo.
2. Enter**Windows features** in the**Type here to search** box.
3. Click the**Turn Windows features on or off** applet in the search tool.
4. Select the**.NET Framework 3.5** checkbox if that feature isn’t enabled.  
![The Windows Features window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/the-windows-features-window-1.jpg)
5. Also, click the**.NET Framework 4.8** checkbox if it’s not selected.
6. Press the**OK** button in the Windows Features window.
7. Then click**Yes** to install.
8. Restart Windows 11 after installing the feature.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
## 7\. Reset the Components for Windows Update

 Windows 11 22H2 update issues can also arise because of corrupted update components. You can repair the update components by resetting them. This troubleshooting method involves restarting update services and refreshing the catroot2 and SoftwareDistribution folders by renaming them. You can reset components for Windows updates with the Command Prompt like this:

1. Open Command Prompt with elevated permissions, as outlined in steps one to three of method two.
2. Then stop four services by inputting and executing the following commands:  
`net stop wuauserv  
net stop bits  
net stop cryptSvc  
net stop msiserver`
3. Next, rename the SoftwareDistribution folder by executing this command:  
`ren C:\Windows\SoftwareDistribution SoftwareDistribution.old`  
![The ren SoftwareDistribution command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/the-ren-softwaredistribution-command-1.jpg)
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Input this rename catroot2 command and press**Return** :  
`ren C:\Windows\System32\catroot2 Catroot2.old`  
![The ren catroot2 folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/the-ren-catroot2-folder-1.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
5. Then restart the services with these commands:  
`net start wuauserv  
net start bits  
net start cryptSvc  
net start msiserver`
6. Close Command Prompt, and select**Restart** on your Start menu.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 8\. Turn Off Third-Party Antivirus Utilities

 Some third-party antivirus utilities can mistakenly interfere with the update process for Windows 11’s 22H2 update. To stop this from happening, disable real-time scanning for third-party antivirus software.

 If you have a third-party antivirus tool installed, right-click its system tray icon and select a context menu option to turn off its shield for a few hours; then try upgrading Windows 11 to the 22H2 version with the antivirus software disabled.

 AVG and Avast are two antivirus software packages that often generate Windows update errors. Those antivirus tools have also been incompatible with some Windows 10 builds. If you have either of those two installed, consider uninstalling them instead of merely disabling their shields.

## 9\. Disable Kernel DMA Protection

 Some users have said the Kernel DMA Protection security feature in Windows 11 causes the 22H2 update to fail when enabled. If that feature is enabled on your desktop or laptop, disabling it could fix the Windows 11 22H2 not installing. To check if Kernel DMA Protection is enabled,[open the System Information app](https://www.makeuseof.com/windows-11-check-system-information/) and look for that feature in the**System Summary** section.

![The Kernel DMA Protection system detail](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/the-kernal-dma-system-detail-1.jpg)

 The only way to turn off Kernel DMA Protection is to disable a setting for it in the BIOS (Basic Input Output System). You can access Basic Input Output System settings on Windows 11/10 PCs as outlined within our guide on [how to enter the BIOS](https://www.makeuseof.com/tag/enter-bios-computer/) . Look for and disable a Kernel DMA Protection setting on a**Security** tab within the BIOS.

## 10\. Update Your PC's Drivers

 Outdated device drivers can cause Windows upgrade issues. So, we recommend that you generally update device drivers on your PC. The quickest way to do that is to utilize a driver updater tool like Driver Booster.

 A Driver Booster scan will show you what devices on your PC have antiquated drivers. You can also select an**Update Now** option in that software to update the drivers for listed devices. Our [Driver Booster guide](https://www.makeuseof.com/update-windows-drivers-driver-booster-8/) includes instructions for updating drivers with that software.

![Driver Booster 8](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/driver-booster2.jpg)

 Alternatively, you may be able to install some new drivers with optional Windows updates. This is how you can check available optional updates in Windows 11:

1. [Open Settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/) and its**Windows Update** tab.
2. Select**Advanced options** to bring up some configuration settings for updates.
3. Click**Optional updates** to see if there are any driver updates available.
4. Select the checkboxes for driver updates there.
5. Click the**Download and install** option for selected driver updates.

## 11\. Install the 22H2 Update via the Installation Assistant

 This final resolution is more of a workaround than a fix for the 22H2 update not installing via Settings. Instead of using Settings, try upgrading with the Windows 11 Installation Assistant. We have a full guide that tells you [how to use the Installation Assistant](https://www.makeuseof.com/windows-11-installation-assistant-guide/) for updating Windows 11.

![The Windows 11 Update Assistant](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/the-windows-11-update-assistant.jpg)

## Discover the Windows 11 2022 Update

 Those possible solutions will likely resolve most 22H2 update errors for the majority of users. The resolutions on Microsoft’s [Windows update troubleshooting](https://support.microsoft.com/en-us/windows/troubleshoot-problems-updating-windows-188c2b0f-10a7-d72f-65b8-32d177eb136c#WindowsVersion=Windows%5F11) page might also help some users fix Windows 11’s 22H2 update not installing. With that issue fixed, you can discover all the interesting new features and options in the Windows 11 2022 Update.

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
<li><a href="https://fox-hovers.techidaily.com/new-2024-approved-digital-darkroom-mastering-color-opposites/"><u>[New] 2024 Approved  Digital Darkroom  Mastering Color Opposites</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-revolutionizing-tv-broadcasts-with-fb-live-streaming/"><u>[New] 2024 Approved  Revolutionizing TV Broadcasts with FB Live Streaming</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-snapchats-artistic-palette-the-anime-filter-experience/"><u>[New] In 2024, Snapchat’s Artistic Palette  The Anime Filter Experience</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-exploring-platform-variations-youtube-vs-dailymention/"><u>[Updated] 2024 Approved  Exploring Platform Variations  YouTube Vs. DailyMention</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-the-comprehensive-list-of-webinar-recording-methods/"><u>[Updated] In 2024, The Comprehensive List of Webinar Recording Methods</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-advanced-editing-for-professional-photographers-time-stamping-tactics/"><u>2024 Approved  Advanced Editing for Professional Photographers  Time-Stamping Tactics</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/2024-approved-your-iphones-mp3-fix-6-free-tools-to-convert-youtube-audio/"><u>2024 Approved  Your iPhone's MP3 Fix  6 Free Tools to Convert YouTube Audio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-windows-discords-inaccurate-search-results/"><u>Boosting Windows Discord's Inaccurate Search Results</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-cant-get-mail-easy-fixes-for-windows-11-users/"><u>Breaking Down 'Can't Get Mail': Easy Fixes for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-and-correcting-wsl-error-4294967295-on-pcs/"><u>Breaking Down and Correcting WSL: Error 4294967295 on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-windows-11s-operation-elevation-error-740/"><u>Breaking Down Windows 11'S Operation Elevation Error #740</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-into-windows-11-appsfolder-a-step-by-step-walkthrough/"><u>Breaking Into Windows 11 AppsFolder: A Step-by-Step Walkthrough</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-windows-chatbot-constraints-with-freedomgpt/"><u>Breaking Windows ChatBot Constraints with FreedomGPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathe-life-into-your-locked-windows-screen-saver/"><u>Breathe Life Into Your Locked Windows Screen Saver</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-the-basics-resetting-windows-11-privileges/"><u>Bring Back the Basics: Resetting Windows 11 Privileges</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-back-your-guardianship-quick-fixed-windows-tips/"><u>Bringing Back Your Guardianship: Quick Fixed Windows Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-error-code-2e-restore-windows-update/"><u>Bypass Error Code 2E, Restore Windows Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-the-deadlock-in-your-windows-update-journey/"><u>Bypass the Deadlock in Your Windows Update Journey</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-windows-blocks-for-handbrake-success/"><u>Bypass Windows Blocks for HandBrake Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-expiring-soon-error-on-windows-11-os/"><u>Bypassing 'Expiring Soon' Error on Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-immutable-energy-states-in-windows-11/"><u>Bypassing Immutable Energy States in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-11-hiccups-with-easy-fixes/"><u>Bypassing Windows 11 Hiccups with Easy Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cant-download-or-install-icloud-on-windows-try-these-fixes/"><u>Can’t Download or Install iCloud on Windows? Try These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cease-chromes-automatic-conversion-to-webp-format-pc-users/"><u>Cease Chrome’s Automatic Conversion to WebP Format PC Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/charming-windows-echoing-winters-joyful-spirit/"><u>Charming Windows: Echoing Winter's Joyful Spirit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/charting-a-new-course-overcoming-xbox-errors-in-win11/"><u>Charting a New Course: Overcoming Xbox Errors in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/charting-new-territory-ai-in-the-world-of-windows-11/"><u>Charting New Territory: AI in the World of Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/choosing-between-intel-unison-and-phone-link-best-wp-app/"><u>Choosing Between Intel Unison & Phone Link: Best WP App?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/choosing-wisely-critical-considerations-in-procuring-a-laptop/"><u>Choosing Wisely: Critical Considerations in Procuring a Laptop</u></a></li>
<li><a href="https://tech-haven.techidaily.com/deconstructing-nlp-giants-deep-dive-into-gpt-vs-bert/"><u>Deconstructing NLP Giants: Deep Dive Into GPT Vs. BERT</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-tecno-spark-10-5g-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Tecno Spark 10 5G Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/navigating-privacy-settings-to-uncover-someones-professional-email/"><u>Navigating Privacy Settings to Uncover Someone's Professional Email</u></a></li>
</ul></div>
