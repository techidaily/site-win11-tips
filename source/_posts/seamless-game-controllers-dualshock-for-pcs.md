---
title: "Seamless Game Controllers: DualShock for PCs"
date: 2024-11-02T13:23:36.654Z
updated: 2024-11-07T11:49:20.806Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Seamless Game Controllers: DualShock for PCs"
excerpt: "This Article Describes Seamless Game Controllers: DualShock for PCs"
keywords: Seamless PC Gaming,DualShock Controller,PS4 to PC Compatibility,Game Controller Adapters,Cross-Platform Controls,Console Controller for PC,PlayStation Accessories (PC)
thumbnail: https://thmb.techidaily.com/0fffdaf6b0345d8277ec9fafebd3429c28f703cd8774f81e39bb2cfd9b5790b4.jpg
---

## Seamless Game Controllers: DualShock for PCs

 Your PS3 is probably gathering dust by now, so why not put it to good use... or, at least, its controllers? Use them on your PC and give them a new life.

 Although it was possible to use PS3 joypads on PCs in the past, the process was finicky, and their wireless functionality was wonky. That was until DsHidMini entered the scene. Here's how you can use a PS3 DualShock controller on your PC, both through a USB connection and wirelessly through Bluetooth

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is DsHidMini?

 DsHidMini is an open-source solution for connecting and configuring many types of joypads to a PC. As such, if you have your old PS3 or PS4 DualShock controllers around, why not put them to use with this app?

 DsHidMini enables your PC to recognize them and provides XInput emulation. With Xinput being the modern standard for joypads under Windows, you'll be able to use your PlayStation controller with most modern games.

## Getting the Necessary Software for Using Your PS3 Controller on a PC

 By combining two pieces of software, DsHidMini, and BthPS3, you can have your PC detect your DualShock controller effortlessly both when connected with a USB cable and wirelessly through Bluetooth.

 Note, though, that for this guide, we take the existence of correctly working Bluetooth functionality for granted. If your PC lacks Bluetooth support, check our buyer's guide on[the best Bluetooth adapters you can grab today](https://www.makeuseof.com/best-bluetooth-adapters/) . Then, check our guide on[how to add Bluetooth to any computer](https://www.makeuseof.com/add-bluetooth-pc/) .

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1172027/12108" target="_top" id="1172027">
  <img src="//a.impactradius-go.com/display-ad/12108-1172027" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1172027/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Download and Install DsHidMini and BthPS3

 DsHidMini suggests installing BthPS3 to have your DualShock controllers correctly detected and connected to your PC. This guide will follow that suggestion, especially since we want them to work wirelessly.

1. Start by downloading the first piece of software from[DsHidMini's GitHub page](https://github.com/ViGEm/DsHidMini) .  
![DsHidMini GitHub Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshidmini-github-page.jpg)
2. Do the same with a visit at[BthPS3's GitHub page](https://github.com/ViGEm/BthPS3) .  

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528685/16446" target="_top" id="1528685">
  <img src="//a.impactradius-go.com/display-ad/16446-1528685" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528685/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![BthPS3 GitHub Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/bthps3-github-page.jpg)
3. In both cases, you'll find the downloadable files by clicking on the link under**Installation** , then checking out the links under**Assets** . Most people should go for the x64 versions. If you're still using an older 32-bit version of Windows, get the x86 files.  
![BthPS3 GitHub Assets Links](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/bthps3-github-assets-links.jpg)
4. Click on**BthPS3's MSI file** that you've downloaded to install the Bluetooth driver. "MSI" stands for Microsoft Software Installer. Unlike executable installers, MSI relies on the "official" installation libraries bundled with Windows. If you meet any problems during that step, check our guide on[how to fix issues with the Windows Installer package](https://www.makeuseof.com/windows-installer-package-fix-issues/) .  
![BthPS3 Installation](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/bthps3-installation.jpg)
5. After BthPS3's successful installation, you'll see it as a new device under the**Bluetooth** category in**Device Manager** . The easiest way to access the Device Manager is by using the**Windows Key** +**X** shortcut and selecting it from the menu that shows up.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934258/19272" target="_top" id="1934258">
  <img src="//a.impactradius-go.com/display-ad/19272-1934258" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934258/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![BthPS3 Installed Bluetooth Driver in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/bthps3-installed-bluetooth-driver-in-device-manager.jpg)
6. DsHidMini's installation is a tad more complicated since it comes in a compressed archive. Open**Windows File Explorer** , and pay a visit to the folder where you saved DsHidMini's downloaded archive. All modern versions of Windows support the ZIP archive format, so you can right-click on the file and choose**Extract** . However, we used WinRAR instead simply because we had it installed, and it's somewhat faster. In both cases, the result is the same.  
![Extracting DsHidMini Archive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/extracting-dshidmini-archive.jpg)
7. Look inside the extracted archive's folder, and you'll see two more folders:**x64** and**x86** . Enter the one matching your Windows architecture. As mentioned above, most people nowadays should go for**x64** .  
![DsHidMini Extracted Archive Contents](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshidmini-extracted-archive-contents.jpg)
8. Inside that folder, you'll find another subfolder named**dshidmini** . Enter that one, too.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080342/19272" target="_top" id="2080342">
  <img src="//a.impactradius-go.com/display-ad/19272-2080342" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080342/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![DsHidMini Extracted Archive Contents x64](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshidmini-extracted-archive-contents-x64.jpg)
9. Right-click on the**dshidmini.inf** file, and choose**Install** from the menu that shows up. When that step completes, install the**igfilter.inf** the same way.  
![DsHidMini Extracted Archive Contents x64 dshidmini inf install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshidmini-extracted-archive-contents-x64-dshidmini-inf-install.jpg)

 Theoretically, that's everything you need for your DualShock to work with your PC. Practically, as is Windows' tradition, it wouldn't hurt to restart once to ensure the drivers are correctly installed, activated, and work as they should.

## How to Pair and Configure Your PS3 DualShock

 The next step is to "pair" your controller with your PC. However, that process is somewhat unconventional compared to how you usually connect Bluetooth devices to your PC.

1. Connect your DualShock joypad to your PC using a mini-USB cable. Your joypad should begin charging.
2. Pay a visit to the folder with DsHidMini's extracted files. Double-click on the**DSHMC.exe** to run it.  
![DSHMC.exe File In File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshmc-exe-file-in-file-explorer.jpg)
3. You should see your "PlayStation controller" detected on the left side of the app's window. Now, if you run Steam with its outstanding controller support, it should detect and configure your joypad for use in modern games. As for wireless? Unplug the cable, and your joypad should keep working as if nothing happened.  
![DSHMC.exe Controller Detected](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshmc-exe-controller-detected.jpg)
4. DsHidMini will have your controller recognized as an**XInput** device by default to maximize compatibility with modern software. But what if you want to use it on an older title that uses the older**DirectInput** standard or to have emulators like PPSSPP, PCSX2, and RPCS3 recognize it as an actual PlayStation controller? Close DSHMC.exe, then right-click on it and re-run it, but this time choose**Run as Administrator** . When its window shows up again, click on your controller on the left, and you'll see more details about it on the right and some options you can tweak.  
![DSHMC Configuration As Admin](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshmc-configuration-as-admin.jpg)
5. You can change the HID device mode from**XInput** to another mode compatible with the software where you want to use your controller. You can also tweak its**Idle disconnect** period or define after how much time of inactivity the controller should disconnect and turn off.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135366/19272" target="_top" id="2135366">
  <img src="//a.impactradius-go.com/display-ad/19272-2135366" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135366/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![DSHMC Change HID Mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshmc-exe-change-hid-mode.jpg)

## How to Remove Remnants of Old Drivers

 If your joypad isn't correctly detected, did you use another solution in the past to have it work under Windows, like Sony's official driver or ScpToolkit? If yes, the problem might be a conflict between those and the DsHidMini and BthPS3 combo.

 Removing the older drivers and software is somewhat complicated. Plus, the process varies based on the driver and software used. So, we won't go over it in detail but offer a "generic guide" covering the basic steps for most cases.

 Run the**Command Prompt** or**PowerShell** with Administrative rights. Then, use the commands, in sequence, if you were using ScpToolkit:

`taskkill /F /IM ScpServer.exe  
taskkill /F /IM ScpMonitor.exe  
taskkill /F /IM ScpTrayApp.exe  
sc stop Ds3Service  
sc delete Ds3Service`

 These will stop and remove all active processes and services for PlayStation joypad-enabling software you might have used in the past.

 Now, press**Win** +**X** and choose**Device Manager** . Find and remove any mention of a "PlayStation controller" under**Human Interface Devices** if you were using the official Sony drivers.

 For ScpToolkit, look under**libusbK USB Devices** instead, and right-click and**Uninstall** any entry you see. Also, check for and, if found, uninstall the drivers for any "Bluetooth Dongle", "DualShock controller", or "PlayStation controller" under**Universal Serial Bus devices** .

 Then, download[DriverStore Explorer from its GitHub page](https://github.com/lostindark/DriverStoreExplorer/releases/tag/v0.11.79) . Extract its archive and run the app. Enable**Force Deletion** on the right. Seek any**libusbK USB Devices** , a standalone**scpvbus.inf** , or**bluetoothhost.inf** and**ds3controller.inf** if using ScpToolkit.

 Look for**sixaxis.inf** instead if using the official Sony driver. In both cases, place a checkmark next to any of those entries you'll find, and then click on**Delete Drivers** on the right.

 Afterward, exit the app, restart your PC, and let Windows re-detect any hardware and install the default drivers. Then, repeat the steps we covered above to install BthPS3 and DsHidMini from scratch.

<!-- affiliate ads begin -->
<span id="1982570">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982570.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982570">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982570.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982570%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982570/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Use Your PS3 DualShock in Games

 Your controller should work now in most modern games that support Xbox joypads and for most joypad-enabled titles running under Steam.

 When that's not the case, run DSHMC.exe as an administrator and change the HID mode used by your joypad to the one supported by the game or app where you want to use it.

 An easy way to find the HID mode to choose for a particular title is to check if there's information about it at[PCGamingWiki](https://www.pcgamingwiki.com/wiki/Main%5FPage) .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123726/7443" target="_top" id="2123726">
  <img src="//a.impactradius-go.com/display-ad/7443-2123726" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123726/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Using Classic PS3 Joypads on Your Modern-Day Games for Windows

 Reusing your older joypads on your PC is the smartest choice. Apart from the fact you won't have to pay a dime to do it, they're great performers, tried and tested, and you're already familiar with them.

 Worst case scenario, you might have to buy a Bluetooth dongle for your PC, which would still come at a fraction of the cost of a brand-new controller.

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
<li><a href="https://some-skills.techidaily.com/new-the-insiders-guide-to-professional-vsco-usage/"><u>[New] The Insider's Guide to Professional VSCO Usage</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-top-ten-viewers-favorites-in-a-single-day-on-youtube-for-2024/"><u>[Updated] Top Ten Viewers' Favorites in a Single Day on YouTube for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-advanced-tiktok-edit-tricks-to-boost-creativity/"><u>2024 Approved Advanced TikTok Edit Tricks to Boost Creativity</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/can-instant-subscription-lead-to-higher-watch-time/"><u>Can Instant Subscription Lead to Higher Watch Time?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-updater-setback-code-80073712/"><u>Conquering Updater Setback: Code 80073712</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-clock-and-dates-visibility-on-windows-bar/"><u>Customizing Clock and Dates Visibility on Windows Bar</u></a></li>
<li><a href="https://android-unlock.techidaily.com/delete-gmail-account-withwithout-password-on-samsung-galaxy-s24-by-drfone-android/"><u>Delete Gmail Account With/Without Password On Samsung Galaxy S24</u></a></li>
<li><a href="https://tech-revival.techidaily.com/effective-strategies-for-managing-affiliate-reviews-and-feedback/"><u>Effective Strategies for Managing Affiliate Reviews and Feedback</u></a></li>
<li><a href="https://sound-issues.techidaily.com/effective-techniques-to-restore-functionality-in-non-responsive-kotion-each-g2000-mics/"><u>Effective Techniques to Restore Functionality in Non-Responsive Kotion Each G2000 Mics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-accelerate-slow-microsoft-edge-win10-w11/"><u>How to Accelerate Slow Microsoft Edge (Win10, W11)</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-restore-a-bricked-google-pixel-8-back-to-operation-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Restore a Bricked Google Pixel 8 Back to Operation | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-nokia-c300-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some Pro Tips for Pokemon Go PvP Battles On Nokia C300 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/inquiring-into-wsls-effect-on-linux-users/"><u>Inquiring Into WSL's Effect on Linux Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-change-from-pin-based-logon-to-password-logon-in-windows-11/"><u>Navigating the Change From PIN-Based Logon to Password Logon in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-6-peculiar-w11-elements/"><u>Navigating Through 6 Peculiar W11 Elements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-win11-for-isp-configurations/"><u>Navigating Win11 for ISP Configurations</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/step-up-in-the-metaverse-game-with-these-critical-devices-top-7-for-2024/"><u>Step Up in the Metaverse Game with These Critical Devices (Top 7) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-ceasing-windows-data-collection/"><u>Strategies for Ceasing Windows Data Collection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-challenge-of-win11s-read-only-folds/"><u>Tackling the Challenge of Win11's Read-Only Folds</u></a></li>
</ul></div>

