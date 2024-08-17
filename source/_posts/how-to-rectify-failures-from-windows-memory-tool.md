---
title: How To Rectify Failures From Windows Memory Tool
date: 2024-08-16T01:54:58.005Z
updated: 2024-08-17T01:54:58.005Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How To Rectify Failures From Windows Memory Tool
excerpt: This Article Describes How To Rectify Failures From Windows Memory Tool
keywords: Fixing Windows MemTool Errors,Windows Memory Correction Guide,Troubleshoot Windows RAM Issues,Remedy Windows Memory Problems,Resolve Windows Memory Tool Failures,Windows RAM Repair Steps,Correcting Memory Tools in Windows
thumbnail: https://thmb.techidaily.com/f1c57303ea622caa2e3702d3e2a77e00493f995e737fa90087cc4940fcb0139c.jpg
---

## How To Rectify Failures From Windows Memory Tool

 Using the Windows Memory Diagnostic tool, you can diagnose memory issues on your Windows computer. If there is a problem, it will return an error. One common Windows Memory Diagnostic error you may encounter is "Hardware problems were detected; contact manufacturer," followed by the "You have a memory problem" dialog.

 This error can be a false positive. You can also confirm the same by using a third-party memory diagnostic tool. In case of a hardware issue, you may need to replace the memory stick or repair the memory slot, if possible.

## What Causes the Windows Memory Diagnostic Hardware Problems Were Detected Error?

 This error is often triggered after a blue screen of death (BSOD) or the system freezing issues. The reason for the error can vary and include faulty memory slots and memory sticks. It can also be a false positive due to a Windows OS glitch.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Check for Overclocking Issues

 Incorrect overclocking can cause hardware issues. While faster RAM can help you achieve good performance, it is important to consider the hardware limitations before applying the tweaks.

 If you have overclocked your RAM, try to lower the frequencies to see if the error goes away. Do this until you find a safe frequency, or reset it to factory default settings.

 If you are unsure about the default memory frequencies, try to perform a BIOS reset. Load the BIOS default, which should reset the RAM frequencies to its factory default. Refer to your motherboard manufacturer manual for specific instructions.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
## 2\. Run the Hardware Troubleshooter

 The built-in Windows hardware troubleshooter can scan for hardware-related issues and even try to perform a repair if possible. If you haven’t tried already, run the hardware troubleshooter using the Command Prompt to resolve the problem.

 Note that it is a legacy troubleshooter, and you may not find it in the Windows 11 version newer than 22H2\.

 To run the Windows Hardware Troubleshooter:

1. Press the **Win** key and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator**. Click **Yes** if prompted by the User Account Control dialog.  
![run windows hardware troubleshooter command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-windows-hardware-troubleshooter-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
3. In the Command Prompt window, type the following command and press **Enter**:  
`msdt.exe -id DeviceDiagnostic`
4. In the **Hardware and Devices** dialog, click **Next**. By default, the troubleshooter is set to apply any repairs available. To disable automatic repair, click **Advanced** and uncheck the **Apply repairs automatically** option.  
![hardware and devices troubleshooter windows 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/hardware-and-devices-troubleshooter-windows-1.jpg)
5. It will scan your computer for issues, which may take a few minutes. If an issue is detected, select to automatically apply the repair.
6. If the suggested problem is unrelated to memory, you can skip it to see the next problem. The troubleshooter will detect additional issues. If an issue is found, apply the fixes and check for any improvements.

## 3\. Remove and Reinsert Your Memory Sticks

 If you work with multiple memory sticks, remove all the sticks and wipe the card to remove dust and debris. Reboot the computer and check for any improvements.

 Still not working? Remove all but one stick and reboot your computer to see if the error is resolved. If not, repeat the procedure with all the sticks individually to determine and detect a faulty memory stick. If you find a faulty memory module, you can get a replacement or claim a warranty if available.

 If the issue persists, check your memory (RAM) slots for fault. Insert a memory stick into one of the slots and reboot your computer. If there is no error, test other slots and check if you can find a malfunctioning slot.

 If you determine a faulty RAM slot to have caused the issue, repairing it is tedious. First, RAM slots aren’t easily accessible like memory sticks. Second, to replace the slot, you’ll need to find a spare but compatible motherboard with working slots and then solder the connections onto your motherboard.

 If repairing the slots is not possible, your only option is a motherboard replacement. Depending on your system configuration, this can be an expensive solution. Or you can continue to use the system without utilizing the faulty memory slot, albeit with reduced performance.

## 4\. Test Your RAM with MemTest86+

 If the troubleshooter fails to detect any issue, you can perform a memory test using the MemTest86+ utility. It is an open-source memory testing tool to check for fails in your computer memory.

 MemTest86+ is a bootable utility and cannot be used from within Windows. To test your RAM with Memetst86+, you’ll need a USB drive. You can use the Memtest86+ Windows installer to create a bootable drive and boot from it.

 As of writing this article, Memtest86+ wasn’t compatible with Windows Secure Boot. So, you’ll need to disable Secure Boot to use the utility.

 To perform a memory test using Memtest86+:

1. Connect a USB flash drive to your computer. Take a backup of important data in the drive, as all the data will be deleted during the process.
2. Next, go to the [metest86+ page](https://www.memtest.org/) and download the latest version available.
3. Run the installer and select your USB drive. Make sure to select the format option.  
![memtest86 plus create bootable usb drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/memtest86-plus-create-bootable-usb-drive.jpg)
4. Click **Next** and wait for the installer to create a bootable drive.
5. Next, if you haven’t already, [disable Secure Boot on your Windows computer](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/).
6. Next, power off your computer. You may also need to clear your motherboard CMOS to reset your BIOS to factory default settings. You can also [reset BIOS to its default configuration](https://www.makeuseof.com/tag/reset-bios-default-settings-computer/) from the BIOS menu.  
![memtest86 plus memory integrity test in progress](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/memtest86-plus-memory-integrity-test-in-progress.png)
<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Next, plug the Memtest86+ bootable USB drive into your computer and turn it on.
8. Boot into the Boot Menu and select the bootable USB drive as the boot device. The hotkey key to enter the Boot Menu may vary depending on your computer manufacturer. You can press **F9** on an **HP** computer, **F12** on a **Dell** computer and so on to access the **Boot Menu**.
9. Memtest86+ will automatically start the memory integrity check. Let Memtest86+ complete at least 2 passes; the more, the better. Press the **Esc** key to stop the test if there are no errors after multiple passes.

 If an error is detected during testing, it is likely a case of faulty RAM and may need replacement. But to be on the safer side, ensure you test each RAM separately to find the odd one out.

 Not all the errors detected by the Memtest86+ are due to faulty hardware. Some errors may occur due to compatibility issues. Check your RAM module and the motherboard specifications to determine any compatibility issues. You can also test the RAM modules by inserting them into a different motherboard and see if it works.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Perform a Repair Reinstall or Clean Install Windows

 If the Windows Memory Diagnostic tool continues to show the hardware problem was detected error, even after the Memtest86+ passed the test, check if the problem is due to issues with the Windows operating system.

 To fix critical issues with your Windows image, you can perform a [repair reinstall of Windows 11 without deleting apps](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/). If that does not work, perform a clean install. This will reinstall the operating system but delete all your apps and data from the computer. So, backup any data you need before attempting a clean install.

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fixing the Memory Diagnostic Tool "Hardware Problem Detected" Error

 When an error is detected with your memory modules, the Windows Memory Diagnostic tool will show an error. While memory-related issues are often due to faulty hardware, make sure to run the device hardware troubleshooter to detect and resolve minor glitches.

 Alternatively, perform a memory integrity check using the Memtest86 tool. If the memory modules pass the Memtest86, you may need to perform a Windows OS clean install to fix issues with the Windows system files.

 This error can be a false positive. You can also confirm the same by using a third-party memory diagnostic tool. In case of a hardware issue, you may need to replace the memory stick or repair the memory slot, if possible.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-essential-guide-to-compositing-using-blending-modes/"><u>[New] 2024 Approved  Essential Guide to Compositing Using Blending Modes</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-navigating-the-world-of-online-broadcasts-on-youtube-and-twitch-with-obs-for-2024/"><u>[New] Navigating the World of Online Broadcasts on YouTube and Twitch with OBS for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-sync-your-speech-with-visuals-the-art-of-ppt-voiceovers/"><u>[New] Sync Your Speech with Visuals  The Art of PPT Voiceovers</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-transform-your-facebook-vids-to-mp3-easy-and-fast/"><u>[New] Transform Your Facebook Vids to MP3 - Easy & Fast</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-concealed-visibility-mastering-visual-obscurity-in-videos/"><u>[Updated] Concealed Visibility  Mastering Visual Obscurity in Videos</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-excellence-in-auditory-theatre-writing/"><u>[Updated] Excellence in Auditory Theatre Writing</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-achieving-clear-communication-on-skype/"><u>[Updated] In 2024, Achieving Clear Communication on Skype</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-innovating-human-interface-a-guide-to-hand-perception/"><u>[Updated] Innovating Human Interface  A Guide to Hand Perception</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/6-methods-to-mirror-apple-iphone-xs-to-your-windows-pc-drfone-by-drfone-ios/"><u>6 Methods to Mirror Apple iPhone XS to your Windows PC | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/debugging-0xc00ce556-the-winoss-parsing-quest/"><u>Debugging 0xC00CE556: The WinOSs Parsing Quest</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detailed-steps-for-manipulating-windows-registry-command-line/"><u>Detailed Steps for Manipulating Windows Registry Command Line</u></a></li>
<li><a href="https://facebook.techidaily.com/digital-dynamics-redefined-the-top-4-platform-driven-changes-afoot/"><u>Digital Dynamics Redefined: The Top 4 Platform-Driven Changes Afoot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-controls-in-windows-11s-ui-amenities/"><u>Elevate Controls in Windows 11'S UI Amenities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-xbox-audio-quality-within-windows-11-framework/"><u>Elevating Xbox Audio Quality Within Windows 11 Framework</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-playtime-windows-troubleshooting-for-fullscreen-games/"><u>Enhance Playtime: Windows Troubleshooting for Fullscreen Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-the-visibility-of-search-outcomes-in-windows-1011/"><u>Enhancing the Visibility of Search Outcomes in Windows 10/11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/exclusive-selection-of-the-top-4k-capture-apps-for-2024/"><u>Exclusive Selection of the Top 4K Capture Apps for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-blocked-by-administrator-in-windows-os/"><u>Fixing Blocked by Administrator in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-steam-library-error-inability-to-sync-files/"><u>Fixing Steam Library Error: Inability to Sync Files</u></a></li>
<li><a href="https://fake-location.techidaily.com/full-guide-to-fix-itoolab-anygo-not-working-on-oppo-reno-11f-5g-drfone-by-drfone-virtual-android/"><u>Full Guide to Fix iToolab AnyGO Not Working On Oppo Reno 11F 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halting-secondary-apps-camera-usage-code-0xa00f4243/"><u>Halting Secondary App's Camera Usage: Code 0xA00F4243</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-can-we-unlock-our-oneplus-nord-n30-se-phone-screen-by-drfone-android/"><u>How Can We Unlock Our OnePlus Nord N30 SE Phone Screen?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-does-windows-11s-new-backup-feature-work/"><u>How Does Windows 11'S New Backup Feature Work?</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-fix-iphone-11-pro-passcode-not-working-drfone-by-drfone-ios/"><u>How to Fix iPhone 11 Pro Passcode not Working? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-honor-magic5-ultimate-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Honor Magic5 Ultimate to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-fake-gps-location-apps-on-android-of-your-oppo-find-x7-ultra-drfone-by-drfone-virtual/"><u>In 2024, 10 Fake GPS Location Apps on Android Of your Oppo Find X7 Ultra | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-oppo-reno-9a-drfone-by-drfone-virtual-android/"><u>In 2024, How to get the dragon scale and evolution-enabled pokemon On Oppo Reno 9A? | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-innovative-copywriting-routines-adopting-three-key-approaches-to-fb-advertising/"><u>In 2024, Innovative Copywriting Routines  Adopting Three Key Approaches to FB Advertising</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-masterful-ways-of-scrolling-through-appreciated-youtube-feedback/"><u>In 2024, Masterful Ways of Scrolling Through Appreciated YouTube Feedback</u></a></li>
<li><a href="https://tech-haven.techidaily.com/investigating-truthgpt-coin-how-to-tell-if-its-a-scam-or-not/"><u>Investigating TruthGPT Coin - How to Tell If It's A Scam Or Not</u></a></li>
<li><a href="https://win11-tips.techidaily.com/investigating-windows-11s-core-data-the-hidden-registry/"><u>Investigating Windows 11'S Core Data: The Hidden Registry</u></a></li>
<li><a href="https://facebook.techidaily.com/maintaining-professionalism-blocking-negative-profiles-from-fb/"><u>Maintaining Professionalism: Blocking Negative Profiles From FB</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-network-issues-with-ea-games-on-pc/"><u>Mastering Network Issues with EA Games on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-outlook-repair-a-windows-users-manual/"><u>Mastering Outlook Repair: A Windows User's Manual</u></a></li>
<li><a href="https://sound-issues.techidaily.com/overcoming-connectivity-issues-with-the-lucidsound-ls30-microphone/"><u>Overcoming Connectivity Issues with the LucidSound LS30 Microphone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-obstacles-fixing-windows-setup-fails/"><u>Overcoming Obstacles: Fixing Windows Setup Fails</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-mystery-of-windows-subsystem-for-linuxs-error-4294967295/"><u>Overcoming the Mystery of Windows Subsystem for Linux's Error 4294967295</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/practical-steps-for-smooth-recording-of-remote-workshops-on-windowsapple-systems/"><u>Practical Steps for Smooth Recording of Remote Workshops on Windows/Apple Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/qbittorrent-migration-a-practical-guide-to-preserve-settings/"><u>QBittorrent Migration: A Practical Guide to Preserve Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-icon-alert-visibility-in-windows/"><u>Regaining Icon Alert Visibility in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedies-for-dead-input-devices-in-windows-os/"><u>Remedies for Dead Input Devices in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-insufficient-privilege-install-error-on-win-1110/"><u>Resolving Insufficient Privilege Install Error on Win 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-non-startup-of-netflix-in-windows/"><u>Reversing Non-Startup of Netflix in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sidestep-the-initializing-wow-snag/"><u>Sidestep the Initializing WoW Snag</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-microphone-issues-with-xbox-app-on-pc/"><u>Solutions to Microphone Issues with Xbox App on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-address-failed-windows-app-deployments/"><u>Steps to Address Failed Windows App Deployments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-alter-your-windows-cursor-on-pc/"><u>Steps to Alter Your Window's Cursor on PC</u></a></li>
<li><a href="https://extra-resources.techidaily.com/strategies-to-keep-windows-11-photos-app-running-smoothly/"><u>Strategies to Keep Windows 11 Photos App Running Smoothly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-virtual-machines-on-windows-6-performance-tweaks/"><u>Streamline Virtual Machines on Windows: 6 Performance Tweaks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/subsys-end-prepare-seamless-switch-to-new-android-setup-methods/"><u>Subsys End, Prepare: Seamless Switch to New Android Setup Methods</u></a></li>
<li><a href="https://change-location.techidaily.com/the-most-useful-tips-for-pokemon-go-ultra-league-on-vivo-v27-pro-drfone-by-drfone-virtual-android/"><u>The Most Useful Tips for Pokemon Go Ultra League On Vivo V27 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-upgrade-new-features-in-microsoft-paint/"><u>The Ultimate Upgrade: New Features in Microsoft Paint</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-call-history-from-huawei-p60-by-fonelab-android-recover-call-logs/"><u>The way to get back lost call history from Huawei P60</u></a></li>
<li><a href="https://win11-tips.techidaily.com/times-tangle-in-windows-restore-clock-order/"><u>Time's Tangle in Windows: Restore Clock Order</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-addressing-the-application-couldnt-start-xc000003e/"><u>Understanding and Addressing The Application Couldn't Start XC000003E</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unifying-powertoys-across-computers/"><u>Unifying PowerToys Across Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-secret-of-smooth-typing-in-powertoys/"><u>Unlock the Secret of Smooth Typing in PowerToys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-full-potential-of-windows-11s-5g-capability/"><u>Unlocking Full Potential of Windows 11'S 5G Capability</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/updated-2024-approved-free-msnbc-live-online-stream-for-the-latest-shows-for-all-devices/"><u>Updated 2024 Approved Free MSNBC Live Online Stream for the Latest Shows for All Devices</u></a></li>
</ul></div>
