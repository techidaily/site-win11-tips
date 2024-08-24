---
title: Secrets to Clean Up and Free Your PC in Windows
date: 2024-08-23T07:07:42.070Z
updated: 2024-08-24T07:07:42.070Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Secrets to Clean Up and Free Your PC in Windows
excerpt: This Article Describes Secrets to Clean Up and Free Your PC in Windows
keywords: Clean PC Windows,PC Detox Guide,Remove Windows Junk,Optimize Windows,Delete Unwanted Files,Windows Deep Clean,Free Windows Clutter
thumbnail: https://thmb.techidaily.com/05c8c6fd73c6fec22a2f538188954b893a706bcf3ee5edf935baeb75dd083d47.jpg
---

## Secrets to Clean Up and Free Your PC in Windows

 Temporary files, as the name implies, aren’t meant to stick around on your Windows computer forever. Although Windows makes it simple to delete temporary files, there can be times when these files refuse to leave.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

## 1\. Use the Disk Cleanup Tool

[Windows offers several options for clearing temporary files](http://www.makeuseof.com/windows-11-delete-temporary-files/) on your PC. If you are unable to delete temporary files via the Settings app or File Explorer, try using the Disk Cleanup tool instead.

 Here are the steps you can follow:

1. Press **Win + S** to access the search menu.
2. Type **disk cleanup** in the box and press **Enter**.
3. Use the drop-down menu to select the drive from which you want to clear temporary files.
4. Click **OK**.
5. Under **Files to delete**, use the checkboxes to select the files you want to remove.
6. Click **OK** to proceed.
7. Click the **Delete Files** to confirm.  
![Delete Temp Files Using Disk Cleanup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-disk-cleanup.jpg)

 Wait for a few moments until the Disk Cleanup tool clears all the temporary files.

## 2\. Use Command Prompt

 If the Disk Cleanup utility fails to delete some or all of the temporary files on Windows, you can try using the Command Prompt instead. Don’t worry, the process isn’t as complex as it might sound.

 Follow these steps to continue:

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt appears.
3. Copy and paste the following command into the console and hit **Enter**.  
del /q /f /s %temp%\* && del /s /q C:\Windows\temp\*  
![Delete Temp Files Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-command-prompt.jpg)

 Wait for the above command to run and delete the temporary files.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Empty the SoftwareDistribution Folder

 Windows saves all the downloaded update files in the SoftwareDistribution folder before installing them. If a [Windows system update gets stuck](https://www.makeuseof.com/tag/windows-update-stuck/), the OS will not delete the temporary files associated with it.

 To fix this, you can try emptying the SoftwareDistribution folder manually using these steps:

1. Press **Win + S** to open the search menu.
2. Type **services** in the box and press **Enter**.
3. In the Services window, locate the **Windows Update** service. Right-click on it and select **Stop**.
4. Press **Win + R** to open the Run dialog box.
5. Type the following path in the text field and hit **Enter**.  
C:\Windows\SoftwareDistribution\Download
6. In the File Explorer window, press **Ctrl + A** to select all the files and click the **trash icon** at the top to delete them.
7. Return to the Services window, right-click on the **Windows Update** service, and select **Start**.  
![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/clear-softwaredistribution-folder.jpg)

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you run into issues while emptying the SoftwareDistribution folder, you can [force delete files in Windows](https://www.makeuseof.com/windows-11-delete-stubborn-files/) using Command Prompt or a third-party tool.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Edit Registry Files

 By default, the Disk Cleanup utility does not delete temporary files that are less than seven days old. This is because Windows marks these files as active. However, if you want to delete all the temporary files, regardless of their age, you can make changes to the Windows Registry.

 Since editing registry files is slightly risky, make sure to [back up all registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) as a precaution. Once done, follow these steps to edit registry files:

1. Press **Win + R** to open the Run dialog box.
2. Type **regedit** in the box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer > VolumeCaches > Temporary Files**.
5. In the right pane, double-click the **LastAccess** key.
6. Enter **0** in the Value data field.
7. Click **OK**.  
![Edit DWORD in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-dword-in-registry.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
 Restart your PC after this and try to delete temporary files once again.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Boot Into Safe Mode

 It's possible that a third-party program or background service is preventing Windows from erasing temporary files on your system. Booting your PC in safe mode can help you avoid any interference, as Windows will only run with essential drivers and services.

 Use one of the many ways to [boot into safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) and try to delete temporary files one more time.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
## Get Rid of Temporary Files on Windows

 Clearing temporary files is a great way to free up storage space without deleting any of your apps or important data.

 We hope that one of the above tips was helpful and you were able to delete the temporary files without any problems.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-videos.techidaily.com/new-conquer-youtube-creator-studio-a-comprehensive-guide/"><u>[New] Conquer YouTube Creator Studio  A Comprehensive Guide</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-essential-editing-software-for-horizontal-and-vertical-igtv/"><u>[New] Essential Editing Software for Horizontal & Vertical IGTV</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-solution-for-twitter-videos-not-playing-in-chrome/"><u>[New] Solution for Twitter Videos Not Playing in Chrome</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-the-swift-video-voyage-navigating-through-the-youtubes-and-tiktok-landscapes/"><u>[New] The Swift Video Voyage  Navigating Through the YouTubes and TikTok Landscapes</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-from-canvas-to-crypto-top-7-artwork-conversion-platforms/"><u>[Updated] From Canvas to Crypto  Top 7 Artwork Conversion Platforms</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-how-to-streamline-your-vimeo-video-subtitles/"><u>[Updated] How to Streamline Your Vimeo Video Subtitles</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-maximize-impact-sharing-youtube-videos-on-social-media-fb/"><u>[Updated] In 2024, Maximize Impact  Sharing YouTube Videos on Social Media (FB)</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-perfecting-the-art-of-ppt-delivery-via-google-meet-any-device/"><u>[Updated] Perfecting the Art of PPT Delivery via Google Meet (Any Device)</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-uncompromised-zoom-audio-two-key-techniques-revealed-for-2024/"><u>[Updated] Uncompromised Zoom Audio  Two Key Techniques Revealed for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-chortlechamber-personalize-everyday-humor-online/"><u>2024 Approved  ChortleChamber  Personalize Everyday Humor Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-proxies-on-windows-11-pc/"><u>Configuring Proxies on Windows 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-update-nomenclature-windows-edition/"><u>Deciphering Update Nomenclature: Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/determining-ideal-hibernation-on-windows-machines/"><u>Determining Ideal Hibernation on Windows Machines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-your-ideal-windows-11-drawing-software-choices/"><u>Discover Your Ideal Windows 11 Drawing Software Choices</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/does-samsung-galaxy-f14-5g-support-avchd-video-by-aiseesoft-video-converter-play-mts-on-android/"><u>Does Samsung Galaxy F14 5G support AVCHD video?</u></a></li>
<li><a href="https://extra-hints.techidaily.com/echoes-expanse-a-compreshift-of-best-speech-to-text-applications/"><u>Echoes Expanse  A Compreshift of Best Speech-to-Text Applications</u></a></li>
<li><a href="https://win-solutions.techidaily.com/effortless-fixes-stop-windows-control-issues-in-their-tracks/"><u>Effortless Fixes: Stop Windows Control Issues in Their Tracks!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-run-command-keeps-activities-recorded/"><u>Ensuring Run Command Keeps Activities Recorded</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-security-in-free-apps-for-windows-os/"><u>Ensuring Security in Free Apps for Windows OS</u></a></li>
<li><a href="https://extra-hints.techidaily.com/erase-youtubes-short-snippet-playback-option/"><u>Erase YouTube's Short Snippet Playback Option</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/essential-techniques-for-making-and-tweaking-multi-snap-chats/"><u>Essential Techniques for Making & Tweaking Multi-Snap Chats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-fix-team-share-on-pc/"><u>Guide to Fix Team Share on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harmonize-windows-and-android-6-syncing-apps-to-elevate-your-experience/"><u>Harmonize Windows and Android: 6 Syncing Apps to Elevate Your Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-out-of-video-memory-error-in-hogwarts-legacy-on-windows/"><u>How to Fix the Out of Video Memory Error in Hogwarts Legacy on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reinstate-dormant-windows-update-protocols/"><u>How To Reinstate Dormant Windows Update Protocols</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-5-quick-methods-to-bypass-infinix-smart-8-hd-frp-by-drfone-android/"><u>In 2024, 5 Quick Methods to Bypass Infinix Smart 8 HD FRP</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-best-spy-watches-for-your-oneplus-nord-n30-se-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Best Spy Watches For your OnePlus Nord N30 SE | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-webcam-recorder-reviews-unlocking-your-video-potential/"><u>In 2024, Webcam Recorder Reviews - Unlocking Your Video Potential</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/intercept-non-requested-youtube-video-alerts/"><u>Intercept Non-Requested YouTube Video Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/investigating-the-ideal-state-of-windows-pcs/"><u>Investigating the Ideal State of Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-gif-resizing-obstacles-a-quick-fix-guide-to-win11s-issues/"><u>Navigating Through GIF Resizing Obstacles: A Quick Fix Guide to Win11's Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfecting-windows-11-defense-adding-customizable-filter-options-to-context-menu/"><u>Perfecting Windows 11 Defense: Adding Customizable Filter Options to Context Menu</u></a></li>
<li><a href="https://printer-issues.techidaily.com/preventative-measures-against-spooler-shutdowns-win/"><u>Preventative Measures Against Spooler Shutdowns (Win)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proven-methods-for-determining-your-devices-identification-through-windows/"><u>Proven Methods for Determining Your Devices’ Identification Through Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-access-tip-push-gmail-to-top-of-windows-desktop/"><u>Quick Access Tip: Push Gmail to Top of Windows Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefining-assistance-four-new-options-post-cortana/"><u>Redefining Assistance: Four New Options Post-Cortana</u></a></li>
<li><a href="https://win11-tips.techidaily.com/replaying-rarieties-retro-gaming-in-dosbox-x/"><u>Replaying Rarieties: Retro Gaming in DOSBox-X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shift-windows-display-orientation-easily/"><u>Shift Windows Display Orientation Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simple-techniques-for-finding-hidden-gpeditmsc/"><u>Simple Techniques for Finding Hidden Gpedit.msc</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-your-tasks-with-notetaking-techniques-for-w11w10/"><u>Simplify Your Tasks with Notetaking Techniques for W11/W10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speed-up-windows-11-remedies-for-laggy-performance/"><u>Speed Up Windows 11: Remedies for Laggy Performance</u></a></li>
<li><a href="https://sound-issues.techidaily.com/squad-mic-malfunction-solutions-and-tips-for-gamers-edition/"><u>Squad Mic Malfunction Solutions & Tips for Gamers - Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-windows-from-prompting-for-updates/"><u>Stop Windows From Prompting for Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-prevent-changes-in-windows-time-settings/"><u>Techniques to Prevent Changes in Windows Time Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-six-essentials-for-restoring-frozen-menu-functions/"><u>The Six Essentials for Restoring Frozen Menu Functions</u></a></li>
<li><a href="https://buynow-info.techidaily.com/top-cheap-cams-to-buy-before-2024/"><u>Top Cheap Cams to Buy Before 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-read-only-recovery-on-windows-11-folders/"><u>Troubleshooting Read-Only Recovery on Windows 11 Folders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-share-issue-on-geforce-experience/"><u>Troubleshooting Share Issue on GeForce Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncover-top-6-must-have-usage-trackers-on-windows-machines/"><u>Uncover Top 6 Must-Have Usage Trackers on Windows Machines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-hidden-outlook-folders-on-pc-a-step-by-step-guide/"><u>Unlocking Hidden Outlook Folders on PC: A Step-by-Step Guide</u></a></li>
<li><a href="https://tech-haven.techidaily.com/untangle-the-windows-11-setup-knot-a-comprehensive-guide-to-fixing-error-code-80240020/"><u>Untangle the Windows 11 Setup Knot: A Comprehensive Guide to Fixing Error Code 80240020</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-disk-management-secrets-insightful-guide-win-1011/"><u>Unveiling Disk Management Secrets: Insightful Guide (Win 10/11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-silent-workers-stopping-windows-apps/"><u>Unveiling Silent Workers: Stopping Windows Apps</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/unveiling-smooth-audioshifting-tricks-in-adobe-premiere/"><u>Unveiling Smooth Audioshifting Tricks in Adobe Premiere</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-and-its-disappearing-drive-letters-analysis-and-remedial-strategies/"><u>Windows and Its Disappearing Drive Letters: Analysis & Remedial Strategies</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/your-personal-playlist-on-the-go/"><u>Your Personal Playlist On-the-Go</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>