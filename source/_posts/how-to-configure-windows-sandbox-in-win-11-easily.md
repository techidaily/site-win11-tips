---
title: How To Configure Windows Sandbox in Win 11 Easily
date: 2025-01-18T23:32:58.354Z
updated: 2025-01-24T23:38:01.478Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LBCobAYzzcc?si=J3eSTQ3AdyxWAjGo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YezPJZzPJ8Q?si=xF1t4BQHFquzvnzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Install Windows SandBox Using Command Prompt

![enable windows sandbox command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-windows-sandbox-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PKZUYice-ws?si=L8iMa9T3h7TMSWdQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Deployment Image Servicing and Management (DISM) is a command-line utility that facilitates the installation of optional features using the Command Prompt. To install Windows Sandbox, you will need to use the Enable-Feature command in Command Prompt. Here's how to do it.

1. Press**Win + R** to open**Run** .
2. Type**cmd** in the**Run** dialog. Press and hold**Ctrl + Shift** and click**OK** to open Command Prompt as administrator.
3. In the Command Prompt, type the following command and press**Enter** :  
`dism /online /Enable-Feature /FeatureName: "Containers-DisposableClientVM" -All`
4. Wait for the process to complete. Once done, press**Y** and**Enter** to restart your PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X18Dq7rV-xI?si=twFfXIPD0TFmC5EM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Use Windows Sandbox

![Windows Sandbox Open](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Windows-Sandbox-Open.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/grbt-5VvbuI?si=qnoirlmljslpqcQj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-friendly.techidaily.com/new-top-11-add-ons-for-the-dji-phantom-4-masterclass-for-2024/"><u>[New] Top 11 Add-Ons for the DJI Phantom 4 Masterclass for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-efficient-setup-adding-snapchat-to-your-mac/"><u>[Updated] 2024 Approved Efficient Setup Adding Snapchat to Your Mac</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-changing-gender-representation-in-social-media-images-for-2024/"><u>[Updated] Changing Gender Representation in Social Media Images for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-mastering-youtubes-comment-analysis/"><u>2024 Approved Mastering YouTube's Comment Analysis</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/boost-your-websites-conversion-with-advanced-cookiebot-features/"><u>Boost Your Website's Conversion with Advanced Cookiebot Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-windows-photovideo-save-issues/"><u>Clearing Up Windows Photo/Video Save Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decrypting-win11-error-0xa00f4289-on-webcam/"><u>Decrypting Win11 Error 0xA00F4289 on Webcam</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/elevate-editing-expertise-adopt-movie-maker-in-windows-11/"><u>Elevate Editing Expertise Adopt Movie Maker in Windows 11</u></a></li>
<li><a href="https://program-issues.techidaily.com/fixing-a-non-launching-city-skylines-2-expert-tips-and-tricks/"><u>Fixing a Non-Launching City Skylines 2 - Expert Tips and Tricks</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-sharefake-location-on-whatsapp-for-tecno-spark-10-4g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Share/Fake Location on WhatsApp for Tecno Spark 10 4G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-error-resolution-end-too-many-requests-on-windows-platforms/"><u>Mastering Error Resolution: End Too Many Requests on Windows Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrect-your-usb-wi-fi-effective-fixes-for-microsoft-users/"><u>Resurrect Your USB Wi-Fi – Effective Fixes for Microsoft Users</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723862757242-score-big-win-on-tech-top-choice-dell-s3222dgm-gaming-screen-hits-record-low-only-229/"><u>Score Big Win on Tech: Top Choice Dell S3222DGM Gaming Screen Hits Record Low - Only $229</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stabilize-win11s-file-explorer-with-these-fixes/"><u>Stabilize Win11's File Explorer With These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-overcoming-unauthorized-app-restriction/"><u>Strategies for Overcoming Unauthorized App Restriction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-media-top-5-cost-free-windows-cutters/"><u>Streamline Your Media: Top 5 Cost-Free Windows Cutters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/subtletys-secret-invisible-settings-and-buttons/"><u>Subtlety's Secret: Invisible Settings and Buttons</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/webcam-recorder-reviews-unlocking-your-video-potential-for-2024/"><u>Webcam Recorder Reviews - Unlocking Your Video Potential for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-puzzle-solve-the-vanishing-image-problem/"><u>Win 11 Puzzle: Solve the Vanishing Image Problem</u></a></li>
</ul></div>

