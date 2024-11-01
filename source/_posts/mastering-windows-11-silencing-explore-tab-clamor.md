---
title: "Mastering Windows 11: Silencing Explore Tab Clamor"
date: 2024-10-29T19:05:24.467Z
updated: 2024-11-01T16:20:08.697Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Windows 11: Silencing Explore Tab Clamor"
excerpt: "This Article Describes Mastering Windows 11: Silencing Explore Tab Clamor"
keywords: Win11 Mastery Guide,Silence Explorer Tabs,Windows Control Skills,PC Explore Noise Solution,Navigate Windows Efficiently,Clamor in Windows Techniques,Optimize WIndows 11 Use
thumbnail: https://thmb.techidaily.com/a6603b4c8e64882a75258ea91034b33184d3edc319264524a7b728bfe67ef7f7.jpg
---

## Mastering Windows 11: Silencing Explore Tab Clamor

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
<a href="https://appsumo.8odi.net/c/5597632/2044586/7443" target="_top" id="2044586">
  <img src="//a.impactradius-go.com/display-ad/7443-2044586" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2044586/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2123738/7443" target="_top" id="2123738">
  <img src="//a.impactradius-go.com/display-ad/7443-2123738" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123738/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

vivetool /disable /id:37634385  
vivetool /disable /id:36354489
6. You will see the “**Successfully set feature configuration(s)** ” if the command executes successfully.
7. Now,**restart** your system for the changes to take effect. The File Explorer Tabs feature will no longer be active on your system.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136624/26400" target="_top" id="2136624">
  <img src="//a.impactradius-go.com/display-ad/26400-2136624" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136624/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1576474/17382" target="_top" id="1576474">
  <img src="//a.impactradius-go.com/display-ad/17382-1576474" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1576474/17382" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-essential-skills-for-successful-interviews/"><u>[New] 2024 Approved Essential Skills for Successful Interviews</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-unique-gifting-made-simple-discover-top-10-custom-box-sellers-for-2024/"><u>[New] Unique Gifting Made Simple Discover Top 10 Custom Box Sellers for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-in-2024-first-steps-to-successful-vlogging-essentials/"><u>[Updated] In 2024, First Steps to Successful Vlogging Essentials</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-leap-into-virtual-gatherings-xbox-zoom-mastery/"><u>[Updated] Leap Into Virtual Gatherings Xbox Zoom Mastery</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-androids-power-to-replay-film-slices/"><u>2024 Approved Android's Power to Replay Film Slices</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-top-8-speed-upters-accelerate-your-android-media/"><u>2024 Approved Top 8 Speed Upters - Accelerate Your Android Media</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-win-error-logs-post-blue-screen/"><u>Deciphering Win Error Logs Post-Blue Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-webp-savings-steps-for-changing-chrome-image-format-on-windows/"><u>Eliminate WebP Savings: Steps for Changing Chrome Image Format on Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-7-phone-number-locators-to-track-infinix-smart-8-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Phone Number Locators To Track Infinix Smart 8 Location | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-top-notch-solutions-for-disabled-apple-id-from-apple-iphone-8-making-it-possible-by-drfone-ios/"><u>In 2024, Top-Notch Solutions for Disabled Apple ID From Apple iPhone 8 Making It Possible</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-depth-cost-analysis-for-new-podcasters/"><u>In-Depth Cost Analysis for New Podcasters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/nullifying-windows-update-notifications/"><u>Nullifying Windows Update Notifications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-windows-update-settings-quickly/"><u>Reviving Windows Update Settings Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slowing-the-spree-of-lifes-speed-in-your-windowed-world/"><u>Slowing the Spree of Life’s Speed in Your Windowed World</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-nvidia-cp-unauthorized-access-on-windows/"><u>Solving Nvidia CP Unauthorized Access on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-fix-guide-to-replace-msvcr120dll-in-windows/"><u>Step-by-Step Fix Guide to Replace MSVCR120.dll in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-tackle-vac-refusal-message-on-pc/"><u>Steps to Tackle VAC Refusal Message on PC</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-art-of-edible-entertainment-7-steps-to-perfect-plating-on-camera/"><u>The Art of Edible Entertainment 7 Steps to Perfect Plating on Camera</u></a></li>
<li><a href="https://win11-tips.techidaily.com/voice-to-text-made-easy-with-openais-whisper-in-your-windows-environment/"><u>Voice-to-Text Made Easy With OpenAI's Whisper in Your Windows Environment</u></a></li>
</ul></div>

