---
title: Resolving Windows Hello Authentication Failure
date: 2024-09-13T00:54:41.701Z
updated: 2024-09-16T16:24:07.721Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Windows Hello Authentication Failure
excerpt: This Article Describes Resolving Windows Hello Authentication Failure
keywords: Fixing Windows Auth Error,WinAuth Problem Resolution,Overcoming Login Failures,Windows Sign-In Troubleshooting,Authenticating Windows Success,Correcting Hello Sign-In Issues,Remedy Windows Authentication Fail
thumbnail: https://thmb.techidaily.com/485101ae8f555e145174a15eda6071c25617b2b00c96089d339b8e4537366b75.jpg
---

## Resolving Windows Hello Authentication Failure

 If you receive an error message that says, "we couldn't find a fingerprint scanner compatible with Windows Hello Fingerprint" when trying to set up Windows Hello fingerprint login, then your device either doesn't support fingerprint recognition, the fingerprint scanner (or reader) isn't working correctly, or Windows is unable to detect it.

 Windows may not detect the fingerprint scanner for several reasons: the fingerprint reader may have malfunctioned, the biometric drivers could be outdated or corrupted, or biometric recognition could be disabled in the BIOS. If you're tired of dealing with this problem, try these solutions.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Ensure Your Device Supports Fingerprint Recognition

![blue graphic of digital fingerprint scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/blue-finger-scan.jpg)

 The Windows Hello fingerprint recognition feature requires your device to have a fingerprint reader. If you encounter the error "we could not find a fingerprint scanner compatible with Windows Hello Fingerprint" when setting up fingerprint recognition for the first time, make sure your device is equipped with a fingerprint reader compatible with Windows Hello.

 Usually, it is located near (or on) the power button or in the empty space above or below the keyboard. Look around and see if you can find a fingerprint reader. If you fail to find it, check your device's specifications on the manufacturer's website to see if it has a fingerprint scanner.

 If your device does not have a fingerprint reader, you cannot enable biometric authentication on it. However, if your device has a scanner, and you've used it many times before, ensure that it is working correctly.

## 2\. Make Sure the Fingerprint Reader Is Working Properly

![security fingerprint on keyboard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/data-1590455_1920-1.jpg)

 If your device has a fingerprint sensor, but Windows is unable to detect it, ensure the sensor hasn't gone bad. To test the fingerprint reader, sign in to another app where you've set up biometric login. If that app fails to accept biometric verification, use a dry cloth to wipe the dust off your fingerprint scanner.

 After that, try scanning your finger again. If the app fails to recognize the fingerprint scan even after thoroughly cleaning it, there is probably an issue with the scanner. So, have your device inspected by a technician. However, if the scanner works fine on other apps but not when you set up Windows Hello fingerprint login, then apply the remaining fixes.

## 3\. Roll Back the Driver or the Latest Windows Update

 Have you encountered the error under discussion after updating the biometric driver or installing a Windows update recently? If this is the case, you should roll back these updates. Don't know how to do that? Our guide on[how to roll back a driver update on Windows](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) describes the process. If you want to roll back a Windows update, then you need to[uninstall the most recent Windows Update](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) .

 Once you've undone both driver and Windows updates, try setting up Windows Hello biometric login again. If you continue to experience the same problem after rolling back these updates, it suggests that undoing these updates hasn't made a difference. In that case, you should reinstall the drivers and Windows update.

## 4\. Ensure the Windows Biometric Service Is Configured Properly

 When the Windows biometric service is disabled, Windows Hello fingerprint recognition won't work. To ensure this service is enabled and configured correctly, follow these steps:

1. Type**"Services"** in Windows Search and open the**Services** app.  
![Open Services App From Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/1-open-services-app-from-windows-search.jpg)
2. Locate**Windows Biometric Service** .  
![Locate Windows Biometric Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/2-locate-windows-biometric-service-in-windows-services-app.jpg)
3. If you see**"Running"** next to this service in the**Status** column, it's already running. If not, it's disabled.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137219/26400" target="_top" id="2137219">
  <img src="//a.impactradius-go.com/display-ad/26400-2137219" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137219/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. In either case, right-click the service and select**Properties** .  
![Go to Properties of Windows Biometric Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3-go-to-properties-of-windows-biometric-service-in-windows-services-app.jpg)
5. Click on the dropdown menu next to**Startup type** and select**Automatic** .  

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134244/18498" target="_top" id="2134244">
  <img src="//a.impactradius-go.com/display-ad/18498-2134244" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134244/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Select Automatic From the Startup Type Dropdown Menu in the Properties Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/4-select-automatic-from-the-startup-type-dropdown-menu-in-the-properties-window.jpg)
6. If it's already selected, click the**Stop** button to stop the service and then click**Start** again to restart it.  
![Click Start Button to Restart the Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/5-click-start-button-to-restart-the-service-in-windows-services-app.jpg)

## 5\. Update or Reinstall the Biometric Drivers

 If the biometric service is already enabled, yet the fingerprint recognition feature isn't working, the biometric drivers could be outdated or corrupt. To ensure that isn't the case, update the biometric device drivers. To do so, follow these steps:

1. Type**"Device Manager"** in Windows Search and open the**Device Manager** app.
2. Expand the**Biometric devices** category.
3. Right-click on your fingerprint scanner device and select**Update driver** .  
![Update the Fingerprint Scanner Device in Windows Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/6-update-the-fingerprint-scanner-device-in-windows-device-manager.jpg)
4. Then, click on**Search automatically for drivers** .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135393/19272" target="_top" id="2135393">
  <img src="//a.impactradius-go.com/display-ad/19272-2135393" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135393/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If updating the drivers does not fix the problem, right-click the biometric device again and select**Uninstall device** . After uninstalling the drivers, reboot your device, and Windows will automatically install them again. If you prefer, you can also download the relevant drivers from the manufacturer's website and install them manually.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135414/19272" target="_top" id="2135414">
  <img src="//a.impactradius-go.com/display-ad/19272-2135414" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135414/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Disable Fast Startup

 According to some users on a[Microsoft community thread](https://answers.microsoft.com/en-us/windows/forum/all/fingerprint-reader-not-working/95cc0aef-2822-4b51-9f77-8697e6ace897) , disabling the Fast Startup feature has solved fingerprint recognition issues on their devices. Although Fast Startup speeds up your device's boot process, turning it on is known to cause unforeseen problems.

 So, if you also keep this feature enabled on your device, disable it to see if it makes a difference. Don't know how to do that? Refer to our guide on[enabling or disabling Fast Startup on Windows 11](https://www.makeuseof.com/windows-11-turn-on-or-off-fast-startup/) .

## 7\. Ensure the Biometric Reader Isn't Disabled in BIOS

 Some laptops allow users to disable the fingerprint reader in BIOS. If you're setting up a fingerprint login for the first time and getting the error, ensure the fingerprint scanner isn't disabled in BIOS. Accessing BIOS and navigating to the option to enable or disable the biometric device varies between manufacturers.

 If you need guidance on accessing the BIOS and enabling the biometric device, visit your laptop manufacturer's website.

## 8\. When Nothing Else Works…

 If nothing else works, run the Hardware and Devices troubleshooter, enable biometrics in the Local Group Policy Editor, and check for account-specific issues. If these steps fail to resolve the issue, perform a system restore as a last resort. Our guide on[fixing Windows Hello fingerprint recognition](https://www.makeuseof.com/windows-hello-fingerprint-not-working/) explains how to make the above-mentioned changes.

## Get Rid of Annoying Fingerprint Recognition Errors

 If you encounter an error when setting up Windows Hello fingerprint recognition, it does not mean the feature can't be used. If your device supports biometric authentication, the above fixes will help you resolve the annoying error.

 If you are setting up a fingerprint login for the first time, make sure you do it correctly. Otherwise, you'll be constantly annoyed by the bothersome errors when using this fantastic feature.

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
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-understanding-2023s-push-for-shorter-more-impactful-facebook-videos/"><u>[New] In 2024, Understanding 2023'S Push for Shorter, More Impactful Facebook Videos</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-stream-viewer-unraveler-for-2024/"><u>[New] Stream Viewer Unraveler for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-groupgaze-video-extractor-for-2024/"><u>[Updated] GroupGaze Video Extractor for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-windows-vmfreeze-ups-vmware-guide/"><u>Clearing Up Windows VMfreeze-Ups: VMware Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dynamic-desktop-decoration-integrating-spotlight-images-for-wallpapers/"><u>Dynamic Desktop Decoration: Integrating Spotlight Images for Wallpapers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-pcs-gaming-potential-with-advanced-amd-radeon/"><u>Elevate Your PC's Gaming Potential With Advanced AMD Radeon</u></a></li>
<li><a href="https://win-able.techidaily.com/fixing-issue-4201-in-genshin-impact-a-complete-guide/"><u>Fixing Issue 4201 in Genshin Impact - A Complete Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-quicken-slow-excel-processes-on-windows-machines/"><u>How to Quicken Slow Excel Processes on Windows Machines</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-8-best-apps-for-screen-mirroring-vivo-y100i-power-5g-pc-drfone-by-drfone-android/"><u>In 2024, 8 Best Apps for Screen Mirroring Vivo Y100i Power 5G PC | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-understanding-macos-11-big-sur-transition-tips/"><u>In 2024, Understanding macOS 11 Big Sur Transition Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-your-phone-calls-into-windows-11-via-intel-unison/"><u>Integrating Your Phone Calls Into Windows 11 via Intel Unison</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-to-open-disk-space-on-windows-1011/"><u>Step-by-Step to Open Disk Space on Windows 10/11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-and-fixing-your-pc-after-encountering-whea-errors/"><u>Troubleshooting and Fixing Your PC After Encountering WHEA Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-fixing-silent-microphone-issues/"><u>Understanding and Fixing Silent Microphone Issues</u></a></li>
<li><a href="https://os-tips.techidaily.com/unlocking-fresh-capabilities-discover-the-iphone-improvements-in-apples-recent-ios-1evolution-version-172-update/"><u>Unlocking Fresh Capabilities: Discover the iPhone Improvements in Apple's Recent iOS 1Evolution, Version 17.2 Update</u></a></li>
</ul></div>

