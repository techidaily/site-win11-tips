---
title: "Master Silence on Windows 11: Shut Down Tabs"
date: 2024-12-18T19:37:29.312Z
updated: 2024-12-21T18:33:17.079Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Master Silence on Windows 11: Shut Down Tabs"
excerpt: "This Article Describes Master Silence on Windows 11: Shut Down Tabs"
keywords: Mastering Silence (Windows),W11 Quiet Mode,Tab Shutdown Guide,Silent PC Tuning,Windows 11 Peace,Focus Tabs Control,Noise Reduction W11
thumbnail: https://thmb.techidaily.com/bc2d4277b292ae7f5948b4f932bd10c3a9f77d53f80591ecadf09ffda8a120cc.jpg
---

## Master Silence on Windows 11: Shut Down Tabs

 Microsoft was hoping to launch the tabs feature in the File Explorer app for Windows 10\. But it scrapped the idea later on. However, with the Windows 11 22H2 update, users can now try out the tabs feature in File Explorer. The participants of the Windows Insider Program got early access to the feature and Microsoft could soon apply the tabs idea to Windows Notepad as well.

 But what if you want to turn the File Explorer Tabs feature off? An immediate idea would be to uninstall the update, but that is a temporary workaround. You can use ViVeTool to enable or disable the tabs feature or any other new feature of Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jpdGEJJwMLY?si=eKgXOPpNeYvYKcel" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Is ViVeTool?

 ViVeTool is an open-source command line tool that can enable or disable Windows operating system features. Microsoft continuously works on many experimental features and does a lot of testing before rolling out a stable version of a feature. But if you are impatient, you can use ViVeTool to enable an otherwise hidden feature. It is free and the developers recently launched a GUI version of the tool as well.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tPgf_wSdhS8?si=BHoH1ryaxmwk-8FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Disable File Explorer Tabs In Windows 11

 You can disable the File Explorer Tabs by either using the ViVeTool or the ViVeTool GUI version. The latter is much simpler to use because you can search for a feature and activate or deactivate it in one click. But before doing that, download and install both of these tools on your system. Also,[create a system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) for added precaution, in case the tool wrecks something on your Windows 11 computer.

**Download:** [ViVeTool](https://github.com/thebookisclosed/ViVe/releases)

**Download:** [ViVeTool GUI](https://github.com/PeterStrick/ViVeTool-GUI/releases)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KF793jv1LIc?si=fJOogQJ2f8JUfTzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

### 2\. Disable File Explorer Tabs Using the ViVeTool GUI version

 The GUI version of ViVeTool works similarly. You can manually enter the feature ID or use the search function to find a feature in the list. Repeat the following steps to disable File Explorer Tabs using the ViVeTool GUI.

1. Launch the ViVeTool GUI with admin privileges.
2. Click on the drop-down list and select the latest Windows build number. Wait for the tool to list all the feature IDs available for the Windows build.
3. Type**37634385** in the search bar. Select the highlighted feature and click on the**Perform Action** button.  
![Disable File Explorer Tabs Using the ViVeTool GUI version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool-gui-version.jpg)
4. Select the**Deactivate Feature** option. Similarly, find the feature ID**36354489** and deactivate it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Now, close the ViVeTool GUI and**restart** your system.
6. Open the File Explorer and you won’t see the tabs feature anymore.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/f-yPCh24EsA?si=3z8FAd_lMZeAjug7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-content.techidaily.com/new-your-ultimate-guide-to-accessing-facebook-content-on-applemedia-hub-for-2024/"><u>[New] Your Ultimate Guide to Accessing Facebook Content on AppleMedia Hub for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-creative-image-collage-tools-ranked-10/"><u>[Updated] Creative Image Collage Tools Ranked #10</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-leveraging-spotifys-features-a-marketing-gamechanger-guide/"><u>[Updated] Leveraging Spotify’s Features A Marketing Gamechanger Guide</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-twitters-best-binge-friends-amazon-primes-most-liked-shows-23-for-2024/"><u>[Updated] Twitter's Best Binge-Friends Amazon Prime's Most Liked Shows, '23 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-missing-camera-device-manager-hurdle/"><u>Fix Missing Camera: Device Manager Hurdle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-common-blue-screen-error-iomap64-syscall-issues-on-windows/"><u>Fixing Common Blue Screen Error: IOMap64 Syscall Issues on Windows</u></a></li>
<li><a href="https://screen-capture.techidaily.com/focused-communication-tips-for-virtual-teams-for-2024/"><u>Focused Communication Tips for Virtual Teams for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-turn-off-google-location-to-stop-tracking-you-on-xiaomi-redmi-note-13-5g-drfone-by-drfone-virtual-android/"><u>How to Turn Off Google Location to Stop Tracking You on Xiaomi Redmi Note 13 5G | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-locked-iphone-xs-by-restoring-by-drfone-ios-unlock-ios-unlock/"><u>How to Unlock locked iPhone XS by restoring</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-in-use-errors-efficiently-organize-your-windows-devices/"><u>Resolve 'In Use' Errors: Efficiently Organize Your Windows Devices</u></a></li>
<li><a href="https://screen-capture.techidaily.com/techcapture-pro-a-comprehensive-2023-study/"><u>TechCapture Pro A Comprehensive 2023 Study</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveil-concealed-5ghz-links-with-top-tips-for-windows-11/"><u>Unveil Concealed 5GHz Links with Top Tips for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-with-wsl-2-critical-practices-for-developers/"><u>Winning with WSL 2: Critical Practices for Developers</u></a></li>
</ul></div>

