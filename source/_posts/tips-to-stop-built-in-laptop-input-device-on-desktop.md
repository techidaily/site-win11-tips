---
title: Tips to Stop Built-In Laptop Input Device on Desktop
date: 2024-08-23T07:05:57.245Z
updated: 2024-08-24T07:05:57.245Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tips to Stop Built-In Laptop Input Device on Desktop
excerpt: This Article Describes Tips to Stop Built-In Laptop Input Device on Desktop
keywords: Stop Laptop Keyboard Desktop,Disable Inbuilt Keyboard PC,Prevent Port Replicator Use,Cease Built-In USB Devices,Halt External Input on Monitor,Block Laptop Mice on Desk,Dismantle Onboard Peripheral Access
thumbnail: https://thmb.techidaily.com/acc4624304fa10f6661dcbd0f5aeeaf72266dc48176909da6153f980695e7df6.png
---

## Tips to Stop Built-In Laptop Input Device on Desktop

 Sometimes you don't want your laptop's keyboard to take inputs. This is usually because you're plugging in an external keyboard, either because the built-in one is broken or you just want a larger typing space with a full-sized keyboard.

 However, since the keyboard is an integral part of your portable computer, disabling its primary input method is a little tricky. Here, we show you how to temporarily and permanently disable the laptop keyboard on Windows 10 and 11\.

## How to Find Your Laptop Keyboard in Device Manager

 Whether you want to disable your laptop keyboard temporarily or permanently, you will need to uninstall the input device from Device Manager.

 For this, you’ll need to identify the integrated keyboard in Device Manager. Since Device Manager will list all the recognized keyboards, including external keyboards, here’s how you can identify your laptop keyboard from the list.

 To identify the built-in keyboard in Device Manager:

1. Press **Win + R** to open **Run**.
2. Type **devmgmt.msc** and click **OK** to open Device Manager.
3. In Device Manager, expand the **Keyboards** section.  
![device manager keyboards 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/device-manager-keyboards-1.jpg)
4. Right-click on the first keyboard entry **(HID/Standard)** and select **Properties**.
5. In the **General** tab, check the **Location** section. If it says **Location 1** or **Plugged into keyboard port**, it is likely your laptop’s internal keyboard.
6. Bluetooth and USB keyboards will show **On Bluetooth Low Energy** and **On US Input Device**, respectively as its location.

 If you don't find your keyboard listed, make sure you have [set Device Manager to show hidden devices.](https://www.makeuseof.com/view-hidden-devices-in-windows/)

## How to Disable the Laptop Keyboard Temporarily

 To disable your laptop’s keyboard temporarily:

1. Right-click on all the **HID** and **PS/2 Keyboard** entries with the **Properties Location** set to **Location 1** or **Plugged into keyboard.**  
![uninstall keyboard device device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/uninstall-keyboard-device-device-manager.jpg)
2. Next, select **Uninstall Device** from the context menu.
3. Click **Yes** to confirm the action.
4. That’s it. You have disabled your laptop’s internal keyboard successfully.

 That said, this is a temporary solution. As soon as you restart your system, Windows will look for the connected but unrecognized devices and install the necessary drivers to make them functional.

## How to Disable Your Laptop Keyboard Permanently

![disable ps 2 port 18042prt command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/disable-ps-2-port-18042prt-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
 If you want to disable your laptop keyboard permanently, you can disable your laptop’s built-in keyboard driver PS/2 i8042prt service using the Command Prompt. We'll use the sc command-line utility to configure the service and set its start parameter to disabled.

 To disable the laptop keyboard permanently:

1. Press the **Win key** and type **cmd** in the Windows search bar.
2. Right-click on **Command Prompt** and select **Run as Administrator**. Click **Yes** when the UAC prompt appears.
3. In the Command Prompt window, type the following command and press Enter:  
`sc config i8042prt start= disabled`
4. When the success message appears, close the Command Prompt, and restart your PC. After the restart, your laptop keyboard will stop registering any inputs.

 Note that, for this to work, you will need to uninstall your keyboard from Device Manager as shown above and restart your PC.

 If you change your mind and want to re-enable the keyboard, you can use the following command in an [elevated Command Prompt](https://www.makeuseof.com/windows-11-open-command-prompt/).

`sc config i8042prt start= auto`

 Once you see the success message, restart your PC to apply the changes.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Disable the Built-in Keyboard Using an Incompatible Driver

 Another quirky solution to disable a built-in keyboard is to install an incompatible driver for the input device. Here's how to do it.

1. Open Device Manager and expand the **Keyboard** section.
2. Right-click on your laptop keyboard device and select **Update driver**.  
![Update the Relevant Keyboard Driver in Windows Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/5-update-the-relevant-keyboard-driver-in-windows-device-manager.jpg)
3. Select **Browse my computer for drivers**.  
![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)
4. Next, select **Let me pick from a list of available drivers on my computer**.  
![update driver keyboard pick from list of available drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-keyboard-pick-from-list-of-available-drivers-device-manager.jpg)
5. Uncheck the **Show compatible hardware** option.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
6. Select a random manufacturer under the **Manufacturer** column.  
![install incompatible keyboard driver windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-incompatible-keyboard-driver0windows.jpg)
7. Click **Next**. Click **Yes** if an **Update Driver Warning** dialog appears.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
8. Once installed, close Device Manager and reboot your computer.

 After the restart, your laptop keyboard will stop working. If you need to install the correct driver again to enable the keyboard, right-click on the keyboard device and select **Update driver**. Next, select **Search automatically for drivers**. Windows will look for a compatible driver and install it.

![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)

<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->
 Alternatively, select **Browse my computer for drivers** in the Update Drivers dialogue. Next, select **Let me pick from a list of available drivers on my computer**. Make sure the **Show compatible hardware** option is enabled. Select an **HID Keyboard Device** driver from the list and click **Next**.

![install compatible hardware driver keyboard device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-compatible-hardware-driver-keyboard-device-manager.jpg)

 Wait for the driver to install. Once done, reboot your computer, and the keyboard will start working again.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
## Disable Your Laptop Keyboard Permanently on Windows

 The built-in chiclet keyboard on your laptop is the primary input method available, so there is no way to disable it with a single click. Also, you wouldn’t want to disable your keyboard accidentally. If you determine your keyboard to have gone rogue and typing on its own, you can permanently disable it using the Command Prompt and Device Manager.

 That said, apart from the hardware issues, your laptop keyboard can act up for many other reasons. To fix your keyboard, check for pending driver updates, use the built-in troubleshooter, or simply disable the individual keys.

 Sometimes you don't want your laptop's keyboard to take inputs. This is usually because you're plugging in an external keyboard, either because the built-in one is broken or you just want a larger typing space with a full-sized keyboard.

 However, since the keyboard is an integral part of your portable computer, disabling its primary input method is a little tricky. Here, we show you how to temporarily and permanently disable the laptop keyboard on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-files.techidaily.com/new-crafting-compelling-narratives-in-instagram-ads-top-10-tips-for-success-for-2024/"><u>[New] Crafting Compelling Narratives in Instagram Ads  Top 10 Tips for Success for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-optimal-budget-free-fb-picturemotion-designer/"><u>[New] In 2024, Optimal Budget-Free FB Picture/Motion Designer</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-revive-vanished-watch-video-icon-for-2024/"><u>[New] Revive Vanished Watch Video Icon for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-survivals-thrill-top-picks-for-heart-pounding-zombie-games/"><u>[New] Survival's Thrill  Top Picks for Heart-Pounding Zombie Games</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-transform-your-beats-with-free-dji-luts-for-minis-and-air-devices/"><u>[New] Transform Your Beats with Free DJI LUTs for Minis & Air Devices</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-a-step-by-step-process-to-upgrade-and-update-video-covers-on-social-media/"><u>[Updated] A Step-by-Step Process to Upgrade and Update Video Covers on Social Media</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-high-resolution-sky-photography-10-preferred-pages-for-2024/"><u>[Updated] High-Resolution Sky Photography  10 Preferred Pages for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-the-ultimate-routine-for-placing-imovie-in-the-vimeo-spotlight/"><u>[Updated] The Ultimate Routine for Placing iMovie in the Vimeo Spotlight</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-from-dull-to-dynamic-a-masters-approach-to-color/"><u>2024 Approved  From Dull to Dynamic  A Master's Approach to Color</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-scope-of-panoramic-filmmaking-explained/"><u>2024 Approved  The Scope of Panoramic Filmmaking Explained</u></a></li>
<li><a href="https://android-location-track.techidaily.com/5-ways-to-track-motorola-moto-g-5g-2023-without-app-drfone-by-drfone-virtual-android/"><u>5 Ways to Track Motorola Moto G 5G (2023) without App | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-through-win11s-disconnecting-gifs-dilemma-fixes-in-discord/"><u>Cutting Through Win11's Disconnecting GIFs Dilemma: Fixes in Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dismantle-the-defenses-taking-out-secure-qandas-from-win-11/"><u>Dismantle the Defenses: Taking Out Secure Q&As From Win 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/driver-error-code-bcm20702a0-unavailable/"><u>Driver Error Code BCM20702A0 Unavailable</u></a></li>
<li><a href="https://driver-error.techidaily.com/driver-installation-guide-ensuring-proper-functionality-in-windows-operating-systems/"><u>Driver Installation Guide: Ensuring Proper Functionality in Windows Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-error-a00f4289-from-your-windows-11-webcam/"><u>Eliminating Error A00F4289 From Your Windows 11 Webcam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-windows-11-steam-error-missing-files/"><u>Eliminating Windows 11 Steam Error: Missing Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-silent-slack-alerts-a-win-11-strategy-guide/"><u>Enhance Silent Slack Alerts: A Win 11 Strategy Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-the-performance-of-discord-searches-on-windows/"><u>Enhancing the Performance of Discord Searches on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-techniques-to-manage-windows-key-settings/"><u>Expert Techniques to Manage Windows Key Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fine-tuning-group-policies-for-single-accounts-in-latest-windows-versions/"><u>Fine-Tuning Group Policies for Single Accounts in Latest Windows Versions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fine-tuning-the-password-reset-counter-in-windows-11-and-11-after-fails/"><u>Fine-Tuning the Password Reset Counter in Windows 11 and 11 After Fails</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-rectify-error-0x887a0006-on-graphics-issues/"><u>Guide to Rectify Error 0X887A0006 on Graphics Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-counteract-failed-imports-of-iphone-photos-in-windows-os/"><u>How To Counteract Failed Imports of iPhone Photos in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-cut-down-clutter-spot-and-reduce-big-file-usage-windows/"><u>How to Cut Down Clutter: Spot and Reduce Big File Usage Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-intercept-text-messages-on-itel-s23plus-drfone-by-drfone-virtual-android/"><u>How to Intercept Text Messages on Itel S23+ | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-apple-iphone-se-2020-data-from-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Apple iPhone SE (2020) Data From iCloud? | Dr.fone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/how-to-successfully-resolve-intel-dptf-driver-installation-issues-a-comprehensive-guide/"><u>How to Successfully Resolve Intel DPTF Driver Installation Issues - A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-tackle-active-directory-domain-services-printer-failures-in-win-1011/"><u>How to Tackle Active Directory Domain Services Printer Failures in WIN 10/11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-unlock-apple-id-activation-lock-from-apple-iphone-14-pro-max-by-drfone-ios/"><u>How to Unlock Apple ID Activation Lock From Apple iPhone 14 Pro Max?</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-different-methods-to-unlock-your-iphone-12-pro-drfone-by-drfone-ios/"><u>In 2024, Different Methods To Unlock Your iPhone 12 Pro | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-easy-steps-to-document-video-calls/"><u>In 2024, Easy Steps to Document Video Calls</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-can-we-bypass-realme-narzo-n53-frp-by-drfone-android/"><u>In 2024, How Can We Bypass Realme Narzo N53 FRP?</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-tailored-thumbnail-for-social-media-vids/"><u>In 2024, Tailored Thumbnail for Social Media Vids</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-vidcapture-fb-videos-on-the-go/"><u>In 2024, VidCapture  Fb Videos on the Go</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keep-your-usb-active-disabling-hibernation-in-win-11/"><u>Keep Your USB Active: Disabling Hibernation in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-manual-time-adjustment-in-windows-systems/"><u>Master Manual Time Adjustment in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-audio-cds-mp3-conversion-with-imgburn-for-windows-users/"><u>Mastering Audio CDs: MP3 Conversion with ImgBurn for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-usb-security-in-modern-operating-systems/"><u>Optimizing USB Security in Modern Operating Systems</u></a></li>
<li><a href="https://extra-resources.techidaily.com/proficient-approaches-for-tiktok-bios-with-linked-content/"><u>Proficient Approaches for TikTok Bios with Linked Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-and-easy-qr-code-scanning-on-windows-pcs/"><u>Quick & Easy: QR Code Scanning on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-start-guide-access-to-computer-controls/"><u>Quick Start Guide: Access to Computer Controls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-win-tips-for-windows-file-order-max-156/"><u>Quick Win Tips for Windows File Order (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-functionality-to-windows-touchpad-commands/"><u>Restoring Functionality to Windows Touchpad Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-pc-efficiently-eliminate-extra-software-on-win11/"><u>Revamp Your PC: Efficiently Eliminate Extra Software on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-lost-power-options-in-ws-11-interface/"><u>Reviving Lost Power Options in WS 11 Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/screen-stickers-top-8-notebook-apps-for-pc/"><u>Screen Stickers: Top 8 Notebook Apps for PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-synergy-controlling-galaxy-via-windows-11-dex/"><u>Seamless Synergy: Controlling Galaxy via Windows 11 DeX</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-complexity-access-to-windows-printer-administration-console/"><u>Simplifying Complexity: Access to Windows Printer Administration Console</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-windows-navigation-replacing-ls-command-usage/"><u>Simplifying Windows Navigation: Replacing LS Command Usage</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-puzzle-fix-xerox-update-error-0x800f020b-on-your-pc-a-step-by-step-guide/"><u>Solving the Puzzle: Fix Xerox Update Error 0X800F020B on Your PC - A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-seamless-access-to-windows-11s-app-compendium/"><u>Strategies for Seamless Access to Windows 11'S App Compendium</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-methods-for-naming-and-arranging-window-writings-max-156/"><u>Streamlined Methods for Naming and Arranging Window' Writings (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essentials-of-setting-up-pc-manager-on-windows-11/"><u>The Essentials of Setting Up PC Manager on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-step-by-step-guide-to-recovering-windows-1110-keys/"><u>The Step-by-Step Guide to Recovering Windows 11/10 Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-clearing-up-windows-update-jams/"><u>The Ultimate Guide to Clearing Up Windows Update Jams</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/the-unsung-heroes-of-canvas-open-source-paintings/"><u>The Unsung Heroes of Canvas  Open-Source Paintings</u></a></li>
<li><a href="https://techidaily.com/three-methods-to-recover-lost-data-on-infinix-zero-30-5g-by-fonelab-android-recover-data/"><u>Three methods to recover lost data on Infinix Zero 30 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-7-decisions-your-roadmap-to-the-right-windows-device/"><u>Top 7 Decisions: Your Roadmap to the Right Windows Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turn-off-sound-boosters-in-windows-settings/"><u>Turn Off Sound Boosters in Windows Settings</u></a></li>
<li><a href="https://techtrends.techidaily.com/uncovering-contact-information-legally-on-the-internet-a-how-to-guide/"><u>Uncovering Contact Information Legally on the Internet – A How-To Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unifying-chrome-and-system-time-in-windows-land/"><u>Unifying Chrome and System Time in Windows Land</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-potential-on-app-and-browser/"><u>Unlocking Windows' Potential on App & Browser</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-portable-executable-format/"><u>Unraveling Windows' Portable Executable Format</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-optimize-your-mac-a-step-by-step-guide-to-freeing-up-space-for-fcpx/"><u>Updated In 2024, Optimize Your Mac A Step-by-Step Guide to Freeing Up Space for FCPX</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>