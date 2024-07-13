---
title: The Ultimate Fix for WinError 0X80072746 in Outlook
date: 2024-07-12T17:42:46.549Z
updated: 2024-07-13T17:42:46.549Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Ultimate Fix for WinError 0X80072746 in Outlook
excerpt: This Article Describes The Ultimate Fix for WinError 0X80072746 in Outlook
keywords: WinError Repair Outlook,Outlook Error 0X80072746,Fixing Outlook Crash Error,ZeroX80072746 Outlook Troubleshoot,Resolve Outlook Corrupted Files,Outlook Error Code 0X80072746 Fix,WinError Fix in Microsoft Office
thumbnail: https://thmb.techidaily.com/c3feb7e5b167df5f057578cdbf724989b5f25148052cd8949359804b1109e7ca.png
---

## The Ultimate Fix for WinError 0X80072746 in Outlook

 The Mail app error 0x80072746 often occurs when users try to access their newly received emails, and it indicates network-related issues within Windows. This error message typically points towards a problem with the mail server or the network connection.

 Below, we take a look at the different troubleshooting methods that can help fix this issue for good.

## 1\. Allow svchost.exe in the Firewall

 The 0x80072746 error in the Mail app commonly occurs when a third-party firewall interferes with a critical Windows program called svchost.exe.

 This process is responsible to host various essential services necessary for the proper functioning of your Windows operating system. Among these services, the Mail app heavily relies on svchost.exe to establish network connections and download messages.

 If you have installed a third-party security program on your computer, there is a possibility that it is mistakenly blocking svchost.exe. This might be preventing the Mail app from fetching or sending emails, leading to the 0x80072746 error.

 To address this issue, you can check your firewall settings and whitelist svchost.exe. Alternatively, you can [temporarily disable the security program](https://www.makeuseof.com/windows-features-error-0x80071a90/) and check if that fixes the problem.

![Disable antivirus in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-antivirus-windows.jpg)

 It's worth noting that the exact steps of performing this action can vary depending on the specific program you are using. Typically, this information is available in the application settings of the app.

## 2\. Modify VPN Settings

 Active VPNs can also interfere with the Mail app's ability to establish network connections, leading to the problem at hand.

 If you are using a VPN on your computer, you can try the following steps to troubleshoot the issue:

* **Disconnect from the VPN**: Temporarily disable the VPN and then try loading messages in the Mail app again. If this fixes the problem, it implies that VPN was causing the problem.
* **Whitelist Mail app or email server**: Launch the VPN settings and look to whitelist the Mail app or email server’s IP address to prevent VPN from interfering with the program’s network connections.
* **Modify VPN protocols or settings**: If it is essential to use the VPN while using the Mail app, you can modify the protocol and check if that makes any difference.

 Here is how you can modify the VPN settings to resolve the Mail app error:

1. Press the **Win** \+ **I** keys together to open the Settings app.
2. Choose **Network & Internet** \> **VPN**.  
![VPN settings in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/vpn-settings-windows.jpg)
3. Enable the **Allow VPN over metered network** option.  
![Allow VPN over metered network in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/vpn-over-metered-network.jpg)
4. Now, head over to the "Related settings" section and choose **Change adapter options**.
5. Right-click on your LAN (Wi-Fi) connectivity and choose **Properties** from the context menu.
6. Select **Internet Protocol Version 6 (TCP/PV6)** and click **OK** to save the changes.

 You can now close the Settings app and check if the issue is resolved.

## 3\. Set Up Your Account Manually

 Another reason behind the Mail error 0x80072746 is incorrect server settings and incompatibility with specific email providers, which typically occurs when you rely on the automatic setup process.

 You can eliminate these potential issues with the automatic configuration process by setting up your account manually.

 Therefore, if you previously configured your Mail account using the automatic setup process, you might want to try setting it up manually this time in order to bypass any errors or conflicts.

 Here is how you can do that:

1. Launch the Mail client and click on the **gear icon** at the bottom.
2. Choose **Manage Accounts**.  
![Manage accounts option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/manage-accounts.jpg)
3. Select the problematic email and choose **Delete account from this device** from the options available.  
![Delete the account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/delete-mail-app.jpg)
4. Confirm your action in the next window.
5. Once the email account is removed, launch the official website of your email provider and copy the manual settings for IMAP. If these settings are not available, choose POP3\.

1. Now, head back to the Mail client and launch the settings.
2. Head over to the Manage Account section and choose **Add account**.  
![Add account option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/add-account.jpg)
3. Scroll down and choose **Advanced Setup**.  
![Choose Advanced setup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/advanced-setup-option.jpg)
4. Click on **Internet email** and enter the manual settings you copied earlier.  
![Click Internet email](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/internet-email-option.jpg)
5. Finally, click on **Sign in** and check if the issue is resolved.

## 4\. Update the Mail App

 Your Mail app might also be outdated, which is preventing it from being fully compatible with the latest email server configurations and security protocols, leading to the error at hand.

 To check if this is the case, you can head over to Microsoft Store and check for the pending updates that might be available for the Mail app. If you find any, take your time to install them and then check if the Mail app can display emails.

 Follow these steps to proceed:

1. Click on the **Microsoft Store icon** in the taskbar to launch the program.
2. Choose the **Library icon** in the bottom left pane.
3. In the following window, click on the **Get updates** button. This should display all the available updates for the installed apps. MS Store will begin to download them automatically.  
![The Get updates button in MS Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-get-updates-button.jpg)
4. Wait for the updates to download and check if the problem is resolved.

 While you are at it, we also recommend installing any system updates that might be available in the Settings app.

## 5\. Fix Corruption Issues Within the Mail App

 If updating the application did not help, there are also some other fixes that can help you resolve any corruption issues within the Mail app that might be leading to the problem. This involves [repairing and resetting the Mail application](https://www.makeuseof.com/mail-app-cant-get-mail-windows/).

 The Repair option attempts to fix any damaged or missing files that might be contributing to the error, while the Reset option will restore the default, error-free state of the application. It is important to note, however, that while these solutions are effective at fixing the underlying problem, you are likely to lose your settings and preferences within the Mail app.

## Multiple Ways to Fix the Windows Mail App

 Encountering issues with the Mail app can be incredibly frustrating, especially if you rely on it for your important work. Hopefully, the solutions listed above will help you fix the 0x80072746 error once and for all.

 To avoid problems like this from occurring in the future, we recommend keeping your Mail app up-to-date and whitelisting it in the firewall as well as the VPN.

 Below, we take a look at the different troubleshooting methods that can help fix this issue for good.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://audio-shaping.techidaily.com/2024-approved-essential-directories-the-premier-10-sites-for-acquiring-montage-soundtracks/"><u>2024 Approved Essential Directories The Premier 10 Sites for Acquiring Montage Soundtracks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-network-drive-management-with-ease-and-security-win11/"><u>Master Network Drive Management with Ease and Security (Win11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-unresponsive-windows-outlook-conditional-rules/"><u>Overcoming Unresponsive Windows Outlook Conditional Rules</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-desktop-arrangement-including-this-pc-icons/"><u>Efficient Desktop Arrangement: Including 'This PC' Icons</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/the-updated-method-to-bypass-zte-frp-by-drfone-android/"><u>The Updated Method to Bypass ZTE FRP</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/best-practices-for-incorporating-b-footage-in-projects/"><u>Best Practices for Incorporating B-Footage in Projects</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-essential-7-dslrs-to-elevate-virtual-presentations-and-broadcasts/"><u>[Updated] 2024 Approved  Essential 7 DSLRs to Elevate Virtual Presentations & Broadcasts</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-vivo-y78plus-drfone-by-drfone-virtual-android/"><u>A Detailed Guide on Faking Your Location in Mozilla Firefox On Vivo Y78+ | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-pause-life360-location-sharing-for-apple-iphone-7-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, How To Pause Life360 Location Sharing For Apple iPhone 7 Plus | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/discerning-true-value-from-recordcasts-promises/"><u>Discerning True Value From RecordCast’s Promises</u></a></li>
<li><a href="https://win11-tips.techidaily.com/implications-of-removing-windows-11-taskbar-chat-on-your-usage-experience/"><u>Implications of Removing Window's 11 Taskbar Chat on Your Usage Experience</u></a></li>
<li><a href="https://extra-information.techidaily.com/zoomed-up-videos-top-10-editor-recommendations/"><u>Zoomed Up Videos  Top 10 Editor Recommendations</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-the-ultimate-cheat-sheet-essentials-for-vlc-and-mac/"><u>[Updated] The Ultimate Cheat Sheet  Essentials for VLC and Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-your-digital-experience-with-active-windows-11-notifications/"><u>Maximizing Your Digital Experience with Active Windows 11 Notifications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-update-failures-strategies-for-error-0x30017/"><u>Overcoming Windows Update Failures: Strategies for Error 0X30017</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-profits-via-windows-11-pro-key-offers/"><u>Elevate Profits via Windows 11 Pro Key Offers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-onedrive-errors-an-easy-guide/"><u>Overcoming Windows OneDrive Errors: An Easy Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silence-missed-specification-alert-on-windows-11/"><u>Silence Missed Specification Alert on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-frozen-wastebin-symbol-on-win11/"><u>Reactivating Frozen Wastebin Symbol on Win11</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-sync-audio-with-video-with-filmora/"><u>Updated Sync Audio With Video With Filmora</u></a></li>
<li><a href="https://extra-resources.techidaily.com/unplug-and-replay-twitch-livestream-techniques/"><u>Unplug and Replay  Twitch Livestream Techniques</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-honor-90-pro-drfone-by-drfone-virtual-android/"><u>Fixing Foneazy MockGo Not Working On Honor 90 Pro | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-enhancing-your-video-cover-images-updating-techniques-for-fb-for-2024/"><u>[New] Enhancing Your Video Cover Images  Updating Techniques for FB for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-real-time-response-on-windows-discord/"><u>Enhancing Real-Time Response on Windows Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-spooler-not-running-issue-in-microsoft-os/"><u>Correcting Spooler Not Running Issue in Microsoft OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-outlook-crashed-with-simple-solutions-windows-edition/"><u>Conquering Outlook Crashed with Simple Solutions, Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-to-do-restoring-lost-sync-credentials-effectively/"><u>Microsoft To-Do: Restoring Lost Sync Credentials Effectively</u></a></li>
<li><a href="https://android-frp.techidaily.com/ultimate-guide-on-lava-yuva-3-frp-bypass-by-drfone-android/"><u>Ultimate Guide on Lava Yuva 3 FRP Bypass</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-group-policies-in-windows-via-tripartite-lens/"><u>Exploring Group Policies in Windows via Tripartite Lens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11-discord-install-failure/"><u>Overcoming Windows 11 Discord Install Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-solution-for-0x80072af9-issue/"><u>Mastering Solution for 0X80072AF9 Issue</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-channel-flair-free-download-templates/"><u>[Updated] 2024 Approved  Channel Flair  Free Download Templates</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-elevate-your-video-content-with-these-free-stabilization-tools-for-2024/"><u>Updated Elevate Your Video Content with These Free Stabilization Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/captivating-christmas-vistas-with-window-artistry/"><u>Captivating Christmas Vistas with Window Artistry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-installation-issues-with-windows-11-troubleshooter/"><u>Solving Installation Issues with Windows 11 Troubleshooter</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-evaluating-mr-beasts-monetary-world/"><u>[Updated] Evaluating Mr. Beast's Monetary World</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-back-your-game-fixing-lol-connection-failure/"><u>Bringing Back Your Game: Fixing LoL Connection Failure</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-leaders-in-fan-following-top-10-global-youtubers-subs/"><u>2024 Approved  The Leaders in Fan Following  Top 10 Global YouTubers' Subs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-subnet-changes-in-win11/"><u>Navigating Subnet Changes in Win11</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-make-the-most-of-your-apple-iphone-11-pro-lock-screen-with-notifications-drfone-by-drfone-ios/"><u>How to Make the Most of Your Apple iPhone 11 Pro Lock Screen with Notifications? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-endless-login-prompts-on-windows-os/"><u>Bypassing Endless Login Prompts on Windows OS</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-frp-on-samsung-galaxy-a14-5g-by-drfone-android/"><u>In 2024, How to Bypass FRP on Samsung Galaxy A14 5G?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-reinstalling-microsoft-store-apps/"><u>Guide to Reinstalling Microsoft Store Apps</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-how-to-seamlessly-convert-and-download-pinterest-videos-as-mp3/"><u>[Updated] How to Seamlessly Convert and Download Pinterest Videos as MP3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-recover-faulty-windows-file-organizer/"><u>Methods to Recover Faulty Windows File Organizer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathe-life-back-into-your-pcs-arrow-keys/"><u>Breathe Life Back Into Your PC's Arrow Keys</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/planning-to-use-a-pokemon-go-joystick-on-nokia-g22-drfone-by-drfone-virtual-android/"><u>Planning to Use a Pokemon Go Joystick on Nokia G22? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steering-clear-of-low-performance-pitfalls-intel-gpu-resolution/"><u>Steering Clear of Low-Performance Pitfalls: Intel GPU Resolution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-awful-chrome-glitches-on-microsoft-os/"><u>Fixing Awful Chrome Glitches on Microsoft OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-functional-read-aloud-in-office-suite-word/"><u>Fixing Non-Functional Read Aloud in Office Suite (Word)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pushing-the-limits-of-solid-state-drives-on-windows-with-ssdfresh/"><u>Pushing the Limits of Solid State Drives on Windows with SSDFresh</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-the-ultimate-guide-for-gopro-professionals-for-2024/"><u>[Updated] The Ultimate Guide for GoPro Professionals for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-map-integration-in-windows/"><u>Mastering Map Integration in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ignite-old-pcs-with-windows-11-version-22h2/"><u>Ignite Old PCs with Windows 11 Version 22H2</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-starting-with-a-gopro-essential-upgrades-for-new-filmmakers/"><u>In 2024, Starting with a GoPro  Essential Upgrades for New Filmmakers</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-soundcheck-evaluation/"><u>[New] SoundCheck Evaluation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-storage-disks-in-windows-os/"><u>Deciphering Storage Disks in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-server-disruptions-and-ms-store-issues-on-windows-11-and-11/"><u>Remedy for Server Disruptions and MS Store Issues on Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-nullified-network-visibility-in-windows/"><u>Navigating Through Nullified Network Visibility in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-system-integration-windows-plus-kali-linux-setup/"><u>Conquering System Integration: Windows + Kali Linux Setup</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-bargain-bin-chinese-vr-technology/"><u>[Updated] Bargain Bin  Chinese VR Technology</u></a></li>
</ul></div>
