---
title: Stable Date & Time Control in Windows
date: 2024-10-16T04:25:34.636Z
updated: 2024-10-20T18:32:48.082Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stable Date & Time Control in Windows
excerpt: This Article Describes Stable Date & Time Control in Windows
keywords: Window Time Stability,DateTime Control Windows,Stable Windows Schedule,Unified Time Control Win,Sync Windows Clocks,Time Alignment Win OS,Consistent Timing Window
thumbnail: https://thmb.techidaily.com/f78d1d150df9704e5a6635f2d8f1d9b65ffaf1875700edcd569333cc9eed6a06.jpg
---

## Stable Date & Time Control in Windows

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151870/7443" target="_top" id="2151870">
  <img src="//a.impactradius-go.com/display-ad/7443-2151870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151870/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Then click **Apply** \> **OK** to save the changes.

 This will block anyone from changing the date and time settings on your computer. However, if you have administrative access to the computer, you can still alter the settings.

 If you want to revert to the default settings later, open Group Policy Editor again and change the value of Disallow user override of locale settings back to Not Configured or Disabled. This way, users can change the time and date again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118325/7443" target="_top" id="2118325">
  <img src="//a.impactradius-go.com/display-ad/7443-2118325" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118325/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137203/26400" target="_top" id="2137203">
  <img src="//a.impactradius-go.com/display-ad/26400-2137203" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137203/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you’ve made the changes, close the Registry Editor window and restart your computer.

 To undo this restriction, delete the **PreventUserOverrides** DWORD value from the registry or change the value to **0**. Doing so will enable users to change the time and date again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094482/7443" target="_top" id="2094482">
  <img src="//a.impactradius-go.com/display-ad/7443-2094482" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094482/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-posts.techidaily.com/new-in-2024-the-art-of-auditory-branding-logo-insights-for-podcasters/"><u>[New] In 2024, The Art of Auditory Branding Logo Insights for Podcasters</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-top-strategies-to-shoot-a-flawless-green-screen-scene/"><u>[New] Top Strategies to Shoot a Flawless Green Screen Scene</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/wist-your-way-through-youtube-mastering-rotation-techniques/"><u>[New] Twist Your Way Through YouTube Mastering Rotation Techniques</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-powerful-strategies-for-optimizing-gratuitous-timer-use/"><u>[Updated] Powerful Strategies for Optimizing Gratuitous Timer Use</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-insights-into-whatsapp-sound-calls/"><u>2024 Approved Insights Into WhatsApp Sound Calls</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/adding-a-cinematic-touch-ken-burns-in-camtasa-9-for-2024/"><u>Adding a Cinematic Touch Ken Burns in Camtasa 9 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/commanding-control-over-systems-performance-bounds/"><u>Commanding Control over System's Performance Bounds</u></a></li>
<li><a href="https://win-studio.techidaily.com/download-alternative-mac-software-the-ultimate-guide-to-using-atube-catcher-on-mac-and-windows/"><u>Download Alternative Mac Software: The Ultimate Guide to Using aTube Catcher on Mac & Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-methods-to-test-active-tcp-ports-on-windows/"><u>Efficient Methods to Test Active TCP Ports on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-workflow-add-software-menus-to-windows-desktop/"><u>Enhance Workflow: Add Software Menus to Windows Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-to-resolve-rd-connectivity-issues-on-win-10plus/"><u>Expert Tips to Resolve RD Connectivity Issues on WIN 10+</u></a></li>
<li><a href="https://extra-information.techidaily.com/ignite-drive-with-these-20-high-impact-tunes-for-exercise-enthusiasts/"><u>Ignite Drive with These 20 High-Impact Tunes for Exercise Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-integrating-dolby-atmos-audio/"><u>Mastering Windows 11: Integrating Dolby Atmos Audio</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/maximizing-views-optimal-youtube-thumbnails/"><u>Maximizing Views Optimal YouTube Thumbnails</u></a></li>
<li><a href="https://win11-tips.techidaily.com/precision-time-management-chrome-and-windows-harmony/"><u>Precision Time Management: Chrome and Windows Harmony</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-irregularities-in-desktop-menu-settings/"><u>Rectifying Irregularities in Desktop Menu Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-resolving-missing-gpeditmsc-error-on-pcs/"><u>Solutions for Resolving Missing Gpedit.msc Error on PCs</u></a></li>
</ul></div>

