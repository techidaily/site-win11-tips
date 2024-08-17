---
title: 4 Critical Tweaks to Reactivate Firewall
date: 2024-08-16T01:13:35.186Z
updated: 2024-08-17T01:13:35.186Z
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
<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After disabling the antivirus, try enabling the Windows Firewall and check if it functions properly now.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->

1. Once done, head over to the following location:  
`​​​​​​​​​​​​​​HKEY_LOCAL_MACHINE/SYSTEM/CurrentControlSet/Services/BFE`
2. Right-click on the **BFE** key and choose **Permissions** from the context menu.  
![Access permissions of the key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/access-permissions.jpg)
<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
3. Under "Group or user names", click on **Add**.
4. Type "Everyone" in the "Enter the object names to select" and click **OK**.  
![Modify permissions of the key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/modify-permissions.jpg)
<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://youtube-data.techidaily.com/024-approved-strategic-game-plays-with-top-casters/"><u>[New] 2024 Approved  Strategic Game Plays with Top Casters</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-capture-the-world-through-the-lens-of-mi-11/"><u>[New] In 2024, Capture the World Through the Lens of Mi 11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-cutting-edge-mac-cam-apps-a-look-past-bandicam/"><u>[New] In 2024, Cutting-Edge Mac Cam Apps  A Look Past Bandicam</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-the-3-essential-voice-logging-tactics-for-ipad/"><u>[New] The 3 Essential Voice Logging Tactics for iPad</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-2024-approved-navigating-social-medias-shadowy-side-spotting-fake-likes/"><u>[Updated] 2024 Approved  Navigating Social Media's Shadowy Side  Spotting Fake Likes</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-the-sound-of-success-audio-recording-guide/"><u>2024 Approved  The Sound of Success  Audio Recording Guide</u></a></li>
<li><a href="https://buynow-info.techidaily.com/acer-cb3-15-chromebook-assessment-topnotch-large-display-chrome-os-device/"><u>Acer CB3-15 Chromebook Assessment: Topnotch Large Display Chrome OS Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bootstrapping-a-powershell-session-as-an-admin-on-windows-11/"><u>Bootstrapping a PowerShell Session as an Admin on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breached-bitlocker-hold-firm-on-current-security/"><u>Breached BitLocker: Hold Firm on Current Security</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridge-the-gap-addressing-continuous-ps4-controller-disconnection/"><u>Bridge the Gap: Addressing Continuous PS4 Controller Disconnection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-tasks-and-power-in-win11-shortcut-setup/"><u>Bridging Tasks & Power in Win11 Shortcut Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-the-gap-a-blueprint-for-fixing-zero-x-eight-oh-three-one-f-in-windows-mail/"><u>Bridging the Gap: A Blueprint for Fixing Zero X Eight Oh Three One F in Windows Mail</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-successful-drag-operations-on-win11/"><u>Bring Back Successful Drag Operations on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-back-memories-craft-a-windows-1198-vibe/"><u>Bringing Back Memories: Craft a Windows 11/98 Vibe</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-back-original-settings-to-windows-11-touch-panel/"><u>Bringing Back Original Settings to Windows 11 Touch Panel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-google-chrome-to-life-with-windows-11/"><u>Bringing Google Chrome to Life with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/browser-download-techniques-after-windows-installation/"><u>Browser Download Techniques After Windows Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/building-a-window-for-secure-hardware-removal-on-windows-11/"><u>Building a Window for Secure Hardware Removal on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-built-in-graphics-card-for-second-monitor/"><u>Bypassing Built-In Graphics Card for Second Monitor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-do-not-have-access-error-when-uninstalling-apps/"><u>Bypassing Do Not Have Access Error When Uninstalling Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-frozen-right-click-options-in-windows/"><u>Bypassing Frozen Right-Click Options in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-server-slips-resolving-ms-store-failures-in-1011/"><u>Bypassing Server Slips: Resolving MS Store Failures in 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-win-11s-inbuilt-mobility-control/"><u>Bypassing Win 11'S Inbuilt Mobility Control</u></a></li>
<li><a href="https://win11-tips.techidaily.com/captivating-creations-top-editors-for-videos-on-your-win11-pc/"><u>Captivating Creations: Top Editors for Videos on Your Win11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/capturing-critical-windows-user-alerts-in-action/"><u>Capturing Critical Windows User Alerts in Action</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cease-windows-record-of-app-openings/"><u>Cease Windows Record of App Openings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/celebrate-yuletide-in-stunning-windowscapes/"><u>Celebrate Yuletide in Stunning Windowscapes</u></a></li>
<li><a href="https://win-dash.techidaily.com/hassle-free-method-for-installing-latest-battery-drivers-on-your-pcs-os/"><u>Hassle-Free Method for Installing Latest Battery Drivers on Your PC's OS</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-honor-magic-6-lite-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Honor Magic 6 Lite Phones with/without a PC</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-sign-excel-2021-files-online-by-ldigisigner-sign-a-excel-sign-a-excel/"><u>How to sign Excel 2021 files online</u></a></li>
<li><a href="https://extra-hints.techidaily.com/ideal-virtual-screenscapes-for-streamers/"><u>Ideal Virtual Screenscapes for Streamers</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-best-of-the-best-top-vlog-editor-apps-for-iphone-and-android/"><u>In 2024, Best of the Best Top Vlog Editor Apps for iPhone and Android</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-how-to-reverse-video-playback-on-android-phones/"><u>In 2024, How to Reverse Video Playback on Android Phones</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-master-igtv-edits-top-10-tools-ranked/"><u>In 2024, Master IGTV Edits  Top 10 Tools Ranked</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-seamless-integration-getting-snapchat-on-macos/"><u>In 2024, Seamless Integration  Getting Snapchat on macOS</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unlocking-effective-one-channel-streaming-techniques/"><u>In 2024, Unlocking Effective One-Channel Streaming Techniques</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-get-filmora-for-free-the-authorized-and-authentic-way/"><u>New In 2024, Get Filmora for Free The Authorized and Authentic Way</u></a></li>
<li><a href="https://screen-capture.techidaily.com/perfect-screen-capture-on-mac-the-top-5-recommended-approaches-for-2024/"><u>Perfect Screen Capture on Mac  The Top 5 Recommended Approaches for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/the-top-10-apple-iphone-13-pro-max-emualtors-for-windows-mac-and-android-drfone-by-drfone-ios/"><u>The Top 10 Apple iPhone 13 Pro Max Emualtors for Windows, Mac and Android | Dr.fone</u></a></li>
</ul></div>
