---
title: Keep Upgrades at Bay with These 4 Tips
date: 2024-10-20T02:12:19.931Z
updated: 2024-10-20T19:27:20.305Z
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137203/26400" target="_top" id="2137203">
  <img src="//a.impactradius-go.com/display-ad/26400-2137203" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137203/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
10. Open the**en-US** folder and copy all the**adml files** within.
11. Head to**C: > Windows > PolicyDefinitions** \>**en-US** folder and paste all the**adml files** .  
![Copy Office ADML files to PolicyDefinitions Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-office-adml-files-to-policydefinitions-folder.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959712/19272" target="_top" id="1959712">
  <img src="//a.impactradius-go.com/display-ad/19272-1959712" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959712/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657395/16446" target="_top" id="1657395">
  <img src="//a.impactradius-go.com/display-ad/16446-1657395" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657395/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<span id="1975658">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975658.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975658">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975658.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975658%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975658/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-docs.techidaily.com/024-approved-embarking-on-a-virtual-odyssey-through-yt-stories/"><u>[New] 2024 Approved Embarking on a Virtual Odyssey Through YT Stories</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ocial-trends-in-visual-forms-23-edition/"><u>[New] Social Trends in Visual Forms, '23 Edition</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-gripping-gospels-intros-that-draw-ears/"><u>[Updated] 2024 Approved Gripping Gospels Intros That Draw Ears</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-how-to-craft-eye-catching-youtubes-end-titles/"><u>[Updated] How to Craft Eye-Catching YouTubes End Titles</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-share-the-moment-how-to-post-on-twitter/"><u>[Updated] Share the Moment How To Post on Twitter</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-teachers-handbook-building-a-successful-youtube-channel-10-must-dos-for-2024/"><u>[Updated] Teachers' Handbook Building a Successful YouTube Channel – 10 Must-Dos for 2024</u></a></li>
<li><a href="https://location-fake.techidaily.com/3utools-virtual-location-not-working-on-vivo-s18-pro-fix-now-drfone-by-drfone-virtual-android/"><u>3uTools Virtual Location Not Working On Vivo S18 Pro? Fix Now | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/best-ways-to-bypass-icloud-activation-lock-from-apple-iphone-15ipadipod-by-drfone-ios/"><u>Best Ways to Bypass iCloud Activation Lock from Apple iPhone 15/iPad/iPod</u></a></li>
<li><a href="https://win-able.techidaily.com/expert-advice-get-your-sea-of-thieves-game-running-smoothly-again/"><u>Expert Advice: Get Your Sea of Thieves Game Running Smoothly Again</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-concept-to-code-establishing-individual-patterns-on-windows/"><u>From Concept to Code: Establishing Individual Patterns on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-manually-apply-local-group-policies-to-single-windows-account/"><u>How to Manually Apply Local Group Policies to Single Windows Account</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-mend-the-steam-ui-module-fails-issue/"><u>How To Mend the Steam UI Module Fails Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-open-the-fax-cover-page-editor-in-windows-11/"><u>How to Open the Fax Cover Page Editor in Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-oppo-reno-11-pro-5g-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Oppo Reno 11 Pro 5G to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-technique-to-resolve-windows-11-error-code-0xc0000001/"><u>Mastering the Technique to Resolve Windows 11 Error Code 0XC0000001</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-javascript-troubleshooting-with-discord/"><u>Navigating Through Windows' JavaScript Troubleshooting with Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-pink-screen-woes-a-practical-approach/"><u>Resolving Pink Screen Woes: A Practical Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-lost-sound-preferences-on-windows-os/"><u>Restoring Lost Sound Preferences on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-merging-data-on-modern-windows/"><u>The Art of Merging Data on Modern Windows</u></a></li>
</ul></div>

