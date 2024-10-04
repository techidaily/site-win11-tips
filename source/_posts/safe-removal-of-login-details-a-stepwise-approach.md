---
title: "Safe Removal of Login Details: A Stepwise Approach"
date: 2024-10-01T23:20:59.193Z
updated: 2024-10-03T19:37:19.391Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Safe Removal of Login Details: A Stepwise Approach"
excerpt: "This Article Describes Safe Removal of Login Details: A Stepwise Approach"
keywords: Safe Login Deletion,Password Cleanse Steps,Secure Sign Out Guide,Logout Without Risk,Removing User Credentials Safely,Stepwise Account Privacy,Protecting Logout Details
thumbnail: https://thmb.techidaily.com/ae96135be8b387f3dfcd58e7778aa73a8a480a5ecd8a0532a8cb17367d809b46.jpg
---

## Safe Removal of Login Details: A Stepwise Approach

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
<span id="1938141">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938141.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938141">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938141.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938141%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938141/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137226/26400" target="_top" id="2137226">
  <img src="//a.impactradius-go.com/display-ad/26400-2137226" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137226/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

8. Select**Enabled** in the properties window.
9. Click**Apply** followed by**OK** to save changes.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080333/19272" target="_top" id="2080333">
  <img src="//a.impactradius-go.com/display-ad/19272-2080333" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080333/19272" style="position:absolute;visibility:hidden;" border="0" />
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

 Exit the Registry Editor and restart your PC for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541">
  <img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-unlocking-igtvs-potential-secrets-to-attract-more-subscribers/"><u>[Updated] In 2024, Unlocking IGTV's Potential Secrets to Attract More Subscribers</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-boost-your-tech-experience-with-top-text-interpretation-tools-on-mac/"><u>2024 Approved Boost Your Tech Experience with Top Text Interpretation Tools on Mac</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/-of-wisdom-youtube-tvs-unique-selling-points-for-2024/"><u>Bites of Wisdom YouTube TV's Unique Selling Points for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-code-how-long-can-your-password-be/"><u>Breaking the Code: How Long Can Your Password Be?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-freeze-on-dormant-windows-batch-file-functionality/"><u>Breaking the Freeze on Dormant Windows Batch File Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-through-the-barrier-of-ms-store-access/"><u>Breaking Through the Barrier of MS Store Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathe-life-into-your-old-videos-using-madvr-in-the-windows-sphere/"><u>Breathe Life Into Your Old Videos: Using MadVR in the Windows Sphere</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-the-gap-between-internet-access-methods-a-guide-to-dual-connectivity-on-windows/"><u>Bridging the Gap Between Internet Access Methods: A Guide to Dual Connectivity on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/browser-barriers-overcome-top-strategies-for-website-access-in-win-os/"><u>Browser Barriers Overcome: Top Strategies for Website Access in Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-updates-failure-0x800f0845/"><u>Bypassing Updates Failure: 0X800F0845</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-tricky-email-mishap-defeating-error-code-0x800713f/"><u>Bypassing Windows' Tricky Email Mishap: Defeating Error Code 0X800713F</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cable-free-controller-configuration-windows-plus-playstation-3/"><u>Cable-Free Controller Configuration: Windows + PlayStation 3</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/exploring-versatility-in-portable-charging-detailed-look-at-omnicharges-omni-20-power-bank-with-qi-technology/"><u>Exploring Versatility in Portable Charging: Detailed Look at Omnicharge's Omni 20 Power Bank With Qi Technology</u></a></li>
<li><a href="https://driver-error.techidaily.com/gfx-analysis-the-role-of-ms-bda/"><u>GFX Analysis: The Role of MS BDA</u></a></li>
<li><a href="https://article-posts.techidaily.com/in-2024-premiere-previews-extravaganza/"><u>In 2024, Premiere Previews Extravaganza</u></a></li>
<li><a href="https://tech-hub.techidaily.com/1721883691264-introducing-ai-search-access-bing-on-your-devices/"><u>Introducing AI Search: Access Bing on Your Devices</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/mastering-itunes-archives-in-3-easy-steps/"><u>Mastering iTunes Archives in 3 Easy Steps</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/say-hello-to-superior-reception-with-the-straightforward-yet-exceptional-clearstream-eclipse-antenna/"><u>Say Hello to Superior Reception with the Straightforward yet Exceptional ClearStream Eclipse Antenna</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-apple-iphone-se-2020-drfone-by-drfone-virtual-ios/"><u>Will Pokémon Go Ban the Account if You Use PGSharp On Apple iPhone SE (2020) | Dr.fone</u></a></li>
</ul></div>

