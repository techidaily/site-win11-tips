---
title: How to Disable App Launch Tracking in Windows
date: 2024-09-01T05:22:04.893Z
updated: 2024-09-02T05:22:04.893Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Disable App Launch Tracking in Windows
excerpt: This Article Describes How to Disable App Launch Tracking in Windows
keywords: Disabling Windows Tracking,Stop App Launch History,Eliminate Tracking Features,Halt Launcher Logging,Preventing Usage Data,Turn Off Windows Tracking,Cease Application Traces
thumbnail: https://thmb.techidaily.com/d568502deceace8c4ecf36ae07d16a3133e76d13956dfbeb425d156edf1af5a5.png
---

## How to Disable App Launch Tracking in Windows

 Windows records and monitors how often you use particular applications. While this may enhance productivity, it does also raise privacy concerns.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

## 1\. How to Disable App Launch Tracking Through Windows Settings

 To disable app launch tracking, open the Start menu and type **Settings** in the search bar. Select the **Settings** option in the search results. In the left-side menu, click the **Privacy & security** tab. Then click **General** under the Windows permissions section.

 On the next page, locate **Let Windows improve Start and search results by tracking app launches** and toggle it off.

![Disable App Launch Tracking through Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-windows-settings.jpg)

 After making the changes, Windows will stop tracking and recording your app launches.

 If you ever need to re-enable the feature, repeat the same steps and toggle the switch back on. This will enable Windows to start tracking and recording your app launches.

## 2\. How to Disable App Launch Tracking Using the Group Policy Editor

 You can also disable app launch tracking using the Group Policy Editor. But this method is only available in the Pro and Enterprise versions.

 If you don't have these Windows versions, [turn on the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) and follow these instructions.

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **gpedit.msc** in the text box and click **OK**.
3. In the Group Policy Editor window, navigate to the following path:  
`User Configuration > Administrative Templates > Windows Components > Edge UI​`
4. Go to the right side of the window and double-click on **Turn off tracking of app usage**.  
![Disable App Launch Tracking using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-using-group-policy-editor.jpg)
5. On the next page, check the **Enabled** box.
6. Click **Apply** \> **OK** to save your changes.

 This way, you can disable app launch tracking using the group policy editor.

 To enable the feature again, follow the same steps and navigate to _User Configuration > Administrative Templates > Windows Components > Edge UI_. Then double-click on **Turn off tracking of app usage** and check the **Not Configured** or **Disabled** option.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. How to Disable App Launch Tracking Through the Registry Editor

 Registry Editor is another method to disable app launch tracking. The process is tricky as you need to manually modify the registry keys and one wrong move can cause serious problems. So, we suggest you [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 To disable app launch tracking through Registry Editor, do the following:

1. Right-click on Start and select **Run** from the menu list.
2. Type **regedit** in the text field and click **OK**. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. When the UAC window appears, click **Yes** to grant privileges.
4. In the left pane, navigate to the following path:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. If you don't find the Advanced folder, right-click on **Explorer** and select **New** \> **Key**.
6. Name it **Advanced** and press the Enter key.
7. Now, right-click on the **Advanced** folder and choose **New** \> **DWORD (32-bit) Value**.
8. Name it **Start\_TrackProgs** and hit Enter.  
![Disable App Launch Tracking through the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-the-registry-editor.jpg)
9. Double-click on the **Start\_TrackProgs** DWORD and set its value to **0**.
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->

 Once you're done, close the Registry Editor and restart your computer. Now, Windows won't track or record app launches.

 If you ever want to turn back on app launch tracking, double-click on the **Start\_TrackProgs** DWORD in Registry Editor and set its value to **1**. After that, restart your system for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
## Windows Won’t Track or Monitor the Apps You Use

 If you don't want to mess with the Registry Editor or Group Policy Editor, use the Settings option to disable app launch tracking. Choose the method you prefer and enjoy a tracking-free experience.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-mastering-visual-storytelling-the-cutting-edge-6-instagram-reel-tools/"><u>[New] 2024 Approved  Mastering Visual Storytelling  The Cutting-Edge 6 Instagram Reel Tools</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-pro-chromebook-record-unmatched-screen-capture/"><u>[New] 2024 Approved  Pro Chromebook Record  Unmatched Screen Capture</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-gently-unveiled-scene/"><u>[New] Gently Unveiled Scene</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/nfluencer-tip-crafting-irresistible-templated-content-in-youtube-descriptions-for-2024/"><u>[New] Influencer Tip  Crafting Irresistible Templated Content in YouTube Descriptions for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-perfectly-sized-videos-for-maximum-engagement-on-instagram-for-2024/"><u>[New] Perfectly Sized Videos for Maximum Engagement on Instagram for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-prime-10-image-repositories-without-costs/"><u>[New] Prime 10 Image Repositories Without Costs</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-the-real-number-of-youtube-views-you-need-to-make-a-living/"><u>[New] The Real Number of YouTube Views You Need to Make a Living</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-ranking-the-greatest-9-mobile-video-communication-services-ios-android/"><u>[Updated] Ranking the Greatest 9 Mobile Video Communication Services (iOS, Android)</u></a></li>
<li><a href="https://extra-information.techidaily.com/basic-principles-of-story-artistry-for-2024/"><u>Basic Principles of Story Artistry for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-up-unmet-windows-11-requirements-alert/"><u>Clear Up Unmet Windows 11 Requirements Alert</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/creating-an-ai-ecosystem-linking-chatgpt-to-whatsapp-helpdesk/"><u>Creating an AI Ecosystem: Linking ChatGPT to WhatsApp Helpdesk</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-main-panel-of-windows-11-task-manager/"><u>Customizing Main Panel of Windows 11 Task Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-4-paths-to-protect-windows-post-bitlocker/"><u>Discover 4 Paths to Protect Windows Post-BitLocker</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ease-of-access-disabling-security-interrogation-for-windows-11-admin/"><u>Ease of Access: Disabling Security Interrogation for Windows 11 Admin</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-task-managers-live-feed-rates-for-windows-11/"><u>Elevate Task Manager's Live Feed Rates for Windows 11</u></a></li>
<li><a href="https://facebook.techidaily.com/exploring-the-reasoning-behind-feeding-on-facebook/"><u>Exploring the Reasoning Behind 'Feeding' On Facebook</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/exploring-virtual-reality-lgs-360-degree-experience-for-2024/"><u>Exploring Virtual Reality  LG's 360-Degree Experience for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/from-two-dimensions-to-three-making-text-pop-in-photoshop/"><u>From Two-Dimensions to Three  Making Text Pop in Photoshop</u></a></li>
<li><a href="https://article-helps.techidaily.com/full-dissection-gopro-silver-hero4-model-insight-for-2024/"><u>Full Dissection  GoPro Silver Hero4 Model Insight for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/get-the-most-out-of-wow-by-correcting-incompatible-device-drivers-easily/"><u>Get the Most Out of WoW by Correcting Incompatible Device Drivers Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-quash-disconnecting-drama-in-discord-on-windows-11-pcs/"><u>How to Quash Disconnecting Drama in Discord on Windows 11 PCs</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-feasible-ways-to-fake-location-on-facebook-for-your-motorola-moto-g-stylus-5g-2023-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Feasible Ways to Fake Location on Facebook For your Motorola Moto G Stylus 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-mastering-instagram-reels-tips-and-techniques/"><u>In 2024, Mastering Instagram Reels  Tips & Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jumpstart-creativity-opening-ms-paint-on-win11/"><u>Jumpstart Creativity: Opening MS Paint on Win11</u></a></li>
<li><a href="https://blog-min.techidaily.com/macx-pro-the-ultimate-free-dvd-downloader-and-video-transcoder-for-mac-users-convert-your-dvds-into-youtube-ready-files/"><u>MacX Pro: The Ultimate Free DVD Downloader & Video Transcoder for Mac Users – Convert Your DVDs Into YouTube-Ready Files!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterclass-creating-multiple-subfolders-with-ease-in-windows/"><u>Masterclass: Creating Multiple Subfolders with Ease in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-printer-network-setup-a-windows-guide/"><u>Mastering Printer Network Setup: A Windows Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-password-required-avoidance-on-windows-11/"><u>Mastering the Art of 'Password Required' Avoidance on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-window-11s-help-service-disruption/"><u>Mending Window 11'S Help Service Disruption</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-error-windows-cant-stop-volume-device/"><u>Overcoming Error: Windows Can’t Stop Volume Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-printmanagement-not-found-issue-quickly/"><u>Overcoming Windows Printmanagement Not Found Issue Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-vanished-recorded-run-events/"><u>Preventing Vanished Recorded Run Events</u></a></li>
<li><a href="https://win11-tips.techidaily.com/protecting-game-progress-with-epic-saves/"><u>Protecting Game Progress with Epic Saves</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-reactivate-your-preferred-microsoft-store-apps/"><u>Quick Fix: Reactivate Your Preferred Microsoft Store Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefining-reset-count-for-lockouts-after-logon-errors-in-windows-11-pro/"><u>Redefining Reset Count for Lockouts After Logon Errors in Windows 11 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-folder-interruption-noise-in-win11/"><u>Reducing Folder Interruption Noise in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refreshing-windows-paperwork-handler/"><u>Refreshing Windows Paperwork Handler</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secrets-to-affordable-access-buying-windows-11-codes/"><u>Secrets to Affordable Access: Buying Windows 11 Codes</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/solutions-for-a-malfunctioning-xbox-series-x-or-s-headset-expert-tips-included/"><u>Solutions for a Malfunctioning Xbox Series X or S Headset - Expert Tips Included</u></a></li>
<li><a href="https://fox-that.techidaily.com/solve-your-siri-dilemma-7-essential-solutions-for-ios-devices/"><u>Solve Your Siri Dilemma: 7 Essential Solutions for iOS Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-driver-not-supported-errors-in-windows-11/"><u>Solving Driver Not Supported Errors in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-prevalent-anydesk-glitches-in-windows-os/"><u>Solving Prevalent AnyDesk Glitches in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-handling-missing-powershell-on-windows/"><u>Strategies for Handling 'Missing PowerShell' On Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-correct-token-misreference-errors-on-win10win11/"><u>Strategies to Correct Token Misreference Errors on Win10/Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-powershell-workflow-with-script-policy-controls/"><u>Streamline Your PowerShell Workflow with Script Policy Controls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-remedies-for-stalling-spotify-connectivity/"><u>Swift Remedies for Stalling Spotify Connectivity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-subtitle-issues-in-prime-video-for-smooth-windows-11-watching/"><u>Tackling Subtitle Issues in Prime Video for Smooth Windows 11 Watching</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/tinytake-screen-recorder-review-and-alternative/"><u>TinyTake Screen Recorder Review and Alternative</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-disabling-acceleration-with-your-mouse-in-windows/"><u>Tips for Disabling Acceleration with Your Mouse in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-to-enhanced-widget-display-interface-in-windows-11/"><u>Transitioning to Enhanced Widget Display Interface in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/triple-threat-tweaks-for-personalized-win11-preferences/"><u>Triple-Threat Tweaks for Personalized Win11 Preferences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-post-monitor-connection-windows-lag-fixes/"><u>Troubleshooting Post-Monitor Connection: Windows Lag Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turning-your-spoken-language-into-written-communication-using-whisper-on-windows/"><u>Turning Your Spoken Language Into Written Communication Using Whisper on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncover-the-hidden-issues-causing-login-blackouts/"><u>Uncover the Hidden Issues Causing Login Blackouts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfreezing-steam-directory-access-fixes-for-windows-11/"><u>Unfreezing Steam Directory Access: Fixes for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-office-solving-windows-activation-issues/"><u>Unlocking Office: Solving Windows Activation Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-taskbars-hidden-features/"><u>Unveiling Windows Taskbar's Hidden Features</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-screen-record-with-ease-top-10-webcam-software-for-windows-10-for-2024/"><u>Updated Screen Record with Ease Top 10 Webcam Software for Windows 10 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/xbox-not-launching-regain-control-with-these-tricks/"><u>Xbox Not Launching? Regain Control with These Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/your-pathway-to-elevated-settings-windows-11s-higher-power/"><u>Your Pathway to Elevated Settings: Windows 11'S Higher Power</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>