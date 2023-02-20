Title: investigating the relationship between economic factors (GDP, income class) and Mortality 
                                    rate in more than 100 countries

1- Program application:
This program is used to prove the following hypothesis:
Is economic factors such as GDP and income class can have any impact on mortality rate in a group 
of countries?
 
2- Program parts:
This program is designed like a story. So, between coding parts one can find some texts. In order 
to understand the trend of the code, the reason behind the choosing analysing methods, and using these
statistical methods one can read the mentioned paragraphs. 

this program contains one module that contains 5 subparts:
   A- Data loading: Contains two functions. This part get the name of the data files and store 
      the files into three dataframes. 
   B- Data Inspecting: Contains one function. This part inspect all the datasets of the program 
      and evaluate some of their properties.
   C- Data Wrangling: Contains eight function. This part is dedicated to combine all the dataset 
      to make a unify data set for further investigation and inspect it. Also, in this part the
      main dataframe is divided into two main dataframe for each class of interest (Lower income 
      class and upper income class). Finally, intrapolation and extrapolation techniques are used 
      to deal with null data points.
   D- Presenting Data: This part contains all the functions for plotting data sets and presenting 
      them in a proper manner. Contains seven subparts:
	1- Assistant functions: Contains four functions that are used in other parts of this program.
        2- Widgit Functions: contains three functions each of them make a different widgit.
        3- Line Plot Function: Contains two functions that are used in line plots.
        4- Bar Plot Functions: Contains two functions that are used in bar plots.
        5- Map Functions: Contains two functions that are used in maps.
        6- GDP Plots: Contains five functions that are utilized in sketching a different plots.
        7- Mortality Plots: Contains five functions that are utilized in sketching a different plots.
   E- statistical part: this part is used to approve or disapprove the hypothesis. Contains two 
      subparts:
	1- Statistical Functions: Contains five functions that are used in implementing different
	   statistical approaches and tests.
	2- Hypothesis Assessment: in this part by using the statistical functions the mentioned 
	   hypothesis is evaluated and different statistical aspects of the data sets are presented.
   
   Data Sets:
   1- GDP data: 
      Name: API_NY.GDP.MKTP.CD_DS2_en_csv_v2_4770391
      From: www.Worldbank.org
      link: https://data.worldbank.org/indicator/NY.GDP.MKTP.CD
      Downloading tip: After open the link here, please download the CSV file from Download box and 
                       unzip it. Two of those files are the files that this program needs (GDP data, 
		       Class Classification Data).
   2- Class clasification data: 
      Name: Metadata_Country_API_NY.GDP.MKTP.CD_DS2_en_csv_v2_4770391
      From: www.Worldbank.org
      link: https://data.worldbank.org/indicator/NY.GDP.MKTP.CD
   3- Mortality data: 
      Name: WHOMortalityDatabase_Deaths_sex_age_a_country_area_year-Communicable, maternal, 
	    perinatal and nutritional conditions_9th January 2023 23 03
      From: www.WHO.int
      link: https://platform.who.int/mortality/themes/theme-details/MDB/communicable-maternal-perinatal-and-nutritional-conditions
      Downloading Tip: After opening the url, please click on the export data bottom on the right, 
                       then choose Full data, and regarding year bottom click on select all bottom.
                       finally click on export and wait because this process can be a little bit
                       time consuming. :) 
   4- World boarder data: 
      Name: world-countries
      From: www.kaggle.com
      link: https://www.kaggle.com/datasets/ktochylin/world-countries
      Downloading Tip: After clicking on the link, please click on the download bottom on the 
                       top-right, but first one should sign up in kaggle. Don't worry about that 
		       because Kaggle is a credible website. after subscription, please again put 
                       the download bottom and then download the file. Finally, you can use the file
                       after un zipping.

3- Challenges:
During writting this program I have faced some challenges:
   A- First and for most, the main two datasets (GDP, Mortality) come from two different resources
      ; thus, joining them with each other can cause some problems. For example, in this work, after 
      merging datasets with each other, I found that one class has just one member(low income), and
      other class has about 50 countries(high income). So, finding a proper way to over come this 
      issues was crucial.
   B- Another challenge was at the very first part of this work, and that was findig proper 
      datasets for this research.
   C- Next challenge was to find the proper visualization techniques to present the trend of variables
      correctly and Tangible.
   D- the last challenge was to find the best statistical method that completely fit the condition.
 
4- future developements:
I think the most important development in the future version of this program will be adding other 
economic factors such as GINI coefficient and also add more clinical factors such as 
hospital bed per person per country. Design a model to describe the relationship between economic 
section and health system.

5- Run and use the program:
to use this program one can download all the material in the folder on my github repository, download
the data sets from their sources and then press the run all bottom. Moreover, there are many 
descriptions and analysis in the code that is important to be red in order to find how the hypothesis
is approved.

6- Credits:
I learnt many useful tips from below links:
   A - https://www.w3schools.com/python/default.asp
   B - https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/
   C - https://github.com/rwedema/DSLS_PrepProgramming/tree/main/presentations
   D - https://fennaf.gitbook.io/bfvm22prog1/
   G - https://www.youtube.com/@DataScienceforEveryone/videos
   H - https://docs.bokeh.org/en/test/docs/user_guide/interaction/widgets.html
   I - https://docs.bokeh.org/en/latest/docs/user_guide/interaction/callbacks.html
   J - https://www.w3schools.com/colors/colors_groups.asp
   K - https://stackoverflow.com/questions/70808303/filtering-data-source-for-bokeh-plot-using-multichoice-and-customjs
and many other links that I learn many points.

you can check my github link to get access to the program. link:
https://github.com/hooman-b/Assignments_Programming1/tree/master/FinalAssignment

7- License:
This is an open source code, so I become really appreciated, if somebody improve the code.

  