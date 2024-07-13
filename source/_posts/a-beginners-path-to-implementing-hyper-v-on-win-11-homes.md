---
title: A Beginner's Path to Implementing Hyper-V on Win 11 Homes
date: 2024-07-12T17:52:32.077Z
updated: 2024-07-13T17:52:32.077Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Beginner's Path to Implementing Hyper-V on Win 11 Homes
excerpt: This Article Describes A Beginner's Path to Implementing Hyper-V on Win 11 Homes
keywords: Win 11 Virtualization,Hyper-V for Home Users,Start Hyper-V Installation,Learn Win 11 VM Setup,Beginner's Hyper-V Guide,Implementing Win 11 Hyper-V,Setting Up Hyper-V Win 11
thumbnail: https://thmb.techidaily.com/f04df6c23b871cbbd0c17b0eb3921c505712d724d4bbb61a362d901e0200289d.jpg
---

## A Beginner's Path to Implementing Hyper-V on Win 11 Homes

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
<li><a href="https://win11-tips.techidaily.com/a-complete-breakdown-of-mouse-customization-features-on-win11/"><u>A Complete Breakdown of Mouse Customization Features on Win11</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-streamlining-communication-essentials-of-discords-video-sharing-feature/"><u>[Updated] 2024 Approved  Streamlining Communication  Essentials of Discord's Video Sharing Feature</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-high-definition-screens-selecting-your-optimal-4k-display/"><u>In 2024, High Definition Screens  Selecting Your Optimal 4K Display</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719338441167-navigating-through-the-hurdles-winplusprint-mishaps-in-windows/"><u>Navigating Through the Hurdles: Win+Print Mishaps in Windows.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719317772933-reconcile-your-win-plus-print-discrepinasions-with-effective-solutions/"><u>Reconcile Your Win + Print Discrepinasions with Effective Solutions</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-capture-unrooted-android-sounds-4-techniques-for-2024/"><u>[Updated] Capture Unrooted Android Sounds  4 Techniques for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-onedrive-errors-in-windows-1011-system/"><u>Addressing OneDrive Errors in Windows 10/11 System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-functional-utorrent-installers-on-pc-with-os-x/"><u>Addressing Non-Functional uTorrent Installers on PC with OS X</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-cutting-edge-chapter-tactics-to-complement-your-youtube-presentations/"><u>[New] 2024 Approved  Cutting-Edge Chapter Tactics to Complement Your YouTube Presentations</u></a></li>
<li><a href="https://games-able.techidaily.com/reduce-distractions-by-turning-off-ui-features/"><u>Reduce Distractions by Turning Off UI Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-compreenasolutiontowindowss-lsass-problem-step-by-step-guide/"><u>A CompreenasolutiontoWindows's Lsass Problem: Step by Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-one-way-outlook-issue-in-secure-environments/"><u>Addressing the One-Way Outlook Issue in Secure Environments</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-guiding-principles-for-integrating-videos-in-education/"><u>In 2024, Guiding Principles for Integrating Videos in Education</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-explore-the-world-of-tiny-screens-top-6-online-tools-for-free-and-complimentary-youtube-short-downloads/"><u>[Updated] In 2024, Explore the World of Tiny Screens  Top 6 Online Tools for Free & Complimentary YouTube Short Downloads</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/academic-archiving-ranking-the-top-10-educators-video-capturers-for-2024/"><u>Academic Archiving  Ranking the Top 10 Educator's Video Capturers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-routes-to-reviving-the-elusive-windows-terminal/"><u>5 Routes to Reviving the Elusive Windows Terminal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-ways-to-fix-the-no-servers-found-error-in-apex-legends-for-windows/"><u>9 Ways to Fix the No Servers Found Error in Apex Legends for Windows</u></a></li>
<li><a href="https://extra-resources.techidaily.com/evaluating-the-efficacy-of-aurora-hdr-technology/"><u>Evaluating the Efficacy of Aurora HDR Technology</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-essential-steps-to-clear-overflowing-c-drive-data/"><u>3 Essential Steps to Clear Overflowing C: Drive Data</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/essential-fb-video-loader-apps-ranked-5/"><u>Essential FB Video Loader Apps Ranked #5</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-2024-approved-introduction-to-basic-storytelling-constructs/"><u>[New] 2024 Approved  Introduction to Basic Storytelling Constructs</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-secret-story-spotters-top-5-app-recommendations/"><u>[Updated] Secret Story Spotters  Top 5 App Recommendations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-personalizing-windows-using-winbubble/"><u>A Step-by-Step Guide to Personalizing Windows Using WinBubble</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-ultimate-tips-to-streamline-your-ipad-screen-saving/"><u>[New] Ultimate Tips to Streamline Your iPad Screen Saving</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-an-innovative-auto-refresh-check-option-to-the-windows-ui/"><u>Adding an Innovative Auto-Refresh Check Option to the Windows UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-package-registration-hurdles-in-win11-image-files/"><u>Addressing Package Registration Hurdles in Win11 Image Files</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-tailored-techniques-to-procure-tweets-gifs/"><u>[Updated] In 2024, Tailored Techniques to Procure Tweets GIFs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-signs-its-probably-time-to-factory-reset-your-windows-pc/"><u>4 Signs It's Probably Time to Factory Reset Your Windows PC</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-from-novice-to-narrative-youtube-seo-strategies/"><u>[New] In 2024, From Novice to Narrative  YouTube SEO Strategies</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-lost-footage-on-tiktok-repeat-video-history/"><u>2024 Approved  Lost Footage on TikTok  Repeat Video History</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-vivo-v29-pro-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Vivo V29 Pro</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-a-honor-magic-v2-phone-that-is-locked-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset a Honor Magic V2 Phone That Is Locked | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-new-way-to-view-your-files-noteworthy-updates-in-windows-11/"><u>A New Way to View Your Files: Noteworthy Updates in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activation-essentials-making-most-of-win11s-widget-bar/"><u>Activation Essentials: Making Most of Win11's Widget Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-power-management-hiding-dim-display/"><u>Accessing Power Management: Hiding 'Dim Display'</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-in-use-files-errors-in-windows-152-chars/"><u>Addressing 'In-Use' Files Errors in Windows (152 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719363317332-troubleshoot-non-functional-shift-in-windows/"><u>Troubleshoot Non-Functional Shift in Windows.</u></a></li>
</ul></div>
