---
title: Adjust Touch Keyboard Default in Windows 11 Pro
date: 2024-07-12T18:05:16.147Z
updated: 2024-07-13T18:05:16.147Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjust Touch Keyboard Default in Windows 11 Pro
excerpt: This Article Describes Adjust Touch Keyboard Default in Windows 11 Pro
keywords: Win11 Keyboard Adjust,Default Keyboard Set,Change Touch Keys,Windows Touch Settings,Keyboard Config W11,Pro Windows Keyboard Adj,Update Touch Key Prefs
thumbnail: https://thmb.techidaily.com/44cba3f77a25fb10a15058a95ecd605b31dd154fe2d91aae028e5e688022e444.jpg
---

## Adjust Touch Keyboard Default in Windows 11 Pro

 Are you using a Windows touchscreen device and experiencing keyboard issues? This often occurs when certain keys are difficult to use or scrolling becomes tricky because the keyboard pops up in the wrong spot.

 To help with this issue, we'll explain two methods to reset the default opening position of your touch keyboard in Windows 11\. The first method requires running a batch file, while the second involves tweaking the Windows Registry Editor.

Let's explore each one.

## 1\. Tweak Registry Editor to Reset Touch Keyboard Default Open Position

 The Registry Editor is an advanced tool and requires caution when editing. But if you want to reset the default opening position of the touch keyboard efficiently, this is the method to use. However, as I have said before, you have to be especially careful when editing the Registry Editor as any mistake could cause serious damage.

 It is always a good idea to [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) or to take a [backup of the registry editor](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before starting. This can help if something goes wrong. It is now time to reset the default open position of the touch keyboard. To do so, follow these steps:

1. Press**Win + R** on your keyboard to open the Run dialog box.
2. Type**regedit** in the text box and press Enter. This will launch the Registry Editor.
3. Click**Yes** if the UAC (User Account Control) window asks for permission.
4. Once you're in the Registry Editor, navigate to this location:  
`HKEY_CURRENT_USER\Software\Microsoft\TabletTip\1.7`  
 Alternatively, you can copy and paste the given path into the Registry Editor's address bar. This will take you to the specified location.
5. On the left side of the menu, select the**1.7** folder.  
![Tweak Registry Editor to Reset Touch Keyboard Default Open Position](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/tweak-registry-editor-to-reset-touch-keyboard-default-open-position.jpg)
6. Then go to its corresponding right pane, where you will find the**OptimizedKeyboardRelativeXPositionOnScreen** REG\_DOWRD value. Right-click on the key and delete it.
7. Similarly, delete the**OptimizedKeyboardRelativeYPositionOnScreen** key value in the same folder.

 After deleting both values, close the Registry Editor and restart your PC to apply the changes. Now, when you open the touch keyboard, it will start showing up at the default opening position.

## 2\. Run a Batch File to Reset the Touch Keyboard's Default Open Position

 Resetting the default opening position of your touch keyboard can be done quickly and easily by running a batch file. This method is especially useful if you prefer to automate the reset process instead of manually tweaking the registry editor. Here is how to do it.

 To get started, you first need to open the Notepad application. For this, you can type "Notepad" in either Windows Search or the Run dialog box and press**Enter** .

 Once you're in Notepad, copy and paste the following code into it:

`@echo off  
REG Delete "HKCU\SOFTWARE\Microsoft\TabletTip\1.7" /V OptimizedKeyboardRelativeXPositionOnScreen /F  
REG Delete "HKCU\SOFTWARE\Microsoft\TabletTip\1.7" /V OptimizedKeyboardRelativeYPositionOnScreen /F  
taskkill /f /im explorer.exe  
start explorer.exe`

 Now click**File** in the upper-left corner and select**Save As** from the menu list.

![Run Batch File to Reset Touch Keyboard Default Open Position](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-batch-file-to-reset-touch-keyboard-default-open-position.jpg)

 In the File name field, type "ResetTouch.bat", and choose**All Files** from the Save as type. After that, select Desktop from the left-hand side and click**Save** .

 Once the batch file is saved, close the Notepad window. Next, double-click**ResetTouch.bat** on your Desktop to run it. This should reset your touch keyboard's default open position.

## Resetting the Default Position of the Touch Keyboard

 If you're using a Windows touchscreen device, typing with a touch keyboard can be easy. However, you might have noticed an inconvenience where the keyboard opens in an awkward position.

 This can make typing on specific keys difficult, especially if you're used to accessing the keyboard from a certain spot. To fix this issue, refer to this guide on resetting the default open position of your touch keyboard.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/addressing-winrars-summation-anomalies-with-six-fixes/"><u>Addressing WinRAR's Summation Anomalies with Six Fixes</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-from-finish-to-start-the-art-of-negative-playback-on-instagram/"><u>[New] From Finish to Start  The Art of Negative-Playback on Instagram</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-crafting-captivating-tiktok-reacts-filmmakers-guide-with-filmora-pro/"><u>[Updated] Crafting Captivating TikTok Reacts  Filmmaker’s Guide with Filmora Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-user-permissions-issues-with-organizational-settings-in-windows-11/"><u>Addressing User Permissions Issues with Organizational Settings in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-gaming-experience-optimize-amd-graphics-on-pc/"><u>Amplify Gaming Experience: Optimize AMD Graphics on PC</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-google-frp-lock-from-xiaomi-redmi-12-5g-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock from Xiaomi Redmi 12 5G Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-epic-game-launcher-stubbornness-on-w11-computers/"><u>Avoid Epic Game Launcher Stubbornness On W11 Computers</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-stolen-apple-iphone-12-pro-in-different-conditionsin-by-drfone-ios/"><u>How To Unlock Stolen Apple iPhone 12 Pro In Different Conditionsin</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-amd-graphics-efficiency-windows-11-updates-guide/"><u>Boosting AMD Graphics Efficiency: Windows 11 Updates Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-application-runtime-to-compensate-for-lack-of-qt-plugins/"><u>Adjusting Application Runtime to Compensate for Lack of Qt Plugins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automating-wifi-network-deletion-in-win-11/"><u>Automating Wifi Network Deletion in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-practices-for-command-line-access-management/"><u>Best Practices for Command-Line Access Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/aligning-chrome-and-system-time-windows-sync-tips/"><u>Aligning Chrome and System Time (Windows Sync Tips)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-common-fails-keeping-your-temp-folder-valid-in-win11/"><u>Avoiding Common Fails: Keeping Your Temp Folder Valid in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/alter-time-tracks-essential-windows-tools-to-edit-file-dates/"><u>Alter Time Tracks: Essential Windows Tools to Edit File Dates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ascertain-if-your-computer-meets-11th-gen-os-needs/"><u>Ascertain If Your Computer Meets 11Th Gen OS Needs</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-final-cut-pro-x-how-to-crop-an-image/"><u>Updated 2024 Approved Final Cut Pro X How to Crop an Image</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-best-3-oppo-a56s-5g-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>In 2024, Best 3 Oppo A56s 5G Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-and-ranking-video-codecs-for-windows-pcs/"><u>Analyzing and Ranking Video Codecs for Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-and-controlling-rgb-on-windows-11-pcs/"><u>Adjusting and Controlling RGB on Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-uninstallation-block-in-win-11-edition/"><u>Addressing Uninstallation Block in Win 11 Edition</u></a></li>
<li><a href="https://audio-editing.techidaily.com/the-essential-list-6-high-performance-voice-alteration-apps-for-2024/"><u>The Essential List 6 High-Performance Voice Alteration Apps for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-vivo-s18e-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>How to Cast Vivo S18e to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/easily-unlock-your-oppo-reno-11f-5g-device-sim-by-drfone-android/"><u>Easily Unlock Your Oppo Reno 11F 5G Device SIM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplified-audio-top-4-applications-to-surpass-windows-100-threshold/"><u>Amplified Audio: Top 4 Applications to Surpass Windows’ 100%% Threshold</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-11-screen-tick/"><u>Addressing Window's 11 Screen Tick</u></a></li>
<li><a href="https://win11-tips.techidaily.com/biometric-permissions-managing-domain-users-in-w11/"><u>Biometric Permissions: Managing Domain Users in W11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-spin-into-popularity-the-art-of-video-reversal-on-instagram/"><u>[Updated] Spin Into Popularity  The Art of Video Reversal on Instagram</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-common-mistakes-fixing-office-error-0x80041015/"><u>Avoiding Common Mistakes Fixing Office Error 0X80041015</u></a></li>
<li><a href="https://video-capture.techidaily.com/essential-tools-for-clear-images-for-2024/"><u>Essential Tools for Clear Images for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-fn-key-functions-windows-11-edition/"><u>Altering FN Key Functions: Windows 11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-outlook-speed-for-a-smooth-win-experience/"><u>Amplify Outlook Speed for a Smooth WIN Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-defender-in-windows-11-how-to-turn-it-off/"><u>Avoiding Defender in Windows 11: How to Turn It Off</u></a></li>
<li><a href="https://win11-tips.techidaily.com/are-your-windows-11-desktop-icons-shrinking-heres-how-to-fix-that/"><u>Are Your Windows 11 Desktop Icons Shrinking? Here's How to Fix That</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-setting-up-automatic-deletions-in-win11/"><u>Boost Productivity: Setting Up Automatic Deletions in Win11</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-the-best-ispoofer-alternative-to-try-on-vivo-s17t-drfone-by-drfone-virtual-android/"><u>In 2024, The Best iSpoofer Alternative to Try On Vivo S17t | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/artists-rejoice-best-windows-11-drawing-apps/"><u>Artists Rejoice: Best Windows 11 Drawing Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-unviewable-documents-error-in-microsoft-office-mail/"><u>Addressing 'Unviewable' Documents Error in Microsoft Office Mail</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-a-step-by-step-guide-to-the-taskbars-search-bar-in-windows-11/"><u>Boost Efficiency: A Step-By-Step Guide to the Taskbar’s Search Bar in Windows 11</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-a-comprehensive-overview-of-cost-free-cloud-communication-software-for-2024/"><u>[Updated] A Comprehensive Overview of Cost-Free Cloud Communication Software for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-top-6-cheapest-action-cameras-to-buy-under-100/"><u>2024 Approved  Top 6 Cheapest Action Cameras to Buy Under $100</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-perfecting-the-introduction-writing-impressive-summaries/"><u>2024 Approved  Perfecting the Introduction  Writing Impressive Summaries</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-examining-the-financial-success-strategies-of-t-series-on-youtube/"><u>[New] 2024 Approved  Examining the Financial Success Strategies of T-Series on YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-disk-space-how-to-use-windows-autodeleting-feature/"><u>Boost Disk Space: How to Use Windows' AutoDeleting Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beyond-bios-artificial-intelligence-for-windows/"><u>Beyond BIOS: Artificial Intelligence for Windows</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-strategies-for-streaming-fb-live-on-zoom-platform/"><u>[Updated] Strategies for Streaming FB Live on Zoom Platform</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/-level-landing-low-cost-profitable-youtube-platforms/"><u>Entry Level Landing  Low-Cost, Profitable YouTube Platforms</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-turn-standard-alerts-into-personalized-unique-sounds-on-android-devices/"><u>In 2024, Turn Standard Alerts Into Personalized, Unique Sounds on Android Devices</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-3-effective-ways-to-unlock-icloud-account-without-password-from-apple-iphone-7-plus-by-drfone-ios/"><u>In 2024, 3 Effective Ways to Unlock iCloud Account Without Password From Apple iPhone 7 Plus</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-gmail-password-on-google-pixel-fold-devices-by-drfone-android/"><u>How to Reset Gmail Password on Google Pixel Fold Devices</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/updated-top-10-streaming-services-worth-a-try-for-2024/"><u>Updated Top 10 Streaming Services Worth a Try for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/unlocking-iphone-12-passcode-without-a-computer-by-drfone-ios/"><u>Unlocking iPhone 12 Passcode without a Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blending-windows-innovations-into-linux/"><u>Blending Windows Innovations Into Linux</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-conquering-facebook-audiences-live-stream-excellence-with-wirecast/"><u>2024 Approved  Conquering Facebook Audiences  Live Stream Excellence with Wirecast</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-enhancing-m4a-listening-pleasure-advanced-tips-for-android-users-for-2024/"><u>Updated Enhancing M4A Listening Pleasure Advanced Tips for Android Users for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-transform-your-asmr-experience-into-proficiently-produced-videos/"><u>[New] 2024 Approved  Transform Your ASMR Experience Into Proficiently Produced Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-video-transformers-from-the-world-of-windows/"><u>Best Video Transformers From the World of Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/3-ways-for-android-pokemon-go-spoofing-on-infinix-note-30i-drfone-by-drfone-virtual-android/"><u>3 Ways for Android Pokemon Go Spoofing On Infinix Note 30i | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-strategies-in-group-policy-with-gpresult/"><u>Advanced Strategies in Group Policy with GPResult</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-slow-response-times-after-adding-an-additional-screen/"><u>Avoid Slow Response Times After Adding an Additional Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beating-the-default-shrinking-in-winos/"><u>Beating the Default Shrinking in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-techniques-in-powertoys-for-file-security/"><u>Advanced Techniques in PowerToys for File Security</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-reno-11-pro-5g-frp-by-drfone-android/"><u>In 2024, Step-by-Step Tutorial How To Bypass Oppo Reno 11 Pro 5G FRP</u></a></li>
</ul></div>
