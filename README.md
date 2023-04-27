# Education Inequality

Purpose: This project will address education opportunity inequality in U.S. high schools, specifically regarding average student performance on the ACT or SAT exams for college applications, in order to investigate whether performance is predicted by socioeconomic factors.

Data: This project will use two data sets - The first is EdGap_data.xlsx from [EdGap.org](https://www.edgap.org/#5/37.875/-96.965) in 2016, and contains data about average ACT scores, SAT scores, and socioeconomic characteristics for schools in several districts. The second data set is ccd_sch_029_1617_w_1a_11212017.csv is from the National Center for Educational Statistics https://nces.ed.gov/ccd/pubschuniv.asp, and has more basic data about each of these schools. 

NCES data set: https://www.dropbox.com/s/lkl5nvcdmwyoban/ccd_sch_029_1617_w_1a_11212017.csv?dl=0

Data Preparation: Within the Ed Gap data set and the school info data set, we convert the data types of variables so that they will match, and then drop sections of each data set that aren't relevant to the question. The two data sets are then joined, and an imputer is used to create values to replace any missing entries of predictor variables. Data frame is separated into training and testing data sets. Data prep is done in Maxine_Lanier_Education_Inequality_Data_Preparation.ipynb . Resulting clean files are df_train and df_test.
