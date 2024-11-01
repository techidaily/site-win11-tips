---
title: Solving Stuck Lock Screen Timer in Windows 10/11
date: 2024-10-30T16:14:58.109Z
updated: 2024-11-01T17:07:16.067Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solving Stuck Lock Screen Timer in Windows 10/11
excerpt: This Article Describes Solving Stuck Lock Screen Timer in Windows 10/11
keywords: Fix Stuck Timer on W10/W11 Lock Screen,Stop Lock Timer Freeze in Win 10/11,Resolve Lock Screen Delay W10/W11,Eliminate Frozen Lock Screen Countdown,Clear Locked Screen Timer Issue Windows 10/11,End Stuck Lock Timer on Windows 10/11,Prevent Locked Screen Timer Glitches in Win 10/11
thumbnail: https://thmb.techidaily.com/cd61def31c266f510e96724b2a8477792657278ca4fb179ccb3f421fcf0aa55a.jpg
---

## Solving Stuck Lock Screen Timer in Windows 10/11

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
<a href="https://ursime.pxf.io/c/5597632/2136548/16384" target="_top" id="2136548">
  <img src="//a.impactradius-go.com/display-ad/16384-2136548" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136548/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Configure Screen Saver Settings

 Incorrectly configured screen saver settings on Windows can also be the cause of this issue. Here's how you can configure Windows to display the lock screen after you resume from a screensaver.

1. Press **Win + S** to open the search menu.
2. Type **change screen saver** in the box and select the first result that appears.
3. In the Screen Saver Settings window, set the preferred wait time.
4. Tick the **On resume, display logon screen** checkbox.
5. Hit **Apply** followed by **OK**.  
![Screen Saver Settings on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/screen-saver-settings-on-windows.jpg)

 Once you complete the above steps, Windows should lock your system once the screen saver activates.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997675/19272" target="_top" id="1997675">
  <img src="//a.impactradius-go.com/display-ad/19272-1997675" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997675/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1495277">
					<video width="1536" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1495277.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/17189-1495277">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1495277.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:960px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ffunwhole.sjv.io%2Fc%2F5597632%2F1495277%2F17189'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1495277/17189" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://imp.i357552.net/c/5597632/947746/11832" target="_top" id="947746">
  <img src="//a.impactradius-go.com/display-ad/11832-947746" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/947746/11832" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://tiktok-video-files.techidaily.com/new-in-2024-protecting-your-digital-memories-how-to-save-tiktok-videos/"><u>[New] In 2024, Protecting Your Digital Memories How to Save TikTok Videos</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-best-20-anime-openers-anthems-in-order/"><u>[Updated] 2024 Approved Best 20 Anime Openers' Anthems in Order</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-increase-your-fb-popularity-top-ten-seo-best-practices/"><u>[Updated] 2024 Approved Increase Your FB Popularity Top Ten SEO Best Practices</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-best-practices-for-instagram-video-sharing-for-2024/"><u>[Updated] Best Practices for Instagram Video Sharing for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-idevice-audio-mastery-stepwise-recording-of-voices/"><u>[Updated] In 2024, IDevice Audio Mastery Stepwise Recording of Voices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-ways-to-access-windows-troubleshooting-with-hotkeys/"><u>Efficient Ways to Access Windows Troubleshooting with Hotkeys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-quick-uninstall-of-win11-printers/"><u>Expert Guide: Quick Uninstall of Win11 Printers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-download-and-update-directx-on-your-pc/"><u>How to Download and Update DirectX on Your PC</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-advanced-techniques-for-tiktok-video-enhancement-via-zoom/"><u>In 2024, Advanced Techniques for TikTok Video Enhancement via Zoom</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-does-enter-puk-code-mean-and-why-did-the-sim-get-puk-blocked-on-tecno-pova-5-pro-device-by-drfone-android/"><u>In 2024, What Does Enter PUK Code Mean And Why Did The Sim Get PUK Blocked On Tecno Pova 5 Pro Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/instructions-to-prevent-unwanted-touchpad-input-in-windows-10-with-an-attached-mouse-device/"><u>Instructions to Prevent Unwanted Touchpad Input in Windows 10 with an Attached Mouse Device</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/optimizing-video-sharing-with-vimeo-subscription-choices/"><u>Optimizing Video Sharing With Vimeo Subscription Choices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-easy-way-to-manage-your-stickies-across-devices/"><u>The Easy Way to Manage Your Stickies Across Devices</u></a></li>
</ul></div>

