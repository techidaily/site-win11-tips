---
title: Hush Win11's File Explorer Tab Interruptions
date: 2024-10-02T20:12:05.407Z
updated: 2024-10-08T21:31:27.685Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Hush Win11's File Explorer Tab Interruptions
excerpt: This Article Describes Hush Win11's File Explorer Tab Interruptions
keywords: Hush Win11 Disruption,File Explore Glitches,Hush Win11 Issues,Win11 File Problems,Explorer Tab Interruptions,Unstable Explorer Win11,Fixing Hush File Irritation
thumbnail: https://thmb.techidaily.com/6ea9e47c2657fcc7075624e0c60b4b097654c22032956cf343f01ab1f87ea6c8.jpg
---

## Hush Win11's File Explorer Tab Interruptions

 Microsoft was hoping to launch the tabs feature in the File Explorer app for Windows 10\. But it scrapped the idea later on. However, with the Windows 11 22H2 update, users can now try out the tabs feature in File Explorer. The participants of the Windows Insider Program got early access to the feature and Microsoft could soon apply the tabs idea to Windows Notepad as well.

 But what if you want to turn the File Explorer Tabs feature off? An immediate idea would be to uninstall the update, but that is a temporary workaround. You can use ViVeTool to enable or disable the tabs feature or any other new feature of Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is ViVeTool?

 ViVeTool is an open-source command line tool that can enable or disable Windows operating system features. Microsoft continuously works on many experimental features and does a lot of testing before rolling out a stable version of a feature. But if you are impatient, you can use ViVeTool to enable an otherwise hidden feature. It is free and the developers recently launched a GUI version of the tool as well.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130530/26400" target="_top" id="2130530">
  <img src="//a.impactradius-go.com/display-ad/26400-2130530" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130530/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Disable File Explorer Tabs In Windows 11

 You can disable the File Explorer Tabs by either using the ViVeTool or the ViVeTool GUI version. The latter is much simpler to use because you can search for a feature and activate or deactivate it in one click. But before doing that, download and install both of these tools on your system. Also,[create a system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) for added precaution, in case the tool wrecks something on your Windows 11 computer.

**Download:** [ViVeTool](https://github.com/thebookisclosed/ViVe/releases)

**Download:** [ViVeTool GUI](https://github.com/PeterStrick/ViVeTool-GUI/releases)

<!-- affiliate ads begin -->
<span id="1977032">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977032.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977032">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977032.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977032%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977032/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 1\. Disable File Explorer Tabs Using the ViVeTool

 Since it is a command line tool, you can access it from a terminal window. Here’s how to do it:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**CMD** in the text input area and press**Ctrl + Shift + Enter** key to launch the command prompt with administrator privileges.
3. Type**cd Drive Name:\\path** . Here, you need to enter the exact location where you extracted the tool after downloading it. For example, we extracted it to a folder name Vive in C drive. So, our command is**cd C:\\Vive** .
4. Now, you will be in the directory where ViVeTool exists. Type**vivetool** and press the**Enter** key. You will see a bunch of parameters you can use with the tool.  
![Disable File Explorer Tabs Using the ViVeTool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool.jpg)
5. Type the following two commands, one by one in the CMD and press the**Enter** key.  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2145009/26400" target="_top" id="2145009">
  <img src="//a.impactradius-go.com/display-ad/26400-2145009" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2145009/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

vivetool /disable /id:37634385  
vivetool /disable /id:36354489
6. You will see the “**Successfully set feature configuration(s)** ” if the command executes successfully.
7. Now,**restart** your system for the changes to take effect. The File Explorer Tabs feature will no longer be active on your system.

### 2\. Disable File Explorer Tabs Using the ViVeTool GUI version

 The GUI version of ViVeTool works similarly. You can manually enter the feature ID or use the search function to find a feature in the list. Repeat the following steps to disable File Explorer Tabs using the ViVeTool GUI.

1. Launch the ViVeTool GUI with admin privileges.
2. Click on the drop-down list and select the latest Windows build number. Wait for the tool to list all the feature IDs available for the Windows build.
3. Type**37634385** in the search bar. Select the highlighted feature and click on the**Perform Action** button.  
![Disable File Explorer Tabs Using the ViVeTool GUI version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool-gui-version.jpg)
4. Select the**Deactivate Feature** option. Similarly, find the feature ID**36354489** and deactivate it.
5. Now, close the ViVeTool GUI and**restart** your system.
6. Open the File Explorer and you won’t see the tabs feature anymore.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134243/18498" target="_top" id="2134243">
  <img src="//a.impactradius-go.com/display-ad/18498-2134243" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134243/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Disable Any Windows 11 Feature Using ViVeTool

 File Explorer tabs are more useful than you think. But if you use another File Explorer program or can make do without it, ViVeTool is a great utility to disable/enable it. Moreover, it is completely free, and you can even enable other experimental features of Windows 11.

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
<li><a href="https://extra-support.techidaily.com/new-standing-out-on-airwaves-podcast-brand-logo-tips/"><u>[New] Standing Out on Airwaves Podcast Brand Logo Tips</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-creative-video-ends-top-6-budget-friendly-options/"><u>[Updated] 2024 Approved Creative Video Ends Top 6 Budget-Friendly Options</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-the-quick-guide-to-instagrams-magnification-magic/"><u>[Updated] In 2024, The Quick Guide to Instagram's Magnification Magic</u></a></li>
<li><a href="https://tech-hub.techidaily.com/can-computers-predict-your-future-like-astrology/"><u>Can Computers Predict Your Future Like Astrology?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-code-fixing-windows-11-emails-html-anomalies/"><u>Decoding the Code: Fixing Windows 11 Email's HTML Anomalies</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-enhanced-performance-comprehensive-msi-z370-a-pro-drivers/"><u>Download Enhanced Performance: Comprehensive MSI Z370-A Pro Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-turn-your-voice-into-text-with-openais-whisper-for-windows/"><u>How to Turn Your Voice Into Text With OpenAI’s Whisper for Windows</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-mastering-the-procedure-of-attaining-facebooks-blue-status-badge/"><u>In 2024, Mastering the Procedure of Attaining Facebook's Blue Status Badge</u></a></li>
<li><a href="https://win11-tips.techidaily.com/liberating-windows-dialogue-with-freedomgpt-engagement/"><u>Liberating Windows Dialogue: With FreedomGPT Engagement</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/mastering-the-art-of-invisible-viewership-on-instagram-live-for-2024/"><u>Mastering the Art of Invisible Viewership on Instagram Live for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-split-view-failures-in-win-10/"><u>Tackling Split View Failures in Win 10</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/the-entrepreneurs-guide-to-youtube-earnings-thriving-without-ad-support-for-2024/"><u>The Entrepreneur’s Guide to YouTube Earnings Thriving Without Ad Support for 2024</u></a></li>
</ul></div>

