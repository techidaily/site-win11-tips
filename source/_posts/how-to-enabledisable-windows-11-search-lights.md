---
title: How to Enable/Disable Windows 11 Search Lights
date: 2024-10-21T18:26:00.416Z
updated: 2024-10-26T18:12:09.164Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Enable/Disable Windows 11 Search Lights
excerpt: This Article Describes How to Enable/Disable Windows 11 Search Lights
keywords: Disable Windows Search Light,Enable Windows 11 Search,Windows 11 Dark Mode,Turn Off Windows Notification,Reduce Windows Reflections,Adjust Windows Lights Out,Mute Windows Soundscape
thumbnail: https://thmb.techidaily.com/b0350890102e8bceb542486b6a13817e51d92335c8505179cd1df5114471ab31.jpg
---

## How to Enable/Disable Windows 11 Search Lights

 Search highlights is a feature that helps you discover interesting content whenever you launch Windows Search. If you find that they aren’t popping up, there are several ways for you to turn them on. And if you find them to be bothersome, well, you can turn them off and continue enjoying Windows as if they never existed.

 So, keep on reading to find out three ways to turn search highlights on and off.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Turn Search Highlights On and Off in the Settings App

 Press **Win + I** to open the Settings app. Then, select **Privacy & security** on the left side menu, and then click on **Search permissions** in the right panel.

![the privacy and security page on Windows with Search permissions showing in the right panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions.jpg)

 Scroll down to the **More settings** section, and then click the toggle under **Show search highlights** to turn the feature on or off.

![the Seach permissions page on Windows 11 with the More settings section showing and the toggle for Show search highlights set to on](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions-settings.jpg)

 You should no longer see search lights now.

<!-- affiliate ads begin -->
<span id="1983549">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983549.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983549">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983549.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983549%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983549/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Turn Search Highlights On and Off in the Local Group Policy Editor

 Press **Win + R** to open the Windows Run dialog box, type **gpedit.msc** in the text box, and then hit the **Enter** key. For more ways to launch the tool, read our guide on [ways to open the Local Group Policy Editor on Windows 11](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

 On the left side menu, navigate to **Computer Configuration > Administrative Templates > Windows Components > Search**. Then, in the right panel, double-click the **Allow search highlights** policy to edit it.

![the Local Group Policy Editor on Windows with the Allow search highlights policy highlighted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/lgpe-windows-allow-search-highlights-policy.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135357/19272" target="_top" id="2135357">
  <img src="//a.impactradius-go.com/display-ad/19272-2135357" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135357/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To show search highlights, make sure the **Not Configured** or **Enabled** radio button is checked, and then click **OK**.

![the Allow search highlights policy being edited on Windows and it is set to Not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-search-highlights-not-configured-windows.jpg)

 To disable search highlights, check the **Disabled** radio button, and then click **OK**.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975836/19272" target="_top" id="1975836">
  <img src="//a.impactradius-go.com/display-ad/19272-1975836" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975836/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Turn Search Highlights On and Off in the Registry Editor

 Press **Win + R** to open the Windows Run dialog box, type **regedit** in the text box, and then hit the **Enter** key. Click **Yes** in the UAC prompt to finally launch the Registry Editor.

 Before you proceed, we recommend that you read our guide on [how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). This may come in handy in case you accidentally break the Windows Registry.

 In the address bar of the Registry Editor, copy and paste the below text, and then press **Enter**:

`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\SearchSettings`

 Right-click the **SearchSettings** key on the left side menu and select **New > DWORD (32-bit) Value** in the menu that appears. Then, name the value **IsDynamicSearchBoxEnabled**.

![creating a dword value in the Windows registry for the SearchSettings key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/creating-dword-windows-registry.jpg)

 In the right panel, double-click **IsDynamicSearchBoxEnabled** (the value you just created) and then enter **1** in the **Value data** text box to turn search highlights on. Then, click **OK** to apply the change.

![the IsDynamicSearchBoxEnabled value in the Registry Editor and Value data has been set to 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/editing-isdynamicsearchboxenabled-value-windows-registry.jpg)

 To turn search highlights off, enter **0** in the **Value data** text box, and then click **OK**.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135353/19272" target="_top" id="2135353">
  <img src="//a.impactradius-go.com/display-ad/19272-2135353" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135353/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Control Your Search Highlights on Windows 11

 Windows 11 being customizable is what makes interacting with the OS enjoyable. The power is in your hands whether you want to see search highlights or not in Windows Search. And now you know three ways to enable or disable them.

 So, keep on reading to find out three ways to turn search highlights on and off.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-weaving-yt-music-threads-through-video-tapestry/"><u>[New] 2024 Approved Weaving YT Music Threads Through Video Tapestry</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-enhancing-mobile-instagram-videos-velocity-tips/"><u>[New] Enhancing Mobile Instagram Videos' Velocity (Tips)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-instagram-film-to-mp3-conversion-tactics/"><u>[New] In 2024, Instagram Film to MP3 Conversion Tactics</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-ultimate-guide-to-6-best-nft-services-for-creative-geniuses/"><u>2024 Approved The Ultimate Guide to 6 Best NFT Services for Creative Geniuses</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/el-growth-essential-steps-for-youtube-backlink-creation-for-2024/"><u>Channel Growth Essential Steps for YouTube Backlink Creation for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensively-addressing-file-creation-fails-in-windows-error-30005/"><u>Comprehensively Addressing File Creation Fails in Windows Error 30005</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/discovering-the-ultimate-14-stardew-valley-upgrades/"><u>Discovering the Ultimate 14 Stardew Valley Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-techniques-for-launching-windows-calculator/"><u>Efficient Techniques for Launching Windows' Calculator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fastening-your-purchase-speed-for-ms-store-products/"><u>Fastening Your Purchase Speed for MS Store Products</u></a></li>
<li><a href="https://win11-tips.techidaily.com/inter-system-sharing-made-simple-with-nearby-share/"><u>Inter-System Sharing Made Simple with Nearby Share</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-fullscreen-failsures-in-sonic-gameplay-on-w11/"><u>Navigating Fullscreen Failsures in Sonic Gameplay on W11</u></a></li>
<li><a href="https://fox-within.techidaily.com/quick-and-effective-techniques-for-modifying-pdf-text-content-with-adobes-tools/"><u>Quick and Effective Techniques for Modifying PDF Text Content with Adobe's Tools</u></a></li>
<li><a href="https://data-wizards.techidaily.com/reviving-files-phoenix-creates-pdf-savior/"><u>Reviving Files, Phoenix Creates PDF Savior</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/revolutionize-your-online-experience-with-our-cookiebot-solutions/"><u>Revolutionize Your Online Experience With Our Cookiebot Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-increase-space-on-win11-drives-without-trashing-data-max-156-chars/"><u>Strategies to Increase Space on Win11 Drives Without Trashing Data (Max 156 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-switch-off-gpgpu-scheduling-on-the-winos-platform/"><u>Techniques: Switch Off GPGPU Scheduling on the WINOS Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-efficient-methods-to-resolve-common-anydesk-errors-in-os/"><u>Unlocking Efficient Methods to Resolve Common AnyDesk Errors in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-simple-steps-for-changing-windows-11-name/"><u>Unveiling the Simple Steps for Changing Windows 11 Name</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-battle-against-the-d3d11-gpu-hurdle-in-w11w10/"><u>Winning Battle Against the D3D11 GPU Hurdle in W11/W10</u></a></li>
</ul></div>

