---
title: Skip Unsolicited Advice and Tips on Microsoft Windows
date: 2024-10-21T22:56:29.046Z
updated: 2024-10-26T22:08:21.628Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Skip Unsolicited Advice and Tips on Microsoft Windows
excerpt: This Article Describes Skip Unsolicited Advice and Tips on Microsoft Windows
keywords: Skip Ads,Avoid Windows Tips,No Unwanted Guides,Eliminate PC Advice,Discard MS Windows Help,Block Pc Assistance,Dodge OS Tutorials
thumbnail: https://thmb.techidaily.com/e4dab8212b61415ab670db2724890039dc218886423e579644f1092e23638fe5.jpg
---

## Skip Unsolicited Advice and Tips on Microsoft Windows

 Are you tired of constantly seeing tips and suggestions on your computer screen? Want to mute them and concentrate on your work uninterrupted? Don’t worry - the process is quick and straightforward.

 In this article, we’ll discuss how to turn off or disable tips and suggestions notifications on Windows 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Turn Off or Disable Tips and Suggestions Notifications in Windows 11

 Tips and suggestions provide quick guides to Windows and its features. But if you find them annoying, you can turn them off. Here are two easy methods to turn off tips and suggestions notifications on Windows 11\.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934188/19272" target="_top" id="1934188">
  <img src="//a.impactradius-go.com/display-ad/19272-1934188" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934188/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 1\. How to Turn Off Tips and Suggestions Using System Settings

 To turn off tips and suggestions on your computer, you can use the System Settings. This is the easiest and quickest way to mute these notifications. Here's how to do it:

1. Press **Win + I** to open the Settings window.
2. From the left panel, click on the **System** tab.
3. In the System Settings sub-panel, click on the **Notifications** section.  
![Open System Notification Section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/open-system-notification-section.jpg)
4. Next, scroll down to the bottom and expand **Additional settings**.  

![Get tips and suggestions when using Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/get-tips-and-suggestions-when-using-windows.jpg)
5. You will see a checkbox labeled **Get tips and suggestions when using Windows**. Uncheck it to turn off this feature.

 Now, you will not see any tips and suggestions notifications on your computer. If later you wish to re-enable this feature, follow the same steps outlined above and check the "Get tips and suggestions when using Windows" checkbox. Doing this will enable tips and suggestions notifications on your computer.

### 2\. Turn Off Tips and Suggestions Using a REG File

 If the system setting is unresponsive, you can use a REG file instead. This procedure creates a REG file with the necessary commands. Although it may seem complex, it is actually quite simple.

 Here are the steps to follow:

1. [Open the Notepad application](https://www.makeuseof.com/windows-11-open-notepad/).
2. Copy and paste the following code into it:  
`Windows Registry Editor Version 5.00  

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\ContentDeliveryManager]  
"SubscribedContent-338389Enabled"=dword:00000000`
3. Now save the file with the **.reg** extension.
4. Double-click on the file you just created to open it, and click **Yes** in the confirmation dialog box that appears.

 This will turn off tips and suggestions notifications in Windows 11\. To enable these notifications once again, delete the file you just created. Alternatively, double-click on it and click **No** in the confirmation dialog.

## How to Disable Tips and Suggestions Notifications in Windows 11

 If you prefer to disable tips and suggestions notifications on your computer completely, there are several options available. You can utilize the Group Policy Editor, modify the registry editor, or create a REG file. Let's explore each method in detail to disable this feature.

### 1\. Disable Tips and Suggestions Notifications Using Group Policy Editor

 To turn off notifications for tips and suggestions, access the Group Policy Editor. This tool is available for Windows Pro, Education, and Enterprise users. However, it won't work if you use Windows Home Edition.

 In such cases, you must first [activate the Group Policy Editor for Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). Once done, follow the steps below to disable notifications for tips and suggestions:

1. Press **Win + R** to open the Run window.
2. Type **gpedit.msc** in the Run dialog box and press Enter. This will launch the Group Policy Editor window on your screen.
3. On the left side of the window, navigate to the following path:  
Computer Configuration > Administrative Templates > Windows Components > Cloud Content​
4. On the right side of the window, double-click on the **Do not show Windows tips** policy.  
![Do not Show Windows Tips](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/do-not-show-windows-tips.jpg)
5. From the box that appears, select the **Enabled** radio button.
6. Click **Apply** \> **OK** to save the changes.

 Now, tips and suggestions notifications will be completely disabled on your computer. To re-enable the feature, follow the same steps and select the **Not Configured** or **Disabled** radio button instead.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135357/19272" target="_top" id="2135357">
  <img src="//a.impactradius-go.com/display-ad/19272-2135357" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135357/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Disable Tips and Suggestions Notifications Using the Registry Editor

 If you can’t access the Group Policy Editor or activate it, you can modify the registry editor to disable these notifications. The procedure is slightly more technical and requires caution while making changes. It may even wreck your computer system, so proceed cautiously.

 To avoid risks, [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first. That way, you can restore the original settings if required. Once you have taken these precautionary steps, follow the instructions below to disable tips and suggestions notifications:

1. Press the **Windows** key to open the Start Menu.
2. Type **regedit** in the search box and select the **Registry Editor** app from the search results.
3. If the UAC window appears, click **Yes** to grant permission.
4. In the Registry Editor window, navigate to the following path:  
HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\CloudContent
5. If the **CloudContent** key is missing, create a new one. To do this, right-click on the Windows folder and select **New** \> **Key**. Name it **CloudContent**.
6. On the right side of the window, right-click on an empty area and select **New** \> **DWORD (32-bit) Value**.
7. Name the value **DisableSoftLanding** and hit Enter.  
![Disable Tips and Suggestions Notifications Using the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-tips-and-suggestions-notifications-using-the-registry-editor.jpg)
8. Double-click on this newly created entry and set its Value data to **1**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043594/7443" target="_top" id="2043594">
  <img src="//a.impactradius-go.com/display-ad/7443-2043594" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043594/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Click **OK** to save the changes. Now, exit the registry editor window and restart your computer.

 After restarting, tips and suggestions notifications will be disabled on your computer. If you want to enable the feature, follow the same steps and change the Value data to **0**.

### 3\. Disable Tips and Suggestions Notifications Using a REG File

 You can also create a REG file to turn off tips and suggestions notifications on your Windows PC. This method is quite similar to the one we discussed above. However, the process is easier for those with little experience editing registry files.

 To disable tips and suggestions notifications using a REG file, follow the steps outlined below:

1. Search for **Notepad** and select the result from the list.
2. Copy and paste the code below into the Notepad window.  
`Windows Registry Editor Version 5.00  

[HKEY_CURRENT_USER\Software\Policies\Microsoft\Windows\CloudContent]  
"DisableSoftLanding"=dword:00000001`
3. Save the file with the .reg extension. Make sure that the Save as type field is set to **All files**.
4. Now, double-click on the file and click **Yes** at the prompt.

 That’s it! Tips and suggestions feature is now disabled on your computer.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948949/19272" target="_top" id="1948949">
  <img src="//a.impactradius-go.com/display-ad/19272-1948949" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948949/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Stop the Windows Tips and Suggestions Notifications

 We hope that this article helped you understand how to turn off or disable tips and suggestions notifications in Windows 11\. All it takes are a few clicks or a simple REG file to enable or disable this feature.

 In this article, we’ll discuss how to turn off or disable tips and suggestions notifications on Windows 11\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-tips.techidaily.com/new-10-best-mobile-writing-tools-for-iosandroid-images/"><u>[New] 10 Best Mobile Writing Tools for iOS/Android Images</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-2024-approved-skys-best-the-ultimate-hd-collection-websites/"><u>[New] 2024 Approved Sky's Best - The Ultimate HD Collection Websites</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-how-frequent-uploads-can-skyro-cookie-sales-on-your-youtube-channel-for-2024/"><u>[New] How Frequent Uploads Can Skyro Cookie Sales on Your YouTube Channel for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-mastering-visual-narratives-essential-snapchat-video-editors-for-2024/"><u>[New] Mastering Visual Narratives Essential Snapchat Video Editors for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-sidestep-personalized-podcast-suggestions-in-spotify/"><u>[New] Sidestep Personalized Podcast Suggestions in Spotify</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-top-screen-captures-in-firefox-land/"><u>[New] Top Screen Captures in Firefox Land</u></a></li>
<li><a href="https://win11-tips.techidaily.com/directing-win-credits-to-microsoft-logins/"><u>Directing WIN Credits to MICROSOFT LOGINS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-tackling-epic-games-sign-in-on-pc/"><u>Efficiently Tackling Epic Games Sign-In on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-calendar-look-with-outlook-customization-tricks/"><u>Elevate Your Calendar Look with Outlook Customization Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/guide-how-to-prevent-windows-hardware-key-usage/"><u>Guide: How to Prevent Windows' Hardware Key Usage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enhance-windows-11-task-manager-with-a-search-tool/"><u>How to Enhance Windows 11 Task Manager with a Search Tool</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-oppo-f23-5g-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Oppo F23 5G to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-mouse-thumb-button-clicks-in-windows-11/"><u>Mastering Mouse Thumb Button Clicks in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-and-fixing-non-operational-printer-feature-via-wwinplusp-in-windows/"><u>Navigating and Fixing Non-Operational Printer Feature via WWin+P in Windows.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-interface-clarity-displaying-this-pc-icon/"><u>Optimizing Interface Clarity: Displaying 'This PC' Icon</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-unknown-disk-error-in-windows/"><u>Overcoming Unknown Disk Error in Windows</u></a></li>
<li><a href="https://buynow-help.techidaily.com/space-saga-with-a-twist-uncover-the-entertaining-story-in-the-outer-worlds/"><u>Space Saga with a Twist: Uncover the Entertaining Story in 'The Outer Worlds'</u></a></li>
<li><a href="https://tech-hub.techidaily.com/tech-savvy-signups-how-to-join-chatgpt-whatsapp-and-more-with-alternative-verification-methods/"><u>Tech-Savvy Signups: How to Join ChatGPT, WhatsApp and More with Alternative Verification Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-audio-test-failure-immediate-action-plan/"><u>Windows Audio Test Failure: Immediate Action Plan</u></a></li>
</ul></div>

