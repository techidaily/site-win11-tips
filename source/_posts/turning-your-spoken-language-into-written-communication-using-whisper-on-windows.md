---
title: Turning Your Spoken Language Into Written Communication Using Whisper on Windows
date: 2024-11-25T16:57:57.080Z
updated: 2024-11-27T17:56:24.870Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Turning Your Spoken Language Into Written Communication Using Whisper on Windows
excerpt: This Article Describes Turning Your Spoken Language Into Written Communication Using Whisper on Windows
keywords: Written Communcation Conversion,Speech to Text Transform,Audio-to-Text Windows Tool,Spoken Language Windowing,Whisper App,Auditory Communication Writing,Voice Inputs Into Text Windows
thumbnail: https://thmb.techidaily.com/f8310fb64fe59131a1a603b74493ef91ec9be3bf91a44a7ee26654a9f6fff3c0.jpg
---

## Turning Your Spoken Language Into Written Communication Using Whisper on Windows

 OpenAI's Whisper is a new AI-powered solution that can turn your voice into text. Best of all, it comes at zero cost.

 However, there's a catch: it's more challenging to install and use than your average Windows utility. Especially if you want to use your Nvidia GPU's Tensor Cores to give it a nice boost.

 Don't fret, though. That's why we're here! Read on to find out how to install and use it, but also, if you own one, to have Whisper take advantage of your Nvidia GPU.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Is OpenAI's Whisper?

 ChatGPT is all the rage nowadays, and we already saw[how you can use ChatGPT by OpenAI](https://www.makeuseof.com/how-to-use-chatgpt-by-openai/) . And yet, it's not the only interesting project by OpenAI.

 Powered by deep learning and neural networks, Whisper is a natural language processing system that can "understand" speech and transcribe it into text. But it's also its own thing, sitting at a spot right among all similar solutions:

* Whisper is an AI solution "trained" on natural language. So, it's better at understanding "normal" human speech than older solutions.
* Whisper doesn't come with an interface, nor can it record audio. It can only take existing audio files and output text files.
* Since it's good at "making sense of language", Whisper also has the superpower of automatic translation in a single step.
* Whisper is not an online service and can work entirely offline.
* If you have a relatively modern Nvidia GPU (GTX970 or newer), Whisper can run in "hardware accelerated mode" to boost its speed.
* There's no requirement to register, purchase a license, or buy a subscription.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2Iv3DjT2Fyw?si=pR_z8ZDDVGF2MvKJ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Are AMD GPUs Not Supported?

 For GPUs to be useful for more than graphics, they'd have to act as fully programmable processors. That's why Nvidia created CUDA, officially deemed "a parallel computing platform and programming model". To learn more about CUDA and related hardware ("CUDA cores"), read our article on[what are CUDA cores and how they improve PC gaming](https://www.makeuseof.com/tag/what-are-cuda-cores-pc-gaming/) .

 CUDA is proprietary Nvidia technology, only compatible with Nvidia GPUs. The closest alternatives for AMD's hardware are OpenCL and Radeon Compute Platform. To learn more about how each company's solutions compare, check our article on[AMD Compute Units vs. Nvidia CUDA Cores](https://www.makeuseof.com/compute-units-vs-cuda-cores-whats-the-difference/) .

 Compared to the alternatives, CUDA is considered more mature, performant, and easier to use. Thus, most developers only target CUDA, which, in turn, means that their software only takes advantage of the hardware features on Nvidia GPUs. And that includes Whisper.

## How to Download and Install Whisper

 Unfortunately, Whisper is not a standalone app you can download, install, and run. It relies on other software, which must also be installed.

 For Windows, to keep this guide simple, we'll use Chocolatey extensively for installing most of the necessary software parts. Check our guide on[the quickest way to install Windows software](https://www.makeuseof.com/tag/quickest-way-install-windows-software-command-prompt/) for more info on Chocolatey.

 For Linux and Macs, the installation process (excluding the Windows path variable, and easy-to-use batch files we'll create) should be similar.

1. To install and use Whisper, you must have**Python** and its**PIP** tool installed and added to the Windows "Path" variable. For info on that, check our article on[how to install Python PIP on Windows, Mac, and Linux](https://www.makeuseof.com/tag/install-pip-for-python/) .
2. Install**FFMPEG** through Chocolatey with this command:  
`choco install ffmpeg`  
 Also, install its Python version with:  
`pip3 install python-ffmpeg`  
![pip install python ffmpeg](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/pip-install-python-ffmpeg.jpg)
3. Finally, install Whisper from its Github page with:  
`pip3 install git+https://github.com/openai/whisper.git`

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/58KlTPHv8dU?si=7ICagyNgrao7OkVO&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`whisper --help | findstr -i pytorch`  
 You should see**(default: cuda)** instead of**(default: cpu)** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wNhKhWc0wLc?si=1XLYV0sXV52Xc0lu&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What to Do if Torch Fails to Install

 If you encounter the "no version found" errorwhile installing torch, you may need to install an older version of Python parallel to your current one.

Use this command to do that:

`choco install python --version OLDER_VERSION --side-by-side`

Replace "OLDER\_VERSION" with a version, like 3.10.

![choco install python alternate version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/choco-install-python-alternate-version.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SDUPd69Qfls?si=uIGZG-riskwmVZYg&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Then, use the path of the secondary version for all "generic" Whisper commands (e.g., "c:\\Python310\\Scripts\\pip.exe" rather than just "pip").

## How to Record Your Voice

 You can use any sound-recording app to turn your voice into a WAV or MP3 file. Windows includes such an app—for more info on that, see[how to use the Windows 10 Voice Recorder app](https://www.makeuseof.com/how-to-use-the-windows-10-voice-recorder-app/) .

 For a more full-featured option, try**Audacity** . Learn how to do it with our guide on[how to use Audacity to record audio on Windows and Mac](https://www.makeuseof.com/how-to-use-audacity-to-record-audio/) .

![Recording voice with Audacity](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/recording-voice-with-audacity.jpg)

## How to Start Transcribing With Whisper

 Although Whisper doesn't come with a user-friendly GUI, its use is ultra-simple.

 Let's say we have the file**LatestNote.mp3** which contains speech in Greek, in folder**c:\\MyAudioFiles** , and want to translate it to English and transcribe it into a text file.

1. We begin by running**Command Prompt** or**PowerShell** .
2. We "change directory" where the audio file is stored with this command:  
`cd C:\MyAudioFiles`
3. We unleash Whisper on the file with:  
`whisper --model base --language gr --task translate LatestNote.mp3`  
![Whisper translate gr](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/whisper-translate-gr.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qn1XkPJde9Y?si=i6ZJARXO8sJhy2FV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
4. Find the**Path** variable under**User variables for YOUR\_USERNAME** . Double-click on it to edit it. Click on**New** , and paste the path to your scripts folder. Click on**OK** to accept the changes.  
![Environment Variables User Account Path](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/environment-variables-user-account-path.jpg)
5. Return to your scripts folder in Windows Explorer. Create a new batch file there named "wht.bat". "Inside" it, place this command:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HMuxjTCMX2E?si=ylRTMJuUstpjLsZc&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`whisper --model tiny --language en %1`  
![Creating WHT Batch File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/creating-wht-batch-file.jpg)
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
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-unveiling-the-secrets-of-powerful-titles/"><u>[Updated] 2024 Approved Unveiling the Secrets of Powerful Titles</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-precision-editing-at-your-fingertips-canvas-boundary-eradication/"><u>[Updated] Precision Editing at Your Fingertips Canva's Boundary Eradication</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-zooming-into-success-livestream-mastery-with-zoom-and-youtube/"><u>2024 Approved Zooming Into Success Livestream Mastery with Zoom and YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-into-windows-security-learn-about-canary-channel/"><u>Dive Into Windows Security: Learn About Canary Channel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reclaim-a-non-functional-tab-key-on-windows-10/"><u>How to Reclaim a Non-Functional Tab Key on Windows 10</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-14-plus-to-other-iphone-15-pro-max-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 14 Plus to other iPhone 15 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-best-spy-watches-for-your-honor-x7b-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Best Spy Watches For your Honor X7b | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-resolve-microsoft-office-error-0x80041015/"><u>Quick Guide to Resolve Microsoft Office Error 0X80041015</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rollback-mastery-utilizing-system-restore-in-windows/"><u>Rollback Mastery: Utilizing System Restore in Windows</u></a></li>
</ul></div>

