---
title: "Fixing Non-Installed Optional Windows Functions: A 7-Step Guide"
date: 2024-07-12T16:44:59.733Z
updated: 2024-07-13T16:44:59.733Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Fixing Non-Installed Optional Windows Functions: A 7-Step Guide"
excerpt: "This Article Describes Fixing Non-Installed Optional Windows Functions: A 7-Step Guide"
keywords: Windows Function Fix Guide,Install Missing Windows Options,OptiWindows Compliance,Steps to Add OS Features,Uninstall Non-Installed Features,Enhance System Windows,Essential Windows Extras Update
thumbnail: https://thmb.techidaily.com/250f73dd4b9929867a630f9b8f32aa45e2b59d5cab96411e7883925b75cba9fc.jpg
---

## Fixing Non-Installed Optional Windows Functions: A 7-Step Guide

 Optional features are those that you can add to get more functionality or support for certain file formats. For example, you can install different font packs or old Windows utilities like Paint and WordPad.

 If you're having trouble installing optional features, you're not alone. Sometimes optional features may fail to install due to corrupt system files, an outdated Windows version, or incorrect configuration settings.

 Fortunately, there are several ways to fix this problem and get the optional features running again. So, how can you fix the optional features not installing issue?

## 1\. Use the DISM Tool

 One of the first things you can try is using the Deployment Image Servicing and Management (DISM) tool. This tool is part of Windows, and you can use it to fix corrupt system files, including ones that could be causing problems when installing optional features.

To use the DISM tool, follow these steps:

1. Press**Win + Q** to bring up the Windows search dialogue box.
2. Type**cmd** and click**Run as administrator** to open the Command Prompt.
3. Type**dism /online /cleanup-image /restorehealth** and press**Enter** .  
![DISM Windows Utility Overview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/dism-windows-utility.jpg)

 This will start the DISM tool and begin scanning your system for any corrupt or missing files. If it finds any issues with your computer, it will automatically repair them.

 Once the process is complete, you can restart your computer and try installing the optional feature again. If DISM does not work or throws an error code, make sure to go through the [DISM not working fixes](https://www.makeuseof.com/windows-11-dism-error-2-fix/) .

## 2\. Run the System File Checker or SFC Utility

 Another tool you can use to fix issues with optional feature installation is the System File Checker (SFC) utility.

 SFC is a command-line utility on Windows, which means you can use it from the Command Prompt itself. It is a useful tool for troubleshooting and repairing problems with the system files on your computer, similar to the DISM tool.

To check your system using SFC, follow these steps:

1. Open the Command Prompt with administrative rights using any of the [ways to open CMD as an admin on Windows](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
2. Type**sfc /scannow** and press**Enter** .  
![SFC Utility In Windows Overview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-utility-in-windows.jpg)
3. Once SFC scans for errors, make sure to restart your computer.

Want to know the best part?

 The best part is that the System File Checker not only helps you fix the optional features problem but also any other Windows issues. In fact, it's one of the best [ways to repair corrupted Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) .

## 3\. Reset the Windows Update Components

 Windows Update Components include all the services, tasks, and programs that work together to make sure your Windows system is up-to-date and secure.

 Resetting the Windows Update components might help solve the issue with optional feature installation. Here's how you can reset the Windows Update components easily:

1. Open the Command Prompt utility as an administrator.
2. Type the following commands one after the other, pressing**Enter** after each one:

`net stop wuauserv  
net stop cryptSvc  
net stop bits  
net stop msiserver  
ren C:\Windows\SoftwareDistribution SoftwareDistribution.old  
ren C:\Windows\System32\catroot2 catroot2.old  
net start wuauserv  
net start cryptSvc  
net start bits  
net start msiserver`

 This command will stop the Windows Update services, rename the**SoftwareDistribution** and**catroot2** folders, and then restart the services. This can help reset the update process and fix any issues that might be causing problems with optional feature installation.

![Update Components Reset In CMD Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/update-components-reset-in-cmd.jpg)

 While the commands may look intimidating, you don't need to worry, as all the commands mentioned above will not cause any harm to your system.​​​​

## 4\. Run the Windows Update Troubleshooter

 If the Command Prompt method did not work for you, you can use the Windows Update Troubleshooter to reset update components. This tool can help identify and fix problems with the update process, including issues that might be preventing optional features from installing.

Follow these steps to run the update troubleshooter on Windows:

1. Press**Win + I** to launch the Settings app.
2. Scroll down and click**Troubleshoot > Other troubleshooters.**  
![Troubleshooter Settings In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/troubleshooter-settings-in-windows.jpg)
3. Click**Run** next to**Windows Update** to run the troubleshooter.  
![Other Troubleshooters In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/other-troubleshooters-in-windows.jpg)
4. Follow the prompts to complete the troubleshooting process.

 If you're using Windows 10, the Windows Update Troubleshooter is in**Settings > Update & Security >** **Troubleshoot > Windows Update** .

 The troubleshooter will begin scanning your system for any issues with the update process and will offer suggestions for how to fix them. So, you just need to follow the prompts, and then try [installing the optional features](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) again.

## 5\. Update Windows to the Latest Version

 If the issue with optional feature installation is related to outdated system files, you may be able to fix it by updating Windows to the latest version.

 Updating Windows can help ensure that you have the latest security patches, bug fixes, and system files, which can help resolve any issues you may be experiencing.

Here's how you can update Windows to the latest version:

1. Press**Win + I** to open the Settings app.
2. Click on**Windows** **Update > Check for updates** on Windows 11\. For Windows 10, click on **Update & Security > Windows Update > Check for Updates** .  
![Windows Update In Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-update-in-windows-11.jpg)

 That's it. Now, you can install any update that is available for your computer.

 By default, Windows automatically downloads and installs updates, but you can also check for updates manually by following the steps above.

## 6\. Restart the Windows Module Installer Service

 The Windows Module Installer service allows you to install, change, and remove Windows features and optional components. If it is not working properly, it can make it difficult to install optional features.

 Follow the below-given steps to restart the Windows Module Installer service:

1. Open Windows search and type**services** .
2. Select the best match to open the**Services** app.
3. Scroll down and find the**Windows Module Installer** service.
4. Right-click on the service and select**Restart** .  
![Windows Modules Installer Service In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-modules-installer-service.jpg)

 When you reset the module installer service, Windows tries to stop it and then start it again, which can help reset the installation process of optional features and fix any issues that might be causing problems.

 Once the service restarts, try installing the optional feature again, and it should work now.

## 7\. Restore Windows Features Using PowerShell

 If all the above methods fail to work, restoring Windows features is your last resort. So, if you are unable to use or install an optional Windows feature, you might be able to fix the problem by using PowerShell to restore a particular feature.

 Here are the steps for restoring Windows features using the PowerShell:

1. Press**Win + X** to open the Power User menu.
2. Click on**Windows PowerShell (Admin)** or**Terminal (Admin)** .
3. Type the following command and press**Enter** :  
Get-WindowsOptionalFeature -Online ![Get Optional Feature Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/get-optional-feature-command.jpg)  
 This command will show you the**FeatureName** and**State** of every optional Windows feature that you can use. Make sure to copy the "**FeatureName** " of the feature that you want to enable on Windows.
4. To turn on a certain feature, use the following command and replace "**FEATURENAME** " with the feature's name that you copied earlier:  
Enable-WindowsOptionalFeature -Online -FeatureName FEATURENAME ![Enable Optional Feature Command In PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/optional-feature-in-powershell.jpg)
5. Restart your computer for the changes to take effect.

 This will add the feature back to your system and should make it available for you to enable or disable in the features window.

 This method only allows you to restore a specific feature and, not all the features at once. So, you need to copy and paste the same command and edit the**FEATURENAME** every time.

 If these steps don't fix the problem, you may need to ask Microsoft or a technical support professional for more help.

## Get Back the Windows Optional Features

 Hopefully, the issue with optional features not installing on your system should be fixed now. In any case, it is important to keep your system up-to-date and to follow best practices for maintaining your computer properly to help prevent issues like this from occurring.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>



<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-exclusive-webcast-winners/"><u>[New] 2024 Approved  Exclusive Webcast Winners</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/carving-out-the-ultimate-tiktok-final-act-for-2024/"><u>Carving Out the Ultimate TikTok Final Act for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-network-issues-a-comprehensible-guide-for-windows-11-users/"><u>Navigating Network Issues: A Comprehensible Guide for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-a-stuck-recycle-bin-on-microsofts-latest-os/"><u>Reviving a Stuck Recycle Bin on Microsoft's Latest OS</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/in-2024-convert-mp4-to-mp3-top-tools-for-easy-audio-extraction/"><u>In 2024, Convert MP4 to MP3 Top Tools for Easy Audio Extraction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-solutions-at-fingertips-customizing-shortcuts-for-win-11-repairs/"><u>Speedy Solutions at Fingertips: Customizing Shortcuts for Win 11 Repairs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-fix-geforce-experience-on-windows-pcs/"><u>Quick Guide to Fix GeForce Experience on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-instructions-downloading-and-installing-msixbundle-packages/"><u>Step-by-Step Instructions: Downloading & Installing MSixbundle Packages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prime-pick-for-pen-notes-7-ultimate-windows-apps/"><u>Prime Pick for Pen Notes: 7 Ultimate Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/triumph-over-windows-11-theme-lockdown-a-registry-approach/"><u>Triumph Over Windows 11 Theme Lockdown: A Registry Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-power-of-network-configurations-in-windows-os/"><u>Unlock the Power of Network Configurations in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-windows-11-speed-start-up-enhancement-techniques/"><u>Unleash Windows 11 Speed: Start-Up Enhancement Techniques</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-quicktakes-why-videos-thrive-on-twitter-writes/"><u>[Updated] QuickTakes  Why Videos Thrive on Twitter' Writes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-tips-for-photoshopping-on-windows-11/"><u>Troubleshooting Tips for Photoshopping on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-solve-0xc0000001-on-windows-os/"><u>Steps to Solve 0XC0000001 on Windows OS</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-how-to-create-and-edit-videos-on-windows-11/"><u>2024 Approved  How to Create and Edit Videos on Windows 11</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-vertical-video-mastery-top-editing-apps-for-iphone-and-android/"><u>Updated In 2024, Vertical Video Mastery Top Editing Apps for iPhone and Android</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-pinnacle-fix-in-digital-dimensions/"><u>[New] Pinnacle Fix in Digital Dimensions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-high-dpi-screen-resolution-problems-on-pcs/"><u>Tackling High DPI Screen Resolution Problems on PCs</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-the-art-of-storytelling-integrating-captions-into-your-instagram-videos-for-2024/"><u>[Updated] The Art of Storytelling  Integrating Captions Into Your Instagram Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safeguard-against-unexpected-scroll-behavior-in-os/"><u>Safeguard Against Unexpected Scroll Behavior in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-a-frozen-xbox-app-in-windows-10/"><u>Unlocking a Frozen Xbox App in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-steps-to-resolve-onedrive-server-crashes/"><u>Swift Steps to Resolve OneDrive Server Crashes</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-convert-webm-to-mp3-best-tools-for-the-job/"><u>In 2024, Convert WebM to MP3 Best Tools for the Job</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redesigning-the-user-experience-in-win11-settings/"><u>Redesigning the User Experience in Win11 Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regenerating-system-icons-in-windows-os/"><u>Regenerating System Icons in Windows OS</u></a></li>
<li><a href="https://fix-guide.techidaily.com/oneplus-nord-ce-3-5g-bootloop-problem-how-to-fix-it-without-data-loss-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>OnePlus Nord CE 3 5G Bootloop Problem, How to Fix it Without Data Loss | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-risks-in-windows-11-service-deactivation/"><u>Understanding Risks in Windows 11 Service Deactivation</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-prime-mac-video-tools-apart-from-bandicam/"><u>[New] In 2024, Prime Mac Video Tools Apart From Bandicam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-usb-drive-problems-for-efficient-data-handling/"><u>Solving USB Drive Problems for Efficient Data Handling</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-the-digital-archivists-toolkit-downloading-videos-from-messenger-for-2024/"><u>[New] The Digital Archivist's Toolkit  Downloading Videos From Messenger for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-activate-folder-restrictions-in-windows/"><u>Step-by-Step Guide to Activate Folder Restrictions in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ultimate-guide-to-modify-mouses-double-click-speed/"><u>Ultimate Guide to Modify Mouse's Double-Click Speed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/organizing-files-optimizing-drives-defrag-for-win11-users/"><u>Organizing Files, Optimizing Drives: Defrag for Win11 Users</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-tecno-spark-20-proplus-frp-by-drfone-android/"><u>In 2024, Step-by-Step Tutorial How To Bypass Tecno Spark 20 Pro+ FRP</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-rapid-video-size-adjustment-a-beginners-guide/"><u>New In 2024, Rapid Video Size Adjustment A Beginners Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/scrutinizing-the-utility-of-windows-11-interface-components/"><u>Scrutinizing the Utility of Windows 11 Interface Components</u></a></li>
</ul></div>
