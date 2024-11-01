---
title: Disable Windows Automatic Update Warnings
date: 2024-10-26T16:20:23.170Z
updated: 2024-11-01T16:25:03.267Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disable Windows Automatic Update Warnings
excerpt: This Article Describes Disable Windows Automatic Update Warnings
keywords: Stop Auto Updates,No More Prompts,Silence OS Updates,Turn Off Update Alerts,Halt Windows Update Warnings,Avoid Update Notifications,Deactivate Updates Warning,No Windows Alerts,Stop OS Updates
thumbnail: https://thmb.techidaily.com/922f3c41ec2a1fbc3c661b8fc51d0028e0ed70c9ac6f093a3392525ae0eba424.jpg
---

## Disable Windows Automatic Update Warnings

 When an update is ready for installation, Windows notifies you and prompts you to restart your computer. As helpful as these reminders are, they can also be distracting at times. Fortunately, it’s possible to disable update notifications on Windows.

 You can disable Windows update notifications using the Settings app, Group Policy Editor, or Registry Editor. Let's go over each of these methods one by one.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Disable Windows Update Notifications via the Settings App

 The quickest way to disable update notifications on Windows is through the Settings app. Here are the steps for the same.

1. Press**Win + I** to open Windows Settings. You can also use any method we cover in[how to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Update & Security > Windows Update** .
3. Select**Advanced options** .
4. Disable the toggle for**Notify me when a restart is required to finish updating** .
5. Disable the toggle for**Get me up to date** so that Windows does not display a restart warning when an update is ready for installation.  
![Disable Windows Update Notifications Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-settings-app.jpg)

 Once you complete the above steps, Windows should not bother you with update notifications.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135402/19272" target="_top" id="2135402">
  <img src="//a.impactradius-go.com/display-ad/19272-2135402" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135402/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://25home.pxf.io/c/5597632/2148633/16836" target="_top" id="2148633">
  <img src="//a.impactradius-go.com/display-ad/16836-2148633" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148633/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to re-enable the Windows update notifications later, follow the same steps above and set the**Display options for update notifications** policy to**Not configured** .

<!-- affiliate ads begin -->
<span id="1993645">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993645.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993645">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993645.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993645%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993645/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://review-au.sjv.io/c/5597632/2098701/14409" target="_top" id="2098701">
  <img src="//a.impactradius-go.com/display-ad/14409-2098701" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098701/14409" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://some-guidance.techidaily.com/new-the-essentials-of-dynamic-visual-communication/"><u>[New] The Essentials of Dynamic Visual Communication</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-the-ultimate-guide-to-fb-messenger-call-archiving-for-2024/"><u>[New] The Ultimate Guide to FB Messenger Call Archiving for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-insight-efficiently-identify-hdd-vs-ssd-type-on-windows/"><u>Expert Insight: Efficiently Identify HDD vs SSD Type on Windows</u></a></li>
<li><a href="https://tech-haven.techidaily.com/global-warming-or-just-hot-summers-climate-clarity/"><u>Global Warming or Just Hot Summers? Climate Clarity</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-how-to-make-youtube-thumbnails-online-and-offline/"><u>In 2024, How to Make YouTube Thumbnails Online & Offline</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-hurdles-restoring-access-to-notepad/"><u>Navigating Through Windows' Hurdles: Restoring Access to Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-warnings-about-unverified-application-in-windows-os/"><u>Overcoming Warnings About Unverified Application in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overhauling-your-windows-11-control-panel/"><u>Overhauling Your Windows 11 Control Panel</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/overview-of-the-best-samsung-galaxy-s24plus-screen-mirroring-app-drfone-by-drfone-android/"><u>Overview of the Best Samsung Galaxy S24+ Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-error-code-0xc1900101-in-windows-11-update/"><u>Remedying Error Code 0XC1900101 in Windows 11 Update</u></a></li>
<li><a href="https://android-frp.techidaily.com/step-by-step-tutorial-how-to-bypass-samsung-galaxy-f04-frp-by-drfone-android/"><u>Step-by-Step Tutorial How To Bypass Samsung Galaxy F04 FRP</u></a></li>
<li><a href="https://blog-min.techidaily.com/top-12-playeres-mais-populares-de-dvd-livre-para-sistemas-com-windows-10-ou-11-winxdvd/"><u>Top 12 Playeres Mais Populares De DVD Livre Para Sistemas Com Windows 10 Ou 11 - WinXDVD</u></a></li>
<li><a href="https://windows11.techidaily.com/transformative-strategies-to-supercharge-windows-11/"><u>Transformative Strategies to Supercharge Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-arm-installation-iso-file-journey/"><u>Windows 11 ARM Installation: ISO File Journey</u></a></li>
</ul></div>

