---
title: "Enabling Firewall: Essential Fixes for a Shutdown System"
date: 2024-06-25T16:07:47.893Z
updated: 2024-06-26T16:07:47.893Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/reinvigorating-faulty-troubleshooters-in-windows-os/"><u>Reinvigorating Faulty Troubleshooters in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-speech-detection-with-windows/"><u>Streamlining Speech Detection with Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bf-price-war-save-612-on-endless-win10-lifetime-life/"><u>BF Price War: Save $6.12 on Endless Win10 Lifetime Life</u></a></li>
<li><a href="https://win11-tips.techidaily.com/raising-the-bar-for-user-interface-in-w11-larger-icons/"><u>Raising the Bar for User Interface in W11: Larger Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-windows-error-loadlib-err-87/"><u>Mitigating Windows Error LoadLib Err 87</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-usb-health-in-windows-a-troubleshooting-checklist/"><u>Restoring USB Health in Windows: A Troubleshooting Checklist</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-advanced-shortcuts-into-windows-explorer-menus/"><u>Integrating Advanced Shortcuts Into Windows Explorer Menus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-why-files-carry-an-x-marking/"><u>Understanding Why Files Carry an X Marking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sidestep-common-snip-and-sketch-screenshot-hurdles-4-fixes/"><u>Sidestep Common Snip & Sketch Screenshot Hurdles: 4 Fixes</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-lasting-freedom-how-to-banish-youtube-shorts-permanently/"><u>2024 Approved  Lasting Freedom  How To Banish YouTube Shorts Permanently</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/in-2024-bold-and-creative-pfp-options-for-a-unique-tiktok-look/"><u>In 2024, Bold & Creative PFP Options for a Unique TikTok Look</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-from-mundane-to-marvelous-proven-methods-to-record-everyday-life-and-adventures-in-sims-4/"><u>[New] From Mundane to Marvelous  Proven Methods to Record Everyday Life and Adventures in Sims 4</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-20-youtube-time-savers-that-will-skyrocket-engagement-rates/"><u>[Updated] 2024 Approved  20 YouTube Time Savers That Will Skyrocket Engagement Rates</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-ultimate-guide-7-steps-for-stellar-cooking-films/"><u>[Updated] The Ultimate Guide  7 Steps for Stellar Cooking Films</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/premium-power-solutions-for-gopro-hero5-black-certified-and-imposters-for-2024/"><u>Premium Power Solutions for GoPro Hero5 Black - Certified & Imposters for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-art-of-flawless-inshot-edit-transitions/"><u>The Art of Flawless Inshot Edit Transitions</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-perfect-gifs-essential-virtual-meet-scenes/"><u>[New] Perfect GIFs  Essential Virtual Meet Scenes</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-elite-arena-top-10-royale-game-spectacles/"><u>[New] In 2024, Elite Arena  Top 10 Royale Game Spectacles</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-quick-tips-for-transforming-pinterest-videos-into-mp3s/"><u>In 2024, Quick Tips for Transforming Pinterest Videos Into MP3s</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>