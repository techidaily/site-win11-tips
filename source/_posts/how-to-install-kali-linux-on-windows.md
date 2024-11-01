---
title: How to Install Kali Linux on Windows
date: 2024-10-30T16:02:20.396Z
updated: 2024-11-01T17:25:17.273Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Install Kali Linux on Windows
excerpt: This Article Describes How to Install Kali Linux on Windows
keywords: Kali Linux Setup Guide,Windows Kali Installation,Installing Kali Linux,Kali Linux Windows,Kali Linux for PCs,Setting up Kali on Windows,Windows Kali OS
thumbnail: https://thmb.techidaily.com/877cc6ce606cb4f4b4e6d66d093a7f03e00e14887d19a1aafa40b745d8b4ce71.jpg
---

## How to Install Kali Linux on Windows

 Kali Linux is the primary Debian-based Linux distribution used for information security purposes such as security research, penetration testing, password cracking, and more. It is mainly used by white hat or ethical hackers to test the integrity of a system or a network.

 If you cannot install Kali Linux on your PC directly, you can easily install it on Windows through a virtual machine. Read on as we guide you on installing Kali Linux on a Windows PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Install a Virtual Machine on Windows

 The first step to installing Kali Linux is downloading and setting up a virtual machine on your Windows PC. We recommend using Oracle VM VirtualBox as it’s reliable, free to use, and offers very high performance. We also compared[VirtualBox vs. VMWare Player](http://www.makeuseof.com/tag/best-virtual-machine-windows/) if you'd like more information.

To install VM VirtualBox:

1. Download the**Windows hosts** binary setup from the[official VirtualBox site](https://www.virtualbox.org/wiki/Downloads) .  
![download virtual box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/download-virtual-box.jpg)
2. Once the download is complete, launch the VirtualBox installation setup and confirm administrator access if prompted.
3. Go through the installation wizard and click on**Finish** to complete the process.
4. You can optionally restart your PC to ensure that VirtualBox is installed correctly.

<!-- affiliate ads begin -->
<span id="1484963">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1484963.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1484963">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1484963.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1484963%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1484963/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Download the Kali Linux Virtual Machine

 Once we have installed a virtual machine, we need to download the Kali Linux VM image. The VM image will allow you to run the Kali Linux operating system on your current Windows PC.

 There are two main ways to install Kali Linux on a virtual machine: download and use a pre-built VM image or install Kali via an ISO image. Since it is much quicker to import a pre-built VM rather than installing Kali from scratch, we will focus on using the pre-made virtual machine image for this guide. If you’re still interested in installing Kali Linux via ISO, we will overview that at the end of the article.

To download the Kali Linux VM image:

1. Head to the[official Kali Linux website](https://www.kali.org/get-kali/#kali-virtual-machines) to download the pre-built VM image.  
![kali vm download](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/kali-download.jpg)
2. Since we have installed VirtualBox, we will download the VirtualBox image.

3. Confirm whether your PC is 32-bit architecture or 64-bit, and download the stable version (not the weekly version).
4. Extract the contents of the downloaded file, and you may need to install the[7z app](https://www.7-zip.org/download.html) to complete the extraction process.
5. We’re now ready to import Kali into our VirtualBox.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/999558/11832" target="_top" id="999558">
  <img src="//a.impactradius-go.com/display-ad/11832-999558" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/999558/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Import Kali Linux VM on Windows

 Now that our VirtualBox and Kali Linux VM image is ready, we can import it into our VM. Here’s how you can import the pre-installed Kali Linux image into Oracle VM VirtualBox:

1. Search for**Oracle VM Virtual** box in the**Start** menu, and launch the Best match.
2. Click on the green plus-icon labeled**Add** .  
![import kali virtualbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/import-kali.jpg)
3. Navigate to the folder where you extracted the Kali Linux image (we’re looking for a .vbox file).  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135372/19272" target="_top" id="2135372">
  <img src="//a.impactradius-go.com/display-ad/19272-2135372" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135372/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![import kali linux](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/import-kali-2.jpg)
4. Select the**.vbox** file and click on**Open** .

5. Once the VM is loaded, you will see it appear in VirtualBox.
6. Click on the green**Start** icon to fire up Kali Linux.  
![launch kali on virtualbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/launch-kali.jpg)
7. You can log in using the default**kali** user profile using the password**kali** .

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134240/18498" target="_top" id="2134240">
  <img src="//a.impactradius-go.com/display-ad/18498-2134240" border="0" alt="https://techidaily.com" width="540" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134240/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Download the Kali Linux ISO

 If you would instead use the official ISO to install Kali Linux, you can download it from the[official Kali website](https://www.kali.org/) . Once you’ve downloaded the ISO, mount it within VirtualBox and start the virtual machine. After completing the Kali installation steps within VirtualBox, you will successfully install Kali Linux on your Windows.

## Use Kali Linux on Windows

 You can easily install Kali Linux within your Windows PC thanks to virtual machines. We recommend you use the pre-built VM image and skip through the grunty installation process and jump right into Kali Linux. As one of the most secure and popular Linux distributions, Kali Linux is a very useful tool in the world of information security.

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
<li><a href="https://youtube-sure.techidaily.com/024-approved-step-by-step-backdrop-blurring-techniques-on-youtube-videos/"><u>[New] 2024 Approved Step-by-Step Backdrop Blurring Techniques on YouTube Videos</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-accelerate-your-metaverse-journey-with-7-must-have-devices/"><u>[New] Accelerate Your Metaverse Journey with 7 Must-Have Devices</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-superior-audio-modification-software-with-enchanting-features/"><u>[New] Superior Audio Modification Software with Enchanting Features</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-the-compreenasional-path-to-post-perfection-instagram-video-upload-from-pcmac/"><u>[Updated] 2024 Approved The Compreenasional Path to Post-Perfection Instagram Video Upload From PC/Mac</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-high-fidelity-performance-desktops/"><u>[Updated] High Fidelity Performance Desktops</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-restart-oppo-find-x7-ultra-without-power-button-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Restart Oppo Find X7 Ultra Without Power Button | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-guide-to-fix-windows-11-media-issues/"><u>Comprehensive Guide to Fix Windows 11 Media Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-using-github-desktop-in-windows-step-by-step-guide/"><u>Efficiently Using GitHub Desktop in Windows: Step-by-Step Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/experience-cutting-edge-tv-without-breaking-the-bank-with-the-antolink-at-127-a-sophisticated-and-efficient-choice/"><u>Experience Cutting Edge TV Without Breaking the Bank with the Antolink AT-127 - A Sophisticated and Efficient Choice</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-there-are-no-more-files-error-on-windows-11-and-11/"><u>How to Fix the “There Are No More Files” Error on Windows 11 & 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-5-best-route-generator-apps-you-should-try-on-infinix-gt-10-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Best Route Generator Apps You Should Try On Infinix GT 10 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-wsl-upgrades-in-new-windows-environments/"><u>Navigating WSL Upgrades in New Windows Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-obstacles-in-onedrive-folder-integration-on-windows/"><u>Overcoming Obstacles in OneDrive Folder Integration on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-leftright-earheadphone-audio-issues-in-windows/"><u>Solving Left/Right Earheadphone Audio Issues in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-untapped-potential-within-windows-11s-offerings/"><u>The Untapped Potential Within Windows 11'S Offerings</u></a></li>
<li><a href="https://some-skills.techidaily.com/top-10-mobile-vr-headsets-for-2024/"><u>Top 10 Mobile VR Headsets for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-desktop-with-customizable-animated-clock-themed-screensaver-creation-tools/"><u>Transform Your Desktop with Customizable, Animated Clock-Themed Screensaver Creation Tools</u></a></li>
</ul></div>

