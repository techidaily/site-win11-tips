---
title: "Bring Back the Store: Reactivation Steps for MS in Windows 11"
date: 2024-07-29T08:13:24.552Z
updated: 2024-07-30T08:13:24.552Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Bring Back the Store: Reactivation Steps for MS in Windows 11"
excerpt: "This Article Describes Bring Back the Store: Reactivation Steps for MS in Windows 11"
keywords: Revive Win11 Stores,ReactWinMS Shop,StoreRevive Windows11,MS Marketplace Update,Reinstall WinStore,Win11 Retail Service,MS Store Reactivation
thumbnail: https://thmb.techidaily.com/16d13254afac9149dce0a2e443b3fbb7f20249bb61b5f6680c7797d944c293aa.jpg
---

## Bring Back the Store: Reactivation Steps for MS in Windows 11

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Re-Register Microsoft Store Apps for Current Users

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

 If the[Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

To re-register Microsoft Store apps for the current user:

1. Press the**Win** key and type "powershell" into the Search bar.
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell console, type the following command and press**Enter** :  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
4. Wait for the command to execute and complete. You may see a blue loading graphic.
5. Once done, type**exit** and press**Enter** to close PowerShell.

 During the process, you may see some errors highlighted in red. It is due to PowerShell trying to reinstall existing apps on Windows. So, ignore the error and wait for the process to complete.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Re-Register Microsoft Store Apps for All Users

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Install and Re-Register All Microsoft Store Apps on Windows 11

 Re-registering Windows apps is often necessary when Microsoft Store is not working. It can also help deal with other Windows settings and apps. If the issue persists, try the built-in Windows Store Apps troubleshooter to fix common Microsoft Store app issues.


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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-converting-live-streamed-youtubes-into-animated-gif-formats/"><u>[New] 2024 Approved  Converting Live Streamed YouTubes Into Animated GIF Formats</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-studio-vs-campers-contest/"><u>[New] 2024 Approved  Studio vs Camper’s Contest</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-advanced-techniques-for-live-action-sims-playback/"><u>[New] Advanced Techniques for Live-Action Sims Playback</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-advanced-tips-for-bordered-instagram-photography-for-2024/"><u>[New] Advanced Tips for Bordered Instagram Photography for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-comprehensive-strategies-for-tracking-yt-traffic-and-gains/"><u>[New] Comprehensive Strategies for Tracking YT Traffic and Gains</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-deciding-the-best-skype-audio-capture-of-2023/"><u>[New] Deciding the Best Skype Audio Capture of 2023</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-in-2024-pioneering-the-art-of-storytelling-top-youtubers-of-year-2023/"><u>[New] In 2024, Pioneering the Art of Storytelling - Top YouTubers of Year 2023</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-the-10-best-blurred-background-tools/"><u>[Updated] 2024 Approved  The 10 Best Blurred Background Tools</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-beat-matchers-playlist-selecting-flawless-dj-videos-for-2024/"><u>[Updated] Beat Matcher's Playlist  Selecting Flawless DJ Videos for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-expert-tips-for-effective-pip-use-on-edge-browser/"><u>[Updated] Expert Tips for Effective PIP Use on Edge Browser</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-large-display-medium-network-selection-tips/"><u>[Updated] Large Display Medium Network Selection Tips</u></a></li>
<li><a href="https://android-location.techidaily.com/10-free-location-spoofers-to-fake-gps-location-on-your-poco-m6-pro-4g-drfone-by-drfone-virtual/"><u>10 Free Location Spoofers to Fake GPS Location on your Poco M6 Pro 4G | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-from-screen-to-disk-techniques-for-effortless-internet-show-recording/"><u>2024 Approved  From Screen To Disk  Techniques for Effortless Internet Show Recording</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/5-quick-methods-to-bypass-vivo-v27-frp-by-drfone-android/"><u>5 Quick Methods to Bypass Vivo V27 FRP</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-poco-f5-5g-drfone-by-drfone-virtual-android/"><u>A Detailed Guide on Faking Your Location in Mozilla Firefox On Poco F5 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-broken-disk-organization-in-os/"><u>Addressing Broken Disk Organization in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-the-heart-of-your-system-pc-manager-for-w11/"><u>Configuring the Heart of Your System: PC Manager for W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-spontaneous-file-explorer-opens/"><u>Disabling Spontaneous File Explorer Opens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eject-incompatible-setup-warnings-in-win11/"><u>Eject Incompatible Setup Warnings in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-efficiency-with-these-5-must-have-apps-on-windows-11/"><u>Enhance Efficiency with These 5 Must-Have Apps on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-to-windows-11s-photo-application-blurring-feature/"><u>Expert Guide to Windows 11'S Photo Application Blurring Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-to-know-your-characters-on-windows-11/"><u>Get to Know Your Characters on Windows 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/ideas-on-improving-gopros-energy-management-for-2024/"><u>Ideas on Improving GoPro's Energy Management for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-vivo-y28-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Hassle-Free Solutions to Fake Location on Find My Friends Of Vivo Y28 5G | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-oppo-a38-by-drfone-android/"><u>In 2024, Complete Review & Guide to Techeligible FRP Bypass and More For Oppo A38</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-how-to-seamlessly-convert-vimeo-media-to-mp3/"><u>In 2024, How to Seamlessly Convert Vimeo Media to MP3</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-looking-for-a-location-changer-on-oppo-a1-5g-look-no-further-drfone-by-drfone-virtual-android/"><u>In 2024, Looking For A Location Changer On Oppo A1 5G? Look No Further | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-mastering-the-world-of-igs-reels-and-stories/"><u>In 2024, Mastering the World of IG’s Reels and Stories</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-the-best-ispoofer-alternative-to-try-on-samsung-galaxy-f15-5g-drfone-by-drfone-virtual-android/"><u>In 2024, The Best iSpoofer Alternative to Try On Samsung Galaxy F15 5G | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/mastering-instagram-stories-integrating-personalized-graphics-for-2024/"><u>Mastering Instagram Stories  Integrating Personalized Graphics for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-rapid-launcher-loading/"><u>Mastering the Art of Rapid Launcher Loading</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-resolution-of-windows-error-0x80040610-for-outlook/"><u>Mastering the Resolution of Windows Error 0X80040610 for Outlook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-windows-permission-problems/"><u>Mastery over Windows Permission Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-value-save-on-upgrade-with-windows-11-pro-key/"><u>Maximize Value, Save on Upgrade with Windows 11 Pro Key</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-download-performance-in-the-microsoft-app-shop/"><u>Maximizing Download Performance in the Microsoft App Shop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-code-0xa00f4289-in-wincams/"><u>Navigating Through Code 0xA00F4289 in WinCams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-microsofts-safe-mode-only-coding/"><u>Navigating Through Microsoft's Safe Mode Only Coding</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-with-poise-and-precision-from-any-corner-of-the-globe/"><u>Navigating with Poise and Precision From Any Corner of the Globe</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-bypass-oculus-setup-failures-in-windows-1110/"><u>Quick Guide to Bypass Oculus Setup Failures in Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silent-data-exchange-safeguarding-files-across-ws11w10/"><u>Silent Data Exchange: Safeguarding Files Across WS11/W10</u></a></li>
<li><a href="https://extra-support.techidaily.com/solving-movie-editing-queries-with-filmora-guidance-for-2024/"><u>Solving Movie-Editing Queries with Filmora Guidance for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-print-again-in-win11/"><u>Step-By-Step Guide to Print Again in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-missing-d3dx939dll-in-win11/"><u>Steps to Fix Missing D3DX9_39.dll in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-administrative-tasks-a-new-approach-to-windows-uac/"><u>Streamlining Administrative Tasks: A New Approach to Windows UAC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-update-processes-context-menu-update-option-for-win11-users/"><u>Streamlining Update Processes: Context Menu Update Option for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-fn-key-tasks-in-windows-1011-oses/"><u>Tailoring FN Key Tasks in Windows 10/11 OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-overcoming-windows-notepad-hangups/"><u>Tips for Overcoming Windows Notepad Hangups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-smartphone-potential-as-windows-microphone/"><u>Unlocking Smartphone Potential as Windows Microphone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-cant-you-see-a-drive-letter-on-your-windows-machine/"><u>Why Can't You See a Drive Letter on Your Windows Machine?</u></a></li>
</ul></div>
