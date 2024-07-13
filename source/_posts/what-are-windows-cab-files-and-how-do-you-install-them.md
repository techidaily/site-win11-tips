---
title: What Are Windows CAB Files and How Do You Install Them?
date: 2024-07-12T17:04:17.701Z
updated: 2024-07-13T17:04:17.701Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes What Are Windows CAB Files and How Do You Install Them?
excerpt: This Article Describes What Are Windows CAB Files and How Do You Install Them?
keywords: WinCAB Files Basics,Installing CAB on WIN,CAB File Usage Guide,Windows Software Installation,How to Install CAB Files,Understanding CAB Archives,CAB File Format in Windows
thumbnail: https://thmb.techidaily.com/0c231e30e1cde65144bf91e6e96a309bb581e79a51b0603eaf2331d2401d5ca6.jpg
---

## What Are Windows CAB Files and How Do You Install Them?

 There are many ways to download driver and Windows updates, one of which is by visiting the Microsoft Update Catalog. The files downloaded from the Microsoft Update Catalog have a .CAB extension. Microsoft uses these files because they use lossless compression, which means that the original files remain unchanged when they are compressed.

 But what exactly is a Windows CAB file, and how do you install it on your computer? Here's everything you need to know.

## What Is a Windows CAB File?

 A CAB file or Cabinet file is a common archive file format used by Microsoft. It contains the compressed version of different files, folders, and even other cabinet files. Microsoft uses these files to distribute Windows, drivers, and UWP app updates. However, you can also use it to store other forms of data, such as images, videos, and documents.

 A CAB file is compressed using the Microsoft Cabinets Compression Format (MCF), which ensures that you can easily decompress it without losing the data stored in it. It can also be signed with digital certificates, allowing to maintain the authenticity and integrity of the file.

 CAB files are recognized by their first four bytes, which are the [ASCII characters](https://www.makeuseof.com/what-is-ascii-text/) MSCF. You can store up to 65,535 folders in a CAB file, with each folder having a storage capacity of 65,535 files.

 Now that you have a brief understanding of CAB files, let's check out how you can install it on Windows 11\.

## How to Install a CAB File on Windows 11

 You can easily install a CAB file on Windows 11 using Command Prompt and Windows PowerShell. In the Command Prompt method, you'll have to use the [DISM command](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/). Whereas, in the PowerShell method, you'll use the Add-WindowsPackage command.

 Here's how to install a CAB file using Command Prompt.

1. Navigate to the CAB file location on your computer.
2. Right-click the CAB file, and choose **Copy as path**.  
![Copy as path option in context menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/copy-as-path-option.jpg)
3. Press **Win** key to open the **Start Menu**, type **Command Prompt** in the search bar, and choose **Run as administrator** from the right pane.
4. In the elevated Command Prompt window, type the following command and press Enter. Make sure to replace "**CAB location**" with the copied path.  
`dism /Online /Add-Package /PackagePath:"CAB location"`  
![CMD window with command to install a CAB file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/cmd-window.jpg)

 Once the installation is complete, [restart your computer](https://www.makeuseof.com/windows-restart-methods/) to see the changes.

 If you want to install a CAB file using Windows PowerShell, follow these instructions:

1. Open the Start Menu, type **Windows PowerShell**, and choose **Run as administrator** from the right pane.
2. Type the following command and press Enter. Make sure to replace "**CAB location**" with the copied path.  
`Add-WindowsPackage -Online -PackagePath "CAB location"  
`  
![Powershell window with command to install a CAB file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/powershell-window.jpg)

 That's it. PowerShell will install the content of the CAB file on your computer.

## How to Install Driver Updates From a CAB File

 If you have downloaded a driver update, which is a CAB file, you can install it using the following instructions:

1. Double-click the CAB file to view its contents.
2. Press **Ctrl + A** to select all the files, right-click, and choose **Extract**.  
![Extract option in context menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/extract-option.jpg)
3. Choose the location where you want to extract the contents of the CAB file and click **Extract**.
4. Press **Win + X** hotkey to open the Power User menu and choose **Device Manager**.
5. Right-click the device for which you have downloaded the driver update and choose **Update driver**.  
![Update driver option in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/update-driver.jpg)
6. Click **Browse my computer for drivers**.  
![Browse my computer for drivers in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/browse-my-computer-for-drivers.jpg)
7. Click **Browse** and navigate to the location where you have extracted the CAB file.
8. Select the folder that contains the extracted file and click **OK**.  
![OK option in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/ok-option.jpg)
9. Click **Next**.  
![Next option in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/next-option.jpg)

 The Device Manager will now install the driver update on your computer.

## CAB Files: Everything You Need to Know

 You may sometimes come across a CAB file and wonder what it is and how to install it. After reading the above explanation, hopefully, you now have a basic understanding of CAB files. You now also know how to install driver updates that are in the form of CAB files.

 But what exactly is a Windows CAB file, and how do you install it on your computer? Here's everything you need to know.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-slow-downloads-in-steam-a-windows-guide/"><u>Troubleshoot Slow Downloads in Steam - A Windows Guide</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-perfect-your-pcs-sound-with-these-5-windows-11-recording-tips/"><u>In 2024, Perfect Your PC's Sound with These 5 Windows 11 Recording Tips</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-step-by-step-pubg-vocal-changes-made-easy/"><u>In 2024, Step-by-Step PUBG Vocal Changes Made Easy</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-or-see-text-messages-what-can-you-do-with-life360-on-samsung-galaxy-s23-drfone-by-drfone-virtual-android/"><u>Can Life360 Track Or See Text Messages? What Can You Do with Life360 On Samsung Galaxy S23? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-full-potential-multitasking-with-windows-11-in-mac-os-using-parallels/"><u>Unlock Full Potential: Multitasking with Windows 11 in Mac OS Using Parallels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-robust-defense-how-to-upgrade-your-pin-in-windows-11/"><u>Achieving Robust Defense: How to Upgrade Your Pin in Windows 11</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-rhythm-reduction-techniques-efficiently-extracting-percussion-from-songs-digitally/"><u>2024 Approved Rhythm Reduction Techniques Efficiently Extracting Percussion From Songs Digitally</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-aesthetic-background-tunes-for-youtube-originals/"><u>New Aesthetic Background Tunes for YouTube Originals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/utilizing-end-task-control-for-window-management/"><u>Utilizing End Task Control for Window Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-11s-advanced-setup/"><u>Decoding Windows 11'S Advanced Setup</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-10-quick-tips-to-grow-your-tiktok-following-for-2024/"><u>[New] 10 Quick Tips to Grow Your TikTok Following for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-key-clues-suggesting-windows-reboot-required/"><u>3 Key Clues Suggesting Windows Reboot Required</u></a></li>
<li><a href="https://android-unlock.techidaily.com/can-i-bypass-a-forgotten-phone-password-of-vivo-v27-pro-by-drfone-android/"><u>Can I Bypass a Forgotten Phone Password Of Vivo V27 Pro?</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/fb-video-retrieval-the-top-5-software-compared/"><u>FB Video Retrieval  The Top 5 Software Compared</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-synapse-unidentified-razer-peripherals-on-win-11/"><u>Troubleshooting Synapse: Unidentified Razer Peripherals on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-macos-performance-through-windows-innovations/"><u>Boosting macOS Performance Through Windows Innovations</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-conquering-commercials-dodge-fb-vids/"><u>[New] In 2024, Conquering Commercials  Dodge FB Vids</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-vscode-instability-in-windows-11/"><u>Troubleshooting VSCode Instability in Windows 11</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-loom-lens-view-unveiling-screen-record-magic/"><u>In 2024, Loom Lens View  Unveiling Screen Record Magic</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-offline-masterpieces-top-10-ios-game-selections-without-internet/"><u>[New] In 2024, Offline Masterpieces  Top 10 iOS Game Selections Without Internet</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-explore-premium-download-options-for-mp4/"><u>In 2024, Explore Premium Download Options for MP4</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-adjust-your-photos-on-win-11-top-six-techniques-explored/"><u>Efficiently Adjust Your Photos on Win 11: Top Six Techniques Explored</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-scheduling-in-windows-11-calendar/"><u>Streamlining Scheduling in Windows 11 Calendar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-over-controller-woes-a-guide-to-steam-detection/"><u>Win Over Controller Woes: A Guide to Steam Detection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-task-managers-dynamic-speed-in-windows-11/"><u>Boost Task Manager's Dynamic Speed in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-path-failure-on-pc-operating-systems/"><u>Tackling PATH Failure on PC Operating Systems</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-the-best-explainer-video-makers-for-businesses-for-2024/"><u>Updated The Best Explainer Video Makers for Businesses for 2024</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-erase-an-iphone-12-mini-without-apple-id-by-drfone-ios/"><u>In 2024, How to Erase an iPhone 12 mini without Apple ID?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-pc-failures-due-to-unmet-intel-graphic-standards/"><u>Addressing PC Failures Due to Unmet Intel Graphic Standards</u></a></li>
<li><a href="https://extra-hints.techidaily.com/skyward-start-best-easy-to-operate-drones/"><u>Skyward Start  Best Easy-to-Operate Drones</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-innovative-video-sharing-best-practices-for-live-monitor-display-for-2024/"><u>[Updated] Innovative Video Sharing  Best Practices for Live Monitor Display for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-secrets-of-windows-settings-dim-display/"><u>Unveiling the Secrets of Windows Settings: 'Dim Display'</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-productivity-the-essentials-of-using-flow-launcher/"><u>Accelerate Productivity: The Essentials of Using Flow Launcher</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-winning-playbook-strategies-to-eliminate-stutter-in-videos/"><u>The Winning Playbook: Strategies to Eliminate Stutter in Videos</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/detailed-guide-of-ispoofer-for-pogo-installation-on-honor-x7b-drfone-by-drfone-virtual-android/"><u>Detailed guide of ispoofer for pogo installation On Honor X7b | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-error-3-fix-for-windows-10-nvidia-opengl/"><u>Addressing Error 3: Fix for Windows 10 Nvidia OpenGL</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-access-entry-error-in-microsoft-os/"><u>Disabling 'Access Entry' Error in Microsoft OS</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-perfect-your-iphone-videographyphoto-expertise-with-add-ons/"><u>[Updated] 2024 Approved  Perfect Your iPhone Videography/Photo Expertise With Add-Ons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-to-setting-up-windows-11s-pc-manager/"><u>A Step-by-Step Approach to Setting Up Windows 11'S PC Manager</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-unlock-discords-full-potential-with-these-10-innovative-tools-for-2024/"><u>[New] Unlock Discord's Full Potential with These 10 Innovative Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-ahead-mastering-upcoming-tools-through-vivetool/"><u>Windows Ahead: Mastering Upcoming Tools Through ViVeTool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-windows-11-to-your-needs-active-hours-and-updates/"><u>Tailoring Windows 11 to Your Needs: Active Hours & Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-c0000005-failure-on-windows-108/"><u>Tackling C0000005 Failure on Windows 10/8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-unseen-an-inevitable-ai-revolution/"><u>Windows Unseen: An Inevitable AI Revolution</u></a></li>
</ul></div>
