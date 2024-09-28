---
title: How to Enable the Hidden Taskbar Search in Windows 11
date: 2024-08-16T02:35:13.519Z
updated: 2024-08-17T02:35:13.519Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Enable the Hidden Taskbar Search in Windows 11
excerpt: This Article Describes How to Enable the Hidden Taskbar Search in Windows 11
keywords: Windows 11 Taskbar Search,Enable Windows Search Bar,Hidden Search Icon Trick,Activate Taskbar Search,Windows 11 Search Settings,Unveil Windows Search Tool,Tips for Windows 11 Taskbar
thumbnail: https://thmb.techidaily.com/30461ded64430f275adab068e1aa1246b69e0b37015df4b520c0cb3237617656.jpg
---

## How to Enable the Hidden Taskbar Search in Windows 11

 Microsoft has added a search option to the taskbar that lets you customize the search box's appearance. At the time of writing, the feature is hidden by default, but ViveTool can enable it for you.

 This guide will show you how to add the newer taskbar search on a Windows 11 PC.

## How to Add the Hidden Taskbar Search on Windows 11

 To enable the new search box on your system's taskbar, make sure you're on the Windows latest version. For this, open Settings (see[how to open Windows Settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/) for steps) and then select**Windows Update > Check for updates** . If you find any pending updates here, download and install them.

 Once you're done,[download ViveTool from the GitHub page](https://github.com/thebookisclosed/ViVe/releases) . After downloading the zip file, extract the contents into the folder**C:/ViVeTool** .

 Now follow our guide on[how to open the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) to get the tool open. In the Command Prompt window, type the following command and hit**Enter** :

`cd C:\ViVeTool`

 Copy and paste the following command and press**Enter** to add the new Search box on your taskbar:

`vivetool /enable /id:39072097 /variant:2`

![Enable the New Taskbar Search Feature](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/enable-the-new-taskbar-search-feature.jpg)

 After running the command, your computer will display a message saying "Successfully set feature configuration (s)". In order to make the changes effective, restart your computer and then follow these steps:

1. Click on**Settings > Personalisation > Taskbar** .  
![Change Taskbar Search Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/change-taskbar-search-option.jpg)
2. Next to the Search option, you will see a drop-down menu. Click on it and select the kind of outlook you prefer.
3. If you don't need a search box in the taskbar, simply select**Hide** , and the box will disappear.

 If you want to disable this new search feature for any reason, execute the following command in the Command Prompt:

`vivetool /disable /id:39072097 /variant:2`

<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## A New Search Box, Added to the Windows Taskbar

 With the release of Windows 11 build 25227, you can enable a new search box on the taskbar. After reading this tutorial, you should be able to change your taskbar on Windows 11.


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


