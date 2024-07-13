---
title: Demystifying Directory Capacity Assessment via Windows PowerShell
date: 2024-07-12T16:42:39.603Z
updated: 2024-07-13T16:42:39.603Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Demystifying Directory Capacity Assessment via Windows PowerShell
excerpt: This Article Describes Demystifying Directory Capacity Assessment via Windows PowerShell
keywords: DirCapacityAssessmentWP,WPShieldingTechniques,CapacityEvaluationWS,PowerShellDirectoryChecks,WindowsShieldPower,TechWMDirInspection,PowerShellCapacityTest
thumbnail: https://thmb.techidaily.com/52b4eaebcfcbc6c7fedd891af89526f0d5ee168fe7bb540778411c3fb0605514.jpg
---

## Demystifying Directory Capacity Assessment via Windows PowerShell

 If you want to investigate which folders are taking up your storage space, you can check the folder's size to determine what's hogging your drive. Checking folder size is also helpful if you need to move a large folder to a USB drive or cloud storage. An easy way to do this on Windows is to use File Explorer and open the folder Properties dialog.

 File Explorer, however, can be slow to determine the size of a large folder. And not ideal if you want to manage files and folders on multiple computers in an organization. To remedy this, you can use PowerShell to quickly calculate folder sizes on Windows.

## How to Calculate a Folder's Size Using PowerShell on Windows
![powershell cmdlet to view folder size bytes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-cmdlet-to-view-folder-size-bytes.jpg)

 To calculate a folder's size, you'll need to use the two PowerShell cmdlets, Get-ChildItem and Measure-Object, followed by the Length property and Sum parameter.

 The cmdlet Get-ChildItem lets you retrieve information from a specified directory and its sub-directories. The Measure-Object cmdlet and the associated properties and parameters calculate the sum of the length property for the items returned by the Get-ChildItem (alias 'cgi') cmdlet.

 If you are new to PowerShell, you may want to read our explainer on [essential PowerShell cmdlets](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) to understand the basics of PowerShell.

 Now that you are familiar with the PowerShell commands, here is how to use them to get any folder size.

1. Press the **Win** key and type **powershell**.
2. Next, right-click on **Windows PowerShell** and select **Run as administrator**. Click **Yes** if prompted by **User Account Control**.
3. In the PowerShell window, type the following command:  
`Get-ChildItem FolderPath | Measure-Object -Property Length -sum`
4. In the above command, replace **FolderPath** with the directory path where your folder is saved. For example, if you want to calculate the size of the Download folder located in the **E:\\** drive, then the full command will look like this:  
`Get-ChildItem E:\Download | Measure-Object -Property Length -sum`
5. The return will show the item count in the folder and its size in bytes. You'll need to divide the total sum by **1024** to get the size in **KBs** (Kilobytes). Divide it by **1024** again to get the size in **MBs** (Megabytes) and so on.

 Alternatively, you can use the .sum property to retrieve the total size and divide it by 1 million or billion to convert it into megabytes or gigabytes.

![powershell cmdlet to view folder size megabytes gigabytes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-cmdlet-to-view-folder-size-megabytes-gigabytes.jpg)

 For example, if you want to know the value in gigabytes (MBs), type the following command and press **Enter**:

`(gci E:\Download | measure Length -s).sum / 1Mb`

 Similarly, replace **1Mb** with **1Gb** to retrieve the folder size in gigabytes.

`(gci E:\Download | measure Length -s).sum / 1Gb`

 If you want to identify the size of specific types of files in a directory, you can use the wildcard character **\*** followed by the file extension type. It will only show the file size for the specified file type.

 For example, to find how much space is taken by the images in a folder, use the following command:

![powershell cmdlet to view folder by file type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-cmdlet-to-view-folder-by-file-type.jpg)

`(gci E:\download *.jpg | measure Length -s).sum / 1Mb`

 Adding a wildcard character lets you determine if a specific file type takes the most space in the folder. You can then filter the contents based on the file extension and delete or move them if necessary.

## How to Get the Subfolder Size Using PowerShell
![powershell cmdlet to view folder subfolder size](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-cmdlet-to-view-folder-subfolder-size.jpg)

 The above command will only calculate the size of your primary directory or folder. To calculate the total size of files in the specified directory and its subdirectories, you'll need to add the **\-Recurse** parameter to the above command. In addition, we'll use the -force parameter to access hidden and system files.

 For example, to get the total size of your C:\\Users directory and its subdirectories, including the hidden files, the PowerShell command will look something like this:

`((gci -force c:\Users -Recurse -ErrorAction SilentlyContinue| measure Length -s).sum / 1Gb)`

 The output in this instance shows 54 GB approx. as the total size of the c:\\users folder. In the above command, the -ErrorAction SilentlyContinue parameter is used to suppress any error messages that may occur during the process.

## How to Get the Subfolder Size in a Table Format Using PowerShell
![windows powershell ISE script folder size view](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-powershell-ise-script-folder-size-view.jpg)

 If you want to know the size of all the subfolders individually, you can run a PowerShell script to get a graphical view of all the subfolders and their sizes. A script is usually helpful if you have a large directory with multiple subfolders and need to work on them frequently.

 To run this script, you can use PowerShell ISE. Here's how to do it:

1. Press the **Win key** and type **PowerShell ISE**. Click on **Windows PowerShell ISE** from the search result.  
![powershell ise start menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/powershell-ise-start-menu.jpg)
2. Next, copy and paste the following command into the PowerShell ISE console. Make sure to change the directory from c:\\ to your preferred directory.  
`$targetfolder = 'C:\'  
$dataColl = Get-ChildItem -Force $targetfolder -Directory -ErrorAction SilentlyContinue | ForEach-Object {  
   $len = Get-ChildItem -Recurse -Force $_.FullName -File -ErrorAction SilentlyContinue | Measure-Object -Property Length -Sum | Select-Object -ExpandProperty Sum  
   $foldername = $_.FullName  
   $foldersize = '{0:N2} GB' -f ($len / 1Gb)  
   [PSCustomObject]@{  
       foldername = $foldername  
       foldersizeGb = $foldersize  
   }  
}  
$dataColl | Out-GridView -Title "Size of Subdirectories in $targetfolder"`
3. Next, click **Run Script** or press **F5** and wait for the script to execute. Depending on the folder size, you'll see a "**Size Of Subdirectories**" dialog listing all the subdirectories with their size.

 In addition to this, you can make use of the PowerShell comparison operators to filter results. For example, to get file size for folders created between June 2023 and July 2023, you can use the following command:

`(gci -force E:\Download &ndash;Recurse -ErrorAction SilentlyContinue | ? {$_.CreationTime -gt '01/23/23' -AND $_.CreationTime -lt '02/23/23'}| measure Length -s).sum / 1Gb`

 In the above command, **"?"** is an alias for the **Where-Object** cmdlet, **\-gt, -AND, -It** are comparison operators, and **CreationTime** is a condition. The command checks if the CreationTime of files in the subdirectory falls within the specified date range and shows output only if the condition is satisfied. If you get an error, ensure your date and time format in the command matches the system's format and try again.

## Get the Folder and Subfolder Size Using PowerShell

 File Explorer on Windows can help you calculate the size of any folder and file. However, if you work with multiple large folders or in an organization with hundreds of computers to manage, using PowerShell can help you get things done faster.

 That said, if you prefer a more GUI-based solution, consider using a disk analyzer tool. These tools can help you visualize the system's file structure and show a report detailing the contents taking up most space on your system.

 File Explorer, however, can be slow to determine the size of a large folder. And not ideal if you want to manage files and folders on multiple computers in an organization. To remedy this, you can use PowerShell to quickly calculate folder sizes on Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/mitigating-windows-error-loadlib-err-87/"><u>Mitigating Windows Error LoadLib Err 87</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-the-ultimate-guide-to-quieter-skype-talks/"><u>[New] The Ultimate Guide to Quieter Skype Talks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safeguarding-internal-builds-in-windows-11/"><u>Safeguarding Internal Builds in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-interface-adding-portable-software-to-w11/"><u>Optimize Your Interface: Adding Portable Software to W11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-explore-15-exceptional-vr-cam-solutions-like-gopro/"><u>2024 Approved  Explore 15 Exceptional VR Cam Solutions Like GoPro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-multiple-users-ms-logins-on-pc/"><u>Tackling Multiple Users' MS Logins on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-solutions-for-we-encountered-an-error-during-oculus-install/"><u>Step-By Step Solutions for We Encountered an Error During Oculus Install</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-dubbing-videos-with-voiceovers-wondershare-filmora-tutorial/"><u>Updated Dubbing Videos With Voiceovers | Wondershare Filmora Tutorial</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-elevate-your-lol-gameplay-on-camera-three-methods/"><u>In 2024, Elevate Your LOL Gameplay on Camera - Three Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-failure-to-install-win11s-v22h2-update/"><u>Navigating Through Failure to Install Win11's V22H2 Update</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-finding-the-perfect-dj-template-video-download-for-your-events/"><u>[Updated] 2024 Approved  Finding the Perfect DJ Template Video Download for Your Events</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-windows-standard-power-profile/"><u>Restoring Windows' Standard Power Profile</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-capturing-live-gaming-decide-on-obsshadowplay/"><u>[Updated] 2024 Approved  Capturing Live Gaming - Decide on OBS/ShadowPlay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-needed-parts-error-on-windows-1011-systems/"><u>Solving Needed Parts Error on Windows 10/11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-setting-up-windows-outlook-preview/"><u>Quick Guide: Setting Up Windows' Outlook Preview</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safe-windows-storage-expansion-methods/"><u>Safe Windows Storage Expansion Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaiming-lost-wireless-ties-with-these-10-windows-10-tweaks/"><u>Reclaiming Lost Wireless Ties with These 10 Windows 10 Tweaks</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-ultimate-guide-7-best-waterproof-video-recorders/"><u>[New] The Ultimate Guide  7 Best Waterproof Video Recorders</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-securely-shutting-down-your-instagram-presence-forever-for-2024/"><u>[Updated] Securely Shutting Down Your Instagram Presence Forever for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-challenges-of-o365-sync-failures-in-win11/"><u>Overcoming the Challenges of O365 Sync Failures in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/system-mastery-a-path-through-preferences/"><u>System Mastery: A Path Through Preferences</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-6-proven-ways-to-unlock-zte-blade-a73-5g-phone-when-you-forget-the-password-by-drfone-android/"><u>In 2024, 6 Proven Ways to Unlock ZTE Blade A73 5G Phone When You Forget the Password</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-microsoft-pc-manager-bar-tools-on-w11/"><u>Navigating Microsoft PC Manager Bar Tools on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackle-windows-camera-problems-with-expert-tips/"><u>Tackle Windows Camera Problems with Expert Tips</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/how-to-download-tiktok-musically-videos-quickly-for-2024/"><u>How to Download TikTok (Musical.ly) Videos Quickly for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-2024-approved-how-to-create-liquid-water-reveal-intro/"><u>Updated 2024 Approved How to Create Liquid Water Reveal Intro?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-counteract-internal-error-with-remote-desktop/"><u>Strategies to Counteract Internal Error with Remote Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/neatness-noted-navigating-a-tidier-windowed-explore/"><u>Neatness Noted: Navigating a Tidier Windowed Explore</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-become-a-tiktok-pro-in-no-time-essential-recording-and-post-processing-techniques/"><u>[Updated] In 2024, Become a TikTok Pro in No Time  Essential Recording and Post-Processing Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-freeing-up-your-c-drive-space/"><u>Mastering the Art of Freeing Up Your C: Drive Space</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-quick-setup-obs-and-zoom-coexistence-made-simple/"><u>2024 Approved  Quick Setup  OBS & Zoom Coexistence Made Simple</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-systemsettings-issues-on-win11/"><u>Strategies to Overcome SystemSettings Issues on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/traverse-backward-commanding-windows-11-history/"><u>Traverse Backward: Commanding Windows 11 History</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-internet-unreachability-issue/"><u>Overcoming Internet Unreachability Issue</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-intercept-text-messages-on-lava-blaze-2-5g-drfone-by-drfone-virtual-android/"><u>How to Intercept Text Messages on Lava Blaze 2 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-top-5-alternative-editors-beyond-youtubes-limits/"><u>[Updated] 2024 Approved  Top 5 Alternative Editors  Beyond Youtube's Limits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-speech-output-in-windows-environment/"><u>Mastering Speech Output in Windows Environment</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-elevate-your-visual-storytelling-with-lut-techniques-in-premiere-for-2024/"><u>[Updated] Elevate Your Visual Storytelling with LUT Techniques in Premiere for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-security-by-learning-the-quickest-ways-to-access-credentials-in-win11/"><u>Skyrocket Security by Learning the Quickest Ways to Access Credentials in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-tips-for-modifying-windows-passcode/"><u>Quick Tips for Modifying Windows Passcode</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-5-popular-guitar-recording-software-for-guitarists/"><u>Updated 5 Popular Guitar Recording Software for Guitarists</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/2024-approved-expand-your-reach-effective-business-tactics-on-tiktok/"><u>2024 Approved  Expand Your Reach  Effective Business Tactics on TikTok</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-fix-locked-apple-id-from-iphone-x-by-drfone-ios/"><u>How to Fix Locked Apple ID from iPhone X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-restore-razer-devices-detection-via-synapse-on-windows/"><u>Steps to Restore Razer Devices Detection via Synapse on Windows</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-perfect-pairing-of-podcast-apps-and-android-top-6-recommendations/"><u>2024 Approved  Perfect Pairing of Podcast Apps & Android  Top 6 Recommendations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-file-lockdowns-access-restoration-on-pcs/"><u>Reversing File Lockdowns: Access Restoration on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-and-reinforcing-win-1011-menu-functionality/"><u>Reactivating and Reinforcing Win 10/11 Menu Functionality</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/chromebooks-and-hp-perfect-your-video-capture/"><u>Chromebooks and HP  Perfect Your Video Capture</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-windows-photos-apps-generative-erase-is-actually-great/"><u>The Windows Photos App's Generative Erase Is Actually Great</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-tailoring-your-youtube-videos-with-customized-text-and-link-embeddings/"><u>[New] Tailoring Your YouTube Videos with Customized Text & Link Embeddings</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-remove-iphone-14-plus-sim-lock-by-drfone-ios/"><u>How to Remove iPhone 14 Plus SIM Lock?</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/step-into-new-dimensions-with-jaunt-vr-review-for-2024/"><u>Step Into New Dimensions with Jaunt VR Review for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-lost-window-steam-connectivity/"><u>Restoring Lost Window-Steam Connectivity</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-universal-unlock-pattern-for-samsung-galaxy-s23-by-drfone-android/"><u>In 2024, Universal Unlock Pattern for Samsung Galaxy S23</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-manage-disks-keyways-into-windows-11s-storage-manager/"><u>Swiftly Manage Disks: Keyways Into Windows 11'S Storage Manager</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-videos-from-realme-12-pro-5g-to-ipad-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Videos from Realme 12 Pro 5G to iPad | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/method-to-start-windows-11s-admin-powershell-instance/"><u>Method to Start Windows 11'S Admin PowerShell Instance</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-premier-8-safe-video-communication-programs-for-smbs-for-2024/"><u>[Updated] Premier 8 Safe Video Communication Programs for SMBs for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-streamlining-tv-downloads-a-step-by-step-recording-approach/"><u>[New] 2024 Approved  Streamlining TV Downloads  A Step-by-Step Recording Approach</u></a></li>
<li><a href="https://fix-guide.techidaily.com/in-2024-how-to-pause-life360-location-sharing-for-tecno-spark-10-4g-drfone-by-drfone-virtual-android/"><u>In 2024, How To Pause Life360 Location Sharing For Tecno Spark 10 4G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-guide-for-converting-cr2-images-to-windows-jpeg-files/"><u>Stepwise Guide for Converting CR2 Images to Windows JPEG Files</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-direct-call-setup-using-whatsapp-browser-on-your-notebook/"><u>[Updated] 2024 Approved  Direct Call Setup  Using WhatsApp Browser on Your Notebook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secrets-to-turn-off-lurking-apps-in-window-11/"><u>Secrets to Turn Off Lurking Apps in Window 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/one-device-one-storage-transferring-files-smoothly/"><u>One Device, One Storage  Transferring Files Smoothly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-prevent-apex-legends-crashes-w11/"><u>Strategies to Prevent Apex Legends Crashes W11</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-pcandroid-friendly-methods-to-post-videos-on-facebook-successfully/"><u>[New] PC/Android-Friendly Methods to Post Videos on Facebook Successfully</u></a></li>
</ul></div>
