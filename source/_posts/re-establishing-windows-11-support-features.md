---
title: Re-Establishing Windows 11 Support Features
date: 2024-06-23 20:26:51
updated: 2024-06-26 10:51:48
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Re-Establishing Windows 11 Support Features
excerpt: This Article Describes Re-Establishing Windows 11 Support Features
keywords: Win11 Update,Win11 Fixes,Win11 Services,Win11 Restore,Win11 Maintenance,Win11 Reinstate,Win11 Recover Features
thumbnail: https://thmb.techidaily.com/c0f93108181366d1b09090c17e7518417597848beec02f800a980d5086b0f997.jpg
---

## Re-Establishing Windows 11 Support Features

 Microsoft is transitioning from traditional troubleshooters to the Get Help app, a unified platform to streamline troubleshooting. While the Get Help app promises to simplify the process, you might encounter challenges such as a completely white or gray screen when opening the app.

 So, let's look at how to fix the Get Help app issues on Windows and make the troubleshooting experience a breeze.

## 1\. Begin With Some General Fixes

 Here are some quick tips on how to fix the Get Help app not working issues quickly:

* **Restart the Get Help app:**[Open the Task Manager](https://www.makeuseof.com/how-to-access-task-manager-on-windows-11/) and right-click on the Get Help app. Then click on **End task** and start the app again. This simple trick effectively addresses temporary glitches within the application.  
![Get Help End Task Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/get-help-end-task-option.jpg)
* **Reboot your computer:** Rebooting a computer often resolves many problems by clearing your system's memory and terminating problematic processes.
* **Update your Windows version:** Older versions of Windows may contain bugs that may prevent the Get Help app from functioning correctly. So, always [ensure your Windows version is up-to-date](https://www.makeuseof.com/update-windows-manually/).

 Note that these fixes can't help you if your issue is serious. In that case, try the following troubleshooting methods.

## 2\. Repair or Reset the Get Help App

 In some situations, the Get Help app may be corrupt. For example, if your computer is infected by malware, it may force some Windows apps to malfunction. If this is your case, please first [disinfect your Windows computer](https://www.makeuseof.com/best-malware-removal-tools-pc/).

 Afterward, consider repairing or resetting the Get Help app by following these steps:

1. Open the Windows Settings app with the **Win + I** key combination.
2. Use the search bar to type **Apps** and click on **Add or remove programs**.  
![Windows Settings Search Results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-settings-search-results.jpg)
3. Search for **Get Help** in the list of apps and click on the three-dot menu. Then click on **Advanced options**.  
![Get Help In Installed Apps](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/get-help-in-installed-apps.jpg)
4. Now, scroll to the bottom and click **Repair**. If the repair fails, you can use the **Reset** option.  
![Get Help Repair Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/get-help-repair-option.jpg)

 Here's the best part: This process isn't exclusive to the Get Help app. So, you can also apply the above steps to other malfunctioning Windows apps

## 3\. Troubleshoot Network-Related Issues

 The Get Help app relies on your computer’s network to provide you with in-app content. Therefore, it's common for your wrong network settings to cause trouble with the Windows apps. We recommend you take a look at our guide on [how to troubleshoot the internet on Windows](https://www.makeuseof.com/tag/fix-windows-10-wi-fi-problems/) for various methods.

 You can also resolve potential network-related issues by:

* Restarting your router or modem to rectify minor network hiccups.
* Connecting to a different network, as specific network configurations might disrupt certain apps.
* Contacting your Internet Service Provider (ISP) to inquire about potential network maintenance.

## 4\. Disable VPN or Proxy Temporarily

 If you're still facing issues with the Get Help app, it seems to be due to your VPN or proxy configuration. You can disable your connected VPN or proxy for a quick test.

 If you don't know the exact steps for it, here's how to disable your VPN or proxy:

1. Type **VPN settings** in Windows Search and select **Open** next to the search result.  
![VPN Settings Search Results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/vpn-settings-search-results.jpg)
2. Choose the **Disconnect** button to turn off the VPN.
3. Similarly, you must [temporarily disable your proxy](https://www.makeuseof.com/windows-11-disable-proxy/) to troubleshoot the cause of your Get Help failing to work.

 Remember to re-enable your VPN or proxy once you're done to ensure your online activities remain private and secure.

 Now you can open the Get Help app and check whether the content loads correctly. Try the following troubleshooting method if the Get Help app still displays a blank screen.

## 5\. Restart Windows Services

 If you don't know, Windows services continuously operate in the background. Such services handle various system tasks, and specific applications, like the Get Help app, rely on the services to work correctly. If the app is still not working, it may be due to one or more Windows services malfunctioning.

 For that, here's how to fix the Windows services not running problem on Windows:

1. You can use the Services app to manage all the Windows services. To open that, press **Win + R** and type **services.msc**.  
![Services Command On Run App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/services-command-on-run.jpg)
2. Now press **Enter** to launch the Services app.
3. You'll see a list of all the services currently available in your system. Locate the **Diagnostic Policy Service** and right-click on its name.
4. Select **Restart** from its context menu.  
![Diagnostic Policy Service Restart Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/diagnostic-policy-service-restart-option.jpg)
5. Similarly, repeat the steps to restart the **Windows Management Instrumentation** service.

## 6\. Install the Microsoft Edge WebView2 Runtime

 You may not know that the Get Help app is not a full-fledged Windows app. Instead, it's a simple web app that displays the in-app content from Microsoft's server. For this, the app uses something called Microsoft Edge WebView.

 The Microsoft Edge WebView is a small-sized program that allows Windows apps to fetch any content from the internet and display that inside an app. Sometimes, this Microsoft Edge WebView may get corrupted, leading to problems with all web-based apps.

 The good thing is, installing the Microsoft Edge WebView2 Runtime can solve this issue. Here are the steps for it:

1. Visit the [Microsoft Edge Developer website](https://developer.microsoft.com/en-us/microsoft-edge/webview2/) and locate the **Download the WebView2 Runtime** section.
2. Click on the button matching your system's architecture under the **Evergreen Standalone Installer** heading. Alternatively, click the **Download** button under the **Evergreen Bootstrapper**.  
![Microsoft Edge Developer Site Screenshot](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/microsoft-edge-developer-site-screenshot.jpg)
3. Once you download the setup file, run it and follow the instructions.
4. After installing the Microsoft Edge WebView2 Runtime, check if the Get Help app functions correctly.

 If you see an error saying "**Setup failed**," "please re-download the correct version again.

## 7\. Uninstall and Reinstall the Get Help App

 If you've tried all other solutions, we recommend uninstalling and reinstalling the Get Help app.

 For uninstallation, you can easily [uninstall a Windows app via Settings](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/). Once done, go to the [Get Help Microsoft Store page](https://apps.microsoft.com/store/detail/get-help/9PKDZBMV1H3T). Click on the **Get in Store app** button and download it from there.

![Get Help In Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/get-help-in-store.jpg)

 A fresh installation should resolve all the issues with the app. And now, you can go back to troubleshooting without any hassle.

## No More Blank Screen in the Get Help App

 Whenever you come across a web app that is not working, the first thing is to check your internet connection. In addition, installing the Microsoft Edge WebView2 Runtime could come in handy for troubleshooting.

 Now that your Get Help app is working, you may need to know some of the best ways to use it on Windows. This way, you can get the most out of Microsoft's new troubleshooting hub.

 So, let's look at how to fix the Get Help app issues on Windows and make the troubleshooting experience a breeze.
