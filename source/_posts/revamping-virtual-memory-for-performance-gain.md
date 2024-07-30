---
title: Revamping Virtual Memory for Performance Gain
date: 2024-07-29T08:08:14.510Z
updated: 2024-07-30T08:08:14.510Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Revamping Virtual Memory for Performance Gain
excerpt: This Article Describes Revamping Virtual Memory for Performance Gain
keywords: Virtual Memory Boost,Performance Revamp,Memory Optimization,Enhanced VM Perf,Memory Efficiency,VM Gain Strategies,Performance Memory Update
thumbnail: https://thmb.techidaily.com/5003aae1e7f947a598bd55077396c6a77042379632f2075c2e5462803d44d042.jpg
---

## Revamping Virtual Memory for Performance Gain

 Are you having trouble with virtual memory on Windows 11? Resetting virtual memory on Windows can improve system performance or free up extra hard drive space. So, we'll show you exactly how to reset the virtual memory on your Windows 11 computer.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
## What Is Virtual Memory and How Does It Work?

 Virtual memory, also known as a paging file, is a technology used in computers to allow programs to use more memory than what's physically available on it. When you run out of RAM, your operating system relies on virtual memory to continue running programs.

 The computer creates a special file called a page or swap file on the hard drive. It stores some data temporarily removed from RAM and written to the hard drive. This way, the computer can access more memory than what's installed.

 Although virtual memory allows programs to operate smoothly, it can also hurt overall performance. For example, if your computer runs out of RAM, it will use more of the hard drive to store data. This also significantly slows overall performance as HDDs and SSDs are much slower than RAM.

 Let's now see how to reset Virtual Memory on Windows.

## 1\. Use the System Properties window

 If you want to reset virtual memory settings on your Windows device, you can use the System Properties window. To do this, press **Win + R** on your keyboard to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).

 In the text box, type **sysdm.cpl**, and hit Enter. A system properties window will open up. Then, go to the **Advanced** tab and click the **Settings** button in the Performance section.

![How to Reset Virtual Memory on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/how-to-reset-virtual-memory-on-windows-11.jpg)

 This will open up the Performance Options window, where you can manage virtual memory settings. For this, switch to the **Advanced** tab and click on **Change** in the Virtual Memory section.

<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
![Reset Page Size](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-page-size.jpg)

 On the next screen, uncheck the **Automatically manage paging file size for all drives** checkbox and select the drive you want to configure virtual memory. Normally, this will be the drive on which Windows is installed.

 Set the custom size for virtual memory. Then, check the **No paging file** radio button and click **Set**. If you see a warning message, click **Yes** to confirm.

 After following the above steps, click **OK** to save your changes. Now close the System Properties and Settings windows and restart your computer. The new virtual memory settings should now be in effect.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
## 2\. Use Group Policy Editor

 You can also use the Local Group Policy Editor to reset virtual memory settings on your Windows device. But remember that this method is only available on Pro and Enterprise editions.

 If you're using a Home edition, you should first [enable the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To get started, open the Run dialog box and type **gpedit.msc** into the text box. Then click **OK** or press Enter to open the Local Group Policy Editor window.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Clear virtual memory pagefile Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clear-virtual-memory-pagefile-using-group-policy.jpg)

 Then navigate to the following location:

Local Computer Policy > Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Option

 Scroll down and double-click **Shutdown: Clear virtual memory pagefile** policy. In the Properties window, select Enabled and then click **Apply**. Next, click **OK** to save it.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Use Registry Editor

 If you don't have access to the Local Group Policy Editor, you can also use the Registry Editor to reset virtual memory settings on Windows. Before proceeding, you should [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) in case something gets wrong.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Reset Virtual Memory Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-virtual-memory-using-registry.jpg)

 To get started, search for **Registry Editor** in the Start menu and click on it. Once you open the Registry Editor, navigate to the following path:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Memory Management

 Next, double-click on the **ClearPageFileAtShutdown** key and set its value to **1**. Click on the **OK** button to save your changes.

## Reset Virtual Memory To Get Better Performance

 Resetting virtual memory settings improves Windows computer performance. This guide introduces three methods to learn how to reset virtual memory on Windows. Give it a try and see which methods work best for you. If you face any issues while doing this, you can always use system restore to revert to the previous settings.


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
<li><a href="https://youtube-docs.techidaily.com/024-approved-enlightenment-streams-foremost-ed-resources-online/"><u>[New] 2024 Approved  Enlightenment Streams  Foremost Ed Resources Online</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-top-12-ultimate-relaxing-pc-titles/"><u>[New] 2024 Approved  Top 12 Ultimate Relaxing PC Titles</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-free-skype-mp3-logger-101-guide/"><u>[New] Free Skype Mp3 Logger 101 Guide</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-from-amateur-to-pro-excelling-at-instagram-editing/"><u>[New] From Amateur to Pro  Excelling at Instagram Editing</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-mobile-mastery-the-best-gb-emulation-apps-for-2024/"><u>[New] Mobile Mastery  The Best GB Emulation Apps for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-gain-instagram-reel-fame-emulate-top-tiktok-trends-and-insights/"><u>[Updated] In 2024, Gain Instagram Reel Fame  Emulate Top TikTok Trends & Insights</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-premium-audio-capabilities-1-10-free-desktop-tools/"><u>[Updated] In 2024, Premium Audio Capabilities  #1-#10 Free Desktop Tools</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-the-ultimate-method-to-locate-fb-watched-content/"><u>[Updated] In 2024, The Ultimate Method to Locate FB Watched Content</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-mastering-creative-content-for-fb-video-advertising/"><u>[Updated] Mastering Creative Content for Fb Video Advertising</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-stop-device-freeze-non-playing-fb-videos-for-2024/"><u>[Updated] Stop Device Freeze  Non-Playing FB Videos for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-unlock-picture-perfection-compreenhensive-facetune-review-for-2024/"><u>[Updated] Unlock Picture Perfection  Compreenhensive Facetune Review for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-essence-of-video-editing-filmoras-ten-wonders/"><u>2024 Approved  The Essence of Video Editing  Filmora's Ten Wonders</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-tiletime-effortless-video-mosaics-on-both-oses/"><u>2024 Approved  TileTime  Effortless Video Mosaics on Both OSes</u></a></li>
<li><a href="https://howto.techidaily.com/8-workable-fixes-to-the-sim-not-provisioned-mm2-error-on-motorola-moto-g14-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Workable Fixes to the SIM not provisioned MM#2 Error on Motorola Moto G14 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-failure-code-0x0001-on-nvidia-software/"><u>Addressing Failure Code 0X0001 on Nvidia Software</u></a></li>
<li><a href="https://extra-hints.techidaily.com/beginners-choices-superior-gopro-accessories/"><u>Beginner’s Choices  Superior GoPro Accessories</u></a></li>
<li><a href="https://fox-access.techidaily.com/decoding-the-detailed-workings-of-samsung-photo-editor-app-for-2024/"><u>Decoding the Detailed Workings of Samsung Photo Editor App for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-windows-crash-focus-on-0x800f0831/"><u>Eliminate Windows Crash: Focus on 0X800f0831</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-erroneous-wins-protection-messages/"><u>Fixing Erroneous WINS Protection Messages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-file-failsafe-six-steps-for-correcting-winrar-sums/"><u>Fixing File Failsafe: Six Steps for Correcting WinRAR Sums</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-reinstating-missing-pin-after-win-11-updates/"><u>Guide to Reinstating Missing PIN After Win 11 Updates</u></a></li>
<li><a href="https://change-location.techidaily.com/how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-samsung-galaxy-s24-drfone-by-drfone-virtual-android/"><u>How PGSharp Save You from Ban While Spoofing Pokemon Go On Samsung Galaxy S24? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-change-vivo-y100-5g-lock-screen-clock-in-seconds-by-drfone-android/"><u>How To Change Vivo Y100 5G Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-correct-no-save-photoerror-in-windows-11-os/"><u>How to Correct 'No Save' PhotoError in Windows 11 OS</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-pivot-table-field-name-is-not-valid-error-in-excel-2023-stellar-by-stellar-guide/"><u>How to fix Pivot Table Field Name is not Valid error in Excel 2023? | Stellar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-launch-and-configure-win-11-sandbox/"><u>How to Launch and Configure Win 11 Sandbox</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-quickly-fix-bluetooth-not-working-on-infinix-note-30-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Quickly Fix Bluetooth Not Working on Infinix Note 30 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stop-windows-users-from-changing-the-date-and-time/"><u>How to Stop Windows Users From Changing the Date and Time</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-realme-12plus-5g-phone-password-without-factory-reset-by-drfone-android/"><u>How to Unlock Realme 12+ 5G Phone Password Without Factory Reset?</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-catchemall-celebrate-national-pokemon-day-with-virtual-location-on-apple-iphone-14-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, CatchEmAll Celebrate National Pokémon Day with Virtual Location On Apple iPhone 14 Pro | Dr.fone</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-deciding-on-the-best-videography-camera-type-dslr-or-mirrorless/"><u>In 2024, Deciding on the Best Videography Camera Type  DSLR or Mirrorless?</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-how-to-acquire-version-6-of-windows-movie-maker/"><u>In 2024, How to Acquire Version 6 of Windows Movie Maker</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-learn-the-ins-and-outs-of-twitch-live-stream-archiving/"><u>In 2024, Learn the Ins and Outs of Twitch Live Stream Archiving</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-pokemon-go-cooldown-chart-on-vivo-x-fold-2-drfone-by-drfone-virtual-android/"><u>In 2024, Pokémon Go Cooldown Chart On Vivo X Fold 2 | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-sticker-perfection-ranking-the-top-10-apps-for-ios-and-android-photos/"><u>In 2024, Sticker Perfection  Ranking the Top 10 Apps for iOS and Android Photos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-quick-access-windows-11-screen-grab-utility/"><u>Mastering Quick Access: Windows 11 Screen Grab Utility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-screen-space-removing-windows-overscan-effects/"><u>Maximizing Screen Space: Removing Windows Overscan Effects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-winerror-x8019/"><u>Mitigating WinError: X8019</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-reverse-keyboard-input-on-pcs/"><u>Navigating Reverse Keyboard Input on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/notable-nights-of-non-opening-notepad-your-solution-guide-for-windows-users/"><u>Notable Nights of Non-Opening Notepad: Your Solution Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/novices-guide-to-easy-use-of-windows-accessibility/"><u>Novices' Guide to Easy Use of Windows Accessibility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-methods-creating-new-dossiers-in-win11/"><u>Quick Methods: Creating New Dossiers in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-your-windows-11-ms-store-experience/"><u>Reinstating Your Windows 11 MS Store Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rewind-to-richness-a-guide-to-gaming-glory-past/"><u>Rewind to Richness: A Guide to Gaming Glory Past</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamlessly-change-the-dynamic-background-in-windows-os/"><u>Seamlessly Change the Dynamic Background in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-retrieving-cortana-history-from-windows/"><u>Step-by-Step: Retrieving Cortana History From Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stopping-spontaneous-activation-of-file-explorer/"><u>Stopping Spontaneous Activation of File Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-language-settings-add-and-switch-layouts-in-win-11-os/"><u>Streamlining Language Settings: Add & Switch Layouts in Win 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-wi-fi-troubles-with-ease-filling-out-action-deficiencies/"><u>Tackling Wi-Fi Troubles with Ease: Filling Out Action Deficiencies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-advantages-of-using-dxvk-on-your-windows-system/"><u>The Advantages of Using DXVK on Your Windows System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-best-free-must-have-tools-for-windows-11/"><u>The Best Free Must-Have Tools for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-steam-authentication-lags-in-rustwindows/"><u>Troubleshooting Steam Authentication Lags in Rust/Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turn-your-notes-into-masterpieces-with-obsidian-art/"><u>Turn Your Notes Into Masterpieces with Obsidian Art</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-the-power-of-hyper-v-in-windows-11-homes-with-this-guide/"><u>Unleash the Power of Hyper-V in Windows 11 Homes with This Guide</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/unveiling-secrets-sharper-facebook-videos-on-android-for-2024/"><u>Unveiling Secrets  Sharper Facebook Videos on Android for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/velocity-validation-precise-windows-steps-to-assess-internet-router-performance/"><u>Velocity Validation: Precise Windows Steps to Assess Internet Router Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-dynamic-system-health-enhancement/"><u>Windows' Dynamic System Health Enhancement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/wsls-impact-on-linux-desktop-usage/"><u>WSL's Impact on Linux Desktop Usage</u></a></li>
</ul></div>
