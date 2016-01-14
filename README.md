### Dabuntu
EventShop is used for Personalized Situation Detection and Control by combining heterogeneous web streams. Data streams generated by social media, sensor networks, internet of things, and digitalization of transactions provide us with abundance of data which when analysed will provide us with valuable data which can be used to detect patterns to notify when a particular situation occurs.

### About Us
Above Solutions, Inc. is a company which believes in an “Innovative Team Delivering Transformative Solutions”. Established in 2008, ABOVE Solutions, Inc. combines a passion for technology and customer satisfaction to deliver transformative solutions that create economic and social value. 
We have contributed to Eventshop making in scalable, robust and support a wide range of data formats.
Above Solutions Inc. was founded by Poonacha Machaiah.

### Contact Us
http://above-inc.com/
http://dabuntu.com/

### Data Ingestion Layer
Data available in the Internet is of different formats and it has to be unified to a common format. The solution provided is to convert it into STT (Space Time Theme, STT) format. 
The data is then converted to a two dimensional grid called the Emage.
Any CSV, Json, Xml or twitter data source can now be converted to a STT format using eventshop.
Once the data sources are created, different spatio-temporal like min, max, average, sum, majority, split uniform, linear_interpolation. 

### Rule Engine
The rules engine is used to query the data stored by the data source. The rules engine is a mongo specific implementation but can be changed for any other kind of Database.

The idea of the rule engine is to query the data stored in the DB. The fields required as an output should be specified in the Extract Field.
Select the field in which you want to query and select the query operator and specify the parameters as a comma separated value.
The query operators populated depend on the data type specified in the data syntax when configuring the Data source.

### Query Processing Framework
A Query Plan tree is constructed to perform the different operations on the emage generated. The query tree is parsed to check if it can be executed in an asynchronous manner and events are generated to perform each query operation. 

### Alert Framework
Alert Framework is used to set up notify any abnormal conditions in the raw data or transformed data. Alerts can be created either on Query or Data Source and can be also be created to provide any solution if any.

### DB setup

Run the sql files in 

https://github.com/dabuntu/es/blob/master/EventshopJava/src/main/resources/Sql/Eventshop/eventshop.sql

and the sql files in the following folder in the same order

https://github.com/dabuntu/es/tree/master/EventshopJava/src/main/resources/Sql

### Wiki

The installation setup and a detailed description is available in the Wiki

https://github.com/dabuntu/es/wiki
