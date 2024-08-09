---
title: Addressing Windows Hello Compatible Scanner Glitch
date: 2024-08-08T10:57:14.986Z
updated: 2024-08-09T10:57:14.986Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Windows Hello Compatible Scanner Glitch
excerpt: This Article Describes Addressing Windows Hello Compatible Scanner Glitch
keywords: WinHelloScanGlitch,ScannerWindowsHello,HappyHelloScanner,GlitchInWinHello,FixWindowsHappy,WindowsHelloError,ScannerCompatibility
thumbnail: https://thmb.techidaily.com/b46dbabb50d5277c1ad28a5993cc958234753eefedba62d12174cf3ff84234d4.jpg
---

## Addressing Windows Hello Compatible Scanner Glitch

 If you receive an error message that says, "we couldn't find a fingerprint scanner compatible with Windows Hello Fingerprint" when trying to set up Windows Hello fingerprint login, then your device either doesn't support fingerprint recognition, the fingerprint scanner (or reader) isn't working correctly, or Windows is unable to detect it.

 Windows may not detect the fingerprint scanner for several reasons: the fingerprint reader may have malfunctioned, the biometric drivers could be outdated or corrupted, or biometric recognition could be disabled in the BIOS. If you're tired of dealing with this problem, try these solutions.

## 1\. Ensure Your Device Supports Fingerprint Recognition

![blue graphic of digital fingerprint scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/blue-finger-scan.jpg)

 The Windows Hello fingerprint recognition feature requires your device to have a fingerprint reader. If you encounter the error "we could not find a fingerprint scanner compatible with Windows Hello Fingerprint" when setting up fingerprint recognition for the first time, make sure your device is equipped with a fingerprint reader compatible with Windows Hello.

 Usually, it is located near (or on) the power button or in the empty space above or below the keyboard. Look around and see if you can find a fingerprint reader. If you fail to find it, check your device's specifications on the manufacturer's website to see if it has a fingerprint scanner.

 If your device does not have a fingerprint reader, you cannot enable biometric authentication on it. However, if your device has a scanner, and you've used it many times before, ensure that it is working correctly.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Make Sure the Fingerprint Reader Is Working Properly

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
![security fingerprint on keyboard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/data-1590455_1920-1.jpg)

 If your device has a fingerprint sensor, but Windows is unable to detect it, ensure the sensor hasn't gone bad. To test the fingerprint reader, sign in to another app where you've set up biometric login. If that app fails to accept biometric verification, use a dry cloth to wipe the dust off your fingerprint scanner.

 After that, try scanning your finger again. If the app fails to recognize the fingerprint scan even after thoroughly cleaning it, there is probably an issue with the scanner. So, have your device inspected by a technician. However, if the scanner works fine on other apps but not when you set up Windows Hello fingerprint login, then apply the remaining fixes.

## 3\. Roll Back the Driver or the Latest Windows Update

 Have you encountered the error under discussion after updating the biometric driver or installing a Windows update recently? If this is the case, you should roll back these updates. Don't know how to do that? Our guide on [how to roll back a driver update on Windows](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) describes the process. If you want to roll back a Windows update, then you need to [uninstall the most recent Windows Update](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) .

 Once you've undone both driver and Windows updates, try setting up Windows Hello biometric login again. If you continue to experience the same problem after rolling back these updates, it suggests that undoing these updates hasn't made a difference. In that case, you should reinstall the drivers and Windows update.

## 4\. Ensure the Windows Biometric Service Is Configured Properly

 When the Windows biometric service is disabled, Windows Hello fingerprint recognition won't work. To ensure this service is enabled and configured correctly, follow these steps:

1. Type**"Services"** in Windows Search and open the**Services** app.  
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Open Services App From Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/1-open-services-app-from-windows-search.jpg)
2. Locate**Windows Biometric Service** .  
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Locate Windows Biometric Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/2-locate-windows-biometric-service-in-windows-services-app.jpg)
3. If you see**"Running"** next to this service in the**Status** column, it's already running. If not, it's disabled.
4. In either case, right-click the service and select**Properties** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
![Go to Properties of Windows Biometric Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3-go-to-properties-of-windows-biometric-service-in-windows-services-app.jpg)
5. Click on the dropdown menu next to**Startup type** and select**Automatic** .  
![Select Automatic From the Startup Type Dropdown Menu in the Properties Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/4-select-automatic-from-the-startup-type-dropdown-menu-in-the-properties-window.jpg)
6. If it's already selected, click the**Stop** button to stop the service and then click**Start** again to restart it.  
<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Click Start Button to Restart the Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/5-click-start-button-to-restart-the-service-in-windows-services-app.jpg)

## 5\. Update or Reinstall the Biometric Drivers

 If the biometric service is already enabled, yet the fingerprint recognition feature isn't working, the biometric drivers could be outdated or corrupt. To ensure that isn't the case, update the biometric device drivers. To do so, follow these steps:

1. Type**"Device Manager"** in Windows Search and open the**Device Manager** app.
2. Expand the**Biometric devices** category.
3. Right-click on your fingerprint scanner device and select**Update driver** .  
<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Update the Fingerprint Scanner Device in Windows Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/6-update-the-fingerprint-scanner-device-in-windows-device-manager.jpg)
4. Then, click on**Search automatically for drivers** .

 If updating the drivers does not fix the problem, right-click the biometric device again and select**Uninstall device** . After uninstalling the drivers, reboot your device, and Windows will automatically install them again. If you prefer, you can also download the relevant drivers from the manufacturer's website and install them manually.

## 6\. Disable Fast Startup

 According to some users on a [Microsoft community thread](https://answers.microsoft.com/en-us/windows/forum/all/fingerprint-reader-not-working/95cc0aef-2822-4b51-9f77-8697e6ace897) , disabling the Fast Startup feature has solved fingerprint recognition issues on their devices. Although Fast Startup speeds up your device's boot process, turning it on is known to cause unforeseen problems.

 So, if you also keep this feature enabled on your device, disable it to see if it makes a difference. Don't know how to do that? Refer to our guide on [enabling or disabling Fast Startup on Windows 11](https://www.makeuseof.com/windows-11-turn-on-or-off-fast-startup/) .

## 7\. Ensure the Biometric Reader Isn't Disabled in BIOS

 Some laptops allow users to disable the fingerprint reader in BIOS. If you're setting up a fingerprint login for the first time and getting the error, ensure the fingerprint scanner isn't disabled in BIOS. Accessing BIOS and navigating to the option to enable or disable the biometric device varies between manufacturers.

 If you need guidance on accessing the BIOS and enabling the biometric device, visit your laptop manufacturer's website.

## 8\. When Nothing Else Works…

 If nothing else works, run the Hardware and Devices troubleshooter, enable biometrics in the Local Group Policy Editor, and check for account-specific issues. If these steps fail to resolve the issue, perform a system restore as a last resort. Our guide on [fixing Windows Hello fingerprint recognition](https://www.makeuseof.com/windows-hello-fingerprint-not-working/) explains how to make the above-mentioned changes.

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get Rid of Annoying Fingerprint Recognition Errors

 If you encounter an error when setting up Windows Hello fingerprint recognition, it does not mean the feature can't be used. If your device supports biometric authentication, the above fixes will help you resolve the annoying error.

 If you are setting up a fingerprint login for the first time, make sure you do it correctly. Otherwise, you'll be constantly annoyed by the bothersome errors when using this fantastic feature.


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
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-step-by-step-on-vlc-screen-recording/"><u>[New] 2024 Approved  Step-by-Step on VLC Screen Recording</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-direct-download-of-youtube-videos/"><u>[Updated] 2024 Approved  Direct Download of YouTube Videos</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-the-ultimate-guide-to-improving-chromebook-tone-with-top-voice-extensions/"><u>[Updated] The Ultimate Guide to Improving Chromebook Tone with Top Voice Extensions</u></a></li>
<li><a href="https://android-location.techidaily.com/10-fake-gps-location-apps-on-android-of-your-samsung-galaxy-f54-5g-drfone-by-drfone-virtual/"><u>10 Fake GPS Location Apps on Android Of your Samsung Galaxy F54 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-secrets-to-swiftly-concluding-a-troubled-update-process/"><u>5 Secrets to Swiftly Concluding a Troubled Update Process</u></a></li>
<li><a href="https://extra-resources.techidaily.com/a-top-10-curated-list-of-superior-vector-portals/"><u>A Top 10 Curated List of Superior Vector Portals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-smooth-operator-install-in-windows-realm/"><u>Achieve Smooth Operator Install in Windows Realm</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/budget-friendly-interactive-face-to-face-games-for-2024/"><u>Budget-Friendly Interactive Face-to-Face Games for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/chromatic-choices-discover-the-best-5-screens-today-for-2024/"><u>Chromatic Choices  Discover the Best 5 Screens Today for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/crafting-content-conversations-connecting-with-subscribers-for-2024/"><u>Crafting Content Conversations  Connecting With Subscribers for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/easy-instructions-to-access-and-accept-group-albums-on-apple-devices/"><u>Easy Instructions to Access and Accept Group Albums on Apple Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-msresourceappnametext-glitch-win11-style/"><u>Fixing 'MsResource:AppName/Text Glitch', Win11 Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-unsuccessful-onedrive-operations-in-windows-10-and-11/"><u>Fixing Unsuccessful OneDrive Operations in Windows 10 & 11</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-oneplus-12r-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an OnePlus 12R Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-install-magic-mouse-controls-on-a-windows-system-seamlessly/"><u>How to Install Magic Mouse Controls on a Windows System Seamlessly</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-remove-flashlight-from-iphone-se-lock-screen-drfone-by-drfone-ios/"><u>How To Remove Flashlight From iPhone SE Lock Screen | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-suppress-gaming-suggestions-in-windows-11-ui/"><u>How to Suppress Gaming Suggestions in Windows 11 UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-update-audio-drivers-on-windows/"><u>How to Update Audio Drivers on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-swift-typing-techniques-with-powertoys/"><u>Master Swift Typing Techniques with PowerToys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-windows-landscape-incorporate-outlook-preview/"><u>Master the Windows Landscape: Incorporate Outlook Preview</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-windows-1011-eliminating-email-app-errors/"><u>Mending Windows 10/11: Eliminating Email App Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-print-control-in-windows-11-9-ways-short-version-max-48-chars/"><u>Navigating Print Control in Windows 11 (9 Ways) - Short Version (Max 48 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-11-with-ease-access-calculator/"><u>Navigating Windows 11 with Ease: Access Calculator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-0x80070570-error-in-windows-restoring-damaged-data/"><u>Overcoming 0X80070570 Error in Windows: Restoring Damaged Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-updater-problem-code-0x8019/"><u>Overcoming Updater Problem: Code 0X8019</u></a></li>
<li><a href="https://extra-support.techidaily.com/rapid-photo-reader-for-windows-users-for-2024/"><u>Rapid Photo Reader for Windows Users for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-speed-by-tweaking-msram/"><u>Regain Speed by Tweaking MSRam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/repairing-slow-or-non-responsive-windows-download-area/"><u>Repairing Slow or Non-Responsive Windows Download Area</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safeguard-files-when-maximizing-space-in-windows/"><u>Safeguard Files When Maximizing Space in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-sharpen-your-windows-11-multi-tasking-skills/"><u>Strategies to Sharpen Your Windows 11 Multi-Tasking Skills</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solution-to-windows-os-not-found-error/"><u>Swift Solution to Windows OS 'Not Found' Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-dism-error-0x800f082f-on-windows/"><u>Tackling DISM Error 0X800F082F on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-resolving-ubisoft-launcher-not-found-issue/"><u>Troubleshooting: Resolving Ubisoft Launcher Not Found Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unsupported-hardware-to-next-gen-os-in-eight-steps/"><u>Unsupported Hardware to Next-Gen OS in Eight Steps</u></a></li>
</ul></div>
