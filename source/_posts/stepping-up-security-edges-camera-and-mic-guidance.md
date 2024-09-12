---
title: "Stepping Up Security: Edge's Camera & Mic Guidance"
date: 2024-09-11T01:20:43.120Z
updated: 2024-09-12T01:20:43.120Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Stepping Up Security: Edge's Camera & Mic Guidance"
excerpt: "This Article Describes Stepping Up Security: Edge's Camera & Mic Guidance"
keywords: Secure Camera Systems,Enhanced Surveillance Tech,Audio-Visual Integration,Advanced Safety Measures,Edge Security Tools,Real-Time Monitoring Aid,Privacy Protection Innovations
thumbnail: https://thmb.techidaily.com/5c825ad46d87b3691d3904b2e30aab153935e0b73ee1b460d4fca7fb954d5641.jpg
---

## Stepping Up Security: Edge's Camera & Mic Guidance

 Microsoft's Application Guard for Edge is a great tool to shield your browsing from malicious interference. For extra protection, both the camera and microphone are deactivated by default in this environment; however, there may be times when you need these features enabled to utilize certain web applications.

 If that’s the case, follow this guide which will show you how to enable the camera and microphone in Application Guard for Edge on Windows 11\. ​​​​​​





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135396/19272" target="_top" id="2135396">
  <img src="//a.impactradius-go.com/display-ad/19272-2135396" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135396/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 1\. How to Enable the Camera and Microphone via Windows Settings

 To enable the camera and microphone in Application Guard for Edge, follow the steps below:

1. Click on Start, type**Settings** and press**Enter** .
2. On the left side of the screen, select**Privacy & security** .
3. Click the**Windows Security** option on the right.
4. Then, on the next screen, select**App & browser control** .
5. In the new window that opens, click**Change Application Guard settings** under Isolated browsing.
6. Look for the**Camera and microphone** option, and then toggle it on.  
![Enable Camera and Microphone in Application Guard Using Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-camera-and-microphone-in-application-guard-using-windows-settings.jpg)
7. If the UAC prompt appears, click**Yes** to continue.




<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115941/19272" target="_top" id="2115941">
  <img src="//a.impactradius-go.com/display-ad/19272-2115941" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115941/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->





 After you perform the above action, restart your computer for the changes to take effect. Upon restarting, all your camera and microphone settings should now be applied to the Application Guard for Edge.

 In case you need to turn off the feature again, just follow the same steps and toggle the Camera and microphone option to Off. That’s all there is to it.





<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136618/26400" target="_top" id="2136618">
  <img src="//a.impactradius-go.com/display-ad/26400-2136618" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136618/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 2\. How to Enable the Camera and Microphone Using Registry Editor

 If you are more comfortable using the registry editor, you can enable your camera and microphone for Application Guard for Edge. All you need to do is open up the registry folder, make a few easy modifications, and restart your computer so that they can take effect.

 However, before you make any changes, it's essential that you[create a backup of the registry file](https://www.makeuseof.com/tag/backup-restore-windows-registry/) just in case something goes wrong.

 To enable your mic & camera with the help of this tool, follow these steps:

1. Search for**regedit** in the Windows search bar and click on the result to open the registry editor. To find out more, see[how to open the registry](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. When the UAC prompt appears, click**Yes** to confirm.
3. In the Registry Editor window, go to the following location:  
Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Hvsi  
 Copy and paste the given location into the address bar at the top of the registry window and press Enter to quickly jump to the folder.
4. If you don't see the**Hvsi** key there, you need to create it first. In order to do this, right-click on the**Microsoft** folder and select**New > Key** .
5. Name the file**Hvsi** , then hit**Enter** to save it.  
![Creating a new DWORD (32-bit) Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-dword-enableclipboard-key.jpg)
6. Right-click on Hvsi, choose**New > DWORD (32-bit) Value** , then name it**EnableCameraMicrophoneRedirection** .




<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115914/19272" target="_top" id="2115914">
  <img src="//a.impactradius-go.com/display-ad/19272-2115914" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115914/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




7. Now double-click on the newly created DWORD key, and you will see a pop-up window appear.
8. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Camera and Microphone in Application Guard Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-camera-and-microphone-in-application-guard-using-registry-editor.jpg)
9. Then click**OK** to save the changes.




<!-- affiliate ads begin -->
<span id="1770776">
					<video width="240" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1770776.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20702-1770776">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1770776.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftokenmetrics.sjv.io%2Fc%2F5597632%2F1770776%2F20702'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1770776/20702" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->





 Once you've done editing the registry, restart your computer to apply the changes. After restarting, Edge's Application Guard will be able to access your camera and microphone hardware for websites that require it.

 If you want to revert the changes, simply set the EnableCameraMicrophoneRedirection key’s value back to**0** and restart your computer.





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135369/19272" target="_top" id="2135369">
  <img src="//a.impactradius-go.com/display-ad/19272-2135369" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135369/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Your Camera and Mic Is Now Supported in Edge Application Guard

 Application Guard for Edge is a tool that serves as an extra layer of protection from malicious websites and other threats. By default, your camera and microphone are disabled to ensure maximum security. In this guide, we've explained two quick ways in which you can easily activate these features - via Windows Settings or Registry Editor.


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
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-bridging-the-gap-with-magix-music-maker-for-beginners/"><u>[New] 2024 Approved Bridging the Gap with Magix Music Maker for Beginners</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-expert-picks-for-superior-steadicams-in-aerial-cinema/"><u>[New] Expert Picks for Superior Steadicams in Aerial Cinema</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-from-bites-to-blocks-top-10-video-editing-principles/"><u>[Updated] In 2024, From Bites to Blocks Top 10 Video Editing Principles</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-live-techniques-lowering-volume-gradually/"><u>[Updated] Live Techniques Lowering Volume Gradually</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-top-7-strategies-for-delicious-food-vids/"><u>[Updated] Top 7 Strategies for Delicious Food Vids</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-essential-guide-to-making-youtube-thumbnails-for-mobile-storytellers/"><u>2024 Approved The Essential Guide to Making YouTube Thumbnails for Mobile Storytellers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/access-real-time-forex-data-with-ease-incorporating-current-exchange-rates-into-your-excel-worksheets/"><u>Access Real-Time Forex Data with Ease: Incorporating Current Exchange Rates Into Your Excel Worksheets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-tips-for-multi-page-excel-prints-repeating-data-with-ease/"><u>Advanced Tips for Multi-Page Excel Prints: Repeating Data with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ditch-manual-data-entry-seamlessly-move-information-from-printed-forms-using-this-smartphone-technique/"><u>Ditch Manual Data Entry: Seamlessly Move Information From Printed Forms Using This Smartphone Technique</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-techniques-for-consolidating-and-dividing-cells-within-microsoft-excel-spreadsheets/"><u>Easy Techniques for Consolidating and Dividing Cells Within Microsoft Excel Spreadsheets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-strategies-for-concealing-errors-and-signals-in-your-excel-spreadsheets/"><u>Effective Strategies for Concealing Errors and Signals in Your Excel Spreadsheets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-organize-your-data-with-advanced-indentation-strategies-in-excel/"><u>Efficiently Organize Your Data with Advanced Indentation Strategies in Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-tracking-of-changes-mastering-excels-pivot-table-for-percentage-fluctuation-analysis/"><u>Effortless Tracking of Changes: Mastering Excel's Pivot Table for Percentage Fluctuation Analysis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/establishing-custom-default-typography-setting-standard-fonts-and-sizes-in-new-excel-sheets/"><u>Establishing Custom Default Typography: Setting Standard Fonts & Sizes in New Excel Sheets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/excel-tutorial-building-your-first-radar-chart-from-scratch/"><u>Excel Tutorial: Building Your First Radar Chart From Scratch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-clustering-multiple-pie-graphs-together-in-microsoft-excel-easily-and-accurately/"><u>Guide to Clustering Multiple Pie Graphs Together in Microsoft Excel Easily and Accurately</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-correcting-steam-game-setup-failures-during-updates-or-new-installs/"><u>Guide to Correcting Steam Game Setup Failures During Updates or New Installs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-generating-rng-values-using-microsoft-excel-tools-and-features/"><u>Guide: Generating RNG Values Using Microsoft Excel Tools and Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-how-to-implement-mac-os-x-quick-look-functionality-in-windows/"><u>Guide: How to Implement Mac OS X Quick Look Functionality in Windows</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-refine-your-iphone-hdri-expert-tips-for-clearer-results-in-premiere-pro/"><u>In 2024, Refine Your iPhone HDRI Expert Tips for Clearer Results in Premiere Pro</u></a></li>
<li><a href="https://discover-awesome.techidaily.com/macx-video-converter-for-macos-effortlessly-transform-hdsd-videos-to-ipad-apple-tv-compatible-formats/"><u>MacX Video Converter for macOS - Effortlessly Transform HD/SD Videos to iPad, Apple TV Compatible Formats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-data-representation-crafting-graphs-using-microsoft-excel-tutorials/"><u>Mastering Data Representation: Crafting Graphs Using Microsoft Excel Tutorials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-excel-macros-streamline-your-workflow-and-eliminate-repetitive-chores/"><u>Mastering Excel Macros: Streamline Your Workflow and Eliminate Repetitive Chores</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-microsoft-excel-a-step-by-step-guide-to-utilizing-the-filter-feature/"><u>Mastering Microsoft Excel: A Step-by-Step Guide to Utilizing the Filter Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-core-12-imperative-excel-techniques-you-need-to-familiarize-yourself-with/"><u>Mastering the Core: 12 Imperative Excel Techniques You Need to Familiarize Yourself With</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-your-spreadsheet-techniques-to-change-series-names-in-excel/"><u>Mastering Your Spreadsheet: Techniques to Change Series Names in Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-productivity-replace-complex-excel-formulas-with-chatgpt-for-effortless-solutions/"><u>Maximize Productivity: Replace Complex Excel Formulas with ChatGPT for Effortless Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/must-have-android-apps-for-enhanced-chromebook-functionality/"><u>Must-Have Android Apps for Enhanced Chromebook Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfect-your-data-presentation-with-effective-spell-check-functions-in-excel/"><u>Perfect Your Data Presentation with Effective Spell Check Functions in Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/printing-excel-sheets-made-easy-how-to-show-gridlines-with-rowcolumn-labels/"><u>Printing Excel Sheets Made Easy - How to Show Gridlines with Row/Column Labels</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-recent-calls-back-from-tecno-spark-10-pro-by-fonelab-android-recover-call-logs/"><u>Simple ways to get recent calls back from Tecno Spark 10 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-crafting-and-personalizing-your-own-treemap-visualization-with-excel/"><u>Step-by-Step Guide: Crafting & Personalizing Your Own Treemap Visualization with Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-how-to-create-dynamic-summaries-by-groupingcollapsing-excel-rows/"><u>Step-by-Step Guide: How to Create Dynamic Summaries by Grouping/Collapsing Excel Rows</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-renewed-view-of-sony-s3700-2023-edition-for-2024/"><u>The Renewed View of Sony S3700 2023 Edition for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-motorola-edge-2023-device-by-drfone-android/"><u>The Ultimate Guide How to Bypass Swipe Screen to Unlock on Motorola Edge 2023 Device</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-10-xiaomi-14-android-sim-unlock-apk-by-drfone-android/"><u>Top 10 Xiaomi 14 Android SIM Unlock APK</u></a></li>
<li><a href="https://android-transfer.techidaily.com/top-5-from-oppo-a78-to-iphone-contacts-transfer-apps-and-software-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Top 5 from Oppo A78 to iPhone Contacts Transfer Apps and Software | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/understanding-the-benefits-and-drawbacks-a-comprehensive-review-of-chatgpt-plus/"><u>Understanding the Benefits & Drawbacks: A Comprehensive Review of ChatGPT Plus</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/updated-2024-approved-the-best-boxing-streaming-websites-for-the-latest-match-coverage/"><u>Updated 2024 Approved The Best Boxing Streaming Websites for the Latest Match Coverage</u></a></li>
</ul></div>
