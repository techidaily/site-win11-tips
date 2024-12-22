---
title: Uninstalling and Reinstalling Troubled Apps in Windows
date: 2024-12-17T20:20:49.415Z
updated: 2024-12-22T01:00:53.819Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Uninstalling and Reinstalling Troubled Apps in Windows
excerpt: This Article Describes Uninstalling and Reinstalling Troubled Apps in Windows
keywords: Uninstall Apps Windows,Reinstall Faulty Apps,Fix Apps Issues PC,Cleanup Windows Apps,Removing App Errors,Restore App Settings,Repairing Apps Problems
thumbnail: https://thmb.techidaily.com/e7f1cad7a399e71169efcdbd386bd0d5b12f456c3f589c4c694fba40159c8b6c.jpg
---

## Uninstalling and Reinstalling Troubled Apps in Windows

 Have you encountered the error"the app you're trying to install isn't a Microsoft-verified app"while installing an app? The error occurs if you have configured your system to only install apps from the Microsoft Store. You could have set this permission on purpose, or it might have been set by default.

 Other than that, a corrupted Microsoft Store cache, installing an app from an unofficial source, and enabling Windows S mode can also cause the error. Below, you will find a few checks and fixes you should apply to resolve the error and install the app successfully.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YwOwUI47FuU?si=NK7IEELjx7_SJSl2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Install the App From the Microsoft Store

 Considering you get the error when downloading apps outside the Microsoft Store, it makes sense to first check if the same app is available there. If the app is available, you can download it from there, and there won't be any need to go through advanced troubleshooting.

 Therefore, [open the Microsoft Store](https://www.makeuseof.com/windows-open-microsoft-store/) and search for the app. If you find the app in the store, click the **Get** button to install it. However, if the app isn't available in the store and can only be downloaded from another source, ensure it is safe to download.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NC0rdKEQ98o?si=HYgqC8CxF_WTO5if" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AQn0MYjIfyI?si=rIdjT-qMRpjpJXXa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Turn Off the App Install Control Policy

 The App Install Control is a Microsoft Defender SmartScreen feature that prevents users from installing apps outside the Microsoft Store. It does this to prevent users from infecting their devices with third-party applications.

 Therefore, you should turn off this feature to remove any restrictions. To turn it off, follow these steps:

1. Open the Local Group Policy Editor. To do this, check out[how to open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) if you're not using Windows Home edition, and learn [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) if you are.
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8Y-k_3N-0OI?si=1J-aFBXLJl5b3x4h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Type Anywhere in the Value Data Field of Newly Created String in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/9-type-anywhere-in-the-value-data-field-of-newly-created-string-in-windows-registry-editor.jpg)
6. Restart the computer for the changes to take effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the above Registry tweak does not resolve the issue, turn off S mode.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DEqoiNArwjQ?si=oaL_lgnI-RxY5Qy_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://visual-screen-recording.techidaily.com/updated-hurdlehop-pausevidsnapshot/"><u>[Updated] HurdleHop PauseVidSnapshot</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-unlocking-secrets-of-sending-mmc-films-to-vimeo/"><u>[Updated] Unlocking Secrets of Sending MMC Films to Vimeo</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-mastering-ios-the-secrets-of-screen-casts/"><u>2024 Approved Mastering iOS The Secrets of Screen Casts</u></a></li>
<li><a href="https://android-frp.techidaily.com/5-quick-methods-to-bypass-nokia-c12-pro-frp-by-drfone-android/"><u>5 Quick Methods to Bypass Nokia C12 Pro FRP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-efficiency-the-best-productivity-apps-for-win-11/"><u>Elevate Your Efficiency: The Best Productivity Apps for Win 11</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/expert-reviews-the-best-software-for-mending-broken-pixels-and-reviving-faded-memories/"><u>Expert Reviews: The Best Software for Mending Broken Pixels & Reviving Faded Memories</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/hp-victus-15-laptop-now-discounted-by-350-at-best-buy-exclusive-labor-day-sale-offer-on-zdnet/"><u>HP Victus 15 Laptop Now Discounted by $350 at Best Buy: Exclusive Labor Day Sale Offer on ZDNet</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-honor-x50i-device-by-drfone-android/"><u>In 2024, The Ultimate Guide How to Bypass Swipe Screen to Unlock on Honor X50i Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-driver-verifier-on-windows-11/"><u>Launching Driver Verifier on Windows 11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/live-streaming-mastery-top-features-of-manycams-video-enhancement-suite/"><u>Live Streaming Mastery: Top Features of ManyCam's Video Enhancement Suite</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/navigating-the-world-of-avis-to-gifs-with-help-from-filmora-for-2024/"><u>Navigating the World of AVIs to GIFs with Help From Filmora for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-the-pre-use-disk-formatting-mistake/"><u>Remedying the Pre-Use Disk Formatting Mistake</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sketch-success-unlocking-windows-desktop-designs/"><u>Sketch Success: Unlocking Windows Desktop Designs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-christmas-prep-for-windows-11/"><u>The Ultimate Christmas Prep for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-video-encoders-for-windows-users-explained/"><u>Top Video Encoders for Windows Users Explained</u></a></li>
</ul></div>

