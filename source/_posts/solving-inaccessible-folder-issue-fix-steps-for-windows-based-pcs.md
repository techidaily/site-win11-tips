---
title: "Solving 'Inaccessible Folder' Issue: Fix Steps for Windows-Based PCs"
date: 2024-06-25T16:25:09.013Z
updated: 2024-06-26T16:25:09.013Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Solving 'Inaccessible Folder' Issue: Fix Steps for Windows-Based PCs"
excerpt: "This Article Describes Solving 'Inaccessible Folder' Issue: Fix Steps for Windows-Based PCs"
keywords: Fix Inaccessible Folder,Overcome Folder Error,Resolve Folder Access,Windows Folder Fixes,Solve File Permission Issue,Fix Windows Folder Problem,Rectify PC Directory Errors
thumbnail: https://thmb.techidaily.com/8404aae8332517e90ea13209ccbcb49d56b9cbe41228f9bbeee698b42d6caf34.jpg
---

## Solving 'Inaccessible Folder' Issue: Fix Steps for Windows-Based PCs

 Do you encounter the error "the set of folders cannot be opened" when launching Outlook? The leading cause behind this error is the interference from Outlook add-ins. Other possible causes include issues with your email profile, corruption of your Outlook profile, or corrupted OST and data files.

 Likewise, using an incompatible version of Outlook or the same email address in multiple mail apps may also result in an error. Here are some fixes you should apply to resolve the issue.

## 1\. Perform Some Preliminary Checks

 Before moving on to any serious troubleshooting, perform the following preliminary checks first, as they may resolve the error right away:

* Close other open email clients, especially the Mail app that comes built into Windows.
* Run Outlook as administrator. Right-click on the Outlook client and hit **Run as administrator**.  
![Run Outlook as an Administrator in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/1-run-outlook-as-an-administrator-in-windows.jpg)
* Ensure you have the compatible version of Outlook (**x32** or **x64**) installed on your device.
* Update or repair Outlook to ensure a corrupt or outdated installation has not caused the error.

 If the basic checks and fixes do not resolve the error, it's time to move on to serious troubleshooting.

## 2\. Check for Add-In Interference

 The add-in interference is the leading cause of Outlook not launching and presenting the "the set of folders cannot be opened" error, as reported by numerous users on various online forums. Running Outlook in Safe mode is the best way to confirm that since it launches the app without add-ins and other elements.

 Press **Win + R,** type **"Outlook.exe /safe"** and hit **Enter** to launch Outlook in safe mode.

![Run Outlook in Safe Mode by Running a Command in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/2-run-outlook-in-safe-mode-by-running-a-command-in-windows.jpg)

 If the app launches without an error, the add-in interference must have been the culprit. Therefore, stay in safe mode and turn off any interfering add-ins. Here's how:

1. Go to the **File** tab and select **Options**.  
![Select Options in the File Tab of Outlook](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/3-select-options-in-the-file-tab-of-outlook.jpg)
2. Go to the **Add-ins** tab in the left menu.
3. Select **"COM Add-ins"** from the **Manage** menu, then click **Go**.  
![Click on the Go Button After Selecting the COM Add-ins Option From the Manage Dropdown Menu in Outlook](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/4-click-on-the-go-button-after-selecting-the-com-add-ins-option-from-the-manage-dropdown-menu-in-outlook.jpg)
4. Uncheck the boxes behind any add-ins you don't need and disable them.

## 3\. Check for Issues With the OST File

 The mislocated OST file or its corruption can also lead to the error. Therefore, ensure the file is at its original location and recreate it to eliminate the possibility of file corruption. Here's how:

1. Open the Control Panel.
2. Click on the **View by** dropdown menu and select **Large icons**.
3. Go to **Mail (Microsoft Outlook)**.  
![Go to Mail Option in the Windows Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/5-go-to-mail-option-in-the-windows-control-panel.jpg)
4. Click the **Data Files...** button.
5. Select the OST file location and click **Open File Location...**  
![Click the Open File Location Button After Selecting the OST File in the Data Files Tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/6-click-the-open-file-location-button-after-selecting-the-ost-file-in-the-data-files-tab.jpg)
6. Right-click the file in the **File Explorer** and select **Properties**. If the file type is **OST**, the file is in the right place, and no action is needed.  
![Ensure the File Type Is OST by Going to Properties in the Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/7-ensure-the-file-type-is-ost-by-going-to-properties-in-the-windows-file-explorer.jpg)

 To ensure that the OST file is not corrupt, copy it to a safe location outside the Outlook installation folder. Then, right-click and delete the main OST file.

 After that, restart Outlook, and it will automatically recreate the OST file and download the data from the Exchange Server. If you decide to go this route, remain connected to the internet.

## 4\. Check for Issues With Your Outlook Profile

 Outlook uses the Outlook profile to store information about your email accounts, data files, and other client settings. Profile corruption can prevent Outlook from loading the necessary data at launch and can present the "set of folders cannot be opened" error. To rule out profile corruption as the cause of the problem, follow these steps:

1. Open the Control Panel.
2. Click on the **View by** dropdown menu and select **Large icons**.
3. Go to **Mail (Microsoft Outlook)**.
4. Click the **Show Profiles** button.
5. Click on the **Add** button.  
![Click on the Add Button in the Show Profiles Menu in Mail Microsoft Outlook Settings in the Windows Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/8-click-on-the-add-button-in-the-show-profiles-menu-in-mail-microsoft-outlook-settings-in-the-windows-control-panel.jpg)
6. Follow the instructions on the screen to create your new profile.
7. Launch a new Outlook profile.

 If Outlook launches successfully, a corrupt profile could be to blame. So, continue to use the new profile after adding your account. If switching profiles does not help, go to the next step.

## 5\. Look for Issues With the Navigation Pane

 Misconfigured navigation pane settings or corrupted XML files, which store the navigation pane settings, can also prevent Outlook from opening and presenting the error. To eliminate this possibility, you should reset the navigation pane in Outlook that will reset the configuration to its default settings. Press **Win + R**, type **"outlook.exe /resetnavpane"** and hit **Enter**.

![Run a Command to Reset the Navigation Pane in Outlook](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/9-run-a-command-to-reset-the-navigation-pane-in-outlook.jpg)

 After that, relaunch Outlook. If resetting the navigation pane doesn't work, you should delete the XML file manually. To do this, press **Win + R**, type **"%localappdata%\\Microsoft\\Outlook"** and hit **Enter**. After that, delete any XML files you find in this folder.

 Then, restart Outlook from scratch, and it will recreate the XML file with default settings. There's a good chance that it will resolve the issue.

## 6\. Repair the Outlook PST Files

 PST files store data about contacts, calendars, events, and messages. If the error window indicates that Outlook could not open the PST file, then the file could be corrupt, which could be why Outlook presents the error. Therefore, you can fix it by repairing the files. To repair the corrupted data files, follow the below steps:

1. Navigate to the Outlook installation folder, which is located here by default:  
`C:\Program Files\Microsoft Office\root\Office16`
2. Locate the **ScanPST.exe** file and run it.
3. Click **Browse**, paste the path from the error window into the **Inbox Repair** tool, and click Start.  
![Click Start After Pasting the Path From the Error Window into the Inbox Repair Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/10-click-start-after-pasting-the-path-from-the-error-window-into-the-inbox-repair-tool.jpg)
4. Then, click the **Repair** button to complete the repair.

 If you can't locate the Outlook folder in the path mentioned above, see our [guide on repairing the PST file](https://www.makeuseof.com/repair-pst-without-scanpst/) for the exact path.

## 7\. Run the Microsoft Support and Recovery Assistant

 If none of the above fixes resolves the error, run the Microsoft Support and Recovery Assistant, Microsoft's recommended tool for fixing issues with Microsoft Office products.

 Here's how to download and use the tool:

1. Download **Microsoft Support and Recovery Assistant** from the [Microsoft website](https://www.microsoft.com/en-US/download/details.aspx?id=100607).
2. Unzip the file you just downloaded.
3. Run the **SaraSetup** file to install the software.
4. Upon installation, launch the tool and click the **"I agree"** button.
5. Select **Outlook** from the list of applications and click **Next**.  
![Click Next After Selecting Outlook From the List of Apps in the Microsoft Support and Recovery Assistant Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/11-click-next-after-selecting-outlook-from-the-list-of-apps-in-the-microsoft-support-and-recovery-assistant-window.jpg)
6. Then, follow the on-screen instructions to carry out the repair.

 If any underlying problem with the Outlook client contributed to this issue, running this tool will most likely resolve the issue.

## Run Outlook on Windows Without a Hitch

 Running into irritating errors when launching the Outlook client can hinder our productivity. Hopefully, you now better understand what causes the "the set of folders cannot be opened" error. In addition, by carefully applying the fixes listed above, you should be able to fix the error and launch Outlook successfully.

 Likewise, using an incompatible version of Outlook or the same email address in multiple mail apps may also result in an error. Here are some fixes you should apply to resolve the issue.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/boost-your-typing-pace-in-windows-11-overcome-keyboard-latency/"><u>Boost Your Typing Pace in Windows 11: Overcome Keyboard Latency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-and-utilizing-widgets-in-windows-11/"><u>Accessing and Utilizing Widgets in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-windows-key-activationdeactivation-process/"><u>Simplifying Windows Key Activation/Deactivation Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regenerating-system-icons-in-windows-os/"><u>Regenerating System Icons in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-minecraft-glitches-with-these-fixes/"><u>Stop Minecraft Glitches with These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sticky-notes-strategies-for-sustained-top-level-visibility-on-win-os/"><u>Sticky Notes Strategies for Sustained Top-Level Visibility on Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719237818540-trouble-with-compatibility-try-these-straightforward-fixes-now/"><u>Trouble with Compatibility? Try These Straightforward Fixes Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jump-back-to-joy-playing-classics-on-dosbox-x/"><u>Jump Back to Joy: Playing Classics on DOSBox-X</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-2024-approved-essential-underrated-free-speech-to-text-apps-for-mac/"><u>[New] 2024 Approved  Essential, Underrated, Free Speech-to-Text Apps for Mac</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-top-5-winter-scenes-to-enhance-your-video-warmth/"><u>2024 Approved  Top 5 Winter Scenes to Enhance Your Video Warmth</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-tecno-camon-20-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Tecno Camon 20? | Dr.fone</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-10-best-intro-maker-software-for-gamers-on-windows-and-mac-free-and-paid-for-2024/"><u>Updated 10 Best Intro Maker Software for Gamers on Windows and Mac Free & Paid for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-how-to-create-a-sports-highlight-video/"><u>[Updated] 2024 Approved  How to Create a Sports Highlight Video</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-amplify-earnings-monetize-youtube-on-the-go-with-effective-techniques/"><u>[New] 2024 Approved  Amplify Earnings  Monetize YouTube on the Go with Effective Techniques</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/eliminating-suggested-podcast-selections-on-spotify/"><u>Eliminating Suggested Podcast Selections on Spotify</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-samsung-galaxy-f54-5g-to-pc-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Samsung Galaxy F54 5G to PC? | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-the-ultimate-guide-to-saving-your-iphone-7-display/"><u>[Updated] The Ultimate Guide to Saving Your iPhone 7 Display</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>