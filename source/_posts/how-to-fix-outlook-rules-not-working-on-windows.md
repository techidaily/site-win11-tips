---
title: How to Fix Outlook Rules Not Working on Windows
date: 2024-07-12T16:50:07.363Z
updated: 2024-07-13T16:50:07.363Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix Outlook Rules Not Working on Windows
excerpt: This Article Describes How to Fix Outlook Rules Not Working on Windows
keywords: Fixed Outlook Rule Errors,Troubleshoot Outlook Rule Issues,Correct Outlook Rule Malfunction,Resolve Outlook Rules Problems,Fix Windows Outlook Rule Failure,Repair Outlook Rule Not Working,Tweak Non-Operational Outlook Rules
thumbnail: https://thmb.techidaily.com/f6048b78b677a0065b7683b7780e2c91c1ef9e11def92a26e974e1428f77307f.jpg
---

## How to Fix Outlook Rules Not Working on Windows

 By setting up Outlook rules, you can configure the app to handle your inbox efficiently. This allows you to save time and automate actions that would otherwise require manual effort. But what if these Outlook rules stop working on your Windows computer?

 To help out, we have compiled a list of useful solutions that should get Outlook rules to work again.

## 1\. Make Sure Outlook Rules Are Enabled

 To start, you need to ensure that you haven't inadvertently disabled any Outlook rules. To do so, use these steps:

1. Open the **Outlook** app and click the **File** menu in the top left corner.
2. In the **Info** tab, click the **Manage Rules & Alerts** button.
3. Under the **Email Rules** tab, make sure the boxes next to your rules are checked.  
![Enable Outlook Rules](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-outlook-rules.jpg)

## 2\. Rename Outlook Rules

 Using lengthy names for your Outlook rules can cause them to become larger in size, leading to unexpected issues with their functionality. To address this, try assigning shorter names to your Outlook rules and see if that gets things moving again.

 To rename Outlook rules, use these steps:

1. In the Outlook app, click the **File** menu in the top left corner.
2. In the **Info** tab, click the **Manage Rules & Alerts** button.
3. Under the **Email Rules** tab, select the rule you want to rename.
4. Click **Change Rule** and select **Rename Rule**.
5. Type in a shorter name for the rule and hit **OK**.
6. Click **Apply** to save the changes.  
![Rename Outlook Rule](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/rename-outlook-rule.jpg)

## 3\. Delete Unwanted Outlook Rules

 Apart from renaming rules, you can also consider deleting rules that you no longer need to prevent conflicts or unexpected behavior. Here’s how.

1. In the Outlook app, navigate to **File > Info > Manage Rules & Alerts**.
2. Hold down the **Ctrl** key and select the rules you no longer need.
3. Click the **Delete** option at the top.
4. Select **Yes** when prompted.  
![Delete a Outlook Rule](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/delete-a-outlook-rule.jpg)

## 4\. Reset the Outlook SRS File

 Microsoft Outlook stores essential account configuration in an SRS (Send and Receive Settings) file on your PC. If this file somehow becomes corrupted, Outlook rules won’t work. To fix this, you can force Outlook to recreate the SRS file by renaming the old file. Here's how.

1. Press **Win + R** to open the Run dialog box.
2. Type **%appdata%\\Microsoft\\Outlook** in the Open field and press **Enter**.
3. In the File Explorer window that opens, locate and select **Outlook.srs** file.
4. Press **F2** on your keyboard and [rename the file](https://www.makeuseof.com/windows-11-rename-files/) to **Outlook.srs.old**.  
![Rename Outlook SRS File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/rename-outlook-srs-file.jpg)

 Restart Outlook after completing the above steps and check if your rules work as expected.

## 5\. Disable the Stop Processing More Rules Option

 By adjusting the settings in the Outlook app, you can instruct it to halt the processing of additional rules once a specific rule has run. However, this can lead to Outlook ignoring all subsequent rules, giving a false impression that your rules are not functioning correctly. To avoid this, you need to disable the “stop processing more rules” option by following the steps below.

1. In Outlook, head over to **File > Info > Manage Rules & Alerts**.
2. Select your rule from the list.
3. Click the **Change Rule** option and select **Edit Rule Settings** from the list.  
![Edit Outlook Rule](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-outlook-rule.jpg)
4. Clear the **stop processing more rules** checkbox.
5. Click **Finish** and then **Apply**.

## 6\. Configure Outlook Rules to Run on All Devices

 Another reason why your Outlook rules may not work is if you have configured them to run on a specific device only. Here’s how you can change that.

1. In Outlook, head over to **File > Info > Manage Rules & Alerts**.
2. Double-click the problematic rule.
3. Under **Select conditions**, uncheck the **on this computer only** box.
4. Hit **Finish** followed by **Apply**.  
![Configure Outlook Rule](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/configure-outlook-rule.jpg)

## 7\. Activate Cached Exchange Mode

 When you enable the Cached Exchange Mode, Outlook retains a copy of your mailbox within the Outlook data file. This can help the app implement your rules without any issues.

 To enable Cached Exchange Mode in Outlook:

1. Open Outlook and click the **File** menu.
2. In the Info tab, click **Account Settings**, and select **Account Settings**.
3. Under the **Email** tab, select your account and click **Change**.
4. Click **More Settings** and select **Advanced**.
5. Tick the **Use Cached Exchange Mode** checkbox.
6. Hit **Apply** followed by **OK**.

## 8\. Run the Outlook Inbox Repair Tool

 When you use Microsoft Outlook on your Windows PC, it generates OST and PST files to store your account data locally. If these data files become inaccessible for some reason, your Outlook rules may stop working. Fortunately, Outlook includes an inbox repair tool that can help you [repair Outlook data files with ease](https://www.makeuseof.com/how-to-repair-corrupted-pst-and-ost-files-in-microsoft-outlook-using-recovery-toolbox/). Here’s how to run it.

1. Right-click the Outlook shortcut and select **Properties**.
2. Under the **Shortcut** tab, click the **Open File Location** button.
3. Double-click on **SCANPST.EXE** to run it.
4. In the Microsoft Outlook Inbox Repair Tool window, click the **Browse** button and then navigate to the following directory:  
`C:\Users\*username*\AppData\Local\Microsoft\Outlook`  
 Make sure you replace **\*username\*** in the above path with your own username.
5. Select the profile you want to repair and then click **Start**.  
![Outlook Inbox Repair Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/outlook-inbox-repair-tool.jpg)

 Restart Outlook after this and check if the issue is still there.

## 9\. Update the Outlook App

 Using an outdated version of Outlook can also lead to such issues. If you have [disabled automatic updates for Office apps](https://www.makeuseof.com/windows-stop-automatic-office-updates/), use these steps to update the Outlook app.

1. Open Outlook and select the **File** menu in the top-left corner.
2. Choose the **Office Account** tab from the left column.
3. Click **Update Options > Update Now**.  
![Update Outlook App in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/update-outlook-app-in-windows.jpg)

 Wait for Microsoft Office to check for new updates and install them. Following that, Outlook rules should start working.

## 10\. Reset All the Rules

 Lastly, if none of the above tips help, you can consider deleting all the Outlook rules and then setting them up again. Doing so will help fix any issues caused by improper configuration or corrupt data.

 To delete all the Outlook rules at once, [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **Outlook.exe /cleanrules** in the text box and press **Enter**.

![Delete Outlook Rules](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/delete-outlook-rules.jpg)

 Once Outlook deletes all the rules, head to **Manage Rules & Alerts** and set them up again.

## Manage Your Emails Efficiently With Outlook Rules

 Without Outlook rules, organizing your inbox can be quite challenging, especially if you receive a lot of emails throughout the day. Hopefully, one or more of the above tips have proven useful, and Outlook rules are now working as before.

 To help out, we have compiled a list of useful solutions that should get Outlook rules to work again.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://phone-solutions.techidaily.com/cant-play-mp4-files-on-samsung-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Can't play MP4 files on Samsung</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-ultimate-guide-on-honor-90-pro-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide on Honor 90 Pro FRP Bypass</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-fix-auto-lock-greyed-out-on-iphone-xs-max-by-drfone-ios/"><u>In 2024, How To Fix Auto Lock Greyed Out on iPhone XS Max</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-reinstate-your-devices-access-post-error-22/"><u>Guide to Reinstate Your Device's Access Post Error 22</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719242997504-navigate-past-chrome-hiccups-fixes-for-w11-users/"><u>Navigate Past Chrome Hiccups: Fixes for W11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-java-vm-creation-failed-in-windows/"><u>Troubleshooting Java VM Creation Failed in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-reasons-to-use-the-new-outlook-app-on-windows/"><u>9 Reasons to Use the New Outlook App on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-improving-win11-point-accuracy-and-size/"><u>Guide to Improving Win11' Point Accuracy & Size</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-users-guide-to-managing-monitor-luminosity/"><u>Win Users Guide to Managing Monitor Luminosity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/administrative-controls-unveiled-windows-11-and-home-edition/"><u>Administrative Controls Unveiled: Windows 11 & Home Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-msresourceappname-text-glitch-win11-fix/"><u>Addressing 'MsResource/AppName Text' Glitch, Win11 Fix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-lightweight-browser-ram-usage-with-comparative-tests/"><u>Exploring Lightweight Browser RAM Usage with Comparative Tests</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-the-secrets-of-editing-numerical-data-in-tiktoks/"><u>2024 Approved  The Secrets of Editing Numerical Data in TikToks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaching-windows-login-restrictions-a-quick-guide/"><u>Breaching Windows Login Restrictions: A Quick Guide</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/social-media-supremacy-top-10-youtube-influencers-for-2024/"><u>Social Media Supremacy  Top 10 YouTube Influencers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-signature-verification-issue-in-winoses/"><u>Eradicating Signature Verification Issue in WinOSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-mend-flickering-screens-in-windows-11/"><u>How to Mend Flickering Screens in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cpu-gen-identification-using-eight-proven-windows-methods/"><u>CPU Gen Identification Using Eight Proven Windows Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-successfully-unplug-epic-games-from-your-w11-system/"><u>How to Successfully Unplug Epic Games From Your W11 System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-stuttering-challenges-enhancing-warhammer-40k-experience/"><u>Conquer Stuttering Challenges: Enhancing Warhammer 40K Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-invalid-device-label-in-windows-os/"><u>Correcting 'Invalid Device' Label in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-solve-the-disconnected-from-nvidia-experience-problem-in-win-11/"><u>How to Solve the 'Disconnected From NVIDIA Experience' Problem in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-productivity-easy-drive-mapping-for-windows-11-users/"><u>Enhancing Productivity: Easy Drive Mapping for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-sid-retrieval-for-all-users-on-windows-11/"><u>Mastering SID Retrieval for All Users on Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-do-i-stop-someone-from-tracking-my-vivo-s17e-drfone-by-drfone-virtual-android/"><u>In 2024, How Do I Stop Someone From Tracking My Vivo S17e? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-a-global-keyboard-downloading-windows-fonts/"><u>Crafting a Global Keyboard: Downloading Windows Fonts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-moves-for-unlocking-the-calculator-in-windows-11/"><u>Key Moves for Unlocking the Calculator in Windows 11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-elevate-your-recording-game-with-nvidias-tools/"><u>[New] In 2024, Elevate Your Recording Game with NVIDIA's Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-event-viewer-breakdowns/"><u>Addressing Windows Event Viewer Breakdowns</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rescue-your-vscode-session-w11/"><u>How to Rescue Your VSCode Session W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-act-comparing-two-essential-windows-metrics/"><u>Balancing Act: Comparing Two Essential Windows Metrics</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-navigating-instagrams-question-marker-magic/"><u>In 2024, Navigating Instagram’s Question Marker Magic</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-resolve-defenders-0x80004004-error/"><u>Guide to Resolve Defender's 0X80004004 Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-method-integrating-airpods-with-windows/"><u>Efficient Method: Integrating AirPods with Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/desktop-configuration-mastery-embedding-this-pc-symbols/"><u>Desktop Configuration Mastery: Embedding 'This PC' Symbols</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-9-best-phone-monitoring-apps-for-huawei-p60-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Best Phone Monitoring Apps for Huawei P60 | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-ios-system-of-iphone-13-pro-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair iOS System of iPhone 13 Pro? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-snapshot-showdown-youtube-shorts-challenge-to-the-titans-of-tiktok/"><u>[Updated] Snapshot Showdown  YouTube Shorts Challenge to the Titans of TikTok</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-teamsters-shutdown-on-windows-11-10-systems/"><u>Avoiding Teamsters Shutdown on Windows 11, 10 Systems</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-2024-approved-make-a-lasting-impression-youtubes-anime-style-subscribe-buttons-in-filmora/"><u>[Updated] 2024 Approved  Make a Lasting Impression - YouTube's Anime-Style Subscribe Buttons in Filmora</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-syncing-on-windows-the-most-rated-apps/"><u>Mastering File Syncing on Windows: The Most Rated Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-self-scrolled-windows-with-ease-and-precision/"><u>Fix Self-Scrolled Windows with Ease and Precision</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-mastery-building-hotkeys-for-repetitive-text-snapping-tasks/"><u>Windows 11 Mastery: Building Hotkeys for Repetitive Text Snapping Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-random-restarts-on-windows-11-systems/"><u>Troubleshoot Random Restarts on Windows 11 Systems</u></a></li>
</ul></div>
