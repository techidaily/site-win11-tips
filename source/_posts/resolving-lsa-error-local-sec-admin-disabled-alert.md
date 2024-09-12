---
title: "Resolving LSA Error: Local Sec Admin Disabled Alert"
date: 2024-09-11T01:20:50.040Z
updated: 2024-09-12T01:20:50.040Z
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
<span id="1983549">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983549.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983549">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983549.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983549%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983549/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 Several users on a [Microsoft Community forum thread](https://answers.microsoft.com/en-us/windows/forum/all/the-local-security-authority-protection-is-off/6bd9dad0-9d25-4b6e-b101-eeacac9d3b3a) reported that the bug that turns off the Local Security Authority protection feature originated with a Windows update released in March 2023, specifically, the Update for Microsoft Defender antivirus antimalware platform KB5007651\.

 Fortunately, Microsoft has listened to the concerns of the users and fixed this issue in new updates. However, you will have to update your operating system to the latest version to fix this. Therefore, refer to our guide on [how to update Windows manually](https://www.makeuseof.com/update-windows-manually/), install the pending updates and check if that fixes the problem.

 In case that doesn't resolve the issue, uninstall the KB5007651 update. Refer to our guide on [how to uninstall any Windows update](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) if you don't know how. If that doesn't resolve the issue, as some users continue to encounter it despite updating their operating system, apply the remaining fixes.





<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123740/7443" target="_top" id="2123740">
  <img src="//a.impactradius-go.com/display-ad/7443-2123740" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123740/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 4\. Uninstall Recently Installed Third-Party Applications

 Have you recently installed a third-party app, especially from a shady source, and subsequently experienced the error mentioned above in the Windows Security app? If that is the case, the app could be malicious, designed to steal your login credentials, which could be why it has turned off this security feature.

 If you remember the app you installed recently, follow our guide on [how to uninstall any software on Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) to remove it. If you don't remember, open the Settings app and navigate to **Apps > Installed apps**. Here, sort the apps according to the **Date installed**, find the latest app, and uninstall it.

![Sort Installed Apps by Date Installed in the Windows Setiings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sort-installed-apps-by-date-installed-in-the-windows-setiings-app.jpg)





<!-- affiliate ads begin -->
<span id="1531882">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1531882.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1531882">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1531882.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1531882%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1531882/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->








<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136621/26400" target="_top" id="2136621">
  <img src="//a.impactradius-go.com/display-ad/26400-2136621" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136621/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 5\. Repair and Reset the Windows Security Application

 The problematic Windows Security app can also turn off this security feature. If you've tweaked the app's settings recently, you're also more likely to get the "Local Security Authority protection is off" error. Repairing and resetting the Windows Security app is the best way to rule out these possibilities.

![Reset Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-windows-security.jpg)





<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130873/7443" target="_top" id="2130873">
  <img src="//a.impactradius-go.com/display-ad/7443-2130873" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130873/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 Resetting the app will restore its original default settings, eliminating the possibility that misconfigured settings are causing the problem. Repairing the app will fix any underlying issue with its functionality. Refer to our guide on [how to reset a Windows app](https://www.makeuseof.com/windows-reset-app/) (or [repair it)](https://www.makeuseof.com/windows-repair-apps-programs/) if this is your first time doing so.





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115916/19272" target="_top" id="2115916">
  <img src="//a.impactradius-go.com/display-ad/19272-2115916" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115916/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-easyrecorder-straightforward-windows-10-tool/"><u>[New] 2024 Approved EasyRecorder - Straightforward Windows 10 Tool</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-top-tier-screen-capture-tools-for-windows-and-macos/"><u>[New] 2024 Approved Top-Tier Screen Capture Tools for Windows & macOS</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-unpacking-features-a-deep-dive-into-free2xs-tools/"><u>[New] 2024 Approved Unpacking Features A Deep Dive Into Free2X's Tools</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-instagram-story-upgrade-how-to-add-music-effectively-for-2024/"><u>[New] Instagram Story Upgrade How to Add Music Effectively for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-simplify-your-digital-image-management-with-google-photos/"><u>[New] Simplify Your Digital Image Management with Google Photos</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-blueprint-for-buzz-elevating-your-profile-on-fb/"><u>[Updated] Blueprint for Buzz Elevating Your Profile on FB</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-transform-your-chronicles-free-extensions-and-mobile-apps-galore/"><u>[Updated] In 2024, Transform Your Chronicles FREE Extensions & Mobile Apps Galore</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-tailored-brand-symbols-turn-basic-templates-into-logos/"><u>[Updated] Tailored Brand Symbols Turn Basic Templates Into Logos</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-best-virtual-reality-bike-adventures-listed-here/"><u>2024 Approved Best Virtual Reality Bike Adventures Listed Here</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-expert-advice-on-itunes-video-capturing/"><u>2024 Approved Expert Advice on iTunes Video Capturing</u></a></li>
<li><a href="https://win-blog.techidaily.com/beat-the-new-world-connection-error-with-these-proven-strategies/"><u>Beat the 'New World Connection Error' With These Proven Strategies</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/downloading-broadcoms-official-bluetooth-driver-compatible-with-windows-1087/"><u>Downloading Broadcom's Official Bluetooth Driver Compatible with Windows 10/8/7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easing-overuse-signal-fixing-chatgpt-on-windowed-systems/"><u>Easing Overuse Signal: Fixing ChatGPT on Windowed Systems</u></a></li>
<li><a href="https://techtrends.techidaily.com/efficient-fixes-for-when-you-cant-find-the-msvcrtdll-component/"><u>Efficient Fixes for When You Can’t Find the MSVCRT.DLL Component</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-impossible-roblox-app-failures/"><u>Eliminating Impossible Roblox App Failures</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/exclusive-list-of-cost-free-video-downloaders-from-pinterest-for-2024/"><u>Exclusive List of Cost-Free Video Downloaders From Pinterest for 2024</u></a></li>
<li><a href="https://android-location.techidaily.com/getting-the-pokemon-go-gps-signal-not-found-11-error-in-samsung-galaxy-s24-drfone-by-drfone-virtual/"><u>Getting the Pokemon Go GPS Signal Not Found 11 Error in Samsung Galaxy S24 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-windows-10-and-11-desktop-context-menu-not-working/"><u>How to Fix the Windows 10 & 11 Desktop Context Menu Not Working</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-send-and-fake-live-location-on-facebook-messenger-of-your-realme-11-proplus-drfone-by-drfone-virtual-android/"><u>How to Send and Fake Live Location on Facebook Messenger Of your Realme 11 Pro+ | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improving-android-performance-via-wsl-resource-tweaks/"><u>Improving Android Performance via WSL Resource Tweaks</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-catchemall-celebrate-national-pokemon-day-with-virtual-location-on-realme-narzo-n55-drfone-by-drfone-virtual-android/"><u>In 2024, CatchEmAll Celebrate National Pokémon Day with Virtual Location On Realme Narzo N55 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/interactive-steps-to-peruse-windows-11s-registry-contents/"><u>Interactive Steps to Peruse Windows 11'S Registry Contents</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-dism-your-windows-11-image-salvation/"><u>Leveraging Dism: Your Windows 11 Image Salvation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/managing-metric-tracking-on-windows-11-wifi/"><u>Managing Metric Tracking on Windows 11 Wifi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-of-file-management-on-windows-with-altwindirstat/"><u>Master the Art of File Management on Windows with altWinDirStat</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-lsa-not-available-alert-in-windows/"><u>Mitigating LSA Not Available Alert in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-system-leading-winners-winning/"><u>Optimize Your System: Leading Winners, Winning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/presents-for-the-holidays-windows-apps-from-ms-store/"><u>Presents for the Holidays: Windows Apps From MS Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/python-server-integration-effective-windows-file-sharing/"><u>Python Server Integration: Effective Windows File Sharing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-establish-smooth-operations-in-windows-controls/"><u>Re-Establish Smooth Operations in Windows Controls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-your-screens-harmony-uncover-hidden-apps-and-windows-in-windows-11/"><u>Restore Your Screen's Harmony: Uncover Hidden Apps & Windows in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamlessly-connecting-wi-fi-and-ethernet-in-one-operating-system/"><u>Seamlessly Connecting Wi-Fi & Ethernet in One Operating System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-non-existent-device-error-in-windows-11/"><u>Solving Non-Existent Device Error in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactical-approach-to-fix-a-non-responsive-battlenet-app/"><u>Tactical Approach to Fix a Non-Responsive Battle.net App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-improve-win-11s-virtual-memory/"><u>Tips to Improve Win 11'S Virtual Memory</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/truthseekers-elons-latest-ai-venture/"><u>TruthSeekers: Elon's Latest AI Venture?</u></a></li>
<li><a href="https://solve-outstanding.techidaily.com/unveiling-the-best-perian-replacements-must-try-applications-for-both-macos-and-windows-users/"><u>Unveiling the Best Perian Replacements: Must-Try Applications for Both macOS and Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/utilizing-microsoft-windows-11-for-child-safety/"><u>Utilizing Microsoft Windows 11 for Child Safety</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>