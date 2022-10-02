# Analysis of Edmonton's Crime Statistics
### _A Data Visualization Project using Tableau_

Edmonton Crime statistics was analyzed for a **10 year period of 2009 to 2019**. For any data analytics or mining project, the first step is the business understanding. Data is one of the most important resource any business or industry can have, and when collected and interpreted correctly, can provide valuable insights to the business.

However, this can only start from understanding the business industry, be it domain of Health care, Retail, Finance, Engineering, Transportation just to mention a few. Without understanding the business or industry in question, it is almost impossible to have a data understanding, and if you can not make sense of your data, then you cannot ask your data questions.

### Edmonton Police Business Understanding 
Edmonton Police Services (EPS) classifies **Crimes and Disorder** into various categories. **Violent crimes** are made up of _Homicide, Sexual assault, Assault and Robbery_, while the **Property crime** category covers _Break & Enter, Theft of vehicle, Theft from vehicle and Theft over $5,000_.

EPS also tracks **Social Disorders, Domestic violence, and Impaired driving incidents.**

Other important indicators and **KPIs** worth tracking are **Crime Severity Index (CSI), Weighted Clearance Rate (WCR)**, Calls received by **emergency services**, and **Complaint**/Satisfaction Percentage. These Business concepts are defined in a data dictionary. A data dictionary is a part of the Data Understanding and should be a comprehensive definitions of the business and data terms.

### Data Preparation
The next step is the extract transform load. ETL is an interative process and can be carried out in Excel, PowerQuery, Visual Studio or/and Visualization tools like Tableau and PowerBI. In general, whatever transformations made to the data through cleaning, manipulation, wrangling, creating measures, calculated field just to mention a few , are all classified under the ETL process. 

For my analysis, I relied on Tableau for the transformation processes. 

### Data Modeling 
My visualizations has a summary that gives at a glance the important metrics. The summary page provides drill down to other dashboards with deep dive on violent crimes, property crimes,  social disorder, crime clearance rate and complaint Percentage.

## Edmonton Crime Statistics Summary
* Downtown has the highest crime count in the 10 years of 2009 - 2019, followed by Oliver, and Mccaulay neighborhoods. 
* The total homicide for this period is **339**, and reported domestic violence cases is greater than **166,000**.
* Missing persons cases stood at **100** in 2009, and although this dropped between 2010 and 2015, the trend showed a rise in 2019. 
![EdmontonCrimeSummary](https://user-images.githubusercontent.com/114383545/192958566-68e9d745-d06f-440b-9257-afb1c648fb78.jpg)



## Edmonton Violent Crimes Deep Dive
* Assault has the highest crime count of the four violent crime category, and the top Edmonton neighborhood for assault is Graydon Hill and Paisley.
* **Clareview campus** recorded the highest homicide victims within the 10 years, followed by Clareview business.
* Robbery cases was more prevalent in the Desrochers area and River valley neighborhoods. 
![ViolentCrimes DeepDive](https://user-images.githubusercontent.com/114383545/192958671-8cb78add-a4e4-4882-9f03-f3af11870025.jpg)



## Edmonton Property Crimes Deep Dive
* Theft from vehicle is the most popular property crime category in Edmonton. There were **10,000** reported cases in 2009. Cases dropped significantly between 2010 and 2014, but saw a rise from 2016 onwards.
![PropertyCrimes DeepDive](https://user-images.githubusercontent.com/114383545/192958719-61e5423b-a025-438e-85e2-e25840c1576d.jpg)



## Edmonton Social Disorder Deep Dive
* The trend in Edmonton social disorder shows a rise in **Q3 (summer months)** of each year, then a dip in **Q4 & Q1 (winter months)**. However between 2015 and 2017, the difference was of minor significance.
* Incidents caused by impaired driving has steadily decreased from 2013 to 2019.
![SocialDisorder DeepDive](https://user-images.githubusercontent.com/114383545/192958764-9e9aad92-06eb-46c4-a12f-67cf69a943a4.jpg)



## Edmonton Clearance Rate Deep Dive
* From the CSI line graph, crime took a nose dive in 2010 - 2015, and consequently the crime clearance rate also increased in that period.
![ClearanceRate DeepDive](https://user-images.githubusercontent.com/114383545/192958797-0648d7f1-86dc-4bcc-b917-fb368db5ff2d.jpg)



## Edmonton Complaints & Satisfaction Deep Dive
* Percentage of complaints investigated and closed within **6 months** is below **50%**. 
* At an average the number of Non-emergency calls responded to every year range between **200,000 and 400,000** with the highest value occurring in 2013.
![ComplaintRate DeepDive](https://user-images.githubusercontent.com/114383545/192958838-68a4340c-4163-4779-a7e5-8546e96bafbc.jpg)

## Edmonton Neighbourhood
* _Downtown, Oliver, Mccauley, Central McDougall and Boyle Street_ are the **5 top contibuting neighbourhoods to total crime count**. 
* For the specific Categories of Violent Crimes and Prpoerty crimes, Downtown still has the highest count. 
* However Oliver, Alberta Avenue, Strathcona and Queen Mary Park are the next top 4 Contributors to the specific Property crime category (Break and enter, Theft of Vehicle, Theft from vechicle, and Theft over $5,000). 
* While McCauley, Central McDougall, Boyle Street and Oliver are the the next top 4 contibutors to the category of Violent crimes (Homicide, Robbery, Assault and Sexual Assault).
![Neighbourhood](https://user-images.githubusercontent.com/114383545/193347797-98e5f22b-b7f3-4a1e-b3e3-5df80638483e.jpg)

## Evaluation
The visualizations gives valuable insights on Edmonton's crime indicators. **All KPIs showed a decrease for the year 2011 - 2014.** _This period of reduced crime activity should be further investigated to determine the underlying reason, and apply lessons learnt to improve current situation._ Questions such as did Edmonton see a decrease in population resulting in fewer crime count? was there an increase in police strength? was crime underreported during this period? All these and more is part of my recommendation for subsequent analysis.


## Conclusion
Analysis like these are useful in providing valuable insights to EPS to help in _resource allocation to the different neighborhoods, and to put preventive measures in place to make for a safer city._
