---
title: Addressing Dual Users' MS Error on Windows OS
date: 2024-08-16T02:08:53.294Z
updated: 2024-08-17T02:08:53.294Z
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
## 1\. Remove the Device from Your Microsoft Account

 When you log in to a Windows device with your Microsoft account, the two begin communicating with one another. The device adds your account to its list of recognized users, while your account also adds the device to its list of connected devices.

 However, there may be instances when your account stays linked to a device even after you've removed it. This could be a possible reason why you are encountering the "another user on this device uses this Microsoft account" error.

![Removing a device from Microsoft accounts.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/microsoft-account-devices.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->

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
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
5. Right-click the account and select **Delete**.

 Note that this time you'll only see the Microsoft accounts on the device, not the local accounts. If these do not resolve the issue, it is likely that the problem extends beyond this specific account.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
## 4\. Change the Local Security Policy Settings

 Ever since Windows 10, Microsoft has been pushing users to sign in with their Microsoft accounts rather than local Windows accounts.

 Although you can now easily [create a local account in Windows](https://www.makeuseof.com/windows-11-create-local-user-account/), security policies regarding the accounts on your computer might be causing the "another user on this device uses this Microsoft account" error.

![Local security policies in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-security-policy.jpg)
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-enhance-visibility-a-comprehensive-guide-to-video-tagging/"><u>[New] In 2024, Enhance Visibility  A Comprehensive Guide to Video Tagging</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-the-essential-guide-instagram-optimization-through-final-cut-pro-x/"><u>[New] The Essential Guide  Instagram Optimization Through Final Cut Pro X</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-unleashing-the-potential-of-iphone-photos-through-motion-blur/"><u>[New] Unleashing the Potential of iPhone Photos Through Motion Blur</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-mastering-color-grading-with-gopro-studio/"><u>2024 Approved  Mastering Color Grading with GoPro Studio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-virtual-machine-security-with-vboxs-secure-boot-toggle/"><u>Boost Virtual Machine Security with VBox's Secure Boot Toggle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-privilege-needed-blue-screen-windows-fix-guide/"><u>Bypassing 'Privilege Needed' Blue Screen: Windows Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719381834367-cep-library-integration/"><u>CEP Library Integration:</u></a></li>
<li><a href="https://location-social.techidaily.com/change-location-on-yik-yak-for-your-xiaomi-redmi-note-12-pro-4g-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>Change Location on Yik Yak For your Xiaomi Redmi Note 12 Pro 4G to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-your-windows-11-experience-with-nircmd-tips/"><u>Command Your Windows 11 Experience with NirCmd Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-not-empty-assertion-a-practical-guide-to-x80070091-fixes/"><u>Disabling 'Not Empty' Assertion: A Practical Guide to X80070091 Fixes</u></a></li>
<li><a href="https://extra-information.techidaily.com/engaging-podcast-openers-captivating-intro-lines/"><u>Engaging Podcast Openers  Captivating Intro Lines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-to-rectify-cant-add-your-folder-now-in-onedrive/"><u>Essential Steps to Rectify 'Can't Add Your Folder Now' In OneDrive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719218779653-expert-tips-reinstating-functionality-of-wwinplusp-in-os/"><u>Expert Tips: Reinstating Functionality of WWin+P in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-disparities-in-cloud-and-offline-windows-updates/"><u>Exploring Disparities in Cloud and Offline Windows Updates</u></a></li>
<li><a href="https://howto.techidaily.com/fix-app-not-available-in-your-country-play-store-problem-on-oneplus-11-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix App Not Available in Your Country Play Store Problem on OnePlus 11 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-keygen-malware-on-windows-recognition-and-eradication-steps/"><u>Identifying Keygen Malware on Windows: Recognition and Eradication Steps</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/in-2024-a-tweet-to-snap-showcase-video-posting-techniques/"><u>In 2024, A Tweet-to-Snap Showcase  Video Posting Techniques</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-vivo-x-fold-2-to-mac-drfone-by-drfone-android/"><u>In 2024, How to Mirror Vivo X Fold 2 to Mac? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-phone-number-from-your-apple-id-from-your-iphone-15-plus-by-drfone-ios/"><u>In 2024, How To Remove Phone Number From Your Apple ID from Your iPhone 15 Plus?</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-merge-mpeg-videos-without-cost-top-options/"><u>In 2024, Merge MPEG Videos Without Cost Top Options</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-top-10-best-spy-watches-for-your-apple-iphone-15-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, Top 10 Best Spy Watches For your Apple iPhone 15 Pro Max | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrate-compatibility-troubleshoot-in-windows-clippy/"><u>Integrate Compatibility Troubleshoot in Windows Clippy</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/iphone-8-backup-password-never-set-but-still-asking-heres-the-fix-by-drfone-ios/"><u>iPhone 8 Backup Password Never Set But Still Asking? Heres the Fix</u></a></li>
<li><a href="https://win-forum.techidaily.com/master-the-trick-to-always-launch-windows-11-programs-as-an-administrator/"><u>Master the Trick to Always Launch Windows 11 Programs as an Administrator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-pc-storage-identifying-excess-disk-usage-in-windows/"><u>Maximizing PC Storage: Identifying Excess Disk Usage in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/msdia80dll-what-is-it-and-should-you-keep-it/"><u>msdia80.dll What Is It And Should You Keep It?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/navigating-around-common-blunders-when-using-advanced-generative-ais/"><u>Navigating Around Common Blunders When Using Advanced Generative AIs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-nvidia-connect-error-in-windows-oses/"><u>Overcoming NVIDIA Connect Error in Windows OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-win11s-security-measures-through-rufus-mastery/"><u>Overcoming Win11's Security Measures Through Rufus Mastery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-unreachable-network-paths/"><u>Overcoming Windows' Unreachable Network Paths</u></a></li>
<li><a href="https://audio-editing.techidaily.com/proven-leaders-in-speech-to-text-the-best-6-automatic-transcription-apps-for-2024/"><u>Proven Leaders in Speech to Text The Best 6 Automatic Transcription Apps for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/say-goodbye-to-old-files-enabling-the-autodelete-option-on-windows-11/"><u>Say Goodbye to Old Files: Enabling the Autodelete Option on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-integration-wirelessly-link-dualshock-3-and-win/"><u>Seamless Integration: Wirelessly Link DualShock 3 & Win</u></a></li>
<li><a href="https://os-tips.techidaily.com/solving-flash-drive-issues-effective-techniques-for-device-repair-and-data-retrieval/"><u>Solving Flash Drive Issues: Effective Techniques for Device Repair and Data Retrieval</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stay-connected-disable-usb-sleep-on-windows-11-pc/"><u>Stay Connected: Disable USB Sleep on Windows 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-error-0x00000709/"><u>Steps to Rectify Error 0X00000709</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-address-unsuccessful-onedrive-procedures/"><u>Strategies to Address Unsuccessful OneDrive Procedures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-5-best-torrent-clients-for-windows/"><u>The 5 Best Torrent Clients for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/thriving-without-11-upgrade-boost-your-pc-health/"><u>Thriving Without 11 Upgrade: Boost Your PC Health</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turning-spoken-words-into-written-phrases-a-guide-for-windows-users/"><u>Turning Spoken Words Into Written Phrases: A Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-full-potential-of-the-windows-key/"><u>Unlocking Full Potential of the Windows Key</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-activate-educational-themes/"><u>Win 11: Activate Educational Themes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-troubleshooting-for-elusive-temp-files/"><u>Windows Troubleshooting for Elusive Temp Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-customization-increasing-icon-dimensions-in-w11/"><u>Winning at Customization: Increasing Icon Dimensions in W11</u></a></li>
</ul></div>
