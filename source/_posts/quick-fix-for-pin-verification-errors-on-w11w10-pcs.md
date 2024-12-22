---
title: Quick Fix for Pin Verification Errors on W11/W10 PCs
date: 2024-12-18T09:26:23.781Z
updated: 2024-12-22T08:33:38.983Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Fix for Pin Verification Errors on W11/W10 PCs
excerpt: This Article Describes Quick Fix for Pin Verification Errors on W11/W10 PCs
keywords: Pin Verify Fix,Quick Fix Verification,Pin Error Resolve,Unlock PC Issue,Fix Pin Failure,Pin Troubleshoot Tips,Error Fix Verification
thumbnail: https://thmb.techidaily.com/56e9a63f6cd0da6aa662fe6ddfb8ba418b2232ba03eb8e75fedd97f8000b9ecc.jpg
---

## Quick Fix for Pin Verification Errors on W11/W10 PCs

 The “Check the PIN” error occurs for some users when they try pairing Bluetooth devices with their Windows 11/10 PCs. When users try connecting peripherals via Settings, the Add a device window shows this message, “Check the PIN and try connecting again.” Users say that issue typically occurs when they try to re-pair devices after unpairing them.

 The “Check the PIN” error means users can’t connect affected Bluetooth devices with their PCs. It is more widely reported to affect Bluetooth keyboards and headphones. You can fix the same issue on your PC with the potential “Check the PIN” fixes below.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qNrOsjUdRz0?si=xGzhmNmtgxNTsRxN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Run the Troubleshooter for Bluetooth

 Windows has a Bluetooth troubleshooter that can fix Bluetooth connectivity errors such as the “Check the PIN” Bluetooth error.

 You can find it listed among other troubleshooters within the Settings app. This [how-to-run Windows troubleshooters guide](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) includes instructions for opening troubleshooting tools via Settings.

![The Devices and Printers Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/add-a-device-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kZVDkvMZvP4?si=xAugrCf-Ud6EMMpm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Utilize the Add a Device Wizard

 The Add a device wizard provides another way to pair Bluetooth devices with your Windows PC. Some users have said they got around the “Check the PIN” error by pairing their Bluetooth devices with that wizard. This is how you can utilize the Add a device wizard in Windows 11/10:

1. Press **Windows** key + **S**, input **Control Panel**, and click the search result that matches the keyword entered.
2. Click **Large icons** on the Control Panel’s **View by** drop-down menu.  
![The Control Panel's large icon view](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-control-panel.jpg)
3. Then click **Devices and Printers** to view that applet.
4. Press the **Add a device** button.  
![The Devices and Printers Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/add-a-device-option.jpg)
5. Select your Bluetooth peripheral within the Add a device window. If you cannot see your Bluetooth device listed there, make sure it’s turned on and close enough to your PC to be discoverable.  

![The Add a device wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-add-a-device-wizard.jpg)
6. Click **Next** to proceed with Bluetooth device pairing.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oP8grXxuy2o?si=uIRNhTYbecTcaC7J" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. If prompted to input a WPS PIN, input the required device code in the text box.
8. Select **Next** to pair the Bluetooth device.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VlwHTQQMs?si=BXYwD1pKiaTuev4y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Edit the Addrs Registry Key

 There’s also a confirmed registry tweak solution for the “Check the PIN error.” This tweak involves deleting a numeric subkey within the **Addrs** registry key. We advise you to back up the registry before attempting to apply possible fixes that involve deleting keys.

 Follow the below steps to edit the **Addrs** registry key:

1. To [open Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/), find that app by activating the Windows search box and inputting a **regedit** keyword. Then you can select **Registry Editor** in the search results.
2. Next, click inside the registry address box to clear the path there.
3. Input this **Addrs** registry key path in the address box:  
`HKEY_USERS\.DEFAULT\Software\Microsoft\Windows\CurrentVersion\Bluetooth\ExceptionDB\Addrs`
4. Double-click the **Addrs** key to expand it. If the **ExceptionDB** key doesn’t include an **Addrs** key in your registry, you can’t apply this potential solution.
5. Then right-click a numeric subkey within the **Addrs** key and select **Delete**. That subkey’s title will include random numbers and maybe letters also.  
![The Delete registry key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-delete-registry-key-option.jpg)
6. Click **Yes** when prompted to confirm the deletion.  
![The Yes confirmation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-yes-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qn1XkPJde9Y?si=i6ZJARXO8sJhy2FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Update the Bluetooth Driver on Your PC

 Another possibility is that an old or faulty Bluetooth driver on your PC is causing the “Check the PIN” error. So, try updating your PC’s Bluetooth driver to see if that makes any difference. You can do that with the methods covered in this [guide to finding and replacing outdated drivers](https://www.makeuseof.com/tag/find-replace-outdated-windows-drivers/).

 The most straightforward way to apply this resolution is to utilize a driver updater utility, such as Driver Booster 8\. That will show if the Bluetooth driver on your PC is outdated and provide you with an option to download and install a new one. We recommend utilizing one of the software packages from the [best free driver updaters for Windows](https://www.makeuseof.com/windows-best-free-driver-updaters/).

![The Driver Booster software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/driver-booster-software.jpg)

## Utilize Your Bluetooth Peripheral With Windows PC

 There aren’t lots of confirmed potential fixes for the “Check the PIN” error. However, the potential fixes outlined in this guide are widely confirmed to work by users who’ve needed to fix the “Check for PIN” error.

 So, maybe one might also get that error sorted on your PC, enabling you to pair and utilize your Bluetooth device again.

 The “Check the PIN” error means users can’t connect affected Bluetooth devices with their PCs. It is more widely reported to affect Bluetooth keyboards and headphones. You can fix the same issue on your PC with the potential “Check the PIN” fixes below.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-clips.techidaily.com/new-overcoming-video-limitations-on-instagram-platform-for-2024/"><u>[New] Overcoming Video Limitations on Instagram Platform for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-perfect-your-gaming-capture-console-gameplay-on-a-computer/"><u>[Updated] 2024 Approved Perfect Your Gaming Capture Console Gameplay on a Computer</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-fb-profile-picture-dimensions/"><u>[Updated] In 2024, FB Profile Picture Dimensions</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-google-play-location-on-htc-u23-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Google Play Location On HTC U23 | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-delete-icloud-account-from-iphone-13-without-password-by-drfone-ios/"><u>In 2024, How to Delete iCloud Account From iPhone 13 without Password?</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-k850-ultrahd-samsung-2023-tech-review/"><u>In 2024, K850 UltraHD Samsung 2023 Tech Review</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-x-studio-audio-pc-app/"><u>In 2024, X-Studio Audio PC App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-salvation-from-script-setbacks-in-windows-os/"><u>Swift Salvation From Script Setbacks in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essence-and-function-of-wu-and-orchestrator-services/"><u>The Essence and Function of WU & Orchestrator Services</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/the-ultimate-guide-to-non-vimeo-editing-software/"><u>The Ultimate Guide to Non-Vimeo Editing Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tomorrows-tech-landscape-windows-plus-artificial-intelligence/"><u>Tomorrow's Tech Landscape: Windows + Artificial Intelligence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-audio-issues-automatic-startup-fixes-for-wake/"><u>Troubleshooting Audio Issues: Automatic Startup Fixes for Wake</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unbeatable-free-livestream-solutions-reviewed-across-all-platforms-for-2024/"><u>Unbeatable Free Livestream Solutions Reviewed Across All Platforms for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-windows-11-power-through-service-configuration/"><u>Unlock Windows 11 Power Through Service Configuration</u></a></li>
</ul></div>

