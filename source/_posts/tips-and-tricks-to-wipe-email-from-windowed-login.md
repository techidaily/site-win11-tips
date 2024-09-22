---
title: Tips & Tricks to Wipe Email From Windowed Login
date: 2024-09-20T17:15:54.768Z
updated: 2024-09-21T18:47:47.117Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tips & Tricks to Wipe Email From Windowed Login
excerpt: This Article Describes Tips & Tricks to Wipe Email From Windowed Login
keywords: Email Erase Tip,Login Privacy Clear,Wipe Login Windows,Secure Email Delete,Safe Login Cleanup,Remove Login Data,Email Window Hide
thumbnail: https://thmb.techidaily.com/d0c9b7047797b18daa1e1aa41be92c363eb13ba8f8bfa2b570a90a8bfa430bd1.jpg
---

## Tips & Tricks to Wipe Email From Windowed Login

 If you frequently use your computer in public places, it's a good idea to remove your email address from the Windows login screen. This means people can't get your email address if they see your screen over your shoulder.

 You can accomplish this using the Settings app, Group Policy Editor, or Registry Editor. In this post, we've covered all these methods in detail.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Hide Email Address From Windows Login Screen Using the Settings App

 The Windows Settings app provides a quick way to hide account information from the login screen. So, if you are in a rush, use the following steps to remove user email addresses from the Windows login screen.

1. Press**Win + I** or use one of the[many ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Accounts > Sign-in options** .
3. Under**Additional settings** , toggle off the switch next to **Show account details such as my email address on the sign-in screen** .  
![Hide Email From Windows Login Screen Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-settings-app.jpg)

## 2\. How to Hide Email Address From Windows Login Screen Using the Group Policy Editor

 The Group Policy Editor (or gpedit.msc) is a handy Windows tool for configuring advanced system settings. You can also this tool to hide your email address from the Windows login screen.

 Note that the Group Policy Editor is only available on Windows Professional, Education, and Enterprise editions. If your PC is running Windows Home, check out[how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

1. Press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the search box and select the first result that appears.
3. Use the left pane to navigate to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options** .
4. Double-click the **Interactive Logon: Display user information when the session is locked** policy on your right.
5. In the properties window, click the drop-down menu to select the**Do not display user information** option.
6. Click**Apply** followed by**OK** .  
![Hide Email From Windows Login Screen Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-group-policy-editor.jpg)
7. Next, double-click on the**Interactive logon: Do not display last user name** policy from the same section.
8. Select**Enabled** in the properties window.
9. Click**Apply** followed by**OK** to save changes.

## 3\. How to Hide Email Address From Windows Login Screen Using the Registry Editor

 If the above two methods don’t work for some reason, you can make changes to the Windows registry files to hide your email address from the login screen. For that, you’ll need to use the Registry Editor on Windows.

 When it comes to editing Registry files, it's important to be cautious as making incorrect changes can cause irreversible damage to your PC. We recommend you either back up all the registry files or create a restore point before you make any changes. If you need help with that, check our guides on[how to back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and[how to create a restore point in Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

 Once you’re done with that, use the following steps to hide your email address from the Windows login screen via Registry Editor.

1. Press**Win + X** to open the Power User menu and select**Run** from the list.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows > System** .
5. Right-click on the**System** key and select**New > DWORD (32-bit) Value** .
6. Rename the DWORD to**BlockUserFromShowingAccountDetailsOnSignin** .
7. Double-click on the newly created DWORD and enter**1** in the**Value data** field. Then, click**OK** .  
![Hide Email From Windows Login Screen Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-registry-editor.jpg)

 Exit the Registry Editor and restart your PC for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123733/7443" target="_top" id="2123733">
  <img src="//a.impactradius-go.com/display-ad/7443-2123733" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123733/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Hiding Your Email Address From the Windows Login Screen Is Easy

 As we just saw, hiding your personal information from the Windows login screen barely takes a couple of minutes, regardless of the method you employ.

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
<li><a href="https://youtube-data.techidaily.com/-part-blueprint-to-monitor-and-maximize-your-youtube-profits/"><u>[New] 3-Part Blueprint to Monitor and Maximize Your YouTube Profits</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-reveal-the-disenchanted-instagrams-unfollowers/"><u>[Updated] Reveal the Disenchanted Instagram's Unfollowers</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-visual-transcript-generator-for-2024/"><u>[Updated] Visual Transcript Generator for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-unleash-your-creativity-drawing-faces-on-snapchat/"><u>2024 Approved Unleash Your Creativity Drawing Faces on Snapchat</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/best-free-iphone-14-plus-imei-checker-by-drfone-ios/"><u>Best Free iPhone 14 Plus IMEI Checker</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-windows-access-denial-mysteries/"><u>Deciphering Windows Access Denial Mysteries</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-converter-transforming-png-images-into-bmp-format-with-movavi/"><u>Free Online Converter: Transforming PNG Images Into BMP Format with Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guia-para-cambiar-tu-fotografia-de-alta-calidad-dng-a-jpg-gratuito-usando-la-herramienta-en-linea-de-movavi/"><u>Guía Para Cambiar Tu Fotografía De Alta Calidad: DNG a JPG Gratuito Usando La Herramienta en Línea De Movavi</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/how-to-turn-off-google-location-to-stop-tracking-you-on-apple-iphone-15-plus-drfone-by-drfone-virtual-ios/"><u>How to Turn Off Google Location to Stop Tracking You on Apple iPhone 15 Plus | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-mastering-real-time-broadcasting-step-by-step-guide/"><u>In 2024, Mastering Real-Time Broadcasting Step by Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/m4r-a-wav-sin-costo-el-poder-de-la-conversion-online-por-movavi/"><u>M4R a WAV Sin Costo: El Poder De La Conversión Online Por Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavi-flac-mp3/"><u>Movavi의 웹사이트에서 FLAC 파일을 MP3로 가용성 향상: 원격 무료 바이트 정렬과 전환</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quicktime-video-downsizing-made-simple-achieve-smaller-sizes-using-just-4-basic-tricks/"><u>QuickTime Video Downsizing Made Simple: Achieve Smaller Sizes Using Just 4 Basic Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/wmv-online-mjpeg-converter/"><u>WMV 이미지/비디오를 자동화된 바이트 스트림으로 무료로 변환: Online MJPEG Converter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mp4-wmv/"><u>최선의 MP4, WMV 바인딩: 영상 변환에 대한 전문가 권장</u></a></li>
</ul></div>

