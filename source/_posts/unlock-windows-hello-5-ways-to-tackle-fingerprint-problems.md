---
title: "Unlock Windows Hello: 5 Ways to Tackle Fingerprint Problems"
date: 2024-06-25T16:28:06.549Z
updated: 2024-06-26T16:28:06.549Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlock Windows Hello: 5 Ways to Tackle Fingerprint Problems"
excerpt: "This Article Describes Unlock Windows Hello: 5 Ways to Tackle Fingerprint Problems"
keywords: Windows Hello Troubleshooting,Fingerprint Lock Issues,Solve Windows Fingerprint Error,Overcome Windows Hello Failures,Fix Windows Fingerprint Login,Unlock Happy Methods,Windows Fingerprint Security Tips
thumbnail: https://thmb.techidaily.com/1a71493edba37cb030611c5a8b9738f6d63a9069f2561431aa2bb888dda851d0.jpg
---

## Unlock Windows Hello: 5 Ways to Tackle Fingerprint Problems

 Using a fingerprint scanner is perhaps the most convenient way to log in to your Windows computer. It not only eliminates the need to type in a complex password or PIN every time you want to access your computer but also saves you time. But what if Windows Hello fingerprint authentication stops working on your computer?

 Fortunately, there are several ways to fix this annoying issue. So, let’s dive in and explore what you should do when Windows Hello fingerprint login isn’t working.

## 1\. Remove and Re-Register Your Fingerprint

 Your first step is to remove your Windows Hello fingerprint and register it again. This may sound basic, but it is one of the most straightforward ways to get your fingerprint reader to work again. Here are the steps you can follow.

1. Press **Win + I** to open the Settings app.
2. Head to **Accounts > Sign-in options**.
3. Under the **Windows Hello** section, click the **Remove** button.  
![Windows Sign-in Options window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Remove-Windows-Hello-Fingerprint-1.jpg)
4. Once removed, click the **Set up** button and follow the on-screen instructions to register your fingerprint again.

 If the issue persists or if you are unable to remove and re-add your fingerprint due to the "This option is currently unavailable" error on the Windows Hello page, there may be a problem with the Biometric drivers on your PC.

## 2\. Reinstall the Biometric Device Driver

 Biometric drivers on your PC help Windows communicate with your PC's fingerprint scanner. If these drivers are outdated or malfunctioning, you may run into problems.

 Most of the time, you can fix the problem by simply uninstalling and reinstalling the driver on your PC. Here’s how you can go about it.

1. Right-click on the **Start** icon to open the Power User menu.
2. Select **Device Manager** from the list.
3. Expand **Biometric devices**.  
![Biometric Driver selected in Device Manager window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Biometric-Driver-in-Device-Manager-1.jpg)
4. Right-click on your fingerprint scanner device and select **Uninstall device**.
5. Select **Uninstall** to confirm.

 Additionally, you should also expand the **Universal Serial Bus Controllers** section in the Device Manager and look for any entries with a yellow exclamation. If you find any, right-click on them one by one and select **Uninstall device** to remove them.

 Restart your PC after completing the above steps and check if the issue still occurs.

## 3\. Run the Hardware and Devices Troubleshooter

 Windows 10 and 11 include a number of [troubleshooters for resolving various system-related issues](https://www.makeuseof.com/windows-11-troubleshooters/). In this case, you should run the Hardware and Devices troubleshooter. It will scan your computer’s fingerprint scanner for any issues and attempt to fix them.

 Follow these steps to run the Hardware and Devices troubleshooter on Windows:

1. Press **Win + R** to open the Run dialog box.
2. Type **msdt.exe -id DeviceDiagnostic** in the Open field and press **Enter**.
3. In the Hardware and Devices window, click **Next**.  
![Hardware and Devices Troubleshooter Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Hardware-and-Devices-Troubleshooter-Window.jpg)

 Wait for Windows to diagnose any issues with your computer. If any issues are detected, follow the on-screen instructions to apply the recommended fixes.

## 4\. Turn Off Fast Startup

 Fast Startup is a handy Windows feature that speeds up your PC's boot time after shutdown. However, this feature might sometimes prevent Windows from loading properly. When this happens, the fingerprint scanner may not work on your Windows 10 or 11 PC.

 Use one of the many ways to [disable Fast Startup on your Windows computer](https://www.makeuseof.com/windows-11-turn-on-or-off-fast-startup/) and see if that gets the fingerprint scanner to work.

## 5\. Configure Windows Biometric Service to Start Automatically

 The Windows Biometric Service is an essential program for Windows Hello, as it captures and manages your fingerprint data. Ideally, the service should start automatically every time Windows boots. However, this might not happen if the service is not configured correctly.

 Use these steps to configure the Windows Biometric Service:

1. Open the **Services** app using the search menu.
2. Scroll down to locate the **Windows Biometric Service** on the list.
3. Right-click on it and select **Properties**.
4. Click the drop-down menu to change the **Startup type** to **Automatic**.
5. Hit **Apply** followed by **OK**.  
![Windows Biometric Service Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Windows-Biometric-Service-Properties.jpg)

 Restart your PC after this. Following that, you should be able to sign in with your fingerprint.

## 6\. Enable Biometrics via the Local Group Policy Editor

 Another reason why Windows Hello fingerprint sign-in may not work is if the feature is disabled from the Local Group Policy. It's important to note that Group Policy Settings are only available on Professional, Education, and Enterprise editions of Windows. If you are on Windows Home, you don't need to worry about this step.

 To enable fingerprint authentication via the Local Group Policy Editor, use these steps:

1. Press **Win + S** to open the search menu.
2. Type **gpedit.msc** in the search box and press **Enter** to [open the Local Group Policy Editor](https://www.makeuseof.com/tag/open-local-group-policy-editor-windows/).
3. Use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Components > Biometrics**.
4. Check if all the policies within the Biometrics folder are enabled. If not, double-click each policy one by one and set them to **Enabled**.  
![Biometric Policies in Local Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Local-Group-Policy-Editor-Window-1.jpg)

 Restart your PC one more time and check if the issue is still there.

## 7\. Create a New User Account

 An issue with your current user account can also cause certain Windows features to stop working. This usually happens when your user account files get corrupted. If you suspect that to be the case, you can [create and switch to a new user account](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) to fix the issue. Here’s how you can go about it.

1. Press **Win + I** to open the Settings app.
2. Head to **Accounts > Other users**.
3. Click the **Add account** button.
4. In the Microsoft account window, click on **I don't have this person's sign-in information** and follow the on-screen prompts to create a new user account.  
![Microsoft Account Sign In Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Microsoft-Account-Sign-In-Window.jpg)

 Set up Windows Hello fingerprint login for your new user account and see if you can sign in with your fingerprint.

## 8\. Perform a System Restore

 If the fingerprint not working issue only occurred recently, you can use System Restore to revert Windows to a previous state. This will allow you to undo any changes that may have caused the issue. Note that this is only possible if you have previously [enabled System Restore on your PC](https://www.makeuseof.com/windows-11-enable-system-restore/).

 Follow these steps to perform a system restore on Windows:

1. Press **Win + S** to open the search menu.
2. Type **Create a restore point in the search box** and press **Enter**.
3. Under the **System Protection** tab, click on **System Restore**.
4. Click **Next**.
5. Select a restore point before the issue first appeared and hit **Next**.
6. Review all the details one more time before hitting **Finish**.  
![System Restore Dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/System-Restore-Dialog.jpg)

 Windows will restart and revert to the specified restore point. After that, the fingerprint should work as before.

## 9\. Install the Latest Windows Updates

 Microsoft regularly releases software updates for Windows 10 and Windows 11 to add new features, improve performance, and—crucially for our purposes—fix bugs. If the fingerprint not working issue is caused by a system bug, updating Windows to its most recent version should help.

 You can check for new updates by going to the **Windows Update** tab in the **Settings** app. Download and install any pending updates on your PC. Hopefully, this will resolve the issue.

## Fixing Windows Hello's Fingerprint Check

 It’s annoying when your PC's fingerprint scanner stops working all of a sudden. However, that shouldn’t force you to use your password or PIN to sign in to your computer.

 We hope one of the methods mentioned above has helped and you are able to sign in with your fingerprint again. However, if all else fails, you may want to consider resetting your Windows computer.

 Fortunately, there are several ways to fix this annoying issue. So, let’s dive in and explore what you should do when Windows Hello fingerprint login isn’t working.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-11-icon-display-ease/"><u>Enhancing Windows 11 Icon Display Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-spotify-connections-on-windows-11-devices/"><u>Overcoming Spotify Connections on Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-walkthrough-on-windows-11-sound-settings-navigation/"><u>A Quick Walkthrough on Windows 11 Sound Settings Navigation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-system-integration-windows-plus-kali-linux-setup/"><u>Conquering System Integration: Windows + Kali Linux Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/create-a-seamless-workflow-with-alt-tab-in-win1110/"><u>Create a Seamless Workflow with Alt-Tab in Win11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-exception-handling-breaking-point-solution/"><u>Mastering Windows Exception Handling: Breaking Point Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-measures-for-eradicating-white-screens-in-win1011/"><u>Efficient Measures for Eradicating White Screens in WIN10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-windows-snip-and-sketch-with-one-move/"><u>Launching Windows Snip & Sketch With One Move</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-samsung-galaxy-s24plus-phone-without-password-by-drfone-android/"><u>How To Unlock Samsung Galaxy S24+ Phone Without Password?</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-3-ways-for-android-pokemon-go-spoofing-on-samsung-galaxy-a05-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways for Android Pokemon Go Spoofing On Samsung Galaxy A05 | Dr.fone</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-get-the-best-free-3gp-video-rotator-for-your-needs-top-recommendations-for-2024/"><u>Updated Get the Best Free 3GP Video Rotator for Your Needs Top Recommendations for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-advanced-tactics-for-maximizing-the-use-of-virtual-boards-during-zoom-sessions-desktopiosandroid-for-2024/"><u>[New] Advanced Tactics for Maximizing the Use of Virtual Boards During Zoom Sessions (Desktop/iOS/Android) for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-the-top-5-game-changers-for-professional-obs-studio-video/"><u>[New] In 2024, The Top 5 Game-Changers for Professional OBS Studio Video</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirror-on-apple-iphone-13-pro-drfone-by-drfone-ios/"><u>How to Screen Mirror on Apple iPhone 13 Pro? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-find-my-friends-work-on-samsung-galaxy-f54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Does find my friends work on Samsung Galaxy F54 5G | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-innovative-hiring-the-10-most-engaging-vids/"><u>[Updated] Innovative Hiring  The 10 Most Engaging Vids</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-special-features-virtual-location-on-nokia-g22-drfone-by-drfone-virtual-android/"><u>How To Use Special Features - Virtual Location On Nokia G22? | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>