---
title: Understanding and Removing Windows ~BT Directories Effectively
date: 2024-08-16T02:42:20.756Z
updated: 2024-08-17T02:42:20.756Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Understanding and Removing Windows ~BT Directories Effectively
excerpt: This Article Describes Understanding and Removing Windows ~BT Directories Effectively
keywords: Windows BT Directory Cleaning,BT Directories in Windows,Remove Windows Directories,Windows Directory Structure,Effective BT Removal Tools,Delete Windows BT Folders,Optimize Windows ~BT Storage
thumbnail: https://thmb.techidaily.com/c2838348b746990136e05e229d4b40bfea769dde8bb07eb48712190cd8997d0c.jpg
---

## Understanding and Removing Windows ~BT Directories Effectively

 Deleting the hidden "$Windows.\~BT" folder and recovering gigabytes of space on your hard drive is tempting. But what is this cryptically named folder for, and how critical is it to your Windows installation?

## What Is the “$Windows.\~BT” Folder, and Should You Delete It?

 Windows creates the "$Windows.\~BT" folder when you upgrade the operating system to a newer build. This folder contains all the essential files for the upgrade process, like temporary installation files and logs from the previous Windows installation.

 Windows automatically removes the "$Windows.\~BT" folder after 10 days. As manually deleting this folder will [remove old Windows installation files](https://www.makeuseof.com/tag/delete-old-windows-update-files/), you won't be able to roll back to the previous Windows build using the **Go back** option in the Recovery menu within that time (for example, to [downgrade from Windows 11 to Windows 10](https://www.makeuseof.com/windows-11-downgrade-to-windows-10/)). Hence, you should only get rid of this folder if you are satisfied with the current Windows build on your PC. You can also safely delete the massive folder if Windows fails to do it automatically after the grace period.

 But you shouldn't just delete this hidden folder like any other folder on the desktop. Instead, you should turn to the Disk Cleanup tool or the Command Prompt.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
## How to Find and Delete the "$Windows.\~BT" Folder

 As "$Windows.\~BT" is a hidden folder, you need to [configure Windows to show hidden files and folders](https://www.makeuseof.com/windows-11-show-hidden-files-folders/) to find it in File Explorer. Once you do, the **C:\\$Windows.\~BT** directory will become visible.

 You can’t delete the "$Windows.\~BT" folder directly, though. To do so, you need to run the Disk Cleanup tool. Here's how:

1. Press **Win + R** to open the Run dialog box.
2. Type **cleanmgr** in the box and press **Enter**.
3. Use the dropdown menu to select the system drive (usually **C:**) and click **OK**.
4. Click the **Clean up system files** button.
5. Under **Files to delete**, use the checkboxes to select these options: **Previous Windows Installations**, **Windows Update Cleanup**, **Windows upgrade log files**, **Temporary Windows installation files**, and **Temporary files**.
6. Click **OK**.
7. Choose **Delete Files** to confirm.  
![Delete the $Windows.~BT Folder Using the Disk Cleanup Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/delete-the-windows-bt-folder-using-the-disk-cleanup-tool.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the "$Windows.\~BT" folder shows up even after you run the Disk Cleanup tool, you'll need to execute a few commands in Command Prompt. For that, [open Command Prompt with administrative rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) and then run the following commands one by one.

`takeown /F C:\$Windows.~BT\* /R /A
icacls C:\$Windows.~BT\*.* /T /grant administrators:F
rmdir /S /Q C:\$Windows.~BT\`

 Once you run the above commands, the "$Windows.\~BT" folder will be deleted for good.

 Now that you understand the purpose of the "$Windows.\~BT" folder, you can decide how to handle it. Beyond the "$Windows.\~BT" folder, you may also come across folders like "Windows.old," "$WinREAgent," "$SysReset," and others which can also be deleted safely using the Disk Cleanup tool.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://eaxpv-info.techidaily.com/new-global-viewership-kings-youtubes-viral-royalty-for-2024/"><u>[New] Global Viewership Kings  YouTube's Viral Royalty for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-obs-full-screen-troubles-now-under-control/"><u>[New] Obs Full Screen Troubles  Now Under Control</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-pro-tips-for-capturing-360-degree-fisheye-photos/"><u>[New] Pro Tips for Capturing 360-Degree Fisheye Photos</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-10-free-youtube-playlist-downloaders-onlinepcandroidios2/"><u>[Updated] 2024 Approved  10 FREE YouTube Playlist Downloaders [Online/PC/Android/iOS]2</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-boosting-brand-visibility-essential-insta-highlight-upgrades-for-2024/"><u>[Updated] Boosting Brand Visibility  Essential Insta Highlight Upgrades for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-unlock-the-secret-to-massive-engagement-3-top-tips-for-making-powerful-two-pov-reaction-videos-on-youtube/"><u>[Updated] Unlock the Secret to Massive Engagement  3 Top Tips for Making Powerful Two-POV Reaction Videos on YouTube</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-your-guide-to-preserving-live-streams-on-periscope/"><u>2024 Approved  Your Guide to Preserving Live Streams on Periscope</u></a></li>
<li><a href="https://extra-hints.techidaily.com/audiovisual-amplification-harness-no-cost-tools-for-dynamic-voice-effects/"><u>Audiovisual Amplification  Harness No-Cost Tools for Dynamic Voice Effects</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-or-see-text-messages-what-can-you-do-with-life360-on-realme-gt-neo-5-se-drfone-by-drfone-virtual-android/"><u>Can Life360 Track Or See Text Messages? What Can You Do with Life360 On Realme GT Neo 5 SE? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-the-heart-of-your-system-pc-manager-for-w11/"><u>Configuring the Heart of Your System: PC Manager for W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-spontaneous-file-explorer-opens/"><u>Disabling Spontaneous File Explorer Opens</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/easy-guide-how-to-bypass-realme-narzo-60-pro-5g-frp-android-10111213-by-drfone-android/"><u>Easy Guide How To Bypass Realme Narzo 60 Pro 5G FRP Android 10/11/12/13</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/easy-to-use-games-recorders-ranked-no-1-10-for-2024/"><u>Easy-to-Use Games Recorders Ranked No. 1-10 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-efficiency-with-these-5-must-have-apps-on-windows-11/"><u>Enhance Efficiency with These 5 Must-Have Apps on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-to-windows-11s-photo-application-blurring-feature/"><u>Expert Guide to Windows 11'S Photo Application Blurring Feature</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-messages-files-from-samsung-galaxy-a54-5g-by-fonelab-android-recover-messages/"><u>How To  Restore Missing Messages Files from Samsung Galaxy A54 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-increase-the-performance-of-android-studio-on-windows/"><u>How to Increase the Performance of Android Studio on Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-pictures-from-gt-3-by-fonelab-android-recover-pictures/"><u>How to Rescue Lost Pictures from GT 3?</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-reset-apple-id-and-apple-password-from-apple-iphone-se-2020-by-drfone-ios/"><u>How to Reset Apple ID and Apple Password From Apple iPhone SE (2020)</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-best-pokemons-for-pvp-matches-in-pokemon-go-for-apple-iphone-15-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, Best Pokemons for PVP Matches in Pokemon Go For Apple iPhone 15 Pro Max | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-driveease-expert-review/"><u>In 2024, DriveEase Expert Review</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-easily-stream-facebook-live-chats-with-roku/"><u>In 2024, Easily Stream Facebook Live Chats with Roku</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-pictuner-expert-strategies-in-image-distortion/"><u>In 2024, PicTuner  Expert Strategies in Image Distortion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-machine-how-to-optimize-windows-11-settings/"><u>Master Your Machine: How to Optimize Windows 11 Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-classic-diablo-a-beginners-guide/"><u>Mastering Classic Diablo: A Beginner's Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-resolution-of-windows-error-0x80040610-for-outlook/"><u>Mastering the Resolution of Windows Error 0X80040610 for Outlook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-administrative-roadblocks-during-software-setup/"><u>Navigating Administrative Roadblocks During Software Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-lowered-cpu-demand-for-windows-hosts/"><u>Navigating Lowered CPU Demand for Windows Hosts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-code-0xa00f4289-in-wincams/"><u>Navigating Through Code 0xA00F4289 in WinCams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-to-uninstall-quickly-in-windows-11/"><u>Navigating to Uninstall Quickly in Windows 11</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-the-ultimate-guide-to-3d-animation-software-free-and-paid/"><u>New In 2024, The Ultimate Guide to 3D Animation Software Free and Paid</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-non-signed-file-barrier-for-system-upgrades/"><u>Overcoming Non-Signed File Barrier for System Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-bypass-oculus-setup-failures-in-windows-1110/"><u>Quick Guide to Bypass Oculus Setup Failures in Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-languages-change-navigating-hotkeys-in-windows-11-and-11-pro/"><u>Quick Languages Change: Navigating Hotkeys in Windows 11 & 11 Pro</u></a></li>
<li><a href="https://sound-issues.techidaily.com/realtek-hd-audio-troubles-restoring-plugged-in-status/"><u>Realtek HD Audio Troubles: Restoring Plugged In Status</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rebooting-to-standard-power-plans-guide-for-win-11/"><u>Rebooting to Standard Power Plans: Guide for Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sidestep-common-snip-and-sketch-screenshot-hurdles-4-fixes/"><u>Sidestep Common Snip & Sketch Screenshot Hurdles: 4 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silent-data-exchange-safeguarding-files-across-ws11w10/"><u>Silent Data Exchange: Safeguarding Files Across WS11/W10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-print-again-in-win11/"><u>Step-By-Step Guide to Print Again in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-missing-d3dx939dll-in-win11/"><u>Steps to Fix Missing D3DX9_39.dll in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-update-processes-context-menu-update-option-for-win11-users/"><u>Streamlining Update Processes: Context Menu Update Option for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-dxgi-failure-in-windows-fix-for-removed-devices/"><u>Tackling DXGI Failure in Windows: Fix for Removed Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-synchronized-note-taking-in-windows-11/"><u>The Art of Synchronized Note-Taking in Windows 11</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-best-free-language-learning-apps-of-the-year-2024-our-top-picks/"><u>The Best Free Language-Learning Apps of the Year 2024 - Our Top Picks!</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-tech-the-comprehensive-guide-to-computer-hardware/"><u>Tom's Tech: The Comprehensive Guide to Computer Hardware</u></a></li>
<li><a href="https://some-skills.techidaily.com/top-30-latest-forgotten-free-speech-transcription-tools-for-macos-for-2024/"><u>Top 30 Latest, Forgotten Free Speech Transcription Tools for macOS for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-full-potential-of-policy-editor-in-windows-11/"><u>Unlock the Full Potential of Policy Editor in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-smartphone-potential-as-windows-microphone/"><u>Unlocking Smartphone Potential as Windows Microphone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-system-details-locate-windows-ip-and-mac-via-powershell/"><u>Unveiling System Details: Locate Windows' IP and MAC via Powershell</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-cant-you-see-a-drive-letter-on-your-windows-machine/"><u>Why Can't You See a Drive Letter on Your Windows Machine?</u></a></li>
<li><a href="https://win11.techidaily.com/winning-back-access-to-steam-remote-play/"><u>Winning Back Access to Steam Remote Play</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/your-ultimate-guide-to-protecting-images/"><u>Your Ultimate Guide to Protecting Images</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>