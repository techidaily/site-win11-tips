---
title: "Gaining Control: Four Effective Tactics for Account Disabling on Win11"
date: 2024-09-01T05:20:33.535Z
updated: 2024-09-02T05:20:33.535Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Gaining Control: Four Effective Tactics for Account Disabling on Win11"
excerpt: "This Article Describes Gaining Control: Four Effective Tactics for Account Disabling on Win11"
keywords: Win11 Control Tactic,Disable Account Methods,Win11 Security Steps,Preventing Unauthorized Access,Managing User Permissions,Secure Win11 Settings,Anti-Abuse Measures Win11
thumbnail: https://thmb.techidaily.com/c8e68cffef41fc4061ac722c7019bbd23a7bd74185b074d0cf9fcbe34770c5fd.jpg
---

## Gaining Control: Four Effective Tactics for Account Disabling on Win11

 You can create multiple users account on Windows 11 for yourself and others. This allows you to create different spaces for your personal and work tasks and enable others to share your computer and have their own spaces.

 But what if you need to stop someone from accessing their account without deleting it? While you can temporarily disable a user account on Windows 11 using the block sign-in option, there are a few other ways to disable specific or all user accounts on Windows 11.

## 1\. How to Disable a User Account in Windows Settings

 Windows allows the system administrator to manage user accounts on Windows 11\. Not only can you[add a local user account](https://www.makeuseof.com/windows-11-create-local-user-account/) there, but you can also block sign-in to disable an account temporarily.

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

 When disabled, the user account will be hidden from your lock screen. To verify the same, press**Win + L** to[lock your Windows 11 computer](https://www.makeuseof.com/windows-11-ways-to-lock/) . Next, double-click on the lock screen to view the login screen. If disabled, the user account will appear on the lower left side of your screen.

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
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
8. If you need to enable the account again, execute the following command:  
`net user NewUser /Active:yes`
9. Make sure to replace NewUser with the account name you want to enable.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Click**Apply** and**OK** to save the changes.
5. To enable the account gain, uncheck the**Account is disabled** option and click**Apply** and**OK** .

### Disable User Account Using Local Users and Groups on Windows 11 Home

 Windows 11 Home users will have to rely on a third-party tool to disable a user account via the Local User and Groups console. Lusrmgr is a third-party snap-in that offers similar functionalities as the Local Users and Groups Management console.

 To install the tool, follow our guide to[enable Local User and Group Management on Windows 11](https://www.makeuseof.com/windows-home-edition-enable-local-user-group-management/) . Once done, follow the steps below:

1. Double-click on the**lusrmgr.exe** file to launch the application.
2. In the**Local users and groups** dialog, select**Users** .
3. Right-click on the user account you want to disable and select**Edit** .  
![run lusrmgr exe file edit account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/run-lusrmgr-exe-file-edit-account.jpg)
4. Next, open the**Account** tab.
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
5. Select the**Account is disabled** option.  
![run lusrmgr exe file edit account disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/run-lusrmgr-exe-file-edit-account-disabled.jpg)
6. Click**Apply** and**OK** to save the changes.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-navigating-through-facebook-gif-downloads-across-platforms/"><u>[New] In 2024, Navigating Through Facebook GIF Downloads Across Platforms</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-secrets-of-the-social-elite-6-actionable-tips-for-growing-instagram-followers-for-2024/"><u>[New] Secrets of the Social Elite  6 Actionable Tips for Growing Instagram Followers for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-free-tools-roundup-leading-online-video-capture-tech/"><u>[Updated] 2024 Approved  Free Tools Roundup  Leading Online Video Capture Tech</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-surging-channel-growth-with-optimal-video-hashes/"><u>[Updated] In 2024, Surging Channel Growth with Optimal Video Hashes</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-sustainable-design-in-action-the-huawei-p10s-environmental-approach/"><u>[Updated] In 2024, Sustainable Design in Action  The Huawei P10’s Environmental Approach</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-transforming-visual-feeds-with-harmonious-hits/"><u>[Updated] In 2024, Transforming Visual Feeds with Harmonious Hits</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-parallel-audio-stream-mapping-for-2024/"><u>[Updated] Parallel Audio Stream Mapping for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-tips-to-prevent-frame-skipping-in-obs-studio-for-2024/"><u>[Updated] Tips to Prevent Frame Skipping in OBS Studio for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/assessing-if-sns-hdr-deserves-your-investment-time/"><u>Assessing If SNS HDR Deserves Your Investment Time</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-honor-90-lite-drfone-by-drfone-virtual-android/"><u>Catch or Beat Sleeping Snorlax on Pokemon Go For Honor 90 Lite | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-htc-u23-pro-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for HTC U23 Pro Hard Reset | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-and-rectifying-windowss-c0000005-complication/"><u>Demystifying and Rectifying Windows's C0000005 Complication</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diagnosing-and-repairing-error-0xc0000001/"><u>Diagnosing and Repairing Error 0xC0000001</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-system-performance-new-approach-to-icon-cache/"><u>Enhancing System Performance: New Approach to Icon Cache</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-insights-budgeted-windows-11-codes/"><u>Exclusive Insights: Budgeted Windows 11 Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-track-to-windows-11-safe-mode-via-easy-methods/"><u>Fast Track to Windows 11 Safe Mode via Easy Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-bluetooth-absence-rediscover-devices-mgr-win/"><u>Fix Bluetooth Absence, Rediscover Devices Mgr WIN</u></a></li>
<li><a href="https://win-solutions.techidaily.com/fixing-login-issues-on-steam-a-step-by-step-guide/"><u>Fixing Login Issues on Steam: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-steam-cloud-errors-in-windows/"><u>Fixing Steam Cloud Errors in Windows</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722960663263-get-the-latest-epson-l3150-printer-drivers-compatible-with-microsoft-windows-10-8-and-7-free/"><u>Get the Latest Epson L3150 Printer Drivers Compatible with Microsoft Windows 10, 8 & 7 - Free!</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-a-network-locked-samsung-galaxy-a05s-phone-by-drfone-android/"><u>How to Unlock a Network Locked Samsung Galaxy A05s Phone?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-ways-to-safeguard-windows-without-bitlocker/"><u>Innovative Ways to Safeguard Windows Without BitLocker</u></a></li>
<li><a href="https://hardware-help.techidaily.com/intels-latest-leap-panther-lake-and-clearwater-forest-cpus-preparing-for-cutting-edge-lithographic-node-upgrades/"><u>Intel's Latest Leap: Panther Lake & Clearwater Forest CPUs Preparing for Cutting-Edge Lithographic Node Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-your-game-running-fixes-for-roblox-on-windows-pcs/"><u>Keeping Your Game Running: Fixes for Roblox on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-in-maintaining-reliable-windows-notepad-performance/"><u>Mastery in Maintaining Reliable Windows Notepad Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimization-techniques-for-quick-epic-game-access/"><u>Optimization Techniques for Quick Epic Game Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-activation-error-0x8007251d-a-step-by-step-guide/"><u>Resolving Windows Activation Error 0X8007251D: A Step-by-Step Guide</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/revolutionize-your-gameplay-with-acers-new-lineup-high-performance-oled-monitors-and-the-exceptional-480hz-predator-x27u-f3/"><u>Revolutionize Your Gameplay with Acer's New Lineup: High-Performance OLED Monitors and the Exceptional 480Hz Predator X27U F3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-printer-connectivity-failures-in-windows-11/"><u>Solutions for Printer Connectivity Failures in Windows 11</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/stream-media-in-style-on-a-budget-unveiling-the-lenovo-tab-m10-hds-capabilities-in-this-exclusive-2020-review/"><u>Stream Media in Style on a Budget: Unveiling the Lenovo Tab M10 HD's Capabilities in This Exclusive 2020 Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-pcs-safety-audit-with-wins-11-tactics/"><u>Streamline Your PC's Safety Audit with Wins 11 Tactics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-the-pointers-pace-turn-off-acceleration-in-windows-11/"><u>Taming the Pointer's Pace: Turn Off Acceleration In Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-silent-voice-finding-expression-in-a-muted-world/"><u>The Silent Voice: Finding Expression in a Muted World</u></a></li>
<li><a href="https://facebook.techidaily.com/the-typographic-touch-chat-styles-and-standouts/"><u>The Typographic Touch: Chat Styles and Standouts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-palette-of-digital-artistic-possibilities-on-win10/"><u>The Ultimate Palette of Digital Artistic Possibilities on Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-recover-from-lost-connection-error-in-win/"><u>Tips to Recover From Lost Connection Error in Win</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-15-apps-to-hack-wifi-password-on-nokia-by-drfone-android/"><u>Top 15 Apps To Hack WiFi Password On Nokia</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-6-changes-in-windows-ui-and-layout/"><u>Top 6 Changes in Windows UI and Layout</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-loadlibrary-err-87-misstep/"><u>Troubleshooting LoadLibrary Err 87 Misstep</u></a></li>
<li><a href="https://facebook.techidaily.com/unplugging-spotifys-social-media-connection-from-fb/"><u>Unplugging Spotify's Social Media Connection From FB</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-and-fixing-0x0000004e-in-windows-1011/"><u>Unraveling and Fixing 0X0000004E in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-isnt-my-usb-mouse-working-on-my-laptop-top-repair-strategies-inside/"><u>Why Isn't My USB Mouse Working on My Laptop? Top Repair Strategies Inside</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-secrets-automating-selective-file-shifts/"><u>Windows 11 Secrets: Automating Selective File Shifts</u></a></li>
<li><a href="https://discover-blog.techidaily.com/1724766779512-18/"><u>デジアーティー18周年記念限定プロジェクト - オマケ付き</u></a></li>
</ul></div>
