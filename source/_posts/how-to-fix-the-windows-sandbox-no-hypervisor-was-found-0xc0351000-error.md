---
title: How to Fix the Windows Sandbox No Hypervisor Was Found 0XC0351000 Error
date: 2025-02-28T18:28:03.967Z
updated: 2025-03-04T17:56:56.183Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the Windows Sandbox No Hypervisor Was Found 0XC0351000 Error
excerpt: This Article Describes How to Fix the Windows Sandbox No Hypervisor Was Found 0XC0351000 Error
keywords: Windows Sandbox Error 0XC0351000,Fixing Windows Sandbox Hypervisor Missing,Resolve Windows Sandbox No Hypervisor,Windows Sandbox ZeroError,Troubleshoot Windows Sandbox Failure,Windows Sandbox Hyperlink Issue,Curing 0XC0351000 Error in Sandbox
thumbnail: https://thmb.techidaily.com/14af88c4727edfc68754682f8d9e5a16b4632ead51b56f451896cf5d83dd52e4.jpg
---

## How to Fix the Windows Sandbox No Hypervisor Was Found 0XC0351000 Error

 Windows Sandbox is a handy utility to test untrusted apps and files in a secure virtual environment. The setup process is pretty straightforward for Windows Sandbox. However, when you try to launch the app, you may encounter the "No Hypervisor was found code 0XC0351000" error.

 The error message indicates that Windows Sandbox was unable to detect Hypervisor. This can happen due to many reasons, including incorrectly configured virtual machine-related features in Windows Features.

 Follow the steps in the article below to troubleshoot this error on your Windows PC.

## 1\. Check and Enable Virtualization Technology in BIOS
![virtualization status windows task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/virtualization-status-windows-task-manager.jpg)

 All the virtualization-based tools need hardware virtualization enabled in BIOS to work. If you haven’t configured your hardware virtualization, check if it is enabled in Task Manager. If not, you can manually enable it in BIOS to support virtualization tools.

To check the virtualization status:

1. Right-click on**Start** and open**Task Manager.**
2. In Task Manager, open the**Performance** tab.
3. Next, make sure the**CPU** tab is selected.
4. Locate the**Virtualization** section. If**Enabled** , skip to the next method.
5. If**Disabled** , follow the steps below to enable hardware virtualization on your computer.

 Now we'll cover how to enable Hardware Virtualization in BISO on an HP computer. The instructions to enable hardware virtualization may vary depending on your computer manufacturer. You can find specific instructions on your computer manufacturer's website, or check out [how to enter the BIOS in Windows 10/11](https://www.makeuseof.com/tag/enter-bios-computer/) .

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

 Windows Sandbox is available as an optional feature that you can install from the Windows Features dialog, and we've covered how to do this in our guide on [how to enable and set up Windows Sandbox in Windows 11](https://www.makeuseof.com/enable-set-up-windows-sandbox-windows-11/) . Similarly, you may need to enable a few additional optional features essential to run the virtualization tool successfully.

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
<li><a href="https://fox-info.techidaily.com/new-2024-approved-iphones-ultimate-podcast-downloading-manual/"><u>[New] 2024 Approved IPhone's Ultimate Podcast Downloading Manual</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-2024-approved-navigating-like-a-pro-with-telegram-web/"><u>[Updated] 2024 Approved Navigating Like a Pro with Telegram Web</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-prime-landscapes-for-streaming-success/"><u>2024 Approved Prime Landscapes for Streaming Success</u></a></li>
<li><a href="https://driver-install.techidaily.com/asus-drivers-download-and-install-for-windows/"><u>ASUS Drivers Download & Install for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/converti-gif-a-formato-flv-free-online-con-movavi/"><u>Converti GIF a Formato FLV Free Online Con Movavi</u></a></li>
<li><a href="https://fox-http.techidaily.com/earn-big-with-little-experience-discover-the-top-13-reddit-money-ways-for-2024/"><u>Earn Big with Little Experience - Discover the Top 13 Reddit Money Ways for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gratis-omzettingen-van-ai-fysische-architecturen-online-movavi/"><u>Gratis Omzettingen Van AI-Fysische Architecturen Online - Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guia-paso-a-paso-como-eliminar-y-recortar-archivos-de-video-mp4-sin-coste-alguno-desde-tu-computadora-o-servicio-online/"><u>Guía Paso a Paso: Cómo Eliminar Y Recortar Archivos De Video MP4 Sin Coste Alguno Desde Tu Computadora O Servicio Online</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-a-nubia-z50s-pro-phone-that-is-locked-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset a Nubia Z50S Pro Phone That Is Locked | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-proven-ways-in-how-to-hide-location-on-life360-for-honor-90-lite-drfone-by-drfone-virtual-android/"><u>In 2024, Proven Ways in How To Hide Location on Life360 For Honor 90 Lite | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1726218758115-mp3-movavi/"><u>MP3形式変換できる動画コンバーター - Movavi：オンライン・無料サービス</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-free-to-download-top-rated-3d-animation-apps-for-mobile-devices-for-2024/"><u>New Free to Download Top-Rated 3D Animation Apps for Mobile Devices for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-secretly-capturing-zoom-sessions-no-need-for-approvals/"><u>Quick Guide to Secretly Capturing Zoom Sessions – No Need for Approvals</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-2024-approved-split-mkv-videos-with-ease-top-10-free-software-options/"><u>Updated 2024 Approved Split MKV Videos with Ease Top 10 Free Software Options</u></a></li>
</ul></div>

