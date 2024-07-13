---
title: Boosting File Management Efficiency with New Commands for Win 11
date: 2024-07-12T18:07:13.695Z
updated: 2024-07-13T18:07:13.695Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Boosting File Management Efficiency with New Commands for Win 11
excerpt: This Article Describes Boosting File Management Efficiency with New Commands for Win 11
keywords: Windows File Organize,Win 11 Optimized Commands,Enhance Win 11 FS,Efficient File Management Win,Win 11 File Streamline,Command Boosts Win 11,Increase File Speed Win 11
thumbnail: https://thmb.techidaily.com/9ca2eff6ae26123de716ede19623049b700dbda01116c41da9ae37331ba659b6.jpg
---

## Boosting File Management Efficiency with New Commands for Win 11

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
<li><a href="https://win11-tips.techidaily.com/avoid-discord-updates-and-autostart-on-windows-10/"><u>Avoid Discord Updates & Autostart on Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adopt-a-streamlined-approach-to-input-customization/"><u>Adopt a Streamlined Approach to Input Customization</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-experience-fcp-for-free-90-day-trial-inside/"><u>2024 Approved Experience FCP for Free 90-Day Trial Inside</u></a></li>
<li><a href="https://win11-tips.techidaily.com/artistry-made-easy-top-7-windows-11-drawing-apps-reviewed/"><u>Artistry Made Easy: Top 7 Windows 11 Drawing Apps Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-with-automated-folder-pairings-in-new-windows-os/"><u>Boost Efficiency with Automated Folder Pairings in New Windows OS</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-uncovering-steps-to-pinpoint-perfect-discord-communities/"><u>In 2024, Uncovering  Steps to Pinpoint Perfect Discord Communities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-and-reset-windows-11s-touch-keyboard-layout/"><u>Adjust and Reset Windows 11'S Touch Keyboard Layout</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-directional-audio-with-windows-earbuds/"><u>Balancing Directional Audio with Windows Earbuds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-not-stopping-generic-audio-issue/"><u>Addressing 'Windows Not Stopping Generic Audio' Issue</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-5-techniques-you-never-heard-of-for-converting-mp4-to-gif-in-photoshop-for-2024/"><u>New 5 Techniques You Never Heard of for Converting MP4 to GIF in Photoshop for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-elevate-your-footage-expert-video-editing-advice-for-stunning-home-videos/"><u>Updated 2024 Approved Elevate Your Footage Expert Video Editing Advice for Stunning Home Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-high-temperature-troubleshooting-tips-w11/"><u>Avoiding High-Temperature Troubleshooting Tips: W11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/downloading-twitters-animated-content-simplified-for-2024/"><u>Downloading Twitter's Animated Content Simplified for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/joining-the-metaverse-comedy-club-top-20plus-memes-and-techniques/"><u>Joining the Metaverse Comedy Club  Top 20+ Memes & Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-wsl-registration-failure-error-x80370102-fix-guide/"><u>Addressing WSL Registration Failure - Error X80370102 Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-common-errors-essential-tips-for-first-time-windows-11-users/"><u>Avoiding Common Errors: Essential Tips for First-Time Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-practices-for-eluding-windows-11-explorer-errors/"><u>Best Practices for Eluding Windows 11 Explorer Errors</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-pc-video-editing-made-easy-a-review-of-vn-video-editor/"><u>In 2024, PC Video Editing Made Easy A Review of VN Video Editor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-hurdles-with-these-three-steps-to-activate-telnet-on-wins/"><u>Avoid Hurdles with These Three Steps to Activate Telnet on Wins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-experts-strategy-for-managing-component-services-in-w11/"><u>An Expert's Strategy for Managing Component Services in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-task-manager-admin-mode-on-windows-11/"><u>Boosting Task Manager: Admin Mode on Windows 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/top-10-password-cracking-tools-for-samsung-galaxy-s23-ultra-by-drfone-android/"><u>Top 10 Password Cracking Tools For Samsung Galaxy S23 Ultra</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-the-fastest-way-to-determine-twitter-video-aspect-ratios/"><u>Updated 2024 Approved The Fastest Way to Determine Twitter Video Aspect Ratios</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-display-drivers-that-dont-launch-in-windows-10/"><u>Avoiding Display Drivers That Don’t Launch in Windows 10</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-soundtrack-sanctuary-the-finest-websites-offering-free-audio-selections-for-filmmakers/"><u>In 2024, Soundtrack Sanctuary The Finest Websites Offering Free Audio Selections for Filmmakers</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-remove-a-previously-synced-google-account-from-your-infinix-hot-40i-by-drfone-android/"><u>In 2024, How to Remove a Previously Synced Google Account from Your Infinix Hot 40i</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-code-development-top-wls-2-methods-on-latest-oses/"><u>Boost Your Code Development: Top WLS 2 Methods on Latest OSes</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-enhance-audio-quality-get-high-quality-fx/"><u>[Updated] In 2024, Enhance Audio Quality, Get High-Quality FX</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713942770188-updated-live-stream-on-youtube-using-zoom/"><u>Updated | Live Stream on YouTube Using Zoom</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-filmmaking-with-ease-decoding-common-video-editing-hurdles-in-filmora/"><u>2024 Approved  Filmmaking with Ease  Decoding Common Video Editing Hurdles in Filmora</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-2024-approved-crafting-the-rhythm-adding-beats-and-melodies-to-your-fb-vids/"><u>[New] 2024 Approved  Crafting the Rhythm  Adding Beats and Melodies to Your FB Vids</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-tools-for-win-soft-installation-chocolatey-or-wm/"><u>Best Tools for Win Soft Installation: Chocolatey or WM</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-remove-screen-lock-pin-on-infinix-hot-30-5g-like-a-pro-5-easy-ways-by-drfone-android/"><u>In 2024, How To Remove Screen Lock PIN On Infinix Hot 30 5G Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-edge-safety-implement-windows-11-defender-application-guard/"><u>Boosting Edge Safety: Implement Windows 11 Defender Application Guard</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixed-no-device-detected-for-wireless-connection-on-pc/"><u>[FIXED] No Device Detected for Wireless Connection on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-performance-on-windows-11-top-seven-tweaks-for-game-enthusiasts/"><u>Boosting Performance on Windows 11: Top Seven Tweaks for Game Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/become-a-full-screen-screenshot-expert-4-essential-tricks-for-windows/"><u>Become a Full-Screen Screenshot Expert: 4 Essential Tricks for Windows.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-windows-11-lock-screen-effortlessly/"><u>Avoiding Windows 11 Lock Screen Effortlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-usb-connection-issues-on-windows-11/"><u>Addressing USB Connection Issues on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-control-display-settings-for-windows-11-users/"><u>Advanced Control: Display Settings for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplifying-old-directx-gaming-via-dxvk-powered-upgrades/"><u>Amplifying Old DirectX Gaming via DXVK-Powered Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-windows-11-efficiency-key-modifications-to-apply/"><u>Boost Windows 11 Efficiency: Key Modifications to Apply</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-yellow-shade-from-laptop-panels/"><u>Banishing Yellow Shade From Laptop Panels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-frustration-fixing-11s-windows-pin-hiccups/"><u>Avoid Frustration: Fixing 11'S Windows PIN Hiccups</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-history-enthusiasts-guide-to-inspiring-youtube-channels/"><u>In 2024, History Enthusiasts' Guide to Inspiring YouTube Channels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-blank-spaces-on-your-screen-icons-revival-guide/"><u>Avoid Blank Spaces on Your Screen: Icons Revival Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-pc-a-guide-to-setting-up-hyper-v-on-win-11-home/"><u>Boost Your PC: A Guide to Setting Up Hyper-V on Win 11 Home</u></a></li>
<li><a href="https://ai-voice.techidaily.com/in-2024-best-5-quandale-dingle-voice-generators/"><u>In 2024, Best 5 Quandale Dingle Voice Generators</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-guide-to-using-free-luts-for-obs-for-2024/"><u>Updated Guide To Using Free Luts for OBS for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-pc-with-smooth-directx-downloads-and-upgrades/"><u>Boost Your PC with Smooth DirectX Downloads & Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-write-access-denial-errors-in-windows-11-system/"><u>Addressing Write Access Denial Errors in Windows 11 System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/are-your-windows-apps-struggling-to-connect-to-the-internet-try-these-fixes/"><u>Are Your Windows Apps Struggling to Connect to the Internet? Try These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/alteration-of-login-failure-counter-windows-11-user-guide/"><u>Alteration of Login Failure Counter: Windows 11 User Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-the-effectiveness-of-your-pointer-on-win11s-system/"><u>Boosting the Effectiveness of Your Pointer on Win11's System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bidding-farewell-to-ads-in-the-win-11-startup/"><u>Bidding Farewell to Ads in the Win 11 Startup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-performance-of-windows-for-swift-steam-uploads/"><u>Boosting Performance of Windows for Swift Steam Uploads</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-from-xiaomi-14-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock from Xiaomi 14 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-customized-windows-cmd-tricks-and-tips/"><u>Boost Productivity: Customized Windows Cmd Tricks and Tips</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-optimal-4k-video-recording-tools-compilation-for-2024/"><u>[New] Optimal 4K Video Recording Tools Compilation for 2024</u></a></li>
</ul></div>
