---
title: "Cutting Down Waiting Time: Editing Boot Sequence Timer Win11"
date: 2024-10-08T02:09:28.246Z
updated: 2024-10-15T10:07:26.470Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Cutting Down Waiting Time: Editing Boot Sequence Timer Win11"
excerpt: "This Article Describes Cutting Down Waiting Time: Editing Boot Sequence Timer Win11"
keywords: Win11 Boot Speed,Edit Boot Timer,Reduce Boot Delay,Win11 Start Quick,Optimize Boot Process,Win11 Timer Adjustment,Fast Boot Windows
thumbnail: https://thmb.techidaily.com/9a9907ac5dbaa04f31e369bac93b279f477635cd1d417e1d02f2db8686c1981a.jpg
---

## Cutting Down Waiting Time: Editing Boot Sequence Timer Win11

 When you turn on your dual-boot system, Windows waits for a while, allowing you to choose the operating system you want to load. However, the default wait time may be too short, giving you little time to decide.

 Fortunately, you can configure the wait time as per your choice. In this article, we'll explore four quick ways to change the boot menu timeout in Windows 11\. So, let's begin.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Change Boot Menu Timeout Using the Settings App

 The quickest way to configure the boot menu timeout is via the Settings app. Here's a step-by-step instructions to do that:

1. Press the **Win + I** hotkey to open the **Settings app**.
2. Choose **System** from the left sidebar and **About** from the right pane.
3. Choose **System protection**.  
![System protection option in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-protection.jpg)
4. Switch to the **Advanced** tab and click the **Settings** button under the **Startup and Recovery** section.
5. Click the drop-down icon under the **Default operating system** option and choose your default OS.
6. Check the **Time to display list of operating systems** option and select the timeout value. The value can range from **0** to **999**.  
![Time to display list of operating systems option in System Protection window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/time-to-display-list-of-operating-systems-option.jpg)
7. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924297/11305" target="_top" id="924297">
  <img src="//a.impactradius-go.com/display-ad/11305-924297" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i110150.net/i/5597632/924297/11305" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Change Boot Menu Timeout Using System Configuration

 The System Configuration app, aka msconfig, is a built-in Windows utility that lets you [control your system's startup programs](https://www.makeuseof.com/optimize-startup-programs-windows-11/) and services. You can also use it to adjust various system settings, including the boot menu timeout. To change the boot menu timeout using the System Configuration app, follow the below instructions:

1. Press the **Win** key to open the **Start Menu,** type **System Configuration** in the search bar, and select the same from the result.
2. Switch to the **Boot** tab.
3. Enter the value (seconds) in the **Timeout** section and check the **Make all boot settings permanent** option.  
![Timeout option in msconfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/timeout-option.jpg)
4. Click **Apply.**
5. Click **Yes** to confirm your changes.  
![Yes option in msconfig window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/yes-option-1.jpg)
6. Choose the **Restart** button.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135408/19272" target="_top" id="2135408">
  <img src="//a.impactradius-go.com/display-ad/19272-2135408" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135408/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Change Boot Menu Timeout Using the Command Prompt

 If you're an advanced Windows user, you can use Command Prompt to configure the boot menu timeout on your Windows PC. Here's how:

1. Open the Start Menu, type **Command Prompt** in the search bar, and choose **Run as administrator** from the right pane. If this method doesn't work, check out other ways to [launch Command Prompt in Windows](https://www.makeuseof.com/windows-11-open-command-prompt/).
2. In the elevated Command Prompt window, type the following command and press Enter. This will display the current time for which the boot menu appears.  
`bcdedit`
3. Type the following command and press Enter to change the timeout. Make sure to replace **`SECONDS`**with the new timeout.  
`bcdedit /timeout SECONDS`  
![Timeout change command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/timout-change-command.jpg)

 That's it! From the next boot, the boot manager will appear for the specified duration of time.

## 4\. Change Boot Menu Timeout Using the Boot Options

 Another efficient way to configure the boot menu timeout is through the Boot Manager. The Boot Manager, also known as the Boot Loader, is responsible for launching your operating system when you turn on your computer. Not only that, it enables you to select a specific operating system if you are using multiple operating systems on your device.

 To modify the boot menu timeout through the Boot Manager, follow these instructions:

1. Open the Start Menu, click the **Power icon** and choose **Restart** from the context menu. If this method doesn't work, try any other [ways to restart your Windows PC](https://www.makeuseof.com/windows-restart-methods/).
2. In the Boot Manager, click on **Change defaults or choose other options**.  
![Change defaults or choose other options in the Boot menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-defaults-or-choose-other-options.jpg)
3. Select the **Change the timer** option.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049379/7443" target="_top" id="2049379">
  <img src="//a.impactradius-go.com/display-ad/7443-2049379" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049379/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Change the timer option in the Boot menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-the-timer.jpg)
4. Choose a time between the given options.  
![Choose time in the Boot Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/choose-time.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130528/26400" target="_top" id="2130528">
  <img src="//a.impactradius-go.com/display-ad/26400-2130528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130528/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Control Your System Boot Menu on Windows

 Optimizing the boot menu timeout in Windows is a simple yet effective way to manage your system's startup time. By adjusting the duration for which the boot menu appears, you can ensure that you have adequate time to select your preferred operating system.

 Fortunately, you can configure the wait time as per your choice. In this article, we'll explore four quick ways to change the boot menu timeout in Windows 11\. So, let's begin.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-duration-decoded-a-guide-to-editing-youtube-videos-for-2024/"><u>[New] Duration Decoded A Guide to Editing YouTube Videos for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-navigate-the-clouds-and-crowd-fb-livestreams-via-dji-for-2024/"><u>[New] Navigate the Clouds and Crowd FB Livestreams via DJI for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-learn-to-record-mi-11s-display-effortlessly/"><u>[Updated] 2024 Approved Learn to Record Mi 11'S Display Effortlessly</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-step-by-step-changing-file-types-for-mac-snapshots-for-2024/"><u>[Updated] Step-by-Step Changing File Types for Mac Snapshots for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/bringing-serenity-to-chaos-mastery-through-gpt-techniques/"><u>Bringing Serenity to Chaos: Mastery Through GPT Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/critical-review-do-windows-11s-gadgets-merit-attention/"><u>Critical Review: Do Windows 11'S Gadgets Merit Attention?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-failed-office-activation-on-windows-apps/"><u>Fixing Failed Office Activation on Windows Apps</u></a></li>
<li><a href="https://program-issues.techidaily.com/1723012801291-halo-3-stability-issues-on-pc-discover-the-fix/"><u>Halo 3 Stability Issues on PC? Discover the Fix!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-locate-and-manage-windows-batch-files/"><u>How to Locate & Manage Windows Batch Files</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-cards-of-vivo-y17s-without-puk-codes-by-drfone-android/"><u>How To Unlock SIM Cards Of Vivo Y17s Without PUK Codes</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-discover-the-best-10-animated-text-software-for-stunning-visuals/"><u>New In 2024, Discover the Best 10 Animated Text Software for Stunning Visuals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-removing-the-persistent-win11-error-code/"><u>Swiftly Removing the Persistent Win11 Error Code</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-addressing-high-dpi-display-problems/"><u>Understanding and Addressing High-DPI Display Problems</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/1726030653858-youtube3/"><u>より大きな音で楽しむ: YouTube動画を最適化する3つの技術</u></a></li>
</ul></div>

