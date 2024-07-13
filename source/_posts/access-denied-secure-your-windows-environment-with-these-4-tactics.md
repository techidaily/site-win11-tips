---
title: "Access Denied: Secure Your Windows Environment with These 4 Tactics"
date: 2024-07-12T16:49:48.760Z
updated: 2024-07-13T16:49:48.760Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Access Denied: Secure Your Windows Environment with These 4 Tactics"
excerpt: "This Article Describes Access Denied: Secure Your Windows Environment with These 4 Tactics"
keywords: AccessDeniedSecureWin,WindowSecurityTips,DenyErrorSolutions,SecureWindowsMethods,WinAccessGuard,WindowsProtectTactics,SafeWinEnvironments
thumbnail: https://thmb.techidaily.com/c92572eed4dd2bbe96a0af1968717f74dd3686117855d1fc2a4babce9d7f3f12.png
---

## Access Denied: Secure Your Windows Environment with These 4 Tactics

 You can create multiple users account on Windows 11 for yourself and others. This allows you to create different spaces for your personal and work tasks and enable others to share your computer and have their own spaces.

 But what if you need to stop someone from accessing their account without deleting it? While you can temporarily disable a user account on Windows 11 using the block sign-in option, there are a few other ways to disable specific or all user accounts on Windows 11.

## 1\. How to Disable a User Account in Windows Settings

 Windows allows the system administrator to manage user accounts on Windows 11\. Not only can you [add a local user account](https://www.makeuseof.com/windows-11-create-local-user-account/) there, but you can also block sign-in to disable an account temporarily.

To disable user accounts via Settings:

1. Press**Win + I** to open the**Settings** panel.
2. In the left pane, click on the**Accounts** tab.  
![windows 11 settings account family](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-11-settings-account-family-1.jpg)
3. Next, in the right pane, scroll down and click on**Family** .
4. Under**Your family** , scroll down and click on the account you want to disable.  
![windows 11 settings account family block sign in](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-11-settings-account-family-block-sign-in-1.jpg)
5. Next, click the**Block sign in** button and click**Block** in the confirmation dialog.  
![windows 11 settings account family allow sign in](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-11-settings-account-family-allow-sign-in-1.jpg)
6. If you need to enable the user account again, click the**Allow sign in** button and click**Allow** to confirm the action.

 Note that you must log in to your administrator account to make changes to user accounts. Also, you can only block sign-in for members of**Your family** in the Family groups from Settings. If you need to disable a local user account, you must use the PowerShell and Command Prompt methods below.

## 2\. How to Disable a User Account Using Windows PowerShell

 If you need to disable and enable user accounts frequently, PowerShell can help you do it efficiently. To do this, you can use the Disable-LocalUser cmdlet and specify the user account name you want to disable.

To disable a user account using PowerShell:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Terminal (Admin)** . It will open Windows Terminal with PowerShell set as the default profile.
3. If not, click the drop-down icon in the**Terminal** tabs section and select**Windows PowerShell** .  
![powerhsell user account list view](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/powerhsell-user-account-list-view.jpg)
4. Next, type the following command to find all the user accounts on your PC:  
`Get-LocalUser`
5. Locate the user account name in the**Name** column.

1. Next, type the following command to disable the specified user account:  
`Disable-LocalUser -Name &ldquo;NewUser&rdquo;`
2. In the above command, replace**NewUser** with the user account name you want to disable.  
![powerhsell user account disable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/powerhsell-user-account-disable.jpg)
3. PowerShell will not return a success message after the user account is disabled.
4. If you need to enable the account again, type the following command and press Enter:  
`Enable-LocalUser -Name &ldquo;NewUser&rdquo;`
5. In the above command replace NewUser with your user account name.

 When disabled, the user account will be hidden from your lock screen. To verify the same, press**Win + L** to [lock your Windows 11 computer](https://www.makeuseof.com/windows-11-ways-to-lock/) . Next, double-click on the lock screen to view the login screen. If disabled, the user account will appear on the lower left side of your screen.

## 3\. Disable a User Account Using the Command Prompt

 Another way to disable a local user account is via the Command Prompt. It is a command-line utility that you can use to disable Microsoft or local user accounts.

To disable a user account using Command Prompt:

1. Press**Win + R** to open**Run** .
2. Type**cmd** in the**Run** box. Next, press**OK** while holding the**Ctrl + Shift** key to open the elevated Command Prompt. Click**Yes** if prompted by User Account Control.
3. In the Command Prompt window, type the following command to find all the available user accounts on your PC:  
`net user`
4. Locate the user account name in the return list.  
![command prompt net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/command-prompt-net-user.jpg)
5. Next, type the following command to disable the specified user account:  
`net user NewUser /active:no`
6. In the above command, replace**NewUser** with the user account name you want to disable.  
![command prompt net user disable account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/command-prompt-net-user-disable-account.jpg)
7. Next, type**exit** and press Enter to close Command Prompt.
8. If you need to enable the account again, execute the following command:  
`net user NewUser /Active:yes`
9. Make sure to replace NewUser with the account name you want to enable.

## 4\. Disable a User Account From the Computer Management Console

 The Computer Management Console gives system administrators access to advanced tools such as Task Scheduler, Event Viewer, Device Manager, etc. Another useful Computer Management feature is Local Users and Groups.

 Local User and Groups lets you manage user accounts and groups on your Windows computer. While the Computer Management console is available on all versions of Windows, Local User and Groups is only available on the Pro, Edu, and Enterprise edition of the OS.

 To disable user accounts using the Local Users and Groups Management console:

1. Click on the**Search icon** in**Taskbar** .
2. Type**computer management** and click on**Computer Management** from the search result.
3. In the**Computer Management** console, expand**System Tools** .  
![computer management local users groups users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/computer-managemnet-local-users-groups-users.jpg)
4. Next, locate and select**Local Users and Groups.**
5. Select the**Users** folder**.**

1. In the right pane, you can view all the user accounts on your PC.
2. To disable a user account, right-click on the**User Account Name** and select**Properties** .  
![computer management local users groups users account is disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/computer-managemnet-local-users-groups-users-account-is-disabled.jpg)
3. In the**Properties** dialog, select the**Account is disabled** option.
4. Click**Apply** and**OK** to save the changes.
5. To enable the account gain, uncheck the**Account is disabled** option and click**Apply** and**OK** .

### Disable User Account Using Local Users and Groups on Windows 11 Home

 Windows 11 Home users will have to rely on a third-party tool to disable a user account via the Local User and Groups console. Lusrmgr is a third-party snap-in that offers similar functionalities as the Local Users and Groups Management console.

 To install the tool, follow our guide to [enable Local User and Group Management on Windows 11](https://www.makeuseof.com/windows-home-edition-enable-local-user-group-management/) . Once done, follow the steps below:

1. Double-click on the**lusrmgr.exe** file to launch the application.
2. In the**Local users and groups** dialog, select**Users** .
3. Right-click on the user account you want to disable and select**Edit** .  
![run lusrmgr exe file edit account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/run-lusrmgr-exe-file-edit-account.jpg)
4. Next, open the**Account** tab.
5. Select the**Account is disabled** option.  
![run lusrmgr exe file edit account disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/run-lusrmgr-exe-file-edit-account-disabled.jpg)
6. Click**Apply** and**OK** to save the changes.

## There Are Many Ways to Disable a User Account on Windows 11

 Disabling a user account lets you restrict access to a specific user account without deleting the account completely. This way, if you need to restore the account at a later stage, you can enable it and continue using it without restoring files and folders.

 That said, removing a user account on Windows 11 is not a complicated process. Just log in to your administrator account and block sign-in or remove user accounts from Settings, and you're pretty much done.

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
<li><a href="https://win11-tips.techidaily.com/steps-to-identify-non-recognized-usb-devices-on-win-11/"><u>Steps to Identify Non-Recognized USB Devices on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-the-amd-installer-crash-in-windows/"><u>Quick Fixes for the AMD Installer Crash in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-gaming-e84-fix-for-steam-windows/"><u>Streamline Your Gaming: E84 Fix for Steam Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-missing-msvcrt120dll-on-your-computer/"><u>Overcoming Missing Msvcrt120dll on Your Computer</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-unleash-creativity-with-these-8-free-youtube-thumbnail-builders/"><u>2024 Approved  Unleash Creativity with These 8 Free YouTube Thumbnail Builders</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-grandview-media-mastering-the-art-of-selecting-a-cms/"><u>[New] In 2024, Grandview Media  Mastering the Art of Selecting a CMS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-another-program-uses-device-auditory-fault/"><u>Tackling 'Another Program Uses Device' Auditory Fault</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-sizing-down-software-on-windows-11/"><u>Mastering the Art of Sizing Down Software on Windows 11</u></a></li>
<li><a href="https://ai-video.techidaily.com/top-9-choices-for-video-auto-translate/"><u>Top 9 Choices for Video Auto Translate</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silence-windows-aggressive-contrast-mode/"><u>Silence Windows' Aggressive Contrast Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/spotlight-on-7-irksome-windows-11-aesthetics/"><u>Spotlight on 7 Irksome Windows 11 Aesthetics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/standardizing-your-windows-system-backups/"><u>Standardizing Your Windows System Backups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-power-of-csgo-in-w11/"><u>Unlocking the Power of CS:GO in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-and-tricks-for-resolving-active-directory-printer-issues-on-win11/"><u>Tips & Tricks for Resolving Active Directory Printer Issues on Win11</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-expertise-in-iphones-macro-photography-secrets-revealed-for-2024/"><u>[New] Expertise in iPhone's Macro Photography Secrets Revealed for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/supercharge-with-leading-winning-apps-for-windows/"><u>Supercharge with Leading Winning Apps for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-game-launch-freezes-steps-to-mend-windows-11-steam/"><u>Troubleshooting Game Launch Freezes: Steps to Mend Windows 11 Steam</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-advanced-tips-for-minecraft-gaming-streams-for-2024/"><u>[Updated] Advanced Tips for Minecraft Gaming Streams for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quickly-manipulate-text-illumination-in-windows-11/"><u>Quickly Manipulate Text Illumination in Windows 11</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-easy-steps-for-exceptional-tiktok-video-experience-for-2024/"><u>[New] Easy Steps for Exceptional TikTok Video Experience for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-rectifying-error-0x80300024-in-winxp/"><u>Steps for Rectifying Error 0X80300024 in WinXP</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-realme-c33-2023mirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can Realme C33 2023Mirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/superior-vm-choices-to-upgrade-windows-11-performance/"><u>Superior VM Choices To Upgrade Windows 11 Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-editing-tasks-with-powertoys-text-tools/"><u>Simplify Editing Tasks with PowerToys' Text Tools</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-mastering-the-melody-adding-audio-to-your-canva-videos/"><u>In 2024, Mastering the Melody  Adding Audio to Your Canva Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-sudo-tool-is-coming-to-windows-how-and-why-to-use-it/"><u>The Sudo Tool Is Coming to Windows: How and Why to Use It</u></a></li>
<li><a href="https://some-approaches.techidaily.com/total-mastery-of-powerdirector-with-our-review-and-guide-for-2024/"><u>Total Mastery of PowerDirector with Our Review & Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-power-peaks-controlling-wlanext-usage/"><u>Taming Power Peaks: Controlling WLANEXT Usage</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-navigating-video-editing-the-essentials-of-cropping-and-exporting-to-instagram/"><u>[New] In 2024, Navigating Video Editing  The Essentials of Cropping and Exporting to Instagram</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-redefine-gaming-radeons-latest-release/"><u>[New] 2024 Approved  Redefine Gaming  Radeon's Latest Release</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-update-issue-error-code-0x80073712/"><u>Resolving Windows Update Issue: Error Code 0X80073712</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-foodie-hits-top-tiktok-chefs-and-cooks/"><u>[New] 2024 Approved  Foodie Hits  Top TikTok Chefs & Cooks</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-bringing-in-the-crowd-the-top-ten-reasons-and-fixes-to-boost-youtube-views-for-2024/"><u>[New] Bringing in the Crowd  The Top Ten Reasons and Fixes to Boost YouTube Views for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-lenovo-thinkphone-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Location is Not Updating and How to Fix On Lenovo ThinkPhone | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-successful-java-setup-in-windows/"><u>Strategies for Successful Java Setup in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resuscitating-silent-windows-headset-mic/"><u>Resuscitating Silent Windows Headset Mic</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-breakthrough-ways-to-transform-your-powerpoint-presentations/"><u>2024 Approved  Breakthrough Ways to Transform Your PowerPoint Presentations</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-instagram-uploading-tweets-videos-directly/"><u>[New] 2024 Approved  Instagram  Uploading Tweets' Videos Directly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimalist-workstations-with-windows-os/"><u>Minimalist Workstations with Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-missing-optional-windows-extras-in-7-steps/"><u>Troubleshooting Missing Optional Windows Extras in 7 Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-device-tracking-with-windows-live-tiles/"><u>Mastering Device Tracking with Windows Live Tiles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-fixes-for-non-displaying-storepages-on-win-10/"><u>Unveiling Fixes for Non-Displaying Storepages on Win 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-new-age-of-computing-from-w10s-familiarity-to-w11s-novelty/"><u>The New Age of Computing: From W10's Familiarity to W11's Novelty</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategizing-user-focused-gpo-settings-for-windows-1111-oses/"><u>Strategizing User-Focused GPO Settings for Windows 11/11 OSes</u></a></li>
<li><a href="https://extra-tips.techidaily.com/benq-sw320-monitor-reveal-a-spectacle-in-4k-technology-for-2024/"><u>BenQ SW320 Monitor Reveal  A Spectacle in 4K Technology for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-best-stream-tech-innovative-hardware-and-software-guide-for-youtubers/"><u>[Updated] 2024 Approved  Best Stream Tech  Innovative Hardware & Software Guide for Youtubers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-11s-error-0x0000011b-on-operations/"><u>Tackling Windows 11'S Error 0X0000011B on Operations</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-scrutinizing-hero5s-performance-throughout-day-for-2024/"><u>[New] Scrutinizing Hero5's Performance Throughout Day for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-efficiency-mastering-ms-projectenaside-from-what-ive-provided-please-give-me-5-new-book-titles-related-to-ai-in-healthcare/"><u>Unlock Efficiency: Mastering MS Project'enaside From What I've Provided, Please Give Me 5 New Book Titles Related to AI in Healthcare</u></a></li>
</ul></div>
