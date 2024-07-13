---
title: Activating Hyper-V on Your Windows 11 PC
date: 2024-07-12T17:48:53.795Z
updated: 2024-07-13T17:48:53.795Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Activating Hyper-V on Your Windows 11 PC
excerpt: This Article Describes Activating Hyper-V on Your Windows 11 PC
keywords: Hyper-V Enablement,Windows 11 Hyper-V,Activate Hyper-V Win11,Hyper-V On Win11 PC,Turning On Hyper-V,Hyper-V Startup W11,Enable Virtualization
thumbnail: https://thmb.techidaily.com/0bb0f990e78102071e50c31f7028b725d7f6b1084837b38e9693d564989750d9.jpg
---

## Activating Hyper-V on Your Windows 11 PC

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

 Hyper-V is available as an optional feature on Windows 11 Pro, Enterprise, and Education. To check your edition of Windows, go to **Settings > System > About**. Then, check the **Windows specifications** section to find your Windows edition.

 If you have the Home edition, here’s how to [install Hyper-V on Windows 11 Home](https://www.makeuseof.com/install-hyper-v-windows-11-home/). All you have to do is run a bat script to install Hyper-V on non-compatible systems.

 Depending on how many virtual machines and types of applications you intend to run, you may need more resources to run the virtual machines smoothly.

 In addition, you need to enable Hardware Virtualization in BIOS. It is an essential feature to run virtual machines on your Windows system but often disabled by default.

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
6. Hit **Enter** and then select **Enabled** from the options.
7. Press **F10** to save the changes and exit **BIOS**.
8. Your PC will restart and apply the changes. This may take a while, so wait till your system is fully restarted.

 After restart, you can enable Hyper-V on Windows 11\. Here’s how to do it.

## 1\. Turn On Hyper-V in Windows 11 Via Control Panel

![enable hyper v windows features control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hyper-v-windows-features-control-panel.png)

 You can enable Hyper-V using the Windows Features dialog. You can access Windows Features to [add or remove optional features in Windows 11](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) from the Control Panel. Here’s how to do it.

1. Press **Win + R** to open **Run**.
2. Type **control** and click **OK** to open the Control Panel.
3. In the Control Panel, go to **Programs > Programs and Features.**
4. In the left pane, click on **Turn Windows features on or off.**
5. In the **Windows Features** dialog, select **Hyper-V.** If you expand Hyper-V, you will see **Hyper-V Management Tools** and **Hyper-V Platforms.**
6. Make sure both the options are selected and click **OK**. Since these are optional features, Windows will begin to install and enable them on your PC. This process may take some time to complete.
7. Once completed, click on **Restart Now** to restart, and apply the changes.

 After the restart, search for **Hyper-V** and click on **Hyper-V Manager** to create virtual machines in Windows 11\.

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

## 3\. Enable Hyper-V Using PowerShell

![enable hyper v windows 11 powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hyper-v-windows-11-powershell.png)

 If you prefer Windows PowerShell over Command Prompt, you can also enable Hyper-V using the shell application.

 However, unlike Command Prompt, PowerShell uses the enable-WindowsOptional features cmdlet to enable optional features in a Windows image.

 To enable Hyper-V using PowerShell:

1. Press the **Win** key, and type **powershell**. Then, right-click on **PowerShell** and select **Run as Administrator.**
2. In the PowerShell window, type the following shell command and hit Enter:  
`Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V-All`
3. PowerShell will run the cmdlet and initiate the Hyper-V enabling process. If successful, you will be asked to restart your PC.
4. Type **Y** to confirm, and your PC will restart to apply the changes and enable a new feature.

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
<li><a href="https://fake-location.techidaily.com/can-life360-track-you-when-your-vivo-y100-5g-is-off-drfone-by-drfone-virtual-android/"><u>Can Life360 Track You When Your Vivo Y100 5G is off? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-errors-fixing-loadlib-failure-87/"><u>Navigating Windows Errors: Fixing LoadLib Failure 87</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-error-0xc00d36b4-from-win11-devices/"><u>Eliminating Error 0XC00D36B4 From Win11 Devices</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-ultimate-guide-to-zoom-transcription-software-fee-based-for-2024/"><u>[Updated] Ultimate Guide to Zoom Transcription Software (Fee-Based) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-windows-vigilance-tracking-top-7-potential-infection-pathways/"><u>Essential Windows Vigilance: Tracking Top 7 Potential Infection Pathways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boundary-setting-for-insider-release-access/"><u>Boundary Setting for Insider Release Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-adobes-secrets-ms-store-version-acquisition/"><u>Unlocking Adobe's Secrets: MS Store Version Acquisition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-aggregatorhostexe-in-windows-secure-exploring-its-role/"><u>Is AggregatorHost.exe in Windows Secure? Exploring Its Role</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-ui-evolution-focusing-on-the-taskbar/"><u>Windows UI Evolution - Focusing on the Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-administered-window-on-os-x/"><u>Guidelines for Administered Window on OS X</u></a></li>
<li><a href="https://win11.techidaily.com/3-key-steps-for-a-quick-return-to-desktop-in-wins-1011/"><u>3 Key Steps for a Quick Return to Desktop in Wins 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-roblox-availability-tackling-windows-settings-issue/"><u>Unblocking Roblox Availability: Tackling Windows Settings Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-handle-apple-photo-imports-that-go-wrong-on-pcs-windows/"><u>How to Handle Apple Photo Imports That Go Wrong on PCs (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/file-upload-woes-overcoming-chromes-challenges-on-windows/"><u>File Upload Woes: Overcoming Chrome's Challenges on Windows</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-innovative-igtv-thumbnail-upgrades-guide/"><u>In 2024, Innovative IGTV Thumbnail Upgrades Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-taskbar-icons-that-dont-pop-up/"><u>Correcting Taskbar Icons that Don't Pop Up</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-advanced-taskbar-features-in-windows-11/"><u>Activating Advanced Taskbar Features in Windows 11</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/in-2024-split-cut-and-edit-videos-for-free-our-top-recommendations/"><u>In 2024, Split, Cut, and Edit Videos for Free Our Top Recommendations</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/screen-based-strategies-to-speak-more-fluently/"><u>Screen-Based Strategies to Speak More Fluently</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-discover-the-hottest-snapchat-tips-for-todays-trends/"><u>[New] In 2024, Discover the Hottest Snapchat Tips for Today's Trends</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-maximum-speed-for-your-digital-purchases-at-microsoft/"><u>Unlock Maximum Speed for Your Digital Purchases at Microsoft</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-find-my-iphone-without-apple-id-on-your-iphone-14-by-drfone-ios/"><u>In 2024, How to Remove Find My iPhone without Apple ID On your iPhone 14?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-fix-the-windows-services-tool-when-it-wont-open-or-respond/"><u>7 Ways to Fix the Windows Services Tool When It Won't Open or Respond</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-amp-up-your-sessions-with-essential-tips-from-zooms-changer-suite/"><u>2024 Approved  Amp Up Your Sessions with Essential Tips From Zoom's Changer Suite</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-file-organization-grouped-directories-at-a-glance-on-windows-11/"><u>Enhance File Organization - Grouped Directories at a Glance on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-non-operational-amd-radeon-ssp-on-windows/"><u>Troubleshooting Non-Operational AMD Radeon SSP on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-security-clean-up-clearing-the-old-protection-data/"><u>Windows Security Clean-Up: Clearing the Old Protection Data</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-fix-facebook-story-not-uploading-problem/"><u>[Updated] In 2024, Fix Facebook Story Not Uploading Problem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/excelling-at-windows-11-desktop-image-standards/"><u>Excelling at Windows 11 Desktop Image Standards</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-laptop-or-desktop-windows-era/"><u>Unveiling Laptop or Desktop Windows Era</u></a></li>
<li><a href="https://techidaily.com/how-to-update-apple-iphone-13-to-the-latest-iosipados-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update Apple iPhone 13 to the Latest iOS/iPadOS Version? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-8-plus-to-other-iphone-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 8 Plus to other iPhone? | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-instant-ideas-recording-ppts-with-ease/"><u>[Updated] Instant Ideas  Recording PPTs with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-against-zero-x-eight-oh-three-one-f-failures-in-mail-apps/"><u>Winning Against Zero X Eight Oh Three One F Failures in Mail Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-system-speed-strategies-for-virtual-memory-upgradation-in-windows-11/"><u>Elevating System Speed: Strategies for Virtual Memory Upgradation in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-vocal-expressions-to-written-words-with-windows-whisper/"><u>From Vocal Expressions to Written Words with Windows Whisper</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-the-key-differences-in-exe-and-msi-formats/"><u>Identifying the Key Differences in EXE & MSI Formats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/onedrive-error-resolution-guide-for-windows-enthusiasts/"><u>OneDrive Error Resolution Guide for Windows Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-tutorial-making-sense-of-blue-screen-in-w11/"><u>Comprehensive Tutorial: Making Sense of Blue Screen in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-winning-software-for-the-ultimate-pc/"><u>Discover Winning Software for the Ultimate PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-sound-failure-in-audacity-windows-11-and-11/"><u>Eliminating Sound Failure in Audacity, Windows 11 & 11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unlock-your-visuals-quick-and-costless-video-downloads-on-pinterest-for-2024/"><u>Unlock Your Visuals  Quick & Costless Video Downloads on Pinterest for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-becoming-a-master-of-instagrams-video-dialogue-dynamics/"><u>[New] 2024 Approved  Becoming a Master of Instagram's Video Dialogue Dynamics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-11s-code-0x0000004e-hurdle/"><u>Addressing Windows 11'S Code 0X0000004E Hurdle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-subnet-shift-a-guide-to-win11-networks/"><u>Master the Subnet Shift: A Guide to Win11 Networks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-a-tidy-desktop-unnecessary-windows-software-list/"><u>Get a Tidy Desktop: Unnecessary Windows Software List</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-asmr-viewers-essentials-explained/"><u>[New] In 2024, ASMR Viewers' Essentials Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-network-gaps-win-10-and-11-written-for-telnet-users/"><u>Bridging Network Gaps: Win 10 & 11' Written for Telnet Users</u></a></li>
</ul></div>
