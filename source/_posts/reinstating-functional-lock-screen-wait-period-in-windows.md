---
title: Reinstating Functional Lock Screen Wait Period in Windows
date: 2024-10-26T17:49:36.308Z
updated: 2024-11-01T18:27:16.376Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reinstating Functional Lock Screen Wait Period in Windows
excerpt: This Article Describes Reinstating Functional Lock Screen Wait Period in Windows
keywords: Window Lock Delay,Reinstate Lock Screen,Functional Lock Timer,Screen Wait Redesign,Windows Security Hold,Lock Screen Pause,Windows Timeout Fix
thumbnail: https://thmb.techidaily.com/9fc617880b7f763c252c5a9e983583a15e0501d81b43be135b81d00ad4f84b19.png
---

## Reinstating Functional Lock Screen Wait Period in Windows

 Have you ever left your computer unattended for a while, only to return and find that it was still unlocked? Several users have reported problems getting their Windows computers to lock automatically after a certain period of inactivity.

 To help out, we have listed some useful tips that should get the lock screen timeout to work on your Windows 10 or 11 PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Check Screen Timeout Settings

 Before we get to any advanced troubleshooting tips, it’s a good idea to double-check the screen timeout settings on Windows. Here are the steps for the same.

1. Press **Win + I** to open the Settings app.
2. Navigate to **System > Power & battery**.
3. Click on **Screen and sleep** to expand it.
4. Click the drop-down menus next to **On battery power, turn off my screen after** and **When plugged in, turn off my screen after** to select your preferred timeout.  
![Screen and Sleep Settings in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/screen-and-sleep-settings-in-windows.jpg)

 After setting your preferred timeout, observe if Windows locks your PC after the specified period.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134247/18498" target="_top" id="2134247">
  <img src="//a.impactradius-go.com/display-ad/18498-2134247" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134247/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1934254/19272" target="_top" id="1934254">
  <img src="//a.impactradius-go.com/display-ad/19272-1934254" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934254/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you complete the above steps, Windows should lock your system once the screen saver activates.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037345/7443" target="_top" id="2037345">
  <img src="//a.impactradius-go.com/display-ad/7443-2037345" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037345/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://aligracehair.sjv.io/c/5597632/1880956/19272" target="_top" id="1880956">
  <img src="//a.impactradius-go.com/display-ad/19272-1880956" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880956/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Restart your PC after applying the above changes and check if the issue is still there.

## 4\. Other Generic Fixes to Try

 If the above solutions do not work, you can try some generic Windows fixes to get the lock screen timeout working on Windows.

* **Disconnect External Devices:** It is possible that an external device connected to your system is keeping Windows awake. To test this, disconnect all external devices and see if the problem persists.
* **Reset Your Power Plan:** Issues with the power plan settings could also cause such problems. To fix this, you can try [resetting the power plan to default on Windows](https://www.makeuseof.com/reset-power-plans-to-default-in-windows/).
* **Install Windows Updates:** It's possible that the lock screen timeout problem is occurring due to a bug within the Windows build your PC is running. If that's the case, [installing Windows updates](https://www.makeuseof.com/update-windows-manually/) should help.
* **Try a Clean Boot:**[Performing a clean boot on Windows](https://www.makeuseof.com/how-perform-clean-boot-windows-10/) can help you determine whether a third-party program or service is causing issues with the lock screen timeout. Once you find the problematic program, consider removing it from your system to avoid such issues in the future.
* **Perform a System Restore:** If the issue has only started occurring recently, you can [perform a system restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) to undo recent changes and fix the problem.

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
<li><a href="https://youtube-sure.techidaily.com/econstructing-the-legal-framework-of-youtube-and-cc-licenses/"><u>[New] Deconstructing the Legal Framework of Youtube & CC Licenses</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-prime-top-10-free-transcript-harvesters-for-videos/"><u>[New] In 2024, Prime Top 10 Free Transcript Harvesters for Videos</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-enhancing-film-aesthetics-with-luts-technology-for-2024/"><u>[Updated] Enhancing Film Aesthetics with Luts Technology for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-free-ways-to-save-your-desktop-on-windows-8-for-2024/"><u>[Updated] Free Ways to Save Your Desktop on Windows 8 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-backup-configuration-error-on-windows-systems/"><u>Correcting “Backup Configuration Error” On Windows Systems</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/expert-tips-for-srt-enhanced-mp4-files-for-2024/"><u>Expert Tips for SRT-Enhanced MP4 Files for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fix-gpu-non-detection-problems/"><u>Fix: GPU Non-Detection Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-initiate-clipboard-integration-within-microsofts-app-guard-on-windows-11/"><u>How to Initiate Clipboard Integration Within Microsoft's App Guard on Windows 11</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-advanced-equipment-guide-top-5-innovative-slow-motion-devices/"><u>In 2024, Advanced Equipment Guide Top 5 Innovative Slow Motion Devices</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-make-sense-of-iphone-video-repetition-tech/"><u>In 2024, Make Sense of iPhone Video Repetition Tech</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-ultimate-smartphone-list-for-capturing-crystal-clear-video/"><u>In 2024, Ultimate Smartphone List for Capturing Crystal Clear Video</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-failed-driver-installations-on-windows-11/"><u>Remedying Failed Driver Installations on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-power-management-on-pcs/"><u>The Ultimate Guide to Power Management on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-playbook-for-kali-on-windows-systems/"><u>The Ultimate Playbook for Kali on Windows Systems</u></a></li>
</ul></div>

