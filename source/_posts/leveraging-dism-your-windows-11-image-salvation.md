---
title: "Leveraging Dism: Your Windows 11 Image Salvation"
date: 2024-09-01T05:14:01.085Z
updated: 2024-09-02T05:14:01.085Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Leveraging Dism: Your Windows 11 Image Salvation"
excerpt: "This Article Describes Leveraging Dism: Your Windows 11 Image Salvation"
keywords: Win11 Image Recovery,Save Windows Image,Rescue Windows PC,Revive Windows PC,Fix Windows Image,Dism Image Repair,Cleanup Windows Image
thumbnail: https://thmb.techidaily.com/bab43c6ebbd68c7b02aa8931b44c8b3c5cf156c7a7bd1aa24fbe3ea34de877b1.jpg
---

## Leveraging Dism: Your Windows 11 Image Salvation

 Windows 11, like its predecessor, features the built-in Deployment Image Servicing and Management (DISM), a command-line utility to troubleshoot critical system errors. The DISM commands can help you fix Blue Screen of Death (BSOD) errors, a slow computer due to broken system files, and even repair the Windows Recovery Environment.

 In this article, we’ll show you how you can use the DISM and System File Checker utility to repair your damaged Windows 11 image and installation.

## How to Use the DISM Command in Windows 11

 The DISM command-line utility is a multi-purpose tool. It allows the system administrator to prepare and service Windows images. In addition, you can use the DISM tool in combination with the System File Checker utility to recover your Windows computer from critical failure.

 While DISM supports multiple specified commands, to repair your Windows computer, you only need to know the DISM CheckHealth, DISM ScanHealth, and DISM RestoreHealth commands.

 If you can boot into Windows 11, you can run the DISM command from an elevated PowerShell console or Command Prompt. If not, you’ll need to [boot into the Windows Recovery Environment](boot%20into%20the%20Windows%20Recovery%20Environment) and launch Command Prompt from **Advanced Options** to run DISM.

## Check Your System Health Using the DISM CheckHealth Command

 You can check for any file corruption using the DISM CheckHealth command. It is a diagnostic tool used to detect system image corruption and report the same. However, it doesn’t perform any repair.

 To run the CheckHealth command:

1. Press the **Win** key and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator**.  
![DISM scan health powershell command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-clean-health-powershell-command.jpg)
3. In the Command Prompt window, type the following command and press **Enter**:  
`DISM /Online /Cleanup-Image /CheckHealth`
4. In the above command, the **/Online** parameter specifies the scan must be performed on the currently running operating system. The **/Cleanup-Image** parameter specifies the operation is related to Windows image repair.
5. When executed, the command will show the report as “**The component stored has been corrupted**” or “**No component store corrupted detected.**” depending on whether a component store corruption is found.  
![DISM powershell CheckHealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-powershell-checkhealth-command.jpg)
6. If you use PowerShell, use the following command instead:  
`Repair-WindowsImage -Online -CheckHealth`
7. The PowerShell command will report your image status to indicate whether it is **Healthy**, **Repairable** or **Non-repairable**. A healthy image doesn’t need any further action, and you can proceed to run the SFC tool.

 If the image is repairable, you can use the RestoreHealth command to use Windows Update to fix any corruption. However, for a non-repairable image, you may need to perform a clean install to fix your computer.

## Perform an Advanced System Image Scan with the ScanHealth Command

![DISM scan health command PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-scan-health-command-powershell.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You can use the DISM ScanHealth command to perform an advanced scan of your Windows 11 system image. This will check your system for component store corruption and save the report to a log file.

 To run the DISM ScanHealth command:

1. Open **PowerShell** as administrator.
2. Type the following command and press Enter:  
`DISM /Online /Cleanup-Image /ScanHealth`
3. This process may take some time to complete. Once done, it will report any issues with the component store.
4. If an issue is detected, run the DISM RestoreHealth command to repair your Windows image.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Run the DISM RestoreHealth Command to Repair the Windows System Image

![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dism-scan-health-restore-health-command-prompt.jpg)

 The DISM RestoreHealth command uses Windows Update to provide the necessary files to fix file corruption and repair the Windows 11 system image. However, you must be connected to the internet so that the DISM tool can download and restore the files needed to perform a repair.

 To run the DISM RestoreHealth command:

1. Open **Windows PowerShell** as administrator.
2. Next, type the following command and press **Enter**:  
`DISM.exe /Online /Cleanup-image /RestoreHealth`
3. The DISM utility will perform a scan and start repairing the Windows system image. This process may take some time to complete. So, wait till the progress bar reaches 100%.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
## Repair System Image Using an Alternate Repair Source

 The DISM RestoreHealth command may not work if your computer is not connected to the internet or if the Windows Update component is corrupt. In this situation, you can use a Windows installation media or a mounted Windows ISO as a local source to repair the system image.

 First, [create a bootable Windows 11 USB drive](https://www.makeuseof.com/windows-11-create-bootable-usb-drive/). Once you have the installation media ready, connect it to your computer and proceed with the below steps.

 To repair your Windows 11 system image using DISM and a local repair source:

1. Press **Win + E** to open **File Explorer**.
2. Open your installation media drive, open the **Sources** folder and make sure the **install.wim** file exists. Also, note the driver letter assigned to your installation media. In this instance, our installation media is assigned the drive letter **(I:)**.  
![install wim file in Windows 11 installation media](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/install-wim-file-in-windows-11-installation-media.jpg)
3. Next, type the following command to run the **DISM RestoreHealth** command with the installation media as a repair source:  
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
`DISM /Online /Cleanup-Image /RestoreHealth /Source:I\Sources\install.wim /LimitAccess`
4. In the above command, replace the placeholder **:I** with your installation media drive letter. Also, the **LimitAccess** command is an optional parameter that restricts DISM access to the specified source and prevents it from using **Windows Update** as a repair source.
5. Once the process is complete, you can close Command Prompt and run the **System File Checker** utility to complete the repair process.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## Repair Your Windows Installation Using the System File Checker (SFC) Utility

![run system file checker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/run-system-file-checker.png)

 Once you have successfully repaired your Windows 11 system image using the DISM RestoreHealth command, run the System File Checker (SFC) utility. It will scan your Windows installation for system file corruption and fix them automatically.

 In almost all instances, you must run the System File Checker utility after using the DISM image repair command to complete the repair process. Here’s how to do it:

1. Press **Win + X** to open the **WindowsX** menu.
2. Click **Terminal (Admin)** to launch the **Windows** Terminal app as administrator.
3. In the **Terminal** window, type the following command to run the **System File Checker** utility:  
`sfc /scannow`
4. When you run the above command, the System File Checker utility will start verifying the integrity of system files to detect corruption. If detected, it’ll automatically try to repair by replacing the files with a cached copy located at **%WinDir%\\System32\\dllcache.**

 The SFC process may take some time to complete and often may feel stuck at some stage. If you see no progress for a long time, press the **Enter** key a few times on your keyboard to refresh the Command Prompt window to view real-time progress.

 After the process is complete, restart your computer and check for any improvements. If the issue persists, run the **sfc /scannow** command again to see if that helps fix the problem.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
## Repair and Recover Your Windows System Image Using DISM and SFC

 DISM makes it easy to repair a corrupt Windows image. It works both online using Windows Update and offline with a WIM file. The steps to use DISM may look complicated at first glance; however, it only takes two commands and an elevated Command Prompt to repair your Windows 11 image and installation.

 In this article, we’ll show you how you can use the DISM and System File Checker utility to repair your damaged Windows 11 image and installation.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-info.techidaily.com/new-in-2024-fundamentals-of-online-tale-creation-methods/"><u>[New] In 2024, Fundamentals of Online Tale Creation Methods</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-thrilling-trials-and-daring-escapades-a-curated-list-of-greatest-games-top-10/"><u>[New] Thrilling Trials & Daring Escapades  A Curated List of Greatest Games (Top 10)</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-frame-your-life-with-iphones-top-10-photo-rules/"><u>[Updated] In 2024, Frame Your Life with iPhone's Top 10 Photo Rules</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-optimize-chromes-voice-the-best-web-based-vocal-modification-apps/"><u>[Updated] Optimize Chrome's Voice  The Best Web-Based Vocal Modification Apps</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/compatibility-guide-can-nintendo-switch-support-bluetooth-earbuds-like-airpods/"><u>Compatibility Guide: Can Nintendo Switch Support Bluetooth Earbuds Like AirPods?</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-contacts-files-on-poco-c51-by-fonelab-android-recover-contacts/"><u>Complete guide for recovering contacts files on Poco C51.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-and-defeating-the-d3d11-compatible-gpu-predicament-in-w11w10/"><u>Decoding and Defeating the D3D11-Compatible GPU Predicament in W11/W10</u></a></li>
<li><a href="https://tech-hub.techidaily.com/decoding-chatgpts-shared-link-ecosystem/"><u>Decoding ChatGPT's Shared Link Ecosystem</u></a></li>
<li><a href="https://tech-hub.techidaily.com/discover-secure-chat-options-engage-with-duckduckgos-ai-including-chatgpt/"><u>Discover Secure Chat Options: Engage with DuckDuckGo’s AI, Including ChatGPT!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-screen-captures-in-windows-snip-tool-vs-printscreen/"><u>Efficient Screen Captures in Windows: Snip Tool Vs. Printscreen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expediting-windows-ram-cache-deletion-process/"><u>Expediting Windows RAM Cache Deletion Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-iphone-to-pc-mastering-the-use-of-apple-maps/"><u>From iPhone to PC: Mastering the Use of Apple Maps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-scribbling-in-windows-11-effortlessly/"><u>Get Scribbling in Windows 11 Effortlessly</u></a></li>
<li><a href="https://network-issues.techidaily.com/guides-on-fixing-acer-led-displays/"><u>Guides on Fixing Acer LED Displays</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-manage-your-laptops-energy-efficient-features/"><u>How to Manage Your Laptop's Energy Efficient Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reveal-hidden-elements-in-windows-11-ui/"><u>How to Reveal Hidden Elements in Windows 11 UI</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-12-to-other-iphone-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 12 to other iPhone? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-turn-off-virtualization-on-windows-11/"><u>How to Turn Off Virtualization on Windows 11</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-relaxation-playlist-20-sweetest-country-tunes-on-tiktok/"><u>In 2024, Relaxation Playlist  20 Sweetest Country Tunes on TikTok</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-ultimate-5-vr-sets-elevating-uav-experience/"><u>In 2024, Ultimate 5 VR Sets Elevating UAV Experience</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-realme-gt-neo-5-se-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On Realme GT Neo 5 SE? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insider-look-at-opened-windows-content/"><u>Insider Look at Opened Windows Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-command-prompt-a-guide-to-user-management/"><u>Navigating Command Prompt: A Guide to User Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-dll-loss-restoring-d3dx939-on-windows-11/"><u>Overcoming DLL Loss: Restoring D3DX9_39 on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-startup-hurdles-for-photoshop-on-windows-1011/"><u>Overcoming Startup Hurdles for Photoshop on Windows 10/11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/partner-filmmaking-for-channelnode-increase-strategies-for-2024/"><u>Partner Filmmaking for Channelnode Increase Strategies for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/precise-windows-lockout-after-downtime/"><u>Precise Windows Lockout After Downtime</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/prove-your-skills-fast-and-precise-video-edits-on-windows-11/"><u>Prove Your Skills  Fast & Precise Video Edits on Windows 11</u></a></li>
<li><a href="https://techidaily.com/remove-poco-m6-5g-unlock-screen-by-drfone-android-unlock-android-unlock/"><u>Remove Poco M6 5G unlock screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rescue-lost-co-pilot-in-windows-new-era-11/"><u>Rescue Lost Co-Pilot in Windows' New Era, 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-keyboard-issues-in-the-windows-snipper/"><u>Resolving Keyboard Issues in the Windows Snipper</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-steam-storage-write-failure/"><u>Resolving Windows' Steam Storage Write Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-your-pcs-bluetooth-link-with-these-9-essential-tips-for-win-11/"><u>Restore Your PC's Bluetooth Link with These 9 Essential Tips for Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamping-mouse-interaction-with-windows-clicklock-feature/"><u>Revamping Mouse Interaction with Windows ClickLock Feature</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/ryan-kaji-youthful-wealth-through-internet-popularity/"><u>Ryan Kaji  Youthful Wealth Through Internet Popularity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/smooth-the-waters-fixing-icloud-install-problems-on-windows/"><u>Smooth the Waters: Fixing iCloud Install Problems on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-switching-between-foreign-languages-on-windows-devices/"><u>Speedy Switching Between Foreign Languages on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-altering-windows-index-settings/"><u>Step-by-Step: Altering Windows Index Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-installation-craft-a-focused-fast-bootable-win-11-drive/"><u>Streamline Your Installation: Craft a Focused, Fast Bootable Win 11 Drive</u></a></li>
<li><a href="https://tech-hub.techidaily.com/strengthening-empathy-through-ai-dialogue/"><u>Strengthening Empathy Through AI Dialogue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/supercharge-your-routine-with-the-finest-6-apps-for-windows-11-users/"><u>Supercharge Your Routine with the Finest 6 Apps for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-restoration-of-your-windows-application-performance/"><u>Swift Restoration of Your Windows Application Performance</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-future-of-smartphones-delving-into-teslas-mobile-ambitions-expected-price-points-release-timeframe-and-rumored-features/"><u>The Future of Smartphones? Delving Into Tesla's Mobile Ambitions: Expected Price Points, Release Timeframe, and Rumored Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tidy-up-your-windows-past-with-easy-techniques/"><u>Tidy Up Your Windows Past with Easy Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-reverting-windows-folders-to-full-editability/"><u>Tips for Reverting Windows Folders to Full Editability</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-potential-integrating-previous-pc-software-with-newer-os/"><u>Unlocking Potential: Integrating Previous PC Software with Newer OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-secrets-the-component-services-of-windows-11/"><u>Unlocking Secrets: The Component Services of Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-secrets-of-successful-gmaps-integration-in-windows/"><u>Unveiling the Secrets of Successful GMaps Integration in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-context-menu-incorporating-copy-and-move-commands-into-folder-options-win-11/"><u>Upgrade Context Menu: Incorporating Copy & Move Commands Into Folder Options (Win 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-over-windows-correcting-access-violations/"><u>Winning Over Windows: Correcting Access Violations</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>