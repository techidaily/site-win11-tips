---
title: Personalizing Failure Lockout Period on Sign In Errors
date: 2024-08-16T01:43:54.094Z
updated: 2024-08-17T01:43:54.094Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Personalizing Failure Lockout Period on Sign In Errors
excerpt: This Article Describes Personalizing Failure Lockout Period on Sign In Errors
keywords: Personalized Lockout Period,Custom Failure Lockout,Individual Sign-In Error,Tailored Access Denied,User Account Lockout,Error Handling Timeframe,Specific Login Delay
thumbnail: https://thmb.techidaily.com/d6f225de23330f252c6d5195ffc58e836dfeb5e08b530725208b4f5fec9ae8dd.JPG
---

## Personalizing Failure Lockout Period on Sign In Errors

 Windows has a policy setting that can lock someone out from signing in if they enter the wrong local account password too many times. The user is not allowed to sign in for a set number of minutes after being locked out, but you can change this lockout duration.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

## How to Change the Duration a User Is Locked Out of Their Account via Local Security Policy

 This method will work as long as the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press **Windows key + R** to open the **Run** dialogue.
2. Type “secpol.msc” into the text field and hit **Enter**.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, click on the **Account Lockout Policy** folder under **Account Policies**.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on **Account lockout duration**.  
![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  
![Choose how long a local account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-set-local-account-lockout-duration.jpg)

<!-- affiliate ads begin -->
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
3. This will pull up information, among other things, about how long this account lockout duration is currently set.
4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
## Find the Balance Between Security and Convenience

 Setting account lockout duration too high will cause inconvenience, but if you set it to zero, an administrator will have to be contacted each time a user locks themselves out. Find a balance between security and convenience when it comes to changing how long a user is locked out after a set number of failed login attempts.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-http.techidaily.com/new-in-2024-xsplit-vs-obs-battle-ideal-tools-for-livestreaming/"><u>[New] In 2024, XSplit Vs. OBS Battle  Ideal Tools for Livestreaming</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-master-the-art-of-sound-alteration-on-sony-games/"><u>[New] Master the Art of Sound Alteration on Sony Games</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-achieve-superior-mp4-output-from-instagram-videos-2-ways/"><u>[Updated] 2024 Approved  Achieve Superior MP4 Output From Instagram Videos 2 Ways</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-discovering-vr-identity-a-hands-on-approach-to-self-representation/"><u>[Updated] Discovering VR Identity - A Hands-On Approach to Self-Representation</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-escape-from-ennui-with-humor-top-20-funny-faces-in-social-media-jail/"><u>[Updated] Escape From Ennui with Humor  Top 20 Funny Faces in Social Media Jail</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-from-raw-to-ready-a-compreenass-guide-to-video-crop-on-instagram-for-2024/"><u>[Updated] From Raw to Ready  A Compreenas's Guide to Video Crop on Instagram for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-configuring-picture-in-picture-for-apple-browsers/"><u>[Updated] In 2024, Configuring Picture-in-Picture for Apple Browsers</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-elevating-your-content-game-with-these-top-20-tiktok-captions/"><u>[Updated] In 2024, Elevating Your Content Game with These Top 20 TikTok Captions</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-top-tier-seo-strategies-to-elevate-your-podcast-rankings/"><u>[Updated] Top-Tier SEO Strategies to Elevate Your Podcast Rankings</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-mastering-tempo-a-guide-to-instagram-story-adjustments/"><u>2024 Approved  Mastering Tempo  A Guide to Instagram Story Adjustments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-secrets-to-swiftly-concluding-a-troubled-update-process/"><u>5 Secrets to Swiftly Concluding a Troubled Update Process</u></a></li>
<li><a href="https://android-location-track.techidaily.com/5-ways-to-track-xiaomi-redmi-a2-without-app-drfone-by-drfone-virtual-android/"><u>5 Ways to Track Xiaomi Redmi A2 without App | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-smooth-operator-install-in-windows-realm/"><u>Achieve Smooth Operator Install in Windows Realm</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-lsassexe-component-not-found-error-in-windows/"><u>Addressing lsass.exe Component Not Found Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/becoming-a-storage-strategy-expert-with-windows-diskusage-commands-mastery/"><u>Becoming a Storage Strategy Expert with Windows' DiskUsage Commands Mastery</u></a></li>
<li><a href="https://win-able.techidaily.com/crusader-kings-ii-wont-start-troubleshooting-guide/"><u>Crusader Kings II Won't Start: Troubleshooting Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-computer-experience-running-task-manager-as-admin-on-win11/"><u>Elevate Your Computer Experience: Running Task Manager as Admin on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-compliance-with-insider-editions/"><u>Ensuring Compliance with Insider Editions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-msresourceappnametext-glitch-win11-style/"><u>Fixing 'MsResource:AppName/Text Glitch', Win11 Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-unsuccessful-onedrive-operations-in-windows-10-and-11/"><u>Fixing Unsuccessful OneDrive Operations in Windows 10 & 11</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/free-msnbc-live-online-stream-for-the-latest-shows-for-all-devices-for-2024/"><u>Free MSNBC Live Online Stream for the Latest Shows for All Devices for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-itel-p55-5g-s-lock-screen-pattern-pin-or-password-by-drfone-android-unlock-android-unlock/"><u>How to bypass Itel P55 5G’s lock screen pattern, PIN or password</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-a-non-responsive-synaptics-touchpad-scroll-wheel-under-windows-10/"><u>How to Fix a Non-Responsive Synaptics Touchpad Scroll Wheel Under Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-a-persistent-enter-network-credentials-message-on-windows/"><u>How to Fix a Persistent Enter Network Credentials Message on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-suppress-gaming-suggestions-in-windows-11-ui/"><u>How to Suppress Gaming Suggestions in Windows 11 UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-update-audio-drivers-on-windows/"><u>How to Update Audio Drivers on Windows</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-3-ways-of-how-to-get-someones-apple-id-off-iphone-se-without-password-by-drfone-ios/"><u>In 2024, 3 Ways of How to Get Someones Apple ID Off iPhone SE without Password</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-high-speed-replicas-best-racing-games/"><u>In 2024, High-Speed Replicas  Best Racing Games</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-reset-a-locked-nubia-z50-ultra-phone-by-drfone-android/"><u>In 2024, How to Reset a Locked Nubia Z50 Ultra Phone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-pokemon-go-error-12-failed-to-detect-location-on-xiaomi-redmi-note-12-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go Error 12 Failed to Detect Location On Xiaomi Redmi Note 12 5G? | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-samsung-galaxy-s21-fe-5g-2023frp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Samsung Galaxy S21 FE 5G (2023)FRP Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-swift-typing-techniques-with-powertoys/"><u>Master Swift Typing Techniques with PowerToys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-windows-landscape-incorporate-outlook-preview/"><u>Master the Windows Landscape: Incorporate Outlook Preview</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-cc-errors-on-windows-10-a-step-by-step-guide/"><u>Mastering CC Errors on Windows 10: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-windows-1011-eliminating-email-app-errors/"><u>Mending Windows 10/11: Eliminating Email App Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-print-control-in-windows-11-9-ways-short-version-max-48-chars/"><u>Navigating Print Control in Windows 11 (9 Ways) - Short Version (Max 48 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-11-with-ease-access-calculator/"><u>Navigating Windows 11 with Ease: Access Calculator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-0x80070570-error-in-windows-restoring-damaged-data/"><u>Overcoming 0X80070570 Error in Windows: Restoring Damaged Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-printer-connection-failsafes-in-windows/"><u>Overcoming Printer Connection Failsafes in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-speed-by-tweaking-msram/"><u>Regain Speed by Tweaking MSRam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-decades-old-windows-authentication-error/"><u>Reversing Decades-Old Windows Authentication Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safeguard-files-when-maximizing-space-in-windows/"><u>Safeguard Files When Maximizing Space in Windows</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/sdk-innovations-for-android-the-updated-rankings-of-facebook-video-downloading-tools/"><u>SDK Innovations for Android  The Updated Rankings of Facebook Video Downloading Tools</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/sizing-up-how-to-make-videos-work-in-instagram-bests/"><u>Sizing Up  How to Make Videos Work in Instagram Bests</u></a></li>
<li><a href="https://program-issues.techidaily.com/solution-fixing-your-steam-account-access-problems/"><u>Solution: Fixing Your Steam Account Access Problems</u></a></li>
<li><a href="https://win-answers.techidaily.com/step-by-step-solutions-getting-your-copy-of-the-witcher-n-wont-start/"><u>Step-by-Step Solutions: Getting Your Copy of The Witcher N Won't Start</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-tackle-windows-security-faults-effectively/"><u>Steps to Tackle Windows Security Faults Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-sharpen-your-windows-11-multi-tasking-skills/"><u>Strategies to Sharpen Your Windows 11 Multi-Tasking Skills</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-connectivity-issues-with-geforce-experience-software/"><u>Tackling Connectivity Issues with GeForce Experience Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-dism-error-0x800f082f-on-windows/"><u>Tackling DISM Error 0X800F082F on Windows</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/the-path-to-proficiency-mastering-gif-sharing-on-snapchat/"><u>The Path to Proficiency  Mastering Gif Sharing on Snapchat</u></a></li>
<li><a href="https://games-able.techidaily.com/top-level-165hz-visuals-for-gamers/"><u>Top-Level 165Hz Visuals for Gamers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-resolving-ubisoft-launcher-not-found-issue/"><u>Troubleshooting: Resolving Ubisoft Launcher Not Found Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unpacking-and-solving-the-mystery-of-error-0x8007251d/"><u>Unpacking and Solving the Mystery of Error 0X8007251d</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unsupported-hardware-to-next-gen-os-in-eight-steps/"><u>Unsupported Hardware to Next-Gen OS in Eight Steps</u></a></li>
</ul></div>
