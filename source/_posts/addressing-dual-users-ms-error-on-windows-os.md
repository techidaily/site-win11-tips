---
title: Addressing Dual Users' MS Error on Windows OS
date: 2024-07-12T16:57:04.169Z
updated: 2024-07-13T16:57:04.169Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Dual Users' MS Error on Windows OS
excerpt: This Article Describes Addressing Dual Users' MS Error on Windows OS
keywords: MS_Windows_Error_Dual_Users,Windows_MS_Error_Solution,DualUser_MS_OS_Issues,Overcome_Windows_MS_Errors,Fixing_Dual_Windows_MS,Eradicating_Dual_OS_Errors,Resolve_Users_Error_Windows
thumbnail: https://thmb.techidaily.com/b357c4b8f72776975451a46d642e42d569af6d435c0d587f7372c46c2b7924bd.jpg
---

## Addressing Dual Users' MS Error on Windows OS

 So you're trying to sign in to your Windows device with a Microsoft account, but it throws an error that reads, "another user on this device uses this Microsoft account." You're certain that the account isn't signed in to the device, so why is Windows showing an error?

 Although this error serves as a security feature to keep your device safe, it can sometimes overdo it and lock you out. Fortunately, there are plenty of solutions for this error. Let's start by understanding what causes the error and then explore the possible solutions.

## What Is the "Another User on This Device Uses This Microsoft Account" Error?

![Windows displaying an error when adding account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-already-signedin.jpg)

 The "another user on this device uses this Microsoft account" error is a message that appears when you are trying to sign in to a Microsoft account on a device that already has a user signed in with the same account. This can happen if multiple users share a computer or if you are trying to access your account from a different device.

 The error message is a security measure to prevent unauthorized access to your account. In most scenarios, this error pops up if you've previously signed in with your account on that device, then deleted your account. If your account wasn't completely wiped off the device, you'll get this error message when you try to log in with it again.

 Another variation of this error reads "account already has been added to this PC." Fortunately, the solutions for both these errors are the same. Let's explore these solutions in more detail.

## 1\. Remove the Device from Your Microsoft Account

 When you log in to a Windows device with your Microsoft account, the two begin communicating with one another. The device adds your account to its list of recognized users, while your account also adds the device to its list of connected devices.

 However, there may be instances when your account stays linked to a device even after you've removed it. This could be a possible reason why you are encountering the "another user on this device uses this Microsoft account" error.

![Removing a device from Microsoft accounts.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/microsoft-account-devices.jpg)

 Thus, the first solution you can try is to remove the device from your Microsoft account. Here's how you can do it:

1. Go to the [Microsoft account website](https://account.microsoft.com) and sign in with your account credentials.
2. Go to the **Devices** tab and select the device you want to sign in on.
3. Click on the **Remove** hyperlink to remove the device from your Microsoft account.
4. Check **I'm ready to remove this device** and then click **Remove**.

 Restart your device and try signing in to your Microsoft account again. If this doesn't fix the error, you'll need to get your hands slightly dirty.

 The other solutions for this error require you to have access to an administrator account on the Windows device. If you don't have access to an administrator account, you'll have to ask the device owner to apply these solutions.

## 2\. Delete the Account From the Local Users and Groups Settings

 As the name implies, the Local Users and Groups Settings let you manage your computer's users and groups. You can change the permissions and memberships of each user, and in this case, you can use it to delete the excess user.

![Windows local users and groups settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-local-users.jpg)

 There are several [ways to access Windows' Local Users and Groups settings](https://www.makeuseof.com/windows-open-local-users-and-groups/). Once it's open, in the Local Users and Groups window, navigate to **Users**. Find the user account that's causing the error, right-click on it, then select **Delete**.

 Restart your device and try signing in to your Microsoft account again.

## 3\. Delete the Account Using the Registry Editor

 To ensure that the Microsoft account leaves no trails behind, you can clean up the remnants using the [Windows Registry Editor](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/). However, if the previous solution worked properly for you, you won't find the account in Registry Editor.

 Here's how you can delete the account with Registry Editor:

1. Open the Start menu and search for **Registry Editor**.
2. Open **Registry Editor**.
3. On the left-side pane, navigate to **HKEY\_USERS > .DEFAULT > Software > Microsoft > IdentityCRL > StoredIdentities**.
4. Once you expand **StoredIdentities**, you'll see a list of signed-in Microsoft accounts.  
![Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windwos-registery-user.jpg)
5. Right-click the account and select **Delete**.

 Note that this time you'll only see the Microsoft accounts on the device, not the local accounts. If these do not resolve the issue, it is likely that the problem extends beyond this specific account.

## 4\. Change the Local Security Policy Settings

 Ever since Windows 10, Microsoft has been pushing users to sign in with their Microsoft accounts rather than local Windows accounts.

 Although you can now easily [create a local account in Windows](https://www.makeuseof.com/windows-11-create-local-user-account/), security policies regarding the accounts on your computer might be causing the "another user on this device uses this Microsoft account" error.

![Local security policies in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-security-policy.jpg)

 You can change the local security policy on your device so that it doesn't block Microsoft accounts from logging in. You can do this through the Local Security Policies settings in Windows. Here's how:

1. Open the Local Security Policy window (see [how to open the Local Security Policy in Windows](https://www.makeuseof.com/windows-11-local-security-policy/) if you need help).
2. In the Local Security Policy window, navigate to **Security Settings** \> **Local Policies** \> **Security Options**.
3. Find the **Accounts: Block Microsoft accounts** policy and double-click on it.
4. From the drop-down list, select **This policy is disabled**.
5. Click on **Apply** and **OK** to save the changes.

 Restart your device and try signing in to your Microsoft account. If the error still persists, it might be time to outsource your solutions and [contact Microsoft support](https://www.makeuseof.com/contact-microsoft-support/) to have them help you out.

## Fix the "Another User on This Device Uses This Microsoft Account" Error and Get Back to Work

 This error becomes frustrating when it persists even after you've long deleted the account from that device. Hopefully, the solutions mentioned here will help you thoroughly sever the tie between your account and the device so you can sign in again.

 If all the measures here fail, you can contact Microsoft support and ask them for help. If that too fails, then there's no better fixer than a fresh installation of Windows.

 Although this error serves as a security feature to keep your device safe, it can sometimes overdo it and lock you out. Fortunately, there are plenty of solutions for this error. Let's start by understanding what causes the error and then explore the possible solutions.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-card-on-nubia-z50-ultra-online-without-jailbreak-by-drfone-android/"><u>In 2024, How to Unlock SIM Card on Nubia Z50 Ultra online without jailbreak</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-depths-of-diablos-first-adventure/"><u>Navigating the Depths of Diablo's First Adventure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-your-lost-dxgidll-with-these-win11-hacks/"><u>Restore Your Lost Dxgi.dll with These Win11 Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unpacking-the-delay-in-windows-11-adoption/"><u>Unpacking the Delay in Windows 11 Adoption</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/quick-fix-getting-snapchat-installed-on-mac-for-2024/"><u>Quick Fix  Getting Snapchat Installed on Mac for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/frostfangs-frequency-prime-online-locations-for-tts-files-for-2024/"><u>Frostfang's Frequency  Prime Online Locations for TTS Files for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/income-streams-from-windows-11-an-examination/"><u>Income Streams From Windows 11: An Examination</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-spot-and-dismantle-unused-windows-folders-easily/"><u>How to Spot & Dismantle Unused Windows Folders Easily</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/in-2024-top-explainer-video-tools-a-comprehensive-review/"><u>In 2024, Top Explainer Video Tools A Comprehensive Review</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-boosting-your-fb-pages-advanced-ranking-strategies/"><u>[Updated] Boosting Your FB Pages  Advanced Ranking Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrading-widely-used-directx-classics-through-dxvk/"><u>Upgrading Widely-Used DirectX Classics Through DXVK</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-the-variance-in-procedures-for-local-and-remote-windows-reinstallations/"><u>Analyzing the Variance in Procedures for Local and Remote Windows Reinstallations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-mouse-controls-in-win11-effortlessly/"><u>Navigating Mouse Controls in Win11 Effortlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-disabling-xbox-game-pass-error/"><u>Mastering the Art of Disabling Xbox Game Pass Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-initiate-sfc-process-in-windows-1087/"><u>Steps to Initiate SFC Process in Windows 10/8/7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/incorporating-external-disk-into-explorer-nav-pane/"><u>Incorporating External Disk Into Explorer Nav Pane</u></a></li>
<li><a href="https://extra-information.techidaily.com/cant-see-cursor-only-sony-a6400-glitch/"><u>Can't See, Cursor Only - Sony A6400 Glitch</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-what-is-ai-marketing/"><u>Updated What Is AI Marketing?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-door-on-stuck-wow-61-patches/"><u>Unlocking the Door on Stuck WoW 6.1 Patches</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-captivating-comedy-crafted-step-by-step-meme-tutorial/"><u>2024 Approved  Captivating Comedy Crafted  Step-by-Step Meme Tutorial</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-browsing-bygone-tales-in-the-facebook-universe-with-devices/"><u>[New] 2024 Approved  Browsing Bygone Tales in the Facebook Universe with Devices</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-leading-the-charge-in-sustainable-filmmaking/"><u>[New] 2024 Approved  Leading the Charge in Sustainable Filmmaking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sharpen-windows-safety-edge-context-menu-firewall-customization-guide/"><u>Sharpen Windows Safety Edge: Context Menu Firewall Customization Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-csgo-launch-failures-on-w11/"><u>Troubleshooting CS:GO Launch Failures on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-11-reactivating-deactivated-voice-command/"><u>Addressing Windows 11: Reactivating Deactivated Voice Command</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-windows-11-visuality-with-app-sizing/"><u>Boosting Windows 11 Visuality with App Sizing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-file-denial-in-steam-for-windows-11-users/"><u>Tackling File Denial in Steam for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoidance-of-error-0x80070570-saving-your-damaged-files-in-windows-11/"><u>Avoidance of Error 0X80070570: Saving Your Damaged Files in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/power-up-your-device-instantly-mastering-win-11s-double-clicked-apk-method/"><u>Power Up Your Device Instantly: Mastering Win 11'S Double-Clicked APK Method</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-resetting-windows-settings-on-reboot/"><u>Steps for Resetting Windows Settings on Reboot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/surreptitious-shutdown-strategy-for-windows-11/"><u>Surreptitious Shutdown Strategy for Windows 11</u></a></li>
<li><a href="https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-infinix-smart-8-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix the Error of Unfortunately the Process.com.android.phone Has Stopped on Infinix Smart 8 Pro | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-iphone-6s-with-an-apple-watch-and-what-to-do-if-it-doesnt-work-by-drfone-ios/"><u>How to Unlock iPhone 6s With an Apple Watch & What to Do if It Doesnt Work</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-the-dxgidll-file-missing-in-windows-11-heres-how-to-fix-it/"><u>Is the Dxgi.dll File Missing in Windows 11? Here's How to Fix It</u></a></li>
<li><a href="https://youtube-data.techidaily.com/mages-cozier-cinematics-best-bgs-selection-for-2024/"><u>Icy Images, Cozier Cinematics  Best Bgs Selection for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/put-a-halt-on-application-start-tracking-in-windows/"><u>Put a Halt on Application Start-Tracking in Windows</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-from-raw-footage-to-youtube-perfection-premiere-pro-techniques/"><u>[New] 2024 Approved  From Raw Footage to YouTube Perfection - Premiere Pro Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-terminal-configuration-basics/"><u>Mastering Windows Terminal Configuration Basics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-window-11-screens-a-comprehensive-wallpaper-plan/"><u>Tailoring Window 11 Screens: A Comprehensive Wallpaper Plan</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-window-into-evolution-noteworthy-windows-11-file-enhancements/"><u>A Window Into Evolution: Noteworthy Windows 11 File Enhancements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reactivate-a-nonfunctional-nvidia-cp-on-windows-11/"><u>How to Reactivate a Nonfunctional Nvidia CP on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-hidden-pathways-open-directory-games-in-windows/"><u>The Hidden Pathways: Open Directory Games in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-the-hurdles-of-xbox-game-pass-error-code-0-essential-tips-for-windows-11-users/"><u>Avoiding the Hurdles of Xbox Game Pass Error Code 0: Essential Tips for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovate-your-experience-avoiding-common-pitfalls-in-windows-11/"><u>Innovate Your Experience: Avoiding Common Pitfalls in Windows 11</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-best-route-generator-apps-you-should-try-on-vivo-y100i-power-5g-drfone-by-drfone-virtual-android/"><u>5 Best Route Generator Apps You Should Try On Vivo Y100i Power 5G | Dr.fone</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/2024-approved-top-10-windowsmaclinux-friendly-audio-editors-that-match-audacitys-capabilities/"><u>2024 Approved Top 10 Windows/Mac/Linux-Friendly Audio Editors That Match Audacitys Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speed-spectrum-mastering-windows-network-adapter-assessment-methods/"><u>Speed Spectrum: Mastering Windows' Network Adapter Assessment Methods</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-finding-those-who-fled-my-insta-friends/"><u>[Updated] In 2024, Finding Those Who Fled  My Insta Friends</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-page-lockout-in-windows-systems/"><u>Overcoming Page Lockout in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-routes-to-windows-control-panel-entry/"><u>Unveiling the Routes to Windows Control Panel Entry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-mute-microphone-issue-during-video-recordings/"><u>Tackling Mute Microphone Issue During Video Recordings</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-top-strategies-for-capturing-discords-real-time-broadcasts-for-2024/"><u>[Updated] Top Strategies for Capturing Discord's Real-Time Broadcasts for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-cutting-edge-clarity-optimal-4k-panels-for-video-production/"><u>[New] 2024 Approved  Cutting-Edge Clarity  Optimal 4K Panels for Video Production</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-and-fixing-the-msvcr110dll-gap/"><u>Uncovering & Fixing the Msvcr110.dll Gap</u></a></li>
</ul></div>
