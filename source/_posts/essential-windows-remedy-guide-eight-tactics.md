---
title: Essential Windows Remedy Guide - Eight Tactics
date: 2024-08-16T01:48:42.213Z
updated: 2024-08-17T01:48:42.213Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Essential Windows Remedy Guide - Eight Tactics
excerpt: This Article Describes Essential Windows Remedy Guide - Eight Tactics
keywords: Fix Windows Glitches,Windows Troubleshooting Steps,Quick Windows Solutions,Easy Windows Repair Tips,Optimize Windows Performance,Resolve Windows Issues,Streamline Windows Functionality
thumbnail: https://thmb.techidaily.com/8e945962e22da7cc13548b0273df3ba622849bedca30e5d0f04cb4a458929e39.jpg
---

## Essential Windows Remedy Guide - Eight Tactics

 Out of all the errors, glitches, and problems you might encounter while using Windows, few generate as much fear as the dreaded "Operating system not found" screen. Visions of losing your entire media collection, your work, and your precious photos all flash before your eyes.

 Stop. Take a deep breath. Your data is still there—and just as importantly, you can fix the problem. Let's take a look at how to fix the "operating system not found" error on Windows 10 or Windows 11.

## 1\. Force Restart Your Windows

 Plenty of Windows troubles such as freezing up or programs malfunctions can be taken care of by a simple restart. In this case, since you are unable to boot your operating system, the only option left is to restart your PC straight from the power button of your computer.

 If this was a random one-time glitch, the quick reboot will fix the "Operating System not found" error is no time.

## 2\. Check the BIOS

 You need to check for two things in the BIOS. Firstly, you need to ensure your machine recognizes your hard drive. Secondly, you need to make sure the drive on which you installed Windows is listed as the preferred boot drive.

 The method for entering the BIOS changes from manufacturer to manufacturer. Typically, you'll need to press**Escape** ,**Delete** , or one of the**Function keys** during the boot-up process, before Windows loads. You should see an onscreen message advising you which is the correct key during the boot process.

[The BIOS menu](https://www.makeuseof.com/tag/the-bios-explained-boot-order-video-memory-saving-resets-and-optimum-defaults-si/) itself also varies between devices. Broadly speaking, you need to locate the**Boot** tab at the top of the screen. Unfortunately, you can only use your keyboard to navigate the BIOS menu, so keep an eye out for a list of controls on the BIOS screen.

 Within the Boot tab, highlight**Hard Drive** and press**Enter** . Make sure**Hard Drive** is listed above**USB Storage** ,**CD\\DVD\\BD-ROM** ,**Removable Devices** , and**Network Boot** . You can adjust the order using the**+** and**–** keys.

![boot order windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/boot-order-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->

 If everything in your BIOS menu looked fine, jump to step three. If you didn't see the hard drive listed, go to step two.

## 3\. Reset the BIOS

 If your machine is not recognizing your hard drive, there are lots of possible causes. For non-tech-savvy users, the only easy solution is to try resetting the entire BIOS menu to its default values.

 At the bottom of the BIOS menu, you should see a key for**Setup Defaults** or**Reset BIOS** . On some machines it's**F9** , but it might be different on yours. Confirm your decision when prompted and restart your machine.

 If the operating system is still not found, you can stop reading this article. Unless you know a lot about building computers, you'll need to take your machine to a computer repair shop.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Fix the Boot Records

 Microsoft Windows primarily relies on three records to boot your machine. They are the**Master Boot Record** (MBR),**DOS Boot Record** (DBR), and the**Boot Configuration Database** (BCD).

 If any of the three records becomes damaged or corrupted, there's a high chance you'll encounter the "Operating system not found" message.

 Thankfully, fixing these records is not as complicated as you might think. You just need a removable Windows installation drive. Use Microsoft's [Media Creation Tool](https://www.microsoft.com/en-gb/software-download/windows10) to create some Windows installation media.

![windows media creation tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-media-creation-tool.jpg)

 When your tool is ready, you need to use it to boot your machine. Depending on your device, you might only need to press a single key during the boot process, or you might have to change the boot order in the BIOS menu.

 Eventually, you will see the Windows Setup screen. Enter your preferred language, keyboard, and time format, and click**Next** . On the next screen, select**Repair your computer** .

 Next, navigate to**Troubleshoot > Advanced Options > Command Prompt** . When Command Prompt loads, type the following three commands. Press**Enter** after each of them:

* **bootrec.exe /fixmbr**
* **bootrec.exe /fixboot**
* **bootrec.exe /rebuildbcd**

 Each command might take several minutes to complete. Once all the processes are finished, restart your PC and see if it boots successfully.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
## 5\. Enable or Disable UEFI Secure Boot

 The [Windows operating system has come a long way](https://www.makeuseof.com/windows-brief-history/) . However, one thing remains the same. Almost every Windows machine is shipped with UEFI firmware and Secure Boot enabled. However, in some cases, it might not work. For example, if Windows is installed on a GUID Partition Table, it can only boot in UEFI mode. Conversely, if Windows is running on an MBR disk, it cannot boot in UEFI mode.

 As such, it's prudent to either enable or disable UEFI Secure Boot and see if it makes a difference. You make the adjustments in the BIOS menu. Usually, the option will be called**Secure Boot** and can be found in the**Security** tab.

![secure boot configuration windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/secure-boot-configuration-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
## 6\. Activate the Windows Partition
![disk part](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/disk-part.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->

 It's possible that the Windows partition is disabled. If that's the case, then it's possible to encounter the 'operating system not found' error in your PC. You can fix this using Windows' native diskpart tool. To work through the following steps, you will once again need a Windows installation media USB.

 Turn on your machine and boot from the tool. As in step three, you'll need to enter your language preferences, etc., click**Next** , select**Repair your computer** , and go to**Troubleshoot > Advanced Options > Command Prompt** .

 In Command Prompt, type**diskpart** and press**Enter** , then type**list disk** and press**Enter** . You will see a list of all the disks attached to your machine. Make a note of the disk number you need. Typically, it's the largest one.

 Next, type**select disk \[number\]** , replacing \[number\] with the aforementioned number. Press**Enter** .

 Now type**list volume** and press**Enter** . It will show you all the partitions on the disk you selected. Establish which partition Windows is installed on and make a note of the number, then type**select volume \[number\]** , again replacing \[number\] with the number you just noted.

 Finally, type**active** and press**Enter** . To see if the process was successful, restart your machine.

## 7\. Use Easy Recovery Essentials

 Easy Recovery Essentials is a third-party app that specializes in fixing boot issues. If none of the previous five steps have worked, it's worth trying.

 In addition to fixing the "Operating system not found" message, it can also solve other common startup error messages. They include:

* INACCESSIBLE\_BOOT\_DEVICE.
* INACCESSIBLE\_BOOT\_VOLUME.
* UNMOUNTABLE\_BOOT\_VOLUME.
* BOOTMGR is missing.
* The Boot Configuration Data for your PC is missing or contains errors.
* An error occurred while attempting to read the boot configuration data.
* Boot.ini not found.
* ... and more.

 Just download the app, burn the ISO to a CD, and use the CD to boot your machine. The app's wizard guides you through the repair process.

**Download:** [Easy Recovery Essentials](https://neosmart.net/EasyRE/) ($40, free for Windows 11)

## 8\. Reinstall Windows

 If none of the methods above have worked so far, then perhaps a complete reinstallation is in order. Don't worry, you won't lose any of your data though. Now, since you can't launch your PC, you will have to reinstall your Windows straight from a USB drive, as [laid out by Microsoft](http://docs.microsoft.com/en-us/windows-hardware/manufacture/desktop/install-windows-from-a-usb-flash-drive?view=windows-11) .

 So plug in your bootable USB drive and boot your PC from the USB. If you don't have a bootable USB yet, you can check out our guide on [creating a bootable USB from scratch](https://www.makeuseof.com/tag/10-tools-make-bootable-usb-iso-file/) and get your work started. If your Windows doesn't boot, you might first have to change the booting order so that the OS can load boot up through your USB. To do that, press the**Esc/F10/F12** or the relevant key to boot into the boot-selection device. Once you're there, change the booting order to boot from your USB.

 The process is fairly straightforward from there. Just follow the on-screen instructions, launch the installation wizard and wait while it installs a new copy of Windows.

## Last Resort: Head to the Shops

 Our tips should help you fix the operating system not found error on Windows in all but the direst of circumstances. Unfortunately, however, it's just one of many error messages that you're likely to encounter while using Microsoft's operating system.

 If you can't work out what is wrong with your machine, it makes little sense to keep fiddling. If you are not tech-savvy, you might do more harm than good. As a last resort, head to your local PC repair shop, and they should be able to get you up and running again in no time.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## Fixing the "Operating System Not Found" Error on Windows PC

 Regardless of if you fix the problem yourself, or you need professional help, you'll hopefully get a PC that remembers it has an operating system again. Best of all, your files should all be safe and sound!

 Microsoft Windows, by itself, is full of potential errors, and its official Store is no different. However, there are ways you can fix any issues you come across with the Microsoft Store.

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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-how-to-optimize-your-instagram-stories-for-engagement/"><u>[New] 2024 Approved  How to Optimize Your Instagram Stories for Engagement</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-aural-archive-discussion-and-judgment-for-2024/"><u>[New] Aural Archive  Discussion & Judgment for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-guide-to-the-top-10-historical-education-channels-for-2024/"><u>[New] Guide to the Top 10 Historical Education Channels for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-the-ultimate-cut-for-quality-offline-ipad-gaming/"><u>[New] In 2024, The Ultimate Cut for Quality Offline iPad Gaming</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-mastering-mobile-apps-for-luts-for-2024/"><u>[New] Mastering Mobile Apps for LUTs for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-creating-illusionary-settings-with-instagrams-chroma-key/"><u>[Updated] Creating Illusionary Settings with Instagram’s Chroma Key</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-top-strategies-for-capturing-webinars-effectively/"><u>[Updated] In 2024, Top Strategies for Capturing Webinars Effectively</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-insiders-look-at-top-earning-instagram-tactics-for-2024/"><u>[Updated] Insider's Look at Top Earning Instagram Tactics for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-instantaneous-pro-thumbnail-creation-valorant-edition/"><u>[Updated] Instantaneous Pro Thumbnail Creation - Valorant Edition</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-illuminating-path-to-stellar-android-video-quality/"><u>2024 Approved  Illuminating Path to Stellar Android Video Quality</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-laughter-unleashed-a-stepwise-strategy-for-making-impactful-gifs/"><u>2024 Approved  Laughter Unleashed  A Stepwise Strategy for Making Impactful GIFs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-snipping-tool-with-a-simple-key-combo-on-win-11/"><u>Activating Snipping Tool with a Simple Key Combo on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-gaps-improving-windows-11s-trouble-resolution-tools/"><u>Bridging Gaps: Improving Windows 11'S Trouble Resolution Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customize-the-status-bar-a-guide-to-including-a-weather-icon-in-windows-11/"><u>Customize the Status Bar: A Guide to Including a Weather Icon in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cybersecurity-insight-key-windows-activities-that-could-conceal-threats/"><u>Cybersecurity Insight: Key Windows Activities That Could Conceal Threats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-window-management-active-periods-not-permanent-disruptions/"><u>Efficient Window Management: Active Periods, Not Permanent Disruptions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-entry-into-your-windows-11s-application-arcade/"><u>Effortless Entry Into Your Windows 11'S Application Arcade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-flawed-windows-safety-features-in-win-11/"><u>Fixing Flawed Windows Safety Features in Win 11</u></a></li>
<li><a href="https://buynow-info.techidaily.com/future-proof-gear-leading-wireless-mice-to-watch-in-2025/"><u>Future-Proof Gear: Leading Wireless Mice to Watch in 202#!5</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-constant-windows-printer-selection/"><u>Guidelines for Constant Windows Printer Selection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-does-ai-enhance-windows-11-usability/"><u>How Does AI Enhance Windows 11 Usability?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-the-windows-11-taskbar-teams-chat-removal-will-impact-you/"><u>How the Windows 11 Taskbar Teams Chat Removal Will Impact You</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-nokia-105-classic-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on Nokia 105 Classic? | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-constructing-captivating-valorant-youtube-thumbnails/"><u>In 2024, Constructing Captivating Valorant YouTube Thumbnails</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-fake-snapchat-location-without-jailbreak-on-samsung-galaxy-f14-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fake Snapchat Location without Jailbreak On Samsung Galaxy F14 5G | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-process-of-screen-sharing-samsung-galaxy-f15-5g-to-pc-detailed-steps-drfone-by-drfone-android/"><u>In 2024, Process of Screen Sharing Samsung Galaxy F15 5G to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-the-essential-guide-to-crafting-dynamic-snaps/"><u>In 2024, The Essential Guide to Crafting Dynamic Snaps</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-top-10-airplay-apps-in-realme-11x-5g-for-streaming-drfone-by-drfone-android/"><u>In 2024, Top 10 AirPlay Apps in Realme 11X 5G for Streaming | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-troubleshooting-error-connecting-to-the-apple-id-server-on-iphone-13-pro-by-drfone-ios/"><u>In 2024, Troubleshooting Error Connecting to the Apple ID Server On iPhone 13 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-themes-for-enhanced-terminal-views/"><u>Innovative Themes for Enhanced Terminal Views</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-time-display-on-win-11-taskbar/"><u>Mastering Time Display on Win 11 Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-for-fixing-media-creators-error-0x8007043c/"><u>Methods for Fixing Media Creator's Error 0X8007043C</u></a></li>
<li><a href="https://technical-tips.techidaily.com/navigating-google-gemini-strategies-for-optimizing-your-visibility/"><u>Navigating Google Gemini: Strategies for Optimizing Your Visibility</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-unleash-your-creativity-best-stop-motion-animation-tools-for-mac-and-pc-for-2024/"><u>New Unleash Your Creativity Best Stop Motion Animation Tools for Mac and PC for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-grammarly-a-dead-service-on-your-desktop/"><u>Reactivating Grammarly, a Dead Service on Your Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reignite-the-gaming-revolution-integrate-trophies-and-awards-using-retroarch/"><u>Reignite the Gaming Revolution - Integrate Trophies and Awards Using Retroarch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-absent-remove-button-for-windows-11-pins/"><u>Reinstating Absent 'Remove' Button for Windows 11 PINs</u></a></li>
<li><a href="https://buynow-info.techidaily.com/roku-vs-chromecast-showdown-determining-the-top-streaming-stick/"><u>Roku vs Chromecast Showdown: Determining the Top Streaming Stick</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-re-entry-to-your-shared-windows-spot/"><u>Seamless Re-Entry to Your Shared Windows Spot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-pc-manager-on-windows-11-a-quick-guide/"><u>Setting Up PC Manager on Windows 11 – A Quick Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-stabilizing-dwarf-fortress-on-win/"><u>Solutions for Stabilizing Dwarf Fortress on Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-ensure-seamless-windows-notepad-functioning/"><u>Steps to Ensure Seamless Windows Notepad Functioning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-recover-non-operational-windows-apps/"><u>Steps to Recover Non-Operational Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-windows-11-bluetooth-try-connecting-error/"><u>Steps to Resolve Windows 11 Bluetooth 'Try Connecting' Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sticky-notes-strategies-for-sustained-top-level-visibility-on-win-os/"><u>Sticky Notes Strategies for Sustained Top-Level Visibility on Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-evolutionary-leap-with-ai-copilot-in-windows-11-life/"><u>The Evolutionary Leap with AI Copilot in Windows 11 Life</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-windows-workshop-generating-and-deciphering-system-insights/"><u>The Windows Workshop: Generating & Deciphering System Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/too-much-glitches-handle-deps-before-virtualbox-on-win/"><u>Too Much Glitches? Handle Deps Before VirtualBox on Win</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/top-budget-routers-of-the-year-an-in-depth-look-at-the-tp-link-archer-c9/"><u>Top Budget Routers of the Year: An In-Depth Look at the TP-Link Archer C9</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbo-enabledisable-bing-ai-on-windows-11-search-bar/"><u>Turbo Enable/Disable: Bing AI on Windows 11 Search Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/use-external-tools-explore-third-party-software-like-flux-redshift-or-display-temp-to-customize-display-behavior-according-to-time-of-day-and-ambient-light-26/"><u>Use External Tools: Explore Third-Party Software Like f.lux, Redshift, or Display Temp to Customize Display Behavior According to Time of Day and Ambient Light Conditions</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-is-a-sim-network-unlock-pin-get-your-vivo-y77t-phone-network-ready-by-drfone-android/"><u>What Is a SIM Network Unlock PIN? Get Your Vivo Y77t Phone Network-Ready</u></a></li>
<li><a href="https://win11-tips.techidaily.com/whats-behind-windows-11s-disappearing-thumbnail-issue-fixes-here/"><u>What's Behind Windows 11'S Disappearing Thumbnail Issue? Fixes Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win10-isolating-and-fixing-unilateral-audio-malfunction/"><u>Win10: Isolating and Fixing Unilateral Audio Malfunction</u></a></li>
</ul></div>
