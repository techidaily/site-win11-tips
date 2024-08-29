---
title: Effective Techniques for Applying the Year Functionality in MS Excel Tutorials
date: 2024-08-27 12:41:37
updated: 2024-08-29 10:50:26
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
