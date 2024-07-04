---
title: 4 Critical Tweaks to Reactivate Firewall
date: 2024-07-03T12:46:16.196Z
updated: 2024-07-04T12:46:16.196Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 4 Critical Tweaks to Reactivate Firewall
excerpt: This Article Describes 4 Critical Tweaks to Reactivate Firewall
keywords: React Firewall Trigger,Boost Firewall Performance,Enhance Security Settings,Update Firewall Configuration,Improve Firewall Efficiency,Optimize Firewall Functions,Revitalize Network Protection
thumbnail: https://thmb.techidaily.com/d35c94f12f755c322517a2947b55e4796f16febf7bfe5d4d03e4ed968b83a331.jpg
---

## 4 Critical Tweaks to Reactivate Firewall

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
<li><a href="https://win11-tips.techidaily.com/solving-windows-11s-ms-resource-and-apperror/"><u>Solving Windows 11'S Ms-Resource and AppError</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-stalled-keys-for-active-windows-11/"><u>Addressing Stalled Keys for Active Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-ignoring-soon-expiring-licenses-alerts-in-windows/"><u>Quick Fix for Ignoring Soon Expiring Licenses Alerts in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1011-hack-design-your-own-unique-pin-pattern/"><u>Windows 10/11 Hack: Design Your Own Unique Pin Pattern</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-measures-for-eradicating-white-screens-in-win1011/"><u>Efficient Measures for Eradicating White Screens in WIN10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-alteration-of-nat-types-in-windows-operating-systems/"><u>Effective Alteration of NAT Types in Windows Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-windows-hello-5-ways-to-tackle-fingerprint-problems/"><u>Unlock Windows Hello: 5 Ways to Tackle Fingerprint Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-web-speed-contrast-in-your-tech-world/"><u>Addressing the Web Speed Contrast in Your Tech World</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-no-network-reachable-errors-win/"><u>Eradicating No Network Reachable Errors (WIN)</u></a></li>
<li><a href="https://howto.techidaily.com/6-solutions-to-fix-error-505-in-google-play-store-on-oppo-a78-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Solutions to Fix Error 505 in Google Play Store on Oppo A78 5G | Dr.fone</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/edit-videos-for-free-top-online-tools-and-software/"><u>Edit Videos for Free Top Online Tools and Software</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-the-ultimate-showdown-final-cut-pro-vs-final-cut-express/"><u>New In 2024, The Ultimate Showdown Final Cut Pro vs Final Cut Express</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-circle-everything-you-need-to-know-on-oppo-f23-5g-drfone-by-drfone-virtual-android/"><u>Life360 Circle Everything You Need to Know On Oppo F23 5G | Dr.fone</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-2024-approved-elevating-your-sound-experience-the-top-10-alternatives-to-audacity-across-computers-and-tablets/"><u>Updated 2024 Approved Elevating Your Sound Experience The Top 10 Alternatives to Audacity Across Computers and Tablets</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-find-your-perfect-game-recorder-top-10-free-apps-for-2024/"><u>[New] Find Your Perfect Game Recorder  Top 10 Free Apps for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/midnight-tales-in-motion-evaluating-parental-choices-for-kids/"><u>Midnight Tales in Motion  Evaluating Parental Choices for Kids</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-vivo-y78t-drfone-by-drfone-virtual-android/"><u>How to get the dragon scale and evolution-enabled pokemon On Vivo Y78t? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-10-proven-methods-for-boosting-fb-search-rankings/"><u>[Updated] 2024 Approved  10 Proven Methods for Boosting FB Search Rankings</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/learn-how-to-trim-video-with-kapwing-editor-online/"><u>Learn How to Trim Video with Kapwing Editor Online</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>