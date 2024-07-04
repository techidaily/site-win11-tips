---
title: "Cross-OS Synergy: Creating a Linux VM Inside Windows Using Hyper-V"
date: 2024-06-25T16:23:01.416Z
updated: 2024-06-26T16:23:01.416Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Cross-OS Synergy: Creating a Linux VM Inside Windows Using Hyper-V"
excerpt: "This Article Describes Cross-OS Synergy: Creating a Linux VM Inside Windows Using Hyper-V"
keywords: Linux Virtual Machine (VM),Hyper-V Integration,Cross-Platform Cloud Setup,OS Migration Techniques,Virtualization Efficiency,Windows Hosting for Linux,Hybrid System Configuration
thumbnail: https://thmb.techidaily.com/5396014f071443efd9e1f13ed6c2f299f41c767371cdaf8ce5e5162404d28c7d.jpg
---

## Cross-OS Synergy: Creating a Linux VM Inside Windows Using Hyper-V

 Virtual Machines enable you to experience multiple operating systems on a single system while keeping them isolated from the host OS. You must have tried creating virtual machines to try out a new OS you don’t want to install directly. But have you ever tried using Hyper-V inside a virtual machine?

 Hyper-V is Windows inbuilt hypervisor that allows you to create virtual machines and run them. But it is also possible to use Hyper-V inside a VMware Windows virtual machine. So, you can create a Hyper-V virtual machine inside a VMware virtual machine and run it without any issues. Here’s how to do it.

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

 Virtualization features are now active for the above Windows virtual machine. Next, you need to install Hyper-V.

### 2\. Install Hyper-V on the Windows Virtual Machine

 To install Hyper-V on the VMware Windows virtual machine, repeat the following steps.

1. Launch the VMware app on your system. Double-click on the Windows virtual machine to boot it up.
2. Once you boot to the desktop, press the**Win + R** key to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
3. Type**appwiz.cpl** and press the enter key.
4. The programs and features window will launch. Click on the**Turn Windows Features on or off** option.
5. Scroll down and click on the**Hyper-V** checkbox in the Windows Features list.  
![Install Hyper-V on the Windows Virtual Machine](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/install-hyper-v-on-the-windows-virtual-machine.jpg)
6. Click on the**OK** button to install the feature on your system.
7. **Restart** your system to apply changes when the installation completes.

 Hyper-V is now active on your Windows virtual machine. Next, you need to create a Linux virtual machine it.

### 3\. Create a Linux Virtual Machine Using Hyper-V

 The last piece of the puzzle is to create a Linux virtual machine inside the Windows virtual machine using Hyper-V. You can pick any Linux distribution that you want. We will go with Ubuntu for this experiment. You have to download the Ubuntu ISO file inside the virtual machine from the [Ubuntu website](https://ubuntu.com/download/desktop) before starting with the steps.

To create an Ubuntu virtual machine, do as follows:

1. Boot up the Windows virtual machine. Press the**Win key** and type Hyper-V manager. Launch the app.
2. Navigate to the right-hand side section and click on**New > Virtual Machine** .  
![Create a Linux Virtual Machine Using Hyper-V 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-1.jpg)
3. Click on the**Next** button. Enter the name of the virtual machine and click on**Next** .
4. Click on the**Generation 1** radio button and click on Next.
5. Keep the**Startup Memory** as**2GB** and enable the**Use Dynamic memory for this virtual machine** option.  
![Create a Linux Virtual Machine Using Hyper-V 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-2.jpg)
6. Then, click on**Next** button and select the**Default switch** option in the Configure Networking section.
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

 Also, uninstall the Hyper-V feature if you don’t need it any further in your Windows virtual machine. Check out our guide on [how to disable or remove Hyper-V in Windows 11](https://www.makeuseof.com/windows-11-disable-hyper-v/) for more information.

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
<li><a href="https://win11-tips.techidaily.com/quick-guide-unlocking-windows-11/"><u>Quick Guide: Unlocking Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-web-pace-unify-phone-and-laptop-connectivity/"><u>Balancing Web Pace: Unify Phone & Laptop Connectivity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pure-potential-upgrade-with-minimalist-win11/"><u>Pure Potential: Upgrade with Minimalist Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fixes-for-windows-defender-shield-unresponsiveness/"><u>Essential Fixes for Windows Defender Shield Unresponsiveness</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-recover-lost-downloads-in-chrome-on-your-windows-pc/"><u>How to Recover Lost Downloads in Chrome, on Your Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-a-persistent-enter-network-credentials-message-on-windows/"><u>How to Fix a Persistent Enter Network Credentials Message on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/low-priced-windows-keys-what-youre-really-paying-for/"><u>Low-Priced Windows Keys: What You're Really Paying For</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-device-names-candd-a-clear-breakdown/"><u>Dissecting Device Names (C&D): A Clear Breakdown</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-list-of-apps-facilitating-the-switch-from-macos-to-windows/"><u>The Ultimate List of Apps Facilitating the Switch From MACOS to WINDOWS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-self-scrolled-windows-with-ease-and-precision/"><u>Fix Self-Scrolled Windows with Ease and Precision</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-android-to-apple-how-to-transfer-photos-from-infinix-smart-8-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Android to Apple How To Transfer Photos From Infinix Smart 8 to iPad Easily | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-survival-kings-ranking-the-best-royales/"><u>[Updated] 2024 Approved  Survival Kings  Ranking the Best Royales</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/breaking-down-why-your-tiktok-freezes/"><u>Breaking Down Why Your TikTok Freezes</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-mastering-economy-in-gaming-top-business-sim-titles/"><u>In 2024, Mastering Economy in Gaming  Top Business Sim Titles</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-pros-and-cons-free2webcam-software-analysis-for-2024/"><u>[Updated] Pros & Cons  Free2WebCam Software Analysis for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-apple-iphone-12-pro-passcode-screen-by-drfone-ios/"><u>How to Unlock Apple iPhone 12 Pro Passcode Screen?</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unlock-full-media-potential-with-funimate-tools/"><u>2024 Approved  Unlock Full Media Potential with Funimate Tools</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/guide-to-delivering-engaging-ppt-in-google-meet-mobiledesktop/"><u>Guide to Delivering Engaging PPT in Google Meet (Mobile/Desktop)</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-can-you-transfer-files-from-lenovo-thinkphone-to-iphone-151413-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How Can You Transfer Files From Lenovo ThinkPhone To iPhone 15/14/13? | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-overcoming-unseen-thumbnails-in-youtube-shorts/"><u>2024 Approved  Overcoming Unseen Thumbnails in YouTube Shorts</u></a></li>
</ul></div>
