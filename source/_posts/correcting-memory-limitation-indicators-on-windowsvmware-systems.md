---
title: Correcting Memory Limitation Indicators on Windows/VMware Systems
date: 2024-07-12T17:28:28.713Z
updated: 2024-07-13T17:28:28.713Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Memory Limitation Indicators on Windows/VMware Systems
excerpt: This Article Describes Correcting Memory Limitation Indicators on Windows/VMware Systems
keywords: Fix Memory Errors Win,RAM Fix in VMware,Overcoming Mem Limits WS,Windows Memory Faults,VMWare Memory Optimization,Enhance Windows RAM,Correcting Mem Indicator
thumbnail: https://thmb.techidaily.com/6af91e940bb187fedb6046d135c289160c909fca83f80b9023766807a5bb6dc8.png
---

## Correcting Memory Limitation Indicators on Windows/VMware Systems

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
<li><a href="https://win11-tips.techidaily.com/what-is-the-microsoft-visual-cplusplus-redistributable-used-for/"><u>What Is the Microsoft Visual C++ Redistributable Used For?</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/logo-magic-sprucing-up-your-podcasts-visual-appeal-for-2024/"><u>Logo Magic  Sprucing Up Your Podcast's Visual Appeal for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerated-action-plan-for-file-explorer-restarts-on-win-11/"><u>Accelerated Action Plan for File Explorer Restarts on Win 11</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-is-av1-the-new-video-codec-front-runner/"><u>2024 Approved  Is AV1 The New Video Codec Front-Runner?</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-mkvtoolnix-for-mac-the-easiest-way-to-edit-videos/"><u>2024 Approved MKVtoolnix for Mac The Easiest Way to Edit Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-integrate-sudo-with-windows-systems/"><u>Why Integrate Sudo with Windows Systems</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-huawei-p60-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Huawei P60 to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-photo-preview-boards-in-win-11/"><u>Adjusting Photo Preview Boards in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-network-adapter-error-31-quickly/"><u>Addressing Windows Network Adapter Error 31 Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-printer-busy-message-in-win11/"><u>Eliminating Printer Busy Message in Win11</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/top-20-free-footage-sites-a-comprehensively-curated-list/"><u>Top 20 Free Footage Sites  A Comprehensively Curated List</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-how-to-for-customizing-windows-11-with-widgets/"><u>A Comprehensive How-To for Customizing Windows 11 with Widgets</u></a></li>
<li><a href="https://iphone-location.techidaily.com/hide-location-on-apple-iphone-13-mini-and-android-without-others-knowing-drfone-by-drfone-virtual-ios/"><u>Hide location on Apple iPhone 13 mini and Android without others knowing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/embedding-ical-into-your-windows-system-without-hassle/"><u>Embedding iCal Into Your Windows System without Hassle</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-mastering-ipad-for-time-lapse-cinematography-for-2024/"><u>[Updated] Mastering iPad for Time-Lapse Cinematography for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-edge-approaches-to-adjacent-and-distinct-windows-partition-merging/"><u>Cutting-Edge Approaches to Adjacent and Distinct Windows Partition Merging</u></a></li>
<li><a href="https://win11-tips.techidaily.com/can-pressing-prtscn-launch-snipping-tool-steps-to-halt/"><u>Can Pressing PrtScn Launch Snipping Tool? Steps to Halt</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-maximizing-earnings-on-snapchat-platforms/"><u>[Updated] 2024 Approved  Maximizing Earnings on Snapchat Platforms</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-instant-guide-obtaining-safe-free-vlc-media-player-on-a-mac/"><u>[New] Instant Guide  Obtaining Safe, Free VLC Media Player on a Mac</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-professional-gear-tips-gopro-edition-for-2024/"><u>[New] Professional Gear Tips  GoPro Edition for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-edit-like-a-pro-quicktime-video-editing-on-mac-made-easy/"><u>In 2024, Edit Like a Pro QuickTime Video Editing on Mac Made Easy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-examine-excel-data-in-notepad/"><u>How to Examine Excel Data in Notepad</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-unlock-fb-story-potential-4-effective-techniques/"><u>2024 Approved  Unlock FB Story Potential - 4 Effective Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-epic-launcher-sign-in-on-pc/"><u>Mastering the Art of Epic Launcher Sign-In on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoidance-and-remediation-for-a-frozen-resource-monitor-app-in-windows-11/"><u>Avoidance and Remediation for a Frozen Resource Monitor App in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-apk-deployment-for-win-11-users/"><u>Instant APK Deployment for Win 11 Users</u></a></li>
<li><a href="https://techidaily.com/recover-apple-iphone-12-pro-data-from-ios-itunes-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover Apple iPhone 12 Pro Data From iOS iTunes | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-zooming-in-and-out-like-a-storytelling-pro-insta-tips/"><u>In 2024, Zooming in and Out Like a Storytelling Pro  Insta Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-dxgierrordeviceremoved-error-in-windows-10-and-11/"><u>How to Fix the DXGI_ERROR_DEVICE_REMOVED Error in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lowering-dropbox-cpu-utilization-on-windows-machines/"><u>Lowering Dropbox CPU Utilization on Windows Machines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masteringdarkmodesettingforwindowstexteditor/"><u>MasteringDarkModeSettingForWindowsTextEditor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-error-0x0000004e-in-windows-devices/"><u>Navigating Error 0X0000004E in Windows Devices</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-disabled-iphone-6sipad-without-computer-drfone-by-drfone-ios/"><u>In 2024, How to Unlock Disabled iPhone 6s/iPad Without Computer | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-introduction-to-windows-exepe-file-formats/"><u>An Introduction to Windows EXE/PE File Formats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ceasing-windows-notification-for-updates/"><u>Ceasing Windows Notification for Updates</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-discover-the-power-of-wax-a-free-video-editor-tutorial/"><u>New 2024 Approved Discover the Power of Wax A Free Video Editor Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-subnet-tweak-for-experienced-users-win11/"><u>Effortless Subnet Tweak for Experienced Users, Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-hidden-options-mastery-of-lost-control-configurations/"><u>Explore Hidden Options: Mastery of Lost Control Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leap-forward-in-windows-video-management-integrate-tdarrs-distributed-capabilities/"><u>Leap Forward in Windows Video Management: Integrate Tdarr's Distributed Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/manipulating-windows-files-disabling-read-only-status/"><u>Manipulating Windows Files: Disabling Read-Only Status</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-revolutionize-your-shooting-essential-camera-gear-guide-for-2024/"><u>[Updated] Revolutionize Your Shooting  Essential Camera Gear Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-yourphoneexe-malware-insights-on-windows-87/"><u>Is YourPhone.exe Malware? Insights on Windows 8/7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-terminal-usage-make-it-primary-choice/"><u>Elevate Your Terminal Usage: Make It Primary Choice</u></a></li>
<li><a href="https://driver-install.techidaily.com/1720063335352-tp-link-usb-wi-fi-adapter-windows-get-it-free-today/"><u>TP Link USB Wi-Fi Adapter: Windows, Get It Free Today!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-tools-unveiled-for-the-curious-newbie/"><u>Windows Tools Unveiled for the Curious Newbie</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-manage-secure-boot-and-tpm-settings-on-virtualbox-70/"><u>Step-by-Step Guide to Manage Secure Boot & TPM Settings on VirtualBox 7.0</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-pioneering-tiktok-creations-with-foundational-tools/"><u>[Updated] Pioneering TikTok Creations with Foundational Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-accessibility-issues-of-purchased-software-on-ms-marketplace/"><u>Unlocking Accessibility Issues of Purchased Software on MS Marketplace</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-do-i-sim-unlock-my-iphone-se-2020-by-drfone-ios/"><u>In 2024, How Do I SIM Unlock My iPhone SE (2020)?</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-from-live-demos-to-replays-tapping-into-aiseesoft-screencast-potential/"><u>In 2024, From Live Demos to Replays  Tapping Into Aiseesoft Screencast Potential</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-a-step-by-step-guide-to-adding-and-modifying-discord-roles/"><u>[New] In 2024, A Step-by-Step Guide to Adding and Modifying Discord Roles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/multiple-routes-for-opening-utilities-on-windows-systems/"><u>Multiple Routes for Opening Utilities on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-windows-handbrake-blockage-now/"><u>Unlock Windows HandBrake Blockage Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halt-the-haste-of-edges-tabs-in-w11/"><u>Halt the Haste of Edge's Tabs in W11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/dissecting-the-importance-of-using-itop-for-capture-for-2024/"><u>Dissecting the Importance of Using ITop for Capture for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-optimal-audio-tuning-parameters-for-gadgets/"><u>New In 2024, Optimal Audio Tuning Parameters for Gadgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-unlock-your-onedrive-on-a-windows-machine/"><u>How To Unlock Your OneDrive on a Windows Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/envisioning-the-ideal-user-experience-in-windows-11/"><u>Envisioning the Ideal User Experience in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploiting-windows-11s-error-diagnostic-solutions/"><u>Exploiting Windows 11'S Error Diagnostic Solutions</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-hidefake-snapchat-location-on-your-poco-x6-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Hide/Fake Snapchat Location on Your Poco X6 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-insights-employing-law-filters-within-windows/"><u>Essential Insights: Employing LAW Filters Within Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-strategies-against-locked-out-windows-pin/"><u>Immediate Strategies Against Locked-Out Windows PIN</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-gopro-quik-for-computer-download-and-alternative-options-for-2024/"><u>New GoPro Quik for Computer Download and Alternative Options for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-clear-the-focus-wallpaper-icon-on-windows-11/"><u>How to Clear the Focus Wallpaper Icon on Windows 11</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-premium-black-gopro-battery-units-with-official-chargers/"><u>[New] Premium Black GoPro Battery Units with Official Chargers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-guide-to-the-best-fileshare-apps-on-a-windows-laptop/"><u>Exclusive Guide to the Best Fileshare Apps on a Windows Laptop</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/resize-with-confidence-a-comprehensive-guide-to-image-ratios-for-2024/"><u>Resize with Confidence A Comprehensive Guide to Image Ratios for 2024</u></a></li>
</ul></div>
