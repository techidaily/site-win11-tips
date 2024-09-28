---
title: Strategies to Solve W11/W10 Bluetooth PIN Verification Failures
date: 2024-08-08T11:11:05.837Z
updated: 2024-08-09T11:11:05.837Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategies to Solve W11/W10 Bluetooth PIN Verification Failures
excerpt: This Article Describes Strategies to Solve W11/W10 Bluetooth PIN Verification Failures
keywords: BtPIN_Solution,WiFi11_Fix,WiFi10_Recovery,BlutoothVerify,PIN_Failure_Strategy,Bluetooth_SecurityCheck,Wireless_ErrorResolution
thumbnail: https://thmb.techidaily.com/c4f624b3f2bccad5b6da118fee2e7df55a3a172015085fad0a0d2520bcd157aa.jpg
---

## Strategies to Solve W11/W10 Bluetooth PIN Verification Failures

 The “Check the PIN” error occurs for some users when they try pairing Bluetooth devices with their Windows 11/10 PCs. When users try connecting peripherals via Settings, the Add a device window shows this message, “Check the PIN and try connecting again.” Users say that issue typically occurs when they try to re-pair devices after unpairing them.

 The “Check the PIN” error means users can’t connect affected Bluetooth devices with their PCs. It is more widely reported to affect Bluetooth keyboards and headphones. You can fix the same issue on your PC with the potential “Check the PIN” fixes below.

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Run the Troubleshooter for Bluetooth

 Windows has a Bluetooth troubleshooter that can fix Bluetooth connectivity errors such as the “Check the PIN” Bluetooth error.

 You can find it listed among other troubleshooters within the Settings app. This [how-to-run Windows troubleshooters guide](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) includes instructions for opening troubleshooting tools via Settings.

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
![The Add a device wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-add-a-device-wizard.jpg)
6. Click **Next** to proceed with Bluetooth device pairing.
7. If prompted to input a WPS PIN, input the required device code in the text box.
8. Select **Next** to pair the Bluetooth device.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
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
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
![The Delete registry key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-delete-registry-key-option.jpg)
6. Click **Yes** when prompted to confirm the deletion.  
![The Yes confirmation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-yes-option.jpg)

## 4\. Update the Bluetooth Driver on Your PC

 Another possibility is that an old or faulty Bluetooth driver on your PC is causing the “Check the PIN” error. So, try updating your PC’s Bluetooth driver to see if that makes any difference. You can do that with the methods covered in this [guide to finding and replacing outdated drivers](https://www.makeuseof.com/tag/find-replace-outdated-windows-drivers/).

 The most straightforward way to apply this resolution is to utilize a driver updater utility, such as Driver Booster 8\. That will show if the Bluetooth driver on your PC is outdated and provide you with an option to download and install a new one. We recommend utilizing one of the software packages from the [best free driver updaters for Windows](https://www.makeuseof.com/windows-best-free-driver-updaters/).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
![The Driver Booster software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/driver-booster-software.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
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