---
title: "Balancing Security & Usability: User Access Levels on Windows"
date: 2024-08-16T01:06:59.024Z
updated: 2024-08-17T01:06:59.024Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Balancing Security & Usability: User Access Levels on Windows"
excerpt: "This Article Describes Balancing Security & Usability: User Access Levels on Windows"
keywords: SecureUsabilityAccess,UXWindowsSecurityLvl,UsableAccessControlWin,BalancedUserPermissions,SecurityInUAWin,AccessLevelBalanceWin,UsageSecurityWindows
thumbnail: https://thmb.techidaily.com/302790bfdd6c387be2ce7104b2f0ec7045e52a09e036ffbf26a83ecf9455ec5e.jpg
---

## Balancing Security & Usability: User Access Levels on Windows

 By default, standard users on Windows can run programs with elevated privileges if they enter an administrator password when prompted by User Access Control (UAC).

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

## The UAC Behaviors Available for Standard User Accounts

 Unlike when [changing UAC behaviors for administrator accounts](https://www.makeuseof.com/change-user-access-control-works-administrators-windows/), the behaviors for standard user accounts are a little more limited. According to the [Microsoft Learn](https://learn.microsoft.com/en-us/windows/security/threat-protection/security-policy-settings/user-account-control-behavior-of-the-elevation-prompt-for-standard-users) website, here are the behaviors you can choose and what they mean:

* **Automatically deny elevation requests**: This option returns an **Access denied** error message to standard users when they try to perform an operation that requires elevation of privilege. Most organizations that run desktops as standard users configure this policy to reduce help desk calls.
* **Prompt for credentials on the secure desktop**: When an operation requires elevation of privilege, the user is prompted on the secure desktop to enter a different username and password. If the user enters valid credentials, the operation continues with the applicable privilege.
* **Prompt for credentials**: An operation that requires elevation of privilege prompts the user to type an administrative username and password. If the user enters valid credentials, the operation continues with the applicable privilege.

 The default UAC behavior for standard user accounts is **Prompt for credentials**, but Microsoft recommends you change it to **Automatically deny elevation requests**. That way, only users with administrator accounts can decide how the UAC behaves and make choices that will keep the computer safe.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Change the UAC Behavior for Standard Users in the Local Group Policy Editor

 The easiest way to change the way UAC behaves for standard users is to tweak the **User Account Control: Behavior of the elevation prompt for standard users** policy. To do that, [open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and follow the steps below.

 The Local Group Policy Editor isn't available by default on Windows Home. As such, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Head to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options**.
2. Right-click the **User Account Control: Behavior of the elevation prompt for standard users** policy and select **Properties** in the menu.  
![modifying the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Expand the dropdown and choose a different UAC behavior.  
![editing the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/editing-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Click **OK**.

 Keep in mind that only administrators can change the behavior of the UAC. If a standard user tried to change it using the Local Group Policy Editor, for example, they'd probably get an **Access denied** error message.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Change the UAC Behavior for Standard Users in the Registry Editor

 If you're looking for another way to change UAC behavior for standard users, or the [Local Group Policy is not working](https://www.makeuseof.com/windows-local-group-policy-unresponsive/) on your computer, you can make changes in the Windows registry instead.

 Before you do that, however, we recommend you [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) to protect your computer in case you make a mistake. Once you do that, [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) and follow the steps below:

1. Copy **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** and paste it into the address bar at the top of the Registry Editor.  
![the System key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-key-registry-editor.jpg)
2. Press **Enter** on your keyboard to go to the **System** key.
3. Right-click the **ConsentPromptBehaviorUser** value in the right panel and select **Modify**.  
![modifying the ConsentPromptBehaviorUser value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-consentpromptbehavioruser-in-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->
4. In the **Value data** text box, enter **0** for **Automatically deny elevation requests**, **1** for **Prompt for credentials on the secure desktop**, or **3** for **Prompt for credentials**.  
![setting Value data for ConsentPromptbehavior Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/setting-value-data-for-consentpromptbehavior-registry-editor.jpg)
5. Click **OK**.

 Now restart your computer to allow the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://vp-tips.techidaily.com/new-in-2024-home-cinematic-wonders-fastest-tips-and-tricks/"><u>[New] In 2024, Home Cinematic Wonders  Fastest Tips & Tricks</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-transform-your-content-game-with-creator-studio-insight/"><u>[Updated] 2024 Approved  Transform Your Content Game with Creator Studio Insight</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-streamline-task-management-with-safaris-picture-in-picture/"><u>[Updated] Streamline Task Management with Safari's Picture In Picture</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-the-ultimate-framework-perfecting-live-broadcasts-via-obs-and-zoom/"><u>[Updated] The Ultimate Framework  Perfecting Live Broadcasts via OBS & Zoom</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-watch-more-not-less-secrets-to-free-youtube-gains/"><u>[Updated] Watch More, Not Less  Secrets to Free YouTube Gains</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-perfect-obs-settings-for-low-cost-hardware/"><u>2024 Approved  Perfect OBS Settings for Low-Cost Hardware</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-smoothly-alter-color-grades-with-luts-abroad/"><u>2024 Approved  Smoothly Alter Color Grades with LUTs, Abroad</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-unintended-self-appearance-fixes-for-video-calls-and-chats/"><u>2024 Approved  Unintended Self-Appearance Fixes for Video Calls and Chats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combatting-failed-rpc-in-windows-top-solutions/"><u>Combatting Failed RPC in Windows: Top Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-your-windows-pdf-viewers/"><u>Customizing Your Window's PDF Viewers</u></a></li>
<li><a href="https://location-social.techidaily.com/does-find-my-friends-work-on-huawei-p60-drfone-by-drfone-virtual-android/"><u>Does find my friends work on Huawei P60 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-experience-with-active-phone-link-alerts/"><u>Enhancing Windows Experience with Active Phone Link Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicate-the-zero-error-on-new-win11-systems/"><u>Eradicate the Zero Error on New Win11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eternal-trash-bin-configurations-in-your-windows-1011-dock/"><u>Eternal Trash Bin Configurations in Your Windows 10/11 Dock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-advice-on-installing-win11s-version-22h2-upgrade-successfully/"><u>Expert Advice on Installing Win11's Version 22H2 Upgrade Successfully</u></a></li>
<li><a href="https://howto.techidaily.com/gmail-not-working-on-vivo-y78-5g-7-common-problems-and-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Gmail Not Working on Vivo Y78 5G 7 Common Problems & Fixes | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-windows-key-onoff-switch-techniques/"><u>Guide to Windows Key: On/Off Switch Techniques</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-do-motorola-moto-g84-5g-screen-sharing-drfone-by-drfone-android/"><u>How To Do Motorola Moto G84 5G Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-microsoft-365-error-code-30015-26-on-windows/"><u>How to Fix the Microsoft 365 Error Code 30015-26 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-windows-update-automatically-replacing-your-amd-graphics-driver/"><u>How to Fix Windows Update Automatically Replacing Your AMD Graphics Driver</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-system-of-iphone-se-2022-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair System of iPhone SE (2022)? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-apple-iphone-6s-screen-mirroring-you-must-know-drfone-by-drfone-ios/"><u>In 2024, Apple iPhone 6s Screen Mirroring You Must Know | Dr.fone</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-cooking-crusaders-youtube-stars-serving-up-deliciousness/"><u>In 2024, Cooking Crusaders  YouTube Stars Serving Up Deliciousness</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-the-activation-lock-on-your-ipad-and-iphone-12-pro-max-without-apple-account-by-drfone-ios/"><u>In 2024, How to Remove the Activation Lock On your iPad and iPhone 12 Pro Max without Apple Account</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-unlock-the-secrets-of-your-lost-iphone-x/"><u>In 2024, Unlock the Secrets of Your Lost iPhone X</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/in-2024-video-traffic-triumph-key-youtube-seo-tools/"><u>In 2024, Video Traffic Triumph - Key YouTube SEO Tools</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/mastering-adobe-premiere-top-6-essential-tips-for-pro-level-video-editing-for-2024/"><u>Mastering Adobe Premiere Top 6 Essential Tips for Pro-Level Video Editing for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-privacy-remove-login-email-in-windows/"><u>Mastering Privacy: Remove Login Email in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-repair-tools-crafting-troubleshooter-shortcuts/"><u>Mastering Windows Repair Tools: Crafting Troubleshooter Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterpieces-at-your-fingertips-4-notable-new-paint-features/"><u>Masterpieces at Your Fingertips: 4 Notable New Paint Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-through-difficulties-handling-winscomrsvdll-problems/"><u>Navigate Through Difficulties: Handling WinscomrsvDll Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-key-discrepancies-an-essential-guide-to-troubleshooting-on-windows-11/"><u>Navigating Key Discrepancies: An Essential Guide to Troubleshooting on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/nircmd-guide-for-power-users-optimize-win-commands/"><u>NirCmd Guide for Power Users: Optimize Win Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-robloxs-code-403-issue-on-pc/"><u>Overcoming Roblox's Code 403 Issue on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-disconnected-spotify-pc-app/"><u>Quick Fix for Disconnected Spotify PC App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-functional-wastebin-icon-in-windows-11/"><u>Reinstating Functional Wastebin Icon in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seal-the-gap-with-6-key-strategies-reviving-disappearing-windows-in-windows-11/"><u>Seal the Gap with 6 Key Strategies: Reviving Disappearing Windows in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-procedures-for-resetting-windows-updates/"><u>Simplified Procedures for Resetting Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-steps-for-updating-administrator-in-win11-environment/"><u>Streamlined Steps for Updating Administrator in Win11 Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-execution-optimizing-android-studio-on-windows/"><u>Swift Execution: Optimizing Android Studio on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-temperature-spikes-during-high-performance-gaming/"><u>Taming Temperature Spikes During High-Performance Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-integrating-secondary-antivirus-without-defenders-limits/"><u>Techniques for Integrating Secondary Antivirus without Defender’s Limits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-prevent-activation-of-windows-mobility-center-win-11/"><u>Tips: Prevent Activation of Windows Mobility Center (Win 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tracking-down-image-files-for-windows-11-backgrounds/"><u>Tracking Down Image Files for Windows 11 Backgrounds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-no-hypervisor-in-windows-sandbox/"><u>Troubleshooting No Hypervisor in Windows Sandbox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-potential-optimizing-your-system-with-intel-drivers/"><u>Unlocking Potential: Optimizing Your System with Intel Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-wordpad-a-window-guide-to-access/"><u>Unlocking WordPad: A Window Guide to Access</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/virtual-interview-mastery-2024s-proven-strategies-to-land-your-dream-role/"><u>Virtual Interview Mastery: 2024'S Proven Strategies to Land Your Dream Role</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ways-to-halt-the-start-of-edge-tabs-in-windows-11/"><u>Ways to Halt the Start of Edge Tabs in Windows 11</u></a></li>
</ul></div>
