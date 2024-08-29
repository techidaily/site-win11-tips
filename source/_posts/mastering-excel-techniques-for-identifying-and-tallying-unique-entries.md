---
title: "Mastering Excel: Techniques for Identifying and Tallying Unique Entries"
date: 2024-08-28T01:09:05.545Z
updated: 2024-08-29T01:09:05.545Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/5d29a63e1845651f830e0124c103033fe9ea8d7a1b11e86673f2ac375d1ce40d.jpeg
---

## Mastering Excel: Techniques for Identifying and Tallying Unique Entries

### Quick Links

* [Use the COUNTA and UNIQUE Functions](https://change-location.techidaily.com/in-2024-what-pokemon-evolve-with-a-dawn-stone-for-samsung-galaxy-m14-4g-drfone-by-drfone-virtual-android/)
* [Use the SUM and COUNTIF Functions](https://tech-revival.techidaily.com/synthesizing-visuals-seamlessly-gpt-4-meets-dall-e-techniques/)

 You can use the COUNT function and variations to count cells that contain numbers. But what if you want to count only the distinct values in a cell range? We'll show you two ways to count unique values in Excel.

 Both methods we'll explain use a combination of functions and variations of [the COUNT function](https://android-location-track.techidaily.com/how-to-track-a-lost-xiaomi-redmi-note-12t-pro-for-free-drfone-by-drfone-virtual-android/). And because your cell range could include blank cells, we're including alternative formulas to account for this.

Related: [How to Use the COUNT Function in Microsoft Excel](https://android-location-track.techidaily.com/how-to-track-a-lost-xiaomi-redmi-note-12t-pro-for-free-drfone-by-drfone-virtual-android/) 

##  Use the COUNTA and UNIQUE Functions

 This first method is for those who use Excel for [Microsoft 365](https://games-able.techidaily.com/ultimate-console-content-psplus-or-xbox-game-pass/), Excel for the web, Excel 2021, or Excel for iPhone, iPad, or Android phones or tablets. This is because the UNIQUE function is only available in these and later versions of Excel.

 The UNIQUE function provides all distinct values in a cell range. Because you don't want to list those unique values, but count them instead, you'll add the COUNTA function. The COUNTA function [counts nonblank cells](https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-vivo-v29-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/).

 To list the unique values in the cell range A2 through A5, you would use this formula:

=UNIQUE(A2:A5)

 You can see here we have three distinct values listed.

![UNIQUE function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/UniqueFunction-ExcelCountUnique.png) 

 To count those unique values instead of listing them, you add the COUNTA function to the beginning of the formula:

=COUNTA(UNIQUE(A2:A5))

 Now you have the count for those unique values which is 3.

![COUNTA with UNIQUE in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/CountaUniqueFunctions-ExcelCountUnique.png) 

 If the cell range you want to count contains blanks, those will be included as unique values which may cause a problem. To exclude blank cells in your range, you can add the FILTER function to the formula:

 The FILTER function is only available in the versions of Excel listed [above](https://extra-approaches.techidaily.com/updated-prime-10-converters-free-apps-for-efficient-srt-file-transformations/).

=COUNTA(UNIQUE(FILTER(A2:A5,A2:A5<>"")))

 Let's break down the FILTER portion of the formula. `A2:A5,A2:A5` represents the cell range and the criteria to filter which are the same, `<>` represents not equal to, and `""` represents blank.

 As you can see in the screenshot below, the blank cell in our array is not counted as a unique value.

![COUNTA, UNIQUE, and FILTER functions](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/CountaUniqueFilterFunctions-ExcelCountUnique.png) 

Related: [How to Count Cells in Microsoft Excel](https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-vivo-v29-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/) 

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
##  Use the SUM and COUNTIF Functions

 If you're using a version of Excel where the UNIQUE and FILTER functions are unavailable, you can use SUM and [COUNTIF](https://win-forum.techidaily.com/complete-tutorial-clearing-out-windows-10-memory-dump-data/) instead.

 You may also use the same formulas below replacing the SUM function with SUMPRODUCT.

 The [SUM function](https://instagram-videos.techidaily.com/updated-steps-to-instagram-verification-and-fan-growth-in-under-150-characters/) adds numbers and the COUNTIF function counts those cells containing numbers that meet specific criteria.

 To find the unique values in the cell range A2 through A5, use the following formula:

=SUM(1/COUNTIF(A2:A5,A2:A5))

 To break down this formula, the `COUNTIF` function counts the cells with numbers in our range and uses that same cell range as the criteria. That result then is [divided](https://facebook-video-share.techidaily.com/new-in-2024-breaking-through-youtubes-walls-using-advanced-creator-studio-skills/) by `1` and the `SUM` function adds the remaining values.

![SUM and COUNTIF functions in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/SumCountifFunctions-ExcelCountUnique.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->
 Similar to the first method, you can run into issues if you have blanks in your cell range with this method. Only, you'll receive the #DIV/0![error](https://ios-unlock.techidaily.com/in-2024-iphone-12-pro-asking-for-passcode-after-ios-1714-update-what-to-do-by-drfone-ios/) rather than an extra unique value.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
 To eliminate this problem, you can use the following formula:

=SUM((A2:A5<>"")/COUNTIF(A2:A5,A2:A5&""))

 The additional portion for the `COUNTIF` function [concatenates](https://location-social.techidaily.com/in-2024-how-to-sharefake-location-on-whatsapp-for-realme-narzo-60x-5g-drfone-by-drfone-virtual-android/) a blank string to prevent zeroes in the results because you cannot divide by zero. The additional portion for the `SUM` function adds the values that do not equal blank. All of this provides the count of distinct values and also does not count blanks as unique.

![SUM and COUNTIF filtered](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/SumCountifFunctionsFiltered-ExcelCountUnique.png) 

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Finding unique values in Excel doesn't have to be a difficult task. By using the [functions and formulas](https://games-able.techidaily.com/is-premium-play-on-demand-worth-it/) here, you should see those distinct values in no time!

Related: [Functions vs. Formulas in Microsoft Excel: What's the Difference?](https://games-able.techidaily.com/is-premium-play-on-demand-worth-it/)

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
<li><a href="https://article-helps.techidaily.com/new-in-2024-budget-savvy-gopro-upgrades-for-starters/"><u>[New] In 2024, Budget Savvy GoPro Upgrades for Starters</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-transform-your-ig-story-with-melodic-elements-without/"><u>[New] Transform Your IG Story with Melodic Elements (Without)</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-magix-video-pro-x-review/"><u>[Updated] 2024 Approved  Magix Video Pro X Review</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-from-still-shots-to-moving-images-ipads-timelapse-magic/"><u>[Updated] From Still Shots to Moving Images  IPad's Timelapse Magic</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-sharing-youtube-content-on-facebook-a-step-by-step-guide/"><u>[Updated] Sharing YouTube Content on Facebook  A Step-by-Step Guide</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-youtubes-best-lighting-tools-ranked-17-1/"><u>[Updated] YouTube's Best Lighting Tools Ranked #17-1</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-line-concoctions-5-hilarious-tricks-at-work/"><u>Command Line Concoctions: 5 Hilarious Tricks at Work</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correction-of-windows-1011-zoom-failure-code-1132/"><u>Correction of Windows 10/11 Zoom Failure - Code 1132</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-to-fix-mouse-moving-on-its-own/"><u>Easy to Fix Mouse Moving on Its Own</u></a></li>
<li><a href="https://win11-tips.techidaily.com/extending-displayed-apps-on-w11-start-screen/"><u>Extending Displayed Apps on W11 Start Screen</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-honor-x8b-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Honor X8b | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-steam-error-on-windows-no-more-blank-screens/"><u>Fixing Steam Error on Windows: No More Blank Screens</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-activate-and-use-life360-ghost-mode-on-vivo-y78plus-drfone-by-drfone-virtual-android/"><u>How To Activate and Use Life360 Ghost Mode On Vivo Y78+ | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-develop-a-trusted-window-icon-for-safe-hardware-disconnect-in-win11/"><u>How to Develop a Trusted Window Icon for Safe Hardware Disconnect in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-overcome-hard-drive-read-failure-in-windows/"><u>How to Overcome Hard Drive Read Failure in Windows</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-15-top-rated-screen-capture-tools-to-support-education/"><u>In 2024, 15 Top-Rated Screen Capture Tools to Support Education</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-android-to-apple-how-to-transfer-photos-from-honor-magic-5-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Android to Apple How To Transfer Photos From Honor Magic 5 to iPad Easily | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-transitioning-smoothly-the-technology-enhancers-handbook/"><u>In 2024, Transitioning Smoothly  The Technology Enhancer's Handbook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instantly-install-hyper-v-on-your-windows-11-homesystem/"><u>Instantly Install Hyper-V on Your Windows 11 Homesystem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-phone-calls-into-your-workflow-intel-unison-and-windows-11-guide/"><u>Integrating Phone Calls Into Your Workflow: Intel Unison & Windows 11 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/level-up-on-windows-11-the-seven-must-try-strategies-to-boost-your-gameplay/"><u>Level Up on Windows 11: The Seven Must-Try Strategies to Boost Your Gameplay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-fingertip-input-windows-tutorial/"><u>Mastering Fingertip Input: Windows Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-microsoft-store-error-code-x80131500/"><u>Mastering Microsoft Store Error Code: X80131500</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-mobility-control-deactivation-in-w11/"><u>Mastering Mobility Control Deactivation in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-guide-to-bypass-ms-teams-error-80080300-on-windows-11/"><u>Mastery Guide to Bypass MS Teams Error 80080300 on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-windows-charmap-problems-with-ease/"><u>Mending Windows CharMap Problems with Ease</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-generative-ai-7-common-missteps-and-how-to-dodge-them/"><u>Navigating Generative AI: 7 Common Missteps and How to Dodge Them</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-graphics-shortage-on-enchanted-magic-school-platform/"><u>Overcoming Graphics Shortage on Enchanted Magic School Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-steams-non-syncing-library-files/"><u>Quick Fix for Steam's Non-Syncing Library Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-eradicating-xbox-service-interruption/"><u>Quick Fixes: Eradicating Xbox Service Interruption</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-powerful-cpu-usage-a-compre-cookie/"><u>Reducing Powerful CPU Usage: A Compre Cookie</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-the-disk-read-failure-issue-in-windows/"><u>Remedying the Disk Read Failure Issue in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-unresponsive-windows-webcam/"><u>Remedying Unresponsive Windows Webcam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrecting-disconnected-win-ethernet/"><u>Resurrecting Disconnected Win Ethernet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/selecting-optimal-windows-options-for-switch-gaming-enthusiasts/"><u>Selecting Optimal Windows Options for Switch Gaming Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-taskbar-customization-with-portables/"><u>Simplifying Taskbar Customization with Portables</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-rectifying-white-login-screens-on-win1011-oses/"><u>Steps for Rectifying White Login Screens on Win10/11 OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-locate-and-open-windowsstore-folder/"><u>Steps to Locate and Open WindowsStore Folder</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solutions-to-22h2-windows-setbacks/"><u>Swift Solutions to 22H2 Windows Setbacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-error-0x0000007b-quick-fixes-for-windows/"><u>Taming Error 0X0000007B - Quick Fixes for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-halt-windows-shutdown-clock/"><u>Techniques to Halt Windows Shutdown Clock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/telnet-setup-for-network-connectivity-in-windows-11/"><u>Telnet Setup for Network Connectivity in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-issue-code-30005-failed-file-creation-on-windows/"><u>Troubleshooting Issue Code 30005 - Failed File Creation on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-error-40-in-chrome-browser/"><u>Troubleshooting Windows Error 40 in Chrome Browser</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-gpu-potential-win-friendly-tools-ranked-1-6/"><u>Unleash GPU Potential: Win-Friendly Tools Ranked #1-#6</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-window-slide-show-magic-seven-free-paths-to-success/"><u>Unleash Window Slide Show Magic - Seven Free Paths to Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-optimized-web-linkage-in-your-windows-applications-today/"><u>Unlock Optimized Web Linkage in Your Windows Applications Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/utilizing-windows-11s-auto-hdr-effectively/"><u>Utilizing Windows 11'S Auto HDR Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-wisdom-secrets-to-instant-dossiers-creation/"><u>Win11 Wisdom: Secrets to Instant Dossiers Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-edge-less-design-tips/"><u>Windows 11 Edge-Less Design Tips</u></a></li>
</ul></div>
