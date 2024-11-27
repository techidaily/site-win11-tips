---
title: "The Ultimate Guide: Embedding Old Apps Into the Latest Windows 11"
date: 2024-11-23T16:48:03.657Z
updated: 2024-11-27T16:55:44.337Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes The Ultimate Guide: Embedding Old Apps Into the Latest Windows 11"
excerpt: "This Article Describes The Ultimate Guide: Embedding Old Apps Into the Latest Windows 11"
keywords: Windows 11 App Embedding,Upgrading Apps to Windows 11,Guide to Older App Compatibility,Integrating Classic Windows Programs,Latest OS App Adaptation,Win11 for Legacy Software,Embedding Vintage Windows Apps
thumbnail: https://thmb.techidaily.com/4d762caa04f98755e083fa6f19084871af3024b44e5497cff1919865c9f50ec3.jpg
---

## The Ultimate Guide: Embedding Old Apps Into the Latest Windows 11

 Setting up Windows 11 on your PC, or another PC is a laborious task. After installing the operating system and the OEM drivers, there is still a lot of work left. You need to reconfigure your system settings, re-download, and install all the Microsoft Store apps. Along with that, you need to individually download and install each third-party software, which makes it more challenging.

 But what if you could eliminate the hours spent in finding and installing every single app, and configuring every setting? We will discuss two methods to effortlessly migrate most of your old apps to your new PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eu4vwlZcMvM?si=4vEczfVU4BUUFP-t&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Using Microsoft Account

 If you used a Microsoft account on your old PC, Windows 11 offers multiple options to back up your App list, Preferences, and use OneDrive for personal files. To do that, you must enable [OneDrive](https://www.makeuseof.com/what-is-onedrive/)and back up all your personal files and folders to it. It will only take care of the files part but the apps and preferences are still left. But you must also enable the backup of these two things on your old PC before [reinstalling Windows 11](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/) or migrating to a new PC.

 Repeat the following steps to enable apps and settings backup:

1. Press **Win + I** to launch the Settings app. Navigate to **Accounts > Windows backup** section.
2. Go to the **Remember my apps** option and click on the toggle next to it to enable the settings.
3. Next, click on the toggle next to **Remember my preferences** option to back up your settings as well.  
![Backup Apps and Preferences to Microsoft Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/backup-apps-and-preferences-to-microsoft-account.jpg)
4. You will notice that the top section of the Windows backup page will mark each of these features as “**backed up**”.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After you reinstall Windows 11, the OOBE page will ask you to [sign in with a Microsoft account](https://www.makeuseof.com/windows-switch-local-account-to-microsoft-account/). Enter your credentials, and you will see a “Welcome back, User!” message with an option to restore all apps, settings, and files present on your previous machine. Click on the **Next** button and proceed setup up your new PC

![Install Old Apps Using Microsoft Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-old-apps-using-microsoft-account.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 As soon as you boot to the desktop, you will see a popup that Windows is trying to restore the most used apps from before. It will ask you to open Microsoft Store to restore additional apps from your old PC. Click on the **Restore my apps** button.

![Install Old Apps Using Microsoft Account 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-old-apps-using-microsoft-account-2.jpg)

 Microsoft Store will display all the remaining apps available for restoration. Click on the **Restore All** button if you want to bring back every app. Wait for the apps to install and then close Microsoft Store.

![Install Old Apps Using Microsoft Account 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-old-apps-using-microsoft-account-3.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kiW7sLvL65k?si=IHSeRFsYCrfqpn2o&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/aoMiYpYiFZs?si=qvYvGytDD17fvSXO&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What About Any Left Out Apps?

 Even after using both methods, some apps will still be left out. It is because Microsoft Account sign-in only brings back Windows settings and Microsoft Store apps. The winget export file can restore only the apps listed in its official repository.

 As such, you still need to download the programs that aren’t included in both of these methods. But it will be a very short list compared to the effort you would have to put in if you just performed a normal installation.

## Save Time When Setting Up Windows 11

 Make sure to enable files, apps, and preferences backup on your PC and create a winget export file beforehand. After you have both these backups in place, you can begin reinstalling Windows 11 on a different PC or reinstalling on the same PC.

 But what if you could eliminate the hours spent in finding and installing every single app, and configuring every setting? We will discuss two methods to effortlessly migrate most of your old apps to your new PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-recording.techidaily.com/new-enhancing-engagement-with-dynamic-360-videos-on-facebook/"><u>[New] Enhancing Engagement with Dynamic 360 Videos on Facebook</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-in-2024-flipping-photo-lightness-for-an-alternate-look/"><u>[New] In 2024, Flipping Photo Lightness for an Alternate Look</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-securing-brand-deals-with-youtube-personalities/"><u>[New] Securing Brand Deals with YouTube Personalities</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-next-gen-gameplay-logging-alternatives-to-fbx/"><u>[Updated] 2024 Approved Next-Gen Gameplay Logging Alternatives to FBX</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-windows-11-tips-for-effective-sound-recording/"><u>[Updated] 2024 Approved Windows 11 Tips for Effective Sound Recording</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/a-perfect-guide-to-remove-or-disable-google-smart-lock-on-realme-narzo-60x-5g-by-drfone-android/"><u>A Perfect Guide To Remove or Disable Google Smart Lock On Realme Narzo 60x 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-ideal-screen-dimensions-win11s-guide/"><u>Configuring Ideal Screen Dimensions: Win11's Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-windows-pink-screen-errors/"><u>Eliminating Windows Pink Screen Errors</u></a></li>
<li><a href="https://fox-glue.techidaily.com/from-frustration-to-finishing-how-magix-vpx-saves-time-for-2024/"><u>From Frustration to Finishing How Magix VPX Saves Time for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-bypassing-google-account-with-vnrom-bypass-for-samsung-galaxy-s24-ultra-by-drfone-android/"><u>In 2024, Bypassing Google Account With vnROM Bypass For Samsung Galaxy S24 Ultra</u></a></li>
<li><a href="https://win11-tips.techidaily.com/open-sticky-notes-in-windows-11-with-precision/"><u>Open Sticky Notes in Windows 11 with Precision</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-server-access-denial-windows-wise/"><u>Overcoming Server Access Denial Windows-Wise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-resolving-isdonedll-problems-in-w10w11/"><u>Quick Guide to Resolving ISDone.dll Problems in W10/W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simple-and-slim-revamp-with-windows-11-tiny/"><u>Simple & Slim: Revamp with Windows 11 Tiny</u></a></li>
<li><a href="https://win11-tips.techidaily.com/supercharge-hardware-interactions-discover-4-windows-11-disk-management-actions/"><u>Supercharge Hardware Interactions: Discover 4 Windows 11 Disk Management Actions</u></a></li>
<li><a href="https://some-approaches.techidaily.com/windows-1087-cd/"><u>Windows 10/8/7용 자원 없이 CD를 굽는 효율적인 소품 - 무료 대여 제안</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winerror-0xc0000005-a-comprehensible-solution-manual/"><u>WinError 0xC0000005: A Comprehensible Solution Manual</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    