---
title: Guidelines to Address Hypervisor Absence in Sandbox
date: 2024-10-15T18:21:39.122Z
updated: 2024-10-20T17:48:33.223Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guidelines to Address Hypervisor Absence in Sandbox
excerpt: This Article Describes Guidelines to Address Hypervisor Absence in Sandbox
keywords: Virt-Sandbox Security,Hyper-Vir Deficiency,Absentee VM Safeguard,Sandbox Hypervoid Guide,SANDBOX Virtual Gap,Hostless Hypervisor Fix,Secure Sandbox NoHyper
thumbnail: https://thmb.techidaily.com/1da8846cbd836d9712f7b59a73630f863ec9ad2fa528ea4ddf23335f3fc8b9a6.png
---

## Guidelines to Address Hypervisor Absence in Sandbox

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006946/19272" target="_top" id="2006946">
  <img src="//a.impactradius-go.com/display-ad/19272-2006946" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006946/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![turn on virtual machine platform windows hypervisor platform](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-on-virtual-machine-platform-windows-hypervisor-platform.jpg)
4. In the**Windows Features** dialogue, scroll down and locate**Virtual Machine Platform** and**Windows Hypervisor Platform.**

<!-- affiliate ads begin -->
<span id="1938141">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938141.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938141">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938141.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938141%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938141/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Select both options and click**OK** .
6. Windows will start installing the necessary files. So, wait for the process to complete. Once done, click on**Restart Now** to restart your system and apply the changes.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135373/19272" target="_top" id="2135373">
  <img src="//a.impactradius-go.com/display-ad/19272-2135373" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135373/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2144272/7443" target="_top" id="2144272">
  <img src="//a.impactradius-go.com/display-ad/7443-2144272" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144272/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-redirecting-noise-free-tweets-back-to-audio/"><u>[New] 2024 Approved Redirecting Noise-Free Tweets Back to Audio</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-step-by-step-enabling-screen-capture-on-macos/"><u>[New] 2024 Approved Step-by-Step Enabling Screen Capture on MacOS</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-easy-steps-to-record-your-vlc-videos-effectively/"><u>[Updated] Easy Steps to Record Your VLC Videos Effectively</u></a></li>
<li><a href="https://techtrends.techidaily.com/can-i-swim-with-my-data-intact-understanding-iphone-15-pro-maxs-water-protection/"><u>Can I Swim With My Data Intact? Understanding iPhone 15 Pro Max's Water Protection.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-cc-errors-on-the-latest-windows-os/"><u>Demystifying CC Errors on the Latest Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-you-through-fixed-windows-character-mapping-glitches/"><u>Guiding You Through Fixed Windows Character Mapping Glitches</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/imagesegment-scrutiny-review-for-2024/"><u>ImageSegment Scrutiny Review for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-oppo-find-x6-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Snapchat Location Spoofer to Protect Your Privacy On Oppo Find X6? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-the-ultimate-path-to-link-integration-on-instagrams-social-stage/"><u>In 2024, The Ultimate Path to Link Integration on Instagram's Social Stage</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-exploring-vn-video-editor-on-pc-a-brief-look/"><u>New 2024 Approved Exploring VN Video Editor on PC A Brief Look</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-trick-to-elevate-your-account-type/"><u>Quick Trick to Elevate Your Account Type</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reconnecting-microphone-and-xbox-app-on-windows-1011/"><u>Reconnecting Microphone and Xbox App on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shortcut-to-resolving-lengthy-gpsvc-loops/"><u>Shortcut to Resolving Lengthy GPSVC Loops</u></a></li>
<li><a href="https://win-blog.techidaily.com/startup-hiccups-for-atomic-heart-gamers-identifying-problems-and-implementing-solutions/"><u>Startup Hiccups for Atomic Heart Gamers: Identifying Problems & Implementing Solutions</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/step-by-step-guide-adding-the-fetch-addon-to-your-kodi-nexus-and-matrix-devices/"><u>Step-by-Step Guide: Adding the Fetch Addon to Your Kodi Nexus & Matrix Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-resolving-nvidia-disp-not-showed-problems/"><u>Strategies for Resolving Nvidia Disp Not Showed Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-screen-separation-problems/"><u>Unblocking Screen Separation Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-winrm-the-essential-recovery-routes/"><u>Unlocking WinRM: The Essential Recovery Routes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-your-visual-display-ideal-5-apps-for-personalized-time-themed-windows-screensavers/"><u>Upgrade Your Visual Display: Ideal 5 Apps for Personalized Time-Themed Windows Screensavers</u></a></li>
</ul></div>

