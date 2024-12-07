---
title: Effective Techniques for Applying the Year Functionality in MS Excel Tutorials
date: 2024-12-01T21:40:55.515Z
updated: 2024-12-06T18:26:23.588Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/stock-lede-microsoft-office_excel-1.png
---

## Effective Techniques for Applying the Year Functionality in MS Excel Tutorials

If you need to quickly extract the year from a date in Microsoft Excel, you can use the YEAR function. This will give you the year value in a separate cell, allowing you to use it in a separate formula.

 The YEAR function can be especially useful if you've [converted text to date values in Excel,](https://screen-mirror.techidaily.com/how-to-screen-mirroring-samsung-galaxy-xcover-7-drfone-by-drfone-android/) and you want to extract the year values from your data.

Related: [How to Convert Text to Date Values in Microsoft Excel](https://screen-mirror.techidaily.com/how-to-screen-mirroring-samsung-galaxy-xcover-7-drfone-by-drfone-android/) 

 To use the YEAR function, you'll need to open your Excel spreadsheet and have cells containing dates (in any format) set as an appropriate "Date" number value.

 It's best to set these cell values as "Long Date" or "Short Date" numbers value using the Home > Number drop-down menu. You can also use cells with custom date formats.

![Ensure cells with dates in Excel are set to an appropriate &quot;Date&quot; number value using the Home &gt; Number drop-down menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/Excel-Set-Number-as-Date.png) 

 If you have a date converted to a number, you can also extract the year from a 5-digit Excel "serial" number, which counts the number of days from the 1st January 1900\. You can see this value by changing any date value to a standard number value using the Home > Number menu.

 Because of this particular limit, you can only use YEAR to extract the year from dates starting from the 1st January 1900 onwards. The function won't work with dates earlier than that.

 To extract the year from a cell containing a date, type 

        `=YEAR(CELL)`
    
 , replacing 

        `CELL`
    
 with a cell reference. For instance, 

        `=YEAR(A2)`
    
 will take the date value from cell A2 and extract the year from it.

![Examples of the YEAR function used in Microsoft Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/Excel-YEAR-Function.png) 

 The example above shows various styles of date values in column A. Regardless of the format, the YEAR function used in column B is able to read these and extract the year value.

 If you prefer, you could also use a 5-digit Excel "serial" number, rather than a cell reference.

![Examples of the YEAR function used in Microsoft Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/Excel-YEAR-Function.png) 

 The example above shows this using the formula 

        `=YEAR(43478)`
    
 , with a serial number (43478) matching the date (13th January 2019), which the YEAR function is able to understand. From this serial number, the year (2019) is returned.

 The value returned by a formula containing the YEAR function can then be used by other formula. For instance, you could combine it with a DATE formula (eg. 

        `=DATE(YEAR(A2),1,11`
    
) to create a valid date value.

![An example DATE formula value, created using the value created by a YEAR formula in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/Excel-DATE-Function-Example.png) 

 If you want to repeat it for multiple date values, you can [use the fill handle](https://visual-screen-recording.techidaily.com/new-in-2024-top-5-best-hdmi-21-gaming-monitors-ps5-compatible/) to copy the YEAR formula into additional cells.

Related: [How to Automatically Fill Sequential Data into Excel with the Fill Handle](https://visual-screen-recording.techidaily.com/new-in-2024-top-5-best-hdmi-21-gaming-monitors-ps5-compatible/)

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
<li><a href="https://some-tips.techidaily.com/new-streamline-screen-capabilities-building-in-frame-video-experiences-on-sierra/"><u>[New] Streamline Screen Capabilities Building In-Frame Video Experiences on Sierra</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-optimizing-content-sharing-from-twitters-to-snaps-for-2024/"><u>[Updated] Optimizing Content Sharing From Twitters to Snaps for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/adapting-careers-in-an-ai-driven-world/"><u>Adapting Careers in an AI-Driven World</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/g-value-instructional-design-of-youtube-alerts-and-annotations/"><u>Adding Value Instructional Design of YouTube Alerts & Annotations</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-or-see-text-messages-what-can-you-do-with-life360-on-apple-iphone-12-pro-drfone-by-drfone-virtual-ios/"><u>Can Life360 Track Or See Text Messages? What Can You Do with Life360 On Apple iPhone 12 Pro? | Dr.fone</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/comprehensive-review-of-the-aphaca-bt6e-portable-bluetooth-fm-broadcasting-device-for-cars/"><u>Comprehensive Review of the Aphaca BT6e Portable Bluetooth FM Broadcasting Device for Cars</u></a></li>
<li><a href="https://win11-tips.techidaily.com/defeating-the-invalid-captcha-obstacle-in-steam/"><u>Defeating the 'Invalid CAPTCHA' Obstacle in Steam</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/digital-artists-dreamland-ultimate-afx-template-set/"><u>Digital Artist's Dreamland Ultimate AFX Template Set</u></a></li>
<li><a href="https://win11-tips.techidaily.com/downloading-and-installing-windows-11-arm-an-iso-based-tutorial/"><u>Downloading & Installing Windows 11 ARM: An ISO-Based Tutorial</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/google-is-launching-an-ai-called-bard-to-compete-with-chatgpt/"><u>Google Is Launching An AI Called Bard to Compete With ChatGPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-manipulate-and-tailor-your-fax-cover-pages-in-w11/"><u>How to Manipulate and Tailor Your Fax Cover Pages in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-quickly-turn-off-notifications-in-windows-11/"><u>How to Quickly Turn Off Notifications in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionizing-access-control-methods-for-windows-admins/"><u>Revolutionizing Access Control Methods for Windows Admins</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722963662119-step-by-step-download-drivers-for-your-microsoft-4000-ergonomic-keyboard-today/"><u>Step-by-Step: Download Drivers for Your Microsoft 4000 Ergonomic Keyboard Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/syncing-your-customized-powertoys-setup/"><u>Syncing Your Customized PowerToys Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trick-installing-outlook-preview-in-windows-1011/"><u>Trick: Installing Outlook Preview in Windows 10/11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-solutions-for-windows-11s-red-screen-error/"><u>Troubleshooting and Solutions for Windows 11'S Red Screen Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-storage-management-relocate-your-onedrive/"><u>Win 11 Storage Management: Relocate Your OneDrive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-strategy-against-default-saving-failures/"><u>Winning Strategy Against Default Saving Failures</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kZVDkvMZvP4?si=xAugrCf-Ud6EMMpm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

