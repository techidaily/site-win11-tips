---
title: "Cross-OS Synergy: Creating a Linux VM Inside Windows Using Hyper-V"
date: 2024-07-12T16:49:03.244Z
updated: 2024-07-13T16:49:03.244Z
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
<li><a href="https://win11-tips.techidaily.com/exploring-actions-and-activation-labels-in-dev-tools/"><u>Exploring Actions & Activation Labels in Dev Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-tackle-the-windows-exception-breaking-point-issue/"><u>How to Tackle the Windows Exception Breaking Point Issue</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-zooms-best-audio-fixes-clear-sounds-and-hearing-improvement/"><u>[Updated] Zoom's Best Audio Fixes  Clear Sounds & Hearing Improvement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-to-rectify-cant-add-your-folder-now-in-onedrive/"><u>Essential Steps to Rectify 'Can't Add Your Folder Now' In OneDrive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-nvidia-connect-error-in-windows-oses/"><u>Overcoming NVIDIA Connect Error in Windows OSes</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-your-route-to-revisiting-fbs-recently-viewed-gems/"><u>[Updated] 2024 Approved  Your Route to Revisiting Fb’s Recently Viewed Gems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-pc-storage-identifying-excess-disk-usage-in-windows/"><u>Maximizing PC Storage: Identifying Excess Disk Usage in Windows</u></a></li>
<li><a href="https://some-tips.techidaily.com/the-ultimate-tutorial-for-lut-use-in-after-effects-for-2024/"><u>The Ultimate Tutorial for LUT Use in After Effects for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-11-mail-tips-for-resolving-html-code-displays-in-emails/"><u>Fixing Windows 11 Mail: Tips for Resolving HTML Code Displays in Emails</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overhauling-your-operating-systems-state-a-windows-1011-reboot-guide/"><u>Overhauling Your Operating System's State: A Windows 10/11 Reboot Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/say-goodbye-to-old-files-enabling-the-autodelete-option-on-windows-11/"><u>Say Goodbye to Old Files: Enabling the Autodelete Option on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-keygen-malware-on-windows-recognition-and-eradication-steps/"><u>Identifying Keygen Malware on Windows: Recognition and Eradication Steps</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-streamlining-the-process-of-google-voice-call-capture/"><u>[Updated] In 2024, Streamlining the Process of Google Voice Call Capture</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrate-compatibility-troubleshoot-in-windows-clippy/"><u>Integrate Compatibility Troubleshoot in Windows Clippy</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-unleash-flawless-footage-overcome-instagram-video-hurdles/"><u>[New] In 2024, Unleash Flawless Footage  Overcome Instagram Video Hurdles</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-innovations-in-home-audio-engineering-analyzing-the-best-and-worst-of-the-top-digital-music-makers-this-year/"><u>2024 Approved Innovations in Home Audio Engineering Analyzing the Best and Worst of the Top Digital Music Makers This Year</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/fine-tuning-your-films-rhythm-synchronizing-soundtracks-with-video-in-final-cut-pro-x/"><u>Fine-Tuning Your Films Rhythm Synchronizing Soundtracks with Video in Final Cut Pro X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-unreachable-network-paths/"><u>Overcoming Windows' Unreachable Network Paths</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-the-ultimate-list-of-windows-videography-tools-to-oust-background-noise/"><u>New In 2024, The Ultimate List of Windows Videography Tools to Oust Background Noise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stay-connected-disable-usb-sleep-on-windows-11-pc/"><u>Stay Connected: Disable USB Sleep on Windows 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-win11s-security-measures-through-rufus-mastery/"><u>Overcoming Win11's Security Measures Through Rufus Mastery</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-easy-screencasting-techniques-systematic-guidebook/"><u>[Updated] 2024 Approved  Easy Screencasting Techniques  Systematic Guidebook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-winscomrssvsvc-error-on-initial-startup/"><u>Mitigating WinscomrssvSvc Error on Initial Startup</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-resize-like-a-pro-mastering-vertical-video-ratios-for-social-media/"><u>New In 2024, Resize Like a Pro Mastering Vertical Video Ratios for Social Media</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-overview-of-fps-for-youtube-videos/"><u>New 2024 Approved Overview of FPS for YouTube Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectify-restore-responsive-shortcut-keys-in-windows-11/"><u>Rectify: Restore Responsive Shortcut Keys in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-prevent-windowed-app-relocations/"><u>Methods to Prevent Windowed App Relocations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-wi-fi-setup-woes-reconciling-missing-steps-in-prompts/"><u>Navigating Wi-Fi Setup Woes: Reconciling Missing Steps in Prompts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/introducing-ad-free-innovation-windows-11s-modernized-start/"><u>Introducing Ad-Free Innovation: Windows 11'S Modernized Start</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-chilly-ambiance-ideal-winter-bgs-for-videos/"><u>[New] 2024 Approved  Chilly Ambiance  Ideal Winter BGs for Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safe-stepping-stones-on-windows-11-top-8-to-skip/"><u>Safe Stepping Stones on Windows 11: Top 8 To Skip</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-exposed-the-hazards-of-fake-follower-purchases-on-youtube/"><u>[New] Exposed  The Hazards of Fake Follower Purchases on YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-swiftly-clear-windows-cached-data/"><u>How to Swiftly Clear Windows' Cached Data</u></a></li>
<li><a href="https://fake-location.techidaily.com/the-best-8-vpn-hardware-devices-reviewed-on-honor-x7b-drfone-by-drfone-virtual-android/"><u>The Best 8 VPN Hardware Devices Reviewed On Honor X7b | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-integration-wirelessly-link-dualshock-3-and-win/"><u>Seamless Integration: Wirelessly Link DualShock 3 & Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reactivate-an-inactive-windows-11-license/"><u>How to Reactivate an Inactive Windows 11 License</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-disparities-in-cloud-and-offline-windows-updates/"><u>Exploring Disparities in Cloud and Offline Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rushing-past-stuck-warcraft-64-patches/"><u>Rushing Past Stuck Warcraft 6.4 Patches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/smooth-switch-the-best-windows-apps-for-ex-mac-users/"><u>Smooth Switch: The Best Windows Apps for Ex-Mac Users</u></a></li>
</ul></div>
