---
title: Configuring Wi-Fi Network's Usage Meter Settings on Windows 11
date: 2024-10-04T17:06:40.611Z
updated: 2024-10-08T21:53:27.174Z
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

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528693/16446" target="_top" id="1528693">
  <img src="//a.impactradius-go.com/display-ad/16446-1528693" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528693/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Enable or Disable Wi-Fi Metered Connections via the Command Prompt

 If you're a power user who prefers to make system changes with a command-line tool, you can use the[Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to enable or disable metered connection for a Wi-Fi network on Windows. Here's how you can go about it.

1. Right-click the**Start icon** or use the**Win + X** keyboard shortcut to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the terminal window, type the following command and press**Enter** to view a list of network profiles on your computer:  
`netsh wlan show profiles`  
![Network Profiles in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-profiles-in-windows.jpg)
5. Note down the Wi-Fi network name for which you want to enable or disable the metered connection option.

<!-- affiliate ads begin -->
<span id="701707">
					<video width="1536" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/701707.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/7443-701707">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/701707.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:960px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fappsumo.8odi.net%2Fc%2F5597632%2F701707%2F7443'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/701707/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144283/7443" target="_top" id="2144283">
  <img src="//a.impactradius-go.com/display-ad/7443-2144283" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144283/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on[the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049383/7443" target="_top" id="2049383">
  <img src="//a.impactradius-go.com/display-ad/7443-2049383" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049383/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://instagram-video-recordings.techidaily.com/new-mastering-the-art-of-instagram-video-bordering-for-2024/"><u>[New] Mastering the Art of Instagram Video Bordering for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/approved-maximizing-income-mastering-short-video-markets/"><u>2024 Approved Maximizing Income Mastering Short Video Markets</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/decoding-the-art-of-engaging-in-youtube-short-forms-for-2024/"><u>Decoding the Art of Engaging in YouTube Short Forms for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decreasing-cpu-impact-from-ntoskrnlexe/"><u>Decreasing CPU Impact From Ntoskrnl.exe</u></a></li>
<li><a href="https://howto.techidaily.com/fix-lava-storm-5g-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Lava Storm 5G Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-your-insignia-usb-ethernet-adaptor-up-and-running-with-this-driver-download/"><u>Get Your Insignia USB-Ethernet Adaptor Up and Running with This Driver Download</u></a></li>
<li><a href="https://win11-tips.techidaily.com/new-horizons-for-pc-users-features-in-win11-feb-2023-patch/"><u>New Horizons for PC Users - Features in Win11 FEB 2023 Patch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/scribing-success-best-writing-aids-for-windows-pc/"><u>Scribing Success: Best Writing Aids for Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocketing-system-performance-through-vram-upgrade-on-windows/"><u>Skyrocketing System Performance Through VRAM Upgrade on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-terminal-hurdles-on-your-pc/"><u>Solving Terminal Hurdles on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transition-from-cr2-to-jpg-format-with-windows-ease/"><u>Transition From CR2 to JPG Format with Windows Ease</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/whats-crucial-in-choosing-your-next-smart-tv/"><u>What's Crucial in Choosing Your Next Smart TV?</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/which-pokemon-can-evolve-with-a-moon-stone-for-honor-magic-5-pro-drfone-by-drfone-virtual-android/"><u>Which Pokémon can Evolve with a Moon Stone For Honor Magic 5 Pro? | Dr.fone</u></a></li>
</ul></div>

