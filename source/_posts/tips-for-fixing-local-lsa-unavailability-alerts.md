---
title: Tips for Fixing Local LSA Unavailability Alerts
date: 2024-10-09T05:48:46.473Z
updated: 2024-10-15T00:22:07.294Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tips for Fixing Local LSA Unavailability Alerts
excerpt: This Article Describes Tips for Fixing Local LSA Unavailability Alerts
keywords: LSA Alert Resolution Tips,Disabling LSA Notifications,Addressing LSA Downtime Issues,Fixing Local LSA Alerts,Troubleshooting LSA Failures,Removing LSA Errors,Stop Local LSA Warning
thumbnail: https://thmb.techidaily.com/8efb02d1ad78746fe7e04d066e97a30754c0040bd1d393f4b6d528ffbc9df6b1.jpg
---

## Tips for Fixing Local LSA Unavailability Alerts

 Have you seen a warning saying, "Local Security Authority protection is off. Your device may be vulnerable" in the Core isolation settings of the Windows Security app? If so, the Local Security Authority (LSA) protection feature, which protects your login credentials, is turned off on your system.

 The feature could be off for numerous reasons; a problematic Windows update, the presence of malware in your system, interference from a recently installed third-party app, problems with the Windows Security app, improper Registry Editor settings, and more. If you want to fix this issue and activate the feature again, apply the following solutions.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082539/7443" target="_top" id="2082539">
  <img src="//a.impactradius-go.com/display-ad/7443-2082539" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082539/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Install Any Pending Windows Updates

![A Windows laptop installing updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Install-Windows-11-Updates.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118315/7443" target="_top" id="2118315">
  <img src="//a.impactradius-go.com/display-ad/7443-2118315" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118315/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Several users on a [Microsoft Community forum thread](https://answers.microsoft.com/en-us/windows/forum/all/the-local-security-authority-protection-is-off/6bd9dad0-9d25-4b6e-b101-eeacac9d3b3a) reported that the bug that turns off the Local Security Authority protection feature originated with a Windows update released in March 2023, specifically, the Update for Microsoft Defender antivirus antimalware platform KB5007651\.

 Fortunately, Microsoft has listened to the concerns of the users and fixed this issue in new updates. However, you will have to update your operating system to the latest version to fix this. Therefore, refer to our guide on [how to update Windows manually](https://www.makeuseof.com/update-windows-manually/), install the pending updates and check if that fixes the problem.

 In case that doesn't resolve the issue, uninstall the KB5007651 update. Refer to our guide on [how to uninstall any Windows update](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) if you don't know how. If that doesn't resolve the issue, as some users continue to encounter it despite updating their operating system, apply the remaining fixes.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880944/19272" target="_top" id="1880944">
  <img src="//a.impactradius-go.com/display-ad/19272-1880944" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880944/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868575/19272" target="_top" id="1868575">
  <img src="//a.impactradius-go.com/display-ad/19272-1868575" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868575/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Enable LSA to Foolproof Your Security

 Buggy Windows updates often give rise to unforeseen problems now and then. The "Local Security Authority protection is off. Your device may be vulnerable" error can also result from a faulty Windows update. Hopefully, you can now take the necessary steps to ensure the warning isn't a false alarm and resolve the problem using the recommended fixes.

 If the issue persists, use the abovementioned alternative methods to enable the LSA feature forcefully.

 The feature could be off for numerous reasons; a problematic Windows update, the presence of malware in your system, interference from a recently installed third-party app, problems with the Windows Security app, improper Registry Editor settings, and more. If you want to fix this issue and activate the feature again, apply the following solutions.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-identifying-hidden-account-activities/"><u>[Updated] 2024 Approved Identifying Hidden Account Activities</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-building-authority-in-education-10-tips-for-youtube-channel-creation-for-2024/"><u>[Updated] Building Authority in Education 10 Tips for YouTube Channel Creation for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-hackers-handbook-advanced-win11-tactics/"><u>[Updated] The Hacker's Handbook Advanced Win11 Tactics</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-get-your-video-dimensions-spot-on-for-instagram-sharing/"><u>2024 Approved Get Your Video Dimensions Spot-On for Instagram Sharing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-security-enlarge-pins-best-practices-in-windows-1111/"><u>Boost Security, Enlarge Pins: Best Practices in Windows 11/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/converting-gmail-to-outlook-on-windows-a-step-by-step-guide/"><u>Converting Gmail To Outlook on Windows – A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-non-loading-messages-in-windows-discord-client/"><u>Correcting Non-Loading Messages in Windows Discord Client</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cut-the-words-start-talking-windows-11s-method/"><u>Cut the Words, Start Talking: Windows 11'S Method</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-honor-90-lite-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Honor 90 Lite | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-fixing-excel-notation-on-notepad/"><u>Guide: Fixing Excel Notation on Notepad</u></a></li>
<li><a href="https://fox-where.techidaily.com/how-to-overcome-common-airplay-issues-with-ease-a-step-by-step-guide/"><u>How to Overcome Common AirPlay Issues with Ease: A Step-by-Step Guide</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-professional-insights-crafting-and-sharing-360-videos-on-fb/"><u>In 2024, Professional Insights Crafting & Sharing 360 Videos on FB</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-10-password-cracking-tools-for-vivo-v27e-by-drfone-android/"><u>In 2024, Top 10 Password Cracking Tools For Vivo V27e</u></a></li>
<li><a href="https://screen-capture.techidaily.com/no-expense-high-quality-topping-chromebook-screen-capture-apps-for-2024/"><u>No Expense, High Quality – Topping Chromebook Screen Capture Apps for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/selective-subscription-strategies-for-ps5-gamers/"><u>Selective Subscription Strategies for PS5 Gamers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-silent-infiltrator-confronting-wacatacbml-in-your-windows-domain/"><u>The Silent Infiltrator: Confronting Wacatac.B!ml in Your Windows Domain</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-clear-up-a-white-login-screen-on-windows-1011/"><u>Tips to Clear Up a White Login Screen on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-your-potential-top-7-efficiency-enhancing-widgets-for-win-11/"><u>Unleashing Your Potential: Top 7 Efficiency Enhancing Widgets for Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-and-dxgidll-fix-for-a-missing-crucial-file/"><u>Win11 & Dxgi.dll: Fix for a Missing Crucial File</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    