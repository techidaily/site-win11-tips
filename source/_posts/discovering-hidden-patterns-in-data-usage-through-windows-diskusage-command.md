---
title: Discovering Hidden Patterns in Data Usage Through Windows' DiskUsage Command
date: 2024-08-28T01:20:03.555Z
updated: 2024-08-29T01:20:03.555Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Discovering Hidden Patterns in Data Usage Through Windows' DiskUsage Command
excerpt: This Article Describes Discovering Hidden Patterns in Data Usage Through Windows' DiskUsage Command
keywords: Data Usage Trends,Windows Disk Analysis,Usage Pattern Discovery,DiskStatistics Insight,Data Consumption Tracking,Usage Command Analysis,Uncovered Data Patterns
thumbnail: https://thmb.techidaily.com/0fdf2fa9392d7802826e32aaa7c1f7d7a9d236164e77dff001f4eb865ae62af5.jpg
---

## Discovering Hidden Patterns in Data Usage Through Windows' DiskUsage Command

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
## Additional DiskUsage Command Options

 The DiskUsage tool contains several other useful options that you can use to filter the output. You can filter by filename, display reserved space, or the largest directories within the folder.

 For example, to filter by filename add **/n=installer** to the end of the command to display only files that contain the word installer.

 You can see a complete list of the options by typing **DiskUsage /?** and pressing **Enter**.

![A list of DiskUsage options in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-options.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<span id="1793213">
					<video width="1080" height="1620" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:1080px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Analyze Drive Space With DiskUsage

 Many of the available command line tools are extremely useful for maintaining and managing your Windows PC. And as this guide shows, DiskUsage.exe is a powerful alternative to graphical UI tools such as Storage Sense if you want to really dig down into how your drive space is being used.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-information.techidaily.com/new-conquer-online-video-platforms-zooming-into-youtube-and-fb-lives/"><u>[New] Conquer Online Video Platforms  Zooming Into YouTube & FB Lives</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-from-ordinary-to-epic-iphones-best-landscape-tricks-for-2024/"><u>[New] From Ordinary to Epic  IPhone's Best Landscape Tricks for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-insta-vids-dissecting-the-relevance-of-self-image-authenticity-for-2024/"><u>[New] Insta Vids  Dissecting the Relevance of Self-Image Authenticity for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-makeup-inspiration-videos/"><u>[New] Makeup Inspiration Videos</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-navigating-self-viewer-phenomenon-in-facebook-live-conversations/"><u>[New] Navigating Self-Viewer Phenomenon in Facebook Live Conversations</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-navigating-the-virtual-landscape-of-xbox-zoom/"><u>[New] Navigating the Virtual Landscape of Xbox Zoom</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-short-track-olympics-highlights-from-22-for-2024/"><u>[New] Short Track Olympics - Highlights From '22 for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-screenflow-pros-mac-saga-full-evaluation-report-for-2024/"><u>[Updated] ScreenFlow Pro's Mac Saga - Full Evaluation Report for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-the-ultimate-combat-guide-to-top-fps-games-for-2024/"><u>[Updated] The Ultimate Combat Guide to Top FPS Games for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-top-15-no-cost-web-image-editors-review-for-2024/"><u>[Updated] Top 15 No-Cost Web Image Editors Review for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-podcast-versus-visual-media-which-suits-your-content-best/"><u>2024 Approved  Podcast versus Visual Media  Which Suits Your Content Best?</u></a></li>
<li><a href="https://location-social.techidaily.com/4-feasible-ways-to-fake-location-on-facebook-for-your-apple-iphone-14-plus-drfone-by-drfone-virtual-ios/"><u>4 Feasible Ways to Fake Location on Facebook For your Apple iPhone 14 Plus | Dr.fone</u></a></li>
<li><a href="https://location-fake.techidaily.com/all-must-knows-to-use-fake-gps-go-location-spoofer-on-honor-70-lite-5g-drfone-by-drfone-virtual-android/"><u>All Must-Knows to Use Fake GPS GO Location Spoofer On Honor 70 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-out-clutter-celebrate-pure-win11/"><u>Clear Out Clutter: Celebrate Pure Win11</u></a></li>
<li><a href="https://article-tips.techidaily.com/conquer-iphone-photography-by-perfecting-motion-capture-for-2024/"><u>Conquer iPhone Photography by Perfecting Motion Capture for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delay-windows-11-shutdown-dealing-with-live-applications/"><u>Delay Windows 11 Shutdown: Dealing with Live Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/earnings-explored-microsoft-and-its-windows-11-model/"><u>Earnings Explored: Microsoft & Its Windows 11 Model</u></a></li>
<li><a href="https://common-error.techidaily.com/1723205974664-error-651-on-windows-heres-how-to-easily-correct-it/"><u>Error 651 on Windows? Here's How to Easily Correct It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-to-managing-app-packages-using-wingetui-in-windows-11/"><u>Essential Guide to Managing App Packages Using WingetUI in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expediting-the-epic-games-universe-download-process/"><u>Expediting the Epic Games Universe Download Process</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/how-to-correctly-address-pnpdetected-fatal-errors-in-your-windows-11-setup/"><u>How to Correctly Address PNP_Detected Fatal Errors in Your Windows 11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-photo-capture-file-creation-failed-camera-app-error-on-windows-10-and-11/"><u>How to Fix the “Photo Capture File Creation Failed” Camera App Error on Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-google-chrome-aw-snap-error-on-windows/"><u>How to Fix the Google Chrome “Aw, Snap!” Error on Windows</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-poco-m6-5g-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on Poco M6 5G? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-text-messages-from-oppo-find-x6-pro-to-new-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Text Messages from Oppo Find X6 Pro to New Phone | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-ultimate-guide-to-free-pptp-vpn-for-beginners-on-motorola-edge-40-drfone-by-drfone-virtual-android/"><u>In 2024, Ultimate Guide to Free PPTP VPN For Beginners On Motorola Edge 40 | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/iphone-is-disabled-here-is-the-way-to-unlock-disabled-apple-iphone-11-pro-max-by-drfone-ios/"><u>iPhone Is Disabled? Here Is The Way To Unlock Disabled Apple iPhone 11 Pro Max</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/linguistic-expressions-of-affection/"><u>Linguistic Expressions of Affection</u></a></li>
<li><a href="https://extra-support.techidaily.com/lol-library-top-picks-for-outstanding-meme-creators-for-2024/"><u>LOL Library  Top Picks for Outstanding Meme Creators for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/make-windows-11-more-engaging-with-themes/"><u>Make Windows 11 More Engaging with Themes</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ating-industry-titans-a-creators-guide-to-mnc-deals/"><u>Navigating Industry Titans  A Creator's Guide to MNC Deals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-blue-screen-mysteries/"><u>Navigating Through Windows' Blue Screen Mysteries</u></a></li>
<li><a href="https://win11-tips.techidaily.com/online-free-windows-efficient-update-tips/"><u>Online-Free Windows: Efficient Update Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-icon-cache-via-command-line/"><u>Optimizing Icon Cache via Command Line</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-non-detectable-disk-error/"><u>Overcoming Non-Detectable Disk Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-system-call-error-in-windows-os/"><u>Overcoming System Call Error in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11-error-microsoft-store-0x80073cf3/"><u>Overcoming Windows 11 Error: Microsoft Store 0X80073cf3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11s-lost-d3dx939dll-issue/"><u>Overcoming Windows 11'S Lost D3DX9_39.dll Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalize-windows-email-and-scheduling-with-top-pics/"><u>Personalize Window's Email & Scheduling with Top Pics</u></a></li>
<li><a href="https://win-answers.techidaily.com/quick-solutions-overcoming-issues-with-genshin-impact-startup/"><u>Quick Solutions: Overcoming Issues with Genshin Impact Startup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quickening-steam-download-speed-on-your-windows-system/"><u>Quickening Steam Download Speed on Your Windows System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapid-resolution-quick-tips-for-a-stable-wwe-gameplay/"><u>Rapid Resolution: Quick Tips for a Stable WWE Gameplay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-windows-photo-viewer-essential-tips-for-11-users/"><u>Reactivating Windows Photo Viewer: Essential Tips for 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-disabled-windows-account-access/"><u>Restoring Disabled Windows Account Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-your-pc-a-step-by-step-windows-11-reboot-guide/"><u>Reviving Your PC: A Step-by-Step Windows 11 Reboot Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securely-deploy-powertoys-in-win11-environments/"><u>Securely Deploy PowerToys in Win11 Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shifting-onedrive-folder-a-windows-10-guide/"><u>Shifting OneDrive Folder: A Windows 10 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speeding-up-your-pc-adjusting-boot-sequence-timer-in-win11/"><u>Speeding Up Your PC: Adjusting Boot Sequence Timer in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-resolving-steam-login-errors/"><u>Strategies for Resolving Steam Login Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/supercharge-your-mobile-setup-with-one-click-apks-in-windows-11/"><u>Supercharge Your Mobile Setup with One Click APKs in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-microsoft-store-crash-resolve-error-code-x800704cf/"><u>Tackling Microsoft Store Crash: Resolve Error Code X800704CF</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-enigma-of-extraneous-edges-processes/"><u>The Enigma of Extraneous Edges Processes</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/the-ultimate-toolkit-powerdirectors-comprehensive-24-analysis/"><u>The Ultimate Toolkit  PowerDirector's Comprehensive '24 Analysis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocked-accessibility-for-non-functional-applications-on-ms-store/"><u>Unblocked Accessibility for Non-Functional Applications on MS Store</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unlocking-secrets-of-teslas-self-driving-cab-price-insights-launch-date-and-specifications-rumors-revealed/"><u>Unlocking Secrets of Tesla's Self-Driving Cab: Price Insights, Launch Date & Specifications - Rumors Revealed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-hidden-potential-via-shortcut-combinations/"><u>Unveiling Windows' Hidden Potential via Shortcut Combinations</u></a></li>
<li><a href="https://driver-install.techidaily.com/update-legacy-printers-install-mx870-drivers-windows/"><u>Update Legacy Printers: Install MX870 Drivers, Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-bestowed-powers-via-command-line/"><u>Windows 11: Bestowed Powers via Command Line</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211838378-your-sds-silence-uncover-solutions/"><u>Your SD's Silence? Uncover Solutions!</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>