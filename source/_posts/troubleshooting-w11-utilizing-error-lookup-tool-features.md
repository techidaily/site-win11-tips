---
title: "Troubleshooting W11: Utilizing Error Lookup Tool Features"
date: 2024-06-25T17:01:20.772Z
updated: 2024-06-26T17:01:20.772Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Troubleshooting W11: Utilizing Error Lookup Tool Features"
excerpt: "This Article Describes Troubleshooting W11: Utilizing Error Lookup Tool Features"
keywords: W11 Troubleshoot Guide,Error Lookup in Windows,Error Tool Insights,Fixing Windows 11 Errors,Error Resolution Tips,Uncovering OS Errors,Error Analysis Strategy
thumbnail: https://thmb.techidaily.com/a3293f7209aa15a71e0e22b0ceceeb5d43595d799fa4a5a92be66390c4a5c2d5.jpg
---

## Troubleshooting W11: Utilizing Error Lookup Tool Features

 Windows operating system is far from perfect and encounters errors frequently. While Microsoft releases updates to fix widespread errors, some errors require a different tweaking approach to fix them. However, whenever you see an error code, the first idea is to note it down and search for it online.

 But do you know you can look up error codes in Windows 11? Microsoft offers an error lookup tool using which you can check for any error that pops up on your Windows PC. Without further ado, let's explore this wonderful tool and learn how to check error codes with it.

## What Is the Microsoft Error Lookup Tool?

 Microsoft Error Lookup tool does exactly what it sounds like. You can look up system error codes using this tool to get an idea of what the error code is really about. However, this is a command-line tool, so you need to use Command Prompt to run it. Microsoft is yet to release a GUI version of this tool, which could make searching for error codes for non-tech-savvy users convenient.

 Using a simple command, you can search and learn more about the nature of the error code. Microsoft Error Lookup tool is only available for Windows OS versions 8.1 and above. So, if you are still using Windows 7, searching the web remains your only option.

## How to Download and Run Microsoft Error Lookup Tool

 Microsoft Error Lookup is a lightweight command-line tool. You don’t need a copious amount of system resources to run it on your system. Here’s how to download and set up the tool on your system:

### 1\. Downloading and Renaming the Tool

 Repeat the following steps to download and install the Microsoft Error Lookup tool:

1. Launch a web browser on your system and visit the [Microsoft Error Lookup Tool download page](https://www.microsoft.com/en-us/download/details.aspx?id=100432) .
2. Scroll down and click on the Download button. It will take a few seconds for the download to complete.
3. Press**Win + E** to [launch the File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to the Microsoft Error Lookup Tool executable file download location.
4. Since it is a command-line tool, you will have to run it by typing its full name. The default download name is**Err\_6.4.5** which will be trouble to remember and type correctly every time in the Command Prompt. So, we will rename it to something easier like**Err** .
5. Right-click on the Microsoft Error Lookup tool executable file and select**Show more options** .  
![Renaming Microsoft Error Lookup Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/renaming-microsoft-error-lookup-tool.jpg)
6. Then, click on the**Rename** option from the context menu. Type**Err** and press the enter key to rename the tool.

### 2\. Placing the Tool in a Convenient Location

 You can only run the Microsoft Error Lookup Tool from the command line. If you place it in a deeply nested path like a folder inside a directory, you will have to navigate to that directory from the command line every time. So, you must move the tool to an accessible location first.

Here’s how to do it:

1. Press**Win + E** to open File Explorer and navigate to the Microsoft Error Lookup Tool download location. Now, press**Ctrl + C** to copy the file.
2. Go to the C drive and paste the tool. Grant permissions to place the tool in C drive.  
![Placing Microsoft Error Lookup Tool in C drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/placing-microsoft-error-lookup-tool-in-c-drive.jpg)
3. Now, press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** in the text box and press enter key.
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
![Exporting Error Code Lookup results in a text file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/exporting-error-code-lookup-results-in-a-text-file.jpg)

 Now, open the file, and you can read the entire list of error code results and begin troubleshooting.

## Can the Microsoft Error Lookup Tool Display Information About All Error Codes?

 Microsoft updates the tool to the latest version in 2019\. Since then, it hasn’t received an update. So, as newer builds or a [new version of Windows](https://www.makeuseof.com/windows-12-improve-upon-windows-11/) comes out, the tool may fail to produce results for a specific error code. But the chances of that are very slim. Moreover, it contains information only about Windows and some other Microsoft error codes. Don’t expect it to display information about errors you face inside a third-party application or program.

 So, you can use the error lookup tool without any worries and patiently wait for Microsoft to release a new build. You can check for the latest available build by visiting the official download page of the Microsoft Error Lookup Tool. Or, you can try a bunch of third-party options like Winerr or Error Lookup Tool for a more presentable error code lookup and troubleshooting experience.

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
<li><a href="https://win11-tips.techidaily.com/instantaneous-transcription-experience-with-whisper-desktop/"><u>Instantaneous Transcription Experience with Whisper Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-classic-diablo-a-beginners-guide/"><u>Mastering Classic Diablo: A Beginner's Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-network-address-translation-win1110-edition-explained/"><u>Navigating Network Address Translation: Win11/10 Edition Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harnessing-windows-oversight-on-apps-browsers/"><u>Harnessing Windows Oversight on Apps, Browsers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-the-non-verified-error-during-windows-file-installation/"><u>Solving the Non-Verified Error During Windows File Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-sticky-notes-display-on-win-11/"><u>Mastering the Art of Sticky Notes Display on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-management-navigating-taskbar-with-windows-hotkeys/"><u>Effortless Management: Navigating Taskbar with Windows Hotkeys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-packages-on-pc-the-choco-way-or-wm-approach/"><u>Navigating Packages on PC: The Choco Way or WM Approach</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/spotlight-on-stories-crafting-three-effective-highlights-for-2024/"><u>Spotlight on Stories  Crafting Three Effective Highlights for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-the-essential-review-of-screen-recorders-for-mp4-for-2024/"><u>[New] The Essential Review of Screen Recorders for MP4 for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/planning-to-use-a-pokemon-go-joystick-on-nokia-c12-pro-drfone-by-drfone-virtual-android/"><u>Planning to Use a Pokemon Go Joystick on Nokia C12 Pro? | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-revive-your-bricked-oneplus-12-in-minutes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Revive Your Bricked OnePlus 12 in Minutes | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-rookie-riches-profitable-sites-for-beginnere-buyouts/"><u>In 2024, Rookie Riches  Profitable Sites for Beginner'e Buyouts</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-explore-a-variety-of-inexpensive-camera-models-suitable-for-making-slow-motion-footage-without-compromising-quality/"><u>New Explore a Variety of Inexpensive Camera Models Suitable for Making Slow-Motion Footage without Compromising Quality</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-expert-list-superior-gaming-live-options/"><u>2024 Approved  Expert List  Superior Gaming Live Options</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-the-process-of-purging-audio-content-in-the-latest-avi-codec-for-2024/"><u>New The Process of Purging Audio Content in the Latest AVI Codec for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-the-ultimate-guide-to-vignette-apps-free-and-paid-options-for-ios-and-android-for-2024/"><u>Updated The Ultimate Guide to Vignette Apps Free and Paid Options for iOS and Android for 2024</u></a></li>
</ul></div>