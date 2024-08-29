---
title: Dodging the Hurdle of Microsoft Store Error 0X80072EFD on Windows Devices
date: 2024-08-28T01:10:08.531Z
updated: 2024-08-29T01:10:08.531Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Dodging the Hurdle of Microsoft Store Error 0X80072EFD on Windows Devices
excerpt: This Article Describes Dodging the Hurdle of Microsoft Store Error 0X80072EFD on Windows Devices
keywords: WinErrorSolution,X80072EFDSync,MSStoreHurdleDodge,ErrorCodeX2FEFF,WindowsDevicesFix,HurdleMicrosoftStore,0X80072EFDRemedy
thumbnail: https://thmb.techidaily.com/d37722b399ead697bedbcc110ba522ecee9e4647945e2b3d01fc0e88a66cb913.jpg
---

## Dodging the Hurdle of Microsoft Store Error 0X80072EFD on Windows Devices

 Users have reported a 0x80072EFD Microsoft Store error on support forums that can arise in Windows 11 or 10\. Those users see a "server stumbled" or "check your internet connection" message with a 0x80072EFD error code inside MS Store after launching that app. When this error pops up, users can't utilize the Microsoft Store.

 The 0x80072EFD error is often a connection-related one. However, it occurs even when users can surf the web in their browsers. If you need to fix the 0x80072EFD error, try fixing it with these potential resolutions.

## 1\. Run the Windows Store App Troubleshooter

 Running the Windows Store App troubleshooter is a straightforward potential resolution for the 0x80072EFD error to start with. That troubleshooting tool might detect issues and give you a fix. You can open and run the Windows Store App troubleshooter like this:

1. Press**Start** and click the menu shortcut to open Settings.
2. Select the**Troubleshoot** section of Settings.
3. Click on**Other trouble-shooters** to look through the troubleshooting tools.
4. Select Windows Store Apps'**Run** option to bring up that troubleshooting tool.  
![The troubleshooter list in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/troubleshooter-list-in-windows-11.jpg)
5. Go through and apply any suggestions the troubleshooter offers.  
![The Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-store-apps.jpg)

**Internet Connections** is another troubleshooter that may be useful for fixing the Microsoft Store's 0x80072EFD error. So, consider running that troubleshooter if the Windows Store Apps option doesn't help.

 Note that the troubleshooting tools are accessible in the**Update & Security** category in the Settings app if you use Windows 10\. Click the**Troubleshoot** tab and**Additional troubleshooters** option to access them from there. Then press the**Run this troubleshooter** buttons for Windows Store Apps or Internet Connections.

## 2\. Refresh the SoftwareDistribution Folder

 SoftwareDistribution is a folder for temporarily storing Windows update files. Sometimes refreshing that folder by renaming it can resolve error**0x80072EFD** . Rename the SoftwareDistribution folder like this:

1. Hold down the**Windows** key and press**S** to access a search utility.
2. Type in**cmd** to find a Command Prompt app.
3. Open Command Prompt with elevated permissions by clicking its**Run as administrator** option in the search tool.
4. Turn off some services by executing these separate commands:  
`net stop wuauserv  
net stop cryptSvc  
net stop bits  
net stop msiserver`
5. To rename SoftwareDistribution, type in the following and hit**Enter** :  
`ren C:\Windows\SoftwareDistribution SoftwareDistribution.old`  
![The rename SoftwareDistribution.old folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/rename-softwaredistribution-old-folder.jpg)
6. Also, rename a catroot2 directory with this command:  
`ren C:\Windows\System32\catroot2 catroot2.old`  
![The rename catroot2 command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/rename-catroot2-command.jpg)
7. Restart the turned-off services by inputting and executing the following commands:  
`net start wuaserv  
net start cryptSvcc  
net start bits  
net start msiserver`
8. Then bring up your Start menu to select**Restart** .

## 3\. Reset the Microsoft Store's Cache

 Microsoft store has a cache in which data accumulates. Resetting or clearing that cache's data is a reliable solution to various Microsoft Store issues. So, we recommend users try doing that when troubleshooting the 0x80072EFD error. You can clear that cache in Settings, as covered in our[guide for resetting apps](https://www.makeuseof.com/windows-reset-app/) in Windows 11 and Windows 10.

![The Reset button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-button.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
## 4\. Turn Off Proxy Server

 Some users who've needed to fix error 0x80072EFD have confirmed they resolved that issue by turning off the proxy server setting. That's because a proxy server generated a Microsoft Store connection issue on those users' PCs. You can check if a proxy server is enabled on your PC and disable it in the following steps:

1. Start the Run dialogue by pressing**Win** +**R** .
2. Type**inetcpl.cpl** inside Run's command box and click**OK** to open Internet Options.
3. Select**Connections** \>**LAN settings** to reach a**Use a proxy server** setting.  
![The LAN settings button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/advanced-tab.jpg)
4. Uncheck the checkbox for**Use a proxy server** if it's selected.
5. Click the**Automatically detect settings** option to select it.  
![The Use a proxy server for your LAN checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/use-a-proxy-server-option.jpg)
6. Select the Local Area Network window's**OK** option.

## 5\. Double-Check the Time Settings in Windows

 An incorrect region time on your PC is another potential cause for error 0x80072EFD. Users have confirmed they've fixed error 0x80072EF by adjusting time settings on their PCs. The Microsoft Store's time tracking needs to sync with the PC's set regional time. So, have a look through your time settings as follows:

1. [Open up Settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/) , and click that app's**Time & language** tab.
2. Click**Date & time** to view those settings.  
![The Date & time navigation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/date-time-tab.jpg)
3. Select to turn off the**Set time zone** option there.
4. Make sure the correct time zone for your location is selected in the**Time Zone** drop-down menu.  
![The Set the time zone automatically option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/set-the-time-automatically-option.jpg)
5. Then press the**Sync now** button.  
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Sync now button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sync-now-button.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
 Alternatively, you can manually set the time by disabling the Set the time automatically option. Press the**Change** button for the**Set the date and time manually** option. Check the date and exact time for your location via online sources, and then enter it inside the**Change date & time** box.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Enable TLS Protocols

 TLS is an encryption protocol that ensures your data privacy online. It's widely used and is essential for security when your computer communicates with internet servers.

1. Open Internet Options as specified in the first two steps for the fourth resolution.
2. Then select**Advanced** inside the Internet Options window.
3. Scroll down to the**Security** section on the**Advanced** tab.
4. Select the**TLS 1.0** ,**1.1** ,**1.2** , and**1.3** checkboxes there.  
![The Advanced tab in Internet Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-advanced-tab.jpg)
5. Click**Apply** to set the protocol options.
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
6. Select**OK** to exit the Internet Options window.

## 7\. Reregister Microsoft Store

 You can't reinstall Microsoft Store like other apps. However, reregistering it with PowerShell is similar to reinstalling. If other potential solutions don't fix the 0x80072EFD error, reregistering MS Store is worth a try. This is how you can register that app:

1. Activate the**Type here to search** box with that tool's**Windows** +**S** hotkey.
2. Enter**PowerShell** within that tool's search box.
3. Launch Windows PowerShell with elevated permissions by clicking that search result's**Run as administrator** option.
4. Input this command for reregistering MS Store and hit**Return** to execute:  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reregister MS Store command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reregister-ms-store-command.jpg)
5. Wait until you're sure the command has finished.
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
<!-- affiliate ads end -->
6. Then exit PowerShell, and select the**Restart** option.

## 8\. Reset Your Network

 Resetting network settings in Windows is another 0x80072EFD error fix that's worked for some users. Note that this measure will erase Wi-Fi and Ethernet connection details, so you'll need to re-establish your connection after applying it. You can apply this potential fix as covered in our[how-to reset networks in Windows 11](https://www.makeuseof.com/reset-network-settings-windows-11/) guide.

![The Reset now button for networks](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-now-network-option.jpg)

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## Get Shopping in Microsoft Store Again

 The 0x80072EFD error isn't always easy to fix, and you may have to try applying quite a few potential resolutions to get it sorted. However, many Microsoft Store users have fixed the 0x80072EFD error with the solutions in this guide. So, maybe one of those potential fixes will also work on your PC.

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
<li><a href="https://fox-info.techidaily.com/new-golden-nuggets-revealing-the-hottest-reddit-topics-10-for-2024/"><u>[New] Golden Nuggets  Revealing the Hottest Reddit Topics (10) for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-innovative-recording-solutions-for-igadgets/"><u>[Updated] 2024 Approved  Innovative Recording Solutions for iGadgets</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-elevate-your-marketing-game-free-50-youtube-adornments-here/"><u>[Updated] Elevate Your Marketing Game - Free 50 YouTube Adornments Here!</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-beyond-the-leading-films-hidden-cinema-treasures/"><u>[Updated] In 2024, Beyond the Leading Films  Hidden Cinema Treasures</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-adding-soundtracks-to-your-inshot-projects/"><u>2024 Approved  Adding Soundtracks to Your InShot Projects</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-capturing-your-xbox-playtime-for-sharing/"><u>2024 Approved  Capturing Your Xbox Playtime for Sharing</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-getting-acquainted-with-periscope-costs-benefits-and-account-creation/"><u>2024 Approved  Getting Acquainted with Periscope  Costs, Benefits & Account Creation</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-navigating-through-an-absent-obs-camera-input/"><u>2024 Approved  Navigating Through an Absent OBS Camera Input</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-ultimate-guide-capturing-internet-radio-with-14-methods/"><u>2024 Approved  The Ultimate Guide  Capturing Internet Radio with 14 Methods</u></a></li>
<li><a href="https://win-howtos.techidaily.com/8-fixes-for-windows-10-update-error-code-0x800f0922/"><u>8 Fixes for Windows 10 Update Error Code 0X800f0922</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/a-closer-look-at-kobo-clara-colours-screen-brilliance-ereader-reviews/"><u>A Closer Look at Kobo Clara Colour's Screen Brilliance – eReader Reviews</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/automated-conversion-tracking-with-the-help-of-cookiebot-technology/"><u>Automated Conversion Tracking with the Help of Cookiebot Technology</u></a></li>
<li><a href="https://win11-tips.techidaily.com/commanding-your-computer-to-rest-when-not-in-use/"><u>Commanding Your Computer to Rest When Not In Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-printer-settings-for-secure-edge-environment/"><u>Configuring Printer Settings for Secure Edge Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/connectivity-through-time-leveraging-windows-7-for-windows-11-activation/"><u>Connectivity Through Time: Leveraging Windows 7 for Windows 11 Activation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-false-listings-of-devices-in-windows-error-logs/"><u>Correcting False Listings of Devices in Windows Error Logs</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/crafty-impostors-exposed-spotting-fabricated-followers-for-2024/"><u>Crafty Impostors Exposed  Spotting Fabricated Followers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customize-and-control-your-windows-11-program-preferences/"><u>Customize and Control Your Windows 11 Program Preferences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-risks-of-keygen-virus-and-windows-security-measures/"><u>Decoding the Risks of Keygen Virus & Windows Security Measures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/direct-to-the-heart-of-recent-windows-use/"><u>Direct to the Heart of Recent Windows Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easing-privilege-based-errors-in-system-installation/"><u>Easing Privilege-Based Errors in System Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-reading-experience-in-windows-11-notepad/"><u>Elevate Reading Experience in Windows 11 Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-operational-usb-on-your-windows-machine/"><u>Fixing Non-Operational USB on Your Windows Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harnessing-windows-capabilities-for-bulk-archive-decompression/"><u>Harnessing Windows Capabilities for Bulk Archive Decompression</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-hidefake-snapchat-location-on-your-realme-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>How to Hide/Fake Snapchat Location on Your Realme 12 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-troubleshoot-microsoft-print-to-pdf-problem-on-windows-11-devices/"><u>How To Troubleshoot 'Microsoft Print to PDF' Problem on Windows 11 Devices</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-from-novice-to-pro-periscope-stream-mastery/"><u>In 2024, From Novice to Pro  Periscope Stream Mastery</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-realme-narzo-60-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How PGSharp Save You from Ban While Spoofing Pokemon Go On Realme Narzo 60 5G? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-11-free-apps-to-check-imei-on-poco-m6-5g-phones-by-drfone-android/"><u>In 2024, Top 11 Free Apps to Check IMEI on Poco M6 5G Phones</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-top-12-prominent-xiaomi-redmi-13c-5g-fingerprint-not-working-solutions-by-drfone-android/"><u>In 2024, Top 12 Prominent Xiaomi Redmi 13C 5G Fingerprint Not Working Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/invisible-archive-integration-win1011-imaging-strategies/"><u>Invisible Archive Integration: WIN10/11 Imaging Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-win-plus-p-not-working-on-windows-heres-how-to-fix-it/"><u>Is Win + P Not Working on Windows? Here's How to Fix It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-windows-update-self-replacing-amd-graphics-drivers/"><u>Master Windows Update: Self-Replacing AMD Graphics Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-compression-techniques-for-disk-optimization/"><u>Mastering File Compression Techniques for Disk Optimization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-edge-browser-setting-up-microsofts-defender-application-guard-in-win-11/"><u>Secure Edge Browser: Setting up Microsoft's Defender Application Guard in Win 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-media-powerhouses-unveiling-the-secrets-of-facebook-twitter-instagram-and-youtube/"><u>Social Media Powerhouses: Unveiling the Secrets of Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-stop-non-data-transfer-from-usb-ports-on-pc/"><u>Solutions to Stop Non-Data Transfer From USB Ports on PC</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-essential-companer-for-modern-pc-builds-by-toms-hq/"><u>The Essential Companer for Modern PC Builds by Tom's HQ</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-windows-11-home-into-a-virtual-environment-with-hyper-v/"><u>Transforming Windows 11 Home Into a Virtual Environment with Hyper-V</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-the-self-opens-issue-with-msdnstore/"><u>Troubleshooting the Self-Opens Issue with MSDN/Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-issues-from-a-recent-windows-system-upgrade/"><u>Unraveling Issues From a Recent Windows System Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-window-icon-location-techniques/"><u>Unveiling Window Icon Location Techniques</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-reducing-ambient-acoustic-disturbances-a-guide-to-minimizing-hiss/"><u>Updated In 2024, Reducing Ambient Acoustic Disturbances A Guide to Minimizing Hiss</u></a></li>
<li><a href="https://win11-tips.techidaily.com/zeroing-in-on-browsers-post-windows-setup/"><u>Zeroing in on Browsers Post-Windows Setup</u></a></li>
</ul></div>
