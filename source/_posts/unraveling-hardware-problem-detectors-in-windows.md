---
title: Unraveling Hardware Problem Detectors in Windows
date: 2024-09-12T01:05:02.823Z
updated: 2024-09-17T08:04:59.986Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unraveling Hardware Problem Detectors in Windows
excerpt: This Article Describes Unraveling Hardware Problem Detectors in Windows
keywords: Windows Hardware Diag,PC Troubleshoot Win,System Error Fixer,Device Detection Win,Hardware Finder Win,PC Health Monitoring,Detect & Repair Win
thumbnail: https://thmb.techidaily.com/1b6d7be592f2912a27c2919b7274dc65400897b1c72eb15814464402850a760a.jpg
---

## Unraveling Hardware Problem Detectors in Windows

 Using the Windows Memory Diagnostic tool, you can diagnose memory issues on your Windows computer. If there is a problem, it will return an error. One common Windows Memory Diagnostic error you may encounter is "Hardware problems were detected; contact manufacturer," followed by the "You have a memory problem" dialog.

 This error can be a false positive. You can also confirm the same by using a third-party memory diagnostic tool. In case of a hardware issue, you may need to replace the memory stick or repair the memory slot, if possible.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Causes the Windows Memory Diagnostic Hardware Problems Were Detected Error?

 This error is often triggered after a blue screen of death (BSOD) or the system freezing issues. The reason for the error can vary and include faulty memory slots and memory sticks. It can also be a false positive due to a Windows OS glitch.

## 1\. Check for Overclocking Issues

 Incorrect overclocking can cause hardware issues. While faster RAM can help you achieve good performance, it is important to consider the hardware limitations before applying the tweaks.

 If you have overclocked your RAM, try to lower the frequencies to see if the error goes away. Do this until you find a safe frequency, or reset it to factory default settings.

 If you are unsure about the default memory frequencies, try to perform a BIOS reset. Load the BIOS default, which should reset the RAM frequencies to its factory default. Refer to your motherboard manufacturer manual for specific instructions.

## 2\. Run the Hardware Troubleshooter

 The built-in Windows hardware troubleshooter can scan for hardware-related issues and even try to perform a repair if possible. If you haven’t tried already, run the hardware troubleshooter using the Command Prompt to resolve the problem.

 Note that it is a legacy troubleshooter, and you may not find it in the Windows 11 version newer than 22H2\.

 To run the Windows Hardware Troubleshooter:

1. Press the **Win** key and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator**. Click **Yes** if prompted by the User Account Control dialog.  
![run windows hardware troubleshooter command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-windows-hardware-troubleshooter-command-prompt.jpg)
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118319/7443" target="_top" id="2118319">
  <img src="//a.impactradius-go.com/display-ad/7443-2118319" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118319/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
7. Next, plug the Memtest86+ bootable USB drive into your computer and turn it on.
8. Boot into the Boot Menu and select the bootable USB drive as the boot device. The hotkey key to enter the Boot Menu may vary depending on your computer manufacturer. You can press **F9** on an **HP** computer, **F12** on a **Dell** computer and so on to access the **Boot Menu**.
9. Memtest86+ will automatically start the memory integrity check. Let Memtest86+ complete at least 2 passes; the more, the better. Press the **Esc** key to stop the test if there are no errors after multiple passes.

 If an error is detected during testing, it is likely a case of faulty RAM and may need replacement. But to be on the safer side, ensure you test each RAM separately to find the odd one out.

 Not all the errors detected by the Memtest86+ are due to faulty hardware. Some errors may occur due to compatibility issues. Check your RAM module and the motherboard specifications to determine any compatibility issues. You can also test the RAM modules by inserting them into a different motherboard and see if it works.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123732/7443" target="_top" id="2123732">
  <img src="//a.impactradius-go.com/display-ad/7443-2123732" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123732/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Perform a Repair Reinstall or Clean Install Windows

 If the Windows Memory Diagnostic tool continues to show the hardware problem was detected error, even after the Memtest86+ passed the test, check if the problem is due to issues with the Windows operating system.

 To fix critical issues with your Windows image, you can perform a [repair reinstall of Windows 11 without deleting apps](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/). If that does not work, perform a clean install. This will reinstall the operating system but delete all your apps and data from the computer. So, backup any data you need before attempting a clean install.

## Fixing the Memory Diagnostic Tool "Hardware Problem Detected" Error

 When an error is detected with your memory modules, the Windows Memory Diagnostic tool will show an error. While memory-related issues are often due to faulty hardware, make sure to run the device hardware troubleshooter to detect and resolve minor glitches.

 Alternatively, perform a memory integrity check using the Memtest86 tool. If the memory modules pass the Memtest86, you may need to perform a Windows OS clean install to fix issues with the Windows system files.

 This error can be a false positive. You can also confirm the same by using a third-party memory diagnostic tool. In case of a hardware issue, you may need to replace the memory stick or repair the memory slot, if possible.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-mastering-custom-whatsapp-ringtone-for-ios-and-android-users/"><u>2024 Approved Mastering Custom WhatsApp Ringtone for iOS and Android Users</u></a></li>
<li><a href="https://howto.techidaily.com/app-wont-open-on-your-honor-magic-5-lite-here-are-all-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>App Wont Open on Your Honor Magic 5 Lite? Here Are All Fixes | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/creating-convenience-microsoft-store-links-for-windows-11-uwp/"><u>Creating Convenience: Microsoft Store Links for Windows 11 (UWP)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-discord-installer-faults-on-pc-and-laptop/"><u>Eradicating Discord Installer Faults on PC & Laptop</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/facebooks-stance-on-personal-content-distribution-in-the-digital-age/"><u>Facebook's Stance on Personal Content Distribution in the Digital Age</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-unrequested-launch-of-msdnstoreapp/"><u>Fixing the Unrequested Launch of MSDN/StoreApp</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harnessing-windows-tools-for-device-serial-numbers/"><u>Harnessing Windows Tools for Device Serial Numbers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-a-slow-download-speed-in-battlenet-for-windows/"><u>How to Fix a Slow Download Speed in Battle.net for Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-whatsapp-messages-on-samsung-galaxy-s23-fe-without-them-knowing-drfone-by-drfone-virtual-android/"><u>How to Track WhatsApp Messages on Samsung Galaxy S23 FE Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-windows-keys-a-solution-guide-for-win10/"><u>Master Your Windows Keys: A Solution Guide for WIN10</u></a></li>
<li><a href="https://tech-haven.techidaily.com/new-york-times-puzzles-insightful-clues-and-solutions-from-todays-edition-may-19th/"><u>New York Times Puzzles - Insightful Clues & Solutions From Today’s Edition, May 19Th</u></a></li>
<li><a href="https://win-able.techidaily.com/quick-solutions-for-fixing-ring-of-elysiums-persistent-crash-problem/"><u>Quick Solutions for Fixing Ring of Elysium's Persistent Crash Problem</u></a></li>
<li><a href="https://win-solutions.techidaily.com/revolutionary-audio-precision-from-microsoft-now-available-on-a-wider-range-of-desktops-and-laptops/"><u>Revolutionary Audio Precision From Microsoft Now Available on a Wider Range of Desktops and Laptops</u></a></li>
<li><a href="https://extra-hints.techidaily.com/simplest-way-win-clownfish-vocal-alteration-tool/"><u>Simplest Way Win Clownfish Vocal Alteration Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winter-wonderland-windows-celebrate-the-holiday-season/"><u>Winter Wonderland Windows: Celebrate the Holiday Season</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    