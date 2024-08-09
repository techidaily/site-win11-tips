---
title: "Altering Taskbar Size: Step-by-Step Guide"
date: 2024-08-08T10:57:26.308Z
updated: 2024-08-09T10:57:26.308Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Altering Taskbar Size: Step-by-Step Guide"
excerpt: "This Article Describes Altering Taskbar Size: Step-by-Step Guide"
keywords: Taskbar Resize Tutorial,Windows Adjust Bar,Set Taskbar Width,Modify Taskbar,TaskSize Change Steps,Customizing Bar Size,Alter Taskbar Sizes Guide
thumbnail: https://thmb.techidaily.com/25b0e40b25535b4355b8cca4194992e02cab9c78ac10458526a89f4c7d70d265.jpg
---

## Altering Taskbar Size: Step-by-Step Guide

 Ever looked at the Windows 11 Taskbar and thought it looks too small for your liking? Or maybe you feel it could be a little smaller? If that’s the case, you can change its size to suit your needs by making it bigger or smaller.

 Unlike Windows 10, you can’t just unlock the Taskbar and adjust its size freely in Windows 11\. While Microsoft has removed this way of going about it in Windows 11, there is a workaround that you can use, although it’s not as elegant.

<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How Do I Make the Windows 11 Taskbar Bigger or Smaller?

 The only way to change the size of the Taskbar is to use the Registry Editor. However, we advise caution when dealing with the Windows Registry because if something goes wrong, you might experience performance issues on your Windows 11 PC. If you’re unfamiliar with it, we recommend reading our guides on [what the Windows Registry is](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) and [how to not mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/) .

 Once you’re all caught up or are already familiar with the Windows Registry, and you know what you’re doing, you can make the Taskbar bigger or smaller. To do that:

1. Start by pressing**Win + R** to open Windows Run.
2. Type**regedit** in the text box and hit the**Enter** key.
3. Then, click**Yes** on the UAC prompt to launch the Registry Editor.
4. Copy and paste the below text in the address bar of the Registry Editor and hit the**Enter** key:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. In the**Advanced** key, look for a value called**TaskbarSi** . If it’s not there, right-click**Advanced** , select**New > DWORD (32-bit) Value** , and name that value**TaskbarSi.**  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
![creating a new dword in the advanced key in the Registry Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/new-dword-advanced-regedit.jpg)
6. Double-click**TaskbarSi** to edit it, and then enter**2** in the**Value data** text box and click**OK** to make the Taskbar bigger.  
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![changing the taskbarsi value to 2 in the Registry Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/taskbarsi-value-2.jpg)

 Once you restart your computer, you will see the result: an enlarged Taskbar.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
![an enlarged Taskbar on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-enlarged-taskbar.jpg)

 To make the Taskbar smaller, enter**0** in the**Value data** text box, click**OK** , and then restart your computer. You will then see that the Taskbar has shrunk.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![a smaller taskbar in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-small-taskbar.jpg)

 If you decide to go back to the Taskbar’s default size, you can easily set**Value data** to**1** or simply delete the**TaskbarSi** value.

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Adjust the Taskbar’s Size to Suit Your Needs on Windows 11

 Even though you can’t make the Taskbar bigger or smaller on Windows 11 as easily as you can on Windows 10, a little know-how can help. And as long as you followed the instructions mentioned above correctly, you shouldn’t worry about messing up the Windows Registry. However, we still recommend that you use this method only if you know what you’re doing.


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
<li><a href="https://video-capture.techidaily.com/new-in-2024-noise-control-for-filmmakers-basic-pro-methods-and-pricing/"><u>[New] In 2024, Noise Control for Filmmakers - Basic, Pro Methods & Pricing</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-non-standard-windows-media-development-tools/"><u>[New] Non-Standard Windows Media Development Tools</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-audio-capture-system-testing-guide/"><u>[Updated] Audio Capture System Testing Guide</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-how-to-quickly-modify-photo-resolution-on-an-iphone/"><u>[Updated] How to Quickly Modify Photo Resolution on an iPhone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-enhancing-facebooks-instream-ad-reach-a-detailed-approach/"><u>[Updated] In 2024, Enhancing Facebook's Instream Ad Reach  A Detailed Approach</u></a></li>
<li><a href="https://howto.techidaily.com/4-ways-to-fix-android-blue-screen-of-death-on-samsung-galaxy-a25-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Ways to Fix Android Blue Screen of Death On Samsung Galaxy A25 5G | Dr.fone</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/7-reasons-to-consider-using-chatgpt-for-health-advice/"><u>7 Reasons to Consider Using ChatGPT for Health Advice</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/8-best-apps-for-screen-mirroring-xiaomi-13t-pro-pc-drfone-by-drfone-android/"><u>8 Best Apps for Screen Mirroring Xiaomi 13T Pro PC | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/a-guide-to-incorporating-chatgpt-into-your-digital-audio-workflow-for-superior-sound-effects/"><u>A Guide to Incorporating ChatGPT Into Your Digital Audio Workflow for Superior Sound Effects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-technical-odyssey-embracing-hdr-in-windows-11-environments/"><u>A Technical Odyssey: Embracing HDR in Windows 11 Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blend-in-with-the-background-hide-taskbars-language-bar-win11/"><u>Blend in with the Background: Hide Taskbar's Language Bar, Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-user-interface-add-psoft-tools-to-windows-11/"><u>Boosting User Interface: Add PSoft Tools to Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-audio-subtitle-symphony-streamlining-prime-viewing-in-windows-11/"><u>Decoding Audio-Subtitle Symphony: Streamlining Prime Viewing in Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/dose-life360-notify-me-when-someone-checks-my-location-on-apple-iphone-13-mini-drfone-by-drfone-virtual-ios/"><u>Dose Life360 Notify Me When Someone Checks My Location On Apple iPhone 13 mini? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-subsystem-with-5-crucial-techniques/"><u>Enhancing Windows Subsystem with 5 Crucial Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-vivetool-windows-gateway-to-new-and-emerging-tools/"><u>Exploring ViVeTool: Windows' Gateway to New & Emerging Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-app-install-issues-on-microsoft-store/"><u>Fixing App Install Issues on Microsoft Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-fatal-error-c0000022-in-windows/"><u>How to Fix the Fatal Error C0000022 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-handle-internal-windows-error-during-remote-desktop-use/"><u>How to Handle Internal Windows Error During Remote Desktop Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-swiftly-and-permanently-discard-a-partition-on-windows-pc/"><u>How to Swiftly and Permanently Discard a Partition on Windows PC</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-a-detailed-vpna-fake-gps-location-free-review-on-realme-note-50-drfone-by-drfone-virtual-android/"><u>In 2024, A Detailed VPNa Fake GPS Location Free Review On Realme Note 50 | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-change-credit-card-on-your-apple-iphone-15-pro-apple-id-and-apple-pay-by-drfone-ios/"><u>In 2024, How to Change Credit Card on Your Apple iPhone 15 Pro Apple ID and Apple Pay</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-nokia-105-classic-to-outlook-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Nokia 105 Classic to Outlook | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lowering-resource-usage-in-windows-modules-installer/"><u>Lowering Resource Usage in Windows Modules Installer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-speech-output-in-windows-environment/"><u>Mastering Speech Output in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-efficiency-guide/"><u>Mastering Windows 11: Efficiency Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/nine-must-have-android-apps-for-windows-users/"><u>Nine Must-Have Android Apps for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/peering-into-ftdibussys-an-analysis-of-windows-memory-controls/"><u>Peering Into ftdibus.sys: An Analysis of Windows' Memory Controls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prevent-non-scrollability-of-ranges-in-excel-windows/"><u>Prevent Non-Scrollability of Ranges in Excel, Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-chromes-system-time-a-fix-guide-windows/"><u>Realigning Chrome's System Time: A Fix Guide (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-windows-standard-power-profile/"><u>Restoring Windows' Standard Power Profile</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-file-access-mastering-network-drives-in-win11/"><u>Seamless File Access: Mastering Network Drives in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-error-0x80246007-on-windows-11-updates/"><u>Solving Error 0X80246007 on Windows 11 Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-approach-to-bypassing-no-permission-on-pc/"><u>Step-by-Step Approach to Bypassing 'No Permission' On PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-guide-for-converting-cr2-images-to-windows-jpeg-files/"><u>Stepwise Guide for Converting CR2 Images to Windows JPEG Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stuck-keys-alert-restoring-order-in-windows/"><u>Stuck Keys Alert: Restoring Order in Windows</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-honor-100-pro-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset Honor 100 Pro | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/top-15-augmented-reality-games-like-pokemon-go-to-play-on-honor-100-drfone-by-drfone-virtual-android/"><u>Top 15 Augmented Reality Games Like Pokémon GO To Play On Honor 100 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-xbox-apps-voice-issues-in-windows/"><u>Understanding Xbox App's Voice Issues in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11s-core-data-an-analysis-of-the-registry/"><u>Unlocking Windows 11'S Core Data: An Analysis of the Registry</u></a></li>
</ul></div>
