---
title: Eliminating 'Restricted IT Administrator' Message in OS
date: 2024-07-12T16:31:24.383Z
updated: 2024-07-13T16:31:24.383Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminating 'Restricted IT Administrator' Message in OS
excerpt: This Article Describes Eliminating 'Restricted IT Administrator' Message in OS
keywords: Restricted IT Admins Removal,Eradicate Admin Block Errors,Unblock IT Admin Messages,Disable Restricted Admin Alerts,IT Admin Access Control,Remove IT Admin Barriers,Clear IT Admin Denials
thumbnail: https://thmb.techidaily.com/48bbf816680af2439ef36580a7c2fe3c4155339daebaab90b2926193e2ffe8d4.png
---

## Eliminating 'Restricted IT Administrator' Message in OS

 Some users have posted on troubleshooting forums about a “Page not available” error that occurs when they open Windows Security. The “Page not available” error message says, “Your IT Administrator has limited access to some areas of this app.” That error message appears within Windows Security, and users can’t access that app’s antivirus settings because of it.

 This error message suggests another administrative user has applied restrictions to Windows Security. However, it often arises on standalone PCs that aren’t connected to an organization network. This is how you can fix the “Your IT administrator has limited access” error.

## 1\. Change Your User Account to an Admin Account

 You shouldn’t usually need admin rights to access Windows Security. However, make sure you’re signed in to an admin account to ensure you have full system permissions. If you’re utilizing a standard account, change it to an administrator one. You can do that with one of the methods outlined in this guide to [changing user account type in Windows](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) .

![The Access work or school account settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/work-or-school-accounts.jpg)

## 2\. Uninstall Third-Party Security Software

 Have you installed a third-party antivirus app on your PC? If so, that security software could be by conflicting with Microsoft Defender and causing the “Page not available” error. Try uninstalling the third-party antivirus utility you’ve installed with a method in our guide to [removing Windows software](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) . Or utilize a dedicated removal tool for your antivirus app if there’s one available.

![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/uninstall-option-3.jpg)

## 3\. Remove Any Work or School Accounts

 Have you connected your PC with any school or work organization account? If so, such an account could be restricting access to Windows Security settings. Try disconnecting your PC from the school or work in Settings as follows:

1. Bring up Settings and click that app’s**Accounts** tab (or category).
2. Scroll down to select the**Access work or school navigation** option.
3. Click a connected work or school account to expand it.  
![The Access work or school account settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/work-or-school-accounts.jpg)
4. Press the**Disconnect** button and select**Yes** .

## 4\. Disable the Turn Off Microsoft Defender Antivirus Policy

 Some Windows Pro and Enterprise users have confirmed they’ve fixed the “Page not available” error by disabling a**Turn off Microsoft Defender Antivirus** policy. So, check that policy setting even if you can’t recall changing it yourself. This is how you can check and disable the**Turn Off Microsoft Defender Antivirus** Group Policy setting in Windows Pro and Enterprise:

1. To access the file search box, hold the Windows logo key and press S.
2. Type**gpedit.msc** inside the file search box.
3. Double-click**gpedit.msc** to [open the Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) window.
4. Next, double-click**Computer Configuration** and**Administrative Templates** within Group Policy Editor’s sidebar.
5. Expand the**Windows Components** folder in the sidebar.

1. Click**Microsoft Defender Antivirus** to select that policy.  
![Microsoft Defender Antivirus settings in Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/microsoft-defender-antivirus-settings.jpg)
2. Then double-click**Turn off Microsoft Defender Antivirus** .
3. Click**Disabled** if the**Turn off Microsoft Defender Antivirus** policy is enabled.  
![The Turn off Microsoft Defender Antivirus window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-turn-off-microsoft-defender-antivirus-window.jpg)
4. Select the policy’s**Apply** and**OK** options.
5. Double-click**Allow antimalware to startup with normal priority** and select to disable that policy as outlined in the previous two steps as well.  
![The Allow antimalware service to startup with normal priority window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-antimalware-service-window.jpg)
6. Next, click**Client Interface** within the Microsoft Defender Antivirus settings.  
![Allow antimalware service to startup with normal priority](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/client-interface-setting.jpg)
7. Double-click the**Enable headless UI mode** policy to view it.  
![The Client Interface settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/enable-headless-ui-mode.jpg)
8. Select**Disabled** \>**Apply** \>**OK** in the Enable headless UI mode policy window.

## 5\. Run a PowerShell Command

 Running a set-MpPreference PowerShell command is a widely confirmed potential resolution for the “Page not available” error. The confirmed command disables Microsoft Defender’s UI lockdown mode. You can run that PowerShell command like this:

1. Activate the Windows search utility.
2. Input a**PowerShell** search phrase to find that command-line app.
3. Open PowerShell with elevated permissions by right-clicking the search result for that command-line app and selecting**Run as administrator** .
4. Input this**MpPreference** command and press**Return** :  
`set-MpPreference -UILockdown`  
![The set-Mppreference PowerShell command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-set-mppreference-command.jpg)
5. Exit PowerShell and open Windows Security again to see if the error persists.

## 6\. Repair/Reset Windows Security

 Windows Security is a UWP app for which you can select**Repair** and**Reset** Settings options that can resolve various issues. Those options are there to help users fix apps that aren’t working right. So, try selecting Windows Security’s**Repair** and**Reset** options to see if they make any difference.

![The Reset button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-button.jpg)

 Our article [about resetting Windows apps](https://www.makeuseof.com/windows-reset-app/) tells you how to access the**Reset** button. The**Repair** button is just above the**Reset** option. It’s recommended to select**Repair** first since that doesn’t affect app data.

## 7\. Modify the Registry via Command Prompt

 Users also confirm that running a series of Command Prompt commands that modify the registry can resolve the “Page not available” issue. As those are reg delete commands, we recommend you back up the registry before applying this potential fix. Then try running the registry commands for erasing policies like this:

 Open the utility for finding files and apps with the**Windows** logo +**S** key combination.

1. Find the Command Prompt by typing in a**CMD** search phrase.
2. Click the Command Prompt app with the mouse’s right button to select a**Run as administrator** context menu option.
3. Execute the following commands separately, pressing**Enter** after inputting each one:  
`reg delete "HKLM\Software\Microsoft\Windows\CurrentVersion\Policies" /f  

reg delete "HKLM\Software \Microsoft\WindowsSelfHost" /f  

reg delete "HKLM\Software\Policies" /f  

reg delete "HKLM\Software\WOW6432Node\Microsoft\Policies" /f  

reg delete "HKLM\Software\WOW6432Node\Microsoft\Windows\CurrentVersion\Policies" /f  

reg delete "HKLM\SOFTWARE\Policies\Microsoft\Windows Defender" /v DisableAntiSpyware  

reg delete "HKCU\Software\Microsoft\Windows\CurrentVersion\Policies" /f  

reg delete "HKCU\Software\Microsoft\WindowsSelfHost" /f  

reg delete "HKCU\Software\Policies" /f  

reg delete "HKLM\Software\Microsoft\Policies" /f`
4. Input**exit** in the Command Prompt to close the app.  
![The reg delete command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reg-delete.jpg)
5. Open the Start menu, select**Power** , and press the**Restart** button.

## 8\. Perform a System Restore

 If the “Page not available” error remains after applying other potential solutions, try performing a system restore. That might work if you can select a restore point predating the “Page not available” error on your PC. Rolling Windows back to an earlier time could undo any system changes that caused the issue to arise.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-resotre-window.jpg)

 Our guide on [creating and utilizing restore points](https://www.makeuseof.com/windows-11-create-restore-point/) provides instructions for rolling back Windows with System Restore. Choose the oldest restore point you can. However, remember that you’ll probably need to reinstall some software packages installed after the restore point’s date.

## Start Utilizing Windows Security Again

 The potential solutions covered in this guide address many of the primary causes for that error occurring. So, they’ll probably get the “Page not available” error sorted on most users’ Windows 11/10 PCs. Fixing the “Page not available” error will enable you to access all the settings in Windows Security again.

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
<li><a href="https://win11-tips.techidaily.com/the-essential-guide-to-microsofts-phone-link-features/"><u>The Essential Guide to Microsoft's 'Phone Link' Features</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-what-does-jailbreaking-iphone-6-plus-i-do-get-answers-here-by-drfone-ios/"><u>In 2024, What Does Jailbreaking iPhone 6 Plus i Do? Get Answers here</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-diving-deep-into-tiktoks-anime-world-the-symphony-of-dance-sounds-and-visual-magic-for-2024/"><u>[Updated] Diving Deep Into TikTok’s Anime World  The Symphony of Dance, Sounds and Visual Magic for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-without-taskbar-chat-what-it-means-for-you/"><u>Windows 11 Without Taskbar Chat: What It Means for You?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-compatibility-tips-synapse-reinstatement-guide/"><u>Win Compatibility Tips: Synapse Reinstatement Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-crash-code-0x80072efd-from-your-microsoft-store/"><u>Banishing Crash Code 0X80072EFD From Your Microsoft Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-prolong-pin-length-for-enhanced-safety/"><u>Tips to Prolong PIN Length for Enhanced Safety</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosted-methods-for-graphic-detail-recognition-windows-11/"><u>Boosted Methods for Graphic Detail Recognition, Windows 11</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-mastering-full-screen-fb-video-settings-for-2024/"><u>[Updated] Mastering Full-Screen FB Video Settings for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-diy-youtube-intros-and-ends-without-breaking-the-bank/"><u>[New] 2024 Approved  DIY YouTube Intros & Ends Without Breaking the Bank</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-elevate-your-content-game-on-youtube-top-11-video-seo-insights/"><u>[New] Elevate Your Content Game on YouTube  Top 11 Video SEO Insights</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-dissecting-wirecast-a-comprehensive-breakdown-and-comparisons-for-2024/"><u>[Updated] Dissecting WireCast  A Comprehensive Breakdown & Comparisons for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-pictures-from-vivo-y200-by-fonelab-android-recover-pictures/"><u>Possible solutions to restore deleted pictures from Vivo Y200.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-roblox-frame-rates-on-windows-systems/"><u>Boosting Roblox Frame Rates on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-stronger-side-why-you-should-opt-for-win11/"><u>Unveiling the Stronger Side: Why You Should Opt for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-ip-and-mac-info-with-windows-powershell/"><u>Unraveling IP and MAC Info with Windows Powershell</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-honor-90-gt-phone-forgot-password-by-drfone-android-unlock-android-unlock/"><u>How to Unlock Honor 90 GT Phone Forgot Password</u></a></li>
<li><a href="https://win11-tips.techidaily.com/w11-addressing-undetected-additional-monitor/"><u>W11: Addressing Undetected Additional Monitor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-picks-optimal-pomodoro-timers-tailored-for-windows-users/"><u>Top Picks: Optimal Pomodoro Timers Tailored For Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-memory-makeover-with-triple-tactics/"><u>Windows Memory Makeover with Triple Tactics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/wipe-out-unfulfilled-criteria-indication-in-win11/"><u>Wipe Out Unfulfilled Criteria Indication in Win11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-chromebooks-ultimate-sniping-software-our-5-favorites/"><u>In 2024, Chromebook's Ultimate Sniping Software  Our 5 Favorites</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-comprehensive-strategies-for-overwatch-gaming-saves/"><u>In 2024, Comprehensive Strategies for Overwatch Gaming Saves</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tricking-eyes-vanish-taskbar-search-in-windows-11/"><u>Tricking Eyes: Vanish Taskbar Search in Windows 11</u></a></li>
<li><a href="https://fox-access.techidaily.com/level-up-your-playtime-examining-kinemaster-on-android/"><u>Level Up Your Playtime  Examining KineMaster on Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unyielding-windows-security-choosing-the-strongest-passwords-shields/"><u>Unyielding Windows Security: Choosing the Strongest Passwords Shields</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-windowed-games-a-list-of-best-fps-trackers-on-pc/"><u>Winning at Windowed Games: A List of Best FPS Trackers on PC</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-honor-100-pro-drfone-by-drfone-virtual-android/"><u>Will Pokémon Go Ban the Account if You Use PGSharp On Honor 100 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-against-roblox-needs-to-close-windows-errors/"><u>Winning Against Roblox Needs to Close Windows Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-barriers-uniting-pc-and-android-devices/"><u>Breaking Barriers: Uniting PC & Android Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-tour-to-windows-easy-entry-point/"><u>A Step-by-Step Tour to Windows Easy Entry Point</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-full-screen-feature-on-facebook-what-you-need-to-know/"><u>2024 Approved  Full-Screen Feature on Facebook  What You Need to Know</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-the-ultimate-song-catcher-list-top-ten-products-that-make-preserving-music-a-breeze/"><u>Updated The Ultimate Song Catcher List Top Ten Products That Make Preserving Music a Breeze</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-motorola-moto-g-5g-2023-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Motorola Moto G 5G (2023) Hard Reset | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-definitive-guide-to-configuring-script-policies-in-ps/"><u>The Definitive Guide to Configuring Script Policies in PS</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-free-video-editing-essentials-cutting-and-joining-tools-for-starters-for-2024/"><u>New Free Video Editing Essentials Cutting and Joining Tools for Starters for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-use-pokemon-emerald-master-ball-cheat-on-honor-x50-gt-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Pokémon Emerald Master Ball Cheat On Honor X50 GT | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/transforming-engagement-on-instagram-top-10-compelling-igtv-content-concepts-for-brands/"><u>Transforming Engagement on Instagram  Top 10 Compelling IGTV Content Concepts for Brands</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-a-step-by-step-walkthrough-to-change-profile-pictorials/"><u>[New] In 2024, A Step-by-Step Walkthrough to Change Profile Pictorials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-optimal-adventure-play-winning-hd-games-on-pc-with-scummvm/"><u>A Guide to Optimal Adventure Play: Winning HD Games on PC with ScummVM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-the-power-of-sandbox-with-win-11/"><u>Unleashing the Power of Sandbox with Win 11</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/professionals-choice-the-best-8-streaming-audio-capture-tools-for-2024/"><u>Professionals Choice The Best 8 Streaming Audio Capture Tools for 2024</u></a></li>
</ul></div>
