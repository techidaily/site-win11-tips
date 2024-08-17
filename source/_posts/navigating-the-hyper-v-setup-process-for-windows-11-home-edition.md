---
title: Navigating the Hyper-V Setup Process for Windows 11 Home Edition
date: 2024-08-16T01:51:00.526Z
updated: 2024-08-17T01:51:00.526Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
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

![save hyperv install script](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/save-hyperv-install-script.png)

 5\. Next, click the drop-down for **Save as type** and select **All Files.**

 6\. Click the **Save** button to save the file.

![run hyperv bat script administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/run-hyperv-bat-script-administrator.png)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->

 7\. Next, right-click on the **hyperv.bat** file and select **Run as administrator**. Click **Yes** if prompted by User Account Control.

 8\. The scrip will start executing in the Command Prompt to install Hyper-V. It may take a while, so wait till the process is complete.

 9.Once completed, you will see the Operation completed successfully message.

![install hyper v install windows 11 home](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/install-hyper-v-install-windows-11-home.png)
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 10\. Type **Y** to confirm and restart your PC. If not, enter N to exit the Command Prompt.

 Note that you will need to restart your PC to apply the changes. After the restart, you should have Hyper-V installed in Windows 11 Home. Type Hyper-V in Windows search and click on Hyper-V Manager to create new a virtual machine.

 If it is still not available, you can [enable Hyper-V using the Windows Features dialog](https://www.makeuseof.com/windows-11-enable-hyper-v/), Command Prompt, and Windows PowerShell.

 Here's how you can quickly add Hyper-V to Windows 11 using Command Prompt:

1. Press the **Win** key and type **cmd**. Then right-click on **Command Prompt** and select **Run as administrator.**  
![enable hyper v command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hyper-v-command-prompt.png)
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. In the Command Prompt window, type the following command and press **Enter**:  
`<code>DISM /Online /Enable-Feature /All /FeatureName:Microsoft-Hyper-V`
3. The above command uses the Deployment Imaging Service and Management (DISM) tool to enable Microsoft Hyper-V and the necessary dependencies on your Windows computer. The operation completed successfully message means you have successfully enabled Hyper-V.

## How to Disable Hyper-V on Windows 11 Home
![disable hyper v windows 11 windows features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/disable-hyper-v-windows-11-windows-features.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-innovative-techniques-for-recording-instagram-story-highlights/"><u>[New] 2024 Approved  Innovative Techniques for Recording Instagram Story Highlights</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-fix-chrome-non-playing-androidios-videos-for-2024/"><u>[New] Fix Chrome  Non-Playing Android/iOS Videos for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-expert-analysis-which-editing-tool-trumps-the-other-filmora-or-democreator/"><u>[Updated] 2024 Approved  Expert Analysis  Which Editing Tool Trumps the Other, Filmora or Democreator?</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-streamlining-your-profile-alter-name-in-google-meet/"><u>[Updated] 2024 Approved  Streamlining Your Profile  Alter Name in Google Meet</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-decoding-the-mystery-of-where-are-my-youtube-comments-in-2024/"><u>[Updated] Decoding the Mystery of Where Are My YouTube Comments, In 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-innovating-your-teaching-with-interactive-screencasts/"><u>[Updated] In 2024, Innovating Your Teaching with Interactive Screencasts</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-quick-start-guide-dells-simple-screen-recording-methods/"><u>[Updated] Quick Start Guide  Dell's Simple Screen Recording Methods</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-nubia-red-magic-8s-pro-drfone-by-drfone-virtual-android/"><u>Catch or Beat Sleeping Snorlax on Pokemon Go For Nubia Red Magic 8S Pro | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpt-as-your-writing-partner-for-youtube-videos/"><u>ChatGPT as Your Writing Partner for YouTube Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-error-0xca00a009-from-windows-update-logs/"><u>Clearing Error 0xCA00A009 From Windows Update Logs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/costly-mistakes-when-opting-for-discounted-activation-keys/"><u>Costly Mistakes When Opting for Discounted Activation Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/craft-secure-quick-access-button-in-windows-11-for-hardware-unhook/"><u>Craft Secure, Quick Access Button in Windows 11 for Hardware Unhook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-windows-11-taskbar-for-key-indicators/"><u>Customizing Windows 11 Taskbar for Key Indicators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-your-way-through-windows-file-organization/"><u>Customizing Your Way Through Windows File Organization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-your-pcs-intel-processor-gen-through-windows/"><u>Deciphering Your PC's Intel Processor Gen Through Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-system-fixes-via-hotkey-configurations-in-w1011/"><u>Efficient System Fixes via Hotkey Configurations in W10/11</u></a></li>
<li><a href="https://fox-helps.techidaily.com/efficiently-setting-up-mixer-on-macos/"><u>Efficiently Setting Up Mixer on MacOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-code-crash-tactics-to-tackle-script-errors-in-windows/"><u>Eliminate Code Crash: Tactics to Tackle Script Errors in Windows</u></a></li>
<li><a href="https://win-forum.techidaily.com/expert-tips-for-forcing-windows-app-closure-with-ease-via-revouninstaller-tools/"><u>Expert Tips for Forcing Windows App Closure with Ease via RevoUninstaller Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explaining-and-solving-the-problem-of-missing-windows-drive-letters/"><u>Explaining and Solving The Problem Of Missing Windows Drive Letters</u></a></li>
<li><a href="https://android-unlock.techidaily.com/full-tutorial-to-bypass-your-vivo-x-flip-face-lock-by-drfone-android/"><u>Full Tutorial to Bypass Your Vivo X Flip Face Lock?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidance-to-overcome-same-user-account-error-on-pc/"><u>Guidance to Overcome Same-User Account Error on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-correcting-mcuicnt-execution-not-found-in-win-10/"><u>Guidelines for Correcting McUICnt Execution Not Found in Win 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-avoid-discord-starting-with-system-boots-up/"><u>How to Avoid Discord Starting with System Boots Up</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-legacy-library-exploring-free-visual-echoes/"><u>In 2024, The Legacy Library  Exploring Free Visual Echoes</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-imei-unlokers-for-your-lava-blaze-2-phone-by-drfone-android/"><u>In 2024, Top IMEI Unlokers for Your Lava Blaze 2 Phone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-what-pokemon-evolve-with-a-dawn-stone-for-huawei-nova-y71-drfone-by-drfone-virtual-android/"><u>In 2024, What Pokémon Evolve with A Dawn Stone For Huawei Nova Y71? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/inside-windows-power-to-guide-apps-browsers/"><u>Inside Windows' Power to Guide Apps, Browsers</u></a></li>
<li><a href="https://extra-support.techidaily.com/joyful-journeys-await-best-classic-summer-movies-for-2024/"><u>Joyful Journeys Await  Best Classic Summer Movies for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/latest-guide-how-to-bypass-google-pixel-8-frp-without-computer-by-drfone-android/"><u>Latest Guide How To Bypass Google Pixel 8 FRP Without Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/managing-high-gpu-activity-in-windows-desktop-window/"><u>Managing High GPU Activity in Windows Desktop Window</u></a></li>
<li><a href="https://extra-skills.techidaily.com/mastering-media-conversion-from-xml-to-srt-efficiently-for-2024/"><u>Mastering Media Conversion  From XML to SRT Efficiently for 2024</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/mastering-the-art-of-listening-best-earbuds-2024/"><u>Mastering the Art of Listening: Best Earbuds, 2024</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/mastering-your-home-network-with-the-advanced-features-of-the-linksys-ea9500-router/"><u>Mastering Your Home Network with the Advanced Features of the Linksys EA9500 Router</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-formatting-essential-disk-error-on-pc/"><u>Navigating the 'Formatting Essential' Disk Error on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventive-tips-the-top-7-windows-activities-that-could-be-risky/"><u>Preventive Tips: The Top 7 Windows Activities That Could Be Risky</u></a></li>
<li><a href="https://win11-tips.techidaily.com/probing-the-digital-core-acquiring-sids-on-win11-systems/"><u>Probing the Digital Core: Acquiring SIDs on Win11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-dropbox-cpu-load-on-windows-systems/"><u>Reducing Dropbox CPU Load on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refreshing-your-pc-resetting-windows-11-applications/"><u>Refreshing Your PC: Resetting Windows 11 Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revealing-the-secrets-to-disabling-cortana-in-windows-11/"><u>Revealing the Secrets to Disabling Cortana in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sketchmasters-roundup-top-7-drawing-tools-for-windows/"><u>SketchMasters Roundup: Top 7 Drawing Tools for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/smooth-launch-into-lotr-world-lol/"><u>Smooth Launch Into LOTR World (LOL)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-reinstate-windows-11-search-results/"><u>Techniques to Reinstate Windows 11 Search Results</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-razer-blade-pro-17-unveiled-high-end-performance-tailored-for-travel/"><u>The Razer Blade Pro 17 Unveiled: High-End Performance, Tailored for Travel</u></a></li>
<li><a href="https://unlock-android.techidaily.com/the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-itel-s23plus-device-by-drfone-android/"><u>The Ultimate Guide How to Bypass Swipe Screen to Unlock on Itel S23+ Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/time-traveling-computers-into-the-windows-11-era-with-old-tools/"><u>Time Traveling Computers Into the Windows 11 Era with Old Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-preventing-unwanted-command-window-activation/"><u>Tips for Preventing Unwanted Command Window Activation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-picture-files-on-windows-11-pc/"><u>Unlocking Picture Files on Windows 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unwanted-warning-fixes-for-chrome-on-windows-systems/"><u>Unwanted Warning Fixes for Chrome on Windows Systems</u></a></li>
<li><a href="https://extra-tips.techidaily.com/windows-11-unleash-its-full-capabilities/"><u>Windows 11  Unleash Its Full Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-reimagined-unveiling-update-22h2-features/"><u>Windows 11 Reimagined: Unveiling Update #22H2 Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-how-to-invisibly-remove-the-language-feature/"><u>Windows 11: How to Invisibly Remove the Language Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-excellence-via-vivetool-getting-ahead-of-the-curve/"><u>Windows Excellence via ViVeTool: Getting Ahead of the Curve</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-yourphoneexe-necessary-or-not-for-security/"><u>Windows' YourPhone.exe - Necessary or Not for Security?</u></a></li>
<li><a href="https://windows11.techidaily.com/zero-cost-hardware-recreation-in-windows/"><u>Zero-Cost Hardware Recreation in Windows</u></a></li>
</ul></div>
