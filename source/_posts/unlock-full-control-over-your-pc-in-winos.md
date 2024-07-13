---
title: Unlock Full Control Over Your PC in WinOS
date: 2024-07-12T17:18:54.341Z
updated: 2024-07-13T17:18:54.341Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlock Full Control Over Your PC in WinOS
excerpt: This Article Describes Unlock Full Control Over Your PC in WinOS
keywords: PC Mastery WinOS,Gain WinOS Control,WinOS User Ownership,Secure Windows OS,Enhance WinOS Security,Optimize PC with WinOS,Tighten WinOS Access
thumbnail: https://thmb.techidaily.com/70a221261e83ff3179ef93192d51afbff1f7257579ffa960f9e7a085032e4b04.png
---

## Unlock Full Control Over Your PC in WinOS

 Administrator accounts offer extensive control over the system, granting the ability to manage settings, install software, and access critical system files. However, occasionally, users may encounter issues when attempting to switch from their standard user account to an admin account.

 Below, we explore various effective fixes to resolve this problem permanently.

## 1\. Modify the User Account Control (UAC) Settings

 User Account Control (UAC) is a security feature that prevents users from making unauthorized changes to the computer. It typically appears as a dialog box, prompting you to confirm the action by clicking the "Yes" or "No" option.

 In the case of this specific error, you might be facing the issue because of misconfigured or incorrect UAC settings. Here is how you can ensure UAC is enabled and set to a suitable level:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "control" in the text field and click **Enter**.
3. In the following window, navigate to **System and Security** \> **Security and Maintenance**.
4. Choose **Change User Account Control settings**.
5. In the dialog that appears, move the slider to the desired level (recommended: notify only when apps try to make changes to your computer) and click **OK** to save the changes.  
![The User Account Control Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-uac-settings.jpg)

 Once done, close the Command Prompt and check if the issue is resolved.

## 2\. Activate the Built-In Administrator Account
![Enable the built-in admin account in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-built-in-admin-account.jpg)

 Windows comes with a hidden administrator account that can allow you to have full control over the system. This account is typically disabled by default for security reasons but if you are having trouble switching to an administrator account, enabling the built-in Administrator account can be beneficial.

 Here's how to activate the built-in Administrator account:

1. Press the **Win** \+ **R** keys to open Run.
2. Type "cmd" in Run and press the **Ctrl** \+ **Shift** \+ **Enter** to open Command Prompt as an administrator.
3. Click **Yes** in the following dialog.
4. Once you are in the Command Prompt, type the command below and hit **Enter** to execute it:  
net user administrator /active:yes
5. After the command executes successfully, you should see a message in Command Prompt confirming it. If you want to set a password for this administrator account, execute the following command:  
​​​​​​​net user administrator *
6. Follow the prompts to set a new password.

 Alternatively, you can also use the Local Users and Groups management console to make these changes. Here is how you can do that:

1. Open Run by pressing **Win** \+ **R** keys together.
2. Type "lusrmgr.msc" in Run and click **Enter**.
3. In the left pane, expand **Users** and right-click on **Administrator**.
4. Choose **Properties** from the context menu.
5. Uncheck the **Account is disabled** option and click **OK**.  
![Enable the built-in admin account in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-admin-account.jpg)

 This should successfully activate the built-in administrator account. You can now access the Settings app again and check if you can switch the account type easily now.

## 3\. Make the Changes in Safe Mode

 It's possible that a background process or application is causing interference with system processes, which could be preventing you from switching to an administrator account.

 To determine if this is the cause of the issue, you can [boot your computer into Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/). Safe Mode launches the system with minimal drivers and programs, disabling any background processes that may be contributing to the problem. In this diagnostic state, you should be able to switch to the administrator account if such processes were previously causing the obstruction.

 Once you have booted into Safe Mode, try performing the action that was initially causing the problem. If it does not occur in Safe Mode, you can try eliminating the culprit by either uninstalling it manually or [using the System Restore utility](https://www.makeuseof.com/tag/system-restore-factory-reset-work-windows-10/) to revert to a stable, error-free state.

## 4\. Disable Your Antivirus Program
![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 If you are using a third-party security program on your computer, it might be preventing you from switching to an admin account because of security reasons.

 In this case, you can try to temporarily disable your security program and see if that helps you switch to an administrator account. You can do this by right-clicking on your antivirus icon in the taskbar and choosing the **Shields Control** \> **Disable until the computer is restarted** option.

 If this works, you can consider [switching to a better security program for your Windows](https://www.makeuseof.com/windows-11-antivirus-apps/) to prevent issues like this from occurring in the future.

## 5\. Create a New Administrator Account

## Finally, if none of the methods above have helped you, you can try creating a new administrator account in Windows

 This will help with any corruption issues in the current account, as well as help you determine if the permission-related problems were user-specific. It is, however, important to note that you will require admin access to the system to proceed with the steps in this method, so you must enable the built-in administrator account beforehand.

 Once that is done, here is how you can proceed:

1. Open the Settings app by pressing the **Win** \+ **I** keys together.
2. Choose **Accounts** from the left pane and click on **Other users**.
3. Hit the **Add account** button for **Add other users** in the following window.  
![The Add account option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-account-option.jpg)
4. Select **I don’t have this person’s sign-in information** \> **Add a user without a Microsoft account**.
5. In the next dialog, enter details like the username and password for the new account.
6. Click **Next**.
7. Once the account is created, click on the **Change account type** button associated with the newly created account.  
![The Change account type button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-change-account-type-option.jpg)
8. Expand the Account type dropdown and choose **Administrator** from the menu.
9. Click **OK** to save the changes.

 You can now log into the new administrator account and begin using it.

## Enjoy Administrative Access to Your Windows System

 The inability to change an account type to Administrator in Windows can be caused by a number of reasons, such as misconfigured User Account Control (UAC) settings or underlying system issues. However, with the right troubleshooting methods, you can overcome the account type change challenge and enjoy administrative access to the system.

 Below, we explore various effective fixes to resolve this problem permanently.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-capture-cinematic-moments-seamlessly-across-pcs-and-smartphones/"><u>2024 Approved  Capture Cinematic Moments Seamlessly Across PCs & Smartphones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-dims-handbook-for-windows-11-repair/"><u>The Complete DIMS Handbook for Windows 11 Repair</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-nostalgic-gaming-empathetic-3ds-on-android-devices/"><u>[New] In 2024, Nostalgic Gaming  Empathetic 3DS on Android Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solve-stuck-sheets-and-frozen-viewport-in-excel/"><u>Solve Stuck Sheets and Frozen Viewport in Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-full-capability-of-windows-11-with-multi-display-setup/"><u>Unlock the Full Capability of Windows 11 With Multi-Display Setup</u></a></li>
<li><a href="https://win11.techidaily.com/perfecting-visual-harmony-with-windows-desktop-wallpapers/"><u>Perfecting Visual Harmony with Windows Desktop Wallpapers</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-2024-approved-redefine-creativity-in-tiktok-videos-through-backdrops/"><u>[New] 2024 Approved  Redefine Creativity in TikTok Videos Through Backdrops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-share-failures-on-geforce-experience-for-w10w11/"><u>Tackling Share Failures on GeForce Experience for W10/W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-file-management-with-windows-autodelete-feature/"><u>Simplifying File Management with Windows' AutoDelete Feature</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-learn-how-everything-works-on-realme-gt-3-drfone-by-drfone-virtual-android/"><u>Life360 Learn How Everything Works On Realme GT 3 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-steam-online-connectivity-failures-w11/"><u>Addressing Steam Online Connectivity Failures W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-and-tricks-to-fix-error-0x800700e1-in-windows-11/"><u>Tips & Tricks to Fix Error 0X800700E1 in Windows 11</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-apple-iphone-6s-plus-to-the-latest-ios-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade Apple iPhone 6s Plus to the Latest iOS Version? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-samsung-galaxy-f54-5g-by-phone-number-drfone-by-drfone-virtual-android/"><u>How to Track Samsung Galaxy F54 5G by Phone Number | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speeding-up-a-halted-download-the-windows-method/"><u>Speeding up a Halted Download: The Windows Method</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-adopting-sudo-can-transform-your-windows-experience/"><u>Why Adopting Sudo Can Transform Your Windows Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-internal-audio-error-in-audacity-win-11-and-11/"><u>Tackling Internal Audio Error in Audacity, Win 11 & 11</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-oppo-reno-11-5g-drfone-by-drfone-virtual/"><u>In 2024, 9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Oppo Reno 11 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-tour-to-windows-booting-point/"><u>A Quick Tour to Windows' Booting Point</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-device-diversity-into-a-single-note-world/"><u>Transforming Device Diversity Into a Single Note World</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cant-scroll-in-microsoft-excel-for-windows-try-these-fixes/"><u>Can't Scroll in Microsoft Excel for Windows? Try These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-security-settings-through-gpo/"><u>Unveiling Windows Security Settings Through GPO</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/secrets-for-skillful-extraction-of-superior-quality-videos-for-2024/"><u>Secrets for Skillful Extraction of Superior Quality Videos for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-lava-blaze-curve-5g-drfone-by-drfone-virtual-android/"><u>Will Pokémon Go Ban the Account if You Use PGSharp On Lava Blaze Curve 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-clean-boot-a-beginners-approach/"><u>Windows 11 Clean Boot: A Beginner's Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-tackle-windows-package-unopenable-issue-effectively/"><u>Steps to Tackle Windows Package Unopenable Issue Effectively</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-in-2024-unlock-vlcs-hidden-feature-playing-videos-in-slow-motion-made-easy/"><u>New In 2024, Unlock VLCs Hidden Feature Playing Videos in Slow Motion Made Easy</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-essential-list-the-10-leading-vimeo-downloaders-web/"><u>[New] 2024 Approved  Essential List  The 10 Leading Vimeo Downloaders Web</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/premium-tools-for-saving-your-live-video-memories-for-2024/"><u>Premium Tools for Saving Your Live Video Memories for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-google-play-services-keeps-stopping-on-tecno-pova-5-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What to Do if Google Play Services Keeps Stopping on Tecno Pova 5 Pro | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/dissecting-digital-communication-discord-versus-skype-for-2024/"><u>Dissecting Digital Communication  Discord Versus Skype for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-display-embrace-tiled-workspace/"><u>Streamline Your Display: Embrace Tiled Workspace</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-entrepreneurs-guide-free-business-template-plugins-for-2024/"><u>[Updated] Entrepreneur's Guide  Free Business Template Plugins for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/dose-life360-notify-me-when-someone-checks-my-location-on-lava-yuva-2-pro-drfone-by-drfone-virtual-android/"><u>Dose Life360 Notify Me When Someone Checks My Location On Lava Yuva 2 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-detailed-manual-for-individualized-keybindings-in-win11/"><u>A Detailed Manual for Individualized Keybindings in Win11</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-short-cuts-big-impact-top-editors-for-youtube-short-videos-on-mobile-for-2024/"><u>[Updated] Short Cuts, Big Impact  Top Editors for YouTube Short Videos on Mobile for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-wizardry-learn-hotkeys-to-manage-your-pc/"><u>Windows Wizardry: Learn Hotkeys to Manage Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-5-tactics-reactivating-windows-defender-protection-mechanism/"><u>Top 5 Tactics: Reactivating Windows Defender Protection Mechanism</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-next-level-designers-post-acid-tools-explored/"><u>[Updated] Next-Level Designers  Post-ACID Tools Explored</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-premier-game-recorder-picks-excluding-the-mainstream-one/"><u>In 2024, Premier Game Recorder Picks Excluding the Mainstream One</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-discover-the-best-digital-stores-for-authentic-wildlife-audio/"><u>Updated In 2024, Discover the Best Digital Stores for Authentic Wildlife Audio</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-top-digital-scrapbooking-tools-for-photos-and-videos/"><u>2024 Approved Top Digital Scrapbooking Tools for Photos and Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-wasd-isolation-necessity-or-concern/"><u>Understanding WASD Isolation: Necessity or Concern?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-incorrect-windows-duo-software-setup/"><u>Steps to Rectify Incorrect Windows Duo Software Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convergence-of-ios-and-windows-using-apple-maps-effectively/"><u>Convergence of iOS and Windows: Using Apple Maps Effectively</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-most-downloaded-and-loved-android-apps/"><u>New In 2024, Most Downloaded and Loved Android Apps</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-iphone-14-pro-ios-system-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair iPhone 14 Pro iOS System? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-updater-setback-error-0x800f080a-on-windows-systems/"><u>Bypassing Updater Setback Error 0X800F080A on Windows Systems</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-2023s-leading-covert-video-download-apps-1-8/"><u>[Updated] In 2024, 2023'S Leading Covert Video Download Apps #1-8</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-the-essential-guide-to-premium-discord-emoji-tools/"><u>[New] 2024 Approved  The Essential Guide to Premium Discord Emoji Tools</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-nokia-c12-plus-drfone-by-drfone-virtual-android/"><u>In 2024, How PGSharp Save You from Ban While Spoofing Pokemon Go On Nokia C12 Plus? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/confusion-in-xbox-app-gaming-placement/"><u>Confusion in Xbox App Gaming Placement</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-camstudio-screen-capturing-a-comprehensive-analysis-users-for-2024/"><u>[New] CamStudio Screen Capturing  A Comprehensive Analysis Users for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-flawless-screen-capture-s-assassins-creed-odyssey-for-2024/"><u>[Updated] Flawless Screen Capture 'S Assassin's Creed Odyssey for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-unifiedvision-mixer-hub/"><u>[Updated] 2024 Approved  UnifiedVision Mixer Hub</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-mouseclicklock-usability-on-windows-systems/"><u>Boosting MouseClickLock Usability on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-app-start-issue-qt-plugin-not-available/"><u>Troubleshooting App Start Issue: Qt Plugin Not Available</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-hidden-time-display-on-windows-bar/"><u>Setting Up Hidden Time Display on Window's Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/can-malware-scanners-hang-up-compute-resources/"><u>Can Malware Scanners Hang Up Compute Resources?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-a-new-surname-username-alteration-in-windows-11/"><u>Securing a New Surname: UserName Alteration in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-center-personalizing-folders-through-comments-in-11/"><u>Command Center: Personalizing Folders Through Comments in 11</u></a></li>
</ul></div>
