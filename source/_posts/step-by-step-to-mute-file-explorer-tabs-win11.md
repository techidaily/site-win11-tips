---
title: Step-by-Step to Mute File Explorer Tabs Win11
date: 2024-11-14T16:08:02.685Z
updated: 2024-11-17T17:25:03.696Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Step-by-Step to Mute File Explorer Tabs Win11
excerpt: This Article Describes Step-by-Step to Mute File Explorer Tabs Win11
keywords: Muting Explorer Tabs W11,Windows File Tab Mute,Silence Tab Noise,Mute Explorer Sounds,Quieten Explore WIN11,Turn Off Windows Files Sound,Suppress File Explorer Audio
thumbnail: https://thmb.techidaily.com/795e21b2952dac96e4f9316f33c867f4d5e9a26e7b970dc3ae9c242e74e0d377.jpg
---

## Step-by-Step to Mute File Explorer Tabs Win11

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
<a href="https://25home.pxf.io/c/5597632/2148650/16836" target="_top" id="2148650">
  <img src="//a.impactradius-go.com/display-ad/16836-2148650" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148650/16836" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1983582">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983582.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983582">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983582.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983582%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983582/22993" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2145009/26400" target="_top" id="2145009">
  <img src="//a.impactradius-go.com/display-ad/26400-2145009" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2145009/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Now, close the ViVeTool GUI and**restart** your system.
6. Open the File Explorer and you won’t see the tabs feature anymore.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1175223/12108" target="_top" id="1175223">
  <img src="//a.impactradius-go.com/display-ad/12108-1175223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1175223/12108" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-videos.techidaily.com/new-social-media-connectivity-embedding-live-streams-from-twitch-to-fb/"><u>[New] Social Media Connectivity Embedding Live Streams From Twitch to FB</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-hololens-review-pioneering-virtual-spacecraft/"><u>[Updated] HoloLens Review Pioneering Virtual Spacecraft</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-and-confident-windows-viewing-top-6-fixes-now/"><u>Clear and Confident Windows Viewing: Top 6 Fixes Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/devhomes-blueprint-for-cutting-edge-w11-living/"><u>DevHome's Blueprint for Cutting-Edge W11 Living</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/enhance-conversions-using-our-advanced-cookiebot-features/"><u>Enhance Conversions Using Our Advanced Cookiebot Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-to-ensure-your-surfaces-software-stays-current/"><u>Expert Tips to Ensure Your Surface's Software Stays Current</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-unsuccessful-execution-of-high-privileges-tasks/"><u>Fixing Unsuccessful Execution of High Privileges Tasks</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/forgotten-the-voicemail-password-of-poco-x6-try-these-fixes-by-drfone-android/"><u>Forgotten The Voicemail Password Of Poco X6? Try These Fixes</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-do-you-play-mkv-files-on-xiaomi-redmi-12-5g-by-aiseesoft-video-converter-play-mkv-on-android/"><u>How do you play MKV files on Xiaomi Redmi 12 5G?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-uncover-hidden-5ghz-networks-in-windows-11-using-7-tips/"><u>How to Uncover Hidden 5GHz Networks in Windows 11 Using 7 Tips</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-how-to-stabilize-iphone-videos-3-ways/"><u>In 2024, How to Stabilize iPhone Videos? [3-Ways]</u></a></li>
<li><a href="https://extra-skills.techidaily.com/master-your-chromebooks-pitch-and-tone-with-our-top-5-web-tools-for-2024/"><u>Master Your Chromebook's Pitch and Tone with Our Top 5 Web Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-quick-fixes-to-common-windows-11-problems/"><u>Mastering Quick FIXES to Common Windows 11 Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-windows-update-error-0x80073712/"><u>Quick Fix for Windows Update: Error 0X80073712</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/review-of-the-stanley-j5c09-a-powerful-workhorse-for-heavy-duty-tasks/"><u>Review of the Stanley J5C09 - A Powerful Workhorse for Heavy Duty Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-integration-of-files-in-win-11-os/"><u>Seamless Integration of Files in Win 11 OS</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/unlock-your-charm-personalized-youtube-channel-url-essentials-for-2024/"><u>Unlock Your Charm Personalized YouTube Channel URL Essentials for 2024</u></a></li>
</ul></div>

