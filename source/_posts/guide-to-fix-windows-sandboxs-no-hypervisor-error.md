---
title: Guide to Fix Windows Sandbox's No Hypervisor Error
date: 2024-09-14T22:22:05.963Z
updated: 2024-09-17T08:02:32.113Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Fix Windows Sandbox's No Hypervisor Error
excerpt: This Article Describes Guide to Fix Windows Sandbox's No Hypervisor Error
keywords: Windows Sandbox Fix Guide,Hypervisor Error Solution,Solve No Hypervisor Issue,Windows Sandbox Troubleshoot,Fix Sandbox Error,Windows NoHyperfix Guide,Windows Sandbox Recovery Steps
thumbnail: https://thmb.techidaily.com/c8cdb9a666b994c5df18bf9fb906f435b3e886e46b814d7626bddc0615133ba1.jpg
---

## Guide to Fix Windows Sandbox's No Hypervisor Error

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

## 2\. Enable Virtual Machine Platform Features

 Windows Sandbox is available as an optional feature that you can install from the Windows Features dialog, and we've covered how to do this in our guide on[how to enable and set up Windows Sandbox in Windows 11](https://www.makeuseof.com/enable-set-up-windows-sandbox-windows-11/) . Similarly, you may need to enable a few additional optional features essential to run the virtualization tool successfully.

 The two optional features you need to enable are**Virtual Machine Platform** and**Windows Hypervisor Platform** . These tools enable platform support for virtual machines and provide the necessary API to run virtualization software on Windows.

To enable virtualization features:

1. Press**Win + I** to open**Settings** .
2. Type**appwiz.cpl** and click**OK** to open**Control Panel.**  
![turn windows features on off windows 11 control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-windows-featureson-off-windows-11-control-panel.jpg)
3. In the left pane, click on**Turn Windows features on or off.**  
![turn on virtual machine platform windows hypervisor platform](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-on-virtual-machine-platform-windows-hypervisor-platform.jpg)
4. In the**Windows Features** dialogue, scroll down and locate**Virtual Machine Platform** and**Windows Hypervisor Platform.**
5. Select both options and click**OK** .
6. Windows will start installing the necessary files. So, wait for the process to complete. Once done, click on**Restart Now** to restart your system and apply the changes.

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
<a href="https://bluettius.sjv.io/c/5597632/2139109/17108" target="_top" id="2139109">
  <img src="//a.impactradius-go.com/display-ad/17108-2139109" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139109/17108" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-footage.techidaily.com/updated-how-to-convert-your-videos-into-cash-streams-youtubes-2024-strategy/"><u>[Updated] How to Convert Your Videos Into Cash Streams - Youtube's 2024 Strategy</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-prime-websites-boosting-youtube-video-popularity/"><u>2024 Approved Prime Websites Boosting YouTube Video Popularity</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/acquire-clear-articulation-in-russian-language/"><u>Acquire Clear Articulation in Russian Language</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-windows-vmfreeze-ups-vmware-guide/"><u>Clearing Up Windows VMfreeze-Ups: VMware Guide</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/does-motorola-g24-power-support-avchd-video-by-aiseesoft-video-converter-play-mts-on-android/"><u>Does Motorola G24 Power support AVCHD video?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-pcs-gaming-potential-with-advanced-amd-radeon/"><u>Elevate Your PC's Gaming Potential With Advanced AMD Radeon</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enablingdisabling-content-filter-on-modern-windows/"><u>Enabling/Disabling Content Filter on Modern Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-quicken-slow-excel-processes-on-windows-machines/"><u>How to Quicken Slow Excel Processes on Windows Machines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-recover-lost-pin-on-windows-11-amidst-errors/"><u>How To Recover Lost PIN on Windows 11 Amidst Errors</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-samsung-galaxy-a54-5g-location-by-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Samsung Galaxy A54 5G Location by Number | Dr.fone</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/mars-lander-city-building-game-where-construction-meets-entertaining-gusts/"><u>Mars Lander City-Building Game: Where Construction Meets Entertaining Gusts!</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/mastering-the-basics-of-lg-channels-for-tech-enthusiasts/"><u>Mastering the Basics of LG Channels for Tech Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-to-open-disk-space-on-windows-1011/"><u>Step-by-Step to Open Disk Space on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-playtime-fixing-minecraft-exit-failures/"><u>Streamline Playtime: Fixing Minecraft Exit Failures</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-ultimate-guide-to-iphone-hdr-mastery-for-2024/"><u>The Ultimate Guide to iPhone HDR Mastery for 2024</u></a></li>
</ul></div>

