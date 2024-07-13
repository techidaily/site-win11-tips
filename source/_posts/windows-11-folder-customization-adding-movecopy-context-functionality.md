---
title: Windows 11 Folder Customization - Adding Move/Copy Context Functionality
date: 2024-07-12T17:39:43.659Z
updated: 2024-07-13T17:39:43.659Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Windows 11 Folder Customization - Adding Move/Copy Context Functionality
excerpt: This Article Describes Windows 11 Folder Customization - Adding Move/Copy Context Functionality
keywords: Windows 11 Folder Trim,Win11 Move/Copy Actions,Folder Shell Ext Addon,Custom Folder Controls,Context Menu Editing Win11,Enhance Windows Explorer,Optimize File Management Win11
thumbnail: https://thmb.techidaily.com/178e67f42d6ae355b4752027c9ad22197720cab14f0cfafff04bedca8cb4afb0.jpg
---

## Windows 11 Folder Customization - Adding Move/Copy Context Functionality

 You may frequently need to move or copy files to alternative folders in Windows. To do this, you might move files to different folders by dragging and dropping them. To copy a file to another location, you can either hold the**Ctrl** key while dragging or utilize the copy-paste hotkeys.

 It would be better to have context menu options for moving and copying files to selected locations. Then you could right-click a file and select a**Move to folder** or**Copy to folder** option. This is how you can add context menu options for moving and copying files to folders in Windows 11/10.

## How to Add a Move to Folder Context Menu Option

 To add new context menu options in Windows 11/10, you must tweak the [Windows registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) one way or another. The Registry Editor app enables users to customize Windows’ right-click menus by manually tweaking the registry. You can add a Move to folder option to the context menu with the Registry Editor as follows:

1. Bring up the Registry Editor with a method included in our [how to open regedit](https://www.makeuseof.com/windows-11-open-registry-editor/) guide.
2. Click inside the address bar at the top of Registry Editor, and erase the current key location there.
3. Then enter this**ContextMenuHandlers** key location and press**Return** :  
`HKEY_CLASSES_ROOT\AllFilesystemObjects\shellex\ContextMenuHandlers`
4. Next, right-click**ContextMenuHandlers** and select the**New** submenu.
5. Click**Key** on the submenu.  
![The New and Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-key-option.jpg)

1. Enter**Move to folder** for the new key’s name.
2. Select the new**Move to folder** key in the Registry Editor’s sidebar.
3. Double-click the**(Default)** string for the selected key.
4. Input**{C2FBB631-2971-11D1-A18C-00C04FD75D13}** inside the**Value data** box.  
![The value data for the Move to folder key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/an-edit-string-window.jpg)
5. Select**OK** to set the new value for the (Default) string.
6. Exit the Registry Editor.

 You can now try out the new**Move to folder** option on the context menu. Press the**Explorer** taskbar button to view the Windows file manager. Right-click a file and select the new**Move to folder** option. You’ll need to select**Show more options** \>**Move to folder i** n Windows 11.

![The Move to folder option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/move-to-folder-context-menu-option.jpg)

 A small Move Items window will then appear from which you can select a destination folder. Choose a folder to move the file to in that window. Then click**Move** to place the file in the selected directory.

![The Move Items window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/move-items-window.jpg)

## How to Add a Copy to Folder Context Menu Option

 The Windows context menu includes a**Copy** option, but that doesn’t enable you to select a destination for pasting the file. Thus, users must manually paste copied items into different folders after selecting that option. However, you can add a better**Copy to folder** context menu option that brings up a destination folder selection window like this:

1. Open the**ContextMenuHandlers** registry key as covered in the first three steps for adding a**Move to** folder option.
2. Click the**ContextMenuHandlers** with the right mouse button and select its New option.
3. Select**Key** to add a new one to the registry.
4. Type**Copy to folder** inside the text box for the new key.  
![The Copy to folder key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-folder-option-1.jpg)
5. Select**Copy to folder** and double-click its**(Default)** string.
6. Enter the value**{C2FBB630-2971-11D1-A18C-00C04FD75D13}** inside the**Data** box.  
![The value data for the Copy to folder key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-edit-string-window-for-the-copytokey.jpg)
7. Click the**OK** button to apply the value.
8. Close the Registry Editor app’s window.

 Then you can select the**Copy to folder** context menu option much the same as the move one. Right-click a file in Explorer, select**Show more options** (in Windows 11), and click**Copy to folder** . A Copy Items window will open from which you can choose a folder to include the copied file. Clicking**Copy** will paste the item into the selected folder.

![The Copy to folder option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-folder-option.jpg)

 You can remove the "Copy/Move to folder" options from the right-click menu by deleting their registry keys. Open the**ContextMenuHandlers** key location specified in step three for adding a Move to folder context menu option. Right-click the**Copy to folder** or**Move to folder** registry key and select**Delete** . Select**Yes** when prompted to confirm you’re sure about erasing that key.

## How to Add Move and Copy to Folder Context Menu Options With WinBubble

 It’s relatively straightforward to add the "Copy/Move to folder" options with the Registry Editor, but there’s still an easier way to do it. You can add the same options to the context menu with the freeware WinBubble. WinBubble is customization software that includes a wide variety of context menu options. This is how to add a "Copy/Move to folder" context menu options with WinBubble:

1. Head over to [the WinBubble](https://www.softpedia.com/get/Tweak/System-Tweak/WinBubble.shtml) page on Softpedia.
2. Press WinBubble’s**Download Now** button.
3. Click the**Softpedia Mirror (US)** option for the download location.
4. Next, bring up a**Downloads** tab or page in whatever web browser you’re utilizing. You can do that in Chrome, Edge, Firefox, or Opera with the**Ctrl** +**J** hotkey.
5. Double-click the WinBubble ZIP to view that archive inside File Explorer.

1. Select**Extract all** on Explorer’s command bar or the**Compressed Folder Tools** tab in Windows 10.  
![The Extract all option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/extract-all-option.jpg)
2. Press the**Browse** button.
3. Choose a suitable directory to extract the archive outside the one it downloaded to, and click the**Select Folder** option.
4. Next, select**Show extracted files when complete** for the WinBubbles folder to automatically open after extraction.
5. Then click**Extract** to bring up the unzipped WinBubbles folder.  
![The Extract Compressed window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-extract-compressed-window.jpg)

1. Now double-click WinBubbles EXE to launch that software.
2. Select the**Move to** option on the**General** tab.
3. Click the**Copy to** checkbox to select that option.  
![The Copy to option in WinBubble](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-to-checkbox.jpg)
4. Press WinBubble’s**Apply** option when highlighted yellow.  
![The Apply button in WinBubble](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/highlighted-apply-button.jpg)
5. A WinBubble dialog box window will appear confirming the tweaks have been saved. Click**OK** to close that message.
6. Minimize or exit the WinBubble window.

 Now look at your new context menu options for copying and moving items to different locations. WinBubble adds them to the classic context menu like the manual registry tweak methods. So, you’ll still need to select**Show more options** or press**Shift** +**F10** to access those options in Windows 11.

 You can also utilize WinBubble to remove the "Copy/Move to Folder" options. Uncheck the selected**Move to** and**Copy to** checkboxes on its**General** tab. Click**Apply** to set the new options.

## Move and Copy Files to Folders With Your New Context Menu Options

 The**"** Copy/Move to folder" context menu options undoubtedly provide more convenient ways to copy and move files into alternative directories. You won’t need to drag files about anymore for moving items in Windows 11 after adding a new**"** Move to Folder option" to the right-click menu. Nor will you need to paste copied files elsewhere in Windows 11 thanks to the "Copy to folder" menu option.

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
<li><a href="https://win11-tips.techidaily.com/personalize-auto-lock-and-screensaver-interval/"><u>Personalize Auto-Lock & Screensaver Interval</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-depth-review-the-full-story-of-theta-s-technology-for-2024/"><u>[Updated] In-Depth Review  The Full Story of Theta S Technology for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-best-5-gif-to-video-converter-online-no-need-to-download/"><u>In 2024, Best 5 GIF to Video Converter Online [No Need to Download]</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-network-locked-sim-card-inserted-on-your-htc-phone-unlock-it-now-by-drfone-android/"><u>In 2024, Network Locked SIM Card Inserted On Your HTC Phone? Unlock It Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-barriers-how-to-successfully-install-java/"><u>Overcoming Barriers: How to Successfully Install Java</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-mastery-building-hotkeys-for-repetitive-text-snapping-tasks/"><u>Windows 11 Mastery: Building Hotkeys for Repetitive Text Snapping Tasks</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-how-to-change-background-on-teams-before-or-after-calling-for-2024/"><u>[Updated] How to Change Background on Teams Before or After Calling for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719242997504-navigate-past-chrome-hiccups-fixes-for-w11-users/"><u>Navigate Past Chrome Hiccups: Fixes for W11 Users</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/find-your-perfect-game-recorder-top-10-free-apps-for-2024/"><u>Find Your Perfect Game Recorder  Top 10 Free Apps for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-the-sound-experts-choice-7-innovative-free-transitions-to-revolutionize-your-work-for-2024/"><u>New The Sound Experts Choice 7 Innovative Free Transitions to Revolutionize Your Work for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-action-packed-snapshots-the-bold-polaroid-xs-100i-review/"><u>[New] Action-Packed Snapshots  The Bold Polaroid XS 100I Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-teamsters-shutdown-on-windows-11-10-systems/"><u>Avoiding Teamsters Shutdown on Windows 11, 10 Systems</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-future-proofing-visuals-evaluating-av1s-standpoint-over-vp9-for-2024/"><u>[Updated] Future-Proofing Visuals  Evaluating AV1's Standpoint over VP9 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-resolving-file-corrupted-error-x70-on-windows-1011/"><u>Swiftly Resolving 'File Corrupted' Error X70 on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-users-guide-to-managing-monitor-luminosity/"><u>Win Users Guide to Managing Monitor Luminosity</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-efficiently-shifting-videos-youtube-to-dailymotion-strategy/"><u>[New] 2024 Approved  Efficiently Shifting Videos  YouTube to Dailymotion Strategy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaching-windows-login-restrictions-a-quick-guide/"><u>Breaching Windows Login Restrictions: A Quick Guide</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-elite-humor-image-processor-for-2024/"><u>[New] Elite Humor Image Processor for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-expert-strategies-for-seamless-clip-composition/"><u>2024 Approved  Expert Strategies for Seamless Clip Composition</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-mimicking-marvels-how-to-create-comedic-videos/"><u>2024 Approved  Mimicking Marvels  How to Create Comedic Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-act-comparing-two-essential-windows-metrics/"><u>Balancing Act: Comparing Two Essential Windows Metrics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-adding-wordpad-shortcut-accessibility/"><u>Mastering Windows 11: Adding WordPad Shortcut Accessibility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-walkthrough-for-finding-windows-keys-losses/"><u>The Complete Walkthrough for Finding Windows Keys Losses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/productive-power-up-with-top-6-windows-apps-for-organizers/"><u>Productive Power-Up with Top 6 Windows Apps for Organizers</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-echoes-of-exploration-in-role-playing-history/"><u>[New] 2024 Approved  Echoes of Exploration in Role-Playing History</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-optimal-design-options-for-windows-users-no-cost-or-charged/"><u>[New] Optimal Design Options for Windows Users - No Cost or Charged</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-msresourceappname-text-glitch-win11-fix/"><u>Addressing 'MsResource/AppName Text' Glitch, Win11 Fix</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-pictures-from-motorola-moto-g-stylus-5g-2023-by-fonelab-android-recover-pictures/"><u>Possible solutions to restore deleted pictures from Motorola Moto G Stylus 5G (2023).</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-vivo-s17e-location-on-skout-drfone-by-drfone-virtual-android/"><u>How to Change Vivo S17e Location on Skout | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-ace-the-art-of-game-recordings-in-windows-11/"><u>[Updated] Ace the Art of Game Recordings in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-non-functioning-intel-unison-issues-in-windows-11/"><u>Navigating Through Non-Functioning Intel Unison Issues in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/administrative-controls-unveiled-windows-11-and-home-edition/"><u>Administrative Controls Unveiled: Windows 11 & Home Edition</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/navigating-through-youtubes-revenue-flow-after-monetization/"><u>Navigating Through YouTube's Revenue Flow After Monetization</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-cutting-edge-speech-to-text-googles-pathway-for-precision-for-2024/"><u>[New] Cutting-Edge Speech-to-Text  Google’s Pathway for Precision for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-mastering-cloud-costs-in-depth-price-analysis-and-best-options/"><u>2024 Approved  Mastering Cloud Costs  In-Depth Price Analysis & Best Options</u></a></li>
<li><a href="https://printer-issues.techidaily.com/regain-printers-availability-with-these-tips/"><u>Regain Printer's Availability with These Tips</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-instagram-mastery-the-top-10-steps-to-optimize-engagement-for-2024/"><u>[Updated] Instagram Mastery  The Top 10 Steps to Optimize Engagement for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-prevent-unintentional-erasure-of-panel-settings-by-cp/"><u>Techniques to Prevent Unintentional Erasure of Panel Settings by CP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocketing-printer-speed-in-windows-realm/"><u>Skyrocketing Printer Speed in Windows Realm</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-eliminating-webcam-dark-screen/"><u>Techniques for Eliminating Webcam Dark Screen</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-exploring-the-mystery-of-the-blue-video-symbol-on-fb-messages/"><u>2024 Approved  Exploring the Mystery of the Blue Video Symbol on FB Messages</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-exclusive-twitter-gif-compiler-for-avid-scribes-for-2024/"><u>[New] Exclusive Twitter GIF Compiler for Avid Scribes for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/approved-mitigating-the-risk-of-youtube-sanctions/"><u>2024 Approved  Mitigating the Risk of YouTube Sanctions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-file-extraction-failures-in-windows-1110/"><u>Navigating Through File Extraction Failures in Windows 11/10</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-the-complete-playbook-for-team-call-recording-desktopmobile/"><u>[Updated] 2024 Approved  The Complete Playbook for Team Call Recording (Desktop/Mobile)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reestablishing-credible-power-consumption-forecasts-in-win-11-setup/"><u>Reestablishing Credible Power Consumption Forecasts in Win 11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-code-0x0001-problem-in-ge-for-windows/"><u>Steps to Resolve Code 0X0001 Problem in GE for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-google-chrome-from-creating-new-tabs-ownself/"><u>Preventing Google Chrome From Creating New Tabs Ownself</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-your-desktop-layout-with-one-click/"><u>Restoring Your Desktop Layout with One Click</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-revolutionize-your-image-layouts-with-these-tools/"><u>[New] Revolutionize Your Image Layouts with These Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-lost-steam-games-iconage/"><u>Solutions for Lost Steam Games Iconage</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-perfecting-video-chapters-on-youtube-a-professionals-blueprint/"><u>[New] Perfecting Video Chapters on YouTube  A Professional's Blueprint</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-addressing-roblox-shutdown-issues-on-your-windows-machine/"><u>Swiftly Addressing Roblox Shutdown Issues on Your Windows Machine</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-instagram-story-wizardry-secrets-revealed/"><u>[Updated] 2024 Approved  Instagram Story Wizardry  Secrets Revealed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-original-terminals-in-win11/"><u>Regaining Original Terminals in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-random-restarts-on-windows-11-systems/"><u>Troubleshoot Random Restarts on Windows 11 Systems</u></a></li>
<li><a href="https://location-social.techidaily.com/edit-and-send-fake-location-on-telegram-for-your-nokia-g310-in-3-ways-drfone-by-drfone-virtual-android/"><u>Edit and Send Fake Location on Telegram For your Nokia G310 in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-mastering-instagram-utilizing-search-to-expand-your-filters/"><u>[New] In 2024, Mastering Instagram  Utilizing Search to Expand Your Filters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-captcha-troubles-in-steam/"><u>Overcoming Windows CAPTCHA Troubles in Steam</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-easily-unlock-your-motorola-moto-g73-5g-device-sim-by-drfone-android/"><u>In 2024, Easily Unlock Your Motorola Moto G73 5G Device SIM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-with-ease-the-windows-11-touchpad-guide/"><u>Navigating with Ease: The Windows 11 Touchpad Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insightful-strategies-for-hardware-serial-numbers-on-windows/"><u>Insightful Strategies for Hardware Serial Numbers on Windows</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-elevate-your-online-presence-mastering-youtube-edits-in-premiere/"><u>[Updated] Elevate Your Online Presence  Mastering YouTube Edits in Premiere</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-stuttering-challenges-enhancing-warhammer-40k-experience/"><u>Conquer Stuttering Challenges: Enhancing Warhammer 40K Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-event-viewer-breakdowns/"><u>Addressing Windows Event Viewer Breakdowns</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-window-placement-with-powertoys/"><u>Personalizing Window Placement with PowerToys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailored-windows-note-placement-guide/"><u>Tailored Windows Note Placement Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-reasons-to-use-the-new-outlook-app-on-windows/"><u>9 Reasons to Use the New Outlook App on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-java-vm-creation-failed-in-windows/"><u>Troubleshooting Java VM Creation Failed in Windows</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-revolutionizing-online-content-the-power-of-time-stamps/"><u>[New] Revolutionizing Online Content  The Power of Time-Stamps</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/1716461741067-best-10-youtube-volume-boosters-for-windows-macos-android-and-iphone/"><u>Best 10 YouTube Volume Boosters for Windows, MacOS, Android and iPhone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-taskmanagers-dominance/"><u>Mastery Over TaskManager's Dominance</u></a></li>
</ul></div>
