---
title: "Fix Guide: Enhance Windows Bluetooth Device with Full Sound Features"
date: 2024-09-11T01:20:46.230Z
updated: 2024-09-12T01:20:46.230Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Fix Guide: Enhance Windows Bluetooth Device with Full Sound Features"
excerpt: "This Article Describes Fix Guide: Enhance Windows Bluetooth Device with Full Sound Features"
keywords: Bluetooth Audio Fix,Full Sound on Windows,Windows Bluetooth Tips,Improve Bluetooth Sound,Windows Hearing Boost,Bluetooth Device Enhancement,Optimize Windows Audio
thumbnail: https://thmb.techidaily.com/fa290563760e589f24a85fc95189dcd8b9293ad6203d8af2e7f7aed06726e6d2.jpg
---

## Fix Guide: Enhance Windows Bluetooth Device with Full Sound Features

 When you connect your Bluetooth headphone or speaker to your Windows computer, it may show the status as connected as "voice only" or "music only." This is nothing a quick "disconnect and reconnect" troubleshooting method can’t usually solve.

 However, if a quick reconnect doesn’t help, the problem may be due to a buggy audio driver, incorrect audio device configuration, and stopped audio services. Here we show you a few troubleshooting tips to help you resolve this problem on Windows and get your Bluetooth headset working again.

## 1\. Run the Windows Bluetooth Troubleshooter

![Run Bluetooth troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/bluetooth-troubleshooter-1.jpg)





<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014854/22899" target="_top" id="2014854">
  <img src="//a.impactradius-go.com/display-ad/22899-2014854" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014854/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 Windows 10 and 11 feature a built-in troubleshooter to find and fix common Bluetooth issues. It is an automated tool but works differently on Windows 10 and 11\.

 To run the Bluetooth troubleshooter:

1. Press **Win + I** to open **Settings**.
2. In the **System** tab, scroll down and click on **Troubleshooter**.
3. Select the **Other troubleshooters** option.  
![bluetooth troubleshooter get help automatic diagnostic](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/bluetooth-troubleshooter-get-help-automatic-diagnostic.jpg)
4. Click **Run** for the **Bluetooth** option.
5. The troubleshooter will scan the system for issues and recommend applicable fixes automatically. Follow the on-screen instructions to apply the fixes.
6. On the newer iteration of Windows 11, this will open the **Get Help** app seeking your consent to run the troubleshooter. Click **Yes** and then follow the on-screen instructions. You can skip some steps, like checking for Windows updates, by selecting the **No** option.

 Let the Get Help app try all available fixes until the issue is fixed.

## 2\. Enable Bluetooth Services in Device Properties

 Your headset or speaker offers distinct services which are enabled by default. However, if disabled, one or more Bluetooth functions can stop working for your audio device. To fix the issue, open the Bluetooth device properties using the Control Panel and review the services.

 Here’s how to do that:

1. Press **Win + R** to open **Run**.  
![control printers run box windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/control-printers-run-box-windows.jpg)
2. Type **control Printer** and click **OK** to open the **Bluetooth & devices** tab in the **Settings** app.




<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123740/7443" target="_top" id="2123740">
  <img src="//a.impactradius-go.com/display-ad/7443-2123740" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123740/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




3. Next, click on **Devices**.  
![bluetooth and devices devices windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/bluetooth-and-devices-devices-windows-11-settings.jpg)
4. Scroll down and click **More devices** **and printer settings**. This should open **Devices and Printers** in the Control Panel.




<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014859/22899" target="_top" id="2014859">
  <img src="//a.impactradius-go.com/display-ad/22899-2014859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014859/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




5. Alternatively, copy and paste the following in the **Run** dialog to open **Device and Printers**.  
`shell:::{A8A91A66-3A7D-4424-8D24-04E180695C7A}`
6. Next, right-click on your **Bluetooth headset** or **speaker** and select **Properties**.
7. Open the **Services** tab in the **Properties** dialog.
8. Under **Bluetooth services**, select all the options. You’ll usually have the following options. Enable them all:  
`Audio Sink  
Handsfree Telephony  
Remote Control  
Remotely Controllable Device`
9. Click **Apply** and **OK** to save the changes.

 Close the Control Panel, and your Bluetooth audio device should start to work now. If not, perform a restart and check for any improvements.

## 3\. Check and Enable the Windows Bluetooth Services

 Windows OS uses multiple Bluetooth-related services that help it connect to other Bluetooth devices and transmit audio. This is in addition to the services enabled above.

 If any of these services are stopped or incorrectly configured, your Bluetooth headphone or speaker can start malfunctioning. To fix the problem, check the status of all the essential Bluetooth-associated services and restart them if necessary.

 You can check the status of services and restart them from the Services snap-in. To check and restart Bluetooth services:

1. Press **Win + R** to open **Run**.
2. Type **services.msc** and click **OK** to open the Services snap-in.  
![Services Shortcode In Run Dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/opening-sevices-from-run_dialog.jpg)
3. In the Services snap-in, locate the following services and check if the status shows **Running**.  




<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135394/19272" target="_top" id="2135394">
  <img src="//a.impactradius-go.com/display-ad/19272-2135394" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135394/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




`Bluetooth Audio Gateway Service  
Bluetooth Support Service  
Bluetooth User Support Service`
4. If not, right-click on **Bluetooth Audio Gateway Service** and select **Restart**.  
![restart bluetooth services services snap in windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/restart-bluetooth-services-services-snap-in-windows.jpg)
5. Once done, check the other two services. If not running, restart the services one by one.
6. Close the Services snap-in and check for any improvements.

 If the issue persists, [disable any audio enhancements on Windows](https://www.makeuseof.com/disable-audio-enhancements-windows/). While intended to improve your listening experience, these enhancements can also cause audio issues. Turning off these enhancements can help you resolve the problem with your audio devices.





<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134495/18498" target="_top" id="2134495">
  <img src="//a.impactradius-go.com/display-ad/18498-2134495" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134495/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 4\. Check Your Bluetooth Device Driver for Issues

 An outdated or buggy Bluetooth driver is a common cause of a malfunctioning Bluetooth device on Windows computers. Try to update the driver, perform a roll back or uninstall the driver to see if it resolves the issue.

* **Update the driver**: You can [find and replace outdated drivers on Windows using Device Manager](https://www.makeuseof.com/tag/find-replace-outdated-windows-drivers/). In Device Manager, expand the **Bluetooth** section and locate your Bluetooth adapter. On most computers, you may find an **Intel Bluetooth Wireless Bluetooth** device. Find the device and check if a new driver update is available.
* **Roll back a recent driver update**: New but buggy driver update can also cause the Bluetooth adapter to act up. To fix the issue, you can [perform a driver rollback for the Bluetooth adapter](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) to install the previous driver version. While a handy option, its availability can differ depending on when the driver was installed.
* **Reinstall the Bluetooth adapter driver:** A reinstall may be necessary if a corrupt or partially installed driver causes Bluetooth-related problems. To [uninstall Bluetooth drivers in Windows](https://www.makeuseof.com/windows-11-uninstall-drivers/), you can use the Device Manager or the Command Prompt. Restart your PC and Windows should reinstall the driver.

## 5\. Update the Bluetooth Driver Manually From the Manufacturer’s Website

 While some driver updates may be available via Windows updates, you will likely receive the latest update from the device manufacturer's website. In this instance, check your Bluetooth device manufacturer's website to see if a new update is available.

 To manually download and install the latest Bluetooth device driver update:

1. Press **Win + R** to open **Run**.
2. Type **devmgmt.msc** and click **OK** to open Device Manager.
3. In Device Manager, expand the **Bluetooth** section. Here locate your Bluetooth device's make. In this instance, we have an **Intel (R) Wireless Bluetooth (R)** device.  
![device manager driver version detials](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/device-manager-driver-version-detials.jpg)
4. Double-click on the Bluetooth device entry to open its properties.
5. Next, open the **Driver** tab. Note down the Driver version. You’ll need this to see if a newer driver version is available.
6. Since we have an Intel Bluetooth Wireless device, we’ll open the [Intel Wireless Bluetooth for Windows page](https://www.intel.com/content/www/us/en/download/18649/intel-wireless-bluetooth-for-windows-10-and-windows-11.html). The page lists the latest version of the driver available for download. In case of a different Bluetooth device manufacturer, visit the manufacturer's website and locate downloads for the device.  
![download bluetooth driver manually](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/download-bluetooth-driver-manually.jpg)
7. Compare the version with the one available on your computer. Download the newer version if available. Run the installer and complete the installation.




<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135396/19272" target="_top" id="2135396">
  <img src="//a.impactradius-go.com/display-ad/19272-2135396" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135396/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




8. During installation, your Bluetooth devices, including the headphone, keyboard, and mouse, may stop working temporarily. Wait for a few minutes for the changes to apply. Sometimes, a restart may be necessary to finish installing the update.

 Similarly, the download page may also offer older versions of the driver. If you have the latest version installed, try to download an older version to perform a downgrade. Useful if the rollback driver option isn’t available in Device Manager.





<!-- affiliate ads begin -->
<span id="1770776">
					<video width="240" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1770776.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20702-1770776">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1770776.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftokenmetrics.sjv.io%2Fc%2F5597632%2F1770776%2F20702'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1770776/20702" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Fixing the Bluetooth Headset or Speaker Showing a "Voice Only" Error

 Incorrect Bluetooth service configuration is a common reason your Bluetooth device shows as connected as voice only. You can configure the device’s properties to enable these services. If the issue persists, check for driver issues by installing a new driver update or performing a driver rollback.

 However, if a quick reconnect doesn’t help, the problem may be due to a buggy audio driver, incorrect audio device configuration, and stopped audio services. Here we show you a few troubleshooting tips to help you resolve this problem on Windows and get your Bluetooth headset working again.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-masterclass-in-instagram-story-downloads-and-creation/"><u>[New] 2024 Approved Masterclass in Instagram Story Downloads & Creation</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-accelerate-follower-count-key-strategies-unlocked-for-2024/"><u>[New] Accelerate Follower Count Key Strategies Unlocked for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-enhancing-video-content-top-formats-on-youtube-for-2024/"><u>[New] Enhancing Video Content Top Formats on YouTube for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-peak-procurement-of-lecture-captures-for-2024/"><u>[New] Peak Procurement of Lecture Captures for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-ultimate-guide-enjoy-tweets-in-stunning-hd-quality/"><u>[New] Ultimate Guide Enjoy Tweets in Stunning HD Quality</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-tune-in-to-success-mastering-the-art-of-vocal-change-on-insta/"><u>[Updated] 2024 Approved Tune in to Success Mastering the Art of Vocal Change on Insta</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-elevating-positivity-in-a-constructive-space-for-2024/"><u>[Updated] Elevating Positivity in a Constructive Space for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-professional-recording-apps-faceoff-obs-vs-fraps-for-2024/"><u>[Updated] Professional Recording Apps Faceoff – OBS vs Fraps for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-synergistic-campaigns-brands-and-youtube-hand-in-hand-for-2024/"><u>[Updated] Synergistic Campaigns Brands & YouTube Hand in Hand for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-unhackable-blueprint-for-inserting-your-tiktok-links/"><u>[Updated] Unhackable Blueprint for Inserting Your TikTok Links</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-enhancing-imagery-with-smart-layers-in-photoshop/"><u>2024 Approved Enhancing Imagery with Smart Layers in Photoshop</u></a></li>
<li><a href="https://techtrends.techidaily.com/best-18-video-player-apps-compatible-with-mac-windows-10-ios-and-android/"><u>Best 18 Video Player Apps Compatible with Mac, Windows 10, iOS & Android</u></a></li>
<li><a href="https://change-location.techidaily.com/can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-vivo-s18-pro-drfone-by-drfone-virtual-android/"><u>Can I use iTools gpx file to catch the rare Pokemon On Vivo S18 Pro | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/capture-kings-arena/"><u>Capture King's Arena</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-unsupported-apps-on-windows-vista/"><u>Dealing with Unsupported Apps on Windows Vista</u></a></li>
<li><a href="https://facebook.techidaily.com/discovering-the-world-of-ray-ban-stories-through-facebook/"><u>Discovering the World of Ray-Ban Stories Through Facebook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-hypothetical-device-misidentification-on-win-11/"><u>Eliminating Hypothetical Device Misidentification on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/empower-your-mouse-movements-with-global-friendly-powertoys/"><u>Empower Your Mouse Movements with Global-Friendly PowerToys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-analysis-selecting-the-best-photo-org-for-windows/"><u>Expert Analysis: Selecting the Best Photo Org for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-effectively-assigning-shortcuts-on-windows-11/"><u>Expert Tips for Effectively Assigning Shortcuts on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-windows-tool-for-managing-system-components/"><u>Exploring Windows Tool for Managing System Components</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-persistent-settings-in-windows-sound-system/"><u>Fixing Non-Persistent Settings in Windows Sound System</u></a></li>
<li><a href="https://change-location.techidaily.com/home-button-not-working-on-lava-storm-5g-here-are-real-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Home Button Not Working on Lava Storm 5G? Here Are Real Fixes | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-increase-fps-troubleshooting-performance-drops-in-farming-simulator-22-on-pc/"><u>How to Increase FPS: Troubleshooting Performance Drops in Farming Simulator 22 on PC</u></a></li>
<li><a href="https://extra-hints.techidaily.com/immersive-inventory-visualization/"><u>Immersive Inventory Visualization</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-tiktok-to-see-more-content-on-your-oppo-find-x6-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location on TikTok to See More Content On your Oppo Find X6 | Dr.fone</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/in-depth-analysis-of-asus-rog-zephyrus-g14-balancing-large-display-and-compromise/"><u>In-Depth Analysis of Asus ROG Zephyrus G14 - Balancing Large Display and Compromise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-how-to-manipulate-audio-configurations-with-windows-11/"><u>Master How to Manipulate Audio Configurations with Windows 11</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-editing-canon-videos-like-a-pro-top-software-and-techniques-for-2024/"><u>New Editing Canon Videos Like a Pro Top Software and Techniques for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/new-horizons-essential-alterations-to-windows-11s-explorer/"><u>New Horizons: Essential Alterations to Windows 11'S Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-updater-issue-code-x80246007-on-win1011/"><u>Overcome Updater Issue Code X80246007 on WIn10/11</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-stuck-on-downloading-of-gionee-f3-pro-7-ways-to-resolve-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Stuck on Downloading Of Gionee F3 Pro? 7 Ways to Resolve | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-alter-your-cursors-look-in-windows-10/"><u>Quick Fix: Alter Your Cursor's Look in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rekindling-stagnant-windows-discord-window-functionality/"><u>Rekindling Stagnant Windows Discord Window Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/returning-to-standard-windows-folder-layouts/"><u>Returning to Standard Windows Folder Layouts</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/review-of-the-samsung-galaxy-s1e-small-size-doesnt-mean-less-value/"><u>Review of the Samsung Galaxy S1e - Small Size Doesn't Mean Less Value</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-your-computers-dead-usb-connectors-in-windows/"><u>Revive Your Computer's Dead USB Connectors in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simple-strategies-to-reboot-distribution-and-catroot-in-windows-11/"><u>Simple Strategies to Reboot Distribution & Catroot in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skip-unverified-warning-in-adobe-software/"><u>Skip Unverified Warning in Adobe Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-java-vm-crash-on-windows-machines/"><u>Solutions to Java VM Crash on Windows Machines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-weather-icon-integration-into-windows-11/"><u>Step-by-Step Guide: Weather Icon Integration Into Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-lost-lan-signal-in-windows-system/"><u>Tackling Lost LAN Signal in Windows System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-for-rectifying-inaccurate-malware-warning-in-chrome/"><u>Tactics for Rectifying Inaccurate Malware Warning in Chrome</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/tango-communication-app-reviewed-enjoy-voicevideo-plus-text-messaging-for-free/"><u>Tango Communication App Reviewed: Enjoy Voice/Video + Text Messaging for Free!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turn-off-windows-app-start-monitoring/"><u>Turn Off Windows App Start Monitoring</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-editing-internet-setup-in-win11/"><u>Understanding and Editing Internet Setup in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-the-full-potential-of-your-windows-11-display/"><u>Unleash the Full Potential of Your Windows 11 Display</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-full-capabilities-of-windows-11-key-adjustments-made-easy/"><u>Unlocking the Full Capabilities of Windows 11: Key Adjustments Made Easy</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-pokemon-evolve-with-a-dawn-stone-for-nokia-150-2023-drfone-by-drfone-virtual-android/"><u>What Pokémon Evolve with A Dawn Stone For Nokia 150 (2023)? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windocs-remedying-missing-msvcr120dll-file-errors/"><u>WinDOCS: Remedying Missing Msvcr120.dll File Errors</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>