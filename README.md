# Celebal-Assignment-04
-I have performed in-depth Exploratory Data Analysis in this assignment using Mobile dataset downloaded from Kaggle. 
- Dataset Features
   The dataset includes the following key columns:
   name – Mobile phone name
   price – Listed price in INR
   rating – Average customer rating
   reviews – Number of customer reviews
   battery, display, memory, camera – Product specs in text form
-EDA Workflow
   Data Loading & Setup
   Loaded CSV via Colab upload
   Imported necessary libraries (Pandas, Seaborn, Matplotlib)
 Initial Data Exploration
   Checked shape, data types, and missing values
   Displayed summary statistics using .describe()
 Feature Engineering  
   Extracted numerical features from text fields:
   RAM, ROM from memory
   battery_mah from battery
   screen_size from display
   rear_cam_count and front_cam_mp from camera
   Cleaned reviews and converted rating to numeric
 Univariate Analysis
   Visualized distributions using histograms and box plots
   Analyzed pricing, ratings, and screen sizes
 Bivariate Analysis
   Compared price with RAM, ROM, battery capacity, and screen size
   Plotted scatterplots for rating vs reviews 
   Enhanced clarity with transparency (alpha) and jitter (swarmplot)
 Correlation Analysis
   Created a heatmap to study relationships between numerical features
   Identified moderate positive correlation between price and RAM/ROM
-Visualizations Used
   Histograms (e.g., Rating, Screen Size)
   Box Plots (Price by RAM/ROM)
   Scatter Plots (Battery vs Price, Reviews vs Rating)
   Heatmap (Correlation matrix)   
   Outlier Detection
   Used IQR method to detect price outliers
   Highlighted unusually high- or low-priced devices

   
