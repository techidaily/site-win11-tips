---
title: Quickly Manipulate Text Illumination in Windows 11
date: 2024-08-16T01:38:44.388Z
updated: 2024-08-17T01:38:44.388Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quickly Manipulate Text Illumination in Windows 11
excerpt: This Article Describes Quickly Manipulate Text Illumination in Windows 11
keywords: WinTextShine Effects,Windows 11 Brighten Text,Quick IllumiWords PC,W11 Text Highlighting,Fast Windows Text Glow,Shiny Windows Text Tool,Accelerate Text Lighting W11
thumbnail: https://thmb.techidaily.com/60fbcd30864e8b21a8752d2636e7944e4f6dffcb372de2311bd231d44717be72.jpg
---

## Quickly Manipulate Text Illumination in Windows 11

 Search highlights is a feature that helps you discover interesting content whenever you launch Windows Search. If you find that they aren’t popping up, there are several ways for you to turn them on. And if you find them to be bothersome, well, you can turn them off and continue enjoying Windows as if they never existed.

 So, keep on reading to find out three ways to turn search highlights on and off.

## 1\. How to Turn Search Highlights On and Off in the Settings App

 Press **Win + I** to open the Settings app. Then, select **Privacy & security** on the left side menu, and then click on **Search permissions** in the right panel.

![the privacy and security page on Windows with Search permissions showing in the right panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions.jpg)

 Scroll down to the **More settings** section, and then click the toggle under **Show search highlights** to turn the feature on or off.

![the Seach permissions page on Windows 11 with the More settings section showing and the toggle for Show search highlights set to on](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions-settings.jpg)

 You should no longer see search lights now.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Turn Search Highlights On and Off in the Local Group Policy Editor

 Press **Win + R** to open the Windows Run dialog box, type **gpedit.msc** in the text box, and then hit the **Enter** key. For more ways to launch the tool, read our guide on [ways to open the Local Group Policy Editor on Windows 11](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

 On the left side menu, navigate to **Computer Configuration > Administrative Templates > Windows Components > Search**. Then, in the right panel, double-click the **Allow search highlights** policy to edit it.

![the Local Group Policy Editor on Windows with the Allow search highlights policy highlighted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/lgpe-windows-allow-search-highlights-policy.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->

 To show search highlights, make sure the **Not Configured** or **Enabled** radio button is checked, and then click **OK**.

![the Allow search highlights policy being edited on Windows and it is set to Not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-search-highlights-not-configured-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To disable search highlights, check the **Disabled** radio button, and then click **OK**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
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
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To turn search highlights off, enter **0** in the **Value data** text box, and then click **OK**.

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-sharing-recording.techidaily.com/new-exploring-new-frontiers-in-gaming-recording-tech/"><u>[New] Exploring New Frontiers in Gaming Recording Tech</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-achieve-hd-video-quality-on-fb-live/"><u>[Updated] 2024 Approved  Achieve HD Video Quality on FB Live</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-explore-the-world-of-fb-live-broadcasting-for-2024/"><u>[Updated] Explore the World of FB Live Broadcasting for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-differentiate-with-style-on-snapchat-top-120plus-narratives-for-your-private-stories/"><u>[Updated] In 2024, Differentiate with Style on Snapchat  Top 120+ Narratives for Your Private Stories</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-blocked-resources-steps-for-windows-users-156-chars/"><u>Clearing Up Blocked Resources: Steps for Windows Users (156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-compromised-windows-defense-in-win-11/"><u>Correcting Compromised Windows Defense in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-linux-setup-not-wsl/"><u>Efficient Linux Setup, Not WSL</u></a></li>
<li><a href="https://extra-information.techidaily.com/effortless-installation-and-fun-with-ifunnys-memes/"><u>Effortless Installation & Fun with iFunny's Memes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-intrusive-credential-prompts-on-windows-11-local-account/"><u>Eliminating Intrusive Credential Prompts on Windows 11 Local Account</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tweaks-for-maximum-performance-in-windows-11/"><u>Essential Tweaks for Maximum Performance in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-unidentified-hardware-errors-win-1110-tips/"><u>Fixing Unidentified Hardware Errors: Win 11/10 Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-1011-unlocking-folders-that-wont-double-click-open/"><u>Fixing Windows 10/11: Unlocking Folders that Won't Double-Click Open</u></a></li>
<li><a href="https://win11-tips.techidaily.com/handling-the-exception-breaking-point-message-in-windows/"><u>Handling the Exception Breaking Point Message in Windows</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-do-you-play-mov-files-on-samsung-galaxy-m34-by-aiseesoft-video-converter-play-mov-on-android/"><u>How do you play .mov files on Samsung Galaxy M34 ?</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-add-your-digital-signature-to-a-word-document-by-ldigisigner-sign-a-word-sign-a-word/"><u>How to Add Your Digital Signature to a Word Document</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-engage-dialer-feature-win-11/"><u>How to Engage Dialer Feature Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reset-error-win11s-uptime-failure-code-0x80246007/"><u>How to Reset Error: Win11’s Uptime Failure, Code 0X80246007</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-5-quick-methods-to-bypass-honor-x50-frp-by-drfone-android/"><u>In 2024, 5 Quick Methods to Bypass Honor X50 FRP</u></a></li>
<li><a href="https://fox-links.techidaily.com/in-2024-mastering-the-art-of-video-enhancement-from-sdr-basics-to-hdr-excellence/"><u>In 2024, Mastering the Art of Video Enhancement  From SDR Basics to HDR Excellence</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-secrets-of-single-stream-success-online-broadcast-tips-and-tricks/"><u>In 2024, Secrets of Single-Stream Success  Online Broadcast Tips and Tricks</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-top-apps-and-online-tools-to-track-honor-90-phone-withwithout-imei-number-by-drfone-android/"><u>In 2024, Top Apps and Online Tools To Track Honor 90 Phone With/Without IMEI Number</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jump-start-your-android-devices-double-clicking-apks-on-win-11/"><u>Jump-Start Your Android Devices: Double-Clicking APKs on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jumpstart-your-silenced-speaker-tech-fix-at-hand/"><u>Jumpstart Your Silenced Speaker - Tech Fix at Hand</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-points-preparing-for-a-full-system-reinstallation/"><u>Key Points: Preparing for a Full System Reinstallation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-power-menus-suppress-dim-screen/"><u>Mastering Windows Power Menus: Suppress Dim Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-conquer-format-missing-on-windows/"><u>Methods to Conquer Format Missing On Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-missing-file-detection-issue-in-win-11/"><u>Mitigating Missing File Detection Issue in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-law-filter-features/"><u>Navigating Through Windows LAW Filter Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-extraction-problem-error-1152-in-windows/"><u>Overcoming Extraction Problem: Error 1152 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-package-access-issues-on-windows-1110-systems/"><u>Overcoming Package Access Issues on Windows 11/10 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-challenge-of-windows-exception-breakpoint-error/"><u>Overcoming the Challenge of Windows Exception Breakpoint Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-hurdle-opening-windows-folders-via-double-click/"><u>Overcoming the Hurdle: Opening Windows' Folders via Double-Click</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/prime-selections-securing-entry-level-channel-monetization-sites-for-2024/"><u>Prime Selections  Securing Entry-Level Channel Monetization Sites for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/real-time-voice-transcription-whisper-desktop-expertise/"><u>Real-Time Voice Transcription: Whisper Desktop Expertise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaim-your-browser-quick-fixes-to-unlock-chrome-on-win11/"><u>Reclaim Your Browser: Quick Fixes to Unlock Chrome on Win11.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redesigning-faded-boot-prompts-steps/"><u>Redesigning Faded Boot Prompts: Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinvigorating-inactive-cleanup-tools-for-win11/"><u>Reinvigorating Inactive Cleanup Tools for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-erratic-mouse-movements-7-solutions/"><u>Resolving Erratic Mouse Movements: 7 Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-phantom-device-mistake-in-windows-1011/"><u>Resolving Phantom Device Mistake in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamping-creativity-microsofts-surface-studio-2-insight/"><u>Revamping Creativity: Microsoft's Surface Studio 2 Insight</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-your-windows-family-safety-solutions-for-malfunctions/"><u>Reviving Your Windows Family Safety: Solutions for Malfunctions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionize-incompatibility-on-windows-without-tools/"><u>Revolutionize Incompatibility on Windows without Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-your-grades-essential-tips-for-efficient-windows-learning/"><u>Skyrocket Your Grades: Essential Tips for Efficient Windows Learning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-ui-resolution-on-new-windows-build/"><u>Streamline UI Resolution on New Windows Build</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-correction-winoss-parsing-error-0exc00ce556/"><u>Swift Correction: WinOSs Parsing Error 0eXC00CE556</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-troublesome-downloads-in-windows-11-networks-2/"><u>Tackling Troublesome Downloads in Windows 11 Networks (2)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-best-choice-selecting-quality-bittorrent-clients/"><u>The Best Choice: Selecting Quality BitTorrent Clients</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-troubleshooting-misused-system-tokens-on-windows/"><u>Tips for Troubleshooting “Misused System Tokens” On Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-top-9-reasons-why-a-pc-is-better-than-a-mac/"><u>Understanding Top 9 Reasons Why a PC Is Better than a Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-wizards-a-how-to-for-cortana-data-extraction/"><u>Windows Wizards: A How-To for Cortana Data Extraction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/wp-apps-face-off-intel-unison-or-microsofts-phone-link/"><u>WP Apps Face-Off: Intel Unison or Microsoft's Phone Link?</u></a></li>
</ul></div>
