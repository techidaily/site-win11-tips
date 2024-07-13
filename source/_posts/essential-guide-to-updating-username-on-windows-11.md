---
title: Essential Guide to Updating Username on Windows 11
date: 2024-07-12T16:31:29.735Z
updated: 2024-07-13T16:31:29.735Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Essential Guide to Updating Username on Windows 11
excerpt: This Article Describes Essential Guide to Updating Username on Windows 11
keywords: Update Windows Username,Win11 User Change,New OS User Edit,Password Update Guide,Windows 11 Login Change,User Name Upgrade Windows,System User Modify Tips
thumbnail: https://thmb.techidaily.com/bb9b7157cde51ae69f835473474384e7538166f2945a00387bf22cab11273e3c.jpg
---

## Essential Guide to Updating Username on Windows 11

 Have you got tired of using the same username for a long time? Were you assigned a random username when you created your account, but now you want to add a personal touch? If you want to change your username for any reason, Windows lets you do it easily. In fact, there are numerous ways to go about this. We have listed some of the simplest ones below.

## Before We Get Started…

 Keep in mind that the first four methods discussed below can only be used to change the username of a local user account. If you use them to change the username of a Microsoft account, the change will be reversed the next time you restart your device.

 So, if you want to change your Microsoft account username, we recommend directly using the last method—changing your username from Microsoft's website. However, if you want to change the username of a local user account, you can use one of the first four methods mentioned below.

## 1\. How to Change Your Username Using the Control Panel

 The Control Panel serves as the central hub in the Windows operating system. From changing the operating system's appearance to configuring the connected hardware, the Control Panel allows users to tailor the entire OS. Among other customizations, users can change their usernames and manage their user accounts effectively.

To change your username using the Control Panel, follow these steps:

1. Type**"Control Panel"** in Windows Search and open the**Control Panel** app. (Check out [other ways to access the Control Panel](https://www.makeuseof.com/windows-open-control-panel/) )
2. Select**Large icons** from the**View by** dropdown menu if it isn't already selected.
3. Go to**User Accounts** .  
![Go to User Accounts in Windows Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/1-go-to-user-accounts-in-windows-control-panel.jpg)
4. Click on**Change your account name** .  
![Click on Change Your Account Name in User Account Settings in Windows Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/2-click-on-change-your-account-name-in-user-account-settings-in-windows-control-panel.jpg)
5. Click**Yes** in the**User Account Control (UAC)** window.
6. In the**New account name** field, type your new username.
7. After that, click on**Change Name** .  
![Click on Change Name After Entering the New Username](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/3-click-on-change-username-after-entering-the-new-username.jpg)
8. For this change to take effect, you need to sign out of your account and sign back in.

## 2\. How to Change Your Username Using the Run Command

 Using the Run command, Windows users can access any location on a computer whose path is known. It eliminates the need to navigate through numerous folders to reach our destination.

 Using this utility, we can access the User Accounts settings via a simple command, "netplwiz," which allows us to access the dedicated account management panel. From there, you can easily change your username.

To change your username using the Run command, follow these steps:

1. Press**Win + R** to launch the**Run command** .
2. Enter**"netplwiz"** in the**Run command** field and press**Enter** .  
![Run Netplwiz Command in the Windows Run Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/4-run-netplwiz-command-in-the-windows-run-command.jpg)
3. Click**Yes** in the**User Account Control (UAC)** window.
4. In the**User Accounts** window, select the user account for which the username needs to be changed.
5. Click on**Properties** .  
![Go to Properties in the User Accounts Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/5-go-to-properties-in-the-user-accounts-window.jpg)
6. In the**General** tab, you'll see your existing username. Rename it to your liking after removing it.
7. Once the new username has been added, click the**Apply** button and**OK** .  
![Click OK After Adding the New Name in the User Accounts Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/6-click-ok-after-adding-the-new-name-in-the-user-accounts-window.jpg)
8. Then, log out of your account, and you'll be greeted with your new username on the sign-in screen when you sign in.

## 3\. How to Change Your Username From Local User and Group Management Tool

 If the "netplwiz" command does not work or gives an error when accessing the user account manager, you can use the local user and group management tool to change the username. This is the easiest way to modify your Windows username, as it allows you to simply rename your username directly—like you rename any folder.

 Here's how to change the username through the local user and group management tool:

1. Press**Win + R** to open the Run command.
2. Type**"lusrmgr.msc"** and press**Enter** .  
![Run lusrmgr.msc Command in Windows Run Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/7-run-lusrmgr-msc-command-in-windows-run-command.jpg)
3. Click**"Yes"** in the**User Account Control (UAC)** window.
4. Select the**Users** tab in the left sidebar.
5. Find your account in the right pane.
6. Right-click the username and click**Rename** .  
![Click Rename by Right-clicking on the Account Name in the Local User and Group Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/8-click-rename-by-right-clicking-on-the-account-name-in-the-local-user-and-group-management-tool.jpg)
7. Enter the new username you want to use.

 Afterward, close the local user and group management tool, sign out of your account once, and you'll see your new username on the sign-in screen.

## 4\. How to Change Your Username Using Windows PowerShell

[Windows Powershell](https://www.makeuseof.com/what-is-windows-powershell/) , an object-oriented automation engine, was designed primarily for IT administrators to automate tasks. Still, its simplicity and ease of use make it worthwhile for laypeople without programming experience.

 Using its built-in cmdlets or writing custom scripts, you can make any changes to your Windows device that you usually make via GUI-based applications and settings. You can also change your username using it.

 To change your username using the Windows PowerShell, follow these steps:

1. Type**"Windows PowerShell"** in Windows Search and open the Windows PowerShell app.
2. Type the following command and press Enter to find your current username:  
Get-LocalUser
3. Add the following command after entering your current username and the one you want to switch to:  
Rename-LocalUser -Name "Enter your current username" -NewName "Enter the new username"
4. Hit**Enter** after adding the above command.  
![Changing Username in Windows Powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/changing-username-in-windows-powershell.jpg)
5. Then, log back into your account after logging out.

## 5\. How to Change Your Profile Username From the Microsoft Website

 If you use a Microsoft account on your computer, change your username on the Microsoft website. To update your profile username on the Microsoft website, follow these steps:

1. Go to your account page on the [Microsoft website](https://account.microsoft.com/account/Account) .
2. Log in to your account if you haven't already.
3. Navigate to the**Your info** menu after logging in.
4. Click the**Edit name** button.  
![Click on Your info and Edit name to Change Username of a Microsoft Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/click-on-your-info-and-edit-name-to-change-username-of-a-microsoft-account.jpg)
5. Remove your current username and add the one you wish to switch to.
6. After that, click**Save** .  
![Click on Save to Change the Username of Microsoft Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/click-on-save-to-change-the-username-of-microsoft-account.jpg)

 Changing the username associated with your Microsoft account may not take effect immediately. Sometimes, you may not see the new username after signing out from your account once, as we do in the other methods. To prevent that from happening, we recommend [restarting your device](https://www.makeuseof.com/windows-restart-methods/) instead of just signing out.

## Change Your Username With Ease

 Your username doesn't have to remain the same for the rest of your life. If you decide to change it, you can use the first four methods listed above to change the current username (of your local user account) to the one you prefer. Regardless of which way you opt, ensure you sign out of your account once. Only then will this change take effect.

 You will need to change the username associated with your Microsoft account from the Microsoft website. Also, remember that changing your username does not automatically change the user profile folder name. Therefore, you'll have to change it separately.


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
<li><a href="https://win11-tips.techidaily.com/revamping-gpos-a-step-by-step-guide-for-windows-users/"><u>Revamping GPOs: A Step-by-Step Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rescue-your-vscode-session-w11/"><u>How to Rescue Your VSCode Session W11</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-frp-from-honor-magic-6-by-drfone-android/"><u>In 2024, How to Bypass FRP from Honor Magic 6?</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-vivo-y78-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Snapchat Location Spoofer to Protect Your Privacy On Vivo Y78 5G? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-apps-and-online-tools-to-track-vivo-v27-phone-withwithout-imei-number-by-drfone-android/"><u>In 2024, Top Apps and Online Tools To Track Vivo V27 Phone With/Without IMEI Number</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/2024-approved-where-can-i-find-crowd-cheering-effect/"><u>2024 Approved Where Can I Find Crowd Cheering Effect?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-online-gaming-prevent-lol-disconnections-in-windows/"><u>Secure Online Gaming: Prevent LoL Disconnections in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-productivity-easy-drive-mapping-for-windows-11-users/"><u>Enhancing Productivity: Easy Drive Mapping for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-flashing-display-issues-on-windows-11/"><u>Quick Fix for Flashing Display Issues on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-reinstate-your-devices-access-post-error-22/"><u>Guide to Reinstate Your Device's Access Post Error 22</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/using-the-best-templates-to-create-slow-motion-videos-on-capcut/"><u>Using the Best Templates to Create Slow Motion Videos on CapCut</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-save-locations-windows-xp78-errors/"><u>Overcoming Save Locations: Windows XP/7/8 Errors</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-add-visual-appeal-with-these-methods-for-yt-video-inclusion-in-ppt/"><u>[New] 2024 Approved  Add Visual Appeal with These Methods for YT Video Inclusion in PPT</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-beyond-fcpx-10-video-editing-solutions-for-every-budget/"><u>In 2024, Beyond FCPX 10 Video Editing Solutions for Every Budget</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-effortless-transition-in-windows-terminals-attention-mode/"><u>Quick Fix: Effortless Transition in Windows Terminal’s Attention Mode</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-alluring-phrase-formulation-device/"><u>[Updated] Alluring Phrase Formulation Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/desktop-configuration-mastery-embedding-this-pc-symbols/"><u>Desktop Configuration Mastery: Embedding 'This PC' Symbols</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-mend-flickering-screens-in-windows-11/"><u>How to Mend Flickering Screens in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-self-scrolled-windows-with-ease-and-precision/"><u>Fix Self-Scrolled Windows with Ease and Precision</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-syncing-on-windows-the-most-rated-apps/"><u>Mastering File Syncing on Windows: The Most Rated Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-file-backup-with-windows-11/"><u>Streamlining File Backup with Windows 11</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-from-poco-x5-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock from Poco X5 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-solve-the-disconnected-from-nvidia-experience-problem-in-win-11/"><u>How to Solve the 'Disconnected From NVIDIA Experience' Problem in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-bypass-windows-admin-installation-restriction-error/"><u>Steps to Bypass Windows 'Admin Installation Restriction' Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-a-global-keyboard-downloading-windows-fonts/"><u>Crafting a Global Keyboard: Downloading Windows Fonts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cpu-gen-identification-using-eight-proven-windows-methods/"><u>CPU Gen Identification Using Eight Proven Windows Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-stuttering-challenges-enhancing-warhammer-40k-experience/"><u>Conquer Stuttering Challenges: Enhancing Warhammer 40K Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-method-integrating-airpods-with-windows/"><u>Efficient Method: Integrating AirPods with Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-sid-retrieval-for-all-users-on-windows-11/"><u>Mastering SID Retrieval for All Users on Windows 11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/failed-to-play-mp4-movies-with-sony-xperia-10-v-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Failed to play MP4 movies with Sony Xperia 10 V</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-mastering-the-art-of-hashtag-usage-a-primer-for-gamers-yt/"><u>[Updated] Mastering the Art of Hashtag Usage  A Primer for Gamers YT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-0x00000001-barrier-in-game-access/"><u>Overcoming the 0X00000001 Barrier in Game Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-signature-verification-issue-in-winoses/"><u>Eradicating Signature Verification Issue in WinOSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-resolve-defenders-0x80004004-error/"><u>Guide to Resolve Defender's 0X80004004 Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-errors-a-guide-to-fs-repair-in-win11/"><u>Mending Errors: A Guide to FS Repair in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-successfully-unplug-epic-games-from-your-w11-system/"><u>How to Successfully Unplug Epic Games From Your W11 System</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/crafting-memorable-dialogues-a-screenwriters-guide-for-2024/"><u>Crafting Memorable Dialogues  A Screenwriter's Guide for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/change-location-on-yik-yak-for-your-nokia-g22-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>Change Location on Yik Yak For your Nokia G22 to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-efficiently-recording-your-xbox-adventures/"><u>[New] Efficiently Recording Your Xbox Adventures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamping-memory-use-on-win-11-os/"><u>Revamping Memory Use on Win 11 OS</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-samsung-galaxy-f54-5g-frp-in-3-different-ways-by-drfone-android/"><u>In 2024, How To Bypass Samsung Galaxy F54 5G FRP In 3 Different Ways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-invalid-device-label-in-windows-os/"><u>Correcting 'Invalid Device' Label in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-improving-win11-point-accuracy-and-size/"><u>Guide to Improving Win11' Point Accuracy & Size</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-exploring-leading-podcast-host-platforms/"><u>2024 Approved  Exploring Leading Podcast Host Platforms</u></a></li>
<li><a href="https://fix-guide.techidaily.com/solved-warning-camera-failed-on-vivo-v27-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Solved Warning Camera Failed on Vivo V27 Pro | Dr.fone</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-audio-interpretation-software-zero-cost-version-for-2024/"><u>[Updated] Audio Interpretation Software – Zero Cost Version for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-harnessing-visuals-crafting-persuasive-and-striking-snap-ads/"><u>[New] 2024 Approved  Harnessing Visuals  Crafting Persuasive and Striking Snap Ads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-change-easily-altering-nat-settings-in-win1110/"><u>Navigating the Change: Easily Altering NAT Settings in Win11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-lightweight-browser-ram-usage-with-comparative-tests/"><u>Exploring Lightweight Browser RAM Usage with Comparative Tests</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-pink-screens-in-windows-systems/"><u>Quick Fixes for Pink Screens in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quiet-quandaries-winning-back-volume-from-vexed-keyboard/"><u>Quiet Quandaries: Winning Back Volume From Vexed Keyboard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-steps-to-navigate-windows-system-restore-functions/"><u>Simplified Steps to Navigate Windows' System Restore Functions</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/premier-8-edits-suites-for-linux-buffs-for-2024/"><u>Premier 8 Edits Suites for Linux Buffs for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-how-to-effortlessly-download-and-setup-movie-maker-6/"><u>In 2024, How to Effortlessly Download and Setup Movie Maker 6</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectify-your-input-cannot-be-opened-error-in-windows-vlc/"><u>Rectify 'Your Input Cannot Be Opened' Error in Windows, VLC</u></a></li>
<li><a href="https://screen-recording.techidaily.com/desktop-recording-head-to-head-obs-vs-shadowplay/"><u>Desktop Recording Head-to-Head  OBS Vs. ShadowPlay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-moves-for-unlocking-the-calculator-in-windows-11/"><u>Key Moves for Unlocking the Calculator in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-trigger-startup-success-for-windows-index-service/"><u>Strategies to Trigger Startup Success for Windows Index Service</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-making-life-easier-watching-fb-videos-on-your-tv/"><u>[New] 2024 Approved  Making Life Easier  Watching FB Videos on Your TV</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-console-management-with-admin-rights/"><u>Mastering Windows Console Management with Admin Rights</u></a></li>
</ul></div>
