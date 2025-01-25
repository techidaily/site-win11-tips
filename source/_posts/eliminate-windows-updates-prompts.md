---
title: Eliminate Windows Updates Prompts
date: 2025-01-23T23:28:15.158Z
updated: 2025-01-24T18:49:52.134Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/H2cXnI9oOvM?si=3nz2sBB124ln-83T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/LI9nKlbhnw8?si=uUXFVbuEqXtFHHv0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the above steps, Windows should not bother you with update notifications.

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to re-enable the Windows update notifications later, follow the same steps above and set the**Display options for update notifications** policy to**Not configured** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5EKBEujWCw4?si=PwVvvervi8OrYaEA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/kiW7sLvL65k?si=IHSeRFsYCrfqpn2o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://some-approaches.techidaily.com/updated-the-fundamentals-of-human-interface-recognition/"><u>[Updated] The Fundamentals of Human Interface Recognition</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-integrated-video-workflows-on-ios/"><u>2024 Approved Integrated Video Workflows on iOS</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-mastering-podcast-beginnings-eye-catching-strategies/"><u>2024 Approved Mastering Podcast Beginnings Eye-Catching Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/defending-your-digital-domain-with-top-7-crypto-programs-for-windows-153-chars/"><u>Defending Your Digital Domain with Top 7 Crypto Programs for Windows (153 Chars)</u></a></li>
<li><a href="https://network-issues.techidaily.com/direct-troubleshooting-route-no-current-gfx-wnvidia/"><u>Direct Troubleshooting Route: No Current GFX W/NVIDIA</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fasten-your-gear-3-key-methods-to-hone-mouse-closings/"><u>Fasten Your Gear: 3 Key Methods to Hone Mouse Closings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-the-preferred-platform-for-direct-device-interaction-google-or-windows/"><u>Identifying the Preferred Platform for Direct Device Interaction: Google or Windows?</u></a></li>
<li><a href="https://article-posts.techidaily.com/in-2024-best-no-cost-cross-platform-laptop-dvd-decoders/"><u>In 2024, Best No-Cost, Cross-Platform Laptop DVD Decoders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/journey-through-win11-settings-mouse-mastery-essentials/"><u>Journey Through Win11 Settings: Mouse Mastery Essentials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/method-for-handling-error-code-0x800704b3-in-windows/"><u>Method for Handling Error Code: 0X800704B3 in Windows</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/optimal-filming-equipment-advice-on-choosing-the-best-lenses-for-2024/"><u>Optimal Filming Equipment Advice on Choosing the Best Lenses for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-process-to-refresh-webcam-software-in-windows-10/"><u>Step-by-Step Process to Refresh Webcam Software in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-pc-efficiency-inspecting-cpu-gpu-and-memory-load/"><u>Understanding PC Efficiency: Inspecting CPU, GPU, and Memory Load</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/unlocking-languages-with-movies-and-television-insights/"><u>Unlocking Languages with Movies & Television Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-webcam-functionality-after-0xa00f4289-error/"><u>Unlocking Webcam Functionality After 0xA00F4289 Error</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/unlocking-wireless-potential-an-in-depth-look-at-the-tp-link-re505x-range-extender/"><u>Unlocking Wireless Potential: An In-Depth Look at the TP-Link RE505X Range Extender</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unpacking-internet-accessibility-after-os-setup/"><u>Unpacking Internet Accessibility After OS Setup</u></a></li>
</ul></div>

