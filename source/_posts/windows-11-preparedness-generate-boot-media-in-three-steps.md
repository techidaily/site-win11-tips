---
title: "Windows 11 Preparedness: Generate Boot Media in Three Steps"
date: 2024-07-12T16:49:45.600Z
updated: 2024-07-13T16:49:45.600Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11 Preparedness: Generate Boot Media in Three Steps"
excerpt: "This Article Describes Windows 11 Preparedness: Generate Boot Media in Three Steps"
keywords: Win11BootMediaPrep,WindowsBootGenSteps,PrepareWin11Boot,GenWindowsBootMedia,BootMediaW11Prep,StepsForWin11Boot,CreateBootWin11
thumbnail: https://thmb.techidaily.com/8f5cadb41c029899508ca6efd6723f50f45c76c5999800100c8f4f1fd518b7be.jpg
---

## Windows 11 Preparedness: Generate Boot Media in Three Steps

 A Windows 11 bootable USB drive is useful to clean install your OS, or perform an upgrade. A bootable Windows USB also helps you troubleshoot your PC from critical errors and install Windows on multiple PCs offline.

 Microsoft makes it easy to create an installation media with its Media Creation Tool. In addition, you can also use Rufus and the Command Prompt to create one. In this guide, we show you the three different ways to create a USB flash drive installer for Windows 11\.

## Before We Start: How to Download the Windows 11 ISO Image

 To successfully create a Windows 11 USB bootable drive, you will need a Windows 11 ISO file, also known as an [ISO image](https://www.makeuseof.com/what-is-iso/). As such, get this sorted before you proceed to create a bootable USB. You can easily [download the Windows 11 ISO](https://www.makeuseof.com/windows-11-download-iso/) from the Microsoft official website. Here's how to do it:

1. Visit [Microsoft’s official page](https://www.microsoft.com/software-download/windows11) to download Windows 11\.
2. Scroll down to the **Download Windows 11 Disk Image (ISO) for X64 devices** section.
3. Click the drop-down menu and select **Windows 11 (multi-edition ISO)**.  
![download windows 11 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/download-windows-11-iso.jpg)
4. Next, click on the **Download** **Now** button to continue.
5. The current page will load additional information and show the **Select the product language** section. Click the drop-down for **Choose one** and select your preferred language. Click **Confirm** to continue.  
![download windows 11 iso choose language](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/download-windows-11-iso-choose-language.jpg)
6. When the download section loads, click the **64-bit Download** button.  
![download windows 11 iso 64 bit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/download-windows-11-iso-64-bit.jpg)
7. Your download will begin immediately. However, it may take some time to finish downloading, depending on your Internet speed.

 Once you have the ISO file downloaded, follow one of the methods below to create a Windows 11 bootable USB drive.

## 1\. How to Create a Windows 11 Bootable USB Using Rufus
![create windows 11 bootable usb drive with rufus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/create-windows-11-bootable-usb-drive-with-rufus.png)

 Rufus is an open-source utility to format and create a bootable USB flash drive for the Windows operating system. It's a lightweight utility and offers a few more customization options compared to Microsoft's in-house media creation tool.

 To create a Windows 11 bootable USB drive using Rufus:

1. Visit the [Rufus website](https://rufus.ie/en/) and scroll down to the **Download** section.
2. Click on the **Rufus link** to download the latest version.
3. Run the executable file and click **Yes** if prompted by UAC.
4. Connect your USB flash drive to your PC and wait for Rufus to detect and show it under the **Device** section.
5. Click the drop-down for **Boot selection** and select **Disk or ISO image.**

1. Then, click the **SELECT** button.
2. Select the **Windows ISO** file and click **Open**.
3. Click the drop-down under the **Image option** and select **Standard Windows 11 Installation**.
4. Leave the **Partition scheme (GPT)** and **Target system (UEFI)** as default.
5. Under **Volume label**, enter a name for your bootable flash drive.
6. Leave the **File system** and **Cluster size,** and other options as default.
7. Make sure the **Quick format** and **Create extended label and icon files** option is checked.
8. Click the **Start** button to initiate the bootable drive creating process.

 Once done, Rufus will show a success message. Now you can use the [Windows 11 bootable drive to install the OS](http://www.makeuseof.com/how-to-clean-install-windows-11/) on any compatible system.

## 2\. How to Create a Windows 11 Bootable USB Drive Using the Media Creation Tool

 The media creation tool is Microsoft's in-house solution to create an installation media. You can use the media creation tool to create a bootable USB flash drive or download the ISO file to your local drive. Since it needs to download the ISO to create a bootable drive, you cannot use an existing Windows ISO image with this tool.

 To create an installation media using the media creation tool:

1. Connect your USB flash drive of at least 8GB to your PC. Make sure it is detected and you have taken a backup of all the files on your USB drive.
2. Next, visit the [Microsoft download center](https://www.microsoft.com/software-download/windows11) page.
3. Under the **Create Windows 11 Installation Media** section, click the **Download Now** button and save the file to your PC.
4. Next, run the **Mediacreationtool.exe** file and click **Yes** if prompted by UAC. The tool may take a few seconds to launch, so wait till you see the **Setup wizard.**
5. Click the **Accept button** to agree to the terms.  
![select language and edition Create bootable drive windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/select-langugae-and-edition.png)

1. The media creation tool will automatically select the **Edition** and **Language** to match the current Windows configuration on your PC. To change the language, uncheck **Use the recommended options for this PC** box and select your preferred language from the drop-down menu.
2. Choose your options and click **Next**.  
![choose which media to use Media Creation Tool Bootable Drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/choose-which-media-to-use.png)
3. In the **Choose which media to use** window, select **USB flash** drive.
4. Click the **Next** button.
5. Select your USB drive from the list of drives available.  
![select a usb drive media creation tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/select-a-usb-drive.png)
6. Click the **Next** button to continue.
7. Next, click the **Finish** button.

 Media Creation Tool will now download the necessary Windows 11 files and create an installation media. When the "your USB flash drive is ready" message appears, click the **Finish** button to close the setup wizard. Now you can boot from the USB drive to troubleshoot or [clean install Windows 11](https://www.makeuseof.com/how-to-clean-install-windows-11/).

## 3\. How to Create a Bootable Drive Using Command Prompt

 If you don’t want to use a third-party tool to create a bootable drive, you can use the Diskpart utility and Command Prompt to create installation media. Here's how to do it.

1. First, take a backup of all the files on your USB drive and then connect it to your PC.
2. Press the **Win** key, type cmd, **and** click on **Run as Administrator** under **Command Prompt.** You can also use PowerShell if you prefer it over Command Prompt.  
![disk part windows 11 bootable drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/disk-part-windows-11-bootable-drive.png)
3. In the Command Prompt window, type the following command and hit enter to launch the **Windows Diskpart** utility.  
`DISKPART`
4. Next, type the following command to list all the available storage devices:  
`LIST DISK`
5. Here, locate your USB drive. You can look at the **Size column** to determine your USB drive. In this case, the USB drive is listed as **Disk 2.**

1. Next, type the following command to select your drive:  
`SEL DISK 2`
2. In the above command, change **DISK 2** with the number assigned to your USB drive. For example, if you have a single SSD or SATA drive setup, your primary drive will show as **DISK 0** and USB drive as **DISK 1**. It is of **extreme importance that you select the right drive** as the next step involves wiping clean the selected drive.
3. Once the drive is erased, type the following command and hit enter to erase all the content from the drive:  
`Clean`
4. Next, type the following command to create a primary partition:  
`Create Partition Primary`
5. After creating a primary partition, type the following command to select the main partition:  
`List Par`
6. Command Prompt will show the details of your USB drive.  
![format usb drive windows 11 cmd](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/format-usb-drive-windows-11-cmd.png)
7. Type the following command and hit enter to activate the partition:  
`Active`
8. Then type the following command to format the USB drive. It is important to format the drive in NTFS format as the [FAT32 format will cause the incorrect parameter error](https://www.makeuseof.com/windows-fix-parameter-is-incorrect-error/).  
`FORMAT FS=NTFS LABEL=&ldquo;BootableUSB&rdquo; QUICK OVERRIDE`
9. Once done, type **Exit** and hit enter to exit the Disk Part utility.

 Now you will need to mount the ISO image and then move its content to your USB drive.

![mount ISO image Windows 11 Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/mount-ISO-image-Windows-11-Command-Prompt.png)

1. To do this, type the following command and hit **Enter** to mount the Windows 11 ISO file:  
`PowerShell Mount-DiskImage -ImagePath "C:\Users\UserName\Downloads\Win11_English_x64v1.iso"`
2. In the above command, replace the file path with the location of your Windows 11 ISO.  
![cmd list volume](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/cmd-list-volume.png)
3. Once the ISO is mounted, type the following command to launch Diskpart.  
`Diskpart`
4. Next, type the following command to show the available volume.  
`List volume`
5. This will help you determine the Drive letter for the mounted ISO file. In the **Type column**, the mounted ISO will be listed as **DVD-ROM**. And the **Ltr column** lists the letter associated with the volume. Note down the details of the ISO volume as you will be using it moving forward.  
![list volume cmd windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/list-volume-cmd-windows-11.png)

1. Once you have the volume details for the mounted ISO, type the following command to exit Diskpart:  
`Exit`
2. Next, type the mounted ISO volume letter and hit enter. For example, if your mounted ISO volume letter is **J**, then type the following command and press Enter.  
`J:`
3. Type the following command to boot from CD:  
`cd boot`
4. Next, type the following command to apply the master boot code compatible with Bootmgr to the USB flash drive:  
`Bootsect /nt60 I:`
5. In the above command, replace **I** with the drive letter associated with your USB flash drive.  
![copy iso files to usb drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/copy-iso-files-to-usb-drive.png)
6. Next, type the following command and hit Enter to copy Windows 11 system files to the USB flash drive:  
`xcopy J:\*.* I:\ /E /F /H`
7. In the above command, replace **K:** and **I:** with your **Mounted ISO Volume** and **USB drive** letter, respectively.
8. The process may take a 5-10 minutes to complete. If the Command Prompt feels stuck, it is normal behaviour, so wait until the process is complete.
9. If successful, you will see a **Files (s) Copied** message.

 That’s it. Now you can use the USB bootable drive to clean install Windows 11\.

## Multiple Ways to Create a Windows 11 Bootable USB Drive

 With its Media Creation Tool, Microsoft makes it easy to create installaltion media. However, if you have a Windows 11 ISO image ready, you can use Rufus or the Command Prompt to create a Windows 11 bootable USB drive quickly. You can use the same to clean install Windows 11 on a new PC, troubleshoot your Windows computer or dual boot Windows 10 with Windows 11\.

 A Windows 11 bootable USB drive is useful to clean install your OS, or perform an upgrade. A bootable Windows USB also helps you troubleshoot your PC from critical errors and install Windows on multiple PCs offline.

 Microsoft makes it easy to create an installation media with its Media Creation Tool. In addition, you can also use Rufus and the Command Prompt to create one. In this guide, we show you the three different ways to create a USB flash drive installer for Windows 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/mastering-malware-discovery-without-software-assistance/"><u>Mastering Malware Discovery without Software Assistance</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-videos-from-honor-x50iplus-by-fonelab-android-recover-video/"><u>How to retrieve erased videos from Honor X50i+</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11-dir-not-empty-error-0x80070091/"><u>Overcoming Windows 11 Dir Not Empty Error (0X80070091)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-no-network-reachable-errors-win/"><u>Eradicating No Network Reachable Errors (WIN)</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-twitters-viral-hit-list-tiktok-edition/"><u>2024 Approved  Twitter's Viral Hit List  TikTok Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-low-end-specs-in-windows-game-capture/"><u>Overcoming Low-End Specs in Windows Game Capture</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easing-the-heat-cutting-down-vanguard-writes-on-your-computer/"><u>Easing the Heat: Cutting Down Vanguard’ Writes on Your Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-hidden-dangers-on-a-computer-screen/"><u>Navigating Hidden Dangers on a Computer Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/creating-a-window-11-notebook-space-you-love/"><u>Creating a Window 11 Notebook Space You Love</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensively-tackle-the-icloud-install-issue-on-windows/"><u>Comprehensively Tackle the iCloud Install Issue on Windows</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-laughterbox-easy-entry-endless-entertainment/"><u>In 2024, LaughterBox  Easy Entry, Endless Entertainment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-android-into-windows-11-select-the-best-6-companion-apps/"><u>Integrating Android Into Windows 11: Select the Best 6 Companion Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11-copypaste-anomalies/"><u>Overcoming Windows 11 Copy/Paste Anomalies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/multi-vm-mastery-setting-up-linux-vm-in-hyper-v-on-windows/"><u>Multi-VM Mastery: Setting Up Linux VM in Hyper-V on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-maze-of-non-responsive-windows-services-management-tool/"><u>Navigating the Maze of Non-Responsive Windows Services Management Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-mute-your-keyboard-on-a-windows-computer/"><u>How to Mute Your Keyboard on a Windows Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fundamentals-of-selecting-the-best-win-notebook/"><u>Fundamentals of Selecting the Best Win Notebook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/experience-gaming-unbound-android-in-desktop-windows-with-google-play-service/"><u>Experience Gaming Unbound: Android in Desktop Windows with Google Play Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-audacitys-error-while-opening-sound-device-issue-in-windows-10-and-11/"><u>How to Fix Audacity’s “Error While Opening Sound Device” Issue in Windows 10 & 11</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-download-vn-video-editor-for-mac-or-explore-alternative-options/"><u>Updated 2024 Approved Download VN Video Editor for Mac or Explore Alternative Options</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-how-to-charm-your-way-into-a-friends-tiktok-show/"><u>[New] In 2024, How to Charm Your Way Into a Friend’s TikTok Show</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-efficient-bluescreenview-use/"><u>Essential Tips for Efficient BlueScreenView Use</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-enhance-business-efficiency-mastering-call-tracking-with-google-voice-services/"><u>New Enhance Business Efficiency Mastering Call Tracking with Google Voice Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hide-post-display-adjustment-in-windows-power-configuration/"><u>Hide Post-Display Adjustment in Windows Power Configuration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-top-visibility-of-your-notebooks-on-win/"><u>Ensuring Top-Visibility of Your Notebooks on Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-window-display-mastering-alt-tab-order-in-win1110/"><u>Maximizing Window Display: Mastering Alt-Tab Order in Win11/10</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-change-samsung-galaxy-s23plus-lock-screen-password-by-drfone-android/"><u>In 2024, How To Change Samsung Galaxy S23+ Lock Screen Password?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-non-starting-adobe-photoshopping-in-windows-11/"><u>How to Enable Non-Starting Adobe Photoshopping in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/finding-your-preferred-soft-install-tool-on-win-devices/"><u>Finding Your Preferred Soft Install Tool on Win Devices</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-liberating-content-free-techniques-for-transforming-videos-into-auditory-experiences/"><u>2024 Approved Liberating Content Free Techniques for Transforming Videos Into Auditory Experiences</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/4-easy-ways-for-your-motorola-moto-g23-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>4 Easy Ways for Your Motorola Moto G23 Hard Reset | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-music-from-meizu-21-by-fonelab-android-recover-music/"><u>Easy steps to recover deleted music from Meizu 21</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/scrutinizing-high-quality-brightness-in-hd-imaging/"><u>Scrutinizing High-Quality Brightness in HD Imaging</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-in-2024-12-websites-with-triggered-animate-on-scroll-examples/"><u>New In 2024, 12 Websites with Triggered Animate on Scroll Examples</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-camera-apps-error-0xa00f425d-in-windows-11-and-11/"><u>How to Fix the Camera App’s Error 0xA00F425D in Windows 11 & 11</u></a></li>
</ul></div>
