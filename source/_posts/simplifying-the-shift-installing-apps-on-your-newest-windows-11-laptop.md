---
title: "Simplifying the Shift: Installing Apps on Your Newest Windows 11 Laptop"
date: 2024-11-06T12:23:21.351Z
updated: 2024-11-07T12:05:44.803Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Simplifying the Shift: Installing Apps on Your Newest Windows 11 Laptop"
excerpt: "This Article Describes Simplifying the Shift: Installing Apps on Your Newest Windows 11 Laptop"
keywords: Windows 11 App Setup,Easy Win11 App,Windows App Installs,New Win11 Installation,Simplified Win11 Laptops,Win11 App Addition,Laptop App Setup Win11
thumbnail: https://thmb.techidaily.com/24c0edcba484cab644836ae0bb31bb9d7220262ab1b4fd8d660fcbd9d1d07966.jpg
---

## Simplifying the Shift: Installing Apps on Your Newest Windows 11 Laptop

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
<a href="https://appsumo.8odi.net/c/5597632/2094414/7443" target="_top" id="2094414">
  <img src="//a.impactradius-go.com/display-ad/7443-2094414" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094414/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1983539">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983539.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983539">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983539.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983539%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983539/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886015/19272" target="_top" id="1886015">
  <img src="//a.impactradius-go.com/display-ad/19272-1886015" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886015/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## What About Any Left Out Apps?

 Even after using both methods, some apps will still be left out. It is because Microsoft Account sign-in only brings back Windows settings and Microsoft Store apps. The winget export file can restore only the apps listed in its official repository.

 As such, you still need to download the programs that aren’t included in both of these methods. But it will be a very short list compared to the effort you would have to put in if you just performed a normal installation.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151868/7443" target="_top" id="2151868">
  <img src="//a.impactradius-go.com/display-ad/7443-2151868" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151868/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Save Time When Setting Up Windows 11

 Make sure to enable files, apps, and preferences backup on your PC and create a winget export file beforehand. After you have both these backups in place, you can begin reinstalling Windows 11 on a different PC or reinstalling on the same PC.

 But what if you could eliminate the hours spent in finding and installing every single app, and configuring every setting? We will discuss two methods to effortlessly migrate most of your old apps to your new PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-boosting-youtube-income-using-studio-anywhere-anyhow-for-2024/"><u>[New] Boosting YouTube Income Using Studio Anywhere, Anyhow for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-from-humble-beginnings-to-prodigy-carryminatis-earnings-ajey/"><u>[Updated] From Humble Beginnings to Prodigy CarryMinati's Earnings (Ajey)</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-the-ultimate-guide-to-finding-free-westeros-ringtones/"><u>2024 Approved The Ultimate Guide to Finding Free Westeros Ringtones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-center-conquest-windows-high-rank-entry/"><u>Command Center Conquest: Windows High-Rank Entry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/devhomes-role-in-crafting-the-future-of-w11-interface/"><u>DevHome's Role in Crafting the Future of W11 Interface</u></a></li>
<li><a href="https://hardware-help.techidaily.com/enhance-productivity-connect-two-displays-to-your-m3-macbook-pro-tips-and-tricks-for-a-smooth-setup/"><u>Enhance Productivity: Connect Two Displays to Your M3 MacBook Pro - Tips and Tricks for a Smooth Setup</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-enable-usb-debugging-on-a-locked-meizu-21-phone-by-drfone-android/"><u>How To Enable USB Debugging on a Locked Meizu 21 Phone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-pc-screen-to-realme-c67-4g-phones-drfone-by-drfone-android/"><u>How to Mirror PC Screen to Realme C67 4G Phones? | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-expert-advice-on-flawless-ipad-screen-captures/"><u>In 2024, Expert Advice on Flawless iPad Screen Captures</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-tecno-spark-10c-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Tecno Spark 10C to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-10-itel-a60-android-sim-unlock-apk-by-drfone-android/"><u>In 2024, Top 10 Itel A60 Android SIM Unlock APK</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-windows-software-on-macos-platform/"><u>Leveraging Windows Software on macOS Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-insufficient-permissions-in-win-setup-procedures/"><u>Mitigating Insufficient Permissions in Win Setup Procedures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-disk-space-with-windows-compression/"><u>Optimize Disk Space with Windows Compression</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-0x800704b3-network-error-on-windows/"><u>Overcoming the 0X800704B3 Network Error on Windows</u></a></li>
<li><a href="https://discover-awesome.techidaily.com/premiere-pro-202n-crashes-resolved-fix-your-hanging-issues-now/"><u>Premiere Pro 202N Crashes Resolved - Fix Your Hanging Issues Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-enhanced-alerts-full-charge-on-winos/"><u>Strategies for Enhanced Alerts: Full Charge on WINOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-handbook-for-windows-startup-tweaks/"><u>The Ultimate Handbook for Windows Startup Tweaks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-secrets-to-banish-windows-pink-screens/"><u>Unveiling Secrets to Banish Windows Pink Screens</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    