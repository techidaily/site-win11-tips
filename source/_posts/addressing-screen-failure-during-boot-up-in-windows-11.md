---
title: Addressing Screen Failure During Boot-Up in Windows 11
date: 2024-07-12T17:23:11.800Z
updated: 2024-07-13T17:23:11.800Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Screen Failure During Boot-Up in Windows 11
excerpt: This Article Describes Addressing Screen Failure During Boot-Up in Windows 11
keywords: Win11 Boot Failure,Screen Freeze Bootup,Bootup Display Error,Windows 11 Start Glitch,Boot Screen Issue,Windows 11 Booting,Boot Up Screen Problem
thumbnail: https://thmb.techidaily.com/74732f3286f05f088e049d5a5051d94a307e70b489a1cfb414ed825a2ed00d16.jpg
---

## Addressing Screen Failure During Boot-Up in Windows 11

 The “display driver failed to start” error message usually appears when you try to launch a game on Windows. The error message appears in the form of a Windows notification above the system tray area. When this error occurs, it causes your screen to go completely black. Sometimes it will recover, but sometimes it will require a hard reset.

 When this error is at its worst, it can prevent you from playing your favorite games. As such, here is how you can fix the “display driver failed to start” error on a Windows 10 or 11 PC.

## 1\. Perform Some Display Driver-Related Fixes

 The error message points to your display driver as the main culprit. As such, before you try anything else, you can try these display driver-related fixes to see if they do the job.

### Roll Back the Latest Graphics Driver Update
![The Roll Back Driver option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/roll-back-driver-button.jpg)

 If your graphics card’s driver has recently been updated, try rolling back to the old GPU driver. A **Roll Back Driver** option is usually only available for a short time (typically a few days) after updating a driver. Check out our guide to [rolling back drivers in Windows](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) for further details about how to apply this potential resolution.

### Install the Latest Driver for Your PC’s Graphics Card

 People plagued with this error message have confirmed that updating your graphics drivers is a good solution for the “display driver failed to start” error. And while Windows usually handles driver updates through Windows Update, it sometimes won't update NVIDIA and AMD GPU drivers.

 You can update your graphics card’s driver yourself with the methods discussed in our guide to [updating GPU drivers on Windows](http://www.makeuseof.com/update-graphics-drivers-in-windows-10/).

### Reinstall Your Graphics Driver

 If your PC’s GPU already has the newest graphics driver available, consider reinstalling the graphics driver. It's best to do a clean install to ensure your GPU's driver is back to its factory defaults.

 Check out [how to cleanly install and reinstall GPU drivers on Windows](https://www.makeuseof.com/how-to-cleanly-install-and-reinstall-gpu-drivers-on-windows/) for more information.

## 2\. Utilize the Hardware and Devices Troubleshooter

 Windows has a Hardware and Devices troubleshooter that can help resolve the “display driver failed to start” error. This troubleshooting tool is no longer available within Settings or Control Panel, but it is still accessible via Command Prompt.

 You can access and run the Hardware and Devices troubleshooting utility like this:

1. First, locate the Command Prompt by pressing **Win + S**, typing "cmd," and clicking on **Command Prompt**.
2. Enter and execute the Hardware and Devices command:  
`msdt.exe -id DeviceDiagnostic`
3. Click **Next** to start the troubleshooting.  
![The Hardware and Devices troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/hardware-and-devices-troubleshooter-troubleshooter-2.jpg)
4. Select **Apply this fix** to rectify any issues Windows finds.

## 3\. Lower the Windows Visual Effect Settings

 Windows has various visual effect settings that can affect performance. Having too many visual effects enabled can potentially cause issues on PCs with more limited GPUs.

 So, it’s recommended to select the "adjust for best performance" mode in the visual effect settings like this:

1. Right-click **Start**, select **Search**, and input "advanced system settings" in the text box.
2. Press the **Settings** button in the **Performance** category.  
![The Advanced tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/advanced-tab-2.jpg)
3. Click the **Adjust for best performance** radio button, which will deselect most if not all of the effect checkboxes.  
![The "adjust for best performance" button selected](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adjust-for-best-performance-radio-button.jpg)
4. Select **Apply** to set the new performance settings.
5. Click the Performance Options window’s **OK** button.

## 4\. Edit the GraphicsDrivers Registry Key

 Some users have got the “display driver failed to start” error fixed by editing the GraphicsDriver registry key. This tweaking involves adding a new **TdrDelay** DWORD value to that key for extending Timeout Detection Delay.

 You can edit the GraphicsDriver registry key like this:

1. Open the Run dialog with **Win + R** and enter "regedit".
2. Click **OK** or press **Enter** to open the Registry Editor window.
3. Then enter this GraphicsDrivers key location inside the registry address bar:  
`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\GraphicsDrivers`
4. Right-click **GraphicsDrivers** and select the **New** context menu option.
5. Select **DWORD (32-bit) Value** to add a new entry.  
![The New > DWORD options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dword-32-bit-value-2.jpg)
6. Type **TdrDelay** within the new DWORD’s text box.
7. Double-click the **TdrDelay** DWORD.
8. Input a value of **5** in the data box and select **OK**.  
![The Value data box the TdrDelay](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/value-data-box-2.jpg)
9. Now close the Registry Editor and reboot your PC.

## 5\. Roll Back Windows to a Previous Restore Point
![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-restore-window.jpg)

 If you have System Restore enabled, restoring Windows to an earlier date is worth a try if nothing else has worked so far. Rolling back Windows will undo every system change made after a selected date.

 As such, you can use System Restore to put your PC "back in time" to a moment when the error didn't occur. It does mean you may lose some apps or data, so be sure to back up anything you want to keep.

 Our guide to [utilizing System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) provides step-by-step instructions for how to roll back Windows 10 and 11\. Select a restore point date created before you needed to fix the “display driver failed to start” error.

 If this fixes the problem, be careful when re-installing the apps and drivers that got wiped during the restore. If you do, keep tabs on what you reinstalled and when. If the "display driver failed to start" error resurfaces, uninstall everything you recently reinstalled.

## 6\. Perform a Windows Factory Reset

 If System Restore is not an option or it doesn't resolve the issue, you can try a factory reset as the last resort. Performing a factory reset will likely fix the “display driver failed to start” error. However, factory resetting a PC deletes all the apps that weren't pre-installed with Windows. So, be prepared to reinstall all third-party apps you installed yourself.

![The Keep my Files option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/keep-my-files-option.jpg)

 You can apply a factory reset with the Reset this PC utility. That tool includes a **Keep my files** option you can select to keep files in your user folders (Documents, Pictures, Videos, etc). Our guide for [factory resetting Windows 10 and 11](http://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer) provides details on how to access and utilize that tool.

## Enjoy Your Windows Gaming Again

 Applying those potential solutions will almost certainly be enough to fix the “display driver failed to start” error in most cases. However, you may need to try applying more than one of them to find one that works on your PC. Then you can get back to playing all your favorite Windows games again without further issues.

 When this error is at its worst, it can prevent you from playing your favorite games. As such, here is how you can fix the “display driver failed to start” error on a Windows 10 or 11 PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/elevate-your-mouse-game-with-cross-border-powertoys-techniques/"><u>Elevate Your Mouse Game with Cross-Border PowerToys Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-error-0x0000004e-in-windows-a-quick-guide/"><u>Fixing Error 0X0000004E in Windows: A Quick Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-automatic-restarts-on-windows-11-devices/"><u>Conquering Automatic Restarts on WIndows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-your-path-upgrading-outdated-windows-driver-tech/"><u>Clear Your Path: Upgrading Outdated Windows Driver Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-update-faults-windows-xp-x8019/"><u>Eradicating Update Faults: Windows XP, X8019</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-non-successful-updates-in-windows-discord/"><u>Dealing with Non-Successful Updates in Windows Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-bygone-era-to-future-tech-using-windows-7-key-in-11-setup/"><u>From Bygone Era to Future Tech: Using Windows 7 Key in 11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-surprising-alerts-in-windows-security/"><u>Troubleshooting Surprising Alerts in Windows Security</u></a></li>
<li><a href="https://win11-tips.techidaily.com/does-windows-subsystem-enhance-linux-presence/"><u>Does Windows Subsystem Enhance Linux Presence?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-file-extractions-with-win11-sefx-magic/"><u>Elevating File Extractions with Win11 SEFx Magic</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-overcoming-call-failed-error-on-win1011/"><u>Guidelines for Overcoming 'Call Failed' Error on Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-cleansing-windows-arp-cache/"><u>Understanding and Cleansing Windows ARP Cache</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-pro-movie-magic-simplified-techniques-for-aspiring-filmmakers/"><u>New In 2024, Pro Movie Magic Simplified Techniques for Aspiring Filmmakers</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-understanding-pixel-dimensions-ratio-calculation-techniques/"><u>2024 Approved Understanding Pixel Dimensions Ratio Calculation Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-11s-mysteries-inside-its-registry-files/"><u>Unraveling Windows 11'S Mysteries: Inside Its Registry Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-eliminate-path-error-in-windows/"><u>Guide to Eliminate PATH Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-cheat-sheet-for-ms-project-keys/"><u>The Ultimate Cheat Sheet for MS Project Keys</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-change-location-on-yik-yak-for-your-vivo-x90s-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>In 2024, Change Location on Yik Yak For your Vivo X90S to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/evaluating-the-need-for-maintaining-pagefilesys-filespace/"><u>Evaluating the Need for Maintaining Pagefile.sys Filespace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mystery-overcoming-windows-run-time-errors/"><u>Unraveling the Mystery: Overcoming Windows 'Run-Time Errors'</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-windows-customization-via-cli-registry-edition/"><u>Advanced Windows Customization via CLI: Registry Edition</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-in-2024-leading-edge-tiktok-editing-tools-for-windows-users/"><u>[Updated] In 2024, Leading Edge TikTok Editing Tools for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-taskbar-absence-during-full-screen-mode/"><u>Tackling Taskbar Absence During Full-Screen Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-windows-users-to-fix-f429f-camera-app-hurdle/"><u>Guiding Windows Users to Fix F429F Camera App Hurdle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-ways-to-put-a-windows-computer-to-sleep/"><u>9 Ways to Put a Windows Computer to Sleep</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/ps-color-enhancement-simplified-approaches-for-2024/"><u>PS Color Enhancement  Simplified Approaches for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-streamlining-your-video-call-process-with-obs-and-skype/"><u>[Updated] In 2024, Streamlining Your Video Call Process with OBS & Skype</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginners-path-to-w11-audio-recording/"><u>Beginner's Path to W11 Audio Recording</u></a></li>
<li><a href="https://fix-guide.techidaily.com/in-2024-change-location-on-yik-yak-for-your-xiaomi-redmi-13c-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>In 2024, Change Location on Yik Yak For your Xiaomi Redmi 13C to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-a-complete-tour-through-discords-capabilities/"><u>[New] In 2024, A Complete Tour Through Discord's Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-problematic-java-setup-on-windows-pcs/"><u>Unblocking Problematic Java Setup on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/digitally-delving-opening-game-directories-on-windows/"><u>Digitally Delving: Opening Game Directories on Windows</u></a></li>
<li><a href="https://driver-install.techidaily.com/streamlined-input-device-driver-xbox-to-windows/"><u>Streamlined Input Device Driver, Xbox to Windows</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-proven-ways-in-how-to-hide-location-on-life360-for-nokia-150-2023-drfone-by-drfone-virtual-android/"><u>In 2024, Proven Ways in How To Hide Location on Life360 For Nokia 150 (2023) | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-intelligent-interface-ais-role-in-windows-evolution/"><u>The Intelligent Interface: AI's Role in Windows Evolution</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-easily-unlock-your-lava-yuva-3-device-sim-by-drfone-android/"><u>In 2024, Easily Unlock Your Lava Yuva 3 Device SIM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-windows-notifications-for-essential-only/"><u>Adjust Windows Notifications for Essential Only</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-complete-guide-to-drone-racing-plus-high-speed-fpv-drones/"><u>[New] The Complete Guide to Drone Racing + High-Speed FPV Drones</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-detect-and-remove-spyware-on-xiaomi-redmi-a2plus-drfone-by-drfone-virtual-android/"><u>In 2024, How to Detect and Remove Spyware on Xiaomi Redmi A2+? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-effortlessly-switch-nat-settings-in-windows-oses/"><u>How to Effortlessly Switch NAT Settings in Windows OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-simple-steps-for-overcoming-windows-onedrive-glitches/"><u>5 Simple Steps for Overcoming Windows OneDrive Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-potential-the-must-have-msistore-tools/"><u>Unlock Potential: The Must-Have MSIStore Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-peak-performance-taming-vanguards-cpu-power-draw-in-windows/"><u>Unlock Peak Performance: Taming Vanguard’s CPU Power Draw in Windows</u></a></li>
</ul></div>
