---
title: 7 Strategies for Windows Firewall Configuration
date: 2024-08-16T01:14:58.081Z
updated: 2024-08-17T01:14:58.081Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 7 Strategies for Windows Firewall Configuration
excerpt: This Article Describes 7 Strategies for Windows Firewall Configuration
keywords: WinFirewall Tips,SecureWindows Setup,Firewall Guard Steps,OptimizeWinSecurity,EnhanceWinGuard,WindowsFirewall Strategy,SafePC Networks
thumbnail: https://thmb.techidaily.com/9f88f4d439bd19afe08962ae532d3a6f41b689b2a4dc10b0fa384c3313d41768.jpg
---

## 7 Strategies for Windows Firewall Configuration

 The Windows Firewall protects your device from malicious threats. But if you don't configure its settings correctly, this tool might prevent you from accessing most of the apps on your device.

 So, what's the solution if you've configured the wrong firewall settings by mistake? It's simple—all you need to do is reset these settings to their defaults.

 Let’s dive in and explore all the solutions.

## 1\. Use the Control Panel

 The Control Panel is an incredible tool that allows you to troubleshoot system issues or tweak PC settings. Now, let’s check out how this tool can help you reset the firewall settings:

1. Type **Control Panel** in the Start menu search bar and select the **Best match**. Alternatively, check out [the various way to access the Control Panel](https://www.makeuseof.com/windows-open-control-panel/).
2. Click the **View by** drop-down menu and select either the **Small icons** or **Large icons** option.
3. Select **Windows Defender Firewall** from the menu items.
4. Click the **Restore defaults** option on the left-hand side and follow the on-screen instructions.

![Clicking the Restore defaults option on the Windows Defender Firewall screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/clicking-the-restore-defaults-option-on-the-windows-defender-firewall-screen.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Use the Command Prompt

 Ever used the Command Prompt before? It’s an incredible tool that helps you configure system settings, troubleshoot PC issues, and access various apps.

 In fact, you can perform a lot of tasks with this tool as long as you [type in the correct commands](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/).

 Now, let’s check out how to reset the firewall settings using the Command Prompt:

1. Type **Command Prompt** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as administrator**.
3. Type the following command and press **Enter**:

netsh advfirewall reset

 Wait for the process to complete. From there, restart your device to save these changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
## 3\. Use Windows PowerShell

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

 Struggling to reset the firewall settings using the Command Prompt? If so, then try [Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/).

 Here’s how to reset the firewall settings using PowerShell:

1. Type **Windows PowerShell** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as Administrator**.
3. Copy-paste the following command into PowerShell and press **Enter**:

(New-Object -ComObject HNetCfg.FwPolicy2).RestoreLocalFirewallDefaults()

 Wait for the process to complete, and then restart your device.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## 4\. Use the Windows Security App

 The Windows Security app is a tool that helps you scan and fix system bugs. Interestingly, you can also use this tool to reset the firewall settings.

 Here are the steps you need to follow:

1. Press **Win + I** to access the system settings.
2. Select the **Update & Security** option.
3. Click the **Windows Security** option on the left-hand side.
4. Select the **Firewall & network protection** tool in the middle pane.
5. Click the **Restore firewalls to default** option on the next screen.

![Clicking the Restore firewalls to default option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/clicking-the-restore-firewalls-to-default-option.jpg)
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Use the "Firewall with Advanced Security" Tool

 Still can’t reset the firewall settings? Try one of the options in the “Windows Firewall with Advanced Security” screen.

 As the name suggests, the “Windows Firewall with Advanced Security” tool allows you to configure various advanced settings. So, you can use it later if you want to tweak various firewall settings.

 For now, let’s check out how this tool can help you reset the firewall settings:

1. Press **Win + R** to open the Run command dialog box.
2. Type **wf.msc** and press **Enter** to open the “Windows Defender Firewall with Advanced Security” screen.
3. Navigate to the top-left corner and right-click on the **Windows Defender Firewall with Advanced Security on Local Computer** option.
4. Select the **Restore Default Policy** option.

![Selecting the Restore Default Policy option on the Firewall with Advanced Security screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-restore-default-policy-option-on-the-firewall-with-advanced-secutiry-screen.jpg)
<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Can’t access the “Windows Defender Firewall with Advanced Security” screen using the steps we’ve covered? Try these methods:

1. Press **Win + I** to access the system settings.
2. Select the **Update & Security** option.
3. Click the **Windows Security** option on the left-hand side.
4. Select the **Firewall & network protection** tool in the middle pane.
5. Click **Advanced settings** in the middle pane.

 From there, right-click on the **Windows Defender Firewall with Advanced Security on Local Computer** option and select the **Restore Default Policy** option.

## Restoring the Firewall Settings to Their Default Settings

 It’s quite frustrating when the firewall settings prevent you from accessing the apps on your PC. But the good news is that you can simply resolve such issues by resetting these settings.

 To reset the firewall settings with ease, check out any of the tips we’ve covered. And if you want to reset the Settings app instead, there are solutions for that too!


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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-revolutionize-your-social-media-top-downloader-plugins-and-addons-for-fb-on-firefox/"><u>[New] 2024 Approved  Revolutionize Your Social Media  Top Downloader Plugins and Addons for FB on Firefox</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/treamer-profitability-analysis-and-verification-for-2024/"><u>[New] Streamer Profitability Analysis and Verification for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-chucklechief-your-1-tool-for-tweeting-gifs/"><u>[Updated] 2024 Approved  ChuckleChief  Your #1 Tool for Tweeting Gifs</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-a-step-by-step-guide-to-creating-unique-facebook-video-content/"><u>[Updated] A Step-by-Step Guide to Creating Unique Facebook Video Content</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-explore-11-budget-friendly-title-generators-for-yt-for-2024/"><u>[Updated] Explore 11 Budget-Friendly Title Generators for YT for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-from-reels-to-filters-a-closer-look-at-tiktok-vs-snaps-features/"><u>[Updated] In 2024, From Reels to Filters  A Closer Look at TikTok vs Snap's Features</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-unlock-6-figure-videos-top-hashtag-trends/"><u>[Updated] Unlock 6-Figure Videos  Top Hashtag Trends</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-assessing-acid-pro-top-alternative-software/"><u>2024 Approved  Assessing ACID Pro  Top Alternative Software</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-deciphering-the-advantages-of-modern-multicam-technology/"><u>2024 Approved  Deciphering the Advantages of Modern Multicam Technology</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-free-mp4-screen-capture-toolkit-released/"><u>2024 Approved  Free MP4 Screen Capture Toolkit Released</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-revisiting-video-broadcast-choices-post-wirecast/"><u>2024 Approved  Revisiting Video Broadcast Choices Post-Wirecast</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-the-humor-in-highlights-best-mobile-edits-compared/"><u>2024 Approved  The Humor in Highlights  Best Mobile Edits Compared</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/2024-approved-youtube-snippets-guide-essential-info-inside/"><u>2024 Approved  YouTube Snippets Guide  Essential Info Inside</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/2024s-ultimate-lineup-a-look-at-leading-game-devices/"><u>2024'S Ultimate Lineup: A Look at Leading Game Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-a-three-dimensional-soundscape-in-windows-11/"><u>Achieving a Three-Dimensional Soundscape in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/audio-visual-assurance-verify-windows-equipment-before-calling/"><u>Audio Visual Assurance: Verify Windows Equipment Before Calling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-storage-demands-on-windows-os/"><u>Decoding the Storage Demands on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discreet-deletion-of-email-after-signing-in-windows/"><u>Discreet Deletion of Email After Signing In Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-search-on-windows-11-the-top-5-must-knows/"><u>Elevating Search on Windows 11: The Top 5 Must-Knows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-0x800f0845-from-windows-updates/"><u>Eradicating 0X800f0845 From Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-resolving-outlook-errors-on-windows/"><u>Expert Tips: Resolving Outlook Errors on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-and-engage-with-10-key-network-settings-in-winos/"><u>Explore and Engage with 10 Key Network Settings in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-and-restore-your-microsoft-store-registrations-win-11/"><u>Fix and Restore Your Microsoft Store Registrations (Win 11)</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-vivo-t2x-5g-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an Vivo T2x 5G Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-factory-reset-ipad-or-iphone-13-without-icloud-password-or-apple-id-by-drfone-ios/"><u>How to Factory Reset iPad or iPhone 13 without iCloud Password or Apple ID?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-install-microsoft-defender-application-guard-for-edge-in-windows-11/"><u>How to Install Microsoft Defender Application Guard for Edge in Windows 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-apple-iphone-se-2022-to-other-iphone-drfone-by-drfone-ios/"><u>How to Mirror Apple iPhone SE (2022) to Other iPhone? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-easy-steps-on-how-to-create-a-new-apple-id-account-on-iphone-x-drfone-by-drfone-ios/"><u>In 2024, Easy Steps on How To Create a New Apple ID Account On iPhone X | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-iphones-a-compreenas-guide-to-storing-and-sharing-gifs/"><u>In 2024, IPhones  A Compreenas Guide to Storing & Sharing GIFs</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-orbiting-imagery-advanced-methods-for-drone-video-editing/"><u>In 2024, Orbiting Imagery  Advanced Methods for Drone Video Editing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-advanced-shortcuts-into-windows-explorer-menus/"><u>Integrating Advanced Shortcuts Into Windows Explorer Menus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-text-selection-in-windows-compatible-pdfs/"><u>Mastering Text Selection in Windows-Compatible PDFs</u></a></li>
<li><a href="https://youtube-help.techidaily.com/maximize-your-youtube-income-with-effective-mobile-device-strategies-for-2024/"><u>Maximize Your YouTube Income with Effective Mobile Device Strategies for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/poco-f5-pro-5g-music-recovery-recover-deleted-music-from-poco-f5-pro-5g-by-fonelab-android-recover-music/"><u>Poco F5 Pro 5G Music Recovery - Recover Deleted Music from Poco F5 Pro 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-persistent-microsoft-edge-shortcuts/"><u>Preventing Persistent Microsoft Edge Shortcuts</u></a></li>
<li><a href="https://extra-support.techidaily.com/rapid-rhythmic-revision-software-roundup-mobiledesktop-for-2024/"><u>Rapid Rhythmic Revision Software Roundup (Mobile/Desktop) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-functionality-of-windows-photo-viewer-in-win11/"><u>Restoring Functionality of Windows Photo Viewer in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-missing-data-from-windows-1011s-search-feature/"><u>Restoring Missing Data From Windows 10/11'S Search Feature</u></a></li>
<li><a href="https://location-social.techidaily.com/simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-apple-iphone-14-plus-drfone-by-drfone-virtual-ios/"><u>Simple and Effective Ways to Change Your Country on YouTube App Of your Apple iPhone 14 Plus | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-directdraw-crashes-in-win11-a-step-by-step-guide/"><u>Solving DirectDraw Crashes in Win11: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-correcting-file-errors-in-windows-11/"><u>Steps to Correcting File Errors in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-the-endless-cycle-of-windows-ui-issues/"><u>Stop the Endless Cycle of Windows UI Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-error-code-0x80070091-empty-directories-unveiled/"><u>Tackling Windows Error Code 0X80070091 - Empty Directories Unveiled</u></a></li>
<li><a href="https://some-guidance.techidaily.com/tactics-for-triumphing-in-virtual-marketplaces-for-2024/"><u>Tactics for Triumphing in Virtual Marketplaces for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-5-best-pc-optimization-tools-on-a-windows-pc/"><u>The 5 Best PC Optimization Tools on a Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-hidden-perils-behind-budget-windows-activation-codes/"><u>The Hidden Perils Behind Budget Windows Activation Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-surface-computer-firmware-update-manual/"><u>The Ultimate Surface Computer Firmware Update Manual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-altering-window-icons-distance-on-11plus-windows/"><u>Title: Altering Window Icons' Distance on 11+ Windows</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/troubleshooting-excessive-obs-bitrate/"><u>Troubleshooting Excessive OBS Bitrate</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-tackling-steam-disk-errors/"><u>Understanding and Tackling Steam Disk Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrading-graphic-memory-in-windows-11-systems/"><u>Upgrading Graphic Memory in Windows 11 Systems</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/windows-11-and-battery-health-unveiling-the-secrets-of-system-reports/"><u>Windows 11 and Battery Health: Unveiling the Secrets of System Reports</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-wrinkle-free-up-operator-installation/"><u>Windows Wrinkle? Free Up Operator Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/workflow-enhancer-integrating-sticky-notes-into-your-windows-morning-ritual/"><u>Workflow Enhancer: Integrating Sticky Notes Into Your Windows Morning Ritual</u></a></li>
</ul></div>
