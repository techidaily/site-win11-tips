---
title: Essential Steps to Implement Hyper-V on Windows 11 Home
date: 2024-09-11T01:21:04.894Z
updated: 2024-09-12T01:21:04.894Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Essential Steps to Implement Hyper-V on Windows 11 Home
excerpt: This Article Describes Essential Steps to Implement Hyper-V on Windows 11 Home
keywords: Hyper-V Installation Guide,Virtualization on Win11 Home,Setting Up Hyper-V W11,Hyper-V Setup Windows 11,Enabling Hyper-V in Win11,Win11 Hyper-V Implementation,Hyper-V Steps for Win11 Users
thumbnail: https://thmb.techidaily.com/e849b3433ae861a98a41e422ed19bb8502406c23628dc5175ac052fdfbe1c181.jpg
---

## Essential Steps to Implement Hyper-V on Windows 11 Home

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





<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130529/26400" target="_top" id="2130529">
  <img src="//a.impactradius-go.com/display-ad/26400-2130529" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130529/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1983539">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983539.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983539">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983539.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983539%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983539/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 5\. Next, click the drop-down for **Save as type** and select **All Files.**

 6\. Click the **Save** button to save the file.

![run hyperv bat script administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/run-hyperv-bat-script-administrator.png)





<!-- affiliate ads begin -->
<a href="https://smilemakers.pxf.io/c/5597632/2123901/26106" target="_top" id="2123901">
  <img src="//a.impactradius-go.com/display-ad/26106-2123901" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://smilemakers.pxf.io/i/5597632/2123901/26106" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 7\. Next, right-click on the **hyperv.bat** file and select **Run as administrator**. Click **Yes** if prompted by User Account Control.

 8\. The scrip will start executing in the Command Prompt to install Hyper-V. It may take a while, so wait till the process is complete.

 9.Once completed, you will see the Operation completed successfully message.

![install hyper v install windows 11 home](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/install-hyper-v-install-windows-11-home.png)





<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014854/22899" target="_top" id="2014854">
  <img src="//a.impactradius-go.com/display-ad/22899-2014854" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014854/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 10\. Type **Y** to confirm and restart your PC. If not, enter N to exit the Command Prompt.

 Note that you will need to restart your PC to apply the changes. After the restart, you should have Hyper-V installed in Windows 11 Home. Type Hyper-V in Windows search and click on Hyper-V Manager to create new a virtual machine.

 If it is still not available, you can [enable Hyper-V using the Windows Features dialog](https://www.makeuseof.com/windows-11-enable-hyper-v/), Command Prompt, and Windows PowerShell.

 Here's how you can quickly add Hyper-V to Windows 11 using Command Prompt:

1. Press the **Win** key and type **cmd**. Then right-click on **Command Prompt** and select **Run as administrator.**  
![enable hyper v command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hyper-v-command-prompt.png)
2. In the Command Prompt window, type the following command and press **Enter**:  




<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115910/19272" target="_top" id="2115910">
  <img src="//a.impactradius-go.com/display-ad/19272-2115910" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115910/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




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





<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123474/16836" target="_top" id="2123474">
  <img src="//a.impactradius-go.com/display-ad/16836-2123474" border="0" alt="https://techidaily.com" width="300" height="50"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123474/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Run Hyper-V on Windows 11 Home

 Microsoft has officially restricted the use of Hyper-V to the Pro, Education, and Enterprise edition of the OS. However, a little tweak in the BIOS and a handy batch script can help you install Hyper-V on Windows 11 Home.

 Once you have Hyper-V up and running, you can install Windows, Ubuntu, and other supported operating systems in a virtual machine.

 If you don’t want to use a third-party virtual machine manager, here is how to install Hyper-V on Windows 11 Home using a batch script hack.





<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-tips.techidaily.com/new-2024-approved-supreme-4k-tvs-for-the-ultimate-gaming-experience/"><u>[New] 2024 Approved Supreme 4K TVs for the Ultimate Gaming Experience</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-best-practices-for-creating-compelling-hash-tags-on-facebook/"><u>[New] Best Practices for Creating Compelling Hash Tags on Facebook</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-elevate-your-social-media-game-producing-powerful-fb-reels-for-2024/"><u>[New] Elevate Your Social Media Game Producing Powerful FB Reels for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-instagram-and-soundtracks-demystifying-legalities/"><u>[New] Instagram & Soundtracks Demystifying Legalities</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-quick-start-guide-to-arranging-engaging-google-sessions-for-2024/"><u>[New] Quick Start Guide to Arranging Engaging Google Sessions for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-reignite-retro-fun-select-best-pc-emulators-for-game-boy-advance-games/"><u>[Updated] 2024 Approved Reignite Retro Fun Select Best PC Emulators for Game Boy Advance Games</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-engage-and-measure-instagram-stories-as-a-data-source/"><u>[Updated] In 2024, Engage and Measure Instagram Stories as a Data Source</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-srt-conversion-made-easy-a-step-by-step-approach/"><u>[Updated] SRT Conversion Made Easy A Step-by-Step Approach</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-expert-chromebook-zoom-techniques-unveiled/"><u>2024 Approved Expert Chromebook Zoom Techniques Unveiled</u></a></li>
<li><a href="https://android-unlock.techidaily.com/best-lava-blaze-2-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>Best Lava Blaze 2 Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://howto.techidaily.com/calls-on-oppo-a38-go-straight-to-voicemail-12-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Calls on Oppo A38 Go Straight to Voicemail? 12 Fixes | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/coordinating-devices-in-power-save-windows-states/"><u>Coordinating Devices in Power-Save Windows States</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-yellowed-displays-via-windows-settings/"><u>Correcting Yellowed Displays via Windows Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/corrective-measures-for-virtual-disks-not-starting/"><u>Corrective Measures for Virtual Disks Not Starting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-windows-media-storage-hurdles/"><u>Demystifying Windows Media Storage Hurdles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-net-runtime-errors-in-microsoft-os/"><u>Eliminating .NET Runtime Errors in Microsoft OS</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-overcoming-the-msvcr110dll-deficit/"><u>Guide to Overcoming the Msvcr110.dll Deficit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-revive-blackened-webcam-on-windows-os/"><u>How to Revive Blackened Webcam on Windows OS</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-accelerated-download-solutions-for-vimeo-files/"><u>In 2024, Accelerated Download Solutions for Vimeo Files</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-catch-or-beat-sleeping-snorlax-on-pokemon-go-for-samsung-galaxy-a05-drfone-by-drfone-virtual-android/"><u>In 2024, Catch or Beat Sleeping Snorlax on Pokemon Go For Samsung Galaxy A05 | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-is-inshot-surging-above-all-else-in-edits/"><u>In 2024, Is InShot Surging Above All Else in Edits?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-triple-widget-grid-layout-in-windows-11/"><u>Mastering the Triple Widget Grid Layout in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-your-efficiency-with-essential-win11-navigation-shortcuts/"><u>Maximize Your Efficiency with Essential Win11 Navigation Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-printer-error-messages-on-windows/"><u>Navigating Through Printer Error Messages on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-fatal-roblox-error-messages/"><u>Overcoming Fatal Roblox Error Messages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11s-wi-fi-discovery-issues/"><u>Overcoming Windows 11'S Wi-Fi Discovery Issues</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/preparation-to-beat-giovani-in-pokemon-go-for-infinix-smart-8-pro-drfone-by-drfone-virtual-android/"><u>Preparation to Beat Giovani in Pokemon Go For Infinix Smart 8 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-windows-11-shortcut-issues-for-f-keys/"><u>Resolve: Windows 11 Shortcut Issues for F Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-clear-printer-usage-messages/"><u>Steps to Clear Printer Usage Messages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-prevent-windows-11-from-listening-in/"><u>Steps to Prevent Windows 11 From Listening In</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stopping-inadvertent-command-triggers-in-operating-system/"><u>Stopping Inadvertent Command Triggers in Operating System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-approach-to-discerning-hard-drive-from-solid-state-drive-in-windows/"><u>Streamlined Approach to Discerning Hard Drive From Solid State Drive in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-1011-updates-eliminate-x080246007/"><u>Streamlining Windows 10/11 Updates: Eliminate X080246007</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-on-overcoming-installation-hurdles-in-windows-os/"><u>Tips on Overcoming Installation Hurdles in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/triggering-windows-11-dialer/"><u>Triggering Windows 11 Dialer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbo-drives-efficient-data-alignment-for-win11-users/"><u>Turbo Drives: Efficient Data Alignment for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-fixing-windows-msvcr110dll-gap/"><u>Understanding & Fixing Windows' Msvcr110.dll Gap</u></a></li>
<li><a href="https://driver-install.techidaily.com/update-xerox-copier-6515-drivers/"><u>Update Xerox Copier 6515 Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11s-invalid-name-error-a-step-by-step-guide/"><u>Win11's 'Invalid Name Error': A Step-by-Step Guide</u></a></li>
</ul></div>







<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    