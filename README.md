# P450-query-pipline

This script is designed to temporarily solve the problem of slow P450 fungal database blast and limited number of submissions. Please prepare the following files before using it:

1.Download all fungal P450 sequences in the database (usually fasta files) via the Nelson website：http://p450.riceblast.snu.ac.kr/download.php?a=download；

2.Build this file as a database, compare your own sequences to it, and the result can be output in format 6. At this point, you will get the Query corresponding to each sequence, which is important, and it is through these Query that the script gets the relevant information from the database.

About blastp you can read the article ： https://blast.ncbi.nlm.nih.gov/doc/blast-help/downloadblastdata.html#downloadblastdata

3.To reduce the threshold of use, datasets are always stored in excel tables, (when preparing a dataset put its original id in the first column and query id in the second column), note that openpyxl currently only supports the .xlsx suffix.

4.Before running, you need to clarify the Headers information in the developer extension of your browser, and you need to register on the official website of P450 to get the username and password.

5.The overall framework of the code is also applicable to other scenarios, and changes can be made according to the actual situation.
