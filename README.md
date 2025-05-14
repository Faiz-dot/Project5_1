# Will the Customer Accept the Coupon?
#  Project Overview

This project investigates the factors that influence whether a customer accepts a driving coupon delivered to their cell phone. The analysis utilizes a dataset collected via an Amazon Mechanical Turk survey, detailing driving scenarios, user attributes, contextual factors, and coupon attributes. The goal is to identify characteristics that distinguish customers who accept coupons from those who do not.
Please find the project file here https://github.com/Faiz-dot/Project5_1/blob/main/Project5_1.ipynb

# Data Description
The dataset includes information on user demographics (gender, age, marital status, children, education, occupation, income, frequency of visits to various venues), contextual factors (destination, location, weather, temperature, time, passenger type), and coupon details (type and expiration time).

# Analysis Steps

Data Loading and Inspection: Read the `coupons.csv` file and examine its structure and missing data.
Data Cleaning:  Handle missing and problematic data. In this analysis, the 'car' column was dropped due to a high percentage of missing values, remaining rows with missing data were removed, and duplicate rows 
  were dropped.
  
# Data Visualization:
      Visualize the distribution of coupon types using a bar plot.
      Visualize the distribution of temperature using a histogram.
    
# Bar Coupon Investigation: Focus the analysis on bar-related coupons.
      Filter the data to include only bar coupons.
       Calculate the proportion of bar coupons that were accepted.
       Compare the acceptance rate based on bar visit frequency (3 or fewer times vs. more than 3 times a month).
       Compare the acceptance rate for specific demographic and contextual groups (e.g., frequent bar goers over 25, frequent bar goers with specific passenger/occupation combinations).
# Independent Investigation (Coffee House Coupons & other coupon types): Explore the characteristics of passengers who accept Coffee House coupons, mirroring the analysis performed for bar coupons.
       Filter the data to include only Coffee House coupons.
       Calculate the proportion of Coffee House coupons that were accepted.
       Compare acceptance rates based on Coffee House visit frequency.
       Compare acceptance rates for various combinations of user and contextual attributes (e.g., age, passenger type, income, weather, time, occupation).

 # Key Findings :

   Approximately more than 46 percent of the total observed coupons were accepted.
   Bar coupons had an acceptance rate of approximately 41 percent.
   Fo Bar Coupons:
      Drivers who visit bars more than 3 times a month have a significantly higher acceptance rate (67%) compared to those who visit 3 or fewer times a month (33%).
       Drivers who go to bars more than once a month and are over the age of 25 have a higher acceptance rate (56%) than all other groups (35%).
       Comparing the acceptance rate between drivers who go to bars more than once a month, had passengers that were not a kid, and had occupations other than farming, fishing, or forestry shows a target 
       acceptance rate of approximately 76.5 % , while other groups had a rate of approximately 35%.
       
  # Comparing more specific groups:
       
          Group 1 (Bar > once a month, Passenger not kid, not widowed): Approx. 77% acceptance rate.
          Group 2 (Bar > once a month, Age < 30): Approx. 60% acceptance rate.
          Group 3 (Cheap Restaurant > 4 times/month, Income < 50K): Approx. 45% acceptance rate.
          Similar finding where founf on Coffee House copouns.
           
# Further investigation could involve:

   Exploring the other coupon types (less expensive restaurants, carry out & take away, more expensive restaurants) to identify their specific acceptance patterns and influencing factors.
   Applying more advanced statistical or machine learning techniques to build predictive models for coupon acceptance.
   Analyzing the interactions between different features to understand how combinations of factors affect acceptance rates.
   Visualizing the distributions and relationships between more pairs of variables to gain deeper insights.



