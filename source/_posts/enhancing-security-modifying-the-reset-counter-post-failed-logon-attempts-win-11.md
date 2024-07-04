---
title: "Enhancing Security: Modifying the Reset Counter Post Failed Logon Attempts, Win 11"
date: 2024-06-25T16:26:37.788Z
updated: 2024-06-26T16:26:37.788Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Enhancing Security: Modifying the Reset Counter Post Failed Logon Attempts, Win 11"
excerpt: "This Article Describes Enhancing Security: Modifying the Reset Counter Post Failed Logon Attempts, Win 11"
keywords: Secure Windows Login,Reset Counter Adjustment,Increase System Safety,Preventing Unauthorized Access,Enhanced Password Security,Lockout Policy Management,Windows 11 Security Update
thumbnail: https://thmb.techidaily.com/f5fbbf41453d9824bf6879798120e6de2082db27f668f4cb2a72d45c0fe37f64.jpg
---

## Enhancing Security: Modifying the Reset Counter Post Failed Logon Attempts, Win 11

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/revamp-your-workspace-windows-11-widget-techniques/"><u>Revamp Your Workspace: Windows 11 Widget Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-dism-error-0x800f082f-on-windows/"><u>Tackling DISM Error 0X800F082F on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-connectivity-issues-with-geforce-experience-software/"><u>Tackling Connectivity Issues with GeForce Experience Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-workflow-integrating-wordpad-shortcuts-into-context-menus-on-windows-11/"><u>Streamlining Workflow: Integrating WordPad Shortcuts Into Context Menus on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-system-monitoring-ram-gpu-and-cpu-status-guide/"><u>Efficient System Monitoring: RAM, GPU, and CPU Status Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-setting-up-windows-outlook-preview/"><u>Quick Guide: Setting Up Windows' Outlook Preview</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-fixes-for-flickering-win1011-screens/"><u>Efficient Fixes for Flickering WIN10/11 Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-ed-themed-windows-experience/"><u>Tailoring Ed-Themed Windows Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-absence-of-critical-dll-mfc71u-on-pc/"><u>Resolving Absence of Critical DLL: Mfc71u on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-1011-photography-setup/"><u>Streamlining Windows 10/11 Photography Setup</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-in-2024-prime-pickups-for-novice-gopro-owners/"><u>[Updated] In 2024, Prime Pickups for Novice GoPro Owners</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-dive-into-the-deep-end-of-facebook-meme-culture-for-2024/"><u>[Updated] Dive Into The Deep End of Facebook Meme Culture for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/crafting-seamless-virtual-gatherings-with-google-meet-for-2024/"><u>Crafting Seamless Virtual Gatherings with Google Meet for 2024</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/in-2024-what-is-the-best-voice-changer-for-whatsapp-discover-the-seven-7-best-voice-changers-for-whatsapp-here-in-this-post/"><u>In 2024, What Is the Best Voice Changer for WhatsApp? Discover the Seven (7) Best Voice Changers for WhatsApp Here in This Post</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-expert-recommended-6-online-apps-to-delete-background-perfectly/"><u>[New] Expert-Recommended 6 Online Apps to Delete Background Perfectly</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-mastering-the-art-of-sound-recording-via-vocaroo-strategies-and-replacements/"><u>In 2024, Mastering the Art of Sound Recording via Vocaroo Strategies and Replacements</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-pc-screen-to-motorola-g24-power-phones-drfone-by-drfone-android/"><u>How to Mirror PC Screen to Motorola G24 Power Phones? | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-iconic-stop-motion-animations-15-best-ever/"><u>[Updated] Iconic Stop-Motion Animations - #15 Best Ever</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-trending-vids-the-videoviral-phenomenon-for-2024/"><u>[New] Trending Vids  The #VideoViral Phenomenon for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-top-5-free-mpeg-video-joiner-tools-reviewed-for-2024/"><u>New Top 5 Free MPEG Video Joiner Tools Reviewed for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>