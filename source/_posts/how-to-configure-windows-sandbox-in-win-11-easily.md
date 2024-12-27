---
title: How To Configure Windows Sandbox in Win 11 Easily
date: 2024-12-22T17:29:05.307Z
updated: 2024-12-27T17:55:53.425Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/xIP8ktrmOdg?si=zRnjbGzM6PDx2jCq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Check the**Windows Sandbox** option and click**OK** .  
![enable Windows sandbox turn windows features on or off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-Windows-sandbox-turn-windows-features-on-or-off.jpg)
6. Windows will search for the files and install the required dependencies to run Windows Sandbox scenarios. Once the changes are applied, close the Windows features dialog and restart your PC.
7. After the restart, press**Win + S** to open**Windows search.**
8. Type**sandbox** and click on**Windows Sandbox** from the search result to launch the virtualization tool.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_7AYCS7zBU0?si=7R9oIpE4hyEbtk3x" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/RCYs8keh-Vs?si=uDC28-9yh-k6HLj4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Use Windows Sandbox

![Windows Sandbox Open](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Windows-Sandbox-Open.jpg)

 Now that you have Windows Sandbox installed, you can start using it to test untrusted apps in isolation. To launch the app, press**Win + S** to open**Windows Search** and type**Windows Sandbox.** Click on the app from the search result to open it.

 Upon its launch, Windows Sandbox looks like a lightweight version of your Windows machine. You can copy files from your host system or download them from the Internet using the built-in web browser. Any actions you perform in the sandbox will not affect your host system.

 Once the testing is complete, close the Sandbox and click**OK** to confirm the action. Unlike a VM, Sandbox will delete all the data (including apps and files) upon exit. So, you'll get a clean, isolated environment running the same Windows OS build as your host machine each time.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/793ViIxl4tI?si=DDBkjPlPX5bZ-f1Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-irecorder-pro-in-depth-analysis/"><u>[New] 2024 Approved IRecorder Pro In-Depth Analysis</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-in-2024-mastering-the-art-of-monitoring-loved-comments-on-youtube/"><u>[New] In 2024, Mastering the Art of Monitoring Loved Comments on YouTube</u></a></li>
<li><a href="https://youtube-data.techidaily.com/nlock-your-video-soundtrack-4-cost-effective-wav-extractors/"><u>[New] Unlock Your Video Soundtrack 4 Cost-Effective WAV Extractors</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-innovative-approaches-to-keeping-your-snaps-connected/"><u>[Updated] 2024 Approved Innovative Approaches to Keeping Your Snaps Connected</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-leading-brands-offering-the-best-steadicams-for-dslr-users-for-2024/"><u>[Updated] Leading Brands Offering the Best Steadicams for DSLR Users for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-complete-guide-to-vr-ready-space-setup/"><u>2024 Approved The Complete Guide to VR-Ready Space Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/chromes-unwanted-tab-behavior-stop-and-reverse/"><u>Chrome's Unwanted Tab Behavior: Stop and Reverse</u></a></li>
<li><a href="https://fox-that.techidaily.com/discover-effective-ways-to-retrieve-disappeared-app-icons-on-ios-devices/"><u>Discover Effective Ways to Retrieve Disappeared App Icons on iOS Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-muting-pc-sound-boosting-options/"><u>Guide to Muting PC Sound Boosting Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-restore-a-missing-windows-update-service-on-windows/"><u>How to Restore a Missing Windows Update Service on Windows</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-open-minds-open-tech-easeus-report/"><u>In 2024, Open Minds, Open Tech - EaseUS Report</u></a></li>
<li><a href="https://win11-tips.techidaily.com/inside-the-windows-engine-crafting-and-deciphering-system-data/"><u>Inside the Windows Engine: Crafting & Deciphering System Data</u></a></li>
<li><a href="https://extra-support.techidaily.com/mastering-googles-text-conversion-service-a-detailed-walkthrough-for-2024/"><u>Mastering Google's Text Conversion Service A Detailed Walkthrough for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/past-perspectives-present-7-features-from-older-windows-versions/"><u>Past Perspectives Present: 7 Features From Older Windows Versions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-time-travel-reimagining-windows-11-as-98/"><u>Tech Time Travel: Reimagining Windows 11 as 98</u></a></li>
<li><a href="https://games-able.techidaily.com/the-hidden-advantages-of-turning-off-console/"><u>The Hidden Advantages of Turning Off Console</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-esd-data-into-linuxwindows-iso-formats/"><u>Transitioning ESD Data Into Linux/Windows ISO Formats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-discontent-in-windows-11-upgrades/"><u>Unveiling the Discontent in Windows 11 Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winrar-archive-success-nine-ways-to-prevent-checksum-errors/"><u>WinRAR Archive Success: Nine Ways to Prevent Checksum Errors</u></a></li>
</ul></div>

