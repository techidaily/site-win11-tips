---
title: Steps to Reactivate Inactive Windows Firewall Defense
date: 2024-12-05T21:29:41.839Z
updated: 2024-12-06T16:43:29.930Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fqBKCGAKHmA?si=OkoaI17nE5qNqTHj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Run the Firewall Troubleshooter

 If you are having trouble enabling Firewall in Windows, it is a good idea to start troubleshooting using the official Firewall troubleshooter released by Microsoft Automated Troubleshooting Services.

 This utility will scan your system for underlying problems that might be preventing Firewall from functioning. If an issue is identified, it will suggest relevant fixes that you can either apply manually or from within the troubleshooter.

 Here is how you can run the troubleshooter:

1. Head over to the [official Microsoft page for the troubleshooter](https://support.microsoft.com/en-us/windows/automatically-diagnose-and-fix-problems-with-windows-firewall-513e9cf8-19ae-d579-2092-d5e64fe06f5f) and download it.  
![Download firewall troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/download-troubleshooter.jpg)
2. Click on the downloaded file and proceed with the on-screen instructions to start the scan.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qNrOsjUdRz0?si=xGzhmNmtgxNTsRxN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xtylXDY9YfA?si=VonzSiDFGCpJm2uC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Restore defaults for firewall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restore-defaults.jpg)

1. Confirm the action in the following prompt and proceed with the on-screen instructions to proceed.
2. Once done, open Run again.
3. Type "cmd" in the text field and press **Ctrl** \+ **Shift** \+ **Enter** keys together. This will open Command Prompt with administrator privileges.
4. Click **Yes** in the User Account Control prompt.
5. Once you are inside the Command Prompt window, type the command mentioned below and click **Enter** to execute it. This will force enable the Firewall component.  
`netsh firewall set opmode mode=ENABLE exceptions=enable`
6. Wait for the command to execute and then restart your computer. Check if the problem is now fixed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ME5-sAQJVE4?si=ZfcvJSnhQevWtjI0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aYH0B2HqcIM?si=3fkoG85L6hAeB4ok" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-leading-tech-macs-finest-video-recording-software/"><u>[New] 2024 Approved Leading Tech Mac's Finest Video Recording Software</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-the-ultimate-guide-to-free-accurate-youtube-transcript-creation/"><u>[New] In 2024, The Ultimate Guide to Free, Accurate YouTube Transcript Creation</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-top-ten-video-cards-selection-guide-for-youtube-aficionados/"><u>[Updated] Top-Ten Video Cards Selection Guide for YouTube Aficionados</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-unveiling-5-cutting-edge-hmds-for-drone-masters/"><u>2024 Approved Unveiling 5 Cutting-Edge HMDs for Drone Masters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-steps-to-revert-settings-after-system-restart/"><u>Easy Steps to Revert Settings After System Restart</u></a></li>
<li><a href="https://fox-zero.techidaily.com/effizienteste-tools-zum-kopieren-ihrer-datentrager-hddssd-unter-windows-10-kostenlos-and-benutzerfreundlich/"><u>Effizienteste Tools Zum Kopieren Ihrer Datenträger (HDD/SSD) Unter Windows 10 - Kostenlos & Benutzerfreundlich</u></a></li>
<li><a href="https://sound-issues.techidaily.com/expert-tips-for-fixing-a-malfunctioned-microphone-on-the-runmus-gaming-headset/"><u>Expert Tips for Fixing a Malfunctioned Microphone on the Runmus Gaming Headset</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/how-to-optimally-utilize-a-creative-commons-license/"><u>How to Optimally Utilize a Creative Commons License</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-infinix-zero-30-5g-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Infinix Zero 30 5G to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-hidden-windows-bar-when-window-is-full-screen/"><u>Overcoming Hidden Windows Bar when Window Is Full Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-addressing-lsa-deactivation-issue/"><u>Quick Guide to Addressing LSA Deactivation Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-unrecognized-razers-by-synapse-in-latest-windows-os/"><u>Remedy Unrecognized Razers by Synapse in Latest Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-autostart-of-discord-from-windows-operating-system/"><u>Removing Autostart of Discord From Windows Operating System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shaping-the-future-of-windows-11-with-ai-assistance/"><u>Shaping the Future of Windows 11 with AI Assistance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sticking-with-the-classic-top-7-factors-favoring-windows-10/"><u>Sticking with the Classic: Top 7 Factors Favoring Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-windows-update-classification/"><u>Understanding Windows Update Classification</u></a></li>
<li><a href="https://win-amazing.techidaily.com/updated-drivers-for-your-epson-wf-3620-download-and-install-on-windows-10-8-or-7/"><u>Updated Drivers for Your Epson WF-3620 - Download & Install on Windows 10, 8 or 7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-deep-dive-mastery-of-activating-concealed-character-profile-tool/"><u>Windows Deep Dive: Mastery of Activating Concealed Character Profile Tool</u></a></li>
<li><a href="https://tech-revival.techidaily.com/44kz44oz44ou44ol44o844k44gn5yuv55s744ov44kh44kk44or44ks6zplusz5aow44ov44kh44kk44or44gr6lui5oplusb44gz44kl5oml6acg/"><u>コンピュータで動画ファイルを音声ファイルに転換する手順</u></a></li>
</ul></div>

