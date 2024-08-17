---
title: Addressing Taskbar Inactivity in Windows OS
date: 2024-08-16T01:37:13.864Z
updated: 2024-08-17T01:37:13.864Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Taskbar Inactivity in Windows OS
excerpt: This Article Describes Addressing Taskbar Inactivity in Windows OS
keywords: Taskbar Latency Fix,Window OS Performance,Taskbar Response Time,Active Taskbar Status,Minimize Delay Reduction,User Interface Speedup,Windows Efficiency Boost
thumbnail: https://thmb.techidaily.com/39891eff73508b464f66ea96b5a005498dc7a497b224e926f9156c826add0320.jpeg
---

## Addressing Taskbar Inactivity in Windows OS

 Task Manager is one of the most important Windows 11/10 system utilities. So, it’s a big issue when Task Manager is not working. Some users have reported Task Manager not opening (working) for them when they try to access it.

 Task Manager might throw up an error message or simply not respond when it’s not working. Task Manager opens with a blank window and crashes soon after for some users. Users can’t utilize Task Manager when it’s not working. This is how you can fix Task Manager not working on a Windows 11/10 PC.

## 1\. Run System File and Image Repair Commands

 Many users have confirmed running system file and image repair commands can fix the Task Manager not working. So, that’s one of the first things you should try for fixing Task Manager when it’s not opening.

 To apply this potential solution, you’ll need to input separate Command Prompt commands for running the DISM (Deployment Image Servicing and Management) and SFC (System File Checker) tools. The SFC tool repairs system files and DISM services the Windows image.

 Follow the instructions in our article about [repairing corrupted Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) to run the SFC and DISM command-line tools.

![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/sfc-scannow-command2.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Disable the Remove Task Manager Policy

 Group Policy Editor includes an option for disabling Task Manager. If you see an error message that states Task Manager is disabled, that option is likely enabled. Even if you don’t see an error message, you should still check the **Remove Task Manager** policy if you can access Group Policy Editor on your PC. This is how you can disable the **Remove Task Manager** policy:

1. [Open Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) on your Windows PC. If you're on Windows Home, you'll need to learn [how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) first.
2. Double-click **User Configuration** \> **Administrative Templates** \> **System** \> **Ctrl + Alt + Del Options** in Group Policy Editor’s sidebar.  
![The Ctrl+Alt+Del Options policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/remove-task-manager-policy.jpg)
3. Next, double-click **Remove Task Manager** to view a window for configuring that policy.
4. Select **Disabled** or **Not Configured** if you find this policy enabled.  
![The Remove Task Manager window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/remove-task-manager-window.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
5. Click **Apply** to set the new option for enabling Task Manager.
6. Then close the Remove Task Manager window by clicking **OK**.

 If this policy is not enabled, try turning it on and off. Click **Enabled** and **Apply** to activate the policy. Then select **Disabled**/**Not configured** to disable it.

## 3\. Initiate an Antivirus Scan

 Malware can sometimes be the reason for the Task Manager not working. Task Manager is targeted by malware because it’s an important system utility. So, [run an antivirus scan](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) with Windows Security or third-party security software to check for and purge malware from your PC. Select the most thorough antivirus scanning option in whatever option you utilize.

![The antivirus scan options in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/scan-now-option.jpg)
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Edit the Policies Key

 Note that running an antivirus scan might only eliminate the cause of this issue. Then you would still need to re-enable Task Manager to get it working after purging malware that disabled it. A virus will have likely disabled Task Manager in the registry. You can re-enable the Task Manager by editing the Policies registry key like this:

1. To access Registry Editor, press the **Windows key + S** key combination, enter a **regedit** keyword, and click the matching result shown in the search tool.
2. Next, go to the **Policies** key by inputting this path inside the registry address bar:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies`
3. Skip to step seven if you can see a **System** subkey. If you can’t, right-click **Policies** and select **New** \> **Key**.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-key-options.jpg)
4. Enter **System** in the new key’s text box.
5. Right-click **System** and select **New** \> **DWORD**.

1. Input **DisableTaskMgr** inside the DWORD’s text box.
2. Double-click the **DisableTaskMgr** DWORD within the **System** key.  
![The DisableTaskMgr DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disabletskmgr-dword.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. The value for the **DisableTaskMrg** DWORD should be **0**. If it’s set any differently, erase the number in the **Value** box and input **0**.
4. Click **OK** to set the **DisableTaskMgr** value.  
![The Edit DWORD (32-bit) Value window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-edit-dword-window.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
5. Now close the Registry Editor. To ensure the changes take effect, [restart your Windows PC](https://www.makeuseof.com/windows-restart-methods/) after editing the registry.

## 5\. Run the PowerShell Command for Re-Registering Apps

 Some users say they managed to fix Task Manager by running a PowerShell command for reinstalling and registering built-in Windows 11/10 apps. If that worked for them, maybe this resolution will fix Task Manager not working on your PC. This is how you can run that PowerShell command:

1. Activate the **Type here to search** box by utilizing the **Windows key + S** keyboard shortcut.
2. Enter **PowerShell** inside the file search box.
3. Click **Run as administrator** for the matching PowerShell app search result.
4. Input this command:  
`Get-AppXPackage | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The PowerShell command that can fix Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-reinstall-apps-command.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
5. Press **Enter** to execute the command and wait for it to finish before exiting PowerShell.

## 6\. Change Your User Account

 Windows user account issues can also cause Task Manager to stop working. For example, your user account might be corrupted in some way. In this case, you can try to repair the corrupted user account or set up an entirely new one. Task Manager might work fine in a new user account.

 First, set up a new user account and sign into it to see if Task Manager works there. If it does, transfer all the user files from your old Windows account to the new one. Our guide to [fixing Windows issues by creating new accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) includes instructions for applying this troubleshooting method.

![The Add account button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/add-account-button.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Restore Windows to an Earlier Time

 The System Restore tool can address some of the potential causes for Task Manager not working if you have it enabled. Much depends on whether you can select a restoration point that will roll Windows back to a date when Task Manager worked okay. If you can, rolling Windows back to an earlier time is worth a try when other potential solutions are ineffective.

 Our article about [how to utilize System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) tells you how to apply this potential fix. Choose a restoration point that will restore Windows to a time when you could utilize Task Manager without issues. You’ll need to reinstall desktop software and apps installed after a chosen restore point.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/system-restore-window.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->

## 8\. Reset Your Window PC

 This final resolution for the Task Manager not working is the most nuclear of the lot. Resetting Windows 11/10 will restore the platform to factory default settings by reinstalling it, which will obliterate malware and repair system file issues. It’s recommended as a last resort since resetting Windows will wipe out all the software you’ve installed.

 You can apply this potential resolution with the Reset this PC tool, as covered in this article about [resetting Windows 10 or 11](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/#:~:text=To%20access%20this%20Windows%20reinstall,this%20PC%20to%20get%20started.). There’s no need to back up user files since you can select a **Keep my files** option within the Reset this PC window. Make sure the **Reinstall preinstalled apps** option is selected to retain the software bundled with your PC.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/reset-this-pc-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->
## Use Task Manager Within Windows Again

 Task Manager is not something most users can do without. Fortunately, the potential resolutions in this guide will likely resolve many of the Task Manager issues that prevent users from opening and utilizing that utility. At least one will probably kick-start Task Manager on your PC, enabling you to use that tool as required again.

 Task Manager might throw up an error message or simply not respond when it’s not working. Task Manager opens with a blank window and crashes soon after for some users. Users can’t utilize Task Manager when it’s not working. This is how you can fix Task Manager not working on a Windows 11/10 PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-bringing-rhythm-to-instagrams-visual-narratives/"><u>[New] 2024 Approved  Bringing Rhythm to Instagram's Visual Narratives</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-how-to-download-and-keep-your-favorite-fb-stories-for-2024/"><u>[Updated] How to Download and Keep Your Favorite FB Stories for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-interactive-multiplayer-experiences-online/"><u>[Updated] Interactive Multiplayer Experiences Online</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-the-science-of-hashtags-how-they-drive-instagram-success/"><u>[Updated] The Science of Hashtags  How They Drive Instagram Success</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-isyncslideshow-integrate-ios-plus-sierra-images/"><u>2024 Approved  ISyncSlideshow  Integrate iOS + Sierra Images</u></a></li>
<li><a href="https://buynow-help.techidaily.com/argument-unveiling-the-merits-of-owning-an-ipad/"><u>Argument: Unveiling the Merits of Owning an iPad</u></a></li>
<li><a href="https://facebook.techidaily.com/beyond-the-likes-and-shares-unraveling-facebook-fact-from-fiction/"><u>Beyond the Likes and Shares: Unraveling Facebook Fact From Fiction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/browsing-lightly-identifying-minimal-resource-using-software-across-windowsmacoschromeos/"><u>Browsing Lightly: Identifying Minimal Resource-Using Software Across Windows/macOS/ChromeOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/chrome-opening-woes-resolved-fast-fixed-for-windows-11-users/"><u>Chrome Opening Woes Resolved: Fast Fixed for Windows 11 Users</u></a></li>
<li><a href="https://extra-tips.techidaily.com/community-shared-music-collections-copyright-free/"><u>Community-Shared Music Collections (Copyright-Free)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crucial-software-aid-the-best-windows-apps-that-facilitate-mac-switch/"><u>Crucial Software Aid: The Best Windows Apps That Facilitate MAC Switch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-and-dissolving-ms-teams-error-80080300-on-win11-platform/"><u>Deciphering and Dissolving MS Teams Error 80080300 on Win11 Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/digital-impressions-drawing-techniques-for-pc-screens/"><u>Digital Impressions: Drawing Techniques for PC Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ditch-installation-struggles-preparations-before-vbox-on-pc/"><u>Ditch Installation Struggles: Preparations Before VBox on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-deep-a-comprehensive-guide-to-os-settings/"><u>Dive Deep: A Comprehensive Guide to OS Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-internal-rdp-problems-on-windows-os/"><u>Eliminating Internal RDP Problems on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-managed-users-and-groups-in-win1110-homes/"><u>Enabling Managed Users and Groups in Win11/10 Homes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harmonize-window-11-settings-for-clear-prime-video-texts/"><u>Harmonize Window 11 Settings for Clear Prime Video Texts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-bypass-win11s-alarming-zero-error-alerts/"><u>How to Bypass Win11’s Alarming Zero Error Alerts</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-send-and-fake-live-location-on-facebook-messenger-of-your-zte-axon-40-lite-drfone-by-drfone-virtual-android/"><u>How to Send and Fake Live Location on Facebook Messenger Of your ZTE Axon 40 Lite | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stop-microsoft-edges-from-popping-up/"><u>How to Stop Microsoft Edges From Popping Up</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-stream-anything-from-vivo-s18-to-apple-tv-drfone-by-drfone-android/"><u>How To Stream Anything From Vivo S18 to Apple TV | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-samsung-galaxy-a14-5g-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Samsung Galaxy A14 5G to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-can-i-bypass-a-forgotten-phone-password-of-samsung-galaxy-a14-4g-by-drfone-android/"><u>In 2024, Can I Bypass a Forgotten Phone Password Of Samsung Galaxy A14 4G?</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-easy-photo-progression-on-instagram/"><u>In 2024, Easy Photo Progression on Instagram</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insight-into-the-workings-of-windows-odbc-tools/"><u>Insight Into the Workings of Windows ODBC Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-program-harmony-in-os-with-win-pct-wisdom/"><u>Master Program Harmony in OS with Win-PCT Wisdom</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-books-8-effective-studying-tips-on-windows/"><u>Mastering the Books: 8 Effective Studying Tips on Windows</u></a></li>
<li><a href="https://win-solutions.techidaily.com/navigating-through-microsoft-flight-simulator-2020s-update-problem-solutions-inside/"><u>Navigating Through Microsoft Flight Simulator 2020'S Update Problem – Solutions Inside</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-utorrent-install-issues-on-a-windows-laptop/"><u>Navigating uTorrent Install Issues on a Windows Laptop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/opera-installer-lockdown-try-these-window-tips/"><u>Opera Installer Lockdown? Try These Window Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-file-operations-in-powershell-and-command-prompt/"><u>Optimizing File Operations in PowerShell & Command Prompt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-cleanup-automating-deletion-of-files-in-windows/"><u>Quick Cleanup: Automating Deletion of Files in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-steps-to-record-windows-uac-notifications/"><u>Quick Steps to Record Windows UAC Notifications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-administrative-controls-on-windows-defense-measures/"><u>Reversing Administrative Controls on Windows Defense Measures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-your-computers-print-command-conundrum-with-effective-tips/"><u>Solving Your Computer's Print Command Conundrum with Effective Tips.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speak-write-and-transform-an-intuitive-guide-to-text-generation-with-windows-whisper/"><u>Speak, Write and Transform: An Intuitive Guide to Text Generation with Windows Whisper</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-tackle-windows-administrator-security-configs/"><u>Steps to Tackle Windows Administrator Security Configs</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/strategic-approaches-to-share-ppt-powerfully-in-google-meet/"><u>Strategic Approaches to Share PPT Powerfully in Google Meet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-removing-signature-rejection-on-pcs/"><u>Strategies for Removing Signature Rejection on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-tasks-with-these-8-best-rated-window-pomodoros/"><u>Streamline Your Tasks With These 8 Best-Rated Window Pomodoros</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-missing-mcuicnt-file-execution-issue-on-windows/"><u>Tackling Missing McUICnt File Execution Issue on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-shutdown-playbook-avoiding-windows-11-activities/"><u>The Shutdown Playbook: Avoiding Windows 11 Activities</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/the-syncopated-science-of-video-and-music-on-vimeo-for-2024/"><u>The Syncopated Science of Video and Music on Vimeo for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/top-10-password-cracking-tools-for-samsung-galaxy-f34-5g-by-drfone-android/"><u>Top 10 Password Cracking Tools For Samsung Galaxy F34 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-guide-5-steps-to-reset-windows-defender-status/"><u>Troubleshooting Guide: 5 Steps to Reset Windows Defender Status</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-stable-internet-windows-edition-guide/"><u>Troubleshooting Stable Internet: Windows Edition Guide</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/understanding-and-fixing-bsod-caused-by-internal-video-memory-management-errors/"><u>Understanding and Fixing BSOD Caused by Internal Video Memory Management Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-should-you-care-about-runtime-brokers-on-your-system/"><u>Why Should You Care About Runtime Brokers on Your System?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-back-access-clearing-windowss-prior-passcode/"><u>Winning Back Access: Clearing “Windows's Prior Passcode”</u></a></li>
</ul></div>
