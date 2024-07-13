---
title: Configuring the Reset Failure Count for Incorrect Login Attempts on Windows 11
date: 2024-07-12T16:50:57.687Z
updated: 2024-07-13T16:50:57.687Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Configuring the Reset Failure Count for Incorrect Login Attempts on Windows 11
excerpt: This Article Describes Configuring the Reset Failure Count for Incorrect Login Attempts on Windows 11
keywords: Windows 11 Login Limits,Win11 Password Failures,Reset Attempt Control,Secure Login Windows 11,Incorrect Logins Management,Windows 11 Access Restrictions,Account Lockout Thresholds
thumbnail: https://thmb.techidaily.com/5137476410d550ff3157a9e8b8c303fc95e61e87d44f30246bb809e8ce4eedda.jpg
---

## Configuring the Reset Failure Count for Incorrect Login Attempts on Windows 11

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  
![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/the-complete-wm-maker-playbook-for-youtube-clips-perfection-for-2024/"><u>The Complete WM Maker Playbook for YouTube Clips Perfection for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-discover-the-10-best-yoga-platforms-for-enhanced-fitness/"><u>[New] Discover The 10 Best Yoga Platforms For Enhanced Fitness</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cease-auto-recommended-games-in-windows-11/"><u>Cease Auto-Recommended Games in Windows 11</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/chartbusters-of-the-digital-era-top-video-milestones-achieved-by-24/"><u>Chartbusters of the Digital Era  Top Video Milestones Achieved by '24</u></a></li>
<li><a href="https://youtube-web.techidaily.com/31271100-new-2024-approved-wave-goodbye-to-costs-with-our-50-free-banners-offer/"><u>[New] 2024 Approved  Wave Goodbye to Costs with Our 50 Free Banners Offer!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/storeroom-in-mp60-speed-still-scarce/"><u>Storeroom in MP60, Speed Still Scarce</u></a></li>
<li><a href="https://techidaily.com/unlock-android-phone-if-you-forget-the-samsung-galaxy-m34-password-or-pattern-lock-by-drfone-android-unlock-android-unlock/"><u>Unlock android phone if you forget the Samsung Galaxy M34 password or pattern lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proven-windows-methods-to-identify-system-gadgets/"><u>Proven Windows Methods to Identify System Gadgets</u></a></li>
<li><a href="https://android-frp.techidaily.com/frp-hijacker-by-hagard-download-and-bypass-your-oppo-a1x-5g-frp-locks-by-drfone-android/"><u>FRP Hijacker by Hagard Download and Bypass your Oppo A1x 5G FRP Locks</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-top-10-text-to-robot-voice-generators-windows-mac-android-iphone/"><u>2024 Approved Top 10 Text to Robot Voice Generators Windows, Mac, Android, iPhone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-xbox-mic-malfunctions-in-windows-os/"><u>Overcoming Xbox Mic Malfunctions in Windows OS</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-best-instagram-highlights-covers-apps-for-iphone-and-android/"><u>[Updated] In 2024, Best Instagram Highlights Covers Apps for iPhone and Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11-display-options-with-these-10-tips/"><u>Unlocking Windows 11 Display Options with These 10 Tips</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-2024-approved-synchronized-system-apple-watch-and-mac-unlocking/"><u>[New] 2024 Approved  Synchronized System  Apple Watch and Mac Unlocking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rejoining-fall-guys-fixing-connectivity-issues-on-pc/"><u>Rejoining Fall Guys: Fixing Connectivity Issues on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beating-the-buzz-mastering-voice-recorder-shortcuts-in-windows-11/"><u>Beating the Buzz: Mastering Voice Recorder Shortcuts in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-driver-initialization-failure-in-windows-11/"><u>Solutions for Driver Initialization Failure in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-the-mechanics-of-windows-11s-compatibility-tool/"><u>Uncovering the Mechanics of Windows 11’S Compatibility Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-the-non-verified-error-during-windows-file-installation/"><u>Solving the Non-Verified Error During Windows File Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-system-tray-and-secret-icons-in-win11/"><u>Decoding System Tray & Secret Icons in Win11</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-learn-the-art-of-adding-borders-on-insta-videos-for-2024/"><u>[Updated] Learn the Art of Adding Borders on Insta Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-command-gain-admin-status/"><u>Regain Command - Gain Admin Status</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-your-mouse-icon-with-ease-on-win-os/"><u>Transforming Your Mouse Icon with Ease on Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-resolving-user-not-found-issue-windows-1011/"><u>Steps for Resolving 'User Not Found' Issue: Windows 10/11</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-additional-tips-about-sinnoh-stone-for-honor-x50-gt-drfone-by-drfone-virtual-android/"><u>In 2024, Additional Tips About Sinnoh Stone For Honor X50 GT | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-intel-unison-for-windows-11-calling/"><u>The Ultimate Guide to Intel Unison for Windows 11 Calling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-back-old-file-management-interface/"><u>Bringing Back Old File Management Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/counteracting-shutdownrestart-blockage-due-to-deceptive-apps-in-windows/"><u>Counteracting Shutdown/Restart Blockage Due to Deceptive Apps in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719320946567-list-three-benefits-of-applying-a-cultural-relativist-approach-when-encountering-unfamiliar-customs-or-beliefs/"><u>List Three Benefits of Applying a Cultural Relativist Approach when Encountering Unfamiliar Customs or Beliefs</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-journey-into-the-metaverse-top-8-vr-headgear/"><u>[Updated] Journey Into the Metaverse  Top 8 VR Headgear</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-2024-approved-filmmaking-on-a-shoestring-10-essential-low-budget-tools/"><u>New 2024 Approved Filmmaking on a Shoestring 10 Essential Low-Budget Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-microsofts-ai-assistive-functions/"><u>Understanding Microsoft's AI Assistive Functions</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-11-restrictions-a-beginners-guide/"><u>Bypassing Windows 11 Restrictions: A Beginner's Guide</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-precision-in-video-calls-the-art-of-border-reduction/"><u>[Updated] Precision in Video Calls  The Art of Border Reduction</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-the-ultimate-tiktok-twitter-syncing-method/"><u>[New] The Ultimate TikTok-Twitter Syncing Method</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-3-effective-methods-to-fake-gps-location-on-android-for-your-oppo-a1x-5g-drfone-by-drfone-virtual/"><u>In 2024, 3 Effective Methods to Fake GPS location on Android For your Oppo A1x 5G | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/3-things-you-must-know-about-fake-snapchat-location-on-honor-x9a-drfone-by-drfone-virtual-android/"><u>3 Things You Must Know about Fake Snapchat Location On Honor X9a | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-error-unending-teams-sign-in-requests/"><u>Overcoming Windows Error: Unending Teams Sign-In Requests</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-best-mac-mp3-conversion-tools-a-comprehensive-guide/"><u>New In 2024, Best Mac MP3 Conversion Tools A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-d3dx939dll-loss-in-windows-11/"><u>Resolving D3DX9_39.dll Loss in Windows 11</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-the-blueprint-to-establishing-a-distinctive-marketing-persona/"><u>[New] In 2024, The Blueprint to Establishing a Distinctive Marketing Persona</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-unsuited-file-vlc-problem/"><u>Overcoming Windows' 'Unsuited File' VLC Problem</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-intense-evaluation-the-detailed-study-of-bublcam-360/"><u>[Updated] Intense Evaluation  The Detailed Study of Bublcam 360</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/everything-you-need-to-know-about-lock-screen-settings-on-your-realme-narzo-60-5g-by-drfone-android/"><u>Everything You Need to Know about Lock Screen Settings on your Realme Narzo 60 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-guide-to-managing-win11-applications-via-winget/"><u>The Complete Guide to Managing Win11 Applications via Winget</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-expanded-pinned-area-on-windows-11-ui/"><u>Techniques for Expanded Pinned Area on Windows 11 UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-inadequate-usb-support-on-desktops/"><u>Addressing Inadequate USB Support on Desktops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-tackling-windows-1011-interrupt-crashes/"><u>Strategies for Tackling Windows 10/11 INTERRUPT Crashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-checklist-longer-pins-in-windows-11-and-11/"><u>The Ultimate Checklist: Longer PINs in Windows 11 and 11</u></a></li>
</ul></div>
