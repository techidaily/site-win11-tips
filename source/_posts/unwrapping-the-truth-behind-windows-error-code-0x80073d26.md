---
title: Unwrapping the Truth Behind Windows' Error Code 0X80073D26
date: 2024-07-29T08:08:28.181Z
updated: 2024-07-30T08:08:28.181Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unwrapping the Truth Behind Windows' Error Code 0X80073D26
excerpt: This Article Describes Unwrapping the Truth Behind Windows' Error Code 0X80073D26
keywords: WinErrorCode_0X80073D26,Code0X80073D26Windows,ErrorCode_0X80073D26Truth,UncoveringWindowsError,Fix0X80073D26Windows,WindowsErrorCodesInvestigate,TruthBehindWinError0X80073D26
thumbnail: https://thmb.techidaily.com/f9dfa57d80070d52083269f7e54688cbc55bc603dffea5c52daaecde9ad2614f.jpg
---

## Unwrapping the Truth Behind Windows' Error Code 0X80073D26

 Error 0x80073D26 is an issue that users have widely reported occurring when trying to install or play Xbox Game Pass titles via Microsoft Store. When this issue arises, users get redirected to install the Gaming Services app in the Microsoft Store. Users then see the “Something unexpected happened” error 0x80073D26 message when they try to install (or update) Gaming Services.

 Players can’t enjoy their Xbox Game Pass titles because of error 0x80073D26, which makes this an annoying issue for Xbox Game Pass users. This is how you can fix the Microsoft Store error 0x80073D26 in Windows

## 1\. Run the Windows Store App Troubleshooting Tool

 This isn’t the most likely solution for error 0x80073D26, but it’s worth trying since Microsoft Store is a UWP app. Running the Windows Store App troubleshooter might detect a Microsoft Store issue and provide a fix. These are the steps for running the Windows Store App troubleshooting utility:

1. Open Settings and click **System** to view that tab.
2. Next, select **Troubleshoot** to reach three troubleshooting navigation options.
3. Bring up the list of troubleshooting tools by clicking **Other trouble-shooters**.
4. Then click **Run** to launch the Windows Store Apps troubleshooting tool.  
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Run button for the Windows App Store troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-app-store-troubleshooter.jpg)
5. Apply all troubleshooting suggestions provided within Windows Store Apps window.  
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
![The Windows Store Apps window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-store-app-troubleshooter.jpg)

 You can run the same troubleshooter tool in Windows 10, but the steps for accessing it are a bit different. Click **Update & Security** \> **Troubleshoot** \> **Additional troubleshooters** in Windows 10’s Settings app. Then select **Windows Store Apps** \> **Run the troubleshooter** to get troubleshooting.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Repair and Reset the Microsoft Store App

 Accumulated and corrupted Microsoft Store cache data is a potential cause for error 0x80073D26\. Resetting the Microsoft Store app via Settings or the Command Prompt will clear the app’s data. Try applying both methods in this guide to resetting Microsoft Store. Also, select the **Repair** option for the Microsoft Store just above its **Reset** button in Settings to see if that resolves the issue.

![The Reset button for Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-button-1.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Edit the Registry

 One of the most widely confirmed fixes for error 0x80073D26 is to enter the Registry and delete the GamingServices and GamingServicesNet Registry keys. Although confirmed to work, we still recommend users [back up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before deleting keys. Then follow these steps for editing the registry:

1. Open the Windows Run accessory by right-clicking **Start** on your taskbar and selecting the **Run** option.
2. Input the **regedit** Run command and click **OK** to [launch the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. Copy and paste this key location in the registry address bar:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services`
4. Right-click the **GamingServices** subkey within the Services key to select **Delete** \> **Yes**.  
![The Delete registry key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/delete-option-1.jpg)
5. Click the **GamingServicesNet** key with the mouse’s right button and select the **Delete** \> **Yes** options.
6. Exit Registry Editor and restart your PC.

## 5\. Reinstall the Microsoft Gaming Service

 One of Microsoft’s official resolutions for error 0x80073D26 is to reinstall Gaming Service. This potential solution involves entering three PowerShell commands that will remove the Gaming Service app along with associated registry entries. These are the steps for applying this potential fix:

1. Activate Windows Search by pressing **Win + S**.
2. Enter **PowerShell** inside the file search tool.
3. Open PowerShell with admin rights by right-clicking that app in the search results and selecting **Run as Administrator**.
4. Next, remove the Gaming Service app by entering this command and hitting **Enter**:  
`Get-AppxPackage *gaming services* -allusers | remove-appxpackage -allusers`  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The remove-app package command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-app-package-command.jpg)
5. Then input these separate commands, pressing **Return** after each:  
`Remove-Item -Path "HKLM:\System\CurrentControlSet\Services\GamingServices" -recurse  

Remove-Item -Path "HKLM:\System\CurrentControlSet\Services\GamingServicesNet" -recurse` 
![The remove-app package command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-app-package-command.jpg)
6. Close out of PowerShell to restart Windows.
7. Reopen Powershell and execute the following command:  
`start ms-windows-store://pdp/?productid=9MWPM2CQNLHN`
8. Then click the **Get** button for installing Gaming Service.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
## 5\. Perform Some Generic Windows Fixes for Errors

 Windows is by no means impervious to errors. Fortunately, there are some tricks you can apply to almost every error, including this one.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
### Repair System Files
![The Reset button for Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-button-1.jpg)

 To begin with, try repairing system files to see if there are any issues. You can do that by executing a System File Checker scan within the Command Prompt. That tool will check for and repair corrupted system files detected when you run its command. To apply this potential fix, follow the instructions in our [how to run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide.

### Set Windows to Clean Boot
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-services-tab.jpg)

 Another possibility is that a software conflict might be causing error 0x80073D26 to occur on your PC. Setting Windows to clean boot by disabling third-party startup items will likely eliminate such a potential cause. That will stop third-party apps and services that could be conflicting with the Microsoft Store from automatically starting.

 To apply this fix, check out this guide about [clean-booting Windows 10 or 11](https://www.makeuseof.com/clean-boot-windows-11/). Disable startup programs in Task Manager and services in MS Config as covered within that guide; then restart your PC and try installing Microsoft Store games again to see if the issue persists.

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Reinstall the Microsoft Store
![The remove Microsoft Store command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-microsoft-store-command.jpg)

 Some users might need to reinstall the Microsoft Store to fix error 0x80073D26\. Such a resolution might be necessary for fixing wider issues with the Microsoft Store app other potential solutions don’t address.

 There isn’t a standard uninstall option available for Microsoft Store. So, you’ll have to reinstall that app with two PowerShell commands. Our guide about [how to reinstall the Microsoft Store](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) tells you how to apply this potential fix.

### Perform an In-Place Windows Upgrade

 Some Microsoft Store users have also fixed error 0x80073D26 by performing an in-place Windows upgrade. An in-place upgrade is a method for installing the latest Windows 11/10 version without losing any installed software or user files.

 This will likely fix the 0x80073D26 error because it will refresh all of the system's registry entries, the system files, and also upgrade Windows to the latest version.

 Performing a Windows 11 in-place upgrade is relatively straightforward. All you need to do is download the latest Windows 11 ISO file, open it up, and launch the setup wizard from there. Our article about [performing an in-place upgrade of Windows 11](https://www.makeuseof.com/in-place-upgrade-windows-11/) includes full guidelines for how to do this.

![The Windows 11 Setup window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-11-setup-window2.jpg)

 You can also perform a Windows 10 in-place upgrade much the same. One difference is that you’ll need to download a Windows 10 Setup file by clicking **Download tool** on the [Microsoft Windows 10 download webpage](https://www.microsoft.com/en-gb/software-download/windows10). Then select **Upgrade this PC** now in the Windows 10 Setup wizard to install the latest version of the OS.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
## Enjoy the Best Xbox Game Pass Games Available on the Microsoft Store

 It’s very likely the potential resolutions covered in this guide will fix error 0x80073D26, as some of them are widely confirmed to work. Hopefully, you can get this error fixed and get back into gaming.

 Players can’t enjoy their Xbox Game Pass titles because of error 0x80073D26, which makes this an annoying issue for Xbox Game Pass users. This is how you can fix the Microsoft Store error 0x80073D26 in Windows



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-data.techidaily.com/ccess-creative-banners-for-video-makers-at-zero-price/"><u>[New] Access Creative Banners for Video Makers at Zero Price</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-twitter-video-downloader-download-twitter-videos-to-iphone/"><u>[New] In 2024, Twitter Video Downloader  Download Twitter Videos to iPhone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-mastering-virality-in-instagram-clips/"><u>[Updated] 2024 Approved  Mastering Virality in Instagram Clips</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-essential-android-video-capture-the-best-5-picks/"><u>[Updated] In 2024, Essential Android Video Capture  The Best 5 Picks</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-immediate-techniques-for-instagram-video-audio-extraction-mp3/"><u>[Updated] In 2024, Immediate Techniques for Instagram Video Audio Extraction (MP3)</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-listeners-lens-sound-study/"><u>[Updated] In 2024, Listener's Lens  Sound Study</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-ranking-of-free-easy-to-use-image-overlay-apps-on-smartphones/"><u>[Updated] Ranking of Free, Easy-to-Use Image Overlay Apps on Smartphones</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-streamline-your-content-a-tutorial-for-instagram-video-sharing/"><u>[Updated] Streamline Your Content  A Tutorial for Instagram Video Sharing</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-beginners-ultimate-list-of-youtube-production-tools/"><u>2024 Approved  Beginner's Ultimate List of YouTube Production Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-muted-slack-notifications-on-windows-11/"><u>Addressing Muted Slack Notifications on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-screen-failure-during-boot-up-in-windows-11/"><u>Addressing Screen Failure During Boot-Up in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-typing-pace-in-windows-11-overcome-keyboard-latency/"><u>Boost Your Typing Pace in Windows 11: Overcome Keyboard Latency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/common-windows-11-22h2-issues-and-their-fixes/"><u>Common Windows 11 22H2 Issues and Their Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-reference-to-non-existent-token-errors-in-win11/"><u>Correcting “Reference to Non-Existent Token” Errors in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciding-on-nearby-transfer-google-vs-windows-options/"><u>Deciding on Nearby Transfer: Google Vs. Windows Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/editing-directory-names-for-users-in-windows-11-edition/"><u>Editing Directory Names for Users in Windows 11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-microphone-errors-during-valorant-matches/"><u>Eliminating Microphone Errors During Valorant Matches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhanced-collaboration-on-a-sleeker-platform/"><u>Enhanced Collaboration on a Sleeker Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-1011s-trouble-solving-capabilities/"><u>Enhancing Windows 10/11'S Trouble-Solving Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-guide-to-top-7-secure-windows-applications-153-chars/"><u>Exclusive Guide to Top 7 Secure Windows Applications (153 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expedite-your-browser-eliminating-youtube-stalls-in-chrome/"><u>Expedite Your Browser: Eliminating YouTube Stalls in Chrome</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-the-differences-between-exe-and-msi-files/"><u>Exploring the Differences Between EXE & MSI Files</u></a></li>
<li><a href="https://extra-resources.techidaily.com/fast-facial-masking-on-piscart-a-convenient-guide/"><u>Fast Facial Masking on PiscArt  A Convenient Guide</u></a></li>
<li><a href="https://extra-resources.techidaily.com/from-novice-to-expert-a-telegram-web-blueprint/"><u>From Novice to Expert  A Telegram Web Blueprint</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-update-files-are-missing-error-0x80070003-on-windows/"><u>How to Fix the Update Files Are Missing Error 0X80070003 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-locate-the-lurking-lost-disk/"><u>How to Locate the Lurking Lost Disk</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-actions-your-guide-to-repairing-windows-software-glitches/"><u>Immediate Actions: Your Guide to Repairing Windows Software Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-windows-search-11-key-strategies/"><u>Master Your Windows Search: 11 Key Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-no-lags-smoother-youtube-videos-on-windows/"><u>Navigate No Lags: Smoother YouTube Videos on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-cannot-continue-error-in-amd-installation/"><u>Overcoming the 'Cannot Continue' Error in AMD Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-failure-lockout-period-on-sign-in-errors/"><u>Personalizing Failure Lockout Period on Sign In Errors</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-contacts-from-vivo-y02t-by-fonelab-android-recover-contacts/"><u>Possible solutions to restore deleted contacts from Vivo Y02T.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prevent-unwanted-launch-of-snipping-tool-via-print-screen-in-win-11/"><u>Prevent Unwanted Launch of Snipping Tool via Print Screen in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-the-application-could-not-load-qt-plugin-error/"><u>Rectifying the 'Application Could Not Load Qt Plugin' Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionize-productivity-essential-windows-based-tools-listed/"><u>Revolutionize Productivity: Essential Windows-Based Tools Listed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-smooth-file-transfers-tips-and-tricks-for-windows-users/"><u>Securing Smooth File Transfers: Tips & Tricks for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/starting-smart-with-windows-hidden-folders/"><u>Starting Smart with Windows' Hidden Folders</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-fundamentals-of-quantum-hdr-efficiency/"><u>The Fundamentals of Quantum HDR Efficiency</u></a></li>
<li><a href="https://ai-topics.techidaily.com/the-recommended-natural-ai-hindi-voice-generator-for-2024/"><u>The Recommended Natural AI Hindi Voice Generator for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/timely-changes-essential-windows-programs-for-editing-file-dates/"><u>Timely Changes: Essential Windows Programs for Editing File Dates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-troubleshooting-msvcr120-deficiency-windows-wise/"><u>Tips for Troubleshooting Msvcr120 Deficiency Windows-Wise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trimming-down-excessive-cpu-usage-in-windows-hosts/"><u>Trimming Down Excessive CPU Usage in Windows Hosts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-telnet-on-windows-11-systems/"><u>Unlocking Telnet on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unmasking-your-worldwide-address-through-cmd-windows/"><u>Unmasking Your Worldwide Address Through CMD, Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-drag-recover-lost-functionality-fast/"><u>Win11 Drag: Recover Lost Functionality Fast</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-command-center-for-app-and-browser-authority/"><u>Windows Command Center for App and Browser Authority</u></a></li>
</ul></div>
