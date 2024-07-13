---
title: Solving Windows 11'S Ms-Resource and AppError
date: 2024-07-12T17:41:35.946Z
updated: 2024-07-13T17:41:35.946Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solving Windows 11'S Ms-Resource and AppError
excerpt: This Article Describes Solving Windows 11'S Ms-Resource and AppError
keywords: Win11MsResourceError,FixAppErrorWin11,ResolveAppErrorsWindows,TroubleshootWin11Error,Windows11AppFixing,ErrorHandlingWin11,MsResourceErrorSolution
thumbnail: https://thmb.techidaily.com/3d4f10ff7575c64862599f681c5c76c2a7860b5686d5a4ad72e83eea7dc08de2.jpg
---

## Solving Windows 11'S Ms-Resource and AppError

 If you have performed an upgrade recently and noticed a weird "ms-resource:Appname/text" entry in the Start Menu, you are not alone. You may also encounter this error when opening a setting or app.

 This entry in the Start Menu is a trace for a built-in app that has been removed in the successive upgrade. Depending on where you are seeing the error, follow the steps in the article below to resolve this error on your computer.

## 1\. How to Fix the "ms-resource:Appname/Text" Error in the Start Menu

 You can remove the "ms-resource:Appname/Text" entry from the Start Menu by removing the affected application package using PowerShell. Additionally, you can kill the StartMenuExperienceHost.exe process in Task Manager to restart the service.

 Before attempting to remove the app, package, and restart the services, check if you have any Windows updates pending. If you are running a fresh install, try to install all the pending Windows updates. These updates often include bug fixes and may be the only thing you need to do to fix this issue.

![windows 11 update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-update.jpg)

 To check and install Windows updates:

1. Press **Win + I** to open the **Settings** app.
2. Open the **Windows Update** tab.
3. Click on **Check of updates**. Continue to download and install all pending updates.
4. Restart your computer to apply the updates and check if the issue is resolved.

 If the issue persists, you can use PowerShell to remove the affected app package and then restart the associated services to fix the problem.

 To remove the "ms-resource:Appname/Text" entry from the Start Menu:

1. Press the **Win** key and type **powershell**.
2. Right-click on **Windows** **PowerShell** and select **Run as administrator**.  
![remove holographicsfirstrun app powershell windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/remove-holographicsfirstrun-app-powershell-windows.jpg)
3. In the PowerShell window, type the following command and press **Enter**:  
`Get-AppxPackage -all *HolographicFirstRun* | Remove-AppPackage -AllUsers`

 Once you've run the command, be sure to restart your computer.

1. After the computer restarts, [open Task Manager](https://www.makeuseof.com/how-to-access-task-manager-on-windows-11/).
2. Next, open the **Details** tab in Task Manager. On Windows 11, click the three horizontal lines icon to access the details tab.
3. Now you need to locate both **StartMenuExperienceHost.exe** and **Explorer** **.exe**. On Windows 11, you can use the search feature in **Task Manager** to locate the processes.  
![end start menu experience host task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/end-start-menu-experience-host-task-manager.jpg)
4. Right-click on each process and **End Task**.
5. In Task Manager, click **Run new task**. On Windows 10 and older versions, click **File** and select **Run new task**.  
![run new task open tempstate folder file explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-new-task-open-tempstate-folder-file-explorer.jpg)
6. In the **Create new task** dialog, type the following path and click the **Browse** button.  
`%localappdata%\Packages\Microsoft.Windows.StartMenuExperienceHost_cw5n1h2txyewy`
7. In the File Explorer window, delete the **TempState** folder.
8. Go back to Task Manager, and click **Run new task**.
9. Type **explorer.exe** and select the **Create this task with administrative privileges** option.

 Once done, give your PC another restart.

## 2\. Re-Register Your Microsoft Store Apps

 You can [re-register Microsoft Store apps using PowerShell](https://www.makeuseof.com/reregister-microsoft-store-apps-windows/) to stop the error appearing when using Microsoft apps. Doing so should remove any leftover entries showing up in the Start Menu after the update.

 Wait for the process to complete. This may take a few minutes as the command will try to re-register all the apps, including existing ones. Once the process is complete, restart your computer and check for any improvements.

## 3\. Check the Microsoft Store for App Updates

 You may see the "ms-resource:Appname/Text" entry if Windows attempted an unsuccessful app installation. To fix the issue, check if an update exists for the app in the Microsoft Store.

 To determine the app name click on the app entry and check if you can find any information about the app. If not, right-click on the app entry in the **Start Menu** and select **Open File Location**.

![view application folder windows 11 run shell apps folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/view-application-folder-windows-11-run-shell-apps-folder.jpg)

 Alternatively, you can view the application directory to view the installed apps. Press **Win + R** to open Run, type **shell:appsfolder**, and click **OK**. It will open the **Applications** folder. Go through the apps to see if you can locate an app named **ms-resource:Appname/Text** or similar to the entry in the Start Menu.

 Once you have the app name, open the Microsoft Store. Search for the app and check if an update exists. Click **Update** to download and install the update. Once installed, restart your computer and check for any improvements.

## What if the "Ms-resource:Appname/Text" Error Appears When Launching an App?

 At times, you may encounter this error when opening a built-in Microsoft Store app. In this instance, you can run the Microsoft Store apps troubleshooter to fix the issue. Here are a few additional troubleshooting steps to fix this error when launching an app.

## 4\. Run the Microsoft Store Apps Troubleshooter
![The Run button for the Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-run-button-for-the-app-troubleshooter.jpg)

 You can use the built-in Microsoft Store Apps troubleshooter to fix issues with the store apps. Here’s how to do it.

1. Press **Win + I** to open **Settings**.
2. In the **System** tab, scroll down and click on **Troubleshoot**.
3. Next, click on **Other troubleshooters**.
4. Click the **Run** button for **Windows Store Apps**. Wait for the troubleshooter to launch and follow the on-screen instructions. It will scan your system against the common Microsoft Store app issues. Apply any recommended fixes and restart your computer to see if the issue is resolved.

 If you don’t see a Windows Store App troubleshooter option, you are likely running a newer version of the OS without this option. In this instance, try to repair the Microsoft Store app.

## 5\. Repair the Microsoft Store App
![repair microsoft store windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/repair-microsoft-store-windows-11.jpg)

 If the Windows Store Apps troubleshooter is missing or didn’t help, try to repair the Microsoft Store App. You can use the built-in repair option to find and fix common issues with the official app store.

 To repair the Microsoft Store app:

1. Press **Win + I** to open the **Settings** app.
2. Open the **Apps** tab and click on **Installed Apps.**
3. Locate and click the **three-dots** menu beside the **Microsoft Store** app.
4. Select **Advanced Options**.
5. Scroll down to the **Reset** section.
6. Click the **Repair** button, wait for the process to complete, and show a checkmark. If the repair is successful, restart your computer.

### Reset the Microsoft Store App

 In addition to performing a repair, you can also reset the Microsoft Store app to resolve common issues with the store apps. You can perform a reset from the Advanced Options section. Before that, run the wsreset.exe tool to clear the store cache to see if that helps.

 To reset the Microsoft Store App cache:

![wsreset.exe command in the Run tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsreset-exe-command.jpg)

1. Press **Win + R** to open the **Run** dialog.
2. Type **wsreset.exe** and click **OK**.

 Still not resolved? Try to [perform a Microsoft Store reset](https://www.makeuseof.com/windows-10-11-reset-microsoft-store/). Doing so will delete all app data, and you may need to sign in to your Microsoft account again.

## 6\. Other Troubleshooting Steps You Can Try

 If the issue persists, here are a few additional troubleshooting steps you can follow:

1. **Create a new user account** – Try to [create a new local user account](https://www.makeuseof.com/windows-11-create-local-user-account/) to see if the error exists in the new account. This is a handy workaround for a newly set up Windows computer.
2. **Perform a repair reinstall of Windows 11** – You can reinstall [Windows 11 without deleting your apps and files](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/). This is an upgrade reinstall and should fix any issues triggered due to issues with the system files.
3. **Perform a reset** – If an in-place upgrade doesn’t help, consider [performing a factory reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/). You can perform a complete reset while choosing to keep your files, but all your apps will be removed.
4. **Clean install** – [Performing a Windows clean install](https://www.makeuseof.com/how-to-clean-install-windows-11/) will erase everything on your computer and reinstall Windows 11 from scratch. Make sure to back up important data before attempting a clean install.

## Fixing the "ms-resource:Appname/Text" Error in Windows 11

 Often this entry in the start menu is a ghost entry from an unsuccessful or leftover installation of a Microsoft app. To remove the entry or restore the app, you can re-register the Microsoft app, remove the affected app package or run the Windows Store Apps Troubleshooter.

 If the issue persists, an in-place upgrade, factory reset, or a clean install may be necessary to resolve the issue. This is a time-consuming process, and you may need to set up your computer from scratch.

 This entry in the Start Menu is a trace for a built-in app that has been removed in the successive upgrade. Depending on where you are seeing the error, follow the steps in the article below to resolve this error on your computer.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-tips-to-find-the-best-videographer/"><u>[Updated] 2024 Approved  Tips to Find The Best Videographer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-your-personalized-mixer-settings-after-crashes/"><u>Reinstating Your Personalized Mixer Settings After Crashes</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-journey-to-certified-status-achieving-discord-partner-authenticity-for-2024/"><u>[Updated] Journey to Certified Status  Achieving Discord Partner Authenticity for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719311785872-fix-crashing-file-explorer-on-windows-11-now/"><u>Fix Crashing File Explorer on Windows 11 Now!</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-global-gastronomy-hits-on-tiktok/"><u>In 2024, Global Gastronomy Hits on TikTok</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-resolve-slowness-issues-of-a-windows-printer/"><u>Swiftly Resolve Slowness Issues of a Windows Printer</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-how-to-fake-gps-on-android-without-mock-location-for-your-infinix-smart-7-drfone-by-drfone-virtual/"><u>In 2024, How to Fake GPS on Android without Mock Location For your Infinix Smart 7 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-stabilizing-inconsistent-windows-printers/"><u>Steps for Stabilizing Inconsistent Windows Printers</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/primepickings-top-twitters-and-top-viewers-favorites/"><u>PrimePickings  Top Twitters & Top Viewers’ Favorites</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unraveling-cuts-in-imovie-size-modification-mystery/"><u>[New] Unraveling Cuts in iMovie  Size Modification Mystery</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-laughter-on-your-phone-humorous-ringtone-sites/"><u>[New] Laughter on Your Phone  Humorous Ringtone Sites</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-top-rated-imovie-alternatives-for-android-devices/"><u>New Top-Rated iMovie Alternatives for Android Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-the-stopped-netflix-app-in-windows/"><u>Reviving the Stopped Netflix App in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-device-to-windows-microphone-setup/"><u>Android Device to Windows Microphone Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaim-your-network-nirvana-a-guide-to-the-top-6-ways-to-mend-network-hardware-in-windows/"><u>Reclaim Your Network Nirvana: A Guide to the Top 6 Ways to Mend Network Hardware in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-mastering-delete-confirmation-options/"><u>Windows: Mastering Delete Confirmation Options</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-cross-platform-video-editing-made-easy-a-chromebook-users-guide/"><u>Updated In 2024, Cross-Platform Video Editing Made Easy A Chromebook Users Guide</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-ultimate-selection-non-advertising-android-recording-tools/"><u>[Updated] In 2024, Ultimate Selection  Non-Advertising Android Recording Tools</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-unlocking-the-best-8-no-charge-powerful-3d-video-tools/"><u>[Updated] Unlocking The Best 8 No-Charge, Powerful 3D Video Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-11s-cloud-storage-functionality/"><u>Streamlining Windows 11'S Cloud Storage Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-action-for-resolving-missing-msconfig-in-windows-1011/"><u>Swift Action for Resolving Missing MSCONFIG in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-9-methods-resolving-wwe-2k23-freeze-in-windows-11/"><u>Top 9 Methods: Resolving WWE 2K23 Freeze in Windows 11</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-6-best-nft-makers-for-artists-to-unleash-imagination/"><u>2024 Approved  6 Best NFT Makers for Artists to Unleash Imagination</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/theme-it-right-top-5-winter-scenes-as-video-bgs/"><u>Theme It Right  Top 5 Winter Scenes as Video Bgs</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-creating-hilarious-reactions-mastering-youtube-tricks-3-methods/"><u>[Updated] In 2024, Creating Hilarious Reactions  Mastering YouTube Tricks (3 Methods)</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-beginners-journey-into-podcasting-making-sounds-count-using-audacity/"><u>New In 2024, Beginners Journey Into Podcasting Making Sounds Count Using Audacity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-pre-vista-password-recall-on-w10w11/"><u>Addressing the “Pre-Vista Password Recall on W10/W11”</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-file-transfer-via-winrar-6-corrective-steps-for-sums/"><u>Secure File Transfer via WinRAR: 6 Corrective Steps for Sums</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-steam-ui-error-on-windows-os-platform/"><u>Mending Steam UI Error on Windows OS Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-restrictions-and-unlocking-full-ram-potential/"><u>Overcoming Restrictions and Unlocking Full RAM Potential</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-a-detailed-vpna-fake-gps-location-free-review-on-honor-90-gt-drfone-by-drfone-virtual-android/"><u>In 2024, A Detailed VPNa Fake GPS Location Free Review On Honor 90 GT | Dr.fone</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-unleash-the-experience-top-9-streams/"><u>2024 Approved  Unleash the Experience  Top 9 Streams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719237818540-trouble-with-compatibility-try-these-straightforward-fixes-now/"><u>Trouble with Compatibility? Try These Straightforward Fixes Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-locate-missing-ubisoft-game-launcher/"><u>Solutions to Locate Missing Ubisoft Game Launcher</u></a></li>
<li><a href="https://win11-tips.techidaily.com/alter-subnet-configurations-in-windows-11/"><u>Alter Subnet Configurations in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-epic-gaming-on-pc-by-solving-login-glitches/"><u>Unlock Epic Gaming on PC by Solving Login Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-resolving-unreachable-device-error-on-pc/"><u>Quick Guide: Resolving Unreachable Device Error on PC</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-craft-stellar-channels-best-10-apps-for-artistic-banner-design/"><u>In 2024, Craft Stellar Channels  Best 10 Apps for Artistic Banner Design</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-upgrade-or-downgrade-iphone-15-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade iPhone 15 Without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-infinix-smart-8-hd-drfone-by-drfone-virtual-android/"><u>In 2024, A Detailed Guide on Faking Your Location in Mozilla Firefox On Infinix Smart 8 HD | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-streamlining-meetings-integrate-slack-and-filmora-effortlessly/"><u>2024 Approved  Streamlining Meetings  Integrate Slack & Filmora Effortlessly</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-picture-puns-smilesketchers-for-2024/"><u>[New] Picture Puns  SmileSketchers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncover-the-windows-11s-system32-folder-way/"><u>Uncover the Windows 11'S System32 Folder Way</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-step-by-step-strategies-for-altering-voices-in-tiktok-content-creation/"><u>In 2024, Step-by-Step Strategies for Altering Voices in TikTok Content Creation</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-precision-editing-unveiled-harnessing-the-potential-of-ps-background-erasure-feature/"><u>[New] Precision Editing Unveiled  Harnessing the Potential of PS Background Erasure Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-zoom-correction-for-error-1132/"><u>Windows 11 Zoom Correction for Error 1132</u></a></li>
<li><a href="https://win11-tips.techidaily.com/routes-to-success-system32-on-windows-11/"><u>Routes to Success: System32 on Windows 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/reel-in-quality-essential-audio-devices-for-podcast-producers/"><u>Reel in Quality  Essential Audio Devices for Podcast Producers</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-shaping-perceptions-expert-strategies-for-photoshop-distortions/"><u>[New] Shaping Perceptions  Expert Strategies for Photoshop Distortions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-tricks-to-overcome-pin-failures-in-win10win11/"><u>Quick Tricks to Overcome PIN Failures in Win10/Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-utility-tips-efficiently-handling-archived-files/"><u>Windows Utility Tips: Efficiently Handling Archived Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-youre-overlooking-with-low-priced-activation-keys/"><u>What You're Overlooking with Low-Priced Activation Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-superuser-access-challenges/"><u>Tackling Windows' Superuser Access Challenges</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-expert-tips-for-crafting-immersive-soundscapes-in-youtube/"><u>[New] Expert Tips for Crafting Immersive Soundscapes in YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/returning-the-windows-11-search-bar-to-an-icon-style/"><u>Returning the Windows 11 Search Bar to an Icon Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-your-digital-desktop-top-5-apps-for-customizable-clock-screen-savers-on-windows/"><u>Upgrade Your Digital Desktop: Top 5 Apps for Customizable Clock Screen Savers on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-update-fresh-start-procedure/"><u>Windows Update Fresh Start Procedure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-regain-normal-colors-of-microsoft-shop/"><u>Methods to Regain Normal Colors of Microsoft Shop</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-combining-sounds-and-visuals-a-guide-to-blending-video-and-audio-for-2024/"><u>New Combining Sounds & Visuals A Guide to Blending Video and Audio for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-pc-gaming-with-yuzu-on-windows/"><u>Skyrocket PC Gaming with Yuzu on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pioneer-productivity-mass-folder-creation-on-modern-windows-systems/"><u>Pioneer Productivity: Mass Folder Creation on Modern Windows Systems</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/n-2024-mastering-morning-tweets-essential-rules-and-prohibitions/"><u>[New] In 2024, Mastering Morning Tweets  Essential Rules & Prohibitions</u></a></li>
</ul></div>
