---
title: Tackling Windows 10/11'S Error 0X80073D26 in Xbox App
date: 2025-03-02T20:02:04.749Z
updated: 2025-03-05T00:36:49.568Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling Windows 10/11'S Error 0X80073D26 in Xbox App
excerpt: This Article Describes Tackling Windows 10/11'S Error 0X80073D26 in Xbox App
keywords: Win10ErrorX80073D26Solution,Windows10XboxAppError,FixWindows10XboxError,Xbox10ErrorResolution,Error0X80073D26FixXbox,11XboxOSErrorHandling,SolveXBoxWinErrorCode
thumbnail: https://thmb.techidaily.com/07be777ce45c307461ad22ca534398f5c53e5285da087031d4c184f1389088d2.jpg
---

## Tackling Windows 10/11'S Error 0X80073D26 in Xbox App

 Error 0x80073D26 is an issue that users have widely reported occurring when trying to install or play Xbox Game Pass titles via Microsoft Store. When this issue arises, users get redirected to install the Gaming Services app in the Microsoft Store. Users then see the “Something unexpected happened” error 0x80073D26 message when they try to install (or update) Gaming Services.

 Players can’t enjoy their Xbox Game Pass titles because of error 0x80073D26, which makes this an annoying issue for Xbox Game Pass users. This is how you can fix the Microsoft Store error 0x80073D26 in Windows

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Run the Windows Store App Troubleshooting Tool

 This isn’t the most likely solution for error 0x80073D26, but it’s worth trying since Microsoft Store is a UWP app. Running the Windows Store App troubleshooter might detect a Microsoft Store issue and provide a fix. These are the steps for running the Windows Store App troubleshooting utility:

1. Open Settings and click **System** to view that tab.
2. Next, select **Troubleshoot** to reach three troubleshooting navigation options.
3. Bring up the list of troubleshooting tools by clicking **Other trouble-shooters**.
4. Then click **Run** to launch the Windows Store Apps troubleshooting tool.  
![The Run button for the Windows App Store troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-app-store-troubleshooter.jpg)
5. Apply all troubleshooting suggestions provided within Windows Store Apps window.  

![The Windows Store Apps window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-store-app-troubleshooter.jpg)

 You can run the same troubleshooter tool in Windows 10, but the steps for accessing it are a bit different. Click **Update & Security** \> **Troubleshoot** \> **Additional troubleshooters** in Windows 10’s Settings app. Then select **Windows Store Apps** \> **Run the troubleshooter** to get troubleshooting.

## 2\. Repair and Reset the Microsoft Store App

 Accumulated and corrupted Microsoft Store cache data is a potential cause for error 0x80073D26\. Resetting the Microsoft Store app via Settings or the Command Prompt will clear the app’s data. Try applying both methods in this guide to resetting Microsoft Store. Also, select the **Repair** option for the Microsoft Store just above its **Reset** button in Settings to see if that resolves the issue.

![The Reset button for Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-button-1.jpg)

## 3\. Edit the Registry

 One of the most widely confirmed fixes for error 0x80073D26 is to enter the Registry and delete the GamingServices and GamingServicesNet Registry keys. Although confirmed to work, we still recommend users [back up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before deleting keys. Then follow these steps for editing the registry:

1. Open the Windows Run accessory by right-clicking **Start** on your taskbar and selecting the **Run** option.
2. Input the **regedit** Run command and click **OK** to [launch the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. Copy and paste this key location in the registry address bar:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services`
4. Right-click the **GamingServices** subkey within the Services key to select **Delete** \> **Yes**.  
![The Delete registry key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/delete-option-1.jpg)
5. Click the **GamingServicesNet** key with the mouse’s right button and select the **Delete** \> **Yes** options.

6. Exit Registry Editor and restart your PC.

## 5\. Reinstall the Microsoft Gaming Service

 One of Microsoft’s official resolutions for error 0x80073D26 is to reinstall Gaming Service. This potential solution involves entering three PowerShell commands that will remove the Gaming Service app along with associated registry entries. These are the steps for applying this potential fix:

1. Activate Windows Search by pressing **Win + S**.
2. Enter **PowerShell** inside the file search tool.
3. Open PowerShell with admin rights by right-clicking that app in the search results and selecting **Run as Administrator**.
4. Next, remove the Gaming Service app by entering this command and hitting **Enter**:  
`Get-AppxPackage *gaming services* -allusers | remove-appxpackage -allusers`  
![The remove-app package command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-app-package-command.jpg)
5. Then input these separate commands, pressing **Return** after each:  

`Remove-Item -Path "HKLM:\System\CurrentControlSet\Services\GamingServices" -recurse  

Remove-Item -Path "HKLM:\System\CurrentControlSet\Services\GamingServicesNet" -recurse` 
![The remove-app package command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-app-package-command.jpg)
6. Close out of PowerShell to restart Windows.

7. Reopen Powershell and execute the following command:  
`start ms-windows-store://pdp/?productid=9MWPM2CQNLHN`
8. Then click the **Get** button for installing Gaming Service.

## 5\. Perform Some Generic Windows Fixes for Errors

 Windows is by no means impervious to errors. Fortunately, there are some tricks you can apply to almost every error, including this one.

### Repair System Files

![The Reset button for Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-button-1.jpg)

 To begin with, try repairing system files to see if there are any issues. You can do that by executing a System File Checker scan within the Command Prompt. That tool will check for and repair corrupted system files detected when you run its command. To apply this potential fix, follow the instructions in our [how to run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide.

### Set Windows to Clean Boot

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-services-tab.jpg)

 Another possibility is that a software conflict might be causing error 0x80073D26 to occur on your PC. Setting Windows to clean boot by disabling third-party startup items will likely eliminate such a potential cause. That will stop third-party apps and services that could be conflicting with the Microsoft Store from automatically starting.

 To apply this fix, check out this guide about [clean-booting Windows 10 or 11](https://www.makeuseof.com/clean-boot-windows-11/). Disable startup programs in Task Manager and services in MS Config as covered within that guide; then restart your PC and try installing Microsoft Store games again to see if the issue persists.

### Reinstall the Microsoft Store

![The remove Microsoft Store command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-microsoft-store-command.jpg)

 Some users might need to reinstall the Microsoft Store to fix error 0x80073D26\. Such a resolution might be necessary for fixing wider issues with the Microsoft Store app other potential solutions don’t address.

 There isn’t a standard uninstall option available for Microsoft Store. So, you’ll have to reinstall that app with two PowerShell commands. Our guide about [how to reinstall the Microsoft Store](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) tells you how to apply this potential fix.

### Perform an In-Place Windows Upgrade

 Some Microsoft Store users have also fixed error 0x80073D26 by performing an in-place Windows upgrade. An in-place upgrade is a method for installing the latest Windows 11/10 version without losing any installed software or user files.

 This will likely fix the 0x80073D26 error because it will refresh all of the system's registry entries, the system files, and also upgrade Windows to the latest version.

 Performing a Windows 11 in-place upgrade is relatively straightforward. All you need to do is download the latest Windows 11 ISO file, open it up, and launch the setup wizard from there. Our article about [performing an in-place upgrade of Windows 11](https://www.makeuseof.com/in-place-upgrade-windows-11/) includes full guidelines for how to do this.

![The Windows 11 Setup window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-11-setup-window2.jpg)

 You can also perform a Windows 10 in-place upgrade much the same. One difference is that you’ll need to download a Windows 10 Setup file by clicking **Download tool** on the [Microsoft Windows 10 download webpage](https://www.microsoft.com/en-gb/software-download/windows10). Then select **Upgrade this PC** now in the Windows 10 Setup wizard to install the latest version of the OS.

## Enjoy the Best Xbox Game Pass Games Available on the Microsoft Store

 It’s very likely the potential resolutions covered in this guide will fix error 0x80073D26, as some of them are widely confirmed to work. Hopefully, you can get this error fixed and get back into gaming.

 Players can’t enjoy their Xbox Game Pass titles because of error 0x80073D26, which makes this an annoying issue for Xbox Game Pass users. This is how you can fix the Microsoft Store error 0x80073D26 in Windows

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-lab.techidaily.com/024-approved-content-creators-arena-vs-beta-studio-evolutionary-path/"><u>[New] 2024 Approved Content Creator's Arena Vs. Beta Studio Evolutionary Path</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-cutting-through-steps-posting-tiktok-videos-on-twitter-for-2024/"><u>[New] Cutting Through Steps Posting TikTok Videos on Twitter for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-critical-considerations-when-buying-a-windows-laptop/"><u>Guide to Critical Considerations When Buying a WIndows Laptop</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-exit-dfu-mode-on-iphone-6-plus-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Exit DFU Mode on iPhone 6 Plus? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-a-network-locked-huawei-nova-y91-phone-by-drfone-android/"><u>How to Unlock a Network Locked Huawei Nova Y91 Phone?</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-elevate-your-creative-process-mastering-the-use-of-luts-in-pscc/"><u>In 2024, Elevate Your Creative Process Mastering the Use of LUTs in PSCC</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-obs-studio-showdown-with-bandicam-the-ultimate-test/"><u>In 2024, OBS Studio Showdown with Bandicam The Ultimate Test</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-unlock-your-apple-iphone-14-pro-max-in-minutes-with-iccid-code-everything-you-need-to-know-by-drfone-ios/"><u>In 2024, Unlock Your Apple iPhone 14 Pro Max in Minutes with ICCID Code Everything You Need to Know</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lowering-high-resource-demand-in-device-to-device-interaction-windows/"><u>Lowering High Resource Demand in Device-to-Device Interaction Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-tasks-essential-cmd-command-knowledge/"><u>Mastering Windows Tasks: Essential CMD Command Knowledge</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-spin-flip-and-rotate-the-top-online-video-rotation-services/"><u>New Spin, Flip, and Rotate The Top Online Video Rotation Services</u></a></li>
<li><a href="https://extra-support.techidaily.com/quick-and-simple-facial-masking-in-photos-for-2024/"><u>Quick & Simple Facial Masking in Photos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-error-code-0x00000709/"><u>Resolving Windows Error Code 0X00000709</u></a></li>
<li><a href="https://win11-tips.techidaily.com/synching-gmail-with-outlook-app-for-windows-users/"><u>Synching Gmail with Outlook App for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-time-out-top-strategies-to-jumpstart-windows-installation/"><u>Tackling the Time-Out: Top Strategies to Jumpstart Windows Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-pc-hurdles-steadying-cpu-load-in-rm-toolkit/"><u>Troubleshoot PC Hurdles: Steadying CPU Load in RM Toolkit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-silent-speakers-in-windows-1011/"><u>Troubleshooting Silent Speakers in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveil-the-secrets-of-windows-flexible-fax-interface/"><u>Unveil the Secrets of Windows' Flexible Fax Interface</u></a></li>
<li><a href="https://technical-tips.techidaily.com/mpgmpeg-1-mkv/"><u>무료 MPG/MPEG-1를 사용하여 MKV 형식으로 바꾸기: 모바이비 - 구현 방법</u></a></li>
</ul></div>

