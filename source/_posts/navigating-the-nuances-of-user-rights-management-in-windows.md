---
title: Navigating the Nuances of User Rights Management in Windows
date: 2024-08-28T01:11:48.770Z
updated: 2024-08-29T01:11:48.770Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating the Nuances of User Rights Management in Windows
excerpt: This Article Describes Navigating the Nuances of User Rights Management in Windows
keywords: UserRightsWindows,ManagingUserPerms,WindowsUserPolicy,PermissionsControlWin,RightsManagementWin,AccessControlWinOS,ProtectingUserWinRights
thumbnail: https://thmb.techidaily.com/f7008ec86977e694421ef724a35a33c6fec32d45741490d50d66c52b24ae9074.jpg
---

## Navigating the Nuances of User Rights Management in Windows

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
3. Expand the dropdown and choose a different UAC behavior.  
![editing the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/editing-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
4. Click **OK**.

 Keep in mind that only administrators can change the behavior of the UAC. If a standard user tried to change it using the Local Group Policy Editor, for example, they'd probably get an **Access denied** error message.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
## How to Change the UAC Behavior for Standard Users in the Registry Editor

 If you're looking for another way to change UAC behavior for standard users, or the [Local Group Policy is not working](https://www.makeuseof.com/windows-local-group-policy-unresponsive/) on your computer, you can make changes in the Windows registry instead.

 Before you do that, however, we recommend you [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) to protect your computer in case you make a mistake. Once you do that, [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) and follow the steps below:

1. Copy **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** and paste it into the address bar at the top of the Registry Editor.  
![the System key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-key-registry-editor.jpg)
2. Press **Enter** on your keyboard to go to the **System** key.
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
3. Right-click the **ConsentPromptBehaviorUser** value in the right panel and select **Modify**.  
![modifying the ConsentPromptBehaviorUser value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-consentpromptbehavioruser-in-registry-editor.jpg)
4. In the **Value data** text box, enter **0** for **Automatically deny elevation requests**, **1** for **Prompt for credentials on the secure desktop**, or **3** for **Prompt for credentials**.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![setting Value data for ConsentPromptbehavior Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/setting-value-data-for-consentpromptbehavior-registry-editor.jpg)
5. Click **OK**.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->

 Now restart your computer to allow the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## Control UAC's Behavior for Standard Users on Windows

 UAC is an integral part of protecting your Windows computer from malicious programs that want to run with elevated privileges. While you can't make it elevate programs without prompting, you can make it stricter by setting it to **Automatically deny elevation requests**. And, as you can see, it is quite easy to do, whether you're using the Local Group Policy Editor or the Registry Editor.

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-capture.techidaily.com/new-essential-strategies-successful-webcam-and-gaming-recordings/"><u>[New] Essential Strategies  Successful Webcam & Gaming Recordings</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-step-by-step-guide-youtube-downloads-for-ios-devices/"><u>[New] In 2024, Step-by-Step Guide  YouTube Downloads for iOS Devices</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-tiktok-to-twitter-sharing-videos/"><u>[Updated] 2024 Approved  TikTok to Twitter  Sharing Videos</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-top-5-websites-for-an-active-social-presence/"><u>[Updated] In 2024, Top 5 Websites for an Active Social Presence</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-experts-picks-the-top-5-professional-drone-brands/"><u>2024 Approved  Expert's Picks  The Top 5 Professional Drone Brands</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-explore-top-5-apps-combining-photography-and-soundscape/"><u>2024 Approved  Explore Top 5 Apps Combining Photography & Soundscape</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-navigating-earnings-skyward-youtube-analytics-and-advertising-guide/"><u>2024 Approved  Navigating Earnings Skyward  YouTube Analytics & Advertising Guide</u></a></li>
<li><a href="https://extra-resources.techidaily.com/becoming-a-metaverse-veteran-top-7-gadgets-for-the-experts/"><u>Becoming a Metaverse Veteran  Top 7 Gadgets for the Experts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-the-slate-executing-a-clean-boot-in-windows-11/"><u>Clearing the Slate: Executing a Clean Boot in Windows 11</u></a></li>
<li><a href="https://article-helps.techidaily.com/decoding-digital-dazzle-an-initial-journey-into-video-standards/"><u>Decoding Digital Dazzle  An Initial Journey Into Video Standards</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-the-most-effective-tool-for-win-soft-dependency/"><u>Discovering the Most Effective Tool for Win Soft Dependency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/empowering-policy-management-using-gpresult/"><u>Empowering Policy Management Using GPResult</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-file-writing-capability-in-windows-1011/"><u>Enhancing File Writing Capability in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-system-safety-with-new-passwords-in-win-11/"><u>Enhancing System Safety with New Passwords in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-procedure-to-clear-steams-domain-name-service-caches/"><u>Essential Procedure to Clear Steam's Domain Name Service Caches</u></a></li>
<li><a href="https://extra-information.techidaily.com/first-timers-insights-into-pixel-density-matters/"><u>First-Timer's Insights Into Pixel Density Matters</u></a></li>
<li><a href="https://some-techniques.techidaily.com/harnessing-gopros-power-for-compelling-time-lapse-clips-for-2024/"><u>Harnessing GoPro's Power for Compelling Time-Lapse Clips for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-bypass-the-admin-restriction-error-message-on-pcs/"><u>How to Bypass the Admin Restriction Error Message on PCs</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-elite-cards-for-uhd-video-creation/"><u>In 2024, Elite Cards for UHD Video Creation</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-essential-vr-companies-for-the-next-decade/"><u>In 2024, Essential VR Companies for the Next Decade</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-from-realme-11-5g-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock from Realme 11 5G Phones with/without a PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/make-full-privilege-access-to-terminal-a-snap-shot/"><u>Make Full-Privilege Access to Terminal A Snap Shot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-concurrent-archive-decompression-in-a-digital-age/"><u>Mastering Concurrent Archive Decompression in a Digital Age</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-gpos-on-user-profiles-in-windows-11-and-11/"><u>Mastering GPOs on User Profiles in Windows 11 & 11</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/maximize-your-access-to-fb-videos-with-our-top-5-picks-for-2024/"><u>Maximize Your Access to FB Videos with Our Top 5 Picks for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-and-rectifying-workspace-errors-in-office-software/"><u>Navigating and Rectifying Workspace Errors in Office Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-extender-writes-to-reduce-power-draw/"><u>Optimizing Extender' Writes to Reduce Power Draw</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-error-0x80041015-on-windows-a-step-by-step-guide/"><u>Overcoming Error 0X80041015 on Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-errors-when-attempting-to-login-to-battlenet/"><u>Overcoming Errors When Attempting to Login to Battle.net</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-input-sluggishness-in-win-os-via-7-fixes/"><u>Overcoming Input Sluggishness in WIN OS via 7 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-text-display-error-w11s-msresource-challenge/"><u>Overcoming Text Display Error: W11's MsResource Challenge</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-your-desktop-image-in-windows-easily/"><u>Personalizing Your Desktop Image in Windows Easily</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/resolving-the-issue-where-is-msvcr70dll/"><u>Resolving the Issue: Where Is MSVCR70.DLL?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-lost-luster-how-to-repeat-steam-accomplishments/"><u>Restore Lost Luster: How to Repeat Steam Accomplishments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-navigation-window-11-power-user-guide/"><u>Simplify Navigation: Window 11 Power User Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-system-crash-code-0xc0000001/"><u>Steps to Resolve System Crash: Code 0xC0000001</u></a></li>
<li><a href="https://win11-tips.techidaily.com/terminal-and-powershell-a-study-on-their-contrasting-traits/"><u>Terminal & PowerShell: A Study on Their Contrasting Traits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-consequences-of-muting-windows-11-notification-tones/"><u>The Consequences of Muting Windows 11 Notification Tones</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/transform-your-chromebook-into-a-linux-powerhouse-2023-edition/"><u>Transform Your Chromebook Into a Linux Powerhouse (2023 Edition)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/triumphant-tech-revival-quick-windows-resets-in-3-steps/"><u>Triumphant Tech Revival: Quick Windows Resets in 3 Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbocharge-ssds-syncing-ssd-fresh-and-windows/"><u>Turbocharge SSDs: Syncing SSD Fresh & Windows</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlock-word-potential-with-ai-powered-automated-drafting/"><u>Unlock Word Potential with AI-Powered Automated Drafting</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-search-tweaks-enhancing-your-experience/"><u>Windows 11'S Search Tweaks: Enhancing Your Experience</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>