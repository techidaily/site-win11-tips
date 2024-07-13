---
title: Unmasking Dormant Folders in the Windows 11 UI
date: 2024-07-12T17:20:59.718Z
updated: 2024-07-13T17:20:59.718Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unmasking Dormant Folders in the Windows 11 UI
excerpt: This Article Describes Unmasking Dormant Folders in the Windows 11 UI
keywords: Uncover Dormant Win Folders,Find Hidden Win Files,Expose Dormant Windows Files,Reveal Dormant Windows Folders,Discover Unused Windows Sites,Identify Inactive File Locations,Detect Untouched Windows Spaces
thumbnail: https://thmb.techidaily.com/dde748be235f13590c269ef1d0659f5ed0b11e11e440f8880873d74d5b6083f2.jpg
---

## Unmasking Dormant Folders in the Windows 11 UI

 If you’re running the latest version of Windows 11, the folders in This PC will be hidden by default. That's by design so you can pay more attention to your drives. However, there’s a way you can unhide them so you can access them.

 In this guide, we are going to show you how to add or remove the 3D Objects, Documents, Music, Video, Pictures, and Downloads in This PC by making a few Windows Registry tweaks.

## Before You Start Adding or Removing Folders in This PC…

 We are going to make changes to the Windows Registry by adding keys and values to it using the Registry Editor. To fire it up, press **Win + R** to bring up the Windows Run dialog box, enter **regedit** in the text box, and then click **OK**.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 Before you proceed, we highly recommend reading our guide on [what the Windows Registry is and how to edit it](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) to familiarize yourself with what we will be doing next. Also important is knowing [how to back up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). Considering this is the database that Windows stores the data it needs to operate properly, you will need this backup in case you make an error.

 For showing and hiding folders in This PC to work, make sure you’re running the latest version of Windows 11\. You'll know you have it if File Explorer has tabs.

 With the Registry Editor open, let's get to it.

## How to Show or Hide the 3D Objects Folder in This PC

 For the **3D Objects** folder, you need to add a key to the registry and the folder will pop up in This PC. So, in the address bar of the Registry Editor, enter the below path and then hit the **Enter** key:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace

 Next, right-click the **NameSpace** key in the left panel and select **New > Key**. Then, name that key **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}**. If the name is a bit too hard to type out, just copy and paste it.

![new-key-namespace-regedit-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/new-key-namespace-regedit-windows.jpg)

 Once done, refresh File Explorer by hitting **F5**. Now you will see that the **3D Objects** folder has appeared in This PC.

![3d-objects-this-pc](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3d-objects-this-pc.jpg)

 To remove the folder again, just go back to the Registry Editor, right-click the **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}** key, and select **Delete**. After you refresh File Explorer, the folder will be gone.

## How to Show or Hide the Documents, Music, Videos, Pictures, and/or Downloads Folders in This PC

 To add the **Documents** folder to This PC, enter the below path in the address bar of the Registry Editor and then hit **Enter** on your keyboard to go where its key is located:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{d3162b92-9365-467a-956b-92703aca08af}

 Right-click the **HideIfEnabled** value in the right panel and select **Delete**.

![delete-hideifenabled-value-regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/delete-hideifenabled-value-regedit.jpg)

 Now, refresh File Explorer with **F5** and the **Documents** folder will appear in This PC.

 To hide it, right-click the key on the left panel and select **New > DWORD (32-bit) Value** and name it **HideIfEnabled**. Double-click the newly-created value in the right panel, set **Value data** to **22ab9b9**, and then click **OK**.

![set-hideifenabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-hideifenabled.jpg)

 Now when you refresh This PC in File Explorer, you will see that the **Documents** folder is gone.

 The steps to show or hide the other folders from this point on are the same. Just go to the respective key in the Registry Editor and either delete the **HideIfEnabled** value to show the folder in this PC or create the value and set it to **22ab9b9** to hide the folder.

 Here’s the path to the **Music** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{3dfdf296-dbec-4fb4-81d1-6a3438bcf4de}

 Here’s the path to the **Video** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{f86fa3ab-70d2-4fc7-9c99-fcbf05467f3a}

 Here’s the path to the **Pictures** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{24ad3ad4-a569-4530-98e1-ab02f9417aa8}

 Here’s the path to the **Downloads** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{088e3905-0323-4b02-9826-5d99428e115f}

## Choose the Folders You Want to Appear on This PC in Windows 11

 If you want to see folders on This PC, you can do so by making a couple of edits to the Windows Registry. While we do recommend that you know what you’re doing if you proceed, we have made the instructions relatively simple to follow so there's minimal chance of messing up the registry.

 As long as you take the necessary steps not to mess up the Windows Registry, you should be able to hide and show the folders you want easily.


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
<li><a href="https://win11-tips.techidaily.com/enhancing-productivity-easy-drive-mapping-for-windows-11-users/"><u>Enhancing Productivity: Easy Drive Mapping for Windows 11 Users</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/top-15-augmented-reality-games-like-pokemon-go-to-play-on-meizu-21-drfone-by-drfone-virtual-android/"><u>Top 15 Augmented Reality Games Like Pokémon GO To Play On Meizu 21 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/desktop-configuration-mastery-embedding-this-pc-symbols/"><u>Desktop Configuration Mastery: Embedding 'This PC' Symbols</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-msresourceappname-text-glitch-win11-fix/"><u>Addressing 'MsResource/AppName Text' Glitch, Win11 Fix</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/android-unlock-code-sim-unlock-your-tecno-pova-5-phone-and-remove-locked-screen-by-drfone-android/"><u>Android Unlock Code Sim Unlock Your Tecno Pova 5 Phone and Remove Locked Screen</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-veiled-glance-at-digital-diary-fb/"><u>[Updated] Veiled Glance at Digital Diary (FB)</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-the-ultimate-list-5-best-photo-slideshow-software-for-beginners/"><u>New The Ultimate List 5 Best Photo Slideshow Software for Beginners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-0x00000001-barrier-in-game-access/"><u>Overcoming the 0X00000001 Barrier in Game Access</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-sony-xperia-5-v-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Sony Xperia 5 V to Other Android Devices Devices? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-act-comparing-two-essential-windows-metrics/"><u>Balancing Act: Comparing Two Essential Windows Metrics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-improving-win11-point-accuracy-and-size/"><u>Guide to Improving Win11' Point Accuracy & Size</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-navigating-through-the-sea-of-user-interactions-on-youtube/"><u>[Updated] Navigating Through the Sea of User Interactions on YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-invalid-device-label-in-windows-os/"><u>Correcting 'Invalid Device' Label in Windows OS</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-photos-from-v29-pro-by-fonelab-android-recover-photos/"><u>Possible solutions to restore deleted photos from V29 Pro.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-syncing-on-windows-the-most-rated-apps/"><u>Mastering File Syncing on Windows: The Most Rated Apps</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-boosting-vimeo-playback-speed/"><u>[New] In 2024, Boosting Vimeo Playback Speed</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-in-2024-crop-resize-and-reform-mastering-video-shape-editing/"><u>New In 2024, Crop, Resize, and Reform Mastering Video Shape Editing</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-6-methods-to-protect-yourself-from-location-tracking-on-apple-iphone-13-drfone-by-drfone-virtual-ios/"><u>In 2024, 6 Methods to Protect Yourself from Location Tracking on Apple iPhone 13 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-solve-the-disconnected-from-nvidia-experience-problem-in-win-11/"><u>How to Solve the 'Disconnected From NVIDIA Experience' Problem in Win 11</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-innovative-techniques-for-designing-attractive-vlog-narratives/"><u>[Updated] 2024 Approved  Innovative Techniques for Designing Attractive Vlog Narratives</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-framing-the-future-expert-tips-for-picture-perfection/"><u>2024 Approved  Framing the Future  Expert Tips for Picture Perfection</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-2024-approved-covert-observers-fb-flashbacks-reader/"><u>[New] 2024 Approved  Covert Observers  FB Flashbacks Reader</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/latest-guide-how-to-bypass-itel-p40-frp-without-computer-by-drfone-android/"><u>Latest Guide How To Bypass Itel P40 FRP Without Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-reasons-to-use-the-new-outlook-app-on-windows/"><u>9 Reasons to Use the New Outlook App on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-flashing-display-issues-on-windows-11/"><u>Quick Fix for Flashing Display Issues on Windows 11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-ultimate-toolkit-for-dominating-social-media-management-smm/"><u>2024 Approved  The Ultimate Toolkit for Dominating Social Media Management (SMM)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-errors-a-guide-to-fs-repair-in-win11/"><u>Mending Errors: A Guide to FS Repair in Win11</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-2024-approved-the-only-guide-to-make-2d-rigging-clear-to-you/"><u>Updated 2024 Approved The Only Guide to Make 2D Rigging Clear to You</u></a></li>
<li><a href="https://extra-tips.techidaily.com/prime-portals-select-4k-ready-laptops-for-visionary-artists/"><u>Prime Portals  Select 4K-Ready Laptops for Visionary Artists</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rescue-your-vscode-session-w11/"><u>How to Rescue Your VSCode Session W11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/fresh-set-of-interview-points-for-captivated-ears/"><u>Fresh Set of Interview Points for Captivated Ears</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-15-best-free-mp4-video-rotators-windowsmac-android-iphone-and-online/"><u>New 2024 Approved 15 Best Free MP4 Video Rotators Windows,Mac， Android, iPhone & Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-resolve-defenders-0x80004004-error/"><u>Guide to Resolve Defender's 0X80004004 Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-event-viewer-breakdowns/"><u>Addressing Windows Event Viewer Breakdowns</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-console-management-with-admin-rights/"><u>Mastering Windows Console Management with Admin Rights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-moves-for-unlocking-the-calculator-in-windows-11/"><u>Key Moves for Unlocking the Calculator in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-effortless-transition-in-windows-terminals-attention-mode/"><u>Quick Fix: Effortless Transition in Windows Terminal’s Attention Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-mend-flickering-screens-in-windows-11/"><u>How to Mend Flickering Screens in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cpu-gen-identification-using-eight-proven-windows-methods/"><u>CPU Gen Identification Using Eight Proven Windows Methods</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/10-best-montage-songs-for-your-montage-video/"><u>10 Best Montage Songs for Your Montage Video</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-automate-your-transcriptions-how-to-turn-speech-into-text/"><u>New Automate Your Transcriptions How to Turn Speech Into Text</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-expert-advice-yt-clip-sharing-using-your-google-id/"><u>2024 Approved  Expert Advice  YT Clip Sharing Using Your Google ID</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-gigglegrid-generate-memes-with-ease-and-speed/"><u>In 2024, GiggleGrid  Generate Memes with Ease and Speed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaching-windows-login-restrictions-a-quick-guide/"><u>Breaching Windows Login Restrictions: A Quick Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-sid-retrieval-for-all-users-on-windows-11/"><u>Mastering SID Retrieval for All Users on Windows 11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-path-to-perfect-streams-streamlabs-plus-obs-for-mac-users/"><u>2024 Approved  The Path to Perfect Streams  Streamlabs + OBS for Mac Users</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-the-right-to-appeal-steps-following-abrupt-video-content-suspension-for-2024/"><u>[New] The Right to Appeal  Steps Following Abrupt Video Content Suspension for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-self-scrolled-windows-with-ease-and-precision/"><u>Fix Self-Scrolled Windows with Ease and Precision</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-method-integrating-airpods-with-windows/"><u>Efficient Method: Integrating AirPods with Windows</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-best-video-format-converter-for-pc-and-online-for-2024/"><u>New Best Video Format Converter for PC and Online for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-teamsters-shutdown-on-windows-11-10-systems/"><u>Avoiding Teamsters Shutdown on Windows 11, 10 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-change-easily-altering-nat-settings-in-win1110/"><u>Navigating the Change: Easily Altering NAT Settings in Win11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/administrative-controls-unveiled-windows-11-and-home-edition/"><u>Administrative Controls Unveiled: Windows 11 & Home Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-successfully-unplug-epic-games-from-your-w11-system/"><u>How to Successfully Unplug Epic Games From Your W11 System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-signature-verification-issue-in-winoses/"><u>Eradicating Signature Verification Issue in WinOSes</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-tracking-apps-to-track-meizu-21-pro-without-them-knowing-drfone-by-drfone-virtual-android/"><u>Top 5 Tracking Apps to Track Meizu 21 Pro without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-reinstate-your-devices-access-post-error-22/"><u>Guide to Reinstate Your Device's Access Post Error 22</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-detect-and-remove-spyware-on-oppo-reno-9a-drfone-by-drfone-virtual-android/"><u>How to Detect and Remove Spyware on Oppo Reno 9A? | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-craft-your-cinematic-iphone-footage-creating-and-editing-slow-movement-sequences/"><u>In 2024, Craft Your Cinematic iPhone Footage  Creating & Editing Slow Movement Sequences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-stuttering-challenges-enhancing-warhammer-40k-experience/"><u>Conquer Stuttering Challenges: Enhancing Warhammer 40K Experience</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-oppo-reno-10-5g-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>In 2024, Oppo Reno 10 5G ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-lightweight-browser-ram-usage-with-comparative-tests/"><u>Exploring Lightweight Browser RAM Usage with Comparative Tests</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-save-locations-windows-xp78-errors/"><u>Overcoming Save Locations: Windows XP/7/8 Errors</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-unparalleled-access-8-leading-fb-movie-downloader-list/"><u>2024 Approved  Unparalleled Access  #8 Leading FB Movie Downloader List</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-a-global-keyboard-downloading-windows-fonts/"><u>Crafting a Global Keyboard: Downloading Windows Fonts</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-2024-approved-20-time-saving-adobe-premiere-shortcuts-every-editor-should-know/"><u>New 2024 Approved 20 Time-Saving Adobe Premiere Shortcuts Every Editor Should Know</u></a></li>
</ul></div>
