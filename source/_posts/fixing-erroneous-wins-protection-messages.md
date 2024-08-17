---
title: Fixing Erroneous WINS Protection Messages
date: 2024-08-16T01:51:39.242Z
updated: 2024-08-17T01:51:39.242Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Erroneous WINS Protection Messages
excerpt: This Article Describes Fixing Erroneous WINS Protection Messages
keywords: Error-Free DNS,Winsock Repair Guide,Resolve WINS Issues,Fix WINS Mistakes,Correct DNS Misconfig,Stop Erroneous WINS,Secure DNS Messages
thumbnail: https://thmb.techidaily.com/37cbd79bb1dc4f01076609d4f2040fc4f61e96fa43faa2585a2bbac8dade3639.jpg
---

## Fixing Erroneous WINS Protection Messages

 Windows Security incorporates the Microsoft Defender antivirus utility. However, some users can’t select to run Microsoft Defender scans because of an error message that says: “Unexpected error. Sorry, we ran into a problem.” That “Unexpected error” message pops up for some users when they select the**Virus & threat protection** tab in Windows Security.

 Consequently, the**Virus and threat protection tab** is inaccessible. That error means there’s an issue with the Windows antivirus tool. This is how you can resolve the “Unexpected error” issue.

## 1\. Check for New Windows Updates

 First, check for and install available Windows patch updates. Microsoft releases many patches to update Microsoft Defender. So, a patch update could feasibly resolve a Windows Security bug. Our [guide to manually updating Windows](https://www.makeuseof.com/update-windows-manually/#:~:text=Press%20the%20Win%20%2B%20I%20hotkeys,the%20Check%20for%20updates%20button.) tells you how to check for and install new updates in Settings.

![The Reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-option.jpg)

<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Run System File and Image Scans

 System file issues might be causing the “Unexpected error” on your PC. To check if that’s the case, run a System File Checker scan within the Command Prompt. Such a scan will repair the corrupted system files detected. Our guide on [utilizing the SFC tool on Windows](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to scan system files with that utility.

![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-sfc-scannow-command.jpg)

 It’s also recommended to run a Deployment Image Servicing and Management scan, which can resolve Windows system image issues. The System File Checker tool doesn’t work when there are issues with the system image. So, try executing this command before the SFC scan as well:

`Dism /Online /Cleanup-Image /RestoreHealth`

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
## 3\. Remove Third-Party Antivirus Software

 Do you have an alternative third-party antivirus tool installed on your PC? If so, then there’s a possibility that antivirus software is causing the issue by conflicting with Microsoft Defender. At least try turning off the third-party AV utility by right-clicking the system tray icon for the app and selecting a disable context menu setting.

 If disabling the third-party antivirus software works, you have two options. You can re-enable that antivirus software and utilize the alternative antivirus scanner it provides. Or you can completely uninstall the third-party antivirus software if you prefer Microsoft Defender. Our guide to removing Windows software includes numerous methods for uninstalling programs.

## 4\. Modify the Windows Defender Registry Key

 This registry tweak for modifying a**DisableAntiSpyware** DWORD is one of the most widely confirmed fixes for the “Unexpected error” issue. So, maybe this could the “Unexpected error” solution you’re looking for as well. To apply this potential fix, edit the registry as follows:

1. Open Run, input**regedit** , and click**OK** .
2. Erase the current registry path and input this registry key location inside the address box:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender`
3. You can skip through to step five if the Windows Defender key includes a**DisableAntiSpyware** DWORD. However, users who can’t see that DWORD will need to right-click the**Windows Defender** key and select**New** \>**DWORD** .  
![The New and Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-new-key-options.jpg)
4. Type**DisableAntiSpyware** in the DWORD’s text box.
5. Double-click the**DisableAntiSpyware** DWORD to access its**Value** box.
6. Input**0** in the data box if that’s not the current value set.  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-edit-dword-window.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
7. Select**OK** to confirm the value for the DWORD.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## 5\. Reset the Windows Security App

 Resetting Windows Security is worth trying whenever that app isn’t working right. In this case, something is up with the antivirus component of that app. You can reset that app within Settings or by executing a PowerShell command. Our article about [resetting Windows Security](https://www.makeuseof.com/windows-11-reset-windows-security/) tells you how to apply this potential resolution in three different ways.

![The Reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-option.jpg)

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Run a Malwarebytes Scan

 The “Unexpected error” can sometimes be caused by malware targeting Windows Security. Yet, users can’t purge malware with Windows Security because of the error. So, try running a scan with the freeware Malwarebytes version. Some users have said utilizing that software helped them resolve the “Unexpected error” issue. This is how you can run a Malwarebytes scan:

1. Open the [Malwarebytes](https://www.anrdoezrs.net/links/7251228/type/dlg/sid/UUmuoUeUpU2024249/https://www.malwarebytes.com/) website.
2. Click the**Free Download** button.
3. Activate Explorer by holding the**Windows** logo key and pressing**E** .
4. Go to the folder location containing the Malwarebytes setup file.
5. Double-click the**MBSetup.exe** file.
6. Click**Install** to add Malwarebytes to a default directory path.  
![The Install button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-button-for-malwarebytes.jpg)
<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Select**Me or my family** (for personal use) at the production selection step and click**Next** .
8. Click**Skip this for now** if you prefer not to install the additional Malwarebytes Browser Guard software.  
![The Skip this for now option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/skip-this-for-now-option.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
9. Select**Done** to finish.
10. Malwarebytes will then open automatically. Select**Get started** \>**Maybe later** within the Malwarebytes window.
11. Click**Get started** again.
12. Select Malwarebytes’**Scan** option.  
![The Scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/scan-option.jpg)
13. Press the**Quarantine** button after the scan.

 If this potential resolution works, you can keep Malwarebytes installed for manual scanning. It’s a 14-day trial of the Premium version, and the real-time protection will only last a couple of weeks. However, you can disable the Malwarebytes protection to ensure it doesn’t conflict with Microsoft Defender by right-clicking the utility’s system tray icon and deselecting the**Malware** ,**Ransomware** ,**Exploit** , and**Web Protection** options.

 The Microsoft Safety Scanner is an alternative to Malwarebytes you can run a malware scan with as well. However, that’s only a temporary scanning utility that expires after 10 days. You can download that utility from this [Microsoft page](https://learn.microsoft.com/en-us/microsoft-365/security/intelligence/safety-scanner-download?view=o365-worldwide) . Check out [our Microsoft Safety Scanner guide](https://www.makeuseof.com/microsoft-safety-scanner-guide/) for details about to purge malware with that tool.

## 7\. Check the "Turn Off Microsoft Defender Antivirus" Group Policy Setting

 If you’re a Windows Pro or Enterprise user, check that the the**Turn Off Microsoft Defender Antivirus** policy isn’t enabled in Group Policy. You can check that policy in the following steps:

1. [Open Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) by pressing the**Windows** logo +**S** hotkey, entering**gpedit.msc** in the search box, and selecting the**gpedit.msc** result.
2. Then navigate to this policy location in Group Policy’s sidebar:  
`Computer Configuration\Administrative Templates\Windows Components\Microsoft Defender Antivirus`
3. Next, double-click**Turn Off Microsoft Defender Antivirus** to check that policy.  
![The Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/microsoft-defender-antivirus-policy-settings.jpg)
4. Click**Not Configured** if that policy is set to**Enabled** .  
![The Turn Off Microsoft Defender Antivirus policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-microsoft-defender-antivirus.jpg)
5. Select the policy’s**Apply** and**OK** options.

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 8\. Reset Windows or Perform an In-Place Upgrade

 Resetting Windows is a troubleshooting method that restores the platform to a default (factory) configuration. The Reset this PC tool gives you a simple way to reinstall the platform and preserve user files, but you’ll need to reinstall apps.

[Applying a Windows reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) might resolve some deeper system issues causing the “Unexpected error” issue. However, it’s only advised to do so if none of the other potential solutions suggested here work.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-this-pc-tool.jpg)
<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 An in-place upgrade is an alternative troubleshooting method to resetting Windows. Performing an in-place upgrade will reinstall Windows by installing the latest build version. So, it’s like a reset, but the advantage is that an in-place upgrade preserves the apps you’ve installed. This guide to [performing an in-place upgrade on Windows](https://www.makeuseof.com/in-place-upgrade-windows-11/) provides full instructions for upgrading Windows 11 in such a way.

 However, you could feasibly upgrade to a new Windows version via Settings. Open**Windows Update** in the Settings app to see if there’s a version upgrade available. If so, select to upgrade to the latest Windows build from there.

## Run a Scan With Windows Security Again

 You’ll probably be able to access the antivirus-scanning options in Windows Security again after applying the potential solutions covered here. So, try applying all those potential “Unexpected error” resolutions in the order specified to find one that works on your Windows PC. You can also contact the [Microsoft Windows support service](https://support.microsoft.com/en-us/home/contact?SourceApp=smc2&ContactUsExperienceEntryPointAssetId=Google) for further assistance but give the potential fixes outlined here a try first.

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
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-pinnacle-10-royale-struggle-games/"><u>[New] 2024 Approved  Pinnacle 10 Royale Struggle Games</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ow-to-watch-deleted-youtube-videos-online-in-2-ways-ultimate-guide/"><u>[New] How to Watch Deleted YouTube Videos Online in 2 Ways | Ultimate Guide</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-how-to-create-a-youtube-account/"><u>[New] In 2024, How to Create a YouTube Account</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2023-techniques-for-harvesting-fb-status-video-content-for-2024/"><u>[Updated] 2023 Techniques for Harvesting FB Status Video Content for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-prime-opening-strategies-top-16-youtube-vids-that-thrive/"><u>[Updated] 2024 Approved  Prime Opening Strategies  Top 16 YouTube Vids That Thrive</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-seamless-mp4-to-fb-video-transfer-technology/"><u>[Updated] 2024 Approved  Seamless MP4-to-FB Video Transfer Technology</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-top-6-cool-minecraft-house-ideas-for-2024/"><u>[Updated] Top 6 Cool Minecraft House Ideas for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-step-by-step-blueprint-for-impressive-photographic-mosaics/"><u>2024 Approved  Step-by-Step Blueprint for Impressive Photographic Mosaics</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-top-13-effortless-revenue-strategies-for-newbies-on-reddit/"><u>2024 Approved  Top 13 Effortless Revenue Strategies for Newbies on Reddit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-memory-diagnostic-failure-on-your-pc/"><u>Addressing 'Memory Diagnostic Failure' On Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-network-throughput-measurement/"><u>Advanced Network Throughput Measurement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amend-non-working-shortcuts-solve-f-keys-issue-on-windows-11/"><u>Amend: Non-Working Shortcuts - Solve F Keys Issue on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-insight-into-hardware-allocated-memory-in-windows/"><u>An Insight Into Hardware-Allocated Memory in Windows</u></a></li>
<li><a href="https://win-solutions.techidaily.com/dealing-with-resident-evil-village-unlaunching-glitches/"><u>Dealing with Resident Evil Village Unlaunching Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-windows-11s-system-tools/"><u>Deciphering Windows 11'S System Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-steps-to-install-emoji-15-on-your-pc/"><u>Decoding the Steps to Install Emoji 15 on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/digital-ecosystem-integration-windows-apps-on-iphones-pcs-and-macs-launched/"><u>Digital Ecosystem Integration: Windows Apps on iPhones, PCs and Macs Launched</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-find-and-purge-unused-windows-folders-for-a-streamlined-pc/"><u>Efficiently Find & Purge Unused Windows Folders for a Streamlined PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-linux-performance-via-windows-apps/"><u>Elevating Linux Performance via Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-classic-gaming-collection-with-retroarch-achievements-tutorial/"><u>Enhance Your Classic Gaming Collection with Retroarch Achievements Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-efficiency-of-frozen-windows-safety-mode/"><u>Enhancing Efficiency of Frozen Windows Safety Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-windows-camera-recording-retention/"><u>Expert Tips for Windows Camera Recording Retention</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-come-up-with-the-best-pokemon-team-on-samsung-galaxy-s23plus-drfone-by-drfone-virtual-android/"><u>How to Come up With the Best Pokemon Team On Samsung Galaxy S23+? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-apple-iphone-6-to-factory-settings-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Reset Apple iPhone 6 to Factory Settings? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-trigger-or-suppress-windows-file-dialogs/"><u>How to Trigger or Suppress Windows File Dialogs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/make-the-most-of-windows-11s-enhanced-bar/"><u>Make the Most of Windows 11'S Enhanced Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-sleep-cycles-in-windows-systems/"><u>Mastering Sleep Cycles in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-onedrive-overcoming-delayed-folder-upload-errors/"><u>Mastering Windows OneDrive: Overcoming Delayed Folder Upload Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-suppress-mechanism-for-windows-11-dings/"><u>Quick Suppress Mechanism for Windows 11 Dings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/riding-out-the-storm-conquering-xbox-app-glitches-on-win11/"><u>Riding Out the Storm: Conquering Xbox App Glitches on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-skyrim-experience-cutting-down-x-script-errors/"><u>Seamless Skyrim Experience: Cutting Down X-Script Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-innovation-windows-personalization-through-lock-patterns/"><u>Stepwise Innovation: Windows Personalization Through Lock Patterns</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-reviving-the-net-framework-on-pcs-max-156/"><u>The Art of Reviving the .NET Framework on PCs (Max 156)</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-best-mp4-devices-roundup/"><u>The Best MP4 Devices Roundup</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-ultimate-guide-to-earning-cash-online-with-no-skills-needed-for-2024/"><u>The Ultimate Guide to Earning Cash Online with No Skills Needed for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-no-cost-win-for-podcast-enthusiasts/"><u>The Ultimate No-Cost Win for Podcast Enthusiasts</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/0-inspirational-hr-journeys-unveiled-for-2024/"><u>Top 10 Inspirational HR Journeys Unveiled for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-outlooks-failing-notification-system-a-user-friendly-approach/"><u>Troubleshooting Outlook's Failing Notification System: A User-Friendly Approach</u></a></li>
<li><a href="https://some-skills.techidaily.com/unleash-your-livestream-potential-no-millions-of-followers-needed-for-2024/"><u>Unleash Your Livestream Potential  No Millions of Followers Needed for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-swift-notification-off-switch/"><u>Windows 11: Swift Notification OFF Switch</u></a></li>
</ul></div>
