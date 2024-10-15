---
title: Guide to Fix Windows Sandbox's No Hypervisor Error
date: 2024-10-11T23:29:57.103Z
updated: 2024-10-15T08:25:56.193Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151868/7443" target="_top" id="2151868">
  <img src="//a.impactradius-go.com/display-ad/7443-2151868" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151868/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136616/26400" target="_top" id="2136616">
  <img src="//a.impactradius-go.com/display-ad/26400-2136616" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136616/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Select both options and click**OK** .
6. Windows will start installing the necessary files. So, wait for the process to complete. Once done, click on**Restart Now** to restart your system and apply the changes.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148634/16836" target="_top" id="2148634">
  <img src="//a.impactradius-go.com/display-ad/16836-2148634" border="0" alt="https://techidaily.com" width="80" height="31"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148634/16836" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2100534/7443" target="_top" id="2100534">
  <img src="//a.impactradius-go.com/display-ad/7443-2100534" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100534/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-video-files.techidaily.com/new-music-magic-for-instagram-a-guide-for-2024/"><u>[New] Music Magic for Instagram A Guide for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-expedited-srt-to-txt-conversion-2023s-efficient-method/"><u>[Updated] In 2024, Expedited SRT to TXT Conversion 2023'S Efficient Method</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-output-amplification-for-disconnected-bluetooth-devices/"><u>Enhancing Output Amplification for Disconnected Bluetooth Devices</u></a></li>
<li><a href="https://techidaily.com/how-to-update-apple-iphone-6s-to-the-latest-ios-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update Apple iPhone 6s to the Latest iOS Version? | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-80plus-catchy-cooking-channel-names-to-attract-more-audience/"><u>In 2024, 80+ Catchy Cooking Channel Names to Attract More Audience</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-the-essential-guide-to-zero-cost-webinars-on-youtube/"><u>In 2024, The Essential Guide to Zero-Cost Webinars on YouTube</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/jumpstart-global-opportunities-leading-3-linguistic-advancement-apps/"><u>Jumpstart Global Opportunities: Leading 3 Linguistic Advancement Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterclass-on-winservicesexe-in-windows-os/"><u>Masterclass on WinServices.exe in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-through-windows-avoid-fullscreen-frustrations/"><u>Navigate Through Windows: Avoid Fullscreen Frustrations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recovering-original-directory-view-in-win11/"><u>Recovering Original Directory View in Win11</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/resolving-network-not-registered-issues-on-your-samsung-galaxy-device/"><u>Resolving 'Network Not Registered' Issues on Your Samsung Galaxy Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-slide-show-creation-windows-11s-seven-step-methodology/"><u>Seamless Slide Show Creation: Windows 11'S Seven-Step Methodology</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-address-stalled-spotify-on-windows-systems/"><u>Steps to Address Stalled Spotify on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/system-rejuvenation-exploring-windows-8-restarts/"><u>System Rejuvenation: Exploring Windows' 8 Restarts</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/the-art-of-engaging-audiences-with-facebooks-split-screen-tech-for-2024/"><u>The Art of Engaging Audiences with Facebook's Split Screen Tech for 2024</u></a></li>
</ul></div>

