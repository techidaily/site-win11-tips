---
title: "Understanding & Resolving WinError: 0X80071a90 in Windows"
date: 2024-08-16T01:38:08.846Z
updated: 2024-08-17T01:38:08.846Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Understanding & Resolving WinError: 0X80071a90 in Windows"
excerpt: "This Article Describes Understanding & Resolving WinError: 0X80071a90 in Windows"
keywords: ErrorCodeWin7,WinErrorResolution,WindowsInstallationIssue,FixWindowsError7190,WinXPErrorHandler,WindowsOSTroubleshoot,UninstallingError7190
thumbnail: https://thmb.techidaily.com/31e82f83edcdc65ad4f95de4a88750a749956ca58ec25424a7976e33fcb26a46.jpg
---

## Understanding & Resolving WinError: 0X80071a90 in Windows

 The Windows Features error 0x80071A90 occurs when the users try to install or enable a features component such as .NET Framework but the process fails. This typically happens when there is an issue within the Windows component store which maintains the system components.

 Below, we take a look at why this error occurs, and the solutions to try to resolve it for good.

## Factors That Might Be Contributing to the 0x80071A90 Error

 While there are several factors that might be contributing to the Windows Features error, here are the most common ones:

* **Antivirus interruption** : If you are using a third-party security program on your computer, there is a chance that it is blocking the installation or enablement of Windows features by detecting them as potentially harmful or unwanted. This is often a false security alarm.
* **Third-party software conflicts** : Sometimes, a third-party program running in the background can interfere with the installation or enablement of Windows features, leading to the error code 0x80071A90.
* **Corrupted system files** : If the system files that are critical for the installation or enablement of Windows features are missing or corrupted, you are likely to run into the error under consideration.
* **Outdated incomplete Windows updates** : Your system might be outdated, which is resulting in compatibility issues and preventing you from installing/enabling certain Windows features.
* **Other hardware or software issues** : In some cases, hardware or software issues like problems with the device drivers or registry settings can also lead to the Windows Features error.

 Regardless of what might be causing the problem in your case, the troubleshooting methods we have listed above should help you fix it in no time. Proceed with the method that fits your situation the best.

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
## 1\. Disable Your Antivirus

 Antivirus programs are designed to protect your computer from harmful software and viruses but in doing so, they may also prevent some legitimate Windows components and features from installing or updating properly. This typically happens when the antivirus falsely considers the feature to be harmful.

 Some programs can also interfere with the Windows component store or the update process, leading to the problem.

 This is why, we recommend getting started with disabling your antivirus program temporarily. The exact steps of doing so may differ, depending upon the security program you are using. However, typically, you can achieve this by right-clicking on the antivirus icon in the taskbar and choosing**Disable until the computer is restarted** .

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 Once the security program is disabled, try enabling the targeted Windows feature again and check if the problem is now fixed. If the antivirus program happens to be the culprit, you can consider switching to a better alternative.

## 2\. Perform the Action in Safe Mode

 As we mentioned earlier, certain applications and processes running in the background can also interfere with the installation or enablement of Windows features. To prevent any potential third-party software conflicts, you can try performing the action in Safe Mode.

 This mode launches Windows with only the necessary drivers and services, allowing you to finish tasks without interference from third-party software.

 Once you [boot into Safe Mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) , launch the Windows Features utility and try performing the action that was initially triggering the error. If a background process was leading to it, you should be able to enable the targeted feature without any problems now.

## 3\. Rebuild the WMI Repository

 You might also be facing the problem due to a corrupted WMI Repository.

 This repository is like a database where your system stores information about hardware, software, and other related settings. This information can be used by software programs and administrative scripts to manage the system settings and if the repository has corrupt or missing files, it can lead to issues like Windows Features error.

 To fix issues with the WMI repository, you can rebuild it, which will essentially check the repository for any inconsistencies and reset it to its default state. This can help fix any issues that were preventing the installation or enablement of Windows features.

Follow these steps to proceed:

1. Press the**Win** +**R** keys together to open Run.
2. Type "cmd" in Run and press**Ctrl** +**Shift** +**Enter** keys together. This will launch Command Prompt as an administrator.
3. Click**Yes** in the User Account Control prompt.
4. Once you are inside the Command Prompt, execute the following commands one by one:  
`winmgmt /salvagerepositorywinmgmt /verifyrepositorywinmgmt /resetrepository`
5. Wait for the commands to execute and then exit Command Prompt. You can now check if the issue is resolved.

## 4\. Try Some Generic Windows-Based Fixes for Errors

 If nothing else works, these general WIndows fixes can help you fix the issue:

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Update Windows
![install windows 11 feature update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/install-windows-11-feature-update.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->

 If you haven’t installed the latest Windows updates in a while, then you might be facing the problem due to an outdated system. This can be due to a compatibility issue or because your system lacks updates/hotfixes that were released by Microsoft to address specific issues related to Windows features.

 In this case, we recommend taking your time to [install any pending Windows updates](https://www.makeuseof.com/windows-11-install-updates/) available. This will ensure that the drivers and software are compatible with the latest version of Windows.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
### Check the System for Corruption Errors
![Run SFC scan in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/sfc-scan-1-1.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In order to install or enable Windows features, the system relies on critical files and the Windows component store. If any of these files or the store becomes corrupted, it can impede the system's access to the necessary components for feature installation or enablement, leading to errors like the one at hand.

 To fix such corruption errors, you can use a tool like the System File Checker (SFC) to scan and repair system files or the Deployment Image Servicing and Management (DISM) tool to repair the Windows component store. You can run both these utilities via Command Prompt.

 Follow the correct steps for running SFC and DISM in Windows in our guide on [how to fix file system errors on Windows](https://www.makeuseof.com/fix-file-system-errors-windows/) .

<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Enable Your Windows Features Again

 The Windows Features error 0x80071A90 is a frustrating problem that can prevent you from installing/enabling certain Windows features. Fortunately, there are several troubleshooting methods that can help you fix it for good.

 To prevent any such issues from occurring in the future, we highly recommend keeping your Windows up-to-date at all times. Additionally, make sure you use a reputable antivirus and avoid unsafe third-party programs that can interfere with the system processes.


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
<li><a href="https://screen-recording.techidaily.com/new-a-practical-handbook-for-recording-virtual-play-battles-for-2024/"><u>[New] A Practical Handbook for Recording Virtual Play Battles for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-cold-climates-hot-wins-beijing-highlights/"><u>[Updated] Cold Climates, Hot Wins  Beijing Highlights</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-gamers-choice-best-alternatives-to-official-recorder-for-2024/"><u>[Updated] Gamer's Choice  Best Alternatives to Official Recorder for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-strategic-youtube-content-publishing-to-boost-view-counts-for-2024/"><u>[Updated] Strategic YouTube Content Publishing to Boost View Counts for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-5-best-toy-drones/"><u>2024 Approved  5 Best Toy Drones</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-from-celluloid-to-screen-adapting-your-vids-for-ig/"><u>2024 Approved  From Celluloid to Screen  Adapting Your Vids for IG</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-superior-sonic-collectors-for-seminars/"><u>2024 Approved  Superior Sonic Collectors for Seminars</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-windows-11s-missing-wi-fi-functionality/"><u>Boosting Windows 11'S Missing Wi-Fi Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-your-pc-health-top-13-tactics-to-restore-windows/"><u>Boosting Your PC Health: Top 13 Tactics to Restore Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/break-free-from-verifying-glass-cases-in-windows-installation/"><u>Break Free From Verifying Glass Cases in Windows Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-windows-11s-spotify-link-barriers/"><u>Breaking Down Windows 11'S Spotify Link Barriers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-into-high-privilege-windows-command-center/"><u>Breaking Into High-Privilege Windows Command Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-code-how-to-reactivate-memory-feature-in-win11/"><u>Breaking the Code: How to Reactivate Memory Feature in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridge-firewall-gap-enable-chrome-networking-in-windows-os/"><u>Bridge Firewall Gap: Enable Chrome Networking in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-gaps-in-windows-11-sticky-notebook-coordination/"><u>Bridging Gaps in Window's 11 Sticky Notebook Coordination</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-the-gap-between-windows-and-photoshop-open-up-delays/"><u>Bridging the Gap Between Windows and PhotoShop Open-Up Delays</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-more-to-the-table-reimagining-windows-11s-widget-framework/"><u>Bringing More to the Table: Reimagining Windows 11'S Widget Framework</u></a></li>
<li><a href="https://win11-tips.techidaily.com/browser-blackout-blues-efficient-strategies-to-unlock-windows-sites/"><u>Browser Blackout Blues: Efficient Strategies to Unlock Windows Sites</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-windows-download-block-with-opera-tricks/"><u>Bypass Windows Download Block with Opera Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-access-denied-saving-problems-on-windows/"><u>Bypassing Access Denied Saving Problems on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-audacity-sound-error-in-windows-10-and-11/"><u>Bypassing Audacity Sound Error in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-microsoft-store-lockdown-on-windows-11/"><u>Bypassing Microsoft Store Lockdown on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-the-not-found-window-error/"><u>Bypassing the Not Found Window Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-user-account-prompts-in-windows/"><u>Bypassing User Account Prompts in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-permission-issues-easily/"><u>Bypassing Windows Permission Issues Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cant-select-or-highlight-text-in-a-pdf-on-windows-heres-how-to-fix-it/"><u>Can't Select or Highlight Text in a PDF on Windows? Here's How to Fix It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/capture-windows-like-a-pro-snip-tool-vs-prtsc-advantages/"><u>Capture Windows Like a Pro: Snip Tool Vs. PrtSc Advantages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/capturing-sound-in-win-11-step-by-step/"><u>Capturing Sound in Win 11 Step-by-Step</u></a></li>
<li><a href="https://win11-tips.techidaily.com/character-map-navigation-in-new-windows-11/"><u>Character Map Navigation in New Windows 11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/effective-way-to-repair-your-hard-drive-with-windows-chkdsk-command/"><u>Effective Way to Repair Your Hard Drive with Windows' Chkdsk Command</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/expert-advice-restoring-your-surface-pros-ability-to-connect-to-wireless-networks/"><u>Expert Advice: Restoring Your Surface Pro’s Ability to Connect to Wireless Networks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719360477145-reigniting-your-computers-print-functionality-with-effective-wwin-solutions/"><u>Reigniting Your Computer's Print Functionality with Effective WWin Solutions</u></a></li>
<li><a href="https://buynow-info.techidaily.com/travel-light-click-with-confidence-the-perfect-blend-of-accuracy-and-cables-in-sabrents-portable-mouse-solution/"><u>Travel Light, Click with Confidence - The Perfect Blend of Accuracy & Cables in Sabrent's Portable Mouse Solution</u></a></li>
</ul></div>
