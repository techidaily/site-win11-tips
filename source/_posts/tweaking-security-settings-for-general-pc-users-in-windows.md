---
title: Tweaking Security Settings for General PC Users in Windows
date: 2024-08-16T02:34:43.271Z
updated: 2024-08-17T02:34:43.271Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tweaking Security Settings for General PC Users in Windows
excerpt: This Article Describes Tweaking Security Settings for General PC Users in Windows
keywords: Windows Secure Tweaks,PC Security Adjustment,Basic Win Safety,User-Friendly Firewall,Antivirus Settings Guide,Safe Passwords Tips,Access Controls Easy
thumbnail: https://thmb.techidaily.com/d156dc661c6f6baa9eb3b5c3ab4152f8f8f4fcdc0dbe084557e36eab0ab2db64.jpeg
---

## Tweaking Security Settings for General PC Users in Windows

 By default, standard users on Windows can run programs with elevated privileges if they enter an administrator password when prompted by User Access Control (UAC).

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

## The UAC Behaviors Available for Standard User Accounts

 Unlike when [changing UAC behaviors for administrator accounts](https://www.makeuseof.com/change-user-access-control-works-administrators-windows/), the behaviors for standard user accounts are a little more limited. According to the [Microsoft Learn](https://learn.microsoft.com/en-us/windows/security/threat-protection/security-policy-settings/user-account-control-behavior-of-the-elevation-prompt-for-standard-users) website, here are the behaviors you can choose and what they mean:

* **Automatically deny elevation requests**: This option returns an **Access denied** error message to standard users when they try to perform an operation that requires elevation of privilege. Most organizations that run desktops as standard users configure this policy to reduce help desk calls.
* **Prompt for credentials on the secure desktop**: When an operation requires elevation of privilege, the user is prompted on the secure desktop to enter a different username and password. If the user enters valid credentials, the operation continues with the applicable privilege.
* **Prompt for credentials**: An operation that requires elevation of privilege prompts the user to type an administrative username and password. If the user enters valid credentials, the operation continues with the applicable privilege.

 The default UAC behavior for standard user accounts is **Prompt for credentials**, but Microsoft recommends you change it to **Automatically deny elevation requests**. That way, only users with administrator accounts can decide how the UAC behaves and make choices that will keep the computer safe.

## How to Change the UAC Behavior for Standard Users in the Local Group Policy Editor

 The easiest way to change the way UAC behaves for standard users is to tweak the **User Account Control: Behavior of the elevation prompt for standard users** policy. To do that, [open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and follow the steps below.

 The Local Group Policy Editor isn't available by default on Windows Home. As such, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Head to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options**.
2. Right-click the **User Account Control: Behavior of the elevation prompt for standard users** policy and select **Properties** in the menu.  
![modifying the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
<!-- affiliate ads end -->
3. Expand the dropdown and choose a different UAC behavior.  
![editing the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/editing-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
4. Click **OK**.

 Keep in mind that only administrators can change the behavior of the UAC. If a standard user tried to change it using the Local Group Policy Editor, for example, they'd probably get an **Access denied** error message.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## How to Change the UAC Behavior for Standard Users in the Registry Editor

 If you're looking for another way to change UAC behavior for standard users, or the [Local Group Policy is not working](https://www.makeuseof.com/windows-local-group-policy-unresponsive/) on your computer, you can make changes in the Windows registry instead.

 Before you do that, however, we recommend you [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) to protect your computer in case you make a mistake. Once you do that, [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) and follow the steps below:

1. Copy **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** and paste it into the address bar at the top of the Registry Editor.  
![the System key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-key-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. Press **Enter** on your keyboard to go to the **System** key.
3. Right-click the **ConsentPromptBehaviorUser** value in the right panel and select **Modify**.  
![modifying the ConsentPromptBehaviorUser value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-consentpromptbehavioruser-in-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
4. In the **Value data** text box, enter **0** for **Automatically deny elevation requests**, **1** for **Prompt for credentials on the secure desktop**, or **3** for **Prompt for credentials**.  
![setting Value data for ConsentPromptbehavior Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/setting-value-data-for-consentpromptbehavior-registry-editor.jpg)
5. Click **OK**.

 Now restart your computer to allow the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
## Control UAC's Behavior for Standard Users on Windows

 UAC is an integral part of protecting your Windows computer from malicious programs that want to run with elevated privileges. While you can't make it elevate programs without prompting, you can make it stricter by setting it to **Automatically deny elevation requests**. And, as you can see, it is quite easy to do, whether you're using the Local Group Policy Editor or the Registry Editor.

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-clips.techidaily.com/new-dish-on-titles-crafting-captivating-cookery-channel-names/"><u>[New] Dish on Titles  Crafting Captivating Cookery Channel Names</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-proven-techniques-for-amplifying-your-impact-on-youtube-shorts/"><u>[New] Proven Techniques for Amplifying Your Impact on YouTube Shorts</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-camera-selection-for-amateurs/"><u>[Updated] Camera Selection for Amateurs</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-flawlessbackgroundfixer-premium-photo-editing-app/"><u>[Updated] FlawlessBackgroundFixer  Premium Photo Editing App</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-how-to-capture-and-share-your-favorite-pics-on-social-platforms-with-obs/"><u>[Updated] How to Capture and Share Your Favorite Pics on Social Platforms with OBS</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-seamless-facial-smoothing-motion-blur-techniques-in-picsart/"><u>2024 Approved  Seamless Facial Smoothing  Motion Blur Techniques in Picsart</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-should-you-review-off-facebook-histories-security-tips-and-tricks/"><u>2024 Approved  Should You Review Off-Facebook Histories? Security Tips & Tricks</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/3-ways-for-android-pokemon-go-spoofing-on-huawei-p60-drfone-by-drfone-virtual-android/"><u>3 Ways for Android Pokemon Go Spoofing On Huawei P60 | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/achieve-crystal-clear-slack-discussions-with-these-10-tools/"><u>Achieve Crystal Clear Slack Discussions with These 10 Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-taskbar-icons-that-dont-pop-up/"><u>Correcting Taskbar Icons that Don't Pop Up</u></a></li>
<li><a href="https://fox-access.techidaily.com/dive-into-a-world-of-timelessness-crafting-slow-motion-videos-using-mobile-apps-for-2024/"><u>Dive Into a World of Timelessness  Crafting Slow Motion Videos Using Mobile Apps for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/effortless-installation-of-validity-fingerprint-sensor-driver-secure-and-easy-download/"><u>Effortless Installation of Validity Fingerprint Sensor Driver – Secure & Easy [DOWNLOAD]</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-system-speed-strategies-for-virtual-memory-upgradation-in-windows-11/"><u>Elevating System Speed: Strategies for Virtual Memory Upgradation in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-error-0xc00d36b4-from-win11-devices/"><u>Eliminating Error 0XC00D36B4 From Win11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-sound-failure-in-audacity-windows-11-and-11/"><u>Eliminating Sound Failure in Audacity, Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/file-upload-woes-overcoming-chromes-challenges-on-windows/"><u>File Upload Woes: Overcoming Chrome's Challenges on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-administered-window-on-os-x/"><u>Guidelines for Administered Window on OS X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-handle-apple-photo-imports-that-go-wrong-on-pcs-windows/"><u>How to Handle Apple Photo Imports That Go Wrong on PCs (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-the-key-differences-in-exe-and-msi-formats/"><u>Identifying the Key Differences in EXE & MSI Formats</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-from-airwaves-to-your-iphone-mastery-of-podcast-downloads/"><u>In 2024, From Airwaves to Your iPhone  Mastery of Podcast Downloads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-subnet-shift-a-guide-to-win11-networks/"><u>Master the Subnet Shift: A Guide to Win11 Networks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-errors-fixing-loadlib-failure-87/"><u>Navigating Windows Errors: Fixing LoadLib Failure 87</u></a></li>
<li><a href="https://win11-tips.techidaily.com/onedrive-error-resolution-guide-for-windows-enthusiasts/"><u>OneDrive Error Resolution Guide for Windows Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-tasks-the-power-of-flow-launcher-in-windows/"><u>Optimize Tasks: The Power of Flow Launcher in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-net-core-not-installed-app-issue-in-windows/"><u>Overcoming .NET Core Not Installed App Issue in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-lan-access-blockades-in-winmc/"><u>Overcoming LAN Access Blockades in WinMC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/powershell-command-for-extracting-ip-and-mac-addresses/"><u>PowerShell Command for Extracting IP & MAC Addresses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redressing-invisible-lan-windows-network-guide/"><u>Redressing Invisible LAN: Windows Network Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-faded-bios-boot-options/"><u>Remedy for Faded BIOS Boot Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-speaker-functionality-in-computers-abruptly/"><u>Restore Speaker Functionality in Computers Abruptly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionize-your-pc-top-winners-from-microsofts-store/"><u>Revolutionize Your PC: Top Winners From Microsoft's Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-system-controls-learn-how-to-use-4-techniques-for-disk-editor-on-win11/"><u>Seamless System Controls: Learn How to Use 4 Techniques for Disk Editor on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-your-digital-life-winning-crypto-apps-ranked-150-chars/"><u>Secure Your Digital Life: Winning Crypto Apps Ranked (150 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-your-system-crafting-a-custom-uninstall-menu-for-win/"><u>Simplify Your System: Crafting a Custom Uninstall Menu for Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-git-operations-github-desktop-and-windows-11-explained/"><u>Simplifying Git Operations: GitHub Desktop and Windows 11 Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-authorization-snags-head-on/"><u>Tackling Windows Authorization Snags Head-On</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/the-language-and-usage-of-pfp-in-tiktok-space/"><u>The Language and Usage of PFP in TikTok Space</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-next-gen-samsung-gear-360-finding-your-perfect-replacement/"><u>The Next Gen Samsung Gear 360 - Finding Your Perfect Replacement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-fix-guide-combatting-a-non-active-wsresetexe/"><u>The Ultimate Fix Guide: Combatting a Non-Active WSReset.exe</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-oppo-reno-10-pro-5g-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Oppo Reno 10 Pro 5G Reset Code | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-grandmas-old-computer-for-better-use/"><u>Transform Your Grandma’s Old Computer for Better Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-eliminating-no-servers-found-in-apex-legends-(156-chars/"><u>Troubleshooting: Eliminating 'No Servers Found' In Apex Legends (<156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-fury-not-frustration-fixing-lag-in-sw-battlefront-2/"><u>Unleash Fury, Not Frustration: Fixing Lag in SW Battlefront 2</u></a></li>
<li><a href="https://win-dash.techidaily.com/updated-epson-wf-2630-drivers-now-available-compatible-with-win7-81-and-10/"><u>Updated Epson WF-2630 Drivers Now Available: Compatible with Win7, 8.1 & 10</u></a></li>
<li><a href="https://driver-install.techidaily.com/windows-compatible-hp-p1102w-drivers/"><u>Windows Compatible HP P1102w Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-mail-troubleshooting-unraveling-the-zero-x-eight-oh-three-one-f-mystery/"><u>Windows Mail Troubleshooting: Unraveling the Zero X Eight Oh Three One F Mystery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-wisdom-three-routes-to-your-games-data/"><u>Windows Wisdom: Three Routes to Your Games' Data</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>