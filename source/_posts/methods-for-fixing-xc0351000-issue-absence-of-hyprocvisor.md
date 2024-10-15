---
title: Methods for Fixing XC0351000 Issue - Absence of Hyprocvisor
date: 2024-10-09T01:40:08.352Z
updated: 2024-10-15T03:55:11.331Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Methods for Fixing XC0351000 Issue - Absence of Hyprocvisor
excerpt: This Article Describes Methods for Fixing XC0351000 Issue - Absence of Hyprocvisor
keywords: XC0351000 Fix Methods,Hyprocvisor Recovery Steps,XC0351000 Troubleshooting Guide,Addressing XC0351000 Error,XC0351000 Issue Resolution,Hyprocvisor Activation Fixes,Correcting XC0351000 Latency
thumbnail: https://thmb.techidaily.com/18c9dd2cba19f0ecf97513cafd5088c9e4acab9c65510cdf2678db2edca6954d.jpg
---

## Methods for Fixing XC0351000 Issue - Absence of Hyprocvisor

 Windows Sandbox is a handy utility to test untrusted apps and files in a secure virtual environment. The setup process is pretty straightforward for Windows Sandbox. However, when you try to launch the app, you may encounter the "No Hypervisor was found code 0XC0351000" error.

 The error message indicates that Windows Sandbox was unable to detect Hypervisor. This can happen due to many reasons, including incorrectly configured virtual machine-related features in Windows Features.

 Follow the steps in the article below to troubleshoot this error on your Windows PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Check and Enable Virtualization Technology in BIOS

![virtualization status windows task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/virtualization-status-windows-task-manager.jpg)

 All the virtualization-based tools need hardware virtualization enabled in BIOS to work. If you haven’t configured your hardware virtualization, check if it is enabled in Task Manager. If not, you can manually enable it in BIOS to support virtualization tools.

To check the virtualization status:

1. Right-click on**Start** and open**Task Manager.**
2. In Task Manager, open the**Performance** tab.
3. Next, make sure the**CPU** tab is selected.
4. Locate the**Virtualization** section. If**Enabled** , skip to the next method.
5. If**Disabled** , follow the steps below to enable hardware virtualization on your computer.

 Now we'll cover how to enable Hardware Virtualization in BISO on an HP computer. The instructions to enable hardware virtualization may vary depending on your computer manufacturer. You can find specific instructions on your computer manufacturer's website, or check out[how to enter the BIOS in Windows 10/11](https://www.makeuseof.com/tag/enter-bios-computer/) .

1. Shut down your PC.
2. Press the**Power** button and then start pressing the**Esc** key to view the**Start menu** .
3. Press**F10** to enter**BIOS Setup.**  
![startup menu bios setup utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/startup-menu-bios-setup-utility.jpg)
4. In the**BIOS Setup Utility,** use the right-left arrow keys to locate and open the**Configuration** tab.
5. Next, use the down-up arrow keys to select**Virtualization Technology** or anything with similar terms.  
![enable hardware virtualization bios](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/enable-hardware-virtualization-bios.jpg)
6. With the option highlighted, press**Enter** and select**Enabled** from the options. Now the Virtualization Technology status will show as**Enabled** .
7. Press**F10** again to save the changes and exit BIOS.

 Wait for your computer to restart. Open Task Manager to see the Virtualization status in the CPU tab. If it says "Enabled," try to open Windows Sandbox to see if it works without the error.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484945/16446" target="_top" id="1484945">
  <img src="//a.impactradius-go.com/display-ad/16446-1484945" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484945/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Enable Virtual Machine Platform Features

 Windows Sandbox is available as an optional feature that you can install from the Windows Features dialog, and we've covered how to do this in our guide on[how to enable and set up Windows Sandbox in Windows 11](https://www.makeuseof.com/enable-set-up-windows-sandbox-windows-11/) . Similarly, you may need to enable a few additional optional features essential to run the virtualization tool successfully.

 The two optional features you need to enable are**Virtual Machine Platform** and**Windows Hypervisor Platform** . These tools enable platform support for virtual machines and provide the necessary API to run virtualization software on Windows.

To enable virtualization features:

1. Press**Win + I** to open**Settings** .
2. Type**appwiz.cpl** and click**OK** to open**Control Panel.**  
![turn windows features on off windows 11 control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-windows-featureson-off-windows-11-control-panel.jpg)
3. In the left pane, click on**Turn Windows features on or off.**  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036486/19272" target="_top" id="2036486">
  <img src="//a.impactradius-go.com/display-ad/19272-2036486" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036486/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![turn on virtual machine platform windows hypervisor platform](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-on-virtual-machine-platform-windows-hypervisor-platform.jpg)
4. In the**Windows Features** dialogue, scroll down and locate**Virtual Machine Platform** and**Windows Hypervisor Platform.**
5. Select both options and click**OK** .
6. Windows will start installing the necessary files. So, wait for the process to complete. Once done, click on**Restart Now** to restart your system and apply the changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2052063/7443" target="_top" id="2052063">
  <img src="//a.impactradius-go.com/display-ad/7443-2052063" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052063/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Set Hypervisor to Run at System Startup

 Windows Sandbox may not work if Hypervisor fails to start during system startup. To fix this issue, you can modify your Boot Configuration Data (BCD) file to launch Hypervisor automatically at system startup.

To set Hypervisor to launch at system startup:

1. Press the**Win** key and type**cmd** . Then, right-click on**Command Prompt** and select**Run as administrator.**
2. In the Command Prompt window, type the following command and press Enter:  
`BCDEDIT /Set {current} hypervisorlaunchtype auto`
3. Wait for the success message and restart your PC.
4. After the restart, open Command Prompt as administrator and run the following command:  
`bcdedit`
5. Next, scroll down to the**Hypervisorlaunchtype** entry and make sure it is set to**Auto** .
6. Try to launch Windows Sandbox and check if the No Hypervisor was found error is resolved.

 Note that with the Hypervisor set to launch at startup, virtual machines running on third-party virtualization tools such as VMWare may not work correctly.

 To disable Hypervisor at startup, type the following command in the elevated Command Prompt:

`bcdedit /set hypervisorlaunchtype off`

Once done, restart your computer to apply the changes.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896527/19272" target="_top" id="1896527">
  <img src="//a.impactradius-go.com/display-ad/19272-1896527" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896527/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Set With Your Sandbox Again

 While only available on the Pro, Enterprise, and Education editions of the Windows 10 and 11 running systems, Sandbox is an excellent lightweight virtualization solution to test unsafe files and apps on your PC.

 However, if this virtualization option is unavailable, consider using a Windows Sandbox alternative such as Sandboxie-Plus. It is free to use and works on all the editions of Windows OS.

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
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-sky-hdr-perfection-top-website-reviews/"><u>[New] In 2024, Sky HDR Perfection - Top Website Reviews</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-revolutionize-online-transmission-essential-browsers-screen-capture-vendors/"><u>[Updated] 2024 Approved Revolutionize Online Transmission Essential Browsers' Screen Capture Vendors</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-tweaking-image-previews-for-youtube-like-experience-in-twitter-videos-for-2024/"><u>[Updated] Tweaking Image Previews for YouTube-Like Experience in Twitter Videos for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/3-things-you-must-know-about-fake-snapchat-location-on-motorola-g54-5g-drfone-by-drfone-virtual-android/"><u>3 Things You Must Know about Fake Snapchat Location On Motorola G54 5G | Dr.fone</u></a></li>
<li><a href="https://os-tips.techidaily.com/alpaka-go-sling-assessment-ideal-protective-cover-tailored-for-devoted-ipad-users/"><u>Alpaka Go Sling Assessment: Ideal Protective Cover Tailored for Devoted iPad Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-looks-like-youre-stranded-xbox-app-error-in-windows-10-and-11/"><u>How to Fix the “Looks Like You’re Stranded” Xbox App Error in Windows 10 & 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-6-appsservices-to-trace-any-honor-70-lite-5g-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, Top 6 Apps/Services to Trace Any Honor 70 Lite 5G Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/procreates-parallels-on-windows-a-ranking/"><u>Procreate's Parallels on Windows: A Ranking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-pathway-out-of-windows-11-and-10s-s-constraints/"><u>The Pathway Out of Windows 11 and 10'S S Constraints</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-top-5-non-windows-solutions-to-the-windows-snipping-tool-limitation/"><u>The Top 5 Non-Windows Solutions to the Window’s Snipping Tool Limitation</u></a></li>
<li><a href="https://blog-min.techidaily.com/top-streaming-services-offering-stunning-4k-uhd-video-netflix-amazon-prime-directv-now-and-beyond/"><u>Top Streaming Services Offering Stunning 4K UHD Video: Netflix, Amazon Prime, DIRECTV NOW & Beyond</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-system-trays-with-personalized-weather-symbols-on-windows-11/"><u>Transforming System Trays with Personalized Weather Symbols on Windows 11</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-creative-cinema-for-kids-bring-your-imagination-to-life/"><u>Updated Creative Cinema for Kids Bring Your Imagination to Life</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-free-up-space-9-best-video-compression-software-for-windows-10/"><u>Updated In 2024, Free Up Space 9 Best Video Compression Software for Windows 10</u></a></li>
</ul></div>

