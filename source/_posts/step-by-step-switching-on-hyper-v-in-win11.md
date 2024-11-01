---
title: "Step-by-Step: Switching On Hyper-V in Win11"
date: 2024-10-31T18:43:55.298Z
updated: 2024-11-01T19:42:54.633Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Step-by-Step: Switching On Hyper-V in Win11"
excerpt: "This Article Describes Step-by-Step: Switching On Hyper-V in Win11"
keywords: Hyper-V Enablement,Windows 11 Hyper-V Guide,Activate Hyper-V Win11,Turning on Win11 Hyper-V,Win11 Hyper-V Setup,Hyper-V Activation Win11,Enabling Hyper-V in Win11
thumbnail: https://thmb.techidaily.com/88bfebb08e4cbb8d0a68e78c0297b8f1e363343f342702915251fd121c5a13e0.jpg
---

## Step-by-Step: Switching On Hyper-V in Win11

 Hyper-V is Microsoft's in-house virtualization solution for Windows 11\. It lets you create virtual machines and run them on virtual hardware. That said, if you want to use Hyper-V on your computer, you will need to enable it first.

 In this article, we show you the how to enable Hyper-V in Windows 11 and create virtual machines without third-party tools.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Are the Use Cases for Hyper-V?

 Hyper-V is a native virtualization tool that allows you to run multiple operating systems on your system virtually without affecting your host OS.

 With Hyper-V, you don’t have to rely on third-party hypervisor solutions such as VirtualBox and VMware Workstation. [Hyper-V has plenty of use cases for individuals](https://www.makeuseof.com/tag/reasons-start-using-virtual-machine/), and even more for organizations.

 Some Hyper-V virtual machine use cases include:

* Run and test software for an older version of Windows or non-Windows OS
* Test software on multiple operating systems using multiple virtual machines on a single host system.
* Offers disaster recovery features including live migration and failover clustering for increased uptime.
* Create and run virtual machines in isolation for improved security.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880956/19272" target="_top" id="1880956">
  <img src="//a.impactradius-go.com/display-ad/19272-1880956" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880956/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135365/19272" target="_top" id="2135365">
  <img src="//a.impactradius-go.com/display-ad/19272-2135365" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135365/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Next, use the down arrow key to highlight the **Virtualization Technology** option.  
![enable hardware virtualization bios hp laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hardware-virtualization-bios-hp-laptoop.jpg)
6. Hit **Enter** and then select **Enabled** from the options.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134240/18498" target="_top" id="2134240">
  <img src="//a.impactradius-go.com/display-ad/18498-2134240" border="0" alt="https://techidaily.com" width="540" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134240/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100542/7443" target="_top" id="2100542">
  <img src="//a.impactradius-go.com/display-ad/7443-2100542" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100542/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139120/17108" target="_top" id="2139120">
  <img src="//a.impactradius-go.com/display-ad/17108-2139120" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139120/17108" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<span id="1630055">
					<video width="192" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1630055.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18460-1630055">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1630055.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:120px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fcaperobbin.sjv.io%2Fc%2F5597632%2F1630055%2F18460'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1630055/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-final-cut-pros-essential-effect-enhancers-the-top-10-selection/"><u>[New] 2024 Approved Final Cut Pro’s Essential Effect Enhancers The Top 10 Selection</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-professional-perception-pioneering-hdr-art-with-photoshop/"><u>[New] Professional Perception Pioneering HDR Art with PhotoShop</u></a></li>
<li><a href="https://win-news.techidaily.com/aucun-moyen-pour-ouvrir-les-dossiers-de-courriel-par-defaut-sur-microsoft-outlook-solution-rapide/"><u>Aucun Moyen Pour Ouvrir Les Dossiers De Courriel Par Défaut Sur Microsoft Outlook - Solution Rapide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decreasing-high-cpu-demand-of-cloud-storage-on-windows-pcs/"><u>Decreasing High CPU Demand of Cloud Storage on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-file-handling-excellence-harnessing-win-11s-copy-and-move/"><u>Elevate File Handling Excellence: Harnessing Win 11’S Copy & Move</u></a></li>
<li><a href="https://techidaily.com/how-to-erase-apple-iphone-11-pro-data-permanently-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>How To Erase Apple iPhone 11 Pro Data Permanently | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-phone-touchscreen-of-honor-70-lite-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Phone Touchscreen Of Honor 70 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-propel-your-profile-5-core-techniques-for-instagram-marketing-gurus/"><u>In 2024, Propel Your Profile 5 Core Techniques for Instagram Marketing Gurus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-entry-point-not-found-on-windows-pc/"><u>Overcoming 'Entry Point Not Found' On Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-speedy-epic-game-installations/"><u>Quick Fixes for Speedy Epic Game Installations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quieting-chrome-ads-and-alerts-on-windows-machines/"><u>Quieting Chrome Ads & Alerts on Windows Machines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-run-history-loss-issue/"><u>Resetting Run History Loss Issue</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/steps-to-saving-fb-status-video-memories/"><u>Steps to Saving Fb Status Video Memories</u></a></li>
<li><a href="https://driver-install.techidaily.com/swift-intel-chipset-patch-installation/"><u>Swift Intel Chipset Patch Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/vivetool-explained-how-to-access-next-gen-windows-tools/"><u>ViVeTool Explained: How to Access Next-Gen Windows Tools</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    