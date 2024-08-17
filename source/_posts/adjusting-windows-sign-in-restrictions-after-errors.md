---
title: Adjusting Windows Sign In Restrictions After Errors
date: 2024-08-16T01:06:24.810Z
updated: 2024-08-17T01:06:24.810Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Windows Sign In Restrictions After Errors
excerpt: This Article Describes Adjusting Windows Sign In Restrictions After Errors
keywords: Fix Sign-In Issues Windows,Adjust Windows Login Limits,Reset Windows Access Errors,Correct Login Errors Windows,Modify Windows Account Restrictions,Resolve Windows Sign In Errors,Alter User Permissions Windows
thumbnail: https://thmb.techidaily.com/e7e8dd516afa1923591eaf41c5af1b183e6c455af91f00d4dbb04a5e5e72a795.jpg
---

## Adjusting Windows Sign In Restrictions After Errors

 Windows has a policy setting that can lock someone out from signing in if they enter the wrong local account password too many times. The user is not allowed to sign in for a set number of minutes after being locked out, but you can change this lockout duration.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

## How to Change the Duration a User Is Locked Out of Their Account via Local Security Policy

 This method will work as long as the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press **Windows key + R** to open the **Run** dialogue.
2. Type “secpol.msc” into the text field and hit **Enter**.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, click on the **Account Lockout Policy** folder under **Account Policies**.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on **Account lockout duration**.  
![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  
![Choose how long a local account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-set-local-account-lockout-duration.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. This will pull up information, among other things, about how long this account lockout duration is currently set.
4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
## Find the Balance Between Security and Convenience

 Setting account lockout duration too high will cause inconvenience, but if you set it to zero, an administrator will have to be contacted each time a user locks themselves out. Find a balance between security and convenience when it comes to changing how long a user is locked out after a set number of failed login attempts.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-expert-tips-top-free-tools-to-extract-and-save-instagram-videos-windowsos-x/"><u>[New] In 2024, Expert Tips  Top Free Tools to Extract and Save Instagram Videos (Windows/OS X)</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-in-2024-the-artistry-of-image-editing-understanding-luts-role/"><u>[New] In 2024, The Artistry of Image Editing  Understanding LUTs' Role</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-what-if-my-videos-removed-immediately-due-to-copyright/"><u>[New] In 2024, What If My Videos Removed Immediately Due to Copyright?</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/breakneck-broadcast-channel-your-youtube-list-for-2024/"><u>Breakneck Broadcast  Channel Your YouTube List for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/bypassing-vimeo-top-10-editing-software-choices/"><u>Bypassing Vimeo  Top 10 Editing Software Choices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cool-running-tech-maintaining-moderate-temperatures-while-gaming/"><u>Cool Running Tech: Maintaining Moderate Temperatures While Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/counteracting-no-display-available-on-windows-11/"><u>Counteracting 'No Display Available' On Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-one-way-outlook-on-secure-windows-operating-system/"><u>Dealing with One-Way Outlook on Secure Windows Operating System</u></a></li>
<li><a href="https://facebook.techidaily.com/decoding-metas-dissolution-of-face-tech-with-fb/"><u>Decoding Meta's Dissolution of Face Tech with FB</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-red-x-symbols-in-computer-file-systems/"><u>Demystifying Red “X” Symbols in Computer File Systems</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ver-the-tricks-to-recording-and-screencasting-your-youtube-views-without-cash-for-2024/"><u>Discover The Tricks to Recording & Screencasting Your YouTube Views without Cash for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-into-unparalleled-windows-software-selection/"><u>Dive Into Unparalleled Windows Software Selection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enriching-context-menus-adding-a-diskspace-analyzer-feature/"><u>Enriching Context Menus: Adding a DiskSpace Analyzer Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-the-depths-of-0x0000003b-bsod-error-in-windows-pcs/"><u>Exploring the Depths of 0X0000003B BSOD Error in Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-no-connection-to-ea-servers-on-your-pc/"><u>Fixing No Connection to EA Servers on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-a-head-start-at-gameplay-with-winning-tactics-fc-style/"><u>Get a Head Start at Gameplay with Winning Tactics, FC Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harnessing-the-potential-of-wingetui-for-w11-package-management/"><u>Harnessing the Potential of WingetUI for W11 Package Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-activate-w11s-accelerated-support-mode/"><u>How to Activate W11’s Accelerated Support Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-expand-your-playnite-digital-library-on-windows-pcs/"><u>How to Expand Your Playnite Digital Library on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-manage-spotlight-images-on-your-pcs-lock-screen/"><u>How to Manage Spotlight Images on Your PC's Lock Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-repair-systemsettings-glitches-in-win11/"><u>How to Repair SystemSettings Glitches in Win11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-a-guide-nokia-g22-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>In 2024, A Guide Nokia G22 Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-to-fix-pokemon-go-route-not-working-on-apple-iphone-13-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Fix Pokemon Go Route Not Working On Apple iPhone 13? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-top-10-airplay-apps-in-vivo-s17e-for-streaming-drfone-by-drfone-android/"><u>In 2024, Top 10 AirPlay Apps in Vivo S17e for Streaming | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leading-non-windows-programs-as-substitutes-for-the-windows-snip-tool/"><u>Leading Non-Windows Programs as Substitutes for the Window’s Snip Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-microphone-windows-11-recording-guide/"><u>Mastering Microphone: Windows 11 Recording Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsofts-next-leap-after-cortana/"><u>Microsoft's Next Leap After Cortana</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-mkv-to-mp4-transformation-on-windows/"><u>Navigating Through MKV-to-MP4 Transformation on Windows</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-mac-os-slideshow-creator-turn-memories-into-stunning-videos-for-2024/"><u>New Mac OS Slideshow Creator Turn Memories Into Stunning Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-shift-key-stickiness-in-windows-os/"><u>Overcome Shift Key Stickiness in Windows OS</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/pc-video-editing-with-vn-a-short-review/"><u>PC Video Editing with VN A Short Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reigniting-your-non-responsive-windows-digital-scribe/"><u>Reigniting Your Non-Responsive Windows Digital Scribe</u></a></li>
<li><a href="https://review-topics.techidaily.com/reinstall-hardware-drivers-with-device-manager-in-windows-11-and-10-by-drivereasy-guide/"><u>Reinstall hardware drivers with Device Manager in Windows 11 & 10</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/resolve-your-iphone-12-keeps-asking-for-outlook-password-drfone-by-drfone-ios/"><u>Resolve Your iPhone 12 Keeps Asking for Outlook Password | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-spotify-freeze-issue-in-windows-11-os/"><u>Resolving Spotify Freeze Issue in Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-a-chrome-friendly-environment-in-windows-11/"><u>Setting Up a Chrome-Friendly Environment in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-fixing-windows-service-non-responder-error/"><u>Strategies for Fixing Windows Service Non-Responder Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-system-efficiency-incorporating-law-filters-into-your-workflow/"><u>Streamlining System Efficiency: Incorporating LAW Filters Into Your Workflow</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solution-to-try-connection-bluetooth-misfire/"><u>Swift Solution to 'Try Connection' Bluetooth Misfire</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-11s-complicated-update-to-v22h2-process/"><u>Tackling Windows 11'S Complicated Update to V22H2 Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-best-weather-apps-for-windows-11-and-11/"><u>The Best Weather Apps for Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-launching-windows-ea-quickly/"><u>The Ultimate Guide to Launching Windows EA Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-win11-guide-to-crafting-extractable-sfxs/"><u>The Win11 Guide to Crafting Extractable SFXs</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/three-ways-to-sim-unlock-motorola-moto-g-stylus-5g-2023-by-drfone-android/"><u>Three Ways to Sim Unlock Motorola Moto G Stylus 5G (2023)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-4-innovations-microsoft-paint-revamped/"><u>Top 4 Innovations: Microsoft Paint Revamped</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-windows-10-updates-solutions-when-they-arent-working/"><u>Troubleshooting Windows 10 Updates: Solutions When They Aren't Working</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uniting-computers-and-phones-with-samsung-flow/"><u>Uniting Computers & Phones with Samsung Flow</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unrivaled-video-tech-for-apple-phones-for-2024/"><u>Unrivaled Video Tech for Apple Phones for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-profile-management-new-folder-titles/"><u>Win 11 Profile Management: New Folder Titles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-timeline-6-ways-to-get-your-systems-timer-running/"><u>Windows Timeline: 6 Ways to Get Your System's Timer Running</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-strategies-for-loaded-screen-woes-lol/"><u>Winning Strategies for Loaded-Screen Woes (LOL)</u></a></li>
</ul></div>
