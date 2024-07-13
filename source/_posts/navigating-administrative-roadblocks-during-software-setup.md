---
title: Navigating Administrative Roadblocks During Software Setup
date: 2024-07-12T17:08:57.762Z
updated: 2024-07-13T17:08:57.762Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Administrative Roadblocks During Software Setup
excerpt: This Article Describes Navigating Administrative Roadblocks During Software Setup
keywords: Admin Setup Challenges,Overcoming Software Hurdles,Ease Software Installation,Bypassing IT Obstacles,Simplify Tech Implementation,Remove Setup Barriers,Streamline System Deployment
thumbnail: https://thmb.techidaily.com/6110f59d84b8b2836afe3cb9128ab55b4983bac7c041837cad5f3c0f9163df97.jpg
---

## Navigating Administrative Roadblocks During Software Setup

 Installing software is usually a smooth process on Windows 10 and 11 PCs. However, sometimes installation hiccups can arise. For instance, some users have reported this error message appears when they try to install Windows software packages, “The system administrator has set policies to prevent this installation.”

 Users cannot install whatever programs for which that system administrator error arises. The error message suggests this issue is due to some kind of enforced admin settings. You can fix the “system administrator has set policies” error by applying the resolutions below.

## 1\. Run the Software’s Setup File as An Administrator

 First, start with the easiest of potential solutions. They don’t get much simpler than running the affected software’s installation file with administrative rights. Right-click the setup file for the software you can’t install and select **Run as administrator** on its context menu.

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-run-as-administrator-option.jpg)

## 2\. Enable the Built-in Windows Admin Account

 It has been confirmed by some users that activating and logging into the built-in (hidden) Windows admin account can fix the “system administrator has set policies” error. It’s recommended to try that even if your current user account is an administrative one. You can do that by following the instructions for the Command Prompt method in our guide to [enabling the built-in Windows administrator account](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/).

![The net user administrator /active:yes command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/net-user-admin-account-command.jpg)

 When you’ve activated the account, restart your Windows PC. Then sign in to the newly activated admin account and try installing the software you need from there. Disable the built-in administrator account when you’re done with it.

## 3\. Turn Off UAC (User Account Control)

 User Account Control is a security screen that can hinder the installation of programs when set at its highest setting. To ensure UAC isn’t causing any issues with installing software, temporarily turn off User Account Control by selecting its lowest **Never notify** option. You can apply this potential fix by disabling User Account Control with one of the methods in our [guide to turning off UAC](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/).

![The User Account Control Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-uac-settings.jpg)

## 4\. Run or Restart the Windows Installer Service

 Windows Installer is a service that needs to be running for users to install software with MSI packages. So, check that service is enabled and running. Even if it is, restarting that service might also resolve the “system administrator has set policies” error. This is how you can run or restart Windows Installer:

1. To access the file finder tool, right-click **Start** and select the **Search** shortcut.
2. Next, input a **services** search phrase.
3. Click the **Services** app found by the search tool.
4. Double-click **Windows Installer** to see that service’s property settings.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-services-window.jpg)
5. If the service is stopped, click its **Start** button. Or select **Stop** and **Start** to restart Windows Installer.  
![The Windows Installer Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-windows-installer-properties-service-window.jpg)
6. Select **Apply** \> **OK** to save the Windows Installer service settings.

## 5\. Change Group Policy Settings

 Lots of users have fixed the “system administrator has set policies” error by setting the Windows Installer policy to never disable Windows Installer. However, you will need to access Local Group Policy Editor, available in the Windows Pro and Enterprise editions, to apply this potential fix. If you can utilize that tool, change the **Turn Off Windows Installer** policy like this:

1. Press **Win + R**, input the **gpedit.msc** command, and click **OK** to [openLocal Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
2. Double-click on **Computer Configuration** and **Administrative Templates** inside Group Policy’s left sidebar.
3. Then go to **Windows Components** \> **Windows Installer** to access policy settings.
4. Double-click the **Turn off Windows Installer** policy setting.  
![The Turn off Windows Installer policy setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-installer-policy-settings.jpg)
5. Select **Enabled** if that option isn’t already set.
6. Then click **Never** on the **Disable Windows Installer** drop-down menu.  
![The Never option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-never-option.jpg)
7. Select the policy window’s **Apply** and **OK** options.

 On top of that, delete software restriction policies. These are the steps for deleting software restriction policies:

1. Double-click **Windows Settings** \> **Security Settings** in Group Policy’s sidebar.
2. Right-click **Software Restriction Policies** and select **Delete Software Restriction Policies** if that option is available.  
![delete-software-restriction-policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/delete-software-restriction-policies.jpg)
3. Click **Yes** to confirm the deletion of software restriction policies.

 Some users also say they went even further and created a new software restriction policy in Group Policy Editor to resolve the “system administrator has set policies” error. You can try doing that after selecting to delete software restriction policies. Create a new software restriction policy like this:

1. Click **Software Restriction Policies** with the right mouse button to select **New Software Restriction Policies**.  
![The New Software Restriction Policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-software-restriction-policies.jpg)
2. Double-click on **Enforcement**.  
![The Software Restriction Policies object types](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enforcement-option.jpg)
3. Select the **All users except local administrators** radio button.  
![The Enforcement Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enforcement-properties-window.jpg)
4. Click the Enforcement Properties window’s **Apply** and **OK** options.
5. [Run Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/#:~:text=Press%20the%20Win%20%2B%20R%20on,Command%20Prompt%20with%20administrative%20privileges.) via the search utility.
6. Enter and execute this command for updating the policy:  
`gpupdate /force`
7. Exit the Command Prompt app and restart Windows.

## 6\. Edit the Installer Registry Key

 Editing an **Installer** registry key is a widely confirmed fix for the “system administrator has set policies” error. This registry tweak involves setting a **DisableMSI** DWORD value. You may also need to create a new **Installer** key from scratch if it’s not already there. These are the steps for applying this registry solution:

1. Click on the taskbar magnifying glass or Search box.
2. Type in a **regedit** search term to locate the Registry Editor app.
3. Select **Registry Editor** to start that app.
4. Input this path inside the Registry Editor address bar:  
`HKEY_LOCAL_MACHINE\Software\Policies\Microsoft\Windows\`
5. If you can’t see an **Installer** subkey, right-click the **Windows** key and select **New** \> **Key**. Users who can select an existing **Installer** subkey within the **Windows** key can skip through to step seven.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-new-key-options.jpg)

1. Enter **Installer** for the new key’s name.
2. Right-click the **Installer** key and select **New** \> **DWORD (32-bit) Value**.
3. Enter **DisableMSI** to be the title of the new DWORD.  
![the-disable-msi-dword](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-disable-msi-dword.jpg)
4. Double-click **DisableMSI** inside the **Installer** key.
5. Make sure the **DisableMSI** value is set to **0**.  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-edit-dword-window.jpg)
6. Select **OK** to set the **DisableMSI** value.
7. Close Registry Editor and restart your PC.

## Get Your Windows Software Installed

 The “system administrator has set policies” error is an old Windows issue many users have fixed with the troubleshooting methods covered in this guide. So, those are tried and tested resolutions that will likely fix the “system administrator has set policies” error on your PC. Then you can get all the Windows 10 and 11 software you need installed.

 Users cannot install whatever programs for which that system administrator error arises. The error message suggests this issue is due to some kind of enforced admin settings. You can fix the “system administrator has set policies” error by applying the resolutions below.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-videos.techidaily.com/capturing-every-angle-how-to-post-360-photos-on-androidios/"><u>Capturing Every Angle  How to Post 360 Photos on Android/iOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stopping-intelligent-assistant-protocol-on-windows/"><u>Stopping Intelligent Assistant Protocol on Windows</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/start-with-simple-understanding-facebook-metrics-for-newbies-for-2024/"><u>Start with Simple  Understanding Facebook Metrics for Newbies for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-unanticipated-error-messages-in-wins-secure/"><u>Tackling Unanticipated Error Messages in WINS Secure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-audio-tracking-on-windows-powered-screencasts/"><u>Strategies for Audio Tracking on Windows-Powered Screencasts</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-gamified-learning-educational-youtubers-to-subscribe/"><u>2024 Approved  Gamified Learning  Educational YouTubers to Subscribe</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dual-virus-defense-think-again-windows-users/"><u>Dual Virus Defense? Think Again, Windows Users!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-pens-tools-for-the-modern-windowed-tech-user/"><u>Top Pens' Tools For the Modern Windowed Tech User</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-adobe-reader-setup-on-ms-store/"><u>Effortless Adobe Reader Setup on MS Store</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-premiere-pro-rapid-transitions/"><u>2024 Approved  Premiere Pro Rapid Transitions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-workflow-programmatic-shortcuts-in-winos/"><u>Streamline Workflow: Programmatic Shortcuts in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-insufficient-ram-issues-on-windowsvmware-platforms/"><u>Addressing Insufficient RAM Issues on Windows/VmWare Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sync-your-schedule-how-to-reset-windows-time-service/"><u>Sync Your Schedule: How to Reset Windows Time Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-using-windows-file-browsing-in-place-of-ls/"><u>Expert Tips for Using Windows File Browsing in Place of LS</u></a></li>
<li><a href="https://extra-hints.techidaily.com/skyward-haven-of-the-pennywise-clouds/"><u>Skyward Haven of the Pennywise Clouds</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-learn-the-insider-tricks-of-screening-instagram-stories/"><u>[Updated] 2024 Approved  Learn the Insider Tricks of Screening Instagram Stories</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-the-ultimate-guide-to-linkedin-video-thumbnail-dimensions/"><u>New 2024 Approved The Ultimate Guide to LinkedIn Video Thumbnail Dimensions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-changing-app-size-using-pc-keys-on-windows-11/"><u>Tips for Changing App Size Using PC Keys on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-combination-of-files-in-windows-1011/"><u>Seamless Combination of Files in Windows 10/11</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-replace-windows-movie-maker-on-mac-top-video-editing-solutions/"><u>Updated In 2024, Replace Windows Movie Maker on Mac Top Video Editing Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-run-pcs-leveraging-the-power-of-key-optimization-tools/"><u>Efficiently Run PCs: Leveraging the Power of Key Optimization Tools</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/maximizing-quality-and-efficiency-with-compressor-in-final-cut-pro-x-for-2024/"><u>Maximizing Quality and Efficiency with Compressor in Final Cut Pro X for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-ultimate-guide-on-samsung-galaxy-a15-5g-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide on Samsung Galaxy A15 5G FRP Bypass</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-smooth-download-of-unmarked-tiktok-content/"><u>[Updated] 2024 Approved  Smooth Download of Unmarked TikTok Content</u></a></li>
<li><a href="https://article-files.techidaily.com/new-seamless-speech-to-text-translation-in-microsoft-office-suite-word-for-2024/"><u>[New] Seamless Speech-to-Text Translation in Microsoft Office Suite (Word) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-tech-companion-asus-vivobook-s-15-review/"><u>The Ultimate Tech Companion: Asus Vivobook S 15 Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unhindered-wi-fi-on-your-desktop-9-strategies-for-win11-users/"><u>Unhindered Wi-Fi on Your Desktop: 9 Strategies for Win11 Users</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-the-new-era-of-authenticity-understanding-the-algorithm-update/"><u>[Updated] The New Era of Authenticity  Understanding the Algorithm Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-background-removal-in-photo-editing-tools/"><u>Mastering Background Removal in Photo Editing Tools</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/the-art-of-producing-captivating-facebook-video-content-for-2024/"><u>The Art of Producing Captivating Facebook Video Content for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-captivating-creativity-top-30-unique-tiktok-profile-photos/"><u>2024 Approved  Captivating Creativity  Top 30 Unique TikTok Profile Photos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-correcting-xbox-game-pass-error-0x000-on-windows-11-systems/"><u>Understanding and Correcting Xbox Game Pass Error 0X000_ on Windows 11 Systems</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-principles-of-paradoxical-intervention/"><u>[Updated] Principles of Paradoxical Intervention</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-top-5-grievances-from-windows-11-users/"><u>Unveiling the Top 5 Grievances From Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-path-setting-up-google-maps-on-windows-pcs/"><u>Navigating the Path: Setting up Google Maps on Windows PCs</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-freebie-flicks-discovering-the-top-10-free-movies-online/"><u>In 2024, Freebie Flicks  Discovering the Top 10 Free Movies Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-your-cyber-voyage-checking-stable-connections-on-pc/"><u>Securing Your Cyber Voyage: Checking Stable Connections on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-path-upgrading-your-vm-software-from-virtualbox-v6-to-v7-in-win11/"><u>Step-by-Step Path: Upgrading Your VM Software From VirtualBox v6 to v7 in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-common-errors-in-win1011-0x8007045d/"><u>Solving Common Errors in Win10/11 - 0X8007045D</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-iconic-imagery-transforming-audio-into-visual-podcast-identity/"><u>[Updated] Iconic Imagery  Transforming Audio Into Visual Podcast Identity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trailblazing-to-windows-birthplace-points/"><u>Trailblazing to Windows' Birthplace Points</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-lowering-cpu-intensity-in-gaming-windows/"><u>Solutions for Lowering CPU Intensity in Gaming Windows</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-make-every-frame-count-best-1080p-video-editing-software-for-film-quality-results/"><u>Updated Make Every Frame Count Best 1080P Video Editing Software for Film-Quality Results</u></a></li>
<li><a href="https://win11-tips.techidaily.com/spotting-large-files-and-drives-in-windows-storage-soup/"><u>Spotting Large Files & Drives in Windows Storage Soup</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-the-ultimate-pathway-to-vimeo-recording/"><u>[New] The Ultimate Pathway to Vimeo Recording</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/mastering-tiktoks-siri-speech-functionality/"><u>Mastering TikTok's Siri Speech Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-6-most-reliable-brightness-tools-for-windows-multi-display-users/"><u>The 6 Most Reliable Brightness Tools For Windows Multi-Display Users</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-stream-to-success-obs-youtube-broadcast-basics/"><u>In 2024, Stream to Success  OBS Youtube Broadcast Basics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-setup-a-closer-look/"><u>Windows 11 Setup: A Closer Look</u></a></li>
</ul></div>
