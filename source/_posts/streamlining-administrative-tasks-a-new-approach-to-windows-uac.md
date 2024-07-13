---
title: "Streamlining Administrative Tasks: A New Approach to Windows UAC"
date: 2024-07-12T17:09:18.248Z
updated: 2024-07-13T17:09:18.248Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Streamlining Administrative Tasks: A New Approach to Windows UAC"
excerpt: "This Article Describes Streamlining Administrative Tasks: A New Approach to Windows UAC"
keywords: Admin Optimization,UAC Simplification,UAC Redesign,Efficiency in Security,Enhanced Access Control,Secure Task Streamlining,Windows Permission Management
thumbnail: https://thmb.techidaily.com/e7c07b94a0d6b31286cb181ffa8593e2e10d0215534d64f40b8e2e1bab83a4ee.jpg
---

## Streamlining Administrative Tasks: A New Approach to Windows UAC

 If you’ve ever tried running a program on Windows as an administrator, you’ve probably come across a prompt asking you to either give or deny it permission to make high-level changes. That’s User Access Control (UAC) in action, and it adds an extra layer of security when a program or task is seeking elevated privileges. This gives you the chance to stop unwanted or malicious software from making changes on your PC.

 As an administrator, you can change how UAC behaves. In this guide, we’re going to show you how to do that using the Local Group Policy Editor and Registry Editor.

## What Behaviors Does UAC Have for Administrators?

 Before you go about changing the way UAC acts for administrators, it helps to know what behaviors you can choose and what they mean. We’re going to list them below, along with the definitions that are listed on [Microsoft Learn](https://learn.microsoft.com/en-us/windows/security/threat-protection/security-policy-settings/user-account-control-behavior-of-the-elevation-prompt-for-administrators-in-admin-approval-mode).

 Here’s what you can choose:

* **Elevate without prompting**: Assumes that the administrator will permit an operation that requires elevation, and more consent or credentials aren't required. This minimizes the protection that is provided by UAC.
* **Prompt for credentials on the secure desktop**: When an operation requires elevation of privilege, the user is prompted on the secure desktop to enter a privileged username and password. If the user enters valid credentials, the operation continues with the user's highest available privilege.
* **Prompt for consent on the secure desktop**: When an operation requires elevation of privilege, the user is prompted on the secure desktop to select **Permit** or **Deny**. If the user selects **Permit**, the operation continues with the user's highest available privilege.
* **Prompt for credentials**: An operation that requires elevation of privilege prompts the administrator to type the username and password. If the administrator enters valid credentials, the operation continues with the applicable privilege.
* **Prompt for consent**: An operation that requires elevation of privilege prompts the administrator to select **Permit** or **Deny**. If the administrator selects **Permit**, the operation continues with the administrator's highest available privilege.
* **Prompt for consent for non-Windows binaries**: This prompt for consent is the default. When an operation for a non-Microsoft application requires elevation of privilege, the user is prompted on the secure desktop to select **Permit** or **Deny**. If the user selects **Permit**, the operation continues with the user's highest available privilege.

 Now that you're familiar with the UAC behaviors for administrators, let’s see how to change them.

## Changing UAC Behavior for Administrators in the Local Group Policy Editor

 To change the UAC behavior for admins using the Local Group Policy Editor (LGPE), start by pressing **Win + R**, typing **gpedit.msc** in Windows Run, and hitting the **Enter** key to [open the LGPE on Windows](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

![Gpedit In Run Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Gpedit-In-Run-Menu.jpg)

 In the left panel, navigate to **Configuration > Windows Settings > Security Settings > Local Policies > Security Options**. In the right panel, double-click the **User Account Control: Behavior of the elevation prompt for administrators in Admin Approval Mode** policy to access its **Properties** window.

![the UAC behavior for admin policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/uac-behavior-admin-policy-local-group-policy-editor.jpg)

 Click on the dropdown and select the UAC behavior you want.

![Editing the UAC behavior for admin policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-uac-behavior-admin-policy-local-group-policy-editor.jpg)

 To apply and save the changes, click on **OK**.

## Changing UAC Behavior for Administrators in the Registry Editor

 To change the UAC behavior for administrators using the Registry Editor, start by pressing **Win + R**, typing **regedit** in Windows Run, and hitting the **Enter** key.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 In the UAC prompt, click **Yes** to [open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-local-security-policy/).

 Changing settings in the Registry Editor can impact the performance of your computer negatively if you make a mistake. To make sure you always have a way to revert the changes, we recommend learning [how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/).

 In the navigation panel on the left, head to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Policies > System**. In the right panel, double-click the **ConsentPromptBehaviorAdmin** value to modify it.

![The ConsentPromptBehaviorAdmin value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/consentpromptbehavior-value-registry-editor.jpg)

 Enter one of the following variables in the text box for **Value date**:

| Variable | UAC Behavior                                 |
| -------- | -------------------------------------------- |
| 0        | Elevate without prompting                    |
| 1        | Prompt for credentials on the secure desktop |
| 2        | Prompt for consent on the secure desktop     |
| 3        | Prompt for credentials                       |
| 4        | Prompt for consent                           |
| 5        | Prompt for consent for non-Windows binaries  |

 So, if you were to, for example, change it to **Prompt for credentials**, you’d enter **3** in the **Value data** text box.

![Editing the ConsentPromptBehaviorAdmin value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-consentpromptbehavior-value-registry-editor.jpg)

 Then, click **OK** to apply and save the changes.

## Control the UAC’s Behavior as an Administrator

 Now you can change the behavior of UAC for admins as you please, depending on your situation. Just be careful not to make your computer more vulnerable in the process, which can happen if you choose **Elevate without prompting**. Microsoft recommends using that option only when you’re in a highly secure environment where the administrator accounts are tightly controlled.

 In that case, you can even disable the UAC altogether if you'd like since you know there are other measures in place to protect your computer from unwanted or malicious programs.

 As an administrator, you can change how UAC behaves. In this guide, we’re going to show you how to do that using the Local Group Policy Editor and Registry Editor.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-open-the-ease-of-access-center-on-windows/"><u>5 Ways to Open the Ease of Access Center on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-window-updates-that-left-old-traits-behind/"><u>6 Window Updates That Left Old Traits Behind</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-chromebook-and-hp-efficient-webcam-recording-tips/"><u>[Updated] Chromebook & HP  Efficient Webcam Recording Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-startup-manipulating-boot-timeout-on-windows-11/"><u>Accelerate Startup: Manipulating Boot Timeout on Windows 11</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-broadcasting-fb-movies-on-whatsapp/"><u>[Updated] 2024 Approved  Broadcasting FB Movies on WhatsApp</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-adding-emulators-to-playnite-on-pc/"><u>A Step-by-Step Guide: Adding Emulators to Playnite on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719286286586-unmasking-windows-hidden-chronicle-view-clean-up/"><u>Unmasking Windows' Hidden Chronicle - View, Clean Up</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-absence-of-rockalldlldll-windows/"><u>Addressing Absence of Rockalldll.dll (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-onedrives-faulty-blob-tag-errors-in-windows/"><u>Addressing OneDrive's Faulty Blob Tag Errors in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/access-strongest-passwords-effortlessly-with-these-7-free-generators/"><u>Access Strongest Passwords Effortlessly With These 7 Free Generators</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-best-android-unlock-software-for-oneplus-12-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>The Best Android Unlock Software For OnePlus 12 Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-change-windows-11-administrator-name/"><u>A Comprehensive Guide to Change Windows 11 Administrator Name</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-alternatives-when-bitlocker-isnt-available-on-windows/"><u>5 Alternatives When Bitlocker Isn't Available on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719269092202-fixed-windows-shift-key-unreachable/"><u>Fixed: Windows Shift Key Unreachable</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/unlocking-instagrams-soundscape-feature/"><u>Unlocking Instagram’s Soundscape Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-insufficient-installation-privilege-issue-on-win-1011/"><u>Addressing Insufficient Installation Privilege Issue on Win 10/11</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-in-2024-the-5-highest-rated-audio-mixers-suited-to-mac-systems/"><u>Updated In 2024, The 5 Highest-Rated Audio Mixers Suited to Mac Systems</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/making-a-mark-with-google-slides-by-adding-youtube-videos-for-2024/"><u>Making a Mark with Google Slides by Adding YouTube Videos for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-mastering-the-art-of-speech-to-text-with-google-ai/"><u>[New] Mastering the Art of Speech-to-Text with Google AI</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-do-i-stop-someone-from-tracking-my-xiaomi-redmi-note-12t-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How Do I Stop Someone From Tracking My Xiaomi Redmi Note 12T Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719276038972-troubleshoot-silent-pc-audio-solutions-ready/"><u>Troubleshoot Silent PC Audio – Solutions Ready</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-15-pro-without-swiping-up-6-ways-by-drfone-ios/"><u>In 2024, How To Unlock Apple iPhone 15 Pro Without Swiping Up? 6 Ways</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-recollection-runway-your-easy-path-to-story-archives/"><u>[Updated] 2024 Approved  Recollection Runway  Your Easy Path to Story Archives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapting-notepad-display-from-light-to-dark-in-win-11-version/"><u>Adapting Notepad Display: From Light to Dark in Win 11 Version</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-pathways-to-revitalize-a-dying-windows-services-console/"><u>7 Pathways to Revitalize a Dying Windows Services Console</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719335028418-stop-early-window-11-edge-tabs-now/"><u>Stop Early Window 11 Edge Tabs Now</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-unlock-from-apple-iphone-15-how-to-fix-it-by-drfone-ios/"><u>Apple ID Unlock From Apple iPhone 15? How to Fix it?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719343275245-tackle-windows-geforce-failures-head-on-today/"><u>Tackle Windows GeForce Failures Head-On Today!</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-mobile-image-mastery-with-top-10-stickers-for-appleandroid-users/"><u>[New] Mobile Image Mastery with Top 10 Stickers for Apple/Android Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/2024s-best-windows-computers-for-enhanced-productivity/"><u>2024'S Best Windows Computers for Enhanced Productivity</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-pro-mac-and-pc-screen-capture-experts-for-2024/"><u>[Updated] Pro Mac & PC Screen Capture Experts for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-alternative-protection-strategies-for-missing-bitlocker-in-winoss/"><u>5 Alternative Protection Strategies for Missing Bitlocker in WinOSs</u></a></li>
<li><a href="https://games-able.techidaily.com/7-important-settings-to-customize-before-starting-a-new-fps-game/"><u>7 Important Settings to Customize Before Starting a New FPS Game</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-best-ways-on-how-to-unlockbypassswiperemove-samsung-galaxy-s23-fingerprint-lock-by-drfone-android/"><u>In 2024, Best Ways on How to Unlock/Bypass/Swipe/Remove Samsung Galaxy S23 Fingerprint Lock</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/maximize-youtube-exposure-in-156-characters-or-less-for-2024/"><u>Maximize YouTube Exposure in 156 Characters or Less for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-yuzu-emulation-windows-tips/"><u>Accelerating Yuzu Emulation: Windows Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-compelling-arguments-why-windows-11-eclipses-macos/"><u>6 Compelling Arguments Why Windows 11 Eclipses macOS</u></a></li>
<li><a href="https://some-techniques.techidaily.com/hasten-to-past-accessing-removed-reddit-threads-swiftly-for-2024/"><u>Hasten to Past  Accessing Removed Reddit Threads Swiftly for 2024</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-in-2024-top-tiktok-watermark-erasers-remove-logos-in-seconds/"><u>New In 2024, Top TikTok Watermark Erasers Remove Logos in Seconds</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-snicker-secrets-of-virtual-realms-making-funny-memes/"><u>2024 Approved  Snicker Secrets of Virtual Realms  Making Funny Memes</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-use-ispoofer-on-realme-12-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to use iSpoofer on Realme 12 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-playstation-services-hiccup-on-windows/"><u>Addressing PlayStation Services Hiccup on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensible-guide-to-managing-windows-key/"><u>A Comprehensible Guide to Managing Windows Key</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-improve-photo-scaling-in-windows-11/"><u>A Step-by-Step Guide to Improve Photo Scaling in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-nvidia-panel-errors-win1110-fixes/"><u>Addressing Nvidia Panel Errors: Win11/10 Fixes</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-in-2024-here-are-the-top-five-online-stop-motion-makers-and-a-brief-tutorial-about-how-to-make-a-stop-motion-video-from-photos-and-videos/"><u>New In 2024, Here Are the Top Five Online Stop Motion Makers and a Brief Tutorial About How to Make a Stop Motion Video From Photos and Videos</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-instant-freeze-capture-feature-guide/"><u>[Updated] Instant Freeze Capture Feature Guide</u></a></li>
</ul></div>
