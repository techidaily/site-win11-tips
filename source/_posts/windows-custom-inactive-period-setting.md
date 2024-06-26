---
title: "Windows: Custom Inactive Period Setting"
date: 2024-06-25T16:26:22.151Z
updated: 2024-06-26T16:26:22.151Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows: Custom Inactive Period Setting"
excerpt: "This Article Describes Windows: Custom Inactive Period Setting"
keywords: Windows Power Control,Active Time Limit,Inactivity Timer Settings,Adjust Window Idle Time,Pause System Activation,Restart Prevention Mode,Customize Idle Time Windows
thumbnail: https://thmb.techidaily.com/e591b5728fa84d66a3323b91b4ed2e3f5b0efaa53a757d0b8f7bbc674ee0d976.jpg
---

## Windows: Custom Inactive Period Setting

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
2. Click the down arrow next to**Local Policies** in the left pane to expand it.
3. Click on**Security Options** to open it.
4. The Security Options will open up in the right pane. Now scroll down to the policy named**Interactive logon: Machine inactivity limit** and double-click on it to open its properties.  
![Machine Inactivity Limit Selected in Security Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/select-machine-inactivity-limit-in-security-options.jpg)
5. Under the section**Machine will be locked after** , enter the time in seconds after which you want your PC to get locked automatically. This time is the time of machine inactivity or the time when your PC is idle. You can enter the time between**0** to**599940** seconds. For this tutorial, we'll enter**300 seconds** which is five minutes. Now click on**Apply** and then**OK** .
6. Finally, close the Local Security Policy window and restart your computer for the change to take effect.

 Now, when you use your PC, you will experience that your PC will lock itself after your custom timer expires. And if someone tries to unlock your PC while you're gone, it'll ask them for your password, which should keep them at bay until you get back.

 If you ever want to reverse this action and not have your PC lock automatically, just open the**Interactive logon: Machine inactivity limit** policy in**Local Security Policy** . Then just change the time or seconds to**0** —this is the default setting and will not lock your PC automatically.

## 2\. How to Lock Your Windows PC After a Specific Amount of Inactivity via the Registry Editor

 You can tweak settings in the Registry Editor to configure your PC to lock automatically after a set time. And you can do this in Windows Home and all the other Windows editions.

 However, you must be careful while making changes in the registry and should only make the changes as detailed below and not change anything else. It'd be a good idea to create a restore point in Windows before you change your registry settings. If something goes wrong, you can revert your PC to its last working state.

 Now let's go ahead and explore how to lock your PC automatically via the Registry Editor.

1. Type**Registry Editor** in**Windows Search** and select**Registry Editor** under**Best match** . Or use one of the many [ways to open the Registry Editor in Windows 11](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Click on**Yes** on the UAC prompt.
3. In the left pane, use the following path to reach the**System** registry key: **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System**  
![Navigate to System Key in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/navigate-to-system-key-in-registry-editor.jpg)
4. Click on the**System** key in the left pane and its components will open up in the right pane. Now scroll down to get to the**InactivityTimeoutSecs** DWORD.  
![Scroll to InactivityTimeoutSecs in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/scroll-to-inactivitytimeoutsecs.jpg)
5. Double-click on the**InactivityTimeoutSecs** DWORD to modify its value. Select**Decimal** under**Base** , and under**Value data** , enter a number between**0** to**599940** —this is the time in seconds after which your PC will get locked automatically. Like in the Local Security Policy method, we'll give it a time of**300 seconds** or five minutes. Now tap on**OK** .
6. In case you do not find the**InactivityTimeoutSecs** DWORD in your registry, you can create it. Right-click on the**System** key folder in the left pane or right-click on a space in the right pane of the**System** key. Select**New** , then select**DWORD (32-bit) Value** .  
![Create InactivityTimeoutSecs DWORD in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/create-inactivitytimeoutsecs-dword.jpg)  
 A new value will be created in the right pane. Name it**InactivityTimeoutSecs** . Then press**Enter** .
7. Now double-click on**InactivityTimeoutSecs** DWORD, and enter the time after which you want your PC to get locked.
8. Finally, close the Registry Editor and restart your PC to apply the changes.

 Now your PC will get locked if you're not using it or are away from it after the time you have set in the Registry Editor. If you're on a Windows 11 machine, you can also [explore a few other ways to lock your PC](https://www.makeuseof.com/windows-11-ways-to-lock/) .

 To stop your PC from getting locked automatically, modify the**InactivityTimeoutSecs** DWORD value in the Registry Editor by changing the time to**0** seconds.

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
<li><a href="https://win11-tips.techidaily.com/breaking-down-windows-character-map-hurdles-a-step-by-step-solution/"><u>Breaking Down Windows Character Map Hurdles: A Step-by-Step Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-disk-errors-with-advanced-windows-tools/"><u>Fixing Disk Errors with Advanced Windows Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-unanticipated-error-messages-in-wins-secure/"><u>Tackling Unanticipated Error Messages in WINS Secure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recovering-d3dx939dll-error-on-win11/"><u>Recovering D3DX9_39.dll Error on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-advice-on-resolving-windows-error-code-0xc0000001/"><u>Expert Advice on Resolving Windows Error Code 0XC0000001</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-resetting-graphics-drivers-on-latest-oses/"><u>Quick Guide to Resetting Graphics Drivers on Latest OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turn-off-windows-upgrade-notifications/"><u>Turn Off Windows Upgrade Notifications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rejuvenate-outdated-systems-why-not-windows/"><u>Rejuvenate Outdated Systems: Why Not Windows?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/confronting-memory-write-issues-in-windows/"><u>Confronting 'Memory Write' Issues in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/address-the-empty-spaces-for-windows-11-image-tiles/"><u>Address the Empty Spaces for Windows 11 Image Tiles</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-integrating-fb-live-on-roku-step-by-step-guide-for-2024/"><u>[New] Integrating FB Live on Roku  Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-can-we-unlock-our-xiaomi-civi-3-disney-100th-anniversary-edition-phone-screen-by-drfone-android/"><u>In 2024, How Can We Unlock Our Xiaomi Civi 3 Disney 100th Anniversary Edition Phone Screen?</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/crafting-unique-videos-master-tiktoks-sound-personalization/"><u>Crafting Unique Videos  Master TikTok's Sound Personalization</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/streamline-your-workflow-with-the-top-5-pc-screen-grabbers/"><u>Streamline Your Workflow with the Top 5 Pc Screen Grabbers</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-unlock-your-potential-best-free-mac-screen-recorder-software-reviewed/"><u>[New] In 2024, Unlock Your Potential  Best Free Mac Screen Recorder Software Reviewed</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/best-mobile-video-editing-apps-for-iphone-and-android/"><u>Best Mobile Video Editing Apps for iPhone And Android</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-from-still-to-stunning-how-to-achieve-the-ken-burns-effect/"><u>New 2024 Approved From Still to Stunning How to Achieve the Ken Burns Effect</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-gaming-evolved-streaming-xbox-content-on-facebook/"><u>In 2024, Gaming Evolved  Streaming Xbox Content on Facebook</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-the-professionals-method-for-removing-unwanted-sounds-from-media-projects-using-premiere-pro-for-2024/"><u>New The Professionals Method for Removing Unwanted Sounds From Media Projects Using Premiere Pro for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/tinysnap-capture-assessment-with-variants-for-2024/"><u>TinySnap Capture Assessment with Variants for 2024</u></a></li>
</ul></div>
