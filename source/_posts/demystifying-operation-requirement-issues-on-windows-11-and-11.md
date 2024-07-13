---
title: Demystifying Operation Requirement Issues on Windows 11 & 11
date: 2024-07-12T17:10:48.689Z
updated: 2024-07-13T17:10:48.689Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Demystifying Operation Requirement Issues on Windows 11 & 11
excerpt: This Article Describes Demystifying Operation Requirement Issues on Windows 11 & 11
keywords: Windows 11 OS Issue,Windows Update Troubleshooting,Win11 Installation Guide,Win11 Requirements Explained,Windows Performance Optimization,Resolving Win11 Errors,Compatibility Issues in Win11
thumbnail: https://thmb.techidaily.com/6fd0cef62e823c305fb86e64196b6559e3c33c787060e717fb517085eb725bc3.jpg
---

## Demystifying Operation Requirement Issues on Windows 11 & 11

 Some users have reported in support forum posts that error 740 occurs when they try to run programs or access folders on Windows PCs. The error 740 message says, “The requested operation requires elevation.” Users can’t access software, folders, or files for which error 740 occurs.

 This is how you can fix error 740 within Windows 10 and 11\.

## 1\. Run the Affected Programs With Admin Rights

 The error 740 message mentions the need for operation elevation. That’s a hint to try running affected programs with elevated (administrator) rights. Check out this guide on [always running apps as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) to set affected EXE files to run with elevated rights.

![The Run this program as an administrator checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-this-program-as-an-administrator.jpg)

## 2\. Set Programs to Run in Compatibility Mode

 It’s also recommended to set older programs to run in compatibility mode. Doing so might address a compatibility issue causing error 740\. You can set an affected program to run in compatibility mode like this:

1. Open the affected software’s installation within File Explorer.
2. Right-click an affected program’s EXE (application file) and select **Properties** \> **Compatibility**.
3. Select **Run this program in compatibility mode for** and choose Windows 8 or an older platform on the drop-down menu. It’s best to select the Windows platform for which the publisher originally released the software.  
![The Run this program in compatibility mode drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-this-program-in-compatibility-mode.jpg)
4. Press the **Apply** \> **OK** buttons to set the compatibility mode setting.

## 3\. Turn Off the User Account Control Feature

 User Account Control is the security feature that throws up notifications when programs try to make changes. UAC could be a potential cause of error 740 when it’s set very high. So, try turning off UAC before running affected apps. Our [guide to disabling User Account Control](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) tells you how to turn off that feature.

![The User Account Control Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/user-account-control-settings.jpg)

## 4\. Adjust Folder Permission Settings

 This potential resolution is recommended for users who can’t access specific folders because of error 740\. In that scenario, this error can be a folder permissions issue that selecting the **Replace all child object permission entries** option could feasibly address.

 Try selecting the **Replace all child object permission** setting for an affected folder as follows:

1. Press **Win + E** to bring up File Explorer.
2. Open whatever directory contains the folder for which error 740 occurs.
3. Right-click the affected folder and select that directory’s **Properties** option.
4. Select **Security** on the window’s tab bar.
5. Click **Advanced** to access more security settings.  
![The Security tab and Advanced button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-security-tab3.jpg)
6. Select the **Replace all child object permissions entries with inheritable permission entries from this object** checkbox.  
![The Replace all child object permission entries checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/replace-all-child-objects-option.jpg)
7. Click **Apply** on the Advanced Security Settings window.
8. Select **Yes** when asked to continue.
9. Exit the folder’s properties window and restart your PC.

## 5\. Modify the Behavior of the UAC Elevation Prompt

 If your Windows PC has the Group Policy Editor, try changing the behavior of UAC’s elevation prompt with that tool. Selecting the **Elevate without prompting** setting for the User Account Control: Behavior policy could fix error 740 for some users.

 You can select that option within Windows Enterprise and Pro editions like this:

1. Open the Local Group Policy Editor. If you need help, check out the [ways to open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
2. Next, double-click **Computer Configuration** to expand that sidebar navigation option.
3. Double-click **Windows Settings** and select **Security S** **ettings**.
4. Then go to **Local Policies** and **Security Options** to access User Account Control Policy settings.  
![Security Options within Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/security-options.jpg)
5. Double-click the **User Account Control: Behavior of the elevation prompt for administrators in Admin Approval Mode** policy.
6. Select the **Elevate without prompting** option on the drop-down menu.  
![The Elevate without prompting option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/elevate-without-prompting.jpg)
7. Click **Apply** to set the **Elevate without prompting policy**.
8. Select **OK** to close the policy setting’s window.
9. Then reboot Windows after closing Group Policy Editor.

## 6\. Disable Admin Approval Mode

 Admin Approval Mode prompts administrative users for task permissions when enabled. It’s a strict Group Policy Editor security policy that can potentially cause elevation issues. Follow these steps to turn off Admin Approval Mode.

1. Go to **Security Options** in Group Policy Editor as outlined for steps one to four of resolution five.
2. Double-click the **User Account Control: Admin Approval Mode for the Built-in Administrator account** policy setting.  
![The Admin Approval Mode policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/admin-approval-mode-policy.jpg)
3. Click the **Disabled** radio button if this policy is enabled.  
![the-enabled-radio-button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enabled-radio-button.jpg)
4. Select **Apply** to turn off Admin Approval Mode.
5. To close the policy window, select the **OK** option.

## 7\. Disable Third-Party Antivirus Software Packages

 Have you installed a third-party antivirus or security app on your PC? If you have, your third-party security software could be causing error 740 by blocking the EXE file you’re trying to run. This can happen when the antivirus software flags the application file as malicious.

 The potential solution, in this case, is to temporarily disable third-party antivirus software before trying to run affected programs. Look for and select an option that turns off the antivirus shield by right-clicking on the antivirus software’s system tray icon. If there are time options available, select to turn the real-time protection off for about an hour or so.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 If disabling the security software works, you don’t necessarily have to turn the security software off whenever you want to run the application file. Your antivirus software will probably include an exclusion list to which you can add trustworthy program file exceptions. Add the affected EXE file there to exclude it from the antivirus protection.

## 8\. Migrate to a New Admin User Account

 If the “requested operation requires elevation” error persists after trying other resolutions, your user account might be corrupted. Then you might need to create and utilize a new admin account to resolve this issue. You can migrate to that account by copying files from your old user account into the new one.

![The Add account option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-account-option.jpg)

 To apply this troubleshooting method for the “requested operation requires elevation” error, follow the instructions within this article about [how to fix Windows issues by creating new user accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/). First, you’ll need to set up and sign in to the new admin account to see if the error occurs there. If not, transfer user files into the new account as covered there.

## Get Error 740 Sorted on Windows

 The “requested operation requires elevation” error is an inconvenient admin access privilege issue many users have needed to fix. Users have resolved that issue by applying the potential resolutions in this guide. So, try applying those fixes for the “requested operation requires elevation” error in the order specified to find one that works on your Windows 10 or 11 PC.

 This is how you can fix error 740 within Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/tackling-dxgi-failure-in-windows-fix-for-removed-devices/"><u>Tackling DXGI Failure in Windows: Fix for Removed Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-explore-conceal-and-reveal-folders/"><u>Streamlining Windows Explore: Conceal and Reveal Folders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-system-details-locate-windows-ip-and-mac-via-powershell/"><u>Unveiling System Details: Locate Windows' IP and MAC via Powershell</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-overcoming-windows-notepad-hangups/"><u>Tips for Overcoming Windows Notepad Hangups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-fn-key-tasks-in-windows-1011-oses/"><u>Tailoring FN Key Tasks in Windows 10/11 OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-synchronized-note-taking-in-windows-11/"><u>The Art of Synchronized Note-Taking in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-power-of-voice-activated-accessibility-features/"><u>Unlocking the Power of Voice-Activated Accessibility Features</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/gigglegrid-create-social-media-laughs-in-seconds-for-2024/"><u>GiggleGrid  Create Social Media Laughs in Seconds for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ten-clear-indicators-of-pc-needs-a-factory-start/"><u>Ten Clear Indicators of PC Needs a Factory Start</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-update-processes-context-menu-update-option-for-win11-users/"><u>Streamlining Update Processes: Context Menu Update Option for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-full-potential-of-policy-editor-in-windows-11/"><u>Unlock the Full Potential of Policy Editor in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/syncing-up-with-microsoft-sql-on-malwarebytes-after-disconnect/"><u>Syncing Up with Microsoft SQL on Malwarebytes After Disconnect</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-from-ground-to-greatness-photos-on-a-stretch/"><u>[New] From Ground to Greatness  Photos on a Stretch</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/enter-the-world-of-online-promotion-exclusive-free-youtube-banner-access/"><u>Enter the World of Online Promotion  Exclusive Free YouTube Banner Access</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-boosting-your-youtube-shorts-profits-key-requirements-and-earning-potential/"><u>In 2024, Boosting Your Youtube Shorts Profits  Key Requirements & Earning Potential</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-instagram-stop-motion-101-tips-and-tricks-for-beginners-for-2024/"><u>New Instagram Stop Motion 101 Tips and Tricks for Beginners for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoidance-and-correction-of-windows-error-0xc00000f/"><u>Avoidance and Correction of Windows Error: 0Xc00000f</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-ultimate-breakdown-decoding-comprehensiveness-of-xvideo-hub-review/"><u>[Updated] The Ultimate Breakdown  Decoding Comprehensiveness of XVideo Hub Review</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/how-to-get-youtube-sponsorship-for-small-channels-easy/"><u>How to Get YouTube Sponsorship for Small Channels (Easy)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-to-batch-installing-apps-using-winstall-in-windows-11/"><u>A Step-by-Step Approach to Batch Installing Apps Using Winstall in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-customized-keyboard-tricks-for-win-os/"><u>Boost Efficiency: Customized Keyboard Tricks for WIN OS</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-chortlecraft-customize-funny-digital-images/"><u>2024 Approved  ChortleCraft  Customize Funny Digital Images</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-a-listers-voice-alteration-essentials-comprehensive-guides-to-transforming-your-singing-style/"><u>In 2024, A-Listers Voice Alteration Essentials Comprehensive Guides to Transforming Your Singing Style</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-screen-seizing-specialists-the-best-browser-recorder-tools-ranked/"><u>2024 Approved  Screen Seizing Specialists  The Best Browser Recorder Tools Ranked</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-majestic-visual-chronicles-compiler-suite/"><u>[New] Majestic Visual Chronicles Compiler Suite</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-chrome-clock-error-ahead-or-behind-windows-edition/"><u>Adjusting Chrome Clock Error: Ahead or Behind? (Windows Edition)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-smartphone-potential-as-windows-microphone/"><u>Unlocking Smartphone Potential as Windows Microphone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-navigating-discords-user-imagery-like-a-pro/"><u>[New] 2024 Approved  Navigating Discord's User Imagery Like a Pro</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-mastering-the-art-of-screen-enhancement-in-teams/"><u>[New] Mastering the Art of Screen Enhancement in Teams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-warning-indicators-that-call-for-a-full-reboot/"><u>5 Warning Indicators That Call For a Full Reboot</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-top-10-adobe-premiere-elements-alternatives-for-2024/"><u>New Top 10 Adobe Premiere Elements Alternatives for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-trouble-with-iphone-6-swipe-up-try-these-11-solutions-drfone-by-drfone-ios/"><u>In 2024, Trouble with iPhone 6 Swipe-Up? Try These 11 Solutions | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/full-screen-pro-tips-and-tricks-for-editors-for-2024/"><u>Full Screen Pro Tips and Tricks for Editors for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-keep-windows-sound-preferences-intact/"><u>Strategies to Keep Windows Sound Preferences Intact</u></a></li>
<li><a href="https://extra-resources.techidaily.com/capturing-the-echoes-of-yesteryears-scanning-and-storing-vintage-prints/"><u>Capturing the Echoes of Yesteryears  Scanning and Storing Vintage Prints</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sidestep-common-snip-and-sketch-screenshot-hurdles-4-fixes/"><u>Sidestep Common Snip & Sketch Screenshot Hurdles: 4 Fixes</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-techniques-to-transfer-data-from-samsung-galaxy-a05s-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Techniques to Transfer Data from Samsung Galaxy A05s to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-failure-windows-update-issue-code-0x80242016/"><u>Avoid Failure: Windows Update Issue Code 0X80242016</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-unveiling-hidden-potential-edit-wonders-on-snapchat-app/"><u>[Updated] 2024 Approved  Unveiling Hidden Potential  Edit Wonders on Snapchat App</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-obs-upgrade-tips-clearer-footage/"><u>[Updated] 2024 Approved  OBS Upgrade Tips  Clearer Footage</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-in-2024-if-you-have-transferred-to-the-mac-platform-you-may-need-virtualdub-for-mac-alternatives-because-virtualdub-only-supports-windows-os-nativel/"><u>Updated In 2024, If You Have Transferred to the Mac Platform, You May Need VirtualDub for Mac Alternatives because VirtualDub only Supports Windows OS Natively</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-average-gain-for-youtubers-per-ad-exposure/"><u>In 2024, Average Gain for YouTubers per Ad Exposure?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-cant-you-see-a-drive-letter-on-your-windows-machine/"><u>Why Can't You See a Drive Letter on Your Windows Machine?</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-youtube-triumphs-how-to-turn-your-cell-phone-into-an-editing-machine/"><u>[New] YouTube Triumphs  How to Turn Your Cell Phone Into an Editing Machine</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-realme-12-5g-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Transfer Music from Realme 12 5G to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-your-window-11-interface-for-maximum-efficiency-and-satisfaction/"><u>Tailor Your Window 11 Interface for Maximum Efficiency and Satisfaction</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-building-your-own-youtube-organization-toolkit-the-watch-later-way/"><u>[Updated] Building Your Own YouTube Organization Toolkit  The Watch Later Way</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-administrative-tasks-a-new-approach-to-windows-uac/"><u>Streamlining Administrative Tasks: A New Approach to Windows UAC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silent-data-exchange-safeguarding-files-across-ws11w10/"><u>Silent Data Exchange: Safeguarding Files Across WS11/W10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-instructional-paper-on-windows-11s-speed-boost-feature/"><u>The Ultimate Instructional Paper on Windows 11'S Speed Boost Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-print-again-in-win11/"><u>Step-By-Step Guide to Print Again in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-missing-d3dx939dll-in-win11/"><u>Steps to Fix Missing D3DX9_39.dll in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719216451577-achieving-total-screen-capture-mastery-using-snip-and-sketch/"><u>Achieving Total Screen Capture Mastery Using Snip & Sketch</u></a></li>
</ul></div>
