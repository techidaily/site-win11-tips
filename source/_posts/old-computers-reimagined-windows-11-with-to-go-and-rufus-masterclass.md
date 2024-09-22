---
title: "Old Computers Reimagined: Windows 11 with To Go and Rufus Masterclass"
date: 2024-09-14T17:16:37.529Z
updated: 2024-09-21T22:03:13.624Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Old Computers Reimagined: Windows 11 with To Go and Rufus Masterclass"
excerpt: "This Article Describes Old Computers Reimagined: Windows 11 with To Go and Rufus Masterclass"
keywords: Windows 11 Revival,ToGo PCs,Rufus Guide,Old Tech Makeover,Win11 Retro,Reimagined Computers,Masterclass Forold PCs
thumbnail: https://thmb.techidaily.com/3a8d29dc752129bc6cecd890184a07ba60927370b95afc8af67003c49b108b72.jpg
---

## Old Computers Reimagined: Windows 11 with To Go and Rufus Masterclass

 Windows 11 system requirements specify that it needs UEFI, Secure Boot and TPM. Many old computers are powerful enough to run Windows 11\. Yet, they cannot install the OS because of these requirements. Windows 11 refuses to install and displays the message "this PC can't run Windows 11".

 There is a way to bypass these requirements and install Windows 11 on any powerful computer, even if it is old. The process is quite simple as well.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Are Windows 11's System Requirements?

 Unlike earlier versions, Windows 11 is rigid with its minimum system requirements. It not only asks for a fast processor but also insists on the processor being a certain generation or higher. The supported processors include newer models from AMD, Intel, and Qualcomm.

![Screenshot showing the minimum system requirements for Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/01-screenshot-showing-the-minimum-system-requirements-for-windows-11.jpg)

[Image via Microsoft.com](https://www.microsoft.com/en-in/windows/windows-11-specifications)

 You can check if your PC meets these requirements using the [PC Health Check app](https://support.microsoft.com/en-us/windows/how-to-use-the-pc-health-check-app-9c8abd9b-03ba-4e67-81ef-36f37caa7844). But, if any of the requirements are not fulfilled, Windows will say that the system does not meet the requirements.

![Screenshot showing that the PC does not meet minimum system requirements for Windows 11 in PC Health Check app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/02-screenshot-showing-that-the-pc-does-not-meet-minimum-system-requirements-for-windows-11-in-pc-health-check-app.jpg)

 Windows 11 compatibility check is not only a warning, but will also result in refusal to install the OS. [Windows 10 will retire on October 14, 2025](https://www.makeuseof.com/windows-10-last-version-end-of-support/), after which it will not get any updates. As such, your PC won't get any new features or security fixes unless you install Windows 11 on it.

 However, you can give your computer a new lease of life by creating a Windows To Go bootable disk. With that, you can bypass all these requirements:

* A compatible processor,
* A UEFI BIOS,
* Secure Boot compatibility,
* TPM (Trusted Platform Module),
* and a Microsoft account for the initial device setup.

## The Hardware You Need to Create a Windows 11 To Go Drive

![Photo showing a SSD connected to a USB to SATA adapter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/03-photo-showing-a-ssd-connected-to-a-usb-to-sata-adapter.jpg)

 Portable versions of Windows run over the USB interface. You need a USB 3.0 to SATA adapter and an SSD. One end of the adapter will connect to the USB 3.0 on your computer, and the SSD will be at the other end. Quite simple.

 And yes, you can install Windows To Go on a USB flash drive. It will also work with a USB 2.0 and a hard disk as well. But, these slower devices and interfaces are not recommended. We will get to this later.

## How to Create a Windows To Go Drive Using Rufus

 Rufus is a free open-source tool to create bootable USB drives, which you can use to install operating systems. Rufus can also create Windows To Go portable drives. So, to start, [download Rufus from the official website](https://rufus.ie/en/).

 You will also need an image of Windows 11\. It is [available as a free download at Microsoft](https://www.microsoft.com/software-download/windows11). You are not required to register to download the media. Activation after installation is optional as well.

 On the download page, scroll down to the section titled **Download Windows 11 Disk Image (ISO) for x64 devices**. Then, select **Windows 11 (multi edition ISO for x64 devices)** from the drop-down box.

![Screenshot showing download page and options of Windows 11 Disk Image](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/04-screenshot-showing-download-page-and-options-of-windows-11-disk-image.jpg)

[Image via Microsoft.com](https://www.microsoft.com/software-download/windows11)

 Scroll down to **Select the product language** and click **Confirm** to download. The download is in excess of 5GB. Once downloaded, connect your USB SSD and run Rufus.

### How to Use Rufus

 Once Rufus is started, it's time to set up your drive. Select your USB SSD in the Device dropdown box. If the USB drive does not show up, expand **Advanced drive properties** and check **List USB Hard Drives**. For **Boot selection**, since you have already downloaded the image, click **SELECT** and choose the Windows 11 ISO.

![Screenshot showing selection of USB SSD in Device dropdown box of Rufus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/05-screenshot-showing-selection-of-usb-ssd-in-device-dropdown-box-of-rufus.jpg)

![Screenshot showing selection of Disk Image in Rufus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/06-screenshot-showing-selection-of-disk-image-in-rufus.jpg)

![Screenshot showing selection of Windows 11 ISO as Disk Image in Rufus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/07-screenshot-showing-selection-of-windows-11-iso-as-disk-image-in-rufus.jpg)

Close

 For the **Image Option** select **Windows To Go.** This will create a portable installation of Windows 11 that you can use across multiple computers. In the **Partition scheme,** select **GPT** if your drive is above 2TB, or select **MBR** if below 2TB. If your computer does not have UEFI, you need to stick to MBR only. If you don't know the difference between the two, check out [MBR vs. GPT: which should you use?](https://www.makeuseof.com/tag/mbr-vs-gpt/)

 GPT will work with UEFI only which is different from CSM BIOS. The combination to choose depends upon what your computer has. You should decide it based on the findings during the PC Heath Check.

![Screenshot showing selection of Windows To Go in Image Option of Rufus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/08-screenshot-showing-selection-of-windows-to-go-in-image-option-of-rufus.jpg)

![Screenshot showing selection of GPT in Partition scheme of Rufus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/09-screenshot-showing-selection-of-gpt-in-partition-scheme-of-rufus.jpg)

![Screenshot showing selection of Target system in Rufus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/10-screenshot-showing-selection-of-target-system-in-rufus.jpg)

Close

 You can leave the rest of the options to their default and click **Start**. Rufus will then ask you to choose the version of Windows 11\. Since you have downloaded the full version, all versions are available for installation. Choose the one that suits your needs.

 Rufus will present you with more options to customize your installation. Here is the best way to set up Rufus, as it sorts out a lot of issues:

1. Select **Prevent Windows To Go from accessing internal disks**. This will prevent portable media from disturbing the OS on the host machine.
2. Select **Remove requirement for an online Microsoft account** if you don’t like to create one for privacy. This is no longer an option in standard Windows 11 installation, as it requires a Microsoft account.
3. Did you not add a Microsoft account? You need a local account then, Create a local account with username as you like.
4. Leave the other two options checked as well, this will save time during installation.

![Screenshot showing selection of Windows version from the version list in Rufus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/11-screenshot-showing-selection-of-windows-version-from-the-version-list-in-rufus.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134243/18498" target="_top" id="2134243">
  <img src="//a.impactradius-go.com/display-ad/18498-2134243" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134243/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Screenshot showing customization of Windows installation in Rufus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/12-screenshot-showing-customization-of-windows-installation-in-rufus.jpg)

Close

 Once you're ready to go, click **Start.** Rufus will clear the data on the portable drive, write Windows 11 files, and make the drive bootable. This will usually take around 10 minutes.

![Screenshot showing warning that all data in the USB SSD will be destroyed and to click OK to confirm in Rufus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/13-screenshot-showing-warning-that-all-data-in-the-usb-ssd-will-be-destroyed-and-to-click-ok-to-confirm-in-rufus.jpg)

<!-- affiliate ads begin -->
<span id="1155462">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1155462.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1155462">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1155462.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1155462%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1155462/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Screenshot showing Rufus applying the Windows 11 Disk Image to the USB SSD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/14-screenshot-showing-rufus-applying-the-windows-11-disk-image-to-the-usb-ssd.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130890/7443" target="_top" id="2130890">
  <img src="//a.impactradius-go.com/display-ad/7443-2130890" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130890/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Screenshot showing that Rufus completed applying the Windows 11 Disk Image to the USB SSD and is ready for boot](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/15-screenshot-showing-that-rufus-completed-applying-the-windows-11-disk-image-to-the-usb-ssd-and-is-ready-for-boot.jpg)

Close

 When done, close Rufus. If you are going to use Windows To Go on the same computer, reboot it. If you want to use it on another computer, eject the USB device and connect it to the target computer.

### How to Set Up Windows 11 to Boot

[Enter the UEFI or BIOS menu](https://www.makeuseof.com/tag/enter-bios-computer/), it is usually the DEL key on desktops and F2 key on laptops. The screens vary between different computers, adapt these instructions as needed. Go to the **Boot** tab and set the USB drive as the first boot device. **Save and Exit** (usually F10).

![Screenshot showing the setting of the USB SSD as the first boot priority in BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/16-screenshot-showing-the-setting-of-the-usb-ssd-as-the-first-boot-priority-in-bios.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080317/19272" target="_top" id="2080317">
  <img src="//a.impactradius-go.com/display-ad/19272-2080317" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080317/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Your computer will boot into Windows To Go. The screen shows that the computer’s **Secure Boot** is off, it does not have the TPM either.

![Screenshot showing the boot of USB SSD with the Windows 11 Disk Image](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/17-screenshot-showing-the-boot-of-usb-ssd-with-the-windows-11-disk-image.jpg)

 Windows will take a few minutes to set up everything. Since you have already set the regional options and privacy options, the installation will not ask any more questions.

![Screenshot showing Windows 11 setting everything up after boot of USB SSD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/18-screenshot-showing-windows-11-setting-everything-up-after-boot-of-usb-ssd.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082520/7443" target="_top" id="2082520">
  <img src="//a.impactradius-go.com/display-ad/7443-2082520" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082520/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once done, you have Windows 11, completely functional on a computer that does not meet the minimum system requirements. It will still run A-OK!

![Screenshot showing Windows 11 running perfectly on a Computer that does not meet minimum requirements](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/19-screenshot-showing-windows-11-running-perfectly-on-a-computer-that-does-not-meet-minimum-requirements.jpg)

 It will also update, as a normal installation would do. There is still one thing you need to do. You did not set the password when you created the username in Rufus. This is important for security.

 To set the password, open **Settings** \> search for **Change your password** \> click **Password** and change it.

![Screenshot showing setting of password to the Local account of newly installed Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/20-screenshot-showing-setting-of-password-to-the-local-account-of-newly-installed-windows-11.jpg)

 If you didn’t do that, Windows 11 will compel you to do it at the next reboot anyway.

![Screenshot showing Windows 11 telling us to set a password to the Local account after reboot](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/21-screenshot-showing-windows-11-telling-us-to-set-a-password-to-the-local-account-after-reboot.jpg)

## How to Use the Right Hardware for Windows To Go

 Windows 11 on a USB drive will work well, exactly as it would on an internal drive, provided the disk speeds are up to the mark. As such, it's a good idea to ensure you're using the right ports and drives to ensure the quickest experience possible.

### SSDs Are Always a Better Choice

![Photo showing a Hard Disk and a SSD and to prefer a SSD to HDD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/22-photo-showing-a-hard-disk-and-a-ssd-and-to-prefer-a-ssd-to-hdd.jpg)

 Solid state drives (SSD) have no moving parts in them. This makes them very fast compared to hard disks (HDD) which use spinning disks.

 Operating systems use plenty of small files, and SSDs shine at the read/write speed of these files. Hard disks, in contrast, need more time to seek the files. This is shown via the access time of each drive; SSDs take 1ms, and hard disks take 20ms. As such, you should always choose an SSD to store your operating system if you can.

### USB 3.0 Is 10 Times Faster Than 2.0

![Photo showing a USB 2.0 adapter and a USB 3.0 adapter and to prefer USB 3.0 adapter to USB 2.0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/23-photo-showing-a-usb-2-0-adapter-and-a-usb-3-0-adapter-and-to-prefer-usb-3-0-adapter-to-usb-2-0.jpg)

 USB 3.0 read/writes at 5Gbps compared to USB 2.0 which can do only 480Mbps. So, you should use a USB 3.0 to SATA adapter.

### Use the USB 3.0 Port on Your Computer

![Photo showing a USB 2.0 port and a USB 3.0 port and to prefer USB 3.0 to USB 2.0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/24-photo-showing-a-usb-2-0-port-and-a-usb-3-0-port-and-to-prefer-usb-3-0-to-usb-2-0.jpg)

 Identify the 3.0 port on your computer. It is usually blue. You can also use USB-C ports which usually are USB 3.0 or above.

## Important Things to Know About Windows 11 To Go

 Before you use Windows 11 To Go, keep in mind these important things:

* **Drives with Windows To Go will not boot as internal disks.** If you remove the SSD from the USB to SATA adapter and connect it to an internal SATA port, the PC will not boot from it.
* **The disk is portable across different computers—if they have the same configuration.** For example, if one computer has NVIDIA graphics with an already installed driver, the same disk will not boot on other hardware. In such case, you need to boot in safe mode and reset the drivers.
* **Bypassing the system requirements is not a good idea overall.** Some of the features in Windows 11 provide additional security for your computer. You may need those if the computer is at risk of cyberattacks. However, this may be a good last resort if you're worried about Windows 10's loss of support.

## Extend Your PC's Life With Windows 11 To Go

 Some say that aging hardware kills a computer. But that’s not the usual case. Chromebooks in perfect condition are getting discarded because of the lack of software updates. The same will happen with the PCs that are running Windows 10, the ones that are incompatible with Windows 11\. Bypassing the system requirements can give your computer a new lease of life.

 There is a way to bypass these requirements and install Windows 11 on any powerful computer, even if it is old. The process is quite simple as well.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-voiceover-guide-for-engaging-videography/"><u>[New] 2024 Approved Voiceover Guide for Engaging Videography</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-mastering-video-sharing-understanding-vimeo-membership-plans/"><u>[New] In 2024, Mastering Video Sharing Understanding Vimeo Membership Plans</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-2024-approved-how-asmr-can-boost-your-health-and-happiness/"><u>[Updated] 2024 Approved How ASMR Can Boost Your Health & Happiness</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-leveraging-youtube-for-dynamic-instagram-stories-for-2024/"><u>[Updated] Leveraging YouTube for Dynamic Instagram Stories for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-soundsreview-insight-for-2024/"><u>[Updated] SoundsReview Insight for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-the-ultimate-android-moba-game-series-countdown-10/"><u>[Updated] The Ultimate Android MOBA Game Series Countdown (#10)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-minmax-cpu-values-through-windows-menus/"><u>Deciphering Min/Max CPU Values Through Windows Menus</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-an-in-depth-examination-of-vivavideo-app/"><u>In 2024, An In-Depth Examination of VivaVideo App</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-check-if-your-oneplus-11-5g-is-unlocked-by-drfone-android/"><u>In 2024, How To Check if Your OnePlus 11 5G Is Unlocked</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-windows-view-overcoming-overscan-issues/"><u>Streamline Windows View: Overcoming Overscan Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/successful-execution-of-amd-195-on-your-os/"><u>Successful Execution of AMD 195 on Your OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-changing-your-home-screen-picture-on-pc/"><u>The Art of Changing Your Home Screen Picture on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/three-easy-steps-to-remove-store-app-from-win11/"><u>Three Easy Steps to Remove Store App From Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-shadowy-taskbar-snoop-in-windows-11/"><u>Unveiling the Shadowy Taskbar Snoop in Windows 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/your-2024-guide-to-the-leading-cloud-storage-champions/"><u>Your 2024 Guide to the Leading Cloud Storage Champions</u></a></li>
</ul></div>

