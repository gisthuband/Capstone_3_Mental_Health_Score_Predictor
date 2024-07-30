Capstone 3 Project: Mental Health, Race, and Unemployment during Economic/Health Crisis, COVID-19

Mental health is paramount to the success of a society.  An economic/health crisis like COVID-19 threatened the mental health of all people in the US, however, due to systemic racism, different racial groups within the US are disparately impacted by crisis.  

By using a mental health score predictor, mental health predictions could be made for different racial groups within America based on unemployment statistics and racial group; this kind of information could be used to assess devastation and prepare mental health resources to soften the toll societally.

Contents of Project:

Data: [https://github.com/gisthuband/Capstone_3_Mental_Health_Score_Predictor/tree/main/data](url)

This section contains two datasets: one from the NCHS (National Center for Health Statistics) and one from the BLS (Bureau of Labor Statistics).  The NCHS contaings information on mental health survey scores from 2020 to 2022.  The BLS data containing unemployment rates and unemployment numbers from 2019 to 2022.

Data_Wrangling: [https://github.com/gisthuband/Capstone_3_Mental_Health_Score_Predictor/tree/main/data_wrangle](url)

This section contains the data wrangling phase of the data science life cycle.  All of the data was merged and tidied into one dataframe ready for analysis.  The dataframe resulting from this section contains around 700 observations of mental health scores, for each, racial group, date, mental health test indication, unemployment rate change of racial group and year, and unemployment number of the racial group per the year.

Exploratory_Data_Analysis: [https://github.com/gisthuband/Capstone_3_Mental_Health_Score_Predictor/tree/main/exploratory_data_analysis](url)

In this section, the data was visualized and statistical test were performed to assess the relationships and patterns within the data.  It was found that regression could be a viable option for the dataframe.  

Preprocessing: [https://github.com/gisthuband/Capstone_3_Mental_Health_Score_Predictor/tree/main/preprocessing](url)

In this section, a preprocessing class was constructed that could standardize and split data into test and training data.  It could also generate random score data, to assess whether or not the models are behaving due to luck.

Modeling: [https://github.com/gisthuband/Capstone_3_Mental_Health_Score_Predictor/tree/main/modeling](url)

In this section, eight machine learning regression models were deployed and tested, yielding a table of R squared values and root mean squared error.  Following the result assessment, a function was made that had an input of race, indication of mental health status, unemployment rate change within race, and total unemployed change within race (all generated randomly).  The mental health scores (0-48 according to the GAD7 andf PHQ9 tests) were then predicted with the input.

Final_Report_and_Presentation: [https://github.com/gisthuband/Capstone_3_Mental_Health_Score_Predictor/tree/main/final_documentation_and_presentation](url)

This folder contains the final written up report and the presentation of the findings for stakeholders.

Future Work:

Need more data from previous economic crises, like the housing crisis in 2008 which was followed by the 2009 H1N1 pandemic.  If possible, data on the medical expenses associated with poor mental health could be used to further assess risk and the importance of implementing preventative resources for mental health in the US.

