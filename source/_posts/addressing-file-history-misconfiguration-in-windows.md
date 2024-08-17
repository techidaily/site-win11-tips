---
title: Addressing File History Misconfiguration in Windows
date: 2024-08-16T01:10:14.469Z
updated: 2024-08-17T01:10:14.469Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing File History Misconfiguration in Windows
excerpt: This Article Describes Addressing File History Misconfiguration in Windows
keywords: Fix Windows Backup Issues,Tackle File Save Errors,Correct Windows HDD Sync,Solve Data Loss Problems,Mend Drives Recovery Faults,Rectify Files Not Synced,Unravel PC Storage Glitches
thumbnail: https://thmb.techidaily.com/cf1ae4b3cdb5debdafe3b02949517a45048f6142dd7f5f842e985181e8a620c0.jpg
---

## Addressing File History Misconfiguration in Windows

 File History is a nifty feature on Windows that allows you to back up your important files and folders to an external drive. Although the feature works as expected most of the time, it can occasionally trouble you with errors like the “We found errors in your File History settings” on Windows.

 Let’s see how you can resolve this error and get the File History feature to work again on Windows.

## 1\. Restart the File History Service

 File History Service is a small program that needs to be running in the background for the File History feature to work. If this service is experiencing any problems, you could run into the "We found errors in your File History settings" error. In most cases, you can fix any temporary issues with File History Service by simply restarting it.

To restart the File History Service in Windows:

1. Right-click on the**Start icon** and select**Run** from the resulting menu.
2. Type**services.msc** in the text box and press**Enter** .
3. In the Services windows, scroll down to locate**File History Service** . Right-click on it and select**Restart** . If the service is not running, select**Start** .  
![Restart File Hisotry Service Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/restart-file-hisotry-service-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Disconnect and Reconnect the Backup Drive

 Connection problems with your external drive can also cause Windows to display the "We found errors in your File History settings" error. If it’s nothing major, you should be able to resolve the error by disconnecting and reconnecting your backup drive.

 While you're at it, try using a different USB port. This will help you determine if there’s a [problem with the USB port](https://www.makeuseof.com/tag/dead-usb-port-heres-how-to-diagnose-and-fix-it/) you’re using. If you suspect a port is malfunctioning, check out how to diagnose and fix a faulty USB port on Windows.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## 3\. Re-Select the Backup Drive and Restart File History

 Next, you can try re-selecting your backup drive in File History settings and see if that helps. Here are the steps for the same.

1. Press**Win + R** or use one of the [many ways to open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**control** in the box and press**Enter** .
3. Click the**View by** drop-down menu and select**Large icons** .
4. Select**File History** from the Control Panel menu items.
5. Click the**Select drive** option from the left sidebar.
6. Select your preferred drive from the list and click**OK** .  
![Select File History Drive Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/select-file-history-drive-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After selecting your preferred drive, you’ll have to restart the File History feature on Windows. To do so, use the following steps:

1. Click the magnifying icon on the taskbar or use the**Win + S** keyboard shortcut to open the search menu.
2. Type**file history** in the search box and select the first result that appears.
3. In the Control Panel window that opens, click the**Turn off** button.
4. Wait for a few seconds and click the**Turn on** button.  
![Turn On File History in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-on-file-history-in-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the error message persists even after this, you can try using a different drive for the File History backup and see if that works.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Reset File History

 Finally, if nothing else works, resetting File History may be your only option. You can accomplish this by deleting the File History data files from your computer.

 In order to delete File History data files, you’ll have to ensure that your PC is configured to [show hidden files and folders on Windows](https://www.makeuseof.com/windows-11-show-hidden-files-folders/) . Here’s how to check.

1. Open the Windows search menu.
2. Type**File Explorer Options** in the search box and press**Enter** .
3. Switch to the**View** tab and check the**Show hidden files, folders, and drives** option.
4. Hit**Apply** followed by**OK** .

 Now, delete the File History data from your system by following the steps below.

1. Press**Win + E** to open File Explorer.
2. Type the following path in the File Explorer’s address bar and press**Enter** .  
`%UserProfile%\AppData\Local\Microsoft\Windows\FileHistory`
3. Press**Ctrl + A** to select all the folders and click the**trash icon** at the top to delete them.  
![Delete File Hisotry AppData](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/delete-file-hisotry-appdata.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->

## Fixing File History Errors on Windows

 After you apply the fixes listed above, the File History error should no longer bother you.

 Tired of dealing with File History errors on your Windows device? It might be a good idea to use a cloud storage service or third-party backup software to protect your important data.


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
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-cut-out-facebook-video-2023-edition-mobile-friendly/"><u>[New] 2024 Approved  Cut Out Facebook Video  2023 Edition, Mobile-Friendly</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-the-secrets-of-captivating-audiences-in-your-videos/"><u>[New] 2024 Approved  The Secrets of Captivating Audiences in Your Videos</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-1-3-in-ipad-voice-memos-and-recorders/"><u>[New] In 2024, 1-3 in iPad Voice Memos & Recorders</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-complete-kinetic-review-2023-for-2024/"><u>[Updated] Complete Kinetic Review 2023 for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-hands-on-crafting-unique-movie-closures-for-pennies/"><u>[Updated] Hands-On  Crafting Unique Movie Closures for Pennies</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-design-ideas-top-6-mc-village-residences/"><u>[Updated] In 2024, Design Ideas  Top 6 MC Village Residences</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-youtubes-economic-model-month-to-month-income/"><u>2024 Approved  YouTube's Economic Model  Month-to-Month Income?</u></a></li>
<li><a href="https://howto.techidaily.com/8-solutions-to-solve-youtube-app-crashing-on-xiaomi-redmi-note-12r-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Solutions to Solve YouTube App Crashing on Xiaomi Redmi Note 12R | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/ace-the-first-impression-create-professional-cover-letters-with-help-from-chatgpt/"><u>Ace the First Impression: Create Professional Cover Letters With Help From ChatGPT</u></a></li>
<li><a href="https://games-able.techidaily.com/are-high-end-macs-shaping-up-future-gaming-scenarios/"><u>Are High-End Macs Shaping Up Future Gaming Scenarios?</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/audiovisual-elements-in-eye-catching-fb-advertising-for-2024/"><u>Audiovisual Elements in Eye-Catching FB Advertising for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-or-see-text-messages-what-can-you-do-with-life360-on-apple-iphone-8-drfone-by-drfone-virtual-ios/"><u>Can Life360 Track Or See Text Messages? What Can You Do with Life360 On Apple iPhone 8? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/detailed-guide-on-removing-iphone-12-activation-lock-without-previous-owner-by-drfone-ios/"><u>Detailed Guide on Removing iPhone 12 Activation Lock without Previous Owner?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-9-tricks-for-enhancing-windows-11s-sound-experience/"><u>Discover 9 Tricks for Enhancing Windows 11'S Sound Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-linux-setup-not-wsl/"><u>Efficient Linux Setup, Not WSL</u></a></li>
<li><a href="https://win11-tips.techidaily.com/handling-the-exception-breaking-point-message-in-windows/"><u>Handling the Exception Breaking Point Message in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hiccup-in-snipsyncs-workflow-9-strategies-to-patch/"><u>Hiccup in SnipSync's Workflow? 9 Strategies to Patch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-engage-dialer-feature-win-11/"><u>How to Engage Dialer Feature Win 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-music-from-your-samsung-galaxy-a15-4g-by-fonelab-android-recover-music/"><u>How to recover old music from your Samsung Galaxy A15 4G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-run-the-system-file-checker-sfc-in-windows/"><u>How to Run the System File Checker (SFC) in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-swap-cr2-images-seamlessly-to-windows-jpgs/"><u>How to Swap CR2 Images Seamlessly to Windows JPGs</u></a></li>
<li><a href="https://fix-guide.techidaily.com/in-2024-10-best-fake-gps-location-spoofers-for-honor-v-purse-drfone-by-drfone-virtual-android/"><u>In 2024, 10 Best Fake GPS Location Spoofers for Honor V Purse | Dr.fone</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-effortless-ways-to-transfer-data-from-your-apple-iphone-12-pro-max-to-iphone-15-drfone-by-drfone-transfer-from-ios/"><u>In 2024, Effortless Ways to Transfer Data from Your Apple iPhone 12 Pro Max to iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-optimizing-video-playback-with-pip-on-safari-devices/"><u>In 2024, Optimizing Video Playback with PIP on Safari Devices</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/instagram-story-expertise-your-ultimate-resource-for-2024/"><u>Instagram Story Expertise  Your Ultimate Resource for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-points-preparing-for-a-full-system-reinstallation/"><u>Key Points: Preparing for a Full System Reinstallation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/learn-to-manipulate-software-sizes-using-windows-11s-shortcut-keys/"><u>Learn to Manipulate Software Sizes Using Windows 11'S Shortcut Keys</u></a></li>
<li><a href="https://driver-download.techidaily.com/logitech-driver-download-made-easy-fast-results-for-windows-users/"><u>Logitech Driver Download Made Easy: Fast Results for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-your-way-through-windowware-woes-8-tips-and-tricks/"><u>Navigating Your Way Through Windowware Woes: 8 Tips and Tricks</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-unleashing-creativity-in-mobile-sound-selection-how-to-design-ringtones/"><u>New 2024 Approved Unleashing Creativity in Mobile Sound Selection How to Design Ringtones</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-the-elite-lineup-of-audio-reverse-applications-discovering-your-ideal-choices-for-mobile-and-computing/"><u>New The Elite Lineup of Audio Reverse Applications Discovering Your Ideal Choices for Mobile & Computing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-dim-windows-11-screens-tips-inside/"><u>Overcoming Dim Windows 11 Screens - Tips Inside!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-hidden-desktop-icons-on-windows-11/"><u>Restore Hidden Desktop Icons on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-error-code-0x80041015-on-windows/"><u>Steps to Rectify Error Code 0X80041015 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-correction-winoss-parsing-error-0exc00ce556/"><u>Swift Correction: WinOSs Parsing Error 0eXC00CE556</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-disabling-method-for-windows-11-alerts/"><u>Swift Disabling Method for Windows 11 Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-for-turning-an-offline-printer-online/"><u>Tactics for Turning an Offline Printer Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-best-choice-selecting-quality-bittorrent-clients/"><u>The Best Choice: Selecting Quality BitTorrent Clients</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-unseen-paths-of-mouse-control-on-win11/"><u>The Unseen Paths of Mouse Control on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-mend-text-not-showing-up-on-discord-windows/"><u>Tips to Mend Text Not Showing Up on Discord Windows</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-6-kid-friendly-websites-with-free-movie-downloads/"><u>Top 6 Kid-Friendly Websites with Free Movie Downloads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-extra-potential-with-your-devices-via-a-90-degree-window-flip/"><u>Unlock Extra Potential with Your Devices via a 90-Degree Window Flip</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-ical-functionality-on-windows-11-devices/"><u>Unlocking iCal Functionality on Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-fixes-define-role-of-chkdsk-sfc-dism/"><u>Unraveling Windows Fixes: DEFINE Role of CHKDSK, SFC, DISM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/vintage-gear-future-functions-embrace-windows-11-with-to-go-and-rufus/"><u>Vintage Gear, Future Functions: Embrace Windows 11 with To Go and Rufus</u></a></li>
<li><a href="https://howto.techidaily.com/vivo-y78t-bootloop-problem-how-to-fix-it-without-data-loss-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Vivo Y78t Bootloop Problem, How to Fix it Without Data Loss | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-users-run-a-cost-free-locally-operated-gpt-model/"><u>Windows Users: Run a Cost-Free, Locally Operated GPT Model.</u></a></li>
</ul></div>
