---
title: Hush Win11's File Explorer Tab Interruptions
date: 2024-10-13T16:32:31.637Z
updated: 2024-10-14T17:44:29.181Z
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

## How to Disable File Explorer Tabs In Windows 11

 You can disable the File Explorer Tabs by either using the ViVeTool or the ViVeTool GUI version. The latter is much simpler to use because you can search for a feature and activate or deactivate it in one click. But before doing that, download and install both of these tools on your system. Also,[create a system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) for added precaution, in case the tool wrecks something on your Windows 11 computer.

**Download:** [ViVeTool](https://github.com/thebookisclosed/ViVe/releases)

**Download:** [ViVeTool GUI](https://github.com/PeterStrick/ViVeTool-GUI/releases)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136615/26400" target="_top" id="2136615">
  <img src="//a.impactradius-go.com/display-ad/26400-2136615" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136615/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 1\. Disable File Explorer Tabs Using the ViVeTool

 Since it is a command line tool, you can access it from a terminal window. Here’s how to do it:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**CMD** in the text input area and press**Ctrl + Shift + Enter** key to launch the command prompt with administrator privileges.
3. Type**cd Drive Name:\\path** . Here, you need to enter the exact location where you extracted the tool after downloading it. For example, we extracted it to a folder name Vive in C drive. So, our command is**cd C:\\Vive** .
4. Now, you will be in the directory where ViVeTool exists. Type**vivetool** and press the**Enter** key. You will see a bunch of parameters you can use with the tool.  
![Disable File Explorer Tabs Using the ViVeTool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool.jpg)
5. Type the following two commands, one by one in the CMD and press the**Enter** key.  

vivetool /disable /id:37634385  
vivetool /disable /id:36354489
6. You will see the “**Successfully set feature configuration(s)** ” if the command executes successfully.
7. Now,**restart** your system for the changes to take effect. The File Explorer Tabs feature will no longer be active on your system.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135403/19272" target="_top" id="2135403">
  <img src="//a.impactradius-go.com/display-ad/19272-2135403" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135403/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Disable File Explorer Tabs Using the ViVeTool GUI version

 The GUI version of ViVeTool works similarly. You can manually enter the feature ID or use the search function to find a feature in the list. Repeat the following steps to disable File Explorer Tabs using the ViVeTool GUI.

1. Launch the ViVeTool GUI with admin privileges.
2. Click on the drop-down list and select the latest Windows build number. Wait for the tool to list all the feature IDs available for the Windows build.
3. Type**37634385** in the search bar. Select the highlighted feature and click on the**Perform Action** button.  
![Disable File Explorer Tabs Using the ViVeTool GUI version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool-gui-version.jpg)
4. Select the**Deactivate Feature** option. Similarly, find the feature ID**36354489** and deactivate it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027181/19272" target="_top" id="2027181">
  <img src="//a.impactradius-go.com/display-ad/19272-2027181" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027181/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Now, close the ViVeTool GUI and**restart** your system.
6. Open the File Explorer and you won’t see the tabs feature anymore.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118306/7443" target="_top" id="2118306">
  <img src="//a.impactradius-go.com/display-ad/7443-2118306" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118306/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-files.techidaily.com/new-thriving-in-the-digital-age-mastering-facebook-interaction/"><u>[New] Thriving in the Digital Age Mastering Facebook Interaction</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-top-picks-video-grabbers-on-microsofts-os/"><u>[New] Top Picks Video Grabbers on Microsoft's OS</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/approved-youtube-income-101-from-ideas-to-earnings-in-action/"><u>2024 Approved YouTube Income 101 From Ideas to Earnings in Action</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-can-life360-track-or-see-text-messages-what-can-you-do-with-life360-on-realme-note-50-drfone-by-drfone-virtual-android/"><u>In 2024, Can Life360 Track Or See Text Messages? What Can You Do with Life360 On Realme Note 50? | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-high-quality-speech-to-text-solutions/"><u>In 2024, High-Quality Speech-to-Text Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-obstacles-with-the-malfunctioning-google-nearby-sharing/"><u>Overcoming Obstacles with the Malfunctioning Google Nearby Sharing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-ending-windows-gpsvc-delays/"><u>Quick Guide: Ending Windows GPSVC Delays</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snippet-savvy-crafting-custom-keybinds-for-speed-and-precision-in-win11/"><u>Snippet Savvy: Crafting Custom Keybinds for Speed & Precision in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-runtime-broker-a-key-to-optimized-pc-operations/"><u>Understanding Runtime Broker: A Key to Optimized PC Operations</u></a></li>
</ul></div>

