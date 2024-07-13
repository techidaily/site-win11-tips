---
title: Turn Off High Contrast Setting in Windows
date: 2024-07-12T16:49:43.413Z
updated: 2024-07-13T16:49:43.413Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Turn Off High Contrast Setting in Windows
excerpt: This Article Describes Turn Off High Contrast Setting in Windows
keywords: Disable HighContrast,TurnOffContrastWin,ReduceWindowsContrast,RemoveHighContrastWin,ContrastSettingToggle,OffHighContrastMode,SwitchContrastOffWin
thumbnail: https://thmb.techidaily.com/c6867ae9c4f4e3df3c9379b15f4163ebd35319a50b7aab7a2fe4029be64b0298.jpg
---

## Turn Off High Contrast Setting in Windows

 Microsoft first introduced high-contrast themes with Windows 7\. The idea was to add a theme that helps users with low vision or photosensitivity see screen elements better. But not everyone needs the high contrast mode on Windows 11 or older versions. Maybe you turned it on by accident and are now struggling to turn it off.

 High contrast mode makes the screen elements darker to increase clarity, but the result may not look inviting for every user. As such, we will explore multiple methods to turn off the high contrast mode on Windows 11 or older operating systems.

## What Is High Contrast Mode?

 High Contrast Mode is an accessibility feature that comes free with Windows. It makes certain screen elements darker and more distinguishable so that users with low vision can see everything. High contrast mode isn’t limited to Windows only; you can also find it in Android, iOS, macOS, Linux, and more.

 But there is a dark mode on Windows 11, isn't there? So, why do we need high-contrast themes? It is because dark mode can reduce the strain on the eyes and is helpful for users who don’t have problems with their vision. But dark mode makes everything black except the text and people with low vision may struggle with it.

 High contrast themes offer customizability to tweak different screen elements, like text, links, background, button text, and more. It's a lot more helpful than dark mode, which just adds a dark or black-grayish background with a white color.

## How to Disable High Contrast Mode on Windows

 If High Contrast Mode has been turned on and you'd like to change that, there are multiple ways to get the job done.

### 1\. Using the High Contrast Mode Shortcut keys

 To disable high contrast mode on Windows using keyboard shortcuts, press the**Left Alt + Left Shift + Print Screen** keys at once. You won’t see any pop-up window to confirm the action, but you will hear a “beep” sound before the system reverts to the default theme. You can use this shortcut again if you need to re-enable High Contrast mode.

### 2\. Using the Settings app

 To disable the high contrast mode using the Settings app on Windows 8 and above, do as follows.

1. Press**Win + I** to [launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) on your system.
2. Navigate to the left-hand side menu and click on**Personalization** .
3. Click on the**Themes** option under Personalization. Scroll down and click on the**Contrast Themes** option.
4. Click on the drop-down menu in the Contrast Themes option and select the**None** option.  
![Disable High Contrast Mode Using Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-high-contrast-mode-using-settings-app.jpg)
5. Then, click on the**Apply** option. Windows will change back to the previous theme.

### 3\. Using the Sign-in screen

 You can even disable the high contrast mode on Windows 11 and 10 before you sign in. Here’s how to do it:

1. Power on your Windows PC. Press any key or click the mouse key to go to the sign-in screen.
2. Navigate to the bottom-right area and click on the**Accessibility** icon.
3. The Accessibility menu will pop up. Click on the**Contrast Theme** toggle to disable it.  
![Disable High Contrast Mode Using Sign In Screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-high-contrast-mode-using-sign-in-screen.jpg)
4. Windows will revert to the default theme. Enter your PIN or password and log in.

### 4\. Using the Control Panel

 To disable the high contrast mode in Windows 11 and 10, do as follows:

1. Press the**Win + S** to bring up Windows Search. Type Control Panel and click on the search result
2. The Control Panel will launch. Click on the**Appearance and Personalization** option.
3. Select the Ease of Access option and click on the**Set Up high contrast** option.
4. Now, select the**Choose a high contrast theme** option.  
![Disable High Contrast Mode Using Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-high-contrast-mode-using-control-panel.jpg)
5. Navigate to**Themes > Contrast Themes** .
6. Click on the drop-down menu in the Contrast Themes option and select the**None** option.
7. Then, click on the**Apply** button.

 Windows 7 doesn’t have a Settings app, so the process of disabling high contrast mode using the Control Panel is a bit different:

1. Press the**Win** key and click on the Control Panel option.
2. Navigate to**Appearance and Personalization > Personalization** .
3. Click on the Windows classic theme or any other system theme.
4. Windows 7 will switch from the high contrast theme to a normal theme.

### 5\. Using the Run Dialog Box

 Repeat the following steps to disable high contrast mode using the run command box:

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type “**shell:::{ED834ED6-4B5A-4bfe-8F11-A626DCB6A921}** ” in the text input area and press the Enter key.  
![Disable High Contrast Mode Using Run Box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-high-contrast-mode-using-run-box.jpg)
3. The old personalization settings control panel window will launch.
4. Click on any system theme. It will deactivate the current high-contrast theme and apply the selected theme.

### 6\. Using Another Theme

 You can disable the high-contrast theme by applying another theme to your system. Here’s how to do it:

1. Press**Win + I** to launch the Settings app.
2. Navigate to**Personalization > Themes** .
3. Move to the**Current theme** section and click on any default system theme or a downloaded theme.  
![Disable High Contrast Mode Using A Different Theme](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-high-contrast-mode-using-a-different-theme.jpg)
4. Windows will apply the selected theme.

 If you want to re-enable the high-contrast theme, you have to visit the "high contrast theme" section here and choose a compatible theme.

### 7\. Using a Script

 It is also possible to revert to a system theme using a script file on Windows. It will take less time as opposed to navigating the settings app to disable the high contrast mode. Here’s how to do it:

1. Go to the desktop. Right-click on the desktop and click on**New > Text Document** .
2. Open the newly created text file and paste the following script into it.  
@echo off C:\Windows\resources\Themes\aero.themetaskkill /F /IM systemsettings.exe
3. Now, press**Ctrl + S** to save the file. Type the name “**disablehc.bat** ” and click on the**save** button.  
![Disable High Contrast Mode Using a script](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-high-contrast-mode-using-a-script.jpg)
4. Go to the desktop again and right-click on the newly created .bat file.
5. Select the**Run as administrator** option in the context menu.
6. UAC will pop up. Click on the**Yes** button to grant administrator privileges to the .bat file. Otherwise, it won’t be able to make changes to the system theme.
7. The command prompt will pop up for a few seconds, run the script, and then close automatically. Your Windows system will disable the high contrast mode and switch to the aero theme.

## The Windows High Contrast Theme Won’t Bother You Anymore

 These were the seven methods using which you can disable the high contrast theme on Windows. The quickest way is to use the hotkeys for contrast themes or use a BAT script. If you want to save your eyes from the harsh white light but cannot stand high-contrast themes, use a dark theme on Windows 11.

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
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-realme-gt-neo-5-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use GPS Joystick to Fake GPS Location On Realme GT Neo 5 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionize-your-windows-11-the-most-impactful-settings-to-modify/"><u>Revolutionize Your Windows 11: The Most Impactful Settings to Modify</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-websites-windows-programs-a-tutorial/"><u>Making Websites Windows Programs: A Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-complications-caused-by-latest-windows-updates/"><u>Resolving Complications Caused by Latest Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-prevent-expiring-notifications-on-win11/"><u>Strategies to Prevent Expiring Notifications on Win11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-pinnacle-visuals-for-the-modern-broadcaster/"><u>[New] Pinnacle Visuals for the Modern Broadcaster</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-windows-apps-into-linux-world/"><u>Integrating Windows Apps Into Linux World</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-freeframe-studio-gameplay-capture-made-simple-in-24/"><u>[New] In 2024, FreeFrame Studio  Gameplay Capture Made Simple in '24</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-slacks-missing-notifications-issue-in-win-11/"><u>Solving Slack's Missing Notifications Issue in Win 11</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-3-things-you-must-know-about-fake-snapchat-location-on-apple-iphone-14-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, 3 Things You Must Know about Fake Snapchat Location On Apple iPhone 14 Plus | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-establishing-windows-11-support-features/"><u>Re-Establishing Windows 11 Support Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-windows-hello-recognition-work-again/"><u>Making Windows Hello Recognition Work Again</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hidden-potential-utilize-hotkeys-to-control-windows-taskbar/"><u>Hidden Potential: Utilize Hotkeys to Control Windows Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-11-pin-access-issues/"><u>Resolving Windows 11 PIN Access Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-your-workflow-with-aero-shake-w11-tech/"><u>Optimizing Your Workflow with Aero Shake W11 Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimizing-browser-resource-usage-winmacchromeos-comparison/"><u>Minimizing Browser Resource Usage: Win/Mac/ChromeOS Comparison</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proactive-power-indicators-ensure-a-full-charge-with-windows-11-alerts/"><u>Proactive Power Indicators: Ensure a Full Charge with Windows 11 Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-virtualboxs-usb-failure-message-a-step-by-step-guide-for-windows-users/"><u>Resolving VirtualBox's USB Failure Message: A Step-by-Step Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-onedrives-cant-add-your-folder-right-now-error-on-windows/"><u>How to Fix OneDrive's Can’t Add Your Folder Right Now Error on Windows</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-capturepros-a-studio-showdown/"><u>[New] 2024 Approved  CapturePros  A Studio Showdown</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-spinning-jujutsu-kaisen-stories-on-tiktok-for-2024/"><u>[New] Spinning Jujutsu Kaisen Stories on TikTok for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-easing-through-administrative-denial-of-installers/"><u>Strategies for Easing Through Administrative Denial of Installers</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-capture-your-macs-screen-a-step-by-step-walkthrough/"><u>[New] Capture Your Mac's Screen  A Step-by-Step Walkthrough</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-audible-acuity-ending-echo-of-empty-spaces/"><u>Regain Audible Acuity: Ending Echo of Empty Spaces</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-master-windows-blue-screen-troubleshooting/"><u>How to Master Windows Blue Screen Troubleshooting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-to-streamline-your-windows-netconnection-access/"><u>Step-By Step to Streamline Your Windows NetConnection Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-old-password-needed-on-windows-11-errors/"><u>Remedy for 'Old Password Needed' On Windows 11 Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-your-networks-security-keys-five-steps-towards-error-elimination-in-windows/"><u>Mastering Your Network's Security Keys: Five Steps Towards Error Elimination in Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-3-ways-for-android-pokemon-go-spoofing-on-xiaomi-redmi-k70-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways for Android Pokemon Go Spoofing On Xiaomi Redmi K70 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-items-into-windows-11-taskbar/"><u>Integrating Items Into Windows 11 Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-experience-implementing-appxappxbundle-files-from-store/"><u>Seamless Experience: Implementing Appx/Appxbundle Files From Store</u></a></li>
<li><a href="https://youtube-data.techidaily.com/movie-for-beginners-building-intriguing-openers-for-youtube-for-2024/"><u>[New] IMovie for Beginners  Building Intriguing Openers for YouTube for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefine-access-restoring-standard-user-privileges-in-win11/"><u>Redefine Access: Restoring Standard User Privileges in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-windows-program-functionality-with-ease/"><u>Restoring Windows Program Functionality with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modern-standby-uncovering-its-defects-and-criticisms/"><u>Modern Standby: Uncovering Its Defects and Criticisms</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-quality-of-movement-choosing-between-mirrorless-and-dslr/"><u>[Updated] In 2024, Quality of Movement  Choosing Between Mirrorless & DSLR</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-outlooks-error-0x80040610-in-windows-systems/"><u>Overcoming Outlook's Error 0X80040610 in Windows Systems</u></a></li>
</ul></div>
