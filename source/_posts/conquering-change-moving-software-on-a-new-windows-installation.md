---
title: "Conquering Change: Moving Software on a New Windows Installation"
date: 2024-09-01T05:18:07.096Z
updated: 2024-09-02T05:18:07.096Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Conquering Change: Moving Software on a New Windows Installation"
excerpt: "This Article Describes Conquering Change: Moving Software on a New Windows Installation"
keywords: WinChangeSoftwareTips,NewWinInstallUpdate,SoftwareShiftWindows,QuickWinUpdateSteps,EfficientNewOSSetup,SoftwareTransitionWin,UpdateOnNewWinOS
thumbnail: https://thmb.techidaily.com/13632811731c559bc127701456401507af159186a9de22e1aa59a5e7f9127b24.jpg
---

## Conquering Change: Moving Software on a New Windows Installation

 Setting up Windows 11 on your PC, or another PC is a laborious task. After installing the operating system and the OEM drivers, there is still a lot of work left. You need to reconfigure your system settings, re-download, and install all the Microsoft Store apps. Along with that, you need to individually download and install each third-party software, which makes it more challenging.

 But what if you could eliminate the hours spent in finding and installing every single app, and configuring every setting? We will discuss two methods to effortlessly migrate most of your old apps to your new PC.

## 1\. Using Microsoft Account

 If you used a Microsoft account on your old PC, Windows 11 offers multiple options to back up your App list, Preferences, and use OneDrive for personal files. To do that, you must enable [OneDrive](https://www.makeuseof.com/what-is-onedrive/)and back up all your personal files and folders to it. It will only take care of the files part but the apps and preferences are still left. But you must also enable the backup of these two things on your old PC before [reinstalling Windows 11](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/) or migrating to a new PC.

 Repeat the following steps to enable apps and settings backup:

1. Press **Win + I** to launch the Settings app. Navigate to **Accounts > Windows backup** section.
2. Go to the **Remember my apps** option and click on the toggle next to it to enable the settings.
3. Next, click on the toggle next to **Remember my preferences** option to back up your settings as well.  
![Backup Apps and Preferences to Microsoft Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/backup-apps-and-preferences-to-microsoft-account.jpg)
4. You will notice that the top section of the Windows backup page will mark each of these features as “**backed up**”.

 After you reinstall Windows 11, the OOBE page will ask you to [sign in with a Microsoft account](https://www.makeuseof.com/windows-switch-local-account-to-microsoft-account/). Enter your credentials, and you will see a “Welcome back, User!” message with an option to restore all apps, settings, and files present on your previous machine. Click on the **Next** button and proceed setup up your new PC

![Install Old Apps Using Microsoft Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-old-apps-using-microsoft-account.jpg)

 As soon as you boot to the desktop, you will see a popup that Windows is trying to restore the most used apps from before. It will ask you to open Microsoft Store to restore additional apps from your old PC. Click on the **Restore my apps** button.

![Install Old Apps Using Microsoft Account 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-old-apps-using-microsoft-account-2.jpg)

 Microsoft Store will display all the remaining apps available for restoration. Click on the **Restore All** button if you want to bring back every app. Wait for the apps to install and then close Microsoft Store.

![Install Old Apps Using Microsoft Account 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-old-apps-using-microsoft-account-3.jpg)

## 2\. Using a Winget JSON File

 The first method of using Microsoft Account has its limitations. It only includes Windows apps and settings but leaves many other third-party apps that you installed from the Winget repository or from the web. So you can use Winget to export the app list into a JSON file and then import it to your new Windows 11 PC. You must execute this method after Windows 11 brings back all the settings and Microsoft apps, and you boot to the desktop.

 Repeat the following steps to import a Winget JSON file:

1. Download or copy the Winget export file on your system.
2. Press **Win + R** to open the **Run dialog box**. Type **cmd** and press **Ctrl + Shift + Enter** to [open Command Prompt with administrator privileges](https://www.makeuseof.com/how-to-always-open-command-prompt-as-administrator-windows/).
3. Now, use the **winget import -i** command to import the JSON file. Type the following command and press the **Enter** key:  
`winget import -i C:\apps.json --accept-source-agreements --accept-package-agreements`
4. Replace the folder location and name with the storage location and name of the winget export file on your system.  
![Import Apps Using Winget in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/import-apps-using-winget-in-windows-11.jpg)
5. Patiently wait while winget downloads and installs all the packages in the JSON file one by one. Then, close the Command Prompt window.

<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What About Any Left Out Apps?

 Even after using both methods, some apps will still be left out. It is because Microsoft Account sign-in only brings back Windows settings and Microsoft Store apps. The winget export file can restore only the apps listed in its official repository.

 As such, you still need to download the programs that aren’t included in both of these methods. But it will be a very short list compared to the effort you would have to put in if you just performed a normal installation.

<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Save Time When Setting Up Windows 11

 Make sure to enable files, apps, and preferences backup on your PC and create a winget export file beforehand. After you have both these backups in place, you can begin reinstalling Windows 11 on a different PC or reinstalling on the same PC.

 But what if you could eliminate the hours spent in finding and installing every single app, and configuring every setting? We will discuss two methods to effortlessly migrate most of your old apps to your new PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-screensavers-supreme-mastering-the-art-of-twitvid-archiving/"><u>[New] 2024 Approved  ScreenSavers Supreme  Mastering the Art of TwitVid Archiving</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-chic-crests-curating-the-best-websites-for-aesthetic-laptop-backgrounds/"><u>[New] Chic Crests  Curating the Best Websites for Aesthetic Laptop Backgrounds</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-top-10-online-yogis-for-peak-physique-and-harmony/"><u>[New] In 2024, Top 10 Online Yogis for Peak Physique and Harmony</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/n-2024-top-10-youtube-to-webm-converter-apps-reviewed-and-ranked/"><u>[New] In 2024, Top 10 YouTube to WebM Converter Apps Reviewed & Ranked</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-mastering-the-power-of-hashtags-on-instagram-now/"><u>[New] Mastering the Power of #Hashtags on Instagram Now</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-undead-uprising-your-guide-to-engrossing-zombie-playtime/"><u>[Updated] In 2024, Undead Uprising  Your Guide to Engrossing Zombie Playtime</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-instagram-tv-shutdown-procedure/"><u>[Updated] Instagram TV Shutdown Procedure</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-secrets-revealed-how-to-boost-facebook-rankings-in-under-a-minute-for-2024/"><u>[Updated] Secrets Revealed  How to Boost Facebook Rankings in Under a Minute for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1-mastering-accessibility-a-step-by-step-guide-to-adding-alt-text-in-ms-excel/"><u>1. Mastering Accessibility: A Step-by-Step Guide to Adding Alt Text in MS Excel</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-mastering-the-art-of-using-telegram-online/"><u>2024 Approved  Mastering the Art of Using Telegram Online</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-tecno-pop-8-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Tecno Pop 8 Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://location-fake.techidaily.com/6-ways-to-change-spotify-location-on-your-htc-u23-pro-drfone-by-drfone-virtual-android/"><u>6 Ways to Change Spotify Location On Your HTC U23 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-essential-benefits-of-integrating-microsoft-365-into-daily-operations/"><u>7 Essential Benefits of Integrating Microsoft 365 Into Daily Operations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-showing-and-hiding-excel-sheet-columns-for-better-organization/"><u>A Step-by-Step Guide to Showing and Hiding Excel Sheet Columns for Better Organization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beware-deceptions-uncover-the-truth-about-scam-ridden-mac-app-store/"><u>Beware Deceptions: Uncover the Truth About Scam-Ridden Mac App Store</u></a></li>
<li><a href="https://screen-capture.techidaily.com/breaking-ground-video-capture-breakdown-for-2024/"><u>Breaking Ground  Video Capture Breakdown for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-microsoft-office-applications-creating-and-managing-spreadsheet-features-inside-microsoft-word/"><u>Bridging Microsoft Office Applications: Creating and Managing Spreadsheet Features Inside Microsoft Word</u></a></li>
<li><a href="https://win11-tips.techidaily.com/building-an-easy-monthly-budget-using-microsoft-excel-tips-and-tricks-for-beginners/"><u>Building an Easy Monthly Budget Using Microsoft Excel – Tips and Tricks for Beginners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bulk-clean-up-eliminating-characters-from-an-excel-document-simultaneeously/"><u>Bulk Clean-Up: Eliminating # Characters From an Excel Document Simultaneeously</u></a></li>
<li><a href="https://facebook.techidaily.com/care-for-confidentiality-sidestep-these-3-apps/"><u>Care for Confidentiality: Sidestep These 3 Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/coloring-beneath-the-surface-a-guide-to-shading-alternating-cells-in-ms-excel/"><u>Coloring Beneath the Surface: A Guide to Shading Alternating Cells in MS Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comparing-microsoft-office-key-differences-on-windows-vs-macos-platforms/"><u>Comparing Microsoft Office: Key Differences on Windows vs macOS Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-tutorial-renaming-and-disposing-of-kindle-gadgets-via-amazons-online-portal/"><u>Comprehensive Tutorial: Renaming & Disposing of Kindle Gadgets via Amazon's Online Portal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-microsoft-office-spell-checker-to-overlook-web-addresses-effortlessly/"><u>Configuring Microsoft Office Spell Checker to Overlook Web Addresses Effortlessly</u></a></li>
<li><a href="https://win-able.techidaily.com/decode-the-error-expert-advice-for-playing-far-cry-6-on-your-pc/"><u>Decode the Error: Expert Advice for Playing Far Cry 6 on Your PC</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/decoding-the-artificial-intelligence-driven-paperclip-enigma/"><u>Decoding the Artificial Intelligence-Driven Paperclip Enigma</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-the-modernized-interface-of-microsoft-excels-revamped-formula-bar/"><u>Discover the Modernized Interface of Microsoft Excel's Revamped Formula Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-the-unique-capabilities-of-siri-11-innovative-uses-for-your-mac/"><u>Discover the Unique Capabilities of Siri: 11 Innovative Uses for Your Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-guide-unlocking-cell-type-ahead-with-slidebar-in-microsoft-excel/"><u>Easy Guide: Unlocking Cell Type-Ahead with Slidebar in Microsoft Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-guide-turning-off-microsoft-offices-security-warnings/"><u>Effective Guide: Turning Off Microsoft Office's Security Warnings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-methods-for-managing-visibility-of-sheet-tab-buttons-in-microsoft-excel/"><u>Effective Methods for Managing Visibility of Sheet Tab Buttons in Microsoft Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-techniques-for-applying-the-year-functionality-in-ms-excel-tutorials/"><u>Effective Techniques for Applying the Year Functionality in MS Excel Tutorials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-techniques-for-identifying-variances-between-two-excel-datasets/"><u>Effective Techniques for Identifying Variances Between Two Excel Datasets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-determining-your-datasets-middle-value-the-median-formula-in-excel-unveiled/"><u>Efficiently Determining Your Dataset's Middle Value: The Median Formula in Excel Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-lock-and-unlock-specific-rows-in-microsoft-excel-with-these-simple-tips/"><u>Efficiently Lock and Unlock Specific Rows in Microsoft Excel with These Simple Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-data-entry-mastering-flash-fill-and-auto-fill-in-microsoft-excel/"><u>Effortless Data Entry: Mastering Flash Fill & Auto Fill in Microsoft Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-techniques-to-craft-stunning-bubble-charts-using-excel/"><u>Effortless Techniques to Craft Stunning Bubble Charts Using Excel</u></a></li>
<li><a href="https://extra-tips.techidaily.com/elevate-photo-quality-discover-the-best-10-web-enhancement-software/"><u>Elevate Photo Quality  Discover the Best 10 Web Enhancement Software</u></a></li>
<li><a href="https://some-techniques.techidaily.com/from-sound-to-web-crafting-a-standout-podcast-rss-feed-for-2024/"><u>From Sound to Web  Crafting a Standout Podcast RSS Feed for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-exit-android-factory-mode-on-itel-a60-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Exit Android Factory Mode On Itel A60? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-fix-auto-lock-greyed-out-on-apple-iphone-7-drfone-by-drfone-ios/"><u>How To Fix Auto Lock Greyed Out on Apple iPhone 7 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-xiaomi-redmi-k70-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Xiaomi Redmi K70 Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-can-i-catch-the-regional-pokemon-without-traveling-on-poco-c65-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Catch the Regional Pokémon without Traveling On Poco C65 | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-realme-c33-2023-drfone-by-drfone-virtual-android/"><u>In 2024, How to get the dragon scale and evolution-enabled pokemon On Realme C33 2023? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-luminous-android-videography-techniques/"><u>In 2024, Luminous Android Videography Techniques</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-slow-start-technique/"><u>In 2024, Slow Start Technique</u></a></li>
<li><a href="https://some-guidance.techidaily.com/1724765580074-macx-dvd-ripper-pro/"><u>MacX DVD Ripper Pro 無料ダウンロード - 公式サイトから安心してセキュリティ保証</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-microsoft-excel-with-essential-hotkey-techniques-and-tips/"><u>Mastering Microsoft Excel with Essential Hotkey Techniques and Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-microsoft-excels-match-formula-for-efficiently-finding-cell-values-and-their-rows/"><u>Mastering Microsoft Excel's MATCH Formula for Efficiently Finding Cell Values and Their Rows</u></a></li>
<li><a href="https://fox-that.techidaily.com/mastering-the-technique-force-restart-procedure-for-iphones-to-reach-recovery-mode/"><u>Mastering the Technique: Force Restart Procedure for iPhones to Reach Recovery Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modify-excels-initial-spreadsheet-setup-tips-for-changing-the-standard-numbers-at-launch/"><u>Modify Excel's Initial Spreadsheet Setup: Tips for Changing the Standard Numbers at Launch</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-mastering-adobe-premiere-top-6-tricks-for-professional-grade-videos/"><u>New In 2024, Mastering Adobe Premiere Top 6 Tricks for Professional-Grade Videos</u></a></li>
<li><a href="https://program-issues.techidaily.com/overcoming-logitech-configuration-challenges-effective-fixes-for-windows-users/"><u>Overcoming Logitech Configuration Challenges: Effective Fixes for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-remedy-for-rearranged-character-inputs/"><u>Quick Remedy for Rearranged Character Inputs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-adding-and-utilizing-microsoft-office-extensions/"><u>Step-by-Step Guide: Adding & Utilizing Microsoft Office Extensions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-crafting-personalized-excel-templates/"><u>Step-by-Step Guide: Crafting Personalized Excel Templates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-developing-custom-data-types-in-microsoft-excel/"><u>Step-by-Step Guide: Developing Custom Data Types in Microsoft Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-downsizing-pngjpeg-content-in-your-word-and-excel-docs/"><u>Step-by-Step Guide: Downsizing PNG/JPEG Content in Your Word and Excel Docs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-erasing-gridlines-and-preview-pane-in-microsoft-excel/"><u>Step-by-Step Guide: Erasing Gridlines and Preview Pane in Microsoft Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-mastering-text-wrapping-techniques-in-excel/"><u>Step-by-Step Guide: Mastering Text Wrapping Techniques in Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-mastering-uppercase-letters-with-microsoft-excel/"><u>Step-by-Step Guide: Mastering Uppercase Letters with Microsoft Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-printing-targeted-data-selections-from-your-excel-workbook/"><u>Step-by-Step Guide: Printing Targeted Data Selections From Your Excel Workbook</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/eal-number-of-youtube-views-you-need-to-make-a-living-for-2024/"><u>The Real Number of YouTube Views You Need to Make a Living for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-accessing-and-deciphering-obscure-file-types/"><u>The Ultimate Guide to Accessing and Deciphering Obscure File Types</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-master-these-7-microsoft-excel-features-for-superior-financial-planning/"><u>The Ultimate Guide: Master These 7 Microsoft Excel Features for Superior Financial Planning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-csv-files-a-beginners-guide-to-opening-and-usage/"><u>Understanding CSV Files: A Beginner's Guide to Opening & Usage</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/unlocking-tv-potential-with-social-medias-facebook-live-streams-for-2024/"><u>Unlocking TV Potential with Social Media's Facebook Live Streams for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>