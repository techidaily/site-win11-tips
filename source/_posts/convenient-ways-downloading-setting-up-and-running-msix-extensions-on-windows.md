---
title: "Convenient Ways: Downloading, Setting Up & Running MSIX Extensions on Windows"
date: 2024-08-16T02:17:17.038Z
updated: 2024-08-17T02:17:17.038Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Convenient Ways: Downloading, Setting Up & Running MSIX Extensions on Windows"
excerpt: "This Article Describes Convenient Ways: Downloading, Setting Up & Running MSIX Extensions on Windows"
keywords: MSIX Download Guide,Install MSIX Packages,Run MSIX Extensions,Setup MSIX Apps,Windows MSIX Support,Simplify MSIX Use,Enhance Windows Experience
thumbnail: https://thmb.techidaily.com/65d1648a69e474032218f98a4f9088236faaaabb296646cc458aad0041a1d229.png
---

## Convenient Ways: Downloading, Setting Up & Running MSIX Extensions on Windows

 The new Microsoft Store on Windows 11 works great for the most part. But, for the times it doesn’t, Windows lets you sideload Microsoft Store apps in appx, appxBundle, msixbundle app files on your computer.

 **MUO VIDEO OF THE DAY**

 **SCROLL TO CONTINUE WITH CONTENT**

 You can download the appx or msix package from the app developer’s website, GitHub, or directly from the Microsoft Store server using third-party utilities. Here we show how to download appx/appxbundle and msixbundle package files from Microsoft Store and install them on your Windows computer.

## 1\. How to Download Appx/AppxBundle Files Using Adguard
![adguard msixbundle download](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/adguard-msixbundle-download.jpg)

 Adguard is a third-party web service and an online link generator for Microsoft Store. It makes it easy to download appx and appxbundle files from the Microsoft Store for sideloading them on your Windows computer.

To download appx, appxbundle or msixbundle using Adguard:

1. Go to [Microsoft Store](https://apps.microsoft.com/store/apps) on your browser, search, and open the app you want to download.
2. Copy the app URL, including the product ID, from the address bar. For example, the app URL for the Xbox app on Microsoft Store will look like this:  
`https://apps.microsoft.com/store/detail/xbox/9MV0B5HZVK9Z`
3. Next, go to the [Adguard page](https://store.rg-adguard.net/) and paste the app URL.
4. On the right side, click the**RP** drop-down and select**Retail** .
5. Click the**Check mark** button to generate a direct download link. It will populate the page with msixbundle, appx or appxbundle, and other associated files.
6. You only need to download the full app package. The rest are app dependencies that you don’t need to download in most cases. For example, in this instance, we only need to download**msixbundle** , which is also the largest file in the list.
7. Make sure to check the architecture compatibility (**x64, x86, Arm**) for the files depending on your system architecture.
8. Next, click on the msixbudle link to download. Microsoft Edge may sometimes block the download as not secure. You can use alternative browsers like Google Chrome and Firefox to compelete the download.

## 2\. Generate Microsoft Store Apps Direct Download Links Using Fiddler

 Fiddler Classic is a network tracking and monitoring tool to log HTTP(s) traffic from web browsers and installed apps. You can use this app to track Microsoft Store network when downloading an app to your computer. Then use the URL as a direct download link to download appx, msixbundle, and appxbundle files using any web browser.

To generate a Microsoft Store app downloading link using Fiddler:

1. Download and install the [Fidler Classic app](https://www.telerik.com/download/fiddler) . You’ll need to enter your email and territory to download the app.
2. Open**Fiddler** , and click the**WinConfig** button in the top left corner. Click**Yes** if prompted by User Account Control.  
![Fiddler_WinConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/fiddler_winconfig.jpg)
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. In the**AppContainer Lookback** **Exception Utility** dialog, scroll down and check the**Microsoft Store** box.  
![Fiddler app container loopback exception utlility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/fiddler-app-container-loopback-exception-utlility.jpg)
4. Click on**Save Changes.**
5. Next, click on**Edit** and go to**Remove** , and select**All Sessions** . Alternatively, press**Ctrl + X** to do the same.  
![Filddler remove all sessions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/filddler-remove-all-sessions.jpg)

1. Next, launch**Microsoft Store,** search for the app you want to download, and click**Install** . Wait for the app to download and install completely. Fiddler will start capturing the traffic as the necessary files for the app download and install.
2. Once the download is complete, open the**Fiddler** app and press**Ctrl + F** to open**Find** .
3. Type**appx** in the**Find** dialog. Leave the rest options as default and click**Find Sessions** . It will scan through the recently captured Microsoft Store traffic and highlight the matching entries in yellow.  
![fiddler find session](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/fiddler-find-session.jpg)
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. If no entries are highlighted, open**Find (Ctrl+F)** and type**msixbundle, appx** or**appxbundle** in the**Find** field, and click on**Find Sessions** .  
![Fiddler copy just url](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/fiddler-copy-just-url.jpg)
5. Right-click on any entry highlighted in yellow and select**Copy > Just URL.**
6. Open**Google Chrome** or**Firefox** and paste the copied URL in the address bar. Press**Enter** and click**Save** to download the file. On Microsoft Edge, you may face a connection is not secure error. If so, switch to a different browser to complete the download.

 To install the downloaded appx, appxbundle, or msixbundle file, you can use PowerShell or the App Installer.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
## How to Install Appx, Appxbundle and Msixbundle Apps

 In an ideal situation, you can double-click on the app file package to install it on your Windows computer. However, if that does not work, you can sideload the apps using PowerShell and the official App Installer. Here are the three ways to install the appxbundle and msixbundle file packages on Windows 10 and 11.

<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Install Appx/Appxbundle/Msixbundle App By Running the File
![install appxbundle double click](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/install-appxbundle-double-click.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can install some appx, appxbundle, and msixbundle files like you would do with any .exe file. Follow these steps to sideload and install Universal Windows Platform apps.

1. Locate the saved app package in the**Downloads** folder.
2. Next, double-click on the file to open the installation wizard and click on the**Install** button to install the software.

 Unfortunately, this installation method does not work always. You are likely to run into errors like [this app package is not support installation](https://www.makeuseof.com/app-package-not-supported-installation-app-installer/) . What you can do instead is try to install the app using the App Installer app or PowerShell. You can use PowerShell to install apps not signed by Microsoft Store.

### 2\. Install Appx, Appxbundle, and Msixbundle using App Installer
![microsoft app installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/microsoft-app-installer.jpg)

 Microsoft offers an official App Installer to sideload Windows 10 apps. However, this app installer also works on Windows 11\. If you encounter an error when sideloading apps using the convention double-click method, the App Installer will do the trick.

 Make sure to [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before installing App Installer. Once installed, you may not be able to uninstall the app. And it can also fiddle with Windows PowerShell’s ability to sideload apps.

To install App Installer:

1. Launch**Microsoft Store** and search for the app installer.
2. Click on**App** **Installer** from the search results. The description reads the app lets you sideload Windows 10 apps.
3. Click on Install and wait for it to complete the process.
4. Once installed, click on the appx, appxbundle, or msixbundle file to open it in**App Installer.**
5. Click**Install** and wait for the app installation to finish.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
### 3\. Install Appx, Msixbundle, and Appxbundle Using PowerShell
![install msixbundle sideload powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/install-msixbundle-sideload-powershell.jpg)

 You can use Windows PowerShell to sideload Microsoft Store app on Windows. This is an efficient way to sideload apps on multiple computers or when you get an error while running the msixbundle or other package files.

To install appx, msixbudnle, and appxbundle apps using PowerShell:

1. Press the**Win** key and**powershell** .
2. Right-click on**Windows PowerShell** and select**Run as administrator.**
3. Next, type the following command and press**Enter** to install the app:  
`Add-AppxPackage -Path $AppFilePath`
4. In the above command, replace AppFilePath with the appx, msixbundle, or appxbundle file path. To get the file path, right-click on the file and select**Copy as path.**
5. For example, if you want to install msixbundle for Files Apps, the full command will be something like this:  
`Add-AppxPackage -Path $C:\Users\Username\Downloads\Files.Package.msixbundle`
6. PowerShell will show a progress bar to indicate the installation. Once done, you can launch the app from the Start menu.

 In addition, if you want to install a non-Microsoft Store app file package, you may also need to enable Developer Mode to install UWP apps from third-party sources.

To enable Developer Mode on Windows 11 ![enable developer mode windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-developer-mode-windows-11.jpg)

1. Press**Win + I** to open**Settings** .
2. Open the**Privacy & Security** tab in the left pane,
3. Click on**For Developers** and then toggle the switch for**Developer Mode.**

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
## Download and Install Appx, Appxbundle, and Msixbundle from Microsoft Store on Windows

 Thanks to the built-in sideload support on Windows, you can easily install Microsoft Store and non-store apps on your computer. Adguard and Fiddler handle the important aspect of allowing to download app package files for sideload.

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
<li><a href="https://fox-links.techidaily.com/new-2024-approved-magix-video-pro-x-review/"><u>[New] 2024 Approved  Magix Video Pro X Review</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-saving-pc-views-with-a-single-click-win/"><u>[New] Saving PC Views with a Single Click (Win)</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-windows-snapshot-mastery-3-easy-approaches/"><u>[New] Windows Snapshot Mastery (3 Easy Approaches)</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-gamer-wealth-wave-the-year-ahead/"><u>[Updated] 2024 Approved  Gamer Wealth Wave  The Year Ahead</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-taking-your-reels-up-a-notch-with-these-top-editors/"><u>[Updated] 2024 Approved  Taking Your Reels Up a Notch with These Top Editors</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-free-traffic-on-youtube-tips-that-actually-work/"><u>[Updated] Free Traffic on YouTube  Tips That Actually Work</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-personalize-chromes-sound-review-of-the-top-web-based-speech-converters/"><u>[Updated] Personalize Chrome's Sound  Review of the Top Web-Based Speech Converters</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-instagram-success-starts-here-discovering-top-tracking-and-analysis-apps/"><u>2024 Approved  Instagram Success Starts Here  Discovering Top Tracking and Analysis Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-to-batch-installing-apps-using-winstall-in-windows-11/"><u>A Step-by-Step Approach to Batch Installing Apps Using Winstall in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-chrome-clock-error-ahead-or-behind-windows-edition/"><u>Adjusting Chrome Clock Error: Ahead or Behind? (Windows Edition)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-the-path-to-successful-screen-startup-post-update/"><u>Clearing the Path to Successful Screen Startup Post-Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decrease-overhead-memory-use-by-antivirus-programs/"><u>Decrease Overhead Memory Use by Antivirus Programs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-into-mobility-control-deactivation-win-11/"><u>Dive Into Mobility Control Deactivation (Win 11)</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/edit-in-high-def-the-best-video-software-for-2024/"><u>Edit in High-Def The Best Video Software for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-language-skills-quick-translate-via-windows-key-combinations/"><u>Elevate Language Skills: Quick Translate via Windows Key Combinations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-note-taking-with-obsidians-artistic-touch/"><u>Elevate Note-Taking with Obsidian's Artistic Touch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/empower-control-over-windows-with-alomware-tools/"><u>Empower Control Over Windows With AlomWare Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-communication-translate-foreign-words-with-hotkeys/"><u>Enhance Communication: Translate Foreign Words with Hotkeys</u></a></li>
<li><a href="https://screen-capture.techidaily.com/expert-guide-to-quick-screen-captures-on-mac-using-shortcuts-for-2024/"><u>Expert Guide to Quick Screen Captures on Mac Using Shortcuts for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-csgo-start-problems-on-w11/"><u>Fixing CS:GO Start Problems on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-failed-message-display-on-discord-desktop/"><u>Fixing Failed Message Display on Discord Desktop</u></a></li>
<li><a href="https://extra-hints.techidaily.com/game-speed-controls-unveiled-a-comprehensible-guide/"><u>Game Speed Controls Unveiled  A Comprehensible Guide</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-nokia-130-musicwithwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Nokia 130 Musicwith/without a PC</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-does-openais-shap-enhance-model-insight/"><u>How Does OpenAI's SHAP Enhance Model Insight?</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-locate-or-retrieve-a-lost-forgotten-or-unknown-email-address/"><u>How to Locate or Retrieve a Lost, Forgotten, or Unknown Email Address</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-3utools-virtual-location-not-working-on-honor-90-gt-fix-now-drfone-by-drfone-virtual-android/"><u>In 2024, 3uTools Virtual Location Not Working On Honor 90 GT? Fix Now | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-to-come-up-with-the-best-pokemon-team-on-apple-iphone-11-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Come up With the Best Pokemon Team On Apple iPhone 11 Pro? | Dr.fone</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-pixel-paradise-100plus-game-havens-explored/"><u>In 2024, Pixel Paradise  100+ Game Havens Explored</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-tracking-apps-to-track-vivo-y200-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Tracking Apps to Track Vivo Y200 without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/optimal-4k-video-recording-tools-compilation-for-2024/"><u>Optimal 4K Video Recording Tools Compilation for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overhauling-window-11-mails-default-html-settings-for-clarity/"><u>Overhauling Window 11 Mail's Default HTML Settings for Clarity</u></a></li>
<li><a href="https://tech-hub.techidaily.com/redefining-possibilities-with-openais-latest-innovation-gpt-4-ai-model/"><u>Redefining Possibilities with OpenAI’s Latest Innovation: GPT-4 AI Model</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedies-for-not-enough-memory-available-problem-windows-vmware/"><u>Remedies for 'Not Enough Memory Available' Problem (Windows VmWare)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-overlapping-app-images-in-os-interface/"><u>Removing Overlapping App Images in OS Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sorting-perfection-windows-software-that-shines/"><u>Sorting Perfection: Windows Software That Shines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-correctly-installing-an-ms-store-app/"><u>Steps for Correctly Installing an MS Store App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-enabling-non-standard-windows-apps/"><u>Strategies for Enabling Non-Standard Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-your-gaming-how-to-fix-the-error-code-0x000-in-xbox-game-pass-on-windows-11/"><u>Streamlining Your Gaming: How to Fix the Error Code 0X000_ in Xbox Game Pass on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-your-pcs-display-lock-settings/"><u>Tailor Your PC's Display Lock Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-clear-microsofts-watchdog-logs-on-windows/"><u>Techniques to Clear Microsoft's Watchdog Logs on Windows</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-showdown-is-forefront-ai-a-superior-alternative-to-chatgpt/"><u>The Showdown: Is Forefront AI a Superior Alternative to ChatGPT?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-troubleshooting-and-reviving-dysfunctional-windows-downloads/"><u>Tips for Troubleshooting and Reviving Dysfunctional Windows Downloads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformative-windows-tips-top-20-cmd-commands/"><u>Transformative Windows Tips: Top 20 CMD Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-mending-exception-error-on-win-os/"><u>Understanding and Mending Exception Error on Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-winservicesexe-deciphering-windows-process/"><u>Understanding WinServices.exe: Deciphering Windows Process</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/king-youtubes-potential-for-visual-storytelling-for-2024/"><u>Unlocking YouTube's Potential for Visual Storytelling for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/unpacking-the-features-of-androids-lightroom-app-for-2024/"><u>Unpacking the Features of Android's Lightroom App for 2024</u></a></li>
</ul></div>
