---
title: Stealth Mode for Windows 11 Apps
date: 2024-06-25T17:11:05.447Z
updated: 2024-06-26T17:11:05.447Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stealth Mode for Windows 11 Apps
excerpt: This Article Describes Stealth Mode for Windows 11 Apps
keywords: Stealth Mode Windows,W11 Stealth Feature,Windows Stealth Mode,App Stealth Window,Enhance W11 Privacy,Secure W11 Apps,Hidden Windows 11
thumbnail: https://thmb.techidaily.com/dfc76f0ba5d27ec9fc744372720f89b9cd207751d15fc2d7499285fee5808af2.jpg
---

## Stealth Mode for Windows 11 Apps

 Background apps in Windows continue to perform actions such as updates and fetch up-to-date data even when you are not using them. While Windows can intelligently manage and power-optimize background apps, it can still drain your battery and increase data usage.

 Fortunately, Windows lets you change the background permission for individual Microsoft Store apps. Here we show you how to disable individual or all background apps in Windows 11\.

## 1\. How to Disable Background Apps via the Settings App

 If you want to disable individual Microsoft Store apps from running in the background, you can disable it from the Settings page. Follow the below steps to disable background apps from Settings.

1. Press **Win + I** to open the **Settings** app.
2. Open the **Apps** tab in the left pane.
3. Click on **Installed apps** in the right pane and search to locate the app for which you want to change the background permission.
4. Click the **three-dots menu** icon next to the app name and select **Advanced options.** If the option is not available, then the app does not support the background app permission management feature.  
![advanced options windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/advanced-options-windows-11-settings.jpg)
5. Scroll down to the **Background apps permissions** section.  
![background app permission never](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/background-app-permission-never.png)
6. Click the drop-down for **Let this app run in background** and select **Never**. This should disable the app from running in the background.

 By default, the background permission for the app is set to **Power optimized(recommended)**. This means Windows will decide when the app can run in the background to save more power. If you set it to **Always**, the app will continuously run in the background irrespective of your power status.

## 2\. How to Disable Background Apps via Power & Battery Settings

 The Power & battery page in Windows 11 Settings provides data on the battery usage of installed apps. This is really useful If you want to disable background apps based on battery usage to save some juice.

 Here's how to do it.

1. Press **Win + X** to open the **WinX** men and select **Settings**.
2. In the **System** tab, scroll down and click on **Power & battery.**
3. Scroll down to the Battery section and click on **Battery usage.**  
![power and battery usage](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/power-and-batter-usage.png)
4. Click the drop-down for **Battery levels** and select **Last 7 days.** Windows will load all the apps using the battery power in the last seven days.  
![manage background activity](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/manage-background-activity.png)
5. To change the background app permission, click the **three-dots menu** beside the app name, and click on **Manage background productivity**. This option is only available for Microsoft Store apps.
6. Click the **drop-down** (**Power optimized**) under the **Background apps permissions** section and select **Never**. This will disable the app from running in the background.
7. Repeat the steps for all the apps that can drain your battery or affect system performance.

 In addition to disabling background apps, try to create and use [custom Windows power plans to extend your laptop battery life](https://www.makeuseof.com/tag/save-energy-extend-battery-life-custom-windows-power-plans/). With custom power plans, you can tweak your processor and other components to configure low-power modes to achieve an improved battery life.

## 3\. How to Disable Background Apps for the Current User

 If you want, you can disable background apps for the individual user. Useful if you share your PC with multiple users at work or home. Also useful if you need to disable a non-Microsoft third-party app from running in the background.

 For this, you will need to create a registry file and run it with administrative privilege. Before you proceed, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/). You can use the restore point to revert your PC to its previous state if something goes wrong when editing the registry entries.

 To disable background apps for the current user:

1. Press **Win + R** to open the **Run** dialog.
2. Type **notepad** and click **OK** to open the text editor app.  
![disable background apps windows 11 registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disable-background-apps-windows-11-registry-editor.jpg)
3. In the Notepad file, copy and paste the following content:  
`Windows Registry Editor Version 5.00  

[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\BackgroundAccessApplications]  
"GlobalUserDisabled"=dword:00000001  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Search]  
"BackgroundAppGlobalToggle"=dword:00000000`
4. Next, press **Win + S** to open the **Save** dialog.
5. Here, name the file as **Disable\_Background\_Apps\_for\_current\_user.reg**. Then, click the **Save as type** drop-down and select **All Files.**  
![disable background apps windows 11 registry editor save](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disable-background-apps-windows-11-registry-editor-save.jpg)
6. Click the **Save** button to save the file.
7. Right-click on the newly created reg file and select **Open.** Click **Yes** to confirm and modify the registry entries to disable background apps.
8. If the script runs without error, restart your PC to apply the changes.

 The above script modifies the two DWORD values, **GlobalUserDisabled** and **BackgroundAppGlobalToggle,** setting them to **1** and **0**, respectively. Modifying the GlobalUserDisabled value prevents background access to applications.

 Similarly, changes to the BackgroundAppGlobalToggle turn off the toggle for background apps in Windows search, thus limiting its background access.

 If you need to turn on background apps for the current user, then save the following script as **enable\_background\_apps.reg** and run it as administrator.

![reg file content background app disable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/reg-file-content-background-app-disable.png)

`Windows Registry Editor Version 5.00  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\BackgroundAccessApplications]  
"GlobalUserDisabled"=-  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Search]  
"BackgroundAppGlobalToggle"=-`

## 4\. How to Disable Background Apps for All Users Using Registry Editor

 If you want to disable background apps for all the user accounts, you can manually create and modify the registry values in the Registry Editor.

 To disable background apps for all the user accounts:

1. Press **Win + R** to open **Run**.
2. Type **regedit**, and click **OK**. Click **Yes** to grant administrative access.
3. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows`
4. Under the **Windows** key, locate the **AppPrivacy** key**.** If not available, you will need to create a new key.  
![registry editor create new key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/registry-editor-create-new-key.png)
5. Right-click on the **Windows** key and select **New > Key.** Rename the key as **AppPrivacy.**
6. Right-click on the **AppPrivacy** key and select **New > DWORD (32-bit) Value**. Rename the value as **LetAppsRunInBackground.**  
![registry editor create new value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/registry-editor-create-new-value.png)
7. Right-click on the **LetAppsRunInBackground** value and select **Modify**.  
![registry editor data 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/registry-editor-data-2.png)
8. Type **2** in the **Value data** field and click **OK** to save the changes.
9. Close the Registry Editor and restart your PC to apply the changes.

 This should disable Microsoft Store apps from running in the background. To enable the background apps, modify the **LetAppsRunInBackground** value and set it to **0**.

## 5\. How to Disable Background Apps Using the Group Policy Editor

 Alternatively, you can also use the Group Policy Editor to configure background apps settings on your computer network. This is useful for system administrators having to configure multiple systems.

 Note that Group Policy Editor is officially only available in the Pro, Education, and Enterprise editions of the Windows OS. If you are on Home, read our guide on [how to enable Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). This involves a registry hack to enable the missing functionality in the Home edition of the OS.

 Once you have the policy editor up and running, continue with the steps below. To disable background apps using Group Policy Editor:

1. Press the **Win key**, type **group policy**, and click on **Edit group policy** from the search results.
2. In the Group Policy Editor, navigate to the following location:  
`Computer Configuration\Administrative Templates\Windows Components\App Privacy​`
3. In the right pane, locate and double-click on **Let Windows apps run in the background** policy.  
![disable background app group policy editor policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/disable-background-app-group-policy-editor-policy.png)
4. In the new window that appears, select **Enabled**.
5. Next, under the **Options** section, click the drop-down for **Default for all apps** and select **Force Deny**.  
![disable background app group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/disable-background-app-group-policy-editor.png)
6. Click **OK** and **Apply** to save the changes.

 Alternatively, you can set the Let Windows apps run in the background policy to **Disabled** and apply the changes. However, when set to **Disabled** or **Not Configured**, individual employees in your organization can configure the apps to run in the background.

 On the contrary, setting this policy to **Force Deny** will prevent the app from running in the background, with no option for the employees to change the policy.

## Disabling Background Apps in Windows 11

 Windows allows you to configure background app permission for the Microsoft Store apps. You can disable these apps to conserve battery and avoid unnecessary data usage on a metered connection.

 That said, if you are struggling with slow system performance issues, disabling background apps may not be the solution. What you can do instead is reconfigure your OS, analyze your storage devices and look for hardware upgrades to boost system performance.

 Fortunately, Windows lets you change the background permission for individual Microsoft Store apps. Here we show you how to disable individual or all background apps in Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/solving-outlook-cannot-be-opened-issue-on-windows-desktop/"><u>Solving Outlook Cannot Be Opened Issue on Windows Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-cursor-visibility-on-win-11-a-guide/"><u>Maximizing Cursor Visibility on Win 11: A Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-to-streamline-your-windows-netconnection-access/"><u>Step-By Step to Streamline Your Windows NetConnection Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-windows-to-run-this-application-you-must-install-net-core-error/"><u>How to Fix the Windows “To Run This Application, You Must Install .NET Core” Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/past-keys-to-future-launches-utilizing-windows-7-for-windows-11-bootup/"><u>Past Keys to Future Launches: Utilizing Windows 7 for Windows 11 Bootup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-without-taskbar-chat-what-it-means-for-you/"><u>Windows 11 Without Taskbar Chat: What It Means for You?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-turning-onoff-secure-boot-in-virtualbox/"><u>Step-by-Step Guide: Turning On/Off Secure Boot in VirtualBox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-8-cross-platform-tools-for-microsoft-enthusiasts/"><u>Top 8 Cross-Platform Tools for Microsoft Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/screenscape-symphony-composing-personalized-displays-in-windows-1011/"><u>Screenscape Symphony: Composing Personalized Displays in Windows 10/11</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-the-ultimate-routine-for-accessing-and-playing-fb-videos-via-apple-tv/"><u>2024 Approved  The Ultimate Routine for Accessing and Playing FB Videos via Apple TV</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-best-websites-for-turning-a-photo-into-a-cartoon/"><u>Updated Best Websites for Turning a Photo Into a Cartoon</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-honor-x9a-drfone-by-drfone-virtual-android/"><u>In 2024, 4 solution to get rid of pokemon fail to detect location On Honor X9a | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-iphone-album-arrangement-masterclass-achieving-systematic-order-and-cloud-sync/"><u>[New] IPhone Album Arrangement Masterclass  Achieving Systematic Order & Cloud Sync</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-expertise-in-iphones-macro-photography-secrets-revealed/"><u>2024 Approved  Expertise in iPhone's Macro Photography Secrets Revealed</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/2024-approved-vloggers-ultimate-gear-list-17-100/"><u>2024 Approved  Vloggers' Ultimate Gear List #17-100</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-how-to-zoom-inout-in-instagram-stories/"><u>[Updated] 2024 Approved  How to Zoom In/Out in Instagram Stories</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/in-2024-your-iphones-mp3-fix-6-free-tools-to-convert-youtube-audio/"><u>In 2024, Your iPhone's MP3 Fix  6 Free Tools to Convert YouTube Audio</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-shake-the-sound-mobile-beats-best-ripplers/"><u>[Updated] Shake the Sound  Mobile Beats' Best Ripplers</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-usb-c-vision-the-new-standard-in-monitors-hp-envy-27/"><u>2024 Approved  USB-C Vision  The New Standard in Monitors - HP Envy 27</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>