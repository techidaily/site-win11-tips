---
title: Altering Privilege Levels for Non-Administrators on Windows OS
date: 2024-08-08T10:54:01.980Z
updated: 2024-08-09T10:54:01.980Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Altering Privilege Levels for Non-Administrators on Windows OS
excerpt: This Article Describes Altering Privilege Levels for Non-Administrators on Windows OS
keywords: Admin Rights Limitation,Privilege Control Windows,NT User Privileges,Regular Account Security,Non-Admin Access,OS Permissions Restrict,Secure User Levels
thumbnail: https://thmb.techidaily.com/5350e79af12b414e304e4335d5b2d88e62b5e0973ecd1f3c8cd4da92e1845552.jpeg
---

## Altering Privilege Levels for Non-Administrators on Windows OS

 By default, standard users on Windows can run programs with elevated privileges if they enter an administrator password when prompted by User Access Control (UAC).

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
## The UAC Behaviors Available for Standard User Accounts

 Unlike when [changing UAC behaviors for administrator accounts](https://www.makeuseof.com/change-user-access-control-works-administrators-windows/), the behaviors for standard user accounts are a little more limited. According to the [Microsoft Learn](https://learn.microsoft.com/en-us/windows/security/threat-protection/security-policy-settings/user-account-control-behavior-of-the-elevation-prompt-for-standard-users) website, here are the behaviors you can choose and what they mean:

* **Automatically deny elevation requests**: This option returns an **Access denied** error message to standard users when they try to perform an operation that requires elevation of privilege. Most organizations that run desktops as standard users configure this policy to reduce help desk calls.
* **Prompt for credentials on the secure desktop**: When an operation requires elevation of privilege, the user is prompted on the secure desktop to enter a different username and password. If the user enters valid credentials, the operation continues with the applicable privilege.
* **Prompt for credentials**: An operation that requires elevation of privilege prompts the user to type an administrative username and password. If the user enters valid credentials, the operation continues with the applicable privilege.

 The default UAC behavior for standard user accounts is **Prompt for credentials**, but Microsoft recommends you change it to **Automatically deny elevation requests**. That way, only users with administrator accounts can decide how the UAC behaves and make choices that will keep the computer safe.

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
## How to Change the UAC Behavior for Standard Users in the Local Group Policy Editor

 The easiest way to change the way UAC behaves for standard users is to tweak the **User Account Control: Behavior of the elevation prompt for standard users** policy. To do that, [open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and follow the steps below.

 The Local Group Policy Editor isn't available by default on Windows Home. As such, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Head to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options**.
2. Right-click the **User Account Control: Behavior of the elevation prompt for standard users** policy and select **Properties** in the menu.  
![modifying the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
3. Expand the dropdown and choose a different UAC behavior.  
![editing the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/editing-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
4. Click **OK**.

 Keep in mind that only administrators can change the behavior of the UAC. If a standard user tried to change it using the Local Group Policy Editor, for example, they'd probably get an **Access denied** error message.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
## How to Change the UAC Behavior for Standard Users in the Registry Editor

 If you're looking for another way to change UAC behavior for standard users, or the [Local Group Policy is not working](https://www.makeuseof.com/windows-local-group-policy-unresponsive/) on your computer, you can make changes in the Windows registry instead.

 Before you do that, however, we recommend you [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) to protect your computer in case you make a mistake. Once you do that, [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) and follow the steps below:

1. Copy **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** and paste it into the address bar at the top of the Registry Editor.  
![the System key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-key-registry-editor.jpg)
2. Press **Enter** on your keyboard to go to the **System** key.
3. Right-click the **ConsentPromptBehaviorUser** value in the right panel and select **Modify**.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![modifying the ConsentPromptBehaviorUser value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-consentpromptbehavioruser-in-registry-editor.jpg)
4. In the **Value data** text box, enter **0** for **Automatically deny elevation requests**, **1** for **Prompt for credentials on the secure desktop**, or **3** for **Prompt for credentials**.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
![setting Value data for ConsentPromptbehavior Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/setting-value-data-for-consentpromptbehavior-registry-editor.jpg)
5. Click **OK**.

 Now restart your computer to allow the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
## Control UAC's Behavior for Standard Users on Windows

 UAC is an integral part of protecting your Windows computer from malicious programs that want to run with elevated privileges. While you can't make it elevate programs without prompting, you can make it stricter by setting it to **Automatically deny elevation requests**. And, as you can see, it is quite easy to do, whether you're using the Local Group Policy Editor or the Registry Editor.

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/new-the-art-of-sound-transition-in-logic-pro-x/"><u>[New] The Art of Sound Transition in Logic Pro X</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-ace-the-art-of-online-fame-trending-on-youtube/"><u>[Updated] 2024 Approved  Ace the Art of Online Fame  Trending on YouTube</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-clear-conferencing-backdrops-blurring-for-better-presence/"><u>[Updated] 2024 Approved  Clear Conferencing Backdrops  Blurring for Better Presence</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-crafting-cinematic-magic-essential-tips-for-creating-stunning-slow-motion-media-on-instagram-for-2024/"><u>[Updated] Crafting Cinematic Magic  Essential Tips for Creating Stunning Slow-Motion Media on Instagram for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-guide-to-superior-youtube-commercials/"><u>[Updated] In 2024, Guide to Superior YouTube Commercials</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-the-complete-guide-from-recording-to-live-on-facebook-for-2024/"><u>[Updated] The Complete Guide  From Recording to Live on Facebook for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-top-live-stream-scenery-ideas-2023/"><u>[Updated] Top Live Stream Scenery Ideas 2023</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-web-wonders-weekly-review/"><u>[Updated] Web Wonders Weekly Review</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-enhance-images-with-text-via-web-and-mobile-apps/"><u>2024 Approved  Enhance Images with Text via Web & Mobile Apps</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-mastering-the-art-of-phantoms-time-recapture/"><u>2024 Approved  Mastering the Art of Phantom's Time Recapture</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-strategies-to-eliminate-frames-loss-in-obs-recordings/"><u>2024 Approved  Strategies to Eliminate Frames Loss in OBS Recordings</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-unleash-the-power-of-zoom-your-win10-journey-begins-here/"><u>2024 Approved  Unleash the Power of Zoom  Your Win10 Journey Begins Here</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-easy-ways-to-change-location-on-youtube-tv-on-vivo-y27s-drfone-by-drfone-virtual-android/"><u>5 Easy Ways to Change Location on YouTube TV On Vivo Y27s | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-full-screen-windows-alignment-in-windows/"><u>Achieving Full-Screen Windows Alignment in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-win1011-blue-screen-crash-issue/"><u>Addressing Win10/11 Blue Screen Crash Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-barriers-editing-your-win11-fax-pages-with-ease/"><u>Breaking Down Barriers: Editing Your Win11 Fax Pages with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-restrictions-for-microsoft-store-on-win11/"><u>Clearing Restrictions for Microsoft Store on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/craft-your-win11-boot-experience-steps-to-optimize-service-setups/"><u>Craft Your Win11 Boot Experience: Steps to Optimize Service Setups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detailed-process-for-moving-qbittorrent-software-across-pcs/"><u>Detailed Process for Moving qBittorrent Software Across PCs</u></a></li>
<li><a href="https://win-amazing.techidaily.com/easy-setup-fresh-hp-m477-printer-drivers-to-enhance-your-printing-experience/"><u>Easy Setup: Fresh HP M477 Printer Drivers to Enhance Your Printing Experience</u></a></li>
<li><a href="https://activate-lock.techidaily.com/easy-tutorial-for-activating-icloud-from-iphone-x-safe-and-legal-by-drfone-ios/"><u>Easy Tutorial for Activating iCloud from iPhone X Safe and Legal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-shortcuts-for-power-users-on-windows/"><u>Essential Shortcuts for Power Users on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/foster-robust-windows-application-connections-with-simple-fixes/"><u>Foster Robust Windows Application Connections with Simple Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-classic-to-continuous-understanding-windows-10-and-11s-evolution/"><u>From Classic to Continuous: Understanding Windows 10 & 11'S Evolution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-graphic-design-to-daily-use-ai-in-windows/"><u>From Graphic Design to Daily Use: AI in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-reopen-battlenet-desktop-client-on-windows-os/"><u>Guide to Reopen Battle.net Desktop Client on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-securely-manage-editing-accessibility/"><u>Guide to Securely Manage Editing Accessibility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-and-disable-the-windows-key/"><u>How to Enable and Disable the Windows Key</u></a></li>
<li><a href="https://win-able.techidaily.com/how-to-prevent-mass-effect-legendary-edition-from-crashing-on-pc-or-your-gaming-console/"><u>How To Prevent Mass Effect Legendary Edition From Crashing on PC or Your Gaming Console</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-asus-rog-phone-8-prowithwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Asus ROG Phone 8 Prowith/without a PC</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-enable-usb-debugging-on-a-locked-xiaomi-redmi-12-5g-phone-by-drfone-android/"><u>In 2024, How To Enable USB Debugging on a Locked Xiaomi Redmi 12 5G Phone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-ways-to-augment-folder-context-menus/"><u>Innovative Ways to Augment Folder Context Menus</u></a></li>
<li><a href="https://extra-tips.techidaily.com/knockout-kings-vs-viewership-titans/"><u>Knockout Kings Vs. Viewership Titans</u></a></li>
<li><a href="https://screen-recording.techidaily.com/make-the-most-of-your-gaming-experience-top-methods-to-document-minecraft-on-mac-for-2024/"><u>Make the Most of Your Gaming Experience - Top Methods to Document Minecraft on Mac for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-open-secrets-of-windows-11-sticky-notes/"><u>Navigating the Open Secrets of Windows 11 Sticky Notes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-w11-way-to-alter-your-fax-cover-page/"><u>Navigating the W11 Way to Alter Your Fax Cover Page</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-access-denied-save-issues-on-windows/"><u>Navigating Through Access Denied Save Issues on Windows</u></a></li>
<li><a href="https://program-issues.techidaily.com/overcome-indivisible-crash-problems-with-these-simple-solutions/"><u>Overcome Indivisible Crash Problems with These Simple Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-update-obstacles-with-these-fixes/"><u>Overcome Update Obstacles with These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11-camera-issue-fixing-error-f429f/"><u>Overcoming Windows 11 Camera Issue: Fixing Error F429F</u></a></li>
<li><a href="https://techidaily.com/recover-apple-iphone-8-plus-data-from-ios-itunes-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover Apple iPhone 8 Plus Data From iOS iTunes | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redirecting-home-page-in-win11-settings/"><u>Redirecting Home Page in Win11 Settings</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-frp-lock-on-oneplus-nord-ce-3-5g-by-drfone-android-unlock-remove-google-frp/"><u>Remove FRP Lock on OnePlus Nord CE 3 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-connection-between-windows-11-and-print-devices/"><u>Restoring Connection Between Windows 11 and Print Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-downloads-for-windows-top-10-choices-revealed/"><u>Secure Downloads for Windows: Top 10 Choices Revealed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slick-techniques-for-masking-windows-11-task-view/"><u>Slick Techniques for Masking Windows 11 Task View</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-failed-windows-speech-recognition-initialization/"><u>Solving Failed Windows Speech Recognition Initialization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-reigniting-wifi-detection-in-windows-11-systems/"><u>Steps for Reigniting Wifi Detection in Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-roblox-unrecoverable-errors/"><u>Strategies to Overcome Roblox Unrecoverable Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tap-into-divine-interface-capabilities-in-windows-11/"><u>Tap Into Divine Interface Capabilities in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-end-of-windows-xp-7-and-81-era-from-microsoft/"><u>The End of Windows XP, 7 & 8.1 Era From Microsoft</u></a></li>
<li><a href="https://activate-lock.techidaily.com/the-ultimate-guide-to-unlocking-apple-watch-or-iphone-11-pro-from-icloud-by-drfone-ios/"><u>The Ultimate Guide to Unlocking Apple Watch Or iPhone 11 Pro from iCloud</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/timelapse-techniques-for-samsung-smartphones/"><u>Timelapse Techniques for Samsung Smartphones</u></a></li>
<li><a href="https://win-forum.techidaily.com/top-5-methods-to-secure-your-pc-windows-edition/"><u>Top 5 Methods to Secure Your PC: Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unbreakable-passwords-top-four-managers-for-the-new-windows-edition/"><u>Unbreakable Passwords: Top Four Managers for the New Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-display-experience-shift-to-adaptive-layouts/"><u>Upgrade Display Experience: Shift to Adaptive Layouts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-settings-returning-to-initial-touch-keyboard-configuration/"><u>Win 11 Settings: Returning to Initial Touch Keyboard Configuration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-guide-to-opening-quick-capture-utility/"><u>Windows 11 Guide to Opening Quick Capture Utility</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/windows-11s-best-pc-webcam-recorders-reviewed-for-2024/"><u>Windows 11'S Best PC Webcam Recorders Reviewed for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/zeroing-out-0x800f0831-windows-troubleshoot-guide/"><u>Zeroing Out 0X800F0831: Windows Troubleshoot Guide</u></a></li>
</ul></div>
