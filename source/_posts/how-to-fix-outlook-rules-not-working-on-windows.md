---
title: How to Fix Outlook Rules Not Working on Windows
date: 2024-06-25T16:23:57.301Z
updated: 2024-06-26T16:23:57.301Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/win-11-and-the-lost-bluetooth-9-effective-solutions-to-find-your-connection/"><u>Win 11 and the Lost Bluetooth: 9 Effective Solutions to Find Your Connection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-needs-user-id-login-failures/"><u>Troubleshooting Windows Needs User ID Login Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-use-an-additional-monitor-without-gui-chipset/"><u>How to Use an Additional Monitor Without GUI Chipset</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-shortage-of-physical-storage-space-vm-errors/"><u>Resolving Shortage of Physical Storage Space (VM) Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-establish-your-windows-hello-fix-unresponsive-fingerprints/"><u>Re-Establish Your Windows Hello: Fix Unresponsive Fingerprints</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snipcam-issues-quick-solutions-for-troubleshooting/"><u>SnipCam Issues: Quick Solutions for Troubleshooting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-windows-11s-full-potential-through-taskbar-utilization/"><u>Unleash Windows 11'S Full Potential Through Taskbar Utilization</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-protecting-melodies-on-instagram-for-2024/"><u>[Updated] Protecting Melodies on Instagram for 2024</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-top-online-image-resizers-for-perfect-proportions/"><u>Updated Top Online Image Resizers for Perfect Proportions</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-life360-on-windows-pc-for-xiaomi-redmi-13c-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Life360 on Windows PC For Xiaomi Redmi 13C? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-unlock-from-iphone-15-pro-max-how-to-fix-it-by-drfone-ios/"><u>Apple ID Unlock From iPhone 15 Pro Max? How to Fix it?</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-ultimate-strategy-guide-to-digital-video-enhancement/"><u>[New] The Ultimate Strategy Guide to Digital Video Enhancement</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/prime-sound-alteration-apps-for-vloggers/"><u>Prime Sound Alteration Apps for Vloggers</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-mastering-movies-with-yi-4k-hero/"><u>In 2024, Mastering Movies with YI 4K HERO</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-obs-glitch-fix-stop-frames-from-dropping/"><u>[Updated] OBS Glitch Fix  Stop Frames From Dropping</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-perfecting-the-introduction-writing-impressive-summaries/"><u>2024 Approved  Perfecting the Introduction  Writing Impressive Summaries</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>