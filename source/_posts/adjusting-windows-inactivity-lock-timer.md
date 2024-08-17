---
title: Adjusting Windows Inactivity Lock Timer
date: 2024-08-16T02:21:08.575Z
updated: 2024-08-17T02:21:08.575Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Windows Inactivity Lock Timer
excerpt: This Article Describes Adjusting Windows Inactivity Lock Timer
keywords: WinLock Adjustment,Activity Lock Time,Inactive Session Halt,Timers in Windows Security,Lockout Period Change,Active-Inactive Timer Control,Reducing Login Delays
thumbnail: https://thmb.techidaily.com/2fabafc66fe8d6c738eceaf2d94bef9969abb79ce6dfc7f79cdd9561a56a5238.jpg
---

## Adjusting Windows Inactivity Lock Timer

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
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. Click the down arrow next to**Local Policies** in the left pane to expand it.
3. Click on**Security Options** to open it.
4. The Security Options will open up in the right pane. Now scroll down to the policy named**Interactive logon: Machine inactivity limit** and double-click on it to open its properties.  
![Machine Inactivity Limit Selected in Security Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/select-machine-inactivity-limit-in-security-options.jpg)
<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Under the section**Machine will be locked after** , enter the time in seconds after which you want your PC to get locked automatically. This time is the time of machine inactivity or the time when your PC is idle. You can enter the time between**0** to**599940** seconds. For this tutorial, we'll enter**300 seconds** which is five minutes. Now click on**Apply** and then**OK** .
6. Finally, close the Local Security Policy window and restart your computer for the change to take effect.

 Now, when you use your PC, you will experience that your PC will lock itself after your custom timer expires. And if someone tries to unlock your PC while you're gone, it'll ask them for your password, which should keep them at bay until you get back.

 If you ever want to reverse this action and not have your PC lock automatically, just open the**Interactive logon: Machine inactivity limit** policy in**Local Security Policy** . Then just change the time or seconds to**0** —this is the default setting and will not lock your PC automatically.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
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
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Click on the**System** key in the left pane and its components will open up in the right pane. Now scroll down to get to the**InactivityTimeoutSecs** DWORD.  
![Scroll to InactivityTimeoutSecs in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/scroll-to-inactivitytimeoutsecs.jpg)
5. Double-click on the**InactivityTimeoutSecs** DWORD to modify its value. Select**Decimal** under**Base** , and under**Value data** , enter a number between**0** to**599940** —this is the time in seconds after which your PC will get locked automatically. Like in the Local Security Policy method, we'll give it a time of**300 seconds** or five minutes. Now tap on**OK** .
6. In case you do not find the**InactivityTimeoutSecs** DWORD in your registry, you can create it. Right-click on the**System** key folder in the left pane or right-click on a space in the right pane of the**System** key. Select**New** , then select**DWORD (32-bit) Value** .  
![Create InactivityTimeoutSecs DWORD in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/create-inactivitytimeoutsecs-dword.jpg)  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
 A new value will be created in the right pane. Name it**InactivityTimeoutSecs** . Then press**Enter** .
7. Now double-click on**InactivityTimeoutSecs** DWORD, and enter the time after which you want your PC to get locked.
8. Finally, close the Registry Editor and restart your PC to apply the changes.

 Now your PC will get locked if you're not using it or are away from it after the time you have set in the Registry Editor. If you're on a Windows 11 machine, you can also [explore a few other ways to lock your PC](https://www.makeuseof.com/windows-11-ways-to-lock/) .

 To stop your PC from getting locked automatically, modify the**InactivityTimeoutSecs** DWORD value in the Registry Editor by changing the time to**0** seconds.

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-how-to-upload-window-movie-maker-video-to-vimeo/"><u>[New] 2024 Approved  How to Upload Window Movie Maker Video to Vimeo</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-mastering-facebook-vids-the-top-20-marketing-hacks/"><u>[New] 2024 Approved  Mastering Facebook Vids  The Top 20 Marketing Hacks</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-understanding-facebook-story-algorithms-how-to-optimize-for-success/"><u>[New] 2024 Approved  Understanding Facebook Story Algorithms  How to Optimize for Success</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-achieving-professional-streams-with-obs-android-style/"><u>[New] Achieving Professional Streams with OBS, Android Style</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-ideal-mp4-slicer-for-mac-boost-your-vlog-game/"><u>[New] Ideal MP4 Slicer for Mac  Boost Your Vlog Game</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-obspluszoom-creating-a-flawless-production-workflow-for-2024/"><u>[New] OBS+Zoom  Creating a Flawless Production Workflow for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-the-art-of-arranging-youtube-video-elements/"><u>[New] The Art of Arranging YouTube Video Elements</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-champion-phonographs-for-seminar-sessions/"><u>[Updated] 2024 Approved  Champion Phonographs for Seminar Sessions</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-audiograbbers-free-toolkit-and-evaluation/"><u>[Updated] In 2024, AudioGrabbers Free Toolkit & Evaluation</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-craft-your-own-story-the-top-5-instagram-tips-for-aspiring-social-stars/"><u>[Updated] In 2024, Craft Your Own Story  The Top 5 Instagram Tips for Aspiring Social Stars</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-from-joke-to-jest-constructing-impactful-social-media-memes/"><u>[Updated] In 2024, From Joke to Jest  Constructing Impactful Social Media Memes</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-the-gentle-art-of-stepping-back-from-discords-for-2024/"><u>[Updated] The Gentle Art of Stepping Back From Discords for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-comprehensible-guide-downloading-safe-free-vlc-on-macos/"><u>2024 Approved  The Comprehensible Guide  Downloading Safe, Free VLC on macOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-technical-odyssey-embracing-hdr-in-windows-11-environments/"><u>A Technical Odyssey: Embracing HDR in Windows 11 Environments</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/a-list-makeup-tutorials-who-to-watch/"><u>A-List Makeup Tutorials  Who to Watch ?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-device-to-windows-microphone-setup/"><u>Android Device to Windows Microphone Setup</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-for-resource-utilization-in-wsl-android/"><u>Best Practices for Resource Utilization in WSL-Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blend-in-with-the-background-hide-taskbars-language-bar-win11/"><u>Blend in with the Background: Hide Taskbar's Language Bar, Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-user-interface-add-psoft-tools-to-windows-11/"><u>Boosting User Interface: Add PSoft Tools to Windows 11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-make-excel-2000-hyperlinks-working-by-stellar-guide/"><u>Easy Steps to Make Excel 2000 Hyperlinks Working</u></a></li>
<li><a href="https://win-dash.techidaily.com/effortless-driver-update-procedures-for-the-lenovo-t450-expert-tips-and-tricks/"><u>Effortless Driver Update Procedures for the Lenovo T450: Expert Tips & Tricks</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/enhance-editing-efficiency-the-finest-text-plugins-for-ae/"><u>Enhance Editing Efficiency  The Finest Text Plugins for AE</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-subsystem-with-5-crucial-techniques/"><u>Enhancing Windows Subsystem with 5 Crucial Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-to-unlock-disks-in-w10-and-w11/"><u>Essential Steps to Unlock Disks in W10 & W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-vivetool-windows-gateway-to-new-and-emerging-tools/"><u>Exploring ViVeTool: Windows' Gateway to New & Emerging Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-app-install-issues-on-microsoft-store/"><u>Fixing App Install Issues on Microsoft Store</u></a></li>
<li><a href="https://program-issues.techidaily.com/how-to-fix-unable-to-sync-in-your-steam-gaming-library-a-step-by-step-guide/"><u>How to Fix 'Unable to Sync' In Your Steam Gaming Library: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-fatal-error-c0000022-in-windows/"><u>How to Fix the Fatal Error C0000022 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-handle-internal-windows-error-during-remote-desktop-use/"><u>How to Handle Internal Windows Error During Remote Desktop Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-swiftly-and-permanently-discard-a-partition-on-windows-pc/"><u>How to Swiftly and Permanently Discard a Partition on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/implementing-edthemes-in-windows-11/"><u>Implementing EdThemes in Windows 11</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-access-your-apple-iphone-14-pro-when-you-forget-the-passcode-by-drfone-ios/"><u>In 2024, How to Access Your Apple iPhone 14 Pro When You Forget the Passcode?</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-fix-pokemon-go-route-not-working-on-realme-narzo-n55-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Pokemon Go Route Not Working On Realme Narzo N55? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lowering-resource-usage-in-windows-modules-installer/"><u>Lowering Resource Usage in Windows Modules Installer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-speech-output-in-windows-environment/"><u>Mastering Speech Output in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-freeing-up-your-c-drive-space/"><u>Mastering the Art of Freeing Up Your C: Drive Space</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-efficiency-guide/"><u>Mastering Windows 11: Efficiency Guide</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/maximizing-your-amazon-prime-experience-with-toshibas-55lf711u20-fire-tv-reviewed/"><u>Maximizing Your Amazon Prime Experience with Toshiba's 55LF711U20 Fire TV Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-microsoft-pc-manager-bar-tools-on-w11/"><u>Navigating Microsoft PC Manager Bar Tools on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-failure-to-install-win11s-v22h2-update/"><u>Navigating Through Failure to Install Win11's V22H2 Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/nine-must-have-android-apps-for-windows-users/"><u>Nine Must-Have Android Apps for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-internet-unreachability-issue/"><u>Overcoming Internet Unreachability Issue</u></a></li>
<li><a href="https://extra-support.techidaily.com/polaroid-cubeplus-action-camera-review-for-2024/"><u>Polaroid Cube+ Action Camera Review for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-music-from-redmi-a2-by-fonelab-android-recover-music/"><u>Possible solutions to restore deleted music from Redmi A2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prevent-non-scrollability-of-ranges-in-excel-windows/"><u>Prevent Non-Scrollability of Ranges in Excel, Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-tips-for-modifying-windows-passcode/"><u>Quick Tips for Modifying Windows Passcode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-windows-standard-power-profile/"><u>Restoring Windows' Standard Power Profile</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safeguarding-internal-builds-in-windows-11/"><u>Safeguarding Internal Builds in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secrets-to-turn-off-lurking-apps-in-window-11/"><u>Secrets to Turn Off Lurking Apps in Window 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/skirting-watermarks-in-stock-photography/"><u>Skirting Watermarks in Stock Photography</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-error-0x80246007-on-windows-11-updates/"><u>Solving Error 0X80246007 on Windows 11 Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-guide-for-converting-cr2-images-to-windows-jpeg-files/"><u>Stepwise Guide for Converting CR2 Images to Windows JPEG Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-manage-disks-keyways-into-windows-11s-storage-manager/"><u>Swiftly Manage Disks: Keyways Into Windows 11'S Storage Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackle-windows-camera-problems-with-expert-tips/"><u>Tackle Windows Camera Problems with Expert Tips</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/management-for-those-balancing-careers-and-youtubing-for-2024/"><u>Time Management for Those Balancing Careers and YouTubing for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719237818540-trouble-with-compatibility-try-these-straightforward-fixes-now/"><u>Trouble with Compatibility? Try These Straightforward Fixes Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-xbox-apps-voice-issues-in-windows/"><u>Understanding Xbox App's Voice Issues in Windows</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unveiling-key-traits-of-gpt-4-and-gpt-35/"><u>Unveiling Key Traits of GPT-4 and GPT-3.5</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unzipping-challenge-managing-multiple-compressed-files-in-a-snap/"><u>Unzipping Challenge: Managing Multiple Compressed Files in a Snap</u></a></li>
<li><a href="https://win11-tips.techidaily.com/workarounds-to-manipulate-windows-11-sleepwake/"><u>Workarounds to Manipulate Windows 11 Sleep/Wake</u></a></li>
</ul></div>
