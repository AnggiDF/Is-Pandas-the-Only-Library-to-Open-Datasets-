# Is-Pandas-the-Only-Library-to-Open-Datasets-
Opening various kind of datasets. 

Data have various types since there is a lot of source can be extracted to informative and knowledgeable dataset. There are a lot of data types, such as xlsx, txt, API, json, CSV, TSV, http, zip, twitter, and so on. But before we process it, we should understanding the data to choose useful one. In this time, I want to share how to read some various data types in Python.

1. Application Programming Interface (API)

Application Programming Interface (API) is an interface that allows computer interact with users. To open API file, we must import request library to open data in python. In request library, the URL and header of data should be clearly stated. This data statement used to get request of data so data will be opened. After that, data should be changed to Json format to make Pandas library read the data.

2.  Website URL

To open data from website, we should know where the table we want to opened so we can find its link. This link can be check in developer tools. Same like open API, we should import Request and Pandas library to open it. But, we should import Beautifulsoup too to find that table and its specific website code. We also should make our frame to put that data to dataset.

3. Text File (TXT)

Text file is a file contain document form. This kind of data sometimes contain tabular format but still in the document form. We can extract it using Pandas library. In Pandas, there are 2 ways to open it, read() used when just want to read the file like its form, read_fwf() used when to open the file on dataframe.

4. Zip File

Zip file is a file contain lots of file and compressed them to lower size one. In Python, we can open zip file using Zipfile library to extract that zip file. We should specify where is data come from (sometimes data from website and local disk). We can use Pandas library to open some type of data in zip file. The data can be read in Pandas library like txt, csv, tsv, xlsx, etc but pictures data can be read using OS library.

5. Excel File (XLSX)

Like CSV file, excel file (XLSX) has a table form. This data can be read only using Pandas library. We should specify too what excel data want to opened.

6. List Data

List is one of a simple data. To open it just need Pandas library and the result will be like table data.

7. Dictionary Data

Another simple dataset is dictionary. We just need Pandas library to open it and will be a table dataset.

8. Numpy Array (2D)

Last simple dataset is numpy array (2D) form. We can read it only using Pandas library and also will be a table form.


In the end, Pandas library is so useful library to open some of various data. This is initial step to presents data more informative and knowledgeable.
