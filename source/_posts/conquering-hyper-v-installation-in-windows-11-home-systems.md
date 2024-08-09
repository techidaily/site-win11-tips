---
title: Conquering Hyper-V Installation in Windows 11 Home Systems
date: 2024-08-08T11:12:45.338Z
updated: 2024-08-09T11:12:45.338Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Conquering Hyper-V Installation in Windows 11 Home Systems
excerpt: This Article Describes Conquering Hyper-V Installation in Windows 11 Home Systems
keywords: Win11 Hyper-V Setup Guide,Hyper-V Win11 Install Tips,Essential Win11 VM Tools,Easy Win11 Hyper-V Configuration,Win11 Proceeding with Hyper-V,Masterful Win11 Hyper-V Deployment,Optimal Win11 Virtualization Setup
thumbnail: https://thmb.techidaily.com/477a0b3e8eaad5a77258f27b87d4827ff92a53251f6cf584b61b0ab39b309f07.jpg
---

## Conquering Hyper-V Installation in Windows 11 Home Systems

 You can enable Hyper-V in Windows 11 as an optional feature included by default with the operating system. It lets you create virtual machines to install and run the guest OS on virtual hardware. However, Hyper-V is only available for the Pro, Education, and Enterprise edition of the OS. If you are using the Home edition, you have to rely on a third-party virtual machine manager.

 If you don’t want to use a third-party virtual machine manager, here is how to install Hyper-V on Windows 11 Home using a batch script hack.

## How to Enable Hardware Virtualization in Windows 11

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
![run hyperv bat script administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/run-hyperv-bat-script-administrator.png)

 7\. Next, right-click on the **hyperv.bat** file and select **Run as administrator**. Click **Yes** if prompted by User Account Control.

 8\. The scrip will start executing in the Command Prompt to install Hyper-V. It may take a while, so wait till the process is complete.

 9.Once completed, you will see the Operation completed successfully message.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
![install hyper v install windows 11 home](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/install-hyper-v-install-windows-11-home.png)

 10\. Type **Y** to confirm and restart your PC. If not, enter N to exit the Command Prompt.

 Note that you will need to restart your PC to apply the changes. After the restart, you should have Hyper-V installed in Windows 11 Home. Type Hyper-V in Windows search and click on Hyper-V Manager to create new a virtual machine.

 If it is still not available, you can [enable Hyper-V using the Windows Features dialog](https://www.makeuseof.com/windows-11-enable-hyper-v/), Command Prompt, and Windows PowerShell.

 Here's how you can quickly add Hyper-V to Windows 11 using Command Prompt:

1. Press the **Win** key and type **cmd**. Then right-click on **Command Prompt** and select **Run as administrator.**  
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![enable hyper v command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hyper-v-command-prompt.png)
2. In the Command Prompt window, type the following command and press **Enter**:  
`<code>DISM /Online /Enable-Feature /All /FeatureName:Microsoft-Hyper-V`
3. The above command uses the Deployment Imaging Service and Management (DISM) tool to enable Microsoft Hyper-V and the necessary dependencies on your Windows computer. The operation completed successfully message means you have successfully enabled Hyper-V.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
## Run Hyper-V on Windows 11 Home

 Microsoft has officially restricted the use of Hyper-V to the Pro, Education, and Enterprise edition of the OS. However, a little tweak in the BIOS and a handy batch script can help you install Hyper-V on Windows 11 Home.

 Once you have Hyper-V up and running, you can install Windows, Ubuntu, and other supported operating systems in a virtual machine.

 If you don’t want to use a third-party virtual machine manager, here is how to install Hyper-V on Windows 11 Home using a batch script hack.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-blog.techidaily.com/024-approved-mastering-the-craft-how-to-produce-mukbang-videos/"><u>[New] 2024 Approved  Mastering the Craft  How to Produce Mukbang Videos</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-from-novice-to-nirvana-transform-your-instagram-edits/"><u>[New] In 2024, From Novice to Nirvana  Transform Your Instagram Edits</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-essential-steps-for-recording-games-via-obs-for-2024/"><u>[Updated] Essential Steps for Recording Games via OBS for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719309134944-10-command-prompt-wonders-you-didnt-know/"><u>10 Command Prompt Wonders You Didn’t Know</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-how-to-chat-on-google-meet-complete-guide/"><u>2024 Approved  How to Chat on Google Meet [Complete Guide]</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-panopticam-review-breakdown/"><u>2024 Approved  PanoptiCam Review Breakdown</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-ultimate-action-cam-editing-solutions/"><u>2024 Approved  Ultimate Action Cam Editing Solutions</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-unleashing-broadcast-potential-from-obs-to-facebook-platform/"><u>2024 Approved  Unleashing Broadcast Potential  From OBS to Facebook Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-window-shifts-gone-but-not-forgotten/"><u>6 Window Shifts: Gone But Not Forgotten</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-infinix-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Infinix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-add-ons-for-disk-image-duality-on-pc/"><u>Avoiding Add-Ons for Disk Image Duality on PC</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/detailed-video-capture-using-videoleap-tools/"><u>Detailed Video Capture Using Videoleap Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-the-superiority-of-pcs-to-macs-in-9-areas/"><u>Dissecting the Superiority of PCs to Macs in 9 Areas</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-excel-essential-productivity-software-for-professionals-on-windows/"><u>Efficiently Excel: Essential Productivity Software for Professionals on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-system-performance-with-effective-use-of-windows-law-filters/"><u>Elevating System Performance with Effective Use of Window's LAW Filters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-writing-problems-on-windows-platforms/"><u>Eliminating Writing Problems on Windows Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-reliable-clicks-and-movement-on-your-desktop/"><u>Ensuring Reliable Clicks & Movement on Your Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-unresponsive-files-downloads-in-windows-11-5/"><u>Fixing Unresponsive Files Downloads in Windows 11 (5)</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-upgrade-iphone-12-to-the-latest-iosipados-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade iPhone 12 to the Latest iOS/iPadOS Version? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ignite-innovation-top-picks-from-microsofts-store-2-infuse-your-living-space-with-a-touch-of-history-while-maintaining-modern-comfort-and-style-lets-embark-20/"><u>Ignite Innovation: Top Picks From Microsoft's Store, 2 Infuse Your Living Space with a Touch of History While Maintaining Modern Comfort and Style? Let's Embark on an Exciting Home Decor Journey Together!</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-eternal-vision-recorder-tool/"><u>In 2024, Eternal Vision Recorder Tool</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-icloud-lock-on-iphone-15-pro-max-by-drfone-ios/"><u>In 2024, How to Bypass iCloud Lock on iPhone 15 Pro Max</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/in-2024-viral-harmony-essential-soundtracks-for-popular-video-shorts/"><u>In 2024, Viral Harmony  Essential Soundtracks For Popular Video Shorts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-closed-caption-settings-in-windows-11/"><u>Mastering Closed Caption Settings in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-directx-downloads-issue-in-os/"><u>Mending DirectX Downloads Issue in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-winvpn-error-remote-computer-not-reachable/"><u>Quick Guide: WinVPN Error Remote Computer Not Reachable</u></a></li>
<li><a href="https://tech-revival.techidaily.com/rapidly-advancing-ai-the-emerging-cybersecurity-dilemma/"><u>Rapidly Advancing AI: The Emerging Cybersecurity Dilemma</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-update-failure-error-0x8024800c/"><u>Resolving Windows Update Failure (Error 0X8024800C)</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-your-lost-connection-fixes-for-wifi-failures-in-win11/"><u>Reviving Your Lost Connection: Fixes for Wifi Failures in Win11</u></a></li>
<li><a href="https://win-solutions.techidaily.com/simple-steps-to-resolve-javascript-issues-in-discord/"><u>Simple Steps to Resolve JavaScript Issues in Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719361339925-solving-ms-to-do-discrepancies-no-sync-heres-how/"><u>Solving MS To-Do Discrepancies: No Sync? Here's How</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steam-deck-windows-installation-essentials/"><u>Steam Deck: Windows Installation Essentials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-mystery-fixing-windows-error-code-0x0000004e/"><u>Tackling the Mystery: Fixing Windows Error Code 0X0000004E</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/understanding-ip-sounds-and-songs-on-instagram-for-2024/"><u>Understanding IP  Sounds and Songs on Instagram for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-mac-video-editing-discover-the-best-options-beyond-vsdc/"><u>Updated In 2024, Mac Video Editing Discover the Best Options Beyond VSDC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-settings-unveiled/"><u>Windows 11 Settings Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-files-save-path-problem-easy-fix-guide/"><u>Windows Files' Save Path Problem: Easy Fix Guide</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>