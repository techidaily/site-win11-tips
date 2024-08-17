---
title: Interacting with Network Drives From Smartphones
date: 2024-08-16T01:55:01.232Z
updated: 2024-08-17T01:55:01.232Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Interacting with Network Drives From Smartphones
excerpt: This Article Describes Interacting with Network Drives From Smartphones
keywords: Phone Drive Interaction,Smartphone NAS Access,Mobile NAS Connectivity,Phones With Network Storage,Remote Drives Mobile Use,Network USB Support (Mobile),Handheld NFS Access
thumbnail: https://thmb.techidaily.com/dc7ffd70cb73963a6e0b0477afa34122ac2690b6da8afae499c025285139f98c.png
---

## Interacting with Network Drives From Smartphones

 If you searched for ways to access your Windows files from your Android/iOS devices, chances are you landed on guides suggesting you to download all sorts of external applications, free or paid. Did you know that you absolutely don't need any external application for file transfers across your devices? Well, now you do. Windows Network Share is a really easy way of sharing files, folders, or entire drives across devices on the same network. Let's learn how to set up Windows Network Share to access your PC files from Android/iOS.

## What Is Network File Sharing?

 When you want to share a file or folder with someone, sometimes it is faster to share it over your local network, rather than uploading to the cloud or looking for a USB flash drive. This process is called network file sharing. File Transfer Protocol (FTP) is also a valid option for file sharing remotely or on the local network but, it's much more of a hassle to set up than Windows Network Share.

 Windows Network Share utilizes the SMB protocol internally to make files, directories, or, entire drives available for read/write access for devices on the local network. While it's super easy and swift to set up, it's also a common target for adversaries. So, it's wise that you learn [how the SMB protocol works and some common SMB vulnerabilities](https://www.makeuseof.com/what-is-smb-protocol-and-what-are-its-risks/) to ensure that your network perimeter isn't breached.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->

![Manually adding the device and account details](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/manually-adding-the-device-and-account-details.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537546&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/7_copy_2_2_hdpro.png" border="0">HD Video Converter Factory Pro</a>
<!-- affiliate ads end -->

![Access established to the drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/access-established-to-the-drive.jpg)
<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->

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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->

![Typing in the IP of the Windows PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/typing-in-the-ip-of-the-windows-pc.jpeg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->

![Typing in user account credentials](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/typing-in-user-account-credentials.jpeg)

![Access established to the drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/access-established-to-the-drive.jpeg)
<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The shared drive being listed on the Browse Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-shared-drive-being-listed-on-the-browse-menu.jpeg)
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->

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
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-audible-illusion-how-does-this-voice-change-application-work-alternatives-awaits/"><u>[New] 2024 Approved  Audible Illusion  How Does This Voice Change Application Work? Alternatives Awaits</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-correcting-obs-darkness-during-live-streams/"><u>[New] 2024 Approved  Correcting OBS Darkness During Live Streams</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-instagram-illumination-best-covered-ig-highlights-on-the-move/"><u>[Updated] 2024 Approved  Instagram Illumination  Best-Covered IG Highlights on the Move</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-securing-students-learning-mac-based-lecture-recording/"><u>[Updated] 2024 Approved  Securing Students' Learning  Mac-Based Lecture Recording</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-virtual-vs-augmented-unraveling-ar-mr-and-vr-distinctions/"><u>[Updated] 2024 Approved  Virtual Vs. Augmented  Unraveling AR, MR & VR Distinctions</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-from-zero-to-zoom-expertise-in-a-flash/"><u>[Updated] From Zero to Zoom Expertise in a Flash</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-kinemaster-mastery-sculpting-close-up-cinematic-brilliance/"><u>2024 Approved  Kinemaster Mastery  Sculpting Close-Up Cinematic Brilliance</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-fake-gps-without-root-on-infinix-note-30-5g-drfone-by-drfone-virtual-android/"><u>3 Ways to Fake GPS Without Root On Infinix Note 30 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-guide-overcoming-launch-failures-in-obs-studio/"><u>Comprehensive Guide: Overcoming Launch Failures in OBS Studio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/controlling-metrics-on-your-windows-11-wifi-networks/"><u>Controlling Metrics on Your Windows 11 Wifi Networks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-missing-essentials-issue-on-windows-11-system/"><u>Correcting 'Missing Essentials' Issue on Windows 11 System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/countering-sudden-invisibility-in-win-based-gaming/"><u>Countering Sudden Invisibility in Win-Based Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-a-unique-look-for-your-window-terminal/"><u>Crafting a Unique Look for Your Window Terminal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphraning-the-message-of-crossed-out-icons-on-files/"><u>Deciphraning: The Message of Crossed-Out Icons on Files</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-pictures-from-zte-blade-a73-5g-by-fonelab-android-recover-pictures/"><u>Easy steps to recover deleted pictures from ZTE Blade A73 5G.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-unauthorized-users-4-routines-for-restraining-windows-access/"><u>Eliminating Unauthorized Users: 4 Routines for Restraining Windows Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-track-command-management-in-windows-1011/"><u>Fast-Track Command Management in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-access-the-protected-windowsapps-folder-on-windows/"><u>How to Access the Protected WindowsApps Folder on Windows</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-system-of-apple-iphone-13-mini-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair System of Apple iPhone 13 mini? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-call-logs-from-honor-magic-6-pro-by-fonelab-android-recover-call-logs/"><u>How to rescue lost call logs from Honor Magic 6 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/implementing-robust-access-controls-via-powertoys/"><u>Implementing Robust Access Controls via PowerToys</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-do-you-get-sun-stone-evolutions-in-pokemon-for-nokia-c12-drfone-by-drfone-virtual-android/"><u>In 2024, How Do You Get Sun Stone Evolutions in Pokémon For Nokia C12? | Dr.fone</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/in-depth-evaluation-of-the-compact-and-convenient-aphaca-bt6n-for-wireless-fm-broadcasting/"><u>In-Depth Evaluation of the Compact and Convenient Aphaca BT6n for Wireless FM Broadcasting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-approaches-to-adding-items-to-win-11-contextual-menu/"><u>Innovative Approaches to Adding Items to Win 11 Contextual Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-mouse-settings-in-windows-11-with-minimal-hassle/"><u>Mastering Mouse Settings in Windows 11 with Minimal Hassle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-recovering-missing-regedit/"><u>Mastering the Art of Recovering Missing Regedit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/outsmarting-windows-logon-requirements/"><u>Outsmarting Windows Logon Requirements</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/overcoming-low-resolution-output-in-obs/"><u>Overcoming Low-Resolution Output in OBS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-steps-for-reactivating-fixed-menu-options-on-pc/"><u>Quick Steps for Reactivating Fixed Menu Options on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refreshing-graphics-drivers-on-windows-11-systems/"><u>Refreshing Graphics Drivers on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-original-windows-backup-configurations/"><u>Regaining Original Windows Backup Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-saving-woes-quickly-6-key-methods-for-powerpoint-in-windows/"><u>Resolve Saving Woes Quickly: 6 Key Methods for PowerPoint in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restrictions-on-windows-11-insider-edition-use/"><u>Restrictions on Windows 11 Insider Edition Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shed-heavy-weights-pure-power-windows-11-tiny/"><u>Shed Heavy Weights: Pure Power, Windows 11 Tiny</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-reinstallation-when-applications-dont-start-on-ms-marketplace/"><u>Strategies for Reinstallation When Applications Don't Start on MS Marketplace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-key-to-understanding-your-last-windows-use/"><u>The Key to Understanding Your Last Windows Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-leading-windows-brightness-management-apps-and-utilities/"><u>The Leading Windows Brightness Management Apps & Utilities</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-ultimate-checklist-for-smart-dash-cam-selection-a-buyers-guide/"><u>The Ultimate Checklist for Smart Dash Cam Selection: A Buyer's Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-windows-1011-icon-spacing-control-tutorial/"><u>Title: Windows 10/11 Icon Spacing Control Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-computere-clock-display-top-5-windows-screensaver-apps-for-dynamic-visuals/"><u>Transform Your Computer’e Clock Display: Top 5 Windows Screensaver Apps for Dynamic Visuals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/twinning-inboxes-gmail-plus-outlook-for-windows-users-guide/"><u>Twinning Inboxes: Gmail + Outlook for Windows Users Guide</u></a></li>
<li><a href="https://fake-location.techidaily.com/ultimate-guide-to-free-pptp-vpn-for-beginners-on-oppo-a1x-5g-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Free PPTP VPN For Beginners On Oppo A1x 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfreezing-and-restoring-itunes-on-windows-devices/"><u>Unfreezing and Restoring iTunes on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-your-pcs-onedrive-mysteries-solutions-here/"><u>Unraveling Your PC's OneDrive Mysteries: Solutions Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-secrets-of-monitoring-network-traffic-on-windows-11/"><u>Unveiling the Secrets of Monitoring Network Traffic on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-windows-11-functionality-with-a-powerful-run-feature/"><u>Upgrade Windows 11 Functionality with a Powerful Run Feature</u></a></li>
</ul></div>
