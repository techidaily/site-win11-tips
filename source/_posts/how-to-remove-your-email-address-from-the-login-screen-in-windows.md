---
title: How to Remove Your Email Address From the Login Screen in Windows
date: 2024-09-10T02:43:59.472Z
updated: 2024-09-16T19:15:01.049Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Remove Your Email Address From the Login Screen in Windows
excerpt: This Article Describes How to Remove Your Email Address From the Login Screen in Windows
keywords: Removing Email Login Windows,Logout Email Field Clearance,Erase Usermail Windows Sign-In,Unlink Email From Windows Login,Disconnect Email From PC Access,Delete Email From Windows Login Screen,Exclude Email on Windows Log In
thumbnail: https://thmb.techidaily.com/23f13f96d936d78089a7e8a3b93e560ac0ab8587601498f32a131493f3f787f8.jpg
---

## How to Remove Your Email Address From the Login Screen in Windows

 If you frequently use your computer in public places, it's a good idea to remove your email address from the Windows login screen. This means people can't get your email address if they see your screen over your shoulder.

 You can accomplish this using the Settings app, Group Policy Editor, or Registry Editor. In this post, we've covered all these methods in detail.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Hide Email Address From Windows Login Screen Using the Settings App

 The Windows Settings app provides a quick way to hide account information from the login screen. So, if you are in a rush, use the following steps to remove user email addresses from the Windows login screen.

1. Press**Win + I** or use one of the[many ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Accounts > Sign-in options** .
3. Under**Additional settings** , toggle off the switch next to **Show account details such as my email address on the sign-in screen** .  
![Hide Email From Windows Login Screen Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-settings-app.jpg)

## 2\. How to Hide Email Address From Windows Login Screen Using the Group Policy Editor

 The Group Policy Editor (or gpedit.msc) is a handy Windows tool for configuring advanced system settings. You can also this tool to hide your email address from the Windows login screen.

 Note that the Group Policy Editor is only available on Windows Professional, Education, and Enterprise editions. If your PC is running Windows Home, check out[how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

1. Press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the search box and select the first result that appears.
3. Use the left pane to navigate to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options** .
4. Double-click the **Interactive Logon: Display user information when the session is locked** policy on your right.
5. In the properties window, click the drop-down menu to select the**Do not display user information** option.
6. Click**Apply** followed by**OK** .  
![Hide Email From Windows Login Screen Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-group-policy-editor.jpg)
7. Next, double-click on the**Interactive logon: Do not display last user name** policy from the same section.
8. Select**Enabled** in the properties window.
9. Click**Apply** followed by**OK** to save changes.

## 3\. How to Hide Email Address From Windows Login Screen Using the Registry Editor

 If the above two methods don’t work for some reason, you can make changes to the Windows registry files to hide your email address from the login screen. For that, you’ll need to use the Registry Editor on Windows.

 When it comes to editing Registry files, it's important to be cautious as making incorrect changes can cause irreversible damage to your PC. We recommend you either back up all the registry files or create a restore point before you make any changes. If you need help with that, check our guides on[how to back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and[how to create a restore point in Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

 Once you’re done with that, use the following steps to hide your email address from the Windows login screen via Registry Editor.

1. Press**Win + X** to open the Power User menu and select**Run** from the list.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows > System** .
5. Right-click on the**System** key and select**New > DWORD (32-bit) Value** .
6. Rename the DWORD to**BlockUserFromShowingAccountDetailsOnSignin** .
7. Double-click on the newly created DWORD and enter**1** in the**Value data** field. Then, click**OK** .  
![Hide Email From Windows Login Screen Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-registry-editor.jpg)

 Exit the Registry Editor and restart your PC for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118305/7443" target="_top" id="2118305">
  <img src="//a.impactradius-go.com/display-ad/7443-2118305" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118305/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://driver-error.techidaily.com/7770-graphics-card-up-and-running-with-instant-driver-downloads/"><u>7770 Graphics Card Up and Running with Instant Driver Downloads</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/blueprinting-a-dynamic-tiktok-end-credits-rollout/"><u>Blueprinting a Dynamic TikTok End-Credits Rollout</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-se-2022-to-others-ios-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone SE (2022) To Others ios devices? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/mastering-photo-capture-techniques-of-smart-hdr-3-and-4-modules-for-2024/"><u>Mastering Photo Capture Techniques of Smart HDR 3 & 4 Modules for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-download-adobe-premiere-pro-cs6-for-mac-os-x-free-trial-full-version/"><u>New Download Adobe Premiere Pro CS6 for Mac OS X (Free Trial, Full Version)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-hurdle-of-winscomrssvdll-errors-on-pc/"><u>Overcoming the Hurdle of WinscomrssvDll Errors on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-convert-mkv-to-mp4-with-windows-software/"><u>Quick Guide: Convert MKV to MP4 with Windows Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-notification-for-windows-11-webcamera-access/"><u>Securing Notification for Windows 11 WebCamera Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-prevent-autostarted-microsoft-marketplace/"><u>Techniques to Prevent Autostarted Microsoft Marketplace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-users-handbook-for-changing-windows-pin/"><u>The User's Handbook for Changing Windows PIN</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-correcting-the-driver-power-management-failures-in-windows-systems/"><u>Troubleshooting Tips: Correcting the Driver Power Management Failures in Windows Systems</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/xiaomi-14-pro-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>Xiaomi 14 Pro ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
</ul></div>

