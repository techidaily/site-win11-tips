---
title: Retrieving Lost Actions From WinRunHist
date: 2024-07-12T16:34:58.893Z
updated: 2024-07-13T16:34:58.893Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Retrieving Lost Actions From WinRunHist
excerpt: This Article Describes Retrieving Lost Actions From WinRunHist
keywords: WinRunHist Recovery,Action Retrieval WinR-H,Restore WinRun Hist Actions,WinRunLostActions Fix,WinRunHistory Cleanup,WinRun Hist Errors Resolve,WinRunRestore Missing Actions
thumbnail: https://thmb.techidaily.com/09d90f71aa46b1fd9d4bcc7810bb203ff9683f8d93c042d20e109ab131454cc4.jpg
---

## Retrieving Lost Actions From WinRunHist

 The Run command dialog box in Windows makes it easy to launch apps, access system tools, and perform various other tasks. It also has an auto-complete feature that makes it easy to re-use your commands later. However, the auto-complete feature in the Run tool may not work if it fails to save your command history in the first place.

 If you're encountering a similar problem, don’t fret. Below, we share some quick and useful tips that should get the Run tool to save your history once again.

## 1\. Check Your Privacy Settings

 A common reason why Windows may not save the Run command history is if you have previously blocked it from tracking your app launches. Here’s how you can change that.

1. Press **Win + I** to open the Settings app.
2. Select **Privacy & security** from the left sidebar.
3. Under Windows permissions, click on **General**.
4. Enable the toggle next to **Let Windows improve Start and search results by tracking app launches**.  
![Allow Windows to Track App Launches on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-windows-to-track-app-launches-on-windows.jpg)

 After completing the above steps, try running a few commands via the Run dialog box. Then, check if it is saving your command history and providing auto-complete suggestions.

## 2\. Edit Registry Files

 Is the **Let Windows improve Start and search results by tracking app launches** option grayed out on your PC? If so, you can take help from the Registry Editor to get Windows to save your Run command history.

 As you may already be aware, registry files on your PC store essential settings for Windows and its services. Making incorrect modifications to these files can render your system inoperable. Hence, it’s a good idea to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Click the search icon on the taskbar or press the **Win + S** keyboard shortcut to open the search menu.
2. Type **registry editor** in the search box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer > Advanced**.
5. Locate the **Start\_TrackProgs** entry in the right pane. If you can’t find it, right-click on the **Advanced** key and select **New > DWORD (32-bit) Value**. Rename it to **Start\_TrackProgs**.
6. Double-click the newly created DWORD and enter **1** in the **Value data** field.
7. Click **OK**.  
![Edit Registry DWORD on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-registry-dword-on-windows.jpg)

 Restart your PC after this for the changes to take effect. Following this, the Run command should start saving your history on Windows.

## 3\. Apply Generic Fixes

 If the problem persists even after implementing the above tips, you can try applying some basic fixes to resolve the underlying issue.

* **Restart Your PC:** This may appear rudimentary, but temporary OS-related glitches can sometimes cause such anomalies. If it’s nothing major, [restarting your PC](https://www.makeuseof.com/windows-restart-methods/) should fix any issues with the Run command.
* **Run an SFC Scan:** Such issues can also arise if some of the critical system files on your PC are corrupt. [Running a System File Checker (SFC) scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) can help detect and repair any damaged system files on your PC.
* **Scan for Malware:** It’s possible that your system is infected by malware, which is why the Run command is having trouble saving your history. To rule out this possibility, you can [scan Windows for malware using PowerShell](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/) or Windows Defender.

## Get the Run Tool to Save Your History on Windows

 It can be inconvenient if the Run command dialog box stops saving your history on Windows. Hopefully, one of the solutions provided above has successfully resolved the issue for you.

 If you feel that the Run utility in Windows lacks advanced features, you can always switch to alternative tools like Run-Command or PowerToys Run.

 If you're encountering a similar problem, don’t fret. Below, we share some quick and useful tips that should get the Run tool to save your history once again.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/addressing-non-unified-sticky-note-syncing-on-win11/"><u>Addressing Non-Unified Sticky Note Syncing on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719380036891-dual-virus-defense-think-again-windows-users/"><u>Dual Virus Defense? Think Again, Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-empty-pages-in-the-explorer-bar/"><u>Addressing Empty Pages in the Explorer Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-operational-windows-keyboard-entry/"><u>Addressing Non-Operational Windows Keyboard Entry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-approach-to-mastering-windows-law-filters/"><u>A Practical Approach to Mastering Windows LAW Filters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-guide-to-recognizing-and-addressing-uninstalled-disk-issue-win-11-style/"><u>A Practical Guide to Recognizing & Addressing 'Uninstalled Disk' Issue, Win 11 Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-perfection-in-window-management-via-alomware/"><u>Achieving Perfection in Window Management via AlomWare</u></a></li>
<li><a href="https://some-skills.techidaily.com/template-transformations-build-unique-logos-for-pennies-for-2024/"><u>Template Transformations  Build Unique Logos for Pennies for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-essential-fixes-for-unresponsive-windows-family-safety/"><u>5 Essential Fixes for Unresponsive Windows Family Safety</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-system-load-in-win11/"><u>Accelerate System Load in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-ram-problems-in-windows-systems-using-vmware/"><u>Addressing RAM Problems in Windows Systems Using VMware</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719268063873-ensuring-complete-screen-images-with-snip-and-sketch-tips/"><u>Ensuring Complete Screen Images with Snip & Sketch Tips</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/2024-approved-visual-anonymous-how-to-make-faces-and-objects-invisible/"><u>2024 Approved  Visual Anonymous  How to Make Faces and Objects Invisible</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-issue-of-battlenet-not-opening-windows/"><u>Addressing the Issue of Battle.net Not Opening Windows</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-vibrant-video-vibes-merging-melodies-with-media/"><u>2024 Approved  Vibrant Video Vibes  Merging Melodies with Media</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-uncovering-non-google-ar-accessories-and-tools/"><u>In 2024, Uncovering Non-Google AR Accessories and Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-restoring-lost-functionality-to-your-windows-tablet-pens/"><u>A Guide: Restoring Lost Functionality to Your Windows Tablet Pens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-phased-out-features-in-current-windows-design/"><u>6 Phased-Out Features in Current Windows Design</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-navigating-the-legal-landscape-check-tiktok-video-compliance/"><u>[Updated] Navigating the Legal Landscape  Check TikTok Video Compliance</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-watch-hulu-outside-us-on-apple-iphone-13-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Watch Hulu Outside US On Apple iPhone 13 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-simplified-approach-to-windows-odbc-data-management/"><u>A Simplified Approach to Windows ODBC Data Management</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-the-secrets-to-attractive-profile-videos-for-2024/"><u>[New] The Secrets to Attractive Profile Videos for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-game-changers-explore-top-10-gaming-bloggers-for-2024/"><u>[Updated] Game Changers  Explore Top 10 Gaming Bloggers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-plan-for-installing-win11-version-22h2-updater/"><u>A Step-by-Step Plan for Installing WIN11 Version 22H2 Updater</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/unlock-your-boost-mobile-apple-iphone-se-2022-before-the-plan-expires-by-drfone-ios/"><u>Unlock Your Boost Mobile Apple iPhone SE (2022) Before the Plan Expires</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-spooler-service-error-on-windows-systems/"><u>Addressing Spooler Service Error on Windows Systems</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-insta-vibes-music-trends-unveiled/"><u>[New] In 2024, Insta Vibes  Music Trends Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-misaligned-windows-thx-listening-experience/"><u>Addressing Misaligned Windows THX Listening Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-functional-automation-rules-on-desktop/"><u>Addressing Non-Functional Automation Rules on Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719300675775-localize-chatgpt-on-pc-free-and-simple-with-gpt4all/"><u>Localize ChatGPT on PC - Free & Simple With GPT4All</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-to-organizing-your-w11-space/"><u>A Step by Step Approach to Organizing Your W11 Space</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-pinnacle-community-standards-on-youtube/"><u>[Updated] Pinnacle Community Standards on YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-error-another-app-uses-same-speaker-windows-edition/"><u>Addressing Error: Another App Uses Same Speaker, Windows Edition</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-professional-acid-pro-analysis-and-substitutes/"><u>In 2024, Professional ACID Pro Analysis and Substitutes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719296840588-end-of-year-sale-windows-10-starting-at-an-insanely-low-612/"><u>End of Year Sale: Windows 10, Starting at an Insanely Low $6.12!</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/enhancing-user-experience-recovering-lost-youtubefb-videos-for-2024/"><u>Enhancing User Experience  Recovering Lost YouTube/FB Videos for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-optimizing-tasks-in-teams-with-these-8-social-media-apps/"><u>[Updated] In 2024, Optimizing Tasks in Teams with These 8 Social Media Apps</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-gigglegraphics-suite/"><u>In 2024, GiggleGraphics Suite</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-breaking-down-the-process-of-adding-fonts-to-ae-projects/"><u>In 2024, Breaking Down the Process of Adding Fonts to AE Projects</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-youtube-growth-secrets-masterful-narration-techniques/"><u>[New] In 2024, YouTube Growth Secrets  Masterful Narration Techniques</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/cutting-edge-techniques-for-youtube-thumbnails-made-for-macos/"><u>Cutting-Edge Techniques for YouTube Thumbnails, Made for macOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-high-savings-harness-the-power-of-w11-pro-discounts/"><u>Achieve High Savings: Harness the Power of W11 Pro Discounts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-disappearing-badge-icons/"><u>Addressing Disappearing Badge Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-fix-notepad-not-opening-on-windows/"><u>7 Ways to Fix Notepad Not Opening on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-incorrect-side-by-side-setup-on-windows-os/"><u>Addressing 'Incorrect Side-by-Side Setup' On Windows OS</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-unlocking-potential-an-in-depth-look-at-vivocut-editing/"><u>[Updated] In 2024, Unlocking Potential  An In-Depth Look at VivoCut Editing</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/cultivating-a-thriving-business-model-with-snapchat-insights/"><u>Cultivating a Thriving Business Model with Snapchat Insights</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-beyond-zoom-the-intricacies-of-iphone-xs-lens-tech/"><u>2024 Approved  Beyond Zoom  The Intricacies of iPhone X's Lens Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-absent-file-application-linkages-in-win10/"><u>Addressing Absent File Application Linkages in Win10</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-flawless-coexistence-of-linktree-and-tiktok-biographies/"><u>2024 Approved  Flawless Coexistence of Linktree and TikTok Biographies</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/unlocking-potential-switch-pro-controller-on-steam/"><u>Unlocking Potential  Switch Pro Controller on Steam</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-app-on-motorola-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to Recover Deleted Photos from Android Gallery App on Motorola</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-11-free-apps-to-check-imei-on-vivo-y27-5g-phones-by-drfone-android/"><u>Top 11 Free Apps to Check IMEI on Vivo Y27 5G Phones</u></a></li>
<li><a href="https://extra-hints.techidaily.com/sony-bdp-s3700-review-for-2024/"><u>Sony BDP- S3700 Review for 2024</u></a></li>
</ul></div>
