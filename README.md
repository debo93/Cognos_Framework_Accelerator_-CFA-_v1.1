# CFM_Accelerator_-CFMA-_v1.1
This Code base is written using python 2.7. It basically accelerates the creation of packages in Cognos Framework Manager, creating the Database Layer where the objects are imported along with joins and table description. It also conatins the usage properties of each columns of each table. Then the Business Layer is built where the tables are grouped into meaningful subject areas, and giving all the columns a meaningful business name. Then the presentation Layer is created along with the package which can be directly published to IBM Cognos Report Studio to create Reports over the exposed package.

## Steps to work with the Code Package : 

## First Create the Folder Structure as depicted below :

        CFMA_v1.1
          |
          |--- Code_Base
          |       |---Cognos_Metadata_Generator.xlsm
          |       |---CSA_v1.1.pyc
          |
          |--- Input
          |       |---Input_parameters.py
          |       |--- <Input_metadata_file>.csv
          |
          |--- Output (Here you will get the output along with timestamp added to each output)
          |
          |--- CSA v1.1.exe

## Then give the inputs in the Input Folder : 
        2.1. Input_parameters.py : metadata path, project name, database name, schema name, report studio path
        2.2. <Input_metadata_file>.csv : table names, column names, data type, precision, scale, alias/business name of columns,relationships between the tables, subjects areas of the table, table description, column usage properties. 

## If the metadata and the input parameters file is properly filled and validated, run the .exe file and the package will be generated along with some customizables included in the package.
