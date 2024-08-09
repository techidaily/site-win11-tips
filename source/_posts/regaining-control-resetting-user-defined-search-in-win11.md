---
title: "Regaining Control: Resetting User-Defined Search in Win11"
date: 2024-08-08T11:07:02.143Z
updated: 2024-08-09T11:07:02.143Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Regaining Control: Resetting User-Defined Search in Win11"
excerpt: "This Article Describes Regaining Control: Resetting User-Defined Search in Win11"
keywords: Win11 Search Customize,Reset Search Win11,Control User Search,Win11 Default Settings,Win11 Privacy Options,Manage Windows Search,Reconfigure Win11 Indexing
thumbnail: https://thmb.techidaily.com/35506a9c5eeb39965a6739f4255f2a7fd3073f2c89e35224944b9c79ce0abec8.jpg
---

## Regaining Control: Resetting User-Defined Search in Win11

 Like any other computer program, Windows Search can sometimes develop issues that require you to reset its settings to work properly. This article explains two simple ways to reset Windows Search settings back to default. Let's look at each one in detail.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
## Why Should You Reset Windows Search Settings?

 Windows Search tracks files and folders on your hard drive, so you can find them more quickly. However, over time search settings and preferences can become corrupted, leading to incorrect search results or slow performance. To get the most effective results from Windows Search, you should periodically reset your search settings.

 Resetting search settings on Windows can improve search speed and accuracy. It gets rid of useless data and resolves errors or conflicts due to stored information. This can ultimately enhance your computer’s performance and provide a more efficient search experience.

 Let's now explore how to reset Windows Search settings.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 1\. Tweak the Registry Editor

 If you want to reset Windows Search settings back to default, you can modify the registry editor. It involves directly changing certain keys in the Windows Registry, which can sometimes become risky if done incorrectly.

 To avoid this issue, be sure to [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before proceeding. Once done, follow these steps.

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the dialog box and hit the Enter key.
3. When the UAC prompt appears on the screen, click **Yes** to continue.
4. In the Registry Editor window, navigate to the following path:  
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows Search  
 You can also copy and paste the path into the address bar at the top of the window and hit the Enter key. This will take you to the Windows Search section.
5. Now move to the right pane and search for the key named **SetupCompletedSuccessfully**.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Reset Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-search.jpg)
6. Select this key, right-click on it, and choose **Modify**.
7. Set the value to **0** and click **OK** to save the changes.

 If the SetupCompletedSuccessfully key is missing, you will have to manually create it. To do this, right-click on the Windows Search key and select **New > DWORD (32-bit) Value**. Name this newly created key as **SetupCompletedSuccessfully** and set its value to **0**.

 After performing the steps above, close the Registry Editor and restart your computer for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Use Windows PowerShell

 If you prefer command-line solutions, you can use PowerShell to reset Windows Search settings. It involves running a few simple commands to restore search settings. Here's how to do it.

[Open the Microsoft Download Page](https://www.microsoft.com/en-us/download/100295) and download the ResetWindowsSearchBox.ps1 PowerShell script. Once downloaded, right-click on the file and select **Run with PowerShell**.

 If you see an error message _"Cannot be loaded because the running script is disabled on this system"_ you need to enable script execution first. To do that, [open PowerShell as a system administrator](http://www.makeuseof.com/windows-11-powershell-administrator/). Then type **Get-ExecutionPolicy** and press Enter.

![Restrict or Unrestrict the Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restrict-or-unrestrict-the-command.png)

 If the output is **Restricted**, execute the following command to allow PowerShell scripts:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted

 After setting the execution policy, try running the ResetWindowsSearchBox.ps1 file again. Once the script is executed successfully, it resets Windows search settings.

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
![Reset Windows Search Via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-search-via-powershell.png)

 After resetting the Windows Search settings, you can restore the execution policy to its original settings. To do that, open PowerShell as an administrator again and execute the following command:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Restricted

 Once the execution policy is set back to its original value, restart your computer. The Windows Search settings should now be restored to their default state.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Easy Ways to Reset Windows Search

 Resetting Windows search settings can fix any issues you may have with your search experience. This guide will teach you how to reset Windows Search settings to their original values.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-achieve-higher-interactions-mastering-the-art-of-square-videos/"><u>[New] 2024 Approved  Achieve Higher Interactions  Mastering the Art of Square Videos</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-from-snapshots-to-delights-viral-eats-you-need-in-your-life/"><u>[New] 2024 Approved  From Snapshots to Delights  Viral Eats You Need in Your Life</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-quick-and-quiet-recording-of-games/"><u>[New] 2024 Approved  Quick and Quiet Recording of Games</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-expert-insights-on-efficiently-setting-up-and-analyzing-fb-instream-ad-campaigns-for-2024/"><u>[New] Expert Insights on Efficiently Setting Up and Analyzing FB Instream Ad Campaigns for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-the-complete-process-of-scheduling-google-meets/"><u>[New] In 2024, The Complete Process of Scheduling Google Meets</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-srt-transition-subbed-content-conversion-strategies/"><u>[New] SRT Transition  Subbed Content Conversion Strategies</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-leading-edge-selecting-9-superior-online-microphone-recorders-for-2024/"><u>[Updated] Leading Edge  Selecting 9 Superior Online Microphone Recorders for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-streamline-your-sound-key-audio-interfaces-for-podcasters/"><u>2024 Approved  Streamline Your Sound  Key Audio Interfaces for Podcasters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-secrets-to-swiftly-concluding-a-troubled-update-process/"><u>5 Secrets to Swiftly Concluding a Troubled Update Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-smooth-operator-install-in-windows-realm/"><u>Achieve Smooth Operator Install in Windows Realm</u></a></li>
<li><a href="https://win11-tips.techidaily.com/becoming-a-storage-strategy-expert-with-windows-diskusage-commands-mastery/"><u>Becoming a Storage Strategy Expert with Windows' DiskUsage Commands Mastery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crucial-mistakes-to-sidestep-on-your-first-day-with-windows-11/"><u>Crucial Mistakes to Sidestep on Your First Day with Windows 11</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/easy-guide-to-tecno-spark-go-2023-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Tecno Spark Go (2023) FRP Bypass With Best Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-steps-to-run-windows-media-player/"><u>Easy Steps to Run Windows Media Player</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-computer-experience-running-task-manager-as-admin-on-win11/"><u>Elevate Your Computer Experience: Running Task Manager as Admin on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-compliance-with-insider-editions/"><u>Ensuring Compliance with Insider Editions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-msresourceappnametext-glitch-win11-style/"><u>Fixing 'MsResource:AppName/Text Glitch', Win11 Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-unsuccessful-onedrive-operations-in-windows-10-and-11/"><u>Fixing Unsuccessful OneDrive Operations in Windows 10 & 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-music-from-xiaomi-redmi-12-by-fonelab-android-recover-music/"><u>How to retrieve erased music from Xiaomi Redmi 12</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-suppress-gaming-suggestions-in-windows-11-ui/"><u>How to Suppress Gaming Suggestions in Windows 11 UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-update-audio-drivers-on-windows/"><u>How to Update Audio Drivers on Windows</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-a-comprehensive-guide-to-apple-iphone-13-mini-blacklist-removal-tips-and-tools-by-drfone-ios/"><u>In 2024, A Comprehensive Guide to Apple iPhone 13 mini Blacklist Removal Tips and Tools</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-xiaomi-mix-fold-3-drfone-by-drfone-android/"><u>In 2024, How To Use Allshare Cast To Turn On Screen Mirroring On Xiaomi Mix Fold 3 | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-is-it-possible-to-use-miracast-with-apple-iphone-12-drfone-by-drfone-ios/"><u>In 2024, Is it Possible to Use Miracast with Apple iPhone 12? | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-maximum-mac-gif-recorder/"><u>In 2024, Maximum Mac Gif Recorder</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-the-essentials-of-creating-a-personalized-twitter-account/"><u>In 2024, The Essentials of Creating a Personalized Twitter Account</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-vsx-screen-grabber-insight-detailed-overview/"><u>In 2024, VSX Screen Grabber Insight  Detailed Overview</u></a></li>
<li><a href="https://technical-tips.techidaily.com/ios-18-launch-details-free-update-key-enhancements-and-latest-announcements/"><u>IOS 18 Launch Details - Free Update, Key Enhancements, & Latest Announcements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-swift-typing-techniques-with-powertoys/"><u>Master Swift Typing Techniques with PowerToys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-windows-landscape-incorporate-outlook-preview/"><u>Master the Windows Landscape: Incorporate Outlook Preview</u></a></li>
<li><a href="https://technical-tips.techidaily.com/mastering-multiplayer-connecting-your-nintendo-switch-to-a-flatscreen-display/"><u>Mastering Multiplayer: Connecting Your Nintendo Switch to a Flatscreen Display</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-windows-1011-eliminating-email-app-errors/"><u>Mending Windows 10/11: Eliminating Email App Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-print-control-in-windows-11-9-ways-short-version-max-48-chars/"><u>Navigating Print Control in Windows 11 (9 Ways) - Short Version (Max 48 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-11-with-ease-access-calculator/"><u>Navigating Windows 11 with Ease: Access Calculator</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-s-most-popular-free-video-fx-apps-for-iphone-and-android-for-2024/"><u>New S Most Popular Free Video FX Apps for iPhone and Android for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-0x80070570-error-in-windows-restoring-damaged-data/"><u>Overcoming 0X80070570 Error in Windows: Restoring Damaged Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-updater-problem-code-0x8019/"><u>Overcoming Updater Problem: Code 0X8019</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-speed-by-tweaking-msram/"><u>Regain Speed by Tweaking MSRam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/repairing-slow-or-non-responsive-windows-download-area/"><u>Repairing Slow or Non-Responsive Windows Download Area</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-non-working-windows-lock-screen-delay/"><u>Reviving Non-Working Windows Lock Screen Delay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safeguard-files-when-maximizing-space-in-windows/"><u>Safeguard Files When Maximizing Space in Windows</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/securely-capturing-and-storing-itunes-media-content-for-2024/"><u>Securely Capturing and Storing iTunes Media Content for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-failed-cloud-operations-on-windows-devices/"><u>Solutions for Failed Cloud Operations on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-sharpen-your-windows-11-multi-tasking-skills/"><u>Strategies to Sharpen Your Windows 11 Multi-Tasking Skills</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solution-to-windows-os-not-found-error/"><u>Swift Solution to Windows OS 'Not Found' Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-dism-error-0x800f082f-on-windows/"><u>Tackling DISM Error 0X800F082F on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-resolving-ubisoft-launcher-not-found-issue/"><u>Troubleshooting: Resolving Ubisoft Launcher Not Found Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-zero-error-mystery-in-windows-11-updates/"><u>Unraveling Zero-Error Mystery in Windows 11 Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unsupported-hardware-to-next-gen-os-in-eight-steps/"><u>Unsupported Hardware to Next-Gen OS in Eight Steps</u></a></li>
</ul></div>
