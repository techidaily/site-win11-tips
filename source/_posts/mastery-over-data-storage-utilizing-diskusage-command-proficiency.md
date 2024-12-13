---
title: "Mastery Over Data Storage: Utilizing DiskUsage Command Proficiency"
date: 2024-12-09T22:40:43.714Z
updated: 2024-12-13T00:10:09.227Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastery Over Data Storage: Utilizing DiskUsage Command Proficiency"
excerpt: "This Article Describes Mastery Over Data Storage: Utilizing DiskUsage Command Proficiency"
keywords: Data Storage Mastery,Disk Usage Control,Storage Optimization,Managing DiskSpace,Command Line Expertise,Efficient Data Management,Maximizing Space Utility
thumbnail: https://thmb.techidaily.com/1d642682ec5cb6a6ea7cd33f84c3c6bed241d468dfb7fb68a3c7508632db1da6.jpg
---

## Mastery Over Data Storage: Utilizing DiskUsage Command Proficiency

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uzb-0C0xUYA?si=F4MPhdVqyVgx7_8X" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. In our example, this looks like **DiskUsage C:\\Users\\UserName\\Pictures /h**.  
![Disk usage date displayed in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-data.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pejPLJBLmXw?si=WD97jA3doqbMCkCX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can use DiskUsage to analyze any folder in the same way. You can even check internal and external drives, including the C: drive. Bear in mind that analyzing a drive such as C: will spew out a huge list of files and folders in DiskUsage.

 If using DiskUsage.exe seems too complicated, you can easily view how disk space is being used with [Storage Sense](https://www.makeuseof.com/windows-11-storage-sense-guide/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SDUPd69Qfls?si=uIGZG-riskwmVZYg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6KXVWj6Ar1M?si=Cd_jktmoN3e9OzH3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Make sure to include the **/h** option so that the output is in a format that's easy to read.

 After identifying what is taking up the most space, you can use any one of these [methods to delete large files](https://www.makeuseof.com/windows-11-delete-select-files/).

## Additional DiskUsage Command Options

 The DiskUsage tool contains several other useful options that you can use to filter the output. You can filter by filename, display reserved space, or the largest directories within the folder.

 For example, to filter by filename add **/n=installer** to the end of the command to display only files that contain the word installer.

 You can see a complete list of the options by typing **DiskUsage /?** and pressing **Enter**.

![A list of DiskUsage options in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-options.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Analyze Drive Space With DiskUsage

 Many of the available command line tools are extremely useful for maintaining and managing your Windows PC. And as this guide shows, DiskUsage.exe is a powerful alternative to graphical UI tools such as Storage Sense if you want to really dig down into how your drive space is being used.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-professional-fb-cover-setups-to-skyrocket-engagement/"><u>[New] 2024 Approved Professional FB Cover Setups to Skyrocket Engagement</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-best-practices-for-high-quality-remote-podcasts/"><u>[New] Best Practices for High-Quality Remote Podcasts</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-ever-fading-memories-revived-youtubes-lost-content-hunt-for-2024/"><u>[New] Ever-Fading Memories Revived YouTube's Lost Content Hunt for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-harmonizing-posts-with-instagram-music/"><u>[New] In 2024, Harmonizing Posts with Instagram Music</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-slice-and-tag-the-art-of-chaptering-in-vimeo/"><u>[New] Slice and Tag The Art of Chaptering in Vimeo</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-the-step-by-step-process-for-screening-web-tv-episodes/"><u>[Updated] In 2024, The Step-by-Step Process for Screening Web TV Episodes</u></a></li>
<li><a href="https://blog-min.techidaily.com/4-ways-to-transfer-music-from-oppo-a56s-5g-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>4 Ways to Transfer Music from Oppo A56s 5G to iPhone | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensible-guide-to-handling-unhandled-exception-in-windows/"><u>Comprehensible Guide to Handling Unhandled Exception in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-crashing-windows-registry-with-easy-fixes/"><u>Conquering Crashing Windows Registry with Easy Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-a-permanent-delete-bin-for-windows-users/"><u>Customizing a Permanent Delete Bin for Windows Users</u></a></li>
<li><a href="https://tech-haven.techidaily.com/harnessing-the-power-of-chatgpt-across-different-languages/"><u>Harnessing the Power of ChatGPT Across Different Languages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-malfunction-fixing-windows-app-glitches/"><u>Mastery Over Malfunction: Fixing Windows App Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-windows-11-disk-creative-strategies-for-cleanup-max-156-chars/"><u>Maximizing Windows 11 Disk: Creative Strategies for Cleanup (Max 156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/organize-windows-wonders-alt-tab-magic-with-win1110/"><u>Organize Windows Wonders: Alt-Tab Magic with Win11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-component-services-on-windows-11/"><u>Step-by-Step Guide to Component Services on Windows 11</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/why-dji-mavic-2-pro-remains-the-ultimate-tool-for-aerial-photography-experts/"><u>Why DJI Mavic 2 Pro Remains the Ultimate Tool for Aerial Photography Experts</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    