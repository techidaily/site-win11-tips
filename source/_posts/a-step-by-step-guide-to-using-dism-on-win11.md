---
title: A Step-by-Step Guide to Using Dism on Win11
date: 2024-07-12T17:49:54.826Z
updated: 2024-07-13T17:49:54.826Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Step-by-Step Guide to Using Dism on Win11
excerpt: This Article Describes A Step-by-Step Guide to Using Dism on Win11
keywords: Dism Win11 Tutorial,Windows Removal Steps,Win11 Uninstall Guide,Dism Utility Use,Cleaning Win11 System,Win11 Setup Optimize,Remove OS via Dism
thumbnail: https://thmb.techidaily.com/8efb02d1ad78746fe7e04d066e97a30754c0040bd1d393f4b6d528ffbc9df6b1.jpg
---

## A Step-by-Step Guide to Using Dism on Win11

 Windows 11, like its predecessor, features the built-in Deployment Image Servicing and Management (DISM), a command-line utility to troubleshoot critical system errors. The DISM commands can help you fix Blue Screen of Death (BSOD) errors, a slow computer due to broken system files, and even repair the Windows Recovery Environment.

 In this article, we’ll show you how you can use the DISM and System File Checker utility to repair your damaged Windows 11 image and installation.

## How to Use the DISM Command in Windows 11

 The DISM command-line utility is a multi-purpose tool. It allows the system administrator to prepare and service Windows images. In addition, you can use the DISM tool in combination with the System File Checker utility to recover your Windows computer from critical failure.

 While DISM supports multiple specified commands, to repair your Windows computer, you only need to know the DISM CheckHealth, DISM ScanHealth, and DISM RestoreHealth commands.

 If you can boot into Windows 11, you can run the DISM command from an elevated PowerShell console or Command Prompt. If not, you’ll need to [boot into the Windows Recovery Environment](boot%20into%20the%20Windows%20Recovery%20Environment) and launch Command Prompt from **Advanced Options** to run DISM.

## Check Your System Health Using the DISM CheckHealth Command

 You can check for any file corruption using the DISM CheckHealth command. It is a diagnostic tool used to detect system image corruption and report the same. However, it doesn’t perform any repair.

 To run the CheckHealth command:

1. Press the **Win** key and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator**.  
![DISM scan health powershell command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-clean-health-powershell-command.jpg)
3. In the Command Prompt window, type the following command and press **Enter**:  
`DISM /Online /Cleanup-Image /CheckHealth`
4. In the above command, the **/Online** parameter specifies the scan must be performed on the currently running operating system. The **/Cleanup-Image** parameter specifies the operation is related to Windows image repair.
5. When executed, the command will show the report as “**The component stored has been corrupted**” or “**No component store corrupted detected.**” depending on whether a component store corruption is found.  
![DISM powershell CheckHealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-powershell-checkhealth-command.jpg)
6. If you use PowerShell, use the following command instead:  
`Repair-WindowsImage -Online -CheckHealth`
7. The PowerShell command will report your image status to indicate whether it is **Healthy**, **Repairable** or **Non-repairable**. A healthy image doesn’t need any further action, and you can proceed to run the SFC tool.

 If the image is repairable, you can use the RestoreHealth command to use Windows Update to fix any corruption. However, for a non-repairable image, you may need to perform a clean install to fix your computer.

## Perform an Advanced System Image Scan with the ScanHealth Command

![DISM scan health command PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-scan-health-command-powershell.jpg)

 You can use the DISM ScanHealth command to perform an advanced scan of your Windows 11 system image. This will check your system for component store corruption and save the report to a log file.

 To run the DISM ScanHealth command:

1. Open **PowerShell** as administrator.
2. Type the following command and press Enter:  
`DISM /Online /Cleanup-Image /ScanHealth`
3. This process may take some time to complete. Once done, it will report any issues with the component store.
4. If an issue is detected, run the DISM RestoreHealth command to repair your Windows image.

## Run the DISM RestoreHealth Command to Repair the Windows System Image

![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dism-scan-health-restore-health-command-prompt.jpg)

 The DISM RestoreHealth command uses Windows Update to provide the necessary files to fix file corruption and repair the Windows 11 system image. However, you must be connected to the internet so that the DISM tool can download and restore the files needed to perform a repair.

 To run the DISM RestoreHealth command:

1. Open **Windows PowerShell** as administrator.
2. Next, type the following command and press **Enter**:  
`DISM.exe /Online /Cleanup-image /RestoreHealth`
3. The DISM utility will perform a scan and start repairing the Windows system image. This process may take some time to complete. So, wait till the progress bar reaches 100%.

## Repair System Image Using an Alternate Repair Source

 The DISM RestoreHealth command may not work if your computer is not connected to the internet or if the Windows Update component is corrupt. In this situation, you can use a Windows installation media or a mounted Windows ISO as a local source to repair the system image.

 First, [create a bootable Windows 11 USB drive](https://www.makeuseof.com/windows-11-create-bootable-usb-drive/). Once you have the installation media ready, connect it to your computer and proceed with the below steps.

 To repair your Windows 11 system image using DISM and a local repair source:

1. Press **Win + E** to open **File Explorer**.
2. Open your installation media drive, open the **Sources** folder and make sure the **install.wim** file exists. Also, note the driver letter assigned to your installation media. In this instance, our installation media is assigned the drive letter **(I:)**.  
![install wim file in Windows 11 installation media](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/install-wim-file-in-windows-11-installation-media.jpg)
3. Next, type the following command to run the **DISM RestoreHealth** command with the installation media as a repair source:  
`DISM /Online /Cleanup-Image /RestoreHealth /Source:I\Sources\install.wim /LimitAccess`
4. In the above command, replace the placeholder **:I** with your installation media drive letter. Also, the **LimitAccess** command is an optional parameter that restricts DISM access to the specified source and prevents it from using **Windows Update** as a repair source.
5. Once the process is complete, you can close Command Prompt and run the **System File Checker** utility to complete the repair process.

## Repair Your Windows Installation Using the System File Checker (SFC) Utility

![run system file checker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/run-system-file-checker.png)

 Once you have successfully repaired your Windows 11 system image using the DISM RestoreHealth command, run the System File Checker (SFC) utility. It will scan your Windows installation for system file corruption and fix them automatically.

 In almost all instances, you must run the System File Checker utility after using the DISM image repair command to complete the repair process. Here’s how to do it:

1. Press **Win + X** to open the **WindowsX** menu.
2. Click **Terminal (Admin)** to launch the **Windows** Terminal app as administrator.
3. In the **Terminal** window, type the following command to run the **System File Checker** utility:  
`sfc /scannow`
4. When you run the above command, the System File Checker utility will start verifying the integrity of system files to detect corruption. If detected, it’ll automatically try to repair by replacing the files with a cached copy located at **%WinDir%\\System32\\dllcache.**

 The SFC process may take some time to complete and often may feel stuck at some stage. If you see no progress for a long time, press the **Enter** key a few times on your keyboard to refresh the Command Prompt window to view real-time progress.

 After the process is complete, restart your computer and check for any improvements. If the issue persists, run the **sfc /scannow** command again to see if that helps fix the problem.

## Repair and Recover Your Windows System Image Using DISM and SFC

 DISM makes it easy to repair a corrupt Windows image. It works both online using Windows Update and offline with a WIM file. The steps to use DISM may look complicated at first glance; however, it only takes two commands and an elevated Command Prompt to repair your Windows 11 image and installation.

 In this article, we’ll show you how you can use the DISM and System File Checker utility to repair your damaged Windows 11 image and installation.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-discover-the-best-8-mirrorless-cameras-that-transform-vlogging/"><u>[Updated] 2024 Approved  Discover the Best  8 Mirrorless Cameras That Transform Vlogging</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-messages-from-itel-by-fonelab-android-recover-messages/"><u>How to retrieve erased messages from Itel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-strategies-to-tackle-delay-in-typing-windows-11s-keyboard/"><u>8 Strategies to Tackle Delay in Typing Windows 11'S Keyboard</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-edit-like-a-pro-the-5-best-iphone-video-editing-apps/"><u>New In 2024, Edit Like a Pro The 5 Best iPhone Video Editing Apps</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-proven-techniques-to-elevate-your-igtv-videos-on-mobile-and-professional-cameras/"><u>[New] 2024 Approved  Proven Techniques to Elevate Your IGTV Videos on Mobile & Professional Cameras</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-the-best-free-and-easy-to-use-4k-video-editors/"><u>New 2024 Approved The Best Free and Easy-to-Use 4K Video Editors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-no-wi-fi-in-windows-network/"><u>Breaking Down No Wi-Fi in Windows Network</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-repeated-team-sign-ins-on-windows-systems/"><u>Bypassing Repeated Team Sign-Ins on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-system-startup-with-auto-auditory-restart-mechanism/"><u>Boosting System Startup with Auto Auditory Restart Mechanism</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-the-ultimate-guide-to-discord-from-basics-to-advanced/"><u>[New] The Ultimate Guide to Discord  From Basics to Advanced</u></a></li>
<li><a href="https://win11-tips.techidaily.com/creating-a-secure-quick-launch-button-for-hardware-removal/"><u>Creating a Secure, Quick-Launch Button for Hardware Removal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breakdown-of-microsofts-earnings-through-windows-11/"><u>Breakdown of Microsoft's Earnings Through Windows 11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-exploring-alternatives-to-buying-views-for-authentic-audience-building/"><u>2024 Approved  Exploring Alternatives to Buying Views for Authentic Audience Building</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-digital-delights-8-most-watched-movies/"><u>[Updated] 2024 Approved  Digital Delights  8 Most Watched Movies</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-ticklishtones-selecting-the-best-ringtones-for-smiles/"><u>[Updated] TicklishTones  Selecting the Best Ringtones for Smiles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-weekly-windows-file-backups-matter/"><u>Why Weekly Windows File Backups Matter</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-turning-pinterest-video-into-downloadable-mp3-files/"><u>In 2024, Turning Pinterest Video Into Downloadable MP3 Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-disrupted-microphone-input-in-valorant-windows/"><u>Addressing Disrupted Microphone Input in Valorant (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-solutions-to-resolve-windows-update-error-0x800f080a/"><u>Essential Solutions to Resolve Windows Update Error 0X800F080A</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-spot-and-dismantle-unused-windows-folders-easily/"><u>How to Spot & Dismantle Unused Windows Folders Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-firewall-essential-fixes-for-a-shutdown-system/"><u>Enabling Firewall: Essential Fixes for a Shutdown System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-through-windows-11-theme-barriers-using-registry/"><u>Breaking Through Windows 11 Theme Barriers Using Registry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-lifeline-for-gaming-ensuring-persistent-connection-of-your-ps4-controller-in-windows/"><u>A Lifeline for Gaming: Ensuring Persistent Connection of Your PS4 Controller in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-reasons-to-never-turn-off-your-windows-11-push-notifications/"><u>Discover Reasons to Never Turn Off Your Windows 11 Push Notifications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-windows-11-experience-implementing-superior-run-capabilities/"><u>Elevate Your Windows 11 Experience: Implementing Superior Run Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-windows-navigator-placement-of-this-pc-icons/"><u>Customizing Windows Navigator: Placement of 'This PC' Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-1011-camera-error-0xa00f425d/"><u>Fixing Windows 10/11 Camera Error: 0XA00F425D</u></a></li>
<li><a href="https://fake-location.techidaily.com/ultimate-guide-to-free-pptp-vpn-for-beginners-on-samsung-galaxy-f54-5g-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Free PPTP VPN For Beginners On Samsung Galaxy F54 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-device-safety-increase-win11-pin-length/"><u>Elevate Your Device Safety: Increase Win11 PIN Length</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-winexe-creation-from-batch-scripts/"><u>Unveiling WinEXE Creation From Batch Scripts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-file-sharing-capabilities-in-geforce/"><u>Enhancing File-Sharing Capabilities in GeForce</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-ios-images-not-working-with-windows-1011/"><u>How to Fix iOS Images Not Working with Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-language-skills-using-windows-1011-hotkeys/"><u>Boost Your Language Skills Using Windows 10/11 Hotkeys</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-cutting-the-clutter-stopping-instagram-followers/"><u>2024 Approved  Cutting the Clutter  Stopping Instagram Followers</u></a></li>
<li><a href="https://windows11.techidaily.com/activate-dialer-in-microsoft-windows-11/"><u>Activate Dialer in Microsoft Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-messages-from-note-30-5g-by-fonelab-android-recover-messages/"><u>How to Rescue Lost Messages from Note 30 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-admin-username-on-windows-11-step-by-step-guide/"><u>Altering Admin Username on Windows 11: Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-using-dark-theme-in-notepad/"><u>Understanding and Using Dark Theme in Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reactivate-a-nonfunctional-nvidia-cp-on-windows-11/"><u>How to Reactivate a Nonfunctional Nvidia CP on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-restricted-it-administrator-message-in-os/"><u>Eliminating 'Restricted IT Administrator' Message in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-usability-faster-uninstall-options-in-win/"><u>Enhancing Usability: Faster Uninstall Options in Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unwrapping-the-truth-behind-windows-error-code-0x80073d26/"><u>Unwrapping the Truth Behind Windows' Error Code 0X80073D26</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-recent-calls-back-from-zte-nubia-flip-5g-by-fonelab-android-recover-call-logs/"><u>Simple ways to get recent calls back from ZTE Nubia Flip 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-prompt-pranks-engage-in-5-digital-delights/"><u>Command Prompt Pranks: Engage in 5 Digital Delights</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-stepwise-approach-to-voice-recognition-integration-in-powerpoint-presentations/"><u>In 2024, The Stepwise Approach to Voice Recognition Integration in PowerPoint Presentations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-11-taskbar-responsiveness/"><u>Enhancing Windows 11 Taskbar Responsiveness</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-cut-down-on-menus-in-windows-11/"><u>How to Cut Down on Menus in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-end-task-control-panel-in-windows-11-ui/"><u>Mastering the End Task Control Panel in Windows 11 UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diminish-noise-restoring-your-keys-sound-functionality/"><u>Diminish Noise: Restoring Your Key's Sound Functionality</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-two-ways-to-track-my-boyfriends-meizu-21-without-him-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Two Ways to Track My Boyfriends Meizu 21 without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/n-youtube-seo-methods-for-video-rankings/"><u>Proven YouTube SEO Methods for Video Rankings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-to-updating-username-on-windows-11/"><u>Essential Guide to Updating Username on Windows 11</u></a></li>
</ul></div>
