---
title: Effective Blue Screen Analysis Techniques with Microsoft on W11
date: 2024-10-03T20:14:48.747Z
updated: 2024-10-09T01:23:33.208Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Effective Blue Screen Analysis Techniques with Microsoft on W11
excerpt: This Article Describes Effective Blue Screen Analysis Techniques with Microsoft on W11
keywords: W11 BS Analysis,MS Windows Screens,BS Diagnostic Tool,Screen Error Fix,W11 BlueScreenTech,TechTroubleshootingW11,Debugging MicrosoftOS
thumbnail: https://thmb.techidaily.com/58d6990fb1aba3befeda20029d053fd2dc8e67729321f3227eadd737a516d064.jpg
---

## Effective Blue Screen Analysis Techniques with Microsoft on W11

 Windows operating system is far from perfect and encounters errors frequently. While Microsoft releases updates to fix widespread errors, some errors require a different tweaking approach to fix them. However, whenever you see an error code, the first idea is to note it down and search for it online.

 But do you know you can look up error codes in Windows 11? Microsoft offers an error lookup tool using which you can check for any error that pops up on your Windows PC. Without further ado, let's explore this wonderful tool and learn how to check error codes with it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is the Microsoft Error Lookup Tool?

 Microsoft Error Lookup tool does exactly what it sounds like. You can look up system error codes using this tool to get an idea of what the error code is really about. However, this is a command-line tool, so you need to use Command Prompt to run it. Microsoft is yet to release a GUI version of this tool, which could make searching for error codes for non-tech-savvy users convenient.

 Using a simple command, you can search and learn more about the nature of the error code. Microsoft Error Lookup tool is only available for Windows OS versions 8.1 and above. So, if you are still using Windows 7, searching the web remains your only option.

## How to Download and Run Microsoft Error Lookup Tool

 Microsoft Error Lookup is a lightweight command-line tool. You don’t need a copious amount of system resources to run it on your system. Here’s how to download and set up the tool on your system:

### 1\. Downloading and Renaming the Tool

 Repeat the following steps to download and install the Microsoft Error Lookup tool:

1. Launch a web browser on your system and visit the[Microsoft Error Lookup Tool download page](https://www.microsoft.com/en-us/download/details.aspx?id=100432) .
2. Scroll down and click on the Download button. It will take a few seconds for the download to complete.
3. Press**Win + E** to[launch the File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to the Microsoft Error Lookup Tool executable file download location.
4. Since it is a command-line tool, you will have to run it by typing its full name. The default download name is**Err\_6.4.5** which will be trouble to remember and type correctly every time in the Command Prompt. So, we will rename it to something easier like**Err** .
5. Right-click on the Microsoft Error Lookup tool executable file and select**Show more options** .  
![Renaming Microsoft Error Lookup Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/renaming-microsoft-error-lookup-tool.jpg)
6. Then, click on the**Rename** option from the context menu. Type**Err** and press the enter key to rename the tool.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123739/7443" target="_top" id="2123739">
  <img src="//a.impactradius-go.com/display-ad/7443-2123739" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123739/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389">
  <img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Placing the Tool in a Convenient Location

 You can only run the Microsoft Error Lookup Tool from the command line. If you place it in a deeply nested path like a folder inside a directory, you will have to navigate to that directory from the command line every time. So, you must move the tool to an accessible location first.

Here’s how to do it:

1. Press**Win + E** to open File Explorer and navigate to the Microsoft Error Lookup Tool download location. Now, press**Ctrl + C** to copy the file.
2. Go to the C drive and paste the tool. Grant permissions to place the tool in C drive.  
![Placing Microsoft Error Lookup Tool in C drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/placing-microsoft-error-lookup-tool-in-c-drive.jpg)
3. Now, press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** in the text box and press enter key.

4. In the Command Prompt window, type the following command and press the enter key:**cd C:\\** .
5. Now, you will be in the parent directory. Type**Err** and press enter.  
![Running Microsoft Error Lookup Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/running-microsoft-error-lookup-tool.jpg)
6. Microsoft Error Lookup Tool will run and display the format to look up error codes along with other available parameters. Don’t close the tool yet.

## How to Check Error Codes Using Microsoft Error Lookup Tool

 Now, you have the Microsoft Error Lookup Tool up and running on your system. All you need to do is run appropriate commands to view information about error codes. Here’s how:

1. In the same Command Prompt window, you must type**\[Tool name\] \[error code\]** and press the enter key.
2. Suppose you want to look up the error code 0x80070490 using the tool. So, the correct command will be:**Err 0x80070490** .  
![Checking an Error Code in Microsoft Error Lookup Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/checking-an-error-code-in-microsoft-error-lookup-tool.jpg)
3. Press the enter key and the tool will display all the matching information it has about the error code. It will include the exact error string and a sentence describing the meaning. Often, it will also try to make suggestions to fix the error.

 An error code can have multiple meanings and the error lookup tool will list all of them. You can use this information to narrow down your search and try to fix the issue.

## How to Export the Output of Microsoft Error Code Tool

 The tools can output multiple matches for an error code and that information becomes difficult to scroll in the Command Prompt window. But we can export the results of the error code lookup to a text file on your system.

Repeat the following steps:

1. Press**Win + S** and type CMD. Click on the**Run as administrator** option.
2. Now, type the following command to navigate to the error lookup tool location:**cd C:\\**
3. The syntax for copying the error code lookup results is:**Err \[Error code\] > \[Path of text file\]** .
4. So, your final command will become:**Err 0x80070490 > D:\\error.txt** .  
![Exporting Error Code Lookup results in Microsoft Error Lookup Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/exporting-error-code-lookup-results-in-microsoft-error-lookup-tool.jpg)
5. It will export the results to the text file named error on D drive. If the file doesn’t exist, the tool will create it with the same name. However, it won’t display any search result in the Command Prompt and just display the number of matches found.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135361/19272" target="_top" id="2135361">
  <img src="//a.impactradius-go.com/display-ad/19272-2135361" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135361/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Exporting Error Code Lookup results in a text file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/exporting-error-code-lookup-results-in-a-text-file.jpg)

 Now, open the file, and you can read the entire list of error code results and begin troubleshooting.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134240/18498" target="_top" id="2134240">
  <img src="//a.impactradius-go.com/display-ad/18498-2134240" border="0" alt="https://techidaily.com" width="540" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134240/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Can the Microsoft Error Lookup Tool Display Information About All Error Codes?

 Microsoft updates the tool to the latest version in 2019\. Since then, it hasn’t received an update. So, as newer builds or a[new version of Windows](https://www.makeuseof.com/windows-12-improve-upon-windows-11/) comes out, the tool may fail to produce results for a specific error code. But the chances of that are very slim. Moreover, it contains information only about Windows and some other Microsoft error codes. Don’t expect it to display information about errors you face inside a third-party application or program.

 So, you can use the error lookup tool without any worries and patiently wait for Microsoft to release a new build. You can check for the latest available build by visiting the official download page of the Microsoft Error Lookup Tool. Or, you can try a bunch of third-party options like Winerr or Error Lookup Tool for a more presentable error code lookup and troubleshooting experience.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997717/19272" target="_top" id="1997717">
  <img src="//a.impactradius-go.com/display-ad/19272-1997717" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997717/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Lookup Error Details With Ease

 Microsoft Error Lookup Tool is a free tool that you can easily run on your system. Surely, you won’t get a very descriptive troubleshooting guide with it. But you will still be able to find the issue and error string related to it, and even a suggestion, if the tool has one.

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-http.techidaily.com/new-discover-the-joy-of-customized-messaging-downloading-and-tailoring-whatsapp-ringtones-on-mobile-for-2024/"><u>[New] Discover the Joy of Customized Messaging Downloading & Tailoring WhatsApp Ringtones on Mobile for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-easy-steps-to-personalize-google-meet-on-laptops-and-mobile-devices/"><u>[New] Easy Steps to Personalize Google Meet on Laptops & Mobile Devices</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-from-novice-to-pro-an-extensive-guide-to-capturing-top-notch-audio-on-zoom/"><u>[New] From Novice to Pro An Extensive Guide to Capturing Top-Notch Audio on Zoom</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-streamlined-strategies-for-gaming-screen-recording/"><u>[New] In 2024, Streamlined Strategies for Gaming Screen-Recording</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-syncing-muted-voices-with-obs-streams/"><u>[Updated] 2024 Approved Syncing Muted Voices with OBS Streams</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-dynamic-website-content-incorporating-youtube-playlists/"><u>[Updated] Dynamic Website Content Incorporating YouTube Playlists</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-low-cost-options-for-acquiring-gopro-cameras/"><u>[Updated] Low-Cost Options for Acquiring GoPro Cameras</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-routes-to-reviving-the-elusive-windows-terminal/"><u>5 Routes to Reviving the Elusive Windows Terminal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-get-started-with-windows-11s-widgets/"><u>7 Ways to Get Started With Windows 11'S Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-windows-pop-up-non-adobe-issue/"><u>Avoiding Windows Pop-Up: Non-Adobe Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-writing-with-these-top-pc-apps/"><u>Boost Your Writing with These Top PC Apps</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/complete-fixes-to-solve-apple-iphone-7-randomly-asking-for-apple-id-password-drfone-by-drfone-ios/"><u>Complete Fixes To Solve Apple iPhone 7 Randomly Asking for Apple ID Password | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/earn-money-by-using-bing-unveiling-my-experience-with-microsofts-lucrative-offer/"><u>Earn Money by Using Bing? Unveiling My Experience with Microsoft's Lucrative Offer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719335028418-stop-early-window-11-edge-tabs-now/"><u>Stop Early Window 11 Edge Tabs Now</u></a></li>
</ul></div>

