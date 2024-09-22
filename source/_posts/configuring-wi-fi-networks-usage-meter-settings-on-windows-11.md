---
title: Configuring Wi-Fi Network's Usage Meter Settings on Windows 11
date: 2024-09-17T22:29:30.866Z
updated: 2024-09-21T19:28:04.037Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Configuring Wi-Fi Network's Usage Meter Settings on Windows 11
excerpt: This Article Describes Configuring Wi-Fi Network's Usage Meter Settings on Windows 11
keywords: Wi-Fi Usage Monitor,Windows 11 Network Settings,Metering Settings Config,Configuring Wi-Fi Meter,Tracking Bandwidth Use,Setting Data Limits,Wi-Fi Consumption Control
thumbnail: https://thmb.techidaily.com/a23ef58f3369824904efee9f97817b15b093c9dc4ea1ce81d7226560e11dda64.jpg
---

## Configuring Wi-Fi Network's Usage Meter Settings on Windows 11

 If you're using a capped internet connection, such as a mobile hotspot, you'd want to limit your Windows PC's background data usage. That way, you ensure that background processes, like OneDrive or Steam, do not use up all your data while your computer's on.

 But how do you configure your PC to treat a Wi-Fi network as a metered or unmetered connection? Luckily, Windows 11 provides a couple of different ways to enable or disable metered connections for a Wi-Fi network. Let's go over both of them in detail.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Enable or Disable Metered Connections for a Wi-Fi Network Using the Settings App

 The**Network & internet** section in the Settings app serves as a central location for all the network-related settings on Windows. You can visit that section to quickly enable or disable a metered connection for your computer's Wi-Fi network. Here are the steps for the same.

1. Open the**Start menu** and click the**gear-shaped icon** to[launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Network & internet** from the left sidebar.
3. Click on**Wi-Fi** from the right pane.
4. Go to**Manage known networks** .
5. Select the network you want to configure.
6. Enable the toggle next to**Metered connection** to set the Wi-Fi network as metered. If you want to set the network as an unmetered connection, disable the toggle.  
![Enable or Disable Metered Connection in Windows 11 Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/enable-or-disable-metered-connection-in-windows-11-using-settings-app.jpg)

 Note that you'll have to repeat the above steps for each Wi-Fi network separately. Following that, Windows will remember your network preferences.

## 2\. Enable or Disable Wi-Fi Metered Connections via the Command Prompt

 If you're a power user who prefers to make system changes with a command-line tool, you can use the[Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to enable or disable metered connection for a Wi-Fi network on Windows. Here's how you can go about it.

1. Right-click the**Start icon** or use the**Win + X** keyboard shortcut to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the terminal window, type the following command and press**Enter** to view a list of network profiles on your computer:  
`netsh wlan show profiles`  
![Network Profiles in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-profiles-in-windows.jpg)
5. Note down the Wi-Fi network name for which you want to enable or disable the metered connection option.
6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on[the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

## Efficiently Manage Your Data With Metered Connection

 Enabling or disabling the metered connection option for Wi-Fi networks in Windows is relatively simple, regardless of the method you use.

 If you have a limited data plan, you can also set a data usage limit for your Wi-Fi connection. This way, Windows will notify you when you approach the set data limit.

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
<li><a href="https://instagram-video-files.techidaily.com/new-cutting-edge-strategies-for-dynamic-igtv-backgrounds/"><u>[New] Cutting-Edge Strategies for Dynamic IGTV Backgrounds</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-mastering-snapchats-filter-frenzy-a-comprehensive-handbook/"><u>[New] Mastering Snapchat's Filter Frenzy A Comprehensive Handbook</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-transform-your-instagram-vids-with-advanced-editing-skills-for-2024/"><u>[Updated] Transform Your Instagram Vids with Advanced Editing Skills for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-canvas-kids-discover-10-free-kid-friendly-art-makers-for-mac/"><u>2024 Approved Canvas Kids Discover 10 Free, Kid-Friendly Art Makers for Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1726224350544-aimp3-movavi/"><u>免費線上AI到MP3的音頻變換 - 如何使用 Movavi 工具</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1726226878276-3gpswf-movavi/"><u>網路直接無成本自動轉換3GP到SWF - 使用Movavi的方法</u></a></li>
<li><a href="https://win11-tips.techidaily.com/aif-mov-url/"><u>AIF MOV 파일을 제공하는 URL로 원격에서 무료 바이트열 변환 - 모바비</u></a></li>
<li><a href="https://win11-tips.techidaily.com/asfavi/"><u>ASF形式の動画をAVIに変換する自由なオンラインツール - 快適で使いやすくて安全な方法!</u></a></li>
<li><a href="https://windows11.techidaily.com/function-keys-not-working-in-windows-10-heres-what-to-do/"><u>Function Keys Not Working in Windows 10? Here's What to Do</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-do-i-stop-someone-from-tracking-my-zte-blade-a73-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How Do I Stop Someone From Tracking My ZTE Blade A73 5G? | Dr.fone</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/in-2024-unlocking-old-tweets-with-twitter-archive-tools/"><u>In 2024, Unlocking Old Tweets with Twitter Archive Tools</u></a></li>
<li><a href="https://win-able.techidaily.com/master-the-solution-stop-your-app-from-breaking-down-with-this-detailed-crash-fix-guide/"><u>Master the Solution: Stop Your App From Breaking Down with This Detailed Crash Fix Guide</u></a></li>
<li><a href="https://extra-information.techidaily.com/no-pay-maximum-fun-20-custom-lut-sets-for-dji-miniair-users/"><u>No Pay, Maximum Fun 20 Custom LUT Sets for DJI Mini/Air Users</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014848/22899" target="_top" id="2014848">
  <img src="//a.impactradius-go.com/display-ad/22899-2014848" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014848/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

