# 📱 Mobile User Behavior Dashboard

## 🎯 Objective  
The primary objective of this project was to analyze mobile user behavior to gain insights into device usage patterns, screen time, app usage, and battery drain across different age groups and demographics. Using these insights, I aimed to create a data-driven foundation for understanding how various user segments interact with their devices daily.

## 📊 Data Source  
I obtained the Mobile User Behavior Dataset from Kaggle. This dataset includes user demographics, device specifications, and behavioral metrics like screen time, app usage, and data consumption, covering 700 users across various devices and operating systems.

## 🛠️ Data Cleaning and DAX Custom Columns  
To prepare the data for analysis, I performed several data cleaning steps and created custom columns using DAX formulas in Power BI:

- **Data Cleansing**:  
   - **Standardized Column Names**: Ensured all column names were consistently formatted.
   - **Handled Missing Values**: Addressed any missing values in the dataset to avoid gaps in the analysis.
  
- **DAX Custom Columns**:  
   - **Age Groups**: Created an “Age Group” column to categorize users into age brackets (e.g., 18-24, 25-34, 35-44, etc.) for easier demographic analysis.
   - **Screen Time Categories**: Added a “Screen Time Category” column to segment users into "Low," "Medium," and "High" screen time groups based on average hours of daily screen time.

Check all the **DAX formulas and KPI measures** by clicking [here](https://github.com/KameshBhardwaj/DAX-formulas-and-KPIs-Measures).

## 📈 Visualizations in Power BI  
The Power BI dashboard includes various visualizations to illustrate key insights into mobile user behavior:

- **KPIs**:
   - **Total Users**: 700 users
   - **Average App Usage Time**: 271.13 min/day
   - **Average Screen On Time**: 5.27 hours/day
   - **High Screen Time Percentage**: 48.29%

- **Charts**:
   - **Stacked Bar Chart**: Shows user count across screen-on time categories.
   - **Clustered Bar Chart**: Displays average app usage time by age group.
   - **Stacked Bar Chart**: Compares average battery drain across age groups.
   - **Donut Chart**: Provides gender distribution by user count.
   - **Pie Chart**: Depicts the count of users by age for different operating systems.
   - **Line Chart**: Illustrates the average daily data usage by age group.

- **Slicers**:  
   Added interactive slicers for Gender, Age Group, Operating System, and Screen Time Category (High, Medium, Low) to allow users to filter and explore different segments.

## 📝 Analysis and Insights  
The dashboard reveals the following insights:

- **User Screen Time**:  
   - The majority of users (48%) fall into the “High” screen-on time category, with 338 users, indicating heavy device interaction.
   - Medium and Low screen time categories account for 219 and 143 users, respectively.

- **App Usage by Age Group**:  
   - Users aged 18-24 show the highest average app usage time at 298 minutes per day, while the 35-44 age group has the lowest average at 253 minutes.

- **Battery Drain Across Age Groups**:  
   - Battery drain is highest among users aged 18-24, with an average of 1.7k mAh per day, possibly due to increased app usage and screen time.
   - Older age groups (55+) have lower battery drain at 1.5k mAh/day.

- **Gender Distribution**:  
   - The user base is relatively balanced, with 52% male users and 48% female users, providing a comprehensive perspective on gender-related device usage patterns.

- **Operating System Preference**:  
   - Android dominates with 79.1% of users, while 20.9% use iOS, which may suggest potential areas for OS-specific feature targeting.

- **Data Usage**:  
   - Younger users (18-24) have the highest average daily data usage at 1012.96 MB/day, while users aged 35-44 use the least, averaging 855.49 MB/day.

## 💡 Recommendations for Future Analysis  
Based on the insights from this analysis, the following recommendations are proposed:

- **Personalized Features for High Screen-Time Users**:  
   Develop power-saving features and app management tools for users with high screen time, especially in the younger demographics who display higher battery drain and data usage.

- **Targeted Marketing by Age and OS**:  
   Leverage the preference for Android among younger age groups and explore OS-specific features or promotions that resonate with these demographics.

- **Engagement Programs for Balanced Usage**:  
   Promote wellness programs encouraging moderate app and screen time, potentially reducing device strain and improving battery longevity.

- **Further Segmentation of User Behavior**:  
   Conduct deeper analyses on app usage types to understand which apps contribute most to battery drain and screen time across different user segments.

## 🚀 Conclusion  
This project was a practical application of my skills in data transformation, DAX calculations, and visualization in Power BI. The Mobile User Behavior Dashboard successfully highlights behavioral patterns across demographics, offering a foundation for data-driven product development and user engagement strategies. For all custom DAX formulas and KPI measures, please refer to the dedicated folder in my GitHub repository [here](https://github.com/KameshBhardwaj/DAX-formulas-and-KPIs-Measures).
