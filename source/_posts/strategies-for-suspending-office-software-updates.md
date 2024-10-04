---
title: Strategies for Suspending Office Software Updates
date: 2024-09-29T17:27:40.637Z
updated: 2024-10-03T20:23:16.520Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategies for Suspending Office Software Updates
excerpt: This Article Describes Strategies for Suspending Office Software Updates
keywords: Update Pause Strategies,Offsite Software Freeze,Manage Office Updates,Postponing IT Updates,Suspend Software Changes,Update Halt Plans,Delay Office Fixes
thumbnail: https://thmb.techidaily.com/5ef4b9be2cc03e1f5bba8134aa6b00b2355f4bf8946df71748d869f7b05769b2.jpg
---

## Strategies for Suspending Office Software Updates

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

<!-- affiliate ads begin -->
<span id="1983553">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983553.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983553">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983553.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983553%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983553/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Accept the license terms and click the**Continue** button.
4. The installer will prompt you for a location to extract the contents. Select an empty folder and hit**OK** .
5. Go to the location where you extracted the files and open the**admx** folder.
6. Select all the**admx files** and press**Ctrl + C** to copy them.
7. Head to**C: > Windows > PolicyDefinitions** folder.
8. Paste all the admx files in the**PolicyDefinitions** folder.  
![Copy Office ADMX files to PolicyDefinitions Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-office-admx-files-to-policydefinitions-folder.jpg)
9. Return to the folder where you extracted the files and open the**admx** folder again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151889/7443" target="_top" id="2151889">
  <img src="//a.impactradius-go.com/display-ad/7443-2151889" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151889/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

10. Open the**en-US** folder and copy all the**adml files** within.
11. Head to**C: > Windows > PolicyDefinitions** \>**en-US** folder and paste all the**adml files** .  
![Copy Office ADML files to PolicyDefinitions Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-office-adml-files-to-policydefinitions-folder.jpg)

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535">
  <img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After completing the above steps, restart your computer. Following that, Office apps won’t update automatically on your computer. If you want to undo this change, open the Registry Editor again and delete the**EnableAutomaticUpdates** DWORD.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130889/7443" target="_top" id="2130889">
  <img src="//a.impactradius-go.com/display-ad/7443-2130889" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130889/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-blog.techidaily.com/024-approved-engaging-vlogger-subjects-each-day/"><u>[New] 2024 Approved Engaging Vlogger Subjects Each Day</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-navigating-macos-11-big-sur-system-details/"><u>[New] 2024 Approved Navigating MacOS 11 Big Sur - System Details</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-no-more-queasiness-in-vr-worlds/"><u>[New] No More Queasiness in VR Worlds</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-best-websites-reviewed-secure-purchase-of-custom-youtube-soundtracks-for-2024/"><u>[Updated] Best Websites Reviewed Secure Purchase of Custom YouTube Soundtracks for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-leap-into-broadcasting-effortless-setup-for-your-mobile-youtube-ventures-for-2024/"><u>[Updated] Leap Into Broadcasting Effortless Setup for Your Mobile YouTube Ventures for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1080p-vs-4k-quels-sont-les-avantages-de-la-video-en-haute-definition-et-comment-upscaler-a-partir-de-1080p/"><u>1080P vs 4K : Quels Sont Les Avantages De La Vidéo en Haute Définition Et Comment Upscaler À Partir De 1080P</u></a></li>
<li><a href="https://win11-tips.techidaily.com/aif-to-mp4-online-aif/"><u>AIF to MP4 : 원탁한 컴퓨터 없이 Online AIF 변환 서비스</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-oppo-reno-9a-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Oppo Reno 9A Hard Reset | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-guide-to-mac-based-video-conversion-programs-find-download-compare-and-utilize-professional-software/"><u>Comprehensive Guide to Mac-Based Video Conversion Programs: Find, Download, Compare, and Utilize Professional Software!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-converter-change-mp2-audio-files-into-mp3-format-with-movavi/"><u>Free Online Converter: Change MP2 Audio Files Into MP3 Format with Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-converter-change-wmv-files-into-high-quality-flac-format-with-ease/"><u>Free Online Converter: Change WMV Files Into High-Quality FLAC Format with Ease</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-can-i-get-more-stardust-in-pokemon-go-on-poco-m6-5g-drfone-by-drfone-virtual-android/"><u>How can I get more stardust in pokemon go On Poco M6 5G? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-pictures-from-nokia-xr21-by-fonelab-android-recover-pictures/"><u>How to recover deleted pictures from Nokia XR21.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavi-convertidor-sin-costo-para-cambiar-mpg-a-3gp-facilmente-en-linea/"><u>Móvavi - Convertidor Sin Costo Para Cambiar MPG a 3GP Fácilmente en Línea</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movaviflv3gp/"><u>Movaviで簡単にフリーオンライン変換:FLVを3GPに</u></a></li>
<li><a href="https://win11-tips.techidaily.com/scambia-il-tuo-file-video-tta-con-un-formato-flac-senza-costi-usando-leditor-di-codici-video-online-movavi-passaggi-semplici-per-tutti/"><u>Scambia Il Tuo File Video TTA Con Un Formato FLAC Senza Costi Usando L'editor Di Codici Video Online Movavi - Passaggi Semplici per Tutti</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-not-found-device-issue-code-24-on-microsoft-windows-versions-11-8-and-7/"><u>Solving the ‘Not Found’ Device Issue - Code 24 on Microsoft Windows Versions 11, 8 & 7</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/top-5-vivo-y17s-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Vivo Y17s Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://win11-tips.techidaily.com/veelvoudig-maken-van-flac-liedjes-in-mp4-online-gratis-movavi-online-konverter/"><u>Veelvoudig Maken Van FLAC-Liedjes in MP4 Online, Gratis - Movavi Online Konverter</u></a></li>
</ul></div>

