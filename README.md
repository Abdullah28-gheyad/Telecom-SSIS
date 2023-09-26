# Telecom-SSIS

--Telecom Company :
- The company has a system that saves a CSV file periodically, every 5 minutes. This file includes basic data for the various movements made by customers during a specific period of time.
- The company has provided you with the following table, which shows the data stored in the csv file

-Provided Data & Types 

  -  ![Provided Data overview](https://github.com/Abdullah28-gheyad/Telecom-SSIS/blob/master/Screenshot%202023-09-26%20201857.png) 


- The processing required to be completed on this data before it is stored in the database

  -  ![processing required overview](https://github.com/Abdullah28-gheyad/Telecom-SSIS/blob/master/processing_table.png)
 
  -  Rejected transactions will be stored in a separate table, with the original csv file name recorded
  -  During the process of recording data in the database, there are some additional data that are required to be recorded to ensure the quality of the data storage process
Number of animations in the csv file
The number of transactions stored in the database
The number of transactions rejected because the required conditions were not met
Link the data stored in the database with the original csv file

- After completing the process of storing data in the database according to the previous conditions, move the csv file to another folder


SSIS Data Flow 

  -  ![Data Flow overview](https://github.com/Abdullah28-gheyad/Telecom-SSIS/blob/master/Screenshot%20(55).png)


-- Before Running the ETL


  -  ![Before Running overview](https://github.com/Abdullah28-gheyad/Telecom-SSIS/blob/master/Screenshot%20(54).png)



-- After Running the ETL


  -  ![After Running overview](https://github.com/Abdullah28-gheyad/Telecom-SSIS/blob/master/Screenshot%20(56).png)
