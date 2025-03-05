---
title: "Overcoming Stuck PIN on Windows 10 & 11: A Step-by-Step Guide"
date: 2025-02-27T17:43:52.361Z
updated: 2025-03-05T02:39:05.946Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Overcoming Stuck PIN on Windows 10 & 11: A Step-by-Step Guide"
excerpt: "This Article Describes Overcoming Stuck PIN on Windows 10 & 11: A Step-by-Step Guide"
keywords: Fixing PIN Lock,Unlock Windows Screen,Troubleshoot PIN Access,Bypass Windows Pin Error,Resolve PIN Halt,Ease Windows PIN Entry,Guide to Clear PIN Lock
thumbnail: https://thmb.techidaily.com/01edaba53137429381532b08b94562d4a741359e1c28374d3f1b3c538848d74c.jpg
---

## Overcoming Stuck PIN on Windows 10 & 11: A Step-by-Step Guide

 Is your Windows Hello PIN not being accepted by Windows? In most cases, it occurs when you enter the wrong PIN. Other factors that could contribute to this issue include corruption of the Ngc folder, a problem with your Microsoft or local accounts, or misconfigured PIN settings in the Group Policy Editor.

 Likewise, not updating your operating system for long, being infected with malware, or corrupted system files can also prevent your login PIN from working. If you're having trouble logging in to your device using your Windows Hello PIN, give the following solutions a shot.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Ensure You Aren't Entering the Incorrect PIN

 You could simply be entering the wrong PIN, which is the first possible cause of your PIN not working. To eliminate this possibility, reset your PIN once.

 Your computer must be connected to an active internet connection to reset your PIN. Therefore, turn on your computer and ensure that the internet is connected. To reset your PIN, go to the profile's login page and click on **I forgot my PIN**.

![Clicking on I Forgot My PIN in Windows Home Screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/Clicking-on-I-Forgot-My-PIN-in-Windows-Home-Screen.jpg)

 You can either reset the PIN by verifying your identity with your Microsoft account password or choose an alternative sign-in option by clicking **Send code**, which sends a code to your email address.

![Windows Notifying About Receiving the Code to Reset Pin on the Windows Login Screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/Windows-Notifying-About-Receiving-the-Code-to-Reset-Pin-on-the-Windows-Login-Screen-Censor-1.jpg)

 If you select the latter option, enter the code you received by email and click **Continue**. Windows will direct you to enter a new PIN here, so enter it, confirm it once, and click **OK**.

![Adding a New Pin to Change the Old One in Windows Login Screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/Adding-a-New-Pin-to-Change-the-Old-One-in-Windows-Login-Screen.jpg)

 Restart your computer once more, add your new PIN on the login screen, and try logging in again to make sure it was the wrong PIN that wasn't letting you enter the computer previously. You are good to go if you can log in this time - just don't forget your new PIN.

 If the PIN again does not work after resetting and you are sure that the PIN you are entering is correct, the problem may reside elsewhere. Therefore, use an alternate way to log in to your account and then rule out other possibilities.

## 2\. Sign-In Using Alternative Methods

 If resetting the PIN from the login screen does not resolve the issue, you can use your account password instead. To do that, follow the below steps:

1. Click **Sign-in options** to view other options for logging in.
2. Click the **key icon**, which is usually located on the left.  
![sign in options windows 11 password](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sign-in-options-windows-11-password.jpg)
3. Type the password associated with your account here.

 Once logged in, you can start applying the remaining fixes.

 If you don't remember your account password, you can reset it just like you can your PIN. Unlike resetting the PIN, resetting the password mostly goes smoothly and lets you sign in.

## 3\. Delete the Ngc Folder in Windows

 Windows stores all your PIN-related settings in this folder, so if the OS isn't accepting your PIN, which is correct, you should delete this folder. This process will wipe out all PIN-related data from the OS. You can then set up a new PIN, which should work fine.

 You can delete the Ngc folder by following these steps:

1. Log in to your administrator account.
2. Navigate to **C: drive > Windows> ServiceProfiles > LocalService > AppData > Local> Microsoft**.
3. Locate the Ngc folder, right-click on it, and hit **Delete**.  
![Deleting Ngc Folder in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/Deleting-Ngc-Folder-in-Windows-10-Edit.jpg)

 Navigate to **Settings > Accounts > Sign-in options** to set up a new PIN after deleting the old one. Afterward, click on **Windows Hello PIN**, add a new PIN, and hopefully, the PIN will start working on your operating system.

![Windows Hello PIN In Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/3-Windows-Hello-PIN-In-Windows-Settings-App.jpg)

 If this fix also doesn't resolve the issue, it lies somewhere else that needs to be investigated further.

## 4\. Rule Out User Account Specific Issues

 When troubleshooting PIN issues, it's essential to rule out account-specific problems first. To begin with, check that the problem does not persist on a single Microsoft account. The best way to confirm this is to switch to a local account. To do that, follow the below steps:

1. Open the Windows Settings app.
2. Go to **Accounts**.
3. Navigate to **Your info** in the left-sidebar.
4. Click on **Sign in with a local account instead**.  
![changing accounts settings in windows 10 settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/changing-accounts-settings-in-windows-10-settings-app-edit.jpg)
5. Click on **Next**.

6. Enter your PIN.
7. Set up your local account by adding your username and password.
8. Once done, hit **Next**.  
![Setting Up Local Account in Windows 10 Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/2-Setting-Up-Local-Account-in-Windows-10-Settings-App.jpg)
9. Click on **Sign out and finish**.

 By following the above steps, you will return to the login screen. Type in your PIN again to confirm it works. If it does, it's your Microsoft account that is to blame. Creating another user account and checking if the PIN works there could help confirm that.

 Therefore, if the issue originates from your Microsoft user account, you should copy your files to the new account and start using the new account permanently.

 If the PIN does not work on any account, move on to the next fix.

## 5\. Tweak PIN Sign-In Settings in Group Policy Editor

 When the convenience PIN sign-in setting in the Group Policy Editor is disabled, the PIN will not work. Therefore, it's essential to ensure it's not causing the problem during sign-in.

 Some Windows versions, however, might not have this feature. If this applies to you as well, skip this step.

 Follow the below steps to adjust the settings in the Group Policy Editor:

1. Search for the **Run** app in the Windows search bar.
2. Type **gpedit.msc** and click on **OK**.
3. Navigate to **Administrative Templates > System > Logon**.
4. In the right-hand pane, locate and double-click on **Turn on convenience PIN sign-in setting**.
5. Check the **Enabled** checkbox, click **Apply**, and hit **OK**.

 If the setting is already enabled, continue to apply the remaining fixes.

 Group Policy Editor isn't available in the Windows Home edition by default. You can skip this fix if you're using the Home edition or try [alternative ways to get the Group Policy Editor](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

## 6\. Update or Downgrade Your OS

 According to [Microsoft support helpers](https://answers.microsoft.com/en-us/windows/forum/all/pin-not-working-on-windows-10/d444ebfb-d643-40b5-be62-1569454118d1), one of the possible causes of PIN not working on Windows may be recent updates. If you remember doing an update recently, you need to [roll the update back](https://www.makeuseof.com/tag/regret-update-windows-10-revert-version/).

 Conversely, if you haven't updated your computer for quite some time, maybe the problem stems from an outdated Windows OS. In that case, follow the below steps to update your computer:

1. Open the Windows Settings app.
2. Go to **Update & Security**.
3. Navigate to **Windows Update** in the left sidebar.
4. Click on **Check for updates** box.  
![Checking for Windows PC updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/9-Checking-for-Windows-PC-updates.jpg)

 Windows will automatically check for the latest updates and update itself if necessary. After your OS has been updated, try logging in again with your PIN if it works this time.

 If you're experiencing this issue on Windows 11, see our guide on [how to install Windows 11 updates](https://www.makeuseof.com/windows-11-install-updates/) to update your system. If you've started experiencing this issue after installing an update, follow our guide on [how to uninstall updates in Windows 11](https://www.makeuseof.com/windows-11-uninstall-updates/) and uninstall the most recent updates you installed.

 If the issue persists, run a malware scan to rule out the possibility of malware interference.

## 7\. Turn Off Your Antivirus and Run a Malware Scan

 Possible interference from antivirus may also result in your PIN being rejected. To prevent this from happening, temporarily turn off any third-party antivirus you're using. If turning off the third-party security suite fixes the problem, turn it off permanently.

 In addition, you can [temporarily disable Windows Defender](https://www.makeuseof.com/how-to-turn-off-windows-defender/) (now known as Microsoft Defender), the built-in security suite, to ensure that it's not the culprit. Remember to re-enable the security suite, as turning it off for too long can expose your device to malware.

 Aside from that, malware infections can also impair many system functions. Thus, it is imperative to rule out this possibility. You can easily do this by [running a Microsoft Defender offline scan](https://www.makeuseof.com/how-to-remove-malware-using-microsoft-defenders-offline-scan/). By scanning the system, you can ensure that no hidden malware is affecting its performance.

## 8\. Run an SFC Scan

 When you remove malware from your computer, make sure it hasn't corrupted any Windows files that might have caused the issue at hand.

 The easiest way to do this is to run an SFC scan. The scan automatically searches for corrupted files and replaces them with a cached copy. You can check out how to use the SFC tool in our guide on [how to repair corrupt Windows files with its built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

 If running the SFC scan does not fix the problem, you can [revert your system to an earlier restore point](https://www.makeuseof.com/use-system-restore-windows/) where the PIN was working. You can only do this if you've already created a restore point. Otherwise, it's impossible.

## PIN Still Isn’t Working on Windows?

 After you have tried all fixes listed above and the issue persists, consider restoring your computer to a previous point where the PIN was working fine. If that doesn't solve the problem either, it's best to factory reset your computer as a last resort.

 Likewise, not updating your operating system for long, being infected with malware, or corrupted system files can also prevent your login PIN from working. If you're having trouble logging in to your device using your Windows Hello PIN, give the following solutions a shot.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-brush-up-your-youtube-videos-with-color-correction/"><u>[New] 2024 Approved Brush Up Your Youtube Videos with Color Correction</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-deconstructing-the-legal-framework-of-youtube-and-cc-licenses/"><u>[Updated] Deconstructing the Legal Framework of Youtube & CC Licenses</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/educational-and-amusing-wildlife-footage-for-kids-free-downloads/"><u>Educational & Amusing Wildlife Footage for Kids - Free Downloads!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-apples-desk-to-windows-domain-windows-11-via-parallels/"><u>From Apple's Desk to Windows' Domain: Windows 11 via Parallels</u></a></li>
<li><a href="https://android-location.techidaily.com/how-to-fake-gps-on-android-without-mock-location-for-your-poco-m6-pro-5g-drfone-by-drfone-virtual/"><u>How to Fake GPS on Android without Mock Location For your Poco M6 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-directdraw-problems-on-modern-windows/"><u>How to Rectify DirectDraw Problems on Modern Windows</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-12-pro-max-to-other-iphone-13-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 12 Pro Max to other iPhone 13 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-oneplus-ace-2v-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from OnePlus Ace 2V to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-three-ways-to-sim-unlock-vivo-y27-5g-by-drfone-android/"><u>In 2024, Three Ways to Sim Unlock Vivo Y27 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-overcome-stuck-fn-keys-controlling-screen-brightness-in-windows-11/"><u>Methods to Overcome Stuck Fn Keys Controlling Screen Brightness in Windows 11</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-rotate-your-3gp-videos-without-spending-a-dime-top-5-free-tools-for-2024/"><u>New Rotate Your 3GP Videos Without Spending a Dime Top 5 Free Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalized-guide-to-nvidia-drivers-for-users/"><u>Personalized Guide to Nvidia Drivers for Users</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/proactive-planning-harnessing-the-power-of-slack-and-filmora-for-meetings/"><u>Proactive Planning Harnessing the Power of Slack & Filmora For Meetings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rebalancing-high-life-impact-on-windows-operations/"><u>Rebalancing High-Life Impact on Windows Operations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-windowss-spotify-connectivity-glitches-a-guide/"><u>Solving Windows's Spotify Connectivity Glitches: A Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stealthy-innovation-unveiled-asus-s15-reviewed-excellently/"><u>Stealthy Innovation Unveiled: Asus S15 Reviewed Excellently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-bypass-now-need-windows-password-warning/"><u>Steps to Bypass Now Need Windows Password Warning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-recover-winget-operations-on-windows-11/"><u>Swiftly Recover Winget Operations on Windows 11</u></a></li>
<li><a href="https://tech-haven.techidaily.com/troubleshooting-performance-issues-how-to-fix-low-fps-in-nier-gestalt-and-nier-replicant/"><u>Troubleshooting Performance Issues: How to Fix Low FPS in NieR: Gestalt and NieR: Replicant</u></a></li>
</ul></div>

