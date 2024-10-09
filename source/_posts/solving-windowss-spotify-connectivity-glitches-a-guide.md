---
title: "Solving Windows's Spotify Connectivity Glitches: A Guide"
date: 2024-10-06T16:40:09.926Z
updated: 2024-10-08T16:45:21.972Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Solving Windows's Spotify Connectivity Glitches: A Guide"
excerpt: "This Article Describes Solving Windows's Spotify Connectivity Glitches: A Guide"
keywords: Fix Spotify PC Error,Spotify Playback FIX,Solve Spotify PC Issue,Windows Spotify Stability,Troubleshoot Spotify Connect,Spotify Glitch Resolution,Enhance Spotify Functionality
thumbnail: https://thmb.techidaily.com/a686c6eefaf9c4b50a452c73ac89f7229b66217691cf20f6f81f6b08cd386aeb.jpg
---

## Solving Windows's Spotify Connectivity Glitches: A Guide

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

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/798165/11305" target="_top" id="798165">
  <img src="//a.impactradius-go.com/display-ad/11305-798165" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i110150.net/i/5597632/798165/11305" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The HTTP option in Spotify](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/http-option.jpg)
5. Then select**Restart App** to apply.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012420/19272" target="_top" id="2012420">
  <img src="//a.impactradius-go.com/display-ad/19272-2012420" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012420/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925549/19272" target="_top" id="1925549">
  <img src="//a.impactradius-go.com/display-ad/19272-1925549" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925549/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Edit DWORD window for the EnableActiveProbing DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/edit-dword-window.jpg)
8. Select**OK** to save the new**EnableActiveProbing** value.

## 5\. Exclude Spotify From Your Antivirus Software

 You might need to fix error code 4 because of antivirus software interference with the Spotify app. Both third-party antivirus apps and Windows Security can feasibly block Spotify’s internet connectivity. You can select to exclude Spotify from antivirus protection by adding it to an exception (trusted software) list most security apps include.

![Windows Security's app exclusion settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-security-s-exclusion-list-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484940/16446" target="_top" id="1484940">
  <img src="//a.impactradius-go.com/display-ad/16446-1484940" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484940/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Our article about[setting Windows Security exclusions](https://www.makeuseof.com/windows-11-security-exclusions/) includes instructions for adding software to that app’s exception list. If you’re utilizing a third-party antivirus tool, look for an exclusion list within its settings tab. The antivirus software’s website will also likely include guidelines for how to use its exclusion list.

## 6\. Turn Off the Windows Defender Firewall

 Windows Defender Firewall is a component of Windows Security for filtering network traffic. Turning that firewall off could resolve error 4 if Spotify isn’t allowed through it. You can turn off WDF as outlined in our guide to[disabling the Windows Defender firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) .

![The turn off firewall settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-firewall-s-allow-app-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134248/18498" target="_top" id="2134248">
  <img src="//a.impactradius-go.com/display-ad/18498-2134248" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134248/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<span id="1975636">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975636.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975636">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975636.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975636%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975636/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Then open the[Spotify Windows](https://www.spotify.com/us/download/windows/) download page.
6. Click**Download** to get the installer for the desktop Spotify app.  
![The Download Spotify option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/download-option.jpg)
7. Open the Explorer file manager along with the folder in which Spotify downloaded.
8. Double-click the**SpotifySetup.exe** file to bring up the setup wizard and install Spotify.

 Another option is to install the Spotify UWP (Universal Windows Platform) app on Microsoft Store. Click the**Get it From Microsoft Store** button on the linked Spotify download page to bring up that app’s MS store page. Then click the**Get in Store app** \>**Open Microsoft Store** options and select**Get** to install the UWP app.

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
<li><a href="https://some-skills.techidaily.com/updated-the-prime-picks-best-storytelling-channels-fans/"><u>[Updated] The Prime Picks Best Storytelling Channels Fans</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-exploring-the-realm-of-physical-interaction-tech/"><u>2024 Approved Exploring the Realm of Physical Interaction Tech</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/best-splashproof-cameras-for-child-filmmakers-in-rainy-days/"><u>Best Splashproof Cameras For Child Filmmakers in Rainy Days</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathing-life-into-frozen-windows-hibernate/"><u>Breathing Life Into Frozen Windows Hibernate</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-systems-android-to-windows-shared-files/"><u>Bridging Systems: Android to Windows Shared Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-the-forgotten-how-to-locate-the-hidden-enhancement-in-windows-11/"><u>Bring Back the Forgotten: How to Locate the Hidden Enhancement in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-windows-update-service-quickly/"><u>Bring Back Windows Update Service Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-pin-for-smooth-projections-on-windows-11/"><u>Bypass PIN for Smooth Projections on WIndows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-ssi-on-windows-easy-installation-of-unchecked-drivers/"><u>Bypassing SSI on Windows: Easy Installation of Unchecked Drivers</u></a></li>
<li><a href="https://video-capture.techidaily.com/discover-the-best-free-tools-for-rapid-download-of-xnxx-content-without-hurdles/"><u>Discover the Best Free Tools for Rapid Download of XNXX Content Without Hurdles</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/how-to-successfully-overcome-whea-unrecoverable-bsod-mistakes/"><u>How to Successfully Overcome WHEA Unrecoverable BSOD Mistakes</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-feasible-ways-to-fake-location-on-facebook-for-your-honor-x50iplus-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Feasible Ways to Fake Location on Facebook For your Honor X50i+ | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/quick-and-simple-setup-download-drivers-for-brother-mfc-7360n-on-pcs-running-windows-1187/"><u>Quick and Simple Setup: Download Drivers for Brother MFC-7360N on PCs Running Windows 11/8/7</u></a></li>
<li><a href="https://tech-revival.techidaily.com/reimagining-coding-with-non-chatgpt-ai-innovations/"><u>Reimagining Coding with Non-ChatGPT AI Innovations</u></a></li>
</ul></div>

