---
title: "Windows 11: Bestowed Powers via Command Line"
date: 2024-12-20T01:04:51.111Z
updated: 2024-12-22T06:01:02.354Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11: Bestowed Powers via Command Line"
excerpt: "This Article Describes Windows 11: Bestowed Powers via Command Line"
keywords: Windows 11 CLI,PowerCmdWin11,Win11CommandOpt,Windows 11 CmdLimits,Win11PowerOptions,CMDWin11Enhancements,CLIWindowsUpgrade
thumbnail: https://thmb.techidaily.com/5a612b69f151ee0b6ea165a5e0a8368a6294f13aca50623658d8bbb7241b81d0.jpg
---

## Windows 11: Bestowed Powers via Command Line

 God Mode enables you to access hundreds of Control Panel applets from a single All Tasks window. That’s a handy thing to activate in Windows 11 for accessing Control Panel settings and creating shortcuts that open them.

 Many users activate God Mode by setting up desktop shortcuts that open the All Tasks window. However, you can instead add a **God Mode** option to the desktop’s context menu in Windows 11\. Then the All Tasks window will be directly accessible on your right-click menu. This is how you can add God Mode to Windows 11’s context menu.

## How to Add God Mode to the Context Menu by Manually Editing the Registry

 You can add God Mode to Windows 11’s desktop context menu by manually tweaking the registry. The tweaking required is relatively simple to apply and involves adding a couple of new registry entries to the Shell key. Follow these steps to manually add God Mode to Windows 11’s context menu:

1. Open the Registry Editor (see [how to open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) for instructions).
2. Click in the address bar at the top of Registry Editor to delete the current key location.
3. Input this Shell key path in the address bar and hit **Enter**:  
`Computer\HKEY_CLASSES_ROOT\DesktopBackground\Shell\`
4. Right-click on **Shell** in Registry Editor’s navigation sidebar to select **New** and **Key**.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/new-key-options.jpg)
5. Type **God Mode** in the key’s text box.

1. Right-click **God Mode** and select the **New** \> **Key** context menu options again.
2. Input **command** within the subkey’s text box.  
![The God Mode registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/god-mode-key.jpg)
3. Double-click on the **(Default)** string for the new command key you’ve added to the registry.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K4lRBnNnd9k?si=5e0MbdOz-fF6Ry_k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Input **explorer** **shell:::{ED7BA470-8E54-465E-825C-99712043E01C}** within the **Data value** box and click **OK**.  
![The Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-string-window.jpg)
5. Click on the Registry Editor’s **X** button.

 Check out the new **God Mode** option on your context menu for opening Task View. Right-click somewhere on the desktop background image and select **Show more options**. Then select **God Mod** to bring up the **Task View** window. You can open a multitude of Control Panel applets from there.

![A God Mode context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/god-mode-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S3Th6oa_isA?si=TTQ013BB9beUM4x6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you ever change your mind about having a **God Mode** context menu option, open the Shell key in Registry Editor again. Then right-click on the **God Mode** key you added and select delete. Click **Yes** to erase the **God Mode** key along with its **command** subkey.

![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-delete-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RvR5PNhspKE?si=uJcMYK9v-_Xq7fAg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Add God Mode to the Context Menu With Right-Click Extender

 The manual registry tweak method is straightforward, but you can add God Mode to the context menu with third-party software instead if preferred. Right-Click Extender is customization software that includes an option for adding God Mode to the context menu. This is how you can add God Mode to your context menu with Right-Click Extender:

1. Open this [Right-Click Extender](https://www.softpedia.com/get/Tweak/System-Tweak/Right-Click-Extender.shtml) download page.
2. Click on the **Download** and **Secure Download (US)** options and download the file.
3. Extract the Right-Click Extender archive by following the instructions within this guide to [unzipping ZIP files in Windows](https://www.makeuseof.com/unzip-files-windows-10/).  
![The Extract Compressed (Zipped) Folders window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/extract-compressed-zip-folder.jpg)
4. Open the extracted Right-Click Extender directory and its Right-Click Extender v2 subfolder.
5. Double-click the Right-Click Extender v2 application file.
6. Click on the **Desktop** tab in Right-Click Extender.
7. Select the **All Tasks (GodMode)** setting and its Icon checkbox.  
![The Right-Click Extender v2 window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-all-tasks-setting.jpg)
8. Press the green **Apply** button.

 Now you’ll see a new **God Mode** option on Windows 11’s classic context menu. This option will also have an icon by it. Click on **God Mode** to view the list of Control Panel applets.

## How to Create Control Panel Shortcuts From God Mode's All Tasks Window

 The Task View window the God Mode context menu option opens makes hundreds of Control Panel applets more accessible. You can open whatever Control Panel settings you need from that window. However, the list of applets shown in that window is quite long.

 Task View makes it easy to create desktop shortcuts for opening the Control Panel applets you need to access more regularly. To do so, left-click an applet or utility in the Task View window, drag it onto the desktop, and release the mouse button. Then you can click on the desktop shortcut to open its Control Panel applet whenever needed.

![The All Tasks (God Mode) window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-all-tasks-window.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E3yY7lZ-FKA?si=g8VEuExP8GH59B69" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Make the Most of God Mode on Windows

 Adding God Mode to your desktop’s context menu will enable you to access a plethora of Control Panel applets and tools within a single window in a couple of clicks. That will save you from rummaging through the Control Panel to find certain applets and settings when needed. Plus, you can make more essential Control Panel applets even more accessible by creating shortcuts for them from the Task View window.

 Many users activate God Mode by setting up desktop shortcuts that open the All Tasks window. However, you can instead add a **God Mode** option to the desktop’s context menu in Windows 11\. Then the All Tasks window will be directly accessible on your right-click menu. This is how you can add God Mode to Windows 11’s context menu.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-blog.techidaily.com/ed-tap-into-tagging-techniques-for-6kplus-youtube-vistas-for-2024/"><u>[Updated] Tap Into #Tagging Techniques for $6K+ YouTube Vistas for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-mastering-reddit-a-step-by-step-guide-for-effective-posts/"><u>2024 Approved Mastering Reddit A Step-By-Step Guide for Effective Posts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-dual-windows-metrics-a-comparative-study/"><u>Deciphering Dual Windows Metrics: A Comparative Study</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-no-data-transfer-problems-on-windows-usb-sticks/"><u>Fixing No-Data Transfer Problems on Windows USB Sticks</u></a></li>
<li><a href="https://tech-revival.techidaily.com/future-foresight-outsmarting-a-machine-oracle/"><u>Future Foresight: Outsmarting a Machine Oracle</u></a></li>
<li><a href="https://tech-hub.techidaily.com/guide-to-shield-your-artwork-from-generative-ai-using-nightshade-methods/"><u>Guide to Shield Your Artwork From Generative AI Using Nightshade Methods</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-lock-apps-on-tecno-camon-30-pro-5g-to-protect-your-individual-information-by-drfone-android/"><u>In 2024, How to Lock Apps on Tecno Camon 30 Pro 5G to Protect Your Individual Information</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-what-is-geo-blocking-and-how-to-bypass-it-on-nubia-red-magic-8s-pro-drfone-by-drfone-virtual-android/"><u>In 2024, What is Geo-Blocking and How to Bypass it On Nubia Red Magic 8S Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-content-transfer-via-application-guard-in-edge-win-11/"><u>Mastering Content Transfer via Application Guard in Edge (Win 11)</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/mastering-video-size-adjustments-on-igtv-for-2024/"><u>Mastering Video Size Adjustments on IGTV for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/outsmarting-ongoing-login-prompts-on-microsoft-teams/"><u>Outsmarting Ongoing Login Prompts on Microsoft Teams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proactive-pc-management-leveraging-command-prompt-for-effective-identification-and-resolution-of-error-codes/"><u>Proactive PC Management: Leveraging Command Prompt for Effective Identification & Resolution of Error Codes</u></a></li>
<li><a href="https://solve-outstanding.techidaily.com/rapid-conversion-guide-turning-x265-into-mp4-quickly-and-efficiently/"><u>Rapid Conversion Guide: Turning X265 Into MP4 Quickly and Efficiently</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/remove-unwanted-elements-top-video-blur-apps-for-mobile-for-2024/"><u>Remove Unwanted Elements Top Video Blur Apps for Mobile for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-disk-management-techniques-for-windows-1011/"><u>Simplifying Disk Management: Techniques for Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-no-drivers-available-when-installing-windows/"><u>Solutions for 'No Drivers Available' When Installing Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-windows-11-control-panel-is-missing-key-settings-heres-where-to-find-them/"><u>The Windows 11 Control Panel Is Missing Key Settings, Here's Where to Find Them</u></a></li>
<li><a href="https://blog-min.techidaily.com/top-15-videstableringsprogrammer-i-2024-denne-gratis-og-kosten-parat/"><u>Top 15 Videstableringsprogrammer I 2024: Denne Gratis Og Kosten Parat</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-in-multitasking-the-advantage-of-16gb-ram/"><u>Winning in Multitasking: The Advantage of 16GB RAM</u></a></li>
</ul></div>

