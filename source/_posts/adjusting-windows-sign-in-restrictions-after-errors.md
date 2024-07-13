---
title: Adjusting Windows Sign In Restrictions After Errors
date: 2024-07-12T18:01:56.299Z
updated: 2024-07-13T18:01:56.299Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Windows Sign In Restrictions After Errors
excerpt: This Article Describes Adjusting Windows Sign In Restrictions After Errors
keywords: Fix Sign-In Issues Windows,Adjust Windows Login Limits,Reset Windows Access Errors,Correct Login Errors Windows,Modify Windows Account Restrictions,Resolve Windows Sign In Errors,Alter User Permissions Windows
thumbnail: https://thmb.techidaily.com/e7e8dd516afa1923591eaf41c5af1b183e6c455af91f00d4dbb04a5e5e72a795.jpg
---

## Adjusting Windows Sign In Restrictions After Errors

 Windows has a policy setting that can lock someone out from signing in if they enter the wrong local account password too many times. The user is not allowed to sign in for a set number of minutes after being locked out, but you can change this lockout duration.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

## How to Change the Duration a User Is Locked Out of Their Account via Local Security Policy

 This method will work as long as the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press **Windows key + R** to open the **Run** dialogue.
2. Type “secpol.msc” into the text field and hit **Enter**.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, click on the **Account Lockout Policy** folder under **Account Policies**.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on **Account lockout duration**.  
![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  
![Choose how long a local account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-set-local-account-lockout-duration.jpg)

## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
3. This will pull up information, among other things, about how long this account lockout duration is currently set.
4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

## Find the Balance Between Security and Convenience

 Setting account lockout duration too high will cause inconvenience, but if you set it to zero, an administrator will have to be contacted each time a user locks themselves out. Find a balance between security and convenience when it comes to changing how long a user is locked out after a set number of failed login attempts.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/avoiding-delays-when-integrating-an-additional-screen-to-windows/"><u>Avoiding Delays When Integrating an Additional Screen to Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-the-impact-of-audio-device-isolation/"><u>Analyzing the Impact of Audio Device Isolation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-writing-with-these-top-pc-apps/"><u>Boost Your Writing with These Top PC Apps</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-what-to-look-for-in-a-youtube-mp3-converter-a-beginners-guide/"><u>Updated 2024 Approved What to Look for in a YouTube MP3 Converter A Beginners Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-generated-windows-keys-unveiling-potential-perils/"><u>AI-Generated Windows Keys: Unveiling Potential Perils</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augment-windows-security-incorporating-advanced-firewalls-in-the-context-menu/"><u>Augment Windows Security: Incorporating Advanced Firewalls in the Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-disk-alignment-failures/"><u>Addressing Windows Disk Alignment Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-disruptions-how-to-mend-broken-windows-registry-items/"><u>Avoiding Disruptions: How to Mend Broken Windows Registry Items</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-the-speedy-route-to-collecting-cutting-edge-tiktoks/"><u>[Updated] 2024 Approved  The Speedy Route to Collecting Cutting-Edge TikToks</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-unlock-nubia-z50-ultra-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>In 2024, Unlock Nubia Z50 Ultra Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-reimagining-creation-in-the-crypto-world-a-guide-to-top-nft-generating-platforms/"><u>[New] Reimagining Creation in the Crypto World - A Guide to Top NFT-Generating Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blend-worlds-the-best-6-android-apps-for-an-advanced-window-11-experience/"><u>Blend Worlds: The Best 6 Android Apps for an Advanced Window 11 Experience</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-adobe-premiere-power-enhancing-your-youtube-presence/"><u>[Updated] 2024 Approved  Adobe Premiere Power  Enhancing Your YouTube Presence</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-best-free-youtube-video-editing-apps-for-iphone-and-ipad-and-how-tos/"><u>2024 Approved  Best Free YouTube Video Editing Apps for iPhone & iPad & How-Tos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoidance-procedures-for-win-11-mobility-center/"><u>Avoidance Procedures for Win 11 Mobility Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-brainpower-the-ultimate-8-windows-guide-to-studying/"><u>Boost Your Brainpower: The Ultimate 8 Windows Guide to Studying</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-a-keygen-examining-its-impacts-and-cleanup-techniques-for-pcs/"><u>What Is a Keygen? Examining Its Impacts and Cleanup Techniques for PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-real-time-task-tracker-on-windows-11-os/"><u>Boosting Real-Time Task Tracker on Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-10-and-11s-paudio-issue-with-audacity/"><u>Addressing Windows 10 & 11'S PAudio Issue with Audacity</u></a></li>
<li><a href="https://extra-hints.techidaily.com/hilarityhub-online-tool-for-funny-image-crafting/"><u>HilarityHub  Online Tool for Funny Image Crafting</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-collaborative-video-workflows-for-content-growth/"><u>[New] 2024 Approved  Collaborative Video Workflows for Content Growth</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-maximizing-your-social-media-impact-group-photosvideos-on-ig/"><u>In 2024, Maximizing Your Social Media Impact  Group Photos/Videos on IG</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-top-tiktok-chefs-and-culinary-stars-for-2024/"><u>[Updated] Top TikTok Chefs & Culinary Stars for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-zoom-failures-immediate-resolution-for-error-1132/"><u>Avoiding Zoom Failures - Immediate Resolution for Error 1132</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-sticky-situations-solved-tiktok-video-cleanup/"><u>2024 Approved  Sticky Situations Solved  TikTok Video Cleanup</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-evaluating-bandicam-and-camtasia-for-mac-users/"><u>[New] Evaluating Bandicam and Camtasia for Mac Users</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-streamline-webcam-use-on-modern-devices/"><u>[Updated] In 2024, Streamline Webcam Use on Modern Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-a-marooned-experience-with-xbox-in-windows-11/"><u>Avoiding a Marooned Experience with Xbox in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-your-keystrokes-typingaid-techniques/"><u>Amplify Your Keystrokes - TypingAid Techniques</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-infinix-zero-5g-2023-turbo-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Infinix Zero 5G 2023 Turbo to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blend-audio-and-video-recording-on-windows-11s-snipping-tool-max-156/"><u>Blend Audio and Video Recording on Windows 11'S Snipping Tool (Max 156)</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-clipcraft-designer/"><u>[Updated] 2024 Approved  ClipCraft Designer</u></a></li>
<li><a href="https://windows11.techidaily.com/1719297453407-mastery-overprint-how-to-reactivate-the-missing-windows-functionality/"><u>Mastery Overprint: How to Reactivate the Missing Windows Functionality</u></a></li>
<li><a href="https://some-techniques.techidaily.com/filching-frames-from-films-for-windows-10-photos-collection-for-2024/"><u>Filching Frames From Films for Windows 10 Photos Collection for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-terminal-background-for-custom-aesthetics/"><u>Adjust Terminal Background for Custom Aesthetics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-access-windows-shared-folders/"><u>Android: Access Windows Shared Folders</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-the-screen-recording-faceoff-bandicam-versus-camtasiaenas/"><u>[New] The Screen Recording Faceoff  Bandicam Versus Camtasia'enas</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-earnings-on-youtube-a-monthly-perspective/"><u>[New] In 2024, Earnings on YouTube  A Monthly Perspective?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-6-appsservices-to-trace-any-samsung-galaxy-s23-tactical-edition-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, Top 6 Apps/Services to Trace Any Samsung Galaxy S23 Tactical Edition Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-settings-for-drive-mappings-win11/"><u>Advanced Settings for Drive Mappings (Win11)</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-best-spy-watches-for-your-lava-blaze-pro-5g-drfone-by-drfone-virtual-android/"><u>Top 10 Best Spy Watches For your Lava Blaze Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-window-frame-blackout-restore-taskbar/"><u>Addressing Window Frame Blackout: Restore Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-windows-tools-for-mp4-and-mov-clips/"><u>Best Windows Tools for MP4 and MOV Clips</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-htc-vive-comfort-strategies-for-a-smoother-ride/"><u>2024 Approved  HTC Vive Comfort  Strategies for a Smoother Ride</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-free-software-picks-with-maximum-safety-standards/"><u>Best Free Software Picks with Maximum Safety Standards</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-unwanted-termination-messages-in-roblox-games/"><u>Avoiding Unwanted Termination Messages in Roblox Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplifying-the-importance-of-your-cursor-in-windows/"><u>Amplifying the Importance of Your Cursor in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-update-problem-windows-11-error-code-0x800f0922/"><u>Addressing Update Problem: Windows 11 Error Code 0X800f0922</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-accidental-scrolling-on-your-windows-device/"><u>Avoid Accidental Scrolling on Your Windows Device</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-integrating-moving-images-with-sound-a-comprehensive-guide-for-2024/"><u>New Integrating Moving Images with Sound A Comprehensive Guide for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-master-list-of-10-best-video-chat-programs-today/"><u>[New] Master List of 10 Best Video Chat Programs Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/back-to-basics-quick-fixes-in-13-essential-steps-for-systems/"><u>Back-to-Basics: Quick Fixes in 13 Essential Steps for Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-file-management-techniques-dragging-tabs-in-windows-11/"><u>Advanced File Management Techniques: Dragging Tabs in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assessing-the-role-and-safety-profile-of-aggregatorhostexe-in-windows/"><u>Assessing the Role and Safety Profile of AggregatorHost.exe in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/become-a-speech-converter-transcribe-talk-with-whisper-in-windows/"><u>Become a Speech Converter: Transcribe Talk with Whisper in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blending-windows-excellence-into-macos-benefits/"><u>Blending Windows Excellence Into macOS Benefits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beating-the-system-a-strategy-for-fixing-0x800700e9-in-xbox-game-passwindows-11/"><u>Beating the System: A Strategy for Fixing 0X800700E9 in Xbox Game Pass/Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boldly-hiding-extra-commands-within-window-contexts-win-10/"><u>Boldly Hiding Extra Commands Within Window Contexts (Win 10)</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-pro-vs-express-which-video-editing-software-reigns-supreme-in-2024/"><u>Updated Pro Vs. Express Which Video Editing Software Reigns Supreme, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-service-non-response-overcome-error-1053-quickly/"><u>Addressing Windows Service Non-Response: Overcome Error 1053 Quickly</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-perfect-virtual-screens-choosing-best-meet-backgrounds-for-2024/"><u>[New] Perfect Virtual Screens  Choosing Best Meet Backgrounds for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-nubia-phone-without-google-account-by-drfone-android/"><u>In 2024, How to Unlock Nubia Phone without Google Account?</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>