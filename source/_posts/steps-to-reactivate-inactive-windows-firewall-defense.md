---
title: Steps to Reactivate Inactive Windows Firewall Defense
date: 2024-11-22T17:26:40.680Z
updated: 2024-11-27T16:33:55.264Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Reactivate Inactive Windows Firewall Defense
excerpt: This Article Describes Steps to Reactivate Inactive Windows Firewall Defense
keywords: Reactivate Windows Firewall,Windows Defense Relaunch,Resume Firewall Protection,Restart Windows Firewall,Enable Firewall Now,Activate Firewall Service,Boost Firewall Security
thumbnail: https://thmb.techidaily.com/4d92bee2eba99f34da43a3826fc4e46ce3e4a6c22b117140d007c698449c206f.png
---

## Steps to Reactivate Inactive Windows Firewall Defense

 Windows Firewall is crucial to ensure the security of your computer and protect it from potential threats. However, sometimes you may encounter issues while enabling it.

 Below, we explore the different solutions you can try to fix this issue for good.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Run the Firewall Troubleshooter

 If you are having trouble enabling Firewall in Windows, it is a good idea to start troubleshooting using the official Firewall troubleshooter released by Microsoft Automated Troubleshooting Services.

 This utility will scan your system for underlying problems that might be preventing Firewall from functioning. If an issue is identified, it will suggest relevant fixes that you can either apply manually or from within the troubleshooter.

 Here is how you can run the troubleshooter:

1. Head over to the [official Microsoft page for the troubleshooter](https://support.microsoft.com/en-us/windows/automatically-diagnose-and-fix-problems-with-windows-firewall-513e9cf8-19ae-d579-2092-d5e64fe06f5f) and download it.  
![Download firewall troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/download-troubleshooter.jpg)
2. Click on the downloaded file and proceed with the on-screen instructions to start the scan.  
![Firewall troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/firewall-troubleshooter.jpg)
3. Once the scan completes, check the results and apply the solutions suggested by the troubleshooter.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15TKQ-BOENI?si=Ri4B2AuxAdi0Bglz&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can now close the troubleshooter and check if the issue is resolved.

## 2\. Check if Another Security Software Is Active

 Are you using a third-party security program on your computer? If so, there is a good chance that it is conflicting with Windows Firewall and stopping it from working. As such, if you have installed another antivirus app recently, we recommend temporarily disabling or uninstalling the third-party security program and then enabling Windows Firewall.

 Disabling the third-party antivirus software may vary depending on the program you have installed. However, a common approach is to right-click on the antivirus icon located in the taskbar. From the context menu that appears, you should find an option to disable the antivirus temporarily until you restart your computer.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zAzTErKy6h8?si=vi5z3M9_7fW6qiAJ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oeSN3u4fO9M?si=Ua3Hzcil6u6akDgY&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Click **Apply** to save the changes and check if the issue is now resolved.

## Additional Generic Fixes to Try

 Apart from the fixes we have listed above, here are some additional solutions that you can try to fix the Firewall problem.

* **Ensure relevant services are running**: Windows Firewall relies on several services to function properly. Ensure that the Windows Defender Firewall, Windows Defender Advanced Threat Protection, Windows Defender Antivirus Network Inspection, and Windows Defender Antivirus services are working fine in the Windows Services utility.
* **Scan with SFC**: You can also scan the system for underlying corruption errors that might be leading to the problem using the [System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/). You can run it via Command Prompt and analyze the results to find the culprit.
* **Clean install Windows**: If nothing works and it is essential for you to enable Firewall, you can [perform a clean install](https://www.makeuseof.com/how-to-clean-install-windows-11/) of Windows. It will wipe the existing installation and download a new one without any underlying problems.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/97ydpSmzTJw?si=tFcelmtQX4u-b3u5&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Protect Your System With Windows Firewall

 The steps above should help you fix issues with Windows Firewall easily. If the error persists and you do not want to clean install the system yet, you can report the issue to Microsoft and wait for them to suggest a fix.

 Below, we explore the different solutions you can try to fix this issue for good.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-access.techidaily.com/updated-2024-approved-unveiling-superiority-in-choosing-drones-lipo-energizers/"><u>[Updated] 2024 Approved Unveiling Superiority in Choosing Drones' LiPo Energizers</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-pixelgrabber-w11-simplest-screen-to-video-converter/"><u>[Updated] PixelGrabber W11 Simplest Screen to Video Converter</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-capture-and-preserve-snapchat-moments-top-techniques/"><u>2024 Approved Capture and Preserve Snapchat Moments Top Techniques</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-ultimate-guide-to-youtube-success-with-tubebuddy/"><u>2024 Approved The Ultimate Guide to YouTube Success with TubeBuddy</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/best-5-ai-movie-script-generators/"><u>Best 5 AI Movie Script Generators</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/clarifying-how-shared-links-function-in-ai-conversations/"><u>Clarifying How Shared Links Function in AI Conversations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-failed-directx-updates-on-windows/"><u>Correcting Failed DirectX Updates on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-apps-facilitating-pc-overdrive-from-laptops/"><u>Essential Apps Facilitating PC Overdrive From Laptops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-notepad-crashing-on-windows/"><u>How to Fix Notepad Crashing on Windows</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-4-ways-to-transfer-music-from-infinix-note-30-vip-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 4 Ways to Transfer Music from Infinix Note 30 VIP to iPhone | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-the-esc-key-not-working-in-windows-try-these-fixes/"><u>Is the Esc Key Not Working in Windows? Try These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-glitches-fixing-ms-store-in-windows-10-and-11/"><u>Overcoming Glitches: Fixing MS Store in Windows 10 & 11</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/prevent-bot-data-exposure-with-caution/"><u>Prevent Bot Data Exposure with Caution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-solve-code-0x0000004e-on-windows-pcs/"><u>Steps to Solve Code 0X0000004E on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-correcting-internal-error-in-remote-desktop-windows/"><u>Strategies for Correcting Internal Error in Remote Desktop Windows</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    