---
title: Reinstating Functional Lock Screen Wait Period in Windows
date: 2024-09-15T17:34:15.067Z
updated: 2024-09-16T17:17:27.524Z
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

## 2\. Configure Screen Saver Settings

 Incorrectly configured screen saver settings on Windows can also be the cause of this issue. Here's how you can configure Windows to display the lock screen after you resume from a screensaver.

1. Press **Win + S** to open the search menu.
2. Type **change screen saver** in the box and select the first result that appears.
3. In the Screen Saver Settings window, set the preferred wait time.
4. Tick the **On resume, display logon screen** checkbox.
5. Hit **Apply** followed by **OK**.  
![Screen Saver Settings on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/screen-saver-settings-on-windows.jpg)

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

 Restart your PC after applying the above changes and check if the issue is still there.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115937/19272" target="_top" id="2115937">
  <img src="//a.impactradius-go.com/display-ad/19272-2115937" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115937/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Other Generic Fixes to Try

 If the above solutions do not work, you can try some generic Windows fixes to get the lock screen timeout working on Windows.

* **Disconnect External Devices:** It is possible that an external device connected to your system is keeping Windows awake. To test this, disconnect all external devices and see if the problem persists.
* **Reset Your Power Plan:** Issues with the power plan settings could also cause such problems. To fix this, you can try [resetting the power plan to default on Windows](https://www.makeuseof.com/reset-power-plans-to-default-in-windows/).
* **Install Windows Updates:** It's possible that the lock screen timeout problem is occurring due to a bug within the Windows build your PC is running. If that's the case, [installing Windows updates](https://www.makeuseof.com/update-windows-manually/) should help.
* **Try a Clean Boot:**[Performing a clean boot on Windows](https://www.makeuseof.com/how-perform-clean-boot-windows-10/) can help you determine whether a third-party program or service is causing issues with the lock screen timeout. Once you find the problematic program, consider removing it from your system to avoid such issues in the future.
* **Perform a System Restore:** If the issue has only started occurring recently, you can [perform a system restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) to undo recent changes and fix the problem.

<!-- affiliate ads begin -->
<span id="1976998">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1976998.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1976998">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1976998.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1976998%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1976998/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-tips.techidaily.com/new-cinematic-continuity-a-kinemaster-led-guide/"><u>[New] Cinematic Continuity A Kinemaster-Led Guide</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-2024-video-size-adjustments-imovies-mysterious-trimming/"><u>[New] In 2024, Video Size Adjustments IMovie's Mysterious Trimming</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-how-to-upload-tiktok-videos-to-twitter-for-2024/"><u>[Updated] How to Upload TikTok Videos to Twitter for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-crafting-engaging-bio-stories-a-guide-to-stand-out-on-fb/"><u>[Updated] In 2024, Crafting Engaging Bio Stories – A Guide to Stand Out on FB</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/4kmp4-hd/"><u>最新技術により、迅速4K動画をMP4 HDフォーマットにアップコンバートする方法</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-check-distance-and-radius-on-google-maps-for-your-samsung-galaxy-a15-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Check Distance and Radius on Google Maps For your Samsung Galaxy A15 5G | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/in-2024-youtube-masterclass-advanced-techniques-for-video-commentary-embedding/"><u>In 2024, YouTube Masterclass Advanced Techniques for Video Commentary Embedding</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-obstacles-during-utorrent-setup-on-windows-systems/"><u>Overcoming Obstacles During uTorrent Setup on Windows Systems</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/professional-video-review-complete-guide-on-bitraser-enterprise-level-data-wipe-tool/"><u>Professional Video Review: Complete Guide on BitRaser Enterprise-Level Data Wipe Tool</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/spotlight-on-stories-crafting-three-effective-highlights/"><u>Spotlight on Stories Crafting Three Effective Highlights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-teamup-error-80080300-in-windows-11/"><u>Troubleshooting TeamUp Error 80080300 in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-the-mechanism-of-windows-11s-autobackup-feature/"><u>Understanding the Mechanism of Windows 11'S AutoBackup Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-data-potential-four-ways-to-tap-into-disk-editor-settings-on-windows-11/"><u>Unlock Data Potential: Four Ways to Tap Into Disk Editor Settings on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-file-path-for-stored-screenshots/"><u>Windows File Path for Stored Screenshots</u></a></li>
</ul></div>

