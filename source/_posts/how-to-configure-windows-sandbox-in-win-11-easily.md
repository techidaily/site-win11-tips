---
title: How To Configure Windows Sandbox in Win 11 Easily
date: 2025-01-26T16:29:20.323Z
updated: 2025-02-03T01:01:18.554Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/YezPJZzPJ8Q?si=xF1t4BQHFquzvnzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fqBKCGAKHmA?si=OkoaI17nE5qNqTHj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Check the**Windows Sandbox** option and click**OK** .  
![enable Windows sandbox turn windows features on or off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-Windows-sandbox-turn-windows-features-on-or-off.jpg)
6. Windows will search for the files and install the required dependencies to run Windows Sandbox scenarios. Once the changes are applied, close the Windows features dialog and restart your PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JAkb8Bv3AU4?si=2rHwnZYTzTLieKgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6X24fPKs6AE?si=YtQy-8zy7GifgfA7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Install Windows SandBox Using Command Prompt

![enable windows sandbox command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-windows-sandbox-command-prompt.jpg)

 Deployment Image Servicing and Management (DISM) is a command-line utility that facilitates the installation of optional features using the Command Prompt. To install Windows Sandbox, you will need to use the Enable-Feature command in Command Prompt. Here's how to do it.

1. Press**Win + R** to open**Run** .
2. Type**cmd** in the**Run** dialog. Press and hold**Ctrl + Shift** and click**OK** to open Command Prompt as administrator.
3. In the Command Prompt, type the following command and press**Enter** :  
`dism /online /Enable-Feature /FeatureName: "Containers-DisposableClientVM" -All`
4. Wait for the process to complete. Once done, press**Y** and**Enter** to restart your PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UUPt2zKtJ5k?si=LLHdsFDLzVByJsKj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://instagram-clips.techidaily.com/2024-approved-trendsetters-in-instagram-ae-best-selling-template-collections/"><u>2024 Approved Trendsetters in Instagram AE Best-Selling Template Collections</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/5-best-methods-for-converting-blu-ray-discs-into-high-definition-mp4-files/"><u>5 Best Methods for Converting Blu-Ray Discs Into High-Definition MP4 Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-movecopy-tasks-to-windows-explorers-context-menu/"><u>Adding Move/Copy Tasks to Windows Explorer's Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/empower-your-windows-network-with-python-driven-transfers/"><u>Empower Your Windows Network with Python-Driven Transfers</u></a></li>
<li><a href="https://buynow-info.techidaily.com/expert-insights-on-anthropics-advanced-image-editing-suite-a-detailed-evaluation/"><u>Expert Insights on Anthropics' Advanced Image Editing Suite – A Detailed Evaluation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-windows-11-camera-app-f429f-hiccup/"><u>How to Rectify Windows 11 Camera App F429F Hiccup</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-cards-of-honor-play-8t-without-puk-codes-by-drfone-android/"><u>How To Unlock SIM Cards Of Honor Play 8T Without PUK Codes</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-top-10-fingerprint-lock-apps-to-lock-your-motorola-moto-g24-phone-by-drfone-android/"><u>In 2024, Top 10 Fingerprint Lock Apps to Lock Your Motorola Moto G24 Phone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-registry-editor-access-control-in-win11/"><u>Mastering Registry Editor Access Control in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-hyper-v-setup-process-for-windows-11-home-edition/"><u>Navigating the Hyper-V Setup Process for Windows 11 Home Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-winget-in-windows-11-environments/"><u>Reactivating Winget in Windows 11 Environments</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/solving-macbook-air-unresponsiveness-top-tips-for-quick-recovery/"><u>Solving MacBook Air Unresponsiveness – Top Tips for Quick Recovery</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/starting-off-smoothly-with-fast-forwarding-in-snapchat-for-2024/"><u>Starting Off Smoothly with Fast-Forwarding in Snapchat for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/inancial-scale-one-million-youtube-viewers-pay-for-2024/"><u>The Financial Scale One Million YouTube Viewers' Pay for 2024</u></a></li>
<li><a href="https://program-issues.techidaily.com/ultimate-guide-7-proven-methods-to-resolve-steams-black-screen-issue/"><u>Ultimate Guide: 7 Proven Methods to Resolve Steam's Black Screen Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-your-windows-11-defense-enhanced-filter-options-via-context-menu/"><u>Upgrade Your Windows 11 Defense: Enhanced Filter Options via Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-modern-standby-gets-a-bad-rap-in-windows/"><u>Why Modern Standby Gets a Bad Rap in Windows</u></a></li>
</ul></div>

