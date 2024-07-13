---
title: A Step-by-Step Approach for Moving Programs in Windows 11
date: 2024-07-12T17:52:51.860Z
updated: 2024-07-13T17:52:51.860Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Step-by-Step Approach for Moving Programs in Windows 11
excerpt: This Article Describes A Step-by-Step Approach for Moving Programs in Windows 11
keywords: Win11 Move Apps Guide,Windows 11 Transfer Programs,Program Relocation W11,Step-by-Step Program W11 Move,Easy Program Mover in Windows 11,Windows 11 App Migration Tips,Quick Program Placement Win11
thumbnail: https://thmb.techidaily.com/2bb5e1bc170b8c3f4a6ce1aff27e49a67b4dbeb274ccf0d0ed18fa3d929b62b2.jpg
---

## A Step-by-Step Approach for Moving Programs in Windows 11

 Setting up Windows 11 on your PC, or another PC is a laborious task. After installing the operating system and the OEM drivers, there is still a lot of work left. You need to reconfigure your system settings, re-download, and install all the Microsoft Store apps. Along with that, you need to individually download and install each third-party software, which makes it more challenging.

 But what if you could eliminate the hours spent in finding and installing every single app, and configuring every setting? We will discuss two methods to effortlessly migrate most of your old apps to your new PC.

## 1\. Using Microsoft Account

 If you used a Microsoft account on your old PC, Windows 11 offers multiple options to back up your App list, Preferences, and use OneDrive for personal files. To do that, you must enable [OneDrive](https://www.makeuseof.com/what-is-onedrive/) and back up all your personal files and folders to it. It will only take care of the files part but the apps and preferences are still left. But you must also enable the backup of these two things on your old PC before [reinstalling Windows 11](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/) or migrating to a new PC.

 Repeat the following steps to enable apps and settings backup:

1. Press **Win + I** to launch the Settings app. Navigate to **Accounts > Windows backup** section.
2. Go to the **Remember my apps** option and click on the toggle next to it to enable the settings.
3. Next, click on the toggle next to **Remember my preferences** option to back up your settings as well.  
![Backup Apps and Preferences to Microsoft Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/backup-apps-and-preferences-to-microsoft-account.jpg)
4. You will notice that the top section of the Windows backup page will mark each of these features as “**backed up**”.

 After you reinstall Windows 11, the OOBE page will ask you to [sign in with a Microsoft account](https://www.makeuseof.com/windows-switch-local-account-to-microsoft-account/). Enter your credentials, and you will see a “Welcome back, User!” message with an option to restore all apps, settings, and files present on your previous machine. Click on the **Next** button and proceed setup up your new PC

![Install Old Apps Using Microsoft Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-old-apps-using-microsoft-account.jpg)

 As soon as you boot to the desktop, you will see a popup that Windows is trying to restore the most used apps from before. It will ask you to open Microsoft Store to restore additional apps from your old PC. Click on the **Restore my apps** button.

![Install Old Apps Using Microsoft Account 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-old-apps-using-microsoft-account-2.jpg)

 Microsoft Store will display all the remaining apps available for restoration. Click on the **Restore All** button if you want to bring back every app. Wait for the apps to install and then close Microsoft Store.

![Install Old Apps Using Microsoft Account 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-old-apps-using-microsoft-account-3.jpg)

## 2\. Using a Winget JSON File

 The first method of using Microsoft Account has its limitations. It only includes Windows apps and settings but leaves many other third-party apps that you installed from the Winget repository or from the web. So you can use Winget to export the app list into a JSON file and then import it to your new Windows 11 PC. You must execute this method after Windows 11 brings back all the settings and Microsoft apps, and you boot to the desktop.

 Repeat the following steps to import a Winget JSON file:

1. Download or copy the Winget export file on your system.
2. Press **Win + R** to open the **Run dialog box**. Type **cmd** and press **Ctrl + Shift + Enter** to [open Command Prompt with administrator privileges](https://www.makeuseof.com/how-to-always-open-command-prompt-as-administrator-windows/).
3. Now, use the **winget import -i** command to import the JSON file. Type the following command and press the **Enter** key:  
`winget import -i C:\apps.json --accept-source-agreements --accept-package-agreements`
4. Replace the folder location and name with the storage location and name of the winget export file on your system.  
![Import Apps Using Winget in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/import-apps-using-winget-in-windows-11.jpg)
5. Patiently wait while winget downloads and installs all the packages in the JSON file one by one. Then, close the Command Prompt window.

## What About Any Left Out Apps?

 Even after using both methods, some apps will still be left out. It is because Microsoft Account sign-in only brings back Windows settings and Microsoft Store apps. The winget export file can restore only the apps listed in its official repository.

 As such, you still need to download the programs that aren’t included in both of these methods. But it will be a very short list compared to the effort you would have to put in if you just performed a normal installation.

## Save Time When Setting Up Windows 11

 Make sure to enable files, apps, and preferences backup on your PC and create a winget export file beforehand. After you have both these backups in place, you can begin reinstalling Windows 11 on a different PC or reinstalling on the same PC.

 But what if you could eliminate the hours spent in finding and installing every single app, and configuring every setting? We will discuss two methods to effortlessly migrate most of your old apps to your new PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/achieve-advanced-settings-for-windows-11s-bar/"><u>Achieve Advanced Settings for Windows 11'S Bar</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-5-critical-equipment-items-to-start-your-channel-right-for-2024/"><u>[New] 5 Critical Equipment Items to Start Your Channel Right for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-screen-projection-not-working-window-glitch/"><u>Addressing Screen Projection Not Working Window Glitch</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-instagram-exit-wave-analysis-for-2024/"><u>[New] Instagram Exit Wave Analysis for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/prevent-cross-site-tracking-on-apple-iphone-8-and-browser-drfone-by-drfone-virtual-ios/"><u>Prevent Cross-Site Tracking on Apple iPhone 8 and Browser | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-system-best-practices-for-dns-setup-in-windows-11/"><u>Accelerate Your System: Best Practices for DNS Setup in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-valorant-setup-with-these-tips/"><u>Accelerate Your Valorant Setup with These Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-common-failures-when-importing-iphones-to-windows/"><u>Addressing Common Failures When Importing iPhones to Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activate-and-configure-powershell-execution-policies-securely/"><u>Activate & Configure PowerShell Execution Policies Securely</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719323547365-unlock-the-future-affordable-windows-11-for-keys-fan-enthusiasts-on-black-friday/"><u>Unlock the Future: Affordable Windows 11 for Keys Fan Enthusiasts on Black Friday</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-the-speaker-in-microsofts-new-era/"><u>Activating the Speaker in Microsoft's New Era</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-ultimate-display-match-top-6-hdmi-21-monitors-compared/"><u>[New] The Ultimate Display Match  Top 6 HDMI 2.1 Monitors Compared</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-crashes-of-ccleaner-in-windows-11/"><u>Addressing Crashes of CCleaner in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activate-secure-networking-with-telnet-on-windows-11/"><u>Activate Secure Networking with Telnet on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-key-strategies-for-optimizing-windows-11s-bar/"><u>5 Key Strategies for Optimizing Windows 11'S Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-innovative-windows-tricks-for-program-launching/"><u>6 Innovative Windows Tricks for Program Launching</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-fixing-no-write-saves-winos/"><u>A Step-by-Step Guide to Fixing No Write Saves, WinOS</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-transformative-content-strategies-for-tiktok-success/"><u>[New] In 2024, Transformative Content Strategies for TikTok Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-windows-11-firewall-settings-to-the-context-menu/"><u>Adding Windows 11 Firewall Settings to the Context Menu</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-redefine-viewing-premium-platforms-for-videos/"><u>2024 Approved  Redefine Viewing  Premium Platforms for Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-your-workflow-efficient-redo-keys-on-windows/"><u>Ace Your Workflow: Efficient Redo Keys on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-functional-cutpaste-in-win-11/"><u>Addressing Non-Functional Cut/Paste in Win 11</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-digital-domain-decision-which-platform-for-your-videos/"><u>2024 Approved  Digital Domain Decision  Which Platform for Your Videos?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-absentee-tab-button-on-your-pc/"><u>Addressing the Absentee Tab Button on Your PC</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-step-by-step-strategies-to-thrive-on-reddit/"><u>[New] Step-by-Step Strategies to Thrive on Reddit</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-capture-the-inspired-moment-essential-photos-for-ig/"><u>2024 Approved  Capture the Inspired Moment  Essential Photos for IG</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-step-by-step-plan-msoffice-install-on-win11/"><u>A Complete Step-by-Step Plan: MSOffice Install on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-using-windows-iscsi-initiator/"><u>A Step-by-Step Guide to Using Windows iSCSI Initiator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-file-history-misconfiguration-in-windows/"><u>Addressing File History Misconfiguration in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-excessive-tiworkerexe-cpu-usage-issue/"><u>Addressing Excessive TiWorker.exe CPU Usage Issue</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-ultimate-guide-to-non-time-restricted-recorders-for-2024/"><u>[Updated] Ultimate Guide to Non-Time Restricted Recorders for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-walkthrough-cortana-data-retrieval-for-windows-users/"><u>A Complete Walkthrough: Cortana Data Retrieval for Windows Users</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-exclusive-list-of-cost-free-video-downloaders-from-pinterest/"><u>[Updated] Exclusive List of Cost-Free Video Downloaders From Pinterest</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-networked-resources-in-explorers-sidebar/"><u>Adding Networked Resources in Explorer's Sidebar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-fix-the-cannot-find-gpeditmsc-error-in-windows/"><u>4 Ways to Fix the “Cannot Find Gpedit.msc” Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-setup-5-key-tools-to-turbocharge-windows/"><u>Accelerate Your Setup: 5 Key Tools to Turbocharge Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719382132283-boost-your-windows-screenshot-game-4-key-solutions/"><u>Boost Your Windows Screenshot Game: 4 Key Solutions</u></a></li>
</ul></div>
