---
title: "Optimizing OS Setup: A Guide to Installing Win11 in VMWare 17"
date: 2024-08-08T11:02:16.029Z
updated: 2024-08-09T11:02:16.029Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Optimizing OS Setup: A Guide to Installing Win11 in VMWare 17"
excerpt: "This Article Describes Optimizing OS Setup: A Guide to Installing Win11 in VMWare 17"
keywords: Win11 VMSetup,Win11 VirtualWin,OptiOSInstallation,VirtualWin11Guide,Win11 in VMware,EfficientWin11Setup,OptimizedVirtualWin11
thumbnail: https://thmb.techidaily.com/56c09995c4310ae28019d3390616d9116d70341b815aee65c7667ed39de0e4c8.jpg
---

## Optimizing OS Setup: A Guide to Installing Win11 in VMWare 17

 Have you ever tried installing Windows 11 on VMware Workstation Player? It is not as easy as you expect from a Windows OS installation. Microsoft imposed the TPM requirement and secure boot for installing Windows 11\. Fortunately, Oracle introduced TPM virtualization in October 2022 and VMware also caught up sometime later.

 As such, you don’t have to rely on registry hacks to disable the TPM and secure boot requirements while installing Windows 11\. This post will guide you to create a virtual machine and install Windows 11 on it.

## The Prerequisites for Installing Windows 11 on VMware

 Here’s what you will need to install Windows 11 with TPM support in VMware Workstation 17 Player:

1. A Windows 11 ISO image file. Check our detailed guide on[how to download the Windows 11 ISO file](https://www.makeuseof.com/windows-iso-direct-download/) .
2. A Windows 10 or above operating system with TPM 2.0 and virtualization support.
3. The latest version of VMware Workstation 17 Player must be pre-installed on the host system.
4. Adequate computing resources to run Windows 11 as a virtual machine. The list includes 64 GB disk space, 4 GB RAM, and a dual-core x64 processor.

 Once you have the necessary ISO file and the latest copy of VMware on your system, you can proceed to the virtual machine creation and Windows 11 installation.

## How to Install Windows 11 in VMware Workstation 17 Player

 Firstly, we will create a virtual machine in VMware for Windows 11\. Then, we will install Windows 11 on the virtual machine. Lastly, we will install VMware tools to finish setting up the virtual machine.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
### 1\. Create a Windows 11 Virtual Machine

 Here’s how to create a virtual machine for Windows 11 in VMware:

1. Launch VMware Player on your system. On the home page, click on**Create a new virtual machine** option.
2. Select the**I will install the operating system later** radio button and click on the**Next** button.  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
![Creating a Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/creating-a-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)
3. Keep the**Guest Operating System** option as**Windows** and then click on the drop-down menu. Pick the**Windows 11 x64** option and click on the**Next** button.
4. Enter an appropriate name for the new Windows 11 virtual machine. Then, click on the**Browse** button to pick a location on the disk drive for virtual disk creation. Click on**Next** .
5. On the Encryption information page, Choose the encryption type as**Only the files needed to support a TPM are encrypted** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
![Enabling Encryption in Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enabling-encryption-in-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)
6. You need to create an 8-character password to encrypt the virtual machine. Keep the **Remember the password on this machine in Credential Manager** checkbox enabled. Click on the**Next** button to continue.
7. Now, specify the disk capacity and set the maximum disk size to**64 GB** . Increase the space if you want to install multiple programs in the virtual machine.
8. Select the**Split virtual disk into multiple files** option and click on**Next** .  
![Adjusting Disk Capacity of Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/adjusting-disk-capacity-of-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)

 VMware will display a summary of all the settings you picked for the Windows 11 virtual machine. But there’s one thing still missing: you haven’t customized the hardware preferences or added the Windows 11 ISO file to the virtual machine.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
![Configuring resources of Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/configuring-resources-of-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)

1. Click on the**Customize Hardware** button. Under the memory tab, increase the**RAM** allocation to**6 GB** or more to avoid a sluggish Windows 11 experience.
2. Switch to the**Processors** tab and allocate**4 or more cores** to the Windows virtual machine.
3. Next, move to the**New CD/DVD (SATA)** tab, and click on the**Use ISO image file** option located under the**Connection** section.
4. Click on the**Browse** button and select the Windows 11 ISO image file you previously downloaded. Click on the**Open** button.
5. Now, close the Hardware window and click on the**Finish** button to create the new virtual machine.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
### 2\. Install Windows 11 on the Virtual Machine

 Repeat the following steps to install Windows 11 on the newly created virtual machine:

1. Navigate to the left-hand side menu and select the Windows 11 virtual machine. Click on the**Play virtual machine** option.
2. Press any keyboard key to boot from the ISO file. Pick the appropriate language and region and click on the**Next** button. Then, click on the**Install now** button.  
![Installing Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/installing-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)
3. In the Windows setup window, click on the**I don’t have a product key** option.
4. Pick the Windows 11 version (Home, Pro, or Education) and click on the**Next** button.
5. Accept the**End User License Agreement** and select the**Custom** installation option.

1. Click on the**Next** button. Setup will begin the Windows 11 installation. The virtual machine will restart a few times.  
<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Installing Windows 11 Virtual Machine In VMware Workstation 17 Player 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/installing-windows-11-virtual-machine-in-vmware-workstation-17-player-2.jpg)
2. After the machine boots up, select the correct region and click on the**Yes** button. Pick the appropriate keyboard layout.
3. Windows 11 will force you to add a Microsoft account. To avoid this, press**Shift + F10** , type the**oobe\\bypassnro** command, and press the**Enter** key.
4. The virtual machine will restart. Click on the**I don’t have internet** option.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
![Setting Up Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/setting-up-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)
5. Enter a**name** for your Windows PC and assign a**password** . Pick**three security questions** and proceed.  
![Setting Up Windows 11 Virtual Machine In VMware Workstation 17 Player 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/setting-up-windows-11-virtual-machine-in-vmware-workstation-17-player-2.jpg)
6. **Uncheck** all the tracking options on the Privacy settings page and click on the**Accept** button.
7. Wait for the setup to finalize changes and boot to the desktop.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 3\. Install the VMware Tools

 The Windows 11 virtual machine is up and running in VMware. But it appears cropped and very small. Many useful features won’t activate until you install VMware tools in the Windows 11 virtual machine. Repeat the following steps:

1. Go to the top menu of VMware Player and click on the**Player** button.
2. Select the**Manage** option from the drop-down menu and click on the**Install VMware tools** option. It will mount the VMware tools setup image file in Windows File Explorer.  
![Installing VMware Tools](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/installing-vmware-tools.jpg)
3. Press**Win + E** to[launch the File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and open the mounted ISO file drive.
4. Locate and select the**setup64.exe** file. Press**Ctrl + Shift + Enter** to launch the setup with admin privileges.
5. In the VMware tools installation window, click on the**Next** button and select the**Complete** installation option.  
![Installing VMware Tools 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/installing-vmware-tools-2.jpg)
6. Then click on the**Install** button. After the installation completes, click on the**Finish** button.
7. Lastly, click on the**Yes** button to restart the virtual machine to apply changes.  
![Windows 11 VM in VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-11-vm-in-vmware-workstation-17-player.jpg)

 The Windows 11 virtual machine is ready to use. You can even run Windows features like Hyper V and Windows MDAG and Sandbox inside this machine.

## Run Windows 11 on VMware Without Any Registry Hacks

 With TMP emulation, there is no need for registry tweaking to disable secure boot and TPM requirements on Windows 11\. All the features work fine, and you don’t need to switch to another hypervisor program. However, Oracle VirtualBox offers the same TPM virtualization and secure boot features.


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
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-unveiling-the-power-of-three-tiers-in-crafting-fb-ad-engaging-messages/"><u>[New] 2024 Approved  Unveiling the Power of Three Tiers in Crafting FB Ad Engaging Messages</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-exceptional-quality-hd-video-documenters/"><u>[New] Exceptional Quality HD Video Documenters</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-final-thoughts-in-journalistic-styling-for-2024/"><u>[New] Final Thoughts in Journalistic Styling for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-most-effective-5-image-editing-programs-on-iphone-x-7-8/"><u>[New] Most Effective 5 Image Editing Programs on iPhone (X, 7, 8)</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-revamp-your-chat-audio-experience-with-a-personalized-whatsapp-ringtone/"><u>[New] Revamp Your Chat Audio Experience with a Personalized WhatsApp Ringtone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-elevate-your-earning-game-youtube-on-facebook-revenue-strategies-for-2024/"><u>[Updated] Elevate Your Earning Game  YouTube on Facebook Revenue Strategies for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-gear-up-for-greatness-choosing-webcams-for-youtube-excellence/"><u>[Updated] Gear Up for Greatness  Choosing Webcams for YouTube Excellence</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-comprehensive-guide-to-disconnecting-discord-servers/"><u>[Updated] In 2024, Comprehensive Guide to Disconnecting Discord Servers</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-the-social-narrative-this-years-twittale-highlights/"><u>[Updated] In 2024, The Social Narrative  This Year's TwitTale Highlights</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-essentials-of-blurring-photo-borders/"><u>[Updated] The Essentials of Blurring Photo Borders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-ways-to-open-the-control-panel-on-windows/"><u>11 Ways to Open the Control Panel on Windows</u></a></li>
<li><a href="https://extra-information.techidaily.com/2023s-leading-platforms-for-picture-frame-adjustment-techniques-for-2024/"><u>2023'S Leading Platforms for Picture Frame Adjustment Techniques for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-capturecast-unveiling-2023s-best-recording-software/"><u>2024 Approved  CaptureCast  Unveiling 2023'S Best Recording Software</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-professionally-enhancing-photos-with-effective-use-of-3d-lut-filters/"><u>2024 Approved  Professionally Enhancing Photos with Effective Use of 3D LUT Filters</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-uncovering-8-affordable-platform-agnostic-virtual-communication-tools/"><u>2024 Approved  Uncovering 8 Affordable, Platform-Agnostic Virtual Communication Tools</u></a></li>
<li><a href="https://vp-tips.techidaily.com/5-tools-to-make-a-gif-meme-for-2024/"><u>5 Tools to Make a GIF Meme for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-calendar-revolution-customizing-your-scheduling-tool-on-windows-pc/"><u>A Calendar Revolution: Customizing Your Scheduling Tool on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-fresh-windows-beginning-navigating-3-reset-routes/"><u>A Fresh Windows Beginning: Navigating 3 Reset Routes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-guide-to-eliminate-hardware-detection-faults/"><u>A Quick Guide to Eliminate Hardware Detection Faults</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-file-management-with-seamless-multi-folder-crafting-on-windows-pcs/"><u>Accelerate File Management with Seamless Multi-Folder Crafting on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-academic-excellence-winning-strategies-for-efficient-windows-learning/"><u>Achieve Academic Excellence: Winning Strategies for Efficient Windows Learning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-incorrect-side-by-side-setup-on-windows-os/"><u>Addressing 'Incorrect Side-by-Side Setup' On Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-directx-update-problems-in-windows-os/"><u>Addressing DirectX Update Problems in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-insufficient-installation-privilege-issue-on-win-1011/"><u>Addressing Insufficient Installation Privilege Issue on Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-spooler-service-error-on-windows-systems/"><u>Addressing Spooler Service Error on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-taskbar-icon-glitches-in-win-108/"><u>Addressing Taskbar Icon Glitches in Win 10/8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-tactics-for-superior-windows-navigation-eliminating-ls/"><u>Advanced Tactics for Superior Windows Navigation: Eliminating LS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amend-f-key-malfunctions-restore-control-in-windows-11/"><u>Amend: F Key Malfunctions - Restore Control in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/antivirus-alert-7-significant-windows-functions-under-scrutiny/"><u>Antivirus Alert: 7 Significant Windows Functions Under Scrutiny</u></a></li>
<li><a href="https://win11-tips.techidaily.com/are-some-websites-not-opening-in-any-browser-on-windows-7-ways-to-fix-it/"><u>Are Some Websites Not Opening in Any Browser on Windows? 7 Ways to Fix It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-high-temperature-troubleshooting-tips-w11/"><u>Avoiding High-Temperature Troubleshooting Tips: W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-unwanted-termination-messages-in-roblox-games/"><u>Avoiding Unwanted Termination Messages in Roblox Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-windowed-app-movement-windows-task-managing-tips/"><u>Avoiding Windowed App Movement: Windows Task Managing Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-windows-11-lock-screen-effortlessly/"><u>Avoiding Windows 11 Lock Screen Effortlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-the-black-glare-from-window-8-displays/"><u>Banishing the Black Glare From Window 8 Displays</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beyond-code-ai-reshaping-windows-tech-landscape/"><u>Beyond Code: AI Reshaping Windows Tech Landscape</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-system-management-via-cmd/"><u>Boost Your System Management via CMD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719363006980-discover-solutions-for-programs-that-dont-work-on-vistawindows-7/"><u>Discover Solutions for Programs that Don't Work on Vista/Windows 7</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/effortlessly-transferring-your-personal-soundtrack-for-2024/"><u>Effortlessly Transferring Your Personal Soundtrack for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/elegant-endings-selecting-from-free-or-premium-templates/"><u>Elegant Endings  Selecting From Free or Premium Templates</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-realme-gt-5-240w-drfone-by-drfone-virtual-android/"><u>How PGSharp Save You from Ban While Spoofing Pokemon Go On Realme GT 5 (240W)? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-feasible-ways-to-fake-location-on-facebook-for-your-vivo-y27-4g-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Feasible Ways to Fake Location on Facebook For your Vivo Y27 4G | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-fake-snapchat-location-on-samsung-galaxy-f04-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fake Snapchat Location on Samsung Galaxy F04 | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-to-do-if-your-iphone-xs-max-has-bad-esn-or-blacklisted-imei-by-drfone-ios/"><u>In 2024, What to do if your iPhone XS Max has bad ESN or blacklisted IMEI?</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/mastering-facetime-capturing-conversations-live/"><u>Mastering FaceTime  Capturing Conversations Live</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719332049172-swiftly-addressing-windows-faults-with-easy-fixes/"><u>Swiftly Addressing Windows Faults with Easy Fixes!</u></a></li>
<li><a href="https://extra-hints.techidaily.com/unique-voice-customization-for-chrome-os-5-top-cloud-audio-editors-reviewed/"><u>Unique Voice Customization for Chrome OS  5 Top Cloud Audio Editors Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719358153094-unlocking-cloud-storage-integrating-dropbox-and-google-drive-via-c/"><u>Unlocking Cloud Storage: Integrating Dropbox and Google Drive via C:</u></a></li>
</ul></div>
