---
title: Android Linking to Windows Shared Drives
date: 2024-08-08T10:58:04.734Z
updated: 2024-08-09T10:58:04.734Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Android Linking to Windows Shared Drives
excerpt: This Article Describes Android Linking to Windows Shared Drives
keywords: Android File Sharing,Windows Share Access,Cross-Platform Drive Linking,Mobile Network Drives,PC-to-Android Data Transfer,Android External Drive Sync,Integrated OS File Sharing
thumbnail: https://thmb.techidaily.com/6d060e78cf4821c16957dc0af5764350800050d4c706e3284222e7ce2389a41f.jpg
---

## Android Linking to Windows Shared Drives

 If you searched for ways to access your Windows files from your Android/iOS devices, chances are you landed on guides suggesting you to download all sorts of external applications, free or paid. Did you know that you absolutely don't need any external application for file transfers across your devices? Well, now you do. Windows Network Share is a really easy way of sharing files, folders, or entire drives across devices on the same network. Let's learn how to set up Windows Network Share to access your PC files from Android/iOS.

## What Is Network File Sharing?

 When you want to share a file or folder with someone, sometimes it is faster to share it over your local network, rather than uploading to the cloud or looking for a USB flash drive. This process is called network file sharing. File Transfer Protocol (FTP) is also a valid option for file sharing remotely or on the local network but, it's much more of a hassle to set up than Windows Network Share.

 Windows Network Share utilizes the SMB protocol internally to make files, directories, or, entire drives available for read/write access for devices on the local network. While it's super easy and swift to set up, it's also a common target for adversaries. So, it's wise that you learn [how the SMB protocol works and some common SMB vulnerabilities](https://www.makeuseof.com/what-is-smb-protocol-and-what-are-its-risks/) to ensure that your network perimeter isn't breached.

## How to Share a Windows Drive on Your Local Network

 To access your computer's files, you need to share them on the local network. For the demonstration, I'll be sharing a drive on the local network. If you wish to share a folder or a single file instead, you can follow the same steps but with only the folder(s) and file(s) selected.

 Before you dive into the steps, it's recommended you [create a separate, local Windows user account](https://www.makeuseof.com/windows-11-create-local-user-account/) to be used solely for network drive access.

 Here are the steps to share files on the local network in Windows 10/11:

1. **Right-click** on the drive you want to share.
2. From the drop-down menu, click on **Properties**.
3. In the **Properties** menu, go to the **Sharing** tab.  
<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![sharing tab open in properties menu of a drive-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sharing-tab-open-in-properties-menu-of-a-drive-1.jpg)
4. Click on **Advanced Settings** in the new pop-up menu, check the **Share this folder** box, and wait, it's not over yet. Now to prevent unsolicited access to your locally shared drives, click on **Permissions**.
5. In the new menu that pops up, click on **Add**. Yet another box should pop up. Here, type in the username of your user account. Use a dedicated user account only for network access or use your primary account's username and press **Enter**. You should find your name is present on the list of users with permission to the shared drive.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
![Adding a new user in the access group of the shared drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adding-a-new-user-in-the-access-group-of-the-shared-drive.jpg)
6. Finally, click on your account name, and in the **Permissions for <account name>** section, check the **Full Control** box and hit **Apply**.  
![Adding permissions to the user account and confimring changes by pressing on Apply](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adding-permissions-to-the-user-account-and-confimring-changes-by-pressing-on-apply.jpg)

 That's all the steps to share your drive on the local network. However, if you run into any trouble, it's recommended you check out the [dedicated guide on enabling Windows Network Share](https://www.makeuseof.com/how-network-file-share-windows-10/).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
## How to Access Your Windows Files From an Android Device

 Now that you have shared the drive on the local network you'll be able to access your newly shared drives and files from your Android device in just a few taps. Make sure your Android device and Windows PC are connected to the same Wi-Fi network. With these checks out of the way, let's look at the steps to access Windows network shared files from Android:

1. Fire up the **Files** application on your Android device.
2. On the **Files** application, scroll to **Network Storage** and tap on it.
3. Inside **Network Storage**, tap on **Add network storage**. You might be asked to select an option from a list of protocols. Tap on **Network Drive** or any option with **SMB** in the name.
4. Your device will start to scan for locally shared drives. Wait for it to locate your Windows drive. If your device is unable to locate it follow the next steps. First, you need to [find the IP address of your Windows PC](https://www.makeuseof.com/find-ip-mac-address-windows-powershell/).
5. After noting the IP address, go back to your Android device and tap on **Add Manually**.
6. In the new window, type in the IPv4 address you copied earlier into the Address field. Then, type **445** into the **Port** field. Finally, fill in the **Username** and **Password** fields with your account credentials and hit on **Add** or **Connect**.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
![Selecting Network Share on Files app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/selecting-network-share-on-files-app.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
![Selecting SMB Protocol](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/selecting-smb-protocol.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Manually adding the device and account details](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/manually-adding-the-device-and-account-details.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
![Access established to the drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/access-established-to-the-drive.jpg)

Close

 Now, you should be able to access files on your Windows PC from your Android device. You can modify the files or download them to your Android device. All done without ever needing any external application!

 On some devices, such as Samsung phones, when you click on **Network Storage**, you might be asked to update the Files app to add the network access functionality. Proceed to do so, and then return to the guide.

## How to Access Your Windows Files From an iOS Device

 The steps to access Windows files from iOS are pretty much identical to the steps required for Android devices. Here's how you can access your Windows PC's files from iOS:

1. Before opening your iOS device. You need to grab the IP address of your Windows PC. There are multiple ways to do it. The easiest one being typing in **cmd** in the search box and then using the **ipconfig** command to fetch network-related details. Note down the value of the IPv4 field.
2. Fire up the **Files** application on your iOS device.
3. Click on the three horizontal dots (ellipsis) in the top right corner. From there, select **Connect to Server**.
4. A new window should open up asking you to input the IP address of the shared drive. Type in the IP address that you previously noted down and tap on **Next**.
5. Then, you will be prompted to enter the user account credentials to access the shared drive. Type them in and tap on **Next**.

![Connecting to the shared drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/connecting-to-the-shared-drive.jpeg)

![Typing in the IP of the Windows PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/typing-in-the-ip-of-the-windows-pc.jpeg)

![Typing in user account credentials](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/typing-in-user-account-credentials.jpeg)

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Access established to the drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/access-established-to-the-drive.jpeg)

![The shared drive being listed on the Browse Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-shared-drive-being-listed-on-the-browse-menu.jpeg)

Close

 Now you should be able to view the files on the shared drive. You can now download, upload or modify the local files on your Windows PC with ease and without having to download any third-party application.

## Access Your PC Files on iOS/Android Without Third-Party Apps

 Now that you know how to access your PC files using Windows Network Share, uploading, downloading, and modifying files should be super easy to do. You won't have to rely on downloading and testing third-party applications for minor tasks like copying over a PDF file from your Windows PC to your Android/iOS devices.

 If you wish to share files between computers on the same network, that is possible as well. But, for heavy file sharing between two computers, a few alternatives to network sharing may be worth checking out if you'll be sharing large chunks of data.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-screen-recorder-freedom-top-10-no-cost-choices-for-cameras/"><u>[New] 2024 Approved  Screen Recorder Freedom  Top 10 No-Cost Choices for Cameras</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-the-basics-for-transforming-full-size-photos-into-efficient-thumbnails/"><u>[New] 2024 Approved  The Basics for Transforming Full-Size Photos Into Efficient Thumbnails</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/n-2024-how-to-harness-youtubes-creative-commons-in-video-making/"><u>[New] In 2024, How to Harness YouTube's Creative Commons in Video Making</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-perfecting-your-rl-game-captures-for-2024/"><u>[New] Perfecting Your RL Game Captures for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-quick-and-cool-xbox-snapshots-a-gamers-bible-for-2024/"><u>[New] Quick & Cool Xbox Snapshots  A Gamers' Bible for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-securing-your-speech-on-the-ipad/"><u>[New] Securing Your Speech on the iPad</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-swiftly-uncover-unfollowers-on-instagram-for-2024/"><u>[New] Swiftly Uncover Unfollowers on Instagram for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-periscope-stars-in-snapchat-highlights/"><u>[Updated] 2024 Approved  Periscope Stars in Snapchat Highlights</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-broadcast-battle-analyzing-obs-vs-twitchs-pros-for-2024/"><u>[Updated] Broadcast Battle  Analyzing OBS Vs. Twitch's Pros for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-tips-for-quickly-and-securely-scrape-gifs-from-social-networking-sites-like-fb/"><u>[Updated] In 2024, Tips for Quickly and Securely Scrape GIFs From Social Networking Sites Like FB</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unveiling-8-premium-mp3-extraction-software-android/"><u>[Updated] Unveiling 8 Premium MP3 Extraction Software (Android)</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-perfecting-your-shots-top-tripods-for-content-creators/"><u>2024 Approved  Perfecting Your Shots  Top Tripods for Content Creators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-buyers-guide-affordable-access-to-windows-11-vcs/"><u>A Buyer’s Guide: Affordable Access to Windows 11 VCs</u></a></li>
<li><a href="https://video-capture.techidaily.com/adding-drama-to-videos-strikethrough-for-emphasis-and-clarity-for-2024/"><u>Adding Drama to Videos  Strikethrough for Emphasis and Clarity for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridge-gap-for-sd-detectability-by-explore-window/"><u>Bridge Gap for SD Detectability by Explore Window</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-forth-invisible-5ghz-connections-with-these-fixes/"><u>Bring Forth Invisible 5GHz Connections with These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/challenging-the-status-quo-embracing-individuality-in-restricted-settings/"><u>Challenging the Status Quo: Embracing Individuality in Restricted Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/concealing-taskview-in-window-11-taskbar-design/"><u>Concealing TaskView in Window 11 Taskbar Design</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-the-functionality-of-fn-keys-on-modern-pcs-windows-11/"><u>Configuring the Functionality of FN Keys on Modern PCs (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-mac-locations-on-your-windows-11-system/"><u>Deciphering MAC Locations on Your Windows 11 System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/defender-cleanup-procedures-for-a-secure-and-streamlined-pc/"><u>Defender Cleanup Procedures for a Secure and Streamlined PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-productivity-windows-11-pc-manager-tools-guide/"><u>Enhance Productivity: Windows 11 PC Manager Tools Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-error-e1-code-on-w10w11-systems/"><u>Eradicating Error E1 Code on W10/W11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-to-escape-the-slow-gpsvc-cycle/"><u>Expert Tips to Escape the Slow GPSVC Cycle</u></a></li>
<li><a href="https://youtube-help.techidaily.com/green-walls-in-grey-buildings-a-step-towards-eco-cities-for-2024/"><u>Green Walls in Grey Buildings  A Step Towards Eco-Cities for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-reactivate-an-inactive-hotspot-in-windows-11/"><u>Guidelines to Reactivate an Inactive Hotspot in Windows 11</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-iphone-14-pro-passcode-without-itunes-without-knowing-passcode-by-drfone-ios/"><u>How to Unlock iPhone 14 Pro Passcode without iTunes without Knowing Passcode?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-a-guide-oppo-find-x7-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>In 2024, A Guide Oppo Find X7 Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-critical-approaches-to-documenting-youtube-live-video/"><u>In 2024, Critical Approaches to Documenting Youtube LIVE Video</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-remove-forgotten-pin-of-your-samsung-galaxy-m34-by-drfone-android/"><u>In 2024, How to Remove Forgotten PIN Of Your Samsung Galaxy M34</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-itel-a60s-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Itel A60s to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-mastering-pc-hd-video-viewing-and-editing-with-windows-hdr-support/"><u>In 2024, Mastering PC HD Video Viewing & Editing with Windows HDR Support</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-custom-keybinds-quick-paste-in-win-1011/"><u>Master Custom Keybinds: Quick Paste in Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modern-standby-anomalies-in-the-windows-ecosystem/"><u>Modern Standby Anomalies in the Windows Ecosystem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalized-lock-pattern-creation-guide-for-windows-11-pcs/"><u>Personalized Lock Pattern Creation Guide for Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/printer-not-working-on-windows-11-heres-how-to-fix-it/"><u>Printer Not Working on Windows 11? Here's How to Fix It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-chrome-induced-system-time-missteps-windows/"><u>Rectifying Chrome-Induced System Time Missteps (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-disabling-discords-auto-checkup-at-startup/"><u>Strategies for Disabling Discord's Auto-Checkup at Startup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-ensure-complete-ram-usage-by-windows-os/"><u>Strategies to Ensure Complete RAM Usage by Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-persistent-issues-windows-obs-not-opening-troubleshooting/"><u>Tackling Persistent Issues: Windows OBS Not Opening Troubleshooting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taking-control-of-security-answers-in-windows-11-local-account/"><u>Taking Control of Security Answers in Windows 11 Local Account</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-windows-autoshrink-mechanism/"><u>Taming Window's Autoshrink Mechanism</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-secure-boot-a-comprehensive-guide-using-rufus-on-win11/"><u>Unlocking Secure Boot: A Comprehensive Guide Using Rufus on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/visual-search-enhancements-in-windows-11-file-explorer/"><u>Visual Search Enhancements in Windows 11 File Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-back-your-inactive-printer-on-pcs/"><u>Winning Back Your Inactive Printer on PCs</u></a></li>
</ul></div>
