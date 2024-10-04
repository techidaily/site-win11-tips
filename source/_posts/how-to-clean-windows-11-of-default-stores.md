---
title: How to Clean Windows 11 of Default Stores
date: 2024-09-27T20:59:17.089Z
updated: 2024-10-03T19:30:00.029Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Clean Windows 11 of Default Stores
excerpt: This Article Describes How to Clean Windows 11 of Default Stores
keywords: Window Cleaning Guide,Remove Default Apps,Clearing Win11 Cache,Disable Store Redirect,Uninstall Windows Stores,Clean Windows 11,Eliminate Default Shops
thumbnail: https://thmb.techidaily.com/0e850e00d907836de022b6a5493d7e424fd91aacae9c4b818ed3e14b82d98585.jpg
---

## How to Clean Windows 11 of Default Stores

 Microsoft Store is the go-to place for Windows users if they want to install an app. The app library is slowly expanding, and you will find all the popular apps without any difficulty. But sometimes the Microsoft Store application behaves abnormally and requires troubleshooting.

 But what if it still doesn’t work, even after repairing and resetting? There is no uninstall option in the Settings app, so it is possible to uninstall Microsoft Store? Well, it is possible to remove and reinstall the Microsoft Store app. Here’s how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Should You Uninstall the Microsoft Store App?

 Microsoft Store houses all the useful and popular applications for Windows devices. Moreover, it guarantees safe and malware-free application downloads. But if the app fails to start or doesn’t work properly, removing it makes sense.

 But don’t worry. You can remove the app and then reinstall it if you want. Reinstallation can fix persistent issues with the current version of the Microsoft Store app. It will remove the current app installation and all its related files and corrupt data. After that, you can reinstall the Microsoft app with a single command.

## How to Uninstall Microsoft Store App From Windows 11

 You can remove the Microsoft Store app from Windows 11 using the winget tool and run it using the command prompt. In addition, you can use the PowerShell cmdlet to remove the Microsoft Store application package from your system or use a batch file.

### 1\. Using Winget

 Winget is a handy Windows package manager tool available with the newer releases of Windows 10 and 11\. It makes it ridiculously easy to search and manage applications on your system. You can use it to remove any application, even the Microsoft Store app from your system. Here’s how:

1. Press the**Win + R** key to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** and press the**Ctrl + Shift + Enter** keys to launch the Command Prompt with administrator privileges.
2. Now, we need to locate the ID of the Microsoft Store app installed on the system. Type the following command in the command prompt window and press the enter key:**Winget list Store**
3. Winget will list all the installed programs on your system containing the string “store” in their name. Find the Microsoft Store app in the list and**copy** its**ID** .
4. After that, you need to run the uninstall command using winget. The syntax is**winget uninstall \[app ID\]** . So, the command will be:  
winget uninstall Microsoft.WindowsStore_8wekyb3d8bb
5. Press enter to execute the command and wait for it to execute successfully.  
![Uninstall Microsoft Store App using winget](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-winget.jpg)
6. Type**exit** in the command prompt window and press enter to close it.

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2141684/17092" target="_top" id="2141684">
  <img src="//a.impactradius-go.com/display-ad/17092-2141684" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettide.pxf.io/i/5597632/2141684/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<span id="1982485">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982485.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982485">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982485.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982485%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982485/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Using PowerShell

 Before winget was officially integrated into Windows 10 and 11, there was a method to[remove the Microsoft Store app using PowerShell](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) . The method still works and all you need to do is list the package name and then use the**Remove-AppxPackage** cmdlet to uninstall the Microsoft Store app from your system. Make sure to run PowerShell with elevated permissions.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144310/7443" target="_top" id="2144310">
  <img src="//a.impactradius-go.com/display-ad/7443-2144310" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144310/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 3\. Using a Batch File

 If you want to save the hassle of typing commands every time you want to uninstall the Microsoft Store app, you can use a batch file. It will help you to remove Microsoft Store app from your system in a couple of clicks whenever the normal troubleshooting methods don’t work for you. Repeat the following steps:

1. Press**Win + D** to switch to the Desktop. Right-click on the Desktop and select the**New > Text Document** option.
2. Open the newly created text document file on the desktop. A Notepad window will pop up. Paste the following text in it:  
@echo off winget uninstall "Microsoft Store" exit
3. Now, press**Ctrl + Shift + S** to open the "Save as" window. Name the batch file as**UninstallStore.bat** and keep the**Save as** type option as**All files** .  
![Uninstall Microsoft Store App using batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-batch-file.jpg)
4. Click on the**Save** button. Close the Notepad window.
5. Press**Win + D** to switch to the desktop again. Right-click on the batch file and select the**Run as administrator** option from the context menu.
6. A command prompt window will open, run the Microsoft Store app uninstallation command, and close automatically. You don’t need to interact with the window.
7. Open the Start menu and search for Microsoft Store. You won’t find any matching app on your system.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918679/19272" target="_top" id="1918679">
  <img src="//a.impactradius-go.com/display-ad/19272-1918679" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918679/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Easily Remove the Microsoft Store From Windows

 Windows 10 and 11 don’t offer an option to uninstall Microsoft Store. So, you are only left at the mercy of a system restore or reset. However, you can now uninstall the Microsoft Store app from your system using any of the three methods mentioned above. You can also reinstall it using the PowerShell cmdlet and continue using the app again.

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
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-from-in-the-moment-to-lasting-images-how-to-save-from-snapchat/"><u>[New] In 2024, From In-the-Moment to Lasting Images How to Save From Snapchat</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-fixing-muted-audio-and-video-transmission-errors-on-fb-messengers-mobile-app/"><u>2024 Approved Fixing Muted Audio & Video Transmission Errors on FB Messengers Mobile App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/designating-menu-triggers-for-software-patch-alerts/"><u>Designating Menu Triggers for Software Patch Alerts</u></a></li>
<li><a href="https://technical-tips.techidaily.com/detailed-instructions-for-fixing-missing-d3dx926dll-in-your-system/"><u>Detailed Instructions for Fixing Missing d3dx9_26.dll in Your System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-the-diversity-of-windows-n-versions/"><u>Dissecting the Diversity of Windows N Versions</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-did-the-netflix-mail-order-rentals-shape-todays-entertainment-landsume/"><u>How Did the Netflix Mail Order Rentals Shape Today’s Entertainment Landsume?</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-samsung-galaxy-s23-phone-without-pin-by-drfone-android/"><u>How to Unlock Samsung Galaxy S23 Phone without PIN</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-ispoofer-is-not-working-on-nokia-g310-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, iSpoofer is not working On Nokia G310? Fixed | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-software-removal-windows-11-edition-143-chars/"><u>Navigating SoftWare Removal: Windows 11 Edition (143 Chars)</u></a></li>
<li><a href="https://change-location.techidaily.com/pokemon-go-error-12-failed-to-detect-location-on-vivo-x-fold-2-drfone-by-drfone-virtual-android/"><u>Pokemon Go Error 12 Failed to Detect Location On Vivo X Fold 2? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proven-approaches-for-effective-windows-file-browsing-sans-ls/"><u>Proven Approaches for Effective Windows File Browsing Sans LS</u></a></li>
<li><a href="https://win-able.techidaily.com/troubleshooting-common-bugs-in-phasmophobia-updates-and-fixes-for-the-new-year/"><u>Troubleshooting Common Bugs in Phasmophobia: Updates and Fixes for the New Year</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-secret-search-mechanism-of-windows-11/"><u>Unlock Secret Search Mechanism of Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-secrets-quick-fixed-for-11-windows-issues/"><u>Unveiling Secrets: Quick Fixed for 11 Windows Issues</u></a></li>
</ul></div>

