---
title: Resolving W11/W10's Refusal to Open Folders After Double-Clicks
date: 2024-07-12T17:28:00.390Z
updated: 2024-07-13T17:28:00.390Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving W11/W10's Refusal to Open Folders After Double-Clicks
excerpt: This Article Describes Resolving W11/W10's Refusal to Open Folders After Double-Clicks
keywords: Double-Click Folder Issue,W11/W10 Opening Refusal,Folder Access Problem,Windows Double-Click Error,File Folder Open Failure,Open Folders Post-Double Click,Resolving W11/W10 Double-Click Bug
thumbnail: https://thmb.techidaily.com/c36628b8a77d9c8656bc14c8b8281e34c21620e4322ca2c6d47a165e3e9293b6.png
---

## Resolving W11/W10's Refusal to Open Folders After Double-Clicks

 Some users have posted on help chat forums about folders not opening when they double-click them in Windows File Explorer. This means users can’t access folders by double-clicking on directories. There isn’t a specific error message associated with this issue.

 This issue doesn’t necessarily mean users can’t open any folders, for they can still access directories by selecting **Open** on the right-click menu. However, selecting the **Open** context menu option isn’t the most ideal way to access them. If you can’t open folders by double-clicking them on your Windows 11/10 PC, try applying these potential fixes.

## 1\. Adjust File Explorer Options

 File Explorer has alternative single-click and double-click options for opening items. If single-click is set, double-clicking folders won’t open them. Try single-clicking a folder to see if that works. If it does, then you probably need to select the **Double-click to open an item** option like this:

1. Right-click on your taskbar’s **Start** button to select a **Search** shortcut.
2. Type "File Explorer options" to find a matching search result.
3. Click **File Explorer Options** to bring up the window with that title.
4. Select the **Double-click to open an item** radio button.  
![The Double-click to open an item option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/double-click-to-open-an-item-option.jpg)
5. Click the **Apply** button for saving settings.
6. Select **OK** to close the File Explorer Options window.

 If you find the **Double-click to open item** option is already selected, you could try selecting the single-click setting instead. That way, you might at least be able to access your folders by single-clicking them. Or, proceed with applying the other resolutions below.

## 2\. Adjust the Double-Click Mouse Speed

 The mouse **Double-click speed** setting can feasibly cause this issue if it’s set too fast. So, you might need to lower that setting a little bit. This is how you can adjust the mouse double-click speed:

1. First, bring up the tool for finding files with the **Windows** key + **S** hotkey that opens it.
2. Type the "mouse settings" keyword phrase.
3. Click **Mouse settings** to open a Settings window.
4. Next, click the **Additional mouse** options in Settings.  
![The Additional mouse settings option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/additional-mouse-settings.jpg)
5. Drag the **Double-click speed** bar’s slider left to slow it down.  
![The Double-click speed setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/double-click-speed-setting.jpg)
6. Select **Apply** and click **OK** to set the new double-click speed.

 The required double-click speed for opening folders will now be slower than before. So, you won’t need to double-click so quickly.

## 3\. Scan and Repair Windows System Files

 Microsoft advises users to run system file scans when Windows functions aren’t working right. In this case, there’s an issue with the folders’ double-click functionality.

 So, [run a System File Checker scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) to see if Windows Resource Protection detects any corrupted system files. If so, Windows Resource Protection will probably also repair the files detected, which could fix the double-clicking of folders not opening.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-sfc-scannow3.jpg)

## 4\. Edit the Shell Registry Key

 Quite a few users have confirmed editing the **shell** registry key can fix the double-clicking of folders not working in Windows 11/10\. Those users changed that key’s **(Default)** string value to fix the issue. These are the steps for editing the **shell** key:

1. Press the **Windows** logo keyboard key + **R** to start Run.
2. Input a **regedit** (Registry Editor) Run command inside the **Open** box and select **OK**.
3. Bring up the shell key by inputting this path inside the registry address box:  
`Computer\HKEY_CLASSES_ROOT\Directory\shell`
4. Double-click **(Default)** inside the **shell** key.  
![The shell registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-shell-key.jpg)
5. If the **Value data** box is empty, or set differently, input **none** there as in the snapshot directly below.  
![The (Default) string value for the shell registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-default-string-value.jpg)
6. Click **OK** to save the new **(Default)** string value.

 You might need to [restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) for this registry tweak to take effect. Alternatively, restart Windows and then try double-clicking a folder to see if it opens.

## 5\. Edit the Mouse Registry Key

 Double-click issues can arise when string values for the **Mouse** registry key have been altered from their default settings (typically by third-party apps). To be more specific, **MouseHoverWidth**, **MouseHoverHeight**, **DoubleClickHeight**, and **DoubleClickWidth** are four **Mouse** key strings you might need to restore to default values for to fix this issue.

 To do so, edit the **Mouse** registry key like this:

1. Bring up Registry Editor as instructed for the first two steps of the previous potential solution.
2. Next, go to the **Mouse** key by entering this path within Registry Editor’s address bar:  
`Computer\HKEY_CURRENT_USER\Control Panel\Mouse`
3. Double-click the **MouseHoverWidth** string.  
![The Mouse key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/mouse-key.jpg)
4. If set any differently, input **4** inside the **Value data** box and select **OK**.  
![The MouseHoverWidth string value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-mousehoverwidth-string-value.jpg)
5. Repeat the previous two steps for the **MouseHoverHeight**, **DoubleClickHeight**, and **DoubleClickWidth** strings in the **Mouse** key. Set their values to **4**, just like you did for the **MouseHoverWidth**string.

 When you’ve finished adjusting those string values, exit the Registry Editor and restart your PC. If you find all those strings are already set to four, you don’t need to change them.

## 6\. Turn Off Controlled Folder Access

 Some users have said they fixed the double-clicking of folders not working by turning off controlled folder access. Controlled folder access is the Windows Security feature that blocks unauthorized apps from modifying contents inside protected directories. Thus, enabling that feature restricts folder access.

 So, try turning off controlled folder access like this:

1. Open Windows Security by double-clicking the small shield icon inside the system tray area of your taskbar.
2. Click **Virus & threat protection** in Windows Security’s left navigation sidebar.  
![The tab sidebar in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-security-s-tab-sidebar.jpg)
3. Scroll down a little and click on **Manage ransomware protection**.  
![The Manage ransomware protection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/manage-ransomware-protection.jpg)
4. Click the **Controlled folder access** toggle switch to turn off that setting.  
![The Controlled folder access setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/controlled-folder-access-setting.jpg)

 Then, go into File Explorer and try opening some folders again to see if disabling that security feature makes a difference. If it does, then it’s probably best to leave controlled folder access off.

## 7\. Revert Windows to a Restore Point

 Rolling Windows back to a saved restoration point is one of the last things to try if no other potential fixes for this issue work. Applying this potential fix will undo system changes made and remove software installed after your chosen restore point date.

 However, it’s only worth reverting Windows if you can select a restore point that will roll back the OS to a time when you could open folders by double-clicking them.

![The System Restore tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-system-restore-tool.jpg)

 To apply this potential fix, check out our guide on [utilizing System Restore](https://www.makeuseof.com/use-system-restore-windows/). The System Restore tool will need to be enabled for you to select a restoration point. Be prepared to reinstall software packages a selected restore point deletes, which you can check by clicking **Scan for affected programs** in System Restore.

## Make Double-Clicking Open Folders on Windows Again

 Those potential fixes for double-clicking folders not working will probably resolve that Windows 11/10 issue in most cases. We can’t promise they’re guaranteed, but lots of users have confirmed some of them work.

 Beyond those possible resolutions, you might have to try something more drastic, like a full system reset or in-place Windows upgrade.

 This issue doesn’t necessarily mean users can’t open any folders, for they can still access directories by selecting **Open** on the right-click menu. However, selecting the **Open** context menu option isn’t the most ideal way to access them. If you can’t open folders by double-clicking them on your Windows 11/10 PC, try applying these potential fixes.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-unleash-your-creative-potential-with-top-10-tiktok-editors/"><u>[New] In 2024, Unleash Your Creative Potential with Top 10 TikTok Editors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-usb-health-in-windows-a-troubleshooting-checklist/"><u>Restoring USB Health in Windows: A Troubleshooting Checklist</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-update-failure-error-0x8024800c/"><u>Resolving Windows Update Failure (Error 0X8024800C)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-winvpn-error-remote-computer-not-reachable/"><u>Quick Guide: WinVPN Error Remote Computer Not Reachable</u></a></li>
<li><a href="https://win11-tips.techidaily.com/open-windows-dialogue-the-freedomgpt-way/"><u>Open Windows Dialogue: The FreedomGPT Way</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-labyrinth-a-guide-to-windows-11s-services/"><u>Navigating the Labyrinth: A Guide to Windows 11'S Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ignite-innovation-top-picks-from-microsofts-store-2-infuse-your-living-space-with-a-touch-of-history-while-maintaining-modern-comfort-and-style-lets-embark-20/"><u>Ignite Innovation: Top Picks From Microsoft's Store, 2 Infuse Your Living Space with a Touch of History While Maintaining Modern Comfort and Style? Let's Embark on an Exciting Home Decor Journey Together!</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-essential-apps-for-invisible-story-watching-for-2024/"><u>[New] Essential Apps for Invisible Story Watching for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steam-deck-windows-installation-essentials/"><u>Steam Deck: Windows Installation Essentials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-settings-unveiled/"><u>Windows 11 Settings Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-yellow-discoloration-in-windows-laptop-screens/"><u>Resolving Yellow Discoloration in Windows Laptop Screens</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-chrome-os-native-screen-recorder/"><u>2024 Approved  Chrome OS Native Screen Recorder</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-polishing-your-tiktok-content-a-guide-to-filters/"><u>2024 Approved  Polishing Your TikTok Content  A Guide to Filters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/run-a-local-and-free-chatgpt-clone-on-your-windows-pc-with-gpt4all/"><u>Run a Local and Free ChatGPT Clone on Your Windows PC With GPT4All</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-esd-to-iso-transformation-on-windows-pcs/"><u>Step-by-Step ESD to ISO Transformation on Windows PCs</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-no-8-visual-artists-choice-for-photo-assembly/"><u>In 2024, No. 8 Visual Artist's Choice for Photo Assembly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-mystery-fixing-windows-error-code-0x0000004e/"><u>Tackling the Mystery: Fixing Windows Error Code 0X0000004E</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-geforce-now-error-xc0f1103f-in-windows-11/"><u>Overcoming GeForce Now Error Xc0f1103f in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-program-installation-on-windows-11/"><u>Mastering Program Installation on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-new-cycle-begins-without-maintenance-updates-to-windows-xp781/"><u>A New Cycle Begins Without Maintenance Updates to Windows XP/7/8.1</u></a></li>
<li><a href="https://fake-location.techidaily.com/looking-for-a-location-changer-on-lenovo-thinkphone-look-no-further-drfone-by-drfone-virtual-android/"><u>Looking For A Location Changer On Lenovo ThinkPhone? Look No Further | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-prime-camcorder-selections-in-depth-insights/"><u>[New] Prime Camcorder Selections – In-Depth Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-files-save-path-problem-easy-fix-guide/"><u>Windows Files' Save Path Problem: Easy Fix Guide</u></a></li>
<li><a href="https://network-issues.techidaily.com/addressing-bd-issues-on-ws-21-ws-8-and-older-windows/"><u>Addressing BD Issues on WS-21, WS-8 & Older Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveling-the-playing-field-for-laptops-and-iphones/"><u>Leveling the Playing Field for Laptops and iPhones</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-optimal-8-capture-tools-without-delay/"><u>In 2024, Optimal 8 Capture Tools Without Delay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-closed-caption-settings-in-windows-11/"><u>Mastering Closed Caption Settings in Windows 11</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-reigniting-creativity-exclusive-free-drawing-tools-for-mac-users/"><u>2024 Approved  Reigniting Creativity  Exclusive FREE Drawing Tools for Mac Users</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-get-the-apple-id-verification-code-from-iphone-14-pro-max-in-the-best-ways-by-drfone-ios/"><u>How To Get the Apple ID Verification Code From iPhone 14 Pro Max in the Best Ways</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/4-ways-to-unlock-apple-iphone-xr-to-use-usb-accessories-without-passcode-drfone-by-drfone-ios/"><u>4 Ways to Unlock Apple iPhone XR to Use USB Accessories Without Passcode | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-efficiency-moving-windows-11-folders-with-tabs/"><u>Maximizing Efficiency: Moving Windows 11 Folders with Tabs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-techniques-for-scrubbing-windows-safety-files/"><u>Simplified Techniques for Scrubbing Windows' Safety Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-fixes-for-stalled-google-nearby-share-on-pc/"><u>Unveiling Fixes for Stalled Google Nearby Share on PC</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-lenovo-thinkphone-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your Lenovo ThinkPhone? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-upgrade-efficiency-over-entertainment/"><u>Windows 11 Upgrade: Efficiency Over Entertainment</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-integrate-harmony-in-media-posts-facebooks-sound-guide/"><u>2024 Approved  Integrate Harmony in Media Posts  Facebook's Sound Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11-writability-enabledisable-ntfs-compression/"><u>Unlocking Windows 11' Writability: Enable/Disable NTFS Compression</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-win10s-best-bet-for-screen-snaps-and-recordings/"><u>[New] In 2024, Win10's Best Bet for Screen Snaps and Recordings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-galaxys-potential-the-dex-connection-technique/"><u>Leveraging Galaxy's Potential: The DeX Connection Technique</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/the-best-asmr-microphones-you-should-try/"><u>The Best ASMR Microphones You Should Try</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keep-windows-11-clean-enable-the-autodelete-functionality/"><u>Keep Windows 11 Clean: Enable the Autodelete Functionality</u></a></li>
<li><a href="https://extra-skills.techidaily.com/setting-up-windows-11-for-automatic-hdr-activation-for-2024/"><u>Setting Up Windows 11 for Automatic HDR Activation for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-amplify-vram-in-windows-os/"><u>Strategies to Amplify VRAM in Windows OS</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/bringing-your-nikon-videos-to-life-editing-software-and-techniques/"><u>Bringing Your Nikon Videos to Life Editing Software and Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-directx-downloads-issue-in-os/"><u>Mending DirectX Downloads Issue in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-optimal-performance-kali-on-windows/"><u>Achieve Optimal Performance: Kali on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-your-monitor-memorable-saving-windows-spotlight-photos-as-walls/"><u>Making Your Monitor Memorable: Saving Windows Spotlight Photos as Walls</u></a></li>
<li><a href="https://ai-voice.techidaily.com/updated-2024-approved-top-10-robotic-voice-generators-with-comparison-table/"><u>Updated 2024 Approved Top 10 Robotic Voice Generators (with Comparison Table)</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-speeding-up-live-instagram-broadcasts-on-desktop-for-2024/"><u>[New] Speeding Up Live Instagram Broadcasts on Desktop for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-mp3-conversion-windows-and-imgburn-a-guide-to-creating-professional-audio-cds/"><u>Streamlining MP3 Conversion: Windows & ImgBurn - A Guide to Creating Professional Audio CDs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-could-not-be-registered-error-a-windows-photos-guide/"><u>Addressing 'Could Not Be Registered' Error: A Windows Photos Guide</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-best-youtube-to-mp3-converters-free-download-onlinewinmac/"><u>[New] 2024 Approved  Best YouTube to MP3 Converters Free Download [Online/Win/Mac]</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/revealing-the-techniques-for-perfect-sound-transitions-for-2024/"><u>Revealing the Techniques for Perfect Sound Transitions for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-easy-steps-to-wipe-your-drives-partitions-in-windows/"><u>4 Easy Steps to Wipe Your Drive's Partitions in Windows</u></a></li>
</ul></div>
