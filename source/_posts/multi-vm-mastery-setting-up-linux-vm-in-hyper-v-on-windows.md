---
title: "Multi-VM Mastery: Setting Up Linux VM in Hyper-V on Windows"
date: 2024-07-12T17:27:45.434Z
updated: 2024-07-13T17:27:45.434Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Multi-VM Mastery: Setting Up Linux VM in Hyper-V on Windows"
excerpt: "This Article Describes Multi-VM Mastery: Setting Up Linux VM in Hyper-V on Windows"
keywords: Linux VM Setup,Hyper-V Mastery,Linux Hyper-V,VM Configuration,Linux VM Guide,Hyper-VM Setup,Linux on Windows
thumbnail: https://thmb.techidaily.com/3a6dbb861d55872fdf4ced41ee2862ae3932a3822bc0678be6a1186e4efd451b.jpg
---

## Multi-VM Mastery: Setting Up Linux VM in Hyper-V on Windows

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
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-unlocking-virtual-reality-the-best-video-conversion-tools/"><u>In 2024, Unlocking Virtual Reality The Best Video Conversion Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-incompatibility-between-windows-and-fingerprint-device/"><u>Addressing Incompatibility Between Windows and Fingerprint Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-restoring-the-non-responsive-service-control-panel/"><u>A Comprehensive Guide: Restoring the Non-Responsive Service Control Panel</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-trendsetters-tunes-hits-of-the-week-for-yt-shorts-soundtracks/"><u>2024 Approved  Trendsetters’ Tunes  Hits of the Week for YT Shorts Soundtracks</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/enhancing-window-interface-on-expanded-windows-10-monitors/"><u>Enhancing Window Interface on Expanded Windows 10 Monitors</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-2024-approved-15-best-sites-to-watch-cartoons-online-free-and-so-can-you/"><u>Updated 2024 Approved 15 Best Sites to Watch Cartoons Online Free And So Can You</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-elevation-failure-overcoming-error-740-in-windows/"><u>Addressing Elevation Failure: Overcoming Error 740 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-essential-steps-for-dealing-with-windows-http-error-0x80860010/"><u>7 Essential Steps for Dealing with Windows' HTTP Error 0X80860010</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-error-code-a00f4289-for-windows-11-webcam/"><u>Addressing Error Code A00F4289 for Windows 11 Webcam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-fixing-windows-error-xffffff/"><u>A Comprehensive Guide to Fixing Windows' Error XFFFFFF</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-pc-screen-to-nokia-c300-phones-drfone-by-drfone-android/"><u>In 2024, How to Mirror PC Screen to Nokia C300 Phones? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-end-task-bar-functionality-in-windows-11/"><u>Activating End Task Bar Functionality in Windows 11</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-catchemall-celebrate-national-pokemon-day-with-virtual-location-on-realme-v30t-drfone-by-drfone-virtual-android/"><u>In 2024, CatchEmAll Celebrate National Pokémon Day with Virtual Location On Realme V30T | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719355984111-troubleshooting-made-simple-your-guide-to-windows-help/"><u>Troubleshooting Made Simple: Your Guide to Windows Help</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-beginners-path-to-implementing-hyper-v-on-win-11-homes/"><u>A Beginner's Path to Implementing Hyper-V on Win 11 Homes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-excellence-perfecting-your-consoles-gamepad-functionality/"><u>Achieving Excellence: Perfecting Your Console's Gamepad Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-dangers-of-purchasing-low-cost-windows-licenses/"><u>6 Dangers of Purchasing Low-Cost Windows Licenses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719370971554-xbox-not-responding-unfreeze-and-get-back-in/"><u>Xbox Not Responding? Unfreeze and Get Back In!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719341599288-windows-chatbot-simulation-localize-for-free-with-gpt4all/"><u>Windows ChatBot Simulation: Localize for Free with GPT4All</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-interconnecting-platforms-sharing-tiktok-to-facebook/"><u>[Updated] Interconnecting Platforms  Sharing TikTok to Facebook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-gmail-to-windows-outlook-seamless-integration-method/"><u>Adding Gmail to Windows Outlook: Seamless Integration Method</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-network-unity-wi-fi-plus-ethernet-integration-in-windows/"><u>Achieving Network Unity: Wi-Fi + Ethernet Integration in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-deactivated-outlook-mail-signals/"><u>Addressing Deactivated Outlook Mail Signals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-strategies-reviving-failed-google-drive-windows-links/"><u>7 Strategies: Reviving Failed Google Drive Windows Links</u></a></li>
<li><a href="https://extra-resources.techidaily.com/assessing-the-video-capacity-of-64gb-drives/"><u>Assessing the Video Capacity of 64Gb Drives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719278811623-bypassing-chrome-block-strategies-for-w11-users/"><u>Bypassing Chrome Block: Strategies for W11 Users.</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/essential-tips-for-computer-users-to-start-tiktok-live/"><u>Essential Tips for Computer Users to Start TikTok LIVE</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-pro-rated-list-the-best-5-hd-webcams-with-capture-microphones/"><u>[New] Pro-Rated List  The Best 5 HD Webcams with Capture Microphones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719371223006-master-the-digital-age-essential-keys-fan-deal-at-lowest-price-on-windows-11-612lifetime/"><u>Master the Digital Age - Essential Keys Fan Deal at Lowest Price on Windows 11, $6.12/Lifetime!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-set-up-image-slideshows-in-windows-11-without-installing-extra-software/"><u>7 Ways to Set Up Image Slideshows in Windows 11 Without Installing Extra Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-disabled-volume-shadow-copy-on-pcs/"><u>Addressing Disabled Volume Shadow Copy on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-issue-of-erased-typing-on-windows-systems/"><u>Addressing the Issue of Erased Typing on Windows Systems</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-instasoul-unleash-your-essence-through-100-dynamic-captions/"><u>[Updated] In 2024, InstaSoul  Unleash Your Essence Through 100 Dynamic Captions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719305742826-windows-pause-auto-updates-no-more-prompts/"><u>Windows Pause Auto-Updates: No More Prompts</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-exploring-stardews-peak-mods-list-of-the-best/"><u>[Updated] In 2024, Exploring Stardew's Peak Mods - List of the Best</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-fatal-wow-bug-on-latest-windows-11-version/"><u>Addressing Fatal WoW Bug on Latest Windows 11 Version</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-using-the-mspcm-bar-tools-windows-11-style/"><u>A Step-by-Step Guide to Using the MSPCM Bar Tools, Windows 11 Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-for-moving-programs-in-windows-11/"><u>A Step-by-Step Approach for Moving Programs in Windows 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-exploring-metaverse-laughter-creating-your-own-funny-online-jokes/"><u>[Updated] Exploring Metaverse Laughter  Creating Your Own Funny Online Jokes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-selectable-items-on-microsofts-new-os/"><u>Addressing Non-Selectable Items on Microsoft's New OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719360477145-reigniting-your-computers-print-functionality-with-effective-wwin-solutions/"><u>Reigniting Your Computer's Print Functionality with Effective WWin Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-ways-to-reset-folder-view-settings-to-default-in-windows-11/"><u>3 Ways to Reset Folder View Settings to Default in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-printers-under-edge-guard-on-windows-11/"><u>Accessing Printers Under Edge Guard on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-1drive-errors-steps-to-success-in-w11/"><u>Addressing 1Drive Errors: Steps to Success in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-key-methods-windows-11-uses-to-intrude-on-privacy/"><u>5 Key Methods Windows 11 Uses to Intrude on Privacy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapting-oculus-quest-2-for-windows-vr-software/"><u>Adapting Oculus Quest 2 for Windows VR Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-stepwise-approach-to-winerror-issues/"><u>A Stepwise Approach to WinError Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensible-windows-screentime-intermission/"><u>A Comprehensible Window's Screentime Intermission</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-complete-fixes-to-solve-iphone-14-plus-randomly-asking-for-apple-id-password-by-drfone-ios/"><u>In 2024, Complete Fixes To Solve iPhone 14 Plus Randomly Asking for Apple ID Password</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-pitfalls-going-for-low-cost-windows-license-keys/"><u>8 Pitfalls: Going for Low-Cost Windows License Keys</u></a></li>
</ul></div>
