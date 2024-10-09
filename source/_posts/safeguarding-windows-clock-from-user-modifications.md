---
title: Safeguarding Windows Clock From User Modifications
date: 2024-10-06T20:17:58.357Z
updated: 2024-10-08T16:40:29.118Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Safeguarding Windows Clock From User Modifications
excerpt: This Article Describes Safeguarding Windows Clock From User Modifications
keywords: Protect Windows Time,Prevent Clock Alterations,Secure System Clock,Stop Clock Changes,Maintain Clock Settings,Lock Windows Timestamp,Defend User-Mod Timing
thumbnail: https://thmb.techidaily.com/716b773a3a0bbb4238a628ab28cfde8731d3dd391169cbf818a66e733201ea5d.jpg
---

## Safeguarding Windows Clock From User Modifications

 You’re using your Windows device and notice something strange in the date and time settings. Someone has changed the settings without your knowledge or permission. This makes it difficult to stay on schedule with tasks and activities. In this guide, we’ll show how to stop anonymous users from changing date and time settings on Windows computers.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How To Prevent Users From Changing the Date and Time on Windows

 There are two ways to prevent users from changing Windows date and time. The first is to use Group Policy Editor, a system administration tool designed to control computer behavior in an organization. While the second way is to use Registry Editor, which allows you to modify Windows registry settings.

 For both methods, you need administrative access to the computer to change it. Once you’ve made the changes, nobody can alter the date and time settings. Let’s look at each method in more detail.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135371/19272" target="_top" id="2135371">
  <img src="//a.impactradius-go.com/display-ad/19272-2135371" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135371/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2043597/7443" target="_top" id="2043597">
  <img src="//a.impactradius-go.com/display-ad/7443-2043597" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043597/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Then click **Apply** \> **OK** to save the changes.

 This will block anyone from changing the date and time settings on your computer. However, if you have administrative access to the computer, you can still alter the settings.

 If you want to revert to the default settings later, open Group Policy Editor again and change the value of Disallow user override of locale settings back to Not Configured or Disabled. This way, users can change the time and date again.

<!-- affiliate ads begin -->
<span id="1424533">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424533.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424533">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424533.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424533%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424533/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://appsumo.8odi.net/c/5597632/2037356/7443" target="_top" id="2037356">
  <img src="//a.impactradius-go.com/display-ad/7443-2037356" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037356/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you’ve made the changes, close the Registry Editor window and restart your computer.

 To undo this restriction, delete the **PreventUserOverrides** DWORD value from the registry or change the value to **0**. Doing so will enable users to change the time and date again.

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
<li><a href="https://youtube-data.techidaily.com/nrich-your-knowledge-student-approved-history-youtubes-to-watch/"><u>[New] Enrich Your Knowledge Student-Approved History YouTubes To Watch</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-broadcast-excellence-incorrante-video-loops-into-television-for-2024/"><u>[Updated] Broadcast Excellence Incorrante Video Loops Into Television for 2024</u></a></li>
<li><a href="https://discover-dash.techidaily.com/comprehensive-guide-to-digiarty-software-deciphering-the-winxdvd-licensing-agreement/"><u>Comprehensive Guide to Digiarty Software - Deciphering the WinXDVD Licensing Agreement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decrypting-windows-11s-concealed-theme-settings-via-registry/"><u>Decrypting Windows 11'S Concealed Theme Settings via Registry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-add-to-taskbar-in-w11/"><u>Efficiently Add to Taskbar in W11</u></a></li>
<li><a href="https://fox-blue.techidaily.com/enhancing-detail-in-youtube-clips/"><u>Enhancing Detail in YouTube Clips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-navigation-adding-folders-with-comments-in-windows-11/"><u>Enhancing Navigation: Adding Folders with Comments in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-software-top-5-programs-that-simplify-your-laptop-switch/"><u>Essential Software: Top 5 Programs That Simplify Your Laptop Switch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-wordsmith-tools-win-friendly-selections/"><u>Essential Wordsmith Tools: Win-Friendly Selections</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-gmail-password-on-vivo-y100-devices-by-drfone-android/"><u>How to Reset Gmail Password on Vivo Y100 Devices</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-vivo-s17t-phone-without-password-by-drfone-android/"><u>How To Unlock Vivo S17t Phone Without Password?</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-entrepreneurs-essentials-top-free-business-templates/"><u>In 2024, Entrepreneur's Essentials Top Free Business Templates</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-optimize-visual-design-top-10-must-have-type-plugins-for-ae/"><u>In 2024, Optimize Visual Design Top 10 Must-Have Type Plugins for AE</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-social-media-powerhouses-insight-into-facebook-twitter-instagram-and-youtube/"><u>Navigating the Social Media Powerhouses: Insight Into Facebook, Twitter, Instagram & Youtube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reestablishing-wireless-connection-in-windows/"><u>Reestablishing Wireless Connection in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-dilemma-step-by-step-guide-to-overcoming-glexttexturecompression-level-compression-format-opengl-error-1281/"><u>Resolving the Dilemma: Step-by-Step Guide to Overcoming GL_EXT_texture_compression Level Compression Format OpenGL Error #1281</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-pasting-operation-in-chrome-edge-firefox-os/"><u>Reviving Pasting Operation in Chrome, Edge, Firefox OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-step-by-step-for-windows-11-fast-startup/"><u>The Ultimate Step-by-Step for Windows 11 Fast Startup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-not-just-linux-no-more-windows-subsystem/"><u>Why Not Just Linux? No More Windows Subsystem</u></a></li>
</ul></div>

