---
title: Troubleshooting O365 Sync Issues on Windows
date: 2024-08-16T02:35:03.787Z
updated: 2024-08-17T02:35:03.787Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting O365 Sync Issues on Windows
excerpt: This Article Describes Troubleshooting O365 Sync Issues on Windows
keywords: O365 Sync Problems,Office Sync Issues,Windows O365 Errors,O365 Sync Failures,Microsoft Office Synchronization,Fix O365 Sync Errors,Resolve Office Sync Issues
thumbnail: https://thmb.techidaily.com/d00f8f89497ceffd0abb3141cb4e3658817be8d659619b87570cab49fe038d18.jpg
---

## Troubleshooting O365 Sync Issues on Windows

 OneDrive is Microsoft’s cloud storage app included with Windows, and many users save their files to the cloud with it. However, some users have had issues accessing shared OneDrive files because of error 0x80070185\. When users try to copy or download shared OneDrive files, they see this message: “Error 0x80070185: The cloud operation was unsuccessful.”

 Users can’t copy or download shared files from OneDrive once error 0x80070185 appears. If you're also experiencing this issue, here is how you can fix error 0x80070185 in Windows 10 and 11.

## 1\. Log Out and Back Into OneDrive

 First, try logging out and back into your OneDrive account. To do so, you’ll need to unlink your PC with your OneDrive account. This is how you can log out and sign back into OneDrive:

1. Right-click the**OneDrive** icon in the system tray.
2. Click the**Help & Settings** cog button.
3. Select**Settings** to bring up an**Account** tab.  
![The Settings option in OneDrive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/settings-option.jpg)
4. Click the**Unlink this PC** option.  
![The Unlink this PC option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/unlink-this-pc.jpg)
5. Select**Unlink account** to sign out.

1. If a sign-in window doesn’t automatically open, input OneDrive in the Windows search box and select to open it there.
2. Input your OneDrive email address (for your Microsoft account), and click the**Sign in** option.  
![The Sign in button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/sign-in-button.jpg)
3. Enter a password, and press the**Sign in** button.
4. Keep clicking**Next** to reach the last option on the OneDrive setup window.
5. Press the**Open my OneDrive** **folder** button.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Free Up Hard Drive Space

 Error 0x80070185 can arise when there’s very little free space available on the local drive. As such, your PC’s hard drive may have insufficient space for the larger files in your OneDrive cloud storage.

 First, check your PC’s drive storage space by launching File Explorer and clicking**This PC** . The C: drive icon there shows you how much free storage is available.

![The Local Disk storage icon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/local-disk-storage-icon.jpg)

 If your PC’s hard drive is full, or close to it, free up some storage space. You can make more space on your hard drive by uninstalling software, deleting unneeded user files, and erasing junk data. Our guide about[how to free up storage space in Windows 11](https://www.makeuseof.com/windows-11-free-up-storage-space/) includes numerous methods for making space on a drive.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Reset the OneDrive App

 Corrupted OneDrive cache data is a potential cause for error 0x80070185 that you can address by resetting the app. Reset OneDrive with Run as follows:

1. Bring up the Power User shortcuts menu by pressing the**Win + X** keys.
2. Select**Run** to view that command dialog.
3. Type or paste the following command for resetting OneDrive into Run:  
`%localappdata%\Microsoft\OneDrive\OneDrive.exe /reset`  
![The reset OneDrive Run command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-reset-one-drive-command.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
4. Click**OK** to execute the reset command for OneDrive.
5. If the OneDrive icon doesn’t reappear after the reset, input this command into Run and click**OK** :  
`%localappdata%\Microsoft\OneDrive\onedrive.exe`

## 4\. Sync OneDrive to Another Drive Location

 Do you have another drive partition on your PC? If you do, try linking the OneDrive app with the alternative partition instead. You can sync OneDrive to a different drive location like this:

1. First, unlink the OneDrive app as outlined in steps one to five of this guide’s first potential resolution.
2. Then input the email address and password for the Microsoft account you utilize with the OneDrive app.
3. Press the**Sign in** button.
4. Click the**Change location** option.  
![The Change location option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/change-location-option.jpg)
5. Select an alternative drive partition on your PC to link OneDrive with.
6. Click**Select Folder** to confirm the chosen location.
7. Keep clicking**Next** a few times, and select the**Open my OneDrive folder** option.  
![The Open my OneDrive folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/open-my-onedrive-folder.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->

## 5\. Enable the "Always Keep on Device" and "Free Up Space" Options

 Some OneDrive users have confirmed selecting to always keep affected files on the device, along with a "free up space" option, can fix error 0x80070185\. Selecting the "always keep on this device" option makes a OneDrive file available offline.

 This is how you can select those options for an affected OneDrive file:

1. Press**Win + E** to open File Explorer.
2. Click the arrow for your OneDrive storage on the left of Explorer.
3. Right-click the file affected by error 0x80070185 and select**Always keep on this** **device** .  
![The Always keep on this device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/always-keep-on-this-device-option.jpg)
4. Then right-click the same file again to select**Free up** **space** .
5. Repeat these steps for all files you can’t access because of error 0x80070185.

## 6\. Turn Off Any Active Firewalls

 Firewall blocks applied to OneDrive can sometimes cause the error 0x80070185 to occur. We recommend users temporarily turn off firewalls to see if they’re causing this issue. You can turn off the Windows Defender Firewall with the following steps:

1. Click the**Search** box or a magnifying glass icon on your Windows taskbar.
2. Input**Windows Defender Firewall** to find the applet.
3. Select the**Windows Defender Firewall** search result to view the applet in the Control Panel.
4. Click**Turn Windows Defender Firewall on or off** to access the settings.  
![The Windows Defender Firewall applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-defender-firewall-applet.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
5. Select the two**Turn off Windows Defender Firewall** network settings, and click**OK** to apply.  
![The Turn off Windows Defender Firewall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/turn-off-windows-defender-firewall-option.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
6. Return to OneDrive to see if the 0x80070185 error persists with the firewall off.

 It’s also recommended to turn off any third-party firewalls installed. Some antivirus utilities also have firewalls. If you’ve installed any additional security software, select the option to disable its firewall if it has one.

 Should this potential solution resolve error 0x80070185, set up a firewall exception for OneDrive. You can do that for the Windows firewall as instructed in our[how to allow apps through Windows Defender](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) piece. Users with third-party firewalls can allow OneDrive through them with the exclusion settings in their security apps.

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
## 7\. Reinstall OneDrive

 Reinstalling OneDrive is a solution that’s worked for some users. This will give you a completely fresh and up-to-date OneDrive app. These are the steps for uninstalling and reinstalling OneDrive:

1. Launch Run (see[how to open Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for instructions) and input**ms-settings:appsfeatures** inside its**Open** box.
2. Select**OK** to view Apps & features in Settings.
3. If you’re using Windows 11’s Settings app, click OneDrive’s three-menu button and click**Uninstall** . You can select OneDrive and press**Uninstall** in Windows 10.  
![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-uninstall-option.jpg)
4. Select**Uninstall** for confirmation.
5. Open the[OneDrive page on the Microsoft Store](https://apps.microsoft.com/store/detail/onedrive/9WZDNCRFJ1P3?hl=en-gb&gl=gb) .
6. Click OneDrive’s**Get in Store** button.
7. Select**Open Microsoft Store** to view the OneDrive page in that app.  
![The Get button for OneDrive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/get-button-for-onedrive.jpg)
8. Click**Get** to reinstall OneDrive.

<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Access your OneDrive Files again

 OneDrive’s error 0x80070185 is not always easy to fix. However, users have got error 0x80070185 resolved by applying the troubleshooting methods above. Hopefully, one of them will restore access to your affected OneDrive files as well.

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
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-5-ways-to-record-gameplay-and-webcam/"><u>[New] 2024 Approved  5 Ways to Record Gameplay and Webcam</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-efficient-techniques-recording-saving-and-converting-movies-in-win-11/"><u>[New] 2024 Approved  Efficient Techniques  Recording, Saving, and Converting Movies in Win 11</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-key-10-acoustic-amplifiers-for-android-ios/"><u>[Updated] 2024 Approved  Key 10 Acoustic Amplifiers for Android, iOS</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-2024-approved-the-ultimate-guide-to-superior-gear-in-the-4k-market/"><u>[Updated] 2024 Approved  The Ultimate Guide to Superior Gear in the 4K Market</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-avoiding-poverty-earning-in-beauty-media/"><u>[Updated] Avoiding Poverty  Earning in Beauty Media</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-exquisite-online-destinations-for-sparkling-3d-typography/"><u>[Updated] Exquisite Online Destinations for Sparkling 3D Typography</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-build-successful-youtube-advertisements-for-free-for-2024/"><u>[Updated] How to Build Successful YouTube Advertisements for Free for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-instagram-success-stories-leveraging-highlights-for-growth/"><u>[Updated] In 2024, Instagram Success Stories  Leveraging Highlights for Growth</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-pinnacle-montage-apps-androidiphones-creative-powerhouses/"><u>[Updated] Pinnacle Montage Apps  Android/iPhone's Creative Powerhouses</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-quick-recording-visuals-plus-verbal-input/"><u>[Updated] Quick Recording  Visuals + Verbal Input</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-unlock-the-full-potential-of-windows-photos-app-with-visual-and-audio-tweaks/"><u>2024 Approved  Unlock the Full Potential of Windows Photos App with Visual & Audio Tweaks</u></a></li>
<li><a href="https://tech-revival.techidaily.com/best-ai-companion-exploring-features-of-google-bard-vs-bing-chat-for-a-winners-edge/"><u>Best AI Companion? Exploring Features of Google Bard vs Bing Chat for a Winner's Edge</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/complete-examination-of-eero-pro-wifi-routers-for-extensive-home-wireless-reach-and-quality-connection/"><u>Complete Examination of Eero Pro WiFi Routers for Extensive Home Wireless Reach and Quality Connection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conducting-an-intuitive-in-place-windows-11-transition/"><u>Conducting an Intuitive, In-Place Windows 11 Transition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/declutter-drive-space-recognizing-the-leviathans-in-windows-pcs/"><u>Declutter Drive Space: Recognizing the Leviathans in Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-your-way-to-system32-win11/"><u>Discovering Your Way to System32 (Win11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-win10-use-strategies-post-upgrade-decision/"><u>Efficient Win10 Use Strategies Post Upgrade Decision</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-managing-extraneous-tasks-on-windows/"><u>Efficiently Managing Extraneous Tasks on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-pc-download-pace-in-battlenet-gaming/"><u>Enhance PC Download Pace in Battle.net Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-11-icon-display-ease/"><u>Enhancing Windows 11 Icon Display Ease</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/guide-on-how-to-free-up-iphone-14-pro-max-space-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>Guide on How To Free Up iPhone 14 Pro Max Space | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-samsung-galaxy-m34-5g-location-on-skout-drfone-by-drfone-virtual-android/"><u>How to Change Samsung Galaxy M34 5G Location on Skout | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/how-to-record-ps3-gameplay-for-2024/"><u>How to Record PS3 Gameplay for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-iphone-se-2022-with-an-apple-watch-and-what-to-do-if-it-doesnt-work-by-drfone-ios/"><u>How to Unlock iPhone SE (2022) With an Apple Watch & What to Do if It Doesnt Work</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-oneplus-ace-2-phone-without-any-data-loss-by-drfone-android/"><u>How to Unlock OnePlus Ace 2 Phone without Any Data Loss</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-oppo-reno-9a-drfone-by-drfone-virtual-android/"><u>In 2024, 4 solution to get rid of pokemon fail to detect location On Oppo Reno 9A | Dr.fone</u></a></li>
<li><a href="https://buynow-info.techidaily.com/in-depth-analysis-of-the-midland-lxt50vp3-a-radio-with-features-but-questionable-execution/"><u>In-Depth Analysis of the Midland LXT50VP3 - A Radio with Features but Questionable Execution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-use-of-android-phones-as-webcams-on-windows-11-pcs/"><u>Innovative Use of Android Phones as Webcams on Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/invisible-culprits-affecting-windows-11s-efficiency/"><u>Invisible Culprits Affecting Windows 11'S Efficiency</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/invisible-motion-capture-instruction/"><u>Invisible Motion Capture Instruction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lightening-up-your-browser-load-top-7-windows-apps-less-ram-intensive/"><u>Lightening Up Your Browser Load: Top 7 Windows Apps Less RAM-Intensive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-reactivate-a-non-functional-windows-download-folder/"><u>Methods to Reactivate a Non-Functional Windows Download Folder</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-initial-load-hurdles-in-lol/"><u>Overcoming Initial Load Hurdles in LOL</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/quick-fixes-and-expert-advice-dealing-with-the-elusive-winhttpdll-problem/"><u>Quick Fixes and Expert Advice: Dealing With the Elusive Winhttp.dll Problem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-blue-screens-resulting-from-wins-intruder-exception/"><u>Quick Fixes for Blue Screens Resulting From Win's Intruder Exception</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaiming-missing-power-configurations-in-win-11-os/"><u>Reclaiming Missing Power Configurations in Win 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seize-the-deal-unmissable-black-friday-612-win10/"><u>Seize the Deal: Unmissable Black Friday - $6.12 Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-malfunctioning-office-notification-system/"><u>Solving Malfunctioning Office Notification System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-windows-11s-ms-resource-and-apperror/"><u>Solving Windows 11'S Ms-Resource and AppError</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-clearing-admin-not-allowed-message-in-os/"><u>Strategies for Clearing Admin Not Allowed Message in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackle-clutter-unwanted-windows-tools-and-how-to-eliminate-them/"><u>Tackle Clutter: Unwanted Windows Tools and How to Eliminate Them</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-guide-to-windows-1011-revamping-using-winbubble/"><u>The Complete Guide to Windows 10/11 Revamping Using WinBubble</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essentials-for-successful-intel-lan-setup-on-vista/"><u>The Essentials for Successful Intel LAN Setup on Vista</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-truth-behind-the-windows-store-dodging-digital-duplicates/"><u>The Truth Behind the Windows Store: Dodging Digital Duplicates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-fix-for-winerror-0x80072746-in-outlook/"><u>The Ultimate Fix for WinError 0X80072746 in Outlook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-resolving-battlenet-not-available-errors-on-win-1011/"><u>Tips for Resolving Battle.net Not Available Errors on Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-2023-laptop-reveals-ifa-edition/"><u>Top 2023 Laptop Reveals - IFA Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-for-no-sound-when-screencasting-with-powerpoint/"><u>Troubleshooting for No Sound when Screencasting with PowerPoint</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-secure-boot-status-a-windows-bios-solution-manual/"><u>Unlocking Secure Boot Status: A Windows BIOS Solution Manual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-transcends-platforms-iphoneipadmacpc-compatibility-announced/"><u>Windows Transcends Platforms: IPhone/iPad/Mac/PC Compatibility Announced</u></a></li>
</ul></div>
