---
title: Troubleshooting 'App Not Certified by Microsoft' On PC
date: 2024-06-25T17:01:17.984Z
updated: 2024-06-26T17:01:17.984Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting 'App Not Certified by Microsoft' On PC
excerpt: This Article Describes Troubleshooting 'App Not Certified by Microsoft' On PC
keywords: App Certification Issues,Fix Uncertified Apps,Troubleshoot MS Error,Resolve Non-Certified App,Unlicensed Windows Program,Microsoft License Conflict,PC Compatibility Problems
thumbnail: https://thmb.techidaily.com/5648c434c12cbf88b15506d6d23b8724252689511d16fa18d7a28833e2a6d9c5.jpg
---

## Troubleshooting 'App Not Certified by Microsoft' On PC

 Have you encountered the error"the app you're trying to install isn't a Microsoft-verified app"while installing an app? The error occurs if you have configured your system to only install apps from the Microsoft Store. You could have set this permission on purpose, or it might have been set by default.

 Other than that, a corrupted Microsoft Store cache, installing an app from an unofficial source, and enabling Windows S mode can also cause the error. Below, you will find a few checks and fixes you should apply to resolve the error and install the app successfully.

## 1\. Install the App From the Microsoft Store

 Considering you get the error when downloading apps outside the Microsoft Store, it makes sense to first check if the same app is available there. If the app is available, you can download it from there, and there won't be any need to go through advanced troubleshooting.

 Therefore, [open the Microsoft Store](https://www.makeuseof.com/windows-open-microsoft-store/) and search for the app. If you find the app in the store, click the **Get** button to install it. However, if the app isn't available in the store and can only be downloaded from another source, ensure it is safe to download.

## 2\. Make Sure the App You're Downloading Is Safe

 Microsoft doesn't allow untrusted publishers to list their apps on the Microsoft Store. If you haven't found the app on the store, it could be unsafe and infect your computer. Thus, ensure that the app you want to download is secure before downloading.

 To determine if an app is safe, copy its download link and paste it into [VirusTotal's URL search box](https://www.virustotal.com/gui/home/url). After that, press **Enter**.

![Check the Authenticity of a Software by Entering its URL in VirusTotal’s Official Website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/1-check-the-authenticity-of-a-software-by-entering-its-url-in-virustotal-s-official-website.jpg)

 If the scanner doesn't find any problems with the download link, it's probably safe. After ensuring that, you can apply the remaining fixes to enable app installation outside the store.

## 3\. Change the Operating System App Settings

 Microsoft cares about the safety and security of its Windows users. To facilitate that, Windows offers a feature that blocks the installation of apps outside the Microsoft Store. The downside of enabling this feature is that it prevents users from installing popular and safe applications from the web.

 When users try to install an app with this restriction turned on, Windows will likely display an error message saying that the app isn't a Microsoft-verified app. Therefore, to avoid encountering the error described above, you should allow Windows to install apps outside the Microsoft Store.

 To modify the app permissions on Windows 10, follow the steps below:

1. Open the **Settings** app.
2. Open **Apps** settings and select **Apps and Features** from the left sidebar.
3. Select **Anywhere** from the dropdown menu under **Choose where to get apps**.

 To modify app permissions on Windows 11, open the **Settings** app, select the **Apps** tab, and then go to **Advanced app settings**.

![Go to Advanced Apps Settings in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/2-go-to-advanced-apps-settings-in-windows-settings-app.jpg)

 Select **Anywhere** from the dropdown menu next to **Choose where to get apps**.

![Select Anywhere From the Dropdown Menu Next to Choose Where to Get Apps Option in Apps Settings in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/3-select-anywhere-from-the-dropdown-menu-next-to-choose-where-to-get-apps-option-in-apps-settings-in-windows-settings-app.jpg)

## 4\. Turn Off the App Install Control Policy

 The App Install Control is a Microsoft Defender SmartScreen feature that prevents users from installing apps outside the Microsoft Store. It does this to prevent users from infecting their devices with third-party applications.

 Therefore, you should turn off this feature to remove any restrictions. To turn it off, follow these steps:

1. Open the Local Group Policy Editor. To do this, check out [how to open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) if you're not using Windows Home edition, and learn [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) if you are.
2. Navigate to **Computer Configuration > Administrative Templates > Windows Components > Windows Defender SmartScreen > Explorer**.  
![Go to Explorer Folder by Navigating to the Path in Windows Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/4-go-to-explorer-folder-by-navigating-to-the-path-in-windows-local-group-policy-editor.jpg)
3. Open the policy for **Configure App Install Control**.
4. Select **Disabled** to turn off this feature.  
![Disable the Policy for Configure App Install Control in Windows Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/5-disable-the-policy-for-configure-app-install-control-in-windows-local-group-policy-editor.jpg)

## 5\. Change the App Install Control Permission in the Registry Editor

 To modify the App Install Control permissions via the Registry Editor, follow the below steps:

1. Open the Registry Editor.
2. Navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer**.  
![Go to Explorer Folder by Navigating to the Path in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/6-go-to-explorer-folder-by-navigating-to-the-path-in-windows-registry-editor.jpg)
3. Right-click on **Explorer** and select **New > String value**.  
![Create New String Value in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/7-create-new-string-value-in-windows-registry-editor.jpg)
4. Name this new value **"AicEnabled."**  
![Name the Newly Created String Value AicEnabled in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/8-name-the-newly-created-string-value-aicenabled-in-windows-registry-editor.jpg)
5. Double-click on the newly created string and type "**Anywhere"** in the **Value data** field.  
![Type Anywhere in the Value Data Field of Newly Created String in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/9-type-anywhere-in-the-value-data-field-of-newly-created-string-in-windows-registry-editor.jpg)
6. Restart the computer for the changes to take effect.

 If the above Registry tweak does not resolve the issue, turn off S mode.

## 6\. Disable Windows S Mode

 Windows S mode is primarily the most secure environment you can get in Windows. It mainly serves as a means of protecting your children and keeping sensitive documents away from prying eyes.

 When this mode is active, users can only download apps from the Microsoft Store, can't use the command line or code editors, and can't modify the Windows Registry Editor.

 Therefore, if you have recently bought a new device and this mode is enabled there by default, Windows will probably throw the error if you attempt to install any app outside the store. Therefore, you should make sure it isn't enabled and disable it if it is.

 To determine whether your device is running S mode, open the **Settings** app, select the **System** tab on the left, and open the **About** page.

 If the S mode is enabled on your device, you'll see it there. If the feature is active, turn it off by following these steps:

1. Open the **Settings** app.
2. Navigate to the **System** tab and go to **Activation**.
3. Click on **Go to the store** under **Switch to Windows 11 Home/Pro**, which will take you to the Microsoft Store page where you can opt out of S mode.
4. Click the **Get** button and follow the on-screen instructions to get out of S mode.

## 7\. Run the Windows Store Apps Troubleshooter

 If the Windows S mode isn't enabled, and you haven't restricted your operating system from downloading apps from outside Microsoft, the error could be caused by an underlying issue with the Microsoft Store. To ensure this is not the case, you should run the Windows Store Apps troubleshooter, which is a built-in tool for troubleshooting issues with the Store.

 If you've never run the troubleshooter before, refer to our guide on [how to run a troubleshooter on Windows 10 or 11](https://www.makeuseof.com/run-troubleshooter-windows-10-11/).

## Successfully Install Third-Party Applications Again on Windows

 Microsoft blocks the installation of third-party apps for your security, but it's pointless if it prevents you from installing vital apps. Hopefully, you now better understand why the Microsoft Store presents the "the app you're trying to install isn't a Microsoft-verified app" error. Following the fixes above will enable you to download the apps from unofficial sources.

 Have you encountered the error"the app you're trying to install isn't a Microsoft-verified app"while installing an app? The error occurs if you have configured your system to only install apps from the Microsoft Store. You could have set this permission on purpose, or it might have been set by default.

 Other than that, a corrupted Microsoft Store cache, installing an app from an unofficial source, and enabling Windows S mode can also cause the error. Below, you will find a few checks and fixes you should apply to resolve the error and install the app successfully.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/upgrade-the-antiquity-embellishing-old-games-with-retroarch-awards/"><u>Upgrade the Antiquity - Embellishing Old Games With Retroarch Awards</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-mouse-movement-how-to-stop-acceleration/"><u>Master Your Mouse Movement: How to Stop Acceleration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-unsuccessful-nvidia-connect-attempts-in-windows-11/"><u>Resolving Unsuccessful Nvidia Connect Attempts in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-11-the-8-most-common-mistakes-for-beginners-to-skip/"><u>Navigating Windows 11: The 8 Most Common Mistakes for Beginners to Skip</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-missing-5ghz-network-on-windows-11-top-7-solutions/"><u>Troubleshoot Missing 5GHz Network on Windows 11: Top 7 Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-correct-xbox-mic-issues-in-os/"><u>Guidelines to Correct Xbox Mic Issues in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/your-ultimate-toolkit-to-counteract-bsod-on-win10/"><u>Your Ultimate Toolkit to Counteract BSOD on Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-strategies-against-locked-out-windows-pin/"><u>Immediate Strategies Against Locked-Out Windows PIN</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-samsung-galaxy-a05-phone-forgot-password-by-drfone-android-unlock-android-unlock/"><u>How to Unlock Samsung Galaxy A05 Phone Forgot Password</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/leveraging-youtubes-cc-options-for-video-production/"><u>Leveraging YouTube's CC Options for Video Production</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-best-auto-tracking-camera-mount/"><u>In 2024, Best Auto Tracking Camera Mount</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-easy-cartoon-making-top-10-online-and-offline-solutions/"><u>New In 2024, Easy Cartoon Making Top 10 Online and Offline Solutions</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-expanding-reach-fb-live-on-broadcast-networks-for-2024/"><u>[Updated] Expanding Reach  FB Live on Broadcast Networks for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-decoding-the-visual-language-of-live-videos-on-youtube/"><u>[New] In 2024, Decoding the Visual Language of Live Videos on YouTube</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unboxing-unveiled-enhancing-customer-experiences/"><u>2024 Approved  Unboxing Unveiled  Enhancing Customer Experiences</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-guide-to-structuring-youtube-content-with-separate-chapters/"><u>In 2024, Guide to Structuring YouTube Content with Separate Chapters</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-direct-from-mobile-how-to-upload-videos-on-twit/"><u>[Updated] Direct From Mobile  How to Upload Videos on Twit</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>