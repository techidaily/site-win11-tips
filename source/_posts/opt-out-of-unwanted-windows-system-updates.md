---
title: Opt Out of Unwanted Windows System Updates
date: 2024-10-29T17:31:25.875Z
updated: 2024-11-01T18:50:42.721Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Opt Out of Unwanted Windows System Updates
excerpt: This Article Describes Opt Out of Unwanted Windows System Updates
keywords: Opt-Out Update,Block Windows Updates,Unsubscribe System Patches,Skip Windows Updates,Stop Automatic Updates,Disable OS Patching,Turn Off Windows Patch
thumbnail: https://thmb.techidaily.com/e9c990e25117479e90a6a7012f47011623d3e85d5155cf7861b563822cc331cb.jpg
---

## Opt Out of Unwanted Windows System Updates

 Are you tired of constantly seeing tips and suggestions on your computer screen? Want to mute them and concentrate on your work uninterrupted? Don’t worry - the process is quick and straightforward.

 In this article, we’ll discuss how to turn off or disable tips and suggestions notifications on Windows 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Turn Off or Disable Tips and Suggestions Notifications in Windows 11

 Tips and suggestions provide quick guides to Windows and its features. But if you find them annoying, you can turn them off. Here are two easy methods to turn off tips and suggestions notifications on Windows 11\.

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948905/19272" target="_top" id="1948905">
  <img src="//a.impactradius-go.com/display-ad/19272-1948905" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948905/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://aligracehair.sjv.io/c/5597632/2135368/19272" target="_top" id="2135368">
  <img src="//a.impactradius-go.com/display-ad/19272-2135368" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135368/19272" style="position:absolute;visibility:hidden;" border="0" />
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
9. Click **OK** to save the changes. Now, exit the registry editor window and restart your computer.

 After restarting, tips and suggestions notifications will be disabled on your computer. If you want to enable the feature, follow the same steps and change the Value data to **0**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082533/7443" target="_top" id="2082533">
  <img src="//a.impactradius-go.com/display-ad/7443-2082533" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082533/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137229/26400" target="_top" id="2137229">
  <img src="//a.impactradius-go.com/display-ad/26400-2137229" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137229/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Stop the Windows Tips and Suggestions Notifications

 We hope that this article helped you understand how to turn off or disable tips and suggestions notifications in Windows 11\. All it takes are a few clicks or a simple REG file to enable or disable this feature.

 In this article, we’ll discuss how to turn off or disable tips and suggestions notifications on Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-exploring-the-capabilities-of-bandicam-for-multimedia-creators/"><u>[New] 2024 Approved Exploring the Capabilities of Bandicam for Multimedia Creators</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-tonal-terrain-mac-audio-artistry/"><u>[New] 2024 Approved Tonal Terrain Mac Audio Artistry</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-simplifying-massive-media-swap-iphone-to-mac-file-relocation/"><u>[New] Simplifying Massive Media Swap IPhone-to-Mac File Relocation</u></a></li>
<li><a href="https://extra-hints.techidaily.com/celebrating-redditenas-top-ten-upvoted-discussions/"><u>Celebrating Reddit'enas Top Ten Upvoted Discussions</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/comprehensive-j5-tactical-prov1-led-flashlight-analysis-sturdy-and-miniature-design/"><u>Comprehensive J5 Tactical ProV1 LED Flashlight Analysis – Sturdy and Miniature Design</u></a></li>
<li><a href="https://tech-hub.techidaily.com/content-connoisseurs-guide-outperforming-ai-writing-tools/"><u>Content Connoisseurs Guide: Outperforming AI Writing Tools</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/different-methods-to-unlock-your-iphone-7-plus-by-drfone-ios/"><u>Different Methods To Unlock Your iPhone 7 Plus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortlessly-setup-your-sandbox-on-windows-11/"><u>Effortlessly Setup Your Sandbox on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-battlenet-network-performance-on-windows/"><u>Elevating Battle.net Network Performance on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-deal-for-tech-lovers-612-windows-11-lifetime-thanks-to-keys-fans/"><u>Exclusive Deal for Tech Lovers: $6.12 Windows 11 Lifetime, Thanks to Keys Fans!</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/extracting-still-moments-top-10-video-to-photo-converters-for-2024/"><u>Extracting Still Moments Top 10 Video to Photo Converters for 2024</u></a></li>
<li><a href="https://discover-guides.techidaily.com/las-otras-innovadoras-herramientas-avanzadas-para-mejorar-videos-mediante-inteligencia-artificial/"><u>Las Otras Innovadoras Herramientas Avanzadas Para Mejorar Videos Mediante Inteligencia Artificial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/opening-windows-exe-files-a-simple-fix-guide/"><u>Opening Windows .exe Files: A Simple Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-data-management-in-win1011-with-integrated-disk-analysis/"><u>Optimize Data Management in Win10/11 with Integrated Disk Analysis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-error-code-0xc00d36b4-in-win11/"><u>Overcoming Error Code 0xC00D36B4 in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-avert-steam-freezes-in-your-win-11-game-environment/"><u>Strategies to Avert Steam Freezes in Your Win 11 Game Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overturn-restricted-application-alerts/"><u>Strategies to Overturn Restricted Application Alerts</u></a></li>
<li><a href="https://games-able.techidaily.com/transform-your-laptop-into-an-optimal-xbox-game-viewport/"><u>Transform Your Laptop Into an Optimal Xbox Game Viewport</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-intel-unison-wont-work-in-win11-solutions-included/"><u>Troubleshooting: Intel Unison Won't Work in Win11, Solutions Included</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    