---
title: "Mastering Excel: A Step-by-Step Guide to Using INDEX and MATCH"
date: 2024-08-28T01:06:57.797Z
updated: 2024-08-29T01:06:57.797Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/d558a627b87b79877888fadd197a60bce9f9f188240e22025a6fa593d0f053ec.jpg
---

## Mastering Excel: A Step-by-Step Guide to Using INDEX and MATCH

### Quick Links

* [VLOOKUP Versus INDEX and MATCH](https://location-social.techidaily.com/in-2024-how-to-changefake-your-samsung-galaxy-f54-5g-location-on-viber-drfone-by-drfone-virtual-android/)
* [INDEX and MATCH Function Basics](https://extra-support.techidaily.com/updated-premium-steadicam-options-for-high-quality-dslr-shoots/)
* [How to Use INDEX and MATCH in Excel](https://extra-approaches.techidaily.com/prime-gold-toned-text-interactive-3d-sites-reviewed-for-2024/)

 While the [VLOOKUP function](https://extra-tips.techidaily.com/integrate-sound-and-sight-web-studio/) is good for finding values in Excel, it has its limitations. With a combination of the INDEX and MATCH functions instead, you can look up values in any location or direction in your spreadsheet.

 The INDEX function returns a value based on a location you enter in the formula while MATCH does the reverse and returns a location based on the value you enter. When you combine these functions, you can find any number or text you need.

##  VLOOKUP Versus INDEX and MATCH

 The difference between these functions and VLOOKUP is that VLOOKUP finds values from left to right. Hence the function's name; VLOOKUP performs a vertical lookup.

 Microsoft best explains [the way VLOOKUP works](https://support.microsoft.com/en-us/office/look-up-values-with-vlookup-index-or-match-68297403-7c3c-4150-9e3c-4d348188976b):

> There are certain limitations with using VLOOKUP---the VLOOKUP function can only look up a value from left to right. This means that the column containing the value you look up should always be located to the left of the column containing the return value.

 Microsoft goes on to say that if your sheet isn't set up in a way where VLOOKUP can help you find what you need, you can use INDEX and MATCH instead. So let's look at how to use INDEX and MATCH in Excel.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
##  INDEX and MATCH Function Basics

 To use these functions together, it's important to understand their purpose and structure.

 The syntax for INDEX in Array Form is

        `INDEX(array, row_number, column_number)`
    
 with the first two arguments required and the third optional.

 INDEX looks up a position and returns its value. To find the value in the fourth row in the cell range D2 through D8, you would enter the following formula:

=INDEX(D2:D8,4)

![INDEX function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/INDEX-ExcelINDEXandMATCH.png) 

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
 The result is 20,745 because that's the value in the fourth position of our cell range.

 For more details on the Array and Reference Forms of INDEX as well as other ways to use this function, take a look at our how-to for [INDEX in Excel](https://youtube-help.techidaily.com/in-2024-the-full-course-on-becoming-a-yt-creator-expert/).

 The syntax for MATCH is `MATCH(value, array, match_type)` with the first two arguments required and the third optional.

 MATCH looks up a value and returns its position. To find the value in cell G2 in the range A2 through A8, you would enter the following formula:

=MATCH(G2,A2:A8)

![MATCH function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/MATCH-ExcelINDEXandMATCH.png) 

 The result is 4 because the value in cell G2 is in the fourth position in our cell range.

 For additional details on the `match_type` argument and other ways to use this function, take a look at our tutorial for [MATCH in Excel](https://extra-guidance.techidaily.com/mirthful-missions-delving-into-the-goofy-movie-vhs-for-2024/).

Related: [How to Find a Value's Position With MATCH in Microsoft Excel](https://extra-guidance.techidaily.com/mirthful-missions-delving-into-the-goofy-movie-vhs-for-2024/) 

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
##  How to Use INDEX and MATCH in Excel

 Now that you know what each function does and its syntax, it's time to put this dynamic duo to work. Below, we'll use the same data as above for INDEX and MATCH individually.

 You'll place the formula for the MATCH function inside the formula of the INDEX function in place of the position to look up.

 To find the value (sales) based on the location ID, you would use this formula:

=INDEX(D2:D8,MATCH(G2,A2:A8))

 The result is 20,745\. MATCH finds the value in cell G2 within the range A2 through A8 and provides that to INDEX which looks to cells D2 through D8 for the result.

![INDEX and MATCH for a cell reference](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/INDEXMATCHG2-ExcelINDEXandMATCH.png) 

 Let's look at another example. We want to know which city has sales that match a certain amount. Using our sheet, you would enter this formula:

=INDEX(B2:B8,MATCH(G5,D2:D8))

 The result is Houston. MATCH finds the value in cell G5 within the range D2 through D8 and provides that to INDEX which looks to cells B2 through B8 for the result.

![INDEX and MATCH for a cell reference](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/INDEXMATCHG5-ExcelINDEXandMATCH.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
 Here's an example using an actual value instead of a cell reference. We'll look for the value (sales) for a specific city with this formula:

=INDEX(D2:D8,MATCH("Houston",B2:B8))

 In the MATCH formula, we replaced the cell reference containing the lookup value with the actual lookup value of "Houston" from B2 through B8 which gives us the result 20,745 from D2 through D8.

 Be sure when you use the actual value to look up, rather than a cell reference, that you enclose it in quotes as shown here.

![INDEX and MATCH for text](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/INDEXMATCHHouston-ExcelINDEXandMATCH.png) 

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
 To obtain that same result by using the location ID instead of the city, we simply change the formula to this:

=INDEX(D2:D8,MATCH("2B",A2:A8))

 Here we changed the MATCH formula to look up "2B" in the cell range A2 through A8 and provide that result to INDEX which then returns 20,745.

![INDEX and MATCH for text](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/INDEXMATCH2B-ExcelINDEXandMATCH.png) 

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
[Basic functions in Excel](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/) like those that help you [add numbers](https://instagram-clips.techidaily.com/updated-2024-approved-unveiling-instagrams-policies-a-musicians-legal-primer/) in cells or [enter the current date](https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-app-on-redmi-note-12-5g-by-stellar-photo-recovery-android-mobile-photo-recover/) are certainly helpful. But when you start adding more data and advancing your data entry or analysis needs, lookup functions like INDEX and MATCH in Excel can be quite useful.

Related: [12 Basic Excel Functions Everybody Should Know](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/)

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
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-how-to-use-a-whiteboard-in-google-meet/"><u>[New] 2024 Approved  How to Use a Whiteboard in Google Meet</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/xceptional-7-cameras-elevating-online-educational-vlogs-for-2024/"><u>[New] Exceptional 7 Cameras Elevating Online Educational Vlogs for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-premier-psone-emulators-enjoy-classic-gaming-again/"><u>[New] In 2024, Premier PsOne Emulators  Enjoy Classic Gaming Again</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-how-to-run-a-sports-youtube-chain-on-macos/"><u>[Updated] 2024 Approved  How to Run a Sports YouTube Chain on MacOS</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-exploring-new-worlds-top-10-sci-fi-metaverse-movie-adventures/"><u>[Updated] Exploring New Worlds  Top 10 Sci-Fi Metaverse Movie Adventures</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-setting-up-snapchat-on-apple-computers-step-by-step/"><u>[Updated] Setting Up Snapchat on Apple Computers Step by Step</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-crafting-a-seamless-gift-discovery-journey/"><u>2024 Approved  Crafting a Seamless Gift Discovery Journey</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correction-of-err-87-incorrect-libraries-loaded-on-winos/"><u>Correction of Err 87: Incorrect Libraries Loaded on WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-win-error-logs-post-blue-screen/"><u>Deciphering Win Error Logs Post-Blue Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-microsofts-defender-on-win11-systems/"><u>Disabling Microsoft's Defender on Win11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-webp-savings-steps-for-changing-chrome-image-format-on-windows/"><u>Eliminate WebP Savings: Steps for Changing Chrome Image Format on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/end-stuck-operator-download-on-windows-heres-how/"><u>End Stuck Operator Download on Windows - Here's How</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidance-resolving-vds-errors-in-windows-1011/"><u>Guidance: Resolving VDS Errors in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-resolve-xc10100bf-file-errors/"><u>Guide to Resolve XC10100BF File Errors</u></a></li>
<li><a href="https://techidaily.com/hard-reset-poco-c55-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Poco C55 in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stop-google-chrome-from-crashing-on-pc/"><u>How to Stop Google Chrome From Crashing on PC</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-can-life360-track-or-see-text-messages-what-can-you-do-with-life360-on-itel-p40-drfone-by-drfone-virtual-android/"><u>In 2024, Can Life360 Track Or See Text Messages? What Can You Do with Life360 On Itel P40? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-lock-your-vivo-y02t-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>In 2024, Lock Your Vivo Y02T Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-proven-ways-in-how-to-hide-location-on-life360-for-meizu-21-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Proven Ways in How To Hide Location on Life360 For Meizu 21 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/initiating-narration-mode-on-windows-11-pc/"><u>Initiating Narration Mode on Windows 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leading-overclock-utilities-and-monitors/"><u>Leading Overclock Utilities & Monitors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-window-recovery-in-win-1011-unlocking-6-methods-for-out-of-sight-panes/"><u>Master Window Recovery in Win 10/11: Unlocking 6 Methods for Out-of-Sight Panes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11s-access-the-guide-to-group-policy-editor/"><u>Mastering Windows 11'S Access: The Guide to Group Policy Editor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-time-management-android-and-windows-calendar-coexistence/"><u>Mastery Over Time Management: Android and Windows Calendar Coexistence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimize-overuse-lower-high-usage-of-interests-on-windows/"><u>Minimize Overuse: Lower High Usage of Interests on Windows</u></a></li>
<li><a href="https://video-capture.techidaily.com/mjolnir-strikes-back-release-day/"><u>Mjölnir Strikes Back! Release Day</u></a></li>
<li><a href="https://win11-tips.techidaily.com/nullifying-windows-update-notifications/"><u>Nullifying Windows Update Notifications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-memory-use-of-antivirus-software-features/"><u>Optimize Memory Use of Antivirus Software Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-stuck-gpsvc-hang-in-windows/"><u>Overcoming the Stuck GPSVC Hang in Windows</u></a></li>
<li><a href="https://extra-hints.techidaily.com/pinnacle-zooctorial-template-repositories/"><u>Pinnacle Zooctorial Template Repositories</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quashing-games-recommendations-on-win11-systems/"><u>Quashing Games Recommendations on Win11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reengineering-windowed-discord-search-for-optimal-performance/"><u>Reengineering Windowed Discord Search for Optimal Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refine-your-terminal-experience-make-it-default/"><u>Refine Your Terminal Experience: Make It Default</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-win11s-dragging-woes-quickly/"><u>Resolve Win11's Dragging Woes Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-faulty-windows-11-license-numbers/"><u>Reviving Faulty Windows 11 License Numbers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-windows-update-settings-quickly/"><u>Reviving Windows Update Settings Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slowing-the-spree-of-lifes-speed-in-your-windowed-world/"><u>Slowing the Spree of Life’s Speed in Your Windowed World</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-nvidia-cp-unauthorized-access-on-windows/"><u>Solving Nvidia CP Unauthorized Access on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speeding-up-the-transfer-tips-for-microsofts-marketplace/"><u>Speeding Up the Transfer: Tips for Microsoft’s Marketplace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-fix-guide-to-replace-msvcr120dll-in-windows/"><u>Step-by-Step Fix Guide to Replace MSVCR120.dll in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-win11-screensaver-personalization/"><u>Step-by-Step Guide to Win11 Screensaver Personalization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-tackle-vac-refusal-message-on-pc/"><u>Steps to Tackle VAC Refusal Message on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-solving-windows-error-messages/"><u>Strategies for Solving Windows Error Messages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-development-wsl-2s-most-effective-methods/"><u>Streamlining Development: WSL 2'S Most Effective Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/struggle-with-mspm-installer-win-fix-guide-needed/"><u>Struggle with MSPM Installer? Win-Fix Guide Needed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-remedies-for-steam-connection-stalls-coded-in-rustwindows/"><u>Swift Remedies for Steam Connection Stalls, Coded in Rust/Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-geforce-now-failure-code-xc0f1103f-on-windows/"><u>Tackling GeForce Now Failure Code XC0F1103F on Windows</u></a></li>
<li><a href="https://some-guidance.techidaily.com/through-the-lens-through-the-mind-advanced-photo-editing-mastery-for-2024/"><u>Through the Lens, Through the Mind  Advanced Photo Editing Mastery for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-windows-experience-efficient-redoing-ahead/"><u>Transform Your Windows Experience: Efficient Redoing Ahead</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-fixing-windows-headset-mic-noise/"><u>Understanding & Fixing Windows Headset Mic Noise</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/unlock-full-potential-of-raw-photos-using-free-darktable-editor-on-os-x-and-linux-platforms/"><u>Unlock Full Potential of Raw Photos Using Free Darktable Editor on OS X & Linux Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/voice-to-text-made-easy-with-openais-whisper-in-your-windows-environment/"><u>Voice-to-Text Made Easy With OpenAI's Whisper in Your Windows Environment</u></a></li>
</ul></div>
