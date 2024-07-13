---
title: "Enhancing Security: Modifying the Reset Counter Post Failed Logon Attempts, Win 11"
date: 2024-07-12T16:53:11.563Z
updated: 2024-07-13T16:53:11.563Z
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/correcting-invalid-device-label-in-windows-os/"><u>Correcting 'Invalid Device' Label in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-lightweight-browser-ram-usage-with-comparative-tests/"><u>Exploring Lightweight Browser RAM Usage with Comparative Tests</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-xiaomi-redmi-note-12-5g-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Xiaomi Redmi Note 12 5G in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/administrative-controls-unveiled-windows-11-and-home-edition/"><u>Administrative Controls Unveiled: Windows 11 & Home Edition</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-our-favorite-free-video-splitters-a-comprehensive-review-for-2024/"><u>New Our Favorite Free Video Splitters A Comprehensive Review for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-streamlining-image-editing-luts-in-adobe-photoshop-cc/"><u>In 2024, Streamlining Image Editing  LUTs in Adobe PhotoShop CC</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-ultimate-strategy-for-computer-based-tv-broadcasting/"><u>[New] In 2024, Ultimate Strategy for Computer-Based TV Broadcasting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rescue-your-vscode-session-w11/"><u>How to Rescue Your VSCode Session W11</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-the-complete-screenrec-manual-for-laptops/"><u>[Updated] In 2024, The Complete ScreenRec Manual for Laptops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-method-integrating-airpods-with-windows/"><u>Efficient Method: Integrating AirPods with Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-signature-verification-issue-in-winoses/"><u>Eradicating Signature Verification Issue in WinOSes</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-2024-approved-innovative-audio-editing-implementing-and-designing-keyframes-in-adobe-premiere-pro-mac/"><u>Updated 2024 Approved Innovative Audio Editing Implementing and Designing Keyframes in Adobe Premiere Pro (Mac)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaching-windows-login-restrictions-a-quick-guide/"><u>Breaching Windows Login Restrictions: A Quick Guide</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/fluency-in-english-for-non-native-speakers/"><u>Fluency in English for Non-Native Speakers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-solve-the-disconnected-from-nvidia-experience-problem-in-win-11/"><u>How to Solve the 'Disconnected From NVIDIA Experience' Problem in Win 11</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-maximizing-earning-potential-with-strategic-facebook-video-ads/"><u>[Updated] Maximizing Earning Potential with Strategic Facebook Video Ads</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/in-2024-rotate-your-avi-videos-for-free-top-picks-for-every-platform/"><u>In 2024, Rotate Your AVI Videos for Free Top Picks for Every Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-a-global-keyboard-downloading-windows-fonts/"><u>Crafting a Global Keyboard: Downloading Windows Fonts</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-comprehensively-understanding-ios-visual-record-function/"><u>2024 Approved  Comprehensively Understanding IO’s Visual Record Function</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-essential-tips-for-combining-srt-with-mp4-video-content/"><u>2024 Approved  Essential Tips for Combining SRT with MP4 Video Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-reinstate-your-devices-access-post-error-22/"><u>Guide to Reinstate Your Device's Access Post Error 22</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-mend-flickering-screens-in-windows-11/"><u>How to Mend Flickering Screens in Windows 11</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-2024-approved-enhance-your-tiktok-viewing-experience/"><u>[New] 2024 Approved  Enhance Your TikTok Viewing Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-teamsters-shutdown-on-windows-11-10-systems/"><u>Avoiding Teamsters Shutdown on Windows 11, 10 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-productivity-easy-drive-mapping-for-windows-11-users/"><u>Enhancing Productivity: Easy Drive Mapping for Windows 11 Users</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-maximizing-engagement-in-your-tiktok-unpacking-sessions/"><u>In 2024, Maximizing Engagement in Your TikTok Unpacking Sessions</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-the-ultimate-guide-to-discovering-whatsapp-hacks/"><u>In 2024, The Ultimate Guide to Discovering WhatsApp Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-stuttering-challenges-enhancing-warhammer-40k-experience/"><u>Conquer Stuttering Challenges: Enhancing Warhammer 40K Experience</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-cyber-cracked-joke-creator/"><u>[Updated] 2024 Approved  Cyber Cracked Joke Creator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/desktop-configuration-mastery-embedding-this-pc-symbols/"><u>Desktop Configuration Mastery: Embedding 'This PC' Symbols</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-blueprints-for-breaking-ground-in-edu-video-production-on-youtube-channels-for-2024/"><u>[New] Blueprints for Breaking Ground in Edu-Video Production on YouTube Channels for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-new-age-smartphone-a-review-of-huawei-p10s-innovations/"><u>The New Age Smartphone? A Review of Huawei P10's Innovations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-improving-win11-point-accuracy-and-size/"><u>Guide to Improving Win11' Point Accuracy & Size</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-act-comparing-two-essential-windows-metrics/"><u>Balancing Act: Comparing Two Essential Windows Metrics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cpu-gen-identification-using-eight-proven-windows-methods/"><u>CPU Gen Identification Using Eight Proven Windows Methods</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-top-techniques-for-stunning-android-time-lapse-captures/"><u>[New] Top Techniques for Stunning Android Time-Lapse Captures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-resolve-defenders-0x80004004-error/"><u>Guide to Resolve Defender's 0X80004004 Error</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-transform-your-tone-with-simple-steps-using-audacity/"><u>Updated Transform Your Tone with Simple Steps Using Audacity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-self-scrolled-windows-with-ease-and-precision/"><u>Fix Self-Scrolled Windows with Ease and Precision</u></a></li>
</ul></div>
