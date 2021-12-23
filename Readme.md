# Kickstarting with Excel

## **Overview of Project**

The client, Louise, launched a sucessful kickstarter campaign for the play "Fever". She now wants to know how different campaigns fared in relation to their launch dates and their funding goals. This project analyzes theses campaigns data across a range of goals, locations, dates and project types. Over 4000 individual campaigns were analyzed. Analysis was completed based upon launch dates and funding goals.

### **Purpose**

The purpose of this analysis is to provide statisical data to aid in defining the "Fever" Kickstarter campaign launch.

## **Analysis and Challenges**

    1. Analysis was completed on the source Kickstarter data using Pivot Charts and Pivot Tables.
    2. Analysis was completed based upon Launch Date *Figure 1* and Funding Goal *Figure 2*.
    3. Analysis was restricted to the Theater Category

![Figure 1](https://github.com/CR-HSDC/Kickstarter-analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png)
![Figure 2](https://github.com/CR-HSDC/Kickstarter-analysis/blob/main/resources/Outcomes_vs_Goals.png)

### **Analysis of Outcomes Based on Launch Date**

    1. From *Figure 1* it can be observed that the highest number of successful Theather projects were those that launched in May-June period.

    2. From *Figure 1* a trough can be observed for the "Sep" values for "successful" and "failed" trends, suggesting that overall activity in the "Theater" category experiences a periodic low at this time, following the summer months.

### **Analysis of Outcomes Based on Goals**

    1. The highest rates for successful projects were in the "Less than 10,000" and "35,0000 to 44499" ranges.
    2. The highest rate for failed projects was in the "45,000 to 49,999" range.


### **Challenges and Difficulties Encountered**

    1. Potential difficultiies include incorrect assignment of axes in the Excel Pivot Tables, incorrect formulae in calculating projects statistics (% Failed etc..) or incorrectly sorting chart axes, as required.


## **Results**

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    1. It is best to launch projects in the May June Period.
    2. Theater appears to be a seasonal category; apart from minor peaks during October and Febraury; the majority of the project launches occur in the Apr to Aug time frame.

- What can you conclude about the Outcomes based on Goals?
    1. Launching a project with  a goal in the "45,000 to 49,999" is the riskiest option, due to the highest rate of failures being observed in that range. Budgets of less than 10,000 or between 35,000 and 44,999 display the highest success rates and are the recommended ranges.


- What are some limitations of this dataset?
    1. This dataset only provides data relevant to the kickstarter campagin funding, it does not provide details on which productions (or kickstarter projects) were successfully launched to market; the information is only useful for analyzing what reached the funding goal.
    2. Additional information (e.g. successful launch date, "Did Product make it to Market", etc...) would allow additional analysis (e.g. do projects which have goals < $10,000 have a higher probablyity of not launching successfully, or does this result in longer launch times etc.



- What are some other possible tables and/or graphs that we could create?
    1.  The above graphs could be filtered for multiple countries, and overlaid upon each other to observe variability of trend data, per Country. This may be useful, for example, to assess if countries in the southern hemisphere (e.g. Australia) observe differing months of Theater Activity, considering the inverted seasonality.


