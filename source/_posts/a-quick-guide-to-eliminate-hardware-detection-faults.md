---
title: A Quick Guide to Eliminate Hardware Detection Faults
date: 2024-07-12T17:51:45.484Z
updated: 2024-07-13T17:51:45.484Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Quick Guide to Eliminate Hardware Detection Faults
excerpt: This Article Describes A Quick Guide to Eliminate Hardware Detection Faults
keywords: HW Fault Elimination Guide,Detect & Fix Hardware Issues,Hardware Troubleshooting Tips,Avoid Hardware Detection Errors,Quick Hardware Problem Solving,Navigating Hardware Malfunctions,Effective HW Fault Remediation
thumbnail: https://thmb.techidaily.com/a929b0d993c705dcd1293af7219e5e597567df393d17dd26d0130a00b3701a6a.JPG
---

## A Quick Guide to Eliminate Hardware Detection Faults

 Using the Windows Memory Diagnostic tool, you can diagnose memory issues on your Windows computer. If there is a problem, it will return an error. One common Windows Memory Diagnostic error you may encounter is "Hardware problems were detected; contact manufacturer," followed by the "You have a memory problem" dialog.

 This error can be a false positive. You can also confirm the same by using a third-party memory diagnostic tool. In case of a hardware issue, you may need to replace the memory stick or repair the memory slot, if possible.

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

## 5\. Perform a Repair Reinstall or Clean Install Windows

 If the Windows Memory Diagnostic tool continues to show the hardware problem was detected error, even after the Memtest86+ passed the test, check if the problem is due to issues with the Windows operating system.

 To fix critical issues with your Windows image, you can perform a [repair reinstall of Windows 11 without deleting apps](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/). If that does not work, perform a clean install. This will reinstall the operating system but delete all your apps and data from the computer. So, backup any data you need before attempting a clean install.

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
<li><a href="https://youtube-stream.techidaily.com/2024-approved-simplified-blue-screen-usage-guide/"><u>2024 Approved  Simplified Blue Screen Usage Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-ways-to-check-for-open-tcpip-ports-on-windows/"><u>3 Ways to Check for Open TCP/IP Ports on Windows</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-top-live-audio-alteration-systems-the-best/"><u>Updated In 2024, Top Live Audio Alteration Systems The Best</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-iphone-xs-without-passcode-4-easy-methods-by-drfone-ios/"><u>In 2024, How To Unlock iPhone XS Without Passcode? 4 Easy Methods</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-best-of-breed-exceptional-cardboard-vr-gaming-experienits/"><u>2024 Approved  Best of Breed  Exceptional Cardboard VR Gaming Experienits</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/rootjunky-apk-to-bypass-google-frp-lock-for-realme-12-proplus-5g-by-drfone-android/"><u>Rootjunky APK To Bypass Google FRP Lock For Realme 12 Pro+ 5G</u></a></li>
<li><a href="https://some-skills.techidaily.com/venture-into-virtuality-comprehensively-reviewing-top-10-vr-streamers-for-2024/"><u>Venture Into Virtuality  Comprehensively Reviewing Top 10 VR Streamers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-chkdsk-sfc-vs-dism-in-os-maintenance/"><u>Understanding CHKDSK, SFC Vs. DISM in OS Maintenance</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-panorama-pioneers-determining-the-best-360-cams/"><u>[New] Panorama Pioneers  Determining the Best 360 Cams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-alteration-of-nat-types-in-windows-operating-systems/"><u>Effective Alteration of NAT Types in Windows Operating Systems</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-professional-drone-selection-guide-top-5/"><u>2024 Approved  Professional Drone Selection Guide (Top 5)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-advice-on-resolving-windows-error-code-0xc0000001/"><u>Expert Advice on Resolving Windows Error Code 0XC0000001</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrading-to-optimal-windows-audios-through-driver-revision/"><u>Upgrading to Optimal Windows Audios Through Driver Revision</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-join-the-fun-hot-tiktok-challenges-await-for-2024/"><u>[New] Join the Fun  Hot TikTok Challenges Await for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-2024-approved-3-best-effects-to-appear-on-camera-made-with-filmora/"><u>New 2024 Approved 3 Best Effects to Appear on Camera Made with Filmora</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-cleanse-your-computer-of-previous-security-audits/"><u>How to Cleanse Your Computer of Previous Security Audits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cure-for-unresponsive-wired-gaming-accessories/"><u>Cure for Unresponsive Wired Gaming Accessories</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-windows-11-password-strategy/"><u>Transforming Windows 11 Password Strategy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-steps-to-correct-windows-operating-system-office-errors/"><u>Immediate Steps to Correct Windows Operating System Office Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-strategies-to-fix-windows-error-code-0x800704b3/"><u>Effective Strategies to Fix Windows' Error Code: 0X800704B3</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-ultimate-guide-to-transforming-views-into-revenue/"><u>2024 Approved  The Ultimate Guide to Transforming Views Into Revenue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customize-your-computing-conduct-setting-active-hours-to-mitigate-updates-in-windows-11/"><u>Customize Your Computing Conduct: Setting Active Hours to Mitigate Updates in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-credential-store-lockups-on-pcs/"><u>Fix Credential Store Lockups on PCs</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/best-3d-entrance-makers-for-youtube-creators/"><u>Best 3D Entrance Makers for YouTube Creators</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/complete-fixes-to-solve-iphone-xr-randomly-asking-for-apple-id-password-drfone-by-drfone-ios/"><u>Complete Fixes To Solve iPhone XR Randomly Asking for Apple ID Password | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insights-into-windows-patch-identification/"><u>Insights Into Window's Patch Identification</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-dungeon-dominance-top-ten-rogue-classics/"><u>[Updated] 2024 Approved  Dungeon Dominance  Top Ten Rogue Classics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/circumventing-non-changeable-sleepwake-modes-in-windows-11/"><u>Circumventing Non-Changeable Sleep/Wake Modes in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-the-top-6-computer-utilization-monitors-on-pcs/"><u>Discover the Top 6 Computer Utilization Monitors on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detailed-guide-to-overcoming-steam-auth-problems-with-rust-on-windows/"><u>Detailed Guide to Overcoming Steam Auth Problems with Rust on Windows</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-incorporating-yt-playlists-into-web-design/"><u>2024 Approved  Incorporating YT Playlists Into Web Design</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-win1011-recycle-bin-repair-strategies/"><u>Mastering WIN10/11 Recycle Bin Repair Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-internal-error-in-windows-11-remote/"><u>Mastering the Art of Fixing Internal Error in Windows 11 Remote</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tweak-viewer-direction-on-windows-monitor/"><u>Tweak Viewer Direction on Windows Monitor</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713949550761-do-you-want-to-print-designs-onto-your-garments-or-other-fashion-accessories-find-out-how-to-create-a-screen-print-effect-in-photoshop-to-give-your-text-or-/"><u>Do You Want to Print Designs Onto Your Garments or Other Fashion Accessories? Find Out How to Create a Screen Print Effect in Photoshop to Give Your Text or Graphics a Vintage or Retro Look for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-the-leading-free-software-for-quality-desktop-recording/"><u>[New] 2024 Approved  The Leading Free Software for Quality Desktop Recording</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-elevate-your-videos-how-to-find-and-use-free-sound-effects-in-final-cut-pro-for-2024/"><u>Updated Elevate Your Videos How to Find and Use Free Sound Effects in Final Cut Pro for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/create-individualized-keystroke-rules-in-windows-11/"><u>Create Individualized Keystroke Rules in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-functionality-of-microsofts-phone-link-an-introduction/"><u>The Functionality of Microsoft's 'Phone Link': An Introduction</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-spotlight-on-the-top-8-authentic-video-promotion-methods/"><u>2024 Approved  Spotlight on the Top 8 Authentic Video Promotion Methods</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-instant-influence-youtubes-hourly-video-tops/"><u>2024 Approved  Instant Influence  Youtube's Hourly Video Tops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-for-loss-of-pin-access-in-windows-11-post-update-fallout/"><u>Fix for Loss of PIN Access in Windows 11 Post-Update Fallout</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-quickly-enable-or-disable-bing-chat-ai-in-windows-11-taskbar-search/"><u>How to Quickly Enable or Disable Bing Chat AI in Windows 11 Taskbar Search</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augment-windows-management-with-a-disk-space-analysis-tool/"><u>Augment Windows Management with a Disk Space Analysis Tool</u></a></li>
<li><a href="https://techidaily.com/factory-reset-on-apple-iphone-14-pro-max-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>Factory Reset on Apple iPhone 14 Pro Max | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-win-10s-cc-troubleshooting/"><u>Essential Tips for Win 10'S CC Troubleshooting</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-solutions-to-hard-reset-oppo-find-x6-pro-phone-using-pc-drfone-by-drfone-reset-android-reset-android/"><u>3 Solutions to Hard Reset Oppo Find X6 Pro Phone Using PC | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-3-innovative-ways-for-windows-hardware-id-access/"><u>Exploring 3 Innovative Ways for Windows Hardware ID Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-windows-net-runtime-requirement-hurdle/"><u>Avoiding Windows' .NET Runtime Requirement Hurdle</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-hidefake-snapchat-location-on-your-oppo-a78-5g-drfone-by-drfone-virtual-android/"><u>How to Hide/Fake Snapchat Location on Your Oppo A78 5G | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/proven-ways-to-fix-there-was-a-problem-parsing-the-package-on-honor-90-lite-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Proven Ways to Fix There Was A Problem Parsing the Package on Honor 90 Lite | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/av1-compression-a-beginners-overview/"><u>AV1 Compression  A Beginner's Overview</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-files-write-access-no-more-restrictions/"><u>Adjusting Windows Files: Write Access No More Restrictions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gearing-up-with-best-laptops-from-ifa-2023/"><u>Gearing Up with Best Laptops From IFA 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-persistence-of-user-defined-volume-mixer/"><u>Ensuring Persistence of User-Defined Volume Mixer</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-elevate-your-storytelling-how-to-add-professional-3d-effects-to-your-windows-videos-for-2024/"><u>New Elevate Your Storytelling How to Add Professional 3D Effects to Your Windows Videos for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-interactive-presenters-synopsis-update-8/"><u>[Updated] In 2024, Interactive Presenter's Synopsis, Update 8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cut-down-clutter-tackling-large-storage-consumers-in-windows/"><u>Cut Down Clutter: Tackling Large Storage Consumers in Windows</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-unleash-your-creativity-gopro-video-editing-on-mac-for-beginners-for-2024/"><u>New Unleash Your Creativity GoPro Video Editing on Mac for Beginners for 2024</u></a></li>
</ul></div>
