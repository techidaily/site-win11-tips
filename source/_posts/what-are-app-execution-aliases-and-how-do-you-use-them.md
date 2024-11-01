---
title: What Are App Execution Aliases, and How Do You Use Them?
date: 2024-10-31T16:25:56.063Z
updated: 2024-11-01T19:34:20.263Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes What Are App Execution Aliases, and How Do You Use Them?
excerpt: This Article Describes What Are App Execution Aliases, and How Do You Use Them?
keywords: App Exec ALIAS,SEO Exec ALIAS,Execute Alias Usage,Alias for App SEO,App Performance Optimization,Enhancing App Visibility,Boosting App Engagement
thumbnail: https://thmb.techidaily.com/1ed4f091728645649c840ae907d2be87aba494a53f4cf1942b1dcf1c240fc190.jpg
---

## What Are App Execution Aliases, and How Do You Use Them?

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
<a href="https://appsumo.8odi.net/c/5597632/2151866/7443" target="_top" id="2151866">
  <img src="//a.impactradius-go.com/display-ad/7443-2151866" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151866/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Enable App Execution Aliases in Settings

 You can enable and disable aliases for compatible apps in the main settings in both Windows 10 and 11\. If more than one app uses the same alias name, you can choose which has the alias applied to it.

In Windows 11:

1. Open**Settings > Apps** , and look for**Advanced app settings** .
2. In the advanced app settings, click**App execution aliases** to see the list of compatible apps.
3. Use the slider switches to enable or disable the alias for each app. You can see the alias name below each app.

![app aliases in windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win11.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997717/19272" target="_top" id="1997717">
  <img src="//a.impactradius-go.com/display-ad/19272-1997717" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997717/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

In Windows 10:

1. If you're using Windows 10, you'll find the aliases in**Settings > Apps & features** .
2. Click the**App execution aliases** link near the top of the Apps & features page.
3. You can then enable and disable aliases using the switches.

![app aliases in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win10.jpg)

<!-- affiliate ads begin -->
<span id="1977028">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977028.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977028">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977028.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977028%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977028/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

7. Right-click in the right pane and select**New > String value** . Name the string**path** . The change the Value data to the same path as above, but without the app filename.

 You can now close the Registry Editor. The new App Execution Alias will now be available to use in the Windows CLIs.

<!-- affiliate ads begin -->
<a href="https://smilemakers.pxf.io/c/5597632/2123899/26106" target="_top" id="2123899">
  <img src="//a.impactradius-go.com/display-ad/26106-2123899" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://smilemakers.pxf.io/i/5597632/2123899/26106" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-capture-your-gaming-moments-xbox-one-screenshots-made-simple/"><u>[New] 2024 Approved Capture Your Gaming Moments Xbox One Screenshots Made Simple</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-data-size-and-time-coefficient-in-video-files-20mb-for-2024/"><u>[New] Data Size and Time Coefficient in Video Files (20MB) for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-boost-views-via-strategic-tagging-tactics/"><u>[Updated] In 2024, Boost Views via Strategic Tagging Tactics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-chromeedge-bar-hide-on-maxed-windows/"><u>Eliminating Chrome/Edge Bar Hide on Maxed Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-8-solutions-to-fix-find-my-friends-location-not-available-on-realme-narzo-n55-drfone-by-drfone-virtual-android/"><u>In 2024, 8 Solutions to Fix Find My Friends Location Not Available On Realme Narzo N55 | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-can-i-bypass-a-forgotten-phone-password-of-motorola-edge-40-neo-by-drfone-android/"><u>In 2024, Can I Bypass a Forgotten Phone Password Of Motorola Edge 40 Neo?</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-from-individual-tracks-to-albums-building-a-personalized-soundtrack-on-web-and-mobile/"><u>In 2024, From Individual Tracks to Albums Building a Personalized Soundtrack on Web & Mobile</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leverage-virtualization-with-hyper-v-on-windows-11-home-systems/"><u>Leverage Virtualization with Hyper-V on Windows 11 Home Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-windows-11-efficiency-with-shortcuts-and-nircmd/"><u>Master Your Windows 11 Efficiency with Shortcuts & NirCmd</u></a></li>
<li><a href="https://win-extraordinary.techidaily.com/movavis-ultimate-guide-to-convert-your-flac-tracks-to-mp4-videos-at-no-cost-do-it-online-today/"><u>Movavi's Ultimate Guide to Convert Your FLAC Tracks to MP4 Videos at No Cost - Do It Online Today!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-11-notification-settings/"><u>Navigating Windows 11 Notification Settings</u></a></li>
<li><a href="https://technical-tips.techidaily.com/solving-the-mystery-what-to-do-when-d3dx928dll-is-nowhere-to-be-found/"><u>Solving the Mystery: What to Do When d3dx9_28.dll Is Nowhere to Be Found</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-windows-11s-spotify-connectivity-hiccup/"><u>Solving Windows 11'S Spotify Connectivity Hiccup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-split-screen-on-pcs/"><u>Troubleshooting Split Screen on PCs</u></a></li>
</ul></div>

