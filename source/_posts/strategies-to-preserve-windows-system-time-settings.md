---
title: Strategies to Preserve Windows System Time Settings
date: 2024-11-20T16:46:57.285Z
updated: 2024-11-27T16:21:07.472Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategies to Preserve Windows System Time Settings
excerpt: This Article Describes Strategies to Preserve Windows System Time Settings
keywords: Windows Time Control,Time Setting Safeguard,Save System Clock,Maintain OS Timestamp,Preserve PC Timezone,Secure Date & Time,Protect OS DateTime
thumbnail: https://thmb.techidaily.com/dccea8e74312ef3978115e47791b42d8d3af59ddef7b2d9a4c85759dfb53f1ee.jpg
---

## Strategies to Preserve Windows System Time Settings

 You’re using your Windows device and notice something strange in the date and time settings. Someone has changed the settings without your knowledge or permission. This makes it difficult to stay on schedule with tasks and activities. In this guide, we’ll show how to stop anonymous users from changing date and time settings on Windows computers.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uV3vm805eX0?si=YSPcsFxBcJmoxLsU&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How To Prevent Users From Changing the Date and Time on Windows

 There are two ways to prevent users from changing Windows date and time. The first is to use Group Policy Editor, a system administration tool designed to control computer behavior in an organization. While the second way is to use Registry Editor, which allows you to modify Windows registry settings.

 For both methods, you need administrative access to the computer to change it. Once you’ve made the changes, nobody can alter the date and time settings. Let’s look at each method in more detail.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2Iv3DjT2Fyw?si=pR_z8ZDDVGF2MvKJ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9sk53d1bBhY?si=yaTeDogLb3D4dYu1&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’ve made the changes, close the Registry Editor window and restart your computer.

 To undo this restriction, delete the **PreventUserOverrides** DWORD value from the registry or change the value to **0**. Doing so will enable users to change the time and date again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S0b9szh8vEk?si=NlGzpJ6MN_SJNk5A&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Stop Windows Time and Date Changes

 Now stop unauthorized users from changing the date and time settings on your Windows computer. This keeps your tasks and activities on track. If necessary, you can always undo this restriction.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-elite-remote-meeting-apps-beyond-zoom/"><u>[New] 2024 Approved Elite Remote Meeting Apps Beyond Zoom</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-the-comprehensive-guide-to-capturing-perfect-instagram-covers/"><u>[New] 2024 Approved The Comprehensive Guide to Capturing Perfect Instagram Covers</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ltimate-video-editors-top-8-linux-picks/"><u>[New] Ultimate Video Editors Top 8 Linux Picks</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-speech-to-text-technology-absolutely-gratuitous/"><u>[Updated] 2024 Approved Speech-to-Text Technology, Absolutely Gratuitous</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/best-virtual-background-for-google-meet-video-call-for-2024/"><u>Best Virtual Background for Google Meet Video Call for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-microsoft-store-glitches-code-0x80073cf3/"><u>Conquering Microsoft Store Glitches: Code 0X80073CF3</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/error-code-0xc0000185-what-it-is-and-how-to-fix-it/"><u>Error Code 0Xc0000185: What It Is and How to Fix It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-address-incorrect-file-history-on-your-pc/"><u>Guidelines to Address “Incorrect File History” On Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-identify-and-eliminate-keygen-virus-from-windows-computers/"><u>How to Identify & Eliminate Keygen Virus From Windows Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-browser-blackouts-tactics-to-reopen-sites-in-windows/"><u>Navigating Browser Blackouts: Tactics to Reopen Sites in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-chrome-hurdles-in-w11-effective-steps-herein/"><u>Overcoming Chrome Hurdles in W11 – Effective Steps Herein</u></a></li>
<li><a href="https://win11-tips.techidaily.com/precision-power-management-lowering-user-mode-service-usage-in-windows/"><u>Precision Power Management: Lowering User-Mode Service Usage in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-sync-error-resolution-in-ms-to-do-app/"><u>Streamlining Sync Error Resolution in MS To-Do App</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/top-5-professional-grade-art-tablets-for-designers-2024-selection/"><u>Top 5 Professional-Grade Art Tablets for Designers - 2024 Selection</u></a></li>
<li><a href="https://buynow-info.techidaily.com/1722489198434-unbeatable-prime-day-offers-hunt-the-best-apple-bargains/"><u>Unbeatable Prime Day Offers: Hunt the Best Apple Bargains!</u></a></li>
</ul></div>

