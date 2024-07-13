---
title: "Exploring ViVeTool: Windows' Gateway to New & Emerging Tools"
date: 2024-07-12T17:01:24.241Z
updated: 2024-07-13T17:01:24.241Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Exploring ViVeTool: Windows' Gateway to New & Emerging Tools"
excerpt: "This Article Describes Exploring ViVeTool: Windows' Gateway to New & Emerging Tools"
keywords: ViVeTool Insights,Windows Tool Access,New Tech Explore,Emerging Tools Guide,Gateway To Innovation,ViVeEasy Integration,Advanced Windows Apps
thumbnail: https://thmb.techidaily.com/9be41d62e85e6d9d35faed892e42e95be3740ff6798e8e9db724143c55700cdb.png
---

## Exploring ViVeTool: Windows' Gateway to New & Emerging Tools

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
<li><a href="https://smart-video-creator.techidaily.com/edit-videos-on-your-chromebook-top-free-software-picks-for-2024/"><u>Edit Videos on Your Chromebook Top Free Software Picks for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-realme-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>What is the best Pokemon for pokemon pvp ranking On Realme 12 Pro+ 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-virtual-machine-security-with-vboxs-secure-boot-toggle/"><u>Boost Virtual Machine Security with VBox's Secure Boot Toggle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overhauling-your-operating-systems-state-a-windows-1011-reboot-guide/"><u>Overhauling Your Operating System's State: A Windows 10/11 Reboot Guide</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-crafting-gentle-volume-declines-using-logic-pro/"><u>2024 Approved  Crafting Gentle Volume Declines Using Logic Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathing-life-into-your-inactive-windows-11-wi-fi-hotspot/"><u>Breathing Life Into Your Inactive Windows 11 Wi-Fi Hotspot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-windows-11-key-combinations-for-screenshot-taking/"><u>Discover Windows 11 Key Combinations for Screenshot Taking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rushing-past-stuck-warcraft-64-patches/"><u>Rushing Past Stuck Warcraft 6.4 Patches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-disparities-in-cloud-and-offline-windows-updates/"><u>Exploring Disparities in Cloud and Offline Windows Updates</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-building-captivating-visual-puzzles-a-mosaic-journey/"><u>In 2024, Building Captivating Visual Puzzles  A Mosaic Journey</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-not-empty-assertion-a-practical-guide-to-x80070091-fixes/"><u>Disabling 'Not Empty' Assertion: A Practical Guide to X80070091 Fixes</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/024-approved-a-comprehensive-look-editing-and-polishing-yt-videos-via-movie-maker/"><u>[New] 2024 Approved  A Comprehensive Look  Editing and Polishing YT Videos via Movie Maker</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-prevent-windowed-app-relocations/"><u>Methods to Prevent Windowed App Relocations</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-how-to-proficiently-use-a-switch-pro-controller-on-steam/"><u>[Updated] How to Proficiently Use a Switch Pro Controller on Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/circumventing-the-failed-to-launch-lunar-client-windows-message/"><u>Circumventing the Failed to Launch: Lunar Client Windows Message</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/effortlessly-capture-and-archive-your-favorite-fb-story-moments/"><u>Effortlessly Capture and Archive Your Favorite FB Story Moments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-pc-storage-identifying-excess-disk-usage-in-windows/"><u>Maximizing PC Storage: Identifying Excess Disk Usage in Windows</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-pro-editors-manual-tackling-gopro-distortion/"><u>2024 Approved  Pro Editor's Manual  Tackling GoPro Distortion</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/process-of-screen-sharing-oppo-a78-to-pc-detailed-steps-drfone-by-drfone-android/"><u>Process of Screen Sharing Oppo A78 to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-best-software-utilities-for-altering-audio-frequencies/"><u>New Best Software Utilities for Altering Audio Frequencies</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-ideal-5-safe-platforms-for-remote-work-in-startups-for-2024/"><u>[Updated] Ideal 5 Safe Platforms for Remote Work in Startups for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-unreachable-network-paths/"><u>Overcoming Windows' Unreachable Network Paths</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-overcoming-the-crashes-in-windows-11s-photos-application/"><u>[Updated] Overcoming the Crashes in Windows 11'S Photos Application</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-win11s-security-measures-through-rufus-mastery/"><u>Overcoming Win11's Security Measures Through Rufus Mastery</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-navigating-new-horizons-a-tech-upgrade-blueprint/"><u>[Updated] Navigating New Horizons  A Tech Upgrade Blueprint</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reactivate-an-inactive-windows-11-license/"><u>How to Reactivate an Inactive Windows 11 License</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/mastering-facebooks-live-features-for-optimal-performance/"><u>Mastering Facebook's Live Features for Optimal Performance</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-insta-personality-showcase-100-crafted-caption-ideas/"><u>[New] 2024 Approved  Insta Personality Showcase - 100 Crafted Caption Ideas</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safe-stepping-stones-on-windows-11-top-8-to-skip/"><u>Safe Stepping Stones on Windows 11: Top 8 To Skip</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-to-rectify-cant-add-your-folder-now-in-onedrive/"><u>Essential Steps to Rectify 'Can't Add Your Folder Now' In OneDrive</u></a></li>
<li><a href="https://extra-resources.techidaily.com/affordable-text-animation-strategies-webreal-world/"><u>Affordable Text Animation Strategies  Web/Real World</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-nvidia-connect-error-in-windows-oses/"><u>Overcoming NVIDIA Connect Error in Windows OSes</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-mastering-the-art-of-snapchat-sponsored-content-for-2024/"><u>[Updated] Mastering the Art of Snapchat Sponsored Content for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-actions-and-activation-labels-in-dev-tools/"><u>Exploring Actions & Activation Labels in Dev Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-tackle-the-windows-exception-breaking-point-issue/"><u>How to Tackle the Windows Exception Breaking Point Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-keygen-malware-on-windows-recognition-and-eradication-steps/"><u>Identifying Keygen Malware on Windows: Recognition and Eradication Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/determine-disk-technology-in-windows-1011/"><u>Determine Disk Technology in Windows 10/11</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-ditch-the-search-get-filmora-discounts-without-reddit/"><u>New 2024 Approved Ditch the Search Get Filmora Discounts Without Reddit</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-top-rated-aiff-conversion-tools-a-comprehensive-review/"><u>New In 2024, Top-Rated AIFF Conversion Tools A Comprehensive Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-11-mail-tips-for-resolving-html-code-displays-in-emails/"><u>Fixing Windows 11 Mail: Tips for Resolving HTML Code Displays in Emails</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-your-windows-11-experience-with-nircmd-tips/"><u>Command Your Windows 11 Experience with NirCmd Tips</u></a></li>
<li><a href="https://techidaily.com/recover-apple-iphone-12-mini-data-from-itunes-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover Apple iPhone 12 mini Data From iTunes | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/changing-windows-security-pin-made-simple/"><u>Changing Windows Security PIN Made Simple</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-swiftly-clear-windows-cached-data/"><u>How to Swiftly Clear Windows' Cached Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoidance-tactics-removing-onedrive-in-file-explorer-window/"><u>Avoidance Tactics: Removing OneDrive in File Explorer Window</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-2024-approved-real-time-streaming-methods-for-facebook-video-uploads/"><u>[Updated] 2024 Approved  Real-Time Streaming Methods for Facebook Video Uploads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-the-task-of-installing-gmaps-on-windows/"><u>Conquering the Task of Installing GMaps on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrate-compatibility-troubleshoot-in-windows-clippy/"><u>Integrate Compatibility Troubleshoot in Windows Clippy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectify-restore-responsive-shortcut-keys-in-windows-11/"><u>Rectify: Restore Responsive Shortcut Keys in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/introducing-ad-free-innovation-windows-11s-modernized-start/"><u>Introducing Ad-Free Innovation: Windows 11'S Modernized Start</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-wi-fi-setup-woes-reconciling-missing-steps-in-prompts/"><u>Navigating Wi-Fi Setup Woes: Reconciling Missing Steps in Prompts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-privilege-needed-blue-screen-windows-fix-guide/"><u>Bypassing 'Privilege Needed' Blue Screen: Windows Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-winscomrssvsvc-error-on-initial-startup/"><u>Mitigating WinscomrssvSvc Error on Initial Startup</u></a></li>
</ul></div>
