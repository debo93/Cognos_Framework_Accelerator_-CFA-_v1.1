# Cognos_Framework_Accelerator_-CFA-_v1.1
This Code base is written using python 2.7. It basically accelerates the creation of packages in Cognos Framework Manager, creating the Database Layer where the objects are imported along with joins and table description. It also conatins the usage properties of each columns of each table. Then the Business Layer is built where the tables are grouped into meaningful subject areas, and giving all the columns a meaningful business name. Then the presentation Layer is created along with the package which can be directly published to IBM Cognos Report Studio to create Reports over the exposed package.

Steps to work with the Code Package : 

1. First Create the Folder Structure as depicted in the .PNG File.
2. Following is the Folder Structure and it's components : 
        
        CFA_v1.1
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
          
