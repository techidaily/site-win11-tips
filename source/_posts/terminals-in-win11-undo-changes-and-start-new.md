---
title: "Terminals in Win11: Undo Changes & Start New"
date: 2024-08-16T02:22:00.525Z
updated: 2024-08-17T02:22:00.525Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Terminals in Win11: Undo Changes & Start New"
excerpt: "This Article Describes Terminals in Win11: Undo Changes & Start New"
keywords: Win11 Terminal Reversal,Win11 Terminal Rollback,Win11 Terminal Restore,Win11 Terminal Reset,New Terminal in Win11,Win11 Terminal Start Fresh,Win11 Terminal Undo Action
thumbnail: https://thmb.techidaily.com/e874e7774ed1bae47e14908261fcbf31de304eed1c8fec16cc5f931b201e9fca.jpg
---

## Terminals in Win11: Undo Changes & Start New

 Windows Terminal is the next-generation command line platform in Windows 11\. It provides an improved user experience with modern command line tools that enable you to access multiple command lines in a single window. The tool is essential for developers and administrators alike, but sometimes your terminal settings need to be reset to default.

 In this article, we will explain how to reset your Windows Terminal settings back to their original state.

## Why Would You Reset Your Windows Terminal?

 Windows Terminal is an amazing tool for power users and developers. It allows you to access a variety of tools, all in one place, with custom settings and themes that make it easy to work from anywhere. But over time, your Windows Terminal may become cluttered with old settings or themes that have become redundant or are no longer relevant.

 It also helps clear out any potentially harmful malware or corrupt files that might be lurking in the background of your system, hindering your productivity. By doing so, you will ensure that your computer works as fast and as smoothly as possible - giving you the most optimal experience when using this powerful tool.

 Let's now move to the below sections and see how it can be reset.

## How to Reset Windows Terminal Settings by Clearing JSON Files

 In order to reset the settings back to the original defaults, you will need to delete the settings.json file. Here's how to do it.

1. Right click on Start and select**Terminal** from the menu list.
2. Next, click the down-arrow icon and select**Settings** .
3. From the left pane of the Settings page, click**Open JSON file** .  
![Open JSON file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-json-file.jpg)
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. If you're asked which app to use to open the file, then double-click on**Notepad** .
5. On the next page, select all the contents and**Delete** them.
6. Now press**Ctrl + S** on your keyboard to save it.

 Next time you open the app, a new configuration with all the default settings will be created automatically.

## How to Reset Windows Terminal Settings Using Command Prompt

 The Command Prompt is a command line tool that can help you accomplish a number of tasks on your computer. It lets you run programs, manage files, and even troubleshoot problems with the operating system. We covered a lot of its functionality in our [beginner's guide to the Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) , but for now, we'll just explore resetting the Windows Terminal settings.

 To reset Windows Terminal Settings back to their defaults, follow these steps:

1. Open the Command Prompt. For this, use the Taskbar search or type "cmd" in the Run dialog.
2. In the Command Prompt window, copy and paste the following command:  
![Reset Windows Terminal Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-command-prompt.jpg)  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
del /f /s /q /a "%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json"
3. Now press the**Enter** key to delete the settings.json file.
4. You can now exit the command prompt.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
## How to Reset Windows Terminal Settings Using Windows PowerShell

 Windows PowerShell is another command line application that you can use to restore Windows Terminal Settings to their default state. To figure out how, follow these steps:

1. Open Windows PowerShell. You can do this by pressing**Win + R** , typing "PowerShell", and then pressing**Enter** . You can also one of the other [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
2. In the PowerShell window, copy and paste the following command:  
![Reset Windows Terminal Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-powershell.jpg)  
Remove-Item -Path "$env:LOCALAPPDATA\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json" -Force
3. Press**Enter** to execute the command.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
## How to Reset Windows Terminal Settings From File Explorer

 If you don't prefer the command line process, you can use Windows File Explorer to reset the settings. In this way, the Terminal will be reset to its default settings, and you can continue using it. Here's how to do it:

1. Open Windows File Explorer. For this, right-click Start and choose**File Explorer** , or press**Win + E** on your keyboard.
2. Copy and paste the following path into the address bar:  
![Reset Windows Terminal Using File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-file-explorer.jpg)  
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState
3. On the next page, right-click on**settings.json** and select**Delete** from the context menu.

 Once you perform the above steps, Settings.json will automatically be created with the default settings.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
## Resetting the Windows Terminal, Made Easy

 After reading this post, you now know some useful tips that will help you reset the terminal to default settings in Windows 11\. Try them out and find out which one works best for you.


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
<li><a href="https://extra-tips.techidaily.com/new-10-best-podcasts-microphones/"><u>[New] 10 Best Podcasts Microphones</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-fusing-visuals-with-acoustic-expressionism/"><u>[New] 2024 Approved  Fusing Visuals with Acoustic Expressionism</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-best-vr-and-action-cameras-beyond-gopros-realm-for-2024/"><u>[New] Best VR and Action Cameras Beyond GoPro's Realm for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-snippetsnapper-a-close-look-at-micro-recorders/"><u>[Updated] 2024 Approved  SnippetSnapper  A Close Look at Micro-Recorders</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-generate-custom-online-comedic-artwork/"><u>[Updated] Generate Custom Online Comedic Artwork</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-claritycleanseapp-top-tier-background-eraser/"><u>2024 Approved  ClarityCleanseApp  Top-Tier Background Eraser</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-instagrowth-hack-secrets-for-scaling-to-1000month-fans/"><u>2024 Approved  InstaGrowth Hack  Secrets for Scaling to 1,000/Month Fans</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-integrating-your-podcast-into-apple-music/"><u>2024 Approved  Integrating Your Podcast Into Apple Music</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-soundtrack-your-life-a-complete-guide-to-adding-personalized-ringtones-and-sounds/"><u>2024 Approved  Soundtrack Your Life  A Complete Guide to Adding Personalized Ringtones & Sounds</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/amazon-basics-tablet-holder-evaluation-portable-solution-for-on-the-go-tech/"><u>Amazon Basics Tablet Holder Evaluation: Portable Solution for On-the-Go Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-with-customized-cmd-shortcuts-and-windows/"><u>Boost Efficiency with Customized Cmd Shortcuts and Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-battlenet-speed-fasten-your-windows-pace/"><u>Boosting Battle.net Speed: Fasten Your Windows Pace</u></a></li>
<li><a href="https://article-helps.techidaily.com/capture-and-keep-your-linkedin-content-with-these-6-powerful-apps-for-2024/"><u>Capture & Keep Your LinkedIn Content with These 6 Powerful Apps for 2024</u></a></li>
<li><a href="https://buynow-info.techidaily.com/comprehensive-analysis-of-vyncs-tracking-tool-and-its-complex-tiered-membership-options/"><u>Comprehensive Analysis of VyNCs Tracking Tool and Its Complex Tiered Membership Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easing-the-heat-cutting-down-vanguard-writes-on-your-computer/"><u>Easing the Heat: Cutting Down Vanguard’ Writes on Your Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-efficient-bluescreenview-use/"><u>Essential Tips for Efficient BlueScreenView Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/experience-gaming-unbound-android-in-desktop-windows-with-google-play-service/"><u>Experience Gaming Unbound: Android in Desktop Windows with Google Play Service</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/highlight-hacks-a-practical-guide-to-boosting-brand-engagement-on-insta-for-2024/"><u>Highlight Hacks  A Practical Guide to Boosting Brand Engagement on Insta for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-audacitys-error-while-opening-sound-device-issue-in-windows-10-and-11/"><u>How to Fix Audacity’s “Error While Opening Sound Device” Issue in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-mute-your-keyboard-on-a-windows-computer/"><u>How to Mute Your Keyboard on a Windows Computer</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-quickly-fix-bluetooth-not-working-on-xiaomi-redmi-note-13-proplus-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Quickly Fix Bluetooth Not Working on Xiaomi Redmi Note 13 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-oneplus-nord-ce-3-5g-phone-without-password-by-drfone-android/"><u>How To Unlock OnePlus Nord CE 3 5G Phone Without Password?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-window-display-mastering-alt-tab-order-in-win1110/"><u>Maximizing Window Display: Mastering Alt-Tab Order in Win11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-low-end-specs-in-windows-game-capture/"><u>Overcoming Low-End Specs in Windows Game Capture</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pitfalls-of-the-promotional-assessing-risks-with-low-price-auth-codes/"><u>Pitfalls of the Promotional: Assessing Risks with Low-Price Auth Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reigning-fast-the-quintessential-wins-performance-aids/"><u>Reigning Fast: The Quintessential Win's Performance Aids</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reintroducing-versatility-beyond-win-1110s-s-mode/"><u>Reintroducing Versatility Beyond Win 11/10'S S Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-w11w10s-refusal-to-open-folders-after-double-clicks/"><u>Resolving W11/W10's Refusal to Open Folders After Double-Clicks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-email-setup-connecting-your-gmail-to-outlook-windows/"><u>Simplifying Email Setup: Connecting Your Gmail to Outlook Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-file-explorer-freezes-in-win11-with-these-fixes/"><u>Stop File Explorer Freezes in Win11 With These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-audio-software-performance-on-windows-with-error-9999/"><u>Streamlining Audio Software Performance on Windows with Error 9999</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-manual-for-chrome-and-windows-11/"><u>The Ultimate Manual for Chrome and Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/three-keys-to-a-cleaner-windows-experience/"><u>Three Keys to a Cleaner Windows Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-server-execution-failed-in-wmp/"><u>Unraveling 'Server Execution Failed' In WMP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-audio-device-isolation-explained/"><u>Windows Audio Device Isolation Explained</u></a></li>
</ul></div>
