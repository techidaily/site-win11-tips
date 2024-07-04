---
title: Eliminating Unbootable Windows VMs via VMware in Win11
date: 2024-06-25T16:17:34.891Z
updated: 2024-06-26T16:17:34.891Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminating Unbootable Windows VMs via VMware in Win11
excerpt: This Article Describes Eliminating Unbootable Windows VMs via VMware in Win11
keywords: Windows Boot Issue Resolution,VMware VM Fix Strategies,Win11 VM Stability Improvement,Unbootable VMs Removal Tips,Secure Windows Virtual Machines,Optimize Win11 VM Performance,Troubleshoot Boot Failures in VMware
thumbnail: https://thmb.techidaily.com/3a6dbb861d55872fdf4ced41ee2862ae3932a3822bc0678be6a1186e4efd451b.jpg
---

## Eliminating Unbootable Windows VMs via VMware in Win11

 Virtual machines enable you to try out multiple operating systems without removing your main operating system. VMware is one such popular third-party hypervisor that supports multiple operating systems. However, some users face the 'Failed to start the virtual machine' error when they power on any virtual machine in VMware.

 As a result, they are unable to launch any virtual machine in VMware and are stuck at the error screen. We will discuss multiple methods to resolve this issue and help you successfully launch the virtual machine. Let’s begin.

## 1\. Close and Restart the VMWare Virtual Machine

 VMware can face a glitch and can face issues while launching the virtual machines. So, you must completely close the app and run it with administrator rights. Here’s how:

1. Right-click on the **Start** button to launch the Power User menu. Click on the **Task Manager** option.
2. Click on the search bar and type **vmware**. Press the **Enter** key to search for all the related processes.
3. Right-click on the process and select the **End Task** option.  
![Terminate and restart VMware](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/terminate-and-restart-vmware.jpg)
4. Similarly, close all the related processes and then close the Task Manager window.
5. Press the **Win** key, type **vmware**, and click on the **Run as administrator** option.
6. The User Account Control window will open. Click on the **Yes** button.
7. Try to launch a virtual machine and check if you face the error again.

## 2\. Check If Virtualization is Active

 Every virtualization program including VMware needs hardware virtualization to work on a Windows PC. So, if you have turned off virtualization from BIOS, you must re-enable it. Repeat the following steps:

1. **Restart** your Windows PC.
2. Repeatedly mash the designated **F-key** (or even **Esc** key in some cases) to enter the BIOS. You can find out the designated F-key for your PC by searching its model name.
3. Switch to the **Advanced Settings** page.
4. Locate the **Hardware Virtualization** settings. In our Asus PC, it shows up as “**SVM**” mode, but you may see other names like **VT-x**, **AMD-V**, or **Vanderpool**. Use the **arrow** key to highlight and press the **Enter** key to enable the feature.  
![Enable hardware virtualization in BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/enable-hardware-virtualization-in-bios.jpg)
5. Press the **F10** key to save the changes and exit the BIOS.
6. Boot to the desktop and launch VMware. Check if you can launch a virtual machine without any error.

## 3\. Update VMware App

 An outdated and buggy build of VMware can cause issues with certain features. So, you must update the app to install the latest build and fix issues with new Windows updates. Here’s how to do it:

1. Press the **Win** key and type **vmware**. Then press the **Enter** key to open the app.
2. Go to the top menu and click on the **Player** button.
3. Navigate to the **Help > Software updates** option.
4. Click on the **Check for updates** button.  
![Updating the VMware app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/updating-the-vmware-app.jpg)
5. Wait for the utility to search the servers for new updates if any. Download and install the updates on your PC.
6. **Restart** your PC and launch VMware. Power on a virtual machine and check if the error pops up or not.

## 4\. Disable Memory Integrity in Windows Security

 Memory Integrity is a feature listed under the Core Isolation setting in the Windows Security app. It protects high-security processes from malware and requires hardware virtualization. Since hardware virtualization can only be used by one program at a time, VMware can encounter errors when you power on a virtual machine.

 So, you must disable memory integrity on your PC. Here’s how to do it:

1. Press the **Win** key, type **Windows Security**, and press the **Enter** key.
2. Click on the **Device Security** option.
3. Locate the **Core Isolation** section and click on the **Core Isolation details** option.
4. Now, click on the **toggle** below **Memory Integrity** to disable the feature.  
![Disable Memory Integrity](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disable-memory-integrity.jpg)
5. **Close** the Windows Security app.

## 5\. Remove Other Windows Virtualization Features

 VMware relies on the Windows Hypervisor Platform feature which offers support for third-party hypervisors. But if you have other Windows virtualization features also installed on your PC, it can conflict with VMware’s virtual machine. So, you must remove these features. Repeat the following steps:

1. Press **Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **appwiz.cpl** and press the **Enter** key.
2. The Programs and Features window will open. Click on the **Turn Windows features on or off** option.
3. Scroll down and uncheck **Hyper-V**, **Virtual Machine Platform**, and **Windows Subsystem for Linux** features in the list.
4. Click on the **OK** button.  
![Remove other virtualization features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/remove-other-virtualization-features.jpg)
5. Now, click on the **Restart now** button to apply the changes and remove all these features from your PC.

## 6\. Disable VBS

 Virtualization-based security can interfere with third-party hypervisors, so you must disable it. Check out [how to disable VBS to increase performance in Windows 11](https://www.makeuseof.com/windows-11-disable-vbs/) for more information. After disabling VBS, launch VMware and run a virtual machine to check if the 'Failed to Start the Virtual Machine' error persists.

## 7\. Remove Any Other Virtualization-Based Program

 If you use other third-party hypervisors like VirtualBox on your PC, you must uninstall them for some time and then run VMware. You won’t lose any virtual machines because you are only removing the hypervisor program. The virtual machine files will remain intact.

 Repeat the following steps to remove other hypervisors:

1. Press **Win + R** to open the Run dialog box. Type **appwiz.cpl** in the text box and press the **Enter** key.
2. The Programs and Features window will launch. Scroll down and locate the other third-party hypervisors in the list.
3. **Right-click** on the program and click on the **Uninstall** option.
4. Follow the on-screen instructions to remove the program from your computer.

## 8\. Reinstall the VMware App

 If the existing installation of VMware is corrupt or crucial files are missing from the installation folder, you must reinstall the app. It will remove all the installation files and install a new copy of the app on your PC.

 Repeat the following steps to install VMware using Winget:

1. Right-click on the **Start** button to open the **Power User** menu. Click on the **Terminal (Admin)** option.
2. The User Account Control window will pop up. Click on the **Yes** button.
3. Type the following command and press the **Enter** key to uninstall VMware:  
`Winget uninstall VMware.WorkstationPlayer`
4. Wait for Winget to remove the app package from your PC.
5. Now, execute the following command to install VMware from the Winget repository:  
`Winget install VMware.WorkstationPlayer`
6. It will take a while to download and install the app on your PC.  
![Reinstalling VMware](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/reinstalling-vmware.jpg)
7. **Close** the Terminal app window.
8. Launch VMware and power on a virtual machine to check if it runs without any issues now.

## 9\. Use System Restore

 If VMware was running fine on your PC before installing a new update or making changes to your PC, you can [use System Restore](https://www.makeuseof.com/use-system-restore-windows/) to revert to an earlier state. All your personal files will stay unaffected, and you won’t have to reset your PC for an app.

## Get VMware Working Again

 These were the nine methods to fix VMware’s 'Failed to Start the Virtual Machine' error on Windows 11\. Check virtualization settings in BIOS, update the app, and disable memory integrity. After that, disable VBS, uninstall optional virtualization features, and reinstall the app to fix the issue.

 As a result, they are unable to launch any virtual machine in VMware and are stuck at the error screen. We will discuss multiple methods to resolve this issue and help you successfully launch the virtual machine. Let’s begin.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/personalizing-problem-solving-in-windows-1011-with-shortcuts/"><u>Personalizing Problem-Solving in Windows 10/11 with Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-c0000005-error-on-your-pcs-operating-system/"><u>Remedy for C0000005 Error on Your PC's Operating System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-windows-sandbox-no-hypervisor-was-found-0xc0351000-error/"><u>How to Fix the Windows Sandbox No Hypervisor Was Found 0XC0351000 Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-more-than-one-antivirus-isnt-ideal-for-windows-users/"><u>Why More Than One Antivirus Isn't Ideal for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/workaround-cease-discord-startup-and-update-checks-in-windows/"><u>Workaround: Cease Discord Startup and Update Checks in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strengthening-game-accessibility-winning-over-ea-errors/"><u>Strengthening Game Accessibility: Winning Over EA Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-your-windows-experience-with-customized-fn-keys-settings/"><u>Tailor Your Windows Experience with Customized FN Keys Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-directdraw-errors-with-ease-on-new-windows-oses/"><u>Fixing DirectDraw Errors with Ease on New Windows OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-files-directories-for-game-access/"><u>Winning at Files: Directories for Game Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-endless-login-prompts-on-windows-os/"><u>Bypassing Endless Login Prompts on Windows OS</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-realme-11x-5g-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Realme 11X 5G to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-windows-and-mac-friendly-techniques-for-fb-video-download/"><u>[New] 2024 Approved  Windows & Mac-Friendly Techniques for FB Video Download</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-best-discord-font-generators-onlineiphoneandroid/"><u>[New] 2024 Approved  Best Discord Font Generators [Online/iPhone/Android]</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-pokemon-go-cooldown-chart-on-nokia-c02-drfone-by-drfone-virtual-android/"><u>In 2024, Pokémon Go Cooldown Chart On Nokia C02 | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-superior-options-other-than-obs-for-live-recordings/"><u>In 2024, Superior Options Other than OBS for Live Recordings</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-identify-missing-drivers-with-windows-device-manager-on-windows-10-and-7-by-drivereasy-guide/"><u>How to identify missing drivers with Windows Device Manager on Windows 10 & 7</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-top-screen-capture-apps-for-idevices/"><u>[New] Top Screen Capture Apps for iDevices</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-select-macos-big-sur-11-apps-for-seamless-video-editing/"><u>[Updated] Select MacOS Big Sur 11 Apps for Seamless Video Editing</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-mastering-the-art-of-fcp-freedom/"><u>2024 Approved  Mastering the Art of FCP Freedom</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-expert-tips-for-changing-mac-screenshot-formats/"><u>[New] Expert Tips for Changing Mac Screenshot Formats</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>