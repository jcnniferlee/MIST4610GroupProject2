# Team 4 MIST 4610 Group Project 2

# TEAM NAME
21482 Group 4 


# TEAM MEMBERS
- Jennifer Lee [@jcnniferlee](https://github.com/jcnniferlee/MIST4610GroupProject1.git)
- Connie Wang [@cw76668](https://github.com/cw76668)
- Kevin Choi [@kc11502](https://github.com/kc11502)
- Kayla Valentine [kaylavalentine](https://github.com/kaylavalentine)
- Vivek Shah [vsshah5](https://github.com/vsshah5)

# DATA SET DESCRIPTION
Our data set details Crime Data from 2020 to Present from the Los Angeles Open Data Portal. We obtained our data set on the provided website [Catalog.data.gov](https://catalog.data.gov/dataset/crime-data-from-2020-to-present). It includes all crimes reported to the Los Angeles Police Department (LAPD) since January 1, 2020. The dataset is also regularly updated and publicly available through data.lacity.org. It has around 1.2M rows and 28 columns, where each row represents a single reported crime. The dataset includes information like the date and time the crime occurred, the type of crime, the LAPD area where it happened, victim details (like age, gender, and race), and even the weapon used if applicable. It also includes location data (latitude and longitude). Most of the data is in the form of dates, strings, integers, and floats. 

The String data type was used in fields including the type of crime, the location it took place in, and the descent of the crime's victim. The Number datatype was used in fields including the report number, the codes of the crimes committed, and the area of LA that the crime took place in. The DateTime datatype includes fields that detail the time the crime occurred as well as the time that the crime was officially reported. Overall, this dataset uses different datatypes in numerous ways to report data about crimes in Los Angeles.

![66E33C51-7095-4633-8D5A-CA8B91B9BF91_1_201_a](https://github.com/user-attachments/assets/55969a52-cfb3-4e24-8516-53188b9f68dc)


# QUESTION 1
Since the beginning of 2025, has there been a correlation or occurrence of violent crimes in certain areas of LA, and what spatial patterns can be identified across the city?

# VISUALIZATION 1
![4D6B591F-D954-4123-AC80-D9FBCCE5DB4A_1_201_a](https://github.com/user-attachments/assets/361dab6f-e299-4362-ab77-d9045605bf65)

The bar chart above shows the differences in violent crimes between 2024 and 2025 from January through March for both years. The yellow bars represent the violent crimes in 2024 and the green bars represent 2025. 

# VISUALIZATION 2
![E7FAB962-0713-4DEC-9DAB-D29763584AF4_1_201_a](https://github.com/user-attachments/assets/5e63918c-6fa6-4122-835f-fd7f96c004dd)

The same information is also presented through another visualization mapping out the different violent crimes between 2024 and 2025 through January and March. 

# ANALYSIS 
After analyzing the data, we are able to concur that in comparison to the first three months of 2024, the first three months of 2025 had a significantly lower crime rate. The total count in 2024 amounts to 52,616 while the total count in 2025 amounts to 257. This is roughly 200 times smaller than the amount of crimes in 2024. We were also able to find that crime decreased disproportionately with there being less crime overall but noticed that there was a particularly large decrease in central and west LA specifically. While this stark contrast may be attributed to reports not being filed in the first few months of 2025, we can also draw to the conclusion that this may be due to the effectiveness of new distrtict attorney Nathan Hochman. After being sworn into office on December 3rd, 2024, Hochman focused much of his attention on the prioritization and implementation  of policies that enforced LAPD focus on high-crime zones. 

# IMPORTANCE
This question is important as it allows us to draw conclusions about which specific government policies worked and which did not. In determining which policies are effective and which are not, public officials are able to eliminate the unsuccessful policies and replace them with more important policies instead. With more successful policies, crime rates will decrease and more crimes can be prevented. Projections for crimes in certain areas can also help with things like resource allocation, which is important to prevent crime. With more properly allocated resources the right people, tools, and funding are directed toward the most effective strategies and areas of need.

# MANIPULATION
To create this visualizatiom, we put Lat to rows and Long to columns. We also put Year to columns as well. After filtering by year (2024 and 2025 only), we also filtered by the months to include only January-March. For organizational purposes, we put area name to color to show a more visually clear map. 

# QUESTION 2
Is there a correlation in the types of crimes committed against different age groups and whether the severity of a crime varies depending on the age of the victim?

# VISUALIZATION 1
![FC27E622-BD57-4951-90B7-136DA70F7DB9_1_201_a](https://github.com/user-attachments/assets/2c523cd4-7e01-4932-a01f-63b0d7298db5)
This is an overall scatterplot showing the correlation between victims age and crime count not including zero.

# VISUALIZATION 2
![C7A70D0D-11A4-4CD9-B01F-6E6D5A97C57E_1_201_a](https://github.com/user-attachments/assets/16468b32-e2e8-4b4b-a375-96ed61eb272f)
This is the same scatterplot as above now including zero.

# AGES 1 - 17
![E0D7615D-E726-4CBF-95A5-D02A49025C89_1_201_a](https://github.com/user-attachments/assets/f36048f1-212f-491f-9a28-422bd6729d43)

# AGES 18 - 29
![20622FF0-FB41-4F5A-937E-6E7C04DED50D_1_201_a](https://github.com/user-attachments/assets/9b28d1b7-bca7-41e1-905c-7c2f245cf8f9)

# AGES 30 - 40
![3BC561F3-8044-464D-A66E-75E1B0862292_1_201_a](https://github.com/user-attachments/assets/47a915ea-0030-4305-8fce-ace74c6b55d2)

# AGES 41 - 58
![3C3BD8DD-B99E-453E-8F1A-F8E5B56D5F53_1_201_a](https://github.com/user-attachments/assets/dc7b11fa-5ee0-43d0-a4d8-209ef8f46064)

# ANALYSIS
Based on our visualizations, we are able to concur what age is most likely to fall victim to misdemeanors or felonies as well as the most common crime against each age group. For ages 1-17, we found that they were not subject to misdemeanors/felonies and subject only to unclassified crimes, with the most common crime being child abuse. For ages 18-28, we found that they were subject to a couple misdemeanors/felonies with the most common crime being battery with sexual contact. For ages 29-40, we found that they were subject to the most misdemeanors AND felonies out of all age groups with the most common crime being battery - simple assault. Lastly, for ages 41-58, we found that they were subject to a single misdemeanor/felony with the most common crime being violation of restraining orders.

# IMPORTANCE
This question is important as public officials and law enforcement can conclude what age is most likely to fall victim to misdemeanors/felonies and the most common crime within the age group, allowing them to focus their efforts on the prevention of the most common crimes per age group. Another thing they can look out for is the severity of a crime, as crimes done against children and minors tend to be considered more severe and typically have harsher consequences. By focusing efforts on certain age groups and crime, this also guides resource allocation by allowing for the implementation of programs such as school safety programs and senior protection programs. 

# MANIPULATION
![3F054A75-9265-4DE4-93B8-47114A039852_1_201_a](https://github.com/user-attachments/assets/d9d915f4-f759-4f05-b95a-4cdfc5e046ca)
The initial manipulation above shows the classifications of certain crimes into 'Felony', 'Misdemeanor', and 'Unclassified'. By separating the different crimes into those categories, we are able to determine what age groups are more subject to misdemeanors and/or felonies. Then to map out our data, we put the count of crime code in rows and the median of age in Y. Then we filtered by ages 1-58 and filtered the crime count to > 1000. We also created a calculated field to identify crime classification and colored the scatterplot based on that. The scatterplot point sizes were based off the count of the crime and the points on the scatterplot were also labeled. 

# CONCLUSION








