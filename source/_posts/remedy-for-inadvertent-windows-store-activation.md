---
title: Remedy for Inadvertent Windows Store Activation
date: 2024-11-03T08:25:29.930Z
updated: 2024-11-06T21:24:50.146Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Remedy for Inadvertent Windows Store Activation
excerpt: This Article Describes Remedy for Inadvertent Windows Store Activation
keywords: Unintended Windows Launch,Stop Windows Errors,Prevent App Install,Avoid Accidental Opening,Block Unwanted Updates,Halt Windows Glitches,Quiet Down Software Triggers
thumbnail: https://thmb.techidaily.com/24b4a5d68fd5e6bea75410f8f6c4c82cdd5bcbea33115cb8218e3e0a99c10ef2.jpg
---

## Remedy for Inadvertent Windows Store Activation

 The Microsoft Store has come a long way since its introduction to Windows 8\. Every app, game, or movie available on the store is certified, so you don’t have to worry about infecting your computer with malware.

 But what if Windows keeps opening the Microsoft Store for no apparent reason? If you’ve run into the same issue, this guide should help you fix it.

##

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Close Microsoft Store's Background Processes

 Windows might keep opening the Microsoft Store if there’s a process still running in the background. To fix it, you should use Task Manager to stop any background activity.

 Press**Ctrl + Shift + Esc** to bring up Task Manager. There, right-click**Microsoft Store** and select**End task** .

![Close Windows Store with Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/task-manager-1.jpg)

##

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134491/18498" target="_top" id="2134491">
  <img src="//a.impactradius-go.com/display-ad/18498-2134491" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134491/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Restart the Microsoft Store Services

 There’s a chance that the Microsoft Store keeps acting up because of a service malfunction. The Microsoft Store Install Service is the one that works in the background to keep the store working.

 This is why restarting the service might be enough to fix Microsoft Store.

1. In the Start menu search bar, search for**services** and select**Run as administrator** .
2. In the Services window, locate and open**Microsoft Store Install Service** .
3. Click**Stop > Start** to restart it.
4. Restart your computer and monitor if Microsoft Store keeps opening.

![Restart Microsoft Store service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/store-service-1.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528688/16446" target="_top" id="1528688">
  <img src="//a.impactradius-go.com/display-ad/16446-1528688" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528688/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080333/19272" target="_top" id="2080333">
  <img src="//a.impactradius-go.com/display-ad/19272-2080333" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080333/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Re-register Microsoft Store

 If nothing worked until now, you could re-register the Microsoft Store app. To do it, launch PowerShell with administrative rights and paste this code:

`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}<strong> </strong>`

 Then, press**Enter** to run it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135415/19272" target="_top" id="2135415">
  <img src="//a.impactradius-go.com/display-ad/19272-2135415" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135415/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Apply Generic Fixes for Microsoft Store Issues

 You may encounter this problem if the cache has become corrupted. As such, check out[how to fix a damaged Microsoft Store cache](https://www.makeuseof.com/ways-to-fix-damaged-microsoft-store-cache/) for more ways to fix this annoying problem.

 Similarly, a virus may be causing the Microsoft Store to open. Check out[how to remove malware using a Microsoft Defender offline scan](https://www.makeuseof.com/how-to-remove-malware-using-microsoft-defenders-offline-scan/) and give your PC a deep clean.

## Fix the Microsoft Store App Opening Itself

 Having the Microsoft Store app open by itself can be very disruptive, especially if it opens on top of all windows. Hopefully, one of these solutions worked and Microsoft Store has stopped launching by itself.

 If you’ve had enough and uninstalled it, you can still get Microsoft apps without the Microsoft Store.

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
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-tips-to-prevent-frame-skipping-in-obs-studio/"><u>[New] In 2024, Tips to Prevent Frame Skipping in OBS Studio</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-optimal-recording-is-30fps-or-60fps-superior-for-videos-for-2024/"><u>[Updated] Optimal Recording Is 30Fps or 60Fps Superior for Videos for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-visionedit-pro/"><u>[Updated] VisionEdit Pro</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-top-10-ingenious-ae-techniques-for-headline-hype/"><u>2024 Approved Top 10 Ingenious AE Techniques for Headline Hype</u></a></li>
<li><a href="https://technical-tips.techidaily.com/amazing-ipad-air-assessment-surpasses-expectations-making-me-question-my-ipad-pro-choice-a-deep-dive-by-zdnet/"><u>Amazing iPad Air Assessment: Surpasses Expectations, Making Me Question My iPad Pro Choice! - A Deep Dive by ZDNet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decode-your-pc-6-simple-ways-to-know-its-model/"><u>Decode Your PC - 6 Simple Ways to Know Its Model</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-fix-pokemon-go-route-not-working-on-poco-x5-drfone-by-drfone-virtual-android/"><u>How to Fix Pokemon Go Route Not Working On Poco X5? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-a-guide-nubia-red-magic-9-proplus-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>In 2024, A Guide Nubia Red Magic 9 Pro+ Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-elevate-engagement-discover-these-top-12-techniques-for-video-success/"><u>In 2024, Elevate Engagement - Discover These Top 12 Techniques for Video Success</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-synchronized-system-apple-watch-and-mac-unlocking/"><u>In 2024, Synchronized System Apple Watch and Mac Unlocking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-the-webcam-woes-unlocking-error-a00f4289-in-win11/"><u>Navigating Through the Webcam Woes: Unlocking Error A00F4289 in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-prevent-windows-notepad-crashes/"><u>Strategies to Prevent Windows Notepad Crashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-and-tricks-mastering-windows-11-login-security/"><u>Tips & Tricks: Mastering Windows 11 Login Security</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-how-win11-secrets-your-digital-world/"><u>Understanding How Win11 Secrets Your Digital World</u></a></li>
</ul></div>

