---
title: Five Simple Fixes for Your Non-Operational Windows Notepad
date: 2024-07-12T16:33:23.375Z
updated: 2024-07-13T16:33:23.375Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Five Simple Fixes for Your Non-Operational Windows Notepad
excerpt: This Article Describes Five Simple Fixes for Your Non-Operational Windows Notepad
keywords: Windows Notepad Troubleshoot,Notepad Repair Steps,Fixing Non-Functional Notepad,Notepad Error Resolution,Restart Notepad Tips,Stop Notepad Crash,Quick Notepad FIX Guide
thumbnail: https://thmb.techidaily.com/6d6520e192a843298c5f3fb60d79f701e9d849b7c957109090842f5892749c79.jpg
---

## Five Simple Fixes for Your Non-Operational Windows Notepad

 Notepad is a simple text editor app that comes pre-installed on your Windows computer. You can use it to view, create, and edit text files whenever needed. But what if Windows fails to open Notepad and you can’t use it?

 Several factors, ranging from a temporary app glitch to corrupt user account files, can prevent Notepad from opening on Windows. Fortunately, there are some quick fixes you can use to regain access to the Notepad app on Windows.

## 1\. Use Alternative Methods to Open Notepad

 Before you try any advanced solutions, see if you can open Notepad using the Run tool. Press**Win + R** to open the Run dialog box. Type**notepad** in the Open field and press**Enter** .

 If that doesn’t work, try opening Notepad through a command-line tool. Open the search menu to launch**Command Prompt** or**PowerShell** . In the console, type**notepad** and then press**Enter** .

![Open Notepad via Command-Line Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-notepad-via-command-line-tool.jpg)

 You could also ask Cortana to open Notepad. However, if none of these methods work, proceed to the next solution.

## 2\. Set Notepad as the Default Text Editor

 If Notepad is not set as the default text editor app on Windows, your text files may open in a different app. If you don't want that, use these steps to set Notepad as the default text editor app.

1. Open the**Start menu** and click the**gear icon** to launch the Settings app.
2. Navigate to the**Apps** tab.
3. Select**Default apps** from the right pane.
4. Scroll all the way down to the**Related settings** section.
5. Click**Choose defaults by file type** .
6. Type**.txt** in the search box and click the current default app.
7. Select**Notepad** and click the**Set default** button.  
![Set Notepad as Default Text Editor App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/set-notepad-as-default-text-editor-app-on-windows.jpg)

Try opening a few text files and see if they open in Notepad.

## 3\. Repair or Reset the Notepad App

 The built-in repair tool on Windows is quite efficient when it comes to fixing minor app-related issues. Microsoft recommends using this tool when an app fails to open or does not work as expected on your Windows computer.

To repair the Notepad app on Windows:

1. Right-click the Start icon or press**Win + X** to open the Power User menu.
2. Select**Installed apps** from the list.
3. Scroll down or use the search tool to locate**Notepad** on the app list.
4. Click the**three-dot menu icon** next to Notepad and select**Advanced options** .
5. Scroll down to the Reset section and click the**Repair** button.  
![Repair or Reset the Notepad App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/repair-or-reset-the-notepad-app.jpg)

 You should see a checkmark next to the Repair button once the process is complete. Then, try to [open the Notepad app](https://www.makeuseof.com/windows-11-open-notepad/) again.

 If repairing the Notepad app does not make any difference, you can try resetting it. Here are the steps for the same.

1. Press**Win + S** to open the search menu.
2. Type**Notepad** in the search box and select**App settings** .
3. Under the Reset section, click the**Reset** button.

 Windows will reset the Notepad app to its default version, which should resolve any issues with it.

## 4\. Reinstall the Notepad App

 You can also try uninstalling and reinstalling the Notepad app on your computer. To do so, you’ll need to access the [optional features on Windows](https://www.makeuseof.com/tag/windows-10-optional-features-guide/) . Here’s how you can go about it.

1. Press**Win + I** to launch the Settings app.
2. Navigate to**Apps > Optional features** .
3. Click on**Notepad** to expand it.
4. Click the**Uninstall** button.  
![Uninstall Notepad App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/uninstall-notepad-app-on-windows.jpg)
5. Wait for Windows to uninstall Notepad from your computer.
6. Next, click the**View features** button at the top.
7. Type**Notepad** in the search box.
8. Tick the**Notepad (system)** checkbox and click**Next** .
9. Click**Install** .  
![Install Notepad App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/install-notepad-app-on-windows.jpg)

 Wait for Windows to install Notepad on your computer and then try to open it using the search menu.

## 5\. Run the SFC and DISM Scans

 Corrupted system files could also interfere with system processes and prevent Notepad from opening. The System File Checker (SFC) is a built-in utility that can help you repair system files on Windows. It basically scans your system for damaged system files and replaces them with their cached versions.

To run the SFC scan on Windows:

1. Click the magnifying icon on the taskbar to open the search menu.
2. Type**command prompt** in the box and select**Run as administrator** .
3. When the User Account Control (UAC) prompt appears, select**Yes** to continue.
4. In the console, input the following command and press**Enter** :  
`sfc /scannow`

 Wait for the scan to complete and then enter the following command to run the DISM (or Deployment Image Servicing and Management) scan. It will try to detect and repair any issues with the system image.

`DISM.exe /Online /Cleanup-image /Restorehealth`

![DISM Scan in Windows Terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/dism-scan-in-windows-terminal.jpg)

 After the scan is complete, restart your PC and see if you can access Notepad.

## 6\. Perform a Clean Boot

 At times, third-party apps and background services can conflict with Windows processes and cause problems like the one discussed here. One way to verify this possibility is to boot your computer in a clean boot state, where it only runs with essential apps and services.

 If you perform a clean boot and Notepad opens normally, it means that the culprit causing the issue got disabled. If you'd like to learn more about the topic, check out our guide on [how to perform a clean boot on Windows](https://www.makeuseof.com/how-perform-clean-boot-windows-10/) and follow the steps listed there.

## 7\. Create Another User Account

 If some of the files in your user account have become corrupt, you may have difficulty performing simple tasks like opening an app. If that seems to be the case, your best option is to create and switch to a new user account.

To create a new user account on Windows:

1. Use one of the [many ways to open the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Accounts > Other users** .
3. Click the**Add account** button.
4. In the Microsoft account window, click **I don't have this person's sign-in information** .  
![Microsoft Account Sign-In Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/microsoft-account-sign-in-window.jpg)

 Follow the on-screen prompts to create a new user account. Make sure you give the new account administrative privileges so that you can [move your personal files and data to the new account](https://www.makeuseof.com/windows-10-copy-files-between-user-accounts/) with ease.

 Once you sign in with your newly created account, Notepad should open without problems.

## Start Using Notepad Again

 Hopefully, the solutions provided above have helped, and you’re able to use Notepad again. However, if none of the above solutions work, you can perform a system restore to undo any recent changes that may have caused the problem.


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
<li><a href="https://facebook-video-content.techidaily.com/new-instant-hd-fb-content-downloader-for-2024/"><u>[New] Instant HD FB Content Downloader for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-record-and-share-every-victory-in-obs/"><u>2024 Approved  Record & Share Every Victory in OBS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-systemsettings-issues-on-win11/"><u>Strategies to Overcome SystemSettings Issues on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-control-file-explorer-display-options-windows-11/"><u>How to Control File Explorer Display Options (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-command-prompt-not-running-as-administrator-on-windows/"><u>How to Fix Command Prompt Not Running as Administrator on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-footage-excellence-with-these-best-apps-for-windows-11/"><u>Enhance Footage Excellence with These Best Apps for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-quick-ways-to-check-your-graphics-card-model-on-windows-11/"><u>3 Quick Ways to Check Your Graphics Card Model on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/designing-personalized-secure-locks-for-windows-11/"><u>Designing Personalized Secure Locks for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-user-interface-add-psoft-tools-to-windows-11/"><u>Boosting User Interface: Add PSoft Tools to Windows 11</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-screenrec-demystified-a-comprehensible-guide-for-laptops/"><u>[Updated] 2024 Approved  ScreenRec Demystified  A Comprehensible Guide for Laptops</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-comprehensive-tutorial-adding-timer-functionality-to-obs-for-2024/"><u>[Updated] Comprehensive Tutorial  Adding Timer Functionality to OBS for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-innovative-approach-wearable-unlocks-your-mac/"><u>In 2024, Innovative Approach  Wearable Unlocks Your Mac</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-be-a-part-of-the-buzz-top-10-tiktok-tests/"><u>[New] 2024 Approved  Be a Part of the Buzz  Top 10 TikTok Tests</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-husqvarnas-sky-high-adventure-with-h501s-x4-review/"><u>2024 Approved  Husqvarna's Sky-High Adventure with H501S X4 Review</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-fluent-in-content-sharing-tiktok-twitter-transition/"><u>[New] Fluent in Content Sharing  TikTok-Twitter Transition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-adjust-windows-activity-lock/"><u>How to Adjust Windows Activity Lock</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/get-more-out-of-your-browsing-select-these-5-chrome-extensions-for-fb-vids-for-2024/"><u>Get More Out of Your Browsing  Select These 5 Chrome Extensions for FB Vids for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-restoring-full-volume-in-partially-muted-fb-content/"><u>In 2024, Restoring Full Volume in Partially Muted FB Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-manage-disks-keyways-into-windows-11s-storage-manager/"><u>Swiftly Manage Disks: Keyways Into Windows 11'S Storage Manager</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-easy-screenshot-methods-for-mac-users/"><u>[Updated] 2024 Approved  Easy Screenshot Methods for Mac Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-fatal-error-c0000022-in-windows/"><u>How to Fix the Fatal Error C0000022 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unzipping-challenge-managing-multiple-compressed-files-in-a-snap/"><u>Unzipping Challenge: Managing Multiple Compressed Files in a Snap</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-commencing-your-google-meet-experience-for-2024/"><u>[New] Commencing Your Google Meet Experience for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/everything-you-need-to-know-about-lock-screen-settings-on-your-vivo-y100i-by-drfone-android/"><u>Everything You Need to Know about Lock Screen Settings on your Vivo Y100i</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-videovantage-warriors/"><u>[Updated] In 2024, VideoVantage Warriors</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-effortless-screen-capture-on-chrome-os-devices-for-2024/"><u>[New] Effortless Screen Capture on Chrome OS Devices for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-windows-photos-apps-generative-erase-is-actually-great/"><u>The Windows Photos App's Generative Erase Is Actually Great</u></a></li>
<li><a href="https://win11-tips.techidaily.com/traverse-backward-commanding-windows-11-history/"><u>Traverse Backward: Commanding Windows 11 History</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-comedy-cache-hot-names-and-trends-in-the-laughter-world-for-2024/"><u>[Updated] Comedy Cache  Hot Names & Trends in the Laughter World for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-efficiency-guide/"><u>Mastering Windows 11: Efficiency Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/workarounds-to-manipulate-windows-11-sleepwake/"><u>Workarounds to Manipulate Windows 11 Sleep/Wake</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-local-user-policies-a-guide-to-windows-11-and-11-systems/"><u>Adjusting Local User Policies: A Guide to Windows 11 & 11 Systems</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-best-choice-avi-player-with-multiplatform-support/"><u>2024 Approved  Best Choice Avi Player with Multiplatform Support</u></a></li>
<li><a href="https://facebook.techidaily.com/banish-facebooks-watch-history-for-a-clean-start/"><u>Banish Facebook's Watch History for a Clean Start</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-audio-subtitle-symphony-streamlining-prime-viewing-in-windows-11/"><u>Decoding Audio-Subtitle Symphony: Streamlining Prime Viewing in Windows 11</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-hidefake-snapchat-location-on-your-oppo-a18-drfone-by-drfone-virtual-android/"><u>How to Hide/Fake Snapchat Location on Your Oppo A18 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719295110946-get-a-free-self-hosted-gptclone-with-gpt4all/"><u>Get a Free, Self-Hosted GPTClone with GPT4All</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-the-little-billionaire-a-10-year-olds-wealthy-youtube-journey-for-2024/"><u>[Updated] The Little Billionaire  A 10-Year-Old's Wealthy YouTube Journey for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-steam-cloud-connection-problems/"><u>Correcting Steam Cloud Connection Problems</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-the-definitive-guide-to-perfecting-vimeo-recordings/"><u>In 2024, The Definitive Guide to Perfecting Vimeo Recordings</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-unlock-photo-editing-potential-with-these-clever-pixlr-techniques/"><u>[New] Unlock Photo Editing Potential with These Clever Pixlr Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-correct-xbox-mic-issues-in-os/"><u>Guidelines to Correct Xbox Mic Issues in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-rectifying-device-is-unreachable-error-in-windows/"><u>Mastering the Art of Rectifying Device Is Unreachable Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/system-mastery-a-path-through-preferences/"><u>System Mastery: A Path Through Preferences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-what-sets-ai-hardware-on-a-distinct-path/"><u>Analyzing What Sets AI Hardware on a Distinct Path</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-maximizing-vimeo-presence-with-movies-from-wmm/"><u>[New] In 2024, Maximizing Vimeo Presence with Movies From WMM</u></a></li>
<li><a href="https://fake-location.techidaily.com/the-best-8-vpn-hardware-devices-reviewed-on-apple-iphone-12-mini-drfone-by-drfone-virtual-ios/"><u>The Best 8 VPN Hardware Devices Reviewed On Apple iPhone 12 mini | Dr.fone</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-virtual-verification-app-standards-by-vll/"><u>[New] 2024 Approved  Virtual Verification  App Standards by VLL</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-apk-journey-to-gaming-bliss-funimate-pro-guide/"><u>In 2024, APK Journey to Gaming Bliss  Funimate Pro Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-handle-internal-windows-error-during-remote-desktop-use/"><u>How to Handle Internal Windows Error During Remote Desktop Use</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-oppo-reno-9awithwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Oppo Reno 9Awith/without a PC</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-access-the-archived-unique-methods-for-viewing-old-youtube/"><u>[New] 2024 Approved  Access the Archived  Unique Methods for Viewing Old YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-counteract-internal-error-with-remote-desktop/"><u>Strategies to Counteract Internal Error with Remote Desktop</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-ubuntus-finest-top-10-free-video-editing-software/"><u>Updated 2024 Approved Ubuntus Finest Top 10 Free Video Editing Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-technical-odyssey-embracing-hdr-in-windows-11-environments/"><u>A Technical Odyssey: Embracing HDR in Windows 11 Environments</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ive-channel-titling-techniques-for-growth/"><u>Creative Channel Titling Techniques for Growth</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-prevent-apex-legends-crashes-w11/"><u>Strategies to Prevent Apex Legends Crashes W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-winerror-0xc0000005/"><u>Mastering the Art of Fixing WinError 0Xc0000005</u></a></li>
<li><a href="https://win11-tips.techidaily.com/click-without-the-rush-learn-to-deactivate-mouse-acceleration-windows-style/"><u>Click Without the Rush: Learn to Deactivate Mouse Acceleration Windows Style</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-can-i-catch-the-regional-pokemon-without-traveling-on-lenovo-thinkphone-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Catch the Regional Pokémon without Traveling On Lenovo ThinkPhone | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-top-voip-platforms-face-off-discord-vs-skype-showdown/"><u>[New] 2024 Approved  Top VoIP Platforms Face-Off  Discord Vs Skype Showdown</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uniting-your-inboxes-connecting-gmail-with-windows-outlook-app/"><u>Uniting Your Inboxes: Connecting Gmail with Windows' Outlook App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackle-windows-camera-problems-with-expert-tips/"><u>Tackle Windows Camera Problems with Expert Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-laptop-onoff-trick-for-energy-conservation/"><u>Boost Your Laptop: On/Off Trick for Energy Conservation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-cross-device-note-utilization-guide/"><u>Windows 11 Cross-Device Note Utilization Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-error-code-0xc0000001-on-windows-11-or-11/"><u>How to Fix Error Code 0Xc0000001 on Windows 11 or 11</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-2024-approved-enhance-filmmaking-on-iphone-top-camera-extensions-listed/"><u>[New] 2024 Approved  Enhance Filmmaking on iPhone  Top Camera Extensions Listed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-xbox-game-pass-0x00000001-error-in-windows-10-and-11/"><u>How to Fix the Xbox Game Pass 0X00000001 Error in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-multiple-users-ms-logins-on-pc/"><u>Tackling Multiple Users' MS Logins on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-swiftly-and-permanently-discard-a-partition-on-windows-pc/"><u>How to Swiftly and Permanently Discard a Partition on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-the-barrier-win-solution-for-epic-games-access/"><u>Bypassing the Barrier: Win Solution for Epic Games Access</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-streaming-made-simple-free-downloader-to-mp3s-now/"><u>[New] Streaming Made Simple  Free Downloader to MP3s Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blend-in-with-the-background-hide-taskbars-language-bar-win11/"><u>Blend in with the Background: Hide Taskbar's Language Bar, Win11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-linuxs-best-pick-screen-capture-and-save-tools/"><u>2024 Approved  Linux's Best Pick  Screen Capture & Save Tools</u></a></li>
</ul></div>
