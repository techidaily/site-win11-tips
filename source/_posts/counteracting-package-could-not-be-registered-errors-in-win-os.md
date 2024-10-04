---
title: Counteracting 'Package Could Not Be Registered' Errors in Win OS
date: 2024-09-26T20:19:58.199Z
updated: 2024-10-03T20:25:01.655Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Counteracting 'Package Could Not Be Registered' Errors in Win OS
excerpt: This Article Describes Counteracting 'Package Could Not Be Registered' Errors in Win OS
keywords: Windows Registration Error Fix,WinOS Package Issue Resolution,Overcome WinError Packaging,Uninstalling Win OS Problems,Solving Win System Installation,Remedying Win Package Errors,Addressing WinOS Failure Alerts
thumbnail: https://thmb.techidaily.com/9abfa493c09f599241cf74fbf150ee16ae0981c6610495144fe17eca852c8fbd.jpg
---

## Counteracting 'Package Could Not Be Registered' Errors in Win OS

 Microsoft Photos is the default image viewer in Windows with which many users open picture files. However, some users can’t open images in Photos because of a “Package could not be registered” error. That issue arises for some Photos users when they try to open JPG or PNG images in that app.

 This is how you can fix the “Package could not be registered” error in Windows 11 and 10.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Run the Windows Store Apps Troubleshooter

 Start your error troubleshooting with a troubleshooter for UWP apps on Microsoft Store. Windows Store Apps is a troubleshooter that could identify and resolve an issue with the Photos app. These are the steps for running that troubleshooter in Windows 11:

1. Simultaneously press the**Win + I** keyboard keys to bring up Settings.
2. Click**Troubleshoot** within the**System** tab of Settings.
3. Next, select**Other trouble-shooters** to reach the Windows troubleshooters in Settings.
4. Press the Windows Store Apps troubleshooter’s**Run** button.  
![The troubleshooters in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/other-troubleshooters-in-settings.jpg)
5. Then select to apply fixes suggested by the Windows Store App troubleshooter.  
![The Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-store-apps-troubleshooter.jpg)

 The same troubleshooter is also available within Windows 10’s Settings app. To access it, click the**Update & Security** category and**Troubleshoot** tab. Then you can select**Additional troubleshooters** to bring up the list of troubleshooting tools.

## 2\. Update Photos

 Updating Microsoft Store apps like Photos can fix issues with them. So, try updating Microsoft Photos like this:

1. Click**Start** and select Microsoft Store on that button’s menu.
2. Select Microsoft Store’s**Library** tab.
3. Click**Get updates** to see what apps need updating. MS Store will then automatically download and install an update for Photos if available.  
![The Get updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/get-updates-button.jpg)
4. Wait for the Photos app update to finish before closing Microsoft Store.

## 3\. Repair and Reset the Photos Apps

 Repairing or resetting Photos will likely fix the “Package could not be registered” if that app has corrupted files or data. You can select adjacent**Repair** and**Reset** troubleshooting options for Photos within Settings’ Apps & Features tool. To apply this solution, follow the instructions in our guide for[resetting Microsoft Store apps](https://www.makeuseof.com/windows-reset-app/) . Select the**Repair** option first and**Reset** second if necessary.

![The Repair and Reset buttons for Photos](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-repair-reset-buttons.jpg)

<!-- affiliate ads begin -->
<span id="1630055">
					<video width="192" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1630055.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18460-1630055">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1630055.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:120px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fcaperobbin.sjv.io%2Fc%2F5597632%2F1630055%2F18460'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1630055/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Run the Deployment Image and System File Checker Tools

 The “Package could not be registered” error can also be due to Windows system file corruption. That much has been confirmed by users who’ve said that running Deployment Image Servicing Management and System File Checker scans fixed this issue on their PCs. You can apply this potential solution by[opening the Command Prompt with admin rights](https://www.makeuseof.com/windows-11-open-command-prompt/) and running these separate DISM and SFC commands:

`DISM.exe /Online /Cleanup-image /Restorehealth`

`sfc /scannow`

 Run the Deployment Image Servicing Management scan command before the System File Checker tool. Leave the Command Prompt open until it shows a Windows Resource Protection message for the SFC scan. If it says Windows Resource Protection repaired files, this resolution might have resolved the “Package could not be registered” error.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100530/7443" target="_top" id="2100530">
  <img src="//a.impactradius-go.com/display-ad/7443-2100530" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100530/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Reinstall Photos

 If the “Package could not be registered” error persists after applying the resolutions above, you might need to reinstall Photos to fix it. This solution is the most likely one to fix a corrupted Photos app. You can uninstall and reinstall Photos with PowerShell like this:

1. Start PowerShell with a method in our guide to[opening PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. Then input this command for uninstalling PowerShell and hit**Enter** :  
`Get-AppxPackage Microsoft.Windows.Photos | Remove-AppxPackage`  
![The uninstall Photos command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/remove-photos-command.jpg)
3. To reinstall Photos, input this PowerShell command and press**Enter** :  
`Get-AppxPackage -allusers Microsoft.Windows.Photos | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall Photos app command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reinstall-photos-app.jpg)
4. Restart your PC after reinstalling Photos.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136619/26400" target="_top" id="2136619">
  <img src="//a.impactradius-go.com/display-ad/26400-2136619" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136619/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Reset Windows

 If you’ve tried all other resolutions suggested here, there could be a deeper Windows issue causing the “Package could not be registered” Photos error. Then a system reset could be needed to remedy that deeper issue. Resetting Windows will refresh the platform’s components and restore it to a default state.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reset-this-pc-tool.jpg)

 This is suggested as a last resort because you’ll need to reinstall third-party software installed before resetting Windows. However, you can select to keep user files such as photos, documents, videos, etc. Our[guide to resetting Windows 10 and 11](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) tells you how to perform a factory reset.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105869/7443" target="_top" id="2105869">
  <img src="//a.impactradius-go.com/display-ad/7443-2105869" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105869/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Open Your Images in Photos Again

 One of the above resolutions will likely resolve the “Package Could not be Registered” error on your Windows 11/10 PC. However, remember there are plenty of third-party app alternatives you can open your images with if that Photos error persists. IrfanView, XnView, and FastStone Image Viewer are among the best Photos alternatives that are freely available.

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-premier-external-hard-drive-choices-for-xbox/"><u>[New] 2024 Approved Premier External Hard Drive Choices for Xbox</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-unleashing-creative-potential-in-gopro-4k-edits/"><u>[New] Unleashing Creative Potential in GoPro 4K Edits</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-revolutionize-your-mind-best-15-tech-and-science-channels/"><u>[Updated] Revolutionize Your Mind Best 15 Tech & Science Channels</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-screen-recorder-mac-with-audio-for-2024/"><u>[Updated] Screen Recorder Mac with Audio for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-the-clutter-updating-and-refreshing-outdated-windows-tech/"><u>Clear the Clutter: Updating and Refreshing Outdated Windows Tech</u></a></li>
<li><a href="https://buynow-info.techidaily.com/comprehensive-review-of-mobvoo-ticwatch-e2-inexpensive-but-subpar-performance/"><u>Comprehensive Review of Mobvoo TicWatch E2: Inexpensive but Subpar Performance</u></a></li>
<li><a href="https://driver-download.techidaily.com/1722964960357-enhance-gaming-experience-with-corsair-icue-windows-11-and-nt-free-downloads-available-now/"><u>Enhance Gaming Experience with Corsair iCUE: Windows 11 and nT - FREE Downloads Available Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-pc-experience-through-win-pct-techniques/"><u>Enhance Your PC Experience Through Win PCT Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-internal-audio-problems-with-audacity-windows-11/"><u>Fixing Internal Audio Problems with Audacity (Windows 11)</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-additional-tips-about-sinnoh-stone-for-apple-iphone-6s-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, Additional Tips About Sinnoh Stone For Apple iPhone 6s Plus | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-change-sony-xperia-1-v-lock-screen-clock-in-seconds-by-drfone-android/"><u>In 2024, How To Change Sony Xperia 1 V Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-youtube-mysteries-solved-decoding-unlisted-content-explained/"><u>In 2024, YouTube Mysteries Solved Decoding 'Unlisted' Content Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keyboard-troubles-heres-a-list-of-solutions-to-rescue-ineffectual-shortcuts-in-windows/"><u>Keyboard Troubles? Here's a List of Solutions to Rescue Ineffectual Shortcuts in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-error-free-0x80072af9-corrections/"><u>Mastering Error-Free: 0X80072AF9 Corrections</u></a></li>
<li><a href="https://fox-that.techidaily.com/overcoming-iphone-silence-effective-solutions-to-activate-vibration-when-needed/"><u>Overcoming iPhone Silence: Effective Solutions to Activate Vibration When Needed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-chromium-noise-on-your-windows-pc/"><u>Reducing Chromium Noise on Your Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-procedure-elevating-to-virtualbox-version-70-on-windows-11/"><u>Stepwise Procedure: Elevating to VirtualBox Version 7.0 on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unpacking-decoding-the-red-x-in-windows-explorer/"><u>Unpacking: Decoding the Red X in Windows Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/wi-fi-adapter-no-more-windows-80211n-resolved-by-broadcom/"><u>Wi-Fi Adapter No More: Windows 802.11N Resolved by Broadcom</u></a></li>
</ul></div>

