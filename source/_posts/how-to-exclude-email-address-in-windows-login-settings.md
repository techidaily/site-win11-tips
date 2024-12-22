---
title: How to Exclude Email Address in Windows Login Settings
date: 2024-12-19T21:19:09.302Z
updated: 2024-12-21T17:59:07.317Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Exclude Email Address in Windows Login Settings
excerpt: This Article Describes How to Exclude Email Address in Windows Login Settings
keywords: Exclude Email Config,Login Security,Remove E-Mail On Windows,Disable Email Access,Windows E-Mail Exclusion,Setup No Email Signin,Filter Out Emails Login
thumbnail: https://thmb.techidaily.com/9ed1822c884a606f5ae36981b782d8b43a1eaddd1153302103151c40c41208fa.jpg
---

## How to Exclude Email Address in Windows Login Settings

 If you frequently use your computer in public places, it's a good idea to remove your email address from the Windows login screen. This means people can't get your email address if they see your screen over your shoulder.

 You can accomplish this using the Settings app, Group Policy Editor, or Registry Editor. In this post, we've covered all these methods in detail.

## 1\. How to Hide Email Address From Windows Login Screen Using the Settings App

 The Windows Settings app provides a quick way to hide account information from the login screen. So, if you are in a rush, use the following steps to remove user email addresses from the Windows login screen.

1. Press**Win + I** or use one of the[many ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Accounts > Sign-in options** .
3. Under**Additional settings** , toggle off the switch next to **Show account details such as my email address on the sign-in screen** .  
![Hide Email From Windows Login Screen Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qv4Qm7kpeMs?si=9fv5SOS5a2DvixTK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nl0Z0eth1u4?si=0eecOBNfc--51AJO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PNw3Lb26wFA?si=5NR1XRVSp41EQYMy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

8. Select**Enabled** in the properties window.
9. Click**Apply** followed by**OK** to save changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/j5gTm5KxtQ0?si=onF1rBS2nEM5nLGg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aknYnDfODro?si=zONIVzA9FFq0rLOD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Exit the Registry Editor and restart your PC for the changes to take effect.

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
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-primary-footage-document-critique-with-asides/"><u>[New] 2024 Approved Primary Footage Document Critique with Asides</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-essential-tips-for-pinning-friends-on-snapchat/"><u>[Updated] 2024 Approved Essential Tips for Pinning Friends on Snapchat</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-win1011-crash-code-issue/"><u>Correcting Win10/11 Crash Code Issue</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/easy-guide-how-to-bypass-infinix-note-30-frp-android-10111213-by-drfone-android/"><u>Easy Guide How To Bypass Infinix Note 30 FRP Android 10/11/12/13</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-a-dormant-wi-fi-hotspot-in-windows-11/"><u>Enabling a Dormant Wi-Fi Hotspot in Windows 11</u></a></li>
<li><a href="https://win-bits.techidaily.com/expert-tips-for-troubleshooting-and-updating-pc-components-with-fresh-drivers-on-windows-yl-tech-solutions/"><u>Expert Tips for Troubleshooting & Updating PC Components with Fresh Drivers on Windows - YL Tech Solutions</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/how-to-transfer-from-apple-iphone-se-2020-to-iphone-8x11-drfone-by-drfone-transfer-from-ios/"><u>How to Transfer from Apple iPhone SE (2020) to iPhone 8/X/11 | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-forgotten-the-voicemail-password-of-infinix-note-30-5g-try-these-fixes-by-drfone-android/"><u>In 2024, Forgotten The Voicemail Password Of Infinix Note 30 5G? Try These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-your-clocks-methods-for-windows-time-repair/"><u>Reviving Your Clocks: Methods for Windows Time Repair</u></a></li>
<li><a href="https://win11.techidaily.com/roblox-error-403-resolving-access-denied-in-win/"><u>Roblox Error 403: Resolving Access Denied in Win</u></a></li>
<li><a href="https://screen-capture.techidaily.com/seamless-techniques-for-saving-facetime-chats-live/"><u>Seamless Techniques for Saving FaceTime Chats Live</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-circumvent-installation-blockers-in-windows-11/"><u>Techniques to Circumvent Installation Blockers in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-entering-and-exiting-windows-terminals-concentration-zone/"><u>Tips for Entering & Exiting Windows Terminal's Concentration Zone</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-the-lenovo-thinkpad-x13s-a-high-end-arm-equipped-ultraportable-with-cutting-edge-5g-features-and-robust-battery-performance/"><u>Unveiling the Lenovo ThinkPad X13s: A High-End Arm-Equipped Ultraportable with Cutting-Edge 5G Features and Robust Battery Performance</u></a></li>
</ul></div>

