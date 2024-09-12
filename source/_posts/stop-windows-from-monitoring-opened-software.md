---
title: Stop Windows From Monitoring Opened Software
date: 2024-09-11T01:25:04.486Z
updated: 2024-09-12T01:25:04.486Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stop Windows From Monitoring Opened Software
excerpt: This Article Describes Stop Windows From Monitoring Opened Software
keywords: Stop Software Tracking,Avoid Windows Surveillance,End PC Monitoring,Disable Software Watch,Block Window Tracker,Prevent OS Tracking,Eliminate Windows Spying
thumbnail: https://thmb.techidaily.com/dce6bc9a112b3f049356452f785b8eb72027385ba75d849bd9c5cf60929a80d0.png
---

## Stop Windows From Monitoring Opened Software

 Windows records and monitors how often you use particular applications. While this may enhance productivity, it does also raise privacy concerns.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.


>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>







<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2126492/26400" target="_top" id="2126492">
  <img src="//a.impactradius-go.com/display-ad/26400-2126492" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2126492/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 1\. How to Disable App Launch Tracking Through Windows Settings

 To disable app launch tracking, open the Start menu and type **Settings** in the search bar. Select the **Settings** option in the search results. In the left-side menu, click the **Privacy & security** tab. Then click **General** under the Windows permissions section.

 On the next page, locate **Let Windows improve Start and search results by tracking app launches** and toggle it off.

![Disable App Launch Tracking through Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-windows-settings.jpg)





<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134241/18498" target="_top" id="2134241">
  <img src="//a.impactradius-go.com/display-ad/18498-2134241" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134241/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 After making the changes, Windows will stop tracking and recording your app launches.

 If you ever need to re-enable the feature, repeat the same steps and toggle the switch back on. This will enable Windows to start tracking and recording your app launches.





<!-- affiliate ads begin -->
<span id="1977004">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977004.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977004">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977004.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977004%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977004/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 2\. How to Disable App Launch Tracking Using the Group Policy Editor

 You can also disable app launch tracking using the Group Policy Editor. But this method is only available in the Pro and Enterprise versions.

 If you don't have these Windows versions, [turn on the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) and follow these instructions.

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **gpedit.msc** in the text box and click **OK**.
3. In the Group Policy Editor window, navigate to the following path:  
`User Configuration > Administrative Templates > Windows Components > Edge UI​`
4. Go to the right side of the window and double-click on **Turn off tracking of app usage**.  
![Disable App Launch Tracking using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-using-group-policy-editor.jpg)
5. On the next page, check the **Enabled** box.
6. Click **Apply** \> **OK** to save your changes.

 This way, you can disable app launch tracking using the group policy editor.

 To enable the feature again, follow the same steps and navigate to _User Configuration > Administrative Templates > Windows Components > Edge UI_. Then double-click on **Turn off tracking of app usage** and check the **Not Configured** or **Disabled** option.





<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134489/18498" target="_top" id="2134489">
  <img src="//a.impactradius-go.com/display-ad/18498-2134489" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134489/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 3\. How to Disable App Launch Tracking Through the Registry Editor

 Registry Editor is another method to disable app launch tracking. The process is tricky as you need to manually modify the registry keys and one wrong move can cause serious problems. So, we suggest you [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 To disable app launch tracking through Registry Editor, do the following:

1. Right-click on Start and select **Run** from the menu list.
2. Type **regedit** in the text field and click **OK**. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. When the UAC window appears, click **Yes** to grant privileges.
4. In the left pane, navigate to the following path:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. If you don't find the Advanced folder, right-click on **Explorer** and select **New** \> **Key**.
6. Name it **Advanced** and press the Enter key.
7. Now, right-click on the **Advanced** folder and choose **New** \> **DWORD (32-bit) Value**.
8. Name it **Start\_TrackProgs** and hit Enter.  
![Disable App Launch Tracking through the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-the-registry-editor.jpg)
9. Double-click on the **Start\_TrackProgs** DWORD and set its value to **0**.




<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134235/18498" target="_top" id="2134235">
  <img src="//a.impactradius-go.com/display-ad/18498-2134235" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134235/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->





 Once you're done, close the Registry Editor and restart your computer. Now, Windows won't track or record app launches.

 If you ever want to turn back on app launch tracking, double-click on the **Start\_TrackProgs** DWORD in Registry Editor and set its value to **1**. After that, restart your system for the changes to take effect.





<!-- affiliate ads begin -->
<span id="1983473">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983473.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983473">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983473.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983473%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983473/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Windows Won’t Track or Monitor the Apps You Use

 If you don't want to mess with the Registry Editor or Group Policy Editor, use the Settings option to disable app launch tracking. Choose the method you prefer and enjoy a tracking-free experience.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.





<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-top-strategies-for-crafting-viral-reactions-a-guide/"><u>[New] In 2024, Top Strategies for Crafting Viral Reactions A Guide</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-beats-in-the-balance-adding-music-to-whatsapp/"><u>[Updated] Beats in the Balance Adding Music to WhatsApp</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/commanding-conversations-innovative-language-programs/"><u>Commanding Conversations: Innovative Language Programs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-invalid-user-alerts-fix-guide-for-windows-1111/"><u>Disabling Invalid User Alerts: Fix Guide for Windows 11/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-digital-tidying-enabling-self-deleting-windows-trash/"><u>Effortless Digital Tidying: Enabling Self-Deleting Windows Trash</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-stubborn-windows-printers-a-swift-guide/"><u>Eliminating Stubborn Windows Printers: A Swift Guide</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/enhance-your-livestream-quality-learn-4-innovative-techniques/"><u>Enhance Your Livestream Quality Learn 4 Innovative Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicate-entryways-four-slick-steps-to-disable-a-user-on-win11/"><u>Eradicate Entryways: Four Slick Steps to Disable a User on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-data-recovery-offer-immediate-access-and-assurance/"><u>Exclusive Data Recovery Offer: Immediate Access & Assurance</u></a></li>
<li><a href="https://driver-download.techidaily.com/fast-and-simple-guide-install-webcam-drivers-on-windows-7/"><u>Fast and Simple Guide: Install Webcam Drivers on Windows 7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-make-the-taskbar-bigger-or-smaller-on-windows-11/"><u>How to Make the Taskbar Bigger or Smaller on Windows 11</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-seamlessly-integrate-new-epson-printer-drivers-with-your-windows-10-device-a-comprehensive-guide/"><u>How To Seamlessly Integrate New Epson Printer Drivers with Your Windows 10 Device: A Comprehensive Guide</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-best-pokemons-for-pvp-matches-in-pokemon-go-for-vivo-v30-drfone-by-drfone-virtual-android/"><u>In 2024, Best Pokemons for PVP Matches in Pokemon Go For Vivo V30 | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-fix-oem-unlock-missing-on-oppo-by-drfone-android/"><u>In 2024, How To Fix OEM Unlock Missing on Oppo?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-driver-verifier-via-control-panel-on-w11/"><u>Launching Driver Verifier via Control Panel on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-basic-window-aids-for-beginners/"><u>Mastering Basic Window Aids for Beginners</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/mastery-guide-sync-videos-to-facebook-pc-and-android-way-for-2024/"><u>Mastery Guide Sync Videos to Facebook - PC & Android Way for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-task-manager-visibility/"><u>Maximizing Task Manager Visibility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modernizing-the-user-experience-with-windows-1011-shortcuts/"><u>Modernizing the User Experience with Windows 10/11 Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/old-gameshells-rekindled-with-atlasos/"><u>Old Gameshells Rekindled with AtlasOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/patching-up-a-purple-problem-desktop-restoration-steps/"><u>Patching Up a Purple Problem: Desktop Restoration Steps</u></a></li>
<li><a href="https://technical-tips.techidaily.com/securing-your-education-savings-a-guide-to-the-microsoft-student-price-cut/"><u>Securing Your Education Savings: A Guide to the Microsoft Student Price Cut</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-tasks-with-mspcm-toolbar-in-windows-11/"><u>Streamlining Tasks with MSPCM Toolbar in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-procedure-for-restoring-icons-on-windows-11s-search-bar/"><u>The Procedure for Restoring Icons on Windows 11'S Search Bar</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-videos-from-asus-rog-phone-8-pro-by-fonelab-android-recover-video/"><u>The way to get back lost videos from Asus ROG Phone 8 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-managing-text-highlighting-in-windows-11/"><u>Tips for Managing Text Highlighting in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-non-microsoft-tools-for-immediate-and-accurate-screen-sniping/"><u>Top Non-Microsoft Tools For Immediate and Accurate Screen Sniping</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-full-potential-of-service-management-on-windows-11/"><u>Unlock the Full Potential of Service Management on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mysteries-of-windows-iscsi-initiator-access/"><u>Unraveling the Mysteries of Windows iSCSI Initiator Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/update-windows-11-admin-credentials-quickly/"><u>Update Windows 11 Admin Credentials Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-strategies-for-outlook-malfunctions/"><u>Winning Strategies for Outlook Malfunctions</u></a></li>
</ul></div>







<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    