---
title: Seamless Hosting of Linux VMs via Hyper-V Windows Platform
date: 2024-10-29T16:55:17.457Z
updated: 2024-11-01T19:46:57.919Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Seamless Hosting of Linux VMs via Hyper-V Windows Platform
excerpt: This Article Describes Seamless Hosting of Linux VMs via Hyper-V Windows Platform
keywords: Seamless Linux VM Hosting,Hyper-V Virtualization,Linux VM Integration,Hyper-V for Linux VMs,Cross-Platform Hosting,Windows VM Management,Linux VM on Windows Platform
thumbnail: https://thmb.techidaily.com/829f3e424c1b3b1991d559a20a197c8257f098aee3dfffc59a2e2d3ad659a88e.jpg
---

## Seamless Hosting of Linux VMs via Hyper-V Windows Platform

 Virtual Machines enable you to experience multiple operating systems on a single system while keeping them isolated from the host OS. You must have tried creating virtual machines to try out a new OS you don’t want to install directly. But have you ever tried using Hyper-V inside a virtual machine?

 Hyper-V is Windows inbuilt hypervisor that allows you to create virtual machines and run them. But it is also possible to use Hyper-V inside a VMware Windows virtual machine. So, you can create a Hyper-V virtual machine inside a VMware virtual machine and run it without any issues. Here’s how to do it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## The Prerequisites for Running a Linux Virtual Machine Inside Hyper-V

 Firstly, you will need a Windows virtual machine that is completely functional inside VMware. We would suggest Windows 10 or 11 virtual machines for this project. Moreover, you must pick either Windows Pro or Enterprise edition because Hyper-V isn’t available for Windows Home edition.

 Make sure to dedicate an adequate amount of hardware resources to the virtual machine. The reason behind this is that you will try to run a virtual machine inside a virtual machine. So, the Windows virtual machine can dedicate only a portion of its resources to running a Linux virtual machine using Hyper-V. We tested this using a Windows 11 system with 16GB of RAM and an eight-core AMD processor.

 Also, update the VMware Workstation Player to the latest version before you begin the installation method.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/999558/11832" target="_top" id="999558">
  <img src="//a.impactradius-go.com/display-ad/11832-999558" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/999558/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Create a Linux Virtual Machine Inside Windows Virtual Machine Using Hyper-V

 We will break the steps into three parts. Firstly, you must enable the virtualization features for the Windows virtual machine. Then you need to enable Hyper-V on this virtual machine. Lastly, you need to create a Linux virtual machine using Hyper-V.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123748/7443" target="_top" id="2123748">
  <img src="//a.impactradius-go.com/display-ad/7443-2123748" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123748/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 1\. Enable Virtualization for Windows Virtual Machine in VMware

To enable Virtualization, do as follows:

1. Launch the VMware app on your system. Click on the Windows virtual machine you want to use.
2. Virtual machine details will pop up on the right side. Click on the**Edit Virtual Machine settings** option.
3. The**Hardware** tab will open by default. Click on the**Processors** option.
4. Locate the V**irtualize engine section** and click on**Virtualize Intel VT-x/EPT or AMD-V/RV** option.  
![Enable Virtualization for Windows Virtual Machine in VMware](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-virtualization-for-windows-virtual-machine-in-vmware.jpg)
5. Click on the**OK** button to apply changes.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139118/17108" target="_top" id="2139118">
  <img src="//a.impactradius-go.com/display-ad/17108-2139118" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139118/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Virtualization features are now active for the above Windows virtual machine. Next, you need to install Hyper-V.

### 2\. Install Hyper-V on the Windows Virtual Machine

 To install Hyper-V on the VMware Windows virtual machine, repeat the following steps.

1. Launch the VMware app on your system. Double-click on the Windows virtual machine to boot it up.
2. Once you boot to the desktop, press the**Win + R** key to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
3. Type**appwiz.cpl** and press the enter key.
4. The programs and features window will launch. Click on the**Turn Windows Features on or off** option.
5. Scroll down and click on the**Hyper-V** checkbox in the Windows Features list.  
![Install Hyper-V on the Windows Virtual Machine](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/install-hyper-v-on-the-windows-virtual-machine.jpg)
6. Click on the**OK** button to install the feature on your system.
7. **Restart** your system to apply changes when the installation completes.

 Hyper-V is now active on your Windows virtual machine. Next, you need to create a Linux virtual machine it.

### 3\. Create a Linux Virtual Machine Using Hyper-V

 The last piece of the puzzle is to create a Linux virtual machine inside the Windows virtual machine using Hyper-V. You can pick any Linux distribution that you want. We will go with Ubuntu for this experiment. You have to download the Ubuntu ISO file inside the virtual machine from the[Ubuntu website](https://ubuntu.com/download/desktop) before starting with the steps.

To create an Ubuntu virtual machine, do as follows:

1. Boot up the Windows virtual machine. Press the**Win key** and type Hyper-V manager. Launch the app.
2. Navigate to the right-hand side section and click on**New > Virtual Machine** .  
![Create a Linux Virtual Machine Using Hyper-V 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-1.jpg)
3. Click on the**Next** button. Enter the name of the virtual machine and click on**Next** .
4. Click on the**Generation 1** radio button and click on Next.
5. Keep the**Startup Memory** as**2GB** and enable the**Use Dynamic memory for this virtual machine** option.  
![Create a Linux Virtual Machine Using Hyper-V 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-2.jpg)
6. Then, click on**Next** button and select the**Default switch** option in the Configure Networking section.

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1815678/21290" target="_top" id="1815678">
  <img src="//a.impactradius-go.com/display-ad/21290-1815678" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://versadesk.pxf.io/i/5597632/1815678/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Click on the**Create a virtual hard disk** option and allocate**20GB** to the virtual hard disk. Move to the next section.  
![Create a Linux Virtual Machine Using Hyper-V 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-3.jpg)
8. Pick the**Install an operating system from a bootable CD/DVD-ROM** option located under the Installation options section. Select the Ubuntu Image file (.iso) you downloaded before beginning this step.  

![Create a Linux Virtual Machine Using Hyper-V 4](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-4.jpg)
9. Click on the**Next** button and review the virtual machine configuration. Then, click on the**Finish** button to create the virtual machine.

 Now that the virtual machine is ready, it's time to get Ubuntu up and running:

1. Select the newly created virtual machine in the list and click on the**Start** option to launch the virtual machine.
2. Ubuntu setup will launch. Select the**Install Ubuntu** option and proceed with the installation.
3. Click on**Minimal Installation** and uncheck the**Download updates while installing Ubuntu** option.
4. Then, pick the**Erase disk and install Ubuntu** option and click on the**Install Now** button.
5. Select your geographical location and enter your username and password. Then, click on the**Continue** button.
6. Wait for the installation to complete. It may take longer if you have a SATA HDD installed on your system.
7. The installer will prompt you to restart the system. Click on the**Restart Now** button.  
![Ubuntu Virtual Machine Running Using Hyper-V](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/ubuntu-virtual-machine-running-using-hyper-v.jpg)

 The virtual machine will boot to the Ubuntu desktop. You can use Ubuntu and notice that the system runs fine inside Hyper-V just like it does on any other virtualization software.

## A Few Things to Remember

 Creating a virtual machine inside a virtual machine is possible. But you have to remember that the underlying configuration of the host system must be such that it can run a virtual machine inside a virtual machine without any issue. If you attempt this experiment on a low-end system with 4GB RAM and a dual-core processor, it will choke the system.

 So, you need to use a system that can devote ample hardware resources to the Windows virtual machine. Only, then you would be able to use Hyper-V and create a Linux virtual machine and allocate run it without any issues. After you try our Ubuntu using Hyper-V, you can power off the virtual machine. Or you can take the extra step and delete the virtual machine from Hyper-V Manager. It will free up a lot of space inside the Windows virtual machine.

 Also, uninstall the Hyper-V feature if you don’t need it any further in your Windows virtual machine. Check out our guide on[how to disable or remove Hyper-V in Windows 11](https://www.makeuseof.com/windows-11-disable-hyper-v/) for more information.

<!-- affiliate ads begin -->
<span id="1983473">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983473.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983473">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983473.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983473%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983473/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Use Virtual Machine Inside a Virtual Machine With Hyper-V

 VMware supports hardware virtualization and can extend the feature to its virtual machines. VirtualBox is yet to catch up in this aspect because Hyper-V doesn’t work in a VirtualBox virtual machine as of writing this post. Make sure that you turn off virtualization features for the Windows virtual machine when you no longer need it.

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
<li><a href="https://extra-guidance.techidaily.com/new-prime-5-toy-drones-reviewed/"><u>[New] Prime 5 Toy Drones Reviewed</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-ace-the-game-crafting-a-pro-gaming-channels-success-story/"><u>[Updated] 2024 Approved Ace the Game Crafting a Pro Gaming Channels Success Story</u></a></li>
<li><a href="https://win-popular.techidaily.com/44cm5ywo6z2i6kej5rg65pa55rov77ya5b6p5y6f56gs56kf5lik55qe5pya5paw5pcn5asx6loh5paz44cn/"><u>「全面解決方法：復原硬碟上的最新損失資料」</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-passport-photo-creation-made-easy-10-images-at-no-cost/"><u>2024 Approved Passport Photo Creation Made Easy 10 Images at No Cost</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ing-the-right-video-sharing-platform-tiktok-vs-youtubes-shorts-for-2024/"><u>Choosing the Right Video Sharing Platform TikTok vs YouTubes' Shorts for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halting-secondary-apps-camera-usage-code-0xa00f4243/"><u>Halting Secondary App's Camera Usage: Code 0xA00F4243</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/highest-quality-capture-options-for-2024/"><u>Highest Quality Capture Options for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-20plus-creative-photo-collage-ideas-to-light-up-your-life/"><u>In 2024, 20+ Creative Photo Collage Ideas to Light Up Your Life</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-ultimate-guide-to-catch-the-regional-located-pokemon-for-vivo-v30-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Ultimate Guide to Catch the Regional-Located Pokemon For Vivo V30 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/investigating-windows-11s-core-data-the-hidden-registry/"><u>Investigating Windows 11'S Core Data: The Hidden Registry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedies-for-dead-input-devices-in-windows-os/"><u>Remedies for Dead Input Devices in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-alter-your-windows-cursor-on-pc/"><u>Steps to Alter Your Window's Cursor on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-upgrade-new-features-in-microsoft-paint/"><u>The Ultimate Upgrade: New Features in Microsoft Paint</u></a></li>
</ul></div>

