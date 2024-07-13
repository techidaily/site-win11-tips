---
title: "Boot Into Peace: Five Tactics to Overcome Windows Security Failures"
date: 2024-07-12T17:05:28.852Z
updated: 2024-07-13T17:05:28.852Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Boot Into Peace: Five Tactics to Overcome Windows Security Failures"
excerpt: "This Article Describes Boot Into Peace: Five Tactics to Overcome Windows Security Failures"
keywords: Overcome WinSec,Windows Safeguard Bypass,Secure Boot Procedures,Efficient PC Security,Mastering Windows Defense,Strategic WinSec Fixes,Tactics for Safe Computing
thumbnail: https://thmb.techidaily.com/f567a9fec699d773d0b269b2abfaf091f129a875a6f111520a97150e50266041.jpg
---

## Boot Into Peace: Five Tactics to Overcome Windows Security Failures

 Secure Boot is a security feature that helps to ensure that only trusted applications are installed on the computer. Although this feature is enabled by default on most computers, you will still likely see the "Secure Boot state unsupported" error while installing Windows 11\.

 The error mainly appears when TPM is disabled on your computer. As such, if you're also facing the same problem, follow the fixes below to troubleshoot the problem for good.

## What Causes the "Secure Boot State Unsupported" Error?

[Secure Boot](https://www.makeuseof.com/what-is-secure-boot-how-does-it-work/) is a feature of modern computers that uses a digital signature to verify the authenticity of the system's software, especially the operating system's files. It is one of the minimum requirements to install Windows 11\.

 Although you can easily [bypass Windows 11's minimum requirements](https://www.makeuseof.com/bypass-windows-11-minimum-installation-requirements/), doing so would adversely affect your computer. You could expect your device to slow down or even crash on a frequent basis.

 Some of the common reasons behind the "Secure Boot state unsupported" error are:

1. You'll likely see the error message if TPM is disabled or not installed on your computer.
2. The error message will appear if Secure Boot is disabled in the BIOS.
3. You'll also encounter the error if BIOS mode is set to Legacy instead of UEFI.

 Now, let's dive into fixes that will help you eliminate the problem.

## 1\. Enable Secure Boot in BIOS

 You must enable Secure Boot in BIOS if you want to install Windows 11 on your computer. But before doing that, view Secure Boot's current state. Here's how to do it:

1. Press the **Win + R** hotkey to open the Run dialog box. Then, type **msinfo32,** and press **Enter**. It'll [open the System information window](https://www.makeuseof.com/windows-open-system-information/).
2. Click **System** **Summary** in the left panel.
3. Check the **Secure Boot State** in the right pane.  
![Secure Boot State in System Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Secure-Boot-State.jpg)

 If the Secure Boot status is **Off**, you'll have to enable it through your BIOS. To do that, follow the instructions:

1. Open the Settings menu by pressing the Win + I hotkey, and navigate to **System** \> **Recovery.**
2. Click **Restart now** next to **Advanced startup.** It'll restart your computer.  
![Restart Now option next to Advanced Startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Restart-Now-option.jpg)
3. In the Advanced startup mode, choose **Troubleshoot** and then **Advanced options.**
4. Choose **UEFI Firmware Settings** and click **Restart.** I'll boot you straight into Windows UEFI BIOS.
5. Choose **BIOS Setup.**
6. Switch to **Secure Boot.**
7. Check the box before **Secure Boot Enable.**  
![Enable Secure Boot in BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Enable-Secure-Boot-1.jpg)

 Note that the steps to [enable Secure Boot](https://www.makeuseof.com/how-enable-tpm-secure-boot-before-upgrading-windows-11/) will be different for different manufacturers. You can check out your manufacturer's BIOS page to know how to do it on your computer.

 Once you've enabled Secure Boot, try to install Windows and check if the problem continues. If yes, then try the next solution on the list.

## 2\. Check and Enable TPM Support

 You must have the TPM chip installed on your computer to download Windows 11\. If the TPM chip is missing, you can still install Windows 11 by bypassing the minimum requirement, but then the "Secure Boot state unsupported" error will continue to bother you now and then.

 The problem in the discussion can also appear if TPM is disabled on your computer. To enable TPM, follow the below instructions:

1. Open the Run dialog box.
2. In the search bar, type **tpm.msc** and press Enter.
3. In the TPM management window, click **Actions** in the top bar.
4. Choose **Prepare the TPM** from the context menu.  
![Prepare the TPM in TPM Management Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Prepar-the-TPM.jpg)

 Restart your computer and check for the problem.

## 3\. Choose UEFI as the BIOS' Mode

 Windows supports two BIOS modes–**UEFI** and **Legacy**. The difference between these two modes is in the process that the firmware uses to locate the boot target.

 You must install Windows using the new UEFI mode as it offers more security features than the Legacy BIOS mode.

 To choose UEFI as the BIOS mode, follow the below steps:

1. Open the BIOS page on your computer.
2. Choose **Boot Sequence** from the left panel.
3. Check the **UEFI option** under **Boot List** Options.  
![UEFI Option in BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/UEFI-Option.jpg)
4. Save the changes and restart your computer.

 Again, the process will differ for different manufacturers; therefore, you must check your manufacturer's BIOS page to know how to do it on your computer.

## 4\. Convert the Partition Style From MBR to GPT

 In modern computers, the boot mode is set to UEFI and has GPT (GUID Partition Style) partition style. However, if your computer is using Legacy Boot mode and MBR (Master Boot Record) partition style, then you will face the problem at hand.

 The solution, in this case, is to convert the partition style from MBR to GPT. But before doing that, you must check your computer partition style. Here's how:

1. Press **Win + X** to open the **Power menu.**
2. Choose **Disk Management.**
3. In the Disk Management window, right-click on the hard disk drive and choose **Properties** from the context menu.  
![Properties option in Disk Management tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/properties-option.jpg)
4. Switch to the **Volumes** tab.
5. Check the **Partition style.** If it shows Master Boot Record (MBR), then you will have to convert it to GPT.  
![Partition Style in Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Partition-Style.jpg)

 To convert the MBR partition style to GPT, follow the below steps:

1. Open the **Start Menu** by pressing the **Windows** key.
2. Type **Command Prompt** in the search bar and click the **Run as administrator** option in right pane.
3. Type **mbr2gpt /validate /allowfullOS** and press Enter. This command will validate the partition.  
![Validate command option in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/validate-command.jpg)
4. Once the validation is complete, type **mbr2gpt /convert /allowfullOS** and press Enter.

 That's it. Windows will start converting the partition style. The process may take some time, depending on the size of your drive.

## 5\. Perform a Clean Boot

 Are you still facing the "Secure Boot state unsupported" error? If yes, then you will have to perform a clean boot to troubleshoot the issue. Check out our guide on [how to perform a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/) for more information.

 In the clean boot state, check if you're facing the error message again or not.

![System configuration window on desktop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-configuration-window.jpg)

 If not, then it indicates that one of the services you disabled was causing the problem. To narrow it down, repeat the above process while slowly re-enabling the services until you see the error again.

 Once you find out which service is the culprit, consider downloading its driver update or running an SFC scan if it's a Windows-based service.

## The "Secure Boot State Unsupported" Error, Fixed

 The "Secure Boot state unsupported" error is a very common issue that appears when you try to install Windows 11\. Fortunately, you can quickly troubleshoot this error by following the above fixes.

 But in the worst-case scenario, if none of the above fixes were helpful, then you will have to clean install Windows.

 The error mainly appears when TPM is disabled on your computer. As such, if you're also facing the same problem, follow the fixes below to troubleshoot the problem for good.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/how-to-start-wordpad-in-a-windows-desktop/"><u>How to Start WordPad in a Windows Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-the-most-effective-win-video-codecs/"><u>Demystifying the Most Effective Win Video Codecs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-items-to-windows-11-desktop-menu-hierarchy/"><u>Adding Items to Windows 11 Desktop Menu Hierarchy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/finding-lightweight-browsers-for-chromeoswindowsmacos-ram-and-cpu-wise/"><u>Finding Lightweight Browsers for ChromeOS/Windows/macOS: RAM & CPU-Wise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dxvk-transforming-windows-gaming-experience-for-the-better/"><u>DXVK: Transforming Windows Gaming Experience for the Better</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instructions-to-bring-back-old-school-search-in-windows-11/"><u>Instructions to Bring Back Old-School Search in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-future-microsofts-copilot-key-and-windows-11-revolution/"><u>Navigating the Future: Microsoft's Copilot Key and Windows 11 Revolution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1011-permanent-file-disposal-via-custom-trash-bin-setup/"><u>Windows 10/11: Permanent File Disposal via Custom Trash Bin Setup</u></a></li>
<li><a href="https://extra-information.techidaily.com/10-prime-free-images-hosts-ensure-picture-longevity/"><u>10 Prime Free Images Hosts, Ensure Picture Longevity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disentangling-stacked-icons-on-operating-system-ui/"><u>Disentangling Stacked Icons on Operating System UI</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/get-noticed-on-facebook-the-simple-guide-to-optimizing-your-video-aspect-ratios-for-2024/"><u>Get Noticed on Facebook The Simple Guide to Optimizing Your Video Aspect Ratios for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winfixing-comprehensive-steps-for-repairing-windows-filesystem-issues/"><u>Winfixing: Comprehensive Steps for Repairing Windows Filesystem Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/should-you-block-yourphoneexe-on-home-editions/"><u>Should You Block YourPhone.exe on Home Editions?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-comparison-dissecting-key-differences-between-local-and-microsoft-logins-in-os/"><u>In-Depth Comparison: Dissecting Key Differences Between Local & Microsoft Logins in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-completely-reskin-windows-11-for-a-nostalgic-windows-98-look/"><u>How to Completely Reskin Windows 11 for a Nostalgic Windows 98 Look</u></a></li>
<li><a href="https://network-issues.techidaily.com/seamless-troubleshooting-of-wide-text-lines-on-laptops/"><u>Seamless Troubleshooting of Wide Text Lines on Laptops</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-quick-mac-mastering-screen-recording-via-shortcuts-for-2024/"><u>[Updated] Quick Mac  Mastering Screen Recording via Shortcuts for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-print-bridge-trouble-shooting-guide/"><u>Windows Print Bridge: Trouble Shooting Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-function-keys-actions-on-windows-1011/"><u>Adjusting Function Keys' Actions on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revising-the-start-page-to-a-new-preference-in-win11/"><u>Revising the Start Page to a New Preference in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-your-system-ready-for-windows-11-with-our-top-3-usb-tips/"><u>Get Your System Ready for Windows 11 with Our Top 3 USB Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mobile-file-access-via-windows-server/"><u>Mobile File Access via Windows Server</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-writing-game-wins-finest-tools/"><u>Elevate Your Writing Game – Win's Finest Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-guide-to-enhancing-performance-in-your-new-windows-11-setup/"><u>A Quick Guide to Enhancing Performance in Your New Windows 11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-different-ways-to-tailor-windows-11-search/"><u>Explore Different Ways to Tailor Windows 11 Search</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinventing-win11s-configuration-interface/"><u>Reinventing Win11's Configuration Interface</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-crafting-unique-videos-master-tiktoks-sound-personalization/"><u>[Updated] In 2024, Crafting Unique Videos  Master TikTok's Sound Personalization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-hacks-for-instantaneous-iis-server-management-entry/"><u>8 Hacks for Instantaneous IIS Server Management Entry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-reactivate-the-default-folder-cooking-a-comprehensive-guide/"><u>Methods to Reactivate the Default Folder' Cooking: A Comprehensive Guide</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-if-you-want-to-prompt-your-ecommerce-business-in-facebook-then-using-facebook-video-ads-is-one-of-the-effective-methods-this-post-will-show-yo/"><u>2024 Approved If You Want to Prompt Your eCommerce Business in Facebook, Then Using Facebook Video Ads Is One of the Effective Methods. This Post Will Show You How to Edit Videos for Facebook Advertisement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/icon-position-correction-made-simple/"><u>Icon Position Correction Made Simple</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breakthrough-programs-facilitating-switch-from-mac-to-windows/"><u>Breakthrough Programs Facilitating Switch From MAC to WINDOWS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-uncover-and-attend-to-hidden-storage/"><u>How to Uncover and Attend to Hidden Storage?</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-illusion-of-movement-facial-motion-blur-with-picsart/"><u>2024 Approved  Illusion of Movement  Facial Motion Blur with Picsart</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/unlock-the-power-of-live-broadcasting-with-tiktok-from-pc-for-2024/"><u>Unlock the Power of Live Broadcasting with TikTok From PC for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/guide-to-diy-vr-headgear-crafting-a-personalized-google-model/"><u>Guide to DIY VR Headgear  Crafting a Personalized Google Model</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-critical-evaluation-screen-recorders-on-desktops/"><u>[New] 2024 Approved  Critical Evaluation  Screen Recorders on Desktops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719380879608-speedy-outlook-on-windows-heres-how/"><u>Speedy Outlook on Windows? Here's How!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-windows-component-services-interface-quickly/"><u>Accessing Windows' Component Services Interface Quickly</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-decoding-the-world-of-discord-stickers/"><u>[New] In 2024, Decoding the World of Discord Stickers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-streamline-note-taking-with-win-11-display-rules/"><u>How to Streamline Note-Taking with Win 11 Display Rules</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-device-disconnection-dxgi-error-guide/"><u>Overcoming Device Disconnection: DXGI Error Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-vmware-crashes-a-guide-for-win11-users/"><u>Overcoming VMware Crashes: A Guide for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-customize-windows-11s-search-via-settings/"><u>5 Ways to Customize Windows 11'S Search via Settings</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-ways-to-track-vivo-x-fold-2-without-them-knowing-drfone-by-drfone-virtual-android/"><u>3 Ways to Track Vivo X Fold 2 without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/verifying-microphone-function-on-windows/"><u>Verifying Microphone Function on Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/additional-tips-about-sinnoh-stone-for-xiaomi-redmi-12-drfone-by-drfone-virtual-android/"><u>Additional Tips About Sinnoh Stone For Xiaomi Redmi 12 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-basics-to-brilliance-elevating-your-windows-experience-via-ms-store/"><u>From Basics to Brilliance: Elevating Your Windows Experience via MS Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stabilize-cease-persistent-file-explorer-opens/"><u>Stabilize: Cease Persistent File Explorer Opens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-immediate-folder-upload-tackling-onedrive-errors/"><u>Mastering Immediate Folder Upload: Tackling OneDrive Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidance-on-resolving-windows-software-initiation-flaw-error/"><u>Guidance on Resolving Windows Software Initiation Flaw (Error)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-order-in-windows-registry-through-repair-methods/"><u>Restoring Order in Windows Registry Through Repair Methods</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-maximizing-audience-reach-twitch-livest-writes-for-youtube/"><u>2024 Approved  Maximizing Audience Reach  Twitch Livest Writes for YouTube</u></a></li>
</ul></div>
