---
title: "Mastering Excel Macros: Streamline Your Workflow and Eliminate Repetitive Chores"
date: 2024-08-27 20:35:26
updated: 2024-08-29 12:11:53
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/8e48b2813408b75482794fbb8e9c7fd16cd8c115a0a176db85647e2b441ce187.jpg
---

## Mastering Excel Macros: Streamline Your Workflow and Eliminate Repetitive Chores

### Quick Links

* [What is a Macro?](https://easy-unlock-android.techidaily.com/mastering-lock-screen-settings-how-to-enable-and-disable-on-nokia-xr21-by-drfone-android/)
* [Creating a Macro: An Explanation by Example](https://tech-renaissance.techidaily.com/ordering-your-star-wars-adventure-a-step-by-step-disneyplus-tutorial/)
* [Using an Excel Macro](https://facebook-record-videos.techidaily.com/updated-2024-approved-aspect-ratios-unveiled-a-complete-youtube-manual/)
* [Looking Under the Hood: What Makes a Macro Work](https://change-location.techidaily.com/how-to-teleport-your-gps-location-on-samsung-galaxy-xcover-7-drfone-by-drfone-virtual-android/)
* [Taking Our Example One Step Farther...](https://youtube-clips.techidaily.com/boost-income-secrets-to-successful-youtube-shorts-earning-for-2024/)
* [Download this Template](https://android-pokemon-go.techidaily.com/in-2024-pokemon-go-cooldown-chart-on-motorola-razr-40-drfone-by-drfone-virtual-android/)

 One of the more powerful, but seldom used functions of Excel is the ability to very easily create automated tasks and custom logic within macros. Macros provide an ideal way to save time on predictable, repetitive tasks as well as standardize document formats - many times without having to write a single line of code.

 If you are curious what macros are or how to actually create them, no problem - we will walk you through the entire process.

 Note: the same process should work in most versions of Microsoft Office. The screenshots might look slightly different.

##  What is a Macro?

 A Microsoft Office Macro (as this functionality applies to several of the MS Office Applications) is simply Visual Basic for Applications (VBA) code saved inside a document. For a comparable analogy, think of a document as HTML and a macro as Javascript. In much of the same way that Javascript can manipulate HTML on a webpage, a macro can manipulate a document.

 Macros are incredibly powerful and can do pretty much anything your imagination can conjure. As a (very) short list of functions you can do with a macro:

* Apply style and formatting.
* Manipulate data and text.
* Communicate with data sources (database, text files, etc.).
* Create entirely new documents.
* Any combination, in any order, of any of the above.

##  Creating a Macro: An Explanation by Example

 We start with your garden variety CSV file. Nothing special here, just a 10x20 set of numbers between 0 and 100 with both a row and column header. Our goal is to produce a well formatted, presentable data sheet which includes summary totals for each row.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/image46.png) 

 As we stated above, a macro is VBA code, but one of the nice things about Excel is you can create/record them with zero coding required - as we will do here.

 To create a macro, go to View > Macros > Record Macro.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/image47.png) 

 Assign the macro a name (no spaces) and click OK.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/image48.png) 

 Once this is done, all of your actions are recorded - every cell change, scroll action, window resize, you name it.

 There are a couple of places which indicate Excel is record mode. One is by viewing the Macro menu and noting that Stop Recording has replaced the option for Record Macro.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/image49.png) 

 The other is in the bottom right corner. The 'stop' icon indicates it is in macro mode and pressing here will stop the recording (likewise, when not in record mode, this icon will be the Record Macro button, which you can use instead of going to the Macros menu).

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/image50.png) 

 Now that we are recording our macro, let's apply our summary calculations. First add the headers.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/image51.png) 

 Next, apply the appropriate formulas (respectively):

* \=SUM(B2:K2)
* \=AVERAGE(B2:K2)
* \=MIN(B2:K2)
* \=MAX(B2:K2)
* \=MEDIAN(B2:K2)

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/image52.png) 

 Now, highlight all the calculation cells and drag the length of all our data rows to apply the calculations to each row.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/image53.png) 

 Once this is done, each row should display their respective summaries.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/image54.png) 

 Now, we want to get the summary data for the entire sheet, so we apply a few more calculations:

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/image55.png) 

 Respectively:

* \=SUM(L2:L21)
* \=AVERAGE(B2:K21) \*This must be calculated across all data because the average of the row averages does not necessarily equal the average of all the values.
* \=MIN(N2:N21)
* \=MAX(O2:O21)
* \=MEDIAN(B2:K21) \*Calculated across all data for the same reason as above.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/image56.png) 

 Now that the calculations are done, we will apply the style and formatting. First apply general number formatting across all the cells by doing a Select All (either Ctrl + A or click the cell between the row and column headers) and select the "Comma Style" icon under the Home menu.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/image57.png) 

 Next, apply some visual formatting to both the row and column headers:

* Bold.
* Centered.
* Background fill color.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/image58.png) 

 And finally, apply some style to the totals.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/image59.png) 

 When all is finished, this is what our data sheet looks like:

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/image60.png) 

 Since we are satisfied with the results, stop the recording of the macro.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/image61.png) 

 Congratulations - you have just created an Excel macro.

 In order to use our newly recorded macro, we have to save our Excel Workbook in a macro enabled file format. However, before we do that, we first need to clear all the existing data so that it is not embedded in our template (the idea being every time we use this template, we will import the most up-to-date data).

 To do this, select all cells and delete them.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/image62.png) 

 With the data now cleared (but the macros still included in the Excel file), we want to save the file as a macro enabled template (XLTM) file. It is important to note that if you save this as a standard template (XLTX) file then macros will **not** be able to be run from it. Alternately, you can save the file as a legacy template (XLT) file, which will allow macros to be run.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/image63.png) 

 Once you have saved the file as a template, go ahead and close Excel.

##  Using an Excel Macro

 Before covering how we can apply this newly recorded macro, it is important to cover a few points about macros in general:

* **Macros can be malicious.**
* See the point above.

 VBA code is actually quite powerful and can manipulate files outside of the scope of the current document. For example, a macro could alter or delete random files in your My Documents folder. As such, it is important to make sure you only run macros from trusted sources.

 To put our data format macro to use, open the Excel Template file which was created above. When you do this, assuming you have standard security settings enabled, you will see a warning across the top of the workbook which says that macros are disabled. Because we trust a macro created by ourselves, click the 'Enable Content' button.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/image64.png) 

 Up next, we are going to import the latest data set from a CSV (this is the source the worksheet used to create our macro).

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/image65.png) 

 To complete the import of the CSV file, you may have to set a few options in order for Excel to interpret it correctly (e.g. delimiter, headers present, etc.).

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/image66.png) 

 Once our data is imported, simply go to the Macros menu (under the View tab) and select View Macros.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/image67.png) 

 In the resulting dialog box, we see the "FormatData" macro we recorded above. Select it and click Run.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/image68.png) 

 Once running, you may see the cursor jump around for a few moments, but as it does you will see the data being manipulated **exactly** as we recorded it. When all is said and done, it should look just like our original - except with different data.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/image69.png) 

##  Looking Under the Hood: What Makes a Macro Work

 As we have mentioned a couple of times, a macro is driven by Visual Basic for Applications (VBA) code. When you "record" a macro, Excel is actually translating everything you do into its respective VBA instructions. To put it simply - you don't have to write any code because Excel is writing the code for you.

 To view the code that makes our macro run, from the Macros dialog click the Edit button.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/image70.png) 

 The window that opens displays the source code that was recorded from our actions when creating the macro. Of course, you can edit this code or even create new macros entirely inside of the code window. While the recording action used in this article will likely fit most needs, more highly customized actions or conditional actions would require you to edit the source code.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/image71.png) 

##  Taking Our Example One Step Farther...

 Hypothetically, assume our source data file, data.csv, is produced by an automated process which always saves the file to the same location (e.g. [C:\\Data\\data.csv](https://www.howtogeek.com/162975/geek-school-learn-how-to-use-excel-macros-to-automate-tedious-tasks/file://\\NetworkPath\Important\data.csv) is always the most recent data). The process of opening this file and importing it can be easily made into a macro as well:

1. Open the Excel Template file containing our "FormatData" macro.
2. Record a new macro named "LoadData".
3. With the macro recording, import the data file like you normally would.
4. Once the data is imported, stop recording the macro.
5. Delete all the cell data (select all then delete).
6. Save the updated template (remember to use a macro enabled template format).

 Once this is done, whenever the template is opened there will be two macros - one which loads our data and the other which formats it.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/image72.png) 

 If you really wanted to get your hands dirty with a bit of code editing, you could easily combine these actions into a single macro by copying the code produced from "LoadData" and inserting it at the beginning of the code from "FormatData".

##  Download this Template

 For your convenience, we have included both the Excel template produced in this article as well as a sample data file for you to play around with.

[Download Excel Macro Template from How-To Geek](https://fox-http.techidaily.com/new-2024-approved-comprehensive-2023-guide-to-lg-360-cam-tech/)

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
