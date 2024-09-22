---
title: "Eliminating 0xC0351000 Error: Windows Sandbox without Hypervisor"
date: 2024-09-19T22:55:36.030Z
updated: 2024-09-21T20:14:31.361Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Eliminating 0xC0351000 Error: Windows Sandbox without Hypervisor"
excerpt: "This Article Describes Eliminating 0xC0351000 Error: Windows Sandbox without Hypervisor"
keywords: C0351000 Fix,Windows Sandbox Error,Hybrid VM Solution,Zeroing Hex Flaw,Sandbox Bug Resolution,Hypervisor-Free Boot,WinSys Secure Run
thumbnail: https://thmb.techidaily.com/b5e9ddde4e68e5c468b12c2fce264f22eb978dc955e335250b1f4d060c7be8f8.jpg
---

## Eliminating 0xC0351000 Error: Windows Sandbox without Hypervisor

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
<a href="https://aligracehair.sjv.io/c/5597632/2135394/19272" target="_top" id="2135394">
  <img src="//a.impactradius-go.com/display-ad/19272-2135394" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135394/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://android-location.techidaily.com/9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-xiaomi-redmi-a2-drfone-by-drfone-virtual/"><u>9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Xiaomi Redmi A2 | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/best-in-class-premium-screenshots-and-recorders/"><u>Best in Class Premium Screenshots & Recorders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fastest-and-friendliest-torrents-on-windows-our-picks/"><u>Fastest and Friendliest Torrents on Windows: Our Picks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harness-windows-power-to-maximize-android-studio-efficiency/"><u>Harness Windows Power to Maximize Android Studio Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-configure-microsoft-word-to-always-open-email-attachments-in-reading-view-on-windows/"><u>How to Configure Microsoft Word to Always Open Email Attachments in Reading View on Windows</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-from-poco-c55-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock from Poco C55 Devices</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-delete-icloud-account-with-or-without-password-from-your-apple-iphone-14-pluswindowsmac-by-drfone-ios/"><u>In 2024, How to Delete iCloud Account with or without Password from your Apple iPhone 14 Plus/Windows/Mac</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-11-free-apps-to-check-imei-on-vivo-y200-phones-by-drfone-android/"><u>In 2024, Top 11 Free Apps to Check IMEI on Vivo Y200 Phones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mend-tackle-non-functional-keys-on-windows-11-pc/"><u>Mend: Tackle Non-Functional Keys on Windows 11 PC</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/offline-replay-select-playlist-extractors-reviewed-for-2024/"><u>Offline Replay Select Playlist Extractors Reviewed for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-event-viewer-on-windows-11-systems/"><u>Reinstating Event Viewer on Windows 11 Systems</u></a></li>
<li><a href="https://android-frp.techidaily.com/ultimate-guide-from-oppo-reno-11-5g-frp-bypass-by-drfone-android/"><u>Ultimate Guide from Oppo Reno 11 5G FRP Bypass</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ultimate-guide-to-catch-the-regional-located-pokemon-for-motorola-moto-g14-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Catch the Regional-Located Pokemon For Motorola Moto G14 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-unlocking-hidden-powers-in-commands/"><u>Windows 11: Unlocking Hidden Powers in Commands</u></a></li>
</ul></div>

