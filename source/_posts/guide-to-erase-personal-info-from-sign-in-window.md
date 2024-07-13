---
title: Guide to Erase Personal Info From Sign-In Window
date: 2024-07-12T17:07:41.709Z
updated: 2024-07-13T17:07:41.709Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Erase Personal Info From Sign-In Window
excerpt: This Article Describes Guide to Erase Personal Info From Sign-In Window
keywords: Delete Login Data,Privacy Sign-Out Guide,Remove User Info,Clear Browser History,Wipe Session Cookies,Erase Account Info,Hide Personal Details
thumbnail: https://thmb.techidaily.com/18d1ae3b93316df7253b6d9ca3430e2e7b9da85a6ae22dbb42da5be064fc57fa.png
---

## Guide to Erase Personal Info From Sign-In Window

 If you frequently use your computer in public places, it's a good idea to remove your email address from the Windows login screen. This means people can't get your email address if they see your screen over your shoulder.

 You can accomplish this using the Settings app, Group Policy Editor, or Registry Editor. In this post, we've covered all these methods in detail.

## 1\. How to Hide Email Address From Windows Login Screen Using the Settings App

 The Windows Settings app provides a quick way to hide account information from the login screen. So, if you are in a rush, use the following steps to remove user email addresses from the Windows login screen.

1. Press**Win + I** or use one of the [many ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Accounts > Sign-in options** .
3. Under**Additional settings** , toggle off the switch next to **Show account details such as my email address on the sign-in screen** .  
![Hide Email From Windows Login Screen Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-settings-app.jpg)

## 2\. How to Hide Email Address From Windows Login Screen Using the Group Policy Editor

 The Group Policy Editor (or gpedit.msc) is a handy Windows tool for configuring advanced system settings. You can also this tool to hide your email address from the Windows login screen.

 Note that the Group Policy Editor is only available on Windows Professional, Education, and Enterprise editions. If your PC is running Windows Home, check out [how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

1. Press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the search box and select the first result that appears.
3. Use the left pane to navigate to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options** .
4. Double-click the **Interactive Logon: Display user information when the session is locked** policy on your right.
5. In the properties window, click the drop-down menu to select the**Do not display user information** option.
6. Click**Apply** followed by**OK** .  
![Hide Email From Windows Login Screen Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-group-policy-editor.jpg)
7. Next, double-click on the**Interactive logon: Do not display last user name** policy from the same section.
8. Select**Enabled** in the properties window.
9. Click**Apply** followed by**OK** to save changes.

## 3\. How to Hide Email Address From Windows Login Screen Using the Registry Editor

 If the above two methods don’t work for some reason, you can make changes to the Windows registry files to hide your email address from the login screen. For that, you’ll need to use the Registry Editor on Windows.

 When it comes to editing Registry files, it's important to be cautious as making incorrect changes can cause irreversible damage to your PC. We recommend you either back up all the registry files or create a restore point before you make any changes. If you need help with that, check our guides on [how to back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [how to create a restore point in Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

 Once you’re done with that, use the following steps to hide your email address from the Windows login screen via Registry Editor.

1. Press**Win + X** to open the Power User menu and select**Run** from the list.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows > System** .
5. Right-click on the**System** key and select**New > DWORD (32-bit) Value** .
6. Rename the DWORD to**BlockUserFromShowingAccountDetailsOnSignin** .
7. Double-click on the newly created DWORD and enter**1** in the**Value data** field. Then, click**OK** .  
![Hide Email From Windows Login Screen Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-registry-editor.jpg)

 Exit the Registry Editor and restart your PC for the changes to take effect.

## Hiding Your Email Address From the Windows Login Screen Is Easy

 As we just saw, hiding your personal information from the Windows login screen barely takes a couple of minutes, regardless of the method you employ.


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
<li><a href="https://some-approaches.techidaily.com/updated-the-present-state-of-drones-and-their-future-expansion/"><u>[Updated] The Present State of Drones and Their Future Expansion</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-in-2024-pioneering-digital-recording-solutions-ranking-the-7-best-audio-editors-beyond-audacity-on-android/"><u>Updated In 2024, Pioneering Digital Recording Solutions Ranking the 7 Best Audio Editors Beyond Audacity on Android</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-master-the-science-and-art-of-attention-grabbing-titles/"><u>In 2024, Master the Science and Art of Attention-Grabbing Titles</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-mastering-game-streams-with-ai-enhanced-portraits/"><u>[New] 2024 Approved  Mastering Game Streams with AI-Enhanced Portraits</u></a></li>
<li><a href="https://youtube-web.techidaily.com/mplify-earnings-monetize-youtube-on-the-go-with-effective-techniques-for-2024/"><u>[New] Amplify Earnings  Monetize YouTube on the Go with Effective Techniques for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-touch-screen-on-infinix-smart-7-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Touch Screen on Infinix Smart 7 | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-process-system-isnt-responding-error-on-samsung-galaxy-a34-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Process System Isnt Responding Error on Samsung Galaxy A34 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sidestep-common-snip-and-sketch-screenshot-hurdles-4-fixes/"><u>Sidestep Common Snip & Sketch Screenshot Hurdles: 4 Fixes</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-12-get-deleted-photos-back-with-ease-and-safety-by-fonelab-android-recover-photos/"><u>How to 12 Get Deleted photos Back with Ease and Safety?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-print-again-in-win11/"><u>Step-By-Step Guide to Print Again in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-bypass-oculus-setup-failures-in-windows-1110/"><u>Quick Guide to Bypass Oculus Setup Failures in Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-missing-d3dx939dll-in-win11/"><u>Steps to Fix Missing D3DX9_39.dll in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-administrative-tasks-a-new-approach-to-windows-uac/"><u>Streamlining Administrative Tasks: A New Approach to Windows UAC</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-navigating-instagrams-posting-video-count/"><u>[New] Navigating Instagram's Posting Video Count</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-pros-of-choosing-best-pc-video-grabbers-for-win11/"><u>[New] In 2024, Pros of Choosing Best PC Video Grabbers for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719216451577-achieving-total-screen-capture-mastery-using-snip-and-sketch/"><u>Achieving Total Screen Capture Mastery Using Snip & Sketch</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-aiff-converter-buying-guide-make-the-right-decision-for-2024/"><u>Updated AIFF Converter Buying Guide Make the Right Decision for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-navigating-new-horizons-the-essence-of-vr-travel/"><u>[New] Navigating New Horizons  The Essence of VR Travel</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-mastering-video-capture-on-your-laptop-with-screenrec/"><u>[Updated] Mastering Video Capture on Your Laptop with ScreenRec</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ten-clear-indicators-of-pc-needs-a-factory-start/"><u>Ten Clear Indicators of PC Needs a Factory Start</u></a></li>
<li><a href="https://extra-tips.techidaily.com/conquer-the-cutting-edge-with-advanced-pixlr-tricks/"><u>Conquer the Cutting-Edge with Advanced Pixlr Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-power-to-edit-and-markup-in-windows-based-pdfs/"><u>Regain Power to Edit and Markup in Windows-Based PDFs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-failure-windows-update-issue-code-0x80242016/"><u>Avoid Failure: Windows Update Issue Code 0X80242016</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-synchronized-note-taking-in-windows-11/"><u>The Art of Synchronized Note-Taking in Windows 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-innovative-techniques-for-superior-canva-visuals/"><u>[Updated] Innovative Techniques for Superior Canva Visuals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-dxgi-failure-in-windows-fix-for-removed-devices/"><u>Tackling DXGI Failure in Windows: Fix for Removed Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-instructional-paper-on-windows-11s-speed-boost-feature/"><u>The Ultimate Instructional Paper on Windows 11'S Speed Boost Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-chrome-clock-error-ahead-or-behind-windows-edition/"><u>Adjusting Chrome Clock Error: Ahead or Behind? (Windows Edition)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-to-batch-installing-apps-using-winstall-in-windows-11/"><u>A Step-by-Step Approach to Batch Installing Apps Using Winstall in Windows 11</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-cutting-edge-filmmaking-kinemasters-seamless-segments/"><u>2024 Approved  Cutting-Edge Filmmaking  Kinemaster's Seamless Segments</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-elite-10-sound-recording-essentials-on-spotify-platform/"><u>[Updated] 2024 Approved  Elite 10 Sound Recording Essentials on Spotify Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silent-data-exchange-safeguarding-files-across-ws11w10/"><u>Silent Data Exchange: Safeguarding Files Across WS11/W10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-full-potential-of-policy-editor-in-windows-11/"><u>Unlock the Full Potential of Policy Editor in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-for-overcoming-license-expiration-notice-in-win11/"><u>Tactics for Overcoming License Expiration Notice in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-system-details-locate-windows-ip-and-mac-via-powershell/"><u>Unveiling System Details: Locate Windows' IP and MAC via Powershell</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-smart-approaches-boosting-communication-on-discord-through-the-use-of-voxels-audio-transformation-feature/"><u>2024 Approved Smart Approaches Boosting Communication on Discord Through the Use of Voxels Audio Transformation Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/syncing-up-with-microsoft-sql-on-malwarebytes-after-disconnect/"><u>Syncing Up with Microsoft SQL on Malwarebytes After Disconnect</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-explore-conceal-and-reveal-folders/"><u>Streamlining Windows Explore: Conceal and Reveal Folders</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-beyond-one-angle-explore-our-11-multicam-review-for-2024/"><u>[Updated] Beyond One Angle  Explore Our #11 Multicam Review for 2024</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/concurrent-communication-skills/"><u>Concurrent Communication Skills</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/implementing-youtubes-custom-markup-guide/"><u>Implementing YouTube's Custom Markup Guide</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/20-wonderful-stop-motion-ideas-for-beginners-and-kids-filmora/"><u>20 Wonderful Stop Motion Ideas for Beginners and Kids - Filmora</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-languages-change-navigating-hotkeys-in-windows-11-and-11-pro/"><u>Quick Languages Change: Navigating Hotkeys in Windows 11 & 11 Pro</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-error-495-while-downloadupdating-android-apps-on-honor-70-lite-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Error 495 While Download/Updating Android Apps On Honor 70 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-update-processes-context-menu-update-option-for-win11-users/"><u>Streamlining Update Processes: Context Menu Update Option for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-system-freeze-operation-failed-code-0x0000011b/"><u>Resolving System Freeze: Operation Failed Code 0X0000011B</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-unlocking-the-potential-of-your-tiktok-camera/"><u>2024 Approved  Unlocking the Potential of Your TikTok Camera</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-excellent-replacements-to-top-rated-fbx-recorder-apps/"><u>[New] In 2024, Excellent Replacements to Top-Rated FBX Recorder Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-cant-you-see-a-drive-letter-on-your-windows-machine/"><u>Why Can't You See a Drive Letter on Your Windows Machine?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-overcoming-windows-notepad-hangups/"><u>Tips for Overcoming Windows Notepad Hangups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rebooting-to-standard-power-plans-guide-for-win-11/"><u>Rebooting to Standard Power Plans: Guide for Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-keep-windows-sound-preferences-intact/"><u>Strategies to Keep Windows Sound Preferences Intact</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-smartphone-potential-as-windows-microphone/"><u>Unlocking Smartphone Potential as Windows Microphone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-silent-audio-devices-pc-edition/"><u>Revive Silent Audio Devices – PC Edition</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/master-earning-plan-top-5-highest-paying-ig-posts/"><u>Master Earning Plan  Top 5 Highest Paying IG Posts</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-step-by-step-eliminating-rhythm-units-from-your-songs-digitally/"><u>New Step-by-Step Eliminating Rhythm Units From Your Songs Digitally</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-power-of-voice-activated-accessibility-features/"><u>Unlocking the Power of Voice-Activated Accessibility Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-fn-key-tasks-in-windows-1011-oses/"><u>Tailoring FN Key Tasks in Windows 10/11 OSes</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-the-art-of-auditory-purity-advanced-strategies-to-dismiss-background-noises-using-offline-and-online-technologies/"><u>Updated The Art of Auditory Purity Advanced Strategies to Dismiss Background Noises Using Offline and Online Technologies</u></a></li>
<li><a href="https://vp-tips.techidaily.com/how-to-make-gmail-meetings-work-zipping-up-zoom-integrations-for-2024/"><u>How to Make Gmail Meetings Work  Zipping Up Zoom Integrations for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-2024-approved-best-15-programs-to-edit-gopro-footage/"><u>[New] 2024 Approved  Best 15 Programs to Edit GoPro Footage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-warning-indicators-that-call-for-a-full-reboot/"><u>5 Warning Indicators That Call For a Full Reboot</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/approved-harnessing-the-power-of-filmora-for-youtube-video-promotions/"><u>2024 Approved  Harnessing the Power of Filmora for YouTube Video Promotions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-your-window-11-interface-for-maximum-efficiency-and-satisfaction/"><u>Tailor Your Window 11 Interface for Maximum Efficiency and Satisfaction</u></a></li>
</ul></div>
