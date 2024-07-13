---
title: How to Fix the Printmanagement.msc Not Found Error on Windows
date: 2024-07-12T17:12:00.885Z
updated: 2024-07-13T17:12:00.885Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the Printmanagement.msc Not Found Error on Windows
excerpt: This Article Describes How to Fix the Printmanagement.msc Not Found Error on Windows
keywords: Windows Printfix,MSC Error Resolution,Cure PrintManagementError,Windows TroubleshootMsc,FixingPrintManagerFailure,ResolveWindowsPrintIssue,CorrectMsCNotFound
thumbnail: https://thmb.techidaily.com/fe4b0191212c8e41c031bf23c61d1f9123e35ac3bb319d7b6d127b4e0747eef8.jpg
---

## How to Fix the Printmanagement.msc Not Found Error on Windows

 Print management on Windows is a central way to manage your printers and printing options. You can use print management to control which users have access to printers, as well as set printing preferences such as paper size and quality. However, sometimes you may find the print management console missing from your computer. In most cases, the problem occurs after updating Windows to the latest version.

Here are some potential solutions to help you resolve the issue.

## 1\. Restart Your Computer

 If you're getting an error when trying to open Printmanagement.msc, try restarting your computer. This might fix the problem if it's simply a glitch.

## 2\. Add the Print Management Feature Manually

 In case restarting doesn't work, open the Start menu and search for "Printmanagement.msc". If it doesn't show up in the search results, it seems that the Print Management feature isn't installed on your computer. In that case, you will have to manually add it. To do that, follow these steps:

1. Right-click on Start and select**Settings** from the Power User menu.
2. Select**Apps** from the left side of the Settings window.
3. In the right pane, click on**Optional features** .  
![Installing Print Management Via Optional Feature](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Installing-Print-Management-Via-Optional-Feature.jpg)
4. Next to "Add an optional feature", click**View features** .  
![Add an optional feature](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Add-an-optional-feature.jpg)
5. Search for "Print Management" in the next dialog box.
6. Once you find it, click on the**Print Management** checkbox.
7. Click**Next > Install** to add the feature.  
![Install Print Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Install-Print-Management.jpg)

 The process will take a while, so after it has been added, you can check that the problem still exists. If yes, try the next solution on the list.

## 3\. Clear the Printer Spooler Files

 Windows uses a print spooler to manage all the print jobs that are waiting to be sent to your printer. Over time, the spooler can fill up with old or corrupt files, which can cause errors. So, if you're getting an error when trying to open Printmanagement.msc, it might be because your print spooler is full.

 To fix this, you'll need to clean out the print spooler. Here's how to clean it out and get things working again.

1. Click on the**Start** menu and search for "Services."
2. Select the result at the top of the list.
3. In the Services window, scroll down and search for "Print Spooler."
4. Once you find the application, double-click on it to open the**Properties** window.
5. On the "General" tab, check if the "Service status" is**Running** . If yes, click the**Stop** button to stop it.  
![Stop Print Spooler application](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Stop-Print-Spooler-application.jpg)

1. When you are done making changes, click**OK** to save them.
2. Now press**Win + I** on your keyboard to [open the Run Command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
3. Type**%WINDIR%\\system32\\spool\\printers** in the dialog box and press Enter.  
![Open Print Spooler files](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Open-Print-Spooler-files.jpg)
4. If this is your first time opening this folder, you may be prompted that you don't have permission to access it. Click**Continue** to grant permanent access to this folder.
5. On the following screen, select and delete all contents of the folder.
6. Now go back to Services and open the Print Spooler Properties window.
7. Click the**Start** button to run the Service status. Also, make sure the "Startup type" dropdown menu is set to**Automatic** .  
![Start Print Spooler application](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Start-Print-Spooler-application.jpg)
8. Finally, click**Apply** and then**OK** to save the changes.

 If you have done all the steps above, it should fix the problem. If not, try the next solution.

## 4\. Run SFC and DISM Scan

 If Print Management goes missing on Windows due to corruption of system files, the next course of action is to run DISM (Deployment Image Servicing and Management) and SFC (System File Checker). It scans all protected system files and replaces corrupted files with cached copies that are stored in compressed formats.

The steps below will guide you through running DISM and SFC scans:

1. Click the Start menu and search for "Command Prompt."
2. Right-click on the search result and select**Run as administrator** .
3. If UAC appears on the screen, click**Yes** to open the Command Prompt as an administrator.  
![SFC and DISM Scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/SFC-and-DISM-Scan.jpg)
4. Type the following command in the Command Prompt window and hit Enter:  
`sfc /scannow`

It may take some time for the scan to complete, so please be patient.

 After the SFC scan is complete, run Deployment Image Servicing and Management to repair corrupted system images and restore system files. The steps are as follows:

* Run Command Prompt as an administrator. If you need help with this, see [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
* Type the following command into the command prompt and press Enter:  
`DISM /Online /Cleanup-Image /ScanHealth  
Dism.exe /online /cleanup-image /restorehealth`

 The process may take some time to complete. After you have executed the DISM command, restart your computer to see if the problem has been resolved.

## 5\. Update the Printer Driver

 If you still can't get it to work, it's likely that the printer driver you're using is outdated. In that case, updating your printer driver will solve the problem for you.

To update your printer driver, follow these steps:

1. Right-click Start and select**Device Manager** . Alternatively, you can also use the Run command to open it. For this, press**Win + R** , type "devmgmt.msc," and press**Enter** .
2. In Device Manager, find your printer under the "Print queues" category.
3. Now right-click on your printer driver and choose**Update driver** from the context menu.  
![Update Printer driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Update-Printer-driver.jpg)
4. If you're prompted to choose how you want to search for drivers, select "Search automatically for drivers." Windows will then search for and install the latest drivers for your printer.

 Once the drivers have been updated, try opening Print Management again. The "Printmanagement.msc not found" error should now be fixed. If updating your printer driver doesn't fix the problem, you can also try uninstalling and reinstalling your printer.

## 6\. Check For Windows Update

 An outdated Windows operating system can often result in printmanagement.msc error messages. So, if you continue to have this problem, Windows Update may help.

To run Windows Update, follow these steps:

1. Press**Win + I** on your keyboard to open System Settings.
2. Scroll down and click**Windows Update** in the left pane.
3. Click**Check for updates** on the right to see if there are any updates.
4. If new updates are available, they will begin downloading automatically.
5. Once the update has been completed, restart your computer and check if it resolves your issue.

## Print Management Should Now Be Available

 Having printer-related issues on your computer is common, but fortunately, the information above will help you resolve them. If none of these solutions work, you can try restoring Windows to an earlier point. This will revert any recent changes that might have caused the printmanagement.msc file to go missing.


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
<li><a href="https://tiktok-clips.techidaily.com/unlock-tiktoks-secrets-with-7-must-have-charms-and-clandestine-messages/"><u>Unlock TikTok's Secrets with #7 Must-Have Charms and Clandestine Messages</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-exploring-the-capabilities-of-avs-audio-software-a-deep-dive-into-features-ratings-and-options-for-2024/"><u>New Exploring the Capabilities of AVS Audio Software – A Deep Dive Into Features, Ratings, and Options for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mystery-of-0x80072f8f-on-pcs/"><u>Unraveling the Mystery of 0X80072f8f on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-the-battle-defeating-file-extraction-error-1152-in-windows/"><u>Winning the Battle: Defeating File Extraction Error 1152 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stealth-mode-for-windows-11-apps/"><u>Stealth Mode for Windows 11 Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-expert-guide-to-opening-credential-vaults/"><u>The Expert Guide to Opening Credential Vaults</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncluttered-desktop-organize-and-personalize-win11/"><u>Uncluttered Desktop: Organize and Personalize Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/selecting-top-tier-nvidia-drivers-focusing-on-purpose/"><u>Selecting Top-Tier Nvidia Drivers - Focusing on Purpose</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-itel-p55-5g-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Itel P55 5G Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-language-access-using-keyboard-shortcuts-for-translation-on-windows/"><u>Quick Language Access: Using Keyboard Shortcuts for Translation on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/wsls-role-in-boosting-linux-desktops/"><u>WSL's Role in Boosting Linux Desktops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/suspending-windows-update-activations/"><u>Suspending Windows Update Activations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-combat-low-usb-controller-space/"><u>Strategies to Combat Low USB Controller Space</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-application-launch-failure-the-0xc000003e-error-on-windows-11/"><u>Solving Application Launch Failure: The 0XC000003E Error on Windows 11</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-iphone-15-with-a-mask-on-drfone-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 15 with a Mask On | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-ascend-video-rankings-top-seo-gadgets-revealed/"><u>[New] In 2024, Ascend Video Rankings – Top SEO Gadgets Revealed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tricks-for-a-larger-windowed-pin-display-in-win-11/"><u>Tricks for a Larger Windowed Pin Display in Win 11</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-optimize-your-mac-a-step-by-step-guide-to-reclaiming-storage-for-fcpx/"><u>Updated In 2024, Optimize Your Mac A Step-by-Step Guide to Reclaiming Storage for FCPX</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-exclusive-leaderboard-luminary-youtube-videographers-guide/"><u>[New] In 2024, Exclusive Leaderboard Luminary  YouTube Videographer's Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-photo-gallery-functions-on-windows-pc/"><u>Unlocking Photo Gallery Functions on Windows PC</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-airdrop-not-working-how-to-fix-it-on-iphone-ipad-and-mac-for-2024/"><u>[Updated] Airdrop Not Working, How to Fix It on iPhone, iPad, & Mac for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-process-system-isnt-responding-error-on-honor-90-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Process System Isnt Responding Error on Honor 90 | Dr.fone</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-maximize-your-iphone-xs-selfie-potential-top-free-apps/"><u>2024 Approved  Maximize Your iPhone X's Selfie Potential - Top Free Apps</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-from-clips-to-classrooms-harnessing-youtubes-potential-for-teaching/"><u>[Updated] 2024 Approved  From Clips to Classrooms  Harnessing YouTube's Potential for Teaching</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-shaded-world-of-microsofts-simple-scribbler/"><u>The Shaded World of Microsoft's Simple Scribbler</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-cricket-iphone-15-for-free-by-drfone-ios/"><u>In 2024, How To Unlock Cricket iPhone 15 for Free</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-split-display-frustrations-in-windows/"><u>Overcoming Split Display Frustrations in WIndows</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-great-tips-on-converting-text-to-mp3-for-2024/"><u>New Great Tips on Converting Text to MP3 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-ensuring-reliable-intel-wireless-networks-in-windows/"><u>Techniques: Ensuring Reliable Intel Wireless Networks in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-unresponsive-video-driver-in-windows-1110/"><u>Solutions for Unresponsive Video Driver in Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switch-viewing-direction-on-windows-device/"><u>Switch Viewing Direction on Windows Device</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-mastering-your-podcast-sound-with-these-10-premier-audio-editing-software-options-free-or-paid-for-2024/"><u>New Mastering Your Podcast Sound with These 10 Premier Audio Editing Software Options (Free or Paid) for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-elevate-your-content-premier-youtube-rank-tracker-apps/"><u>[Updated] 2024 Approved  Elevate Your Content  Premier YouTube Rank Tracker Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-using-dism-with-win11-system-recovery/"><u>The Ultimate Guide to Using Dism with Win11 System Recovery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-file-stewardship-streamlining-googledrive-and-dropbox-via-windows-c/"><u>Swift File Stewardship: Streamlining GoogleDrive & Dropbox via Windows C</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-maximizing-hd-quality-fb-live-broadcast-tips/"><u>[Updated] 2024 Approved  Maximizing HD Quality  FB Live Broadcast Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-stuck-grammarly-service-on-pcs/"><u>Reactivating Stuck Grammarly Service on PCs</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-it-oppo-find-x6-pro-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix It Oppo Find X6 Pro Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-1011-automate-heic-to-jpeg-images/"><u>Win 10/11: Automate HEIC to JPEG Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-skyrims-x-script-on-pc/"><u>Troubleshooting Skyrim's X-Script on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prime-protection-top-rated-windows-encryption-programs-153-chars/"><u>Prime Protection: Top-Rated Windows Encryption Programs (153 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shades-of-twilight-harnessing-ms-paints-dark-theme/"><u>Shades of Twilight: Harnessing MS Paint's Dark Theme</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-windows-on-steam-deck-made-simple/"><u>Setting Up Windows on Steam Deck Made Simple</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-picture-perfection-picart-guide-to-pristine-image-editing/"><u>[New] Picture Perfection  PicArt Guide to Pristine Image Editing</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-push-past-limitations-showcase-videos-in-social-media/"><u>[New] Push Past Limitations  Showcase Videos in Social Media</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-command-attention-on-instagram-nine-paths-to-social-media-glory/"><u>[Updated] Command Attention on Instagram  Nine Paths to Social Media Glory</u></a></li>
</ul></div>
