---
title: Installing Official Windows OS on Steam Deck
date: 2024-08-16T02:48:17.256Z
updated: 2024-08-17T02:48:17.256Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Installing Official Windows OS on Steam Deck
excerpt: This Article Describes Installing Official Windows OS on Steam Deck
keywords: Steam Deck OS Install,Windows OS for Steam Deck,Official Windows Steam Purchase,Steam Deck Windows Update,Steam Deck Microsoft OS,Buy Windows on Steam Deck,Steam Deck Compatible Windows
thumbnail: https://thmb.techidaily.com/18b7f2a3affa298abd49de738912f69fd84b1ae730be3c4356f4b4963bc95eed.jpg
---

## Installing Official Windows OS on Steam Deck

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

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
## Why You Should Install Windows on Your Steam Deck

![Steam Deck surrounded by peripherals](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2024/01/steam-deck-surrounded-by-peripherals.JPG)

Jhet Borja/MUO

 If you’re someone who owns a PC, the chances are very high that you’re running Windows on it. Windows is familiar to many and is fairly easy to use.

 While not having a mouse and keyboard on your Steam Deck will pose some navigation issues, having an operating system that’s familiar to you and that you know how to use might be worth that sacrifice.

 Having Windows on your Steam Deck can also make it a work laptop or desktop replacement. You can easily use Photoshop, Microsoft Office apps, Lightroom, and all the usual suspects on Windows—so long as you’re willing to bring around a mouse and keyboard. Thankfully, there are plenty of [Steam Deck accessories](https://www.makeuseof.com/essential-steam-deck-accessories/) that can make doing real work on it a breeze.

## What You Need to Install Windows on Your Steam Deck

 You only need a few things to install Windows on your Steam Deck, most of which are software. But you will need a few hardware accessories as well.

### Hardware

 For hardware, you really only need a USB flash drive and a USB-C hub to plug it into your Steam Deck. You can also [install an SD card on your Steam Deck](https://www.makeuseof.com/how-to-install-steam-deck-sd-card/) as long as it's decently fast. A USB 3.0 or higher flash drive or a UHS-I or higher SD card would suffice, but we wouldn’t suggest anything slower.

 We also highly suggest using a separate PC as we've done in this guide, but you can also use your Steam Deck and follow similar steps using the Linux version of Ventoy.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Ventoy

 The first piece of software is Ventoy, a program that allows you to boot multiple ISOs from one external storage device without needing to format it to add a different ISO. This will avoid the back-and-forth formatting of the storage device used, making it easier to go back in case you make a mistake along the way.

![Ventoy Windows zip file from GitHub](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/ventoy-windows-zip-file-from-github.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537546&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/7_copy_2_2_hdpro.png" border="0">HD Video Converter Factory Pro</a>
<!-- affiliate ads end -->

 Head to [Ventoy’s GitHub page](https://github.com/ventoy/Ventoy/) and on the right side, click on **Releases**. Scroll down to **Assets** and click on the ZIP folder that says Windows on it. Extract the contents into a folder on your PC.

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### GNOME Partition Editor (GParted) ISO

![downloading GParted amd64 version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/downloading-gparted-amd64-version.jpg)

 GParted is an ISO used to create partitions on your internal SSD on your Steam Deck. The new partition will be where you’ll place the Windows installation. To download it, head to [GParted.org](https://gparted.org/download.php) and click on the **amd64.iso** download file.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Windows 11 ISO

 To put Windows onto your Steam Deck, you’ll of course need the installer. You can easily find this on [Microsoft’s Windows 11 page](https://www.microsoft.com/en-ca/software-download/windows11).

![Downloading Windows 11 ISO from Microsoft](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/downloading-windows-11-iso-from-microsoft.jpg)
<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Head to the **Download Windows 11 Disk Image (ISO)** option and on the dropdown menu, select **Windows 11 (multi-edition ISO)**. Click on **Download**, then select your language. It should then give you another download button to download the Windows ISO that is about 6GB to 7GB in size.

### Windows Drivers for Steam Deck

![Downloading Windows Drivers for Steam Deck](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/downloading-windows-drivers-for-steam-deck.jpg)
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Windows doesn’t support all the Steam Deck’s hardware straight from the get-go. Fortunately, Steam has provided Windows drivers so that your audio, Wi-Fi, Bluetooth, SD card reader, and APU are all working properly.

 You can find and download the Windows drivers for your Steam Deck on the [Steam Deck Windows Resources support page](https://help.steampowered.com/en/faqs/view/6121-ECCD-D643-BAA8). Extract all of them into a single folder so that you can paste it onto your SD card or flash drive later.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Install Windows on Your Steam Deck

 If you’ve got your flash drive or SD card ready with all the software downloaded, you can now start turning your Steam Deck into a Windows experience. In our case, we’ll be using an SD card so that we don’t need to deal with a USB hub or a dock.

### 1\. Install Ventoy on Your Flash Drive or SD Card

 To be able to run both the GParted and the Windows 11 ISOs from one SD card without needing to format it multiple times, you’ll need to use Ventoy. This will make things way more convenient.

![Run Ventoy2Disk from extracted folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/run-ventoy2disk-from-extracted-folder.jpg)

 To install Ventoy on your flash drive or SD card, you’ll want to plug it into your PC and open the Ventoy folder you extracted earlier. Then click on **Ventoy2Disk.exe**.

![Selected SD card to install Ventoy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/selected-sd-card-to-install-ventoy.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->

 You’ll then select the storage device you want to store Ventoy on. In our case, it’s the 32GB SD card. Click **Install**.

![Ventoy Drive with all ISOs and Windows Drivers inside](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/ventoy-drive-with-all-isos-and-windows-drivers-inside.jpg)
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->

 Now that Ventoy is installed, copy over GParted, the Windows 11 ISO, and a folder containing the Windows drivers for the Steam Deck. You can now insert the SD card into the Steam Deck.

<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
### 2\. Enter the Steam Deck Boot Manager

 Next, you’ll need to boot from the SD card or flash drive you’ve connected to the Steam Deck using the device's boot manager.

![Volume down and power button to enter Steam Deck boot manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/volume-down-and-power-button-to-enter-steam-deck-boot-manager.JPG)
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Jhet Borja/MUO

 To do this, shut down your Steam Deck first. Once it’s off, hold down the volume down button and power button until you hear a chime. Once you hear the chime, let go of the power button, but keep holding down the volume down button until the boot manager shows, like in the image below.

![No SteamOS option in boot manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/no-steamos-option-in-boot-manager.JPG)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Jhet Borja/MUO

 If you hold down the power button after the chime, you’ll most likely end up turning your Steam Deck off again.

 Once you’re in the boot manager, select the SD card or flash drive. This should show Ventoy and both the Windows and GParted ISOs.

### 3\. Use GParted to Partition Your Internal SSD

 You'll now need to partition your Steam Deck's SSD. If you don't, you most likely won't be able to install Windows 11 on the /home partition, and you'll also end up wiping SteamOS from your drive.

 If you want just Windows on your Steam Deck, you can also use Ventoy to wipe all partitions and either leave the combined partition as unallocated or format it as NTFS. We don't suggest this, however, as SteamOS really is the best way to experience the Steam Deck. It's better to have the option to switch between the two than be stuck with just Windows.

![GParted ISO on Ventoy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/gparted-iso-on-ventoy.JPG)
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Jhet Borja/MUO

 Finally, you’re ready to partition your SSD. By this point, you can plug in your mouse and keyboard to make it easier to navigate. If your SD card or flash drive is the only thing you can see, switch it to your SSD on the upper right drop-down menu.

![Resizing home partition on Steam Deck SSD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/resizing-home-partition-on-steam-deck-ssd.JPG)

Jhet Borja/MUO

 To partition your SSD, right-click (left trigger) on the **/home** partition or the largest partition on the SSD. Click on **Resize/Move** and move the right wall to the left, leaving the empty space as a new unallocated partition.

 In our case, we’re leaving around 250 GB or about 250,000 MiB for Windows 11\. Click on the **Resize/Move** button on the bottom right to make your changes.

![Unallocated partition on GParted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/unallocated-partition-on-gparted.JPG)
<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Jhet Borja/MUO

 Finally, click on the **green check mark** in the toolbar. Forgetting to do this will not apply your partition changes.

 The software will then process the new partition sizes, which may take a few minutes depending on how big your SSD is. Once it’s done, you can now press the power button to exit GParted and power down.

### 4\. Windows 11 Setup on the Steam Deck

 Now you're ready to install Windows on your Steam Deck. Before you go to the boot manager though, unplug any other USB devices you used earlier except the flash drive. This prevents the ISOs or Ventoy from malfunctioning.

![Windows 11 ISO on Ventoy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-iso-on-ventoy.JPG)

Jhet Borja/MUO

 Go back to the boot manager (with the volume down button and the power button) and select the SD card or flash drive once again. With Ventoy open, this time select the Windows 11 ISO.

![I don't have a product key option during Windows 11 setup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/i-don-t-have-a-product-key-windows-11-setup.JPG)
<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->

Jhet Borja/MUO

 Just follow the setup by choosing the right language and keyboard layout until you reach the Windows key section. There, you can safely choose **I don’t have a product key** if you don’t have one.

![Entering partition size Windows 11 setup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/entering-partition-size-windows-11-setup.JPG)
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Jhet Borja/MUO

 Proceed until you reach the **Where do you want to install Windows?** screen. You’ll want to scroll to the very bottom and click the drive that says **Unallocated space**. Next, click **New,** and it’ll automatically add the right size for you. So just click **Apply**.

 It will then start installing Windows onto that partition. Once Windows 11 is installed, you’ll have to go through another setup process.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
### 5\. Install the Windows Drivers for the Steam Deck

 Once you’ve installed Windows, you can now install the drivers for your Steam Deck.

![Windows Drivers from Steam](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-drivers-from-steam.png)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To do this, open up your File Explorer and click on the Ventoy drive. Open the folder we told you to place the Steam Deck drivers inside and start with any one of them.

 If you’re prompted to restart, don’t do it yet. You can restart once you’ve installed all the drivers to make it easier.

![Installing Steam Deck audio driver part 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/installing-steam-deck-audio-driver-part-1.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->

 Proceed to click on **Install** for the other drivers, but you may find that the audio drivers do not have an executable. To install the two audio drivers, simply right-click (left trigger) on the file that says **Setup information** and click **Install**.

 Once they’re all installed, you can now restart your Steam Deck. If things didn’t go so smoothly, you can refer to the section below to find your issue and the solution for it.

## Potential Issues and Solutions While Installing Windows on Your Steam Deck

 We’ve compiled a few issues that we came across during our installation and found solutions to them so that you don’t have to scour the internet to find fixes.

### ISOs Show a Black Screen or Don't Boot Up

 If the ISOs aren’t working properly, just press the power button once to exit and shut down. This is most likely due to other USB devices plugged into your Steam Deck like a keyboard and mouse. This is why we used an SD card in our installation. Remove all USB devices except your flash drive or use a USB-C flash drive if possible.

 If this doesn’t work, you may also try to delete the other ISO from the SD card or flash drive. You may also try reinstalling Ventoy as a last resort, but this will format the drive so make sure you have everything in a folder that you can easily paste onto the drive.

### The Windows 0x80300001 Error

![Selecting partition created in GParted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/selecting-partition-created-in-gparted.JPG)

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

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
### You Can’t Find SteamOS in the Boot Manager

![No SteamOS option in boot manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/no-steamos-option-in-boot-manager.JPG)

Jhet Borja/MUO

 If you want to go back to SteamOS and can’t find it in the boot manager, you should shut down your Steam Deck and go to the BIOS instead.

 To enter the BIOS, hold down the volume up button and the power button until you hear the chime. Let go of the power button but hold down the volume up button until you enter the BIOS.

![Selecting steamcl.efi in Steam Deck BIOS to boot into SteamOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/selecting-steamcl-efi-in-steam-deck-bios-to-boot-into-steamos.JPG)

Jhet Borja/MakeUseOf

 Once you’re in the BIOS, select **Boot from file > eps > efi > steamos > steamcl.efi**. This should boot you back into SteamOS.

 Now that you’re in SteamOS, you can put it back onto the boot manager by entering desktop mode.

![Konsole command to make SteamOS appear in boot manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/konsole-command-to-make-steamos-appear-in-boot-manager-1.JPG)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->

 On desktop mode, click on the Steam Deck icon on the bottom left and open Konsole. You can search for it by bringing up the keyboard by clicking on the text box and pressing on the Steam button + X.

 Then type:

`sudo efibootmgr -c -L "SteamOS" -l "\EFI\steamos\steamcl.efi" -d /dev/nvme0n1p1`

![Steam Deck user password](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/steam-deck-user-password.jpg)

 In case you don’t have a sudo account and can’t add the command, go to **Settings > Users** then assign a username and password. You can then try adding the same command in Konsole and adding your password after pressing Enter. It will then show your boot options.

 If you can see steamcl.efi with an asterisk next to its boot order number, it means that it’s in your boot manager now. You can verify it by shutting your Steam Deck down and entering the boot manager.

### Steam Deck Navigation and Controls on Windows

 If you’re having a hard time with the Steam Deck controls on Windows and want to use the controls like on SteamOS, download Steam and have it open.

![Enabling Steam Input for Xbox Controllers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/enabling-steam-input-for-xbox-controllers.jpg)

 Then go to **Steam > Settings > Controller > Enable Steam Input for Xbox Controllers**. You should then be able to use both trackpads like on SteamOS. You may also configure it by scrolling down and editing it on the **Non-game controller layouts**.

 The Steam Deck is a very versatile device as it’s not just a full-on gaming device, but also a full-on PC. Installing Windows on it will allow you to use it similarly to your desktop PC for regular writing work, but also for more intensive work like video and photo editing.

 We hope this guide has helped you figure out how to install Windows on your Steam Deck and fix some of the issues you might face while doing so.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://remote-screen-capture.techidaily.com/new-discover-the-best-9-mobile-video-conferencing-apps-androidiphone/"><u>[New] Discover The Best 9 Mobile Video Conferencing Apps (Android/iPhone)</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-mastering-mic-levels-on-a-mac/"><u>[New] Mastering Mic Levels on a Mac</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-time-stretching-through-lenses-a-detailed-slomo-analysis-2024/"><u>[New] Time Stretching Through Lenses  A Detailed SloMo Analysis, 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-ultimate-wild-top-10-unforgettable-tiktok-challenges/"><u>[New] Ultimate Wild  Top 10 Unforgettable TikTok Challenges</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-11-easy-to-produce-vlog-projects-at-home/"><u>[Updated] 11 Easy-to-Produce Vlog Projects at Home</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-craft-viral-instagram-moments-by-incorporating-tiktok-wisdom/"><u>[Updated] 2024 Approved  Craft Viral Instagram Moments by Incorporating TikTok Wisdom</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-detailed-synopsis-googles-podcast-platform-explored-for-2024/"><u>[Updated] Detailed Synopsis  Google's Podcast Platform Explored for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-rescuing-muted-voices-during-obs-sessions/"><u>[Updated] In 2024, Rescuing Muted Voices During OBS Sessions</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-navigating-facebooks-high-def-download-routes/"><u>[Updated] Navigating Facebook's High-Def Download Routes</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-10-premier-online-church-service-providers/"><u>[Updated] The 10 Premier Online Church Service Providers</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-quickcapture-vs-recordify-comparative-recorder-analysis-2023/"><u>2024 Approved  'QuickCapture' Vs 'Recordify'  Comparative Recorder Analysis 2023</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-capture-crop-and-color-correct-with-this-lists-top-5-android-apps/"><u>2024 Approved  Capture, Crop, and Color-Correct with This List's Top 5 Android Apps</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-discovering-the-tech-marvel-in-apples-m1-max-clip/"><u>2024 Approved  Discovering the Tech Marvel in Apple's M1 Max Clip</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-distraction-free-deliberations-perfecting-backdrop-blur-on-mobile-devices/"><u>2024 Approved  Distraction-Free Deliberations  Perfecting Backdrop Blur on Mobile Devices</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-step-into-the-metaverse-analyzing-6-engrossing-cases/"><u>2024 Approved  Step Into the Metaverse  Analyzing 6 Engrossing Cases</u></a></li>
<li><a href="https://extra-hints.techidaily.com/a-canvas-of-colors-advanced-theory-and-use-for-2024/"><u>A Canvas of Colors  Advanced Theory & Use for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-windows-11-hotspot-performance-post-restart/"><u>Boosting Windows 11 Hotspot Performance Post-Restart</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-boundaries-innovations-for-windows-11-widget-design/"><u>Breaking Boundaries: Innovations for Windows 11 Widget Design</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-chains-of-stuck-downloads-on-windows-11-pcs/"><u>Breaking the Chains of Stuck Downloads on Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-code-how-long-can-your-password-be/"><u>Breaking the Code: How Long Can Your Password Be?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-freeze-on-dormant-windows-batch-file-functionality/"><u>Breaking the Freeze on Dormant Windows Batch File Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-through-the-barrier-of-ms-store-access/"><u>Breaking Through the Barrier of MS Store Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breath-of-fresh-windows-11-air-for-archaic-machines-via-to-go-and-rufus/"><u>Breath of Fresh Windows 11 Air for Archaic Machines via To Go & Rufus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathe-life-into-your-old-videos-using-madvr-in-the-windows-sphere/"><u>Breathe Life Into Your Old Videos: Using MadVR in the Windows Sphere</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-the-gap-between-internet-access-methods-a-guide-to-dual-connectivity-on-windows/"><u>Bridging the Gap Between Internet Access Methods: A Guide to Dual Connectivity on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-the-gap-fixing-win11-ccleaner-problems/"><u>Bridging the Gap: Fixing Win11 CCleaner Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-the-hourglass-fixes-for-missing-windows-server-time/"><u>Bring Back the Hourglass: Fixes for Missing Windows Server Time</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-windows-update-service-quickly/"><u>Bring Back Windows Update Service Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-back-missing-apps-windows-11s-window-reunification-methods/"><u>Bringing Back Missing Apps: Windows 11'S Window Reunification Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-down-your-pc-with-grace/"><u>Bringing Down Your PC with Grace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/browser-barriers-overcome-top-strategies-for-website-access-in-win-os/"><u>Browser Barriers Overcome: Top Strategies for Website Access in Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/budgeting-without-breaking-the-bank-on-windows-11/"><u>Budgeting Without Breaking the Bank on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/building-sfx-archives-a-windows-11-guide-for-beginners/"><u>Building SFX Archives: A Windows 11 Guide for Beginners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-error-successful-install-of-ms-pc-manager/"><u>Bypass Error: Successful Install of MS PC Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-pin-for-smooth-projections-on-windows-11/"><u>Bypass PIN for Smooth Projections on WIndows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-restricted-access-on-your-winsec-pc/"><u>Bypassing 'Restricted Access' On Your WinSec PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-controlled-windows-settings-by-administrators/"><u>Bypassing Controlled Windows Settings by Administrators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-the-sign-out-barrier-fixing-software-conflict-on-windows/"><u>Bypassing the Sign-Out Barrier: Fixing Software Conflict on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-updates-failure-0x800f0845/"><u>Bypassing Updates Failure: 0X800F0845</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-tricky-email-mishap-defeating-error-code-0x800713f/"><u>Bypassing Windows' Tricky Email Mishap: Defeating Error Code 0X800713F</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cable-free-controller-configuration-windows-plus-playstation-3/"><u>Cable-Free Controller Configuration: Windows + PlayStation 3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/can-your-pc-run-windows-11-check-these-system-requirements/"><u>Can Your PC Run Windows 11? Check These System Requirements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cant-set-an-account-as-administrator-on-windows-heres-the-fix/"><u>Can't Set an Account as Administrator on Windows? Here's the Fix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cease-chromes-automatic-new-tab-generations-on-windows/"><u>Cease Chrome's Automatic New Tab Generations on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cease-defender-firewall-protection-on-windows-11/"><u>Cease Defender Firewall Protection on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cease-unintentional-restarts-windows-11-guide/"><u>Cease Unintentional Restarts: Windows 11 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cease-windows-11-user-monitoring-a-guide/"><u>Cease Windows 11 User Monitoring: A Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/choosing-restful-states-on-your-windows-pc/"><u>Choosing Restful States on Your Windows PC</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-integrating-gopro-adventures-with-popular-social-media-channels/"><u>In 2024, Integrating GoPro Adventures with Popular Social Media Channels</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-all-encompassing-guide-to-dji-phantom-4s-capabilities/"><u>In 2024, The All-Encompassing Guide to DJI Phantom 4'S Capabilities</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcoming-d3d-initialization-setbacks/"><u>Overcoming D3D Initialization Setbacks</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1722856772010-wallet-friendly-hd-entertainment-packs-start-your-ht-journey-today/"><u>Wallet-Friendly HD Entertainment Packs - Start Your HT Journey Today!</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>