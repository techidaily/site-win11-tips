---
title: "Multi-VM Mastery: Setting Up Linux VM in Hyper-V on Windows"
date: 2024-08-16T01:39:40.432Z
updated: 2024-08-17T01:39:40.432Z
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

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
### 2\. Install Hyper-V on the Windows Virtual Machine

 To install Hyper-V on the VMware Windows virtual machine, repeat the following steps.

1. Launch the VMware app on your system. Double-click on the Windows virtual machine to boot it up.
2. Once you boot to the desktop, press the**Win + R** key to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
3. Type**appwiz.cpl** and press the enter key.
4. The programs and features window will launch. Click on the**Turn Windows Features on or off** option.
5. Scroll down and click on the**Hyper-V** checkbox in the Windows Features list.  
![Install Hyper-V on the Windows Virtual Machine](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/install-hyper-v-on-the-windows-virtual-machine.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
6. Click on the**OK** button to install the feature on your system.
7. **Restart** your system to apply changes when the installation completes.

 Hyper-V is now active on your Windows virtual machine. Next, you need to create a Linux virtual machine it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
### 3\. Create a Linux Virtual Machine Using Hyper-V

 The last piece of the puzzle is to create a Linux virtual machine inside the Windows virtual machine using Hyper-V. You can pick any Linux distribution that you want. We will go with Ubuntu for this experiment. You have to download the Ubuntu ISO file inside the virtual machine from the [Ubuntu website](https://ubuntu.com/download/desktop) before starting with the steps.

To create an Ubuntu virtual machine, do as follows:

1. Boot up the Windows virtual machine. Press the**Win key** and type Hyper-V manager. Launch the app.
2. Navigate to the right-hand side section and click on**New > Virtual Machine** .  
![Create a Linux Virtual Machine Using Hyper-V 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-1.jpg)
<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Click on the**Next** button. Enter the name of the virtual machine and click on**Next** .
4. Click on the**Generation 1** radio button and click on Next.
5. Keep the**Startup Memory** as**2GB** and enable the**Use Dynamic memory for this virtual machine** option.  
![Create a Linux Virtual Machine Using Hyper-V 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-2.jpg)
6. Then, click on**Next** button and select the**Default switch** option in the Configure Networking section.
7. Click on the**Create a virtual hard disk** option and allocate**20GB** to the virtual hard disk. Move to the next section.  
![Create a Linux Virtual Machine Using Hyper-V 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-3.jpg)
8. Pick the**Install an operating system from a bootable CD/DVD-ROM** option located under the Installation options section. Select the Ubuntu Image file (.iso) you downloaded before beginning this step.  
![Create a Linux Virtual Machine Using Hyper-V 4](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-4.jpg)
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<span id="1793213">
					<video width="1080" height="1620" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:1080px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://youtube-data.techidaily.com/024-approved-elevate-your-online-presence-secrets-of-youtube-live-with-wirecast/"><u>[New] 2024 Approved  Elevate Your Online Presence  Secrets of Youtube Live with WireCast</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-brand-synergy-in-the-age-of-digital-partnerships/"><u>[New] Brand Synergy in the Age of Digital Partnerships</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-beginners-guide-capturing-youtube-videos-as-screencasts-without-payment/"><u>[New] In 2024, Beginner's Guide  Capturing YouTube Videos as Screencasts Without Payment</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-evade-robotic-ratings-for-real-time-traffic-surge/"><u>[New] In 2024, Evade Robotic Ratings for Real-Time Traffic Surge</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-unveiling-inauthentic-accounts-on-brand-pages/"><u>[New] Unveiling Inauthentic Accounts on Brand Pages</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-captivation-craftsman-for-posters/"><u>[Updated] Captivation Craftsman for Posters</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-craft-compelling-content-essential-youtube-short-video-edits/"><u>[Updated] Craft Compelling Content  Essential Youtube Short Video Edits</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-essential-android-apps-for-playing-old-school-ps2-titles-for-2024/"><u>[Updated] Essential Android Apps for Playing Old-School PS2 Titles for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-crafting-a-viral-narrative-on-social-media/"><u>[Updated] In 2024, Crafting a Viral Narrative on Social Media</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-monetize-like-a-pro-how-to-use-youtube-studio-on-any-device-for-2024/"><u>[Updated] Monetize Like a Pro  How to Use Youtube Studio on Any Device for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/2-ways-to-monitor-oneplus-12r-activity-drfone-by-drfone-virtual-android/"><u>2 Ways to Monitor OnePlus 12R Activity | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-peek-at-the-finest-laptops-from-ifa-2023/"><u>A Peek at the Finest Laptops From IFA 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-seamless-shift-to-workspace-with-windows-1011/"><u>A Seamless Shift to Workspace with Windows 10/11</u></a></li>
<li><a href="https://video-capture.techidaily.com/apex-10-royale-showdowns-for-2024/"><u>Apex 10 Royale Showdowns for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/are-instagrams-video-selfies-truly-genuine-in-2024/"><u>Are Instagram's Video Selfies Truly Genuine, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719319638119-collectors-paradise-unlocked-free-windows-11-for-keys-fan-year-round/"><u>Collector’s Paradise Unlocked: Free Windows 11 For Keys Fan, Year-Round!</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/crafting-shareable-instagram-stories-that-spread-like-wildfire-for-2024/"><u>Crafting Shareable Instagram Stories That Spread Like Wildfire for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/create-a-seamless-workflow-with-alt-tab-in-win1110/"><u>Create a Seamless Workflow with Alt-Tab in Win11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-ways-to-expand-hard-drive-capacity-in-windows-for-free/"><u>Efficient Ways to Expand Hard Drive Capacity in Windows, For Free</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/effortless-drive-cleanup-with-bitraser-available-now-for-immediate-purchase/"><u>Effortless Drive Cleanup with BitRaser – Available Now for Immediate Purchase</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-windows-storage-without-overwriting-data/"><u>Elevate Windows Storage Without Overwriting Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-windowtop-calculator-stays-on-top/"><u>Ensuring Windowtop Calculator Stays on Top</u></a></li>
<li><a href="https://win11-tips.techidaily.com/epic-games-troubleshooting-on-pc-focus-on-login-issues/"><u>Epic Games Troubleshooting on PC: Focus on Login Issues</u></a></li>
<li><a href="https://tech-haven.techidaily.com/explore-the-best-free-ai-solutions-like-microsofts-gpt-3-similar-to-sora/"><u>Explore the Best FREE AI Solutions Like Microsoft's GPT-3, Similar to Sora</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-responding-spotify-app-in-w10-and-w11/"><u>Fixing Non-Responding Spotify App in W10 & W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/github-desktop-essentials-for-effective-windows-git-control/"><u>GitHub Desktop Essentials for Effective Windows Git Control</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hotkey-hacks-masterful-window-management-made-simple/"><u>Hotkey Hacks: Masterful Window Management Made Simple</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-whatsapp-messages-on-vivo-v29-pro-without-them-knowing-drfone-by-drfone-virtual-android/"><u>How to Track WhatsApp Messages on Vivo V29 Pro Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-xs-max-to-others-ios-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone XS Max To Others ios devices? | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-can-128gb-hold-extensive-video-content/"><u>In 2024, Can 128GB Hold Extensive Video Content?</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-corrected-clandestine-miniature-video-absence/"><u>In 2024, Corrected  Clandestine Miniature Video Absence</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/in-depth-analysis-of-the-economical-amazon-basics-6-sheet-paper-shredder/"><u>In-Depth Analysis of the Economical Amazon Basics 6-Sheet Paper Shredder</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-windows-snip-and-sketch-with-one-move/"><u>Launching Windows Snip & Sketch With One Move</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-connectivity-fixing-lol-drops-in-windows/"><u>Mastering Connectivity: Fixing LoL Drops in Windows</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mastering-the-art-of-image-deletion-on-facebook-a-step-by-step-process/"><u>Mastering the Art of Image Deletion on Facebook - A Step-by-Step Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-resolution-of-error-0x80d03801/"><u>Mastering the Resolution of Error 0X80D03801</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-calculator-display-timeframe-on-windows/"><u>Maximizing Calculator Display Timeframe on Windows</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/mophies-top-end-powerstation-ac-an-affordable-choice-for-easy-charging-on-the-go/"><u>Mophie's Top-End Powerstation AC: An Affordable Choice for Easy Charging on the Go</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-process-of-win-backup-defaulting/"><u>Navigating the Process of Win Backup Defaulting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overhauling-copy-and-paste-on-chrome-edge-firefox-os/"><u>Overhauling Copy & Paste on Chrome, Edge, Firefox OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pivotal-techniques-for-reworking-windows-via-shortcuts/"><u>Pivotal Techniques for Reworking Windows via Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/purely-native-drive-duality-creation-guide/"><u>Purely Native Drive Duality Creation Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reimagining-admin-workflow-a-fresh-perspective-on-windows-uac/"><u>Reimagining Admin Workflow: A Fresh Perspective on Windows UAC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-outlook-fails-in-windows-systems/"><u>Resolve Outlook Fails in Windows Systems</u></a></li>
<li><a href="https://data-recovery.techidaily.com/secure-iphone-data-extraction-unlocking-lost-information/"><u>Secure iPhone Data Extraction: Unlocking Lost Information</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snowy-seasonings-sharing-apps-from-microsofts-marketplace/"><u>Snowy Seasonings: Sharing Apps From Microsoft's Marketplace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-applying-apple-maps-to-windows/"><u>Step-by-Step Guide: Applying Apple Maps to Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-windows-management-with-effective-key-combinations/"><u>Streamline Windows Management with Effective Key Combinations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-rectify-zero-error-in-windows-11-installation-steps/"><u>Swiftly Rectify Zero-Error in Windows 11 Installation Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-domain-based-biometric-use-in-windows-11/"><u>Tailoring Domain-Based Biometric Use in Windows 11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-10-oppo-f23-5g-android-sim-unlock-apk-by-drfone-android/"><u>Top 10 Oppo F23 5G Android SIM Unlock APK</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-htc-u23-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive HTC U23 Screen | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-homescreen-activation-in-windows-11/"><u>Troubleshooting Homescreen Activation in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-store-error-with-xbox-games/"><u>Troubleshooting Windows Store Error with Xbox Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-normalcy-windows-11s-basic-user-reset-guide/"><u>Unleashing Normalcy: Windows 11'S Basic User Reset Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-startup-paths-essential-steps/"><u>Unlocking Windows' Startup Paths: Essential Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/visualize-storage-quickly-integrate-diskanalyzer-into-windows-menu/"><u>Visualize Storage Quickly: Integrate DiskAnalyzer Into Windows Menu</u></a></li>
</ul></div>
