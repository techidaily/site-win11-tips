---
title: "Mastering Privacy: Remove Login Email in Windows"
date: 2025-01-06T17:10:10.368Z
updated: 2025-01-12T22:33:26.150Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Privacy: Remove Login Email in Windows"
excerpt: "This Article Describes Mastering Privacy: Remove Login Email in Windows"
keywords: Removing Windows Login,Email Omission WinXP,Enhancing PC Privacy,Secure Computing XP,Opt Out Window Mail,Privacy Settings Windows,Stealthy User Access
thumbnail: https://thmb.techidaily.com/3de06be99a3225bd572539cfd46d39535123115f6244e3ee7a3676c38fda1900.jpg
---

## Mastering Privacy: Remove Login Email in Windows

 If you frequently use your computer in public places, it's a good idea to remove your email address from the Windows login screen. This means people can't get your email address if they see your screen over your shoulder.

 You can accomplish this using the Settings app, Group Policy Editor, or Registry Editor. In this post, we've covered all these methods in detail.

## 1\. How to Hide Email Address From Windows Login Screen Using the Settings App

 The Windows Settings app provides a quick way to hide account information from the login screen. So, if you are in a rush, use the following steps to remove user email addresses from the Windows login screen.

1. Press**Win + I** or use one of the[many ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Accounts > Sign-in options** .
3. Under**Additional settings** , toggle off the switch next to **Show account details such as my email address on the sign-in screen** .  
![Hide Email From Windows Login Screen Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nWu29cqFjZA?si=TNZyCbPq68PQ0JIb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XA_wP7rS9ww?si=LarMG3sEHAhSoL6q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

8. Select**Enabled** in the properties window.
9. Click**Apply** followed by**OK** to save changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kx-Pb0otJCs?si=Mvr49yQVesmJA8-O" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/zXUt81WsQpI?si=W3DKIAsa2-qbGadJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Exit the Registry Editor and restart your PC for the changes to take effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-video-capture.techidaily.com/new-optimal-listeners-for-university-talks/"><u>[New] Optimal Listeners for University Talks</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-unseen-video-on-sony-a6400-whats-going-wrong/"><u>[Updated] 2024 Approved Unseen Video on Sony A6400 What's Going Wrong?</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/rial-elegance-at-the-end/"><u>Editorial Elegance at the End</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-erase-personal-info-from-sign-in-window/"><u>Guide to Erase Personal Info From Sign-In Window</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-restoring-a-dysfunctional-downloads-hub-in-windows/"><u>Guidelines for Restoring a Dysfunctional Downloads Hub in Windows</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-best-ways-to-bypass-icloud-activation-lock-on-iphone-12-pro-maxipadipod-by-drfone-ios/"><u>In 2024, Best Ways to Bypass iCloud Activation Lock on iPhone 12 Pro Max/iPad/iPod</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/in-depth-analysis-and-review-the-shark-ion-robovac-av751-exceptional-cleaning-performance-with-navigation-challenges-tech-insights/"><u>In-Depth Analysis and Review: The Shark iON RoboVac AV751 - Exceptional Cleaning Performance with Navigation Challenges | Tech Insights</u></a></li>
<li><a href="https://technical-tips.techidaily.com/kostenloze-avi-in-webm-omzetten-online-gratis-converter-met-movavi/"><u>Kostenloze AVI-in-WEBM Omzetten Online - Gratis Converter Met Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719298672852-leveraging-local-links-to-global-drives-dropbox-and-googledrive-via-c/"><u>Leveraging Local Links to Global Drives: Dropbox & GoogleDrive via C:</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapid-rendition-accelerating-prints-on-windows-system/"><u>Rapid Rendition: Accelerating Prints on Windows System</u></a></li>
<li><a href="https://hardware-help.techidaily.com/site-selection-involves-evaluating-factors-like-size-shape-topography-accessibility-and-proximity-to-amenities/"><u>Site Selection Involves Evaluating Factors Like Size, Shape, Topography, Accessibility, and Proximity to Amenities.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-slow-windows-10-closure-while-tasks-remain-open/"><u>Strategies for Slow Windows 10 Closure While Tasks Remain Open</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ming-excellence-selecting-the-best-webcams-for-youtube/"><u>Streaming Excellence Selecting the Best Webcams for YouTube</u></a></li>
<li><a href="https://win-blog.techidaily.com/unlock-the-solution-overcome-assassins-creed-odyssey-stalling-issues-on-your-pc-2024-edition/"><u>Unlock the Solution: Overcome 'Assassin's Creed Odyssey' Stalling Issues on Your PC, 2024 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-more-than-one-antivirus-isnt-ideal-for-windows-users/"><u>Why More Than One Antivirus Isn't Ideal for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-woes-8-strategies-for-neutralizing-pink-displays/"><u>Windows Woes: 8 Strategies for Neutralizing Pink Displays</u></a></li>
</ul></div>

