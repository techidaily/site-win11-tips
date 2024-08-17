---
title: Resolving Shortage of Physical Storage Space (VM) Errors
date: 2024-08-16T02:16:33.858Z
updated: 2024-08-17T02:16:33.858Z
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

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
## 3\. Expand the Virtual Memory for the Virtual Machine

 The “not enough physical memory” error can occur because not enough virtual memory has been allocated to the virtual machine. You can expand a virtual machine’s memory allocation in VMWare like this:

1. Open your VMware software.
2. Right-click the virtual machine for which you need to fix the error and select**Settings** .
3. Increase the virtual machine’s memory allocation with the bar slider. That amount should always be higher than your PC’s available RAM.  
![The memory bar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-memory-bar.jpg)
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
## 5\. Delete a Recent Windows Update

 The “not enough physical memory” error can be caused by a Windows update that conflicts with VMware. So, uninstalling a recent update could fix that issue for some users. Check out our guide about [uninstalling Windows updates](https://www.makeuseof.com/windows-11-uninstall-updates/) for further details on how to apply this potential solution.

![The Installed Updates Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-uninstall-update-option.jpg)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->

## 6\. Perform a Clean Boot

 Performing a clean boot will disable non-essential apps and services from the Windows startup. Clean booting can potentially resolve the “not enough physical memory” in two ways. Applying this troubleshooting method will ensure there aren’t any third-party programs conflicting with VMware and free up RAM for the software.

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-services-tab-in-msconfig.jpg)
<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->

 To disable all third-party startup programs and services, check out the guidelines in our guide on [how to clean boot in Windows](https://www.makeuseof.com/clean-boot-windows-11/) . This will perform a clean boot whenever you restart Windows.

 Try utilizing your VMware virtual machine after clean booting. If this works,

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-mobility-meets-entertainment-top-portable-viewers/"><u>[New] 2024 Approved  Mobility Meets Entertainment  Top Portable Viewers</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-the-key-to-rising-roi-in-facebooks-animated-advertising-sector/"><u>[New] In 2024, The Key to Rising ROI in Facebook's Animated Advertising Sector</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-affordable-pc-screen-grabber-selection-list/"><u>[Updated] 2024 Approved  Affordable PC Screen Grabber Selection List</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-best-10-tiktok-tools-for-professional-video-makers-pc/"><u>2024 Approved  Best 10 TikTok Tools for Professional Video Makers (PC)</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-the-ultimate-guide-to-vivacuts-video-editing-features/"><u>2024 Approved  The Ultimate Guide to VivaCut's Video Editing Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-ways-microsoft-can-improve-windows-11-widgets/"><u>8 Ways Microsoft Can Improve Windows 11 Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-network-access-on-windows-10-and-11-through-telnet/"><u>Boosting Network Access on Windows 10 & 11 Through Telnet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-insufficient-access-block-during-uninstalls/"><u>Bypassing Windows' Insufficient Access Block During Uninstalls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-into-design-mastering-windows-11s-theme-customization/"><u>Dive Into Design: Mastering Windows 11'S Theme Customization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diving-deep-into-identity-unveiling-sids-in-windows-11/"><u>Diving Deep Into Identity: Unveiling SIDs in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-data-safety-embedding-secure-passwords-into-files/"><u>Elevate Data Safety: Embedding Secure Passwords Into Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-frozen-windows-update-pause/"><u>Eliminate Frozen Windows Update Pause</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-the-windows-menu-with-superior-powers/"><u>Enhancing the Windows Menu with Superior Powers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-continuity-of-settings-with-nvidia-control-panel-in-windows-11/"><u>Ensuring Continuity of Settings with NVidia Control Panel in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-overcoming-org-managed-configurations-in-windows-11/"><u>Guidelines for Overcoming Org-Managed Configurations in Windows 11</u></a></li>
<li><a href="https://change-location.techidaily.com/hacks-to-do-pokemon-go-trainer-battles-for-vivo-v27-pro-drfone-by-drfone-virtual-android/"><u>Hacks to do pokemon go trainer battles For Vivo V27 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halt-mspm-errors-windows-based-fixes-required/"><u>Halt MSPM Errors, Windows-Based Fixes Required</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-facebook-cover-video-introduction-size-format-and-time/"><u>In 2024, Facebook Cover Video  Introduction, Size, Format & Time</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-can-i-get-more-stardust-in-pokemon-go-on-motorola-moto-g13-drfone-by-drfone-virtual-android/"><u>In 2024, How can I get more stardust in pokemon go On Motorola Moto G13? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-methods-to-change-gps-location-on-samsung-galaxy-m14-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Methods to Change GPS Location On Samsung Galaxy M14 5G | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-scaling-photography-with-no-detail-degradation/"><u>In 2024, Scaling Photography with No Detail Degradation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-language-shifts-hotkey-techniques-for-multilingual-translation-in-windows-11/"><u>Master Language Shifts: Hotkey Techniques for Multilingual Translation in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-packages-on-pc-the-choco-way-or-wm-approach/"><u>Navigating Packages on PC: The Choco Way or WM Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/run-task-manager-as-an-admin-essential-steps-for-windows-11-users/"><u>Run Task Manager as an Admin: Essential Steps for Windows 11 Users</u></a></li>
<li><a href="https://fake-location.techidaily.com/spoofing-life360-how-to-do-it-on-honor-magic-6-pro-drfone-by-drfone-virtual-android/"><u>Spoofing Life360 How to Do it on Honor Magic 6 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-reducing-system-resource-utilization-by-services/"><u>Strategies for Reducing System Resource Utilization by Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-improve-graphics-performance-on-hogwarts-learning-platform/"><u>Strategies to Improve Graphics Performance on Hogwarts Learning Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-switch-off-microsofts-assistant/"><u>Techniques to Switch Off Microsoft's Assistant</u></a></li>
<li><a href="https://techidaily.com/three-methods-to-recover-lost-data-on-honor-90-pro-by-fonelab-android-recover-data/"><u>Three methods to recover lost data on Honor 90 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-tips-for-overcoming-server-notifications-on-pc-apex-(156-chars/"><u>Top Tips for Overcoming Server Notifications on PC Apex (<156 Chars)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/top-rated-apps-to-elevate-instagram-imagery/"><u>Top-Rated Apps to Elevate Instagram Imagery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-photo-error-on-windows-devices-efficiently/"><u>Troubleshoot Photo Error on Windows Devices Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/undetectable-disk-hiding-methods-in-windows-10-and-11/"><u>Undetectable Disk Hiding Methods in Windows 10 & 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/unlocking-made-easy-the-best-10-apps-for-unlocking-your-infinix-device-by-drfone-android/"><u>Unlocking Made Easy The Best 10 Apps for Unlocking Your Infinix Device</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-top-dual-screen-video-editing-apps-for-mobile-devices/"><u>Updated Top Dual-Screen Video Editing Apps for Mobile Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-a-ram-cache-and-how-do-you-clear-it-on-windows/"><u>What Is a RAM Cache, and How Do You Clear It on Windows?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-taskbar-attachment-techniques/"><u>Windows 11 Taskbar Attachment Techniques</u></a></li>
</ul></div>
