# Pollution_in_indiana

HOSPITALIZATIONS AND POLLUTION IN INDIANA
Revathi Duggineni, Akshita Venkat Patri, Harini Suram, Sahithi Bhavana Vallabhaneni,
Shiva Vinjamoori, Natalie Barnes
Indiana University - Purdue University, Indianapolis, IN 46202, USA.
rduggine@iu.edu, akspatri@iu.edu, hsuram@iu.edu, svallab@iu.edu, svinjamo@iu.edu,
natabarn@iu.edu

Abstract:
We analyzed three separate data sets in this study to determine whether there existed a
relationship between the air quality index and EMS (emergency medical services) from 2015 to
2018. We discovered rejection of the null hypothesis using techniques such as logistic regression
and data analysis tools such as Naive Bayes, XG Booster, Random forest classifier, and SGD
classifier. We feel that many other reasons could be causing the high number of hospitalizations,
so we encourage more research on this topic using multiple data sets and features.
<br>

Keywords:
EMS, AQI, Ozone, Python, SQL, machine learning, data cleaning, hypothesis testing, MS Excel,
Tableau, CSV file, Kruskal Wallis.
<br>

Project Scope:
1.1 Introduction:
In 2013, air pollution was classified as a cancer-causing agent and contributor to chronic
diseases (Air Pollution and Your Health, 2021). Air pollution is created from several origins,
including natural and human. Human-originated resources include natural gas, fuels, vehicle
emissions, and coal-powered plants (Air Pollution and Your Health, 2021). Natural gases from
organic matter include methane, volcanic eruptions, and wildfire smoke (Air Pollution and Your
Health, 2021). The effects of pollution on health have been documented to increase emergency
room visits and hospitalizations, premature deaths, and decreased lung functioning, such as
asthma (Air Pollution, 2020). Health-related costs have exceeded $6.5 billion in the United
States of America based on ozone levels between the years 2000-2002 (Air Pollution, 2020).
The United States boasts some of the cleanest air globally. Still, much work is yet to be done
with an increased population, which often positively correlates with increased consumption
(Breathe a Little Easier, 2020). The Breath a Little Easier (2020) project monitors air quality,
intending to improve air quality over time. This project mentions that lower-income areas are
poorly affected by industrialized organizations but does not specify if they refer to industrialized
countries or regions. This study will further establish correlations between areas, pollution, and
emergency medical systems (EMS) calls in the state of Indiana.
<br>

1.2 Aim:
● To find the alliance between EMS (Emergency Medical Systems) calls Fine Particulate
Matter, air pollution, and corresponding CO, NO2, and ozone levels in Indiana.
● To find any correlation present between the levels of CO, NO2, Ozone, and Particulate
Matter 2.5 (PM 2.5) and EMS calls for heart stroke, weakness, malaise, nausea, chest
pain, or respiratory distress.
● Identify any retrospective trends to any pollutant levels to predict future levels.
<br>

Hypothesis:
Null Hypothesis: There is no association between AQI (Air Quality Index) of PM2.5, CO, NO2,
Ozone, and health emergencies. There is no trend of pollutants present by day.
Alternate Hypothesis: There is an association between AQI (Air Quality Index) of PM2.5, CO,
NO2, Ozone, and health emergencies. There are trends for pollutants present by day.
<br>

Tools:
Python package for calculating the Air Quality Index, Pandas for data manipulation and
data cleaning, Tableau for adding visual features in the form of pie charts or tables, MySQL and
Python to perform data cleaning and extraction.
Merging of tables was done through Pandas. To calculate the AQI values for each pollutant for
each day from the dataset, the Python package python-AQI 0.6.1. was called.
EMS (Emergency Medical Services) data from 2015 - 2018 was downloaded in order to filter
the data for which only calls that occurred for symptoms like chest pain, respiratory distress,
nausea, malaise, and heart stroke (as provided by the EMS provider) were considered.
Then, both the tables, EMS and the pollutants' tables, were loaded into SQL to perform the
functions of SQL.
<br>

Type of study:
This will be a retrospective cohort study with a focus on time between the years 2015 and
2018. All measurement aspects of the study: location, air pollution, and EMS calls, will need to
reflect this timeline, as available.
<br>

1.3 Purpose:
Pollution is a worldwide problem affecting the health and lives of all people. This study
is to use previously recorded data and apply it to predict future effects of pollution using machine
learning.
<br>

2 Methodology:
2.1 Steps of the Project:
The following procedures and methods were used to estimate the concentrations of
pollutants in the years 2015 and 2018.
● We searched for data effectiveness, read alternative literature evaluations, and debated the
work's validity.
● Exploration of research questions and the formulation of null and alternative hypotheses.
● Python and MySQL were used to gather, load, and extract data.
● Data cleaning, transformation and extraction, Python, SQL, and Machine Learning -
essential tools for data collection.
● Cleaning data with (Python, MySQL, Machine learning).
● Data modeling and exploratory analysis.
● Test statistics and hypothesis testing, correlation and regression, and comparative studies.
<br>

2.2 Team members’ responsibility:
Because everyone on the team comes from a different background, working together on a certain
project appears to be quite difficult, even though the tasks are distributed among us.
Name Background (including experience with SQL and
Python)
Responsibilities
Revathi
Duggineni
Bachelors in Pharmaceutical Sciences. Little idea
about SQL. Manageable with Python.
Reporting,
Proofreading, and
Presentation
Akshita Venkat
Patri
Bachelors In Computer Science Engineering.
Worked on backend codes using Django (a Python
web framework), as well as on SQL server for
developing web applications.
Python, SQL, Tableau,
Machine Learning
Harini Suram Bachelors in Dentistry. Novice to SQL and Python Data importing, SQL,
reporting, data
pre-processing
Sahithi
Bhavana
Vallabhaneni
Bachelors in Pharmaceutical Sciences. Beginner in
SQL and Python.
Reporting,
proofreading and
presentation
Shiva
Vinjamoori
Bachelors in Pharmaceutical Sciences. Good with
SQL. Learner in Python.
Proofreading and
presentation
Natalie Barnes Bachelor’s of Science in Nursing-- Novice to SQL
and Python.
Machine learning,
Python, SQL, data
cleaning, Tableau,
project manager
<br>

2.3 Actual Contributions from Individual Team Members:
Based on the project proposal, we divided responsibilities as shown in the table above,
but after understanding each team member's strengths and weaknesses, we decided to make
changes. As a result, the table below explains the specific responsibilities of the team members.
Name Background Responsibilities
Revathi
Duggineni
Bachelors in Pharmaceutical Sciences. Little
idea about SQL. Manageable with Python.
Reporting, Proofreading and
Presentation, Slide Show
Akshita
Venkat patri
Bachelors In Computer Science Engineering.
Worked on backend codes using Django (a
Python web framework), as well as on SQL
server for developing web-applications.
Python, SQL, Machine
Learning, Slide Show,
Presentation
Harini
Suram
Bachelors in Dentistry. Novice to SQL and
Python
Data importing, SQL, Data
Pre-processing, Python,
Tableau, Slide Show
Sahithi
Bhavana
Vallabhaneni
Bachelors in Pharmaceutical Sciences.
Beginner in SQL and Python.
Reporting, Proofreading, Slide
Show
Shiva
Vinjamoori
Bachelors in Pharmaceutical Sciences. Good
with SQL. Learner in Python.
Proofreading and Reporting
Natalie
Barnes
Bachelor’s of Science in Nursing-- Novice to
SQL and Python.
Data Cleaning, Machine
Learning, Python, SQL,
Tableau, Data Cleaning,
Project Manager, Reporting,
Slide Show
<br>

2.4 Project Challenges:
Group 6 did a fantastic job of establishing the endpoint on time, but each project has its
own set of advantages and disadvantages. People in our group come from various backgrounds
and only have a rudimentary knowledge of the programming languages in question. We worked
very hard to learn new things and put them into practice in the project.
Our team members are friendly and motivated, which allows us to produce better results. We
held several meetings to better understand how to work together. Our project has an online
member with whom we took the sections every week and discussed the project deliverables.
The entire procedure is broken down into several steps, beginning with data collection and the
final result. The initial setup of MYSQL and Python took a long time, as the number of rows in
the table is limited.
<br>

3 Data collection:
Gathering data is a huge task so we have chosen tools like Python and MySQL for sorting
and extraction of data for which our team members started the project by uploading the files of
medical services, air quality, and hospital directory to MySQL with an appropriate number of
rows.
We utilized the datasets from sites like Medical Services Runs dataset,
https://hub.mph.in.gov/dataset/emergency-medical-service-runs.
The files from this dataset are:
Emergency_medical_service_runs_2015
Emergency_medical_service_runs_2016
Emergency_medical_service_runs_2017
Emergency_medical_service_runs_2018
This is the data set for the AIR DATA:
Download Files | AirData | US EPA
Annual_aqi_by_county_2015.zip
Annual_aqi_by_county_2016.zip
Annual_aqi_by_county_2017.zip
Annual_aqi_by_county_2018.zip
Hospital Directory to extract hospitals mentioned in the EMS calls and match them with the
county they are located in:
Hospitals | Provider Data
Catalog (cms.gov)MIS/hosdir/wdirhos.htm
As the hospital directory only mentions the zip code and not the county, to convert zip codes to
counties, the following was used:
https://wonder.cdc.gov/wonder/sci_data/codes/fips/type_txt/cntyxref.asp
<br>

Data Analysis:
Analysis was done using multiple linear regression to understand the association between EMS
calls and the pollutants mentioned above.
We also did a Kruskal Wallis (One way analysis of variance) to derive the mean difference
between levels of pollutants concerning EMS calls from 2015-2018.
<br>

Data Visualization:
Python will use the Seaborn package and Tableau to show the relationship between the top-5
cities with the highest number of EMS calls and their pollutants.
<br>

Data Description:
We read the CSV files into a Pandas data frame using Python, where we cleaned the data
and extracted the relevant features for our study. This data was then stored in the phpMyAdmin
MySQL database, where our group members could share it to perform their respective tasks
efficiently.
<br>

4 Data extraction and storage:
4.1 Data extraction:
Data extraction was conducted from several resources to address the multiple facets of the study.
The attributes selected that are of significance for the EMS datasets are:
a. DATA_INCIDENT
b. SYMPTOM_PRIMARY
c. DESTINATION_NAME
d. DESTINATION_TYPE
The attributes selected that were of significance for the annual AQI datasets are:
a. STATE
b. COUNTY
c. YEAR
d. DAYS_WITH_AQI
e. GOOD_DAYS
f. MODERATE_DAYS
g. UNHEALTHY_FOR_SENSITIVE_GROUPS_DAYS
h. UNHEALTHY_DAYS
i. VERY_UNHEALTHY_DAYS
j. DAYS_CO
k. DAYS_NO2
l. DAYS_OZONE
m. DAYS_SO2
n. DAYS_PM2
Some databases utilize hospital sites as reference points for location, whereas others use
counties, county codes, or Core-Based Statistical Area (CBSA) codes. To guarantee that we can
consistently tie in place, the EMS information must be cross-referenced from the hospital
location to zip code and from zip code to county. In the final report, the standard location
measure will be by county. To extract hospitals referenced in EMS calls and match them with the
county in which they are situated, we used the Hospital Directory.
When it was time to upload the files to SQL, multiple attempts were made, however, SQL’s
server kept giving an error that the files were too big, despite uploading them traditionally and
via the Powershell server. After these attempts, we discovered the files would upload
traditionally if the rows were limited to less than 30,000 per file. This resulted in several files
being successfully uploaded once they were divided.
<br>

4.2 Data cleaning:
Data cleaning first consisted of reviewing the CSV files and removing any unnecessary
files, reducing them to the columns specified above. Any EMS calls that did not determine a
hospital were removed from the dataset as there was no other way to know the location of the
call. As previously mentioned, specific symptoms were associated with poor air quality. If a sign
was not related to poor air quality, such as a motor accident, these symptoms or complaints were
removed from the file. The joining of the EMS calls and hospital directory file was the most
work-intensive portion as there were inconsistent names for the hospitals in the EMS files. It was
clear that the EMS calls did not have a standardized database to identify hospitals from. Before
joining the two files upon hospital names, over 150,000 entries had to be reviewed and
standardized by changing all the hospital names to those listed in the hospital directory. Names
were modified by replacing them with the formula listed in Figure 1.
Fig 1. Modified facility names to standardized nomenclature per the hospital directory file.
Once names were standardized for hospitals, the EMS logs and hospital files could be
joined by the hospital names, allowing the zip code and counties to be listed. The files were
joined based on the dates as the AQI data was a listing of one air quality value per day, and
the county was matched with the date of EMS calls and county (Figure 2).
Fig 2. Joining of tables based on dates.
In order to ease the process,we cleaned the data using mysql. The procedure went as follows:
we divided each data set into sub datasets with the rows less than the limit and inserted the
sub datasets into one by using INSERT INTO Statement.
<br>

FOR EMS DATASET:
EMS dataset was the largest dataset.So we applied some filters and organized the files
into sections and made it finally less than 25000 rows in each file.Because the table was
uploaded as TABLE 8 rather than 2015a, we renamed it to EMS 2015a using ALTER TABLE,
and similarly for EMS 2015b and EMS 2015c.EMS 2015a, EMS 2015b, and EMS 2015c are
currently available. We now used insert into commands to join these three tables into one.We
can now see that EMS 2015b has almost 57k rows.The EMS 2015a and EMS 2015c tables
will be deleted, and EMS 2015b will be renamed to EMS 2015c.Similarly, we created EMS
2016, EMS 2017, and EMS 2018, and then used INSERT INTO instructions to consolidate all
four tables into one. The final table is known as the EMS file.
We then removed the duplicate files and unwanted files from the EMS files. Although there
are many duplicated and unwanted files in the EMS file, they can be easily removed with the
help of SQL. The removed items include Other for destination name, non-hospital facilities.
The end destination is not always the destination. It's supposed that's where the patient was
picked up in some cases. Our data is based solely on hospital entries, and there are several
items that are not tied to hospitals.
The following entity-relationship diagram displays how files were joined to ultimately create the
final AQIEMS database. There were intentionally two primary keys in AQI as each date
provided a specific AQI to each county. Therefore, this made them unique qualities together.
Fig 3. Entity relationship diagram
<br>

FOR AQI:
Even for the air quality we did the same process as the air quality consists of four year
data sets, i.e. 2016-2020 we have a large number of rows in each data set. We divided the data
sets into sub datasets and managed to make a single file.
The entire process is detailed and explained in the link below.
https://drive.google.com/drive/folders/1FGTCFUPb3DJEOShlRTN6u8I5darNpx9n?usp=shari
ng
<br>

FOR HOSPITAL DIRECTORY:
The hospital directory file is a very important and quite big file which has many
attributes which are unwanted and has many duplicates so cleaning of these files took much
time. The four files are subdivided and sorted. The removed files include all non-specified
symptoms from the table. All empty events with no symptoms listed. Removal of
considerations that may skew data such as unspecified pain, removed death, removed
non-specific terms such as “mass/tumor” and included general symptoms such as “cough” that
could be applied to several types of disease outside of pollution-induced diseases.
https://drive.google.com/drive/folders/19a2Ts7vSmlHzC3-ycALjkopSSnG_4s-3?usp=sharing
<br>

4.3 Data import:
Once the cleaning was completed, we began importing the final AQIEMS into the Python
Jupyter Notebook using the Python Pandas data frame. We began to bring the interaction
between the multiple data sets that have been cleaned and simplified in PHPMyAdmin. We
attempted to import the data into the collaborative access to PHPMyAdmin, a platform supplied
by the professor, and imported the data sets for the EMS, Air Quality, and Hospital Directory, as
well as the AQIEMS main file. The following entity-relationship diagram displays how files
were joined to ultimately create the final AQIEMS database. There were intentionally two
primary keys in AQI as each date provided a specific AQI to each county. Therefore, this made
them unique qualities together.
<br>

5. Data Analysis
5.1 Deliverables
Fig 4. Descriptive table
The table demonstrates the features used in the study to determine the relationship between the
AQI and the EMS in regards to the various counties and zip codes. We can observe ZIP _Code,
AQI, SYMPTOM _PRIMARY encoded, Category _encoded, and Defining _Parameter
_encoded.
First, we opened the AQIEMSI.csv file. The two parameters we renamed are defining_parameter
and zip_code from defining parameter and zip code. These changes were made due to the
inability for the coding to recognize the names when there is a space in between characters.
Fig 5. Opening csv file.
Next, we opened the symptom_primary file to list
all the symptoms. When the symptoms displayed
(Figures 5 and 6), it was clear they needed to be
categorized to ensure the plotting was not too busy
with too many labels. All symptoms were
reviewed and renamed to the affected system of the
symptom (Figure 7).
Fig 6. All possible symptoms in the database.
Fig 7. Example of changing all symptoms related to the respiratory system to “Respiratory” for grouping.
Encoding was then completed to assign numbers to provide numerical value for analysis. The
final categorized names were the following prior to encoding them as symptoms_encoded:
Respiratory, Gastrointestinal, Pain, General/Multiple Symptoms, and Cardiac.
However, it was important to find if there were more systems affected than others. We
concluded from Figure 8 that the count for general/multiple systems is much higher (count as in
how many times it occurred) in comparison to other systems plotted in the graph. It is important
to note the second highest is respiratory, and this is a significant finding.
.
Fig 8. graph of the categorized symptoms
In order to perform a correlation matrix plot, the symptoms in each category were converted
from alphabetical to integers and then replaced using df.corr() (Figure 8).
Fig 9. Correlation matrix plot
To find out the best correlation point we compared 3 different types of correlation based on the
P-value, the more the value the higher the correlation efficiency. The 3 correlation coefficients
we used are Pearson, Spearman, and Kendall correlation (Figures 10, 11, and 12).
Fig 10. pearson correlation
Fig 11. Spearman correlation
Fig 12. Kendall correlation
Our correlation analysis shows that the P-value of Pearson correlation is higher when compared
to the other two which makes it highly efficient.
Fig 13. Heatmap of correlation
This heat map showed that there was a true positive correlation between AQI and
Category_encoded with a value being 0.78. This is not surprising as the encoding is of AQI.
This may also indicate, since it is not 1, that there may be errors in our data as they should be
directly correlated. It also shows us that there is a weak inverse correlation between AQI and
Symptom_PRIMARY_encoded with a value -0.0024.
<br>

Scatter plot:
We displayed a scatter plot between the symptom and the AQI levels
Fig 14. scatter plot
The scatterplot matrix helped us to gather many relationships between combinations of variables
to be visualized in one single chart. With respect to our study, we made a scatterplot matrix
between AQI and SYMPTOM_PRIMARY_encoded. By looking at the above plot it is clear
from the upper left-hand plot that our data is not normally distributed.
<br>

● Comparative Studies
We began comparing the air quality index with the rate of hospitalizations in the hospital
directory using python. We took individual poor, moderate, and good air quality days and began
comparing them with hospitalizations to determine the rate of hospitalizations for the four years
and created graphs based on the features. Our initial findings show that there was an increased
rate of hospitalizations as the air quality decreased from good to moderate. Although there were
worse hospitalization rates for poor days than good days, they were less than moderate. This
may be a display of our major data restraint as we have a significantly smaller amount of data for
poor days than we do the other qualities (Figure 31).
Fig 15. Rate of hospitalizations for the poor air quality days
Fig 16. Rate of hospitalizations for moderate air quality:
Fig 17 Rate of hospitalizations for both good air quality days and overall
Fig 18 Graph with respect to the rate of hospitalizations and air quality
Then we started to take other attributes by selecting one defining parameter such as avg(AQI)
from AQIEMS for good, moderate, and poor air quality days.
<br>

Code:
'SELECT `Defining Parameter`, AVG(`AQI`) FROM `AQIEMS` where `Category`= "Moderate"
GROUP BY `Defining Parameter`.
The second step was to categorize the various air pollutant levels that had an impact on
hospitalization rates, and we also attempted to calculate contamination rates such as contaminant
levels per quality and average contaminate air quality.
When we compared the contaminant levels of air quality, we discovered that PM2.5 is more
effective on bad days with an average rate of contaminant levels of more than 120.
Fig 19 Defining parameter
The final step was to compare the contaminants and Air quality levels, Air contaminate ratios
with this we can observe that Sulfur Dioxide seems to be the biggest effect on Air quality.
Fig 20: Contaminate levels per quality
Finally, we did non-normalized data and when we checked the air quality graph that compares air
contaminate ratios to contaminates and air quality levels, it shows that moderate and unhealthy
levels are skyrocketing due to SO2 which clearly explains why SO2 seems to have the biggest
effect on air quality.
Fig 21: contaminants and air quality levels
Logistic Regression Model
For the analysis, we imported the CSV file into the Python Jupyter Notebook and used the
Logistic Regression approach to determine which features were taken into account and had an
accurate p-value.
Fig 22 Code for Test Train Split
After performing the Test train split, the Category_encoded column was taken to do prediction
and we divided it into two parts: the training and testing part.
Thirty percent of the category encoded column is for testing data, while the remaining
percentage is for training. Import the logistic regression package and use the code below to make
predictions about how this model will help to make predictions in the future. We can see that F1
scores are lower. The less data there is, the lower the F1 score.
Fig 23 Code for plotting the logistic regression curve;
As seen from above,it is clear that F1 scores are next to 1.
Conditional Logistic Regression Graph:
We plotted a graph between AQI, and Category_encoded
● 0-50: Good days
● 50-100: Moderate days
● 100 and above: Unhealthy days
On the graph, the category increases with an increase in the defining parameter. The more
unhealthy days there are, the higher the AQI will be.
Fig 24:Logistic Regression Curve
Here,
0 : CO
1 : NO2
2 : Ozone
3 : PM10
4 : PM 2.5
5 : SO2
Hence, we can say that SO2 is the determining factor for unhealthy days.
<br>

Hypothesis Testing
Our null hypothesis defines that there is no relationship between AQI and EMS.
Alternate Hypothesis defines that there is a relationship between AQI and EMS.
<br>

Kruskal Test
Since our data is not normally distributed and we have more than 5 categories (unique values),
we found Kruskal to be an appropriate method for testing. We performed a Kruskal-Wallis test
between columns AQI and Category_encoded by selecting from the AQI table and EMS table
respectively. We took the P-value to be the determining factor. If P-value is less than 0.5 it
concludes the null hypothesis being rejected and our hypothesis being correct. If it is >=0.05, we
can finalize that the null hypothesis is correct.
After performing the test analysis, we found our P-value to be 0.0 which clearly defines our
hypothesis as accurate and hence we made the statement that “our hypothesis is right and
hence, we reject the null hypothesis.”
Fig 25. Hypothesis Testing
<br>

Data Visualizations including Heat Maps
To portray the data more graphically, we began to plot several graphs using Python and Tableau,
and we obtained pretty good charts.
In Tableau, we began by creating graphs that displayed the sum of AQI in each year, the
percentage of AQI by category, the average AQI by city, symptoms by pollutants and Air quality
index, pollutants and AQI by month average AQI by City:
We analyzed different cities' average AQI and discovered that the darker the color, the higher the
AQI, and the lighter the color, the lower the AQI. Based on this, we can observe that the average
AQI ranges from 5.88 to 50.51
From the image, we can see that the city of Indianapolis has the darkest color, indicating that it
has the highest average AQI levels. In contrast, the city of Washington has the lowest average
AQI levels.
Fig 26: The average of AQI by city
The graphic below depicts the various cities with average AQIs ranging from 30 to 50.8. There
are around eight cities within the range.
Fig 27: The average of AQI by city with AQI values shown
We can now see the contribution of pollutants to the rate of Average AQI with respect to the
months.
We can observe that the metric PM 2.5 is at its peak in the month of July, and Ozone is at its
lowest in the month of June. The lighter the color, the lower the impact of the pollutant in that
month. The darker the color, the greater the impact of pollutants in that given month.
Fig 28:Monthly list of Pollutants and AQI
Fig 29: Monthly list of pollutants and AQI with AVG(AQI)values
We also attempted to obtain a visual representation of the relationship between the symptoms
and the Air Quality Index.
We can see that the defining factors appear to have the same impact on good and moderate days,
but on unhealthy days, PM2.5 has a significant impact on the Air Quality Index.
Fig 30. List of symptoms by pollutants and AQI
We then tried to show a relationship between parameters such as respiratory, pain,
multiple/general, cardiac, and gastrointestinal with the air quality index.
Fig 31. Clear view of symptoms of each system that got affected by 6 different pollutants
We can clearly see that the impact of the PM 2.5 is more on the parameters like respiratory,
gastrointestinal, and pain.
The percentage of the category wise AQI:
We can clearly show that good days are more and unhealthy days are very few.
Fig 32. AQI levels denoted based on category
Fig 33: AQI range (2015-2018)
<br>

CHOROPLETH MAP
Fig 34. Choropleth Map of Indiana’s AQI averages
We also did a choropleth map to visualize the different counties that were affected by the levels
of the pollutants that lead to increased rate of hospitalization. There are white areas due to not all
counties participating as reporters/monitors of AQI. There are also no hospitals in every county,
thus this limited the map to only those containing a hospital as this was the destination we
needed in our initial data. This may also be a restriction of our data.
To formulate the choropleth map, we found the AVERAGE AQI for every county for the past 4
years. For each county, FIPS (Federal Information Processing System) codes were gathered
which were added to data. Required packages (geopandas,pyshp,shapely,plotly-geo)were
installed and we mapped AVG AQI with the corresponding FIPS code and displayed our results
<br>

Heat mapping:
We used heat mapping to plot the differences in the air quality at different periods of the year,
and we discovered that in 2016, the sixth month had the highest amount of air quality, and in
2018, the fifth month also had a high level of air quality, with a numerical value of 56.
Fig 35. AQI heatmap (2015-2018)by months
<br>

AUC - ROC curve:
Fig 36 AUC-ROC curve
This ROC curve was from logistic regression. We have a high area under the curve (AUC) which
means the ability to predict classifications has high accuracy.
A part of testing, and training of data using Machine Learning
(prediction)
<br>

Predictive Analysis
SGD classifier:
Fig 37: Code to find accuracy for SGD
We imported the SGD model to check the accuracy and to estimate how often the classifier was
correct.
The result with good accuracy was noted: 0.98.
<br>

Gaussian Naive Bayes:
Fig 38:Code to define Accuracy for Naive Bayes
Fig 39:Results of Naive Bayes
The Gaussian Naive Bayes model was loaded. We trained the models and predicted the response for the
test dataset using training sets such as X train and y train. Now we must examine the model's accuracy
and classifier, with the Naive Bayes classifier demonstrating that it is unable to effectively forecast data
with mild days. Moderate days were forecast to be both nice and bad.
<br>

XG BOOST:
Fig 40:Results of XG Boost
We put in the XG increase. Import XGB classifier from XG boost. Using the XGB Classifier, we must
examine the model accuracy and how frequently the classifier is correct. The precision is 1.0.
<br>

RANDOM FOREST CLASSIFIER :
Fig 41:Results of Random forest classifier
Using the Random Forest model to fit the datasets, we bring the classification model into the
picture as our study is a classification problem. We must first create the prediction object. The
RBM is then fitted with X and Y data. We must use RFC to forecast a new result. Visualizing the
results of the Random Forest Classification, We must generate a set of values ranging from the
minimum to the maximum value of x. The difference between 0.01 and 0.02 To reshape the data
into a Len (x grid) * 1 array, i.e. to construct a column out of the x grid value, use Reshape.
Make a scatter plot of the original data. Plot the expected data.
Clustering on only data, random forest classifier, create a Gaussian classifier and train the model
using the training sets y_pred = clf.predict (X_test), Now import the scikit-learn metrics module
for accuracy calculation, now we have to check the accuracy.
We have got accuracy 1.0
<br>

DECISION TREE CLASSIFIER:
Fig 42:Code for Decision tree classifier
Confusion matrices:
Fig. a : Logistic regression (Accuracy score: 0.983)
Fig. b : Naive Bayes (Accuracy score: 0.98)
Fig. c : SGD (Accuracy: 0.979)
Fig. d: Decision tree classifier (Accuracy: 1.00)
Fig. e: XG Boost (Accuracy: 1.00)
Fig. f: Random Forest Classifier(Accuracy:1.0)
Fig 43:Tabular representation of scores of all models
Methods Accuracy Precision F1 scores
Logistic regression 0.983 0.99 0.99
Naive bayes 0.98 0.97 0.99
SGD classifer 0.979 0.972 0.98
Decision tree
classifier
1.0 1.0 1.0
XG booster 1.0 1.0 1.0
Random Forest
Classifier
1.0 1.0 1.0
Gaussian Naive Bayes is considered the most accurate model as it had the least errors due to
having all the unhealthy days as correctly classified. SGD Classifier and Logistic Regression did
not accurately classify unhealthy days.
<br>

Conclusion:
Since our hypothesis test results provided the value of P to be 0.0, we rejected the null
hypothesis and concluded that there exists a relationship between AQI and EMS.
We also concluded that the AVERAGE AQI value is highest for the county 'MARION'
‘MARION'' in the city of Indianapolis
<br>

Results:
Results indicate that there is an association between pollutant levels and health emergencies
related to chest pain, respiratory distress, nausea, malaise, and heart stroke as classified by the
EMS. As for our second portion of the study, provide output on the trends of pollutant days.
Our results were concluded from the hypothesis testing and choropleth graphical depictions
which rejected our null hypothesis and concluded the highly affected county in Indiana to be
Marion as it has an AQI range of 50.
From Boxplotting we analyzed that there was a correlation between AQI levels and diseases like
malaise, nausea, stroke, and weakness.
<br>

Limitations of our study:
The sample size for the unhealthy days was small and restricted.
We were unable to gather the data for all counties of Indiana state but could gather only for a few
counties as the air quality levels are not maintained or recorded in other countries.
There was a lot of unwanted data in each data set. Deleting them was a huge task.
Due to data overfitting, decision tree classifiers did not work well. However, SGD, Logistic
regression, and Naive Bayes gave us accuracy as next to 1.
There is a weak correlation between symptoms and AQI. Correlation is not the best
representation of data.
When we limited our categories to just two (good and unhealthy), instead of considering 3
categories (Good, moderate and models showed their accuracy, precision, and “f1- score'' to be 1
for all categories. Hence, we decided to stick to considering 3 categories and got our precision,
F1- score, and accuracy next to 1.
<br>

References:
U.S. Department of Health and Human Services. (n.d.). Air pollution and your health. National
Institute of Environmental Health Sciences. Retrieved September 27, 2021, from
https://www.niehs.nih.gov/health/topics/agents/air-pollution/index.cfm
Centers for Disease Control and Prevention. (2020, December 21). Air pollution. Centers for
Disease Control and Prevention. Retrieved September 27, 2021, from
https://www.cdc.gov/climateandhealth/effects/air_pollution.htm
Emergency medical service runs - the Indiana data hub. Datasets - the Indiana Data Hub.
(2019, September 11). Retrieved September 27, 2021, from
https://hub.mph.in.gov/dataset/emergency-medical-service-runs
Breathe a little Easier: Why America's air is among the cleanest in the world. IER. (2020, April
14). Retrieved September 27, 2021, from
https://www.instituteforenergyresearch.org/climate-change/breathe-a-little-easier-why-americas-
air-is-among-the-cleanest-in-the-world/
Environmental Protection Agency. (n.d.). AirData website file download page. EPA. Retrieved
September 27, 2021, from https://aqs.epa.gov/aqsweb/airdata/download_files.html#Annual
Hospital directory. (n.d.). Retrieved September 27, 2021, from
https://www.in.gov/health/reports/QAMIS/hosdir/wdirhos.htm
Centers for Disease Control and Prevention. (n.d.). County cross reference file (FIPS/ZIP4).
Centers for Disease Control and Prevention. Retrieved September 27, 2021, from
https://wonder.cdc.gov/wonder/sci_data/codes/fips/type_txt/cntyxref.asp
