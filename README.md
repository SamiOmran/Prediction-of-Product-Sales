# **Prediction of Product Sales** 💹

This first project will be a sales prediction for food items sold at various stores.

## Content
- [Inspecting Data](#phase-1️⃣-inspecting-data)
- [Cleaning Data](#phase-2️⃣-clean-data)
- [Visualizing Data](#phase-3️⃣-exploratory-data-analysis)
  * [Histograms](#histogram)
  * [Heatmap](#heatmap)
  * [Bar Plot](#bar-plot)
  * [Scatter](#scatter-plot)

<br>

# Project Phases:
## Phase 1️⃣: **Inspecting Data**
We loaded the data frame using pandas and understood the records in the df.

## Phase 2️⃣: **Clean Data**
**Cleaning data passes by stages:** ⏬
- Check for duplicates ✔️
- Check for null values(missing) ✔️
- Check for appropriate data types ✔️
- Check for inconsistency values ✔️

## Phase 3️⃣ **Exploratory Data Analysis**
Create visualizations of data to understand the data and see if there is a relationship between features. Here we are presenting some of the figures we got:

### Histogram
![histograms](https://github.com/user-attachments/assets/828eca3c-e776-45db-809d-6e2e730c8aa7)

**From the figure above we can see the distribution for each numerical column:**
  1. For `Item_Weight` column we have more than 1400 missing values(weight = 0g), the minimum weight is 4.5g and the maximum weight is 21.35g
    
  2. For `Item_Visibility` column the distribution goes from 0.0% - 0.35%
     
  3. For `Outlet_Establishment_Year` column the range from 1985 - 2009

<br>

### Heatmap
![heatmap (1)](https://github.com/user-attachments/assets/af71bd95-1a88-4da7-8824-917efe22c833)
**As shown in heatmap we can see:**
  1. `Item_Weight` have moderate **+ve** relation with `Outlet_Establishment_Year` (0.52)
    
  2. `Item_MRP` have moderate **+ve** relation with `Item_Outlet_Sales` (0.57)

<br>

### Bar plot
![item_weight_fat_content](https://github.com/user-attachments/assets/a862e4f1-e519-4de2-805e-c37e5464eddf)

**Here we are seeing the weights based on item types:**
  - The average weight of `starchy foods` with **low-fat** content is the highest among other types. Also `starchy foods` with **regular-fat** content is the highest.
  
  - `Household`, `Health and Hygiene`, `Hard Drinks` and `others` are only `low fat` items

<br>

### Scatter plot
![item_mrp_outlet_sales](https://github.com/user-attachments/assets/97e1dc63-9fec-417d-8ea7-a20fb729f511)
From the plot, we can see that it's divided into 4 different groups, but in general, we can say that whenever the `MRP` increases the `outlet_sales` increases

