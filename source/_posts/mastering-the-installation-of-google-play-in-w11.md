---
title: Mastering the Installation of Google Play in W11
date: 2024-07-12T17:20:26.866Z
updated: 2024-07-13T17:20:26.866Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the Installation of Google Play in W11
excerpt: This Article Describes Mastering the Installation of Google Play in W11
keywords: Google Play Setup Guide,W11 APK Installer,Play Services Update Tips,Android OS W11 GPP,Installing Google Play Ease,W11 Play Store Optimization,Quick Play Setup W11
thumbnail: https://thmb.techidaily.com/114b6bfca9f928095e8da2f7f3417492afac50bf37b6d4d36fe64b43b43e9aea.jpg
---

## Mastering the Installation of Google Play in W11

 You can natively run Android apps on Windows 11 via Windows Subsystem for Android (WSA); however, it has its limitations. The new OS only natively supports Amazon’s Appstore and not Google Play Store. And while sideloading Android apps is an option, anything that requires Google Play Services will not work.

 However, you can install Google Play Store on Windows 11 to overcome this limitation. Here we show you how.

## How to Install Google Play Store on Windows 11

 As discussed earlier, you can [sideload and run Android apps on Windows 11](https://www.makeuseof.com/windows-11-sideload-android-apps/) . However, finding APKs and installing them via the Command Prompt is cumbersome. You also need to configure Android Debug Bridge (ADB) to install Android apps.

 You can install a fully functional Google Play Store to remedy this problem. Also, this allows you to run Google Play Services-dependent apps.

 However, it is a complicated process and involves downloading several small packages and then moving them around. Fortunately, a developer (Yujinchang08) on GitHub has simplified this process with a custom WSA installer.

 The WSA installer consists of a modified WSA package with Magisk and Open GApps integration. Magisk is a root access utility wherein Open GApps offers up-to-date Google Apps packages.

 For this guide, we will focus on the second method to install Google Play Store on Windows 11\. So, let’s begin.

 Note that this process requires installing third-party modified files and packages and involves potential risks. Before proceeding,[create a restore point in Windows 11](https://www.makeuseof.com/windows-11-create-restore-point/) or [recovery drive](http://www.makeuseof.com/create-recovery-drive-system-repair-disc-windows-10/) . These recovery options can help you undo the changes or repair the system if something goes wrong.

## Step 1: Uninstall Android Subsystem for Android
![uninstall windows subsystem for android](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/uninstall-windows-subsystem-for-android.png)

 If you have Windows Subsystem for Android installed, you can uninstall it from the Apps & features section.

To uninstall WSA:

1. Press**Win + I** to open the**Settings** panel.
2. Open the**Apps** tab in the left pane.
3. Next, click on**Apps & Features.**
4. Locate and click on**Windows Subsystem for Android** under**App list** .
5. Click the**three dots** and select**Uninstall** . Click**Uninstall** again to confirm the action.

## Step 2: Enable Developer Mode in Windows 11
![enable-developer-mode-windows-11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/enable-developer-mode-windows-11.png)

 Developer Mode allows you to sideload apps and access other developer features, including remote installation apps via SSH services.

To enable Developer Mode:

1. Press**Win + I** to open the**Settings** app.
2. Open the**Privacy and Security** tab in the left pane.
3. In the right pane, click on**For Developers.**
4. Toggle the switch for**Developer Mode** and set it to**On** . Click**Yes** to confirm the action.

## Step 3: Enable Virtual Machine to Run Android Apps
![enable windows hypervisor platform windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/enable-windows-hypervisor-platform-windows-11.png)

 You need to [enable and configure Virtual Machine Platform and Windows Hypervisor Platform](https://www.makeuseof.com/windows-11-enable-hyper-v/) to run Windows Subsystem for Android on Windows 11\. Skip this step if you have installed WSA previously.

To configure the Virtual Machine:

1. Press**Win + S** to open the**search bar** .
2. Type**Windows Features** and then click on**Turn Windows features on or off** from the search results.
3. In the Windows Features window, select**Virtual Machine Platform** and**Windows Hypervisor Platform.**
4. Click**OK** to save the changes and Windows will install the selected features. Restart your PC to apply the changes.

If successful, you will see an update status message during restart.

## Step 4: Setup and Install Windows Subsystem for Linux and Linux Distro on Windows 11

 To install Google Play Store on Windows 11, you’ll need to build a locally modified Windows Subsystem for Android. For this, you’ll need to install Windows Subsystem for Linux (WSL) and a Linux distro. This is necessary as you’ll need to run some commands to build Windows Subsystem for Android.

To install WSL and a Linux distro on Windows 11:

1. Launch Microsoft Store.
2. In Microsoft Store, search for**Windows Subsystem for Linux (WSL)** and install the app. Wait for the app to install.  
![windows subsystem for linux](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-subsystem-for-linus-1.jpg)
3. Next, search for a Linux distro. We’ll use Ubuntu. So, search for**Ubuntu** and install the distro. If you have a Linux distro installed, you can skip to the next step ![Ubuntu distro windows 11 install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/ubuntu-distro-windows-11-install-1.jpg)
4. Once installed, press the**Win** key and type**Ubuntu** . Right-click on**Ubuntu** and select**Run as administrator** .
5. In the Ubuntu terminal, you’ll need to create a user with a password for the Linux system. So, create a username and password. Leave the Ubuntu terminal open.

 Now you’ll see a Linux\\Ubuntu folder in File Explorer’s left pane.

## Step 5: Setup Magisk and Windows Subsystem for Android

 The next set of steps involve downloading a Gitbub repository, MagiskOnWSALocal, to integrate Magisk root and Google Apps into WSA.

1. Go to the [MagiskOnWSALocal page](https://github.com/LSPosed/MagiskOnWSALocal) on GitHub.
2. Click the**Code** drop-down in the top right corner.  
![copy github url magiskonwsa](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/copy-github-url-magiskonwsa.jpg)
3. Copy the**GitHub URL** under the**HTTPS** tab.  
![download install magiskonWSA github command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/download-install-magiskonwsa-github-command-prompt.jpg)
4. Open the Ubuntu terminal and type the following command followed by the GitHub URL:  
`git clone https://github.com/LSPosed/MagiskOnWSALocal.git`
5. Press**Enter** to close the GitHub repository to the Linux user account on your computer.  
![run script magiskonwsa local install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-script-magiskonwsa-local-install.jpg)
6. Next, type the following command to move to the scripts folder. This will change the directory to the specified folder.  
`cd MagiskOnWSALocal  
cd scripts`
7. Next, type the following command to run the script and download the necessary files to install all the necessary files for Magisk, Play Store, and Windows Subsystem for Android:  
`./run.sh`
8. Depending on your Internet speed, downloading may take some time. So, wait till the process is complete.
9. As the process completes, you’ll see a command line installer open up.

## Step 6: Install Google Play Store on Windows 11

1. Next, in the**Into to MagiskOnWSA** dialog, select**OK** .  
![intro to magiskonWSA](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/intro-to-magiskonwsa.jpg)
2. Next, select**X64 X86\_64** for**Build Arch** .  
![build arch masigkonwsa local](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/build-arch-masigkonwsa-local.jpg)
3. Next, for**WSA release** type, select**Retail Stable Channel** .  
![WSA retail type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/wsa-retail-type.jpg)
4. Select**No** in the**Do you want to** **Root WSA dialog** .
5. Select**Yes** in the**Do you want to install GApps** dialog.  
![which GApps you want to install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/which-gapps-you-want-to-install.jpg)
6. Select**OpenGApps** in the**Which GApps do you want to install** dialog.
7. Next, in the**Do you want to keep Amazon Appstore** dialog, select**Yes** or**No** , depending on your requirement.
8. Select**No** in the**Do you want to compress the output** dialog.
9. MagiskOnWSALocal will start generating custom Windows subsystem for the Android image.

 This process may take some time to complete. So, wait for the process to complete.

## Step 7: Install Windows Subsystem for Android

 Once done, you’ll need to install WSA on Windows 11\. To install WSA, you’ll need to copy the contents of the MagiskonWSALocal folder, which contains the image file, to your installation drive and then execute a command.

 To install WSA, you need to enable Developer Mode on Windows 11\. Once enabled, follow the below steps to install WSA.

To install WSA on Windows 11:

1. Open**File Explorer** and go to the**Linux\\Ubuntu** tab.
2. Next, depending on where you had installed**MagiskOnWSA** , go to:  
`\home\username\MagiskOnWSALocal\Output  
or  
\root\MagiskOnWSALocal\output`
3. Next, open the **WSA\_2302.40000.9.0\_x64\_Release-Nightly-MindTheGapps-13.0-RemovedAmazon** folder.  
![magiskonwsalocal copy folders files](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/magiskonwsalocal-copy-folders-files.jpg)
4. Copy all the files and folders inside the**WSA** folder.
5. Next, go to your installation drive**C:\\** and create a new folder named**WSA** .  
![WSA folder Windows C drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/wsa-folder-windows-c-drive.jpg)

1. Paste the copied files into the**WSA** folder.
2. Close**File Explorer** .
3. Press the**Win** key and type**cmd** . Right-click on**Command Prompt** and select**Run as administrator** .  
![install Windows subsystem for Android windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-windows-subsystem-for-android-windows-11.jpg)
4. In the Command Prompt window, type the following command to change the directory to the WSA folder:  
`cd C:\WSA`
5. Next, run the following command to execute the following command to install the WSA package:  
`PowerShell.exe -ExecutionPolicy Bypass -File .\Install.ps1`
6. The script will install the modified Windows subsystem for Android with**Play Store** support. Wait for the installation to complete and ignore any errors in the PowerShell console.
7. Once done, you’ll see the**Magisk** and**Play Store** windows. However, you’ll need to enable**Developer mode** on Windows Subsystem for Android to use Play Store.

To enable Developer mode on Windows Subsystem for Android:

![Windows subsystem for android enable developer mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-subsystem-for-android-enable-developer-mode.jpg)

1. Press the**Win** key, type**Windows Subsystem for Android** , and open the app from the search results.
2. Next, open the**Developer** tab in the left pane.
3. Toggle the**Developer mode** switch to turn it**On** .
4. Next, open the**Play Store App** and sign in with your Google account. You may need to authenticate and sign in on your Android device.

 After signing in, you can download and install all the Play Store apps just like on an Android phone. Also, you can open the installed apps from the Start menu, Windows search, and apps list.

 Now you can install Android apps on Windows 11 from Google Play Store. That said, some apps may still not work properly due to the region and licensing restrictions.

## Installing the Google Play Store on Windows 11

 Being able to run Android apps natively on Windows 11 removes the hassle of Android emulators. Now with the Play Store support, you can install most if not all the Android apps without sideloading.

 That said, for the apps that are not available in Play Store, you can sideload them on your Windows 11 PC using Command Prompt or the WSA Tool.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>



<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/in-depth-analysis-process-sorting-and-theme-customization-in-windows-11/"><u>In-Depth Analysis: Process Sorting and Theme Customization in Windows 11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/bending-images-photoshops-simplest-alterations-for-2024/"><u>Bending Images  Photoshop's Simplest Alterations for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-grades-with-these-top-8-windows-study-hacks/"><u>Skyrocket Grades with These Top 8 Windows Study Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-correcting-severe-browser-js-problem-in-discord/"><u>Strategies for Correcting Severe Browser JS Problem in Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-new-waves-in-windows-unlocking-vivetools-secrets/"><u>Navigating New Waves in Windows: Unlocking ViVeTool's Secrets</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-essential-tips-for-ppt-video-production/"><u>[New] In 2024, Essential Tips for PPT Video Production</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-intelligence-microsofts-new-ai-helper-for-windows-11-taskbar/"><u>Integrating Intelligence: Microsoft's New AI Helper for Windows 11 Taskbar</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-how-to-extract-the-beat-from-any-song-using-online-tools/"><u>In 2024, How to Extract the Beat From Any Song Using Online Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-correction-resetting-folders-on-a-ws11-pc/"><u>Immediate Correction: Resetting Folders on a WS11 PC</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/storytellers-sanctum-summit-selections/"><u>Storytellers Sanctum – Summit Selections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-methodology-for-windows-update-reset/"><u>Stepwise Methodology for Windows Update Reset</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-this-article-aims-to-show-you-how-to-export-videos-in-filmora/"><u>New This Article Aims to Show You How to Export Videos in Filmora</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-discovering-synergistic-partnerships-on-youtube-platforms/"><u>2024 Approved  Discovering Synergistic Partnerships on YouTube Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-revive-network-router-page-on-windows/"><u>Methods to Revive Network Router Page on Windows</u></a></li>
<li><a href="https://audio-editing.techidaily.com/a-guide-to-the-premier-8-sounds-for-youtube-launches-and-introduction-scenes-for-2024/"><u>A Guide to the Premier 8 Sounds for YouTube Launches and Introduction Scenes for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-minimize-malware-scanners-cpuram-demands/"><u>How to Minimize Malware Scanner's CPU/RAM Demands</u></a></li>
<li><a href="https://vp-tips.techidaily.com/revive-your-iphone-ipad-and-macs-airdrop-functionality-with-quick-tips/"><u>Revive Your iPhone, iPad & Mac's Airdrop Functionality with Quick Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-phone-call-basics-with-intel-unison/"><u>Mastering Windows 11: Phone Call Basics with Intel Unison</u></a></li>
<li><a href="https://win11-tips.techidaily.com/start-your-chatgpt-experience-windows-guide/"><u>Start Your ChatGPT Experience: Windows Guide</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-best-webcams-on-windows-10-top-applications-reviewed/"><u>[Updated] In 2024, Best Webcams on Windows  10 Top Applications Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalize-your-windows-11-interface-with-these-tips/"><u>Revitalize Your Windows 11 Interface with These Tips</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-capturing-both-webcam-and-monitor-live-feed/"><u>In 2024, Capturing Both Webcam & Monitor Live Feed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-win11-space-to-perfection/"><u>Tailoring Your Win11 Space to Perfection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-valorant-microphone-failures-on-windows-10/"><u>Overcoming Valorant Microphone Failures on Windows 10</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-win10s-elite-screen-capture-selection/"><u>[New] Win10's Elite Screen Capture Selection</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-easy-guide-to-oppo-k11-5g-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to Oppo K11 5G FRP Bypass With Best Methods</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/achieve-xbox-broadcast-excellence-on-facebook-for-2024/"><u>Achieve Xbox Broadcast Excellence on Facebook for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-recordings-best-no-fee-windows-editors/"><u>Master Your Recordings: Best No-Fee Windows Editors</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-accelerate-your-videos-a-quicktime-player-guide-for-windows-and-mac/"><u>Updated 2024 Approved Accelerate Your Videos A QuickTime Player Guide for Windows and Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-0x8024800c-in-windows-update/"><u>Steps to Resolve 0X8024800C in Windows Update</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-nokia-105-classic-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos From Nokia 105 Classic to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-comics-an-intuitive-approach-for-win11-users/"><u>Navigating Comics: An Intuitive Approach for Win11 Users</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-2024-approved-add-pro-level-effects-to-your-videos-in-3-easy-steps-with-fcp-x/"><u>Updated 2024 Approved Add Pro-Level Effects to Your Videos in 3 Easy Steps with FCP X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapid-rectifications-quick-tricks-to-prevent-windows-crashes-in-games/"><u>Rapid Rectifications: Quick Tricks to Prevent Windows Crashes in Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfecting-selectivity-enable-checkbox-file-option-in-win11/"><u>Perfecting Selectivity: Enable Checkbox File Option in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-monitoring-integrating-system-resource-data-in-systray/"><u>Streamline Monitoring: Integrating System Resource Data in SysTray</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-unidentified-window-second-screen/"><u>Resolving Unidentified Window Second Screen</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-deciphering-fb-mystery-vanishing-youtubefacebook-videos/"><u>In 2024, Deciphering FB Mystery  Vanishing YouTube/Facebook Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/implementing-windows-11-parental-control-measures/"><u>Implementing Windows 11 Parental Control Measures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-windows-11-keyboard-shortcuts-next-to-power-icon/"><u>Tailoring Windows 11: Keyboard Shortcuts Next to Power Icon</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-there-are-no-more-files-error-on-windows-10-and-11/"><u>How to Fix the “There Are No More Files” Error on Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-geforce-experience-setup-failure-windows-11-edition/"><u>Resolving GeForce Experience Setup Failure, Windows 11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reboot-the-process-solving-hidden-logins-on-windows-11/"><u>Reboot the Process: Solving Hidden Logins on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-solve-media-creator-tool-errors-winerror-0x8007043c/"><u>How to Solve Media Creator Tool Errors: WinError 0X8007043C</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-essential-strategies-for-memorable-youtube-closings/"><u>In 2024, Essential Strategies for Memorable YouTube Closings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-minecraft-glitches-with-these-fixes/"><u>Stop Minecraft Glitches with These Fixes</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-how-to-overlay-photos-on-computer-desktop-and-online/"><u>[Updated] In 2024, How to Overlay Photos on Computer (Desktop & Online)</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-beyond-the-buzzwords-the-leading-edits-without-vimeo-for-2024/"><u>[New] Beyond the Buzzwords  The Leading Edits Without Vimeo for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-microsoft-store-blockage-issue-on-win11/"><u>Resolving Microsoft Store Blockage Issue on Win11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-rapid-reference-green-screen-basics/"><u>In 2024, Rapid Reference  Green Screen Basics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-hyper-v-in-windows-11/"><u>How to Enable Hyper-V in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-error-code-31-in-windows-os/"><u>Mastering the Art of Fixing Error Code 31 in Windows OS</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-discovering-deliciousness-tiktoks-most-shared-snacks/"><u>[Updated] In 2024, Discovering Deliciousness  TikTok's Most Shared Snacks</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-essential-free-tiktok-cutting-tools-for-mac-computers/"><u>[Updated] In 2024, Essential Free TikTok Cutting Tools for Mac Computers</u></a></li>
</ul></div>
