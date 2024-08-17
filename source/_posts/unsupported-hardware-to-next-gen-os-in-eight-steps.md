---
title: Unsupported Hardware to Next-Gen OS in Eight Steps
date: 2024-08-16T02:11:54.613Z
updated: 2024-08-17T02:11:54.613Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unsupported Hardware to Next-Gen OS in Eight Steps
excerpt: This Article Describes Unsupported Hardware to Next-Gen OS in Eight Steps
keywords: Upgrading Unsupported Devices,Next-Gen OS Transition Guide,Hardware Compatibility Upgrade,Step-by-Step OS Migration,Legacy PC OS Modernization,Evolving Old Hardware,OS Update for Outdated Tech
thumbnail: https://thmb.techidaily.com/d0ab1cb7b8b22999ef087a383ed3db769492e1f7dd341f7046ddf8ecb2ad394e.png
---

## Unsupported Hardware to Next-Gen OS in Eight Steps

 If you have installed Windows 11 on unsupported hardware, the upgrade process will be a tough task. When you try to look for an update, Windows 11 shows everything as up to date and has no option to install the 22H2 version.

 While you can use the ISO-based clean install method, the upgrade process lets you install the latest version without deleting your apps and other data. Here’s how to upgrade to Windows 11 22H2 on unsupported hardware using the Windows 11 setup file.

## How to Upgrade to Windows 11 22H2 on Unsupported Hardware

[Windows 11 runs a hardware compatibility check](https://www.makeuseof.com/check-computer-compatible-windows-11-22h2/) during the upgrade process. To perform a successful upgrade, you’ll need to work around this hardware compatibility assessment. To achieve this, we’ll replace the appraiserress.dll file in Windows 11 ISO with the appraiserress.dll from Windows 10 ISO.

 If you have Windows 11 22H2 and Windows 10 ISO available, skip to the third step below. If not, follow all the steps to download the necessary ISOs and then perform an upgrade.

 While these steps shouldn’t cause any issues, it is better to [create a backup of any important Windows 11 data](https://www.makeuseof.com/windows-11-create-complete-backup/) on your system drive just in case something goes wrong and you need to perform a clean install.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Download the Windows 11 22H2 ISO
![iso file download windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/iso-file-download-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->

 You can [legally download the Windows 11 ISO](https://www.makeuseof.com/windows-11-download-iso/) from the Microsoft server directly or using Media Creation Tool. For this guide, we’ll use Media Creation Tool to download the ISO image file.

1. Go to the [Microsoft Software Download page](https://www.microsoft.com/software-download/windows11) .
2. Click on**Download Now** under**Create Windows 11 Installation Media.**
3. Run the**mediacreationtool.exe** file and accept the license terms.
4. Review the selected language and edition. To change the language, uncheck**Use the recommended options for this PC** and select your preferred language.
5. Click**Next** .
6. Select the**ISO file** option in the**Choose which media to use** dialog.
7. Select the download location and click**Save** . Make sure the selected partition has enough space available.
8. Media Creation Tool will start downloading the ISO to your local drive. This process may take some time, depending on your Internet connection. So wait for the download to complete.
9. Once the download is complete, click**Finish** and follow the next step to download Windows 10 ISO.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Download a Windows 10 ISO
![windows 10 download ISO preference](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-10-download-iso-preference.jpg)
<!-- affiliate ads begin -->

<!-- affiliate ads end -->

 You’ll need to modify the Windows 11 ISO by replacing the appraiserress.dll with a version available in Windows 10 ISO. This DLL file is responsible for performing a hardware check during an upgrade.

To download Windows 10 ISO:

1. Go to [Windows 10 download page](https://www.microsoft.com/en-us/software-download/windows10) .
2. Click the**Download Now** button under**Create Windows 10 installation media** .
3. Run the**mediacreationtool.exe** file to open Windows 10 Setup dialog.
4. Click on**Accept** .
5. In the**What do you want to do** screen, select**Create installation media** and click**Next** .
6. Check if the language, edition, and architecture preferences are set correctly. If not, click on**Use the recommended options for this** **device** and set your preferences.
7. Next, select the**ISO file** option and click**Next** .
8. Select the download location and click**Save** .
9. The downloading process may take several minutes to complete. So wait for the process to complete and click**Finish** once done.

 Once you have both the ISO files saved, follow the next step to extract and modify the Windows 11 ISO.

## 3\. Modify the Windows 11 ISO to Bypass Hardware Check During the Upgrade

 The following steps involve extracting the Windows 10 ISO and copying the appraiserress.dll file. Next, move the copied DLL file to the Windows 11 ISO’s sources folder. Here’s how to do it.

1. Right-click on the**Windows 10 ISO** file and select**Mount** . This will create a new virtual DVD Drive and open the ISO folder.  
![mount windows 10 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/mount-windows-10-iso.jpg)
2. Open the**Sources** folder and locate the**appraiserres.dll** file. Copy the**DLL** file and move it to a different folder.  
![copy appraiserres dll windows 10 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-appraiserres-dll-windows-10-iso.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Next, extract the Windows 11 ISO to a different folder. You can [use WinRAR to extract](https://www.win-rar.com/start.html?&L=0) the Windows 11 ISO file.  
![extract windows 11 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/extract-windows-11-iso.jpg)
4. Open the Windows 11 ISO's extracted folder and then the**Source** folder.
5. Next, copy and paste the**appraiserres.dll** file copied from Windows 10 ISO into Windows 11 ISO's**Sources** folder.

1. Select**Replace the file in the destination** to confirm the action.  
![replace the file in the destination appraiserrs ll windows 11 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/replace-the-file-in-the-destination-appraiserrs-ll-windows-11-iso.jpg)
<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. Next, disconnect your PC from the Internet. This prevents the setup from downloading updated files during installation and overwriting the modified dll file.
3. Once the Internet is disabled, open the extracted Windows 11 ISO folder and double-click on the**Setup file** . Click**Yes** if prompted by UAC.
4. In the**Windows 11 Setup** dialog, click on**Change how Setup downloads updates.**  
![windows 11 setup not right now updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-11-setup-not-right-now-updates.jpg)
5. Next, select**Note right now.** This will prevent the Windows setup from finding and installing newer updates causing the upgrade process to fail on unsupported hardware.  
![windows 11 setup choose what to install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-11-setup-choose-what-to-install.jpg)
6. In the**Choose what to keep** screen, select**Keep personal files and apps.**
7. Click**Next** and then click on**Accept** .  
![windows 11 setup ready to install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-11-setup-ready-to-install.jpg)
8. Next, click on**Install** to install Windows 11 version 22H2 while keeping your personal files and apps.
9. Leave your computer idle until the installation process is complete. After the restart, you’ll have the latest Windows 11 22H2 running on your computer.

To check your Windows specification:

![check windows specification windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/check-windows-specification-windows-11.jpg)

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, scroll down and click on**About** .
3. Under Windows specifications, you’ll see**Version 22H2** if the upgrade was successful.

<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Go Back to the Previous Version
![go back windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/go-back-windows-11.jpg)

 If you run into an issue after the upgrade, you can use the**Go back** option to undo the update and restore the earlier version of Windows 11\. However, the "Go back" option is only available for seven days since the upgrade. After that, the option will be greyed out.

To go back to the previous version:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, scroll down and click on**Recovery** .
3. Click on**Go back** under**Recovery options** . Then, follow the on-screen instructions to uninstall the Windows 22H2 update.

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
## Installing Windows 11 22H2 on Unsupported Hardware

 It is easy to bypass the Windows 11 system hardware requirements when you want to perform a clean install. However, to perform an upgrade, you’ll need to modify the appraiserress.dll file and then run the setup.

 While the upgrade is possible for now, the lack of future automatic Windows updates makes maintaining the PC a complicated task. If upgrading to Windows 11 is not a must, you can stick to Windows 10 on older hardware, which will continue to receive support until late 2025.


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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-banner-bonanza-unlimited-50-free-youtube-designs/"><u>[New] 2024 Approved  Banner Bonanza  Unlimited 50 FREE YouTube Designs</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-pinpointing-pioneers-a-strategic-look-at-influencers-on-insta-for-2024/"><u>[New] Pinpointing Pioneers  A Strategic Look at Influencers on Insta for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-veracity-of-ffmpegs-audio-extraction-techniques/"><u>[New] The Veracity of FFmpeg’s Audio Extraction Techniques</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-ultimate-guide-to-top-tier-tripods-and-mounts-for-gopro-for-2024/"><u>[New] Ultimate Guide to Top-Tier Tripods & Mounts for GoPro for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-photo-perfection-top-6-iphone-utilities-to-exclude-unwanted-elements/"><u>[Updated] Photo Perfection  Top 6 iPhone Utilities to Exclude Unwanted Elements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/battery-friendly-tips-minimize-windows-11-apps-impact/"><u>Battery-Friendly Tips: Minimize Windows 11 Apps' Impact</u></a></li>
<li><a href="https://media-tips.techidaily.com/best-top-ranking-free-wmv-to-avi-video-converter-tools-a-comprehensive-guide/"><u>Best Top-Ranking Free WMV to AVI Video Converter Tools: A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-steam-goals-a-complete-walkthrough/"><u>Clearing Steam Goals: A Complete Walkthrough</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-security-with-windows-11-preparation/"><u>Elevate Security with Windows 11 Preparation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-the-depths-of-wacatacbml-signature-and-defense-for-windows-users/"><u>Exploring the Depths of Wacatac.B!ml: Signature & Defense for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719371847315-fixing-faulty-windows-keys-in-a-minute/"><u>Fixing Faulty Windows Keys in a Minute</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-mend-windows-disk-read-problems/"><u>Guide to Mend Windows Disk Read Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-curtail-pc-sound-enhancement-effects/"><u>How To Curtail PC Sound Enhancement Effects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-audacity-error-code-9999-in-windows-1110/"><u>How to Fix the Audacity Error Code 9999 in Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-isdonedll-isarcextract-error-in-windows-11-and-11/"><u>How to Fix the ISDone.dll (ISArcExtract) Error in Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-nvidia-control-panel-access-denied-error-in-windows-1110/"><u>How to Fix the NVIDIA Control Panel “Access Denied” Error in Windows 11/10</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-get-the-apple-id-verification-code-from-apple-iphone-15-in-the-best-ways-by-drfone-ios/"><u>How To Get the Apple ID Verification Code From Apple iPhone 15 in the Best Ways</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-stream-anything-from-xiaomi-redmi-note-12-5g-to-apple-tv-drfone-by-drfone-android/"><u>How To Stream Anything From Xiaomi Redmi Note 12 5G to Apple TV | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improve-live-feed-rates-on-task-monitor-win-11/"><u>Improve Live Feed Rates on Task Monitor Win 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-bypass-android-lock-screen-using-emergency-call-on-samsung-galaxy-a34-5g-by-drfone-android/"><u>In 2024, How to Bypass Android Lock Screen Using Emergency Call On Samsung Galaxy A34 5G?</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-the-ultimate-obs-playbook-for-twitch-and-youtube-streaming/"><u>In 2024, The Ultimate OBS Playbook for Twitch & YouTube Streaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-blue-screen-recovery-steps/"><u>Mastering Windows 11 Blue Screen Recovery Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-store-sign-in-troubles-solutions-await/"><u>Microsoft Store Sign-In Troubles? Solutions Await</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-non-responsive-ctrl-issue-in-windows-11/"><u>Overcoming the Non-Responsive Ctrl Issue in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-steps-for-a-functional-windows-11-search-interface/"><u>Quick Steps for a Functional Windows 11 Search Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reimagine-your-pc-swap-out-windows-11s-essentials/"><u>Reimagine Your PC: Swap Out Windows 11'S Essentials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-unavailable-windows-updates-in-windows/"><u>Restoring Unavailable Windows Updates in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/retrieving-lost-actions-from-winrunhist/"><u>Retrieving Lost Actions From WinRunHist</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-unresponsive-keyboard-arrows-top-troubleshooting-tips-and-fixes/"><u>Solve Unresponsive Keyboard Arrows: Top Troubleshooting Tips & Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-tutorial-for-turning-on-windows-11s-quick-start/"><u>Step-by-Step Tutorial for Turning On Windows 11'S Quick Start</u></a></li>
<li><a href="https://unlock-android.techidaily.com/still-using-pattern-locks-with-infinix-zero-30-5g-tips-tricks-and-helpful-advice-by-drfone-android/"><u>Still Using Pattern Locks with Infinix Zero 30 5G? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://fox-blue.techidaily.com/streamline-conversion-selecting-the-top-10-free-tools-for-2024/"><u>Streamline Conversion  Selecting the Top 10 Free Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-approach-automated-password-addition-into-windows-texts/"><u>Streamlined Approach: Automated Password Addition Into Windows Texts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-strategies-to-combat-windows-1011-error-740/"><u>Swift Strategies to Combat Windows 10/11 Error 740</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taking-control-of-windows-read-only-constraints/"><u>Taking Control of Windows Read-Only Constraints</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-secrets-to-configuring-pc-manager/"><u>Unveiling the Secrets to Configuring PC Manager</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-honor-x7b-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Location is Not Updating and How to Fix On Honor X7b | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-sid-exploration-a-comprehensible-guidebook/"><u>Windows 11 SID Exploration: A Comprehensible Guidebook</u></a></li>
</ul></div>
