---
title: "Maximizing Your Hard Drive Potential: A Deep Dive Into Using DiskUsage in Windows"
date: 2024-10-29T19:07:59.002Z
updated: 2024-11-01T19:46:04.053Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Maximizing Your Hard Drive Potential: A Deep Dive Into Using DiskUsage in Windows"
excerpt: "This Article Describes Maximizing Your Hard Drive Potential: A Deep Dive Into Using DiskUsage in Windows"
keywords: Hard Drive Optimization,DiskSpace Management,Windows Disk Usage,Storage Capacity,File System Efficiency,Data Utilization Tips,Maxing Out HDD Potential
thumbnail: https://thmb.techidaily.com/24c0edcba484cab644836ae0bb31bb9d7220262ab1b4fd8d660fcbd9d1d07966.jpg
---

## Maximizing Your Hard Drive Potential: A Deep Dive Into Using DiskUsage in Windows

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

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1557746/17382" target="_top" id="1557746">
  <img src="//a.impactradius-go.com/display-ad/17382-1557746" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1557746/17382" style="position:absolute;visibility:hidden;" border="0" />
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
4. Make sure to include the **/h** option so that the output is in a format that's easy to read.

 After identifying what is taking up the most space, you can use any one of these [methods to delete large files](https://www.makeuseof.com/windows-11-delete-select-files/).

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037335/7443" target="_top" id="2037335">
  <img src="//a.impactradius-go.com/display-ad/7443-2037335" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037335/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Additional DiskUsage Command Options

 The DiskUsage tool contains several other useful options that you can use to filter the output. You can filter by filename, display reserved space, or the largest directories within the folder.

 For example, to filter by filename add **/n=installer** to the end of the command to display only files that contain the word installer.

 You can see a complete list of the options by typing **DiskUsage /?** and pressing **Enter**.

![A list of DiskUsage options in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-options.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137226/26400" target="_top" id="2137226">
  <img src="//a.impactradius-go.com/display-ad/26400-2137226" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137226/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2145009/26400" target="_top" id="2145009">
  <img src="//a.impactradius-go.com/display-ad/26400-2145009" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2145009/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Analyze Drive Space With DiskUsage

 Many of the available command line tools are extremely useful for maintaining and managing your Windows PC. And as this guide shows, DiskUsage.exe is a powerful alternative to graphical UI tools such as Storage Sense if you want to really dig down into how your drive space is being used.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-techniques.techidaily.com/updated-exploring-watermark-free-stock-image-sources/"><u>[Updated] Exploring Watermark-Free Stock Image Sources</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-in-2024-a-symphony-for-photos-on-digital-platforms/"><u>[Updated] In 2024, A Symphony for Photos on Digital Platforms</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-savory-sensations-top-youtube-food-influencers/"><u>[Updated] Savory Sensations Top YouTube Food Influencers</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-spotlight-secrets-perfecting-vlogger-lights/"><u>2024 Approved Spotlight Secrets Perfecting Vlogger Lights</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-top-video-editors-for-youtube-on-the-houseno-cost-included/"><u>2024 Approved Top Video Editors for YouTube on the House—No Cost Included</u></a></li>
<li><a href="https://hardware-help.techidaily.com/brother-hl-l2380dw-official-windows-printing-solutions-and-download-links/"><u>Brother HL-L2380DW: Official Windows Printing Solutions & Download Links</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-rid-of-highlighted-icon-in-windows-11/"><u>Get Rid of Highlighted Icon in Windows 11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/guia-completa-para-aumentar-la-claridad-y-resolucion-de-tus-videos-de-hd4k-con-windows-o-mac/"><u>Guía Completa Para Aumentar La Claridad Y Resolución De Tus Videos De HD/4K Con Windows O Mac</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-what-is-geo-blocking-and-how-to-bypass-it-on-infinix-smart-8-drfone-by-drfone-virtual-android/"><u>In 2024, What is Geo-Blocking and How to Bypass it On Infinix Smart 8? | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-academic-writing-leveraging-chatgpt-for-effective-research-and-essay-creation/"><u>Mastering Academic Writing: Leveraging ChatGPT for Effective Research & Essay Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-devices-that-react-to-pc-slumber/"><u>Mastering Devices That React to PC Slumber</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-mute-shift-key-trouble/"><u>Mastery Over Mute Shift Key Trouble.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-new-steer-clear-of-these-8-windows-11-faux-pas/"><u>Navigating the New: Steer Clear of These 8 Windows 11 Faux Pas</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-opening-terminal-in-quake/"><u>Quick Guide: Opening Terminal in Quake</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-pasting-tips-for-pre-defined-text-in-win-1011/"><u>Quick Pasting Tips for Pre-Defined Text in Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reimagining-sign-ins-in-windows-11-shifting-from-pin-to-more-secure-authentication/"><u>Reimagining Sign-Ins in Windows 11: Shifting From PIN to More Secure Authentication</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-a-stuck-or-unresponsive-media-player-on-win11/"><u>Troubleshooting a Stuck or Unresponsive Media Player on Win11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/unraveling-monetization-strategies-in-the-realm-of-video-shorts/"><u>Unraveling Monetization Strategies in the Realm of Video Shorts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-the-definitive-guide-to-dns-cache-clearance/"><u>Windows 11: The Definitive Guide to DNS Cache Clearance</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    