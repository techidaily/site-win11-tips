---
title: Beginning Your Quake Experience via Terminal
date: 2025-01-23T20:49:42.958Z
updated: 2025-01-25T00:41:33.650Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Beginning Your Quake Experience via Terminal
excerpt: This Article Describes Beginning Your Quake Experience via Terminal
keywords: Earthquake Basics,Terminal Tips,Disaster Prep Guide,Seismic Start,Emergency Command,Quake Readiness,Terminal Safety
thumbnail: https://thmb.techidaily.com/4f39ebc55802b5fd29e1ead6db3dfc5174731a378a897f2615b5059637faad66.png
---

## Beginning Your Quake Experience via Terminal

 The Windows Terminal is a Microsoft app used for working in command-line tools like PowerShell, Command Prompt, and WSL. It includes several useful features, including Quake Mode. And if you regularly need to enter command lines, Quake Mode is an efficient way to do it.

Here's how to enable and use Quake mode in Windows Terminal.

## What Is Quake Mode, and Why Should You Use It?

 Windows Terminal is a fast and efficient way to make using command-line tools easier. You can download it from the Microsoft Store.

![multiple tabs in the windows terminal app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/window-terminal-app.jpg)

 The key features of Windows Terminal include multiple tabs, panes, and a GPU-accelerated text rendering engine. There are also custom themes, styles, and configurations. And, of course, Quake mode which was added in version 1.9.

 When enabled, Quake mode lets you quickly open a new terminal instance from within any app. The terminal window opens from the top of the screen and fills the full-screen width. You can then hide the terminal window, keeping it ready to be opened whenever you need it.

 The name Quake mode refers to the similar-looking terminal window you could open in the iD Software game, Quake.

 If you don't know what Quake is, why not check out some [classic PC FPS games?](https://www.makeuseof.com/tag/play-classic-shooters-on-modern-computer/) Great fun, even if you have a modern PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlYIdWQc-jw?si=ZQ5809CbQGEar0vg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Open Windows Terminal in Quake Mode

There are two ways to open the Windows Terminal in Quake mode.

 The first is to press**Win + R** to open the**Run dialog** . In the text field, type**wt -w \_quake** . Make sure you include the spaces after the t and before the underscore.

 You can also open the Windows Terminal app in the normal way. You can find it in the main Start Menu apps list if you are new to the app. With the app open in standard mode, press**Win + \`** (the grave accent button below Esc on the keyboard).

![The windows terminal in quake mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-terminal-quake.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/h5uImbOWmTg?si=z4kP-R0QbXbBAJTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want the command-line tool to be run as an administrator, you will need to use the second method. Learn how to open [Windows PowerShell or Command Prompt as an administrator](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .

## Hiding and Restoring the Terminal Window

 The idea of the Quake mode is to give the ability to have a terminal window always available. Even when in a full-screen app or if you can't click a terminal shortcut in the Taskbar.

 Once the Windows Terminal is in Quake mode, you can hide it by pressing**Win + \`** . It remains active but is hidden off-screen.

To reveal the window again, press the same keyboard shortcut.

 The Quake mode terminal window stretches the entire width of the screen. By default, it will fill about half the height of the screen. Unfortunately, you can't change the width, but you can click and drag the bottom edge of the panel to make it less intrusive.

## Closing the Quake Mode Terminal Window

 As mentioned, the**Windows Key + \`** shortcut doesn't close the terminal window; it only hides it. Even closing the original Windows Terminal window won't remove the Quake mode window.

 When the Quake mode terminal window is on-screen, a terminal icon will appear in the Taskbar. You can hover over this icon and click the**X** on the peek preview window.

![The peek window for the Windows Terminal in quake mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/closing-quake-mode-window.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RAnyQ0uj9Yg?si=Es4_ulcdM_-LuDcq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you don't see a peek preview, you can right-click on the terminal icon in the Taskbar and select**Close Window** .

 If the [Windows Taskbar is not working](https://www.makeuseof.com/tag/5-steps-fix-windows-10-taskbar-issues/) for some reason, these options won't be available. Instead, you can close the Quake mode terminal window by typing**EXIT** in the terminal and pressing**Return** .

## Start Windows Terminal in Quake Mode at Logon

 You can set the Terminal to open at logon in the PowerShell settings. But even if you have previously used Quake mode, the terminal will start in a normal window. You can get around this by creating a modified shortcut in shell:startup.

1. Type**Run** into Windows Search and open the Run Dialog.
2. Open the startup items folder by typing**shell:startup** , then click**Ok** .  
![creating a shortcut to quake mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/auto-open-quake-mode.jpg)
3. Right-click anywhere in the folder and select**New > Shortcut** .
4. For the location of the item, type:**wt.exe -w \_quake** . Click**Next** .  
![shortcut to automatically open quake mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/quake-mode-shortcut.jpg)
5. Give the shortcut a name you will recognize, such as**Terminal Quake** . Then click**Finish** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Sj2QNA-JXI?si=V-_h73iE3VlE214k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The next time you log on to Windows, the terminal will open automatically in Quake Mode. You can then use it, or press the**Windows + \`** shortcut to minimize it.

 If you have [disabled app execution aliases](https://www.makeuseof.com/app-execution-aliases-guide/) , you will have to type or browse to the full path for the Windows Terminal. So instead of typing**wt.exe -w \_quake** , enter **C:\\Users\\\[username\]\\AppData\\Local\\Microsoft\\WindowssApps\\wt.exe -w \_quake** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zWYVKFk3yPQ?si=Yu7xsjIYgRiq8zHk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Using the Windows Terminal's Quake Mode

 The Windows Terminal is a great way to work in command-line apps such as PowerShell and Windows Subsystem for Linux. Being able to run it in Quake mode means that you always have access to the terminal you need, no matter what you do on your PC.

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
<li><a href="https://fox-info.techidaily.com/new-srt-conversion-essentials-ttml-xml-ssa-and-beyond-for-2024/"><u>[New] SRT Conversion Essentials TTML, XML, SSA, and Beyond for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/he-pathway-to-popular-youtube-thumbnails-mac-edition/"><u>[New] The Pathway to Popular Youtube Thumbnails Mac Edition</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-transform-ppt-deck-into-video-stream/"><u>[Updated] 2024 Approved Transform PPT Deck Into Video Stream</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-beat-bloggers-base-downloads-for-analysis/"><u>[Updated] In 2024, Beat Bloggers' Base Downloads for Analysis</u></a></li>
<li><a href="https://tech-revival.techidaily.com/7-cybersecurity-trends-and-predictions/"><u>7 Cybersecurity Trends and Predictions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/controlling-the-chaos-reconnect-lost-nexus-on-steam/"><u>Controlling the Chaos: Reconnect Lost Nexus on Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customize-your-digital-space-a-guide-to-alomwares-utilities/"><u>Customize Your Digital Space - A Guide to AlomWare's Utilities</u></a></li>
<li><a href="https://techtrends.techidaily.com/discover-our-favorites-free-apps-for-learning-new-languages-in-202e4/"><u>Discover Our Favorites: Free Apps for Learning New Languages in 202E4</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/exploring-versatility-in-portable-charging-detailed-look-at-omnicharges-omni-20-power-bank-with-qi-technology/"><u>Exploring Versatility in Portable Charging: Detailed Look at Omnicharge's Omni 20 Power Bank With Qi Technology</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-sony-xperia-10-v-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Sony Xperia 10 V to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-portable-apps-into-windows-desktop/"><u>Integrating Portable Apps Into Windows Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-nuances-of-custom-windows-snapping-via-powertoys/"><u>Navigating the Nuances of Custom Windows Snapping via PowerToys</u></a></li>
<li><a href="https://buynow-info.techidaily.com/sony-ps-lx310bt-review-a-small-turntable-with-sleek-design/"><u>Sony PS-LX310BT Review: A Small Turntable With Sleek Design</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ten-techniques-to-restore-vanished-windows-data/"><u>Ten Techniques to Restore Vanished Windows Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-inaccessible-window-writable-solution-reopen-your-notepad-efficiently/"><u>The Inaccessible Window' Writable Solution: Reopen Your Notepad Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-mastering-the-art-of-desk-icon-space-adjustment-on-winos/"><u>Title: Mastering the Art of Desk Icon Space Adjustment on WINOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-windows-11-fixes-keyboard-shortcuts-for-rapid-problem-solving/"><u>Unlock Windows 11 Fixes: Keyboard Shortcuts for Rapid Problem Solving</u></a></li>
<li><a href="https://fox-links.techidaily.com/unveiling-the-mystery-writing-hooks-for-vlogger-scripts-for-2024/"><u>Unveiling the Mystery Writing Hooks for Vlogger Scripts for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-actions-made-fast-with-cut-paste-shortcuts/"><u>Windows Actions Made Fast with Cut-Paste Shortcuts</u></a></li>
</ul></div>

