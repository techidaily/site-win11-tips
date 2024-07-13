---
title: "Quick Tips: Ignoring ‘License Expires’ Messages in Win11"
date: 2024-07-12T17:17:32.516Z
updated: 2024-07-13T17:17:32.516Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Quick Tips: Ignoring ‘License Expires’ Messages in Win11"
excerpt: "This Article Describes Quick Tips: Ignoring ‘License Expires’ Messages in Win11"
keywords: Win11 License Guide,Ignore Windows Alerts,Win11 Update Tricks,Bypass Licensing Errors,Fix Expiry Notices,Win11 Maintenance Tips,Manage Windows Updates
thumbnail: https://thmb.techidaily.com/90c2e01727fc918de7950373ab7790d2b6bd79b92f560dcc1472e9356e8fe972.png
---

## Quick Tips: Ignoring ‘License Expires’ Messages in Win11

 Have you encountered the alarming "your Windows license will expire soon" error message on your PC? That usually happens when the Windows license on your PC is expired or deemed invalid. However, if your Windows license is indeed genuine, there might be another issue preventing Microsoft from authenticating it properly.

 In the following sections, we will discuss the common causes behind this error and provide potential solutions to fix it.

## Why Does the “Your Windows License Will Expire Soon” Error Appear?

 The "Your Windows license will expire soon" error message can occur due to several factors, and here are the most prevalent ones:

* **Windows license is invalid:** Using an unauthorized or pirated version of Windows is one of the most common reasons why you might encounter this error message.
* **Hardware changes:** Performing hardware changes, such as replacing the motherboard in your system, can also lead to activation errors on Windows.
* **Connectivity issues:** Your computer might fail to connect to the Key Management Service (KMS) server due to network-related issues, resulting in activation errors.
* **Corrupt Activation Token files:** The **Tokens.dat** file contains the activation information for your Windows installation. If this file becomes inaccessible for some reason, you may encounter the “Your Windows license will expire soon” error on Windows.  
![Your Windows License Will Expire Soon Error on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/your-windows-license-will-expire-soon-error-on-windows.jpg)

 Now that you are aware of the common causes of this error, let's now focus on the potential solutions to resolve it.

## 1\. Apply Some Preliminary Fixes

 Before you try any advanced troubleshooting tips, it’s a good idea to start with some basic fixes.

* **Restart Windows Explorer:** Temporary issues with the Windows Explorer process can sometimes trigger the “Your Windows license will expire soon” error on your PC. If it’s nothing major, you should be able to fix it by simply [restarting the Windows Explorer process](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/).
* **Run the SFC Scan:** It’s possible that Microsoft is having trouble authenticating your Windows license due to corrupt or damaged system files. To repair these files, you can try [running the System File Checker (SFC) scan on your PC](https://www.makeuseof.com/system-file-checker-sfc-windows/).
* **Scan for Malware:** Another potential factor contributing to Windows activation issues is malware infection. To address this, you can try [scanning your PC for malware using PowerShell](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/) or Microsoft Defender.

## 2\. Run the Activation Troubleshooter

 Both Windows 10 and 11 offer various troubleshooters for addressing common system issues. In this case, you can take help from the Windows Activation troubleshooter to fix any issues that may have caused the “Your Windows license will expire soon” error on your PC.

 To run the Activation troubleshooter, use these steps:

1. Press **Win + I** to open the Settings app.
2. Navigate to **System > Activation**.
3. Click the **Troubleshooter** button.  
![Running the Windows Activation Troubleshooter-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/running-the-windows-activation-troubleshooter-1.jpg)

 Wait for the troubleshooter to do its thing, and then check if it resolves the error.

## 3\. Find Your Product Key and Activate Windows

 Another thing you can do to fix this error is to find your product key using the ShowKeyPlus app and then attempt to activate Windows again. Several users on the forums reported fixing the error with this method. You can also give it a go.

1. [Download the ShowKeyPlus app](https://www.microsoft.com/store/productId/9PKVZCPRX9NV) from the Microsoft Store.
2. Open the ShowKeyPlus app using the search menu.
3. Note down the **OEM key** in the **Home** tab.  
![ShowKeyPlus App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/showkeyplus-app-on-windows.jpg)
4. Press **Win + I** to open the Settings app.
5. In the **System** tab, click on **Activation**.
6. Click the **Change** button next to **Change product key**.
7. Enter the **OEM key** noted earlier and click **Next**.
8. Click the **Activate** button to confirm.  
![Update Product Key on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/update-product-key-on-windows.jpg)

## 4\. Activate Windows Using Command Prompt

 If you are unable to activate Windows via the Settings app, you can try to activate it through the Command Prompt. To do so, make sure that your PC is connected to the internet, and then use these steps:

1. Click the **magnifying icon** on the taskbar to access the search menu.
2. Type **cmd** in the box and select **Run as administrator**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Type **slmgr /ato** in the console and press Enter.  
![Activate Windows via Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/activate-windows-via-command-prompt.jpg)

 Wait for Command Prompt to validate your product key. You will see a message confirming the outcome of the activation process, whether it was successful or not. If the activation is successful, you should not see the “Your Windows license will expire soon” error after this.

## 5\. Rebuild the Tokens.dat File

 Tokens.dat is a system file related to Windows activation and licensing. If this file somehow gets corrupted, Windows may have trouble verifying the authenticity of your license and trouble you with the “Your Windows license will expire soon” error.

 You can try rebuilding the Tokens.dat file on your PC to see if that fixes the error. Here are the steps for the same.

1. Right-click on the **Start icon** or use the **Win + X** keyboard shortcut to open the Power User menu.
2. Select **Terminal (Admin)** from the list.
3. Type the following commands one by one and press **Enter** after each.  
`net stop sppsvc  
cd %windir%\system32\spp\store\2.0  
ren tokens.dat tokens.bar  
net start sppsvc  
cscript.exe %windir%\system32\slmgr.vbs /rilc`

 Restart your computer after running the above commands and then check if you still get the “Your Windows license will expire soon” error on your PC.

## 6\. Reset the Licensing Status

 In case your Windows license is not genuine, there's a workaround to dismiss the “Your Windows license will expire soon” message. This workaround involves resetting the activation period and [hiding the Activate Windows watermark](https://www.makeuseof.com/tag/remove-activate-windows-10-watermark/) via Command Prompt. Here are the steps you can follow.

1. [Open Command Prompt with administrative privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Type **slmgr /rearm** in the console and press **Enter**.
3. Restart your PC after running the command.  
![Reset the Activation Timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-the-activation-timer.jpg)

 It's worth noting that you can only utilize the above command a few times. Eventually, you will have to obtain a genuine Windows license to eliminate the error message permanently.

## Fixing the “Your Windows License Will Expire Soon” Error on Windows

 Since Microsoft limits access to various personalization and security features on systems with inactivated Windows licenses, it’s vital to troubleshoot errors like the “Your Windows license will expire soon”. One of the above fixes should help you resolve the error message on your Windows computer. However, if nothing works, you can consider reaching out to Microsoft tech support as a last resort.

 Have you encountered the alarming "your Windows license will expire soon" error message on your PC? That usually happens when the Windows license on your PC is expired or deemed invalid. However, if your Windows license is indeed genuine, there might be another issue preventing Microsoft from authenticating it properly.

 In the following sections, we will discuss the common causes behind this error and provide potential solutions to fix it.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://sound-optimizing.techidaily.com/new-in-2024-hearing-locations-of-exasperated-dogs-communicating-through-bark/"><u>New In 2024, Hearing Locations of Exasperated Dogs Communicating Through Bark</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-complete-guide-on-unlocking-apple-iphone-13-mini-with-a-broken-screen-drfone-by-drfone-ios/"><u>In 2024, Complete Guide on Unlocking Apple iPhone 13 mini with a Broken Screen? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explaining-the-red-x-its-role-in-file-system-navigation/"><u>Explaining the Red “X”: Its Role in File System Navigation</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-2024-approved-essential-windows-and-macos-daw-software-ranking-the-best/"><u>Updated 2024 Approved Essential Windows & macOS DAW Software Ranking the Best</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/the-ultimate-guide-3-premium-video-sound-enhancers-for-the-digital-age-for-2024/"><u>The Ultimate Guide 3 Premium Video Sound Enhancers for the Digital Age for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefine-access-restoring-standard-user-privileges-in-win11/"><u>Redefine Access: Restoring Standard User Privileges in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-desktop-with-these-8-innovative-personalization-steps-from-bubbleui/"><u>Elevate Your Desktop with These 8 Innovative Personalization Steps From BubbleUI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-windows-hello-recognition-work-again/"><u>Making Windows Hello Recognition Work Again</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-image-perfection-with-windows-photos-app/"><u>Effortless Image Perfection with Windows Photos App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-your-workflow-with-aero-shake-w11-tech/"><u>Optimizing Your Workflow with Aero Shake W11 Tech</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-the-art-of-vocal-transformation-utilizing-morphvox-for-competitive-gaming-advantage/"><u>New 2024 Approved The Art of Vocal Transformation Utilizing Morphvox for Competitive Gaming Advantage</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/full-guide-on-mirroring-your-xiaomi-redmi-note-12-5g-to-your-pcmac-drfone-by-drfone-android/"><u>Full Guide on Mirroring Your Xiaomi Redmi Note 12 5G to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-how-to-stay-on-top-of-youtube-moderation-standards/"><u>[Updated] 2024 Approved  How to Stay on Top of YouTube Moderation Standards</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-switching-on-or-off-the-registry-editor/"><u>Guide: Switching on or Off the Registry Editor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-audible-acuity-ending-echo-of-empty-spaces/"><u>Regain Audible Acuity: Ending Echo of Empty Spaces</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-windows-apps-into-linux-world/"><u>Integrating Windows Apps Into Linux World</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/fcpx-countdown-made-easy-3-simple-steps-to-get-started-for-2024/"><u>FCPX Countdown Made Easy 3 Simple Steps to Get Started for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-items-into-windows-11-taskbar/"><u>Integrating Items Into Windows 11 Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/budget-beware-top-7-hazards-with-sub-standard-windows-licenses/"><u>Budget Beware: Top 7 Hazards with Sub-Standard Windows Licenses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-your-networks-security-keys-five-steps-towards-error-elimination-in-windows/"><u>Mastering Your Network's Security Keys: Five Steps Towards Error Elimination in Windows</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-mobile-access-to-all-you-love-best-download-tools-for-android-and-ios/"><u>2024 Approved  Mobile Access to All You Love  Best Download Tools for Android and iOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-windows-service-failure-error-1053/"><u>Correcting Windows Service Failure Error 1053</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/make-a-tattoo-disappear-like-a-magic-for-2024/"><u>Make A Tattoo Disappear Like A Magic for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-erroneous-onedrive-tags-in-windows-file-system/"><u>Correcting Erroneous OneDrive Tags in Windows File System</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-why-does-the-pokemon-go-battle-league-not-available-on-lava-yuva-2-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Why does the pokemon go battle league not available On Lava Yuva 2 Pro | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/ways-to-find-unlocking-codes-for-huawei-p60-phones-by-drfone-android/"><u>Ways To Find Unlocking Codes For Huawei P60 Phones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-windows-file-thumbnail-absence-in-version-11/"><u>Correcting Windows File Thumbnail Absence in Version 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-oppo-find-x7-drfone-by-drfone-virtual-android/"><u>Catch or Beat Sleeping Snorlax on Pokemon Go For Oppo Find X7 | Dr.fone</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-the-best-mac-video-editing-tools-for-beginners-a-comprehensive-guide/"><u>New 2024 Approved The Best Mac Video Editing Tools for Beginners A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimizing-browser-resource-usage-winmacchromeos-comparison/"><u>Minimizing Browser Resource Usage: Win/Mac/ChromeOS Comparison</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-outlooks-error-0x80040610-in-windows-systems/"><u>Overcoming Outlook's Error 0X80040610 in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-establishing-windows-11-support-features/"><u>Re-Establishing Windows 11 Support Features</u></a></li>
<li><a href="https://screen-capture.techidaily.com/1715860789066-new-capture-every-moment-on-mac-free/"><u>[New] Capture Every Moment on Mac, FREE!</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-decoding-dimensions-the-key-to-perfect-aspect-ratios-in-video/"><u>[Updated] In 2024, Decoding Dimensions  The Key to Perfect Aspect Ratios in Video</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modern-standby-uncovering-its-defects-and-criticisms/"><u>Modern Standby: Uncovering Its Defects and Criticisms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-for-microsoft-pc-manager-on-w11/"><u>Essential Guide for Microsoft PC Manager on W11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-durecorder-uncovered-features-and-analysis/"><u>In 2024, DuRecorder Uncovered  Features and Analysis</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/the-future-of-video-editing-fast-reliable-and-64-bit-compatible-for-2024/"><u>The Future of Video Editing Fast, Reliable, and 64-Bit Compatible for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-a-visual-journey-the-art-of-editing-with-snapchat-filters/"><u>[New] In 2024, A Visual Journey  The Art of Editing with Snapchat Filters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/classic-lookup-resurrecting-w11-file-explorer/"><u>Classic Lookup: Resurrecting W11 File Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hidden-potential-utilize-hotkeys-to-control-windows-taskbar/"><u>Hidden Potential: Utilize Hotkeys to Control Windows Taskbar</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-epic-video-journeys-the-fastest-hits-reaching-100m-views-by-24/"><u>[New] Epic Video Journeys  The Fastest Hits Reaching 100M Views by '24</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-innovative-puzzles-await-in-leading-room-escape-experiences/"><u>[New] Innovative Puzzles Await in Leading Room Escape Experiences</u></a></li>
<li><a href="https://article-files.techidaily.com/top-offline-transcription-programs-for-speech-for-2024/"><u>Top Offline Transcription Programs for Speech for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-gifify-your-tweet-a-costless-how-to-guide/"><u>In 2024, Gifify Your Tweet  A Costless How-To Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diy-disk-clone-mastery-for-pc-enthusiasts/"><u>DIY Disk Clone Mastery for PC Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proactive-power-indicators-ensure-a-full-charge-with-windows-11-alerts/"><u>Proactive Power Indicators: Ensure a Full Charge with Windows 11 Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-onedrives-cant-add-your-folder-right-now-error-on-windows/"><u>How to Fix OneDrive's Can’t Add Your Folder Right Now Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-master-windows-blue-screen-troubleshooting/"><u>How to Master Windows Blue Screen Troubleshooting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-websites-windows-programs-a-tutorial/"><u>Making Websites Windows Programs: A Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-focus-amidst-windows-11s-multitask-features/"><u>Enhancing Focus Amidst Windows 11'S Multitask Features</u></a></li>
</ul></div>
