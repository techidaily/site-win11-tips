---
title: Harnessing the Potential of DiskUsage for In-Depth Drive Space Examination
date: 2024-06-25T16:49:05.840Z
updated: 2024-06-26T16:49:05.840Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Harnessing the Potential of DiskUsage for In-Depth Drive Space Examination
excerpt: This Article Describes Harnessing the Potential of DiskUsage for In-Depth Drive Space Examination
keywords: DiskSpace Analysis,Usage Insights,Storage Utilization,Drive Data Review,Storage Efficiency,File System Overview,Space Capacity Exam
thumbnail: https://thmb.techidaily.com/0ab25ce0bb8d4ab2078e845cda986fa9a30d3de551640bc5deeb7f8730f9ba76.jpg
---

## Harnessing the Potential of DiskUsage for In-Depth Drive Space Examination

 The DiskUsage.exe tool can be used to analyze the contents of any drive or folder on Windows 11\. DiskUsage is accessed from the command line and includes many options for filtering and refining the file data that can be output. In certain situations, this can make it far more useful than GUI tools like Storage Sense.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

## View Disk Usage of Any Drive or Folder

 The simplest way to use the DiskUsage command line tool is to get an overview of how space is currently used in almost a drive or folder. We have used the tool on Windows 11, but it is also available on Windows 10\.

1. Run the Command Prompt as an admin. If you need help, check out [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. In Command Prompt type **DiskUsage** followed by the path to the drive or folder you want to analyze.
3. For example, to view the disk usage of the Pictures folder, type: **DiskUsage C:\\Users\\UserName\\Pictures**, and press **Enter**.  
![The disk usage command in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-cmd.jpg)
4. To see the SizeOnDisk number in a human-readable format, e.g. KB, MB, or GB, add **/h** to the end of the command.
5. In our example, this looks like **DiskUsage C:\\Users\\UserName\\Pictures /h**.  
![Disk usage date displayed in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-data.jpg)

 You can use DiskUsage to analyze any folder in the same way. You can even check internal and external drives, including the C: drive. Bear in mind that analyzing a drive such as C: will spew out a huge list of files and folders in DiskUsage.

 If using DiskUsage.exe seems too complicated, you can easily view how disk space is being used with [Storage Sense](https://www.makeuseof.com/windows-11-storage-sense-guide/).

## List All Files Larger Than a Specified Size

 You can refine the data displayed in DiskUsage based on file size. So if, for example, you only want to include files over 500MB, you can set it to ignore smaller files.

1. To only include files above a specific size, you need to add the minFileSize option to the command.
2. As an example: **DiskUsage /minFileSize=6553600 C:\\Users\\UseName\\Downloads /h**.
3. This will only look for files in Downloads larger than 50MB and then display the disk space those files occupy in that location.
4. The file size number must be entered in bytes, so you might have to convert MB to Byte using an online conversion tool.

 For a more detailed view of large files, including file name as well as size, you can use the **/u** command modifier. This allows you to list a defined number of the largest files in the drive or folder.

1. To do this type: **DiskUsage C:\\Users\\UserName\\Downloads /h /u=15**.
2. The 15 largest files in the Downloads folder will now be listed in Command Prompt.  
![file data listed in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-list.jpg)
3. You can replace the number with any other you want to use. For example, to see the top 5 files taking up space, use **/u=5**.
4. Make sure to include the **/h** option so that the output is in a format that's easy to read.

 After identifying what is taking up the most space, you can use any one of these [methods to delete large files](https://www.makeuseof.com/windows-11-delete-select-files/).

## Additional DiskUsage Command Options

 The DiskUsage tool contains several other useful options that you can use to filter the output. You can filter by filename, display reserved space, or the largest directories within the folder.

 For example, to filter by filename add **/n=installer** to the end of the command to display only files that contain the word installer.

 You can see a complete list of the options by typing **DiskUsage /?** and pressing **Enter**.

![A list of DiskUsage options in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-options.jpg)

## Analyze Drive Space With DiskUsage

 Many of the available command line tools are extremely useful for maintaining and managing your Windows PC. And as this guide shows, DiskUsage.exe is a powerful alternative to graphical UI tools such as Storage Sense if you want to really dig down into how your drive space is being used.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/methods-to-recover-faulty-windows-file-organizer/"><u>Methods to Recover Faulty Windows File Organizer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-missing-mfc71udll-in-windows-os/"><u>Addressing Missing Mfc71u.dll in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-dxgierrordeviceremoved-error-in-windows-10-and-11/"><u>How to Fix the DXGI_ERROR_DEVICE_REMOVED Error in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoidance-and-remediation-for-a-frozen-resource-monitor-app-in-windows-11/"><u>Avoidance and Remediation for a Frozen Resource Monitor App in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-the-challenge-the-ultimate-fix-for-xbox-game-passs-error-code-0x800700e9/"><u>Conquering the Challenge: The Ultimate Fix for Xbox Game Pass’s Error Code 0X800700E9</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-printer-connection-failsafes-in-windows/"><u>Overcoming Printer Connection Failsafes in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stifling-windows-restart-requests/"><u>Stifling Windows Restart Requests</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-guide-rectifying-image-importer-issues-with-ios-on-windows-11-pcs/"><u>Mastery Guide: Rectifying Image Importer Issues with iOS on Windows 11 PCs</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-change-your-sim-pin-code-on-your-xiaomi-redmi-note-12-pro-4g-phone-by-drfone-android/"><u>How To Change Your SIM PIN Code on Your Xiaomi Redmi Note 12 Pro 4G Phone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-minisnap-probebericht-uberprufung/"><u>[New] MiniSnap Probebericht Überprüfung</u></a></li>
<li><a href="https://howto.techidaily.com/android-screen-stuck-general-realme-narzo-60-5g-partly-screen-unresponsive-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Screen Stuck General Realme Narzo 60 5G Partly Screen Unresponsive | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/why-is-ipogo-not-working-on-poco-m6-5g-fixed-drfone-by-drfone-virtual-android/"><u>Why is iPogo not working On Poco M6 5G? Fixed | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-full-tutorial-to-bypass-your-realme-c53-face-lock-by-drfone-android/"><u>In 2024, Full Tutorial to Bypass Your Realme C53 Face Lock?</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-contacts-from-samsung-galaxy-a15-5g-by-fonelab-android-recover-contacts/"><u>How to recover deleted contacts from Samsung Galaxy A15 5G.</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-a-dual-method-approach-for-instagram-reel-downloads/"><u>[Updated] A Dual Method Approach for Instagram Reel Downloads</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-funny-bone-flickers-the-top-20-tiktok-jokes-and-pranks-for-2024/"><u>[New] Funny Bone Flickers  The Top 20 TikTok Jokes and Pranks for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-honor-magic-6-pro-drfone-by-drfone-virtual-android/"><u>How to use Snapchat Location Spoofer to Protect Your Privacy On Honor Magic 6 Pro? | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>