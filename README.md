# linear-regression-project
  1.	Library Imports & Data Loading:
   The necessary libraries (pandas, numpy, matplotlib) are imported, and the dataset is read from a CSV file.
	2.	Exploratory Data Analysis (EDA):
	•	Basic data inspection using .head(), .tail(), .sample(), .shape, .describe(), and .info().
	•	Checked for missing values (df.isnull()) and confirmed none were present.
	•	Removed duplicates and re-checked data dimensions.
	3.	Outlier Detection and Removal:
	•	Used IQR (Interquartile Range) to detect outliers.
	•	Boxplots visualized data before and after outlier removal.
	4.	Feature Scaling:
	•	Applied both Min-Max Scaling and Standardization to normalize the numerical features (YearsExperience, Salary).
	•	These transformations ensure consistent feature scales for modeling.
