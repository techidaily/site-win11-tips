---
title: Expert Guide to Utilizing DiskUsage on Windows Systems
date: 2024-08-16T01:36:22.131Z
updated: 2024-08-17T01:36:22.131Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Expert Guide to Utilizing DiskUsage on Windows Systems
excerpt: This Article Describes Expert Guide to Utilizing DiskUsage on Windows Systems
keywords: DiskSpace Usage Guide,Windows Disk Management,Disk Usage Tips,Tracking Disk Space,System Storage Insight,DiskStats Analysis,Optimizing DiskUsage
thumbnail: https://thmb.techidaily.com/0be1e99c17baad20df818e64c74b29c212a06e76be2a092d41b1fc888150e8a5.jpeg
---

## Expert Guide to Utilizing DiskUsage on Windows Systems

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

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
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
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. You can replace the number with any other you want to use. For example, to see the top 5 files taking up space, use **/u=5**.
4. Make sure to include the **/h** option so that the output is in a format that's easy to read.

 After identifying what is taking up the most space, you can use any one of these [methods to delete large files](https://www.makeuseof.com/windows-11-delete-select-files/).

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Additional DiskUsage Command Options

 The DiskUsage tool contains several other useful options that you can use to filter the output. You can filter by filename, display reserved space, or the largest directories within the folder.

 For example, to filter by filename add **/n=installer** to the end of the command to display only files that contain the word installer.

 You can see a complete list of the options by typing **DiskUsage /?** and pressing **Enter**.

![A list of DiskUsage options in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-options.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## Analyze Drive Space With DiskUsage

 Many of the available command line tools are extremely useful for maintaining and managing your Windows PC. And as this guide shows, DiskUsage.exe is a powerful alternative to graphical UI tools such as Storage Sense if you want to really dig down into how your drive space is being used.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-efficient-classroom-documentation-choose-the-best-screen-recorder/"><u>[New] 2024 Approved  Efficient Classroom Documentation  Choose the Best Screen Recorder</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-action-packed-escapades-the-next-big-things-post-gta-v/"><u>[New] In 2024, Action-Packed Escapades - The Next Big Things Post-GTA V</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-efficient-strategies-to-log-facetime-discussions/"><u>[Updated] 2024 Approved  Efficient Strategies to Log FaceTime Discussions</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-lost-footage-immediate-removal-impacts/"><u>[Updated] 2024 Approved  Lost Footage  Immediate Removal Impacts</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-harnessing-googles-capability-for-exact-speech-recognition/"><u>2024 Approved  Harnessing Google’s Capability for Exact Speech Recognition</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-visualizing-stories-turning-your-favorite-vimeo-into-dynamic-gifs/"><u>2024 Approved  Visualizing Stories  Turning Your Favorite Vimeo Into Dynamic GIFs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-disk-space-safely-preserving-data-on-your-windows-11-local-drive-max-156-chars/"><u>Boost Your Disk Space Safely: Preserving Data on Your Windows 11 Local Drive (Max 156 Chars)</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/can-you-unlock-apple-iphone-13-pro-max-after-forgetting-the-passcode-by-drfone-ios/"><u>Can You Unlock Apple iPhone 13 Pro Max After Forgetting the Passcode?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-confusion-a-guide-to-reinstalling-store-software/"><u>Clearing Up Confusion: A Guide to Reinstalling Store Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-files-and-folders-win-1011-edition/"><u>Conquering Files and Folders, Win 10/11 Edition</u></a></li>
<li><a href="https://network-issues.techidaily.com/core-i9-pc-lacks-graphics-acceleration/"><u>Core I9 PC Lacks Graphics Acceleration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/double-tap-for-apks-a-user-friendly-guide-in-win-11/"><u>Double-Tap for APKs: A User-Friendly Guide in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-windows-crash-focus-on-0x800f0831/"><u>Eliminate Windows Crash: Focus on 0X800f0831</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-no-more-files-errors-in-win-11/"><u>Eliminating 'No More Files' Errors in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-user-experience-7-steps-to-missing-windows-add-ons/"><u>Enhancing User Experience: 7 Steps to Missing Windows Add-Ons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-interface-adding-portable-apps-menus/"><u>Enhancing Windows Interface: Adding Portable Apps Menus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-file-failsafe-six-steps-for-correcting-winrar-sums/"><u>Fixing File Failsafe: Six Steps for Correcting WinRAR Sums</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-users-through-admin-level-execution-woes/"><u>Guiding Users Through Admin-Level Execution Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harnessing-windows-oversight-on-apps-browsers/"><u>Harnessing Windows Oversight on Apps, Browsers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-bring-back-your-bluetooth-in-windows-11-top-9-methods/"><u>How to Bring Back Your Bluetooth in Windows 11: Top 9 Methods</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-frp-on-nokia-c02-by-drfone-android/"><u>How to Bypass FRP on Nokia C02?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-permit-browser-network-access-via-windows-security-settings/"><u>How to Permit Browser Network Access via Windows Security Settings</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-play-mov-files-on-samsung-galaxy-s23-ultra-by-aiseesoft-video-converter-play-mov-on-android/"><u>How to play MOV files on Samsung Galaxy S23 Ultra ?</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-remove-a-previously-synced-google-account-from-your-lava-blaze-pro-5g-by-drfone-android/"><u>How to Remove a Previously Synced Google Account from Your Lava Blaze Pro 5G</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-spy-on-text-messages-from-computer-and-honor-100-pro-drfone-by-drfone-virtual-android/"><u>How to Spy on Text Messages from Computer & Honor 100 Pro | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-lava-yuva-3-by-phone-number-drfone-by-drfone-virtual-android/"><u>How to Track Lava Yuva 3 by Phone Number | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-card-on-oppo-reno-8t-5g-online-without-jailbreak-by-drfone-android/"><u>How to Unlock SIM Card on Oppo Reno 8T 5G online without jailbreak</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improve-system-stability-automatic-updates-plus-amd-video-replacement/"><u>Improve System Stability: Automatic Updates + AMD Video Replacement</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-infinix-note-30-drfone-by-drfone-virtual-android/"><u>In 2024, 15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Infinix Note 30 | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-breaking-ice-the-peak-of-chinas-sports-showcase-2022/"><u>In 2024, Breaking Ice  The Peak of China's Sports Showcase, 2022</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-music-from-vivo-y100t-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Music from Vivo Y100t to iPod | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-how-to-use-star-feature-to-your-advantage/"><u>In 2024, How to Use Star Feature to Your Advantage</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-oppo-a38-drfone-by-drfone-virtual-android/"><u>In 2024, Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Oppo A38 | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-preparation-to-beat-giovani-in-pokemon-go-for-honor-magic5-ultimate-drfone-by-drfone-virtual-android/"><u>In 2024, Preparation to Beat Giovani in Pokemon Go For Honor Magic5 Ultimate | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-microsoft-works-with-windows-11-easy/"><u>Integrating Microsoft Works with Windows 11 Easy</u></a></li>
<li><a href="https://win-able.techidaily.com/1723001364236-launch-problems-in-valorant-heres-how-you-can-resolve-them-on-your-pc-latest-tips/"><u>Launch Problems in Valorant? Here's How You Can Resolve Them on Your PC - Latest Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leap-to-peak-ssd-performance-win-and-fresh-methods/"><u>Leap to Peak SSD Performance: Win and Fresh Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-safety-sticky-notes-edition/"><u>Mastering File Safety: Sticky Notes Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-screen-space-removing-windows-overscan-effects/"><u>Maximizing Screen Space: Removing Windows Overscan Effects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/novices-guide-to-easy-use-of-windows-accessibility/"><u>Novices' Guide to Easy Use of Windows Accessibility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-cure-all-solutions-for-windows-camera-glitches/"><u>Quick Cure-All Solutions for Windows Camera Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-methods-creating-new-dossiers-in-win11/"><u>Quick Methods: Creating New Dossiers in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamlessly-change-the-dynamic-background-in-windows-os/"><u>Seamlessly Change the Dynamic Background in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-windows-exploration-without-the-use-of-ls/"><u>Streamlined Windows Exploration Without the Use of LS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-language-settings-add-and-switch-layouts-in-win-11-os/"><u>Streamlining Language Settings: Add & Switch Layouts in Win 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/successfully-overcome-windows-error-0x80070003-a-step-by-step-guide/"><u>Successfully Overcome Windows Error 0X80070003 - A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-advantages-of-using-dxvk-on-your-windows-system/"><u>The Advantages of Using DXVK on Your Windows System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-best-free-must-have-tools-for-windows-11/"><u>The Best Free Must-Have Tools for Windows 11</u></a></li>
<li><a href="https://fox-that.techidaily.com/the-complete-cheat-sheet-mend-glitchy-audio-on-airpods-using-10-steps/"><u>The Complete Cheat Sheet: Mend Glitchy Audio on AirPods Using 10 Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-insiders-guide-to-customizing-the-desktop-menu/"><u>The Insider's Guide to Customizing the Desktop Menu</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-motorola-moto-g24-drfone-by-drfone-virtual-android/"><u>The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Motorola Moto G24 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-steam-authentication-lags-in-rustwindows/"><u>Troubleshooting Steam Authentication Lags in Rust/Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turn-your-notes-into-masterpieces-with-obsidian-art/"><u>Turn Your Notes Into Masterpieces with Obsidian Art</u></a></li>
<li><a href="https://technical-tips.techidaily.com/understanding-the-404-not-found-issue-explanation-and-solutions/"><u>Understanding the 404 Not Found Issue: Explanation & Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11-potential-steps-for-successful-optional-components-integration/"><u>Unlocking Windows 11 Potential: Steps for Successful Optional Components Integration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-and-o365-sync-issues-a-quick-guide-to-fixing-errors/"><u>Win 11 and O365 Sync Issues: A Quick Guide to Fixing Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-evolves-spotlight-on-new-updates-capabilities/"><u>Windows 11 Evolves: Spotlight on New Updates' Capabilities</u></a></li>
</ul></div>
