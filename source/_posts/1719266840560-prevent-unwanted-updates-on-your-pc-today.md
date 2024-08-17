---
title: Prevent Unwanted Updates on Your PC Today!
date: 2024-08-16T01:18:19.879Z
updated: 2024-08-17T01:18:19.879Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Prevent Unwanted Updates on Your PC Today!
excerpt: This Article Describes Prevent Unwanted Updates on Your PC Today!
keywords: Update Prevention Guide,Safe PC Update Tips,Avoid Spurious Updates,Secure PC Maintenance,Halt Unwanted Software,Stop Unnecessary Patches,Guard Your PC Against Updates
thumbnail: https://thmb.techidaily.com/bd9bfd190306deb90b91d858667c2c41b78982227d8d0c9a830c7fb7735e577b.jpg
---

## Prevent Unwanted Updates on Your PC Today

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

 Another way to disable automatic Office updates is via the Group Policy Editor. It’s worth noting that you can only access the Group Policy Editor on Professional, Education, or Enterprise editions of Windows. If you're on Windows Home, be sure to check out [how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

 By default, the Group Policy Editor does not include any modules for managing Microsoft Office settings. So, in order to stop automatic Office updates via the Group Policy Editor, first, you’ll have to download and install Administrative Templates for Microsoft Office products. Here are the steps for the same.

1. Open up your web browser and head over to Microsoft Download Center to [download the Administrative Template files (ADMX/ADML) for Office apps](https://www.microsoft.com/en-us/download/details.aspx?id=49030) .  
![Download Office Administrative Templates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/download-office-administrative-templates.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
2. Double-click the downloaded**EXE file** to run it.
3. Accept the license terms and click the**Continue** button.
4. The installer will prompt you for a location to extract the contents. Select an empty folder and hit**OK** .
5. Go to the location where you extracted the files and open the**admx** folder.
6. Select all the**admx files** and press**Ctrl + C** to copy them.
7. Head to**C: > Windows > PolicyDefinitions** folder.
8. Paste all the admx files in the**PolicyDefinitions** folder.  
![Copy Office ADMX files to PolicyDefinitions Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-office-admx-files-to-policydefinitions-folder.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
9. Return to the folder where you extracted the files and open the**admx** folder again.
10. Open the**en-US** folder and copy all the**adml files** within.
11. Head to**C: > Windows > PolicyDefinitions** \>**en-US** folder and paste all the**adml files** .  
![Copy Office ADML files to PolicyDefinitions Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-office-adml-files-to-policydefinitions-folder.jpg)

 After completing the above steps, you’re all set to disable automatic Office updates via the Group Policy Editor. Here are the steps you can follow.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the box and select the first result that appears. This will open the Local Group Policy Editor.
3. Use the left pane to navigate to **Local Computer Policy > Computer Configuration > Administrative Templates > Microsoft Office 2016 > Updates** .
4. Double-click the**Enable Automatic Updates** policy on your right.  
![Stop Automatic Office Updates Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/stop-automatic-office-updates-using-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
5. Select the**Disabled** option.
6. Hit**Apply** followed by**OK** .
7. Next, press**Win + R** to open the Run dialog.
8. Type**cmd** in the text box and press**Ctrl + Shift + Enter** to [open Command Prompt with administrative privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
9. Type**gpupdate /force** in the console and hit**Enter** to apply the Group Policy changes.

 If you want to re-enable automatic updates for Office apps later, simply set the**Enable Automatic Updates** policy to**Enabled** .

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## 4\. How to Stop Automatic Office Updates With the Registry Editor

 You can also use the Registry Editor to make the above policy change and disable automatic Office updates on your computer. Since Registry Editor holds important settings for Windows and its apps, you should only use this method if you’re comfortable editing the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) .

 If you decide to use this method, make sure you back up all the registry files or create a restore point beforehand. If you need help, refer to our guide on [how to create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) and follow the steps outlined there.

 Once you've done that, use the following steps to disable automatic Office updates via the Registry Editor.

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **Computer > HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft** .  
![Registry Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor.jpg)
5. Right-click the**Microsoft** key and select**New > Key** .

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->

 After completing the above steps, restart your computer. Following that, Office apps won’t update automatically on your computer. If you want to undo this change, open the Registry Editor again and delete the**EnableAutomaticUpdates** DWORD.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-crafting-a-continuous-youtube-video-stream-from-separate-files/"><u>[New] 2024 Approved  Crafting a Continuous Youtube Video Stream From Separate Files</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-top-5-xbox-external-hard-drive/"><u>[New] 2024 Approved  Top 5 Xbox External Hard Drive</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-comprehensive-examination-gopro-hero4-silver-version/"><u>[New] Comprehensive Examination  GoPro HERO4 Silver Version</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-time-tested-tactics-storing-slides-in-ppt/"><u>[New] In 2024, Time-Tested Tactics  Storing Slides in PPT</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-behind-the-screencast-scenes-industry-secrets-revealed/"><u>[Updated] 2024 Approved  Behind the Screencast Scenes  Industry Secrets Revealed</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-optimal-orientation-for-fb-content-creation/"><u>[Updated] 2024 Approved  Optimal Orientation for FB Content Creation</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-swift-systems-for-capturing-content/"><u>[Updated] 2024 Approved  Swift Systems for Capturing Content</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-concoct-clever-caricatures/"><u>[Updated] Concoct Clever Caricatures</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-mastering-idevice-screenshots-latest-techniques/"><u>[Updated] Mastering iDevice Screenshots   Latest Techniques</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-mastering-the-art-of-capturing-live-cricket-action/"><u>[Updated] Mastering the Art of Capturing Live Cricket Action</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-the-ultimate-packing-list-travel-video-edition-for-2024/"><u>[Updated] The Ultimate Packing List  Travel Video Edition for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-crafting-visual-stories-select-the-best-ig-video-editors/"><u>2024 Approved  Crafting Visual Stories  Select the Best IG Video Editors</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-illuminating-seamless-transitions-in-song-production-crossfade/"><u>2024 Approved  Illuminating Seamless Transitions in Song Production (Crossfade)</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-secrets-revealed-streamlined-importation-on-windows-10-os/"><u>2024 Approved  Secrets Revealed  Streamlined Importation on Windows 10 OS</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/a-comprehensive-list-of-top-senior-mobile-plans-dominating-2024-market/"><u>A Comprehensive List of Top Senior Mobile Plans Dominating 2024 Market</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-no-privileges-errors-in-win11-systems/"><u>Correcting No Privileges Errors in Win11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-gpresult-a-key-to-gpo-data-interpretation/"><u>Decoding GPResult: A Key to GPO Data Interpretation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-mechanics-of-windows-exepe/"><u>Decoding the Mechanics of Windows EXE/PE</u></a></li>
<li><a href="https://win11-tips.techidaily.com/did-upgrading-to-windows-11-break-the-windows-subsystem-for-linux-try-these-fixes/"><u>Did Upgrading to Windows 11 Break the Windows Subsystem for Linux? Try These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-linguistic-transitions-mastering-windows-hotkey-combinations/"><u>Effortless Linguistic Transitions: Mastering Windows Hotkey Combinations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-windows-11-to-dolby-atmos-system-level/"><u>Elevate Windows 11 to Dolby Atmos System Level</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-connectivity-configure-dns-on-windows-11/"><u>Enhancing Connectivity: Configure DNS on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/erase-incompatibility-warning-label-in-win11-os/"><u>Erase Incompatibility Warning Label in Win11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/handling-non-microsoft-verified-application-warnings/"><u>Handling Non-Microsoft Verified Application Warnings</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-itel-p40plus-drfone-by-drfone-virtual-android/"><u>How Do I Stop Someone From Tracking My Itel P40+? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-amplify-safety-extending-pin-length-on-win11-devices/"><u>How to Amplify Safety: Extending Pin Length on Win11 Devices</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-fix-apple-id-verification-code-not-working-on-apple-iphone-14-pro-max-by-drfone-ios/"><u>How To Fix Apple ID Verification Code Not Working On Apple iPhone 14 Pro Max</u></a></li>
<li><a href="https://some-techniques.techidaily.com/how-to-host-an-engaging-online-livestream-event-for-2024/"><u>How to Host an Engaging Online Livestream Event for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improving-windows-11-taskbar-stability/"><u>Improving Windows 11 Taskbar Stability</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-avoiding-grainy-zoom-videos-techniques-included/"><u>In 2024, Avoiding Grainy Zoom Videos – Techniques Included</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-oppo-reno-11-pro-5g-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from Oppo Reno 11 Pro 5G to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-uploading-finesse-imovie-videos-meeting-youtube-standards/"><u>In 2024, Uploading Finesse  IMovie Videos Meeting YouTube Standards</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/insightful-evaluation-of-the-latest-lg-360-cam-model-for-2024/"><u>Insightful Evaluation of the Latest LG 360 Cam Model for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-file-management-folder-facelift/"><u>Mastering Windows 11 File Management: Folder Facelift</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modify-aspect-ratio-on-windows-monitors/"><u>Modify Aspect Ratio on Windows Monitors</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/new-complete-guide-of-top-video-language-translators/"><u>New Complete Guide of Top Video Language Translators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-local-sam-service-issues/"><u>Overcoming Local SAM Service Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-quit-required-error-when-using-roblox/"><u>Overcoming Quit Required Error when Using Roblox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/productivity-prodigies-unveiling-the-wins-best-software-solutions/"><u>Productivity Prodigies: Unveiling the Win's Best Software Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revoking-read-only-restriction-on-windows-documents/"><u>Revoking Read-Only Restriction on Windows Documents</u></a></li>
<li><a href="https://win11-tips.techidaily.com/run-a-zero-cost-locally-accessible-gpt-on-your-pc-use-gpt4all/"><u>Run a Zero-Cost, Locally Accessible GPT on Your PC – Use GPT4All.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/start-menu-sleight-stealthy-key-concealment/"><u>Start Menu Sleight: Stealthy Key Concealment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-self-scrolling-in-windows-tips-included/"><u>Stop Self-Scrolling in Windows, Tips Included</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-speed-conquering-windows-11-slowdowns-immediately/"><u>Streamline Speed: Conquering Windows 11 Slowdowns Immediately</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-11-management-processes-settings-and-custom-themes/"><u>Streamlining Windows 11 Management: Processes, Settings, & Custom Themes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-your-slate-device-implementing-windows-11s-user-friendly-taskbar/"><u>Transforming Your Slate Device: Implementing Windows 11'S User-Friendly Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-secrets-where-are-bsod-logs-stored/"><u>Unlocking the Secrets: Where Are BSOD Logs Stored?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-win11s-secrets-to-eliminate-bluescreen-issues/"><u>Unlocking Win11's Secrets to Eliminate Bluescreen Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-the-windows-11-update-error-0x800f0922-heres-how-to-fix-it/"><u>What Is the Windows 11 Update Error 0X800f0922? Here's How to Fix It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/window-warriors-fixed-wobbling-arrows-await/"><u>Window Warriors, Fixed Wobbling Arrows Await</u></a></li>
<li><a href="https://driver-download.techidaily.com/windows-compatible-newest-drivers-and-update-instructions-for-the-nvidia-geforce-mx150/"><u>Windows Compatible: Newest Drivers & Update Instructions for the Nvidia GeForce MX150</u></a></li>
</ul></div>
