# JSONtoVirtual
How to make a virtual list from JSON
-
FileMaker ver16~

DEMO file: fetch.fmp12

How to use it

1.Specify the url from which you get the JSON

2.Run 'Insert FROM URL' script

3.Specify the target node of JSON where you want to convert to virtual list

4.Specify keys you want to include into the virtual list(comma separated)

5.Click the 'Go Virtual List' button


*Pay attention:
All Fields of VirtualList are same calculation formula.
It doesn't depend on hard-coded key names.
In short, it's DRY.

Sample File: fetch2.fmp12
--> 1 table, 1 field for Virtual List

Sample File: fetch3.fmp12
--> Analyze JSON(Virtual List) data by ExecuteSQL