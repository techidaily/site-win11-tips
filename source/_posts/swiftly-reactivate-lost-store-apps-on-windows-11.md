---
title: Swiftly Reactivate Lost Store Apps on Windows 11
date: 2024-10-03T22:35:49.958Z
updated: 2024-10-08T23:26:54.848Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Swiftly Reactivate Lost Store Apps on Windows 11
excerpt: This Article Describes Swiftly Reactivate Lost Store Apps on Windows 11
keywords: Swift App Reactivation Windows,Reinstate Lost Windows Store,Quick Windows App Fixing,Windows 11 App Restore,Reactivating Lost Apps W11,Fast Restart Store Software,Windows 11 App Revival
thumbnail: https://thmb.techidaily.com/6ed52b8d826a5b6701c9229d81239cb21a1a6ea95480871656b8b252c90f9890.jpeg
---

## Swiftly Reactivate Lost Store Apps on Windows 11

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Re-Register Microsoft Store Apps for Current Users

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
<a href="https://unicoeye.pxf.io/c/5597632/2134236/18498" target="_top" id="2134236">
  <img src="//a.impactradius-go.com/display-ad/18498-2134236" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134236/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135399/19272" target="_top" id="2135399">
  <img src="//a.impactradius-go.com/display-ad/19272-2135399" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135399/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137973/21526" target="_top" id="2137973">
  <img src="//a.impactradius-go.com/display-ad/21526-2137973" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137973/21526" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-evaluationcast-breakdown/"><u>[New] 2024 Approved EvaluationCast Breakdown</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-exclusive-list-top-10-live-streaming-networks-ranked/"><u>[New] 2024 Approved Exclusive List Top 10 Live Streaming Networks Ranked</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-ultimate-guide-to-enhancing-photos-with-top-10-screenshot-charmers/"><u>[New] In 2024, Ultimate Guide to Enhancing Photos with Top 10 Screenshot Charmers</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-best-virtual-background-for-google-meet-video-call/"><u>[Updated] In 2024, Best Virtual Background for Google Meet Video Call</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-rhythm-roundup-hot-music-for-todays-top-youtube-short-videos/"><u>[Updated] In 2024, Rhythm Roundup Hot Music for Today’s Top YouTube Short Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/artificial-insight-windows-software-reinvented/"><u>Artificial Insight: Windows Software Reinvented</u></a></li>
<li><a href="https://common-error.techidaily.com/bluetooth-keyboard-wont-pair-here-are-the-quick-fixes-for-pc-users/"><u>Bluetooth Keyboard Won't Pair? Here Are the Quick Fixes for PC Users!</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-netflix-location-to-get-more-country-version-on-apple-iphone-14-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Change Netflix Location to Get More Country Version On Apple iPhone 14 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsofts-copilot-key-what-does-it-mean-for-your-windows-11-pc/"><u>Microsoft's Copilot Key: What Does It Mean For Your Windows 11 PC?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalizing-your-pcs-dns-with-ease-in-windows-11/"><u>Revitalizing Your PC's DNS with Ease in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-win11-wi-fi-accessibility-with-9-steps/"><u>Securing Win11 Wi-Fi Accessibility with 9 Steps</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/simplify-screen-capture-the-6-key-steps-to-successfully-streaming-netflix-on-macos-for-2024/"><u>Simplify Screen Capture The 6 Key Steps to Successfully Streaming Netflix on macOS for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-fixing-non-displaying-searches-in-win-1011-os/"><u>Strategies for Fixing Non-Displaying Searches in Win 10/11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-overcome-sudden-screen-loss-during-win-games/"><u>Techniques to Overcome Sudden Screen Loss During WIN Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-manipulating-the-windows-11-registry-to-unlock-themes/"><u>The Art of Manipulating the Windows 11 Registry to Unlock Themes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-free-note-taking-tricks-in-windows-11/"><u>Top Free Note-Taking Tricks in Windows 11</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-with-the-trending-of-videos-more-and-more-people-are-likely-to-create-videos-to-help-people-figure-out-the-best-free-online-video-editing-tools-ive-/"><u>Updated With the Trending of Videos, More and More People Are Likely to Create Videos. To Help People Figure Out the Best Free Online Video Editing Tools, Ive Tested some Online Video Editors on the Market A for 2024</u></a></li>
</ul></div>

