---
title: Overcoming Frozen PC Lock Screen Wait Time Issue
date: 2024-12-01T21:44:24.484Z
updated: 2024-12-07T02:07:04.372Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Frozen PC Lock Screen Wait Time Issue
excerpt: This Article Describes Overcoming Frozen PC Lock Screen Wait Time Issue
keywords: Fix Freeze PC Screen,Unfreeze Lock Screen,Stop PC Wait Time,Quick PC Reset,Resolve Lock Delay,End Frozen Screens,Prevent Lock Lag
thumbnail: https://thmb.techidaily.com/0087bea05b577dbfb71c5ba8ff49de27f95d036e8af8878f0f3b10198632d36b.jpg
---

## Overcoming Frozen PC Lock Screen Wait Time Issue

 Have you ever left your computer unattended for a while, only to return and find that it was still unlocked? Several users have reported problems getting their Windows computers to lock automatically after a certain period of inactivity.

 To help out, we have listed some useful tips that should get the lock screen timeout to work on your Windows 10 or 11 PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9hsPbiic0O8?si=58mZ2Cu6wicQfsUP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Check Screen Timeout Settings

 Before we get to any advanced troubleshooting tips, it’s a good idea to double-check the screen timeout settings on Windows. Here are the steps for the same.

1. Press **Win + I** to open the Settings app.
2. Navigate to **System > Power & battery**.
3. Click on **Screen and sleep** to expand it.
4. Click the drop-down menus next to **On battery power, turn off my screen after** and **When plugged in, turn off my screen after** to select your preferred timeout.  
![Screen and Sleep Settings in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/screen-and-sleep-settings-in-windows.jpg)

 After setting your preferred timeout, observe if Windows locks your PC after the specified period.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLO5dwmJAVs?si=1OYH8rv8aPaMsCiU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Configure Screen Saver Settings

 Incorrectly configured screen saver settings on Windows can also be the cause of this issue. Here's how you can configure Windows to display the lock screen after you resume from a screensaver.

1. Press **Win + S** to open the search menu.
2. Type **change screen saver** in the box and select the first result that appears.
3. In the Screen Saver Settings window, set the preferred wait time.
4. Tick the **On resume, display logon screen** checkbox.
5. Hit **Apply** followed by **OK**.  
![Screen Saver Settings on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/screen-saver-settings-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/e4Nt2xXXtmE?si=CtKwFry4b0AJXnaN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the above steps, Windows should lock your system once the screen saver activates.

## 3\. Check Screen Saver Settings in the Local Group Policy

 If the issue remains even after you configure the screen saver settings, you will need to check the policies related to the screen saver and make sure they are configured correctly.

 As you may be aware, the Local Group Policy Editor is only available on Windows Pro, Enterprise, and Education editions. However, if you are using the Home edition, you can use a workaround to [access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To modify group policies related to screen saver, use these steps:

1. Press **Win + R** to open the Run dialog box.
2. Type **gpedit.msc** in the box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **User Configuration > Administrative Templates > Control Panel > Personalization**.
5. Double-click the **Enable Screen Saver** policy on your right.
6. Select the **Enabled** option.
7. Hit **Apply** and then click **OK**.
8. Similarly, enable the **Password protect the screen saver** policy as well.  
![Password Protect Screen Saver Policy in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/password-protect-screen-saver-policy-in-group-policy-editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SyMZxS9479s?si=0T6zZpyN2LBftFTM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Restart your PC after applying the above changes and check if the issue is still there.

## 4\. Other Generic Fixes to Try

 If the above solutions do not work, you can try some generic Windows fixes to get the lock screen timeout working on Windows.

* **Disconnect External Devices:** It is possible that an external device connected to your system is keeping Windows awake. To test this, disconnect all external devices and see if the problem persists.
* **Reset Your Power Plan:** Issues with the power plan settings could also cause such problems. To fix this, you can try [resetting the power plan to default on Windows](https://www.makeuseof.com/reset-power-plans-to-default-in-windows/).
* **Install Windows Updates:** It's possible that the lock screen timeout problem is occurring due to a bug within the Windows build your PC is running. If that's the case, [installing Windows updates](https://www.makeuseof.com/update-windows-manually/) should help.
* **Try a Clean Boot:**[Performing a clean boot on Windows](https://www.makeuseof.com/how-perform-clean-boot-windows-10/) can help you determine whether a third-party program or service is causing issues with the lock screen timeout. Once you find the problematic program, consider removing it from your system to avoid such issues in the future.
* **Perform a System Restore:** If the issue has only started occurring recently, you can [perform a system restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) to undo recent changes and fix the problem.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KdpTAZ9zonQ?si=5Nd5SPW1axA7GPuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get the Lock Screen Timeout Working Again on Windows

 When the lock screen timeout fails to work as expected, it can potentially put your Windows computer at risk. Hopefully, one or more of the above tips have helped you solve the problem and you are at peace.

 To help out, we have listed some useful tips that should get the lock screen timeout to work on your Windows 10 or 11 PC.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://hardware-tips.techidaily.com/1-dont-purchase-these-4-apple-devices-yet-a-zdnet-insight/"><u>1. Don't Purchase These 4 Apple Devices Yet: A ZDNet Insight</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-inspirational-article-leaderboard-maker/"><u>2024 Approved Inspirational Article Leaderboard Maker</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-sun-salutations-and-beyond-youtubes-premier-yoga-pages/"><u>2024 Approved Sun Salutations & Beyond – YouTube's Premier Yoga Pages</u></a></li>
<li><a href="https://win-web3.techidaily.com/1728503818294-vm/"><u>信頼性高く、持続可能な方法でウェブ上のVMバックアップを行う - 専門家から学ぶ</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/beyond-silence-the-rise-of-quiet-firing-in-modern-workplaces-why-it-has-companies-concerned/"><u>Beyond Silence: The Rise of 'Quiet Firing' In Modern Workplaces - Why It Has Companies Concerned</u></a></li>
<li><a href="https://win11-tips.techidaily.com/directing-wakeable-assets-on-windows-during-rest/"><u>Directing Wakeable Assets on Windows During Rest</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-techniques-merging-both-adjacent-and-non-adjacent-windows-partitions/"><u>Efficient Techniques: Merging Both Adjacent & Non-Adjacent Windows Partitions</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/home-cinematic-wonders-fastest-tips-and-tricks/"><u>Home Cinematic Wonders Fastest Tips & Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-package-could-not-be-registered-photos-error-in-windows-10-and-11/"><u>How to Fix the “Package Could Not Be Registered” Photos Error in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-mend-audio-output-not-found-issue/"><u>How To Mend 'Audio Output Not Found' Issue</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-2-ways-to-monitor-google-pixel-8-activity-drfone-by-drfone-virtual-android/"><u>In 2024, 2 Ways to Monitor Google Pixel 8 Activity | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-your-pen-tablet-not-working-on-windows-heres-how-to-fix-it/"><u>Is Your Pen Tablet Not Working on Windows? Here’s How to Fix It</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/reconstructing-disappeared-chatgpt-exchanges/"><u>Reconstructing Disappeared ChatGPT Exchanges</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/setting-up-a-memorable-social-media-presence-with-covers/"><u>Setting Up a Memorable Social Media Presence with Covers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-task-management-on-win11-with-a-quick-search-bar/"><u>Unlocking Task Management on Win11 with a Quick Search Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-secrets-of-updater-error-0xca00a009/"><u>Unveiling the Secrets of Updater Error #0xCA00A009</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-woes-9-essential-fixes-for-ineffectual-keystrokes-and-keycombinations/"><u>Windows Woes? 9 Essential Fixes for Ineffectual Keystrokes and Keycombinations</u></a></li>
</ul></div>

