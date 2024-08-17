---
title: Realigning Defective Battery Life Meter on Windows 11 Machines
date: 2024-08-16T02:33:44.521Z
updated: 2024-08-17T02:33:44.521Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Realigning Defective Battery Life Meter on Windows 11 Machines
excerpt: This Article Describes Realigning Defective Battery Life Meter on Windows 11 Machines
keywords: Battery Lifemeter Windows 11 Fix,Realign Battery Meter Issue,Enhance Defective W11 Battery,Correct Battery Metric Errors,Resolve Power Meter Malfunction,Optimize W11 Battery Health,Improve Battery Life Detection
thumbnail: https://thmb.techidaily.com/517296fb76b2495d3ca7ac9af3e02d36cfd22dc3a1d76f74a4f77913c7df7881.jpg
---

## Realigning Defective Battery Life Meter on Windows 11 Machines

 Keeping track of how much charge remains in your laptop battery is easy. By default, hovering over the battery icon in the System Tray displays an estimate of battery time remaining, along with a percentage. Occasionally, the time estimate goes missing, leaving you to work out how much usage time you have left by percentage alone.

 Here's how to get that useful battery time remaining estimate showing again if it has vanished from your notebook.

## Where Did the Time Estimate Go?

 There are a few possible reasons why the time estimate has disappeared. The change often happens after upgrading to Windows 11, but even simply updating the OS can cause it. A later update may fix the issue, but that isn't always the case.

![battery icon tooltip in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/battery-time.jpg)

 It isn't entirely obvious what the root cause is. It could be a conflict in the Registry, which can occur during the update process. It also seems to have been deliberately disabled by Microsoft in some updates. Perhaps because the company is working on power and battery settings for a future update.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Enable the Battery Time Estimate in the Registry

 Whatever the cause of its disappearance, the battery time estimate is still part of the OS. And with a bit of Registry tweaking, it can be brought back into view.

 As always, it is a good idea to[back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you make any changes. This is only a minor edit and shouldn't cause problems, but it's better to be safe than sorry.

1. Click Windows Search and type**Regedit** to find the Registry Editor. You don't need to choose Run as Administrator. Just select the search result.
2. With the Registry Editor open, navigate to: **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Power** .
3. If there is no**Power** key, right-click on**Control** in the navigation panel, and select**New > Key** . Name the new registry key**Power** .  
![power values in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-key.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
4. Right-click the Power key and select**New > DWORD (32-bit) Value** . Set the name of this DWORD as**EnergyEstimationEnabled** .
5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .
7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out[how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
## Fix a Missing Battery Time Estimate on Windows

 Not being able to easily see the estimate of battery time remaining probably isn't going to keep you up at night. But it is a handy feature if using your laptop away from a power source. Luckily, a few minutes spent editing the Registry will fix the problem, so you always know how long it will be before your battery dies.


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
<li><a href="https://driver-install.techidaily.com/fixed-conexant-hd-audio-on-the-latest-windows-version/"><u>[Fixed] Conexant HD Audio on the Latest Windows Version</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-propagate-your-content-with-vimeo-links/"><u>[New] 2024 Approved  Propagate Your Content with Vimeo Links</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-fb-media-migration-tools-for-windowsmacos-users-for-2024/"><u>[New] FB Media Migration Tools for Windows/macOS Users for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-how-to-fix-live-video-interrupted-on-facebook-in-2024/"><u>[New] How to Fix Live Video Interrupted on Facebook, In 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-screencast-excellence-the-ultimate-guide-to-best-obs-tools/"><u>[New] In 2024, Screencast Excellence  The Ultimate Guide to Best OBS Tools</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-junior-jams-and-junction-gaming/"><u>[New] Junior Jams & Junction Gaming</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-lullabies-for-your-mind-no-stress-pcs/"><u>[New] Lullabies for Your Mind  No-Stress PCs</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-stream-to-file-conversion-effortless-archive-creation/"><u>[New] Stream-to-File Conversion  Effortless Archive Creation</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-unlocking-tiktoks-potential-changing-your-profile-number/"><u>[New] Unlocking TikTok's Potential  Changing Your Profile Number</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-become-a-meme-wizard-with-these-9gag-strategies/"><u>[Updated] 2024 Approved  Become a Meme Wizard with These 9GAG Strategies</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-ensuring-total-sound-from-partially-muted-fb-media/"><u>[Updated] Ensuring Total Sound From Partially Muted FB Media</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-expert-tips-for-capturing-and-saving-igtv-on-handhrani/"><u>[Updated] In 2024, Expert Tips for Capturing and Saving IGTV on Handhrani</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-vpna-fake-gps-location-free-review-on-nubia-red-magic-8s-proplus-drfone-by-drfone-virtual-android/"><u>A Detailed VPNa Fake GPS Location Free Review On Nubia Red Magic 8S Pro+ | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-flawless-display-with-win11-settings/"><u>Achieve Flawless Display with Win11 Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-game-bar-errors-on-underpowered-systems/"><u>Addressing Game Bar Errors on Underpowered Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-local-user-policies-a-guide-to-windows-11-and-11-systems/"><u>Adjusting Local User Policies: A Guide to Windows 11 & 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-what-sets-ai-hardware-on-a-distinct-path/"><u>Analyzing What Sets AI Hardware on a Distinct Path</u></a></li>
<li><a href="https://win11-tips.techidaily.com/designing-personalized-secure-locks-for-windows-11/"><u>Designing Personalized Secure Locks for Windows 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/diy-cinematic-tips-fast-ways-to-improve-your-indie-projects/"><u>DIY Cinematic Tips  Fast Ways to Improve Your Indie Projects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-footage-excellence-with-these-best-apps-for-windows-11/"><u>Enhance Footage Excellence with These Best Apps for Windows 11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/high-res-webcam-videos-in-minutes-a-step-guide-for-2024/"><u>High-Res Webcam Videos in Minutes  A Step Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-control-file-explorer-display-options-windows-11/"><u>How to Control File Explorer Display Options (Windows 11)</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/how-to-convert-instagram-video-to-mp4-2-proven-ways-for-2024/"><u>How to Convert Instagram Video to MP4 [ 2 Proven Ways] for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-disabled-windows-application/"><u>How to Enable Disabled Windows Application</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-xbox-game-pass-0x00000001-error-in-windows-10-and-11/"><u>How to Fix the Xbox Game Pass 0X00000001 Error in Windows 10 & 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-deleted-photos-on-12-proplus-5g-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to Retrieve deleted photos on 12 Pro+ 5G</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-the-ultimate-guide-to-youtube-channel-removal-pcphone/"><u>In 2024, The Ultimate Guide to Youtube Channel Removal (PC/Phone)</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/locating-archived-reels-on-instagram-essential-tips-and-tricks/"><u>Locating Archived Reels On Instagram: Essential Tips and Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-winerror-0xc0000005/"><u>Mastering the Art of Fixing WinError 0Xc0000005</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-with-style-installation-and-usage-of-ms-store-themes/"><u>Navigate With Style: Installation and Usage of MS Store Themes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-launchers-security-failures-on-windows-systems/"><u>Navigating Launcher's Security Failures on Windows Systems</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-public-domain-videos-at-your-fingertips-best-download-sites-for-2024/"><u>New Public Domain Videos at Your Fingertips Best Download Sites for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pro-level-windows-photos-shortcut-guide/"><u>Pro-Level Windows Photos Shortcut Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-faded-screen-settings-in-uefi/"><u>Restoring Faded Screen Settings in UEFI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-reverse-winerror-exit-point-failure/"><u>Steps to Reverse WinError Exit Point Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-error-1053-unresponsive-service-issue/"><u>Tackling Windows Error 1053: Unresponsive Service Issue</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-filmmakers-toolkit-essential-color-grading-of-7-techniques/"><u>The Filmmaker's Toolkit  Essential Color Grading of 7 Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ultimate-list-of-windows-note-taking-aids/"><u>Ultimate List of Windows Note-Taking Aids</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-solving-obs-errors-windows-edition/"><u>Understanding and Solving OBS Errors: Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-power-management-features-for-maximum-efficiency/"><u>Unlocking Power Management Features for Maximum Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-yourphoneexe-phone-link-in-windows-1110-should-you-disable-it/"><u>What Is YourPhone.exe (Phone Link) in Windows 11/10? Should You Disable It?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-notepad-blockade-uncover-the-7-pathways-to-access-it-again/"><u>Windows Notepad Blockade: Uncover the 7 Pathways to Access It Again</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-editorial-techniques-select-from-the-top-8-video-trimming-titles/"><u>Winning Editorial Techniques: Select From The Top 8 Video Trimming Titles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-strategies-for-efficient-wsl-2-on-windows/"><u>Winning Strategies for Efficient WSL 2 on Windows</u></a></li>
</ul></div>
