---
title: How to Prolong the Wait Before Closing Windows 10 When Active Tasks Are Running
date: 2024-09-28T18:06:47.571Z
updated: 2024-10-03T22:22:44.018Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Prolong the Wait Before Closing Windows 10 When Active Tasks Are Running
excerpt: This Article Describes How to Prolong the Wait Before Closing Windows 10 When Active Tasks Are Running
keywords: Extend Win10 Shutdown Delay,Prolong Windows Shutdown Start,Delay Windows Close During Use,Manage Win10 Closure Time,Postpone Win10 Exit Process,Control Win10 Lockout Timing,Extend Active Tasks Before Win10 Shutdown
thumbnail: https://thmb.techidaily.com/1b264feb60401b06f1b5b9d369aaa689e44f7f3921972fa9eb3d747a1df53b5a.jpg
---

## How to Prolong the Wait Before Closing Windows 10 When Active Tasks Are Running

 Sometimes, when shutting down, restarting, or logging off from your Windows 10 machine, you may get an error message that interrupts or even cancels the operation. To prevent this from happening, you can make Windows wait longer when logging off.

 Making the system give it a little while longer could actually save you time. Here’s what you should do, should you be faced with this situation.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Does Windows Show an Error Message While Logging Off?

 It may be that you have quite a few tasks running simultaneously, each possibly with unsaved data. If this is the case, each task or application attempts to save data before Windows logs off. This could be one reason for the error message. As a remedy, you may want to extend the time allotted for signing off to allow all tasks to finish what they are doing.

 Alternatively, it could just be a problem task. This may be true if it is a recurring issue. In this case, and if you’re sure none of the applications you are using will lose data, you could make Windows force a sign-off more quickly.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049382/7443" target="_top" id="2049382">
  <img src="//a.impactradius-go.com/display-ad/7443-2049382" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049382/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## What Should You Try First?

 The method described here basically forces Windows to wait longer while shutting down or logging off. However, if you have a misbehaving program interfering with Windows log-off, it could be something to look into. There are fixes you should try first if there is an[app preventing Windows from shutting down or logging off](https://www.makeuseof.com/this-app-preventing-windows-shutting-down-restarting-signing-out-error/) .

 If none of those options works, you can adjust how long Windows waits before logging off, which gives any running or buggy apps more time to sort themselves out.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997643/19272" target="_top" id="1997643">
  <img src="//a.impactradius-go.com/display-ad/19272-1997643" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997643/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Make Windows Wait Longer When Logging Off

 There are two processes that you can turn to. With the first, WaitToKillAppTimeout, Windows grants apps 20 seconds to save data and close. If apps don’t respond, Windows considers them “hung.” HungAppTimeout, the second, tells Windows how many seconds to wait before considering apps to be hung and offering a force-close solution.

 Changing both these values involves[editing the registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) , so be wary, and[make a backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) copy before you tinker with it.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014853/22899" target="_top" id="2014853">
  <img src="//a.impactradius-go.com/display-ad/22899-2014853" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014853/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 1A. How to Set WaitToKillAppTimeout for Just Your User Account

 Do this to change how long Windows waits for apps when logging off just from your user account.

1. Open the Registry editor. See[how to open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-open-registry-editor/) for more information.
2. Navigate to the following folder in the registry:  
`HKEY_CURRENT_USER\Control Panel\Desktop`
3. In the pane on the right, look for the string named**WaitToKillAppTimeout** .
4. If you don’t see it, you’ll need to create it by right-clicking in any empty space in the pane and selecting**New > String Value** . Rename it**WaitToKillAppTimeout** .
5. Double-click this string to edit its value, which is in milliseconds. (1000 milliseconds equals one second.) By default, the value data is set to 20,000 (or 20 seconds).
6. Increase this value to make Windows wait on running apps longer before shutting down or logging off. (Decreasing its value will log you off more quickly.)

### 1B. How to Change WaitToKillAppTimeout for All Users

This will apply altered log-off rules to all users on the PC.

1. Open the Registry editor.
2. Navigate to the following folder in the registry:  
`HKEY_USERS\.DEFAULT\Control Panel\Desktop`
3. Follow steps three to six from method 1A to change how long Windows waits for apps to finish closing properly when logging off for all users.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136621/26400" target="_top" id="2136621">
  <img src="//a.impactradius-go.com/display-ad/26400-2136621" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136621/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2A. How to Set HungAppTimeout for Just Your User Account

 Doing this will change how long Windows waits for apps that it considers hung. This is just for your user account.

1. Open the Registry Editor.
2. Navigate to the following folder in the Registry:  
`HKEY_CURRENT_USER\Control Panel\Desktop`
3. In the pane on the right, look for the string named**HungAppTimeout** .
4. If the string doesn’t exist, create it by right-clicking in any empty space in the pane and choosing**New > String Value** . Rename it**HungAppTimeout** .
5. Double-click this string to edit its value – again, in milliseconds. (1000 milliseconds equals 1 second.) By default, the value data is set to 5000.
6. Increase this value to make Windows afford more time to hung apps and wait longer when shutting down or logging off. (Reduce this value to log off more quickly.)

### 2B. How to Change HungAppTimeout for All Users

This will allow you to change the default value for all users.

1. Open the Registry Editor.
2. Navigate to the following folder in the registry:  
`HKEY_USERS\.DEFAULT\Control Panel\Desktop`
3. Follow steps 3 to 6 from method 2A to change how long Windows waits when logging off for all users.

## Give Apps More Time to Close When Logging Off

 If apps keep interrupting Windows when you shut down or log off, it would be wise to give them a little more time to finish up and close properly. That way, they won’t interrupt the log-off process and have you intervene manually.

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
<li><a href="https://visual-screen-recording.techidaily.com/new-top-free-video-calls-on-pcmac-os-for-easy-online-meetings-for-2024/"><u>[New] Top Free Video Calls on PC/Mac OS for Easy Online Meetings for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-professional-video-editors-showdown-filmora-versus-democracy-creator/"><u>[Updated] 2024 Approved Professional Video Editors Showdown Filmora Versus Democracy Creator</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-making-your-igtv-more-inclusive-with-subtitles/"><u>[Updated] Making Your IGTV More Inclusive with Subtitles</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-sketchsphere-complete-evaluation-24-edition/"><u>[Updated] SketchSphere Complete Evaluation '24 Edition</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-tecno-pova-5-pro-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Tecno Pova 5 Pro</u></a></li>
<li><a href="https://tech-haven.techidaily.com/customize-ai-like-never-before-discover-how-to-create-personalized-gpt-models-via-chatgpts-latest-innovation/"><u>Customize AI Like Never Before – Discover How to Create Personalized GPT Models via ChatGPT's Latest Innovation</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-any-oppo-reno-10-5g-phone-password-using-emergency-call-by-drfone-android/"><u>How To Unlock Any Oppo Reno 10 5G Phone Password Using Emergency Call</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-simulate-gps-movement-in-ar-games-on-motorola-g54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Simulate GPS Movement in AR games On Motorola G54 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jumpstart-creativity-opening-ms-paint-on-win11/"><u>Jumpstart Creativity: Opening MS Paint on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-password-required-avoidance-on-windows-11/"><u>Mastering the Art of 'Password Required' Avoidance on Windows 11</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-make-your-videos-pop-top-text-animation-apps-for-android-and-ios/"><u>New In 2024, Make Your Videos Pop Top Text Animation Apps for Android and iOS</u></a></li>
<li><a href="https://extra-information.techidaily.com/paving-pathways-in-pixels-the-leading-vr-treadmills-reviewed/"><u>Paving Pathways in Pixels The Leading VR Treadmills Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefining-reset-count-for-lockouts-after-logon-errors-in-windows-11-pro/"><u>Redefining Reset Count for Lockouts After Logon Errors in Windows 11 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refreshing-windows-paperwork-handler/"><u>Refreshing Windows Paperwork Handler</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-handling-missing-powershell-on-windows/"><u>Strategies for Handling 'Missing PowerShell' On Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turning-your-spoken-language-into-written-communication-using-whisper-on-windows/"><u>Turning Your Spoken Language Into Written Communication Using Whisper on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncover-the-hidden-issues-causing-login-blackouts/"><u>Uncover the Hidden Issues Causing Login Blackouts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfreezing-steam-directory-access-fixes-for-windows-11/"><u>Unfreezing Steam Directory Access: Fixes for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-taskbars-hidden-features/"><u>Unveiling Windows Taskbar's Hidden Features</u></a></li>
</ul></div>

