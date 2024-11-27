---
title: Dealing with Inactive Windows Media Player Sounds
date: 2024-11-26T17:39:43.424Z
updated: 2024-11-27T16:42:34.182Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Dealing with Inactive Windows Media Player Sounds
excerpt: This Article Describes Dealing with Inactive Windows Media Player Sounds
keywords: Silent WMP Issues,Quiet Playback Fix,Stop Media Sound Alerts,Mute Media Errors,Inactive Audio Windows,WMP Silence Remedy,Turn Off Media Noise
thumbnail: https://thmb.techidaily.com/c08cfb9fc52b90a12972e5ec144ec0c7f63bc215d0f41358268b867a2994d1b8.jpg
---

## Dealing with Inactive Windows Media Player Sounds

 Although Windows includes a dedicated audio troubleshooter that can help resolve most audio-related issues, it may not always be effective. At times, the Windows audio troubleshooter may fail to resolve the underlying issue and display the “Audio services not responding” error.

 If the audio services on your Windows computer have become unresponsive, don’t fret. This guide packs some useful troubleshooting tips that should help you resolve the issue in no time.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Restart the Windows Audio Service

 Typically, the Windows Audio service starts automatically when your computer boots. However, if the service encounters any problems during startup, it may malfunction. If it's just a one-off glitch, restarting the Windows Audio service should fix the issue. Hence, you should start with that.

To restart the Windows Audio service:

1. Press**Win + S** to open the search menu.
2. Type**services** in the text box and press**Enter** .
3. In the Services window, scroll down to locate the**Windows Audio** service on the list. Then, right-click on it and select**Restart** .  
![Restart Windows Audio Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-windows-audio-service.jpg)

## 2\. Make Sure the Supporting Audio Components Are Running

 Windows Audio service relies on several system components to function properly on your PC. If one of these components is not running, audio services may stop responding.

Here’s how to check if the required services are running.

1. Press**Win + R** to open the Run dialog box.
2. Type**services.msc** in the Open field and press**Enter** .
3. Locate the**RPC Endpoint Mapper** service on the list and double-click on it to open its properties.
4. Click the drop-down menu next to**Startup type** to select**Automatic** .
5. Click**Apply** followed by**OK** .
6. Similarly, change the startup type for**Remote Procedure Call (RPC)** and**DCOM Server Process Launcher** services as well.  
![Remote Procedure Call Service in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/remote-procedure-call-service-in-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wNhKhWc0wLc?si=1XLYV0sXV52Xc0lu&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Restart your PC after this and check if the issue is still there.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MmTJlcwgyrQ?si=x3hba82M0tT57fj7&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Add Local and Network Services Using Command Prompt

 Another thing you can do to resolve this issue is to register local and network services on Windows using Command Prompt. Here are the steps for the same.

1. Right-click on the**Start icon** or press**Win + X** to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Type the following command in the console and press**Enter** to register network services on your system.  
`net localgroup Administrators /add networkservice`
5. Now run the following command to register local services:  
`net localgroup Administrators /add localservice`
6. Exit the Command Prompt window and then restart your PC.  
![Add Local and Network Services Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-local-and-network-services-using-command-prompt.jpg)

 Like using Command Prompt? Check our guide to learn[how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

## 4\. Update Audio Drivers

 Outdated or incompatible audio drivers on your PC can also cause the audio services to malfunction. If that's the case, updating the audio drivers on your PC should do the trick. If you need help with that, check our guide on[how to update audio drivers on Windows](https://www.makeuseof.com/update-audio-drivers-windows/) and follow the steps outlined there.

 If updating audio drivers manually sounds like a tedious task, you can get one of the[best driver updater for Windows](https://www.makeuseof.com/windows-best-free-driver-updaters/) to ease the process.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K7fATC_lI7o?si=UFotPJqflDRZr-mv&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Switch to the Default Sound Drivers

 Your Windows computer comes with its own set of sound drivers. If updating your current audio drivers does not help, you can switch to Windows' default sound drivers and see if that works. To do so, use the following steps:

1. Click the**magnifying icon** on the taskbar or press**Win + S** to open the search menu.
2. Type**control panel** in the text box and select the first result that appears.
3. Navigate to**System > Advanced System Settings** .
4. In the System Properties window, switch to the**Hardware** tab and click the**Device Installation Settings** button.
5. Select the**No (your device might not work as expected)** option and click**Save Changes** .

1. Select**Yes** when the User Account Control (UAC) prompt appears.  
![Device Installation Settings on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/device-installation-settings-on-windows.jpg)
2. Now use one of the[many ways to open Device Manager](https://www.makeuseof.com/windows-open-device-manager/) .
3. Expand the**Sound, video, and game controllers** .
4. Right-click on your sound driver and select**Uninstall device** .
5. Select**Uninstall** to confirm the action.
6. In the Device Manager window, click the**Action** menu at the top and select**Scan for hardware changes** from the list.  
![Uninstall Sound Driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/uninstall-sound-driver.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6xGqSETroqA?si=4C1GPgXi-AksR_oO&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Run the SFC and DISM Scans

 Corrupt or damaged system files on Windows can also cause audio services to stop responding. System File Checker (SFC) and Deployment Image Servicing and Management (DISM) are two Windows tools that can help you identify and repair such system files.

 The SFC scan will check your computer for missing or corrupt system files, whereas DISM will repair the Windows system image. You can run these tools using Command Prompt. To know more, check our guide on[how to repair corrupt Windows files with Windows built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/) and follow the steps outlined there.

## 7\. Perform a System Restore

 System Restore is a useful feature on Windows that creates a backup of your entire system at predefined intervals. It can help you restore your system to the point before the problem occurred.

 System Restore will undo any recent changes made to your computer and resolve the issue for good. Don’t worry, this process won’t affect any of your personal data.

To perform a system restore on Windows, use these steps:

1. Right-click on the**Start** icon and select**Run** from the list.
2. Type**sysdm.cpl** in the box and press**Enter** .
3. In the System Properties window, switch to the**System Protection** tab.
4. Click on**System Restore** .
5. Click**Next** .
6. Select a restore point before the issue first appeared and hit**Next** .
7. Review all the details and click**Finish** .  
![System Restore Dialog on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/system-restore-dialog-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/L603QXgjb3I?si=sMYHfMGy2kNPSHPt&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Wait for Windows to restart and revert to the specified restore point. After that, the audio services should work fine.

## Fixing Audio Services on Windows Is Easy

 It can be confusing if the audio services on Windows suddenly become unresponsive. In most cases, manually restarting the audio services should resolve the issue. If not, you may have to go through the trouble of scanning the system files or performing a system restore.

 That said, if none of the above solutions work, you can consider resetting your Windows computer or performing an in-place upgrade as a last resort.

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
<li><a href="https://fox-hovers.techidaily.com/new-2024-approved-chill-and-thrills-highlighting-olympic-snowboard-cross-winners/"><u>[New] 2024 Approved Chill & Thrills Highlighting Olympic Snowboard Cross Winners</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-erase-red-eye-in-iphone-pics-for-free-with-our-guide/"><u>[Updated] Erase Red-Eye in iPhone Pics for Free with Our Guide</u></a></li>
<li><a href="https://howto.techidaily.com/calls-on-tecno-spark-10-4g-go-straight-to-voicemail-12-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Calls on Tecno Spark 10 4G Go Straight to Voicemail? 12 Fixes | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/efficient-deletion-techniques-for-online-discussions/"><u>Efficient Deletion Techniques for Online Discussions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enrich-your-environment-adding-tasks-to-folder-context-menus/"><u>Enrich Your Environment: Adding Tasks to Folder Context Menus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/extending-the-duration-of-windows-11-shutdown-during-execution/"><u>Extending the Duration of Windows 11 Shutdown During Execution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-missing-piece-regain-access-to-windows-11-enhancements/"><u>Fixing the Missing Piece: Regain Access to Window's 11 Enhancements</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-after-switching-from-lava-blaze-2-5g-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data After Switching From Lava Blaze 2 5G to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-chromebook-video-editing-mastery-how-to-use-any-app-regardless-of-os/"><u>In 2024, Chromebook Video Editing Mastery How to Use Any App, Regardless of OS</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-multi-platform-windows-film-editor-clones/"><u>In 2024, Multi-Platform Windows Film Editor Clones</u></a></li>
<li><a href="https://win-howtos.techidaily.com/pam-pulse-amplitude-modulation/"><u>PAM (Pulse Amplitude Modulation)</u></a></li>
<li><a href="https://win-dash.techidaily.com/seamless-printing-with-newly-updated-windows-driver-for-hp-officejet-pro-8600/"><u>Seamless Printing with Newly Updated Windows Driver for HP Officejet Pro 8600</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-non-connecting-wi-fi-usb-on-windows-devices/"><u>Solving Non-Connecting Wi-Fi USB on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-windows-11s-file-management-adding-custom-movecopy-menus/"><u>Tailoring Windows 11'S File Management: Adding Custom Move/Copy Menus</u></a></li>
<li><a href="https://extra-hints.techidaily.com/top-zeoid-startups-revealed-in-panzoids/"><u>Top Zeoid Startups Revealed in Panzoids</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-secure-boot-failures-wins-quick-solutions/"><u>Troubleshoot Secure Boot Failures: Win's Quick Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-weather-app-companions-guide/"><u>Win Weather App Companions Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-alert-7-symptoms-needed-a-fresh-start/"><u>Windows Alert: 7 Symptoms Needed a Fresh Start</u></a></li>
<li><a href="https://win11-tips.techidaily.com/workarounds-to-fix-static-sleepwake-modes-on-win11/"><u>Workarounds to Fix Static Sleep/Wake Modes on Win11</u></a></li>
</ul></div>

