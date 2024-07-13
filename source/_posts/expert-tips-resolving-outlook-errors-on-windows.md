---
title: "Expert Tips: Resolving Outlook Errors on Windows"
date: 2024-07-12T16:50:02.031Z
updated: 2024-07-13T16:50:02.031Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Expert Tips: Resolving Outlook Errors on Windows"
excerpt: "This Article Describes Expert Tips: Resolving Outlook Errors on Windows"
keywords: Fix Outlook Errors,Outlook Troubleshoot Windows,Solve Outlook Issues,Outlook Problem Remedies,Outlook Repair Guide,Windows Outlook Fix Tips,Resolving Outlook Errors
thumbnail: https://thmb.techidaily.com/85a7b59f6ebac3b02742cde59cd187960869a90caaaa91e9c7ebf00da17adc0d.jpg
---

## Expert Tips: Resolving Outlook Errors on Windows

 Microsoft Outlook's somewhat vague "Something went wrong" error message may appear when you are trying to set up your account or using the app in general. Without a clear indication of what’s going wrong, fixing such Outlook errors can be tricky.

 To help out, we have listed all the possible ways to fix the “Something went wrong” error in Outlook for Windows.

## 1\. Edit Registry Files

 Autodiscover is a nifty feature that allows Outlook to automatically configure email account settings without requiring manual input from the user. If this service receives any unexpected results from the third-party web server, Outlook might display the "Something went wrong" error message. To resolve this, you will need to make a few changes to the registry files on your PC.

 As you may be aware, making incorrect changes to the registry files can render your system inoperable. Hence, it is advisable to [back up all of your registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Press **Win + R** to open the Run dialog box.
2. Type **regedit** in the box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Paste the following path in the address bar at the top and press **Enter** to quickly navigate to the **AutoDiscover** key.  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Office\XX.0\Outlook\AutoDiscover`  
 Replace **XX.0** in the above path with your version of Office (**16.0** \= Office 365, Office 2019, and Office 2016, **15.0** \= Office 2013).
5. Right-click on the **AutoDiscover** key and select **New > DWORD (32-bit) Value**.  
![Create DWORD in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-dword-in-registry.jpg)

1. Rename the DWORD to **ExcludeHttpsRootDomain**.
2. Double-click the newly created DWORD and set its value to **1**.
3. Right-click on the **AutoDiscover** key again and select **New > DWORD (32-bit) Value**. Name the DWORD **ExcludeHttpsAutoDiscoverDomain**.
4. Double-click the **ExcludeHttpsAutoDiscoverDomain** DWORD and set its value to **1**.
5. Create two more DWORD values named **ExcludeSrvRecord** and **ExcludeLastKnownGoodUrl** and set their values to **1**.  
![AutoDiscover in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/autodiscover-in-registry-editor.jpg)

 Restart your PC after this and check if you still get the “Something went wrong” error in Microsoft Outlook.

## 2\. Open Outlook in Safe Mode

 At times, third-party add-ins in Outlook can disrupt app processes and trigger such errors. To verify if this is the case, you can [try starting Outlook in safe mode](https://www.makeuseof.com/outlook-safe-mode/).

 If Outlook works as expected, it means one of your add-ins is causing the issue. To find the culprit, you'll need to disable all the add-ins and re-enable them one at a time. Here are the steps for the same.

1. In the Outlook app, click on **File > Options**.
2. In the **Outlook Options** window, select the **Add-ins** tab from the left sidebar.
3. Click the **Go** button next to **COM Add-ins**.
4. Clear all the checkboxes to disable your add-ins and then click **OK**.  
![Disable Outlook Add-Ins-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-outlook-add-ins-1.jpg)

 Restart the Outlook app and enable your add-ins one by one until the error occurs again. Once you find the troublesome add-in, consider removing it to avoid such issues.

## 3\. Clear the Outlook Cache

 Outdated or corrupted cache data can cause Outlook to misbehave and display unusual errors. If this is the cause of your problems, clearing the Outlook app cache should get things going again. To do so, use these steps:

1. Press **Win + R** to open the Run command (see [how to open the Windows Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more information).
2. Type **%localappdata%\\Microsoft\\Outlook** in the text box and press **Enter**.
3. In the **RoamCache** folder that opens, press **Ctrl + A** to select all the files, and click the **trash** icon at the top to delete them.  
![Delete Outlook Cache Data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-outlook-cache-data.jpg)

## 4\. Repair Your Outlook Profile

 Another reason why you may get the “Something went wrong” error in Outlook is if there is an issue with your Outlook profile. You can try repairing your Outlook profile to see if that restores normalcy. Here are the steps for the same.

1. Open the Outlook app and click the **File** menu at the top.
2. In the Info tab, click on **Account Settings** and select **Account Settings**.
3. Select your profile under the **Email** tab and click **Repair**.  
![Repair Outlook Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-outlook-account.jpg)

 Allow Outlook to repair your profile and then restart the app.

## 5\. Remove and Re-Add Your Account

 If repairing your Outlook profile does not help, your next best option is to remove your email account from the Outlook app and add it back. Here's how to do it.

1. Open the Outlook app.
2. Navigate to **File > Info > Account Settings > Account Settings**.
3. Under the **Email** tab, select your account and click **Remove**.
4. Select **Yes** to continue.  
![Remove Outlook Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/remove-outlook-account.jpg)

 Once removed, click the **New** option under the **Email** tab and set up your account again.

## 6\. Remove Outlook Password From Credential Manager

 Are you getting the "Something went wrong" error while adding an account in Outlook? That might be caused by outdated data in the [Credential Manager](https://www.makeuseof.com/windows-credential-manager-guide/). You can try removing any Outlook entries from the Credential Manager to fix the issue.

1. Click the **magnifying icon** on the taskbar.
2. Type **credential manager** in the box and select the first result that appears.
3. Select **Windows Credentials**.
4. Select the entry related to your account and click **Remove**.  
![Remove Outlook Credentials From Windows PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/remove-outlook-credentials-from-windows-pc.jpg)

## 7\. Run the Office Repair Tool

 Running Microsoft’s Office repair tool is an effective way to resolve issues with Office apps like Outlook. So, if the above tips don't help, you can run the Office repair tool as a last resort.

1. Press **Win + S** to open the search menu.
2. Type **Control Panel** in the box and press **Enter**.
3. Click the drop-down menu in the top right corner to select **Large icons**.
4. Click on **Programs and Features**.
5. Select **Microsoft Office suite** on the list and click the **Change** button at the top.
6. Select the **Quick Repair** option.
7. Click the **Repair** button.  
![Repair Microsoft Office](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/repair-microsoft-office.jpg)

 If the problem persists even after this, repeat the above steps to perform an **Online Repair**. This process may take a little longer, but it’s most likely to resolve the issue.

## Fixing Outlook's “Something Went Wrong” Error on Windows

 Encountering such errors in the Outlook app can affect your productivity and leave you frustrated. We hope that the solutions listed above have helped in resolving the “Something went wrong” error in Microsoft Outlook.

 That said, if all of the above tips prove ineffective, we recommend you contact the official Microsoft support team for further assistance.

 To help out, we have listed all the possible ways to fix the “Something went wrong” error in Outlook for Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-eyedome-xtreme-ultimate-os-video-snapper/"><u>In 2024, EyeDome Xtreme  Ultimate OS Video Snapper</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-strategies-windows-voice-logging/"><u>Step-by-Step Strategies: Windows Voice Logging</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-uncover-and-attend-to-hidden-storage/"><u>How to Uncover and Attend to Hidden Storage?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-completely-reskin-windows-11-for-a-nostalgic-windows-98-look/"><u>How to Completely Reskin Windows 11 for a Nostalgic Windows 98 Look</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-guide-to-microsofts-phone-link-features/"><u>The Essential Guide to Microsoft's 'Phone Link' Features</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-gopro-hero-vs-yi-4k-which-takes-the-prize-in-latest-tech/"><u>[New] GoPro Hero Vs. Yi 4K  Which Takes the Prize in Latest Tech?</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-tips-and-tricks-for-apple-id-locked-issue-from-iphone-13-pro-by-drfone-ios/"><u>In 2024, Tips and Tricks for Apple ID Locked Issue From iPhone 13 Pro</u></a></li>
<li><a href="https://some-techniques.techidaily.com/expert-selections-unveiling-the-top-5-professional-drones-for-2024/"><u>Expert Selections  Unveiling the Top 5 Professional Drones for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-immediate-folder-upload-tackling-onedrive-errors/"><u>Mastering Immediate Folder Upload: Tackling OneDrive Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-multitasking-enhancing-windows-11-widget-capabilities/"><u>Streamlining Multitasking: Enhancing Windows 11 Widget Capabilities</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-enhance-playstation-2-experience-top-5-android-emulators-for-2024/"><u>[New] Enhance PlayStation 2 Experience  Top 5 Android Emulators for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/capture-and-share-the-new-era-of-screen-recorders-on-spring-for-2024/"><u>Capture and Share  The New Era of Screen Recorders on Spring for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-writing-game-wins-finest-tools/"><u>Elevate Your Writing Game – Win's Finest Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-eradicate-wows-fatal-issue-132-in-win-1011/"><u>Strategies to Eradicate WoW's Fatal Issue #132 in Win 10/11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-change-lock-screen-wallpaper-on-realme-10t-5g-by-drfone-android/"><u>How to Change Lock Screen Wallpaper on Realme 10T 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-solve-pin-verification-issues-on-w11w10-pcs/"><u>Strategies to Solve PIN Verification Issues on W11/W10 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stabilize-cease-persistent-file-explorer-opens/"><u>Stabilize: Cease Persistent File Explorer Opens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mobile-file-access-via-windows-server/"><u>Mobile File Access via Windows Server</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/mavericks-video-converter-edit-and-convert-mp4-files-with-ease-for-2024/"><u>Mavericks Video Converter Edit and Convert MP4 Files with Ease for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-in-2024-innovative-approaches-to-video-voiceover-integration/"><u>[New] In 2024, Innovative Approaches to Video Voiceover Integration</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/new-how-to-make-a-flv-photo-slideshow/"><u>New How to Make a FLV Photo Slideshow</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-premiere-pro-2023-importing-editing-and-exporting-videos-for-beginners/"><u>New Premiere Pro 2023 Importing, Editing, and Exporting Videos for Beginners</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-10-best-youtube-music-reaction-video-and-how-to-make-one/"><u>[Updated] In 2024, 10 Best YouTube Music Reaction Video & How to Make One</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revising-the-start-page-to-a-new-preference-in-win11/"><u>Revising the Start Page to a New Preference in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-streamline-note-taking-with-win-11-display-rules/"><u>How to Streamline Note-Taking with Win 11 Display Rules</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-part-of-the-touch-screen-not-working-on-realme-narzo-n55-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Part of the Touch Screen Not Working on Realme Narzo N55 | Dr.fone</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/2024-approved-video-splitting-made-easy-a-step-by-step-guide-for-windows-live-movie-maker/"><u>2024 Approved Video Splitting Made Easy A Step-by-Step Guide for Windows Live Movie Maker</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dxvk-transforming-windows-gaming-experience-for-the-better/"><u>DXVK: Transforming Windows Gaming Experience for the Better</u></a></li>
<li><a href="https://extra-tips.techidaily.com/strategize-and-succeed-a-stepwise-approach-to-impactful-reddit-sharing/"><u>Strategize & Succeed  A Stepwise Approach to Impactful Reddit Sharing</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-picshots-secrets-easy-peasy-collage-formation/"><u>In 2024, Picshot's Secrets  Easy-Peasy Collage Formation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breakthrough-programs-facilitating-switch-from-mac-to-windows/"><u>Breakthrough Programs Facilitating Switch From MAC to WINDOWS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/finding-lightweight-browsers-for-chromeoswindowsmacos-ram-and-cpu-wise/"><u>Finding Lightweight Browsers for ChromeOS/Windows/macOS: RAM & CPU-Wise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/icon-position-correction-made-simple/"><u>Icon Position Correction Made Simple</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-your-system-ready-for-windows-11-with-our-top-3-usb-tips/"><u>Get Your System Ready for Windows 11 with Our Top 3 USB Tips</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-awesome-free-apps-to-transform-your-mobile-images/"><u>[Updated] Awesome FREE Apps to Transform Your Mobile Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-picks-optimal-pomodoro-timers-tailored-for-windows-users/"><u>Top Picks: Optimal Pomodoro Timers Tailored For Windows Users</u></a></li>
<li><a href="https://some-approaches.techidaily.com/transformative-voice-techniques-enhance-your-oratory-with-these-tools-for-2024/"><u>Transformative Voice Techniques – Enhance Your Oratory with These Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-function-keys-actions-on-windows-1011/"><u>Adjusting Function Keys' Actions on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-device-disconnection-dxgi-error-guide/"><u>Overcoming Device Disconnection: DXGI Error Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-comparison-dissecting-key-differences-between-local-and-microsoft-logins-in-os/"><u>In-Depth Comparison: Dissecting Key Differences Between Local & Microsoft Logins in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instructions-to-bring-back-old-school-search-in-windows-11/"><u>Instructions to Bring Back Old-School Search in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-basics-to-brilliance-elevating-your-windows-experience-via-ms-store/"><u>From Basics to Brilliance: Elevating Your Windows Experience via MS Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-reactivate-the-default-folder-cooking-a-comprehensive-guide/"><u>Methods to Reactivate the Default Folder' Cooking: A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-start-wordpad-in-a-windows-desktop/"><u>How to Start WordPad in a Windows Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-the-most-effective-win-video-codecs/"><u>Demystifying the Most Effective Win Video Codecs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-prolong-pin-length-for-enhanced-safety/"><u>Tips to Prolong PIN Length for Enhanced Safety</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-solving-sync-issues-between-cameras-and-obs/"><u>In 2024, Solving Sync Issues Between Cameras and OBS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinventing-win11s-configuration-interface/"><u>Reinventing Win11's Configuration Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disentangling-stacked-icons-on-operating-system-ui/"><u>Disentangling Stacked Icons on Operating System UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-order-in-windows-registry-through-repair-methods/"><u>Restoring Order in Windows Registry Through Repair Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/should-you-block-yourphoneexe-on-home-editions/"><u>Should You Block YourPhone.exe on Home Editions?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-future-microsofts-copilot-key-and-windows-11-revolution/"><u>Navigating the Future: Microsoft's Copilot Key and Windows 11 Revolution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-app-experience-win11-color-automation/"><u>Tailoring Your App Experience: Win11 Color Automation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-definitive-guide-to-configuring-script-policies-in-ps/"><u>The Definitive Guide to Configuring Script Policies in PS</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-experience-the-next-wave-watching-fb-live-on-roku/"><u>[Updated] In 2024, Experience the Next Wave  Watching FB Live on Roku</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-in-depth-analysis-of-sharex-criticism-and-replacements/"><u>In 2024, In-Depth Analysis of ShareX  Criticism & Replacements</u></a></li>
<li><a href="https://extra-hints.techidaily.com/crafting-a-seamless-gift-discovery-journey/"><u>Crafting a Seamless Gift Discovery Journey</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-windows-from-tracking-your-apps/"><u>Stop Windows From Tracking Your Apps</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-expert-tips-to-master-camera-snap-in-zoom-calls/"><u>[Updated] In 2024, Expert Tips to Master Camera Snap in Zoom Calls</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-tips-and-tricks-for-recording-ps3-games-with-flawless-results-for-2024/"><u>[Updated] Tips and Tricks for Recording PS3 Games with Flawless Results for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-download-youtubes-best-moments-without-full-streaming-for-2024/"><u>[Updated] Download YouTube's Best Moments Without Full Streaming for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-the-complete-guide-to-zooms-top-free-and-paid-transcribers-for-virtual-meetings/"><u>In 2024, The Complete Guide to Zoom's Top Free & Paid Transcribers for Virtual Meetings</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-text-animation-made-easy-top-mobile-video-editing-apps/"><u>New In 2024, Text Animation Made Easy Top Mobile Video Editing Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-vmware-crashes-a-guide-for-win11-users/"><u>Overcoming VMware Crashes: A Guide for Win11 Users</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/rethink-your-classic-movies-best-swaps-7-for-2024/"><u>Rethink Your Classic Movies - Best Swaps #7 for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-discover-the-best-online-video-editors-for-adding-music/"><u>Updated 2024 Approved Discover the Best Online Video Editors for Adding Music</u></a></li>
<li><a href="https://android-location-track.techidaily.com/best-anti-tracker-software-for-tecno-spark-20-proplus-drfone-by-drfone-virtual-android/"><u>Best Anti Tracker Software For Tecno Spark 20 Pro+ | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidance-on-resolving-windows-software-initiation-flaw-error/"><u>Guidance on Resolving Windows Software Initiation Flaw (Error)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-different-ways-to-tailor-windows-11-search/"><u>Explore Different Ways to Tailor Windows 11 Search</u></a></li>
</ul></div>
