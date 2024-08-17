---
title: "DIMS Masterclass: Restoring and Repairing Win11 Images"
date: 2024-08-16T01:46:33.405Z
updated: 2024-08-17T01:46:33.405Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes DIMS Masterclass: Restoring and Repairing Win11 Images"
excerpt: "This Article Describes DIMS Masterclass: Restoring and Repairing Win11 Images"
keywords: Win11 Image Recovery,Win11 Image Repair,Win11 Diagnostic Tools,Win11 Image Masterclass,Win11 Restore Tutorial,Win11 Images Fixed Guide,Win11 Image Correction
thumbnail: https://thmb.techidaily.com/9f799a63c5ced001089eec847a965c77100b85a292d3d2c56946946b1d875c1f.jpg
---

## DIMS Masterclass: Restoring and Repairing Win11 Images

 Windows 11, like its predecessor, features the built-in Deployment Image Servicing and Management (DISM), a command-line utility to troubleshoot critical system errors. The DISM commands can help you fix Blue Screen of Death (BSOD) errors, a slow computer due to broken system files, and even repair the Windows Recovery Environment.

 In this article, we’ll show you how you can use the DISM and System File Checker utility to repair your damaged Windows 11 image and installation.

## How to Use the DISM Command in Windows 11

 The DISM command-line utility is a multi-purpose tool. It allows the system administrator to prepare and service Windows images. In addition, you can use the DISM tool in combination with the System File Checker utility to recover your Windows computer from critical failure.

 While DISM supports multiple specified commands, to repair your Windows computer, you only need to know the DISM CheckHealth, DISM ScanHealth, and DISM RestoreHealth commands.

 If you can boot into Windows 11, you can run the DISM command from an elevated PowerShell console or Command Prompt. If not, you’ll need to [boot into the Windows Recovery Environment](boot%20into%20the%20Windows%20Recovery%20Environment) and launch Command Prompt from **Advanced Options** to run DISM.

## Check Your System Health Using the DISM CheckHealth Command

 You can check for any file corruption using the DISM CheckHealth command. It is a diagnostic tool used to detect system image corruption and report the same. However, it doesn’t perform any repair.

 To run the CheckHealth command:

1. Press the **Win** key and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator**.  
![DISM scan health powershell command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-clean-health-powershell-command.jpg)
3. In the Command Prompt window, type the following command and press **Enter**:  
`DISM /Online /Cleanup-Image /CheckHealth`
4. In the above command, the **/Online** parameter specifies the scan must be performed on the currently running operating system. The **/Cleanup-Image** parameter specifies the operation is related to Windows image repair.
5. When executed, the command will show the report as “**The component stored has been corrupted**” or “**No component store corrupted detected.**” depending on whether a component store corruption is found.  
![DISM powershell CheckHealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-powershell-checkhealth-command.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. If you use PowerShell, use the following command instead:  
`Repair-WindowsImage -Online -CheckHealth`
7. The PowerShell command will report your image status to indicate whether it is **Healthy**, **Repairable** or **Non-repairable**. A healthy image doesn’t need any further action, and you can proceed to run the SFC tool.

 If the image is repairable, you can use the RestoreHealth command to use Windows Update to fix any corruption. However, for a non-repairable image, you may need to perform a clean install to fix your computer.

## Perform an Advanced System Image Scan with the ScanHealth Command
![DISM scan health command PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-scan-health-command-powershell.jpg)

 You can use the DISM ScanHealth command to perform an advanced scan of your Windows 11 system image. This will check your system for component store corruption and save the report to a log file.

 To run the DISM ScanHealth command:

1. Open **PowerShell** as administrator.
2. Type the following command and press Enter:  
`DISM /Online /Cleanup-Image /ScanHealth`
3. This process may take some time to complete. Once done, it will report any issues with the component store.
4. If an issue is detected, run the DISM RestoreHealth command to repair your Windows image.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Run the DISM RestoreHealth Command to Repair the Windows System Image
![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dism-scan-health-restore-health-command-prompt.jpg)

 The DISM RestoreHealth command uses Windows Update to provide the necessary files to fix file corruption and repair the Windows 11 system image. However, you must be connected to the internet so that the DISM tool can download and restore the files needed to perform a repair.

 To run the DISM RestoreHealth command:

1. Open **Windows PowerShell** as administrator.
2. Next, type the following command and press **Enter**:  
`DISM.exe /Online /Cleanup-image /RestoreHealth`
3. The DISM utility will perform a scan and start repairing the Windows system image. This process may take some time to complete. So, wait till the progress bar reaches 100%.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Repair System Image Using an Alternate Repair Source

 The DISM RestoreHealth command may not work if your computer is not connected to the internet or if the Windows Update component is corrupt. In this situation, you can use a Windows installation media or a mounted Windows ISO as a local source to repair the system image.

 First, [create a bootable Windows 11 USB drive](https://www.makeuseof.com/windows-11-create-bootable-usb-drive/). Once you have the installation media ready, connect it to your computer and proceed with the below steps.

 To repair your Windows 11 system image using DISM and a local repair source:

1. Press **Win + E** to open **File Explorer**.
2. Open your installation media drive, open the **Sources** folder and make sure the **install.wim** file exists. Also, note the driver letter assigned to your installation media. In this instance, our installation media is assigned the drive letter **(I:)**.  
![install wim file in Windows 11 installation media](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/install-wim-file-in-windows-11-installation-media.jpg)
<!-- affiliate ads begin -->
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Next, type the following command to run the **DISM RestoreHealth** command with the installation media as a repair source:  
`DISM /Online /Cleanup-Image /RestoreHealth /Source:I\Sources\install.wim /LimitAccess`
4. In the above command, replace the placeholder **:I** with your installation media drive letter. Also, the **LimitAccess** command is an optional parameter that restricts DISM access to the specified source and prevents it from using **Windows Update** as a repair source.
5. Once the process is complete, you can close Command Prompt and run the **System File Checker** utility to complete the repair process.

## Repair Your Windows Installation Using the System File Checker (SFC) Utility
![run system file checker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/run-system-file-checker.png)
<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you have successfully repaired your Windows 11 system image using the DISM RestoreHealth command, run the System File Checker (SFC) utility. It will scan your Windows installation for system file corruption and fix them automatically.

 In almost all instances, you must run the System File Checker utility after using the DISM image repair command to complete the repair process. Here’s how to do it:

1. Press **Win + X** to open the **WindowsX** menu.
2. Click **Terminal (Admin)** to launch the **Windows** Terminal app as administrator.
3. In the **Terminal** window, type the following command to run the **System File Checker** utility:  
`sfc /scannow`
4. When you run the above command, the System File Checker utility will start verifying the integrity of system files to detect corruption. If detected, it’ll automatically try to repair by replacing the files with a cached copy located at **%WinDir%\\System32\\dllcache.**

 The SFC process may take some time to complete and often may feel stuck at some stage. If you see no progress for a long time, press the **Enter** key a few times on your keyboard to refresh the Command Prompt window to view real-time progress.

 After the process is complete, restart your computer and check for any improvements. If the issue persists, run the **sfc /scannow** command again to see if that helps fix the problem.

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Repair and Recover Your Windows System Image Using DISM and SFC

 DISM makes it easy to repair a corrupt Windows image. It works both online using Windows Update and offline with a WIM file. The steps to use DISM may look complicated at first glance; however, it only takes two commands and an elevated Command Prompt to repair your Windows 11 image and installation.

 In this article, we’ll show you how you can use the DISM and System File Checker utility to repair your damaged Windows 11 image and installation.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-screen-grab.techidaily.com/new-free-world-quest-the-elite-10-mmo-rankings-for-2024/"><u>[New] Free World Quest  The Elite 10 MMO Rankings for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-mastering-subtitle-integration-on-instagram-tv/"><u>[New] In 2024, Mastering Subtitle Integration on Instagram TV</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-augmenting-realities-for-better-outcomes/"><u>[Updated] Augmenting Realities for Better Outcomes</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-evaluating-m1s-capabilities-for-heavy-duty-media-editing/"><u>[Updated] Evaluating M1's Capabilities for Heavy-Duty Media Editing</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-exploring-4k-precision-on-asuss-professional-display/"><u>[Updated] Exploring 4K Precision on ASUS's Professional Display</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-unlock-screen-capture-potential-with-expert-tips-from-adobe-captivity/"><u>[Updated] In 2024, Unlock Screen Capture Potential with Expert Tips From Adobe Captivity</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-navigating-zoom-with-skype-a-guide-to-seamless-video-calls/"><u>[Updated] Navigating Zoom with Skype  A Guide to Seamless Video Calls</u></a></li>
<li><a href="https://extra-information.techidaily.com/budget-friendly-sky-vault-optimal-large-file-haven-for-2024/"><u>Budget-Friendly Sky Vault  Optimal Large File Haven for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/complete-guide-restoring-functionality-of-water-damaged-iphonesipods/"><u>Complete Guide: Restoring Functionality of Water-Damaged iPhones/iPods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-the-corrupted-windows-11-trash-issue/"><u>Correcting the Corrupted Windows 11 Trash Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-edge-methods-for-faster-epic-game-installs/"><u>Cutting-Edge Methods for Faster Epic Game Installs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-and-correcting-windows-11s-zoom-error-1132/"><u>Decoding and Correcting Windows 11'S Zoom Error #1132</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-windows-error-0xc0000001-quick-fixes/"><u>Eliminating Windows Error 0xC0000001: Quick Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-windows-information-discovery-everywhereapp-style/"><u>Enhance Windows Information Discovery, EverywhereApp Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/epic-color-crisis-8-ways-to-retool-your-pink-desktop/"><u>Epic Color Crisis: 8 Ways to Retool Your Pink Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-transforming-word-docs-into-pdf-on-win-11/"><u>Essential Guide: Transforming Word Docs Into PDF on Win 11</u></a></li>
<li><a href="https://win-able.techidaily.com/fix-it-now-effective-solutions-for-risk-of-rain-ebx-not-crashing-issues/"><u>Fix It Now: Effective Solutions for Risk of Rain Ebx Not Crashing Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-intellij-unison-crashes-in-windows-11/"><u>Fixing IntelliJ Unison Crashes in Windows 11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-laugh-loop-meme-treasures-for-diverse-events/"><u>In 2024, Laugh Loop  Meme Treasures for Diverse Events</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-mastering-the-art-of-subtitle-extraction-from-youtube-videos-a-threefold-approach-guide/"><u>In 2024, Mastering the Art of Subtitle Extraction From YouTube Videos  A Threefold Approach Guide</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/is-mega-mewtwo-the-strongest-pokemon-on-apple-iphone-12-mini-drfone-by-drfone-virtual-ios/"><u>Is Mega Mewtwo The Strongest Pokémon On Apple iPhone 12 mini? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lowest-black-friday-keys-fan-discount-on-windows-11-free-forever/"><u>Lowest Black Friday Keys Fan Discount on Windows 11, Free Forever</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-powershell-a-key-for-administrators/"><u>Mastering PowerShell: A Key for Administrators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-missing-file-detection-problems-on-win-11/"><u>Mitigating Missing File Detection Problems on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-past-error-x80072f30-in-windows-store/"><u>Navigate Past Error X80072F30 in Windows Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-no-hypervisor-detection-in-windows-sandbox-environment/"><u>Overcoming No Hypervisor Detection in Windows Sandbox Environment</u></a></li>
<li><a href="https://screen-capture.techidaily.com/passionate-communicator-evaluation-revision-viii-for-2024/"><u>Passionate Communicator Evaluation - Revision VIII for 2024</u></a></li>
<li><a href="https://driver-download.techidaily.com/rtx-2060-super-graphics-card-driver-download-for-windows-11/"><u>RTX 2060 Super Graphics Card Driver Download for Windows 11</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-recent-calls-back-from-oppo-find-n3-flip-by-fonelab-android-recover-call-logs/"><u>Simple ways to get recent calls back from Oppo Find N3 Flip</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-tackle-failed-system-call-on-windows-systems/"><u>Steps to Tackle Failed System Call on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-smarter-android-resource-use-in-wsl/"><u>Strategies for Smarter Android Resource Use in WSL</u></a></li>
<li><a href="https://win11-tips.techidaily.com/synergizing-macos-and-windows-software/"><u>Synergizing macOS and Windows Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-dxgierrordeviceremoved-challenge/"><u>Tackling the DXGI_ERROR_DEVICE_REMOVED Challenge</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-aesthetic-enhancement-implementing-themes-from-the-microsoft-store/"><u>The Art of Aesthetic Enhancement: Implementing Themes From the Microsoft Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/time-saving-windows-keyboard-tricks-for-swift-tasks/"><u>Time-Saving Windows: Keyboard Tricks for Swift Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-0xc00000f-windows-problems/"><u>Troubleshooting 0xC00000F Windows Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-power-of-repair-for-compromised-system-files/"><u>Unlocking the Power of Repair for Compromised System Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-mastery-easy-to-follow-guide-to-building-bootable-usbs/"><u>Win 11 Mastery: Easy-to-Follow Guide to Building Bootable USBs</u></a></li>
</ul></div>
