---
title: How to Enable an End Task Option on the Windows 11 Taskbar
date: 2024-09-13T23:19:24.190Z
updated: 2024-09-17T03:25:21.708Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Enable an End Task Option on the Windows 11 Taskbar
excerpt: This Article Describes How to Enable an End Task Option on the Windows 11 Taskbar
keywords: Windows 11 Taskbar Setup,Enable End Task Icon,Taskbar Options Guide,Turn On Windows Exit Button,Close Taskbar Window Tips,EndTask Feature in Win11,Windows 11 Taskbar Customize
thumbnail: https://thmb.techidaily.com/66f3a5314b7f0b6f994f976b66c33a57ff0466854aa08d5996bdfaffcb47f66d.jpg
---

## How to Enable an End Task Option on the Windows 11 Taskbar

 The "end task" option in Windows 11 is your best friend when a program has stopped responding or has frozen. It allows you to close those unresponsive applications without restarting your PC. However, the "end task" may not be easy to find on Windows 11, especially if you are new to the operating system.

 In this article, we are sharing tricks to bring the End task option to the Windows 11 taskbar by using ViveTool. After enabling it, you will be only a click away from closing all the unresponsive applications.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is ViveTool, And Why Do You Need It to Enable End Task in Taskbar?

 ViveTool is a third-party program designed to enable Windows 11 features that Microsoft is testing internally and are not available for Insiders or general users. Using this app, ViveTool can give you an idea about what the software company plans to introduce to the next Windows 11 updates.

 At the time of writing, the "end task" option on Windows 11 taskbar is currently hidden in Windows 11 Dev Insider build 25300, meaning that even Insiders can't get it just yet. And this is where the ViveTool comes in.

 You can enable feature ID 42592269 to make the end task option appear on the taskbar jump list. However, before we hop into ViveTool and enable this handy feature, you should keep your expectations low regarding the functionality and reliability of the features you're about to enable.

## How to Enable End Task Option in Windows 11 Taskbar

![End task option in Windows 11 Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/end-task-option-in-taskbar.jpg)

 Besides ViveTool, you also need to ensure that your PC is running Windows 11 Dev Channel build 25300 or later. You should see the build number in the bottom right corner of the desktop. Alternatively, you can navigate to**Settings** \>**System** \>**About** to check the OS build number.

 After ensuring your PC is running build 25300 or newer,[download the ViveTool zip file from the GitHub page](https://github.com/thebookisclosed/ViVe/releases) . Now, open File Explorer and find the zipped file. To unzip it, right-click on the file and select**Extract All** . You can also[unzip the file by using Command Prompt and PowerShell](https://www.makeuseof.com/zip-unzip-files-command-prompt-powershell/) . For the sake of simplicity, the extracted content should be in the folder**C:/ViVeTool** .

![Enable End Task option in Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/feature-id-in-command-prompt-edit.jpg)

 Now that you are done with setting up ViveTool on Windows 11, follow the below steps to enable the feature ID responsible for adding the "end task" option on the Windows 11 taskbar:

1. Open Command Prompt as an Administrator (see[how to open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for steps).
2. Type the following command and hit**Enter** :  
cd C:\ViVeTool
3. Copy and paste the following command and press**Enter:**  
vivetool /enable /id:42592269

 Command Prompt will display a message that says "Successfully set feature configuration (s)" after successfully running the command. To make the changes take effect, restart your computer. After the restart, open a program and right-click its icon on the taskbar to display the jump list containing the**End task** option.

## An End Task Button on the Windows 11 Taskbar Is Now at Your Fingertips

 Adding the "end task" option onto the Windows 11 taskbar is currently available only via ViveTool. However, in the coming days, Microsoft will likely introduce it to every Windows 11 Insider, then eventually to the public either via a Moment update or through the Windows Web Experience pack. But before that happens, you are now familiar with the trick to terminate any task or process right from the Windows 11 taskbar.

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



<!-- affiliate ads begin -->
<span id="1770526">
					<video width="240" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1770526.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20702-1770526">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1770526.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftokenmetrics.sjv.io%2Fc%2F5597632%2F1770526%2F20702'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1770526/20702" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

