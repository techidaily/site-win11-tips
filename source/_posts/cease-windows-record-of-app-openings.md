---
title: Cease Windows Record of App Openings
date: 2025-01-21T16:29:55.965Z
updated: 2025-01-25T00:15:12.148Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Cease Windows Record of App Openings
excerpt: This Article Describes Cease Windows Record of App Openings
keywords: Stop Windows App Opens Tracking,Cease Windows Access Logs,Disable Windows Application Records,End Windows App Usage Monitoring,Halt Windows Opening Event Recording,Block Windows App Start Tracking,Eliminate Windows Recorded App Activity
thumbnail: https://thmb.techidaily.com/0fc1e99290cf59c3605c4bd53329b181e70c2492cf43dd61e625fadd84b42143.jpg
---

## Cease Windows Record of App Openings

 Windows records and monitors how often you use particular applications. While this may enhance productivity, it does also raise privacy concerns.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

## 1\. How to Disable App Launch Tracking Through Windows Settings

 To disable app launch tracking, open the Start menu and type **Settings** in the search bar. Select the **Settings** option in the search results. In the left-side menu, click the **Privacy & security** tab. Then click **General** under the Windows permissions section.

 On the next page, locate **Let Windows improve Start and search results by tracking app launches** and toggle it off.

![Disable App Launch Tracking through Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-windows-settings.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6xGqSETroqA?si=4C1GPgXi-AksR_oO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After making the changes, Windows will stop tracking and recording your app launches.

 If you ever need to re-enable the feature, repeat the same steps and toggle the switch back on. This will enable Windows to start tracking and recording your app launches.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fZTlPdOFNmo?si=Ym8p7ayV1gtNzzXj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Disable App Launch Tracking Using the Group Policy Editor

 You can also disable app launch tracking using the Group Policy Editor. But this method is only available in the Pro and Enterprise versions.

 If you don't have these Windows versions, [turn on the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) and follow these instructions.

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **gpedit.msc** in the text box and click **OK**.
3. In the Group Policy Editor window, navigate to the following path:  
`User Configuration > Administrative Templates > Windows Components > Edge UI​`
4. Go to the right side of the window and double-click on **Turn off tracking of app usage**.  
![Disable App Launch Tracking using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-using-group-policy-editor.jpg)
5. On the next page, check the **Enabled** box.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zAzTErKy6h8?si=vi5z3M9_7fW6qiAJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Click **Apply** \> **OK** to save your changes.

 This way, you can disable app launch tracking using the group policy editor.

 To enable the feature again, follow the same steps and navigate to _User Configuration > Administrative Templates > Windows Components > Edge UI_. Then double-click on **Turn off tracking of app usage** and check the **Not Configured** or **Disabled** option.

## 3\. How to Disable App Launch Tracking Through the Registry Editor

 Registry Editor is another method to disable app launch tracking. The process is tricky as you need to manually modify the registry keys and one wrong move can cause serious problems. So, we suggest you [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 To disable app launch tracking through Registry Editor, do the following:

1. Right-click on Start and select **Run** from the menu list.
2. Type **regedit** in the text field and click **OK**. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. When the UAC window appears, click **Yes** to grant privileges.
4. In the left pane, navigate to the following path:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. If you don't find the Advanced folder, right-click on **Explorer** and select **New** \> **Key**.
6. Name it **Advanced** and press the Enter key.
7. Now, right-click on the **Advanced** folder and choose **New** \> **DWORD (32-bit) Value**.
8. Name it **Start\_TrackProgs** and hit Enter.  
![Disable App Launch Tracking through the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-the-registry-editor.jpg)
9. Double-click on the **Start\_TrackProgs** DWORD and set its value to **0**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iPCr_bxZjMQ?si=ubOsoq5umPEXL9xL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you're done, close the Registry Editor and restart your computer. Now, Windows won't track or record app launches.

 If you ever want to turn back on app launch tracking, double-click on the **Start\_TrackProgs** DWORD in Registry Editor and set its value to **1**. After that, restart your system for the changes to take effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6X24fPKs6AE?si=YtQy-8zy7GifgfA7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Windows Won’t Track or Monitor the Apps You Use

 If you don't want to mess with the Registry Editor or Group Policy Editor, use the Settings option to disable app launch tracking. Choose the method you prefer and enjoy a tracking-free experience.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-how-to-screen-hulu-on-any-system-seamlessly/"><u>[Updated] 2024 Approved How to Screen Hulu On Any System Seamlessly</u></a></li>
<li><a href="https://win-dash.techidaily.com/canon-mp250-driver-installation-instructions-how-to-keep-your-printer-updated/"><u>Canon MP250 Driver Installation Instructions – How to Keep Your Printer Updated</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elite-weather-solutions-for-windows-enthusiasts/"><u>Elite Weather Solutions for Windows Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enable-visible-file-images-again-in-your-windows-11-setup/"><u>Enable Visible File Images Again in Your Windows 11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-lan-gaming-disruptions-a-windows-mc-guide/"><u>Fixing LAN Gaming Disruptions: A Windows MC Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-your-license-expires-message-in-windows/"><u>Fixing the Your License Expires Message in Windows</u></a></li>
<li><a href="https://win-amazing.techidaily.com/free-access-to-the-m-audio-fast-track-ultra-driver-enhance-your-setup-today/"><u>Free Access to the M-Audio Fast Track Ultra Driver - Enhance Your Setup Today!</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-fix-oem-unlock-missing-on-samsung-galaxy-s24-ultra-by-drfone-android/"><u>How To Fix OEM Unlock Missing on Samsung Galaxy S24 Ultra?</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-the-digital-artisans-guide-mastering-screen-recordings-in-macos/"><u>In 2024, The Digital Artisan's Guide Mastering Screen Recordings in macOS</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-unlocking-the-potential-of-your-laptops-recording-features/"><u>In 2024, Unlocking the Potential of Your Laptop's Recording Features</u></a></li>
<li><a href="https://fake-location.techidaily.com/looking-for-a-location-changer-on-xiaomi-redmi-13c-5g-look-no-further-drfone-by-drfone-virtual-android/"><u>Looking For A Location Changer On Xiaomi Redmi 13C 5G? Look No Further | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-function-for-non-functional-win11-codes/"><u>Regaining Function for Non-Functional Win11 Codes</u></a></li>
<li><a href="https://hardware-help.techidaily.com/rndis-driver-troubleshooting-for-windows-download-and-upgrade-solutions/"><u>RNDIS Driver Troubleshooting for Windows: Download & Upgrade Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-dismantle-geforce-now-error-code-xc0f1103f/"><u>Strategies to Dismantle GeForce Now Error Code: Xc0f1103f</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/1723064964936-survive-the-night-with-friends-in-dying-light-a-thrilling-first-person-parkour-and-cooperative-gameplay-experience/"><u>Survive the Night with Friends in 'Dying Light': A Thrilling First-Person Parkour and Cooperative Gameplay Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-blueprint-to-decipher-windowsstore-access-code/"><u>The Blueprint to Decipher WindowsStore Access Code</u></a></li>
</ul></div>

