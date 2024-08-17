---
title: A Comprehensive Guide to Hyper-V Enablement in Win11
date: 2024-08-16T01:13:39.507Z
updated: 2024-08-17T01:13:39.507Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Comprehensive Guide to Hyper-V Enablement in Win11
excerpt: This Article Describes A Comprehensive Guide to Hyper-V Enablement in Win11
keywords: Win11 Hyper-V Setup,Windows 11 VMware Guide,Enabling Hyper-V Win11,Win11 Virtualization Techniques,Win11 Hyper-V Implementation,Advanced Win11 VM Management,Hyper-V Installation Win11
thumbnail: https://thmb.techidaily.com/26d450fdec75a3cb5316781ad73e34df68fc7b736cd85313bb608d818166317c.jpg
---

## A Comprehensive Guide to Hyper-V Enablement in Win11

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->

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
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
4. In the BIOS Setup Utility, use the arrow key and open the **Configuration** tab.
5. Next, use the down arrow key to highlight the **Virtualization Technology** option.  
![enable hardware virtualization bios hp laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hardware-virtualization-bios-hp-laptoop.jpg)
<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Hit **Enter** and then select **Enabled** from the options.
7. Press **F10** to save the changes and exit **BIOS**.
8. Your PC will restart and apply the changes. This may take a while, so wait till your system is fully restarted.

 After restart, you can enable Hyper-V on Windows 11\. Here’s how to do it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
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
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
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
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once Hyper-V is up and running, you can configure some settings to optimize your virtual machines for optimal performance. Here are a few settings you can configure before creating a virtual machine. You can access these settings from the right pane in Hyper-V Manager.

* **Hyper-V Settings:** You can configure your virtual hard disk and virtual machine location, configure NUMA spanning storage migration, and allow enhanced session mode. On the user side, it lets you configure the virtual machine's keyboard and the mouse release key.
* **Virtual Switch Manager:** It lets you create External, Internal, or Private switches. Virtual switches are bound to the physical network adapter to access the network.
* **Integration services:** You can choose from and enable/disable a host of integration services, including Heartbeat, Key-Value pair exchange, Time synchronization, and Volume shadow copy requestor (VSS) to enhance the performance and functionality of your virtual machine.

![Windows admin center console home](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-admin-center-console-home.jpg)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
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
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-a-guide-to-winning-at-game-capturing-with-win10/"><u>[New] 2024 Approved  A Guide to Winning at Game Capturing with Win10</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-framing-character-arcs-on-screen/"><u>[New] Framing Character Arcs on Screen</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-in-2024-top-hd-video-cameras-unveiled/"><u>[New] In 2024, Top HD Video Cameras Unveiled</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/vercome-artificial-watches-for-natural-views/"><u>[New] Overcome Artificial Watches for Natural Views</u></a></li>
<li><a href="https://youtube-data.techidaily.com/09110926-new-supercharge-videos-download-premium-effs/"><u>[New] Supercharge Videos - Download Premium Effs!</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-top-5-ps1-emulators-bringing-classic-games-back/"><u>[Updated] In 2024, Top 5 PS1 Emulators - Bringing Classic Games Back</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-perfecting-your-reel-integrating-music-on-instagram/"><u>[Updated] Perfecting Your Reel  Integrating Music on Instagram</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-ultimate-list-best-trivia-shows-for-general-knowledge-24/"><u>2024 Approved  The Ultimate List - Best Trivia Shows for General Knowledge, '24</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-ultimate-psd-layer-control/"><u>2024 Approved  Ultimate PSD Layer Control</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boot-windows-resolving-black-screen-issues/"><u>Boot Windows: Resolving Black Screen Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breach-the-barrier-onedrive-access-restored-in-windows/"><u>Breach the Barrier: OneDrive Access Restored in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-free-on-windows-with-gpt-alternative/"><u>Breaking Free on Windows with GPT Alternative</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathe-life-back-into-the-escape-function-in-windows-os/"><u>Breathe Life Back Into the Escape Function in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathe-new-life-into-your-typing-9-steps-for-fixing-faulty-keyboard-shortcut-combinations-on-windows/"><u>Breathe New Life Into Your Typing: 9 Steps for Fixing Faulty Keyboard Shortcut Combinations on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathing-new-life-into-wt-color-schemes/"><u>Breathing New Life Into WT: Color Schemes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridge-the-time-gap-chrome-on-pc-error-fixation/"><u>Bridge the Time Gap: Chrome on PC Error Fixation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-data-gaps-the-art-of-file-integration/"><u>Bridging Data Gaps: The Art of File Integration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-life-to-silent-non-responsive-slack-alerts/"><u>Bring Back Life to Silent, Non-Responsive Slack Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/building-a-safe-window-shortcut-for-easy-hardware-disconnect-on-win11/"><u>Building a Safe Window Shortcut for Easy Hardware Disconnect on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-the-brick-wall-top-fixes-for-windows-install-verification-pause/"><u>Bypass the Brick Wall: Top Fixes for Windows Install Verification Pause</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-the-worst-8-bad-habits-in-windows-11-life/"><u>Bypass the Worst: 8 Bad Habits in Windows 11 Life</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-extract-error-1152-in-windows-oses/"><u>Bypassing 'Extract Error 1152 in Windows OSes'</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-bluetooth-connection-required-on-windows-1011/"><u>Bypassing Bluetooth 'Connection Required' On Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-pin-locks-fixes-for-windows-os/"><u>Bypassing PIN Locks: Fixes for Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-quick-access-go-straight-to-file-explorer-via-onedrive/"><u>Bypassing Quick Access: Go Straight to File Explorer via OneDrive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-the-blackout-fixes-for-hiberwipe-errors/"><u>Bypassing the Blackout: Fixes for HiberWipe Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-update-obstacle-uptime-failure-code-0x80246007/"><u>Bypassing Windows Update Obstacle: Uptime Failure, Code 0X80246007</u></a></li>
<li><a href="https://win11-tips.techidaily.com/capturing-cortanas-past-on-a-modern-os/"><u>Capturing Cortana's Past on a Modern OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/capturing-uac-notifications-with-precision/"><u>Capturing UAC Notifications with Precision</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cast-your-canvas-into-the-night-with-paints-dark-mode/"><u>Cast Your Canvas Into the Night with Paint's Dark Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ceasing-high-contrast-display-mode-on-pc/"><u>Ceasing High Contrast Display Mode on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/christmas-trusted-windows-app-gifting-via-ms-store/"><u>Christmas: Trusted Windows App Gifting via MS Store</u></a></li>
<li><a href="https://vp-tips.techidaily.com/cinema-journey-iphone-users-best-choice-for-films/"><u>Cinema Journey  IPhone Users' Best Choice for Films</u></a></li>
<li><a href="https://win-dash.techidaily.com/diagnose-and-fix-razer-barracuda-x-laptop-mic-problems-under-windows-1011-step-by-step-tutorial/"><u>Diagnose & Fix Razer Barracuda X Laptop Mic Problems Under Windows 10/11 - Step-by-Step Tutorial</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/discover-the-samsung-galaxy-z-flip-6-insights-on-price-points-product-launch-date-and-advanced-features-announced/"><u>Discover the Samsung Galaxy Z Flip 6: Insights on Price Points, Product Launch Date & Advanced Features Announced</u></a></li>
<li><a href="https://extra-tips.techidaily.com/elevating-your-tiktoks-dual-effect-adding-methods/"><u>Elevating Your TikToks  Dual Effect-Adding Methods</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-nokia-g310-phone-without-any-data-loss-by-drfone-android/"><u>How to Unlock Nokia G310 Phone without Any Data Loss</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-5-ways-to-track-nokia-c02-without-app-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Ways to Track Nokia C02 without App | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-learning-the-art-of-soundshaping-in-audacity/"><u>In 2024, Learning the Art of Soundshaping in Audacity</u></a></li>
<li><a href="https://techidaily.com/three-methods-to-recover-lost-data-on-reno-9a-by-fonelab-android-recover-data/"><u>Three methods to recover lost data on Reno 9A</u></a></li>
</ul></div>
