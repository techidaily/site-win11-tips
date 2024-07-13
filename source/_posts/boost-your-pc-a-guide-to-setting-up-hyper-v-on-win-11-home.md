---
title: "Boost Your PC: A Guide to Setting Up Hyper-V on Win 11 Home"
date: 2024-07-12T18:06:58.299Z
updated: 2024-07-13T18:06:58.299Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Boost Your PC: A Guide to Setting Up Hyper-V on Win 11 Home"
excerpt: "This Article Describes Boost Your PC: A Guide to Setting Up Hyper-V on Win 11 Home"
keywords: Win 11 Hyper-V Guide,Setup Hyper-V Win 11,Hyper-V Installation Win,Win 11 Virtualization,Boost PC Hyper-V Win 11,Hyper-V Windows 11 Tips,Win 11 Virtual Setup Guide
thumbnail: https://thmb.techidaily.com/354d3de8b2ab7d7a38cbcbf902765f2fb1bfbf3c885557e06e23ea74d7f6110b.jpg
---

## Boost Your PC: A Guide to Setting Up Hyper-V on Win 11 Home

 You can enable Hyper-V in Windows 11 as an optional feature included by default with the operating system. It lets you create virtual machines to install and run the guest OS on virtual hardware. However, Hyper-V is only available for the Pro, Education, and Enterprise edition of the OS. If you are using the Home edition, you have to rely on a third-party virtual machine manager.

 If you don’t want to use a third-party virtual machine manager, here is how to install Hyper-V on Windows 11 Home using a batch script hack.

## How to Enable Hardware Virtualization in Windows 11

![enable hardware virtualization bios hp laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hardware-virtualization-bios-hp-laptoop-1.jpg)

 Hyper-V is a bare-metal hypervisor and requires [Hardware Virtualization enabled in BIOS to work](https://www.makeuseof.com/what-is-virtualization-and-what-is-it-for/). Most modern systems support Hardware Virtualization, and you can enable it in BIOS.

 The below steps are for an HP laptop. Refer to the user manual or Knowledge Base resources on the computer manufacturer's website for other systems.

 To enable Hardware Virtualization in BIOS:

1. Shut down your PC if it is powered on.
2. Press the **Power** button to turn on the computer and then start pressing the **F10 key** to enter BIOS. The BIOS setup key varies depending on the manufacturer. So, use **F10, F2, F12, F1,** or **DEL** and see which one works for you.
3. Once in the BIOS Setup utility, open the **Configuration** tab.
4. Use the down arrow key and highlight **Virtualization Technology.**
5. Hit **Enter** and then select **Enabled**. Press **Enter** again to make the selection.
6. Next, press **F10** to save the changes and exit **BIOS**.
7. Your PC will restart with the Hardware Virtualization enabled. Now you can continue to install Hyper-V on your system.

## How to Install Hyper-V on Windows 11 Home

 The next step is to create and run a batch script to install the required files to enable Hyper-V in Windows 11 Home.

 Before you proceed with the next set of steps, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/). This will help you restore your computer to its current state if something goes wrong during the process.

 To enable Hyper-V in Windows 11 Home:

 1\. Open a new Notepad file. To do this, press **Win + R**, type notepad, and click **OK.**

![hyper v install windows 11 home script](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/hyper-v-install-windows-11-home-script.png)

 2\. In the Notepad file, copy and paste the following script:

`pushd "%~dp0"  
dir /b %SystemRoot%\servicing\Packages\*Hyper-V*.mum >hyper-v.txt  
for /f %%i in ('findstr /i . hyper-v.txt 2^>nul') do dism /online /norestart /add-package:"%SystemRoot%\servicing\Packages\%%i"  
del hyper-v.txt  
Dism /online /enable-feature /featurename:Microsoft-Hyper-V -All /LimitAccess /ALL  
pause`

 3\. Press **Ctrl + S** to open the save dialog.

 4\. In the file name field, type **hyperv.bat.** The **.bat** extension at the end of the file name is important to execute the script.

![save hyperv install script](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/save-hyperv-install-script.png)

 5\. Next, click the drop-down for **Save as type** and select **All Files.**

 6\. Click the **Save** button to save the file.

![run hyperv bat script administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/run-hyperv-bat-script-administrator.png)

 7\. Next, right-click on the **hyperv.bat** file and select **Run as administrator**. Click **Yes** if prompted by User Account Control.

 8\. The scrip will start executing in the Command Prompt to install Hyper-V. It may take a while, so wait till the process is complete.

 9.Once completed, you will see the Operation completed successfully message.

![install hyper v install windows 11 home](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/install-hyper-v-install-windows-11-home.png)

 10\. Type **Y** to confirm and restart your PC. If not, enter N to exit the Command Prompt.

 Note that you will need to restart your PC to apply the changes. After the restart, you should have Hyper-V installed in Windows 11 Home. Type Hyper-V in Windows search and click on Hyper-V Manager to create new a virtual machine.

 If it is still not available, you can [enable Hyper-V using the Windows Features dialog](https://www.makeuseof.com/windows-11-enable-hyper-v/), Command Prompt, and Windows PowerShell.

 Here's how you can quickly add Hyper-V to Windows 11 using Command Prompt:

1. Press the **Win** key and type **cmd**. Then right-click on **Command Prompt** and select **Run as administrator.**  
![enable hyper v command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hyper-v-command-prompt.png)
2. In the Command Prompt window, type the following command and press **Enter**:  
`<code>DISM /Online /Enable-Feature /All /FeatureName:Microsoft-Hyper-V`
3. The above command uses the Deployment Imaging Service and Management (DISM) tool to enable Microsoft Hyper-V and the necessary dependencies on your Windows computer. The operation completed successfully message means you have successfully enabled Hyper-V.

## How to Disable Hyper-V on Windows 11 Home

![disable hyper v windows 11 windows features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/disable-hyper-v-windows-11-windows-features.jpg)

 You can disable Hyper-V in Windows 11 Home using the Windows Features dialog.

 To disable Hyper-V:

1. Press **Win + R** to open the **Run** dialog box.
2. Type **optionalfeatures.exe** and click **OK**.
3. In the **Windows Features** dialog, locate the Hyper-V option.
4. Uncheck the **Hyper-V** option and click **OK**. Wait for the uninstallation process to complete.
5. Next, click on **Restart Now** to restart your PC and apply the changes.

 Apart from Hyper-V, the Windows OS features another nifty virtualization solution, Windows Sandbox—a lightweight desktop environment to run applications in isolation. You can [enable Windows Sandbox from Windows Features](https://www.makeuseof.com/enable-set-up-windows-sandbox-windows-11/), but only on the Pro and Enterprise edition of the OS.

 Unlike Hyper-V, there is no batch script hack to install the sandbox app on the Home edition of Windows 11\. Instead, you can use one of the [Windows Sandbox Alternatives for Windows](https://www.makeuseof.com/windows-11-sandbox-alternatives/) to run and test applications in isolation.

## Run Hyper-V on Windows 11 Home

 Microsoft has officially restricted the use of Hyper-V to the Pro, Education, and Enterprise edition of the OS. However, a little tweak in the BIOS and a handy batch script can help you install Hyper-V on Windows 11 Home.

 Once you have Hyper-V up and running, you can install Windows, Ubuntu, and other supported operating systems in a virtual machine.

 If you don’t want to use a third-party virtual machine manager, here is how to install Hyper-V on Windows 11 Home using a batch script hack.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-xr-to-others-android-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone XR To Others Android Devices? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-yellow-shade-from-laptop-panels/"><u>Banishing Yellow Shade From Laptop Panels</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-top-6-nft-platforms-unlocking-creativity-for-artists/"><u>2024 Approved  Top 6 NFT Platforms  Unlocking Creativity for Artists</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-frustration-fixing-11s-windows-pin-hiccups/"><u>Avoid Frustration: Fixing 11'S Windows PIN Hiccups</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-meme-mastery-ranking-internet-cultures-favorites/"><u>[New] 2024 Approved  Meme Mastery  Ranking Internet Culture's Favorites</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-simple-steps-to-document-online-meetings-on-os-xwindows-for-2024/"><u>[New] Simple Steps to Document Online Meetings on OS X/Windows for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-music-from-vivo-y100t-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Music from Vivo Y100t to iPod | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-customized-windows-cmd-tricks-and-tips/"><u>Boost Productivity: Customized Windows Cmd Tricks and Tips</u></a></li>
<li><a href="https://techidaily.com/video-file-repair-how-to-fix-corrupted-video-files-of-nubia-red-magic-9-pro-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>Video File Repair - How to Fix Corrupted video files of Nubia Red Magic 9 Pro on Mac?</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-enhanced-clarity-clear-background-in-cam-recordings-for-2024/"><u>[New] Enhanced Clarity  Clear Background in Cam Recordings for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-code-development-top-wls-2-methods-on-latest-oses/"><u>Boost Your Code Development: Top WLS 2 Methods on Latest OSes</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-the-ultimate-youtube-to-mp4-blueprint/"><u>[New] The Ultimate YouTube to MP4 Blueprint</u></a></li>
<li><a href="https://vp-tips.techidaily.com/precision-in-dissipating-soundtracks-a-guide-for-pros/"><u>Precision in Dissipating Soundtracks  A Guide for Pros</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-7-types-of-audio-effects-you-should-know/"><u>Updated In 2024, 7 Types of Audio Effects You Should Know</u></a></li>
<li><a href="https://youtube-help.techidaily.com/maximizing-audience-engagement-with-youtube-shorts-templates-for-2024/"><u>Maximizing Audience Engagement with YouTube Shorts Templates for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-infinix-hot-40-pro-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>How to Cast Infinix Hot 40 Pro Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-2024-approved-deciphering-the-twitter-archive-a-beginners-tutorial/"><u>[Updated] 2024 Approved  Deciphering the Twitter Archive  A Beginner's Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-task-manager-admin-mode-on-windows-11/"><u>Boosting Task Manager: Admin Mode on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-discord-updates-and-autostart-on-windows-10/"><u>Avoid Discord Updates & Autostart on Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-pc-with-smooth-directx-downloads-and-upgrades/"><u>Boost Your PC with Smooth DirectX Downloads & Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplifying-old-directx-gaming-via-dxvk-powered-upgrades/"><u>Amplifying Old DirectX Gaming via DXVK-Powered Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-edge-safety-implement-windows-11-defender-application-guard/"><u>Boosting Edge Safety: Implement Windows 11 Defender Application Guard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-performance-on-windows-11-top-seven-tweaks-for-game-enthusiasts/"><u>Boosting Performance on Windows 11: Top Seven Tweaks for Game Enthusiasts</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-top-10-after-effects-text-presets/"><u>[Updated] 2024 Approved  Top 10 After Effects Text Presets</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-the-apple-iphone-xr-sim-lock-4-easy-methods-by-drfone-ios/"><u>How To Unlock The Apple iPhone XR SIM Lock 4 Easy Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-and-reset-windows-11s-touch-keyboard-layout/"><u>Adjust and Reset Windows 11'S Touch Keyboard Layout</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-6s-plus-3-ways-to-unlock-by-drfone-ios/"><u>In 2024, How To Unlock Apple iPhone 6s Plus 3 Ways To Unlock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-update-disruption-x712-fiasco/"><u>Addressing Windows Update Disruption: X712 Fiasco</u></a></li>
<li><a href="https://win11-tips.techidaily.com/artistry-made-easy-top-7-windows-11-drawing-apps-reviewed/"><u>Artistry Made Easy: Top 7 Windows 11 Drawing Apps Reviewed</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/vintage-vibes-curating-melodic-selections-for-nuptial-video-making/"><u>Vintage Vibes Curating Melodic Selections for Nuptial Video Making</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-blank-spaces-on-your-screen-icons-revival-guide/"><u>Avoid Blank Spaces on Your Screen: Icons Revival Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-mobile-with-instant-windows-apks/"><u>Boost Your Mobile with Instant Windows APKs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-display-drivers-that-dont-launch-in-windows-10/"><u>Avoiding Display Drivers That Don’t Launch in Windows 10</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-pro-tips-for-streaming-and-screening-netflix-on-mac/"><u>[Updated] In 2024, Pro-Tips for Streaming & Screening Netflix on Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-write-access-denial-errors-in-windows-11-system/"><u>Addressing Write Access Denial Errors in Windows 11 System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-experts-strategy-for-managing-component-services-in-w11/"><u>An Expert's Strategy for Managing Component Services in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-control-display-settings-for-windows-11-users/"><u>Advanced Control: Display Settings for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-common-errors-essential-tips-for-first-time-windows-11-users/"><u>Avoiding Common Errors: Essential Tips for First-Time Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-not-stopping-generic-audio-issue/"><u>Addressing 'Windows Not Stopping Generic Audio' Issue</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fake-the-location-to-get-around-the-mlb-blackouts-on-vivo-v29-drfone-by-drfone-virtual-android/"><u>In 2024, Fake the Location to Get Around the MLB Blackouts on Vivo V29 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-in-depth-look-at-winservicesexe-and-its-errors/"><u>An In-Depth Look at Winservices.exe and Its Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-practices-for-eluding-windows-11-explorer-errors/"><u>Best Practices for Eluding Windows 11 Explorer Errors</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-crafting-consumer-connection-reimagining-receiving/"><u>2024 Approved  Crafting Consumer Connection  Reimagining Receiving</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-lost-data-from-honor-magic-v2-by-fonelab-android-recover-data/"><u>Recover lost data from Honor Magic V2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-with-automated-folder-pairings-in-new-windows-os/"><u>Boost Efficiency with Automated Folder Pairings in New Windows OS</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/in-2024-online-movie-creation-made-easy-top-9-free-tools/"><u>In 2024, Online Movie Creation Made Easy Top 9 Free Tools</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/s-hottest-4k8k-video-editing-tools-a-comprehensive-guide/"><u>S Hottest 4K/8K Video Editing Tools A Comprehensive Guide</u></a></li>
<li><a href="https://fake-location.techidaily.com/looking-for-a-location-changer-on-xiaomi-redmi-12-5g-look-no-further-drfone-by-drfone-virtual-android/"><u>Looking For A Location Changer On Xiaomi Redmi 12 5G? Look No Further | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bidding-farewell-to-ads-in-the-win-11-startup/"><u>Bidding Farewell to Ads in the Win 11 Startup</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-optimal-framessec-for-high-quality-slow-motion-cinematography/"><u>In 2024, Optimal Frames/Sec for High-Quality Slow-Motion Cinematography</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>