---
title: Guide to Turn On/Off Windows 11 Highlight Effect
date: 2024-08-16T02:42:31.508Z
updated: 2024-08-17T02:42:31.508Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Turn On/Off Windows 11 Highlight Effect
excerpt: This Article Describes Guide to Turn On/Off Windows 11 Highlight Effect
keywords: Win11 Highlight On/Off Guide,Enable/Disable Windows 11 Effects,Highlighting Windows 11 Tutorial,Turn Windows 11 Effects On,Off Switch for Windows 11 Effects,Master Win11 Visual Effects,Activate Windows 11 Brightness
thumbnail: https://thmb.techidaily.com/3d668bfb6eaaff582ac6a3ef0ec269ab4610d6df4de409efc683d784a7434cf5.jpg
---

## Guide to Turn On/Off Windows 11 Highlight Effect

 Search highlights is a feature that helps you discover interesting content whenever you launch Windows Search. If you find that they aren’t popping up, there are several ways for you to turn them on. And if you find them to be bothersome, well, you can turn them off and continue enjoying Windows as if they never existed.

 So, keep on reading to find out three ways to turn search highlights on and off.

## 1\. How to Turn Search Highlights On and Off in the Settings App

 Press **Win + I** to open the Settings app. Then, select **Privacy & security** on the left side menu, and then click on **Search permissions** in the right panel.

![the privacy and security page on Windows with Search permissions showing in the right panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions.jpg)

 Scroll down to the **More settings** section, and then click the toggle under **Show search highlights** to turn the feature on or off.

![the Seach permissions page on Windows 11 with the More settings section showing and the toggle for Show search highlights set to on](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions-settings.jpg)

 You should no longer see search lights now.

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Turn Search Highlights On and Off in the Local Group Policy Editor

 Press **Win + R** to open the Windows Run dialog box, type **gpedit.msc** in the text box, and then hit the **Enter** key. For more ways to launch the tool, read our guide on [ways to open the Local Group Policy Editor on Windows 11](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

 On the left side menu, navigate to **Computer Configuration > Administrative Templates > Windows Components > Search**. Then, in the right panel, double-click the **Allow search highlights** policy to edit it.

![the Local Group Policy Editor on Windows with the Allow search highlights policy highlighted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/lgpe-windows-allow-search-highlights-policy.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->

 To show search highlights, make sure the **Not Configured** or **Enabled** radio button is checked, and then click **OK**.

![the Allow search highlights policy being edited on Windows and it is set to Not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-search-highlights-not-configured-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->

 To disable search highlights, check the **Disabled** radio button, and then click **OK**.

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Turn Search Highlights On and Off in the Registry Editor

 Press **Win + R** to open the Windows Run dialog box, type **regedit** in the text box, and then hit the **Enter** key. Click **Yes** in the UAC prompt to finally launch the Registry Editor.

 Before you proceed, we recommend that you read our guide on [how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). This may come in handy in case you accidentally break the Windows Registry.

 In the address bar of the Registry Editor, copy and paste the below text, and then press **Enter**:

`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\SearchSettings`

 Right-click the **SearchSettings** key on the left side menu and select **New > DWORD (32-bit) Value** in the menu that appears. Then, name the value **IsDynamicSearchBoxEnabled**.

![creating a dword value in the Windows registry for the SearchSettings key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/creating-dword-windows-registry.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->

 In the right panel, double-click **IsDynamicSearchBoxEnabled** (the value you just created) and then enter **1** in the **Value data** text box to turn search highlights on. Then, click **OK** to apply the change.

![the IsDynamicSearchBoxEnabled value in the Registry Editor and Value data has been set to 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/editing-isdynamicsearchboxenabled-value-windows-registry.jpg)

 To turn search highlights off, enter **0** in the **Value data** text box, and then click **OK**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
## Control Your Search Highlights on Windows 11

 Windows 11 being customizable is what makes interacting with the OS enjoyable. The power is in your hands whether you want to see search highlights or not in Windows Search. And now you know three ways to enable or disable them.

 So, keep on reading to find out three ways to turn search highlights on and off.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://on-screen-recording.techidaily.com/new-expert-tips-for-capturing-desktop-activity-the-ezvide-way/"><u>[New] Expert Tips for Capturing Desktop Activity - The Ezvide Way</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-10-best-agricultural-games-for-group-fun/"><u>[New] In 2024, 10 Best Agricultural Games for Group Fun</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-savor-playtime-the-essential-guide-to-high-quality-offline-ios-games/"><u>[New] Savor Playtime – The Essential Guide to High-Quality Offline iOS Games</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-uncovering-snapchats-hidden-symbolism/"><u>[Updated] 2024 Approved  Uncovering Snapchat's Hidden Symbolism</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-best-buy-top-10-gaming-gpus-for-high-quality-online-viewing/"><u>[Updated] In 2024, Best Buy  Top 10 Gaming GPUs for High-Quality Online Viewing</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-cut-to-the-chase-boosting-your-instagram-with-content/"><u>2024 Approved  Cut to the Chase - Boosting Your Instagram with Content</u></a></li>
<li><a href="https://fox-that.techidaily.com/9-effective-solutions-if-you-cant-access-chatgpt-on-your-iphone/"><u>9 Effective Solutions if You Can't Access ChatGPT on Your iPhone</u></a></li>
<li><a href="https://fox-helps.techidaily.com/a-guide-to-risk-management-and-mitigation-strategies-in-market-research-for-2024/"><u>A Guide to Risk Management and Mitigation Strategies in Market Research for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-disk-space-safely-preserving-data-on-your-windows-11-local-drive-max-156-chars/"><u>Boost Your Disk Space Safely: Preserving Data on Your Windows 11 Local Drive (Max 156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719316562070-boosting-window-light-in-windows-11-top-solutions-explored/"><u>Boosting Window Light in Windows 11: Top Solutions Explored!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-confusion-a-guide-to-reinstalling-store-software/"><u>Clearing Up Confusion: A Guide to Reinstalling Store Software</u></a></li>
<li><a href="https://win11.techidaily.com/diagnose-and-mend-dormant-usb-ports-the-windows-manual/"><u>Diagnose & Mend Dormant USB Ports - The Windows Manual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-user-experience-7-steps-to-missing-windows-add-ons/"><u>Enhancing User Experience: 7 Steps to Missing Windows Add-Ons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-interface-adding-portable-apps-menus/"><u>Enhancing Windows Interface: Adding Portable Apps Menus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-unavailability-of-icloud-on-windows/"><u>Fixing the Unavailability of iCloud on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-through-default-windows-backup-reset/"><u>Guiding Through Default Windows Backup Reset</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-users-through-admin-level-execution-woes/"><u>Guiding Users Through Admin-Level Execution Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harnessing-windows-oversight-on-apps-browsers/"><u>Harnessing Windows Oversight on Apps, Browsers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-you-dont-have-permission-to-view-this-file-error-on-windows/"><u>How to Fix the “You Don’t Have Permission to View This File” Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-downloads-folder-not-responding-on-windows/"><u>How to Fix the Downloads Folder Not Responding on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-permit-browser-network-access-via-windows-security-settings/"><u>How to Permit Browser Network Access via Windows Security Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improve-system-stability-automatic-updates-plus-amd-video-replacement/"><u>Improve System Stability: Automatic Updates + AMD Video Replacement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-microsoft-works-with-windows-11-easy/"><u>Integrating Microsoft Works with Windows 11 Easy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leap-to-peak-ssd-performance-win-and-fresh-methods/"><u>Leap to Peak SSD Performance: Win and Fresh Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-safety-sticky-notes-edition/"><u>Mastering File Safety: Sticky Notes Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-gui-diskspace-windows-menu-integration-guide/"><u>Mastering GUI Diskspace: Windows Menu Integration Guide</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-through-toms-comprehensive-hardware-reviews/"><u>Navigating Through Tom's Comprehensive Hardware Reviews</u></a></li>
<li><a href="https://win11-tips.techidaily.com/past-keys-to-future-launches-utilizing-windows-7-for-windows-11-bootup/"><u>Past Keys to Future Launches: Utilizing Windows 7 for Windows 11 Bootup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-remedy-fixing-file-not-found-issues-in-windows-1110/"><u>Quick Remedy: Fixing 'File Not Found' Issues in Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-operation-issues-on-modern-windows-pcs/"><u>Resolving Operation Issues on Modern Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-updater-roadblock-0x80073712/"><u>Resolving Updater Roadblock: 0X80073712</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-installation-of-windows-chatgpt/"><u>Step-by-Step Installation of Windows ChatGPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-windows-exploration-without-the-use-of-ls/"><u>Streamlined Windows Exploration Without the Use of LS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/supercharge-windows-11s-notepad-with-copilot/"><u>Supercharge Windows 11’S Notepad With Copilot</u></a></li>
<li><a href="https://facebook.techidaily.com/the-evolution-from-standard-bot-to-metaai/"><u>The Evolution: From Standard Bot to MetaAI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-insiders-guide-to-customizing-the-desktop-menu/"><u>The Insider's Guide to Customizing the Desktop Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-setting-up-window-sandbox/"><u>The Ultimate Guide to Setting up Window Sandbox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-restoring-accessibility-of-displays-in-nvidia-software/"><u>Tips for Restoring Accessibility of Displays in Nvidia Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-windows-strategy-for-sound-graph-segregation/"><u>Understanding Windows' Strategy for Sound Graph Segregation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11-potential-steps-for-successful-optional-components-integration/"><u>Unlocking Windows 11 Potential: Steps for Successful Optional Components Integration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/where-windows-hides-shot-files/"><u>Where Windows Hides Shot Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-evolves-spotlight-on-new-updates-capabilities/"><u>Windows 11 Evolves: Spotlight on New Updates' Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winrars-hash-harmony-six-ways-to-ensure-correct-sums/"><u>WinRAR's Hash Harmony: Six Ways to Ensure Correct Sums</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>