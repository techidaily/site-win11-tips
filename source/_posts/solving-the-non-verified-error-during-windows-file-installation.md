---
title: Solving the Non-Verified Error During Windows File Installation
date: 2024-06-25T16:09:03.930Z
updated: 2024-06-26T16:09:03.930Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solving the Non-Verified Error During Windows File Installation
excerpt: This Article Describes Solving the Non-Verified Error During Windows File Installation
keywords: Fixing Windows Install Failures,Resolve Unverified Files Error,Stop Windows Install Trouble,Eliminate Verification Issue,Solve PC File Errors,Correct Non-Verified Windows Error,Prevent Installation Hiccups
thumbnail: https://thmb.techidaily.com/4be59755ae7994bb626513b3614a3ec947be3b56430323187fb64d462d24a601.jpg
---

## Solving the Non-Verified Error During Windows File Installation

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
<li><a href="https://win11-tips.techidaily.com/recommended-procedures-for-dying-wireless-controller/"><u>Recommended Procedures for Dying Wireless Controller</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-find-and-purge-unused-windows-folders-for-a-streamlined-pc/"><u>Efficiently Find & Purge Unused Windows Folders for a Streamlined PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/vcplusplus-redistribution-purpose-explored/"><u>VC++ Redistribution Purpose Explored</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-through-windows-update-obstacles-with-error-code-0x800736cc/"><u>Breaking Through Windows Update Obstacles with Error Code 0X800736CC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/repairing-windows-camera-failure-on-photovideo-saving/"><u>Repairing Windows Camera Failure on Photo/Video Saving</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-double-click-with-these-simple-windows-adjustments/"><u>Optimize Your Double-Click with These Simple Windows Adjustments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delving-into-upcoming-changes-with-windows-11-version-22h2/"><u>Delving Into Upcoming Changes with Windows 11 Version 22H2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-windows-11s-0x800f0922-error-quick-fixed-guide/"><u>Solving Windows 11'S 0X800F0922 Error - Quick Fixed Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-barriers-editing-your-win11-fax-pages-with-ease/"><u>Breaking Down Barriers: Editing Your Win11 Fax Pages with Ease</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-the-soft-bricked-oppo-f25-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix the Soft Bricked Oppo F25 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-employing-inbuilt-screen-recording-tools-on-mate-p-models-p20-p10/"><u>[New] In 2024, Employing Inbuilt Screen Recording Tools on Mate, P Models (P20, P10)</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-ratio-revelation-uncovering-the-secrets-of-pixel-calculations/"><u>Updated Ratio Revelation Uncovering the Secrets of Pixel Calculations</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-make-your-gaming-great-not-stressful/"><u>[New] In 2024, Make Your Gaming Great, Not Stressful</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-top-10-password-cracking-tools-for-xiaomi-redmi-k70e-by-drfone-android/"><u>In 2024, Top 10 Password Cracking Tools For Xiaomi Redmi K70E</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-tactics-for-trending-on-instagram-designing-dynamic-puzzles/"><u>[Updated] In 2024, Tactics for Trending on Instagram  Designing Dynamic Puzzles</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/influencers-insight-surging-up-by-a-thousand-on-ig-each-month/"><u>Influencer's Insight  Surging up by a Thousand on IG Each Month</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-deleted-nokia-c210-pictures-an-easy-method-explained-by-fonelab-android-recover-pictures/"><u>How to Restore Deleted Nokia C210 Pictures  An Easy Method Explained.</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-unbeatable-windows-chat-providers-3-1-ranked/"><u>[New] 2024 Approved  Unbeatable Windows Chat Providers, #3-#1 Ranked</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-tiktok-and-beyond-unveiling-the-best-books-for-todays-reader/"><u>[New] 2024 Approved  TikTok and Beyond  Unveiling the Best Books for Today's Reader</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>