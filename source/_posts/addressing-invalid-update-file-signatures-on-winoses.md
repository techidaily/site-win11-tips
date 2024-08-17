---
title: Addressing Invalid Update File Signatures on WinOSes
date: 2024-08-16T01:20:37.122Z
updated: 2024-08-17T01:20:37.122Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Invalid Update File Signatures on WinOSes
excerpt: This Article Describes Addressing Invalid Update File Signatures on WinOSes
keywords: Windows Validation Errors,OS Updates Signature Fix,WinOS Invalid Files,Update Corruption Solutions,Signature Verification Win,File Integrity WinOS,Erroneous Signatures Address
thumbnail: https://thmb.techidaily.com/75030bd59360efbfc2946329061573b90f37300b7251c4b711e0f5f10f28322c.jpg
---

## Addressing Invalid Update File Signatures on WinOSes

 Users frequently report Windows 11/10 update errors on software support forums. One such update issue reported is an error message that says, “Some update files aren’t signed.” Some users see that error message appear within Settings’ Windows Update tab when trying to update Windows.

 Windows updates fail to install when this issue occurs. This error usually includes either a 0x800b0109 or 0x800b0100 code after its message. This is how you can resolve the “Some update files aren’t signed” error 0x800b0109 on a Windows 11/10 PC.

## 1\. Utilize the Windows Update Troubleshooter

 The Windows Update troubleshooting tool is there to help you fix any issues encountered when trying to update Windows 11/10\. That troubleshooter doesn’t necessarily fix every update error, but it can at least resolve some issues.

 So, utilizing that troubleshooter is always worth a try, which you can access in Settings as covered within this guide to [running any troubleshooter on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/).

![The Windows Update troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-update-troubleshooter.jpg)

## 2\. Run Deployment Imaging and System File Scans

 System file corruption is among the [most common reasons for Windows update errors](https://www.makeuseof.com/reasons-why-windows-updates-fail/). For that reason, running a System File Checker scan to address system file corruption is a recommended troubleshooting method for error 0x800b0109\.

 It’s also advisable to utilize the Deployment Imaging and Servicing Management to repair possible Windows image corruption.

 Both Deployment Imaging and System File Checker are Command Prompt tools. You can run them by inputting and executing two commands within the Command Prompt. Our article on [repairing corrupted Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) includes instructions on how to utilize the SFC and DISM command-line tools.

![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-sfc-scannow.jpg)

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Check the Windows Update and BITS Services Are Enabled

 Windows Updates and Background Intelligent Transfer Service (BITS) are two services that need to be enabled for updates. So, check those services are correctly set like this:

1. Simultaneously press the **Windows** logo + **S** keys on your keyboard.
2. Enter the search phrase "services" to find the app with a matching title.
3. Click on **Services** inside the search results.
4. Double-click **Windows Update** to access settings for that service.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/services-window.jpg)
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Set the **Startup type** setting to the **Automatic** option.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/startup-type-drop-down-menu.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
6. Click **Start** (inside the properties windows) to run the Windows Update service.
7. Save the settings by pressing the **Apply** and **OK** buttons.
8. Double-click the **Background Intelligent Transfer Service** to view its settings.
9. Select a **Manual** startup option.
10. Click the **Start** option for the BITS service if it’s stopped.
11. Then click on the **Apply** and **OK** options to set that service’s options.

 If you find both services to be already enabled and running, try restarting them. You can do so by right-clicking the BITS and Windows Update service names and selecting a **Restart** option on their context menus.

## 4\. Reset Components for Windows Updates

 Resetting components for Windows updates will completely refresh the catroot2 and SoftwareDistribution folders, which store update data. This troubleshooting method also reregisters all DLL files for important update services. Applying such a potential resolution can fix corrupted components causing error 0x800b0109\.

 To apply this possible error 0x800b0109 resolution, check out our article on [resetting Windows update components](https://www.makeuseof.com/reset-windows-update-components/). That guide includes a command-line and batch file method. Creating and running a batch file is the quicker and more straightforward way to reset Windows update components.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Deactivate Third-Party Security Software

 A third-party security (antivirus) app can potentially conflict with Windows update processes. This can happen when the antivirus protection of a security app locks files needed by Windows Update. It’s not something that happens often, but temporarily disable any third-party antivirus protection on your PC just in case.

 Security apps typically include options for disabling antivirus protection on their system tray context menus. Right-click your security app’s icon in Windows 11’s system tray area to find and select its option for temporarily disabling the antivirus shield. Then, return to the Settings app to see if error 0x800b0109 still happens with the antivirus shield disabled.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

## 6\. Erase the Windows Update Key

 Deleting the Windows Update registry key is a potential resolution some users confirm to fix error 0x800b0109\. However, we always recommend [backing up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or saving a system restoration point before deleting registry keys.

 When you’ve done that, try deleting the Windows Update key like this:

1. Open Run, accessible by pressing **Windows** logo key + **R**, and type a **regedit** command into that accessory.
2. Select Run’s **OK** option to open the Registry Editor.
3. Next, clear the registry address bar and input this key path there:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\WindowsUpdate`
4. Right-click the WindowsUpdate registry key to select **Delete**.  
![The Delete context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-delete-option-1.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
5. Click **Yes** when prompted for confirmation to delete the key.  
![The Confirm Key Delete prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-key-confirmation-1.jpg)

 Thereafter, it’s also recommended to restart the Windows Update and BITS services. To do so, open Services as covered in the first three steps of resolution three. Then, select the **Restart** context menu options for Windows Update and BITS.

## 7\. Try Downloading the Failed Update From Microsoft Update Catalog

 If error 0x800b0109 still isn’t fixed after applying the potential resolutions above, try going around it by manually downloading the affected update from [Microsoft Update Catalog](https://www.catalog.update.microsoft.com/Home.aspx). Then, you can install the update with an MSU file downloaded from there.

 You will first need to identify what update is failing as follows:

1. Simultaneously press your keyboard’s **Windows** logo + **I** keys to access Settings.
2. Click **Windows Update** (or **Update & Security**) in Settings.
3. Select **Update history** to view installed and failed updates.  
![The update history in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-history4.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
4. Note down the KB code for your recently failed Windows update.

 Then, you can find and download that failed update on the Microsoft Update Catalog website. This article about [updating Windows manually](https://www.makeuseof.com/update-windows-manually/) includes instructions for utilizing the Microsoft Update Catalog.

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 8\. Apply an In-Place Windows Upgrade

 An in-place Windows upgrade is the last resort for fixing error 0x800b0109\. Applying this potential resolution will reinstall Windows on your PC with its latest ISO file. The installation of a fresh Windows copy will likely resolve other issues causing the 0x800b0109 update error that other potential solutions couldn’t fix.

 The good thing about an in-place upgrade is that it won’t eradicate your installed software or user files. This [how-to perform an in-place upgrade](https://www.makeuseof.com/in-place-upgrade-windows-11/) guide tells you how to apply this potential solution for Windows 11\. The steps are quite similar for Windows 10, but you’ll need to download its ISO with the Media Creation Tool available on this [Microsoft page](https://www.microsoft.com/en-gb/software-download/windows10).

![The Windows 10 Media Creation tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-10-setup-window.jpg)
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Windows Updated Again

 There isn’t a surefire way to fix error 0x800b0109 since there are varied possible reasons for that Windows 11/10 issue occurring. However, it’s likely at least one of the eight potential resolutions in this guide will fix that update issue on your PC.

 Some of the best third-party Windows repair tools might also be helpful for resolving the “Some update files aren’t signed” error.

 Windows updates fail to install when this issue occurs. This error usually includes either a 0x800b0109 or 0x800b0100 code after its message. This is how you can resolve the “Some update files aren’t signed” error 0x800b0109 on a Windows 11/10 PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-capture-and-relive-your-favorite-moments-anywhere-anytime-the-best-in-free-video-downloaders-for-youtubes/"><u>[New] 2024 Approved  Capture and Relive Your Favorite Moments Anywhere, Anytime  The Best in Free Video Downloaders for YouTubes</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-capture-your-best-moments-top-8-mirrorless-cameras-for-you-for-2024/"><u>[New] Capture Your Best Moments  Top 8 Mirrorless Cameras For You for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-effective-methods-for-capturing-youtube-live-broadcasts/"><u>[New] Effective Methods for Capturing YouTube Live Broadcasts</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-how-to-create-and-merge-stunning-hdr-images-in-lightroom-for-2024/"><u>[New] How to Create and Merge Stunning HDR Images in Lightroom for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-select-selections-ideal-spots-to-download-snapalert-melodies/"><u>[New] Select Selections  Ideal Spots to Download SnapAlert Melodies</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-big-sur-essentials-system-and-hardware-upgrade/"><u>[Updated] Big Sur Essentials  System and Hardware Upgrade</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-crafting-powerful-narratives-with-these-30-video-plans/"><u>[Updated] Crafting Powerful Narratives with These 30 Video Plans</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-instagrams-silent-frames-no-more-a-sound-fix/"><u>[Updated] In 2024, Instagram's Silent Frames No More – A Sound Fix</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-reimagine-your-storytelling-with-smartly-scaled-instagram-videos/"><u>[Updated] Reimagine Your Storytelling with Smartly Scaled Instagram Videos</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-best-video-changer-tools-reviewed-8-of-the-best-for-iphones-and-pcs/"><u>2024 Approved  Best Video Changer Tools Reviewed  8 of the Best for iPhones and PCs</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-new-wonders-of-windows-11/"><u>2024 Approved  New Wonders of Windows 11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-prime-android-space-savers-compendium/"><u>2024 Approved  Prime Android Space-Savers Compendium</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-swiftstrike-timetape-recording/"><u>2024 Approved  SwiftStrike TimeTape Recording</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-understanding-macos-11-big-sur-transition-tips/"><u>2024 Approved  Understanding macOS 11 Big Sur Transition Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-windows-component-services-interface-quickly/"><u>Accessing Windows' Component Services Interface Quickly</u></a></li>
<li><a href="https://extra-information.techidaily.com/add-fade-inout-premiere-pro-for-2024/"><u>Add Fade In/Out Premiere Pro for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-items-to-windows-11-desktop-menu-hierarchy/"><u>Adding Items to Windows 11 Desktop Menu Hierarchy</u></a></li>
<li><a href="https://extra-information.techidaily.com/click-magic-secrets-to-stunning-polished-pics-for-2024/"><u>Click Magic  Secrets to Stunning, Polished Pics for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-the-most-effective-win-video-codecs/"><u>Demystifying the Most Effective Win Video Codecs</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/effortlessly-converse-top-17-casual-spanish-utterances/"><u>Effortlessly Converse: Top 17 Casual Spanish Utterances</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/epic-virtual-realms-finest-10-budget-friendly-mmorpgs-for-2024/"><u>Epic Virtual Realms  Finest 10 Budget-Friendly MMORPGs for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/essential-six-digital-communication-hubs-for-corporate-success/"><u>Essential Six Digital Communication Hubs for Corporate Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-different-ways-to-tailor-windows-11-search/"><u>Explore Different Ways to Tailor Windows 11 Search</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/fix-cannot-paste-the-data-error-in-microsoft-excel-2007-stellar-by-stellar-guide/"><u>Fix Cannot Paste the Data Error in Microsoft Excel 2007 | Stellar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-your-system-ready-for-windows-11-with-our-top-3-usb-tips/"><u>Get Your System Ready for Windows 11 with Our Top 3 USB Tips</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-apple-iphone-6s-plus-data-from-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Apple iPhone 6s Plus Data From iCloud? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-start-wordpad-in-a-windows-desktop/"><u>How to Start WordPad in a Windows Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-streamline-note-taking-with-win-11-display-rules/"><u>How to Streamline Note-Taking with Win 11 Display Rules</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-12-mini-to-other-iphone-11-pro-max-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 12 mini To Other iPhone 11 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-uncover-and-attend-to-hidden-storage/"><u>How to Uncover and Attend to Hidden Storage?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/icon-position-correction-made-simple/"><u>Icon Position Correction Made Simple</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-comparison-dissecting-key-differences-between-local-and-microsoft-logins-in-os/"><u>In-Depth Comparison: Dissecting Key Differences Between Local & Microsoft Logins in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instructions-to-bring-back-old-school-search-in-windows-11/"><u>Instructions to Bring Back Old-School Search in Windows 11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/latest-guide-on-ipad-23-and-iphone-15-pro-max-icloud-activation-lock-bypass-by-drfone-ios/"><u>Latest Guide on iPad 2/3 and iPhone 15 Pro Max iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/making-your-mark-strategies-for-monthly-growth-on-instagram/"><u>Making Your Mark  Strategies for Monthly Growth on Instagram</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-immediate-folder-upload-tackling-onedrive-errors/"><u>Mastering Immediate Folder Upload: Tackling OneDrive Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-reactivate-the-default-folder-cooking-a-comprehensive-guide/"><u>Methods to Reactivate the Default Folder' Cooking: A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mobile-file-access-via-windows-server/"><u>Mobile File Access via Windows Server</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-future-microsofts-copilot-key-and-windows-11-revolution/"><u>Navigating the Future: Microsoft's Copilot Key and Windows 11 Revolution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-device-disconnection-dxgi-error-guide/"><u>Overcoming Device Disconnection: DXGI Error Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-vmware-crashes-a-guide-for-win11-users/"><u>Overcoming VMware Crashes: A Guide for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-order-in-windows-registry-through-repair-methods/"><u>Restoring Order in Windows Registry Through Repair Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-strategies-windows-voice-logging/"><u>Step-by-Step Strategies: Windows Voice Logging</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-eradicate-wows-fatal-issue-132-in-win-1011/"><u>Strategies to Eradicate WoW's Fatal Issue #132 in Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-multitasking-enhancing-windows-11-widget-capabilities/"><u>Streamlining Multitasking: Enhancing Windows 11 Widget Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-app-experience-win11-color-automation/"><u>Tailoring Your App Experience: Win11 Color Automation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-prolong-pin-length-for-enhanced-safety/"><u>Tips to Prolong PIN Length for Enhanced Safety</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-the-power-of-sandbox-with-win-11/"><u>Unleashing the Power of Sandbox with Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-ip-and-mac-info-with-windows-powershell/"><u>Unraveling IP and MAC Info with Windows Powershell</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-stronger-side-why-you-should-opt-for-win11/"><u>Unveiling the Stronger Side: Why You Should Opt for Win11</u></a></li>
<li><a href="https://fox-links.techidaily.com/variants-of-windows-movie-maker-a-comprehensive-list-for-2024/"><u>Variants of Windows Movie Maker  A Comprehensive List for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/w11-addressing-undetected-additional-monitor/"><u>W11: Addressing Undetected Additional Monitor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-compatibility-tips-synapse-reinstatement-guide/"><u>Win Compatibility Tips: Synapse Reinstatement Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-against-roblox-needs-to-close-windows-errors/"><u>Winning Against Roblox Needs to Close Windows Errors</u></a></li>
</ul></div>
