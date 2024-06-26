---
title: Troubleshooting Deactivated Rulesets in Outlook/Windows
date: 2024-06-25T17:05:50.936Z
updated: 2024-06-26T17:05:50.936Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Deactivated Rulesets in Outlook/Windows
excerpt: This Article Describes Troubleshooting Deactivated Rulesets in Outlook/Windows
keywords: Fix Outlook Rule Errors,Reactivate Deactivated Rules,Resolve Outlook Issues,Unblock Windows Rules,Restart Disabled Mail Filters,Reclaim Outlook Settings,Reinstate Email Automatics
thumbnail: https://thmb.techidaily.com/3ce7ce4cef66cdb03e7ac7e019dea8d112e1795f84ca632563f78a12990cc533.jpg
---

## Troubleshooting Deactivated Rulesets in Outlook/Windows

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/elevate-screen-radiance-on-windows-11-practical-fixes/"><u>Elevate Screen Radiance on Windows 11: Practical Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-file-access-mastering-network-drives-in-win11/"><u>Seamless File Access: Mastering Network Drives in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-snipping-tool-with-a-simple-key-combo-on-win-11/"><u>Activating Snipping Tool with a Simple Key Combo on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/repairing-password-management-on-windows-systems/"><u>Repairing Password Management on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-0x800704cf-from-windows-marketplace/"><u>Eliminating 0X800704CF From Windows Marketplace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformative-power-for-photo-renewal-with-windows/"><u>Transformative Power for Photo Renewal with Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halt-unsolicited-opens-in-ms-store-on-windows-10/"><u>Halt Unsolicited Opens in MS Store on Windows 10</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-the-ultimate-guide-to-mobile-video-editing-top-apps-compared/"><u>Updated The Ultimate Guide to Mobile Video Editing Top Apps Compared</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-20-complimentary-luts-available-for-dji-miniair-2-users/"><u>[Updated] 20 Complimentary LUTs Available for DJI Mini/Air 2 Users</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-expertly-evaluating-webcam-technology-for-professionals/"><u>[Updated] 2024 Approved  Expertly Evaluating WebCam Technology for Professionals</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-nokia-c300-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>How to Track Nokia C300 Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-switch-clash-top-10-intense-battles-to-play/"><u>In 2024, Switch Clash  Top 10 Intense Battles to Play</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-in-2024-create-slide-masking-effect-intro/"><u>Updated In 2024, Create Slide Masking Effect Intro</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/how-to-use-tiktok-on-mac-and-pc-computers/"><u>How to Use TikTok on Mac and PC Computers?</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-transform-your-favorite-videos-into-mp3s-with-these-proven-converters-for-2024/"><u>Updated Transform Your Favorite Videos Into MP3s with These Proven Converters for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>