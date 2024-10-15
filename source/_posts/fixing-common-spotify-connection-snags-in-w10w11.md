---
title: Fixing Common Spotify Connection Snags in W10/W11
date: 2024-10-12T07:27:00.191Z
updated: 2024-10-14T19:30:38.946Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Common Spotify Connection Snags in W10/W11
excerpt: This Article Describes Fixing Common Spotify Connection Snags in W10/W11
keywords: Fix Spotify Disconnects,Resolve WiFi Issues,Streaming Woes Remedied,Connectivity Troubleshooting,Stop Playback Pauses,Wi-Fi Sound Interruptions,Clear Spotify Glitches
thumbnail: https://thmb.techidaily.com/c465b3961d0e8ae791649e84e8128b1614e8e09e935ed979e13eb915c45489fc.jpg
---

## Fixing Common Spotify Connection Snags in W10/W11

 Spotify is one of the best Windows apps for streaming and downloading music. However, some Spotify users can’t stream and download music with that app because of error code 4\. Error code 4 is a Spotify connectivity issue with a message that says, “No internet connection detected.” Yet, users can usually still open and view websites when that issue arises.

 Users who need to fix error code 4 can’t utilize the Spotify app online. That means things like radio and streaming don’t work. This is how you can fix Spotify error code 4 on a Windows 10 or 11 PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Run the Flush DNS Command

![The flushdns command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/flushdns-command.jpg)

 One confirmed solution for error code 4 is to flush the DNS cache. The DNS (Domain Name System) cache is a local storage repository of IP addresses on your PC. Your web browser retrieves DNS lookup data from that cache.

 Clearing the DNS cache will flush out and refresh its data. You can clear the DNS cache by running a flush DNS command in Command Prompt or Run. Check out our guide about[how to flush the DNS](https://www.makeuseof.com/flush-dns-cache-windows-11/) on Windows for further details about how to apply this solution.

## 2\. Select the HTTP Option in Spotify

 Spotify includes alternative proxy settings you can select to configure how that app connects with the Internet. Changing the proxy option to**HTTP** can reputedly resolve error code 4\. You can select the**HTTP** option in Spotify as follows:

1. Open your Spotify app.
2. Click the username button at the top of Spotify to view its menu.
3. Select**Settings** to view Spotify’s options.  
![The Settings menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-settings-option.jpg)
4. Click the**Proxy type** drop-down menu to select**HTTP** .  
![The HTTP option in Spotify](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/http-option.jpg)
5. Then select**Restart App** to apply.

## 3\. Change DNS Server Settings

 Error code 4 often occurs because Spotify can’t recognize your PC’s default DNS server set by your ISP. In such a scenario, the app can’t load required online resources correctly, resulting in error 4\. Many users have addressed that issue by changing their PCs’ DNS server to the universally recognized Google DNS.

 Our guide to[changing the DNS server in Windows](https://www.makeuseof.com/windows-11-alternate-ways-change-dns-server-settings/) post includes step-by-step guidelines for how to apply this solution via the Control Panel and Settings among other methods. You’ll need to set the preferred and alternative DNS server settings to Google addresses. Input**8.8.8.8** for the preferred DNS server and**8.8.4.4** for the alternative DNS setting.

![DNS server settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dns-server-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/2106655/12108" target="_top" id="2106655">
  <img src="//a.impactradius-go.com/display-ad/12108-2106655" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/2106655/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Tweak the Registry

 Some Spotify users have confirmed tweaking a DWORD value in the registry resolved error 4 for them. Those users changed the EnableActiveProbing DWORD’s value, which was set to 0 (disabled) on their PCs. These are the steps for fixing error code 4 by editing the registry:

1. Press the search box’s**Win + S** hotkey.
2. To locate the Registry Editor, enter**regedit** inside the**Type here to search** box.
3. Select Registry Editor inside the search tool.
4. Next, click within the address bar at the top of Registry Editor to clear the current location in it.
5. Go to the Internet key by inputting the following path:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\NlaSvc\Parameters\Internet`
6. Then right-click the**EnableActiveProbing** DWORD and select**Modify** .  
![The Modify option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/modify-option.jpg)
7. If**EnableActiveProbing** is set to**0** , clear the**Value data** box. Then input**1** inside that data box.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975802/19272" target="_top" id="1975802">
  <img src="//a.impactradius-go.com/display-ad/19272-1975802" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975802/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Edit DWORD window for the EnableActiveProbing DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/edit-dword-window.jpg)
8. Select**OK** to save the new**EnableActiveProbing** value.

<!-- affiliate ads begin -->
<span id="1983474">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983474.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983474">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983474.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983474%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983474/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137378/7443" target="_top" id="2137378">
  <img src="//a.impactradius-go.com/display-ad/7443-2137378" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137378/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Exclude Spotify From Your Antivirus Software

 You might need to fix error code 4 because of antivirus software interference with the Spotify app. Both third-party antivirus apps and Windows Security can feasibly block Spotify’s internet connectivity. You can select to exclude Spotify from antivirus protection by adding it to an exception (trusted software) list most security apps include.

![Windows Security's app exclusion settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-security-s-exclusion-list-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139115/17108" target="_top" id="2139115">
  <img src="//a.impactradius-go.com/display-ad/17108-2139115" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139115/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Our article about[setting Windows Security exclusions](https://www.makeuseof.com/windows-11-security-exclusions/) includes instructions for adding software to that app’s exception list. If you’re utilizing a third-party antivirus tool, look for an exclusion list within its settings tab. The antivirus software’s website will also likely include guidelines for how to use its exclusion list.

## 6\. Turn Off the Windows Defender Firewall

 Windows Defender Firewall is a component of Windows Security for filtering network traffic. Turning that firewall off could resolve error 4 if Spotify isn’t allowed through it. You can turn off WDF as outlined in our guide to[disabling the Windows Defender firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) .

![The turn off firewall settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-firewall-s-allow-app-settings.jpg)

 Should this solution work, it’s not a good idea to keep the firewall disabled. Open Windows Defender Firewall’s allowed app list and select the Spotify checkboxes there to permit that app through it. Check out our how to guide about[allowing apps through the Windows firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) for further details.

![The firewall's allowed apps settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/allowed-app-settings.jpg)

 Of course, numerous standalone third-party firewalls can block Spotify much the same. If you have installed a third-party firewall, try disabling it to see if that resolves error 4\. Then add Spotify to its allowed apps and turn the firewall back on if it does.

## 7\. Reinstall Spotify

 Reinstalling Spotify could resolve unknown reasons for error code 4 arising and will at least ensure you’re using the latest app version. However, note that reinstalling the app will wipe your Spotify playlists. Back up (export) any playlists you wish to keep so you can restore them. Then reinstall Spotify with the following steps:

1. Press the Start menu button and select**All apps** (in Windows 11).
2. Scroll down to the Spotify app on the Start menu.
3. Right-click Spotify and select**Uninstall** .  
![Spotify's Uninstall option on the Start menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-start-menu-s-uninstall-option.jpg)
4. If you’ve installed the desktop Spotify app, Programs and Features will open from which you can select the software and click**Uninstall** . Users who’ve installed the UWP Spotify app can select**Uninstall** on a confirmation prompt.
5. Then open the[Spotify Windows](https://www.spotify.com/us/download/windows/) download page.
6. Click**Download** to get the installer for the desktop Spotify app.  
![The Download Spotify option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/download-option.jpg)
7. Open the Explorer file manager along with the folder in which Spotify downloaded.
8. Double-click the**SpotifySetup.exe** file to bring up the setup wizard and install Spotify.

 Another option is to install the Spotify UWP (Universal Windows Platform) app on Microsoft Store. Click the**Get it From Microsoft Store** button on the linked Spotify download page to bring up that app’s MS store page. Then click the**Get in Store app** \>**Open Microsoft Store** options and select**Get** to install the UWP app.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1061528/11832" target="_top" id="1061528">
  <img src="//a.impactradius-go.com/display-ad/11832-1061528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1061528/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Enjoy Spotify Music Online Again

 There’s a very good chance at least one Windows troubleshooting method in this guide will resolve Spotify error code 4 on your PC. They’re user-confirmed fixes that address the most common reasons for error 4 arising. With that app connection issue sorted, you can then enjoy all the best online music and radio Spotify has to offer again.

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
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-easy-process-how-to-save-twitter-videos-on-an-android-device/"><u>[New] In 2024, Easy Process How to Save Twitter Videos on an Android Device</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-effortless-downloads-at-zero-cost-find-the-top-20-tools-for-youtube-sound-ripping/"><u>[New] In 2024, Effortless Downloads at Zero Cost Find the Top 20 Tools for YouTube Sound Ripping</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-essential-solutions-for-troubleshooting-missing-wireless-connections-in-windows-10/"><u>10 Essential Solutions for Troubleshooting Missing Wireless Connections in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-default-screen-saver-in-windows-11/"><u>Adjusting Default Screen Saver in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-xbox-game-pass-0x00000001-troubleshooting-for-windows-11/"><u>Avoiding Xbox Game Pass 0X00000001: Troubleshooting for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-yellow-shade-from-laptop-panels/"><u>Banishing Yellow Shade From Laptop Panels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/battle-bugs-tackling-skyrims-extension-failure/"><u>Battle Bugs: Tackling Skyrim's Extension Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/black-friday-special-612-unlimited-win10-life/"><u>Black Friday Special: $6.12, Unlimited Win10 Life</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boltgun-playtime-maximized-overcoming-computer-delays-in-warhammer-40k/"><u>Boltgun Playtime Maximized: Overcoming Computer Delays in Warhammer 40K</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-by-mastering-task-management-on-a-windows-11-pc/"><u>Boost Productivity by Mastering Task Management on a Windows 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-start-menu-efficiency-in-the-world-of-windows-11/"><u>Boost Your Start Menu Efficiency in the World of Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-typing-copy-pasting-expertise/"><u>Boost Your Typing, Copy-Pasting Expertise</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-honor-x7b-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Honor X7b | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-all-you-need-to-know-about-mega-greninja-for-realme-c55-drfone-by-drfone-virtual-android/"><u>In 2024, All You Need To Know About Mega Greninja For Realme C55 | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-fcpx-essential-edits-a-step-by-step-guide-to-l-cuts-and-j-cuts/"><u>In 2024, FCPX Essential Edits A Step-by-Step Guide to L-Cuts and J-Cuts</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-ultracapture-pro-the-march-2023-examination/"><u>In 2024, UltraCapture Pro – The March 2023 Examination</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/inside-toms-hardware-comprehensive-guides-for-tech-enthusiasts/"><u>Inside Tom's Hardware: Comprehensive Guides for Tech Enthusiasts</u></a></li>
<li><a href="https://vp-tips.techidaily.com/top-6-ai-video-enhancement-tools-for-stunning-results/"><u>Top 6 AI Video Enhancement Tools for Stunning Results</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unlock-productivity-discovering-7-advantages-of-chatgpt-in-workflow/"><u>Unlock Productivity: Discovering 7 Advantages of ChatGPT in Workflow</u></a></li>
</ul></div>

