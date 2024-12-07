---
title: How to Reset the Mouse and Keyboard Settings to Their Defaults on Windows
date: 2024-12-01T23:58:11.670Z
updated: 2024-12-06T16:22:24.291Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Reset the Mouse and Keyboard Settings to Their Defaults on Windows
excerpt: This Article Describes How to Reset the Mouse and Keyboard Settings to Their Defaults on Windows
keywords: Reset Win Terminal,Default Win Terminal,Reset Terminal Settings,Win Terminal Basics,Windows 11 Terminal,Terminal Settings Defaults,Restore Terminal Options
thumbnail: https://thmb.techidaily.com/b35a9a46671dd373ee6fb76f2e7c8c289a52fdab2f2b7f6dd74a2f0921700773.jpg
---

## How to Reset the Mouse and Keyboard Settings to Their Defaults on Windows

 After configuring some system settings unknowingly, you might realize that the mouse or keyboard doesn’t perform as expected. In such instances, it's hard to know which settings you should tweak to resolve the issue.

 An easy way out would be to reset the mouse or keyboard settings to their default. So, let’s dive in and check out how you can reset these settings.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Reset the Mouse Settings to Their Defaults

![Person using a computer mouse](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/person-using-a-computer-mouse.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jjGL9wFdlbo?si=Vb1JgZqRXNc03UGG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Let’s start by checking out how you can reset the mouse settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3AGmFrtBLHw?si=VhvpUaXHPBHl6OT6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Using the Run Command Dialog Box

 The Run command dialog box is an incredible tool that can help you access most of the apps on your PC. In this case, we’ll use it to quickly access the "Mouse Properties" screen. From there, you can go ahead and reset the mouse settings.

 Here are the steps you need to follow:

1. Press **Win + R** to open the Run command dialog box.
2. Type **control mouse** and press **Enter** to open the Mouse Properties window.
3. Navigate to the **Pointers** tab.
4. Press the **Use Default** button in the bottom-right corner of the screen.
5. Click **Apply** and then click **OK**.

![Pressing the Use Default button on the Mouse Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/pressing-the-use-default-button-on-the-mouse-properties-window.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nyp7-xVwqHA?si=XCuZbpKLFIdrGQQh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Using the Control Panel

 You can always use the Control Panel to [troubleshoot PC issues](https://www.makeuseof.com/how-to-troubleshoot-faulty-windows-pc/) or tweak some system settings. Now, here’s how this tool can help you reset the mouse settings:

1. Type **Control Panel** in the Start menu search bar and select the **Best match**.
2. Click the **View by** drop-down menu and select **Small icons**.
3. Scroll down and select **mouse** from the list.

![Selecting mouse from the Control Panel menu items](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/selecting-mouse-from-the-control-panel-menu-items.jpg)

 Next, navigate to the **Pointers** tab and then press the **Use Default** button. Finally, press **Apply** and then press **OK**.

### Using the System Settings

 The Windows system settings can also help you reset the mouse settings. Here are the steps you need to follow:

1. Press **Win + I** key to access the system settings.
2. Select **Devices** from the options.
3. Click **Mouse** on the left side and then select **Additional mouse options** on the right.

![Selecting Additional mouse options on the Mouse settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/selecting-additional-mouse-options-on-the-mouse-settings-window.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=M69YSY0Mk_gsdU0Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Navigate to the **Pointers** section and then press the **Use default** button. Press **Apply**, press **OK**, and then close the system settings.

### Use the Registry Editor

 You can also reset the mouse settings to their default by editing the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/). However, you’ll need to tweak a couple of Registry values manually.

 Bear in mind that the Registry Editor is quite a sensitive tool. This means you might end up causing issues to your device if you tweak the wrong Registry keys. So, be sure to [back up your Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first before you proceed.

 Here’s how to reset the mouse settings using the Registry Editor:

1. Type **Registry Editor** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as administrator**.
3. Type the following command in the address bar and press **Enter**.

Computer\HKEY_CURRENT_USER\Control Panel\Mouse

 Double-click on the **DoubleClickSpeed** option on the right-hand side.

![Selecting the DoubleClickSpeed option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/selecting-the-doubleclickspeed-option.jpg)

 The default value for the "DoubleClickSpeed" option should be 200\. So, set the **Value data** for this option to **200** and then press **OK**.

 From there, apply the same steps and set the Value data for the other Registry values as follows:

* ActiveWindowsTracking: **0**
* Beep: **No**
* DoubleClickHeight: **4**
* ExtendedSounds: **No**
* MouseHoverHeight: **4**
* MouseHoverTime: **100**
* MouseHoverWidth: **4**
* MouseSensitivity: **20**
* MouseSpeed: **1**
* MouseThreshold1: **6**
* MouseThreshold2: **10**
* MouseTrails: **0**
* SnapToDefaultButton: **0**
* SwapMouseButtons: **0**

 Finally, close the Registry Editor and then restart your device to save these changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DCARjc5g5VI?si=9OfovbKBrpoJeXTY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Reset the Keyboard Settings to Their Defaults

![A lady using a Windows PC while holding a cup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/A-lady-using-a-Windows-PC-while-holding-a-cup.jpg)

 Now, we’ll take look at how to reset the keyboard settings.

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
<li><a href="https://youtube-zero.techidaily.com/-youtuber-quizzes-to-know-what-type-of-youtuber-you-are/"><u>[New] 6 YouTuber Quizzes to Know What Type of YouTuber You Are</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-full-spectrum-analysis-unpacking-xstudio-video-workshop-essentials/"><u>[New] Full Spectrum Analysis Unpacking XStudio Video Workshop Essentials</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-mastering-live-streamed-gaming-sessions-for-2024/"><u>[New] Mastering Live-Streamed Gaming Sessions for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-unlocking-seo-potential-top-strategies-to-dominate-online-search-results-as-a-novice-for-2024/"><u>[New] Unlocking SEO Potential Top Strategies to Dominate Online Search Results as a Novice for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-proper-placement-of-external-webpages-in-insta-content/"><u>[Updated] In 2024, Proper Placement of External Webpages in Insta Content</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-top-25-mobile-editors-for-dji-filmmaking/"><u>[Updated] The Top 25 Mobile Editors for DJi Filmmaking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-constant-calculator-visibility-on-pcs/"><u>Ensuring Constant Calculator Visibility on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-make-admin-access-more-discreet-in-windows-11/"><u>How to Make Admin Access More Discreet in Windows 11</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/quick-fixes-and-expert-advice-dealing-with-the-elusive-winhttpdll-problem/"><u>Quick Fixes and Expert Advice: Dealing With the Elusive Winhttp.dll Problem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-greyed-out-bin-status-on-win11-pc/"><u>Rectifying Greyed Out Bin Status on Win11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reigniting-dormant-media-playback-in-windows-11/"><u>Reigniting Dormant Media Playback in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-output-leverage-flow-launcher-in-your-workday/"><u>Skyrocket Output: Leverage Flow Launcher in Your Workday</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-encyclopedia-of-hand-centered-interaction-systems-for-2024/"><u>The Encyclopedia of Hand-Centered Interaction Systems for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-and-fixes-for-ksuserdll-not-found-issues-in-windows/"><u>Troubleshooting and Fixes for 'ksuser.dll Not Found' Issues in Windows</u></a></li>
<li><a href="https://some-approaches.techidaily.com/ultimate-collection-top-soccer-matches-and-spectacular-goals-of-the-2ebyu/"><u>Ultimate Collection: Top Soccer Matches and Spectacular Goals of the 2Ebyu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-robloxs-error-403-obstacle-on-windows/"><u>Unlocking Roblox's Error 403 Obstacle on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveil-the-hidden-reactivating-grayed-out-memory-in-win11/"><u>Unveil the Hidden: Reactivating Grayed-Out Memory in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-screensaver-unchangeability-best-practices/"><u>Windows Screensaver Unchangeability: Best Practices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/xbox-game-install-woes-quick-fix-guide/"><u>Xbox Game Install Woes: Quick Fix Guide</u></a></li>
</ul></div>

