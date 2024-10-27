---
title: Keep Upgrades at Bay with These 4 Tips
date: 2024-10-20T22:45:53.206Z
updated: 2024-10-26T17:23:33.945Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Keep Upgrades at Bay with These 4 Tips
excerpt: This Article Describes Keep Upgrades at Bay with These 4 Tips
keywords: Avoid Upgrade Issues,Stable System Maintenance,Prevent Software Glitches,Tips for Tech Sustainability,Keeping Devices Updated,Maintaining Latest Systems,Software Update Strategies
thumbnail: https://thmb.techidaily.com/f7008ec86977e694421ef724a35a33c6fec32d45741490d50d66c52b24ae9074.jpg
---

## Keep Upgrades at Bay with These 4 Tips

 By default, all your Office apps are set to update themselves automatically in the background. Although this approach keeps your Office apps updated with the latest features and improvements, these updates can sometimes overwhelm you or worse, cause new problems.

 Fortunately, there are several ways to disable automatic Office updates on Windows. Let's go over each of those methods one by one.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Stop Automatic Office Updates via the Settings App

 Windows lets you check for any pending Office updates directly from the Settings app. This allows you to install Office updates along with other system updates. If you don’t want that, you can disable the**Receive updates for other Microsoft products** option in the Settings app. Here are the steps for the same.

1. Open the**Start menu** and click the**gear icon** to launch the Settings app.
2. Select**Windows Update** from the left sidebar.
3. Select**Advanced options** .
4. Disable the toggle next to**Receive updates for other Microsoft products** .  
![Stop Automatic Office Updates Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/stop-automatic-office-updates-using-the-settings-app.jpg)

## 2\. How to Stop Automatic Office Updates Using One of Its Apps

 You can also opt out of automatic Office updates by using one of its apps, such as Word or Excel. Here’s how you can go about it.

1. Open any Office app, such as Word.
2. Click the**File** menu in the top left corner.
3. Select**Account** from the left pane.
4. Click the**Update Options** drop-down menu in the Manage Account section and choose**Disable Updates** .
5. Select**Yes** to confirm.  
![Stop Office Updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/stop-office-updates.jpg)

 Once you complete the above steps, your Office apps will not check for and install newer updates. Don't worry, you'll still be able to install updates manually.

 If you want to re-enable automatic updates later, use the same steps above and select**Enable Update** in the**Update Options** menu.

## 3\. How to Stop Automatic Office Updates Using the Group Policy Editor

 Another way to disable automatic Office updates is via the Group Policy Editor. It’s worth noting that you can only access the Group Policy Editor on Professional, Education, or Enterprise editions of Windows. If you're on Windows Home, be sure to check out[how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

 By default, the Group Policy Editor does not include any modules for managing Microsoft Office settings. So, in order to stop automatic Office updates via the Group Policy Editor, first, you’ll have to download and install Administrative Templates for Microsoft Office products. Here are the steps for the same.

1. Open up your web browser and head over to Microsoft Download Center to[download the Administrative Template files (ADMX/ADML) for Office apps](https://www.microsoft.com/en-us/download/details.aspx?id=49030) .  
![Download Office Administrative Templates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/download-office-administrative-templates.jpg)
2. Double-click the downloaded**EXE file** to run it.
3. Accept the license terms and click the**Continue** button.
4. The installer will prompt you for a location to extract the contents. Select an empty folder and hit**OK** .
5. Go to the location where you extracted the files and open the**admx** folder.
6. Select all the**admx files** and press**Ctrl + C** to copy them.
7. Head to**C: > Windows > PolicyDefinitions** folder.
8. Paste all the admx files in the**PolicyDefinitions** folder.  
![Copy Office ADMX files to PolicyDefinitions Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-office-admx-files-to-policydefinitions-folder.jpg)
9. Return to the folder where you extracted the files and open the**admx** folder again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105860/7443" target="_top" id="2105860">
  <img src="//a.impactradius-go.com/display-ad/7443-2105860" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105860/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

10. Open the**en-US** folder and copy all the**adml files** within.
11. Head to**C: > Windows > PolicyDefinitions** \>**en-US** folder and paste all the**adml files** .  
![Copy Office ADML files to PolicyDefinitions Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-office-adml-files-to-policydefinitions-folder.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006919/19272" target="_top" id="2006919">
  <img src="//a.impactradius-go.com/display-ad/19272-2006919" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006919/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After completing the above steps, you’re all set to disable automatic Office updates via the Group Policy Editor. Here are the steps you can follow.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the box and select the first result that appears. This will open the Local Group Policy Editor.
3. Use the left pane to navigate to **Local Computer Policy > Computer Configuration > Administrative Templates > Microsoft Office 2016 > Updates** .
4. Double-click the**Enable Automatic Updates** policy on your right.  
![Stop Automatic Office Updates Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/stop-automatic-office-updates-using-group-policy-editor.jpg)
5. Select the**Disabled** option.
6. Hit**Apply** followed by**OK** .
7. Next, press**Win + R** to open the Run dialog.
8. Type**cmd** in the text box and press**Ctrl + Shift + Enter** to[open Command Prompt with administrative privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
9. Type**gpupdate /force** in the console and hit**Enter** to apply the Group Policy changes.

 If you want to re-enable automatic updates for Office apps later, simply set the**Enable Automatic Updates** policy to**Enabled** .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115951/19272" target="_top" id="2115951">
  <img src="//a.impactradius-go.com/display-ad/19272-2115951" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115951/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. How to Stop Automatic Office Updates With the Registry Editor

 You can also use the Registry Editor to make the above policy change and disable automatic Office updates on your computer. Since Registry Editor holds important settings for Windows and its apps, you should only use this method if you’re comfortable editing the[Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) .

 If you decide to use this method, make sure you back up all the registry files or create a restore point beforehand. If you need help, refer to our guide on[how to create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) and follow the steps outlined there.

 Once you've done that, use the following steps to disable automatic Office updates via the Registry Editor.

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **Computer > HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft** .  
![Registry Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor.jpg)
5. Right-click the**Microsoft** key and select**New > Key** .

1. Rename the key as**Office** .
2. Right-click on the**Office** key and select**New > Key** .
3. Rename the key as**16.0** .
4. Right-click the**16.0** key and select**New > Key** .
5. Rename the key as**Common** .
6. Within the**Common** key, create another key named**OfficeUpdate** .
7. Right-click the**OfficeUpdate** key and select**New > DWORD (32-bit) Value** . Name this new DWORD**EnableAutomaticUpdates** .
8. Double-click**EnableAutomaticUpdates** DWORD and set its**Value Data** to**0** .
9. Click**OK** .  
![Turn Off Automatic Office Updates Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-off-automatic-office-updates-using-registry-editor.jpg)

 After completing the above steps, restart your computer. Following that, Office apps won’t update automatically on your computer. If you want to undo this change, open the Registry Editor again and delete the**EnableAutomaticUpdates** DWORD.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526">
  <img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Stop Automatic Office Updates on Windows

 It is almost always preferable to keep your Office apps up to date so that you can benefit from new features and security updates. Hence, if you disable automatic Office updates for some reason, don’t forget to check for new updates manually every once in a while.

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
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-navigating-spotifys-advertising-landscape/"><u>[New] 2024 Approved Navigating Spotify's Advertising Landscape</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-crafting-a-narrative-template-for-online-educational-videos/"><u>[Updated] In 2024, Crafting a Narrative Template for Online Educational Videos</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-in-2024-standout-14-animation-techniques-for-texts/"><u>[Updated] In 2024, Standout 14 Animation Techniques for Texts</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-expert-tips-for-high-quality-sound-memos/"><u>2024 Approved Expert Tips for High-Quality Sound Memos</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-infuse-motion-blur-into-image-sequence/"><u>2024 Approved Infuse Motion Blur Into Image Sequence</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-understanding-facebooks-silent-video-alerts/"><u>2024 Approved Understanding Facebook's Silent Video Alerts</u></a></li>
<li><a href="https://tech-hub.techidaily.com/daily-life-with-ai-chatbots-comparing-claude-and-chatgpts-effectiveness/"><u>Daily Life with AI Chatbots: Comparing Claude and ChatGPT's Effectiveness</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elite-four-password-keepers-for-a-robust-windows-11-experience/"><u>Elite Four Password Keepers for a Robust Windows 11 Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-calamity-to-caution-prioritize-windows-backups/"><u>From Calamity to Caution: Prioritize Windows Backups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-steam-deck-to-full-os-installing-windows/"><u>From Steam Deck to Full OS: Installing Windows</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-precision-workflow-tackling-backdrops-in-affinity-photo-to-perfection/"><u>In 2024, Precision Workflow Tackling Backdrops in Affinity Photo to Perfection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-paper-jam-clearance-for-non-responsive-printers-on-win-10/"><u>Instant Paper Jam Clearance for Non-Responsive Printers on Win 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-unintended-taskmgr-application-sort/"><u>Preventing Unintended TaskMgr Application Sort</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-adding-program-icons-to-windows-11s-taskbar/"><u>Quick Guide: Adding Program Icons to Windows 11'S Taskbar</u></a></li>
<li><a href="https://fox-that.techidaily.com/solving-location-unavailable-errors-a-step-by-step-guide-for-iphone-users/"><u>Solving 'Location Unavailable' Errors: A Step-by-Step Guide for iPhone Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-correcting-error-during-software-updates/"><u>Steps for Correcting Error During Software Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-overuse-of-resources-in-remote-connectivity-tools/"><u>Tackling Overuse of Resources in Remote Connectivity Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-the-impact-of-microsofts-copilot-key-on-pcs/"><u>Understanding the Impact of Microsoft's Copilot Key on PCs</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-s-ultimate-avi-editor-for-windows-8-edit-videos-like-a-pro-for-2024/"><u>Updated S Ultimate AVI Editor for Windows 8 Edit Videos Like a Pro for 2024</u></a></li>
</ul></div>

