---
title: Solutions for Failed Cloud Operations on Windows Devices
date: 2024-06-25T16:28:50.349Z
updated: 2024-06-26T16:28:50.349Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solutions for Failed Cloud Operations on Windows Devices
excerpt: This Article Describes Solutions for Failed Cloud Operations on Windows Devices
keywords: Cloud Operation Failures,Windows Cloud Issues,Resolving Cloud Errors,Windows Devices Cloud Support,Troubleshooting Cloud Service,Fixing Failed Cloud Operations,Windows Cloud Recovery Options
thumbnail: https://thmb.techidaily.com/ff4b473fea2e89c79aee76abe0eab2251a21420b8834da223e912daed0885bd1.jpg
---

## Solutions for Failed Cloud Operations on Windows Devices

 OneDrive is Microsoft’s cloud storage app included with Windows, and many users save their files to the cloud with it. However, some users have had issues accessing shared OneDrive files because of error 0x80070185\. When users try to copy or download shared OneDrive files, they see this message: “Error 0x80070185: The cloud operation was unsuccessful.”

 Users can’t copy or download shared files from OneDrive once error 0x80070185 appears. If you're also experiencing this issue, here is how you can fix error 0x80070185 in Windows 10 and 11.

## 1\. Log Out and Back Into OneDrive

 First, try logging out and back into your OneDrive account. To do so, you’ll need to unlink your PC with your OneDrive account. This is how you can log out and sign back into OneDrive:

1. Right-click the**OneDrive** icon in the system tray.
2. Click the**Help & Settings** cog button.
3. Select**Settings** to bring up an**Account** tab.  
![The Settings option in OneDrive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/settings-option.jpg)
4. Click the**Unlink this PC** option.  
![The Unlink this PC option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/unlink-this-pc.jpg)
5. Select**Unlink account** to sign out.

1. If a sign-in window doesn’t automatically open, input OneDrive in the Windows search box and select to open it there.
2. Input your OneDrive email address (for your Microsoft account), and click the**Sign in** option.  
![The Sign in button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/sign-in-button.jpg)
3. Enter a password, and press the**Sign in** button.
4. Keep clicking**Next** to reach the last option on the OneDrive setup window.
5. Press the**Open my OneDrive** **folder** button.

## 2\. Free Up Hard Drive Space

 Error 0x80070185 can arise when there’s very little free space available on the local drive. As such, your PC’s hard drive may have insufficient space for the larger files in your OneDrive cloud storage.

 First, check your PC’s drive storage space by launching File Explorer and clicking**This PC** . The C: drive icon there shows you how much free storage is available.

![The Local Disk storage icon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/local-disk-storage-icon.jpg)

 If your PC’s hard drive is full, or close to it, free up some storage space. You can make more space on your hard drive by uninstalling software, deleting unneeded user files, and erasing junk data. Our guide about [how to free up storage space in Windows 11](https://www.makeuseof.com/windows-11-free-up-storage-space/) includes numerous methods for making space on a drive.

## 3\. Reset the OneDrive App

 Corrupted OneDrive cache data is a potential cause for error 0x80070185 that you can address by resetting the app. Reset OneDrive with Run as follows:

1. Bring up the Power User shortcuts menu by pressing the**Win + X** keys.
2. Select**Run** to view that command dialog.
3. Type or paste the following command for resetting OneDrive into Run:  
`%localappdata%\Microsoft\OneDrive\OneDrive.exe /reset`  
![The reset OneDrive Run command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-reset-one-drive-command.jpg)
4. Click**OK** to execute the reset command for OneDrive.
5. If the OneDrive icon doesn’t reappear after the reset, input this command into Run and click**OK** :  
`%localappdata%\Microsoft\OneDrive\onedrive.exe`

## 4\. Sync OneDrive to Another Drive Location

 Do you have another drive partition on your PC? If you do, try linking the OneDrive app with the alternative partition instead. You can sync OneDrive to a different drive location like this:

1. First, unlink the OneDrive app as outlined in steps one to five of this guide’s first potential resolution.
2. Then input the email address and password for the Microsoft account you utilize with the OneDrive app.
3. Press the**Sign in** button.
4. Click the**Change location** option.  
![The Change location option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/change-location-option.jpg)
5. Select an alternative drive partition on your PC to link OneDrive with.
6. Click**Select Folder** to confirm the chosen location.
7. Keep clicking**Next** a few times, and select the**Open my OneDrive folder** option.  
![The Open my OneDrive folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/open-my-onedrive-folder.jpg)

## 5\. Enable the "Always Keep on Device" and "Free Up Space" Options

 Some OneDrive users have confirmed selecting to always keep affected files on the device, along with a "free up space" option, can fix error 0x80070185\. Selecting the "always keep on this device" option makes a OneDrive file available offline.

 This is how you can select those options for an affected OneDrive file:

1. Press**Win + E** to open File Explorer.
2. Click the arrow for your OneDrive storage on the left of Explorer.
3. Right-click the file affected by error 0x80070185 and select**Always keep on this** **device** .  
![The Always keep on this device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/always-keep-on-this-device-option.jpg)
4. Then right-click the same file again to select**Free up** **space** .
5. Repeat these steps for all files you can’t access because of error 0x80070185.

## 6\. Turn Off Any Active Firewalls

 Firewall blocks applied to OneDrive can sometimes cause the error 0x80070185 to occur. We recommend users temporarily turn off firewalls to see if they’re causing this issue. You can turn off the Windows Defender Firewall with the following steps:

1. Click the**Search** box or a magnifying glass icon on your Windows taskbar.
2. Input**Windows Defender Firewall** to find the applet.
3. Select the**Windows Defender Firewall** search result to view the applet in the Control Panel.
4. Click**Turn Windows Defender Firewall on or off** to access the settings.  
![The Windows Defender Firewall applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-defender-firewall-applet.jpg)
5. Select the two**Turn off Windows Defender Firewall** network settings, and click**OK** to apply.  
![The Turn off Windows Defender Firewall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/turn-off-windows-defender-firewall-option.jpg)
6. Return to OneDrive to see if the 0x80070185 error persists with the firewall off.

 It’s also recommended to turn off any third-party firewalls installed. Some antivirus utilities also have firewalls. If you’ve installed any additional security software, select the option to disable its firewall if it has one.

 Should this potential solution resolve error 0x80070185, set up a firewall exception for OneDrive. You can do that for the Windows firewall as instructed in our [how to allow apps through Windows Defender](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) piece. Users with third-party firewalls can allow OneDrive through them with the exclusion settings in their security apps.

## 7\. Reinstall OneDrive

 Reinstalling OneDrive is a solution that’s worked for some users. This will give you a completely fresh and up-to-date OneDrive app. These are the steps for uninstalling and reinstalling OneDrive:

1. Launch Run (see [how to open Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for instructions) and input**ms-settings:appsfeatures** inside its**Open** box.
2. Select**OK** to view Apps & features in Settings.
3. If you’re using Windows 11’s Settings app, click OneDrive’s three-menu button and click**Uninstall** . You can select OneDrive and press**Uninstall** in Windows 10.  
![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-uninstall-option.jpg)
4. Select**Uninstall** for confirmation.
5. Open the [OneDrive page on the Microsoft Store](https://apps.microsoft.com/store/detail/onedrive/9WZDNCRFJ1P3?hl=en-gb&gl=gb) .
6. Click OneDrive’s**Get in Store** button.
7. Select**Open Microsoft Store** to view the OneDrive page in that app.  
![The Get button for OneDrive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/get-button-for-onedrive.jpg)
8. Click**Get** to reinstall OneDrive.

## Access your OneDrive Files again

 OneDrive’s error 0x80070185 is not always easy to fix. However, users have got error 0x80070185 resolved by applying the troubleshooting methods above. Hopefully, one of them will restore access to your affected OneDrive files as well.

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
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-application-was-unable-to-start-0xc000003e-error-in-windows-11-and-11/"><u>How to Fix “The Application Was Unable to Start” 0Xc000003e Error in Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-windows-11s-ms-resource-and-apperror/"><u>Solving Windows 11'S Ms-Resource and AppError</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-restarting-windows-updates/"><u>Mastering the Art of Restarting Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-nvidia-control-panel-access-denied-error-in-windows-1110/"><u>How to Fix the NVIDIA Control Panel “Access Denied” Error in Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-elevate-taskmanager-with-a-new-cli-tab-windows-11/"><u>How to Elevate TaskManager with a New CLI Tab (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-superuser-access-a-step-by-step-guide/"><u>Mastering Superuser Access: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-desktop-layout-app-sizes-in-windows-11/"><u>Mastering Desktop Layout: App Sizes in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719311785872-fix-crashing-file-explorer-on-windows-11-now/"><u>Fix Crashing File Explorer on Windows 11 Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-actions-and-activation-labels-in-dev-tools/"><u>Exploring Actions & Activation Labels in Dev Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-onedrive-overcoming-delayed-folder-upload-errors/"><u>Mastering Windows OneDrive: Overcoming Delayed Folder Upload Errors</u></a></li>
<li><a href="https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-nokia-130-music-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix the Error of Unfortunately the Process.com.android.phone Has Stopped on Nokia 130 Music | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-voice-modulation-mastery-a-guide-to-installing-and-applying-autotune-in-audacity/"><u>Updated In 2024, Voice Modulation Mastery A Guide to Installing and Applying Autotune in Audacity</u></a></li>
<li><a href="https://youtube-help.techidaily.com/how-to-monetize-your-youtube-shorts-simple-steps-for-2024/"><u>How to Monetize Your YouTube Shorts  Simple Steps for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-the-ultimate-guide-to-samsung-galaxy-a14-4g-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Ultimate Guide to Samsung Galaxy A14 4G Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-a-step-by-step-guide-to-finding-the-perfect-flac-converter-online-for-2024/"><u>Updated A Step-by-Step Guide to Finding the Perfect FLAC Converter Online for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/identifying-premium-silent-soundtracks-for-visual-media-for-2024/"><u>Identifying Premium Silent Soundtracks for Visual Media for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-nurturing-nature-in-valheim-top-seed-selection-tips/"><u>[New] Nurturing Nature in Valheim  Top Seed Selection Tips</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-realme-c67-5g-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Realme C67 5G to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-change-location-on-facebook-marketplace-for-samsung-galaxy-s24-drfone-by-drfone-virtual-android/"><u>3 Ways to Change Location on Facebook Marketplace for Samsung Galaxy S24 | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/vimeo-in-a-nutshell-the-video-sharing-experience-for-2024/"><u>Vimeo in a Nutshell  The Video Sharing Experience for 2024</u></a></li>
</ul></div>
