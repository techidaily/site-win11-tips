---
title: Quick Tricks to Overcome PIN Failures in Win10/Win11
date: 2024-07-12T17:00:46.081Z
updated: 2024-07-13T17:00:46.081Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Tricks to Overcome PIN Failures in Win10/Win11
excerpt: This Article Describes Quick Tricks to Overcome PIN Failures in Win10/Win11
keywords: PinFailureSolutions,WindowsLoginTricks,FixPinFailWindowsOS,BypassPinErrors,Win10/Win11ResetPIN,SecurePINRecovery,PINOverrideTips
thumbnail: https://thmb.techidaily.com/ff65255da837891834ddbec118debc41ab0f1d1e57de67c2dd583540d5810764.jpg
---

## Quick Tricks to Overcome PIN Failures in Win10/Win11

 Is your Windows Hello PIN not being accepted by Windows? In most cases, it occurs when you enter the wrong PIN. Other factors that could contribute to this issue include corruption of the Ngc folder, a problem with your Microsoft or local accounts, or misconfigured PIN settings in the Group Policy Editor.

 Likewise, not updating your operating system for long, being infected with malware, or corrupted system files can also prevent your login PIN from working. If you're having trouble logging in to your device using your Windows Hello PIN, give the following solutions a shot.

## 1\. Ensure You Aren't Entering the Incorrect PIN

 You could simply be entering the wrong PIN, which is the first possible cause of your PIN not working. To eliminate this possibility, reset your PIN once.

 Your computer must be connected to an active internet connection to reset your PIN. Therefore, turn on your computer and ensure that the internet is connected. To reset your PIN, go to the profile's login page and click on **I forgot my PIN**.

![Clicking on I Forgot My PIN in Windows Home Screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/Clicking-on-I-Forgot-My-PIN-in-Windows-Home-Screen.jpg)

 You can either reset the PIN by verifying your identity with your Microsoft account password or choose an alternative sign-in option by clicking **Send code**, which sends a code to your email address.

![Windows Notifying About Receiving the Code to Reset Pin on the Windows Login Screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/Windows-Notifying-About-Receiving-the-Code-to-Reset-Pin-on-the-Windows-Login-Screen-Censor-1.jpg)

 If you select the latter option, enter the code you received by email and click **Continue**. Windows will direct you to enter a new PIN here, so enter it, confirm it once, and click **OK**.

![Adding a New Pin to Change the Old One in Windows Login Screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/Adding-a-New-Pin-to-Change-the-Old-One-in-Windows-Login-Screen.jpg)

 Restart your computer once more, add your new PIN on the login screen, and try logging in again to make sure it was the wrong PIN that wasn't letting you enter the computer previously. You are good to go if you can log in this time - just don't forget your new PIN.

 If the PIN again does not work after resetting and you are sure that the PIN you are entering is correct, the problem may reside elsewhere. Therefore, use an alternate way to log in to your account and then rule out other possibilities.

## 2\. Sign-In Using Alternative Methods

 If resetting the PIN from the login screen does not resolve the issue, you can use your account password instead. To do that, follow the below steps:

1. Click **Sign-in options** to view other options for logging in.
2. Click the **key icon**, which is usually located on the left.  
![sign in options windows 11 password](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sign-in-options-windows-11-password.jpg)
3. Type the password associated with your account here.

 Once logged in, you can start applying the remaining fixes.

 If you don't remember your account password, you can reset it just like you can your PIN. Unlike resetting the PIN, resetting the password mostly goes smoothly and lets you sign in.

## 3\. Delete the Ngc Folder in Windows

 Windows stores all your PIN-related settings in this folder, so if the OS isn't accepting your PIN, which is correct, you should delete this folder. This process will wipe out all PIN-related data from the OS. You can then set up a new PIN, which should work fine.

 You can delete the Ngc folder by following these steps:

1. Log in to your administrator account.
2. Navigate to **C: drive > Windows> ServiceProfiles > LocalService > AppData > Local> Microsoft**.
3. Locate the Ngc folder, right-click on it, and hit **Delete**.  
![Deleting Ngc Folder in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/Deleting-Ngc-Folder-in-Windows-10-Edit.jpg)

 Navigate to **Settings > Accounts > Sign-in options** to set up a new PIN after deleting the old one. Afterward, click on **Windows Hello PIN**, add a new PIN, and hopefully, the PIN will start working on your operating system.

![Windows Hello PIN In Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/3-Windows-Hello-PIN-In-Windows-Settings-App.jpg)

 If this fix also doesn't resolve the issue, it lies somewhere else that needs to be investigated further.

## 4\. Rule Out User Account Specific Issues

 When troubleshooting PIN issues, it's essential to rule out account-specific problems first. To begin with, check that the problem does not persist on a single Microsoft account. The best way to confirm this is to switch to a local account. To do that, follow the below steps:

1. Open the Windows Settings app.
2. Go to **Accounts**.
3. Navigate to **Your info** in the left-sidebar.
4. Click on **Sign in with a local account instead**.  
![changing accounts settings in windows 10 settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/changing-accounts-settings-in-windows-10-settings-app-edit.jpg)
5. Click on **Next**.
6. Enter your PIN.
7. Set up your local account by adding your username and password.
8. Once done, hit **Next**.  
![Setting Up Local Account in Windows 10 Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/2-Setting-Up-Local-Account-in-Windows-10-Settings-App.jpg)
9. Click on **Sign out and finish**.

 By following the above steps, you will return to the login screen. Type in your PIN again to confirm it works. If it does, it's your Microsoft account that is to blame. Creating another user account and checking if the PIN works there could help confirm that.

 Therefore, if the issue originates from your Microsoft user account, you should copy your files to the new account and start using the new account permanently.

 If the PIN does not work on any account, move on to the next fix.

## 5\. Tweak PIN Sign-In Settings in Group Policy Editor

 When the convenience PIN sign-in setting in the Group Policy Editor is disabled, the PIN will not work. Therefore, it's essential to ensure it's not causing the problem during sign-in.

 Some Windows versions, however, might not have this feature. If this applies to you as well, skip this step.

 Follow the below steps to adjust the settings in the Group Policy Editor:

1. Search for the **Run** app in the Windows search bar.
2. Type **gpedit.msc** and click on **OK**.
3. Navigate to **Administrative Templates > System > Logon**.
4. In the right-hand pane, locate and double-click on **Turn on convenience PIN sign-in setting**.
5. Check the **Enabled** checkbox, click **Apply**, and hit **OK**.

 If the setting is already enabled, continue to apply the remaining fixes.

 Group Policy Editor isn't available in the Windows Home edition by default. You can skip this fix if you're using the Home edition or try [alternative ways to get the Group Policy Editor](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

## 6\. Update or Downgrade Your OS

 According to [Microsoft support helpers](https://answers.microsoft.com/en-us/windows/forum/all/pin-not-working-on-windows-10/d444ebfb-d643-40b5-be62-1569454118d1), one of the possible causes of PIN not working on Windows may be recent updates. If you remember doing an update recently, you need to [roll the update back](https://www.makeuseof.com/tag/regret-update-windows-10-revert-version/).

 Conversely, if you haven't updated your computer for quite some time, maybe the problem stems from an outdated Windows OS. In that case, follow the below steps to update your computer:

1. Open the Windows Settings app.
2. Go to **Update & Security**.
3. Navigate to **Windows Update** in the left sidebar.
4. Click on **Check for updates** box.  
![Checking for Windows PC updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/9-Checking-for-Windows-PC-updates.jpg)

 Windows will automatically check for the latest updates and update itself if necessary. After your OS has been updated, try logging in again with your PIN if it works this time.

 If you're experiencing this issue on Windows 11, see our guide on [how to install Windows 11 updates](https://www.makeuseof.com/windows-11-install-updates/) to update your system. If you've started experiencing this issue after installing an update, follow our guide on [how to uninstall updates in Windows 11](https://www.makeuseof.com/windows-11-uninstall-updates/) and uninstall the most recent updates you installed.

 If the issue persists, run a malware scan to rule out the possibility of malware interference.

## 7\. Turn Off Your Antivirus and Run a Malware Scan

 Possible interference from antivirus may also result in your PIN being rejected. To prevent this from happening, temporarily turn off any third-party antivirus you're using. If turning off the third-party security suite fixes the problem, turn it off permanently.

 In addition, you can [temporarily disable Windows Defender](https://www.makeuseof.com/how-to-turn-off-windows-defender/) (now known as Microsoft Defender), the built-in security suite, to ensure that it's not the culprit. Remember to re-enable the security suite, as turning it off for too long can expose your device to malware.

 Aside from that, malware infections can also impair many system functions. Thus, it is imperative to rule out this possibility. You can easily do this by [running a Microsoft Defender offline scan](https://www.makeuseof.com/how-to-remove-malware-using-microsoft-defenders-offline-scan/). By scanning the system, you can ensure that no hidden malware is affecting its performance.

## 8\. Run an SFC Scan

 When you remove malware from your computer, make sure it hasn't corrupted any Windows files that might have caused the issue at hand.

 The easiest way to do this is to run an SFC scan. The scan automatically searches for corrupted files and replaces them with a cached copy. You can check out how to use the SFC tool in our guide on [how to repair corrupt Windows files with its built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

 If running the SFC scan does not fix the problem, you can [revert your system to an earlier restore point](https://www.makeuseof.com/use-system-restore-windows/) where the PIN was working. You can only do this if you've already created a restore point. Otherwise, it's impossible.

## PIN Still Isn’t Working on Windows?

 After you have tried all fixes listed above and the issue persists, consider restoring your computer to a previous point where the PIN was working fine. If that doesn't solve the problem either, it's best to factory reset your computer as a last resort.

 Likewise, not updating your operating system for long, being infected with malware, or corrupted system files can also prevent your login PIN from working. If you're having trouble logging in to your device using your Windows Hello PIN, give the following solutions a shot.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/swift-fixes-for-microsoft-store-crash-code-error-0x80072efd/"><u>Swift Fixes for Microsoft Store Crash Code Error 0X80072EFD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-workflow-with-top-3d-painting-shortcuts/"><u>Streamline Your Workflow with Top 3D Painting Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/update-with-ease-a-guide-for-surface-computer-owners/"><u>Update with Ease: A Guide for Surface Computer Owners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-steam-disk-write-failures-effectively/"><u>Tackling Windows Steam Disk Write Failures Effectively</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/explore-laughter-tears-fusion-the-best-ig-accounts-ever/"><u>Explore Laughter-Tears Fusion  The Best IG Accounts Ever</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-2024-approved-top-10-vocal-remover-software-for-every-budget-and-skill-level/"><u>Updated 2024 Approved Top 10 Vocal Remover Software for Every Budget and Skill Level</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-1011-zoom-glitch-1132/"><u>Overcoming Windows 10/11 Zoom Glitch 1132</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-xbox-game-pass-error-code-0x00000001-on-windows-os/"><u>Troubleshooting Xbox Game Pass Error Code 0X00000001 on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-effortlessly-bypass-pin-in-windows-11-projections/"><u>Navigate Effortlessly: Bypass PIN in Windows 11 Projections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-your-downloads-with-these-5-windows-clients/"><u>Maximize Your Downloads with These 5 Windows Clients</u></a></li>
<li><a href="https://games-able.techidaily.com/strategies-to-resolve-xbox-one-joystick-faults/"><u>Strategies to Resolve Xbox One Joystick Faults</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-uninstall-guide-enhancing-your-workflow-in-windows/"><u>The Ultimate Uninstall Guide: Enhancing Your Workflow in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-copilot-unveiled-revolutionizing-the-development-process/"><u>Microsoft Copilot Unveiled: Revolutionizing the Development Process</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-cross-platform-connections-effortless-insta-facebook-linkup/"><u>[Updated] 2024 Approved  Cross-Platform Connections  Effortless Insta-Facebook Linkup</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-how-to-leverage-different-gadgets-recording-and-saving-youtube-livestayere/"><u>2024 Approved  How To Leverage Different Gadgets  Recording and Saving YouTube Livestayere</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-transparent-taskbars-on-win11/"><u>Mastering the Art of Transparent Taskbars on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-the-power-of-combined-android-and-windows-11-displays/"><u>Leveraging the Power of Combined Android & Windows 11 Displays</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-vpn-connections-failed-on-windows/"><u>Troubleshooting VPN Connections Failed on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-your-systems-core-settings/"><u>Navigating Through Your System's Core Settings</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-depth-zoom-techniques-for-exceptional-podcasts/"><u>In-Depth Zoom Techniques for Exceptional Podcasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-tackle-non-responsive-function-keys-for-brighness-on-windows-11/"><u>Methods to Tackle Non-Responsive Function Keys for Brighness on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-fullscreen-glitches-with-ease-on-windows/"><u>Navigate Fullscreen Glitches with Ease on Windows</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-revolutionize-your-channels-thumbnails-with-these-tools/"><u>2024 Approved  Revolutionize Your Channel's Thumbnails with These Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11s-shortcut-for-seamless-sticky-note-entry/"><u>Win11's Shortcut for Seamless Sticky Note Entry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-superuser-access-a-step-by-step-guide/"><u>Mastering Superuser Access: A Step-by-Step Guide</u></a></li>
<li><a href="https://network-issues.techidaily.com/solution-found-windows-1110-no-amd-adapter-error/"><u>[SOLUTION FOUND] Windows 11/10 No AMD Adapter Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leading-the-way-in-qr-decoding-with-your-windows-machine/"><u>Leading the Way in QR Decoding with Your Windows Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinvigorate-dull-volume-options-in-disk-management-tool/"><u>Reinvigorate Dull Volume Options in Disk Management Tool</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-effective-ways-to-fix-checkra1n-error-31-on-apple-iphone-15-pro-by-drfone-ios/"><u>In 2024, Effective Ways To Fix Checkra1n Error 31 On Apple iPhone 15 Pro</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-in-2024-tiktok-video-aspect-ratio/"><u>Updated In 2024, Tiktok Video Aspect Ratio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-reinstate-working-state-of-amd-graphics-suite/"><u>Steps to Reinstate Working State of AMD Graphics Suite</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ways-to-streamline-win11s-print-management-max-52-chars/"><u>Ways to Streamline Win11’s Print Management (Max 52 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-premier-6-task-tracking-tools-for-windows-users/"><u>Unveiling The Premier 6 Task-Tracking Tools for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-outlooks-failing-notification-system-a-user-friendly-approach/"><u>Troubleshooting Outlook's Failing Notification System: A User-Friendly Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-offline-windows-enhancements/"><u>Navigating Offline Windows Enhancements</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-tricks-to-optimize-live-streaming-of-your-snapchat-content/"><u>In 2024, Tricks to Optimize Live Streaming of Your Snapchat Content</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-enabling-autoplay-youtube-without-alerts/"><u>In 2024, Enabling Autoplay YouTube Without Alerts</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-exclusive-round-up-premium-vr-tools/"><u>2024 Approved  Exclusive Round-Up  Premium VR Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-geforce-experience-settings-retrieval-issues/"><u>Overcoming GeForce Experience Settings Retrieval Issues</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-it-infinix-hot-30-5g-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix It Infinix Hot 30 5G Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-correcting-code-0x0000004e-in-os/"><u>Techniques for Correcting Code 0X0000004E in OS</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-mastering-the-art-of-visual-flow-with-kinemaster/"><u>2024 Approved  Mastering the Art of Visual Flow with Kinemaster</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/0-best-youtube-thumbnail-fonts-to-make-your-video-stunning/"><u>[New] 20 Best YouTube Thumbnail Fonts to Make Your Video Stunning</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/failed-to-play-mkv-movies-on-samsung-galaxy-z-fold-5-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Failed to play MKV movies on Samsung Galaxy Z Fold 5</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/how-to-reverse-a-video-in-final-cut-pro-for-2024/"><u>How to Reverse A Video in Final Cut Pro for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedies-for-no-powershell-found-on-your-windows-device/"><u>Remedies for No PowerShell Found on Your Windows Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-win11s-shopping-crash-error-x800704cf/"><u>Tackling Win11's Shopping Crash: Error X800704CF</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11s-next-chapter-begins-with-moment-22h2s-features/"><u>Windows 11'S Next Chapter Begins With Moment #22H2's Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/security-scare-can-you-trust-your-biometric-lock-on-windows/"><u>Security Scare: Can You Trust Your Biometric Lock on Windows?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-restoring-icon-order-in-windows/"><u>Tips for Restoring Icon Order in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-tablet-navigation-a-guide-to-windows-11s-taskbar/"><u>Optimizing Tablet Navigation: A Guide to Windows 11'S Taskbar</u></a></li>
</ul></div>
