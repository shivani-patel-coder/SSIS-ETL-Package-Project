# SSIS-ETL-Package-Project
Created basic ETL Project using SQL Server Management Studio and SQL Server Integration Services
The data pipeline basically flows in following manner:
Data will be extracted from Demo CSV file and will be transferred (Using SSIS) into an empty table ("RepPerformanceTargets") located in AdventureWorks database (SQL Server Management Studio).
The Demo ETL Package is also deployed in SQL Server for future updates.
To get refreshed data every time, I also utilized "Execute SQL Query Task" in SSIS to truncate table data everytime new data is uploaded in database.
Control Flow in SSIS

![Control Flow in SSIS](https://user-images.githubusercontent.com/75600348/121791039-654ed780-cb9a-11eb-917b-f489620ac400.JPG)

Data Flow in SSIS

![Data Flow in SSIS](https://user-images.githubusercontent.com/75600348/121791069-bbbc1600-cb9a-11eb-8da5-a52ac3d8227f.JPG)

OLEDB Destination Connection Sneakpeak!

![SSIS OLEDB Destination Connection Sneak Peak](https://user-images.githubusercontent.com/75600348/121791258-d1323f80-cb9c-11eb-82c0-3c34bc27d41a.JPG)

Demo CSV File

[CSV File overview](https://user-images.githubusercontent.com/75600348/121791072-c8d90500-cb9a-11eb-8ea4-e7063a379ae8.JPG)

ETL Run Success

![ETL Run Successful](https://user-images.githubusercontent.com/75600348/121791182-f7a3ab00-cb9b-11eb-9fec-03f9a56123d7.JPG)

SQL Server Run

![Data Transferred Success](https://user-images.githubusercontent.com/75600348/121791211-47827200-cb9c-11eb-8a29-dfe0be96c4cc.JPG)

