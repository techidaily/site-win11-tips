---
title: 4 Routines to Pause Windows & Office Software Updates
date: 2024-07-12T17:20:02.686Z
updated: 2024-07-13T17:20:02.686Z
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
<li><a href="https://win11-tips.techidaily.com/tailored-fn-keys-adjustments-for-microsoft-windows-1011/"><u>Tailored FN Keys Adjustments for Microsoft Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-troubleshooting-and-reviving-dysfunctional-windows-downloads/"><u>Tips for Troubleshooting and Reviving Dysfunctional Windows Downloads</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-netflix-location-to-get-more-country-version-on-honor-x9b-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Netflix Location to Get More Country Version On Honor X9b | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/advanced-video-editing-made-easy-adobe-premiere-pro-on-mac-for-2024/"><u>Advanced Video Editing Made Easy Adobe Premiere Pro on Mac for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-correctly-installing-an-ms-store-app/"><u>Steps for Correctly Installing an MS Store App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sorting-perfection-windows-software-that-shines/"><u>Sorting Perfection: Windows Software That Shines</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-special-features-virtual-location-on-samsung-galaxy-f04-drfone-by-drfone-virtual-android/"><u>How To Use Special Features - Virtual Location On Samsung Galaxy F04? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-your-digital-life-learn-these-5-essential-window-folder-tricks/"><u>Simplify Your Digital Life: Learn These 5 Essential Window Folder Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformative-windows-tips-top-20-cmd-commands/"><u>Transformative Windows Tips: Top 20 CMD Commands</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-6-ways-to-transfer-contacts-from-nokia-c110-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 6 Ways To Transfer Contacts From Nokia C110 to iPhone | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-mystery-of-win11s-disconnected-5g-wi-fi/"><u>Tackling the Mystery of Win11's Disconnected 5G Wi-Fi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-win-11s-proxy-panel/"><u>A Comprehensive Guide to Win 11'S Proxy Panel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-winservicesexe-deciphering-windows-process/"><u>Understanding WinServices.exe: Deciphering Windows Process</u></a></li>
<li><a href="https://fake-location.techidaily.com/spoofing-life360-how-to-do-it-on-tecno-spark-10-4g-drfone-by-drfone-virtual-android/"><u>Spoofing Life360 How to Do it on Tecno Spark 10 4G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/workaround-for-prolonged-shutdown-during-active-windows-10-applications/"><u>Workaround for Prolonged Shutdown During Active Windows 10 Applications</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-earnings-update-navigating-youtube-monetization/"><u>[New] In 2024, Earnings Update  Navigating YouTube Monetization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-elevating-your-wsl-2-and-docker-coexistence/"><u>A Guide to Elevating Your WSL 2 & Docker Coexistence</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-solutions-to-hard-reset-xiaomi-redmi-13c-5g-phone-using-pc-drfone-by-drfone-reset-android-reset-android/"><u>3 Solutions to Hard Reset Xiaomi Redmi 13C 5G Phone Using PC | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-clear-microsofts-watchdog-logs-on-windows/"><u>Techniques to Clear Microsoft's Watchdog Logs on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-advanced-capabilities-with-windows-powershell-policy-settings/"><u>Unlock Advanced Capabilities with Windows PowerShell Policy Settings</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-track-imei-number-of-honor-play-40c-through-google-earth-by-drfone-android/"><u>How To Track IMEI Number Of Honor Play 40C Through Google Earth?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-windows-store-error-code-0x80073cf3/"><u>Steps to Resolve Windows Store Error Code 0X80073CF3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-your-pcs-display-lock-settings/"><u>Tailor Your PC's Display Lock Settings</u></a></li>
<li><a href="https://some-tips.techidaily.com/the-complete-gif-makers-manual-for-2024/"><u>The Complete GIF Maker's Manual for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-rise-of-autonomous-computing-with-windows/"><u>The Rise of Autonomous Computing with Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assessing-windows-subsystem-for-linux-impact/"><u>Assessing Windows Subsystem for Linux Impact</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-workflow-speed-with-effective-fixes-for-excel-on-windows/"><u>Boost Workflow Speed with Effective Fixes for Excel on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-enabling-non-standard-windows-apps/"><u>Strategies for Enabling Non-Standard Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-mending-exception-error-on-win-os/"><u>Understanding and Mending Exception Error on Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-the-art-of-toggling-between-window-terminals-concentration-and-normalcy/"><u>Uncovering the Art of Toggling Between Window Terminal's Concentration and Normalcy</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-sharefake-location-on-whatsapp-for-tecno-phantom-v-fold-drfone-by-drfone-virtual-android/"><u>How to Share/Fake Location on WhatsApp for Tecno Phantom V Fold | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-how-to-clear-steams-dns-cache/"><u>Understanding How to Clear Steam's DNS Cache</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-your-gaming-how-to-fix-the-error-code-0x000-in-xbox-game-pass-on-windows-11/"><u>Streamlining Your Gaming: How to Fix the Error Code 0X000_ in Xbox Game Pass on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategizing-overheating-mitigation-in-windows/"><u>Strategizing Overheating Mitigation in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-printer-removal-procedures-for-windows-11-users/"><u>Swift Printer Removal Procedures for Windows 11 Users</u></a></li>
</ul></div>
