---
title: "Preserving Your Productivity: Transferring Legacy Programs to 11"
date: 2024-09-21T17:31:44.069Z
updated: 2024-09-28T17:51:11.345Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Preserving Your Productivity: Transferring Legacy Programs to 11"
excerpt: "This Article Describes Preserving Your Productivity: Transferring Legacy Programs to 11"
keywords: Productivity Boosting Tips,Legacy Programs Migration,Preserve Work Efficiency,Shift Software Successfully,Upgrade Program Systems,Transfer Tech Wisdom,Enhance Operational Flow
thumbnail: https://thmb.techidaily.com/3be6004f814f322eb7c81e59f5f3e6dc5377a1a28f18fb94887b3ff8d1dce543.jpg
---

## Preserving Your Productivity: Transferring Legacy Programs to 11

 Setting up Windows 11 on your PC, or another PC is a laborious task. After installing the operating system and the OEM drivers, there is still a lot of work left. You need to reconfigure your system settings, re-download, and install all the Microsoft Store apps. Along with that, you need to individually download and install each third-party software, which makes it more challenging.

 But what if you could eliminate the hours spent in finding and installing every single app, and configuring every setting? We will discuss two methods to effortlessly migrate most of your old apps to your new PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137218/26400" target="_top" id="2137218">
  <img src="//a.impactradius-go.com/display-ad/26400-2137218" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137218/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1328683">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1328683.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1328683">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1328683.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1328683%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1328683/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136613/26400" target="_top" id="2136613">
  <img src="//a.impactradius-go.com/display-ad/26400-2136613" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136613/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## What About Any Left Out Apps?

 Even after using both methods, some apps will still be left out. It is because Microsoft Account sign-in only brings back Windows settings and Microsoft Store apps. The winget export file can restore only the apps listed in its official repository.

 As such, you still need to download the programs that aren’t included in both of these methods. But it will be a very short list compared to the effort you would have to put in if you just performed a normal installation.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2136548/16384" target="_top" id="2136548">
  <img src="//a.impactradius-go.com/display-ad/16384-2136548" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136548/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Save Time When Setting Up Windows 11

 Make sure to enable files, apps, and preferences backup on your PC and create a winget export file beforehand. After you have both these backups in place, you can begin reinstalling Windows 11 on a different PC or reinstalling on the same PC.

 But what if you could eliminate the hours spent in finding and installing every single app, and configuring every setting? We will discuss two methods to effortlessly migrate most of your old apps to your new PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-screen-grab.techidaily.com/new-essential-steps-for-iphone-7-screen-capture/"><u>[New] Essential Steps for iPhone 7 Screen Capture</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-unlock-camera-live-screen-capture-analysis-and-top-replacements/"><u>[New] Unlock Camera Live Screen Capture Analysis & Top Replacements</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-xiaomi-11-a-new-era-of-high-fidelity-video-recording/"><u>[New] Xiaomi 11 A New Era of High Fidelity Video Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-fresh-windows-beginning-navigating-3-reset-routes/"><u>A Fresh Windows Beginning: Navigating 3 Reset Routes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-guide-to-eliminate-hardware-detection-faults/"><u>A Quick Guide to Eliminate Hardware Detection Faults</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-incorrect-side-by-side-setup-on-windows-os/"><u>Addressing 'Incorrect Side-by-Side Setup' On Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-directx-update-problems-in-windows-os/"><u>Addressing DirectX Update Problems in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-taskbar-icon-glitches-in-win-108/"><u>Addressing Taskbar Icon Glitches in Win 10/8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-tactics-for-superior-windows-navigation-eliminating-ls/"><u>Advanced Tactics for Superior Windows Navigation: Eliminating LS</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/an-in-depth-look-at-the-lenovo-ideapad-combining-essential-features-with-a-pleasant-design/"><u>An In-Depth Look at the Lenovo Ideapad: Combining Essential Features with a Pleasant Design</u></a></li>
<li><a href="https://win11-tips.techidaily.com/are-some-websites-not-opening-in-any-browser-on-windows-7-ways-to-fix-it/"><u>Are Some Websites Not Opening in Any Browser on Windows? 7 Ways to Fix It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-system-management-via-cmd/"><u>Boost Your System Management via CMD</u></a></li>
<li><a href="https://screen-recording.techidaily.com/easy-video-calls-with-googles-hangouts-on-your-android-for-2024/"><u>Easy Video Calls with Google's Hangouts on Your Android for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-sign-xlb-document-with-digital-signature-tutorial-by-ldigisigner-sign-a-excel-sign-a-excel/"><u>How to Sign .xlb document with Digital Signature - (Tutorial)</u></a></li>
<li><a href="https://games-able.techidaily.com/reviving-invalid-payment-methods-on-ps5/"><u>Reviving Invalid Payment Methods on PS5</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/unhappy-with-windows-10-photos-here-are-8-better-options/"><u>Unhappy with Windows 10 Photos? Here Are 8 Better Options</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-unlocking-audio-content-effective-strategies-for-transferring-podcast-episodes-onto-computers/"><u>Updated Unlocking Audio Content Effective Strategies for Transferring Podcast Episodes Onto Computers</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    