---
title: "Streamlining File Sharing: Using Dropbox/Google Drive From Windows Paths"
date: 2024-06-25T16:31:30.555Z
updated: 2024-06-26T16:31:30.555Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Streamlining File Sharing: Using Dropbox/Google Drive From Windows Paths"
excerpt: "This Article Describes Streamlining File Sharing: Using Dropbox/Google Drive From Windows Paths"
keywords: File Sharing Streamline,Cloud Storage Access,Path Integration Dropbox,Google Drive System Link,Windows File Transfer,Syncing Files Efficiently,Remote File Connectivity
thumbnail: https://thmb.techidaily.com/bf80edb76b200416e748e081aeadfa243850d855fed3e04f595dd2c29ba995d4.jpg
---

## Streamlining File Sharing: Using Dropbox/Google Drive From Windows Paths

 Today, cloud storage solutions are an essential part of our daily life, to the point that all major OSes come with support for such cloud services "baked in".

 Cloud storage services are easier than ever to access, they offer free storage, and as a bonus, they can make your life miserable if you want to access anything stored there using a quirky app instead of your web browser.

 That's why you can find extra third-party tools that assist in using cloud storage "as a normal drive". For this article, though, we'll do the same by exploiting Windows' built-in shared folders functionality!

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

 Now, let's fix, or rather "sidestep" this little issue by exploiting how network folders work on Windows.

## How to Set Up Windows Shared Folders

 The first part of the process will be "sharing" the actual folder used by the cloud storage service that we want to access directly from a drive. Don't worry; you won't be sharing anything with anyone (apart from the cloud service provider where you already keep your files).

 For this example, we'll swap cloud services and "do Dropbox", but you can use the same process with any cloud storage service's local folder.

1. Run your favorite file manager and visit the path "directly above" your cloud storage folder (so that you can see it in your file manager).  
![Dropbox Folder In Windows Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dropbox-folder-in-windows-explorer.jpg)
2. Right-click on the folder and choose **Properties**.  
![Dropbox Folder Windows Explorer Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dropbox-folder-windows-explorer-properties.jpg)
3. Move to the **Sharing** tab and enable sharing for your folder. If you need help, check our guide on [how to access shared folders on Windows](https://www.makeuseof.com/unable-to-access-shared-folder-windows/).  
![Dropbox Folder Windows Explorer Properties Sharing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dropbox-folder-windows-explorer-properties-sharing.jpg)

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

## What About Using Subst?

 You may wonder why we didn't go with subst for this guide. Indeed, subst is so useful that we've made sure to include it on our list of [the essential Windows CMD commands you should know](https://www.makeuseof.com/tag/essential-windows-cmd-commands/). But what is it, how can it help, and how do you use it?

 Open Windows Search with **Win + S**, search for "**Terminal**" or "**PowerShell**", and choose **Run as Administrator**. There, use subst like:

subst DRIVE_LETTER: FULL:\PATH\TO\FOLDER

 For example, to map the folder "c:\\Cloud Drives\\Dropbox" to the letter "Z", the command would be:

subst Z: "C:\Cloud Drives\Dropbox"

 After that, your folder should be accessible from the drive you assigned to it. If the change isn't apparent immediately, log off and back on or restart your PC.

## A Local Folder for Your Cloud Storage on Windows

 Thanks to Microsoft's somewhat square logic of "if it's a shared folder, you can map it, no matter where it is", it's easy to access your cloud storage folders directly from a drive letter. All it takes is to share them with yourself!

 Of course, power users would probably prefer to "subst them" to submission. Strangely, many forget that "subst" can also be used with cloud storage folders. Despite your chosen path, we can probably mark this little annoyance when using cloud storage folders with a "problem solved."

 Cloud storage services are easier than ever to access, they offer free storage, and as a bonus, they can make your life miserable if you want to access anything stored there using a quirky app instead of your web browser.

 That's why you can find extra third-party tools that assist in using cloud storage "as a normal drive". For this article, though, we'll do the same by exploiting Windows' built-in shared folders functionality!

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/winning-editorial-techniques-select-from-the-top-8-video-trimming-titles/"><u>Winning Editorial Techniques: Select From The Top 8 Video Trimming Titles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-output-with-windows-streamlined-launcher/"><u>Maximize Output with Windows' Streamlined Launcher</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-restricted-it-administrator-message-in-os/"><u>Eliminating 'Restricted IT Administrator' Message in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbo-charging-windows-printer-performance/"><u>Turbo-Charging WIndows Printer Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-audio-cd-production-from-mp3-files-an-efficient-guide-to-using-imgburn-in-windows/"><u>Mastering Audio CD Production From MP3 Files: An Efficient Guide to Using ImgBurn in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-data-streams-with-netstat-on-microsofts-latest-windows/"><u>Navigating Data Streams with Netstat on Microsoft's Latest Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-in-game-audio-output-solving-windows-issues-in-valorant/"><u>Realigning In-Game Audio Output: Solving Windows Issues in Valorant</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-windows-to-run-this-application-you-must-install-net-core-error/"><u>How to Fix the Windows “To Run This Application, You Must Install .NET Core” Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-visual-display-top-5-ideal-windows-pc-clock-themed-screensavers/"><u>Enhance Visual Display: Top 5 Ideal Windows PC Clock-Themed Screensavers</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-decoding-effective-tiktok-advertising-methods/"><u>2024 Approved  Decoding Effective TikTok Advertising Methods</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-unlocking-the-secrets-to-overwatch-video-capture/"><u>[New] In 2024, Unlocking the Secrets to Overwatch Video Capture</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/a-framework-for-employing-videos-in-educational-settings/"><u>A Framework for Employing Videos in Educational Settings</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/frp-hijacker-by-hagard-download-and-bypass-your-itel-s23plus-frp-locks-by-drfone-android/"><u>FRP Hijacker by Hagard Download and Bypass your Itel S23+ FRP Locks</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-change-nubia-z50s-pro-lock-screen-clock-in-seconds-by-drfone-android/"><u>In 2024, How To Change Nubia Z50S Pro Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/1715860288330-2024-approved-screen-savvy-secure-your-captures-chromebooks-top-4-techniques/"><u>2024 Approved  Screen Savvy  Secure Your Captures - Chromebook's Top 4 Techniques!</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-best-anti-tracker-software-for-sony-xperia-10-v-drfone-by-drfone-virtual-android/"><u>In 2024, Best Anti Tracker Software For Sony Xperia 10 V | Dr.fone</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/2024-approved-navigating-the-soundscape-of-premiere-pro-simple-strategies-for-audio-layer-management/"><u>2024 Approved Navigating the Soundscape of Premiere Pro Simple Strategies for Audio Layer Management</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-complete-testimonials-of-gecatas-recorder/"><u>[New] 2024 Approved  Complete Testimonials of Gecata's Recorder</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-ultimate-guide-to-voice-to-text-conversion-using-ms-words-advanced-features/"><u>[Updated] The Ultimate Guide to Voice-to-Text Conversion Using MS Word's Advanced Features</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>