##This is how you repliacate the research

-Download the data source and put into a folder on your local drive. You'll have a UCI HAR Dataset folder.
-Put run_analysis.R in the parent folder of UCI HAR Dataset, then set it as your working directory using setwd() function in RStudio.
-If you do not have the "reshape2" and "data.table" packages installed allready do that before you initiate the last step.
-Run source("run_analysis.R"), then it will generate a new file tiny_data.txt in your working directory.


##Please review the CodeBook to make sense of the data.