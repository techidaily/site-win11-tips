---
title: "Transferring Older PC Tools: From Legacy Systems to Windows 11"
date: 2024-08-08T11:11:57.698Z
updated: 2024-08-09T11:11:57.698Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Transferring Older PC Tools: From Legacy Systems to Windows 11"
excerpt: "This Article Describes Transferring Older PC Tools: From Legacy Systems to Windows 11"
keywords: Older PC Transition,Legacy System Upgrade,Windows 11 Tooling,XP to Windows Conversion,Retro PC Tools for Modern OS,Migrating Legacy Software,Win11 From PCs Past
thumbnail: https://thmb.techidaily.com/243178c138d6204ad2bbeb47ec4cfcdba020958c11cab04cb22d5f5327eef01b.jpg
---

## Transferring Older PC Tools: From Legacy Systems to Windows 11

 Setting up Windows 11 on your PC, or another PC is a laborious task. After installing the operating system and the OEM drivers, there is still a lot of work left. You need to reconfigure your system settings, re-download, and install all the Microsoft Store apps. Along with that, you need to individually download and install each third-party software, which makes it more challenging.

 But what if you could eliminate the hours spent in finding and installing every single app, and configuring every setting? We will discuss two methods to effortlessly migrate most of your old apps to your new PC.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Using Microsoft Account

 If you used a Microsoft account on your old PC, Windows 11 offers multiple options to back up your App list, Preferences, and use OneDrive for personal files. To do that, you must enable [OneDrive](https://www.makeuseof.com/what-is-onedrive/)and back up all your personal files and folders to it. It will only take care of the files part but the apps and preferences are still left. But you must also enable the backup of these two things on your old PC before [reinstalling Windows 11](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/) or migrating to a new PC.

 Repeat the following steps to enable apps and settings backup:

1. Press **Win + I** to launch the Settings app. Navigate to **Accounts > Windows backup** section.
2. Go to the **Remember my apps** option and click on the toggle next to it to enable the settings.
3. Next, click on the toggle next to **Remember my preferences** option to back up your settings as well.  
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Backup Apps and Preferences to Microsoft Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/backup-apps-and-preferences-to-microsoft-account.jpg)
4. You will notice that the top section of the Windows backup page will mark each of these features as “**backed up**”.

 After you reinstall Windows 11, the OOBE page will ask you to [sign in with a Microsoft account](https://www.makeuseof.com/windows-switch-local-account-to-microsoft-account/). Enter your credentials, and you will see a “Welcome back, User!” message with an option to restore all apps, settings, and files present on your previous machine. Click on the **Next** button and proceed setup up your new PC

![Install Old Apps Using Microsoft Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-old-apps-using-microsoft-account.jpg)

 As soon as you boot to the desktop, you will see a popup that Windows is trying to restore the most used apps from before. It will ask you to open Microsoft Store to restore additional apps from your old PC. Click on the **Restore my apps** button.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Import Apps Using Winget in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/import-apps-using-winget-in-windows-11.jpg)
5. Patiently wait while winget downloads and installs all the packages in the JSON file one by one. Then, close the Command Prompt window.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
## What About Any Left Out Apps?

 Even after using both methods, some apps will still be left out. It is because Microsoft Account sign-in only brings back Windows settings and Microsoft Store apps. The winget export file can restore only the apps listed in its official repository.

 As such, you still need to download the programs that aren’t included in both of these methods. But it will be a very short list compared to the effort you would have to put in if you just performed a normal installation.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
## Save Time When Setting Up Windows 11

 Make sure to enable files, apps, and preferences backup on your PC and create a winget export file beforehand. After you have both these backups in place, you can begin reinstalling Windows 11 on a different PC or reinstalling on the same PC.

 But what if you could eliminate the hours spent in finding and installing every single app, and configuring every setting? We will discuss two methods to effortlessly migrate most of your old apps to your new PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-2023s-facebook-video-grabber-windowsmacosandroid/"><u>[New] In 2024, 2023'S Facebook Video Grabber  Windows/macOS/Android</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-mastering-the-art-of-digital-distortion-in-minutes/"><u>[New] Mastering the Art of Digital Distortion in Minutes</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-masterpiece-moments-iphone-plus-androids-best-ig-covers-for-2024/"><u>[New] Masterpiece Moments  IPhone + Android's Best IG Covers for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-transform-your-video-footage-with-advanced-screen-recording-tech/"><u>[New] Transform Your Video Footage with Advanced Screen Recording Tech</u></a></li>
<li><a href="https://printer-issues.techidaily.com/trouble-windows-fails-to-load-printer-driver/"><u>[TROUBLE] Windows Fails to Load Printer Driver</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-enhancing-the-speed-of-vimeo-videos/"><u>[Updated] 2024 Approved  Enhancing the Speed of Vimeo Videos</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-a-guide-to-formulating-successful-product-sponsorships-in-youtubespace/"><u>[Updated] A Guide to Formulating Successful Product Sponsorships in YouTubespace</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-uncomplicated-ways-to-save-vimeo-content-for-2024/"><u>[Updated] Uncomplicated Ways to Save Vimeo Content for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-essential-fixes-for-fbm-not-working-here/"><u>10 Essential Fixes for FBM Not Working Here</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-2023s-leading-platforms-for-picture-frame-adjustment-techniques/"><u>2024 Approved  2023'S Leading Platforms for Picture Frame Adjustment Techniques</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-the-ultimate-instagram-photography-guide-for-crafting-perfect-covers/"><u>2024 Approved  The Ultimate Instagram Photography Guide for Crafting Perfect Covers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-tips-to-quickly-solve-windows-screen-problems/"><u>5 Tips to Quickly Solve Windows Screen Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-new-features-the-moment-4-update-added-to-windows-11/"><u>7 New Features the Moment 4 Update Added to Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-potential-exciting-enhancements-from-w11-22h2-moment/"><u>7 Potential Exciting Enhancements From W11 22H2 Moment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-ways-to-free-up-local-drive-space-without-deleting-files-on-windows-11/"><u>8 Ways to Free Up Local Drive Space Without Deleting Files on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-new-dimension-in-windows-11-understanding-the-role-of-copilot-key/"><u>A New Dimension in Windows 11: Understanding the Role of Copilot Key</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-preparing-your-pc-before-win-upgrade/"><u>A Step-by-Step Guide to Preparing Your PC Before Win Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-system-operations-using-windows-task-scheduler/"><u>Accelerate System Operations Using Windows Task Scheduler</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-battery-health-monitoring-set-up-full-charge-indicators-in-win11/"><u>Accelerating Battery Health Monitoring: Set Up Full Charge Indicators in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-typing-top-7-tricks-for-fast-input-on-win-pcs/"><u>Accelerating Typing: Top 7 Tricks for Fast Input on Win PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-network-configurations-in-win11/"><u>Accessing Network Configurations in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-nighttime-display-in-notepad-windows-11-edition/"><u>Activating Nighttime Display in Notepad Windows 11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-system-file-checker-a-quick-tutorial/"><u>Activating System File Checker: A Quick Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/address-unsigned-files-issue-for-updated-pcs/"><u>Address 'Unsigned' Files Issue for Updated PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-and-amending-system-call-failures-in-modern-windows/"><u>Addressing and Amending System Call Failures in Modern Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-error-code-30015-26-in-microsoft-365-for-users/"><u>Addressing Error Code 30015-26 in Microsoft 365 for Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-service-did-not-respond-issue-in-windows/"><u>Addressing Service Did Not Respond Issue in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-user-permissions-issues-with-organizational-settings-in-windows-11/"><u>Addressing User Permissions Issues with Organizational Settings in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-11-screen-tick/"><u>Addressing Window's 11 Screen Tick</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-user-interface-customization-for-win-11/"><u>Advanced User Interface Customization for Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/aligning-chrome-and-system-time-windows-sync-tips/"><u>Aligning Chrome and System Time (Windows Sync Tips)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/alt-tab-techniques-efficiently-arrange-your-open-windows-win1110/"><u>Alt-Tab Techniques: Efficiently Arrange Your Open Windows (Win11/10)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-windows-11-outputs-with-savvy-techniques/"><u>Amplify Windows 11 Outputs with Savvy Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automated-awareness-quick-open-of-windows-and-sticky-notebooks/"><u>Automated Awareness: Quick Open of Windows and Sticky Notebooks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automating-wifi-network-deletion-in-win-11/"><u>Automating Wifi Network Deletion in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-the-trouble-fixing-corrupted-recycle-bin-on-win1011/"><u>Avoid the Trouble: Fixing Corrupted Recycle Bin on Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719327449344-bargain-hunters-rejoice-key-lovers-snag-best-prices-for-lifetime-windows-11/"><u>Bargain Hunters Rejoice: Key Lovers Snag Best Prices for Lifetime Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beating-elusive-obs-recording-glitches-on-windows-operating-system/"><u>Beating Elusive OBS Recording Glitches on Windows Operating System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-kept-secrets-eclectic-windows-11-styles/"><u>Best-Kept Secrets: Eclectic Windows 11 Styles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bitlocker-free-windows-4-effective-security-measures/"><u>BitLocker-Free Windows: 4 Effective Security Measures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719365152122-boost-windows-with-top-2023-ms-store-winners/"><u>Boost Windows with Top 2023 MS Store Winners!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-code-development-top-wls-2-methods-on-latest-oses/"><u>Boost Your Code Development: Top WLS 2 Methods on Latest OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-file-management-in-windows-11/"><u>Boosting File Management in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-net-speed-win-pc-download-acceleration-tips/"><u>Boosting Net Speed: Win-PC Download Acceleration Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-system-performance-with-advanced-virtual-memory-management-techniques/"><u>Boosting System Performance with Advanced Virtual Memory Management Techniques</u></a></li>
<li><a href="https://extra-resources.techidaily.com/comprehensive-discussion-googles-podcast-uncovered/"><u>Comprehensive Discussion  Google's Podcast Uncovered</u></a></li>
<li><a href="https://fox-http.techidaily.com/enhancing-visuals-through-selective-zooming/"><u>Enhancing Visuals Through Selective Zooming</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-about-oppo-find-x6-frp-bypass-by-drfone-android/"><u>In 2024, About Oppo Find X6 FRP Bypass</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-tiktok-to-see-more-content-on-your-oneplus-12-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location on TikTok to See More Content On your OnePlus 12 | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-maximizing-your-content-tips-for-rl-recording-and-editing/"><u>In 2024, Maximizing Your Content  Tips for RL Recording & Editing</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-reimagine-photos-with-picshots-simple-techniques/"><u>In 2024, Reimagine Photos with Picshot’s Simple Techniques</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-the-complete-guide-to-poco-f5-pro-5g-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Complete Guide to Poco F5 Pro 5G FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://data-recovery.techidaily.com/innovative-data-retrieval-software-for-iphones/"><u>Innovative Data Retrieval Software for iPhones</u></a></li>
<li><a href="https://fix-guide.techidaily.com/realme-c53-bootloop-problem-how-to-fix-it-without-data-loss-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Realme C53 Bootloop Problem, How to Fix it Without Data Loss | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/recommendations-to-overcome-live-breakdowns-fb-for-2024/"><u>Recommendations to Overcome Live Breakdowns (FB) for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/tickletech-design-easy-entertaining-visuals-for-2024/"><u>TickleTech  Design Easy, Entertaining Visuals for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/0plus-creative-youtubes-channel-names-for-aspiring-vloggers-no-more-than-156-characters/"><u>Top 10+ Creative YouTubes Channel Names for Aspiring Vloggers (No More than 156 Characters)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719366332809-trouble-at-clipcraft-unravel-fixes-today/"><u>Trouble at ClipCraft? Unravel Fixes Today</u></a></li>
<li><a href="https://change-location.techidaily.com/what-legendaries-are-in-pokemon-platinum-on-vivo-s18e-drfone-by-drfone-virtual-android/"><u>What Legendaries Are In Pokemon Platinum On Vivo S18e? | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/whispering-wonders-for-zzzs-choice-vocalists/"><u>Whispering Wonders for Zzz's  Choice Vocalists</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>