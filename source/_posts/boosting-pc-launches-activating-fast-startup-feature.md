---
title: "Boosting PC Launches: Activating Fast Startup Feature"
date: 2024-08-16T01:08:49.391Z
updated: 2024-08-17T01:08:49.391Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Boosting PC Launches: Activating Fast Startup Feature"
excerpt: "This Article Describes Boosting PC Launches: Activating Fast Startup Feature"
keywords: Fast Boot PC,Quick PC Start,Launch Accelerator,Speedy System Boost,Rapid PC Launch,Efficient PC Wakeup,Faster PC Initiation
thumbnail: https://thmb.techidaily.com/cdded6aa8f500657d1cc67ca7b77cb926c32d80c757bf8e50b4e15a0eac70eb2.jpg
---

## Boosting PC Launches: Activating Fast Startup Feature

 Windows 11 has kept many of the useful features from its predecessor, including Fast Startup. As the name suggests, Fast Startup allows your computer to start up faster after a shutdown.

 Hibernate-capable Windows 11 systems come with Fast Startup enabled by default. If you want to turn on or off Fast Startup in Windows 11 manually, this guide will show you how.

## Why Should You Enable or Disable Fast Startup?

 With the release of Windows 8, Microsoft updated and renamed the default shutdown scenario as Fast Startup. It begins with the shutdown process by writing data to disk, similar to the hibernate process.

 However, unlike hibernation, it logs off all the user sessions and writes the remaining boot information to the hiberfil file. So, instead of loading everything from scratch, Windows loads data from the Hiberfil.sys file into memory when you restart your computer, significantly reducing the boot time.

 That said, Fast Startup is not without its shortcomings. For example, [according to Microsoft](http://docs.microsoft.com/en-us/troubleshoot/windows-client/deployment/updates-not-install-with-fast-startup), you may face difficulties installing Windows updates on Fast Startup-enabled systems. Another reason is the [missing dual boot option because of the disabled delayed start function](https://www.makeuseof.com/windows-10-dual-boot-option-not-showing/). To learn more, read our explainer on [how Fast Startup works and why you should disable it](https://www.makeuseof.com/what-is-windows-fast-startup-why-disable-it/).

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Check if Fast Startup Is On or Off

![check fast startup status windows 11 powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/check-fast-startup-status-windows-11-powershell.jpg)

 Often, a major Windows feature update may overwrite the power settings and disable Hibernate, thus disabling Fast Startup. Or you may experience unusual boot behavior even when you think Fast Startup is on. Before attempting to troubleshoot your computer, check if Fast Startup is on or off.

 You can use Command Prompt to check the Fast Startup status:

1. Press the **Win** key and type **powershell**.
2. Right-click on **PowerShell** and select **Run as administrator**. Click **Yes** if prompted by User Account Control.
3. In the PowerShell console, copy and paste the following command and press Enter:  
`(GP "HKLM:\SYSTEM\CurrentControlSet\Control\Session Manager\Power")."HiberbootEnabled"`
4. The above command uses the **Get-Item (GP)** cmdlet to retrieve power-related settings and information about the **HiberBootEnabled** value in the Windows Registry.
5. A returned value of **1** means Fast Startup is On. A **0** would indicate Fast Startup as Off.

 If the hybrid boot is off, you can follow the steps below to enable Hibernation and then Fast Startup on your computer.

 To turn on Fast Startup, you must have Hibernate feature enabled on your computer. To check if Hibernate is enabled on your PC:

1. Press the **Win** key to open the **Start menu**.
2. Next, click on **Power** (power icon) and check if **Hibernate** is shown among other power options.
3. If disabled, the **Hibernate** option will not appear in the Power menu.

 Alternatively, check if Hibernate, while available, is hidden in the Control Panel. To do this:

1. Press **Win + R** to open **Run**.
2. Type **powercfg.cpl** and click **OK** to open Power Options in Control Panel.  
![choose what the power buttons do control panel windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/choose-what-the-power-buttons-do-control-panel-windows-11.jpg)
3. In the **Control Panel** dialog, click **Choose what the power buttons do** in the left pane.
4. Click **Change settings that are currently unavailable**.  
![enable disable fast startup control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/enable-disable-fast-startup-control-panel.png)
<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
5. Under **Shutdown settings**, check if **Hibernate** is available. If available, select **Hibernate** and click **Save changes** to show **Hibernate** in the Power menu.

 If the Hibernate option is missing, you can enable it using a Command Prompt command.

## How to Enable Hibernation in Windows 11

![turn on hibernate Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/turn-on-hibernate-Windows-11.png)

 Fast Startup is only available on systems compatible with the Hibernate feature available on almost all modern computers. However, this option is often disabled by default on lower-end systems.

 To enable Hibernate on Windows 11:

1. Type **cmd** in the Windows search bar.
2. Right-click on Command Prompt and select **Run as Administrator.**
3. In the Command Prompt window, type the following command and hit enter to turn on Hibernate:  
`Powercfg -h on`

 Now that you have enabled the hibernate feature, below are the various ways to enable and disable Fast Startup on your Windows computer.

## How to Turn On or Off Fast Startup in the Control Panel

![enable disable fast startup control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/enable-disable-fast-startup-control-panel.png)
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->

 The easiest way to turn on Fast Startup is via the Control Panel's power settings. Here’s how to do it.

1. Press **Win + R** to open **Run**.
2. Type **control** and click **OK** to open the Control Panel.
3. Go to **System and Security** and then click on **Power Options**.
4. In the left pane, click on **Choose what the power buttons do.**
5. Next, click the **Change settings that are currently unavailable** link.
6. Under the **Shutdown settings** section, check the **Turn on fast startup (recommended)** option to turn on the feature.
7. Uncheck the **Turn on fast startup option** to disable Fast Startup.
8. Click **Save changes** to apply the changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
## How to Turn On or Off Fast Startup Using the Registry Editor

![turn on off fast startup registry register](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/turn-on-off-fast-startup-registry-register.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->

 The next set of methods involves modifying the Windows registry. If something goes wrong, restoring your system to a functioning state can become difficult. So, [create a restore point](https://www.makeuseof.com/tag/create-system-restore-point/) before attempting to edit your registry entries. This will allow you to undo the changes if your system breaks during the process.

 Once done, do the following:

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK**. Click **Yes** when prompted by UAC.
3. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Power`
4. You can also copy/paste the above path for quicker navigation.
5. In the right-pane, scroll down and locate the DWORD value **HiberbootEnabled.**
6. Right-click on **HiberbootEnabled** and select **Modify**.
7. Type **1** in the **Value data** field and click **OK** to save the changes.
8. To turn off Fast Startup, enter **0** in the **Value data** field and click **OK**.
9. Close the Registry Editor and reboot your computer.

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Turn On or Off Fast Startup Using a Registry File

![turn on off registry file fast startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/turn-on-off-registry-file-fast-startup.png)
<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->

 If you don’t want to work with the Registry Editor, you can create a REG file and run it to achieve the same. Here’s how to do it.

1. Press the **Win** key, search for the **Notepad** app and open it.
2. To enable Fast Startup, copy and paste the following code in the Notepad file:  
`Windows Registry Editor Version 5.00  
[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Power]  
"HiberbootEnabled"=dword:00000001`
3. To disable fast startup, copy and paste the following code instead.  
`Windows Registry Editor Version 5.00  
[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Power]  
"HiberbootEnabled"=dword:00000000`
4. Click on **File** and select **Save As.**
5. Enter file name as **Enable\_fast\_startup.reg** or **Disable\_fast-startup.reg**.
6. Click on **Save as** type drop-down and select **All Files.**
7. Next, click **Save**.
8. Double-click on the **Enable\_fast-startup.reg** file to run. Then click **Yes**, and **Yes** to confirm the action.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->
## How to Enable or Disable Fast Startup in the Group Policy Editor

![require use of fast startup group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/require-use-of-fast-startup-group-policy-editor-1.png)

 Group Policy Editor allows you to configure your Group Policy settings to allow or restrict features as required. You can use it to enable or disable the Fast Startup feature on your Windows computer.

 Note that the Group Policy Editor is only available in Windows Edu, Pro, and Enterprise editions of the OS. If you are running Home, here's how to [access the Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 Follow these steps to turn on Fast Startup on Windows 11:

1. Press **Win + R** to open **Run**.
2. Type **gpedit.msc** and click **OK** to open Group Policy Editor.
3. In Group Policy Editor, navigate to the following location:  
`Computer Configuration\Administrative Templates\System\Shutdown`
4. In the right pane, right-click on **Require use of fast startup** and select **Edit**.
5. Select **Enabled** to turn on Fast Startup.
6. Or Select **Disabled** to turn off Fast Startup.
7. Click **Apply** and **OK** to save the changes.

## How to Turn Off Fast Startup Using the Command Prompt

![disable fast startup hibernate Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/disable-fast-startup-hibernate-Windows-2.png)

 Since fast startup depends on the Hibernate feature, you can disable Hibernate to turn off Fast start. However, this will also turn off Hibernate in Power options, so tread carefully.

1. Press **Win + R** to open **Run**.
2. Type **cmd** into the box and then press **Ctrl + Shift + Enter** to open the Command Prompt as administrator.
3. In the Command Prompt window, type the following command and hit enter:  
`Powercfg -h off`
4. This will disable the Hibernate feature and also turn off Fast Startup.

## Making Your Windows 11 PC Boot Better

 The Fast Startup feature works like a charm on the older and slower systems with traditional HDDs or hybrid configurations. While you can shave off a few seconds even on an SSD, the incompatibility with dual boot and issues with Windows updates is an annoyance for many.

 Whether you want to turn Fast Startup on or off depends on what problem you are trying to solve. Try experimenting with the feature to see if it works for you. If not, you can always undo the changes.

 Hibernate-capable Windows 11 systems come with Fast Startup enabled by default. If you want to turn on or off Fast Startup in Windows 11 manually, this guide will show you how.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-exclusive-list-12-flawless-non-timebound-tools/"><u>[New] 2024 Approved  Exclusive List  12 Flawless Non-Timebound Tools</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-streamlining-youtube-videos-for-facebook-circulation/"><u>[New] Streamlining YouTube Videos for Facebook Circulation</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-speedy-tiktok-video-performance-a-step-by-step-plan/"><u>[Updated] Speedy TikTok Video Performance  A Step-by-Step Plan</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-hero4-black-vs-hero4-silver/"><u>2024 Approved  Hero4 Black Vs Hero4 Silver</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-soundsnatcher-free-guide-and-assessment/"><u>2024 Approved  SoundSnatcher Free Guide & Assessment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-guide-repairing-windows-error-0x80040610-in-outlook/"><u>Comprehensive Guide: Repairing Windows Error 0X80040610 in Outlook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easing-privilege-restrictions-for-windows-installer-success/"><u>Easing Privilege Restrictions for Windows Installer Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-fixes-to-enhance-windows-high-dpi-scaling/"><u>Effective Fixes to Enhance Windows High DPI Scaling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-visibility-of-the-taskbar-with-maximized-window/"><u>Ensuring Visibility of the Taskbar With Maximized Window</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-the-underutilized-tools-for-system-monitoring/"><u>Exploring the Underutilized Tools for System Monitoring</u></a></li>
<li><a href="https://tech-haven.techidaily.com/from-hacking-to-ai-woes-the-story-behind-linustechtips-twitter-account-breach-unraveling-trojan-threats-and-challenges-with-chatgpt/"><u>From Hacking to AI Woes: The Story Behind @LinusTechTips' Twitter Account Breach, Unraveling Trojan Threats & Challenges with ChatGPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/full-uninstallation-blueprint-for-wsl-in-modern-windows/"><u>Full Uninstallation Blueprint for WSL in Modern Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-mend-the-mist-of-talos-extender/"><u>How to Mend the Mist of Talos Extender</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-test-a-microphone-on-windows-pc/"><u>How to Test a Microphone on Windows PC</u></a></li>
<li><a href="https://win-able.techidaily.com/ice-apply-cold-packs-or-ice-wrapped-in-a-cloth-for-15-20-minutes-every-hour-on-the-first-day-then-reduce-frequency-as-swelling-subsides-icing-helps-minimize400/"><u>Ice: Apply Cold Packs or Ice Wrapped in a Cloth for 15-20 Minutes Every Hour on the First Day, Then Reduce Frequency as Swelling Subsides. Icing Helps Minimize Inflammation and Numbs Pain.</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-avoid-blurry-scenes-zooming-in-on-google-meet/"><u>In 2024, Avoid Blurry Scenes  Zooming In on Google Meet</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-chromatic-coherence-helper/"><u>In 2024, Chromatic Coherence Helper</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-mastering-file-shift-quick-and-easy-transfer-tactics-for-the-computer/"><u>In 2024, Mastering File Shift  Quick and Easy Transfer Tactics for the Computer</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/influential-impact-celebrating-instagrams-most-dynamic-stars-for-2024/"><u>Influential Impact  Celebrating Instagram's Most Dynamic Stars for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/isnapmaker-ios-and-macos-media-synthesis-tool-for-2024/"><u>ISnapMaker  IOS & macOS Media Synthesis Tool for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-win-11-games-in-no-time-the-ultimate-guide-to-boosting-your-playstyle/"><u>Master Win 11 Games in No Time: The Ultimate Guide to Boosting Your Playstyle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterful-windows-artistry-with-these-7-distinguished-drawing-tools/"><u>Masterful Windows Artistry with These 7 Distinguished Drawing Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reconnecting-disconnected-network-via-windows-settings/"><u>Reconnecting Disconnected Network via Windows Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-the-situation-when-another-software-overrides-speakers/"><u>Remedying the Situation When Another Software Overrides Speakers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-unconnect-error-for-windows-nvidia-applications/"><u>Removing Unconnect Error for Windows' Nvidia Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-link-failures-spotify-in-windows-11-environments/"><u>Resolving Link Failures: Spotify in Windows 11 Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-the-0x80072746-email-failure-on-windows-pc/"><u>Resolving the 0X80072746 Email Failure on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/script-for-setting-up-ms-word-opening-email-attachments-without-edit-options/"><u>Script for Setting Up MS Word: Opening Email Attachments Without Edit Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shed-light-on-dark-windows-11-desktops-tips-inside/"><u>Shed Light on Dark Windows 11 Desktops - Tips Inside!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-amd-graphics-drivers-update-for-windows-11-pcs/"><u>Step-by-Step AMD Graphics Drivers Update for Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-resetting-video-driver-errors/"><u>Steps to Fix Resetting Video Driver Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-storage-with-ntfs-compression-in-win11/"><u>Streamline Storage with NTFS Compression in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-remedy-dealing-with-roblox-error-code-262/"><u>Swift Remedy: Dealing with Roblox Error Code 262</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-insufficient-rights-error-during-windows-installation/"><u>Tackling Insufficient Rights Error During Windows Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-drive-camouflage-in-w11w10/"><u>The Art of Drive Camouflage in W11/W10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-upgrade-error-xc004f050/"><u>Troubleshooting Windows Upgrade Error Xc004f050</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-fixing-windows-error-0xc0000001-quickly/"><u>Understanding & Fixing Windows Error 0xC0000001 Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-potential-pinning-to-windows-11-bar/"><u>Unleash Potential: Pinning to Windows 11 Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-best-windows-photo-organizers-listed-here/"><u>Unveiling the Best Windows Photo Organizers Listed Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrading-ancient-pcs-for-modern-operations-using-windows-to-go-and-rufus/"><u>Upgrading Ancient PCs for Modern Operations: Using Windows To Go and Rufus</u></a></li>
<li><a href="https://change-location.techidaily.com/will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-vivo-s18-pro-drfone-by-drfone-virtual-android/"><u>Will Pokémon Go Ban the Account if You Use PGSharp On Vivo S18 Pro | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/youtubes-centralized-digital-media-command-center/"><u>YouTube's Centralized Digital Media Command Center</u></a></li>
</ul></div>
