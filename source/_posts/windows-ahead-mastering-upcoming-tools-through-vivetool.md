---
title: "Windows Ahead: Mastering Upcoming Tools Through ViVeTool"
date: 2024-07-12T16:59:02.257Z
updated: 2024-07-13T16:59:02.257Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Ahead: Mastering Upcoming Tools Through ViVeTool"
excerpt: "This Article Describes Windows Ahead: Mastering Upcoming Tools Through ViVeTool"
keywords: Windows Future Tips,Upcoming Tech Windows,Master ViVeTools,ViVeTool Guide,Learning Windows Tools,Advanced Windows Utilities,Tech Tools for Windows Users
thumbnail: https://thmb.techidaily.com/91d802feac954d9a2b7218b9de82c000f339447018e6cb53073b6a41a90f92e5.jpg
---

## Windows Ahead: Mastering Upcoming Tools Through ViVeTool

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
<li><a href="https://unlock-android.techidaily.com/in-2024-forgotten-the-voicemail-password-of-itel-p55-5g-try-these-fixes-by-drfone-android/"><u>In 2024, Forgotten The Voicemail Password Of Itel P55 5G? Try These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/documentation-skills-snapping-windows-uac-prompts/"><u>Documentation Skills: Snapping Windows UAC Prompts</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-ace-your-gift-shopping-the-ultimate-guide-to-selecting-specialty-stores/"><u>[New] Ace Your Gift Shopping  The Ultimate Guide to Selecting Specialty Stores</u></a></li>
<li><a href="https://win11-tips.techidaily.com/circuit-breakers-fixes-to-power-up-your-photoshop/"><u>Circuit Breakers: Fixes to Power Up Your PhotoShop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-audacitys-error-while-opening-sound-device-issue-in-windows-11-and-11/"><u>How to Fix Audacity’s “Error While Opening Sound Device” Issue in Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-editing-tasks-with-powertoys-text-tools/"><u>Simplify Editing Tasks with PowerToys' Text Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosted-efficiency-expert-tips-for-optimizing-bar-use/"><u>Boosted Efficiency: Expert Tips for Optimizing Bar Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-sizing-down-software-on-windows-11/"><u>Mastering the Art of Sizing Down Software on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/standardizing-your-windows-system-backups/"><u>Standardizing Your Windows System Backups</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-battlefront-bastion-100plus-epic-game-battles/"><u>[Updated] In 2024, Battlefront Bastion  100+ Epic Game Battles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-start-system-file-verification-with-sfc/"><u>How to Start System File Verification with SFC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expedite-word-clarity-with-windows-11-help/"><u>Expedite Word Clarity with Windows 11 Help</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-an-efficient-windows-menu-for-software-alerts/"><u>Crafting an Efficient Windows Menu for Software Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-to-reactivate-googles-nearby-share-app/"><u>Essential Tips to Reactivate Google's Nearby Share App</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-mastering-instagram-boosting-post-engagement-strategies/"><u>[New] In 2024, Mastering Instagram  Boosting Post Engagement Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-elevate-taskmanager-with-a-new-cli-tab-windows-11/"><u>How to Elevate TaskManager with a New CLI Tab (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resuscitating-silent-windows-headset-mic/"><u>Resuscitating Silent Windows Headset Mic</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimalist-workstations-with-windows-os/"><u>Minimalist Workstations with Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/locating-and-opening-system32-windows-11/"><u>Locating and Opening System32 (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silence-windows-aggressive-contrast-mode/"><u>Silence Windows' Aggressive Contrast Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-dll-not-loading-error-in-windows-steam-client/"><u>Fixing Dll Not Loading Error in Windows Steam Client</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-edge-access-control-constructing-your-windows-personal-pins/"><u>Cutting-Edge Access Control: Constructing Your Windows Personal Pins</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-a-prism-of-design-from-theory-to-practice/"><u>[Updated] A Prism of Design  From Theory to Practice</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-memory-limitation-indicators-on-windowsvmware-systems/"><u>Correcting Memory Limitation Indicators on Windows/VMware Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-the-amd-installer-crash-in-windows/"><u>Quick Fixes for the AMD Installer Crash in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-recover-nvidia-configurations-on-windows-os/"><u>How to Recover NVIDIA Configurations on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-device-tracking-with-windows-live-tiles/"><u>Mastering Device Tracking with Windows Live Tiles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-update-issue-error-code-0x80073712/"><u>Resolving Windows Update Issue: Error Code 0X80073712</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-successful-java-setup-in-windows/"><u>Strategies for Successful Java Setup in Windows</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-how-to-create-video-contents-that-convert-sales/"><u>Updated 2024 Approved How to Create Video Contents That Convert Sales</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-video-editing-for-mac-avs-editor-solution-for-2024/"><u>New Video Editing for Mac AVS Editor Solution for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-linux-with-windows-tools/"><u>Enhancing Linux with Windows Tools</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-2024-approved-the-ultimate-list-of-leading-pitch-shifting-tools-to-explore/"><u>New 2024 Approved The Ultimate List of Leading Pitch-Shifting Tools to Explore</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quickly-manipulate-text-illumination-in-windows-11/"><u>Quickly Manipulate Text Illumination in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-rectifying-error-0x80300024-in-winxp/"><u>Steps for Rectifying Error 0X80300024 in WinXP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instructions-disable-virtual-machine-feature-in-windows-11/"><u>Instructions: Disable Virtual Machine Feature in Windows 11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-investigating-spotlighted-comments-online/"><u>[New] Investigating Spotlighted Comments Online</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-how-to-screen-capture-snapchat-stories-effectively/"><u>In 2024, How to Screen Capture Snapchat Stories Effectively</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-professional-gaming-intro-designers-you-can-trust-for-2024/"><u>New Professional Gaming Intro Designers You Can Trust for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-identify-non-recognized-usb-devices-on-win-11/"><u>Steps to Identify Non-Recognized USB Devices on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-for-clearing-false-device-error-on-pcs/"><u>Expert Guide for Clearing False Device Error on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/implementing-windows-11s-revamped-widget-interface/"><u>Implementing Windows 11'S Revamped Widget Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/spotlight-on-7-irksome-windows-11-aesthetics/"><u>Spotlight on 7 Irksome Windows 11 Aesthetics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-windows-hello-for-secure-user-access/"><u>Enabling Windows Hello for Secure User Access</u></a></li>
<li><a href="https://some-approaches.techidaily.com/superior-solutions-top-bdr-softwares-for-windows-macos-for-2024/"><u>Superior Solutions  Top BDR Softwares for Windows, macOS for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-missing-msvcrt120dll-on-your-computer/"><u>Overcoming Missing Msvcrt120dll on Your Computer</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-leading-with-visuals-setting-up-premium-cover-videos-on-fb-for-2024/"><u>[Updated] Leading With Visuals  Setting Up Premium Cover Videos on FB for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automate-mass-rename-with-powertoys/"><u>Automate Mass Rename with PowerToys</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-innovative-artists-guide-to-best-free-3d-psds/"><u>[New] 2024 Approved  Innovative Artists' Guide to Best Free 3D PSDs</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-xiaomi-redmi-12-5gmirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can Xiaomi Redmi 12 5GMirror Share to PC? | Dr.fone</u></a></li>
</ul></div>
