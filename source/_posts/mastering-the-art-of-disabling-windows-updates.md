---
title: Mastering the Art of Disabling Windows Updates
date: 2024-08-28T01:09:20.947Z
updated: 2024-08-29T01:09:20.947Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the Art of Disabling Windows Updates
excerpt: This Article Describes Mastering the Art of Disabling Windows Updates
keywords: Windows Update Turn Off Guide,Stop Windows Updates Quickly,Disable Windows Updates Easily,No More Windows Updates,Mastering Windows Update Control,Halt Windows Patches Instantly,Techniques to Avoid Windows Updates
thumbnail: https://thmb.techidaily.com/6b564cfcc68d7fa9fa2ebcc8ac34b00c6e2d610d2ee82b6185002beb469144e3.jpg
---

## Mastering the Art of Disabling Windows Updates

 By default, all your Office apps are set to update themselves automatically in the background. Although this approach keeps your Office apps updated with the latest features and improvements, these updates can sometimes overwhelm you or worse, cause new problems.

 Fortunately, there are several ways to disable automatic Office updates on Windows. Let's go over each of those methods one by one.

## 1\. How to Stop Automatic Office Updates via the Settings App

 Windows lets you check for any pending Office updates directly from the Settings app. This allows you to install Office updates along with other system updates. If you don’t want that, you can disable the**Receive updates for other Microsoft products** option in the Settings app. Here are the steps for the same.

1. Open the**Start menu** and click the**gear icon** to launch the Settings app.
2. Select**Windows Update** from the left sidebar.
3. Select**Advanced options** .
4. Disable the toggle next to**Receive updates for other Microsoft products** .  
![Stop Automatic Office Updates Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/stop-automatic-office-updates-using-the-settings-app.jpg)

## 2\. How to Stop Automatic Office Updates Using One of Its Apps

 You can also opt out of automatic Office updates by using one of its apps, such as Word or Excel. Here’s how you can go about it.

1. Open any Office app, such as Word.
2. Click the**File** menu in the top left corner.
3. Select**Account** from the left pane.
4. Click the**Update Options** drop-down menu in the Manage Account section and choose**Disable Updates** .
5. Select**Yes** to confirm.  
![Stop Office Updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/stop-office-updates.jpg)

 Once you complete the above steps, your Office apps will not check for and install newer updates. Don't worry, you'll still be able to install updates manually.

 If you want to re-enable automatic updates later, use the same steps above and select**Enable Update** in the**Update Options** menu.

## 3\. How to Stop Automatic Office Updates Using the Group Policy Editor

 Another way to disable automatic Office updates is via the Group Policy Editor. It’s worth noting that you can only access the Group Policy Editor on Professional, Education, or Enterprise editions of Windows. If you're on Windows Home, be sure to check out[how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

 By default, the Group Policy Editor does not include any modules for managing Microsoft Office settings. So, in order to stop automatic Office updates via the Group Policy Editor, first, you’ll have to download and install Administrative Templates for Microsoft Office products. Here are the steps for the same.

1. Open up your web browser and head over to Microsoft Download Center to[download the Administrative Template files (ADMX/ADML) for Office apps](https://www.microsoft.com/en-us/download/details.aspx?id=49030) .  
![Download Office Administrative Templates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/download-office-administrative-templates.jpg)
2. Double-click the downloaded**EXE file** to run it.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
3. Accept the license terms and click the**Continue** button.
4. The installer will prompt you for a location to extract the contents. Select an empty folder and hit**OK** .
5. Go to the location where you extracted the files and open the**admx** folder.
6. Select all the**admx files** and press**Ctrl + C** to copy them.
7. Head to**C: > Windows > PolicyDefinitions** folder.
8. Paste all the admx files in the**PolicyDefinitions** folder.  
![Copy Office ADMX files to PolicyDefinitions Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-office-admx-files-to-policydefinitions-folder.jpg)
9. Return to the folder where you extracted the files and open the**admx** folder again.
<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
10. Open the**en-US** folder and copy all the**adml files** within.
11. Head to**C: > Windows > PolicyDefinitions** \>**en-US** folder and paste all the**adml files** .  
![Copy Office ADML files to PolicyDefinitions Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-office-adml-files-to-policydefinitions-folder.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
 After completing the above steps, you’re all set to disable automatic Office updates via the Group Policy Editor. Here are the steps you can follow.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the box and select the first result that appears. This will open the Local Group Policy Editor.
3. Use the left pane to navigate to **Local Computer Policy > Computer Configuration > Administrative Templates > Microsoft Office 2016 > Updates** .
4. Double-click the**Enable Automatic Updates** policy on your right.  
![Stop Automatic Office Updates Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/stop-automatic-office-updates-using-group-policy-editor.jpg)
5. Select the**Disabled** option.
6. Hit**Apply** followed by**OK** .
7. Next, press**Win + R** to open the Run dialog.
8. Type**cmd** in the text box and press**Ctrl + Shift + Enter** to[open Command Prompt with administrative privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
9. Type**gpupdate /force** in the console and hit**Enter** to apply the Group Policy changes.

 If you want to re-enable automatic updates for Office apps later, simply set the**Enable Automatic Updates** policy to**Enabled** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
## 4\. How to Stop Automatic Office Updates With the Registry Editor

 You can also use the Registry Editor to make the above policy change and disable automatic Office updates on your computer. Since Registry Editor holds important settings for Windows and its apps, you should only use this method if you’re comfortable editing the[Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) .

 If you decide to use this method, make sure you back up all the registry files or create a restore point beforehand. If you need help, refer to our guide on[how to create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) and follow the steps outlined there.

 Once you've done that, use the following steps to disable automatic Office updates via the Registry Editor.

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **Computer > HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft** .  
![Registry Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor.jpg)
5. Right-click the**Microsoft** key and select**New > Key** .
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Rename the key as**Office** .
2. Right-click on the**Office** key and select**New > Key** .
3. Rename the key as**16.0** .
4. Right-click the**16.0** key and select**New > Key** .
5. Rename the key as**Common** .
6. Within the**Common** key, create another key named**OfficeUpdate** .
7. Right-click the**OfficeUpdate** key and select**New > DWORD (32-bit) Value** . Name this new DWORD**EnableAutomaticUpdates** .
8. Double-click**EnableAutomaticUpdates** DWORD and set its**Value Data** to**0** .
9. Click**OK** .  
![Turn Off Automatic Office Updates Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-off-automatic-office-updates-using-registry-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
 After completing the above steps, restart your computer. Following that, Office apps won’t update automatically on your computer. If you want to undo this change, open the Registry Editor again and delete the**EnableAutomaticUpdates** DWORD.

## Stop Automatic Office Updates on Windows

 It is almost always preferable to keep your Office apps up to date so that you can benefit from new features and security updates. Hence, if you disable automatic Office updates for some reason, don’t forget to check for new updates manually every once in a while.


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
<li><a href="https://youtube-videos.techidaily.com/new-editing-savvy-streamlining-your-youtube-video-lengths/"><u>[New] Editing Savvy  Streamlining Your YouTube Video Lengths</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-craft-your-ideal-video-experience-on-vimeo-through-plan-selection/"><u>[New] In 2024, Craft Your Ideal Video Experience on Vimeo Through Plan Selection</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-elevate-engagement-discover-these-top-12-techniques-for-video-success/"><u>[New] In 2024, Elevate Engagement - Discover These Top 12 Techniques for Video Success</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-in-2024-enabling-virtual-reality-on-your-phone-a-step-by-step-approach/"><u>[New] In 2024, Enabling Virtual Reality on Your Phone  A Step-by-Step Approach</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-strategy-cradle-nurturing-market-gains/"><u>[New] In 2024, Strategy Cradle  Nurturing Market Gains</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-leading-video-technology-of-the-year-2024/"><u>[New] The Leading Video Technology of the Year - 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-the-ultimate-instagram-accelerator-unveiling-the-fastest-path-to-follower-fortune-and-fanfare-for-2024/"><u>[New] The Ultimate Instagram Accelerator  Unveiling the Fastest Path to Follower Fortune & Fanfare for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-2024-approved-best-affordable-video-editors-in-the-market-2023-edition/"><u>[Updated] 2024 Approved  Best Affordable Video Editors in the Market - 2023 Edition</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-cutting-edge-tips-for-professional-lunapic-editing-for-2024/"><u>[Updated] Cutting-Edge Tips for Professional LunaPic Editing for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-visual-narrative-magic-mastering-the-art-of-fading-edits-for-2024/"><u>[Updated] Visual Narrative Magic  Mastering the Art of Fading Edits for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-practical-methods-reflecting-video-via-vlc-software/"><u>2024 Approved  Practical Methods  Reflecting Video via VLC Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/close-all-a-guide-to-ending-windows-instances-concurrently/"><u>Close All: A Guide to Ending Windows Instances Concurrently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convenient-start-unveiling-sticky-notes-at-system-launch/"><u>Convenient Start: Unveiling Sticky Notes at System Launch</u></a></li>
<li><a href="https://win-answers.techidaily.com/efficient-techniques-to-unfreeze-chrome-windows-11-expert-tips-for-smooth-browsing/"><u>Efficient Techniques to Unfreeze Chrome Windows 11: Expert Tips for Smooth Browsing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-windows-defense-with-customizable-firewall-options-in-context-menu/"><u>Elevate Windows Defense with Customizable Firewall Options in Context Menu</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/eluding-prying-eyes-privacy-preserving-video-editing-for-2024/"><u>Eluding Prying Eyes  Privacy-Preserving Video Editing for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/empower-windows-to-keep-files-organized-quickly/"><u>Empower Windows to Keep Files Organized Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-write-functionality-of-steam-folders-in-win-11/"><u>Enhancing Write Functionality of Steam Folders in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-taskbars-presence-during-window-maximum-size/"><u>Ensuring Taskbar's Presence During Window Maximum Size</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-writing-aides-for-windows-desktop-users/"><u>Essential Writing Aides for Windows Desktop Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-to-overcome-error-0x80072f8f-0x20000/"><u>Expert Tips to Overcome Error 0X80072f8f - 0X20000</u></a></li>
<li><a href="https://win11-tips.techidaily.com/five-proactive-tactics-to-rectify-network-key-errors-on-windows-11-systems/"><u>Five Proactive Tactics to Rectify Network Key Errors on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-disconnected-printer-issues-a-step-by-point-guide/"><u>Fixing Disconnected Printer Issues: A Step-By Point Guide</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1723862721549-get-your-hands-on-the-high-end-dell-g16-gaming-laptop-for-only-949-limited-time-offer/"><u>Get Your Hands on the High-End Dell G16 Gaming Laptop for Only $949 - Limited Time Offer</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-a-lost-oneplus-ace-3-for-free-drfone-by-drfone-virtual-android/"><u>How to Track a Lost OnePlus Ace 3 for Free? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-motorola-moto-g84-5g-phone-with-broken-screen-by-drfone-android/"><u>How to Unlock Motorola Moto G84 5G Phone with Broken Screen</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/journey-through-puzzles-the-top-10-websites-buying-mystery-boxes/"><u>Journey Through Puzzles  The Top 10 Websites Buying Mystery Boxes</u></a></li>
<li><a href="https://win-amazing.techidaily.com/latest-toshiba-satellite-driver-downloads-for-windows-users/"><u>Latest Toshiba Satellite Driver Downloads for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-mmc-fixing-missing-snap-ins/"><u>Mastering Windows MMC: Fixing Missing Snap-Ins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/null-device-alert-a-guide-for-win-11-users/"><u>Null Device Alert: A Guide for Win 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-challenges-of-non-responsive-windows-services-manager/"><u>Overcoming The Challenges of Non-Responsive Windows Services Manager</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-unwrite-permission-errors-in-targeted-memory-segment-reference-point-0x/"><u>Overcoming Unwrite Permission Errors in Targeted Memory Segment - Reference Point 0X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalize-folder-options-adding-movecopy-to-context-menu/"><u>Personalize Folder Options: Adding 'Move'/'Copy' To Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-resolving-disk-read-failed-error/"><u>Quick Guide: Resolving 'Disk Read Failed' Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefine-your-window-world-8-customization-strategies-by-winbubble/"><u>Redefine Your Window World: 8 Customization Strategies by WinBubble</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-control-reclaiming-microsoft-store-on-windows-11/"><u>Regaining Control: Reclaiming Microsoft Store on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinventing-the-right-click-experience-for-update-tracking/"><u>Reinventing the Right-Click Experience for Update Tracking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-active-status-to-office-outlook-push-notifications/"><u>Restoring Active Status to Office Outlook Push Notifications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrecting-windows-photo-viewer-on-windows-11-systems/"><u>Resurrecting Windows Photo Viewer on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-guide-setting-up-outlook-preview-on-winos/"><u>Simplified Guide: Setting Up Outlook Preview on WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-ps4-joystick-disconnections-in-windows-environment/"><u>Solving PS4 Joystick Disconnections in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-heic-files-into-jpeg-on-windows-11-platform/"><u>Streamlining HEIC Files Into JPEG on Windows 11 Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-storage-steam-writes-correctly-now/"><u>Streamlining Storage: Steam Writes Correctly Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-resolve-w11-photoshop-not-launching-issue/"><u>Tips to Resolve W11 Photoshop Not Launching Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/total-termination-of-wsl-in-the-windows-11-ecosystem/"><u>Total Termination of WSL in the Windows 11 Ecosystem</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/ultimate-index-ranked-6-fb-lite-downloads/"><u>Ultimate Index  Ranked 6 FB Lite Downloads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-top-7-factors-why-you-shouldnt-upgrade-from-win10-to-win11/"><u>Unveiling Top 7 Factors: Why You Shouldn't Upgrade From Win10 to Win11</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-ispoofer-update-on-itel-a60-drfone-by-drfone-virtual-android/"><u>Will iSpoofer update On Itel A60 | Dr.fone</u></a></li>
</ul></div>
