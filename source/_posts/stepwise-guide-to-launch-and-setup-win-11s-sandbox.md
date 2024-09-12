---
title: Stepwise Guide to Launch and Setup Win 11'S Sandbox
date: 2024-09-11T01:27:54.681Z
updated: 2024-09-12T01:27:54.681Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stepwise Guide to Launch and Setup Win 11'S Sandbox
excerpt: This Article Describes Stepwise Guide to Launch and Setup Win 11'S Sandbox
keywords: Win 11 Sandbox Installation,Windows 11 Safe Mode,Win 11 Security Sandbox,Setting Up Win 11 Sandbox,Guide to Win 11 Setup,Win 11 Basic Configuration,Launching Win 11 Sandbox
thumbnail: https://thmb.techidaily.com/d0ad864c2a74122a666dad56374980e063d684e4d59ea3afda17d52be535612e.jpg
---

## Stepwise Guide to Launch and Setup Win 11'S Sandbox

 Microsoft Windows 11 features multiple virtualization solutions out of the box. While Hyper-V is an excellent tool, Windows Sandbox is an easy alternative to Windows virtual machines. It lets you run untrusted apps in an isolated environment without the hassle of setting up a complete virtualization tool.

 Unfortunately, Windows Sandbox is not available on the Home edition of the OS. If you are running the Pro, Enterprise, and Education edition, here is how to enable and set up Windows Sandbox in Windows 11.


>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>



## How to Set Up Windows Sandbox in Windows 11

 Windows Sandbox is an optional feature, which means you'll have to install it from the Optional features section. You can[add and remove optional features from the Windows Features dialog](http://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) . Alternatively, you can use PowerShell or Command Prompt for a swift installation of Windows Sandbox.

 While the setup process is easier, your computer must meet some system requirements. Windows 11 Pro, Education, or Enterprise running computers with virtualization support are Windows Sandbox compatible. In most cases,[if your system can run Windows Hyper-V](https://www.makeuseof.com/windows-11-enable-hyper-v/) , it should also run Windows Sandbox.

## 1\. Enable Windows Sandbox Using the Windows Features Dialog

 You can install Windows Sandbox using the Windows Features dialog. This dialog houses most of the optional Windows features that are ready to be installed on your PC.

 Follow these steps to install Windows Sandbox using the Windows Features dialog:

1. Press**Win + R** to open**Run** .
2. Type**appwiz.cpl** and click**OK** to open**Control Panel.**
3. In the left panel, click on**Turn Windows features on or off.**  
![control panel turn windows features on or off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/control-panel-turn-windows-features-on-or-off.jpg)
4. In the**Turn Windows features on or off dialog** , scroll down and locate**Windows Sandbox.**




<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136613/26400" target="_top" id="2136613">
  <img src="//a.impactradius-go.com/display-ad/26400-2136613" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136613/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




5. Check the**Windows Sandbox** option and click**OK** .  
![enable Windows sandbox turn windows features on or off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-Windows-sandbox-turn-windows-features-on-or-off.jpg)
6. Windows will search for the files and install the required dependencies to run Windows Sandbox scenarios. Once the changes are applied, close the Windows features dialog and restart your PC.




<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2120863/26400?prodsku=Mercury" target="_top" id="2120863">
  <img src="//a.impactradius-go.com/display-ad/26400-2120863" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2120863/26400?prodsku=Mercury" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




7. After the restart, press**Win + S** to open**Windows search.**
8. Type**sandbox** and click on**Windows Sandbox** from the search result to launch the virtualization tool.





<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136617/26400" target="_top" id="2136617">
  <img src="//a.impactradius-go.com/display-ad/26400-2136617" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136617/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 3\. Install Windows Sandbox Using PowerShell

![enable windows sandbox powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-windows-sandbox-powershell.jpg)

 You can use the Enable WindowsOptionalFeature command in PowerShell to install Windows Sandbox in Windows. This method is useful if you find the sandbox option greyed out or unable to install it from the Windows Feature dialog.

To install Windows Sandbox using PowerShell:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Windows Terminal (Admin)** to open the Windows Terminal with administrative privilege. Since PowerShell is assigned as the default profile upon launch, you can execute your PowerShell cmdlets straight away in Windows Terminal.
3. In the Windows Terminal window, copy and paste the following command and press Enter:  
Enable-WindowsOptionalFeature -Online -FeatureName "Containers-DisposableClientVM" -All
4. If no error occurs, Windows will install the required files to enable Windows Sandbox.
5. Once done, press**Y** and hit**Enter** to restart your PC.
6. After the restart, you can launch Windows Sandbox from Windows Search.

## 3\. Install Windows SandBox Using Command Prompt

![enable windows sandbox command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-windows-sandbox-command-prompt.jpg)





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135417/19272" target="_top" id="2135417">
  <img src="//a.impactradius-go.com/display-ad/19272-2135417" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135417/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 Deployment Image Servicing and Management (DISM) is a command-line utility that facilitates the installation of optional features using the Command Prompt. To install Windows Sandbox, you will need to use the Enable-Feature command in Command Prompt. Here's how to do it.

1. Press**Win + R** to open**Run** .
2. Type**cmd** in the**Run** dialog. Press and hold**Ctrl + Shift** and click**OK** to open Command Prompt as administrator.
3. In the Command Prompt, type the following command and press**Enter** :  
`dism /online /Enable-Feature /FeatureName: "Containers-DisposableClientVM" -All`
4. Wait for the process to complete. Once done, press**Y** and**Enter** to restart your PC.

## How to Use Windows Sandbox

![Windows Sandbox Open](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Windows-Sandbox-Open.jpg)





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135357/19272" target="_top" id="2135357">
  <img src="//a.impactradius-go.com/display-ad/19272-2135357" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135357/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 Now that you have Windows Sandbox installed, you can start using it to test untrusted apps in isolation. To launch the app, press**Win + S** to open**Windows Search** and type**Windows Sandbox.** Click on the app from the search result to open it.

 Upon its launch, Windows Sandbox looks like a lightweight version of your Windows machine. You can copy files from your host system or download them from the Internet using the built-in web browser. Any actions you perform in the sandbox will not affect your host system.

 Once the testing is complete, close the Sandbox and click**OK** to confirm the action. Unlike a VM, Sandbox will delete all the data (including apps and files) upon exit. So, you'll get a clean, isolated environment running the same Windows OS build as your host machine each time.





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135373/19272" target="_top" id="2135373">
  <img src="//a.impactradius-go.com/display-ad/19272-2135373" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135373/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Set Up and Use Windows Sandbox in Windows 11

 Windows Sandbox provides an excellent way to test apps and files in an isolated environment without the hassle of setting up a virtual machine. While the virtual machines have distinct advantages, Sandbox is lighter, faster, and loads a fresh copy of Windows OS each time it's run.

 Windows 11 Home users, however, have missed out on this excellent feature. But if you must use a sandbox, consider using third-party alternatives such as Sandboxie Plus and SHADE Sandbox. These alternatives offer a similar set of functionalities with no complicated setup involved.


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
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-behind-the-scenes-of-music-enhanced-snapchats/"><u>[New] In 2024, Behind the Scenes of Music-Enhanced Snapchats</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-maximize-engagement-with-facebook-posting-360-degree-photos-on-mobile/"><u>[New] In 2024, Maximize Engagement with Facebook Posting 360-Degree Photos on Mobile</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-pristineai-designs-crafting-visuals-with-ai/"><u>[New] PristineAI Designs Crafting Visuals with AI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-and-remedying-error-0x8007000d-on-pcs/"><u>Deciphering and Remedying 'Error 0X8007000D' On PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/design-focused-windows-11-start-menu/"><u>Design-Focused Windows 11 Start Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-how-copilot-key-upgrades-your-windows-11-experience/"><u>Discovering How Copilot Key Upgrades Your Windows 11 Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-fixes-activating-sleeping-wsreset-process/"><u>Effective Fixes: Activating Sleeping WSReset Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-windows-experience-with-these-top-7-tips-36/"><u>Elevate Your Windows Experience with These Top 7 Tips (36)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-data-security-adding-passwords-to-windows-text/"><u>Enhancing Data Security: Adding Passwords to Windows Text</u></a></li>
<li><a href="https://win-solutions.techidaily.com/expert-advice-on-overcoming-stuttering-issues-with-borderlands-ngameplay/"><u>Expert Advice on Overcoming Stuttering Issues with Borderlands nGameplay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-guide-enhance-windows-bluetooth-device-with-full-sound-features/"><u>Fix Guide: Enhance Windows Bluetooth Device with Full Sound Features</u></a></li>
<li><a href="https://vp-tips.techidaily.com/guia-completa-y-gratuita-descargando-audio-desde-videos-mp4-a-formato-mp3-con-calidad-superior-metodos-modernos/"><u>Guía Completa Y Gratuita: Descargando Audio Desde Videos MP4 a Formato MP3 Con Calidad Superior - Métodos Modernos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-add-trusted-sites-on-windows-11/"><u>How to Add Trusted Sites on Windows 11</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-12-to-other-iphone-14-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 12 To Other iPhone 14 devices? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-oppo-find-n3-flip-phone-password-without-factory-reset-by-drfone-android/"><u>How to Unlock Oppo Find N3 Flip Phone Password Without Factory Reset?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-unset-custom-search-rules-in-windows-11/"><u>How to Unset Custom Search Rules in Windows 11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/initially-yours-the-ultimate-gear-list-for-gopros-for-2024/"><u>Initially Yours The Ultimate Gear List for GoPros for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-package-accessibility-a-step-by-step-windows-solution/"><u>Mastering Package Accessibility: A Step-by-Step Windows Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-through-windows-setup-for-steam-deck/"><u>Navigate Through Windows Setup for Steam Deck</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-inactive-wsreset-troubleshooting-steps/"><u>Navigating Through Inactive WSReset Troubleshooting Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-based-thx-audio-glitches/"><u>Overcoming Windows-Based THX Audio Glitches</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/post-publish-editing-elevating-your-youtube-content/"><u>Post-Publish Editing Elevating Your YouTube Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventive-measures-against-windows-notepad-freezes/"><u>Preventive Measures Against Windows Notepad Freezes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proven-techniques-to-connect-airpods-with-windows/"><u>Proven Techniques to Connect AirPods with Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/retrogame-enhancement-via-retroarchs-advanced-shading-features/"><u>RetroGame Enhancement via RetroArch’s Advanced Shading Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionize-keyboard-use-redefine-functionality-via-fn-keys-on-windows-11/"><u>Revolutionize Keyboard Use: Redefine Functionality via FN Keys on Windows 11</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/sony-xbr65x850f-65-inch-4k-tv-quality-and-price-that-wont-break-the-bank/"><u>Sony XBR65X850F (65-Inch) 4K TV: Quality & Price That Won't Break The Bank</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-correcting-unreachable-windows-network/"><u>Steps for Correcting Unreachable Windows Network</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-eliminate-user-specific-ms-errors/"><u>Steps to Eliminate User-Specific MS Errors</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/the-budget-friendly-point-and-shoot-fz53-review/"><u>The Budget-Friendly Point & Shoot: FZ53 Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-covert-world-hiding-wi-fi-signals-in-windows/"><u>The Covert World: Hiding Wi-Fi Signals in Windows</u></a></li>
<li><a href="https://games-able.techidaily.com/the-ultimate-list-9-superior-emulators-for-steam-decks/"><u>The Ultimate List: 9 Superior Emulators for Steam Decks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-and-tricks-correcting-malfunctioned-read-aloud-feature-in-office-suite/"><u>Tips & Tricks: Correcting Malfunctioned Read Aloud Feature in Office Suite</u></a></li>
<li><a href="https://win-answers.techidaily.com/ultimate-guide-solve-the-league-of-legends-not-launching-problem/"><u>Ultimate Guide: Solve the 'League of Legends Not Launching' Problem</u></a></li>
</ul></div>




