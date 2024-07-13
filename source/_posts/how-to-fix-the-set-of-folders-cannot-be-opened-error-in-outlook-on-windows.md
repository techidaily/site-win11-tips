---
title: How to Fix “The Set of Folders Cannot Be Opened” Error in Outlook on Windows
date: 2024-07-12T17:44:22.550Z
updated: 2024-07-13T17:44:22.550Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix “The Set of Folders Cannot Be Opened” Error in Outlook on Windows
excerpt: This Article Describes How to Fix “The Set of Folders Cannot Be Opened” Error in Outlook on Windows
keywords: Outlook Folder Access Issue,Solve Outlook Folder Error,Fixing Outlook Unsupported Files,Overcome Folder Open Not Possible Error,Troubleshoot Windows Outlook Folder,Resolve Outlook Folders Closed Error,Stop Folders Cannot Be Accessed In Outlook
thumbnail: https://thmb.techidaily.com/3e844b75dba05d50e037a8922f63f44130183016b1138a00c38fe8d101f4bd1f.jpg
---

## How to Fix “The Set of Folders Cannot Be Opened” Error in Outlook on Windows

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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-error-code-0x80070091-empty-directories-unveiled/"><u>Tackling Windows Error Code 0X80070091 - Empty Directories Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-no-write-error-a-guide-for-windows-users/"><u>Tackling the No Write Error: A Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-tackling-steam-disk-errors/"><u>Understanding and Tackling Steam Disk Errors</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-step-by-step-guide-to-instagram-livestreaming-using-obs/"><u>[New] In 2024, Step-by-Step Guide to Instagram Livestreaming Using OBS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrading-graphic-memory-in-windows-11-systems/"><u>Upgrading Graphic Memory in Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-vlc-unrecognized-media-issue/"><u>Overcoming Windows VLC Unrecognized Media Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-fix-the-sorry-there-is-a-problem-with-the-onedrive-servers-error-on-windows/"><u>6 Ways to Fix the “Sorry, There Is a Problem With the OneDrive Servers” Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-microsoft-store-error-x80072f30-in-windows/"><u>Resolving Microsoft Store Error X80072F30 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-the-battle-against-freezes-in-apex-legends/"><u>Winning the Battle Against Freezes in Apex Legends</u></a></li>
<li><a href="https://extra-hints.techidaily.com/comprehensive-finance-analysis-launching-a-podcasts-cost-for-2024/"><u>Comprehensive Finance Analysis  Launching a Podcast's Cost for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unison-vs-phone-link-for-windows-phone-users-explored/"><u>Unison Vs. Phone Link for Windows Phone Users Explored</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-the-endless-cycle-of-windows-ui-issues/"><u>Stop the Endless Cycle of Windows UI Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-altering-window-icons-distance-on-11plus-windows/"><u>Title: Altering Window Icons' Distance on 11+ Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-missing-data-from-windows-1011s-search-feature/"><u>Restoring Missing Data From Windows 10/11'S Search Feature</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-enable-usb-debugging-on-a-locked-oppo-reno-10-pro-5g-phone-by-drfone-android/"><u>How To Enable USB Debugging on a Locked Oppo Reno 10 Pro 5G Phone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-how-to-improve-youtube-video-quality-and-clarity/"><u>[New] How to Improve YouTube Video Quality and Clarity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-hidden-perils-behind-budget-windows-activation-codes/"><u>The Hidden Perils Behind Budget Windows Activation Codes</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/amazons-favorite-originals-twitter-top-picks-for-2024/"><u>Amazon's Favorite Originals - Twitter Top Picks for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-correcting-file-errors-in-windows-11/"><u>Steps to Correcting File Errors in Windows 11</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-from-raw-to-refined-tailoring-youtube-videos-with-premiere-pro/"><u>[New] In 2024, From Raw to Refined  Tailoring YouTube Videos with Premiere Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-default-sound-level-configurations-in-windows/"><u>Restoring Default Sound Level Configurations in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-shortage-of-physical-storage-space-vm-errors/"><u>Resolving Shortage of Physical Storage Space (VM) Errors</u></a></li>
<li><a href="https://audio-editing.techidaily.com/discovering-top-10-budget-friendly-online-digital-audio-workstations-daws/"><u>Discovering Top 10 Budget-Friendly Online Digital Audio Workstations (DAWs)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-how-to-use-filters-on-instagram-in-2024/"><u>[Updated] How to Use Filters on Instagram, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-things-to-try-when-prime-videos-subtitles-arent-working-on-windows-11/"><u>4 Things to Try When Prime Video's Subtitles Aren't Working on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-guide-to-instant-uninstalling-via-windows-shortcuts/"><u>The Guide to Instant Uninstalling via Windows Shortcuts</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-the-next-big-thing-in-short-form-videos-wholl-take-the-lead-likes-or-tiktok-for-2024/"><u>[Updated] The Next Big Thing in Short Form Videos  Who'll Take the Lead, Likes or TikTok for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-mastering-your-voice-on-the-fly-a-look-at-the-best-6-apps-for-instant-modification/"><u>Updated 2024 Approved Mastering Your Voice on the Fly A Look at the Best 6 Apps for Instant Modification</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-excellent-gopro-video-processing-systems-for-2024/"><u>[New] Excellent GoPro Video Processing Systems for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-surface-computer-firmware-update-manual/"><u>The Ultimate Surface Computer Firmware Update Manual</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-unveil-the-leading-10-hidden-story-viewers/"><u>In 2024, Unveil the Leading 10 Hidden Story Viewers</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-transforming-images-with-ar-a-guide-to-free-lut-downloads/"><u>2024 Approved  Transforming Images with AR  A Guide to Free LUT Downloads</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/exclusive-no-cost-premiere-pro-resource-pack-for-2024/"><u>Exclusive, No-Cost Premiere Pro Resource Pack for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-fine-tuning-frequency-flux-innovative-approaches-to-minimize-noise-in-audacity-for-2024/"><u>New Fine-Tuning Frequency Flux Innovative Approaches to Minimize Noise in Audacity for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/perfect-your-content-with-top-tier-title-tactics/"><u>Perfect Your Content with Top-Tier Title Tactics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-explorer-onedrive-as-a-launchpad/"><u>Mastering File Explorer: OneDrive as a Launchpad</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-feature-a-podcast-in-one-quick-snap-for-2024/"><u>[New] Feature a Podcast in One Quick Snap for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-5-best-pc-optimization-tools-on-a-windows-pc/"><u>The 5 Best PC Optimization Tools on a Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-functionality-of-windows-photo-viewer-in-win11/"><u>Restoring Functionality of Windows Photo Viewer in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/workflow-enhancer-integrating-sticky-notes-into-your-windows-morning-ritual/"><u>Workflow Enhancer: Integrating Sticky Notes Into Your Windows Morning Ritual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-identity-under-threat-are-biometrics-safe/"><u>Windows Identity Under Threat: Are Biometrics Safe?</u></a></li>
<li><a href="https://extra-tips.techidaily.com/exploring-affordable-cloud-storage-solutions/"><u>Exploring Affordable Cloud Storage Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-text-selection-in-windows-compatible-pdfs/"><u>Mastering Text Selection in Windows-Compatible PDFs</u></a></li>
<li><a href="https://location-fake.techidaily.com/6-ways-to-change-spotify-location-on-your-honor-90-pro-drfone-by-drfone-virtual-android/"><u>6 Ways to Change Spotify Location On Your Honor 90 Pro | Dr.fone</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-2024-approved-best-tricks-for-learning-photo-slideshow/"><u>New 2024 Approved Best Tricks for Learning Photo Slideshow</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-wrinkle-free-up-operator-installation/"><u>Windows Wrinkle? Free Up Operator Installation</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-from-memory-to-moments-securely-uploading-photos-to-snapchat/"><u>2024 Approved  From Memory to Moments  Securely Uploading Photos to Snapchat</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-stop-automated-post-proposals-on-instagram/"><u>[New] 2024 Approved  Stop Automated Post Proposals on Instagram</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-directdraw-crashes-in-win11-a-step-by-step-guide/"><u>Solving DirectDraw Crashes in Win11: A Step-by-Step Guide</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/disable-screen-lock-on-tecno-by-drfone-android-unlock-android-unlock/"><u>Disable screen lock on Tecno</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbo-charging-windows-printer-performance/"><u>Turbo-Charging WIndows Printer Performance</u></a></li>
<li><a href="https://review-topics.techidaily.com/quickly-remove-google-frp-lock-on-samsung-galaxy-s24plus-by-drfone-android-unlock-remove-google-frp/"><u>Quickly Remove Google FRP Lock on Samsung Galaxy S24+</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-bypassing-ssi-and-installing-unverified-drivers/"><u>Mastering Windows: Bypassing SSI & Installing Unverified Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-persistent-microsoft-edge-shortcuts/"><u>Preventing Persistent Microsoft Edge Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mystery-of-runtime-brokers-in-computing/"><u>Unraveling the Mystery of Runtime Brokers in Computing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-popular-rainmeter-problems-in-windows-systems/"><u>Troubleshooting Popular Rainmeter Problems in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-aid-unlocking-essential-assistive-tech/"><u>Windows Aid: Unlocking Essential Assistive Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-route-to-your-windows-disk-space-win-1011/"><u>Quick Route to Your Windows Disk Space (Win 10/11)</u></a></li>
</ul></div>
