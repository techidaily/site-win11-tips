---
title: Immediate Actions for 'Local Security Not Functioning' Warning
date: 2024-07-12T17:40:09.968Z
updated: 2024-07-13T17:40:09.968Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Immediate Actions for 'Local Security Not Functioning' Warning
excerpt: This Article Describes Immediate Actions for 'Local Security Not Functioning' Warning
keywords: Local Security Alert,Fix Secure System,Immediate Safeguard,Network Protection Error,Respond to Warnings,Stop Unauthorized Access,Trigger Warning Action
thumbnail: https://thmb.techidaily.com/e36d4a2a6c674cd6677ba6814b8c312dcb4a11aef63558c23c156a0dfc593865.jpg
---

## Immediate Actions for 'Local Security Not Functioning' Warning

 Have you seen a warning saying, "Local Security Authority protection is off. Your device may be vulnerable" in the Core isolation settings of the Windows Security app? If so, the Local Security Authority (LSA) protection feature, which protects your login credentials, is turned off on your system.

 The feature could be off for numerous reasons; a problematic Windows update, the presence of malware in your system, interference from a recently installed third-party app, problems with the Windows Security app, improper Registry Editor settings, and more. If you want to fix this issue and activate the feature again, apply the following solutions.

## 1\. Perform Some Preliminary Checks

 First off, perform the following basic fixes to ensure temporary issues haven't caused the feature to turn off:

* Close all apps currently running on your device. Then, restart your device.
* Try to manually enable the feature in Core isolation settings. For that, open the Windows Security app, navigate to the **Device Security** tab, and turn on the toggle under **Local Security Authority Protection**.
* If the feature is already enabled in the security settings, but the warning message still appears, disable it once, re-enable it again, and restart your device.
* Temporarily turn off third-party security software you use to ensure its interference does not turn off the feature.

 If none of the above fixes resolves the issue, begin applying the remaining fixes.

## 2\. Ensure the Warning Isn't Just a False Flag

 Some users who encountered the error under discussion reported that the warning was simply a false flag triggered due to a Windows update issue. In other words, the warning appeared even though the feature was already enabled and functioning well.

 Therefore, you should ensure that the warning you have received isn't just a false alarm and that the feature is turned off. Follow these steps to check that:

1. Open the **Event Viewer** app by searching for **"Event Viewer"** in Windows Search.
2. On the left-hand sidebar, navigate to **Applications and Services Logs > Microsoft > Windows > LSA**.
3. Find the event with **ID 5004** associated with LSA protection and ensure it is enabled and operational.

 If there is no event with this ID in the Event Viewer app, the feature could be disabled. So, apply the remaining fixes and see if they fix the issue.

## 3\. Install Any Pending Windows Updates
![A Windows laptop installing updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Install-Windows-11-Updates.jpg)

 Several users on a [Microsoft Community forum thread](https://answers.microsoft.com/en-us/windows/forum/all/the-local-security-authority-protection-is-off/6bd9dad0-9d25-4b6e-b101-eeacac9d3b3a) reported that the bug that turns off the Local Security Authority protection feature originated with a Windows update released in March 2023, specifically, the Update for Microsoft Defender antivirus antimalware platform KB5007651\.

 Fortunately, Microsoft has listened to the concerns of the users and fixed this issue in new updates. However, you will have to update your operating system to the latest version to fix this. Therefore, refer to our guide on [how to update Windows manually](https://www.makeuseof.com/update-windows-manually/), install the pending updates and check if that fixes the problem.

 In case that doesn't resolve the issue, uninstall the KB5007651 update. Refer to our guide on [how to uninstall any Windows update](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) if you don't know how. If that doesn't resolve the issue, as some users continue to encounter it despite updating their operating system, apply the remaining fixes.

## 4\. Uninstall Recently Installed Third-Party Applications

 Have you recently installed a third-party app, especially from a shady source, and subsequently experienced the error mentioned above in the Windows Security app? If that is the case, the app could be malicious, designed to steal your login credentials, which could be why it has turned off this security feature.

 If you remember the app you installed recently, follow our guide on [how to uninstall any software on Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) to remove it. If you don't remember, open the Settings app and navigate to **Apps > Installed apps**. Here, sort the apps according to the **Date installed**, find the latest app, and uninstall it.

![Sort Installed Apps by Date Installed in the Windows Setiings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sort-installed-apps-by-date-installed-in-the-windows-setiings-app.jpg)

## 5\. Repair and Reset the Windows Security Application

 The problematic Windows Security app can also turn off this security feature. If you've tweaked the app's settings recently, you're also more likely to get the "Local Security Authority protection is off" error. Repairing and resetting the Windows Security app is the best way to rule out these possibilities.

![Reset Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-windows-security.jpg)

 Resetting the app will restore its original default settings, eliminating the possibility that misconfigured settings are causing the problem. Repairing the app will fix any underlying issue with its functionality. Refer to our guide on [how to reset a Windows app](https://www.makeuseof.com/windows-reset-app/) (or [repair it)](https://www.makeuseof.com/windows-repair-apps-programs/) if this is your first time doing so.

## 6\. Ensure Malware Isn't Responsible for Deactivating the Feature

 Malware designed to find a loophole in your device's security can also turn off this feature to access your credentials and hand them over to threat actors. Considering how serious this threat can be, ensuring your device is virus-free is essential. Running the [Windows Defender malware scan](https://www.makeuseof.com/how-to-remove-malware-using-microsoft-defenders-offline-scan/) is probably the best way to find any threats.

 If any threats are detected, take the recommended actions to remove them. Once this is done, return to Core isolation settings and check if the warning has disappeared.

## 7\. Use Other Methods to Enable Local Security Authority Protection

 If none of the above fixes and checks have resolved the issue, the toggle to enable this feature is grayed out in Windows Security, and enabling the feature from the Windows Security app does not eradicate the warning, use the alternative ways to enable Local Security Authority protection.

 There are mainly two alternative ways to enable this feature on Windows: using the Local Group Policy Editor, a Windows utility for managing group policy settings, and using the Registry Editor, which lets us access and edit the Windows operating system configuration settings.

 Our guide on [how to enable Local Security Authority protection](https://www.makeuseof.com/windows-11-enable-local-security-authority-protection/) explains the process to enable this security feature using each of these methods.

 Misconfiguring the Windows Registry Editor settings can completely ruin your system's performance and even make it unbootable. So, don't forget to [create a Windows Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making any changes there.

## Enable LSA to Foolproof Your Security

 Buggy Windows updates often give rise to unforeseen problems now and then. The "Local Security Authority protection is off. Your device may be vulnerable" error can also result from a faulty Windows update. Hopefully, you can now take the necessary steps to ensure the warning isn't a false alarm and resolve the problem using the recommended fixes.

 If the issue persists, use the abovementioned alternative methods to enable the LSA feature forcefully.

 The feature could be off for numerous reasons; a problematic Windows update, the presence of malware in your system, interference from a recently installed third-party app, problems with the Windows Security app, improper Registry Editor settings, and more. If you want to fix this issue and activate the feature again, apply the following solutions.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-best-free-video-combining-tools-alternatives-to-software-this-year/"><u>Updated In 2024, Best Free Video Combining Tools Alternatives to Software This Year</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activate-windows-11-home-hub-guide/"><u>Activate Windows 11 Home Hub: Guide</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-discover-9-easy-no-cost-editing-software-options/"><u>[New] Discover 9 Easy, No-Cost Editing Software Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-windows-11-desk-drawings/"><u>A Step-by-Step Guide to Windows 11 Desk Drawings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-failed-shadow-copy-procedures/"><u>Addressing Failed Shadow Copy Procedures</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/still-using-pattern-locks-with-realme-10t-5g-tips-tricks-and-helpful-advice-by-drfone-android/"><u>Still Using Pattern Locks with Realme 10T 5G? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-resolving-rd-session-errors-win10win11/"><u>A Guide to Resolving RD Session Errors Win10/Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/abort-windows-over-the-top-contrast-mode/"><u>Abort Windows' Over-the-Top Contrast Mode</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-whats-the-best-video-size-for-instagram-weve-got-the-answer/"><u>Updated 2024 Approved Whats the Best Video Size for Instagram? Weve Got the Answer</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-how-to-take-360-videos-on-iphone-for-facebook/"><u>[Updated] In 2024, How to Take 360 Videos on iPhone for Facebook</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-from-raw-footage-to-youtube-a-step-by-step-process-unveiled/"><u>In 2024, From Raw Footage to YouTube  A Step-by-Step Process Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719266023156-zero-cost-local-gpt-clones-gpt4alls-window-solution/"><u>Zero-Cost Local GPT Clones: GPT4All's Window Solution.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-steam-interface-dll-failure-on-pc/"><u>Addressing Steam Interface Dll Failure on PC</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-find-the-perfect-video-collaboration-app-our-choice-of-10-free-tools/"><u>[New] In 2024, Find the Perfect Video Collaboration App  Our Choice of 10 Free Tools</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-6-appsservices-to-trace-any-gionee-f3-pro-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, Top 6 Apps/Services to Trace Any Gionee F3 Pro Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-pc-interaction-with-comprehensible-win11-navkeys/"><u>Accelerate PC Interaction with Comprehensible Win11 NavKeys</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated/"><u>Updated </u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-bilingual-capabilities-using-windows-shortcuts/"><u>Accelerate Your Bilingual Capabilities Using Windows Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-pc-choose-winning-apps-of-2023/"><u>Accelerate Your PC: Choose Winning Apps of 2023</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-photo-savvy-with-an-iphone-ideal-perspectives-uncovered/"><u>[New] Photo Savvy with an iPhone  Ideal Perspectives Uncovered</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-fix-the-checksum-error-in-winrar/"><u>6 Ways to Fix the Checksum Error in WinRAR</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-and-amending-system-call-failures-in-modern-windows/"><u>Addressing and Amending System Call Failures in Modern Windows</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/the-investors-guide-to-choosing-yt-channels-for-2024/"><u>The Investor's Guide to Choosing YT Channels for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-crafting-a-viral-path-best-hashtags-for-youtube-riches/"><u>2024 Approved  Crafting a Viral Path  Best Hashtags for YouTube Riches</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-change-your-apple-id-on-apple-iphone-11-with-or-without-password-by-drfone-ios/"><u>In 2024, How To Change Your Apple ID on Apple iPhone 11 With or Without Password</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-windows-printer-speedy-solutions/"><u>Accelerating Windows Printer: Speedy Solutions</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-ultimate-compilation-of-leading-9-mobile-meeting-services-ios-android-for-2024/"><u>[Updated] Ultimate Compilation of Leading 9 Mobile Meeting Services (iOS, Android) for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/foremost-recommendations-audio-customization-pros/"><u>Foremost Recommendations  Audio Customization Pros</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-to-disabling-chrome-tab-clones/"><u>A Step-by-Step Approach to Disabling Chrome Tab Clones</u></a></li>
<li><a href="https://change-location.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-samsung-galaxy-s21-fe-5g-2023-drfone-by-drfone-virtual-android/"><u>9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Samsung Galaxy S21 FE 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-elite-fight-club-best-of-10-battle-royale-titles/"><u>[New] 2024 Approved  Elite Fight Club  Best of 10 Battle Royale Titles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719266840560-prevent-unwanted-updates-on-your-pc-today/"><u>Prevent Unwanted Updates on Your PC Today!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-slick-techniques-to-launch-iis-manager/"><u>8 Slick Techniques to Launch IIS Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-renovated-widget-display-tool-for-windows-11/"><u>Accessing Renovated Widget Display Tool for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-ways-to-open-the-print-management-tool-in-windows-11/"><u>9 Ways to Open the Print Management Tool in Windows 11</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-streamlined-sounds-iphones-efficient-podcasting/"><u>2024 Approved  Streamlined Sounds  IPhone's Efficient Podcasting</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-top-10-discord-plugins-to-improve-using-experience/"><u>[New] In 2024, Top 10 Discord Plugins to Improve Using Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719349707624-resurrect-your-xbox-on-a-slow-pc-steps-to-take/"><u>Resurrect Your Xbox on a Slow PC: Steps to Take!</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-understanding-video-length-and-content-strategy-in-youtube-shorts/"><u>[New] 2024 Approved  Understanding Video Length and Content Strategy in YouTube Shorts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-winter-wonderland-adjustments-in-windows-11/"><u>7 Winter Wonderland Adjustments in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-straightforward-steps-to-find-windows-ram-details/"><u>5 Straightforward Steps to Find Windows RAM Details</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-windows-in-minutes-with-handy-shorthand/"><u>Ace Windows in Minutes with Handy Shorthand</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719338830306-windows-lacks-drive-letters-why-and-how-to-rectify-this-issue/"><u>Windows Lacks Drive Letters: Why and How to Rectify This Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-operational-utorrent-installer-on-pcs/"><u>Addressing Non-Operational uTorrent Installer on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-customize-win11-mouse-controls/"><u>A Guide to Customize Win11 Mouse Controls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719364035206-on-premise-self-hosted-gpt-the-windows-path-via-gpt4all/"><u>On-Premise, Self-Hosted GPT: The Windows Path via GPT4All</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-fix-a-grayed-out-screen-saver-settings-on-windows/"><u>4 Ways to Fix a Grayed Out Screen Saver Settings on Windows</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/expert-tips-on-capturing-and-sharing-your-instagram-stories-for-2024/"><u>Expert Tips on Capturing and Sharing Your Instagram Stories for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-century-of-change-the-windows-taskbar/"><u>A Century of Change: The Windows Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-github-desktop-in-windows-1011/"><u>A Comprehensive Guide to GitHub Desktop in Windows 10/11</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/essential-choice-10-budget-friendly-caption-tools/"><u>Essential Choice  10 Budget-Friendly Caption Tools</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-decoding-and-mastering-the-true-significance-of-pfp-in-tiktok-world/"><u>[New] 2024 Approved  Decoding and Mastering  The True Significance of PFP in TikTok World</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-recovering-cortana-insights-on-pcs/"><u>A Guide to Recovering Cortana Insights on PCs</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-nocturnal-nuances-expert-insights-into-nighttime-photography-for-2024/"><u>[Updated] Nocturnal Nuances  Expert Insights Into Nighttime Photography for 2024</u></a></li>
</ul></div>
