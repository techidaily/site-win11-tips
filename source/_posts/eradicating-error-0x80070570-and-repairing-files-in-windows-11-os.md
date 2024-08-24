---
title: Eradicating Error 0X80070570 & Repairing Files in Windows 11 OS
date: 2024-08-23T07:02:01.670Z
updated: 2024-08-24T07:02:01.670Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eradicating Error 0X80070570 & Repairing Files in Windows 11 OS
excerpt: This Article Describes Eradicating Error 0X80070570 & Repairing Files in Windows 11 OS
keywords: Fix Windows 11 ZeroError,Eradicate Win11 FS Error,Resolve WinXPatch_070570,Eliminate WinOS 11 Fail,Correct Windows FS Error,Rectify 0X80070570 Issue,Cure XP11 File Corruption
thumbnail: https://thmb.techidaily.com/75e496d7d03af882c809a7273c9e1eb1d9baeae9a3a5a4a6ed566b778061c9ff.png
---

## Eradicating Error 0X80070570 & Repairing Files in Windows 11 OS

 Error 0x80070570 is a Windows issue that sometimes pops up when you try to delete files on external hard drives. This error also occurs when users try to transfer files between PCs and external drives. The error 0x80070570 message says, “The file or directory is corrupted and unreadable.”

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

## 1\. Repair System Files With an SFC Scan

 Some users have confirmed repairing system files resolved error 0x80070570 on their PCs. System File Checker is a command-line tool with which you can check for and repair corrupted system files that might be causing file operation issues. Check out our guide to [utilizing System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) for details about how to run an SFC scan within the Command Prompt.

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command2.jpg)

## 2\. Utilize the Check Disk Tool

 Drive file system issues often cause error 0x80070570\. The most widely confirmed solution for that error is to run a CHKDSK scan of the drive you can’t delete files on or transfer files to. The CHKDSK tool can repair file system errors on the drive it’s scanning.

![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command.jpg)

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Perform a Startup Repair

 This resolution is recommended if error 0x80070570 occurs when trying to delete files on the C: hard drive or transfer them there. Startup Repair is primarily a utility for fixing Windows startup issues. However, that tool can remedy corrupted system files and C: drive issues. This is how you can utilize Startup Repair:

1. First, [bring up the Advanced Startup Options menu](https://www.makeuseof.com/windows-11-access-advanced-startup-options/) via the Settings app.
2. Select **Startup Repair** within the Advanced options menu.  
![The Start-up Repair option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-up-repair.jpg)
3. Next, select your Windows user account.
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
4. Input your user account password.
5. Select **Continue** to initiate the repair.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
## 6\. Format an External Drive

 Formatting an affected external drive to which you can’t transfer files or delete data because of error 0x80070570 is suggested only as a last resort. Applying this potential fix will wipe all data on the drive, so do not format your PC’s C: drive. However, some users have confirmed formatting affected external drives fixes error 0x80070570\.

![The format drive utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-format-tool.jpg)

 You can format an external drive with the Windows Disk Management utility or in File Explorer. Connect the drive to your PC, and then follow the steps in this guide on [how to format a USB drive](https://www.makeuseof.com/tag/format-usb-drive/) to do this within File Explorer.

## Perform the Required File Operations Again on Windows

 The potential error 0x80070570 solutions covered here have worked for many Windows 11/10 users. Repairing drive errors with the CHKDSK tool usually does the trick. You could also utilize a third-party utility like Hard Disk Sentinel and HDDScan to check for and repair drive issues. With error 0x80070570 fixed, you can copy or delete files as required again.

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-top-10-essential-tools-for-pro-ig-video-editors/"><u>[New] 2024 Approved  Top 10 Essential Tools for Pro IG Video Editors</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-conveniently-record-and-preserve-your-online-gatherings/"><u>[New] Conveniently Record and Preserve Your Online Gatherings</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-crafting-compelling-stories-for-online-video-platforms/"><u>[Updated] 2024 Approved  Crafting Compelling Stories for Online Video Platforms</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/1716070171738-updated-2024-approved-live-video-logging-on-mac-free/"><u>[Updated] 2024 Approved  Live Video Logging on Mac, Free!</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-imitation-ingenuity-generating-parodies-of-films/"><u>[Updated] Imitation Ingenuity  Generating Parodies of Films</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-crafting-soft-declines-in-volume-using-audacity/"><u>2024 Approved  Crafting Soft Declines in Volume Using Audacity</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-effective-techniques-for-capturing-windows-8-display/"><u>2024 Approved  Effective Techniques for Capturing Windows 8 Display</u></a></li>
<li><a href="https://android-unlock.techidaily.com/a-perfect-guide-to-remove-or-disable-google-smart-lock-on-motorola-edge-40-neo-by-drfone-android/"><u>A Perfect Guide To Remove or Disable Google Smart Lock On Motorola Edge 40 Neo</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-futuristic-windows-with-ai-assistance/"><u>Crafting Futuristic Windows with AI Assistance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/debugging-code-0x0001-on-nvidia-software-w11/"><u>Debugging Code 0X0001 on Nvidia Software, W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disconnecting-anonymous-windows-users-securely/"><u>Disconnecting Anonymous Windows Users Securely</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-method-to-dismiss-incorrect-virus-notifications-on-windows-chrome/"><u>Efficient Method to Dismiss Incorrect Virus Notifications on Windows Chrome</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-error-0x0000004e-on-windows-os/"><u>Eradicating Error 0X0000004E on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fixes-for-run-as-user-permissions-problems/"><u>Essential Fixes for Run As User Permissions Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-methods-to-wi-fi-erase-on-windows-11/"><u>Essential Methods to Wi-Fi Erase on Windows 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/everything-you-need-to-know-about-lock-screen-settings-on-your-xiaomi-redmi-note-12-pro-5g-by-drfone-android/"><u>Everything You Need to Know about Lock Screen Settings on your Xiaomi Redmi Note 12 Pro 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-quickly-resolving-windows-error-0xc0000001/"><u>Expert Tips for Quickly Resolving Windows Error 0xC0000001</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-advanced-network-monitoring-with-windows-11s-netstat-tool/"><u>Explore Advanced Network Monitoring with Windows 11'S Netstat Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-no-supported-device-for-windows-hello-login/"><u>Fixing 'No Supported Device' For Windows Hello Login</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-mend-missing-steam-game-icons/"><u>Guide to Mend Missing Steam Game Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-lowered-cpu-levels-on-windows-hosts/"><u>Guiding Lowered CPU Levels on Windows Hosts</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-exit-android-factory-mode-on-xiaomi-redmi-a2plus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Exit Android Factory Mode On Xiaomi Redmi A2+? | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-phantom-pitches-is-this-magical-talker-an-illusion-or-reality-explore-more-options/"><u>In 2024, Phantom Pitches  Is This Magical Talker an Illusion or Reality? Explore More Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-win11-like-a-pro-with-powerful-command-shortcuts/"><u>Navigate Win11 Like a Pro with Powerful Command Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-complexities-of-dism-with-win11-images/"><u>Navigating the Complexities of DISM with Win11 Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-challenge-restarting-windows-service/"><u>Overcoming the Challenge: Restarting Windows Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaim-lost-connection-7-fast-fixes-for-non-wi-fi-usb-in-windows-os/"><u>Reclaim Lost Connection: 7 Fast Fixes for Non-Wi-Fi USB in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rediscovering-the-past-7-windows-11-features-from-yesteryears/"><u>Rediscovering the Past: 7 Windows 11 Features From Yesteryears</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-windows-11-to-revive-inactive-wi-fi-hotspot/"><u>Resetting Windows 11 to Revive Inactive Wi-Fi Hotspot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-for-windows-error-code-0x887a0006-gpu-hang/"><u>Step-by-Step for Windows Error Code 0X887A0006: GPU Hang</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-wise-implementation-of-ms-defender-application-guard-in-edge-browser/"><u>Step-Wise Implementation of MS Defender Application Guard in Edge Browser</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-app-problem-solving-with-7-actions/"><u>Streamlining Windows App Problem-Solving with 7 Actions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/system-debugging-made-easy-locating-and-resolving-error-codes-via-the-power-of-command-prompt/"><u>System Debugging Made Easy: Locating and Resolving Error Codes via the Power of Command Prompt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-non-viewable-files-in-outlook-2019-on-a-pc/"><u>Tackling Non-Viewable Files in Outlook 2019 on a PC</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-hidden-reasons-behind-imovies-cuts/"><u>The Hidden Reasons Behind iMovie’s Cuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-simplified-approach-to-creating-windows-11-uwp-links/"><u>The Simplified Approach to Creating Windows 11 (UWP) Links</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/the-ultimate-guide-to-animated-text-in-mobile-videos-for-2024/"><u>The Ultimate Guide to Animated Text in Mobile Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-overcome-windows-steam-display-problems/"><u>Tips to Overcome Windows Steam Display Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-big-files-windows-disk-space-cleanup-guide/"><u>Uncovering Big Files: Windows Disk Space Cleanup Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-resolving-error-0x80070091-in-windows-os/"><u>Understanding and Resolving Error 0X80070091 in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unearthing-windows-bsod-indicators-and-their-origins/"><u>Unearthing Windows BSOD Indicators & Their Origins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-mystery-8-ways-to-iis-manager-access/"><u>Unlocking the Mystery: 8 Ways to IIS Manager Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-fix-for-error-code-0x80041015-on-pc/"><u>Unveiling the Fix for Error Code 0X80041015 on PC</u></a></li>
<li><a href="https://howto.techidaily.com/want-to-uninstall-google-play-service-from-realme-c67-4g-here-is-how-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Want to Uninstall Google Play Service from Realme C67 4G? Here is How | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-arm-from-iso-file-to-fully-operational-os/"><u>Windows 11 ARM: From ISO File to Fully Operational OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-reserve-memory-an-overview/"><u>Windows Reserve Memory: An Overview</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>