## 3. Methodology

The dataset has already been provided; hence the data source is not required to be identified in this report. The initial step to take is to perform the pre-processing steps on the dataset, to prepare it for the data analysis methods.

### 3.1. Pre-processing Steps

#### Data Cleaning
The data undergoes cleaning to ensure accuracy and a suitable format for analysis. This involves handling missing values, removing duplicates, and addressing data quality issues. 
- Missing values can be handled by ignoring them or filling them in using estimation or prediction. 
- In this study, a few missing values were addressed through estimation. 
- Outliers were not removed, as the data appeared to be well-clustered.

#### Data Integration
Multiple datasets are merged into a single dataset, resolving inconsistencies in variable names, data types, and formats. The data analysis report combined the survey datasets into five sets, each corresponding to specific survey questions.

#### Data Transformation
Data is converted into a suitable format for analysis, and categorical variables are encoded into numerical values. 
- Fortunately, the survey data required no format changes and was ready for analysis without further modification. 
- Generalization can be applied to transform primitive data, such as converting cities to cardinal directions.

#### Data Normalization
This process involves scaling numerical features to a standardized range, making data appear similar. There are three common forms:
- **1NF**: Ensures no repeating groups.
- **2NF**: Ensures separate data with only one key.
- **3NF**: Meets all 2NF requirements while ensuring data dependency on the primary key.

For this implementation, **1NF normalization** was used (Watts, 2020).

#### Data Reduction
Data reduction helps identify essential features while eliminating irrelevant or redundant ones. 
- It can involve compressing data into lossy or non-lossy formats and reducing dimensionality to improve computational efficiency.
- By removing the CI from the tables (Deepak, 2023) (Baheti, 2021), a smaller volume of data was achieved with equivalent analytical quality.

### 3.2. Data Analysis Methods

After data preprocessing, the analysis will be performed using Google Colab, which hosts the Jupyter Notebook. Statistical analysis and data visualization will be done using the following tools:
- **Pandas**: For data manipulation, cleaning, and analysis.
- **Seaborn**: For aesthetically pleasing and statistically sophisticated visualizations.
- **Plotly**: The primary library for easy graph and chart plotting.

#### Workflow and Tools
- Initially, the plan was to use **VScode**, but Google Colab proved more convenient due to different PC setups. For larger projects, VScode remains the preferred choice.
- The dataset was saved as a Python file and submitted alongside this report.

#### Libraries and Usage
- **Seaborn**: Chosen for its simpler visualization compared to Matplotlib, which requires longer code. Seaborn provides aesthetically appealing visualizations (Pierre, 2023).
- **Pandas**: Focuses on data manipulation, cleaning, and analysis. It works well with Seaborn in a data analysis workflow (Rovira, 2021).

#### Additional Insights
As data was also cleaned and analyzed in Excel, the usage of Pandas was not as extensive as initially expected.
