---
title: Navigating Android to Windows Shared Drives
date: 2024-07-12T16:55:24.677Z
updated: 2024-07-13T16:55:24.677Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Android to Windows Shared Drives
excerpt: This Article Describes Navigating Android to Windows Shared Drives
keywords: Android File Transfer,Switch OS for Sharing,Jump Between OS,Share Data Across Systems,Cross-Platform Drive Access,OS File Syncing,Dual OS Shared Storage
thumbnail: https://thmb.techidaily.com/d31e8723e03acf63385b6b2673e7168286d60ba0c51b363448b469a8ffe4640d.jpg
---

## Navigating Android to Windows Shared Drives

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
<li><a href="https://win11-tips.techidaily.com/rethinking-default-browsing-in-newest-windows-os/"><u>Rethinking Default Browsing in Newest Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-and-utilizing-toolbar-features-in-microsofts-pcm-win11/"><u>Navigating and Utilizing Toolbar Features in Microsoft's PCM Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-your-systems-graphics-with-windows-11-tips/"><u>Revive Your System's Graphics with Windows 11 Tips</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/high-quality-video-communication-ranking-the-top-10-mobile-apps-for-2024/"><u>High-Quality Video Communication  Ranking the Top 10 Mobile Apps for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/ultimate-guide-to-nullifying-auditory-elements-in-windows-clips-for-2024/"><u>Ultimate Guide to Nullifying Auditory Elements in Windows Clips for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-unearthing-old-facebook-tales-an-easy-to-follow-device-method-for-2024/"><u>[Updated] Unearthing Old Facebook Tales  An Easy-to-Follow Device Method for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-typing-snippets-and-hotkeys-on-windows/"><u>Streamline Your Typing: Snippets & Hotkeys on Windows</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-best-top-rated-video-animation-software-for-smartphones-and-tablets/"><u>New 2024 Approved Best Top-Rated Video Animation Software for Smartphones and Tablets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-windows-pc-select-prime-clock-saver-programs/"><u>Transform Windows PC – Select Prime Clock Saver Programs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-restore-deleted-run-logs/"><u>Methods to Restore Deleted Run Logs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimizing-browser-heft-comparing-best-options-for-low-ram-usage/"><u>Minimizing Browser Heft: Comparing Best Options for Low RAM Usage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-innovators-guide-leveraging-windows-11-widgets/"><u>Tech Innovators Guide: Leveraging Windows 11 Widgets</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/efficient-solutions-for-youtube-short-snags/"><u>Efficient Solutions for YouTube Short Snags</u></a></li>
<li><a href="https://article-tips.techidaily.com/mastering-quantum-hdr-techniques-for-professionals-for-2024/"><u>Mastering Quantum HDR Techniques for Professionals for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shift-key-woes-try-these-fixes-now/"><u>Shift Key Woes? Try These Fixes Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-playback-launching-windows-media-player/"><u>Streamline Playback: Launching Windows Media Player</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steering-with-apple-maps-from-a-pc/"><u>Steering with Apple Maps From a PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/supercharge-your-pc-top-5-windows-speed-solutions/"><u>Supercharge Your PC: Top 5 Windows Speed Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-to-optimize-msi-startstop-functionality/"><u>Tactics to Optimize MSI Start/Stop Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11-read-only-folder-issues/"><u>Overcoming Windows 11 Read-Only Folder Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/time-capsules-unlocked-exploring-7-features-from-bygone-windows/"><u>Time Capsules Unlocked: Exploring 7 Features From Bygone Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-network-hurdles-reconnecting-lele-on-pc/"><u>Navigating Network Hurdles: Reconnecting LeLë on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/system-repair-exploration-sifting-through-disms-role-with-chkdsksfc/"><u>System Repair Exploration: Sifting Through DISM's Role with CHKDSK/SFC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-teams-speed-and-efficiency-upgrade/"><u>Microsoft Teams' Speed & Efficiency Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-frozen-volume-shadows-in-operating-systems/"><u>Tackling Frozen Volume Shadows in Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-digital-management-with-windows-automatic-file-disposal/"><u>Simplify Digital Management with Windows' Automatic File Disposal</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-becoming-a-pro-at-using-zoom-on-win10-systems/"><u>In 2024, Becoming a Pro at Using Zoom on WIN10 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-gmail-plus-outlook-in-one-window-windows/"><u>Step-by-Step Guide: Gmail + Outlook in One Window, Windows</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-simplify-your-audio-life-master-vrecorder-installs/"><u>[Updated] Simplify Your Audio Life - Master VRecorder Installs</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-camtasia-vs-captivate-which-to-choose-in-2024/"><u>New Camtasia Vs Captivate - Which to Choose, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-hidden-wins-must-use-secrets-in-windows-11/"><u>Uncovering Hidden Wins: Must-Use Secrets in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-change-windows-startpage-configuration/"><u>Steps to Change Windows Startpage Configuration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secrets-to-effortless-transitions-into-game-fullscreen/"><u>Secrets to Effortless Transitions Into Game FullScreen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-efficiency-essential-7-strategies-in-windows-11-38/"><u>Maximizing Efficiency: Essential 7 Strategies in Windows 11 (38)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-resource-allocation-within-wsl-android-environment/"><u>Tailoring Resource Allocation Within WSL-Android Environment</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-do-realme-11-5g-screen-sharing-drfone-by-drfone-android/"><u>How To Do Realme 11 5G Screen Sharing | Dr.fone</u></a></li>
</ul></div>
