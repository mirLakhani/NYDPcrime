# NYDPcrime
Our dataset, sourced from the US Data.gov website, encompasses all NYPD arrest records in New York City's five boroughs for the year 2023, providing detailed information on arrest types, locations, and demographics, including gender, race, and age groups categorized into five brackets.
# Team Name:
39217 Group 7

# Team Members:
Dylan McMorrow 

Aafreen Anjum 

Jack Drummond 

Ishi Gupta 

Miral Lakhani  

# Description of Dataset:
Our dataset shows all of the NYPD arrest records in the 5 boroughs of New York City for the current year (2023). We obtained our dataset from US Data.gov website (https://catalog.data.gov/dataset/nypd-arrest-data-year-to-date). Each record represents an arrest affected by the NYPD and includes information about the type, location, and time of enforcement. Additionally, descriptions for suspect demographics are also included. 

Our dataset contains dimensions that include information on the date of the arrest, offense description, and corresponding law code. There are also columns to record the demographics of the arrested individuals, including gender, race, and age group. The dataset divides the age groups into 5 different categories (<18, 18-24, 25-44, 45-64, and 65+). There are also multiple columns describing location data. The “Arrest_Boro” column specifies which of the 5 boroughs in New York City the arrest took place. Each borough is depicted by a letter (“B” - Bronx, “S” - Staten Island, “K” - Brooklyn, “M” - Manhattan, and “Q” - Queens). There are also multiple columns describing the latitude and longitude of the arrest location. Each record in the dataset contains a unique and randomly generated “Arrest_Key”, which serves as the primary key to identify each arrest. The “Law_Cat_Cd” column classifies the level of offense into 3 categories (“F” - Felony, “M” - Misdemeanor, and “V” - Violation). 


# Question 1:
Among the boroughs, which one has the highest number of assault arrests across various age groups? Additionally, considering the borough and age group with the highest assault arrests, what racial demographic shows the highest number of arrests for assault?

# Importance:
​​Understanding the distribution of assault arrests across New York City's boroughs and various age groups, and subsequently identifying the racial demographic with the highest number of arrests within the most affected borough and age group, is of paramount importance for effective law enforcement and community well-being. This question enables a nuanced analysis that goes beyond mere crime statistics. By pinpointing the borough with the highest assault arrests, law enforcement can strategically allocate resources to address specific geographic hotspots. By looking at different age groups, we can create programs that are better suited to the needs of specific communities. Additionally, finding out which racial group has the highest number of arrests helps us have conversations about whether there might be unfair treatment happening and how we can make sure policing is fair for everyone. In essence, this question addresses not only the where and when of assault arrests but also delves into the who, providing insights crucial for fostering safer communities and promoting fairness within the criminal justice system.
<img width="621" alt="Screenshot 2023-12-04 at 1 27 05 PM" src="https://github.com/mirLakhani/NYDPcrime/assets/148798235/c34cb241-5cc7-45d8-a298-bd7523818575">



Upon completing our analysis using Tableau, the data reveals that Brooklyn has the highest count of assault arrests. This insight is visually represented through the utilization of a stacked bar graph. A more detailed look of Brooklyn in particular reveals that the age range with the greatest number of assault arrests is between 25 and 44 years old, totaling 3,915 arrests.
<img width="624" alt="Screenshot 2023-12-04 at 1 27 19 PM" src="https://github.com/mirLakhani/NYDPcrime/assets/148798235/5f1ba530-c35c-4e74-95ba-1a1d3257551a">



In order to further our investigation, we looked at the racial distribution of arrests in Brooklyn for those aged 25 to 44. This extra layer of information is helpful because it offers a more complex picture of the demographics associated with these arrests. This helps identify any potential disparities or patterns that can guide focused intervention efforts and advance equity in law enforcement procedures.

# Question 2:
Which months in the current year have witnessed the highest number of arrests, and how do they compare to the estimated arrest totals for the final three months of 2023. What specific offenses were most frequently cited in those arrests?


# Importance: 
Understanding the months in the current year with the highest volume of arrests and identifying the specific offenses most commonly associated with those arrests is vital for law enforcement strategies and community safety. This question provides a complex viewpoint that is essential for making well-informed decisions, going beyond a simple examination of arrest numbers. Law enforcement can more efficiently deploy resources by identifying the months with higher arrest rates and concentrating on times of increased criminal activity.

This information is a powerful tool for raising public awareness. Knowing which months have higher arrest rates can help people be more vigilant and take preventative action during these times, improving both personal and community safety. By delving deeper into the particular crimes that are most commonly reported in those arrests, the second half of the question expands on the first by offering more context. Understanding the types of crimes makes it possible for the public to become more informed about the kinds of criminal activity that are common throughout particular months.	


We created a visual representation of the total arrest counts per month using a Tableau treemap. The intensity of the shades in the treemap signifies the total number of arrests, with May displaying the darkest shade of blue, indicative of the highest arrest count, and February exhibiting the lightest shade, reflecting the lowest arrest count. Based on our analysis law enforcement can focus on increasing visibility and presence in areas during May, the month identified with the highest number of arrests.

In order to shed more insight on the most common offenses, we expanded our analysis by examining the most common crimes each month. According to our analysis, assault was consistently the most common offense, with petit larceny coming in second. This information is essential because it gives law enforcement a thorough grasp of the kinds of crimes that frequently lead to arrest rates. Law enforcement agencies can tailor their strategies and allocate resources effectively to address these specific challenges. 


# Manipulations Applied to the Dataset:
In our data preparation process, we prioritized the highest quality, cleanliness, and standardization of the dataset. Leveraging Tableau's Data Interpreter feature, we refined the raw data, aligning it with usability and relevance standards. The commitment to delivering reliable insights resulted in a standardized dataset without the need for manipulation, characterized by quantifiable measurements. In addition, a thorough elimination of potential data issues was conducted, resulting in a dataset that is free from duplicates, irrelevant entries, redundancies, and inaccuracies. We curated a comprehensive dataset that is not only clean but also devoid of incomplete or low-quality information. 

# Tableau Packaged Workbook: 
The packaged workbook containing the visualizations shown above is attached to this repository.


# MIST 4610 Group Project 2

## Team Name:
39217 Group 7
## Team Members
1. Dylan McMorrow [@DylanMcMorrow](https://github.com/dylanmcmorrow5/MIST4610GroupProject2.git)
2. Aafreen Anjum [@AafreenAnjum](https://github.com/aanjum2003/NYPDcrime/blob/main/README.md)
3. Jack Drummond [@JackDrummond](https://github.com/jdrum7/NYPD_Crime_Data)
4. Ishi Gupta [@IshiGupta](https://github.com/ishigupta24/NYPD-crime)
5. Miral Lakhani [@MiralLakhani](https://github.com/mirLakhani/NYDPcrime/blob/main/README.md)


## Description of Dataset:
Our dataset shows all of the NYPD arrest records in the 5 boroughs of New York City for the current year (January 2023 through September 2023). We obtained our dataset from US Data.gov website (https://catalog.data.gov/dataset/nypd-arrest-data-year-to-date). There are 19 columns and over 170,000 rows in the dataset. The data contains dimensions that include information on the date of the arrest, offense description, and corresponding law code. The date dimension is of type date, while the offense description and law code are of type string. There are also columns to record the demographics of the arrested individuals, including gender, race, and age group, which are all of type string. The dataset divides the age groups into 5 different categories (<18, 18-24, 25-44, 45-64, and 65+). There are also multiple columns describing location data. The ‚ÄúArrest_Boro‚Äù column is type string, and specifies which of the 5 boroughs in New York City the arrest took place. Each borough is depicted by a letter (‚ÄúB‚Äù - Bronx, ‚ÄúS‚Äù - Staten Island, ‚ÄúK‚Äù - Brooklyn, ‚ÄúM‚Äù - Manhattan, and ‚ÄúQ‚Äù - Queens). Each record in the dataset contains a unique and randomly generated ‚ÄúArrest_Key‚Äù, which is a numeric data type and serves as the primary key to identify each arrest. The ‚ÄúLaw_Cat_Cd‚Äù dimension is of type string, and classifies the level of offense into 3 categories (‚ÄúF‚Äù - Felony, ‚ÄúM‚Äù - Misdemeanor, and ‚ÄúV‚Äù - Violation). The Jurisdiction dimension is a numeric data type and specifies which jurisdiction led to the arrest. ‚Äú0‚Äù represents Patrol, ‚Äú1‚Äù represents Transit, and ‚Äú2‚Äù is Housing. All code numbers after 2 represent jurisdictions outside of the NYPD. The Arrest Precinct is a numeric data type which represents the number of the precinct the arrest occurred at. The Ky code dimension is a numeric data type, which is a 3-digit number corresponding to the offense description. The Pd Description is a string data type, and it is a more specific description of the crime compared with the Offense Description. The corresponding Pd Code is numeric data. There are also multiple columns describing the latitude and longitude of the arrest location, which are numeric data (specifically decimals).  The X and Y Coordinate Cd columns represent the location of the arrest using the New York State Plane Coordinate System, while the Latitude and Longitude columns represent the global coordinates. For more detailed information on the dataset, please follow this link (https://data.cityofnewyork.us/Public-Safety/NYPD-Arrest-Data-Year-to-Date-/uip8-fykc). 

## Question 1:
Question:

Among the 5 boroughs of New York City, which one has the highest number of assault arrests across various age groups, and how do the other boroughs differ? Additionally, considering the borough and age group with the highest assault arrests, what racial demographic shows the highest number of arrests for assault?

Importance:

‚Äã‚ÄãUnderstanding the distribution of assault arrests across New York City's boroughs and various age groups, and subsequently identifying the racial demographic with the highest number of arrests within the most affected borough and age group, is of paramount importance for effective law enforcement and community well-being. This question enables a nuanced analysis that goes beyond mere crime statistics. By pinpointing the borough with the highest assault arrests, law enforcement can strategically allocate resources to address specific geographic hotspots. By looking at different age groups, we can create programs that are better suited to the needs of specific communities. Additionally, finding out which racial group has the highest number of arrests helps us have conversations about whether there might be unfair treatment happening and how we can make sure policing is fair for everyone. In essence, this question addresses not only the where and when of assault arrests but also delves into the who, providing insights crucial for fostering safer communities and promoting fairness within the criminal justice system.


<img width="1216" alt="Question 1A" src="https://github.com/dylanmcmorrow5/MIST4610GroupProject2/assets/148798141/0def6b64-46fc-4a1e-b3f1-ed234cfab3c0">

Upon completing our analysis using Tableau, the data reveals that Brooklyn has the highest count of assault arrests. The criminal offenses we selected are ‚ÄúFelony Assault‚Äù and ‚ÄúAssault 3 and Related Offenses‚Äù. This insight is visually represented through the utilization of a stacked bar graph. Brooklyn has the most total arrests for assault of any borough at 11,164, with the Bronx just behind at 11,097. Staten Island has by far the least assault arrests, at 1,685. Across each borough, the age range with the greatest number of assault arrests is between 25 and 44 years old. Brooklyn also had the highest number of assault arrests for this age range of any borough, totaling 6,541 arrests. Our next visualization continues to look at assault data, taking a deeper look into the demographics.

<img width="1226" alt="Question 1B" src="https://github.com/dylanmcmorrow5/MIST4610GroupProject2/assets/148798141/d1b52741-d91d-4b8c-a748-ba02f95768ca">

In order to further our investigation, we looked at the racial distribution of arrests in Brooklyn for those aged 25 to 44 using a heatmap. The darker shades of blue along with a larger size of the blocks indicated a higher number of assault arrests. This extra layer of information is helpful because it offers a more complex picture of the demographics associated with these arrests. This helps identify any potential disparities or patterns that can guide focused intervention efforts through social programs and advance equity in law enforcement procedures. It is clear the highest arrest count is for black individuals, highlighting a serious need for reform in Brooklyn.



## Question 2:
Question:

Which months in the current year have witnessed the highest number of arrests, and how do they compare to the estimated arrest totals for remaining months of 2023? For the month with the highest number of arrests, what specific offenses were most frequently cited in those arrests?

Importance:

Understanding the months in the current year with the highest volume of arrests and identifying the specific offenses most commonly associated with those arrests is vital for law enforcement strategies and community safety. This question provides a complex viewpoint that is essential for making well-informed decisions, going beyond a simple examination of arrest numbers. Law enforcement can more efficiently deploy resources by identifying the months with higher arrest rates and concentrating on times of increased criminal activity.

This information is a powerful tool for raising public awareness. Knowing which months have higher arrest rates can help people be more vigilant and take preventative action during these times, improving both personal and community safety. By delving deeper into the particular crimes that are most commonly reported in those arrests, the second half of the question expands on the first by offering more context. Understanding the types of crimes makes it possible for the public to become more informed about the kinds of criminal activity that are common throughout particular months.	


<img width="1225" alt="Question 2A" src="https://github.com/dylanmcmorrow5/MIST4610GroupProject2/assets/148798141/50b61fec-b960-42f4-876b-fca6cddc67c3">


We created a visual representation of the total arrest counts per month using a line graph. January through August contain actual data from the dataset, while September through December are estimates based on Tableau‚Äôs forecasting tool. We decided to modify the range on the y-axis to 15,000 - 22,000 arrests to more accurately depict changes from month to month. Before this change, the line appeared a lot flatter since the range went from 0 - 23,000 arrests, making it more difficult to compare the different months. After modifying the axis, May clearly displays the highest arrest count, while February dips low on the graph, reflecting the lowest arrest count. Based on our analysis law enforcement can focus on increasing visibility and presence in areas during May, the month identified with the highest number of arrests.


<img width="1225" alt="Question 2B" src="https://github.com/dylanmcmorrow5/MIST4610GroupProject2/assets/148798141/9e0ab630-a561-4ef3-b587-2d18033fcff0">


In order to shed more insight on the most common offenses, we expanded our analysis by examining the most common crimes for May because it is the month with the most arrests. According to our analysis, assault was consistently the most common offense, with petit larceny coming in second. This information is essential because it gives law enforcement a thorough grasp of the kinds of crimes that frequently lead to arrest rates. Law enforcement agencies can tailor their strategies and allocate resources effectively to address these specific challenges during May in hopes to reduce the number of arrests to a number closer to other months of the year.


## Manipulations Applied to the Dataset:
Although we did not need to manipulate the dataset, we focused on ensuring the highest data quality by using Tableau's Data Interpreter to refine and standardize the raw data. This process improved usability by eliminating potential issues such as duplicates, inaccuracies, and empty cells resulting in a comprehensive dataset that is free of errors. We also utilized Tableau‚Äôs forecasting feature in our second question to provide estimates for data in September - December to fill in the gaps since the current year has not concluded and contains no entries for these months. From the beginning, our team was dedicated to selecting a dataset with an adequate number of rows and columns, accompanied by a clear data dictionary. This dedication aided us in our understanding, minimizing the time spent preparing the data for analysis.

## Tableau Packaged Workbook:
Attached to this repository is the Tableau packaged workbook file (MIST4610Project2.twbx) containing the visualizations shown above.


