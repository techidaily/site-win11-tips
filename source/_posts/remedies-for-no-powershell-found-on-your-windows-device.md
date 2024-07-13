---
title: Remedies for No PowerShell Found on Your Windows Device
date: 2024-07-12T16:47:26.204Z
updated: 2024-07-13T16:47:26.204Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Remedies for No PowerShell Found on Your Windows Device
excerpt: This Article Describes Remedies for No PowerShell Found on Your Windows Device
keywords: PowerShell Woes,Fixing No PowerShell,PowerShell Not Available,Resolve PowerShell Errors,Enable PowerShell,Troubleshoot Missing PowerShell,Restore Windows Powershell
thumbnail: https://thmb.techidaily.com/046b51c249713a58e7f91807e73ec08e3a40b03e4add7fe4a3b9657a9796ae66.jpg
---

## Remedies for No PowerShell Found on Your Windows Device

 PowerShell is a handy tool that lets you automate tasks, troubleshoot various errors, and manage a variety of Windows settings. But what if it suddenly goes missing from your computer?

 If you use PowerShell frequently, it can be aggravating when Windows cannot find it. Thankfully, it’s possible to restore the missing PowerShell with a few troubleshooting tips. In this post, we'll walk you through all of them.

## 1\. Make Sure Windows PowerShell Is Enabled

 On Windows, you can enable or disable optional features and programs from the Control Panel. To start, you need to ensure that PowerShell isn’t disabled on your computer. Here’s how to check.

1. Press**Win + R** to open the Run dialog.
2. Type**control** in the box and press**Enter** to open Control Panel.
3. Click the drop-down menu in the top right corner to select**Large icons** .
4. Go to**Programs and Features** .
5. Click the**Turn Windows features on or off** link from the left pane.
6. When the User Account Control (UAC) prompt appears, select**Yes** to continue.
7. In the Windows Features dialog, locate**Windows PowerShell** and select its checkbox.
8. Click**OK** to save the changes.  
![Enable PowerShell on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Enable-PowerShell-on-Windows.jpg)

 Restart your computer after this (see [how to restart a Windows computer](https://www.makeuseof.com/windows-restart-methods/) ) and then try to launch PowerShell using the search menu.

## 2\. Launch PowerShell Using Run Command or File Explorer

 If you are unable to open PowerShell via the search menu, you can try using the Run dialog box. Press**Win + R** to open the Run dialog. Type**powershell** in the box and press**Enter** . If you want to launch PowerShell with admin rights, press**Ctrl + Shift + Enter** instead.

![Open PowerShell via Run Command on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Open-PowerShell-via-Run-Command-on-Windows.jpg)

 You can also open PowerShell from the File Explorer address bar. To do so, press**Win + E** to open File Explorer. Type**PowerShell** in the address bar and press**Enter** .

## 3\. Create a Desktop Shortcut for PowerShell

 Windows may fail to open PowerShell if it does not know the exact file path to the PowerShell executable file. If that’s the case, you can manually locate the PowerShell executable file on your computer and create a desktop shortcut for it. Here are the steps for doing the same.

1. Right-click on the**Start icon** to open the Power User menu and select**File Explorer** from the list.
2. Navigate to**This PC** .
3. Head over to**C: > Windows > SysWOW64** and locate**WindowsPowerShell** folder.
4. Open the WindowsPowerShell folder and go to the**v1.0** folder.
5. Double-click on the PowerShell executable file and see if it works. If it does, right-click on it and select**Send to > Desktop (create shortcut)** .  
![Create Desktop Shortcut for PowerShell on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Create-Desktop-Shortcut-for-PowerShell-on-Windows.jpg)

 You can then use the newly created desktop shortcut to launch PowerShell. For added convenience, you can assign a keyboard shortcut to PowerShell. To learn more about this, check our guide on [how to assign keyboard shortcuts to programs in Windows](https://www.makeuseof.com/windows-keyboard-shortcuts-programs/) .

## 4\. Scan Your Computer for Corrupted System Files

 Damaged or corrupted system files can also interfere with Windows operations and prevent PowerShell from launching. Fortunately, your Windows PC comes with a few built-in tools, such as SFC (System File Checker) and DISM (or Deployment Image Servicing and Management) that can help you with such issues. If Windows suffers from system file corruption, running these tools will fix the problem.

To run the SFC scan on Windows:

1. Click the magnifying glass icon on the taskbar or press**Win + S** to open the search menu.
2. Type**command prompt** in the search box and select**Run as administrator** from the right panel.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Type**SFC /scannow** in the console and press**Enter** .

 The SFC scan will start verifying the integrity of your system files and fix any issues with them. The scan might take a while, so be patient.

 Next, you need to run the DISM scan. This is another diagnostic tool that Windows offers. It can automatically detect any issues with the system image and fix them. If you want to learn more about them, check out our guide on the [differences between CHKDSK, SFC, and DISM](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) .

 To run DISM,[open Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) again. Paste the following command in the console and press**Enter** .

`DISM.exe /Online /Cleanup-image /Restorehealth`

![DISM Scan Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/DISM-Scan-Windows.jpg)

 Wait for the command to execute successfully, and then restart your PC. Following that, see if Windows can find PowerShell on your computer.

## 5\. Update Windows PowerShell

 If Windows still can't find PowerShell at this point, there could be a problem with the PowerShell app itself. You can try updating the PowerShell app to see if that makes any difference.

To update PowerShell on Windows:

1. Press**Win + X** to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. When the User Account Control (UAC) prompt shows up, select**Yes** .
4. Type the following command and press**Enter** .  
`winget install --id Microsoft.Powershell --source winget`  
![Update PowerShell on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Update-PowerShell-on-Windows.jpg)

 Windows will download and install the most recent version of PowerShell. Following that, you should be able to access PowerShell.

 Using Command Prompt isn't the only way to update PowerShell on Windows. If you want to learn other methods, check our guide on [how to install or update PowerShell on Windows](https://www.makeuseof.com/windows-11-powershell-install-update/) .

## 6\. Create a New User Account

 It's possible that the PowerShell not opening problem is limited to your current user account. In that case, you can create and switch to a new user account and see if that works.

To create a new user account on Windows, use these steps.

1. Open the start menu and click the**gear icon** to open the Settings app.
2. Navigate to**Accounts** .
3. Select**Other users** .
4. Click the**Add account** button.
5. Click on **I don't have this person's sign-in information** and follow the on-screen prompts to create a new user account.  
![Microsoft Account Sign-In](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Microsoft-Account-Sign-In.jpg)

 Sign in with your newly created account, and see if Windows can find PowerShell now.

## Access Windows PowerShell Again

 Hopefully, one of the above fixes has proven useful, and you're able to access PowerShell once again. If not, you may have to consider resetting your Windows computer as a last resort.

 PowerShell isn't the only command-line tool available on Windows. You can also use the Command Prompt to communicate with your system.


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
<li><a href="https://win11-tips.techidaily.com/a-guide-to-customize-win11-mouse-controls/"><u>A Guide to Customize Win11 Mouse Controls</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-beyond-facetime-on-android-top-10-virtual-communication-applications/"><u>New Beyond FaceTime on Android Top 10 Virtual Communication Applications</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/unlock-iphone-13-mini-with-forgotten-passcode-different-methods-you-can-try-drfone-by-drfone-ios/"><u>Unlock iPhone 13 mini With Forgotten Passcode Different Methods You Can Try | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-missing-mic-during-screencast-with-powerpoint/"><u>Addressing Missing Mic During Screencast with PowerPoint</u></a></li>
<li><a href="https://youtube-data.techidaily.com/levating-user-experience-with-personalized-youtube-card-implementation/"><u>[New] Elevating User Experience with Personalized YouTube Card Implementation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-and-amending-system-call-failures-in-modern-windows/"><u>Addressing and Amending System Call Failures in Modern Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-century-of-change-the-windows-taskbar/"><u>A Century of Change: The Windows Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-windows-in-minutes-with-handy-shorthand/"><u>Ace Windows in Minutes with Handy Shorthand</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-earning-potential-for-videos-amassing-1-million-views/"><u>2024 Approved  Earning Potential for Videos Amassing 1 Million Views</u></a></li>
<li><a href="https://extra-tips.techidaily.com/unleashing-potential-a-guide-for-solitary-showrunners/"><u>Unleashing Potential  A Guide for Solitary Showrunners</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-a-beginners-guide-to-embedding-youtube-playlists-in-code/"><u>[New] A Beginner's Guide to Embedding YouTube Playlists in Code</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719364066200-microsofts-helpers-quick-fixes-for-window-woes/"><u>Microsoft's Helpers: Quick Fixes for Window Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-slick-techniques-to-launch-iis-manager/"><u>8 Slick Techniques to Launch IIS Manager</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-in-2024-from-cluttered-to-clean-learn-how-to-crop-unwanted-parts-of-your-video-with-avidemux/"><u>New In 2024, From Cluttered to Clean Learn How to Crop Unwanted Parts of Your Video with Avidemux</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-windows-11-desk-drawings/"><u>A Step-by-Step Guide to Windows 11 Desk Drawings</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-art-of-glamour-videos/"><u>2024 Approved  The Art of Glamour Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/abort-windows-over-the-top-contrast-mode/"><u>Abort Windows' Over-the-Top Contrast Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719266023156-zero-cost-local-gpt-clones-gpt4alls-window-solution/"><u>Zero-Cost Local GPT Clones: GPT4All's Window Solution.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-windows-printer-speedy-solutions/"><u>Accelerating Windows Printer: Speedy Solutions</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-a-user-friendly-guide-to-board-integration-in-desktopiosandroid-zoom-meetings/"><u>[New] In 2024, A User-Friendly Guide to Board Integration in Desktop/iOS/Android Zoom Meetings</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-beyond-one-viewpoint-the-ultimate-review-of-best-11-bridge-cams/"><u>2024 Approved  Beyond One Viewpoint  The Ultimate Review of Best 11 Bridge Cams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-pc-choose-winning-apps-of-2023/"><u>Accelerate Your PC: Choose Winning Apps of 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-locate-elusive-gpeditmsc-on-pc/"><u>7 Ways to Locate Elusive 'Gpedit.msc' On PC</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-explore-the-world-of-frames-5-free-youtube-tips-for-you/"><u>In 2024, Explore the World of Frames  5 Free YouTube Tips for You</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-samsung-galaxy-m34-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Samsung Galaxy M34 to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-steam-interface-dll-failure-on-pc/"><u>Addressing Steam Interface Dll Failure on PC</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-2024-approved-top-4-hatsune-miku-voice-ai-generators-for-all-times/"><u>Updated 2024 Approved Top 4 Hatsune Miku Voice AI Generators for All Times</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-pc-queries-with-everythingapp/"><u>Accelerate Your PC Queries with EverythingApp</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-pc-interaction-with-comprehensible-win11-navkeys/"><u>Accelerate PC Interaction with Comprehensible Win11 NavKeys</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-elevate-your-channels-templates-at-no-charge/"><u>[New] Elevate Your Channels - Templates at No Charge!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-recovering-cortana-insights-on-pcs/"><u>A Guide to Recovering Cortana Insights on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719364035206-on-premise-self-hosted-gpt-the-windows-path-via-gpt4all/"><u>On-Premise, Self-Hosted GPT: The Windows Path via GPT4All</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-exemplary-directors-dialogue-compilation/"><u>[Updated] Exemplary Directors' Dialogue Compilation</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-call-logs-from-your-vivo-y77t-by-fonelab-android-recover-call-logs/"><u>How to recover old call logs from your Vivo Y77t?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-renovated-widget-display-tool-for-windows-11/"><u>Accessing Renovated Widget Display Tool for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719338830306-windows-lacks-drive-letters-why-and-how-to-rectify-this-issue/"><u>Windows Lacks Drive Letters: Why and How to Rectify This Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-alter-program-dimensions-using-pc-keys/"><u>A Step-by-Step Guide to Alter Program Dimensions Using PC Keys</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-leveraging-full-motion-video-on-iphones/"><u>[New] Leveraging Full Motion Video on iPhones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-fix-a-grayed-out-screen-saver-settings-on-windows/"><u>4 Ways to Fix a Grayed Out Screen Saver Settings on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-bilingual-capabilities-using-windows-shortcuts/"><u>Accelerate Your Bilingual Capabilities Using Windows Shortcuts</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-from-simple-images-to-creative-stickers-complete-tutorial-for-chat-app-enthusiasts/"><u>[Updated] From Simple Images to Creative Stickers  Complete Tutorial for Chat App Enthusiasts</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-does-the-stardust-trade-cost-in-pokemon-go-on-nokia-c22-drfone-by-drfone-virtual-android/"><u>In 2024, How does the stardust trade cost In pokemon go On Nokia C22? | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/fast-track-your-favorites-on-netflix-with-playback-speeds/"><u>Fast-Track Your Favorites on Netflix with Playback Speeds</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-a-complete-manual-for-logging-and-storing-periscope-video/"><u>2024 Approved  A Complete Manual for Logging & Storing Periscope Video</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-resolving-rd-session-errors-win10win11/"><u>A Guide to Resolving RD Session Errors Win10/Win11</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/ipogo-will-be-the-new-ispoofer-on-apple-iphone-11-drfone-by-drfone-virtual-ios/"><u>iPogo will be the new iSpoofer On Apple iPhone 11? | Dr.fone</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/from-jittery-to-jerky-free-video-stabilization-techniques-in-premiere-pro/"><u>From Jittery to Jerky-Free Video Stabilization Techniques in Premiere Pro</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-factory-reset-ipad-or-apple-iphone-15-without-icloud-password-or-apple-id-by-drfone-ios/"><u>How to Factory Reset iPad or Apple iPhone 15 without iCloud Password or Apple ID?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-using-dism-on-win11/"><u>A Step-by-Step Guide to Using Dism on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-to-disabling-chrome-tab-clones/"><u>A Step-by-Step Approach to Disabling Chrome Tab Clones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-straightforward-steps-to-find-windows-ram-details/"><u>5 Straightforward Steps to Find Windows RAM Details</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-interconnecting-your-music-collection-across-services/"><u>2024 Approved  Interconnecting Your Music Collection Across Services</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/time-management-wizards-the-ultimate-guide-to-facebook-timetables-for-2024/"><u>Time Management Wizards  The Ultimate Guide to Facebook Timetables for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-winter-wonderland-adjustments-in-windows-11/"><u>7 Winter Wonderland Adjustments in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719349707624-resurrect-your-xbox-on-a-slow-pc-steps-to-take/"><u>Resurrect Your Xbox on a Slow PC: Steps to Take!</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-reimagine-imagery-best-online-wallpaper-changer-list/"><u>[Updated] Reimagine Imagery  Best Online Wallpaper Changer List</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-failed-shadow-copy-procedures/"><u>Addressing Failed Shadow Copy Procedures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-clear-the-microsoft-defender-protection-history-on-windows-10-and-11/"><u>4 Ways to Clear the Microsoft Defender Protection History on Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-handy-windows-10-and-11-command-shortcuts-you-can-set-up-with-nircmd/"><u>8 Handy Windows 10 & 11 Command Shortcuts You Can Set Up With NirCmd</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-audiovisual-interpretation-engine/"><u>[New] 2024 Approved  Audiovisual Interpretation Engine</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-to-effectively-upload-ultra-hd-content-on-youtube/"><u>[Updated] In 2024, How to Effectively Upload Ultra HD Content on YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-fix-the-checksum-error-in-winrar/"><u>6 Ways to Fix the Checksum Error in WinRAR</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-ways-to-open-the-print-management-tool-in-windows-11/"><u>9 Ways to Open the Print Management Tool in Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-sign-txt-file-document-with-electronic-digital-signature-tutorial-by-ldigisigner-sign-a-word-sign-a-word/"><u>How to Sign .txt file document with Electronic Digital Signature - (Tutorial)</u></a></li>
<li><a href="https://extra-information.techidaily.com/embracing-illusion-what-is-vrs-truth/"><u>Embracing Illusion  What Is VR's Truth?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activate-windows-11-home-hub-guide/"><u>Activate Windows 11 Home Hub: Guide</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-discover-the-leading-screen-recorder-tools-for-mac-creatives/"><u>2024 Approved  Discover the Leading Screen Recorder Tools for Mac Creatives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719266840560-prevent-unwanted-updates-on-your-pc-today/"><u>Prevent Unwanted Updates on Your PC Today!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-github-desktop-in-windows-1011/"><u>A Comprehensive Guide to GitHub Desktop in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-operational-utorrent-installer-on-pcs/"><u>Addressing Non-Operational uTorrent Installer on PCs</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-how-to-share-screen-on-skype-when-working-from-home-for-2024/"><u>[New] How to Share Screen on Skype When Working From Home for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-virtualdub-substitutes-explore-these-video-editing-options/"><u>New 2024 Approved VirtualDub Substitutes Explore These Video Editing Options</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-corrupt-mp4-and-avi-files-of-oneplus-12-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair corrupt MP4 and AVI files of OnePlus 12?</u></a></li>
</ul></div>
