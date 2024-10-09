---
title: Enabling Hyper-V in Windows 11 for Beginners
date: 2024-10-04T20:32:13.189Z
updated: 2024-10-09T03:06:11.663Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enabling Hyper-V in Windows 11 for Beginners
excerpt: This Article Describes Enabling Hyper-V in Windows 11 for Beginners
keywords: Win11 Hyper-V Setup,Hyper-V Guide W11,Start Hyper-V W11,Basic Hyper-V Install,Learn Hyper-V Windows,Newbies Hyper-V Tutorial,Essential V Hyper-W11
thumbnail: https://thmb.techidaily.com/06e8346e5608d987194209ad6987c897b2a9a9792c4b565af91b063377adb915.jpg
---

## Enabling Hyper-V in Windows 11 for Beginners

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
<a href="https://aligracehair.sjv.io/c/5597632/1880940/19272" target="_top" id="1880940">
  <img src="//a.impactradius-go.com/display-ad/19272-1880940" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880940/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144285/7443" target="_top" id="2144285">
  <img src="//a.impactradius-go.com/display-ad/7443-2144285" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144285/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`<code>DISM /Online /Enable-Feature /All /FeatureName:Microsoft-Hyper-V`
3. The above command uses the Deployment Imaging Service and Management (DISM) tool to enable Microsoft Hyper-V and the necessary dependencies on your Windows computer. The operation completed successfully message means you have successfully enabled Hyper-V.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144288/7443" target="_top" id="2144288">
  <img src="//a.impactradius-go.com/display-ad/7443-2144288" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144288/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://wigfever.sjv.io/c/5597632/2014853/22899" target="_top" id="2014853">
  <img src="//a.impactradius-go.com/display-ad/22899-2014853" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014853/22899" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-eclipsing-fears-in-your-first-10-videos/"><u>[New] In 2024, Eclipsing Fears in Your First 10 Videos</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-in-2024-prime-ways-from-video-links-to-audio-downloads/"><u>[New] In 2024, Prime Ways From Video Links to Audio Downloads</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-terminology-trek-through-the-virtual-landscape/"><u>[New] Terminology Trek Through the Virtual Landscape</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-thwarting-vr-discomfort-tips-for-a-smooth-experience/"><u>[New] Thwarting VR Discomfort Tips for a Smooth Experience</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-2024-approved-thumbnail-magic-a-filmmakers-mobile-techniques-for-youtube/"><u>[Updated] 2024 Approved Thumbnail Magic A Filmmaker's Mobile Techniques for YouTube</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-seamless-social-streams-link-instagram-and-facebook/"><u>[Updated] In 2024, Seamless Social Streams Link Instagram & Facebook</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/elevate-your-video-visibility-ethically-one-million-in-views-for-2024/"><u>Elevate Your Video Visibility Ethically One Million in Views for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-5-programs-for-a-smooth-transition-from-apples-macos/"><u>Essential 5 Programs for a Smooth Transition From Apple's MacOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-concept-to-code-establishing-individual-patterns-on-windows/"><u>From Concept to Code: Establishing Individual Patterns on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-manually-apply-local-group-policies-to-single-windows-account/"><u>How to Manually Apply Local Group Policies to Single Windows Account</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-open-the-fax-cover-page-editor-in-windows-11/"><u>How to Open the Fax Cover Page Editor in Windows 11</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-unlink-apple-id-from-iphone-12-mini-by-drfone-ios/"><u>How To Unlink Apple ID From iPhone 12 mini</u></a></li>
<li><a href="https://fox-place.techidaily.com/mastering-theme-management-in-flipbook-pro-essential-guide/"><u>Mastering Theme Management in FlipBook Pro: Essential Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-javascript-troubleshooting-with-discord/"><u>Navigating Through Windows' JavaScript Troubleshooting with Discord</u></a></li>
<li><a href="https://fox-blue.techidaily.com/premier-advice-superior-iphone-audio-artists-for-2024/"><u>Premier Advice Superior iPhone Audio Artists for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-pink-screen-woes-a-practical-approach/"><u>Resolving Pink Screen Woes: A Practical Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-lost-sound-preferences-on-windows-os/"><u>Restoring Lost Sound Preferences on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-merging-data-on-modern-windows/"><u>The Art of Merging Data on Modern Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unplug-plug-back-in-quick-tips-to-resurrect-your-usb-wi-fi-link/"><u>Unplug, Plug Back In! – Quick Tips to Resurrect Your USB Wi-Fi Link</u></a></li>
</ul></div>

