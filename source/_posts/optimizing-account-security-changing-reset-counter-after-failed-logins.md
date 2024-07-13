---
title: "Optimizing Account Security: Changing Reset Counter After Failed Logins"
date: 2024-07-12T16:44:11.666Z
updated: 2024-07-13T16:44:11.666Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Optimizing Account Security: Changing Reset Counter After Failed Logins"
excerpt: "This Article Describes Optimizing Account Security: Changing Reset Counter After Failed Logins"
keywords: Secure Passwords Update,Prevent Reset Abuse,Improve Login Safety,Strengthen Access Controls,Enhance Account Protection,Reduce Failed Attempt Risks,Optimize Security Measures
thumbnail: https://thmb.techidaily.com/6a82b15c3b5908dade20c57e5528354889aa2d43fb699583edd3d2db4662000a.jpg
---

## Optimizing Account Security: Changing Reset Counter After Failed Logins

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
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-avoiding-social-media-isolation-tweet-on-fb/"><u>In 2024, Avoiding Social Media Isolation  Tweet on FB</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-file-extraction-failure-fix-for-error-1152-in-win/"><u>Addressing File Extraction Failure: Fix for Error 1152 in Win</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-improve-video-loading-times-in-instagram-for-2024/"><u>[New] Improve Video Loading Times in Instagram for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-ways-to-open-the-display-settings-in-windows-11/"><u>10 Ways to Open the Display Settings in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719255690388-pro-tips-to-improve-your-snip-and-sketch-screenshot-experience/"><u>Pro Tips to Improve Your Snip & Sketch Screenshot Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-essential-solutions-for-troubleshooting-missing-wireless-connections-in-windows-10/"><u>10 Essential Solutions for Troubleshooting Missing Wireless Connections in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-remove-a-saved-wi-fi-network-from-windows-11/"><u>4 Ways to Remove a Saved Wi-Fi Network From Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719225198037-epic-launcher-removal-woes-in-windows-11-fix-now/"><u>Epic Launcher Removal Woes in Windows 11: Fix Now</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-basics-of-weaving-a-narrative-thread/"><u>2024 Approved  Basics of Weaving a Narrative Thread</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-key-steps-for-efficient-access-to-windows-connections-tool/"><u>10 Key Steps for Efficient Access to Window's Connections Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/13-tips-to-fix-windows-system-restore/"><u>13 Tips to Fix Windows System Restore</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-gaining-entry-into-windows-11s-application-repository/"><u>A Guide to Gaining Entry Into Windows 11'S Application Repository</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-speedy-techniques-for-windows-control-panel/"><u>11 Speedy Techniques for Window's Control Panel</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-the-easy-way-to-remove-an-apple-id-from-your-macbook-for-your-iphone-12-pro-by-drfone-ios/"><u>In 2024, The Easy Way to Remove an Apple ID from Your MacBook For your iPhone 12 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719228801666-streamline-help-process-for-windows-snags/"><u>Streamline Help Process for Windows Snags</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-do-vivo-y55s-5g-2023-screen-sharing-drfone-by-drfone-android/"><u>How To Do Vivo Y55s 5G (2023) Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-themed-settings-for-education-on-windows-11/"><u>Activating Themed Settings for Education on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-new-windows-11-perks-after-version-update/"><u>10 New Windows 11 Perks After Version Update</u></a></li>
<li><a href="https://screen-capture.techidaily.com/the-beginners-guide-to-pioneering-minecraft-recordings-on-mac-for-2024/"><u>The Beginner's Guide to Pioneering Minecraft Recordings on Mac for 2024</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-fake-gps-without-root-on-motorola-moto-e13-drfone-by-drfone-virtual-android/"><u>3 Ways to Fake GPS Without Root On Motorola Moto E13 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-incompatibility-with-windows-11-at-home/"><u>Addressing Incompatibility with Windows 11 at Home</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-app-launch-with-windows-11/"><u>Accelerate Your App Launch with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-fix-strategies-for-your-windows-resolution-dilemmas/"><u>10 Fix Strategies for Your Windows Resolution Dilemmas</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/how-to-video-chatcall-on-snapchat-with-3-steps-for-2024/"><u>How to Video Chat/Call on Snapchat with 3 Steps for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-recently-used-windows-with-ease/"><u>Accessing Recently Used Windows with Ease</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-creating-auditory-immersion-with-canvas-soundscape-tools/"><u>[New] Creating Auditory Immersion with Canva's Soundscape Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-internal-error-during-win10-remote-access/"><u>Addressing Internal Error During Win10 Remote Access</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-maximizing-impact-the-best-instagram-hashtag-list/"><u>[New] Maximizing Impact  The Best Instagram Hashtag List</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/steps-to-uncover-youtubes-central-editing-nexus/"><u>Steps to Uncover YouTube’s Central Editing Nexus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719244514852-enhancing-your-windows-snipping-experience-with-proven-fixes/"><u>Enhancing Your Windows Snipping Experience with Proven Fixes</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-remove-screen-lock-pin-on-vivo-y56-5g-like-a-pro-5-easy-ways-by-drfone-android/"><u>In 2024, How To Remove Screen Lock PIN On Vivo Y56 5G Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activate-advanced-protection-features-for-win-11s-edge-using-defender-aguard/"><u>Activate Advanced Protection Features for Win 11'S Edge Using Defender Aguard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719231278472-how-to-correctly-use-win-plus-p-printer-command-in-windows/"><u>How to Correctly Use Win + P Printer Command in Windows.</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/integrating-melodies-enhance-videos-using-filmoras-soundtrack-tools-for-2024/"><u>Integrating Melodies Enhance Videos Using Filmoras Soundtrack Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-system-id-inaccuracy-in-windows-11/"><u>Addressing System ID Inaccuracy in Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/4-ways-to-transfer-music-from-asus-rog-phone-7-ultimate-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>4 Ways to Transfer Music from Asus ROG Phone 7 Ultimate to iPhone | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-solutions-for-a-fully-operational-windows-search-bar/"><u>11 Solutions for a Fully Operational Windows Search Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-ways-to-open-the-control-panel-on-windows/"><u>11 Ways to Open the Control Panel on Windows</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-instagram-aesthetics-unleashed-leading-enhancers-for-2024/"><u>[Updated] Instagram Aesthetics Unleashed  Leading Enhancers for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-discover-easy-ad-free-screen-recording-apps/"><u>[Updated] Discover Easy, Ad-Free Screen Recording Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-simple-steps-to-fix-server-not-found-error-on-windows-pcs-in-apex-legends-(156-chars/"><u>9 Simple Steps to Fix 'Server Not Found' Error on Windows PCs in Apex Legends (<156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719239834039-start-menu-no-more-unwanted-advertisements/"><u>Start Menu, No More Unwanted Advertisements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-ways-to-fix-a-cursor-when-it-moves-on-its-own-in-windows-11/"><u>10 Ways to Fix a Cursor When It Moves On Its Own in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719355808573-how-to-reactivate-and-rescue-non-responsive-printer-feature-via-win-plus-p-in-windows/"><u>How to Reactivate and Rescue Non-Responsive Printer Feature via Win + P in Windows.</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-actionable-solutions-for-converting-xml-ssa-ttml-etc-to-srt/"><u>2024 Approved  Actionable Solutions for Converting XML, SSA, TTML, Etc., To SRT</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-xiaomi-unveils-next-level-screen-recording-for-photo-lovers/"><u>[New] Xiaomi Unveils Next-Level Screen Recording for Photo Lovers</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-2-ways-to-transfer-text-messages-from-samsung-galaxy-xcover-6-pro-tactical-edition-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 2 Ways to Transfer Text Messages from Samsung Galaxy XCover 6 Pro Tactical Edition to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719204304616-gpt4all-free-chatbot-clones-at-home-for-windows/"><u>GPT4All: Free ChatBot Clones at Home for Windows.</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-watch-hulu-outside-us-on-infinix-hot-40-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Watch Hulu Outside US On Infinix Hot 40 Pro | Dr.fone</u></a></li>
</ul></div>
