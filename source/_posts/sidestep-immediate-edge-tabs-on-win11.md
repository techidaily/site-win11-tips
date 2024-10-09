---
title: Sidestep Immediate Edge Tabs on Win11
date: 2024-10-05T19:58:09.138Z
updated: 2024-10-09T00:42:40.393Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Sidestep Immediate Edge Tabs on Win11
excerpt: This Article Describes Sidestep Immediate Edge Tabs on Win11
keywords: Win11 Tab Avoidance,Edge Skip in Windows,Sidestep Edge Tabs,Disable Edge Quick Access,Win11 Edge Control,Windows Tab Shortcuts,Prevent Edge Pop-Ups
thumbnail: https://thmb.techidaily.com/918ad49eae4bb09e7bbe637c097999923379261d114b5800bdb87d98b552aa6d.jpg
---

## Sidestep Immediate Edge Tabs on Win11

 Microsoft Edge is the default browser in Windows and comes pre-installed on the operating system without any easy way of getting rid of it. The browser uses "tab preloading," which preloads the Start and New Tab page while you sign in to your PC.

 For Edge lovers, it is a boon, but if you don’t use the default browser and prefer something else, it is a waste of resources. Fortunately, you can easily disable Edge's tab preloading in Windows 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Disable Edge Tab Preloading Using the Group Policy Editor

 Windows Pro, Education, and Enterprise users get the perks of the Group Policy Editor by default. You can use it to configure system policies on your PC and personalize it. If you're on Windows Home, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

 Repeat the following steps to disable Edge tab preloading using the Group Policy Editor:

1. Press **Win + S** to open Windows Search. Type **gpedit.msc** in the text box and press the **Enter** key to open the Group Policy Editor.
2. Click on the **User Configuration** option in the left-hand side pane.
3. Navigate to **Administrative Templates > Windows Components > Microsoft Edge**.
4. Find the “**Allow Microsoft Edge to start and load the Start and New Tab page at Windows startup and each time Microsoft Edge is closed**” policy. Right-click on it and select the **Edit** option from the context menu.  
![Disable Microsoft Edge Tab Preloading Using GPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-gpe.jpg)
5. Click on the **Enabled** radio button.
6. Scroll down and click on the drop-down list next to the **Configure tab preloading** option. Select the **Prevent tab preloading** option.
7. Click on the **Apply** button. Then click on the **OK** button to save the changes.  
![Disable Microsoft Edge Tab Preloading Using GPE 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-gpe-2.jpg)
8. **Exit** the Group Policy Editor window.
9. **Restart** your PC for the policy changes to take effect and disable the tab preloading feature.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657395/16446" target="_top" id="1657395">
  <img src="//a.impactradius-go.com/display-ad/16446-1657395" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657395/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. How to Disable Edge Tab Preloading Using the Registry Editor

 If you use the Home version of Windows 11, it may be easier to take a different approach instead of going through the Group Policy Editor method. If you want, you can tweak the registry manually to disable the Edge tab preloading feature in Windows 11\. Repeat the following steps to do so:

 Before making changes to the Windows Registry, [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) for safety purposes.

1. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **regedit** in the text box and press the **Enter** key.
2. Go to the address bar at the top and click on it. Paste the following path in the text box and press the **Enter** key:  
HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\MicrosoftEdge\Main
3. Go to the right-hand side section and right-click on the empty area. Select **New > DWORD (32-bit) Value**.
4. Click on the newly created DWORD value and name it “**AllowPrelaunch**”.
5. Right-click on the **AllowPrelaunch** value and select the **Modify** option from the context menu.
6. Go to the **Value Data** field and type **0** in it. Set the **Base** to **Hexadecimal** and click on the **OK** button.  
![Disable Microsoft Edge Tab Preloading Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-registry-editor.jpg)

 Now, you need to create a new subkey and add a new DWORD value:

1. Right-click on the Microsoft Edge key and select the **New > Key** option.
2. Name the key “**TabPreloader**” and click on it to select it.
3. Go to the right-hand side section and right-click on it. Select **New > DWORD (32-bit) Value**.
4. Click on the DWORD value and name it “**AllowTabPreloading**”.
5. Right-click on the **AllowTabPreloading** value and select the **Modify** option.
6. Go to the **Value Data** field and type **0** in it. Set the **Base** to **Hexadecimal** and click on the **OK** button.  
![Disable Microsoft Edge Tab Preloading Using Registry Editor 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-registry-editor-2.jpg)
7. **Close** the Registry Editor window.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012434/19272" target="_top" id="2012434">
  <img src="//a.impactradius-go.com/display-ad/19272-2012434" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012434/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

8. **Restart** your PC to apply the changes made to the registry.

## 3\. How to Disable Edge Tab Preloading Using CMD or PowerShell

 If you find the Registry Editor method too cumbersome, you can use the Command Prompt or PowerShell to modify the Registry and disable Edge tab preloading. Here’s how to do it:

1. [Open the Command Prompt with administrator privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/) on your PC.
2. Execute the following commands to add two new registry entries:  
`reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\MicrosoftEdge\Main" /v AllowPrelaunch /t REG_DWORD /d 00000000 /f  
 reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\MicrosoftEdge\TabPreloader" /v AllowTabPreloading /t REG_DWORD /d 00000000 /f`
3. **Close** the Command Prompt window and **restart** your PC.  
![Disable Microsoft Edge Tab Preloading Using CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-cmd.jpg)

## 4\. How to Disable Edge Tab Preloading Using the Ultimate Windows Tweaker App

 You can also use a third-party app like the Ultimate Windows Tweaker to disable Edge tab preloading in Windows 11\. Download the [Ultimate Windows Tweaker](https://www.thewindowsclub.com/ultimate-windows-tweaker-4-windows-10) app and install it on your PC. After that, repeat the following steps:

1. Press **Win + S** to open the Windows Search app. Type **Ultimate Windows Tweaker** and then click on the **Run as administrator** option.
2. Click on the **Search For Tweaks** option. Type “**edge tab**” in the search box and click on the **Go** button.  
![Disable Microsoft Edge Tab Preloading Using Ultimate Windows Tweaker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-ultimate-windows-tweaker.jpg)
3. Click on the **Disable Edge Tab Preloading** checkbox to enable it. Then, click on the **Apply Tweaks** button.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938677/19272" target="_top" id="1938677">
  <img src="//a.impactradius-go.com/display-ad/19272-1938677" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938677/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Disable Microsoft Edge Tab Preloading Using Ultimate Windows Tweaker 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-ultimate-windows-tweaker-2.jpg)
4. **Close** the Ultimate Windows Tweaker app and **restart** your PC to apply the changes.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915870/19272" target="_top" id="1915870">
  <img src="//a.impactradius-go.com/display-ad/19272-1915870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915870/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Disable Edge Tab Preloading for Good on Windows 11

 Edge tab preloading serves no useful purpose if you use other browsers. You can disable it using the Group Policy Editor or the Registry Editor. Lastly, if you want a GUI app to disable the feature, you can use the Ultimate Windows Tweaker app.

 For Edge lovers, it is a boon, but if you don’t use the default browser and prefer something else, it is a waste of resources. Fortunately, you can easily disable Edge's tab preloading in Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-a-step-by-step-framework-for-transcribing-whatsapp-calls/"><u>[New] 2024 Approved A Step-by-Step Framework for Transcribing WhatsApp Calls</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-the-journey-to-origin-how-to-utilize-reverse-image-functionality-on-instagram-for-2024/"><u>[New] The Journey to Origin How to Utilize Reverse Image Functionality on Instagram for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-adsense-on-youtube-determining-your-income-from-1k-viewer-engagement/"><u>[Updated] 2024 Approved AdSense on YouTube Determining Your Income From 1K Viewer Engagement</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-az-video-logger-full-application-scrutiny/"><u>[Updated] 2024 Approved AZ Video Logger - Full Application Scrutiny</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-three-ways-to-make-your-instagram-videos-pop-with-captions/"><u>[Updated] In 2024, Three Ways to Make Your Instagram Videos Pop with Captions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-your-commands-making-terminal-default/"><u>Elevating Your Commands: Making Terminal Default</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-too-many-background-processes-running-on-a-windows-pc/"><u>How to Fix Too Many Background Processes Running on a Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-revive-nonworking-google-nearby-share-on-pc/"><u>How To Revive Nonworking Google Nearby Share on PC</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-a-found-iphone-15-drfone-by-drfone-ios/"><u>In 2024, How To Unlock A Found iPhone 15? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-online-efficiency-an-in-depth-guide-to-copernics-desktop-and-cloud-search-tools/"><u>Mastering Online Efficiency: An In-Depth Guide to Copernic's Desktop and Cloud Search Tools</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-do-you-want-to-discover-how-to-stabilize-a-video-are-you-in-search-of-the-finest-tools-to-establish-this-task-step-into-this-article-to-explore-the-exci/"><u>New Do You Want to Discover How to Stabilize a Video? Are You in Search of the Finest Tools to Establish This Task? Step Into This Article to Explore the Exciting Facts About It</u></a></li>
<li><a href="https://video-capture.techidaily.com/reimagining-video-production-with-screenflow-a-mac-users-guide/"><u>Reimagining Video Production with ScreenFlow – A Mac User's Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-stop-vmware-blue-screen-errors-on-win11/"><u>Steps to Stop VMware Blue Screen Errors on Win11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/the-blueprint-for-youtube-educational-video-success-stories-for-2024/"><u>The Blueprint for YouTube Educational Video Success Stories for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-solutions-to-windows-obs-studio-non-launch-problems/"><u>Unveiling Solutions to Windows OBS Studio Non-Launch Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-tips-discovering-and-eliminating-blank-folder-clutter/"><u>Windows Tips: Discovering & Eliminating Blank Folder Clutter</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    