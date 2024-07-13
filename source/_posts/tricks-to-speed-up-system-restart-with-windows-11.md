---
title: Tricks to Speed Up System Restart with Windows 11
date: 2024-07-12T17:05:16.821Z
updated: 2024-07-13T17:05:16.821Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tricks to Speed Up System Restart with Windows 11
excerpt: This Article Describes Tricks to Speed Up System Restart with Windows 11
keywords: Windows 11 Fast Boot,Accelerate Windows Reboot,Boost PC Start-Up,Quick Windows Restart,Optimize System Relaunch,Speedy Win11 Reset,Enhance Start Process
thumbnail: https://thmb.techidaily.com/19d1e1f9a7e016bed2849100cf93d86788ddae5b2cf2f12f9be9d04582b68734.jpg
---

## Tricks to Speed Up System Restart with Windows 11

 Windows 11 has kept many of the useful features from its predecessor, including Fast Startup. As the name suggests, Fast Startup allows your computer to start up faster after a shutdown.

 Hibernate-capable Windows 11 systems come with Fast Startup enabled by default. If you want to turn on or off Fast Startup in Windows 11 manually, this guide will show you how.

## Why Should You Enable or Disable Fast Startup?

 With the release of Windows 8, Microsoft updated and renamed the default shutdown scenario as Fast Startup. It begins with the shutdown process by writing data to disk, similar to the hibernate process.

 However, unlike hibernation, it logs off all the user sessions and writes the remaining boot information to the hiberfil file. So, instead of loading everything from scratch, Windows loads data from the Hiberfil.sys file into memory when you restart your computer, significantly reducing the boot time.

 That said, Fast Startup is not without its shortcomings. For example, [according to Microsoft](http://docs.microsoft.com/en-us/troubleshoot/windows-client/deployment/updates-not-install-with-fast-startup), you may face difficulties installing Windows updates on Fast Startup-enabled systems. Another reason is the [missing dual boot option because of the disabled delayed start function](https://www.makeuseof.com/windows-10-dual-boot-option-not-showing/). To learn more, read our explainer on [how Fast Startup works and why you should disable it](https://www.makeuseof.com/what-is-windows-fast-startup-why-disable-it/).

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

 The easiest way to turn on Fast Startup is via the Control Panel's power settings. Here’s how to do it.

1. Press **Win + R** to open **Run**.
2. Type **control** and click **OK** to open the Control Panel.
3. Go to **System and Security** and then click on **Power Options**.
4. In the left pane, click on **Choose what the power buttons do.**
5. Next, click the **Change settings that are currently unavailable** link.
6. Under the **Shutdown settings** section, check the **Turn on fast startup (recommended)** option to turn on the feature.
7. Uncheck the **Turn on fast startup option** to disable Fast Startup.
8. Click **Save changes** to apply the changes.

## How to Turn On or Off Fast Startup Using the Registry Editor
![turn on off fast startup registry register](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/turn-on-off-fast-startup-registry-register.png)

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

## How to Turn On or Off Fast Startup Using a Registry File
![turn on off registry file fast startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/turn-on-off-registry-file-fast-startup.png)

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
<li><a href="https://win11-tips.techidaily.com/three-keys-to-a-cleaner-windows-experience/"><u>Three Keys to a Cleaner Windows Experience</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-boosting-video-reach-on-youtube-an-in-depth-guide-to-seo-techniques/"><u>2024 Approved  Boosting Video Reach on YouTube  An In-Depth Guide to SEO Techniques</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-elevating-live-play-with-professional-gear-lists/"><u>[New] In 2024, Elevating Live Play with Professional Gear Lists</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-remove-forgotten-pin-of-your-vivo-s17-by-drfone-android/"><u>In 2024, How to Remove Forgotten PIN Of Your Vivo S17</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reintroducing-versatility-beyond-win-1110s-s-mode/"><u>Reintroducing Versatility Beyond Win 11/10'S S Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-restarting-non-responsive-resource-monitors-in-windows-11/"><u>Strategies for Restarting Non-Responsive Resource Monitors in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-low-end-specs-in-windows-game-capture/"><u>Overcoming Low-End Specs in Windows Game Capture</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-perfect-places-to-procure-pixel-ringers-online/"><u>In 2024, Perfect Places to Procure Pixel Ringers Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-resetting-graphics-drivers-on-latest-oses/"><u>Quick Guide to Resetting Graphics Drivers on Latest OSes</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-things-you-need-to-know-about-wipe-datafactory-reset-for-motorola-moto-g-5g-2023-drfone-by-drfone-reset-android-reset-android/"><u>All Things You Need to Know about Wipe Data/Factory Reset For Motorola Moto G 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-unleashing-instagram-success-through-precision-metrics-monitoring/"><u>[New] In 2024, Unleashing Instagram Success Through Precision Metrics Monitoring</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-w11w10s-refusal-to-open-folders-after-double-clicks/"><u>Resolving W11/W10's Refusal to Open Folders After Double-Clicks</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/unlocking-full-potential-watching-facebook-videos-on-your-apple-devices/"><u>Unlocking Full Potential  Watching Facebook Videos on Your Apple Devices</u></a></li>
<li><a href="https://fix-guide.techidaily.com/restore-missing-app-icon-on-motorola-edge-40-step-by-step-solutions-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Restore Missing App Icon on Motorola Edge 40 Step-by-Step Solutions | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/prime-portable-canvas-apps-for-windows-free-and-charged/"><u>Prime Portable Canvas Apps for Windows  Free and Charged</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-tips-for-sticky-note-backup/"><u>The Essential Tips for Sticky Note Backup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11-copypaste-anomalies/"><u>Overcoming Windows 11 Copy/Paste Anomalies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-email-setup-connecting-your-gmail-to-outlook-windows/"><u>Simplifying Email Setup: Connecting Your Gmail to Outlook Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/multi-vm-mastery-setting-up-linux-vm-in-hyper-v-on-windows/"><u>Multi-VM Mastery: Setting Up Linux VM in Hyper-V on Windows</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-use-device-manager-to-update-your-hardware-drivers-on-windows-7-by-drivereasy-guide/"><u>How to use Device Manager to update your hardware drivers on Windows 7</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-ultimate-shift-from-standard-definition-to-dynamic-range-brilliance/"><u>The Ultimate Shift  From Standard Definition to Dynamic Range Brilliance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-cr2-conversion-to-jpg-in-windows-environment/"><u>Streamline CR2 Conversion to JPG in Windows Environment</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-a-step-by-step-tutorial-for-recording-youtube-live-across-devices/"><u>[New] In 2024, A Step-by-Step Tutorial for Recording YouTube Live Across Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-file-explorer-freezes-in-win11-with-these-fixes/"><u>Stop File Explorer Freezes in Win11 With These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-maze-of-non-responsive-windows-services-management-tool/"><u>Navigating the Maze of Non-Responsive Windows Services Management Tool</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-enhancing-your-tiktok-intro-with-mac-techniques/"><u>[Updated] In 2024, Enhancing Your TikTok Intro with Mac Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-chromes-firewallantivirus-denial-error-on-pc/"><u>Resolving Chrome's Firewall/Antivirus Denial Error on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pitfalls-of-the-promotional-assessing-risks-with-low-price-auth-codes/"><u>Pitfalls of the Promotional: Assessing Risks with Low-Price Auth Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-establishing-elusive-link-finding-missing-launcher/"><u>Re-Establishing Elusive Link: Finding Missing Launcher</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-melodic-alerts-downloading-and-altering-tamil-tunes/"><u>[Updated] Melodic Alerts  Downloading and Altering Tamil Tunes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbocharging-pc-vram-with-windows-1011-tips-and-tricks/"><u>Turbocharging PC VRAM with Windows 10/11 Tips and Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-and-easy-cures-for-your-computers-messaging-woes/"><u>Quick & Easy Cures for Your Computer's Messaging Woes</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-the-ultimate-guide-five-high-quality-voice-recorders-for-mobile-devices/"><u>Updated 2024 Approved The Ultimate Guide Five High-Quality Voice Recorders for Mobile Devices</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-essential-asmr-channel-discoveries-for-2024/"><u>[New] Essential ASMR Channel Discoveries for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-hidden-dangers-on-a-computer-screen/"><u>Navigating Hidden Dangers on a Computer Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sneaky-storage-solutions-hiding-zips-within-computer-photos/"><u>Sneaky Storage Solutions: Hiding ZIPs Within Computer Photos</u></a></li>
<li><a href="https://extra-resources.techidaily.com/unparalleled-video-gear-top-5-slow-cams/"><u>Unparalleled Video Gear  Top 5 Slow Cams</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-quick-tips-transferring-camera-roll-from-your-device-to-snapchat-app/"><u>[New] Quick Tips  Transferring Camera Roll From Your Device to Snapchat App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivate-your-windows-11-explore-with-ease/"><u>Reactivate Your Windows 11 Explore with Ease</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-immerse-yourself-in-the-world-of-apples-ios-vr-titles/"><u>2024 Approved  Immerse Yourself in the World of Apple's iOS VR Titles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reigning-fast-the-quintessential-wins-performance-aids/"><u>Reigning Fast: The Quintessential Win's Performance Aids</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-audio-software-performance-on-windows-with-error-9999/"><u>Streamlining Audio Software Performance on Windows with Error 9999</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-best-8-youtube-thumbnail-grabbers-you-should-know-for-2024/"><u>[Updated] Best 8 YouTube Thumbnail Grabbers You Should Know for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11-dir-not-empty-error-0x80070091/"><u>Overcoming Windows 11 Dir Not Empty Error (0X80070091)</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ing-a-youtube-guru-essential-production-know-how-for-2024/"><u>Becoming a YouTube Guru  Essential Production Know-How for 2024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-say-goodbye-to-shaky-videos-top-stabilizer-apps-for-mobile/"><u>Updated 2024 Approved Say Goodbye to Shaky Videos Top Stabilizer Apps for Mobile</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-manual-for-chrome-and-windows-11/"><u>The Ultimate Manual for Chrome and Windows 11</u></a></li>
</ul></div>
