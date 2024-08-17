---
title: "Overcoming 0X80070570 Error in Windows: Restoring Damaged Data"
date: 2024-08-16T02:11:24.572Z
updated: 2024-08-17T02:11:24.572Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Overcoming 0X80070570 Error in Windows: Restoring Damaged Data"
excerpt: "This Article Describes Overcoming 0X80070570 Error in Windows: Restoring Damaged Data"
keywords: Fix 0X80070570 Error,Windows System Recovery,Data Restoration Steps,Troubleshoot WinError,Stop Blue Screen Error,Data Damage Repair,Resolve BlueScreenX
thumbnail: https://thmb.techidaily.com/53c515418786e92ebed3c6206ea33f7c074dbdb116bb5f52f889c6937a269f05.jpg
---

## Overcoming 0X80070570 Error in Windows: Restoring Damaged Data

 Error 0x80070570 is a Windows issue that sometimes pops up when you try to delete files on external hard drives. This error also occurs when users try to transfer files between PCs and external drives. The error 0x80070570 message says, “The file or directory is corrupted and unreadable.”

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

## 1\. Repair System Files With an SFC Scan

 Some users have confirmed repairing system files resolved error 0x80070570 on their PCs. System File Checker is a command-line tool with which you can check for and repair corrupted system files that might be causing file operation issues. Check out our guide to [utilizing System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) for details about how to run an SFC scan within the Command Prompt.

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command2.jpg)

<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Utilize the Check Disk Tool

 Drive file system issues often cause error 0x80070570\. The most widely confirmed solution for that error is to run a CHKDSK scan of the drive you can’t delete files on or transfer files to. The CHKDSK tool can repair file system errors on the drive it’s scanning.

![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)

 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Perform a Startup Repair

 This resolution is recommended if error 0x80070570 occurs when trying to delete files on the C: hard drive or transfer them there. Startup Repair is primarily a utility for fixing Windows startup issues. However, that tool can remedy corrupted system files and C: drive issues. This is how you can utilize Startup Repair:

1. First, [bring up the Advanced Startup Options menu](https://www.makeuseof.com/windows-11-access-advanced-startup-options/) via the Settings app.
2. Select **Startup Repair** within the Advanced options menu.  
![The Start-up Repair option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-up-repair.jpg)
3. Next, select your Windows user account.
4. Input your user account password.
5. Select **Continue** to initiate the repair.

## 6\. Format an External Drive

 Formatting an affected external drive to which you can’t transfer files or delete data because of error 0x80070570 is suggested only as a last resort. Applying this potential fix will wipe all data on the drive, so do not format your PC’s C: drive. However, some users have confirmed formatting affected external drives fixes error 0x80070570\.

![The format drive utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-format-tool.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->

 You can format an external drive with the Windows Disk Management utility or in File Explorer. Connect the drive to your PC, and then follow the steps in this guide on [how to format a USB drive](https://www.makeuseof.com/tag/format-usb-drive/) to do this within File Explorer.

## Perform the Required File Operations Again on Windows

 The potential error 0x80070570 solutions covered here have worked for many Windows 11/10 users. Repairing drive errors with the CHKDSK tool usually does the trick. You could also utilize a third-party utility like Hard Disk Sentinel and HDDScan to check for and repair drive issues. With error 0x80070570 fixed, you can copy or delete files as required again.

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-docs.techidaily.com/024-approved-beyond-the-basics-advanced-techniques-for-improved-recordings/"><u>[New] 2024 Approved  Beyond the Basics  Advanced Techniques for Improved Recordings</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-the-essential-handbook-to-professional-screen-recordings/"><u>[New] 2024 Approved  The Essential Handbook to Professional Screen Recordings</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/iscover-the-power-of-5-editors-beyond-youtubes-boundaries-for-2024/"><u>[New] Discover the Power of 5 Editors Beyond Youtube's Boundaries for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-broadcasting-without-rts-video-tweeting-simplified/"><u>[New] In 2024, Broadcasting Without RTs  Video Tweeting Simplified</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-quick-and-easy-iphone-methods-to-download-podcasts-anywhere-for-2024/"><u>[New] Quick and Easy iPhone Methods to Download Podcasts Anywhere for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-the-visual-vault-techniques-for-capturing-tweets-animated-content-for-2024/"><u>[New] The Visual Vault  Techniques for Capturing Tweets’ Animated Content for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-capture-the-catch-5-pro-fish-cameras-unveiled/"><u>[Updated] Capture the Catch  5 Pro-Fish Cameras Unveiled</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-swift-methodology-to-weed-out-fake-pals-from-insta-network/"><u>[Updated] In 2024, Swift Methodology to Weed Out Fake Pals From Insta Network</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-best-practices-in-youtube-keyword-selection/"><u>2024 Approved  Best Practices in YouTube Keyword Selection</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-fiery-firefox-screenshot-add-ons/"><u>2024 Approved  Fiery Firefox Screenshot Add-Ons</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-illusions-realized-what-is-augmented-reality/"><u>2024 Approved  Illusions Realized  What Is Augmented Reality?</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-simplified-method-for-youtubers-to-dailymotion/"><u>2024 Approved  Simplified Method for YouTubers to Dailymotion</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/approved-upgrade-your-youtube-bio-with-pro-templates/"><u>2024 Approved  Upgrade Your Youtube Bio with Pro Templates</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/capture-and-share-best-social-media-tools-of-the-year-for-2024/"><u>Capture and Share  Best Social Media Tools of the Year for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/cryptographic-cantaloupe-does-this-voice-modification-appify-to-magic-find-other-tools-for-2024/"><u>Cryptographic Cantaloupe  Does This Voice Modification Appify to Magic? Find Other Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/debugging-0xc00ce556-the-winoss-parsing-quest/"><u>Debugging 0xC00CE556: The WinOSs Parsing Quest</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-enhanced-ui-in-windows-11/"><u>Discovering Enhanced UI in Windows 11</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/early-insights-into-the-power-and-performance-of-the-samsung-galaxy-s2-ultra/"><u>Early Insights Into the Power and Performance of the Samsung Galaxy S2# Ultra</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-routes-to-your-computers-command-center/"><u>Easy Routes to Your Computer’s Command Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-xbox-audio-quality-within-windows-11-framework/"><u>Elevating Xbox Audio Quality Within Windows 11 Framework</u></a></li>
<li><a href="https://win11-tips.techidaily.com/emancipate-chatbots-on-windows-using-freedomgpt/"><u>Emancipate ChatBots on Windows: Using FreedomGPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-context-menus-add-a-windows-diskspace-viewer/"><u>Enhance Context Menus: Add a Window's DiskSpace Viewer</u></a></li>
<li><a href="https://extra-hints.techidaily.com/essential-distortion-effects-for-photography-artists/"><u>Essential Distortion Effects for Photography Artists</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-activating-user-defined-permissions-in-windows-1011/"><u>Guide to Activating User-Defined Permissions in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-do-windows-downloads-vary-cloud-across-borders-vs-disk-locally/"><u>How Do Windows Downloads Vary: Cloud Across Borders Vs. Disk Locally</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-does-pagefilesys-affect-your-computers-performance-and-safety/"><u>How Does Pagefile.sys Affect Your Computer’s Performance & Safety?</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-frp-from-meizu-21-pro-by-drfone-android/"><u>How to Bypass FRP from Meizu 21 Pro?</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-correctly-address-the-0x80072efd-error-in-windows-11-systems/"><u>How to Correctly Address the 0X80072EFD Error in Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-error-0x80300024-in-windows/"><u>How to Fix Error 0X80300024 in Windows</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/how-to-prevent-and-mend-live-stream-glitches-fb-for-2024/"><u>How to Prevent & Mend Live Stream Glitches (FB) for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/humor-hacks-create-memes-free-and-easy-for-2024/"><u>Humor Hacks  Create Memes Free and Easy for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-gps-location-on-infinix-gt-10-pro-easily-and-safely-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change GPS Location on Infinix GT 10 Pro Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-does-enter-puk-code-mean-and-why-did-the-sim-get-puk-blocked-on-nokia-c12-device-by-drfone-android/"><u>In 2024, What Does Enter PUK Code Mean And Why Did The Sim Get PUK Blocked On Nokia C12 Device</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-youtube-visual-identity-made-easy/"><u>In 2024, YouTube Visual Identity Made Easy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/invoke-smooth-pathways-into-windows-shares/"><u>Invoke Smooth Pathways Into Windows Shares</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-steps-for-delving-into-windows-boot-zone/"><u>Key Steps for Delving Into Windows' Boot Zone</u></a></li>
<li><a href="https://extra-support.techidaily.com/kinemaster-tools-for-cohesive-narrative-flow-for-2024/"><u>Kinemaster Tools for Cohesive Narrative Flow for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-network-issues-with-ea-games-on-pc/"><u>Mastering Network Issues with EA Games on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-updates-decode-error-0xc1900101/"><u>Mastering Windows 11 Updates: Decode Error 0xC1900101</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-for-eliminating-interrupt-error-on-windows-1011/"><u>Methods for Eliminating INTERRUPT Error on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-through-windows-specific-excel-new-cell-inserts-glitches/"><u>Navigate Through Windows-Specific Excel New Cell Inserts Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/old-pc-new-tricks-staying-current-without-windows-11/"><u>Old PC, New Tricks: Staying Current Without Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-display-issues-with-missing-touch-or-stylus-functionality/"><u>Overcoming Display Issues with Missing Touch or Stylus Functionality</u></a></li>
<li><a href="https://win-answers.techidaily.com/overcoming-offline-hurdles-restoring-access-to-origin-service/"><u>Overcoming Offline Hurdles: Restoring Access to Origin Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-onedrive-failure-in-windows-versions-1011/"><u>Overcoming OneDrive Failure in Windows Versions 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-typing-hurdles-reinvigorating-the-tab-key-in-windows/"><u>Overcoming Typing Hurdles: Reinvigorating the Tab Key in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-lost-d3dx939dll-in-modern-windows-11/"><u>Resolving Lost D3DX9_39.dll in Modern Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-xbox-app-stranded-issue-quickly-on-windows-1011/"><u>Resolving Xbox App 'Stranded' Issue Quickly on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seize-savings-unveil-windows-11-pro-key-deals/"><u>Seize Savings: Unveil Windows 11 Pro Key Deals</u></a></li>
<li><a href="https://location-social.techidaily.com/set-your-preferred-job-location-on-linkedin-app-of-your-oneplus-ace-2v-drfone-by-drfone-virtual-android/"><u>Set Your Preferred Job Location on LinkedIn App of your OnePlus Ace 2V | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sidestep-the-initializing-wow-snag/"><u>Sidestep the Initializing WoW Snag</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-microphone-issues-with-xbox-app-on-pc/"><u>Solutions to Microphone Issues with Xbox App on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-common-issues-with-winservicesexe-quickly/"><u>Solving Common Issues with Winservices.exe Quickly</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/sonic-immersion-sonys-3d-earphones/"><u>Sonic Immersion: Sony's 3D Earphones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-recover-from-roblox-crashes/"><u>Strategies to Recover From Roblox Crashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-microsoft-teams-hurdle-80080300-on-win11-systems/"><u>Tackling Microsoft Teams Hurdle #80080300 on Win11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-write-issues-overcoming-folder-lockdowns-in-windows/"><u>Tackling Write Issues: Overcoming Folder Lockdowns in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-invisible-shutdown-command-secrete-windows-11s-hideaway/"><u>The Invisible Shutdown Command: Secrete Windows 11'S Hideaway</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-addressing-sluggish-downloads-on-windows-pcs/"><u>Tips for Addressing Sluggish Downloads on Windows PCs</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/transcription-triumphs-quick-methods-for-fb-call-records/"><u>Transcription Triumphs  Quick Methods for FB Call Records</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trim-down-your-taskbar-with-windows-11-tweaks/"><u>Trim Down Your Taskbar with Windows 11 Tweaks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unifying-powertoys-across-computers/"><u>Unifying PowerToys Across Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unshackling-windows-11-steps-to-bypass-security-measures/"><u>Unshackling Windows 11: Steps To Bypass Security Measures</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-are-location-permissions-life360-on-samsung-galaxy-z-fold-5-drfone-by-drfone-virtual-android/"><u>What are Location Permissions Life360 On Samsung Galaxy Z Fold 5? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-unearth-lost-features-and-tab-for-a-smoother-experience/"><u>Windows 11: Unearth Lost Features and Tab for a Smoother Experience</u></a></li>
</ul></div>
