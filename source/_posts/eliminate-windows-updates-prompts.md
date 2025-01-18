---
title: Eliminate Windows Updates Prompts
date: 2025-01-12T17:35:48.712Z
updated: 2025-01-18T17:51:17.434Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminate Windows Updates Prompts
excerpt: This Article Describes Eliminate Windows Updates Prompts
keywords: Stop Update Alerts,Avoid Windows Prompt,Block Update Notifications,Remove Update Reminders,Disable WinUpdates,Quiet Update Warnings,Halt Updater Messages
thumbnail: https://thmb.techidaily.com/ebbfde368b81e7f396fe512ace44b149bef6fef394a1d6fd8cfa20e2c4a0b6c3.jpg
---

## Eliminate Windows Updates Prompts

 When an update is ready for installation, Windows notifies you and prompts you to restart your computer. As helpful as these reminders are, they can also be distracting at times. Fortunately, it’s possible to disable update notifications on Windows.

 You can disable Windows update notifications using the Settings app, Group Policy Editor, or Registry Editor. Let's go over each of these methods one by one.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/htnQWyEOCgc?si=fy86hi8_hTtbWAnw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Disable Windows Update Notifications via the Settings App

 The quickest way to disable update notifications on Windows is through the Settings app. Here are the steps for the same.

1. Press**Win + I** to open Windows Settings. You can also use any method we cover in[how to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Update & Security > Windows Update** .
3. Select**Advanced options** .
4. Disable the toggle for**Notify me when a restart is required to finish updating** .
5. Disable the toggle for**Get me up to date** so that Windows does not display a restart warning when an update is ready for installation.  
![Disable Windows Update Notifications Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the above steps, Windows should not bother you with update notifications.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Disable Windows Update Notifications Using Group Policy Editor

 Group Policy Editor is a powerful tool for configuring various settings on your Windows computer. If you have the Enterprise or Professional edition of Windows, you can disable update notifications using the Group Policy Editor. If you don't have either of those versions, read our guide on[how to access Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

To disable Windows update notifications using Group Policy Editor:

1. Press**Win + R** to open the Run dialog box.
2. Type**gpedit.msc** in the box and press**Enter** .
3. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Update > Manage end use experience.**
4. Double-click the**Display options for update notifications** policy on your right.
5. Select the**Disabled** option.
6. Click**Apply** followed by**OK** .  
![Disable Windows Update Notifications Using the Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-group-policy-editor-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15Ju8Cb4UZ8?si=5wdiQXdz1BOxIkDH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to re-enable the Windows update notifications later, follow the same steps above and set the**Display options for update notifications** policy to**Not configured** .

## 3\. Disable Windows Update Notifications With Registry Editor

 If you can’t seem to access the Group Policy Editor for some reason, you can use the Registry Editor to disable update notifications.

 Since Registry Editor is a powerful tool that needs to be handled with care, we recommend that you back up all the registry files or create a restore point before proceeding with the changes below. If you need help, check our guides on[how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and[how to create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

To disable Windows update notifications using Registry Editor:

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the Registry Editor window, use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows** .
5. Locate the**WindowsUpdate** key. If you can’t find it, right-click on the**Windows** key and select**New > Key** . Rename the key as**WindowsUpdate** .
6. Right-click the**WindowsUpdate** key and select**New > DWORD (32-bit) Value** .
7. Rename the DWORD as**SetUpdateNotificationLevel** .
8. Double-click the newly created DWORD and change its**Value data** to**0** .
9. Click**OK** .  
![Disable Windows Update Notifications Using the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-registry-editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/620kcQ7Dw7w?si=a5ussGs5HV7sG3hF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Exit the Registry Editor window and restart your PC to apply the changes. Following that, Windows will not display update notifications on your computer.

## No More Update Notifications on Windows

 Windows updates are critical for the overall stability of your computer. That said, turning off Windows update notifications makes sense if you're not in a rush to install updates as soon as they are ready for installation.

 If you find Windows notifications to be distracting in general, you can use Focus Assist to silence all alerts and stay productive.

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
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-sneak-peek-to-secrecy-how-to-create-hidden-stories/"><u>[New] 2024 Approved Sneak Peek to Secrecy How to Create Hidden Stories</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-convincing-audiences-to-join-a-positive-approach/"><u>[New] Convincing Audiences to Join A Positive Approach</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/n-2024-extract-translate-and-save-youtube-subtitles-for-free/"><u>[New] In 2024, Extract, Translate & Save YouTube Subtitles for FREE</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-say-laughs-say-free-mememakers-tutorial-for-2024/"><u>[New] Say Laughs, Say Free - MemeMaker's Tutorial for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-melodic-instagram-reels-blending-music-voiceovers/"><u>[Updated] In 2024, Melodic Instagram Reels Blending Music, Voiceovers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keep-taskmanager-front-and-center-in-windows/"><u>Keep TaskManager Front and Center in Windows</u></a></li>
<li><a href="https://techtrends.techidaily.com/kostenlose-abspielung-von-dvds-mit-dem-neuen-kostengunstigen-dekoder-ohne-download-notwendigkeit/"><u>Kostenlose Abspielung Von DVDs Mit Dem Neuen, Kostengünstigen Dekoder Ohne Download-Notwendigkeit</u></a></li>
<li><a href="https://win-solutions.techidaily.com/lego-star-wars-pc-game-troubleshooting-for-skywalker-saga-update/"><u>Lego Star Wars PC Game Troubleshooting for Skywalker Saga Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/managing-file-capacity-with-win-1011-tips/"><u>Managing File Capacity with Win 10/11 Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-chatgpt-windows-setup-guide/"><u>Mastering ChatGPT: Windows Setup Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-access-to-off-screen-panes-win11-guide/"><u>Regaining Access to Off-Screen Panes: Win11 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-barriers-steam-and-windows-11-file-privilege-issue/"><u>Removing Barriers: Steam & Windows 11 File Privilege Issue</u></a></li>
<li><a href="https://program-issues.techidaily.com/resolving-cannot-reach-live-config-servers-troubleshooting-guide/"><u>Resolving 'Cannot Reach Live Config Servers': Troubleshooting Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-woes-re-opening-chrome-made-simple/"><u>Windows 11 Woes: Re-Opening Chrome Made Simple</u></a></li>
</ul></div>

