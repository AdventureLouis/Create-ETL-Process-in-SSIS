I will show you how to implement ETL Processes in SSIS,in this exercise I will unravel different data-cleaning steps.
<br>
You will discover how you can implement data cleaning during the extraction process, during the load process, and after the load process and finally transform

However, it turns out that in real-world datasets, sometimes only ETL is not enough to have clean data that is ready for analysis, 
and as a result, the whole process that I used for arriving at clean data is represented in diagram below :

![SSIS_Project_Architecture](https://github.com/AdventureLouis/Create-ETL-Process-in-SSIS/assets/161846069/6a34f772-2700-45f4-abf9-af60491aee4f)

It is important to note that data cleaning will be implemented in each stage above. The last transform above will be used to perform the final cleaning after the data has been loaded into the database
### About Dataset
The dataset used in this publication comes from Amazon Sales Data, which can be found in the data.world and below is the link to the site
https://data.world/sanskritidsai/amazon-sales-data?source=post_page-----9667699d38eb--------------------------------
The raw dataset can be found below👇
https://raw.githubusercontent.com/Louis192/Data_1/main/Original_amazon.csv
and the below is a screenshot of the raw dataset on excel

![Original_Dataset](https://github.com/AdventureLouis/Create-ETL-Process-in-SSIS/assets/161846069/f4e77f0e-1ba6-489b-93a4-8fcde836dded)


