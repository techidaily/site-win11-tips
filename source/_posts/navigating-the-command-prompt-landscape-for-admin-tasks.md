---
title: Navigating the Command Prompt Landscape for Admin Tasks
date: 2024-07-12T16:35:46.446Z
updated: 2024-07-13T16:35:46.446Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating the Command Prompt Landscape for Admin Tasks
excerpt: This Article Describes Navigating the Command Prompt Landscape for Admin Tasks
keywords: Admin Terminal Commands,PC Command Line Usage,Windows Console Navigation,System Administration CLI,PowerShell Execution Steps,Terminal Tips for Admins,Tasks in Cmd Prompt
thumbnail: https://thmb.techidaily.com/ffa6265ad1a6a848473605e7aedcfa3ec46ffbe39326ff49e8d4fafd11fa0e00.jpg
---

## Navigating the Command Prompt Landscape for Admin Tasks

 When managing user accounts on a Windows PC, it often makes sense to use the Settings app. After all, it provides a graphical user interface that simplifies the process. But for those who'd rather manage the accounts with fewer clicks, they can use the **net user** command in Command Prompt to manage user accounts on Windows.

 In this guide, we're going to show you how to use the net user command to perform various actions on user accounts on a Windows computer.

## 1\. List All User Accounts
![list all user accounts with net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/list-all-user-accounts-with-net-user.jpg)

 Before you start managing user accounts with **net user**, it helps to know all the user accounts on your computer. To list them all, [open Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/), enter the below command, and hit the **Enter** key to run it:

`net user`

 Keep the names you see in mind, as you will need them as you use the **net user** command.

## 2\. Show All the Information of a User Account
![user account details while using net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/user-account-details-while-using-net-user.jpg)

 You can also bring up all the important information about a user by simply typing the **net user** command followed by the name of the user's name. Here's the basic syntax:

`net user Username`

 Let's say there's a user named "Jack" on the computer. To bring up their account information, you'd enter the below command, replacing **Username** in the above command structure with **Jack**:

`net user Jack`

 Once you run the command, you'll be able to see, the user's full name, when their password expires, when they last logged in, whether they're an administrator, and more.

## 3\. Add and Delete a User Account

 To add a new user in Command Prompt, you need to use the **net user** command followed by the name of the new account, the desired password you wish to set, and the **/add** switch (this tells **net user** that you're adding a user). Here's the basic syntax of the command:

`net user Username Password /add`

 Keep in mind that all you'll be creating here is a local account, but you can always [switch a local account to a Microsoft account](https://www.makeuseof.com/windows-switch-local-account-to-microsoft-account/) later on. Here's an example of the command in action:

`net user Jill Pa$w0rd /add`

 After you run that command, you'll see that the new user, **Jill**, has been added to your computer. To delete an account, just replace the **/add** switch with **/delete** without specifying the password. Here's how:

`net user Jill /delete`

 Now net user will remove the account from the computer.

## 4\. Enable and Disable a User Account
![deactivating an account with net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/deactivating-an-account-with-net-user.jpg)

 If there's a user you wish to temporarily restrict so they can't access their account, you can simply disable it instead of deleting it. Here's the basic syntax of that action, making sure to use the **/active:no** switch at the end of the command to tell **net user** you're disabling it:

`net user Username /active:no`

 So, here's an example of what disabling an account would look like after replacing **Username** with the name of the actual user account:

`net user Jack /active:no`

 And if you want to enable a disabled account, you just have to change the **/active:no** switch to **/active:yes**.

## 5\. Enable and Disable a Domain User Account

 Sometimes, you might not want a user to access all the resources in a particular domain. The easier way to restrict them is to disable their account in that domain. You can do this by adding the **/domain** switch to the syntax discussed in the previous section.

 Here's the syntax for disabling an account on a particular domain using **net user**, making sure to replace **Username** with the name of the user you want to disable:

`net user Username /domain /active:no`

 If you want to enable an account on a domain, just use the **/active:yes** switch in the above command structure instead.

## 6\. Set User Account Login Times

 If you want to specify the times someone can log in, you can use the **/time** parameter to specify the account login times. You can use the basic syntax below:

`net user Username /time login_times`

 In the above command structure, replace **Username** with the user you want to limit the login times for, and **login\_times** with a time range in the format **D-D,00:00**. Here's an example of how you'd do this:

`net user Jack /time:M-F,09:00-17:00`

 As per the example above, that user can only log in from Monday to Friday between 9 a.m. and 5 p.m. If Jack tried to log in, he'd get a message saying **Your account has time restrictions that prevent you from signing in**.

 To remove the time restrictions, you'd use the below command:

`net user Jack /time:all`

 Now Jack can go back to logging in whenever he wants.

## 7\. Set User Account Expiry Date
![setting an account expiriation date with net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/setting-an-account-expiriation-date-with-net-user.jpg)

 By default, accounts are set to never expire, but you can change that if you have a user you want to be active for a specific period of time. You will need to use the **/expires** parameter while specifying the year, month, and expiration date. Here's the basic command structure:

`net user Username /expires:DD/MM/YYYY`

 An example of this in action would be:

`net user Jack /expires:27/07/2024`

 With the above command, Windows will disable the on the date you've set above.

## 8\. Change the Password of a User Account

 You can also use the **net user** command to [change the password of a user account in Command Prompt](https://www.makeuseof.com/tag/quick-tip-change-the-windows-user-password-via-command-line/). This will make it so that you can quickly change the password of any local account with a single command, instead of having to do it through the Settings app, which requires many clicks.

 The beauty of it is that you can also use it to change passwords for multiple accounts without leaving the Command Prompt window.

## 9\. Change the Password of a Domain User Account

 You can also change the password of a user on a domain by appending the **/domain** switch at the end of the command for changing a user account. The syntax for this is as follows:

`net user Username NewPassword /domain`

 Again this has to be a local domain user account for this to work. So, if you [changed the user account from a Microsoft account to a local account](https://www.makeuseof.com/how-to-switch-windows-from-microsoft-account-to-local-account/), you'll need to switch it back to use the command.

## 10\. Set a Password Policy for Users
![setting an account policy with net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/setting-account-policy-with-net-user.jpg)

 If you need a particular user to change the password during their next login, you can use the **net user** command along with the **/passwordchg:yes** parameter (by default, the parameter is **/passwordchg:no**). Here's the basic syntax:

`net user Username /passwordchg:yes`

 Here's an example of what that would look like in Command Prompt:

`net user Jack /passwordchg:yes`

 So, the next time Jack logs into the computer, he will get a prompt asking him to change his password before he can access his user account.

## 11\. Set a Home Directory for Users

 When creating a new user profile using **net user**, you can set the home directory, which is where Windows will store the user's personal files and settings. By default, Windows places the home directory of each user account in **This PC > Local Disk (C:) > Users**. To change this with **net user** during account creation, the basic syntax is as follows:

`net user Username Password /add /homedir:Path-to-directory`

 A real-world example of this would be:

`net user Jack Pa$w0rd /add /homedir:D:\Other Users\Jack`

 The above command will place the home directory of **Jack**, as it creates the account, in the **D:\\Other Users\\Jack** folder.

## Take Control of Your Computer's Users Accounts With the Net User Command

 Net user is a simple command to understand, allowing you to effectively manage your accounts from one location: Command Prompt. Of course, we haven't covered everything here, as there are too many parameters and switches to cover in a single guide.

 With that said, after you've understood how to perform the **net user** actions we've covered, you'll be on your way to managing accounts on Windows much quicker.

 In this guide, we're going to show you how to use the net user command to perform various actions on user accounts on a Windows computer.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/top-6-windows-to-dos-optimal-apps-compared/"><u>Top 6 Windows To-Dos: Optimal Apps Compared</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-error-code-0x800713f-windows-11s-mail-woes/"><u>Unraveling Error Code 0X800713F: Windows 11'S Mail Woes</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-adjust-macs-captured-screen-storage-place/"><u>[New] In 2024, Adjust Mac's Captured Screen Storage Place</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-create-unforgettable-slideshows-with-these-5-top-tools-for-2024/"><u>Updated Create Unforgettable Slideshows with These 5 Top Tools for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/top-10-airplay-apps-in-xiaomi-redmi-note-13-proplus-5g-for-streaming-drfone-by-drfone-android/"><u>Top 10 AirPlay Apps in Xiaomi Redmi Note 13 Pro+ 5G for Streaming | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-your-pubg-saved-data-in-windows-1110/"><u>Reviving Your PUBG Saved Data in Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secrets-to-always-seeing-your-sticky-notes-in-windows/"><u>Secrets to Always Seeing Your Sticky Notes in Windows</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-overcoming-obstacles-in-iphone-xs-facial-detection-system/"><u>2024 Approved  Overcoming Obstacles in iPhone X’s Facial Detection System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-addressing-windows-update-errors/"><u>Step-by-Step: Addressing Windows Update Errors</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/top-10-telegram-spy-tools-on-apple-iphone-6s-for-parents-drfone-by-drfone-virtual-ios/"><u>Top 10 Telegram Spy Tools On Apple iPhone 6s for Parents | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-windows-terminal-for-quake-environment/"><u>Accessing Windows Terminal for Quake Environment</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-change-oneplus-nord-n30-5g-lock-screen-password-by-drfone-android/"><u>How To Change OnePlus Nord N30 5G Lock Screen Password?</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-dispelling-digital-studio-misconceptions-what-daws-truly-are/"><u>2024 Approved Dispelling Digital Studio Misconceptions What DAWs Truly Are</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/detailed-guide-of-ispoofer-for-pogo-installation-on-zte-blade-a73-5g-drfone-by-drfone-virtual-android/"><u>Detailed guide of ispoofer for pogo installation On ZTE Blade A73 5G | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-nokia-c22-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Nokia C22 Bricked Devices | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-data-security-activating-controlled-folder-access/"><u>Achieve Data Security: Activating Controlled Folder Access</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-the-most-efficient-ways-to-manage-your-timeline/"><u>In 2024, The Most Efficient Ways to Manage Your Timeline</u></a></li>
<li><a href="https://win11-tips.techidaily.com/character-discovery-windows-11-pathway/"><u>Character Discovery: Windows 11 Pathway</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-full-guide-on-mirroring-your-zte-nubia-flip-5g-to-your-pcmac-drfone-by-drfone-android/"><u>In 2024, Full Guide on Mirroring Your ZTE Nubia Flip 5G to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-is-it-possible-to-quick-review-on-windows-heres-how/"><u>[Updated] Is It Possible to Quick Review on Windows? Here’s How</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-enhanced-functionality-with-ai-for-windows-11-users/"><u>Unveiling Enhanced Functionality with AI for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-taskbar-in-windows-11/"><u>Tailoring Your Taskbar in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-with-improved-windows-tiling/"><u>Boost Productivity with Improved Windows Tiling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-resolving-error-0xc00000f-in-windows-pcs/"><u>Understanding and Resolving Error 0Xc00000f in Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-w11-issues-with-csgo/"><u>Addressing W11 Issues with CS:GO</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/expert-guide-to-a-lasting-goodbye-deleting-tiktok-effectively-for-2024/"><u>Expert Guide to a Lasting Goodbye  Deleting TikTok Effectively for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-swiftly-show-and-hide-directories-on-windows-11-pcs/"><u>Tips for Swiftly Show & Hide Directories on Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-printer-connectivity-in-windows-os/"><u>Restoring Printer Connectivity in Windows OS</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-enhancing-film-quality-with-simplified-audio-layer-control-in-premiere-pro-2023/"><u>Updated In 2024, Enhancing Film Quality with Simplified Audio Layer Control in Premiere Pro 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-managing-your-network-proxy/"><u>Windows 11: Managing Your Network Proxy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sharpening-up-discord-response-time-on-windows-devices/"><u>Sharpening Up Discord Response Time on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-power-of-in-hand-typing-enable-steps-on-windows/"><u>Unlock the Power of In-Hand Typing: Enable Steps on Windows</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-the-roadmap-to-an-influential-instagram-profile-six-simple-steps-for-following-and-verified-recognition/"><u>[Updated] The Roadmap to an Influential Instagram Profile  Six Simple Steps for Following and Verified Recognition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-file-download-problems-in-windows/"><u>Strategies to Overcome File Download Problems in WIndows</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-futures-camera-giants-top-10-camcorder-picks-2024-edition/"><u>[New] Future's Camera Giants  Top 10 Camcorder Picks, 2024 Edition</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-action-camera-buying-for-newbies-the-updated-guide-23/"><u>In 2024, Action Camera Buying for Newbies - The Updated Guide '23</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-tutorial-using-netstat-in-windows-11/"><u>A Comprehensive Tutorial: Using Netstat in Windows 11</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-dive-deep-configuring-fb-video-for-full-screen-viewing/"><u>[Updated] 2024 Approved  Dive Deep  Configuring FB Video for Full-Screen Viewing</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-beat-o-vision-your-guide-to-the-years-most-shared-rap-tracks/"><u>[New] 2024 Approved  Beat-O-Vision  Your Guide to the Year's Most Shared Rap Tracks</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-the-ultimate-list-of-free-green-screen-apps-for-mobile-video-editing/"><u>New The Ultimate List of Free Green Screen Apps for Mobile Video Editing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trim-down-warmup-latency-top-tips-for-a-quicker-boot-up/"><u>Trim Down Warmup Latency – Top Tips for a Quicker Boot-Up</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sync-success-reestablishing-obs-studio-server-connection-in-win/"><u>Sync Success: Reestablishing OBS Studio Server Connection in Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/vivetool-blueprint-engaging-windows-companion/"><u>ViveTool Blueprint: Engaging Windows Companion</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-screenflow-unleashed-a-comprehensive-macos-review/"><u>[Updated] ScreenFlow Unleashed  A Comprehensive macOS Review</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-ultimate-tv-streaming-guide-international-and-regional-channels/"><u>[New] Ultimate TV Streaming Guide  International & Regional Channels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveil-the-secret-dark-mode-setting-in-win-11s-notepad/"><u>Unveil the Secret: Dark Mode Setting in Win 11'S Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlink-others-login-on-win-11/"><u>Unlink Others' Login on Win 11</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-exploring-imovies-default-cropping-behavior/"><u>[Updated] In 2024, Exploring iMovie's Default Cropping Behavior</u></a></li>
</ul></div>
