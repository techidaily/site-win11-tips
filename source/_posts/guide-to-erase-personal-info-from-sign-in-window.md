---
title: Guide to Erase Personal Info From Sign-In Window
date: 2024-06-25T16:39:09.040Z
updated: 2024-06-26T16:39:09.040Z
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
<li><a href="https://win11-tips.techidaily.com/synchronizing-sound-pathways-resolving-paudio-in-winaudacity/"><u>Synchronizing Sound Pathways: Resolving PAudio in WINAudacity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sync-your-schedule-how-to-reset-windows-time-service/"><u>Sync Your Schedule: How to Reset Windows Time Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-app-start-issue-qt-plugin-not-available/"><u>Troubleshooting App Start Issue: Qt Plugin Not Available</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-adjust-windows-activity-lock/"><u>How to Adjust Windows Activity Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-approach-to-using-and-revoking-windows-terminal-focus/"><u>A Practical Approach to Using & Revoking Windows Terminal Focus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-controlling-sounds-on-windows-11/"><u>The Ultimate Guide to Controlling Sounds on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-outlooks-failing-notification-system-a-user-friendly-approach/"><u>Troubleshooting Outlook's Failing Notification System: A User-Friendly Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/image-editing-strategies-remove-unwanted-areas/"><u>Image Editing Strategies: Remove Unwanted Areas</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-windows-11-boot-tracks-step-by-step-guide/"><u>Clearing Windows 11 Boot Tracks: Step-by-Step Guide</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-preparing-to-engage-in-googles-video-meetings/"><u>2024 Approved  Preparing to Engage in Google's Video Meetings</u></a></li>
<li><a href="https://fake-location.techidaily.com/best-10-mock-location-apps-worth-trying-on-realme-12-pro-5g-drfone-by-drfone-virtual-android/"><u>Best 10 Mock Location Apps Worth Trying On Realme 12 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-instant-impact-effortless-ways-to-amplify-your-tiktok-pics/"><u>2024 Approved  Instant Impact  Effortless Ways to Amplify Your TikTok Pics</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-optimizing-social-media-for-vimeo-sharing/"><u>[Updated] In 2024, Optimizing Social Media for Vimeo Sharing</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/navigating-to-facebooks-story-archives-quickly/"><u>Navigating to Facebook's Story Archives Quickly</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-use-face-id-to-pay-for-apple-books-purchases-on-iphone-14-pro-max-by-drfone-ios-unlock-ios-unlock/"><u>How to Use Face ID to Pay for Apple Books Purchases on iPhone 14 Pro Max</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-unboundscreen-capturing-every-gaming-moment-for-free/"><u>[New] UnboundScreen  Capturing Every Gaming Moment for FREE</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-honor-magic5-ultimate-drfone-by-drfone-virtual-android/"><u>In 2024, Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Honor Magic5 Ultimate | Dr.fone</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-top-converter-tools-download-4k-videos-in-mp4-format-with-ease/"><u>New In 2024, Top Converter Tools Download 4K Videos in MP4 Format with Ease</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-best-gadgets-to-reduce-camera-jiggle-effects/"><u>2024 Approved  Best Gadgets to Reduce Camera Jiggle Effects</u></a></li>
</ul></div>
