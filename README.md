# Census-2011-data-analysis-for-India


Python packages required to successfully run assign1.sh:


-csv: Used for writing in csv file


-pandas: Used for handling dataset


-numpy: Used to perform vaious mathematical operation in array


-scipy.stats: Used for finding p-value using t test


-xlrd: For dealing with some older version of the excel files (.xls)


-warnings: For handling warnings


Some info regarding approach:


Q1-------------------------------------------------------------
Data file used- C-18 and population data from assignment1


Output file- percent-india.csv
   
   
Q2-------------------------------------------------------------
Data file used- C-18 and population data from assignment1


Ratio used- male:female for calculating p-value


Test Used- t test for calculating p-value


Output file- gender-india-a.csv, gender-india-b.csv,
             gender-india-c.csv


Q3-------------------------------------------------------------
Data file used- C-18 and population data from assignment1


Ratio used- rural:urban for calculating p-value


Test Used- t test for calculating p-value


Output file- geography-india-a.csv, geography-india-b.csv,
             geography-india-c.csv


Q4-------------------------------------------------------------
Data file used- C-18 and population data from assignment1


Output file- 3-to-2-ratio.csv, 2-to-1-ratio.csv


Output file columns- (state-code,ratio-3-to-2)
                     (state-code,ratio-2-to-1)
   
   
Q5-------------------------------------------------------------
Data file used- C-18 and C-13(for finding age-group wise population)


Output file- age-india.csv 


Q6-------------------------------------------------------------                   
Data file used- C-18 and C-08(for finding literacy-group wise population)


Didn't consider literate as a literacy group since in data file it 
has more finer divisions 


Output file- literacy-india.csv 


Q7-------------------------------------------------------------
Data file used- C-17 statewise data file


Discarded OTHERS LanguageName as it will be different for 
different states.


Output file- region-india-a.csv,region-india-b.csv 


Q8--------------------------------------------------------------
Data file used- C-18 and C-13(for finding age-group wise population)


Output file- age-gender-a.csv, age-gender-b.csv, age-gender-c.csv


Q9-------------------------------------------------------------- 
Data file used- C-18 and C-08(for finding literacy-group wise population)


Didn't consider literate as a literacy group since in data file it 
has more finer divisions 


Output file- literacy-gender-a.csv, literacy-gender-b.csv, 
             literacy-gender-c.csv 
  
  
----------------------------------------------------------------              
I used state-code in all the questions related to state/ut.


Steps for running the assign2.sh:


1)Download 21111049-assign2.zip from githhub.


2)Unzip it


3)Make working directory as folder - '21111049-assign2'


4)Use command -> sh assign2.sh to completely run assignment1


Estimated execution time:44 sec
