---
title: "Mastering Outlook Repair: A Windows User's Manual"
date: 2024-08-08T11:05:07.344Z
updated: 2024-08-09T11:05:07.344Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Outlook Repair: A Windows User's Manual"
excerpt: "This Article Describes Mastering Outlook Repair: A Windows User's Manual"
keywords: Fix Outlook Errors,Windows Mail Troubleshoot,Outlook Problem Solver,Mail App Repair Guide,Office Suite Maintenance,Email Client Restore,Microsoft Mail Fix Tips
thumbnail: https://thmb.techidaily.com/151e2edee1a0284cef5f2216fc95a6d76e6031c7de10b21fb5cd31a56d669f73.jpg
---

## Mastering Outlook Repair: A Windows User's Manual

 Microsoft Outlook's somewhat vague "Something went wrong" error message may appear when you are trying to set up your account or using the app in general. Without a clear indication of what’s going wrong, fixing such Outlook errors can be tricky.

 To help out, we have listed all the possible ways to fix the “Something went wrong” error in Outlook for Windows.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
## 1\. Edit Registry Files

 Autodiscover is a nifty feature that allows Outlook to automatically configure email account settings without requiring manual input from the user. If this service receives any unexpected results from the third-party web server, Outlook might display the "Something went wrong" error message. To resolve this, you will need to make a few changes to the registry files on your PC.

 As you may be aware, making incorrect changes to the registry files can render your system inoperable. Hence, it is advisable to [back up all of your registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Press **Win + R** to open the Run dialog box.
2. Type **regedit** in the box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Paste the following path in the address bar at the top and press **Enter** to quickly navigate to the **AutoDiscover** key.  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Office\XX.0\Outlook\AutoDiscover`  
 Replace **XX.0** in the above path with your version of Office (**16.0** \= Office 365, Office 2019, and Office 2016, **15.0** \= Office 2013).
5. Right-click on the **AutoDiscover** key and select **New > DWORD (32-bit) Value**.  
![Create DWORD in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-dword-in-registry.jpg)

1. Rename the DWORD to **ExcludeHttpsRootDomain**.
2. Double-click the newly created DWORD and set its value to **1**.
3. Right-click on the **AutoDiscover** key again and select **New > DWORD (32-bit) Value**. Name the DWORD **ExcludeHttpsAutoDiscoverDomain**.
4. Double-click the **ExcludeHttpsAutoDiscoverDomain** DWORD and set its value to **1**.
5. Create two more DWORD values named **ExcludeSrvRecord** and **ExcludeLastKnownGoodUrl** and set their values to **1**.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![AutoDiscover in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/autodiscover-in-registry-editor.jpg)

 Restart your PC after this and check if you still get the “Something went wrong” error in Microsoft Outlook.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Open Outlook in Safe Mode

 At times, third-party add-ins in Outlook can disrupt app processes and trigger such errors. To verify if this is the case, you can [try starting Outlook in safe mode](https://www.makeuseof.com/outlook-safe-mode/).

 If Outlook works as expected, it means one of your add-ins is causing the issue. To find the culprit, you'll need to disable all the add-ins and re-enable them one at a time. Here are the steps for the same.

1. In the Outlook app, click on **File > Options**.
2. In the **Outlook Options** window, select the **Add-ins** tab from the left sidebar.
3. Click the **Go** button next to **COM Add-ins**.
4. Clear all the checkboxes to disable your add-ins and then click **OK**.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->
![Disable Outlook Add-Ins-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-outlook-add-ins-1.jpg)

 Restart the Outlook app and enable your add-ins one by one until the error occurs again. Once you find the troublesome add-in, consider removing it to avoid such issues.

## 3\. Clear the Outlook Cache

 Outdated or corrupted cache data can cause Outlook to misbehave and display unusual errors. If this is the cause of your problems, clearing the Outlook app cache should get things going again. To do so, use these steps:

1. Press **Win + R** to open the Run command (see [how to open the Windows Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more information).
2. Type **%localappdata%\\Microsoft\\Outlook** in the text box and press **Enter**.
3. In the **RoamCache** folder that opens, press **Ctrl + A** to select all the files, and click the **trash** icon at the top to delete them.  
![Delete Outlook Cache Data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-outlook-cache-data.jpg)

## 4\. Repair Your Outlook Profile

 Another reason why you may get the “Something went wrong” error in Outlook is if there is an issue with your Outlook profile. You can try repairing your Outlook profile to see if that restores normalcy. Here are the steps for the same.

1. Open the Outlook app and click the **File** menu at the top.
2. In the Info tab, click on **Account Settings** and select **Account Settings**.
3. Select your profile under the **Email** tab and click **Repair**.  
![Repair Outlook Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-outlook-account.jpg)

 Allow Outlook to repair your profile and then restart the app.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## 5\. Remove and Re-Add Your Account

 If repairing your Outlook profile does not help, your next best option is to remove your email account from the Outlook app and add it back. Here's how to do it.

1. Open the Outlook app.
2. Navigate to **File > Info > Account Settings > Account Settings**.
3. Under the **Email** tab, select your account and click **Remove**.
4. Select **Yes** to continue.  
![Remove Outlook Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/remove-outlook-account.jpg)

 Once removed, click the **New** option under the **Email** tab and set up your account again.

## 6\. Remove Outlook Password From Credential Manager

 Are you getting the "Something went wrong" error while adding an account in Outlook? That might be caused by outdated data in the [Credential Manager](https://www.makeuseof.com/windows-credential-manager-guide/). You can try removing any Outlook entries from the Credential Manager to fix the issue.

1. Click the **magnifying icon** on the taskbar.
2. Type **credential manager** in the box and select the first result that appears.
3. Select **Windows Credentials**.
4. Select the entry related to your account and click **Remove**.  
![Remove Outlook Credentials From Windows PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/remove-outlook-credentials-from-windows-pc.jpg)

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
## 7\. Run the Office Repair Tool

 Running Microsoft’s Office repair tool is an effective way to resolve issues with Office apps like Outlook. So, if the above tips don't help, you can run the Office repair tool as a last resort.

1. Press **Win + S** to open the search menu.
2. Type **Control Panel** in the box and press **Enter**.
3. Click the drop-down menu in the top right corner to select **Large icons**.
4. Click on **Programs and Features**.
5. Select **Microsoft Office suite** on the list and click the **Change** button at the top.
6. Select the **Quick Repair** option.
7. Click the **Repair** button.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![Repair Microsoft Office](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/repair-microsoft-office.jpg)

 If the problem persists even after this, repeat the above steps to perform an **Online Repair**. This process may take a little longer, but it’s most likely to resolve the issue.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
## Fixing Outlook's “Something Went Wrong” Error on Windows

 Encountering such errors in the Outlook app can affect your productivity and leave you frustrated. We hope that the solutions listed above have helped in resolving the “Something went wrong” error in Microsoft Outlook.

 That said, if all of the above tips prove ineffective, we recommend you contact the official Microsoft support team for further assistance.

 To help out, we have listed all the possible ways to fix the “Something went wrong” error in Outlook for Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-customizing-facebook-memories-with-look-back-edits/"><u>[New] Customizing Facebook Memories with Look Back Edits</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-advanced-methods-to-archive-your-whatsapp-chat/"><u>[New] In 2024, Advanced Methods to Archive Your WhatsApp Chat</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-boost-clicks-and-conversions-the-top-15-powerful-tools-for-fb-data-analysis/"><u>[Updated] In 2024, Boost Clicks & Conversions  The Top 15 Powerful Tools for FB Data Analysis</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-quick-mac-mastering-screen-recording-via-shortcuts/"><u>[Updated] In 2024, Quick Mac  Mastering Screen Recording via Shortcuts</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-ultimate-razer-webcam-analysis-for-2024/"><u>[Updated] Ultimate Razer Webcam Analysis for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unveiling-the-best-practices-for-linktree-on-tiktok-profiles/"><u>[Updated] Unveiling the Best Practices for Linktree on TikTok Profiles</u></a></li>
<li><a href="https://howto.techidaily.com/9-quick-fixes-to-unfortunately-touchwiz-has-stopped-of-nokia-c300-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Quick Fixes to Unfortunately TouchWiz has stopped Of Nokia C300 | Dr.fone</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/advanced-ai-voice-to-text-apps-for-2024/"><u>Advanced AI Voice to Text Apps for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/approaches-to-addressing-critical-app-issues/"><u>Approaches to Addressing Critical App Issues</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/bringing-classrooms-to-the-future-with-mondly-and-apple/"><u>Bringing Classrooms to the Future with Mondly & Apple</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configure-touch-input-in-windows-enabledisable-steps/"><u>Configure Touch Input in Windows: Enable/Disable Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-error-code-0x887a0006-for-graphics/"><u>Correcting Error Code 0X887A0006 for Graphics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-windows-infamous-blue-screen-issues/"><u>Demystifying Windows' Infamous Blue Screen Issues</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/exploring-vllo-experiences-for-2024/"><u>Exploring VLLO Experiences for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/finding-solutions-to-unacceptable-connections-in-windows-os/"><u>Finding Solutions to Unacceptable Connections in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-crashing-file-explorer-on-windows-11-now/"><u>Fix Crashing File Explorer on Windows 11 Now</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-apple-iphone-11-pro-to-roku-drfone-by-drfone-ios/"><u>How to Mirror Apple iPhone 11 Pro to Roku? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-videos-from-your-tecno-pova-6-pro-5g-by-fonelab-android-recover-video/"><u>How to recover old videos from your Tecno Pova 6 Pro 5G</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-enhancing-visual-storytelling-on-instagram-with-loops/"><u>In 2024, Enhancing Visual Storytelling on Instagram With Loops</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-hacks-to-do-pokemon-go-trainer-battles-for-samsung-galaxy-m14-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Hacks to do pokemon go trainer battles For Samsung Galaxy M14 5G | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-track-imei-number-of-oppo-a56s-5g-through-google-earth-by-drfone-android/"><u>In 2024, How To Track IMEI Number Of Oppo A56s 5G Through Google Earth?</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-unleash-creativity-using-mematic-app/"><u>In 2024, Unleash Creativity Using Mematic App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-install-package-troubleshooting-in-newest-windows-release/"><u>Mastering Install Package Troubleshooting in Newest Windows Release</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-removing-window-search-artifacts/"><u>Mastery Over Removing Window Search Artifacts</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-get-your-plugins-back-on-track-fcpx-troubleshooting-tips-for-2024/"><u>New Get Your Plugins Back on Track FCPX Troubleshooting Tips for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-device-driver-load-failure-in-win11/"><u>Overcoming Device Driver Load Failure in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-challenge-of-restarting-windows-sound-on-booting/"><u>Overcoming the Challenge of Restarting Windows Sound on Booting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-error-code-30015-26-in-m365-for-windows-computers/"><u>Resolving Error Code 30015-26 in M365 for Windows Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stay-connected-tips-for-disabling-usb-power-save-mode/"><u>Stay Connected - Tips for Disabling USB Power Save Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-browsing-efficiency-on-windows/"><u>Streamlining Browsing Efficiency on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-path-to-reinstating-default-windows-backups/"><u>The Path to Reinstating Default Windows Backups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-task-scheduler-guide-to-efficient-batch-processing/"><u>The Task Scheduler Guide to Efficient Batch Processing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-future-windows-laptops-top-picks/"><u>The Ultimate Guide to Future Windows Laptops: Top Picks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-alter-desktop-icons-separation-in-win-oss/"><u>Title: Alter Desktop Icons' Separation in WIN OSs</u></a></li>
<li><a href="https://tech-revival.techidaily.com/transform-your-interview-gameplay-using-chatgpt-insights/"><u>Transform Your Interview Gameplay Using ChatGPT Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-windows-workspaces-into-a-unified-digital-ecosystem-via-aoemi/"><u>Transforming Windows Workspaces Into a Unified Digital Ecosystem via AOEMi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trouble-locating-astra-pilot-help-for-windows-11-pcs/"><u>Trouble Locating Astra Pilot? Help For Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-missing-5ghz-network-on-windows-11-top-7-solutions/"><u>Troubleshoot Missing 5GHz Network on Windows 11: Top 7 Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-variability-in-windows-protocols-for-cloud-and-local-reinstallation/"><u>Understanding Variability in Windows Protocols for Cloud and Local Reinstallation</u></a></li>
<li><a href="https://extra-resources.techidaily.com/understanding-video-storage-in-24-hours/"><u>Understanding Video Storage in 24-Hours</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-folder-customization-adding-movecopy-context-functionality/"><u>Windows 11 Folder Customization - Adding Move/Copy Context Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/your-ultimate-toolkit-to-counteract-bsod-on-win10/"><u>Your Ultimate Toolkit to Counteract BSOD on Win10</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>