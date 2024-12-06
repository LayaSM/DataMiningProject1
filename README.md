# DataMiningProject1
### Analysis of School shootings in US Statistics

This project analyzes school shooting statistics in the United States using datasets available on Kaggle. The primary goal is to explore trends in school shootings, identify patterns, and visualize data to better understand the prevalence and impact of these tragic events.

### Datasets Used

School Shooting Dataset: Provides data on school shootings, casualties, and types of schools affected.
link to the dataset: https://www.kaggle.com/datasets/cid007/school-shooting-in-us?resource=download

Shooting Situations Dataset: Details the context and situations in which shootings occurred.

Shooting Locations Dataset: Highlights locations where shootings took place.

### Preprocessing Steps

General Cleaning

1. Removed unnecessary columns (e.g., 'Number of school shootings, by type of casualty', 'Unnamed' columns).

2. Renamed columns for clarity, e.g.,

Unnamed: 2 → Deaths

Unnamed: 3 → Injuries

Unnamed: 9 → Middle Schools

Unnamed: 10 → High Schools

3. Dropped the first row containing invalid data.

4. Converted relevant columns to appropriate data types (e.g., Number of casualties from shootings to int).

5. Handling Missing and Duplicate Data

6. Checked for and removed null values.

7. Removed duplicate rows based on the School Year column.


### Processing Additional Datasets

Shooting Situations

-> Renamed columns for consistency (Unnamed: 0 → School Year).

-> Removed null values and duplicates.

Shooting Locations

-> Renamed columns for consistency (Unnamed: 0 → School Year).

-> Removed null values and duplicates.

### Data Visualization

Number of Casualties by School Year

-> A bar chart illustrates the number of casualties from shootings across school years.

-> Output File: Number of casualties from shootings.png

Shooting Situations

-> Summed up all shooting situations across categories.

-> A pie chart represents the proportions of different shooting situations.

-> Output File: shootingSituationPieChart.png

Shooting Locations

-> Summed up all shooting locations across categories.

-> A pie chart represents the proportions of shootings based on location types.

-> Output File: shootingLocationPieChart.png

### Dependencies

Python Libraries:

pandas

seaborn

matplotlib

nltk


# How to Run the Analysis

1. Download the datasets from Kaggle and place them in the project directory.

2. Install required Python libraries using: pip install pandas seaborn matplotlib nltk

3. Run the Python script to preprocess the data and generate visualizations.

4. Check the output images for insights and trends.

# Insights and Future Scope

The bar chart shows yearly trends in casualties, highlighting years with higher impacts.

Pie charts provide an understanding of the context and locations of school shootings.

Future analysis can delve deeper into correlations between various factors such as legislation, demographic trends, and regional impacts.

