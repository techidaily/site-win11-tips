---
title: How to Stop Windows Users From Changing the Date and Time
date: 2024-06-25T16:45:28.276Z
updated: 2024-06-26T16:45:28.276Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Stop Windows Users From Changing the Date and Time
excerpt: This Article Describes How to Stop Windows Users From Changing the Date and Time
keywords: Stopping DST Change on PCs,Prevent Windows Time Modification,Anti-TimeShift in Windows,Block Clock Adjustment WIN,Secure Windows Date Settings,Disable System Time Editing,Protect Windows Timestamps
thumbnail: https://thmb.techidaily.com/46bc9e67353768ac792e1534a64f3c2875130c736cfcb08614e4c3a629de687e.jpg
---

## How to Stop Windows Users From Changing the Date and Time

 You’re using your Windows device and notice something strange in the date and time settings. Someone has changed the settings without your knowledge or permission. This makes it difficult to stay on schedule with tasks and activities. In this guide, we’ll show how to stop anonymous users from changing date and time settings on Windows computers.

## How To Prevent Users From Changing the Date and Time on Windows

 There are two ways to prevent users from changing Windows date and time. The first is to use Group Policy Editor, a system administration tool designed to control computer behavior in an organization. While the second way is to use Registry Editor, which allows you to modify Windows registry settings.

 For both methods, you need administrative access to the computer to change it. Once you’ve made the changes, nobody can alter the date and time settings. Let’s look at each method in more detail.

## 1\. Use the Group Policy Editor

 If your computer is part of an organization and users often change the date and time, use Group Policy Editor to stop it. This will prevent those with limited access to the computer from altering the date and time. However, this method only works for Windows Pro, Enterprise, or Education Editions.

 So, if you have Windows Home Edition, this won’t work. In that case, you must first [activate the Group Policy Editor for Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). If it seems complicated, skip it and try the next solution instead.

 Follow these steps to prevent users from changing the date and time:

1. Press **Win + R** on your keyboard to open the Run window.
2. Type **gpedit.msc** in the text box and press Enter. This will open the Group Policy Editor window.
3. On the left side of the window, navigate to the following path:  
Computer Configuration > Administrative Templates > System > Locale Services
4. In the right-side pane, double-click on **Disallow user override of locale settings**.  
![Disallow user override of locale settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/disallow-user-override-of-locale-settings.jpg)
5. In the pop-up window, check the **Enabled** radio button.
6. Then click **Apply** \> **OK** to save the changes.

 This will block anyone from changing the date and time settings on your computer. However, if you have administrative access to the computer, you can still alter the settings.

 If you want to revert to the default settings later, open Group Policy Editor again and change the value of Disallow user override of locale settings back to Not Configured or Disabled. This way, users can change the time and date again.

## 2\. Tweak the Registry Editor

 If you’re using Windows Home Edition or have disabled the Group Policy Editor, use the Registry Editor to protect date and time settings. This method is more advanced and has a higher risk of system damage.

 In that case, [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it. Doing so will restore settings if something goes wrong.

 Follow these steps to stop users from changing the time and date via the registry:

1. [Open the Run command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** in the field and press Enter. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. In the Registry Editor window, navigate to the following path:  
HKEY_CURRENT_USER\Software\Policies\Microsoft\Control Panel\International\
4. If the International folder doesn’t exist, create one. To do that, right-click on Control Panel and select **New** \> **Key**. Name it **International**.
5. Then right-click on **International** and select New > DWORD (32-bit) Value.
6. Name the newly created value **PreventUserOverrides**.
7. Double-click on the **PreventUserOverrides** DWORD value.  
![Use Registry Editor to Prevent Users From Chaning date and time settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/use-registry-editor-to-prevent-users-from-chaning-date-and-time-settings.jpg)
8. In the pop-up window, change the Value data to **1** and click **OK**.

 Once you’ve made the changes, close the Registry Editor window and restart your computer.

 To undo this restriction, delete the **PreventUserOverrides** DWORD value from the registry or change the value to **0**. Doing so will enable users to change the time and date again.

## Stop Windows Time and Date Changes

 Now stop unauthorized users from changing the date and time settings on your Windows computer. This keeps your tasks and activities on track. If necessary, you can always undo this restriction.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/proven-strategies-for-unlocking-store-apps-directory/"><u>Proven Strategies for Unlocking Store Apps Directory</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-solution-for-0x80072af9-issue/"><u>Mastering Solution for 0X80072AF9 Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfecting-snip-tool-text-edits-on-win-11/"><u>Perfecting Snip Tool Text Edits on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-mouse-response-time-on-windows-devices/"><u>Optimizing Mouse Response Time on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategizing-overheating-mitigation-in-windows/"><u>Strategizing Overheating Mitigation in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-app-usage-a-comprehensive-review/"><u>Window's App Usage: A Comprehensive Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reduce-chrome-distractions-in-windows-1110/"><u>Reduce Chrome Distractions in Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-starting-wordpad-efficiently-on-windows/"><u>Essential Guide: Starting WordPad Efficiently on Windows</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-fake-snapchat-location-on-vivo-x-fold-2-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fake Snapchat Location on Vivo X Fold 2 | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-masterful-bots-to-take-discord-engagement-to-new-heights/"><u>[New] Masterful Bots to Take Discord Engagement To New Heights</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/disabling-apple-iphone-7-parental-restrictions-withwithout-password-by-drfone-ios/"><u>Disabling Apple iPhone 7 Parental Restrictions With/Without Password</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-blending-past-and-present-film-aesthetics/"><u>[Updated] Blending Past and Present Film Aesthetics</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-deal-with-the-samsung-galaxy-f54-5g-screen-black-but-still-works-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Deal With the Samsung Galaxy F54 5G Screen Black But Still Works? | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-streaming-showdown-obs-or-twitch-studio/"><u>[Updated] 2024 Approved  Streaming Showdown  OBS or Twitch Studio</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-effective-communication-in-live-discovers-with-our-guide/"><u>[New] In 2024, Effective Communication in Live Discovers with Our Guide</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-discover-the-best-yoga-vlogs-perfect-balance-guide/"><u>2024 Approved  Discover the Best Yoga Vlogs - Perfect Balance Guide</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-how-to-create-and-change-video-cover-on-facebook/"><u>[Updated] How to Create and Change Video Cover on Facebook</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>