---
title: "Exploring Differences: CHKDSK, SFC, and Windows' Fixes"
date: 2024-08-16T02:17:33.403Z
updated: 2024-08-17T02:17:33.403Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Exploring Differences: CHKDSK, SFC, and Windows' Fixes"
excerpt: "This Article Describes Exploring Differences: CHKDSK, SFC, and Windows' Fixes"
keywords: CHKDSK Vs. SFC Windows Fixes,Chkdsk Functionality,System File Checker (SFC),Disk Error Repair,Windows Filesystem Health,Data Integrity Tools,OS File Verification
thumbnail: https://thmb.techidaily.com/c2d68683c182adeb644872ae9b6efd92813d48ae83b60547183327ca40ae4d54.jpg
---

## Exploring Differences: CHKDSK, SFC, and Windows' Fixes

### Quick Links

* [What Is CHKDSK and When Should You Use It?](#what-is-chkdsk-and-when-should-you-use-it)
* [What Is SFC Scannow and When Should You Use It?](#what-is-sfc-scannow-and-when-should-you-use-it)
* [What Is DISM and When Should You Use It?](#what-is-dism-and-when-should-you-use-it)
* [What Order Should You Run CHKDSK, SFC, and DISM In?](#what-order-should-you-run-chkdsk-sfc-and-dism-in)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Key Takeaways

* CHKDSK scans your hard drive for errors and bad sectors, and you should run it if your computer isn't booting properly.
* SFC scans and repairs Windows system files, so run it when you experience program crashes or missing DLL errors.
* DISM is the most powerful tool and fixes corrupt files in the Windows system image, use it when SFC can't repair files.

 When your PC starts reporting errors, slowing down, or misbehaving, you can use Windows's built-in diagnostic tools to try and fix the problem. CHKDSK, SFC, and DISM check the health of your hard drive and repair corrupt files, but the three tools work in different ways and target different areas of your system.

 CHKDSK, SFC, and DISM are system tools, and you can run all three. However, this can be time-consuming and unnecessary for your specific problem, so it's best to know when and how to use this trio of troubleshooting tools.

## What Is CHKDSK and When Should You Use It?

 CHKDSK (Check Disk) is the first Windows diagnostic tool you should try if your PC starts acting strangely. For example, if it hangs while shutting down or becomes frustratingly slow.

 CHKDSK scans your entire hard drive to find and fix errors in files and the file system itself. It also checks your drive for bad sectors (clusters of data that cannot be read), and either tries to repair them or tells your system not to use them.

 Windows may run CHKDSK on startup if it detects a problem with your hard drive, sometimes for innocuous reasons such as improper shutdown, but also more serious ones, including malware infection and impending drive failure. However, it won't actually fix any issues until instructed to do so.

 To prevent future errors and potential data loss, it's worth running CHKDSK manually as part of your PC maintenance routine. You can use one of the following methods:

### 1\. Run CHKDSK Through File Explorer

 You can run CHKDSK from the command prompt. If you're uncomfortable using the Command Prompt, open **File Explorer**, click **This PC**, right-click the drive you want to check and select **Properties**.

 Select the **Tools** tab and then select **Check** in the **Error-checking** section.

![Launch the Check Disk tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-error-checking.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If Windows determines that everything is running smoothly, it will suggest that you don't need to scan the drive. To run CHKDSK anyway, select **Scan drive**.

 The scan may take anywhere from a few minutes to half an hour, depending on the size and state of your drive. Once complete, CHKDSK will either tell you that no errors were found, or if it does find any, it will suggest you fix them.

### 2\. Run CHKDSK From the Command Prompt

 For greater control over the disk-checking process, you should run CHKDSK from an elevated Command Prompt. Follow these steps to continue:

1. Press the **Win** \+ **R** keys to open the Run dialog.
2. Type "cmd" in Run and press the **Ctrl** \+ **Shift** \+ **Enter** keys together to open Command Prompt as an administrator.
3. Click **Yes** in the User Account Control prompt.
4. In the Command Prompt window, type **chkdsk,** then space, followed by the drive letter you want to check. For example, **chkdsk c:** to scan your C: drive.  
![CHKDSK scan in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/chkdsk-scan.jpg)
5. Press **Enter** to scan for errors in read-only mode, which means no changes will be made.

 To make changes, you can use parameters with the CHKDSK command. Here are two you can use to fix problems:

* To make CHKDSK fix the problems it finds, type **chkdsk /f c:** (for your C: drive).
* To scan for bad sectors and errors, type **chkdsk /r c:**

 If you cannot run these commands because "the volume is in use by another process," Command Prompt will offer to schedule the scan for when your PC restarts. This should, however, only happen once. If the tool pops up whenever you boot your PC, you can [stop CHKDSK from running at every startup](https://www.makeuseof.com/tag/stuck-chkdsk-use-fix-right-way/) manually.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Is SFC Scannow and When Should You Use It?

 Whereas CHKDSK finds and fixes errors in the file system of your hard drive, **SFC (System File Checker)** specifically scans and repairs Windows system files. If it detects a file has been corrupted or modified, SFC automatically replaces that file with the correct version.

 Knowing when to use SFC is usually more obvious than with CHKDSK, which depends on the hunch that your hard drive isn't behaving correctly. If Windows programs are crashing, you're getting error messages about missing DLL files, or you're experiencing the dreaded Blue Screen of Death, then it's definitely time to run SFC.

[Open an elevated Command Prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), then type the following command and press **Enter** to execute:

`sfc /scannow`

 SFC will perform a full scan of your system and repair and replace any files that are damaged or missing using versions from the Windows component store (read the next section on DISM for more information on this and how SFC and DISM work can work together). The scan can take some time, but make sure you leave the Command Prompt window open until it's complete.

 If you only want to scan but not repair corrupted system files, type:

`sfc /verifyonly command`

 Once SFC has finished scanning, you'll see one of three messages:

* **Windows Resource Protection did not find any integrity violations.** This means that whatever's causing your PC problems isn't related to a system file.
* **Windows Resource Protection found corrupt files and successfully repaired them.** This should hopefully mean that your problems have been solved.
* **Windows Resource Protection found corrupt files but was unable to fix some of them.** This means that system files are to blame, but SFC can't replace them. Try running the tool again in Safe Mode. If you still get the same result, don't despair: it's time to use DISM.

![Screenshot of complete sfc scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/screenshot-of-complete-sfc-scan.jpg)
<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
## What Is DISM and When Should You Use It?

**DISM (Deployment Image Servicing and Management)** is the most powerful of the three Windows diagnostic tools. Although you shouldn't usually need to use the tools, it's the one to turn to when you're experiencing frequent crashes, freezes, and errors, but SFC either can't repair your system files or is unable to run at all.

 While CHKDSK scans your hard drive and SFC your system files, DISM detects and fixes corrupt files in the component store of the Windows system image so that SFC can work properly. It can also help with Windows updates, driver integration, and boot issues you might be facing.

[Create a backup of your data](https://www.makeuseof.com/tag/ultimate-windows-10-data-backup-guide/) before running DISM, just in case something goes wrong.

 As with CHKDSK and SFC, you'll need to open an elevated Command Prompt (or Administrator Terminal Window on Windows 11) to run DISM. To save you the time and risk of performing repairs unnecessarily, you can first check if the image is corrupted without making any changes. Type the following command and press Enter:

`Dism /Online /Cleanup-Image /CheckHealth`

![windows dism check in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/windows-dism-check-in-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->

 The scan should only take a few seconds. If no corruption is detected, you can run a more advanced scan to determine if the component store is healthy and repairable, again without making any changes, by typing:

`Dism /Online /Cleanup-Image /ScanHealth`

 If DISM reports that there are problems with the system image, run another advanced scan to repair these issues automatically. DISM will connect to Windows Update to download and replace damaged files as required. Note that the process may take up to 10 minutes and hang for a while at 20 seconds, but this is normal. Type this command:

`Dism /Online /Cleanup-Image /RestoreHealth  
`

![dism scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dism-scan.jpg)

 Once the scan and repairs are complete, restart your PC and run SFC again to replace your corrupt or missing system files.

## What Order Should You Run CHKDSK, SFC, and DISM In?

 Now that you understand what CHKDSK, SFC, and DISM do, running one or more of these Windows troubleshooting tools will hopefully help you fix your PC.

 However, a common question concerns the order in which you should run these system tests. Should you always run CHKDSK first? Or how about always running DISM before SFC?

 There is no specific order to CHKDSK, SFC, and DISM, as why you run each tool depends on the issue you're experiencing. However, if you run SFC and it finds corrupt files and other issues, you should then run DISM to fix the Component Store and then run SFC again to fix any broken files.

 If you're still having trouble, perform a System Restore. This will restore your system files, settings, and programs to a time when they worked properly. If your system wasn't damaged when the restore point was created, it may solve your corruption problems.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-clips.techidaily.com/new-create-engaging-facebook-covers/"><u>[New] Create Engaging Facebook Covers</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-dual-display-documentation-technique/"><u>[New] In 2024, Dual Display Documentation Technique</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-seamless-integration-of-snap-camera-for-enhanced-online-participation/"><u>[Updated] 2024 Approved  Seamless Integration of Snap Camera for Enhanced Online Participation</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-capture-cumulative-chronicles-for-2024/"><u>[Updated] Capture Cumulative Chronicles for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-unveiling-premium-screen-recorders-in-tech/"><u>[Updated] In 2024, Unveiling Premium Screen Recorders in Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/change-screen-direction-with-windows-settings/"><u>Change Screen Direction with Windows Settings</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/tive-conclaves-educational-yt-powerhouses-for-2024/"><u>Cognitive Conclaves  Educational YT Powerhouses for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combatting-unsuccessful-onedrive-operations-on-os/"><u>Combatting Unsuccessful OneDrive Operations on OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-system-details-ip-and-mac-with-ps-on-windows/"><u>Discovering System Details: IP & MAC with PS on Windows</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/effortless-earnings-channel-size-no-longer-a-challenge-for-2024/"><u>Effortless Earnings  Channel Size No Longer a Challenge for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-wi-fi-connection-speed-in-windows-11-with-these-tips/"><u>Enhance Wi-Fi Connection Speed in Windows 11 With These Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-real-time-rendering-cutting-down-lag-time/"><u>Enhancing Real-Time Rendering: Cutting Down Lag Time</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-alternatives-when-bitlocker-disappears-on-pcs/"><u>Exploring Alternatives When BitLocker Disappears on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-loading-device-drivers-on-windows-11/"><u>Fixing Non-Loading Device Drivers on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-responsive-spotify-app-on-windows-11-pcs/"><u>Fixing Non-Responsive Spotify App on Windows 11 PCs</u></a></li>
<li><a href="https://change-location.techidaily.com/here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-vivo-y100-5g-drfone-by-drfone-virtual-android/"><u>Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Vivo Y100 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-solidify-the-save-feature-on-nvidias-windows-control-center/"><u>How to Solidify the Save Feature on NVidia's Windows Control Center</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-google-play-location-on-nubia-red-magic-8s-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Google Play Location On Nubia Red Magic 8S Pro | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-two-ways-to-track-my-boyfriends-xiaomi-redmi-note-12-pro-4g-without-him-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Two Ways to Track My Boyfriends Xiaomi Redmi Note 12 Pro 4G without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-access-the-fastest-way-to-snipping-tool-win-11/"><u>Instant Access: The Fastest Way to Snipping Tool Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-context-menu-quick-uninstall-in-win-1110/"><u>Mastering Context Menu: Quick Uninstall in Win 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-video-drivers-errors/"><u>Mastering the Art of Fixing Video Drivers Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-unreachable-issues-fixing-mb-service-disconnect-in-windows-11/"><u>Overcoming Unreachable Issues: Fixing MB Service Disconnect in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pro-tips-for-leveraging-the-power-of-windows-11-calendar/"><u>Pro Tips for Leveraging the Power of Windows 11 Calendar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/purging-steams-domain-name-system-on-windows-systems/"><u>Purging Steam's Domain Name System on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinvigorating-computers-top-8-windows-tricks/"><u>Reinvigorating Computers: Top 8 Windows Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-changing-windows-11-default-applications/"><u>Step-by-Step: Changing Windows 11 Default Applications</u></a></li>
<li><a href="https://facebook.techidaily.com/strategizing-discreet-social-media-exposure/"><u>Strategizing Discreet Social Media Exposure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-the-benefits-in-not-muting-wins-11-pushes/"><u>Uncovering the Benefits in Not Muting Wins 11 Pushes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unnoticed-slowdown-agents-innocent-looking-apps-for-windows-11/"><u>Unnoticed Slowdown Agents: Innocent-Looking Apps for Windows 11</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/unpacking-the-features-a-comprehensive-review-of-logitechs-c920-hd-webcam/"><u>Unpacking the Features: A Comprehensive Review of Logitech's C920 HD Webcam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-windows-11-faces-a-slow-uptake-from-users/"><u>Why Windows 11 Faces a Slow Uptake From Users</u></a></li>
</ul></div>
