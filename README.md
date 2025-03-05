
## Call centers performance analysis

## Table of Content
-  [Project Overview](#project-overview)
-  [Data Sources](#data-sources)
-  [Tools](#tools)
-  [Data cleaning ](#data-cleaning )
-  [Exploratory data analysis](#exploratory-data-analysis)
-  [Data analysis](#data-analysis)
-  [Findings](#findings)
  
### Project overview
---
   - Creating  a dashboard  for call center
 
![Screenshot 2025-02-18 235535](https://github.com/user-attachments/assets/9d77a612-9259-4779-903c-5ea8493e380f)

![Screenshot 2025-02-18 235703](https://github.com/user-attachments/assets/f589eb68-450a-47b2-8460-e7693db994a0)

![Screenshot 2025-02-19 000108](https://github.com/user-attachments/assets/ac891faf-24b4-4459-bfe3-2a8e45e01867)

![Screenshot 2025-02-19 000241](https://github.com/user-attachments/assets/e639e7e8-db8d-4f13-ac64-d26f322cd50a)

![Screenshot 2025-02-19 000335](https://github.com/user-attachments/assets/f8361e4e-36c7-4498-a9a7-9bc36a1d1096)

![Screenshot 2025-02-19 000410](https://github.com/user-attachments/assets/d1f28d54-40b1-4758-a664-77e74770e6b5)

![Screenshot 2025-02-19 000446](https://github.com/user-attachments/assets/4931df94-a5ea-4c44-85f3-b12feb957279)

![Screenshot 2025-02-19 000537](https://github.com/user-attachments/assets/8923198f-1ac3-4470-8b76-711c54438aaf)

 
 ### Data sources
 ---

*The dataset use for this analysis is "Call Center_Dataset.csv"  file . we have data on sentiment ,csat_score reason channel etc*


### Tools
---
  - Excel: Data cleaning
  - Excel-pivot tables
  - Excel-Charts
  - Excel-slicers
      - [Download Excel here](https://microsoft.com)

### Data cleaning 
---
-Create a duplicate sheet as back up in case you need to have a view on the original dataset

-Enlarge all the columns that has data for visibility reasons 

-Make a distinction between the headers row and the rest using the cell style

-Freeze the top row , to make it always visible on the screen when scrolling down using freeze panes

-Check the number of data you have in your dataset , by placing the cursor on the main row of the dataset and press Ctrl + ↓ and to go back to the first row press Ctrl + ↑

-Data type checking :

	  * for the csat_score and call duration in minutes columns ,change the data type to number
	  * for the call_timestamp column use the text to column function to harmonized the date
	  * Leave the other columns as there are , as they  are text


### Exploratory data analysis
---

EDA involved exploring  the call center data to  answer key question , such as :

  - What is the total inbound contacts for the month ?
  - what are the reasons for calls?
  - what is the number of contact per call center ?
  - what is the number of contact per channel  ?

### Data analysis
---

```
- AS the data is just for one month , we need to create a another column for the call day by using the function  date and then change data type to number and zero decimal number to have the call day

-Create a new sheet , to create  a pivot tables :
	* Calls by sentiment
	* Reasons for call
	* Calls by Channel
	* Calls by call center
	* Calls by response time
	* Calls by call day
	* Calls by state
	* Sentiment by call center
	* Response time by call center

- Create a new sheet for our dashboard ,The dashboard will be compose of the following element
	*  Slicers for call day
	*  Doughnut charts for Calls by Channel
	*  clustered bar chart for Calls by sentiment
	*  clustered bar chart for sentiments by call center
	*  Clustered column chart for calls by call center
	*  Clustered column chart for  Reasons for call
	*  Clustered column chart for Calls by response time
	*  Map of Calls by state
	*  Clustered column chart Calls by Channel

-Links the slicers to all the pivot charts and tables for the interactivity
	
```

### Findings
---

- In the overall , for the month of October 2020 ;
	* We had a total inbound contact of  32,941 
	* Most clients call in order to have more clarity on billing issues
	* Is Los Angeles/CA that had the highest number of call in October
	* In all the call centers , the response time was attained by the majority of agent
	* The channel that received the highest number of contact is live contact mainly on the phone





💻💻  


