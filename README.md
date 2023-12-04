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

Importance:
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
