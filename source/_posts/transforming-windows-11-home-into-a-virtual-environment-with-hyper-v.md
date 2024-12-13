---
title: Transforming Windows 11 Home Into a Virtual Environment with Hyper-V
date: 2024-12-07T16:26:46.655Z
updated: 2024-12-12T20:26:38.342Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Transforming Windows 11 Home Into a Virtual Environment with Hyper-V
excerpt: This Article Describes Transforming Windows 11 Home Into a Virtual Environment with Hyper-V
keywords: Win11 Hyper-V Virt,Virtualize Win11 Hub,Hyper-V Windows Transf,Win11 To Hyper-V Space,Home Win11 Virt Env,Virtual Win11 Hyper,Hyper-V Convert WinHome
thumbnail: https://thmb.techidaily.com/80de444cb408ef81f4728e2850b723591d8016d7f4cd61445fe263111407c51f.jpg
---

## Transforming Windows 11 Home Into a Virtual Environment with Hyper-V

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BR4gsW-J7as?si=9a56UDKZKhREZnwz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/tPgf_wSdhS8?si=BHoH1ryaxmwk-8FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 5\. Next, click the drop-down for **Save as type** and select **All Files.**

 6\. Click the **Save** button to save the file.

![run hyperv bat script administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/run-hyperv-bat-script-administrator.png)

 7\. Next, right-click on the **hyperv.bat** file and select **Run as administrator**. Click **Yes** if prompted by User Account Control.

 8\. The scrip will start executing in the Command Prompt to install Hyper-V. It may take a while, so wait till the process is complete.

 9.Once completed, you will see the Operation completed successfully message.

![install hyper v install windows 11 home](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/install-hyper-v-install-windows-11-home.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/e4Nt2xXXtmE?si=CtKwFry4b0AJXnaN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/XS1nQCe95LU?si=A2dhdFkSAI61_nKA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLO5dwmJAVs?si=1OYH8rv8aPaMsCiU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-cloud.techidaily.com/new-digital-migration-made-simple-top-5-file-transfer-routes-for-computers-for-2024/"><u>[New] Digital Migration Made Simple Top 5 File Transfer Routes for Computers for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-tiktok-basics-for-macwindows-computers-explained/"><u>[New] In 2024, TikTok Basics for Mac/Windows Computers Explained</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-rapidrun-framefrozen-capture/"><u>[Updated] In 2024, RapidRun FrameFrozen Capture</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-unveiling-the-leading-free-stock-video-and-image-archives/"><u>[Updated] In 2024, Unveiling the Leading Free Stock Video and Image Archives</u></a></li>
<li><a href="https://games-able.techidaily.com/are-larger-game-companies-stifling-the-markets-health-market-analysis-special-episode/"><u>Are Larger Game Companies Stifling the Market's Health? [Market Analysis Special Episode]</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-edge-methods-for-heic-to-jpeg-switch-on-windows-11/"><u>Cutting-Edge Methods for Heic to JPEG Switch on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-video-output-fixing-black-webcam-display/"><u>Enhancing Video Output: Fixing Black Webcam Display</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-uses-for-microsofts-vcplusplus-distribute/"><u>Exploring Uses for Microsoft's VC++ Distribute</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-go-incognito-with-admin-credentials-on-windows-11/"><u>How to Go Incognito with Admin Credentials on Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-2-ways-to-monitor-honor-x7b-activity-drfone-by-drfone-virtual-android/"><u>In 2024, 2 Ways to Monitor Honor X7b Activity | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-pre-upgrade-knowledge-key-elements-explained/"><u>In 2024, Pre-Upgrade Knowledge Key Elements Explained</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-rising-above-internet-naysayers-and-detractors/"><u>In 2024, Rising Above Internet Naysayers and Detractors</u></a></li>
<li><a href="https://extra-hints.techidaily.com/innovative-software-to-reclaim-lost-files-from-missing-disk-segments/"><u>Innovative Software to Reclaim Lost Files From Missing Disk Segments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-your-windows-experience-with-unseen-functionalities-from-vivetool/"><u>Maximize Your Windows Experience with Unseen Functionalities From ViVeTool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-chrome-repair-for-windows-sudden-closure-errors/"><u>Quick Chrome Repair for Windows' Sudden Closure Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/route-to-administrator-rights-on-window-control-hub/"><u>Route to Administrator Rights on Window Control Hub</u></a></li>
<li><a href="https://technical-tips.techidaily.com/seamless-collaboration-setting-up-and-using-copilot-on-microsoft-teams/"><u>Seamless Collaboration: Setting Up and Using Copilot on Microsoft Teams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-rectifying-cannot-link-with-nvidia-error-in-windows/"><u>Steps for Rectifying Cannot Link with NVIDIA Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-command-prompt-with-elevated-authority-in-windows-11/"><u>The Ultimate Guide to Command Prompt with Elevated Authority in Windows 11</u></a></li>
</ul></div>

