---
title: Efficient Ways to Delete Email From Windows Sign-In Screen
date: 2024-06-25T16:08:36.971Z
updated: 2024-06-26T16:08:36.971Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Efficient Ways to Delete Email From Windows Sign-In Screen
excerpt: This Article Describes Efficient Ways to Delete Email From Windows Sign-In Screen
keywords: Sign-In Screen Cleanup,Email Removal Tips,Deleting Windows Emails,Quick Email Disabling,Contact Panel Purge,Simplify Inbox Clutter,Remove Emails Fast
thumbnail: https://thmb.techidaily.com/8d42a5be41c7b4a2ee5933ca8170ed38361404ba710cadb2872cd630ac7e122c.jpg
---

## Efficient Ways to Delete Email From Windows Sign-In Screen

 If you frequently use your computer in public places, it's a good idea to remove your email address from the Windows login screen. This means people can't get your email address if they see your screen over your shoulder.

 You can accomplish this using the Settings app, Group Policy Editor, or Registry Editor. In this post, we've covered all these methods in detail.

## 1\. How to Hide Email Address From Windows Login Screen Using the Settings App

 The Windows Settings app provides a quick way to hide account information from the login screen. So, if you are in a rush, use the following steps to remove user email addresses from the Windows login screen.

1. Press**Win + I** or use one of the [many ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Accounts > Sign-in options** .
3. Under**Additional settings** , toggle off the switch next to **Show account details such as my email address on the sign-in screen** .  
![Hide Email From Windows Login Screen Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-settings-app.jpg)

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
7. Next, double-click on the**Interactive logon: Do not display last user name** policy from the same section.
8. Select**Enabled** in the properties window.
9. Click**Apply** followed by**OK** to save changes.

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
<li><a href="https://win11-tips.techidaily.com/smooth-switch-the-best-windows-apps-for-ex-mac-users/"><u>Smooth Switch: The Best Windows Apps for Ex-Mac Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-outlooks-non-synchronization-in-windows-os/"><u>How to Rectify Outlook's Non-Synchronization in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-applying-apple-maps-to-windows/"><u>Step-by-Step Guide: Applying Apple Maps to Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-copy-paste-not-working-in-chrome-edge-and-firefox-on-windows/"><u>How to Fix Copy-Paste Not Working in Chrome, Edge, and Firefox on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-zero-error-in-windows-sandbox-missing-hypervisor-solution/"><u>Fixing Zero Error in Windows Sandbox - Missing Hypervisor Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disguised-delayers-innocuous-apps-hindering-pc-speed/"><u>Disguised Delayers: Innocuous Apps Hindering PC Speed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-fixing-memory-detection-problems/"><u>Understanding and Fixing Memory Detection Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-a-convenient-upgrade-notification-toolbar-in-windows-1111/"><u>Adding a Convenient Upgrade Notification Toolbar in Windows 11/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-9-methods-resolving-wwe-2k23-freeze-in-windows-11/"><u>Top 9 Methods: Resolving WWE 2K23 Freeze in Windows 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-alternatives-to-xsplit-for-digital-media-masters/"><u>In 2024, Alternatives to Xsplit for Digital Media Masters</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-enhancing-speed-for-vimeo-playback-for-2024/"><u>[Updated] Enhancing Speed for Vimeo Playback for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-where-is-the-best-place-to-catch-dratini-on-vivo-x100-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Where Is the Best Place to Catch Dratini On Vivo X100 Pro | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-the-secret-behind-successful-igtv-uploads-from-h-videos/"><u>[Updated] 2024 Approved  The Secret Behind Successful IGTV Uploads From H-Videos</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-maximizing-video-quality-in-zoom-conferences-on-win11/"><u>In 2024, Maximizing Video Quality in Zoom Conferences on Win11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-prime-open-source-tools-for-educational-screenshots/"><u>In 2024, Prime Open-Source Tools for Educational Screenshots</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-apple-iphone-15-pro-data-from-ios-itunes-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How to Recover Apple iPhone 15 Pro Data From iOS iTunes? | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-3dlut-mobility-boost-image-and-video-quality/"><u>In 2024, 3DLUT Mobility  Boost Image & Video Quality</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-preserving-your-snapshots-mobile-and-desktop-compatible/"><u>[New] 2024 Approved  Preserving Your Snapshots  Mobile & Desktop Compatible</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/slip-up-on-tiktok-how-to-get-back-content-for-2024/"><u>Slip-Up on TikTok  How to Get Back Content for 2024</u></a></li>
</ul></div>
