---
title: How to Deal with Imminent License Expiry on Your PC
date: 2024-07-12T17:17:12.667Z
updated: 2024-07-13T17:17:12.667Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Deal with Imminent License Expiry on Your PC
excerpt: This Article Describes How to Deal with Imminent License Expiry on Your PC
keywords: License Lifespan Management,Expiring Software Handling,Renewal Preparation Guide,Proactive License Planning,Dealing with Soft Laws End,Anticipating PC Licenses' Fade,Timely Software License Update
thumbnail: https://thmb.techidaily.com/a876d99fc810824e790e14200a363bc8a24888dbe0f9cb4aa8918882c26356a6.jpeg
---

## How to Deal with Imminent License Expiry on Your PC

 Have you encountered the alarming "your Windows license will expire soon" error message on your PC? That usually happens when the Windows license on your PC is expired or deemed invalid. However, if your Windows license is indeed genuine, there might be another issue preventing Microsoft from authenticating it properly.

 In the following sections, we will discuss the common causes behind this error and provide potential solutions to fix it.

## Why Does the “Your Windows License Will Expire Soon” Error Appear?

 The "Your Windows license will expire soon" error message can occur due to several factors, and here are the most prevalent ones:

* **Windows license is invalid:** Using an unauthorized or pirated version of Windows is one of the most common reasons why you might encounter this error message.
* **Hardware changes:** Performing hardware changes, such as replacing the motherboard in your system, can also lead to activation errors on Windows.
* **Connectivity issues:** Your computer might fail to connect to the Key Management Service (KMS) server due to network-related issues, resulting in activation errors.
* **Corrupt Activation Token files:** The **Tokens.dat** file contains the activation information for your Windows installation. If this file becomes inaccessible for some reason, you may encounter the “Your Windows license will expire soon” error on Windows.  
![Your Windows License Will Expire Soon Error on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/your-windows-license-will-expire-soon-error-on-windows.jpg)

 Now that you are aware of the common causes of this error, let's now focus on the potential solutions to resolve it.

## 1\. Apply Some Preliminary Fixes

 Before you try any advanced troubleshooting tips, it’s a good idea to start with some basic fixes.

* **Restart Windows Explorer:** Temporary issues with the Windows Explorer process can sometimes trigger the “Your Windows license will expire soon” error on your PC. If it’s nothing major, you should be able to fix it by simply [restarting the Windows Explorer process](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/).
* **Run the SFC Scan:** It’s possible that Microsoft is having trouble authenticating your Windows license due to corrupt or damaged system files. To repair these files, you can try [running the System File Checker (SFC) scan on your PC](https://www.makeuseof.com/system-file-checker-sfc-windows/).
* **Scan for Malware:** Another potential factor contributing to Windows activation issues is malware infection. To address this, you can try [scanning your PC for malware using PowerShell](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/) or Microsoft Defender.

## 2\. Run the Activation Troubleshooter

 Both Windows 10 and 11 offer various troubleshooters for addressing common system issues. In this case, you can take help from the Windows Activation troubleshooter to fix any issues that may have caused the “Your Windows license will expire soon” error on your PC.

 To run the Activation troubleshooter, use these steps:

1. Press **Win + I** to open the Settings app.
2. Navigate to **System > Activation**.
3. Click the **Troubleshooter** button.  
![Running the Windows Activation Troubleshooter-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/running-the-windows-activation-troubleshooter-1.jpg)

 Wait for the troubleshooter to do its thing, and then check if it resolves the error.

## 3\. Find Your Product Key and Activate Windows

 Another thing you can do to fix this error is to find your product key using the ShowKeyPlus app and then attempt to activate Windows again. Several users on the forums reported fixing the error with this method. You can also give it a go.

1. [Download the ShowKeyPlus app](https://www.microsoft.com/store/productId/9PKVZCPRX9NV) from the Microsoft Store.
2. Open the ShowKeyPlus app using the search menu.
3. Note down the **OEM key** in the **Home** tab.  
![ShowKeyPlus App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/showkeyplus-app-on-windows.jpg)
4. Press **Win + I** to open the Settings app.
5. In the **System** tab, click on **Activation**.
6. Click the **Change** button next to **Change product key**.
7. Enter the **OEM key** noted earlier and click **Next**.
8. Click the **Activate** button to confirm.  
![Update Product Key on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/update-product-key-on-windows.jpg)

## 4\. Activate Windows Using Command Prompt

 If you are unable to activate Windows via the Settings app, you can try to activate it through the Command Prompt. To do so, make sure that your PC is connected to the internet, and then use these steps:

1. Click the **magnifying icon** on the taskbar to access the search menu.
2. Type **cmd** in the box and select **Run as administrator**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Type **slmgr /ato** in the console and press Enter.  
![Activate Windows via Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/activate-windows-via-command-prompt.jpg)

 Wait for Command Prompt to validate your product key. You will see a message confirming the outcome of the activation process, whether it was successful or not. If the activation is successful, you should not see the “Your Windows license will expire soon” error after this.

## 5\. Rebuild the Tokens.dat File

 Tokens.dat is a system file related to Windows activation and licensing. If this file somehow gets corrupted, Windows may have trouble verifying the authenticity of your license and trouble you with the “Your Windows license will expire soon” error.

 You can try rebuilding the Tokens.dat file on your PC to see if that fixes the error. Here are the steps for the same.

1. Right-click on the **Start icon** or use the **Win + X** keyboard shortcut to open the Power User menu.
2. Select **Terminal (Admin)** from the list.
3. Type the following commands one by one and press **Enter** after each.  
`net stop sppsvc  
cd %windir%\system32\spp\store\2.0  
ren tokens.dat tokens.bar  
net start sppsvc  
cscript.exe %windir%\system32\slmgr.vbs /rilc`

 Restart your computer after running the above commands and then check if you still get the “Your Windows license will expire soon” error on your PC.

## 6\. Reset the Licensing Status

 In case your Windows license is not genuine, there's a workaround to dismiss the “Your Windows license will expire soon” message. This workaround involves resetting the activation period and [hiding the Activate Windows watermark](https://www.makeuseof.com/tag/remove-activate-windows-10-watermark/) via Command Prompt. Here are the steps you can follow.

1. [Open Command Prompt with administrative privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Type **slmgr /rearm** in the console and press **Enter**.
3. Restart your PC after running the command.  
![Reset the Activation Timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-the-activation-timer.jpg)

 It's worth noting that you can only utilize the above command a few times. Eventually, you will have to obtain a genuine Windows license to eliminate the error message permanently.

## Fixing the “Your Windows License Will Expire Soon” Error on Windows

 Since Microsoft limits access to various personalization and security features on systems with inactivated Windows licenses, it’s vital to troubleshoot errors like the “Your Windows license will expire soon”. One of the above fixes should help you resolve the error message on your Windows computer. However, if nothing works, you can consider reaching out to Microsoft tech support as a last resort.

 Have you encountered the alarming "your Windows license will expire soon" error message on your PC? That usually happens when the Windows license on your PC is expired or deemed invalid. However, if your Windows license is indeed genuine, there might be another issue preventing Microsoft from authenticating it properly.

 In the following sections, we will discuss the common causes behind this error and provide potential solutions to fix it.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-8-engaging-exercise-routines-for-active-viewership/"><u>[Updated] In 2024, 8 Engaging Exercise Routines for Active Viewership</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-mouse-response-time-on-windows-devices/"><u>Optimizing Mouse Response Time on Windows Devices</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-make-a-lasting-impression-5-top-movie-intro-software/"><u>In 2024, Make a Lasting Impression 5 Top Movie Intro Software</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/final-cut-pro-for-ipad-for-2024/"><u>Final Cut Pro for iPad for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-blocking-self-starting-windows-store/"><u>Strategies for Blocking Self-Starting Windows Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-hyper-v-setup-process-for-windows-11-home-edition/"><u>Navigating the Hyper-V Setup Process for Windows 11 Home Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-s-mode-a-safe-choice-for-beginners/"><u>Windows 11 S Mode: A Safe Choice for Beginners?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-engineering-the-taskbar-key-steps-to-better-windows-11-ux/"><u>Re-Engineering the Taskbar: Key Steps to Better Windows 11 UX</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-running-sfc-on-windows/"><u>Understanding and Running SFC on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-banishing-the-persistent-pink-error-on-windows/"><u>The Ultimate Guide to Banishing the Persistent Pink Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-software-windows-best-photo-arrangers-reviewed/"><u>Winning Software: Windows' Best Photo Arrangers Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-winterminals-bg-pic/"><u>Setting WinTerminal's Bg Pic</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swivel-your-snaps-with-these-6-steps-for-windows-11-users/"><u>Swivel Your Snaps with These 6 Steps for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-and-utilizing-widgets-in-windows-11/"><u>Accessing and Utilizing Widgets in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-0x800704cf-error-in-win11-marketplace/"><u>Overcoming 0X800704CF Error in Win11 Marketplace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-modern-standby-gets-a-bad-rap-in-windows/"><u>Why Modern Standby Gets a Bad Rap in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinvigorating-faulty-troubleshooters-in-windows-os/"><u>Reinvigorating Faulty Troubleshooters in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-windows-multiscreen-woes/"><u>Understanding Windows Multiscreen Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-tip-how-to-turn-off-nvidia-ui/"><u>Tech Tip: How to Turn Off NVIDIA UI</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-a-complete-guide-to-sourcing-elite-instagram-ringtones-and-designing-noteworthy-ringtone-alarms/"><u>2024 Approved  A Complete Guide to Sourcing Elite Instagram Ringtones & Designing Noteworthy Ringtone Alarms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-your-windows-11-defense-enhanced-filter-options-via-context-menu/"><u>Upgrade Your Windows 11 Defense: Enhanced Filter Options via Context Menu</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-reinstall-your-hardware-drivers-on-windows-11-and-10-and-7-by-drivereasy-guide/"><u>Use Device Manager to reinstall your hardware drivers on Windows 11 & 10 & 7</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-auto-reframe-video-editing-tools-top-picks-for-creators-for-2024/"><u>New Auto-Reframe Video Editing Tools Top Picks for Creators for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-windows-headset-microphone-blockage/"><u>Unblocking Windows Headset Microphone Blockage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-onedrive-errors-on-windows-effective-fixes/"><u>Tackling OneDrive Errors on Windows: Effective Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revealing-the-hidden-search-bar-in-win11s-task-manager/"><u>Revealing the Hidden Search Bar in Win11's Task Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-winget-in-windows-11-environments/"><u>Reactivating Winget in Windows 11 Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-desktop-icon-chaos-in-windows/"><u>Avoid Desktop Icon Chaos in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-roblox-error-262-instantly/"><u>Overcoming Roblox Error 262 Instantly</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/from-imovie-to-adobe-premiere-top-windows-movie-maker-equivalents-for-mac-for-2024/"><u>From iMovie to Adobe Premiere Top Windows Movie Maker Equivalents for Mac for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-a-closer-inspection-of-splice-video-editor-features-pricing-and-more/"><u>New 2024 Approved A Closer Inspection of Splice Video Editor Features, Pricing, and More</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-the-role-of-windows-print-management-interface/"><u>Understanding the Role of Windows Print Management Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-cutting-the-fat-in-windows-11/"><u>The Ultimate Guide to Cutting the Fat in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrecting-your-muted-windows-start-button-icon/"><u>Resurrecting Your Muted Windows Start Button Icon</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-snap-uac-dialogues/"><u>A Step-by-Step Guide to Snap UAC Dialogues</u></a></li>
<li><a href="https://fox-access.techidaily.com/expert-strategy-seamlessly-integrating-subtitles-in-videos-for-2024/"><u>Expert Strategy  Seamlessly Integrating Subtitles in Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-configurations-restarted-a-triad-of-tips/"><u>Win11 Configurations Restarted: A Triad of Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-steam-library-accessibility-on-win-11-pcs/"><u>Troubleshooting Steam Library Accessibility on Win 11 PCs</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-conversion-mastery-tips-and-tricks-from-the-best-ogg-tools/"><u>New Conversion Mastery Tips and Tricks From the Best OGG Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapting-oculus-quest-2-as-a-windows-vr-device/"><u>Adapting Oculus Quest 2 as a Windows VR Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1011-hack-design-your-own-unique-pin-pattern/"><u>Windows 10/11 Hack: Design Your Own Unique Pin Pattern</u></a></li>
</ul></div>
