---
title: Prevent Windows From Tracing New Program Starts
date: 2024-11-21T16:09:12.745Z
updated: 2024-11-27T16:30:49.442Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Prevent Windows From Tracing New Program Starts
excerpt: This Article Describes Prevent Windows From Tracing New Program Starts
keywords: Block Program Tracking in Windows,Hide Startup Apps Execution Trace,Disable Windows Logon Events,Stop New Program Alerts on PC,Prevent Windows System Notifications,Secure Program Launch Privacy,Eliminate Program Trigger Messages
thumbnail: https://thmb.techidaily.com/8efb02d1ad78746fe7e04d066e97a30754c0040bd1d393f4b6d528ffbc9df6b1.jpg
---

## Prevent Windows From Tracing New Program Starts

 Windows records and monitors how often you use particular applications. While this may enhance productivity, it does also raise privacy concerns.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Disable App Launch Tracking Through Windows Settings

 To disable app launch tracking, open the Start menu and type **Settings** in the search bar. Select the **Settings** option in the search results. In the left-side menu, click the **Privacy & security** tab. Then click **General** under the Windows permissions section.

 On the next page, locate **Let Windows improve Start and search results by tracking app launches** and toggle it off.

![Disable App Launch Tracking through Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-windows-settings.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gOyLy8DeizY?si=GkAmK0hChZw6_2tW&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After making the changes, Windows will stop tracking and recording your app launches.

 If you ever need to re-enable the feature, repeat the same steps and toggle the switch back on. This will enable Windows to start tracking and recording your app launches.

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/BR4gsW-J7as?si=9a56UDKZKhREZnwz&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Click **Apply** \> **OK** to save your changes.

 This way, you can disable app launch tracking using the group policy editor.

 To enable the feature again, follow the same steps and navigate to _User Configuration > Administrative Templates > Windows Components > Edge UI_. Then double-click on **Turn off tracking of app usage** and check the **Not Configured** or **Disabled** option.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aknYnDfODro?si=zONIVzA9FFq0rLOD&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/W5aJC8okA8s?si=L2rnYAp-gmGlLQSf&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you're done, close the Registry Editor and restart your computer. Now, Windows won't track or record app launches.

 If you ever want to turn back on app launch tracking, double-click on the **Start\_TrackProgs** DWORD in Registry Editor and set its value to **1**. After that, restart your system for the changes to take effect.

## Windows Won’t Track or Monitor the Apps You Use

 If you don't want to mess with the Registry Editor or Group Policy Editor, use the Settings option to disable app launch tracking. Choose the method you prefer and enjoy a tracking-free experience.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-understanding-youtube-shorts-earnings-for-maker-income/"><u>[Updated] 2024 Approved Understanding YouTube Shorts Earnings for Maker Income</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-faulty-function-keys-solutions-for-windows-10/"><u>Fix Faulty Function Keys: Solutions for Windows 10</u></a></li>
<li><a href="https://tech-haven.techidaily.com/harnessing-artificebot-intelligence-the-ultimate-walkthrough-for-bing-app-users-on-android/"><u>Harnessing Artificebot Intelligence: The Ultimate Walkthrough for Bing App Users on Android</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-use-pokemon-go-joystick-on-itel-p55-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Pokemon Go Joystick on Itel P55 5G? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/looking-for-a-location-changer-on-tecno-spark-10c-look-no-further-drfone-by-drfone-virtual-android/"><u>Looking For A Location Changer On Tecno Spark 10C? Look No Further | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-your-web-server-with-iis-opening-techniques/"><u>Mastering Your Web Server with IIS Opening Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-download-speeds-steam-and-windows-collaboration/"><u>Optimizing Download Speeds: Steam & Windows Collaboration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/precision-methods-seamless-union-of-disjoint-windows-partitions/"><u>Precision Methods: Seamless Union of Disjoint Windows Partitions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-sticky-notes-position-in-desktop-windows/"><u>Secure Sticky Notes' Position in Desktop Windows</u></a></li>
<li><a href="https://vp-tips.techidaily.com/setup-smoothly-share-soon-the-ifunny-meme-adventure-begins-for-2024/"><u>Setup Smoothly, Share Soon The iFunny Meme Adventure Begins for 2024</u></a></li>
<li><a href="https://solve-manuals.techidaily.com/solving-the-puzzle-of-error-code-0xc000021a-on-windows-an-in-depth-tutorial/"><u>Solving the Puzzle of Error Code 0xC000021A on Windows: An In-Depth Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-verdict-on-yourphone-to-turn-it-off-or-keep-running/"><u>The Verdict on YourPhone: To Turn It Off or Keep Running?</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/top-tips-and-tricks-for-an-unforgettable-labor-day-bash-a-comprehensive-guide/"><u>Top Tips & Tricks for an Unforgettable Labor Day Bash: A Comprehensive Guide</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-webm-video-compression-made-easy-online-solutions/"><u>Updated 2024 Approved WebM Video Compression Made Easy Online Solutions</u></a></li>
<li><a href="https://program-issues.techidaily.com/why-is-guilty-gear-strive-delayed-exploring-the-reasons-behind-its-postponement/"><u>Why Is 'Guilty Gear Strive' Delayed? Exploring the Reasons Behind Its Postponement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-voice-control-commands-quick-guide/"><u>Win11 Voice Control Commands Quick Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-issues-learn-how-to-seek-expert-guidance/"><u>Windows Issues? Learn How to Seek Expert Guidance!</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    