---
title: "Regaining Access: Reactivating MS Store Apps in Windows 11"
date: 2024-08-16T02:22:52.162Z
updated: 2024-08-17T02:22:52.162Z
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

## How to Re-Register Microsoft Store Apps for Current Users
![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

 If the [Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

To re-register Microsoft Store apps for the current user:

1. Press the**Win** key and type "powershell" into the Search bar.
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell console, type the following command and press**Enter** :  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
4. Wait for the command to execute and complete. You may see a blue loading graphic.
5. Once done, type**exit** and press**Enter** to close PowerShell.

 During the process, you may see some errors highlighted in red. It is due to PowerShell trying to reinstall existing apps on Windows. So, ignore the error and wait for the process to complete.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Re-Register Microsoft Store Apps for All Users
![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
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
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-fixing-invisible-areas-within-youtube-videos/"><u>[Updated] 2024 Approved  Fixing Invisible Areas Within YouTube Videos</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-action-packed-shoots-creating-dynamic-video-stories-on-youtube/"><u>[Updated] Action-Packed Shoots  Creating Dynamic Video Stories on YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-fix-the-cannot-find-gpeditmsc-error-in-windows/"><u>4 Ways to Fix the “Cannot Find Gpedit.msc” Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-key-steps-to-resolve-epic-launcher-security-code-errors-on-windows/"><u>7 Key Steps to Resolve Epic Launcher Security Code Errors on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-calendar-revolution-customizing-your-scheduling-tool-on-windows-pc/"><u>A Calendar Revolution: Customizing Your Scheduling Tool on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-understanding-and-using-components-settings/"><u>A Guide to Understanding and Using Components Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-windows-11-desk-drawings/"><u>A Step-by-Step Guide to Windows 11 Desk Drawings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-academic-excellence-winning-strategies-for-efficient-windows-learning/"><u>Achieve Academic Excellence: Winning Strategies for Efficient Windows Learning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-end-task-bar-functionality-in-windows-11/"><u>Activating End Task Bar Functionality in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/address-vanishing-hardware-problems-in-dm/"><u>Address Vanishing Hardware Problems In DM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-fresh-installation-displays-fail-to-start/"><u>Addressing Windows' Fresh Installation: Displays Fail To Start</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-guidelines-integrating-latest-intel-wireless-tech-in-os-x/"><u>Advanced Guidelines: Integrating Latest Intel Wireless Tech in OS X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-crashing-keep-your-file-explorer-fixed-in-windows-11/"><u>Avoid Crashing: Keep Your File Explorer Fixed in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-the-past-erasing-defenders-track-of-security-efforts/"><u>Banish the Past: Erasing Defender’s Track of Security Efforts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-the-black-glare-from-window-8-displays/"><u>Banishing the Black Glare From Window 8 Displays</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719192555427-environment-variables-configuration/"><u>Environment Variables Configuration:</u></a></li>
<li><a href="https://change-location.techidaily.com/how-does-the-stardust-trade-cost-in-pokemon-go-on-vivo-x90s-drfone-by-drfone-virtual-android/"><u>How does the stardust trade cost In pokemon go On Vivo X90S? | Dr.fone</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/how-to-effortlessly-gain-premium-quality-pictures-online/"><u>How to Effortlessly Gain Premium Quality Pictures Online</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-apple-iphone-12-pro-max-location-is-wrong-drfone-by-drfone-virtual-ios/"><u>How to Fix My Apple iPhone 12 Pro Max Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-10-fingerprint-lock-apps-to-lock-your-vivo-x-flip-phone-by-drfone-android/"><u>In 2024, Top 10 Fingerprint Lock Apps to Lock Your Vivo X Flip Phone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719371223006-master-the-digital-age-essential-keys-fan-deal-at-lowest-price-on-windows-11-612lifetime/"><u>Master the Digital Age - Essential Keys Fan Deal at Lowest Price on Windows 11, $6.12/Lifetime!</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/quick-resolution-zero-signal-on-dp-ports/"><u>Quick Resolution: Zero Signal on DP Ports</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719353940627-resolve-icloud-install-issues-on-windows-quickly/"><u>Resolve iCloud Install Issues on Windows Quickly!</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolved-amd-vulkan-problem/"><u>Resolved AMD Vulkan Problem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719332049172-swiftly-addressing-windows-faults-with-easy-fixes/"><u>Swiftly Addressing Windows Faults with Easy Fixes!</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-future-is-now-insights-from-jaunt-vr-review-for-2024/"><u>The Future Is Now  Insights From Jaunt VR Review for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/top-5-nokia-g22-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Nokia G22 Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719355984111-troubleshooting-made-simple-your-guide-to-windows-help/"><u>Troubleshooting Made Simple: Your Guide to Windows Help</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719358153094-unlocking-cloud-storage-integrating-dropbox-and-google-drive-via-c/"><u>Unlocking Cloud Storage: Integrating Dropbox and Google Drive via C:</u></a></li>
</ul></div>
