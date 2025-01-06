---
title: How To Configure Windows Sandbox in Win 11 Easily
date: 2025-01-02T18:52:58.990Z
updated: 2025-01-06T09:20:14.867Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How To Configure Windows Sandbox in Win 11 Easily
excerpt: This Article Describes How To Configure Windows Sandbox in Win 11 Easily
keywords: Windows Sandbox Setup,Win 11 Sandbox Guide,Easy Win 11 Sandbox,Configuring Sandbox Win 11,Simple Win 11 Sandbox,Win 11 Easy Sandboxing,Optimize Win 11 Sandbox Use
thumbnail: https://thmb.techidaily.com/eea9086dc7bf337d2bb499bc698c2b462f09146348f5ebcda0ff8ce585d15359.jpg
---

## How To Configure Windows Sandbox in Win 11 Easily

 Microsoft Windows 11 features multiple virtualization solutions out of the box. While Hyper-V is an excellent tool, Windows Sandbox is an easy alternative to Windows virtual machines. It lets you run untrusted apps in an isolated environment without the hassle of setting up a complete virtualization tool.

 Unfortunately, Windows Sandbox is not available on the Home edition of the OS. If you are running the Pro, Enterprise, and Education edition, here is how to enable and set up Windows Sandbox in Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kiW7sLvL65k?si=IHSeRFsYCrfqpn2o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Set Up Windows Sandbox in Windows 11

 Windows Sandbox is an optional feature, which means you'll have to install it from the Optional features section. You can[add and remove optional features from the Windows Features dialog](http://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) . Alternatively, you can use PowerShell or Command Prompt for a swift installation of Windows Sandbox.

 While the setup process is easier, your computer must meet some system requirements. Windows 11 Pro, Education, or Enterprise running computers with virtualization support are Windows Sandbox compatible. In most cases,[if your system can run Windows Hyper-V](https://www.makeuseof.com/windows-11-enable-hyper-v/) , it should also run Windows Sandbox.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/H2cXnI9oOvM?si=3nz2sBB124ln-83T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Enable Windows Sandbox Using the Windows Features Dialog

 You can install Windows Sandbox using the Windows Features dialog. This dialog houses most of the optional Windows features that are ready to be installed on your PC.

 Follow these steps to install Windows Sandbox using the Windows Features dialog:

1. Press**Win + R** to open**Run** .
2. Type**appwiz.cpl** and click**OK** to open**Control Panel.**
3. In the left panel, click on**Turn Windows features on or off.**  
![control panel turn windows features on or off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/control-panel-turn-windows-features-on-or-off.jpg)
4. In the**Turn Windows features on or off dialog** , scroll down and locate**Windows Sandbox.**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zmXpl6irBYk?si=BXjGpQr6PXFcqhCI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Check the**Windows Sandbox** option and click**OK** .  
![enable Windows sandbox turn windows features on or off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-Windows-sandbox-turn-windows-features-on-or-off.jpg)
6. Windows will search for the files and install the required dependencies to run Windows Sandbox scenarios. Once the changes are applied, close the Windows features dialog and restart your PC.
7. After the restart, press**Win + S** to open**Windows search.**
8. Type**sandbox** and click on**Windows Sandbox** from the search result to launch the virtualization tool.

## 3\. Install Windows Sandbox Using PowerShell

![enable windows sandbox powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-windows-sandbox-powershell.jpg)

 You can use the Enable WindowsOptionalFeature command in PowerShell to install Windows Sandbox in Windows. This method is useful if you find the sandbox option greyed out or unable to install it from the Windows Feature dialog.

To install Windows Sandbox using PowerShell:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Windows Terminal (Admin)** to open the Windows Terminal with administrative privilege. Since PowerShell is assigned as the default profile upon launch, you can execute your PowerShell cmdlets straight away in Windows Terminal.
3. In the Windows Terminal window, copy and paste the following command and press Enter:  
Enable-WindowsOptionalFeature -Online -FeatureName "Containers-DisposableClientVM" -All
4. If no error occurs, Windows will install the required files to enable Windows Sandbox.
5. Once done, press**Y** and hit**Enter** to restart your PC.
6. After the restart, you can launch Windows Sandbox from Windows Search.

## 3\. Install Windows SandBox Using Command Prompt

![enable windows sandbox command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-windows-sandbox-command-prompt.jpg)

 Deployment Image Servicing and Management (DISM) is a command-line utility that facilitates the installation of optional features using the Command Prompt. To install Windows Sandbox, you will need to use the Enable-Feature command in Command Prompt. Here's how to do it.

1. Press**Win + R** to open**Run** .
2. Type**cmd** in the**Run** dialog. Press and hold**Ctrl + Shift** and click**OK** to open Command Prompt as administrator.
3. In the Command Prompt, type the following command and press**Enter** :  
`dism /online /Enable-Feature /FeatureName: "Containers-DisposableClientVM" -All`
4. Wait for the process to complete. Once done, press**Y** and**Enter** to restart your PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lxv4NM-89CU?si=Uj5rOkhrwZ_6QIuW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Use Windows Sandbox

![Windows Sandbox Open](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Windows-Sandbox-Open.jpg)

 Now that you have Windows Sandbox installed, you can start using it to test untrusted apps in isolation. To launch the app, press**Win + S** to open**Windows Search** and type**Windows Sandbox.** Click on the app from the search result to open it.

 Upon its launch, Windows Sandbox looks like a lightweight version of your Windows machine. You can copy files from your host system or download them from the Internet using the built-in web browser. Any actions you perform in the sandbox will not affect your host system.

 Once the testing is complete, close the Sandbox and click**OK** to confirm the action. Unlike a VM, Sandbox will delete all the data (including apps and files) upon exit. So, you'll get a clean, isolated environment running the same Windows OS build as your host machine each time.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/May-pLCUkEA?si=PGlcFZAlsp3S3beI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Set Up and Use Windows Sandbox in Windows 11

 Windows Sandbox provides an excellent way to test apps and files in an isolated environment without the hassle of setting up a virtual machine. While the virtual machines have distinct advantages, Sandbox is lighter, faster, and loads a fresh copy of Windows OS each time it's run.

 Windows 11 Home users, however, have missed out on this excellent feature. But if you must use a sandbox, consider using third-party alternatives such as Sandboxie Plus and SHADE Sandbox. These alternatives offer a similar set of functionalities with no complicated setup involved.

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
<li><a href="https://screen-recording.techidaily.com/new-xiaomi-11-a-new-era-of-high-fidelity-video-recording-for-2024/"><u>[New] Xiaomi 11 A New Era of High Fidelity Video Recording for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-efficiently-recording-your-xbox-adventures/"><u>[Updated] Efficiently Recording Your Xbox Adventures</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-mastering-vimeo-recording-techniques/"><u>[Updated] In 2024, Mastering Vimeo Recording Techniques</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-navigating-tiktok-lives-as-a-virtual-attendee/"><u>[Updated] Navigating TikTok Lives as a Virtual Attendee</u></a></li>
<li><a href="https://win-wonderful.techidaily.com/comment-configurer-la-sauvegarde-repetee-ou-en-temps-reel-sur-un-ordinateur-avec-windows/"><u>Comment Configurer La Sauvegarde Répétée Ou en Temps Réel Sur Un Ordinateur Avec Windows?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/determining-active-windows-11-a-guide-with-3-methods/"><u>Determining Active Windows 11: A Guide with 3 Methods</u></a></li>
<li><a href="https://win-amazing.techidaily.com/easy-guide-to-download-and-install-epson-workforce-ds-30-driver-on-your-pc-with-windows-11-8-or-7/"><u>Easy Guide to Download and Install Epson WorkForce DS 30 Driver on Your PC with Windows 11, 8, or 7</u></a></li>
<li><a href="https://facebook.techidaily.com/examining-security-fears-in-the-world-of-facebook-games/"><u>Examining Security Fears in the World of Facebook Games</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-frp-hijacker-by-hagard-download-and-bypass-your-motorola-moto-g23-frp-locks-by-drfone-android/"><u>In 2024, FRP Hijacker by Hagard Download and Bypass your Motorola Moto G23 FRP Locks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-prime-experience-tackling-audio-subtitle-hiccups-in-windows-11/"><u>Optimize Your Prime Experience: Tackling Audio-Subtitle Hiccups in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proactive-system-care-self-update-plus-gpu-driver-change-routine/"><u>Proactive System Care: Self-Update + GPU Driver Change Routine</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-oneplus-nord-ce-3-lite-5g-stuck-on-startup-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for OnePlus Nord CE 3 Lite 5G Stuck on Startup Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-gaming-resolving-the-e84-error-in-steam/"><u>Seamless Gaming: Resolving the E84 Error in Steam</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723964487998-steep-discount-alert-8bitdos-nes-style-retro-keyboard-now-at-just-79-on-amazon-prime-day/"><u>Steep Discount Alert: 8BitDo's NES-Style Retro Keyboard Now at Just $79 on Amazon Prime Day!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-windows-11-gpo-control/"><u>Step-by-Step Guide to Windows 11 GPO Control</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-ending-others-session-in-windows-11/"><u>Steps for Ending Others' Session in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-remedies-to-win-1011-active-directory-domain-services-printer-issues/"><u>Swift Remedies to Win 10/11 Active Directory Domain Services Printer Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-memory-efficient-web-browsers-under-56-characters/"><u>Top Memory-Efficient Web Browsers Under 56 Characters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-virtual-solutions-synced-with-windows-11-hardware/"><u>Top Virtual Solutions Synced with Windows 11 Hardware</u></a></li>
</ul></div>

