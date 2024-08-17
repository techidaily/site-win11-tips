---
title: Jumpstart Your PC with Hyper-V on Windows 11
date: 2024-08-16T01:52:58.096Z
updated: 2024-08-17T01:52:58.096Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Jumpstart Your PC with Hyper-V on Windows 11
excerpt: This Article Describes Jumpstart Your PC with Hyper-V on Windows 11
keywords: Hyper-V Windows 11,Jumpstart PC Hyper-V,Windows 11 VM Optimize,PC Enhancement with Hyper-V,Virtualization in Windows 11,Boost PC Performance (Hyper-V),Installing Hyper-V on Win11
thumbnail: https://thmb.techidaily.com/b2faccf55ba2f62eeda01fb2856eae6cf952310d841c8d8317d40b9a309e6901.jpg
---

## Jumpstart Your PC with Hyper-V on Windows 11

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
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Hyper-V is available as an optional feature on Windows 11 Pro, Enterprise, and Education. To check your edition of Windows, go to **Settings > System > About**. Then, check the **Windows specifications** section to find your Windows edition.

 If you have the Home edition, here’s how to [install Hyper-V on Windows 11 Home](https://www.makeuseof.com/install-hyper-v-windows-11-home/). All you have to do is run a bat script to install Hyper-V on non-compatible systems.

 Depending on how many virtual machines and types of applications you intend to run, you may need more resources to run the virtual machines smoothly.

 In addition, you need to enable Hardware Virtualization in BIOS. It is an essential feature to run virtual machines on your Windows system but often disabled by default.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
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
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Add Hyper-V to Windows 11 Using Command Prompt
![enable hyper v command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hyper-v-command-prompt.png)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->

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
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Configure Hyper-V Settings
![hyper v manager windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hyper-v-manager-windows-11.jpg)

 Once Hyper-V is up and running, you can configure some settings to optimize your virtual machines for optimal performance. Here are a few settings you can configure before creating a virtual machine. You can access these settings from the right pane in Hyper-V Manager.

* **Hyper-V Settings:** You can configure your virtual hard disk and virtual machine location, configure NUMA spanning storage migration, and allow enhanced session mode. On the user side, it lets you configure the virtual machine's keyboard and the mouse release key.
* **Virtual Switch Manager:** It lets you create External, Internal, or Private switches. Virtual switches are bound to the physical network adapter to access the network.
* **Integration services:** You can choose from and enable/disable a host of integration services, including Heartbeat, Key-Value pair exchange, Time synchronization, and Volume shadow copy requestor (VSS) to enhance the performance and functionality of your virtual machine.

![Windows admin center console home](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-admin-center-console-home.jpg)

 While the MMC-based Hyper-V manager is functional and built into the OS, consider using the relatively new Windows Admin Center. It is a browser-based management app that lets you manage your servers, virtual machines, local users and groups, and more.

 Download [Windows Admin Center](https://www.microsoft.com/en-in/windows-server/windows-admin-center) from the official Microsoft page and run the installer to give it a go. Once installed, open the app, and it will launch in your default browser, giving you access to a host of management tools.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-disruptive-beats-curated-list-of-music-mutators/"><u>[New] 2024 Approved  Disruptive Beats  Curated List of Music Mutators</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-capturing-quality-logitech-webcam-recording-guide-for-2024/"><u>[New] Capturing Quality  Logitech Webcam Recording Guide for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-control-youtube-audio-mobiledesktop-approach/"><u>[New] In 2024, Control YouTube Audio  Mobile/Desktop Approach</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-pioneering-methods-to-log-lol-gaming-sessions/"><u>[New] Pioneering Methods to Log LOL Gaming Sessions</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-preventing-frame-gaps-in-obs-recordings-for-2024/"><u>[New] Preventing Frame Gaps in OBS Recordings for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-secrets-to-high-quality-roblox-game-footage-on-macos/"><u>[Updated] In 2024, Secrets to High-Quality Roblox Game Footage on macOS</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-thunder-gods-fury-new-age-begins/"><u>[Updated] Thunder God's Fury  New Age Begins</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-guidelines-to-help-you-change-windows-11-wallpaper/"><u>2024 Approved  Guidelines to Help You Change Windows 11 Wallpaper</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/5-quick-methods-to-bypass-infinix-smart-8-frp-by-drfone-android/"><u>5 Quick Methods to Bypass Infinix Smart 8 FRP</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-htc-u23-pro-drfone-by-drfone-virtual-android/"><u>9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On HTC U23 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-your-onedrive-save-point-on-windows-10/"><u>Altering Your OneDrive Save Point on Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-auto-time-zone-switches-in-microsofts-operating-system/"><u>Bypassing Auto Time Zone Switches in Microsoft's Operating System</u></a></li>
<li><a href="https://fox-access.techidaily.com/cant-access-video-feature-on-sony-a6400-camera/"><u>Can't Access Video Feature on Sony A6400 Camera</u></a></li>
<li><a href="https://extra-information.techidaily.com/comparing-gopro-and-yi-4k-cams-new-insights-on-high-speed-cameras/"><u>Comparing GoPro and Yi 4K Cams  New Insights on High-Speed Cameras</u></a></li>
<li><a href="https://extra-tips.techidaily.com/crafting-visual-wonders-in-lightrooms-hdr-workflow-for-2024/"><u>Crafting Visual Wonders in Lightroom's HDR Workflow for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crucial-aspects-of-revamping-your-windows-setup/"><u>Crucial Aspects of Revamping Your Windows Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-microsofts-phone-link-application-functionality/"><u>Decoding Microsoft's Phone Link Application Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/double-clicking-away-how-to-instantly-load-apk-files-on-windows-11/"><u>Double-Clicking Away: How to Instantly Load APK Files on Windows 11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/eliminate-screen-hiccup-in-win11/"><u>Eliminate Screen Hiccup in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-to-java-development-kit-setup-in-windows-11/"><u>Essential Steps to Java Development Kit Setup in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-to-unlocking-stuck-battlenet-login/"><u>Expert Guide to Unlocking Stuck Battle.net Login</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-resetting-windows-11-applications/"><u>Guide to Resetting Windows 11 Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-find-windows-background-save-spot-in-11/"><u>How to Find Window's Background Save Spot in 11</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-nubia-z50-ultra-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Nubia Z50 Ultra without Losing Data | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-tackle-closed-folder-issues-in-winxpxo11-on-double-click/"><u>How to Tackle Closed Folder Issues in WinXP/XO11 on Double-Click</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-13-pro-max-to-other-iphone-13-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 13 Pro Max To Other iPhone 13 devices? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-update-or-downgrade-iphone-15-plus-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade iPhone 15 Plus Without iTunes? | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-exciting-quests-selecting-the-top-10-adventure-gaming-treasures/"><u>In 2024, Exciting Quests  Selecting the Top 10 Adventure Gaming Treasures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-administrator-access-via-cmd/"><u>Instant Administrator Access via CMD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-windows-11s-storyteller-a-step-by-step-guide/"><u>Launching Windows 11'S Storyteller: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-techniques-to-accelerate-steam-downloads-on-windows/"><u>Master Techniques to Accelerate Steam Downloads on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-software-deletion-in-windows-11-115-chars/"><u>Mastering Software Deletion in Windows 11 (115 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modifying-password-policy-update-lockout-value-post-incorrect-attempts/"><u>Modifying Password Policy: Update Lockout Value Post Incorrect Attempts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pro-wls-techniques-unlocking-the-full-power-of-wsl-2-in-win-oses/"><u>Pro WLS Techniques: Unlocking the Full Power of WSL 2 in Win OSes</u></a></li>
<li><a href="https://driver-install.techidaily.com/quick-logitech-usb-mini-headset-driver-fixes/"><u>Quick Logitech USB Mini-Headset Driver Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reestablishing-access-rectifying-unreachable-ea-services/"><u>Reestablishing Access: Rectifying Unreachable EA Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-writing-rights-denied-on-windows-devices/"><u>Remedying Writing Rights Denied on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-pcs-dns-cache-efficiently/"><u>Revamp Your PC's DNS Cache Efficiently</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/securing-your-gameplay-on-windows-10-the-5-essentials/"><u>Securing Your Gameplay on Windows 10  The 5 Essentials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shifting-paradigms-of-administrative-control-in-windows-environments/"><u>Shifting Paradigms of Administrative Control in Windows Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-guide-to-buy-and-install-adobe-reader-via-ms-store/"><u>Simplified Guide to Buy and Install Adobe Reader via MS Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-discontinue-repeated-edge-icons/"><u>Solutions to Discontinue Repeated Edge Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-overcoming-windows-no-internet-issue/"><u>Steps for Overcoming Windows No Internet Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-workflow-integrating-wordpad-shortcuts-into-context-menus-on-windows-11/"><u>Streamlining Workflow: Integrating WordPad Shortcuts Into Context Menus on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-ed-themed-windows-experience/"><u>Tailoring Ed-Themed Windows Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essentials-of-installing-works-in-the-latest-os/"><u>The Essentials of Installing Works in the Latest OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-desktop-tips-for-a-win11-masterpiece/"><u>Transform Your Desktop: Tips for a Win11 Masterpiece</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tweak-viewer-direction-on-windows-monitor/"><u>Tweak Viewer Direction on Windows Monitor</u></a></li>
</ul></div>
