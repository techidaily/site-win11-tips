---
title: The Ultimate Fix for WinError 0X80072746 in Outlook
date: 2024-06-25T17:09:25.904Z
updated: 2024-06-26T17:09:25.904Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/time-capsules-unlocked-exploring-7-features-from-bygone-windows/"><u>Time Capsules Unlocked: Exploring 7 Features From Bygone Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slaying-windows-beast-error-code-0xc00ce556/"><u>Slaying Window's Beast Error: Code 0xC00CE556</u></a></li>
<li><a href="https://win11-tips.techidaily.com/designing-a-lasting-deletion-feature-for-windows-desktop-trash/"><u>Designing a Lasting Deletion Feature for Windows Desktop Trash</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-erratic-read-only-file-behavior-on-win11/"><u>Fixing Erratic Read-Only File Behavior on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crucial-cross-platform-tools-windows-meets-android/"><u>Crucial Cross-Platform Tools: Windows Meets Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/routine-steps-to-engage-windows-11s-calculator/"><u>Routine Steps to Engage Windows 11'S Calculator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-reduce-cpu-and-ram-overuse-by-unrealcefsubprocess-on-systems/"><u>Strategies to Reduce CPU and RAM Overuse by UnrealCEFSubprocess on Systems</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-optimal-zoom-settings-for-microsoft-teams-communication/"><u>[Updated] Optimal Zoom Settings for Microsoft Teams Communication</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-mastering-lut-applications-in-premiere-pro/"><u>[New] Mastering LUT Applications in Premiere Pro</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-make-every-minute-count-with-these-15-engaging-activities-while-listening-to-podcasts/"><u>2024 Approved  Make Every Minute Count with These 15 Engaging Activities While Listening to Podcasts</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-from-high-speed-to-serenity-making-captivating-slow-movies-on-instagram/"><u>[Updated] From High-Speed to Serenity  Making Captivating Slow Movies on Instagram</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-nokia-c300-drfone-by-drfone-virtual-android/"><u>What is the best Pokemon for pokemon pvp ranking On Nokia C300? | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/fix-xiaomi-redmi-note-12-pro-4g-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Xiaomi Redmi Note 12 Pro 4G Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-change-location-on-yik-yak-for-your-asus-rog-phone-8-pro-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>In 2024, Change Location on Yik Yak For your Asus ROG Phone 8 Pro to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-catchy-counterpoint-the-best-backwards-song-videos-of-this-year/"><u>New Catchy Counterpoint The Best Backwards Song Videos of This Year</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>