---
title: Efficient Management of Wi-Fi Data Metering Settings on Win11
date: 2024-10-27T18:24:11.666Z
updated: 2024-11-01T18:32:29.857Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Efficient Management of Wi-Fi Data Metering Settings on Win11
excerpt: This Article Describes Efficient Management of Wi-Fi Data Metering Settings on Win11
keywords: Wi-Fi Data Management,Win11 Metering Controls,Optimize Wi-Fi Settings,Wi-Fi Efficiency in Windows,Data Metering Adjustment,Win11 Network Config,Manage Wi-Fi Consumption
thumbnail: https://thmb.techidaily.com/c64fedaf756cbcf9ac92722c1b2668052e1efc526bd85097cc0c097ddacbbc3a.jpg
---

## Efficient Management of Wi-Fi Data Metering Settings on Win11

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
<a href="https://bluettieu.pxf.io/c/5597632/2141676/17091" target="_top" id="2141676">
  <img src="//a.impactradius-go.com/display-ad/17091-2141676" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettieu.pxf.io/i/5597632/2141676/17091" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1880960/19272" target="_top" id="1880960">
  <img src="//a.impactradius-go.com/display-ad/19272-1880960" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880960/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135402/19272" target="_top" id="2135402">
  <img src="//a.impactradius-go.com/display-ad/19272-2135402" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135402/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on[the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2112008/7443" target="_top" id="2112008">
  <img src="//a.impactradius-go.com/display-ad/7443-2112008" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2112008/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-quick-tips-apply-smooth-motion-blur-on-your-pics/"><u>[New] 2024 Approved Quick Tips Apply Smooth Motion Blur on Your Pics</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-the-pinnacle-selector-your-personal-video-vault/"><u>[New] 2024 Approved The Pinnacle Selector Your Personal Video Vault</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-smooth-blur-magic-for-instagrams-story-moments/"><u>[New] In 2024, Smooth Blur Magic for Instagram's Story Moments</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-the-art-of-storytelling-integrating-captions-into-your-instagram-videos-for-2024/"><u>[New] The Art of Storytelling Integrating Captions Into Your Instagram Videos for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-the-future-of-flight-hubsans-revolutionary-h501s-explored/"><u>[Updated] The Future of Flight - Hubsan's Revolutionary H501S Explored</u></a></li>
<li><a href="https://win11-tips.techidaily.com/debugging-problematic-code-x0001-on-windows-11-and-11/"><u>Debugging Problematic Code X0001 on Windows 11 & 11</u></a></li>
<li><a href="https://games-able.techidaily.com/enhancing-gameplay-with-improved-3d-models/"><u>Enhancing Gameplay with Improved 3D Models</u></a></li>
<li><a href="https://win11-tips.techidaily.com/five-easy-methods-to-eliminate-network-keys-mismatch-in-windows-11/"><u>Five Easy Methods to Eliminate Network Keys Mismatch in Windows 11</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-secrets-to-high-quality-roblox-game-footage-on-macos/"><u>In 2024, Secrets to High-Quality Roblox Game Footage on macOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsofts-phone-link-app-what-is-it-and-how-do-you-use-it/"><u>Microsoft's Phone Link App: What Is It and How Do You Use It?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prevent-webp-conversion-alter-chromee-images-on-your-pc/"><u>Prevent WebP Conversion: Alter Chrome’e Images on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocketing-through-efficiency-top-7-strategies-with-windows-11/"><u>Skyrocketing Through Efficiency: Top 7 Strategies with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-system-implement-autodelete-feature-in-winos/"><u>Streamline Your System: Implement AutoDelete Feature in WINOS</u></a></li>
<li><a href="https://sound-issues.techidaily.com/ultimate-solutions-how-to-restore-functionality-in-non-responsive-pc-speakers/"><u>Ultimate Solutions: How to Restore Functionality in Non-Responsive PC Speakers</u></a></li>
<li><a href="https://win-dash.techidaily.com/usb-to-hdmi-or-vga-get-your-insignia-cables-latest-drivers-here/"><u>USB to HDMI or VGA: Get Your Insignia Cable's Latest Drivers Here!</u></a></li>
</ul></div>

