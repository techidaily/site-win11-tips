---
title: Windows Setup Guide for Steam Deck Owners
date: 2024-08-16T01:55:36.292Z
updated: 2024-08-17T01:55:36.292Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Windows Setup Guide for Steam Deck Owners
excerpt: This Article Describes Windows Setup Guide for Steam Deck Owners
keywords: Steam Deck Setup Instructions,Windows Compatible with Steam Deck,Optimize Steam Deck Windows,Steam Deck Installation Guide,Boot Steam Deck on Windows,Configuring Steam Deck for PC,Streaming Deck Windows Setup
thumbnail: https://thmb.techidaily.com/38e4000e96c33206bb992b3f696967e164e1f69dc3c8232613dcea5c215cabc4.jpg
---

## Windows Setup Guide for Steam Deck Owners

### Quick Links

* [Why You Should Install Windows on Your Steam Deck](#why-you-should-install-windows-on-your-steam-deck)
* [What You Need to Install Windows on Your Steam Deck](#what-you-need-to-install-windows-on-your-steam-deck)
* [How to Install Windows on Your Steam Deck](#how-to-install-windows-on-your-steam-deck)
* [Potential Issues and Solutions While Installing Windows on Your Steam Deck](#potential-issues-and-solutions-while-installing-windows-on-your-steam-deck)

### Key Takeaways

* Installing Windows on your Steam Deck allows you to access a familiar operating system and use the device as a work laptop or desktop replacement.
* To install Windows on your Steam Deck, you need a USB flash drive or SD card, Ventoy software, a GParted ISO, and a Windows 11 ISO.
* Follow our step-by-step guide to install Ventoy, partition your SSD, install Windows 11, and then install Windows drivers for proper functionality on your Steam Deck.

 Do you want to have a familiar operating system or Game Pass on your Steam Deck? You can dual-boot SteamOS with Windows on the device. Here’s a thorough guide on installing Windows 11 on your Steam Deck.

## Why You Should Install Windows on Your Steam Deck
![Steam Deck surrounded by peripherals](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2024/01/steam-deck-surrounded-by-peripherals.JPG)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Jhet Borja/MUO

 If you’re someone who owns a PC, the chances are very high that you’re running Windows on it. Windows is familiar to many and is fairly easy to use.

 While not having a mouse and keyboard on your Steam Deck will pose some navigation issues, having an operating system that’s familiar to you and that you know how to use might be worth that sacrifice.

 Having Windows on your Steam Deck can also make it a work laptop or desktop replacement. You can easily use Photoshop, Microsoft Office apps, Lightroom, and all the usual suspects on Windows—so long as you’re willing to bring around a mouse and keyboard. Thankfully, there are plenty of [Steam Deck accessories](https://www.makeuseof.com/essential-steam-deck-accessories/) that can make doing real work on it a breeze.

<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
## What You Need to Install Windows on Your Steam Deck

 You only need a few things to install Windows on your Steam Deck, most of which are software. But you will need a few hardware accessories as well.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
### Hardware

 For hardware, you really only need a USB flash drive and a USB-C hub to plug it into your Steam Deck. You can also [install an SD card on your Steam Deck](https://www.makeuseof.com/how-to-install-steam-deck-sd-card/) as long as it's decently fast. A USB 3.0 or higher flash drive or a UHS-I or higher SD card would suffice, but we wouldn’t suggest anything slower.

 We also highly suggest using a separate PC as we've done in this guide, but you can also use your Steam Deck and follow similar steps using the Linux version of Ventoy.

### Ventoy

 The first piece of software is Ventoy, a program that allows you to boot multiple ISOs from one external storage device without needing to format it to add a different ISO. This will avoid the back-and-forth formatting of the storage device used, making it easier to go back in case you make a mistake along the way.

![Ventoy Windows zip file from GitHub](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/ventoy-windows-zip-file-from-github.jpg)

 Head to [Ventoy’s GitHub page](https://github.com/ventoy/Ventoy/) and on the right side, click on **Releases**. Scroll down to **Assets** and click on the ZIP folder that says Windows on it. Extract the contents into a folder on your PC.

### GNOME Partition Editor (GParted) ISO
![downloading GParted amd64 version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/downloading-gparted-amd64-version.jpg)

 GParted is an ISO used to create partitions on your internal SSD on your Steam Deck. The new partition will be where you’ll place the Windows installation. To download it, head to [GParted.org](https://gparted.org/download.php) and click on the **amd64.iso** download file.

### Windows 11 ISO

 To put Windows onto your Steam Deck, you’ll of course need the installer. You can easily find this on [Microsoft’s Windows 11 page](https://www.microsoft.com/en-ca/software-download/windows11).

![Downloading Windows 11 ISO from Microsoft](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/downloading-windows-11-iso-from-microsoft.jpg)
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Head to the **Download Windows 11 Disk Image (ISO)** option and on the dropdown menu, select **Windows 11 (multi-edition ISO)**. Click on **Download**, then select your language. It should then give you another download button to download the Windows ISO that is about 6GB to 7GB in size.

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Windows Drivers for Steam Deck
![Downloading Windows Drivers for Steam Deck](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/downloading-windows-drivers-for-steam-deck.jpg)
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

 Windows doesn’t support all the Steam Deck’s hardware straight from the get-go. Fortunately, Steam has provided Windows drivers so that your audio, Wi-Fi, Bluetooth, SD card reader, and APU are all working properly.

 You can find and download the Windows drivers for your Steam Deck on the [Steam Deck Windows Resources support page](https://help.steampowered.com/en/faqs/view/6121-ECCD-D643-BAA8). Extract all of them into a single folder so that you can paste it onto your SD card or flash drive later.

<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Install Windows on Your Steam Deck

 If you’ve got your flash drive or SD card ready with all the software downloaded, you can now start turning your Steam Deck into a Windows experience. In our case, we’ll be using an SD card so that we don’t need to deal with a USB hub or a dock.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Install Ventoy on Your Flash Drive or SD Card

 To be able to run both the GParted and the Windows 11 ISOs from one SD card without needing to format it multiple times, you’ll need to use Ventoy. This will make things way more convenient.

![Run Ventoy2Disk from extracted folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/run-ventoy2disk-from-extracted-folder.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->

 To install Ventoy on your flash drive or SD card, you’ll want to plug it into your PC and open the Ventoy folder you extracted earlier. Then click on **Ventoy2Disk.exe**.

![Selected SD card to install Ventoy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/selected-sd-card-to-install-ventoy.jpg)
<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You’ll then select the storage device you want to store Ventoy on. In our case, it’s the 32GB SD card. Click **Install**.

![Ventoy Drive with all ISOs and Windows Drivers inside](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/ventoy-drive-with-all-isos-and-windows-drivers-inside.jpg)

 Now that Ventoy is installed, copy over GParted, the Windows 11 ISO, and a folder containing the Windows drivers for the Steam Deck. You can now insert the SD card into the Steam Deck.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
### 2\. Enter the Steam Deck Boot Manager

 Next, you’ll need to boot from the SD card or flash drive you’ve connected to the Steam Deck using the device's boot manager.

![Volume down and power button to enter Steam Deck boot manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/volume-down-and-power-button-to-enter-steam-deck-boot-manager.JPG)
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->

Jhet Borja/MUO

 To do this, shut down your Steam Deck first. Once it’s off, hold down the volume down button and power button until you hear a chime. Once you hear the chime, let go of the power button, but keep holding down the volume down button until the boot manager shows, like in the image below.

![No SteamOS option in boot manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/no-steamos-option-in-boot-manager.JPG)
<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->

Jhet Borja/MUO

 If you hold down the power button after the chime, you’ll most likely end up turning your Steam Deck off again.

 Once you’re in the boot manager, select the SD card or flash drive. This should show Ventoy and both the Windows and GParted ISOs.

### 3\. Use GParted to Partition Your Internal SSD

 You'll now need to partition your Steam Deck's SSD. If you don't, you most likely won't be able to install Windows 11 on the /home partition, and you'll also end up wiping SteamOS from your drive.

 If you want just Windows on your Steam Deck, you can also use Ventoy to wipe all partitions and either leave the combined partition as unallocated or format it as NTFS. We don't suggest this, however, as SteamOS really is the best way to experience the Steam Deck. It's better to have the option to switch between the two than be stuck with just Windows.

![GParted ISO on Ventoy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/gparted-iso-on-ventoy.JPG)
<!-- affiliate ads begin -->
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Jhet Borja/MUO

 On Ventoy, select GParted to run it. You can run it in normal mode, but if that doesn’t work, grub2 might do it.

![Enter GParted Live first option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/enter-gparted-live-first-option.JPG)

Jhet Borja/MUO

 Once GParted is open, you’ll be greeted with a few things before you can get to partitioning. Firstly, you’ll need to select the settings. Pick the first one—**GParted Live (Default Settings)**.

![GParted Don't touch keymap option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/gparted-don-t-touch-keymap-option.JPG)

 Next, select **Don’t touch keymap** and then select your language. If you’re just going to use English, we suggest just pressing A on the Steam Deck until you reach the main screen.

![Selecting Steam Deck SSD in GParted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/selecting-steam-deck-ssd-in-gparted.JPG)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537546&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/7_copy_2_2_hdpro.png" border="0">HD Video Converter Factory Pro</a>
<!-- affiliate ads end -->

Jhet Borja/MUO

 Finally, you’re ready to partition your SSD. By this point, you can plug in your mouse and keyboard to make it easier to navigate. If your SD card or flash drive is the only thing you can see, switch it to your SSD on the upper right drop-down menu.

![Resizing home partition on Steam Deck SSD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/resizing-home-partition-on-steam-deck-ssd.JPG)

Jhet Borja/MUO

 To partition your SSD, right-click (left trigger) on the **/home** partition or the largest partition on the SSD. Click on **Resize/Move** and move the right wall to the left, leaving the empty space as a new unallocated partition.

 In our case, we’re leaving around 250 GB or about 250,000 MiB for Windows 11\. Click on the **Resize/Move** button on the bottom right to make your changes.

![Unallocated partition on GParted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/unallocated-partition-on-gparted.JPG)

Jhet Borja/MUO

 Finally, click on the **green check mark** in the toolbar. Forgetting to do this will not apply your partition changes.

 The software will then process the new partition sizes, which may take a few minutes depending on how big your SSD is. Once it’s done, you can now press the power button to exit GParted and power down.

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
### 4\. Windows 11 Setup on the Steam Deck

 Now you're ready to install Windows on your Steam Deck. Before you go to the boot manager though, unplug any other USB devices you used earlier except the flash drive. This prevents the ISOs or Ventoy from malfunctioning.

![Windows 11 ISO on Ventoy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-iso-on-ventoy.JPG)
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->

Jhet Borja/MUO

 Go back to the boot manager (with the volume down button and the power button) and select the SD card or flash drive once again. With Ventoy open, this time select the Windows 11 ISO.

![I don't have a product key option during Windows 11 setup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/i-don-t-have-a-product-key-windows-11-setup.JPG)

Jhet Borja/MUO

 Just follow the setup by choosing the right language and keyboard layout until you reach the Windows key section. There, you can safely choose **I don’t have a product key** if you don’t have one.

![Entering partition size Windows 11 setup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/entering-partition-size-windows-11-setup.JPG)

Jhet Borja/MUO

 Proceed until you reach the **Where do you want to install Windows?** screen. You’ll want to scroll to the very bottom and click the drive that says **Unallocated space**. Next, click **New,** and it’ll automatically add the right size for you. So just click **Apply**.

 It will then start installing Windows onto that partition. Once Windows 11 is installed, you’ll have to go through another setup process.

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 5\. Install the Windows Drivers for the Steam Deck

 Once you’ve installed Windows, you can now install the drivers for your Steam Deck.

![Windows Drivers from Steam](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-drivers-from-steam.png)

 To do this, open up your File Explorer and click on the Ventoy drive. Open the folder we told you to place the Steam Deck drivers inside and start with any one of them.

 If you’re prompted to restart, don’t do it yet. You can restart once you’ve installed all the drivers to make it easier.

![Installing Steam Deck audio driver part 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/installing-steam-deck-audio-driver-part-1.png)

 Proceed to click on **Install** for the other drivers, but you may find that the audio drivers do not have an executable. To install the two audio drivers, simply right-click (left trigger) on the file that says **Setup information** and click **Install**.

 Once they’re all installed, you can now restart your Steam Deck. If things didn’t go so smoothly, you can refer to the section below to find your issue and the solution for it.

## Potential Issues and Solutions While Installing Windows on Your Steam Deck

 We’ve compiled a few issues that we came across during our installation and found solutions to them so that you don’t have to scour the internet to find fixes.

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### ISOs Show a Black Screen or Don't Boot Up

 If the ISOs aren’t working properly, just press the power button once to exit and shut down. This is most likely due to other USB devices plugged into your Steam Deck like a keyboard and mouse. This is why we used an SD card in our installation. Remove all USB devices except your flash drive or use a USB-C flash drive if possible.

 If this doesn’t work, you may also try to delete the other ISO from the SD card or flash drive. You may also try reinstalling Ventoy as a last resort, but this will format the drive so make sure you have everything in a folder that you can easily paste onto the drive.

### The Windows 0x80300001 Error
![Selecting partition created in GParted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/selecting-partition-created-in-gparted.JPG)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->

Jhet Borja/MUO

 This error will most likely pop up because the partition you want to install Windows on isn’t in NTFS format or a blank unallocated partition.

![Wrong ext4 partition format for Windows on GParted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/wrong-ext4-partition-format-for-windows-on-gparted.JPG)

Jhet Borja/MUO

 You may have created a new partition as ext4 in GParted instead of leaving the unallocated partition as it is. If you insist on creating a new partition in GParted, make sure it’s in NTFS format and not ext4\.

### Windows Cannot Install Drivers
![Windows cannot install required files error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-cannot-install-required-files-error.JPG)

Jhet Borja/MUO

 If you’re near the end of your Windows installation and it suddenly says it cannot install drivers, other USB devices may be interfering with the installation.

 Shut down your Steam Deck by holding down the power button and unplug any USB devices except your flash drive or SD card. Don’t plug in any USB devices during the installation to avoid this issue.

### You Can’t Find SteamOS in the Boot Manager
![No SteamOS option in boot manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/no-steamos-option-in-boot-manager.JPG)
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->

Jhet Borja/MUO

 If you want to go back to SteamOS and can’t find it in the boot manager, you should shut down your Steam Deck and go to the BIOS instead.

 To enter the BIOS, hold down the volume up button and the power button until you hear the chime. Let go of the power button but hold down the volume up button until you enter the BIOS.

![Selecting steamcl.efi in Steam Deck BIOS to boot into SteamOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/selecting-steamcl-efi-in-steam-deck-bios-to-boot-into-steamos.JPG)

Jhet Borja/MakeUseOf

 Once you’re in the BIOS, select **Boot from file > eps > efi > steamos > steamcl.efi**. This should boot you back into SteamOS.

 Now that you’re in SteamOS, you can put it back onto the boot manager by entering desktop mode.

![Konsole command to make SteamOS appear in boot manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/konsole-command-to-make-steamos-appear-in-boot-manager-1.JPG)

 On desktop mode, click on the Steam Deck icon on the bottom left and open Konsole. You can search for it by bringing up the keyboard by clicking on the text box and pressing on the Steam button + X.

 Then type:

`sudo efibootmgr -c -L "SteamOS" -l "\EFI\steamos\steamcl.efi" -d /dev/nvme0n1p1`

![Steam Deck user password](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/steam-deck-user-password.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->

 In case you don’t have a sudo account and can’t add the command, go to **Settings > Users** then assign a username and password. You can then try adding the same command in Konsole and adding your password after pressing Enter. It will then show your boot options.

 If you can see steamcl.efi with an asterisk next to its boot order number, it means that it’s in your boot manager now. You can verify it by shutting your Steam Deck down and entering the boot manager.

### Steam Deck Navigation and Controls on Windows

 If you’re having a hard time with the Steam Deck controls on Windows and want to use the controls like on SteamOS, download Steam and have it open.

![Enabling Steam Input for Xbox Controllers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/enabling-steam-input-for-xbox-controllers.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then go to **Steam > Settings > Controller > Enable Steam Input for Xbox Controllers**. You should then be able to use both trackpads like on SteamOS. You may also configure it by scrolling down and editing it on the **Non-game controller layouts**.

 The Steam Deck is a very versatile device as it’s not just a full-on gaming device, but also a full-on PC. Installing Windows on it will allow you to use it similarly to your desktop PC for regular writing work, but also for more intensive work like video and photo editing.

 We hope this guide has helped you figure out how to install Windows on your Steam Deck and fix some of the issues you might face while doing so.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-freedom-from-popups-discover-the-top-7-android-adblock-apps/"><u>[New] 2024 Approved  Freedom From Popups? Discover the Top 7 Android AdBlock Apps</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-do-youtubers-get-paid-monthly-in-2024/"><u>[New] Do YouTubers Get Paid Monthly, In 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-navigating-through-the-best-screen-recorders-for-teaching/"><u>[New] Navigating Through the Best Screen Recorders for Teaching</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-perfecting-synchronized-recording-webcam-plus-display-techniques-for-2024/"><u>[New] Perfecting Synchronized Recording  Webcam + Display Techniques for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-to-turn-off-or-not-navigating-through-your-off-facebook-activities/"><u>[New] To Turn Off or Not  Navigating Through Your Off-Facebook Activities</u></a></li>
<li><a href="https://blog-min.techidaily.com/2-ways-to-transfer-text-messages-from-realme-12plus-5g-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>2 Ways to Transfer Text Messages from Realme 12+ 5G to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-detailed-manual-for-individualized-keybindings-in-win11/"><u>A Detailed Manual for Individualized Keybindings in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-steam-online-connectivity-failures-w11/"><u>Addressing Steam Online Connectivity Failures W11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/artistic-horizons-scouting-the-finest-8-drawing-apps-for-iphones/"><u>Artistic Horizons  Scouting the Finest 8 Drawing Apps for iPhones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-mouseclicklock-usability-on-windows-systems/"><u>Boosting MouseClickLock Usability on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convergence-of-ios-and-windows-using-apple-maps-effectively/"><u>Convergence of iOS and Windows: Using Apple Maps Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-hdd-invisibility-glitches/"><u>Correcting HDD Invisibility Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-a-personalized-windows-11-interface-with-enlarged-icons/"><u>Crafting a Personalized Windows 11 Interface with Enlarged Icons</u></a></li>
<li><a href="https://extra-resources.techidaily.com/crafting-memes-with-ease-on-9gag-platform/"><u>Crafting Memes with Ease on 9GAG Platform</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/discovering-virtual-mastery-kinemasters-android-journey/"><u>Discovering Virtual Mastery  KineMaster's Android Journey</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/easy-guide-to-xiaomi-civi-3-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Xiaomi Civi 3 FRP Bypass With Best Methods</u></a></li>
<li><a href="https://games-able.techidaily.com/eliminating-low-memory-alerts-while-using-roblox-in-ios/"><u>Eliminating Low-Memory Alerts While Using Roblox in iOS</u></a></li>
<li><a href="https://video-capture.techidaily.com/engaging-oratory-insights-part-8-for-2024/"><u>Engaging Oratory Insights Part 8 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-visual-display-top-5-ideal-windows-pc-clock-themed-screensavers/"><u>Enhance Visual Display: Top 5 Ideal Windows PC Clock-Themed Screensavers</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/enjoy-uninterrupted-youtube-with-effective-adblocking-methods-for-2024/"><u>Enjoy Uninterrupted YouTube with Effective Adblocking Methods for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-seamless-web-access-via-win-os/"><u>Ensuring Seamless Web Access via Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-smooth-operation-fixing-windows-notepad-crashes/"><u>Ensuring Smooth Operation: Fixing Windows Notepad Crashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-value-not-available-issue-in-windows/"><u>Eradicating Value Not Available Issue in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/executing-customized-policies-to-a-singular-account-in-win-1011/"><u>Executing Customized Policies to a Singular Account in Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-windows-memory-landscape-identify-ram-straightforwardly/"><u>Exploring Windows Memory Landscape: Identify RAM Straightforwardly</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/get-liked-faster-on-tinder-clever-bio-tricks-that-work-for-2024/"><u>Get Liked Faster on Tinder  Clever Bio Tricks That Work for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/guide-to-tape-twitch-streams-effectively-for-2024/"><u>Guide to Tape Twitch Streams Effectively for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hidden-treasures-found-the-guide-to-recover-lost-features-in-windows-11/"><u>Hidden Treasures Found: The Guide to Recover Lost Features in Window’s 11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-google-frp-on-oneplus-nord-ce-3-lite-5g-by-drfone-android-unlock-remove-google-frp/"><u>How To Bypass Google FRP on OnePlus Nord CE 3 Lite 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-product-activation-failed-error-on-microsoft-office-apps-for-windows/"><u>How to Fix the Product Activation Failed Error on Microsoft Office Apps for Windows</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-diminishing-excessive-encoding-obs/"><u>In 2024, Diminishing Excessive Encoding (OBS)</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-realme-note-50-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Realme Note 50 to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://buynow-help.techidaily.com/in-depth-assessment-of-the-amplifi-hd-wireless-networking-solution-defeat-wi-fi-weak-spots-with-ease/"><u>In-Depth Assessment of the Amplifi HD Wireless Networking Solution: Defeat Wi-Fi Weak Spots with Ease!</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-vocalizing-text-pioneering-audio-to-written-content-conversion/"><u>New In 2024, Vocalizing Text Pioneering Audio to Written Content Conversion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-unlocking-windows-11/"><u>Quick Guide: Unlocking Windows 11</u></a></li>
<li><a href="https://apple-account.techidaily.com/removing-device-from-apple-id-for-your-apple-iphone-x-by-drfone-ios/"><u>Removing Device From Apple ID For your Apple iPhone X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrecting-a-non-responsive-mouse-on-windows-computers/"><u>Resurrecting a Non-Responsive Mouse on Windows Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-implementation-of-updater-in-win11-version-22h2/"><u>Seamless Implementation of Updater in WIN11 Version 22H2</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/securely-delete-files-with-the-top-rated-bitraser-drive-eraser-buy-now/"><u>Securely Delete Files with the Top-Rated BitRaser Drive Eraser – Buy Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-a-new-surname-username-alteration-in-windows-11/"><u>Securing a New Surname: UserName Alteration in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-non-working-activation-codes-in-win11/"><u>Solutions for Non-Working Activation Codes in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-enabling-task-managers-quick-find-feature-on-win11/"><u>Step-by-Step Guide: Enabling Task Manager's Quick Find Feature on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solution-regain-shared-resources-access/"><u>Swift Solution: Regain Shared Resources Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-mechanism-behind-windows-sound-graph-isolation/"><u>The Mechanism Behind Windows Sound Graph Isolation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-controlling-sounds-on-windows-11/"><u>The Ultimate Guide to Controlling Sounds on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uninstalling-microsoft-edge-from-windows-11/"><u>Uninstalling Microsoft Edge From Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-flawless-gameplay-combat-apex-legends-freezes/"><u>Unleash Flawless Gameplay: Combat Apex Legends Freezes</u></a></li>
</ul></div>
