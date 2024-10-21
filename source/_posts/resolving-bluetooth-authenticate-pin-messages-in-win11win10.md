---
title: Resolving Bluetooth Authenticate Pin Messages in Win11/Win10
date: 2024-10-17T21:19:35.684Z
updated: 2024-10-20T22:16:24.319Z
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
<a href="https://appsumo.8odi.net/c/5597632/2082527/7443" target="_top" id="2082527">
  <img src="//a.impactradius-go.com/display-ad/7443-2082527" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082527/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Add a device wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-add-a-device-wizard.jpg)
6. Click **Next** to proceed with Bluetooth device pairing.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535">
  <img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<span id="1834906">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1834906.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16836-1834906">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1834906.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2F25home.pxf.io%2Fc%2F5597632%2F1834906%2F16836'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1834906/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Update the Bluetooth Driver on Your PC

 Another possibility is that an old or faulty Bluetooth driver on your PC is causing the “Check the PIN” error. So, try updating your PC’s Bluetooth driver to see if that makes any difference. You can do that with the methods covered in this [guide to finding and replacing outdated drivers](https://www.makeuseof.com/tag/find-replace-outdated-windows-drivers/).

 The most straightforward way to apply this resolution is to utilize a driver updater utility, such as Driver Booster 8\. That will show if the Bluetooth driver on your PC is outdated and provide you with an option to download and install a new one. We recommend utilizing one of the software packages from the [best free driver updaters for Windows](https://www.makeuseof.com/windows-best-free-driver-updaters/).

![The Driver Booster software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/driver-booster-software.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130887/7443" target="_top" id="2130887">
  <img src="//a.impactradius-go.com/display-ad/7443-2130887" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130887/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Utilize Your Bluetooth Peripheral With Windows PC

 There aren’t lots of confirmed potential fixes for the “Check the PIN” error. However, the potential fixes outlined in this guide are widely confirmed to work by users who’ve needed to fix the “Check for PIN” error.

 So, maybe one might also get that error sorted on your PC, enabling you to pair and utilize your Bluetooth device again.

 The “Check the PIN” error means users can’t connect affected Bluetooth devices with their PCs. It is more widely reported to affect Bluetooth keyboards and headphones. You can fix the same issue on your PC with the potential “Check the PIN” fixes below.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-approaches.techidaily.com/new-understanding-av1-a-first-step-for-beginners/"><u>[New] Understanding AV1 A First Step for Beginners</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-capture-and-store-videos-effortlessly-with-our-top-list/"><u>[Updated] 2024 Approved Capture & Store Videos Effortlessly with Our Top List</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-capturing-awe-the-power-of-creative-distortion-in-photoshop/"><u>[Updated] Capturing Awe The Power of Creative Distortion in Photoshop</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-mastering-facebook-profile-pictures-with-these-expert-creators/"><u>[Updated] Mastering Facebook Profile Pictures with These Expert Creators</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-secrets-revealed-effective-facebook-video-publishing-techniques/"><u>[Updated] Secrets Revealed Effective Facebook Video Publishing Techniques</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-video-showdown-determining-the-best-among-obs-and-twitch-hubs/"><u>2024 Approved Video Showdown Determining the Best Among OBS and Twitch Hubs</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/best-photo-slideshow-maker-how-to-make-a-photo-slideshow-for-2024/"><u>Best Photo Slideshow Maker How to Make a Photo Slideshow for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-decades-old-password-in-windows-error/"><u>Deciphering Decades-Old Password in Windows Error</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-interpreting-laws-around-youtube-content-capture/"><u>In 2024, Interpreting Laws Around YouTube Content Capture</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-your-system-up-to-date-for-windows-11-installation/"><u>Is Your System up to Date for Windows 11 Installation?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-steam-disconnect-issues/"><u>Overcoming Windows Steam Disconnect Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-windows-uac-dynamics-from-an-admins-perspective/"><u>Transforming Windows UAC Dynamics From an Admin's Perspective</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-five-data-usage-practices-in-win11/"><u>Understanding Five Data Usage Practices in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-error-xc0f1103f-in-geforce-experience-win-1011/"><u>Unraveling Error XC0F1103F in GeForce Experience Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-win-friendly-secure-software-archives/"><u>Unveiling Win-Friendly, Secure Software Archives</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    