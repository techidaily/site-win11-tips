---
title: Techniques to Switch Off Microsoft's Assistant
date: 2024-07-12T16:49:39.203Z
updated: 2024-07-13T16:49:39.203Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Techniques to Switch Off Microsoft's Assistant
excerpt: This Article Describes Techniques to Switch Off Microsoft's Assistant
keywords: Disabling Cortana,Turning Off AI,Shutting Down MS Assist,Stop Microsoft Assistant,Silence Cortana,Deactivate AI Helper,Cease Microsoft's Help
thumbnail: https://thmb.techidaily.com/4f252061500e08e9c2f2521977c5b0253a500625454298afd84e9855ed4fbb6b.jpg
---

## Techniques to Switch Off Microsoft's Assistant

 Windows Copilot, Microsoft's new AI assistant, can assist you with a variety of tasks, such as answering questions, changing system settings, and creating AI images. However, if you're not a fan of Copilot or simply don't need it, you can remove its taskbar icon or disable it entirely on your Windows 11 PC. Here, we'll show you how.

## How to Remove the Copilot Icon From the Windows 11 Taskbar

 By default, the Copilot icon appears in the Windows 11 taskbar. However, if you prefer not to have it there but still want to use it occasionally, it's easy to hide the Copilot icon. Simply right-click anywhere on an empty spot on your taskbar and select **Taskbar settings**. In the Settings window that appears, turn off the toggle next to **Copilot**.

![Remove Copilot Icon From Windows 11 Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/remove-copilot-icon-from-windows-11-taskbar.jpg)

 This should remove the Copilot icon from the taskbar. You can still access Copilot by pressing the **Win + C** keyboard shortcut in Windows 11\.

## How to Completely Disable Copilot via Group Policy Settings

 Although hiding the Copilot is quite easy, it does not turn it off completely, and you might inadvertently access it. Fortunately, you can turn off Copilot completely via the Local Group Policy Editor on PCs running the Professional, Education, or Enterprise edition of Windows 11\.

 If you are using Windows 11 Home, skip to the Registry Editor method below or use a [workaround to enable the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Press **Win + S** to access the search menu.
2. Type **gpedit.msc** in the search box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **User Configuration > Administrative Templates > Windows Components > Windows Copilot**.
5. Double-click the **Turn off Windows Copilot** policy on your right.
6. Select the **Enabled** option.
7. Hit **Apply** followed by **OK**.  
![Turn Off Windows Copilot Using the Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-windows-copilot-using-the-group-policy-editor.jpg)

 Once you complete the above steps, Copilot will be disabled on your Windows 11 PC and you won't be able to access it even with the keyboard shortcut. If you want to re-enable Copilot later, repeat the above steps and set the **Turn off Windows Copilot** policy to **Not configured** or **Disabled**.

## How to Completely Disable Copilot by Modifying Registry Files

 Another way to disable Copilot on Windows 11 involves modifying registry files. However, since editing the registry can be risky, you should follow the steps carefully. Also, be sure to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/). This will allow you to restore the registry files in case something goes wrong.

 Once you’ve done that, here’s what you need to do to disable Copilot via the Registry Editor:

1. Press **Win + R** to open the Run dialog.
2. Type **regedit** in the text box and press **Enter** to open the Registry Editor.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > Software > Policies > Microsoft > Windows**.
5. Right-click the **Windows** key and select **New > Key**. Name it **WindowsCopilot**.
6. Right-click on the **WindowsCopilot** DWORD, go to **New**, and select **DWORD (32-bit) Value** from the submenu. Name the DWORD **TurnOffWindowsCopilot**.
7. Double-click the **TurnOffWindowsCopilot** DWORD, type **1** in the text field, and click **OK**.
8. Restart your PC for the changes to take effect.  
![Turn Off Windows Copilot Using the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-windows-copilot-using-the-registry-editor.jpg)

 And that’s about it. Windows Copilot will be disabled on your PC. To re-enable it in the future, repeat the above steps and set the **TurnOffWindowsCopilot** DWORD value to 0\. You can also delete the **TurnOffWindowsCopilot** DWORD instead.

## Get Rid of Copilot on Windows 11

 While Windows Copilot is a powerful tool, not everyone may want to use it. Fortunately, it’s possible to get rid of it. The above steps will help you achieve your goal, whether you want to keep Copilot out of sight or turn it off entirely.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/shifting-paradigms-of-administrative-control-in-windows-environments/"><u>Shifting Paradigms of Administrative Control in Windows Environments</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-best-practices-for-measuring-igtv-video-effectiveness/"><u>[New] In 2024, Best Practices for Measuring IGTV Video Effectiveness</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-logitechs-full-blown-4k-webcam-complete-reveal-and-evaluation/"><u>[New] 2024 Approved  Logitech's Full-Blown 4K Webcam - Complete Reveal & Evaluation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-security-faults-and-fixes/"><u>Navigating Through Windows Security Faults & Fixes</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-shine-a-light-best-video-brightening-and-enhancement-apps/"><u>Updated Shine a Light Best Video Brightening and Enhancement Apps</u></a></li>
<li><a href="https://youtube-web.techidaily.com/-of-wisdom-youtube-tvs-unique-selling-points/"><u>Bites of Wisdom  YouTube TV's Unique Selling Points</u></a></li>
<li><a href="https://fix-guide.techidaily.com/quick-fixes-for-why-is-my-infinix-smart-8-hd-black-and-white-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Quick Fixes for Why Is My Infinix Smart 8 HD Black and White | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-overcoming-d3d11-gpu-hurdles-in-w11w10/"><u>Quick Guide to Overcoming D3D11 GPU Hurdles in W11/W10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-the-impact-reducing-unrealcefsubprocess-load-in-windows/"><u>Mitigating the Impact: Reducing UnrealCEFSubprocess Load in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-glitches-with-ps/"><u>Resolving Windows Glitches with PS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-ed-themed-windows-experience/"><u>Tailoring Ed-Themed Windows Experience</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/ultimate-list-of-websites-offering-authentic-nature-sound-archives/"><u>Ultimate List of Websites Offering Authentic Nature Sound Archives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tweak-viewer-direction-on-windows-monitor/"><u>Tweak Viewer Direction on Windows Monitor</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/unlocking-the-power-of-smart-lock-a-beginners-guide-for-poco-m6-pro-4g-users-by-drfone-android/"><u>Unlocking the Power of Smart Lock A Beginners Guide for Poco M6 Pro 4G Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-writing-rights-denied-on-windows-devices/"><u>Remedying Writing Rights Denied on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pro-wls-techniques-unlocking-the-full-power-of-wsl-2-in-win-oses/"><u>Pro WLS Techniques: Unlocking the Full Power of WSL 2 in Win OSes</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-troubleshooting-solo-earbuds/"><u>2024 Approved  Troubleshooting Solo Earbuds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modifying-windows-11-shutdown-time-for-tasks-in-progress/"><u>Modifying Windows 11 Shutdown Time for Tasks in Progress</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essentials-of-installing-works-in-the-latest-os/"><u>The Essentials of Installing Works in the Latest OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-resolve-dual-user-microsoft-errors/"><u>Strategies to Resolve Dual User Microsoft Errors</u></a></li>
<li><a href="https://ai-video.techidaily.com/best-10-hindi-video-translators-with-step-by-step-guidance/"><u>Best 10 Hindi Video Translators with Step-by-Step Guidance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-new-windows-11-experience-must-try-settings/"><u>Tailoring Your New Windows 11 Experience: Must-Try Settings</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-3-ways-to-unlock-apple-iphone-15-plus-without-passcode-or-face-id-by-drfone-ios/"><u>In 2024, 3 Ways to Unlock Apple iPhone 15 Plus without Passcode or Face ID</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-smart-spending-on-action-cams-find-your-bargains-under-100/"><u>2024 Approved  Smart Spending on ACTION Cams  Find Your Bargains Under $100</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-digital-containers-file-prop-techniques/"><u>Navigating Digital Containers: File Prop Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reestablishing-access-rectifying-unreachable-ea-services/"><u>Reestablishing Access: Rectifying Unreachable EA Services</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/brazilians-vs-europeans-a-comparative-study-on-pt-shortcuts/"><u>Brazilians vs Europeans: A Comparative Study on PT Shortcuts</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/master-your-snapchats-the-top-6-editing-apps-for-both-devices-for-2024/"><u>Master Your Snapchats  The Top 6 Editing Apps for Both Devices for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-honor-play-40c-by-drfone-android/"><u>10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Honor Play 40C</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-introduction-to-kinetic-graphic-principles/"><u>2024 Approved  Introduction to Kinetic Graphic Principles</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-video-editing-101-download-edit-and-share-your-creations-online-for-2024/"><u>New Video Editing 101 Download, Edit, and Share Your Creations Online for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-case-for-how-win11-wins-over-macos/"><u>The Case For: How Win11 Wins over macOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-guide-to-buy-and-install-adobe-reader-via-ms-store/"><u>Simplified Guide to Buy and Install Adobe Reader via MS Store</u></a></li>
<li><a href="https://extra-hints.techidaily.com/21-edition-deep-dive-unraveling-vegas-pros-complexities-for-2024/"><u>'21 Edition Deep-Dive  Unraveling Vegas Pro’s Complexities for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/system-patch-up-reviving-synapse-in-latest-windows/"><u>System Patch-Up: Reviving Synapse in Latest Windows</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-universal-method-for-recording-your-preferred-youtube-stream-no-matter-the-device/"><u>[Updated] 2024 Approved  Universal Method for Recording Your Preferred YouTube Stream, No Matter the Device</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-improve-your-video-production-best-free-video-stabilization-tools/"><u>New Improve Your Video Production Best Free Video Stabilization Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-the-empty-folder-error-message-on-win-11/"><u>Removing the 'Empty Folder' Error Message on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-workflow-integrating-wordpad-shortcuts-into-context-menus-on-windows-11/"><u>Streamlining Workflow: Integrating WordPad Shortcuts Into Context Menus on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-pcs-dns-cache-efficiently/"><u>Revamp Your PC's DNS Cache Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-functionality-of-microsofts-phone-link-an-introduction/"><u>The Functionality of Microsoft's 'Phone Link': An Introduction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-address-offline-lsa-warning/"><u>Steps to Address Offline LSA Warning</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-3-ways-to-export-contacts-from-apple-iphone-xs-max-to-excel-csv-and-vcard-easily-drfone-by-drfone-transfer-from-ios/"><u>In 2024, 3 Ways to Export Contacts from Apple iPhone XS Max to Excel CSV & vCard Easily | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-windows-11-password-strategy/"><u>Transforming Windows 11 Password Strategy</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-pure-android-capturer-unspotted-and-unobstructed/"><u>[Updated] Pure Android Capturer  Unspotted & Unobstructed</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-your-essential-guide-to-discord-stickers/"><u>[New] In 2024, Your Essential Guide to Discord Stickers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedily-seek-synonyms-with-win11-dictionary/"><u>Speedily Seek Synonyms with Win11 Dictionary</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-discontinue-repeated-edge-icons/"><u>Solutions to Discontinue Repeated Edge Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modifying-password-policy-update-lockout-value-post-incorrect-attempts/"><u>Modifying Password Policy: Update Lockout Value Post Incorrect Attempts</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-a-step-by-step-approach-to-generating-income-with-trailers/"><u>[New] In 2024, A Step-by-Step Approach to Generating Income with Trailers</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-turn-your-videos-into-dvds-with-these-3-easy-methods/"><u>New 2024 Approved Turn Your Videos Into DVDs with These 3 Easy Methods</u></a></li>
</ul></div>
