# Math 1500 Result Extraction from CrowdMark

The Jupyter notebook is intended to help the TAs in Department of Mathematics at University of Manitoba in the extraction of results for Math 1500 term tests. It automatically produces the excel files for all the sections within a particular group. 


# Files and Important Notes
- It is super **important** that the files downloaded from Crowdmark follow the naming convention: **term test #.csv** . For example, the group file for term test 7 should be named 'term test 7.csv' .
- Also, the code only generates the results of the sections within the same group. Files corresponding to more than one groups should **NOT** be present in the working directory. The working directory should only contain the .csv files downloaded from Crowdmark (of the same group) and the Jupyter Notebook (1500-extraction.ipynb).




##  Installing packages/libraries
The packages used in the code are pandas, numpy and openpyxl. Note that pandas and numpy are generally pre-installed in python. If not installed, then one can use the following commands in the terminal to install them:

- <code>pip install numpy</code>
- <code>pip install pandas</code>
- <code>pip install openpyxl</code>

Alternatively, they all can be installed from Anacondas Navigator.


## Running the Jupyter Notebook
One has to open the jupyter notebook and then just run every cell by pressing <code>shift + return</code>.  When one runs the last cell (main()), it will ask to enter the number of csv files in the working directory (i.e., the term test #.csv files). If one has term test 1.csv to term test 7.csv, then **7** must be entered, and **nothing else**,

--------------------------------------------------------
### To the TAs 
Hopefully, this takes some load off from you guys wherein before, you had to manually search, copy and paste the results from all the files to one main excel file for your section and now everything has been automated for you. Comments and suggestions to further enhance the code/include more cases are always welcome.
