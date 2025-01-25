---
title: Adjusting Your Window's Search and Highlight Settings
date: 2025-01-17T17:55:07.685Z
updated: 2025-01-24T20:39:45.242Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Your Window's Search and Highlight Settings
excerpt: This Article Describes Adjusting Your Window's Search and Highlight Settings
keywords: Window Adjustment Guide,Change Window Search Settings,Tailor Window Highlighting,Modify Screen Focus Aids,Update Windows Sensitivity,Personalize Display Mode,Adapt Screen Brightness Levels
thumbnail: https://thmb.techidaily.com/8d1de21c666386207e0a2c0896dc0647ebc82a413cfdd6aa282a235213b145ee.jpg
---

## Adjusting Your Window's Search and Highlight Settings

 Search highlights is a feature that helps you discover interesting content whenever you launch Windows Search. If you find that they aren’t popping up, there are several ways for you to turn them on. And if you find them to be bothersome, well, you can turn them off and continue enjoying Windows as if they never existed.

 So, keep on reading to find out three ways to turn search highlights on and off.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ITtcSWvS8bo?si=4M4BfMgaabrW6148" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Turn Search Highlights On and Off in the Settings App

 Press **Win + I** to open the Settings app. Then, select **Privacy & security** on the left side menu, and then click on **Search permissions** in the right panel.

![the privacy and security page on Windows with Search permissions showing in the right panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mK1lEBRm_1w?si=FSaM0OKO0XBCgjtT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Scroll down to the **More settings** section, and then click the toggle under **Show search highlights** to turn the feature on or off.

![the Seach permissions page on Windows 11 with the More settings section showing and the toggle for Show search highlights set to on](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions-settings.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l-SCWTWpegY?si=oxTsHQkIu1v4-I6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You should no longer see search lights now.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UCqHbpxQGP4?si=XGkajFHdqyoKNAFM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Turn Search Highlights On and Off in the Local Group Policy Editor

 Press **Win + R** to open the Windows Run dialog box, type **gpedit.msc** in the text box, and then hit the **Enter** key. For more ways to launch the tool, read our guide on [ways to open the Local Group Policy Editor on Windows 11](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

 On the left side menu, navigate to **Computer Configuration > Administrative Templates > Windows Components > Search**. Then, in the right panel, double-click the **Allow search highlights** policy to edit it.

![the Local Group Policy Editor on Windows with the Allow search highlights policy highlighted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/lgpe-windows-allow-search-highlights-policy.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rBnnLFJbvr4?si=LlHYrYlOBp7NLMec" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To show search highlights, make sure the **Not Configured** or **Enabled** radio button is checked, and then click **OK**.

![the Allow search highlights policy being edited on Windows and it is set to Not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-search-highlights-not-configured-windows.jpg)

 To disable search highlights, check the **Disabled** radio button, and then click **OK**.

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
<li><a href="https://digital-screen-recording.techidaily.com/new-leading-screenshot-and-record-tools-for-firefox/"><u>[New] Leading Screenshot & Record Tools for Firefox</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-from-mundane-to-memorable-transform-your-social-media-identity-with-these-tips/"><u>[Updated] 2024 Approved From Mundane to Memorable Transform Your Social Media Identity with These Tips</u></a></li>
<li><a href="https://video-capture.techidaily.com/1-comprehensive-upkeep-suite-the-essential-enhancer-pack-for-your-kodi-experience/"><u>1. [Comprehensive Upkeep Suite] - The Essential Enhancer Pack for Your Kodi Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-absence-of-drive-letters-in-windows-os-understanding-issues-solutions/"><u>Decoding Absence of Drive Letters in Windows OS: Understanding Issues, Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-desktop-experience-with-easy-widget-implementation-in-win-11/"><u>Enhance Your Desktop Experience with Easy Widget Implementation in Win 11</u></a></li>
<li><a href="https://win-remarkable.techidaily.com/essential-strategies-for-securing-your-wallet-against-online-threats-insights-from-yl-computing/"><u>Essential Strategies for Securing Your Wallet Against Online Threats - Insights From YL Computing</u></a></li>
<li><a href="https://tech-revival.techidaily.com/exploring-the-downside-why-you-should-think-twice-about-generative-ai-for-messaging-services/"><u>Exploring the Downside: Why You Should Think Twice About Generative AI for Messaging Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-fixing-errors-during-iphone-image-upload-to-windows/"><u>Guidelines for Fixing Errors During iPhone Image Upload to Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-a-detailed-vpna-fake-gps-location-free-review-on-zte-nubia-z60-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, A Detailed VPNa Fake GPS Location Free Review On ZTE Nubia Z60 Ultra | Dr.fone</u></a></li>
<li><a href="https://ai-topics.techidaily.com/new-what-is-ai-background-generator/"><u>New What Is AI Background Generator?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-cures-tackling-11-windows-11-snags/"><u>Quick Cures: Tackling 11 Windows 11 Snags</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-system-operations-task-scheduler-and-batches/"><u>Streamlining System Operations: Task Scheduler & Batches</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ssence-of-youtubes-content-craft-room-for-2024/"><u>The Essence of YouTube's Content Craft Room for 2024</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/the-future-is-now-a-rigorous-evaluation-of-makeblocks-mbot-for-aspiring-young-engineers/"><u>The Future Is Now: A Rigorous Evaluation of Makeblock's mBot for Aspiring Young Engineers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-11s-moment-update-a-symphony-of-new-functions/"><u>Unraveling Windows 11’S Moment Update - A Symphony of New Functions</u></a></li>
</ul></div>

