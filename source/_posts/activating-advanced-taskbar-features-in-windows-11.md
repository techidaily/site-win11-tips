---
title: Activating Advanced Taskbar Features in Windows 11
date: 2024-07-12T17:31:27.668Z
updated: 2024-07-13T17:31:27.668Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Activating Advanced Taskbar Features in Windows 11
excerpt: This Article Describes Activating Advanced Taskbar Features in Windows 11
keywords: Win 11 Taskbar Tips,Enhance Window Bar,Taskbar Tricks W11,Advanced Bar Controls,Maximize Taskbar Usage,Windows 11 UI Upgrades,Power Taskbar Tweaks
thumbnail: https://thmb.techidaily.com/7c4b3f31474d59dd334b247ce3128a185630128709ac4ffbfcbd9f4ba557fefe.jpg
---

## Activating Advanced Taskbar Features in Windows 11

 Microsoft is continuously developing new features and fixing the underlying issues with Windows 11 in the Insider channel. But some additions in Windows 11, like the Teams icon on the Taskbar, make no sense for most users. It isn’t an app anyone loves to pin on the Taskbar unless they use it in their workplace.

 In a surprising move, Microsoft removed the Teams icon and the option to adjust its presence on the Taskbar, as seen in a new Insider Dev build. Along with that, there are a couple of changes to the Search Box as well. Curious? Let’s begin.

## What Are the Enhanced Taskbar Settings in Windows 11?

 The first major change is the removal of the [Microsoft Teams](https://www.makeuseof.com/what-is-microsoft-teams-my-day/) chat icon from the Taskbar. Until now, there was only an option to hide the tool from the Taskbar. Despite its popularity in the business landscape, the Teams app has very little usage for the rest of Windows users. So, completely removing the icon and its traces from the Settings app is a change that most users will like.

![Old Taskbar settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/old-taskbar-settings.jpg)

 But that won’t remove the Teams app entirely. You will have to uninstall it manually to get rid of it. The Search Box is also getting a few improvements. It will get a dedicated section in the Taskbar setting with an option to launch whenever you hover over it. All these hidden changes can be revealed using the ViveTool.

## How to Enable Multiple Taskbar Settings in Windows 11

 At the time of writing, the above-mentioned Taskbar changes exist in the Windows Insider Dev build 23466\. Remember that there are now two separate channels, [Canary](https://www.makeuseof.com/what-is-windows-insider-canary-channel/) and Dev in the Insider program.

 You need to update your PC which is enrolled in the Dev channel to install build 23466\. However, if you aren’t a Windows Insider participant, use [UUP Dump to download the Insider builds directly](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) and then install them on your PC.

 You will also need the trusty-old ViveTool to enable hidden experimental features on your PC. Just [download the ViveTool from GitHub](https://redirect.viglink.com/?format=go&jsonp=vglnk%5F168840932974910&key=eac202ea7a96cf485281d6c4ffa2069e&libId=ljn7bewf0103es17000ULjtg6rvb2&loc=https%3A%2F%2Fwww.makeuseof.com%2Fenable-gallery-file-explorer-windows-11%2F&ccpaConsent=1---&v=1&opt=true&optExText=false&out=https%3A%2F%2Fgithub.com%2Fthebookisclosed%2FViVe%2Freleases&ref=https%3A%2F%2Fwww.makeuseof.com%2Fauthor%2Fabhishekkumar-mishra%2Fpage%2F2%2F&title=How%20to%20Enable%20the%20Gallery%20in%20File%20Explorer%20in%20Windows%2011&txt=download%20ViVetool%20from%20GitHub) and extract it to a folder named “Vive” in the C drive for easier access. After that, repeat the following steps:

1. [Open Command Prompt with administrator privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/) on your PC.
2. Type **cd C:\\** command and press the **Enter** key to switch to the main directory in the C drive.
3. After that, type **cd Vive** to switch to the folder where ViveTool is present.
4. Now, type the following commands and press the Enter key to execute them one by one:  
`vivetool /enable /id:44520430  
 vivetool /enable /id:43572692  
 vivetool /enable /id:41950597`
5. **Close** the Command Prompt.  
![Enable New Taskbar Features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-new-taskbar-features.jpg)
6. **Restart** your PC to apply the changes made by ViveTool.

 Now, you can adjust the newly enabled settings on your PC.

1. Right-click on the Taskbar to open the context menu. Click on the **Taskbar settings** option.
2. The first change that you will observe is that the Chat option is no longer present under the Taskbar Items section. The same goes for its presence on the Taskbar.
3. Scroll down to the **Search** section. Click on the **Search box** option, and you can select the full, condensed view, or completely disable the search box.  
![New Taskbar settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-taskbar-settings.jpg)
4. After enabling the new Search Box features, it will automatically open when your hover the cursor over it. If you want to disable this action, click on the **toggle** next to the **Open search on hover (when available)** option.

 The Search Box will also display a small icon related to a current important event in the world. When you open the Search Box or click on the event icon, you will see an expanded section describing the event and the options to learn more and use [Bing’s AI-powered chatbot](https://www.makeuseof.com/ways-bing-ai-improving/) feature.

![Search Box Events Popup in Windows 11-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/search-box-events-popup-in-windows-11-1.jpg)

## The Teams Chat Icon Is Gone For Good

 Not everyone needs the pre-packaged apps in Windows 11 that Microsoft is so confident about. Removing the Teams Chat icon is a commendable change, and we hope that it makes it to the final preview and stable channels as well. Apart from that, the changes to Taskbar settings will make it customizable for end users.

 In a surprising move, Microsoft removed the Teams icon and the option to adjust its presence on the Taskbar, as seen in a new Insider Dev build. Along with that, there are a couple of changes to the Search Box as well. Curious? Let’s begin.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

