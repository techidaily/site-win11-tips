---
title: A Detailed How-To for Hypertuned Windows 11 Homes
date: 2024-08-16T01:11:32.251Z
updated: 2024-08-17T01:11:32.251Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Detailed How-To for Hypertuned Windows 11 Homes
excerpt: This Article Describes A Detailed How-To for Hypertuned Windows 11 Homes
keywords: Hypertuning Windows 11,Win11 Optimization Guide,Windows XP Performance Tips,Boost Home PC Speed,Enhance Windows 10 Performance,Advanced Windows Tweaks,Boosting Windows Stability
thumbnail: https://thmb.techidaily.com/802df3d91ab6daf6d905273698ce2644dd2e6aa605c087ae0dc1d7ad5065d08f.jpg
---

## A Detailed How-To for Hypertuned Windows 11 Homes

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
<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 5\. Next, click the drop-down for **Save as type** and select **All Files.**

 6\. Click the **Save** button to save the file.

![run hyperv bat script administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/run-hyperv-bat-script-administrator.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->

 7\. Next, right-click on the **hyperv.bat** file and select **Run as administrator**. Click **Yes** if prompted by User Account Control.

 8\. The scrip will start executing in the Command Prompt to install Hyper-V. It may take a while, so wait till the process is complete.

 9.Once completed, you will see the Operation completed successfully message.

![install hyper v install windows 11 home](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/install-hyper-v-install-windows-11-home.png)
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
## How to Disable Hyper-V on Windows 11 Home

![disable hyper v windows 11 windows features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/disable-hyper-v-windows-11-windows-features.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
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
<li><a href="https://extra-guidance.techidaily.com/new-premier-band-performances-web/"><u>[New] Premier Band Performances Web</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-step-by-step-creating-stellar-content-for-facebook-stories-for-2024/"><u>[New] Step-by-Step  Creating Stellar Content for Facebook Stories for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-ultimate-list-timely-humor-for-various-gatherings/"><u>[New] Ultimate List  Timely Humor for Various Gatherings</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-swiftly-secure-screen-shots-on-windows/"><u>2024 Approved  Swiftly Secure Screen Shots on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-keystrokes-using-typingaid/"><u>Accelerate Your Keystrokes Using TypingAid</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amending-disabled-windows-shadow-snapshots/"><u>Amending Disabled Windows Shadow Snapshots</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cant-change-the-brightness-of-your-windows-11-pc-here-are-8-ways-to-fix-it/"><u>Can't Change the Brightness of Your Windows 11 PC? Here Are 8 Ways to Fix It</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/cutting-through-platform-barriers-sharing-tweets-videos-to-snapchat/"><u>Cutting Through Platform Barriers  Sharing Tweets' Videos to Snapchat</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-the-dilemran-of-winscripterrors/"><u>Deciphering the Dilemran of WinScriptErrors</u></a></li>
<li><a href="https://article-tips.techidaily.com/discover-the-most-compelling-5-iphone-friendly-podcast-services-for-2024/"><u>Discover the Most Compelling 5 iPhone-Friendly Podcast Services for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-full-use-of-the-control-key-in-windows-11/"><u>Enabling Full Use of the Control Key in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-smooth-background-operations-with-edge-in-win11/"><u>Ensuring Smooth Background Operations with Edge in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essentials-of-windows-diagnostics-compiling-and-analyzing-data/"><u>Essentials of Windows Diagnostics: Compiling & Analyzing Data</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/explore-10-prime-video-editing-apps-for-android-and-pc-for-2024/"><u>Explore 10 Prime Video Editing Apps for Android and PC for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-unavailability-of-icloud-on-windows/"><u>Fixing the Unavailability of iCloud on Windows</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/forgot-locked-iphone-15-password-learn-the-best-methods-to-unlock-by-drfone-ios/"><u>Forgot Locked iPhone 15 Password? Learn the Best Methods To Unlock</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/fx360-pro-by-id-cooling-top-value-cooling-solution-under-70/"><u>FX360 Pro by ID-Cooling - Top Value Cooling Solution Under $70</u></a></li>
<li><a href="https://fox-that.techidaily.com/halt-double-notifications-disable-ipad-sounds-during-iphone-call-activation/"><u>Halt Double Notifications: Disable iPad Sounds During iPhone Call Activation</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-find-ispoofer-pro-activation-key-on-motorola-edge-40-pro-drfone-by-drfone-virtual-android/"><u>How to Find iSpoofer Pro Activation Key On Motorola Edge 40 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-copy-paste-not-working-in-chrome-edge-and-firefox-on-windows/"><u>How to Fix Copy-Paste Not Working in Chrome, Edge, and Firefox on Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-file-explorer-crashes-on-windows-11-complete-guide/"><u>How to Fix File Explorer Crashes on Windows 11 – Complete Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-guide-for-installing-windows-11-arm-via-iso-download/"><u>How-To Guide for Installing Windows 11 ARM via ISO Download</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-expert-advice-yt-clip-sharing-using-your-google-id/"><u>In 2024, Expert Advice  YT Clip Sharing Using Your Google ID</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-a-network-locked-realme-gt-5-phone-by-drfone-android/"><u>In 2024, How to Unlock a Network Locked Realme GT 5 Phone?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-best-spy-watches-for-your-realme-narzo-60x-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Best Spy Watches For your Realme Narzo 60x 5G | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-tutorial-to-change-samsung-galaxy-a23-5g-imei-without-root-a-comprehensive-guide-by-drfone-android/"><u>In 2024, Tutorial to Change Samsung Galaxy A23 5G IMEI without Root A Comprehensive Guide</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-win-customer-trust-incorporating-these-20-marketing-expressions/"><u>In 2024, Win Customer Trust  Incorporating These 20 Marketing Expressions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jumpstart-your-pc-with-hyper-v-on-windows-11/"><u>Jumpstart Your PC with Hyper-V on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-apex-servers-on-pc-7-ways-to-fix-no-server-errors-(156-chars/"><u>Mastering Apex Servers on PC: 7 Ways to Fix 'No Server' Errors (<156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-model-names-unraveling-your-device-in-six-easy-ways/"><u>Mastering Model Names: Unraveling Your Device in Six Easy Ways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-recollection-of-previous-windows-password/"><u>Mending “Recollection of Previous Window's Password”</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-mspm-setup-obstacles-in-windows-vista/"><u>Overcoming MSPM Setup Obstacles in Windows Vista</u></a></li>
<li><a href="https://buynow-help.techidaily.com/reliable-petfeeding-solution-with-petsafes-automated-six-meal-dispenser/"><u>Reliable PetFeeding Solution with PetSafe's Automated Six-Meal Dispenser</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-windows-crashes-due-to-video-drivers/"><u>Remedying Windows Crashes Due to Video Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-smooth-asana-operations-on-pcs/"><u>Restoring Smooth Asana Operations on PCs</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/screen-spectaculum-hitting-720p-with-twitter-vids/"><u>Screen Spectaculum  Hitting 720P with Twitter Vids</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shift-key-woes-try-these-fixes-now/"><u>Shift Key Woes? Try These Fixes Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steering-clear-of-stuck-warcraft-patches/"><u>Steering Clear of Stuck Warcraft Patches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-enable-digital-supervision-in-windows-11-pcs/"><u>Steps to Enable Digital Supervision in Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-prevent-date-changes-on-windows-pcs/"><u>Steps to Prevent Date Changes on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-non-definable-error-in-windows-environment/"><u>Tackling 'Non-Definable' Error in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-innovators-guide-leveraging-windows-11-widgets/"><u>Tech Innovators Guide: Leveraging Windows 11 Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-restoring-accessibility-of-displays-in-nvidia-software/"><u>Tips for Restoring Accessibility of Displays in Nvidia Software</u></a></li>
<li><a href="https://apple-account.techidaily.com/top-notch-solutions-for-disabled-apple-id-on-iphone-14-making-it-possible-by-drfone-ios/"><u>Top-Notch Solutions for Disabled Apple ID On iPhone 14 Making It Possible</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-write-file-access-issue-on-windows-1011/"><u>Troubleshooting Write File Access Issue on Windows 10/11</u></a></li>
<li><a href="https://win-solutions.techidaily.com/ultimate-strategies-to-stop-flickering-on-your-windows-browser-chrome-edition-updated-for-2e24/"><u>Ultimate Strategies to Stop Flickering on Your Windows Browser: Chrome Edition (Updated for 2E24)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/understanding-instagrams-reels-vs-stories-format-for-2024/"><u>Understanding Instagram’s Reels vs Stories Format for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-windows-strategy-for-sound-graph-segregation/"><u>Understanding Windows' Strategy for Sound Graph Segregation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-ftdibussys-its-impact-on-windows-memory-protocols/"><u>Unraveling ftdibus.sys: Its Impact on Windows Memory Protocols</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-typical-windows-rainmeter-setbacks-and-how-to-overcome-them/"><u>Unraveling Typical Windows Rainmeter Setbacks and How to Overcome Them</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winrars-hash-harmony-six-ways-to-ensure-correct-sums/"><u>WinRAR's Hash Harmony: Six Ways to Ensure Correct Sums</u></a></li>
</ul></div>
