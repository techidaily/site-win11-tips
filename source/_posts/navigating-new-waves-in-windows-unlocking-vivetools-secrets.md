---
title: "Navigating New Waves in Windows: Unlocking ViVeTool's Secrets"
date: 2024-07-12T17:21:38.860Z
updated: 2024-07-13T17:21:38.860Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Navigating New Waves in Windows: Unlocking ViVeTool's Secrets"
excerpt: "This Article Describes Navigating New Waves in Windows: Unlocking ViVeTool's Secrets"
keywords: Windows Navigation Guide,ViVeTool Insights,Software Tool Tips,Tech Trend Exploration,Innovation in Tools,Mastering New Software,Unlocking Development Secrets
thumbnail: https://thmb.techidaily.com/6aaf83c5a09999402e25379b87750585dedbdeb12f25c6a6196a672ab852e088.jpg
---

## Navigating New Waves in Windows: Unlocking ViVeTool's Secrets

 ViVeTool is an open-source command-line tool to enable experimental but hidden features on your Windows computer. It is also available in a GUI version, which makes it much easier to enable or disable certain features on Windows.

 It allows you to try newer and unreleased features on your stable or developer Windows releases, such as the multi-tab feature in File Explorer or restore the classic Windows 11 context menu. But should you use ViVeTool? Let’s find out!

## What Is ViVeTool, and How Does It Work?

 ViVeTool is a third-party open-source C# library and console app to enable unreleased features on your Windows computer. You can also use it to restore or disable certain features.

 ViVeTool uses feature IDs, part of Windows Feature Management, a software-development practice, to identify the available features. You can then use the feature IDs to enable or disable certain features on your Windows computer by using the ViVeTool command-line or GUI utility.

 For example, if you want to remove the new search box and replace it with the classic search icon, you’ll need to run the **ViVetool /disable /id:39263329** command using the ViVeTool command-line utility.

 The **feature ID id:39263329** in the above command tells the ViVeTool and the subsequent API request which feature to toggle on your Windows computer.

 You can source the feature ID from the internet or by using the ViVeTool GUI version. That said, the feature ID description in the GUI version is mostly cryptic, so tread carefully. Once you have the feature ID, you can use the ViVeTool command-line or GUI version to enable or disable features on your Windows computer.

## Is ViVeTool Safe to Use?

 ViVeTool doesn’t add new features on its own. It simply toggles the existing features to enable or disable them for your Windows system. However, since these features are experimental by nature, activating them may sometimes cause some issues.

 If you want to use ViVeTool on your daily driver, go through the [Windows data backup and recovery options](https://www.makeuseof.com/tag/ultimate-windows-10-data-backup-guide/) and proceed with the steps below. Ideally, use a virtual machine to test new features, and if found to be stable, apply them to your daily driver.

## How to Download and Install the ViVeTool GUI Version

 ViVeTool GUI is the forked version of the ViVeTool command-line utility. It is less complicated to use and removes the hassle of executing commands or remembering them in the first place. The GUI version is available as an executable installer or portable version. Here’s how to install and use ViVeTool GUI on Windows.

 To download the ViVeTool GUI version:

1. Go to the [ViVeTool GUI page](https://github.com/PeterStrick/ViVeTool-GUI/releases/) on GitHub.  
![download vivetool gui zip](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/download-vivetool-gui-zip.jpg)
2. Download the latest version of the **Setup.exe file** available. You can also download a portable version if you prefer.
3. Run the setup file and keep the default settings. Follow the on-screen instructions to install the app.

## How to Install Unreleased Features Using ViVeTool on Windows

 Now that the app is installed, you can use it to find and install unreleased features on your Windows computer. Here’s how to do it:

1. Launch the ViVeTool using a desktop shortcut or from the **Start** menu.  
![vivetool gui select build](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/vivetool-gui-select-build.jpg)
2. Click the **Select Build** drop-down in the top-left corner and select your **Windows build.** You can [check Windows 11 build and version](https://www.makeuseof.com/check-build-and-version-windows-11/) using the **Settings app**. ViVeTool GUI will now start looking for all the available features for the selected build. This may take a few minutes, so wait till the list is populated.
3. ViVeTool GUI categorizes the available features into different categories, including **Always Disabled**, **Always Enabled**, **Disabled by Default**, **Enabled by Default**, and **Modifiable**. You can expand the category and select the feature to install.
4. Next, select the feature you want to enable or disable. Alternatively, type the feature name in the search bar to find a specific feature.  
![activate feature vivetool gui](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/activate-feature-vivetool-gui.jpg)
5. Click the **Perform Action** drop-down select **Activate** to enable the feature. Wait for the success message and click **Close**.  
![revert to default values feature vivetool gui](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/revert-to-default-values-feature-vivetool-gui.jpg)
6. If the changes are not immediately visible, [restart Windows Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) to apply the changes. In some instances, you may need to restart your PC to make the changes.

 To revert the changes or disable a feature, you can use the Deactivate Feature option available in ViVeTool. Here's how to disable a feature using ViVeTool:

![deactivate feature vivetool gui](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/deactivate-feature-vivetool-gui.jpg)

1. Launch **ViVeTool GUI.**
2. Search and select the feature you want to disable.
3. Click the **Perform Action** drop-down in the top-right corner.
4. Select **Deactivate Feature** and click **OK**.

 Alternatively, you can also revert the feature to its default state. To do this, select the modified feature, click on **Perform Action,** and select **Revert Feature to Default Values.** The changes will take effect when you restart your computer next time.

 Here are a few new and lesser-known Windows features that you can enable using ViVeTool before anyone else:

* [Enable Windows Copilot Using ViVeTool](https://www.makeuseof.com/enable-windows-copilot-vivetool/)
* [Enable the Home Section in the Settings App in Windows 11](https://www.makeuseof.com/enable-home-section-settings-app-windows-11/)
* [Enable Instant Search Results in File Explorer in Windows 11](https://www.makeuseof.com/instant-search-results-file-explorer-windows-11/)
* [Enable the Enhanced Taskbar in Windows 11](https://www.makeuseof.com/enhanced-taskbar-settings-windows-11/)
* [Enable the Volume Mixer in the Action Center in Windows 11](https://www.makeuseof.com/volume-mixer-action-center-windows/)

## How to Use the ViVeTool Command-Line Version

 The original version of ViVeTool is a command-line utility. While it offers similar functionality as the GUI version, it is an efficient way to enable and disable Windows features quickly. Here’s how to do it:

1. Go to the [ViVeTool page](https://github.com/PeterStrick/ViVeTool-GUI/releases/) on GitHub. This lists all the releases of ViVeTools since its inception.  
![download vivetool command line zip](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/download-vivetool-command-line-zip.jpg)
2. Locate the latest version of ViVeTools. As of writing this, **Version 1.6.2** is the latest stable release available, and version 1.7 is available as a pre-release.
3. Click on **Assets** to view the download options.
4. Next, click the **ViVeTool.GUI.1.6.2.0.Portable.zip** file (version may change with the new releases) to download the latest version to your local drive.  
![vivetool zip extract folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/vivetool-zip-extract-folder.jpg)
5. Right-click on the **Zip** file and select **Extract** **all**. Select a destination and click **Extract**. Take note of the extraction folder.

1. Next, press the **Win** key and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator.**  
![command prompt vivetool change directory](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/command-prompt-vivetool-change-directory.jpg)
3. In the Command Prompt, change the directory to ViVeTool extracted folder. So, type the following command and press **Enter** to change the directory:  
`cd /d [ViVeToolFolderPath]`
4. For example, if I have the ViVeTool folder saved in C:\\Users\\username\\Downloads\\ViVeTool-v0.3.2, then the full command will look this:  
`cd /d C:\Users\username\Downloads\ViVeTool-v0.3.2`
5. Next, to enable a feature, use the following command and press Enter:  
`ViVeTool.exe /enable /id:featureID`

1. In the above command, replace featureID with the feature ID you want to enable.  
![command prompt vivetool enable feature](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/command-prompt-vivetool-enable-feature.jpg)
2. For example, to enable the tab feature in File Explorer, the feature ID is id:37634385\. So, the full command will look like this:  
`ViVeTool.exe /enable /id:37634385`
3. If you want to disable a feature, then the command will look something like this:  
`ViVeTool.exe /disable /id:featureID`
4. Once the command is executed, type exit and press Enter to close the Command Prompt.
5. Restart your PC to apply the changes. After the PC restarts, the changes should be visible.

## Why Does Enabling a Feature in ViVeTool Not Do Anything?

 You may not be able to enable all the features present in ViVeTool. Almost all the hidden features are OS build-dependent. This means if you enable a feature using ViVeTool, but the changes don’t take effect, it is likely because the feature is not supported by the Windows OS build version you are running.

 In other instances, it may be due to the feature state being set to **Always Disabled** or **Enabled** during compilation. In this instance, even if ViVeTool successfully processes your request, you are unlikely to see any real changes, as the feature is hard-coded to remain on or off.

## ViVeTool's Supported Commands

 Apart from the /enable and /disable command, ViVeTools support a bunch of other commands to reset the custom configuration for specific or all features, update ViVeTool, and export and import custom feature configuration.

| ViVeTool Command | Action                                                       |
| ---------------- | ------------------------------------------------------------ |
| /enable          | Enable a feature                                             |
| /disable         | Disable a feature                                            |
| /query           | Find a list of all the existing features configuration       |
| /reset           | To reset a custom configuration for a specific feature       |
| /resetall        | To reset a custom configuration for all the features         |
| /addsubs         | To add a feature usage subscription                          |
| /delsub          | To remove a feature usage subscription                       |
| /export          | To export custom feature configuration                       |
| /import          | To import custom feature configuration                       |
| /fixlkg          | Fix the current ‘Last Known Good’ rollback system corruption |
| /appupdate       | Look for new ViVeTool updates                                |
| /notifyusage     | Shows a feature notification                                 |

## ViVeTool Brings Hidden Windows Experimental Features to Everyone

 ViVeTool makes it easy to find and test new experimental features before they are released to the public. Whether you use the GUI or command-line version, it lets you easily enable and disable some exciting and annoying features.

 That said, many of these hidden features may be buggy and cause system malfunction. So, keep your system backup handy before you tinker with ViVeTool.

 It allows you to try newer and unreleased features on your stable or developer Windows releases, such as the multi-tab feature in File Explorer or restore the classic Windows 11 context menu. But should you use ViVeTool? Let’s find out!



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/addressing-non-operative-brightness-fn-button-on-windows-11/"><u>Addressing Non-Operative Brightness Fn Button on Windows 11</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-elite-10-survival-skirmishes/"><u>[New] 2024 Approved  Elite 10 Survival Skirmishes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-simple-guide-to-windows-11-home-interface-activation/"><u>A Simple Guide to Windows 11 Home Interface Activation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-solution-manual-windows-rainmeter-problems-decoded/"><u>A Comprehensive Solution Manual: Windows Rainmeter Problems Decoded</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719296093582-restore-your-shift-keys-functionality/"><u>Restore Your Shift Key's Functionality.</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-2023s-top-tweets-the-highest-traffic-watchlist/"><u>2024 Approved  2023'S Top Tweets  The Highest Traffic Watchlist</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-visual-journey-customizing-your-windows-11-monitor-walls/"><u>A Visual Journey: Customizing Your Windows 11 Monitor Walls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-windows-11s-network-settings/"><u>Accessing Windows 11'S Network Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-incorrect-parameter-loaderror-87/"><u>Addressing Incorrect Parameter LoadError 87</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-lunar-client-startup-failures-on-windows-systems/"><u>Addressing “Lunar Client Startup Failures” On Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-simple-guide-to-adjusting-mask-in-windows-11/"><u>A Simple Guide to Adjusting MASK in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-thoroughly-detailed-guide-to-windows-boot-options/"><u>A Thoroughly Detailed Guide to Windows Boot Options</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/updated-2024-approved-7-best-real-time-video-translation-apps/"><u>Updated 2024 Approved 7 Best Real Time Video Translation Apps</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-realme-11-5g-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>How to Unlock Realme 11 5G Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-microsoft-edge-fix-for-w10w11/"><u>Accelerate Your Microsoft Edge: Fix for W10/W11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-cut-trim-and-enhance-youtube-editing-tips-for-the-rookie-for-2024/"><u>[Updated] Cut, Trim & Enhance  YouTube Editing Tips for the Rookie for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719363489312-solving-your-computers-print-command-conundrum-with-effective-tips/"><u>Solving Your Computer's Print Command Conundrum with Effective Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapt-windows-sleep-timer-to-suit-you/"><u>Adapt Window's Sleep Timer to Suit You</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-unlocking-windows-11s-credential-vault/"><u>A Comprehensive Guide to Unlocking Windows 11’S Credential Vault</u></a></li>
<li><a href="https://fake-location.techidaily.com/ispoofer-is-not-working-on-motorola-moto-g-stylus-2023-fixed-drfone-by-drfone-virtual-android/"><u>iSpoofer is not working On Motorola Moto G Stylus (2023)? Fixed | Dr.fone</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-round-lens-photography-a-complete-circuit/"><u>In 2024, Round Lens Photography  A Complete Circuit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-folder-and-file-unity-a-windows-exploration/"><u>Achieving Folder & File Unity: A Windows Exploration</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-music-from-oneplus-11r-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Music from OnePlus 11R to iPod | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-from-ordinary-to-outstanding-unveiling-the-secrets-of-engaging-biographies/"><u>[New] In 2024, From Ordinary to Outstanding  Unveiling the Secrets of Engaging Biographies</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/the-ultimate-checklist-for-professional-youtube-clips-for-2024/"><u>The Ultimate Checklist for Professional YouTube Clips for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-system-called-fails-on-windows-1011/"><u>Addressing System Called Fails on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-method-for-clean-booting-on-windows-11-systems/"><u>A Step-by-Step Method for Clean Booting on Windows 11 Systems</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-navigating-social-networking-videos-your-ultimate-guide-for-appletv-users/"><u>[New] 2024 Approved  Navigating Social Networking Videos  Your Ultimate Guide for AppleTV Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-proactive-steps-to-overcome-no-servers-found-in-apex-legends-(156-chars/"><u>8 Proactive Steps to Overcome 'No Servers Found' In Apex Legends (<156 Chars)</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-capturing-the-moment-methods-for-online-audio-recording/"><u>[New] Capturing the Moment  Methods for Online Audio Recording</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-influencers-utopia-summit/"><u>[Updated] In 2024, Influencers' Utopia Summit</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-cut-your-editing-time-in-half-with-these-20-adobe-premiere-shortcuts/"><u>New 2024 Approved Cut Your Editing Time in Half with These 20 Adobe Premiere Shortcuts</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-simplified-process-updating-user-status-on-discord/"><u>[New] Simplified Process  Updating User Status on Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/address-unsigned-files-issue-for-updated-pcs/"><u>Address 'Unsigned' Files Issue for Updated PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/actions-to-take-when-facing-invalid-name-on-pc/"><u>Actions to Take When Facing Invalid Name on PC</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/n-2024-get-more-from-tiny-screens-top-6-youtube-shorts-downloader-apps/"><u>[New] In 2024, Get More From Tiny Screens  Top 6 YouTube Shorts Downloader Apps</u></a></li>
</ul></div>
