# Education Inequality

# Purpose: 
This project will address education opportunity inequality in U.S. high schools, specifically regarding average student performance on the ACT or SAT exams for college applications, in order to investigate whether performance is predicted by socioeconomic factors.

# Data: 
This project will use two data sets - The first is EdGap_data.xlsx from [EdGap.org](https://www.edgap.org/#5/37.875/-96.965) in 2016, and contains data about average ACT scores, SAT scores, and socioeconomic characteristics for schools in several districts. The second data set is ccd_sch_029_1617_w_1a_11212017.csv is from the National Center for Educational Statistics https://nces.ed.gov/ccd/pubschuniv.asp, and has more basic data about each of these schools. 

NCES data set: https://www.dropbox.com/s/lkl5nvcdmwyoban/ccd_sch_029_1617_w_1a_11212017.csv?dl=0

# Data Preparation: 
Within the Ed Gap data set and the school info data set, we convert the data types of variables so that they will match, and then drop sections of each data set that aren't relevant to the question. The two data sets are then joined, and an imputer is used to create values to replace any missing entries of predictor variables. Data frame is separated into training and testing data sets. Data prep is done in Maxine_Lanier_Education_Inequality_Data_Preparation.ipynb . Resulting clean files are df_train and df_test.

A new subset of data to analyzed, household size, was added, and the data preparation file was updated. 2016 and 2017 census data with the number of households of each size (1, 2, 3, 4+) by zip code. Excel sheets for 2016 and 2017 were downloaded from the US Census Bureau: https://data.census.gov/table?q=household+size+zip+code&g=010XX00US$8600000&tid=ACSST5Y2016.S2501 Extraneous rows and columns were removed from the 2017 sheet and saved as EditedData.csv. New data prep file with added subset is Maxine_Lanier_Education_Inequality_Data_Preparation_Added_Subset.ipynb. df_train and df_test were updated to include additional data. 

# Author:
Maxine Lanier
# Liscence: 
Anyone may use.
