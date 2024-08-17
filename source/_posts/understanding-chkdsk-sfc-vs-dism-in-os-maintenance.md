---
title: Understanding CHKDSK, SFC Vs. DISM in OS Maintenance
date: 2024-08-16T01:43:16.718Z
updated: 2024-08-17T01:43:16.718Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Understanding CHKDSK, SFC Vs. DISM in OS Maintenance
excerpt: This Article Describes Understanding CHKDSK, SFC Vs. DISM in OS Maintenance
keywords: Chkdsk Basics,SFC Overview,Disk Check Pro,Fixed Sys Image,System File Repair,DISM Tools Guide,OS Maintenance Tech
thumbnail: https://thmb.techidaily.com/42a3217d9873863c48091846f5f8a9e9b9b6456440b499628df593e7d229a025.jpg
---

## Understanding CHKDSK, SFC Vs. DISM in OS Maintenance

### Quick Links

* [What Is CHKDSK and When Should You Use It?](#what-is-chkdsk-and-when-should-you-use-it)
* [What Is SFC Scannow and When Should You Use It?](#what-is-sfc-scannow-and-when-should-you-use-it)
* [What Is DISM and When Should You Use It?](#what-is-dism-and-when-should-you-use-it)
* [What Order Should You Run CHKDSK, SFC, and DISM In?](#what-order-should-you-run-chkdsk-sfc-and-dism-in)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->

 If Windows determines that everything is running smoothly, it will suggest that you don't need to scan the drive. To run CHKDSK anyway, select **Scan drive**.

 The scan may take anywhere from a few minutes to half an hour, depending on the size and state of your drive. Once complete, CHKDSK will either tell you that no errors were found, or if it does find any, it will suggest you fix them.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
### 2\. Run CHKDSK From the Command Prompt

 For greater control over the disk-checking process, you should run CHKDSK from an elevated Command Prompt. Follow these steps to continue:

1. Press the **Win** \+ **R** keys to open the Run dialog.
2. Type "cmd" in Run and press the **Ctrl** \+ **Shift** \+ **Enter** keys together to open Command Prompt as an administrator.
3. Click **Yes** in the User Account Control prompt.
4. In the Command Prompt window, type **chkdsk,** then space, followed by the drive letter you want to check. For example, **chkdsk c:** to scan your C: drive.  
![CHKDSK scan in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/chkdsk-scan.jpg)
<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Press **Enter** to scan for errors in read-only mode, which means no changes will be made.

 To make changes, you can use parameters with the CHKDSK command. Here are two you can use to fix problems:

* To make CHKDSK fix the problems it finds, type **chkdsk /f c:** (for your C: drive).
* To scan for bad sectors and errors, type **chkdsk /r c:**

 If you cannot run these commands because "the volume is in use by another process," Command Prompt will offer to schedule the scan for when your PC restarts. This should, however, only happen once. If the tool pops up whenever you boot your PC, you can [stop CHKDSK from running at every startup](https://www.makeuseof.com/tag/stuck-chkdsk-use-fix-right-way/) manually.

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
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
## What Is DISM and When Should You Use It?

**DISM (Deployment Image Servicing and Management)** is the most powerful of the three Windows diagnostic tools. Although you shouldn't usually need to use the tools, it's the one to turn to when you're experiencing frequent crashes, freezes, and errors, but SFC either can't repair your system files or is unable to run at all.

 While CHKDSK scans your hard drive and SFC your system files, DISM detects and fixes corrupt files in the component store of the Windows system image so that SFC can work properly. It can also help with Windows updates, driver integration, and boot issues you might be facing.

[Create a backup of your data](https://www.makeuseof.com/tag/ultimate-windows-10-data-backup-guide/) before running DISM, just in case something goes wrong.

 As with CHKDSK and SFC, you'll need to open an elevated Command Prompt (or Administrator Terminal Window on Windows 11) to run DISM. To save you the time and risk of performing repairs unnecessarily, you can first check if the image is corrupted without making any changes. Type the following command and press Enter:

`Dism /Online /Cleanup-Image /CheckHealth`

![windows dism check in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/windows-dism-check-in-command-prompt.jpg)

 The scan should only take a few seconds. If no corruption is detected, you can run a more advanced scan to determine if the component store is healthy and repairable, again without making any changes, by typing:

`Dism /Online /Cleanup-Image /ScanHealth`

 If DISM reports that there are problems with the system image, run another advanced scan to repair these issues automatically. DISM will connect to Windows Update to download and replace damaged files as required. Note that the process may take up to 10 minutes and hang for a while at 20 seconds, but this is normal. Type this command:

`Dism /Online /Cleanup-Image /RestoreHealth  
`

![dism scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dism-scan.jpg)

 Once the scan and repairs are complete, restart your PC and run SFC again to replace your corrupt or missing system files.

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://on-screen-recording.techidaily.com/new-best-10-de-stress-fun-titles-for-playtime/"><u>[New] Best 10 De-Stress Fun Titles for Playtime</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-20-must-have-video-tools-for-new-creators/"><u>[New] In 2024, 20 Must-Have Video Tools For New Creators</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-epic-soundscape-trending-audio-for-cutting-edge-youtube-short-videos/"><u>[New] In 2024, Epic Soundscape  Trending Audio for Cutting-Edge YouTube Short Videos</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-boosting-vimeo-content-delivery/"><u>2024 Approved  Boosting Vimeo Content Delivery</u></a></li>
<li><a href="https://location-social.techidaily.com/4-most-known-ways-to-find-someone-on-tinder-for-realme-10t-5g-by-name-drfone-by-drfone-virtual-android/"><u>4 Most-Known Ways to Find Someone on Tinder For Realme 10T 5G by Name | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-task-managers-welcome-screenscape-in-win11/"><u>Adjusting Task Manager's Welcome Screenscape in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-the-way-for-smooth-steam-disk-operations/"><u>Clearing the Way for Smooth Steam Disk Operations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-blocked-paths-in-windows-update/"><u>Clearing Up Blocked Paths in Windows Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensible-methodology-for-adding-intel-ethernet-support/"><u>Comprehensible Methodology for Adding Intel Ethernet Support</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortlessly-connect-airpods-to-windows-machines/"><u>Effortlessly Connect AirPods to Windows Machines</u></a></li>
<li><a href="https://extra-tips.techidaily.com/enhance-your-editing-with-fcps-top-10-plugins/"><u>Enhance Your Editing with FCP's Top 10 Plugins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-data-protection-turning-on-controlled-folder-access/"><u>Ensuring Data Protection: Turning on Controlled Folder Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-validity-of-windows-11-temp-files/"><u>Ensuring Validity of Windows 11 Temp Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-advice-for-eliminating-windows-temp-files/"><u>Expert Advice for Eliminating Windows' Temp Files</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/expert-strategies-for-efficient-whatsapp-use-for-2024/"><u>Expert Strategies for Efficient WhatsApp Use for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gpt4all-for-pcs-local-free-chatgpt-version/"><u>GPT4All for PCs: Local, Free ChatGPT Version.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-changing-windows-11-search-icons-backwards/"><u>Guidelines for Changing Windows 11 Search Icons Backwards</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-google-frp-lock-from-xiaomi-redmi-note-13-pro-5g-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock from Xiaomi Redmi Note 13 Pro 5G Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-empower-your-taskbar-with-new-features/"><u>How to Empower Your Taskbar with New Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-unreadable-source-issue-on-your-windows-pc/"><u>How to Fix ‘Unreadable Source’ Issue on Your Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-turn-your-voice-to-text-in-real-time-with-whisper-desktop/"><u>How to Turn Your Voice to Text in Real Time With Whisper Desktop</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-full-assessment-samsungs-360-degree-capture-device/"><u>In 2024, Full Assessment  Samsung's 360-Degree Capture Device</u></a></li>
<li><a href="https://blog-min.techidaily.com/in-2024-how-to-teleport-your-gps-location-on-honor-x50-gt-drfone-by-drfone-virtual-android/"><u>In 2024, How To Teleport Your GPS Location On Honor X50 GT? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-ipogo-will-be-the-new-ispoofer-on-samsung-galaxy-z-fold-5-drfone-by-drfone-virtual-android/"><u>In 2024, iPogo will be the new iSpoofer On Samsung Galaxy Z Fold 5? | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/instagram-filters-a-2023-guide-to-enhanced-photography/"><u>Instagram Filters  A 2023 Guide to Enhanced Photography</u></a></li>
<li><a href="https://win11-tips.techidaily.com/intel-unison-explained-easy-mobile-dialing-on-the-latest-windows-11/"><u>Intel Unison Explained: Easy Mobile Dialing on the Latest Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/investigating-windows-process-hostaggregate-use-and-security-implications/"><u>Investigating Windows' Process HostAggregate: Use & Security Implications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/latency-free-leap-essential-tips-for-clean-video-windows-streams/"><u>Latency-Free Leap: Essential Tips for Clean Video Windows Streams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-a-halted-warcraft-update-sequence/"><u>Navigating a Halted Warcraft Update Sequence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-d3d11-gpu-error-landscape-for-windows-1110/"><u>Navigating the D3D11 GPU Error Landscape for Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-no-server-issues-fixes-and-tips-for-apex-on-windows-(156-chars/"><u>Overcoming 'No Server' Issues: Fixes and Tips for Apex on Windows (<156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-problems-with-saving-windows-volume-configurations/"><u>Overcoming Problems with Saving Window's Volume Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-exception-breakpoint-obstacle/"><u>Overcoming Windows Exception Breakpoint Obstacle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-data-theft-controlling-removable-storage-on-pcs/"><u>Preventing Data Theft: Controlling Removable Storage on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reset-and-reactivate-a-windows-users-guide-for-ms-store/"><u>Reset and Reactivate: A Windows User's Guide for MS Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalizing-steam-data-flow-escaping-slowdown-traps/"><u>Revitalizing Steam Data Flow: Escaping Slowdown Traps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-telnet-activation-on-latest-windows-systems/"><u>Secure Telnet Activation on Latest Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-hidden-time-display-on-windows-bar/"><u>Setting Up Hidden Time Display on Window's Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-file-management-with-windows-autodelete-feature/"><u>Simplifying File Management with Windows' AutoDelete Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speeding-up-a-halted-download-the-windows-method/"><u>Speeding up a Halted Download: The Windows Method</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-incorrect-windows-duo-software-setup/"><u>Steps to Rectify Incorrect Windows Duo Software Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-tackle-windows-package-unopenable-issue-effectively/"><u>Steps to Tackle Windows Package Unopenable Issue Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-display-embrace-tiled-workspace/"><u>Streamline Your Display: Embrace Tiled Workspace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-internal-audio-error-in-audacity-win-11-and-11/"><u>Tackling Internal Audio Error in Audacity, Win 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-dims-handbook-for-windows-11-repair/"><u>The Complete DIMS Handbook for Windows 11 Repair</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-5-tactics-reactivating-windows-defender-protection-mechanism/"><u>Top 5 Tactics: Reactivating Windows Defender Protection Mechanism</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-app-start-issue-qt-plugin-not-available/"><u>Troubleshooting App Start Issue: Qt Plugin Not Available</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-wasd-isolation-necessity-or-concern/"><u>Understanding WASD Isolation: Necessity or Concern?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-full-capability-of-windows-11-with-multi-display-setup/"><u>Unlock the Full Capability of Windows 11 With Multi-Display Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-adopting-sudo-can-transform-your-windows-experience/"><u>Why Adopting Sudo Can Transform Your Windows Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-clean-boot-a-beginners-approach/"><u>Windows 11 Clean Boot: A Beginner's Approach</u></a></li>
</ul></div>
