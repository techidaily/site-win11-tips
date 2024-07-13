---
title: Unlocking Accessibility Issues of Purchased Software on MS Marketplace
date: 2024-07-12T16:43:29.130Z
updated: 2024-07-13T16:43:29.130Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlocking Accessibility Issues of Purchased Software on MS Marketplace
excerpt: This Article Describes Unlocking Accessibility Issues of Purchased Software on MS Marketplace
keywords: Accessible Software MSI,MS Marketplace Integration,Buyers' Accessibility Rights,Purchasing Software Limitations,MS Solutions Compliance,Legal Use Of MS Software,Accessibility Standards MS
thumbnail: https://thmb.techidaily.com/fb8053ac7214659fa378f042df998d4365da978dd3a640439d6ee68045b0a185.jpg
---

## Unlocking Accessibility Issues of Purchased Software on MS Marketplace

 The Microsoft Store lets you install verified apps securely from its app store. However, when you try to install an app, you may encounter an error that says "this app couldn’t be installed." This can happen with a specific app or all the apps you want to install.

 The problem can be as simple as a corrupted Microsoft Store cache or issues with system files. Here are a few troubleshooting steps to quickly resolve this error and get Microsoft Store working again.

## 1\. Run the Microsoft Store Troubleshooter
![windows store apps troubleshooter 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-store-apps-troubleshooter-1.jpg)

 You can quickly fix common Microsoft Store problems using the Windows Store Apps troubleshooter. It is a built-in troubleshooting utility that can scan and fix issues preventing the Microsoft Store from installing apps.

To run the Windows Store Apps troubleshooter:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, scroll down and click on**Troubleshooter.**
3. Next, click on**Other troubleshooters.**
4. Scroll down and click on the**Run** button for Windows Store Apps. The troubleshooter will perform a scan and recommend fixed. Apply any recommended fixes and check for improvements.

## 2\. Clear and Reset the Windows Store Cache Using WSReset
![wsreset clear microsoft store cache](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/wsreset-clear-microsoft-store-cache.jpg)

 WSReset or Windows Store Reset is a built-in utility to reset or clear Windows Store Cache. Resetting the store cache can help you fix temporary glitches preventing you from installing apps from Microsoft Store.

To reset the Windows Store cache:

1. Press the**Win** key and type**wsreset** .
2. Click on**wsreset** –**run command** from the search result. This will open a black Window that will reset the Windows Store cache. The window will close automatically and launch Microsoft Store.
3. Close Microsoft Store and then relaunch the app to see if the error is resolved.

## 3\. Restart the Microsoft Store Install Service

 Microsoft Store Install service provides support for the Microsoft Store and starts on demand. If the service is disabled, you may not be able to install apps from the store resulting in the "this app couldn’t be installed" message.

 To fix the error, check if the service is running. If not, you can enable it manually using the Services snap-in.

To restart Microsoft Store Install Service:

1. Press**Win + R** to open**Run** .
2. Type**services.msc** and click**OK** .
3. In the**Services** snap-in, locate the**Microsoft Store Install Service** entry.  
![microsoft store install service properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/microsoft-store-install-service-properties.jpg)
4. Right-click on the service entry and select**Properties** .
5. In the**Properties** dialog, check if the**Startup type** is set to**Disabled** .  
![microsoft store install service manual startup type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/microsoft-store-install-service-manual-startup-type.jpg)
6. If yes, click the**Startup type** drop-down and select**Manual** .  
![microsoft store install service restart](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/microsoft-store-install-service-restart.jpg)
7. Click**Apply** and**OK** to save the changes.
8. Next, right-click on**Microsoft Store Install Services** and select**Restart** .

 Close the Services snap-in and launch Microsoft Store. Then, try to install the app and check if the error is resolved.

## 4\. Perform a Microsoft Store Repair
![repair microsoft store windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/repair-microsoft-store-windows-11.jpg)

 You can use the built-in repair tool to fix common issues that may prevent the Microsoft Store from triggering such errors. Follow these steps to repair the Microsoft Store app.

1. Press**Win + I** to open**Settings** .
2. Open the**Apps** tab in the left pane.
3. Click on**Installed apps** .
4. Next, search for**Microsoft Store.**
5. Click the**three-dots menu** and select**Advanced options.**
6. Scroll down to the**Reset** section.
7. Click on**Repair** and wait for the process to complete.
8. Once done, relaunch Microsoft Store and try to install the app to see if the error is resolved.

## 5\. Manually Reset Microsoft Store Apps
![reset microsoft store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/reset-microsoft-store.jpg)

 You can manually reset the Microsoft Store app from the Settings app. The Reset option will delete all the app data, and you may need to log in to use Microsoft Store again.

To reset Microsoft Store:

1. Press**Win + I t** o open**Settings** .
2. Open the**Apps** tab in the left pane.
3. Click on**Installed apps** to view all the apps installed on your PC.
4. Search for the**Microsoft Store** app.
5. Click the**three-dots menu** and select**Advanced Options.**
6. Scroll down to the**Reset** section.
7. Click on**Reset** and again on the**Reset** button to confirm the action.
8. Once the**reset** is complete, you’ll see a**checkmark** beside the**Reset** button.

 Launch Microsoft Store and sign in with your Microsoft Account if required. Then, try to install the app and check for any improvements.

## 6\. Re-register the Microsoft Store App
![powershell re_register microsoft store app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/powershell-re_register-microsoft-store-app.jpg)

 Another way to fix the "this app couldn’t be installed" error is to re-register the Microsoft Store using PowerShell. Here’s how to do it.

1. Make sure**Microsoft Store** is closed.
2. Next, press the**Win key** and type**powershell** .
3. Right-click on**PowerShell** and select**Run as administrator.**
4. In the PowerShell window, type the following command to re-register the app for the current user:  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
5. Wait for the command to process and close PowerShell. Relaunch Microsoft Store and check if you can install the app without the error.

## 7\. Reinstall the Microsoft Store

 You can reinstall Microsoft Store to fix issues with the app due to corrupt app files or bugs. Since clearing the cache didn’t help, you can perform a reinstall to resolve the error.

 Note that Microsoft Store is a system app. As a result, you cannot uninstall it from the Settings panel. Instead, you’ll need to use the**Get-AppxPackage** cmdlet in PowerShell to remove and reinstall the app.

 Make sure to [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before uninstalling Microsoft Store. When something goes awry, you can use the restore point to undo the changes and restore your PC to its current state.

To reinstall Microsoft Store:

1. Press the**Win** key and type**powershell** .
2. Right-click on Windows PowerShell and select**Run as administrator.**  
![remove microsoft store powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/remove-microsoft-store-powershell.jpg)
3. Next, in the PowerShell Windows, type the following command and press Enter:  
`get-appxpackage *store |remove-appxpackage`
4. Once the app is removed, use the following command to reinstall Microsoft Store:  
`Get-AppxPackage -AllUsers Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}  

`
5. Wait for the app to install successfully. Then, type**exit** and press**Enter** to close PowerShell.  
![reinstall microsoft store powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/reinstall-microsoft-store-powershell.jpg)
6. Press**Win** key and type**Microsoft Store** to launch the app.

## Fixing the "This App Couldn’t Be Installed" Error on Windows

 This error is often due to issues with the corrupt app cache and temporary glitches. Use the Windows Store Apps troubleshooter or run the WSreset tool to fix common problems with Microsoft Store. If the issue persists, you can perform a reset or re-register the app to resolve the error.

 That said, if the issue persists with a specific app, you can download the Microsoft Store apps using a third-party service and install them manually on your PC.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>



<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/how-to-quickly-enable-or-disable-bing-chat-ai-in-windows-11-taskbar-search/"><u>How to Quickly Enable or Disable Bing Chat AI in Windows 11 Taskbar Search</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-future-of-windows-interface-winbubbles-8-innovations/"><u>The Future of Windows Interface: WinBubble's 8 Innovations</u></a></li>
<li><a href="https://howto.techidaily.com/4-solutions-to-fix-unfortunately-your-app-has-stopped-error-on-xiaomi-13-ultra-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Solutions to Fix Unfortunately Your App Has Stopped Error on Xiaomi 13 Ultra | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-bridging-identities-with-100-creative-and-empowering-insta-captions-for-2024/"><u>[New] Bridging Identities with 100 Creative and Empowering Insta Captions for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-with-ease-to-windows-11s-security-management/"><u>Navigate with Ease to Windows 11’S Security Management</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-wav-conversion-made-easy-a-beginners-best-friend/"><u>New 2024 Approved Wav Conversion Made Easy A Beginners Best Friend</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-mspcm-interface-on-windows-11-easily/"><u>Navigating the MSPCM Interface on Windows 11 Easily</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-a-step-by-step-guide-to-microsoft-teams-snap-photos/"><u>[New] 2024 Approved  A Step-by-Step Guide to Microsoft Teams Snap Photos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insights-into-windows-patch-identification/"><u>Insights Into Window's Patch Identification</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-xiaomi-redmi-12-drfone-by-drfone-virtual-android/"><u>How PGSharp Save You from Ban While Spoofing Pokemon Go On Xiaomi Redmi 12? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-best-vivo-t2x-5g-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>In 2024, Best Vivo T2x 5G Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-secret-techniques-for-a-transparent-windows-11-title-bar/"><u>The Secret Techniques for a Transparent Windows 11 Title Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-control-over-file-explorer-on-stable-windows-11/"><u>Regain Control Over File Explorer on Stable Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-connection-attempted-bluetooth-hiccup-on-pcs/"><u>Solving 'Connection Attempted' Bluetooth Hiccup on PCs</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-the-ultimate-guide-to-tiktok-marketing-best-practices-and-success-stories/"><u>[New] The Ultimate Guide to TikTok Marketing  Best Practices and Success Stories</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-control-over-windows-snipping-commands/"><u>Regaining Control Over Windows' Snipping Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-itunes-operational-status-on-your-pc/"><u>Restoring iTunes Operational Status on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/msix-extension-mastery-a-practical-guide-to-microsoft-store-add-ons/"><u>MSIX Extension Mastery: A Practical Guide to Microsoft Store Add-Ons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-screen-guide-to-windows-11-gpus/"><u>Optimize Your Screen: Guide to Windows 11 GPUs</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-avi-video-rotation-made-easy-top-5-free-solutions-for-2024/"><u>Updated AVI Video Rotation Made Easy Top 5 Free Solutions for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-the-backbone-softwaredistribution-and-catroot2-on-ws11/"><u>Resetting the Backbone: SoftwareDistribution and Catroot2 on WS11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-device-inactivity-in-new-os-sleep-mode/"><u>Overcoming Device Inactivity in New OS Sleep Mode</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-countdown-magic-mastering-fcpx-timers-in-3-short-steps-for-2024/"><u>New Countdown Magic Mastering FCPX Timers in 3 Short Steps for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-limited-access-install-troubleshooting-on-win-1110/"><u>Navigating Through Limited Access Install Troubleshooting on Win 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-stuck-lock-screen-delay-on-pcs/"><u>Solutions for Stuck Lock Screen Delay on PCs</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-innovative-tips-to-create-effective-free-video-advertisements-on-youtube/"><u>[Updated] 2024 Approved  Innovative Tips to Create Effective Free Video Advertisements on YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-cleanse-your-computer-of-previous-security-audits/"><u>How to Cleanse Your Computer of Previous Security Audits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-store-wont-let-you-sign-in-try-these-fixes/"><u>Microsoft Store Won’t Let You Sign In? Try These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turning-android-into-a-compatible-webcam-for-windows-11/"><u>Turning Android Into a Compatible Webcam for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailored-permanent-trash-setup-for-efficient-file-disposal-on-pcs/"><u>Tailored Permanent Trash Setup for Efficient File Disposal on PCs</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-5-top-realistic-text-to-speech-ai-voice-generators-you-may-like/"><u>Updated 5 Top Realistic Text to Speech AI Voice Generators You May Like</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-win1011-recycle-bin-repair-strategies/"><u>Mastering WIN10/11 Recycle Bin Repair Strategies</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-frp-on-tecno-camon-20-by-drfone-android/"><u>In 2024, How to Bypass FRP on Tecno Camon 20?</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-set-longer-duration-for-your-youtube-film/"><u>[New] Set Longer Duration for Your YouTube Film</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-combining-visual-and-auditory-elements-in-the-windows-photos-app-for-2024/"><u>[Updated] Combining Visual and Auditory Elements in the Windows Photos App for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-for-loss-of-pin-access-in-windows-11-post-update-fallout/"><u>Fix for Loss of PIN Access in Windows 11 Post-Update Fallout</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-realme-v30t-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some Pro Tips for Pokemon Go PvP Battles On Realme V30T | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstate-missing-dxgidll-streamline-your-win11/"><u>Reinstate Missing Dxgi.dll, Streamline Your Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-internal-error-in-windows-11-remote/"><u>Mastering the Art of Fixing Internal Error in Windows 11 Remote</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-tackle-dxgierrordevicehunk-on-windows-11/"><u>Steps to Tackle DXGI_ERROR_DEVICE_HUNK on Windows 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/extensive-appraisal-hero4-black-capabilities-for-2024/"><u>Extensive Appraisal  Hero4 Black Capabilities for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-steam-connectivity-woes-in-w11/"><u>Navigating Through Steam Connectivity Woes in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gearing-up-with-best-laptops-from-ifa-2023/"><u>Gearing Up with Best Laptops From IFA 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-credential-store-lockups-on-pcs/"><u>Fix Credential Store Lockups on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-windows-11s-file-order-preferences/"><u>Realigning Windows 11'S File Order Preferences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-picks-for-trusted-free-software-downloads-on-windows/"><u>Top Picks for Trusted, Free Software Downloads on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-walkthrough-switching-nat-type-on-wins-10-and-11/"><u>Step-By-Step Walkthrough: Switching NAT Type on Wins 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-challenge-xfffffddd-print-error-in-xp/"><u>Overcoming the Challenge: XFFFFFDDD Print Error in XP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-steps-to-correct-windows-operating-system-office-errors/"><u>Immediate Steps to Correct Windows Operating System Office Errors</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-boost-traffic-critical-youtube-seo-instruments-for-video-success/"><u>[New] In 2024, Boost Traffic  Critical YouTube SEO Instruments for Video Success</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-dreammaker-8-studio-edition-for-2024/"><u>[New] DreamMaker 8 Studio Edition for 2024</u></a></li>
</ul></div>
