---
title: How to Turn Your Voice to Text in Real Time With Whisper Desktop
date: 2024-08-16T02:28:35.710Z
updated: 2024-08-17T02:28:35.710Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Turn Your Voice to Text in Real Time With Whisper Desktop
excerpt: This Article Describes How to Turn Your Voice to Text in Real Time With Whisper Desktop
keywords: Real-Time Speech-to-Text,Voice-to-Text Conversion,Live Transcription Software,Immediate Text Output,Whisper Desktop Features,Audio to Written Transcripts,Instant Text From Audio
thumbnail: https://thmb.techidaily.com/9d3732c41a53a8a22c767ec42385e845ec206bbdbcdafbf7af2a45ba4a50f286.jpg
---

## How to Turn Your Voice to Text in Real Time With Whisper Desktop

 The very same people behind ChatGPT have created another AI-based tool you can use today to boost your productivity. We're referring to Whisper, a voice-to-text solution that eclipsed all similar solutions that came before it.

 You can use Whisper in your programs or the command line. And yet, that defeats its very purpose: typing without a keyboard. If you need to type to use it, why use it to avoid typing? Thankfully, you can now use Whisper through a desktop GUI. Even better, it can also transcribe your voice almost in real time. Let's see how you can type with your voice using Whisper Desktop.

## What Is OpenAI's Whisper?

 OpenAI's Whisper is an Automatic Speech Recognition system (ASR for short) or, to put it simply, is a solution for converting spoken language into text.

 However, unlike older dictation and transcription systems, Whisper is an AI solution trained on over 680,000 hours of speech in various languages. Whisper offers unparalleled accuracy and, quite impressively, not only is it multilingual, but it can also translate between languages.

 More importantly, it's free and available as open source. Thanks to that, many developers have forked its code into their own projects or created apps that rely on it, like Whisper Desktop.

 If you'd prefer the "vanilla" version of Whisper and the versatility of the terminal instead of clunky GUIs, check our article on [how to turn your voice into text with OpenAI's Whisper for Windows](https://www.makeuseof.com/dictate-documents-openai-whisper/).

## Are Whisper and Whisper Desktop the Same?

 Despite its official-sounding name, Whisper Desktop is a third-party GUI for Whisper, made for everyone who'd prefer to click buttons instead of typing commands.

 Whisper Desktop is a standalone solution that doesn't rely on an existing Whisper installation. As a bonus, it uses an alternative, optimized version of Whisper, so it should perform better than the standalone version.

 You're on the other end of the spectrum, and instead of seeking an easier way to use Whisper than the terminal you're seeking ways to implement it in your own solutions? Rejoice, for [OpenAI has opened access to ChatGPT and Whisper APIs](https://www.makeuseof.com/what-chatgpt-and-whisper-apis-means-for-businesses/).

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Download & Install Whisper Desktop

 Although Whisper Desktop is easier to use than the standalone Whisper, its installation is more convoluted than repeatedly clicking Next in a wizard.

1. Visit [Whisper Desktop's official Github page](https://github.com/Const-me/Whisper). Look on the right, and click on the latest version under **Releases**.  
![Whisper Desktop Github Releases Link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/whisper-desktop-github-releases-link.jpg)
2. Under **Assets**, click **WhisperDesktop.zip** and download it to your PC.  
![Whisper Desktop Github Download Link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/whisper-desktop-github-download-link.jpg)
3. Extract the downloaded archive to a folder and use your file manager to visit it. Inside you will find the Whisper Desktop application. Double-click on it to run it.  
![Whisper Desktop App in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/whisper-desktop-app-in-file-explorer.jpg)
4. You also need a Whisper language model in **GCML** binary format. Whisper Desktop will provide you with two links for acquiring one. Skip the second link for generating your own model since it's a more complicated process. Click on **Hugging Face** to open that page in your default browser, from where you can download a ready-to-use file.  
![Whisper Desktop Language Model Links](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/whisper-desktop-language-model-links.jpg)
5. The version of Whisper Desktop we used while writing this article provided a link to an obsolete repository at Hugging Face. If you meet the same problem, notice a link to a **new location**. Click on it to visit the new repository.  
![Hugging Face Whisper Models New Location](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hugging-face-whisper-models-new-location.jpg)
6. Click on the link that will take you to the available **models**.  
![Hugging Face Available Models Link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hugging-face-available-models-link.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
7. From that list, click on either the **ggml-medium.bin** or **ggml-medium.en.bin**, depending on if you want multilingual or English-only support in Whisper.  
![Hugging Face Whisper Medium Model Link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hugging-face-whisper-medium-model-link.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Finally, you should have reached your destination. Notice the line stating that this file is stored with Git LFS and is too big to display, but you can still download it. Click on **download** to do precisely that.  
![Hugging Face Whisper Medium Model Download Link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hugging-face-whisper-medium-model-download-link.jpg)
9. When the file completes downloading, use your favorite file manager (File Explorer will do) to move the downloaded language model file into the same folder as Whisper Desktop.  
![Whisper Medium Model Placed in Whisper Desktop Folder in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/whisper-medium-model-placed-in-whisper-desktop-folder-in-file-explorer.jpg)
<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Transcribing With Whisper Desktop

 Transcribing with Whisper Desktop is easy, but you may still need one or two clicks to use the app.

 Rerun Whisper Desktop. Does it (still) miss the correct path to your downloaded language model? Click on the **button with the three dots** on the right of the field and manually select the file you downloaded from Hugging Face.

 From this spot, you can also use the drop-down menu next to **Model Implementation** to choose if you want to run Whisper on your GPU (**GPU**), on both the CPU and GPU (**Hybrid**), or only on the CPU (**Reference**).

![Whisper Desktop Selecting Model Implementation](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/whisper-desktop-selecting-model-implementation.jpg)

 The **Advanced** button leads to more options that affect how Whisper will run on your hardware. However, since the button clearly states they are advanced, we suggest you only tweak them if you are troubleshooting or know what you are doing. Setting the wrong options values here can impose a performance penalty or render the app unusable.

 Click on OK to move to the app's main interface.

![Whisper Desktop Advanced Options Changing Graphics Adapter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/whisper-desktop-advanced-options-changing-graphics-adapter.jpg)

 If you already have a recording of your voice you want to turn into written text, click on **Transcribe File** and select it. Still, we will use Whisper Desktop for live transcription for this article.

 The options offered are straightforward. You can select the **language** Whisper will use, choose if you want to **translate** between languages and enable the app's **Debug Console**.

 Most English-speaking users can safely skip those options and only ensure the correct audio input is selected from the pull-down menu next to **Capture Device**.

 Make sure **Save to text file** and **Append to that file** are enabled to have Whisper Desktop save its output to a file without overwriting its content. Use the **button with the three dots** on the right of the file's path field to define said text file.

![Whisper Desktop Saving And Appending to Text File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/whisper-desktop-saving-and-appending-to-text-file.jpg)
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->

 Click on **Capture** to begin transcribing your speech to text.

 Whisper Desktop will show you three indicators for when it detects voice activity, when it's actively transcribing, and when the process is stalled.

 You can keep talking for as long as you like, and you should occasionally see the two first indicators flashing while the app turns your voice into text. Click **Stop** when done.

![Whisper Desktop Active Voice Transcribing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/whisper-desktop-active-voice-transcribing.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->

 The text file you selected should open in your default text editor, containing in written form everything you said until you clicked **Stop**.

![Transcribed Text With Whisper Desktop in Typora](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/transcribed-text-with-whisper-desktop-in-typora.jpg)

 We should note that you can also do the opposite of what we saw here: convert any text to speech. This way you can listen to anything as if it were a podcast instead of tiring your eyes squinting at screens. For more info on that, check our article on [some of the best free online tools to download text-to-speech as MP3 audio](https://www.makeuseof.com/tag/download-text-to-speech-as-mp3-audio/).

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Whisper Desktop Voice-Typing Tips

 Although Whisper Desktop can be a lifesaver, enabling you to write with your voice much quicker than you could type, it's far from perfect.

 During our testing, we found that it may occasionally stutter, skip some words, fail to transcribe until you manually stop and restart the process, or get stuck in a loop and keep re-transcribing the same phrase repeatedly.

 We believe those are temporary glitches that will be fixed since the standalone Whisper doesn't exhibit the same issues.

 Apart from those minor bumps, turning your voice to text should be effortless with Whisper Desktop. Still, during our tests, we found that it can perform even better if...

1. Instead of uttering only two or three words and then pausing, Whisper can understand you better if you go on longer. Try to at least give it an entire sentence at a time.
2. For the same reason, avoid repeatedly starting and stopping the transcription process.
3. Whenever you realize you made a mistake, ignore it and keep going. Loading and unloading the language model seems to be the most time-consuming part of the process with the current state of Whisper and our available hardware. So, it's quicker to keep talking and then edit out your mistakes afterward.
4. As with the standalone version of Whisper, it's best to use the optimal language model for your available hardware. You can use up to the **medium** model if your GPU has 8GB of VRAM. For less VRAM, go for the smaller models. Only choose the slightly more accurate but also much more demanding **large** model if you use a GPU with 16GB of VRAM or more.
5. Remember that the larger the language model, the slower the transcription process. Don't go for a model larger than needed. You'll probably find Whisper Desktop can already "understand you" most of the time with the medium or smaller models, with only one or two errors per paragraph.

<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Are You Still Typing? Use Your Voice With Whisper

 Despite requiring some time to set up, as you will see when you try it, Whisper Desktop performs much better than most alternatives, with much higher accuracy and better speed.

 After you start using it to type with your voice, your keyboard may look like a relic from ancient times long gone.

 You can use Whisper in your programs or the command line. And yet, that defeats its very purpose: typing without a keyboard. If you need to type to use it, why use it to avoid typing? Thankfully, you can now use Whisper through a desktop GUI. Even better, it can also transcribe your voice almost in real time. Let's see how you can type with your voice using Whisper Desktop.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/new-tech-gear-review-vr-treadmills-showdown-for-2024/"><u>[New] Tech Gear Review  VR Treadmills Showdown for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-uncovering-the-best-apps-to-transform-your-speech/"><u>[Updated] Uncovering the Best Apps to Transform Your Speech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/15-secrets-to-discovering-window-settings/"><u>15 Secrets to Discovering Window Settings</u></a></li>
<li><a href="https://blog-min.techidaily.com/2-ways-to-transfer-text-messages-from-google-pixel-8-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>2 Ways to Transfer Text Messages from Google Pixel 8 to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-savvy-sound-engineers-10-best-free-lut-picks/"><u>2024 Approved  Savvy Sound Engineers' 10 Best FREE LUT Picks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerated-unzipping-of-multiple-files-using-windows-tools/"><u>Accelerated Unzipping of Multiple Files Using Windows Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/approaches-to-fix-java-non-installation-in-windows/"><u>Approaches to Fix Java Non-Installation in Windows</u></a></li>
<li><a href="https://extra-information.techidaily.com/comprehensive-guide-to-enhancing-footage-in-gopro-studio/"><u>Comprehensive Guide to Enhancing Footage in GoPro Studio</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/elevate-your-communication-master-skype-calls-recording-for-2024/"><u>Elevate Your Communication  Master Skype Calls Recording for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/essential-guide-to-integrating-video-in-curricular-design/"><u>Essential Guide to Integrating Video in Curricular Design</u></a></li>
<li><a href="https://extra-resources.techidaily.com/essential-windows-10-hacks-and-insights/"><u>Essential WINDOWS 10 Hacks & Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-automate-microsoft-to-do-with-ifttt/"><u>How to Automate Microsoft To Do With IFTTT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-control-windows-11-shutdown-with-open-filestasks/"><u>How to Control Windows 11 Shutdown with Open Files/Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-windows-0x8007007e-error-code/"><u>How to Fix the Windows 0X8007007E Error Code</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-windows-upgrade-failures-and-errors/"><u>How to Resolve Windows Upgrade Failures and Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-setup-virtualboxs-security-features-secure-boot-and-tpm/"><u>How to Setup VirtualBox's Security Features: Secure Boot & TPM</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-realme-narzo-n55-bootloader-easily-by-drfone-android/"><u>How to Unlock Realme Narzo N55 Bootloader Easily</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-3-ways-to-fake-gps-without-root-on-honor-x50-gt-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Fake GPS Without Root On Honor X50 GT | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-all-must-knows-to-use-fake-gps-go-location-spoofer-on-apple-iphone-12-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, All Must-Knows to Use Fake GPS GO Location Spoofer On Apple iPhone 12 Pro | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-itel-p40-phone-without-password-by-drfone-android/"><u>In 2024, How To Unlock Itel P40 Phone Without Password?</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-ultimate-guide-twitter-video-enhancers/"><u>In 2024, Ultimate Guide  Twitter Video Enhancers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/introducing-automatic-system-updates-notice-to-windows-11-ui/"><u>Introducing Automatic System Updates Notice to Windows 11 UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-auto-lock-and-screensaver-configurations/"><u>Mastering Auto-Lock & Screensaver Configurations</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-your-windows-11-top-20-optimizations-guide/"><u>Mastering Your Windows 11: Top 20 Optimizations Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-resolve-old-password-needed-alert/"><u>Quick Guide to Resolve Old Password Needed Alert</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reconnecting-to-spotify-fixing-windows-11-errors/"><u>Reconnecting to Spotify: Fixing Windows 11 Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-windows-terminal-the-unshackled-experience/"><u>Restoring Windows Terminal: The Unshackled Experience</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/simple-steps-for-linking-a-ps4-gamepad-to-console/"><u>Simple Steps for Linking a PS4 Gamepad to Console</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snipgear-gone-wrong-nine-effective-tips-to-get-it-running-again/"><u>SnipGear Gone Wrong? Nine Effective Tips to Get It Running Again</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-problems-active-status-of-your-win11-license/"><u>Solving Problems: Active Status of Your Win11 License</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-adjustments-for-enhanced-windows-bar/"><u>Step-by-Step Adjustments for Enhanced Windows Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-unregistered-package-error-in-win11-images/"><u>Steps to Resolve Unregistered Package Error in Win11 Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-secure-command-line-user-permissions-on-pc/"><u>Steps to Secure Command Line User Permissions on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-unintentional-hotkey-engagements-on-pc/"><u>Stop Unintentional Hotkey Engagements on PC</u></a></li>
<li><a href="https://win-amazing.techidaily.com/streamline-your-sounds-nahimics-latest-drivers-installed-in-a-flash/"><u>Streamline Your Sounds: Nahimic's Latest Drivers Installed in a Flash</u></a></li>
<li><a href="https://extra-tips.techidaily.com/streamline-your-vfx-creation-with-story-remix-and-windows-10-photos/"><u>Streamline Your VFX Creation with Story Remix and Windows 10 Photos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-tasks-updating-window-11s-context-menu/"><u>Streamlining Tasks: Updating Window 11'S Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-user-support-4-new-windows-features/"><u>Transforming User Support: 4 New Windows Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-for-windows-1011-search-that-fails-to-display-output/"><u>Troubleshooting for Windows 10/11 Search that Fails to Display Output</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-operation-failed-0x0000011b-errors/"><u>Troubleshooting Operation Failed: 0X0000011B Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-11-resolving-webcam-error-code-a00f4289/"><u>Troubleshooting Windows 11: Resolving Webcam Error Code A00F4289</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-aggregatorhostexe-windows-functionality-and-safety-concerns/"><u>Understanding AggregatorHost.exe: Windows' Functionality & Safety Concerns</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-fixing-outlook-problems-on-pcs/"><u>Understanding and Fixing Outlook Problems on PCs</u></a></li>
<li><a href="https://sound-issues.techidaily.com/unlock-your-windows-scanner-a-practical-approach/"><u>Unlock Your Windows Scanner: A Practical Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-secrets-of-microsofts-copilot-key-for-windows-11-users/"><u>Unveiling the Secrets of Microsoft's Copilot Key for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/using-dialer-in-win-11/"><u>Using Dialer in Win 11</u></a></li>
</ul></div>
