---
title: Brightening Dull Cursors in UEFI
date: 2024-07-12T17:44:02.172Z
updated: 2024-07-13T17:44:02.172Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Brightening Dull Cursors in UEFI
excerpt: This Article Describes Brightening Dull Cursors in UEFI
keywords: Bright UEFI Cursors,Revive Cursor UI,Enhanced UEFI Cursors,Clear UEFI Icons,Dynamic Cursor UI,Improved UI Cursors,Clean UEFI Display
thumbnail: https://thmb.techidaily.com/e1e53d68e6a8bd97bb49ce774576b58cc661b7caf15fc6fdb1157408db40b882.jpg
---

## Brightening Dull Cursors in UEFI

 Newer computers come with Unified Extensible Firmware Interface (UEFI) as the new standard. However, Legacy BIOS is still largely part of most active systems due to legacy software and hardware support. Switching from UEFI to Legacy BIOS is easy using the firmware utility. But what if the legacy boot option is grayed out in BIOS?

 This can happen for a few reasons. A common reason for the grayed-out BIOS is if you have Secure Boot or Platform Trusted Technology (TPM) enabled. Issues with Modern Standby supported system is another reason that prevents you from switching from UEFI to Legacy BIOS.

 Here is how to fix the Legacy Boot grayed-out in BIOS issue on your Windows system.

## What Causes the Legacy Boot Grayed Out Problem?

 You may find the Legacy Boot option grayed out if the UEFI settings, such as Secure Boot and TPM are enabled in the BIOS utility. In some instances, the BIOS utility can tell you why you can't switch to the Legacy boot option.

 Boot into your BIOS utility and open**Advanced Boot** **Options** . Next, check the**Enable Legacy Option ROMs** option. You may see an error prompt explaining why the Legacy option cannot be enabled. It usually hints that PPT/TPM or Secure Boot is enabled.

 If you don't have any such option, try the troubleshooting steps below to restore the Legacy boot option in BIOS.

## 1\. Disable Secure Boot to Enable Boot

 Secure Boot is a UEFI feature that protects your computer against malware by allowing only trusted system software to run on your computer. When enabled, it will perform a cryptographic check during the boot process to verify the integrity of the system image.

 However, if you have Secure Boot enabled, it will likely disable Legacy Boot as well. You'll need to [disable Secure Boot in your BIOS utility](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/) to fix the issue.

 The below steps to disable Secure Boot are for an HP Pavilion computer. For other systems, refer to your system manual.

To disable secure boot:

1. Click on**Start** and then click on**Power** .
2. Press and hold the**Shift key** and click on**Restart** . Confirm the action if necessary.
3. Release the**Shift** key as the PC shuts down and boot into the**Recovery Menu.**
4. Go to**Troubleshoot** and click on**Advanced options** .
5. Next, click on**UEFI Firmware Settings.**  
![Advanced OptionspUEFI Firmware Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/advanced-optionspuefi-firmware-settings.jpg)

1. Click**Restart** to boot into the**Startup Menu.**  
![startup menu HP](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/startup-menu-hp-1.jpg)
2. In the Startup Menu, press**F10** to access the**BIOS Settings** . You may see other options depending on your computer manufacturer.
3. Use the right and left arrow keys to open the**Boot Options** tab in the BIOS Utility.
4. Next, use the up and down arrow key to highlight the**Secure Boot** option and press**Enter** to view more options.  
![disable secure boot bios](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-secure-boot-bios.jpg)
5. Select**Disabled** and make sure the changes are shown in the Boot Options tab.
6. Press**F10** to save the changes and disable Secure Boot.

## 2\. Disable Trusted Platform Technology (TPM)

![disable TPM state BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-tpm-state-bios-1.jpg)

 In addition to Secure Boot, you may also have enabled Trusted Platform Module (TPM), disabling Legacy BIOS. To fix the issue, check if TPM is enabled on your PC, which is likely a case on a Windows 11 running system, and disable the option if necessary.

 You can disable TPM from the BIOS setup utility. Here's how to do it.

1. Boot into your BIOS utility using the**Windows Recovery Menu.**
2. Next, open the**Security** tab using the right and left arrow keys.
3. Highlight the**TPM State** option and press**Enter** . If no TPM option is available, look for the**PTT** option.
4. Select**Disabled** to disable TPM on your device.
5. Press**F10** to save the change and exit.

## 3\. Disable Modern Standby

 Modern Standby (S0) is a newer power mode available on select modern computers. It is enabled by default on compatible systems but can cause issues with Legacy Boot.

 To fix the issue, try to [disable Modern Standby on your Windows computer](https://www.makeuseof.com/windows-disable-modern-standby/) . Once disabled, restart your PC to see if you can switch to Legacy Boot now.

## Restore a Grayed Out Legacy Boot Option in Your BIOS

 You can fix the grayed-out Legacy boot option in BIOS by disabling Secure Boot and Trusted Platform Technology. In addition, disable Standard Standby (S0) to fix the problem.

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
<li><a href="https://win11-tips.techidaily.com/mending-the-corrupted-file-issue-in-windows-11-os-error-0x80070570/"><u>Mending the Corrupted File Issue in Windows 11 OS (Error 0X80070570)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-cannot-access-source-file-in-win1110/"><u>Dealing with Cannot Access Source File in Win11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-window-updates-blocked-by-error-2e/"><u>Fix Window Updates Blocked by Error 2E</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/innovative-solutions-exceeding-standard-fbx-recorders-for-2024/"><u>Innovative Solutions Exceeding Standard FBX Recorders for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-effortless-edits-crafting-new-folders-on-windows-11/"><u>Explore Effortless Edits: Crafting New Folders on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-the-way-you-search-on-windows-11/"><u>Revamp the Way You Search on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-fatal-glitches-steps-to-fix-error-0x00000001-in-xbox-game-pass-for-windows-11/"><u>Overcoming Fatal Glitches: Steps to Fix Error 0X00000001 in Xbox Game Pass for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/historic-footprints-in-tech-rediscovering-7-old-world-windows-aspects/"><u>Historic Footprints in Tech: Rediscovering 7 Old-World Windows Aspects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-stop-nvidia-graphic-boost-features/"><u>Guide to Stop NVIDIA Graphic Boost Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reenergizing-your-dead-wireless-hotspot-in-windows-11/"><u>Reenergizing Your Dead Wireless Hotspot in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-launching-apps-on-windows-11/"><u>Efficiently Launching Apps on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lightning-bloatware-eradication-for-your-win11-system/"><u>Lightning Bloatware Eradication for Your Win11 System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reach-top-ssd-efficiency-in-windows-utilize-ssdfresh/"><u>Reach Top SSD Efficiency in Windows, Utilize SSDFresh</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-manual-for-registry-editing-with-command-prompt/"><u>Comprehensive Manual for Registry Editing with Command Prompt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improve-real-time-display-updates-for-win-11-task-tracker/"><u>Improve Real-Time Display Updates for Win 11 Task Tracker</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-elite-windows-apps-for-data-security-149-chars/"><u>7 Elite Windows Apps for Data Security (149 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-11s-fatal-0xf0831-malfunction/"><u>Bypassing Windows 11'S Fatal 0XF0831 Malfunction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-spotify-connections-on-windows-11-devices/"><u>Overcoming Spotify Connections on Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-communication-making-calls-on-windows-11-with-unison-app/"><u>Elevate Communication: Making Calls on Windows 11 with Unison App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-setup-service-via-command-line-utilities/"><u>Adjusting Setup Service via Command-Line Utilities</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-prime-pick-for-iphoneandroid-face-modifications/"><u>2024 Approved  Prime Pick for iPhone/Android Face Modifications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefine-your-digital-space-with-win-11-sketching-techniques/"><u>Redefine Your Digital Space with Win 11 Sketching Techniques</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-top-performers-in-the-world-of-live-game-broadcast-cams/"><u>[Updated] Top Performers in the World of Live Game Broadcast Cams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/repairing-windows-camera-failure-on-photovideo-saving/"><u>Repairing Windows Camera Failure on Photo/Video Saving</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gain-early-access-the-way-into-windows-11-beta/"><u>Gain Early Access: The Way Into Windows 11 Beta</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-default-path-problems-on-windows-1011/"><u>Resolving Default Path Problems on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-turn-off-the-mobile-interface-win-11/"><u>Quick Fix: Turn Off the Mobile Interface (Win 11)</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-mastering-vocal-modulation-in-audacity-an-easy-guide/"><u>New 2024 Approved Mastering Vocal Modulation in Audacity An Easy Guide</u></a></li>
<li><a href="https://extra-hints.techidaily.com/techs-trailblazers-windows-10-redefines-user-interface/"><u>Tech's Trailblazers  Windows 10 Redefines User Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/next-gen-teams-meeting-demands-efficiently/"><u>Next-Gen Teams Meeting Demands Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-cloud-storage-onedrive-login-on-windows/"><u>Master Your Cloud Storage: OneDrive Login on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-error-code-0x887a0006-device-hang-fixes/"><u>Resolving Error Code 0X887A0006: Device Hang Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-winsplit-display-issues-now/"><u>Fixing WinSplit Display Issues Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-netflix-freeze-in-windows-software/"><u>Overcoming Netflix Freeze in Windows Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinforcing-the-resilience-of-windows-11-taskbar/"><u>Reinforcing the Resilience of Windows 11 Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delight-in-top-tier-windows-features-via-ms-store-apps/"><u>Delight in Top-Tier Windows Features via MS Store Apps</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-directly-embedding-google-meet-in-youtubes-video-library/"><u>[New] In 2024, Directly Embedding Google Meet in YouTube's Video Library</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realign-subtitles-in-prime-video-elevate-your-windows-11-experience/"><u>Realign Subtitles in Prime Video, Elevate Your Windows 11 Experience</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-prime-video-picture-format-guide/"><u>2024 Approved Prime Video Picture Format Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-into-powertoys-for-faster-copy-pasting/"><u>Dive Into PowerToys for Faster Copy-Pasting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/propelty-keystrokes-on-windows-1011-decrease-lag-quickly/"><u>Propelty Keystrokes on Windows 10/11: Decrease Lag Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-customization-user-dir-names-in-w11/"><u>Mastering Customization: User Dir Names in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/excel-on-windows-1011-our-selection-of-the-top-5plus-productivity-boosters/"><u>Excel on Windows 10/11: Our Selection of the Top 5+ Productivity Boosters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-the-vintage-password-problem-on-w10w11/"><u>Navigating Through the Vintage Password Problem on W10/W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-onedrive-connection-problems-in-os-versions/"><u>Fixing OneDrive Connection Problems in OS Versions</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-vivo-s17-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>How to Cast Vivo S17 Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-fix-oem-unlock-missing-on-samsung-galaxy-s23-tactical-edition-by-drfone-android/"><u>In 2024, How To Fix OEM Unlock Missing on Samsung Galaxy S23 Tactical Edition?</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-whats-new-with-windows-11/"><u>2024 Approved  What's New with Windows 11?</u></a></li>
</ul></div>
