---
title: Methods to Restore Deleted Run Logs
date: 2024-06-25T16:43:50.453Z
updated: 2024-06-26T16:43:50.453Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Methods to Restore Deleted Run Logs
excerpt: This Article Describes Methods to Restore Deleted Run Logs
keywords: Recovering Run Logs,Restoring Deleted Logs,Data Backup for Logs,RunLog Recovery Methods,Resetting System Logs,Log Deletion Fixes,Reinstating Run Records
thumbnail: https://thmb.techidaily.com/c6867ae9c4f4e3df3c9379b15f4163ebd35319a50b7aab7a2fe4029be64b0298.jpg
---

## Methods to Restore Deleted Run Logs

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/tackling-erroneous-code-fixing-0x800713f-mail-glitch-in-windows-11/"><u>Tackling Erroneous Code: Fixing 0X800713F Mail Glitch in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/repairing-password-management-on-windows-systems/"><u>Repairing Password Management on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-settings-returning-to-initial-touch-keyboard-configuration/"><u>Win 11 Settings: Returning to Initial Touch Keyboard Configuration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reimagine-archived-footage-boost-video-quality-using-madvr-on-windows/"><u>Reimagine Archived Footage: Boost Video Quality Using MadVR on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveling-the-playing-field-for-laptops-and-iphones/"><u>Leveling the Playing Field for Laptops and iPhones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-folder-customization-adding-movecopy-context-functionality/"><u>Windows 11 Folder Customization - Adding Move/Copy Context Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-customization-in-windows-11-adding-directories/"><u>Mastering Customization in Windows 11: Adding Directories</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11-dir-not-empty-error-0x80070091/"><u>Overcoming Windows 11 Dir Not Empty Error (0X80070091)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/joining-forces-onedrive-and-windows-live-account-sync/"><u>Joining Forces: OneDrive & Windows Live Account Sync</u></a></li>
<li><a href="https://extra-hints.techidaily.com/best-practices-zooming-into-fb-live-excellence/"><u>Best Practices  Zooming Into FB Live Excellence</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-harmonizing-your-spotify-queue-with-youtube-music-catalogs/"><u>[Updated] 2024 Approved  Harmonizing Your Spotify Queue with YouTube Music Catalogs</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-logo-design-101-tips-to-make-your-podcast-stand-out/"><u>2024 Approved  Logo Design 101  Tips to Make Your Podcast Stand Out</u></a></li>
<li><a href="https://extra-resources.techidaily.com/duets-of-destiny-song-suggestions-for-the-big-ask/"><u>Duets of Destiny  Song Suggestions for the Big Ask</u></a></li>
<li><a href="https://android-location.techidaily.com/getting-the-pokemon-go-gps-signal-not-found-11-error-in-huawei-nova-y71-drfone-by-drfone-virtual/"><u>Getting the Pokemon Go GPS Signal Not Found 11 Error in Huawei Nova Y71 | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-the-essentials-of-whatsapp-room-setup/"><u>[Updated] 2024 Approved  The Essentials of WhatsApp Room Setup</u></a></li>
<li><a href="https://extra-tips.techidaily.com/holistic-iphone-use-images-and-videos-fused-together/"><u>Holistic iPhone Use  Images & Videos Fused Together</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-remove-and-reset-face-id-on-apple-iphone-xs-max-drfone-by-drfone-ios/"><u>How to Remove and Reset Face ID on Apple iPhone XS Max | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/discover-the-leading-free-audio-modification-software-of-the-year/"><u>Discover the Leading Free Audio Modification Software of the Year</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-change-gps-location-on-vivo-g2-easily-and-safely-drfone-by-drfone-virtual-android/"><u>How to Change GPS Location on Vivo G2 Easily & Safely | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>