---
title: Restore Hidden Desktop Icons on Windows 11
date: 2024-08-08T11:09:53.619Z
updated: 2024-08-09T11:09:53.619Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restore Hidden Desktop Icons on Windows 11
excerpt: This Article Describes Restore Hidden Desktop Icons on Windows 11
keywords: Windows 11 Icon Recovery,Restore Desktop Items,Hidden Icons Unveil,Win11 Icons Reinstate,Desktop Image Restoration,Icon Retrieval for Win11,Windows 11 Icon Fix
thumbnail: https://thmb.techidaily.com/dadc574a72620fb10d26a05d18b7bc541d4008da38e3f5b8b4a33a2f717ba587.jpg
---

## Restore Hidden Desktop Icons on Windows 11

 Desktop icons on Windows 11 give you quick access to your favorite apps, files, folders, and more. But what if these desktop icons vanish without a trace? How do you get the icons back?

 If you're facing this baffling problem, this guide will help you restore the missing desktop icons in Windows 11.

## 1\. Enable Show Desktop Icons

 On Windows 11, you can show or hide desktop icons with a couple of clicks. So, if you’ve accidentally hidden your desktop icons, getting them back is fairly easy.

 Right-click anywhere on an empty spot on your desktop and select**View > Show desktop icons** . Once you do that, all your hidden desktop icons should reappear.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
![Show Desktop Icons on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Show-Desktop-Icons-on-Windows-11.jpg)

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Check Desktop Icon Settings

 If you're only missing a few desktop icons, such as This PC, Recycle Bin, Control Panel, and others, you may have disabled them in the "Desktop Icon Settings" window. In that case, you can use the following steps to re-enable those desktop icons.

1. Open the**Start menu** and click the**gear icon** to launch the Settings app.
2. Select**Personalization** from the left sidebar.
3. Select**Themes** .
4. Under**Related settings** , click on**Desktop icon settings** .
5. Under the**Desktop icons** section, use the checkboxes to enable the icons you want on your desktop.
6. Click**Apply** followed by**OK** to save the changes.  
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
![Desktop Icon Settings Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Desktop-Icon-Settings-Window.jpg)

 Once you complete the above steps, your icons should appear on the desktop.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Restart Windows Explorer

 The Windows Explorer process handles the Graphical User Interface (GUI) for a number of utilities, including the desktop. If this service encounters any issues, your desktop and taskbar icons may disappear. If this is the case, you can restart the Windows Explorer process to fix the problem.

1. Right-click on the Start icon or press**Win + X** to open the Power User menu.
2. Select**Task Manager** from the list.
3. In the**Processes** tab, locate**Windows Explorer** . Right-click on it and select**Restart** .  
<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
![Restart Windows Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Restart-Windows-Explorer.jpg)

 Your taskbar will disappear for a brief moment and then reappear. Following this, your desktop icons should be visible.

## 4\. Rebuild Icon Cache

 Another reason why desktop icons on Windows may appear broken or go missing is if the existing icon cache data is corrupt. In that case, you can try clearing the corrupted icon cache data. This will force Windows to rebuild the icon cache from scratch and resolve your problem.

To rebuild icon cache on Windows 11:

1. Press**Win + S** to open the search menu.
2. Type**command prompt** in the box and select**Run as administrator** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Paste the following command in the console and press**Enter** to navigate to the directory where Windows stores the icon cache.  
`cd /d %userprofile%\AppData\Local\Microsoft\Windows\Explorer`
5. Run the following command to terminate the Explorer process:  
`taskkill /f /im explorer.exe`
6. Paste this command and press**Enter** to delete icon cache files:  
`del iconcache*`  
![Rebuild Icon Cache Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Rebuild-Icon-Cache-Windows.jpg)
7. Finally, type in the following text and hit**Enter** to restart Explorer:  
`Explorer.exe`

 Once you complete the above steps, restart your PC and see if the desktop icons appear.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
## 5\. Update Your PC’s Graphics Driver

 An outdated graphics driver on Windows can also lead to such anomalies. You can try updating the faulty driver using Device Manager to see if that helps. Here's how to do it.

1. Press**Win + S** to open the search menu.
2. Type**device manager** in the search box and select the first result that appears.
3. Expand**Display adapters** .
4. Right-click on your graphics driver and select**Update driver** .
5. Select**Search automatically for drivers** to let Windows find and install the best drivers.  
![Update Graphics Driver on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Update-Graphics-Driver-on-Windows.jpg)

 If the issue persists even after updating the driver, your graphics driver may be corrupt. In that case, you'll need to reinstall the graphics driver on your PC. Refer to our guide on[how to fix corrupt drivers on Windows](https://www.makeuseof.com/how-to-fix-corrupt-drivers-on-windows-10/) for more instructions on how to fix this.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Check the Group Policy Settings

 The Group Policy Editor lets you make various system-wide changes on your Windows computer. If desktop icons are disabled from the Group Policy Editor, you won’t be able to add or remove desktop icons no matter what you do. To fix this, you must disable this “Hide and disable all items on the desktop” from the Group Policy Editor.

 Note that you can only access the Group Policy Editor on Windows 11 Professional, Enterprise, and Education editions. If you’re running Windows 11 Home, check our guide on[how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Click the magnifying icon on the taskbar to open the search menu.
2. Type**gpedit.msc** in the box and press**Enter** . This will open the Local Group Policy Editor.
3. Use the left pane to navigate to **User Configuration > Administrative Templates > Desktop** .
4. Double-click the**Hide and disable all items on the desktop** policy on your right.
5. Select**Not configured** or**Disabled** .
6. Click**Apply** followed by**OK** .  
<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Enable Desktop Icons on Windows 11 via Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Enable-Deskop-Icons-on-Windows-11-via-Group-Policy-Editor-1.jpg)

## 7\. Perform a System Restore

 There's a chance that a recent system change is to blame for the missing desktop icons in Windows 11\. If you can't figure out what it is, you can use System Restore to restore Windows to a previous state.

Follow these steps to perform a system restore on Windows:

1. Press**Win + R** to open the Run dialog box.
2. Type**sysdm.cpl** in the box and press**Enter** .
3. Under the**System Protection** tab, click on**System Restore** .
4. Click**Next** .
5. Select a restore point before the issue first appeared and hit**Next** .
6. Click on**Finish** .  
![System Restore Dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/System-Restore-Dialog.jpg)

 Wait for Windows to reboot and revert to the specified restore point. Following that, your desktop icons should appear.

## 8\. Manually Restore the Desktop Shortcut Icons

 If your desktop icons are still missing at this point, you can try restoring them manually.

 To add an icon to the desktop in Windows 11, open the**Start menu** and click on**All apps** . Scroll down to the app you want to add to the desktop. Finally, drag the app shortcut to your desktop.

![Create Desktop Shortcut From Start Menu in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Create-Desktop-Shortcut-From-Start-Menu-in-Windows.jpg)

 Alternatively, you can create a shortcut on your desktop by using the Create Shortcut wizard. To do so, right-click anywhere on the desktop and select**New > Shortcut** . Then, click the**Browse** button to locate the file, folder, or app you want to add to your desktop. Then, click**Next** followed by**Finish** .

 We covered this topic in more detail in our guide to[how to add icons to the desktop on Windows](https://www.makeuseof.com/how-to-add-icon-to-desktop-windows/) .

## Restore the Missing Desktop Icons on Windows 11

 Hopefully, the above-mentioned solutions have helped you restore the missing desktop icons on Windows 11 and things are back to normal. However, if none of the above solutions work, you may have to reset your Windows 11 PC as a last resort.


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
<li><a href="https://on-screen-recording.techidaily.com/new-essential-knowledge-how-io-screen-recorder-works-for-2024/"><u>[New] Essential Knowledge  How Io Screen Recorder Works for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-crafting-captivating-animations-creating-gifs-from-your-favorite-youtube-videos/"><u>[New] In 2024, Crafting Captivating Animations  Creating GIFs From Your Favorite YouTube Videos</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-mastering-multimedia-strategies-for-gamers-on-youtube/"><u>[New] Mastering Multimedia Strategies for Gamers on Youtube</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-troubleshooting-tips-for-the-mystery-of-hidden-shorts-thumbnails/"><u>[New] Troubleshooting Tips for the Mystery of Hidden Shorts Thumbnails</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-the-casual-entrants-handbook-for-tiktok-lives/"><u>[Updated] 2024 Approved  The Casual Entrant's Handbook for TikTok Lives</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-efficient-broadcast-techniques-incorporating-youtube-loops-on-tv/"><u>[Updated] Efficient Broadcast Techniques  Incorporating YouTube Loops on TV</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-sound-excellence-on-a-shoestring-superior-asmr-mics-affordably/"><u>[Updated] In 2024, Sound Excellence on a Shoestring - Superior ASMR Mics Affordably</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-subtle-reduction-of-volume-in-fl-studio/"><u>[Updated] Subtle Reduction of Volume in FL Studio</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-hassle-free-tactics-sharing-igtv-in-insta-stories/"><u>2024 Approved  Hassle-Free Tactics  Sharing IGTV in Insta Stories</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-recording-success-a-step-by-step-approach-to-capturing-chats-on-messenger/"><u>2024 Approved  Recording Success  A Step-by-Step Approach to Capturing Chats on Messenger</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/5-widespread-myths-about-effective-language-acquisition/"><u>5 Widespread Myths About Effective Language Acquisition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-how-to-for-customizing-windows-11-with-widgets/"><u>A Comprehensive How-To for Customizing Windows 11 with Widgets</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-oppo-a38-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Oppo A38</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-introduction-to-windows-exepe-file-formats/"><u>An Introduction to Windows EXE/PE File Formats</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/camera-glitches-ended-by-obs-fix/"><u>Camera Glitches Ended by OBS Fix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/can-pressing-prtscn-launch-snipping-tool-steps-to-halt/"><u>Can Pressing PrtScn Launch Snipping Tool? Steps to Halt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ceasing-windows-notification-for-updates/"><u>Ceasing Windows Notification for Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-subnet-tweak-for-experienced-users-win11/"><u>Effortless Subnet Tweak for Experienced Users, Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-printer-busy-message-in-win11/"><u>Eliminating Printer Busy Message in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploiting-windows-11s-error-diagnostic-solutions/"><u>Exploiting Windows 11'S Error Diagnostic Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-hidden-options-mastery-of-lost-control-configurations/"><u>Explore Hidden Options: Mastery of Lost Control Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halt-the-haste-of-edges-tabs-in-w11/"><u>Halt the Haste of Edge's Tabs in W11</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-apple-iphone-12-pro-drfone-by-drfone-virtual-ios/"><u>How PGSharp Save You from Ban While Spoofing Pokemon Go On Apple iPhone 12 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-clear-the-focus-wallpaper-icon-on-windows-11/"><u>How to Clear the Focus Wallpaper Icon on Windows 11</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-on-oppo-a1-5g-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location on Oppo A1 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-dxgierrordeviceremoved-error-in-windows-10-and-11/"><u>How to Fix the DXGI_ERROR_DEVICE_REMOVED Error in Windows 10 & 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-a-xiaomi-civi-3-disney-100th-anniversary-edition-phone-that-is-locked-by-drfone-android/"><u>How to Reset a Xiaomi Civi 3 Disney 100th Anniversary Edition Phone that is Locked?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-infinix-note-30-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Infinix Note 30 to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-boosting-like-counts-tips-for-tiktok-unboxings/"><u>In 2024, Boosting Like Counts  Tips for TikTok Unboxings</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-life360-notify-when-you-log-out-on-itel-s23-drfone-by-drfone-virtual-android/"><u>In 2024, Does Life360 Notify When You Log Out On Itel S23? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-xiaomi-redmi-note-12-pro-5g-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Xiaomi Redmi Note 12 Pro 5G to Other Android Devices Devices? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-where-is-the-best-place-to-catch-dratini-on-itel-p55-drfone-by-drfone-virtual-android/"><u>In 2024, Where Is the Best Place to Catch Dratini On Itel P55 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-apk-deployment-for-win-11-users/"><u>Instant APK Deployment for Win 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-yourphoneexe-malware-insights-on-windows-87/"><u>Is YourPhone.exe Malware? Insights on Windows 8/7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/multiple-routes-for-opening-utilities-on-windows-systems/"><u>Multiple Routes for Opening Utilities on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-error-0x0000004e-in-windows-devices/"><u>Navigating Error 0X0000004E in Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-hazards-of-cheap-windows-key-purchases/"><u>Navigating the Hazards of Cheap Windows Key Purchases</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-windows-11-search-top-5-expert-methods/"><u>Optimize Your Windows 11 Search: Top 5 Expert Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-account-security-changing-reset-counter-after-failed-logins/"><u>Optimizing Account Security: Changing Reset Counter After Failed Logins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-discord-launch-and-update-check-with-windows-startup/"><u>Preventing Discord Launch and Update Check with Windows Startup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-ignoring-soon-expiring-licenses-alerts-in-windows/"><u>Quick Fix for Ignoring Soon Expiring Licenses Alerts in Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-motorola-moto-g-5g-2023-drfone-by-drfone-virtual-android/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Motorola Moto G 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-this-pc-cant-run-post-windows-11-setup/"><u>Rectifying 'This PC Can't Run' Post-Windows 11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-access-reactivating-ms-store-apps-in-windows-11/"><u>Regaining Access: Reactivating MS Store Apps in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remediation-steps-for-windows-sandboxs-hypervisor-not-found/"><u>Remediation Steps for Windows Sandbox's Hypervisor Not Found</u></a></li>
<li><a href="https://win11-tips.techidaily.com/running-state-of-the-art-ai-windows-edition/"><u>Running State-of-the-Art AI: Windows Edition</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-future-of-pc-gaming-meet-eizos-cg318-4k/"><u>The Future of PC Gaming  Meet EIZO's CG318-4K</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/the-power-of-multilingualism-after-age-50/"><u>The Power of Multilingualism After Age 50</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-ultimate-guide-to-photo-framing-on-the-net/"><u>The Ultimate Guide to Photo Framing on the Net</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-8-cross-platform-tools-for-microsoft-enthusiasts/"><u>Top 8 Cross-Platform Tools for Microsoft Enthusiasts</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/ultimate-mp4-uploader-for-fb/"><u>Ultimate MP4 Uploader for FB</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-windows-approach-to-allocated-ram/"><u>Understanding Windows' Approach to Allocated RAM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-windows-11-potential-via-powertoys-install/"><u>Unleashing Windows 11 Potential via PowerToys Install</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-ways-for-swift-epic-game-loading/"><u>Unveiling Windows Ways for Swift Epic Game Loading</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1011-volume-control-fix-guide/"><u>Windows 10/11 Volume Control Fix Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/your-essential-collection-of-sonys-ps5-unique-game-titles/"><u>Your Essential Collection of Sony's PS5 Unique Game Titles</u></a></li>
</ul></div>
