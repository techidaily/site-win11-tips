---
title: "Resolving LSA Error: Local Sec Admin Disabled Alert"
date: 2024-11-01T08:27:21.396Z
updated: 2024-11-07T03:45:56.491Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Resolving LSA Error: Local Sec Admin Disabled Alert"
excerpt: "This Article Describes Resolving LSA Error: Local Sec Admin Disabled Alert"
keywords: LSA Error Fixing,Local Admin Alert,Sec Admin Issue,Disable Security Alert,LSA Problem Resolution,Local Admin Status Check,Security Admin Restart
thumbnail: https://thmb.techidaily.com/234a90d5c27844c283f4441b2b9e5e76ee9e8064b4a1ba5d5f5c1598b8d0670d.jpg
---

## Resolving LSA Error: Local Sec Admin Disabled Alert

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037334/7443" target="_top" id="2037334">
  <img src="//a.impactradius-go.com/display-ad/7443-2037334" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037334/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Several users on a [Microsoft Community forum thread](https://answers.microsoft.com/en-us/windows/forum/all/the-local-security-authority-protection-is-off/6bd9dad0-9d25-4b6e-b101-eeacac9d3b3a) reported that the bug that turns off the Local Security Authority protection feature originated with a Windows update released in March 2023, specifically, the Update for Microsoft Defender antivirus antimalware platform KB5007651\.

 Fortunately, Microsoft has listened to the concerns of the users and fixed this issue in new updates. However, you will have to update your operating system to the latest version to fix this. Therefore, refer to our guide on [how to update Windows manually](https://www.makeuseof.com/update-windows-manually/), install the pending updates and check if that fixes the problem.

 In case that doesn't resolve the issue, uninstall the KB5007651 update. Refer to our guide on [how to uninstall any Windows update](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) if you don't know how. If that doesn't resolve the issue, as some users continue to encounter it despite updating their operating system, apply the remaining fixes.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997635/19272" target="_top" id="1997635">
  <img src="//a.impactradius-go.com/display-ad/19272-1997635" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997635/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Uninstall Recently Installed Third-Party Applications

 Have you recently installed a third-party app, especially from a shady source, and subsequently experienced the error mentioned above in the Windows Security app? If that is the case, the app could be malicious, designed to steal your login credentials, which could be why it has turned off this security feature.

 If you remember the app you installed recently, follow our guide on [how to uninstall any software on Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) to remove it. If you don't remember, open the Settings app and navigate to **Apps > Installed apps**. Here, sort the apps according to the **Date installed**, find the latest app, and uninstall it.

![Sort Installed Apps by Date Installed in the Windows Setiings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sort-installed-apps-by-date-installed-in-the-windows-setiings-app.jpg)

## 5\. Repair and Reset the Windows Security Application

 The problematic Windows Security app can also turn off this security feature. If you've tweaked the app's settings recently, you're also more likely to get the "Local Security Authority protection is off" error. Repairing and resetting the Windows Security app is the best way to rule out these possibilities.

![Reset Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-windows-security.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948876/19272" target="_top" id="1948876">
  <img src="//a.impactradius-go.com/display-ad/19272-1948876" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948876/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Resetting the app will restore its original default settings, eliminating the possibility that misconfigured settings are causing the problem. Repairing the app will fix any underlying issue with its functionality. Refer to our guide on [how to reset a Windows app](https://www.makeuseof.com/windows-reset-app/) (or [repair it)](https://www.makeuseof.com/windows-repair-apps-programs/) if this is your first time doing so.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136625/26400" target="_top" id="2136625">
  <img src="//a.impactradius-go.com/display-ad/26400-2136625" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136625/26400" style="position:absolute;visibility:hidden;" border="0" />
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

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-helps.techidaily.com/updated-2024-approved-level-up-your-playtime-examining-kinemaster-on-android/"><u>[Updated] 2024 Approved Level Up Your Playtime Examining KineMaster on Android</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-affordable-action-camera-deals-top-6-for-less-than-100-only/"><u>[Updated] Affordable Action Camera Deals Top 6 for Less Than $100 Only</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-breakthrough-tactics-for-capturing-virtual-conferences/"><u>[Updated] In 2024, Breakthrough Tactics for Capturing Virtual Conferences</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-high-speed-recording-tool-with-guided-soundtracks/"><u>[Updated] In 2024, High-Speed Recording Tool with Guided Soundtracks</u></a></li>
<li><a href="https://tech-haven.techidaily.com/conversational-cars-mercedes-benz-meshes-chatgpt-and-voice-control/"><u>Conversational Cars: Mercedes-Benz Meshes ChatGPT & Voice Control</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-erroneous-0xa00f429f-code-in-camera-app/"><u>Fixing the Erroneous 0xA00F429F Code in Camera App</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-top-5-from-nokia-150-2023-to-iphone-contacts-transfer-apps-and-software-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Top 5 from Nokia 150 (2023) to iPhone Contacts Transfer Apps and Software | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovate-with-ease-the-insiders-guide-to-windows-11-widgets/"><u>Innovate with Ease: The Insider's Guide to Window's 11 Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-software-glitch-audacity-error-9999/"><u>Overcoming Windows Software Glitch: Audacity Error 9999</u></a></li>
<li><a href="https://fox-that.techidaily.com/overcoming-your-iphones-display-difficulties-a-breakdown-of-the-top-7-challenges-and-fixes/"><u>Overcoming Your iPhone's Display Difficulties: A Breakdown of the Top 7 Challenges and Fixes</u></a></li>
<li><a href="https://extra-skills.techidaily.com/proven-techniques-for-amplifying-tiktok-unboxing-success-for-2024/"><u>Proven Techniques for Amplifying TikTok Unboxing Success for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shielding-wireless-networks-on-windows/"><u>Shielding Wireless Networks on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-remedies-for-elusive-steam-auth-delays-in-rust-and-pc/"><u>Swift Remedies for Elusive Steam Auth Delays in Rust & PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-overlooked-marvels-of-windows-11-functionality/"><u>The Overlooked Marvels of Windows 11 Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-steams-content-server-inaccessibility-in-windows/"><u>Troubleshooting Steam's Content Server Inaccessibility in Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/ultra-fast-conversion-official-platinum-winx-dvd-ripper-for-speedy-dvd-to-264hevc-mp4-ripping-in-minutes/"><u>Ultra-Fast Conversion: [OFFICIAL] Platinum WinX DVD Ripper for Speedy DVD to 264/HEVC MP4 Ripping in Minutes!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-limits-navigating-personal-identity-in-a-controlled-environment/"><u>Understanding Limits: Navigating Personal Identity in a Controlled Environment</u></a></li>
</ul></div>

