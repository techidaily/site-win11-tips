---
title: "Invisible Handshakes: Encrypted Transfers for WS11/W10 Users"
date: 2024-10-28T16:46:00.830Z
updated: 2024-11-01T18:01:29.326Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Invisible Handshakes: Encrypted Transfers for WS11/W10 Users"
excerpt: "This Article Describes Invisible Handshakes: Encrypted Transfers for WS11/W10 Users"
keywords: Invisible Signals,Data Sharing,Encrypted Exchange,Hidden Handshakes,Secret Transfers,WS11/W10 Security,Cryptographic Transactions,Invisible Signals,Data Sharing,Encrypted Exchange,Hidden Handshakes,Secret Transfers,WS11/W10 Security,Cryptographic Transactions
thumbnail: https://thmb.techidaily.com/eb94a6fed42a33c4c872605a3bb9b0ee6f8339a94887f50639d498bad918e7a5.jpg
---

## Invisible Handshakes: Encrypted Transfers for WS11/W10 Users

 File Explorer in Windows displays any internal or external drives that are connected to your system by default. However, if you don't want a certain drive to appear in File Explorer, you can always hide it.

 By hiding a drive on Windows, you can prevent others from accessing sensitive files within that drive and keep them safe. If you're interested in doing that, this guide will walk you through four different methods to hide drives on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Hide a Drive Using the Disk Management App

 The Disk Management tool on Windows makes it easy to perform various storage-related tasks such as formatting hard disk partitions, assigning drive letters, managing disk space, and more. You can also use it to hide a drive partition on Windows. Here's how:

1. Press**Win + R** or use one of the[many ways to open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**diskmgmt.msc** in the text field and press**Enter** .
3. In the Disk Management window that opens, right-click on the drive you wish to hide and select**Change Drive Letter and Paths** .
4. Now, click the**Remove** button from the pop-up window.
5. Choose**Yes** when the warning message appears.  
![Hide a Drive Using Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-using-disk-management.jpg)

 Once you complete the above steps, your drive will no longer appear in File Explorer.

## 2\. Hide a Drive in Windows With Diskpart Command

 If you're a power user who prefers to make changes via the command-line interface, you can use the diskpart command to hide a drive on Windows. Fortunately, this isn't as intimidating as it might sound.

To hide a drive in Windows with Command Prompt, follow these steps:

1. Press**Win + X** and select**Terminal (Admin)** from the menu that appears.
2. Select**Yes** when the User Account Control (UAC) prompt shows up.
3. In the console, type**diskpart** and press**Enter** .
4. Input the following command in the console and press**Enter** to view a list of drives connected to your system:  
`list volume`  
![List of Drives in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/list-of-drives-in-command-prompt.jpg)
5. Note down the letter of the drive you want to hide from the**Ltr** column.
6. Type the following command to select your drive. Make sure you replace**X** in the command with the drive letter noted in the last step.  
`select volume X`
7. Lastly, run the following command to remove the drive letter and hide the volume.  
`remove letter X`  
![Hide a Drive Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<span id="1982570">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982570.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982570">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982570.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982570%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982570/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You should see a message that reads **Diskpart successfully removed the drive letter or mount point** . Following that, the drive will no longer appear on your PC.

 If you like using Command Prompt, why not check our guide on[how to master the Command Prompt in Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) ?

## 3\. Hide a Drive Using the Group Policy Editor

 The Local Group Policy Editor is a tool that allows you to configure a wide range of settings on your computer. You can use it to hide a drive from your Windows computer.

 The Local Group Policy Editor is only available in Professional, Enterprise, and Education editions of Windows. If you're using the Windows Home edition, check our guide on[how to access the Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

Here's what you need to do:

1. Press**Win + R** to open the Run dialog box.
2. Type**gpedit.msc** in the box and click**OK** .
3. Select**Yes** when the User Account Control (UAC) prompt shows up.
4. In the Local Group Policy Editor window, use the left pane to navigate to **User Configuration > Administrative Templates > Windows Components > File Explorer** .
5. Double-click the**Hide these specified drives in My Computer** policy on your right.  
![Hide a Drive With Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-with-group-policy-editor.jpg)
6. Select the**Enabled** option.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484950/16446" target="_top" id="1484950">
  <img src="//a.impactradius-go.com/display-ad/16446-1484950" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484950/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Under**Options** , select the drive you want to hide.
8. Click**Apply** followed by**OK** .

 Once you complete the above steps, Windows will hide the specified drive from File Explorer. If you want to unhide the drive later, use the same steps and set the**Hide these specified drives in My Computer policy** to**Not configured** .

## 4\. Hide a Drive in Windows via the Registry Editor

 Another brilliant tool that allows you to configure system settings in Windows easily is the Registry Editor. You can use Registry Editor to hide a drive if none of the above methods work. However, you must be careful[not to accidentally mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/) in the process.

 To be safe, you should back up all the registry files before proceeding. If you need help with that, check our guide on[how to back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

 Once you're done with that, use the following steps to hide a drive using Windows Registry:

1. Press**Win + S** to open the search menu.
2. Type**registry editor** in the box and select the first result that appears.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > Software > Microsoft > Windows > CurrentVersion > Policies > Explorer** .
5. Right-click on the**Explorer** key and go to**New** and select**DWORD (32-bit) Value** from the sub-menu.
6. Rename the DWORD to**NoDrives** .
7. Double-click the**NoDrives** DWORD.
8. In the**Edit DWORD (32-bit) Value** dialog box, select**Decimal** as the Base.  
![Hide a Drive via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-via-registry-editor.jpg)
9. Enter a number corresponding to the drive you want to hide in the**Value data** field and click**OK** . Refer to the table below to determine which number to use.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037356/7443" target="_top" id="2037356">
  <img src="//a.impactradius-go.com/display-ad/7443-2037356" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037356/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Drive Letter Refrence for Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/drive-letter-refrence-for-registry-editor.jpg)

 For instance, if you were to hide the**E:** drive from your computer, you'd enter**16** in the Value data field.

 You can also use this method to hide multiple drives at the same time. To do so, add the decimal numbers for both drives and enter the total in the Value data field. For example, if you're looking to hide drive**G:** and**H:** from your computer, you should enter**192** (64 + 128) in the Value data field.

 You'll have to restart your PC to apply the changes. Following that, the drive will not appear in File Explorer. You can undo the above changes at any point by deleting the**NoDrives** DWORD.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1166360/14483" target="_top" id="1166360">
  <img src="//a.impactradius-go.com/display-ad/14483-1166360" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://electronicx.pxf.io/i/5597632/1166360/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Hiding Drives in Windows Is Easy

 Regardless of the method you use, hiding a drive on Windows is fairly simple and shouldn't take more than a few minutes.

 Alternatively, if you don't want to hide an entire drive, Windows also lets you hide specific files and folders in a few easy steps.

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
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-immediate-ios-screen-playback-guide/"><u>[New] 2024 Approved Immediate iOS Screen Playback Guide</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-optimal-steadicams-matched-with-dslr-cameras/"><u>[New] 2024 Approved Optimal Steadicams Matched with DSLR Cameras</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-when-does-instagram-get-most-active-a-comprehensive-look/"><u>[New] 2024 Approved When Does Instagram Get Most Active? A Comprehensive Look</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-top-video-formats-for-maximum-youtube-engagement/"><u>[Updated] 2024 Approved Top Video Formats for Maximum YouTube Engagement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/2024nun-en-guclu-yabanci-teknikli-ucretlessan-video-donusturme-programi/"><u>2024'Nun En Güçlü Yabancı Teknikli Ücretlessan Video Dönüştürme Programı</u></a></li>
<li><a href="https://extra-resources.techidaily.com/50plus-text-wonders-in-video-editing/"><u>50+ Text Wonders in Video Editing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/wavswfmovavi/"><u>免費在線WAV/SWF音訊格式變更者：Movavi 上的方便轉換器選擇</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1726226973578-mp3mp4-movavi/"><u>如何快速免费地将MP3文件转换为MP4 - Movavi秘技</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/5lia6iis5lq644gm5l244ge44ke44gz44ge5pya6auy44gu5yuv55s757eo6zug44oe44o844or44oz44k544oi44k744ow44oz/"><u>一般人が使いやすい最高の動画編集ツールベストセブン</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-no-cost-2d-design-programs-to-enhance-creativity-with-transparency-features-software-and-applications-year-2024/"><u>Best No-Cost 2D Design Programs to Enhance Creativity with Transparency Features (Software & Applications) – Year 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/descubra-os-seus-melhores-ferramentas-pdf-reader-a-lista-dos-6-mais-indispensaveis-para-editores-e-lectores/"><u>Descubra Os Seus Melhores Ferramentas PDF Reader: A Lista Dos 6 Mais Indispensáveis Para Editores E Lectores</u></a></li>
<li><a href="https://facebook.techidaily.com/digital-eyes-for-economic-advantage/"><u>Digital Eyes for Economic Advantage</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-10-fingerprint-lock-apps-to-lock-your-oppo-reno-11-pro-5g-phone-by-drfone-android/"><u>In 2024, Top 10 Fingerprint Lock Apps to Lock Your Oppo Reno 11 Pro 5G Phone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/mastering-lut-applications-in-ae-for-2024/"><u>Mastering LUT Applications in AE for 2024</u></a></li>
<li><a href="https://win-solutions.techidaily.com/resolved-developer-mistake-5573-in-call-of-duty-vanguard-how-to-fix-it/"><u>Resolved: Developer Mistake 5573 in Call of Duty: Vanguard - How to Fix It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-free-video-editing-tools-compatible-with-windows-7/"><u>Top Free Video Editing Tools Compatible with Windows 7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tutorial-de-conversion-dvd-a-avi-comment-utiliser-le-programme-movavi-video-converter/"><u>Tutorial De Conversion DVD À AVI: Comment Utiliser Le Programme Movavi Video Converter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upload-and-convert-your-tiff-files-to-bmp-gratis-expert-online-tools-by-movavi/"><u>Upload & Convert Your TIFF Files to BMP Gratis - Expert Online Tools by Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/webp-jpg/"><u>WebP 그림을 JPG로 무료 강조한 웹 편집 도구 - 모바이비</u></a></li>
</ul></div>

