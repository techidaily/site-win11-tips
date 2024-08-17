---
title: Troubleshooting Code 0X80070570 File Corruption in Windows 11
date: 2024-08-16T01:38:07.829Z
updated: 2024-08-17T01:38:07.829Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Code 0X80070570 File Corruption in Windows 11
excerpt: This Article Describes Troubleshooting Code 0X80070570 File Corruption in Windows 11
keywords: Win11 Error 0X80070570,Fixing X70 Code Failure,Resolve Windows Filescorrupt,Corruption Error in Win11 Update,Troubleshoot 0X80070570 File Issue,Unblock Code 0X80070570 XSS,Microsoft XP70 Windows Fix Guide
thumbnail: https://thmb.techidaily.com/506707788e28afb0dd333ede3d14b446e4802e54b3be096a7cd03abb7e8cbcbb.jpg
---

## Troubleshooting Code 0X80070570 File Corruption in Windows 11

 Error 0x80070570 is a Windows issue that sometimes pops up when you try to delete files on external hard drives. This error also occurs when users try to transfer files between PCs and external drives. The error 0x80070570 message says, “The file or directory is corrupted and unreadable.”

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

## 1\. Repair System Files With an SFC Scan

 Some users have confirmed repairing system files resolved error 0x80070570 on their PCs. System File Checker is a command-line tool with which you can check for and repair corrupted system files that might be causing file operation issues. Check out our guide to [utilizing System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) for details about how to run an SFC scan within the Command Prompt.

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command2.jpg)

## 2\. Utilize the Check Disk Tool

 Drive file system issues often cause error 0x80070570\. The most widely confirmed solution for that error is to run a CHKDSK scan of the drive you can’t delete files on or transfer files to. The CHKDSK tool can repair file system errors on the drive it’s scanning.

![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)

 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
## 5\. Perform a Startup Repair

 This resolution is recommended if error 0x80070570 occurs when trying to delete files on the C: hard drive or transfer them there. Startup Repair is primarily a utility for fixing Windows startup issues. However, that tool can remedy corrupted system files and C: drive issues. This is how you can utilize Startup Repair:

1. First, [bring up the Advanced Startup Options menu](https://www.makeuseof.com/windows-11-access-advanced-startup-options/) via the Settings app.
2. Select **Startup Repair** within the Advanced options menu.  
![The Start-up Repair option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-up-repair.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
3. Next, select your Windows user account.
4. Input your user account password.
5. Select **Continue** to initiate the repair.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
## 6\. Format an External Drive

 Formatting an affected external drive to which you can’t transfer files or delete data because of error 0x80070570 is suggested only as a last resort. Applying this potential fix will wipe all data on the drive, so do not format your PC’s C: drive. However, some users have confirmed formatting affected external drives fixes error 0x80070570\.

![The format drive utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-format-tool.jpg)

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
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-convert-live-facebook-videos-to-mp3s-on-the-fly/"><u>[New] 2024 Approved  Convert Live Facebook Videos to MP3s on the Fly</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-speedy-snapshot-and-voice-guided-session-creator/"><u>[New] In 2024, Speedy Snapshot & Voice-Guided Session Creator</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-movavi-screencapture-pro-detailed-review-analysis/"><u>[Updated] 2024 Approved  Movavi ScreenCapture Pro  Detailed Review Analysis</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-co-create-content-to-maximize-youtube-follower-count/"><u>[Updated] Co-Create Content to Maximize YouTube Follower Count</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-cross-platform-connection-masterclass-instagramfacebook/"><u>[Updated] Cross-Platform Connection Masterclass  Instagram/Facebook</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-whipped-watchers-guide-complete-review-of-frozen-food-filming-tech/"><u>[Updated] In 2024, Whipped Watcher's Guide  Complete Review of Frozen Food Filming Tech</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-snapchat-artistry-integrating-anime-inspired-effects-for-2024/"><u>[Updated] Snapchat Artistry  Integrating Anime-Inspired Effects for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-streamlining-capture-procedures-with-adobe-presenter-for-2024/"><u>[Updated] Streamlining Capture Procedures with Adobe Presenter for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-fast-passes-to-the-control-settings-hub/"><u>11 Fast Passes to the Control Settings Hub</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-bring-a-smile-simple-meme-creation-with-kapwing/"><u>2024 Approved  Bring a Smile  Simple Meme Creation With Kapwing</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-building-a-custom-link-for-youtubes-auto-subscribe/"><u>2024 Approved  Building a Custom Link for YouTube's Auto-Subscribe</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-playcapture-x-the-cost-free-videography-for-games/"><u>2024 Approved  PlayCapture X  The Cost-Free Videography for Games</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-revolutionary-recorders-outside-the-native-windows-ecosystem/"><u>2024 Approved  Revolutionary Recorders Outside the Native Windows Ecosystem</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-streamline-your-workflow-with-aiseesoft-recording-tools/"><u>2024 Approved  Streamline Your Workflow with Aiseesoft Recording Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-access-the-startup-folder-in-windows/"><u>5 Ways to Access the Startup Folder in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-permanently-disable-microsoft-defender-in-windows-11/"><u>5 Ways to Permanently Disable Microsoft Defender in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-strategies-reviving-failed-google-drive-windows-links/"><u>7 Strategies: Reviving Failed Google Drive Windows Links</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-ways-to-fix-a-reappearing-deleted-file-or-folder-on-windows/"><u>8 Ways to Fix a Reappearing Deleted File or Folder on Windows</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-oneplus-ace-2-pro-system-crash-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix OnePlus Ace 2 Pro System Crash Issue | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensible-windows-screentime-intermission/"><u>A Comprehensible Window's Screentime Intermission</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-detailed-walkthrough-of-using-system-restore-in-windows-os/"><u>A Detailed Walkthrough of Using System Restore in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-personalizing-windows-using-winbubble/"><u>A Step-by-Step Guide to Personalizing Windows Using WinBubble</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-pcs-file-sharing-utorrent-tips/"><u>Accelerate Your PC's File Sharing - uTorrent Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-your-pcs-problems-4-top-pct-strategies/"><u>Ace Your PC's Problems: 4 Top PCT Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-peak-performance-tweaking-amd-radeon-windows-settings/"><u>Achieve Peak Performance: Tweaking AMD Radeon Windows Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-harmony-with-googles-cross-platform-tool/"><u>Achieving Harmony with Google's Cross-Platform Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapting-oculus-quest-2-for-windows-vr-compatibility/"><u>Adapting Oculus Quest 2 for Windows VR Compatibility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-num-caps-lock-signifiers-in-win11-systemtray/"><u>Adding Num, Caps Lock Signifiers in Win11 SystemTray</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-error-x80049dd3-for-smooth-typing-on-windows-11/"><u>Addressing Error X80049DD3 for Smooth Typing on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-clickable-items-in-the-latest-os-update/"><u>Addressing Non-Clickable Items in the Latest OS Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-terminal-background-for-custom-aesthetics/"><u>Adjust Terminal Background for Custom Aesthetics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-words-settings-for-consistent-openness-of-email-attachments-as-text/"><u>Adjust Word's Settings for Consistent Openness of Email Attachments as Text</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-settings-for-continuous-save-support-in-nvidia-control-center/"><u>Adjusting Settings for Continuous Save Support in NVidia Control Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advice-for-avoiding-hidden-displays-during-windows-games/"><u>Advice for Avoiding Hidden Displays During Windows Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-privilege-levels-for-non-administrators-on-windows-os/"><u>Altering Privilege Levels for Non-Administrators on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-outlook-speed-for-a-smooth-win-experience/"><u>Amplify Outlook Speed for a Smooth WIN Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-experts-strategy-for-managing-component-services-in-w11/"><u>An Expert's Strategy for Managing Component Services in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-fun-integrating-games-into-windows-11-through-google-play/"><u>Android Fun: Integrating Games Into Windows 11 Through Google Play</u></a></li>
<li><a href="https://win11-tips.techidaily.com/audio-troubleshooting-in-obs-studio-on-windows-11-devices/"><u>Audio Troubleshooting in OBS Studio on Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-clutter-boost-clarity-keeping-your-notifications-centered-in-windows-11/"><u>Avoid Clutter, Boost Clarity: Keeping Your Notifications Centered in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-disruptions-how-to-mend-broken-windows-registry-items/"><u>Avoiding Disruptions: How to Mend Broken Windows Registry Items</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-unwanted-bios-access-during-windows-initialization/"><u>Avoiding Unwanted BIOS Access During Windows Initialization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blackview-minipc-size-upgrade-speed-downgrade/"><u>Blackview MiniPC: Size Upgrade, Speed Downgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-with-these-5-unique-windows-pc-time-saver-tools/"><u>Boost Productivity with These 5 Unique Windows PC Time Saver Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-awareness-of-power-levels-with-win-1011/"><u>Boosting Awareness of Power Levels with Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719346952101-chatgpt-lite-free-self-hosted-windows-edition-with-gpt4all/"><u>ChatGPT Lite: Free Self-Hosted Windows Edition with GPT4All</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-installation-of-updated-hp-deskjet-2540-printer-drivers-download-options-and-tips/"><u>Easy Installation of Updated HP DeskJet 2540 Printer Drivers: Download Options & Tips</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/elevate-your-videography-7-free-sound-effects-collection/"><u>Elevate Your Videography - 7 Free Sound Effects Collection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719204304616-gpt4all-free-chatbot-clones-at-home-for-windows/"><u>GPT4All: Free ChatBot Clones at Home for Windows.</u></a></li>
<li><a href="https://some-techniques.techidaily.com/how-much-do-podcasters-earn-on-average-in-2024/"><u>How Much Do Podcasters Earn on Average, In 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-life360-notify-when-you-log-out-on-samsung-galaxy-a05-drfone-by-drfone-virtual-android/"><u>In 2024, Does Life360 Notify When You Log Out On Samsung Galaxy A05? | Dr.fone</u></a></li>
<li><a href="https://fox-links.techidaily.com/in-2024-expert-advice-youtube-to-mpeg-compression-guide/"><u>In 2024, Expert Advice  YouTube to MPEG Compression Guide</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-life360-on-windows-pc-for-realme-c55-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Life360 on Windows PC For Realme C55? | Dr.fone</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-maximizing-engagement-with-proper-yt-thumbnail-size/"><u>In 2024, Maximizing Engagement with Proper YT Thumbnail Size</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mastering-permissions-with-the-trustedinstaller-on-windows-pertinent-to-system-alterations/"><u>Mastering Permissions with the TrustedInstaller on Windows Pertinent to System Alterations</u></a></li>
<li><a href="https://extra-information.techidaily.com/narrating-real-life-how-to-write-engaging-docu-scripts/"><u>Narrating Real Life  How to Write Engaging Docu-Scripts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719370071964-resolve-wwin-plus-p-non-functionality-in-windows-systems/"><u>Resolve WWin + P Non-Functionality in Windows Systems.</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/respecting-copyrights-when-converting-youtube-to-mp4-for-2024/"><u>Respecting Copyrights When Converting YouTube to MP4 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719376942389-windows-gptmimicry-a-costless-local-edition-via-gpt4all/"><u>Windows GPTMimicry: A Costless Local Edition via GPT4All.</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/yt-bidirectional-navigating-the-queue-from-the-conclusion-backwards-for-2024/"><u>YT Bidirectional  Navigating the Queue From the Conclusion Backwards for 2024</u></a></li>
</ul></div>
