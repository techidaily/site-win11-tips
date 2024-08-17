---
title: "Revival Tactics: Restoring Microsoft Store on Win 11 & 11"
date: 2024-08-16T02:43:43.331Z
updated: 2024-08-17T02:43:43.331Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Revival Tactics: Restoring Microsoft Store on Win 11 & 11"
excerpt: "This Article Describes Revival Tactics: Restoring Microsoft Store on Win 11 & 11"
keywords: Win 11 MSStore,Revive MSStore,Win 11 Store Restore,Windows Store Redo,Win 11 Microsoft Store Update,Win 11 Reinstate MSStore,Win 11 Restore Store
thumbnail: https://thmb.techidaily.com/36b23ef4c54f4e12997c9a2584ed2c68d00394366c249b53e078e95dee6e414c.jpg
---

## Revival Tactics: Restoring Microsoft Store on Win 11 & 11

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

 If the[Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

To re-register Microsoft Store apps for the current user:

1. Press the**Win** key and type "powershell" into the Search bar.
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell console, type the following command and press**Enter** :  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
4. Wait for the command to execute and complete. You may see a blue loading graphic.
5. Once done, type**exit** and press**Enter** to close PowerShell.

 During the process, you may see some errors highlighted in red. It is due to PowerShell trying to reinstall existing apps on Windows. So, ignore the error and wait for the process to complete.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
## Install and Re-Register All Microsoft Store Apps on Windows 11

 Re-registering Windows apps is often necessary when Microsoft Store is not working. It can also help deal with other Windows settings and apps. If the issue persists, try the built-in Windows Store Apps troubleshooter to fix common Microsoft Store app issues.


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
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-discovering-costless-software-for-streaming-sessions/"><u>[New] 2024 Approved  Discovering Costless Software for Streaming Sessions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-essential-tactics-for-control-panel-entry/"><u>10 Essential Tactics for Control Panel Entry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/13-tips-to-fix-windows-system-restore/"><u>13 Tips to Fix Windows System Restore</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-quick-ways-to-disable-usb-selective-suspend-in-windows-11/"><u>3 Quick Ways to Disable USB Selective Suspend in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-clear-the-microsoft-defender-protection-history-on-windows-10-and-11/"><u>4 Ways to Clear the Microsoft Defender Protection History on Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-alternative-protection-strategies-for-missing-bitlocker-in-winoss/"><u>5 Alternative Protection Strategies for Missing Bitlocker in WinOSs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-fix-the-checksum-error-in-winrar/"><u>6 Ways to Fix the Checksum Error in WinRAR</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-easy-tips-for-memo-making-in-windows/"><u>7 Easy Tips for Memo-Making in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-routes-to-rescue-your-stream-with-a-fixed-obs-link-on-windows/"><u>7 Routes to Rescue Your Stream with a Fixed OBS Link on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-slick-techniques-to-launch-iis-manager/"><u>8 Slick Techniques to Launch IIS Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-compre-cookie-cutter-guide-to-revamping-your-pc-with-a-fresh-os/"><u>A Compre Cookie-Cutter Guide to Revamping Your PC with a Fresh OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-tutorial-on-windows-1011s-audio-upgrade/"><u>A Comprehensive Tutorial on Windows 10/11'S Audio Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-precise-walkthrough-for-windows-update-resetting/"><u>A Precise Walkthrough for Windows Update Resetting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-secrets-the-fastest-ways-to-uncover-windows-11s-credential-manager/"><u>Accessing Secrets: The Fastest Ways to Uncover Windows 11'S Credential Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-digital-dreamland-with-windows-pcs/"><u>Achieving Digital Dreamland with Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-windows-11-and-parallels-confluence-in-macos/"><u>Achieving Windows 11 and Parallels Confluence in MacOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-discrepancies-in-disk-based-discord-queries/"><u>Addressing Discrepancies in Disk-Based Discord Queries</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-issues-with-googles-nearby-sharing-on-desktop-pc/"><u>Addressing Issues with Google's Nearby Sharing on Desktop PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-operative-brightness-fn-button-on-windows-11/"><u>Addressing Non-Operative Brightness Fn Button on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-winrars-summation-anomalies-with-six-fixes/"><u>Addressing WinRAR's Summation Anomalies with Six Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-10-and-11s-phishing-protection-settings/"><u>Adjusting Windows 10 & 11'S Phishing Protection Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adopt-a-streamlined-approach-to-input-customization/"><u>Adopt a Streamlined Approach to Input Customization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-tips-for-docx-to-pdf-conversion-on-modern-windows/"><u>Advanced Tips for Docx-to-PDF Conversion on Modern Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-windows-tactics-for-hardware-id-retrieval/"><u>Advanced Windows Tactics for Hardware ID Retrieval</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-generated-windows-keys-unveiling-potential-perils/"><u>AI-Generated Windows Keys: Unveiling Potential Perils</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altwindirstat-strategies-for-effective-disk-space-management/"><u>AltWinDirStat Strategies for Effective Disk Space Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplified-audio-top-4-applications-to-surpass-windows-100-threshold/"><u>Amplified Audio: Top 4 Applications to Surpass Windows’ 100%% Threshold</u></a></li>
<li><a href="https://win11-tips.techidaily.com/artificial-intelligence-windows-future-trailblazer/"><u>Artificial Intelligence: Windows' Future Trailblazer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assisting-with-utorrent-download-stalls-in-microsoft-environments/"><u>Assisting with uTorrent Download Stalls in Microsoft Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/awaken-your-device-finding-and-fixing-muted-speaker-issues/"><u>Awaken Your Device – Finding & Fixing Muted Speaker Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-act-keeping-high-vitality-in-check-on-windows/"><u>Balancing Act: Keeping High Vitality in Check on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beating-the-bug-fixing-frequent-apex-legends-crashes-on-windows-11/"><u>Beating the Bug: Fixing Frequent Apex Legends Crashes on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-practices-unveiled-supercharge-wsl-2-with-windows-dev-tools/"><u>Best Practices Unveiled: Supercharge WSL 2 with Windows Dev Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beyond-boundaries-artificinas-intelligence-in-windows-11/"><u>Beyond Boundaries: Artificinas Intelligence in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blueprint-to-rule-winos-apps-browsers/"><u>Blueprint to Rule WinOS Apps, Browsers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blueprints-for-crafting-safe-dialog-box-for-hardware-disconnect/"><u>Blueprints for Crafting Safe Dialog Box for Hardware Disconnect</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719278811623-bypassing-chrome-block-strategies-for-w11-users/"><u>Bypassing Chrome Block: Strategies for W11 Users.</u></a></li>
<li><a href="https://extra-information.techidaily.com/expert-advice-fixing-iphone-lens-blur-effectively/"><u>Expert Advice  Fixing iPhone Lens Blur Effectively</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-broken-video-files-of-red-magic-9-pro-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair Broken video files of Red Magic 9 Pro on Windows??</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-a-guide-oneplus-open-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>In 2024, A Guide OnePlus Open Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-samsung-galaxy-xcover-7-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>In 2024, How to Unlock Samsung Galaxy XCover 7 Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-quick-guide-to-infusing-new-flair-in-old-content-using-instagram-features/"><u>In 2024, Quick Guide to Infusing New Flair in Old Content Using Instagram Features</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-streaming-stats-how-much-does-pewdiepie-earn/"><u>In 2024, Streaming Stats  How Much Does PewDiePie Earn?</u></a></li>
<li><a href="https://win-dash.techidaily.com/smooth-and-swift-samsung-c460-printer-driver-download-process/"><u>Smooth and Swift Samsung C460 Printer Driver Download Process</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/the-ultimate-unihertz-atom-xl-analysis-small-size-big-features/"><u>The Ultimate Unihertz Atom XL Analysis - Small Size, Big Features!</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/the-wanderlust-chronicles-setting-up-for-success-as-a-travel-vlogger-for-2024/"><u>The Wanderlust Chronicles  Setting Up for Success as a Travel Vlogger for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719266023156-zero-cost-local-gpt-clones-gpt4alls-window-solution/"><u>Zero-Cost Local GPT Clones: GPT4All's Window Solution.</u></a></li>
</ul></div>
