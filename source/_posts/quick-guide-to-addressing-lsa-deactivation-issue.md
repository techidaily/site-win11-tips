---
title: Quick Guide to Addressing LSA Deactivation Issue
date: 2024-11-21T16:36:24.791Z
updated: 2024-11-27T16:30:19.419Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Guide to Addressing LSA Deactivation Issue
excerpt: This Article Describes Quick Guide to Addressing LSA Deactivation Issue
keywords: LSA Deactivation Fix,SOLVING LSA Errors,Address LSA Shutdown,Quick LSA Reactivation,LSA Restart Guide,Resolving LSA Issue,Fast LSA Activation
thumbnail: https://thmb.techidaily.com/c47546ef14b433a853f147293a1e027910647d2b3c636b3d7439e396fc35c411.jpg
---

## Quick Guide to Addressing LSA Deactivation Issue

 Have you seen a warning saying, "Local Security Authority protection is off. Your device may be vulnerable" in the Core isolation settings of the Windows Security app? If so, the Local Security Authority (LSA) protection feature, which protects your login credentials, is turned off on your system.

 The feature could be off for numerous reasons; a problematic Windows update, the presence of malware in your system, interference from a recently installed third-party app, problems with the Windows Security app, improper Registry Editor settings, and more. If you want to fix this issue and activate the feature again, apply the following solutions.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlYIdWQc-jw?si=ZQ5809CbQGEar0vg&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Perform Some Preliminary Checks

 First off, perform the following basic fixes to ensure temporary issues haven't caused the feature to turn off:

* Close all apps currently running on your device. Then, restart your device.
* Try to manually enable the feature in Core isolation settings. For that, open the Windows Security app, navigate to the **Device Security** tab, and turn on the toggle under **Local Security Authority Protection**.
* If the feature is already enabled in the security settings, but the warning message still appears, disable it once, re-enable it again, and restart your device.
* Temporarily turn off third-party security software you use to ensure its interference does not turn off the feature.

 If none of the above fixes resolves the issue, begin applying the remaining fixes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XIUatTFH0Zw?si=ZCtoBtIy18y2F5Vc&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Repair and Reset the Windows Security Application

 The problematic Windows Security app can also turn off this security feature. If you've tweaked the app's settings recently, you're also more likely to get the "Local Security Authority protection is off" error. Repairing and resetting the Windows Security app is the best way to rule out these possibilities.

![Reset Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-windows-security.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JlX-G8rBs1w?si=iIhUoWAq5x3YK9rA&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Resetting the app will restore its original default settings, eliminating the possibility that misconfigured settings are causing the problem. Repairing the app will fix any underlying issue with its functionality. Refer to our guide on [how to reset a Windows app](https://www.makeuseof.com/windows-reset-app/) (or [repair it)](https://www.makeuseof.com/windows-repair-apps-programs/) if this is your first time doing so.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3hS27nZVi9Y?si=_Zqj_l4a4XkPqT2S&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-the-essential-list-of-gratuitous-quality-memes/"><u>[New] In 2024, The Essential List of Gratuitous, Quality Memes</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-effortless-setup-of-streamlabs-for-mac-users-via-obs/"><u>[Updated] 2024 Approved Effortless Setup of Streamlabs for Mac Users via OBS</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-in-2024-techniques-for-smooth-audio-transitions/"><u>[Updated] In 2024, Techniques for Smooth Audio Transitions</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-mememirror-app-mirror-the-worlds-laughter/"><u>[Updated] MemeMirror App - Mirror the World's Laughter</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-top-5-essential-mac-live-streaming-apps-for-2024/"><u>[Updated] Top 5 Essential Mac Live Streaming Apps for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/1726029712401-dvd/"><u>国際版DVDのプレイヤー設定 - 簡単なガイド</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cross-platform-utilization-windows-and-linux-synergy/"><u>Cross-Platform Utilization: Windows & Linux Synergy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-taskbar-usability-6-key-improvements-needed-by-microsoft/"><u>Enhancing Taskbar Usability: 6 Key Improvements Needed by Microsoft</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-sync-side-by-side-application-settings-on-win10/"><u>How to Sync Side-by-Side Application Settings on Win10</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-data-from-iphone-12-pro-to-android-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 12 Pro To Android? | Dr.fone</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/458544-9781101148549-is-your-child-psychic/"><u>Is Your Child Psychic? | Free Book</u></a></li>
<li><a href="https://techtrends.techidaily.com/learn-smarter-with-these-top-8-tech-tools-of-2024/"><u>Learn Smarter with These Top 8 Tech Tools of 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-cpu-state-display-in-windows-settings/"><u>Mastering CPU State Display in Windows Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methodical-approach-to-reviving-media-player-woes-in-win11/"><u>Methodical Approach to Reviving Media Player Woes in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-stop-video-freezing-on-steam/"><u>Methods to Stop Video Freezing on Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocketing-performance-in-windows-11-systems/"><u>Skyrocketing Performance in Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-guide-to-using-apples-messaging-service-in-windows/"><u>The Complete Guide to Using Apple's Messaging Service in Windows</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    