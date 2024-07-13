---
title: Eradicate ScanDisk Errors for a Smooth Run
date: 2024-07-12T16:39:28.885Z
updated: 2024-07-13T16:39:28.885Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eradicate ScanDisk Errors for a Smooth Run
excerpt: This Article Describes Eradicate ScanDisk Errors for a Smooth Run
keywords: Fix ScanDisk Issues,Smooth Disk Use,Remove Disk Errors,Optimize Windows,Eradicate Drive Errors,ScanDisk Solution,Uninterrupted System Run
thumbnail: https://thmb.techidaily.com/e1e3cd6b008cdab8aeee33309c0a15674cf83671f125b94d0f79189ce7d24b4f.jpg
---

## Eradicate ScanDisk Errors for a Smooth Run

 Errors and bugs can pop up on your Windows device, no matter how well you maintain it. One such error is related to your computer's disk, which can prevent your system from booting up properly and restrict access to your files and applications.

 Let's look at various methods to repair the disk issue on your Windows device.

## Why Does the "Repairing Disk Errors" Issue Occur?

 When the disk error occurs, your computer reboots with an error message: "**Repairing disk errors. This might take over an hour to complete.**" Most of the time, this error will just show up once and won't appear the next time you reboot, but sometimes it will show up every single time you boot your PC.

 Usually, this error is caused by:

* A sudden power failure.
* An improper system shutdown.
* Physical damage to your hard drive.
* Corrupted Windows system.

 Now let’s look at possible troubleshooting ways to fix the repairing disk error on your Windows device.

## 1\. Start With These Basic Fixes

 When your Windows computer starts showing disk errors, there are a few initial steps you can take before moving on to more advanced solutions. Here's what we recommend doing:

* **Wait for an hour to pass:** Sometimes, the easiest solution is to wait. If this is the first time you've encountered this error message in a while (if ever), give it an hour, and the error might resolve itself, allowing your computer to reboot normally.
* **Check your drive for physical damage:** If your drive has suffered physical damage, this can lead to this error constantly popping up. Inspect your disk drive for any damage.
* **Revert to a previous time with a System Restore point:** System Restore undoes recent system changes without affecting your files. If the error started appearing recently, try [using System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) and see if that fixes things.

 If the above solutions are not working for you, it's time to get started with the advanced troubleshooting methods.

## 2\. Run the Startup Repair Utility

 The Startup Repair tool is a built-in Windows feature to fix problems preventing your computer from starting correctly. This tool can be a lifesaver if your system keeps encountering errors when booting up.

 Here's how you can use the Startup Repair tool on your computer:

1. Launch the Settings app and go to **System > Recovery**.
2. On the Settings window, click on **Restart now** button (located next to **Advanced startup**).  
![Advanced Startup Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/advanced-startup-option.jpg)
3. A blue-colored screen must appear now. From there, click on **Troubleshoot > Advanced options** and then **Startup Repair**.  
![Startup Repair Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-repair-option.jpg)

 The repair tool will then scan for any corrupted files to repair. If this doesn't work, check out [what to do if Startup Repair fails to fix your PC](https://www.makeuseof.com/what-to-do-if-startup-repair-fails-to-repair-your-pc/).

 Once the repair process begins, avoid interrupting it or turning off your computer. Doing so could corrupt Windows even further.

## 3\. Run the SFC and CHKDSK Tools

 If the startup repair tool does not work, it's time to use the Command Prompt to run the System File Checker and CHKDSK tool.

 The System File Checker (SFC) tool checks your computer for any buggy system files and then tries to fix them. Most of the time, this resolves the disk error issue and other [startup issues on Windows](https://www.makeuseof.com/windows-11-startup-issues-fix/).

 Follow the steps given below to use the System File Checker and CHKDSK:

1. Launch the [Command Prompt with administrator rights](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. On the Command Prompt window, input the **sfc /scannow** command and then **Enter**.
3. Then, type **chkdsk %SystemDrive% /scan** and again press **Enter**.  
![CHKDSK SCAN Command Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command-preview.jpg)

 The above-given commands initiates a thorough scan of your system. It might take a while, and once completed, you should no longer see the black screen on startup.

 If you cannot access your desktop, you can also run the Command Prompt and the given commands via Windows safe mode.

 If these commands came in handy, be sure to check out all the [built-in Windows tools that repair corrupted system files](https://www.makeuseof.com/windows-built-in-repair-tools/).

## 4\. Update the Disk Controller Driver

 The "disk controller driver" usually appears under a variety of names, like "Standard SATA AHCI" Controller. It is a Windows driver that establishes communication between your operating system and your hard drive. If the disk controller driver gets outdated, it can lead to disk-related errors.

 Follow these steps to update the disk controller driver on your PC:

1. Press **Win + X** and click on **Device Manager** from the menu.  
![Device Manager In Power Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/device-manager-in-power-menu.jpg)
2. Expand the **IDE ATA/ATAPI controllers** category. Right-click on your disk controller driver (in our case, **Standard SATA AHCI Controller**) and select **Update driver**.  
![Windows 11 Device Manager Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-11-device-manager-preview.jpg)
3. Choose **Search automatically for drivers**, then **Search for updated drivers on Windows Update**. Windows will then search for the necessary updates for your disk controller driver.  
![Windows 11 Update Drivers Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-11-update-drivers-window.jpg)
4. Once it installs the driver update, restart your computer. If the error black screen doesn't appear, it means your issue is resolved.

## 5\. Try a Third-Party Disk Repair Tool

 Sometimes the in-built Windows tools for troubleshooting are of no use. So, you have to depend on third-party tools to investigate the issue. We'll use a free tool called Macrorit Partition Expert for this guide.

 Third-party disk repair tools are not a sure-shot fix. They sometimes work and sometimes create more trouble with the system. So, before using any tool, [create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) as a backup.

 Here's how to use the Macrorit Partition Expert tool on Windows:

1. Download the tool from [the Macrorit website](https://macrorit.com/partition-magic-manager/partition-expert-download.html) and install the application.
2. Click on **dm.exe** to run Macrorit Partition Expert.  
![Macrorit Partition Expert Files](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/macrorit-partition-expert-files.jpg)
3. On the application window, select the disk or volume where your current Windows is present. For example, in our case, it's in **Disk 0**.
4. After selecting, click on **Check Volume** from the left-hand sidebar.  
![Macrorit Partition Expert Application](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/macrorit-partition-expert-application.jpg)
5. Choose **Fix found errors**, **Try to fix found bad sectors**, and click **OK**.  
![Macrorit Partition Expert Volume Checker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/macrorit-partition-expert-volume-checker.jpg)

 Now, Macrorit Partition Expert will analyze your selected disk to check for any bad sectors and try to fix them.

## 6\. Factory Reset Windows

 If none of the fixes were helpful, you must reinstall Windows OS as a last resort. This will wipe all the data from your computer, so ensure to back up your important data.

 Once you've backed up your files, check out [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/). Once the reinstallation is complete, you'll have a clean slate to work with, and you can restore all the files you've backed up.

## No More Disk Errors on Windows

 As said earlier, there's no fixed reason for the repairing disk error. However, one thing that causes the error is an issue with your disks, such as bad sectors, physical damage, and viruses.

 If you fail to resolve the issue, consider resetting your computer and fresh set up everything.

 Let's look at various methods to repair the disk issue on your Windows device.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/reclaiming-lost-wireless-ties-with-these-10-windows-10-tweaks/"><u>Reclaiming Lost Wireless Ties with These 10 Windows 10 Tweaks</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-google-play-services-keeps-stopping-on-motorola-moto-g73-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What to Do if Google Play Services Keeps Stopping on Motorola Moto G73 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unzipping-challenge-managing-multiple-compressed-files-in-a-snap/"><u>Unzipping Challenge: Managing Multiple Compressed Files in a Snap</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-restore-razer-devices-detection-via-synapse-on-windows/"><u>Steps to Restore Razer Devices Detection via Synapse on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secrets-to-turn-off-lurking-apps-in-window-11/"><u>Secrets to Turn Off Lurking Apps in Window 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/enabling-virtual-reality-on-your-phone-a-step-by-step-approach/"><u>Enabling Virtual Reality on Your Phone  A Step-by-Step Approach</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-premium-online-vendors-for-artisanal-wrapping-solutions/"><u>2024 Approved  Premium Online Vendors for Artisanal Wrapping Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-systemsettings-issues-on-win11/"><u>Strategies to Overcome SystemSettings Issues on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-needed-parts-error-on-windows-1011-systems/"><u>Solving Needed Parts Error on Windows 10/11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/system-mastery-a-path-through-preferences/"><u>System Mastery: A Path Through Preferences</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-dungeons-deep-and-deeper-old-school-and-hybrid-games/"><u>2024 Approved  Dungeons Deep & Deeper  Old School and Hybrid Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-multiple-users-ms-logins-on-pc/"><u>Tackling Multiple Users' MS Logins on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-file-lockdowns-access-restoration-on-pcs/"><u>Reversing File Lockdowns: Access Restoration on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-windows-standard-power-profile/"><u>Restoring Windows' Standard Power Profile</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-step-by-step-procedures-for-producing-high-quality-asmr-videos/"><u>2024 Approved  Step-by-Step Procedures for Producing High-Quality ASMR Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safeguarding-internal-builds-in-windows-11/"><u>Safeguarding Internal Builds in Windows 11</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-unveiling-the-art-of-screencasting-orderly-tutorial-series-for-2024/"><u>[Updated] Unveiling the Art of Screencasting  Orderly Tutorial Series for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/all-you-need-to-know-about-mega-greninja-for-poco-f5-pro-5g-drfone-by-drfone-virtual-android/"><u>All You Need To Know About Mega Greninja For Poco F5 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-cross-device-note-utilization-guide/"><u>Windows 11 Cross-Device Note Utilization Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safe-windows-storage-expansion-methods/"><u>Safe Windows Storage Expansion Methods</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-my-spouse-from-spying-on-my-motorola-g24-power-drfone-by-drfone-virtual-android/"><u>How to Stop My Spouse from Spying on My Motorola G24 Power | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-quick-ways-to-check-your-graphics-card-model-on-windows-11/"><u>3 Quick Ways to Check Your Graphics Card Model on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-lost-window-steam-connectivity/"><u>Restoring Lost Window-Steam Connectivity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-prevent-apex-legends-crashes-w11/"><u>Strategies to Prevent Apex Legends Crashes W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uniting-your-inboxes-connecting-gmail-with-windows-outlook-app/"><u>Uniting Your Inboxes: Connecting Gmail with Windows' Outlook App</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/optimizing-performance-a-deep-dive-into-streamlabs-obs-for-2024/"><u>Optimizing Performance  A Deep Dive Into Streamlabs OBS for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-manage-disks-keyways-into-windows-11s-storage-manager/"><u>Swiftly Manage Disks: Keyways Into Windows 11'S Storage Manager</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-horizontal-vs-vertical-deciding-the-right-face-for-vids/"><u>2024 Approved  Horizontal Vs. Vertical - Deciding the Right Face for Vids</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-guide-for-converting-cr2-images-to-windows-jpeg-files/"><u>Stepwise Guide for Converting CR2 Images to Windows JPEG Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-security-by-learning-the-quickest-ways-to-access-credentials-in-win11/"><u>Skyrocket Security by Learning the Quickest Ways to Access Credentials in Win11</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-foodie-festivals-viral-virtues-of-tiktok-meals/"><u>[Updated] In 2024, Foodie Festivals  Viral Virtues of TikTok Meals</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-iphones-premier-video-tools-pick-cameo-over-filmorago-for-2024/"><u>[Updated] IPhone's Premier Video Tools  Pick Cameo Over FilmoraGo for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/tackling-background-noise-in-virtual-presentations/"><u>Tackling Background Noise in Virtual Presentations</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-masterful-tools-for-youtube-text-extraction-online/"><u>In 2024, Masterful Tools for YouTube Text Extraction Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-counteract-internal-error-with-remote-desktop/"><u>Strategies to Counteract Internal Error with Remote Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719295110946-get-a-free-self-hosted-gptclone-with-gpt4all/"><u>Get a Free, Self-Hosted GPTClone with GPT4All</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-solutions-for-we-encountered-an-error-during-oculus-install/"><u>Step-By Step Solutions for We Encountered an Error During Oculus Install</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/honor-x50i-messages-recovery-recover-deleted-messages-from-honor-x50i-by-fonelab-android-recover-messages/"><u>Honor X50i Messages Recovery - Recover Deleted Messages from Honor X50i</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-windows-photos-apps-generative-erase-is-actually-great/"><u>The Windows Photos App's Generative Erase Is Actually Great</u></a></li>
<li><a href="https://win11-tips.techidaily.com/workarounds-to-manipulate-windows-11-sleepwake/"><u>Workarounds to Manipulate Windows 11 Sleep/Wake</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackle-windows-camera-problems-with-expert-tips/"><u>Tackle Windows Camera Problems with Expert Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/traverse-backward-commanding-windows-11-history/"><u>Traverse Backward: Commanding Windows 11 History</u></a></li>
</ul></div>
