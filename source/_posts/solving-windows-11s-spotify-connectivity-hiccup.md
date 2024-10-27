---
title: Solving Windows 11'S Spotify Connectivity Hiccup
date: 2024-10-21T16:07:47.865Z
updated: 2024-10-26T23:05:08.761Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solving Windows 11'S Spotify Connectivity Hiccup
excerpt: This Article Describes Solving Windows 11'S Spotify Connectivity Hiccup
keywords: Win11SpotifyIssue,FixWinSpotifyConn,ResolveWindows11Play,Windows11SpotifyLink,StopSpotifyConnectFail,CorrectWin11SoundSync,EliminateWindows11StreamError
thumbnail: https://thmb.techidaily.com/c7cd587848b7c423971790fdb3b04288b53670a44c37276f13cc96d749320e4c.jpg
---

## Solving Windows 11'S Spotify Connectivity Hiccup

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

<!-- affiliate ads begin -->
<span id="1993651">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993651.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993651">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993651.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993651%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993651/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Change DNS Server Settings

 Error code 4 often occurs because Spotify can’t recognize your PC’s default DNS server set by your ISP. In such a scenario, the app can’t load required online resources correctly, resulting in error 4\. Many users have addressed that issue by changing their PCs’ DNS server to the universally recognized Google DNS.

 Our guide to[changing the DNS server in Windows](https://www.makeuseof.com/windows-11-alternate-ways-change-dns-server-settings/) post includes step-by-step guidelines for how to apply this solution via the Control Panel and Settings among other methods. You’ll need to set the preferred and alternative DNS server settings to Google addresses. Input**8.8.8.8** for the preferred DNS server and**8.8.4.4** for the alternative DNS setting.

![DNS server settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dns-server-settings.jpg)

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
![The Edit DWORD window for the EnableActiveProbing DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/edit-dword-window.jpg)
8. Select**OK** to save the new**EnableActiveProbing** value.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037359/7443" target="_top" id="2037359">
  <img src="//a.impactradius-go.com/display-ad/7443-2037359" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037359/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Exclude Spotify From Your Antivirus Software

 You might need to fix error code 4 because of antivirus software interference with the Spotify app. Both third-party antivirus apps and Windows Security can feasibly block Spotify’s internet connectivity. You can select to exclude Spotify from antivirus protection by adding it to an exception (trusted software) list most security apps include.

![Windows Security's app exclusion settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-security-s-exclusion-list-settings.jpg)

 Our article about[setting Windows Security exclusions](https://www.makeuseof.com/windows-11-security-exclusions/) includes instructions for adding software to that app’s exception list. If you’re utilizing a third-party antivirus tool, look for an exclusion list within its settings tab. The antivirus software’s website will also likely include guidelines for how to use its exclusion list.

## 6\. Turn Off the Windows Defender Firewall

 Windows Defender Firewall is a component of Windows Security for filtering network traffic. Turning that firewall off could resolve error 4 if Spotify isn’t allowed through it. You can turn off WDF as outlined in our guide to[disabling the Windows Defender firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) .

![The turn off firewall settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-firewall-s-allow-app-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087234/19272" target="_top" id="2087234">
  <img src="//a.impactradius-go.com/display-ad/19272-2087234" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087234/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Should this solution work, it’s not a good idea to keep the firewall disabled. Open Windows Defender Firewall’s allowed app list and select the Spotify checkboxes there to permit that app through it. Check out our how to guide about[allowing apps through the Windows firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) for further details.

![The firewall's allowed apps settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/allowed-app-settings.jpg)

 Of course, numerous standalone third-party firewalls can block Spotify much the same. If you have installed a third-party firewall, try disabling it to see if that resolves error 4\. Then add Spotify to its allowed apps and turn the firewall back on if it does.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130885/7443" target="_top" id="2130885">
  <img src="//a.impactradius-go.com/display-ad/7443-2130885" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130885/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134494/18498" target="_top" id="2134494">
  <img src="//a.impactradius-go.com/display-ad/18498-2134494" border="0" alt="https://techidaily.com" width="721" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134494/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

8. Double-click the**SpotifySetup.exe** file to bring up the setup wizard and install Spotify.

 Another option is to install the Spotify UWP (Universal Windows Platform) app on Microsoft Store. Click the**Get it From Microsoft Store** button on the linked Spotify download page to bring up that app’s MS store page. Then click the**Get in Store app** \>**Open Microsoft Store** options and select**Get** to install the UWP app.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135372/19272" target="_top" id="2135372">
  <img src="//a.impactradius-go.com/display-ad/19272-2135372" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135372/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-tips.techidaily.com/024-approved-expert-advice-for-aspiring-youtube-stars-the-art-of-reaction-videos-3-essential-steps/"><u>[New] 2024 Approved Expert Advice for Aspiring YouTube Stars - The Art of Reaction Videos (3 Essential Steps)</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/024-approved-triple-trouble-how-to-handle-three-tubes-of-content-at-once/"><u>[New] 2024 Approved Triple Trouble How to Handle Three Tubes of Content at Once</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-brief-path-to-past-posts-reinstating-reddit-removals-quickly/"><u>[New] Brief Path to Past Posts Reinstating Reddit Removals Quickly</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-top-30-unique-pfps-for-a-stellar-tiktok-presence/"><u>[New] In 2024, Top 30 Unique PFPs for a Stellar TikTok Presence</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-ultimate-cartoony-transformation-tools-for-pcs-and-macs/"><u>[New] In 2024, Ultimate Cartoony Transformation Tools for PCs & Macs</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-the-path-to-flawless-streams-a-guide-to-recording-on-steam/"><u>[Updated] 2024 Approved The Path to Flawless Streams A Guide to Recording on Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-molds-changing-the-winadmin-access-paradigm/"><u>Breaking Molds: Changing the WinAdmin Access Paradigm</u></a></li>
<li><a href="https://win11-tips.techidaily.com/compelling-case-for-continuing-with-windows-10-win10/"><u>Compelling Case for Continuing with Windows 10 (Win10)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/confronting-memory-write-issues-in-windows/"><u>Confronting 'Memory Write' Issues in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/direct-route-to-recent-windows-documents/"><u>Direct Route to Recent Windows Documents</u></a></li>
<li><a href="https://tech-revival.techidaily.com/experience-ai-like-never-before-dive-into-openais-freshly-launched-gpt-custom-store-today/"><u>Experience AI Like Never Before - Dive Into OpenAI's Freshly Launched GPT Custom Store Today!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-mouse-navigation-turn-off-acceleration-windows-1011/"><u>Mastering Mouse Navigation: Turn Off Acceleration Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-to-startup-folder-in-windows-os-quickly/"><u>Navigating to Startup Folder in Windows OS Quickly</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/revolutionary-mobile-mac-data-cleanse-by-stellar-eraser-superior-standard-edition/"><u>Revolutionary Mobile Mac Data Cleanse by Stellar Eraser - Superior Standard Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-reactivate-apps-hindered-by-qt-plugin-issue/"><u>Steps to Reactivate Apps Hindered by Qt Plugin Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-anomalies-dealing-with-anydesk-issues-in-windows/"><u>Streamlining Anomalies: Dealing with AnyDesk Issues in Windows</u></a></li>
<li><a href="https://games-able.techidaily.com/top-budget-budgets-the-best-white-boards-of-2023/"><u>Top Budget Budgets: The Best White Boards of 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-correcting-wmp-failures/"><u>Understanding & Correcting WMP Failures</u></a></li>
<li><a href="https://activate-lock.techidaily.com/unlock-your-device-icloud-dns-bypass-explained-and-tested-plus-easy-alternatives-on-apple-iphone-15-pro-by-drfone-ios/"><u>Unlock Your Device iCloud DNS Bypass Explained and Tested, Plus Easy Alternatives On Apple iPhone 15 Pro</u></a></li>
</ul></div>

