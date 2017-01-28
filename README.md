# Statistics for a few Wikipedias.

These are slightly edited copies of Zachtes statistics [Monthly counts &amp; Quarterly rankings: December 2016](https://stats.wikimedia.org/EN/TablesWikipediaNO.htm) for Norwegian (bokmål) Wikipedia and a few other Wikipedias, and some additional statistics. The table is created by selecting the actual rows from the table, and then copying the _code_  for those rows. A header and footer is recreated, numbers for table cells corrected, and some confusing additions removed. This is the html-file in the repo.

The slightly edited file is then imported into LibreOffice Calc, and sorted in ascending order. Each data column are then moved into separate sheets together with a copy of the date column.

Two columns are then added for _stdDev_ and _mean_, each accumulated over 12 months. By accumulating over one year most of the effects from hollidays are removed. The year is accumulated up to the last month in the year. Note that this will give a delayed skew because it is a plain moving average, and the standard deviation will be slightly higher than expected. Still this is statistically correct.

A third column is then added for lower bound of one standard deviation, aka the 34/68 % limit, and a fourth colum for a one year difference over the mean. Even if the delayed skew is notable for the mean the difference should be pretty close to the expected for stable values.

The graphs is a plain mapping of the column values. Only some of the graphs are exported from LibreOffice, and then only as png-files. Other files might be created when necessary.

To get the file without using git click "Clone or download" and then "Download ZIP". Open the file localy and extract the file.

Note thet the xlsx-file is a separate dump from LibreOffice and may contain errors.
