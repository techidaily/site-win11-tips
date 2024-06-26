---
title: 4 Routines to Pause Windows & Office Software Updates
date: 2024-06-25T16:49:46.648Z
updated: 2024-06-26T16:49:46.648Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 4 Routines to Pause Windows & Office Software Updates
excerpt: This Article Describes 4 Routines to Pause Windows & Office Software Updates
keywords: Pause OS Updates,Stop Office Update,Delay Windows Updates,Windows Freeze Updates,Halt Software Updates,Postpone OS Changes,Stall Windows Patches
thumbnail: https://thmb.techidaily.com/f47c079fa1fce90a8221b9c2c003a393b4231e2fbb42dbd4e99eb8971ba63ab6.jpg
---

## 4 Routines to Pause Windows & Office Software Updates

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
2. Double-click the downloaded**EXE file** to run it.
3. Accept the license terms and click the**Continue** button.
4. The installer will prompt you for a location to extract the contents. Select an empty folder and hit**OK** .
5. Go to the location where you extracted the files and open the**admx** folder.
6. Select all the**admx files** and press**Ctrl + C** to copy them.
7. Head to**C: > Windows > PolicyDefinitions** folder.
8. Paste all the admx files in the**PolicyDefinitions** folder.  
![Copy Office ADMX files to PolicyDefinitions Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-office-admx-files-to-policydefinitions-folder.jpg)
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
5. Select the**Disabled** option.
6. Hit**Apply** followed by**OK** .
7. Next, press**Win + R** to open the Run dialog.
8. Type**cmd** in the text box and press**Ctrl + Shift + Enter** to [open Command Prompt with administrative privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
9. Type**gpupdate /force** in the console and hit**Enter** to apply the Group Policy changes.

 If you want to re-enable automatic updates for Office apps later, simply set the**Enable Automatic Updates** policy to**Enabled** .

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
<li><a href="https://win11-tips.techidaily.com/gain-early-access-the-way-into-windows-11-beta/"><u>Gain Early Access: The Way Into Windows 11 Beta</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-error-1053-unresponsive-service-issue/"><u>Tackling Windows Error 1053: Unresponsive Service Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-text-hotkeys-setup-for-custom-snip-tapping-in-win11/"><u>Advanced Text Hotkeys Setup for Custom Snip Tapping in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-correcting-wmp-failures/"><u>Understanding & Correcting WMP Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-oculus-errors-on-ws11wc10-systems/"><u>Troubleshooting Oculus Errors on WS11/WC10 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ignite-innovation-top-picks-from-microsofts-store-2-infuse-your-living-space-with-a-touch-of-history-while-maintaining-modern-comfort-and-style-lets-embark-20/"><u>Ignite Innovation: Top Picks From Microsoft's Store, 2 Infuse Your Living Space with a Touch of History While Maintaining Modern Comfort and Style? Let's Embark on an Exciting Home Decor Journey Together!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decode-fn-key-operations-in-modern-windows-pcs/"><u>Decode FN Key Operations in Modern Windows PCs</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-xiaomi-redmi-12-phone-without-pin-by-drfone-android/"><u>In 2024, How to Unlock Xiaomi Redmi 12 Phone without PIN</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-telescope-truth-expose/"><u>In 2024, Telescope Truth Exposé</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/unlocking-the-secrets-to-efficient-image-capturing-for-2024/"><u>Unlocking the Secrets to Efficient Image Capturing for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/how-does-vidma-stack-up-as-a-screen-recorder-for-2024/"><u>How Does Vidma Stack Up as a Screen Recorder for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-best-10-tiktok-video-editors-to-make-tiktok-videos-onlinew-indowspc/"><u>[Updated] In 2024, Best 10 TikTok Video Editors to Make TikTok Videos Online/W Indows/PC</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-vivo-s17t-drfone-by-drfone-virtual-android/"><u>How to Get and Use Pokemon Go Promo Codes On Vivo S17t | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-smoothing-out-the-rough-edges-in-photo-booth-videos/"><u>2024 Approved  Smoothing Out The Rough Edges In Photo Booth Videos</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-lock-your-nubia-red-magic-8s-pro-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>In 2024, Lock Your Nubia Red Magic 8S Pro Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-precision-and-efficiency-incorporating-luts-in-after-effects/"><u>[Updated] In 2024, Precision and Efficiency  Incorporating LUTs in After Effects</u></a></li>
</ul></div>
