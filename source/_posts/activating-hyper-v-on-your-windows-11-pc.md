---
title: Activating Hyper-V on Your Windows 11 PC
date: 2024-08-16T01:19:04.595Z
updated: 2024-08-17T01:19:04.595Z
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Add Hyper-V to Windows 11 Using Command Prompt

![enable hyper v command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hyper-v-command-prompt.png)
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
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
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Disable Hyper-V in Windows 11

 While Hyper-V is safe to enable and use, you can disable it as easily using PowerShell. Useful if the virtualization tool causes conflict with your antivirus solution and other apps.

 To disable Hyper-V using PowerShell:

* Open **PowerShell** as administrator.
* In the PowerShell window, type the following command and press Enter:  
`Disable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V-All`
* Wait for the success message to appear and close PowerShell.
* Restart your PC to apply the changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
## How to Configure Hyper-V Settings

![hyper v manager windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hyper-v-manager-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once Hyper-V is up and running, you can configure some settings to optimize your virtual machines for optimal performance. Here are a few settings you can configure before creating a virtual machine. You can access these settings from the right pane in Hyper-V Manager.

* **Hyper-V Settings:** You can configure your virtual hard disk and virtual machine location, configure NUMA spanning storage migration, and allow enhanced session mode. On the user side, it lets you configure the virtual machine's keyboard and the mouse release key.
* **Virtual Switch Manager:** It lets you create External, Internal, or Private switches. Virtual switches are bound to the physical network adapter to access the network.
* **Integration services:** You can choose from and enable/disable a host of integration services, including Heartbeat, Key-Value pair exchange, Time synchronization, and Volume shadow copy requestor (VSS) to enhance the performance and functionality of your virtual machine.

![Windows admin center console home](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-admin-center-console-home.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->

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
<li><a href="https://video-capture.techidaily.com/new-in-2024-advanced-techniques-capturing-teams-screen-content/"><u>[New] In 2024, Advanced Techniques  Capturing Teams' Screen Content</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-techniques-for-extracting-and-storing-instagram-video-files-pcmac-systems/"><u>[New] Techniques for Extracting and Storing Instagram Video Files (PC/Mac Systems)</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-transforming-skype-sessions-with-proactive-zoom-tactics/"><u>2024 Approved  Transforming Skype Sessions with Proactive Zoom Tactics</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-teach-you-to-transfer-files-from-nokia-g42-5g-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways To Teach You To Transfer Files from Nokia G42 5G to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-a-three-dimensional-soundscape-in-windows-11/"><u>Achieving a Three-Dimensional Soundscape in Windows 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/advanced-workshop-naming-service-2023/"><u>Advanced Workshop Naming Service 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/audio-visual-assurance-verify-windows-equipment-before-calling/"><u>Audio Visual Assurance: Verify Windows Equipment Before Calling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-storage-demands-on-windows-os/"><u>Decoding the Storage Demands on Windows OS</u></a></li>
<li><a href="https://location-social.techidaily.com/edit-and-send-fake-location-on-telegram-for-your-apple-iphone-13-pro-in-3-ways-drfone-by-drfone-virtual-ios/"><u>Edit and Send Fake Location on Telegram For your Apple iPhone 13 Pro in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-search-on-windows-11-the-top-5-must-knows/"><u>Elevating Search on Windows 11: The Top 5 Must-Knows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-0x800f0845-from-windows-updates/"><u>Eradicating 0X800f0845 From Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-resolving-outlook-errors-on-windows/"><u>Expert Tips: Resolving Outlook Errors on Windows</u></a></li>
<li><a href="https://games-able.techidaily.com/exploring-why-gamer-friendly-monitors-are-overrated/"><u>Exploring Why Gamer-Friendly Monitors Are Overrated</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-and-restore-your-microsoft-store-registrations-win-11/"><u>Fix and Restore Your Microsoft Store Registrations (Win 11)</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-4-sim-location-trackers-to-easily-find-your-lost-samsung-galaxy-a14-4g-device-by-drfone-android/"><u>In 2024, Top 4 SIM Location Trackers To Easily Find Your Lost Samsung Galaxy A14 4G Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-advanced-shortcuts-into-windows-explorer-menus/"><u>Integrating Advanced Shortcuts Into Windows Explorer Menus</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/obs-studio-vs-bandicam-which-is-better-for-2024/"><u>OBS Studio vs Bandicam  Which Is Better for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-persistent-microsoft-edge-shortcuts/"><u>Preventing Persistent Microsoft Edge Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-functionality-of-windows-photo-viewer-in-win11/"><u>Restoring Functionality of Windows Photo Viewer in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-missing-data-from-windows-1011s-search-feature/"><u>Restoring Missing Data From Windows 10/11'S Search Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-5-best-pc-optimization-tools-on-a-windows-pc/"><u>The 5 Best PC Optimization Tools on a Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-hidden-perils-behind-budget-windows-activation-codes/"><u>The Hidden Perils Behind Budget Windows Activation Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-surface-computer-firmware-update-manual/"><u>The Ultimate Surface Computer Firmware Update Manual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-altering-window-icons-distance-on-11plus-windows/"><u>Title: Altering Window Icons' Distance on 11+ Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-tackling-steam-disk-errors/"><u>Understanding and Tackling Steam Disk Errors</u></a></li>
<li><a href="https://buynow-info.techidaily.com/unveiling-the-pros-and-cons-of-googles-flagship-contender-a-deep-dive-into-the-pixel-tale/"><u>Unveiling the Pros and Cons of Google's Flagship Contender: A Deep Dive Into the Pixel Tale</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrading-graphic-memory-in-windows-11-systems/"><u>Upgrading Graphic Memory in Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-wrinkle-free-up-operator-installation/"><u>Windows Wrinkle? Free Up Operator Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/workflow-enhancer-integrating-sticky-notes-into-your-windows-morning-ritual/"><u>Workflow Enhancer: Integrating Sticky Notes Into Your Windows Morning Ritual</u></a></li>
</ul></div>
