---
title: Resolving No Hypervisor Issue on Windows Sandbox
date: 2024-09-13T22:47:10.516Z
updated: 2024-09-16T23:49:29.671Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving No Hypervisor Issue on Windows Sandbox
excerpt: This Article Describes Resolving No Hypervisor Issue on Windows Sandbox
keywords: Win Sys Sandbox Fix,Hypervisor Error Solve,Windows Sandbox Troubleshoot,Overcoming Hypervisor Halt,Resolving Sandbox Issue,No VMM on WS Fix,Stop Hypervisor Fail
thumbnail: https://thmb.techidaily.com/010139d6077f90333f3025af8c182332c9900266fd1f6067fe122889069013d2.jpg
---

## Resolving No Hypervisor Issue on Windows Sandbox

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
<a href="https://wigfever.sjv.io/c/5597632/2005183/22899" target="_top" id="2005183">
  <img src="//a.impactradius-go.com/display-ad/22899-2005183" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005183/22899" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-http.techidaily.com/updated-craft-professional-text-the-best-affects-extensions-revealed/"><u>[Updated] Craft Professional Text The Best Affects Extensions Revealed</u></a></li>
<li><a href="https://hardware-help.techidaily.com/2024-ultimate-microsd-card-selection-the-best-picks-for-optimal-performance/"><u>2024 Ultimate MicroSD Card Selection: The Best Picks for Optimal Performance</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/android-unlock-code-sim-unlock-your-samsung-galaxy-a24-phone-and-remove-locked-screen-by-drfone-android/"><u>Android Unlock Code Sim Unlock Your Samsung Galaxy A24 Phone and Remove Locked Screen</u></a></li>
<li><a href="https://change-location.techidaily.com/catchemall-celebrate-national-pokemon-day-with-virtual-location-on-samsung-galaxy-f34-5g-drfone-by-drfone-virtual-android/"><u>CatchEmAll Celebrate National Pokémon Day with Virtual Location On Samsung Galaxy F34 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-not-valid-user-error-in-win11-environment/"><u>Clearing Up 'Not Valid User' Error in Win11 Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-hybrid-errors-top-5-approaches-for-hypervisorbsod/"><u>Eliminating Hybrid Errors: Top 5 Approaches for HYPERVISOR_BSOD</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/1722619314518-exploring-the-capabilities-and-performance-the-2cuative-labs-sound-blaster-zxr-review-from-2013/"><u>Exploring the Capabilities and Performance: The 2Cuative Labs Sound Blaster ZXR Review From 2013</u></a></li>
<li><a href="https://unlock-android.techidaily.com/forgot-pattern-lock-heres-how-you-can-unlock-tecno-camon-20-premier-5g-pattern-lock-screen-by-drfone-android/"><u>Forgot Pattern Lock? Heres How You Can Unlock Tecno Camon 20 Premier 5G Pattern Lock Screen</u></a></li>
<li><a href="https://hardware-help.techidaily.com/graviton4-by-aws-outperforms-amd-and-intel-next-gen-chipsets-deliver-speedy-performance-at-lower-prices/"><u>Graviton4 by AWS Outperforms AMD & Intel: Next-Gen Chipsets Deliver Speedy Performance at Lower Prices</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-fix-microphone-problems-during-zoom-calls-on-windows-1110-computers/"><u>How to Fix Microphone Problems During Zoom Calls on Windows 11/10 Computers</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-office-activation-roadblocks/"><u>Overcoming Windows Office Activation Roadblocks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-lost-volume-controls-post-windows-update/"><u>Regaining Lost Volume Controls Post Windows Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reignite-file-explorer-functionality-for-windows-11/"><u>Reignite File Explorer Functionality for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-window11s-error-msresourceapptext/"><u>Resolving Window11's Error: MsResource/AppText</u></a></li>
</ul></div>

