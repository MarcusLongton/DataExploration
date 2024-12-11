# Coupon Analysis Project

## Project Overview
This project investigates the factors influencing customer decisions to accept or reject coupons for coupons. Using a dataset from the UCI Machine Learning Repository, we analyzed survey responses collected on Amazon Mechanical Turk. Customers were presented with various coupons and contextual scenarios, and their acceptance behavior was recorded.

---

## Objective
To explore the differences between customers who accepted (`Y=1`) and rejected (`Y=0`) coffee house coupons, utilizing Python-based data exploration, visualization, and statistical summaries.

---

## Dataset Description
The dataset includes:
1. **Customer Attributes**: Gender, age, marital status, education, occupation, income, and more.
2. **Contextual Attributes**: Destination, weather, temperature, time, and passengers in the car.
3. **Coupon Details**: Type of coupon (e.g., coffee house) and time before expiration.

---

## Analysis Methodology
### Key Steps:
1. **Data Cleaning**:
   - Addressed missing values and ensured consistent formatting.
   - Filtered dataset specifically for "Coffee House" coupons.

2. **Exploratory Data Analysis (EDA)**:
   - Explored distributions of contextual and demographic variables.
   - Visualized relationships between attributes (e.g., time of day, passenger type) and coupon acceptance.

3. **Comparison of Groups**:
   - Segmented customers into "Accepted" (`Y=1`) and "Not Accepted" (`Y=0`) groups.
   - Highlighted key differences in behavior and attributes.

4. **Visualizations**:
   - Plotted bar charts, histograms, and heatmaps to summarize trends.


## Key Findings

### Observations from the Analysis
- **Age**: There was no significant difference in age between those who accepted and those who did not accept the coffee coupons.
- **Occupation**: Students exhibited a higher acceptance rate for coffee coupons compared to individuals in other occupations.
- **Direction of Travel**: The direction of travel (same or opposite to the coupon's location) did not significantly affect coffee coupon acceptance.
- **Time of Day**: People were more likely to accept coffee coupons during the morning and afternoon (e.g.,10AM, 2 PM), aligning with typical coffee consumption patterns.
- **Weather**: Weather conditions (e.g., sunny, rainy) did not appear to influence the acceptance of coffee coupons.
- **Temperature**: Acceptance rates were slightly higher at moderate temperatures (55°F and 80°F) compared to colder conditions (30°F).

---

### Hypothesis about Drivers Who Accepted Coffee Coupons
Based on these observations, we hypothesize that:

Drivers who are students, those traveling during the afternoon, and those exposed to moderate to warm temperatures are more likely to accept coffee house coupons.

---

### Reasoning Behind the Hypothesis
1. **Students**: The higher acceptance rate among students suggests a correlation with their budget-conscious lifestyle or the association of coffee with studying or socializing.
2. **Afternoon Time**: The preference for afternoon coupon acceptance aligns with common coffee consumption patterns, such as coffee breaks during work or study sessions.
3. **Moderate to Warm Temperatures**: These conditions may encourage coffee consumption, possibly for iced or refreshing beverages.

---

### Additional Considerations
- Although weather and direction of travel did not show a strong influence, they might still play a subtle role in individual decisions.
- Further investigation could analyze the interaction between multiple variables (e.g., age, time of day, and temperature) to uncover more complex behavioral patterns.
- Machine learning techniques could be employed to predict coffee coupon acceptance with greater accuracy and uncover hidden insights.

---

This analysis provides a foundation for understanding the factors influencing coffee house coupon acceptance and lays the groundwork for more targeted marketing strategies.
