---
title: Methods for Correcting False Device Error Windows 10/11
date: 2024-09-11T01:28:15.871Z
updated: 2024-09-12T01:28:15.871Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Methods for Correcting False Device Error Windows 10/11
excerpt: This Article Describes Methods for Correcting False Device Error Windows 10/11
keywords: Fix Windows Errors Quickly,Resolve Devices Glitches,Unblock OS Errors Windows,Tackle Windows Faults,Eradicate Device Mistakes,Eliminate OS Failures,Correct Windows Issues
thumbnail: https://thmb.techidaily.com/a7c3b7288a2ba7cb90e6052babba4915f51445892d0c27222e3c559cd653e7a3.png
---

## Methods for Correcting False Device Error Windows 10/11

 Many users partition their hard drives or utilize external storage devices with their PCs. However, such drives become inaccessible when the “A device which does not exist was specified” error arises. Users have reported seeing this strange error message when they try to open connected external storage devices or drive partitions inside Windows File Explorer.

 That error is most unwelcome since it means users can’t open whatever drives it arises for. Consequently, they can’t access files on affected drives. This is how you can fix the “device which does not exist was specified” error in Windows 10 and 11.


>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>







<!-- affiliate ads begin -->
<span id="1982485">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982485.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982485">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982485.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982485%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982485/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 1\. Plug the Affected Device Into a Different USB Slot

 If this error is affecting an external storage device, try reconnecting the USB drive. There might be an issue with the port you’ve connected the drive with. Plug the USB drive into a different port to see if the same error occurs.

 If you need to resolve this error for an internal drive, check the drive’s internal connections. To do that, you’ll need to open the case for a desktop PC. Then make sure none of the drive’s connection cables are in any way loose.





<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123750/7443" target="_top" id="2123750">
  <img src="//a.impactradius-go.com/display-ad/7443-2123750" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123750/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 2\. Run the SFC Tool

 Users have confirmed the System File Checker tool can resolve this drive error. That highlights system file corruption can cause this issue, which an SFC scan will likely resolve. Our guide to[running a System File Checker scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to execute the SFC command in Windows.

![The sfc /scannow](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/sfc-scannow.jpg)





<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118323/7443" target="_top" id="2118323">
  <img src="//a.impactradius-go.com/display-ad/7443-2118323" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118323/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 3\. Run a Check Disk Scan for the Drive

 You might need to fix the “device which does not exist was specified” error because your drive has some bad sectors. Running a CHKDSK (Check Disk) scan command is a potential remedy for bad drive sectors. This is how you can run the Windows Check Disk tool from the Command Prompt:

1. Open the search tool by simultaneously pressing the**Windows** logo +**S** keys.
2. Enter the search phrase**cmd** inside the text box.
3. Click**Run as administrator** to start Command Prompt with elevated permissions.
4. Then execute the Check Disk scan by inputting this command:  
`chkdsk X: /f /r`  
![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/chkdsk-scan.jpg)
5. Press**Enter** to initiate the scan.

 You’ll need to replace X in the above command with the actual letter of the affected drive you need to scan. For example, the command for a drive labeled D would be:

`chkdsk D: /f /r`

## 4\. Try Changing the Drive’s Letter

 Changing the affected drive’s letter is a potential fix that users have confirmed to work. You can change the drive’s letter with the Disk Management tool like this:

1. If you need to fix this issue for an external drive, connect that storage device to your PC.
2. Open Disk Management by right-clicking**Start** and selecting the shortcut for that tool.
3. Right-click the affected drive and select**Change Drive Letter and Paths** .  
![The Change Drive Letter and Paths option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-drive-letter-paths.jpg)
4. Press the**Change** button.  




<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130874/7443" target="_top" id="2130874">
  <img src="//a.impactradius-go.com/display-ad/7443-2130874" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130874/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




![The Change Drive Letter window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-drive-letter-window.jpg)
5. Click the drop-down menu for the**Assign the following drive lette** r option.  
![The Assign the following drive letter option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/assign-the-following-drive-letter.jpg)
6. Select a drive letter that you’ve never used.




<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118322/7443" target="_top" id="2118322">
  <img src="//a.impactradius-go.com/display-ad/7443-2118322" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118322/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




7. Click**OK** on the Change Drive Letter or Path window.
8. Select**Yes** on the Disk Management confirmation dialog.





<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134249/18498" target="_top" id="2134249">
  <img src="//a.impactradius-go.com/display-ad/18498-2134249" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134249/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 5\. Rescan a Drive

 Disk Management includes a**Rescan Disk** option for troubleshooting drives. That option detects disk changes and updates drive info accordingly when selected. So, rescanning the disk is a viable troubleshooting method for resolving this “device which does not exist” error. This is how you can rescan a drive:

1. Plug the drive into your PC if necessary.
2. Bring up the Disk Management tool.
3. Click the drive for which the error occurs in Disk Management.
4. Then click the**Action** menu.  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/properties-option2.jpg)
5. Select**Rescan Disks** on the menu.

## 6\. Select the Full Control Option for a Drive Location

 The “device which does not exist” error can arise because of restricted drive permissions. In that scenario, users need to select a**Full control** permission option for their drives. These are the steps for selecting the**Full control** permission setting:

1. First, activate the file management tool with Explorer’s**Windows** logo +**E** hotkey.
2. Then click**This PC** in Explorer’s left sidebar.
3. Right-click the affected drive to select**Properties** .  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/properties-option2.jpg)
4. Click the drive’s**Security** tab.




<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115947/19272" target="_top" id="2115947">
  <img src="//a.impactradius-go.com/display-ad/19272-2115947" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115947/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




5. If the**Full control** option isn’t ticked, click the**Edit** button.
6. Select the**Allow** box for the**Full control** option.  
![The Full control option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/full-control-checkbox.jpg)
7. Click**Apply** \>**OK** on the drive’s permissions window.




<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135418/19272" target="_top" id="2135418">
  <img src="//a.impactradius-go.com/display-ad/19272-2135418" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135418/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->





## 7\. Reinstall the Affected Drive

 If you need to fix this issue for an external storage device, try reinstalling the affected drive. Doing so will reinstall the drivers for the affected storage device. This is how you can reinstall the drive:

Insert the affected drive into one of your PC’s USB ports.

1. Click**Start** with the right mouse button to select a**Device Manager** shortcut.
2. Double-click**Disk drives** in Device Manager.
3. Right-click your drive and select**Uninstall device** .  
![The Uninstall device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/uninstall-device2.jpg)
4. Then select the**Uninstall** option on the dialog box prompt.  
![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/uninstall-option3.jpg)
5. Disconnect the drive plugged into the PC.




<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139122/17108" target="_top" id="2139122">
  <img src="//a.impactradius-go.com/display-ad/17108-2139122" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139122/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




6. Plug the drive back into the computer to reinstall its driver.

## 8\. Update Your Motherboard’s Chipset Driver

 It might be necessary for some users to update motherboard drivers to fix this issue. To do so manually, you’ll need the motherboard model and manufacturer details. You can check those details as follows:

1. Open the Windows search box, and type a**System Information** keyword there.
2. Click**System Information** to view that app’s window.
3. Note down the**BaseBand Product** and**BaseBand Manufacturer** details.  
![Baseboard specs in System Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/baseboard-specs.jpg)
4. [Open the Command Prompt](https://www.makeuseof.com/windows-11-open-command-prompt/) if the System Information app doesn’t include a serial number for the motherboard.




<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135360/19272" target="_top" id="2135360">
  <img src="//a.impactradius-go.com/display-ad/19272-2135360" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135360/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




5. Execute this baseboard command:  
`wmic baseboard get product,Manufacturer,version,serialnumber`  
![The baseboard command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/baseboard-command.jpg)
6. Copy and paste the serial number for the motherboard shown within the Command Prompt into Notepad or another text editor.

 Then open the download section of your motherboard manufacturer’s website. Select your motherboard model and download its latest chipset driver from there. You can install the new driver for your motherboard with the downloaded driver (setup.exe) package file.

 The driver package might be included within a ZIP archive, which you’ll need to extract as outlined within this guide to[unzipping files in Windows](https://www.makeuseof.com/unzip-files-windows-10/) .

## Access Your Drive Again on Windows

 Those potential solutions will probably fix the “device which does not exist” drive error for most users. If they’re not enough, there could be an issue with your PC’s motherboard headers. In that case, consider taking your PC to a reputable repair service to resolve such an issue.

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
<li><a href="https://fox-info.techidaily.com/new-2024-approved-explore-more-with-these-videography-aids/"><u>[New] 2024 Approved Explore More with These Videography Aids</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-fifas-favorite-footage-charted-on-youtube/"><u>[New] FIFA's Favorite Footage Charted on YouTube</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-transforming-team-conversation-windows-pre-and-post-calls-for-2024/"><u>[Updated] Transforming Team Conversation Windows Pre & Post-Calls for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-monetizing-content-understanding-youtubes-cpm/"><u>2024 Approved Monetizing Content Understanding YouTube's CPM</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-quick-guide-to-samsung-galaxy-s23-fe-frp-bypass-instantly-by-drfone-android/"><u>A Quick Guide to Samsung Galaxy S23 FE FRP Bypass Instantly</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-tech-epochs-windows-7-key-to-boot-windows-11/"><u>Bridging the Tech Epochs: Windows 7 Key to Boot Windows 11</u></a></li>
<li><a href="https://youtube-data.techidaily.com/96870460-channel-elevation-strategy-quickly-reach-your-10k-view-quota/"><u>Channel Elevation Strategy – Quickly Reach Your 10K View Quota</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-the-windows-fatal-blue-screen-error-0x8007007e/"><u>Clearing Up the Windows Fatal Blue Screen Error: 0X8007007E</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-poco-c51-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Poco C51 Hard Reset | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/coordinating-devices-in-power-save-windows-states/"><u>Coordinating Devices in Power-Save Windows States</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-yellowed-displays-via-windows-settings/"><u>Correcting Yellowed Displays via Windows Settings</u></a></li>
<li><a href="https://extra-hints.techidaily.com/creating-a-visual-statement-with-stellar-podcast-artwork/"><u>Creating a Visual Statement with Stellar Podcast Artwork</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-and-remedying-error-0x8007000d-on-pcs/"><u>Deciphering and Remedying 'Error 0X8007000D' On PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deconstructing-mmc-glitches-resolving-snap-in-crashes/"><u>Deconstructing MMC Glitches: Resolving Snap-In Crashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-windows-media-storage-hurdles/"><u>Demystifying Windows Media Storage Hurdles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-how-copilot-key-upgrades-your-windows-11-experience/"><u>Discovering How Copilot Key Upgrades Your Windows 11 Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-routes-to-activate-windows-11s-calculator/"><u>Efficient Routes to Activate Windows 11'S Calculator</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/90844989-elevate-your-marketing-game-free-50-youtube-adornments-here/"><u>Elevate Your Marketing Game - Free 50 YouTube Adornments Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-net-runtime-errors-in-microsoft-os/"><u>Eliminating .NET Runtime Errors in Microsoft OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-characters-with-windows-11-map-tool/"><u>Explore Characters with Windows 11 Map Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-add-trusted-sites-on-windows-11/"><u>How to Add Trusted Sites on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-completely-uninstall-wsl-on-windows-11-and-11/"><u>How to Completely Uninstall WSL on Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-get-into-and-out-of-the-windows-terminals-focus-mode/"><u>How to Get Into and Out of the Windows Terminal’s Focus Mode</u></a></li>
<li><a href="https://extra-resources.techidaily.com/learn-how-to-directly-control-your-iphones-orientation/"><u>Learn How to Directly Control Your iPhone's Orientation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-triple-widget-grid-layout-in-windows-11/"><u>Mastering the Triple Widget Grid Layout in Windows 11</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/izing-engagement-with-youtube-shorts-content/"><u>Maximizing Engagement with YouTube Shorts Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-inactive-wsreset-troubleshooting-steps/"><u>Navigating Through Inactive WSReset Troubleshooting Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-printer-error-messages-on-windows/"><u>Navigating Through Printer Error Messages on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/organizing-and-naming-pro-level-windows-approach-max-156/"><u>Organizing & Naming: Pro-Level Windows Approach (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-fatal-roblox-error-messages/"><u>Overcoming Fatal Roblox Error Messages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11s-wi-fi-discovery-issues/"><u>Overcoming Windows 11'S Wi-Fi Discovery Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-based-thx-audio-glitches/"><u>Overcoming Windows-Based THX Audio Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-windows-11-shortcut-issues-for-f-keys/"><u>Resolve: Windows 11 Shortcut Issues for F Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionize-keyboard-use-redefine-functionality-via-fn-keys-on-windows-11/"><u>Revolutionize Keyboard Use: Redefine Functionality via FN Keys on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stopping-inadvertent-command-triggers-in-operating-system/"><u>Stopping Inadvertent Command Triggers in Operating System</u></a></li>
<li><a href="https://fix-guide.techidaily.com/strategies-for-apps-that-wont-download-from-play-store-on-lava-blaze-2-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Strategies for Apps That Wont Download From Play Store On Lava Blaze 2 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-5-tips-for-maximizing-wsl-2-in-windows/"><u>Top 5 Tips for Maximizing WSL 2 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/triggering-windows-11-dialer/"><u>Triggering Windows 11 Dialer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-the-purpose-of-an-x-symbol-for-your-drives/"><u>Understanding the Purpose of an X Symbol for Your Drives</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/unlock-motorola-g24-power-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>Unlock Motorola G24 Power Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-efficiency-mastering-the-toolbar-functionality-on-w11-os/"><u>Unveiling Efficiency: Mastering the Toolbar Functionality on W11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11s-invalid-name-error-a-step-by-step-guide/"><u>Win11's 'Invalid Name Error': A Step-by-Step Guide</u></a></li>
</ul></div>




