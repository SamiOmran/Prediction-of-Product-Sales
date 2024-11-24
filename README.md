**# Prediction-of-Product-Sales

This first project will be a sales prediction for food items sold at various stores.

# Project Phases:
## Phase |: **Inspecting Data**
We loaded the data frame using pandas and understood the records in the df.

## Phase ||: **Clean Data**
**Cleaning data passes by stages:**
- Check for duplicates
- Check for null values(missing)
- Check for appropriate data types
- Check for inconsistency values

## Phase |||: **Exploratory Data Analysis**
Create visualizations of data to understand the data and see if there is a relationship between features. Here we are presenting some of the figures we got:

![histograms](https://github.com/user-attachments/assets/828eca3c-e776-45db-809d-6e2e730c8aa7)

**From the figure above we can see the distribution for each numerical column:**
  1. For `Item_Weight` column we have more than 1400 missing values(weight = 0g), the minimum weight is 4.5g and the maximum weight is 21.35g
    
  2. For `Item_Visibility` column the distribution goes from 0.0% - 0.35%
     
  3. For `Outlet_Establishment_Year` column the range from 1985 - 2009
<br>

![heatmap (1)](https://github.com/user-attachments/assets/af71bd95-1a88-4da7-8824-917efe22c833)
**As shown in heatmap we can see:**

  1. `Item_Weight` have moderate **+ve** relation with `Outlet_Establishment_Year` (0.52)
  2. `Item_MRP` have moderate **+ve** relation with `Item_Outlet_Sales` (0.57)
