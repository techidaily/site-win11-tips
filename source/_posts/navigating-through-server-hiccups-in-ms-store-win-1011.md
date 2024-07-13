---
title: Navigating Through Server Hiccups in MS Store, Win 10/11
date: 2024-07-12T16:48:17.651Z
updated: 2024-07-13T16:48:17.651Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Through Server Hiccups in MS Store, Win 10/11
excerpt: This Article Describes Navigating Through Server Hiccups in MS Store, Win 10/11
keywords: MS Store Performance,Win 10 Error Fixing,Win 11 Troubleshooting,Server Hiccup Solutions,Optimizing Windows Store,App Crash Prevention,Stable MS Platform
thumbnail: https://thmb.techidaily.com/6ea9e47c2657fcc7075624e0c60b4b097654c22032956cf343f01ab1f87ea6c8.jpg
---

## Navigating Through Server Hiccups in MS Store, Win 10/11

 Some Microsoft Store users have reported a “server stumbled” error on support forums. Those users have seen this error message within the Microsoft Store app: “The server stumbled… We all have bad days.” That error message usually has 0x80072F05, 0x80131500, or 0x80072ee7 codes.

 This is yet another error that makes the Microsoft Store app unusable when users launch it. Does the same “server stumble” error message crash your Microsoft Store app? If that’s the case, this is how you can resolve that “server stumble” error in Windows 11 and 10.

## 1\. Run the Troubleshooter for Microsoft Store Apps

 The Windows Store App troubleshooter can resolve issues that stop the Microsoft Store app from working. Running that troubleshooter isn’t a surefire fix for every Microsoft Store error, but it’s worth a try.

 These are the steps for running the Windows Store App troubleshooter in Windows:

1. Press**Win + I** keyboard shortcut to open Settings.
2. Then select the**Troubleshoot** navigation bar within Settings’ default**System** tab.
3. Click**Other troubleshooters** to reach the troubleshooting tools.
4. Select the**Run** option for launching Windows Store Apps.  
![The Run button for the Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-run-button.jpg)
5. Click to apply any potential fix suggested within the troubleshooter.  
![Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-store-apps-troubleshooter.jpg)

 The steps for opening the same troubleshooter in Windows 10 aren’t exactly the because of the Settings app’s different layout. You’ll need to click**Update & Security** \>**Troubleshoot** \>**Additional Troubleshooters** in Windows 10’s Settings app. Click Windows Store Apps to press a**Run the troubleshooter** button that opens that troubleshooting tool.

## 2\. Check the Date & Time Settings on Your PC

 Date & time discrepancies on your PC can cause Microsoft Store connectivity issues like the “server stumbled” error to arise. Check the time zone you’ve got set matches up with your PC’s regional configuration. You can verify your PC’s time by selecting to sync its clock. This is how you can check the time configuration within Settings:

1. Open Settings and select the**Time & language** tab.
2. Then click**Date & time** to view those settings.
3. Make sure the correct time zone for your region is selected on the**Time zone** drop-down menu.  
![The Sync now button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/time-zone-drop-down-menu.jpg)
4. Press the**Sync now** button to synchronize with the Windows time server.

## 3\. Start or Restart the Windows Update Service

 MS Store users have confirmed they’ve fixed the “server stumbled” error by starting or restarting the Windows Update service. The Windows Update service is linked with Microsoft Store. So, make sure that the update service is enabled and running as follows:

1. Press**Win + S** to access the Windows Search tool.
2. Type "services," then select**Services** to access the app.
3. Double-click**Windows Update** to view the various settings for that service.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-update-service.jpg)
4. Select**Automatic** if any other option is set on the**Startup** type drop-down menu.
5. Then click the service’s**Start** option if Windows Update is stopped.
6. Press**Apply** to set the service settings.  
![The Windows Update Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-update-properties-window.jpg)
7. Click**OK** or the**X** button to exit Windows Update’s properties window.

 Restart Windows Update if you find that the service is already running with an**Automatic** startup set. You can do that by clicking Windows Update with your mouse’s right button and selecting**Restart** . Or select**Stop** and then**Start** within its properties window.

![The Restart option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restart-option.jpg)

## 4\. Reset the Microsoft Store Cache

 The Microsoft Store has a cache containing temporary, thumbnail, and log file data. A clogged-up cache with corrupted data can cause many MS Store issues. So, some users might need to reset (clear) that cache to fix the “server stumbled” error.

 You can clear that cache by entering the**WSreset.exe** command as outlined in method two within our guide on [how to reset the Microsoft Store](https://www.makeuseof.com/windows-10-11-reset-microsoft-store/) .

![The wsreset command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/wsreset-command.jpg)

## 5\. Turn Off Any Active Proxy Server Settings

 Some users use a proxy server to mask their IP address, but doing sooften causes Microsoft Store connection errors. If you’ve got an intermediary proxy server enabled on your PC, disable it via Settings or the Control Panel.

 Our guide on [how to disable the proxy server settings on Windows](https://www.makeuseof.com/windows-11-disable-proxy/) provides step-by-step instructions for both methods.

![The Use a proxy server for your LAN checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/use-a-proxy-server-option.jpg)

## 6\. Set Up a Connection to Google's DNS Servers

 The “server stumbled” error message highlights that the error could be linked to your PC’s DNS (Domain Name System) server. So, changing to a more reliable public server like Google DNS is a potential resolution that could feasibly work for some users.

 It is indeed the case some users have confirmed setting a Google DNS fixed this error on their PCs. To do that, check out our article about [how to change a DNS server](https://www.makeuseof.com/windows-11-alternate-ways-change-dns-server-settings/) , which also includes Google’s IPv4 addresses.

![DNS settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/dns-settings.jpg)

## 7\. Disable Any Active Third-Party Security Software

 Third-party security software packages that incorporate antivirus shields and firewalls can interfere with MS Store’s network connection. The firewall components of security apps will more likely do so since they monitor inbound and outbound network traffic. So, try temporarily disabling a firewall within any third-party security installed on your PC before opening MS Store.

 However, don’t rule out the possibility that an antivirus component of an installed third-party security app could also be causing the “server stumbled” error. You can usually disable an antivirus shield by right-clicking the security software’s system tray icon and selecting a turnoff option.

 Should this troubleshooting method work, you don’t necessarily need to leave your security software disabled or uninstall it. Instead, add MS Store to the firewall’s allowed app list within your antivirus software. In addition, add that app to the antivirus component’s whitelist.

## 8\. Enable TLS

 If you’re seeing a “server stumbled” error with 80072EFD or 80072EFF codes, you might need to enable some TLS (Transport Layer Security) protocol settings to resolve the issue. Enable TLS with the following steps:

1. Activate Run by pressing**Win + R** .
2. Type**inetcpl.cpl** (for Internet Options) inside Run and select OK.
3. Click**Advanced** to view that tab’s options.
4. Select the Use**TLS 1.0** ,**1.1** ,**1.2** , and**1.3** checkboxes there.  
![The TLS checkboxes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/tls-settings.jpg)
5. Press**Apply** in the Internet Properties window.
6. Click**OK** to exit Internet Properties.

## 9\. Reregister the Microsoft Store

 Reregistering Microsoft Store will reset that app to its factory defaults. That’s a troubleshooting method worth trying if nothing else resolves the “server stumbled” error. You can apply this potential fix by executing a PowerShell command that generally reregisters pre-installed Windows apps.

 Our article about [reregistering Microsoft Store apps on Windows](https://www.makeuseof.com/reregister-microsoft-store-apps-windows/) includes step-by-step instructions for executing that command.

![The reregister command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reregister-command.jpg)

## Download and Install Apps From the Microsoft Store Again

 Many users have stopped the “server stumbled” error crashing MS Store by applying the potential fixes outlined above. So, there’s a strong likelihood that one of those resolutions will get that issue sorted on your Windows 11/10 PC. Then you can get back to downloading and installing apps from Microsoft Store.

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
<li><a href="https://win11-tips.techidaily.com/terminals-in-win11-undo-changes-and-start-new/"><u>Terminals in Win11: Undo Changes & Start New</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-access-control-the-powertoys-way/"><u>Mastering Access Control: The PowerToys Way</u></a></li>
<li><a href="https://games-able.techidaily.com/1719162480304-the-most-reliable-ios-gaming-tools-ranked-find-out-now/"><u>The Most Reliable iOS Gaming Tools Ranked: Find Out Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/joining-forces-onedrive-and-windows-live-account-sync/"><u>Joining Forces: OneDrive & Windows Live Account Sync</u></a></li>
<li><a href="https://win11.techidaily.com/breathe-life-into-vanished-panes-top-strategies-to-recover-off-screen-apps-on-win-10/"><u>Breathe Life Into Vanished Panes! Top Strategies to Recover Off-Screen Apps on Win 10</u></a></li>
<li><a href="https://fox-access.techidaily.com/exploring-the-expense-of-youtube-channel-growth/"><u>Exploring the Expense of YouTube Channel Growth</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-11-free-apps-to-check-imei-on-vivo-v27e-phones-by-drfone-android/"><u>Top 11 Free Apps to Check IMEI on Vivo V27e Phones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-directory-management-without-renaming-features-in-windows-11/"><u>Mastering Directory Management without Renaming Features in Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-9-best-phone-monitoring-apps-for-huawei-nova-y91-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Best Phone Monitoring Apps for Huawei Nova Y91 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/virtualbox-v70-upgrade-guide-win11-edition-walkthrough/"><u>VirtualBox v7.0 Upgrade Guide – Win11 Edition Walkthrough</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-remedies-for-non-functional-windows-alt-codes-49-characters/"><u>Quick Remedies for Non-Functional Windows Alt Codes (49 Characters)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-game-pass-access-restoration-in-win-oses/"><u>Mastering Game Pass Access Restoration in Win OSes</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-complete-guide-for-iphone-15-pro-max-lock-screen-drfone-by-drfone-ios/"><u>In 2024, Complete Guide For iPhone 15 Pro Max Lock Screen | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-absent-d3dx939dll-on-windows-11/"><u>Remedying Absent D3DX9_39.dll on Windows 11</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-simplify-video-editing-on-mac-mkvtoolnix-review-for-2024/"><u>Updated Simplify Video Editing on Mac MKVtoolnix Review for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-solution-to-error-code-0x80070570-rescuing-damaged-files-on-windows-11/"><u>Unlocking Solution to Error Code 0X80070570: Rescuing Damaged Files on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-functionality-to-disabled-volume-snapshots/"><u>Restoring Functionality to Disabled Volume Snapshots</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-functionality-to-amd-gpu-software-on-pcs/"><u>Restoring Functionality to AMD GPU Software on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-normalcy-show-startups-on-task-manager/"><u>Restoring Normalcy: Show Startups on Task Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-unraveling-breakpoint-failed-in-windows-devices/"><u>Tips for Unraveling Breakpoint Failed in Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switching-file-extensions-windows-guide/"><u>Switching File Extensions: Windows Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/using-terminal-to-enter-quake-interface/"><u>Using Terminal to Enter Quake Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-memory-diagnostic-failure-on-your-pc/"><u>Addressing 'Memory Diagnostic Failure' On Your PC</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-facebook-cover-video-best-practices-and-setup/"><u>2024 Approved  Facebook Cover Video | Best Practices and Setup</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-ultimate-guide-top-free-youtube-video-openers/"><u>[Updated] Ultimate Guide  Top Free YouTube Video Openers</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-nubia-red-magic-9-pro-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Nubia Red Magic 9 Pro phone? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-restart-printers-automatic-service-in-win/"><u>Methods to Restart Printer's Automatic Service in Win</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-diving-deep-into-the-world-of-professional-voice-overs-for-videos/"><u>[New] 2024 Approved  Diving Deep Into the World of Professional Voice Overs for Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/synchronizing-camera-use-among-windows-programs/"><u>Synchronizing Camera Use Among Windows Programs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/onedrive-repositioning-in-the-windows-11-environment/"><u>OneDrive Repositioning in the Windows 11 Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-updater-failures-0xca00a009/"><u>Mastering the Art of Fixing Updater Failures #0xCA00A009</u></a></li>
<li><a href="https://android-unlock.techidaily.com/5-solutions-for-motorola-moto-g-5g-2023-unlock-without-password-by-drfone-android/"><u>5 Solutions For Motorola Moto G 5G (2023) Unlock Without Password</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-disk-designations-c-and-d-varieties/"><u>Navigating Disk Designations: C and D Varieties</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-network-throughput-measurement/"><u>Advanced Network Throughput Measurement</u></a></li>
<li><a href="https://screen-recording.techidaily.com/top-10-no-cost-gaming-recording-apps-for-gamers-for-2024/"><u>Top 10 No-Cost Gaming Recording Apps for Gamers for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-step-by-step-process-to-make-professional-discord-photos/"><u>[Updated] 2024 Approved  Step-By-Step Process to Make Professional Discord Photos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-windows-isdonedll-complications-quickly/"><u>Solving Windows ISDone.dll Complications Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-lock-personal-pattern-creation-tutorial/"><u>Mastering Window's Lock: Personal Pattern Creation Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-system-restore-a-guide-to-rollbacks/"><u>Mastering Windows' System Restore: A Guide to Rollbacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-non-responsive-services-on-windows-pcs/"><u>Steps to Rectify Non-Responsive Services on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/multiplying-malware-defenses-think-again-windows/"><u>Multiplying Malware Defenses? Think Again, Windows!</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-how-to-add-3d-effects-to-video-in-windows-10-and-windows-11/"><u>Updated 2024 Approved How to Add 3D Effects to Video in Windows 10 and Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launch-in-pc-no-fee-clone-of-chatgpt-on-windows/"><u>Launch In-PC, No-Fee Clone of ChatGPT on Windows.</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-the-top-methods-for-remotely-podcasting-success/"><u>[New] In 2024, The Top Methods for Remotely Podcasting Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-windows-upgrade-error-xc004f050-code/"><u>Unblocking Windows Upgrade Error Xc004f050 Code</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-elevating-your-instagram-presence-with-watermarks/"><u>[Updated] In 2024, Elevating Your Instagram Presence with Watermarks</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-20-viral-tiktok-anime-ideas/"><u>[New] 2024 Approved  20 Viral Tiktok Anime Ideas</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-elitemac-perfect-blend-of-screen-and-audio-capturing-features/"><u>[Updated] In 2024, EliteMac  Perfect Blend of Screen and Audio Capturing Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-resolving-microsoft-store-error-on-windows-devices/"><u>Tips for Resolving Microsoft Store Error on Windows Devices</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-unlock-your-device-icloud-dns-bypass-explained-and-tested-plus-easy-alternatives-on-iphone-6s-plus-by-drfone-ios/"><u>In 2024, Unlock Your Device iCloud DNS Bypass Explained and Tested, Plus Easy Alternatives On iPhone 6s Plus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-correcting-ipad-picture-importer-mishaps-in-windows/"><u>Quick Guide: Correcting iPad Picture Importer Mishaps in Windows</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-unlocking-adsense-potential-in-youtube-content-creation/"><u>[New] In 2024, Unlocking AdSense Potential in YouTube Content Creation</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-why-does-facebook-suggested-videos-not-showing-up-for-2024/"><u>[Updated] Why Does Facebook Suggested Videos Not Showing Up for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-unveiled-major-updates-on-windows-11-vs-10/"><u>Windows Unveiled: Major Updates on Windows 11 Vs. 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amend-non-working-shortcuts-solve-f-keys-issue-on-windows-11/"><u>Amend: Non-Working Shortcuts - Solve F Keys Issue on Windows 11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-invest-in-insta-success-the-top-earners-playbook/"><u>In 2024, Invest in Insta Success  The Top Earners' Playbook</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-additional-tips-about-sinnoh-stone-for-nokia-c32-drfone-by-drfone-virtual-android/"><u>In 2024, Additional Tips About Sinnoh Stone For Nokia C32 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-copy-pasting-predefined-text-with-windows-11-hotkeys/"><u>Streamline Copy-Pasting Predefined Text with Windows 11 Hotkeys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-11s-geforce-now-error-xc0f1103f/"><u>Tackling Windows 11'S GeForce Now Error Xc0f1103f</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-android-and-ios-leading-titles-mimicking-playstation-games/"><u>[Updated] In 2024, Android & iOS  Leading Titles Mimicking PlayStation Games</u></a></li>
<li><a href="https://animation-videos.techidaily.com/2024-approved-ways-to-create-an-adobe-collage/"><u>2024 Approved Ways to Create an Adobe Collage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-non-start-troubles-in-csgo-and-w11/"><u>Tackling Non-Start Troubles in CS:GO & W11</u></a></li>
</ul></div>
