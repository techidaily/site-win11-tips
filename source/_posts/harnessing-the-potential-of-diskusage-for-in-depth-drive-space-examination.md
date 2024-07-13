---
title: Harnessing the Potential of DiskUsage for In-Depth Drive Space Examination
date: 2024-07-12T17:19:17.339Z
updated: 2024-07-13T17:19:17.339Z
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/essential-reminders-before-overhauling-your-windows/"><u>Essential Reminders Before Overhauling Your Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-your-computers-storage-here-are-the-best-free-options/"><u>Amplify Your Computer's Storage - Here Are the Best Free Options</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-clearing-up-tiktok-problems-on-android-and-iphone-quickly/"><u>[Updated] Clearing up TikTok Problems on Android & iPhone Quickly</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/unlocking-potential-in-5-second-videos/"><u>Unlocking Potential in 5-Second Videos</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-poco-m6-pro-5g-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive Poco M6 Pro 5G Screen | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-the-code-effective-techniques-to-neutralize-wacatacbml/"><u>Deciphering the Code: Effective Techniques to Neutralize Wacatac.B!ml</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-windows-commands-learn-the-top-20-cmd-tricks/"><u>Essential Windows Commands: Learn the Top 20 CMD Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diving-deep-into-identity-unveiling-sids-in-windows-11/"><u>Diving Deep Into Identity: Unveiling SIDs in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-the-digital-snare-spotting-invisible-threats/"><u>Avoid the Digital Snare: Spotting Invisible Threats</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-tackling-the-challenge-of-locating-fbs-most-watched-videos-2e23-for-2024/"><u>[New] Tackling the Challenge of Locating Fb's Most-Watched Videos (2E23) for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-unveiling-the-top-8-instagram-ae-design-choices/"><u>[New] In 2024, Unveiling the Top 8 Instagram AE Design Choices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-windows-terminals-quake-setting/"><u>Enabling Windows Terminal's Quake Setting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-insufficient-access-block-during-uninstalls/"><u>Bypassing Windows' Insufficient Access Block During Uninstalls</u></a></li>
<li><a href="https://howto.techidaily.com/super-easy-ways-to-deal-with-xiaomi-redmi-a2-unresponsive-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Super Easy Ways To Deal with Xiaomi Redmi A2 Unresponsive Screen | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/chrome-compatibility-with-windows-11-explained/"><u>Chrome Compatibility with Windows 11 Explained</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-can-i-get-more-stardust-in-pokemon-go-on-samsung-galaxy-s23plus-drfone-by-drfone-virtual-android/"><u>In 2024, How can I get more stardust in pokemon go On Samsung Galaxy S23+? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-eradicate-system-call-issues-on-modern-windows/"><u>How to Eradicate System Call Issues on Modern Windows</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-enhancing-clarity-in-low-quality-facebook-streams/"><u>[New] 2024 Approved  Enhancing Clarity in Low-Quality Facebook Streams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-performance-new-tech-in-microsoft-teams/"><u>Enhancing Performance: New Tech in Microsoft Teams</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-in-2024-pivoting-careers-from-novice-to-industry-veteran/"><u>[New] In 2024, Pivoting Careers  From Novice to Industry Veteran</u></a></li>
<li><a href="https://extra-skills.techidaily.com/prime-16-video-apps-no-cost-on-pcs-and-macs-for-2024/"><u>Prime 16 Video Apps, No Cost on PCs & Macs for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-file-locks-turn-off-read-only-windows-mode/"><u>Altering File Locks: Turn Off Read-Only Windows Mode</u></a></li>
<li><a href="https://article-posts.techidaily.com/in-2024-bring-the-beat-home-add-songs-to-your-inshot-app/"><u>In 2024, Bring the Beat Home  Add Songs to Your InShot App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-the-windows-menu-with-superior-powers/"><u>Enhancing the Windows Menu with Superior Powers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/curing-wont-start-spotify-on-windows-1011-platforms/"><u>Curing Won't Start Spotify on Windows 10/11 Platforms</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-streamlinedprocess-for-youcamwebrecord/"><u>[New] 2024 Approved  StreamlinedProcess for YouCamWebRecord</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-2024-approved-stepwise-guide-to-optimizing-youtube-tagging-techniques/"><u>[Updated] 2024 Approved  Stepwise Guide to Optimizing YouTube Tagging Techniques</u></a></li>
<li><a href="https://extra-resources.techidaily.com/broadcast-like-a-ghost-anonymous-instagram-strategies-for-2024/"><u>Broadcast Like a Ghost  Anonymous Instagram Strategies for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-skyrocket-on-instagram-unveiling-your-path-with-top-9-secrets/"><u>2024 Approved  Skyrocket on Instagram  Unveiling Your Path with Top 9 Secrets</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-essentials-of-youtube-gaming-livestreaming/"><u>2024 Approved  The Essentials of YouTube Gaming Livestreaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-saved-audio-configurations-winvolume-hacks/"><u>Bring Back Saved Audio Configurations: WinVolume Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciding-on-a-nearby-share-solution-tech-giants-go-head-to-head/"><u>Deciding on a Nearby Share Solution: Tech Giants Go Head-to-Head</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-secure-your-windows-mixer-preferences-settings/"><u>How To Secure Your Windows Mixer Preferences Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convenient-ways-downloading-setting-up-and-running-msix-extensions-on-windows/"><u>Convenient Ways: Downloading, Setting Up & Running MSIX Extensions on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-drive-definitions-c-vs-d-in-os/"><u>Dissecting Drive Definitions: C: Vs D: In OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-differences-chkdsk-sfc-and-windows-fixes/"><u>Exploring Differences: CHKDSK, SFC, and Windows' Fixes</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/top-5-infinix-smart-8-hd-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Infinix Smart 8 HD Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-top-5-tools-for-fb-video-retrieval-made-simple-for-2024/"><u>[New] Top 5 Tools for FB Video Retrieval Made Simple for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-installing-programs-despite-windows-admin-blocks/"><u>Guidelines for Installing Programs Despite Windows Admin Blocks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cross-os-synergy-creating-a-linux-vm-inside-windows-using-hyper-v/"><u>Cross-OS Synergy: Creating a Linux VM Inside Windows Using Hyper-V</u></a></li>
<li><a href="https://extra-information.techidaily.com/best-platforms-maximizing-your-youtube-reach/"><u>Best Platforms  Maximizing Your YouTube Reach</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/secrets-unlocked-winning-with-facebook-ads-for-2024/"><u>Secrets Unlocked  Winning with Facebook Ads for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/choosing-amongst-windows-n-versions-key-considerations/"><u>Choosing Amongst Windows N Versions: Key Considerations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortlessly-linking-devices-a-nearby-share-walkthrough/"><u>Effortlessly Linking Devices: A Nearby Share Walkthrough</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-honor-magic-5-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On Honor Magic 5? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cryptographic-shielding-data-safety-in-networked-drives/"><u>Cryptographic Shielding: Data Safety in Networked Drives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-language-shifts-hotkey-techniques-for-multilingual-translation-in-windows-11/"><u>Master Language Shifts: Hotkey Techniques for Multilingual Translation in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-strategies-for-winning-with-the-windows-11-bar/"><u>Essential Strategies for Winning with the Windows 11 Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combatting-microsoft-teams-crashes-in-win11-and-win10-pcs/"><u>Combatting Microsoft Teams Crashes in Win11 & Win10 PCs</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-excellent-7-dslrs-elevating-live-stream-cinematic-style/"><u>[Updated] Excellent 7 DSLRs Elevating Live-Stream Cinematic Style</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-craft-a-signature-sound-how-to-modify-voices-for-instagram/"><u>2024 Approved  Craft a Signature Sound  How to Modify Voices for Instagram</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-best-in-class-ultra-fast-lapses/"><u>2024 Approved  Best-in-Class Ultra Fast Lapses</u></a></li>
</ul></div>
