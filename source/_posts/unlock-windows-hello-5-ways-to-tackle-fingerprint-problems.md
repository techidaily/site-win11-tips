---
title: "Unlock Windows Hello: 5 Ways to Tackle Fingerprint Problems"
date: 2024-07-12T16:54:53.363Z
updated: 2024-07-13T16:54:53.363Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlock Windows Hello: 5 Ways to Tackle Fingerprint Problems"
excerpt: "This Article Describes Unlock Windows Hello: 5 Ways to Tackle Fingerprint Problems"
keywords: Windows Hello Troubleshooting,Fingerprint Lock Issues,Solve Windows Fingerprint Error,Overcome Windows Hello Failures,Fix Windows Fingerprint Login,Unlock Happy Methods,Windows Fingerprint Security Tips
thumbnail: https://thmb.techidaily.com/1a71493edba37cb030611c5a8b9738f6d63a9069f2561431aa2bb888dda851d0.jpg
---

## Unlock Windows Hello: 5 Ways to Tackle Fingerprint Problems

 Using a fingerprint scanner is perhaps the most convenient way to log in to your Windows computer. It not only eliminates the need to type in a complex password or PIN every time you want to access your computer but also saves you time. But what if Windows Hello fingerprint authentication stops working on your computer?

 Fortunately, there are several ways to fix this annoying issue. So, let’s dive in and explore what you should do when Windows Hello fingerprint login isn’t working.

## 1\. Remove and Re-Register Your Fingerprint

 Your first step is to remove your Windows Hello fingerprint and register it again. This may sound basic, but it is one of the most straightforward ways to get your fingerprint reader to work again. Here are the steps you can follow.

1. Press **Win + I** to open the Settings app.
2. Head to **Accounts > Sign-in options**.
3. Under the **Windows Hello** section, click the **Remove** button.  
![Windows Sign-in Options window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Remove-Windows-Hello-Fingerprint-1.jpg)
4. Once removed, click the **Set up** button and follow the on-screen instructions to register your fingerprint again.

 If the issue persists or if you are unable to remove and re-add your fingerprint due to the "This option is currently unavailable" error on the Windows Hello page, there may be a problem with the Biometric drivers on your PC.

## 2\. Reinstall the Biometric Device Driver

 Biometric drivers on your PC help Windows communicate with your PC's fingerprint scanner. If these drivers are outdated or malfunctioning, you may run into problems.

 Most of the time, you can fix the problem by simply uninstalling and reinstalling the driver on your PC. Here’s how you can go about it.

1. Right-click on the **Start** icon to open the Power User menu.
2. Select **Device Manager** from the list.
3. Expand **Biometric devices**.  
![Biometric Driver selected in Device Manager window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Biometric-Driver-in-Device-Manager-1.jpg)
4. Right-click on your fingerprint scanner device and select **Uninstall device**.
5. Select **Uninstall** to confirm.

 Additionally, you should also expand the **Universal Serial Bus Controllers** section in the Device Manager and look for any entries with a yellow exclamation. If you find any, right-click on them one by one and select **Uninstall device** to remove them.

 Restart your PC after completing the above steps and check if the issue still occurs.

## 3\. Run the Hardware and Devices Troubleshooter

 Windows 10 and 11 include a number of [troubleshooters for resolving various system-related issues](https://www.makeuseof.com/windows-11-troubleshooters/). In this case, you should run the Hardware and Devices troubleshooter. It will scan your computer’s fingerprint scanner for any issues and attempt to fix them.

 Follow these steps to run the Hardware and Devices troubleshooter on Windows:

1. Press **Win + R** to open the Run dialog box.
2. Type **msdt.exe -id DeviceDiagnostic** in the Open field and press **Enter**.
3. In the Hardware and Devices window, click **Next**.  
![Hardware and Devices Troubleshooter Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Hardware-and-Devices-Troubleshooter-Window.jpg)

 Wait for Windows to diagnose any issues with your computer. If any issues are detected, follow the on-screen instructions to apply the recommended fixes.

## 4\. Turn Off Fast Startup

 Fast Startup is a handy Windows feature that speeds up your PC's boot time after shutdown. However, this feature might sometimes prevent Windows from loading properly. When this happens, the fingerprint scanner may not work on your Windows 10 or 11 PC.

 Use one of the many ways to [disable Fast Startup on your Windows computer](https://www.makeuseof.com/windows-11-turn-on-or-off-fast-startup/) and see if that gets the fingerprint scanner to work.

## 5\. Configure Windows Biometric Service to Start Automatically

 The Windows Biometric Service is an essential program for Windows Hello, as it captures and manages your fingerprint data. Ideally, the service should start automatically every time Windows boots. However, this might not happen if the service is not configured correctly.

 Use these steps to configure the Windows Biometric Service:

1. Open the **Services** app using the search menu.
2. Scroll down to locate the **Windows Biometric Service** on the list.
3. Right-click on it and select **Properties**.
4. Click the drop-down menu to change the **Startup type** to **Automatic**.
5. Hit **Apply** followed by **OK**.  
![Windows Biometric Service Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Windows-Biometric-Service-Properties.jpg)

 Restart your PC after this. Following that, you should be able to sign in with your fingerprint.

## 6\. Enable Biometrics via the Local Group Policy Editor

 Another reason why Windows Hello fingerprint sign-in may not work is if the feature is disabled from the Local Group Policy. It's important to note that Group Policy Settings are only available on Professional, Education, and Enterprise editions of Windows. If you are on Windows Home, you don't need to worry about this step.

 To enable fingerprint authentication via the Local Group Policy Editor, use these steps:

1. Press **Win + S** to open the search menu.
2. Type **gpedit.msc** in the search box and press **Enter** to [open the Local Group Policy Editor](https://www.makeuseof.com/tag/open-local-group-policy-editor-windows/).
3. Use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Components > Biometrics**.
4. Check if all the policies within the Biometrics folder are enabled. If not, double-click each policy one by one and set them to **Enabled**.  
![Biometric Policies in Local Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Local-Group-Policy-Editor-Window-1.jpg)

 Restart your PC one more time and check if the issue is still there.

## 7\. Create a New User Account

 An issue with your current user account can also cause certain Windows features to stop working. This usually happens when your user account files get corrupted. If you suspect that to be the case, you can [create and switch to a new user account](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) to fix the issue. Here’s how you can go about it.

1. Press **Win + I** to open the Settings app.
2. Head to **Accounts > Other users**.
3. Click the **Add account** button.
4. In the Microsoft account window, click on **I don't have this person's sign-in information** and follow the on-screen prompts to create a new user account.  
![Microsoft Account Sign In Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Microsoft-Account-Sign-In-Window.jpg)

 Set up Windows Hello fingerprint login for your new user account and see if you can sign in with your fingerprint.

## 8\. Perform a System Restore

 If the fingerprint not working issue only occurred recently, you can use System Restore to revert Windows to a previous state. This will allow you to undo any changes that may have caused the issue. Note that this is only possible if you have previously [enabled System Restore on your PC](https://www.makeuseof.com/windows-11-enable-system-restore/).

 Follow these steps to perform a system restore on Windows:

1. Press **Win + S** to open the search menu.
2. Type **Create a restore point in the search box** and press **Enter**.
3. Under the **System Protection** tab, click on **System Restore**.
4. Click **Next**.
5. Select a restore point before the issue first appeared and hit **Next**.
6. Review all the details one more time before hitting **Finish**.  
![System Restore Dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/System-Restore-Dialog.jpg)

 Windows will restart and revert to the specified restore point. After that, the fingerprint should work as before.

## 9\. Install the Latest Windows Updates

 Microsoft regularly releases software updates for Windows 10 and Windows 11 to add new features, improve performance, and—crucially for our purposes—fix bugs. If the fingerprint not working issue is caused by a system bug, updating Windows to its most recent version should help.

 You can check for new updates by going to the **Windows Update** tab in the **Settings** app. Download and install any pending updates on your PC. Hopefully, this will resolve the issue.

## Fixing Windows Hello's Fingerprint Check

 It’s annoying when your PC's fingerprint scanner stops working all of a sudden. However, that shouldn’t force you to use your password or PIN to sign in to your computer.

 We hope one of the methods mentioned above has helped and you are able to sign in with your fingerprint again. However, if all else fails, you may want to consider resetting your Windows computer.

 Fortunately, there are several ways to fix this annoying issue. So, let’s dive in and explore what you should do when Windows Hello fingerprint login isn’t working.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/prioritize-protection-activating-tpm-and-secure-boot-before-w11-update/"><u>Prioritize Protection: Activating TPM and Secure Boot Before W11 Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-non-functional-headphonesspeakers-in-windows/"><u>Resolving Non-Functional Headphones/Speakers in WINDOWS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detailed-guide-to-implementing-bluescreenview-strategies/"><u>Detailed Guide to Implementing BlueScreenView Strategies</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-amplify-your-shorts-impact-with-bespoke-thumbnails/"><u>[Updated] 2024 Approved  Amplify Your Shorts' Impact with Bespoke Thumbnails</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-media-maker-tool-error-x90017-on-windows/"><u>Unraveling Media Maker Tool Error X.90017 On Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-fixing-non-detectable-windows-commands/"><u>Strategies for Fixing Non-Detectable Windows Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-approach-to-using-windows-11-calendar/"><u>A Practical Approach to Using Windows 11 Calendar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dismantling-barriers-to-running-powershell-scripts-in-windows/"><u>Dismantling Barriers to Running PowerShell Scripts in Windows</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-expanding-youtube-audience-through-perpetual-creative-commons/"><u>[New] 2024 Approved  Expanding YouTube Audience Through Perpetual Creative Commons</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/iphone-13-pro-asking-for-passcode-after-ios-1714-update-what-to-do-by-drfone-ios/"><u>iPhone 13 Pro Asking for Passcode after iOS 17/14 Update, What to Do?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-back-access-decoding-password-demand/"><u>Winning Back Access: Decoding Password Demand</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-loop-of-0xf0831-error-in-win11-os/"><u>Breaking the Loop of 0XF0831 Error in Win11 OS</u></a></li>
<li><a href="https://vp-tips.techidaily.com/a-comprehensive-guide-to-mastering-video-editing-tools-like-movie-maker-w11-for-2024/"><u>A Comprehensive Guide to Mastering Video Editing Tools Like Movie Maker W11 for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-essential-ae-plugin-selection-for-superior-results/"><u>[New] 2024 Approved  Essential AE Plugin Selection for Superior Results</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-windows-11-admin-details-effectively/"><u>Revamp Your Windows 11 Admin Details Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-archival-steganography-in-photos-windows-11/"><u>The Art of Archival Steganography in Photos (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-broken-system-defragmenter-execution/"><u>Rectifying Broken System Defragmenter Execution</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-crafting-emotional-impact-in-personal-youtube-content/"><u>[New] In 2024, Crafting Emotional Impact in Personal YouTube Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bf-price-war-save-612-on-endless-win10-lifetime-life/"><u>BF Price War: Save $6.12 on Endless Win10 Lifetime Life</u></a></li>
<li><a href="https://win11-tips.techidaily.com/protect-your-pc-identifying-the-7-most-suspicious-windows-processes/"><u>Protect Your PC: Identifying the 7 Most Suspicious Windows Processes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/purple-pandemonium-restore-your-pcs-color-calibration/"><u>Purple Pandemonium? Restore Your PC's Color Calibration</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-premium-timepieces-for-your-dream-wedding-on-smartphones/"><u>[Updated] Premium Timepieces for Your Dream Wedding on Smartphones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-connection-between-windows-11-and-print-devices/"><u>Restoring Connection Between Windows 11 and Print Devices</u></a></li>
<li><a href="https://change-location.techidaily.com/how-do-you-get-sun-stone-evolutions-in-pokemon-for-vivo-v27e-drfone-by-drfone-virtual-android/"><u>How Do You Get Sun Stone Evolutions in Pokémon For Vivo V27e? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-file-access-failures-in-microsoft-office-outlook/"><u>Correcting File Access Failures in Microsoft Office Outlook</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-techniques-to-upload-extended-videographics-on-instagram/"><u>[New] 2024 Approved  Techniques to Upload Extended Videographics on Instagram</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-before-and-after-editing-trick-filmora/"><u>Updated 2024 Approved Before & After Editing Trick - Filmora</u></a></li>
<li><a href="https://windows11.techidaily.com/decrypt-the-mystery-of-win11-blue-screen-with-11-hacks/"><u>Decrypt the Mystery of Win11 Blue Screen with 11 Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-integration-of-emulated-titles-in-playnite/"><u>Seamless Integration of Emulated Titles in Playnite</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slick-techniques-for-masking-windows-11-task-view/"><u>Slick Techniques for Masking Windows 11 Task View</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapt-calc-app-for-night-time-viewing-dark-mode-tutorial/"><u>Adapt Calc App for Night-Time Viewing: Dark Mode Tutorial</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/expert-advice-creating-and-uploading-vr-videos-to-boost-fb-visibility-for-2024/"><u>Expert Advice  Creating & Uploading VR Videos to Boost FB Visibility for 2024</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-unlock-apple-id-from-your-apple-iphone-6-without-security-questions-by-drfone-ios/"><u>In 2024, How to Unlock Apple ID From your Apple iPhone 6 without Security Questions?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-speed-minimizing-applications-via-keyboard-shortcuts/"><u>Unleash Speed: Minimizing Applications via Keyboard Shortcuts</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-momentum-media-10-hot-tweets-to-watch/"><u>[New] 2024 Approved  Momentum Media  10 Hot Tweets to Watch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformative-power-for-photo-renewal-with-windows/"><u>Transformative Power for Photo Renewal with Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-inactive-windows-system-voices/"><u>Addressing Inactive Windows System Voices</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-a-complete-guide-to-upload-longer-videos-on-youtube/"><u>2024 Approved  A Complete Guide to Upload Longer Videos on YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11s-potential-masterful-docx-to-pdf-migration/"><u>Unlocking Windows 11'S Potential: Masterful DOCX to PDF Migration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-high-cpu-usage-by-windows-ums-for-vanguard-users/"><u>Unraveling High CPU Usage by Windows’ UMS for Vanguard Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapidly-reach-word-definitions-on-your-system/"><u>Rapidly Reach Word Definitions on Your System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-utorrent-performance-in-win-os/"><u>Optimizing uTorrent Performance in Win OS</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-conquer-lunapic-elevate-your-photographic-skills/"><u>2024 Approved  Conquer Lunapic  Elevate Your Photographic Skills</u></a></li>
<li><a href="https://win11-tips.techidaily.com/triggering-windows-11s-stealthy-taskbar-spotlight/"><u>Triggering Windows 11'S Stealthy Taskbar Spotlight</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-1110-setup-with-rightful-permissions/"><u>Navigating Windows 11/10 Setup with Rightful Permissions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-installer-failures-on-older-windows-versions/"><u>Troubleshooting Installer Failures on Older Windows Versions</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-8-without-losing-any-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone 8 without Losing Any Data? | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/orchestrate-online-albums-photos-pair-with-songs/"><u>Orchestrate Online Albums  Photos Pair With Songs</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-the-leading-lineup-best-no-charges-music-transformation-apps-for-iphoneandroid-enthusiasts-for-2024/"><u>New The Leading Lineup Best No-Charges Music Transformation Apps for iPhone/Android Enthusiasts for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-the-tiktok-text-to-speech-expert-guide/"><u>[New] In 2024, The TikTok Text-to-Speech Expert Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-microsoft-store-functionality-in-windows-11/"><u>Restoring Microsoft Store Functionality in Windows 11</u></a></li>
</ul></div>
