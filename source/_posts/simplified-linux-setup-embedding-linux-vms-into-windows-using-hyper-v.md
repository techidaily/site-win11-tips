---
title: "Simplified Linux Setup: Embedding Linux VMs Into Windows Using Hyper-V"
date: 2024-09-27T22:04:50.554Z
updated: 2024-10-03T16:38:01.865Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Simplified Linux Setup: Embedding Linux VMs Into Windows Using Hyper-V"
excerpt: "This Article Describes Simplified Linux Setup: Embedding Linux VMs Into Windows Using Hyper-V"
keywords: Linux Virtual Integration,Hyper-V Linux Embedding,Simplified Linux VM,Windows with Linux VMs,Hyper-V Linux Setup,Linux on Windows Platform,Streamlined Linux Virtualization
thumbnail: https://thmb.techidaily.com/2862f9e710df6bad4ce9bc4079dc8a66e33ae9d0bd1d0ef6275f60c014f1ce3f.jpg
---

## Simplified Linux Setup: Embedding Linux VMs Into Windows Using Hyper-V

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

## How to Create a Linux Virtual Machine Inside Windows Virtual Machine Using Hyper-V

 We will break the steps into three parts. Firstly, you must enable the virtualization features for the Windows virtual machine. Then you need to enable Hyper-V on this virtual machine. Lastly, you need to create a Linux virtual machine using Hyper-V.

### 1\. Enable Virtualization for Windows Virtual Machine in VMware

To enable Virtualization, do as follows:

1. Launch the VMware app on your system. Click on the Windows virtual machine you want to use.
2. Virtual machine details will pop up on the right side. Click on the**Edit Virtual Machine settings** option.
3. The**Hardware** tab will open by default. Click on the**Processors** option.
4. Locate the V**irtualize engine section** and click on**Virtualize Intel VT-x/EPT or AMD-V/RV** option.  
![Enable Virtualization for Windows Virtual Machine in VMware](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-virtualization-for-windows-virtual-machine-in-vmware.jpg)
5. Click on the**OK** button to apply changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151872/7443" target="_top" id="2151872">
  <img src="//a.impactradius-go.com/display-ad/7443-2151872" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151872/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137218/26400" target="_top" id="2137218">
  <img src="//a.impactradius-go.com/display-ad/26400-2137218" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137218/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Click on the**Generation 1** radio button and click on Next.
5. Keep the**Startup Memory** as**2GB** and enable the**Use Dynamic memory for this virtual machine** option.  
![Create a Linux Virtual Machine Using Hyper-V 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-2.jpg)
6. Then, click on**Next** button and select the**Default switch** option in the Configure Networking section.
7. Click on the**Create a virtual hard disk** option and allocate**20GB** to the virtual hard disk. Move to the next section.  
![Create a Linux Virtual Machine Using Hyper-V 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-3.jpg)
8. Pick the**Install an operating system from a bootable CD/DVD-ROM** option located under the Installation options section. Select the Ubuntu Image file (.iso) you downloaded before beginning this step.  

<!-- affiliate ads begin -->
<span id="1983552">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983552.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983552">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983552.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983552%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983552/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Create a Linux Virtual Machine Using Hyper-V 4](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-4.jpg)
9. Click on the**Next** button and review the virtual machine configuration. Then, click on the**Finish** button to create the virtual machine.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137393/7443" target="_top" id="2137393">
  <img src="//a.impactradius-go.com/display-ad/7443-2137393" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137393/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://smilemakers.pxf.io/c/5597632/2123899/26106" target="_top" id="2123899">
  <img src="//a.impactradius-go.com/display-ad/26106-2123899" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://smilemakers.pxf.io/i/5597632/2123899/26106" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## A Few Things to Remember

 Creating a virtual machine inside a virtual machine is possible. But you have to remember that the underlying configuration of the host system must be such that it can run a virtual machine inside a virtual machine without any issue. If you attempt this experiment on a low-end system with 4GB RAM and a dual-core processor, it will choke the system.

 So, you need to use a system that can devote ample hardware resources to the Windows virtual machine. Only, then you would be able to use Hyper-V and create a Linux virtual machine and allocate run it without any issues. After you try our Ubuntu using Hyper-V, you can power off the virtual machine. Or you can take the extra step and delete the virtual machine from Hyper-V Manager. It will free up a lot of space inside the Windows virtual machine.

 Also, uninstall the Hyper-V feature if you don’t need it any further in your Windows virtual machine. Check out our guide on[how to disable or remove Hyper-V in Windows 11](https://www.makeuseof.com/windows-11-disable-hyper-v/) for more information.

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
<li><a href="https://instagram-video-recordings.techidaily.com/new-privacy-prowess-how-to-disconnect-on-insta/"><u>[New] Privacy Prowess How to Disconnect on Insta</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-heaviest-lifting-uavs-the-definitive-top-10/"><u>[Updated] 2024 Approved Heaviest Lifting UAVs The Definitive Top 10</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-basic-framework-for-crafting-persuasive-social-media-messages-for-2024/"><u>[Updated] Basic Framework for Crafting Persuasive Social Media Messages for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-crafting-powerful-partnerships-a-guide-to-choosing-youtube-allies-for-2024/"><u>[Updated] Crafting Powerful Partnerships A Guide to Choosing YouTube Allies for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-hands-free-tricks-capturing-gotomeetings-on-the-fly-for-2024/"><u>[Updated] Hands-Free Tricks Capturing GoToMeetings on the Fly for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-unlock-the-potential-of-hd-videos-on-android-devices/"><u>2024 Approved Unlock the Potential of HD Videos on Android Devices</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/5-pioneering-portals-to-streamline-your-text-effects-search/"><u>5 Pioneering Portals to Streamline Your Text Effects Search</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-invalid-user-alerts-fix-guide-for-windows-1111/"><u>Disabling Invalid User Alerts: Fix Guide for Windows 11/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-data-recovery-offer-immediate-access-and-assurance/"><u>Exclusive Data Recovery Offer: Immediate Access & Assurance</u></a></li>
<li><a href="https://program-issues.techidaily.com/mastering-troubleshooting-address-the-common-causes-of-valorants-pc-malfunctions/"><u>Mastering Troubleshooting: Address the Common Causes of Valorant's PC Malfunctions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modernizing-the-user-experience-with-windows-1011-shortcuts/"><u>Modernizing the User Experience with Windows 10/11 Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/patching-up-a-purple-problem-desktop-restoration-steps/"><u>Patching Up a Purple Problem: Desktop Restoration Steps</u></a></li>
<li><a href="https://blog-min.techidaily.com/professional-technical-help-at-the-movavi-service-hub/"><u>Professional Technical Help at the Movavi Service Hub</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-tasks-with-mspcm-toolbar-in-windows-11/"><u>Streamlining Tasks with MSPCM Toolbar in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-managing-text-highlighting-in-windows-11/"><u>Tips for Managing Text Highlighting in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mysteries-of-windows-iscsi-initiator-access/"><u>Unraveling the Mysteries of Windows iSCSI Initiator Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/update-windows-11-admin-credentials-quickly/"><u>Update Windows 11 Admin Credentials Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-strategies-for-outlook-malfunctions/"><u>Winning Strategies for Outlook Malfunctions</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/zet-alles-netjes-en-vrijwel-integraal-af-gratuit-vervaardiging-van-online-tod-documenten-met-movavi/"><u>Zet Alles Netjes En Vrijwel Integraal Af: Gratuit Vervaardiging Van Online TOD Documenten Met Movavi</u></a></li>
</ul></div>

