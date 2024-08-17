---
title: Guide to Erase Personal Info From Sign-In Window
date: 2024-08-16T01:58:47.506Z
updated: 2024-08-17T01:58:47.506Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Erase Personal Info From Sign-In Window
excerpt: This Article Describes Guide to Erase Personal Info From Sign-In Window
keywords: Delete Login Data,Privacy Sign-Out Guide,Remove User Info,Clear Browser History,Wipe Session Cookies,Erase Account Info,Hide Personal Details
thumbnail: https://thmb.techidaily.com/18d1ae3b93316df7253b6d9ca3430e2e7b9da85a6ae22dbb42da5be064fc57fa.png
---

## Guide to Erase Personal Info From Sign-In Window

 If you frequently use your computer in public places, it's a good idea to remove your email address from the Windows login screen. This means people can't get your email address if they see your screen over your shoulder.

 You can accomplish this using the Settings app, Group Policy Editor, or Registry Editor. In this post, we've covered all these methods in detail.

## 1\. How to Hide Email Address From Windows Login Screen Using the Settings App

 The Windows Settings app provides a quick way to hide account information from the login screen. So, if you are in a rush, use the following steps to remove user email addresses from the Windows login screen.

1. Press**Win + I** or use one of the [many ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Accounts > Sign-in options** .
3. Under**Additional settings** , toggle off the switch next to **Show account details such as my email address on the sign-in screen** .  
![Hide Email From Windows Login Screen Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-settings-app.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
## 2\. How to Hide Email Address From Windows Login Screen Using the Group Policy Editor

 The Group Policy Editor (or gpedit.msc) is a handy Windows tool for configuring advanced system settings. You can also this tool to hide your email address from the Windows login screen.

 Note that the Group Policy Editor is only available on Windows Professional, Education, and Enterprise editions. If your PC is running Windows Home, check out [how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

1. Press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the search box and select the first result that appears.
3. Use the left pane to navigate to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options** .
4. Double-click the **Interactive Logon: Display user information when the session is locked** policy on your right.
5. In the properties window, click the drop-down menu to select the**Do not display user information** option.
6. Click**Apply** followed by**OK** .  
![Hide Email From Windows Login Screen Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Next, double-click on the**Interactive logon: Do not display last user name** policy from the same section.
8. Select**Enabled** in the properties window.
9. Click**Apply** followed by**OK** to save changes.

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. How to Hide Email Address From Windows Login Screen Using the Registry Editor

 If the above two methods don’t work for some reason, you can make changes to the Windows registry files to hide your email address from the login screen. For that, you’ll need to use the Registry Editor on Windows.

 When it comes to editing Registry files, it's important to be cautious as making incorrect changes can cause irreversible damage to your PC. We recommend you either back up all the registry files or create a restore point before you make any changes. If you need help with that, check our guides on [how to back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [how to create a restore point in Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

 Once you’re done with that, use the following steps to hide your email address from the Windows login screen via Registry Editor.

1. Press**Win + X** to open the Power User menu and select**Run** from the list.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows > System** .
5. Right-click on the**System** key and select**New > DWORD (32-bit) Value** .
6. Rename the DWORD to**BlockUserFromShowingAccountDetailsOnSignin** .
7. Double-click on the newly created DWORD and enter**1** in the**Value data** field. Then, click**OK** .  
![Hide Email From Windows Login Screen Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Exit the Registry Editor and restart your PC for the changes to take effect.

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Hiding Your Email Address From the Windows Login Screen Is Easy

 As we just saw, hiding your personal information from the Windows login screen barely takes a couple of minutes, regardless of the method you employ.


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
<li><a href="https://extra-guidance.techidaily.com/new-mastering-the-art-of-tinder-profiles-top-tricks-for-instant-love-interest/"><u>[New] Mastering the Art of Tinder Profiles  Top Tricks for Instant Love Interest</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-enhanced-imagery-at-your-fingertits-iphone-and-androids-sticker-boost-apps/"><u>[Updated] In 2024, Enhanced Imagery at Your Fingertits – iPhone and Android's Sticker-Boost Apps</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-20plus-artistic-assembly-ideas-for-a-brighter-yard/"><u>2024 Approved  20+ Artistic Assembly Ideas for a Brighter Yard</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-motorola-moto-g-5g-2023-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your Motorola Moto G 5G (2023)? | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/arduino-uno-and-windows-compatibility-fixing-driver-challenges-efficiently/"><u>Arduino Uno and Windows Compatibility: Fixing Driver Challenges Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bootstrapping-a-powershell-session-as-an-admin-on-windows-11/"><u>Bootstrapping a PowerShell Session as an Admin on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breached-bitlocker-hold-firm-on-current-security/"><u>Breached BitLocker: Hold Firm on Current Security</u></a></li>
<li><a href="https://win11-tips.techidaily.com/break-free-from-issues-restoring-windows-family-security/"><u>Break Free From Issues: Restoring Windows Family Security</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breakdown-of-windows-11s-latest-enhancements-after-update/"><u>Breakdown of Windows 11'S Latest Enhancements After Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-barriers-for-skyrims-script-enhancement/"><u>Breaking Barriers for Skyrim's Script Enhancement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-what-makes-ai-systems-different/"><u>Breaking Down: What Makes AI Systems Different?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-barrier-enabling-sluggish-batch-files-on-pcs/"><u>Breaking the Barrier: Enabling Sluggish Batch Files on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridge-the-gap-addressing-continuous-ps4-controller-disconnection/"><u>Bridge the Gap: Addressing Continuous PS4 Controller Disconnection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-gaps-in-computing-ai-for-windows-solutions/"><u>Bridging Gaps in Computing: AI for Windows Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-tasks-and-power-in-win11-shortcut-setup/"><u>Bridging Tasks & Power in Win11 Shortcut Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-the-store-reactivation-steps-for-ms-in-windows-11/"><u>Bring Back the Store: Reactivation Steps for MS in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-back-original-settings-to-windows-11-touch-panel/"><u>Bringing Back Original Settings to Windows 11 Touch Panel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-outdated-computers-into-the-win11-era/"><u>Bringing Outdated Computers Into the Win11 Era</u></a></li>
<li><a href="https://win11-tips.techidaily.com/browser-download-techniques-after-windows-installation/"><u>Browser Download Techniques After Windows Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/building-a-window-for-secure-hardware-removal-on-windows-11/"><u>Building a Window for Secure Hardware Removal on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-hidden-taskbar-scan-shield-in-windows-11/"><u>Bypass Hidden Taskbar Scan Shield in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-the-barrier-taking-down-security-questions-on-local-account-win-11/"><u>Bypass the Barrier: Taking Down Security Questions on Local Account (Win 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-unknown-device-error-step-by-step-guide-for-windows-users/"><u>Bypassing 'Unknown Device Error': Step-by-Step Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-built-in-graphics-card-for-second-monitor/"><u>Bypassing Built-In Graphics Card for Second Monitor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-do-not-have-access-error-when-uninstalling-apps/"><u>Bypassing Do Not Have Access Error When Uninstalling Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-firewall-restrictions-allow-browser-networking-in-windows/"><u>Bypassing Firewall Restrictions: Allow Browser Networking in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-hardware-errors-windows-1110-guide/"><u>Bypassing Hardware Errors: Windows 11/10 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-server-slips-resolving-ms-store-failures-in-1011/"><u>Bypassing Server Slips: Resolving MS Store Failures in 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-usb-suspend-windows-11-guide/"><u>Bypassing USB Suspend: Windows 11 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-win-11s-inbuilt-mobility-control/"><u>Bypassing Win 11'S Inbuilt Mobility Control</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-11-admin-lockdown/"><u>Bypassing Windows 11 Admin Lockdown</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-your-geforce-experience-scanning-problem-in-win/"><u>Bypassing Your GeForce Experience Scanning Problem in Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cableless-game-controls-connecting-ps3-to-pc/"><u>Cableless Game Controls: Connecting PS3 to PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cant-delete-temporary-files-in-windows-try-these-fixes/"><u>Can’t Delete Temporary Files in Windows? Try These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/captivating-creations-top-editors-for-videos-on-your-win11-pc/"><u>Captivating Creations: Top Editors for Videos on Your Win11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/capturing-critical-windows-user-alerts-in-action/"><u>Capturing Critical Windows User Alerts in Action</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cease-windows-record-of-app-openings/"><u>Cease Windows Record of App Openings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/celebrate-yuletide-in-stunning-windowscapes/"><u>Celebrate Yuletide in Stunning Windowscapes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/charting-course-past-the-lost-at-sea-xbox-error-in-win11/"><u>Charting Course Past the Lost at Sea Xbox Error in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/choosing-the-best-bittorrent-clients-for-windows-users/"><u>Choosing the Best BitTorrent Clients for Windows Users</u></a></li>
<li><a href="https://tech-revival.techidaily.com/enhance-the-magic-of-dandd-integrating-ai-assisted-creativity/"><u>Enhance the Magic of D&D: Integrating AI-Assisted Creativity</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-best-practices-in-video-posting-choosing-correct-orientation/"><u>In 2024, Best Practices in Video Posting – Choosing Correct Orientation</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-best-sfpr-settings-to-boost-sluggish-clips/"><u>In 2024, Best SFPR Settings to Boost Sluggish Clips</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-card-on-huawei-nova-y91-online-without-jailbreak-by-drfone-android/"><u>In 2024, How to Unlock SIM Card on Huawei Nova Y91 online without jailbreak</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/streamline-free-webinar-organizing-with-youtube-help-for-2024/"><u>Streamline Free Webinar Organizing with YouTube Help for 2024</u></a></li>
</ul></div>
