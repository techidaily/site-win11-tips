---
title: How to Adjust Windows Activity Lock
date: 2024-08-16T02:04:01.286Z
updated: 2024-08-17T02:04:01.286Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Adjust Windows Activity Lock
excerpt: This Article Describes How to Adjust Windows Activity Lock
keywords: Fixing Window Lock,Unlock Windows Accidentally,Bypass Window Security,Resetting Lock Screen,Access Locked Desktop,Disable Activity Lock,Windows Lock Release Guide
thumbnail: https://thmb.techidaily.com/4c3c65f6b07b6c1127c499f9b9889ab3244702ce710d3692e68eb1f54ab083aa.jpg
---

## How to Adjust Windows Activity Lock

 PC security is not just about having antivirus software on your computer. You should also restrict access to your documents on your PC while you're away from your machine.

 Read on to explore how you can automatically lock your PC after a set time, even when you leave it unattended.

## How to Keep Your Windows PC Inaccessible While Your Gone

 There are lots of places you could use a PC or laptop. It could be in the office, at a conference venue, or on the go at your favorite café. And there'll be times you just need to get up to attend to something pressing.

 Fortunately, you can set your PC to lock automatically after a custom amount of time without activity. This means you can safely leave your work desk, knowing your work is safe from prying eyes.

 Of course, you can also lock your PC manually when you walk away from it—just press the**Win + L** keys together or**Ctrl + Alt + Del** and then sign out. But you could miss doing that in a rush, or if you're distracted.

 Instead, check out these methods to configure your Windows PC to lock automatically when there is no activity after a specific amount of time.

## 1\. How to Lock Your Windows PC After a Set Time via the Local Security Policy

 Using the Local Security Policy, you can set the exact time in seconds after which your PC will lock itself automatically. Make sure you're signed in as an administrator to automatically lock your PC.

 Local Security Policy is only available in the Windows 10 and 11 Pro, Education, and Enterprise editions. If you're using the Home version, skip to method two.

1. Type**Local Security Policy** in Windows Search. Click the**Local Security Policy** under**Best match** to open it. Alternatively, press the**Win + R** keys together to open the**Run** box. Type**secpol.msc** in the**Open** navigation bar and click**OK** or hit**Enter** to launch it.  
![Open Local Security Policy via Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/open-local-security-policy-via-run.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. Click the down arrow next to**Local Policies** in the left pane to expand it.
3. Click on**Security Options** to open it.
4. The Security Options will open up in the right pane. Now scroll down to the policy named**Interactive logon: Machine inactivity limit** and double-click on it to open its properties.  
![Machine Inactivity Limit Selected in Security Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/select-machine-inactivity-limit-in-security-options.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
5. Under the section**Machine will be locked after** , enter the time in seconds after which you want your PC to get locked automatically. This time is the time of machine inactivity or the time when your PC is idle. You can enter the time between**0** to**599940** seconds. For this tutorial, we'll enter**300 seconds** which is five minutes. Now click on**Apply** and then**OK** .
6. Finally, close the Local Security Policy window and restart your computer for the change to take effect.

 Now, when you use your PC, you will experience that your PC will lock itself after your custom timer expires. And if someone tries to unlock your PC while you're gone, it'll ask them for your password, which should keep them at bay until you get back.

 If you ever want to reverse this action and not have your PC lock automatically, just open the**Interactive logon: Machine inactivity limit** policy in**Local Security Policy** . Then just change the time or seconds to**0** —this is the default setting and will not lock your PC automatically.

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. How to Lock Your Windows PC After a Specific Amount of Inactivity via the Registry Editor

 You can tweak settings in the Registry Editor to configure your PC to lock automatically after a set time. And you can do this in Windows Home and all the other Windows editions.

 However, you must be careful while making changes in the registry and should only make the changes as detailed below and not change anything else. It'd be a good idea to create a restore point in Windows before you change your registry settings. If something goes wrong, you can revert your PC to its last working state.

 Now let's go ahead and explore how to lock your PC automatically via the Registry Editor.

1. Type**Registry Editor** in**Windows Search** and select**Registry Editor** under**Best match** . Or use one of the many [ways to open the Registry Editor in Windows 11](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Click on**Yes** on the UAC prompt.
3. In the left pane, use the following path to reach the**System** registry key: **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System**  
![Navigate to System Key in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/navigate-to-system-key-in-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Click on the**System** key in the left pane and its components will open up in the right pane. Now scroll down to get to the**InactivityTimeoutSecs** DWORD.  
![Scroll to InactivityTimeoutSecs in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/scroll-to-inactivitytimeoutsecs.jpg)
5. Double-click on the**InactivityTimeoutSecs** DWORD to modify its value. Select**Decimal** under**Base** , and under**Value data** , enter a number between**0** to**599940** —this is the time in seconds after which your PC will get locked automatically. Like in the Local Security Policy method, we'll give it a time of**300 seconds** or five minutes. Now tap on**OK** .
6. In case you do not find the**InactivityTimeoutSecs** DWORD in your registry, you can create it. Right-click on the**System** key folder in the left pane or right-click on a space in the right pane of the**System** key. Select**New** , then select**DWORD (32-bit) Value** .  
![Create InactivityTimeoutSecs DWORD in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/create-inactivitytimeoutsecs-dword.jpg)  
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 A new value will be created in the right pane. Name it**InactivityTimeoutSecs** . Then press**Enter** .
7. Now double-click on**InactivityTimeoutSecs** DWORD, and enter the time after which you want your PC to get locked.
8. Finally, close the Registry Editor and restart your PC to apply the changes.

 Now your PC will get locked if you're not using it or are away from it after the time you have set in the Registry Editor. If you're on a Windows 11 machine, you can also [explore a few other ways to lock your PC](https://www.makeuseof.com/windows-11-ways-to-lock/) .

 To stop your PC from getting locked automatically, modify the**InactivityTimeoutSecs** DWORD value in the Registry Editor by changing the time to**0** seconds.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
## Work Worry-Free on Your Windows PC With a Custom Time-Out Lock

 Now never be tense about someone getting access to your PC or your work getting stolen while you're away from your PC. Use one of the above methods to automatically lock your PC after a set time.

 You can also explore how to set up Dynamic Lock using your phone to automatically lock your PC when you move away from it.


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
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-mastery-over-buffering-in-vimeo-streams-revised-tips/"><u>[New] 2024 Approved  Mastery Over Buffering in Vimeo Streams (Revised Tips)</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/024-approved-simple-steps-for-incorporating-videos-into-articles/"><u>[New] 2024 Approved  Simple Steps for Incorporating Videos Into Articles</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-enhance-your-ig-visuals-with-three-effective-video-descriptions/"><u>[New] Enhance Your IG Visuals with Three Effective Video Descriptions</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-2024-approved-tune-up-your-social-media-videos-for-maximum-impact/"><u>[Updated] 2024 Approved  Tune Up Your Social Media Videos for Maximum Impact</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-capture-and-store-5-best-ways-to-save-your-favorite-facebook-videos/"><u>[Updated] In 2024, Capture & Store  5 Best Ways to Save Your Favorite Facebook Videos</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-top-5-secure-methods-to-maximize-instagram-earnings-for-2024/"><u>[Updated] Top 5 Secure Methods to Maximize Instagram Earnings for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/3-ways-to-unlock-iphone-12-pro-without-passcode-or-face-id-drfone-by-drfone-ios/"><u>3 Ways to Unlock iPhone 12 Pro without Passcode or Face ID | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-how-to-for-customizing-windows-11-with-widgets/"><u>A Comprehensive How-To for Customizing Windows 11 with Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-network-adapter-error-31-quickly/"><u>Addressing Windows Network Adapter Error 31 Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoidance-and-remediation-for-a-frozen-resource-monitor-app-in-windows-11/"><u>Avoidance and Remediation for a Frozen Resource Monitor App in Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-oppo-reno-11-pro-5g-drfone-by-drfone-virtual-android/"><u>Catch or Beat Sleeping Snorlax on Pokemon Go For Oppo Reno 11 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ceasing-windows-notification-for-updates/"><u>Ceasing Windows Notification for Updates</u></a></li>
<li><a href="https://extra-information.techidaily.com/comprehensive-analysis-of-android-based-lightroom-software-for-2024/"><u>Comprehensive Analysis of Android-Based Lightroom Software for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/embedding-ical-into-your-windows-system-without-hassle/"><u>Embedding iCal Into Your Windows System without Hassle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-insights-employing-law-filters-within-windows/"><u>Essential Insights: Employing LAW Filters Within Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-guide-to-the-best-fileshare-apps-on-a-windows-laptop/"><u>Exclusive Guide to the Best Fileshare Apps on a Windows Laptop</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-xiaomi-redmi-a2-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on Xiaomi Redmi A2 | Dr.fone</u></a></li>
<li><a href="https://driver-download.techidaily.com/get-your-free-scarlett-solo-professional-recording-mic-preamp-for-windows-pcs/"><u>Get Your FREE Scarlett Solo - Professional Recording Mic Preamp for Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-examine-excel-data-in-notepad/"><u>How to Examine Excel Data in Notepad</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-your-oppo-k11-5g-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>How to Mirror Your Oppo K11 5G Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-strategies-against-locked-out-windows-pin/"><u>Immediate Strategies Against Locked-Out Windows PIN</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-flavor-of-fun-explore-the-10-top-themes-at-betterdiscord/"><u>In 2024, Flavor of Fun  Explore the 10 Top Themes at BetterDiscord</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-poco-c51-phone-with-broken-screen-by-drfone-android/"><u>In 2024, How to Unlock Poco C51 Phone with Broken Screen</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-livestreaming-hacks-every-broadcaster-should-know/"><u>In 2024, Livestreaming Hacks Every Broadcaster Should Know</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/in-2024-worldwide-rich-list-top-earning-youtubers/"><u>In 2024, Worldwide Rich List  Top Earning YouTubers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lowering-dropbox-cpu-utilization-on-windows-machines/"><u>Lowering Dropbox CPU Utilization on Windows Machines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masteringdarkmodesettingforwindowstexteditor/"><u>MasteringDarkModeSettingForWindowsTextEditor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-error-0x0000004e-in-windows-devices/"><u>Navigating Error 0X0000004E in Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-ignoring-soon-expiring-licenses-alerts-in-windows/"><u>Quick Fix for Ignoring Soon Expiring Licenses Alerts in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-this-pc-cant-run-post-windows-11-setup/"><u>Rectifying 'This PC Can't Run' Post-Windows 11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-command-over-disabled-menu-functions/"><u>Regaining Command over Disabled Menu Functions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remediation-steps-for-windows-sandboxs-hypervisor-not-found/"><u>Remediation Steps for Windows Sandbox's Hypervisor Not Found</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-internal-errors-quickly-with-windows-rdp-connections/"><u>Resolving Internal Errors Quickly with Windows RDP Connections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/running-state-of-the-art-ai-windows-edition/"><u>Running State-of-the-Art AI: Windows Edition</u></a></li>
<li><a href="https://games-able.techidaily.com/score-big-pinpointing-quality-apple-arcade-playables/"><u>Score Big: Pinpointing Quality Apple Arcade Playables</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-file-organization-in-windows-11/"><u>Simplifying File Organization in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-cant-get-mail-errors-windows-11-edition/"><u>Strategies to Overcome Can’t Get Mail Errors, Windows 11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-8-cross-platform-tools-for-microsoft-enthusiasts/"><u>Top 8 Cross-Platform Tools for Microsoft Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-history-hiccup-quick-fixes-in-3-steps/"><u>Windows History Hiccup - Quick Fixes in 3 Steps</u></a></li>
</ul></div>
