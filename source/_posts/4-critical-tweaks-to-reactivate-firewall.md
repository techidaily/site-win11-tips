---
title: 4 Critical Tweaks to Reactivate Firewall
date: 2024-07-12T17:54:29.616Z
updated: 2024-07-13T17:54:29.616Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 4 Critical Tweaks to Reactivate Firewall
excerpt: This Article Describes 4 Critical Tweaks to Reactivate Firewall
keywords: React Firewall Trigger,Boost Firewall Performance,Enhance Security Settings,Update Firewall Configuration,Improve Firewall Efficiency,Optimize Firewall Functions,Revitalize Network Protection
thumbnail: https://thmb.techidaily.com/d35c94f12f755c322517a2947b55e4796f16febf7bfe5d4d03e4ed968b83a331.jpg
---

## 4 Critical Tweaks to Reactivate Firewall

 Windows Firewall is crucial to ensure the security of your computer and protect it from potential threats. However, sometimes you may encounter issues while enabling it.

 Below, we explore the different solutions you can try to fix this issue for good.

## 1\. Run the Firewall Troubleshooter

 If you are having trouble enabling Firewall in Windows, it is a good idea to start troubleshooting using the official Firewall troubleshooter released by Microsoft Automated Troubleshooting Services.

 This utility will scan your system for underlying problems that might be preventing Firewall from functioning. If an issue is identified, it will suggest relevant fixes that you can either apply manually or from within the troubleshooter.

 Here is how you can run the troubleshooter:

1. Head over to the [official Microsoft page for the troubleshooter](https://support.microsoft.com/en-us/windows/automatically-diagnose-and-fix-problems-with-windows-firewall-513e9cf8-19ae-d579-2092-d5e64fe06f5f) and download it.  
![Download firewall troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/download-troubleshooter.jpg)
2. Click on the downloaded file and proceed with the on-screen instructions to start the scan.  
![Firewall troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/firewall-troubleshooter.jpg)
3. Once the scan completes, check the results and apply the solutions suggested by the troubleshooter.

 You can now close the troubleshooter and check if the issue is resolved.

## 2\. Check if Another Security Software Is Active

 Are you using a third-party security program on your computer? If so, there is a good chance that it is conflicting with Windows Firewall and stopping it from working. As such, if you have installed another antivirus app recently, we recommend temporarily disabling or uninstalling the third-party security program and then enabling Windows Firewall.

 Disabling the third-party antivirus software may vary depending on the program you have installed. However, a common approach is to right-click on the antivirus icon located in the taskbar. From the context menu that appears, you should find an option to disable the antivirus temporarily until you restart your computer.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 After disabling the antivirus, try enabling the Windows Firewall and check if it functions properly now.

## 3\. Reset the Windows Firewall settings

 The issue might also be with the Firewall settings. You can fix any such issues by resetting Windows Firewall settings, as it will restore the firewall configuration to its default state, undoing any customizations or changes that might be causing conflicts.

 Here is how you can proceed:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type “control” in Run and click **Enter**.
3. In the Control Panel, expand the View by option and choose **Category**.
4. Click on **System and Security** \> **Windows Defender Firewall**.  
![Defender Firewall in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/defender-firewall.jpg)
5. Head over to the left pane and choose **Restore defaults**.  
![Restore defaults for firewall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restore-defaults.jpg)

1. Confirm the action in the following prompt and proceed with the on-screen instructions to proceed.
2. Once done, open Run again.
3. Type "cmd" in the text field and press **Ctrl** \+ **Shift** \+ **Enter** keys together. This will open Command Prompt with administrator privileges.
4. Click **Yes** in the User Account Control prompt.
5. Once you are inside the Command Prompt window, type the command mentioned below and click **Enter** to execute it. This will force enable the Firewall component.  
`netsh firewall set opmode mode=ENABLE exceptions=enable`
6. Wait for the command to execute and then restart your computer. Check if the problem is now fixed.

## 4\. Modify the Registry Editor

 There is also a chance that a Registry key DisableAntiSpyware is enabled, which is preventing you from enabling Firewall on your computer.

 To check if this is the case in your situation, you can access the Registry Editor and check the status of the DisableAntiSpyware key.

 However, before you proceed, we highly recommend [creating a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/), just to be safe.

 Once that is done, proceed with the steps below:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "regedit" in Run and click **Enter**.
3. Click **Yes** in the User Account Control prompt.
4. In the Registry Editor, navigate to the location below.  
`​​​​​​​HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender`
5. Move to the right side and look for the DisableAntiSpyware key. If you locate it, delete it. You can also double-click on it and change its value to 0 if you do not want to delete it.  
![Disable or delete the registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/antispyware-key.jpg)

1. Once done, head over to the following location:  
`​​​​​​​​​​​​​​HKEY_LOCAL_MACHINE/SYSTEM/CurrentControlSet/Services/BFE`
2. Right-click on the **BFE** key and choose **Permissions** from the context menu.  
![Access permissions of the key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/access-permissions.jpg)
3. Under "Group or user names", click on **Add**.
4. Type "Everyone" in the "Enter the object names to select" and click **OK**.  
![Modify permissions of the key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/modify-permissions.jpg)
5. Now, head over to the "Permissions for Everyone" section and checkmark the box associated with **Full Control** under Allow.
6. Click **Apply** to save the changes and check if the issue is now resolved.

## Additional Generic Fixes to Try

 Apart from the fixes we have listed above, here are some additional solutions that you can try to fix the Firewall problem.

* **Ensure relevant services are running**: Windows Firewall relies on several services to function properly. Ensure that the Windows Defender Firewall, Windows Defender Advanced Threat Protection, Windows Defender Antivirus Network Inspection, and Windows Defender Antivirus services are working fine in the Windows Services utility.
* **Scan with SFC**: You can also scan the system for underlying corruption errors that might be leading to the problem using the [System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/). You can run it via Command Prompt and analyze the results to find the culprit.
* **Clean install Windows**: If nothing works and it is essential for you to enable Firewall, you can [perform a clean install](https://www.makeuseof.com/how-to-clean-install-windows-11/) of Windows. It will wipe the existing installation and download a new one without any underlying problems.

## Protect Your System With Windows Firewall

 The steps above should help you fix issues with Windows Firewall easily. If the error persists and you do not want to clean install the system yet, you can report the issue to Microsoft and wait for them to suggest a fix.

 Below, we explore the different solutions you can try to fix this issue for good.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/harnessing-windows-oversight-on-apps-browsers/"><u>Harnessing Windows Oversight on Apps, Browsers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-smooth-asana-operations-on-pcs/"><u>Restoring Smooth Asana Operations on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/supercharge-windows-11s-notepad-with-copilot/"><u>Supercharge Windows 11’S Notepad With Copilot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improve-system-stability-automatic-updates-plus-amd-video-replacement/"><u>Improve System Stability: Automatic Updates + AMD Video Replacement</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/streamlining-the-process-vimeo-to-mp3-conversion/"><u>Streamlining the Process  Vimeo to MP3 Conversion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jumpstart-your-pc-with-hyper-v-on-windows-11/"><u>Jumpstart Your PC with Hyper-V on Windows 11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-video-upload-bridging-twitter-tumblr-guide/"><u>[New] Video Upload Bridging  Twitter-Tumblr Guide</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-deep-dive-into-acid-pro-functionality-and-alternatives/"><u>[Updated] 2024 Approved  Deep Dive Into ACID Pro Functionality & Alternatives</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-revive-your-bricked-oppo-a79-5g-in-minutes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Revive Your Bricked Oppo A79 5G in Minutes | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-mspm-setup-obstacles-in-windows-vista/"><u>Overcoming MSPM Setup Obstacles in Windows Vista</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-non-definable-error-in-windows-environment/"><u>Tackling 'Non-Definable' Error in Windows Environment</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-smartphones-and-beyond-the-leading-vr-headsets/"><u>[New] Smartphones and Beyond  The Leading VR Headsets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-model-names-unraveling-your-device-in-six-easy-ways/"><u>Mastering Model Names: Unraveling Your Device in Six Easy Ways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/past-keys-to-future-launches-utilizing-windows-7-for-windows-11-bootup/"><u>Past Keys to Future Launches: Utilizing Windows 7 for Windows 11 Bootup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-installation-of-windows-chatgpt/"><u>Step-by-Step Installation of Windows ChatGPT</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-optimize-your-communication-scheduling-and-planning-with-ease-google/"><u>[Updated] In 2024, Optimize Your Communication  Scheduling & Planning with Ease (Google)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leap-to-peak-ssd-performance-win-and-fresh-methods/"><u>Leap to Peak SSD Performance: Win and Fresh Methods</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-vpna-to-fake-gps-location-on-oppo-find-x6-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use VPNa to Fake GPS Location On Oppo Find X6 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-microsoft-works-with-windows-11-easy/"><u>Integrating Microsoft Works with Windows 11 Easy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-gui-diskspace-windows-menu-integration-guide/"><u>Mastering GUI Diskspace: Windows Menu Integration Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-enable-digital-supervision-in-windows-11-pcs/"><u>Steps to Enable Digital Supervision in Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-downloads-folder-not-responding-on-windows/"><u>How to Fix the Downloads Folder Not Responding on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-windows-exploration-without-the-use-of-ls/"><u>Streamlined Windows Exploration Without the Use of LS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-users-through-admin-level-execution-woes/"><u>Guiding Users Through Admin-Level Execution Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-insiders-guide-to-customizing-the-desktop-menu/"><u>The Insider's Guide to Customizing the Desktop Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-operation-issues-on-modern-windows-pcs/"><u>Resolving Operation Issues on Modern Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-remedy-fixing-file-not-found-issues-in-windows-1110/"><u>Quick Remedy: Fixing 'File Not Found' Issues in Windows 11/10</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-expert-tips-on-selecting-best-free-srt-tools/"><u>2024 Approved  Expert Tips on Selecting Best FREE SRT Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-cure-all-solutions-for-windows-camera-glitches/"><u>Quick Cure-All Solutions for Windows Camera Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-through-default-windows-backup-reset/"><u>Guiding Through Default Windows Backup Reset</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-copy-paste-not-working-in-chrome-edge-and-firefox-on-windows/"><u>How to Fix Copy-Paste Not Working in Chrome, Edge, and Firefox on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steering-clear-of-stuck-warcraft-patches/"><u>Steering Clear of Stuck Warcraft Patches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-guide-for-installing-windows-11-arm-via-iso-download/"><u>How-To Guide for Installing Windows 11 ARM via ISO Download</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/farm-like-royalty-unveiling-the-best-7-stardew-upgrades/"><u>Farm Like Royalty - Unveiling the Best 7 Stardew Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-you-dont-have-permission-to-view-this-file-error-on-windows/"><u>How to Fix the “You Don’t Have Permission to View This File” Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essentials-of-windows-diagnostics-compiling-and-analyzing-data/"><u>Essentials of Windows Diagnostics: Compiling & Analyzing Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-smooth-background-operations-with-edge-in-win11/"><u>Ensuring Smooth Background Operations with Edge in Win11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-htcs-masterpiece-in-vr-the-immersive-experience/"><u>2024 Approved  HTC's Masterpiece in VR  The Immersive Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-bring-back-your-bluetooth-in-windows-11-top-9-methods/"><u>How to Bring Back Your Bluetooth in Windows 11: Top 9 Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-safety-sticky-notes-edition/"><u>Mastering File Safety: Sticky Notes Edition</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-social-media-savvy-top-101-bio-tips-and-techniques-for-facebookers/"><u>In 2024, Social Media Savvy  Top 101 Bio Tips & Techniques for Facebookers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-windows-crashes-due-to-video-drivers/"><u>Remedying Windows Crashes Due to Video Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-prevent-date-changes-on-windows-pcs/"><u>Steps to Prevent Date Changes on Windows PCs</u></a></li>
<li><a href="https://extra-information.techidaily.com/transformative-guide-gifs-becoming-stickers-on-discord-whatsapp-and-telegram/"><u>Transformative Guide  GIFs Becoming Stickers on Discord, WhatsApp & Telegram</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-permit-browser-network-access-via-windows-security-settings/"><u>How to Permit Browser Network Access via Windows Security Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/successfully-overcome-windows-error-0x80070003-a-step-by-step-guide/"><u>Successfully Overcome Windows Error 0X80070003 - A Step-by-Step Guide</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-elevate-your-content-uploading-numerous-photos-and-videos-to-instagram/"><u>[New] 2024 Approved  Elevate Your Content  Uploading Numerous Photos and Videos to Instagram</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-recollection-of-previous-windows-password/"><u>Mending “Recollection of Previous Window's Password”</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-can-we-unlock-our-nokia-c12-plus-phone-screen-by-drfone-android/"><u>How Can We Unlock Our Nokia C12 Plus Phone Screen?</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-how-to-effectively-archive-snapchat-videos-on-mobile-phones/"><u>[New] In 2024, How to Effectively Archive Snapchat Videos on Mobile Phones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-updater-roadblock-0x80073712/"><u>Resolving Updater Roadblock: 0X80073712</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-unavailability-of-icloud-on-windows/"><u>Fixing the Unavailability of iCloud on Windows</u></a></li>
</ul></div>
