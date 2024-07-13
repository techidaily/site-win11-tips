---
title: 4 Easy Steps to Wipe Your Drive's Partitions in Windows
date: 2024-07-12T16:30:07.447Z
updated: 2024-07-13T16:30:07.447Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 4 Easy Steps to Wipe Your Drive's Partitions in Windows
excerpt: This Article Describes 4 Easy Steps to Wipe Your Drive's Partitions in Windows
keywords: Wipe Windows Drive,Cleanup Windows Hardware,Delete Windows Partition,Erase Windows Storage,Clear Windows Drive Space,Format Windows Devices,Reset Windows Drives
thumbnail: https://thmb.techidaily.com/2579e58fb859f12bcf75d41bfcd2bb7289ef81a099867df0bbc5e1bf070a408f.jpg
---

## 4 Easy Steps to Wipe Your Drive's Partitions in Windows

 Your Windows computer provides several options for deleting unwanted drive partitions, whether you are looking to consolidate space, restructure data allocation, or simply start over. However, before you do that, make sure to backup or move any important data on the partition, as the process removes all the data on the drive.

 This guide will show you how to delete a drive partition using the Settings app, Disk Management tool, Command Prompt, and PowerShell.

## 1\. How to Delete a Drive Partition on Windows Using the Settings App

 The Windows Settings app makes it easy to manage drive partitions and perform advanced storage-related tasks. It also provides the most straightforward way to delete a drive partition on Windows.To delete a drive partition via the Settings app:

1. Press **Win + I** to open the Settings app.
2. In the **System** tab, click on **Storage**.
3. Expand **Advanced storage settings** and click **Disks & volumes**.
4. Click the **Properties** button next to the drive you wish to delete.
5. Under the **Format** section, click the **Delete** button.
6. Select **Delete volume** to confirm.  
![Delete a Drive Partition Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-settings-app.jpg)

 Once you complete the steps, the partition and everything on it will be gone.

## 2\. How to Delete a Drive Partition on Windows Using the Disk Management Utility

 Another way to delete a drive partition on Windows is via the Disk Management tool. If you want to use that, follow these steps:

1. Press **Win + R** to open the Run dialog box.
2. Type **diskmgmt.msc** in the text field and press **Enter**.
3. In the Disk Management window, right-click the unwanted partition and click the **Delete Volume** option.
4. Select **Yes** to confirm.  
![Delete a Drive Partition Using the Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-disk-management-tool.jpg)

 Don't want to get rid of a drive altogether? You can also choose to [hide the drive on Windows](https://www.makeuseof.com/how-to-hide-a-drive-in-windows/) using the Disk Management tool.

## 3\. How to Delete a Drive Partition on Windows With the Command Prompt

 Not a fan of GUI? No problem. Windows also lets you delete a drive partition using the Command Prompt. Here are the steps for the same.

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the menu that appears.
2. Select **Yes** when the User Account Control (UAC) prompt shows up.
3. In the console, run the following commands to view a list of drives connected to your system.  
`diskpart  
list volume`
4. Note down the number associated with the drive you want to delete in the **Volume** column.
5. Type the following command and press **Enter** to select the volume. Make sure you replace **N** in the command with the drive number noted earlier.  
`select volume N`
6. Copy and paste the following command and press **Enter** to delete the partition.  
`delete volume`  
![Delete a Drive Partition Using the Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-command-prompt.jpg)

 Enjoy working with the Command Prompt? If so, you will surely love our guide on [customizing the Command Prompt on Windows](https://www.makeuseof.com/windows-customize-command-prompt/).

## 4\. How to Delete a Drive Partition on Windows via PowerShell

 Windows PowerShell is another command-line tool that you can use to delete a disk partition. Here are the steps you need to follow.

1. Press **Win + S** to open the search menu.
2. Type in **Windows PowerShell** and select **Run as administrator**.
3. Select **Yes** when the User Account Control (UAC) prompt appears to [open PowerShell with admin rights](https://www.makeuseof.com/windows-powershell-always-open-as-administrator/).
4. Run the following command to view a list of drives on your PC:  
`Get-volume`
5. Note down the letter assigned to the drive you want to delete in the **DriveLetter** column.
6. Copy and paste the following command to delete the partition. Replace **X** in the command with the actual drive letter noted in the previous step.  
`Remove-Partition -DriveLetter X`
7. Type **Y** and press **Enter** to confirm.  
![Delete a Drive Partition Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-powershell.jpg)

 Once you run the above commands, PowerShell will delete the specified partition.

## There Are Many Ways to Delete Drive Partitions on Windows

 As we just saw, deleting a drive partition on Windows is a simple process, regardless of the method you use. Once you delete a partition, the space on that drive will be unallocated. You can then create a new partition on the empty space or use the space to expand an existing partition.

 This guide will show you how to delete a drive partition using the Settings app, Disk Management tool, Command Prompt, and PowerShell.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/discovering-devhome-your-nexus-for-windows-11-innovation/"><u>Discovering DevHome: Your Nexus for Windows 11 Innovation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-dns-configuration-process-on-windows-11/"><u>Navigating the DNS Configuration Process on Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-google-play-location-on-lava-yuva-3-drfone-by-drfone-virtual-android/"><u>How to Change Google Play Location On Lava Yuva 3 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-forth-forgotten-windows-top-6-techniques-in-win11/"><u>Bringing Forth Forgotten Windows: Top 6 Techniques in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-techniques-to-open-wordpad-in-windows/"><u>Essential Techniques to Open WordPad in Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-easily-unlock-your-infinix-zero-5g-2023-turbo-device-sim-by-drfone-android/"><u>In 2024, Easily Unlock Your Infinix Zero 5G 2023 Turbo Device SIM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-troubled-waters-in-windows-mail-app-with-0x800713f/"><u>Navigating Through Troubled Waters in Windows Mail App with 0X800713F</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-time-sync-techniques-in-video-editing-creating-beats-aligned-cuts-with-premiere-pro-for-modern-filmmakers/"><u>Updated 2024 Approved Time-Sync Techniques in Video Editing Creating Beats-Aligned Cuts with Premiere Pro for Modern Filmmakers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterclass-in-microsoft-essential-gratis-tools-for-win11/"><u>Masterclass in Microsoft: Essential Gratis Tools for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-exiting-wows-unprecedented-crash-132/"><u>Guide to Exiting WoW’s Unprecedented Crash 132</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-exploring-the-finest-text-to-speech-male-voice-tools-for-natural-output/"><u>New Exploring the Finest Text-to-Speech Male Voice Tools for Natural Output</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-actions-for-disabled-windows-update-service/"><u>Immediate Actions for Disabled Windows Update Service</u></a></li>
<li><a href="https://techidaily.com/stellar-data-recovery-for-iphone-12-pro-max-failed-to-recognize-my-iphone-how-to-fix-it-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Stellar Data Recovery for iPhone 12 Pro Max failed to recognize my iPhone. How to fix it? | Stellar</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-get-and-use-pokemon-go-promo-codes-on-vivo-y27-4g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Get and Use Pokemon Go Promo Codes On Vivo Y27 4G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/learn-how-to-setup-touch-typing-feature-on-your-windows-device/"><u>Learn How To Setup Touch Typing Feature on Your Windows Device</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-master-the-art-of-console-game-recording-with-computer-assistance/"><u>2024 Approved  Master the Art of Console Game Recording with Computer Assistance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimize-lag-and-enhance-fps-in-roblox-win-edition/"><u>Minimize Lag & Enhance FPS in Roblox Win Edition</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-unlocking-an-icloud-locked-ipad-and-apple-iphone-15-pro-by-drfone-ios/"><u>In 2024, Unlocking an iCloud Locked iPad and Apple iPhone 15 Pro</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-disengage-from-discord-services/"><u>[Updated] 2024 Approved  Disengage From Discord Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-usb-drive-errors-windows-tips/"><u>Eliminating USB Drive Errors: Windows Tips</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ideo-excellence-started-with-quality-cameras-and-lenses/"><u>[New] Video Excellence Started with Quality Cameras and Lenses</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-easy-guide-how-to-bypass-xiaomi-14-frp-android-10111213-by-drfone-android/"><u>In 2024, Easy Guide How To Bypass Xiaomi 14 FRP Android 10/11/12/13</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-2024-approved-time-lapse-magic-the-best-apps-for-capturing-stunning-videos-on-iphone-and-android/"><u>Updated 2024 Approved Time-Lapse Magic The Best Apps for Capturing Stunning Videos on iPhone and Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11s-voice-commands-keyboard-shortcut-essentials/"><u>Mastering Windows 11'S Voice Commands: Keyboard Shortcut Essentials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-traditional-visuals-the-iconic-window-11-search-return/"><u>Bringing Traditional Visuals: The Iconic Window 11 Search Return</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-net-speeds-unlock-efficient-adapter-checking/"><u>Navigate Net Speeds: Unlock Efficient Adapter Checking</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-effortless-device-integration-with-obs-for-streaming-on-pcmac/"><u>[New] In 2024, Effortless Device Integration with OBS for Streaming on PC/Mac</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-top-independent-game-apps-for-screen-free-android-playing/"><u>2024 Approved  Top Independent Game Apps for Screen-Free Android Playing</u></a></li>
<li><a href="https://article-helps.techidaily.com/most-esteemed-ios-tone-artisans/"><u>Most Esteemed iOS Tone Artisans</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-unpair-and-reconnect-devices-effortlessly-on-win-11/"><u>How to Unpair and Reconnect Devices Effortlessly on Win 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-evaluating-toolwiz-in-a-world-of-mobile-photography-apps/"><u>2024 Approved  Evaluating Toolwiz in a World of Mobile Photography Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reinstate-windows-photo-viewer-on-win11-pcs/"><u>How to Reinstate Windows Photo Viewer on Win11 PCs</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-your-apple-iphone-7-passcode-4-easy-methods-with-or-without-itunes-by-drfone-ios/"><u>In 2024, How to Unlock Your Apple iPhone 7 Passcode 4 Easy Methods (With or Without iTunes)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/memory-and-cpu-efficiency-in-browsers-a-windowsmacoschromeos-comparison/"><u>Memory and CPU Efficiency in Browsers: A Windows/macOS/ChromeOS Comparison</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-code-0x800f0831-the-key-to-smooth-windows/"><u>Decoding Code 0X800F0831: The Key to Smooth Windows</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-youtube-snippets-guide-essential-info-inside/"><u>[New] YouTube Snippets Guide  Essential Info Inside</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-a-step-by-step-roadmap-for-masterful-instagram-photos/"><u>2024 Approved  A Step-by-Step Roadmap for Masterful Instagram Photos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-screen-quiet-disable-win11-folders/"><u>Mastering Screen Quiet: Disable Win11 Folders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-windows-power-management-options/"><u>Exploring Windows' Power Management Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-action-steps-for-correcting-workspace-glitches-on-winos/"><u>Instant Action Steps for Correcting Workspace Glitches on WINOS</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-speaking-in-code-learn-discords-text-to-speech/"><u>[New] Speaking in Code  Learn Discord's Text-to-Speech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/declutter-your-drive-discovering-excessive-disk-space-consumers/"><u>Declutter Your Drive: Discovering Excessive Disk Space Consumers</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-converting-your-cellphone-to-a-diy-video-recorder-for-2024/"><u>[Updated] Converting Your Cellphone to a DIY Video Recorder for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-win-lsa-troubleshooting/"><u>Mastering the Art of Win LSA Troubleshooting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-small-icons-a-guide-for-your-win-11-desktop/"><u>Fixing Small Icons: A Guide for Your Win 11 Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-conquering-system-calls-failure-in-windows-11/"><u>Expert Tips for Conquering System Calls Failure in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leading-emulators-selecting-best-windows-imitations-for-switch-games/"><u>Leading Emulators: Selecting Best Windows Imitations for Switch Games</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-treacle-tracking-step-by-step-tutorial-on-summer-snack-monitoring/"><u>2024 Approved  Treacle Tracking  Step-by-Step Tutorial on Summer Snack Monitoring</u></a></li>
<li><a href="https://howto.techidaily.com/8-workable-fixes-to-the-sim-not-provisioned-mm2-error-on-tecno-phantom-v-flip-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Workable Fixes to the SIM not provisioned MM#2 Error on Tecno Phantom V Flip | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-1110-setup-with-rightful-permissions/"><u>Navigating Windows 11/10 Setup with Rightful Permissions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-starting-wordpad-efficiently-on-windows/"><u>Essential Guide: Starting WordPad Efficiently on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mend-your-windows-overcome-geforce-experience-failures/"><u>Mend Your Windows: Overcome GeForce Experience Failures</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-easy-ways-to-manage-your-infinix-note-30-vip-racing-edition-location-settings-drfone-by-drfone-virtual/"><u>In 2024, Easy Ways to Manage Your Infinix Note 30 VIP Racing Edition Location Settings | Dr.fone</u></a></li>
</ul></div>
