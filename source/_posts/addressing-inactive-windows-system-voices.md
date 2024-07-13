---
title: Addressing Inactive Windows System Voices
date: 2024-07-12T16:58:07.620Z
updated: 2024-07-13T16:58:07.620Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Inactive Windows System Voices
excerpt: This Article Describes Addressing Inactive Windows System Voices
keywords: Silent Windows Speech,Active Windows Talk,Voice Control Disabled,Windows No Voice Engage,Voice OFF Windows Error,Inactive Windows Sound,Dormant Windows Dialogue
thumbnail: https://thmb.techidaily.com/92ce41ef8b05767b09e5cccf1de47f0c1a1c9c1b0cd1ef1d90d54872beba93f1.jpg
---

## Addressing Inactive Windows System Voices

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
<li><a href="https://games-able.techidaily.com/solving-steam-network-not-available-problem/"><u>Solving Steam Network Not Available Problem</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/top-7-phone-number-locators-to-track-apple-iphone-11-pro-location-drfone-by-drfone-virtual-ios/"><u>Top 7 Phone Number Locators To Track Apple iPhone 11 Pro Location | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-desktop-icon-update-process-on-windows/"><u>Simplifying Desktop Icon Update Process on Windows</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-unresponsive-touch-screen-on-oppo-a2-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Touch Screen on Oppo A2 | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-making-money-fast-the-pathway-to-success-in-youtube-shorts/"><u>[New] Making Money Fast  The Pathway to Success in YouTube Shorts</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-ultimate-6-contemporary-mojave-home-layouts/"><u>2024 Approved  Ultimate 6 Contemporary Mojave Home Layouts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/severing-the-ties-unlink-onedrive-from-your-msid-on-windows/"><u>Severing the Ties: Unlink OneDrive From Your MSID on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-approach-to-editing-windows-registry-with-command-prompt/"><u>Stepwise Approach to Editing Windows Registry with Command Prompt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-launchers-security-failures-on-windows-systems/"><u>Navigating Launcher's Security Failures on Windows Systems</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-next-gen-photography-unveiling-auto-and-smart-hdr-features/"><u>[New] 2024 Approved  Next-Gen Photography  Unveiling Auto and Smart HDR Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-chromes-system-time-a-fix-guide-windows/"><u>Realigning Chrome's System Time: A Fix Guide (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-with-style-installation-and-usage-of-ms-store-themes/"><u>Navigate With Style: Installation and Usage of MS Store Themes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-rectifying-device-is-unreachable-error-in-windows/"><u>Mastering the Art of Rectifying Device Is Unreachable Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-device-hang-on-windows-11-zerodxgieror/"><u>Overcoming the Device Hang on Windows 11 (ZeroDXGIEror)</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-mastery-of-live-sharing-youtube-edition/"><u>[Updated] Mastery of Live Sharing  YouTube Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-winerror-0xc0000005/"><u>Mastering the Art of Fixing WinError 0Xc0000005</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-approach-to-bypassing-no-permission-on-pc/"><u>Step-by-Step Approach to Bypassing 'No Permission' On PC</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-in-2024-what-is-still-motion-animation/"><u>Updated In 2024, What Is Still Motion Animation?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-adjust-windows-activity-lock/"><u>How to Adjust Windows Activity Lock</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-pro-filmmaking-lenses-the-ten-most-critical-choices/"><u>2024 Approved  Pro Filmmaking Lenses  The Ten Most Critical Choices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-command-prompt-not-running-as-administrator-on-windows/"><u>How to Fix Command Prompt Not Running as Administrator on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-handle-internal-windows-error-during-remote-desktop-use/"><u>How to Handle Internal Windows Error During Remote Desktop Use</u></a></li>
<li><a href="https://review-topics.techidaily.com/put-and-play-mkv-movies-on-xiaomi-redmi-note-12t-pro-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Put and play MKV movies on Xiaomi Redmi Note 12T Pro</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-mastering-fast-time-cinematography/"><u>[Updated] Mastering Fast-Time Cinematography</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-error-0x80246007-on-windows-11-updates/"><u>Solving Error 0X80246007 on Windows 11 Updates</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-change-your-tecno-spark-20-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How to Change Your Tecno Spark 20 Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/unleashing-creativity-in-youtube-banner-and-thumbnail-design-for-2024/"><u>Unleashing Creativity in YouTube Banner & Thumbnail Design for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/scaling-up-output-the-power-of-flow-launcher-unveiled/"><u>Scaling Up Output: The Power of Flow Launcher Unveiled</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-progressive-solutions-to-adding-vhs-effects-to-video-with-ease/"><u>New 2024 Approved Progressive Solutions to Adding VHS Effects to Video with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/nine-must-have-android-apps-for-windows-users/"><u>Nine Must-Have Android Apps for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-xbox-game-pass-0x00000001-error-in-windows-10-and-11/"><u>How to Fix the Xbox Game Pass 0X00000001 Error in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pro-level-windows-photos-shortcut-guide/"><u>Pro-Level Windows Photos Shortcut Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-non-display-at-operating-system-kickoff/"><u>Resolving Non-Display at Operating System Kickoff</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-efficiency-guide/"><u>Mastering Windows 11: Efficiency Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prevent-non-scrollability-of-ranges-in-excel-windows/"><u>Prevent Non-Scrollability of Ranges in Excel, Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/peering-into-ftdibussys-an-analysis-of-windows-memory-controls/"><u>Peering Into ftdibus.sys: An Analysis of Windows' Memory Controls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-control-file-explorer-display-options-windows-11/"><u>How to Control File Explorer Display Options (Windows 11)</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-secure-recording-of-conversations-what-you-need-to-know-about-whatsapp/"><u>[New] In 2024, Secure Recording of Conversations  What You Need to Know About WhatsApp</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-swiftly-and-permanently-discard-a-partition-on-windows-pc/"><u>How to Swiftly and Permanently Discard a Partition on Windows PC</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-embedding-musical-composition-into-visual-media-projects/"><u>New Embedding Musical Composition Into Visual Media Projects</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-lock-apps-on-honor-magic-vs-2-to-protect-your-individual-information-by-drfone-android/"><u>How to Lock Apps on Honor Magic Vs 2 to Protect Your Individual Information</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-reverse-winerror-exit-point-failure/"><u>Steps to Reverse WinError Exit Point Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-fatal-error-c0000022-in-windows/"><u>How to Fix the Fatal Error C0000022 in Windows</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-streamline-your-filming-process-the-ultimate-logitech-camera-tutorials/"><u>2024 Approved  Streamline Your Filming Process - The Ultimate Logitech Camera Tutorials</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-memorable-moments-made-easy-download-and-save-gif-from-social-media/"><u>[Updated] Memorable Moments Made Easy  Download and Save GIF From Social Media</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-error-code-0xc0000001-on-windows-11-or-11/"><u>How to Fix Error Code 0Xc0000001 on Windows 11 or 11</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/abordagem-do-portugues-cada-frase-conta-uma-historia/"><u>Abordagem Do Português: Cada Frase Conta Uma História</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-faded-screen-settings-in-uefi/"><u>Restoring Faded Screen Settings in UEFI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-file-access-mastering-network-drives-in-win11/"><u>Seamless File Access: Mastering Network Drives in Win11</u></a></li>
</ul></div>
