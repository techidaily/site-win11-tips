---
title: Resolving Shortage of Physical Storage Space (VM) Errors
date: 2024-07-12T16:50:22.975Z
updated: 2024-07-13T16:50:22.975Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Shortage of Physical Storage Space (VM) Errors
excerpt: This Article Describes Resolving Shortage of Physical Storage Space (VM) Errors
keywords: Fix VM Storage Space Issue,Solve VM Storage Crunch,Overcome VM Spaces Deficit,Address VM Shortage Error,Eradicate VM Storage Limits,Eliminate VM Lack of Space,Correct VM Insufficiency
thumbnail: https://thmb.techidaily.com/afda68c97ad8ab431f217d1a649d9d5c1081b7b5e12422de4ab2672dba23567f.jpg
---

## Resolving Shortage of Physical Storage Space (VM) Errors

 VMware Workstation is one of the best virtualization software packages for Windows. However, some users see an error message when they try to start virtual machines in VMware Workstation. That error message says, “not enough physical memory is available to power on this virtual machine,” and virtual machines won’t start up.

 This VMware issue can arise when there’s more than enough RAM available on a PC. However, there are numerous possible causes for the “not enough physical memory” error. This is how you can fix the “not enough physical memory” WMware error in Windows 10 and 11.

## 1\. Configure VMware to Run as an Administrator

 Not running VMware as an administrator places restrictions on its system permissions and access to resources. So, run the software with elevated rights to ensure a lack of permissions isn’t causing any issues.

 You can check out [how to run any program as an administrator on Windows](https://www.makeuseof.com/tag/ways-to-run-a-program-as-administrator-in-windows/) for more help, or you can set VMware to always run as an administrator like this:

1. If there’s a VMware shortcut on your desktop, right-click it and select**Open** file location. Manually open VMware’s installation directory in File Explorer if you can’t right-click a shortcut for the software.
2. Then click the VMware EXE file with the right mouse button to select its**Properties** context menu option.
3. Select**Compatibility** to view that tab’s settings.
4. Click the checkbox for the**Run this program as administrator** option to select it.  
![The Compatibility tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-compatibility-tab2.jpg)
5. Select**Apply** to save the new administrator option for VMware.
6. Then select**OK** to close WMware’s properties window.

## 2\. Edit the Config File

 Lots of users have been able to fix the “not enough physical memory” by editing VMWare’s**config.ini** file. Those users disabled a Host parameter within the software’s configuration file. To disable that Host parameter, open and edit VMware’s**config.ini** file as follows:

1. Press**Win + E** to access File Explorer.
2. Open this VMware directory in Explorer:  
`C:\ProgramData\VMware\VMware Workstation`
3. Right-click the**config.ini** file and select**Open with** .  
![The Open with option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-open-with-option.jpg)
4. Select**Notepad** to view the configuration file in that text editor.
5. Then **input vmmon.disableHostParameters = “TRUE”** at the bottom of the configuration file as in the image below.  
![WMware's config.ini file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-config-ini-file.jpg)
6. Click**File** on Notepad’s menubar.
7. Select the menu’s**Save** option.  
![The Save option in Notepad](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-save-option-in-notepad.jpg)

## 3\. Expand the Virtual Memory for the Virtual Machine

 The “not enough physical memory” error can occur because not enough virtual memory has been allocated to the virtual machine. You can expand a virtual machine’s memory allocation in VMWare like this:

1. Open your VMware software.
2. Right-click the virtual machine for which you need to fix the error and select**Settings** .
3. Increase the virtual machine’s memory allocation with the bar slider. That amount should always be higher than your PC’s available RAM.  
![The memory bar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-memory-bar.jpg)
4. Click**OK** to apply.

## 4\. Update VMware

 The “not enough physical memory” error will more likely arise on outdated WMware versions. So, ensure you’re utilizing the latest version of the software. This is how you can update VMware:

1. Bring up the VMware window.
2. Click the**Help** menu.
3. Select**Software Updates** to view that window.  
![The Software Updates option in VMware](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-software-updates-option.jpg)
4. Then click the**Check for Updates** button.  
![The Check for updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-check-for-updates-option4.jpg)
5. Press the**Get More Information** button for an available update.

1. Log into an account profile on the website that opens.
2. Select the**Download Now** option on the website for the latest VMware Workstation version.
3. Then you’ll need to select an**Accept** option for the EULA agreement.
4. Click another**Download Now** option.
5. Then click File Explorer’s taskbar shortcut.
6. Go to the downloads folder that includes the WMware setup wizard.
7. Double-click the downloaded VMware installer to open it. Go through the setup wizard to install the latest VMware version.

## 5\. Delete a Recent Windows Update

 The “not enough physical memory” error can be caused by a Windows update that conflicts with VMware. So, uninstalling a recent update could fix that issue for some users. Check out our guide about [uninstalling Windows updates](https://www.makeuseof.com/windows-11-uninstall-updates/) for further details on how to apply this potential solution.

![The Installed Updates Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-uninstall-update-option.jpg)

## 6\. Perform a Clean Boot

 Performing a clean boot will disable non-essential apps and services from the Windows startup. Clean booting can potentially resolve the “not enough physical memory” in two ways. Applying this troubleshooting method will ensure there aren’t any third-party programs conflicting with VMware and free up RAM for the software.

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-services-tab-in-msconfig.jpg)

 To disable all third-party startup programs and services, check out the guidelines in our guide on [how to clean boot in Windows](https://www.makeuseof.com/clean-boot-windows-11/) . This will perform a clean boot whenever you restart Windows.

 Try utilizing your VMware virtual machine after clean booting. If this works,

## 7\. Set Up a New Virtual Machine

 If the issue persists despite applying the resolutions above, consider setting up a new virtual machine to replace the one that needs fixing. Download the latest ISO for the virtual machine’s platform. Then you can set up the virtual machine again, as outlined on the [VMware support page](https://kb.vmware.com/s/article/1018415) .

## Jump Into Your WMware Virtual Machine Again

 Those Windows fixes for the “Not enough physical memory” error have worked for many VMware Workstation users. So, there’s a decent enough chance one will kick-start your VMWare virtual machine too. However, users who still need more possible fixes for this issue can submit a support request via the [VMware Customer Connect](https://customerconnect.vmware.com/home?bmctx=89E60DF848C641FD518EB9F6B9A6E5334F602FA3A762B409625CD531863AC847&password=secure%5Fstring&contextType=external&username=string&challenge%5Furl=https:%2F%2Fcustomerconnect.vmware.com%2Fhome&request%5Fid=-8453692679675997712&authn%5Ftry%5Fcount=0&locale=en%5FGB&resource%5Furl=https%253A%252F%252Fcustomerconnect.vmware.com%252Fweb%252Fvmware%252Fchecksession) page.

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
<li><a href="https://win11-tips.techidaily.com/efficiently-run-pcs-leveraging-the-power-of-key-optimization-tools/"><u>Efficiently Run PCs: Leveraging the Power of Key Optimization Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-correcting-xbox-game-pass-error-0x000-on-windows-11-systems/"><u>Understanding and Correcting Xbox Game Pass Error 0X000_ on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/spotting-large-files-and-drives-in-windows-storage-soup/"><u>Spotting Large Files & Drives in Windows Storage Soup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-6-most-reliable-brightness-tools-for-windows-multi-display-users/"><u>The 6 Most Reliable Brightness Tools For Windows Multi-Display Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-adobe-reader-setup-on-ms-store/"><u>Effortless Adobe Reader Setup on MS Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-tech-companion-asus-vivobook-s-15-review/"><u>The Ultimate Tech Companion: Asus Vivobook S 15 Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-lowering-cpu-intensity-in-gaming-windows/"><u>Solutions for Lowering CPU Intensity in Gaming Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trailblazing-to-windows-birthplace-points/"><u>Trailblazing to Windows' Birthplace Points</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-discord-installer-errors-on-windows-devices/"><u>Resolving Discord Installer Errors on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-audio-tracking-on-windows-powered-screencasts/"><u>Strategies for Audio Tracking on Windows-Powered Screencasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-background-removal-in-photo-editing-tools/"><u>Mastering Background Removal in Photo Editing Tools</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/top-10-affordable-accessible-tools-to-transform-videos-for-2024/"><u>Top 10 Affordable, Accessible Tools to Transform Videos for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-prime-software-for-livestream-capture-other-than-obs/"><u>[New] 2024 Approved  Prime Software for Livestream Capture Other Than OBS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-insufficient-ram-issues-on-windowsvmware-platforms/"><u>Addressing Insufficient RAM Issues on Windows/VmWare Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-windows-11s-default-touch-panel-settings-and-positioning/"><u>Restoring Windows 11'S Default Touch Panel Settings & Positioning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-changing-app-size-using-pc-keys-on-windows-11/"><u>Tips for Changing App Size Using PC Keys on Windows 11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/resolve-hdr-video-issue-clearing-blank-display-for-2024/"><u>Resolve HDR Video Issue  Clearing Blank Display for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stopping-intelligent-assistant-protocol-on-windows/"><u>Stopping Intelligent Assistant Protocol on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-synapse-functionality-with-razer-devices-on-windows/"><u>Restoring Synapse Functionality with Razer Devices on Windows</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-clever-ways-to-neglect-edge-academy-vids/"><u>[New] Clever Ways to Neglect EDGE Academy Vids</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-optimal-series-professional-webcam-stabilizers/"><u>[Updated] Optimal Series  Professional Webcam Stabilizers</u></a></li>
<li><a href="https://fox-blue.techidaily.com/efficient-strategies-for-designing-podcast-rss-feeds-for-2024/"><u>Efficient Strategies for Designing Podcast RSS Feeds for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-workflow-programmatic-shortcuts-in-winos/"><u>Streamline Workflow: Programmatic Shortcuts in WinOS</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-in-2024-download-your-wish-unwatermarked-tiktok-files/"><u>[Updated] In 2024, Download-Your-Wish  Unwatermarked TikTok Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-your-cyber-voyage-checking-stable-connections-on-pc/"><u>Securing Your Cyber Voyage: Checking Stable Connections on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-common-errors-in-win1011-0x8007045d/"><u>Solving Common Errors in Win10/11 - 0X8007045D</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-perfecting-picture-clarity-efficiently-eradicating-backgrounds/"><u>2024 Approved  Perfecting Picture Clarity  Efficiently Eradicating Backgrounds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-path-setting-up-google-maps-on-windows-pcs/"><u>Navigating the Path: Setting up Google Maps on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-using-windows-file-browsing-in-place-of-ls/"><u>Expert Tips for Using Windows File Browsing in Place of LS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-top-5-grievances-from-windows-11-users/"><u>Unveiling the Top 5 Grievances From Windows 11 Users</u></a></li>
<li><a href="https://driver-install.techidaily.com/unified-usbasp-drivers-across-windows-generations-and-versions/"><u>Unified USBasp Drivers Across Windows Generations and Versions</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-unveiling-the-secrets-to-creating-an-enterprise-instagram-profile/"><u>[New] Unveiling the Secrets to Creating an Enterprise Instagram Profile</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-icloud-on-apple-iphone-7-smoothly-by-drfone-ios/"><u>In 2024, How To Remove iCloud On Apple iPhone 7 Smoothly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unhindered-wi-fi-on-your-desktop-9-strategies-for-win11-users/"><u>Unhindered Wi-Fi on Your Desktop: 9 Strategies for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-the-dilemma-obs-not-opening-on-windows/"><u>Resolving the Dilemma: OBS Not Opening on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-pens-tools-for-the-modern-windowed-tech-user/"><u>Top Pens' Tools For the Modern Windowed Tech User</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-establishing-backup-routine-for-nvidia-panel-configurations/"><u>Re-Establishing Backup Routine for Nvidia Panel Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-combination-of-files-in-windows-1011/"><u>Seamless Combination of Files in Windows 10/11</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-a-symphony-of-effects-discovering-vendors-for-premium-podcast-audio/"><u>Updated A Symphony of Effects Discovering Vendors for Premium Podcast Audio</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-fine-tuning-focus-closeups-on-teams/"><u>[New] Fine-Tuning Focus  Closeups on Teams</u></a></li>
<li><a href="https://howto.techidaily.com/11-proven-solutions-to-fix-google-play-store-not-working-issue-on-motorola-razr-40-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Proven Solutions to Fix Google Play Store Not Working Issue on Motorola Razr 40 | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-photographic-edge-cutting-edge-editing-strategies/"><u>[New] The Photographic Edge  Cutting-Edge Editing Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-permission-errors-a-step-by-step-guide-on-windows/"><u>Resolving Permission Errors: A Step-by-Step Guide on Windows</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-updated-lg-bp550-features-and-reviews/"><u>[New] Updated LG BP550 - Features & Reviews</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-unanticipated-error-messages-in-wins-secure/"><u>Tackling Unanticipated Error Messages in WINS Secure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-setup-a-closer-look/"><u>Windows 11 Setup: A Closer Look</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-the-ultimate-cheat-sheet-to-gameplay-screencasts-in-overwatch/"><u>2024 Approved  The Ultimate Cheat Sheet to Gameplay Screencasts in Overwatch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dual-virus-defense-think-again-windows-users/"><u>Dual Virus Defense? Think Again, Windows Users!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sync-your-schedule-how-to-reset-windows-time-service/"><u>Sync Your Schedule: How to Reset Windows Time Service</u></a></li>
<li><a href="https://games-able.techidaily.com/can-you-control-your-ps4-with-ps5-controller/"><u>Can You Control Your PS4 with PS5 Controller?</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-avoiding-legal-issues-best-practices-for-zoom-records/"><u>In 2024, Avoiding Legal Issues  Best Practices for Zoom Records</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-workspace-windows-11-widget-techniques/"><u>Revamp Your Workspace: Windows 11 Widget Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-path-upgrading-your-vm-software-from-virtualbox-v6-to-v7-in-win11/"><u>Step-by-Step Path: Upgrading Your VM Software From VirtualBox v6 to v7 in Win11</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-the-ultimate-selection-8-popular-audio-recording-applications/"><u>In 2024, The Ultimate Selection 8 Popular Audio Recording Applications</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-2024-approved-top-4-best-music-editor-for-mac/"><u>New 2024 Approved Top 4 Best Music Editor for Mac</u></a></li>
</ul></div>
