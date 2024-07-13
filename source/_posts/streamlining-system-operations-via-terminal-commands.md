---
title: Streamlining System Operations via Terminal Commands
date: 2024-07-12T16:59:56.241Z
updated: 2024-07-13T16:59:56.241Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Streamlining System Operations via Terminal Commands
excerpt: This Article Describes Streamlining System Operations via Terminal Commands
keywords: OpTmE Streamline,TermComms Optimize,System Ops Efficiency,Terminal Command Strategy,OS Tuning Execution,Commands System Simplify,Operations Control Method
thumbnail: https://thmb.techidaily.com/0d1e6d469f4667c3d31e2ee564e25a93a1f4e0a1835558608501c466657ed85d.png
---

## Streamlining System Operations via Terminal Commands

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
<li><a href="https://facebook-video-files.techidaily.com/updated-2024-approved-unseen-navigators-of-fb-moments/"><u>[Updated] 2024 Approved  Unseen Navigators of FB Moments</u></a></li>
<li><a href="https://android-frp.techidaily.com/step-by-step-tutorial-how-to-bypass-sony-xperia-5-v-frp-by-drfone-android/"><u>Step-by-Step Tutorial How To Bypass Sony Xperia 5 V FRP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-absence-of-hypervisor-on-windows-sandbox/"><u>Addressing Absence of Hypervisor on Windows Sandbox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-timeout-issue-windows-1110-semaphore-error-0x80070079/"><u>Addressing Timeout Issue - Windows 11/10 Semaphore Error 0X80070079</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719358270699-reclaim-shift-control-with-easy-fixes/"><u>Reclaim Shift Control with Easy Fixes.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-efficiency-program-troubleshooting-tool-inclusion/"><u>Adding Efficiency: Program Troubleshooting Tool Inclusion</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-micro-snippet-analysis-at-a-glance/"><u>2024 Approved  Micro Snippet Analysis at a Glance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-stalled-downloads-with-qbittorrent-fixes/"><u>Accelerating Stalled Downloads with qBittorrent Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-closer-look-at-why-pcs-take-the-lead-over-macs-9/"><u>A Closer Look at Why PCs Take the Lead over Macs (#9)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-office-tasks-with-windows-command-shortcuts/"><u>Accelerate Office Tasks with Windows Command Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-crucial-windows-apps-making-mac-to-windows-swap-a-breeze/"><u>5 Crucial Windows Apps Making Mac to Windows Swap a Breeze</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-teleport-your-gps-location-on-poco-m6-pro-4g-drfone-by-drfone-virtual-android/"><u>How To Teleport Your GPS Location On Poco M6 Pro 4G? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-photos-files-from-itel-s23-by-fonelab-android-recover-photos/"><u>How To  Restore Missing Photos Files from Itel S23.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719332049172-swiftly-addressing-windows-faults-with-easy-fixes/"><u>Swiftly Addressing Windows Faults with Easy Fixes!</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-5-methods-to-make-a-fake-facetime-call-video/"><u>Updated 5 Methods to Make a Fake Facetime Call Video</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-apex-of-hd-technology-leading-recorder-brands-decoded/"><u>[Updated] 2024 Approved  Apex of HD Technology  Leading Recorder Brands Decoded</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-remedies-for-vmware-stop-at-boot-on-windows-11/"><u>8 Remedies for VMware Stop at Boot on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-windows-11-privileges-and-permissions-panel/"><u>Activating Windows 11 Privileges and Permissions Panel</u></a></li>
<li><a href="https://extra-tips.techidaily.com/integrate-and-play-srt-files-on-windowsmacos/"><u>Integrate and Play SRT Files on Windows/macOS</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-enhance-your-content-creating-engaging-loop-videos-for-ig/"><u>[Updated] Enhance Your Content  Creating Engaging Loop Videos for IG</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-thumbnail-size-mastery-for-higher-traffic-videos/"><u>2024 Approved  Thumbnail Size Mastery for Higher Traffic Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719320045015-clean-and-tailor-your-w11-desktop-now/"><u>Clean & Tailor Your W11 Desktop, Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-solutions-for-streamlining-windows-display-issues/"><u>5 Solutions for Streamlining Windows Display Issues</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-mastering-the-art-of-backward-movies-on-snapchat/"><u>[Updated] Mastering the Art of Backward Movies on Snapchat</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-prolific-photography-and-video-app-selection-iphone-vs-android/"><u>In 2024, Prolific Photography & Video App Selection  IPhone vs Android</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-command-attention-elevating-your-page-to-the-social-summit/"><u>[Updated] 2024 Approved  Command Attention  Elevating Your Page to the Social Summit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-cluttered-symbol-groups-on-windows-shell/"><u>Addressing Cluttered Symbol Groups on Windows Shell</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-glitch-nvidias-x0001-on-windows-w11/"><u>Addressing Glitch: Nvidia's X0001 on Windows W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719338143984-revitalizing-your-chrome-browser-on-the-latest-os-win11/"><u>Revitalizing Your Chrome Browser on the Latest OS (Win11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-restore-missing-windows-time-service/"><u>6 Ways to Restore Missing Windows Time Service</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-screen-savvy-secure-your-captures-chromebooks-top-4-techniques/"><u>In 2024, Screen Savvy  Secure Your Captures - Chromebook's Top 4 Techniques</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-design-gif-for-sharing/"><u>[Updated] 2024 Approved  Design Gif for Sharing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719381461685-unlock-hidden-features-in-windows-snipping-tool-for-flawless-screen-shots/"><u>Unlock Hidden Features in Windows Snipping Tool for Flawless Screen Shots</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-fix-optional-features-not-installing-on-windows-10-and-11/"><u>7 Ways to Fix Optional Features Not Installing on Windows 10 & 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-harnessing-external-light-for-cozy-interior-spaces/"><u>[Updated] Harnessing External Light for Cozy Interior Spaces</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-seamless-full-screen-display-overcoming-windows-overscan/"><u>Achieve Seamless Full-Screen Display: Overcoming Windows Overscan</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-streamlined-guide-to-resolving-roblox-error-code-262/"><u>A Streamlined Guide to Resolving Roblox Error Code 262</u></a></li>
<li><a href="https://win11-tips.techidaily.com/20-tactics-for-disabling-windows-11/"><u>20 Tactics for Disabling Windows 11</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/find-out-what-ray-tracing-is-in-after-effects-how-it-works-and-learn-about-ray-traced-3d-settings-with-simple-instructions-for-2024/"><u>Find Out What Ray Tracing Is in After Effects, How It Works, and Learn About Ray-Traced 3D Settings with Simple Instructions for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-video-editing-software-face-off-sony-vegas-vs-adobe-premiere-pro-2023-edition/"><u>New In 2024, Video Editing Software Face-Off Sony Vegas vs Adobe Premiere Pro 2023 Edition</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-airplane-mode-turn-off-gps-location-on-motorola-moto-e13-drfone-by-drfone-virtual-android/"><u>Does Airplane Mode Turn off GPS Location On Motorola Moto E13? | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-enhance-youtube-livestreams-webcam-selection-mastery/"><u>[Updated] In 2024, Enhance YouTube Livestreams  Webcam Selection Mastery</u></a></li>
<li><a href="https://fix-guide.techidaily.com/samsung-galaxy-a23-5g-camera-not-working-unexpected-error-fix-it-now-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Samsung Galaxy A23 5G Camera Not Working Unexpected Error? Fix It Now | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-in-2024-breakthrough-personalities-on-tiktok-a-guide-for-motivation/"><u>[New] In 2024, Breakthrough Personalities on TikTok  A Guide for Motivation</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-perfecting-your-dialogue-a-google-meet-strategy-for-2024/"><u>[New] Perfecting Your Dialogue  A Google Meet Strategy for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-android-apps-that-youd-actually-want-to-install-on-windows-11/"><u>6 Android Apps That You’d Actually Want to Install on Windows 11</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-bridging-platform-gaps-youtube-shorts-to-mp4-transformation/"><u>2024 Approved  Bridging Platform Gaps  YouTube Shorts to MP4 Transformation</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-inside-a-virtual-reality-device-a-basic-overview/"><u>[Updated] Inside a Virtual Reality Device  A Basic Overview</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-practical-solutions-for-gpeditmsc-not-found-crisis/"><u>3 Practical Solutions for Gpedit.msc Not Found Crisis</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-exploring-the-most-reliable-free-srt-translation-services-for-2024/"><u>[New] Exploring the Most Reliable Free SRT Translation Services for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-guide-to-optimal-audio-changer-tools-for-vtubers/"><u>[New] Guide to Optimal Audio Changer Tools for VTubers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-absence-of-visuals-in-webcams/"><u>Addressing Absence of Visuals in Webcams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-fix-13-solutions-for-windows-system-repair/"><u>A Quick Fix: 13 Solutions for Windows System Repair</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719363856500-unfreeze-reset-and-restore-shift-key/"><u>Unfreeze, Reset, and Restore Shift Key</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-error-x80049dd3-for-smooth-typing-on-windows-11/"><u>Addressing Error X80049DD3 for Smooth Typing on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-your-pcs-problems-4-top-pct-strategies/"><u>Ace Your PC's Problems: 4 Top PCT Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-using-microsofts-bluetooth-app/"><u>A Step-by-Step Guide to Using Microsoft's Bluetooth App</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/network-locked-sim-card-inserted-on-your-vivo-t2x-5g-phone-unlock-it-now-by-drfone-android/"><u>Network Locked SIM Card Inserted On Your Vivo T2x 5G Phone? Unlock It Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-windows-index-view-options/"><u>Accessing Windows Index View Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-look-at-addressing-error-code-262-on-roblox/"><u>A Comprehensive Look at Addressing Error Code 262 on Roblox</u></a></li>
</ul></div>
