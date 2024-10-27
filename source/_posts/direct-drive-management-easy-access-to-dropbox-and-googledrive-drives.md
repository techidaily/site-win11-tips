---
title: "Direct Drive Management: Easy Access to Dropbox and GoogleDrive Drives"
date: 2024-10-23T20:52:17.736Z
updated: 2024-10-26T20:05:52.498Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Direct Drive Management: Easy Access to Dropbox and GoogleDrive Drives"
excerpt: "This Article Describes Direct Drive Management: Easy Access to Dropbox and GoogleDrive Drives"
keywords: Direct Drive Sync,Cloud Storage Access,Dropbox File Sharing,GoogleDrive Online Management,Easy Drive Control,Quick Cloud Integration,Secure Data Transfer
thumbnail: https://thmb.techidaily.com/b271e3424a506666cfc32d0840f08d97d7b8b324df271cfd9aff178b05822fa5.jpg
---

## Direct Drive Management: Easy Access to Dropbox and GoogleDrive Drives

 Today, cloud storage solutions are an essential part of our daily life, to the point that all major OSes come with support for such cloud services "baked in".

 Cloud storage services are easier than ever to access, they offer free storage, and as a bonus, they can make your life miserable if you want to access anything stored there using a quirky app instead of your web browser.

 That's why you can find extra third-party tools that assist in using cloud storage "as a normal drive". For this article, though, we'll do the same by exploiting Windows' built-in shared folders functionality!

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Common Cloud Storage Issues You May Encounter on Windows

 Dropbox, Google Drive, and similar cloud storage/sync services are easy to access from a web browser or the OS's default file manager. When you demand more than merely accessing your files, though, you may run into issues.

* Dropbox is accessible from a link in the file manager that brings you to its actual local folder, inside which your files are synced. Alternatively, you can visit that folder yourself. Dropbox cannot be "accessible through a letter" by default.
* Google Drive offers the option to map every account to a drive letter. However, try to access the contents of the virtual drive "behind" its "official" drive letter. Instead of your Google Drive files, you'll find a link to its local folder.
* Other alternatives may be even worse, with some only accessible locally through their custom clients.

 So, is it impossible to have your cloud storage account's "root folder" accessible directly from a drive letter?

 Thankfully, you can use a third-party solution for that. They're usually straightforward and can make your cloud storage "behave" like a normal drive on your computer. Still, you might want to avoid such apps for various reasons.

* Most cost money or are ad-supported.
* You'll be giving access to your data to another third party (on top of the cloud storage provider).
* The more apps and services that have access to your files, the higher the chances they'll fall into the wrong hands after a security breach.
* Extra software and services translate to increased complexity and potential for failure: some files may not sync when you expect them, metadata might get lost, etc.

 The major case against them is that there's no reason to use more software than you need.

## Why Not Just Use Google Drive's Folders?

 Let's see how Google Drive fails to offer proper access to its local folder through a letter.

1. Right-click on **Google Drive's icon** on the tray, click on the **cog icon** on the top right to access its menu and choose **Preferences**. Click on the **cog icon** in Google Drive Preferences window to access your account's settings. Ensure there's a drive letter assigned to your Google Drive.  
![Google Drive Settings Drive Letter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/google-drive-settings-drive-letter.jpg)
2. Visit the actual **drive letter** through any file manager and wonder how there's a "My Drive" folder instead of your files.  
![Google Drive Actual Drive Letter Contents](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/google-drive-actual-drive-letter-contents.jpg)
3. Try "entering" that folder and marvel at how the **path** changes to the true one where Google Drive's folder is stored, potentially breaking some apps.  
![Google Drive True Folder Path](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/google-drive-true-folder-path.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975807/19272" target="_top" id="1975807">
  <img src="//a.impactradius-go.com/display-ad/19272-1975807" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975807/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, let's fix, or rather "sidestep" this little issue by exploiting how network folders work on Windows.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100530/7443" target="_top" id="2100530">
  <img src="//a.impactradius-go.com/display-ad/7443-2100530" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100530/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Set Up Windows Shared Folders

 The first part of the process will be "sharing" the actual folder used by the cloud storage service that we want to access directly from a drive. Don't worry; you won't be sharing anything with anyone (apart from the cloud service provider where you already keep your files).

 For this example, we'll swap cloud services and "do Dropbox", but you can use the same process with any cloud storage service's local folder.

1. Run your favorite file manager and visit the path "directly above" your cloud storage folder (so that you can see it in your file manager).  
![Dropbox Folder In Windows Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dropbox-folder-in-windows-explorer.jpg)
2. Right-click on the folder and choose **Properties**.  
![Dropbox Folder Windows Explorer Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dropbox-folder-windows-explorer-properties.jpg)
3. Move to the **Sharing** tab and enable sharing for your folder. If you need help, check our guide on [how to access shared folders on Windows](https://www.makeuseof.com/unable-to-access-shared-folder-windows/).  
![Dropbox Folder Windows Explorer Properties Sharing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dropbox-folder-windows-explorer-properties-sharing.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036501/19272" target="_top" id="2036501">
  <img src="//a.impactradius-go.com/display-ad/19272-2036501" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036501/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Assign Letters to “Networked” Cloud Storage Folders

 Your folder should be accessible "as a share" by now, but it still isn't mapped to a letter. For that, we'll use Windows' ability to assign letters to "network drives" for easy access.

 Thankfully, Windows also recognizes the shared folder as "a network drive", even if it's stored locally.

1. Type "**\\\\localhost**" in your file manager's location bar to see all the shared folders on your local PC. Among them should be your newly shared cloud storage folder.  
![Windows Explorer Localhost Shared Folders](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-explorer-localhost-shared-folders.jpg)
2. Right-click on it and choose **Map network drive**.  
![Windows Explorer Localhost Shared Folders Menu Map Network Drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-explorer-localhost-shared-folders-menu-map-network-drive.jpg)
3. Choose the **letter** you want to assign to your cloud storage folder from the drop-down menu next to **Drive**. Click **Finish** to apply the change.  
![Windows Explorer Map Network Drive Letter Selection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-explorer-map-network-drive-letter-selection.jpg)
4. Visit your "new drive" using the letter you assigned, and you should have direct access to your cloud storage's contents.  
![Windows Explorer Direct Access To Dropbox Folder From Letter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-explorer-direct-access-to-dropbox-folder-from-letter.jpg)

 The above implies that you'll set up your cloud storage client to fully sync all files and folders/keep them stored locally.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135419/19272" target="_top" id="2135419">
  <img src="//a.impactradius-go.com/display-ad/19272-2135419" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135419/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## What About Using Subst?

 You may wonder why we didn't go with subst for this guide. Indeed, subst is so useful that we've made sure to include it on our list of [the essential Windows CMD commands you should know](https://www.makeuseof.com/tag/essential-windows-cmd-commands/). But what is it, how can it help, and how do you use it?

 Open Windows Search with **Win + S**, search for "**Terminal**" or "**PowerShell**", and choose **Run as Administrator**. There, use subst like:

subst DRIVE_LETTER: FULL:\PATH\TO\FOLDER

 For example, to map the folder "c:\\Cloud Drives\\Dropbox" to the letter "Z", the command would be:

subst Z: "C:\Cloud Drives\Dropbox"

 After that, your folder should be accessible from the drive you assigned to it. If the change isn't apparent immediately, log off and back on or restart your PC.

<!-- affiliate ads begin -->
<span id="1793213">
					<video width="864" height="1296" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## A Local Folder for Your Cloud Storage on Windows

 Thanks to Microsoft's somewhat square logic of "if it's a shared folder, you can map it, no matter where it is", it's easy to access your cloud storage folders directly from a drive letter. All it takes is to share them with yourself!

 Of course, power users would probably prefer to "subst them" to submission. Strangely, many forget that "subst" can also be used with cloud storage folders. Despite your chosen path, we can probably mark this little annoyance when using cloud storage folders with a "problem solved."

 Cloud storage services are easier than ever to access, they offer free storage, and as a bonus, they can make your life miserable if you want to access anything stored there using a quirky app instead of your web browser.

 That's why you can find extra third-party tools that assist in using cloud storage "as a normal drive". For this article, though, we'll do the same by exploiting Windows' built-in shared folders functionality!

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-join-the-social-scene-facebook-live-streams-on-roku-tv/"><u>[New] 2024 Approved Join The Social Scene Facebook Live Streams on Roku TV</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-recovering-lost-linkages-restore-facebook-video-suggestions/"><u>[New] Recovering Lost Linkages Restore Facebook Video Suggestions</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-efficient-practices-logging-google-voice-dialogues/"><u>[Updated] 2024 Approved Efficient Practices Logging Google Voice Dialogues</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-iphone-night-photography-step-by-step/"><u>2024 Approved IPhone Night Photography Step by Step</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719328086208-calibrate-display-colors-go-to-settings-)-system-)-display-and-use-the-built-in-calibration-tool-for-accurate-color-representation/"><u>Calibrate Display Colors: Go to 'Settings' > 'System' > 'Display' And Use the Built-In Calibration Tool for Accurate Color Representation.</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/experience-reimagined-computing-with-style-the-ultimate-review-of-the-apple-imacs-striking-power-and-4k-visual-delight/"><u>Experience Reimagined Computing with Style: The Ultimate Review of the Apple iMac's Striking Power and 4K Visual Delight</u></a></li>
<li><a href="https://common-error.techidaily.com/gadget-gone-wrong-now-right/"><u>Gadget Gone Wrong, Now Right</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-gaming-service-failures-on-pcs-and-laptops/"><u>How To Resolve Gaming Service Failures on PCs and Laptops</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-box-by-strategy-market-success-blueprints/"><u>In 2024, Box by Strategy Market Success Blueprints</u></a></li>
<li><a href="https://win-amazing.techidaily.com/latest-nvidia-rtx-2080-driver-version-for-optimal-performance-on-windows-11-systems/"><u>Latest NVIDIA RTX 2080 Driver Version for Optimal Performance on Windows 11 Systems</u></a></li>
<li><a href="https://fox-that.techidaily.com/lost-iphone-application-a-comprehensive-guide-to-recover-vanished-apps/"><u>Lost iPhone Application: A Comprehensive Guide to Recover Vanished Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-of-hyper-v-installation-on-w11-home-systems/"><u>Master the Art of Hyper-V Installation on W11 Home Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-your-hard-drives-terrain-a-guide-to-diskusage-in-windows/"><u>Navigating Through Your Hard Drive's Terrain: A Guide to DiskUsage in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refining-windows-11-for-superior-usability/"><u>Refining Windows 11 for Superior Usability</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategy-to-eradicate-error-0x80300024-on-pcs/"><u>Strategy to Eradicate Error 0X80300024 on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-swordsmans-secrets-tackle-windows-lag-in-star-wars-battlefront-2/"><u>Swift Swordsman's Secrets: Tackle Windows Lag in Star Wars Battlefront 2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-non-operational-amd-radeon-ssp-on-windows/"><u>Troubleshooting Non-Operational AMD Radeon SSP on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-laptop-or-desktop-windows-era/"><u>Unveiling Laptop or Desktop Windows Era</u></a></li>
<li><a href="https://techidaily.com/ways-to-fix-the-failed-to-parse-the-corrupted-excel-2003-file-error-by-stellar-guide/"><u>Ways to Fix the Failed to Parse the Corrupted Excel 2003 File Error</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    