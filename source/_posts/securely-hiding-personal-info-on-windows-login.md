---
title: Securely Hiding Personal Info on Windows Login
date: 2024-12-25T22:00:00.023Z
updated: 2024-12-27T19:43:25.336Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Securely Hiding Personal Info on Windows Login
excerpt: This Article Describes Securely Hiding Personal Info on Windows Login
keywords: Secure Windows Login,Privacy Windows Accounts,Hide User Details PC,Protect Windows ID,Safe Windows Credentials,Personal Data Security WIN,Stealth Windows Logon
thumbnail: https://thmb.techidaily.com/1acb8c811dd75a749590a9459a8ce73dd17ec95c9b2687aeea798f4dbe27d8a4.jpg
---

## Securely Hiding Personal Info on Windows Login

 If you frequently use your computer in public places, it's a good idea to remove your email address from the Windows login screen. This means people can't get your email address if they see your screen over your shoulder.

 You can accomplish this using the Settings app, Group Policy Editor, or Registry Editor. In this post, we've covered all these methods in detail.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cKRBWf1EDZo?si=CTNd4q450biit4eM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Hide Email Address From Windows Login Screen Using the Settings App

 The Windows Settings app provides a quick way to hide account information from the login screen. So, if you are in a rush, use the following steps to remove user email addresses from the Windows login screen.

1. Press**Win + I** or use one of the[many ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Accounts > Sign-in options** .
3. Under**Additional settings** , toggle off the switch next to **Show account details such as my email address on the sign-in screen** .  
![Hide Email From Windows Login Screen Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cBCyRXC1-Tw?si=lN9P2xo0hsfyD8K6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/ITtcSWvS8bo?si=4M4BfMgaabrW6148" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Exit the Registry Editor and restart your PC for the changes to take effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JMgRzDANfSQ?si=NDy01ntXGGOi1Uxs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-visual-virtuosos-guide-choosing-the-best-6-4k-cameras/"><u>[New] 2024 Approved Visual Virtuosos Guide Choosing the Best 6 4K Cameras</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-from-raw-footage-to-final-cut-youtube-edition/"><u>[New] In 2024, From Raw Footage to Final Cut YouTube Edition</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-zoom-mastering-screen-sharing-basics/"><u>[New] Zoom Mastering Screen-Sharing Basics</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-sony-xperia-xz-premium-high-res-video-capabilities-analyzed/"><u>[Updated] Sony Xperia XZ Premium High-Res Video Capabilities Analyzed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-error-code-0x800f0831-in-windows-os/"><u>Conquering Error Code 0X800F0831 in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-11s-package-control-using-wingetui/"><u>Enhancing Windows 11'S Package Control Using WingetUI</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/expanding-your-workspace-connect-a-second-thunderbolt-monitor-with-ease-on-the-new-m1-mac-mini-tips-and-tricks-for-enhanced-productivity-zdnet/"><u>Expanding Your Workspace: Connect a Second Thunderbolt Monitor with Ease on the New M1 Mac Mini - Tips & Tricks for Enhanced Productivity (ZDNET)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-enhancing-gpo-settings-access-win11-edition/"><u>Expert Tips for Enhancing GPO Settings Access, Win11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-correct-lsassexe-not-found-error-on-pc/"><u>How to Correct 'lsass.exe' Not Found Error on PC</u></a></li>
<li><a href="https://fox-http.techidaily.com/mastering-asmr-for-restful-slumber/"><u>Mastering ASMR for Restful Slumber</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-your-onedrive-without-an-online-connection/"><u>Navigate Your OneDrive Without an Online Connection</u></a></li>
<li><a href="https://tech-hub.techidaily.com/navigating-the-nuances-of-business-e-mails-with-gpt/"><u>Navigating the Nuances of Business E-Mails with GPT</u></a></li>
<li><a href="https://games-able.techidaily.com/overcoming-disconnected-world-in-pokemon-go/"><u>Overcoming Disconnected World in Pokémon GO</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11-taskbar-disruption/"><u>Overcoming Windows 11 Taskbar Disruption</u></a></li>
<li><a href="https://fox-shield.techidaily.com/resolving-screen-glitches-in-windows-systems-essential-guidance-by-yl-software-experts/"><u>Resolving Screen Glitches in Windows Systems: Essential Guidance by YL Software Experts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-ms-store-glitches-on-win-1111-platforms/"><u>Solutions for MS Store Glitches on Win 11/11 Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-find-and-restore-lost-pin-in-win-11-update-fallout/"><u>Steps to Find and Restore Lost PIN in Win 11 Update Fallout</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-back-your-search-power-tips-to-troubleshoot-windows-11s-search-issues/"><u>Winning Back Your Search Power: Tips to Troubleshoot Windows 11'S Search Issues</u></a></li>
<li><a href="https://solve-popular.techidaily.com/yl-software-insights-effective-solutions-for-handling-system-crashes-and-lock-ups/"><u>YL Software Insights: Effective Solutions for Handling System Crashes and Lock-Ups</u></a></li>
</ul></div>

