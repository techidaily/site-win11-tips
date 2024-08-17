---
title: Harness the Virtual World with Hyper-V in Windows 11
date: 2024-08-16T02:26:34.299Z
updated: 2024-08-17T02:26:34.299Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Harness the Virtual World with Hyper-V in Windows 11
excerpt: This Article Describes Harness the Virtual World with Hyper-V in Windows 11
keywords: Virtual World Hyper-V,Hyper-V Windows 11,Hyper-V Virtualization,Windows 11 Hyper-V,Microsoft Hyper-V Pro,VR Tech with Hyper-V,Enhanced VM in Windows
thumbnail: https://thmb.techidaily.com/dbece127b3474bfee03fecc83648c4194241691bdbde80d7fc24eae5256f2a38.jpg
---

## Harness the Virtual World with Hyper-V in Windows 11

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
## Prerequisites to Enable Hyper-V on Windows 11
![check Windows 11 edition](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/check-Windows-11-edition.png)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Hyper-V is available as an optional feature on Windows 11 Pro, Enterprise, and Education. To check your edition of Windows, go to **Settings > System > About**. Then, check the **Windows specifications** section to find your Windows edition.

 If you have the Home edition, here’s how to [install Hyper-V on Windows 11 Home](https://www.makeuseof.com/install-hyper-v-windows-11-home/). All you have to do is run a bat script to install Hyper-V on non-compatible systems.

 Depending on how many virtual machines and types of applications you intend to run, you may need more resources to run the virtual machines smoothly.

 In addition, you need to enable Hardware Virtualization in BIOS. It is an essential feature to run virtual machines on your Windows system but often disabled by default.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
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
6. Hit **Enter** and then select **Enabled** from the options.
7. Press **F10** to save the changes and exit **BIOS**.
8. Your PC will restart and apply the changes. This may take a while, so wait till your system is fully restarted.

 After restart, you can enable Hyper-V on Windows 11\. Here’s how to do it.

## 1\. Turn On Hyper-V in Windows 11 Via Control Panel
![enable hyper v windows features control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hyper-v-windows-features-control-panel.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
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

## 2\. Add Hyper-V to Windows 11 Using Command Prompt
![enable hyper v command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hyper-v-command-prompt.png)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
## How to Configure Hyper-V Settings
![hyper v manager windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hyper-v-manager-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->

 Once Hyper-V is up and running, you can configure some settings to optimize your virtual machines for optimal performance. Here are a few settings you can configure before creating a virtual machine. You can access these settings from the right pane in Hyper-V Manager.

* **Hyper-V Settings:** You can configure your virtual hard disk and virtual machine location, configure NUMA spanning storage migration, and allow enhanced session mode. On the user side, it lets you configure the virtual machine's keyboard and the mouse release key.
* **Virtual Switch Manager:** It lets you create External, Internal, or Private switches. Virtual switches are bound to the physical network adapter to access the network.
* **Integration services:** You can choose from and enable/disable a host of integration services, including Heartbeat, Key-Value pair exchange, Time synchronization, and Volume shadow copy requestor (VSS) to enhance the performance and functionality of your virtual machine.

![Windows admin center console home](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-admin-center-console-home.jpg)
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-the-artisans-guide-to-instagram-stories-preservation/"><u>[New] In 2024, The Artisan’s Guide to Instagram Stories Preservation</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-datasafe-experts-assessment-for-2024/"><u>[Updated] DataSafe Experts Assessment for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/2-ways-to-transfer-text-messages-from-samsung-galaxy-m34-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>2 Ways to Transfer Text Messages from Samsung Galaxy M34 to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-reasons-to-use-the-new-outlook-app-on-windows/"><u>9 Reasons to Use the New Outlook App on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-event-viewer-breakdowns/"><u>Addressing Windows Event Viewer Breakdowns</u></a></li>
<li><a href="https://win11-tips.techidaily.com/administrative-controls-unveiled-windows-11-and-home-edition/"><u>Administrative Controls Unveiled: Windows 11 & Home Edition</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-frustrating-fails-correcting-windows-error-1152/"><u>Avoiding Frustrating Fails: Correcting Windows' Error 1152</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-teamsters-shutdown-on-windows-11-10-systems/"><u>Avoiding Teamsters Shutdown on Windows 11, 10 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-act-comparing-two-essential-windows-metrics/"><u>Balancing Act: Comparing Two Essential Windows Metrics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-invalid-device-label-in-windows-os/"><u>Correcting 'Invalid Device' Label in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cpu-gen-identification-using-eight-proven-windows-methods/"><u>CPU Gen Identification Using Eight Proven Windows Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-a-global-keyboard-downloading-windows-fonts/"><u>Crafting a Global Keyboard: Downloading Windows Fonts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-method-integrating-airpods-with-windows/"><u>Efficient Method: Integrating AirPods with Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-productivity-easy-drive-mapping-for-windows-11-users/"><u>Enhancing Productivity: Easy Drive Mapping for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-self-scrolled-windows-with-ease-and-precision/"><u>Fix Self-Scrolled Windows with Ease and Precision</u></a></li>
<li><a href="https://program-issues.techidaily.com/fixing-the-crash-and-stutter-issues-of-bloodhunt-on-windows-computers-tips-and-tricks/"><u>Fixing the Crash and Stutter Issues of Bloodhunt on Windows Computers - Tips & Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-reinstate-your-devices-access-post-error-22/"><u>Guide to Reinstate Your Device's Access Post Error 22</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-mend-flickering-screens-in-windows-11/"><u>How to Mend Flickering Screens in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-successfully-unplug-epic-games-from-your-w11-system/"><u>How to Successfully Unplug Epic Games From Your W11 System</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-capturing-itunes-media-three-recording-techniques/"><u>In 2024, Capturing iTunes Media  Three Recording Techniques</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-animators-toolkit-windows-movie-maker-for-winning-projects/"><u>In 2024, The Animator's Toolkit  Windows Movie Maker for Winning Projects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-moves-for-unlocking-the-calculator-in-windows-11/"><u>Key Moves for Unlocking the Calculator in Windows 11</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/methods-to-transfer-from-apple-iphone-se-2022-to-android-drfone-by-drfone-transfer-from-ios/"><u>Methods to Transfer from Apple iPhone SE (2022) to Android | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-effortless-transition-in-windows-terminals-attention-mode/"><u>Quick Fix: Effortless Transition in Windows Terminal’s Attention Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quiet-quandaries-winning-back-volume-from-vexed-keyboard/"><u>Quiet Quandaries: Winning Back Volume From Vexed Keyboard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-steps-to-navigate-windows-system-restore-functions/"><u>Simplified Steps to Navigate Windows' System Restore Functions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-bypass-windows-admin-installation-restriction-error/"><u>Steps to Bypass Windows 'Admin Installation Restriction' Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-your-steam-network-via-dns-cleanup/"><u>Streamlining Your Steam Network via DNS Cleanup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-with-windows-11-safe-boot-tips/"><u>Troubleshoot With Windows 11 Safe Boot Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-deactivated-rulesets-in-outlookwindows/"><u>Troubleshooting Deactivated Rulesets in Outlook/Windows</u></a></li>
<li><a href="https://win-able.techidaily.com/ultimate-troubleshooting-tips-for-improving-halo-infinite-sound-quality/"><u>Ultimate Troubleshooting Tips for Improving Halo Infinite Sound Quality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-potential-of-folder-multiplication-on-windows-devices/"><u>Unlocking the Potential of Folder Multiplication on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-11-bluescreen-mastery-through-11-fixes/"><u>Unraveling Windows 11 Bluescreen: Mastery Through 11 Fixes</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-google-play-services-keeps-stopping-on-vivo-g2-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What to Do if Google Play Services Keeps Stopping on Vivo G2 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win10win11-troubleshooting-hardware-recognition-issues/"><u>Win10/Win11: Troubleshooting Hardware Recognition Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-and-artificial-intelligence-generating-vibrant-ai-graphics-paint-cocreator/"><u>Windows 11 & Artificial Intelligence: Generating Vibrant AI Graphics (Paint Cocreator)</u></a></li>
</ul></div>
