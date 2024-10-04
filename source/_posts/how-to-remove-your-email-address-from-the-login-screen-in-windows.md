---
title: How to Remove Your Email Address From the Login Screen in Windows
date: 2024-09-29T18:06:12.763Z
updated: 2024-10-03T20:34:06.255Z
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

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528689/16446" target="_top" id="1528689">
  <img src="//a.impactradius-go.com/display-ad/16446-1528689" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528689/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2068426/7443" target="_top" id="2068426">
  <img src="//a.impactradius-go.com/display-ad/7443-2068426" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068426/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137221/26400" target="_top" id="2137221">
  <img src="//a.impactradius-go.com/display-ad/26400-2137221" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137221/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Exit the Registry Editor and restart your PC for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938716/19272" target="_top" id="1938716">
  <img src="//a.impactradius-go.com/display-ad/19272-1938716" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938716/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-top-tactics-for-captivating-audienes-in-instagram-reels/"><u>[New] 2024 Approved Top Tactics for Captivating Audienes in Instagram Reels</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-cinematic-clarity-hub-query-responses/"><u>[Updated] Cinematic Clarity Hub Query Responses</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-tackling-muted-frames-on-snapchat-videos-the-ultimate-solution/"><u>[Updated] Tackling Muted Frames on Snapchat Videos - The Ultimate Solution</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2023s-secretive-vids-downloader-list-top-8-edition-for-2024/"><u>2023'S Secretive Vids Downloader List Top 8 Edition for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delving-into-automated-software-fixes-windows-way/"><u>Delving Into Automated Software Fixes: Windows Way</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-making-windows-menus-less-obvious/"><u>Expert Tips: Making Windows Menus Less Obvious</u></a></li>
<li><a href="https://win11-tips.techidaily.com/getting-to-know-wintoys-your-intuitive-guide-to-an-underutilized-tool-in-windows/"><u>Getting to Know WinToys: Your Intuitive Guide to an Underutilized Tool in Windows</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/how-to-ensure-your-iphones-data-is-gone-forever-the-stellar-method-revealed/"><u>How to Ensure Your iPhone's Data Is Gone Forever – The Stellar Method Revealed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-ccleaner-not-working-on-windows-10-and-11/"><u>How to Fix CCleaner Not Working on Windows 10 & 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-avoiding-simulated-reality-ills-strategies-and-tips/"><u>In 2024, Avoiding Simulated Reality Ills Strategies and Tips</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-premium-quality-computers-at-your-desk/"><u>In 2024, Premium Quality Computers at Your Desk</u></a></li>
<li><a href="https://win11-tips.techidaily.com/msstore-dilemma-resolving-windows-error-code-0x0-in-3-steps/"><u>MsStore Dilemma - Resolving Windows Error Code 0X0 in 3 Steps</u></a></li>
<li><a href="https://ai-video.techidaily.com/new-the-ever-changing-era-of-ai-video-translation-a-reality-to-be-fulfilled/"><u>New The Ever-Changing Era of AI Video Translation A Reality to Be Fulfilled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-disconnected-remote-resources-on-your-pc/"><u>Reviving Disconnected Remote Resources on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-sniptools-unresponsive-commands/"><u>Troubleshooting SnipTool's Unresponsive Commands</u></a></li>
<li><a href="https://buynow-help.techidaily.com/value-meets-performance-in-our-comprehensive-oneplus-nord-n1-review/"><u>Value Meets Performance in Our Comprehensive OnePlus Nord N1^ Review!</u></a></li>
</ul></div>

