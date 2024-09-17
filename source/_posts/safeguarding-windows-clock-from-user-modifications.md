---
title: Safeguarding Windows Clock From User Modifications
date: 2024-09-14T20:29:17.778Z
updated: 2024-09-17T05:30:12.626Z
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136624/26400" target="_top" id="2136624">
  <img src="//a.impactradius-go.com/display-ad/26400-2136624" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136624/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Stop Windows Time and Date Changes

 Now stop unauthorized users from changing the date and time settings on your Windows computer. This keeps your tasks and activities on track. If necessary, you can always undo this restriction.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-helps.techidaily.com/new-2024-approved-design-like-a-pro-free-premiere-plans-templates-2023/"><u>[New] 2024 Approved Design Like a Pro Free Premiere Plans, Templates 2023</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-decoding-the-underlying-messages-in-snapchats-symbolic-language/"><u>[Updated] Decoding the Underlying Messages in Snapchat's Symbolic Language</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-artists-blueprint-10-tips-for-podcast-cover-success/"><u>[Updated] The Artist's Blueprint 10 Tips for Podcast Cover Success</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-the-ultimate-blueprint-for-your-mobile-youtube-businesspersonal-platform/"><u>2024 Approved The Ultimate Blueprint for Your Mobile YouTube Business/Personal Platform</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/big-catch-bigger-views-top-5-aquatic-cameras/"><u>Big Catch, Bigger Views - Top 5 Aquatic Cameras</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combatting-the-msvcr110dll-absence-a-fix-guide/"><u>Combatting the Msvcr110.dll Absence: A Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-your-windows-background-file-location-on-pc/"><u>Discover Your Window's Background File Location on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-fixes-for-severe-javascript-failures-within-discord-win-edition/"><u>Expert Fixes for Severe JavaScript Failures Within Discord WIN Edition</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-ultimate-guide-exploring-master-recorders-features/"><u>In 2024, Ultimate Guide Exploring Master Recorder's Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-stuck-gifs-in-discord-windows-edition/"><u>Mastering the Art of Fixing Stuck GIFs in Discord Windows Edition</u></a></li>
<li><a href="https://technical-tips.techidaily.com/online-broadcast-of-samsung-unveiling-your-step-by-step-watch-tips/"><u>Online Broadcast of Samsung Unveiling: Your Step-by-Step Watch Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sharpen-skills-and-speed-up-valorant-tips-for-top-performance/"><u>Sharpen Skills & Speed Up: Valorant Tips for Top Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-faulty-volume-shadows-in-win/"><u>Troubleshooting Faulty Volume Shadows in Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ultimate-guide-for-higher-frame-rates-in-cs-go/"><u>Ultimate Guide for Higher Frame Rates in CS GO</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/unleash-top-gaming-prowess-the-hp-omen-obelisk-review-a-game-changer-at-a-great-value/"><u>Unleash Top Gaming Prowess: The HP OMEN Obelisk Review – A Game Changer at a Great Value</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    