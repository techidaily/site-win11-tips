---
title: The Ultimate Guide to Setting up Window Sandbox
date: 2024-07-12T17:14:37.359Z
updated: 2024-07-13T17:14:37.359Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Ultimate Guide to Setting up Window Sandbox
excerpt: This Article Describes The Ultimate Guide to Setting up Window Sandbox
keywords: Window Sandbox Basics,Window Sandbox Setup,Creating Window Sandbox,Window Play Without Risks,Secure Windows Gaming,Safe Software Testing,Windows Virtual Environment
thumbnail: https://thmb.techidaily.com/a23ef58f3369824904efee9f97817b15b093c9dc4ea1ce81d7226560e11dda64.jpg
---

## The Ultimate Guide to Setting up Window Sandbox

 Microsoft Windows 11 features multiple virtualization solutions out of the box. While Hyper-V is an excellent tool, Windows Sandbox is an easy alternative to Windows virtual machines. It lets you run untrusted apps in an isolated environment without the hassle of setting up a complete virtualization tool.

 Unfortunately, Windows Sandbox is not available on the Home edition of the OS. If you are running the Pro, Enterprise, and Education edition, here is how to enable and set up Windows Sandbox in Windows 11.

## How to Set Up Windows Sandbox in Windows 11

 Windows Sandbox is an optional feature, which means you'll have to install it from the Optional features section. You can [add and remove optional features from the Windows Features dialog](http://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) . Alternatively, you can use PowerShell or Command Prompt for a swift installation of Windows Sandbox.

 While the setup process is easier, your computer must meet some system requirements. Windows 11 Pro, Education, or Enterprise running computers with virtualization support are Windows Sandbox compatible. In most cases,[if your system can run Windows Hyper-V](https://www.makeuseof.com/windows-11-enable-hyper-v/) , it should also run Windows Sandbox.

## 1\. Enable Windows Sandbox Using the Windows Features Dialog

 You can install Windows Sandbox using the Windows Features dialog. This dialog houses most of the optional Windows features that are ready to be installed on your PC.

 Follow these steps to install Windows Sandbox using the Windows Features dialog:

1. Press**Win + R** to open**Run** .
2. Type**appwiz.cpl** and click**OK** to open**Control Panel.**
3. In the left panel, click on**Turn Windows features on or off.**  
![control panel turn windows features on or off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/control-panel-turn-windows-features-on-or-off.jpg)
4. In the**Turn Windows features on or off dialog** , scroll down and locate**Windows Sandbox.**
5. Check the**Windows Sandbox** option and click**OK** .  
![enable Windows sandbox turn windows features on or off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-Windows-sandbox-turn-windows-features-on-or-off.jpg)
6. Windows will search for the files and install the required dependencies to run Windows Sandbox scenarios. Once the changes are applied, close the Windows features dialog and restart your PC.
7. After the restart, press**Win + S** to open**Windows search.**
8. Type**sandbox** and click on**Windows Sandbox** from the search result to launch the virtualization tool.

## 3\. Install Windows Sandbox Using PowerShell
![enable windows sandbox powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-windows-sandbox-powershell.jpg)

 You can use the Enable WindowsOptionalFeature command in PowerShell to install Windows Sandbox in Windows. This method is useful if you find the sandbox option greyed out or unable to install it from the Windows Feature dialog.

To install Windows Sandbox using PowerShell:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Windows Terminal (Admin)** to open the Windows Terminal with administrative privilege. Since PowerShell is assigned as the default profile upon launch, you can execute your PowerShell cmdlets straight away in Windows Terminal.
3. In the Windows Terminal window, copy and paste the following command and press Enter:  
Enable-WindowsOptionalFeature -Online -FeatureName "Containers-DisposableClientVM" -All
4. If no error occurs, Windows will install the required files to enable Windows Sandbox.
5. Once done, press**Y** and hit**Enter** to restart your PC.
6. After the restart, you can launch Windows Sandbox from Windows Search.

## 3\. Install Windows SandBox Using Command Prompt
![enable windows sandbox command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-windows-sandbox-command-prompt.jpg)

 Deployment Image Servicing and Management (DISM) is a command-line utility that facilitates the installation of optional features using the Command Prompt. To install Windows Sandbox, you will need to use the Enable-Feature command in Command Prompt. Here's how to do it.

1. Press**Win + R** to open**Run** .
2. Type**cmd** in the**Run** dialog. Press and hold**Ctrl + Shift** and click**OK** to open Command Prompt as administrator.
3. In the Command Prompt, type the following command and press**Enter** :  
`dism /online /Enable-Feature /FeatureName: "Containers-DisposableClientVM" -All`
4. Wait for the process to complete. Once done, press**Y** and**Enter** to restart your PC.

## How to Use Windows Sandbox
![Windows Sandbox Open](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Windows-Sandbox-Open.jpg)

 Now that you have Windows Sandbox installed, you can start using it to test untrusted apps in isolation. To launch the app, press**Win + S** to open**Windows Search** and type**Windows Sandbox.** Click on the app from the search result to open it.

 Upon its launch, Windows Sandbox looks like a lightweight version of your Windows machine. You can copy files from your host system or download them from the Internet using the built-in web browser. Any actions you perform in the sandbox will not affect your host system.

 Once the testing is complete, close the Sandbox and click**OK** to confirm the action. Unlike a VM, Sandbox will delete all the data (including apps and files) upon exit. So, you'll get a clean, isolated environment running the same Windows OS build as your host machine each time.

## Set Up and Use Windows Sandbox in Windows 11

 Windows Sandbox provides an excellent way to test apps and files in an isolated environment without the hassle of setting up a virtual machine. While the virtual machines have distinct advantages, Sandbox is lighter, faster, and loads a fresh copy of Windows OS each time it's run.

 Windows 11 Home users, however, have missed out on this excellent feature. But if you must use a sandbox, consider using third-party alternatives such as Sandboxie Plus and SHADE Sandbox. These alternatives offer a similar set of functionalities with no complicated setup involved.


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
<li><a href="https://win11-tips.techidaily.com/unblocking-roblox-availability-tackling-windows-settings-issue/"><u>Unblocking Roblox Availability: Tackling Windows Settings Issue</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-the-6-most-popular-video-editors-for-windows/"><u>New The 6 Most Popular Video Editors for Windows</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-the-most-efficient-ways-to-manage-your-timeline/"><u>New The Most Efficient Ways to Manage Your Timeline</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refining-windows-11-for-superior-usability/"><u>Refining Windows 11 for Superior Usability</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-tips-for-uploading-external-urls-to-ig/"><u>[Updated] Tips for Uploading External URLs to IG</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategy-to-eradicate-error-0x80300024-on-pcs/"><u>Strategy to Eradicate Error 0X80300024 on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-output-with-windows-streamlined-launcher/"><u>Maximize Output with Windows' Streamlined Launcher</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/clear-the-clutter-essential-tiktok-emblem-removers-for-2024/"><u>Clear the Clutter  Essential TikTok Emblem Removers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-windows-11-safe-mode-access/"><u>Step-by-Step Guide to Windows 11 Safe Mode Access</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/ways-to-find-unlocking-codes-for-vivo-y36i-phones-by-drfone-android/"><u>Ways To Find Unlocking Codes For Vivo Y36i Phones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-analysis-creating-and-interpreting-data/"><u>Navigating Windows Analysis: Creating & Interpreting Data</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-guide-to-recording-adobe-presentation-videos/"><u>2024 Approved  Guide to Recording Adobe Presentation Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-laptop-or-desktop-windows-era/"><u>Unveiling Laptop or Desktop Windows Era</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-the-art-of-color-consistency-tips-and-tricks-for-matching-video-clips-in-final-cut-pro/"><u>Updated In 2024, The Art of Color Consistency Tips and Tricks for Matching Video Clips in Final Cut Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-navigation-tips-on-using-narrator-commands/"><u>Streamlining Windows Navigation: Tips on Using Narrator Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-non-operational-amd-radeon-ssp-on-windows/"><u>Troubleshooting Non-Operational AMD Radeon SSP on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-downloading-and-installing-windows-11-arm-from-iso/"><u>Step by Step: Downloading and Installing Windows 11 ARM From ISO</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-right-pace-for-your-cursor-how-to-turn-off-acceleration-win-11/"><u>The Right Pace for Your Cursor: How to Turn Off Acceleration Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-for-generating-flawless-ai-images-on-windows-11-through-paint-tool-sai/"><u>The Ultimate Guide for Generating Flawless AI Images on Windows 11 Through Paint Tool SAI</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-freeing-up-your-screen-time-which-video-player-prevails-vlc-or-mpc/"><u>[Updated] Freeing Up Your Screen Time  Which Video Player Prevails, VLC or MPC?</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/in-2024-public-domain-video-heaven-top-sites-for-free-downloads/"><u>In 2024, Public Domain Video Heaven Top Sites for Free Downloads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformative-troubleshooting-tips-to-ease-team-communication-errors-on-w11/"><u>Transformative Troubleshooting Tips to Ease Team Communication Errors on W11</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-linux-masterclass-comparing-the-best-audio-workflow-tools-available-this-year-for-2024/"><u>New Linux Masterclass Comparing the Best Audio Workflow Tools Available This Year for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-deciphering-instagram-video-glitches-and-finding-silence-free-viewing/"><u>[Updated] 2024 Approved  Deciphering Instagram Video Glitches and Finding Silence-Free Viewing</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-transfer-music-from-itel-p55plus-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Transfer Music from Itel P55+ to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-charting-new-territory-youtubes-revised-policies/"><u>[New] Charting New Territory  YouTube's Revised Policies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-adobes-secrets-ms-store-version-acquisition/"><u>Unlocking Adobe's Secrets: MS Store Version Acquisition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-overcoming-windows-onedrives-cant-add-now-error/"><u>Step-by-Step Guide: Overcoming Windows OneDrive's 'Can’t Add Now' Error</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlock-your-vivo-t2-5g-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>Unlock Your Vivo T2 5G Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-in-device-coexistence-utilize-dex-for-galaxy-on-pc/"><u>Mastery in Device Coexistence: Utilize DeX for Galaxy on PC</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-obs-studio-masterclass-for-ps4-screen-capture/"><u>[New] 2024 Approved  Obs Studio Masterclass for PS4 Screen Capture</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unrivaled-script-authority-place/"><u>In 2024, Unrivaled Script Authority Place</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-how-to-implement-google-meets-grid-view-feature/"><u>[Updated] 2024 Approved  How to Implement Google Meet's Grid View Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-guide-for-outdated-pcs-on-their-way-to-windows-11/"><u>The Guide for Outdated PCs on Their Way to Windows 11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-elevate-video-aesthetics-to-meet-instagram-standards/"><u>[Updated] Elevate Video Aesthetics to Meet Instagram Standards</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/2024-approved-sony-vegas-or-adobe-premiere-pro-which-video-editing-software-is-right-for-you-2023-guide/"><u>2024 Approved Sony Vegas or Adobe Premiere Pro Which Video Editing Software Is Right for You? 2023 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-11-the-8-most-common-mistakes-for-beginners-to-skip/"><u>Navigating Windows 11: The 8 Most Common Mistakes for Beginners to Skip</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-challenges-a-guide-to-fixing-your-manager-tool-in-windows-11/"><u>Navigating Challenges: A Guide to Fixing Your Manager Tool in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterful-video-cutting-solutions-on-your-windows-11-system/"><u>Masterful Video Cutting Solutions on Your Windows 11 System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-of-hyper-v-installation-on-w11-home-systems/"><u>Master the Art of Hyper-V Installation on W11 Home Systems</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-your-pictures-after-p60-has-been-deleted-by-fonelab-android-recover-pictures/"><u>Recover your pictures after P60 has been deleted.</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-appreciative-adjacencies-templates-for-any-spend-plan/"><u>In 2024, Appreciative Adjacencies  Templates for Any Spend Plan</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-cooling-policies-in-microsofts-os-environment/"><u>Navigating Cooling Policies in Microsoft's OS Environment</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-change-vivo-y200e-5g-lock-screen-clock-in-seconds-by-drfone-android/"><u>In 2024, How To Change Vivo Y200e 5G Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://location-social.techidaily.com/does-find-my-friends-work-on-apple-iphone-se-drfone-by-drfone-virtual-ios/"><u>Does find my friends work on Apple iPhone SE | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-pin-removal-functionality-in-windows-11-os/"><u>Restoring PIN Removal Functionality in Windows 11 OS</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/converting-your-clips-into-perfect-instagram-stories-for-2024/"><u>Converting Your Clips Into Perfect Instagram Stories for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-excavate-extravagance-treasure-hunting-maps-ranked-for-2024/"><u>[Updated] Excavate Extravagance  Treasure Hunting Maps Ranked for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-techniques-for-troubled-windows-11-calendars/"><u>Resetting Techniques for Troubled Windows 11 Calendars</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-get-your-game-on-top-10-websites-to-download-games-for-2024/"><u>Updated Get Your Game On Top 10 Websites to Download Games for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-swordsmans-secrets-tackle-windows-lag-in-star-wars-battlefront-2/"><u>Swift Swordsman's Secrets: Tackle Windows Lag in Star Wars Battlefront 2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-your-hard-drives-terrain-a-guide-to-diskusage-in-windows/"><u>Navigating Through Your Hard Drive's Terrain: A Guide to DiskUsage in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methodical-approach-to-reviving-frozen-start-button/"><u>Methodical Approach to Reviving Frozen Start Button</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fixing-foneazy-mockgo-not-working-on-realme-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Fixing Foneazy MockGo Not Working On Realme 12 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-to-implement-without-obstacles-win11-version-22h2-update/"><u>Tactics to Implement Without Obstacles: Win11 Version 22H2 Update</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-revolutionizing-photos-through-automated-hdr-techniques/"><u>In 2024, Revolutionizing Photos Through Automated HDR Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-error-0xc0000142-in-win7win8/"><u>Resolving Error 0XC0000142 in Win7/Win8</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-streamlining-post-editing-the-art-of-vimeos-final-screens/"><u>[Updated] 2024 Approved  Streamlining Post-Editing  The Art of Vimeo's Final Screens</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-perfecting-the-science-of-instagram-highlight-recovery-for-2024/"><u>[New] Perfecting the Science of Instagram Highlight Recovery for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-maximum-speed-for-your-digital-purchases-at-microsoft/"><u>Unlock Maximum Speed for Your Digital Purchases at Microsoft</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quelling-win1011-screen-glitches-with-ease/"><u>Quelling WIN10/11 Screen Glitches with Ease</u></a></li>
</ul></div>
