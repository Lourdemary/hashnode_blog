## Advanced Excel Filter - Unique/Criteria/Wildcards

More complicated filtering may be done with the Excel Advanced Filter than with the [Excel Autofilter](https://lourdemary.hashnode.dev/day-02-of-100-days-of-code-in-data-analytics-basic-excel-filter).

The Advanced filter may be used to filter a data collection based on user-defined criteria and can be applied to many columns of data at the same time. Rather of using a drop-down menu, these criteria are set on the same spreadsheet as the range to be filtered.

![Screenshot (119).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1655220036487/ElL5WpDMI.png align="left")
A List_range and a Criteria_range must be specified in order to conduct an advanced Excel filter. Both of these ranges define cell ranges in your working spreadsheet.

|Range|Discription|
|---|---|
|List_range|You must specify the range of cells you want to filter. Headers at the top of each column should be included in this range.|
|Criteria_range|The filtering criteria are supplied in a range of cells (usually located above or below the list range)|

> Shortcut : ALT + A + Q

#### Extracting a Unique list
The steps of extracting a unique list are as follows:

1. Select the entire source data (data set).
![Screenshot (121).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1655309982880/WofluBZj8.png align="left")
2. Data tab –> Sort & Filter –> Advanced.
>This will open the Advanced Filter dialog box.
(You can also use the keyboard shortcut – Alt + A + Q).
3. In the advanced dialog box 
![Screenshot (122).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1655310008228/dJ17Hp2ux.png align="left")
  - Action: Select the ‘Copy to another location’ option. 
  - List Range: Make sure it corresponds to the dataset you're looking for unique records in. Also, ensure sure the data set's headers are included.
  - Criteria Range: This should be left blank.
  - Copy To: Choose the cell address where you want the list of unique records to be sent.
  - Unique Records Only: check this option.
  - Ok
![Screenshot (123).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1655310018641/9wOrk7qyu.png align="left")

#### Using Criteria
Excel Advanced Filter may be used to filter records based on a set of criteria.

1.  Specify the criteria for which you want to filter the data.
2. Select the entire source data (data set).
![Screenshot (124).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1655311361509/SQgFvUF0u.png align="left")
3. Data tab –> Sort & Filter –> Advanced.
>This will open the Advanced Filter dialog box.
(You can also use the keyboard shortcut – Alt + A + Q).
4. In the advanced dialog box 
![Screenshot (125).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1655311427284/NyVey3Uxg.png align="left")
  - Action: Select the ‘Copy to another location’ option. 
  - List Range: Make sure it corresponds to the dataset you're looking for unique records in. Also, ensure sure the data set's headers are included.
  - Criteria Range: Specify the criteria we established in the previous steps.
  - Copy To: Choose the cell address where you want the list of unique records to be sent.
  - Unique Records Only: check this option.
  - Ok

![Screenshot (126).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1655311439584/4wQBhb_5d.png align="left")
Excel's Advanced filter allows you to build a wide range of criterion combinations.

- AND Criteria

![Screenshot (127).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1655312679170/3kMmUyTHC.png align="left")
You must provide AND criteria below the header if you wish to utilise them.

- OR Criteria

![Screenshot (128).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1655312692664/oIq4Dh9aT.png align="left")
You must put the criterion in the same column if you wish to utilise OR criteria.

> *Criteria listed on the same row are linked by the "AND" operator and criteria listed on different rows are linked by the "OR" operator.*

### Using WILDCARD characters
When creating criteria in Excel Advanced Filter, you may also use wildcard characters.

|wildcard|description|
|---|---|
|* (asterisk)| It represents any number of characters|
| ? | It represents one single character|
|~| It is used to identify wildcard in the text|


#### For *
1. Select the cells you wish to filter.
![Screenshot (129).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1655314012563/yxyfG1b_n.png align="left")
2. Select Data –> Sort and Filter –> Filter (Control + Shift + L on the keyboard).
3. In the header cell, click the filter icon.
4. In the field (below the Text Filter option),type *a
![Screenshot (130).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1655314060191/nFodeGLWu.png align="left")
5. Ok
![Screenshot (133).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1655314741408/f4mp7_O1q.png align="left")

#### For ?
1. Select the cells you wish to filter.
![Screenshot (129).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1655314012563/yxyfG1b_n.png align="left")
2. Select Data –> Sort and Filter –> Filter (Control + Shift + L on the keyboard).
3. In the header cell, click the filter icon.
4. In the field (below the Text Filter option),type ?????
![Screenshot (132).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1655314314230/X3qJuSbwx.png align="left")
5. Ok
![Screenshot (134).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1655314435634/28Co-Ahan.png align="left")

#### For ~
1. Select the cells you wish to filter.
![Screenshot (129).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1655314012563/yxyfG1b_n.png align="left")
2. Select Data –> Sort and Filter –> Filter (Control + Shift + L on the keyboard).
3. In the header cell, click the filter icon.
4. In the field (below the Text Filter option),type 
![Screenshot (131).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1655314520625/M4KLp0qfq.png align="left")
5. Ok
![Screenshot (135).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1655314602749/ZmFuH0un-.png align="left")

#### NOTE :
1. Remember, the headers in the criteria should be exactly the same as that in the data set.
2. Advanced filtering cannot be undone when copied to other locations.
3. The criteria range can be on the same sheet as the data, or on a different sheet.

> When copying the filtered date from sheet 1 to sheet 2, keep the sheet 2 active. 

#### Acknowledgement 
This blog simply represents my own ideas and opinions (based on my limited knowledge) and should not be used as a replacement for legitimate sources. I'd welcome corrections in the comments if I ever make a mistake or if you disagree!

#### End note 
These were the things that I was able to explore today, and I am looking forward to learn more. If you have any further information on the aforementioned concepts, please share it in the comments section below. Don't forget to connect me on [Twitter](https://twitter.com/datanomadd) and [Github](https://github.com/Lourdemary/100_Days_Of_Data).

Have a great time !