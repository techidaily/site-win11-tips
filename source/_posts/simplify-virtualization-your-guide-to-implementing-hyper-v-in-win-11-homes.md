---
title: "Simplify Virtualization: Your Guide to Implementing Hyper-V in Win 11 Homes"
date: 2024-10-11T02:48:07.033Z
updated: 2024-10-14T18:54:14.941Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Simplify Virtualization: Your Guide to Implementing Hyper-V in Win 11 Homes"
excerpt: "This Article Describes Simplify Virtualization: Your Guide to Implementing Hyper-V in Win 11 Homes"
keywords: Win 11 Hyper-V Guide,Simplified VM Setup,Hyper-V Windows 11,Easy Virtualization Win,Homes Hyper-V Tips,Virtualize with Win 11,Hyper-V Implementation
thumbnail: https://thmb.techidaily.com/936d10b629420455d4c3cd43378416c6e205e5dc73cdd968038b275d13e490d5.png
---

## Simplify Virtualization: Your Guide to Implementing Hyper-V in Win 11 Homes

 You can enable Hyper-V in Windows 11 as an optional feature included by default with the operating system. It lets you create virtual machines to install and run the guest OS on virtual hardware. However, Hyper-V is only available for the Pro, Education, and Enterprise edition of the OS. If you are using the Home edition, you have to rely on a third-party virtual machine manager.

 If you don’t want to use a third-party virtual machine manager, here is how to install Hyper-V on Windows 11 Home using a batch script hack.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087409/7443" target="_top" id="2087409">
  <img src="//a.impactradius-go.com/display-ad/7443-2087409" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087409/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://imp.i357552.net/c/5597632/994842/11832" target="_top" id="994842">
  <img src="//a.impactradius-go.com/display-ad/11832-994842" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/994842/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://appsumo.8odi.net/c/5597632/2123733/7443" target="_top" id="2123733">
  <img src="//a.impactradius-go.com/display-ad/7443-2123733" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123733/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Disable Hyper-V on Windows 11 Home

![disable hyper v windows 11 windows features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/disable-hyper-v-windows-11-windows-features.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538">
  <img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-guidance.techidaily.com/updated-quintessential-plots-making-movies-great/"><u>[Updated] Quintessential Plots Making Movies Great</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easing-up-windows-11-restrictions-for-store-app/"><u>Easing Up Windows 11 Restrictions for Store App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-ideas-to-illustrations-mastering-drawing-in-windows-11/"><u>From Ideas to Illustrations: Mastering Drawing in Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-oppo-reno-8t-5g-drfone-by-drfone-virtual-android/"><u>How to Get and Use Pokemon Go Promo Codes On Oppo Reno 8T 5G | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-can-life360-track-you-when-your-xiaomi-redmi-13c-is-off-drfone-by-drfone-virtual-android/"><u>In 2024, Can Life360 Track You When Your Xiaomi Redmi 13C is off? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-an-airtag-from-your-apple-id-account-on-apple-iphone-6-by-drfone-ios/"><u>In 2024, How to Remove an AirTag from Your Apple ID Account On Apple iPhone 6?</u></a></li>
<li><a href="https://hardware-help.techidaily.com/official-geforce-gtx-3070-ti-windows-drivers-compatible-with-windows-10-8-and-7/"><u>Official GeForce GTX 3070 Ti Windows Drivers: Compatible with Windows 10, 8 and 7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proactive-hardware-stress-tests/"><u>Proactive Hardware Stress Tests</u></a></li>
<li><a href="https://win11-tips.techidaily.com/syncing-submenus-with-desktop-environment-in-window-11/"><u>Syncing Submenus with Desktop Environment in Window 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-to-counteract-failed-pages-in-windows-store/"><u>Tactics to Counteract Failed Pages in Windows Store</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-6-appsservices-to-trace-any-infinix-gt-10-pro-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>Top 6 Apps/Services to Trace Any Infinix GT 10 Pro Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win-advanced.techidaily.com/top-free-windows-compatible-imaging-software-beyond-the-best-terabyte-image/"><u>Top Free Windows-Compatible Imaging Software: Beyond the Best Terabyte Image</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/top-ranking-gpus-the-ultimate-list-of-leading-graphics-cards/"><u>Top-Ranking GPUs: The Ultimate List of Leading Graphics Cards</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trusting-robot-generated-passwords-think-again-win-11-edition/"><u>Trusting Robot-Generated Passwords? Think Again! (Win 11 Edition)</u></a></li>
<li><a href="https://extra-resources.techidaily.com/unparalleled-top-10-free-image-archiving-hubs-pics-safe-and-sound/"><u>Unparalleled Top 10 Free Image Archiving Hubs, Pics Safe and Sound</u></a></li>
</ul></div>

