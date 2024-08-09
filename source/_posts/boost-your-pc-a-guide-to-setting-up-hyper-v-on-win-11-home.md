---
title: "Boost Your PC: A Guide to Setting Up Hyper-V on Win 11 Home"
date: 2024-08-08T10:55:03.970Z
updated: 2024-08-09T10:55:03.970Z
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

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
## How to Enable Hardware Virtualization in Windows 11

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
![save hyperv install script](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/save-hyperv-install-script.png)

 5\. Next, click the drop-down for **Save as type** and select **All Files.**

 6\. Click the **Save** button to save the file.

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
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
<li><a href="https://youtube-sure.techidaily.com/024-approved-first-offset-guide-affordable-channel-buys-to-monetize/"><u>[New] 2024 Approved  First Offset Guide  Affordable Channel Buys to Monetize</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-insta-twist-techniques-for-tailoring-your-photos-on-the-fly/"><u>[New] 2024 Approved  Insta-Twist Techniques for Tailoring Your Photos on the Fly</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-becoming-a-wealthy-beauty-channel-host-for-2024/"><u>[Updated] Becoming a Wealthy Beauty Channel Host for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-expert-review-dynamic-action-recording-tools/"><u>[Updated] Expert Review  Dynamic Action Recording Tools</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-guide-to-rapid-or-slowdown-youtubes-playback-adjustments/"><u>[Updated] Guide to Rapid or Slowdown  YouTube's Playback Adjustments</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-exploring-the-capabilities-of-screenflow-on-mac-devices/"><u>[Updated] In 2024, Exploring the Capabilities of ScreenFlow on Mac Devices</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-advanced-techniques-for-dynamic-and-dramatic-ae-heads-ups/"><u>2024 Approved  Advanced Techniques for Dynamic and Dramatic AE Heads-Ups</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-explore-this-costless-voice-changer-to-boost-valorant-skills/"><u>2024 Approved  Explore This Costless Voice Changer to Boost Valorant Skills</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-mirthful-mastery-no-pay-all-smiles/"><u>2024 Approved  Mirthful Mastery  No Pay, All Smiles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-updater-error-code-0xca00a009/"><u>Addressing Windows Updater Error Code: 0XCA00A009</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosted-efficiency-expert-tips-for-optimizing-bar-use/"><u>Boosted Efficiency: Expert Tips for Optimizing Bar Use</u></a></li>
<li><a href="https://fix-guide.techidaily.com/change-location-on-yik-yak-for-your-vivo-x100-pro-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>Change Location on Yik Yak For your Vivo X100 Pro to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/constructing-a-compelling-docu-script-a-stepwise-approach-for-2024/"><u>Constructing a Compelling Docu-Script  A Stepwise Approach for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-an-efficient-windows-menu-for-software-alerts/"><u>Crafting an Efficient Windows Menu for Software Alerts</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/cut-through-competition-advanced-techniques-for-instagram-ready-videos-for-2024/"><u>Cut Through Competition  Advanced Techniques for Instagram-Ready Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-windows-hello-for-secure-user-access/"><u>Enabling Windows Hello for Secure User Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-linux-with-windows-tools/"><u>Enhancing Linux with Windows Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-to-reactivate-googles-nearby-share-app/"><u>Essential Tips to Reactivate Google's Nearby Share App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expedite-word-clarity-with-windows-11-help/"><u>Expedite Word Clarity with Windows 11 Help</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-for-clearing-false-device-error-on-pcs/"><u>Expert Guide for Clearing False Device Error on PCs</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/exploring-the-top-8-facebook-extractors-for-films/"><u>Exploring the Top 8 Facebook Extractors for Films</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-dll-not-loading-error-in-windows-steam-client/"><u>Fixing Dll Not Loading Error in Windows Steam Client</u></a></li>
<li><a href="https://extra-tips.techidaily.com/flash-flick-narrative-template/"><u>Flash Flick Narrative Template</u></a></li>
<li><a href="https://extra-tips.techidaily.com/flash-method-swift-signature-bg-erasure-tips/"><u>Flash Method  Swift Signature BG Erasure Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-elevate-taskmanager-with-a-new-cli-tab-windows-11/"><u>How to Elevate TaskManager with a New CLI Tab (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-audacitys-error-while-opening-sound-device-issue-in-windows-11-and-11/"><u>How to Fix Audacity’s “Error While Opening Sound Device” Issue in Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-recover-nvidia-configurations-on-windows-os/"><u>How to Recover NVIDIA Configurations on Windows OS</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-videos-from-smart-8-plus-by-fonelab-android-recover-video/"><u>How to Rescue Lost Videos from Smart 8 Plus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-start-system-file-verification-with-sfc/"><u>How to Start System File Verification with SFC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/implementing-windows-11s-revamped-widget-interface/"><u>Implementing Windows 11'S Revamped Widget Interface</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-11-best-location-changers-for-vivo-x-flip-drfone-by-drfone-virtual-android/"><u>In 2024, 11 Best Location Changers for Vivo X Flip | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-create-an-apple-developer-account-on-apple-iphone-xs-by-drfone-ios/"><u>In 2024, How To Create an Apple Developer Account On Apple iPhone XS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instructions-disable-virtual-machine-feature-in-windows-11/"><u>Instructions: Disable Virtual Machine Feature in Windows 11</u></a></li>
<li><a href="https://extra-support.techidaily.com/jestjungle-your-gateway-to-universal-comedy-for-2024/"><u>JestJungle  Your Gateway to Universal Comedy for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-sizing-down-software-on-windows-11/"><u>Mastering the Art of Sizing Down Software on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimalist-workstations-with-windows-os/"><u>Minimalist Workstations with Windows OS</u></a></li>
<li><a href="https://extra-support.techidaily.com/next-gen-skyborne-a-deep-dive-into-h501s-x4-for-2024/"><u>Next-Gen Skyborne  A Deep Dive Into H501S X4 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-missing-msvcrt120dll-on-your-computer/"><u>Overcoming Missing Msvcrt120dll on Your Computer</u></a></li>
<li><a href="https://howto.techidaily.com/proven-ways-to-fix-there-was-a-problem-parsing-the-package-on-oppo-a2-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Proven Ways to Fix There Was A Problem Parsing the Package on Oppo A2 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quickly-manipulate-text-illumination-in-windows-11/"><u>Quickly Manipulate Text Illumination in Windows 11</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/remedying-the-cannot-find-dbghelpdll-error-an-in-depth-fix-guide/"><u>Remedying the Cannot Find dBghelp.dll Error: An In-Depth Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-update-issue-error-code-0x80073712/"><u>Resolving Windows Update Issue: Error Code 0X80073712</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resuscitating-silent-windows-headset-mic/"><u>Resuscitating Silent Windows Headset Mic</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silence-windows-aggressive-contrast-mode/"><u>Silence Windows' Aggressive Contrast Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-editing-tasks-with-powertoys-text-tools/"><u>Simplify Editing Tasks with PowerToys' Text Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/standardizing-your-windows-system-backups/"><u>Standardizing Your Windows System Backups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-rectifying-error-0x80300024-in-winxp/"><u>Steps for Rectifying Error 0X80300024 in WinXP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-identify-non-recognized-usb-devices-on-win-11/"><u>Steps to Identify Non-Recognized USB Devices on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-gaming-e84-fix-for-steam-windows/"><u>Streamline Your Gaming: E84 Fix for Steam Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/supercharge-with-leading-winning-apps-for-windows/"><u>Supercharge with Leading Winning Apps for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/superior-vm-choices-to-upgrade-windows-11-performance/"><u>Superior VM Choices To Upgrade Windows 11 Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-another-program-uses-device-auditory-fault/"><u>Tackling 'Another Program Uses Device' Auditory Fault</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-11s-error-0x0000011b-on-operations/"><u>Tackling Windows 11'S Error 0X0000011B on Operations</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/the-2023-assessment-of-apeaksofts-pioneering-screens-recording-for-2024/"><u>The 2023 Assessment of Apeaksoft's Pioneering Screens Recording for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-game-launch-freezes-steps-to-mend-windows-11-steam/"><u>Troubleshooting Game Launch Freezes: Steps to Mend Windows 11 Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-power-of-csgo-in-w11/"><u>Unlocking the Power of CS:GO in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/website-standoffs-on-pc-seven-saving-strategies-for-cross-browser-issues/"><u>Website Standoffs on PC: Seven Saving Strategies for Cross-Browser Issues</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-legendaries-are-in-pokemon-platinum-on-motorola-moto-g23-drfone-by-drfone-virtual-android/"><u>What Legendaries Are In Pokemon Platinum On Motorola Moto G23? | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1722208330807-why-you-should-choose-the-chatgpt-app-for-ios-devices-instead-of-the-website-6-essential-reasons/"><u>Why You Should Choose the ChatGPT App for iOS Devices Instead of the Website - 6 Essential Reasons</u></a></li>
</ul></div>
