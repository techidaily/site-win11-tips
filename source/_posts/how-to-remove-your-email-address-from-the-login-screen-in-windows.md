---
title: How to Remove Your Email Address From the Login Screen in Windows
date: 2024-09-18T04:34:34.381Z
updated: 2024-09-22T05:12:41.905Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Remove Your Email Address From the Login Screen in Windows
excerpt: This Article Describes How to Remove Your Email Address From the Login Screen in Windows
keywords: Removing Email Login Windows,Logout Email Field Clearance,Erase Usermail Windows Sign-In,Unlink Email From Windows Login,Disconnect Email From PC Access,Delete Email From Windows Login Screen,Exclude Email on Windows Log In
thumbnail: https://thmb.techidaily.com/23f13f96d936d78089a7e8a3b93e560ac0ab8587601498f32a131493f3f787f8.jpg
---

## How to Remove Your Email Address From the Login Screen in Windows

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
<a href="https://aligracehair.sjv.io/c/5597632/2135372/19272" target="_top" id="2135372">
  <img src="//a.impactradius-go.com/display-ad/19272-2135372" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135372/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-helps.techidaily.com/new-2024-approved-speedy-conversion-techniques-for-your-srt-to-txt-tasks/"><u>[New] 2024 Approved Speedy Conversion Techniques for Your SRT to TXT Tasks</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-premier-mobile-platforms-for-enhanced-dji-cinematography/"><u>[New] Premier Mobile Platforms for Enhanced DJi Cinematography</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-time-is-money-the-best-facebook-schedulers-reviewed/"><u>[Updated] 2024 Approved Time Is Money The Best Facebook Schedulers Reviewed</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-efficient-mov-editing-and-recording-tutorial-for-windows-11-users-for-2024/"><u>[Updated] Efficient MOV Editing and Recording Tutorial for Windows 11 Users for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/4-easy-ways-for-your-infinix-smart-8-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>4 Easy Ways for Your Infinix Smart 8 Hard Reset | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mkv-ts-movavi/"><u>網路上自由下載 MKV 版的 TS文件 - 使用 Movavi 解析器</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analisi-completa-di-apowersoft-screen-recorder-dettagli-sul-funzionamento-costi-e-piu-informazioni/"><u>Analisi Completa Di Apowersoft Screen Recorder - Dettagli Sul Funzionamento, Costi E Più Informazioni</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conversione-libera-tra-bmp-e-gif-il-perfetto-solutore-on-line-di-movavi/"><u>Conversione Libera Tra BMP E GIF: Il Perfetto Solutore On-Line Di Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-converter-transform-webp-images-into-jpeg-format-with-ease/"><u>Free Online Converter: Transform WebP Images Into JPEG Format with Ease</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-reset-a-oneplus-ace-3-phone-that-is-locked-by-drfone-android/"><u>How to Reset a OnePlus Ace 3 Phone that is Locked?</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-mastering-lock-screen-settings-how-to-enable-and-disable-on-poco-m6-pro-4g-by-drfone-android/"><u>In 2024, Mastering Lock Screen Settings How to Enable and Disable on Poco M6 Pro 4G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/kostenloze-omzetting-van-rmvb-naar-wmv-online-efficient-met-movavi/"><u>Kostenloze Omzetting Van RMVB Naar WMV Online - Efficiënt Met Movavi</u></a></li>
<li><a href="https://buynow-info.techidaily.com/panasonics-multifunctional-camera-the-fz80-analysis/"><u>Panasonic's Multifunctional Camera: The FZ80 Analysis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trasforma-video-aac-a-mp4-senza-costi-usando-il-servizio-di-conversione-online-movavi/"><u>Trasforma Video AAC a MP4 Senza Costi Usando Il Servizio Di Conversione Online Movavi</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/weatherproof-excellence-in-viewing-discover-the-sunbritetv-55-inch-veranda-4k-hdr-tv/"><u>Weatherproof Excellence in Viewing - Discover the SunBriteTV 55-Inch Veranda 4K HDR TV</u></a></li>
</ul></div>

