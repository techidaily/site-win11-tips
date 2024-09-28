---
title: "Effortless Tracking of Changes: Mastering Excel's Pivot Table for Percentage Fluctuation Analysis"
date: 2024-08-28T01:08:35.115Z
updated: 2024-08-29T01:08:35.115Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/18a804e379d2e35c3dce7adfbd6c31163356bdf9fa867d443daa8eb75630573f.jpg
---

## Effortless Tracking of Changes: Mastering Excel's Pivot Table for Percentage Fluctuation Analysis

### Quick Links

* [Formatting the Range as a Table](https://win-answers.techidaily.com/how-to-get-rockstar-online-gaming-platforms-working-again-for-windows-users/)
* [Create a PivotTable to Display Percentage Change](https://techidaily.com/your-complete-guide-to-reset-samsung-galaxy-a15-5g-drfone-by-drfone-reset-android-reset-android/)

 Pivot Tables are an amazing built-in reporting tool in Excel. While typically used to summarize data with totals, you can also use them to calculate the percentage of change between values. Even better: It is simple to do.

 You could use this technique to do all kinds of things---pretty much anywhere you'd like to see how one value compares to another. In this article, we're going to use the straightforward example of calculating and displaying the percent by which the total sales value changes month by month.

 Here's the sheet we're going to use.

![Two years of sales data for a PivotTable](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/sample-data-1.png) 

 It's a pretty typical example of a sales sheet that shows the order date, customer name, sales rep, total sales value, and a few other things.

 To do all this, we're first going to format our range of values as a table in Excel and we're then going to create a Pivot Table to make and display our percentage change calculations.

##  Formatting the Range as a Table

 If your data range is not already formatted as a table, we'd encourage you to do so. Data stored in tables have multiple benefits over data in cell ranges of a worksheet, especially when using PivotTables ([read more about the benefits of using tables](https://www.linkedin.com/pulse/9-reasons-you-need-using-excel-tables-alan-murray/)).

 To format a range as a table, select the range of cells and click Insert > Table.

![Create Table dialog to specify the range of cells](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/create-table.png) 

 Check that the range is correct, that you do have headers in the first row of that range, and then click "OK."

 The range is now formatted as a table. Naming the table will make it easier to refer to in the future when creating PivotTables, charts, and formulas.

 Click the "Design" tab under Table Tools, and enter a name in the box provided at the start of the Ribbon. This table has been named "Sales."

![Name the Table in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/name-the-table.png) 

 You can also change the style of the table here if you want.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
##  Create a PivotTable to Display Percentage Change

 Now let's get on with creating the PivotTable. From within the new table, click Insert > PivotTable.

 The Create PivotTable window appears. It will have automatically detected your table. But you could select the table or range you want to use for the PivotTable at this point.

![The Create PivotTable window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/create-pivottable-1.png) 

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
###  Group the Dates into Months

 We will then drag the date field that we want to group by into the rows area of the PivotTable. In this example, the field is named Order Date.

 From Excel 2016 on, date values are automatically grouped into years, quarters and months.

 If your version of Excel does not do this, or you simply want to change the grouping, right-click a cell containing a date value and then select the "Group" command.

![Group dates in a PivotTable](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/group-dates.png) 

 Select the groups you want to use. In this example, only Years and Months are selected.

![Specifying Years and Months in the Group dialog](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/group-dialog.png) 

 The year and month are now fields which we can use for analysis. The months are still named as Order Date.

![Years and Order Date fields in Rows](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/years-and-months.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
###  Add the Value Fields to the PivotTable

 Move the Year field from Rows and into the Filter area. This enables the user to filter the PivotTable for a year, rather than clutter the PivotTable with too much information.

 Drag the field containing the values (Total sales Value in this example) you want to calculate and present change into the Values area **twice**.

 It might not look like much yet. But that will change very soon.

![Sales value field added twice to the PivotTable](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/values-added-twice.png) 

 Both value fields will have defaulted to sum and currently have no formatting.

 The values in the first column we would like to keep as totals. They do however require formatting.

 Right-click on a number in the first column and select "Number Formatting" from the shortcut menu.

 Choose the "Accounting" format with 0 decimals from the Format Cells dialog.

 The PivotTable now looks like this:

![Formatting the first column](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/pivottable-with-formatting.png) 

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
###  Create the Percentage Change Column

 Right-click on a value in the second column, point to "Show Values," and then click the "% Difference from" option.

![Show values as a percentage difference](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/show-values-as.png) 

 Select "(Previous)" as the Base Item. This means that the current month value is always compared to the previous months (Order Date field) value.

![Select Previous as the base item to compare to](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/previous.png) 

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
 The PivotTable now shows both the values and the percentage change.

![Show values and percentage change](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/values-and-percentage-change.png) 

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
 Click in the cell containing Row Labels and type "Month" as the header for that column. Then click in the header cell for the second values column and type "Variance".

![Rename the headers of the PivotTable](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/rename-headers.png) 

###  Add Some Variance Arrows

 To really polish off this PivotTable, we would like to visualize the percentage change better by adding some green and red arrows.

 These will provide us with a lovely way of seeing whether a change has been positive or negative.

 Click on any one of the values in the second column and then click Home > Conditional Formatting > New Rule. In the Edit Formatting Rule window that opens, take the following steps:

1. Select the "All cells showing "Variance" values for Order Date" option.
2. Select "Icon Sets" from the Format Style list.
3. Select the red, amber and green triangles from the Icon Style list.
4. In the Type column, change the list option to say "Number" instead of Percentage. This will change the Value column to 0's. Exactly what we want.

![Applying variance icons with Conditional Formatting](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/formatting-variance-icons.png) 

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
 Click "OK" and the Conditional Formatting is applied to the PivotTable.

![The completed variance PivotTable](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/04/completed-variance-table.png) 

 PivotTables are an incredible tool and one of the simplest ways to display the percentage change over time for values.

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


