---
title: Quickly Enable Hyper-V in the Latest Windows 11
date: 2024-08-16T02:48:01.187Z
updated: 2024-08-17T02:48:01.187Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quickly Enable Hyper-V in the Latest Windows 11
excerpt: This Article Describes Quickly Enable Hyper-V in the Latest Windows 11
keywords: Enable Hyper-V Win11,Windows 11 Hyper-V Setup,Quick Hyper-V Install,Activate Hyper-V in Win11,Hyper-V Setup Guide Win11,Turn on Hyper-V Windows 11,Enable Hyper-V Latest Win11
thumbnail: https://thmb.techidaily.com/d8e6435243e7bdae68e29ae66158699a00161b12482bc1fecd3d439c888dea97.png
---

## Quickly Enable Hyper-V in the Latest Windows 11

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
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
5. Next, use the down arrow key to highlight the **Virtualization Technology** option.  
![enable hardware virtualization bios hp laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hardware-virtualization-bios-hp-laptoop.jpg)
6. Hit **Enter** and then select **Enabled** from the options.
7. Press **F10** to save the changes and exit **BIOS**.
8. Your PC will restart and apply the changes. This may take a while, so wait till your system is fully restarted.

 After restart, you can enable Hyper-V on Windows 11\. Here’s how to do it.

## 1\. Turn On Hyper-V in Windows 11 Via Control Panel

![enable hyper v windows features control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hyper-v-windows-features-control-panel.png)
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Command Prompt offers a fast and efficient way to perform repetitive tasks. You can use the DISM (Deployment Image Servicing and Management) command-line tool to access and install optional Windows features via Command Prompt.

 Follow these steps to enable Hyper-V on Windows 11 using Command Prompt:

1. Press the **Win** key, and type **cmd**. Then, right-click on **Command Prompt** and select **Run as Administrator.**
2. In the Command Prompt window, type the following command and hit Enter to execute:  
`DISM /Online /Enable-Feature /All /FeatureName:Microsoft-Hyper-V`
3. The Deployment Image Servicing and Management tool will start enabling the Hyper-V feature and show the progress on the Command Prompt.
4. Once the operation is completed successfully, you will need to restart your PC. So, press **Y** on your keyboard to confirm the action.

 After your PC restarts, you can open and [use the Hyper-V Manager to create virtual machines](https://www.makeuseof.com/tag/create-virtual-machine-using-windows-10-hyper-v/).

<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
## 3\. Enable Hyper-V Using PowerShell

![enable hyper v windows 11 powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hyper-v-windows-11-powershell.png)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
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
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
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
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
## How to Configure Hyper-V Settings

![hyper v manager windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hyper-v-manager-windows-11.jpg)

 Once Hyper-V is up and running, you can configure some settings to optimize your virtual machines for optimal performance. Here are a few settings you can configure before creating a virtual machine. You can access these settings from the right pane in Hyper-V Manager.

* **Hyper-V Settings:** You can configure your virtual hard disk and virtual machine location, configure NUMA spanning storage migration, and allow enhanced session mode. On the user side, it lets you configure the virtual machine's keyboard and the mouse release key.
* **Virtual Switch Manager:** It lets you create External, Internal, or Private switches. Virtual switches are bound to the physical network adapter to access the network.
* **Integration services:** You can choose from and enable/disable a host of integration services, including Heartbeat, Key-Value pair exchange, Time synchronization, and Volume shadow copy requestor (VSS) to enhance the performance and functionality of your virtual machine.

![Windows admin center console home](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-admin-center-console-home.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 While the MMC-based Hyper-V manager is functional and built into the OS, consider using the relatively new Windows Admin Center. It is a browser-based management app that lets you manage your servers, virtual machines, local users and groups, and more.

 Download [Windows Admin Center](https://www.microsoft.com/en-in/windows-server/windows-admin-center) from the official Microsoft page and run the installer to give it a go. Once installed, open the app, and it will launch in your default browser, giving you access to a host of management tools.

## Many Ways to Enable Hyper-V in Windows 11

 Hyper-V is a type 1 hypervisor, which means it runs directly on a computer’s hardware. It comes pre-installed, free to use without restriction, and offers linear performance on a consumer-grade system.

 That said, dedicated virtual machines such as the VMWare WorkStation Pro is available on multiple platforms, can be used on older systems, and is more suitable for enterprise solutions. Check out our comparison comparing the three popular hypervisors to find the one that works for you.

 In this article, we show you the how to enable Hyper-V in Windows 11 and create virtual machines without third-party tools.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-detailed-instructions-maximizing-mobizen-record-functionality/"><u>[New] 2024 Approved  Detailed Instructions  Maximizing Mobizen Record Functionality</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-the-most-affordable-gaming-tunes-top-10-lists/"><u>[New] 2024 Approved  The Most Affordable Gaming Tunes  Top 10 Lists</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-key-screenshot-utilities-1-8/"><u>[New] In 2024, Key Screenshot Utilities #1-8</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/n-2024-unveiling-the-art-of-personal-branding-mastery/"><u>[New] In 2024, Unveiling the Art of Personal Branding Mastery</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-recognizing-invisible-social-presence-for-2024/"><u>[New] Recognizing Invisible Social Presence for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unravel-media-complexity-transforming-xmlttml-into-srt-gold/"><u>[New] Unravel Media Complexity  Transforming XML/TTML Into SRT Gold</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-secrets-of-screen-grabs-exposed/"><u>[Updated] In 2024, Secrets of Screen Grabs Exposed</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-step-by-step-webcam-recording-on-macbook-for-2024/"><u>[Updated] Step-by-Step Webcam Recording on MacBook for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-unexplored-instagram-tricks-for-enhanced-engagement-for-2024/"><u>[Updated] Unexplored Instagram Tricks for Enhanced Engagement for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-calculating-the-storage-space-of-24-hour-videos/"><u>2024 Approved  Calculating the Storage Space of 24-Hour Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-methods-for-removing-a-disks-partition-in-windows/"><u>3 Methods for Removing a Disk's Partition in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-superior-features-added-to-windows-11-feb-update/"><u>9 Superior Features Added to Windows 11, Feb Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-ways-to-fix-the-no-servers-found-error-in-apex-legends-for-windows/"><u>9 Ways to Fix the No Servers Found Error in Apex Legends for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-approach-to-probing-program-hideouts-in-windows/"><u>A Practical Approach to Probing Program Hideouts in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerated-assistance-top-tips-for-fixed-gameplay-on-pcs/"><u>Accelerated Assistance: Top Tips for Fixed Gameplay on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-d-drive-folder-in-windows-explorer/"><u>Accessing D: Drive Folder in Windows Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-folder-and-file-unity-a-windows-exploration/"><u>Achieving Folder & File Unity: A Windows Exploration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-blank-screens-on-system-ignition/"><u>Addressing Blank Screens on System Ignition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-faulty-volume-adjustment-sliders/"><u>Addressing Faulty Volume Adjustment Sliders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-frozen-windows-guard-in-windows-11/"><u>Addressing Frozen Windows Guard in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/aging-gracefully-upgrading-your-familys-old-computer/"><u>Aging Gracefully: Upgrading Your Family’s Old Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-insider-look-at-microsofts-revolutionary-copilot-tool/"><u>An Insider Look at Microsoft's Revolutionary Copilot Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/anecdotal-insights-into-seamless-windows-11-setup/"><u>Anecdotal Insights Into Seamless Windows 11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/approaches-to-address-roblox-glitches/"><u>Approaches to Address Roblox Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/audio-visual-capture-mastery-snipping-tools-latest-recording-features-explained-max-156/"><u>Audio-Visual Capture Mastery: Snipping Tool's Latest Recording Features Explained (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automate-the-journey-always-command-prompt-admin-style/"><u>Automate the Journey: Always Command Prompt, Admin Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-frustration-easily-setup-icloud-on-windows-pc/"><u>Avoid Frustration: Easily Setup iCloud on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/black-friday-bonanza-get-your-deal-612-for-eternal-windows-10/"><u>Black Friday Bonanza: Get Your Deal - $6.12 for Eternal Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-disk-space-how-to-use-windows-autodeleting-feature/"><u>Boost Disk Space: How to Use Windows' AutoDeleting Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-steam-downloads-combatting-speedy-slowdowns/"><u>Boosting Steam Downloads: Combatting Speedy Slowdowns</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-task-manager-admin-mode-on-windows-11/"><u>Boosting Task Manager: Admin Mode on Windows 11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/capture-your-brilliance-in-insta-cinematic-footage/"><u>Capture Your Brilliance in Insta Cinematic Footage</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-honor-magic5-ultimate-drfone-by-drfone-virtual-android/"><u>Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Honor Magic5 Ultimate | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-your-iphone-14-pro-passcode-4-easy-methods-with-or-without-itunes-by-drfone-ios/"><u>In 2024, How to Unlock Your iPhone 14 Pro Passcode 4 Easy Methods (With or Without iTunes)</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-identifying-relevant-metaphors-and-analogies/"><u>In 2024, Identifying Relevant Metaphors and Analogies</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-ultimate-screen-recorder-features-for-pcmac/"><u>In 2024, Ultimate Screen Recorder Features for PC/Mac</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-unlocking-top-five-transformative-facebook-traits/"><u>In 2024, Unlocking Top Five Transformative Facebook Traits</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/premium-console-emulation-choosing-the-top-5-for-windows-for-2024/"><u>Premium Console Emulation  Choosing the Top 5 for Windows for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719205412582-shed-light-on-dark-windows-11-desktops-tips-inside/"><u>Shed Light on Dark Windows 11 Desktops - Tips Inside</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/swift-practices-efficient-recording-of-online-meetings-for-2024/"><u>Swift Practices  Efficient Recording of Online Meetings for 2024</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/unveiling-the-rivals-how-iphone-15-pro-stacks-up-to-pro-max/"><u>Unveiling the Rivals: How iPhone 15 Pro Stacks Up to Pro Max</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>