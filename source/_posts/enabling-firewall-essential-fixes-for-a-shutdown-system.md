---
title: "Enabling Firewall: Essential Fixes for a Shutdown System"
date: 2024-07-12T16:31:25.409Z
updated: 2024-07-13T16:31:25.409Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Enabling Firewall: Essential Fixes for a Shutdown System"
excerpt: "This Article Describes Enabling Firewall: Essential Fixes for a Shutdown System"
keywords: Firewall Basics,Enable Firewall,Shutdown Prevention,Security Fixes Now,System Stability Boost,Essential Firewall Fix,Secure Computer Networks
thumbnail: https://thmb.techidaily.com/482035835ea328d1609501451811446cad884a7a61227ca3ca092b735291d94d.jpg
---

## Enabling Firewall: Essential Fixes for a Shutdown System

 Windows Firewall is crucial to ensure the security of your computer and protect it from potential threats. However, sometimes you may encounter issues while enabling it.

 Below, we explore the different solutions you can try to fix this issue for good.

## 1\. Run the Firewall Troubleshooter

 If you are having trouble enabling Firewall in Windows, it is a good idea to start troubleshooting using the official Firewall troubleshooter released by Microsoft Automated Troubleshooting Services.

 This utility will scan your system for underlying problems that might be preventing Firewall from functioning. If an issue is identified, it will suggest relevant fixes that you can either apply manually or from within the troubleshooter.

 Here is how you can run the troubleshooter:

1. Head over to the [official Microsoft page for the troubleshooter](https://support.microsoft.com/en-us/windows/automatically-diagnose-and-fix-problems-with-windows-firewall-513e9cf8-19ae-d579-2092-d5e64fe06f5f) and download it.  
![Download firewall troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/download-troubleshooter.jpg)
2. Click on the downloaded file and proceed with the on-screen instructions to start the scan.  
![Firewall troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/firewall-troubleshooter.jpg)
3. Once the scan completes, check the results and apply the solutions suggested by the troubleshooter.

 You can now close the troubleshooter and check if the issue is resolved.

## 2\. Check if Another Security Software Is Active

 Are you using a third-party security program on your computer? If so, there is a good chance that it is conflicting with Windows Firewall and stopping it from working. As such, if you have installed another antivirus app recently, we recommend temporarily disabling or uninstalling the third-party security program and then enabling Windows Firewall.

 Disabling the third-party antivirus software may vary depending on the program you have installed. However, a common approach is to right-click on the antivirus icon located in the taskbar. From the context menu that appears, you should find an option to disable the antivirus temporarily until you restart your computer.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 After disabling the antivirus, try enabling the Windows Firewall and check if it functions properly now.

## 3\. Reset the Windows Firewall settings

 The issue might also be with the Firewall settings. You can fix any such issues by resetting Windows Firewall settings, as it will restore the firewall configuration to its default state, undoing any customizations or changes that might be causing conflicts.

 Here is how you can proceed:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type “control” in Run and click **Enter**.
3. In the Control Panel, expand the View by option and choose **Category**.
4. Click on **System and Security** \> **Windows Defender Firewall**.  
![Defender Firewall in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/defender-firewall.jpg)
5. Head over to the left pane and choose **Restore defaults**.  
![Restore defaults for firewall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restore-defaults.jpg)

1. Confirm the action in the following prompt and proceed with the on-screen instructions to proceed.
2. Once done, open Run again.
3. Type "cmd" in the text field and press **Ctrl** \+ **Shift** \+ **Enter** keys together. This will open Command Prompt with administrator privileges.
4. Click **Yes** in the User Account Control prompt.
5. Once you are inside the Command Prompt window, type the command mentioned below and click **Enter** to execute it. This will force enable the Firewall component.  
`netsh firewall set opmode mode=ENABLE exceptions=enable`
6. Wait for the command to execute and then restart your computer. Check if the problem is now fixed.

## 4\. Modify the Registry Editor

 There is also a chance that a Registry key DisableAntiSpyware is enabled, which is preventing you from enabling Firewall on your computer.

 To check if this is the case in your situation, you can access the Registry Editor and check the status of the DisableAntiSpyware key.

 However, before you proceed, we highly recommend [creating a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/), just to be safe.

 Once that is done, proceed with the steps below:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "regedit" in Run and click **Enter**.
3. Click **Yes** in the User Account Control prompt.
4. In the Registry Editor, navigate to the location below.  
`​​​​​​​HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender`
5. Move to the right side and look for the DisableAntiSpyware key. If you locate it, delete it. You can also double-click on it and change its value to 0 if you do not want to delete it.  
![Disable or delete the registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/antispyware-key.jpg)

1. Once done, head over to the following location:  
`​​​​​​​​​​​​​​HKEY_LOCAL_MACHINE/SYSTEM/CurrentControlSet/Services/BFE`
2. Right-click on the **BFE** key and choose **Permissions** from the context menu.  
![Access permissions of the key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/access-permissions.jpg)
3. Under "Group or user names", click on **Add**.
4. Type "Everyone" in the "Enter the object names to select" and click **OK**.  
![Modify permissions of the key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/modify-permissions.jpg)
5. Now, head over to the "Permissions for Everyone" section and checkmark the box associated with **Full Control** under Allow.
6. Click **Apply** to save the changes and check if the issue is now resolved.

## Additional Generic Fixes to Try

 Apart from the fixes we have listed above, here are some additional solutions that you can try to fix the Firewall problem.

* **Ensure relevant services are running**: Windows Firewall relies on several services to function properly. Ensure that the Windows Defender Firewall, Windows Defender Advanced Threat Protection, Windows Defender Antivirus Network Inspection, and Windows Defender Antivirus services are working fine in the Windows Services utility.
* **Scan with SFC**: You can also scan the system for underlying corruption errors that might be leading to the problem using the [System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/). You can run it via Command Prompt and analyze the results to find the culprit.
* **Clean install Windows**: If nothing works and it is essential for you to enable Firewall, you can [perform a clean install](https://www.makeuseof.com/how-to-clean-install-windows-11/) of Windows. It will wipe the existing installation and download a new one without any underlying problems.

## Protect Your System With Windows Firewall

 The steps above should help you fix issues with Windows Firewall easily. If the error persists and you do not want to clean install the system yet, you can report the issue to Microsoft and wait for them to suggest a fix.

 Below, we explore the different solutions you can try to fix this issue for good.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-resources.techidaily.com/2024-approved-astonishing-critique-and-substitutes-guide/"><u>2024 Approved  Astonishing Critique & Substitutes Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-device-connectivity-troubleshooting-on-win-os/"><u>Mastering Device Connectivity Troubleshooting on Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-new-depths-noteworthy-alterations-in-windows-11s-interface/"><u>Exploring New Depths: Noteworthy Alterations in Windows 11'S Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stop-discord-from-launching-at-startup-and-searching-for-updates-on-windows/"><u>How to Stop Discord From Launching at Startup and Searching for Updates on Windows</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-easy-avi-file-splitting-and-trimming-a-comprehensive-guide/"><u>Updated Easy AVI File Splitting and Trimming A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-efficiency-in-windows-photos-via-shortcuts/"><u>Maximize Efficiency in Windows Photos via Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-starting-csgo-in-w11/"><u>Mastering the Art of Starting CS:GO in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comparing-computer-storage-the-c-and-d-scene/"><u>Comparing Computer Storage: The 'C:' And 'D:' Scene</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-unique-devices-names-erase-in-use-issues-on-pcs/"><u>Mastering Unique Devices Names: Erase 'In Use' Issues on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-error-x80131500-in-windows-shop/"><u>Demystifying Error X80131500 in Windows Shop</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-how-to-boost-your-instagram-vids-visibility/"><u>[Updated] How to Boost Your Instagram Vids' Visibility</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-join-the-circle-easy-friend-request-steps/"><u>[New] 2024 Approved  Join the Circle  Easy Friend Request Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-messages-failed-to-load-error-on-discord-for-windows/"><u>How to Fix the Messages Failed to Load Error on Discord for Windows</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-install-and-upgrade-guide-to-the-latest-macos-sierra/"><u>[New] Install and Upgrade Guide to the Latest macOS Sierra</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-noteworthy-14-dynamic-text-artworks/"><u>2024 Approved  Noteworthy 14 Dynamic Text Artworks</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-the-hidden-paths-to-pristine-stock-photography/"><u>[Updated] The Hidden Paths to Pristine Stock Photography</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-maximizing-social-media-roi-with-judicious-facebook-hash-usage-for-2024/"><u>[Updated] Maximizing Social Media ROI with Judicious Facebook Hash Usage for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-open-and-use-the-windows-terminal-in-quake-mode/"><u>How to Open and Use the Windows Terminal in Quake Mode</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-pinnacle-group-of-multimedia-harmony-makers/"><u>[New] Pinnacle Group of Multimedia Harmony Makers</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/behind-the-curtains-a-guide-to-youtubes-hidden-videos/"><u>Behind the Curtains  A Guide to YouTube’s Hidden Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stop-roblox-needs-quitting-on-windows-without-hesitation/"><u>How to Stop Roblox Needs Quitting on Windows Without Hesitation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-windows-11-fixes-22h2-edition/"><u>Essential Windows 11 Fixes: 22H2 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/circumventing-verify-errors-for-third-party-windows-apps/"><u>Circumventing Verify Errors for Third-Party Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-setup-for-bings-ai-assistance-in-windows-11-search-shortcuts/"><u>Instant Setup for Bing's AI Assistance in Windows 11 Search Shortcuts</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-crafting-engaging-facebook-reels-the-making-process-explained/"><u>[Updated] 2024 Approved  Crafting Engaging Facebook Reels  The Making Process Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-symbolic-x-in-windows-file-explorer/"><u>Decoding: The Symbolic X in Windows File Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-apply-local-group-policies-to-a-specific-user-account-in-windows-10-and-11/"><u>How to Apply Local Group Policies to a Specific User Account in Windows 10 and 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-batch-renaming-like-a-pro-with-powertoys/"><u>Master Batch Renaming Like a Pro with PowerToys</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/unlocking-creativity-in-youtube-shorts-template-development-for-2024/"><u>Unlocking Creativity in YouTube Shorts Template Development for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-realme-narzo-60-5g-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>In 2024, Realme Narzo 60 5G ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-quickly-remove-bloatware-from-windows-11/"><u>How to Quickly Remove Bloatware From Windows 11</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-displaycast-critique-service/"><u>[Updated] 2024 Approved  DisplayCast Critique Service</u></a></li>
<li><a href="https://extra-information.techidaily.com/heaviest-aerial-transporters-top-10-drones-reviewed/"><u>Heaviest Aerial Transporters  Top 10 Drones Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-failed-directx-file-downloads-on-pcs/"><u>Fixing Failed DirectX File Downloads on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-spotify-application-is-not-responding-error-in-windows-11-and-11/"><u>How to Fix the “Spotify Application Is Not Responding” Error in Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-non-operational-inbox-messages-on-windows/"><u>Breaking Down Non-Operational Inbox Messages on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-cab-files-usage-and-installation-insights/"><u>Mastering Windows CAB Files: Usage and Installation Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-complex-comic-formats-for-win11-users/"><u>Breaking Down Complex Comic Formats for Win11 Users</u></a></li>
<li><a href="https://extra-hints.techidaily.com/envisioning-the-future-learn-from-these-6-metaverse-scenarios/"><u>Envisioning the Future  Learn From These 6 Metaverse Scenarios</u></a></li>
</ul></div>
