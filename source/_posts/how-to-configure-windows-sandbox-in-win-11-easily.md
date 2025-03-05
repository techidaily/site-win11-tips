---
title: How To Configure Windows Sandbox in Win 11 Easily
date: 2025-02-27T03:08:49.138Z
updated: 2025-03-04T19:18:56.586Z
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

## How to Set Up Windows Sandbox in Windows 11

 Windows Sandbox is an optional feature, which means you'll have to install it from the Optional features section. You can[add and remove optional features from the Windows Features dialog](http://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) . Alternatively, you can use PowerShell or Command Prompt for a swift installation of Windows Sandbox.

 While the setup process is easier, your computer must meet some system requirements. Windows 11 Pro, Education, or Enterprise running computers with virtualization support are Windows Sandbox compatible. In most cases,[if your system can run Windows Hyper-V](https://www.makeuseof.com/windows-11-enable-hyper-v/) , it should also run Windows Sandbox.

## 1\. Enable Windows Sandbox Using the Windows Features Dialog

 You can install Windows Sandbox using the Windows Features dialog. This dialog houses most of the optional Windows features that are ready to be installed on your PC.

 Follow these steps to install Windows Sandbox using the Windows Features dialog:

1. Press**Win + R** to open**Run** .
2. Type**appwiz.cpl** and click**OK** to open**Control Panel.**
3. In the left panel, click on**Turn Windows features on or off.**  
![control panel turn windows features on or off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/control-panel-turn-windows-features-on-or-off.jpg)
4. In the**Turn Windows features on or off dialog** , scroll down and locate**Windows Sandbox.**

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

## How to Use Windows Sandbox

![Windows Sandbox Open](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Windows-Sandbox-Open.jpg)

 Now that you have Windows Sandbox installed, you can start using it to test untrusted apps in isolation. To launch the app, press**Win + S** to open**Windows Search** and type**Windows Sandbox.** Click on the app from the search result to open it.

 Upon its launch, Windows Sandbox looks like a lightweight version of your Windows machine. You can copy files from your host system or download them from the Internet using the built-in web browser. Any actions you perform in the sandbox will not affect your host system.

 Once the testing is complete, close the Sandbox and click**OK** to confirm the action. Unlike a VM, Sandbox will delete all the data (including apps and files) upon exit. So, you'll get a clean, isolated environment running the same Windows OS build as your host machine each time.

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
<li><a href="https://article-tips.techidaily.com/new-2024-approved-parrot-prowess-in-bebop-an-in-depth-critique/"><u>[New] 2024 Approved Parrot Prowess in Bebop – An In-Depth Critique</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-high-definition-recording-mastering-live-footage-using-logitech-cam/"><u>[Updated] In 2024, High Definition Recording Mastering Live Footage Using Logitech Cam</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-top-12-wildlife-wonders-for-your-android-device/"><u>[Updated] In 2024, Top 12 Wildlife Wonders for Your Android Device</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-syncing-platforms-for-video-upload/"><u>[Updated] Syncing Platforms for Video Upload</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-from-iphone-images-jpeg-png-guided-conversion-to-pdfs/"><u>2024 Approved From iPhone Images (JPEG, PNG) - Guided Conversion to PDFs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-hotkeys-fastest-car-drivers-for-windows/"><u>Explore Hotkeys: Fastest Car Drivers for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-cab-structures-in-microsofts-windows-environment/"><u>Exploring CAB Structures in Microsoft's Windows Environment</u></a></li>
<li><a href="https://games-able.techidaily.com/exploring-javas-game-world-what-catches-our-eye/"><u>Exploring Java's Game World: What Catches Our Eye</u></a></li>
<li><a href="https://review-topics.techidaily.com/mov-playback-issues-on-xiaomi-redmi-12-5g-by-aiseesoft-video-converter-play-mov-on-android/"><u>MOV playback issues on Xiaomi Redmi 12 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-windows-for-heic-image-conversion/"><u>Optimizing Windows for Heic Image Conversion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-steams-file-lock-up-predicament-on-pc/"><u>Solving Steam's File Lock-Up Predicament on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-to-run-task-manager-as-admin-in-win11/"><u>Step-by-Step to Run Task Manager as Admin in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-reset-blank-login-windows-1011/"><u>Strategies to Reset Blank Login Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-browsing-safety-with-aguard-feature-on-windows-11/"><u>Streamline Your Browsing Safety with Aguard Feature on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solutions-to-common-onedrive-crashes-on-pc/"><u>Swift Solutions to Common OneDrive Crashes on PC</u></a></li>
<li><a href="https://win-help.techidaily.com/understanding-ransomware-a-comprehensive-overview-by-malwarefox/"><u>Understanding Ransomware: A Comprehensive Overview by MalwareFox</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/video-recording-titans-obs-studio-vs-fraps-face-off/"><u>Video Recording Titans OBS Studio vs Fraps Face-Off</u></a></li>
</ul></div>

