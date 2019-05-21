# SparkSQL_DataFrames_Defoe

In this repository we have two python parsers based on [spark-xml package](https://github.com/databricks/spark-xml) for ingesting XML documents using Spark SQL and Dataframes. Each parser ingest a type of digital texutal document. 


#### Running the spark-xml parser for [ALTO](https://www.loc.gov/standards/alto/) and [METS](http://www.loc.gov/standards/mets/) XML schemas into dataframes :

Used for ingesting Brithish Library (BL) books and Find My Past newspapers. 


    spark-submit --packages com.databricks:spark-xml_2.11:0.5.0 dataframes_alto.py
  
#### Running the spark-xml parser for reading [BL newspapers](https://www.webarchive.org.uk/wayback/archive/20140613220103/http://www.jisc.ac.uk/media/documents/programmes/digitisation/blfinal.pdf) XML schemas into dataframes :

Used for ingesting BL newspapers and Times Digital Archive newspapers:
  
 
    spark-submit --packages com.databricks:spark-xml_2.11:0.5.0 dataframes_issues.py
  
  
  
