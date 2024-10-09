---
title: How to Recognize and Implement Execution Monikers
date: 2024-10-03T05:30:37.819Z
updated: 2024-10-09T02:29:08.071Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Recognize and Implement Execution Monikers
excerpt: This Article Describes How to Recognize and Implement Execution Monikers
keywords: Execution Strategy Basics,Moniker Identification,Business Process Mastery,Leadership Initiative Gauge,Performance Enhancement Methods,Operational Effectiveness Analysis,Action Plan Integration Guide
thumbnail: https://thmb.techidaily.com/c16b1e731514b90b733ef5726536377276b9f0da4bb0ae7f591c4a5f178d3c77.jpg
---

## How to Recognize and Implement Execution Monikers

 If you're trying to open an app like Microsoft Paint in the Run Dialog and see an error message, it could be caused by your app aliases. But what exactly are App Execution Aliases, where do you find them, and how do you use them?

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Are App Execution Aliases?

 An alias is an alternative name given to something. The most obvious example is the codename given to a spy or undercover agent. On Windows, aliases have nothing to do with spying. Instead, they are used for streamlining tasks, such as entering commands.

 Windows 10 and 11 both allow aliases to be declared for some apps by default. The available apps vary but are often those commonly associated with command line tools. Giving an app an alias allows it to be executed using a shorter title rather than the full name or path.

 App aliases can be used in several[Windows Command Line Interfaces](https://www.makeuseof.com/what-is-cli-what-does-it-stand-for/) (CLI), including the Run Dialog, Command Prompt, and[PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) . If you use these tools with any regularity, app aliases can help to streamline entering commands.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047406/19272" target="_top" id="2047406">
  <img src="//a.impactradius-go.com/display-ad/19272-2047406" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047406/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Enable App Execution Aliases in Settings

 You can enable and disable aliases for compatible apps in the main settings in both Windows 10 and 11\. If more than one app uses the same alias name, you can choose which has the alias applied to it.

In Windows 11:

1. Open**Settings > Apps** , and look for**Advanced app settings** .
2. In the advanced app settings, click**App execution aliases** to see the list of compatible apps.
3. Use the slider switches to enable or disable the alias for each app. You can see the alias name below each app.

![app aliases in windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win11.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144277/7443" target="_top" id="2144277">
  <img src="//a.impactradius-go.com/display-ad/7443-2144277" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144277/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

In Windows 10:

1. If you're using Windows 10, you'll find the aliases in**Settings > Apps & features** .
2. Click the**App execution aliases** link near the top of the Apps & features page.
3. You can then enable and disable aliases using the switches.

![app aliases in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win10.jpg)

 By default, in both Windows 10 and 11, you can only enable or disable existing app aliases. But if you don't mind editing the Registry, you can create new aliases for many other apps.

## Create App Execution Aliases in Registry Editor

 Before editing or creating registry keys, it is advisable to[create a full backup of the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . Of course, you should also ensure you understand how to restore the Registry from that backup.

 The process below for creating app execution aliases in the Registry Editor should be the same in both Windows 10 and 11.

1. Open**Windows Search** , type**Registry Editor** , and click on the search result to open it.
2. In the editor, navigate to **HKEY\_CURRENT\_USER\\Software\\Microsoft\\Windows\\CurrentVersion\\App Paths** .
3. Next, right-click on the**App Paths** key in the left-hand pane, and select**New > Key** .
4. Give the new key an alias name that relates to the app and ends with .exe. For example, if the alias is for Calendar, call it something like cal.exe.
5. With the alias selected, double-click the**Default** value in the right-hand pane.  
![editing app aliases in registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-regedit.jpg)
6. In the Value data field, you will need to enter the full path to the app executable file. For example**C:\\Program Files (x86)\\Calendar.exe** .

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1013424/11832" target="_top" id="1013424">
  <img src="//a.impactradius-go.com/display-ad/11832-1013424" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1013424/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Right-click in the right pane and select**New > String value** . Name the string**path** . The change the Value data to the same path as above, but without the app filename.

 You can now close the Registry Editor. The new App Execution Alias will now be available to use in the Windows CLIs.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087485/7443" target="_top" id="2087485">
  <img src="//a.impactradius-go.com/display-ad/7443-2087485" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087485/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Using and Creating App Execution Aliases

 Entering commands into tools such as Command Prompt and PowerShell can be laborious. You can streamline that process by enabling or creating aliases for apps that commonly feature in those commands. Why type out a full path to an executable file when you can point to it with a few keystrokes?

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
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-gain-popularity-power-secrets-to-staff-picked-videos-on-vimeo/"><u>[New] 2024 Approved Gain Popularity Power Secrets to Staff-Picked Videos on Vimeo</u></a></li>
<li><a href="https://article-files.techidaily.com/new-in-depth-analysis-the-essence-of-the-google-podcast-application-for-2024/"><u>[New] In-Depth Analysis The Essence of the Google Podcast Application for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-turning-horizons-into-heights-uploading-videos-to-igtv/"><u>[Updated] 2024 Approved Turning Horizons Into Heights Uploading Videos to IGTV</u></a></li>
<li><a href="https://extra-resources.techidaily.com/affordable-gopros-where-to-buy-with-best-price-for-2024/"><u>Affordable GoPros Where to Buy with Best Price for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cease-self-initiating-open-of-search-bar-win11-help/"><u>Cease Self-Initiating Open of Search Bar, Win11 Help</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719364670351-create-a-gratis-local-gptclone-with-gpt4all-for-windows/"><u>Create a Gratis, Local GPTClone with GPT4All for Windows.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-distinctions-a-comparative-analysis-of-standard-login-vs-microsoft-account-on-pcs/"><u>Dissecting Distinctions: A Comparative Analysis of Standard Login vs Microsoft Account on PCs</u></a></li>
<li><a href="https://common-error.techidaily.com/diy-solutions-eradicating-the-windows-error-code-entry-point-not-present/"><u>DIY Solutions: Eradicating the Windows Error Code - Entry Point Not Present</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-windows-drive-space-without-spending-a-dime/"><u>Elevate Windows Drive Space Without Spending a Dime</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-security-modifying-the-reset-counter-post-failed-logon-attempts-win-11/"><u>Enhancing Security: Modifying the Reset Counter Post Failed Logon Attempts, Win 11</u></a></li>
<li><a href="https://win-manuals.techidaily.com/free-nextjs-and-tailwind-css-starter-kit-build-your-professional-portfolio-with-ease/"><u>Free Next.js & Tailwind CSS Starter Kit: Build Your Professional Portfolio with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-unreachable-status-for-malwarebytes-services-in-win11/"><u>How to Fix Unreachable Status for Malwarebytes' Services in Win11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-understanding-movie-storage-space-needs-over-24-hours/"><u>In 2024, Understanding Movie Storage Space Needs Over 24 Hours</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-ram-essential-tweaks-for-enhanced-windows-performance/"><u>Maximizing RAM: Essential Tweaks for Enhanced Windows Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-black-screen-phenomenon-in-webcams/"><u>Overcoming Black Screen Phenomenon in Webcams</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-motorola-edge-2023-stuck-on-boot-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Motorola Edge 2023 Stuck on Boot Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-functionality-to-ailing-xbox-controllers/"><u>Restoring Functionality to Ailing Xbox Controllers</u></a></li>
<li><a href="https://win-outstanding.techidaily.com/save-and-play-on-any-device-how-to-download-xboxclips-in-various-video-types-mp4-mov-avi-flv-wmv-mkv/"><u>Save & Play On Any Device: How to Download XboxClips in Various Video Types: MP4, MOV, AVI, FLV, WMV, MKV</u></a></li>
<li><a href="https://some-techniques.techidaily.com/synergistic-abbyy-and-alteryx-software-suite-comprehensive-data-analysis-and-document-automation/"><u>Synergistic ABBYY & Alteryx Software Suite: Comprehensive Data Analysis & Document Automation</u></a></li>
</ul></div>

