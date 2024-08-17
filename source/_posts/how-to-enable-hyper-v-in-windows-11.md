---
title: How to Enable Hyper-V in Windows 11
date: 2024-08-16T01:45:41.016Z
updated: 2024-08-17T01:45:41.016Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Enable Hyper-V in Windows 11
excerpt: This Article Describes How to Enable Hyper-V in Windows 11
keywords: Hyper-V Windows 11 Setup,Enable Hyper-V Windows 11,Start Hyper-V in Win11,Activate Hyper-V OS 11,Turn on Hyper-V W11,Hyper-V Activation Win11,Launch Hyper-V WS11
thumbnail: https://thmb.techidaily.com/7270266df833210c4618ef395558e4a1dd14a566be785a358865debf94836fef.jpg
---

## How to Enable Hyper-V in Windows 11

 Hyper-V is Microsoft's in-house virtualization solution for Windows 11\. It lets you create virtual machines and run them on virtual hardware. That said, if you want to use Hyper-V on your computer, you will need to enable it first.

 In this article, we show you the how to enable Hyper-V in Windows 11 and create virtual machines without third-party tools.

## What Are the Use Cases for Hyper-V?

 Hyper-V is a native virtualization tool that allows you to run multiple operating systems on your system virtually without affecting your host OS.

 With Hyper-V, you don’t have to rely on third-party hypervisor solutions such as VirtualBox and VMware Workstation. [Hyper-V has plenty of use cases for individuals](https://www.makeuseof.com/tag/reasons-start-using-virtual-machine/), and even more for organizations.

 Some Hyper-V virtual machine use cases include:

* Run and test software for an older version of Windows or non-Windows OS
* Test software on multiple operating systems using multiple virtual machines on a single host system.
* Offers disaster recovery features including live migration and failover clustering for increased uptime.
* Create and run virtual machines in isolation for improved security.

## Prerequisites to Enable Hyper-V on Windows 11
![check Windows 11 edition](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/check-Windows-11-edition.png)
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->

 Hyper-V is available as an optional feature on Windows 11 Pro, Enterprise, and Education. To check your edition of Windows, go to **Settings > System > About**. Then, check the **Windows specifications** section to find your Windows edition.

 If you have the Home edition, here’s how to [install Hyper-V on Windows 11 Home](https://www.makeuseof.com/install-hyper-v-windows-11-home/). All you have to do is run a bat script to install Hyper-V on non-compatible systems.

 Depending on how many virtual machines and types of applications you intend to run, you may need more resources to run the virtual machines smoothly.

 In addition, you need to enable Hardware Virtualization in BIOS. It is an essential feature to run virtual machines on your Windows system but often disabled by default.

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
## How to Enable Hardware Virtualization in BIOS

 On compatible systems, you can enable Hardware Virtualization in BIOS. The below steps are for an HP computer. If you are using a custom-made PC or laptop from another manufacturer, refer to the user manual for detailed instruction. If not, refer to our general guide to [enter the BIOS on Windows](https://www.makeuseof.com/tag/enter-bios-computer/).

 To enable Hardware Virtualization in BIOS:

1. Shut down your PC if it is powered on.
2. Press the **Power** button to power on the system and start pressing the **Esc** key to view the **Startup Menu.**
3. In the **Startup Menu**, press **F10** to enter the **BIOS setup.**  
![Startup menu hp laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/Startup-menu-hp-laptop.jpg)
4. In the BIOS Setup Utility, use the arrow key and open the **Configuration** tab.
5. Next, use the down arrow key to highlight the **Virtualization Technology** option.  
![enable hardware virtualization bios hp laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hardware-virtualization-bios-hp-laptoop.jpg)
<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Hit **Enter** and then select **Enabled** from the options.
7. Press **F10** to save the changes and exit **BIOS**.
8. Your PC will restart and apply the changes. This may take a while, so wait till your system is fully restarted.

 After restart, you can enable Hyper-V on Windows 11\. Here’s how to do it.

## 1\. Turn On Hyper-V in Windows 11 Via Control Panel
![enable hyper v windows features control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hyper-v-windows-features-control-panel.png)
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can enable Hyper-V using the Windows Features dialog. You can access Windows Features to [add or remove optional features in Windows 11](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) from the Control Panel. Here’s how to do it.

1. Press **Win + R** to open **Run**.
2. Type **control** and click **OK** to open the Control Panel.
3. In the Control Panel, go to **Programs > Programs and Features.**
4. In the left pane, click on **Turn Windows features on or off.**
5. In the **Windows Features** dialog, select **Hyper-V.** If you expand Hyper-V, you will see **Hyper-V Management Tools** and **Hyper-V Platforms.**
6. Make sure both the options are selected and click **OK**. Since these are optional features, Windows will begin to install and enable them on your PC. This process may take some time to complete.
7. Once completed, click on **Restart Now** to restart, and apply the changes.

 After the restart, search for **Hyper-V** and click on **Hyper-V Manager** to create virtual machines in Windows 11\.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
## 2\. Add Hyper-V to Windows 11 Using Command Prompt
![enable hyper v command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hyper-v-command-prompt.png)

 Command Prompt offers a fast and efficient way to perform repetitive tasks. You can use the DISM (Deployment Image Servicing and Management) command-line tool to access and install optional Windows features via Command Prompt.

 Follow these steps to enable Hyper-V on Windows 11 using Command Prompt:

1. Press the **Win** key, and type **cmd**. Then, right-click on **Command Prompt** and select **Run as Administrator.**
2. In the Command Prompt window, type the following command and hit Enter to execute:  
`DISM /Online /Enable-Feature /All /FeatureName:Microsoft-Hyper-V`
3. The Deployment Image Servicing and Management tool will start enabling the Hyper-V feature and show the progress on the Command Prompt.
4. Once the operation is completed successfully, you will need to restart your PC. So, press **Y** on your keyboard to confirm the action.

 After your PC restarts, you can open and [use the Hyper-V Manager to create virtual machines](https://www.makeuseof.com/tag/create-virtual-machine-using-windows-10-hyper-v/).

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
## 3\. Enable Hyper-V Using PowerShell
![enable hyper v windows 11 powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hyper-v-windows-11-powershell.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->

 If you prefer Windows PowerShell over Command Prompt, you can also enable Hyper-V using the shell application.

 However, unlike Command Prompt, PowerShell uses the enable-WindowsOptional features cmdlet to enable optional features in a Windows image.

 To enable Hyper-V using PowerShell:

1. Press the **Win** key, and type **powershell**. Then, right-click on **PowerShell** and select **Run as Administrator.**
2. In the PowerShell window, type the following shell command and hit Enter:  
`Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V-All`
3. PowerShell will run the cmdlet and initiate the Hyper-V enabling process. If successful, you will be asked to restart your PC.
4. Type **Y** to confirm, and your PC will restart to apply the changes and enable a new feature.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## How to Disable Hyper-V in Windows 11

 While Hyper-V is safe to enable and use, you can disable it as easily using PowerShell. Useful if the virtualization tool causes conflict with your antivirus solution and other apps.

 To disable Hyper-V using PowerShell:

* Open **PowerShell** as administrator.
* In the PowerShell window, type the following command and press Enter:  
`Disable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V-All`
* Wait for the success message to appear and close PowerShell.
* Restart your PC to apply the changes.

## How to Configure Hyper-V Settings
![hyper v manager windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hyper-v-manager-windows-11.jpg)

 Once Hyper-V is up and running, you can configure some settings to optimize your virtual machines for optimal performance. Here are a few settings you can configure before creating a virtual machine. You can access these settings from the right pane in Hyper-V Manager.

* **Hyper-V Settings:** You can configure your virtual hard disk and virtual machine location, configure NUMA spanning storage migration, and allow enhanced session mode. On the user side, it lets you configure the virtual machine's keyboard and the mouse release key.
* **Virtual Switch Manager:** It lets you create External, Internal, or Private switches. Virtual switches are bound to the physical network adapter to access the network.
* **Integration services:** You can choose from and enable/disable a host of integration services, including Heartbeat, Key-Value pair exchange, Time synchronization, and Volume shadow copy requestor (VSS) to enhance the performance and functionality of your virtual machine.

![Windows admin center console home](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-admin-center-console-home.jpg)

 While the MMC-based Hyper-V manager is functional and built into the OS, consider using the relatively new Windows Admin Center. It is a browser-based management app that lets you manage your servers, virtual machines, local users and groups, and more.

 Download [Windows Admin Center](https://www.microsoft.com/en-in/windows-server/windows-admin-center) from the official Microsoft page and run the installer to give it a go. Once installed, open the app, and it will launch in your default browser, giving you access to a host of management tools.

## Many Ways to Enable Hyper-V in Windows 11

 Hyper-V is a type 1 hypervisor, which means it runs directly on a computer’s hardware. It comes pre-installed, free to use without restriction, and offers linear performance on a consumer-grade system.

 That said, dedicated virtual machines such as the VMWare WorkStation Pro is available on multiple platforms, can be used on older systems, and is more suitable for enterprise solutions. Check out our comparison comparing the three popular hypervisors to find the one that works for you.

 In this article, we show you the how to enable Hyper-V in Windows 11 and create virtual machines without third-party tools.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-ai-generated-podcast-titles-that-stick-with-you/"><u>[New] 2024 Approved  AI-Generated Podcast Titles That Stick With You</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-secure-your-watchlist-free-playlist-extractors-roundup/"><u>[Updated] 2024 Approved  Secure Your Watchlist  Free Playlist Extractors Roundup</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-essential-tips-for-successful-hulu-capturing-on-various-platforms/"><u>[Updated] In 2024, Essential Tips for Successful Hulu Capturing on Various Platforms</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-the-top-5-must-know-for-macos-tiktok-users/"><u>[Updated] The Top 5 Must-Know for macOS TikTok Users</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-accessing-googles-video-conference-platform/"><u>2024 Approved  Accessing Google's Video Conference Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-easy-tips-for-memo-making-in-windows/"><u>7 Easy Tips for Memo-Making in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-routes-to-rescue-your-stream-with-a-fixed-obs-link-on-windows/"><u>7 Routes to Rescue Your Stream with a Fixed OBS Link on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-tutorial-on-windows-1011s-audio-upgrade/"><u>A Comprehensive Tutorial on Windows 10/11'S Audio Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-precise-walkthrough-for-windows-update-resetting/"><u>A Precise Walkthrough for Windows Update Resetting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-digital-dreamland-with-windows-pcs/"><u>Achieving Digital Dreamland with Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-windows-11-and-parallels-confluence-in-macos/"><u>Achieving Windows 11 and Parallels Confluence in MacOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-discrepancies-in-disk-based-discord-queries/"><u>Addressing Discrepancies in Disk-Based Discord Queries</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-issues-with-googles-nearby-sharing-on-desktop-pc/"><u>Addressing Issues with Google's Nearby Sharing on Desktop PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-operative-brightness-fn-button-on-windows-11/"><u>Addressing Non-Operative Brightness Fn Button on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-winrars-summation-anomalies-with-six-fixes/"><u>Addressing WinRAR's Summation Anomalies with Six Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adopt-a-streamlined-approach-to-input-customization/"><u>Adopt a Streamlined Approach to Input Customization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-tips-for-docx-to-pdf-conversion-on-modern-windows/"><u>Advanced Tips for Docx-to-PDF Conversion on Modern Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-windows-tactics-for-hardware-id-retrieval/"><u>Advanced Windows Tactics for Hardware ID Retrieval</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-generated-windows-keys-unveiling-potential-perils/"><u>AI-Generated Windows Keys: Unveiling Potential Perils</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altwindirstat-strategies-for-effective-disk-space-management/"><u>AltWinDirStat Strategies for Effective Disk Space Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assisting-with-utorrent-download-stalls-in-microsoft-environments/"><u>Assisting with uTorrent Download Stalls in Microsoft Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoidance-procedures-for-win-11-mobility-center/"><u>Avoidance Procedures for Win 11 Mobility Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/awaken-your-device-finding-and-fixing-muted-speaker-issues/"><u>Awaken Your Device – Finding & Fixing Muted Speaker Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-act-keeping-high-vitality-in-check-on-windows/"><u>Balancing Act: Keeping High Vitality in Check on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beating-the-system-a-strategy-for-fixing-0x800700e9-in-xbox-game-passwindows-11/"><u>Beating the System: A Strategy for Fixing 0X800700E9 in Xbox Game Pass/Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beyond-boundaries-artificinas-intelligence-in-windows-11/"><u>Beyond Boundaries: Artificinas Intelligence in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blueprints-for-crafting-safe-dialog-box-for-hardware-disconnect/"><u>Blueprints for Crafting Safe Dialog Box for Hardware Disconnect</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719278811623-bypassing-chrome-block-strategies-for-w11-users/"><u>Bypassing Chrome Block: Strategies for W11 Users.</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/core-strategies-for-android-video-capture-for-2024/"><u>Core Strategies for Android Video Capture for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/elevate-your-editing-the-ultimate-list-of-lightroom-luts/"><u>Elevate Your Editing  The Ultimate List of LightRoom LUTs</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/guiding-principles-for-integrating-videos-in-education/"><u>Guiding Principles for Integrating Videos in Education</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-google-frp-on-s17e-by-drfone-android-unlock-remove-google-frp/"><u>How To Bypass Google FRP on S17e</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-vivo-y55s-5g-2023-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Vivo Y55s 5G (2023)? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-15-pro-max-with-an-apple-watch-and-what-to-do-if-it-doesnt-work-drfone-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 15 Pro Max With an Apple Watch & What to Do if It Doesnt Work | Dr.fone</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-merge-audio-files-into-powerpoint-staging/"><u>In 2024, Merge Audio Files Into PowerPoint Staging</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-zoom-meetings-effectively-utilizing-whiteboard-on-various-devices/"><u>In 2024, Zoom Meetings  Effectively Utilizing Whiteboard on Various Devices</u></a></li>
<li><a href="https://android-frp.techidaily.com/latest-guide-how-to-bypass-meizu-21-frp-without-computer-by-drfone-android/"><u>Latest Guide How To Bypass Meizu 21 FRP Without Computer</u></a></li>
<li><a href="https://activate-lock.techidaily.com/the-ultimate-guide-to-bypassing-icloud-activation-lock-on-iphone-11-by-drfone-ios/"><u>The Ultimate Guide to Bypassing iCloud Activation Lock on iPhone 11</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/top-10-unique-gaming-screen-capture-applications/"><u>Top 10 Unique Gaming Screen Capture Applications</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/top-economical-live-capture-software-suite-for-2024/"><u>Top Economical Live Capture Software Suite for 2024</u></a></li>
</ul></div>
