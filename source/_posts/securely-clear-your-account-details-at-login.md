---
title: Securely Clear Your Account Details at Login
date: 2024-12-09T22:48:09.971Z
updated: 2024-12-12T22:21:10.972Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Securely Clear Your Account Details at Login
excerpt: This Article Describes Securely Clear Your Account Details at Login
keywords: Secure Logout,Privacy Protection,Safe Sign-Out,Password Safety,User Security,Clean Credentials,Account Shredding
thumbnail: https://thmb.techidaily.com/7a3bff4e2eede5438bb2fccedcb9095f7ad51baa5a8f2d8fdc6330db34850673.jpg
---

## Securely Clear Your Account Details at Login

 If you frequently use your computer in public places, it's a good idea to remove your email address from the Windows login screen. This means people can't get your email address if they see your screen over your shoulder.

 You can accomplish this using the Settings app, Group Policy Editor, or Registry Editor. In this post, we've covered all these methods in detail.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/omWG4u39lmE?si=yk1AEo_gzDpGjYbl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Hide Email Address From Windows Login Screen Using the Settings App

 The Windows Settings app provides a quick way to hide account information from the login screen. So, if you are in a rush, use the following steps to remove user email addresses from the Windows login screen.

1. Press**Win + I** or use one of the[many ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Accounts > Sign-in options** .
3. Under**Additional settings** , toggle off the switch next to **Show account details such as my email address on the sign-in screen** .  
![Hide Email From Windows Login Screen Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FATJWpNYmio?si=72ugPTb3vJXz6cAM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MmTJlcwgyrQ?si=x3hba82M0tT57fj7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6KXVWj6Ar1M?si=Cd_jktmoN3e9OzH3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Exit the Registry Editor and restart your PC for the changes to take effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-sure.techidaily.com/024-approved-jake-paul-unveiled-charting-the-path-of-youtube-stardom/"><u>[New] 2024 Approved Jake Paul Unveiled Charting the Path of YouTube Stardom</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-star-studded-stories-the-ultimate-guide-to-3-instagram-highlights/"><u>[New] 2024 Approved Star-Studded Stories The Ultimate Guide to 3 Instagram Highlights</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-android-brightening-essentials-stepwise-demystification/"><u>[New] Android Brightening Essentials - Stepwise Demystification</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-cutting-edge-tv-selection-top-10-in-hdtvs-for-2024/"><u>[New] Cutting-Edge TV Selection – Top 10 in HDTVs for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/treaming-success-story-which-video-site-tops-others-vimeo-youtube-in-2024/"><u>[New] Streaming Success Story Which Video Site Tops Others – Vimeo, YouTube, In 2024</u></a></li>
<li><a href="https://win-data.techidaily.com/5rc45lmf5yiq6zmk5pah5lu26yen5paw55m854plusplus5rov5ymhic0g5lia6acb5oiq5pys5ywn6lk75oyh5y2x/"><u>永久刪除文件重新發現法則 - 一頁成本免費指南</u></a></li>
<li><a href="https://win11-tips.techidaily.com/common-mistakes-to-avoid-when-using-file-explorer-in-windows-11/"><u>Common Mistakes to Avoid When Using File Explorer in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-win-11s-audio-capturing-skills/"><u>Elevate Win 11'S Audio Capturing Skills</u></a></li>
<li><a href="https://games-able.techidaily.com/experience-unprecedented-gaming-performance-with-pdw4/"><u>Experience Unprecedented Gaming Performance with PDW4</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/how-to-keep-up-the-snapstreak-game/"><u>How To Keep Up the Snapstreak Game</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-analysis-how-to-garner-windows-11s-sid-data/"><u>In-Depth Analysis: How to Garner Windows 11'S SID Data</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-time-lapse-mastery-a-step-by-step-guide-to-final-cut-pro/"><u>New In 2024, Time Lapse Mastery A Step-by-Step Guide to Final Cut Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-flickering-mouse-in-windows-oss/"><u>Remedying Flickering Mouse in Windows OSs</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/rethinking-recipes-squared-up-tutorials-for-youtube-and-facebook-success/"><u>Rethinking Recipes Squared-Up Tutorials for YouTube and Facebook Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/smooth-sailing-after-fixing-upgrade-issue-0x80246007-in-windows-11/"><u>Smooth Sailing After Fixing Upgrade Issue 0X80246007 in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-desktop-view-with-spotlight-based-wallpapers/"><u>Transform Your Desktop View with Spotlight-Based Wallpapers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unhindered-save-functionality-quick-fix-strategies-win11/"><u>Unhindered Save Functionality: Quick Fix Strategies WIN11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-app-speed-boost-5-efficient-methods/"><u>Win 11 App Speed Boost: 5 Efficient Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winpcs-leading-file-sharing-software-compared/"><u>WinPC's Leading File Sharing Software Compared</u></a></li>
</ul></div>

