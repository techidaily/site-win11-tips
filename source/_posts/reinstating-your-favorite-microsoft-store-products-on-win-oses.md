---
title: Reinstating Your Favorite Microsoft Store Products on Win OSes
date: 2024-09-26T22:46:07.845Z
updated: 2024-10-03T18:45:57.558Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reinstating Your Favorite Microsoft Store Products on Win OSes
excerpt: This Article Describes Reinstating Your Favorite Microsoft Store Products on Win OSes
keywords: MS Windows Restore,WinOS Product Reinstall,Microsoft Store Access,Win OS Repair,MS Favorite Purchases,Redo MS Store Buys,OS Update
thumbnail: https://thmb.techidaily.com/f52859b8cd9dd422cf0c712696f19c9a8d2ea9a54ae99a71f15e709bfd0f373c.jpg
---

## Reinstating Your Favorite Microsoft Store Products on Win OSes

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
<a href="https://aligracehair.sjv.io/c/5597632/1918714/19272" target="_top" id="1918714">
  <img src="//a.impactradius-go.com/display-ad/19272-1918714" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918714/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115951/19272" target="_top" id="2115951">
  <img src="//a.impactradius-go.com/display-ad/19272-2115951" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115951/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014851/22899" target="_top" id="2014851">
  <img src="//a.impactradius-go.com/display-ad/22899-2014851" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014851/22899" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-how-to-enhance-content-discovery-with-instagrams-changes/"><u>[New] 2024 Approved How to Enhance Content Discovery with Instagram's Changes</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-cutting-edge-tiktok-edits-secrets-shared/"><u>[Updated] Cutting-Edge TikTok Edits Secrets Shared</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-discover-the-power-of-5-editors-beyond-youtubes-boundaries/"><u>2024 Approved Discover the Power of 5 Editors Beyond Youtube's Boundaries</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-the-limitless-windows-chatai-with-freedomgpt/"><u>Explore the Limitless Windows ChatAI: With FreedomGPT</u></a></li>
<li><a href="https://techidaily.com/exploring-how-iphones-dominate-the-world-of-mobile-video/"><u>Exploring How iPhones Dominate the World of Mobile Video</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/exploring-virtual-realms-with-kinemaster-app-for-android-users-for-2024/"><u>Exploring Virtual Realms with KineMaster App for Android Users for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-realme-gt-5-pro-drfone-by-drfone-virtual-android/"><u>How Do I Stop Someone From Tracking My Realme GT 5 Pro? | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-ultimate-guide-from-htc-u23-pro-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide from HTC U23 Pro FRP Bypass</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-ultimate-guide-to-catch-the-regional-located-pokemon-for-nokia-c12-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Ultimate Guide to Catch the Regional-Located Pokemon For Nokia C12 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-through-stuck-windows-updates-with-these-tips/"><u>Navigate Through Stuck Windows Updates with These Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-greyed-out-erase-feature-in-windows-11-settings/"><u>Overcoming Greyed Out Erase Feature in Windows 11 Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-your-programs-size-control-on-win11/"><u>Personalizing Your Programs: Size Control on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-unresponsive-game-server-connections-in-windows-via-steam/"><u>Resolving Unresponsive Game Server Connections in Windows via Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safeguarding-windows-clock-from-user-modifications/"><u>Safeguarding Windows Clock From User Modifications</u></a></li>
</ul></div>

