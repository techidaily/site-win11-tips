---
title: Tackling Multiple Users' MS Logins on PC
date: 2024-07-12T17:02:05.810Z
updated: 2024-07-13T17:02:05.810Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling Multiple Users' MS Logins on PC
excerpt: This Article Describes Tackling Multiple Users' MS Logins on PC
keywords: Multi-User Access Control,PC User Login Management,Managing Shared Computers,Secure MS Login Solutions,Preventing Unauthorized Logins,Optimizing Multiple Users' Access,Enhancing Security for Group PCs
thumbnail: https://thmb.techidaily.com/98a90a980daafb5d4122c6bec488811f000154f10382aff0b3452de9d0f47411.jpg
---

## Tackling Multiple Users' MS Logins on PC

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
<li><a href="https://techidaily.com/undelete-lost-pictures-from-infinix-smart-8-by-fonelab-android-recover-pictures/"><u>Undelete lost pictures from Infinix Smart 8.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-internal-error-in-windows-11-remote/"><u>Mastering the Art of Fixing Internal Error in Windows 11 Remote</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-screen-guide-to-windows-11-gpus/"><u>Optimize Your Screen: Guide to Windows 11 GPUs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-control-over-file-explorer-on-stable-windows-11/"><u>Regain Control Over File Explorer on Stable Windows 11</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-unveiling-tiktoks-visual-makeover-techniques-for-2024/"><u>[New] Unveiling TikTok's Visual Makeover Techniques for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-mspcm-interface-on-windows-11-easily/"><u>Navigating the MSPCM Interface on Windows 11 Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-windows-11s-file-order-preferences/"><u>Realigning Windows 11'S File Order Preferences</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-6-ways-to-transfer-contacts-from-asus-rog-phone-8-pro-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 6 Ways To Transfer Contacts From Asus ROG Phone 8 Pro to iPhone | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/how-can-i-get-more-stardust-in-pokemon-go-on-apple-iphone-6-drfone-by-drfone-virtual-ios/"><u>How can I get more stardust in pokemon go On Apple iPhone 6? | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-the-essential-musicians-guide-to-copyright-compliance-on-ig/"><u>[New] 2024 Approved  The Essential Musician's Guide to Copyright Compliance on IG</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-quickly-enable-or-disable-bing-chat-ai-in-windows-11-taskbar-search/"><u>How to Quickly Enable or Disable Bing Chat AI in Windows 11 Taskbar Search</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-control-over-windows-snipping-commands/"><u>Regaining Control Over Windows' Snipping Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-credential-store-lockups-on-pcs/"><u>Fix Credential Store Lockups on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insights-into-windows-patch-identification/"><u>Insights Into Window's Patch Identification</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-steam-connectivity-woes-in-w11/"><u>Navigating Through Steam Connectivity Woes in W11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-optimize-your-memory-perfecting-iphone-album-organization-and-icloud-backup/"><u>[New] Optimize Your Memory  Perfecting iPhone Album Organization and iCloud Backup</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-how-to-locate-horrific-noise-profiles-for-filmmaking-for-2024/"><u>New How to Locate Horrific Noise Profiles for Filmmaking for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-7-best-mac-video-viewing-tools-for-2024/"><u>Top 7 Best Mac Video Viewing Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/msix-extension-mastery-a-practical-guide-to-microsoft-store-add-ons/"><u>MSIX Extension Mastery: A Practical Guide to Microsoft Store Add-Ons</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-complete-guide-to-recording-live-tv-on-your-windows-pc/"><u>In 2024, Complete Guide to Recording Live TV on Your Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-alteration-of-nat-types-in-windows-operating-systems/"><u>Effective Alteration of NAT Types in Windows Operating Systems</u></a></li>
<li><a href="https://howto.techidaily.com/play-store-stuck-on-downloading-of-infinix-note-30i-7-ways-to-resolve-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Stuck on Downloading Of Infinix Note 30i? 7 Ways to Resolve | Dr.fone</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-the-best-of-both-worlds-8-lightweight-yet-powerful-video-editors/"><u>New 2024 Approved The Best of Both Worlds 8 Lightweight Yet Powerful Video Editors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-with-ease-to-windows-11s-security-management/"><u>Navigate with Ease to Windows 11’S Security Management</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-ultimate-list-youtube-alternatives-for-video-creators/"><u>2024 Approved  The Ultimate List  YouTube Alternatives for Video Creators</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-fixed-eclipsed-youtube-short-video/"><u>[New] 2024 Approved  Fixed  Eclipsed YouTube Short Video</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-make-unforgettable-moments-top-photo-and-video-collage-tools/"><u>Updated Make Unforgettable Moments Top Photo and Video Collage Tools</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-ideal-edits-at-your-fingertips-with-these-10-tools/"><u>In 2024, Ideal Edits at Your Fingertips with These 10 Tools</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-best-vivo-s18-pro-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>In 2024, Best Vivo S18 Pro Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-store-wont-let-you-sign-in-try-these-fixes/"><u>Microsoft Store Won’t Let You Sign In? Try These Fixes</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/reasons-why-pokemon-gps-does-not-work-on-oppo-find-n3-drfone-by-drfone-virtual-android/"><u>Reasons why Pokémon GPS does not Work On Oppo Find N3? | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-flash-dead-realme-narzo-60-5g-safely-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Flash Dead Realme Narzo 60 5G Safely | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-3-innovative-ways-for-windows-hardware-id-access/"><u>Exploring 3 Innovative Ways for Windows Hardware ID Access</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/virality-to-value-gauge-your-content-against-competing-craftsmen/"><u>From Virality to Value  Gauge Your Content Against Competing Craftsmen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-strategies-to-fix-windows-error-code-0x800704b3/"><u>Effective Strategies to Fix Windows' Error Code: 0X800704B3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-cleanse-your-computer-of-previous-security-audits/"><u>How to Cleanse Your Computer of Previous Security Audits</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-science-of-space-how-layout-affects-professional-effectiveness/"><u>[New] The Science of Space  How Layout Affects Professional Effectiveness</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-win1011-recycle-bin-repair-strategies/"><u>Mastering WIN10/11 Recycle Bin Repair Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-limited-access-install-troubleshooting-on-win-1110/"><u>Navigating Through Limited Access Install Troubleshooting on Win 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-for-loss-of-pin-access-in-windows-11-post-update-fallout/"><u>Fix for Loss of PIN Access in Windows 11 Post-Update Fallout</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-challenge-xfffffddd-print-error-in-xp/"><u>Overcoming the Challenge: XFFFFFDDD Print Error in XP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-persistence-of-user-defined-volume-mixer/"><u>Ensuring Persistence of User-Defined Volume Mixer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-win-10s-cc-troubleshooting/"><u>Essential Tips for Win 10'S CC Troubleshooting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-device-inactivity-in-new-os-sleep-mode/"><u>Overcoming Device Inactivity in New OS Sleep Mode</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-leave-a-life360-group-on-realme-gt-3-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How To Leave a Life360 Group On Realme GT 3 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-sketch-masters-on-ipados-top-8-artistic-apps-for-2024/"><u>[Updated] Sketch Masters on iPadOS  Top 8 Artistic Apps for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gearing-up-with-best-laptops-from-ifa-2023/"><u>Gearing Up with Best Laptops From IFA 2023</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-pioneering-path-of-vr-technology/"><u>In 2024, The Pioneering Path of VR Technology</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-steps-to-correct-windows-operating-system-office-errors/"><u>Immediate Steps to Correct Windows Operating System Office Errors</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-introducing-efficient-speech-to-text-utilization-in-powerpoint/"><u>2024 Approved  Introducing Efficient Speech-to-Text Utilization in PowerPoint</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstate-missing-dxgidll-streamline-your-win11/"><u>Reinstate Missing Dxgi.dll, Streamline Your Win11</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-android-plus-mac-how-to-archive-your-snap-videos/"><u>In 2024, Android + Mac  How to Archive Your Snap Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-advice-on-resolving-windows-error-code-0xc0000001/"><u>Expert Advice on Resolving Windows Error Code 0XC0000001</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-screensnap-2023-the-new-standard-in-recording-for-2024/"><u>[Updated] ScreenSnap 2023 – The New Standard in Recording for 2024</u></a></li>
</ul></div>
