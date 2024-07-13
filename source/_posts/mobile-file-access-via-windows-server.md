---
title: Mobile File Access via Windows Server
date: 2024-07-12T17:35:02.755Z
updated: 2024-07-13T17:35:02.755Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mobile File Access via Windows Server
excerpt: This Article Describes Mobile File Access via Windows Server
keywords: WinServer File Mobile,Remote File Access WS,Windows Server File Sharing,Mobile WS File Connect,Server-Based File Portability,WS Mobile File Reach,Interactive Window Server File
thumbnail: https://thmb.techidaily.com/f5b8e36c4ebd6a9ca109693d88c7c440e68928a27daf3516cb90c9a543d54e11.jpeg
---

## Mobile File Access via Windows Server

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
![sharing tab open in properties menu of a drive-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sharing-tab-open-in-properties-menu-of-a-drive-1.jpg)
4. Click on **Advanced Settings** in the new pop-up menu, check the **Share this folder** box, and wait, it's not over yet. Now to prevent unsolicited access to your locally shared drives, click on **Permissions**.
5. In the new menu that pops up, click on **Add**. Yet another box should pop up. Here, type in the username of your user account. Use a dedicated user account only for network access or use your primary account's username and press **Enter**. You should find your name is present on the list of users with permission to the shared drive.  
![Adding a new user in the access group of the shared drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adding-a-new-user-in-the-access-group-of-the-shared-drive.jpg)
6. Finally, click on your account name, and in the **Permissions for <account name>** section, check the **Full Control** box and hit **Apply**.  
![Adding permissions to the user account and confimring changes by pressing on Apply](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adding-permissions-to-the-user-account-and-confimring-changes-by-pressing-on-apply.jpg)

 That's all the steps to share your drive on the local network. However, if you run into any trouble, it's recommended you check out the [dedicated guide on enabling Windows Network Share](https://www.makeuseof.com/how-network-file-share-windows-10/).

## How to Access Your Windows Files From an Android Device

 Now that you have shared the drive on the local network you'll be able to access your newly shared drives and files from your Android device in just a few taps. Make sure your Android device and Windows PC are connected to the same Wi-Fi network. With these checks out of the way, let's look at the steps to access Windows network shared files from Android:

1. Fire up the **Files** application on your Android device.
2. On the **Files** application, scroll to **Network Storage** and tap on it.
3. Inside **Network Storage**, tap on **Add network storage**. You might be asked to select an option from a list of protocols. Tap on **Network Drive** or any option with **SMB** in the name.
4. Your device will start to scan for locally shared drives. Wait for it to locate your Windows drive. If your device is unable to locate it follow the next steps. First, you need to [find the IP address of your Windows PC](https://www.makeuseof.com/find-ip-mac-address-windows-powershell/).
5. After noting the IP address, go back to your Android device and tap on **Add Manually**.
6. In the new window, type in the IPv4 address you copied earlier into the Address field. Then, type **445** into the **Port** field. Finally, fill in the **Username** and **Password** fields with your account credentials and hit on **Add** or **Connect**.

![Selecting Network Share on Files app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/selecting-network-share-on-files-app.jpg)

![Selecting SMB Protocol](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/selecting-smb-protocol.jpg)

![Manually adding the device and account details](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/manually-adding-the-device-and-account-details.jpg)

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
<li><a href="https://blog-min.techidaily.com/how-to-sign-a-pdf-v17-document-with-digital-signature-software-by-ldigisigner-sign-a-pdf-sign-a-pdf/"><u>How to sign a PDF v1.7 document with digital signature software</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/break-free-from-youtube-with-these-best-27-video-streamers-for-2024/"><u>Break Free From YouTube with These Best 27 Video Streamers for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/6-solutions-to-fix-error-505-in-google-play-store-on-google-pixel-8-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Solutions to Fix Error 505 in Google Play Store on Google Pixel 8 Pro | Dr.fone</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/unlock-the-power-of-green-screen-top-10-free-apps-for-android-and-ios-for-2024/"><u>Unlock the Power of Green Screen Top 10 Free Apps for Android & iOS for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-overcome-flaws-with-non-working-ccleaner-in-win1011/"><u>Techniques to Overcome Flaws with Non-Working CCleaner in Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-inaccessible-folder-issue-fix-steps-for-windows-based-pcs/"><u>Solving 'Inaccessible Folder' Issue: Fix Steps for Windows-Based PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-savings-with-w11-pro-key-access-prime-deals/"><u>Elevate Savings with W11 Pro Key: Access Prime Deals</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-samsung-galaxy-xcover-7-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Samsung Galaxy XCover 7 Without Password | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-the-prime-8-video-cutter-tools-on-windows/"><u>Discover the Prime 8 Video Cutter Tools on Windows</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-choosing-the-best-video-editor-gopro-hero-vs-polaroid-cube/"><u>2024 Approved  Choosing the Best Video Editor  GoPro Hero Vs. Polaroid Cube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-your-non-operational-windows-11-hotspot/"><u>Activating Your Non-Operational Windows 11 Hotspot</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-nokia-c22-drfone-by-drfone-virtual/"><u>In 2024, 9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Nokia C22 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-wintoys-a-brief-dive-into-a-formidable-windows-feature/"><u>Discovering WinToys: A Brief Dive Into a Formidable Windows Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-your-music-librarys-mp3-files-to-windows-audible-cds-with-imgburn/"><u>Streamlining Your Music Library's MP3 Files to Windows' Audible CDs with ImgBurn</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-balance-of-swiftness-and-security-on-spotify-sounds/"><u>In 2024, The Balance of Swiftness and Security on Spotify Sounds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-smooth-windows-11-display-transitions/"><u>Steps for Smooth Windows 11 Display Transitions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719365826035-resolve-camera-woes-in-windows-heres-how/"><u>Resolve Camera Woes in Windows, Here’s How!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-what-to-anticipate-with-the-discontinuation-of-its-taskbar-chatting-feature/"><u>Windows 11: What to Anticipate With the Discontinuation of Its Taskbar Chatting Feature</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-pro-tools-for-pc-gamers-screen-record-windows-10/"><u>[New] 2024 Approved  Pro Tools for PC Gamers  Screen Record Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-error-0x8000ffff-in-windows-based-printers/"><u>Conquering Error 0X8000FFFF in Windows-Based Printers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-into-the-depth-of-complete-screenshots-via-windows-snipping-tool/"><u>Dive Into the Depth of Complete Screenshots via Windows' Snipping Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unseen-storage-hiding-files-via-image-camouflage-windows-11-style/"><u>Unseen Storage: Hiding Files via Image Camouflage, Windows 11 Style</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-xs-without-passcode-or-face-id-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone XS without Passcode or Face ID</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-fingerprint-scanner-compatibility-problem-in-windows/"><u>Solving Fingerprint Scanner Compatibility Problem in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-ineffective-windowed-discord-searches/"><u>Solutions for Ineffective Windowed Discord Searches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-error-code-0xa00f4289-for-webcams-on-w1011/"><u>Unraveling Error Code 0xA00F4289 for Webcams on W10/11</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-balancing-intense-beats-with-fl-studios-easeful-dimming/"><u>2024 Approved  Balancing Intense Beats with FL Studio's Easeful Dimming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-work-with-multiple-displays-in-win11/"><u>Elevate Your Work with Multiple Displays in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719319638119-collectors-paradise-unlocked-free-windows-11-for-keys-fan-year-round/"><u>Collector’s Paradise Unlocked: Free Windows 11 For Keys Fan, Year-Round!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-personalized-window-pin-creation/"><u>The Ultimate Guide to Personalized Window PIN Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-way-to-unlink-wi-fi-on-windows-11/"><u>Efficient Way to Unlink Wi-Fi on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unmask-the-hidden-storage-issues-in-windows/"><u>Unmask the Hidden Storage Issues in Windows</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-gps-location-on-vivo-y77t-easily-and-safely-drfone-by-drfone-virtual-android/"><u>How to Change GPS Location on Vivo Y77t Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-windows-storage-without-overwriting-data/"><u>Elevate Windows Storage Without Overwriting Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-kali-perfectly-integrating-linux/"><u>Win-Kali: Perfectly Integrating Linux</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-perplexity-of-non-existent-drive-letters-in-windows-systems/"><u>The Perplexity of Non-Existent Drive Letters in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-peek-at-the-finest-laptops-from-ifa-2023/"><u>A Peek at the Finest Laptops From IFA 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-security-implementing-controlled-access-in-windows/"><u>Command Security: Implementing Controlled Access in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-easy-installation-of-microsofts-application-packages/"><u>Unveiling The Easy Installation of Microsoft's Application Packages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/yourphoneexe-on-windows-benefits-and-risks-explored/"><u>YourPhone.exe on Windows - Benefits & Risks Explored</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-wsl-factor-in-the-linux-desktop-landscape/"><u>The WSL Factor in the Linux Desktop Landscape</u></a></li>
<li><a href="https://win11-tips.techidaily.com/vanishing-act-taskview-on-taskbar-hiding/"><u>Vanishing Act: TaskView on Taskbar Hiding</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unifying-partitions-in-windows-step-by-step-methods/"><u>Unifying Partitions in Windows: Step-by-Step Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-5-strategies-to-eradicate-failed-rpc-in-windows/"><u>Top 5 Strategies to Eradicate Failed RPC in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-how-you-use-the-mouse-cross-border-efficiency-via-powertoys/"><u>Transforming How You Use the Mouse: Cross-Border Efficiency via PowerToys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/craft-the-perfect-christmas-look-in-windows-11/"><u>Craft the Perfect Christmas Look in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-key-to-winning-transforming-your-pc-into-a-powerhouse-for-ps1-gaming/"><u>The Key to Winning: Transforming Your PC Into a Powerhouse for PS1 Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-ancient-game-visuals-using-retroarch-shader-magic/"><u>Transforming Ancient Game Visuals Using RetroArch Shader Magic</u></a></li>
</ul></div>
