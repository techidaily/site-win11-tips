---
title: "Regaining Access: Reactivating MS Store Apps in Windows 11"
date: 2024-06-25T16:18:52.846Z
updated: 2024-06-26T16:18:52.846Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Regaining Access: Reactivating MS Store Apps in Windows 11"
excerpt: "This Article Describes Regaining Access: Reactivating MS Store Apps in Windows 11"
keywords: Reactive MS App Windows,MS Store Restore Win11,Activate MS Store Pro,Revive Windows 11 MSC,Access MSC Windows 11,Resume MS Apps Win11,Restart MS Apps OS11
thumbnail: https://thmb.techidaily.com/81c104f653fc6628652d6140a521e94570f22aa2499ea9263be6a00f18fb658c.jpg
---

## Regaining Access: Reactivating MS Store Apps in Windows 11

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

## How to Re-Register Microsoft Store Apps for Current Users ![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

 If the [Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

To re-register Microsoft Store apps for the current user:

1. Press the**Win** key and type "powershell" into the Search bar.
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell console, type the following command and press**Enter** :  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
4. Wait for the command to execute and complete. You may see a blue loading graphic.
5. Once done, type**exit** and press**Enter** to close PowerShell.

 During the process, you may see some errors highlighted in red. It is due to PowerShell trying to reinstall existing apps on Windows. So, ignore the error and wait for the process to complete.

## How to Re-Register Microsoft Store Apps for All Users ![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

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
<li><a href="https://win11-tips.techidaily.com/upgrade-the-antiquity-embellishing-old-games-with-retroarch-awards/"><u>Upgrade the Antiquity - Embellishing Old Games With Retroarch Awards</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-for-fixing-fall-guys-link-failures-windows-wise/"><u>Essential Steps for Fixing Fall Guys Link Failures Windows-Wise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-windows-multiscreen-woes/"><u>Understanding Windows Multiscreen Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-10-step-roadmap-to-winrm/"><u>Unraveling the 10-Step Roadmap to WinRM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-cursor-chaos-win11s-troubleshooting-path/"><u>Navigating Cursor Chaos: Win11's Troubleshooting Path</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-and-optimize-windows-audios-with-up-to-date-drivers-guide/"><u>Revive and Optimize Windows Audios with Up-to-Date Drivers Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-digital-containers-file-prop-techniques/"><u>Navigating Digital Containers: File Prop Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-administrator-access-via-cmd/"><u>Instant Administrator Access via CMD</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-rapidly-increase-views-effective-growth-hacks-for-channels/"><u>In 2024, Rapidly Increase Views  Effective Growth Hacks for Channels</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-explore-the-10-most-inspiring-youtube-makeup-vloggers-ever/"><u>[New] In 2024, Explore the 10 Most Inspiring YouTube Makeup Vloggers Ever</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-elite-10-survival-skirmishes/"><u>[Updated] Elite 10 Survival Skirmishes</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-how-to-proficiently-follow-facebook-live-updates/"><u>[Updated] 2024 Approved  How to Proficiently Follow Facebook Live Updates</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-popular-photos-the-backstory/"><u>2024 Approved  Popular Photos  The Backstory</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-6-ways-to-transfer-contacts-from-realme-c67-5g-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 6 Ways To Transfer Contacts From Realme C67 5G to iPhone | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-diving-deeper-into-webcam-possibilities/"><u>2024 Approved  Diving Deeper Into Webcam Possibilities</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-can-i-use-a-fake-gps-without-mock-location-on-honor-90-pro-drfone-by-drfone-virtual-android/"><u>How Can I Use a Fake GPS Without Mock Location On Honor 90 Pro? | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-blueprint-for-attracting-brands-as-youtube-affiliates/"><u>2024 Approved  The Blueprint for Attracting Brands as Youtube Affiliates</u></a></li>
</ul></div>
