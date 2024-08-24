---
title: Instantly Install Hyper-V on Your Windows 11 Homesystem
date: 2024-08-23T07:08:06.623Z
updated: 2024-08-24T07:08:06.623Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Instantly Install Hyper-V on Your Windows 11 Homesystem
excerpt: This Article Describes Instantly Install Hyper-V on Your Windows 11 Homesystem
keywords: Hyper-V Setup Guide,Windows 11 Hyper-V,Quick Hyper-V Instal,Enable Hyper-V Windows,Hyper-V Installation Steps,Hyper-V on Win11 Homesys,Rapid Windows Hyper-V Install
thumbnail: https://thmb.techidaily.com/8761d7ab814205b2f88e7841689a57f834d49b25e2e76dad4d19bc3d0f2882d9.jpg
---

## Instantly Install Hyper-V on Your Windows 11 Homesystem

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Disable Hyper-V on Windows 11 Home

![disable hyper v windows 11 windows features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/disable-hyper-v-windows-11-windows-features.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
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
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Run Hyper-V on Windows 11 Home

 Microsoft has officially restricted the use of Hyper-V to the Pro, Education, and Enterprise edition of the OS. However, a little tweak in the BIOS and a handy batch script can help you install Hyper-V on Windows 11 Home.

 Once you have Hyper-V up and running, you can install Windows, Ubuntu, and other supported operating systems in a virtual machine.

 If you don’t want to use a third-party virtual machine manager, here is how to install Hyper-V on Windows 11 Home using a batch script hack.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-the-creme-de-la-creme-of-fluid-interactive-games/"><u>[New] 2024 Approved  The Crème De La Créme of Fluid Interactive Games</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-effortless-viewing-tackling-instagram-video-issues-for-2024/"><u>[Updated] Effortless Viewing  Tackling Instagram Video Issues for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-growth-hackers-guide-the-ultimate-list-of-top-strategies-to-retain-youtube-viewers-for-2024/"><u>[Updated] Growth Hackers Guide  The Ultimate List of Top Strategies to Retain YouTube Viewers for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-mac-tools-to-tighten-instagram-video-content/"><u>[Updated] Mac Tools to Tighten Instagram Video Content</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-save-time-money-on-passport-photos-with-our-free-generator-apps/"><u>[Updated] Save Time, Money on Passport Photos with Our Free Generator Apps</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-explore-free-online-music-beat-detection-tools/"><u>2024 Approved  Explore Free Online Music Beat Detection Tools</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-pixelated-personae-effective-face-covering-tactics/"><u>2024 Approved  Pixelated Personae  Effective Face Covering Tactics</u></a></li>
<li><a href="https://howto.techidaily.com/6-fixes-to-unfortunately-whatsapp-has-stopped-error-popups-on-nokia-105-classic-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Fixes to Unfortunately WhatsApp has stopped Error Popups On Nokia 105 Classic | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/can-you-unlock-iphone-15-plus-after-forgetting-the-passcode-drfone-by-drfone-ios/"><u>Can You Unlock iPhone 15 Plus After Forgetting the Passcode? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-directdraw-fails-a-practical-approach-for-win11-users/"><u>Conquering DirectDraw Fails: A Practical Approach for Win11 Users</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/damage-to-central-venous-lines/"><u>Damage to Central Venous Lines</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-fixes-the-ultimate-guide-for-upgrading-ati-radeon-drivers-under-windows/"><u>Easy Fixes: The Ultimate Guide for Upgrading ATI Radeon Drivers Under Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/end-toranse-of-wsl-in-windows-environment/"><u>End-Toranse of WSL in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixes-to-ensure-utorrent-operates-correctly-in-windows/"><u>Fixes to Ensure uTorrent Operates Correctly in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-blank-inputs-reviving-xbox-mic-functionality-on-windows-11/"><u>Fixing Blank Inputs: Reviving Xbox Mic Functionality on Windows 11</u></a></li>
<li><a href="https://win-solutions.techidaily.com/halo-infinite-lag-fix-techniques-to-overcome-gameplay-disruptions-and-improve-performance/"><u>Halo Infinite Lag Fix: Techniques to Overcome Gameplay Disruptions and Improve Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-correctly-unstrand-your-gaming-experience-in-windows/"><u>How to Correctly Unstrand Your Gaming Experience in Windows</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-make-the-most-of-your-apple-iphone-13-pro-max-lock-screen-with-notifications-by-drfone-ios/"><u>How to Make the Most of Your Apple iPhone 13 Pro Max Lock Screen with Notifications?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-retrieve-lost-default-volume-levels-on-pc/"><u>How to Retrieve Lost Default Volume Levels on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-success-with-office-works-setup-in-win11/"><u>Instant Success with Office Works Setup in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-your-linux-environment-into-windows-11-seamlessly/"><u>Integrating Your Linux Environment Into Windows 11 Seamlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/intelligent-battery-alerts-set-up-full-charges-in-windows-11/"><u>Intelligent Battery Alerts: Set Up Full Charges in Windows 11</u></a></li>
<li><a href="https://network-issues.techidaily.com/mastering-anthem-speed-troubleshooting-guide/"><u>Mastering Anthem Speed: Troubleshooting Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-restoring-lost-ps4-input-connection/"><u>Mastering the Art of Restoring Lost PS4 Input Connection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-windows-11s-geforce-now-xc0f1103f-fix/"><u>Mending Windows 11’S GeForce Now: Xc0f1103f Fix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-ad-ds-printer-errors-a-user-friendly-approach-for-windows-users/"><u>Navigating AD DS Printer Errors: A User-Friendly Approach for Windows Users</u></a></li>
<li><a href="https://video-capture.techidaily.com/pixels-and-players-advanced-tactics-for-recording-gaming/"><u>Pixels and Players  Advanced Tactics for Recording Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refresh-classics-atlasos-gaming-update/"><u>Refresh Classics: AtlasOS Gaming Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securely-implementing-new-os-windows-11-and-vmware-edition/"><u>Securely Implementing New OS: Windows 11 & VMWare Edition</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/skyrocketing-view-figures-by-sustaining-youtubes-creative-commons-license-for-2024/"><u>Skyrocketing View Figures by Sustaining YouTube's Creative Commons License for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-method-to-disable-wired-keys-for-pcs-running-windows/"><u>Stepwise Method to Disable Wired Keys for PCs Running Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-android-studio-operations-a-win32-guide/"><u>Streamlining Android Studio Operations: A Win32 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switching-off-internal-display-hardware-in-win-810/"><u>Switching Off Internal Display Hardware in Win 8/10</u></a></li>
<li><a href="https://apple-account.techidaily.com/tips-and-tricks-for-apple-id-locked-issue-on-apple-iphone-se-by-drfone-ios/"><u>Tips and Tricks for Apple ID Locked Issue On Apple iPhone SE</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-ensure-camera-activity-notifications-in-ws11/"><u>Tips to Ensure Camera Activity Notifications in WS11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uninterrupted-playtime-preventing-league-of-legends-offline-on-pc/"><u>Uninterrupted Playtime: Preventing League of Legends Offline on PC</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>