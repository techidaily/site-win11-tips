---
title: "Troubleshooting Synapse: Unidentified Razer Peripherals on Win 11"
date: 2024-07-12T16:58:55.755Z
updated: 2024-07-13T16:58:55.755Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Troubleshooting Synapse: Unidentified Razer Peripherals on Win 11"
excerpt: "This Article Describes Troubleshooting Synapse: Unidentified Razer Peripherals on Win 11"
keywords: Win 11 Razer Issue,Win 11 Device Errors,Razer Not Recognized,Synapse Peripheral Problem,Razer Unidentified Devices,Fixing Windows Peripherals,Synapse Recognition Trouble
thumbnail: https://thmb.techidaily.com/dfd36bdece1f9de4c3b950ac0cec685d6ee5d1281721c2dd1a2340c4240b4f62.png
---

## Troubleshooting Synapse: Unidentified Razer Peripherals on Win 11

 Razer Synapse is the official software for configuring Razer devices, such as keyboards and mice. However, Synapse sometimes doesn’t detect connected Razer devices. Consequently, users can’t configure their devices because they don’t show up in the Synapse software.

 The issue of Synapse not detecting devices is mostly reported for Razer mice and keyboards. However, that issue can also occur for Razer headphones, broadcast microphones, and other accessories that software will usually detect. This is how you can fix the Synapse software not detecting Razer devices within Windows 10 and 11.

## But First, Double-Check Device Compatibility With Razer Synapse

 First, before you hop into the troubleshooting steps, note that Synapse will not detect non-Razer devices. There are even some Razer products Synapse 3.0 and 2.0 don’t support. It might be the case Synapse isn’t detecting your hardware because it doesn’t support it. So, double-check your Razer Synapse software supports the device it’s not detecting.

 You can check supported hardware at the [Razer Synapse 3 supported device page](https://mysupport.razer.com/app/answers/detail/a%5Fid/4130/~/razer-synapse-3-supported-devices) . Click a category on that page to see if your device is listed there. You can also check compatibility for version 2.0 at the [Razer Synapse 2.0](https://mysupport.razer.com/app/answers/detail/a%5Fid/4131/~/razer-synapse-2.0-supported-devices) supported device page. If your device is listed among the supported hardware on one of those pages, your Synapse software should detect it.

## 1\. Run the Hardware and Devices Troubleshooter

 Windows has a Hardware and Devices troubleshooter that could identify and even resolve issues with the Razer device Synapse isn’t detecting. However, that troubleshooter isn’t visible within Settings. Nevertheless, you can run the Hardware and Devices troubleshooter from Command Prompt like this:

1. Make sure your Razer device is connected to your PC.
2. Click a**Type here to search** (magnifying glass) button or box on your Windows 11/10 taskbar.
3. To find Command Prompt, input the phrase**cmd** in the**Type here to search** box.
4. Select the Command Prompt app in the Windows search tool.
5. Execute this Hardware and Devices troubleshooter command:  
`msdt.exe -id DeviceDiagnostic`  
![The Hardware and Devices troubleshooter command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hardware-troubleshooter-command.jpg)
6. Click**Next** in the Hardware and Devices troubleshooter.  
![The Hardware and Devices troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-hardware-and-devices-troubleshooter.jpg)
7. Select**Apply this fix** for resolutions the troubleshooter suggests.

## 2\. Plug the Razer Device into an Alternative USB Port

 This issue can occur because of USB port connection issues. Some users have revealed that plugging Razer devices into different USB ports on their PCs resolved the issue of synapse not detecting them. So, try unplugging your Razer device and plugging it into an alternative USB port. Also, plug the device directly into your PC without using any intermediary USB hubs.

 It’s also recommended to select a**Remove device** option in Settings before plugging your device into another port. To do that, press the**Windows** logo +**I** key, select**Bluetooth and devices** , and click**View more** **devices** . Then click the three-dot button for your Razer hardware and select**Remove device** . In Windows 10’s Settings app, you can select a Razer peripheral on the**Bluetooth & other devices** tab and press**Remove device** .

![The Remove device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/remove-device-option.jpg)

## 3\. Select Synapse’s Repair Option

 A lot of users have also said they’ve been able to fix Synapse not detecting devices by selecting a**Repair** option for that software. Synapse has a**Repair** option you can select on a Razer Gaming Software window. This is how you can select that option in Windows 11/10:

1. Bring up the Windows uninstaller utility in the Control Panel with a method in our guide for [opening Programs and Features on Windows](https://www.makeuseof.com/windows-open-programs-and-features-tool/) .
2. Then select Razer Synapse in Programs and Features.
3. Click the**Change** button for Razer Synapse.  
![The Change button for Synapse](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/change-button.jpg)
4. Select the**Repair** option in the window that opens.  
![The Repair button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-button.jpg)
5. Sign back into Razer Synapse after selecting**Repair** .
6. Then select**Restart** in Windows 11/10 before launching Synapse.

## 4\. Reinstall Razer Synapse

 Corrupted or missing Synapse modules can cause the issue of Synapse not detecting Razer devices. So, thoroughly uninstalling Synapse by erasing leftover data and reinstalling the software will often resolve that issue. Reinstall Razer Synapse as follows:

1. Open the Programs and Features applet.
2. Click Razer Synapse to select that software.
3. Select**Uninstall** in Programs and Features to open a Razer Gaming Software window.
4. Then click the**Uninstall** option in the window to remove Synapse.
5. Uninstall Cortex and any other associated Razer sub-programs.
6. Press the**Windows** logo key +**R** to access a Run command box.
7. Input this folder directory in Run and click**OK** :  
`C:\Program Files (x86)\Razer`  
![The Program Files > Razer folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/razer-directory.jpg)
8. Press**Ctrl** +**A** to select any remaining files in the Razer folder.
9. Press the**Del** key to erase the selected files.

 Next, input this Razer directories path in Explorer’s address bar and hit**Enter** :

`C:\ProgramData\Razer`

![The ProgramData > Razer folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/razer-subfolder.jpg)

 Repeat steps eight and nine to delete all files in the Razer directories folder. Once done, restart your PC.

1. Click**Download Now** on the [Razer Synapse](https://razer.a9yw.net/c/119570/642901/10229?subId1=UUmuoUeUpU2022703&subId2=emuo&u=https%3A%2F%2Fwww.razer.com%2Fgb-en%2Fsynapse-3) page.
2. Double-click the downloaded**RazerSynapseInstaller\_V1.12.0.385.exe** file to open the setup wizard.  
![The Razer software installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/razer-installer.jpg)
3. Select the**Synapse** checkbox along with other Razer software to reinstall, and click the**Install** option.

## 5\. Reinstall Mouse and Keyboard Device Drivers

 Another fix confirmed to work for this Synapse issue is to reinstall all Razer and HID-compliant mouse and keyboard devices. Applying that potential resolution can resolve device driver conflicts. You can reinstall HID mouse and keyboard drivers as follows:

1. Press the**Win +** **X** keyboard shortcut that brings up a Power User menu.
2. Click**Device Manager** to view that tool’s window.
3. Double-click**Mice and other pointing devices** to view peripherals for that category.
4. Right-click a Razer mouse and select**Uninstall device** \>**Uninstall** .  
![The Uninstall device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-device-option.jpg)
5. Repeat the previous step for all HID mice devices listed.
6. Then double-click the**Keyboards** category.  
![The Keyboards device category](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/keyboards-category.jpg)
7. Uninstall all Razer and HID keyboard devices listed there as outlined in step four.
8. Reboot the Windows PC for the automatic reinstallation of device drivers. You can also select**Action** and**Scan for hardware changes** in Device Manager to reinstall uninstalled peripherals.

## 6\. Disable Antivirus Utilities

 Temporarily antivirus apps on your PC to ensure they aren’t blocking Synapse in any way. You can disable Windows Security’s real-time protection as outlined in our guide for [disabling Microsoft Defender](https://www.makeuseof.com/how-to-turn-off-microsoft-defender-windows-11/) . If there’s a third-party antivirus tool on your PC, turn off its shield via its system tray icon’s context menu.

![Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/real-time-protection-option2.jpg)

 Launch Razer Synapse to see if it detects your devices after disabling antivirus software on your PC. If this potential resolution works, consider adding Razer Synapse to the [exclusion list in Windows Security](https://www.makeuseof.com/windows-11-security-exclusions/) or alternative security software. Then turn your antivirus protection back on.

## Configure Your Razer Devices in Synapse Again on Windows

 Those potential solutions will most likely resolve Synapse not detecting connected devices. Then you can reconfigure your Razer mouse, keyboard, or any other supported hardware with that software. However, any users who still need more troubleshooting guidance for this issue can submit a ticket to Razer’s support service by clicking the**Contact Support** button on this [Synapse 3 page](https://mysupport.razer.com/app/answers/detail/a%5Fid/3783/~/razer-synapse-3-support) .

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
<li><a href="https://win11-tips.techidaily.com/navigating-through-limited-access-install-troubleshooting-on-win-1110/"><u>Navigating Through Limited Access Install Troubleshooting on Win 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-strategies-to-fix-windows-error-code-0x800704b3/"><u>Effective Strategies to Fix Windows' Error Code: 0X800704B3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detailed-guide-to-overcoming-steam-auth-problems-with-rust-on-windows/"><u>Detailed Guide to Overcoming Steam Auth Problems with Rust on Windows</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/2024-approved-video-editing-mastery-top-4k8k-software-for-beginners-and-pros/"><u>2024 Approved Video Editing Mastery Top 4K/8K Software for Beginners and Pros</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-miniature-homes-6-top-oriental-designs-for-mcers/"><u>[Updated] In 2024, Miniature Homes  6 Top Oriental Designs for MCers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-steps-to-correct-windows-operating-system-office-errors/"><u>Immediate Steps to Correct Windows Operating System Office Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-chkdsk-sfc-vs-dism-in-os-maintenance/"><u>Understanding CHKDSK, SFC Vs. DISM in OS Maintenance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-3-innovative-ways-for-windows-hardware-id-access/"><u>Exploring 3 Innovative Ways for Windows Hardware ID Access</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-step-by-step-techniques-for-embedding-audio-into-videos-for-2024/"><u>New Step-By-Step Techniques for Embedding Audio Into Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-alteration-of-nat-types-in-windows-operating-systems/"><u>Effective Alteration of NAT Types in Windows Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-advice-on-resolving-windows-error-code-0xc0000001/"><u>Expert Advice on Resolving Windows Error Code 0XC0000001</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tweak-viewer-direction-on-windows-monitor/"><u>Tweak Viewer Direction on Windows Monitor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-store-wont-let-you-sign-in-try-these-fixes/"><u>Microsoft Store Won’t Let You Sign In? Try These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-the-top-6-computer-utilization-monitors-on-pcs/"><u>Discover the Top 6 Computer Utilization Monitors on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-for-loss-of-pin-access-in-windows-11-post-update-fallout/"><u>Fix for Loss of PIN Access in Windows 11 Post-Update Fallout</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-files-write-access-no-more-restrictions/"><u>Adjusting Windows Files: Write Access No More Restrictions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-ways-to-check-for-open-tcpip-ports-on-windows/"><u>3 Ways to Check for Open TCP/IP Ports on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insights-into-windows-patch-identification/"><u>Insights Into Window's Patch Identification</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-reset-the-security-questions-of-your-apple-id-on-your-apple-iphone-6-by-drfone-ios/"><u>In 2024, How To Reset the Security Questions of Your Apple ID On Your Apple iPhone 6</u></a></li>
<li><a href="https://win11-tips.techidaily.com/msix-extension-mastery-a-practical-guide-to-microsoft-store-add-ons/"><u>MSIX Extension Mastery: A Practical Guide to Microsoft Store Add-Ons</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/weaving-an-engaging-film-teaser-thread/"><u>Weaving an Engaging Film Teaser Thread</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/effortlessly-stream-mp3-to-youtube-with-3-key-steps/"><u>Effortlessly Stream  MP3 to YouTube with 3 Key Steps</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-etsy-listing-image-ratio-advice/"><u>2024 Approved  Etsy Listing Image Ratio Advice</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-with-ease-to-windows-11s-security-management/"><u>Navigate with Ease to Windows 11’S Security Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/circumventing-non-changeable-sleepwake-modes-in-windows-11/"><u>Circumventing Non-Changeable Sleep/Wake Modes in Windows 11</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-in-2024-how-to-convert-video-to-gif-fast-and-easy/"><u>Updated In 2024, How to Convert Video to GIF Fast & Easy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-persistence-of-user-defined-volume-mixer/"><u>Ensuring Persistence of User-Defined Volume Mixer</u></a></li>
<li><a href="https://howto.techidaily.com/fix-unfortunately-settings-has-stopped-on-honor-magic-6-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Unfortunately Settings Has Stopped on Honor Magic 6 Quickly | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-windows-net-runtime-requirement-hurdle/"><u>Avoiding Windows' .NET Runtime Requirement Hurdle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-cleanse-your-computer-of-previous-security-audits/"><u>How to Cleanse Your Computer of Previous Security Audits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrading-to-optimal-windows-audios-through-driver-revision/"><u>Upgrading to Optimal Windows Audios Through Driver Revision</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-ultimate-auditory-playscripts-collection/"><u>[New] Ultimate Auditory Playscripts Collection</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-no-more-distractions-expert-guide-to-removing-youtube-ads/"><u>[New] No More Distractions - Expert Guide to Removing YouTube Ads</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-best-discord-alternatives-for-better-experience/"><u>2024 Approved  Best Discord Alternatives for Better Experience</u></a></li>
<li><a href="https://android-location.techidaily.com/getting-the-pokemon-go-gps-signal-not-found-11-error-in-tecno-camon-20-premier-5g-drfone-by-drfone-virtual/"><u>Getting the Pokemon Go GPS Signal Not Found 11 Error in Tecno Camon 20 Premier 5G | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-crafting-captivating-intros-on-mobile-platforms-for-2024/"><u>[New] Crafting Captivating Intros on Mobile Platforms for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/essential-gopro-editing-the-top-15-color-luts-selection-guide/"><u>Essential GoPro Editing  The Top 15 Color LUTs Selection Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-win-10s-cc-troubleshooting/"><u>Essential Tips for Win 10'S CC Troubleshooting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augment-windows-management-with-a-disk-space-analysis-tool/"><u>Augment Windows Management with a Disk Space Analysis Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-quickly-enable-or-disable-bing-chat-ai-in-windows-11-taskbar-search/"><u>How to Quickly Enable or Disable Bing Chat AI in Windows 11 Taskbar Search</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-reset-gmail-password-on-samsung-galaxy-a15-5g-devices-by-drfone-android/"><u>In 2024, How to Reset Gmail Password on Samsung Galaxy A15 5G Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-credential-store-lockups-on-pcs/"><u>Fix Credential Store Lockups on PCs</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-master-adobe-premiere-with-these-20-must-know-shortcuts/"><u>Updated Master Adobe Premiere with These 20 Must-Know Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-mspcm-interface-on-windows-11-easily/"><u>Navigating the MSPCM Interface on Windows 11 Easily</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/length-limit-check-out-these-5-youtube-minisizers-for-2024/"><u>Link Length Limit? Check Out These 5 YouTube Minisizers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customize-your-computing-conduct-setting-active-hours-to-mitigate-updates-in-windows-11/"><u>Customize Your Computing Conduct: Setting Active Hours to Mitigate Updates in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cure-for-unresponsive-wired-gaming-accessories/"><u>Cure for Unresponsive Wired Gaming Accessories</u></a></li>
<li><a href="https://techidaily.com/solved-bad-and-corrupt-videos-that-wont-play-on-oppo-find-x7-by-stellar-video-repair-mobile-video-repair/"><u>Solved  Bad and Corrupt Videos that won't Play on Oppo Find X7</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-basic-procedure-swapping-video-playback-in-vlc-media-player/"><u>[Updated] In 2024, Basic Procedure  Swapping Video Playback in VLC Media Player</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cut-down-clutter-tackling-large-storage-consumers-in-windows/"><u>Cut Down Clutter: Tackling Large Storage Consumers in Windows</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/bring-your-ideas-to-life-best-stop-motion-apps-for-ios-and-android/"><u>Bring Your Ideas to Life Best Stop Motion Apps for iOS and Android</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-discover-your-future-with-window-11s-innovative-creations/"><u>[Updated] In 2024, Discover Your Future with Window 11'S Innovative Creations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gearing-up-with-best-laptops-from-ifa-2023/"><u>Gearing Up with Best Laptops From IFA 2023</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-icloud-activation-lock-on-mac-for-apple-iphone-12-pro-max-by-drfone-ios/"><u>In 2024, How To Bypass iCloud Activation Lock on Mac For Apple iPhone 12 Pro Max?</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-superiorly-crafted-radio-scripts/"><u>2024 Approved  Superiorly Crafted Radio Scripts</u></a></li>
<li><a href="https://apple-account.techidaily.com/turning-off-two-factor-authentication-on-apple-iphone-xr-5-tips-you-must-know-by-drfone-ios/"><u>Turning Off Two Factor Authentication On Apple iPhone XR? 5 Tips You Must Know</u></a></li>
<li><a href="https://win11-tips.techidaily.com/create-individualized-keystroke-rules-in-windows-11/"><u>Create Individualized Keystroke Rules in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-steam-connectivity-woes-in-w11/"><u>Navigating Through Steam Connectivity Woes in W11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/uninterrupted-gaming-on-rtx-graphics/"><u>Uninterrupted Gaming on RTX Graphics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-win1011-recycle-bin-repair-strategies/"><u>Mastering WIN10/11 Recycle Bin Repair Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-internal-error-in-windows-11-remote/"><u>Mastering the Art of Fixing Internal Error in Windows 11 Remote</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-the-swift-method-for-rescaling-audio-playback-rates/"><u>New In 2024, The Swift Method for Rescaling Audio Playback Rates</u></a></li>
</ul></div>
