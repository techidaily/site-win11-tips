---
title: Tackling Windows Sound System Malfunctions
date: 2024-07-12T16:43:21.982Z
updated: 2024-07-13T16:43:21.982Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling Windows Sound System Malfunctions
excerpt: This Article Describes Tackling Windows Sound System Malfunctions
keywords: Fixing Windows Audio Errors,Troubleshoot Windows Sounds,Solve Windows Sound Issues,Windows Audio Problems Help,Windows Sound Glitches Cure,Address Windows Audio Failures,Overcome Windows Sound Breakdown
thumbnail: https://thmb.techidaily.com/51b5c705b272c6a35f26cbee92033b8d25124b814164fccb1a1f598c30e520f7.jpg
---

## Tackling Windows Sound System Malfunctions

 Although Windows includes a dedicated audio troubleshooter that can help resolve most audio-related issues, it may not always be effective. At times, the Windows audio troubleshooter may fail to resolve the underlying issue and display the “Audio services not responding” error.

 If the audio services on your Windows computer have become unresponsive, don’t fret. This guide packs some useful troubleshooting tips that should help you resolve the issue in no time.

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

Restart your PC after this and check if the issue is still there.

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

 Like using Command Prompt? Check our guide to learn [how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

## 4\. Update Audio Drivers

 Outdated or incompatible audio drivers on your PC can also cause the audio services to malfunction. If that's the case, updating the audio drivers on your PC should do the trick. If you need help with that, check our guide on [how to update audio drivers on Windows](https://www.makeuseof.com/update-audio-drivers-windows/) and follow the steps outlined there.

 If updating audio drivers manually sounds like a tedious task, you can get one of the [best driver updater for Windows](https://www.makeuseof.com/windows-best-free-driver-updaters/) to ease the process.

## 5\. Switch to the Default Sound Drivers

 Your Windows computer comes with its own set of sound drivers. If updating your current audio drivers does not help, you can switch to Windows' default sound drivers and see if that works. To do so, use the following steps:

1. Click the**magnifying icon** on the taskbar or press**Win + S** to open the search menu.
2. Type**control panel** in the text box and select the first result that appears.
3. Navigate to**System > Advanced System Settings** .
4. In the System Properties window, switch to the**Hardware** tab and click the**Device Installation Settings** button.
5. Select the**No (your device might not work as expected)** option and click**Save Changes** .

1. Select**Yes** when the User Account Control (UAC) prompt appears.  
![Device Installation Settings on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/device-installation-settings-on-windows.jpg)
2. Now use one of the [many ways to open Device Manager](https://www.makeuseof.com/windows-open-device-manager/) .
3. Expand the**Sound, video, and game controllers** .
4. Right-click on your sound driver and select**Uninstall device** .
5. Select**Uninstall** to confirm the action.
6. In the Device Manager window, click the**Action** menu at the top and select**Scan for hardware changes** from the list.  
![Uninstall Sound Driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/uninstall-sound-driver.jpg)

## 6\. Run the SFC and DISM Scans

 Corrupt or damaged system files on Windows can also cause audio services to stop responding. System File Checker (SFC) and Deployment Image Servicing and Management (DISM) are two Windows tools that can help you identify and repair such system files.

 The SFC scan will check your computer for missing or corrupt system files, whereas DISM will repair the Windows system image. You can run these tools using Command Prompt. To know more, check our guide on [how to repair corrupt Windows files with Windows built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/) and follow the steps outlined there.

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
<li><a href="https://win11-tips.techidaily.com/defender-cleanup-procedures-for-a-secure-and-streamlined-pc/"><u>Defender Cleanup Procedures for a Secure and Streamlined PC</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-social-media-tip-post-youtube-content-dont-twit-for-2024/"><u>[New] Social Media Tip  Post YouTube Content, Don't Twit for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-enterprise-restricted-chromeedge-settings-on-desktop-pcs/"><u>Addressing Enterprise-Restricted Chrome/Edge Settings on Desktop PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-and-defusing-error-0x80070570-saving-your-damaged-files-in-windows-11/"><u>Deciphering and Defusing Error 0X80070570: Saving Your Damaged Files in Windows 11</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-audiophile-free-viewing-modern-strategies-for-quieting-down-videos-on-your-desktop-or-the-net-2024-edition/"><u>Updated Audiophile-Free Viewing Modern Strategies for Quieting Down Videos on Your Desktop or the Net, 2024 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decode-fn-key-operations-in-modern-windows-pcs/"><u>Decode FN Key Operations in Modern Windows PCs</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-no-cost-memes-made-simple-our-meme-kit-for-2024/"><u>[New] No-Cost Memes Made Simple  Our Meme Kit for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/guide-on-how-to-erase-iphone-6s-plus-data-completely-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>Guide on How To Erase iPhone 6s Plus Data Completely | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/essential-online-repositories-for-stylish-text-applications/"><u>Essential Online Repositories for Stylish Text Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-failed-writable-operation-files-in-windows/"><u>Addressing Failed Writable Operation Files in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/concealing-taskview-in-window-11-taskbar-design/"><u>Concealing TaskView in Window 11 Taskbar Design</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-error-e1-code-on-w10w11-systems/"><u>Eradicating Error E1 Code on W10/W11 Systems</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-tricks-of-the-trade-for-instagram-video-preservation/"><u>[Updated] Tricks of the Trade for Instagram Video Preservation</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-navigating-modern-and-future-terrain-with-drones/"><u>[Updated] In 2024, Navigating Modern and Future Terrain with Drones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-the-purpose-and-use-of-microsofts-phone-link-app/"><u>Deciphering the Purpose and Use of Microsoft's 'Phone Link' App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11s-secure-testing-solution-enabling-and-configuring-sandbox/"><u>Win 11'S Secure Testing Solution: Enabling and Configuring Sandbox</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/2024-approved-sound-effects-for-podcasts-11-places-to-find-them/"><u>2024 Approved Sound Effects for Podcasts 11 Places to Find Them</u></a></li>
<li><a href="https://fake-location.techidaily.com/which-is-the-best-fake-gps-joystick-app-on-lava-yuva-3-pro-drfone-by-drfone-virtual-android/"><u>Which is the Best Fake GPS Joystick App On Lava Yuva 3 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-failed-connectivity-issue-of-mb-in-windows-11/"><u>Addressing the Failed Connectivity Issue of MB in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/challenging-the-status-quo-embracing-individuality-in-restricted-settings/"><u>Challenging the Status Quo: Embracing Individuality in Restricted Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-buyers-guide-affordable-access-to-windows-11-vcs/"><u>A Buyer’s Guide: Affordable Access to Windows 11 VCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-cross-language-communication-with-windows-11-hotkeys/"><u>Accelerate Cross-Language Communication with Windows 11 Hotkeys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-manual-for-mending-screen-size-issues-on-windows/"><u>A Step-by-Step Manual for Mending Screen Size Issues on Windows</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/unraveling-time-reverse-video-on-instagram-secrets-for-2024/"><u>Unraveling Time  Reverse Video on Instagram Secrets for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-computer-experience-with-these-6-tools/"><u>Accelerate Your Computer Experience with These 6 Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-conflicts-for-print-job-success/"><u>Eradicating Conflicts for Print Job Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-video-processing-on-windows-embrace-distributed-power-via-tdarr/"><u>Elevate Video Processing on Windows: Embrace Distributed Power via Tdarr</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-mac-locations-on-your-windows-11-system/"><u>Deciphering MAC Locations on Your Windows 11 System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-fixes-for-alt-codes-failing-in-windows-60-characters/"><u>Effective Fixes for ALT Codes Failing in Windows (60 Characters)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-hdr-on-windows-11-an-in-depth-explanation/"><u>Decoding HDR on Windows 11: An In-Depth Explanation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-visual-fields-in-windows-systems/"><u>Altering Visual Fields in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridge-gap-for-sd-detectability-by-explore-window/"><u>Bridge Gap for SD Detectability by Explore Window</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-the-functionality-of-fn-keys-on-modern-pcs-windows-11/"><u>Configuring the Functionality of FN Keys on Modern PCs (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-productivity-windows-11-pc-manager-tools-guide/"><u>Enhance Productivity: Windows 11 PC Manager Tools Guide</u></a></li>
<li><a href="https://activate-lock.techidaily.com/new-multiple-ways-how-to-remove-icloud-activation-lock-from-your-iphone-14-pro-max-by-drfone-ios/"><u>New Multiple Ways How To Remove iCloud Activation Lock From your iPhone 14 Pro Max</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-steps-to-correct-cannot-find-gpeditmsc-issue/"><u>Unveiling Steps to Correct Cannot Find Gpedit.msc Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-forth-invisible-5ghz-connections-with-these-fixes/"><u>Bring Forth Invisible 5GHz Connections with These Fixes</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-the-lowdown-on-converting-ogg-files-expert-tips/"><u>Updated In 2024, The Lowdown on Converting OGG Files Expert Tips</u></a></li>
</ul></div>
