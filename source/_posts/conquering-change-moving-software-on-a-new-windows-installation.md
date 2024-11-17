---
title: "Conquering Change: Moving Software on a New Windows Installation"
date: 2024-11-14T19:43:17.137Z
updated: 2024-11-17T17:05:49.897Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267">
  <img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://jalbum-affiliate-program.sjv.io/c/5597632/1584040/17916" target="_top" id="1584040">
  <img src="//a.impactradius-go.com/display-ad/17916-1584040" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://jalbum-affiliate-program.sjv.io/i/5597632/1584040/17916" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<span id="1938141">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938141.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938141">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938141.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938141%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938141/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## What About Any Left Out Apps?

 Even after using both methods, some apps will still be left out. It is because Microsoft Account sign-in only brings back Windows settings and Microsoft Store apps. The winget export file can restore only the apps listed in its official repository.

 As such, you still need to download the programs that aren’t included in both of these methods. But it will be a very short list compared to the effort you would have to put in if you just performed a normal installation.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037474/7443" target="_top" id="2037474">
  <img src="//a.impactradius-go.com/display-ad/7443-2037474" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037474/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Save Time When Setting Up Windows 11

 Make sure to enable files, apps, and preferences backup on your PC and create a winget export file beforehand. After you have both these backups in place, you can begin reinstalling Windows 11 on a different PC or reinstalling on the same PC.

 But what if you could eliminate the hours spent in finding and installing every single app, and configuring every setting? We will discuss two methods to effortlessly migrate most of your old apps to your new PC.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-stream.techidaily.com/new-how-to-capitalize-on-youtube-shorts-must-knows-earning-prospects/"><u>[New] How to Capitalize on Youtube Shorts Must-Knows, Earning Prospects</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-in-2024-finns-fiscal-flow-income-insights-from-youtube-icon/"><u>[Updated] In 2024, Finn's Fiscal Flow Income Insights From YouTube Icon</u></a></li>
<li><a href="https://fox-search.techidaily.com/best-7-iphoneipad-pdf-readers-in-2020-vision-modify-and-additional-features-for-mobile-documents/"><u>Best 7 iPhone/iPad PDF Readers in 2020: Vision, Modify & Additional Features for Mobile Documents</u></a></li>
<li><a href="https://win-solutions.techidaily.com/crash-free-gaming-top-strategies-to-tackle-state-of-decay-2-bugs-this-year/"><u>Crash-Free Gaming: Top Strategies to Tackle State of Decay 2 Bugs This Year!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/devhome-unlocked-delving-into-windows-11s-potential/"><u>DevHome Unlocked: Delving Into Windows 11'S Potential</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enlightening-the-entanglement-of-skyrims-xsb-errors/"><u>Enlightening the Entanglement of Skyrim's XSB Errors</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-an-airtag-from-your-apple-id-account-from-apple-iphone-14-pro-max-by-drfone-ios/"><u>How to Remove an AirTag from Your Apple ID Account From Apple iPhone 14 Pro Max?</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-simulate-gps-movement-in-ar-games-on-honor-magic-5-lite-drfone-by-drfone-virtual-android/"><u>In 2024, How to Simulate GPS Movement in AR games On Honor Magic 5 Lite? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-shortfall-of-physical-storage-space-on-vmware-systems/"><u>Mitigating Shortfall of Physical Storage Space on VMware Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mouse-troubles-resurrecting-sleeping-winos/"><u>Mouse Troubles: Resurrecting Sleeping WinOS</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-mac-vlc-trimmer-effortlessly-cut-videos-without-compromising-quality/"><u>New 2024 Approved Mac VLC Trimmer Effortlessly Cut Videos Without Compromising Quality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-windows-11-for-peak-performance/"><u>Optimizing Windows 11 for Peak Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-remedy-mcuicnt-execution-missing-windows-issue/"><u>Steps to Remedy McUICnt Execution Missing Windows Issue</u></a></li>
<li><a href="https://extra-resources.techidaily.com/trending-memes-galore-unique-themes-for-any-event/"><u>Trending Memes Galore Unique Themes for Any Event</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-age-estimation-tips-and-tricks/"><u>Windows Age Estimation Tips and Tricks</u></a></li>
</ul></div>

