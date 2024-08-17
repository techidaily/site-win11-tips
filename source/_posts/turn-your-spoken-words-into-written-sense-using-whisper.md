---
title: Turn Your Spoken Words Into Written Sense Using Whisper
date: 2024-08-16T01:45:15.113Z
updated: 2024-08-17T01:45:15.113Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Turn Your Spoken Words Into Written Sense Using Whisper
excerpt: This Article Describes Turn Your Spoken Words Into Written Sense Using Whisper
keywords: Speak to Write Trick,Convert Voice Writing,Audio-To-Text Conversion,Whisper to Text Method,Spoken Words Transform,Written Sense From Speech,Silent Talking Into Words
thumbnail: https://thmb.techidaily.com/be861d402be1baaf3140ac6faae85bc70a45ab620b0dde812294a010c625a831.png
---

## Turn Your Spoken Words Into Written Sense Using Whisper

 OpenAI's Whisper is a new AI-powered solution that can turn your voice into text. Best of all, it comes at zero cost.

 However, there's a catch: it's more challenging to install and use than your average Windows utility. Especially if you want to use your Nvidia GPU's Tensor Cores to give it a nice boost.

 Don't fret, though. That's why we're here! Read on to find out how to install and use it, but also, if you own one, to have Whisper take advantage of your Nvidia GPU.

## What Is OpenAI's Whisper?

 ChatGPT is all the rage nowadays, and we already saw [how you can use ChatGPT by OpenAI](https://www.makeuseof.com/how-to-use-chatgpt-by-openai/) . And yet, it's not the only interesting project by OpenAI.

 Powered by deep learning and neural networks, Whisper is a natural language processing system that can "understand" speech and transcribe it into text. But it's also its own thing, sitting at a spot right among all similar solutions:

* Whisper is an AI solution "trained" on natural language. So, it's better at understanding "normal" human speech than older solutions.
* Whisper doesn't come with an interface, nor can it record audio. It can only take existing audio files and output text files.
* Since it's good at "making sense of language", Whisper also has the superpower of automatic translation in a single step.
* Whisper is not an online service and can work entirely offline.
* If you have a relatively modern Nvidia GPU (GTX970 or newer), Whisper can run in "hardware accelerated mode" to boost its speed.
* There's no requirement to register, purchase a license, or buy a subscription.

## Why Are AMD GPUs Not Supported?

 For GPUs to be useful for more than graphics, they'd have to act as fully programmable processors. That's why Nvidia created CUDA, officially deemed "a parallel computing platform and programming model". To learn more about CUDA and related hardware ("CUDA cores"), read our article on [what are CUDA cores and how they improve PC gaming](https://www.makeuseof.com/tag/what-are-cuda-cores-pc-gaming/) .

 CUDA is proprietary Nvidia technology, only compatible with Nvidia GPUs. The closest alternatives for AMD's hardware are OpenCL and Radeon Compute Platform. To learn more about how each company's solutions compare, check our article on [AMD Compute Units vs. Nvidia CUDA Cores](https://www.makeuseof.com/compute-units-vs-cuda-cores-whats-the-difference/) .

 Compared to the alternatives, CUDA is considered more mature, performant, and easier to use. Thus, most developers only target CUDA, which, in turn, means that their software only takes advantage of the hardware features on Nvidia GPUs. And that includes Whisper.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Download and Install Whisper

 Unfortunately, Whisper is not a standalone app you can download, install, and run. It relies on other software, which must also be installed.

 For Windows, to keep this guide simple, we'll use Chocolatey extensively for installing most of the necessary software parts. Check our guide on [the quickest way to install Windows software](https://www.makeuseof.com/tag/quickest-way-install-windows-software-command-prompt/) for more info on Chocolatey.

 For Linux and Macs, the installation process (excluding the Windows path variable, and easy-to-use batch files we'll create) should be similar.

1. To install and use Whisper, you must have**Python** and its**PIP** tool installed and added to the Windows "Path" variable. For info on that, check our article on [how to install Python PIP on Windows, Mac, and Linux](https://www.makeuseof.com/tag/install-pip-for-python/) .
2. Install**FFMPEG** through Chocolatey with this command:  
`choco install ffmpeg`  
 Also, install its Python version with:  
`pip3 install python-ffmpeg`  
![pip install python ffmpeg](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/pip-install-python-ffmpeg.jpg)
<!-- affiliate ads begin -->

<!-- affiliate ads end -->
3. Finally, install Whisper from its Github page with:  
`pip3 install git+https://github.com/openai/whisper.git`

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Getting Whisper's CUDA-Enabled Version

 Although Whisper doesn't use Nvidia GPUs, the**torch** package it relies on offers a CUDA-accelerated version. Using this instead of the "plain" version can help Whisper complete its transcriptions much faster with the help of your Nvidia GPU.

To have Whisper use the CUDA cores of your Nvidia GPU:

1. If you already have the "vanilla" version of torch installed, uninstall and purge remnants of it with:  
`pip3 uninstall torch`  
 Once it's done, follow it up with:  
`pip cache purge`
2. Install torch's CUDA-enabled version with:  
`pip3 install torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/cu117`  
![pip3 install torch torchvision torchaudio](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/pip3-install-torch-torchvision-torchaudio.jpg)
3. To check if Whisper can use your Nvidia GPU, use:  
`whisper --help | findstr -i pytorch`  
 You should see**(default: cuda)** instead of**(default: cpu)** .

## What to Do if Torch Fails to Install

 If you encounter the "no version found" errorwhile installing torch, you may need to install an older version of Python parallel to your current one.

Use this command to do that:

`choco install python --version OLDER_VERSION --side-by-side`

Replace "OLDER\_VERSION" with a version, like 3.10.

![choco install python alternate version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/choco-install-python-alternate-version.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->

 Then, use the path of the secondary version for all "generic" Whisper commands (e.g., "c:\\Python310\\Scripts\\pip.exe" rather than just "pip").

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Record Your Voice

 You can use any sound-recording app to turn your voice into a WAV or MP3 file. Windows includes such an app—for more info on that, see [how to use the Windows 10 Voice Recorder app](https://www.makeuseof.com/how-to-use-the-windows-10-voice-recorder-app/) .

 For a more full-featured option, try**Audacity** . Learn how to do it with our guide on [how to use Audacity to record audio on Windows and Mac](https://www.makeuseof.com/how-to-use-audacity-to-record-audio/) .

![Recording voice with Audacity](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/recording-voice-with-audacity.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
## How to Start Transcribing With Whisper

 Although Whisper doesn't come with a user-friendly GUI, its use is ultra-simple.

 Let's say we have the file**LatestNote.mp3** which contains speech in Greek, in folder**c:\\MyAudioFiles** , and want to translate it to English and transcribe it into a text file.

1. We begin by running**Command Prompt** or**PowerShell** .
2. We "change directory" where the audio file is stored with this command:  
`cd C:\MyAudioFiles`
3. We unleash Whisper on the file with:  
`whisper --model base --language gr --task translate LatestNote.mp3`  
![Whisper translate gr](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/whisper-translate-gr.jpg)

 Once processed, the text file (named "LatestNote.mp3.txt") will appear in the same folder. Open it in a text editor like**Notepad** to view the translated text.

 We used a translation example because English transcription is even more straightforward: you only have to "lose" the "--language" and "-task" flags. Thus, for plain transcription, the above command would be:

`whisper --model base LatestNote.mp3`

 The "model" flag is required because Whisper uses one out of various options. Let's expand on them to help you choose the best for your needs.

### Which Model to Choose?

 Whisper offers various language models. The larger the model, the more improved its accuracy, but also the higher its hardware requirements. They are:

1. Tiny.
2. Base.
3. Small.
4. Medium.
5. Large.

 Most native English speakers should be fine with the**tiny** or**base** models. Non-native English speakers may see better results with larger models, like**small** and**medium** .

 Note, though, that the medium and large models require over 8GBs of VRAM (that is, "your GPU's memory").

![whisper model small](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/whisper-model-small.jpg)

 To select one of them, specify the model after the "--model" switch in the command:

`whisper --model tiny/small/medium/large [file]`

For example:

`whisper --model small My_Voice_Note.mp3`

## How to Streamline Your Transcription

 Having to type the whole Whisper command every time you want to transcribe some audio can quickly get boring. Let's make a globally accessible batch file to streamline the process.

1. Run**Windows Explorer** and visit your C: drive.
2. Create a folder for your scripts, and copy its path to the Clipboard.
3. In the Windows Start menu, search for "path" and select**Edit the system environment variables** .  
![Windows Start Edit The System Environment Variables](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-start-edit-the-system-environment-variables.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
4. Find the**Path** variable under**User variables for YOUR\_USERNAME** . Double-click on it to edit it. Click on**New** , and paste the path to your scripts folder. Click on**OK** to accept the changes.  
![Environment Variables User Account Path](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/environment-variables-user-account-path.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Return to your scripts folder in Windows Explorer. Create a new batch file there named "wht.bat". "Inside" it, place this command:  
`whisper --model tiny --language en %1`  
![Creating WHT Batch File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/creating-wht-batch-file.jpg)
<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Create two more batch files, "whs" and "whm".
7. Place this inside the first script:  
`whisper --model small --language en %1`
8. Place this inside the second:  
`whisper --model medium --language en %1`

 Congratulations, you now have three scripts for easily using Whisper's tiny, small, and medium models with your audio files! To transcribe any audio file to text:

1. Locate the file with**Windows File Explorer** .
2. **Right-click** on an empty spot and choose**Open in Terminal** .
3. Type this command, replacing "wht" with "whs" or "whm" to use the small or medium language models:  
`wht YOUR_AUDIO_FILE.mp3`

## Typing at the Speed of Sound With Whisper

 Even the quickest touch-typists can't match the speed at which we speak. However, until recently, talking instead of typing wasn't optimal for creating documents.

 Most voice-to-text solutions produced mediocre results. You could find a few solutions worth trying, but they were complicated to use, or costly. Thankfully, Whisper changed all that.

 After the steps above, you should be ready to transcribe or translate your voice with high accuracy, using only a single command.


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
<li><a href="https://twitter-videos.techidaily.com/new-2023s-quick-share-tweeted-videos-to-whatsapp/"><u>[New] 2023'S Quick Share  Tweeted Videos to WhatsApp</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-debunking-photoshake-is-it-essential-or-excessive/"><u>[New] 2024 Approved  Debunking PhotoShake  Is It Essential or Excessive?</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-igtv-video-submission-made-simple/"><u>[New] 2024 Approved  IGTV Video Submission Made Simple</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-the-inverted-illusion-guide-transforming-visual-content-through-angled-spins/"><u>[New] 2024 Approved  The Inverted Illusion Guide  Transforming Visual Content Through Angled Spins</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-leading-webcams-for-windows-10-enthusiasts-for-2024/"><u>[New] Leading Webcams for Windows 10 Enthusiasts for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-mastering-seamless-music-segmentation-the-art-of-crossfade/"><u>[New] Mastering Seamless Music Segmentation  The Art of Crossfade</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-elevate-editing-excellence-cutting-edge-strategies-for-vimeo-video-reduction/"><u>[Updated] 2024 Approved  Elevate Editing Excellence  Cutting-Edge Strategies for Vimeo Video Reduction</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-capturing-coziness-ideal-winter-scenes-for-yt-video/"><u>[Updated] In 2024, Capturing Coziness  Ideal Winter Scenes for YT Video</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-innovative-solutions-for-storing-mov-files-in-windows-10-for-2024/"><u>[Updated] Innovative Solutions for Storing Mov Files in Windows 10 for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-masterclass-choosing-the-pinnacle-in-hdr-cameras/"><u>[Updated] Masterclass  Choosing the Pinnacle in HDR Cameras</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-youtubes-financial-frontier-strategies-for-maximum-gains/"><u>[Updated] Youtube's Financial Frontier  Strategies for Maximum Gains</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-echoes-fade-out-audio-leveling-methods/"><u>2024 Approved  Echoes Fade Out  Audio Leveling Methods</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-iphone-ringtones-a-guide-to-personalized-sound-choices/"><u>2024 Approved  IPhone Ringtones  A Guide to Personalized Sound Choices</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-mastering-the-art-of-affordable-data-storage-cloud/"><u>2024 Approved  Mastering the Art of Affordable Data Storage (Cloud)</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-perfecting-video-calls-merging-zoom-and-skype-expertise/"><u>2024 Approved  Perfecting Video Calls  Merging ZOOM and SKYPE Expertise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-tour-to-windows-easy-entry-point/"><u>A Step-by-Step Tour to Windows Easy Entry Point</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-missing-mfc71udll-in-windows-os/"><u>Addressing Missing Mfc71u.dll in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correct-disabled-volume-adjustment-on-windows/"><u>Correct Disabled Volume Adjustment on Windows</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/cutting-edge-speedy-frame-compiler/"><u>Cutting Edge  Speedy Frame Compiler</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-red-crossed-symbol-in-windows-explorer/"><u>Deciphering Red Crossed Symbol in Windows Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decorate-with-style-customizing-themes-for-an-improved-win11-experience/"><u>Decorate with Style: Customizing Themes for an Improved Win11 Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-component-services-access-in-windows-11/"><u>Demystifying Component Services Access in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easing-up-stuck-exe-files-on-windows-platform/"><u>Easing Up Stuck EXE Files on Windows Platform</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/elite-arena-showdown-best-of-the-royales-for-2024/"><u>Elite Arena Showdown  Best of the Royales for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/expert-tips-on-seamless-multisnapping-videos-in-snapchat-for-2024/"><u>Expert Tips on Seamless Multisnapping Videos in Snapchat for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/file-management-follies-steering-clear-of-windows-11-errors/"><u>File Management Follies: Steering Clear of Windows 11 Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-failed-directx-file-downloads-on-pcs/"><u>Fixing Failed DirectX File Downloads on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-lost-connection-problem-on-windows-vpn-client/"><u>Fixing Lost Connection Problem on Windows VPN Client</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-offline-lsa-message-in-windows-os/"><u>Fixing the Offline LSA Message in Windows OS</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-oneplus-11r-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an OnePlus 11R Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hide-windows-11-language-line-from-status-bar/"><u>Hide Windows 11 Language Line From Status Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-play-your-favorite-oldschool-pc-games-with-dosbox-x/"><u>How to Play Your Favorite Oldschool PC Games With DOSBox-X</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-effortless-webinar-capture-techniques-for-os-xwindows-enthusiasts/"><u>In 2024, Effortless Webinar Capture Techniques for OS X/Windows Enthusiasts</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-freedom-in-meditation-tracks/"><u>In 2024, Freedom in Meditation Tracks</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-samsung-galaxy-m14-4g-location-by-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Samsung Galaxy M14 4G Location by Number | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-screenshot-success-mastering-instagrams-preferred-video-format-with-fcpx/"><u>In 2024, Screenshot Success  Mastering Instagram's Preferred Video Format with FCPX</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insightful-strategies-for-hardware-serial-numbers-on-windows/"><u>Insightful Strategies for Hardware Serial Numbers on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-batch-renaming-like-a-pro-with-powertoys/"><u>Master Batch Renaming Like a Pro with PowerToys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-taskmanagers-dominance/"><u>Mastery Over TaskManager's Dominance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-non-functioning-intel-unison-issues-in-windows-11/"><u>Navigating Through Non-Functioning Intel Unison Issues in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-with-ease-the-windows-11-touchpad-guide/"><u>Navigating with Ease: The Windows 11 Touchpad Guide</u></a></li>
<li><a href="https://win-blog.techidaily.com/neutralization/"><u>Neutralization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-solutions-for-windows-missing-lsass-components/"><u>Quick Solutions for Windows' Missing Lsass Components</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-original-terminals-in-win11/"><u>Regaining Original Terminals in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-virtual-disk-service-not-started-in-windows/"><u>Remedy for Virtual Disk Service Not Started in Windows</u></a></li>
<li><a href="https://network-issues.techidaily.com/smoothing-over-flickering-win7-views/"><u>Smoothing Over Flickering Win7 Views</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-pc-bloatware-removal-in-windows-11/"><u>Streamline Your PC: Bloatware Removal in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-addressing-roblox-shutdown-issues-on-your-windows-machine/"><u>Swiftly Addressing Roblox Shutdown Issues on Your Windows Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailored-windows-note-placement-guide/"><u>Tailored Windows Note Placement Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-basics-of-windows-canary-and-its-benefits/"><u>The Basics of Windows Canary and Its Benefits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-random-restarts-on-windows-11-systems/"><u>Troubleshoot Random Restarts on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-java-vm-creation-failed-in-windows/"><u>Troubleshooting Java VM Creation Failed in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-mastery-building-hotkeys-for-repetitive-text-snapping-tasks/"><u>Windows 11 Mastery: Building Hotkeys for Repetitive Text Snapping Tasks</u></a></li>
</ul></div>
