---
title: Manipulate Your Search & Highlight Settings in Windows 11
date: 2024-09-30T22:36:50.117Z
updated: 2024-10-04T00:44:26.221Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Manipulate Your Search & Highlight Settings in Windows 11
excerpt: This Article Describes Manipulate Your Search & Highlight Settings in Windows 11
keywords: Win11 Custom Sets,Search Personalize Win,Highlight Controls Win11,Optimize Win11 Search,Adjust Win11 Settings,Windows 11 Search Tweaks,Manage Win11 Preferences
thumbnail: https://thmb.techidaily.com/b9ef13db0d4015b8f432338d38cc3c79dffc2187f90b8af800f112790cda12e7.JPG
---

## Manipulate Your Search & Highlight Settings in Windows 11

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
<a href="https://appsumo.8odi.net/c/5597632/2100538/7443" target="_top" id="2100538">
  <img src="//a.impactradius-go.com/display-ad/7443-2100538" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Turn Search Highlights On and Off in the Local Group Policy Editor

 Press **Win + R** to open the Windows Run dialog box, type **gpedit.msc** in the text box, and then hit the **Enter** key. For more ways to launch the tool, read our guide on [ways to open the Local Group Policy Editor on Windows 11](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

 On the left side menu, navigate to **Computer Configuration > Administrative Templates > Windows Components > Search**. Then, in the right panel, double-click the **Allow search highlights** policy to edit it.

![the Local Group Policy Editor on Windows with the Allow search highlights policy highlighted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/lgpe-windows-allow-search-highlights-policy.jpg)

 To show search highlights, make sure the **Not Configured** or **Enabled** radio button is checked, and then click **OK**.

![the Allow search highlights policy being edited on Windows and it is set to Not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-search-highlights-not-configured-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130886/7443" target="_top" id="2130886">
  <img src="//a.impactradius-go.com/display-ad/7443-2130886" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130886/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To disable search highlights, check the **Disabled** radio button, and then click **OK**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068426/7443" target="_top" id="2068426">
  <img src="//a.impactradius-go.com/display-ad/7443-2068426" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068426/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Turn Search Highlights On and Off in the Registry Editor

 Press **Win + R** to open the Windows Run dialog box, type **regedit** in the text box, and then hit the **Enter** key. Click **Yes** in the UAC prompt to finally launch the Registry Editor.

 Before you proceed, we recommend that you read our guide on [how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). This may come in handy in case you accidentally break the Windows Registry.

 In the address bar of the Registry Editor, copy and paste the below text, and then press **Enter**:

`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\SearchSettings`

 Right-click the **SearchSettings** key on the left side menu and select **New > DWORD (32-bit) Value** in the menu that appears. Then, name the value **IsDynamicSearchBoxEnabled**.

![creating a dword value in the Windows registry for the SearchSettings key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/creating-dword-windows-registry.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151884/7443" target="_top" id="2151884">
  <img src="//a.impactradius-go.com/display-ad/7443-2151884" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151884/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In the right panel, double-click **IsDynamicSearchBoxEnabled** (the value you just created) and then enter **1** in the **Value data** text box to turn search highlights on. Then, click **OK** to apply the change.

![the IsDynamicSearchBoxEnabled value in the Registry Editor and Value data has been set to 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/editing-isdynamicsearchboxenabled-value-windows-registry.jpg)

 To turn search highlights off, enter **0** in the **Value data** text box, and then click **OK**.

## Control Your Search Highlights on Windows 11

 Windows 11 being customizable is what makes interacting with the OS enjoyable. The power is in your hands whether you want to see search highlights or not in Windows Search. And now you know three ways to enable or disable them.

 So, keep on reading to find out three ways to turn search highlights on and off.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-encompassing-views-vs-enhanced-visual-depth/"><u>[New] In 2024, Encompassing Views vs Enhanced Visual Depth</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-top-10-global-voyages-for-discovery-enthusiasts/"><u>[New] In 2024, Top 10 Global Voyages for Discovery Enthusiasts</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-break-free-the-chuckles-ranking-20-hilarious-fb-detention-scenes-for-2024/"><u>[Updated] Break Free the Chuckles Ranking 20 Hilarious FB Detention Scenes for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-selecting-the-top-infinite-storage-providers/"><u>2024 Approved Selecting the Top Infinite Storage Providers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-download-to-use-chrome-in-windows-11-world/"><u>From Download to Use: Chrome in Windows 11 World</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-through-audacitys-unresponsive-error-in-win-oses/"><u>Guiding Through Audacity's Unresponsive Error in Win OSes</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-detect-and-stop-mspy-from-spying-on-your-vivo-y100t-drfone-by-drfone-virtual-android/"><u>How to Detect and Stop mSpy from Spying on Your Vivo Y100t | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unfortunately-contacts-has-stopped-error-on-google-pixel-8-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Unfortunately, Contacts Has Stopped Error on Google Pixel 8 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stop-and-fix-windows-operating-pause-issues/"><u>How to Stop and Fix Windows Operating Pause Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-microsofts-artificomedial-intelligence-hub/"><u>Navigating Through Microsoft's Artificomedial Intelligence Hub</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-secrets-of-silent-sleep-in-w10w11-machines/"><u>Unlock the Secrets of Silent Sleep in W10/W11 Machines</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    