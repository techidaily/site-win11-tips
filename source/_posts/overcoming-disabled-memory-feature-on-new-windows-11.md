---
title: Overcoming Disabled Memory Feature on New Windows 11
date: 2024-06-25T17:10:03.345Z
updated: 2024-06-26T17:10:03.345Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Disabled Memory Feature on New Windows 11
excerpt: This Article Describes Overcoming Disabled Memory Feature on New Windows 11
keywords: Win11 Remembrance Fix,Memory Recovery Windows 11,Enhance Window's Mem,Boosting Memory in Win11,Windows 11 Cognitive Aid,Improve Windows Memory Feat,Revive Memory on New Windows
thumbnail: https://thmb.techidaily.com/43a1f72d8140b4852b3ec1b168bf1a5fdf9e93b16a9fa8da6c72d7e20d694e32.jpg
---

## Overcoming Disabled Memory Feature on New Windows 11

 Does the memory integrity feature in Windows Security appear grayed out? Is your PC saying, "Memory integrity is off. Your device may be vulnerable," but you can't turn on the toggle? The memory integrity feature prevents malicious software from accessing high-security processes when your device is invaded by malware.

 But what causes this feature to be grayed out? In this article, we'll discuss why you cannot turn on this feature and how to identify and fix the underlying problem.

## What Causes Memory Integrity to Become Grayed Out on Windows 11?

 The primary cause of memory integrity not working on Windows 11 is your drivers. When they become outdated or corrupt, you are likely to run into this problem. Likewise, if your system is outfitted with incompatible drivers, the memory integrity feature may stop working.

 The error message itself usually explains where the problem lies, so fixing the problem is simple. You can fix faulty drivers, repair corrupted system files, update your operating system, revert an update, or remove incompatible drivers. Let's discuss some fixes to get the feature working again.

 As you apply each fix listed below, go to the Windows Security app and try enabling memory integrity again. It will help you identify what was causing the problem and fix it quickly without going through unnecessary fixes.

## 1\. Identify and Fix Driver Issues

 In most cases, the primary cause of the problem under discussion is outdated or incompatible drivers, so let's start by checking your drivers. To begin with, uninstall any third-party drivers you installed recently. After that, open the **Windows Security** app, click on the **Device security** tab from the left sidebar, and click on **Core isolation details**.

![Clicking on the Core Isolation Details Option in the Device Security Tab of Windows Security App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/1-Clicking-on-the-Core-Isolation-Details-Option-in-the-Device-Security-Tab-of-Windows-Security-App.jpg)

 Here, enable Memory integrity. If you encounter an error saying, **"Resolve any driver incompatibilities and scan again,"** click on the **Review incompatible drivers** link.

![Clicking on the Review Incompatible Drivers Link in Core Isolation Settings of Windows Security App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/2-Clicking-on-the-Review-Incompatible-Drivers-Link-in-Core-Isolation-Settings-of-Windows-Security-App.jpg)

 Then, note down any drivers Memory Integrity suspects are incompatible.

![Noting Down the List of Incompatible Drivers in the Core Isolation Settings Within Windows Security App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/3-Noting-Down-the-List-of-Incompatible-Drivers-in-the-Core-Isolation-Settings-Within-Windows-Security-App.jpg)

 Following the above checks, follow these steps to rule out driver-related problems:

1. Right-click on the Windows **Start** button and select **Device Manager**.
2. Go to the **View** tab and click **Show hidden devices**.  
![Clicking on the Show Hidden Devices Option in the View Tab Dropdown Menu Of Windows Device Manager App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/4-Clicking-on-the-Show-Hidden-Devices-Option-in-the-View-Tab-Dropdown-Menu-Of-Windows-Device-Manager-App.jpg)
3. Look for the device that has a yellow triangle on it with an exclamation mark inside it or the driver(s) with problems indicated by the Memory integrity.
4. Right-click on that device and select **Update driver**.  
![Clicking on the Update Driver Option by Right-clicking on the Incompatible Driver in Windows Device Manager App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/5-Clicking-on-the-Update-Driver-Option-by-Right-clicking-on-the-Incompatible-Driver-in-Windows-Device-Manager-App.jpg)
5. If updating the driver does not solve the problem, right-click it and select **Properties**.
6. Under the **General** tab, read the message in the **Device status** box.  
![Checking the Message in the Device Status Box Under the General Tab of Properties Window of Driver in Windows Device Manager App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/6-Checking-the-Message-in-the-Device-Status-Box-Under-the-General-Tab-of-Properties-Window-of-Driver-in-Windows-Device-Manager-App.jpg)
7. Take note of the error code and visit the [official Microsoft Support documentation](https://support.microsoft.com/en-us/topic/error-codes-in-device-manager-in-windows-524e9e89-4dee-8883-0afa-6bca0456324e) where all Device Manager-related errors are listed.
8. Find the relevant code information and apply the Microsoft recommended fix to fix the problem.

 What if applying the Microsoft recommended fix doesn't fix the problem with the driver, or there is no driver with a yellow triangle? In that case, you'll have to use third-party software to locate and uninstall the incompatible or corrupt driver.

## 2\. Find and Uninstall Incompatible Drivers

 If you cannot locate the incompatible driver in Device Manager, use a third-party program, such as Autoruns, to identify corrupt or incompatible drivers and uninstall them.

 You can follow these steps to do that:

1. Download **Autoruns** from the [Microsoft website](https://learn.microsoft.com/en-us/sysinternals/downloads/autoruns).
2. Unzip the compressed file.
3. To run the app as an administrator, right-click on its executable file and select **Run as administrator**.
4. Go to the **Drivers** tab.
5. The drivers with issues will be highlighted, so locate them.  
![Checking the Corrupt Drivers Highlighted in the Autoruns Software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/7-Clicking-on-the-Run-as-Administrator-Option-by-Right-clicking-on-the-Autoruns-Executable-File-in-Windows-File-Explorer.jpg)
6. Once they have been located, uncheck the box to disable them.  
![Unchecking the Box for the Incompatible Driver in the Drivers Tab of Autoruns App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/8-Unchecking-the-Box-for-the-Incompatible-Driver-in-the-Drivers-Tab-of-Autoruns-App.jpg)
7. If any driver gives an error when disabling, right-click it and select **Delete**.
8. Install the latest drivers from the official website or reboot your device to let Windows install them automatically.

 If you can't locate drivers identified as incompatible by Memory integrity before, the Autoruns app will facilitate finding and removing them.

## 3\. Uninstall Relevant Apps

 If uninstalling the incompatible drivers does not work, you should uninstall the apps or software you installed from the same manufacturer as the drivers. Follow these steps to do that:

1. Right-click on the Windows **Start** button and select **Apps and Features**.  
![Clicking on the Apps and Features by Right-clicking on the Windows Start Button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/9-Clicking-on-the-Apps-and-Features-by-Right-clicking-on-the-Windows-Start-Button.jpg)
2. In the list of installed apps, locate the software from the same manufacturer.
3. Upon finding them, click on the **three vertical dots** next to them and select **Uninstall**.  
![Clicking on the Uninstall Button After Clicking on the Three Vertical Dots Next to Software in the Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/10-Clicking-on-the-Uninstall-Button-After-Clicking-on-the-Three-Vertical-Dots-Next-to-Software-in-the-Windows-Settings-App.jpg)

 Uninstalling the relevant apps from the same manufacturer should resolve the issue. If it does not, ensure it isn't a Windows Update issue.

## 4\. Fix Update-Related Issues

 If incompatible or corrupt drivers aren't the problem, you should ensure your system is up-to-date and no updates are pending. To do this, right-click on the Windows **Start** button and select **Settings**. Next, navigate to **Windows Update** and click the **Check for updates** button on the right.

![Check for Updates Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Check-for-Updates-Windows.jpg)

 If they are paused, click **Resume updates** to let Windows update your system.

![Resuming Windows Update by Clicking on Resume Updates Button in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Image-4-Resuming-Windows-Update-by-Clicking-on-Resume-Button-in-Windows-Settings-App.jpg)

 Moreover, if you've encountered a problem after installing an update recently, you should uninstall it. Our guide on [uninstalling updates in Windows 10 and 11](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) explains how to do it. If pending or recently installed updates are not to blame, apply the next fix.

## 5\. Fix Corrupt System Files

 Corrupt system files are also a major cause of unforeseen issues with Windows features. The Memory integrity feature may have stopped working after a virus invaded your device and corrupted your system files. Thus, you must ensure that your system files are intact to rule out this possibility. An SFC scan can be helpful in this case.

 Search for **"Command Prompt"** in Windows Search, right-click on the **Command Prompt** in search results and click **Run as administrator**. Then type **"SFC /scannow"** and press **Enter**.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/sfc-scannow-command-1.jpg)

 Once the scan is complete, refer to our guide on repairing corrupt system files with Windows built-in tools so you can properly analyze the results.

## 6\. Reset the Windows Security App

 Issues with the Windows Security app can also interfere with the functionality of security features, like memory integrity.

 One way to rule out such issues is to reset the Windows Security app. Keep one caveat in mind, though: resetting Windows Security will revert any security customizations you've made to date. If you don't mind that, you can reset Windows Security.

 The process of resetting Windows Security is similar to [resetting any other Windows app](https://www.makeuseof.com/windows-reset-app/). Do that, and hopefully, the grayed-out memory integrity problem will resolve itself.

## 7\. Alternative Method to Enable the Memory Integrity Feature

 Using the Windows Security app isn't the only way to enable Windows' memory integrity feature. You can also adjust this setting within Registry Editor, which lets you access and modify Windows OS configuration settings. Therefore, if you are unable to turn on this feature from Windows Security, try enabling it from the Registry Editor.

 Follow these steps to enable the memory integrity feature from Registry Editor:

1. Type **"Registry Editor"** in Windows Search and open the **Registry Editor**.
2. Navigate to the following path:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\DeviceGuard\Scenarios\HypervisorEnforcedCodeIntegrity`
3. Right-click on the **Enabled** key in the right pane and select **Modify...**
4. Enter **"1"** under **Value data** if it is not already there.  
![Tweaking a Key Related to Memory Integrity in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/tweaking-a-key-realted-to-memory-integrity-in-windows-registry-editor.jpg)

 Misconfiguring keys in the Registry Editor can have unintended consequences. If you are unfamiliar with tweaking the registry, you can skip this step.

## Turn On the Memory Integrity Feature Again

 Memory integrity is a critical security feature, and if it is not enabled, it can seriously compromise the security of your device. Hopefully, by applying the fixes mentioned in the article, you will solve the problem and easily turn on Memory Integrity.

 But what causes this feature to be grayed out? In this article, we'll discuss why you cannot turn on this feature and how to identify and fix the underlying problem.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/trouble-locating-astra-pilot-help-for-windows-11-pcs/"><u>Trouble Locating Astra Pilot? Help For Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-control-over-file-explorer-on-stable-windows-11/"><u>Regain Control Over File Explorer on Stable Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ten-clear-indicators-of-pc-needs-a-factory-start/"><u>Ten Clear Indicators of PC Needs a Factory Start</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-application-was-unable-to-start-0xc000003e-error-in-windows-11-and-11/"><u>How to Fix “The Application Was Unable to Start” 0Xc000003e Error in Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-tablet-navigation-a-guide-to-windows-11s-taskbar/"><u>Optimizing Tablet Navigation: A Guide to Windows 11'S Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-0x0000011b-operation-failure-on-windows-11/"><u>Correcting 0X0000011B Operation Failure on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-users-guide-to-managing-monitor-luminosity/"><u>Win Users Guide to Managing Monitor Luminosity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ways-to-wipe-old-windows-protection-markers-from-microsofts-record/"><u>Ways to Wipe Old Windows Protection Markers From Microsoft's Record</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-forth-invisible-5ghz-connections-with-these-fixes/"><u>Bring Forth Invisible 5GHz Connections with These Fixes</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-not-working-on-tecno-camon-20-premier-5g-8-solutions-inside-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Not Working On Tecno Camon 20 Premier 5G? 8 Solutions Inside | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/learning-luminaries-leading-ed-tutorials-online-for-2024/"><u>Learning Luminaries  Leading Ed Tutorials Online for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-send-and-fake-live-location-on-facebook-messenger-of-your-nubia-red-magic-8s-proplus-drfone-by-drfone-virtual-android/"><u>In 2024, How to Send and Fake Live Location on Facebook Messenger Of your Nubia Red Magic 8S Pro+ | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-ultimate-kinemaster-guide-to-green-screening/"><u>The Ultimate KineMaster Guide to Green Screening</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-become-a-yt-hub-pro-complete-guide-revealed-for-2024/"><u>[New] Become a YT Hub Pro  Complete Guide Revealed for 2024</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-samsung-galaxy-m14-4g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Samsung Galaxy M14 4G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/the-best-of-the-best-3d-video-production-tools-you-must-use/"><u>The Best of the Best 3D Video Production Tools You Must Use</u></a></li>
<li><a href="https://youtube-web.techidaily.com/he-ultimate-pathway-to-prominence-on-youtube-channel-showcase/"><u>[New] The Ultimate Pathway to Prominence on YouTube  Channel Showcase</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-superior-20-anime-song-intros/"><u>2024 Approved  Superior 20 Anime Song Intros</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-how-to-use-speed-ramping-to-create-an-intense-action-footage/"><u>New How To Use Speed Ramping to Create an Intense Action Footage</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>