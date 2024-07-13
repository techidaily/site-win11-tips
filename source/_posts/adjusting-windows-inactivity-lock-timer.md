---
title: Adjusting Windows Inactivity Lock Timer
date: 2024-07-12T16:44:36.918Z
updated: 2024-07-13T16:44:36.918Z
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
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-retrieve-lost-photos-from-vivo-y28-5g-by-fonelab-android-recover-photos/"><u>Best Android Data Recovery - Retrieve Lost Photos from Vivo Y28 5G.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-indicators-when-a-pc-needs-a-clean-slate/"><u>7 Indicators: When a PC Needs a Clean Slate</u></a></li>
<li><a href="https://extra-hints.techidaily.com/emoji-enhancement-techniques-converting-graphics-into-chat-app-stickers/"><u>Emoji Enhancement Techniques  Converting Graphics Into Chat App Stickers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-alternative-techniques-for-temporarily-haltin-windows-11-safety/"><u>5 Alternative Techniques for Temporarily Haltin Windows 11 Safety</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-install-net-now-demands-from-apps/"><u>Addressing Install .NET Now Demands From Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-to-repairing-onedrive-on-windows-11/"><u>A Step-by-Step Approach to Repairing OneDrive on Windows 11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/unlocking-creative-potential-in-asmr-content-advanced-techniques/"><u>Unlocking Creative Potential in ASMR Content – Advanced Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activate-data-safety-with-controlled-folder-access-feature/"><u>Activate Data Safety with Controlled Folder Access Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-altering-lockout-frequency-in-windows-11-successor/"><u>A Step-by-Step Guide to Altering Lockout Frequency in Windows 11 Successor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-remedies-to-clear-windows-setup-stuck-on-validation-error/"><u>9 Remedies to Clear Windows Setup Stuck on Validation Error</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-unleash-creativity-capturing-sims-4-adventures/"><u>2024 Approved  Unleash Creativity  Capturing Sims 4 Adventures</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-screen-free-serenity-top-10-indoor-games-for-non-networked-play-android/"><u>[Updated] Screen-Free Serenity  Top 10 Indoor Games for Non-Networked Play (Android)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-compreenas-for-conquering-windows-10-bsod-woes/"><u>A Compreenas for Conquering Windows 10 BSOD Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-restart-and-shutdown-disruptions-from-windows-faulty-apps/"><u>Addressing Restart and Shutdown Disruptions From Windows Faulty Apps</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-nubia-red-magic-8s-pro-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>In 2024, How to Unlock Nubia Red Magic 8S Pro Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-snapchat-recordings-techniques-for-your-phone/"><u>2024 Approved  Snapchat Recordings  Techniques for Your Phone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-perfecting-your-rl-game-captures/"><u>[New] Perfecting Your RL Game Captures</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-unlock-icloud-lock-from-your-apple-iphone-6s-plus-and-ipad-by-drfone-ios/"><u>How to Unlock iCloud lock from your Apple iPhone 6s Plus and iPad?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-deciphering-windows-11s-registry/"><u>A Comprehensive Guide to Deciphering Windows 11'S Registry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-preparing-your-pc-before-win-upgrade/"><u>A Step-by-Step Guide to Preparing Your PC Before Win Upgrade</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-step-by-step-guide-to-tiktok-video-creation-using-filmora-and-camera-skills/"><u>[New] 2024 Approved  Step-by-Step Guide to TikTok Video Creation Using Filmora and Camera Skills</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-insufficient-ram-in-windows-vm-hosting-platforms/"><u>Addressing Insufficient RAM in Windows VM Hosting Platforms</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-become-a-digital-native-in-the-metaverse-now/"><u>In 2024, Become a Digital Native in the Metaverse Now</u></a></li>
<li><a href="https://discord-videos.techidaily.com/closing-out-of-a-discord-channel-best-practices-for-2024/"><u>Closing Out of a Discord Channel  Best Practices for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapting-fn-key-operations-in-the-latest-windows-os/"><u>Adapting FN Key Operations in the Latest Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-ways-to-make-the-windows-terminal-your-default-terminal-app/"><u>3 Ways to Make the Windows Terminal Your Default Terminal App</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-streamline-access-top-strategies-for-recent-fb-video-tracks/"><u>[Updated] In 2024, Streamline Access  Top Strategies for Recent Fb Video Tracks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-getting-jdk-rolled-out-in-windows-11-dev-environment/"><u>A Guide to Getting JDK Rolled Out in Windows 11 Dev Environment</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-animation-makers-for-everyone-top-10-tools-for-beginners-to-experts-for-2024/"><u>New Animation Makers for Everyone Top 10 Tools for Beginners to Experts for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-15-innovative-recording-tools-for-gamers-on-both-plattforms/"><u>[New] In 2024, 15 Innovative Recording Tools for Gamers on Both Plattforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-digital-imagery-to-your-desktop/"><u>Adding Digital Imagery to Your Desktop</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/downloading-samfw-frp-tool-30-for-nokia-by-drfone-android/"><u>Downloading SamFw FRP Tool 3.0 for Nokia</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-way-to-fix-the-virus-and-threat-protection-engine-unavailable-issue-in-windows-defender/"><u>5 Way to Fix the Virus & Threat Protection Engine Unavailable Issue in Windows Defender</u></a></li>
<li><a href="https://article-helps.techidaily.com/top-5-methods-to-record-high-quality-audio-on-windows/"><u>Top 5 Methods to Record High-Quality Audio on Windows</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-premium-tvs-for-ps5-and-xbox-series-x-gamers-dreams/"><u>[Updated] In 2024, Premium TVs for PS5 & Xbox Series X Gamers' Dreams</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/a-deep-dive-into-recmasters-video-capturing-technology-for-2024/"><u>A Deep Dive Into Recmaster's Video Capturing Technology for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-key-adjustments-to-reestablish-wi-fi-connectivity-in-windows-10-systems/"><u>5 Key Adjustments to Reestablish Wi-Fi Connectivity in Windows 10 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-crucial-strategies-to-salvage-a-frozen-windows-service-panel/"><u>7 Crucial Strategies to Salvage a Frozen Windows Service Panel</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/forgot-iphone-13-pro-max-backup-password-heres-what-to-do-by-drfone-ios/"><u>Forgot iPhone 13 Pro Max Backup Password? Heres What to Do</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-any-xiaomi-redmi-note-12-pro-5g-phone-password-using-emergency-call-by-drfone-android/"><u>How To Unlock Any Xiaomi Redmi Note 12 Pro 5G Phone Password Using Emergency Call</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-low-memory-alerts-for-vmware-hosts/"><u>Addressing Low Memory Alerts for VmWare Hosts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapting-ancient-windows-to-seniors-needs/"><u>Adapting Ancient Windows to Seniors' Needs</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-seamless-streaming-screen-record-and-upload-from-macpc/"><u>[New] 2024 Approved  Seamless Streaming  Screen Record & Upload From Mac/PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-slowness-in-windows-discord-interface/"><u>Addressing Slowness in Windows Discord Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-pcs-boot-up-with-these-3-ways-in-windows-11/"><u>Accelerate Your PC's Boot-Up with These 3 Ways in Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-airplane-mode-turn-off-gps-location-on-samsung-galaxy-f15-5g-drfone-by-drfone-virtual-android/"><u>Does Airplane Mode Turn off GPS Location On Samsung Galaxy F15 5G? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-icloud-activation-lock-on-mac-for-apple-iphone-14-plus-by-drfone-ios/"><u>In 2024, How To Bypass iCloud Activation Lock on Mac For Apple iPhone 14 Plus?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-secrets-the-fastest-ways-to-uncover-windows-11s-credential-manager/"><u>Accessing Secrets: The Fastest Ways to Uncover Windows 11'S Credential Manager</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-tiktok-and-snapchat-face-off-a-users-perspective-guide/"><u>2024 Approved  TikTok & Snapchat Face-Off  A User's Perspective Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-rotate-images-on-a-windows-11-pc/"><u>6 Ways to Rotate Images on a Windows 11 PC</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-rotate-your-videos-for-free-top-online-video-flip-tools/"><u>Updated 2024 Approved Rotate Your Videos for Free Top Online Video Flip Tools</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-direct-viewing-verdict-obs-vs-shadowcast-for-2024/"><u>[Updated] Direct Viewing Verdict  OBS vs ShadowCast for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-a-spotless-system-restart-in-windows-11/"><u>Achieving a Spotless System Restart in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-iomap64-bsod-with-easy-steps-for-windows-users/"><u>Addressing IOMap64 BSoD with Easy Steps for Windows Users</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-virtual-clarity-streamlining-backgrounds-for-smooth-screenshots/"><u>[New] 2024 Approved  Virtual Clarity  Streamlining Backgrounds for Smooth Screenshots</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-system-blocked-issue-on-your-windows-machine/"><u>Addressing the System Blocked Issue on Your Windows Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-understanding-and-using-components-settings/"><u>A Guide to Understanding and Using Components Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-guide-to-mastering-windows-11s-search-functionality/"><u>A Quick Guide to Mastering Windows 11'S Search Functionality</u></a></li>
<li><a href="https://extra-information.techidaily.com/close-up-clarity-mastering-teammate-focus-for-2024/"><u>Close-Up Clarity  Mastering Teammate Focus for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719327147890-secrets-to-perfect-full-screen-snipping-with-windows-toolkit/"><u>Secrets to Perfect Full-Screen Snipping with Windows' Toolkit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-strategies-for-enabling-uninstalled-features-in-win10win11/"><u>7 Strategies for Enabling Uninstalled Features in Win10/Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719359374237-combat-window-settings-malfunctions-now/"><u>Combat Window Settings Malfunctions Now!</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-fix-icloud-lock-on-your-iphone-6-plus-and-ipad-by-drfone-ios/"><u>How to fix iCloud lock on your iPhone 6 Plus and iPad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-tactics-to-prevent-c-drive-from-running-dry-in-windows/"><u>5 Tactics to Prevent C: Drive From Running Dry in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/actions-to-undo-error-x80780119-on-windows-images/"><u>Actions to Undo Error X80780119 on Windows Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-through-to-windows-11-security-control-screen/"><u>A Step-by-Step Through to Windows 11 Security Control Screen</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-unveiling-synergy-youtube-content-on-facebook-network/"><u>In 2024, Unveiling Synergy  YouTube Content on Facebook Network</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719327449344-bargain-hunters-rejoice-key-lovers-snag-best-prices-for-lifetime-windows-11/"><u>Bargain Hunters Rejoice: Key Lovers Snag Best Prices for Lifetime Windows 11</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-key-browser-aides-optimized-vimeo-content-downloads/"><u>[New] Key Browser Aides  Optimized Vimeo Content Downloads</u></a></li>
</ul></div>
