---
title: Safeguarding Windows Clock From User Modifications
date: 2024-09-16T00:02:13.820Z
updated: 2024-09-22T01:35:41.491Z
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
6. Then click **Apply** \> **OK** to save the changes.

 This will block anyone from changing the date and time settings on your computer. However, if you have administrative access to the computer, you can still alter the settings.

 If you want to revert to the default settings later, open Group Policy Editor again and change the value of Disallow user override of locale settings back to Not Configured or Disabled. This way, users can change the time and date again.

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

 Once you’ve made the changes, close the Registry Editor window and restart your computer.

 To undo this restriction, delete the **PreventUserOverrides** DWORD value from the registry or change the value to **0**. Doing so will enable users to change the time and date again.

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2141676/17091" target="_top" id="2141676">
  <img src="//a.impactradius-go.com/display-ad/17091-2141676" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettieu.pxf.io/i/5597632/2141676/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://extra-guidance.techidaily.com/new-mastering-the-art-of-high-quality-photo-for-free/"><u>[New] Mastering the Art of High Quality Photo for Free</u></a></li>
<li><a href="https://unlock-android.techidaily.com/delete-gmail-account-withwithout-password-on-xiaomi-redmi-a2-by-drfone-android/"><u>Delete Gmail Account With/Without Password On Xiaomi Redmi A2</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/drive-more-traffic-effective-strategies-for-youtube-outros-for-2024/"><u>Drive More Traffic Effective Strategies for YouTube Outros for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-classroom-assets-explore-the-ultimate-guide-of-30-top-rated-teacher-resources-on-movavi-channel/"><u>Essential Classroom Assets: Explore the Ultimate Guide of 30 Top-Rated Teacher Resources on Movavi Channel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gratuit-gif-to-swf-convertisseur-en-ligne-une-utilite-de-movavi/"><u>Gratuit GIF-to-SWF Convertisseur en Ligne: Une Utilité De Movavi</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-realme-c67-5g-location-by-number-drfone-by-drfone-virtual-android/"><u>How to Track Realme C67 5G Location by Number | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-make-the-most-of-your-apple-iphone-7-plus-lock-screen-with-notifications-by-drfone-ios/"><u>In 2024, How to Make the Most of Your Apple iPhone 7 Plus Lock Screen with Notifications?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-why-is-ipogo-not-working-on-oppo-reno-8t-5g-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, Why is iPogo not working On Oppo Reno 8T 5G? Fixed | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mov-to-mxf-conversion-tool-fast-and-secure-file-format-change-online-free-service/"><u>MOV to MXF Conversion Tool - Fast & Secure File Format Change Online, Free Service</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-green-screen-on-a-mac-choosing-the-right-tool-for-the-job/"><u>New In 2024, Green Screen on a Mac Choosing the Right Tool for the Job</u></a></li>
<li><a href="https://techtrends.techidaily.com/resolving-high-cpu-usage-by-dwmexe-in-the-desktop-window-manager-on-windows-10-a-comprehensive-guide/"><u>Resolving High CPU Usage by dwm.exe in the Desktop Window Manager on Windows 10: A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ridimensionamento-gratuito-mp4-a-3g2-con-movavi-conversione-video-facile-e-rapida/"><u>Ridimensionamento Gratuito MP4 a 3G2 Con Movavi - Conversione Video Facile E Rapida</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-10-high-quality-streaming-audio-devices-reviewed-by-movavi/"><u>Top 10 High-Quality Streaming Audio Devices - Reviewed by Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trasforma-i-tuoi-file-swf-in-formato-mp4-libero-e-gratuito-tramite-il-servizio-online-di-movavi/"><u>Trasforma I Tuoi File SWF in Formato MP4 Libero E Gratuito Tramite Il Servizio Online Di Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/wmawmv-movavi/"><u>WMAおよびWMVファイルの自由なオンライン変換 - Movavi</u></a></li>
</ul></div>

