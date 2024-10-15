---
title: Tips for Controlling Lights on Windows 11 Search Results
date: 2024-10-08T18:23:40.581Z
updated: 2024-10-14T21:15:28.055Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tips for Controlling Lights on Windows 11 Search Results
excerpt: This Article Describes Tips for Controlling Lights on Windows 11 Search Results
keywords: Windows 11 Light Control Tips,Brighten/Darken Windows 11,Windows 11 Efficient Lighting,Managing Windows Lights,Reduce Energy Window Light,Optimize Windows Light Settings,Windows 11 Power Saving
thumbnail: https://thmb.techidaily.com/102c7cf0ada16d45d73aab06a0df3c1b4bd516c1e4675a811bb1bd88b724571c.jpg
---

## Tips for Controlling Lights on Windows 11 Search Results

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
<a href="https://aligracehair.sjv.io/c/5597632/2006933/19272" target="_top" id="2006933">
  <img src="//a.impactradius-go.com/display-ad/19272-2006933" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006933/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Turn Search Highlights On and Off in the Local Group Policy Editor

 Press **Win + R** to open the Windows Run dialog box, type **gpedit.msc** in the text box, and then hit the **Enter** key. For more ways to launch the tool, read our guide on [ways to open the Local Group Policy Editor on Windows 11](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

 On the left side menu, navigate to **Computer Configuration > Administrative Templates > Windows Components > Search**. Then, in the right panel, double-click the **Allow search highlights** policy to edit it.

![the Local Group Policy Editor on Windows with the Allow search highlights policy highlighted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/lgpe-windows-allow-search-highlights-policy.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2052059/7443" target="_top" id="2052059">
  <img src="//a.impactradius-go.com/display-ad/7443-2052059" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052059/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To show search highlights, make sure the **Not Configured** or **Enabled** radio button is checked, and then click **OK**.

![the Allow search highlights policy being edited on Windows and it is set to Not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-search-highlights-not-configured-windows.jpg)

 To disable search highlights, check the **Disabled** radio button, and then click **OK**.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135397/19272" target="_top" id="2135397">
  <img src="//a.impactradius-go.com/display-ad/19272-2135397" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135397/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://25home.pxf.io/c/5597632/2148641/16836" target="_top" id="2148641">
  <img src="//a.impactradius-go.com/display-ad/16836-2148641" border="0" alt="https://techidaily.com" width="254" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148641/16836" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-acquiring-igtv-media-easily-a-comprehensive-pcmac-guide/"><u>[New] In 2024, Acquiring IGTV Media Easily A Comprehensive PC/Mac Guide</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-strategic-social-sharing-master-facebook-story-linking-for-2024/"><u>[New] Strategic Social Sharing Master Facebook Story Linking for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-smallest-flyers-yet-big-impact-top-brands-reviewed/"><u>2024 Approved Smallest Flyers Yet Big Impact - Top Brands Reviewed</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-realme-c67-5g-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your Realme C67 5G? | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/budget-smart-high-fidelity-gaming-monitors-selection/"><u>Budget-Smart, High Fidelity Gaming Monitors Selection</u></a></li>
<li><a href="https://extra-resources.techidaily.com/cold-chronicles-the-2022-winter-olympics-in-china/"><u>Cold Chronicles The 2022 Winter Olympics in China</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-mac-with-windows-11-the-parallels-technique/"><u>Conquering Mac with Windows 11: The Parallels Technique</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-setup-positioning-quick-access-tools-in-win11-interface/"><u>Effortless Setup: Positioning Quick Access Tools in Win11 Interface</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-nubia-z50-ultra-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on Nubia Z50 Ultra | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/getting-started-with-langchain-llm-your-ultimate-starter-pack/"><u>Getting Started with LangChain LLM: Your Ultimate Starter Pack</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-linux-side-of-windows-uninterrupted-by-win-11/"><u>Keeping Linux Side of Windows Uninterrupted by Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-rearranging-onedrive-storage-in-win10/"><u>Mastering the Art of Rearranging OneDrive Storage in Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-high-dpi-screen-challenges-on-windows/"><u>Overcoming High DPI Screen Challenges on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rerouting-to-reinstalled-microsoft-store-programs-on-pc/"><u>Rerouting to Reinstalled Microsoft Store Programs on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-your-favorite-feature-how-to-bring-back-photo-viewer-on-win11/"><u>Restore Your Favorite Feature: How to Bring Back Photo Viewer on Win11</u></a></li>
<li><a href="https://fox-that.techidaily.com/struggling-with-iphone-vpn-connection-issues-here-are-7-effective-solutions/"><u>Struggling with iPhone VPN Connection Issues? Here Are 7 Effective Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stuck-in-the-stream-7-ways-to-reopen-reluctant-websites-on-win-os/"><u>Stuck in the Stream? 7 Ways to Reopen Reluctant Websites on Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-comic-file-management-in-win11/"><u>The Ultimate Guide to Comic File Management in Win11</u></a></li>
<li><a href="https://techidaily.com/useful-ways-that-can-help-to-effectively-recover-deleted-files-from-nokia-c300-by-fonelab-android-recover-data/"><u>Useful ways that can help to effectively recover deleted files from Nokia C300</u></a></li>
</ul></div>

