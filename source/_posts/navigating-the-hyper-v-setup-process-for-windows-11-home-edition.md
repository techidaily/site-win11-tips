---
title: Navigating the Hyper-V Setup Process for Windows 11 Home Edition
date: 2024-07-12T17:16:23.101Z
updated: 2024-07-13T17:16:23.101Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating the Hyper-V Setup Process for Windows 11 Home Edition
excerpt: This Article Describes Navigating the Hyper-V Setup Process for Windows 11 Home Edition
keywords: Win11 Hyper-V Installation,Hyper-V Windows Setup Guide,Enabling Hyper-V on Win11,Setting Up Hyper-V Home Edition,Optimizing Win11 for Hyper-V,Hyper-V Configuration W11,Win11 Hyper-V Management
thumbnail: https://thmb.techidaily.com/5e9bfb6a7e4a347d52ac2274763d8cb00a024229f1f3b2af38f5058bc81f8e98.jpg
---

## Navigating the Hyper-V Setup Process for Windows 11 Home Edition

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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/no-more-frustrations-installation-fixes-for-missing-windows-upgrades/"><u>No More Frustrations! Installation Fixes for Missing Windows Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-correction-of-error-1132-in-windows-11/"><u>Mastering the Correction of Error 1132 in Windows 11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-golden-screenplay-gems-that-define-genres/"><u>In 2024, Golden Screenplay Gems That Define Genres</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/effortless-video-editing-on-windows-microsoft-video-editor-review-for-2024/"><u>Effortless Video Editing on Windows Microsoft Video Editor Review for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-xbox-game-pass-error-0x800700e9-on-windows-11/"><u>Overcoming Xbox Game Pass Error: 0X800700E9 on Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-come-up-with-the-best-pokemon-team-on-itel-p40-drfone-by-drfone-virtual-android/"><u>How to Come up With the Best Pokemon Team On Itel P40? | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-the-ultimate-breakdown-understanding-tiktoks-pfp-symbol/"><u>[Updated] 2024 Approved  The Ultimate Breakdown  Understanding TikTok's PFP Symbol</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-create-dynamic-text-animation-in-filmora-for-2024/"><u>Updated Create Dynamic Text Animation in Filmora for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-from-s-mode-essential-tips-for-windows-1011/"><u>Transitioning From S Mode: Essential Tips for Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-amend-out-of-memory-issues-in-hogwarts-adventures/"><u>Strategies to Amend Out of Memory Issues in Hogwarts Adventures</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-a-network-locked-honor-magic-vs-2-phone-by-drfone-android/"><u>How to Unlock a Network Locked Honor Magic Vs 2 Phone?</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/-vloggers-guide-to-camera-lenses-for-2024/"><u>[New] A Vlogger's Guide To Camera Lenses for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-overcome-insufficient-access-during-uninstall/"><u>Steps to Overcome Insufficient Access During Uninstall</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tutorial-implementing-microsoft-copilot-in-your-windows-workspace/"><u>Tutorial: Implementing Microsoft Copilot in Your Windows Workspace</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-inexpensive-pcs-optimized-video-settings-guide/"><u>[Updated] 2024 Approved  Inexpensive PCs  Optimized Video Settings Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quelling-irregular-beats-soundcard-irq-solutions/"><u>Quelling Irregular Beats: Soundcard IRQ Solutions</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-optimizing-video-posts-with-flawless-srt-file-integration-tactics/"><u>[New] Optimizing Video Posts with Flawless SRT File Integration Tactics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-third-party-av-solutions-amidst-microsoft-guard/"><u>Unlocking Third-Party AV Solutions Amidst Microsoft Guard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reimagine-archived-footage-boost-video-quality-using-madvr-on-windows/"><u>Reimagine Archived Footage: Boost Video Quality Using MadVR on Windows</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/the-choreography-of-cinematography-techniques-for-effortless-scene-progression/"><u>The Choreography of Cinematography Techniques for Effortless Scene Progression</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-dolby-atmos-installation-in-windows-1111/"><u>Seamless Dolby Atmos Installation in Windows 11/11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/crafting-gentle-volume-declines-using-logic-pro-for-2024/"><u>Crafting Gentle Volume Declines Using Logic Pro for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snowy-seasonings-sharing-apps-from-microsofts-marketplace/"><u>Snowy Seasonings: Sharing Apps From Microsoft's Marketplace</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-social-media-spotlight-top-twitters/"><u>[New] Social Media Spotlight  Top Twitters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-resolution-of-error-0x80d03801/"><u>Mastering the Resolution of Error 0X80D03801</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/achieving-professional-quality-remotely/"><u>Achieving Professional Quality Remotely</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sculpt-sketch-and-color-like-never-before-microsoft-paint-enhancements/"><u>Sculpt, Sketch & Color Like Never Before: Microsoft Paint Enhancements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-homescreen-activation-in-windows-11/"><u>Troubleshooting Homescreen Activation in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-11-screen-recording-techniques-combining-audio-and-visual-features-in-snipping-tool-max-156/"><u>Unveiling Windows 11 Screen Recording Techniques: Combining Audio & Visual Features in Snipping Tool (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-simplification-recapturing-default-rights/"><u>Windows 11 Simplification: Recapturing Default Rights</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-ultimate-iphone-video-editor-comparison-cameo-or-filmorago-for-2024/"><u>[New] Ultimate iPhone Video Editor Comparison  Cameo or FilmoraGo for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-tecno-camon-20-premier-5gfrp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Tecno Camon 20 Premier 5GFRP Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-connections-how-to-clear-dns-in-steam-settings/"><u>Streamline Connections: How to Clear DNS in Steam Settings</u></a></li>
<li><a href="https://howto.techidaily.com/fix-realme-v30t-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Realme V30T Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-capture-your-gaming-moments-xbox-one-screenshots-made-simple/"><u>[New] 2024 Approved  Capture Your Gaming Moments  Xbox One Screenshots Made Simple</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-control-of-lock-screen-delay-on-pcs/"><u>Regaining Control of Lock Screen Delay on PCs</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-optimizing-facebook-ads-with-a-structured-triple-layered-copywriting-approach/"><u>In 2024, Optimizing Facebook Ads with a Structured, Triple-Layered Copywriting Approach</u></a></li>
<li><a href="https://audio-editing.techidaily.com/essential-websites-offering-lofi-audio-sets-and-wallpapers-for-2024/"><u>Essential Websites Offering Lofi Audio Sets & Wallpapers for 2024</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-music-from-realme-note-50-by-fonelab-android-recover-music/"><u>The way to get back lost music from Realme Note 50</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-wobbling-keyboard-arrows-in-windows-environments/"><u>Revive Wobbling Keyboard Arrows in Windows Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-11s-operation-elevation-issue-740/"><u>Troubleshooting Windows 11'S Operation Elevation Issue #740</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-unusual-wsl-error-4294967295-on-pcs/"><u>Tackling Unusual WSL Error 4294967295 on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-administrator-privileges-denial-in-cmd-prompt/"><u>Solving Administrator Privileges Denial in Cmd Prompt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11s-full-potential-without-tpm/"><u>Unlocking Windows 11'S Full Potential without TPM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-process-of-win-backup-defaulting/"><u>Navigating the Process of Win Backup Defaulting</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-best-gif-maker-software-for-windows-and-mac/"><u>Updated Best GIF Maker Software for Windows and Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-greyed-out-unlock-pin-function-in-windows-11/"><u>Overcoming Greyed Out Unlock Pin Function in Windows 11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-10-vivo-v27e-android-sim-unlock-apk-by-drfone-android/"><u>Top 10 Vivo V27e Android SIM Unlock APK</u></a></li>
</ul></div>
