---
title: "Unlocking the Secrets of Windows' Drive Space: A Guide to DiskUsage"
date: 2024-09-09T21:44:16.934Z
updated: 2024-09-16T20:20:09.740Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlocking the Secrets of Windows' Drive Space: A Guide to DiskUsage"
excerpt: "This Article Describes Unlocking the Secrets of Windows' Drive Space: A Guide to DiskUsage"
keywords: WinDiskSpaceTips,DiskUsageOverview,FreeDiskWindows,CleanupDiskWindows,DriveFreeStorage,ManageWinSpace,OptimizeWindowsDrive
thumbnail: https://thmb.techidaily.com/0d5172690106aeb0b1e42f6467812ce6f42bcdb66b69630f22d7099f56101e88.jpeg
---

## Unlocking the Secrets of Windows' Drive Space: A Guide to DiskUsage

 The DiskUsage.exe tool can be used to analyze the contents of any drive or folder on Windows 11\. DiskUsage is accessed from the command line and includes many options for filtering and refining the file data that can be output. In certain situations, this can make it far more useful than GUI tools like Storage Sense.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129738/7443" target="_top" id="2129738">
  <img src="//a.impactradius-go.com/display-ad/7443-2129738" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129738/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Analyze Drive Space With DiskUsage

 Many of the available command line tools are extremely useful for maintaining and managing your Windows PC. And as this guide shows, DiskUsage.exe is a powerful alternative to graphical UI tools such as Storage Sense if you want to really dig down into how your drive space is being used.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://tech-haven.techidaily.com/can-ai-become-uncontrollable/"><u>Can AI Become Uncontrollable?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/evaluating-windows-11s-restricted-environment-advantages/"><u>Evaluating Windows 11’S Restricted Environment Advantages</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-remove-flashlight-from-iphone-6s-lock-screen-drfone-by-drfone-ios/"><u>How To Remove Flashlight From iPhone 6s Lock Screen | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-unlock-apple-iphone-11-pro-when-we-dont-have-apple-id-or-password-by-drfone-ios/"><u>How to Unlock Apple iPhone 11 Pro When We Dont Have Apple ID or Password?</u></a></li>
<li><a href="https://some-approaches.techidaily.com/master-the-art-of-swift-srt-to-text-transformation-for-2024/"><u>Master the Art of Swift SRT to Text Transformation for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-permission-based-saves-windows-edition/"><u>Navigating Through Permission-Based Saves: Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-resolving-gl-error-code-3-on-nvidia-and-win11/"><u>Strategies for Resolving GL Error Code 3 on NVIDIA & Win11</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/the-ultimate-list-of-elite-code-bootcamps-you-cant-miss/"><u>The Ultimate List of Elite Code Bootcamps You Can't Miss!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-typing-mastering-windows-11s-language-options/"><u>Transform Your Typing: Mastering Windows 11'S Language Options</u></a></li>
<li><a href="https://blog-min.techidaily.com/ultimate-wonderfox-pro-securely-transfer-your-dvds-to-any-cellphone-supported-brands-iphone-huawei-samsung-blackberry-htc-nokia/"><u>Ultimate WonderFox Pro: Securely Transfer Your DVDs to Any Cellphone - Supported Brands: IPhone, Huawei, Samsung, BlackBerry, HTC, Nokia</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    