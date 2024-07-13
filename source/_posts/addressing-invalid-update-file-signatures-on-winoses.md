---
title: Addressing Invalid Update File Signatures on WinOSes
date: 2024-07-12T17:47:18.971Z
updated: 2024-07-13T17:47:18.971Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Invalid Update File Signatures on WinOSes
excerpt: This Article Describes Addressing Invalid Update File Signatures on WinOSes
keywords: Windows Validation Errors,OS Updates Signature Fix,WinOS Invalid Files,Update Corruption Solutions,Signature Verification Win,File Integrity WinOS,Erroneous Signatures Address
thumbnail: https://thmb.techidaily.com/75030bd59360efbfc2946329061573b90f37300b7251c4b711e0f5f10f28322c.jpg
---

## Addressing Invalid Update File Signatures on WinOSes

 Users frequently report Windows 11/10 update errors on software support forums. One such update issue reported is an error message that says, “Some update files aren’t signed.” Some users see that error message appear within Settings’ Windows Update tab when trying to update Windows.

 Windows updates fail to install when this issue occurs. This error usually includes either a 0x800b0109 or 0x800b0100 code after its message. This is how you can resolve the “Some update files aren’t signed” error 0x800b0109 on a Windows 11/10 PC.

## 1\. Utilize the Windows Update Troubleshooter

 The Windows Update troubleshooting tool is there to help you fix any issues encountered when trying to update Windows 11/10\. That troubleshooter doesn’t necessarily fix every update error, but it can at least resolve some issues.

 So, utilizing that troubleshooter is always worth a try, which you can access in Settings as covered within this guide to [running any troubleshooter on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/).

![The Windows Update troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-update-troubleshooter.jpg)

## 2\. Run Deployment Imaging and System File Scans

 System file corruption is among the [most common reasons for Windows update errors](https://www.makeuseof.com/reasons-why-windows-updates-fail/). For that reason, running a System File Checker scan to address system file corruption is a recommended troubleshooting method for error 0x800b0109\.

 It’s also advisable to utilize the Deployment Imaging and Servicing Management to repair possible Windows image corruption.

 Both Deployment Imaging and System File Checker are Command Prompt tools. You can run them by inputting and executing two commands within the Command Prompt. Our article on [repairing corrupted Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) includes instructions on how to utilize the SFC and DISM command-line tools.

![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-sfc-scannow.jpg)

## 3\. Check the Windows Update and BITS Services Are Enabled

 Windows Updates and Background Intelligent Transfer Service (BITS) are two services that need to be enabled for updates. So, check those services are correctly set like this:

1. Simultaneously press the **Windows** logo + **S** keys on your keyboard.
2. Enter the search phrase "services" to find the app with a matching title.
3. Click on **Services** inside the search results.
4. Double-click **Windows Update** to access settings for that service.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/services-window.jpg)
5. Set the **Startup type** setting to the **Automatic** option.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/startup-type-drop-down-menu.jpg)
6. Click **Start** (inside the properties windows) to run the Windows Update service.
7. Save the settings by pressing the **Apply** and **OK** buttons.
8. Double-click the **Background Intelligent Transfer Service** to view its settings.
9. Select a **Manual** startup option.
10. Click the **Start** option for the BITS service if it’s stopped.
11. Then click on the **Apply** and **OK** options to set that service’s options.

 If you find both services to be already enabled and running, try restarting them. You can do so by right-clicking the BITS and Windows Update service names and selecting a **Restart** option on their context menus.

## 4\. Reset Components for Windows Updates

 Resetting components for Windows updates will completely refresh the catroot2 and SoftwareDistribution folders, which store update data. This troubleshooting method also reregisters all DLL files for important update services. Applying such a potential resolution can fix corrupted components causing error 0x800b0109\.

 To apply this possible error 0x800b0109 resolution, check out our article on [resetting Windows update components](https://www.makeuseof.com/reset-windows-update-components/). That guide includes a command-line and batch file method. Creating and running a batch file is the quicker and more straightforward way to reset Windows update components.

## 5\. Deactivate Third-Party Security Software

 A third-party security (antivirus) app can potentially conflict with Windows update processes. This can happen when the antivirus protection of a security app locks files needed by Windows Update. It’s not something that happens often, but temporarily disable any third-party antivirus protection on your PC just in case.

 Security apps typically include options for disabling antivirus protection on their system tray context menus. Right-click your security app’s icon in Windows 11’s system tray area to find and select its option for temporarily disabling the antivirus shield. Then, return to the Settings app to see if error 0x800b0109 still happens with the antivirus shield disabled.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

## 6\. Erase the Windows Update Key

 Deleting the Windows Update registry key is a potential resolution some users confirm to fix error 0x800b0109\. However, we always recommend [backing up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or saving a system restoration point before deleting registry keys.

 When you’ve done that, try deleting the Windows Update key like this:

1. Open Run, accessible by pressing **Windows** logo key + **R**, and type a **regedit** command into that accessory.
2. Select Run’s **OK** option to open the Registry Editor.
3. Next, clear the registry address bar and input this key path there:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\WindowsUpdate`
4. Right-click the WindowsUpdate registry key to select **Delete**.  
![The Delete context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-delete-option-1.jpg)
5. Click **Yes** when prompted for confirmation to delete the key.  
![The Confirm Key Delete prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-key-confirmation-1.jpg)

 Thereafter, it’s also recommended to restart the Windows Update and BITS services. To do so, open Services as covered in the first three steps of resolution three. Then, select the **Restart** context menu options for Windows Update and BITS.

## 7\. Try Downloading the Failed Update From Microsoft Update Catalog

 If error 0x800b0109 still isn’t fixed after applying the potential resolutions above, try going around it by manually downloading the affected update from [Microsoft Update Catalog](https://www.catalog.update.microsoft.com/Home.aspx). Then, you can install the update with an MSU file downloaded from there.

 You will first need to identify what update is failing as follows:

1. Simultaneously press your keyboard’s **Windows** logo + **I** keys to access Settings.
2. Click **Windows Update** (or **Update & Security**) in Settings.
3. Select **Update history** to view installed and failed updates.  
![The update history in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-history4.jpg)
4. Note down the KB code for your recently failed Windows update.

 Then, you can find and download that failed update on the Microsoft Update Catalog website. This article about [updating Windows manually](https://www.makeuseof.com/update-windows-manually/) includes instructions for utilizing the Microsoft Update Catalog.

## 8\. Apply an In-Place Windows Upgrade

 An in-place Windows upgrade is the last resort for fixing error 0x800b0109\. Applying this potential resolution will reinstall Windows on your PC with its latest ISO file. The installation of a fresh Windows copy will likely resolve other issues causing the 0x800b0109 update error that other potential solutions couldn’t fix.

 The good thing about an in-place upgrade is that it won’t eradicate your installed software or user files. This [how-to perform an in-place upgrade](https://www.makeuseof.com/in-place-upgrade-windows-11/) guide tells you how to apply this potential solution for Windows 11\. The steps are quite similar for Windows 10, but you’ll need to download its ISO with the Media Creation Tool available on this [Microsoft page](https://www.microsoft.com/en-gb/software-download/windows10).

![The Windows 10 Media Creation tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-10-setup-window.jpg)

## Get Windows Updated Again

 There isn’t a surefire way to fix error 0x800b0109 since there are varied possible reasons for that Windows 11/10 issue occurring. However, it’s likely at least one of the eight potential resolutions in this guide will fix that update issue on your PC.

 Some of the best third-party Windows repair tools might also be helpful for resolving the “Some update files aren’t signed” error.

 Windows updates fail to install when this issue occurs. This error usually includes either a 0x800b0109 or 0x800b0100 code after its message. This is how you can resolve the “Some update files aren’t signed” error 0x800b0109 on a Windows 11/10 PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/leveraging-the-power-of-combined-android-and-windows-11-displays/"><u>Leveraging the Power of Combined Android & Windows 11 Displays</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-hide-the-power-button-from-the-start-menu-on-windows-11-and-11/"><u>How to Hide the Power Button From the Start Menu on Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-the-pulse-of-internet-stability-at-work/"><u>Keeping the Pulse of Internet Stability at Work</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-superuser-access-a-step-by-step-guide/"><u>Mastering Superuser Access: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-computer-game-learning-windows-shorthand/"><u>Elevate Your Computer Game: Learning Windows Shorthand</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-tackle-unknown-hardware-in-windows-1011-os/"><u>How to Tackle Unknown Hardware in Windows 10/11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-advice-on-configuring-the-taskbar-for-windows-11-slate-devices/"><u>Expert Advice on Configuring the Taskbar for Windows 11 Slate Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-tackle-non-responsive-function-keys-for-brighness-on-windows-11/"><u>Methods to Tackle Non-Responsive Function Keys for Brighness on Windows 11</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-reel-in-real-time-the-top-5-innovative-recorder-apps-for-browsers/"><u>[New] In 2024, Reel in Real-Time  The Top 5 Innovative Recorder Apps for Browsers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-fullscreen-glitches-with-ease-on-windows/"><u>Navigate Fullscreen Glitches with Ease on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-your-downloads-with-these-5-windows-clients/"><u>Maximize Your Downloads with These 5 Windows Clients</u></a></li>
<li><a href="https://howto.techidaily.com/11-ways-to-fix-it-when-my-xiaomi-13t-wont-charge-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Ways to Fix it When My Xiaomi 13T Wont Charge | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-view-and-clear-the-windows-10-activity-history/"><u>How to View and Clear the Windows 10 Activity History</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-convenient-hp-recording-strategies-for-seamless-productivity/"><u>[New] Convenient HP Recording Strategies for Seamless Productivity</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-from-humble-beginnings-to-sponsored-success-channels-blueprint/"><u>[Updated] 2024 Approved  From Humble Beginnings to Sponsored Success  Channels' Blueprint</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-installing-intel-wi-fi-and-lan-drivers-in-windows/"><u>Guide: Installing Intel Wi-Fi & LAN Drivers in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/empowering-aesthetics-activating-color-management-in-win11/"><u>Empowering Aesthetics: Activating Color Management in Win11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-a-complete-guide-to-oem-unlocking-on-vivo-x100-by-drfone-android/"><u>In 2024, A Complete Guide To OEM Unlocking on Vivo X100</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-copilot-unveiled-revolutionizing-the-development-process/"><u>Microsoft Copilot Unveiled: Revolutionizing the Development Process</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-easy-pathway-to-fish-chatter-alteration-within-win-environment/"><u>[New] Easy Pathway to Fish Chatter Alteration Within Win Environment</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-audacity-setup-guide-for-ubuntu-installs-uninstalls-and-troubleshooting-tips-for-2024/"><u>Updated Audacity Setup Guide for Ubuntu Installs, Uninstalls & Troubleshooting Tips for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-how-to-archive-snaps-from-android-plus-mac-systems/"><u>2024 Approved  How to Archive Snaps From Android + Mac Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reactivate-the-forgotten-windows-start-menu/"><u>How to Reactivate the Forgotten Windows Start Menu</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-pro-audio-on-your-device-a-comprehensive-review-of-the-top-8-ios-compatible-daw-apps/"><u>In 2024, Pro Audio on Your Device A Comprehensive Review of the Top 8 iOS-Compatible DAW Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leading-the-way-in-qr-decoding-with-your-windows-machine/"><u>Leading the Way in QR Decoding with Your Windows Machine</u></a></li>
<li><a href="https://some-guidance.techidaily.com/transforming-unboxing-into-art-for-2024/"><u>Transforming Unboxing Into Art for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expedite-your-pcs-performance-windows-11-cleansing-tips/"><u>Expedite Your PC's Performance: Windows 11 Cleansing Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-nonstop-techsign-in-issues-in-ms-teams-windows/"><u>Fixing Nonstop TechSign In Issues in MS Teams Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-effortlessly-bypass-pin-in-windows-11-projections/"><u>Navigate Effortlessly: Bypass PIN in Windows 11 Projections</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-troubleshooting-obs-frame-loss/"><u>In 2024, Troubleshooting OBS Frame Loss</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-transparent-taskbars-on-win11/"><u>Mastering the Art of Transparent Taskbars on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/five-keys-to-unlocking-email-access-issues-in-windows-11-mail-service/"><u>Five Keys to Unlocking Email Access Issues in Windows 11 Mail Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-speech-recognition-initialization-hiccup/"><u>Fixing Windows Speech Recognition Initialization Hiccup</u></a></li>
<li><a href="https://ai-voice.techidaily.com/in-2024-best-celebrity-voice-generator-tools-you-cannot-miss/"><u>In 2024, Best Celebrity Voice Generator Tools You Cannot Miss</u></a></li>
<li><a href="https://win11-tips.techidaily.com/epic-games-launcher-handling-lost-security-code-issues-on-pc/"><u>Epic Games Launcher: Handling Lost Security Code Issues on PC</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-frosty-frontiers-winter-games-apex-moments/"><u>2024 Approved  Frosty Frontiers  Winter Games Apex Moments</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-vlc-tutorial-the-art-of-video-angling-for-2024/"><u>[Updated] VLC Tutorial  The Art of Video Angling for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-change-the-windows-spotlight-picture-whenever-you-want/"><u>How to Change the Windows Spotlight Picture Whenever You Want</u></a></li>
<li><a href="https://review-topics.techidaily.com/motorola-moto-g73-5g-tutorial-bypass-lock-screen-security-password-pin-fingerprint-pattern-by-drfone-android-unlock-android-unlock/"><u>Motorola Moto G73 5G Tutorial - Bypass Lock Screen,Security Password Pin,Fingerprint,Pattern</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-organize-your-notes-visually-with-obsidian-canvas/"><u>How to Organize Your Notes Visually With Obsidian Canvas</u></a></li>
</ul></div>
