---
title: Resolving Bluetooth Authenticate Pin Messages in Win11/Win10
date: 2024-10-24T23:53:03.599Z
updated: 2024-10-26T18:11:38.045Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Bluetooth Authenticate Pin Messages in Win11/Win10
excerpt: This Article Describes Resolving Bluetooth Authenticate Pin Messages in Win11/Win10
keywords: Win11 Bluetooth Pin Fix,Win10 Authenticate Error,Bluetooth Connect Issue,Bluetooth PIN Resolve,Windows Pin Authentication,Win11/Win10 PIN Troubleshoot,Bluetooth Error in W11/W10
thumbnail: https://thmb.techidaily.com/e8d273b848143c340000d0079f7c83e7faa1151d78bf679fca424eb3bb1ead67.jpg
---

## Resolving Bluetooth Authenticate Pin Messages in Win11/Win10

 The “Check the PIN” error occurs for some users when they try pairing Bluetooth devices with their Windows 11/10 PCs. When users try connecting peripherals via Settings, the Add a device window shows this message, “Check the PIN and try connecting again.” Users say that issue typically occurs when they try to re-pair devices after unpairing them.

 The “Check the PIN” error means users can’t connect affected Bluetooth devices with their PCs. It is more widely reported to affect Bluetooth keyboards and headphones. You can fix the same issue on your PC with the potential “Check the PIN” fixes below.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Run the Troubleshooter for Bluetooth

 Windows has a Bluetooth troubleshooter that can fix Bluetooth connectivity errors such as the “Check the PIN” Bluetooth error.

 You can find it listed among other troubleshooters within the Settings app. This [how-to-run Windows troubleshooters guide](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) includes instructions for opening troubleshooting tools via Settings.

![The Devices and Printers Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/add-a-device-option.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111968/7443" target="_top" id="2111968">
  <img src="//a.impactradius-go.com/display-ad/7443-2111968" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111968/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100541/7443" target="_top" id="2100541">
  <img src="//a.impactradius-go.com/display-ad/7443-2100541" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Add a device wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-add-a-device-wizard.jpg)
6. Click **Next** to proceed with Bluetooth device pairing.

7. If prompted to input a WPS PIN, input the required device code in the text box.
8. Select **Next** to pair the Bluetooth device.

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
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484">
  <img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Update the Bluetooth Driver on Your PC

 Another possibility is that an old or faulty Bluetooth driver on your PC is causing the “Check the PIN” error. So, try updating your PC’s Bluetooth driver to see if that makes any difference. You can do that with the methods covered in this [guide to finding and replacing outdated drivers](https://www.makeuseof.com/tag/find-replace-outdated-windows-drivers/).

 The most straightforward way to apply this resolution is to utilize a driver updater utility, such as Driver Booster 8\. That will show if the Bluetooth driver on your PC is outdated and provide you with an option to download and install a new one. We recommend utilizing one of the software packages from the [best free driver updaters for Windows](https://www.makeuseof.com/windows-best-free-driver-updaters/).

![The Driver Booster software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/driver-booster-software.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144299/7443" target="_top" id="2144299">
  <img src="//a.impactradius-go.com/display-ad/7443-2144299" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144299/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-noise-free-videography-utilizing-free-tools-or-purchasing/"><u>[New] In 2024, Noise-Free Videography Utilizing Free Tools or Purchasing</u></a></li>
<li><a href="https://youtube-data.techidaily.com/n-2024-unveiling-the-top-7-android-apps-to-banish-ads/"><u>[New] In 2024, Unveiling The Top 7 Android Apps to Banish Ads</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-understanding-vlcs-screen-recording-features-for-2024/"><u>[New] Understanding VLC's Screen Recording Features for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-through-windows-11-theme-barriers-using-registry/"><u>Breaking Through Windows 11 Theme Barriers Using Registry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-reasons-to-never-turn-off-your-windows-11-push-notifications/"><u>Discover Reasons to Never Turn Off Your Windows 11 Push Notifications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-file-sharing-capabilities-in-geforce/"><u>Enhancing File-Sharing Capabilities in GeForce</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-11-taskbar-responsiveness/"><u>Enhancing Windows 11 Taskbar Responsiveness</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ng-opportunities-where-youtube-collaborations-thrive-for-2024/"><u>Finding Opportunities Where YouTube Collaborations Thrive for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-free-tools-and-tricks-for-easy-person-removal-from-images-explore-movavi/"><u>Guide: Free Tools & Tricks for Easy Person Removal From Images - Explore Movavi</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-vpna-to-fake-gps-location-on-apple-iphone-14-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, Complete Tutorial to Use VPNa to Fake GPS Location On Apple iPhone 14 Pro | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-xiaomi-14-ultra-by-phone-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Xiaomi 14 Ultra by Phone Number | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/incorporating-external-disk-into-explorer-nav-pane/"><u>Incorporating External Disk Into Explorer Nav Pane</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/premier-streaming-platforms-reviewed-and-rated-for-2024/"><u>Premier Streaming Platforms Reviewed & Rated for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-file-denial-in-steam-for-windows-11-users/"><u>Tackling File Denial in Steam for Windows 11 Users</u></a></li>
</ul></div>

