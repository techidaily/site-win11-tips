---
title: Instructions to Bring Back Old-School Search in Windows 11
date: 2024-07-12T17:34:59.082Z
updated: 2024-07-13T17:34:59.082Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Instructions to Bring Back Old-School Search in Windows 11
excerpt: This Article Describes Instructions to Bring Back Old-School Search in Windows 11
keywords: Classic Windows 11 Search Guide,Restore Legacy Windows Search,Windows 11,Nostalgic Windows 11 Search Tutorial,Bring Old-School Search to Windows 11,Reviving Traditional Windows Search,Switch Back Classic Windows Search Mode
thumbnail: https://thmb.techidaily.com/67fbae13bc8823b0a301a4edbd98e7b90a3759ff0f1b1dda3ab1c9790066eccf.jpg
---

## Instructions to Bring Back Old-School Search in Windows 11

 Windows 11 is still an evolving platform, so users may notice changes in their UI as time goes on. Some of these changes aren't always appreciated, and you may have noticed that your taskbar search icon has become a search bar.

 If so, read on. Here's how to revert the Windows 11 search bar to a search icon.

## What Happened to the Windows 11 Taskbar Search Icon?

![screenshot of the new taskbar search icon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/screenshot_of_new_search_taskbar_icon.jpg)

 If you're keeping Windows 11 updated, you would have had your taskbar search icon change over to a larger bar-shaped icon.

 This change happened automatically and, as of the time of writing, cannot be changed through the settings menu.

 Thankfully, there's a catch-all solution to many of these design changes.

## Restoring Features with ViVeTool
![screenshot of ViVeTool in system 32](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/screenshot_of_vivetool_in_system_32.jpg)

 ViVeTool is what we'll be using to change this feature back, and it can be found on the [GitHub page for ViVeTool](https://github.com/thebookisclosed/ViVe/releases/tag/v0.3.2) . In order to properly use this program, it needs to be extracted into the right location: System32.

 Make sure you read up on [System32 and how important it is for your system before you proceed](https://www.makeuseof.com/tag/windows-system32/) . ViVeTool is a safe program, but it's good to know what you're doing before you jump in.

 When you're ready, extract the downloaded ZIP for ViVeTool into your System32 folder.

## How to Restore the Windows 11 Search Bar Icon
![screenshot of the quick command menu opening windows terminal in admin mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/screenshot_of_quick_command_windows_terminal_admin.jpg)

 Begin by launching an admin-level terminal window. To do this, right-click on the start menu icon, and hit**Windows Terminal - Admin** . Make sure you click**Yes** to the User Account Control window.

Next, input the following code into the terminal window:

`vivetool /disable /id:39263329`

 You'll know it's successful if you see the message**Successfully set feature configurations** .

 Then, all you have to do is restart. Your search icon should return to its original style.

## Features Change, Even if You Don’t Want Them To

 At the end of the day, this might very well be a temporary fix. Microsoft could include a toggle in the future, or add in further changes that break the functionality of this tool.

 While that might be annoying, as long as there are people using Windows, there will be people making modifications such as ViVeTool to give control back to the user.


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




